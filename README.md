# 👨‍💻 minishell

Here is the minishell project wroted by [acroisie](https://github.com/acroisie) and I.

The goal of this project is to achieve a basic **shell in C** with some missing features but fully functional.
We divide the work in two different parts, [acroisie](https://github.com/acroisie) managed parsing then I execute.

### The rules:

* Display a prompt
* Functionnal history
* Search & execute basing on the relative and absolute path
* No more than one global variable
* Implement redirections
* Implement pipes `|`
* Manage environnement variables and " `$?` "
* Manage signals `ctrl-C`, `ctrl-D` & `ctrl-\`
* Write somes builtins; `echo (with -n option)`, `cd`, `pwd`, `export`, `unset`, `env`, `exit`.
* Like all C project from 42 you have to follow the 42 norm and leaks are not allowed.

---

## Try it !

```shell
make && ./minishell
```
>Minishell is running enjoy !

#### Example : 
```bash
ls | cat | echo "Hello world!"
```
```bash
echo "Hello world" > hello.txt | cat hello.txt
```
