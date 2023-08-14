# Como criar um projeto do Node

npm init - y

# Instalar o typescript

npm install typescript --save-dec

# Inicializar e configurar o typescript

npx tsc --init

# Formato so ts.config recomendado

"compilerOptions": {
    "target": "es2016",                                 
    "module": "commonjs",                                
    "rootDir": "./src",                                 
    "outDir": "./dist",                                   
    "esModuleInterop": true,                             
    "forceConsistentCasingInFileNames": true,            
    "strict": true,                                      
    "skipLibCheck": true                               
  }