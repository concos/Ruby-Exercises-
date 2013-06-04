def conversion(op)
  case op 
	when '1'
		'add'
	when '2'
		'subtract'
	when '3'
		'multiply'
	when '4'
		'divide'
	end
end

def symbol(sym)
	case sym 
	when '1'
		'+'
	when '2'
		'-'
	when '3'
		'*'
	when '4'
		'/'
	end
end

puts "What is your name:"
name = gets.chomp 

puts "What is the first number" 
first_number = gets.chomp

puts "What is the second number"
second_number = gets.chomp 


puts "What would you like to do? 1) add 2) subtract 3) multiply 4) Divide"
operator = gets.chomp 

if operator == '1'
	result = first_number.to_i + second_number.to_i
elsif operator == '2'
	result = first_number.to_i - second_number.to_i
elsif operator == '3'
	result = first_number.to_i * second_number.to_i
else operator == '4'
	result = first_number.to_f / second_number.to_f		
end 

puts "You chose to #{conversion(operator)} #{first_number} #{symbol(operator)} #{second_number} Result: #{result}"
 
