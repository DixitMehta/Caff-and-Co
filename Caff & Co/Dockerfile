FROM httpd:2.4

# Remove default content
RUN rm -rf /usr/local/apache2/htdocs/*

# Copy your website files
COPY . /usr/local/apache2/htdocs/

EXPOSE 80