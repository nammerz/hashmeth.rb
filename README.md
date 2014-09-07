hashmeth.rb
===========

school = {general_ed: "k thru 8",
			highschool: "9 thru 12",
			college: "degrees, masters, phd"}

school.each_key {|k| puts k}
school.each_value {|v| puts v}

school.each {|k,v| puts "i can achieve anything as long as i go to #{k} " +
		"and pass my #{v}," }
