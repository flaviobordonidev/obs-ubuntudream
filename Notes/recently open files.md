```dataview  
TABLE file.mtime as Modified  
FROM " "  
WHERE date(now) - file.mtime <= dur(1 days)  
SORT file.mtime desc  
```
