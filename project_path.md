# init

## download link sign
><!-- -->
>```bash <!-- markdownlint-disable-line code-block-style -->
># First make sure that the target directory exists
>mkdir -p img && curl --create-dirs --output-dir img -O  "https://raw.githubusercontent.com/MathiasStadler/link_symbol_svg/refs/heads/main/link_symbol.svg"
>```
<!-- -->
## build project - attention a rust-toolchain file is available - rust-toolchain [![alt text][1]](https://ehuss.github.io/rustup/concepts/toolchains.html)
<!-- -->
```bash <!-- markdownlint-disable-line code-block-style -->
> cargo build
info: syncing channel updates for 'nightly-2021-07-10-x86_64-unknown-linux-gnu'
info: latest update on 2021-07-10, rust version 1.55.0-nightly (240ff4c4a 2021-07-09)
info: downloading component 'cargo'
info: downloading component 'clippy'
```
<!-- -->
## run project
<!-- -->
```bash <!-- markdownlint-disable-line code-block-style -->
> cargo run
    Finished dev [unoptimized + debuginfo] target(s) in 0.02s
     Running `target/debug/perf-and-dhat-profiling-example`
{
    Some(
        Integer,
    ): 37449,
    Some(
        String,
    ): 74898,
}
```
<!-- keep the format -->
## run test
<!-- -->
```bash <!-- markdownlint-disable-line code-block-style -->
> cargo test
   Compiling perf-and-dhat-profiling-example v0.1.0 (/home/trapapa/workspce_codium/explore_perf-and-dhat-profiling-example)
    Finished test [unoptimized + debuginfo] target(s) in 0.71s
     Running unittests (target/debug/deps/perf_and_dhat_profiling_example-e4890b96d0d3cb33)

running 1 test
test tests::bench_read_csv ... ok

test result: ok. 1 passed; 0 failed; 0 ignored; 0 measured; 0 filtered out; finished in 0.07s
```
<!-- keep the format -->
## install crates hyperfine
<!-- -->
```bash <!-- markdownlint-disable-line code-block-style -->

>  hyperfine "target/debug/perf-and-dhat-profiling-example"
```
<!-- keep the format -->
>[NOTE!]
>A double dash (--) is used in most Bash built-in commands and many other commands
>to signify the end of command options, after which only positional ("non-option")
>arguments are accepted. [![alt text][1]](https://unix.stackexchange.com/questions/11376/what-does-double-dash-double-hyphen-mean/11382#11382)
<!-- keep the format -->
>[TIP!]
>cargo install --list :: list all already installed packages and their versions system wide in this context
<!-- -->
>```bash <!-- markdownlint-disable-line code-block-style -->
>cargo install --list --help 2>&1 | grep -- -list
>   --list                      list all installed packages and their versions
>  
>```
<!-- keep the format -->
## install crates temp
<!-- -->
```bash <!-- markdownlint-disable-line code-block-style -->
> 
```
<!-- keep the format -->
>[!NOTE]
>Symbol to mark web external links [![alt text][1]](./README.md)
<!-- -->
>[!TIP]
>Marker
<!-- -->
TODO: Test todo
<!-- -->
FIXME:
<!-- -->
BUG:
<!-- -->
NOTE:
<!-- -->
HACK:
<!-- -->
[ ]:<!-- -->
<!-- -->
[x]:
<!-- -->
HACK:
<!-- -->
<!-- Link sign - Don't Found a better way :-( - You know a better method? - send me a email -->
[1]: ./img/link_symbol.svg
<!-- keep the format -->