# Participantes da KERNEL

## Sobre este repositório

Este repositório é uma lista pública e open-source dos participantes da KERNEL.

---

## Como adicionar o seu card

### 1. Crie um fork do repositório
Clique em "Fork" para criar sua própria cópia do repositório.

### 2. Clone seu fork
```bash
git clone https://github.com/SEU_NOME/participantes.git
cd participantes
```

### 3. Crie uma branch com o seu nome
```bash
git switch -c card/seu-nome
```

### 4. Adicione o seu card
Abra o [arquivo HTML](./index.html) e procure a linha abaixo.
```
SEU CARD VAI ABAIXO DESSE COMENTÁRIO
Copie o bloco acima, cole aqui e preencha:
 - src="https://github.com/YOUR_USERNAME.png"
 - alt="Seu Nome"
 - card-name: seu nome
 - card-role: seu cargo ou grau
 - card-bio: 1-2 sentenças sobre você
 - href: seu URL de perfil do GitHub
```

Clone a div abaixo disso e preencha com os seus dados:
Exemplo:
```
<div class="card">
    <img
        class="card-avatar"
        src="https://github.com/jhermesn.png"
        alt="Jorge Hermes avatar"
    />
    <p class="card-name">Jorge Hermes</p>
    <p class="card-role">Founder · KERNEL</p>
    <p class="card-bio">
    Estudante de Engenharia de Software na UEPA. Amo construir comunidades,
    ensinar Git e paraense com muito orgulho.
    </p>
    <a class="card-link" href="https://github.com/jhermesn" target="_blank">
        GitHub →
    </a>
</div>
```

### 5. Salve e commite
```bash
git add .
git commit -m "add card: Seu nome"
```

### 6. Dê Push
```bash
git push -u origin card/seu-nome
```

### 7. Abra o PR
Vá na página do seu fork e clique **Compare & pull request**. Escreva um título curto `Add card: Seu Nome` e submeta.