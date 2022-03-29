# git am

> பேட்ச் கோப்புகளைப் பயன்படுத்துங்கள். மின்னஞ்சல் வழியாக கமிட் பெறும்போது பயனுள்ளதாக இருக்கும்.
> பேட்ச் கோப்புகளை உருவாக்கக்கூடிய `git format-patch` கட்டளையை காண்க.
> மேலும் விவரத்திற்கு: <https://git-scm.com/docs/git-am>.

- பேட்ச் கோப்பைப் பயன்படுத்துங்கள்:

`git am {{கோப்புக்கான/பாதை/கோப்பு.patch}}`

- பேட்ச் கோப்பைப் பயன்படுத்துவதற்கான செயல்முறையை நிறுத்தவும்:

`git am --abort`

- கோப்புகளை நிராகரிக்க தோல்வியுற்ற ஹன்களை சேமித்து, முடிந்தவரை ஒரு பேட்ச் கோப்பைப் பயன்படுத்துங்கள்:

`git am --reject {{கோப்புக்கான/பாதை/கோப்பு.patch}}`