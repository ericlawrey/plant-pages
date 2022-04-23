---
species: flueggea virosa
commonname: White Currant
---

# {{ page.species | capitalize }}
{{ page.commonname }}

# Natural Occurrence:
A local shrub/small tree. Occurs in open forest, vine
thickets, beach scrub and monsoon forest.

# Appearance:
Multi-stemmed, sprawling shrub (1-4m),
often deciduous in dry seasons. Small,
cream-green flowers (females & males
on separate plants) cluster along stems
(Oct-Feb), followed by profuse, round,
snowy-white, fleshy berries.

# Growth Conditions:
Prefers full sun & well-drained soil. Responds well to
regular water in warm months. Drought hardy. Garden
appeal is limited, but useful as screen plant.

# Distinctive Features:
Indigenous use: An important food plant; fruit are bush
tucker; bark/roots used medicinally. Birds & other animals
eat the fruit. Useful in erosion control.

# Botanical Family: PHYLLANTHACEAE

{{ page.species | capitalize }}

{{ page.commonname }}

{{site.url}}{{ page.url }}

<div id="qrcode"></div>
<script src="{{ site.baseurl }}{% link assets/js/qrcode.js %}"> </script>
<script type="text/javascript">
new QRCode(document.getElementById("qrcode"), "{{site.url}}{{ page.url }}");
</script>
