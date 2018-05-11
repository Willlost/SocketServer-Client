# SocketServer-Client
Server:
	
    Run 'SocketServerCommandCentre.exe'
	
    Run on port '8001', otherwise the server won't receive clients' packages
	
    if anyone is online, some commands are available:
	
        '/help' [command] #to get a list of commands (+options)
		
        '/kick' [option]  #to disconnect a user/all users
		
        '/ol' [option]    #to show a list of online/offline users
		
    You can send a message to all clients simply type in something without '/' at the front
	
    You will be warned if:
	
        An unknown user is trying to connect to the server
		
        Someone else is trying to log in as a user that is already online
		
        A known account is trying to log in with a bad password
		
    You will be noticed if:
	
        A known user is connected
		
        A new user is trying to register on this server
		
        A user cancells the registration
		
        A know user is disconnected
		
    
Client:

    Run 'SocketClient.exe'
	
    If you have an account:
	
        Try to log in with your username and password
		
        if you are rejected, the warning will be displayed at the top of the window:
		
            Missing Fields
			
            Bad Username
			
            Bad Password
			
            The account is already logged in
			
            Unable to connect to the server
			
    Otherwise:
	
        Click on 'Create a new account'
		
        Create your username and password
		
        Remember to confirm your password
		
        You can cancel your registration simply by click on 'Cancel'
		
        if you are rejected, the warning will be displayed at the top of the window:
		
            Missing Fields
			
            Password confirmed incorrectly
			
            Username already exist
			
        After you are registered, you will automatically connect to the server
		
    if 'keep me logged in' is checked, you will have a 'Minimize' button on your Client
	
    otherwise you will have a 'Quit' button
	
    There is only one command available:
	
        '/exit'#to exit the client when you checked 'keep me logged in'
		
