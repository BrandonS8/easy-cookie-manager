# Easy Cookie Manager

To install `npm install easy-cookie-manager`

To set a cookie you have to provide 3 arguments (String: name, String: value, Integer: days until expired)

To get a cookie you have to provide 1 argument (String: name)

To delete a cookie you have to provide 1 argument (String: name)

```
import _Cookies from 'easy-cookie-manager'

// This sets a cookie called myCookieName with the value 'testvalue' that expires in 30 days
_Cookies.setCookie('myCookieName', 'testvalue', 30)

// This will return the value of the cookie, which is 'testvalue' in this case
_Cookies.getCookie('myCookieName')


// This will delete the cookie, deletion is done by setting the expiration date to an already passed time
_Cookies.deleteCookie('myCookieName')

```
