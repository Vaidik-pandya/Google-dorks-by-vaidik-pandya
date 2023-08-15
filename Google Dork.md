# SITES FOR IT
https://taksec.github.io/google-dorks-bug-bounty/
https://infosecwriteups.com/10-google-dorks-for-sensitive-data-9454b09edc12

# ADMIN PANEL
```
inurl:domain.com inurl:/admin.aspx
inurl:domain.com inurl:/admin
inurl:domain.com intitle:"index of" inurl:admin/login
```

# INFORMATION DISCLOSURE
```
site:"domain.com" ext:log | ext:txt | ext:conf | ext:cnf | ext:ini | ext:env | ext:sh | ext:bak | ext:backup | ext:swp | ext:old | ext:~ | ext:git | ext:svn | ext:htpasswd | ext:htaccess

site:firebaseio.com "domain.com"
site:s3.amazonaws.com "domain.com"
site:blob.core.windows.net "domain.com"
site:googleapis.com "domain.com"
site:drive.google.com "domain.com"

inurl:"domain.com" intitle:"index of" backup | db | access -github
```

# SQLi
```
site:doamin.com inurl:&#8221;main.php?id=
site:domain.com inurl:zoom.php?id=site:.il
site:domain.com inurl:&#8221;details.php?id=
site:domain.com inurl:&#8221;?came=
site:domain.com inurl:&#8221;index.php?page=
```

# DORKS TO USE FOR BACKUP DISCLOSURE
```
filetype:sql 
filetype:bkf 
filetype:bkp 
filetype:old
filetype:zip
filetype:tar
filetype:gz
filetype:rar
filetype:7z
filetype:tar.gz 
filetype:tar.bz2 
filetype:tgz 
filetype:tbz2 
filetype:tb2 
filetype:ipa 
filetype:apk 
filetype:db 
filetype:dbf 
filetype:mdb 
filetype:accdb 
filetype:xls 
filetype:xlsx 
filetype:xlsm 
filetype:xlsb 
filetype:xlam 
filetype:xla 
filetype:csv 
filetype:txt 
filetype:doc 
filetype:docx 
filetype:ppt 
filetype:pptx 
filetype:pptm 
filetype:pot 
filetype:potx 
filetype:potm 
filetype:pps 
filetype:ppsx 
filetype:ppsm 
filetype:pdf 
filetype:epub 
filetype:mobi 
filetype:azw 
filetype:azw3 
filetype:opf 
filetype:prc 
filetype:lit 
filetype:rtf 
filetype:wps 
filetype:ods 
filetype:odt 
filetype:odp 
filetype:odg 
filetype:odc 
filetype:odf 
filetype:odb 
filetype:dxf 
filetype:dwg 
filetype:svg 
filetype:dwf 
filetype:dwt 
filetype:cad 
filetype:adp 
filetype:accdr 
filetype:mde 
filetype:pub 
filetype:potm 
filetype:xltm 
filetype:sldm 
filetype:ppam 
filetype:docm 
filetype:dotm 
filetype:ppsm 
filetype:xltx 
filetype:xltm 
filetype:vsdx 
filetype:usb 
filetype:docm 
filetype:dotm 
filetype:pptx 
filetype:xlsx 
after:2020-01-01 before:2020-12-31
```

# DORKS FOR CONFIG
```
site:config or intext:config
```

# API DISCLSOURE
```
site:pastebin.com intext:APIKey | intext:APISecret | intext:API-Token -github
```
## Credits:TakSec 
