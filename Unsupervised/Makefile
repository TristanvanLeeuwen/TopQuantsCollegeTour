presentation: presentation.ipynb
	jupyter nbconvert presentation.ipynb --to slides  --SlidesExporter.reveal_url_prefix=reveal.js --SlidesExporter.reveal_theme="solarized" --post serve

html: presentation.ipynb
	cp presentation.ipynb index.ipynb
	jupyter nbconvert index.ipynb --to slides --reveal-prefix "https://cdnjs.cloudflare.com/ajax/libs/reveal.js/3.1.0"
