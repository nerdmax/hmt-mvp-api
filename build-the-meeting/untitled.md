# Get all meetings

{% api-method method="get" host="https://api.hmt.com" path="/v1/meeting" %}
{% api-method-summary %}
Get all meetings
{% endapi-method-summary %}

{% api-method-description %}
{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}
{% api-method-headers %}
{% api-method-parameter name="Authentication" type="string" required=true %}
Authentication token to track down who is emptying our stocks.
{% endapi-method-parameter %}
{% endapi-method-headers %}
{% endapi-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}
{% endapi-method-response-example-description %}

```
{
  "meetings": [
    { "id": "id 1", "name": "meeting 1", "status": "upcoming" },
    { "id": "id 2", "name": "meeting 2", "status": "upcoming" },
    { "id": "id 3", "name": "meeting 3", "status": "past" },
    { "id": "id 4", "name": "meeting 4", "status": "past" }
  ]
}
```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}



