# httperrors
--
    import "."


## Usage

```go
var (
	BadRequest                    = errors.New("400: Bad Request")
	Unauthorized                  = errors.New("401: Unauthorized")
	PaymentRequired               = errors.New("402: Payment Required")
	Forbidden                     = errors.New("403: Forbidden")
	NotFound                      = errors.New("404: Not Found")
	MethodNotAllowed              = errors.New("405: Method Not Allowed")
	NotAcceptable                 = errors.New("406: Not Acceptable")
	ProxyAuthRequired             = errors.New("407: Proxy Auth Required")
	RequestTimeout                = errors.New("408: Request Timeout")
	Conflict                      = errors.New("409: Conflict")
	Gone                          = errors.New("410: Gone")
	LengthRequired                = errors.New("411: Length Required")
	PreconditionFailed            = errors.New("412: Precondition Failed")
	RequestEntityTooLarge         = errors.New("413: Request Entity Too Large")
	RequestURITooLong             = errors.New("414: Request U R I Too Long")
	UnsupportedMediaType          = errors.New("415: Unsupported Media Type")
	RequestedRangeNotSatisfiable  = errors.New("416: Requested Range Not Satisfiable")
	ExpectationFailed             = errors.New("417: Expectation Failed")
	Teapot                        = errors.New("418: Teapot")
	MisdirectedRequest            = errors.New("421: Misdirected Request")
	UnprocessableEntity           = errors.New("422: Unprocessable Entity")
	Locked                        = errors.New("423: Locked")
	FailedDependency              = errors.New("424: Failed Dependency")
	TooEarly                      = errors.New("425: Too Early")
	UpgradeRequired               = errors.New("426: Upgrade Required")
	PreconditionRequired          = errors.New("428: Precondition Required")
	TooManyRequests               = errors.New("429: Too Many Requests")
	RequestHeaderFieldsTooLarge   = errors.New("431: Request Header Fields Too Large")
	UnavailableForLegalReasons    = errors.New("451: Unavailable For Legal Reasons")
	InternalServerError           = errors.New("500: Internal Server Error")
	NotImplemented                = errors.New("501: Not Implemented")
	BadGateway                    = errors.New("502: Bad Gateway")
	ServiceUnavailable            = errors.New("503: Service Unavailable")
	GatewayTimeout                = errors.New("504: Gateway Timeout")
	HTTPVersionNotSupported       = errors.New("505: HTTP Version Not Supported")
	VariantAlsoNegotiates         = errors.New("506: Variant Also Negotiates")
	InsufficientStorage           = errors.New("507: Insufficient Storage")
	LoopDetected                  = errors.New("508: Loop Detected")
	NotExtended                   = errors.New("510: Not Extended")
	NetworkAuthenticationRequired = errors.New("511: Network Authentication Required")
)
```

#### func  FromStatusCode

```go
func FromStatusCode(statusCode int) error
```
FromStatusCode return error based on status code.
