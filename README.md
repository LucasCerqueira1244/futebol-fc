# Pelada FC

Sorteador de times para futebol amador, feito em React + Vite. Funciona sem servidor ou banco de dados: os jogadores são salvos no localStorage do navegador.

## Rodar localmente

```bash
npm install
npm run dev
```

## Publicar grátis na Vercel

1. Crie um repositório no GitHub e envie estes arquivos.
2. Acesse https://vercel.com/new e importe o repositório.
3. Selecione **Vite** como framework (normalmente detectado automaticamente).
4. Build command: `npm run build`; Output directory: `dist`.
5. Clique em **Deploy**. A Vercel fornece um endereço `*.vercel.app`.

## Observações

- O armazenamento é local a cada navegador/dispositivo, não sincronizado entre pessoas.
- A distribuição tenta equilibrar a soma dos níveis, mas é heurística e pode variar entre sorteios.
- O plano gratuito Hobby da Vercel está sujeito às condições e limites vigentes.
