### 1
Kubernetes. Поддерживает контейнеризацию, есть возможность автоматического масштабирования(autoscaling), можно хранить непосредственно в нем как переменные sensitive value, 
есть разграничениеи на зоны- Namespaces. также большое количество документации.



### Доработка




Horizontal Pod Autoscaler тоже присутствует в к8s, HPA автоматически регулирует количество подов в зависимости от нагрузки на цпу и память, значения можно устанавливать, соответсвенно либо уменьшает, либо увеличивает автоматически исходя из введеных данных в конфиг

ingress это правила маршрутизации внешнего трафика к кластеру, работает в паре с ingress контроллером. например, можно настроить hpa при увеличении количества трафика

HashiCorp Vault- инструмент  для хранения сенситив данных(пароли, адреса и прочее, что не хочется или нельзя светить в контейнерах, в перменных) у K8s есть собственная сущность дя реализации подобных задач - secrets 


