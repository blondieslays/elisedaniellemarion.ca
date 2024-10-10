---
title: "Pandora Gallery"
description: "Pandora, the first woman in Greek mythology, opened a jar that unleashed all evils into the world. Yet hope remained."
weight: 3  # Pandora comes after Epimetheus
type: "gallery"
date: 2024-10-07
images:
  - front: "/images/pandora/pyxis.png"
    back: "/images/pandora/back1.png"
    link: "/gallery/pandora/pyxis"
  - front: "/images/pandora/kakon.png"
    back: "/images/pandora/back2.png"
    link: "/gallery/pandora/kakon"
  - front: "/images/pandora/elpis.png"
    back: "/images/pandora/back3.png"
    link: "/gallery/pandora/elpis"
navigation_images:
  left: "/images/arrow-left.png"
  right: "/images/arrow-right.png"
---

<!-- Gallery Content -->
<div class="image-tile-container">
    <!-- Tile 1 -->
    <div class="tile">
        <div class="tile-inner">
            <div class="tile-front">
                <img src="/images/pandora/pyxis.png" alt="Pandora Front Image 1">
            </div>
            <div class="tile-back">
                <img src="/images/pandora/back1.png" alt="Pandora Back Image 1">
            </div>
        </div>
    </div>
    
    <!-- Tile 2 -->
    <div class="tile">
        <div class="tile-inner">
            <div class="tile-front">
                <img src="/images/pandora/kakon.png" alt="Pandora Front Image 2">
            </div>
            <div class="tile-back">
                <img src="/images/pandora/back2.png" alt="Pandora Back Image 2">
            </div>
        </div>
    </div>
    
    <!-- Tile 3 -->
    <div class="tile">
        <div class="tile-inner">
            <div class="tile-front">
                <img src="/images/pandora/elpis.png" alt="Pandora Front Image 3">
            </div>
            <div class="tile-back">
                <img src="/images/pandora/back3.png" alt="Pandora Back Image 3">
            </div>
        </div>
    </div>

<div class="gallery-navigation">
    <a href="{{ .Prev.Permalink }}" class="nav-button left">
        <img src="{{ .Params.navigation_images.left }}" alt="Previous">
    </a>

    <img src="/images/bow-image.png" alt="Bows" class="bow-image"> <!-- Bow image -->
    
    <a href="{{ .Next.Permalink }}" class="nav-button right">
        <img src="{{ .Params.navigation_images.right }}" alt="Next">
    </a>    
</div>

</div>
