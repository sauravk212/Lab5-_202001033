# Lab5-_202001033
Date: 15/03/2022

## Tool <br>
        pylint
        
        
## Github repo link 
  https://github.com/geekcomputers/Python

##  1 

## Error Snippet : 
![error1](https://user-images.githubusercontent.com/117855894/225277905-b41b4302-978b-4e98-b0f9-4b2e6056dac5.PNG)

## Code Snippet : 
![code1](https://user-images.githubusercontent.com/117855894/225278340-f4539171-a3f1-4ba6-9b46-62e04a871e79.PNG)

- Pylint throws errors that some of the files are missing docstrings.
- pylint complains String statement has no effect (pointless-string-statement) for the doc string at the top of the module file.


## 2 

## Error Snippet : 
![error2](https://user-images.githubusercontent.com/117855894/225278809-75984511-6567-4fc7-9406-68a713cbcef1.PNG)



## Code Snippet : 
![code2](https://user-images.githubusercontent.com/117855894/225279113-1a15f3ec-230c-4c7e-a80a-b24d8d05e55b.PNG)

- As this code is not contained in a class or function it is expecting those variables to be constants and as such they should be uppercase.

## 3 


## Error Snippet :
![error3](https://user-images.githubusercontent.com/117855894/225279944-c15df0cd-ccc0-4401-8cc2-7d3edae4bb54.PNG)

## Code Snippet : 
![code3](https://user-images.githubusercontent.com/117855894/225279888-989af047-618c-4c7e-90f5-81a84a3fb0c4.PNG)

- Used when the name doesn't conform to naming rules associated to its type (constant, variable, class...)

## 4 

## Error Snippet :
![error4](https://user-images.githubusercontent.com/117855894/225280495-d2aad5fb-280a-45f4-8d12-d3e0442cc449.PNG)


## Code Snippet : 
![code4](https://user-images.githubusercontent.com/117855894/225280573-47b12a53-28ba-478c-9692-5b04386fe310.PNG)


## 5 

## Error Snippet :
![error5](https://user-images.githubusercontent.com/117855894/225282082-c0c27b43-1af6-4816-b2ed-cd1a657a6fb1.PNG)

## Code Snippet : 
![code5](https://user-images.githubusercontent.com/117855894/225282162-76020199-d59f-4afe-834c-82a96d123be9.PNG)

- The purpose of an else block is to define code that will not be executed if the condition is true, so execution wouldn't continue on to the next block.
However, in this code, the main conditional block has a return statement, meaning execution will leave the function, so there's no need for an else block: all subsequent code after the return will, by definition, not be executed if the condition is true. It's redundant. It can be replaced with a simple if.

