Required adding SCC
oc adm policy add-scc-to-user anyuid -z default --as=system:admin
https://github.com/minishift/minishift/issues/124

Directory for www files: /usr/share/nginx/html
