# MathLibrary
First Commit   ADD, SUB, MUL, DIV

Step 1. Add the JitPack repository to your build file
Add it in your root build.gradle at the end of repositories:

	allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
  
  
  Step 2. Add the dependency

	dependencies {
	        implementation 'com.github.shubhmahalkar:MathLibrary:1.0'
	}
  
  Step 3. How to use
  
    You can perform math basic operations like Addition, Substraction, Division and Multiplication.
    
    Math.Plus(a,b);
    
    Math.Minus(a,b);
    
    Math.Division(a,b);
    
    Math.Multiple(a,b);
    
    
   
    Example - Math.Plus(10,20); // Addition is 30
    
    int sum =  Math.Plus(10, 20);  // Addition
