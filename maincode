score = 0

#y u snooping
import time



def leaderboards():
  
  print ("1- exit")
  print ("your score -->")
  print (score)
  print ("the charts -->")
  print ('''
    austin --> 100,116
    ryan --> 99,961
    james --> 16,915
    lilli --> 10,110
    donivan --> 5,101
    shane --> 1,010
    lincon --> 150
    davis --> 17
  
  
  
  
  
  ''')  
  leaderboardsexit = input()
  if leaderboardsexit == '1':
    maingame()
  else:
    print ("tf")
    leaderboards()





def tutorial():
  print ("tutorial")
  print ('''
  on main menu -->
  press 1 to make music-
  inside of that you will be able to make music
  press 2 to see leaderboards.
  (if you make enough music your leaderboard stat will go up)
  press 3 to come back to tutorial
  press 4 to exit

  on other menus -->

  its pretty much the same thing sooooo ye

  1- exit

  ''')
  toutorialexit = input()
  if toutorialexit == '1':
    maingame()
  else:
    print ("tf")
    tutorial()



def makemusic():
  print ("work in progress")
  print ("1- compose")
  print ("2- exit")
  makeexit = input()
  if makeexit == '1':
    global score
    time.sleep (0.01)
    score += 1
    makemusic()
  if makeexit == '2':
    maingame()
  if makeexit == 'give':
    score += 1
    makemusic()
  else:
    makemusic()


#just type maingame() to go to main menu
def maingame():
  print ("")
  print (r"""

       /$$            /$$$$$$                                   /$$          
      | $$           /$$__  $$                                 |__/          
  /$$$$$$$  /$$$$$$ | $$  \__//$$$$$$/$$$$  /$$   /$$  /$$$$$$$ /$$  /$$$$$$$
 /$$__  $$ /$$__  $$| $$$$   | $$_  $$_  $$| $$  | $$ /$$_____/| $$ /$$_____/
| $$  | $$| $$$$$$$$| $$_/   | $$ \ $$ \ $$| $$  | $$|  $$$$$$ | $$| $$      
| $$  | $$| $$_____/| $$     | $$ | $$ | $$| $$  | $$ \____  $$| $$| $$      
|  $$$$$$$|  $$$$$$$| $$     | $$ | $$ | $$|  $$$$$$/ /$$$$$$$/| $$|  $$$$$$$
 \_______/ \_______/|__/     |__/ |__/ |__/ \______/ |_______/ |__/ \_______/

                      a c̶o̶o̶k̶i̶e̶ music clicker game                                                                             
v1.0                                                        
                                                                             

  """)
  print ("1- make music")
  print ("2- leaderboards")
  print ("3- toutorial")
  print ("4- exit")
  print ("select with number")
  commandmain = input()
  if commandmain == '1':
      loading()
      makemusic()
  if commandmain == '2':
    leaderboards()
  if commandmain == '4':
    print ("bye!!")
    time.sleep(0.5)
    exit()
  if commandmain == '3':
    tutorial()    
        # end


def loading():
    numbers = ['loading.', 'loading..', 'loading...',   'loading..','loading.', 'loading..', 'loading...',   'loading..','loading.', 'loading..', 'loading...',   'loading..', 'loading.']
    for number in numbers:
      print (number)
      time.sleep(.1)


print ("welcome! do you want to join?? [y/n]")
join = input()
if join == 'y':
  time.sleep(1)
  loading()
  maingame()
#renember you can always call any function any time
#reeeeeee
