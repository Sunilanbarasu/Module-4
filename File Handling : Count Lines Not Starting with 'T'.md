---

# Python Script to Reverse File Contents and Save to Another File

## 🎯 Aim
To write a Python program that reverses the contents of a file and saves the reversed content into another file.

## 🧠 Algorithm
1. Create a function `create_file(file_path, content)` to write the given content into a file.  
2. Create a function `reverse_file_content(input_file_path, output_file_path)` to:  
   - Read the content of the input file.  
   - Reverse the content using slicing (`[::-1]`).  
   - Write the reversed content into the output file.  
3. Create a function `read_file(output_file_path)` to read and return the content of the output file.  
4. Get input content from the user, create the input file, reverse its content, and display the reversed result.  

## 🧾 Program
```python
def create_file(file_path, content):
    with open(file_path, 'w') as file:
        file.write(content)

def reverse_file_content(input_file_path, output_file_path):
    with open(input_file_path, 'r') as file:
        content = file.read()
    revcont = content[::-1]
    with open(output_file_path, 'w') as file:
        file.write(revcont)

def read_file(output_file_path):
    with open(output_file_path, 'r') as file:
        content = file.read()
        return content

# Example usage
input_file_path = 'test_case_1.txt'
output_file_path = 'reversed_1.txt'
file_content = input("Enter file content: ")
create_file(input_file_path, file_content)
reverse_file_content(input_file_path, output_file_path)
print(read_file(output_file_path))
```

## 🖥️ Example Output
<img width="1545" height="827" alt="image" src="https://github.com/user-attachments/assets/57c5d7e3-37f4-4165-aace-b13445bb264b" />



## ✅ Result
Thus, the program has been successfully executed to reverse the contents of a file and save it to another file.

---
