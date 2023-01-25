<Page name="home" id="home">

  <Navbar>
    <NavTitle>
      <h1 class="title">Lorenzo Rizzolo - CV</h1>
    </NavTitle>
  </Navbar>

  <center>
    <Card expandable>
      <CardContent padding={false}>
        <div class="card" style="height: 300px">
          <CardHeader textColor="white" class="display-block">
            Curriculum (CV)<br>
            <small style="opacity: 0.8">Scarica il PDF</small>
          </CardHeader>
          <Link cardClose color="white" class="card-opened-fade-in" style="position: absolute; right: 15px; top: 15px" iconF7="xmark_circle_fill" />
        </div>
        <div class="card-content-padding">
          <Button style="color:white;" href="/cv/">clicca per visualizzare il PDF del CV</Button>
        </div>
      </CardContent>
    </Card>
  
    <Card expandable>
      <CardContent padding={false}>
        <div class="card" style="height: 300px">
          <CardHeader textColor="white" class="display-block">
            Contatti<br>
            <small style="opacity: 0.8">Visualizza Contatti</small>
          </CardHeader>
          <Link cardClose color="white" class="card-opened-fade-in" style="position: absolute; right: 15px; top: 15px" iconF7="xmark_circle_fill" />
        </div>
        <div class="card-content-padding">
          <h2>Nome: </h2> Lorenzo Rizzolo <br>
          <h2>Email:</h2> lolloriz36@gmail.com <br>
          <h2>Telefono: </h2> 3465133790 <br>
          <h2>Indirizzo: </h2>Via Torino 31, Piossasco (TO)
        </div>
      </CardContent>
    </Card>
  
    <Card expandable>
      <CardContent padding={false}>
        <div class="card" style="height: 300px">
          <CardHeader textColor="white" class="display-block">
            Competenze<br>
            <small style="opacity: 0.8">Visualizza Competenze</small>
          </CardHeader>
          <Link cardClose color="white" class="card-opened-fade-in" style="position: absolute; right: 15px; top: 15px" iconF7="xmark_circle_fill" />
        </div>
        <div class="card-content-padding">
          <BlockTitle>Competenze Informatiche</BlockTitle>
          <List mediaList inset>
            <ListItem
              title="PHP"
              subtitle="Programamzione BackEnd in PHP.">
            </ListItem>
            <ListItem
              title="JavaScript"
              subtitle="Programmazione BackEnd e FrontEnd in JavaScript.">
            </ListItem>
            <ListItem
              title="HTML, CSS"
              subtitle="Struttura di una pagina web.">
            </ListItem>
            <ListItem
              title="C"
              subtitle="Programmazione in C.">
            </ListItem>
            <ListItem
              title="C++"
              subtitle="Programmazione in C++.">
            </ListItem>
            <ListItem
              title="Python"
              subtitle="Programmazione in Python.">
            </ListItem>
            <ListItem
              title="Switch Cisco"
              subtitle="Utilizzo degli Switch Cisco.">
            </ListItem>
            <ListItem
              title="Cisco Packet Tracer"
              subtitle="Utilizzo basilare di CiscoPacketTracer.">
            </ListItem>
          </List>
          <BlockTitle>Competenze Linguistiche</BlockTitle>
          <List mediaList inset>
            <ListItem
              title="Inglese">
            </ListItem>
            <ListItem
              title="Italiano">
            </ListItem>
          </List>
        </div>
      </CardContent>
    </Card>

    <Card expandable>
      <CardContent padding={false}>
        <div class="card" style="height: 300px">
          <CardHeader textColor="white" class="display-block">
            Certificati<br>
            <small style="opacity: 0.8">Visualizza Certificati</small>
          </CardHeader>
          <Link cardClose color="white" class="card-opened-fade-in" style="position: absolute; right: 15px; top: 15px" iconF7="xmark_circle_fill" />
        </div>
        <div class="card-content-padding">
          <List mediaList inset>
            <ListItem
              title="Patentino Robotica Comau"
              subtitle="Frequentato, e completato con esito positivo il corso del Patentino della robotica Comau.">
            </ListItem>
          </List>
        </div>
      </CardContent>
    </Card>
  
    <Card expandable>
      <CardContent padding={false}>
        <div class="card" style="height: 300px">
          <CardHeader textColor="white" class="display-block">
            Istruzione / Scuola<br>
            <small style="opacity: 0.8">Percorso di studi</small>
          </CardHeader>
          <Link cardClose color="white" class="card-opened-fade-in" style="position: absolute; right: 15px; top: 15px" iconF7="xmark_circle_fill" />
        </div>
        <div class="card-content-padding">
          contenuto
        </div>
      </CardContent>
    </Card>
  
</Page>


<script>
  
  import {
    Accordion, 
    AccordionItem, 
    AccordionContent,
    Icon,
    Card,
    CardContent,
    CardHeader,
    Page,
    Navbar,
    NavLeft,
    NavTitle,
    NavTitleLarge,
    NavRight,
    Link,
    Toolbar,
    Block,
    BlockTitle,
    List,
    ListItem,
    Row,
    Col,
    Button, 
    theme, 
    TreeviewItem, 
    Treeview,
    Subnavbar, 
    Searchbar, 
    Menu, 
    MenuItem 
  } from 'framework7-svelte';


  export let f7route, f7router; // just to remove debug message
</script>