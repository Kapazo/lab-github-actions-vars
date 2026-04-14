1.Por que a Secret aparece no log como ** e a variável aparece
normalmente?
1.R: Pois o github mascara automaticamente os secrets nos logs por segurança. evitando vazamentos de senhas, acessos ou outros dados sensíveis.

2.O Job deploy_app consegue ler a variável BUILD_VERSION criada no Job
build_app? Por quê?

2.R: Não, pois cada job é rodado em um runner diferente e as variáveis não são compartilhadas entre eles.
