<body>
    <!--crear la parte del encabezado-->
    <div class="home-wrapper">
        <!--encabezado-->
        <header>
            <div class="container">
                <!--logo--
                <img src="images/yosoylogo.jpg" width="170px" height="85px">-->

                <h6>"Tigo Hogar"</h6>

                <!--menu-->
                <nav>
                    <!--Anclajes con nombres-->
                    <a href="#home">INICIO</a>
                    <a href="#servicios">SERVICIOS</a>
                    <a href="#contacto">CONTACTO</a>
                </nav>
            </div>
        </header>
        <!--fin del logo y menu-->
        <!--seccion home-->
        <section class="container" id="home">
            <i><h2>Tigo</h2></i>
            <div class="divider"></div>
            <p>¡Para que siempre estes conectado!</p>
            <!--redes sociales-->
            <div class="social">
                <a href="https://www.facebook.com/login/device-based/regular/login/?login_attempt=1&lwv=110" target="_blank"><i class="fab fa-facebook-f" aria-hidden="true"></i></a>
                <a href="https://www.instagram.com/" target="_blank"><i class="fab fa-instagram" aria-hidden="true"></i></a>
                <a href="https://twitter.com/home?lang=es" target="_blank"><i class="fab fa-twitter" aria-hidden="true"></i></a>
            </div>
        </section>
    </div><br>
    <!--servicios-->
    <section class="container" id="servicios">
        <h2>Servicios</h2>
        <!--los servicios estarán divididos en tres columnas-->
        <!--primer servicio-->
        <div class="box">
            <h3>HOGAR </h3>
            <!--insertar una imagen de un servicio-->
            <img src="images/LOGO2023 BENNY.jpg" width="50%"><br><br>
            <img src="images/Imagen de WhatsApp 2023-01-18 a las 14.32.2.jpg" width="50%"><br><br>

            <p class="homefg"> <b>Trabajamos para que estes siempre conectado!</b></p>
        </div>
        <!--formulario de contacto-->
        <section id="contacto">
            <!--primer elemento de un formulario es la etiqueta form-->
            <h2>Contacto</h2>
            <form action="deibyjob@hotmail.com" method="POST">
                <!--insertar los input o campos de texto-->
                <div class="campo"><input type="text" placeholder="Escribir Nombre" required></div>
                <div class="campo"><input type="text" placeholder="Escribir Apellido" required></div>
                <div class="campo"><input type="email" placeholder="Escribir Email" required></div>

                <div class="campo"><select name="ciudad" id="">
                <option value="seleccion">Seleccionar</option>
                <option value="Medellin">Medellín</option>
                <option value="Cali">Cali</option>
                <option value="Bogota">Bogotá</option>                
            </select></div>
                <div class="campo"><input type="text" placeholder="Escribir celular" required></div>
                <div class="campo"><textarea name="" id="" cols="30" rows="10" placeholder="Observaciones"></textarea></div>
                <div class="campo">
                    <button type="submit" name="button" class="btn btn-success">Enviar(Send)</button>
                    <button type="reset" name="reset" class="btn btn-danger">Cancelar</button>
                </div>

            </form>
            <a href="https://api.whatsapp.com/send?phone=573012578319" class="btn-wsp" target="_blank">
                <i class="fa fa-whatsapp icono"></i>
            </a>
        </section>
        <div class="contactame">
            <h5>Contactame por WhatsApp.Te Comunico con un Asesor <br>TIGO HOGAR</h5>

        </div><br>
        <!--pie de página-->
        <footer class="cover">
            &copy;2023 <strong>tigo hogar</strong>, Todos los derechos Reservados. Diseño por <a href="#">Juan Duarte</a>
        </footer>
</body>

</html>
