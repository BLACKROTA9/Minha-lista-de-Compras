MINHA LISTA DE COMPRAS — PROJETO ANDROID

Este é o projeto-fonte para gerar um APK instalável. O APK ainda precisa ser compilado no Android Studio.

REQUISITOS
- Computador Windows, macOS ou Linux
- Android Studio instalado
- Internet na primeira compilação para baixar as ferramentas Gradle/Android

COMO GERAR O APK
1. Descompacte MinhaListaDeComprasAndroid.zip.
2. Abra o Android Studio.
3. Escolha Open e selecione a pasta MinhaListaDeComprasAndroid.
4. Aguarde a sincronização do Gradle e a instalação dos componentes solicitados.
5. No menu Build, escolha Build Bundle(s) / APK(s) > Build APK(s).
6. Ao terminar, clique no link de localização do APK mostrado pelo Android Studio.
   Normalmente ele fica em app/build/outputs/apk/debug/app-debug.apk.

COMO INSTALAR NO CELULAR
1. Transfira app-debug.apk para o celular Android.
2. Toque no arquivo APK usando o app Arquivos/Downloads.
3. Se o Android pedir, autorize a instalação dessa fonte para esse arquivo.
4. Confirme Instalar e abra “Minha Lista de Compras”.

OBSERVAÇÕES
- O projeto usa um WebView local e inclui a lista HTML como recurso interno.
- A lista usa armazenamento local do WebView; desinstalar o app ou limpar os dados pode apagar os dados guardados.
- Guarde uma cópia exportada da lista antes de desinstalar ou limpar os dados.
- Para publicar na Google Play, é necessário preparar e assinar uma versão de lançamento. Este projeto, por si só, não é um APK já compilado.
