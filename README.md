eloqua-ruby-request
==================

Eloqua Ruby Request

## Usage

### GET
        require('eloqua-ruby-request')
        request = EloquaRequest.new('site', 'user', 'password', 'baseUrl')
        response = request.get('/assets/emails?search=Demand*&page=1&count=50&depth=minimal')

### POST
        require('eloqua-ruby-request')
        request = EloquaRequest.new('site', 'user', 'password', 'baseUrl')
        data = ...
        response = request.post('/assets/email', data)

### PUT
        require('eloqua-ruby-request')
        request = EloquaRequest.new('site', 'user', 'password', 'baseUrl')
        data = ...
        response = request.put('/assets/email/123', data)

### DELETE
        require('eloqua-ruby-request')
        request = EloquaRequest.new('site', 'user', 'password', 'baseUrl')
        response = request.delete('/assets/email/123')
        
