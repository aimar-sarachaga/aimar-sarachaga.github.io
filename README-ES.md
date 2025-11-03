# Cómo usar Chirpy Starter (en español)

Este directorio contiene el starter oficial de Chirpy, clonado siguiendo la documentación:
https://chirpy.cotes.page/posts/getting-started/#option-1-using-the-starter-recommended

## Pasos para empezar

1. Instala Ruby y Bundler si no los tienes:

```zsh
sudo apt install ruby-full build-essential zlib1g-dev
sudo gem install bundler
```

2. Instala las dependencias del proyecto:

```zsh
cd chirpy-starter
bundle install
```

3. Sirve el sitio localmente:

```zsh
bundle exec jekyll serve --livereload
# Abre http://127.0.0.1:4000 en tu navegador
```

## Despliegue

- Puedes desplegar en GitHub Pages siguiendo la documentación oficial de Chirpy.
- El repositorio ya incluye workflows de GitHub Actions para despliegue automático.

## Personalización

- Edita `_config.yml` para cambiar título, descripción, url, etc.
- Agrega posts en la carpeta `_posts/`.
- Consulta la documentación oficial para más opciones: https://chirpy.cotes.page/

---

¿Quieres que adapte la configuración inicial, cree un post de ejemplo personalizado o te ayude a configurar el despliegue en GitHub Pages? Dímelo y lo hago.