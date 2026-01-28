# 🎯 Chamador de Senhas Premium

![License](https://img.shields.io/badge/license-MIT-green.svg)
![Version](https://img.shields.io/badge/version-2.2.0-blue.svg)
![Status](https://img.shields.io/badge/status-active-success.svg)
![Developer](https://img.shields.io/badge/developer-Alisson%20Coqueiro-orange.svg)

> **Sistema profissional de gerenciamento de filas e chamadas de pedidos, projetado para alta visibilidade em grandes telas e painéis.**

---

## 📋 Sobre o Projeto

O **Chamador de Senhas** é uma solução robusta e moderna para estabelecimentos que necessitam de um sistema visual eficiente para chamada de clientes. Com uma interface **Glassmorphism** de alta qualidade, ele foi otimizado para ser exibido em **Telões** e **TVs de grande porte**, garantindo legibilidade à distância.

Ideal para:
*   🍔 Lanchonetes e Fast-foods
*   🍽️ Restaurantes
*   🏢 Instituições (como SESC)
*   🏥 Clínicas e Hospitais

## ✨ Funcionalidades Principais

*   **🖥️ Interface Premium**: Design moderno com efeitos de vidro (Glassmorphism), animações suaves e tipografia otimizada.
*   **👁️ Alta Visibilidade (Telão)**: Fontes calibradas para leitura em longas distâncias (até 400px de altura).
*   **📱 Responsividade Total**: Adapta-se perfeitamente de celulares a telões de 80"+.
*   **⌨️ Controle Híbrido**: Operação via teclado numérico físico ou teclado virtual na tela.
*   **🔊 Alerta Sonoro**: Feedback auditivo suave ao chamar uma nova senha.
*   **📜 Histórico Visual**: Lista lateral com as últimas senhas chamadas para referência rápida.
*   **🚫 Validações Inteligentes**:
    *   Bloqueio de senhas fora do intervalo permitido (0-999).
    *   Prevenção de duplicidade imediata.
    *   Formatação visual automática.
*   **💾 Persistência Automática**: Salva o histórico e estado atual no navegador (localStorage).
*   **🌐 Modo Offline**: Funciona sem internet após o primeiro carregamento.

## 🚀 Tecnologias

Este projeto foi construído utilizando as melhores práticas do desenvolvimento web moderno:

*   **HTML5 Semântico**: Estrutura acessível e otimizada.
*   **CSS3 Moderno**: Variáveis nativas, Flexbox, Grid e animações de alta performance.
*   **TailwindCSS**: Framework utilitário para estilização rápida e consistente.
*   **JavaScript (ES6+)**: Lógica modular orientada a objetos (POO).
*   **Glide.js**: Biblioteca leve para carrosséis de imagens.
*   **Google Fonts**: Tipografia *Inter* para máxima legibilidade.

## 🛠️ Instalação e Uso

Você pode utilizar este projeto de duas formas:

### 1. Acesso Direto (Simples)

Basta baixar os arquivos e abrir o `index.html` em qualquer navegador moderno (Chrome, Edge, Firefox, Safari).

```bash
# Clone este repositório
git clone https://github.com/Alissonls/Chamador_senhas.git

# Acesse a pasta
cd Chamador_senhas

# Abra o arquivo
Clique duas vezes em index.html
```

### 2. Servidor Local (Recomendado)

Para uma experiência mais fluida e sem restrições de segurança do navegador:

```bash
# Usando Python
python -m http.server 8000

# Ou usando Node.js
npx serve .
```

Acesse `http://localhost:8000` no seu navegador.

## 📖 Manual de Operação

### Comandos de Teclado
| Tecla | Função |
|-------|--------|
| `0-9` | Digita os números do pedido |
| `ENTER` | **Chama a senha** |
| `BACKSPACE` | Corrige o último dígito |
| `ESC` | Limpa o campo de entrada |
| `ESPAÇO` | Abre/Fecha o painel de controle virtual |

### Painel Virtual
Para dispositivos touch ou operação via mouse, utilize o botão flutuante no canto inferior direito para abrir o teclado numérico virtual.

## ⚙️ Personalização

O sistema foi desenhado para ser facilmente customizável através do arquivo `css/style.css`.

### Ajuste de Cores (Theming)
```css
:root {
    --color-primary: #0066cc;  /* Cor principal */
    --color-accent: #dc2626;   /* Cor de destaque/chamada */
    --glass-bg: rgba(255, 255, 255, 0.08); /* Opacidade do vidro */
}
```

## 👥 Créditos e Autoria

Este projeto foi desenvolvido com foco em qualidade, performance e experiência do usuário.

**Desenvolvido por:**
### **Alisson Coqueiro**
*Software Developer*

---

<div align="center">
  <p>Feito com ❤️ por Alisson Coqueiro</p>
  <p>© 2025 Todos os direitos reservados.</p>
</div>
