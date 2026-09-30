# MDL — Momento de Devoção e Luz

Site estático editorial em português para apresentar os episódios do MDL e oferecer reflexões devocionais. A estrutura é indexável desde o HTML, funciona sem JavaScript e usa as artes oficiais compartilhadas no projeto.

## Executar e validar

- `pnpm dev:static` — inicia a prévia local na porta configurada (`3000` por padrão).
- `pnpm build:static` — gera o site em `dist/public/`, pronto para hospedagem estática.
- `pnpm check` — verifica os tipos TypeScript do starter mantido no repositório.
- `pnpm test` — executa os testes já existentes.

## Conteúdo

A página inicial contém um destaque para o episódio 16 e quatro cartões dos episódios 12–15, cada qual ligado ao seu vídeo exato no canal oficial. Os devocionais são reflexões originais com referências bíblicas curtas. As artes da pasta `client/public/assets/mdl/brand/` vieram dos arquivos compartilhados e foram preservadas; `client/public/favicon.png` é um ícone quadrado simplificado, inspirado na árvore e no livro do emblema, e usado como favicon e marca do projeto.

As rotas atualmente publicadas estão declaradas em `client/public/manus-routes.json`, servido em `/manus-routes.json`.

## WhatsApp — estado atual

A área de inscrição é apenas uma prévia visual: o número, o consentimento e o botão estão desativados. Nesta versão o site **não solicita, salva nem envia** números ou mensagens. Para ativar a lista é necessário primeiro decidir entre administração manual no WhatsApp Business e integração com a WhatsApp Business Platform/Cloud API. A automação pode exigir coleta rastreável de opt-in, armazenamento protegido, modelos aprovados para mensagens fora da janela de atendimento e tratamento dos pedidos de cancelamento.
