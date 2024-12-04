# [CJam](https://sourceforge.net/p/cjam/wiki/Home/)

## Language Basics

The key with CJam is that it is a stack-based language, so the code `1 2 +`, puts a 1 on the stack, puts a 2 on the stack (on top of the 1), and adds them, so you end up with (only) 3 on the stack. Addition is a binary operator. However a unary operator will apply only to the top (last) element of the stack. So `-1 -2 z`, will leave -1 and 2 on the stack, because the `z` (absolute value) only applied to the top element of the stack.
