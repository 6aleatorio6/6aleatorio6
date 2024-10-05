## Olá pessoas que não conheço!

Atualmente estou finalizando o ensino médio com um certificado de TÉCNICO EM INFORMÁTICA PARA INTERNET a tira colo, Tenho 18 anos anos e estou procurando um emprego na área. Minha stack gira em torno do javascript mais basico até os framworks como NestJs e React Native, além do certificado do if, comprovo minhas habilidades com projetos feitos tanto no curso quanto fora. 

Se quiser me contatar use o email: leonardolfelix12@gmail.com

<a href="https://github.com/6aleatorio6" align="left">
    <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=6aleatorio6&hide=java,html,tex&title_color=ffffff&text_color=c9cacc&icon_color=2bbc8a&bg_color=1d1f21&langs_count=3" />
</a>

## Aqui estão 4 repositorios que representam o desenvolvimento das minhas habilidades em ordem descrecente.

### 1. Damas Paia (nome estranho, porém unico) - Jogo de damas online mobile

O Damas Paia é o projeto mais recente que fiz, levando 3 meses de esforços para finalizar. Ele é um jogo de damas online que deveria ser multiplataforma, mas no final só consegui fazer o frontend mobile por falta de tempo. Para mais informações consulte os repositorios.

<p>
  <img src="https://gist.githubusercontent.com/6aleatorio6/ed8cc379ee1ad319cca1dd8604f006de/raw/7258f0b052824b803a8265bd2f57ffefeedbba81/pareamentoEjogo.gif" alt="Pareamento e uma partida de damas" width="624" />
</p>

Atualmente o backend está hospedado no heroku, você pode baixar o apk encontrado no repo mobile para testar. (lembrando que para iniciar uma partida outra pessoa tambem precisa estar na fila, e provavelmente não tem. Peça a um amigo para junto)

| Plataforma                                                   | Tecnologia   | 
| ------------------------------------------------------------ | ------------ | 
| [Backend](https://github.com/6aleatorio6/Damas-Paia_backend) | NestJS       |
| [Mobile](https://github.com/6aleatorio6/Damas-Paia_mobile)   | React Native |

### 2. Biodex - projeto comunitário para o parque Juqueriquere de Caraguatatuba-SP

Este foi um projeto envolvendo toda a turma em seu ultimo semestre. Saiu noticia até no site da prefeitura:  [noticia](https://www.caraguatatuba.sp.gov.br/pmc/2024/06/prefeitura-de-caraguatatuba-recebe-alunos-do-ifsp-para-apresentacao-de-aplicativo-para-o-parque-juqueriquere/).

Infelizmente não foi documentado, então vou dar um breve resumo:

BioDex é um sistema complexo divido em varias partes:
 - Um totem para visitantes preencher o formulario de entrada, tendo um Qrcode alimentado por webSocket para caso o visitante tenha o App do Biodex, podendo preencher o formulario apenas apontando o cell.
 - Um admin que mostra os dados obtidos pelo totem de visitante, com exportação para excel e pdf.
 - Um Aplicativo gameficado, onde a pessoa pode encontrar os qrCode espalhados pelo parque representando a fauna, quando  o app lê algum desses qrCode é aberto um modal com as informações dessa coisa e é 
    contabilizado no ranking do app, que é resetado todo mẽs. Se a pessoa ler o qrcode do token pela camera do app e já tiver completado as informações da conta, ele se comunica com o totem e é contabilizada a visita.

obs: o TOTEM e o Admin usam o mesmo site, dependendo do tipo da conta abre uma das 2 interface.

| Plataforma                                                   | Tecnologia   | 
| ------------------------------------------------------------ | ------------ | 
| [Backend](https://github.com/6aleatorio6/pj3-backend)        | Express      |
| [Mobile](https://github.com/Programadorwolrd/pj3-Aplicativo-Municipal)   | React Native |
| [Totem \| Admin](https://github.com/lorislolo/pi-3sem)   | React |

### 3. TECHPASS - Sistema de gerenciamento de uma empresa de onibus
> AVISO: Esse foi o meu primeiro projeto, o código está uma bagunça, muito menos em documentação. Mas garanto que melhorei, como se pode ver com Damas Paia...

TechPass foi o tabalho que fiz com o (flavio)[https://github.com/flavioifsp] na matéria de projeto integrado no 2° semestre do curso, ele tem 3 partes:
  -  um site publico onde mostra as informações da empresa e onde o cliente pode criar uma conta e recarregar cartão
  - um admin com contas com diferentes permissões, onde um admin pode definir as rotas do onibus para serem mostradas no site publico, criar cartões diferentes com diferentes tarifas para serem  usadas na catraca descontando da conta da pessoa
  - A catraca do onibus, ela recebe uma parametro para identificar o onibus e tem um input oculto, testado com leitor RFID na apresentação do projeto. Ela recebe o id dos cartões do cliente e desconta a tarifa definida daquele cartão e se não tiver saldo suficiente é recusado.

Estou esquecendo muitos detalhes pois faz muito tempo, mas olhando para trás é meio surreal a dimensão desse projeto para o meu nivel na época. Para se ter noção, olha o diagrama do banco:

<img src="https://github.com/flavioifsp/Pj2-G10-TechPass/blob/main/docs/db/banco%20img%202.png?raw=true" alt="Entrar" width="600" />
 
> E por incrivel que pareça, todas as tabelas são usadas

| Plataforma                                                   | Tecnologia   | 
| ------------------------------------------------------------ | ------------ | 
| [Mobile \| Backend \| Catraca](github.com/flavioifsp/Pj2-G10-TechPass)   | Express, Ejs, bootstrap, mySql, Prisma |

### 4. Lista de exercicios

Bem, isso não é bem um projeto, mas sim uma lista de exercicos que fiz no 1° Semestre, quando eu estava aprendendo a lógica da programação

fonte: [wiki python](https://wiki.python.org.br/ListaDeExercicios)  
lista de exercicios que fiz na época: [replit](https://replit.com/@LEONARDOLOPES29/atividade-avaliativa-1#lista2/a45.js)

