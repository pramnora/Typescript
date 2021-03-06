# Typescript
My Typescript code

## About

Typescript, is a 'superset' of Javascript; meaning it does everything that plain vanilla Javascript can do, and, 'more'...with additional features having been added on; including such things as data type checking:  

- string  
> let varName: string;  
- number  
> let varName: number;)  
- boolean 
> let varName: boolean;  
- any     
> let varname: any;  
- /-etc.    

This language is also frequently used with many modern day Javascript frameworks including, Angular 4.  

Basically, Typescript source code files [.ts] are, later on, translated/compiled into becoming plain vanilla [.js] files; the which plain [.js] file can then be linked to and used inside of HTML web pages.  

## Setting up the Typescript programming environment to work on Windows 10...

The hardest part of learning any 'new' programming language by far is learning how to complete doing it's initial set up on your own computer system. Once that part has already been completed; and, you've both written/run your initial, 'Hello, world!', test program which successfully worked; then, the rest of the learning process is pretty much a breeze; namely, find/follow tutorials/and, do sufficient 'practice' so  that you can get to know/and, remember commands.  

1> Download NodeJS from...  
http://www.nodejs.org  
...or, if you already have it installed; then, you might need to 'update' to the lastest NodeJS package...  
> C:\> npm i -g npm  

2> Use NPM/Node Package Manager to install Typescript to work globally on your computer system...
> C:\> npm install -g typescript  

3> Create an empty folder on your C:\ drive; call it...  
Typescript  
...inside of the Typescript folder create the following files...  
a> ts01.html  
Create a [barebone.html] skeleton file tags structure inside of [ts01.html]/and, also, add a pair of script tags inside of the head section which points to the file: [ts01.js]  
> <script src="ts01.js"></script>  
b> ts01.ts  
...simpy write 1 line of code...  
> console.log("Hello, world! from Typescript");  

4> Open up a DOS black screen CLI/Command Line Interface window...  
and,cd /change directory to where the 'new' folder called: Typescript, is located on your system:  
> C:\Typescript>  
...next, type in after the DOS prompt: (>)...  
> C:\Typescript> tsc ts01.ts  
...if everything has been set up to work, successfully; then, the file [ts01.ts] should get compiled into becoming [ts01.js]    

**NOTE**: The term: 'tsc', is short for Typescript Compiler.  

5> Left double click on the file called: [ts01.html] to open it for viewing inside of your web browser; and, press key [F12]...this opens up Google Chrome Console...which shows the [ts01.js] output to the console:  
> Hello, world! From Typescript  

Warmest congratulations, your computer can successfully compile Typescript files: [.ts] into becoming Javascript files: [.js]; and, you are now ready to 'practice' writing Typescript code.  

**NOTE**: In order to find which version of Typescript you are using...  

> C:\Typescript> tsc --version  
> Version 3.6.4    (...as of date: 221019)  

**NOTE**: The line:  

> console.log('Hello, world...');  

...is NOT actually Typescript code; but, instead, it's just plain vanilla Javascript; -(bear in mind, that Typescript can do anything that Javascript can do; but, not vice versa)- ; however, if this example does work; then, that proves your [ts01.ts] file did compile successfully to become [ts01.js]; and, so, now, you're ready to 'start' learning Typescript. 

**NOTE**: You can avoid repeatedly having to save as: [filename.ts]/then, compile using: tsc filename.ts...; by using switch [-w] which will, automatically, watch/compile.   

> tsc filename.ts -w  

...it's possible to watch more than one typescript file: [.ts] all together at once, use...

> tsc filename1.ts filename2.ts -w

...also, remember to hit [CTRL]+[C] to whenever you wish to cancel watching.  

## Links...

Typescript links...  
- https://en.wikipedia.org/wiki/TypeScript  
- https://www.typescriptlang.org/  
- https://github.com/Microsoft/TypeScript  
- https://www.npmjs.com/package/typescript  
-- https://www.typescriptlang.org/play/  (practice doing Typescript coding online inside of your browser)      

### Videos...

Learn TypeScript in 50 Minutes - Tutorial for Beginners  
- https://www.youtube.com/watch?v=WBPrJSw7yQA&t=103s  

TypeScript Crash Course - (Traversy Media)  
- https://www.youtube.com/watch?v=rAy_3SIqT-E&t=963s  

TypeScript Tutorial for Angular and React Developers | Mosh  
- https://www.youtube.com/watch?v=NjN00cM18Z4  

TypeScript - The Basics  
- https://www.youtube.com/watch?v=ahCwqrYpIuM  



