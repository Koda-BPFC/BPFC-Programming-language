# 📜 BPFC - Basic Programming for Children

A **BPFC** é uma linguagem de programação funcional e visual, desenvolvida para o motor **FMPME**. Ela utiliza um sistema de cores e lógica de "escada" para tornar o desenvolvimento de jogos 2D simples para crianças.

## 🛠️ Dicionário de Símbolos

* ⚪ **Começador (Cinza):** Inicia o código com `If` ou `When`.
* 🟣 **Interpretador (=) (Roxo):** Processa a ação à frente.
* 🟠 **Alinhador (-) (Laranja):** Conecta comandos e distribui valores.
* 🔴 **Ator ("") (Vermelho):** O alvo ou nome do objeto.
* 🟢 **Criador (Verde):** Comando `Create-("");` para spawnar objetos.
* 🔵 **Valorizador (Azul):** Define números e velocidades (`valorS4`).
* ⚫ **Colorador (Preto):** Define a cor do objeto (`ColorS7`).
* 🧹 **Limpador (He finished):** Finaliza o script e limpa a memória.
* 🔚 **Finalizador (End):** Fecha os blocos da escada.

## 📝 Exemplo de Código

When this starts-
  name It("Script_Bola")=
  Then he Will now go-
  create=("ball")-
  colorS4("red")
  He finished("Script_Bola")
End End End
