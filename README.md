var brazil = document.createElement('option');
brazil.value = '+55';
brazil.appendChild(document.createTextNode('Brazil +55'));
document.querySelectorAll('#countrycode').forEach(select => select.prepend(brazil));
brazil.selected = true;
