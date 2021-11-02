user_number = int(input("تعداد کاربران بازی را وارد کنید "))
if 2< user_number <12 :
     user_information = [ ]
     counter = user_number
     c_name = 1
     user_information_location =( user_number+1)
     while   counter !=0 :
         user_information.append({
             'name' : input("   player    "+ str(c_name) +"    whats your name   :) "),
             'age' : int(input("    player  "+ str(c_name) +"  whats your age  :)")),
             'user_mood' : 0,
             'user_pass1' : 0 ,
             'user_pass2' : 0 ,
             'user_pass3' : 0 ,
             'user_pass4' : 0
         })
         if user_information[user_information_location]['user_mood'] == 1:
             user_information[user_information_location]




         counter = (counter -1)
         c_name = ( c_name + 1)









else :

    print ("حداکثر تعداد شرکت کنندگان 11بازیکن میباشد و حداقل تعداد 3 نفر میباشد  :((((    !!!!!!!!")


nobat = 0
while nobat < 3 :
   ferst_caracter = input(user_information[nobat]['name'] + "     enter the ferst carakter to start :))))))    " )
   if len(ferst_caracter) == 1 :
       nobat = (nobat + 1)
   else:
       print("pleas enter just 1 cracter :)")


counter_w = 0

while  0 <= counter_w <user_number  :
       if user_information[counter_w] ['age'] == 9826353 :
           user_information[counter_w]['user_mood'] = 1
           user_information[counter_w]['user_mood'] = 1
           counter_w_copy = counter_w
       elif user_information[counter_w]['age'] == 1190276526:
           user_information[counter_w]['user_pass1' ] = 1
           user_information[counter_w]['user_mood'] = 1
           counter_w_copy = counter_w
       elif user_information[counter_w]['age'] == 1371379:
           user_information[counter_w]['user_pass2'] = 1
           user_information[counter_w]['user_mood'] = 1
           counter_w_copy = counter_w
       elif user_information[counter_w]['age'] == 5683403 :
           user_information[counter_w]['user_pass3'] = 1
           user_information[counter_w]['user_mood'] = 1
           counter_w_copy = counter_w
       elif user_information[counter_w]['age'] == 9382718096 :
           user_information[counter_w]['user_pass4'] = 1
           user_information[counter_w]['user_mood'] = 1
           counter_w_copy = counter_w

       counter_w = (counter_w +1)

print(user_information[counter_w_copy]['user_mood'])

"""while  0 <= counter_w <user_number  :
       if user_information[counter_w] ['user_mood'] == 1 : 
          user_ematyasz = (user_ematyasz  + 5 )   خب  ببین حلقه هایی که داریم مربوط به کار های مختلف میباشد بنا براین وقتی سیستم امتیاز دهی و جحدل و رتبه بندی را درست کردی برای هر یک از عملیات ها یک جمله شرطی در حلقه فوق اضافه حواهیم کرد و ارزش مرب.طه را هم در یوزر اینفور میشن 1 خواهیم کرد      """





