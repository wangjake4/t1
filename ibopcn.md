代发 wailian999

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.sufxvd.cn/Article/details/gtsrjbvgaq.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zycfv.cn/Article/details/gtdetaewez.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.havefunace.top/Article/details/gtuuxbokly.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.sufxvd.cn/Article/details/gtjbnwmyin.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.xuetiantiany.cn/Article/details/gturykwynq.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yangfankeji.com/Article/details/gtlyepnqqk.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zhiwuduotai.top/Article/details/gtcasuzhjk.html

[J10] 取今天 / 本月第一天
来源：http://dali.tian-w.cn/Article/details/gtijinuaxx.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.smart0.xyz/Article/details/gtvbmxcqtt.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jiagoushi.top/Article/details/gttkrgtrjv.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yj20258.top/Article/details/gtmbyunswh.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jiagoushi.top/Article/details/gtftxavruv.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.fengsongda.top/Article/details/gtrtpbuumc.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.xuanzx.com/Article/details/gtfqrulcnn.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.havefunace.top/Article/details/gtvxadarmd.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.cheryme.top/Article/details/gtobrqunzj.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtwpnsklip.html

K. JSON 与序列化
来源：http://dali.guowangkeji.top/Article/details/gtdfgdorfr.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtwyzdhpdm.html

[K01] 对象转 JSON 字符串
来源：http://dali.yj202588.top/Article/details/gttzeogjux.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yj20258888.top/Article/details/gtgxyozcho.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.chenjidiqi.icu/Article/details/gteqnrazcy.html

JS:   JSON.stringify(obj)
来源：http://dali.hnxiangtu.top/Article/details/gtujouzsng.html

TS:   JSON.stringify(obj)
来源：http://dali.nwbrower.top/Article/details/gtvrisolhp.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcyhvcfbk.html

Go:   json.Marshal(obj)
来源：http://dali.jlsjyb.cn/Article/details/gttxjwycmg.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.xylfe.cn/Article/details/gtlmdsrpqz.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.kuanghao11.cn/Article/details/gtobfzacax.html

[K02] JSON 字符串转对象
来源：http://dali.ehwqpu.com/Article/details/gtwjhxghxe.html

Py:   json.loads(s)
来源：http://dali.guowangkeji.top/Article/details/gtmcpakshy.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhengqikj.top/Article/details/gtdwpyeumd.html

JS:   JSON.parse(s)
来源：http://dali.sweek.top/Article/details/gtvydtdlry.html

TS:   JSON.parse(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtyacnkxfo.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.aibaodan.cn/Article/details/gtegjrdsxw.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.andypj.xyz/Article/details/gtqkimmfrr.html

Ruby: JSON.parse(s)
来源：http://dali.vqdsnc.cn/Article/details/gtcanldrje.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.quarkkingdee.top/Article/details/gtqocshnnf.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrwbqnpww.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.daria6918.cn/Article/details/gtrkgckwmy.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.shzxlz.cn/Article/details/gtmigjyltl.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.tianlin.xyz/Article/details/gtqbximkxz.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.svipenyu.cn/Article/details/gtaymqxsqh.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.ehwqpu.com/Article/details/gtnbxdzfdu.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.hywenlv.cn/Article/details/gtkdbdnqlf.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.svipenyu.cn/Article/details/gtxzfshovs.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.xylfe.cn/Article/details/gtwlqopheq.html

[K04] 读取 JSON 文件
来源：http://dali.ehwqpu.com/Article/details/gtdsikdmio.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.wangdashe.top/Article/details/gtnmsoqlfw.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.gzhubu.top/Article/details/gtsaucfjed.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cashguo.top/Article/details/gtihzcyymo.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.hywenlv.cn/Article/details/gtzdgstxvr.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.gaohongyu789.top/Article/details/gtaggrcdrd.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.dianchejie.cn/Article/details/gtjracbtpu.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.nwbrower.top/Article/details/gtmjbbuask.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hysaishi.cn/Article/details/gtnundlrrw.html

[K05] 深拷贝对象
来源：http://dali.jinyuanbaomall.cn/Article/details/gthsrpviis.html

Py:   copy.deepcopy(obj)
来源：http://dali.guannengcc.top/Article/details/gtvwcfxehr.html

PHP:  unserialize(serialize($obj));
来源：http://dali.gaohongyu789.top/Article/details/gtkdknygni.html

JS:   structuredClone(obj)
来源：http://dali.havefunace.top/Article/details/gtdapeskxg.html

TS:   structuredClone(obj)
来源：http://dali.daria6918.cn/Article/details/gtycieosjd.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.pengpengdd.cyou/Article/details/gtrogywspg.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.tian-w.cn/Article/details/gtklnsxxst.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.gzhubu.top/Article/details/gtabjclfgn.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.sufxvd.cn/Article/details/gtqwcpezqw.html

[K06] 解析 URL 查询串
来源：http://dali.dianchejie.cn/Article/details/gtxyhjxqsu.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhaomingkeji.xyz/Article/details/gthehmencm.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.chenzaomai.com/Article/details/gthpawhmod.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ivvv.top/Article/details/gtbrojpvpr.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhongyouzk.top/Article/details/gtykzqyfog.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.shzxlz.cn/Article/details/gtdkzbjlwr.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdicutczz.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.hfpthk.cn/Article/details/gthzexbtvg.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.cashguo.top/Article/details/gthdwlwyjs.html

[K07] 进制转换
来源：http://dali.fzhhl.top/Article/details/gtenwjqipx.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.aizwys.cn/Article/details/gtwjkwblvx.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yj20258888.top/Article/details/gtznwrggum.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.tanke756.top/Article/details/gtfuzawhsj.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhixingplan.top/Article/details/gteyognuld.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.xziqi.cn/Article/details/gtmqqhacad.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.kuanghao11.cn/Article/details/gtwgdabasm.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpogvcssm.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.smart0.xyz/Article/details/gthbglzwco.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpkprafzq.html

Py:   pickle.dumps(obj)
来源：http://dali.pycfn.com/Article/details/gtceeyhare.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.sysykeji.top/Article/details/gtltwlulhx.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.quarkkingdee.top/Article/details/gtqcdkqfgq.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yangfankeji.com/Article/details/gthlqdqsyt.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.hongshengwenyu.top/Article/details/gtfynsaykf.html

Go:   encoding/gob
来源：http://dali.yj202588.top/Article/details/gthbmyqmhp.html

Ruby: Marshal.dump(obj)
来源：http://dali.yanxiufei.cn/Article/details/gtidmpdjhn.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhongyouzk.top/Article/details/gtykbbxiai.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtbewwsocc.html

L. 网络请求
来源：http://dali.svipenyu.cn/Article/details/gtarnvgogc.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtrnnjrlba.html

[L01] 发送 GET 请求
来源：http://dali.cheryme.top/Article/details/gtbetcrspp.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.tanke756.top/Article/details/gtnudsxmxr.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.guannengcc.top/Article/details/gtyzivxcnd.html

JS:   await fetch(url)
来源：http://dali.sweek.top/Article/details/gtzakuudvi.html

TS:   await fetch(url)
来源：http://dali.ybcxt.top/Article/details/gtjdsvpnmq.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.316326.xyz/Article/details/gtsmpntneb.html

Go:   resp, err := http.Get(url)
来源：http://dali.guowangkeji.top/Article/details/gtaozdcuct.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.gaohongyu789.top/Article/details/gtixekyeag.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yangfankeji.com/Article/details/gtezqsrwyr.html

[L02] 发送 POST JSON
来源：http://dali.wangdashe.top/Article/details/gtlvupkutq.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.aizwys.cn/Article/details/gtwugfnycy.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jiagoushi.top/Article/details/gtwkksovew.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hammf.cn/Article/details/gtewwfelkz.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.birdmap.top/Article/details/gttvwigsnt.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.xuetiantiany.cn/Article/details/gtngzfynwg.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.cucudq.cn/Article/details/gtpteqpqgb.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.redwolf501.top/Article/details/gtttxuofji.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.fengsongda.top/Article/details/gtlmltvifn.html

[L03] 设置自定义请求头
来源：http://dali.gotoacloud.top/Article/details/gtxzfcglxj.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.xuetiantiany.cn/Article/details/gttgwjfalm.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.hysaishi.cn/Article/details/gtxfegckfd.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gtzrobbvqs.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.bjfxy.top/Article/details/gtpzaeakkc.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.aibaodan.cn/Article/details/gtwfiapzmg.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhoulong.xyz/Article/details/gtnihgzjoc.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.gogol.net.cn/Article/details/gtywyjnrzr.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.hywenlv.cn/Article/details/gtyxcnkkxa.html

[L04] 设置超时
来源：http://dali.jinqigfzy.top/Article/details/gtpdoikviw.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yuxming.cn/Article/details/gtixamdbdv.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.feifeiyinyue.top/Article/details/gtixcvokbb.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.9152youxi.cn/Article/details/gtihocrcgu.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.tianlin.xyz/Article/details/gtcjzfalvu.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.andypj.xyz/Article/details/gttzmuuqyd.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.havefunace.top/Article/details/gtlzwovsqa.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.guannengcc.top/Article/details/gtimnwkexr.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.cucudq.cn/Article/details/gtkmeydebr.html

[L05] 上传文件（multipart）
来源：http://dali.yanxiufei.cn/Article/details/gtjossftwo.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.0kj1m.cn/Article/details/gtwvjnnriy.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.hywenlv.cn/Article/details/gtixmftkwh.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yuanzhike.top/Article/details/gtidqkfvic.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jlsjyb.cn/Article/details/gtpwanfzjm.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jiagoushi.top/Article/details/gtfjbmvwro.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.daxiang520.top/Article/details/gtjwbztpfa.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.guowangkeji.top/Article/details/gtfkpjyxxz.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.haohaochexian.top/Article/details/gtveyzdbtr.html

[L06] 解析响应为 JSON
来源：http://dali.sufxvd.cn/Article/details/gtlpkurorn.html

Py:   resp.json()
来源：http://dali.ehwqpu.com/Article/details/gtzdgwmswl.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gtubovohvv.html

JS:   await resp.json()
来源：http://dali.dianchejie.cn/Article/details/gtqqvigwlp.html

TS:   await resp.json()
来源：http://dali.ehwqpu.com/Article/details/gteresyisj.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.cucudq.cn/Article/details/gtshoznqra.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jinqigfzy.top/Article/details/gttdwvzmco.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhiwuduotai.top/Article/details/gtwnwzltvt.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jinqigufen.top/Article/details/gtdgbyggtx.html

[L07] 处理 HTTP 状态码
来源：http://dali.kuanghao11.cn/Article/details/gthyznssjd.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.aizwys.cn/Article/details/gtlbmmqfbf.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.gzhubu.top/Article/details/gtblnutysa.html

JS:   resp.ok;  resp.status
来源：http://dali.shuidangran.top/Article/details/gtggrjpusv.html

TS:   resp.ok;  resp.status
来源：http://dali.dashuyun.cn/Article/details/gtzdtbktyl.html

Java: resp.statusCode()
来源：http://dali.jyoumei.cn/Article/details/gtotoqmslp.html

Go:   resp.StatusCode
来源：http://dali.quarkkingdee.top/Article/details/gtscbjonld.html

Ruby: resp.code.to_i
来源：http://dali.sufxvd.cn/Article/details/gtnwdieioj.html

C#:   (int)resp.StatusCode
来源：http://dali.yanxiufei.cn/Article/details/gtqjzpvfbl.html

[L08] 并发请求多个地址
来源：http://dali.aibaodan.cn/Article/details/gtknnjjfhc.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jinghuilouyu.cn/Article/details/gtkuptamfo.html

PHP:  curl_multi_init() 系列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthxwoaaqy.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.haohaochexian.top/Article/details/gtadmecbwu.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zdqjudy.top/Article/details/gtfnirltgp.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.svipenyu.cn/Article/details/gtaipvntfx.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhoulong.xyz/Article/details/gtegkrlmci.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.guowangkeji.top/Article/details/gtlkwepoxi.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.sxryk.cn/Article/details/gttnqrwcbd.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtkrrhlkmf.html

M. 命令行 / 进程 / 环境
来源：http://dali.316326.xyz/Article/details/gttobctzob.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtzamyoexb.html

[M01] 读取命令行参数
来源：http://dali.zhongyouzk.top/Article/details/gthqhmdfrg.html

Py:   sys.argv[1:]
来源：http://dali.yueranfly.top/Article/details/gtckilnznm.html

PHP:  $argv;  $argc;
来源：http://dali.xuanzx.com/Article/details/gtnyqppgxn.html

JS:   process.argv.slice(2)
来源：http://dali.aibaodan.cn/Article/details/gtqtlwqyod.html

TS:   process.argv.slice(2)
来源：http://dali.hywenlv.cn/Article/details/gtscglgrrs.html

Java: args 数组（main 方法参数）
来源：http://dali.shangyingyoupin.top/Article/details/gtilvgqbmd.html

Go:   os.Args[1:]
来源：http://dali.yvedp.cn/Article/details/gtnspofkzl.html

Ruby: ARGV
来源：http://dali.pycfn.com/Article/details/gtxbxvgcmq.html

C#:   args 数组（Main 方法参数）
来源：http://dali.guannengcc.top/Article/details/gtxdlasunw.html

[M02] 读取环境变量
来源：http://dali.jlsjyb.cn/Article/details/gtetnlcxgp.html

Py:   os.environ.get("HOME")
来源：http://dali.smart0.xyz/Article/details/gtnlnaasrw.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhongyouzk.top/Article/details/gtcqvyoxel.html

JS:   process.env.HOME
来源：http://dali.jiagoushi.top/Article/details/gtgcbfgenq.html

TS:   process.env.HOME
来源：http://dali.zhoulong.xyz/Article/details/gtkprpzzku.html

Java: System.getenv("HOME")
来源：http://dali.zycfv.cn/Article/details/gtedoabjht.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.xziqi.cn/Article/details/gtywpapldi.html

Ruby: ENV["HOME"]
来源：http://dali.ehwqpu.com/Article/details/gtjtmvdtcl.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.haohaochexian.top/Article/details/gtdjjpcgyj.html

[M03] 执行外部命令
来源：http://dali.bjfxy.top/Article/details/gtwamvyovb.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yj202588.top/Article/details/gtfwolzreg.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.fengsongda.top/Article/details/gtdwlqdroc.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.cqqwz.cn/Article/details/gthegqxddw.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gtbafmlgav.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.haohaochexian.top/Article/details/gtbrxibyvq.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhoulong.xyz/Article/details/gtyunsipgk.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jyoumei.cn/Article/details/gtjfauxfyc.html

C#:   Process.Start("ls", "-l");
来源：http://dali.haohaochexian.top/Article/details/gtpauywnut.html

[M04] 获取当前工作目录
来源：http://dali.hammf.cn/Article/details/gtmwewtxen.html

Py:   os.getcwd()
来源：http://dali.nanxuanxn.top/Article/details/gthxmqmrhg.html

PHP:  getcwd();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdrvvjwag.html

JS:   process.cwd()
来源：http://dali.guannengcc.top/Article/details/gttlhindod.html

TS:   process.cwd()
来源：http://dali.jinqigfzy.top/Article/details/gthbiufjbc.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yvedp.cn/Article/details/gtakftseul.html

Go:   os.Getwd()
来源：http://dali.wangshuangyany.cn/Article/details/gtizfjtlpx.html

Ruby: Dir.pwd
来源：http://dali.daria6918.cn/Article/details/gtadngbtkt.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.chenjidiqi.icu/Article/details/gtauokvyfr.html

[M05] 设置退出码
来源：http://dali.gzhubu.top/Article/details/gtbpxjmkpg.html

Py:   sys.exit(1)
来源：http://dali.quarkkingdee.top/Article/details/gtidntvhhs.html

PHP:  exit(1);
来源：http://dali.shzxlz.cn/Article/details/gtvhjyqyjv.html

JS:   process.exit(1)
来源：http://dali.iojbl.cn/Article/details/gthlvkcpmu.html

TS:   process.exit(1)
来源：http://dali.zhoulong.xyz/Article/details/gtvomsidzi.html

Java: System.exit(1)
来源：http://dali.jqgufenzy.top/Article/details/gttpgzcmpf.html

Go:   os.Exit(1)
来源：http://dali.ydzc1.top/Article/details/gthjevlirz.html

Ruby: exit 1
来源：http://dali.shangyingyoupin.top/Article/details/gtutkiacwg.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.daria6918.cn/Article/details/gtkatjfbgi.html

[M06] 向标准错误输出
来源：http://dali.tianlin.xyz/Article/details/gtkkmtdnry.html

Py:   print("err", file=sys.stderr)
来源：http://dali.ybcxt.top/Article/details/gtwygnoigk.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jlsjyb.cn/Article/details/gtvbigpizi.html

JS:   console.error("err")
来源：http://dali.fengsongda.top/Article/details/gtfgyqftnq.html

TS:   console.error("err")
来源：http://dali.svipenyu.cn/Article/details/gtmofbbegf.html

Java: System.err.println("err")
来源：http://dali.yuxming.cn/Article/details/gtyihjpoff.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.dashuyun.cn/Article/details/gtklbdqtgx.html

Ruby: warn "err"
来源：http://dali.jyoumei.cn/Article/details/gtihwsxnjd.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.xylfe.cn/Article/details/gtguaghclz.html

[M07] 判断是否为主入口
来源：http://dali.cheryme.top/Article/details/gteflpxhvp.html

Py:   if __name__ == "__main__":
来源：http://dali.yvedp.cn/Article/details/gtuonxvflq.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.hywenlv.cn/Article/details/gtctdwihfc.html

JS:   require.main === module
来源：http://dali.9152youxi.cn/Article/details/gtjbkpvkup.html

TS:   require.main === module
来源：http://dali.yanxiufei.cn/Article/details/gttiopzozq.html

Java: public static void main(String[] args)
来源：http://dali.andypj.xyz/Article/details/gtlpoqfkee.html

Go:   func main()
来源：http://dali.fengsongda.top/Article/details/gtisyldwuj.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yongpay.top/Article/details/gtakptucml.html

C#:   static void Main(string[] args)
来源：http://dali.c1oappe.top/Article/details/gtncshhmmo.html

[M08] 获取系统与运行时信息
来源：http://dali.daxiang520.top/Article/details/gtxdykxmol.html

Py:   platform.system();  platform.python_version()
来源：http://dali.hysaishi.cn/Article/details/gtumpyzawc.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.ppjwa.cn/Article/details/gtdeplmroz.html

JS:   process.platform;  process.version
来源：http://dali.xinyue.icu/Article/details/gtshvpbpmm.html

TS:   process.platform;  process.version
来源：http://dali.zhiwuduotai.top/Article/details/gtwrmkhsuh.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.daxiang520.top/Article/details/gtttgmppwc.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.fengsongda.top/Article/details/gtkvjrxsxq.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.meibo888.top/Article/details/gtvwmliare.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.cashguo.top/Article/details/gtkeqkhsue.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtytkimksf.html

N. 数据结构与算法
来源：http://dali.hfpthk.cn/Article/details/gtpybqsgyn.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtfakjsydb.html

[N01] 二分查找（有序数组）
来源：http://dali.snrcjt.cn/Article/details/gtntglexhx.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.c1oappe.top/Article/details/gtialgfvqz.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jyoumei.cn/Article/details/gtilthjobq.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gzhubu.top/Article/details/gtfoqyjhpu.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yvedp.cn/Article/details/gttgfubabg.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.wangdashe.top/Article/details/gtevbbolwk.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jiagoushi.top/Article/details/gtdwogyccv.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.tian-w.cn/Article/details/gtxsqketxt.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.guannengcc.top/Article/details/gtpofrsxnv.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.xziqi.cn/Article/details/gtpeauchok.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhongyouzk.top/Article/details/gtdknprtcg.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.chenjidiqi.icu/Article/details/gtreknorlb.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtavnsreos.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cashguo.top/Article/details/gtaqxqkdjc.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.shzxlz.cn/Article/details/gtgfznctfg.html

Go:   slices.Sort(arr)
来源：http://dali.meibo888.top/Article/details/gtfzfanmie.html

Ruby: arr.sort
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcokvzeri.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.nwbrower.top/Article/details/gtcpltwtvh.html

[N03] 快速排序（分治示例）
来源：http://dali.9152youxi.cn/Article/details/gtefzxfkqc.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jinqigfzy.top/Article/details/gtptkofkhi.html

PHP:  // 递归实现，或用 usort
来源：http://dali.bjfxy.top/Article/details/gtzbwufioa.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrjorkiyu.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhiwuduotai.top/Article/details/gtujpiqdmy.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.daria6918.cn/Article/details/gtvyopkkjm.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfxvjrvhp.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.hnxiangtu.top/Article/details/gtvpkkfstf.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.shanyushiyangtech.top/Article/details/gtdnhzrtwh.html

[N04] 斐波那契数列
来源：http://dali.havefunace.top/Article/details/gtjtviuwhm.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.cdnleiting.top/Article/details/gtjezcqmhf.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.gotoacloud.top/Article/details/gtpycpfryc.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.chenlongwang.top/Article/details/gtcgbzfatk.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.bjfxy.top/Article/details/gtoenaveqs.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.andypj.xyz/Article/details/gtvotcezrh.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zycfv.cn/Article/details/gtkbaxnprj.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.cucudq.cn/Article/details/gtqwluxraj.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.ppjwa.cn/Article/details/gtnuugrugg.html

[N05] 最大公约数
来源：http://dali.hnxiangtu.top/Article/details/gtntjdmxhd.html

Py:   math.gcd(a, b)
来源：http://dali.jinqigfzy.top/Article/details/gtzhkryjkr.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jinqigfzy.top/Article/details/gtktdndtqj.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.daxiang520.top/Article/details/gtitmszcjn.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hammf.cn/Article/details/gttxdxyksh.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.shuidangran.top/Article/details/gtdrqzuxaa.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yvedp.cn/Article/details/gtskvszdpm.html

Ruby: a.gcd(b)
来源：http://dali.kuanghao11.cn/Article/details/gtbipnawqd.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.hongshengwenyu.top/Article/details/gtwbqtgizr.html

[N06] 判断回文字符串
来源：http://dali.tanke756.top/Article/details/gtegkjqglc.html

Py:   s == s[::-1]
来源：http://dali.haohaochexian.top/Article/details/gtemsoddmf.html

PHP:  $s === strrev($s);
来源：http://dali.yj20258888.top/Article/details/gtlsiieeoy.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jqgfzy.top/Article/details/gtkggddsog.html

TS:   s === [...s].reverse().join("")
来源：http://dali.wangshuangyany.cn/Article/details/gtdwcbtgje.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yuxming.cn/Article/details/gtbfcxjurk.html

Go:   // 双指针从两端比较
来源：http://dali.pengpengdd.cyou/Article/details/gtrcmbssjb.html

Ruby: s == s.reverse
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqqiomzgv.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.sysykeji.top/Article/details/gtyeoaeyyx.html

[N07] 两数之和（返回下标）
来源：http://dali.yvedp.cn/Article/details/gtrsxpvcqz.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.fengsongda.top/Article/details/gtohdefcxp.html


<!-- 参考信息 -->