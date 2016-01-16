# Malicious-Code-Sanitizer 
An API/Library to Sanitize Malicious Code </br>
Input : Malicious Code </br>
Output : Cleaned Code </br>

# API Structure </br>
domain.com/sanitizestring/string="'>&script>alert("hacked");&/script>"  </br>
JSON Response of API  : </br>
{ "BadString" : "'>&script>alert("hacked");</script>",  </br>
"CleanedString":""  </br>
} </br>
