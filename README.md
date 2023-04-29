<h2>Spring Security </h2>

<h3>- InMemory Authentication method :</h3>
<img src="Screenshots/in_memory.png" alt="">
<h4>Protection des methodes avec l'annotation "@PreAuthorize".</h4>
<img src="Screenshots/method_protec.png" alt="">


<h3>- JDBC Authentication method :</h3>
<h4>JDBC Bean permettant la connexion avec la base de données via l'objet dataSource.</h4>
<img src="Screenshots/jdbc_auth.png" alt="">
<h4>La Création des users avec leurs roles au démarrage de l'application via le JDBC Bean crée.</h4>
<img src="Screenshots/user_crea.png" alt="">
<h4>Le Fichier schema.sql contenant les requêttes permettant la création des tables users et authorities et un index sur leurs colonnes.</h4>
<img src="Screenshots/schema_sql.png" alt="">

<h3>- UserDetails Authentication method :</h3>
<h4>L'entité User :</h4>
<img src="Screenshots/user_entity.png" alt="">
<h4>L'entité Role :</h4>
<img src="Screenshots/role_entity.png" alt="">

<h4>L'interface UserRepository :</h4>
<img src="Screenshots/i_userrepo.png" alt="">
<h4>L'interface RoleRepository :</h4>
<img src="Screenshots/role_repo.png" alt="">

<h4>L'interface UserService :</h4>
<img src="Screenshots/user_service.png" alt="">
<h4>L'implémentation de l'interface UserService :</h4>
<img src="Screenshots/user_implpng" alt="">

<h4>La Création des users et des roles et affecter les roles au users.</h4>
<img src="Screenshots/user_detail.png" alt="">
<p>N.B: Il faut pas les recrée afin d'éviter une des exception définies dans les méthodes.</p>

<h4>L'implémentation de l'interface UserDetailsService :</h4>
<img src="Screenshots/user_detail_impl.png" alt="">
<h4>Configuration de la methode UserDetails par un objet de type UserDetailServiceImpl :</h4>
<img src="Screenshots/filter_chain.png" alt="">
