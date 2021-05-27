`s3cmd put -P --guess-mime-type --exclude '.git/*' --exclude-from .gitignore --recursive ./ s3://www.driedtoast.com`

Uses 
git clone https://github.com/aerohub/hugo-orbit-theme

mv index.html in public to resume
cp index.html to publics
cp css to public
cp image to public 

^ simplify above with index referencing assets in theme