# Інструкція з використання:

Збережіть цей скрипт у файл з назвою kubeplugin у директорію /usr/local/bin/
Встановити дозвіл на виконання sudo chmod +x /usr/local/bin/kubeplugin

Використовуйте плагін kubeplugin таким чином:

bash kubeplugin <namespace> <resource_type>
Замініть <namespace> та <resource_type> на власні значення. 
Наприклад:

bash kubeplugin kube-system pods

Скрипт виведе статистику використання ресурсів для кожного ресурсу вказаного типу у вказаному просторі імен Kubernetes у форматі Resource, Namespace, Name, CPU, Memory.

Переконайтеся, що ви правильно налаштували зв'язок з вашим кластером Kubernetes, а потім протестуйте плагін на реальному кластері.
