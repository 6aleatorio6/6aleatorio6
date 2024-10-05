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


### 2. Biodex - Projeto comunitário para o parque Juqueriquere de Caraguatatuba-SP

Este foi um projeto desenvolvido por toda a turma no último semestre. Saiu uma notícia até no site da prefeitura: [Notícia](https://www.caraguatatuba.sp.gov.br/pmc/2024/06/prefeitura-de-caraguatatuba-recebe-alunos-do-ifsp-para-apresentacao-de-aplicativo-para-o-parque-juqueriquere/).

Infelizmente, o projeto não possui documentação oficial, então apresento um breve resumo:

**BioDex** é um sistema complexo dividido em várias partes:

- Um totem que permite aos visitantes preencherem o formulário de entrada.
- Um painel administrativo que apresenta os dados coletados pelo totem, com funcionalidades de exportação para Excel e PDF.
- Um aplicativo gamificado que permite aos usuários localizar os QR Codes espalhados pelo parque, representando a fauna local. Ao escanear um desses QR Codes, o app exibe um modal com informações sobre o item, e essa interação é contabilizada no ranking do aplicativo, que é reiniciado mensalmente. Se o usuário escanear o QR Code do token pela câmera do app e já tiver completado as informações da conta, a visita é registrada no totem.

| Plataforma                                                   | Tecnologia   | 
| ------------------------------------------------------------ | ------------ | 
| [Backend](https://github.com/6aleatorio6/pj3-backend)        | Express      |
| [Mobile](https://github.com/Programadorwolrd/pj3-Aplicativo-Municipal)   | React Native |
| [Totem \| Admin](https://github.com/lorislolo/pi-3sem)   | React |

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


