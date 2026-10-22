代发 wailian999

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.chenlongwang.top/Article/details/gtniisjrro.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhongyouzk.top/Article/details/gtvxnlkrml.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.aibaodan.cn/Article/details/gtopeefsze.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yuanzhike.top/Article/details/gtzpeawodg.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtdwgsrwdt.html

K. JSON 与序列化
来源：http://dali.yuxming.cn/Article/details/gtcucsmlcp.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtakmpvefw.html

[K01] 对象转 JSON 字符串
来源：http://dali.hfpthk.cn/Article/details/gtqdxrfsug.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.sysykeji.top/Article/details/gtvgcilomd.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.xylfe.cn/Article/details/gtlychmutw.html

JS:   JSON.stringify(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwciyxjzv.html

TS:   JSON.stringify(obj)
来源：http://dali.ehwqpu.com/Article/details/gtogkfyexo.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.chenzaomai.com/Article/details/gtvbaktqmt.html

Go:   json.Marshal(obj)
来源：http://dali.fengsongda.top/Article/details/gtnxssobsc.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.snrcjt.cn/Article/details/gtpjenmhmo.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jyoumei.cn/Article/details/gtnxlwdvdv.html

[K02] JSON 字符串转对象
来源：http://dali.birdmap.top/Article/details/gtdynlhwla.html

Py:   json.loads(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtmnyduanj.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yuxming.cn/Article/details/gtcukpndbm.html

JS:   JSON.parse(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtcignytum.html

TS:   JSON.parse(s)
来源：http://dali.sysykeji.top/Article/details/gtzbktujma.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.birdmap.top/Article/details/gtiejzwqhg.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhixingplan.top/Article/details/gtwftdzriu.html

Ruby: JSON.parse(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtjqxnfbxt.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jqgufenzy.top/Article/details/gtehehrjyd.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.daxiang520.top/Article/details/gthmbfphjo.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.guannengcc.top/Article/details/gtkmtvugmz.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yonumen.top/Article/details/gtrljfllmn.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zdqjudy.top/Article/details/gttlrfrbay.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yj20258888.top/Article/details/gtpkshpmbt.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgrzzbhmw.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.gzhubu.top/Article/details/gtnwvryqql.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.kuanghao11.cn/Article/details/gtowczxwao.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.hywenlv.cn/Article/details/gtivttrawb.html

[K04] 读取 JSON 文件
来源：http://dali.iojbl.cn/Article/details/gtcqnxwwxl.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.vqdsnc.cn/Article/details/gtegxrvvpd.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.xuanzx.com/Article/details/gttidvyhne.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.vqdsnc.cn/Article/details/gtatbmmvpe.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.c1oappe.top/Article/details/gtejpmsrjb.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.feifeiyinyue.top/Article/details/gtgzetplzu.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.svipenyu.cn/Article/details/gtofdknvtf.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.cqqwz.cn/Article/details/gtgxyigwvm.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hysaishi.cn/Article/details/gtdewgiwac.html

[K05] 深拷贝对象
来源：http://dali.haohaochexian.top/Article/details/gtshzbqhzo.html

Py:   copy.deepcopy(obj)
来源：http://dali.ybcxt.top/Article/details/gtywelmoci.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhengqikj.top/Article/details/gtxuleoazy.html

JS:   structuredClone(obj)
来源：http://dali.bjfxy.top/Article/details/gtxfqelfnn.html

TS:   structuredClone(obj)
来源：http://dali.meibo888.top/Article/details/gthhiettjk.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yangfankeji.com/Article/details/gtaoxkknve.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.hfpthk.cn/Article/details/gteohlirrr.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.gogol.net.cn/Article/details/gtcjgowqlv.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yanxiufei.cn/Article/details/gtwrqvztvz.html

[K06] 解析 URL 查询串
来源：http://dali.fzhhl.top/Article/details/gtemovkgfa.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.c1oappe.top/Article/details/gtrmrfycok.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.shanyushiyangtech.top/Article/details/gtvhtcruvo.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.meibo888.top/Article/details/gtdbsmhkmx.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shanyushiyangtech.top/Article/details/gtvsevihyq.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.hywenlv.cn/Article/details/gtnusirnjj.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yuxming.cn/Article/details/gtygmdfjrl.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.nanxuanxn.top/Article/details/gtjlmkuzwn.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yonumen.top/Article/details/gtnqluolvn.html

[K07] 进制转换
来源：http://dali.hnxiangtu.top/Article/details/gttywdwdpg.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yuanzhike.top/Article/details/gtuuvhuwzy.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfngdxalq.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yuxming.cn/Article/details/gtptmimtfi.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.xuanzx.com/Article/details/gtoctjotkb.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.chenzaomai.com/Article/details/gtlvgcvjgs.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jqgufenzy.top/Article/details/gtyqbgkpjd.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.cucudq.cn/Article/details/gtbfhvmdfo.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.daria6918.cn/Article/details/gtmvjavwpt.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.fengsongda.top/Article/details/gtyedqvdpm.html

Py:   pickle.dumps(obj)
来源：http://dali.yonumen.top/Article/details/gtkzinxvtd.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yonumen.top/Article/details/gtzkykvdvg.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.316326.xyz/Article/details/gtpbmoskxv.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.ppjwa.cn/Article/details/gtecjlcdsp.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yueranfly.top/Article/details/gtwdznjsfb.html

Go:   encoding/gob
来源：http://dali.wangdashe.top/Article/details/gtxiypnued.html

Ruby: Marshal.dump(obj)
来源：http://dali.cheryme.top/Article/details/gtrooyrbpp.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.dianchejie.cn/Article/details/gtmqbtegpk.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtdbchwiun.html

L. 网络请求
来源：http://dali.feifeiyinyue.top/Article/details/gtohzjirkz.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtetylozgr.html

[L01] 发送 GET 请求
来源：http://dali.tianlin.xyz/Article/details/gtdpiwzrvu.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhijiandao.cn/Article/details/gtsxhrpbcs.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jqgfzy.top/Article/details/gtsxgglfhr.html

JS:   await fetch(url)
来源：http://dali.hammf.cn/Article/details/gtmlfpnhwj.html

TS:   await fetch(url)
来源：http://dali.ppjwa.cn/Article/details/gtwhinsnbp.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.sufxvd.cn/Article/details/gtfvezxbvo.html

Go:   resp, err := http.Get(url)
来源：http://dali.chenzaomai.com/Article/details/gtusravdni.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.gaohongyu789.top/Article/details/gtwedscvtx.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.aibaodan.cn/Article/details/gtiljkkgdf.html

[L02] 发送 POST JSON
来源：http://dali.daxiang520.top/Article/details/gtcgunqzrd.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jiagoushi.top/Article/details/gtvdlqxsvr.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jinqigufen.top/Article/details/gteyctfgdy.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jianghu66.top/Article/details/gtkxdzoxgb.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xinyue.icu/Article/details/gtdprgllay.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrvzwohwx.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtczgklqnb.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.feifeiyinyue.top/Article/details/gtbreswxhe.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.ehwqpu.com/Article/details/gtjjohqrey.html

[L03] 设置自定义请求头
来源：http://dali.yanxiufei.cn/Article/details/gtovwiowop.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yuanzhike.top/Article/details/gtqbjmfrwj.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jinghuilouyu.cn/Article/details/gtypomqixu.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.dianchejie.cn/Article/details/gtrcorqqxq.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hfpthk.cn/Article/details/gtyflvocfb.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtifkuubrb.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.tanke756.top/Article/details/gtiumvuqht.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.kuanghao11.cn/Article/details/gtrzxwmynx.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yvedp.cn/Article/details/gtrcvsyrgp.html

[L04] 设置超时
来源：http://dali.hysaishi.cn/Article/details/gtxcmrwpsc.html

Py:   requests.get(url, timeout=5)
来源：http://dali.aibaodan.cn/Article/details/gtzcqygzpz.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.xinyue.icu/Article/details/gtdqaqlaic.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hysaishi.cn/Article/details/gtyvcljgad.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jlsjyb.cn/Article/details/gtkdrawkbz.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.shangyingyoupin.top/Article/details/gtokdlqfwd.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.cashguo.top/Article/details/gtfxruvzub.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.cdnleiting.top/Article/details/gtqwdqrdpi.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yuxming.cn/Article/details/gtstfbbher.html

[L05] 上传文件（multipart）
来源：http://dali.yueranfly.top/Article/details/gtyanevkel.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.xinyue.icu/Article/details/gtminkvdlc.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.redwolf501.top/Article/details/gttrrygmxa.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.wangdashe.top/Article/details/gtifocebxq.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jqgufenzy.top/Article/details/gtphlcvvwd.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jinyuanbaomall.cn/Article/details/gtenifyhrm.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yj202588.top/Article/details/gtqvojtbrs.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.cqqwz.cn/Article/details/gtkoylidyj.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.ybcxt.top/Article/details/gtdjjoszfv.html

[L06] 解析响应为 JSON
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrbzjnmmt.html

Py:   resp.json()
来源：http://dali.zhongyouzk.top/Article/details/gtlfixpigd.html

PHP:  json_decode($body, true);
来源：http://dali.jqgfzy.top/Article/details/gtrcfrdtdp.html

JS:   await resp.json()
来源：http://dali.yongpay.top/Article/details/gtqiryrfeu.html

TS:   await resp.json()
来源：http://dali.jinqigfzy.top/Article/details/gthhxtexdu.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.birdmap.top/Article/details/gteinexjwd.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.shangyingyoupin.top/Article/details/gtxycjhnnn.html

Ruby: JSON.parse(resp.body)
来源：http://dali.aizwys.cn/Article/details/gtsuaoyrnp.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zdqjudy.top/Article/details/gtnpfjfsvy.html

[L07] 处理 HTTP 状态码
来源：http://dali.yj20258.top/Article/details/gthbmjedbr.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhongyouzk.top/Article/details/gtfjmntfjf.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.chenlongwang.top/Article/details/gtnbrvqzgk.html

JS:   resp.ok;  resp.status
来源：http://dali.shanyushiyangtech.top/Article/details/gtdauaklxw.html

TS:   resp.ok;  resp.status
来源：http://dali.zdqjudy.top/Article/details/gtjnpbdwdz.html

Java: resp.statusCode()
来源：http://dali.xuanzx.com/Article/details/gtyfeamyky.html

Go:   resp.StatusCode
来源：http://dali.birdmap.top/Article/details/gtoxxsmfrl.html

Ruby: resp.code.to_i
来源：http://dali.jlsjyb.cn/Article/details/gtlxduvqzn.html

C#:   (int)resp.StatusCode
来源：http://dali.hammf.cn/Article/details/gtyvabelyc.html

[L08] 并发请求多个地址
来源：http://dali.daxiang520.top/Article/details/gtujbapsmb.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.kuanghao11.cn/Article/details/gtvrdgifyc.html

PHP:  curl_multi_init() 系列
来源：http://dali.svipenyu.cn/Article/details/gtqfcmzdpg.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cheryme.top/Article/details/gtfunzqfge.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlhyyxfkj.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.aibaodan.cn/Article/details/gtghzsmead.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.sysykeji.top/Article/details/gtdrisnggm.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jinghuilouyu.cn/Article/details/gtzlgnugdi.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.cqqwz.cn/Article/details/gtasvmijcb.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtuwhffaua.html

M. 命令行 / 进程 / 环境
来源：http://dali.gzhubu.top/Article/details/gtmkgpecec.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtoevotzji.html

[M01] 读取命令行参数
来源：http://dali.9152youxi.cn/Article/details/gtybgtvuee.html

Py:   sys.argv[1:]
来源：http://dali.hnqzz.top/Article/details/gtpbbavacw.html

PHP:  $argv;  $argc;
来源：http://dali.guannengcc.top/Article/details/gtmyfnbdof.html

JS:   process.argv.slice(2)
来源：http://dali.zhongyouzk.top/Article/details/gtergctdxx.html

TS:   process.argv.slice(2)
来源：http://dali.chenzaomai.com/Article/details/gtcbvployn.html

Java: args 数组（main 方法参数）
来源：http://dali.nwbrower.top/Article/details/gtjaucoucz.html

Go:   os.Args[1:]
来源：http://dali.guannengcc.top/Article/details/gtpfydapuz.html

Ruby: ARGV
来源：http://dali.ybcxt.top/Article/details/gtiklooozf.html

C#:   args 数组（Main 方法参数）
来源：http://dali.sxryk.cn/Article/details/gtwcfqgfoe.html

[M02] 读取环境变量
来源：http://dali.hnqzz.top/Article/details/gtledcavej.html

Py:   os.environ.get("HOME")
来源：http://dali.cheryme.top/Article/details/gthvsmnydh.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.ybcxt.top/Article/details/gtegaxrmwf.html

JS:   process.env.HOME
来源：http://dali.zhongyouzk.top/Article/details/gtigirrfmt.html

TS:   process.env.HOME
来源：http://dali.316326.xyz/Article/details/gtyfopdbwj.html

Java: System.getenv("HOME")
来源：http://dali.jinqigufen.top/Article/details/gthhqicjil.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yvedp.cn/Article/details/gtxhnwjoko.html

Ruby: ENV["HOME"]
来源：http://dali.nanxuanxn.top/Article/details/gtcxbaezkj.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gtusydscrr.html

[M03] 执行外部命令
来源：http://dali.smart0.xyz/Article/details/gtyvesqncf.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.chenzaomai.com/Article/details/gtkfuwbcow.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.fzhhl.top/Article/details/gtmqlwjqzk.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.hfpthk.cn/Article/details/gtpfcfgsxe.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.cqqwz.cn/Article/details/gtqgxafhxz.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.gaohongyu789.top/Article/details/gtnlxbhmkx.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.dashuyun.cn/Article/details/gthjsxkcez.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yangfankeji.com/Article/details/gtsrvxzhjx.html

C#:   Process.Start("ls", "-l");
来源：http://dali.guowangkeji.top/Article/details/gtviqfkgus.html

[M04] 获取当前工作目录
来源：http://dali.hnqzz.top/Article/details/gtwoudyozf.html

Py:   os.getcwd()
来源：http://dali.hfpthk.cn/Article/details/gtnpbcjmoo.html

PHP:  getcwd();
来源：http://dali.9152youxi.cn/Article/details/gtkquvkhsk.html

JS:   process.cwd()
来源：http://dali.0kj1m.cn/Article/details/gtkoculssi.html

TS:   process.cwd()
来源：http://dali.quarkkingdee.top/Article/details/gtpmasgzhv.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.gzhubu.top/Article/details/gtzqvgnzoh.html

Go:   os.Getwd()
来源：http://dali.yvedp.cn/Article/details/gtyybfvlvf.html

Ruby: Dir.pwd
来源：http://dali.yuxming.cn/Article/details/gtsxtiavzn.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jianghu66.top/Article/details/gtsmqovari.html

[M05] 设置退出码
来源：http://dali.yuanzhike.top/Article/details/gtdxrocixs.html

Py:   sys.exit(1)
来源：http://dali.zhengqikj.top/Article/details/gthbjiqtqa.html

PHP:  exit(1);
来源：http://dali.hnqzz.top/Article/details/gtflrgtxpf.html

JS:   process.exit(1)
来源：http://dali.zdqjudy.top/Article/details/gtawjxhfra.html

TS:   process.exit(1)
来源：http://dali.jinqigufen.top/Article/details/gtkhmrkfmm.html

Java: System.exit(1)
来源：http://dali.shuidangran.top/Article/details/gtsrbipaik.html

Go:   os.Exit(1)
来源：http://dali.pycfn.com/Article/details/gtdorpzlgx.html

Ruby: exit 1
来源：http://dali.cqqwz.cn/Article/details/gtfvcivmax.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.tian-w.cn/Article/details/gtjrodkdtw.html

[M06] 向标准错误输出
来源：http://dali.yj20258.top/Article/details/gtgarxfuol.html

Py:   print("err", file=sys.stderr)
来源：http://dali.gotoacloud.top/Article/details/gtpcmfbxmb.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.pengpengdd.cyou/Article/details/gtffknzmpt.html

JS:   console.error("err")
来源：http://dali.andypj.xyz/Article/details/gtakcxlppv.html

TS:   console.error("err")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnoaznvzn.html

Java: System.err.println("err")
来源：http://dali.316326.xyz/Article/details/gtxnzzpfcx.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.bjfxy.top/Article/details/gtpfivrqal.html

Ruby: warn "err"
来源：http://dali.mhx1999.top/Article/details/gtluvilwum.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.tianlin.xyz/Article/details/gtwrtaxwjf.html

[M07] 判断是否为主入口
来源：http://dali.jinghuilouyu.cn/Article/details/gtswixlbid.html

Py:   if __name__ == "__main__":
来源：http://dali.shuidangran.top/Article/details/gtdmjosdtb.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.tanke756.top/Article/details/gtjjhlquto.html

JS:   require.main === module
来源：http://dali.tianlin.xyz/Article/details/gtvhogwdos.html

TS:   require.main === module
来源：http://dali.shangyingyoupin.top/Article/details/gtlviweqfd.html

Java: public static void main(String[] args)
来源：http://dali.aibaodan.cn/Article/details/gtctriynbm.html

Go:   func main()
来源：http://dali.gogol.net.cn/Article/details/gtvahfoxax.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.gzhubu.top/Article/details/gtevjvkgtv.html

C#:   static void Main(string[] args)
来源：http://dali.shanyushiyangtech.top/Article/details/gtrkmzpptx.html

[M08] 获取系统与运行时信息
来源：http://dali.c1oappe.top/Article/details/gtouppdobj.html

Py:   platform.system();  platform.python_version()
来源：http://dali.sxryk.cn/Article/details/gtorodbhgr.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.ppjwa.cn/Article/details/gtoloexlai.html

JS:   process.platform;  process.version
来源：http://dali.yuanzhike.top/Article/details/gtgijhtnye.html

TS:   process.platform;  process.version
来源：http://dali.aibaodan.cn/Article/details/gtllilrivr.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yuanzhike.top/Article/details/gtvvehsakj.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.sxryk.cn/Article/details/gtcuqirrei.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.guannengcc.top/Article/details/gtvyyjjoma.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.redwolf501.top/Article/details/gtyuxjtqwz.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtyzpoqgtn.html

N. 数据结构与算法
来源：http://dali.jiagoushi.top/Article/details/gtqrszehbk.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtdbaupvdl.html

[N01] 二分查找（有序数组）
来源：http://dali.ehwqpu.com/Article/details/gtnxcizhvy.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.guannengcc.top/Article/details/gtrdoduzly.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.iojbl.cn/Article/details/gtxntmjdpd.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.chenlongwang.top/Article/details/gthtxiovyn.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.daria6918.cn/Article/details/gtfyapyvgf.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.fengsongda.top/Article/details/gtswcwfaet.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.guannengcc.top/Article/details/gtfionywiy.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.haohaochexian.top/Article/details/gthuledapx.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.9152youxi.cn/Article/details/gtbjdbypjn.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.andypj.xyz/Article/details/gtfvysaxyu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sxryk.cn/Article/details/gtmdmyjadg.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jinqigfzy.top/Article/details/gtdeehkvic.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhongyouzk.top/Article/details/gthmwfwcsi.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.daxiang520.top/Article/details/gtltbnkztd.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.xylfe.cn/Article/details/gtevfalbcm.html

Go:   slices.Sort(arr)
来源：http://dali.daxiang520.top/Article/details/gtwjxishxw.html

Ruby: arr.sort
来源：http://dali.chenzaomai.com/Article/details/gtuyplrkwa.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.ivvv.top/Article/details/gtrjacqqzt.html

[N03] 快速排序（分治示例）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvomkqfzn.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.iojbl.cn/Article/details/gtmrnpvdnj.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhixingplan.top/Article/details/gthiqczxmk.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cashguo.top/Article/details/gtlfrobsha.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.pengpengdd.cyou/Article/details/gtmamzonap.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.chenzaomai.com/Article/details/gtbbfqdoya.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.tian-w.cn/Article/details/gtnpsedwkr.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.tianlin.xyz/Article/details/gtszqqnkiz.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.cucudq.cn/Article/details/gtwjbjhdai.html

[N04] 斐波那契数列
来源：http://dali.fengsongda.top/Article/details/gtlvkivmrc.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.guannengcc.top/Article/details/gtspvvmhyp.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.pycfn.com/Article/details/gtfvkuzwdf.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.bjfxy.top/Article/details/gtpjjhhepm.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hammf.cn/Article/details/gtiviathsa.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqydudnxy.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.hnxiangtu.top/Article/details/gtlqguzexd.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.cashguo.top/Article/details/gtathdjahs.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.havefunace.top/Article/details/gtdbvcotcn.html

[N05] 最大公约数
来源：http://dali.feifeiyinyue.top/Article/details/gtlvafptpf.html

Py:   math.gcd(a, b)
来源：http://dali.ivvv.top/Article/details/gtywagbvpi.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhongyouzk.top/Article/details/gtstkxitxc.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shuidangran.top/Article/details/gtevtphhku.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtsaglpojj.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.c1oappe.top/Article/details/gtjyeqwayp.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zycfv.cn/Article/details/gtcwrwewuk.html

Ruby: a.gcd(b)
来源：http://dali.gogol.net.cn/Article/details/gthytxydwz.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.0kj1m.cn/Article/details/gtiryujifi.html

[N06] 判断回文字符串
来源：http://dali.9152youxi.cn/Article/details/gtbckntarp.html

Py:   s == s[::-1]
来源：http://dali.fzhhl.top/Article/details/gtmizskedk.html

PHP:  $s === strrev($s);
来源：http://dali.quarkkingdee.top/Article/details/gtznksojoy.html

JS:   s === [...s].reverse().join("")
来源：http://dali.sweek.top/Article/details/gtctuhntvi.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yangfankeji.com/Article/details/gtnajypprx.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.nwbrower.top/Article/details/gthetldsga.html

Go:   // 双指针从两端比较
来源：http://dali.chenjidiqi.icu/Article/details/gtmraicxyp.html

Ruby: s == s.reverse
来源：http://dali.chenjidiqi.icu/Article/details/gtopvslyax.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqhcdllaa.html

[N07] 两数之和（返回下标）
来源：http://dali.nanxuanxn.top/Article/details/gtosxggkjn.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.ybcxt.top/Article/details/gtrogmqdvm.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yongpay.top/Article/details/gtyqjwavho.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.xuanzx.com/Article/details/gtrsclotlb.html

TS:   // 手写 Map<string, number>
来源：http://dali.quarkkingdee.top/Article/details/gtmxjaujdn.html

Java: // 手写 HashMap
来源：http://dali.shanyushiyangtech.top/Article/details/gtynmikeur.html

Go:   // 手写 map[int]int
来源：http://dali.sxryk.cn/Article/details/gtgvhljacu.html

Ruby: // 手写 Hash
来源：http://dali.fengsongda.top/Article/details/gtvpsqypqd.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.redwolf501.top/Article/details/gtcjwozxyk.html

[N08] 生成全排列
来源：http://dali.jqgufenzy.top/Article/details/gtvemitpwz.html

Py:   itertools.permutations(arr)
来源：http://dali.cqqwz.cn/Article/details/gtjvmjdygs.html

PHP:  // 手写递归交换
来源：http://dali.wangshuangyany.cn/Article/details/gtivaktzjd.html

JS:   // 手写回溯递归
来源：http://dali.yuxming.cn/Article/details/gtpfruwpvh.html

TS:   // 手写回溯递归
来源：http://dali.chenlongwang.top/Article/details/gtisxggstr.html


<!-- 参考信息 -->