# Comandos Git

## Resumo dos comandos de Git da aula de Introdução a Informática.

01. pwd (pra saber onde estou)

02. cd Desktop (estamos na área de trabalho)

03. mkdir nome_da_pasta (criar pasta)

04. ls (verificar se tem algo na pasta)

05. cd nome_da_pasta (agora estou trabalhando dentro da pasta)

06. git init (cria um repositório local na pasta criada)

07. touch nome_do_arquivo (cria o arquivo)

08. git config --global user.name "Nome Sobrenome"

09. git config --global user.email "seuemail@gmail.com"

10. git add . (adiciona todos os arquivos da pasta ao índice) ou git add nome_do_arquivo.txt (adiciona apenas o arquivo específico)

11. git status (lista os arquivos novos e modificados)

12. git commit -m “Commit inicial” (confirmar as mudanças - (grava permanentemente o arquivo no histórico de versões com uma mensagem)
13. git remote add origin https://github.com/... (definindo o destino / repositório remoto)

14. git push -u origin master (diz ao git para enviar todos os commits no branch local atualmente verificado - seu sistema de arquivos)

15. origin main/master (raiz) - verificar qual está funcionando (main ou master)

16. git pull (incorpora mudanças de um repositório remoto para o branch local)

17. git clone (trás pra sua máquina - cria uma cópia)

18. git add .

19. git commit -m “Commit inicial”

20. git push origin main (onde será executado)
Atenção: a outra pessoa precisa executar o git pull pra estar com a mesma versão

21. criar o repositório no GitHub
Atenção: o arquivo só está na nuvem

22. copiar endereço do repositório

23. git clone https://github.com/... (para colar → shift+insert)

24. cd nome_do_arquivo (verificar o "main" - já vem indicando que é um repositório)

25. touch nome_do_arquivo.txt (opcional para criar outro arquivo)

26. git status

27. git add nome_do_arquivo.txt

28. git status

29. git commit -m "Criei o arquivo X"

30. git push origin main

31. git merge (fundir versões - vai combinar várias sequências de commits em um histórico unificado)

esc > :wq > enter (fechar o editor de confirmação) (editado) permanentemente o arquivo no histórico de versões com uma mensagem)

rm -rf (elimina o repositório e tudo que tem dentro dela) (editado) 


## Resumo criado pelo aluno Felipe Cabuto.
## Arquivo MD editado por Nelson Kobayashi.
## Curso de Introdução à Informática - Digital House
## Professores: Vitoria Gonçalves e Fernando Mello de Amorim