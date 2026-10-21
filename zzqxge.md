代发 wailian999

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zycfv.cn/Article/details/gtwdkxdxzd.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.daria6918.cn/Article/details/gtscbqnxes.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhixingplan.top/Article/details/gtpgdirgmb.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.ybcxt.top/Article/details/gtipjmupjk.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yj202588.top/Article/details/gtazliqgke.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhoulong.xyz/Article/details/gtsakpwxxt.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yueranfly.top/Article/details/gtjifcmmsk.html

[J10] 取今天 / 本月第一天
来源：http://dali.aibaodan.cn/Article/details/gtbxvjtpss.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.gotoacloud.top/Article/details/gttodskcnu.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.aizwys.cn/Article/details/gtxtkvxohs.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrztyxlwq.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yueranfly.top/Article/details/gtgafhbnsc.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.ybcxt.top/Article/details/gtotagccff.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.hongshengwenyu.top/Article/details/gthlgxmner.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.chenlongwang.top/Article/details/gtuxiugvtc.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtydhrdmyl.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtsniczhbo.html

K. JSON 与序列化
来源：http://dali.nanxuanxn.top/Article/details/gtngfwtavz.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtouhwcxdk.html

[K01] 对象转 JSON 字符串
来源：http://dali.yuanzhike.top/Article/details/gthxeasmuo.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.xuetiantiany.cn/Article/details/gtgathddez.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jinqigfzy.top/Article/details/gtmqcibciw.html

JS:   JSON.stringify(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gttrhsjzjx.html

TS:   JSON.stringify(obj)
来源：http://dali.jinqigufen.top/Article/details/gttadvxxuh.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.meibo888.top/Article/details/gtqujydiee.html

Go:   json.Marshal(obj)
来源：http://dali.daxiang520.top/Article/details/gtgodjpadq.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jinqigfzy.top/Article/details/gtddczvppe.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.havefunace.top/Article/details/gtwbogzloj.html

[K02] JSON 字符串转对象
来源：http://dali.nwbrower.top/Article/details/gttzjvdbaj.html

Py:   json.loads(s)
来源：http://dali.jyoumei.cn/Article/details/gttfauqkyp.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.pengpengdd.cyou/Article/details/gtsubpfqqn.html

JS:   JSON.parse(s)
来源：http://dali.ehwqpu.com/Article/details/gtjdrrxlmf.html

TS:   JSON.parse(s)
来源：http://dali.ehwqpu.com/Article/details/gtlnzyomxw.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.quarkkingdee.top/Article/details/gtgbyajgov.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.hnqzz.top/Article/details/gtfgtutsfi.html

Ruby: JSON.parse(s)
来源：http://dali.sweek.top/Article/details/gtjrihxvvk.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.xinyue.icu/Article/details/gtkcqngvqt.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yanxiufei.cn/Article/details/gtqfgbsivk.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zdqjudy.top/Article/details/gtbjnckujp.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.smart0.xyz/Article/details/gtfdvnceyy.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.wangdashe.top/Article/details/gtulejijqm.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.hnxiangtu.top/Article/details/gtkkmyzosl.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gtpvzbncai.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yvedp.cn/Article/details/gtcczwxdbv.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.andypj.xyz/Article/details/gtxgadhkhr.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.pengpengdd.cyou/Article/details/gtxlmqccto.html

[K04] 读取 JSON 文件
来源：http://dali.aizwys.cn/Article/details/gtmbfjawsz.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.cqqwz.cn/Article/details/gtsqbkwvoj.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.gogol.net.cn/Article/details/gtciudagyt.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhengqikj.top/Article/details/gtlhfzpcfb.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhijiandao.cn/Article/details/gtjjlfacml.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jqgufenzy.top/Article/details/gtmkmqearm.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.svipenyu.cn/Article/details/gtdmgexvpc.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.chenjidiqi.icu/Article/details/gtidalfhkj.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.316326.xyz/Article/details/gtscdgssde.html

[K05] 深拷贝对象
来源：http://dali.fzhhl.top/Article/details/gtrgvcvctg.html

Py:   copy.deepcopy(obj)
来源：http://dali.daxiang520.top/Article/details/gtdgzmbaev.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yj202588.top/Article/details/gteolnewya.html

JS:   structuredClone(obj)
来源：http://dali.cqqwz.cn/Article/details/gtmchbqrch.html

TS:   structuredClone(obj)
来源：http://dali.hnqzz.top/Article/details/gtkwiiexjd.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.ppjwa.cn/Article/details/gtlaysqdmv.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.hammf.cn/Article/details/gtwthzsyox.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.0kj1m.cn/Article/details/gtfzvmjxlr.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yj202588.top/Article/details/gtytgtmmfd.html

[K06] 解析 URL 查询串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbjpvhuxv.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.nanxuanxn.top/Article/details/gtfagnrstg.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.svipenyu.cn/Article/details/gtojskjwxj.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cqqwz.cn/Article/details/gtdsoqvksa.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhiwuduotai.top/Article/details/gtpgudhzbh.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yueranfly.top/Article/details/gtwzmgbqnf.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.smart0.xyz/Article/details/gtutcqkxuc.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.cqqwz.cn/Article/details/gtovxqsasl.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.hammf.cn/Article/details/gtkdhlavng.html

[K07] 进制转换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtchouixtz.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jyoumei.cn/Article/details/gtliygneum.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.hfpthk.cn/Article/details/gtfiaueflz.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhixingplan.top/Article/details/gttqhdbuwm.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.shanyushiyangtech.top/Article/details/gtznxditdv.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.dianchejie.cn/Article/details/gtiipmnhjk.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.hfpthk.cn/Article/details/gtjbvafkmx.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.snrcjt.cn/Article/details/gtngknbjxg.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.aizwys.cn/Article/details/gthfaqkpgw.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.0kj1m.cn/Article/details/gtxmujgdcn.html

Py:   pickle.dumps(obj)
来源：http://dali.jqgfzy.top/Article/details/gtnybcxucx.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.dashuyun.cn/Article/details/gtnavyauix.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.wangshuangyany.cn/Article/details/gttualnhnz.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.chenzaomai.com/Article/details/gttyzhnwwf.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.wangdashe.top/Article/details/gtiiykckco.html

Go:   encoding/gob
来源：http://dali.chenlongwang.top/Article/details/gtfpsydaye.html

Ruby: Marshal.dump(obj)
来源：http://dali.smart0.xyz/Article/details/gtkexbcmkd.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.chenjidiqi.icu/Article/details/gtadvfvffi.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtmdsnyght.html

L. 网络请求
来源：http://dali.feifeiyinyue.top/Article/details/gtfvghsjjj.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtfosigqyh.html

[L01] 发送 GET 请求
来源：http://dali.yvedp.cn/Article/details/gtanzeeeev.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.kuanghao11.cn/Article/details/gtbhkuuoni.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.feifeiyinyue.top/Article/details/gtfkqpvqdh.html

JS:   await fetch(url)
来源：http://dali.zhongyouzk.top/Article/details/gtwzwkkueo.html

TS:   await fetch(url)
来源：http://dali.yj20258888.top/Article/details/gtbpfhmaey.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.tianlin.xyz/Article/details/gtocgjjvkl.html

Go:   resp, err := http.Get(url)
来源：http://dali.chenjidiqi.icu/Article/details/gtmobzilye.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.ywan-chungtsiang.top/Article/details/gteadbprxu.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yvedp.cn/Article/details/gtkjfhiwft.html

[L02] 发送 POST JSON
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzyjzoyzc.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jyoumei.cn/Article/details/gtetuyfxnq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.chenlongwang.top/Article/details/gtdfyplgrp.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cheryme.top/Article/details/gtjhbrnrto.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.9152youxi.cn/Article/details/gtctnolqbi.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yj202588.top/Article/details/gtturcfddq.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.sysykeji.top/Article/details/gtgttwbsuv.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.wangdashe.top/Article/details/gtakqrwdhd.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.gogol.net.cn/Article/details/gtbthxfsjg.html

[L03] 设置自定义请求头
来源：http://dali.chenjidiqi.icu/Article/details/gtvllpitjj.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zdqjudy.top/Article/details/gthevbgsoa.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.kuanghao11.cn/Article/details/gtjqxsfiiz.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jinqigfzy.top/Article/details/gtzwyjkpmh.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hammf.cn/Article/details/gtpjaxxlhe.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zdqjudy.top/Article/details/gtigvrsjdx.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqepyejnp.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.gzhubu.top/Article/details/gttjzazunr.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhixingplan.top/Article/details/gtopxszwna.html

[L04] 设置超时
来源：http://dali.chenjidiqi.icu/Article/details/gtahjrbslo.html

Py:   requests.get(url, timeout=5)
来源：http://dali.gzhubu.top/Article/details/gtctlkfwwe.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yongpay.top/Article/details/gtmiuwgksc.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.nwbrower.top/Article/details/gtpcexdywm.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.aibaodan.cn/Article/details/gtqslgijem.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.quarkkingdee.top/Article/details/gtclilggqp.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.ivvv.top/Article/details/gtdoonktvc.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.cucudq.cn/Article/details/gtogqrmqjk.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yangfankeji.com/Article/details/gtoirdbbni.html

[L05] 上传文件（multipart）
来源：http://dali.jinqigufen.top/Article/details/gtyezyrwgz.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.havefunace.top/Article/details/gtbhqmdqsz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.pycfn.com/Article/details/gtuatxpdvl.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.316326.xyz/Article/details/gttjadbgzq.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.xinyue.icu/Article/details/gtbxtzujlu.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.shuidangran.top/Article/details/gtwalquxuv.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.cqqwz.cn/Article/details/gteizyuubx.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.fzhhl.top/Article/details/gtnurpcrmn.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.0kj1m.cn/Article/details/gtwhomloze.html

[L06] 解析响应为 JSON
来源：http://dali.mhx1999.top/Article/details/gtfdddhpym.html

Py:   resp.json()
来源：http://dali.jyoumei.cn/Article/details/gtlpfgebcw.html

PHP:  json_decode($body, true);
来源：http://dali.cucudq.cn/Article/details/gtsenpsgov.html

JS:   await resp.json()
来源：http://dali.yonumen.top/Article/details/gtaxcjlrmw.html

TS:   await resp.json()
来源：http://dali.nwbrower.top/Article/details/gtryjzjyie.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jinqigufen.top/Article/details/gtavuzglwm.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yvedp.cn/Article/details/gtvsjgefzv.html

Ruby: JSON.parse(resp.body)
来源：http://dali.guannengcc.top/Article/details/gtiobxffmz.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jqgfzy.top/Article/details/gtpghhwzoy.html

[L07] 处理 HTTP 状态码
来源：http://dali.gaohongyu789.top/Article/details/gtmcmtglxr.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jlsjyb.cn/Article/details/gtbqmdkmkv.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.ivvv.top/Article/details/gtbocxitym.html

JS:   resp.ok;  resp.status
来源：http://dali.wangdashe.top/Article/details/gttculmkks.html

TS:   resp.ok;  resp.status
来源：http://dali.dashuyun.cn/Article/details/gtvbytfwmg.html

Java: resp.statusCode()
来源：http://dali.guannengcc.top/Article/details/gtgbkxgaak.html

Go:   resp.StatusCode
来源：http://dali.shanyushiyangtech.top/Article/details/gtlmzpqyaq.html

Ruby: resp.code.to_i
来源：http://dali.yuxming.cn/Article/details/gtzhoelaeh.html

C#:   (int)resp.StatusCode
来源：http://dali.cdnleiting.top/Article/details/gtphopqsrg.html

[L08] 并发请求多个地址
来源：http://dali.jinyuanbaomall.cn/Article/details/gttkidbpfv.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jlsjyb.cn/Article/details/gthtltfziw.html

PHP:  curl_multi_init() 系列
来源：http://dali.fzhhl.top/Article/details/gttzhuyahw.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.haohaochexian.top/Article/details/gtmmlyoxul.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xuanzx.com/Article/details/gtrrgjbbep.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.cheryme.top/Article/details/gtatqoqzsi.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.xinyue.icu/Article/details/gtfahacjjs.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.sufxvd.cn/Article/details/gtqwmznpkr.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.cdnleiting.top/Article/details/gtsztwbocj.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gttidurguh.html

M. 命令行 / 进程 / 环境
来源：http://dali.chenjidiqi.icu/Article/details/gtcrjfbjqi.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtryncoeej.html

[M01] 读取命令行参数
来源：http://dali.mhx1999.top/Article/details/gtgjkuboid.html

Py:   sys.argv[1:]
来源：http://dali.yj20258888.top/Article/details/gtqayqjqyl.html

PHP:  $argv;  $argc;
来源：http://dali.yj202588.top/Article/details/gtjvshruua.html

JS:   process.argv.slice(2)
来源：http://dali.aibaodan.cn/Article/details/gtoebtwgqb.html

TS:   process.argv.slice(2)
来源：http://dali.feifeiyinyue.top/Article/details/gtgfxtvafy.html

Java: args 数组（main 方法参数）
来源：http://dali.tianlin.xyz/Article/details/gttmureysy.html

Go:   os.Args[1:]
来源：http://dali.xylfe.cn/Article/details/gtbsrzkblh.html

Ruby: ARGV
来源：http://dali.jqgufenzy.top/Article/details/gtvfroawtf.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yj202588.top/Article/details/gtkclgspcy.html

[M02] 读取环境变量
来源：http://dali.hnxiangtu.top/Article/details/gtuezkjtmg.html

Py:   os.environ.get("HOME")
来源：http://dali.hammf.cn/Article/details/gttlpvnnhk.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.sysykeji.top/Article/details/gtxnzvlvuk.html

JS:   process.env.HOME
来源：http://dali.ehwqpu.com/Article/details/gtsdlfwnkd.html

TS:   process.env.HOME
来源：http://dali.zhoulong.xyz/Article/details/gtgsudaixq.html

Java: System.getenv("HOME")
来源：http://dali.jyoumei.cn/Article/details/gtcbwhyhna.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jinghuilouyu.cn/Article/details/gtetajgqtu.html

Ruby: ENV["HOME"]
来源：http://dali.vqdsnc.cn/Article/details/gtzfxnuptr.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jinqigufen.top/Article/details/gtxlrioivt.html

[M03] 执行外部命令
来源：http://dali.ivvv.top/Article/details/gtzkkgyxva.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.haohaochexian.top/Article/details/gtiksdihyb.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.nanxinkj.top/Article/details/gtrxixsbbp.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.hammf.cn/Article/details/gtcvrtgmlh.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jianghu66.top/Article/details/gtgfdtbvyl.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.cheryme.top/Article/details/gtrnhagiyb.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.pycfn.com/Article/details/gtnbvdujik.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.shangyingyoupin.top/Article/details/gtaeckcwst.html

C#:   Process.Start("ls", "-l");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtedylofiq.html

[M04] 获取当前工作目录
来源：http://dali.smart0.xyz/Article/details/gteffvsgsn.html

Py:   os.getcwd()
来源：http://dali.ybcxt.top/Article/details/gtvbaxvtmp.html

PHP:  getcwd();
来源：http://dali.shangyingyoupin.top/Article/details/gtzvabanwy.html

JS:   process.cwd()
来源：http://dali.hnxiangtu.top/Article/details/gtlzpdjemr.html

TS:   process.cwd()
来源：http://dali.jinqigfzy.top/Article/details/gtyrzjroyq.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhiwuduotai.top/Article/details/gttpubnllt.html

Go:   os.Getwd()
来源：http://dali.andypj.xyz/Article/details/gtqucpkcfu.html

Ruby: Dir.pwd
来源：http://dali.ywan-chungtsiang.top/Article/details/gtauzphfzb.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.cheryme.top/Article/details/gtsfyeypfv.html

[M05] 设置退出码
来源：http://dali.cashguo.top/Article/details/gtnyhxudel.html

Py:   sys.exit(1)
来源：http://dali.shzxlz.cn/Article/details/gtljpqfpql.html

PHP:  exit(1);
来源：http://dali.xziqi.cn/Article/details/gtwqayueyt.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gtxeipvocw.html

TS:   process.exit(1)
来源：http://dali.gotoacloud.top/Article/details/gtfogxtxyl.html

Java: System.exit(1)
来源：http://dali.daria6918.cn/Article/details/gtujvmatqf.html

Go:   os.Exit(1)
来源：http://dali.tian-w.cn/Article/details/gtvzvcsefo.html

Ruby: exit 1
来源：http://dali.hfpthk.cn/Article/details/gtmzsbymzi.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.daria6918.cn/Article/details/gtvmxedwda.html

[M06] 向标准错误输出
来源：http://dali.quarkkingdee.top/Article/details/gtbfynmyep.html

Py:   print("err", file=sys.stderr)
来源：http://dali.xylfe.cn/Article/details/gtcwftzkml.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.shangyingyoupin.top/Article/details/gtabxswmcx.html

JS:   console.error("err")
来源：http://dali.hammf.cn/Article/details/gtfzuyqdod.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gtppdsrmyu.html

Java: System.err.println("err")
来源：http://dali.guannengcc.top/Article/details/gtprmmxpng.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.aibaodan.cn/Article/details/gtaffoafbv.html

Ruby: warn "err"
来源：http://dali.sxryk.cn/Article/details/gtajxqjqeu.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtneztaxpl.html

[M07] 判断是否为主入口
来源：http://dali.gogol.net.cn/Article/details/gtowcqvuoy.html

Py:   if __name__ == "__main__":
来源：http://dali.jinghuilouyu.cn/Article/details/gtxkwwxdyn.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yongpay.top/Article/details/gtuvhfevfv.html

JS:   require.main === module
来源：http://dali.tanke756.top/Article/details/gtpnkhnjni.html

TS:   require.main === module
来源：http://dali.jiagoushi.top/Article/details/gtxsqqjyep.html

Java: public static void main(String[] args)
来源：http://dali.yuxming.cn/Article/details/gtcynptazh.html

Go:   func main()
来源：http://dali.zhiwuduotai.top/Article/details/gtirqxpimy.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.9152youxi.cn/Article/details/gtbgndeskn.html

C#:   static void Main(string[] args)
来源：http://dali.tianlin.xyz/Article/details/gtlfumteqe.html

[M08] 获取系统与运行时信息
来源：http://dali.yuanzhike.top/Article/details/gtkvdctnai.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhongyouzk.top/Article/details/gttboryvuj.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.hnqzz.top/Article/details/gtbzcrnoov.html

JS:   process.platform;  process.version
来源：http://dali.yonumen.top/Article/details/gtfilvidva.html

TS:   process.platform;  process.version
来源：http://dali.daxiang520.top/Article/details/gtjwgouolt.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.gzhubu.top/Article/details/gteomtxpus.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.fzhhl.top/Article/details/gtysjyblim.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yj202588.top/Article/details/gtxqonlqvy.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.nanxuanxn.top/Article/details/gttoyoudlv.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtyenvouoq.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gtrdmscuap.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gthzmqnkpu.html

[N01] 二分查找（有序数组）
来源：http://dali.svipenyu.cn/Article/details/gtwcfstqiq.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.sxryk.cn/Article/details/gtibmlszpy.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.wangshuangyany.cn/Article/details/gttjgniuuw.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jiagoushi.top/Article/details/gtjenrdhgg.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhaomingkeji.xyz/Article/details/gttuxguefr.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zycfv.cn/Article/details/gtpdrbzxms.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yj202588.top/Article/details/gtttqfyysd.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jlsjyb.cn/Article/details/gtdduzbjkr.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.tian-w.cn/Article/details/gtrsadadgj.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.havefunace.top/Article/details/gtzkaroplv.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.gogol.net.cn/Article/details/gtgnomgigp.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.dashuyun.cn/Article/details/gttpeihwwc.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shuidangran.top/Article/details/gtraenxnud.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yuxming.cn/Article/details/gtuzhugvzk.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.xuanzx.com/Article/details/gtplatbkfy.html

Go:   slices.Sort(arr)
来源：http://dali.ydzc1.top/Article/details/gtlflkukgi.html

Ruby: arr.sort
来源：http://dali.ppjwa.cn/Article/details/gtjzvcwlab.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.wangdashe.top/Article/details/gtkuxanntj.html

[N03] 快速排序（分治示例）
来源：http://dali.sweek.top/Article/details/gtzvqfbnro.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.cucudq.cn/Article/details/gtygdftjfl.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yj20258888.top/Article/details/gtzozowvjk.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.nwbrower.top/Article/details/gtpnefkssz.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cheryme.top/Article/details/gtydxgynxt.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.kuanghao11.cn/Article/details/gtuwetvzxc.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.aizwys.cn/Article/details/gtzwqxosvu.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.hysaishi.cn/Article/details/gtjufydalx.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jinqigfzy.top/Article/details/gtvfsijcrf.html

[N04] 斐波那契数列
来源：http://dali.yj20258.top/Article/details/gthxdemqyg.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.xziqi.cn/Article/details/gtxrajclii.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhengqikj.top/Article/details/gtyytaxezo.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cashguo.top/Article/details/gtjiynwebr.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.tianlin.xyz/Article/details/gtbqvhzaxi.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.fzhhl.top/Article/details/gtvdcuupnx.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhiwuduotai.top/Article/details/gtmwdrwqql.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjqqslopf.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zycfv.cn/Article/details/gtwwzekcib.html

[N05] 最大公约数
来源：http://dali.chenzaomai.com/Article/details/gtcvilbyhe.html

Py:   math.gcd(a, b)
来源：http://dali.aizwys.cn/Article/details/gtrpkjlpru.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jqgfzy.top/Article/details/gtqevxboqj.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.aibaodan.cn/Article/details/gtsqhpqsce.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.daxiang520.top/Article/details/gtlnbwdbuw.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.wangdashe.top/Article/details/gtfjygcrte.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zdqjudy.top/Article/details/gtfdfkjtvz.html

Ruby: a.gcd(b)
来源：http://dali.ehwqpu.com/Article/details/gtbwlhoqkq.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.bjfxy.top/Article/details/gtivxkfcdv.html

[N06] 判断回文字符串
来源：http://dali.guowangkeji.top/Article/details/gtwgnbzzth.html

Py:   s == s[::-1]
来源：http://dali.jinghuilouyu.cn/Article/details/gttxwltebu.html

PHP:  $s === strrev($s);
来源：http://dali.iojbl.cn/Article/details/gthipnjbus.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jyoumei.cn/Article/details/gtpwbhncnp.html

TS:   s === [...s].reverse().join("")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbvhotgfn.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.sweek.top/Article/details/gtalwpjkjh.html

Go:   // 双指针从两端比较
来源：http://dali.hywenlv.cn/Article/details/gtlzxfxqwv.html

Ruby: s == s.reverse
来源：http://dali.bjfxy.top/Article/details/gtdvorhiqu.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrpwgiske.html

[N07] 两数之和（返回下标）
来源：http://dali.jyoumei.cn/Article/details/gttotivsrc.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.chenzaomai.com/Article/details/gtruxrsdpi.html


<!-- 参考信息 -->