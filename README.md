# TrainDatabase

Hiya, This is simply a readme file that will go over all of the functionality of all of our included files
Included with this file youll find all of the associated files, but since they are so large you probably wont want to do everything. 
Thus we have this tutorial on what to look for and how to use the interface.

!!!!!Firt Of all the database is called Train_Boys we were unable to rename it but hopefully the name is easy enough to find.!!!! 
This Database was designed and created by John Glover and Philip Maphey.

1) All of the SQL data are within the DDL, DML, and ImportedData files, these files include both
implemented and non implemented queries. 
2) The Train_Boys.json file is simply the document database that holds any user login informaton for our database
3) To make it easier on your brain, ill quickly go through a tutorial to simplify down our python interface

IF you would like to change between any of the user types, !!! RESTART THE PYTHON FILE!!!
Furthermore, on any errors simply restart the python. Sometimes it throws weird errors if you input too many times, accidentally 
put to many spaces, or input too much information too fast
Passenger Use )

The first option avaliable is the passenger option. On selecting 1 you will be prompted to choose either to add in a new user or log into an existing user
Our suggestion is to log in as a new user and add in a password, first name,and last name
Then after completing this it will write out to both the passenger table in the database and the passenger
section of the json file. 

Then if you go back and restart the file log in as yourself. This will only work if you restart the python 
this is because it doesnt recognize that the new user had been added into the json file, so it wont let you log in

After you have successfully logged in, select any of the 4 stations as wanted.
Then for Selection -  1) Input P28-C145 which is an existing trip ID.
                      2)Input P28-C145 as the TripID, SeatGeek as the Supplier ID, and 12/11/2022 as the date. 
                      You will then be able to look into the ticket table and see the new ticket that was just purchased by YOU!
                      3) Input again P28-C145
                      These are not the only trip_ids, supplier ids, and dates that will work, but these are the ones we tested with 

Staff Option 2) - Staff ID : Robert , Password : Christmas (Again you can log in as any of the existing staff users as stated in the json file, this is justone we chose for you)
Then again, select any of the 4 stations - 
                      1) Use jmglov19 as the passenger id
                      2) Use 12/11/2022 as the date
                      3) simply selecting will do the trick
As you can see, we are re-using the same information to prove that they are all connected. Just as our ER diagram shows

Mechanic option 3) - Mechanic ID: Charlie, Password : Charles - Select any of the stations
                    1) Use Syra81 as the train shed id
                    2) Just the selection works 
                    3) Similarly just the selection itself works
Thank you again for using our first ever instance of Thomas3000 - The train station database
