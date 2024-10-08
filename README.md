## Olá pessoas que não conheço!

Atualmente, estou finalizando o ensino médio com um certificado de **Técnico em Informática para Internet** em mãos. Tenho 18 anos e estou em busca de uma oportunidade de trabalho.

Se quiser entrar em contato, meu e-mail é: [leonardolfelix12@gmail.com](mailto:leonardolfelix12@gmail.com).

<a href="https://github.com/6aleatorio6" align="left">
    <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=6aleatorio6&hide=java,html,tex&title_color=ffffff&text_color=c9cacc&icon_color=2bbc8a&bg_color=1d1f21&langs_count=3" />
</a>

## Aqui estão 4 repositórios que representam o desenvolvimento das minhas habilidades.

### 1. Damas Paia (nome estranho, porém único) - Jogo de damas online mobile

O **Damas Paia** é o projeto mais recente que desenvolvi, levando 3 meses de esforços para ser finalizado. Ele é um jogo de damas online que inicialmente deveria ser multiplataforma, mas no final consegui desenvolver apenas o frontend mobile por falta de tempo. Para mais informações, consulte os repositórios.

| Plataforma                                                   | Tecnologia   | 
| ------------------------------------------------------------ | ------------ | 
| [Backend](https://github.com/6aleatorio6/Damas-Paia_backend) | NestJS       |
| [Mobile](https://github.com/6aleatorio6/Damas-Paia_mobile)   | React Native |


<p>
  <img src="https://gist.githubusercontent.com/6aleatorio6/ed8cc379ee1ad319cca1dd8604f006de/raw/7258f0b052824b803a8265bd2f57ffefeedbba81/pareamentoEjogo.gif" alt="Pareamento e uma partida de damas" width="624" />
</p>

Atualmente, o backend está hospedado no Heroku. Você pode instalar o APK encontrado no repositório mobile para experimentar (lembrando que, para iniciar uma partida, outra pessoa também precisa estar na fila, o que provavelmente não acontecerá. Peça a um amigo para testar junto).


### 2. BioDex - Projeto comunitário para o Parque Juqueriquerê, Caraguatatuba-SP

Esse projeto foi desenvolvido em parceria com toda a turma no último semestre e até gerou uma matéria no site da prefeitura: [Notícia](https://www.caraguatatuba.sp.gov.br/pmc/2024/06/prefeitura-de-caraguatatuba-recebe-alunos-do-ifsp-para-apresentacao-de-aplicativo-para-o-parque-juqueriquere/).

Embora o projeto não possua documentação oficial, aqui está um resumo das funcionalidades do **BioDex**:

- **Totem Interativo**: Permite que os visitantes preencham um formulário de entrada digital no parque.
- **Painel Administrativo**: Exibe os dados coletados pelo totem, com opções de exportação para Excel e PDF.
- **Aplicativo Mobile Gamificado**: Os visitantes podem localizar QR Codes espalhados pelo parque, cada um representando uma espécie da fauna local. Ao escanear um QR Code, o app exibe um modal com informações detalhadas sobre o item, e a interação é registrada no ranking mensal do aplicativo. Além disso, se o visitante escanear o QR Code do totem pela câmera do app e já tiver completado as informações de cadastro, a visita é automaticamente registrada.

| Plataforma                                                                                               | Tecnologia   | 
| -------------------------------------------------------------------------------------------------------- | ------------ | 
| [Backend](https://github.com/6aleatorio6/pj3-backend)                                                     | Express      |
| [Aplicativo Mobile](https://github.com/Programadorwolrd/pj3-Aplicativo-Municipal)                          | React Native |
| [Totem e Painel Administrativo](https://github.com/lorislolo/pi-3sem)                                     | React        |

O BioDex é um sistema integrado e desenvolvido para aprimorar a experiência dos visitantes no parque, combinando diversas tecnologias para oferecer uma solução interativa e completa.

### 3. TECHPASS - Sistema de gerenciamento de uma empresa de ônibus

> **AVISO:** Este foi o meu primeiro projeto, e o código está desorganizado, com documentação bastante limitada. No entanto, garanto que minha habilidade evoluiu, como pode ser visto em Damas Paia.

TechPass foi o trabalho que desenvolvi com o [Flávio](https://github.com/flavioifsp) na disciplina de Projeto Integrado durante o 2° semestre do curso. O sistema é composto por três partes:

- Um site público que apresenta informações sobre a empresa e permite que os clientes criem contas e recarreguem seus cartões.
- Um painel administrativo com contas de diferentes permissões, onde o administrador pode definir as rotas dos ônibus a serem exibidas no site público, além de criar cartões com tarifas variadas para serem utilizados na catraca, descontando da conta do usuário.
- A catraca do ônibus, que recebe um parâmetro para identificar o ônibus e possui um input oculto, testado com um leitor RFID durante a apresentação do projeto. Ela recebe o ID dos cartões dos clientes, desconta a tarifa definida para aquele cartão e, caso não haja saldo suficiente, a operação é recusada.


Estou esquecendo muitos detalhes pois faz muito tempo, mas olhando para trás é meio surreal a dimensão desse projeto para o meu nivel na época. Para se ter noção, olha o diagrama do banco:

<img src="https://github.com/flavioifsp/Pj2-G10-TechPass/blob/main/docs/db/banco%20img%202.png?raw=true" alt="Entrar" width="600" />
 
> E por incrivel que pareça, todas as tabelas são usadas

| Plataforma                                                   | Tecnologia   | 
| ------------------------------------------------------------ | ------------ | 
| [Mobile \| Backend \| Catraca](github.com/flavioifsp/Pj2-G10-TechPass)   | Express, Ejs, bootstrap, mySql, Prisma |

### 4. Lista de Exercícios

Este não é exatamente um projeto, mas sim uma lista de exercícios que desenvolvi no 1° semestre, quando estava aprendendo lógica de programação.

- **Fonte:** [Wiki Python](https://wiki.python.org.br/ListaDeExercicios)  
- **Lista de Exercícios:** [Replit](https://replit.com/@LEONARDOLOPES29/atividade-avaliativa-1#lista2/a45.js)


