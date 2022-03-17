helm upgrade -i --set container.image="constantinre.dev/users-api:1.0.0" users-api ./charts/users-api
helm upgrade -i --set container.image="constantinre.dev/users-ui:1.0.0" users-ui ./charts/users-ui
