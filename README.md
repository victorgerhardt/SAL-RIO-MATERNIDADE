# Meu Primeiro Salario-Maternidade

Landing page estatica pronta para publicar no GitHub e na Vercel.

## Arquivos do projeto

- `index.html`: pagina principal da landing page.
- `hero-mockup-transparent.png`: mockup do produto com fundo transparente.
- `logo-horizontal-light.png` e `logo-horizontal-dark.png`: logos usados no topo e rodape.
- `og.png`: imagem de compartilhamento social.
- `favicon.svg`: icone da aba do navegador.
- `vercel.json`: configuracao minima para a Vercel.

## Subir para o GitHub

1. Crie um repositorio vazio no GitHub.
2. Abra o terminal nesta pasta.
3. Rode:

```bash
git init
git add .
git commit -m "Landing page Meu Primeiro Salario Maternidade"
git branch -M main
git remote add origin https://github.com/SEU-USUARIO/SEU-REPOSITORIO.git
git push -u origin main
```

## Publicar na Vercel

1. Entre em https://vercel.com/new.
2. Importe o repositorio do GitHub.
3. Em Framework Preset, escolha `Other` se a Vercel nao detectar automaticamente.
4. Deixe Build Command vazio.
5. Deixe Output Directory vazio ou como `.`.
6. Clique em Deploy.

## Observacao

Essa versao e estatica. Ela nao precisa de Node, instalacao de dependencias ou comando de build para funcionar na Vercel.
