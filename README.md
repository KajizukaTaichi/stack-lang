# Stack Programming Language
The powerful script language designed with a stack oriented approach for efficient execution. 

![image](https://github.com/stack-community/stack-lang/assets/122075081/0f25934d-c7f1-4f30-b180-3389bbc2118a)

Official site: https://stack-community.github.io

## Install

### If you don't want to install...

**Launching Stack needs cargo!**

```bash
git clone https://github.com/Stack-Programing-Community/Stack-Programing-Language.git
cd Stack-Programing-Language
cargo build --release
chmod +x ./run.stack.sh
./run-stack.sh
```

### Normal Install

Stack programming language's interpreter binary files for Windows are in the [release](https://github.com/Stack-Programing-Community/Stack-Programing-Language/releases).

the releases are Regularly when new function become stable, that's good way if you prize safety.


If you using other environment, you can clone the Stack Programming Language repository using `git` and build it using `cargo`, the Rust package manager.
Make sure you have Rust and Git installed on your system before proceeding.

```bash
git clone https://github.com/Stack-Programing-Community/Stack-Programing-Language.git
cd Stack-Programing-Language
cargo build --release
cargo install --path .
```

This will install the `stack` command, which you can use to run Stack programs.
