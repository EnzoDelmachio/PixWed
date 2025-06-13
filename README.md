## Definição de Escopo - [Versão Final]

### Tela Inicial (Público)
- PixWed: Presenteie o amor. Receba com liberdade.
- Plataforma que conecta noivos e convidados com facilidade.
- Receba o valor dos presentes diretamente via Pix.
- Sem taxas e sem compartilhar seus dados com terceiros.
- Interface simples para criar, gerenciar e compartilhar listas de presentes.
- Plataforma sem fins lucrativos.
- Botão de [Saiba Mais (Público)](#saiba-mais-público).
- Opção de ir para a [Tela de Login (Público)](#tela-de-login-público) no canto superior da tela.

### Tela de Login (Público)
- Card de login.
- Logo do site.
- Inserir login e senha.
- Opção de login via Google.
- Opção de ir para a [Tela de Cadastro (Público)](#tela-de-cadastro-público).
- Opção de ir para a [Tela 01 de Recuperação de Senha (Público)](#tela-01-de-recuperação-de-senha-público).

### Tela 01 de Recuperação de Senha (Público)
- Card de recuperação 01.
- Logo do site.
- Inserir o email cadastrado.
- Botão para submeter a requisição de recuperação.

### Tela 02 de Recuperação de Senha (Público)
- Card de recuperação 02.
- Logo do site.
- Inserir a nova senha.
- Inserir novamente a nova senha.
- Botão para submeter a mudança da senha.

### Tela de Cadastro (Público)
- Card de cadastro.
- Logo do site.
- Inserir email, senha, nomes completos do casal.
- Botão para submeter o cadastro.

### Saiba mais (Público)
- Redireciona para o portfólio de relatórios e documentação do projeto.

---

### Tela de Perfil do Casal (Casal)
- Gestão de informações pessoais.
- Chave Pix para recebimento.
- Personalização visual do perfil.
- Capa do perfil com as fotos de apresentação do casal.
- Campo para upload de 2 fotos de perfil, uma para cada membro do casal.
- Dados do evento (data, local, fotos do local).

### Tela de Gerenciamento da Lista (Casal) 
- Opção de ir para o [Modal de Criação/Edição de Presentes (Casal)](#modal-de-criaçãoedição-de-presentes-casal) para criar um novo presente.
- Visão geral de todos os presentes (em cards) com foto, nome do presente.
- Ao clicar no presente é expandido o [Modal de Criação/Edição de Presentes (Casal)](#modal-de-criaçãoedição-de-presentes-casal) mostrando os detalhes do presente e permitindo editar o presente.
- Opção de ir para o [Modal de Criação/Edição da Mensagem de Boas Vindas do Casal (Casal)](#modal-de-criaçãoedição-da-mensagem-de-boas-vindas-do-casal-casal).
- Dashboard interativo com 3 métricas-chave: total arrecadado, presentes ganhos, taxa de conversão da lista (visitas/presentes).
- Visão geral de todos os presentes (em cards) com foto, nome do presente e porcentagem do valor do presente atingida.
- Ao clicar no presente é expandido o [Modal de Criação/Edição de Presentes (Casal)](#modal-de-criaçãoedição-de-presentes-casal) mostrando os detalhes do presente e permitindo editar o presente.
- Filtros de pesquisa por nome do presente, categoria (casa, lua de mel, etc.) e faixa de preço.

### Modal de Criação/Edição de Presentes (Casal)
- Mesmo card da tela de Gerenciamento da Lista, porém maior e com `overflow: auto`.
- Formulário dinâmico para adicionar novos itens à lista ou editar itens existentes (somente para edição).
- Opção de editar o presente (componente switch para habilitar ou desabilitar) usando os campos onde já são exibidas as informações do presete.
- Campos para nome do presente, valor sugerido (R$) e descrição.
- Campo para upload de até 3 fotos para o presente.
- Informações adicionais: quem já presenteou e a mensagem deixada (somente para edição).
- Possibilidade de presente parcial (valor parcial - componente switch para habilitar ou desabilitar).
- Biblioteca de sugestões de presentes populares pré-categorizadas.
- Ao clicar em um dos presentes da biblioteca de sugestões é expandido o [Modal de Adição de Presente da Biblioteca (Casal)](#modal-de-adição-de-presente-da-biblioteca-casal).

### Modal de Criação/Edição da Mensagem de Boas Vindas do Casal (Casal)
- Gestão da mensagem de boas vindas do casal.
- Upload de fotos para serem apresentadas junto da mensagem.

### Modal de Adição de Presente da Biblioteca (Casal)
- Confirmação para adicionar na lista um presente da biblioteca de sugestões.
- Campo de valor sugerido (R$).

---

### Tela de Presentes (Convidado/Público)
- Visão geral de todos os presentes (em cards com hover animation) com foto, nome do presente e valor.
- Ao clicar no presente é aberto o [Modal de Detalhes do Presente (Convidado/Público)](#modal-de-detalhes-do-presentes-convidadopúblico).
- Mensagem de boas-vindas do casal e fotos pré-definidas para uma experiência personalizada.
- Acesso à lista via URL personalizada (ex: url/casal-ana-pedro).
- Filtros de pesquisa por nome do presente, categoria (casa, lua de mel, etc.) e faixa de preço.

### Modal de Detalhes do Presentes (Convidado/Público)
- Mesmo card da [Tela de Presentes (Convidado/Público)](#tela-de-presentes-convidadopúblico).
- Informações adicionais: descrição do presente, QR Code para presentear, campo obrigatório para o nome do convidado e campo opcional para deixar uma mensagem ao casal.

---

### Notas de Design
- O sistema deve adotar um design minimalista e moderno.
- Barra de navegação superior com logo da aplicação (não deve estar na Tela Inicial, porém em todas as outras).
- Menu expansível em formato de lista (não deve estar na Tela Inicial, porém em todas as outras).
- Itens do menu serão expansíveis no formato de sub-lista.
