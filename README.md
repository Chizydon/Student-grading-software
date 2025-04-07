grade.py
score = int(input("Whats your score \n"))
if 90 <= score <= 100:
   print("Your possition is excellent")
elif 80 <= score < 89:
   print("very good")
elif 70 <= score < 79:
   print ("good")
elif 60 <= score < 69:
   print ("satisfactory")
elif 50 <= score < 59:
   print ("needs improvement")
elif 0 <= score < 49:
   print("fail")
else:
   print ("invalid score, input a number between 0 to 100")
