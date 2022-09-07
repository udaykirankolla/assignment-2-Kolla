# assignment-2-Kolla
# KOLLA UDAYKIRAN #
## musuem name is salarjung  museum ##
The Salar Jung Museum is an art museum located at **Dar-ul-Shifa**, on the southern bank of the Musi River in the city of Hyderabad, Telangana, India. It is one of the notable National Museums of India. Originally a private art collection of the Salar Jung family, it was endowed to the nation after the death of **Salar Jung III**. It was inaugurated on 16 December 1951.
---
## Traveling Guide for the museum ##
1. Beghampet Airport is closest to the Salar jung museum.
2. first we will land off the airplane.
3. after landing the flight we want to book a cab to the museum.
4. finally we will reached to the museum.
* I would like to recommended locations to others around the salar jung museum.
    * jamal market shopping complex.
    * chowmahalla palace.
    * Nizam museum.
    * Charminar.
    * modi pearls.

Link to AboutME ![AboutMe](AboutMe.md)

# Table for cities
--- 
| city      | location     | time   |
| ---:      | ---:         |    ---:|
| hyderabad | salarjung    | 1 hour |
| banglore  |  durga temple| 1 hour |
| vijayawada| temple       | 1 hour |
| ongole    | kalanikethan | 1 hour |
---

# pithy quotes
> "failure is the first step for success."
>@ Author: Winston S. Churchill<br>
>"Success usually comes to those who are too busy to be looking for it."
>@ Author: Henry David Thoreau<br>

---
# Code Fencing
>Custom error pages enable you to customize the pages that display when an error occurs. This makes your website appear more professional and also prevents visitors from leaving your site. If a visitor sees a generic error page, they are likely to leave your site
The link to source is <https://stackoverflow.com/questions/18759390/404-custom-error-page>

```
<?php

$status=$_SERVER['REDIRECT_STATUS'];
$codes=array(
      400 => array('400 Bad Request', 'The request cannot be fulfilled due to bad syntax.'),
      401 => array('401 Login Error', 'It appears that the password and/or user-name you entered was incorrect.'),
      403 => array('403 Forbidden', 'Sorry, employees and staff only.'),
      404 => array('404 Missing', 'We\'re sorry, but the page you\'re looking for is missing, hiding, or maybe it moved somewhere else and forgot to tell you.'),
      405 => array('405 Method Not Allowed', 'The method specified in the Request-Line is not allowed for the specified resource.'),
      408 => array('408 Request Timeout', 'Your browser failed to send a request in the time allowed by the server.'),
      414 => array('414 URL To Long', 'The URL you entered is longer than the maximum length.'),
      500 => array('500 Internal Server Error', 'The request was unsuccessful due to an unexpected condition encountered by the server.'),
      502 => array('502 Bad Gateway', 'The server received an invalid response from the upstream server while trying to fulfill the request.'),
      504 => array('504 Gateway Timeout', 'The upstream server failed to send a request in the time allowed by the server.'),
);

$errortitle=$codes[$status][0];
$message=$codes[$status][1];

if($errortitle==false){
       $errortitle="Unknown Error";
       $message="An unknown error has occurred.";
}

?>
<!doctype html>
<html>
<head>
<title><?php echo("$errortitle");?></title>
<meta charset="utf-8">
</head>
<body>

<!-- Insert headers here. -->

<?php
echo('<h1>'.$errortitle.'</h1>');
echo('<p>'.$message.'</p>');
?>

<!-- Insert footers here. -->

</body>
</html>

```
The link is <https://css-tricks.com/snippets/htaccess/custom-error-pages/>
