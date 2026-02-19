---
layout: page
title: Mine Systemer
icon: fas fa-diagram-project
order: 4
---

<div class="row g-4 mt-2">
  <div class="col-md-6">
    <div class="card h-100 shadow-sm border-0" style="border-radius: 12px; background-color: var(--card-bg); transition: transform 0.2s ease;">
      <div class="card-body d-flex flex-column">
        <div class="mb-3">
          <h3 class="card-title h4 mb-1" style="color: var(--link-color);">Fjerdedel-systemet</h3>
          <span class="badge badge-system">Langbal</span>
        </div>
        <div class="custom-scroll mb-4" style="max-height: 120px; overflow-y: auto;">
          <p class="card-text text-muted small pe-2">
            Her finder du nogle brugbare grundlinjer, som du kan bruge, når du skal spille langbal, men er i tvivl om, hvor du skal ramme.
          </p>
        </div>
        <div class="mt-auto">
          <a href="/posts/Fjerdedel-systemet-til-langbal" class="btn btn-sm btn-custom-outline w-100 rounded-pill shadow-sm">
            <i class="fas fa-eye me-2"></i> Se systemet
          </a>
        </div>
      </div>
    </div>
  </div>
</div>

<style>
  .btn-custom-outline {
    border: 2px solid #007bff !important;
    color: #007bff !important;
    background-color: transparent !important;
    font-weight: 600 !important;
  }
  
  .btn-custom-outline:hover {
    background-color: #007bff !important;
    color: #fff !important;
    transform: translateY(-2px);
  }

  .badge-system {
    background-color: rgba(0, 123, 255, 0.15) !important;
    border: 1px solid #007bff !important;
    color: #007bff !important;
    padding: 0.4em 0.8em !important;
    font-size: 0.75rem !important;
    border-radius: 50px !important;
  }

  .card:hover {
    transform: translateY(-5px);
    box-shadow: 0 8px 15px rgba(0,0,0,0.1) !important;
  }

  .custom-scroll::-webkit-scrollbar {
    width: 4px;
  }
  .custom-scroll::-webkit-scrollbar-track {
    background: transparent;
  }
  .custom-scroll::-webkit-scrollbar-thumb {
    background-color: rgba(0,0,0,0.1);
    border-radius: 10px;
  }
  [data-theme="dark"] .custom-scroll::-webkit-scrollbar-thumb {
    background-color: rgba(255,255,255,0.2);
  }
</style>