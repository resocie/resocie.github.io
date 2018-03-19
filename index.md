---
layout: default
---

# OBSERVATÓRIO DAS ELEIÇÕES 2018

O **Observatório das Eleições** 2018 foi criado no âmbito do grupo de pesquisa Resocie (“Repensando as Relações Sociedade-Estado”) do Instituto de Ciência Política - IPOL da Universidade de Brasília, e conta com o apoio técnico da Professora Cláudia Melo, do Departamento de Computação - CIC, e da turma da disciplina Engenharia de Software. O Observatório abriga uma série de iniciativas de pesquisa, que têm como objetivo geral analisar os usos e impactos das novas tecnologias digitais nas eleições brasileiras de 2018. 

Mais especificamente, queremos compreender como os atores políticos (candidatos, organizações da sociedade civil, movimentos sociais, coletivos) usarão mídias sociais para tentar influenciar o processo eleitoral. Em particular, focaremos no estudo dos usos de quatro dessas mídias: Facebook, YouTube, Instagram e Twitter. Essas plataformas têm sido utilizadas em eleições para atingir audiências diferentes e com estratégias distintas. É importante, portanto, estudar cada uma separamente e poder comparar seus usos.

Além disso, estamos interessados em compreender melhor os impactos da chamada “governança de algoritmos” na difusão de informações e propaganda eleitoral. Em especial, queremos analisar os possíveis impactos dos algoritmos de serviços de busca como o Google. 

É importante compreender como esses usos e impactos mudam, à medida que os atores se adaptam às mudanças de contexto prévias ao momento eleitoral. Por isso, precisamos de estratégias e ferramentas que permitam fazer a coleta sistemática de dados ao longo do tempo.

## Justificativa

Estas eleições representam o fim de um ciclo político da democracia brasileira. Iniciado em 1989, nas primeiras eleições presidenciais diretas depois da ditadura militar, encerra-se em 2018 com a crise dos principais atores que lideraram o país nos processos de transição e consolidação democráticas. Ao mesmo tempo em que os atores tradicionais estão em crise, não há uma renovação política clara, nem de partidos políticos e de candidatos ou mesmo de programas políticos. Estas eleições serão marcadas pela incerteza quanto às escolhas e pela polarização política. 

Mais diretamente relacionado ao nosso problema de pesquisa, o processo também é incerto pela ausência de regras claras (pelo menos até o momento) sobre como as campanhas poderão usar as tecnologias digitais. A legislação eleitoral deixa margem para muitas dúvidas, mas a mudança nas regras de financiamento e as possibilidades de compra de propaganda online tem levado muitos analistas políticos a argumentar que a campanha na Internet será especialmente importante este ano. 

Este projeto busca não apenas contribuir para o debate acadêmico sobre o papel da Internet em processos eleitorais, mas também colaborar para o aprimoramento das regras eleitorais sobre o tema.

## Coleta de Dados: o mapa do terreno

Para alcançar os objetivos do Observatório, precisamos de dados sistemáticos e longitudinais sobre os usos que os atores que nos interessam têm feito de mídias sociais e de serviços de busca. Já estamos fazendo um mapeamento preliminar da presença desses atores no que chamamos de “Web pública”, ou seja, naquelas plataformas às quais temos acesso sem necessidade de pedir permissão: sites, páginas oficiais do Facebook (“fan pages”), contas do Twitter (de acesso público), canais do YouTube e contas no Instagram. O projeto também utilizará técnicas qualitativas para coletas de dados, tais como entrevistas e grupos focais, mas isso será feito apenas a partir de junho.

Para a coleta sistemática de informações quantitativas da “Web pública”, fizemos uma lista de aproximadamente 75 atores-chave, que se dividem em dois tipos: organizações da sociedade civil que participarão da campanha e que têm uma pluralidade de orientações ideológicas e de formas organizativas (frentes; coletivos; organizações com membros; organizações sem membros); pré-candidatos à Presidência da República. Neste momento estamos limitando a coleta apenas aos pré-candidatos à Presidência, mas mais adiante poderemos ampliar para candidatos a outros cargos. 

O número de atores-chave tem variado mês a mês, de acordo com as mudanças no cenário eleitoral. Por exemplo, excluímos Luciano Huck e outros pré-candidatos da coleta, mas adicionamos Celso Amorim. Em um cenário tão incerto – como dizíamos acima – e dinâmico como o que vivemos, essa lista precisará passar por um processo permanente de atualização. Neste momento, estamos fazendo as atualizações no início de cada mês.

Para cada mídia social, temos interesse em coletar as seguintes informações (e sua variação ao longo do tempo, até as eleições):

* **Facebook**: número de seguidores de cada página e número de postagens (pode ser o número de posts publicados em um determinado período ou o número total)
* **Twitter**: número de seguidores de cada conta e número de tweets publicados (pode ser o número de tweets publicados em um determinado período ou o número total); também é importante saber se os atores não têm conta no Twitter
* **YouTube**: número de assinantes do canal e número de vídeos postados; também nos interessa saber se os atores listados não têm canal
* **Instagram**: número de seguidores e número de postagens daqueles atores que têm conta no Instagram

Além dessas informações básicas sobre alcance e uso, teríamos interesse em dados de engajamento, ou seja, em que medida os usuários interagiram com esses canais, seja comentando, compartilhando ou curtindo. No entanto, isso pode ficar para uma segunda etapa da pesquisa.

No caso do serviço de busca, focaremos especificamente no Google. Neste caso, nos interessa desenvolver uma estratégia que permita coletar informações de usuários sobre os resultados de buscas a partir de um conjunto de palavras-chave. Mais uma vez, precisamos considerar a dinâmica eleitoral para a definição dessas palavras-chave, que serão atualizadas ao longo do tempo.

## Repositórios

O ponto de partida para as demandas previamente listadas são os repositórios abaixo listados. Espiem, forkem, clonem, contribuam!

https://github.com/resocie/twitter-data-monitor
https://github.com/resocie/instagram-data-monitor
https://github.com/resocie/youtube-data-monitor
https://github.com/minimaxir/facebook-page-post-scraper
https://tools.digitalmethods.net/beta/scrapeGoogle/
https://github.com/teogenesmoura/spreadsheetsGoogle
