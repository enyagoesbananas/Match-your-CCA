# CCA Personality Matching Test
print("Title of program: CCA Matching Personality test")
print()
print("Welcome to DHS! Please answer the following questions truthfully and we'll suggest a CCA for you!")
print("Please respond with a number 1 - 5, where 1 is strongly disagree and 5 is strongly agree.")
print()

tech1 = input("I enjoy building and fixing things.")

outdoor1 = input("I'll go crazy if I am not out of the house for the whole day. I ike the outdoors very much.")

music1 = input("I can see colours in my mind and feel very energised when i hear music.")

tech2 = input("I know how to build apps and websites, and work very well with computers")

outdoor2 = input("I'm good with tying knots and ropes, and am interested to learn survival skills.")

music2 = input("I play a musical instrument well and am passionate about it.")


tech_final = int(tech1) + int(tech2)
outdoor_final = int(outdoor1) + int(outdoor2)
music_final = int(music1)+ int(music2)

print()

if tech_final > outdoor_final and tech_final > music_final:
  print("You might be suitable for Infocomm club!")
elif outdoor_final > music_final:
  print("You might be stuiable for ODAC!")
else:
  print("You might be suitable for Band!")

  
