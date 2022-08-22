# WP plugin with react
npm init -y

add scripts
"build": "wp-scripts build",
"start": "wp-scripts start",

npm install @wordpress/scripts --save

run in web console
wp.data.select("core/block-editor").getBlocks()