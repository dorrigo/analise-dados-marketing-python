# Projeto de Tratamento e Análise de Dados de Marketing com Python 

Você pode conferir os gráficos e códigos no arquivo **df_mkt** encontrado no repositório.

## Análise de Engajamento por Categoria

A análise dos dados revela que a categoria **Esportes** apresenta o **melhor desempenho** em taxa de engajamento, seguida de perto pela categoria **Fashion**, que mostra um resultado bem próximo. Em contraste, as categorias **Tecnologia** e **Comida** registram os **indicadores mais baixos** de engajamento.

**Insight estratégico:**  
Para potencializar o desempenho da categoria de Tecnologia, recomenda-se a **criação de conteúdos híbridos** que integrem tecnologia com outras áreas de maior engajamento. Por exemplo:  
- Tecnologia aplicada ao Esporte (análise de desempenho atlético)  
- Tecnologia na Comida (novas tecnologias no setor)  

---

## Análise de Ganho de Seguidores por Tipo de Post

O ganho de seguidores não tem diferença significativa neste dataset, porém mesmo com essa pequena diferença o conteúdo **áudio-visual** ainda tem vantagem quanto ao conteúdo **textual**.

---

## Análise de Ganho de Seguidores por Categoria de Post

Os dados revelam um cenário intrigante: enquanto a categoria **Esportes** lidera em taxa de engajamento, mostra-se **menos eficaz** na atração de novos seguidores, ocupando a última posição neste aspecto. Em contrapartida, o conteúdo de **Fashion**, embora apresente menor engajamento, destaca-se como o **mais eficiente** para conquistar novos seguidores.

**Implicações Práticas**  

Para objetivos de **engajamento** (curtidas, comentários, shares):  
- Priorizar conteúdos esportivos  
- Aproveitar momentos de grandes eventos esportivos  

Para **crescimento de base** (aquisição de seguidores):  
- Investir em postagens de moda e lifestyle  
- Desenvolver séries regulares de conteúdo fashion  

---

### Análise da Efetividade dos Posts ao Longo do Dia

Podemos identificar no **Histograma das postagens** uma menor concentração de posts nos horários das **6h e 11h da manhã**, o que confirma a baixa de engajamento no mapa de calor (com temas abaixo da média de 2.5 no intervalo). Para contornar esse problema, o ideal seria:

- Trabalhar mais os conteúdos de tema **Fashion** e **Comida** que apresentam maior taxa de engajamento nestes horários com menos volume de posts
- Propor posts com **temas cruzados** entre eles

**Período Vespertino (a partir das 14h):**
- Maior volume de postagens do dia
- Todos os temas apresentam taxa de engajamento próxima
- Oportunidade de manter diversificação de conteúdos

**Período Noturno/Madrugada:**
- **Destaque de engajamento**:
  - Conteúdo de **Esportes** (taxa acima de 3, superior à média)
  - Posts de **Comida** (para o público noturno)
  
**Insight Final:**
É interessante explorar esses dados para entender:
- Padrões de consumo por horário
- Preferências do público em diferentes turnos
- Criar pautas de conteúdo baseadas em evidências

---

## Análise da Distribuição de Postagens com Spam

É preocupante para uma rede social que **mais da metade** dos posts apresentem **Spam Flag**. É importante monitorar:  
- Bots  
- Perfis falsos  
- Links inseguros  

Essa prática:  
- Arruína a experiência dos verdadeiros usuários  
- Faz com que as ferramentas diminuam a entrega dos conteúdos orgânicos afetados  

**Solução:**  
Existem configurações que auxiliam na diminuição e podem melhorar a qualidade e segurança da conta.

---

## Análise das Métricas de Engajamento

- **Média de Likes**: 116.754,25  
- **Média de Compartilhamentos**: 11.536,25  
- **Média de Comentários**: 23.577,75  

O conteúdo de **Tecnologia** domina em Likes com valor **10% acima** da média geral.  
Os compartilhamentos e comentários apresentam valores bem próximos da média geral, tendo maior relevância em posts de **Comida** (quem não gosta de compartilhar ou marcar um amigo em uma receita, não é?).

Essa visualização ajuda a entender melhor o desempenho de cada categoria de post e pensar em estratégias que melhorem os indicadores, baseando-se também no que funciona naquelas categorias que apresentam desempenho acima da média.
