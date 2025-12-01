# lojabytonalize.
!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>TONALIZE - Base Líquida com Pump</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        :root {
            --tonalize-gold: #D4AF37;
            --tonalize-beige: #E8D5C5;
            --tonalize-brown: #8C6A57;
            --tonalize-light: #F9F5F2;
            --tonalize-dark: #5D4037;
            --tonalize-accent: #B8947A;
        }
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Avenir', 'Helvetica Neue', Helvetica, Arial, sans-serif;
        }
        
        body {
            background-color: var(--tonalize-light);
            color: var(--tonalize-dark);
            line-height: 1.6;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }
        
        /* HEADER COM LOGO TONALIZE */
        header {
            background: white;
            box-shadow: 0 2px 20px rgba(140, 106, 87, 0.08);
            position: sticky;
            top: 0;
            z-index: 1000;
        }
        
        .header-top {
            background: linear-gradient(90deg, var(--tonalize-brown), var(--tonalize-accent));
            color: white;
            padding: 8px 0;
            text-align: center;
            font-size: 0.85rem;
            letter-spacing: 0.5px;
        }
        
        .header-main {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 20px 0;
        }
        
        .logo-container {
            display: flex;
            flex-direction: column;
            align-items: center;
        }
        
        .logo {
            font-size: 2.8rem;
            font-weight: 800;
            color: var(--tonalize-brown);
            letter-spacing: 4px;
            text-transform: uppercase;
            margin-bottom: 5px;
        }
        
        .slogan {
            font-size: 0.9rem;
            color: var(--tonalize-accent);
            letter-spacing: 1.5px;
            text-align: center;
        }
        
        /* HERO SECTION */
        .hero {
            background: linear-gradient(rgba(255, 255, 255, 0.9), rgba(255, 255, 255, 0.7)), 
                        url('https://images.unsplash.com/photo-1596462502278-27bfdc403348?ixlib=rb-4.0.3&auto=format&fit=crop&w=1200&q=80');
            background-size: cover;
            background-position: center;
            padding: 80px 0;
            text-align: center;
            position: relative;
        }
        
        .hero-content {
            max-width: 800px;
            margin: 0 auto;
        }
        
        .hero h1 {
            font-size: 3.5rem;
            color: var(--tonalize-brown);
            margin-bottom: 20px;
            font-weight: 300;
        }
        
        .hero h1 strong {
            font-weight: 700;
        }
        
        .hero-subtitle {
            font-size: 1.8rem;
            color: var(--tonalize-accent);
            margin-bottom: 30px;
            font-weight: 300;
        }
        
        .hero-description {
            font-size: 1.1rem;
            max-width: 600px;
            margin: 0 auto 40px;
            color: var(--tonalize-dark);
        }
        
        /* EMBALAGEM DE PUMP */
        .pump-container {
            display: flex;
            justify-content: center;
            align-items: center;
            gap: 60px;
            margin: 60px 0;
            padding: 40px;
            flex-wrap: wrap;
        }
        
        .pump-bottle {
            width:…
