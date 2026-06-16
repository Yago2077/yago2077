<div class="profile-container">
  <div class="profile-header">
    <img src="https://github.com/user-attachments/assets/486a1463-6a18-4d51-a7d5-aca9fc7ecafe" alt="gif do zenitsu" class="profile-img">
    
    <div class="profile-text">
      <p>🖖 Olá, meu nome é <strong>Yago Diehl</strong>, resido em Campinas-SP e possuo experiência em programação, com foco em desenvolvimento <strong>Front-End</strong> e <strong>Back-End</strong>. Atualmente buscando um emprego!</p>
      <p>Meus objetivos são: me aprimorar, obter mais conhecimento e desenvolver novos projetos!</p>
    </div>
  </div>

  <hr class="divider">

  <div class="profile-info">
    <p>👾 <strong>Linguagens:</strong> HTML5 / CSS3 / Java / NodeJS / Python</p>
    <p>💼 <strong>Ferramentas:</strong> Visual Studio Code</p>
  </div>
</div>

<style>
  .profile-container {
    font-family: sans-serif;
    max-width: 800px;
    margin: 0 auto;
    padding: 20px;
    color: #333;
  }

  .profile-header {
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 20px;
  }

  .profile-img {
    width: 180px;
    height: auto;
    border-radius: 8px;
  }

  .profile-text p {
    font-size: 16px;
    line-height: 1.6;
    margin-bottom: 10px;
  }

  .divider {
    border: 0;
    height: 1px;
    background: #ccc;
    margin: 25px 0;
  }

  .profile-info p {
    font-size: 16px;
    margin-bottom: 10px;
  }

  @media (min-width: 600px) {
    .profile-header {
      flex-direction: row;
      align-items: flex-start;
    }
    
    .profile-img {
      width: 200px;
    }
  }
</style>
