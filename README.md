#Vue and .Net Api and Data stored in memory
Example Project on how to develop and Build Vue App with DOTNET Web API
<br>
To run the Project on the backend(API) you need to navigate to the direcory of the cloned Project and hit:<br>
dotnet <br>
from command Line or PowerShell.The command runs the .csproj you need<br>
<hr>
Then for the client side you need to type the following commands:<br>
cd clientapp <br>
  npm install <br>
  npm run serve <br>
  ...to transfer all the environment you need fot the client side to run on a browser<br>
  You will get the address you need to witness the tiny UserCount app.
  The users are stored and retrieved from memory.<btr>But, still, it counts as a
  server-client app
<hr>
  
For my case, specifically i had to also set a parameter.Namely:<br>
set  NODE_OPTIONS=--openssl-legacy-provider <br>
berfore npm start<br>
I have a hunch that this lowers security however.It would be best to 
'set' and 'unset' the parameter after installing and using the client respectively.
