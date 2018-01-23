
MEAN videos
CODE SCHOOL
CALCULATOR



<< MVC in The FULL STACK >>
Stores Data | Authentication | the Front-end is totally static | 

mvc organizes full-stack. 


<Problem> 
        DIRECT ACCESS IS A PROBLEM!! THAT MEANS ITS PUBLIC
            an html that can access the database is dangerous. You black people with a server </problem>
            only the server passes info
            but user needs to send stuff and access stuff "show all pics of sloths in database" 
</problem>

M   Model   (Database) >>>>> [DataBase]
V   View    (out-facing whatever) >>>> [FrontEnd]
C   Controller (mediator/filter) >>>> [BackEnd]

<broad picture> User (MAKING REQUESTS AND RECEIVING RESPONSE) | Browser | VIEW (FACE OF APP | PRODUCT) | CONTROLLER (SERVER | TAKES ORDERS TO BUILDS AND SENDS INFO) | MODEL (DATABASE) |
</broad>


M - MongoDB     
            >>>>> [DataBase]
                - MODEL
                    database stores your app
E - Express.js 
            >>>>> [ROUTER(inside of controller)]
                - VIEW and CONTROLLER 
                    (parses the request sent from the user through the browser)
                    (passes the request on to the CONTROLLER(S))
                    provides more robust features to your web app (WhateverTF that means)
A - Angular.js      
            >>>>> [sends results] 
                - VIEW
                     allows for expanded html library
N - Node.js     
            >>>>>   [] 
                - CONTROLLER
                    (does processing)
                    framework for fast scalable network 
                    Invented to help with file upload/downloads
                    


Streams - 

        [Like Channels that send data in chunks]
        [Readable Writeable or Both]
        
        Read from the request a readable stream from an event emitter
        Communication happens because of fired events
        Readable Stre

NODE - CAN CREATE A FILE UPLOAD WITH PROGRESS

Express - Easy route to URLs to Callbacks
            Middleware(from Connect)
            Environment based configuration
            Redirection helpers
            File Uploads