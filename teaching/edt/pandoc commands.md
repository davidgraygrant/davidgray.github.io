pandoc "EDT L8 Consequentialism.md" -o edtl8.pdf -t beamer -V documentclass=dmgbeamer



pandoc "EDT L8 Consequentialism.md" -o edtl8.pptx --slide-level=2





pandoc l10.md -o l10-handout.docx

pandoc -t revealjs l11.md -o l11-slides.html -s --variable controls="false" --variable progress="false" --variable width="1280" --variable height="720" --variable center="false" --variable margin="0" --variable navigationMode="linear" --variable transition="none" --slide-level=2

pandoc -t revealjs l11.md -o l11-slides.html -s --slide-level=2