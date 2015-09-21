¿Y cómo definimos nuestros propios objetos? Ruby presenta un modelo de objetos basado en clases: todo objeto es instancia de una clase, por ejemplo:


```ruby
class Espadachin
  def atacar_a(victima)
    victima.recibir_danio(nivel_ataque)
  end
  
  def nivel_ataque
    10
  end
  
  def recibir_danio(nivel_danio)
    @puntos_vida -= nivel_danio
  end
end
```


La cual instanciamos de la siguiente forma:

```ruby
dartagnan = Espadachin.new
sanjuro = Espadachin.new
dartagnan.atacar_a(sanjuro)
```

> Ahora te toca a vos: declará la clase Muralla, que no puede atacar, pero sí recibir daño: cuando lo hace solamente pierde la mitad del 

