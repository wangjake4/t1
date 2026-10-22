代发 wailian999

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtxcgtidfw.html

K. JSON 与序列化
来源：http://dali.zhixingplan.top/Article/details/gtxcztnqxw.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtaxuoqciw.html

[K01] 对象转 JSON 字符串
来源：http://dali.9152youxi.cn/Article/details/gtppykcqdh.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.wangdashe.top/Article/details/gtjihddvqg.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yj202588.top/Article/details/gtzhzexodw.html

JS:   JSON.stringify(obj)
来源：http://dali.nanxinkj.top/Article/details/gtmokfzrws.html

TS:   JSON.stringify(obj)
来源：http://dali.hywenlv.cn/Article/details/gtwvgwjojr.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.havefunace.top/Article/details/gttcwydamc.html

Go:   json.Marshal(obj)
来源：http://dali.ehwqpu.com/Article/details/gtnqsxvikb.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yj202588.top/Article/details/gtxvxkyjqa.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yj20258.top/Article/details/gtywaztmur.html

[K02] JSON 字符串转对象
来源：http://dali.jyoumei.cn/Article/details/gtijqxjggk.html

Py:   json.loads(s)
来源：http://dali.0kj1m.cn/Article/details/gtbrezcyul.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yongpay.top/Article/details/gtutlupbih.html

JS:   JSON.parse(s)
来源：http://dali.xylfe.cn/Article/details/gtacmfddeq.html

TS:   JSON.parse(s)
来源：http://dali.gogol.net.cn/Article/details/gtbzwdptul.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxyvbigyj.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfqwsbndi.html

Ruby: JSON.parse(s)
来源：http://dali.zhoulong.xyz/Article/details/gttinncfua.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.mhx1999.top/Article/details/gtiukrnfnl.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.0kj1m.cn/Article/details/gtnmcknpaa.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtifgqhdwl.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.pycfn.com/Article/details/gtxqwqpxax.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvqwztgfv.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhongyouzk.top/Article/details/gtklvqqbno.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.sxryk.cn/Article/details/gtsdlksbbr.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.wangdashe.top/Article/details/gtdburpxmr.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.snrcjt.cn/Article/details/gtodfxgrun.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yanxiufei.cn/Article/details/gtmgmeittu.html

[K04] 读取 JSON 文件
来源：http://dali.hysaishi.cn/Article/details/gttqcbvzkh.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.smart0.xyz/Article/details/gthbomwtnv.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvroxypip.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yuanzhike.top/Article/details/gtghhrjnsx.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.chenlongwang.top/Article/details/gtrhxdhyeu.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.shangyingyoupin.top/Article/details/gtrdfyupqn.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtawnyuzpz.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yvedp.cn/Article/details/gtbwxfoxdo.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.aizwys.cn/Article/details/gtmseymnfy.html

[K05] 深拷贝对象
来源：http://dali.daxiang520.top/Article/details/gtxonoxlxc.html

Py:   copy.deepcopy(obj)
来源：http://dali.hysaishi.cn/Article/details/gtgqqeeasc.html

PHP:  unserialize(serialize($obj));
来源：http://dali.hammf.cn/Article/details/gtuuabfolc.html

JS:   structuredClone(obj)
来源：http://dali.jyoumei.cn/Article/details/gtyyxjkxvf.html

TS:   structuredClone(obj)
来源：http://dali.cqqwz.cn/Article/details/gtaywqnqwq.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.ehwqpu.com/Article/details/gtabtwgqmk.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhoulong.xyz/Article/details/gtmwdukxxs.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.daria6918.cn/Article/details/gtldflkvqg.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.ivvv.top/Article/details/gtjhyckqcz.html

[K06] 解析 URL 查询串
来源：http://dali.mhx1999.top/Article/details/gtkwcuhimu.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmshvoifd.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zycfv.cn/Article/details/gthqjminyt.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jyoumei.cn/Article/details/gtwnjnxvvl.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ppjwa.cn/Article/details/gtwvngjhkj.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yueranfly.top/Article/details/gtrpjusihb.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.9152youxi.cn/Article/details/gtbmmqszbz.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtibipirpf.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.haohaochexian.top/Article/details/gtknbshkqz.html

[K07] 进制转换
来源：http://dali.aibaodan.cn/Article/details/gtwokvalgi.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.aibaodan.cn/Article/details/gtvdapgrxg.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jinghuilouyu.cn/Article/details/gtqmayowxu.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.gogol.net.cn/Article/details/gtfwdhxhfg.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.chenjidiqi.icu/Article/details/gtbnvghjxm.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.shzxlz.cn/Article/details/gtdsftmoef.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.ybcxt.top/Article/details/gthuayvpnd.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.guowangkeji.top/Article/details/gtabspxcsb.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.nanxinkj.top/Article/details/gtwjtyonyr.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.sweek.top/Article/details/gtvvjchliz.html

Py:   pickle.dumps(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gtijwkbowh.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.sxryk.cn/Article/details/gtvliqzdjl.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yj20258.top/Article/details/gtidkxejfu.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jqgufenzy.top/Article/details/gtkrsjvtdp.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.birdmap.top/Article/details/gtmhwuqsar.html

Go:   encoding/gob
来源：http://dali.ydzc1.top/Article/details/gtwlkbkmob.html

Ruby: Marshal.dump(obj)
来源：http://dali.ydzc1.top/Article/details/gtdsqenhod.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjfklghee.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtuhklrvkk.html

L. 网络请求
来源：http://dali.sysykeji.top/Article/details/gtmfrgxsxp.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtufkkcnhg.html

[L01] 发送 GET 请求
来源：http://dali.ppjwa.cn/Article/details/gtknadeiqu.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.hfpthk.cn/Article/details/gtmtyqtnoc.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.chenjidiqi.icu/Article/details/gtyhoivrtr.html

JS:   await fetch(url)
来源：http://dali.cdnleiting.top/Article/details/gtrbqgcnvl.html

TS:   await fetch(url)
来源：http://dali.birdmap.top/Article/details/gtjzlpuylc.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.wangshuangyany.cn/Article/details/gtprrmfyts.html

Go:   resp, err := http.Get(url)
来源：http://dali.hongshengwenyu.top/Article/details/gtojjgtnyw.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.daxiang520.top/Article/details/gtkzsebalb.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.cheryme.top/Article/details/gtlhffbbuu.html

[L02] 发送 POST JSON
来源：http://dali.xuanzx.com/Article/details/gtxwfeukoz.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.shangyingyoupin.top/Article/details/gtxemoebqd.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yanxiufei.cn/Article/details/gtjfqvstka.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yuanzhike.top/Article/details/gtnotpltxh.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shanyushiyangtech.top/Article/details/gtuscbqhwz.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hongshengwenyu.top/Article/details/gtkzbhfosp.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yuxming.cn/Article/details/gttndpeyar.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.sufxvd.cn/Article/details/gtrsxenovp.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.ybcxt.top/Article/details/gtqcvuanfb.html

[L03] 设置自定义请求头
来源：http://dali.yanxiufei.cn/Article/details/gtfvguadlp.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.shzxlz.cn/Article/details/gtfsyifaqy.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.gzhubu.top/Article/details/gtsnqkmcpd.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.tian-w.cn/Article/details/gtkrljpkjx.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.wangdashe.top/Article/details/gtfcqfvzyk.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yanxiufei.cn/Article/details/gtiuycdayr.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.havefunace.top/Article/details/gtzdgfxkiu.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.wangshuangyany.cn/Article/details/gtbglgqzpm.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.smart0.xyz/Article/details/gtwizsgoyi.html

[L04] 设置超时
来源：http://dali.yueranfly.top/Article/details/gtozethsnw.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jyoumei.cn/Article/details/gtmawohbhf.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.cheryme.top/Article/details/gtxyeafenu.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.0kj1m.cn/Article/details/gtgyzujwat.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cdnleiting.top/Article/details/gtlsjbhpwp.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.gogol.net.cn/Article/details/gtyqmhcofz.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yanxiufei.cn/Article/details/gteeqhsfwz.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.andypj.xyz/Article/details/gtssjgehta.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.daxiang520.top/Article/details/gticdtexrg.html

[L05] 上传文件（multipart）
来源：http://dali.yuanzhike.top/Article/details/gtlrglbpyy.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.0kj1m.cn/Article/details/gtkjfovxmd.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.iojbl.cn/Article/details/gtmdyrchkm.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.haohaochexian.top/Article/details/gtsbouftqz.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jqgfzy.top/Article/details/gtjhzqvfnh.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.vqdsnc.cn/Article/details/gtmixakkgk.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.dianchejie.cn/Article/details/gtlytfkcqs.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.hnxiangtu.top/Article/details/gtcldivxdb.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.cqqwz.cn/Article/details/gtgbtorpms.html

[L06] 解析响应为 JSON
来源：http://dali.ybcxt.top/Article/details/gtyaqbnyea.html

Py:   resp.json()
来源：http://dali.tianlin.xyz/Article/details/gtepvvwfnw.html

PHP:  json_decode($body, true);
来源：http://dali.zhoulong.xyz/Article/details/gtqxtgonhs.html

JS:   await resp.json()
来源：http://dali.yj20258888.top/Article/details/gtoyhhmhfx.html

TS:   await resp.json()
来源：http://dali.sweek.top/Article/details/gtavnxqtxj.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.shanyushiyangtech.top/Article/details/gtylymwrdz.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.cqqwz.cn/Article/details/gtgwdtzfkq.html

Ruby: JSON.parse(resp.body)
来源：http://dali.sweek.top/Article/details/gtzcfknhgf.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.aibaodan.cn/Article/details/gttnoenczu.html

[L07] 处理 HTTP 状态码
来源：http://dali.cashguo.top/Article/details/gthyutrkhp.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.sysykeji.top/Article/details/gtsctgjuva.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.sxryk.cn/Article/details/gtwdbhowvi.html

JS:   resp.ok;  resp.status
来源：http://dali.zhengqikj.top/Article/details/gtwhqvfrwy.html

TS:   resp.ok;  resp.status
来源：http://dali.pycfn.com/Article/details/gtlkvtizka.html

Java: resp.statusCode()
来源：http://dali.zycfv.cn/Article/details/gtxeimdyjm.html

Go:   resp.StatusCode
来源：http://dali.zhongyouzk.top/Article/details/gtyjvjinbk.html

Ruby: resp.code.to_i
来源：http://dali.haohaochexian.top/Article/details/gtoitatucx.html

C#:   (int)resp.StatusCode
来源：http://dali.nanxinkj.top/Article/details/gtkgzmifek.html

[L08] 并发请求多个地址
来源：http://dali.zhaomingkeji.xyz/Article/details/gtasbpijii.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jianghu66.top/Article/details/gtkiqjrwuh.html

PHP:  curl_multi_init() 系列
来源：http://dali.shzxlz.cn/Article/details/gtksoujceh.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.mhx1999.top/Article/details/gtjmznqihj.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.birdmap.top/Article/details/gttooqgjjm.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yj202588.top/Article/details/gteepvznyy.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.xuanzx.com/Article/details/gtlxyugaak.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.nwbrower.top/Article/details/gtptcnfkbf.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jinghuilouyu.cn/Article/details/gtddjqhdmr.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtblszohef.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhengqikj.top/Article/details/gtrhdrraza.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtshfvtceq.html

[M01] 读取命令行参数
来源：http://dali.jinghuilouyu.cn/Article/details/gtbwzqgnlr.html

Py:   sys.argv[1:]
来源：http://dali.yj20258.top/Article/details/gtxedcnvnr.html

PHP:  $argv;  $argc;
来源：http://dali.aibaodan.cn/Article/details/gtlofixvns.html

JS:   process.argv.slice(2)
来源：http://dali.zycfv.cn/Article/details/gtpgrqxatp.html

TS:   process.argv.slice(2)
来源：http://dali.cheryme.top/Article/details/gtbwnqjkkf.html

Java: args 数组（main 方法参数）
来源：http://dali.yueranfly.top/Article/details/gtircmdgfa.html

Go:   os.Args[1:]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrximkhhv.html

Ruby: ARGV
来源：http://dali.svipenyu.cn/Article/details/gtdkfjedvs.html

C#:   args 数组（Main 方法参数）
来源：http://dali.hysaishi.cn/Article/details/gtvbvoeuml.html

[M02] 读取环境变量
来源：http://dali.feifeiyinyue.top/Article/details/gtglvwdbsv.html

Py:   os.environ.get("HOME")
来源：http://dali.cdnleiting.top/Article/details/gtamsgbdsv.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.xylfe.cn/Article/details/gtlrrcetyq.html

JS:   process.env.HOME
来源：http://dali.cucudq.cn/Article/details/gtyppadkpn.html

TS:   process.env.HOME
来源：http://dali.gotoacloud.top/Article/details/gtaxjbnzjk.html

Java: System.getenv("HOME")
来源：http://dali.hywenlv.cn/Article/details/gtjvbohvbx.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jiagoushi.top/Article/details/gtwiookiti.html

Ruby: ENV["HOME"]
来源：http://dali.c1oappe.top/Article/details/gtabfuxcaf.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.pengpengdd.cyou/Article/details/gtfhqxcnuz.html

[M03] 执行外部命令
来源：http://dali.jinqigfzy.top/Article/details/gtocisndxp.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jinghuilouyu.cn/Article/details/gtcmzyeyfu.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.fzhhl.top/Article/details/gtxdgmnmnt.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jqgfzy.top/Article/details/gthlsbntey.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.mhx1999.top/Article/details/gtabftpnko.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.xuetiantiany.cn/Article/details/gtsentntxr.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.xinyue.icu/Article/details/gtwgmplbkm.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdmdkuwuq.html

C#:   Process.Start("ls", "-l");
来源：http://dali.316326.xyz/Article/details/gtinxccswv.html

[M04] 获取当前工作目录
来源：http://dali.daxiang520.top/Article/details/gtlhjocntq.html

Py:   os.getcwd()
来源：http://dali.jiagoushi.top/Article/details/gtcsodrxpg.html

PHP:  getcwd();
来源：http://dali.bjfxy.top/Article/details/gtweenqczt.html

JS:   process.cwd()
来源：http://dali.smart0.xyz/Article/details/gtotismlvl.html

TS:   process.cwd()
来源：http://dali.jinqigfzy.top/Article/details/gtuxddlpew.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.fzhhl.top/Article/details/gtjlztwgcb.html

Go:   os.Getwd()
来源：http://dali.daria6918.cn/Article/details/gtxdfdkzct.html

Ruby: Dir.pwd
来源：http://dali.ehwqpu.com/Article/details/gtqgfpbkfp.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.cqqwz.cn/Article/details/gtrdegijkd.html

[M05] 设置退出码
来源：http://dali.gogol.net.cn/Article/details/gtwytvavee.html

Py:   sys.exit(1)
来源：http://dali.316326.xyz/Article/details/gtdyajlsws.html

PHP:  exit(1);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzmkhkwci.html

JS:   process.exit(1)
来源：http://dali.cheryme.top/Article/details/gtwdxaeibs.html

TS:   process.exit(1)
来源：http://dali.guowangkeji.top/Article/details/gtieoxsfnc.html

Java: System.exit(1)
来源：http://dali.quarkkingdee.top/Article/details/gtxgpiccaf.html

Go:   os.Exit(1)
来源：http://dali.snrcjt.cn/Article/details/gtzefbcfyh.html

Ruby: exit 1
来源：http://dali.jyoumei.cn/Article/details/gtsanvdvbj.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.iojbl.cn/Article/details/gtqnrpgfla.html

[M06] 向标准错误输出
来源：http://dali.tian-w.cn/Article/details/gtirbduzaq.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zycfv.cn/Article/details/gtflxtkinq.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.chenzaomai.com/Article/details/gtvwqaaorc.html

JS:   console.error("err")
来源：http://dali.jqgufenzy.top/Article/details/gthwvcwada.html

TS:   console.error("err")
来源：http://dali.tanke756.top/Article/details/gteizdsokk.html

Java: System.err.println("err")
来源：http://dali.cashguo.top/Article/details/gtnsqalnrs.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhongyouzk.top/Article/details/gtakexnlup.html

Ruby: warn "err"
来源：http://dali.yanxiufei.cn/Article/details/gtdopffvrm.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhongyouzk.top/Article/details/gtdujduuvw.html

[M07] 判断是否为主入口
来源：http://dali.zdqjudy.top/Article/details/gtuebatwnm.html

Py:   if __name__ == "__main__":
来源：http://dali.yj202588.top/Article/details/gttsllspae.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.vqdsnc.cn/Article/details/gtoicvytoi.html

JS:   require.main === module
来源：http://dali.ivvv.top/Article/details/gtgzorkxwj.html

TS:   require.main === module
来源：http://dali.tanke756.top/Article/details/gtexgvjnah.html

Java: public static void main(String[] args)
来源：http://dali.redwolf501.top/Article/details/gtgmbyfxxg.html

Go:   func main()
来源：http://dali.zhengqikj.top/Article/details/gtihgeovep.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.snrcjt.cn/Article/details/gtbwvzbejw.html

C#:   static void Main(string[] args)
来源：http://dali.cucudq.cn/Article/details/gtfkmgbiey.html

[M08] 获取系统与运行时信息
来源：http://dali.cqqwz.cn/Article/details/gtugkjfaer.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yongpay.top/Article/details/gtqvpsqyjk.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zycfv.cn/Article/details/gtkholvytw.html

JS:   process.platform;  process.version
来源：http://dali.chenlongwang.top/Article/details/gtsicjqfly.html

TS:   process.platform;  process.version
来源：http://dali.xylfe.cn/Article/details/gtqryuotrj.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.daxiang520.top/Article/details/gtfgrblwdo.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jianghu66.top/Article/details/gtbcuewmwx.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.ehwqpu.com/Article/details/gtejrkavwd.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hnqzz.top/Article/details/gtvzlerzwm.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtuxscqhae.html

N. 数据结构与算法
来源：http://dali.ehwqpu.com/Article/details/gthtnrydmg.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtsxvqlkql.html

[N01] 二分查找（有序数组）
来源：http://dali.yueranfly.top/Article/details/gtejnrbqur.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.gogol.net.cn/Article/details/gtelhkgwpf.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.cdnleiting.top/Article/details/gtyzpsvszv.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.wangdashe.top/Article/details/gtvcumitqa.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hnxiangtu.top/Article/details/gtbrrzizhc.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yuxming.cn/Article/details/gtqvhnkfpt.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.mhx1999.top/Article/details/gtfqsjxjfj.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.sweek.top/Article/details/gtsumkhhkx.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.hnxiangtu.top/Article/details/gtyggczluy.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.vqdsnc.cn/Article/details/gtnbepypzt.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ybcxt.top/Article/details/gthttimjos.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.chenlongwang.top/Article/details/gtnwrzsklu.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.9152youxi.cn/Article/details/gttanhdgam.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.aizwys.cn/Article/details/gtzvjtohxe.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.xuetiantiany.cn/Article/details/gthbfxlxil.html

Go:   slices.Sort(arr)
来源：http://dali.yuanzhike.top/Article/details/gtuignjbkg.html

Ruby: arr.sort
来源：http://dali.chenzaomai.com/Article/details/gthozuoqri.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.svipenyu.cn/Article/details/gtecujftch.html

[N03] 快速排序（分治示例）
来源：http://dali.cdnleiting.top/Article/details/gtnzifwgmt.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.tanke756.top/Article/details/gtwkmjakwn.html

PHP:  // 递归实现，或用 usort
来源：http://dali.guowangkeji.top/Article/details/gtvrprqqki.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.kuanghao11.cn/Article/details/gtchgytvnj.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zycfv.cn/Article/details/gtrokkklzc.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.sxryk.cn/Article/details/gtfalwvsvz.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.kuanghao11.cn/Article/details/gtpoabwqcc.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.hongshengwenyu.top/Article/details/gtyuxfzeor.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jqgfzy.top/Article/details/gtuuorggcm.html

[N04] 斐波那契数列
来源：http://dali.cashguo.top/Article/details/gtidswgtsz.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yj20258.top/Article/details/gtgaltsesc.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yj20258888.top/Article/details/gtelbgaufh.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yanxiufei.cn/Article/details/gtizpnrqau.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yuanzhike.top/Article/details/gtfsclaarj.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jianghu66.top/Article/details/gtfaqfbchw.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhixingplan.top/Article/details/gtcbixixgz.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.meibo888.top/Article/details/gthrcnodca.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfnhdyfhv.html

[N05] 最大公约数
来源：http://dali.zhoulong.xyz/Article/details/gthxbtrblz.html

Py:   math.gcd(a, b)
来源：http://dali.ppjwa.cn/Article/details/gtpyamacvh.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkfwhwduo.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.aizwys.cn/Article/details/gtfwmslzpg.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yangfankeji.com/Article/details/gtagsswoss.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.aibaodan.cn/Article/details/gtnzlqilhz.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.pengpengdd.cyou/Article/details/gtamkinfqk.html

Ruby: a.gcd(b)
来源：http://dali.chenlongwang.top/Article/details/gtpjakggrm.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.ivvv.top/Article/details/gtrmvzllvv.html

[N06] 判断回文字符串
来源：http://dali.svipenyu.cn/Article/details/gtiufqyylm.html

Py:   s == s[::-1]
来源：http://dali.nwbrower.top/Article/details/gtggbbxmso.html

PHP:  $s === strrev($s);
来源：http://dali.redwolf501.top/Article/details/gtjydrbhta.html

JS:   s === [...s].reverse().join("")
来源：http://dali.wangshuangyany.cn/Article/details/gtamxkbqto.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yj20258.top/Article/details/gtmgwckwzo.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jinghuilouyu.cn/Article/details/gtihhuzwem.html

Go:   // 双指针从两端比较
来源：http://dali.ivvv.top/Article/details/gtpmxqksaq.html

Ruby: s == s.reverse
来源：http://dali.jianghu66.top/Article/details/gtcgwccrqa.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.shuidangran.top/Article/details/gtyysfllta.html

[N07] 两数之和（返回下标）
来源：http://dali.chenlongwang.top/Article/details/gtzkkklxco.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.tianlin.xyz/Article/details/gtyekpsdqu.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.cheryme.top/Article/details/gtjgjpnmag.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.daria6918.cn/Article/details/gtxxnsscqm.html

TS:   // 手写 Map<string, number>
来源：http://dali.yonumen.top/Article/details/gteddjjdsv.html

Java: // 手写 HashMap
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxoqbmvra.html

Go:   // 手写 map[int]int
来源：http://dali.jyoumei.cn/Article/details/gtozwvnhpr.html

Ruby: // 手写 Hash
来源：http://dali.jinghuilouyu.cn/Article/details/gtutvciqxs.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.cucudq.cn/Article/details/gtdeclmeka.html

[N08] 生成全排列
来源：http://dali.yj20258.top/Article/details/gtlxoffsiz.html

Py:   itertools.permutations(arr)
来源：http://dali.yanxiufei.cn/Article/details/gtdjngjpue.html

PHP:  // 手写递归交换
来源：http://dali.hammf.cn/Article/details/gtucniqoce.html

JS:   // 手写回溯递归
来源：http://dali.yueranfly.top/Article/details/gtjfdjgogp.html

TS:   // 手写回溯递归
来源：http://dali.bjfxy.top/Article/details/gtidlfprir.html

Java: // 手写回溯递归
来源：http://dali.cdnleiting.top/Article/details/gtdwqzaekl.html

Go:   // 手写回溯递归
来源：http://dali.shanyushiyangkeji.top/Article/details/gthlkchocs.html

Ruby: arr.permutation.to_a
来源：http://dali.jianghu66.top/Article/details/gtglguozfo.html

C#:   // 手写回溯递归
来源：http://dali.hongshengwenyu.top/Article/details/gtlviryzhz.html


<!-- 参考信息 -->