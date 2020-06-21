<script>
    let FacebookImage = "https://scontent.fcul1-1.fna.fbcdn.net/v/t1.0-9/p960x960/72705075_1476187102519867_2945792960224034816_o.jpg?_nc_cat=106&_nc_sid=85a577&_nc_eui2=AeG47U_0ZD5vrINZlwHi0BKTVh_QhxdIC8xWH9CHF0gLzLrWqwy1mAFr1OX_h1Pr3zGM6L9XyurPiHSpJtMsftqZ&_nc_ohc=A-II4bKofOAAX8niEQR&_nc_ht=scontent.fcul1-1.fna&_nc_tp=6&oh=ea69b4ff9826f0c16aab0bff2a575070&oe=5F132226";
</script>

<style>
  .Stories {
    border: 1px solid rgba(219, 219, 219, 1);
    border-radius: 4px;
    margin: 1em 0;
    padding: 0.5em 1em;
    background-color: white;
  }
  .Stories-item img {
    width: 32px;
    height: 32px;
    border-radius: 50%;
  }
  .Stories-item {
    display: flex;
    align-items: center;
    margin: 0 0 0.5em 0;
  }
  .Stories-item h2 {
    font-size: 14px;
    color: black;
    margin: 0 0 0 0.5em;
  }
  .Stories-item h2 span {
    display: block;
    font-size: 9px;
    text-transform: uppercase;
    color: gray;
  }
  .Stories-head {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 0.5em 0 0 0;
  }
  .Stories-head h2 {
    font-size: 12px;
    font-weight: 600;
  }
  .Stories-head span {
    font-size: 12px;
    font-weight: normal;
    color: black;
  }
  .Stories-items {
    margin: 0.5em 0 0.5em 0;
  }
  .Stories-item-box {
    width: 32px;
    height: 32px;
    border: double 2px transparent;
    border-radius: 100%;
    background-image: linear-gradient(#fff, #fff),
      radial-gradient(circle at top left, #f09433, #bc1888);
    background-origin: border-box;
    background-clip: content-box, border-box;
  }
</style>

<div class="Stories">
    <div class="Stories-content">
        <div class="Stories-head">
            <h2>Historias</h2>
            <span>Ver todas...</span>
        </div>
        <div class="Stories-items">
            <div class="Stories-item">
                <div class="Stories-item-box">
                    <img src={FacebookImage} alt="">
                </div>
                    <h2>EnriqueMendoza06 <span>10 hrs. antes</span></h2>
            </div>
        </div>
    </div>
</div>