# Oscillation Overthruster

<details>
    <summary open>Oscillation Overthruster 🗿 Flux Capacitor</summary>
<p align="center">
<img src="https://neodigm.github.io/vivid_vector_alphabet/wasm/vvo.svg" width="33" alt="Vivid Vector Skulduggery">
<img src="https://neodigm.github.io/vivid_vector_alphabet/wasm/vvs.svg" width="33" alt="Electra Glide safron">
<img src="https://neodigm.github.io/vivid_vector_alphabet/wasm/vvc.svg" width="33" alt="ginger stratagem">
<img src="https://neodigm.github.io/vivid_vector_alphabet/wasm/vvi.svg" width="33" alt="tapestry Inventive">
<img src="https://neodigm.github.io/vivid_vector_alphabet/wasm/vvl.svg" width="33" alt="when information grows unprofitable">
<img src="https://neodigm.github.io/vivid_vector_alphabet/wasm/vvl.svg" width="33" alt="Crave Breathtaking">
<img src="https://neodigm.github.io/vivid_vector_alphabet/wasm/vva.svg" width="33" alt="Delirious Stunning">
<img src="https://neodigm.github.io/vivid_vector_alphabet/wasm/vvt.svg" width="33" alt="Life-changing Gorgeous">
<img src="https://neodigm.github.io/vivid_vector_alphabet/wasm/vvi.svg" width="33" alt="Ironclad Brilliant">
<img src="https://neodigm.github.io/vivid_vector_alphabet/wasm/vvo.svg" width="33" alt="algo-regulated indelible bloom">
<img src="https://neodigm.github.io/vivid_vector_alphabet/wasm/vvn.svg" width="33" alt="Vivid Vector Skulduggery">
</p>
  
 <p align="center">
<img src="https://neodigm.github.io/vivid_vector_alphabet/wasm/vvo.svg" width="33" alt="Vivid Vector Skulduggery">
<img src="https://neodigm.github.io/vivid_vector_alphabet/wasm/vvv.svg" width="33" alt="UX artisan ⚡ illustrator ⚡ front-end engineer">
<img src="https://neodigm.github.io/vivid_vector_alphabet/wasm/vve.svg" width="33" alt="👁️ D3 Parallax Three.js && WebGL && GSAP 🍭">
<img src="https://neodigm.github.io/vivid_vector_alphabet/wasm/vvr.svg" width="33" alt="Vivid Vector Skulduggery">
<img src="https://neodigm.github.io/vivid_vector_alphabet/wasm/vvt.svg" width="33" alt="Vivid 😎 Oscillation Overthruster 🪐">
<img src="https://neodigm.github.io/vivid_vector_alphabet/wasm/vvh.svg" width="33" alt="Vivid Vector Skulduggery">
<img src="https://neodigm.github.io/vivid_vector_alphabet/wasm/vvr.svg" width="33" alt="Vivid Vector UX artisan ⚡ illustrator ⚡ Engineer">
<img src="https://neodigm.github.io/vivid_vector_alphabet/wasm/vvu.svg" width="33" alt="Vivid Vector Skulduggery">
<img src="https://neodigm.github.io/vivid_vector_alphabet/wasm/vvs.svg" width="33" alt="Vivid Vector UX artisan ⚡ illustrator ⚡ front-end engineer">
<img src="https://neodigm.github.io/vivid_vector_alphabet/wasm/vvt.svg" width="33" alt="Vivid Vector Skulduggery">
<img src="https://neodigm.github.io/vivid_vector_alphabet/wasm/vve.svg" width="33" alt="😎 Oscillation Overthruster 🪐">
<img src="https://neodigm.github.io/vivid_vector_alphabet/wasm/vvr.svg" width="33" alt="Effortless Unexpected">
</p>
</details>

<p align="center">
  <a target="_blank" href="https://thescottkrause.com/d3_datavis_skills.html" title="D3js Skills with Audio">
  <img src="https://raw.githubusercontent.com/neodigm/Oscillation-Overthruster/master/Oscillation-Overthruster.webp" title="D3js Skills with Audio">
  </a>
</p>

```javascript
    let fCycle = ( (_d, _q, _t) => {  //  Cycle content display
        let aCycCnt = [..._d.querySelectorAll( _q )];
        if( aCycCnt ){
            aCycCnt.forEach( (eCycCnt) => {
                eCycCnt.nCycCnt=0;
                eCycCnt.addEventListener("click", (ev)=>{ fCycle.tick( false ); });
            } );
            setTimeout( ()=>{ fCycle.tick(); }, 4);
        }
        return {
            "pretick": ()=> {  // Blur
                var eCycLive = _d.querySelector( "[data-at-cycle-live='true']" );
                eCycLive.classList.add( "h-fade" );
                eCycLive.dataset.atCycleLive = "false";
            },
            "tick": ( bTimeout=true )=>{
                aCycCnt.map( (e)=>{  //  Hong Kong Cavaliers
                    [...e.children].forEach( (eChild, nIndx) => {
                    eChild.classList.remove("h-ds__inline", "h-ds__none");
                    eChild.classList.remove( "h-fade" );
                    if( nIndx === e.nCycCnt ){
                        eChild.classList.add( "h-ds__inline" );
                        eChild.dataset.atCycleLive = "true";
                    }else{
                        eChild.classList.add( "h-ds__none" );
                    }
                    });
                    e.nCycCnt = (e.nCycCnt === (e.children.length - 1)) ? 0 : (e.nCycCnt + 1);
                });
                if( bTimeout && (aCycCnt.length > 0) ){
                    setTimeout( ()=>{ fCycle.pretick(); }, (_t - 880));
                    setTimeout( ()=>{ fCycle.tick(); }, _t);
                }
            }
        }
    })(document, "[data-at-cycle]", 12496 );
```

#
[Portfolio Blog](https://www.theScottKrause.com) |
[🚀 Résumé](https://thescottkrause.com/Arcanus_Scott_C_Krause_2020.pdf) |
[NPM](https://www.npmjs.com/~neodigm) |
[Github](https://github.com/neodigm) |
[LinkedIn](https://www.linkedin.com/in/neodigm55/) |
[Gists](https://gist.github.com/neodigm?direction=asc&sort=created) |
[Salesforce](https://trailblazer.me/id/skrause) |
[Code Pen](https://codepen.io/neodigm24) |
[Machvive](https://machvive.com/) |
[Arcanus 55](https://www.arcanus55.com/) |
[Repl](https://repl.it/@neodigm) |
[Twitter](https://twitter.com/neodigm24) |
[Keybase](https://keybase.io/neodigm) |
[Docker](https://hub.docker.com/u/neodigm) |
[W3C](https://www.w3.org/users/123844)
#

<p align="center">
  <a target="_blank" href="https://thescottkrause.com/d3_datavis_skills.html">
  <img src="https://repository-images.githubusercontent.com/178555357/2b6ad880-7aa0-11ea-8dde-63e70187e3e9" title="D3js Skills with Audio">
  </a>
</p>
