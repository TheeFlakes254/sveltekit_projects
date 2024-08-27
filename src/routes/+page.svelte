<style>
    body{
        font-family: Arial, Helvetica, sans-serif;
        background-color: #f7f7f7;
        margin: 0;
        padding: 0;
        display: flex;
        justify-content: center;
        align-items: center;
        height: 100vh;
    }

    .container{
        position: relative;
        text-align: center;
        padding: 20px;
        border-radius: 10px;
        box-shadow: 0 0 20px rgba(0, 0, 0, 0.1);
        overflow: hidden;
        width: 100%;
        height: 637px;
        box-sizing: border-box;
    }

    .container::before{
        content: "";
        position: absolute;
        top: 0;
        left: 0;
        width: 100%;
        height: 100%;
        background-image: url("WhatsApp Image 2024-08-07 at 11.42.41_28bd5e84.jpg");
        background-size: cover;
        background-position: center;
        opacity: 0.5;
        z-index: -1;
        border-radius: 10px;
    }

    h1{
        color: #2c7dc0;
        font-size:36px;
        margin-bottom: 20px;
    }

    .highlight{
        color: #e74c3c;
    }

    .donation-box{
        background-color: #d8f153;
        padding: 15px;
        border-radius: 16px;
        border:2px solid #000;
        display: inline-block;
        margin-top: 20px;
        width: 550px;
        height: 190px;
        box-shadow: 2px 5px 5px black;
    }

    .donation-box p{
        font-size: 16px;
        color: #333;
        margin-bottom: 10px;
    }

    .input-group{
        display: flex;
        align-items: center;
    }

    .input-group label{
        font-size: 16px;
        margin-right: 10px;
        align-items: center;
        font-weight: bolder;
        justify-content: space-between;
        gap: 10px;
    }

    .input-group label{
        font-size: 17px;
        margin-top: 100px;
        margin-left: 100px;
    }

    .currency{
        font-size: 16px;
        padding: 10px;
        background-color: #fff;
        border-radius: 15px 0 0 15px;
        border: 1px solid #ccc;
    }

    input[type="number"]{
        font-size: 16px;
        padding: 10px;
        border: 10px;
        border: 1px solid #ccc;
        border-radius: 0 15px 15px 0;
        width: 80px;
        outline: none;
        margin-right: 10px;
        }
    

    .donate-button{
        font-size: 16px;
        color: #fff;
        background-color: #e74c3c;
        padding: 10px 20px;
        border: none;
        border-radius: 19px;
        cursor: pointer;
        transition: background-color 0.3s ease;
    }

    .donate-button:hover{
        background-color: #c0392b;
    }
.support{
    color: #033964;
    font-weight: bolder;
    font-size: 20px;
}
    
</style>


<div class="container">
    <h1> Help Us Build a World Where <br/><span class="highlight">Every Child</span> Can Thrive</h1>
    <div class="donation-box">
        <div class="support">support us, by making a donation </div>
        <form id="donation-amount">
            <div class="input-group">
                <label for="donatio-amount"> i want to give</label>
                <span class="currency">$</span>
                <input type="number" id="donation-amount" placeholder="0.00" required>
                <button type="submit" class="donate-button">Donate</button>
            </div>
        </form>
    </div>
</div>