# O Problema XY

##TL;DR

## O que é?

O problema XY diz respeito sobre sua tentativa _de solução_ ao invés de seu _problema_ real. Isso leva a uma enorme perda de tempo e energia, tanto por parte das pessoas que pedem ajuda quanto por parte das pessoas que prestam ajuda.

*   O usuário quer fazer X.
*   O usuário não sabe como fazer X, mas acha que pode encontrar uma solução se conseguir fazer Y.
*   O usuário também não sabe fazer Y.
*   O usuário pede ajuda com Y.
*   Outros tentam ajudar o usuário com Y, mas ficam confusos porque Y parece um problema estranho para se querer resolver.
*   Depois de muita interação e perda de tempo, finalmente fica claro que o usuário realmente quer ajuda com X, e que Y nem era uma solução adequada para X.

O problema ocorre quando as pessoas ficam presas no que acreditam ser a solução e não conseguem dar um passo atrás e explicar o problema por completo.

## O que fazer sobre isso?

1.  Sempre inclua informações sobre um quadro mais amplo junto com qualquer tentativa de solução.
2.  Se alguém pedir mais informações, forneça detalhes.
3.  Se houver outras soluções que você já descartou, compartilhe por que você as descartou. Isso fornece mais informações sobre seus requisitos.

Lembre-se de que, se suas teorias de diagnóstico fossem precisas, você não estaria pedindo ajuda, certo?

## Exemplos

### Exemplo 1

n00b na verdade não quer os últimos 3 caracteres em um nome de arquivo, ele quer as extensões de arquivo, então por que pedir os últimos 3 caracteres?

```text
<n00b> Como posso ecoar os últimos três caracteres em um nome de arquivo?  
<feline> Se estiverem em uma variável: echo ${foo: -3}  
<feline> Por que 3 caracteres? O que você realmente quer?  
<feline> Você quer a extensão?  
<n00b> Sim.  
<feline> Não há garantia de que cada nome de arquivo terá uma extensão de três letras,  
<feline> então pegar cegamente três caracteres não resolve o problema.  
<feline> echo ${foo##\*.}
```

### Exemplo 2

Se Ângela tivesse acabado de começar explicando que deseja impedir que outras pessoas detectassem seu sistema operacional, essa discussão poderia ter sido muito mais curta e produtiva.

```text
Angela: 'nmap -O -A 127.0.0.1' retorna algumas linhas começando com 'OS:'. Como mudar isso?  
Obama: Procure no código-fonte do nmap, descubra como ele descobre a parte do Linux e, em seguida, reescreva sua pilha TCP/IP para não operar de uma maneira que o nmap possa detectar.  
Angela: Sim, mas não sei nada sobre a API do sistema linux.  
Obama: Bem, a impressão digital do nmap é baseada na maneira como a pilha TCP/IP funciona, não há outra maneira real, exceto reescrever as partes apropriadas dessa pilha.  
Ângela: Eu realmente preciso evitar essas mensagens. O iptables pode fazer isso funcionar?  
Obama: Bem, não use detecção de sistema operacional ou verificação de versão  
Angela: quero evitar que outras pessoas saibam o tipo do meu sistema operacional  
```
  
Fonte: [https://xyproblem.info/](https://xyproblem.info/)