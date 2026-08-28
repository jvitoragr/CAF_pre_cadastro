# 🚀 Guia de Instalação — Extensão CAF Assistente

Este guia ensina como instalar o **CAF Assistente** diretamente como extensão no seu navegador (sem precisar de Tampermonkey ou configurações avançadas).

---

## 📥 1. Downloads dos Pacotes da Extensão

Baixe o arquivo `.zip` correspondente ao seu navegador abaixo:

* 🦊 **Mozilla Firefox:** [Download CAF_Assistente_Firefox.zip](https://raw.githubusercontent.com/jvitoragr/CAF_pre_cadastro/main/Extensao/CAF_Assistente_Firefox.zip)
* 🌐 **Google Chrome / Microsoft Edge / Brave / Opera:** [Download CAF_Assistente_Chrome_Edge.zip](https://raw.githubusercontent.com/jvitoragr/CAF_pre_cadastro/main/Extensao/CAF_Assistente_Chrome_Edge.zip)

---

## 🦊 2. Como Instalar no Mozilla Firefox

1. **Baixe e extraia** o arquivo `CAF_Assistente_Firefox.zip` em uma pasta no seu computador (por exemplo, na sua pasta de *Documentos* ou *Downloads*).
2. Abra o **Mozilla Firefox**.
3. Na barra de endereços (onde digita os sites), digite:
   ```text
   about:debugging#/runtime/this-firefox
   ```
   *(ou digite `about:debugging` e clique em **"Este Firefox"** na lateral esquerda)*.
4. Clique no botão **"Carregar extensão temporária..."** (Load Temporary Add-on).
5. Navegue até a pasta que você extraiu e selecione o arquivo **`manifest.json`**.
6. Clique em **Abrir**.

✅ **Pronto!** O ícone do CAF aparecerá no topo do seu Firefox e o assistente abrirá automaticamente ao acessar o site do [CAF oficial (caf.mda.gov.br)](https://caf.mda.gov.br/).

---

## 🌐 3. Como Instalar no Google Chrome, Microsoft Edge ou Brave

1. **Baixe e extraia** o arquivo `CAF_Assistente_Chrome_Edge.zip` em uma pasta no seu computador.
2. Abra o seu navegador (**Chrome**, **Edge** ou **Brave**).
3. Na barra de endereços, digite:
   * No **Chrome / Brave:** `chrome://extensions`
   * No **Microsoft Edge:** `edge://extensions`
4. No canto superior direito da tela, **ative a chave "Modo do desenvolvedor"**.
5. No canto superior esquerdo, clique no botão **"Carregar sem compactação"** (Load unpacked).
6. Selecione a pasta que você descompactou (a pasta onde estão os arquivos `manifest.json`, `content_script.js`, etc.).
7. Clique em **"Selecionar pasta"**.

✅ **Pronto!** A extensão será instalada e ativada imediatamente na barra de ferramentas do seu navegador.

---

## 💡 Recursos da Extensão
* 📂 **Importação Rápida de JSON:** Carregamento instantâneo dos dados do pré-cadastro familiar.
* 👥 **Inserção Automática de Membros:** Preenchimento dos dados do declarante e membros familiares com 1 clique.
* 🏠 **Preenchimento de Endereço:** Dados de localização da UFPA inseridos automaticamente.
* 🏞️ **Áreas e Imóveis da UFPA:** Tabela de áreas integrada com seleção simplificada.
* 🌾 **Aba de Renda e Produtos:** Inserção em lote de produtos comercializados.
* 📁 **Comprovantes e PDFs em Lote:** Módulo de anexo direto de documentos ao CAF.
* 🖥️ **Posicionamento Inteligente:** Inicia minimizado no canto inferior esquerdo sem cobrir os botões de ação do sistema.

---
**Desenvolvido por João Vitor Toledo**  
*Engenheiro Agrônomo, Mestre em Produção Vegetal, Doutor em Meteorologia Agrícola*
