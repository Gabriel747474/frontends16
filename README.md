Produto Fictício AeroMist é um dispositivo portátil inovador que combina purificação de ar, aromas inteligentes e tecnologia em um único acessório. O objetivo da página é apresentar o produto de forma moderna e envolvente, destacando suas funções, benefícios e incentivando o usuário a experimentar ou obter mais informações. O layout foi projetado priorizando a experiência visual e a navegação intuitiva, incluindo seções de destaques, funcionalidades e contato.

 Animações - CSS

A imagem do produto possui uma animação de flutuação (@keyframes float), criando a sensação de movimento leve e contínuo, reforçando a ideia de modernidade e sofisticação.

Botões utilizam transition para gerar um efeito de aumento ao passar o mouse, tornando a interação mais agradável e dinâmica.

 JavaScript / Biblioteca (ex: GSAP)

Este projeto usa apenas animações básicas em CSS, mas bibliotecas como GSAP podem ser aplicadas quando se deseja criar efeitos baseados em rolagem ou eventos do usuário, como a entrada de elementos com atraso, sequências de movimento ou transições mais complexas.
Assim, o CSS é ideal para efeitos simples e de alto desempenho, enquanto o GSAP se torna a escolha certa para interações mais avançadas.

 Pré-processador CSS

Foi adotado o SASS como pré-processador.
Vantagens:

Organização do código em arquivos menores (parciais), facilitando manutenção.

Uso de variáveis e mixins, reduzindo repetição de cores, tipografia e estilos recorrentes.

Consistência visual em todo o projeto e maior agilidade para ajustes de design.

Ferramentas como o SASS são fundamentais em projetos de médio e grande porte, pois tornam o CSS mais estruturado, reutilizável e escalável.

 Ferramenta de Build

O Gulp foi configurado para automatizar tarefas essenciais do projeto.
Funções implementadas:

Compilação de SASS para CSS.

Minificação de CSS e JS, garantindo melhor desempenho.

Atualização automática do navegador (Live Reload) durante o desenvolvimento.

Cópia otimizada de imagens e fontes para a pasta dist.

O uso do Gulp melhora o fluxo de trabalho, evita erros manuais e garante que o projeto esteja sempre pronto para produção de forma prática e eficiente.
