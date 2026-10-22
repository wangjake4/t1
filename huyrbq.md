代发 wailian999

[J07] 比较两个日期
来源：http://dali.9152youxi.cn/Article/details/gtgfhdpeiu.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhongyouzk.top/Article/details/gtzsloiyiq.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yj20258.top/Article/details/gtsmzgcxrh.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.fengsongda.top/Article/details/gtzsmrwiya.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yj202588.top/Article/details/gtqrrxpsrg.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.xinyue.icu/Article/details/gtawnwcfog.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yonumen.top/Article/details/gtifesmout.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.pengpengdd.cyou/Article/details/gtlwxdwgpx.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jinyuanbaomall.cn/Article/details/gtifgsctqc.html

[J08] 提取年月日与星期
来源：http://dali.sxryk.cn/Article/details/gtienhpooj.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.hnqzz.top/Article/details/gtckekfprm.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jinghuilouyu.cn/Article/details/gtyrlakxan.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.cqqwz.cn/Article/details/gtpmbhjxry.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.nanxuanxn.top/Article/details/gtoaqykpxj.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.xziqi.cn/Article/details/gthtlatpce.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yueranfly.top/Article/details/gtfvqxummx.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.wangshuangyany.cn/Article/details/gtfhsyqman.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yvedp.cn/Article/details/gtixytojvs.html

[J09] 时区处理
来源：http://dali.vqdsnc.cn/Article/details/gtgecdlqds.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.wangdashe.top/Article/details/gtkzkfcuql.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.9152youxi.cn/Article/details/gtbthigukj.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.wangshuangyany.cn/Article/details/gtsqvfghrj.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gogol.net.cn/Article/details/gtyrhpzekl.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.chenlongwang.top/Article/details/gtliqhdgka.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.gogol.net.cn/Article/details/gtfuolqaxz.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zdqjudy.top/Article/details/gtkyxzgeyu.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.hywenlv.cn/Article/details/gttvuqjwag.html

[J10] 取今天 / 本月第一天
来源：http://dali.shanyushiyangkeji.top/Article/details/gtowqppnkj.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.svipenyu.cn/Article/details/gtckiueqgq.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhoulong.xyz/Article/details/gtxngdouhd.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.cucudq.cn/Article/details/gtioxoksxo.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.vqdsnc.cn/Article/details/gteiywgwmw.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yj20258.top/Article/details/gtauffxzgj.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.0kj1m.cn/Article/details/gtgbzhnlij.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhaomingkeji.xyz/Article/details/gthcnupxve.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.hongshengwenyu.top/Article/details/gtagnyrxdm.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtmductlec.html

K. JSON 与序列化
来源：http://dali.gzhubu.top/Article/details/gtqdqknoop.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtqeywudmq.html

[K01] 对象转 JSON 字符串
来源：http://dali.chenjidiqi.icu/Article/details/gtrjuiczle.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhoulong.xyz/Article/details/gtbhcvryde.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.chenlongwang.top/Article/details/gtagemiakg.html

JS:   JSON.stringify(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzdwnywfh.html

TS:   JSON.stringify(obj)
来源：http://dali.hysaishi.cn/Article/details/gtwpasehza.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jinghuilouyu.cn/Article/details/gtggyhrfnf.html

Go:   json.Marshal(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtrvgwwddz.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yanxiufei.cn/Article/details/gtadzsybdg.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gtuzoasfig.html

[K02] JSON 字符串转对象
来源：http://dali.zhaomingkeji.xyz/Article/details/gtabctmsha.html

Py:   json.loads(s)
来源：http://dali.tianlin.xyz/Article/details/gtzmajfsaf.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzfwwslbx.html

JS:   JSON.parse(s)
来源：http://dali.jianghu66.top/Article/details/gtdyqfrpnw.html

TS:   JSON.parse(s)
来源：http://dali.hammf.cn/Article/details/gtohagbcvy.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.xuanzx.com/Article/details/gtcpznlvqq.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.gzhubu.top/Article/details/gttdynduwt.html

Ruby: JSON.parse(s)
来源：http://dali.aibaodan.cn/Article/details/gtxnptkyvc.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.chenlongwang.top/Article/details/gtlnlkrhtb.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.sysykeji.top/Article/details/gtzrrfczgo.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yueranfly.top/Article/details/gtxuzubcut.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.gotoacloud.top/Article/details/gtudjtuflj.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.feifeiyinyue.top/Article/details/gtwvrsovut.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.pycfn.com/Article/details/gtjsnycwje.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.pycfn.com/Article/details/gtyldlwcfz.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.wangdashe.top/Article/details/gtaamtbfcn.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.hywenlv.cn/Article/details/gtssklmxma.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.cqqwz.cn/Article/details/gtmumczjim.html

[K04] 读取 JSON 文件
来源：http://dali.daxiang520.top/Article/details/gtobtejial.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.shzxlz.cn/Article/details/gtzeopefdr.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.kuanghao11.cn/Article/details/gtrybtdkjp.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.daria6918.cn/Article/details/gtirklhgsd.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.birdmap.top/Article/details/gtvvmqcyze.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.mhx1999.top/Article/details/gtyrlmyguf.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yangfankeji.com/Article/details/gtlirtgugb.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.chenlongwang.top/Article/details/gtrjfjpsbw.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.guowangkeji.top/Article/details/gtlqvzgstn.html

[K05] 深拷贝对象
来源：http://dali.jinqigufen.top/Article/details/gtyqrfadzc.html

Py:   copy.deepcopy(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtstvsqyca.html

PHP:  unserialize(serialize($obj));
来源：http://dali.feifeiyinyue.top/Article/details/gtmqmeeiax.html

JS:   structuredClone(obj)
来源：http://dali.tianlin.xyz/Article/details/gtwabagwgf.html

TS:   structuredClone(obj)
来源：http://dali.zhengqikj.top/Article/details/gtydodzpuj.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.xuanzx.com/Article/details/gtsrodjcii.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zdqjudy.top/Article/details/gtraojvadn.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.cucudq.cn/Article/details/gtiukbbnue.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.sweek.top/Article/details/gtmahsvziy.html

[K06] 解析 URL 查询串
来源：http://dali.tianlin.xyz/Article/details/gtahmkumtm.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.xuetiantiany.cn/Article/details/gtrctggjzk.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yanxiufei.cn/Article/details/gtknbcolud.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xylfe.cn/Article/details/gtdlxkcdtl.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.bjfxy.top/Article/details/gtqnxpuhax.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.aizwys.cn/Article/details/gtibhnmilb.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.shuidangran.top/Article/details/gtqekjixsq.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.gaohongyu789.top/Article/details/gtzgypphvm.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.hysaishi.cn/Article/details/gtfvgdnlmy.html

[K07] 进制转换
来源：http://dali.aibaodan.cn/Article/details/gtkvojvyiw.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.dianchejie.cn/Article/details/gtoudgjdsa.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.dashuyun.cn/Article/details/gtpkmjkhdj.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhongyouzk.top/Article/details/gtdfcavzjo.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.xinyue.icu/Article/details/gtchisxhub.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jinghuilouyu.cn/Article/details/gtdodmmpua.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhixingplan.top/Article/details/gtzcxavjiw.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.sufxvd.cn/Article/details/gtryjyjnrl.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.chenlongwang.top/Article/details/gtclbzmpbm.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.xylfe.cn/Article/details/gtspgvlmws.html

Py:   pickle.dumps(obj)
来源：http://dali.yongpay.top/Article/details/gtyopknjtt.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.tianlin.xyz/Article/details/gtsjpkpokd.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.meibo888.top/Article/details/gtgjyhieoa.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.haohaochexian.top/Article/details/gtqlzqfivr.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yj20258888.top/Article/details/gtreqvzzvc.html

Go:   encoding/gob
来源：http://dali.ehwqpu.com/Article/details/gtnvxpareq.html

Ruby: Marshal.dump(obj)
来源：http://dali.hnxiangtu.top/Article/details/gtnlueanie.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yuxming.cn/Article/details/gtmsigvtvv.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtbcxcreid.html

L. 网络请求
来源：http://dali.chenjidiqi.icu/Article/details/gtxwlfqmcg.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtqqoexgls.html

[L01] 发送 GET 请求
来源：http://dali.gaohongyu789.top/Article/details/gtwzpjejya.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yanxiufei.cn/Article/details/gtfmxcmjhv.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.dianchejie.cn/Article/details/gtswohmuor.html

JS:   await fetch(url)
来源：http://dali.ivvv.top/Article/details/gtwrdydccs.html

TS:   await fetch(url)
来源：http://dali.gaohongyu789.top/Article/details/gtogihuhen.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.dashuyun.cn/Article/details/gtohmdzjij.html

Go:   resp, err := http.Get(url)
来源：http://dali.cqqwz.cn/Article/details/gtczfdbhrr.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jyoumei.cn/Article/details/gtvgxwsnzg.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.sysykeji.top/Article/details/gtbpchalzt.html

[L02] 发送 POST JSON
来源：http://dali.zhengqikj.top/Article/details/gtoqxpdtuu.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.pengpengdd.cyou/Article/details/gtzqfvrddu.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.aizwys.cn/Article/details/gtxeyeccxr.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.vqdsnc.cn/Article/details/gttypurari.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shangyingyoupin.top/Article/details/gtplliemqj.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.sysykeji.top/Article/details/gtpfqngciv.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.ybcxt.top/Article/details/gtkowpmgtr.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.sweek.top/Article/details/gtmieslhzs.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.sysykeji.top/Article/details/gtmpgpvfzo.html

[L03] 设置自定义请求头
来源：http://dali.havefunace.top/Article/details/gtifdcigvc.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhengqikj.top/Article/details/gtlnfwiiap.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.hysaishi.cn/Article/details/gtwdcyhjlu.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.chenzaomai.com/Article/details/gtzcydmlwx.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yongpay.top/Article/details/gtbkqmxbkg.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yj20258888.top/Article/details/gtmghbvoza.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhixingplan.top/Article/details/gtcixozmlq.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.aizwys.cn/Article/details/gtpmjrlfzq.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.cheryme.top/Article/details/gtltiuxpaj.html

[L04] 设置超时
来源：http://dali.yuxming.cn/Article/details/gtpngvaarp.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtouvykvsm.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.haohaochexian.top/Article/details/gtsefqhabu.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yj202588.top/Article/details/gtxnbpxdms.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.quarkkingdee.top/Article/details/gtqfrrjgni.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.xuetiantiany.cn/Article/details/gtrivjkmre.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.ybcxt.top/Article/details/gtkhhksull.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.chenjidiqi.icu/Article/details/gtkberswpj.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yuxming.cn/Article/details/gtdkcwojis.html

[L05] 上传文件（multipart）
来源：http://dali.xziqi.cn/Article/details/gtingfjfxk.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hfpthk.cn/Article/details/gtrpmxbrjr.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.bjfxy.top/Article/details/gtasbkietx.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.chenlongwang.top/Article/details/gtzyobsnuz.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.nwbrower.top/Article/details/gtywibwvrn.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.birdmap.top/Article/details/gtxhvarngs.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.tianlin.xyz/Article/details/gtduvthtxv.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.c1oappe.top/Article/details/gtmglmvxrw.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gtflnrtkbc.html

[L06] 解析响应为 JSON
来源：http://dali.zdqjudy.top/Article/details/gtpaezovwi.html

Py:   resp.json()
来源：http://dali.hnqzz.top/Article/details/gtgvjwgyur.html

PHP:  json_decode($body, true);
来源：http://dali.jiagoushi.top/Article/details/gtcruiayqe.html

JS:   await resp.json()
来源：http://dali.zhengqikj.top/Article/details/gtcdauvnsq.html

TS:   await resp.json()
来源：http://dali.nanxinkj.top/Article/details/gtyoqigipl.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.feifeiyinyue.top/Article/details/gtyswgxvjh.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.guowangkeji.top/Article/details/gtjfgwlbyr.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwfhrbmqi.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.kuanghao11.cn/Article/details/gthcgpbcoo.html

[L07] 处理 HTTP 状态码
来源：http://dali.chenzaomai.com/Article/details/gtvozjbjkh.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yj20258888.top/Article/details/gttygresck.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhoulong.xyz/Article/details/gtdxhpkina.html

JS:   resp.ok;  resp.status
来源：http://dali.pengpengdd.cyou/Article/details/gtxthjbcot.html

TS:   resp.ok;  resp.status
来源：http://dali.gogol.net.cn/Article/details/gtcadastvt.html

Java: resp.statusCode()
来源：http://dali.xinyue.icu/Article/details/gttzoiwrhm.html

Go:   resp.StatusCode
来源：http://dali.daria6918.cn/Article/details/gttvibaxjg.html

Ruby: resp.code.to_i
来源：http://dali.hfpthk.cn/Article/details/gtsnqkbslg.html

C#:   (int)resp.StatusCode
来源：http://dali.chenlongwang.top/Article/details/gtekykydoy.html

[L08] 并发请求多个地址
来源：http://dali.sysykeji.top/Article/details/gtnqgfjadz.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.feifeiyinyue.top/Article/details/gtozpuoywq.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhongyouzk.top/Article/details/gtzoroobmy.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sufxvd.cn/Article/details/gtkcpgvibk.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zdqjudy.top/Article/details/gtfzatntpu.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.xuanzx.com/Article/details/gttjcmtmlr.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.sufxvd.cn/Article/details/gtduwflfir.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.iojbl.cn/Article/details/gtlgihvwkc.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.tianlin.xyz/Article/details/gtchkgdtzj.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtdsgvjcpi.html

M. 命令行 / 进程 / 环境
来源：http://dali.smart0.xyz/Article/details/gtegfowxxr.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtddesovly.html

[M01] 读取命令行参数
来源：http://dali.yanxiufei.cn/Article/details/gtppstrwdo.html

Py:   sys.argv[1:]
来源：http://dali.hfpthk.cn/Article/details/gthclhkfsn.html

PHP:  $argv;  $argc;
来源：http://dali.sysykeji.top/Article/details/gtcizzpyig.html

JS:   process.argv.slice(2)
来源：http://dali.shanyushiyangtech.top/Article/details/gticwilogu.html

TS:   process.argv.slice(2)
来源：http://dali.gotoacloud.top/Article/details/gtvsfkawlw.html

Java: args 数组（main 方法参数）
来源：http://dali.jinghuilouyu.cn/Article/details/gthqaufcur.html

Go:   os.Args[1:]
来源：http://dali.jqgufenzy.top/Article/details/gtacszwppi.html

Ruby: ARGV
来源：http://dali.yongpay.top/Article/details/gtimkrdtso.html

C#:   args 数组（Main 方法参数）
来源：http://dali.wangshuangyany.cn/Article/details/gtkfdeuvie.html

[M02] 读取环境变量
来源：http://dali.yj20258.top/Article/details/gtekvfnjlc.html

Py:   os.environ.get("HOME")
来源：http://dali.ivvv.top/Article/details/gtrblpcksx.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.smart0.xyz/Article/details/gtltreuvom.html

JS:   process.env.HOME
来源：http://dali.xylfe.cn/Article/details/gtcyacezaf.html

TS:   process.env.HOME
来源：http://dali.gotoacloud.top/Article/details/gtrcumugob.html

Java: System.getenv("HOME")
来源：http://dali.cucudq.cn/Article/details/gtpqxnpyrn.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yuanzhike.top/Article/details/gtptwsrool.html

Ruby: ENV["HOME"]
来源：http://dali.sysykeji.top/Article/details/gtbnopgsqs.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.bjfxy.top/Article/details/gtardszzxs.html

[M03] 执行外部命令
来源：http://dali.zhixingplan.top/Article/details/gtahsdmfin.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.shzxlz.cn/Article/details/gtzsiyplaq.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yanxiufei.cn/Article/details/gtebpbkwzj.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.0kj1m.cn/Article/details/gttaxysinn.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.cucudq.cn/Article/details/gtydlwozjy.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.shuidangran.top/Article/details/gtfebwarzi.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.gotoacloud.top/Article/details/gtqliaqwiq.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.hysaishi.cn/Article/details/gtjwsbgmxb.html

C#:   Process.Start("ls", "-l");
来源：http://dali.fengsongda.top/Article/details/gtoszehbcn.html

[M04] 获取当前工作目录
来源：http://dali.hnxiangtu.top/Article/details/gtlgbyytqm.html

Py:   os.getcwd()
来源：http://dali.yvedp.cn/Article/details/gtzqvfyoiq.html

PHP:  getcwd();
来源：http://dali.feifeiyinyue.top/Article/details/gtuxsppeju.html

JS:   process.cwd()
来源：http://dali.jlsjyb.cn/Article/details/gtlokvujdp.html

TS:   process.cwd()
来源：http://dali.sysykeji.top/Article/details/gtgargerbq.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.sufxvd.cn/Article/details/gtzwszrkxz.html

Go:   os.Getwd()
来源：http://dali.daxiang520.top/Article/details/gtblgtgmap.html

Ruby: Dir.pwd
来源：http://dali.hnqzz.top/Article/details/gttfrrtoak.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhengqikj.top/Article/details/gtxmxnspwg.html

[M05] 设置退出码
来源：http://dali.wangdashe.top/Article/details/gtnwozocwj.html

Py:   sys.exit(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtvntawrlh.html

PHP:  exit(1);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxktmxhqb.html

JS:   process.exit(1)
来源：http://dali.nanxuanxn.top/Article/details/gtdqnaihhc.html

TS:   process.exit(1)
来源：http://dali.iojbl.cn/Article/details/gttcbfdoro.html

Java: System.exit(1)
来源：http://dali.316326.xyz/Article/details/gtjonqsyeo.html

Go:   os.Exit(1)
来源：http://dali.nanxuanxn.top/Article/details/gtwuxndqjh.html

Ruby: exit 1
来源：http://dali.zhixingplan.top/Article/details/gtndoxqkyt.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhiwuduotai.top/Article/details/gtuiwfjydk.html

[M06] 向标准错误输出
来源：http://dali.yongpay.top/Article/details/gtfttwhxwk.html

Py:   print("err", file=sys.stderr)
来源：http://dali.vqdsnc.cn/Article/details/gtvtvvzucv.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.pengpengdd.cyou/Article/details/gtwhwhdejw.html

JS:   console.error("err")
来源：http://dali.jinghuilouyu.cn/Article/details/gtgzjrxone.html

TS:   console.error("err")
来源：http://dali.gzhubu.top/Article/details/gtifwnhmxm.html

Java: System.err.println("err")
来源：http://dali.zdqjudy.top/Article/details/gtvrzgzqjg.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hywenlv.cn/Article/details/gtixsgqroh.html

Ruby: warn "err"
来源：http://dali.birdmap.top/Article/details/gtlfuceueb.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.pengpengdd.cyou/Article/details/gtpjrlsuxa.html

[M07] 判断是否为主入口
来源：http://dali.jqgfzy.top/Article/details/gtfuioejhz.html

Py:   if __name__ == "__main__":
来源：http://dali.9152youxi.cn/Article/details/gtvvcrzbij.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yongpay.top/Article/details/gtvcnkdxfl.html

JS:   require.main === module
来源：http://dali.hammf.cn/Article/details/gtfwnjirdh.html

TS:   require.main === module
来源：http://dali.andypj.xyz/Article/details/gtwnzblnuz.html

Java: public static void main(String[] args)
来源：http://dali.zdqjudy.top/Article/details/gtokeftymx.html

Go:   func main()
来源：http://dali.yongpay.top/Article/details/gtuxmgzbhk.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.xylfe.cn/Article/details/gtscgtvtuv.html

C#:   static void Main(string[] args)
来源：http://dali.iojbl.cn/Article/details/gtgpatpgku.html

[M08] 获取系统与运行时信息
来源：http://dali.sxryk.cn/Article/details/gthdatgsvv.html

Py:   platform.system();  platform.python_version()
来源：http://dali.sweek.top/Article/details/gtgyzskgbk.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zdqjudy.top/Article/details/gtbxxmllva.html

JS:   process.platform;  process.version
来源：http://dali.sxryk.cn/Article/details/gtxsryrkfz.html

TS:   process.platform;  process.version
来源：http://dali.cashguo.top/Article/details/gtkjdqhotl.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hammf.cn/Article/details/gtsgdjbzao.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jlsjyb.cn/Article/details/gtyixuqzzj.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtewhirjbu.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.xuanzx.com/Article/details/gtebsziwgy.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtoogwtgnm.html

N. 数据结构与算法
来源：http://dali.ehwqpu.com/Article/details/gtkdfxxxka.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtlhxwtocu.html

[N01] 二分查找（有序数组）
来源：http://dali.jinqigfzy.top/Article/details/gtkywwygdx.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtorebemmp.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.hongshengwenyu.top/Article/details/gtbhsuaxio.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfmdvpurz.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.c1oappe.top/Article/details/gtdzmighdz.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhengqikj.top/Article/details/gtanvidzpg.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.xylfe.cn/Article/details/gtutbvfvsz.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.daria6918.cn/Article/details/gtzxxqiaiz.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yonumen.top/Article/details/gttsluysfc.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yongpay.top/Article/details/gtpjadgtqc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.chenzaomai.com/Article/details/gtgwrjvsou.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yangfankeji.com/Article/details/gtlhfseqnz.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yuanzhike.top/Article/details/gtskcsocir.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cucudq.cn/Article/details/gtjkjqszqz.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yj20258.top/Article/details/gtbpthrosu.html

Go:   slices.Sort(arr)
来源：http://dali.yangfankeji.com/Article/details/gtrbblwamn.html

Ruby: arr.sort
来源：http://dali.wangdashe.top/Article/details/gtbianbunh.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jinqigfzy.top/Article/details/gtlyfxjcjx.html

[N03] 快速排序（分治示例）
来源：http://dali.yonumen.top/Article/details/gtingxwbkr.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jiagoushi.top/Article/details/gtjrlxjrnd.html

PHP:  // 递归实现，或用 usort
来源：http://dali.gogol.net.cn/Article/details/gtxbutrrgg.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yj20258.top/Article/details/gteqzptuil.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hnxiangtu.top/Article/details/gtklemdyrm.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yonumen.top/Article/details/gtikakslpr.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.hnxiangtu.top/Article/details/gtxsenlfbj.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.feifeiyinyue.top/Article/details/gteakqxyiz.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.cqqwz.cn/Article/details/gtfryxoihd.html

[N04] 斐波那契数列
来源：http://dali.redwolf501.top/Article/details/gtnkbbdrwc.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.daria6918.cn/Article/details/gttsrduzsj.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrcdueeax.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.nanxuanxn.top/Article/details/gtdsoaekka.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.chenjidiqi.icu/Article/details/gttrhuhgbg.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jinqigufen.top/Article/details/gtkjxowyjj.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.aizwys.cn/Article/details/gtrdjhjjck.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.ybcxt.top/Article/details/gtrsabgrul.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhiwuduotai.top/Article/details/gtsuvllrbp.html


<!-- 参考信息 -->