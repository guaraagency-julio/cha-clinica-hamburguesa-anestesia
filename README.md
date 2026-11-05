# Clínica Hamburguesa de Anestesiologia — website demonstrativo

Primeira versão de redesign institucional da C.H.A. (Novo Hamburgo, RS).

## Publicação

- Demo: https://cha-clinica-hamburguesa-anestesia.pages.dev/
- Repositório: https://github.com/guaraagency-julio/cha-clinica-hamburguesa-anestesia
- Branch de produção: `main`
- Deploy: Cloudflare Pages conectado ao GitHub, site estático sem etapa de build.

## Recursos

- Páginas: início, história, clínica, corpo clínico, anestesia, consulta, atuação, convênios, acervo, ação social, contato, privacidade.
- Navegação responsiva com menu mobile.
- Filtro de nomes e CRM dos profissionais.
- Logotipos dos convênios extraídos de URLs oficiais publicadas na versão anterior.
- Google Maps incorporado, WhatsApp e Instagram.
- Animações conforme rolagem; renderização WebGL com Three.js condicionada à preferência de movimento reduzido e ao tamanho da tela.

## Fonte e escopo

Conteúdo institucional revisado contra o endereço https://clinicaanestesiologia.com.br/ em 05/11/2026. Este trabalho é um **protótipo comercial não oficial**, que requer validação da clínica antes de adoção e publicação em domínio próprio.

### Pendências de validação

1. O site atual menciona 16 e 17 anestesiologistas em contextos diferentes, mas a página de corpo clínico acessível apresenta 15 nomes. Confirmar número e quadro atualizado.
2. Textos históricos usam referências temporais desatualizadas (fundação em 1988, menção a 31 anos). Reproduzidos sem alterações substanciais.
3. Confirmar CRMs, títulos profissionais, vínculos, convênios vigentes, informações sobre anestesia, orientações pré-operatórias e texto sobre declaração do IR.
4. O acervo de três artigos utiliza links externos para as publicações originais; a migração integral deles pode ser realizada após validação.
5. Confirmar autorização para imagens de equipe, marca/logotipos e fotografias institucionais. Imagens gerais são ilustrativas.
6. Conferir detalhes e política de privacidade antes de aceitar dados pessoais. A prévia não coleta dados.
7. A versão publicada no GitHub é standalone em `index.html`; o pacote de desenvolvimento completo separa HTML, CSS, dados e JavaScript.

## Desenvolvimento local

Abrir com um servidor local, por exemplo `python -m http.server 8000`, e acessar http://localhost:8000. O código usa módulos JS e recursos estáticos. Um arquivo standalone também está disponível no pacote de entrega.

## Créditos

Projeto de demonstração feito para a Guará Agency, usando informações institucionais originalmente publicadas pela C.H.A. Marca e conteúdo sujeitos aos titulares.