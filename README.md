# Relatório

## Biblioteca Open CV

### O que é?

O Open Source é uma biblioteca open-source para visão computacional e processamento de imagens. Ele possui uma licença na qual permite o usuário utilizar, modificar e distribuir o software.

### **Criador do Open CV**

O Open CV foi criado pela Intel em 1999, onde seu principal desenvolvedor e líder inicial foi o Gary Bradski, que atuava como engenheiro da Intel e também como pesquisador de IA e visão computacional.

Bradski criou visando fornecer uma biblioteca gratuita e otimizada, podendo tanto ser usada pela indústria e pesquisa acadêmica.

### História

- **1999/2000**
    - Intel lança o projeto para uso interno.
- **2006**
    - Versão 1.0 chega ao público.
- **2009**
    - Open CV 2 com APIs C++ modernizadas, oferecendo melhoria de desempenho e portabilidade.
- **2015**
    - Open CV 3.0 adiciona suporte C++11, melhores bindings para Python e mais algoritmos de Machine Learning.
- **2023/2024**
    - Open CV 4.8.0 traz backend Vulkan (até 4× desempenho), suporte a AVIF/HEVC, OpenVINO e melhorias para JS/Python.
- **2025**
    - Versão 4.12.0 liberada com suporte ao C++20, quantização DNN, HALs para RISC-V e Qualcomm, entre outros.
    - OpenCV 5 Alpha (preview) já disponível.

### **Linguagens e Plataformas**

O OpenCV foi projetado para ser multiplataforma. Ele foi escrito nativamente na biblioteca C++, e a biblioteca do OpenCV suporta Windows, Linux, Android, IOS, MacOS, e possui interfaces C++, Python, Java, MATLAB.

### Como Funciona

- **Nível Conceitual**
    - Pega imagens e vídeos como matrizes de pixels.
    - Aplica operações matemáticas e lógicas para extrair informações visuais.
- **Entrada dos Dados**
    - Carrega dados de várias fontes.
- **Processamento da imagem ou vídeo**
    - Após ler a imagem ou vídeo, possibilita aplicar operações como:
        - Geométricas
        - Cores
        - Filtros
        - Reconhecimentos
        - Desenhos
- **Exibição ou salvamento do resultado**
    - Possibilita:
        - Mostrar em janelas (cv2.imshow)
        - Salvar em disco (cv2.imwrite)
        - Exportar como vídeo (cv2.VideoWriter)

### Principais Recursos

- **CORE / IMGPROC**
    - **CORE**: Funções básicas para lidar com imagens.
    - **IMGPROC**: Ajusta e transforma imagens.
- **Objdetect / Tracking**
    - Detecção de faces.
- **Features2D / Calib3D**
    - **Features2D**: Encontra pontos importantes em imagens.
    - **Calib3D**: Trabalha com visão e medições em 3D.
- **ML interno**
    - Conjunto de métodos de aprendizado de máquina para analisar e classificar dados.
- **DNN**
    - Usa redes neurais para reconhecer e identificar objetos em imagens e vídeos.
- **G-API**
    - Ferramenta do OpenCV para criar e acelerar o processamento de imagens de forma mais rápida e organizada.

### Aplicações Reais

- **Automação e robótica**
    - Detecção de obstáculos
    - Fluxo óptico
    - Reconhecimento de sinais de trânsito
- **Medicina**
    - Segmentação de tumores
    - Registro de imagem
    - Pré-processamento DICOM
    - Análise de contraste
- **Segurança e vigilância**
    - Detecção de movimento
    - Reconhecimento facial
    - Alerta automáticos
- **AR/VR**
    - Interface humano-computador
    - Reconstrução 3D
    - Aplicações em drones
    - Aplicações em veículos autônomos

### Pontos Positivos

- **Gratuito e Open Source** – O OpenCV tem código aberto no GitHub, permitindo uso, estudo, modificação e contribuição por qualquer pessoa.
- **Grande Comunidade e Documentação** – Conta com vasta comunidade, muitos tutoriais, fóruns e documentação oficial detalhada que facilitam o aprendizado e solução de problemas.
- **Integração com outras tecnologias** – Suporta várias linguagens e sistemas operacionais, além de integração com frameworks como TensorFlow, PyTorch e outros.
- **Biblioteca rica e completa** – Oferece milhares de funções, indo de filtros simples até redes neurais avançadas.

### Concorrentes no mercado

- **1. Pillow (PIL Fork)**

- **Vantagens:** Simples de usar, ótima para manipulação básica de imagens (corte, redimensionamento, filtros), boa integração com Python puro.
- **Desvantagens:** Pouco voltada para visão computacional avançada, não possui recursos nativos para detecção de objetos, faces, etc.

- **2. scikit-image**

- **Vantagens:** Baseada em NumPy/SciPy, fácil integração com bibliotecas científicas, boa para processamento e análise de imagens, código limpo.
- **Desvantagens:** Mais lenta em operações pesadas, não é ideal para aplicações em tempo real, menos suporte para hardware acelerado.

- **3. Dlib**

- **Vantagens:** Excelente para detecção e reconhecimento facial, suporte a Machine Learning integrado, bem otimizada em C++.
- **Desvantagens:** Pouco flexível fora de aplicações de faces, comunidade menor que a do OpenCV.

### Funções para serem testadas

- Visão Computacional
- Detecção de objetos em Tempo Real
- Segmentação de imagens
- Reconhecimentos de movimentos e gestos
- Reconhecimento facial
- Realidade aumentada
- Execução de várias operações na imagem

---

## Biblioteca NumPy

### O que é?
NumPy é uma biblioteca Python usada para trabalhar com matrizes (arrays). Criada em 2005 por Travis Oliphant, significa Numerical Python.  
Permite operações com álgebra linear, transformada de Fourier e matrizes N-dimensionais. É base para bibliotecas como Pandas, Scikit-Learn, SciPy e TensorFlow.

### Características
- Trabalha com arrays N-dimensionais (ndarray)  
- Mais rápido e eficiente que listas Python  
- Ideal para dados complexos (imagens, vídeos, machine learning)  
- Memória contínua, aumentando eficiência (“Localidade de Referência”)  

### Vantagens
- Muito mais rápido que listas comuns  
- Operações vetoriais simples e eficientes  
- Compatibilidade com outras bibliotecas científicas  
- Ideal para grandes volumes de dados numéricos

### Desvantagens
- Tipos de dados homogêneos (não mistura tipos na mesma matriz)  
- Manipulação limitada de strings  
- Curva de aprendizado mais íngreme para iniciantes

---

## Biblioteca Pandas

### O que é?
O Pandas é uma biblioteca open source para ciência de dados. É usado para **limpeza**, **tratamento** e **análise exploratória** de dados.

### Pontos positivos
- Sintaxe fácil de entender  
- Ampla documentação e tutoriais  
- Fácil integração com outras bibliotecas (ex: NumPy)  
- Grande comunidade no GitHub

### Pontos negativos
- Alto consumo de memória RAM com grandes volumes de dados  
- Não é ideal para Big Data (pode travar)  
- Para grandes conjuntos, recomenda-se Spark ou Dask

### Estruturas principais
- **Series** – Array unidimensional com índices para identificar registros  
- **DataFrame** – Estrutura bidimensional (tabelas com linhas e colunas)

---

# Biblioteca Selenium

### O que é?

O Selenium é uma poderosa API orientada a objetos, usada para automação de navegadores web, que ***permite realizar tarefas repetitivas de forma programática***. *Também **oferece suporte para execução de testes em várias plataformas de navegadores**.*

### Por que usar?

Selenium ***se adapta a diversos tipos de necessidades em aplicativos web***, realizando operações altamente flexíveis para localizar elementos da interface do usuário e comparar os resultados esperados e conquistados, tendo estimativas reais do comportamento da aplicação.

Sua coleção de funções está disponível para programação em ***Java, CSharp, Python, Ruby, Php, Perl e JavaScript**.*

### **Iniciando com o Selenium**

- **Pré-requisito**: Ter o Python instalado no computador.
- **Instalação do Selenium**:
    - Abra o terminal.
    - Execute o comando:
        
        ```
        
        pip install selenium
        
        ```
        

### **Utilizando o WebDriver Manager**

1. **Por que usar?**
    
    O Selenium precisa de um driver (como o do Chrome) para controlar o navegador.
    
2. **Problema antigo:**
    
    Antes era preciso baixar e configurar esse driver manualmente.
    
3. **Solução moderna:**
    
    Com o **WebDriver Manager**, esse processo é feito automaticamente.
    
4. **Como instalar:**
    
    Execute no terminal:
    
    ```
    
    pip install webdriver-manager
    
    ```
    

### **Componentes do Selenium**

- **Selenium WebDriver**: Controla navegadores reais como Chrome e Firefox de forma programada.
- **Selenium IDE**: Extensão do navegador que grava e reproduz ações, ideal para iniciantes.
- **Selenium Grid**: Permite executar testes em paralelo em diferentes máquinas e navegadores.

### **Pontos Positivos**

- Redução de erros manuais.
- Melhor aproveitamento do tempo dos testadores/desenvolvedores.
- Feedback rápido e execuções ilimitadas de testes.
- Compatível com metodologias ágeis.
- Boa documentação dos testes.

### Pontos Negativos

- Não funciona com aplicativos desktop.
- Recursos limitados para relatórios e depuração.
- Desempenho prejudicado com grandes volumes de testes.
- Curva de aprendizado elevada.
- Limitações em interações mais complexas do usuário.

### **Principais Métodos no Selenium**

| Método | Função |
| --- | --- |
| `back()` | Volta para a página anterior |
| `close()` | Fecha a aba atual |
| `execute_script()` | Executa código JavaScript |
| `forward()` | Vai para a próxima página |
| `get_window_size()` | Pega o tamanho da janela |
| `refresh()` | Recarrega a página |
| `get_screenshot_as_file()` | Salva uma captura de tela como arquivo |

### **Aplicações Reais**

- **Empresas como Amazon, Google e Netflix** usam Selenium para automatizar testes de funcionalidades web.
- Usado para simular cliques, rolagens, preenchimentos de formulário etc., como se fosse um usuário real.

---

# Biblioteca PyAutoGUI

### O que é?

O PyAutoGUI é uma biblioteca Python que permite ***automatizar tarefas na interface gráfica do computador*** (GUI).

Com ela, é possível controlar o mouse e o teclado, capturar a tela, realizar cliques, movimentos e outras interações automaticamente, reproduzindo ações que normalmente seriam feitas manualmente, mas de forma programada, possibilitando uma economia significativa de tempo.

### Como Funciona?

O PyAutoGUI transforma comandos Python em eventos enviados ao sistema operacional. Para isso, ele utiliza bibliotecas internas que acessam as APIs nativas de cada sistema operacional, funções próprias que controlam mouse e teclado. Assim, o sistema entende esses eventos como ações reais do usuário e executa normalmente nos aplicativos ativos.

### Por que usar?

O PyAutoGUI é extremamente **versátil** e **acessível** para programadores de todos os níveis, incluindo aqueles que estão apenas começando. Sua sintaxe simples e documentação detalhada tornam a curva de aprendizado suave.

### **Instalação**

- O PyAutoGUI é instalado via terminal com o comando:
    
    ```
    
    pip install pyautogui
    
    ```
    

### **Executar comandos**

- Crie e salve o código em um arquivo `.py`.
- Execute pelo terminal com:
    
    ```
    
    python nome_do_arquivo.py
    
    ```
    
- Atenção: PyAutoGUI controla mouse e teclado — cuide da posição do cursor antes de rodar scripts.

### **Configuração do ambiente**

- Dependendo de seu sistema operacional, pode ser necessário realizar algumas configurações adicionais para permitir que o PyAutoGUI interaja com o sistema de maneira eficiente.
    - Ex: no macOS, habilitar controle de acessibilidade.

### **Movimentação e Cliques do Mouse**

Uma das funcionalidades mais básicas e úteis do PyAutoGUI é a ***capacidade de mover o mouse e realizar cliques.***

### **Digitação de Texto**

O PyAutoGUI pode ser usado para ***simular a digitação de texto*** em qualquer campo de entrada. 

### **Pressionamento de Teclas**

***Simular o pressionamento de teclas*** é outra funcionalidade essencial do PyAutoGUI. 

### **Abertura e Navegação**

O PyAutoGUI também permite simular ações do teclado, como abrir programas, digitar textos e navegar por sites.

### **Cuidados e Limitações**

- PyAutoGUI:
    - **Depende de coordenadas na tela**.
    - **Não entende** elementos da interface.
    - Pode falhar com:
        - Mudanças de resolução
        - Aplicações complexas (com tecnologias avançadas)
- Testes em diferentes ambientes são importantes.

### **Aplicações reais**

1. **Automação em Sistemas Antigos (Legados)**:
    - Softwares sem APIs.
    - Ex: preenchimento de dados em sistemas bancários antigos.
2. **Testes Básicos em Aplicações Desktop**:
    - Simula interações quando o código-fonte do app não está disponível.

---

# **Biblioteca Tkinter**

- **Criador**: John Ousterhout (década de 1980).
- **Pontos Positivos**:
    - Facilidade de aprendizado e compatibilidade multiplataforma.
    - Widgets básicos prontos e suporte a temas.
    - Comunidade ativa e documentação extensa.
- **Pontos Negativos**:
    - Visual datado e widgets limitados para aplicações avançadas.
    - Layouts menos flexíveis e ferramentas de design pouco intuitivas.
- **Fundamentos Básicos**:
    - Exemplo de código: Criação de janela, botões, labels e uso de gerenciadores de layout (**`pack`**, **`grid`**, **`place`**).

  ---

  # **Biblioteca PyQt**

- **Criador**: Phil Thompson e Riverbank Computing (1998).
- **Pontos Positivos**:
    - Interfaces modernas e multiplataforma.
    - Qt Designer para criação visual de telas.
    - Widgets avançados (tabelas, gráficos) e integração com C++.
- **Pontos Negativos**:
    - Curva de aprendizado íngreme e licença comercial para uso não aberto.
    - Documentação focada em C++ e complexidade para iniciantes.
- **Funcionamento**:
    - Sistema de sinais e slots para eventos, layouts automáticos e suporte a temas.

---

# Bibliotecas Matplotlib e Seaborn

### **O Que São?**

- **Matplotlib**:
    - Biblioteca base para criação de gráficos em Python.
    - Oferece controle detalhado sobre visualizações, desde gráficos simples até complexos.
- **Seaborn**:
    - Biblioteca construída sobre o Matplotlib.
    - Simplifica a criação de gráficos com estilos elegantes e temas pré-definidos.

---

### **Diferenças**

| **Matplotlib** | **Seaborn** |
| --- | --- |
| Maior controle e personalização. | Mais fácil de usar. |
| Ideal para gráficos complexos. | Foco em visualização estatística. |
| Menos estilizado por padrão. | Temas de cor integrados e estética aprimorada. |

---

### **Integrações**

Ambas as bibliotecas são compatíveis com:

- **NumPy**: Para manipulação de arrays e álgebra linear.
- **pandas**: Para análise e manipulação de dados em DataFrames.

---

### **Exemplo Prático (Matplotlib)**


```
import matplotlib.pyplot as plt
import numpy as np

x = np.array([0, 1, 2, 3])
y = np.array([3, 8, 1, 10])

plt.subplot(1, 2, 1)
plt.title("Gráfico de Linha")
plt.plot(x, y)

plt.subplot(1, 2, 2)
plt.scatter(x, y)
plt.title("Gráfico de Dispersão")

plt.show()
```

- **Funcionalidades**: Criação de subplots, gráficos de linha/dispersão e personalização de títulos.

### **Curiosidades**

- **Matplotlib**: Criado por John D. Hunter para gráficos científicos. Usado na primeira imagem de um buraco negro.
- **Seaborn**: Nome possivelmente inspirado em um personagem da série *The West Wing*.

---
