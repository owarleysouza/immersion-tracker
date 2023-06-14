# Immersion Tracker

## Definição do(s) Problema(s)
1. Dificuldade em conduzir o passo a passo de uma imersão de idioma do TNT;
2. Dificuldade de medir satisfação em conduzir as imersões do TNT;
3. Dificuldade de medir progresso das imersões ao longo do tempo.

## Definição de Solução
- Uma aplicação que permite o acompanhamento dos passos da imersão em 'checklist' bem como a evolução do host.

## Jornada de Usuário
- [Imagem do fluxo]()

## Requisitos 
1. Como um usuário eu quero me cadastrar fornecendo e-mail, senha e a confirmação dessa senha para poder usar a aplicação;
2. Como um usuário eu quero entrar na aplicação fornecendo e-mail e senha para que eu possa usar a aplicação;
3. Como um usuário eu quero recuperar minha senha através do e-mail para que eu possa mudá-la e usar a aplicação com a nova senha;
------
4. Como um usuário eu quero ver na página inicial da aplicação as informações de quantidade de imersões, participantes e agendamentos;
5. Como um usuário eu quero poder criar e acessar uma imersão a partir da tela inicial da aplicação;
------
6. Como um usuário eu quero a timeline dos passos da imersão para que eu possa saber todas as informações daquela imersão, principalmente ao clicar em cada ponto, abrindo as infos principais;
7. Como um usuário eu quero uma forma de editar o texto de apresentação do TNT para que eu possa editar o texto caso precise;
8. Como um usuário eu quero uma forma de editar as perguntas para que eu possa editar o texto caso precise;
9. Como um usuário eu quero uma forma de editar os links de encerramento para que eu possa editar o texto caso precise;
10. Como um usuário eu quero concluir uma imersão para que os dados de participantes, agendamentos e percepção minha da imersão sejam computadas nelas e na home, e a imersao vá pra tela de imersões finalizadas (imersões concluídas ou canceladas);

## Regras de Negócio
1. O usuário deve poder criar sua própria timeline, ou usar uma template para as imersões ao escolher um das opções sempre que uma imersão for aberta na primeira vez; (HU 6)
2. Ao concluir uma imersão os dados de participantes, agendamentos e percepção minha da imersão são computados para atualizar a tela principal e aquela imersão vai para a página de imersões finalizadas (imersões concluídas ou canceladas); (HU 10)
3. Ao concluir uma imersão o número de participantes preenchido define o status daquela imersão, se ela foi cancelada (participantes === 0), ou concluída (participantes > 0). Além disso, uma imersão pode passar por 4 estados: criado, quando for inicializada, pronta quando for totalmente preenchida, cancelada quando não houver participantes ou imersão e concluída quando for totalmente realizada. (HU 10)
4. Ao concluir uma imersão, os números de agendamento, participantes e percepção além de irem pro computado geral na tela inicial, também são salvos em cada imersão, para possível analise de dados futura. (HU 10)
