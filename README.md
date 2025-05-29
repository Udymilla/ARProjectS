# ARFoundation Notebook Project

Este projeto foi desenvolvido com Unity 6.1 utilizando a tecnologia AR Foundation para exibir um modelo 3D de notebook ao detectar um QR Code como imagem-alvo.

## Funcionalidades
- Utiliza AR Foundation para rastreamento de imagem.
- Instancia o modelo 3D somente ao detectar a imagem-alvo.
- O modelo é um notebook low poly com texturas aplicadas.
- Aplicação projetada para rodar em dispositivos Android com suporte a ARCore.

## Estrutura do Projeto
- `Assets/Models`: Contém o modelo 3D `.obj` e as texturas.
- `Assets/Scripts`: Contém o script responsável por instanciar o modelo.
- `Assets/Scenes`: Contém a cena principal `SampleScene.unity`.
- `Assets/Settings`: Contém configurações de build.

## Requisitos
- Unity 6.1 ou superior
- Android SDK com nível mínimo 29
- ARCore instalado no dispositivo
- Dispositivo compatível com AR (com suporte a ARCore)

## Instruções de Uso
1. Abra o projeto no Unity.
2. Conecte um dispositivo Android via USB.
3. Compile para Android usando **Build and Run**.
4. Aponte a câmera para o QR Code configurado.
5. O modelo do notebook aparecerá sobre a imagem detectada.

## Observações
- Certifique-se de que o QR Code usado está presente na `XR Reference Image Library`.
- O modelo não deve estar presente na cena por padrão. Ele será instanciado dinamicamente.

## Licença
Este projeto é de uso educacional e experimental.
