# MetaCTF 2021
## Under Inspection (100pts)
### Description: 
>Someone made this [site](https://metaproblems.com/2841e99cee26f773b26b300acad556c4/inspect/) for the Autobots to chat with each other. Seems like the Decepticons have found the site too and made accounts.
One of the Autobot accounts has a flag that they're trying to keep hidden from the Decepticons, can you figure out which account it is and steal it?

### View-source:
Leta check the source file which is done by adding prefix view-source: on the url :)
```Javascript
var username = document.getElementById("username").value;
var password = document.getElementById("password").value;
var result = document.getElementById("result");
var accounts = [
  {user: "Admin", pwd: "MetaCTF{super_secure_password}"},
  {user: "Bumblebee", pwd: "MetaCTF{sting_like_a_bee}"},
  {user: "Starscream", pwd: "MetaCTF{the_best_leader_of_the_decepticons}"},
  {user: "Jazz", pwd: "MetaCTF{do_it_with_style_or_dont_do_it_at_all}"},
  {user: "Megatron", pwd: "MetaCTF{peace_through_tyranny}"},
];
```
# Flag:

```
MetaCTF{do_it_with_style_or_dont_do_it_at_all}
```
