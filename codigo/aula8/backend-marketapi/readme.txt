Para esse projeto vamos usar :

    Express para a API
	Mongoose para o MongoDB
	JWT para autenticação
	Bcrypt para hash de senhas
	Dotenv para variáveis de ambiente

    Para instalar : npm install express mongoose bcryptjs jsonwebtoken dotenv

    Estrutura do projeto : 

    backend-market-api/
├── package.json
├── .env
├── server.js
├── config/
│   └── db.js
├── middleware/
│   └── authMiddleware.js
├── models/
│   ├── User.js
│   ├── Product.js
│   ├── Category.js
│   └── Order.js
├── controllers/
│   ├── authController.js
│   ├── productController.js
│   ├── categoryController.js
│   └── orderController.js
├── routes/
│   ├── authRoutes.js
│   ├── productRoutes.js
│   ├── categoryRoutes.js
│   └── orderRoutes.js