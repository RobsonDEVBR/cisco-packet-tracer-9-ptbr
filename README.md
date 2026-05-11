<p align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/0/08/Cisco_logo_blue_2016.svg" alt="Cisco Logo" width="200"/>
</p>

<h1 align="center">Tradução PT-BR para Cisco Packet Tracer 9.0</h1>

<p align="center">
  Projeto da comunidade para traduzir 100% da interface do Cisco Packet Tracer 9.0 para Português do Brasil, mantendo os termos técnicos para estudo! 🇧🇷
</p>

---

##  Objetivo

Com o lançamento do Cisco Packet Tracer 9.0, milhares de novas frases e menus foram adicionados, deixando os antigos arquivos de tradução incompletos. Este repositório fornece um arquivo `.ptl` atualizado para traduzir o simulador para o Português.

### O Diferencial: Formato "Inglês - Português"
Sabemos que o estudo para as certificações oficiais da Cisco (CCNA, CCNP) exige proficiência com os termos em Inglês. Para evitar que a tradução prejudique o seu aprendizado, este projeto utilizou um script de automação para formatar os termos técnicos no padrão `Inglês - Português`. 

**Exemplo na interface:** `Switch - Interruptor` ou `Routing - Roteamento`. 
Assim, você usa a interface confortavelmente em português, mas continua assimilando o vocabulário das provas oficiais!

##  Como Instalar

Siga estes passos simples para aplicar a tradução no seu computador:

1. **Faça o Download**  
   Baixe o arquivo **[Traducao-Cisco-Packet-Tracer-9-PT-BR.zip](Traducao-Cisco-Packet-Tracer-9-PT-BR.zip)** deste repositório (clique no arquivo e depois no botão de download "Raw" ou no ícone de baixar).
   
2. **Extraia os arquivos**
   Descompacte o arquivo `.zip` no seu computador. Você verá um arquivo chamado `Portuguese_BR.ptl` e um arquivo de instruções `LEIA-ME.txt`.

3. **Copie para a pasta do Packet Tracer**  
   Copie o arquivo `Portuguese_BR.ptl` extraído.
   Vá até o diretório de instalação do Packet Tracer e cole o arquivo dentro da pasta `languages`.
   Geralmente o caminho padrão no Windows é:
   ```text
   C:\Program Files\Cisco Packet Tracer 9.0.0\languages
   ```
   *(Observação: O Windows pode pedir permissão de Administrador para colar o arquivo. Basta clicar em "Continuar").*

3. **Configure no Programa**
   * Abra o Cisco Packet Tracer.
   * No menu superior, vá em **Options** > **Preferences** (ou pressione `Ctrl + R`).
   * Na primeira aba (**Interface**), olhe para a parte inferior na seção **Localization**.
   * Selecione o idioma `Portuguese_BR.ptl` na lista.
   * Clique no botão **Change Language** (Mudar Idioma).

4. **Reinicie!**
   Feche o Packet Tracer e abra-o novamente. Pronto, o programa estará traduzido!
## 🤝 Um pedido: Sintam-se livres para usar e mandar para seus colegas e grupos de faculdade/cursos! Peço apenas que, ao compartilharem o arquivo, mantenham os créditos e o link desta postagem original. Deu bastante trabalho automatizar isso e o reconhecimento ajuda muito!

##  Como o projeto foi feito

O projeto foi construído realizando engenharia reversa no pacote de linguagens oficial da Cisco através das ferramentas Qt (`lconvert` e `lrelease`). 
Em seguida, foi desenvolvido um script em Python que cruzou os dados do modelo da versão 9.0 (`template.ts`) com mais de 10.300 traduções faltantes processadas via API em lote e formatadas no padrão duplo de idioma. 

##  Como Contribuir (Fase de Testes)

⚠️ **Atenção:** Como esta tradução foi gerada de forma automatizada processando mais de 10.000 frases na API, ela atualmente se encontra em fase de **Testes/Beta**. É possível que algumas frases ou contextos de rede tenham ficado com uma tradução literal ou imprecisa.

Se você encontrar algum erro e quiser ajudar a melhorar o projeto:
1. Me mande uma mensagem relatando o erro (via LinkedIn).
2. **Ou faça você mesmo:** Vá na pasta `src/` e edite o arquivo original em texto puro (`Portuguese_BR.ts`). Você pode abrir um Pull Request (PR) aqui no GitHub sugerindo a correção! Toda ajuda é super bem-vinda para deixarmos esse pacote 100% perfeito para a comunidade.

## 👨‍💻 Autor & Créditos

**Robson Silva Pereira**
* 💼 [LinkedIn](https://www.linkedin.com/in/robson-silva-pereira/)

*Aviso Legal: Este é um projeto de tradução comunitário, open-source e não oficial. O Cisco Packet Tracer é uma marca registrada da Cisco Systems, Inc. Todos os direitos do software original pertencem à empresa.*
