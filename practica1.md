#PRÁCTICA Nº 1

###Carrera: Ingenieria de sistemas                        
------------------------
###Materia: tegnologías Emergentes II
--------------
###Apellidos y Nombres: Flores Calle Jorge Miguel
------------------
###C.I: 10038007 L.P.




# 1) Explique que son los sistemas empresariales

Un sistema empresarial es un sistema central de la organización, que garantiza que la información se pueda transmitir atraves de todas las funciones empresariales, y todos los niveles de gestión, para soportar la operación y administración de una empresa.

Un Sistema de Información Empresarial es un sistema que tiene un
impacto muy importante en el funcionamiento de la organización o
negocio y cuya falla traería graves consecuencias.

Normalmente que ofrece alta calidad de servicio, gestiona con
grandes volúmenes de datos, disponible de forma continua y es
capaz de soportar cualquier organización grande.

#2) describa cuales son las características mas importantes de una aplicación empresarial

- ***Acceso a bases de datos***, usualmente a bases de datos
relacionales.

- ***Operaciones transaccionales***, cumple con las propiedades
ACID.

- ***Escalables***, permiten escalabilidad vertical y horizontal.
 
- ***Disponibles***, idealmente prestan servicios de forma continua.

- ***Seguras***, no todos los usuarios acceden con la misma
funcionalidad.

- Permiten integración con otras tecnologías
 Arquitectura multicapa.


#3) Investigue y proponga cinco (5) instituciones que requerirían aplicaciones de misión crítica.
#Justifique su respuesta

En el desarrollo de aplicaciones de misión crítica se consideran:

- Plataforma tecnológica
- Alta disponibilidad
- Esca labilidad
- Seguridad
- Mantenimiento



#4) Explique cuáles son las diferencias entre la escalabilidad horizontal y escalabilidad vertical


**Escalabilidad vertical**.- se refiere a actualizaciones o modernisacion de componentes ya existentes  ,  es decir aumentar el hardware por uno más potente, como disco duro, memoria, procesador, etc. pero también puede ser la migración completa del hardware por uno más potente

![](https://www.oscarblancarteblog.com/wp-content/uploads/2017/03/escalamiento-vertical-failover.png)

**Ventajas:**

   - No implica un gran problema para las aplicaciones, pues todo el cambio es sobre el hardware
   - Es mucho más fácil de implementar que el escalamiento horizontal.
   - Puede ser una solución rápida y económica (compara con modificar el software).

 

**Desventajas:**

- El crecimiento está limitado por el hardware.
- Una falla en el servidor implica que la aplicación se detenga.
- No soporta la Alta disponibilidad.
- Hacer un upgrade del hardware al máximo pues llegar a ser muy caro, ya que las partes más nuevas suelen ser caras con respecto al rendimiento de un modelo anterior.



**Escalabilidad horizontal**.- se refiere a aumentar el numero de componentes 

![](https://www.oscarblancarteblog.com/wp-content/uploads/2017/03/escalamiento-horizontal.png)

**Ventajas:**


- El crecimiento es prácticamente infinito, podríamos agregar cuantos servidores sean necesarios.
- Es posible combinarse con el escalamiento vertical.
- Soporta la alta disponibilidad
- Si un nodo falla, los demás sigue trabajando.
- Soporta el balanceo de cargas.

 

**Desventajas:**

- Requiere de mucho mantenimiento.
- Es difícil de configurar.
- Requiere de grandes cambios en las aplicaciones (si no fueron diseñadas para trabajar en cluster).
- Requiere de una infraestructura más grande.

#5) Que es un servidor Web y que es un servidor de aplicaciones

**servidor web.-**Un servidor web o servidor HTTP es un programa informático que procesa una aplicación del lado del servidor, realizando conexiones bidireccionales o unidireccionales y síncronas o asíncronas con el cliente y generando o cediendo una respuesta en cualquier lenguaje o Aplicación del lado del cliente. El código recibido por el cliente es renderizado por un navegador web. Para la transmisión de todos estos datos suele utilizarse algún protocolo. Generalmente se usa el protocolo HTTP para estas comunicaciones, perteneciente a la capa de aplicación del modelo OSI. El término también se emplea para referirse al ordenador.

**Servidor de aplicaciones.-**Se denomina servidor de aplicaciones a un servidor en una red de computadores que ejecuta ciertas aplicaciones.

Usualmente se trata de un dispositivo de software que proporciona servicios de aplicación a las computadoras cliente. Un servidor de aplicaciones generalmente gestiona la mayor parte (o la totalidad) de las funciones de lógica de negociación y de acceso a los datos de las aplicaciones. Los principales beneficios de la aplicación de la tecnología de servidores de aplicación son la centralización y la disminución de la complejidad en el desarrollo de aplicaciones. 


#6) Con un gráfico explique cómo funciona el protocolo HTTP


![](https://img.youtube.com/vi/tN9yBV-B8Hw/0.jpg)


#7) Explique los elementos importantes de REQUEST en HTTP

- metodo HTTP (HTTP 	method ) usualmente GEST,POST.

- Recurso al que se accede (URL).
- Parámetros de FORM.
 
#8) Explique los elementos importantes de RESPONSE en HTTP

- Codigo de estado (status code): indica si la operacion fue realizada correctamente o no .
- tipo de contenido (content type):si el contenido es HTML , una imagen,un archivo PDF, etc.
- contenido : el HTML , la imagen, etc.

#9) Describa con un gráfico la arquitectura Java EE


![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAARMAAAC3CAMAAAAGjUrGAAAA8FBMVEX////n5+cAAACEhITu7u7f39/r6+twcHCJiYmdnZ2xsbHOzs7R0dHm5uaLi4v4+Pi7u7uUlJRzc3NfX196enrZ2dlWVlaAgIBkZGSkpKTExMRJSUnz8/OTk5Orq6vIyMg/Pz9QUFAyMjI6OjomJiYgICBFRUUsLCwTExMaGhq2t7YVFRWbm3RoaGo9QB49PUOlqJJLTEB5eSSHimmNj38VFRuUlY1SUlyRlmNucU5RUQuhpIGboWpqbVG5vou5uXBeXhXp6czGxnGpqUP8/+E+PzYWHBYpLSnJyaMvMCVpaTDExIFfYzzKyrOQk3eCg3w0PHUSAAAbHElEQVR4nO2dCYPquJGAhSzL933fGGi6mxfvJHskmz2TvbJn9v//m5VtfCAZMDa86ZlN9TweD/fI9odUVSqVygD8Sf4kD8vp/Vilz2os2m1d41mN/WjiQcWQscdxp5QzudSIAlFb3Jjy4aVyqgSciUljwJCCDK+4tlOg/yiATVi/BqoFPRhUpSepe3dxY/lH/ep6HGlM9IUiUt/05Zcmv2m6CzSPNzCvbUDqeZuFLZE2Hvn1lkmcuOQ20hMEorO3F565Y3I62qQxIO0NtzqsYLKzyIsi5G+5C/0dCiTuAy1qKP6UoPzA7yuQBzyAskduw8vfCgiq5Uzij03dWFyQxrCVyN9AuYLJW0RejJPwyXEhgKam+3BZR4ESMAwvDBPeCcsMWGF5ZyhI5Fvlk8Qht+F/5ip0obDoxI2IZQjxu1+SxpwPMyaNccsba/pJAfmK4wTCxLH5pUwU8qKaOZSTirQnFyG883/gTQpSjNAG8kQhIozWWKGuMdJPVjdmfnp2GMP4PRAP1of3zmVwmfqHBXlR9/mnnEQA8oEf3WPSSZo9zSQTNtkTGokzi0/zKCqCUo6BYsnWsiv0Q2DGepJ+yIlAdAVU8rlMvrBwy01hLZrjvCnFTjickrK0QJXcHTv/n+Rg3f+dyAl5L9H84RMvWnHK2DFA6YO0VOt/CeaKpl4j/H0XMn9LT5wCDRPgUwx4UzW9XZkaprlQsxQwNiFUT9BTTx44cPFCl/ikAq+Y+Nw7LWvvEWm8h9qZQH51lHNoHXSij9wyXGiO8XvEfYNSlpg7d7vZ7pzjMicLQsAdp9pXl13XI3KsrUPNxIOFsJcPoLSEgLg4s20VLU64zWzf5/SjB0/7nBi+Rc1AmFu+kXyWhgcr0u8+v+VAPHxExF6EH7sHOZ+g+29S887Yz/hf/Vqfn5mofP5GmFQ1E3Xp96FDaEYQRvpRVY3dciZb33byPXiXnYAnFyebxILyvJe/xzD1H3SNyexFIYNZEE4CtMEptEBqV9LVySX/mSd/UJuxI/g6+RaOGecDNwm2i26FNEh6vQEhVg4ZcbLeF48dbw/DCAp2QUwnuTy1BgPqUAS5wfBBw1zP6GChexbhmsbQ3OWC4wnXv3XeNDEyU6JjTRNoxC/ikYmMeKmOJRcQE+tj1p60Cgp1qY6FRQwd+aBZahXm0HvLpE8emrKVHxRY7KUHL6lhYm7ryTqSIXDEHL5FT/RPv4+UqsHpQHI44BE/XN0IAg8KJ/RiAeSO+GBjhIlHusjJa2f+RplhVYJfz0+YLaJjb9eEpUCtY/U/SKDc+5D/EA3nsEPmh31Ypuh+NmIYRvfa/gcMRsNq+iNyZ3ruiY80dkflqg819sy4ZJGnaK6kkXK7Mdmc3RZKszs9VlIeaMxdZtOmpXhEv8j3mNw5fiESxYS+EPr4TbnX6R6SgYnghPc64OU9bxh/aQ0TGeY3j98WkWKirpm9DkxCggVIGrKAQn48JEXALMBm7ABc3nMCPaqxNUwkmN08fltoJhCu6DgDEz8kLkACXC3TvUiPHFWL5cgrrjMJGWd9DRPDMW4evy00kx1c4YdR/aQCPgh1NRciTZdPQobj8TCn7jmmG1ulT64dR9HoPMr0iRkm6ZpJ87ifhIhQMUsNBYYSBWFh6CFf3GDCyOj4yR8votQRLTooO5eJ652KsycBDKF5x3f/bv8AlskqeZHd4SWgbMgkB2DyWcoTxXNKAMhToPa/MpeJQ/6kVqCht0CT3jQ+cEhfPrgxiN0TKM/kfwpMgOSboDhFfGzJHnGiga76wFI54PQkaCb0bG7MxMuRRZR/QH54oSLDPCQfH923esA38lWYFCVtu4fj6Ybck+y4m7hQYodcut/88fubmG93xDhSsCTHSDcCsDV2qtM05AOpUEAXPKaZ5CvW6tYwuWWLjcyxDCRWmmkanEouPQ7fgUp0zBABn8skNYm+5Atg1Ou2ZhrHHmh/6lhEdwUvssUz5JKJ/kFHRFbZnWtjZ5bQTML3FROgNfqE7iavscWzhGZiLM+baZhs1HmCXzvfefT4hTxbxwaZNEd08UdmogYBRzonvwlcpoc+nYmGZwjiGSbMddBMQoBFoDRrU6wdYHz79OZx8oFXe2hmrMhApD13hsmaEGvNhN/MEY9mkjOLKzQTswiVWNLSgBgpkVZ6D88BczsjvxLHqmPt7zERGT/hAVnBZMa8OLCLgjhYngAcg+4p1D2f7sYKIiVNjZpJDtx7TNba4qVMZGYljWZiBEKsOOA9NxuP7VIejilFgSSZlYQVR2JWqWgmmf/j9BN2zDL95BQDncxxQh34Pt2pHtaxqaZphoaIneWZG2b0yZr47BomjPyMbPHABNf/1VamfrdpX78Xkzs6+La8jgk+YXxCUiQVfEGAmOTnFpOn+rH8O+3rr/Jj1yxjXTBBZZqWaezLngq9VHCxg24w4ZjMw68Tj3XeaGV3csI54kQ0EyfPHYRcHqs72XNdXN1i8twYtQKLm8dvy31bnHnzlooEholpEiY2jxUrlEzCJMXXmSh0VHmdPmHc1jVMZCYHw1LHynEz8tAvLIlmT40dgsrDip5lhYC2cu79TOzOmAlCv5cH4RG6wQTHuP6v0Da8sik2BZbznx8TnBpC9d/vTif7RAhR2nUXhklri3s73JjlG3aHka8zdljpmPAxPCQcJ3KdkHf+AcoevsLklrBMmHDU19GxiLmSM5M02Qv6AOSMRbSP+2v9ZC6TTa1d/dbujC7969jiN2YdsGWCnIQGcsbib9E6JnqdLnRsmTjDeVf5bHS20JNtccdEn0TCcXqyjskGNktw7dr9qM9/Hd/eY7ZydUx23HRHOe7XMdGhVUcjo+YFVv15v77dQY5fJjZD5dd/TPzjBRMNPRh7/IAX0l/PT4GJGISHxLVtV6yF+/X/2vYf/2L3Hy41dgJdvC+62zNRL5HAPlq0igmdLPAiJrU+dZOyk9/+fVJ3HJETL5ikvDZH+LS7Z51i0muUNUwmY49bZ5Zsmdwtj2rsgkltfEXObiWo39cfXTCZL+09pw7NxL44PlNm2GJDmJWAmAoMk+t254rZWcmEHjpE0vHxmTJjLcMQ0ISyZwRdMGns13t7SSNb9hgTT54n3vmeWSTwuJ7J1PFFTBp/qc1TSkez48eYBLI5R3LxOpPy6zDxxtuNRnuQH2TCz1kHxL1/wrNMwNdhksEi7sSEQ0roo0yG5vHk20Z6JoZAI+kSZZ+da7GEyfS3tYIJinsSWG0+9ibiJ7QtfuuSDJ9vdx5mQnfiYC0TZFkFRghvyB+cxfVbWe4oDUw0yo99is82gwmqL22Dzn9PMwkpJrsujr6UCR8oUiqUFuKOGbYK3uU2ux3L5Gr/rI8rM4UZO/QOaIYJSnzfwshHdlnGeJqJ4dPjutMoC5ngyHehUaU2z2m6ahWRk5zMiX4CcjiYqmJUraI+/hnNkgRFj+pY5ICUdBInFVJQomkm8VX9v5SJZWJOteNA42Tdy4qTZPIyN8EEjyM2cEhZro/76RwjlnILmJSknyDCxPWda0xYJNBdxUQ7ka/hZGcK4sQCFR6SLc+zJpi0MaWzjPIFGibz1OKYyWaUCD7EPVgmPkhTyfDTCl3tJxNMhFVMGvOLOPI1WnyzVlyvG/cDd8yk9ZnR6P0aJqd6wma0O2UGD59lIvi+FJQmyvzSu6JP5GePnQEM7ZvQTBrJJ/NPFjBp9m1GsHFQhD51Z9ru1CYHX7c7myONpNN2a5jgKR6TTKbXRh9nYsH37XZ7gAfyuv3s1dMy/6SimXTXeGbiB9egXI9RY7W4AuVl/USc1IkLmdCGh/LZcA7dqXisGMAMX2UiR5j3NDIF4kc+7CST6TwligluF87oZdkRE4/yADsF8Bzfvtd25/Ud9O//+Ss3EMdcRFF0j456fc0LnyIkV1JW5PKGextf0sx1wEsmWFGQmSk4trKLETpmQvf2cBUTAUrWWSRr6Cb9OiBO/4uDZSL0QVU3KRMuuL42utFqJlEpeZmf8uFhPZNcjiWF04KTYl/YkIHJnmbyoa5holzECgYfyPK6SDxKFeV//vyH7fG4rX9cVSnSwali14tzwSrMMLN4PUu38u42k8k8JYaJmkUeErNIvzCfPROmm3SmYmlMqelmbb59OnQTkOlDSnjtSOed1P8YpYvT+SdkxmMWmDdND6saLsxx6tbcPKVLJkjOkVo7xrmpXXzeM2ECD51GqZlUeE70HFdjJk2zzqFRJKMLxMp47wCZcNUv9bvLTQWKNqFPcG+OKb24wBZjybWKIpO5TeBd07ETXpbfMQH2TJkRo74QTrAzcHRdDUCXrUS3Iq9AYfJymX7iyQXGhexhhTrHSJ+wTMyeyWxh8pRu16lsxhQZZDZ5FzO1qtp1wDnC7kFgZEKfnLsd7fPcsjvntdZX5oLqThiApCKD9CNkd6zXTPxwxrpS6C9hck1GTBSayXlEvpJJ4xc6QJHBVO2hgt2/fF3MVzCh/diu7tgrmciOE4CszoyYqj1UJIE7V4LjjDylx5m4l0y6hdZVTFbtQ69LxsyXi//TedIcEMBay0mwCT4KfebGKiaHNfUKVsiz5sVArwNJ5zylsP+Cf7y6FisEMXU129jjrGVvccSEbwZh2wmH4O66PCUmr+DHkpoJnE6Noufmuznx2PlyX8eqmTVHskdszhypmVwLSVGCv3eeUmbO2jCskPlOJD0g95a0vnie0hzZEAfY1/jZ4l06ONP6ZLYweUryzeO35b4+Gefbk3sf3dZFuLWOnzxS/8G4ZPLTqqc0MEGpJP013HfyYUfSEPSmmMR+7/rnCKSs5qaYTPsns4W659S/t+f6ltz3T/o4G078N6EK+jhbUAnvfsLjSSY5X9efzjHwTn6qRb6BSW+WR2goJs/Nt3/4+IXc92O7fHsb+iKbbx9+OniSSV2nRFJFXvJsT4qFVFcisPUGrUEzYeTrMGHlvJahf7uSR70T0GQ/SUVQBS6IdTuJjLpUT9gU4urk58BkTr79mMlWNwBfhbwjhtjyII4cDUBnUBqvZfLUmjCs9LnlV/ZlhNspJpMy2nVBM5mOs82WOTk50J8lkIk9snG2fg+CHwZsvv1fOrv5TMa66rvbYsOeN3maE4/tx46QvJW6OOhZkfvlX/zqz5zpsXNXKCbP3V98P0/p+iR7vJbRPryljduPzzBeQ7ffd7utUNXyi9+S9xV3sYa+gsnr6yktYdIWY2zXd8alNJh8e78Jqfoum2+/iAk/iuuOB+5XYAJH11CO+t4DuRaLmAQjR84eLQV8ASYmdIf14l0yaJXHmFj+rA0hpdQFuQ0o4eF6qNytpUyMiq2Vuj7/ZJhsP8Zk/vrOmYl47byvzhnuJrB04sbARNtOLbMuYDJzHVDvmHCXp/14CpOp2ssUE09VPfKKefWy9sCtXNDeE3wtE2bhrp8LrtInE/WUqBy/o8jlGPmpEJC/p5m49LWV3aB6KpM+F7Rjwuxpes5+wInjdC7ohteanGF+cyUX1KAvbRjZC5j0I/VirJJ/oC6RumfCnrczPS9mUgZ2VOcM23ZwhUnJXtuCXNAzE8y1dZRMszjhfuEbmzHKlHOSbMckYk+7M74LEx9tUECYVBpyppnQOxDWMEGcGSBVilEueyqKZcRLMsYS73koNhEfyWhgwgxZ+JT9gNpEPaVLJjgTqkgKFZRX4cXovplHTeWCzmaCVV3LPOLrFLJ8itQslzfmMeVMN5cLKTJjOyc6rWOC2fN2VvTFtrjOFcZtzvA1JhJ9af1zDB5n8lYdVEnJT7Js5rGEVVnYGqVR1B/EUiGp+sCETcs9dN/FGiYFjJnjj/tsJn1tvTV7lAlyvdQL8m3A56SfaFzlHYT31CyjXOZd24stRRwxYfYDPsfuTNT5e5xJSu/f6Zt7WJ/UWb3IitG5Xl3dQ9v3uCvGNLI72u7aeb/AfIfSsqNc0CX+CVa8Wyce+bHZ5XmHR4l8ASYelPpto8V+9FSUu/HY45TPdmeld2Aiw2MVhmEl1C+7b5d7mhYzoQNUC2MF76NrGD+L4cxE/Cs28tjIe3Xdj72+L6NnAs7LmE1GUfCkOjkqVJjjhMmcNd6JmFK7vsPGlDboF3/zG2Z9hxPDMmrvcooJPuW1NmlSFS9N3ohJ+3Sbdh0wHJ336ba4HPZP35CiZOKxbb2CcfShXwfU/vk3b0LljtYBK8E/eugWkwjJbiwhLd+4Ippmghob0caox9Wy1tVT8tjj8/ZbRtG89eI+316Sfvm7H7ZnCSPJQn2+/YZlgmsmqmQVkqBhc3uFSSvs46trJod5JUt2KZ2T89x6Ssxqd3Ya9vGqqhr3G1/jNtX8LIVAM8GFakZeFkhq5qeRtLvJhJWFuVvT8uQ1L6/baRCNXi+k/ahgmJz23KbY+hG24tQJ90uYPJ7jN0oBGKVWPpmJHMqgqMtctK4D+zzNIZGCHjtEr7b7EGsVe03HXj0vuy9jDpPWPMRdC2d5LhNPAiriU02K9s2Jmt3AJ3K2WNqAgpzLE6VmPUKKFsUez3Il7/FiFu+ixkfe0LvfxkykxpqbjYGP357DhK3PFvknECm6uvGbvdG1oTqZEl+YkQm0KMdkVmfoXiQp/Bomx/v5schHWJI8BcV8bI1rDIyYpP7RPJ1MGwrmydSHNp+bp4R40mDubUSvTUrWydiJ7AzJqhKnki3zUWqlIrCBmK9h4t/fv0OYIDPhg0LfeHkwOjJiQoUy+zW059Z7NCRfArnqVMiWau/K8h3X4ELN0LeFuiUOr5SQ405qheZ8JpjVJ/fy7bFp+GnsHpBtZptM4KaZWNSM8in59mxd0Cui5jmzxEuYuLNrBz2oY9HRj4j1ghvV9tRv/hUmdOQhOTf2yn0ZI/HY0xAmp0qYI5X5sN1py8vUlqw2ZtP7RtnqTOeL/E5MJuShZ4G9wj9hw7vfYZ/XbRFmVX0/136/NHDTdcsfZDJRxOUp+wGZr29TzJNHzsrKvb0qF9Unzt4J+k5MJurbZ/Omk2seond3f7EnlDlRJ3VUk/xRRVxrle4hAsPYsRkkw978+XL/OQiWOo7FpINQIZrbG07vys196JhTjRNOKwXlQozkWESxa1hvCqaYsPvQz3G7VUzY52UMtdyJuv8XMejEzVM0crG1lUwYuegn2C3NNIyTtOJdM1N1vjq52jlb+ZYtfj839pJcUHJmT6l2/7rvd0EGb9uDpfDoezDBJx4kRhlJaYWJz6aK/FGKJ8YOnc3yHJ+NlS72KB6SUhxHH0XRLXfEkXoOk9v1TzS7jDHv+2mgacFGtVDuS+i9oMcO7ds/Z48k+5ymlokW7t2JcCznflhDvv0je5qsy6r808/zouxO7bG1DzpqdC1ixw5O9nkU5RUM8ygPhkj1Kibs87waJjjaXVvLgF5fJ8eZVTmiFWpP07P2jWZNrKDNU4qHBbRVtZev5Azj3LmyXVHcD0xW5MdOPx9wQZytjSmduhYGJstrL7PPBzwzgRXzZAgigV5Clgkd+m8YND9XmUw/RzKZt5nOHdesG1pIBx21tE6O0t8PEFkmvvOeNPuZBhXL6e4//JW9Y5hYVWYAKtZt1JGE8Wez9mVcGa6MGC/KGXZH6Qnj5++d9Uko6sdtvW+BayvU/y15+3c//CDoW5YJSjlgAcnnHdKTN0kKOJ+XJchHUv1098qczWS2fI886lFH6ZjUPaOe5u93jfx9HRSoy9tPMNHq53J7pD+3j+h2CnljBGQi7ICwfgp5pk0weWq+/WanMccXMKHqzA+XODDpxox4MYRYJhmKTXL/fMRX56eNe5IXALtmwoHAmGLy3OdcP6nOMDV9GhazaSa03WGZxA4ZHZHn5OCDNJOWwCQfyMDhI8CTGxUaz6RnkjYwWls87ixfME+p/9oeZzII/ajUkQz7Mprs5KKxd89aQ5+Rp4Tu114uaCZ9TYg1TG6IQeVaNOKOoLw4F/R4rr0sXK+9zEyy+5KaL2YSQ6d/Eou+HeVwvpjJ/drLE7m73Vf2YiZU7taw4fO1eUozai/fy6Oey2TDiXOEkzomOJk+68o8pY/JPKXxrd+vvcyokyHb7iEmSsZ7M4QvOyZMZKzva6+1xU3tZe527eUDfW3furM8xkS6UOLXhIzmMxOOPu+uO++qPKU3Nk/p8drLTMj7sqbuy5iw/bPbMrlKn9ARqkX+CTN4+uZeyuRFexCmji/wY6kyo8OEZymTNt1xVE9mikk2weS77FWZxSSA77tO9h90HvXjTHCWISyjfl8ZlkdQbo2dp+xpKtjji+bFo2oC5ZDivZAJcotYT8u0wJjHm7pMd7nBo+c9d0yYOUXSBZ7WMDEn6iktYSI10ya+aWxcemchk/pRF+SlTCM3T/d2VHzksds9G2JgwtjiPu70BebFwGvMVxuPHQfEzkz212LUH1eZaOTFN96EreED33CAL0CGCbOc2Z93VT2lBDHHF9VebuTzSl0L/lhOIzm47W1STLCVRxbpJWUqymb9t1EWUv9MohET6jlNz9lzPXl8ce3l688v/sff+Q615iUK2x1Gk0yITpURjsmPJpvN33GRyjKjTwCGep957IXJMGi/fu0gcpO/N8vPtx+GANvn4Ztu9n7xdVvc528O2zRGTEA4Uof2qMbFT4FJkwOc/pPTJ9UYF+GYhX5sF1NqZVxcaBUTui70k5lk3uWa0JBrcSkCy+ScLoK6fOpJJq2o4TPrKUXQunn8ttBMTgH9G6ZzKwVryMWKGCZYQlEYI1kQ3NQSqtEhlslPq7bhA0IxQU4hY5sPyOBDVOY8wyR4bj0l/c7xm0Iz8T+v1V72VA0YdQIo8tQ2kLWpPxz/CsMEIU/EouByqR+40a1+Apj6gV9Hx7J5Sp3sZIlXq0gFliVLwI+BBoGZ52Ntdml31NRBPIcQp/A8qsuo3uonrHwdJtfFwWahykBPpQL7wBHJpAJkvDZWjRdMUMJl3ocYYM7msjQRx2VGfi5MdpEDCBMxlfToCKpYsYM6C2c82bocO2Sw8aqqbuoX3JalucFkMk9pttD3LLD1lObL/TylTipgxqpEqFhqaoNQMTMBSJt0nLJF253z41QaV+1yxw3DRN7SUL6O3WHzlDoxgcajTK6LduspOAG53kphXSj4RT5bK8+1xTmMbh6/La+0xY8wiSbzlGYLfc/0I19WMeGSq4PnvqxgAjDd2BfSsWseDUGYRPOSxn4mdmeGCEA9zCvSuvvKTLhnMnkobfguk0ee8HJvz3Uxa6dVJyvUByM7e/55K+5OY2Y5vzV7v26nzOvk/wCkerEkTNwexgAAAABJRU5ErkJggg==)





#10) Explique cuáles son los contenedores, componentes y servicios de Java EE

**Cntenedores.-** Un contenedor es un entorno de ejecución que provee al componente una serie de servicios.
 Java EE define los siguientes tipos de contenedores:

- Contenedor web
- Contenedor de negocio(o de EJBs)

**Componentes.-**Un componente es una unidad de software que forma parte de una aplicación.

Java EE define los siguientes tipos de componentes:

- Componente cliente: Cliente AWT, Swing, Applet y
navegador Web
- Componente web: Servlet, JSP y JSF
- Componente de negocio: EJB
- Cada tipo cubre necesidades concretas y se basan en APIs
especificas


**Servicios.-** Son los servicios que deben ofrecer los contenedores Java EE.

Java EE define los siguientes servicios:

- De directorio: para la indexación y búsqueda de
componentes y recursos
- De despliegue: para poder personalizar los componentes y
recursos
- De transaccionalidad: para poder ejecutar distintas acciones
en una misma unidad transaccional
- De seguridad: para poder autenticar y autorizar a los
usuarios de la aplicación
- De acceso a datos: para facilitar el acceso a Bases de Datos
- De conectividad: para poder acceder fácilmente a distintos
EIS
- De mensajería: para poder comunicarse con otros
componentes, aplicaciones o EIS

#11) Investigue los métodos más utilizados de las clases HttpServlet, HttpServletRequest y HttpServletResponse, y para cada uno de los métodos muestre un ejemplo.

**public abstract interface Servlet:** Todos los servlets implementan este interfaz directamente o extendiendo una clase que lo implemente como HttpServlet. Entre sus métodos están:

- **init(ServletConfig config):** Es el método utilizado para crear una nueva instancia del servlet (análogo al constructor). Ver el ciclo de vida. Este método puede ser sobreescrito para realizar tareas como crear una conexión a una BD que se mantendrá mientras el servlet se mantenga cargado y puede ser utilizada por cada petición. ServletConfig contiene los parámetros de inicialización que entrega el servidor al servlet.
   
- **getServletConfig():** Retorna la configuración dada para la inicialización del servlet.
   
- **service(ServletRequest req, ServletResponse res):** Este método es el que se llama cuando se recibe una petición de un cliente y en su implementación normal para HTTP verifica el tipo de solicitud GET, POST, etc. y la redirige a los métodos respectivos. En general no es necesario reimplementar este método.
   
- **destroy():** Este método es llamado por el servidor para indicar que el servlet será destruido. Es llamado sólo una vez y uno debe encargarse de esperar por posibles peticiones en curso.


---------------------------------------------------------
**public abstract interface ServletRequest:** Permite obtener información del cliente que no depende del protocolo, por ejemplo:

- getRemoteAddr(): Retorna la IP del cliente.
- getParameter(String name): Retorna el valor del parámetro name dado por el cliente.
- getInputStream(): Sirve para crear un canal de comunicación para obtener dados binarios.

**public abstract interface HttpServletRequest extends ServletRequest:** Permite obtener del cliente la información que es dependiente del protocolo, en este caso HTTP. Entre sus métodos están:

- getHeader(String name): Permite obtener el valor de los Headers de HTTP con que fue llamado el servlet.
- getCookies(): Retorna un arreglo que contiene todas las cookies que el cliente envía al servlet.
- getSession(): Retorna la sesión en la cual se encuentra el cliente.

--------------------------------------------------------

**public abstract interface ServletResponse:** Define un objeto para permitir a un servlet enviar una respuesta al cliente.

- setContentType(String type): Permite definir el tipo de respuesta que se le dará al cliente. Si se retornará una página web deberá ser text/html.
- getWriter(): Retorna un objeto Writer para poder enviar respuestas de texto.
- getOutputStream(): Retorna un objeto ServletOutputStream que permite enviar respuestas binarias al cliente.

**public abstract interface HttpServletResponse extends ServletResponse:** Permite enviar al cliente respuestas específicas del protocolo HTTP.

- addCookie(Cookie cookie): Para definir nuevas cookies en el cliente.
- setHeader(String name, String value): Para definir un header HTTP a enviar al cliente.
- sendRedirect(String location): Envía un mensaje al cliente para redireccionar la respuesta a la dirección señalada.
