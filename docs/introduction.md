<h2>Introduction au développement web</h2>
<p>
    Le monde devient de plus en plus connecté, les gens passent la majorité de leur temps sur internet soit passé du temps avec ces amis, effectué des achats, discuter des projets, étudier etc. Mais c'est quoi l'internet? simplement, c'est le grands réseau de machine inter-connecté, qui échangent des informations entres elles. Envoyer un SMS á un proche, passer un appèle téléphonique, faire des discussions instantané (whatsApp par exemple), consulter un document sur un page web etc. Dépendant tu type de communication qu'effectue ces machines il y a des règles (qu'on appèle protocole) á respecter, de la même manière que quand on échange avec un proche. Une  <strong>machine A</strong> (téléphone portable par exemple) qui envoie un SMS á une <strong>machine B</strong> ne suivras pas les mêmes protocoles quand elle veux passer un appèle télophonique par exemple. Si les règles ne sont pas respecté, la communication ne passera pas. <br>
    <br>
    Il existe plusieurs protocole,voici quelques exemple : Secure Shell (SSH), est un protocole de communication sécurisé utilisé pour l'accès à distance aux ordinateurs et aux serveurs, Simple Mail Transfer Protocol (SMTP) est un protocole de communication utilisé pour l'envoi de courriers électroniques entre les serveurs de messagerie. Il définit la manière dont les messages électroniques sont transmis sur Internet. Hypertext Transfer Protocol (HTTP)  un protocole de communication utilisé pour transférer des données sur le Web. Il définit la structure des requêtes et des réponses entre les clients et les serveurs Web. <br>
    <br>
    Comme tu l'as remarquer le protocole qui est utilisé pour communiquer entre deux machines sur le web est le protocole http. Chaque moment sur le web on utilise ce protocole pour communiquer. Quand tu demande une page web (en cliquant sur un lien, facebook, youtube etc), ta machine envoi un message á une autre machine le demander cette page (qu'on appèle ressource). Si tout ce passe bien, uen reponse t'ait envoyé. Cette reponse réponse est une <stron>page html</strong> ayant une structure donnée qui est parfois difficile á comprendre si tu n'est pas un programmeur. Pour facilité  l'interpretation un logiciel client le traduis pour que tu puissent comprendre, comme logiciel client il y a par exemple <strong>Chrome, firefox, safarie etc</strong>. <br>
    <br>
    Être développeur web front end c'est d'apprendre á dévélopper des pages web pour les utilisateurs d'une application web. Il y a des language á apprendre, des concepts á maitriser, des pratiques á adopter etc. Ici je vais te les introduire<br> 
</p>
<h4>Les outils pour débuter</h4>
<p>
    Comme tout métier il y a des outils á utiliser pour faire son travail <a href="outils.md">les outilis ici</a>
</p>
<h4>Structure d'une page html</h4>
<p>
     <a href="/docs/structure.html">Toutes pages html á cette structure basique</a>. Toute page qui ne respecte pas cette structure ne sera pas interpréter par le navigateur. Notez que ceci n'est pas la page que tu vas développer, tu vas la personalisée mais en respectant cette structure.
     <ul>
        <li>
            <strong>!DOCTYPE html</strong>
            <p>Ca désigne le type de document que tu écrit, quand le navigateur vera ca il saura que c'est une page html</p>
        </li>
            <strong>html lang="fr"</strong>
            <p>La langue utilisé dans le document, ici c'est français, tu peux la personnalisé</p>
        </li>
         </li>
            <strong>head</strong>
            <p>Cette section contient ce qu'on appél les métadonnées, c'est d'autre informations supplémentaire destiné au navigateur pour avoir une compréhension approfondie sur le document, par exemple quelque encodage utilisé, comment la page va s'afficher sur les différent appareil (ordinateur portable, télephone mobile etc)</p>
        </li>
        </li>
            <strong>body</strong>
            <p>C'est la section ou se trouve ton code, la stucture de ta page, tu la personnalise selon l'objectif que tu veux atteindre, par exemple, mettre les imgaes, vidéos affiché les tableaux etc</p>
        </li>
     </ul>
    Cré un fichier dont l'extension est html, met le code dans ce fichier et ouvre ce fichier avec ton navigateur et tu veras le résultat
</p>
