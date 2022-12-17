<ul>
  <li>
    <a href="https://gorositostudio.com" target="_blank" rel="noreferrer">
      Studio
    </a>
  </li>
  <li>
    <a href="https://turnos.gorositostudio.com" target="_blank" rel="noreferrer">
      Turnos
    </a>
  </li>
  <li>
    <a href="https://tienda.gorositostudio.com" target="_blank" rel="noreferrer">
      Tienda
    </a>
  </li>
  <li>
    <a href="https://cursos.gorositostudio.com" target="_blank" rel="noreferrer">
      Cursos 
    </a>
  </li>
</ul>

<style>
  @keyframes appear {
    0% {
      opacity: 0;
      transform: translateY(30%) 
    }
    100% {
      opacity: 1;
      transform: translateY(0) 
    }
  }

  @keyframes appearSide {
    0% {
      opacity: 0;
      transform: translateX(-30%) 
    }
    100% {
      opacity: 1;
      transform: translateX(0) 
    }
  }

  ul {
    display:flex;
    flex-direction: column;
    gap: 5vh;
    align-items:center;
    margin-block: 10vh 0;
  }

  ul li {
    font-size: 1.5rem;
    font-weight:500;
    width:min(80vw, 600px);
    text-align:center;
    padding: 1.25rem;
    border: 1px solid white;
    border-radius: 5rem;
    cursor:pointer;
    background: #222;
    transition: all .2s ease;
  }

  ul li:nth-child(odd) {
    animation: .5s appear linear;
  }

  ul li:nth-child(even) {
    animation: .5s appearSide linear;
  }

  ul li:hover {
    background: #ff6f20;
    color: #222;
    transform: scale(1.1);

  }
</style>