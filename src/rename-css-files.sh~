find . -type f -name '*.module.css' -delete
find . -type f -name '*.css' -exec rename 's/\.css/\.module.css/g' '{}' \;
find . -type f -name 'index.module.css' -exec rename 's/\.module.css/\.css/g' '{}' \;
find ./ -type f -name '*.js' -exec sed -i -e 's/\.css/\.module.css/g' {} \;
find ./ -type f -name 'index.js' -exec sed -i -e 's/\.module.css/\.css/g' {} \;
