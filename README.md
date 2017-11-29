# Criar um aplicativo de consulta a API de Filmes #

Criar um aplicativo para consultar a API de Filmes e trazer os filmes enviados pelo endpoint. Seguem abaixo telas como guia:

![tela1](https://user-images.githubusercontent.com/7905193/33221593-75c45b4e-d12f-11e7-833c-cc4acbd5ef0e.png)
![tela2](https://user-images.githubusercontent.com/7905193/33221600-85b668ee-d12f-11e7-95fa-8f66bd47f6ab.png)

### **O aplicativo deve contemplar** ###

- __Uma lista de filmes__. Exemplo de chamada na API: `https://desafio-android-pitang.herokuapp.com/movies/list?page=0&size=3`.
    * Paginação na tela de lista, com scroll infinito (incrementando o parâmetro `page`).
    * Cada filme deve exibir Nome do filme e Foto do filme.
    * Ao clicar em um item da lista, deve levar ao detalhe do filme.
- __Detalhes de um filme__. Exemplo de chamada na API: `https://desafio-android-pitang.herokuapp.com/movies/detail/59e8ec97f36d280364369ca1`.
    * O item de detalhe deve exibir Nome, Foto e Descrição do filme.

### **Essencial** ##
* IDE Utilizada deve ser o Android Studio na versão mais atual
* O sistema de build e gerenciamento de dependêcias deve ser o Gradle
* Deve ser usada uma biblioteca para Mapeamento/Parser de JSON
* Os guidelines UX e UI devem ser do Material Design

### **Desejável** ###

* Bibliotecas de terceiros para reduzir o boilerplate
* Arquitetura MVP
* Cache de imagens e da API

### **Sugestões** ###

Nesta seção sugerimos algumas bibliotecas para o uso, mas fique à vontade para escolher outras que não estiverem na lista.

* Butterknife
* Retrofit
* Glide
* Dagger

### **OBS** ###

A foto das telas de mockup são só um guia, fique a vontade para usar o padrão de usabilidade da sua escolha.

### **Etapas para submissão** ###

O canditador ao finalizar a implementação deverá enviar um pull request para o repositório em questão.

Segue o passo-a-passo:

1. Fazer fork do respositório
2. Implementar seu projeto no fork realizado.
3. Comitar e subir todas as alteraçes para o fork criado por você.
4. Enviar um pull request pelo Github.

O fork deverá ser público para inspeção do código.

### **Observações** ###

Não fazer push para este repositório.
