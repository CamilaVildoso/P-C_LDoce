#  <p align="center">🧁 Sistema de Pedidos da Padaria & Confeitaria L'Doce 🧁
<p align="center">Este é um sistema simple em Java para gerenciar pedidos de uma padaria e confeitaria fictícia chamada L'Doce. O programa permite criar, listar, buscar, atualizar e apagar pedidos de produtos entre duas seções: padaria e confeitaria.

<p align= "center">
<img src="https://github.com/CamilaVildoso/P-C_LDoce/assets/156922629/5a849a64-0c81-431f-8c71-bdcca24523e5" alt="Descripción de la imagen" width="600">
</p>

## 📋 Funcionalidades Implementadas
- **Criar Pedido Online**: Permite que o usuário insira os dados do cliente, escolha o setor (padaria ou confeitaria), selecione produtos específicos e configure opções como tipo de sacola ou produto fit.
- **Listar Produtos**: Mostra todos os produtos disponíveis no sistema.
- **Buscar Produto por Número**: Permite buscar um produto específico pelo número.
- **Atualizar Pedido**: Permite atualizar dados de um pedido existente, como nome do cliente, tipo de sacola ou se o produto é fit.
- **Apagar Pedido**: Remove um pedido específico do sistema.

## 💻 Funcionamento
O programa usa uma interface simple de linha de comando para interação com o usuário. Utiliza o padrão de projeto MVC (Model-View-Controller), onde:

- **Model**: Representado pelas classes Pedido, pedidoPadaria e pedidoConfiteria, que modelam os dados dos pedidos.
- **Controller**: Representado pela classe ProjetoController, que controla a lógica de negócio e interação com o usuário.
- **View**: Implementada no método main() da classe Menu2, onde ocorre a interação direta com o usuário via terminal.
  
## 📍 Requisitos
Para executar este programa, é necessário ter o Java JDK instalado na sua máquina. Certifique-se de ter configurado corretamente as variáveis de ambiente para o Java.
