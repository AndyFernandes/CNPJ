# Tratando dados CNPJ da Receita Federal

Esse projeto visa oferecer uma plataforma para visualizar os dados de CNPJ disponibilizado pela Receita Federal. Esse projeto foi disponibilizado para AIESEC Fortaleza, no intuito de ajudá-los a prospectarem empresas.

---

Passos:

01. Conversão dos dados disponibilizados na Receita Federal para .csv utilizando a ferramenta [CNPJ full](https://github.com/fabioserpa/CNPJ-full).
02. Os dados são filtrados para a Região Metropolitana de Fortaleza. Devido ao grande tamanho de dados e a capacidade limitada de armazenamento do repositório, os dados encontram-se neste [drive](https://drive.google.com/drive/folders/1DetO_3iy_7g2PfIPNIGE2IBcrcm8PqDm?usp=sharing)
03. Os endereços dos dados são agrupados e então é feito a geomapeamento dos dados, através da obtenção das coordenadas pelo endereço. [Notebook 00 e 01]
04. São tratados os *outs points*, que por algum motivo foram convertidos para coordenadas não presentes na RMF. [Notebook 02]
05. É oferecido um notebook para realização de filtragem dos dados + visualizações dos pontos utilizando o Cluster do Folium.