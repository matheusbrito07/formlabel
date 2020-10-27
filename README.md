# formlabel



//html//

   <div class="formlabel">

        <label for="nome">NOME COMPLETO:</label><br>
        <input type="text" id="nome" class="labelfaleconosco" name="nome"><br><br>

        <label for="telefone">TELEFONE PARA CONTATO:</label><br>
        <input type="number" id="telefone" class="labelfaleconosco" name="pTelefone"><br><br>

        <label for="idade">IDADE:</label><br>
        <input type="number" id="idade" class="labelfaleconosco" name="pIdade"><br><br>

        <label for="email">E-MAIL:</label><br>
        <input type="text" id="email" class="labelfaleconosco" name="pEmail"><br><br>

        <label for="msg">MENSAGEM:</label><br>
        <textarea id="msg" class="labelfaleconosco" name="pMensagem" ></textarea><br><br>
        <input type="submit">
    </div>
    
    --------------------
    
    //CSS// 
    
.formlabel{
    text-align: center;
}

.labelfaleconosco{
    width: 15%; 
    height: 20px; 

}

#msg{ 
    width: 15%;
    height: 300px; 
}
