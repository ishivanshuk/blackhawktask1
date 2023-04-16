# blackhawktask1

in the folder where file is present: 

For windows
shift+rightclick -> windows power shell -> 
Run the following code
icacls.exe “drawing-app” /reset
icacls.exe “drawing-app” /grant:r “$($env:username):(r)”
icacls.exe “drawing-app” /inheritance:r

For Linux/Ubuntu
Run chmod +x drawing-app.py

run app using ./drawing-app.py 
