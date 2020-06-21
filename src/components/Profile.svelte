<script>
    let FacebookImage = "https://scontent.fcul1-1.fna.fbcdn.net/v/t1.0-9/p960x960/72705075_1476187102519867_2945792960224034816_o.jpg?_nc_cat=106&_nc_sid=85a577&_nc_eui2=AeG47U_0ZD5vrINZlwHi0BKTVh_QhxdIC8xWH9CHF0gLzLrWqwy1mAFr1OX_h1Pr3zGM6L9XyurPiHSpJtMsftqZ&_nc_ohc=A-II4bKofOAAX8niEQR&_nc_ht=scontent.fcul1-1.fna&_nc_tp=6&oh=ea69b4ff9826f0c16aab0bff2a575070&oe=5F132226";

    export let nickname;
    export let name; 

</script>

<style>
  .Profile-content {
    display: flex;
    align-items: center;
  }
  .Profile-avatar img {
    width: 42px;
    height: 42px;
    border-radius: 50%;
  }
  .Profile-info {
    margin: 0 0 0 0.5em;
  }
  .Profile-info h2 {
    font-size: 14px;
    color: black;
    margin: 0;
    padding: 0;
  }
  .Profile-info span {
    font-size: 12px;
    font-weight: normal;
  }
</style>

<div class="Profile">
    <div class="Profile-content">
        <div class="Profile-avatar">
            <img src={FacebookImage} alt="">        
        </div>
        <div class="Profile-info">
            <h2>{nickname}</h2>
            <span>{name}</span>
        </div>
    </div>
</div>