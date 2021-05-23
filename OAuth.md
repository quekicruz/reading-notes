# What is OAuth? 

- `OAuth` 
  - An open-standard authorization protocol or framework that describes how unrelated servers and services can safely allow authenticated access to their assets without actually sharing the initial, related, single logon credential. 

- Examples of OAuth 
  - `When you try to log into one website and it allows for you to log into it with another websites credentials.`
  - It still asks for your permission to use the other websites credentials to log in. 

- How does OAuth work? 

  - It is good to know the difference between authentication and authorization. 
    - `Authentication`
      - process of a user/subject proving its ownership of a presented identity, by providing a password or some other uniquely owned or presented factor.
    - `Authorization`
      - process of letting subject accesss resources after a successful authentication, often times somewhere else. 
  - `OAuth` 
    - Open Authentication(OAuth)

- Steps to how OAuth work 
  1. The first website connects to the second website on behalf of the user, using OAuth, providing the user’s verified identity.
  2. The second site generates a one-time token and a one-time secret unique to the transaction and parties involved.
  3. The first site gives this token and secret to the initiating user’s client software.
  4. The client’s software presents the request token and secret to their authorization provider (which may or may not be the second site).
   5. If not already authenticated to the authorization provider, the client may be asked to authenticate. After authentication, the client is asked to approve the authorization transaction to the second website.
  6. The user approves (or their software silently approves) a particular transaction type at the first website.
  7. The user is given an approved access token (notice it’s no longer a request token).
   8. The user gives the approved access token to the first website.
  9. The first website gives the access token to the second website as proof of authentication on behalf of the user.
  10. The second website lets the first website access their site on behalf of the user.
   11. The user sees a successfully completed transaction occurring.
  12. OAuth is not the first authentication/authorization system to work this way on behalf of the end-user. In fact, many authentication systems, notably Kerberos, work similarly. What is special about OAuth is its ability to work across the web and its wide adoption. It succeeded with adoption rates where previous attempts failed (for various reasons).

* [This](https://www.csoonline.com/article/3216404/what-is-oauth-how-the-open-authorization-framework-works.html) link is where I retrieved the specific steps shown up above. 

- `OpenID`
  - Verifies users logging into machines and the authentication technology to carry out the specific task 


# Authentication and Authorization Flows 

- `Authentication`
      - process of a user/subject proving its ownership of a presented identity, by providing a password or some other uniquely owned or presented factor.

- `Authorization`
      - process of letting subject accesss resources after a successful authentication, often times somewhere else. 

- `Authorization Code Flow` 
    - Takes Authorization Code for a token to allow for access for information. 


- `PCKE-enhanced Authorization Code Flow`
  - Introduces a secret created by the calling of application that can be verified by the authorization server; it done through Code Verifier
  - Attackers could only get the Auhtorization Code and not the actual Code verifier which is the most important aspect 

- `Implicit Flow with Form Post`
  - Uses OIDC to implement web sign-in. 
  - Web app request and obtains tokens through the front channel, without the need for secrets or extra backend calls. 

- `Client Credentials Flow`
  - Passes Client ID and Client Secret to authenticate themselves and get a token. 

- `Device Authorization Flow`
  - Asks user to authorize through another device to verify information and passes Client ID to initiate the authorization process and get a token. 

- `Resource Owner Password Flow`  
  - Request that users provide credentials, then credentials are sent to the backend and can be stored for future use before being exchanged for an Access Token. 


## Things I want to know more about

- I want actual work the process of building out the authorization code. 


