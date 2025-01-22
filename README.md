# gpt-addition
from: [karpathy's GPT tutorial](https://www.youtube.com/watch?v=kCc8FmEb1nY&t=793s&ab_channel=AndrejKarpathy)
tried to get GPT to add. masking the right inputs and figuring out all the conditions was difficult and my outputs are currently garbage. e.g.
```
input: 57+24=
output: 0+1;62=390;24+90;77=4

```
likely doing more tokenizing to let the model understand the format of the equation better (like a+b=c) and a custom masking technique could help. will try again later, possibly integrating multiplication/division when i learn more. till then, desmos is good for me...
