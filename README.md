# resumo-do-lab
Este repositório contém o resumo das lições aprendidas durante o desenvolvimento do lab na DIO


# Desafio de projeto - Microsoft Azure - Localizando Serviços por Categoria
- Até o momento foi ensinado como criar conta gratuita no Microsoft Azure.
- Foi explicado que determinados tipos de recursos são bloqueados por questões de valor do sérvio ou região de disponibilidade.
- Foram demonstradas configurações de idioma, região e layout do Azure.
- Foi realizada uma demonstração da lista de serviços e um breve overview de algumas categorias e serviços como por exemplo o Bastion.
- Foi informado de que não é recomendada utilização de ferramentas em versão prévia "Preview" em ambientes de produção já que como são ferramentas em fase de testes não há garantia de funcionamento a longo prazo, o uso é por conta e risco do usuario


# Desafio de projeto - Criando máquinas Virtuais na Azure
- Foi abordado o tema de SLA e explicado o tempo de inatividade permitido para cada tipo de SLA. 

| SLA     | Tempo de inatividade por semana | Tempo de inatividade por mês | Tempo de inatividade por ano |
|---------|---------------------------------|------------------------------|------------------------------|
| 99%     | 1,68 hora                       | 7,2 horas                    | 3,65 dias                    |
| 99,9%   | 10,1 minutos                    | 43,2 minutos                 | 8,76 horas                   |
| 99,95%  | 5 minutos                       | 21,6 minutos                 | 4,38 horas                   |
| 99,99%  | 1,01 minuto                     | 4,32 minutos                 | 52,56 minutos                |
| 99,999% | 6 segundos                      | 25,9 segundos                | 5,26 minutos                 |

- Foi abordado o assunto de criação de maquinas virtuais e foram explicadas algumas opções de configuração.
	- Opções de disponibilidade: oferece diversas opções de gerenciamento de disponibilidade e resiliência para os aplicativos.
	- Zonas de disponibilidade: é uma zona fisicamente separa em uma região do Azure. Há três zonas de disponibilidade por região do Azure com suporte. Ao criar uma maquina virtual é possível selecionar até 3 zonas de disponibilidade o que permite manter o sistema disponível mesmo que uma zona seja comprometida.

- Foram abordadas opções de redundância para contas de armazenamento como LRS(armazenamento com redundância local), GRS(armazenamento com redundância geográfica), ZRS(armazenamento com redundância de zona), GZRS(armazenamento com redundância de zona geográfica).
E cada uma dessas opções influência o SLA de disponibilidade da aplicação e no preço.
