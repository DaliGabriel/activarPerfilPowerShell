# ActivarPerfilPowerShell
Pasos para activar el perfil de power shell y usar comandos personalizados para ahorrar tiempo y poder ejecutar scripst de powershell
<br>
<h1>Crear Perfil de Power Shell</h1>

```
New-Item -Path $profile -Type File -Force
```

<h1>Permitir ejecucion de power shell scripts</h1>

```
Set-ExecutionPolicy RemoteSigned
```

<h1>Editar el perfil creado con el ide de power shell</h1>

```
ise $profile
```
