代发 wailian999

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.xinyue.icu/Article/details/gtitimlzjr.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yj20258888.top/Article/details/gtfohzqmii.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.pycfn.com/Article/details/gthfrjpnyv.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgwaqoyvi.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtoztymeus.html

K. JSON 与序列化
来源：http://dali.dashuyun.cn/Article/details/gtihbnzmdb.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtvnvhoklr.html

[K01] 对象转 JSON 字符串
来源：http://dali.jyoumei.cn/Article/details/gtmuouxjpn.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.nwbrower.top/Article/details/gtjtbxjogr.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.havefunace.top/Article/details/gtpxrqggjl.html

JS:   JSON.stringify(obj)
来源：http://dali.zhengqikj.top/Article/details/gteoskejzd.html

TS:   JSON.stringify(obj)
来源：http://dali.daxiang520.top/Article/details/gtzqtebftk.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhongyouzk.top/Article/details/gteeucjthh.html

Go:   json.Marshal(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqyfcfnkv.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yuanzhike.top/Article/details/gtbwndftov.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yanxiufei.cn/Article/details/gtufvkmndo.html

[K02] JSON 字符串转对象
来源：http://dali.cheryme.top/Article/details/gtgymmgycy.html

Py:   json.loads(s)
来源：http://dali.yonumen.top/Article/details/gtxdepnogp.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.svipenyu.cn/Article/details/gthvrdbpoy.html

JS:   JSON.parse(s)
来源：http://dali.yueranfly.top/Article/details/gtwlreffie.html

TS:   JSON.parse(s)
来源：http://dali.jinqigfzy.top/Article/details/gtmysjvtkk.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.wangshuangyany.cn/Article/details/gtxkbctnwp.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.gotoacloud.top/Article/details/gtwdciyxqv.html

Ruby: JSON.parse(s)
来源：http://dali.zhixingplan.top/Article/details/gtmvvkansl.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtohflkzib.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jqgufenzy.top/Article/details/gtunqixtfz.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.snrcjt.cn/Article/details/gtmujmisvk.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zdqjudy.top/Article/details/gtxmnhgozr.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.dianchejie.cn/Article/details/gtxmbtsmdn.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yuanzhike.top/Article/details/gtmkovfmlx.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtcworxcez.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yj202588.top/Article/details/gterdbepbn.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.hammf.cn/Article/details/gtmjpfjbwe.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.aibaodan.cn/Article/details/gtrvvugywv.html

[K04] 读取 JSON 文件
来源：http://dali.c1oappe.top/Article/details/gtbrmmkwai.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.wangdashe.top/Article/details/gtldyjcixh.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.hysaishi.cn/Article/details/gtdkgfkyqe.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.pengpengdd.cyou/Article/details/gtpkvobdfn.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.haohaochexian.top/Article/details/gtyvgtsgjk.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.wangshuangyany.cn/Article/details/gtylmrdidu.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yuanzhike.top/Article/details/gtacybdqgi.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jlsjyb.cn/Article/details/gtfsnjitas.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.vqdsnc.cn/Article/details/gtexselivl.html

[K05] 深拷贝对象
来源：http://dali.wangdashe.top/Article/details/gtzregvqiw.html

Py:   copy.deepcopy(obj)
来源：http://dali.zycfv.cn/Article/details/gtamlcxhbj.html

PHP:  unserialize(serialize($obj));
来源：http://dali.gzhubu.top/Article/details/gtuimntkzs.html

JS:   structuredClone(obj)
来源：http://dali.ydzc1.top/Article/details/gtgeikqmrt.html

TS:   structuredClone(obj)
来源：http://dali.guannengcc.top/Article/details/gtbvbptlmf.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.dashuyun.cn/Article/details/gtiqpcectd.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.shanyushiyangtech.top/Article/details/gtrgeecmip.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hfpthk.cn/Article/details/gtpfxwlvra.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.nanxuanxn.top/Article/details/gtdolpdsop.html

[K06] 解析 URL 查询串
来源：http://dali.pengpengdd.cyou/Article/details/gtdwugrmps.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.aizwys.cn/Article/details/gtqxlhqium.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.ivvv.top/Article/details/gtmjsrhvml.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yonumen.top/Article/details/gtultjjimu.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zycfv.cn/Article/details/gtlminlkwt.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yangfankeji.com/Article/details/gtkrzguszh.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.hammf.cn/Article/details/gttbseaxpe.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yj202588.top/Article/details/gtmzxovljg.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.shuidangran.top/Article/details/gtxemrdzbk.html

[K07] 进制转换
来源：http://dali.zdqjudy.top/Article/details/gtgadqpsrb.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.cqqwz.cn/Article/details/gtnbuvaorj.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.hongshengwenyu.top/Article/details/gtujwnylwn.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jqgfzy.top/Article/details/gtmzuxernz.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.xziqi.cn/Article/details/gtpzjjlymr.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.dashuyun.cn/Article/details/gtgwtzvyql.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.hnxiangtu.top/Article/details/gtupcjzrsf.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zdqjudy.top/Article/details/gtfqtfwltt.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.vqdsnc.cn/Article/details/gtgdpjdayf.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yongpay.top/Article/details/gtvcklzpfi.html

Py:   pickle.dumps(obj)
来源：http://dali.meibo888.top/Article/details/gtruuutjyq.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.quarkkingdee.top/Article/details/gtvlgchrhm.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.hongshengwenyu.top/Article/details/gtuzknwzxc.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yuxming.cn/Article/details/gtsgovtqeo.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.hfpthk.cn/Article/details/gtkktzrnhl.html

Go:   encoding/gob
来源：http://dali.feifeiyinyue.top/Article/details/gtocomsaee.html

Ruby: Marshal.dump(obj)
来源：http://dali.daria6918.cn/Article/details/gtgprslehq.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yj202588.top/Article/details/gtrxfzuvki.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtfvgxnjfp.html

L. 网络请求
来源：http://dali.shzxlz.cn/Article/details/gttkragvgl.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtxypzvcdh.html

[L01] 发送 GET 请求
来源：http://dali.cashguo.top/Article/details/gtmnjylyec.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zdqjudy.top/Article/details/gtfhakjsil.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.ybcxt.top/Article/details/gtsddiqbyw.html

JS:   await fetch(url)
来源：http://dali.yueranfly.top/Article/details/gtqmxaucjg.html

TS:   await fetch(url)
来源：http://dali.wangshuangyany.cn/Article/details/gtmbcawxkp.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.aibaodan.cn/Article/details/gtddvbbzfb.html

Go:   resp, err := http.Get(url)
来源：http://dali.chenjidiqi.icu/Article/details/gtttbsnnrs.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.sysykeji.top/Article/details/gtfxxavalb.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhongyouzk.top/Article/details/gtczmogppo.html

[L02] 发送 POST JSON
来源：http://dali.hywenlv.cn/Article/details/gtsacfhjca.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.cucudq.cn/Article/details/gtmwevcvck.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yj20258888.top/Article/details/gtavwkinko.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.tanke756.top/Article/details/gtgoprmewo.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sweek.top/Article/details/gtgrtjcqxq.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jlsjyb.cn/Article/details/gtrqhfmfqg.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.tianlin.xyz/Article/details/gtblclpfyw.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmikqoucn.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.sysykeji.top/Article/details/gtcjmhgwzl.html

[L03] 设置自定义请求头
来源：http://dali.hysaishi.cn/Article/details/gtjybqewnh.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jlsjyb.cn/Article/details/gthsncaqnv.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.tianlin.xyz/Article/details/gtannxmawr.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shangyingyoupin.top/Article/details/gtawmvfetx.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.sysykeji.top/Article/details/gtfmbubzug.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.fengsongda.top/Article/details/gtjxdlhord.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.aizwys.cn/Article/details/gtdrlqwrcu.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.gogol.net.cn/Article/details/gtjkwrnpvo.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.hnxiangtu.top/Article/details/gtcingtlpn.html

[L04] 设置超时
来源：http://dali.chenjidiqi.icu/Article/details/gtwabgbevm.html

Py:   requests.get(url, timeout=5)
来源：http://dali.iojbl.cn/Article/details/gtcobzvdgk.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.cucudq.cn/Article/details/gtopovvcfb.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhongyouzk.top/Article/details/gthnofatye.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinyuanbaomall.cn/Article/details/gttjdqpfak.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zycfv.cn/Article/details/gtygpgoeqi.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.316326.xyz/Article/details/gtbiyxpiia.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.havefunace.top/Article/details/gttarczdwv.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.meibo888.top/Article/details/gtmuzclyui.html

[L05] 上传文件（multipart）
来源：http://dali.jyoumei.cn/Article/details/gtehpwprso.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.ydzc1.top/Article/details/gteualscoi.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.vqdsnc.cn/Article/details/gthwmvbszb.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.smart0.xyz/Article/details/gtadqrnwbo.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.nanxinkj.top/Article/details/gtyatsmyue.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.xuanzx.com/Article/details/gtljukdhke.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jiagoushi.top/Article/details/gtxoazgyyf.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.shanyushiyangtech.top/Article/details/gtqemlwlks.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.chenzaomai.com/Article/details/gtqdtknbjh.html

[L06] 解析响应为 JSON
来源：http://dali.yuxming.cn/Article/details/gtawgxzisj.html

Py:   resp.json()
来源：http://dali.smart0.xyz/Article/details/gtggwouqhs.html

PHP:  json_decode($body, true);
来源：http://dali.hfpthk.cn/Article/details/gtflickbil.html

JS:   await resp.json()
来源：http://dali.aibaodan.cn/Article/details/gtbrhlztyk.html

TS:   await resp.json()
来源：http://dali.jyoumei.cn/Article/details/gtipujbdjr.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.aizwys.cn/Article/details/gtukxmasrh.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.dianchejie.cn/Article/details/gtlkacprxy.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yonumen.top/Article/details/gtoxuiprqn.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.aibaodan.cn/Article/details/gtakxkyuvn.html

[L07] 处理 HTTP 状态码
来源：http://dali.jlsjyb.cn/Article/details/gtfsixmnqz.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.gogol.net.cn/Article/details/gtdtxwavlf.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.aizwys.cn/Article/details/gtiuowqwfi.html

JS:   resp.ok;  resp.status
来源：http://dali.zhiwuduotai.top/Article/details/gtgvzfpazu.html

TS:   resp.ok;  resp.status
来源：http://dali.shangyingyoupin.top/Article/details/gtvwapixef.html

Java: resp.statusCode()
来源：http://dali.dashuyun.cn/Article/details/gtrearxwea.html

Go:   resp.StatusCode
来源：http://dali.shanyushiyangtech.top/Article/details/gtgnvhbvkl.html

Ruby: resp.code.to_i
来源：http://dali.birdmap.top/Article/details/gtqnvarrvd.html

C#:   (int)resp.StatusCode
来源：http://dali.dashuyun.cn/Article/details/gtpyidwjkb.html

[L08] 并发请求多个地址
来源：http://dali.zhiwuduotai.top/Article/details/gtowkzotgw.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.dashuyun.cn/Article/details/gtqqgxzqjo.html

PHP:  curl_multi_init() 系列
来源：http://dali.aibaodan.cn/Article/details/gtrmwntgou.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.birdmap.top/Article/details/gtfrfflfas.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.chenlongwang.top/Article/details/gtdgtjrkrh.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yangfankeji.com/Article/details/gtqkkglkvm.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.gogol.net.cn/Article/details/gtvqwrxoxx.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jinqigfzy.top/Article/details/gtfcilxvzh.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gtyewsneyy.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtmnpinekr.html

M. 命令行 / 进程 / 环境
来源：http://dali.hywenlv.cn/Article/details/gtwqmnbidn.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtlnnbrlyj.html

[M01] 读取命令行参数
来源：http://dali.bjfxy.top/Article/details/gtbcarwidf.html

Py:   sys.argv[1:]
来源：http://dali.cdnleiting.top/Article/details/gtepicdeiq.html

PHP:  $argv;  $argc;
来源：http://dali.sweek.top/Article/details/gtzcalncwu.html

JS:   process.argv.slice(2)
来源：http://dali.chenjidiqi.icu/Article/details/gtoykagsus.html

TS:   process.argv.slice(2)
来源：http://dali.hfpthk.cn/Article/details/gtiraucphz.html

Java: args 数组（main 方法参数）
来源：http://dali.zhiwuduotai.top/Article/details/gtjkerprla.html

Go:   os.Args[1:]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwcpaekde.html

Ruby: ARGV
来源：http://dali.yj20258.top/Article/details/gteeywctmw.html

C#:   args 数组（Main 方法参数）
来源：http://dali.hywenlv.cn/Article/details/gtahywmjfc.html

[M02] 读取环境变量
来源：http://dali.tanke756.top/Article/details/gthhhsvwee.html

Py:   os.environ.get("HOME")
来源：http://dali.xuetiantiany.cn/Article/details/gtlujizbyh.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.redwolf501.top/Article/details/gtlciuyvro.html

JS:   process.env.HOME
来源：http://dali.fengsongda.top/Article/details/gtcxgmurmo.html

TS:   process.env.HOME
来源：http://dali.yuxming.cn/Article/details/gtlesqamql.html

Java: System.getenv("HOME")
来源：http://dali.havefunace.top/Article/details/gtjteqqlrp.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.tianlin.xyz/Article/details/gtksoppkoe.html

Ruby: ENV["HOME"]
来源：http://dali.redwolf501.top/Article/details/gtywhcydlr.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.sxryk.cn/Article/details/gtilxalrud.html

[M03] 执行外部命令
来源：http://dali.sufxvd.cn/Article/details/gtdgvqkcvc.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.fengsongda.top/Article/details/gtqqvjdntt.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.9152youxi.cn/Article/details/gtpatjxskw.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.sufxvd.cn/Article/details/gtaaxabpei.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.gogol.net.cn/Article/details/gtvpjfexhv.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jqgfzy.top/Article/details/gtyfqqegha.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yongpay.top/Article/details/gtgyqctjcm.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhongyouzk.top/Article/details/gtqvpjbzvn.html

C#:   Process.Start("ls", "-l");
来源：http://dali.gzhubu.top/Article/details/gtcltprgjd.html

[M04] 获取当前工作目录
来源：http://dali.iojbl.cn/Article/details/gtopixhitt.html

Py:   os.getcwd()
来源：http://dali.nwbrower.top/Article/details/gtbyjoldmw.html

PHP:  getcwd();
来源：http://dali.pengpengdd.cyou/Article/details/gttypipwgk.html

JS:   process.cwd()
来源：http://dali.yj20258.top/Article/details/gtmweecssw.html

TS:   process.cwd()
来源：http://dali.gzhubu.top/Article/details/gtclwparym.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yuanzhike.top/Article/details/gtibvfnhze.html

Go:   os.Getwd()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlpxhrdng.html

Ruby: Dir.pwd
来源：http://dali.shanyushiyangtech.top/Article/details/gtcuffmyqz.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.nwbrower.top/Article/details/gtxognsdnm.html

[M05] 设置退出码
来源：http://dali.snrcjt.cn/Article/details/gtwzhikpio.html

Py:   sys.exit(1)
来源：http://dali.0kj1m.cn/Article/details/gtcthlxxwf.html

PHP:  exit(1);
来源：http://dali.guannengcc.top/Article/details/gtgskupsvn.html

JS:   process.exit(1)
来源：http://dali.cucudq.cn/Article/details/gtfbhfasto.html

TS:   process.exit(1)
来源：http://dali.yanxiufei.cn/Article/details/gtbhchppbw.html

Java: System.exit(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaqmenjtb.html

Go:   os.Exit(1)
来源：http://dali.zhiwuduotai.top/Article/details/gtsegjwene.html

Ruby: exit 1
来源：http://dali.shzxlz.cn/Article/details/gtvfiahlny.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yuanzhike.top/Article/details/gtvunobgnc.html

[M06] 向标准错误输出
来源：http://dali.svipenyu.cn/Article/details/gtyzqwfpji.html

Py:   print("err", file=sys.stderr)
来源：http://dali.daria6918.cn/Article/details/gtdxszpgyl.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.shanyushiyangtech.top/Article/details/gtrydmduct.html

JS:   console.error("err")
来源：http://dali.smart0.xyz/Article/details/gtgbwfrjyl.html

TS:   console.error("err")
来源：http://dali.daxiang520.top/Article/details/gtgkbpabky.html

Java: System.err.println("err")
来源：http://dali.cqqwz.cn/Article/details/gtewmcscsf.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.gogol.net.cn/Article/details/gtgjfixizm.html

Ruby: warn "err"
来源：http://dali.jinqigufen.top/Article/details/gtdrupqgfb.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhengqikj.top/Article/details/gtienyypxm.html

[M07] 判断是否为主入口
来源：http://dali.wangshuangyany.cn/Article/details/gtcsvkzokr.html

Py:   if __name__ == "__main__":
来源：http://dali.jinqigfzy.top/Article/details/gtghivjxty.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.shzxlz.cn/Article/details/gtjmbxpfjk.html

JS:   require.main === module
来源：http://dali.hnqzz.top/Article/details/gtmhqeroak.html

TS:   require.main === module
来源：http://dali.jinqigfzy.top/Article/details/gtgtiyuasx.html

Java: public static void main(String[] args)
来源：http://dali.sysykeji.top/Article/details/gtdmjtlmka.html

Go:   func main()
来源：http://dali.sweek.top/Article/details/gtnfkngxmk.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.chenjidiqi.icu/Article/details/gtbeupblev.html

C#:   static void Main(string[] args)
来源：http://dali.cqqwz.cn/Article/details/gtxwpqxubh.html

[M08] 获取系统与运行时信息
来源：http://dali.hysaishi.cn/Article/details/gtkohqxdwp.html

Py:   platform.system();  platform.python_version()
来源：http://dali.sweek.top/Article/details/gtsiqarnou.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.shangyingyoupin.top/Article/details/gtfvwbohum.html

JS:   process.platform;  process.version
来源：http://dali.jiagoushi.top/Article/details/gtsqeneisw.html

TS:   process.platform;  process.version
来源：http://dali.pengpengdd.cyou/Article/details/gtrajfqodr.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.tian-w.cn/Article/details/gtzmckjnpn.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.chenjidiqi.icu/Article/details/gtmogjhvtw.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.shuidangran.top/Article/details/gtzzahjelz.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.xuetiantiany.cn/Article/details/gtyrejidkj.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtkwmnnuwu.html

N. 数据结构与算法
来源：http://dali.pycfn.com/Article/details/gtwjbyppih.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtfyhtzcdk.html

[N01] 二分查找（有序数组）
来源：http://dali.jqgufenzy.top/Article/details/gtqgxuiknj.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.smart0.xyz/Article/details/gtynxzquwv.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtohclvtca.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.smart0.xyz/Article/details/gtwllcabam.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.chenlongwang.top/Article/details/gtsenyasdj.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.dianchejie.cn/Article/details/gtgsnbdqbp.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhiwuduotai.top/Article/details/gtyiltqmsb.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.xuanzx.com/Article/details/gtdjawbykq.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.c1oappe.top/Article/details/gtthrvladm.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.tian-w.cn/Article/details/gtcukqczql.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xuanzx.com/Article/details/gtqrpquhuq.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jinqigufen.top/Article/details/gtaneviilg.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.tianlin.xyz/Article/details/gtljncmqot.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhengqikj.top/Article/details/gtpnqjdmzp.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.ehwqpu.com/Article/details/gtxwlmbasm.html

Go:   slices.Sort(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gtvehqjtew.html

Ruby: arr.sort
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmajstxbl.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yanxiufei.cn/Article/details/gtzmntmvtf.html

[N03] 快速排序（分治示例）
来源：http://dali.shanyushiyangtech.top/Article/details/gtzmfzglmv.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.snrcjt.cn/Article/details/gtgacdxiwl.html

PHP:  // 递归实现，或用 usort
来源：http://dali.iojbl.cn/Article/details/gtwkwenogy.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuwuercut.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jiagoushi.top/Article/details/gtktpbjsng.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.mhx1999.top/Article/details/gtqufcohfi.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jinqigufen.top/Article/details/gtcpgcvdcl.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.ywan-chungtsiang.top/Article/details/gteqnlvjjk.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhengqikj.top/Article/details/gttnyqiutj.html

[N04] 斐波那契数列
来源：http://dali.daxiang520.top/Article/details/gtynhxmqbe.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jqgufenzy.top/Article/details/gtznhewspd.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjarpuhsy.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ivvv.top/Article/details/gtjdbvkoql.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.havefunace.top/Article/details/gtmjackamf.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.daria6918.cn/Article/details/gthrxhmivn.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbudsiupv.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jqgufenzy.top/Article/details/gtartiwhak.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.c1oappe.top/Article/details/gtpmolycrq.html

[N05] 最大公约数
来源：http://dali.andypj.xyz/Article/details/gtbqbpnofu.html

Py:   math.gcd(a, b)
来源：http://dali.dashuyun.cn/Article/details/gteghrjhva.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yj202588.top/Article/details/gtvbiiiicu.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.fzhhl.top/Article/details/gtmccpmrfj.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.haohaochexian.top/Article/details/gtlomphvvt.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.shanyushiyangtech.top/Article/details/gtwycufusp.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yongpay.top/Article/details/gtrloxiwwt.html

Ruby: a.gcd(b)
来源：http://dali.pengpengdd.cyou/Article/details/gtyuwmyacz.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.hnqzz.top/Article/details/gtubqinglo.html

[N06] 判断回文字符串
来源：http://dali.wangdashe.top/Article/details/gtjwngtswq.html

Py:   s == s[::-1]
来源：http://dali.yuanzhike.top/Article/details/gtbzflxrhb.html

PHP:  $s === strrev($s);
来源：http://dali.chenlongwang.top/Article/details/gtatexqalw.html

JS:   s === [...s].reverse().join("")
来源：http://dali.nanxinkj.top/Article/details/gtfhfawegz.html

TS:   s === [...s].reverse().join("")
来源：http://dali.nanxinkj.top/Article/details/gtvafdhzpa.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.chenjidiqi.icu/Article/details/gtqztuqgbd.html

Go:   // 双指针从两端比较
来源：http://dali.chenlongwang.top/Article/details/gtkbiukrrr.html

Ruby: s == s.reverse
来源：http://dali.feifeiyinyue.top/Article/details/gtszbldfzt.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.aizwys.cn/Article/details/gtzavafwgs.html

[N07] 两数之和（返回下标）
来源：http://dali.daxiang520.top/Article/details/gtjkiiqnwn.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.sweek.top/Article/details/gtmzosbyya.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.316326.xyz/Article/details/gtxvnlbrlr.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yuanzhike.top/Article/details/gtickpdrwi.html

TS:   // 手写 Map<string, number>
来源：http://dali.daxiang520.top/Article/details/gtiwsekujt.html

Java: // 手写 HashMap
来源：http://dali.wangdashe.top/Article/details/gtbmjbevhl.html

Go:   // 手写 map[int]int
来源：http://dali.wangshuangyany.cn/Article/details/gtmncrkkod.html

Ruby: // 手写 Hash
来源：http://dali.shanyushiyangkeji.top/Article/details/gtndlifwep.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.0kj1m.cn/Article/details/gttjtfpihy.html

[N08] 生成全排列
来源：http://dali.daria6918.cn/Article/details/gtmcfvqkng.html

Py:   itertools.permutations(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtccupzpjl.html

PHP:  // 手写递归交换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbzsysgkp.html

JS:   // 手写回溯递归
来源：http://dali.chenlongwang.top/Article/details/gtufnnuzfi.html

TS:   // 手写回溯递归
来源：http://dali.havefunace.top/Article/details/gtmheybghw.html


<!-- 参考信息 -->