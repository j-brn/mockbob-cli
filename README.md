## mockbob

cOmMaNdLiNe uTiLiTy tO MoCk sEnTeNcEs lIkE ThIs.

### Usage

mockbob either mocks the given arguments, or reads from stdin.

```sh
mockbob Mock this for me!
```

```sh
echo "some input" | mockbob
```

The mocking strategy can also be customized. For mor information, please run

```
mockbob --help
```

### Build

```sh
git clone https://github.com/j-brn/mockbob-cli.git
cd mockbob-cli
cargo build --release
```