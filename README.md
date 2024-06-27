The SimpleRISC ISA implements 21 instructions and has 16 registers, r0 through r15, with r15 having alias ra (return address) and r14 sp. The program uses 32 bit memory addressing for load and store operations.


# Set up
Make sure you have python3 installed
If you're using mac then you can install python3 using hombrew running:
- `brew install python` 
- Then make sure it installed correctly running `python3 --version` in the terminal and you should see something like `Python 3.12.3`

- Git clone this repo to your computer running `git clone `
- Update the `assembly.s` file with your code
- `.main:` will run your code
- `.break` will print the specified register

- You can see some further examples in the `rn.asc` file for what you'd like to do

# To run the code
- run `python3 sr_unsigned.py assembly.s` in your terminal
 