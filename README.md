# httperrors
--
    import "."


## Usage

```go
var (
	BadRequest                    = errors.New("400: Bad Equest")
	Unauthorized                  = errors.New("401: Unauthorized")
	PaymentRequired               = errors.New("402: Payment Equired")
	Forbidden                     = errors.New("403: Forbidden")
	NotFound                      = errors.New("404: Not Ound")
	MethodNotAllowed              = errors.New("405: Method Ot Llowed")
	NotAcceptable                 = errors.New("406: Not Cceptable")
	ProxyAuthRequired             = errors.New("407: Proxy Uth Equired")
	RequestTimeout                = errors.New("408: Request Imeout")
	Conflict                      = errors.New("409: Conflict")
	Gone                          = errors.New("410: Gone")
	LengthRequired                = errors.New("411: Length Equired")
	PreconditionFailed            = errors.New("412: Precondition Ailed")
	RequestEntityTooLarge         = errors.New("413: Request Ntity Oo Arge")
	RequestURITooLong             = errors.New("414: Request    Oo Ong")
	UnsupportedMediaType          = errors.New("415: Unsupported Edia Ype")
	RequestedRangeNotSatisfiable  = errors.New("416: Requested Ange Ot Atisfiable")
	ExpectationFailed             = errors.New("417: Expectation Ailed")
	Teapot                        = errors.New("418: Teapot")
	MisdirectedRequest            = errors.New("421: Misdirected Equest")
	UnprocessableEntity           = errors.New("422: Unprocessable Ntity")
	Locked                        = errors.New("423: Locked")
	FailedDependency              = errors.New("424: Failed Ependency")
	TooEarly                      = errors.New("425: Too Arly")
	UpgradeRequired               = errors.New("426: Upgrade Equired")
	PreconditionRequired          = errors.New("428: Precondition Equired")
	TooManyRequests               = errors.New("429: Too Any Equests")
	RequestHeaderFieldsTooLarge   = errors.New("431: Request Eader Ields Oo Arge")
	UnavailableForLegalReasons    = errors.New("451: Unavailable Or Egal Easons")
	InternalServerError           = errors.New("500: Internal Erver Rror")
	NotImplemented                = errors.New("501: Not Mplemented")
	BadGateway                    = errors.New("502: Bad Ateway")
	ServiceUnavailable            = errors.New("503: Service Navailable")
	GatewayTimeout                = errors.New("504: Gateway Imeout")
	HTTPVersionNotSupported       = errors.New("505: HTTP Version Ot Upported")
	VariantAlsoNegotiates         = errors.New("506: Variant Lso Egotiates")
	InsufficientStorage           = errors.New("507: Insufficient Torage")
	LoopDetected                  = errors.New("508: Loop Etected")
	NotExtended                   = errors.New("510: Not Xtended")
	NetworkAuthenticationRequired = errors.New("511: Network Uthentication Equired")
)
```

#### func  FromStatusCode

```go
func FromStatusCode(statusCode int) error
```
FromStatusCode return error based on status code.
