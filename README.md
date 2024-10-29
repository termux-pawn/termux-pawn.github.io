![Logo](https://raw.githubusercontent.com/termux-pawn/termux-pawn.github.io/refs/heads/main/images%20(8).png)

# ⚙️ Termux Pawn

**Termux Pawn** é um repositório APT otimizado para o desenvolvimento de scripts em PAWN, com foco no [SA-MP](https://www.sa-mp.com/), [Open.MP](https://www.open.mp/), e plataformas relacionadas. Simplifique o setup do ambiente no Termux e instale pacotes `.deb` necessários para desenvolver, compilar e testar seus scripts de forma ágil e eficiente. 

## ✨ Funcionalidades

- 📦 **Compilador PAWN**: Instale e mantenha atualizado o compilador PAWN diretamente no Termux.
- 🔍 **Ferramentas de Debug**: Pacotes especializados para facilitar o processo de debug e análise de scripts.
- 🚀 **Ambiente Otimizado**: Um ecossistema completo de pacotes, pensado para desenvolvedores PAWN no Termux.

## 🔧 Pré-requisitos

- **Termux**: Certifique-se de que o Termux está instalado e atualizado.
- **Conexão com a Internet**: Para adicionar o repositório e instalar pacotes.

## 📥 Instalação

### 1️⃣ Adicione o Repositório Termux Pawn

Abra o Termux e adicione o repositório com o comando abaixo:

```bash
echo "deb [trusted=yes arch=all] https://termux-pawn.github.io/repo stable main" >> $PREFIX/etc/apt/sources.list
```
### 2️⃣ Atualize a Lista de Pacotes

Em seguida, atualize o cache do APT para que os novos pacotes fiquem disponíveis:

```bash
apt update
```

### 3️⃣ Instale os Pacotes Necessários

Agora você pode instalar qualquer pacote do repositório Termux Pawn. Por exemplo, para instalar o compilador PAWN:

```
apt install -y pawncc
```

## 📂 Pacotes Disponíveis

- **pawncc:** Compilador PAWN v3.10.10 para SA-MP e open.mp

- **pawncc-11:** Compilador PAWN v3.10.11 para open.mp

## 📂 Pacotes Planejados

- **pawn-help:** Um manual com tutoriais e explicações sobre o compilador PAWN

- **mobile-pawn-kit:** Uma ferramenta inspirada no [sampctl](https://github.com/Southclaws/sampctl)

## 📜 Licença

Este projeto está sob a licença MIT!

---

## 🎉 Aproveite o Termux Pawn para elevar seu desenvolvimento em PAWN no Termux a outro nível!
