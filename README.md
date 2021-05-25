HtmlFetcher
=================================================

![Points](../../blob/badges/points.svg)

For this homework, you will download HTML content from web servers. This homework is broken into the following classes:

  - `HttpsFetcher.java`: This is a general HTTP(S) fetcher and is the same as the lecture code.

  - `HtmlFetcher.java`: This is a variant of HTTP(S) fetcher specifically for HTML content. There are a few methods here you must implement.

## Hints ##

Below are some hints that may help with this homework assignment:

  - It will help to have a HTTP reference. The [MDN Web Docs](https://developer.mozilla.org/en-US/) have nice [HTTP reference](https://developer.mozilla.org/en-US/docs/Web/HTTP) references, including references for [HTTP headers](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers) and [HTTP status codes](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status).

  - An inefficient `HtmlFetcher.fetch(URL, int)` implementation will hurt your ability to pass runtime tests for project 4.

      For the most efficient solution, do not directly use `HttpsFetcher.fetchURL(URL url)` in your implementation. Instead, setup the sockets and get the headers in the same way. Then, based on those headers, decide how to proceed. Do not fetch the entire page unless necessary!

  - Some of these methods can be done using regular expressions, but it is not required.

These hints are *optional*. There may be multiple approaches to solving this homework.
