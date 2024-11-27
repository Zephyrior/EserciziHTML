<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sviluppo di una pagina web - Blog Epicode</title>
</head>
<body>
    <div style="display: flex;">
    <header>
        <img src="./logo.svg" width="180px">
        <p>
            <span><strong>Epicode</strong></span> - <span style="color: blueviolet;"><em>Il blog dei developer</em></span>
        </p>
    </header>
    <nav align="center">
        <dl style="display: flex">
            <dd>Home</dd> <dd>Articoli</dd> <dd>Lavora con noi</dd>
        </dl>
    </nav>
    </div>
    <main>
        <article>
            <h1 style="margin-bottom: 0%;">Come creare un template per i post</h1>
            <p style="font-size: smaller;">
                di Mario Rossi - pubblicato il 25-10-2020
            </p>
            <br>
            <p>
                La prima cosa da fare è suddividere in blocchi logici la pagina, identificando le parti comuni da applicare a tutte le pagine.
            </p>
            <p>
                Le varie aree saranno suddivise in:
            </p>
            <ul>
                <li>Contenuti di intestazione del tag &lt;header&gt;</li>
                <li>Contenuti centrali variabili del tag &lt;main&gt; (corpo principale)</li>
                <li>Contenuti di fine pagina comuni, da inserire nel tag &lt;footer&gt;</li>
            </ul>
            <p>
                Formattazione del codice
            </p>
            <p>
                Il testo dell'articolo dovrà essere formattato per identificare tutte le parti da selezionare con i CSS. Perciò i passi saranno:
            </p>
            <ol>
                <li>Progettare il markup assegnando ad ogni specifico testo il tag appropriato</li>
                <li>Scrivere l'HTML dai tag esterni a quelli interni e dall'alto verso basso</li>
                <li>Applicare gli stili CSS</li>
            </ol>
            <p>
                L'applicazione di stili CSS è cresciuta negli anni fino a raggiungere la diffusione pressoché totale.
            </p>
            <table>
                <caption>Diffusione dei CSS</caption>
                <tr>
                    <th>Anno</th>
                    <th>% di utilizzo</th>
                    <th>Supporto browsers</th>
                </tr>
                <tr>
                    <td>2000</td>
                    <td>20%</td>
                    <td>17%</td>
                </tr>
                <tr>
                    <td>2002</td>
                    <td>35%</td>
                    <td>22%</td>
                </tr>
                <tr>
                    <td>2004</td>
                    <td>45%</td>
                    <td>42%</td>
                </tr>
                <tr>
                    <td>2008</td>
                    <td>80%</td>
                    <td>51%</td>
                </tr>
                <tr>
                    <td>2012</td>
                    <td>100%</td>
                    <td>76%</td>
                </tr>
            </table>
            <p>
                Un test di validazione potrà essere fatto tramite il tool online <a href="#">-LINK ESTERNO-</a> dedicato allo scopo. Una volta ottimizzato il tutto, avremo raggiunto il nostro obiettivo ed essere stati dei veri developers come loro:            
            </p>
            <div style="display: flex">
                 <iframe 
                width="560" 
                height="315" 
                src="https://www.youtube.com/embed/sOnsyLAXfSI?si=tzY1OGeBXqkjrpcT" 
                title="YouTube video player" 
                frameborder="0" 
                allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" 
                referrerpolicy="strict-origin-when-cross-origin" 
                allowfullscreen>
            </iframe>
            <aside>
                <p>
                    <h4>Articoli correllati</h4>
                    <a href="#">Validare il codice</a> <br>
                    Categoria: develop<br>
                    Data: 18-9-2020<br>
                    <br>
                    <a href="#"> Corregere la sintassi</a><br>
                    Categoria: develop<br>
                    Data: 16-09-2020<br>
                    <br>
                    <a href="#"> Meno Kb nella pagina </a><br>
                    Categoria: Ottimizzazione<br>
                    Data: 30-09-2020
                </p>
            </aside>
            </div>
        </article>
    </main>
    <section>
        <p>
            Vuoi rimanere aggiornato su altre novità del blog?
        </p>
        <form action="IscrizioneNewsletter.java" method="POST">
            <fieldset>
                <legend>Iscriviti alla nostra newsletter:</legend>
                <label for="fullname"></label>
                <input type="text" id="fullname" name="fullname" placeholder="Nome e Cognome" required>
                <br>
                <label for="email"></label>
                <input type="email" id="email" name="email" placeholder="Esempio@esempio.net" required>
                <br>
                <br>
                <button type="submit">Iscriviti</button>
            </fieldset>
        </form>
    </section>
    <hr>
    <footer>
        <p align="center" style="font-size: smaller;">
            Blog Epicode &copy; 2023
            Testata online di Mario Rossi, registrata con prot.213/218 - via Luigi Einaudi 2 - Milano. P.IVA 00112233.<br>
            info@epicode.school <i><a href="mailto:info@epicode.school">-LINK EMAIL-</a></i>
        </p>
    </footer>
</body>
</html>
