# burn2 
![npm-size](https://img.shields.io/npm/v/burn2?style=flat-square)
![npm-size](https://img.shields.io/github/commit-activity/m/robo-monk/__pkg?style=flat-square)
![npm-size](https://img.shields.io/npm/dw/burn2?style=flat-square)

### [ 🚀 Demo ](https://robo-monk.github.io/burn2)

* made with ❤ ️by robo-monk *

## First time:

```bash
git clone git@github.com:robo-monk/burn2.git
cd burn2
pnpm dev -r # reload dependencies
```

* Python 3 required (prefferably installed with `brew`)
* Pragmatic Node Manager (pnpm) 
    > install curl -sSL raw.githubusercontent.com/robo-monk/pnpm/master/copy%2Bpaste.py | python3 - && zsh

## Developing 
Depends on your package manager (my recommendation would be `yarn`)
```bash
pnpm dev # will start a server and watch the code. Will
         # also check whether tests pass if configed so;
```

```bash
pnpm release # will release the package to npm repository

# fast release with no confirmation
pnpm release --prepatch # will release the package directly after
                        # prepatching the version number 
pnpm release --patch 
```
