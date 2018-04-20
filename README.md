# RexRAT
RexRat is Remote Administration Tool. The package includes:    
1.ReXCrypter - 1/38 Crypter for your server.   
2.ReXStub - Very good stub  
3.Embedder - Used for embedding ip of C&C into file.  
4.ReXCore - Command and Control program  
5.ReXServer - Server (the virus :D)  
# Peparing RexCore  
1.Please run RexCore.exe and go to Listener.  
2.Write port number (Currently it must be **1223**, port changing will work in next version) and click add  
3.RexCore is ready. Please restart it.  
# Preparing RatServer  
1.Run Embedder.exe and write path to server (RATSERVER.exe)  
2.Write your ip (external if you plan on using it on WAN)  
3.It will create file saved.exe   
4.Now crypt the file.  
5.Run ReXCrypter and write path to file saved.exe.   
6.Now write path to stub (ReXStub.exe).  
7.It will create file Ready.exe (This is your encrypted virus)  

# Usage
Run RexCore and Ready.exe(the virus).   
Now your infected computer will show in the connections tab.  
If you want to control it, then click on ID of any computer.  
And now I think you know what to do :DD  

# What not to do.
When you start keylogger your app will freeze. It is normal. I didn't set it up as asynchronous task so it will freeze. (I will change it in another update). The same is when you are downloading files.
