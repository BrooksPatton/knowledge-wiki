# Front End Web Development

## Browsers

### Cookies

The name cookies was first coined in 1979 when it was used in the man page for `fseek` ([wikipedia](https://en.wikipedia.org/wiki/Magic_cookie)). It was primarily used as a token, given to a program to hold and give back at a later time.

I don't know why the word `cookie` was used.

The idea of a cookie doesn't indicate what kind of data or the structure that would be stored in it. It could be an id, inode, or anything really.

[HTTP cookies](https://en.wikipedia.org/wiki/HTTP_cookie) on the other hand were created by [Lou Montulli](https://en.wikipedia.org/wiki/Lou_Montulli), a founding member of Netscape who also made Lynx.

* Cookies went live in Netscape 0.9beta in 1994
* IE started supporting cookies in 1995
* IETF formed a working group to work with cookies in 1995
* Financial Times wrote an article about cookies in 1996 which caused an uproar about privacy
* IETF declared third party cookies to be a privacy threat in 1996. Recommended disabling third party cookies by default. Netscape and IE ignored
* FTC had hearings about cookies in 1996 and 1997

#### Cookie Structure

1. Name
2. Value
3. [Attributes (key/value pairs)]

#### Low-Tech Explanation

I don't know why cookies are called cookies. They aren't tasty, and we can't eat them. Browsers (like Chrome, Edge, or Firefox) use them to store data. Or rather the programs running on the browsers are storing this data. Each cookie is just plain text or numbers. Not really exciting from the surface.

We often have many programs running on each webpage however. Browser extensions, advertisements, and the main website we were there to see to begin with. Each of these programs can leave and read cookies.

What I mean by that is that the browser is given the cookie by the server, a computer that houses the code of the program that our computer is running through the browser. Whenever we navigate back to that site, or if that site uses programming algorithm's that sends messages back to the server it sends the cookies with it. 

The benefits of cookies are that the programs can be more aware of who we are. In the case of being logged into a bank, thats a good thing. We don't want to have to put our username and password in every time we click on something. The server is storing a cookie saying that we have already proven who we are and what our user id is.

However there are privacy concerns. A program like an advertisement can leave cookies on every page that we visit that has that ad. Then they get all the cookies, (from them) that they left, even the ones from different pages. This allows the ads to track us over different websites and build a profile of who we are without our knowledge.

Also, because cookies can be used to prove to programs that we are we and then not have to put our passwords in again there are some security policies that would be a good idea to follow.

First, always use `https` websites. The browser should have a lock icon somewhere on it to show that everything, including the cookies have been encrypted. This will prevent a hacker from looking at your data between your computer and the server. They can still get the data, but they won't be able to make heads or tails of it because it is encrypted. Also, decrypted good encryption takes time that the hacker most likely doesn't have. 

There are some ways that hackers can create websites that look normal but can steal cookies. Unfortunately these websites can also be ads that run on legitimate websites which is why we hear security advocates suggest that we block ads.
