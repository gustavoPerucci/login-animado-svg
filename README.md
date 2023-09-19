# Avatar SVG animado v2

Criado um formulário de login com um avatar SVG que responde à entrada no campo de email. Usei a biblioteca GSAP TweenMax + plugin MorphSVG do GSAP para a animação.

Aqui está o que alterei/corrigi/adicionei na v2:

-Adicionada funcionalidade de senha "mostrar/ocultar". Esta é uma boa melhoria na experiência do usuário, já que muitos usuários, especialmente em dispositivos móveis, preferem ver suas senhas enquanto as digitam devido à taxa com que digitamos incorretamente em nossos dispositivos móveis. A senha é exibida por padrão no celular e oculta por padrão no desktop.

-Adicionado um piscar de olhos aleatório

-Adicionada animação secundária dos ombros quando o avatar levanta os braços.

-Corrigido um bug onde os braços apareciam na frente do rosto por uma fração de segundo quando a página carregava pela primeira vez

-Corrigido um bug onde inserir um endereço de e-mail muito longo atrapalharia a aparência do avatar

-Corrigido um bug onde colar texto na entrada do e-mail não atualizava a aparência do avatar

-Corrigido um bug que fazia o avatar olhar no lugar errado ao passar do campo de senha de volta para o campo de e-mail

-Corrigido um bug no Safari onde um dos braços girava incorretamente

-Corrigido um bug onde o queixo do avatar às vezes virava de cabeça para baixo

-Corrigido um bug onde mudar de abas ou janelas do navegador e depois voltar estragaria a animação do avatar

-Corrigido um bug no Safari onde a borda ao redor do avatar ficava distorcida quando os braços eram animados

-Corrigido um bug onde clicar no rótulo de uma entrada enquanto essa entrada já estava em foco acionava as animações de desfoque

-Implementada uma correção para Chrome/Firefox que não permitia que a posição do cursor de texto fosse calculada dentro de um tipo de entrada "e-mail", apenas um tipo de entrada "texto". Portanto, agora o usuário receberá o teclado de "e-mail" adequado exibido em um dispositivo móvel quando clicar nesse campo.

-Corrigido um bug onde clicar e segurar a caixa de seleção mostrar/ocultar fazia com que os ponteiros caíssem