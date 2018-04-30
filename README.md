
# WebSec-Week7

  

# Project 7 - WordPress Pentesting

  

Time spent: **3** hours spent in total

  

> Objective: Find, analyze, recreate, and document **three vulnerabilities** affecting an old version of WordPress

  

## Pentesting Report

  

1. **Stored Cross-Site Scripting (XSS) | CVE-2015-5622**

- [x] Summary : 
> Cross-site scripting (XSS) vulnerability in WordPress before 4.2.3 allows remote authenticated users to inject arbitrary web script or HTML by leveraging the Author or Contributor role to place a crafted shortcode inside an HTML element, related to wp-includes/kses.php and wp-includes/shortcodes.php

  
- [x] Vulnerability types: `Stored XSS [WP Core]`

- [x] Tested in version: `4.2`

- [x] Fixed in version: `4.2.3`

- [x] GIF Walkthrough: 


- [x] Affected source code:   [Changeset 33359](https://core.trac.wordpress.org/changeset/33359)

&nbsp;
2. **Stored Cross-Site Scripting (XSS) in YouTube URL Embeds | CVE-2017-6817**

- [x] Summary : 
> Cross-site scripting (XSS) vulnerability in WordPress before 4.7.3 allows remote authenticated users to inject arbitrary script in a youtube embed link exploiting a bug in (wp-includes/embed.php) that mishandles special input.
  
- [x] Vulnerability types: `Stored XSS [WP Core]`

- [x] Tested in version: `4.2`

- [x] Fixed in version: `4.7.3`

- [x] GIF Walkthrough: 


- [x] Affected source code:   [Commit](https://github.com/WordPress/WordPress/commit/419c8d97ce8df7d5004ee0b566bc5e095f0a6ca8)

&nbsp;
3. **Unauthenticated Stored Cross-Site Scripting (XSS) in Comments | CVE-2015-3440**

- [x] Summary : 
> An unauthenticated attacker can inject JavaScript in WordPress comments. The script is triggered when the comment is viewed.
  
- [x] Vulnerability types: `Unauthenticated Stored XSS [WP Core]`

- [x] Tested in version: `4.2`

- [x] Fixed in version: `4.2.1`

- [x] GIF Walkthrough: 


- [x] Affected source code:   [Changeset 32299](https://core.trac.wordpress.org/changeset/32299)

  

## Resources

  

- [WordPress Source Browser](https://core.trac.wordpress.org/browser/)

- [WordPress Developer Reference](https://developer.wordpress.org/reference/)
- [klikki.f](https://klikki.f)
  

GIFs created with [Peek](https://github.com/phw/peek).

  

## Notes

  

None
  

## License

  

Copyright [2018] [drsh0x]

  

Licensed under the Apache License, Version 2.0 (the "License");

you may not use this file except in compliance with the License.

You may obtain a copy of the License at

  

http://www.apache.org/licenses/LICENSE-2.0

  

Unless required by applicable law or agreed to in writing, software

distributed under the License is distributed on an "AS IS" BASIS,

WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.

See the License for the specific language governing permissions and

limitations under the License.
