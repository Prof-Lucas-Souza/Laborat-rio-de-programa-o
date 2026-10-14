# Laboratório de Programação

Site estático responsivo para apresentar sete projetos do laboratório.

## Publicar no GitHub Pages
1. Crie um repositório público no GitHub (ex.: `laboratorio-programacao`).
2. Envie **o conteúdo desta pasta** para a raiz do repositório (`index.html`, `projetos.json`, `assets/`).
3. Em **Settings → Pages → Build and deployment**, selecione **Deploy from a branch**, `main` e `/ (root)`.
4. Salve e aguarde o link aparecer. O endereço normalmente será `https://SEU-USUARIO.github.io/laboratorio-programacao/`.

## Testar localmente
Abra um terminal nesta pasta e execute:
```bash
python -m http.server 8000
```
Acesse `http://localhost:8000`. Abrir `index.html` diretamente pelo sistema de arquivos pode bloquear a leitura de `projetos.json`.

## Personalizar
- `projetos.json`: nomes, categorias, descrições e objetivos dos projetos.
- `index.html`: texto institucional e contato (substituir `contato@exemplo.com`).
- `assets/style.css`: cores e estilo.
- `assets/app.js`: filtros e detalhes interativos.

Os ícones atuais são ilustrativos; imagens reais e páginas completas dos projetos podem ser adicionadas depois.
