---
title: Get latest LibreOffice in Ubuntu
author: Valerio Galano
type: post
date: 2013-05-27T12:41:30+00:00
url: /tutorials/get-latest-libreoffice-in-ubuntu/
catcheverest-sidebarlayout:
  - default
dsq_thread_id:
  - 5718325667
trx_addons_post_views_count:
  - 38
categories:
  - How-to guides

---
[LibreOffice][1] is actually the most famous Open Source Office Suite. Unfortunately, Ubuntu repositories often doesn't contains latest versions of it.

If you like to have your LibreOffice always updated, you can simply execute following commands in your terminal:

{{< highlight bash >}}
$ sudo add-apt-repository ppa:libreoffice/ppa
$ sudo apt-get update
$ sudo apt-get dist-upgrade
{{< /highlight >}}

At the end of the process, simply run LibreOffice from applications menu and have fun.

[1]: http://www.libreoffice.org/