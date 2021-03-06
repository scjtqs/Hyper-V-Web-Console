# Hyper-V-Web-Console
Hyper-V Web Console - Consola para manejo de Hyper-V

![Hyper-V-Web-Console Screenshot](https://raw.githubusercontent.com/bet0x/Hyper-V-Web-Console/master/example.png)

## Uso
```
> powershell (ejecutar como administrador)
> git clone https://github.com/bet0x/Hyper-V-Web-Console.git
> cd Hyper-V-Web-Console
> go run hyper-v-web-console.go
```

Abre la siguiente dirección en tu navegador `http://localhost:8080/`.

# Requisitos & Prueba
* Microsoft Windows
* Hyper-V instalado con módulo de soporte para powershell
* Golang
* Editar el archivo config.json
* Probado en Windows 10 Pro + GoLang 1.8.1

## Características
* Información básica de las máquinas virtuales
* Iniciar VM
* Reiniciar VM
* Parar VM
* HTTP Auth básico

## Futuras características
* Puntos de chequeo
* Linux Integration Components
* Manejo de red
* ~~Usuarios~~

## Créditos
* Basado en el trabajo original de @myanote
* Boostrap alpha 4
