# 📦 Carioca Infocell - Gestão de Inventário

Sistema de gerenciamento de estoque e inventário mobile-first desenvolvido originalmente para a loja **Carioca Infocell**. O aplicativo funciona como um PWA (Progressive Web App), permitindo a instalação nativa no celular e o uso de recursos como câmera para leitura de códigos de barras.

---

## ✨ Funcionalidades

- **Controle de Catálogo:** Cadastro, edição, visualização e exclusão de produtos em tempo real.
- **Gerenciador de Categorias:** Organização dinâmica de produtos por tipo.
- **Scanner de Código de Barras:** 
  - Suporte a leitores de código de barras físicos (pistolas USB/Bluetooth).
  - Integração com a câmera do celular para bips em trânsito (via QuaggaJS).
- **Autenticação:** Tela de login integrada para acesso restrito.
- **Mobile-First & PWA:** Layout totalmente responsivo com suporte a instalação na tela inicial.

---

## 🛠️ Tecnologias Utilizadas

Este projeto foi construído utilizando **JavaScript Vanilla** (código puro) para garantir máxima leveza e performance:

- **Front-end:** HTML5, CSS3 e JavaScript Vanilla.
- **Backend-as-a-Service (BaaS):** [Supabase](https://supabase.com/) (Autenticação e Banco de Dados PostgreSQL).
- **Bibliotecas Externas:** [QuaggaJS](https://serratus.github.io/quaggaJS/) (leitura de código de barras via câmera).

---

## 🔒 Configuração e Segurança (Importante)

Por motivos de segurança e privacidade dos dados operacionais da loja real, **as chaves de acesso ao banco de dados foram omitidas neste repositório público**.

Se você deseja testar este projeto localmente:
1. Crie um projeto gratuito no [Supabase](https://supabase.com/).
2. Crie as tabelas `categorias` e `produtos` no seu banco de dados.
3. Ative o RLS (Row Level Security) em ambas as tabelas.
4. Substitua os valores das constantes `SUPABASE_URL` e `SUPABASE_KEY` no arquivo `index.html` pelas chaves do seu projeto.

---

## 🚀 Como Executar Localmente

1. Clone o repositório:
   ```bash
   git clone [https://github.com/SEU-USUARIO/carioca-infocell-portfolio.git](https://github.com/SEU-USUARIO/carioca-infocell-portfolio.git)