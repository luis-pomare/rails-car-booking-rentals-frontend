luis@LAPTOP-3BICV8G1:~/rails-car-booking-rentals-backend$ rails routes | grep api
rswag_ui /api-docs Rswag::Ui::Engine
rswag_api /api-docs Rswag::Api::Engine
api_v1_cars GET /api/v1/cars(.:format) api/v1/cars#index
POST /api/v1/cars(.:format) api/v1/cars#create
api_v1_car GET /api/v1/cars/:id(.:format) api/v1/cars#show
PATCH /api/v1/cars/:id(.:format) api/v1/cars#update
PUT /api/v1/cars/:id(.:format) api/v1/cars#update
DELETE /api/v1/cars/:id(.:format) api/v1/cars#destroy
api_v1_user_reservations GET /api/v1/users/:user_username/reservations(.:format) api/v1/reservations#index
POST /api/v1/users/:user_username/reservations(.:format) api/v1/reservations#create
api_v1_user_reservation DELETE /api/v1/users/:user_username/reservations/:id(.:format) api/v1/reservations#destroy
api_v1_users POST /api/v1/users(.:format) api/v1/users#create
api_v1_user GET /api/v1/users/:username(.:format) api/v1/users#show
DELETE /api/v1/users/:username(.:format) api/v1/users#destroy
luis@LAPTOP-3BICV8G1:~/rails-car-booking-rentals-backend$
