# Google Drive Clone

Marque esse projeto com uma estrela 🌟

## Preview

![](./resources/demo.gif)


## Checklist Features

- Web API
    - [ ] Deve listar arquivos baixados
    - [ ] Deve receber stream de arquivos e salvar em disco
    - [ ] Deve notificar sobre progresso de armazenamento de arquivos em disco
    - [ ] Deve permitir upload de arquivos em formato image, video ou audio
    - [ ] Deve atingir 100% de cobertura de código em testes

- Web App
    - [ ] Deve listar arquivos baixados
    - [ ] Deve permitir fazer upload de arquivos de qualquer tamanho
    - [ ] Deve ter função de upload via botão
    - [ ] Deve exibir progresso de upload
    - [ ] Deve ter função de upload via drag and drop


## certificates
```bash
$ brew install mkcert nss
$ mkcert -install
$ mkcert -key-file key.pem -cert-file cert.pem 0.0.0.0 localhost 127.0.0.1 ::1
```