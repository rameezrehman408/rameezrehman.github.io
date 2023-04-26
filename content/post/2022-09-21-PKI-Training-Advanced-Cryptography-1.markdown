---
categories: pki
date: "2022-09-21T12:07:17Z"
title: PKI Training - Cryptography Day 2
---

# Basic PKI Services
Growth of a PKI setup has following levels:
* First Generation:
  * Registration Authority
  * Certification Authority
* Second Generation:
  Validation & Time Stamping Services are included
  * Validation Authority
  * Time Stamping Authority
* Third Generation:
This builds and deploy of Signing Services upon second generation technology
  * Signing Services
    * Server-side Signing (i.e. Remote Server, Cloud etc.)
    * client-side Signing (i.e. smart cards, USB tokens, mobile app etc.)
  * Verification Services:
    * Single Trust domain
    * Interoperability between Multiple Trust Domains
* Fourth Generation:
  * Document Signing
  * Tracking
  * Workflow
  * e-Notarization
  * Archiving etc.

# PKIX
PKIX produce a number of standards track and informational RFCs.
* RFC 5280 (X.509 Certificates & CRLs)
* RFC 6960 (Online Certificate Status Protocol (OCSP))
* RFC 3161 (Time Stamp Protocol)










{::comment}
You’ll find this post in your `_posts` directory. Go ahead and edit it and re-build the site to see your changes. You can rebuild the site in many different ways, but the most common way is to run `jekyll serve`, which launches a web server and auto-regenerates your site when a file is updated.

Jekyll requires blog post files to be named according to the following format:

`YEAR-MONTH-DAY-title.MARKUP`

Where `YEAR` is a four-digit number, `MONTH` and `DAY` are both two-digit numbers, and `MARKUP` is the file extension representing the format used in the file. After that, include the necessary front matter. Take a look at the source for this post to get an idea about how it works.

Jekyll also offers powerful support for code snippets:

{{< highlight ruby >}}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{{< / highlight >}}

Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll Talk][jekyll-talk].

[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
{:/comment}
