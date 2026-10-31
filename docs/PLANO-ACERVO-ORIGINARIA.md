# Acervo Originária — planejamento editorial e técnico

## Cobertura
O Censo 2022 do IBGE identificou 391 etnias, povos ou grupos indígenas autodeclarados e 295 línguas indígenas. O Quadro Geral dos Povos do ISA utiliza critérios editoriais diferentes. Não tratar essas contagens como listas equivalentes, nem dizer que todo grupo censitário possui um perfil completo.

Fontes de referência:
- IBGE: https://www.ibge.gov.br/brasil-indigena/
- IBGE — Censo 2022: https://www.ibge.gov.br/estatisticas/sociais/trabalho/22827-censo-demografico-2022.html
- Instituto Socioambiental: https://pib.socioambiental.org/pt/Quadro_Geral_dos_Povos

## Modelo de registro
```json
{
  "id": "identificador-estavel",
  "nome": "Nome informado pela fonte",
  "nomesAlternativos": [],
  "povosRelacionados": [],
  "ufs": [],
  "linguas": [],
  "resumo": "",
  "fontes": [{"titulo":"", "url":"", "ano":null}],
  "status": "catalogado",
  "revisaoIndigena": false,
  "atualizadoEm": null
}
```

O status **catalogado** não significa perfil editorial completo. Para registros sem descrição verificada, exibir somente nome e referência, jamais inventar cultura, território ou língua. Não reproduzir automaticamente textos ou fotografias de terceiros. Verificar termos de reutilização.

## Regras de busca
Pesquisar nomes, variantes de grafia, termos, línguas e estados; normalizar maiúsculas/minúsculas e diacríticos; distinguir povo de subgrupo e exibir a fonte de cada dado. Indexar o catálogo carregado separadamente do design da homepage. Indicar a cobertura e a data da base; não usar a expressão "todos os povos" sem delimitar a fonte.

## Etapas
1. Importar e conferir a lista nominal oficial do IBGE com os 391 registros segundo o critério censitário.
2. Conciliar variantes e informações editoriais com o ISA, sem apagar entradas nem fundir automaticamente povos.
3. Migrar os dez registros existentes para o esquema e auditar suas descrições e links.
4. Ativar filtros por UF e língua apenas quando os campos estiverem verificados.
5. Criar fluxo de contribuição e revisão com participação indígena e controle de versões.
