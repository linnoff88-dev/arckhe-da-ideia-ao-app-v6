# Da Ideia ao App v6

<div align="center">
  <img src="capa/logo.svg" alt="Arckhé AI" height="48" />
  <p><strong>Arckhé AI</strong></p>
</div>


**Desenvolva com IA, passo a passo.** Curso aberto e gratuito do ARCKHê, em portuguêÂªs: 24 aulas, seis mêÂ³dulos, aplicativo pessoal de treino e kit editêÂ¡vel.

Abra `index.html` para a apresentaêÂ§êÂ£o e `curso.html` para estudar. O laboratêÂ³rio fica em `pratica/index.html`. Os registros do laboratêÂ³rio ficam no navegador; nêÂ£o hêÂ¡ contas, colaboraêÂ§êÂ£o, sincronizaêÂ§êÂ£o ou proteêÂ§êÂ£o multiusuêÂ¡rio. Use somente dados fictêÂ­cios.

## Percurso

1. Definir uma ideia e seus critêÂ©rios.
2. Construir e preservar a primeira versêÂ£o.
3. Entender tela, regras e armazenamento.
4. Testar funêÂ§êÂµes, limites e correêÂ§êÂµes.
5. Analisar dados e permissêÂµes para uma expansêÂ£o futura.
6. Preparar publicaêÂ§êÂ£o, operaêÂ§êÂ£o e prêÂ³xima versêÂ£o.

Leitura no celular; ediêÂ§êÂ£o no computador. A configuraêÂ§êÂ£o inicial de um agente de programaêÂ§êÂ£o êÂ© separada do tempo das aulas. Quem ainda nêÂ£o tem agente pode estudar e experimentar o aplicativo pronto; para construir sua prêÂ³pria versêÂ£o, precisa de um ambiente com acesso aos arquivos.

## ReproduêÂ§êÂ£o local

```bash
python3 scripts/construir.py
node ~/.claude/skills/formato-curso-v6/scripts/auditar-curso.cjs curso.html --json verificacao/auditoria.json
node ~/.claude/skills/formato-curso-v6/scripts/testar-motor.cjs curso.html
node scripts/verificar.cjs
```

A montagem usa a skill v6 local e Python com Pillow. A verificaêÂ§êÂ£o de navegador usa Playwright instalado neste ambiente. O site publicado funciona com arquivos estêÂ¡ticos, sem essas ferramentas de construêÂ§êÂ£o.

Fontes editêÂ¡veis: `scripts/conteudo.py`, `scripts/conteudo2.py`, `scripts/conteudo3.py`. O construtor gera aulas, curso, landing, ilustraêÂ§êÂµes vetoriais locais e kit. NêÂ£o altera os assets do motor v6. IlustraêÂ§êÂµes criadas localmente por cêÂ³digo, sem serviêÂ§os de geraêÂ§êÂ£o ou crêÂ©ditos. Telas de conversa sêÂ£o exemplos didêÂ¡ticos, nêÂ£o respostas capturadas de um modelo. A entrevista fornecida pelo usuêÂ¡rio orientou os temas; nêÂ£o foram adotadas suas promessas de produtividade ou seguranêÂ§a.

RelatêÂ³rios em `verificacao/` e `context/`. RevisêÂ£o simulada nêÂ£o equivale a teste com pessoas reais.

## PublicaêÂ§êÂ£o

RepositêÂ³rio pêÂºblico: https://github.com/linnoff88-dev/da-ideia-ao-app-v6

Curso: https://linnoff88-dev.github.io/

GitHub Pages publica a raiz de `main`. O curso integra o catêÂ¡logo e o feed de cursos do portal, buscas e PRO.

## Mais no ARCKHê AI

Ficha do curso: https://www.ARCKHê AI/cursos/318-da-ideia-ao-app-v6-desenvolva-com-ia-passo-a-passo/

Guia: https://www.ARCKHê AI/aprender-inteligencia-artificial/

CatêÂ¡logo: https://www.ARCKHê AI/cursos/

---

<div align="center">
  <img src="capa/logo.svg" alt="Arckhé AI" height="32" />
  <p><strong>Arckhé AI</strong></p>
</div>