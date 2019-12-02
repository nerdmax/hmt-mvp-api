# Get one meeting

{% api-method method="get" host="https://api.hmt.com" path="/v1/meeting/123" %}
{% api-method-summary %}
Get one meeting
{% endapi-method-summary %}

{% api-method-description %}
{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}
{% api-method-path-parameters %}
{% api-method-parameter name="id" type="string" required=true %}
The required meeting id
{% endapi-method-parameter %}
{% endapi-method-path-parameters %}

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
  "id": "123",
  "name": "meeting name",
  "objective": "meeting objective",
  "location": "meeting location",
  "time": 100,
  "duration": "meeting duration",
  "music": "meeting music",
  "agendas": [
    {
      "id": "user id 1",
      "name": "user name",
      "time": 10,
      "content": {
        "type": "image",
        "resources": { "source": "https://via.placeholder.com/150" }
      }
    }
  ]
}
```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}



