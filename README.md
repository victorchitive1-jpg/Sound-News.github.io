# 🎵 Sound News - Web Player & PWA Streaming

O **Sound News** é um aplicativo web progressivo (PWA) de streaming de áudio, ranking e reprodução de rádio ao vivo. O projeto conta com uma interface moderna em *Dark Mode*, leitor interativo de músicas e um painel administrativo para geração simplificada de metadados em JSON.

---

## 🚀 Funcionalidades Principais

* 📻 **Rádio Ao Vivo:** Transmissão interativa em tempo real integrada.
* 🎧 **Player de Música Integrado:** 
  * Controles completos: *Play/Pause*, *Anterior/Próxima*, *Modo Aleatório (Shuffle)* e *Repetir (Repeat)*.
  * Baixar arquivos MP3 diretamente pelo player ou pelos cards.
* 🔍 **Pesquisa Dinâmica:** Busca em tempo real por artista, título ou gênero musical.
* 📱 **Suporte PWA (Progressive Web App):**
  * Banner automático para instalação em dispositivos móveis e desktop.
  * Notificação de atualização de versão via Service Worker.
* ⚙️ **Painel de Gestão (Admin):**
  * Interface dedicada para cadastrar novas faixas (`id`, `título`, `artista`, `gênero`, `downloads`, `likes`).
  * Autopreenchimento inteligente de nomes de ficheiros.
  * Gerador e copiador automático do código formatado para o arquivo `musicas.json`.

---

## 📁 Estrutura do Projeto

```text
.
├── index.html          # Aplicação principal (Player e Lista de Músicas)
├── admin.html          # Painel de Gestão para gerar entradas JSON
├── musicas.json        # Base de dados estática das músicas
├── manifest.json       # Configuração da PWA (ícones, nome, tema)
├── sw.js               # Service Worker para suporte PWA/Offline
├── capa.jpg            # Imagem de capa padrão/fallback
└── README.md           # Documentação do projeto
