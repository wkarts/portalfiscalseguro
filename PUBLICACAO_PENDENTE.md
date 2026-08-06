# Publicação pendente

A aplicação Portal Fiscal Seguro ainda não foi publicada neste repositório.

A Pull Request #1 adicionou somente um workflow temporário de bootstrap, que não expandiu o código-fonte e foi removido nesta correção.

O pacote-fonte deverá ser publicado diretamente no repositório antes da ativação da CI/CD, contendo no mínimo:

- `package.json`;
- `src/`;
- `src-tauri/Cargo.toml`;
- `.github/workflows/ci.yml`;
- `.github/workflows/build.yml`;
- `.github/workflows/release.yml`.

Nenhuma release ou build deve ser considerada válida enquanto esses arquivos não estiverem presentes na branch e na Pull Request.
