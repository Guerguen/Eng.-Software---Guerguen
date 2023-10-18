# Eng.-Software---Guerguen

Sistema emissor de conhecimento de transporte eletrônico (CT-e)

Este sistema é um facilitador para a emissão do conhecimento de transporte eletrônico (CT-e) e manifesto eletrônico de documentos fiscais(MDF-e), ambos documentos fiscais obrigatórios, os quais tem por objetivo de registrar as prestações de serviço do transporte de cargas realizadas no Brasil.

Por se tratar de documentos obrigatórios, os transportadores de carga precisam fazer a emissão, tanto para poderem transitar dentro do território brasileiro, quando para declarar as movimentações fiscais para o orgão regulamentador, caso contrário, determinadas fraudes serão passíveis de sansões, conforme prescrito em lei.
Tendo em vista essa necessidade, o sistema emissor é um facilitador tanto para elaboração do documento, o qual possui uma série de campos obrigatórios a serem preenchidos, quanto para transmissão do mesmo via integração com o SEFAZ, pois caso não haja essa validação por parte do mesmo, o conhecimento não terá valor fiscal algum. 

O acesso ao sistema se dá por um website, no qual o transportador fará login através dos seus dados previamente cadastrados, sendo direcionado posteriormente ao portal de sua transportadora, onde poderá fazer novas emissões, bem como acessar as emissões anteriores. Após a emissão do novo documento, ele será transmitido ao SEFAZ via integração do sistema. 
Caso o documento esteja dentro das especificações do SEFAZ, será retornado o status de autorizado para o sistema, caso contrário, retornará com o status de rejeição, apontando quais campos devem ser ajustados, para então posteriormente reenviar e repetir o processo. Posteriormente, o usuário poderá fazer o download desses arquivos em formato PDF e XML para que possa apresentar para os postos fiscais, clientes e contabilidade.

Para execução do projeto, será necessário os seguintes requisitos:
Desenvolvedor Full Stack, Desenvolvedor de Banco de Dados, Gerente de Projeto, Engenheiro-Arquiteto de Software, Analista de Testes, funções as quais podem ser divididas entre dois desenvolvedores. Quanto ao Hardware necessário para que possam operar: Dois computadores com capacidade de 16 a 32 GB de RAM, 256GB de SSD, I7, com Acesso a Internet. Dentre as ferramentas necessárias para executar o projeto estão: JavaScript, SQL, Knockoutjs e Nhibernate.

Através do servidor em nuvem, o usuário poderá acessar ao seu login da transportadora para ter acesso ao portal, portanto será necessário fazer este acesso através de um computador, não sendo necessário altos requisitos, mesmo uma máquina de baixa especificação e diferentes sistemas operacionais, é capaz de executar a aplicação.

Por se tratar de um sistema emissor de documentos os quais são padronizados pelo SEFAZ, não há novas implementações previstas exceto quando a alguma mudança na legislação, as quais sempre possuem um grande tempo prévio para entrarem em vigor. A última alteração prevista foi anunciada no mês 06/2023, todavia entrará em vigor somente após 31 de janeiro de 2024. Desta forma, sempre que há alguma atualização prevista, há tempo  hábil para que os desenvolvedores possam atuar, bem como usualmente não se tratam de mudanças drásticas no processo de emissão de CT-e.

Status do projeto: Concluído.
