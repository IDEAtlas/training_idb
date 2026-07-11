---
layout: default
title: Notebooks
parent: Lab
nav_order: 3
---

# Mapping Workflow Notebooks

<style>
  .notebook-card {
    border: 1px solid #e0e0e0;
    border-radius: 8px;
    padding: 20px;
    margin: 20px 0;
    background-color: #f9f9f9;
    box-shadow: 0 2px 4px rgba(0,0,0,0.1);
  }
  
  .notebook-title {
    font-size: 18px;
    font-weight: 600;
    margin: 0 0 10px 0;
    color: #1f2937;
  }
  
  .notebook-description {
    color: #6b7280;
    margin-bottom: 15px;
    font-size: 14px;
  }
  
  .button-group {
    display: flex;
    gap: 10px;
    flex-wrap: wrap;
  }
  
  .btn {
    display: inline-block;
    padding: 10px 20px;
    border-radius: 6px;
    border: none;
    font-size: 14px;
    font-weight: 600;
    text-decoration: none;
    cursor: pointer;
    transition: all 0.3s ease;
  }
  
  .btn-notebook {
    background-color: #e8f0fe;
    color: #1f2937;
    border: 2px solid #1f2937;
  }
  
  .btn-notebook:hover {
    background-color: #d2e3fc;
    transform: translateY(-2px);
  }
  
  .btn-launch {
    background-color: #ff8c42;
    color: white;
  }
  
  .btn-launch:hover {
    background-color: #ff7a1f;
    transform: translateY(-2px);
  }
</style>

<div class="notebook-card">
  <div class="notebook-title">DUA Mapping Workflow</div>
  <div class="notebook-description">
    End-to-end mapping pipeline including data preparation, model training, inference, and indicator derivation
  </div>
  <div class="button-group">
    <a href="https://github.com/IDEAtlas/ai-dua-mapping/blob/main/DUA_mapping.ipynb" class="btn btn-notebook">📓 Notebook</a>
    <a href="https://mybinder.org/v2/gh/IDEAtlas/ai-dua-mapping/HEAD" target="_blank" class="btn btn-launch">🚀 Launch</a>
  </div>
</div>

**Note:** Please ensure all required data is placed in the corresponding folders as outlined in the IDEAtlas user handbook.
