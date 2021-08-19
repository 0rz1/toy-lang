# toy-lang

I wrote [arithmetic calculator](https://github.com/0rz1/calculator) with go-lang for practice.

I'd like a more challenging work to learn rust.

1. Define a toy language.
2. A language parser.
3. A vm to execute the language.

## Define language

1. function
'''
fn foo() {

}

fn foo2(a, b) {

}
'''

2. if
'''
if () {}

if () {}
else {}

if () {}
else if () {}
else {}
'''

3. for
'''
for (;;) {}
'''

4. value
'''
let a = 1; // define & assign
let a;     // only define
a = 1;     // only assign
'''

5. value type
  * int64 number
  * bool

6. print
'''
let a = 1;
print(a);
'''

7. scope
'''
let a = 1;
{
   let a = 2;
   print(a);  // 2
}
print(a) ; // 1
'''

8. operator
   * +-*/%
   * && || !
   * >= <= > < !=
