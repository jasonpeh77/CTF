# Crac'23 2023

* notes
  -this is Write-Up  for CTF CRAC'23 

## Table of contents
- [Crack it! - 70 mark](#crack-it--70-mark)
- [Spam message -10 mark](#spam-message--10-mark)
- [Image.PNG -10 mark](#imagepng--10-mark)
- [OWL  -15 mark](#owl--15-mark)
- [CREATIVITY -30 mark](#CREATIVITY--30-mark)
- [Boot2root Wargame II Scanning Machine](#boot2root-wargame-ii-scanning-machine)
- [Boot2root Wargame II Service](#boot2root-wargame-ii-service)

## **Crack it! -70 mark**
- based on question it need to find the password so we using Strings to find password
<img width="410" alt="image" src="https://github.com/jasonpeh77/CTF/assets/117582674/3050f89a-00de-404e-8345-49d2875fd65b">

--from here we can saw the password is abc123

---flag:**ctf{abc123}**

## **Spam-message--10-mark**
- we saw that given file it show like normal word ,so we using online tools [SpamMimic Decoder](https://www.spammimic.com/decode.shtml)
  <img width="388" alt="image" src="https://github.com/jasonpeh77/CTF/assets/117582674/e221f5cf-18c4-471a-bff1-99ccfd7d08cb">
  
  -copy all thing paste in tu tools [SpamMimic Decoder](https://www.spammimic.com/decode.shtml)
  
  <img width="437" alt="image" src="https://github.com/jasonpeh77/CTF/assets/117582674/91fb21cd-d46b-4795-bd5d-be950e21ac91">

  -after decode ,we will get the answer
  
  <img width="563" alt="image" src="https://github.com/jasonpeh77/CTF/assets/117582674/1a7c488e-3ac9-430f-92f2-ce642769de4c">

## **imagepng--10-mark**
-This is the image in this question 

  <img width="575" alt="image" src="https://github.com/jasonpeh77/CTF/assets/117582674/955375e8-1b8d-48af-82e5-be7d910ee4d7">

  -Using command zsteg to found the flag

  <img width="648" alt="image" src="https://github.com/jasonpeh77/CTF/assets/117582674/d0bf4001-8fa5-4d1c-9411-3c15bb4cd138">

  --Inside we can saw that flag:**ctf{h1dd3n_m3ss4ge}**

## **Owl -15 mark**
-based on this question it need us to find Shutter Speed value be a flag 
  <img width="774" alt="image" src="https://github.com/jasonpeh77/CTF/assets/117582674/f5288db8-ad7b-4525-a136-0e1c68237aa0">

  -So using exiftools to find that value ** exiftool -ShutterSpeed Owl.jpg**
  
  <img width="226" alt="image" src="https://github.com/jasonpeh77/CTF/assets/117582674/b455f1cf-0ebe-4c7e-be21-c0beb2dbf3a7">

  -So the flag is **ctf{1/400}**

## **CREATIVITY -20 mark**
-Check file type

<img width="156" alt="image" src="https://github.com/jasonpeh77/CTF/assets/117582674/421bf12d-5908-48d9-9588-e75a617075e2">
  
  
  -using strings or cat command to display the detail text in file
  
  <img width="227" alt="image" src="https://github.com/jasonpeh77/CTF/assets/117582674/80c159d5-75fd-4f52-ae69-cfe3eba9c735">
  

  -the find have inside the Reverse first column  is CTFSS{4R3UCR3AT1V3DUD3}







  

