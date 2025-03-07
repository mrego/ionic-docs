---
title: "ion-fab-list"
hide_table_of_contents: true
---
import Tabs from '@theme/Tabs';
import TabItem from '@theme/TabItem';

import Props from '@site/static/auto-generated/fab-list/props.md';
import Events from '@site/static/auto-generated/fab-list/events.md';
import Methods from '@site/static/auto-generated/fab-list/methods.md';
import Parts from '@site/static/auto-generated/fab-list/parts.md';
import CustomProps from '@site/static/auto-generated/fab-list/custom-props.md';
import Slots from '@site/static/auto-generated/fab-list/slots.md';



import EncapsulationPill from '@components/page/api/EncapsulationPill';
import APITOCInline from '@components/page/api/APITOCInline';

<EncapsulationPill type="shadow" />

<h2 className="table-of-contents__title">Contents</h2>

<APITOCInline
  toc={toc}
  maxHeadingLevel={2}
  autogenerated={[Props, Events, Methods, Parts, CustomProps, Slots]}
/>



The `ion-fab-list` element is a container for multiple fab buttons. This collection of fab buttons contains actions related to the main fab button and is flung out on click. To specify what side the buttons should appear on, set the `side` property to 'start', 'end', 'top', 'bottom'



## Usage

<Tabs groupId="framework" defaultValue="angular" values={[{ value: 'angular', label: 'Angular' }, { value: 'javascript', label: 'Javascript' }, { value: 'react', label: 'React' }, { value: 'stencil', label: 'Stencil' }, { value: 'vue', label: 'Vue' }]}>

<TabItem value="angular">

```html
<ion-fab vertical="center" horizontal="center">
  <ion-fab-button>Share</ion-fab-button>
  <ion-fab-list side="top">
    <ion-fab-button>
      <ion-icon name="logo-facebook"></ion-icon>
    </ion-fab-button>
    <ion-fab-button>
      <ion-icon name="logo-twitter"></ion-icon>
    </ion-fab-button>
    <ion-fab-button>
      <ion-icon name="logo-youtube"></ion-icon>
    </ion-fab-button>
  </ion-fab-list>

  <ion-fab-list side="end">
    <ion-fab-button>
      <ion-icon name="logo-pwa"></ion-icon>
    </ion-fab-button>
    <ion-fab-button>
      <ion-icon name="logo-npm"></ion-icon>
    </ion-fab-button>
    <ion-fab-button>
      <ion-icon name="logo-ionic"></ion-icon>
    </ion-fab-button>
  </ion-fab-list>

  <ion-fab-list side="bottom">
    <ion-fab-button>
      <ion-icon name="logo-github"></ion-icon>
    </ion-fab-button>
    <ion-fab-button>
      <ion-icon name="logo-javascript"></ion-icon>
    </ion-fab-button>
    <ion-fab-button>
      <ion-icon name="logo-angular"></ion-icon>
    </ion-fab-button>
  </ion-fab-list>

  <ion-fab-list side="start">
    <ion-fab-button>
      <ion-icon name="logo-vimeo"></ion-icon>
    </ion-fab-button>
    <ion-fab-button>
      <ion-icon name="logo-chrome"></ion-icon>
    </ion-fab-button>
    <ion-fab-button>
      <ion-icon name="logo-react"></ion-icon>
    </ion-fab-button>
  </ion-fab-list>
</ion-fab>
```


</TabItem>


<TabItem value="javascript">

```html
<ion-fab vertical="center" horizontal="center">
  <ion-fab-button>Share</ion-fab-button>
  <ion-fab-list side="top">
    <ion-fab-button>
      <ion-icon name="logo-facebook"></ion-icon>
    </ion-fab-button>
    <ion-fab-button>
      <ion-icon name="logo-twitter"></ion-icon>
    </ion-fab-button>
    <ion-fab-button>
      <ion-icon name="logo-youtube"></ion-icon>
    </ion-fab-button>
  </ion-fab-list>

  <ion-fab-list side="end">
    <ion-fab-button>
      <ion-icon name="logo-pwa"></ion-icon>
    </ion-fab-button>
    <ion-fab-button>
      <ion-icon name="logo-npm"></ion-icon>
    </ion-fab-button>
    <ion-fab-button>
      <ion-icon name="logo-ionic"></ion-icon>
    </ion-fab-button>
  </ion-fab-list>

  <ion-fab-list side="bottom">
    <ion-fab-button>
      <ion-icon name="logo-github"></ion-icon>
    </ion-fab-button>
    <ion-fab-button>
      <ion-icon name="logo-javascript"></ion-icon>
    </ion-fab-button>
    <ion-fab-button>
      <ion-icon name="logo-angular"></ion-icon>
    </ion-fab-button>
  </ion-fab-list>

  <ion-fab-list side="start">
    <ion-fab-button>
      <ion-icon name="logo-vimeo"></ion-icon>
    </ion-fab-button>
    <ion-fab-button>
      <ion-icon name="logo-chrome"></ion-icon>
    </ion-fab-button>
    <ion-fab-button>
      <ion-icon name="logo-react"></ion-icon>
    </ion-fab-button>
  </ion-fab-list>
</ion-fab>
```


</TabItem>


<TabItem value="react">

```tsx
import React from 'react';
import { IonFab, IonFabButton, IonFabList, IonContent, IonIcon } from '@ionic/react';
import { logoFacebook, logoTwitter, logoYoutube, logoPwa, logoNpm, logoIonic, logoGithub, logoJavascript, logoAngular, logoVimeo, logoChrome, logoReact } from 'ionicons/icons';

export const FabListExample: React.FC = () => (
  <IonContent>
    <IonFab vertical="center" horizontal="center">
      <IonFabButton>Share</IonFabButton>
      <IonFabList side="top">
        <IonFabButton>
          <IonIcon icon={logoFacebook} />
        </IonFabButton>
        <IonFabButton>
          <IonIcon icon={logoTwitter} />
        </IonFabButton>
        <IonFabButton>
          <IonIcon icon={logoYoutube} />
        </IonFabButton>
      </IonFabList>

      <IonFabList side="end">
        <IonFabButton>
          <IonIcon icon={logoPwa} />
        </IonFabButton>
        <IonFabButton>
          <IonIcon icon={logoNpm} />
        </IonFabButton>
        <IonFabButton>
          <IonIcon icon={logoIonic} />
        </IonFabButton>
      </IonFabList>

      <IonFabList side="bottom">
        <IonFabButton>
          <IonIcon icon={logoGithub} />
        </IonFabButton>
        <IonFabButton>
          <IonIcon icon={logoJavascript} />
        </IonFabButton>
        <IonFabButton>
          <IonIcon icon={logoAngular} />
        </IonFabButton>
      </IonFabList>

      <IonFabList side="start">
        <IonFabButton>
          <IonIcon icon={logoVimeo} />
        </IonFabButton>
        <IonFabButton>
          <IonIcon icon={logoChrome} />
        </IonFabButton>
        <IonFabButton>
          <IonIcon icon={logoReact} />
        </IonFabButton>
      </IonFabList>
    </IonFab>
  </IonContent>
);

```

</TabItem>


<TabItem value="stencil">

```tsx
import { Component, h } from '@stencil/core';

@Component({
  tag: 'fab-list-example',
  styleUrl: 'fab-list-example.css'
})
export class FabListExample {
  render() {
    return [
      <ion-fab vertical="center" horizontal="center">
        <ion-fab-button>Share</ion-fab-button>
        <ion-fab-list side="top">
          <ion-fab-button>
            <ion-icon name="logo-facebook"></ion-icon>
          </ion-fab-button>
          <ion-fab-button>
            <ion-icon name="logo-twitter"></ion-icon>
          </ion-fab-button>
          <ion-fab-button>
            <ion-icon name="logo-youtube"></ion-icon>
          </ion-fab-button>
        </ion-fab-list>

        <ion-fab-list side="end">
          <ion-fab-button>
            <ion-icon name="logo-pwa"></ion-icon>
          </ion-fab-button>
          <ion-fab-button>
            <ion-icon name="logo-npm"></ion-icon>
          </ion-fab-button>
          <ion-fab-button>
            <ion-icon name="logo-ionic"></ion-icon>
          </ion-fab-button>
        </ion-fab-list>

        <ion-fab-list side="bottom">
          <ion-fab-button>
            <ion-icon name="logo-github"></ion-icon>
          </ion-fab-button>
          <ion-fab-button>
            <ion-icon name="logo-javascript"></ion-icon>
          </ion-fab-button>
          <ion-fab-button>
            <ion-icon name="logo-angular"></ion-icon>
          </ion-fab-button>
        </ion-fab-list>

        <ion-fab-list side="start">
          <ion-fab-button>
            <ion-icon name="logo-vimeo"></ion-icon>
          </ion-fab-button>
          <ion-fab-button>
            <ion-icon name="logo-chrome"></ion-icon>
          </ion-fab-button>
          <ion-fab-button>
            <ion-icon name="logo-react"></ion-icon>
          </ion-fab-button>
        </ion-fab-list>
      </ion-fab>
    ];
  }
}
```

</TabItem>


<TabItem value="vue">

```html
<template>
  <ion-fab vertical="bottom" horizontal="end">
    <ion-fab-button>Share</ion-fab-button>

    <ion-fab-list side="top">
      <ion-fab-button>Facebook</ion-fab-button>
      <ion-fab-button>Twitter</ion-fab-button>
      <ion-fab-button>Youtube</ion-fab-button>
    </ion-fab-list>

    <ion-fab-list side="start">
      <ion-fab-button>Vimeo</ion-fab-button>
    </ion-fab-list>

  </ion-fab>
</template>

<script>
import { IonFab, IonFabButton, IonFabList } from '@ionic/vue';
import { defineComponent } from 'vue';

export default defineComponent({
  components: { IonFab, IonFabButton, IonFabList }
});
</script>
```


</TabItem>

</Tabs>

## Properties
<Props />

## Events
<Events />

## Methods
<Methods />

## CSS Shadow Parts
<Parts />

## CSS Custom Properties
<CustomProps />

## Slots
<Slots />