# shadyrest
Capstone Project for Per Scholas Full Stack Java Developer class 118


This project uses Java EE, MySql, Maven, JPA and JSPs to create a "proof of concept" site that facilitates the logging of service providers in assisted living facilities via bar-coders.

This is just a proof of concept.

Included in the repository are the SQL scripts needed to create the needed "MySql" database (named shadyrest),  populate it with a couple of Admins, RAs and resdients.

Note:  If you don't have a bar-code reader to log your own incidents, simply use the following Key:

Role/Inciden          Keyboard Code:
Admin                 ST-xxxxxx           (where xxxxx is a string of 0s padding the id) ... i.e.   ST-000001  is the #1 admin.
RA                    ST-xxxxxx
Resident              RS-xxxxxx
Service               VB-xxxxxx
Incident              IN-xxxxxx

It may be noted that 3of9 barcoding starts and terminates each code with an "*".  These are stripped prior to transmission.  

So - on paper the code printed is actually:   *ST-000001*  for admin #1.

