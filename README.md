# Learning Path: Haskell: FP

## Udemy Tutorials

- Compile: `ghc <filename>.hs`
- Run w/ Type Check: `stack runghc <filename>.hs`
- Compile (but not run): `stack ghc -- -fno-code <filename>.hs`. `--` begins subargs.
- GHC == Glasgow Haskell Compiler
- GHCI == Glasgow Haskell Compiler Interactive
- REPL `stack ghci`
- In REPL:
  - Run Shell Command `> :!<shellcmd>` ex: `> :!ls`
  - View Type `> :type <varname>`
  - View Kind `> :kind <varname>` (Num, Maybe, Monad, Monoid)
  - View Info `> :info <varname>` (Num)
  - Load Program `> :load <filename>.hs`
  - Run Function `> :run <functionname>`
  - Reload Imported Files `> :reload`
  - Run Main of File in REPL `:main`
  - Debugging (set breakpoints, step through and check thunks and value) `:sprint :list :continue` `:show breaks` `:abandon
  -
- Primitive Types
  - Char
  - Integer
  - Int
  - Float, Double
  - Everything else is defined in terms of these

## Further Resources

- http://haskellbook.com/progress.html
- https://code.fb.com/security/fighting-spam-with-haskell/
