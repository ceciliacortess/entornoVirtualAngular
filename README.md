# UD6_T6.Entorno Virtual Node.js
## Actividad de la asignatura Desarrollo Web en Entorno Cliente

### 1. Instalar nvm (Node Version Manager)
```
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.7/install.sh | bash
```
![1](https://github.com/ceciliacortess/entornoVirtualAngular/assets/131865373/58e425b1-bfab-44e7-afe2-55dc17e71d97)

```
export NVM_DIR="$([ -z "${XDG_CONFIG_HOME-}" ] && printf %s "${HOME}/.nvm" || printf %s "${XDG_CONFIG_HOME}/nvm")"
[ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh" # This loads nvm
```
![2](https://github.com/ceciliacortess/entornoVirtualAngular/assets/131865373/b8412133-2a3b-4c2c-bfa9-a1f01a788e69)

![3](https://github.com/ceciliacortess/entornoVirtualAngular/assets/131865373/f27fbe78-8fab-434f-a70d-e082f3ddd9a0)


### 2. Verificar la instalación
```
command -v nvm
```
![4](https://github.com/ceciliacortess/entornoVirtualAngular/assets/131865373/0d067e88-6b3f-4c81-9071-b60e5bed90c7)

```
nvm -v
```
![5](https://github.com/ceciliacortess/entornoVirtualAngular/assets/131865373/67d2d102-3ac6-4060-b0fd-63512ae0d3db)

### 3. Crear el entorno
#### Instalar la versión de Angular correspondiente (en este caso es la versión 14):
```
nvm install v14.15.5 --alias angular-v14
```
![6](https://github.com/ceciliacortess/entornoVirtualAngular/assets/131865373/f09d19fa-bec7-4a21-8676-f20ccc0ad769)

#### Activar el entorno virtual creado:
```
nvm use 14
```
![8](https://github.com/ceciliacortess/entornoVirtualAngular/assets/131865373/aad66351-d463-4858-95da-33afcd423f5a)

### 4. Instalar versión de Angular
```
npm install -g @angular/cli@14
```
![9](https://github.com/ceciliacortess/entornoVirtualAngular/assets/131865373/fc97b2ff-eec9-440c-b95d-a3f6a3c45fb0)

### 5. Listar las versiones descargadas
```
nvm list
```
![10](https://github.com/ceciliacortess/entornoVirtualAngular/assets/131865373/4c0791dc-5c0b-49ac-bec4-df7c2520bf6a)

