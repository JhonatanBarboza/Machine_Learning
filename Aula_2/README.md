## Margin Boudary

na aula passada nos estudamos o algoritimo Perceptron, onde para funcionar corretamente ela deve dividir a amostra o mais no meio possivel, caso isso não aconteça podem se gerar erros com novos individuos. Por isso queremos deixar nossa decision bounday com uma certa margem de erro, de preferencia o mais simetrico pocivel.

regularização: favorecer a margin boundary o mais longe possível da decision boundary
Loos: quantos explos ficariam detro da margem ao afasta-la da decision boundary

## Função gama 

Agora veremos se um ponto foi classificado de forma correta ou não, se esta dentro ou fora da margem ele ainda sim segue a mesma formula da aula anterior 

yi(vetor theta* vetor xi+ teta0) <=0

para vermos se ele esta dentro ou fora é simples só verificaremos a distancia do ponto ate a decision boudary.

afunção gama nos da o explo corretamente e errado classificado, fora da margem e fora da margem

agoara levaremos em consideração o quanto ele esta acertando ou errando.

## Função Loos

pegamos o Perceptron e sofisticamos o problema para cebtralizar a reta.

### Hinge Loos





