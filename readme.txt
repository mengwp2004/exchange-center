

I, [2018-04-17T16:46:20.180885 #23015]  INFO -- :   Rendered shared/_footer.html.slim (0.1ms)
I, [2018-04-17T16:46:20.181384 #23015]  INFO -- : Completed 200 OK in 215ms (Views: 172.4ms | ActiveRecord: 7.3ms)
I, [2018-04-17T16:46:43.302935 #23015]  INFO -- : Started PATCH "/id_document" for 192.168.80.8 at 2018-04-17 16:46:43 +0800
I, [2018-04-17T16:46:43.305192 #23015]  INFO -- : Processing by Private::IdDocumentsController#update as HTML
I, [2018-04-17T16:46:43.305381 #23015]  INFO -- :   Parameters: {"utf8"=>"✓", "authenticity_token"=>"z6r3PlhG20Sc0e7PWnqMRHZUG9xcSfZicySx7RMcWCM=", "id_document"=>{"name"=>"hdx", "birth_date(3i)"=>"17", "birth_date(2i)"=>"4", "birth_date(1i)"=>"1948", "address"=>"", "city"=>"", "country"=>"", "zipcode"=>"", "id_document_type"=>"id_card", "id_document_number"=>"333", "id_bill_type"=>"tax_bill"}, "commit"=>"更新实名认证"}
I, [2018-04-17T16:46:43.516693 #23015]  INFO -- : Redirected to http://192.168.80.11:3000/settings
I, [2018-04-17T16:46:43.516971 #23015]  INFO -- : Completed 302 Found in 211ms (ActiveRecord: 167.0ms)
I, [2018-04-17T16:46:43.556005 #23015]  INFO -- : Started GET "/settings" for 192.168.80.8 at 2018-04-17 16:46:43 +0800
I, [2018-04-17T16:46:43.558258 #23015]  INFO -- : Processing by Private::SettingsController#index as HTML
I, [2018-04-17T16:46:43.588819 #23015]  INFO -- :   Rendered private/settings/index.html.slim within layouts/application (16.4ms)
I, [2018-04-17T16:46:43.593295 #23015]  INFO -- :   Rendered shared/_html5.html.slim (0.3ms)
I, [2018-04-17T16:46:43.594284 #23015]  INFO -- :   Rendered shared/_meta.html.slim (0.7ms)
I, [2018-04-17T16:46:43.595041 #23015]  INFO -- :   Rendered shared/_alert.html.slim (0.2ms)
I, [2018-04-17T16:46:43.600252 #23015]  INFO -- :   Rendered shared/_header_profile_setting.html.slim (3.5ms)
I, [2018-04-17T16:46:43.600762 #23015]  INFO -- :   Rendered shared/_header_lang_sel.html.slim (0.1ms)
I, [2018-04-17T16:46:43.600925 #23015]  INFO -- :   Rendered shared/_header.html.slim (5.6ms)
I, [2018-04-17T16:46:43.601854 #23015]  INFO -- :   Rendered shared/_flash.slim (0.1ms)
I, [2018-04-17T16:46:43.602259 #23015]  INFO -- :   Rendered shared/_frame.html.slim (1.0ms)
I, [2018-04-17T16:46:43.602549 #23015]  INFO -- :   Rendered shared/_footer.html.slim (0.1ms)
I, [2018-04-17T16:46:43.602904 #23015]  INFO -- : Completed 200 OK in 44ms (Views: 27.9ms | ActiveRecord: 4.1ms)
I, [2018-04-17T16:47:01.786021 #23015]  INFO -- : Started GET "/funds" for 192.168.80.8 at 2018-04-17 16:47:01 +0800
I, [2018-04-17T16:47:01.793516 #23015]  INFO -- : Processing by Private::FundsController#index as HTML
I, [2018-04-17T16:47:01.818659 #23015]  INFO -- : Redirected to http://192.168.80.11:3000/settings
I, [2018-04-17T16:47:01.818923 #23015]  INFO -- : Filter chain halted as :auth_verified! rendered or redirected
I, [2018-04-17T16:47:01.819187 #23015]  INFO -- : Completed 302 Found in 25ms (ActiveRecord: 3.6ms)
I, [2018-04-17T16:47:01.830543 #23015]  INFO -- : Started GET "/settings" for 192.168.80.8 at 2018-04-17 16:47:01 +0800
I, [2018-04-17T16:47:01.835187 #23015]  INFO -- : Processing by Private::SettingsController#index as HTML
I, [2018-04-17T16:47:01.872328 #23015]  INFO -- :   Rendered private/settings/index.html.slim within layouts/application (22.0ms)
I, [2018-04-17T16:47:01.880469 #23015]  INFO -- :   Rendered shared/_html5.html.slim (0.2ms)
I, [2018-04-17T16:47:01.881428 #23015]  INFO -- :   Rendered shared/_meta.html.slim (0.7ms)

