# 🌱 Formulário de Pré-Cadastro da Agricultura Familiar (CAF)

Sistema web para coleta, organização e conferência prévia dos dados da Unidade Familiar de Produção Agrária (UFPA), auxiliando agricultores familiares e cadastradores na preparação das informações para o **Cadastro Nacional da Agricultura Familiar (CAF)**.

---

## 📌 Sobre o Projeto

O **Pré-Cadastro CAF** é uma aplicação de apoio e facilitação de atendimento. Ele permite que o agricultor ou técnico preencha antecipadamente todos os dados cadastrais da família, áreas exploradas, mão de obra e renda da produção, gerando um arquivo estruturado em formato `.json` que pode ser facilmente importado e conferido pelo **cadastrador oficial**.

> [!IMPORTANT]
> **Natureza Preparatória:** O preenchimento deste formulário constitui exclusivamente uma etapa de pré-cadastro e coleta de informações. Ele **não substitui, não homologa e não emite o CAF oficial**, que deve ser formalizado diretamente por um cadastrador autorizado no sistema oficial do Governo Federal.

---

## 🚀 Como Funciona o Fluxo

1. **Preenchimento dos Dados:** O usuário insere as informações familiares, dados da propriedade, coordenadas, mão de obra e notas fiscais de comercialização.
2. **Conferência e Declaração:** O usuário revisa as informações e confirma as declarações obrigatórias de veracidade (Art. 299 do Código Penal) e ciência sobre o tratamento e armazenamento dos dados.
3. **Geração do Arquivo Local (`.json`):** Ao clicar em **"Salvar como"**, o sistema gera um arquivo seguro no padrão `Pré Cadastro CAF - [Nome do Declarante].json` e realiza o download diretamente para o dispositivo.
4. **Atendimento Oficial:** O arquivo gerado é entregue ou transmitido ao cadastrador oficial do CAF (ex: técnicos do Incaper, sindicatos ou entidades credenciadas) para validação e inserção no portal oficial.

---

## 🔒 Privacidade, Armazenamento Local e LGPD

* **Armazenamento 100% Local:** Todos os dados digitados e arquivos PDF anexados são processados e armazenados **inicialmente de forma local** no próprio navegador (`localStorage` do dispositivo).
* **Sem Servidores Externos:** A aplicação não envia automaticamente quaisquer informações ou documentos para bancos de dados ou servidores externos em nuvem.
* **Segurança do Arquivo:** O arquivo JSON resultante contém dados pessoais e documentos em formato Base64. Após o download, ele deve ser mantido em local seguro e compartilhado apenas com profissionais autorizados para a realização do cadastro.
* **LGPD (Lei nº 13.709/2018):** O tratamento das informações e documentos observa as finalidades legítimas de atendimento ao agricultor familiar e preparação para o CAF, respeitando a privacidade e os direitos dos titulares de dados.

---

## 📋 Estrutura do Formulário

* **1. Membros da Família:** Identificação do titular e dos demais integrantes da UFPA (CPF, Nascimento, Sexo, Gênero, Estado Civil, Cor/Raça, Escolaridade, UF/Município de Nascimento, Parentesco, Trabalho na UFPA, Telefone e Documentos).
* **2. Endereço da UFPA:** Localização do estabelecimento principal com busca automática por CEP (ViaCEP) e padronização oficial de UFs e Municípios.
* **3. Áreas e Imóveis Rurais:** Condição de posse, tipo de área, tamanho em hectares/m³, dados do proprietário (quando aplicável), coordenadas geográficas e anexo de documento comprobatório em PDF.
* **4. Mão de Obra na UFPA:** Cadastro de trabalhadores permanentes ou temporários (homem/dia).
* **5. Renda da Propriedade e Documentos Fiscais:** Upload de DANFEs em PDF, importação de chaves de acesso da NF-e e síntese dinâmica da produção comercializada.
* **Declaração, Ciência e Proteção de Dados:** Termo de veracidade e ciência com confirmação prévia ao salvamento.

---

## 🛠️ Tecnologias Utilizadas

* **HTML5 / CSS3 Moderno** (Design responsivo e acessível)
* **JavaScript (Vanilla)** (Processamento client-side, manipulação de estado e geração de JSON)
* **[PDF.js](https://mozilla.github.io/pdf.js/)** (Leitura e extração local de dados de DANFEs em PDF)
* **[ViaCEP](https://viacep.com.br/)** (Consulta de endereços por CEP)
* **[Font Awesome](https://fontawesome.com/)** (Iconografia)

---

## 👨‍💻 Desenvolvedor

**João Vitor Toledo**  
*Engenheiro Agrônomo, Mestre em Produção Vegetal, Doutor em Meteorologia Agrícola*  
GitHub: [@jvitoragr](https://github.com/jvitoragr)

---

## 📄 Licença

Este projeto é disponibilizado para fins de suporte, facilitação e atendimento à agricultura familiar.
