# 🚀 Guia de Instalação — CAF Assistente

Escolha o método de instalação de sua preferência abaixo:

* [Método 1: Instalar como Extensão de Navegador (Recomendado — Sem plugins adicionais)](#-método-1-instalar-como-extensão-de-navegador-recomendado)
* [Método 2: Instalar via Tampermonkey (Userscript)](#-método-2-instalar-via-tampermonkey-userscript)

---

## 🧩 Método 1: Instalar como Extensão de Navegador (Recomendado)

A instalação como extensão nativa é a forma mais simples e rápida: não precisa de plugins extras e o assistente fica integrado diretamente ao seu navegador.

### 📥 1. Downloads dos Pacotes da Extensão

Baixe o arquivo `.zip` correspondente ao seu navegador:

* 🦊 **Mozilla Firefox:** [Download CAF_Assistente_Firefox.zip](https://raw.githubusercontent.com/jvitoragr/CAF_pre_cadastro/main/Instala%C3%A7%C3%A3o/Extens%C3%A3o%20para%20Navegadores/CAF_Assistente_Firefox.zip)
* 🌐 **Google Chrome / Microsoft Edge / Brave / Opera:** [Download CAF_Assistente_Chrome_Edge.zip](https://raw.githubusercontent.com/jvitoragr/CAF_pre_cadastro/main/Instala%C3%A7%C3%A3o/Extens%C3%A3o%20para%20Navegadores/CAF_Assistente_Chrome_Edge.zip)

---

### 🦊 2. Como Instalar no Mozilla Firefox

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

✅ **Pronto!** O ícone do CAF aparecerá na barra do Firefox e o assistente abrirá automaticamente ao acessar o site oficial do [CAF oficial (caf.mda.gov.br)](https://caf.mda.gov.br/).

---

### 🌐 3. Como Instalar no Google Chrome, Microsoft Edge, Brave ou Opera

1. **Baixe e extraia** o arquivo `CAF_Assistente_Chrome_Edge.zip` em uma pasta no seu computador.
2. Abra o seu navegador (**Chrome**, **Edge**, **Brave** ou **Opera**).
3. Na barra de endereços, digite:
   * No **Google Chrome / Brave:** `chrome://extensions`
   * No **Microsoft Edge:** `edge://extensions`
   * No **Opera:** `opera://extensions`
4. No canto superior direito da tela, **ative a chave "Modo do desenvolvedor"**.
5. No canto superior esquerdo, clique no botão **"Carregar sem compactação"** (Load unpacked).
6. Selecione a pasta que você descompactou (a pasta onde estão os arquivos `manifest.json`, `content_script.js`, etc.).
7. Clique em **"Selecionar pasta"**.

✅ **Pronto!** A extensão será instalada e ativada imediatamente na barra de ferramentas do seu navegador.

---

## 🐒 Método 2: Instalar via Tampermonkey (Userscript)

Se você já utiliza ou prefere o gerenciador de userscripts **Tampermonkey**:

### 1. Instalar a Extensão Tampermonkey
* [Tampermonkey para Google Chrome](https://chromewebstore.google.com/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo)
* [Tampermonkey para Microsoft Edge](https://microsoftedge.microsoft.com/addons/detail/tampermonkey/iikmkjmpaadaobahmlepeloendndfphd)
* [Tampermonkey para Mozilla Firefox](https://addons.mozilla.org/pt-BR/firefox/addon/tampermonkey/)

---

### 2. Instalar o Script do CAF Assistente

Escolha uma das opções abaixo para instalar o script no Tampermonkey:

#### ⚡ Opção A: Instalação Automática via URL (Recomendado)
1. Copie a URL direta do script protegido:
   ```text
   https://raw.githubusercontent.com/jvitoragr/CAF_pre_cadastro/refs/heads/main/Instala%C3%A7%C3%A3o/Script%20Tampermonkey/CAF_Assistente_Protegido.js
   ```
2. No seu navegador, clique no ícone do **Tampermonkey** e abra o **Painel de Controle** (*Dashboard*).
3. Clique na aba **Utilitários** (*Utilities*).
4. Na seção **"Instalar de URL"** (*Install from URL*), cole o link copiado no campo de texto e clique em **Instalar**.
5. Na tela de confirmação, clique em **Instalar** (ou *Confirmar Instalação*).

#### 🛠️ Opção B: Instalação Manual (Copiar e Colar)
1. Abra o arquivo [`CAF_Assistente_Protegido.js`](Script%20Tampermonkey/CAF_Assistente_Protegido.js) no repositório.
2. Clique no botão **Raw** (ou selecione e copie todo o código).
3. Abra o ícone do **Tampermonkey** no navegador e clique em **Criar novo script...** (ícone de **+**).
4. Apague qualquer código existente no editor, cole o código copiado e pressione `Ctrl + S` para salvar.

---

## 💡 Principais Recursos do CAF Assistente

* 📂 **Importação e Persistência Automática (F5):** Ao carregar um arquivo JSON, os dados ficam salvos mesmo se recarregar a página.
* ⏏️ **Botão de Ejetar (⏏️):** Mostra o nome do arquivo carregado e permite limpar a memória para um novo atendimento com 1 clique.
* 👥 **Inserção Automática de Membros:** Preenchimento inteligente com verificação de quem já está cadastrado.
* 🏠 **Preenchimento de Endereço:** Dados de localização da UFPA inseridos com verificação automática.
* 🛰️ **Mapa com Satélite Híbrido e Altura de 650px:** Visualização nítida de satélite com nomes de ruas, estradas e córregos para identificar a propriedade rural com facilidade.
* 🌾 **Aba de Renda e Produtos:** Inserção em lote de produtos comercializados com cálculo automático.
* 📁 **Comprovantes e PDFs em Lote:** Módulo de anexo direto de documentos ao CAF com detecção anti-duplicidade e botão individual `+ Inserir`.
* 🖥️ **Posicionamento Inteligente:** Inicia minimizado no canto inferior esquerdo sem cobrir os botões de ação do portal oficial.

---

**Desenvolvido por João Vitor Toledo**  
*Engenheiro Agrônomo, Mestre em Produção Vegetal, Doutor em Meteorologia Agrícola*  
GitHub: [@jvitoragr](https://github.com/jvitoragr)
