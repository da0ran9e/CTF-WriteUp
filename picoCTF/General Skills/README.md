<h1 align="center">General Skills</h1>

1. 2Warm
    - Description: Can you convert the number 42 (base 10) to binary (base 2)? 
    - Flag: `picoCTF{101010}`


2. Lets Warm Up
    - Description: If I told you a word started with 0x70 in hexadecimal, what would it start with in ASCII?
    - Flag: `picoCTF{p}`

3. Warmed Up
    - Description: What is 0x3D (base 16) in decimal (base 10)?
    - Flag: `picoCTF{61}`

4. Bases
    - Description: What does this `bDNhcm5fdGgzX3IwcDM1` mean? I think it has something to do with bases. 
    
    - Base64 
    - Flag: `Flag: picoCTF{l3arn_th3_r0p35}`

5. First Grep

    - Description:Can you find the flag in [file](file/First Grep/file)? This would be really tedious to look through manually, something tells me there is a better way.
    
    ``` shell
    strings file | grep "pico"
    ```
    - Flag: `picoCTF{grep_is_good_to_find_things_5af9d829}`
6. strings it
    - Description: Can you find the flag in [file](file/strings it/strings) without running it?

    ``` shell
    strings strings | grep "pico"
    ```
    - Flag: `picoCTF{5tRIng5_1T_7f766a23}``
7. what's a net cat?
    - Description: Using netcat (nc) is going to be pretty important. Can you connect to `jupiter.challenges.picoctf.org` at port `41120` to get the flag?
    ``` shell
    nc jupiter.challenges.picoctf.org 41120
    ```
    - Flag: `picoCTF{nEtCat_Mast3ry_3214be47}`
8. Based:
    - Description: To get truly 1337, you must understand different data encodings, such as hexadecimal or binary. Can you get the flag from this program to prove you are on the way to becoming 1337? Connect with `nc jupiter.challenges.picoctf.org 29956`.
    - Using [Ciphey]() tool for quick trans
    ``` shell
    ──(kali㉿kali)-[~/Desktop/Files]
    └─$ nc jupiter.challenges.picoctf.org 29956
    Let us see how data is stored
    lamp
    Please give the 01101100 01100001 01101101 01110000 as a word.
    ...
    you have 45 seconds.....

    Input:
    lamp
    Please give me the  143 157 156 164 141 151 156 145 162 as a word.
    Input:
    container
    Please give me the 616e696d6174696f6e as a word.
    Input:
    animation
    You've beaten the challenge
    Flag: picoCTF{learning_about_converting_values_b375bb16}
    ```
9. plumbing
    - Description: Sometimes you need to handle process data outside of a file. Can you find a way to keep the output from this program and search for the flag? Connect to `jupiter.challenges.picoctf.org 4427`.
    ``` shell
    nc jupiter.challenges.picoctf.org 4427 | grep "pico"
    ```
    - Flag: `picoCTF{digital_plumb3r_5ea1fbd7}`
10. flag_shop:
    - Description: There's a flag shop selling stuff, can you buy a flag? [Source](file/flag_shop/store.c). Connect with nc jupiter.challenges.picoctf.org 9745.
    ```shell
    ┌──(kali㉿kali)-[~/Desktop/Files]
    └─$ nc jupiter.challenges.picoctf.org 9745
    Welcome to the flag exchange
    We sell flags

    1. Check Account Balance

    2. Buy Flags

    3. Exit

     Enter a menu selection
    2
    Currently for sale
    1. Defintely not the flag Flag
    2. 1337 Flag
    1
    These knockoff Flags cost 900 each, enter desired quantity
    10000000000000000

    The final cost is: -494665728

    Your current balance after transaction: 494666828

    Welcome to the flag exchange
    We sell flags

    1. Check Account Balance

    2. Buy Flags

    3. Exit

     Enter a menu selection
    2
    Currently for sale
    1. Defintely not the flag Flag
    2. 1337 Flag
    2
    1337 flags cost 100000 dollars, and we only have 1 in stock
    Enter 1 to buy one1
    YOUR FLAG IS: picoCTF{m0n3y_bag5_65d67a74}

    ```

11. mus1c 
    - Description: I wrote you a [song](file/mus1c/lyrics.txt). Put it in the picoCTF{} flag format
    - There is a language called "[rockstar](https://codewithrockstar.com/online)", run the lyric file as code and we get a series of decimal number, paste to [converter](https://www.rapidtables.com/convert/number/ascii-hex-bin-dec-converter.html)
    - Flag: `picoCTF{rrrocknrn0113r}`
12. 1_wanna_b3_a_r0ck5tar
    - Description: I wrote you another [song](file/1_wanna_b3_a_r0ck5tar/lyrics.txt). Put the flag in the picoCTF{} flag format
    - Flag: `picoCTF{BONJOVI}`