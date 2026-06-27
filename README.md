# sent - ferramenta de apresentação (Custom Build)

Ferramenta minimalista de apresentações em texto puro, baseada no [sent](https://tools.suckless.org/sent/), com um novo atalho de navegação e paleta de cores otimizada para conforto visual.

## 🚀 Novos Recursos

* **Navegação direta (ir para o slide N):** foi implementado um recurso exclusivo (não existente nos patches oficiais). Agora é possível saltar diretamente para qualquer slide durante a apresentação:
    1. Pressione a tecla `g`.
    2. Digite o número do slide desejado.
    3. Pressione `Enter` para confirmar (ou `Esc` para cancelar).

## Visual e aparência
* **Cores invertidas:** a paleta de cores padrão (texto preto no fundo branco) foi substituída de forma fixa por **texto branco sobre fundo preto**.
* **Fonte fallback:** adicionada a fonte `bebas neue` ao array de fallbacks para melhor consistência tipográfica em diferentes sistemas.

## Notas de Build
* A regra `clean` do `Makefile` agora remove automaticamente o `config.h` compilado, facilitando testes de novas configurações.
