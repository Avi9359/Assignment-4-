# Assignment-4-
#TASK 1 
file1 = open("my_file.txt","r")
reading_file = file1.read()
print(reading_file)
file1.close()


# TASK 2
text = input("Enter text to write to the file:")
with open("output.txt","w") as file:
    file.write(text + "\n")
print("Data successfully written to output.txt.")

more_text = input("\nEnter additional text to append: ")
with open("output.txt", "a") as file:
    file.write(more_text + "\n")
print("Data successfully appended.")

print("\nFinal content of output.txt:")
with open("output.txt", "r") as file:
    content = file.read()
    print(content)

