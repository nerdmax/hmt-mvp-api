# Create meeting

{% api-method method="post" host="https://api.hmt.com" path="/v1/meeting" %}
{% api-method-summary %}
Create meeting
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

{% api-method-query-parameters %}
{% api-method-parameter name="agendas" type="array" required=false %}
The meeting agendas
{% endapi-method-parameter %}

{% api-method-parameter name="music" type="string" required=false %}
The meeting music
{% endapi-method-parameter %}

{% api-method-parameter name="duration" type="string" required=false %}
The meeting duration
{% endapi-method-parameter %}

{% api-method-parameter name="time" type="number" required=false %}
The meeting time
{% endapi-method-parameter %}

{% api-method-parameter name="location" type="string" required=false %}
The meeting location
{% endapi-method-parameter %}

{% api-method-parameter name="objective" type="string" required=false %}
The meeting objective
{% endapi-method-parameter %}

{% api-method-parameter name="name" type="string" required=false %}
The meeting name
{% endapi-method-parameter %}
{% endapi-method-query-parameters %}
{% endapi-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}
{% endapi-method-response-example-description %}

```
{
  "id": "created meeting id"
}

```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}



