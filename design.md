# Design of kata
## About kata
kata is word learning tool by myself.

## Screen image
```
[login part]
<<TO BE DESIGNED>>

[main menu part]
Please select a mode.
  
  * LEARNING MODE
  ^^^^^^^^^^^^^^^^
  
  * WORD INPUT MODE
  ^^^^^^^^^^^^^^^^^^^

> LEARNING MODE -> move to learning part.
> WORD INPUT MODE -> move to input part.

[learning part]

  [[  WORD  ]]

This WORD means...
  [*] means1
  [ ] means2
  [ ] means3
  [ ] means4

Remain: 5...4...3...2...1...  

> Show WORD by database.
> MEANS can select from multiple option buttons.
> MEANS assign to each buttons.
> User clicked [means button] -> move to correct part or failure part.
> Remain time is count down 5 seconds.
> If remain time is 0 -> move to failure part.

[correct part]
<<TO BE DESIGNED>>

[failure part]
<<TO BE DESIGNED>>

[input part]
Please input word and means set.
       +---------------+
word   | input box 1   |
       +---------------+
     
       +---------------+
means  | input box 2   |
       +---------------+ 
       
       [ADD]   [CANCEL]
> Add to database word/means pair.

```
