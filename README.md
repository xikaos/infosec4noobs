# Infosec4Noobs

## Objetivo
O objetivo deste repositório é introduzir o tema Segurança da Informação apresentando os conceitos básicos, relacionando-os com temas específicos de sistemas de informação e desenvolvimento de software.

## Segurança
O que vem na cabeça quando falamos sobre segurança? Muitas pessoas podem associar o conceito com imunidade ou invulnerabilidade a situações adversas em um determinado contexto. O conceito de segurança é aplicado em diversas áreas como segurança do trabalho, segurança financeira ou segurança nacional, e o fato é que todos eles tem algo em comum: riscos.

Riscos são a chance e o impacto de alguma merda acontecer, seja com uma pessoa ou uma empresa. O papel da segurança é identificar esses riscos e as formas de evitar que eles venham a acontecer ou caso aconteçam, tenham um impacto menor na vida ou nos negócios. Podemos considerar algo seguro quando após implantadas as formas de diminuir a ocorrência e/ou impacto dos riscos, esses sejam considerados como aceitáveis dentro da realidade pessoal ou empresarial.

## Segurança no Contexto da Informação
Quando falamos sobre informação, nos referimos a qualquer tipo de informação e qualquer meio que ela possa estar presente: numa folha de papel, num CD-ROM ou no disco rígido do seu computador. Com a difusão imensa dos Sistemas de Informação, é muito comum achar que Segurança da Informação está associada apenas a sistemas. **Errado!** Segurança da Informação trata de formas de proteger a informação de acordo com o meio em que ela se encontra (físico/digital) e no contexto em que se encontra, o que significa entender quais são os riscos associados a informação durante sua utilização (processamento), transmissão e armazenamento. 

## A Tríplice Sagrada
Existem três aspectos básicos que precisam estar garantidos para que uma informação possa ser considerada **segura**.

### Confidencialidade
Confidencialidade trata de garantir que a informação não pode ser acessada ou visualizada por terceiros (não autorizados). Isso significa torna-la legível apenas para as partes que estão se comunicando ou que precisam acessar a informação. Ataques contra a confidencialidade envolvem a interceptação da comunicação como o famigerado Man in The Middle.

### Integridade
Integridade trata de garantir que a informação está em seu estado original e é confiável. Isso significa garantir que ela não sofreu alteração e não foi corrompida durante o processamento, armazenamento ou transmissão. Ataques contra a integridade envolvem a adulteração ou corrupção da informação.

### Disponibilidade
Disponibilidade trata de garantir que a informação está a disposição de quem necessita dela, o que significa garantir que ela esteja acessível quando necessária. A forma mais conhecida de comprometer a disponibilidade de uma informação ou um sistema é o ataque DoS (ou sua versão distribuída, o DDoS).

## Controles
Para evitar ou reduzir o impacto do comprometimento de alguns dos itens da tríplice sagrada existem controles, que são aplicados de acordo com o aspecto que se visa proteger.

### Confidencialidade
O uso de criptografia é a forma mais efetiva de garantir que a informação seja acessada apenas por terceiros autorizados em função de ser um processo reversível e dependente de uma chave secreta. Existem diversos algorítmos de criptografia que permitem que diferentes graus de confidencialidade sejam possíveis e uma ótima introdução ao tema é abordada nesse vídeo do [Fábio Akita](https://www.youtube.com/watch?v=CcU5Kc_FN_4).

### Integridade
O uso de checksums e hashes é largamente difundido visando permitir a detecção de adulterações no conteúdo de uma mensagem, arquivo ou binário, o que garante que se estabeleça uma relação de confiança na informação.

### Disponibilidade
Mecanismos de redundância e backups são utilizados de forma a garantir que a informação esteja a salvo no caso de destruição ou corrupção dos dados, enquanto arquiteturas de alta disponibilidade visam mitigar as tentativas de ataques de negação de serviço.

### A Triplice no Contexto de Desenvolvimento
TODO
### A Triplice no Contexto de Sistemas 
TODO




