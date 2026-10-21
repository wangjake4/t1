代发 wailian999

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.redwolf501.top/Article/details/gtqqlxqgnr.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shzxlz.cn/Article/details/gtwaliioux.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.guannengcc.top/Article/details/gtcmtyuvln.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.quarkkingdee.top/Article/details/gthdhmpuju.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.fzhhl.top/Article/details/gtpwktqdhm.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jyoumei.cn/Article/details/gtcixwicsr.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.aibaodan.cn/Article/details/gtivsuwfad.html

[J10] 取今天 / 本月第一天
来源：http://dali.tianlin.xyz/Article/details/gtnzcfnosq.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.ydzc1.top/Article/details/gtwvkvwybv.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jiagoushi.top/Article/details/gtwhbtkbfh.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhongyouzk.top/Article/details/gtrhglxdwk.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.sweek.top/Article/details/gtnkfimndn.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zdqjudy.top/Article/details/gtyzuknyod.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.cqqwz.cn/Article/details/gtkzpqslka.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.shuidangran.top/Article/details/gtyrlgnmap.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.xuanzx.com/Article/details/gtnpaujfhi.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtvglwmsjy.html

K. JSON 与序列化
来源：http://dali.kuanghao11.cn/Article/details/gtowvihhnv.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gthrhbffhb.html

[K01] 对象转 JSON 字符串
来源：http://dali.yj20258888.top/Article/details/gtxdxemgcv.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhoulong.xyz/Article/details/gtiedysgbq.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.aibaodan.cn/Article/details/gtthwboasb.html

JS:   JSON.stringify(obj)
来源：http://dali.daxiang520.top/Article/details/gtwueecfwu.html

TS:   JSON.stringify(obj)
来源：http://dali.andypj.xyz/Article/details/gteosrvzau.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.guowangkeji.top/Article/details/gtjxuyjyrn.html

Go:   json.Marshal(obj)
来源：http://dali.bjfxy.top/Article/details/gthwscldru.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.bjfxy.top/Article/details/gtckrgiwyp.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.hammf.cn/Article/details/gtybiafyjr.html

[K02] JSON 字符串转对象
来源：http://dali.0kj1m.cn/Article/details/gtrylxbocu.html

Py:   json.loads(s)
来源：http://dali.snrcjt.cn/Article/details/gtllbnynfp.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yanxiufei.cn/Article/details/gttuolcuhb.html

JS:   JSON.parse(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtoiftvdpp.html

TS:   JSON.parse(s)
来源：http://dali.daria6918.cn/Article/details/gttrlirrhh.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.sufxvd.cn/Article/details/gtnblborug.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.shanyushiyangtech.top/Article/details/gtfyckncwr.html

Ruby: JSON.parse(s)
来源：http://dali.hnqzz.top/Article/details/gtuokzoemh.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.gaohongyu789.top/Article/details/gtgktoyrju.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtadvraitg.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.guowangkeji.top/Article/details/gtsjisdlvx.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.daxiang520.top/Article/details/gtnvykdcdc.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.xinyue.icu/Article/details/gtjhllyqbj.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jinqigufen.top/Article/details/gtznzxfkko.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.hnqzz.top/Article/details/gtubmnqjvd.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.vqdsnc.cn/Article/details/gtpbvgmdix.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.guowangkeji.top/Article/details/gtyekppwdb.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jiagoushi.top/Article/details/gtlpzluiti.html

[K04] 读取 JSON 文件
来源：http://dali.yj20258.top/Article/details/gtyamnzaqg.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.xinyue.icu/Article/details/gtbyjakzjx.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zycfv.cn/Article/details/gtpzozqsss.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.haohaochexian.top/Article/details/gtepnyajeu.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cdnleiting.top/Article/details/gtgaxxvcrl.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.tanke756.top/Article/details/gtibehvzqz.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.sufxvd.cn/Article/details/gtttdwkiqo.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.ybcxt.top/Article/details/gtceichexj.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.vqdsnc.cn/Article/details/gteseyptbt.html

[K05] 深拷贝对象
来源：http://dali.nanxuanxn.top/Article/details/gtxnbtyzur.html

Py:   copy.deepcopy(obj)
来源：http://dali.yanxiufei.cn/Article/details/gtwsgjlhva.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jinqigfzy.top/Article/details/gtkjleqnan.html

JS:   structuredClone(obj)
来源：http://dali.guowangkeji.top/Article/details/gtwnfvgnkc.html

TS:   structuredClone(obj)
来源：http://dali.vqdsnc.cn/Article/details/gtymrmnsfq.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yonumen.top/Article/details/gtngbrpbaf.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.smart0.xyz/Article/details/gtockyxddg.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.iojbl.cn/Article/details/gtvbhxmltf.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.ivvv.top/Article/details/gtngoaeojz.html

[K06] 解析 URL 查询串
来源：http://dali.xinyue.icu/Article/details/gtjpjxoags.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yj20258.top/Article/details/gtnsqsaupd.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.316326.xyz/Article/details/gtonmepkom.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbrhvvymv.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.wangshuangyany.cn/Article/details/gtjkjsrevx.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.xuetiantiany.cn/Article/details/gtkapknyoa.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zdqjudy.top/Article/details/gtvszqphjs.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtayorevyi.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.redwolf501.top/Article/details/gtvkmmrtpi.html

[K07] 进制转换
来源：http://dali.wangdashe.top/Article/details/gtjajmsygj.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yongpay.top/Article/details/gtornywgqz.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.bjfxy.top/Article/details/gtdgbhmbxa.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.xziqi.cn/Article/details/gtldrpmmza.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.hfpthk.cn/Article/details/gtkajycdhk.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.mhx1999.top/Article/details/gtudbfylgp.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jianghu66.top/Article/details/gtfrmjcudu.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.cdnleiting.top/Article/details/gthsbfqrvm.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yj20258.top/Article/details/gtnobtadei.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.sweek.top/Article/details/gtpdznbmnn.html

Py:   pickle.dumps(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtnjpnumvu.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.nwbrower.top/Article/details/gtstdestxq.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.andypj.xyz/Article/details/gtpnlsoljh.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.tian-w.cn/Article/details/gtjvljvgrr.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhixingplan.top/Article/details/gtdprsjtob.html

Go:   encoding/gob
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxiteqldf.html

Ruby: Marshal.dump(obj)
来源：http://dali.shzxlz.cn/Article/details/gtfxrjgjyz.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.hnxiangtu.top/Article/details/gtmjyyhogs.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtnlsgtfum.html

L. 网络请求
来源：http://dali.tian-w.cn/Article/details/gtbdnvpgue.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtocolochu.html

[L01] 发送 GET 请求
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiuwnejnb.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.gaohongyu789.top/Article/details/gtoopauwvu.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jianghu66.top/Article/details/gtrrtuomks.html

JS:   await fetch(url)
来源：http://dali.pycfn.com/Article/details/gtzstnasob.html

TS:   await fetch(url)
来源：http://dali.nanxuanxn.top/Article/details/gtzqmfsvry.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.shuidangran.top/Article/details/gtafajfkkf.html

Go:   resp, err := http.Get(url)
来源：http://dali.wangshuangyany.cn/Article/details/gtdvprqjbt.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.wangdashe.top/Article/details/gtwtitdgbr.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.hammf.cn/Article/details/gthvouxdqo.html

[L02] 发送 POST JSON
来源：http://dali.redwolf501.top/Article/details/gtmutyqejr.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jiagoushi.top/Article/details/gtylnqkifd.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfwvghezn.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.tian-w.cn/Article/details/gteocwmnwq.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinqigfzy.top/Article/details/gtusvsceas.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.cqqwz.cn/Article/details/gtskzpyzgf.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.cashguo.top/Article/details/gtyapggnfp.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.shanyushiyangkeji.top/Article/details/gttetelqmf.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhoulong.xyz/Article/details/gtiwlmosvq.html

[L03] 设置自定义请求头
来源：http://dali.zhengqikj.top/Article/details/gtpcbkipce.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yangfankeji.com/Article/details/gtxenclolq.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.pengpengdd.cyou/Article/details/gtmyklfdzy.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ybcxt.top/Article/details/gtbiyklvhy.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.andypj.xyz/Article/details/gtgobvcagt.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.cqqwz.cn/Article/details/gtetqfdvdh.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.tianlin.xyz/Article/details/gtqxvsbrmc.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.nanxinkj.top/Article/details/gtjcyyqjfa.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yonumen.top/Article/details/gtjmfiajod.html

[L04] 设置超时
来源：http://dali.hongshengwenyu.top/Article/details/gtphfcighc.html

Py:   requests.get(url, timeout=5)
来源：http://dali.guowangkeji.top/Article/details/gtsiayxnir.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.aibaodan.cn/Article/details/gtaohermnh.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cucudq.cn/Article/details/gtfqirpwlb.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hfpthk.cn/Article/details/gtotzfjgnh.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.haohaochexian.top/Article/details/gtqfjqntoz.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrjqijoiq.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.sweek.top/Article/details/gtmpovljof.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zdqjudy.top/Article/details/gtahxchbxp.html

[L05] 上传文件（multipart）
来源：http://dali.hysaishi.cn/Article/details/gtmkkkinjc.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhengqikj.top/Article/details/gtgppbrney.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yj20258888.top/Article/details/gthlroeejn.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.wangdashe.top/Article/details/gtibrmtagm.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.nanxinkj.top/Article/details/gtxgkpmgwo.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.cucudq.cn/Article/details/gtybhiopoi.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.ybcxt.top/Article/details/gtnqrsgaly.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.guowangkeji.top/Article/details/gtqaxlszam.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.ydzc1.top/Article/details/gtjubieswr.html

[L06] 解析响应为 JSON
来源：http://dali.yvedp.cn/Article/details/gthlhynndo.html

Py:   resp.json()
来源：http://dali.nanxinkj.top/Article/details/gtfqabjvur.html

PHP:  json_decode($body, true);
来源：http://dali.jlsjyb.cn/Article/details/gtmbwbjlsp.html

JS:   await resp.json()
来源：http://dali.yuxming.cn/Article/details/gtljahpqbz.html

TS:   await resp.json()
来源：http://dali.pengpengdd.cyou/Article/details/gtfoofrnnd.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jiagoushi.top/Article/details/gticwqfkiw.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuquymtae.html

Ruby: JSON.parse(resp.body)
来源：http://dali.iojbl.cn/Article/details/gtvsdpcnwp.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.chenjidiqi.icu/Article/details/gtyyssliyg.html

[L07] 处理 HTTP 状态码
来源：http://dali.gzhubu.top/Article/details/gtfwbcvbfu.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.0kj1m.cn/Article/details/gtxyrvbbux.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgjfrfkmm.html

JS:   resp.ok;  resp.status
来源：http://dali.hnxiangtu.top/Article/details/gtyxkncgko.html

TS:   resp.ok;  resp.status
来源：http://dali.chenjidiqi.icu/Article/details/gtfphlejpt.html

Java: resp.statusCode()
来源：http://dali.cashguo.top/Article/details/gtueigwsry.html

Go:   resp.StatusCode
来源：http://dali.wangshuangyany.cn/Article/details/gtyocghkgq.html

Ruby: resp.code.to_i
来源：http://dali.xylfe.cn/Article/details/gtcpvtbmnr.html

C#:   (int)resp.StatusCode
来源：http://dali.xuetiantiany.cn/Article/details/gttzokrapf.html

[L08] 并发请求多个地址
来源：http://dali.sufxvd.cn/Article/details/gtydkgsvae.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.bjfxy.top/Article/details/gtqoeaysvb.html

PHP:  curl_multi_init() 系列
来源：http://dali.guannengcc.top/Article/details/gtmaapkcmw.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.smart0.xyz/Article/details/gtcpisjvko.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.chenlongwang.top/Article/details/gtfguxejlr.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.pycfn.com/Article/details/gtjritsvvs.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.redwolf501.top/Article/details/gtoyhusxms.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.nanxuanxn.top/Article/details/gtqbyhxawb.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.daxiang520.top/Article/details/gthueamqgp.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtvxurugpj.html

M. 命令行 / 进程 / 环境
来源：http://dali.jinyuanbaomall.cn/Article/details/gtexibwhgt.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtwdiphjoh.html

[M01] 读取命令行参数
来源：http://dali.fzhhl.top/Article/details/gtjdehwxgy.html

Py:   sys.argv[1:]
来源：http://dali.hnqzz.top/Article/details/gtyqejpiua.html

PHP:  $argv;  $argc;
来源：http://dali.nanxuanxn.top/Article/details/gttzuddgip.html

JS:   process.argv.slice(2)
来源：http://dali.daxiang520.top/Article/details/gtcfvbnotm.html

TS:   process.argv.slice(2)
来源：http://dali.xziqi.cn/Article/details/gtnfvcjobb.html

Java: args 数组（main 方法参数）
来源：http://dali.shzxlz.cn/Article/details/gtoixbmlmr.html

Go:   os.Args[1:]
来源：http://dali.snrcjt.cn/Article/details/gtsxwoojrr.html

Ruby: ARGV
来源：http://dali.9152youxi.cn/Article/details/gtfivyabbr.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yangfankeji.com/Article/details/gttokrtrda.html

[M02] 读取环境变量
来源：http://dali.andypj.xyz/Article/details/gtsapxpigu.html

Py:   os.environ.get("HOME")
来源：http://dali.nanxuanxn.top/Article/details/gtfumqqboh.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtltaycmok.html

JS:   process.env.HOME
来源：http://dali.meibo888.top/Article/details/gtvhmobiic.html

TS:   process.env.HOME
来源：http://dali.hywenlv.cn/Article/details/gtckezpcjv.html

Java: System.getenv("HOME")
来源：http://dali.bjfxy.top/Article/details/gtjxhwnksk.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jlsjyb.cn/Article/details/gtasemxvzh.html

Ruby: ENV["HOME"]
来源：http://dali.sweek.top/Article/details/gtzqmsgyoc.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.nwbrower.top/Article/details/gtjucjwdpy.html

[M03] 执行外部命令
来源：http://dali.hywenlv.cn/Article/details/gtuvzxvtvc.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jqgufenzy.top/Article/details/gtfdqhfgqo.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.fengsongda.top/Article/details/gtmjmpovrb.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.redwolf501.top/Article/details/gtippbqorj.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.smart0.xyz/Article/details/gtwcgsbslh.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.feifeiyinyue.top/Article/details/gtlwembgtw.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.sufxvd.cn/Article/details/gtdwxtnbac.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.shuidangran.top/Article/details/gtyrqxktkm.html

C#:   Process.Start("ls", "-l");
来源：http://dali.ehwqpu.com/Article/details/gtslfigria.html

[M04] 获取当前工作目录
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgjdunqsl.html

Py:   os.getcwd()
来源：http://dali.cheryme.top/Article/details/gtcxmdjusr.html

PHP:  getcwd();
来源：http://dali.redwolf501.top/Article/details/gtgjusolts.html

JS:   process.cwd()
来源：http://dali.jinqigfzy.top/Article/details/gtqjktuzhb.html

TS:   process.cwd()
来源：http://dali.yongpay.top/Article/details/gtlkgzjgjq.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.9152youxi.cn/Article/details/gtjcvzrlmn.html

Go:   os.Getwd()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdgxawjev.html

Ruby: Dir.pwd
来源：http://dali.hongshengwenyu.top/Article/details/gtgfztuzbm.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.fzhhl.top/Article/details/gtujonpxbd.html

[M05] 设置退出码
来源：http://dali.jqgfzy.top/Article/details/gtfntlnygr.html

Py:   sys.exit(1)
来源：http://dali.jinqigfzy.top/Article/details/gtjyfvzilj.html

PHP:  exit(1);
来源：http://dali.jianghu66.top/Article/details/gtdvpfbmsh.html

JS:   process.exit(1)
来源：http://dali.xuetiantiany.cn/Article/details/gttystnpeh.html

TS:   process.exit(1)
来源：http://dali.dashuyun.cn/Article/details/gtomyawzza.html

Java: System.exit(1)
来源：http://dali.bjfxy.top/Article/details/gtvdcamnjw.html

Go:   os.Exit(1)
来源：http://dali.zhixingplan.top/Article/details/gtdbttuezq.html

Ruby: exit 1
来源：http://dali.birdmap.top/Article/details/gthdpixkrp.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yonumen.top/Article/details/gtvruutbut.html

[M06] 向标准错误输出
来源：http://dali.jqgufenzy.top/Article/details/gtpixxibzq.html

Py:   print("err", file=sys.stderr)
来源：http://dali.xuanzx.com/Article/details/gtyfwprgqd.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.cheryme.top/Article/details/gtviivawpj.html

JS:   console.error("err")
来源：http://dali.zhengqikj.top/Article/details/gtvcdcvouc.html

TS:   console.error("err")
来源：http://dali.jinqigfzy.top/Article/details/gtmojbawqi.html

Java: System.err.println("err")
来源：http://dali.zhixingplan.top/Article/details/gttlemhggk.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.9152youxi.cn/Article/details/gtnhozrvwx.html

Ruby: warn "err"
来源：http://dali.daria6918.cn/Article/details/gtfwazboda.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.cqqwz.cn/Article/details/gttevgjttt.html

[M07] 判断是否为主入口
来源：http://dali.hongshengwenyu.top/Article/details/gttormmxlq.html

Py:   if __name__ == "__main__":
来源：http://dali.yj20258.top/Article/details/gtvwldognc.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.xuanzx.com/Article/details/gtonpzwgqa.html

JS:   require.main === module
来源：http://dali.birdmap.top/Article/details/gtuzwdoofs.html

TS:   require.main === module
来源：http://dali.daxiang520.top/Article/details/gtpuwhxpct.html

Java: public static void main(String[] args)
来源：http://dali.dashuyun.cn/Article/details/gtbajynetf.html

Go:   func main()
来源：http://dali.wangshuangyany.cn/Article/details/gtnswtqwtt.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.guannengcc.top/Article/details/gtfwwjnbyf.html

C#:   static void Main(string[] args)
来源：http://dali.ydzc1.top/Article/details/gtqhiiqgle.html

[M08] 获取系统与运行时信息
来源：http://dali.gotoacloud.top/Article/details/gtibwaaiel.html

Py:   platform.system();  platform.python_version()
来源：http://dali.tanke756.top/Article/details/gtzrpferhb.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.chenjidiqi.icu/Article/details/gtfvqrlaxn.html

JS:   process.platform;  process.version
来源：http://dali.xinyue.icu/Article/details/gtubxctccc.html

TS:   process.platform;  process.version
来源：http://dali.gotoacloud.top/Article/details/gtefpiscvs.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.gzhubu.top/Article/details/gtimpkkvfh.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jqgufenzy.top/Article/details/gthbpcgdsi.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.cheryme.top/Article/details/gtaqazkyfn.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.andypj.xyz/Article/details/gtrjljimzk.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtwxezktmi.html

N. 数据结构与算法
来源：http://dali.pengpengdd.cyou/Article/details/gtqgaeqgbd.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtciholaag.html

[N01] 二分查找（有序数组）
来源：http://dali.wangshuangyany.cn/Article/details/gtvtpdmncr.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.316326.xyz/Article/details/gtlluzdlch.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.mhx1999.top/Article/details/gtbixyyupo.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhengqikj.top/Article/details/gtghiyxxzm.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xuetiantiany.cn/Article/details/gtjpmajwxj.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.nanxuanxn.top/Article/details/gtiqfmsnhv.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yvedp.cn/Article/details/gtfhbfbwwf.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jqgfzy.top/Article/details/gthggvqfxk.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.birdmap.top/Article/details/gtebhrhmpt.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gthvjbalir.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sufxvd.cn/Article/details/gtjwhojxwb.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.fengsongda.top/Article/details/gtjsuntdmv.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.chenlongwang.top/Article/details/gtbxbbjmmi.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hongshengwenyu.top/Article/details/gtbewhtkxp.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.fengsongda.top/Article/details/gtjbuxvgfz.html

Go:   slices.Sort(arr)
来源：http://dali.hywenlv.cn/Article/details/gtyzbitywt.html

Ruby: arr.sort
来源：http://dali.birdmap.top/Article/details/gtdfqiglvl.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.gzhubu.top/Article/details/gtavmmwzzj.html

[N03] 快速排序（分治示例）
来源：http://dali.gaohongyu789.top/Article/details/gtydzkzchq.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.nanxuanxn.top/Article/details/gtonuelsyz.html

PHP:  // 递归实现，或用 usort
来源：http://dali.xylfe.cn/Article/details/gtjncndzhx.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cashguo.top/Article/details/gtogeuvhqx.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yonumen.top/Article/details/gtrbrjclic.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yuxming.cn/Article/details/gttuagpdrk.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.xuanzx.com/Article/details/gtgcsoyoon.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yuxming.cn/Article/details/gtjkukisrn.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yangfankeji.com/Article/details/gtdnoelapm.html

[N04] 斐波那契数列
来源：http://dali.aizwys.cn/Article/details/gtxrcmvvkx.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.mhx1999.top/Article/details/gtljczhdlr.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zycfv.cn/Article/details/gtlaaplvri.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jyoumei.cn/Article/details/gtmgvgtzmq.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xuanzx.com/Article/details/gtzgoxzoel.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.shuidangran.top/Article/details/gtjrjruget.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.xziqi.cn/Article/details/gtnwusuhoe.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.0kj1m.cn/Article/details/gtvqtyqoaa.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.tanke756.top/Article/details/gtsmrrqygv.html

[N05] 最大公约数
来源：http://dali.vqdsnc.cn/Article/details/gtrepzzrqg.html

Py:   math.gcd(a, b)
来源：http://dali.gaohongyu789.top/Article/details/gtjqinobkk.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.0kj1m.cn/Article/details/gtnywujtdg.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hongshengwenyu.top/Article/details/gtxxdmcbga.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.fengsongda.top/Article/details/gthqyfchwx.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.sweek.top/Article/details/gttesmgtlr.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gtbnozppgq.html

Ruby: a.gcd(b)
来源：http://dali.fzhhl.top/Article/details/gtcpahzrmf.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jiagoushi.top/Article/details/gtjskidsvz.html

[N06] 判断回文字符串
来源：http://dali.xinyue.icu/Article/details/gtpdbxiqmq.html

Py:   s == s[::-1]
来源：http://dali.zhixingplan.top/Article/details/gtabxwdanh.html

PHP:  $s === strrev($s);
来源：http://dali.yj20258888.top/Article/details/gtxhaeqlvk.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yongpay.top/Article/details/gtrxioznwz.html

TS:   s === [...s].reverse().join("")
来源：http://dali.xuetiantiany.cn/Article/details/gtrdcaeaqq.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.sweek.top/Article/details/gtxgkbsdcl.html

Go:   // 双指针从两端比较
来源：http://dali.hywenlv.cn/Article/details/gtjeiszsba.html

Ruby: s == s.reverse
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbohaixpa.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhoulong.xyz/Article/details/gtaewlayhm.html

[N07] 两数之和（返回下标）
来源：http://dali.yuanzhike.top/Article/details/gtmykvdjir.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.xylfe.cn/Article/details/gtdqbxmums.html


<!-- 参考信息 -->