## Comandos utilizados no TypeScript

### Instalando TypeScript de forma global

```bash
npm i -g typescript
```

### Iniciar arquivo de configurações do TypeScript
```bash
tsc --init
```
- Isso deviria criar o arquivo: <b>tsconfig.json</b>

### Compilar arquivo TypeScript
```bash
tsc basico.ts
```
- Isso deviria criar o arquivo <b>basico.js</b>
- OBS: para executar um arquivo JS, basta digitar "node nome_arquivo.js"

### Executar HTML via HTTP e não via caminho absoluto do arquivo

#### Inicialiar arquivo package.json
```bash
npm init -y
```
- Isso deveria criar o arquivo <b>package.json</b>

#### Instalar Live Server
```bash
npm i -s live-server
```
- Isso deveria criar dentro do arquivo <b>package.json</b> a seguinte dependência:
```JSON
"dependencies": {
    "live-server": "^1.2.2"
}
```

### Similar ao uso do live server que monitora mudanças no código seria o uso do comando:
```bash
tsc -w
```
- Isso deveria monitorar as alterações no projeto e compilar os arquivos ".ts" com:
```
tsc nome_de_cada_arquivo.ts
```