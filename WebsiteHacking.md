1. File Upload Vulnerability
    akan di eksekusi dengan weevely
2. Code execution vulnerability
   "when we allow to execute server from website"
   analyze input, 
3. Local file Inclusion Vulnerabilty
   "website allow to read local file"
   "access file outside www directory" ini bisa diakalin kalau url salah harus 404
4. Remote File Inclussion
    "Same with local file inclussion, but it from other server"
    "don't include file in url"
5. SQL Injection Vulnerability 
    "Selama Paka Django gak ada sql di URL yang bisa di eksekusi" itu gila
6. XSS
    Inject javascript, di jalankan ketika page di load, aman lah ini mah
    minimize user input
    escape untrusted input (& < > " / ')
7. Insecure Session Management
    coockie management add on
    jangan menaruh id di session, harus pake session id atau token
    hati2 csrf (cross site request forgery), jadi form harus memiliki csrf token
    aman kalau selau ngecek request.user ya,, karena biasanya yang di pake change password
    request current password for change password
    Harus pake CSRF Token
8. Brute force attacks 
    mengacak password gitu,, 
    kalau dictionary password itu ngacak password yang ada di list aja
    "HYDRA" Tools untuk generate password brute force attack 
    "password" harus alfa numerik karena akn menyusahkan mesin ini
9. Pakai Sofware INi untuk penetration testing "OWASP ZAP" 
10. Hati-hati permision folder, jangan sampe ada yang 777
11. Hati-hati saat ada beberapa web di server, jika salah satu lemah bisa ke akses yang lainnya
13. Linux untuk hacking, yaitu "Kali Linux"
14. semua file upload harus di rename,
15. jangan satukan dev dg production, 
16. hati hati read access from other user in linux

NAMA-NAMA TOOLS YANG DIPAKE
1. KALI LINUX => UNTUK HACK
2. WEEVELY => to execute file  that has uploaded to the server by file upload (very dangerous) / always rename file upload
3. MESTASPLOITABLE => VULENERABILITY LINUX DISTRO, DESIGNER TO PENETRATION AND HACK, included the website to hack
4. BURP PROXY SUITE, to INTERCEPT REQUEST, change parameter in proxy when upload, UPLOAD, -> PHP JADI .JPG
5. VEIL Framework => generate backdoor app in .exe to make user install it, and we can access that victiom from internet
6. BEEF FRAMEWORK => HOOOKING browser victom from xss attack, and we can access from browser that connect to that xss attack, to do more 




