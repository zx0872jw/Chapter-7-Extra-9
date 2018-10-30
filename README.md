# Chapter-7-Extra-9
string = input("Enter a string: ")
vowels = 0
consonants = 0
for i in range(len(string)):
    if(string[i] == 'a' or string[i] == 'e' or string[i] == 'i' or string[i] == 'o' or string[i] == 'u' or string[i] == 'A' or string[i] == 'E' or string[i] == 'I' or string[i] == 'O' or string[i] == 'U'):
        vowels += 1
    elif not string[i] == ' ':
        consonants += 1

print("Number of vowels are:",vowels)
print("Number of consonants:",consonants)
