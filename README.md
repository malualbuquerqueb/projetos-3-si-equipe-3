# 🎭 IngressArt – Projetos 03

Este é o repositório do projeto **IngressArt**, desenvolvido na disciplina **Projetos 03**.

O objetivo é criar uma solução de **gestão de teatros na cidade do Recife**, modernizando processos internos e otimizando a experiência do público — desde a **compra de ingressos** até a **análise de dados sobre os espectadores** e **geração de relatórios** para os administradores.

<details>
<summary>👥 Equipe</summary>

Nosso time é formado por seis integrantes. Abaixo, estão seus respectivos GitHubs e contatos:

- **Bruno Oliveira**  
  GitHub: [bruno-omf](https://github.com/bruno-omf)  
  E-mail: bomf@cesar.school

- **Karoline Andrade**  
  GitHub: [kass200](https://github.com/kass200)  
  E-mail: kass@cesar.school

- **Jorge Augusto**  
  GitHub: [Jaabsolutaa](https://github.com/Jaabsolutaa)  
  E-mail: jalv@cesar.school

- **Maria Luisa**  
  GitHub: [malualbuquerqueb](https://github.com/malualbuquerqueb)  
  E-mail: mlabc@cesar.school

- **Matheus Miranda**  
  GitHub: [MatheusMiraEsc](https://github.com/MatheusMiraEsc)  
  E-mail: mme@cesar.school

- **Pedro Augusto**  
  GitHub: [pedroooojh](https://github.com/pedroooojh)  
  E-mail: pascd@cesar.school

</details>

---

<details>
<summary>🔗 Links Importantes</summary>

- **Google Drive do Projeto**  
  [Acessar Google Drive](https://drive.google.com/drive/folders/1i39c-0Pjjzu1giN-jWWBlgzjGbyWYoW_?usp=sharing)

</details>

---

<details>
<summary>📦 Entregas</summary>


<details>
<summary>📍 Entrega 1</summary>

- **Histórias de Usuário**  
  [Ver Documento](https://docs.google.com/document/d/1xR2WzLU8VZLKRwLLtpqHdbMdx1_yzDKc0HukmepcWw8/edit?usp=sharing)

- **Sketch Inicial (Figma)**  
  [Ver no Figma](https://www.figma.com/board/r7o7DKTGKAZRDjI0sXXUfe/Projetos-3?node-id=0-1&t=j7Ymv4OdVUhpAi1l-1)

- **Protótipo LO-FI**  
  [Ver no Figma](https://www.figma.com/design/4wSNGq8mUJAOu6osnInCal/LO-FI---IngressArt?node-id=0-1&t=PW0UFo2tPWoakhqY-1)

- **Screencast**  
  [Google Drive](https://drive.google.com/file/d/1qsG7LR3z1AAgocyJOQwtKVRx-g7BBCJX/view?usp=drive_link)  
  [YouTube](https://youtu.be/9tPTPO0eYSs)

</details>

<details>
<summary>📍 Entrega 2</summary>
  
- **Diagrama de Classes**  

![Class Diagram2](https://github.com/user-attachments/assets/7a84ccd0-9294-449a-a334-ac31077a0bd0)

- **Screencast das histórias**
 [Google Drive](https://drive.google.com/file/d/1QlMDrYOWScaeN313fvkxH59cj_X_r5WE/view?usp=drive_link)  
 [YouTube](https://youtu.be/Tp9b67hkByM)


</details>

<details>
<summary>📍 Entrega 3</summary>

- Início da implementação das principais funcionalidades  
- Integração entre telas e lógica de dados  
- Testes iniciais e ajustes com base no feedback  
- Apresentação de um MVP funcional  

</details>

<details>
<summary>📍 Entrega 4</summary>

- Projeto final consolidado  
- Testes completos e validação com usuários  
- Documentação e apresentação final  
- Preparação para publicação ou uso real  

</details>

</details>

---


<details>
<summary> IngressArt - Como rodar?</summary>



###  Requisitos para rodar o projeto
Requisitos:
- Java 17 ou superior
- PostgreSQL instalado
- IDE (Eclipse, VS Code etc.)

Passos:
- Clone ou baixe este repositório
- No PostgreSQL, crie o banco:
  - CREATE DATABASE ingressart;
  - Execute os scripts SQL da pasta database/ para criar as tabelas
  - Configure a conexão com o banco no arquivo ConnectionFactory.java:
  - private static final String USER = "seu_usuario";
  - private static final String PASS = "sua_senha";
 
    
### Rodar o projeto
- Compile e clique com o botão direito na App.java > Run As Java 
- O sistema será iniciado via terminal com menus de interação

---


### Fluxo de Funcionamento
Acesso Inicial
Ao iniciar o sistema, o usuário escolhe:
- Acessar como Teatro (Administrador)
- Acessar como Cliente
- Acessar sem cadastro
- Sair

Teatro (Administrador)
- Menu disponível:
- Cadastrar Peça
  - Listar Peças
  - Editar Peça
  - Deletar Peça
  - Sair
- Cadastrar Sala
- Listar Salas
- Cadastrar Sessão
- Sair

Detalhes:
- Cada peça está vinculada a uma sala e possui sessões.
- A capacidade da sessão segue a capacidade da sala.
- A edição e exclusão de peças afetam também suas sessões.

Cliente
Acesso pode ser com ou sem login.
- Sem login:
- Visualiza peças cadastradas
- Vê detalhes da peça
- Se quiser comprar ingresso, precisa se cadastrar

- Com login:
- Visualiza peças
- Compra ingresso via simulação PIX
- Recebe comprovante com código

Pode acessar a opção Meus Eventos (em construção)
</details>

---

## 📄 Licença

Este projeto está licenciado sob a [Licença MIT](LICENSE).



