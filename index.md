## Projeto final do curso de Visualizações

Para o TCC do curso, você terá de entregar um TidyTuesday! O TidyTuesday é um evento semanal criado para engajar a comunidade no uso do R para análise de dados. Toda semana uma nova base de dados é liberada, e as pessoas da comunidade montam visualizações para compartilhar nas redes sociais. Se quiser conhecer mais, siga a hashtag #tidytuesday no Twitter!

### Dados

Para acessar os dados pelo R é possível utilizar o comando abaixo:

```r
olympics <- readr::read_csv(
    'https://raw.githubusercontent.com/rfordatascience/tidytuesday/master/data/2021/2021-07-27/olympics.csv&#39;
    )
```

### Trabalhos do último curso

Você pode olhar os trabalhos já realizados no passado para se inspirar: [Premiados](https://curso-r.github.io/202103-visualizacao/#trabalhos-finais-premiados)

O resultado deverá ser entregue em um relatório ou apresentação à sua escolha. A submissão deve ser feita pelo classroom, subindo um arquivo .zip contendo
- Arquivo .Rmd (gostaríamos de conseguir rodá-lo, ou seja, se ele for reprodutível é melhor)
- Códigos auxiliares em R (se existirem)
- O output final (em HTML, PDF, Word, etc). Você pode escolher o formato do trabalho final.
- Não é necessário que a base olympics esteja no repositório, já que ela pode ser lida diretamente da internet.

### Meu projeto

O relatório foi desenvolvido utilizando o pacote **readthedown** e pode ser acessado por este [link](euleralencar.github.io/pages/relatorio_cd2.html).


### Suporte e Contato

Sugestões e/ou críticas podem ser enviadas para 'euleralencar@gmail.com'. 

### Agradecimentos

Agradecimento a CursoR, especialmente a Beatriz Milz e ao Júlio Trecenti, que trouxeram conteúdo excelente e de forma bem didática.
