# Atualização em breve

## OBJETIVO: Refatoração completa do projeto (Aplicando boas práticas de semântica e SEO) + implementação de automação, para o preenchimento de cada item da árvore.

Descrição: Temos 5 sessões aqui, uma com os links principais, as tags que serão utilizadas para cada sessão estarão documentadas.

- **Sessão 1:** div contendo nossa foto, nome e uma descrição breve da nossa área de atuação, com a classe "Profile" que vai envolver o conteúdo dentro da mesma.

- **Sessão 2:** Uma lista inline, contendo nossos links das redes sociais, a classe que deve envolver nossa div ou ul, é social.

- **Sessão 3:** Primeira área dos nossos links principais e de mais destaque. A classe a ser usada em nossa ul é link list, e a estrutura de cada caixa de link é:

<ul>
    <li>
        <a href="link" target="_blank">
            <span></span>
        </a>
    </li>
</ul>

- **Sessão 4:** A mesma coisa que a Sessão 3, só que contendo nosso links com menos relevância para o público e sendo envolvida pela classe second-link.

- **Sessão 5:** Nosso footer com a classe end-site.

- **Sessão bônus:** A sessão 3 e 4, serão automatizadas por javascript, através de um json, contendo os objetos: "title, link e description" com isso será mais fácil de fazer a manutenção de nosso site e adicionar links futuramente será algo que teremos mais eficiência.



