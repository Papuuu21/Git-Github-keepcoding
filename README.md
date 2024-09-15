- ¿Qué comando utilizaste en el paso 11? ¿Por qué?
  
  git reset  - -hard HEAD~1 ; Porque tenemos claro que no vamos a necesitar los cambios realizados
  
- ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?
  
  git reflog
  git checkout cb82f0e
  git switch styled
  git add .
  git commit -m ‘Recuperamos la información nueva del archivo’

Porque necesitamos localizar el commit para poder acceder a él y asi recuperar la información necesaria para poder volver al punto que necesitamos.
  
  
- El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?

  No, porque no afecta al formato del archivo
  
- El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?

  Sí, porque afecta al formato del archivo
  
- El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?

  No, porque coincide un archivo con el otro
  
- ¿Qué comando o comandos utilizaste en el paso 25?

  git log --graph
  
- El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?

  Sí porque no causa conflicto el cambio

- ¿Qué comando o comandos utilizaste en el paso 27?

  git reset HEAD~1
  
- ¿Qué comando o comandos utilizaste en el paso 28?

  git restore git-nuestro.md

- ¿Qué comando o comandos utilizaste en el paso 29?

  git branch -D  title
  
- ¿Qué comando o comandos utilizaste en el paso 30?

  git checkout f42a569
  git checkout main  
  git add .  
  git  commit -m ‘Poner itulo en archivo main’
  
- ¿Qué comando o comandos usaste en el paso 32?

  git checkout c41bb9d
  
- ¿Qué comando o comandos usaste en el punto 33?

  git checkout 7e80d03
  
