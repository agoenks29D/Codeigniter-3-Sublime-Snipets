# Codeigniter 3 Snippets (Core Classes)

## Benchmark

| Method | Tab Trigger | Description |
|--------|-------------|-------------|
| `$this->benchmark->mark('name');` | benchmark_mark | Benchmark ~ Mark Start/End |
| `$this->benchmark->elapsed_time('start','end');` | benchmark_elapsed_time | Benchmark ~ Elapsed Time |
| `$this->benchmark->memory_usage();` | benchmark_memory_usage | Benchmark ~ Memory Usage |

## Cache

| Method | Tab Trigger | Description |
|--------|-------------|-------------|
| `$this->cache->clean();` | cache_clean | Cache ~ Clean |
| `$this->cache->decrement('id');` | cache_decrement | Cache ~ Decrement |
| `$this->cache->delete('id');` | cache_delete | Cache ~ Delete |
| `$this->cache->get('id');` | cache_get | Cache ~ Get |
| `$this->cache->get_metadata('id');` | cache_get_metadata | Cache ~ Get Metadata |
| `$this->cache->increment('id');` | cache_increment | Cache ~ Increment |
| `$this->cache->cache_info();` | cache_info | Cache ~ Info |
| `$this->cache->is_supported('_cache_drivers');` | cache_is_supported | Cache ~ Is Supported |
| `$this->load->driver('cache', array('adapter' => '_cache_drivers', 'backup' => '_cache_drivers'));` | cache_load | Cache ~ Load |
| `$this->cache->apc->save('name', data, 1200);` | cache_save_apc | Cache ~ Save Apc |
| `$this->cache->file->save('name', data, 1200);` | cache_save_file | Cache ~ Save File |
| `$this->cache->memcached->save('name', data, 1200);` | cache_save_memcached | Cache ~ Save Memcached |
| `$this->cache->redis->save('name', data, 1200);` | cache_save_redis | Cache ~ Save Redis |
| `$this->cache->wincache->save('name', data, 1200);` | cache_save_wincache | Cache ~ Save Wincache |
| `$this->cache->save('name', data, 1200);` | cache_save | Cache ~ Save |

## Config

| Method | Tab Trigger | Description |
|--------|-------------|-------------|
| `$this->config->item('name');` | config_item | Config ~ Item |
| `$this->config->load('file');` | config_load | Config ~ Load |
| `$this->config->set_item('item', 'value');` | config_set_item | Config ~ Set Item |
| `$this->config->item('name');` | config_item | Config ~ Item |
| `$this->config->slash_item('item');` | config_slash_item | Config ~ Slash Item |

## Input

| Method | Tab Trigger | Description |
|--------|-------------|-------------|
| `$this->input->cookie('name');` | _cookie | Input ~ Cookie |
| `$this->input->get('name');` | _get | $_GET[''] |
| `$this->input->post('name');` | _post | $_POST[''] |
| `$this->input->get_post('name');` | _get_post | $_GET[''] / $_POST[''] |
| `$this->input->post_get('name');` | _post_get | $_POST[''] / $_GET[''] |
| `$this->input->get_request_header('index');` | get_request_header | Get Request Header |
| `$this->input->ip_address();` | ip_address | IP Address |
| `$this->input->is_ajax_request();` | is_ajax_request | Is Ajax Request |
| `$this->input->is_cli_request();` | is_cli_request | Is CLI Request |
| `$this->input->raw_input_stream;` | raw_input_stream | Input ~ Raw Input Stream |
| `$this->input->request_headers();` | request_headers | Request Headers |
| `$this->input->server('index');` | _server | $_SERVER[''] |
| `$this->input->set_cookie($cookie);` | set_cookie | Input ~ Set Cookie |
| `$this->input->input_stream('index');` | input_stream | Input ~ Stream |
| `$this->input->user_agent();` | user_agent | Input ~ User Agent |
| `$this->input->valid_ip('ip_address','_ip_version');` | valid_ip | Input ~ Valid Ip |

## Language

| Method | Tab Trigger | Description |
|--------|-------------|-------------|
| `$this->lang->load('file');` | lang_load | Language ~ Load |
| `$this->lang->line('key');` | lang_line | Language ~ Line |

## Loader

| Method | Tab Trigger | Description |
|--------|-------------|-------------|
| `$this->load->is_loaded('class');` | load_is_loaded | Is Loaded |
| `$this->load->clear_vars();` | load_clear_vars | Clear Vars |
| `$this->load->config('config');` | load_config | Load Config |
| `$this->load->helper('_helper');` | load_helper | Load Helper |
| `$this->load->library('_library');` | load_library | Load Library |
| `$this->load->model('model');` | load_model | Load Model |
| `$this->load->view('view');` | load_view | Load View |
| `$this->load->language('language');` | load_language | Load Language |
| `$this->load->driver('_codeigniter_driver');` | load_driver | Load Driver |
| `$this->load->file('file');` | load_file | Load File |
| `$this->load->database('database', $return);` | load_database | Load Database |
| `$this->load->dbforge('database', $return);` | load_dbforge | Load DB Forge |
| `$this->load->dbutil('database', $return);` | load_dbutil | Load DB Utility |
| `$this->load->get_var('key');` | load_get_var | Get Var |
| `$this->load->get_vars();` | load_get_vars | Get Vars |
| `$this->load->vars('var');` | load_vars | Load Var |
| `$this->load->add_package_path('path');` | load_add_package_path | Add Package Path |
| `$this->load->remove_package_path('path');` | load_remove_package_path | Remove Package Path |
| `$this->load->get_package_paths();` | load_get_package_paths | Get Package Paths |

## Output

| Method | Tab Trigger | Description |
|--------|-------------|-------------|
| `$this->output->parse_exec_vars = FALSE;` | output_parse_exec_vars | Output ~ Parse Exec Vars |
| `$this->output->set_profiler_sections($sections);` | output_set_profiler_sections | Output ~ Set Profiler Sections |
| `$this->output->append('data');` | output_append | Output ~ Append |
| `$this->output->enable_profiler('TRUE');` | output_enable_profiler | Output ~ Enable Profiler |
| `$this->output->get_content_type();` | output_get_content_type | Output ~ Get Content Type |
| `$this->output->get_header('header');` | output_get_header | Output ~ Get Header |
| `$this->output->get_output();` | get_output | Output ~ Get Output |
| `$this->output->_display('content');` | output_display | Output ~ Display |
| `$this->output->set_content_type('application/json')->set_output(json_encode($data));` | output_json | Output ~ Json |
| `$this->output->set_content_type('mime_type');` | set_content_type | Output ~ Set Content Type |
| `$this->output->set_header('HTTP/1.0 200 OK');` | set_header | Output ~ Set Header |
| `$this->output->set_output('data');` | set_output | Output ~ Set Output |
| `$this->output->set_status_header('200');` | set_status_header | Output ~ Set Status Header |

## Router

| Method | Tab Trigger | Description |
|--------|-------------|-------------|
| `$this->router->fetch_class();` | router_fetch_class | Router ~ Fetch Class |
| `$this->router->fetch_method();` | router_fetch_method | Router ~ Fetch Method |

## Security

| Method | Tab Trigger | Description |
|--------|-------------|-------------|
| `$this->router->entity_decode('string');` | security_entity_decode | Security ~ Entity Decode |
| `$this->router->get_csrf_hash();` | get_csrf_hash | Security ~ Get Csrf Hash |
| `$this->router->get_csrf_token_name();` | get_csrf_token | Security ~ Get Csrf Token |
| `$this->router->get_random_bytes(length);` | get_random_bytes | Security ~ Get Random Bytes |
| `$this->router->sanitize_filename('file_path');` | sanitize_filename | Security ~ Sanitize Filename |
| `$this->router->xss_clean('string');` | xss_clean | XSS Clean |

---

<p align="center"><img src="https://cdn-images-1.medium.com/max/738/1*G95uyokAH4JC5Ppvx4LmoQ@2x.png" width="280"></p>

[**PATREON**](https://www.patreon.com/agoenks29D)

[**PAYPAL**](https://www.paypal.me/agungdirgantara)

**[ETH](https://www.blockchain.com/eth/address/0x251b36840557cCe9A245f07E1b834bCfb7354FDb) : 0x251b36840557cCe9A245f07E1b834bCfb7354FDb**

**[DOGE](https://dogechain.info/address/DFmES6KZLQXimXduXwKmooykMsjhWmT1tU) : DFmES6KZLQXimXduXwKmooykMsjhWmT1tU**

**[BITCOIN](https://www.blockchain.com/btc/address/1MEqUeg7fXTkBMFWfJZE9yJREsKZ4SUxQM) : 1MEqUeg7fXTkBMFWfJZE9yJREsKZ4SUxQM**

**[BITCOIN CASH](https://www.blockchain.com/bch/address/qzrllcyrjwvpnuur5kpeyp03p246fzsgzvhleswr6f) : qzrllcyrjwvpnuur5kpeyp03p246fzsgzvhleswr6f**

### Social Media : 

<a class="social_link" href="https://fb.me/agoenks29D">
	<img src="https://static.xx.fbcdn.net/rsrc.php/yo/r/iRmz9lCMBD2.ico" width="32" style="margin-bottom: 2px;">
</a>

<a class="social_link" href="https://instragram.com/agoenks29D">
	<img src="https://www.instagram.com/static/images/ico/favicon.ico/36b3ee2d91ed.ico" width="32">
</a>

<a class="social_link" href="https://t.me/agoenks29D">
	<img src="https://web.telegram.org/favicon.ico" width="32">
</a>

<a class="social_link" href="https://api.whatsapp.com/send?phone=6282167368585&text=Hello,i get your contact from github">
	<img src="https://static.whatsapp.net/rsrc.php/v3/yP/r/rYZqPCBaG70.png" width="36">
</a>

<a class="social_link" href="https://www.youtube.com/channel/UCwXyVSMRqAuyyQtXVoMrf2A?view_as=subscriber&sub_cotnfirmation=1">
	<img src="https://s.ytimg.com/yts/img/favicon_48-vflVjB_Qk.png" width="38">
</a> 

<p></p>

<p align="center"><b>Made with ❤️ + ☕ ~ Agung Dirgantara</b></p>