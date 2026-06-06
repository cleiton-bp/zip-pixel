# ZipPixel

**Deixe suas imagens mais leves em segundos — sem instalar nada e sem enviar para lugar nenhum.**

---

## O problema

Imagens pesadas atrasam sites, estouram limites de anexo e ocupam espaço à toa.
Para resolver isso, normalmente você precisa:

- instalar um programa, ou
- subir suas fotos para um site qualquer (e torcer pra ninguém guardar elas).

## A solução

O ZipPixel reduz o tamanho (KB/MB) das suas imagens **direto no navegador**.

- **Nada é enviado para servidores** — a imagem nunca sai do seu computador.
- **Não precisa instalar** — é um único arquivo `index.html`, abre com dois cliques.
- **Por padrão, escolhe sozinho** o formato que deixa o arquivo menor — você só clica em *Comprimir*.

---

## Como usar

1. Abra o **`index.html`** no navegador (duplo clique já funciona).
2. **Arraste suas imagens** para a área indicada (uma ou várias).
3. Clique em **Comprimir**.
4. Baixe as imagens otimizadas — **uma a uma** ou **todas de uma vez**.

Pronto. Você vê o **tamanho antes**, **depois** e a **% de redução** de cada imagem.

---

## Quer ajustar?

Os controles são opcionais — o padrão já entrega o melhor resultado.

- **Qualidade** — quanto comprimir (mínimo de 5).
- **Formato de saída**:
  - **Automático** *(padrão)* — testa WebP e JPEG e fica com o menor arquivo.
  - **JPEG / PNG / WebP** — força um formato específico.
  - **Manter original** — preserva o formato (mas quase não reduz o tamanho).

Aceita a maioria dos formatos de entrada: **JPG, PNG, WebP, GIF, BMP, AVIF** e mais.

---

## Privacidade

Toda a compressão acontece **no seu navegador**, usando a **Canvas API**.
Sem upload, sem nuvem, sem cadastro. O que entra no seu computador, fica no seu computador.

---

## Tecnologia

- **HTML + CSS + JavaScript puro** — sem frameworks, sem build.
- Compressão via **Canvas API** (`canvas.toBlob`).
- **Um único arquivo** (`index.html`) — fácil de copiar, hospedar e manter.

> Quer publicar online? Hospede o `index.html` em qualquer lugar
> (GitHub Pages, Netlify, Vercel ou seu próprio servidor).

---

## Extras

- **Tema claro e escuro** (segue a preferência do sistema).
- **Português, Inglês e Espanhol** (troca em tempo real).
- Botão de **doação via Pix** — o ZipPixel é gratuito e sem anúncios; se ele te
  ajudou, qualquer valor mantém o projeto no ar.

---

## Licença

Use, adapte e compartilhe à vontade.
