Change the rules to:
RewriteEngine On
RewriteBase /
options +FollowSymLinks
RewriteCond %{REQUEST_FILENAME} !-f
RewriteRule .* server.php/$0 [L]
