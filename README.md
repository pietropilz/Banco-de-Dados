# Banco-de-Dados

O usuário do linkedin é um perfil. O perfil divide-se em perfil de pessoa e perfil de organização.
O perfil de empresa possui nome, descrição, número de funcionários. O perfil de empresa se relaciona com vagas publicadas, localização, áreas de interesse e certificações.
O perfil de usuário nome, descrição, disponibilidade, e-mail para contato. O perfil de usuário se relaciona com vagas publicadas, localização, áreas de interese, certificação e formação.
Uma vaga é publicada por um perfil de organização e um perfil de organização pode publicar diversas vagas. O perfil de pessoa pode ser candidato uma vez a cada vaga e a diversas vagas simultaneamente. As vagas possuem modalidade, carga horária, descrição, requisitos, data de postagem, data limite. As vagas estão relacionadas a um local.
A localização possui país e região. Cada perfil de pessoa pode possuir uma localização, enquanto cada perfil de organização deve possuir pelo menos uma localização. Vagas possuem uma localização. Umamesma localização pode ser atribuída a diferentes perfis e vagas. 
Áreas de interesse possuem nome e descrição. Cada perfil de pessoa e cada perfil de organização podem ter uma ou mais áreas de interesse. Cada área de interesse pode estar relacionada a diferentes perfis. 
Certificação possui nome e descrição. Cada perfil de pessoa e cada perfil de organização podem ter uma ou mais certificações. Cada certificação pode estar relacionada a diferentes perfis. 
Formação possui nome, descrição, data de início, data de fim e instituição. Cada perfil de pessoa pode ter uma ou mais formações. Cada formação pode estar relacionada a diferentes perfis de pessoa.
Um perfil pode se conectar a outros perfils, e essa conexão é simétrica
Um perfil pode publicar várias postagem
Uma postagem tem foto, descrição, hashtags, numero de comentários, numero de compartilhamentos, data de publicação, likes
Um comentário é em relação a um outro comentário ou a uma postagem, que pode ter vários comentários-filhos
Um comentário tem data, texto do comentário
um comentário é feito por um perfil, que pode fazer um ou mais comentários
Um grupo deve incluir um ou mais perfil, e um perfil pode participar de um ou mais grupos. Um grupo tem data de criação
