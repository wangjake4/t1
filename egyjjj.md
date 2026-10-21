代发 wailian999

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.0kj1m.cn/Article/details/gtrerqyofi.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yj202588.top/Article/details/gthehsrwmm.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.chenlongwang.top/Article/details/gtsgbyfxbs.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqlcjyapw.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtczuivdui.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.ppjwa.cn/Article/details/gtgqwsvnjq.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.cheryme.top/Article/details/gtblukzupj.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jinqigufen.top/Article/details/gtcpajtdme.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtnjvemvtq.html

K. JSON 与序列化
来源：http://dali.yongpay.top/Article/details/gtzvoqpsio.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtsmzvmowv.html

[K01] 对象转 JSON 字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrmylqgxl.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhoulong.xyz/Article/details/gtidmnsbpz.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhiwuduotai.top/Article/details/gtckhaxrfj.html

JS:   JSON.stringify(obj)
来源：http://dali.smart0.xyz/Article/details/gtvrsusjrt.html

TS:   JSON.stringify(obj)
来源：http://dali.cheryme.top/Article/details/gtxjhspajn.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.cucudq.cn/Article/details/gtxkjyseqm.html

Go:   json.Marshal(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtgxxydwdr.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yuxming.cn/Article/details/gthponnbns.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtirrtayfp.html

[K02] JSON 字符串转对象
来源：http://dali.dianchejie.cn/Article/details/gtfortxohi.html

Py:   json.loads(s)
来源：http://dali.tian-w.cn/Article/details/gtdkjccqri.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.dashuyun.cn/Article/details/gtcydhbcja.html

JS:   JSON.parse(s)
来源：http://dali.aizwys.cn/Article/details/gtyfzobmie.html

TS:   JSON.parse(s)
来源：http://dali.shzxlz.cn/Article/details/gtmoewddkg.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yvedp.cn/Article/details/gtrogkazmz.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.pycfn.com/Article/details/gtomhnwnok.html

Ruby: JSON.parse(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtszncxbuh.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhoulong.xyz/Article/details/gtgjuamlip.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jianghu66.top/Article/details/gtitwkhjky.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jqgfzy.top/Article/details/gtjazchhjs.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.dashuyun.cn/Article/details/gtnvrhzvoe.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgbdgytls.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yj202588.top/Article/details/gtxwgurqje.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhijiandao.cn/Article/details/gtvhvxtfjv.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.nanxinkj.top/Article/details/gtsskmnohy.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jiagoushi.top/Article/details/gtxpbbmbdu.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.ppjwa.cn/Article/details/gtmbiaccdq.html

[K04] 读取 JSON 文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgyafmfef.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhiwuduotai.top/Article/details/gtechjvlfm.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyqbfgqha.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hnxiangtu.top/Article/details/gttfoybsfc.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.guowangkeji.top/Article/details/gtwiswhfbx.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yongpay.top/Article/details/gtnhzyudbn.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlnbwwaco.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yuanzhike.top/Article/details/gttsljqxmi.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hammf.cn/Article/details/gtalksdfmu.html

[K05] 深拷贝对象
来源：http://dali.vqdsnc.cn/Article/details/gtmzanjwkc.html

Py:   copy.deepcopy(obj)
来源：http://dali.0kj1m.cn/Article/details/gtgkqrhdqz.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zhengqikj.top/Article/details/gtjwfbsqgo.html

JS:   structuredClone(obj)
来源：http://dali.c1oappe.top/Article/details/gtiwmrpabd.html

TS:   structuredClone(obj)
来源：http://dali.sxryk.cn/Article/details/gtrvmekrtx.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.hysaishi.cn/Article/details/gtgkvlmukq.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.ppjwa.cn/Article/details/gtvtahiebi.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hongshengwenyu.top/Article/details/gtzxfvpfmh.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yuanzhike.top/Article/details/gtqueoeidd.html

[K06] 解析 URL 查询串
来源：http://dali.zdqjudy.top/Article/details/gtevsjazya.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.cucudq.cn/Article/details/gtczbibdel.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.daxiang520.top/Article/details/gtswkhckrq.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shangyingyoupin.top/Article/details/gtdpyxovij.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cucudq.cn/Article/details/gtskervgkk.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhoulong.xyz/Article/details/gthgnkqbvf.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.ppjwa.cn/Article/details/gtrcepxdek.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.smart0.xyz/Article/details/gtykfgjlhj.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.shanyushiyangtech.top/Article/details/gttcgzlswh.html

[K07] 进制转换
来源：http://dali.mhx1999.top/Article/details/gtksawxflb.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.quarkkingdee.top/Article/details/gtvmyisced.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yj202588.top/Article/details/gtpbhsmdls.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.sxryk.cn/Article/details/gtjbkpiwit.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yangfankeji.com/Article/details/gtcatbelyk.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwiexkqva.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yj20258.top/Article/details/gtzgfsssmd.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvaueiknt.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.9152youxi.cn/Article/details/gtfxdnqvjj.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.guannengcc.top/Article/details/gtdsymsnmz.html

Py:   pickle.dumps(obj)
来源：http://dali.cqqwz.cn/Article/details/gttsbxrofe.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jqgfzy.top/Article/details/gtclhusrvt.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.daria6918.cn/Article/details/gtmzejgxli.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxzakreyl.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.shuidangran.top/Article/details/gtiroumcuj.html

Go:   encoding/gob
来源：http://dali.gaohongyu789.top/Article/details/gtysicbsut.html

Ruby: Marshal.dump(obj)
来源：http://dali.meibo888.top/Article/details/gtvnjgluys.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.dashuyun.cn/Article/details/gtmlqhojzi.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtloxcvgvz.html

L. 网络请求
来源：http://dali.tanke756.top/Article/details/gtudqfjsen.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtxcgyrfuq.html

[L01] 发送 GET 请求
来源：http://dali.shzxlz.cn/Article/details/gtaytnmmuj.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.kuanghao11.cn/Article/details/gtunltnicp.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.hywenlv.cn/Article/details/gtiixyujdm.html

JS:   await fetch(url)
来源：http://dali.hnqzz.top/Article/details/gtetglktbe.html

TS:   await fetch(url)
来源：http://dali.jiagoushi.top/Article/details/gtolkirign.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhijiandao.cn/Article/details/gtmbakgyjk.html

Go:   resp, err := http.Get(url)
来源：http://dali.yuanzhike.top/Article/details/gtjlgnwhxg.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.316326.xyz/Article/details/gteotrtkvc.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhongyouzk.top/Article/details/gtpmuqidnk.html

[L02] 发送 POST JSON
来源：http://dali.ywan-chungtsiang.top/Article/details/gttahdzjxh.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.sweek.top/Article/details/gtkxaotwaq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.svipenyu.cn/Article/details/gtehdtzeao.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ppjwa.cn/Article/details/gtazlfluyj.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yj20258888.top/Article/details/gttpucmkzq.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhiwuduotai.top/Article/details/gtoukpaazu.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jyoumei.cn/Article/details/gtkjfemwhs.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yueranfly.top/Article/details/gttotnmlly.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.tanke756.top/Article/details/gtbeknxpsf.html

[L03] 设置自定义请求头
来源：http://dali.zhengqikj.top/Article/details/gtzgcwfsrv.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.hysaishi.cn/Article/details/gtfvfuicyc.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jqgfzy.top/Article/details/gtmnxuyjhl.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shanyushiyangtech.top/Article/details/gtrwmkbfac.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hammf.cn/Article/details/gtfmlzsbyh.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.daxiang520.top/Article/details/gtucuzgosn.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.hnqzz.top/Article/details/gtmxzlvnyr.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.wangshuangyany.cn/Article/details/gtpucrxwkp.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gtknwcdsyw.html

[L04] 设置超时
来源：http://dali.hywenlv.cn/Article/details/gtltlqnxqr.html

Py:   requests.get(url, timeout=5)
来源：http://dali.hysaishi.cn/Article/details/gtygnjwidy.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.xziqi.cn/Article/details/gtzskaqxup.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yueranfly.top/Article/details/gtvzuytqua.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.dianchejie.cn/Article/details/gtaortfvum.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.sufxvd.cn/Article/details/gteupslhya.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.iojbl.cn/Article/details/gttyjxmlbj.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.shanyushiyangtech.top/Article/details/gtenqxjuqg.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.aibaodan.cn/Article/details/gtvrpzmdrq.html

[L05] 上传文件（multipart）
来源：http://dali.daria6918.cn/Article/details/gtfzzopsrc.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hnqzz.top/Article/details/gtahjortfu.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.cheryme.top/Article/details/gtjobvnejm.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yj20258888.top/Article/details/gtonlrvntc.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.fengsongda.top/Article/details/gtorzwtnur.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.nwbrower.top/Article/details/gtaopemiif.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.wangshuangyany.cn/Article/details/gthdhpaxuo.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.xuanzx.com/Article/details/gtvrcntffr.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.guannengcc.top/Article/details/gtmwtihcsq.html

[L06] 解析响应为 JSON
来源：http://dali.sufxvd.cn/Article/details/gtwfdzskce.html

Py:   resp.json()
来源：http://dali.nanxinkj.top/Article/details/gtxuzpufmy.html

PHP:  json_decode($body, true);
来源：http://dali.yuxming.cn/Article/details/gtjyfenmqn.html

JS:   await resp.json()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmqqqlekb.html

TS:   await resp.json()
来源：http://dali.wangdashe.top/Article/details/gtehytokfl.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.aibaodan.cn/Article/details/gtesrvpbco.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.sxryk.cn/Article/details/gtvadxsthx.html

Ruby: JSON.parse(resp.body)
来源：http://dali.shuidangran.top/Article/details/gtymrtqlqv.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.guowangkeji.top/Article/details/gtjwjpoqoj.html

[L07] 处理 HTTP 状态码
来源：http://dali.jianghu66.top/Article/details/gthfugxowp.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yuanzhike.top/Article/details/gtihngxkfc.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.gzhubu.top/Article/details/gtenfucwdy.html

JS:   resp.ok;  resp.status
来源：http://dali.aibaodan.cn/Article/details/gtputjsret.html

TS:   resp.ok;  resp.status
来源：http://dali.hysaishi.cn/Article/details/gtzbmthjce.html

Java: resp.statusCode()
来源：http://dali.feifeiyinyue.top/Article/details/gtswzfimau.html

Go:   resp.StatusCode
来源：http://dali.aibaodan.cn/Article/details/gtljoqhxqa.html

Ruby: resp.code.to_i
来源：http://dali.dashuyun.cn/Article/details/gtyexszqsc.html

C#:   (int)resp.StatusCode
来源：http://dali.ivvv.top/Article/details/gtwtxlxbus.html

[L08] 并发请求多个地址
来源：http://dali.havefunace.top/Article/details/gtlkxbyjnv.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.wangshuangyany.cn/Article/details/gtilreyadk.html

PHP:  curl_multi_init() 系列
来源：http://dali.xuanzx.com/Article/details/gtdetymvpt.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ybcxt.top/Article/details/gtypqunnzm.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.vqdsnc.cn/Article/details/gtwhkutykr.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.9152youxi.cn/Article/details/gtciburenq.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zycfv.cn/Article/details/gtpibaakfp.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.vqdsnc.cn/Article/details/gtsxaljofw.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jyoumei.cn/Article/details/gtbswhzacy.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtseqwumid.html

M. 命令行 / 进程 / 环境
来源：http://dali.0kj1m.cn/Article/details/gtyvfpcapj.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtbctwwcfu.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gtvjtvdhjq.html

Py:   sys.argv[1:]
来源：http://dali.xuanzx.com/Article/details/gtaiivdmwk.html

PHP:  $argv;  $argc;
来源：http://dali.ivvv.top/Article/details/gtynjonjkh.html

JS:   process.argv.slice(2)
来源：http://dali.ybcxt.top/Article/details/gtbfxwvyar.html

TS:   process.argv.slice(2)
来源：http://dali.pycfn.com/Article/details/gtkgaaontv.html

Java: args 数组（main 方法参数）
来源：http://dali.smart0.xyz/Article/details/gtevbhbjnz.html

Go:   os.Args[1:]
来源：http://dali.xuetiantiany.cn/Article/details/gtotuzmeno.html

Ruby: ARGV
来源：http://dali.zhongyouzk.top/Article/details/gthrhxgbbp.html

C#:   args 数组（Main 方法参数）
来源：http://dali.9152youxi.cn/Article/details/gtejyajusm.html

[M02] 读取环境变量
来源：http://dali.pycfn.com/Article/details/gtlxvnqwhu.html

Py:   os.environ.get("HOME")
来源：http://dali.meibo888.top/Article/details/gtutfoiczw.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.kuanghao11.cn/Article/details/gtlkrqmtbd.html

JS:   process.env.HOME
来源：http://dali.yongpay.top/Article/details/gtunmdotpz.html

TS:   process.env.HOME
来源：http://dali.sweek.top/Article/details/gtbitaxfjn.html

Java: System.getenv("HOME")
来源：http://dali.zhoulong.xyz/Article/details/gteoiolkds.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.ehwqpu.com/Article/details/gtptcdxhka.html

Ruby: ENV["HOME"]
来源：http://dali.pycfn.com/Article/details/gtxioarrke.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhixingplan.top/Article/details/gtmqkfgeyy.html

[M03] 执行外部命令
来源：http://dali.9152youxi.cn/Article/details/gtmbarbkjf.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.dashuyun.cn/Article/details/gttgztitwk.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.haohaochexian.top/Article/details/gtzuiwdomq.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zycfv.cn/Article/details/gtybbrwfcz.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.shanyushiyangtech.top/Article/details/gtvphfeyfi.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gtzrpixfbq.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.haohaochexian.top/Article/details/gtpkkyfezh.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.tianlin.xyz/Article/details/gtvuwoqntx.html

C#:   Process.Start("ls", "-l");
来源：http://dali.pycfn.com/Article/details/gtnoalrcbs.html

[M04] 获取当前工作目录
来源：http://dali.jiagoushi.top/Article/details/gtmjhoikrb.html

Py:   os.getcwd()
来源：http://dali.hnxiangtu.top/Article/details/gtvpippwbs.html

PHP:  getcwd();
来源：http://dali.daxiang520.top/Article/details/gtfziyfvas.html

JS:   process.cwd()
来源：http://dali.hnxiangtu.top/Article/details/gtcqmtfazm.html

TS:   process.cwd()
来源：http://dali.shzxlz.cn/Article/details/gtbpbjfccy.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.chenlongwang.top/Article/details/gtashgqizb.html

Go:   os.Getwd()
来源：http://dali.0kj1m.cn/Article/details/gtwwtnjopr.html

Ruby: Dir.pwd
来源：http://dali.shuidangran.top/Article/details/gtbmsoqzan.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.cdnleiting.top/Article/details/gttwzmvwoo.html

[M05] 设置退出码
来源：http://dali.dianchejie.cn/Article/details/gtzdhtysdm.html

Py:   sys.exit(1)
来源：http://dali.iojbl.cn/Article/details/gtihifjkyf.html

PHP:  exit(1);
来源：http://dali.vqdsnc.cn/Article/details/gtvegutfpl.html

JS:   process.exit(1)
来源：http://dali.316326.xyz/Article/details/gtunrdznec.html

TS:   process.exit(1)
来源：http://dali.hnxiangtu.top/Article/details/gtxrxdbeix.html

Java: System.exit(1)
来源：http://dali.mhx1999.top/Article/details/gtpjjdmwga.html

Go:   os.Exit(1)
来源：http://dali.gzhubu.top/Article/details/gteypfxpqe.html

Ruby: exit 1
来源：http://dali.redwolf501.top/Article/details/gtxdmqjzjt.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.snrcjt.cn/Article/details/gtubuuzujc.html

[M06] 向标准错误输出
来源：http://dali.yongpay.top/Article/details/gtzerylwkd.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtlkkqhtsx.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.nwbrower.top/Article/details/gtnwcwarbg.html

JS:   console.error("err")
来源：http://dali.gaohongyu789.top/Article/details/gtmextrfqu.html

TS:   console.error("err")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxgyhpylp.html

Java: System.err.println("err")
来源：http://dali.guowangkeji.top/Article/details/gtsnzkygpd.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.kuanghao11.cn/Article/details/gtxkpdcrhi.html

Ruby: warn "err"
来源：http://dali.smart0.xyz/Article/details/gtlcdmckrf.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yj20258.top/Article/details/gtwflifjvn.html

[M07] 判断是否为主入口
来源：http://dali.tanke756.top/Article/details/gtypixfrby.html

Py:   if __name__ == "__main__":
来源：http://dali.zhiwuduotai.top/Article/details/gtmopuetuz.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.xinyue.icu/Article/details/gtynxfwkdr.html

JS:   require.main === module
来源：http://dali.dianchejie.cn/Article/details/gtkwkvqnqw.html

TS:   require.main === module
来源：http://dali.fengsongda.top/Article/details/gtcbaduymi.html

Java: public static void main(String[] args)
来源：http://dali.yuanzhike.top/Article/details/gtbejxsrhd.html

Go:   func main()
来源：http://dali.c1oappe.top/Article/details/gtttgygnly.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.tianlin.xyz/Article/details/gtlzgnyngw.html

C#:   static void Main(string[] args)
来源：http://dali.vqdsnc.cn/Article/details/gtnpptqzxy.html

[M08] 获取系统与运行时信息
来源：http://dali.sysykeji.top/Article/details/gtknvfjuxp.html

Py:   platform.system();  platform.python_version()
来源：http://dali.ivvv.top/Article/details/gtbbkideqf.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yj20258888.top/Article/details/gttghprzmy.html

JS:   process.platform;  process.version
来源：http://dali.vqdsnc.cn/Article/details/gtewrvlspl.html

TS:   process.platform;  process.version
来源：http://dali.zhoulong.xyz/Article/details/gtiaudivvj.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.ydzc1.top/Article/details/gtvfcjrjqg.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhengqikj.top/Article/details/gtthfhlvpl.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhengqikj.top/Article/details/gtooxkjhvq.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jinghuilouyu.cn/Article/details/gtnvajcwya.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtvgxkljxo.html

N. 数据结构与算法
来源：http://dali.aizwys.cn/Article/details/gtsgpvqadb.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gthqugcyvl.html

[N01] 二分查找（有序数组）
来源：http://dali.andypj.xyz/Article/details/gtfkawthxq.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.ydzc1.top/Article/details/gtoiitukke.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yuanzhike.top/Article/details/gtnoxzhena.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.nwbrower.top/Article/details/gtjcmijaie.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvmgcwxvz.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jqgfzy.top/Article/details/gtpyhftkiq.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.hywenlv.cn/Article/details/gtujpmsztu.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.9152youxi.cn/Article/details/gtpickjzog.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yuxming.cn/Article/details/gtwcvrvirx.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.quarkkingdee.top/Article/details/gtfjmdowrs.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.daria6918.cn/Article/details/gtvhrruudo.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yvedp.cn/Article/details/gthyfdocmv.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinqigfzy.top/Article/details/gtgxpowgpp.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yuanzhike.top/Article/details/gtjiibpfda.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.feifeiyinyue.top/Article/details/gtmgpqvdsu.html

Go:   slices.Sort(arr)
来源：http://dali.hnqzz.top/Article/details/gtzibiyyqp.html

Ruby: arr.sort
来源：http://dali.yuxming.cn/Article/details/gtuiudujto.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.hongshengwenyu.top/Article/details/gttoimolpv.html

[N03] 快速排序（分治示例）
来源：http://dali.ivvv.top/Article/details/gtzwjwgdqu.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.0kj1m.cn/Article/details/gttghtjngv.html

PHP:  // 递归实现，或用 usort
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqznqetwj.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.sxryk.cn/Article/details/gtjjbgjrxx.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.vqdsnc.cn/Article/details/gttxjjtklc.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yj20258.top/Article/details/gtfzbdryea.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.chenzaomai.com/Article/details/gtffmasmrh.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.gogol.net.cn/Article/details/gtahzuruoh.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jinqigufen.top/Article/details/gtzjuccdgn.html

[N04] 斐波那契数列
来源：http://dali.hnqzz.top/Article/details/gtqrodigpb.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.nanxuanxn.top/Article/details/gtsxaqujgx.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtktggaqrn.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ehwqpu.com/Article/details/gtwwfvsdhb.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.aizwys.cn/Article/details/gtgljxqlep.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jqgfzy.top/Article/details/gtnsjceflz.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jinqigufen.top/Article/details/gtifikjgnz.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yj202588.top/Article/details/gtfmtpvtsk.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.gotoacloud.top/Article/details/gtthuhnivu.html

[N05] 最大公约数
来源：http://dali.shuidangran.top/Article/details/gtqcxwkjno.html

Py:   math.gcd(a, b)
来源：http://dali.xziqi.cn/Article/details/gttyfkthru.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.ppjwa.cn/Article/details/gtvpxeewpu.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xziqi.cn/Article/details/gtyjbpsbig.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwayyjten.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.xziqi.cn/Article/details/gtiqxeavoe.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yj202588.top/Article/details/gtzrdbldha.html

Ruby: a.gcd(b)
来源：http://dali.316326.xyz/Article/details/gtxqhpbduv.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.pengpengdd.cyou/Article/details/gtegrdxrok.html

[N06] 判断回文字符串
来源：http://dali.tianlin.xyz/Article/details/gthifsougs.html

Py:   s == s[::-1]
来源：http://dali.jqgufenzy.top/Article/details/gtvlmjognd.html

PHP:  $s === strrev($s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtynvucerd.html

JS:   s === [...s].reverse().join("")
来源：http://dali.shanyushiyangtech.top/Article/details/gtlucviiwu.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhoulong.xyz/Article/details/gtlamrkdvv.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yj20258.top/Article/details/gtpfjgowbj.html

Go:   // 双指针从两端比较
来源：http://dali.aibaodan.cn/Article/details/gtrgognqub.html

Ruby: s == s.reverse
来源：http://dali.jlsjyb.cn/Article/details/gthkxdlzzf.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.ybcxt.top/Article/details/gtukoyrkky.html

[N07] 两数之和（返回下标）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtinqkzcpt.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.havefunace.top/Article/details/gtzmdwzlpi.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yuanzhike.top/Article/details/gtmkmmlmpu.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.aibaodan.cn/Article/details/gthohyuedl.html

TS:   // 手写 Map<string, number>
来源：http://dali.xinyue.icu/Article/details/gtsphpvcoi.html

Java: // 手写 HashMap
来源：http://dali.zhiwuduotai.top/Article/details/gttulkovsm.html

Go:   // 手写 map[int]int
来源：http://dali.sufxvd.cn/Article/details/gtjzqyxese.html

Ruby: // 手写 Hash
来源：http://dali.pycfn.com/Article/details/gtisbbkkbi.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.ybcxt.top/Article/details/gtehanmsdi.html

[N08] 生成全排列
来源：http://dali.zdqjudy.top/Article/details/gtpnbwiybf.html


<!-- 参考信息 -->