# Oscillation Overthruster

<details>
    <summary open>Oscillation Overthruster 🗿 Flux Capacitor 🪐 Orthogonal Diagonalizer 👁️ Protomolecule</summary>
<p align="center">
<img src="https://neodigm.github.io/vivid_vector_alphabet/wasm/vvo.svg" width="33" alt="Vivid TypeScript ⚡ WASM ✨ PWA 🍭 ThreeJS Protomolecule">
<img src="https://neodigm.github.io/vivid_vector_alphabet/wasm/vvs.svg" width="33" alt="Electra Glide safron Orthogonal Diagonalizer Protomolecule">
<img src="https://neodigm.github.io/vivid_vector_alphabet/wasm/vvc.svg" width="33" alt="ginger stratagem">
<img src="https://neodigm.github.io/vivid_vector_alphabet/wasm/vvi.svg" width="33" alt="tapestry Inventive Infographics UX PWA Typescript Svelte ThreeJS Vue ✨ htmx">
<img src="https://neodigm.github.io/vivid_vector_alphabet/wasm/vvl.svg" width="33" alt="when information grows unprofitable">
<img src="https://neodigm.github.io/vivid_vector_alphabet/wasm/vvl.svg" width="33" alt="Crave Breathtaking DataVis 🚀 Micro Frontend 🚀 PWA HTMLX">
<img src="https://neodigm.github.io/vivid_vector_alphabet/wasm/vva.svg" width="33" alt="Delirious Stunning Orthogonal Diagonalizer">
<img src="https://neodigm.github.io/vivid_vector_alphabet/wasm/vvt.svg" width="33" alt="Life-changing Gorgeous HTMLX">
<img src="https://neodigm.github.io/vivid_vector_alphabet/wasm/vvi.svg" width="33" alt="Brilliant DataVis 👁️ UX 🍭 PWA 👁️ ThreeJS ✨ Vue  🚀 Svelte 🌶️ htmlx">
<img src="https://neodigm.github.io/vivid_vector_alphabet/wasm/vvo.svg" width="33" alt="Shopify PWA Polaris Liquid GraphQL 🍭 indelible bloom">
<img src="https://neodigm.github.io/vivid_vector_alphabet/wasm/vvn.svg" width="33" alt="Vivid Vector Three.js 🚀 TypeScript 🚀 WASM ✨ PWA">
</p>
  
 <p align="center">
<img src="https://neodigm.github.io/vivid_vector_alphabet/wasm/vvo.svg" width="33" alt="DataVis 👁️ UX 🍭 PWA 👁️ ThreeJS">
<img src="https://neodigm.github.io/vivid_vector_alphabet/wasm/vvv.svg" width="33" alt="UX artisan ⚡ illustrator ⚡ front-end engineer">
<img src="https://neodigm.github.io/vivid_vector_alphabet/wasm/vve.svg" width="33" alt="👁️ D3 Parallax Three.js && WebGL && GSAP 🍭">
<img src="https://neodigm.github.io/vivid_vector_alphabet/wasm/vvr.svg" width="33" alt="Vivid DataVis 👁️ UX 🍭 PWA 👁️ ThreeJS ✨ Vue  🚀 Svelte 🌶️ htmlx">
<img src="https://neodigm.github.io/vivid_vector_alphabet/wasm/vvt.svg" width="33" alt="Vivid 😎 Oscillation Overthruster 🪐">
<img src="https://neodigm.github.io/vivid_vector_alphabet/wasm/vvh.svg" width="33" alt="Vivid Orthogonal Diagonalizer DataVis 🚀 Micro Frontend 🚀 PWA">
<img src="https://neodigm.github.io/vivid_vector_alphabet/wasm/vvr.svg" width="33" alt="Vivid Vector UX artisan ⚡ illustrator ⚡ Engineer">
<img src="https://neodigm.github.io/vivid_vector_alphabet/wasm/vvu.svg" width="33" alt="Vivid Vector Creative ⚡ Business ⚡ Technical Agility">
<img src="https://neodigm.github.io/vivid_vector_alphabet/wasm/vvs.svg" width="33" alt="Vivid Vector UX artisan ⚡ illustrator ⚡ front-end engineer">
<img src="https://neodigm.github.io/vivid_vector_alphabet/wasm/vvt.svg" width="33" alt="Vivid Vector Creative ⚡ Business ⚡ Technical Agility">
<img src="https://neodigm.github.io/vivid_vector_alphabet/wasm/vve.svg" width="33" alt="😎 Oscillation Overthruster 🪐">
<img src="https://neodigm.github.io/vivid_vector_alphabet/wasm/vvr.svg" width="33" alt="Effortless Unexpected DataVis 👁️ UX 🍭 PWA 👁️ ThreeJS ✨ Vue  🚀 Svelte">
</p>
</details>

<p align="center">
  <a target="_blank" href="https://www.thescottkrause.com/d3_datavis_skills.html" title="D3js Skills with Audio">
  <img src="https://raw.githubusercontent.com/neodigm/Oscillation-Overthruster/master/Oscillation-Overthruster.webp" title="D3js Skills with Audio">
  </a>
</p>

[JavaScrpt Implementation](https://www.thescottkrause.com/tags/javascript/) [Neodigm 55 Metronone](https://github.com/arcanus55/neodigm55)

```javascript
//  Neodigm 55 Metronome Begin  // DataVis 👁️ UX 🍭 PWA 👁️ ThreeJS ✨ Vue  🚀 Svelte
const neodigmMetronome = ( () =>{
  let oEmit = {}, aIntv = []
  let bIsInit = bIsPause = false 
  return {  //  Oscillation Overthruster
    init: function(){  //  Reset all
      oEmit = {}
      aIntv.forEach( ( i )=>{ clearInterval( i[0] ) } )
      bIsInit = true
      return neodigmMetronome;
    },
    tick: function( t ){
      if( bIsInit && !bIsPause ){ oEmit[ t ].forEach( ( f )=>{
        if( oEmit[ t ].mx || oEmit[ t ].mx == 0 ){
          if( oEmit[ t ].mx ){ f( --oEmit[ t ].mx ) }
        }else{ f() }
      } ) }
      return neodigmMetronome;
    },
    subscribe: function( f, t, mx ){  //  Usage: .subscribe(f, 1000, 5)
      let _t = t
      if( bIsInit ){
        if( !oEmit[ _t ] ){
          oEmit[ _t ] = []
          aIntv.push( [setInterval( ()=>{ neodigmMetronome.tick( _t ) }, _t ), t] )
        }
        oEmit[ _t ].push( f )
        if( mx ) oEmit[ _t ].mx = mx
      }
      return neodigmMetronome;
    },
    unsubscribe: function( t ){ 
      oEmit[ t ] = null;
      aIntv = aIntv.filter( ( i )=>{
        if( i[1] == t ){clearInterval( i[0] ); return false; }
        return true;
      } )
      return neodigmMetronome;
    },
    pause: function( nT ){
      bIsPause = true;
      if( nT ) setTimeout( neodigmMetronome.play, nT )
      return neodigmMarquee; },
    isPaused: function(){ return bIsPause },
    play:  function(){ bIsPause = false; return neodigmMarquee; }
  }
})();
```

---
#
[Portfolio Blog](https://www.theScottKrause.com) |
[🦄 Résumé](https://thescottkrause.com/Arcanus_Scott_C_Krause_2023.pdf) |
[UX micro-library](https://thescottkrause.com/emerging_tech/neodigm55_ux_library/) |
[PWA WASM](https://www.thescottkrause.com/emerging_tech/curated-pwa-links/) |
[DevToys](https://www.thescottkrause.com/devtoys/) |
[Neodigm UX Wiki](https://github.com/arcanus55/neodigm55/wiki/Cheat-Sheet) | 
[NPM](https://www.npmjs.com/~neodigm) |
[Github](https://github.com/neodigm) |
[LinkedIn](https://www.linkedin.com/in/neodigm555/) |
[Gists](https://gist.github.com/neodigm?direction=asc&sort=created) |
[Salesforce](https://trailblazer.me/id/skrause) |
[Code Pen](https://codepen.io/neodigm24) |
[Machvive](https://www.machfivemarketing.com/accelerators/google_analytics_ga4_migration/) |
[Arcanus 55](https://www.arcanus55.com/?trusted55=A55PV2) |
[Medium](https://medium.com/@neo5ive/accessibility-%EF%B8%8F-ecommerce-552d4d35cd66) |
[W3C](https://www.w3.org/users/123844) |
[InfoSec](https://arcanus55.medium.com/offline-vs-cloud-password-managers-51b1fbebe301)
#
<p align="center">
	  <a target="_blank" href="https://www.thescottkrause.com/emerging_tech/cytoscape_dataviz_skills/">
	  	<img src="https://neodigm.github.io/brand_logo_graphic_design/fantastic/discerning/22.webp" alt="TypeScript UX 🪐 Interactive Infographic ⚡ WASM ✨ PWA 🍭 Svelte">
	  </a>
</p>

<p align="center">
  <a target="_blank" href="https://www.thescottkrause.com">
    <img src="https://neodigm.github.io/pan-fried-monkey-fisticuffs/thescottkrause_contact_card.png" title="UX PWA TypeScript ⚡ WASM ✨ Vue.js 🍭 ThreeJS" alt="Interactive Infographic">
  </a>
</p>
