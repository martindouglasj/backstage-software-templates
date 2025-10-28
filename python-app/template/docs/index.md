# ${{ values.app_name }}
This is a Python app that displays the current time. It has two endpoints:
- `/api/v1/info`
- `/api/v1/healthz`

Access the app at `${{ values.app_name }}-${{ values.app_env }}.test.com/api/v1/info`