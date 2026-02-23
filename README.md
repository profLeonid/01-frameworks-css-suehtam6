
<div align="center">
  <h1>Tailwind</h1>
  <br>
  <img width="551" height="281" alt="image" src="https://github.com/user-attachments/assets/5a3d5530-2ea8-4f42-a7ad-8ada78667eeb" />
</div>
<br>
### Como aplicar o tailwind no projeto
Para aplicar o tailwind no seu projeto por meio de cdn é extremamente simples, ao colocar o 
script abaixo encontrado no site oficial da tailwind (https://tailwindcss.com/docs/installation/play-cdn) na tag <head> do seu arquivo html você já está pronto para utilizar o framework no seu projeto:

`<script src="https://cdn.jsdelivr.net/npm/@tailwindcss/browser@4"></script>`

porém esse método é uma versão limitada do tailwind, para utiliza-lo de forma completa é necessário realizar a instalação usando Vite.

### Empresas que usam Tailwind.

O Tailwind Css é um Framework muito utilizado em diversas empresas de todos os portes.
Os principais exemplos são:

* NASA: Utiliza o framework em sites como o do Jet Propulsion Laboratory (JPL).
* Netflix: Implementou o Tailwind para o site Netflix Top 10, reduzindo drasticamente o tamanho do arquivo CSS.
* Shopify: Adotou a tecnologia em partes de sua infraestrutura e sites institucionais.
* GitHub: Utiliza o Tailwind em projetos específicos, como o site do GitHub Copilot.
* OpenAI: Ferramentas e interfaces como o ChatGPT e o showcase da OpenAI fazem uso do framework.

### Algumas Funcionalidades

#### Responsividade facilitada (Mobile-First)
No Tailwind você utiliza prefixos diretamente na classe. O padrão é para celulares.

`w-full:` Ocupa 100% da largura (padrão).

`md:w-1/2:` Ocupa 50% em tablets.

`lg:w-1/4:` Ocupa 25% em desktops.

#### Estados Condicionais (Hover, Focus, Active)

No tailwind é possível definir o tipo de ação executada a depender do seu estado.

1. `hover:bg-blue-700`  //muda a cor de fundo para azul ao passar o mouse

2. `focus:ring-2`  //adiciona um anel de destaque ao clicar em um campo de texto

3. `disabled:opacity-50`  // esmaece um botão desativado automaticamente

#### Dark Mode nativo

O tailwind possui suporte integrado para modo escuro, basta apenas utilizar o prefixo: <strong>`dark:`</strong>

ex. `class="bg-white text-black dark:bg-gray-900 dark:text-white"`

#### Mecanismo de cores e tipografia

O Tailwind vem com uma paleta de cores curada, ou seja, meticulosamente planeja, permitindo que as cores de seu site, landig page, etc. sejam harmoniosas.



* OpenAI: Ferramentas e interfaces como o ChatGPT e o showcase da OpenAI fazem uso do framework. 


### Vantagem de utilizar o Tailwind

Por que o Tailwind CSS é melhor que Pico, Bootstrap e Bulma?
*	Controle total do design
  Tailwind não impõe visual nem componentes prontos. Você cria qualquer layout sem brigar com o framework.

*	Escala melhor em projetos grandes
  Design tokens centralizados garantem consistência visual e facilitam o trabalho em equipe.

*	Customização nativa.
  Tudo é configurável no tailwind.config.js. Bootstrap, Bulma e Pico exigem sobrescritas de CSS.

*	Responsividade e estados superiores
  Breakpoints, hover, focus e dark mode são explícitos e fáceis de combinar.

* Integração perfeita com frameworks modernos
  Ideal para React, Vue, Svelte, Next.js, etc.

  Tailwind CSS é superior porque oferece controle, escalabilidade e performance, enquanto Pico, Bootstrap e Bulma priorizam rapidez inicial, mas limitam projetos complexos.
