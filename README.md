# Cyber Security: HackRushCTF'25

### Misc

- __Find me__
I just went to the EII website. Right clicked on the slider and clicked on inspect element. There was a comment.
```html
<!-- flag? SFJDVEZ7IV9MMFYzX0hAQ0tSVSRIfQ== -->
```
The string in the comment is in base64 format. I just decoded it using a website that decodes base64 strings.

```sh
FLAG: HRCTF{!_L0V3_H@CKRU$H}
```
- __Crack and Hack__
Using an online MD5 hash decoder, I found out the string to be 12345678. I went to the mess portal and filled in the email-id i.e. hacker@iitgn.ac.in as email-id and 12345678 as the password. I found out that the roll number is 24116969. Then, I just had to append /24116969 to the IR&P council server.

```sh
FLAG: HRCTF{@LW@Y$_U$3_$TR0N6_P@$$W0RD}
```
