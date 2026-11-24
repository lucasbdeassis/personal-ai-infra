# instructions

Always use the relevant skills before proceeding; they contain important instructions and guidelines.

Before writing or editing files, invoke the matching skills (all of the ones that apply, e.g.: programming and python).

| Extension | Skill |
|-----------|--v----|
| `*.md` | /markdown |
| `*.py` | /python |
| `*test*` | /software-testing |
| any code | /programming |

## misc

- If you encounter difficulties running commands or tests, ask for help and relay the error messages to me.
  - I can always install any dependencies you need.
- If you detect a file has changed since you last saw it, match its new style or content instead of reverting it to what you last remember, as the humans (or other agents) probably made an edit to help you.
- Do not use large blocks of characters to atract attention like `==== THING ====`; they're ugly.
- Do not attempt to use GitHub's `gh` CLI nor Gitlab's `glab` unless explicitly told to do so.

## Testes locais e GitHub Actions

- Execute localmente os testes e as validações aplicáveis antes de abrir ou
  atualizar um PR ou publicar diretamente na branch de deploy. Registre no PR
  os comandos, os resultados e qualquer validação pendente.
- O PR não executa essa validação. Reserve GitHub Actions para deploy na VPS,
  incluindo artefatos necessários à publicação e a conferência de saúde do
  serviço publicado. Mantenha testes, lint e revisão de PR fora do Actions.
