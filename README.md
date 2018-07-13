# Java_EE_Udemy14
Injecting an EJB Servlet

#Cannot use FlightService keyword to create a new FlightService object
#Need to ask EJB container that manages the class to provide a new FlightInstance object

#Created a new servlet FlightDetails
#inside servlet declared private FlightService fs; with @EJB above to link 

#Inside the doGet method wrote to PrintWriter getAirplaneModel() and getFrom() 
#run in browser localhost:8080/ejb2/FlightDetails
#prints out:
#The flights details servlet has been called.....
#Boeing 787
#Los Angeles
