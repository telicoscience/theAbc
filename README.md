# Projeto App de Níveis Interativos

Este repositório contém um jogo educativo desenvolvido com HTML, CSS e recursos multimídia, organizado em níveis progressivos de dificuldade. O objetivo é oferecer uma experiência de aprendizado interativa, apresentando imagens e áudios que auxiliam na fixação de vocabulário ou conceitos, dependendo do uso desejado.

## 📂 Estrutura de Diretórios

```bash
App/                     # Pasta raiz do projeto
├─ imagens/              # Imagens utilizadas em todas as fases
├─ audio/                # Arquivos de áudio (ex: pronúncia, efeitos sonoros)
├─ fases/                # Versão genérica das fases para referência
│  ├─ *.html             # Layout básico de cada fase
│  └─ fases.css          # Estilo comum às fases
├─ nivel1/               # Implementação do Nível 1
│  ├─ *.html             # Páginas de cada fase do nível 1
│  └─ design.css         # Estilo específico do nível 1
├─ nivel2/               # Implementação do Nível 2
│  ├─ fases/             # Fases do nível 2
│  └─ inicio/            # Tela inicial e final do nível 2
├─ nivel3/               # Implementação do Nível 3
│  ├─ fases/             # Fases do nível 3
│  └─ inicioefim3/       # Tela inicial e final do nível 3
├─ nivel4/               # Implementação do Nível 4
│  ├─ fases/             # Fases do nível 4
│  └─ inicioefim4/       # Tela inicial e final do nível 4
└─ "play and end"/      # Fluxo principal de execução (play & end)
   ├─ play.html          # Tela principal de jogo
   ├─ end.html           # Tela de vitória/conclusão
   └─ gameover.html      # Tela de fim de jogo (derrota)
```

## 🚀 Como Executar

1. **Clone o repositório**

   ```bash
   git clone https://github.com/SEU-USERNAME/App.git
   cd App
   ```

2. **Executar localmente**

   * **Opção 1:** Abra diretamente no navegador

     * Navegue até `play and end/play.html` para iniciar o jogo.

   * **Opção 2:** Servidor HTTP simples (recomendado)

     ```bash
     python3 -m http.server 8000
     ```

     Em seguida, abra no navegador: `http://localhost:8000/play%20and%20end/play.html`

## 🛠️ Tecnologias

* **HTML5**: Estrutura de páginas
* **CSS3**: Estilização responsiva e interativa
* **JavaScript** (opcional): Adicionar lógica de jogo (caso incluído)
* **Mídia**: Áudios em `.m4a` e imagens em `.png`

## 🎨 Personalização

* Para criar novas fases:

  1. Duplique uma pasta de `nivelX/fases`
  2. Substitua imagens e alterações em HTML/CSS
  3. Atualize ligações entre fases no fluxo principal (`play.html`)

* Para adicionar novos áudios, copie arquivos para `audio/` e referencie nos HTMLs.

## 🤝 Contribuição

1. Fork este projeto
2. Crie uma branch: `git checkout -b feature/nova-fase`
3. Faça suas alterações e commit: `git commit -m "Adiciona nova fase Y"`
4. Push para a branch: `git push origin feature/nova-fase`
5. Abra um Pull Request

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---

> Desenvolvido por Telico Oliveira – Experiência interativa de aprendizado em múltiplos níveis. Boa diversão!
