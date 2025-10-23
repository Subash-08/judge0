FROM judge0/judge0:1.13.0

# Set environment variables
ENV RAILS_ENV=production
ENV JUDGE0_SAVE_COMPILE_OUTPUT=true
ENV JUDGE0_ALLOW_ORIGIN=*

# Expose port
EXPOSE 3000

# Use the default command from the image
CMD ["/bin/bash", "-c", "rm -f /app/tmp/pids/server.pid && bundle exec rails s -b 0.0.0.0 -p 3000"]
