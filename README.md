# Da Ideia ao App v6

<div align="center">
  <img src="capa/logo.svg" alt="Arckhé AI" height="48" />
  <p><strong>Arckhé AI</strong></p>
</div>


**Desenvolva com IA, passo a passo.** Curso aberto e gratuito do ARCKHÉ, em portuguÃªs: 24 aulas, seis mÃ³dulos, aplicativo pessoal de treino e kit editÃ¡vel.

Abra `index.html` para a apresentaÃ§Ã£o e `curso.html` para estudar. O laboratÃ³rio fica em `pratica/index.html`. Os registros do laboratÃ³rio ficam no navegador; nÃ£o hÃ¡ contas, colaboraÃ§Ã£o, sincronizaÃ§Ã£o ou proteÃ§Ã£o multiusuÃ¡rio. Use somente dados fictÃ­cios.

## Percurso

1. Definir uma ideia e seus critÃ©rios.
2. Construir e preservar a primeira versÃ£o.
3. Entender tela, regras e armazenamento.
4. Testar funÃ§Ãµes, limites e correÃ§Ãµes.
5. Analisar dados e permissÃµes para uma expansÃ£o futura.
6. Preparar publicaÃ§Ã£o, operaÃ§Ã£o e prÃ³xima versÃ£o.

Leitura no celular; ediÃ§Ã£o no computador. A configuraÃ§Ã£o inicial de um agente de programaÃ§Ã£o Ã© separada do tempo das aulas. Quem ainda nÃ£o tem agente pode estudar e experimentar o aplicativo pronto; para construir sua prÃ³pria versÃ£o, precisa de um ambiente com acesso aos arquivos.

## ReproduÃ§Ã£o local

```bash
python3 scripts/construir.py
node ~/.claude/skills/formato-curso-v6/scripts/auditar-curso.cjs curso.html --json verificacao/auditoria.json
node ~/.claude/skills/formato-curso-v6/scripts/testar-motor.cjs curso.html
node scripts/verificar.cjs
```

A montagem usa a skill v6 local e Python com Pillow. A verificaÃ§Ã£o de navegador usa Playwright instalado neste ambiente. O site publicado funciona com arquivos estÃ¡ticos, sem essas ferramentas de construÃ§Ã£o.

Fontes editÃ¡veis: `scripts/conteudo.py`, `scripts/conteudo2.py`, `scripts/conteudo3.py`. O construtor gera aulas, curso, landing, ilustraÃ§Ãµes vetoriais locais e kit. NÃ£o altera os assets do motor v6. IlustraÃ§Ãµes criadas localmente por cÃ³digo, sem serviÃ§os de geraÃ§Ã£o ou crÃ©ditos. Telas de conversa sÃ£o exemplos didÃ¡ticos, nÃ£o respostas capturadas de um modelo. A entrevista fornecida pelo usuÃ¡rio orientou os temas; nÃ£o foram adotadas suas promessas de produtividade ou seguranÃ§a.

RelatÃ³rios em `verificacao/` e `context/`. RevisÃ£o simulada nÃ£o equivale a teste com pessoas reais.

## PublicaÃ§Ã£o

RepositÃ³rio pÃºblico: https://github.com/linnoff88-dev/da-ideia-ao-app-v6

Curso: https://linnoff88-dev.github.io/

GitHub Pages publica a raiz de `main`. O curso integra o catÃ¡logo e o feed de cursos do portal, buscas e PRO.

## Mais no ARCKHÉ AI

Ficha do curso: https://www.ARCKHÉ AI/cursos/318-da-ideia-ao-app-v6-desenvolva-com-ia-passo-a-passo/

Guia: https://www.ARCKHÉ AI/aprender-inteligencia-artificial/

CatÃ¡logo: https://www.ARCKHÉ AI/cursos/

---

<div align="center">
  <img src="capa/logo.svg" alt="Arckhé AI" height="32" />
  <p><strong>Arckhé AI</strong></p>
</div>