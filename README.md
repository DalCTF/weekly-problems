# weekly-problems

Repository to maintain problems featured by the society during meetings. 

To add a problem, copy template.json into the appropiate category, and add the details of the problem. Ensure the `"active"` attribute is set to `true` so it is featured as the weekly problem. Otherwise, it will be placed into past problems. 
Use attribute `id` to order which problem is listed first.  

```
{
    "id": 1,
    "name": "Buffer Overflow 1",
    "author": "Sanjay C / Palash Oswal",
    "link": "https://play.picoctf.org/practice/challenge/258",
    "presentedBy": "Conrado Boeira",
    "datePresented": "2025-09-22",
    "tags": ["Binary Exploitation"],
    "snippet": "Control the return address.",
    "flag": "picoCTF{addr3ss3s_ar3_3asy_[REDACTED]}",
    "flagFormat": "picoCTF{}",
    "active": true
}


```