Primero, lo primero: en el paradigma de objetos trabajamos con.... ¡mensajes! (¡ah, no te la esperabas!). Bueno, sí, y los mensajes se los enviamos a objetos. 

Por ejemplo, a los strings podemos enviarle el mensaje `size`, que nos da su longitud. 

```ruby
"hola mundo".size 
# => 10
```

o `include?`, que nos dice si contiene un substring

```ruby
"hola mundo".include?("mundo") 
# => true
```

A los números podemos enviarle el mensaje `even?`, que nos dice si es par:

```ruby
105.even? 
# => false
```

En general a todos podemos enviarle `to_s`, que lo convierte en string: 

```ruby
402.odd?.to_s
# => "false"
```
 
Y así. 

> Ahora te toca a vos: solamente enviando mensajes, averiguá 