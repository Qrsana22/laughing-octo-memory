#XYZ
import sys,time,socket,os
os.system('clear')
def slowtype(text,sec):
    for d in text + "\n":
        sys.stdout.write(d)
        sys.stdout.flush()
        time.sleep(sec/100)
        #############
slowtype("""\033[;33;1m  
__  ___   _______  _____ ___   ___  _     
\ \/ \ \ / |__  / |_   _/ _ \ / _ \| |    
 \  / \ V /  / /    | || | | | | | | |    
 /  \  | |  / /_    | || |_| | |_| | |___ 
/_/\_\ |_| /____|   |_| \___/ \___/|_____|""",2)
slowtype("""_____________________________""",2)
print('')
slowtype ('''\033[33;1m WELCOM TO V1 OF XYZ TOOL''',3)
slowtype("""___________________________________""",2)
print("")
slowtype("""\033[36;1m
____________________________________________

    please enter number only :
        
    1-Html              10-input text.
    2-UTF-8.            11-input serch.
    3-table.            12-input email.
    4-img.              13-input password.
    5-video.            14-input checkbox.
    6-adio.
    7-hayper link.
    8-headers.
    9-javascript.
   
___________________________________
""",3)
###########################
while True :
 html = input(' \033[32;1mwhat do you want :) ')
 if html == "1" :
     slowtype ('''
     <!DOCTYPE html>
     <html>
     <head>
     <meta http-equiv="Content-Type" content="text/html;charset=UTF-8">
     <meta name="description" content="i love my website">
     <meta charset=""
     <title></titlele>
     </head>
    <body>
    /body>
    </html>
 ''',3)
 #########################
 if html == "3" :
  slowtype('''
      <table border="1">
     <thead>
     <tr>
     <td>																		
     </td>
     </tr>
     </thead>
     </table> ''',3 )
 
 ############################
 if html == "4" :
  slowtype (""" <img src="" alt="" > """,3 )

 #############################
 if html == "5" :
     slowtype ('''
     <video controls>
 	<source src="" type="">
	 </video> ''',3)

 ##############################
 if html == "6" :
     slowtype ('''
     <audio controls>
	 <source src="" type="">
 	</audio> ''',3 )

 ##############################
 if html == "10" :
     slowtype ('''
      <input type="text"placeholder="" > ''',3)
 ##############################
 if html == "8" :
     slowtype(''' <h1></h1>
 	 <h2></h2>
 	 <h3></h3>
  	<h4></h4>
  	<h5></h5>
	  <h6></h6> ''',3)
 ##############################
 if html == "7" :
     slowtype(''' <a href=""></a> ''',3)
 ##############################
 if html == "9" :
    slowtype(''' <script></script> ''',3)
 ################################
 if html == "2" :
   slowtype(''' <meta charset="UTF-8"> ''',3)
 ####################################
 if html == "11":
  slowtype(''' <input type="search"placeholder="" > ''',3)
 ######################################
 if html == "12":
  slowtype(''' <input type="email"placeholder=""> ''',3) 
 ######################################
 if html == "13":
  slowtype (''' <input type="password"placeholder="" > ''',3)
 #####################################
 if html == "14":
  slowtype (''' <input type="checkbox" name="" id=""> ''',3)
