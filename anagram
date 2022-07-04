package com.balaji;

import java.util.Arrays;


public class anagram {
    public static void main(String[] args) {
        String str  = "Grab";
        String str1 ="Barg";

        // converting into lower case :
        str  =  str.toLowerCase();
        str1 = str1.toLowerCase();

        // checking the length
        if(str.length()!=str1.length()){
            System.out.println("Both the string not anagram:");
        }
        else{
                char[] string1=str.toCharArray();
                char[] string2=str.toCharArray();


                // sorting array:

            Arrays.sort(string1);
            Arrays.sort(string2);

            if(Arrays.equals(string1,string2)){
                System.out.println("this is anagram ✔ ");
            }
            else {
                System.out.println("this is not anagaram ❌");
            }
        }



    }
}
