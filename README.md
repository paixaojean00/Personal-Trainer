# Landing Page — Alessandro Rodrigues | Personal Trainer

Landing page comercial para Alessandro Rodrigues, especialista em transformação feminina, desenvolvida com Claude (Anthropic) e publicada na Vercel.

**Site publicado:** https://alessandro-rodrigues-personal-train.vercel.app

## Sobre este repositório

Este repositório contém o código-fonte exato do site atualmente publicado, salvo diretamente a partir do deployment ativo na Vercel — sem nenhuma alteração de conteúdo, texto, estilo ou estrutura.

## Estrutura

```
.
├── src/
│   └── index.html      # Página completa (HTML + CSS + JS + assets embutidos)
├── reference/           # Imagens de referência usadas no processo de design
└── README.md
```

## Sobre o arquivo `src/index.html`

O arquivo é um bundle autocontido gerado pelo Claude (recurso de Artifacts/Design): todo o HTML, CSS, lógica de interface (componente único) e assets (fontes, imagens) estão empacotados em um único arquivo `.html`, que se "desempacota" no navegador ao carregar. Isso é o mesmo formato usado no deployment atual — não é necessário nenhum passo de build para publicar.

## Como visualizar localmente

Basta abrir o arquivo `src/index.html` diretamente no navegador, ou servir a pasta com qualquer servidor estático:

```bash
npx serve src
```

## Como publicar (Vercel)

1. Crie um novo projeto na [Vercel](https://vercel.com) e conecte este repositório.
2. Defina o diretório raiz de output/servir como `src` (sem framework, sem comando de build).
3. Deploy.

Esse é exatamente o mesmo processo usado para o deployment atual.

## Status de conteúdo

Alguns blocos da página ainda usam placeholders (a preencher pelo cliente antes do lançamento final):

- Fotos reais (hero, antes/depois, resultados de alunas)
- Depoimentos reais de alunas
- Número de registro profissional (CREF)
- Número de WhatsApp

## Licença / Uso comercial

Este projeto é proprietário. Todos os direitos reservados ao autor/comercializador. Uso, cópia, distribuição ou revenda sem autorização não são permitidos.
