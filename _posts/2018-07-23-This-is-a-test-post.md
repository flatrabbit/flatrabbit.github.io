---
title:  "Test Post"
date:   2018-07-23 12:12:00
categories: [test]
tags: [test]
---
Just playing with the posts option to see how this all works.

code snippet:

``` powershell
Get-ADUser $user -prop proxyaddresses,userPrincipalName | % {

	$PrimarySMTP = $_.proxyaddresses -like "SMTP*"

}
```

Check out the [Jekyll docs][jekyll] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll’s dedicated Help repository][jekyll-help].

[jekyll]:      http://jekyllrb.com
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-help]: https://github.com/jekyll/jekyll-help
