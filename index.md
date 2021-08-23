## Projeto final do curso de Visualizações

Para o TCC do curso, você terá de entregar um TidyTuesday! O TidyTuesday é um evento semanal criado para engajar a comunidade no uso do R para análise de dados. Toda semana uma nova base de dados é liberada, e as pessoas da comunidade montam visualizações para compartilhar nas redes sociais. Se quiser conhecer mais, siga a hashtag #tidytuesday no Twitter! **O trabalho proposto pelo Curso-r é o exemplo das Olimpíadas disponível no github da TidyTuesday.**

### [O projeto](https://euleralencar.github.io/pages/relatorio_cd2.html)

O nosso projeto tem como objetivo analisar o desempenho do Brasil ao longo das Olimpíadas. O relatório foi desenvolvido utilizando o pacote **readthedown** e pode ser acessado por este **[link](https://euleralencar.github.io/pages/relatorio_cd2.html)**. 

### Dados

Para acessar os dados pelo R é possível utilizar o comando abaixo:

```r
olympics <- readr::read_csv(
    'https://raw.githubusercontent.com/rfordatascience/tidytuesday/master/data/2021/2021-07-27/olympics.csv&#39;
    )
```
### Suporte e Contato

Sugestões e/ou críticas podem ser enviadas para 'euleralencar@gmail.com'. 

### Agradecimentos

Agradecimento a CursoR, especialmente a Beatriz Milz e ao Júlio Trecenti, que trouxeram conteúdo excelente e de forma didática.
