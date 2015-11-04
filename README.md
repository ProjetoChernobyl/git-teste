# Testar comandos do Github
Repositório para testar comandos do git


### Comandos para o terminal

### Comandos passo a passo
```
git clone https://github.com/ProjetoChernobyl/git-teste.git   
git status   
git add "nome_do_arquivo"   
git commit -m "meu arquivo adicionado"   
git push
```

- Crie uma pasta com o nome `Git`
- Digite:
```
git clone https://github.com/ProjetoChernobyl/git-teste.git
```
- Feito isso você terá uma pasta com o nome `git-teste` (IMPORTANTE: ENTRE NESSA PASTA)
- você já tem um repositório configurado!
para verificar o estado do repositório digite:
```
git status
```
- Você acabou de clonar e não tem nada novo nele, crie um arquivo novo na pasta.
- Verifique o estado dele agora digitando novamente:
```
git status
```
- Você tem um arquivo novo (o que você acabou de criar), para adicioná-lo ao git digite:
```
git add .
```
ou
```
git add "nome_do_arquivo"
```
- Verifique as mudanças com 
```
git status
```
   - Ele está verde significa que o git está rastreando ele a partir de agora
- Vamos salvar esse arquivo (commitar)
digite
```
git commit -m "meu arquivo adicionado"
```
- Tudo certo mas isso está salvo no seu hd, vamos enviar para o site do git assim ele ficará disponível para toda a equipe
```
git push
```
 - Digite o usuário e a senha e vá ao atualize a página do git para ver sua contribuição.
   















