import socket
from time import *
from datetime import datetime
import sys
#####################################

 #  #   #####    ####    #########
 #  #   #        #   #   #       #
 ####   #####    ####    #       #
 #  #   #        #  #    #       #
 #  #   #####    #   #   #########
 
##############
import Banner#
##############

print ('welcome to my tool... ') 

print ('please select') 

print ('1: find ip')

print ('2: port_checker') 

print ('3: email extractor') 
##########################

a = input ('===> ') 

if (a) == '1' :
    
    print ('this tool was made by HERO' ) 
    
    print ('Pleas enter target name')
    
    hostname = input ('===> ')
    
    ip=socket.gethostbyname(hostname)
    
    print     ('host name is: ', hostname, '/n', 'HOST IP IS: ', ip)
####################################
elif (a) == '2':
    
##############################
#Update HERO Script to v 1.5 #
##############################

    print ('welcome') 
    ip = input ('===> ENTER YOUR IP TO START: ')
    t1 = datetime.now()
    print("Scanning Start.. %s Please Wait.. " %ip )
    sleep(1)
##############################
    try:
        for port in range(1,6553):
            s=socket.socket(socket.AF_INET,socket.SOCK_STREAM)
            if(s.connect_ex((ip,port))==0):
                try:
                    serv=socket.getservbyport(port)

                except socket.error:
                    serv="Unknown Service"
                print ("Port %s Open Service:%s "%(port,serv))
            t2=datetime.now()
            t3=t2-t1
        print ("Scanning Completed On %s"%t3)
    except KeyboardInterrupt:
        print("See You Soon....!")
###############################
#update HERO script to V 2    #
###############################

elif (a) == '3':
    A = '\033[1;31m'
    B = '\033[1;32m'
    C = '\033[1;33m'
    print (A)
    name = input ('enter name===> ')
    print (B)
    email = input ('enter email===> ')
    number = 1949
    while number<2100:
        number=number+1
        print (C)
        print(name+str(number)+email)
    print('email extraction done')
###############################
        

