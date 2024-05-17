# 6th
#customer classes and the parameters with new methods
class Customer  
@@total_customers = 0  
def initialize(name, age)  
@name = name  
@age = age  
@@total_customers += 1  
end  
def display_details  
puts "Customer Details: Name - #{@name}, Age - #{@age}"  
end  
def total_no_of_customers  
puts "Total number of customers: #{@@total_customers}"  
end  
end  
# Creating two objects of the Customer class  
cust1 = Customer.new("vijay", 21)  
cust2 = Customer.new("shivaji", 20)  
# Calling methods on the objects  
cust1.display_details  
cust1.total_no_of_customers  
puts "\n"  
cust2.display_details  
cust2.total_no_of_customers 
