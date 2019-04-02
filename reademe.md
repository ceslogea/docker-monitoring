

O que é Docker
O Que são Containers
O que é Docker Composer

Install Docker CE (Ubunto)

Install Docker Composer (Ubunto)

Baixando repo do git
Executando docker composer

Sobre cAdVisor explanação mostrando interface criada pelo compose

Sobre Node Exporter explanação mostrando interface criada pelo compose

Sobre o Prometheus explanação mostrando interface criada pelo compose

Sobre o Grafana explanação mostrando interface criada pelo compose


Executando testes reddis
https://redis.io/topics/benchmarks
sudo apt install redis-tools 
redis-benchmark -n 100000

Visualizando resultados cAdvisor

Visualizando resultados NodeExporter

Conclusão





    "User cases em diferentes tipos de ciclos de desenvolvimento". 
    Trata sobre como User cases são aplicados nas metodologias de desnvolvimento:  Waterfall, Iteractive, Spiral, Agile, V-Shaped.


"Comparando resultados de coletores de dados de hardware: cAdvisor e node exporter" 

"Node Exporter e cAdvisor, comparação entre plugins coletores de dados"

"Analise de métricas de hardware: cAdvisor e node exporter"

"Avaliação comparativa de monitores de desempenho para containers dockers"

"Um Estudo de Análise Comparativa de monitores de desempenho para Containers Docker"




O Flavio deixa eu só me confirmar uma coisa pfv: 

O Node exporter coleta dados de desempenho do HARDWARE, ele não enxerga containers.

O cAdvisor, encherga somente containers e extrai alguns KPIs de Hardware em comum com NodeExporter: TX RX, Processador, para mensurar memoria por exemplo teriamos que agrupar os containers e ver qual a correlação

Seria coerente comparar mesmo os 2 coletando metricas de fontes diferentes? 




Preciso de uma ajuda com a escolha de um orientador, meu artigo trata basicamente sobre a comparação de resultados de sistemas coletores de dados tipicamente usados com Docker (Node Exporter e cAdvisor).