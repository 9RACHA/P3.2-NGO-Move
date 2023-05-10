# P3.2-NGO-Move
Realiza o titorial Get started with NGO. 
Logo elimina o Network transform que introduciches no último paso. 
Fai que as capsulas respondan aos movementos esquerda, dereita, arriba e abaixo; 
Asegúrate de ese momento o reproduzan en rede (que o player se mova en todos os equipos). 
Non podes usar o Network transform para isto, só Networkvariables e chamadas RPC. Eses movementos terán como input as teclas que ti decidas.

Entregables:

Pequeno informe explicativo con algunhas capturas
Link ao repositorio do xogo

## Informe
Almacene la Variable de red NetworkVariable llamada Position cuyo objetivo es el de guardar la posicion del jugador.
Esta Position es fundamental para generar una posicion aleatoria mediante un [ServerRpc] o posteriormente un [ClientRpc] que generara al principio una posicion aleatoria y despues podremos generar nosotros otra posicion pulsando las flechas de direccion. Es importante recalcar que todo lo relacionado con Inputs en este caso las flechas tendran que ir integradas dentro del metodo Update ya que se va actualizando constantemente.



