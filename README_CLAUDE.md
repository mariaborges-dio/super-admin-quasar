# Quasar Super Admin — base atual

Base recuperada do deployment de produção da Vercel e correspondente ao Console Quasar V10.

Arquivos da aplicação:
- `index.html` — interface e lógica do protótipo
- `support.js` — runtime usado pelo protótipo
- `assets/` — logo e favicon locais
- `vercel.json` — configuração do deployment

Importante para próximas alterações:
- trabalhar sobre esta base, sem reconstruir o projeto;
- o fluxo de Cicatrizes já existe em Cliente > Módulos > Queimadas > drawer do módulo;
- não criar uma nova seção de Cicatrizes na sidebar;
- alteração aplicada (V10.1): removido `mensal`; `Mês de referência` substituído por "Data da cicatriz" manual e obrigatória (não aceita data futura); data/hora de importação registrada separadamente em cada item.
