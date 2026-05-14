---
title: ""
layout: archive
permalink: /beyond-research/
redirect_from:
  - /hobbies/
  - /hobbies
---

<style>
  /* ===== SECTION HEADINGS ===== */
  .hobby-heading {
    color: #005E7A;
    font-size: 0.91rem;
    font-weight: 700;
    margin: 2 rem 0 0.9 rem;
    display: flex;
    align-items: center;
    gap: 9px;
  }

  .hobby-heading::after {
    content: '';
    flex: 1;
    height: 2px;
    background: linear-gradient(90deg, #005E7A22 0%, transparent 100%);
    border-radius: 2px;
  }

  /* ===== PHOTO GRID ===== */
  .photo-grid {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    gap: 14px;
    margin-bottom: 2rem;
  }

  @media (min-width: 700px) {
    .photo-grid {
      grid-template-columns: repeat(4, 1fr);
    }
  }

  .photo-grid__item {
    position: relative;
    border-radius: 12px;
    overflow: hidden;
    cursor: pointer;
    aspect-ratio: 1 / 1;
    box-shadow: 0 4px 12px rgba(31,58,95,0.1);
    transition: transform 0.22s ease, box-shadow 0.22s ease;
  }

  .photo-grid__item:hover {
    transform: translateY(-4px);
    box-shadow: 0 12px 28px rgba(0,94,122,0.22);
  }

  .photo-grid__item img {
    width: 100%;
    height: 100%;
    object-fit: cover;
    display: block;
    transition: transform 0.4s ease;
  }

  .photo-grid__item:hover img {
    transform: scale(1.06);
  }

  .photo-grid__overlay {
    position: absolute;
    inset: 0;
    background: linear-gradient(180deg, transparent 40%, rgba(0,30,50,0.55) 100%);
    opacity: 0;
    transition: opacity 0.3s ease;
    display: flex;
    align-items: flex-end;
    padding: 10px;
  }

  .photo-grid__item:hover .photo-grid__overlay {
    opacity: 1;
  }

  .photo-grid__zoom-icon {
    color: #fff;
    font-size: 1.2rem;
    margin-left: auto;
    opacity: 0.9;
  }

  /* ===== LIGHTBOX ===== */
  .lightbox {
    position: fixed;
    inset: 0;
    background: rgba(0,0,0,0.88);
    z-index: 2000;
    display: none;
    align-items: center;
    justify-content: center;
    padding: 20px;
    cursor: zoom-out;
  }

  .lightbox.is-open {
    display: flex;
  }

  .lightbox img {
    max-width: min(92vw, 900px);
    max-height: 88vh;
    border-radius: 12px;
    box-shadow: 0 20px 60px rgba(0,0,0,0.6);
    object-fit: contain;
    cursor: default;
  }

  .lightbox__close {
    position: absolute;
    top: 18px;
    right: 22px;
    background: rgba(255,255,255,0.15);
    border: none;
    color: #fff;
    font-size: 1.6rem;
    width: 42px;
    height: 42px;
    border-radius: 50%;
    cursor: pointer;
    line-height: 42px;
    text-align: center;
    transition: background 0.2s;
  }

  .lightbox__close:hover {
    background: rgba(255,255,255,0.28);
  }

  .lightbox__nav {
    position: absolute;
    top: 50%;
    transform: translateY(-50%);
    background: rgba(255,255,255,0.15);
    border: none;
    color: #fff;
    font-size: 1.8rem;
    width: 48px;
    height: 48px;
    border-radius: 50%;
    cursor: pointer;
    display: flex;
    align-items: center;
    justify-content: center;
    transition: background 0.2s;
  }

  .lightbox__nav:hover {
    background: rgba(255,255,255,0.28);
  }

  .lightbox__prev { left: 16px; }
  .lightbox__next { right: 16px; }

  /* ===== BOOK SHELF ===== */
  .book-shelf {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(110px, 1fr));
    gap: 16px;
    margin-bottom: 2rem;
  }

  .book-item {
    position: relative;
    border-radius: 6px;
    overflow: hidden;
    box-shadow: 3px 4px 14px rgba(31,58,95,0.15), -1px 0 0 #ddd;
    transition: transform 0.25s ease, box-shadow 0.25s ease;
    cursor: pointer;
    aspect-ratio: 2 / 3;
  }

  .book-item:hover {
    transform: translateY(-6px) rotate(-1.5deg);
    box-shadow: 6px 14px 28px rgba(0,94,122,0.22);
  }

  .book-item img {
    width: 100%;
    height: 100%;
    object-fit: cover;
    display: block;
  }

 
</style>

<h2 class="hobby-heading">📷 Photography</h2>

<div class="photo-grid" id="photoGrid">
  <div class="photo-grid__item" data-index="0">
    <img src="/images/photo1.jpeg" alt="Photography by Zeeshan">
    <div class="photo-grid__overlay"><span class="photo-grid__zoom-icon">⤢</span></div>
  </div>
  <div class="photo-grid__item" data-index="1">
    <img src="/images/photo2.jpeg" alt="Photography by Zeeshan">
    <div class="photo-grid__overlay"><span class="photo-grid__zoom-icon">⤢</span></div>
  </div>
  <div class="photo-grid__item" data-index="2">
    <img src="/images/photo3.jpeg" alt="Photography by Zeeshan">
    <div class="photo-grid__overlay"><span class="photo-grid__zoom-icon">⤢</span></div>
  </div>
  <div class="photo-grid__item" data-index="3">
    <img src="/images/photo4.jpeg" alt="Photography by Zeeshan">
    <div class="photo-grid__overlay"><span class="photo-grid__zoom-icon">⤢</span></div>
  </div>
</div>

<!-- Lightbox -->
<div class="lightbox" id="lightbox" role="dialog" aria-label="Photo viewer">
  <button class="lightbox__close" id="lightboxClose" aria-label="Close">&times;</button>
  <button class="lightbox__nav lightbox__prev" id="lightboxPrev" aria-label="Previous">&#8249;</button>
  <img src="" alt="Enlarged photo" id="lightboxImg">
  <button class="lightbox__nav lightbox__next" id="lightboxNext" aria-label="Next">&#8250;</button>
</div>

<h2 class="hobby-heading">📚 Books</h2>

<div class="book-shelf">
  <div class="book-item"><img src="/images/book2.jpg" alt="Book from personal reading list"></div>
  <div class="book-item"><img src="/images/book3.jpg" alt="Book from personal reading list"></div>
  <div class="book-item"><img src="/images/book4.jpg" alt="Book from personal reading list"></div>
  <div class="book-item"><img src="/images/book5.jpg" alt="Book from personal reading list"></div>
</div>



<script>
(function () {
  /* Photo Lightbox */
  const photos = Array.from(document.querySelectorAll('#photoGrid .photo-grid__item img')).map(function (img) {
    return img.src;
  });
  const lightbox = document.getElementById('lightbox');
  const lightboxImg = document.getElementById('lightboxImg');
  const closeBtn = document.getElementById('lightboxClose');
  const prevBtn = document.getElementById('lightboxPrev');
  const nextBtn = document.getElementById('lightboxNext');
  let currentIdx = 0;

  function openLightbox(idx) {
    currentIdx = idx;
    lightboxImg.src = photos[idx];
    lightbox.classList.add('is-open');
    document.body.style.overflow = 'hidden';
  }

  function closeLightbox() {
    lightbox.classList.remove('is-open');
    document.body.style.overflow = '';
  }

  function showPhoto(idx) {
    currentIdx = (idx + photos.length) % photos.length;
    lightboxImg.src = photos[currentIdx];
  }

  document.querySelectorAll('#photoGrid .photo-grid__item').forEach(function (item) {
    item.addEventListener('click', function () {
      openLightbox(parseInt(this.getAttribute('data-index'), 10));
    });
  });

  closeBtn.addEventListener('click', closeLightbox);
  prevBtn.addEventListener('click', function (e) { e.stopPropagation(); showPhoto(currentIdx - 1); });
  nextBtn.addEventListener('click', function (e) { e.stopPropagation(); showPhoto(currentIdx + 1); });

  lightbox.addEventListener('click', function (e) {
    if (e.target === lightbox) closeLightbox();
  });

  document.addEventListener('keydown', function (e) {
    if (!lightbox.classList.contains('is-open')) return;
    if (e.key === 'Escape') closeLightbox();
    if (e.key === 'ArrowLeft') showPhoto(currentIdx - 1);
    if (e.key === 'ArrowRight') showPhoto(currentIdx + 1);
  });
})();
</script>
