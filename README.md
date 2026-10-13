# Conversor de moeda 🚀

Um projeto para ajuda você quando for realizar uma viagem. Nesse projeto você consegue converte Real, para Dolar, Euro ou Libra Esterlina 

## 📌 Status do Projeto
✅ Finalizado

## 📷 Demonstração
![image](https://github.com/user-attachments/assets/18e97358-187c-439b-968a-bbcda4dd9bc7)

## ✨ Funcionalidades
- Informar um valor em reais (o campo aceita apenas números) e escolher a moeda de destino (Dólar, Euro ou Libra Esterlina)
- Converter o valor usando a cotação do dia e exibir a cotação utilizada e o total convertido

> As cotações (USD, EUR, GBP) estão fixas em `scripts.js` — não há integração com uma API de câmbio em tempo real. Para refletir a cotação atual, atualize manualmente as constantes `USD`, `EUR` e `GBP` nesse arquivo.

## 🔧 Tecnologias utilizadas
- HTML5
- CSS
- JavaScript (vanilla, sem frameworks nem build)

## 📁 Estrutura do projeto

```
index.html      Estrutura da página (formulário de conversão e resultado)
styles.css      Estilos da aplicação
scripts.js      Lógica de conversão de moeda
img/            Logo e ícones usados na interface
```

## ▶️ Como executar

Por ser um projeto estático (sem build), basta abrir o `index.html` diretamente no navegador ou servir a pasta com qualquer servidor local, por exemplo:

```bash
npx serve .
```

ou, usando a extensão **Live Server** do VS Code, clicando com o botão direito em `index.html` → "Open with Live Server".
