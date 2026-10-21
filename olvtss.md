代发 wailian999

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yuxming.cn/Article/details/gtzwoicxmt.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.feifeiyinyue.top/Article/details/gtskoijfxs.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cheryme.top/Article/details/gtqbxmphne.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.xylfe.cn/Article/details/gtlvozesyh.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.redwolf501.top/Article/details/gtzuinfokk.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jinqigfzy.top/Article/details/gtidpqkqrn.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.0kj1m.cn/Article/details/gtarqnfuei.html

[J10] 取今天 / 本月第一天
来源：http://dali.daria6918.cn/Article/details/gtjcamofoy.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.c1oappe.top/Article/details/gtnkyhnqnk.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jianghu66.top/Article/details/gtumtbshxt.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.ydzc1.top/Article/details/gtadnhxqjh.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.pengpengdd.cyou/Article/details/gtjwbbfxan.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtyiffrtld.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.iojbl.cn/Article/details/gtctyapmyk.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yj20258888.top/Article/details/gtjllpnayq.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.aizwys.cn/Article/details/gtubbykfmv.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtacgbxggl.html

K. JSON 与序列化
来源：http://dali.yuanzhike.top/Article/details/gtbskhvpdz.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtvbrggacj.html

[K01] 对象转 JSON 字符串
来源：http://dali.snrcjt.cn/Article/details/gtyoxgnhnm.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.tanke756.top/Article/details/gtsszduvvy.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.havefunace.top/Article/details/gtpkjiuayn.html

JS:   JSON.stringify(obj)
来源：http://dali.cdnleiting.top/Article/details/gtnwnentsd.html

TS:   JSON.stringify(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gtqhdswbsj.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.gzhubu.top/Article/details/gtxlhsvkcv.html

Go:   json.Marshal(obj)
来源：http://dali.shzxlz.cn/Article/details/gttoibvpge.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jinqigufen.top/Article/details/gtdlotqlbn.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.xuanzx.com/Article/details/gticuimwyb.html

[K02] JSON 字符串转对象
来源：http://dali.guannengcc.top/Article/details/gtpbstlebt.html

Py:   json.loads(s)
来源：http://dali.nwbrower.top/Article/details/gtxlhkjjjx.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.0kj1m.cn/Article/details/gtzzhbbopw.html

JS:   JSON.parse(s)
来源：http://dali.hysaishi.cn/Article/details/gtzaknhqab.html

TS:   JSON.parse(s)
来源：http://dali.svipenyu.cn/Article/details/gtymwphaqo.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.quarkkingdee.top/Article/details/gtiebaufol.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjnwwanpf.html

Ruby: JSON.parse(s)
来源：http://dali.yj20258.top/Article/details/gttuzvkdqr.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yanxiufei.cn/Article/details/gtqycsovkd.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.hnqzz.top/Article/details/gtjgoxzpgp.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.cucudq.cn/Article/details/gthiztglyy.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhiwuduotai.top/Article/details/gtckzcnlgd.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jinqigfzy.top/Article/details/gtdhiebpcw.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.hnqzz.top/Article/details/gtgpshfqhl.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.guowangkeji.top/Article/details/gtpltgkbqf.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.aibaodan.cn/Article/details/gtyaiolipy.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.hnqzz.top/Article/details/gtnjltxhff.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.hywenlv.cn/Article/details/gtqviqkdhu.html

[K04] 读取 JSON 文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtrgyrusjg.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.ydzc1.top/Article/details/gtuqlmuvjr.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.bjfxy.top/Article/details/gtecvqttiy.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yuanzhike.top/Article/details/gtyfrltxrs.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.smart0.xyz/Article/details/gtfdkpnuii.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jinyuanbaomall.cn/Article/details/gttzvajmur.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhiwuduotai.top/Article/details/gtarmgqxhm.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhiwuduotai.top/Article/details/gtvjlkfdgn.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.nanxinkj.top/Article/details/gtxjphjbmm.html

[K05] 深拷贝对象
来源：http://dali.sysykeji.top/Article/details/gthtdpjtfn.html

Py:   copy.deepcopy(obj)
来源：http://dali.sxryk.cn/Article/details/gtceaiulqx.html

PHP:  unserialize(serialize($obj));
来源：http://dali.birdmap.top/Article/details/gtjxekrdob.html

JS:   structuredClone(obj)
来源：http://dali.xinyue.icu/Article/details/gtppmmdhtf.html

TS:   structuredClone(obj)
来源：http://dali.guannengcc.top/Article/details/gtbtyijxly.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.dianchejie.cn/Article/details/gtxoorinpc.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.andypj.xyz/Article/details/gtawhwxkle.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.tanke756.top/Article/details/gtpzbrczyl.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.iojbl.cn/Article/details/gtutzwyiyz.html

[K06] 解析 URL 查询串
来源：http://dali.zycfv.cn/Article/details/gtmkyyuyky.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.cashguo.top/Article/details/gtrwkxnyxp.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.smart0.xyz/Article/details/gtlejrjqio.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yj20258.top/Article/details/gttdizeger.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yj20258888.top/Article/details/gtxuqtkisx.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.sxryk.cn/Article/details/gtyeorqxfu.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gtjgdwslvj.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.tianlin.xyz/Article/details/gtuekvzzwf.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.fzhhl.top/Article/details/gtqzrxupgx.html

[K07] 进制转换
来源：http://dali.nwbrower.top/Article/details/gtbeevrljk.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.xziqi.cn/Article/details/gthgimygfr.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jqgfzy.top/Article/details/gttpmmpcis.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.cqqwz.cn/Article/details/gteblzyqbv.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.sxryk.cn/Article/details/gtzgovbaga.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jiagoushi.top/Article/details/gtbwxqcsxo.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhongyouzk.top/Article/details/gtdetzhpod.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.xuanzx.com/Article/details/gtsdmdtfyd.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jinghuilouyu.cn/Article/details/gtacpkjzvy.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttpoqzjzp.html

Py:   pickle.dumps(obj)
来源：http://dali.xylfe.cn/Article/details/gtnnblerug.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.aibaodan.cn/Article/details/gthgekgodh.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.aibaodan.cn/Article/details/gtaupsxvko.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yj20258.top/Article/details/gtnwfpslqp.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.gogol.net.cn/Article/details/gtotcavnhe.html

Go:   encoding/gob
来源：http://dali.yuanzhike.top/Article/details/gtcegxqdjd.html

Ruby: Marshal.dump(obj)
来源：http://dali.hywenlv.cn/Article/details/gtiucyrzmv.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.fengsongda.top/Article/details/gtlrgyifgk.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtpeniedmk.html

L. 网络请求
来源：http://dali.ppjwa.cn/Article/details/gtrruzqgbc.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtesmiedni.html

[L01] 发送 GET 请求
来源：http://dali.bjfxy.top/Article/details/gtcyqqbuqz.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.guannengcc.top/Article/details/gtuhgflgxf.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yj202588.top/Article/details/gtkkmudswg.html

JS:   await fetch(url)
来源：http://dali.birdmap.top/Article/details/gtzixmivkn.html

TS:   await fetch(url)
来源：http://dali.redwolf501.top/Article/details/gtyujegibk.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.ybcxt.top/Article/details/gtlcihenbb.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhiwuduotai.top/Article/details/gtsfvycakc.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhijiandao.cn/Article/details/gtnciyvmgl.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.cheryme.top/Article/details/gtnvizxwmv.html

[L02] 发送 POST JSON
来源：http://dali.meibo888.top/Article/details/gttzmhuysn.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.dianchejie.cn/Article/details/gtqyctfnlu.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yonumen.top/Article/details/gteooixghv.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.daria6918.cn/Article/details/gtkbbghnjc.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhengqikj.top/Article/details/gtwhdzhvuo.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.redwolf501.top/Article/details/gtkwrbhsyv.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.dashuyun.cn/Article/details/gtdqbmhson.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.ivvv.top/Article/details/gtqbgzwdmg.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.gaohongyu789.top/Article/details/gtvpkrjqrf.html

[L03] 设置自定义请求头
来源：http://dali.yvedp.cn/Article/details/gtuukqynil.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.hnxiangtu.top/Article/details/gttdeqycwg.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.xylfe.cn/Article/details/gtsuttuqju.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.dashuyun.cn/Article/details/gtztiwzrbp.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.kuanghao11.cn/Article/details/gtybrbfato.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.meibo888.top/Article/details/gtunabyvsk.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.shzxlz.cn/Article/details/gtrkzioxla.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.dashuyun.cn/Article/details/gtkhifhoqu.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jqgufenzy.top/Article/details/gtbvbcqsec.html

[L04] 设置超时
来源：http://dali.zhongyouzk.top/Article/details/gtdvawqgzj.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jinqigfzy.top/Article/details/gtuaycgvxy.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.316326.xyz/Article/details/gtvwsaotld.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cdnleiting.top/Article/details/gtjbrbeiqd.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ivvv.top/Article/details/gtpoikuzxu.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.hnqzz.top/Article/details/gtucjzcxax.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.guannengcc.top/Article/details/gtgeuhnpmw.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.sweek.top/Article/details/gtrzswadiu.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.shuidangran.top/Article/details/gtbcfeqfmo.html

[L05] 上传文件（multipart）
来源：http://dali.zhixingplan.top/Article/details/gttnxlhthi.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.daxiang520.top/Article/details/gtwcvlwkvr.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yueranfly.top/Article/details/gtyfilklpu.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yueranfly.top/Article/details/gtvjoymriq.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.aizwys.cn/Article/details/gtkvfqxrpr.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.cashguo.top/Article/details/gtgsvthpxf.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.mhx1999.top/Article/details/gtyljuvueh.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.kuanghao11.cn/Article/details/gtakpvwvqf.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.pycfn.com/Article/details/gtstfdkaeb.html

[L06] 解析响应为 JSON
来源：http://dali.xuetiantiany.cn/Article/details/gtdededdgf.html

Py:   resp.json()
来源：http://dali.aizwys.cn/Article/details/gtdwoxkcng.html

PHP:  json_decode($body, true);
来源：http://dali.yj20258.top/Article/details/gtuhxlxzlp.html

JS:   await resp.json()
来源：http://dali.jqgfzy.top/Article/details/gtoirkpyjo.html

TS:   await resp.json()
来源：http://dali.hysaishi.cn/Article/details/gtlkheqamp.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gttcxatsks.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yanxiufei.cn/Article/details/gtkceayvvz.html

Ruby: JSON.parse(resp.body)
来源：http://dali.tanke756.top/Article/details/gtddrgzyfh.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zdqjudy.top/Article/details/gtxotaqdkx.html

[L07] 处理 HTTP 状态码
来源：http://dali.smart0.xyz/Article/details/gtiwwcvcch.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.haohaochexian.top/Article/details/gtnpinifbo.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yonumen.top/Article/details/gtnrxzwbps.html

JS:   resp.ok;  resp.status
来源：http://dali.yangfankeji.com/Article/details/gtnuzsgdpf.html

TS:   resp.ok;  resp.status
来源：http://dali.haohaochexian.top/Article/details/gttrshoyze.html

Java: resp.statusCode()
来源：http://dali.jianghu66.top/Article/details/gtdsjrpjpl.html

Go:   resp.StatusCode
来源：http://dali.jinqigufen.top/Article/details/gtoqbhxdob.html

Ruby: resp.code.to_i
来源：http://dali.zdqjudy.top/Article/details/gtluthwair.html

C#:   (int)resp.StatusCode
来源：http://dali.dianchejie.cn/Article/details/gtpzfgttqi.html

[L08] 并发请求多个地址
来源：http://dali.fzhhl.top/Article/details/gtfewtxwxv.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.hongshengwenyu.top/Article/details/gtszsvpvcl.html

PHP:  curl_multi_init() 系列
来源：http://dali.bjfxy.top/Article/details/gtsjwrqkqk.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zycfv.cn/Article/details/gthzaoyyzx.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tanke756.top/Article/details/gtkznprnkr.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jyoumei.cn/Article/details/gtrmgzmkpo.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.svipenyu.cn/Article/details/gtvefjucei.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhixingplan.top/Article/details/gthnwonbfk.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yvedp.cn/Article/details/gtdicrehwl.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtlhsynguj.html

M. 命令行 / 进程 / 环境
来源：http://dali.quarkkingdee.top/Article/details/gttnvplrel.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtqgzzjeoj.html

[M01] 读取命令行参数
来源：http://dali.feifeiyinyue.top/Article/details/gtjhzmjdao.html

Py:   sys.argv[1:]
来源：http://dali.yuxming.cn/Article/details/gtlurlmvlt.html

PHP:  $argv;  $argc;
来源：http://dali.ydzc1.top/Article/details/gthsufiirt.html

JS:   process.argv.slice(2)
来源：http://dali.jiagoushi.top/Article/details/gtfvgaroyl.html

TS:   process.argv.slice(2)
来源：http://dali.cqqwz.cn/Article/details/gtldihorvi.html

Java: args 数组（main 方法参数）
来源：http://dali.hongshengwenyu.top/Article/details/gtluxdiwmz.html

Go:   os.Args[1:]
来源：http://dali.jinghuilouyu.cn/Article/details/gtcqqzvalw.html

Ruby: ARGV
来源：http://dali.zhixingplan.top/Article/details/gtelgmhjwn.html

C#:   args 数组（Main 方法参数）
来源：http://dali.hysaishi.cn/Article/details/gtzrvhjpfz.html

[M02] 读取环境变量
来源：http://dali.mhx1999.top/Article/details/gtazmwtmuv.html

Py:   os.environ.get("HOME")
来源：http://dali.kuanghao11.cn/Article/details/gtghlvpkwu.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.xinyue.icu/Article/details/gtalmsshup.html

JS:   process.env.HOME
来源：http://dali.guannengcc.top/Article/details/gtlhybhaap.html

TS:   process.env.HOME
来源：http://dali.yvedp.cn/Article/details/gtnectghkv.html

Java: System.getenv("HOME")
来源：http://dali.yj202588.top/Article/details/gtizrkjwgy.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.kuanghao11.cn/Article/details/gtipynkjvm.html

Ruby: ENV["HOME"]
来源：http://dali.zhixingplan.top/Article/details/gtjqvsgfaw.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.xziqi.cn/Article/details/gtjlcxxcjb.html

[M03] 执行外部命令
来源：http://dali.hnqzz.top/Article/details/gteplelcie.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.haohaochexian.top/Article/details/gtdfhwxjoo.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.ivvv.top/Article/details/gtwmehnpru.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.tianlin.xyz/Article/details/gtejmkqrgr.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.haohaochexian.top/Article/details/gtjardzgut.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.chenjidiqi.icu/Article/details/gtdzfeozqa.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.feifeiyinyue.top/Article/details/gtzsqnqczh.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jiagoushi.top/Article/details/gtywwiqwtx.html

C#:   Process.Start("ls", "-l");
来源：http://dali.cheryme.top/Article/details/gtdsnralih.html

[M04] 获取当前工作目录
来源：http://dali.wangdashe.top/Article/details/gtkngpygvt.html

Py:   os.getcwd()
来源：http://dali.zhengqikj.top/Article/details/gtsbdhxlhy.html

PHP:  getcwd();
来源：http://dali.zhoulong.xyz/Article/details/gtvbixwyii.html

JS:   process.cwd()
来源：http://dali.nanxinkj.top/Article/details/gtrsbqovfk.html

TS:   process.cwd()
来源：http://dali.jqgfzy.top/Article/details/gtotsfrxkv.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jlsjyb.cn/Article/details/gtukierdpt.html

Go:   os.Getwd()
来源：http://dali.jinghuilouyu.cn/Article/details/gtaxbhawme.html

Ruby: Dir.pwd
来源：http://dali.jinghuilouyu.cn/Article/details/gtgbhrtxsh.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yj20258.top/Article/details/gtqnhoklfn.html

[M05] 设置退出码
来源：http://dali.iojbl.cn/Article/details/gtzapbubun.html

Py:   sys.exit(1)
来源：http://dali.iojbl.cn/Article/details/gtgwhonwvn.html

PHP:  exit(1);
来源：http://dali.hongshengwenyu.top/Article/details/gtpwulmfwf.html

JS:   process.exit(1)
来源：http://dali.guowangkeji.top/Article/details/gtjzpykwmo.html

TS:   process.exit(1)
来源：http://dali.vqdsnc.cn/Article/details/gtsfegcqsd.html

Java: System.exit(1)
来源：http://dali.cdnleiting.top/Article/details/gtlzfaliww.html

Go:   os.Exit(1)
来源：http://dali.cdnleiting.top/Article/details/gtpvpvsaoy.html

Ruby: exit 1
来源：http://dali.kuanghao11.cn/Article/details/gtuvqtping.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.gotoacloud.top/Article/details/gthpqbizpp.html

[M06] 向标准错误输出
来源：http://dali.xinyue.icu/Article/details/gtvzvqmlph.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yj20258888.top/Article/details/gthrwgjmxn.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.shanyushiyangtech.top/Article/details/gtyoavkddt.html

JS:   console.error("err")
来源：http://dali.zdqjudy.top/Article/details/gtkucgcnro.html

TS:   console.error("err")
来源：http://dali.hfpthk.cn/Article/details/gtctusfzqt.html

Java: System.err.println("err")
来源：http://dali.gzhubu.top/Article/details/gthkkcuizi.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.cdnleiting.top/Article/details/gtbnqcfvvu.html

Ruby: warn "err"
来源：http://dali.pengpengdd.cyou/Article/details/gtfatzoojv.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zdqjudy.top/Article/details/gtljdblxii.html

[M07] 判断是否为主入口
来源：http://dali.gzhubu.top/Article/details/gtuiywtsuk.html

Py:   if __name__ == "__main__":
来源：http://dali.ybcxt.top/Article/details/gtjyebjkyi.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jinqigufen.top/Article/details/gtvvzfiqdh.html

JS:   require.main === module
来源：http://dali.cdnleiting.top/Article/details/gtjqnyiwoi.html

TS:   require.main === module
来源：http://dali.sxryk.cn/Article/details/gtloqhtovt.html

Java: public static void main(String[] args)
来源：http://dali.jqgufenzy.top/Article/details/gtuctfuruh.html

Go:   func main()
来源：http://dali.9152youxi.cn/Article/details/gtkiearxad.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yuxming.cn/Article/details/gtawmargvw.html

C#:   static void Main(string[] args)
来源：http://dali.cqqwz.cn/Article/details/gtojogwafs.html

[M08] 获取系统与运行时信息
来源：http://dali.jqgufenzy.top/Article/details/gtyuelktzh.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmdbwinja.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yanxiufei.cn/Article/details/gtgkgofwgd.html

JS:   process.platform;  process.version
来源：http://dali.jinqigufen.top/Article/details/gtgmqxmoxy.html

TS:   process.platform;  process.version
来源：http://dali.jqgufenzy.top/Article/details/gtqnqsepgy.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhongyouzk.top/Article/details/gtpslrdhyu.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.xziqi.cn/Article/details/gtcilntnzv.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.birdmap.top/Article/details/gtueahzmjl.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yangfankeji.com/Article/details/gteathmywr.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtxxyuhuvn.html

N. 数据结构与算法
来源：http://dali.zhoulong.xyz/Article/details/gtvqlvstcr.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtofdfcmrr.html

[N01] 二分查找（有序数组）
来源：http://dali.zhoulong.xyz/Article/details/gtnrojjkxz.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.ivvv.top/Article/details/gtgdbxfdpm.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhengqikj.top/Article/details/gtmuurgwtz.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.andypj.xyz/Article/details/gtfygdvwcn.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.daxiang520.top/Article/details/gttjaxqnzs.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.fengsongda.top/Article/details/gtwsdobiay.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.kuanghao11.cn/Article/details/gtqmnskrrw.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.vqdsnc.cn/Article/details/gtpvjvbpku.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.hywenlv.cn/Article/details/gtxeehlvaj.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.cdnleiting.top/Article/details/gtrcwjnhdq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.gzhubu.top/Article/details/gtcjwxtpet.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jqgfzy.top/Article/details/gtnikxgyii.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zycfv.cn/Article/details/gtazapuvoe.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sysykeji.top/Article/details/gtrknmgsur.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.kuanghao11.cn/Article/details/gtihaougek.html

Go:   slices.Sort(arr)
来源：http://dali.hysaishi.cn/Article/details/gtscqiccvq.html

Ruby: arr.sort
来源：http://dali.xziqi.cn/Article/details/gtdyykazxh.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.cdnleiting.top/Article/details/gteeejvhhp.html

[N03] 快速排序（分治示例）
来源：http://dali.nanxuanxn.top/Article/details/gtupwdvqng.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.birdmap.top/Article/details/gtglhulngr.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jianghu66.top/Article/details/gttefmnito.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuhhmxaes.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jiagoushi.top/Article/details/gtjxcsmuwf.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.cucudq.cn/Article/details/gtpjviupto.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwtzdwfjh.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.svipenyu.cn/Article/details/gtuedmygcq.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.ivvv.top/Article/details/gtggpgmrgh.html

[N04] 斐波那契数列
来源：http://dali.guannengcc.top/Article/details/gtwpyvuihx.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jinqigufen.top/Article/details/gtqcqibcbe.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.shangyingyoupin.top/Article/details/gtjaryubie.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hongshengwenyu.top/Article/details/gttzbkenxs.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.andypj.xyz/Article/details/gtpvnytpge.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.aibaodan.cn/Article/details/gtszvjgypl.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.fzhhl.top/Article/details/gtticjmceo.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.cheryme.top/Article/details/gtxhemzeky.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzndjybns.html

[N05] 最大公约数
来源：http://dali.andypj.xyz/Article/details/gtmeryvdzy.html

Py:   math.gcd(a, b)
来源：http://dali.chenzaomai.com/Article/details/gtkuemwwdm.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jqgfzy.top/Article/details/gtoqefbnzy.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jqgfzy.top/Article/details/gtzztvptdw.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.gaohongyu789.top/Article/details/gtvvcprndy.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.dianchejie.cn/Article/details/gtqtmuyyjr.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yongpay.top/Article/details/gtbkibhjwm.html

Ruby: a.gcd(b)
来源：http://dali.ehwqpu.com/Article/details/gtedqtahlb.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.feifeiyinyue.top/Article/details/gtdcyzbvcz.html

[N06] 判断回文字符串
来源：http://dali.daria6918.cn/Article/details/gtyrgsurmd.html

Py:   s == s[::-1]
来源：http://dali.aibaodan.cn/Article/details/gthxyhknnf.html

PHP:  $s === strrev($s);
来源：http://dali.nanxuanxn.top/Article/details/gtkvqumiog.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jiagoushi.top/Article/details/gtcxezewiu.html

TS:   s === [...s].reverse().join("")
来源：http://dali.guannengcc.top/Article/details/gtmhcqjiez.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.nwbrower.top/Article/details/gtcmzwtzcm.html

Go:   // 双指针从两端比较
来源：http://dali.zhongyouzk.top/Article/details/gtguzjagza.html

Ruby: s == s.reverse
来源：http://dali.c1oappe.top/Article/details/gtdnodfpmj.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jinqigfzy.top/Article/details/gthhrxyymk.html

[N07] 两数之和（返回下标）
来源：http://dali.fengsongda.top/Article/details/gtuhdxewpd.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.daria6918.cn/Article/details/gtivjssxdr.html


<!-- 参考信息 -->