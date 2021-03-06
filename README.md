# hs3.pl
###### CODENAME marvelous-snuffle

[![Netlify Status](https://api.netlify.com/api/v1/badges/d61529cf-7e8a-4de7-927c-5358cf4d7fa5/deploy-status)](https://app.netlify.com/sites/naughty-volhard-02c8b8/deploys)

## Prerequisites
- [nix](https://nixos.org/nix/manual/#chap-installation)
- direnv (`nix-env -i direnv`)

### Non-nix
If you dislike Nix for whatever reason

#### Ubuntu 
```
apt install ruby-dev libffi-dev
```

#### Fedora
```
dnf install redhat-rpm-config ruby-devel rubygem-bundler
```

## Setup
```
direnv allow .
```

## Development
```
make help
```

## Structure

Więc chcesz szybko dodać jakąś stronę?
Tutaj szybki pogląd na to jak wygląda sytuacja:

* _site/ - tutaj budują się rzeczy, wpisz `make` i powinien się pojawić.
* _layouts/ - główne templatki z których można korzystać jako bazy do podstron.
* _includes/ - reużywalne komponenty, nic ciekawego.
* _sass/ - style które kompilują się do assets.
* assets/ - obrazki, css'y js'y etc.
* _data/ - jakieś dane które powinny być dostępne w każdym miejscu strony, np. odnośniki do social mediów.
* _config.yml - globalne zmienne i konfiguracja budowania/
* pliki .md - treści stron!


### Layout
Draft located at `design`.

Link to prototype: https://xd.adobe.com/view/8ead2469-21eb-4d30-8fbf-0dca204b70ae/?fullscreen

