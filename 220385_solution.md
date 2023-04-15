# Details

Rename this file in the format `yourRollNumber_solution.md` (example, `220000_solution.md`) and submit the solution in the Google form link provided 
*** https://forms.gle/RZtKpFcKfrWrYYxF9 ***


## Your zeroth approach below

Reasoning -
First, I downloaded WSL by watching the youtube videos given in the file.
Then I run it, I got an output:"The answer of this challenge is output of "man" when run on the terminal, copy the exact output"
So I run "man" command on linux terminal and I got this.

```
What manual page do you want?
For example, try ‘man man’.
```

---

## Your first approach below (first.txt)

Reasoning -
In the code file of zeroth.c, I found a macro named clue_of_1 "not rot13 but all".
From this and from the statement "about to rotated", I was sure that i have to rotate my string.
Then I realized that there is two single character word "s" and I thought that may be either "I" or "a" but I eliminated "I" because it is capital letter.
so I rotated all character by 8 as "a" can be obtained by rotating "s" by 8.
After doing this, I got this answer.

```
noicee you did crack a rotation encryption on your own. The following is a clue for the next puzzle: CLASS of that INPUT
```

---

## Your second approach below (strings.txt)

Reasoning - I used `find` command of the linux to find strings.txt .
I typed `find ./ -name strings.txt` and I got the location of it!
Then I opened it and there was total 7 strings.
To find locations of that strings, I used `grep` command.
This command views into the files and give the file's location which contains that string.
I typed `grep -r string` and I got the locations!
The filename of the last string was the password!

```
Location of strings.txt : ./question_mark/Lamp_Stack/1/5/0/3
Location of kw4QLNylm2inErX :
      ./Lamp_Stack_task/question_mark/Lamp_Stack/final.txt
      and 
      ./Lamp_Stack_task/question_mark/Lamp_Stack/six.txt

Location of DabAWF1UenBD2W:
      ./Lamp_Stack_task/question_mark/Lamp_Stack/five.txt
      and
      ./Lamp_Stack_task/question_mark/Lamp_Stack/three.txt

Location of kPVEQPc6ZN8x2jn:
      ./Lamp_Stack_task/question_mark/Lamp_Stack/final.txt
      and
      ./Lamp_Stack_task/question_mark/Lamp_Stack/seven.txt

Location of g4JoMqFZyat9vd5:
      ./Lamp_Stack_task/question_mark/Lamp_Stack/eight.txt
      and
      ./Lamp_Stack_task/question_mark/Lamp_Stack/final.txt

Location of ORNwuwGtKDLydge:
      ./Lamp_Stack_task/question_mark/Lamp_Stack/five.txt
      and
      ./Lamp_Stack_task/question_mark/Lamp_Stack/one.txt

Location of TqMuGims7vlJtno:
      ./Lamp_Stack_task/question_mark/Lamp_Stack/final.txt
      and
      ./Lamp_Stack_task/question_mark/Lamp_Stack/ten.txt


Location of 8dc2evcCSSc4kUy:
      ./Lamp_Stack_task/question_mark/Lamp_Stack/eleven.txt
      and
      ./Lamp_Stack_task/question_mark/Lamp_Stack/final.txt
      
password for fourth.zip : eleven.txt

```

---

## Your third approach below (fourth.zip)

Reasoning -
I unzipped the file using command `unzip fourth.zip`.
I used password "eleven.txt".
I used command `grep -r DevOps{` to find file's location and string "DevOps{...}".
I got the string and its location!

```
File location : ./Lamp_Stack_task/question_mark/get-in/4/2_inner/0.txt
String : DevOps{y0ur3_4w350m3_4nd_0ne_5t3p_c1053r}
```

---


- Name : Dobariya Jenil Bharatbhai
- Roll : 220385
- GitHub username: Jenil-Dobariya
- Discord username: Jenil_D#1156


## Do not tamper below this line

---

Q29yZSB0ZWFtIGtvIGZha2UgZG8=
