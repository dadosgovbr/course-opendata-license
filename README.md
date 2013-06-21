# Licenças de Dados Abertos #

Este curso apresenta um convite às reflexões sobre as questões fundamentais
relacionadas ao licenciamento de direitos associados a dados abertos. Serão
mostradas, também, algumas experiências internacionais sobre o assunto. Ele
se baseia parcialmente no
[conteúdo](http://wiki.gtinda.ibge.gov.br/Produto-GT1-Levantamento-Juridico-Licenciamento-Dados-Abertos.ashx)
reunido pelo governo brasileiro, no âmbito da Infraestrurua Nacional de
Dados Abertos (INDA) para viabilizar um estudo sobre licenças de dados
governamentais abertos.

## Licenças conforme a categoria do objeto ##

As licenças que permitem a livre reutilização do objeto podem ser separadas
quanto à sua natureza específica, em três categorias: software, conteúdo e
dados. Essa separação também se evidencia por uma ordem cronológica, em que
cada uma foi elaborada em um momento que se evidenciou a necessidade pelo
fato das licenças anteriores não atenderem a todas as especificidades
necessárias.

### Software ###

A liberdade de uso, cópia e reutilização tem as suas origens no movimento de
software livre. As comunidades de desenvolvimento de software, como forma de se
livrar das restrições impostas por legislações de propriedade intelectual em
todo o mundo, criaram licenças de software que explicitamente permitiam o uso,
o compartilhamento, o estudo e a modificação dos códigos-fonte. Uma das mais
conhecidas é a [General Public License](http://www.gnu.org/licenses/gpl.html)
(GPL), mantida pela [Free Software Foundation](http://www.fsf.org/), a qual
também mantém uma série de [critérios de avaliação para que uma licença de
software seja considerada "livre"](http://www.gnu.org/philosophy/free-sw.html).

### Conteúdo ###

Mais tarde, comunidades que produziam conteúdo de forma colaborativa, se 
espelhando na experiência do software livre, também viram a necessidade de uma 
licença que garantisse liberdades semelhantes em conteúdos de diversos tipos, 
tais como textos, imagens, músicas, sons, vídeo, etc. Dessa forma, nasceu o 
[conjunto de licenças Creative Commons](http://creativecommons.org/licenses/). 
Observa-se que há muitas variações da licença Creative Commons, cada qual 
fornecendo as liberdades ou restrições específicas que o autor desejar vincular
 à sua obra.

Algumas dessas restrições violam os preceitos da [*Open Definition*](http://opendefinition.org/okd/portugues-brasileiro)
 e da [Definição de Obras Culturais Livres](http://freedomdefined.org/Definition) 
 e, portanto, não são consideradas abertas e nem livres, respectivamente. São 
 consideradas abertas as variações [CC-BY](http://creativecommons.org/licenses/by/3.0/br/),
  que requer apenas atribuição de autoria ao compartlhar, [CC-BY-SA](http://creativecommons.org/licenses/by-sa/3.0/br/), 
  que acrescenta a exigência de uso da mesma licença ao redistribuir ou 
  modificar, e [CC-Zero](http://creativecommons.org/choose/zero/), na qual o 
  autor renuncia a todos os direitos de sua obra, colocando-a efetivamente em domínio público.


### Dados ###

Por fim, quando surgiu o movimento de dados abertos, muito se discutiu sobre as
formas de licenciamento necessárias para garantir as liberdades de uso e reúso
fundamentais para a sua essência. Outro ponto frequentemente argumentado pelos
participantes do movimento é que [as licenças para software livre e para
conteúdo livre não seriam adequadas para dados
abertos](http://opendatacommons.org/faq/licenses/#Why_Not_Use_a_Creative_Commons_or_FreeOpen_Source_Software_License_for_Databases),
por serem ativos de naturezas diferentes. Com isso, foi criado um conjunto de
licenças específicas para dados e bancos de dados que garantem as mesmas
liberdades para cada tipo de ativo. Esse conjunto de licenças é conhecido como
_[Open Data Commons](http://opendatacommons.org/)_:

* _[Open Database License](http://opendatacommons.org/licenses/odbl/)_ (ODbL):
  aplicável a esquemas de bancos de dados, arquitetura da informação e à forma
  de organização dos dados. Exige atribuição de autoria e compartilhamento pela
  mesma licença;
* _[Database Content License](http://opendatacommons.org/licenses/dbcl/)_
  (DbCL): mesmas exigências que a ODbL, mas aplicável ao conteúdo dos bancos de
  dados - os dados em si;
* _[Open Data Commons Attribution
  License](http://opendatacommons.org/licenses/by/)_: aplicável aos dados e a
  bancos de dados, mas com exigência apenas de atribuição de autoria;
* _[Public Domain Dedication and
  License](http://opendatacommons.org/licenses/pddl/)_ (PDDL): aplicável aos
  dados e a bancos de dados, mas renuncia a todos os direitos (coloca-os em
  domínio público).

Para ilustrar a questão da inadequação aos dados abertos das licenças de
conteúdo livre, há o caso do projeto _[Open Street
Map](http://openstreetmap.org)_. Trata-se de uma plataforma colaborativa onde
as pessoas criam mapas, registram vias, pontos de interesse, etc., ao visitar
essas localidades munidos de um equipamento de georreferenciamento (GPS). No
início, o projeto utilizou a licença _[Creative Commons Attribution
Share-alike](http://creativecommons.org/licenses/by-sa/2.0/)_, tendo produzido
grande quantidade de dados usando essa licença. Em um determinado momento,
verificou-se a [necessidade de que a licença usada no projeto fosse alterada
para uma que fosse específica para bancos de
dados](http://strata.oreilly.com/2011/06/openstreetmap-creative-commons-open-database-license.html).
Os administradores da comunidade precisaram iniciar um lento processo de
contatar cada um dos autores que colaboraram no projeto, explicar os motivos do
plano de relicenciamento e solicitar que relicenciassem as suas contribuições
sob a nova licença padrão do projeto, a ODbL.

Apesar de esta ser a visão predominante sobre a necessidade de licença
específica para dados abertos, ela não é unânime. Como será visto adiante,
alguns países aplicam as licenças ''Creative Commons'' aos dados abertos por
serem, na sua visão, suficientes e adequadas.

## Licenças de dados abertos em alguns países ##

Embora esta não seja uma lista exaustiva, pela dificuldade em se fazer um
estudo de ampla abrangência, seguem os comportamentos observados em alguns
países quanto à questão do licenciamento de dados.

### Alemanha ###

O [estudo sobre dados governamentais
abertos](http://www.bmi.bund.de/SharedDocs/Downloads/DE/Themen/OED_Verwaltung/ModerneVerwaltung/opengovernment.pdf;jsessionid=1E610723D01195D670CC8399BECBA4A3.2_cid295?__blob=publicationFile)
encomendado pelo governo federal alemão ao Instituto Fraunhoffer inclui um
capítulo sobre licenças (págs. 246 a 276), o qual além de avaliar a situação em
alguns outros países europeus, recomenda a criação de uma nova licença para os
dados, específica para o governo alemão. A licença desenvolvida foi criticada
por ativistas dos dados abertos por não satisfazer a todas as exigências da
_[Open Definition](http://opendefinition.org/okd/portugues-brasileiro)_, uma
vez que não permite a utilização comercial dos dados.

### Austrália ###

O governo australiano, de acordo com as leis de seu país, entendeu ser
suficiente e adequado o uso da licença _Creative Commons_ para os dados que
publica.

### Brasil ###

No Brasil não há licença padrão definida para a publicação de dados
governamentais abertos. O governo federal, no âmbito da Infraestrutura
Nacional de Dados Abertos (INDA), pretende realizar um estudo sobre os
aspectos jurídicos, econômicos e outros relacionados à livre reutilização dos
dados, de forma a determinar se uma licença é necessária e, caso seja,
recomendar a adoção de uma licença existente ou o desenvolvimento de uma nova.

Considerando a legislação brasileira, a [Lei de Direitos
Autorais](http://www.lexml.gov.br/urn/urn:lex:br:federal:lei:1998-02-19;9610)
prevê explicitamente a proteção a bancos de dados. Por outro lado, a [Lei de
Acesso à
Informação](http://www.lexml.gov.br/urn/urn:lex:br:federal:lei:2011-11-18;12527)
imputa ao Estado o dever de proporcionar o acesso, inclusive na internet, a
toda a informação que produz ou detém que não tenha um motivo específico para
ser considerada sigilosa. A interação destas e outras leis relacionadas será
tratada no estudo planejado.

Na prática, até o momento de elaboração deste texto, a maior parte dos órgãos
públicos brasileiros não tem especificado qualquer licença ao publicar dados
na internet. As poucas exceções têm utilizado, por enquanto, as licenças ODbL e
DbCL.

### Canadá ###

O portal canadense de dados governamentais abertos
([data.gc.ca](http://data.gc.ca)) pretende utilizar uma licença chamada
_[Open Government Licence
Agreement](http://www.data.gc.ca/default.asp?lang=En&n=46D15882-1)_, a qual
colocou em consulta pública. A _Creative Commons_ do Canadá participou da
consulta pública e, embora comemore a melhoria em relação aos termos de
licenciamento anterior, [criticou basicamente três
pontos](http://creativecommons.ca/en/oglc-consultation): a ambiguidade na
compatibilidade com as licenças _Creative Commons_; potenciais barreiras nos
mecanismos das cláusulas que vedam a sugestão de status oficial de dados
redistribuídos; e a tentativa de licenciar um direito de banco de dados, o que,
segundo eles, não existe na legislação canadense.

Outro problema apontado pela Creative Commons é que cada esfera de governo
(federal, estadual e municipal) no Canadá tem licenças para dados diferentes e
mutuamente incompatíveis, o que impede o cruzamento de dados de diferentes
fontes.

### Chile ###

Os dados publicados no portal [datos.gob.cl](http://datos.gob.cl) usam a
licença [Creative Commons Attribution 3.0
(Chile)](http://creativecommons.org/licenses/by/3.0/cl/).

### Espanha ###

A Espanha não tem uma licença específica para dados governamentais abertos. Em
vez disso, o portal espanhol de dados abertos,
[datos.gob.es](http://datos.gob.es), tem termos de uso (
_Aviso legal datos.gob.es_ ) que especificam as permissões de reutilização,
inclusive para fins comerciais.

### E.U.A. ###

Pela Constituição dos Estados Unidos da América, [todo o conteúdo, dados ou
informações produzidos pelo governo são considerados de domínio
público](http://www.law.cornell.edu/uscode/text/17/105). Portanto, já estão
garantidas todas as liberdades fundamentais para dados abertos.

Este talvez seja o melhor exemplo em relação a licenciamento de dados abertos
no mundo, tanto por estar disposto na Constituição do país de forma
obrigatória, quanto especificar que o objeto está em domínio público, que é o
modelo mais liberal possível.

### França ###

A França utiliza, para os dados disponibilizados em seu portal
[data.gouv.fr](http://data.gouv.fr), a [Licence
Ouverte](http://www.data.gouv.fr/Licence-Ouverte-Open-Licence) (licença
aberta). As permissões da _Open Definition_ (usar, reutilizar, copiar,
modificar, uso comercial) são garantidas, mas ela também inclui as usuais
cláusulas que vedam a apresentação de status oficial aos dados redistribuídos.
É mencionado que a atribuição de autoria pode ser feita por meio de
_hyperlinks_. A licença afirma explicitamente ser compatível com a _Open
Government Licence_ do Reino Unido, com a _Creative Commons Attribution 2.0_
(CC-BY) e com a _Open Data Commons Attribution_ (ODC-BY) da _Open Knowledge
Foundation_.

### Noruega ###

A Noruega possui uma licença própria para os dados governamentais abertos, a
_[Norsk lisens for offentlige data](http://data.norge.no/nlod/no)_ (NLOD). Ela
permite as liberdades de uso, reúso, modificação e cópia, inclusive para fins
comerciais.

Algumas restrições adicionais são a isenção de responsabilidade pela qualidade
dos dados, a atribuição de autoria, desde que não passe a impressão de que o
governo endossa a sua forma de uso dos dados e o provimento de link para a
licença. Essas restrições são semelhantes às da _Open Government Licence_ do
Reino Unido.

### Reino Unido ###

Pela lei britânica, todo conteúdo produzido pelo governo daquele país pertence
à coroa ( _[Crown
Copyright](http://www.nationalarchives.gov.uk/information-management/our-services/crown-copyright.htm)_
). Assim, quando a necessidade de abertura de dados se tornou uma política
oficial, o governo britânico encomendou um estudo ao _National Archives_, o
qual culminou no desenvolvimento e
[estabelecimento](http://data.gov.uk/blog/new-open-government-license) da
[Open Government Licence](http://www.nationalarchives.gov.uk/doc/open-government-licence/)
como licença padrão para os dados publicados pelo governo britânico. Essa
licença [garante as liberdades de uso e
reúso](http://www.nationalarchives.gov.uk/information-management/government-licensing/about-the-ogl.htm)
preconizadas pela _[Open
Definition](http://opendefinition.org/okd/portugues-brasileiro)_, qualificando
os dados publicados como dados abertos.

As restrições aplicadas são a atribuição de autoria, mas de uma forma que não
indique endosso ou status oficial, por parte do governo, do seu uso da
informação. Além disso, não ludibriar terceiros ou distorcer a informação ou a
sua fonte.

#### Uruguai ###

O portal de dados governamentais abertos do Uruguai
([catalogodatos.gub.uy](https://catalogodatos.gub.uy)) tem, em seus conjuntos
de dados, a menção a uma _"Licencia de Datos Abiertos de Uruguay"_. Contudo,
não é fornecido link para o conteúdo da licença e não foi possível localizá-la.

