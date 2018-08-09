---
title:  "Test Post"
date:   2017-07-23 12:12:00
categories: [test]
tags: [test]
youtubeId: sM9NgtUJk70
---
Just playing with the posts option to see how this all works.

code snippet:

``` powershell
Get-ADUser $user -prop proxyaddresses,userPrincipalName | % {

	$PrimarySMTP = $_.proxyaddresses -like "SMTP*"

}
```

image test
![My helpful screenshot]({{ "/assets/topobags.jpg" | absolute_url }})

youtube test
sM9NgtUJk70

{% include youtubePlayer.html id=page.youtubeId %}