def operands()

    puts "Input first number"
    
    operand1 = gets.chomp.to_f

    puts "Input second number"

    operand2 = gets.chomp.to_f

    puts "Choose an operator. [*+-/]"
    run = 1

    while run == 1
    operator = gets.chomp


        if operator == "+"
            puts "#{operand1} + #{operand2} is #{operand1 + operand2}"
            run = 0
       
    
        elsif operator == "*"
            puts "#{operand1} * #{operand2} is #{operand1 * operand2}" 
            run = 0
       

        elsif operator == "-"
            puts "#{operand1} - #{operand2} is #{operand1 - operand2}"
            run = 0
       
    
        elsif operator == "/"
            puts "#{operand1} / #{operand2} is #{operand1 / operand2}"
            run = 0
    
     end
    
    end

end
    
operands()
