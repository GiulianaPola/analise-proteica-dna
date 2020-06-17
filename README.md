<h1 align="center">🔬 Análise de Sequências da Enzima Catalase em Diferentes Organismos</h1>

<p align="center">
  <a href="https://opensource.org/licenses/MIT"><img src="https://img.shields.io/badge/license-MIT-green.svg" alt="MIT License"></a>
  <img src="https://img.shields.io/badge/status-finalizado-green" alt="Status do Projeto">
  <img src="https://img.shields.io/badge/python-3.10-blue" alt="Python Version">
</p>

---

## 📚 Sumário

- [🧾 Descrição](#-descrição)
- [🛠️ Tecnologias e Ferramentas](#-tecnologias-e-ferramentas)
- [📂 Estrutura do Projeto](#-estrutura-do-projeto)
- [📦 Pré-requisitos](#-pré-requisitos)
- [⚙️ Instalação](#️-instalação)
- [🚀 Como Usar](#-como-usar)
- [📊 Demonstrações](#-demonstrações)
- [🤝 Contribuição](#-contribuição)
- [👥 Colaboradores](#-colaboradores)
- [📄 Licença](#-licença)
- [🔗 Referências](#-referências)

---

## 🧾 Descrição

Este projeto tem como objetivo a análise bioinformática da enzima **catalase**, utilizando dados reais de sua sequência proteica em quatro organismos diferentes:

- 🐭 **Camundongo**
- 🐶 **Cão**
- 🐄 **Gado-doméstico**
- 🧍 **Humano**

As funcionalidades principais incluem:

- Leitura e análise de arquivos no formato FASTA.
- Identificação e contagem de aminoácidos.
- Geração de gráficos de frequência.
- Comparação entre sequências de diferentes organismos.
- Simulação de mutações aleatórias e comparação com as sequências originais.

---

## 🛠️ Tecnologias e Ferramentas

<p align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" height="30" alt="Python"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/numpy/numpy-original.svg" height="30" alt="NumPy"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/matplotlib/matplotlib-original.svg" height="30" alt="Matplotlib"/>
</p>

---

## 📂 Estrutura do Projeto

```
├── DNA/
│   ├── Camundongo.fasta
│   ├── Cão.fasta
│   ├── Gado-doméstico.fasta
│   ├── Humano.fasta
│   └── Aminoacidos.txt
├── Analise_DNA/
│   └── *.png (Gráficos gerados)
├── main.py
├── Graficos.py
├── Comparar_DNA/
├── Mutação_DNA/
└── Trabalho.pdf
```

---

## 📦 Pré-requisitos

- Python 3.10 ou superior
- Bibliotecas Python:
  - `matplotlib`
  - `numpy`

---

## ⚙️ Instalação

Clone o repositório e instale as dependências:

```bash
git clone https://github.com/seu-usuario/seu-repositorio.git
cd seu-repositorio
pip install matplotlib numpy
```

---

## 🚀 Como Usar

Execute o programa principal:

```bash
python main.py
```

Escolha uma das opções no menu interativo:

- `1`: Identificar aminoácidos e gerar histogramas.
- `2`: Comparar pares de organismos.
- `3`: Simular mutações nas sequências proteicas.

---

## 📊 Demonstrações

### 🔎 Gráfico de frequência de aminoácidos

<p align="center">
  <img src="Analise_DNA/Catalase de 4 organismos.png" alt="Exemplo de Gráfico de Aminoácidos" width="600"/>
</p>

### 🔬 Comparação de Sequência Proteica

Trecho do arquivo de comparação:

```
Catalase de CAMUNDONGO e CÃO
Posição |    Camundongo |          Cão
     1   |          S     |          A
    13   |          Q     |          L
    20   |          S     |          A
    22   |          R     |          K
    40   |          I     |          V
    ...
   530   |          G     |          E
Semelhança: 92,91%
```
---

## 🤝 Contribuição

Contribuições são muito bem-vindas!

1. Fork este repositório.
2. Crie uma branch (`git checkout -b feature-minha-ideia`).
3. Commit suas mudanças (`git commit -m 'feat: nova feature'`).
4. Push para a branch (`git push origin feature-minha-ideia`).
5. Abra um Pull Request.

Considere adicionar testes e seguir boas práticas de código.

---

## 👥 Colaboradores

<table>
  <tr>
    <td align="center">
      <img src="https://avatars.githubusercontent.com/u/00000000?v=4" width="100px;" alt="Diego Zago Brito"/>
      <br/>
      <sub><b>Diego Zago Brito</b></sub><br/>
    </td>
    <td align="center">
      <img src="https://avatars.githubusercontent.com/u/92754890?v=4" width="100px;" alt="Giuliana Pola"/>
      <br/>
      <sub><b>Giuliana Pola</b></sub><br/>
    </td>
  </tr>
</table>

---

## 📄 Licença

Este projeto está licenciado sob os termos da licença [MIT](LICENSE).

---

## 🔗 Referências

- [Protein Information Resource](https://proteininformationresource.org/)
- [Formato FASTA - Wikipedia](https://pt.wikipedia.org/wiki/Formato_FASTA)
- [Tabela de Aminoácidos (IUB Codes)](https://emunix.emich.edu/~evett/BioinformaticsTools/IUB%20Codes.htm)