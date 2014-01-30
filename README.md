##Rails HTTP Status Codes

Since there wasn't a nicely formatted list with descriptions around, here's the available status codes.

This is based off of the codes defined in [Rack::Utils](https://github.com/rack/rack/blob/master/lib/rack/utils.rb#L549)

---

#####1xx Informational
    Status   Symbol                           Description
    ------------------------------------------------------------
    100      :continue                        Continue                         
    101      :switching_protocols             Switching Protocols                         
    102      :processing                      Processing                       
     
#####2xx Success
    Status   Symbol                           Description
    ------------------------------------------------------------
    200      :ok                              OK                         
    201      :created                         Created                         
    202      :accepted                        Accepted                         
    203      :non_authoritative_information   Non-Authoritative Information                         
    204      :no_content                      No Content                         
    205      :reset_content                   Reset Content                         
    206      :partial_content                 Partial Content                         
    207      :multi_status                    Multi-Status                         
    226      :im_used                         IM Used                         
     
#####3xx Redirection
    Status   Symbol                           Description
    ------------------------------------------------------------
    300      :multiple_choices                Multiple Choices                         
    301      :moved_permanently               Moved Permanently                         
    302      :found                           Found                         
    303      :see_other                       See Other                         
    304      :not_modified                    Not Modified                         
    305      :use_proxy                       Use Proxy                         
    307      :temporary_redirect              Temporary Redirect                         
     
#####4xx Client Error
    Status   Symbol                           Description
    ------------------------------------------------------------
    400      :bad_request                     Bad Request
    401      :unauthorized                    Unauthorized
    402      :payment_required                Payment Required
    403      :forbidden                       Forbidden
    404      :not_found                       Not Found
    405      :method_not_allowed              Method Not Allowed
    406      :not_acceptable                  Not Acceptable
    407      :proxy_authentication_required   Proxy Authentication Required
    408      :request_timeout                 Request Timeout
    409      :conflict                        Conflict
    410      :gone                            Gone
    411      :length_required                 Length Required
    412      :precondition_failed             Precondition Failed
    413      :request_entity_too_large        Request Entity Too Large
    414      :request_uri_too_long            Request-URI Too Long  
    415      :unsupported_media_type          Unsupported Media Type
    416      :requested_range_not_satisfiable Requested Range Not Satisfiable
    417      :expectation_failed              Expectation Failed
    422      :unprocessable_entity            Unprocessable Entity
    423      :locked                          Locked
    424      :failed_dependency               Failed Dependency
    426      :upgrade_required                Upgrade Required
     
#####5xx Server Error
    Status   Symbol                           Description
    ------------------------------------------------------------
    500      :internal_server_error           Internal Server Error
    501      :not_implemented                 Not Implemented
    502      :bad_gateway                     Bad Gateway
    503      :service_unavailable             Service Unavailable
    504      :gateway_timeout                 Gateway Timeout
    505      :http_version_not_supported      HTTP Version Not Supported
    507      :insufficient_storage            Insufficient Storage
    510      :not_extended                    Not Extended
