<link rel="stylesheet" href="https://unpkg.com/sakura.css/css/sakura.css" type="text/css">

# Trabalho prático: Elastic Optical Networks 
**Disciplina:** Redes de Computadores II
**Grupo 15:** Carlos Rodrigues, Eduardo Martins e Eduardo Freire

---

## 1. Introdução às Redes Ópticas Elásticas
Redes ópticas elásticas (EONs) são uma evolução recente das redes de fibra óptica, proposta por M. Jinno em 2008, e podem ser caracterizadas como sucessoras da tecnologia DWDM (dense wavelength division multiplexing). Para a compreensão das vantagens das EONs, vamos esclarecer as características da fibra óptica e de suas diferentes versões.

Um enlace de fibra óptica é capaz de transmitir dados na forma de luz, o que permite taxas de transmissão muito altas e grandes distâncias. Para isso, o sinal elétrico é convertido em um sinal eletromagnético e transmitido por um cabo de fibra óptica. Um cabo de fibra óptica — normalmente construído com sílica, um tipo de vidro — é composto por um núcleo, uma casca, cujo índice de refração é menor que o do núcleo, e um revestimento protetor. Com essa configuração, a luz sofre reflexão interna total e permanece no núcleo, assim sendo transmitida pelo cabo.

Uma técnica essencial utilizada em redes de fibra óptica modernas é a multiplexação por divisão do comprimento de onda (WDM). Ela permite que diferentes canais sejam transmitidos simultaneamente em um único enlace, cada um em uma faixa de comprimento de onda. Podemos citar 2 categorias de WDM. A multiplexação esparsa (CWDM), em que cada canal ocupa 20nm, transmite até 18 canais entre 1270nm e 1610 nm. A multiplexação densa (DWDM) reserva 0,4nm a 0,8nm a cada canal, permitindo a transmissão de mais de 100 canais em uma única fibra óptica, acarretando taxa de transmissão total ainda maior.

Transmitir um sinal a uma taxa muito alta em uma pequena faixa de comprimento de onda, como faz o DWDM, implica problemas complexos. A altas taxas, cada símbolo (bit) é muito curto. Conforme o sinal viaja, ocorre o fenômeno de dispersão, que pode levar à sobreposição entre símbolos consecutivos, e à corrupção dos dados. Para que isso não aconteça, redes DWDM precisam de intervalos de guarda entre símbolos, em que nada é transmitido. Esse fenômeno atua como limitante da taxa de transmissão.

Nesse contexto, são propostas as redes EON, baseadas na tecnologia OFDM (multiplexação por divisão de frequência ortogonal). Redes EON são bem menos vulneráveis à dispersão, o que permite taxas de transmissão ainda maiores, o que é essencial frente à demanda imposta por tendências modernas como aplicações de streaming. Além disso, uma fibra óptica EON pode ser dividida entre conexões de forma mais granular e eficiente. No capítulo seguinte, discutiremos como isso é possível.

## 2. Arquiteturas e Tecnologias


## 3. O problema de Roteamento e Alocação de Espectro


## 4. Controle, Design e Gerenciamento da Rede


## 5. Tópicos Avançados e Tendências


## 6. Conclusões

---

## 7. Referências
