LiveText Control is a Node.js script and set of accompanying utilities to remotely manage various variables and images in NewTek LiveText.
# Features
- Managing comprehensive scoreboard graphics control from a web interface
- Managing comprehensive telethon graphics control from a web interface
- Live display of drawings from an iPad in LiveText
- Receiving variables from standard LiveText-formatted text files
- Control playing and stopping movement in LiveText from a web interface
- Setting LiveText to an arbitrary page from a web interface
- Written in Node.js using Google Chrome's V8 JS engine
# Prerequisites
- NewTek LiveText
- A NewTek Tricaster that can take LiveText input
- Node.js (from [nodejs.org](http://nodejs.org/ nodejs.org)), a server-side JS platform using Google Chrome's V8 JS engine
# Usage
## Syntax
For usage instructions, navigate in a command prompt to the root folder of the repository and run the command `node Server.js --help`
This will present a set of options for the program.
The arguments of Server.js are:
+ -i <file>: Poll this file for input. Whenever this file is modified, its contents will be parsed for variables. (supports multiple of this argument)
+ -s: Set the computer to begin acting as a wireless access point when the program starts (for when the computer is wired in and an iPad is in use)
+ -l <file>: Parse this file once on start (for presets) (supports multiple of this argument)
+ -o <file>: Write the output to this location (usually in NewTek Program Files)
+ -p <port>: Listen on this port for the primary socke server (not currently used)
+ -h <port>: Listen on this port for the HTTP server (defaults to 8990)
There will soon be an option for generating a program you can simply double-click to edit
## Running the program
## Using the web interface
Navigate using a web browser to http://localhost:8990/

## Copyright and Licensing
Copyright (C) 2012 Rodger Combs.
The program(s) encoded within this repository (herein the PROGRAM) is provided by Rodger Combs (herein the AUTHOR) for use by any individual or company (herein the USER) in conjunction with NewTek LiveText (herein LIVETEXT) and/or its related products, including, but not limited to, the NewTek Tricaster 850 and NewTek Tricaster 850XD (herein RELATED PRODUCTS) under any of the three (3) conditions listed below:
    1. The USER uses the PROGRAM solely for non-commercial and/or non-profit use, including, but not limited to, and at the sole discretion of the AUTHOR:
        a. Schools
        b. Churches
        c. Charities
        d. USERs who do not profit from use of the PROGRAM, LIVETEXT, or RELATED PRODUCTS
    2. Both of the following conditions are fulfilled:
        a. The USER has received express permission from the AUTHOR to use the PROGRAM, including, but not limited to, permission granted as a result of a purchase from the AUTHOR
        b. Any conditions specified by the AUTHOR for use of the PROGRAM by the USER are followed
    3. The USER intends to profit from use of the PROGRAM, LIVETEXT, or RELATED PRODUCTS, but will not profit from the current use of the PROGRAM, including, but not limited to, a USER who wishes to test the functionality of the PROGRAM or its usefulness in their workflow.
     
Any use of the PROGRAM that does not fulfill one of these conditions is prohibited.

If a USER is licensed for use of the PROGRAM under the above license, then that USER is licensed to modify any portion of the PROGRAM with the exception of this license statement. Such a modified version of the PROGRAM may NOT be redistributed to any other USER except when expressly permitted by the AUTHOR. If the USER is unable to make such a modification, then the USER may submit a feature request or bug report at the GITHUB ISSUES PAGE at https://github.com/11rcombs/LiveText-Control/issues

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

