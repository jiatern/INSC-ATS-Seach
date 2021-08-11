## INSC*** ATS Candidate Search Bookmarklet

This bookmarklet allows you to search on INSC*** ATS using candidate's email or name.
Click the bookmark with any website open (as long as not a blank tab). Ideally the ATS itself.

You can drag and drop the bookmarklet below to your Bookmark bar to save it.

[![ATS Search](https://i.imgur.com/nxgGlCM.png)](javascript:void function(){javascript:var a=prompt("\nSearch ATS for email or names. Examples: \n\njohnsmith@gmail.com \nmailto:johnsmith@gmail.com \nJohn Smith","");-1<a.indexOf("@")?(a=a.replace("mailto:",""),location="https://recruit.inscale.net/candidates?utf8=%E2%9C%93&candidate%5Bsolr_query%5D="+a):location="https://recruit.inscale.net/candidates?utf8=%E2%9C%93&candidate%5Bfirst_name%5D="+a+"&candidate%5Blast_name%5D="+a}();)

or you can manually add the following code as a bookmark:

```
javascript:void function(){javascript:var a=prompt("\nSearch ATS for email or names. Examples: \n\njohnsmith@gmail.com \nmailto:johnsmith@gmail.com \nJohn Smith","");-1<a.indexOf("@")?(a=a.replace("mailto:",""),location="https://recruit.inscale.net/candidates?utf8=%E2%9C%93&candidate%5Bsolr_query%5D="+a):location="https://recruit.inscale.net/candidates?utf8=%E2%9C%93&candidate%5Bfirst_name%5D="+a+"&candidate%5Blast_name%5D="+a}();
```
