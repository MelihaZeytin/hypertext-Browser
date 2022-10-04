# Hypertext Browser

**Task**: Write a basic hypertext browser that supports colored text and hyperlinks. A hypertext document is composed of basic text documents that reside in the same directory and refer to each other in hyperlinks.
A hyperlink looks like:  [label comes here| file_name  ].

A hyperlink looks green on the screen and opens the indicated file when selected (move  the cursor over it and press enter).

A **comment** looks like:  /* Any comment text here */

Comments do not appear on the screen. 

Red text looks like: [red] This is normally written in red. [end_red]

Blue text looks like: [blue] This is normally written in blue.[end_blue]

**Input**: Prompt for the source file name. Get the source file name from the user. Assuming the user gave the name x, you should open and read the source file with the extension “.htx” like x.htx. 

**Output**: Your program should print the output of the htx document on the screen. Text annotated as red and blue should be printed using red and blue characters. Comments should not be printed. (comments are ignored) When the cursor is placed over a hyperlink and enter is pressed, your program should open the referred text file in another console window. 

**Language**: C (strictly)

-----------------------------------------------------

## Çıktılar

### Dosya girdisi
![image](https://user-images.githubusercontent.com/109876399/193850339-6a657848-bf2d-46d1-a774-1c720be2fec7.png)
![image](https://user-images.githubusercontent.com/109876399/193850365-04e32e51-55d9-40b1-8cc8-b014428238da.png)
![image](https://user-images.githubusercontent.com/109876399/193850387-f4c68a39-7212-4369-a7a3-b73d0f33bfd8.png)

### Konsol çıktısı
![image](https://user-images.githubusercontent.com/109876399/193850520-a5386f9d-447f-4ec9-853c-d69940eafe3d.png)
