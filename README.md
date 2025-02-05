## Sistema de Recomendação por Imagens

Este projeto utiliza técnicas de Deep Learning e busca de imagens na web para recomendar produtos similares a uma imagem fornecida pelo usuário. Ele utiliza um modelo pré-treinado para extração de características das imagens e compara a similaridade para encontrar os produtos mais parecidos.

## 📌 Tecnologias Utilizadas

- Python

- Google Colab

- PyTorch

- torchvision

- NumPy

- BeautifulSoup (para web scraping)

- Matplotlib

- scikit-learn (para cálculo de similaridade)

## 🔧 Como Funciona

1. O usuário faz o upload de uma imagem de um produto que deseja comprar.

2. O script realiza uma busca por produtos semelhantes na internet.

3. A imagem enviada pelo usuário é processada por uma rede neural (ResNet50) para extrair suas características visuais.

4. As imagens encontradas na internet também são processadas da mesma forma.

5. O sistema compara as imagens usando similaridade de cosseno e seleciona as quatro mais parecidas.

6. A imagem enviada pelo usuário é exibida ao lado das recomendações.

## 🚀 Como Usar

1. Abra o Google Colab.

2. Carregue o script Python fornecido neste repositório.

3. Execute o código.

4. Faça o upload de uma imagem de um tênis.

5. Veja as recomendações geradas pelo sistema!

## 📷 Exemplo de Saída

O sistema exibirá a imagem enviada pelo usuário com o título "Quero Comprar", e ao lado, quatro sugestões de tênis semelhantes com o título "Recomendações".


📝 Licença

Este projeto é open-source e pode ser usado para fins educacionais ou comerciais com os devidos créditos.

Feito com ❤️ para ajudar nas recomendações de produtos escolhidos!

