# PM-SP + Shape — painel de treino

Site estático, pronto para GitHub e Vercel.

## Funcionalidades
- Iniciar treino do dia ou escolher outro dia
- Cronômetro da sessão, pausa e retomada
- Séries com carga, repetições e marcação de conclusão
- Cronômetro de descanso configurável
- Anotações por sessão
- Plano semanal editável
- Upload e remoção de fotos dos equipamentos
- Histórico e exportação de backup JSON
- Salvamento automático no navegador (localStorage)

## Publicar
1. Extraia o ZIP.
2. Envie a pasta para um repositório GitHub.
3. Na Vercel, importe o repositório.
4. Framework Preset: Other; Build Command e Output Directory podem ficar vazios; Root Directory: `./`.
5. Clique em Deploy.

## Observações
- Não há backend/login: dados e fotos ficam no navegador/dispositivo usado.
- Para evitar perda de dados, use Exportar dados periodicamente.
- As fotos dos equipamentos são adicionadas pelo usuário na aba Equipamentos.
