#Write a script to compare two floating point numbers and print the larger number using the ternary operator. [x = 4.567, y = 4.568]

set x 4.567
set y 4.568
set z [expr ($x > $y ? $x:$y)]
puts $z

puts "\n"

#Write a TCL script that checks if a number is positive, negative or zero using the ternary operator

gets stdin a

set result [expr {$a > 0 ? "Positive" : ($a < 0 ? "Negative" : "Zero")}]

puts "The number is: $result"


#Modify the script below to use a ternary operator instead of if- else

		#set a 10
		#set b 20
		#if {$a > $b} {
			#puts "A is greater"
			#} else {
			#puts "B is greater"



puts "\n"

set a 10
set b 20
set c [expr ($a>$b ? $a:$b)]
puts "the greatest number is :$c"
