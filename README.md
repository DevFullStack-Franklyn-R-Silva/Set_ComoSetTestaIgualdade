# Set_ComoSetTestaIgualdade
## Como as coleções Hash testam igualdade?
#### • Se hashCode e equals estiverem implementados:

* Primeiro hashCode. Se der igual, usa equals para confirmar.

* Lembre-se: String, Integer, Double, etc. já possuem equals e hashCode

#### • Se hashCode e equals NÃO estiverem implementados:

* Compara as referências (ponteiros) dos objetos.
