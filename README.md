# vue-dotnet-example
Example Project on how to develop and Build Vue App with DOTNET Web API

To run the Project on the backen(API)d you need to navigate to the direcory of the cloned Project and hit
dotnet 
from command Line or PowerShell.The command runs the .csproj you need

Then for the client side you need to type the following commands
cd clientapp 
  npm install 
  npm run serve 
  ...to transfer all the environment you need fot the client side to run on a browser
  You will get the address you need to witness the client-server tinyapp

For my case, specifically i had to also set a parameter.Namely
set  NODE_OPTIONS=--openssl-legacy-provider npm start
I have a hunch that this lowers security however.It would be best to 
set and remove the parameter after installing and using the client respectively.
