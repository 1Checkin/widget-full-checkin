# widget-full-checkin

```
document.addEventListener('DOMContentLoaded', () => {
    window.widget = new onecheckin_widget_full_checkin(
        document.getElementById('container'), {
            ready: () => {console.log('ready')},
            "lang": "en",
            "tos_url": "tos.html",
            "privacy_policy_url": "privacy-policy.html",
            "endpoints": "https://mw.dev.1check.in/widget/",
            "autocomplete": "https://mw.dev.1check.in/landing/autocomplete/",
            "template_url": "/theme/widget-full-checkin/widget-en.txt",
            data: {
              "passengers": [
                {
                  "first_name": "Ivan",
                  "last_name": "Ivanov",
                  "middle_name": "Ivanovich",
                  "eticket": "41241241212412",
                  "gender": "male",
                  "ffn": "141414141",
                  "ffn_airline": "SU",
                  "citizenship": "RU",
                  "residence": "RU",
                }
              ],
              "flights": [
                {
                  "booking_ref": "ABCAAA",
                  "departure_code": "SVO",
                  "destination_code": "SVO",
                  "marketing_carrier_code": "SU",
                  "operating_carrier_code": "SU",
                  "flight_num": "025",
                  "departure_date": "2018-05-25",
                  "departure_time": "15:10",
                }
              ],
              "seatStrategies": []
            }
        }
    );
}, false);

```