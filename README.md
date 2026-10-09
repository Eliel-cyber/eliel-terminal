<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:6b3dff,100:21f3ff&height=160&section=header&text=ELIEL%3A%2F%2FTERMINAL&fontSize=38&fontColor=ffffff&fontAlignY=38&animation=fadeIn" alt="ELIEL://TERMINAL" width="100%">

<a href="https://eliel-cyber.github.io/eliel-terminal/"><img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=18&pause=1200&color=21F3FF&center=true&vCenter=true&width=520&lines=%3E+iniciando+sistema...;%3E+carregando+m%C3%B3dulos%3A+erp+%C2%B7+estoque+%C2%B7+excel;%3E+bem-vindo+ao+terminal+do+Eliel" alt="Animação de digitação"></a>

<br>

[![Abrir o terminal](https://img.shields.io/badge/%E2%96%B6%20ABRIR%20O%20TERMINAL-0d0820?style=for-the-badge&logoColor=21f3ff&labelColor=6b3dff&color=0d0820)](https://eliel-cyber.github.io/eliel-terminal/)

![HTML5](https://img.shields.io/badge/HTML5-0d0820?style=flat-square&logo=html5&logoColor=E34F26)
![CSS3](https://img.shields.io/badge/CSS3-0d0820?style=flat-square&logo=css3&logoColor=1572B6)
![JavaScript](https://img.shields.io/badge/JavaScript-0d0820?style=flat-square&logo=javascript&logoColor=F7DF1E)
![Sem bibliotecas](https://img.shields.io/badge/depend%C3%AAncias-0-21f3ff?style=flat-square&labelColor=0d0820)

</div>

---

## `> sobre`

Um **terminal interativo com visual cyberpunk** que funciona como meu cartão de visitas. Em vez de ler um currículo, a pessoa digita comandos e descobre quem eu sou, onde trabalhei e o que já construí.

Feito em **um único arquivo HTML**, com CSS e JavaScript puros, sem nenhuma biblioteca.

## `> recursos`

| | |
|---|---|
| 🟣 **Chuva de código** | animação em `<canvas>` no fundo da tela |
| ⌨️ **Comandos de verdade** | `sobre`, `experiencia`, `skills`, `projetos`, `formacao`, `contato`, `limpar` |
| ✨ **Efeito de digitação** | as respostas aparecem letra por letra, como num terminal |
| ⚡ **Efeito glitch** | no nome, feito só com CSS |
| 📊 **Painel de STATUS** | barras animadas com o nível de cada competência |
| ↕️ **Histórico** | setas ↑ e ↓ repetem comandos anteriores |
| 📱 **Responsivo** | botões clicáveis para quem está no celular |
| ♿ **Acessível** | respeita a configuração de reduzir animações do sistema |

## `> como usar`

Acesse **[eliel-cyber.github.io/eliel-terminal](https://eliel-cyber.github.io/eliel-terminal/)** e digite `ajuda`.

Ou rode no seu computador: baixe o `index.html` e abra no navegador. Não precisa instalar nada.

```text
eliel@cyber:~$ ajuda
Comandos disponíveis:
  sobre        quem sou eu
  experiencia  onde trabalhei
  skills       sistemas e competências
  projetos     o que já construí
  ...
```

> 🥚 Tem um easter egg escondido. Tente usar `sudo`.

## `> como funciona`

- **Fundo animado:** um `<canvas>` desenha caracteres em colunas que caem a cada 55 ms.
- **Comandos:** um objeto JavaScript liga cada comando ao texto da resposta. Também aceita apelidos, como `help` e `clear`.
- **Digitação:** uma função `async` escreve cada resposta aos poucos, com pequenas pausas.
- **Glitch:** os pseudo-elementos `::before` e `::after` duplicam o nome em rosa e ciano e o deslocam em momentos aleatórios.

---

<div align="center">

**Eliel Dias** · [LinkedIn](https://www.linkedin.com/in/elieldias) · [Portfólio](https://eliel-cyber.github.io) · [Outro projeto: relatorio-estoque](https://github.com/Eliel-cyber/relatorio-estoque)

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:21f3ff,100:6b3dff&height=90&section=footer" width="100%" alt="">

</div>
