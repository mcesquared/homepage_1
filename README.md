# homepage_1

<h3>Features</h3><p>Browser start page. Reactive menus, multi-site searchbar, randomly picks background from an array of included wallpapers.</p><br>

<h3>Files</h3><p>Backgrounds should be extracted into the same directory as the homepage. Backgrounds should be .jpg format (specifically written ".jpg") and should be named following "bg-1.jpg, ... bg-12.jpg" formatting. Additional images can be added to the array at line 330 of the source. The variable that determines the random background is defined at line 331, and the CSS rule that sets the random backgroung is at line 333.</p><br>

<h3>Searchbar</h3><p>The searchbar can be used to search mutliple sites depending on a trailing tag added to search terms. Trailing tags take the form of "-*", where "*" is a single designated letter. Current sites are: "-a" Amazon, "-y" Youtube, "-w" Wikipedia, "-p" Piratebay.org, "-i" IMDB, and "-b" Bing Images. The Javascript funtion that determines sites queried begins at line 368; placeholder text in the blank searchbar is designated at line 200.</p><br>

<h3>Cards</h3><p>Website links are on cards that expand on hover over the title. The links themselves highlight on hover. 
Links are easily added via unordered list items to the tables beginning at line 205. The cards are not responsive, so the homepage is not suitable for mobile browsers (yet). I may fix that in the future.</p><br>

<h3>Credits and Blatherings</h3><p>Credit to the 4chan /wg/ Anons whose two homepages inspired this one and contributed to the code. I've modified the source somewhat from their originals, but I expect that were they to look at the code they'd recognize it as their own. This was intended as an educational exercise to become more familiar with CSS, Javascript and HTML 5.0.</p>
