# v1nc3nt.github.io
# Size Limit [![Cult Of Martians][cult-img]][cult]

<img src="https://ai.github.io/size-limit/logo.svg" align="right"
     alt="Size Limit logo by Anton Lovchikov" width="120" height="178">



#* **ES modules** and **tree-shaking** support.
#* Add Size Limit to **GitHub Actions**, **Circle CI** or another CI system
#  to know if a pull request adds a massive dependency.
#* **Modular** to fit different use cases: big JS applications
#  that use their own bundler or small npm libraries with many files.
#* Can calculate **the time** it would take a browser
#  to download and **execute** your JS. Time is a much more accurate
#  and understandable metric compared to the size in bytes.
#* Calculations include **all dependencies and polyfills**
#  used in your JS.

#<p align="center">
#  <img src="" alt="Size Limit CLI" width="738">
#</p>



# <p align="center">
 # <a href="https://evilmartians.com/?utm_source=size-limit">
 #   <img src="https://evilmartians.com/badges/sponsored-by-evil-martians.svg"
 #        alt="Sponsored by Evil Martians" width="236" height="54">
 # </a>
#</p>



sizeLimit([filePlugin, webpackPlugin], [filePath]).then(result => {
  result //=> { size: 12480 }
})
```
