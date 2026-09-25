# Controle de Check-in da Academia

Aplicação web para registrar a chegada e a saída dos alunos de um studio de treinamento. Com os dados coletados, analisei o fluxo de alunos e resolvi um problema real de lotação.

**[▶ Abrir a aplicação](https://anthonnyoliveira.github.io/controle-academia/)**

## O problema

Em um studio de treinamento, a sala ficava lotada em alguns horários. A hipótese inicial era "tem aluno demais", mas não havia dados para confirmar.

## O que eu fiz

1. Criei esta aplicação, com apoio de ferramentas de IA, para registrar os horários reais de chegada e saída de cada aluno.
2. Usei a aplicação durante **1 mês** no studio.
3. Analisei os dados com estatística descritiva:
   - **Média** do tempo de permanência de cada aluno.
   - **Moda** do horário de chegada, agrupando as chegadas em intervalos de 15 minutos.

## O resultado

Os dados mostraram que os alunos de um horário chegavam **atrasados** e os do horário seguinte chegavam **adiantados**. As duas turmas se encontravam na sala ao mesmo tempo, e isso causava o congestionamento.

Recomendei um reajuste dos horários, o que **abriu espaço para 2 alunos a mais** nos horários das 18h e 18h30.

## Funcionalidades

- **Alunos:** cadastro com nome, horário marcado e atividades habituais.
- **Check-in:** registro da chegada e da saída reais, com botão "Agora".
- **Histórico:** tabela com tempo planejado, tempo real e a diferença entre eles.
- **Dashboard:** tempo médio de permanência e horário de chegada mais comum (moda) por aluno.

## Tecnologias

- HTML, CSS e JavaScript, em um único arquivo, sem instalação.
- Os dados ficam salvos no próprio navegador (`localStorage`). Nenhuma informação dos alunos é enviada para a internet.

## Como usar

Abra o link acima ou baixe o arquivo `index.html` e abra no navegador.

## Próximos passos

- Exportar os registros para CSV.
- Analisar os dados em Python (Pandas) e criar gráficos de chegada por horário.
- Incluir a **mediana**, que é menos afetada por valores fora do padrão do que a média.

---

Feito por [Anthonny Oliveira](https://www.linkedin.com/in/anthonny-oliveira-a28983146), estudante de Ciência da Computação.
