 

 

![img](file:///C:/Users/USURIO~2/AppData/Local/Temp/msohtmlclip1/01/clip_image002.jpg)

 

 

 

 

Projeto Web 

 

Pré-requisitos de desenvolvimento

Sabrina E. F. Lobo | Engenharia Mecatrônica -IFSC | 20/07/2021

# Classificação dos requisitos necessários para o sistema

 

  Os requisitos são classificados em duas partes sendo, requisitos funcionais (RF) e requisitos não funcionais (RNF). Os requisitos funcionais são todos os problemas e necessidades que o software deve atender. Já os requisitos não funcionais se referem a forma como o software tornará realidade o que está sendo planejado. Ou seja, os requisitos funcionais estão focados no que será feito, enquanto os não-funcionais descrevem como serão feitos. Sendo assim podemos classificar os requisitos do sistema da seguinte forma:

 

·    **Requisitos funcionais (RF):**

 

[RF001] O sistema deve cadastrar usuários e material.

[RF002] O sistema deve adicionar, atualizar e excluir, matriculas, material e ferramentas.

[RF003]O sistema deve associar ferramentas e materiais as matriculas.

[RF004] O sistema deve ter uma aba de pesquisa para palavras chave.

[RF005] O sistema deve ter a possibilidade de cadastro para diversos laboratórios ou ambientes diferentes.

[RF006] O sistema deve ter um checkbox de reserva para determinados ambientes e laboratórios.

[RF007] O sistema deve ser simples e intuitivo para gerenciar itens de projeto de pesquisa da meca.

[RF008] O sistema deve ter controle de permissões nas contas (Usuário e Administrador).

 

·    **Requisitos não funcionais (RNF):**

 

[RNF001] Desenvolvimento do sistema baseado em sistemas operacionais de desktop;

[RNF002] O sistema deve ser implementado com um banco de dados que permita o registro de pelo menos 5 mil itens.

[RNF003] O sistema deve permitir acesso simultâneo.

[RNF004] O sistema deve funcionar com requisitos mínimos de memória, hardware e processamento. (Afim de que possa ser usado em qualquer dispositivo com baixo desempenho)

 

 

 

 

## Descrição geral 

 

  O sistema deve ser simples e intuitivo para que qualquer usuário possa acessar de forma fácil sem grandes complicações, deve possibilitar que vários usuários usem o sistema ao mesmo tempo. 

  É necessário que o sistema tenha controle de permissões de contas de usuários e administradores, sendo este o item mais importante da lista de requisitos funcionais. Os usuários devem ter acesso a quantidade de materiais e ferramentas disponibilizadas nos laboratórios, os mesmos também terão a opção de reserva de material. Para determinados laboratórios a reserva estará sujeita a permissão dos chefes de laboratório e responsáveis pelo item. As contas de administradores terão controle de todo o sistema como cadastro de materiais, ferramentas, matriculas, permissões de reserva e outras funcionalidades que serão necessárias ao sistema. As contas de administradores devem ser disponibilizadas aos chefes de laboratório, para que assim tenha um maior controle sobre os dados inseridos no sistema.

  O sistema não deve usar muito poder de processamento do dispositivo onde será usado, para afim de ser utilizado até em dispositivos mais antigos como os já existentes nos laboratórios. Deve atender aos itens de requisito de forma que possa atender o gerenciamento de materiais e ferramentas para os projetos de pesquisa da engenharia mecatrônica do IFSC.