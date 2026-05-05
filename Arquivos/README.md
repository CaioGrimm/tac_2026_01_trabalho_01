# Assignment: Reprodução de Artigo em LaTeX (Formato SBC)

## 🎯 Objetivo

Reproduzir o artigo fornecido (`article.pdf`) em LaTeX utilizando o template da SBC.

---

## 📌 O que você deve fazer

Você deve recriar o artigo em LaTeX a partir do PDF fornecido, utilizando o arquivo:

```
main.tex
```

Seu objetivo é reproduzir:

* estrutura do artigo (seções)
* texto
* equações
* figuras
* referências

---

## 📁 Arquivos fornecidos

* `article.pdf` → artigo original
* `reference_sbc.pdf` → versão no formato SBC (referência visual)
* `figures/` → imagens do artigo
* `sbc-template.sty` → template SBC
* `main.tex` → arquivo inicial

---

## 🖼️ Figuras

Use as imagens da pasta `figures/`:

```latex
\begin{figure}[ht]
\centering
\includegraphics[width=0.8\linewidth]{figures/fig1.png}
\caption{Descrição da figura}
\label{fig:exemplo}
\end{figure}
```

---

## 📌 Requisitos

Seu código deve:

* compilar sem erros
* gerar um PDF (`main.pdf`)
* usar o template SBC corretamente
* conter título, autor e resumo
* conter seções organizadas
* conter figuras com `\caption` e `\label`
* conter equações (quando aplicável)

---

## ⏱️ Etapas da entrega

| Etapa | Prazo | Pontos |
|------|------|--------|
| Estrutura inicial | Dia 3 | 2 pts |
| Introdução + seção 1 | Dia 6 | 2 pts |
| Figuras e equações | Dia 9 | 2 pts |
| Texto completo | Dia 12 | 2 pts |
| Versão final | Dia 14 | 2 pts |

---

## ⏱️ Data da entrega: 12/05/2026

---


## 👤 Identificação do autor

Você deve obrigatoriamente modificar os dados do autor no arquivo `main.tex`.

Substitua as informações originais por seus próprios dados:

- Nome completo
- Instituição
- Email

Utilize o seguinte padrão:

- **Instituição:** Instituto de Computação - UFAM  
- **Endereço:** Campus Universitário  

Exemplo:

```latex
\author{Seu Nome Completo}

\address{Instituto de Computação - UFAM\\
Campus Universitário\\
\email{seuemail@ufam.edu.br}}
```
---

## 🚫 Restrições

* Não utilizar outros templates
* Não modificar `sbc-template.sty`
* Não copiar código LaTeX externo

---


## 📤 Entrega

A entrega é feita via commit neste repositório.

Cada push será automaticamente testado.

---

## 💡 Dica

Comece pela estrutura (seções) antes de preencher o conteúdo.
