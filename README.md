# Programming Exercise

Your task is to figure out how this code works.

* Come with a test input for the function.
* Trace the flow of the program with your test input **without running the code**, keeping track of all of the variables and transformations until you can determine the output.
* Keep coming up with new inputs until you're confident until you're confident that you know how the function works.
* Write a summary of what the function does.

```js
function (user){
  if (user.isActive){
    return `Welcome back, ${user.username}!`
  } else {
    return `Hey ${user.username}! Would you like to renew your subscription?`
  }
}
```

| Input | Output |
| ----- | ------ |
|  Lauren (is active)     |  Welcome back, "Lauren", "lhanna7"!      | 
|  Lauren (not active)     |    Hey "Lauren", "lhanna7"! Would you like to renew your subscription?    | 
|       |        | 

<table>
  <tr>
    <th>What does this program do?</th>
    <td>I think this program monitors whether or not the user has an active account on this platform. I think username is an assumed item, so I put lhanna7 as the fill in. I also think isActive is another assumed variable that isn't shown. If somewhere in my account shows isActive, then the message "Welcome back, user.username" will be shown. If isActive is missing, different, etc, then the alternative message will be displayed. I'm not really sure how user.username gets translated, but that's how I took a stab at it </td>
  </tr>
</table>

## Rubric

* Contains a plausible collection of test cases
* Outputs are accurately derived from inputs
* Summary is plausible
