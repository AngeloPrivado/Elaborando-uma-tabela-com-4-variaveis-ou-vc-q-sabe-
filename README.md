# Elaborando-uma-tabela-com-4-variaveis-ou-vc-q-sabe-
Neste código elaboro uma tabela com 4 variáveis (4 Mcs) na plataforma RStudio


# ⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣯⣥⣤⣾⠟⡛⠿⠿⣭⣻⢿⣿⣿⣿⣿⣿⣿⣿⣿⣿
# ⣿⣿⣿⣿⣿⣿⣿⣿⡟⣿⣽⡟⡏⢩⣦⡝⠋⢸⣶⠄⢲⡟⣿⣿⣿⣿⣿⣿⣿⣿
# ⣿⣿⣿⣿⣿⣿⣿⣯⣷⣿⣿⣿⣿⣿⣿⣿⣿⣷⣶⣌⡳⣜⢿⣿⣿⣿⣿⣿⣿⣿
# ⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡇⢀⡛⢌⢿⣿⣿⣿⣿⣿
# ⣿⣿⣿⣿⣿⢸⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⠁⠄⠙⠌⣸⣿⣿⣿⣿⣿
# ⣿⣿⣿⣿⣿⡿⠉⠉⠉⠉⢿⣿⣿⣿⠏⠉⠉⠉⠉⠉⠆⠄⠁⠄⣿⣿⣿⣿⣿⣿
# ⣿⣿⣿⣿⣿⡗⠫⠿⠆⠄⠸⢿⣿⣿⠂⠒⠲⡿⠛⠛⠂⠄⠄⢠⣿⣿⣿⣿⣿⣿
# ⣿⣿⣿⣿⡛⣧⡔⠢⠴⣃⣠⣼⣿⣧⡀⠘⢢⣀⠄⠄⠄⠄⠄⢈⠁⢿⣿⣿⣿⣿
# ⣿⣿⣿⣿⣿⣿⣿⣾⣿⣿⣿⣿⣿⣿⣿⣿⣿⣷⣶⣿⠄⠄⠄⣸⠆⣿⣿⣿⣿⣿
# ⣿⣿⣿⣿⣿⣿⣿⣿⣿⡿⣿⣿⣿⣿⣼⢿⣿⣿⣿⣿⡀⠄⠘⡀⢠⣿⣿⣿⣿⣿
# ⣿⣿⣿⣿⣿⡌⠿⣫⣿⣦⠬⢭⣥⣶⣬⣾⣿⢿⣿⡟⠄⢀⣿⣶⣿⣿⣿⣿⣿⣿
# ⣿⣿⣿⣿⣿⣧⠘⣉⠛⢻⣛⣛⣛⣻⡶⠮⠙⠃⣉⠄⠄⢸⣿⣿⣿⣿⣿⣿⣿⣿
# ⣿⣿⣿⣿⣿⣿⡆⠸⣿⣶⢾⣿⣯⣤⣄⣀⣾⡟⠄⠄⠄⢸⣿⣿⣿⣿⣿⣿⣿⣿
# ⠟⠿⠿⠿⠿⢿⣷⠄⣿⣿⣎⣹⢻⣿⣿⡿⡿⠁⠄⠄⠄⢸⣿⣿⣿⣿⣿⣿⣿⣿
# ⠄⠄⠄⠄⠄⠄⠄⣠⠘⣿⣿⣿⣿⣿⣿⡟⠁⣀⣀⣀⠄⠘⠿⣿⣿⣿⣿⣿⣿⣿



  # EU tenho 4 nomes de Mcs que cantam funk/trap

  # Poze do rodo, Hariel, Orochi, e Paulinho da capital.
  # Tenho a idade de cada um respectivamente 23, 24, 21, 23. 
  # Tenho os videos mais vistos de cada um respectivamente 183M, 11M, 187M, 114M.
  # Tenho a quantidade de seguidores no insta de cada um respectivamente 6M, 8.5M, 5.8M, 806k.

  # Entao de posse dessas informações vamos elaborar uma tabela:

# --- PASSO1 
# ATRIBUINDO A PALAVRA "nome" PARA CRIAR UMA CATEGORIA.
nome=c("Poze_do_Rodo","Hariel","Orochi", "Paulinho_da_capital")

# --- PASSO2 
# VC UTILIZARA UMA FUNCAO CHAMADA "data.frame" E DENTRO DELA COLOCARA TUDO OQ FOI FEITO NO PASSO1 MAIS A IDADE, MAIS AS VIZUALIZACOES, MAS SEGUIDORES DO INSTAM.
# LEMBRANDO QUE ESSES NOMES COMO ("nome", "idade", "yiutube" e "insta") VC QUE DEVE ELABORAR ou inventar, use sua criatividade.
# Após isso use a setinha de atribuição e chame tudo isso que foi pedido de "tabela de mcs", "lista de mcs" ou só "tabela", como eu coloquei abaixo, veja como ficou:

 tabela <- data.frame(nome=c("Poze_do_Rodo","Hariel","Orochi", "Paulinho_da_capital"), 
                     idade=c(23, 24, 21, 23),                    
                     Youtube_viz=c(183, 11, 187, 114),
                     instaem1M=c(6, 8.5, 5.8, 0.806)) 



# APERTE Ctrl + Enter e PRONTO!!!! aparecerá sua tabela na janela superior direita do Rstudio, só clicar nela.
# Note que cada categoria criada possui 4 variaveis, nome tem 4, idade tem 4, youtube e insta tambem possuem 4.
# O que essa função faz, nada mais é do que "CASAR" ESSAS VARIAVEIS PARA FORMAR UMA TABELA ONDE VC PODE VER SEUS DADOS EM ORDEM CRESCENTE, DECRESCENTE OU DA MANEIRA QUE ACHAR MELHOR!
# ESSE EXEMPLO SE TRATA DE UMA DEMONTRACAO BASICA, E CLARO VC PODE USAR MUITO MAIS QUE 4 VARIAVEIS, PODE UTILIZA-LA PARA CENTENAS, MILHOES e MILHOES DE DADOS APENAS COM ESSE CODIGO, POIS CLARO, SE TRATA DA LINGUAGEM "R" A PICA DAS GALAXIAS DA ESTATISTICA.



