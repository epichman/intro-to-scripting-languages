# intro-to-scripting-languages
Class
import valentine

def valentine_function(): # function doesnt matter, as long as it is called again later
    print "Valentine's Day is %s" % valentine.how_many_days_away()
    print "I can't believe Valentine's Day falls on a %s this year! There won't be "\
           "an open table at a restaurant until midnight!" % valentine.which_weekday()
		   
		   
print "Wait! I can't remember how many days away it is till Valentine's Day.\n"
print "How many days away is Valentine's Day?"

valentine_function() #to call the function again just type and end with () 


def favorite_candy(candy_name):
    print "Go ahead and buy %s for yourself, you deserve it!" % candy_name

def more_cowbell():
    print "I've got a fever, and the only prescription is more cowbell!"
    print "Or Valentine's Day candy!"
    candy = raw_input("What is your favorite candy? ")
    favorite_candy(candy)
	
more_cowbell()
