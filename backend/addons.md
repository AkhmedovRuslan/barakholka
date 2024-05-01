dotenvy = "0.15.6"
sea-orm = { version = "0.12.14", features = ["sqlx-mysql", "runtime-tokio-rustls", "macros"] }
tokio = { version = "1.37.0", features = ["full", "macros", "rt-multi-thread"] }
axum = { version = "0.7.5", features = ["full"] }
serde = { version = "1.0.147", features = ["derive"] }
tower-http = { version = "0.3.4", features = ["cors"] }
validator = { version = "0.16.1", features = ["derive"] }
serde_with = "3.6.0"
chrono = "0.4.34"
bcrypt = "0.15.0"
jsonwebtoken = "9.2.0"