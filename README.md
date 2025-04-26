# Assignment-4-

# TASK 1:
file = open('my_file.txt','r')
reading_file = file.read()
print(reading_file)
file.close()

# TASK 2:
with open("output.txt", "w") as file:
    file.write("Hello, Python!\n")
print("Data successfully written to output.txt.")

with open("output.txt", "a") as file:
    file.write("Learning file handling in Python.\n")
print("Data successfully appended.")

with open("output.txt", "r") as file:
    content = file.read()
print("\nFinal content of output.txt:\n")
print(content)
