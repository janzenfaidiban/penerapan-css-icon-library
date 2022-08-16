# Penerapan CSS Icon di dalam dokumen HTML


```html

<html>
    <head>
        <title>Icon</title>
        <!-- BOOTSTRAP STYLE -->
        <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.0/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-gH2yIJqKdNHPEq0n4Mqa/HGKIhSkIHeL5AyhkYV8i59U5AR6csBvApHHNl/vI1Bx" crossorigin="anonymous">

        <!-- BOOTSTRAP ICON -->
        <link href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.9.1/font/bootstrap-icons.css" rel="stylesheet" >
        
        <!-- FONT AWESOME ICONS -->
        <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.1.2/css/all.min.css" rel="stylesheet" integrity="sha512-1sCRPdkRXhBV2PBLUdRb4tMg1w2YPf37qatUFeS7zlBy7jJI8Lf4VHwWfZZfpXtYSLy85pkm9GaYVYMfw5BC1A==" crossorigin="anonymous" referrerpolicy="no-referrer" />
    
    </head>
    <body>
        
        <!-- BOOTSTRAP ICON START -->
        <div class="border m-4 p-4">

            <div class="row">
                <div class="col-12">
                    <h1>Bootstrap Icons</h1>
                </div>
            </div>

            <div class="row">
                <div class="col-lg-4">
                    <a href="#" class="btn btn-success mx-1 w-100 mb-2">
                        <i class="bi bi-facebook me-1"></i>
                        Facebook
                    </a>
                </div>

                <div class="col-lg-4">
                    <a href="#" class="btn btn-success mx-1 w-100 mb-2">
                        <i class="bi bi-instagram me-1"></i>
                        Instagram
                    </a>
                </div>

                <div class="col-lg-4">
                    <a href="#" class="btn btn-success mx-1 w-100 mb-2">
                        <i class="bi bi-youtube me-1"></i>
                        Youtube
                    </a>
                </div>
            </div>
        </div>
        <!-- BOOTSTRAP ICON END -->

        <!-- FONT AWESOME ICON START -->
        <div class="border m-4 p-4">
            <div class="row">
                <div class="col-12">
                    <h1>Font Awesome Icons</h1>
                </div>
            </div>

            <div class="row">
                <!-- GOOGLE PLAY START -->
                <div class="col-lg-4 d-flex gap-3 border shadow p-4 my-4 rounded">

                    <div>
                        <i class="fa-brands fa-google-play display-1" style="font-size: 60px;"></i>
                    </div>

                    <div>
                        <p class="m-0">Download di</p>
                        <h3 class="fw-bolder">Google Play</h3>
                    </div>                  
                    
                </div>
                <!-- GOOGLE PLAY END -->
 
                <!-- APPLE STORE START -->
                <div class="col-lg-4 d-flex gap-3 border shadow p-4 my-4 rounded">

                    <div>
                        <i class="fa-brands fa-apple display-1" style="font-size: 60px;"></i>
                    </div>

                    <div class="">
                        <p class="m-0">Download di</p>
                        <h3 class="fw-bolder">App Store</h3>
                    </div>                  
                    
                </div>
                <!-- APPLE STORE END -->

                <!-- AMAZON PAY START -->
                <div class="col-lg-4 d-flex gap-3 border shadow p-4 my-4 rounded">

                    <div>
                        <i class="fa-brands fa-amazon-pay display-1" style="font-size: 60px;"></i>
                    </div>

                    <div>
                        <p class="m-0">Download di</p>
                        <h3 class="fw-bolder">Amazon Pay</h3>
                    </div>                  
                    
                </div>
                <!-- AMAZON PAY END -->
            </div>          

        </div>
        <!-- FONT AWESOME ICON END -->

        

    </body>
</html>

```
