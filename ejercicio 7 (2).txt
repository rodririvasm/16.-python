celsius=int(input("introduce los grados en celsius:"))    


for i in range(10,55,5):    ###comentario -->  for(i=10;i<=55,i+=5)
    if 10<=celsius<=50: 
        celsius=i
        fahrenheit=((9/5)*celsius+32)
        print("celsius:"+ str(celsius)  + "  Grados fahrenheit:  "+  str(fahrenheit))  