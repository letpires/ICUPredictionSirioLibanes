<p align="center">
  <img src="https://github.com/letpires/ICU_prediction_sirio_libanes/blob/main/banner_projeto_final.png" >
</p>

<h2 align="center">
  Machine Learning na COVID 19
</h2>

<p align="center">
  Este projeto foi desenvolvido com o objetivo de criar um modelo de Machine Learning capaz de ajudar os médicos e enfermeiros do Hospital Sírio-Libanês a prever quais pacientes precisarão ser admitidos na unidade de terapia intensiva (UTI) devido a complicações da COVID-19 e, assim, definir qual a necessidade de leitos de UTI do Hospital a partir dos dados clínicos individuais disponíveis.🏥.</a>
</p>

<p align="center">
    <img alt="Numpy" src="https://img.shields.io/badge/numpy-1.20.0-blue">
    <img alt="Pandas" src="https://img.shields.io/badge/Pandas-1.2.3-yellow">
    

   </a>
</p>

## 📄 Estrutura do repositório

- Veja os dados utilizados [DADOS DO HOSPITAL SÍRIO LIBANÊS](https://github.com/letpires/ICU_prediction_sirio_libanes/blob/main/Kaggle_Sirio_Libanes_ICU_Prediction.xlsx);
- Leia o notebook do projeto [IMPLEMENTANDO MODELOS DE ML NA COVID 19](https://github.com/letpires/ICU_prediction_sirio_libanes/blob/main/Leticia_Pires.ipynb).

## ➕ Contexto

A pandemia de COVID-19 atingiu o mundo inteiro, sobrecarregando os sistemas de saúde - despreparados para uma solicitação tão intensa e demorada de leitos de UTI, profissionais, equipamentos de proteção individual e recursos de saúde. Países como o Brasila, que já possui sistema de saúde superlotados, vem sofrendo com a falta de leitos de Unidade de Terapia Intensiva (UTI) na internação de seus pacientes. Isso já aconteceu e vem acontecendo em alguns estados do Brasil, como Amazonas ([link da matéria](https://g1.globo.com/am/amazonas/noticia/2021/01/14/secretario-de-saude-do-am-fala-que-estado-vive-colapso-do-plano-logistico.ghtml)), onde pacientes não estão mais conseguindo acesso a UTI, assim como não possuem equipamentos básicos para a manutenção de vida, como oxigênio. Em Santa Catarina também o estado é crítico, onde os hospitais de Blumenau já anunciaram triagem para internação de acordo com a chance de sobreviver ([link da matéria](http://g1.globo.com/sc/santa-catarina/videos/v/hospitais-de-blumenau-anunciam-triagem-para-internacao-de-acordo-com-chance-de-sobreviver/9355080/)). Com base nesses acontecimentos e até mesmo na prevenção de sobrecarga do sistema de saúde das redes privadas, o Hospital Sírio-Libanês, busca prevenir e até mesmo predizer, com base em dados clínicos de seus pacientes, conforme forem sendo admitidos no ambiente hospitalar, a necessidade ou não de internação nas UTIs nas próximas horas. A proposta feita pelo Hospital Sírio Libanês está disposta [nesse link do Kaggle](https://www.kaggle.com/S%C3%ADrio-Libanes/covid19).


## ⚠️ Informações gerais

Em nosso conjunto de dados, temos a seguinte janela de dados, ou como é chamado no dataset, `WINDOW`:
 |WINDOW|DESCRIÇÃO|
|:---------:|:-----------------------------------:|
| 0-2	    |  From 0 to 2 hours of the admission |
| 2-4	    | From 2 to 4 hours of the admission  |
| 4-6	    |  From 4 to 6 hours of the admission |
| 6-12    |	From 6 to 12 hours of the admission |
| Above-12|     	Above 12 hours from admission |

- É critério obrigatório para este projeto, não utilizar os dados quando o paciente deu entrada na UTI -> ICU = 1, pois estes já terão ido diretamente para a UTI nas 2 primeiras horas, não importando para a predição;
- A informação e dicas passadas pelo próprio Hospital e que foram seguidas para contrução do modelo é que: devem ser previstos pacientes que necessitarão de UTI e quais NÃO necessitarão de UTI.

## 🚀 Tecnologias 

- 📄 Bibliotecas: Pandas, Numpy, Seaborn, Matplotlib, Yellowbrick, Scikit Learn
- ⚡️ Google Colaboratory.



---

Made with 💜 by Letícia Pires :wave: 
