# Store-Theme KatronixStore-Santiago
 KatronixStore-Santiago es una tienda de tecnología basada en la tienda oficial de Katronix.
<img width="397" alt="image" src="https://user-images.githubusercontent.com/55113386/208122735-6daecb3d-ca10-4dc0-8747-6e7382021e18.png">

<img width="385" alt="image" src="https://user-images.githubusercontent.com/55113386/208122790-eb6fb6bc-8feb-4b09-aeaa-92c2d9a6f368.png">

<img width="386" alt="image" src="https://user-images.githubusercontent.com/55113386/208122893-12d68736-ecfd-4bf8-a8a0-11663636dab1.png">

<img width="378" alt="image" src="https://user-images.githubusercontent.com/55113386/208122939-cfb1bf38-7e0f-4457-b953-0230e87a8c03.png">

<img width="409" alt="image" src="https://user-images.githubusercontent.com/55113386/208123011-5742185d-9baf-44b4-941f-ce10f57c43ee.png">

## Configuración

### Paso 1 - Configuración Básica

Acceda a la guía de configuración básica de VTEX IO y siga todos los pasos indicados.

Al final de la configuración, debe tener instalada la interfaz de línea de comandos de VTEX (Toolbelt) junto con un espacio de trabajo de desarrollador en el que puede trabajar.

### Paso 2 - Clonación del repositorio

[Clone]este repositorio en sus archivos locales para poder comenzar a trabajar en él de manera efectiva.

Luego, acceda al directorio del repositorio usando su terminal.

### Paso 3 - Editar el Manifest.json

Una vez en el directorio del repositorio, es hora de editar el manifest.json de la plantilla Minimum Boilerplate.

Una vez en el archivo, debes remplazar los valores de vendor y account. vendor es el nombre de la cuenta que estas trabajando, nuestro partner y account es el nombre que elijas para tu tienda. Por ejemplo:

json
{
  "vendor": "storecomponents",
  "name": "my-test-theme",
}


### Paso 4 - Instalar apps necesarias

Para usar Store Framework y trabajar en el tema de su tienda, es necesario tener instalados `vtex.store-sitemap` y `vtex.store`.

Ejecute `vtex list` y verifique si esas aplicaciones ya están instaladas. 

Si no lo están, ejecute el siguiente comando para instalarlos: `vtex install vtex.store-sitemap vtex.store -f`

### Paso 5 - Desinstalar el store-theme predeterminado

Al ejecutar `vtex list`, puede verificar si algún tema está instalado.

Es común tener ya instalado un `vtex.store-theme` cuando inicia el proceso de desarrollo frontal de la tienda. 

Por lo tanto, si lo encuentra en la lista de aplicaciones, copie su nombre y utilícelo junto con el comando `vtex uninstall`. Por ejemplo:

json
vtex uninstall vtex.store-theme


### Paso 6 - Ejecute un preview de la tienda

Entonces ha llegado el momento de cargar todos los cambios que realizó en sus archivos locales a la plataforma. Para eso, use el comando vtex link.

Si el proceso se ejecuta sin errores, se mostrará el siguiente mensaje: App linked successfully. Luego, ejecute el comando vtex browse para abrir una ventana del navegador con su tienda vinculada.

Esto le permitirá ver los cambios aplicados en tiempo real, a través de la cuenta y el espacio de trabajo en el que está trabajando.

Dependencies

- "vtex.store": "2.x",
- "vtex.store-header": "2.x",
- "vtex.product-summary": "2.x",
- "vtex.store-footer": "2.x",
- "vtex.store-components": "3.x",
- "vtex.styleguide": "9.x",
- "vtex.slider": "0.x",
- "vtex.carousel": "2.x",
- "vtex.shelf": "1.x",
- "vtex.menu": "2.x",
- "vtex.minicart": "2.x",
- "vtex.product-details": "1.x",
- "vtex.product-kit": "1.x",
- "vtex.search-result": "3.x",
- "vtex.login": "2.x",
- "vtex.my-account": "1.x",
- "vtex.flex-layout": "0.x",
- "vtex.rich-text": "0.x",
- "vtex.store-drawer": "0.x",
- "vtex.locale-switcher": "0.x",
- "vtex.product-quantity": "1.x",
- "vtex.product-identifier": "0.x",
- "vtex.product-specification-badges": "0.x",
- "vtex.product-review-interfaces": "1.x",
- "vtex.telemarketing": "2.x",
- "vtex.order-placed": "2.x",
- "vtex.stack-layout": "0.x",
- "vtex.tab-layout": "0.x",
- "vtex.responsive-layout": "0.x",
- "vtex.slider-layout": "0.x",
- "vtex.iframe": "0.x",
- "vtex.breadcrumb": "1.x",
- "vtex.sticky-layout": "0.x",
- "vtex.add-to-cart-button": "0.x",
- "vtex.modal-layout": "0.x",
- "vtex.search": "1.x",
- "vtex.b2b-organizations": "1.x",
- "vtex.store-link": "0.x",
- "vtex.css-handles": "0.x",
- "vtex.product-list": "0.x",
- "vtex.store-icons": "0.x",
- "vtex.store-image": "0.x",
- "vtex.disclosure-layout": "1.x",
- "vtex.product-price": "1.x",
- "vtex.checkout-summary": "0.x",
- "vtex.overlay-layout": "0.x",
- "vtex.product-highlights": "2.x",
- "itgloberspartnercl.whatsapp-button": "0.x",
- "itgloberspartnercl.bullets-diagramation": "0.x",
- "itgloberspartnercl.add-to-cart-info": "0.x",
- "itgloberspartnercl.custom-department-search": "0.x",
- "itgloberspartnercl.pdf-reader": "0.x",
- "itgloberspartnercl.quick-order": "0.x"

PeerDependencies

- "vtex.wish-list": "1.x",
- "vtex.reviews-and-ratings": "3.x",
- "vtex.mega-menu": "2.x"

Custom Apps (Componentes que deben instalarse en la tienda)

- "itgloberspartnercl-whatsapp-button": "0.x",
- "itgloberspartnercl-bullets-diagramation": "0.x",
- "itgloberspartnercl-add-to-cart-info": "0.x",
- "itgloberspartnercl-custom-department-search": "0.x",
- "itgloberspartnercl-pdf-reader": "0.x",
- "itgloberspartnercl-quick-order": "0.x"


Contributors

Santiago Roman Ceferino
