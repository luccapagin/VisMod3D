# AR.js - Visualização de Modelo 3D

Este projeto utiliza AR.js e A-Frame para visualizar modelos 3D em realidade aumentada (AR) usando um marcador Hiro.

## Funcionalidades

- Visualização de modelos 3D em AR
- Controle de gestos para manipulação do modelo
- Iluminação ambiente e direcional

## Como Usar

### Passo a Passo para Imprimir um Hiro Marker

1. Acesse https://upload.wikimedia.org/wikipedia/commons/4/48/Hiro_marker_ARjs.png
2. Imprima o marcador em uma folha de papel.

### Obtendo Novos Modelos 3D no Sketchfab

1. Acesse o [Sketchfab](https://sketchfab.com/).
2. Procure pelo modelo 3D desejado.
3. Baixe o modelo no formato `.gltf`

### Adicionando Novos Modelos 3D ao Projeto

1. Coloque o arquivo do modelo 3D na pasta `models` do projeto.
2. Atualize o caminho do modelo no arquivo `index.html`:
    
    <!-- ...código... -->
    <a-asset-item id="product-model" src="./models/nome_do_seu_modelo.gltf"></a-asset-item>
    <!-- ...código... -->
    ```
3. Adicione também a pasta `textures`, se uma veio junto com seu modelo 3D.

## Casos de Uso

### 1. Demonstrações Interativas de Produtos
**Caso de Uso:** Varejo de Móveis
- **Cenário:** Um varejista de móveis cria um app de AR onde os clientes podem ver como diferentes peças de móveis ficariam em sua casa.
- **Benefício:** Ajuda os clientes a tomar decisões de compra informadas e reduz devoluções de produtos.

### 2. Ferramentas Educacionais
**Caso de Uso:** Educação Científica
- **Cenário:** Um app educacional que permite aos alunos interagir com modelos 3D do sistema solar, estruturas químicas ou órgãos humanos.
- **Benefício:** Facilita a compreensão de conceitos científicos complexos e torna o aprendizado mais envolvente.

### 3. Provas Virtuais
**Caso de Uso:** Varejo de Moda
- **Cenário:** Uma loja de roupas online oferece um provador virtual onde os clientes podem ver como as roupas ficarão neles antes de comprar.
- **Benefício:** Melhora a experiência de compra online e reduz a probabilidade de devoluções.

### 4. Design e Decoração de Interiores
**Caso de Uso:** Design de Interiores
- **Cenário:** Um app que permite aos usuários visualizar como diferentes cores de tinta, papéis de parede ou móveis ficarão em sua casa.
- **Benefício:** Ajuda os proprietários a tomar melhores decisões de design e aumenta a satisfação do cliente.

### 5. Exposições de Museus
**Caso de Uso:** Reconstituições Históricas
- **Cenário:** Um app de museu que mostra reconstruções 3D de artefatos antigos ou eventos históricos quando os visitantes apontam seus dispositivos para exposições específicas.
- **Benefício:** Proporciona uma compreensão mais profunda da história e melhora a experiência no museu.

### 6. Jogos
**Caso de Uso:** Jogos de Aventura
- **Cenário:** Um jogo de AR onde os jogadores caçam tesouros virtuais escondidos em locais do mundo real.
- **Benefício:** Combina atividade física com jogos para uma experiência mais imersiva.

### 7. Treinamento Médico
**Caso de Uso:** Treinamento Cirúrgico
- **Cenário:** Um app de treinamento médico onde os alunos podem praticar cirurgias em modelos 3D de anatomia humana.
- **Benefício:** Proporciona prática prática sem os riscos associados a cirurgias reais.

### 8. Manutenção e Reparo
**Caso de Uso:** Reparo Automotivo
- **Cenário:** Um app que sobrepõe instruções 3D no motor de um carro para guiar os técnicos em tarefas complexas de reparo.
- **Benefício:** Melhora a precisão e a eficiência no trabalho de reparo.

## Conclusão

Este projeto demonstra como a realidade aumentada pode ser utilizada em diversas indústrias para melhorar a experiência do usuário e aumentar o engajamento. Sinta-se à vontade para explorar e adaptar o projeto para atender às suas necessidades específicas.