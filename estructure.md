PHP-MVC/
├── app/
│   ├── controllers/
│   │   ├── AppointmentController.php
│   │   ├── PatientController.php
│   │   ├── DoctorController.php
│   │   ├── ClinicController.php       // Nuevo
│   │   ├── AdminController.php        // Nuevo
│   │   └── AuthController.php         // Nuevo
│   ├── models/
│   │   ├── Appointment.php
│   │   ├── Doctor.php
│   │   ├── Patient.php
│   │   ├── Schedule.php
│   │   ├── Speciality.php
│   │   ├── MedicalHistory.php
│   │   ├── Clinic.php                 // Nuevo
│   │   ├── Admin.php                  // Nuevo
│   │   └── User.php                   // Nuevo
│   ├── views/
│   │   ├── appointments/
│   │   │   ├── index.php
│   │   │   ├── create.php
│   │   │   └── edit.php
│   │   ├── patients/
│   │   │   ├── index.php
│   │   │   ├── create.php
│   │   │   └── edit.php
│   │   ├── doctors/
│   │   │   ├── index.php
│   │   │   ├── create.php
│   │   │   └── edit.php
│   │   ├── clinics/                   // Nuevo
│   │   │   ├── index.php
│   │   │   ├── create.php
│   │   │   └── edit.php
│   │   ├── admins/                    // Nuevo
│   │   │   ├── index.php
│   │   │   ├── create.php
│   │   │   └── edit.php
│   │   ├── auth/                      // Nuevo
│   │   │   ├── login.php
│   │   │   ├── register.php
│   │   │   └── logout.php
│   │   └── layouts/
│   │       ├── header.php
│   │       └── footer.php
│   ├── core/
│   │   ├── App.php
│   │   ├── Controller.php
│   │   ├── Database.php
│   │   └── Auth.php                   // Nuevo
│   └── init.php
├── public/
│   ├── css/
│   │   └── styles.css
│   ├── js/
│   │   └── scripts.js
│   └── index.php
├── .htaccess
├── composer.json
└── README.md