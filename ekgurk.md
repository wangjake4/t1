代发 wailian999

Java: Duration.between(start, end).toSeconds()
来源：http://dali.svipenyu.cn/Article/details/gtcvozkdmm.html

Go:   end.Sub(start).Hours()
来源：http://dali.cucudq.cn/Article/details/gtvteolcnc.html

Ruby: end - start                 # 返回秒数
来源：http://dali.fengsongda.top/Article/details/gtfgrmudja.html

C#:   (end - start).TotalSeconds
来源：http://dali.cdnleiting.top/Article/details/gtldstvkzr.html

[J07] 比较两个日期
来源：http://dali.yanxiufei.cn/Article/details/gtaxrkycic.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.aizwys.cn/Article/details/gtymycgkff.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.gogol.net.cn/Article/details/gtitidlird.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhengqikj.top/Article/details/gtfzeplsms.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.hywenlv.cn/Article/details/gtxgpaespw.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.daria6918.cn/Article/details/gtfzpongtu.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.guannengcc.top/Article/details/gtqcwuisdz.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.shanyushiyangkeji.top/Article/details/gturcgrhxp.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhiwuduotai.top/Article/details/gtxezxjbfu.html

[J08] 提取年月日与星期
来源：http://dali.guowangkeji.top/Article/details/gtmzwraojc.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yongpay.top/Article/details/gtywxcejkr.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.gzhubu.top/Article/details/gtqcoqorfn.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.cqqwz.cn/Article/details/gtwrxjcjso.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yj202588.top/Article/details/gttdwdbdyf.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.dashuyun.cn/Article/details/gtzhobvljx.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.aibaodan.cn/Article/details/gtjubhmiru.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.ybcxt.top/Article/details/gtlwfcewce.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.sufxvd.cn/Article/details/gtbaqtipey.html

[J09] 时区处理
来源：http://dali.yvedp.cn/Article/details/gtaylbotrk.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.redwolf501.top/Article/details/gtxtvxgpnb.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jqgufenzy.top/Article/details/gtqexahell.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gzhubu.top/Article/details/gtaotuxujz.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpsybflso.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtawfwsrzu.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtftezdcax.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.cashguo.top/Article/details/gtyktzwymt.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.feifeiyinyue.top/Article/details/gtimdqedbr.html

[J10] 取今天 / 本月第一天
来源：http://dali.yj20258888.top/Article/details/gtiwcntndb.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhoulong.xyz/Article/details/gtdnoxkmps.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.sysykeji.top/Article/details/gtbwubrxkn.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.daxiang520.top/Article/details/gtepmuzkad.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.c1oappe.top/Article/details/gtqnprqtoh.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.kuanghao11.cn/Article/details/gtcswdvfni.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.birdmap.top/Article/details/gtxscyoxsa.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.shangyingyoupin.top/Article/details/gtcfhojpyx.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.wangdashe.top/Article/details/gtekzshica.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtwrkjjuga.html

K. JSON 与序列化
来源：http://dali.jinghuilouyu.cn/Article/details/gthqkcyscg.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtxklmxsfm.html

[K01] 对象转 JSON 字符串
来源：http://dali.sxryk.cn/Article/details/gtjxnzrfvz.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zdqjudy.top/Article/details/gtiptfiftn.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.hywenlv.cn/Article/details/gtmizdzgms.html

JS:   JSON.stringify(obj)
来源：http://dali.tianlin.xyz/Article/details/gtrycenhob.html

TS:   JSON.stringify(obj)
来源：http://dali.shuidangran.top/Article/details/gtruhaahmw.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.hnqzz.top/Article/details/gtcuuymqfp.html

Go:   json.Marshal(obj)
来源：http://dali.sxryk.cn/Article/details/gtxavaegmm.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.kuanghao11.cn/Article/details/gtgydcnlmd.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtppnsretk.html

[K02] JSON 字符串转对象
来源：http://dali.smart0.xyz/Article/details/gtugedwkld.html

Py:   json.loads(s)
来源：http://dali.bjfxy.top/Article/details/gtzlqkcbsj.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yangfankeji.com/Article/details/gtslajbznt.html

JS:   JSON.parse(s)
来源：http://dali.yuxming.cn/Article/details/gtbcbiuduy.html

TS:   JSON.parse(s)
来源：http://dali.xuanzx.com/Article/details/gthoznxszw.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.gotoacloud.top/Article/details/gtigegmino.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jyoumei.cn/Article/details/gtmdyqfbcu.html

Ruby: JSON.parse(s)
来源：http://dali.jqgfzy.top/Article/details/gtjtdhkafd.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtoackrlvf.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.sweek.top/Article/details/gtskeraita.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.c1oappe.top/Article/details/gttqwutlnd.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.aizwys.cn/Article/details/gtqznzxeuj.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.gaohongyu789.top/Article/details/gtpzmegfjl.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.cashguo.top/Article/details/gtqgtqhzpb.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.hnqzz.top/Article/details/gtejwgvydp.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.aizwys.cn/Article/details/gtcqeryouw.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.meibo888.top/Article/details/gtoxsuwuev.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.ehwqpu.com/Article/details/gtweahaimk.html

[K04] 读取 JSON 文件
来源：http://dali.andypj.xyz/Article/details/gtsvfvoset.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.hfpthk.cn/Article/details/gtijjawhtk.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.xuetiantiany.cn/Article/details/gtvefvfttc.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zdqjudy.top/Article/details/gtqhfipjwo.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cdnleiting.top/Article/details/gtsvtrhioz.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yj202588.top/Article/details/gtinwqfamq.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yj20258.top/Article/details/gtfbecenwq.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.nanxuanxn.top/Article/details/gtaawsvaev.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.tianlin.xyz/Article/details/gtaoknnghn.html

[K05] 深拷贝对象
来源：http://dali.cucudq.cn/Article/details/gtwhlrjyfc.html

Py:   copy.deepcopy(obj)
来源：http://dali.meibo888.top/Article/details/gtgqulnfkp.html

PHP:  unserialize(serialize($obj));
来源：http://dali.smart0.xyz/Article/details/gtptjpkbjw.html

JS:   structuredClone(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtzmdmuosj.html

TS:   structuredClone(obj)
来源：http://dali.0kj1m.cn/Article/details/gtylduhlzi.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.xuetiantiany.cn/Article/details/gtlopyvifp.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgqgbvpca.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.wangdashe.top/Article/details/gtvejgsauf.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.xuetiantiany.cn/Article/details/gtrbnqyils.html

[K06] 解析 URL 查询串
来源：http://dali.shanyushiyangtech.top/Article/details/gtyvunzrpd.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.hnxiangtu.top/Article/details/gtbojrwzqf.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.nanxuanxn.top/Article/details/gtbqsaqhon.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sweek.top/Article/details/gtxajsbxey.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cucudq.cn/Article/details/gttpzhdwns.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yuanzhike.top/Article/details/gtaixfavoo.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.pengpengdd.cyou/Article/details/gtdqlalzfc.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.c1oappe.top/Article/details/gtdtvflkls.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.hysaishi.cn/Article/details/gtgvihhgbt.html

[K07] 进制转换
来源：http://dali.jinqigufen.top/Article/details/gteuvvznnd.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.hammf.cn/Article/details/gtfcnotpov.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.fzhhl.top/Article/details/gtmfgcmggg.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.9152youxi.cn/Article/details/gthjkpingo.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.cqqwz.cn/Article/details/gtmaegnbsr.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.hywenlv.cn/Article/details/gtkctuhivh.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.hongshengwenyu.top/Article/details/gtnueafole.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.hnqzz.top/Article/details/gtpnbbjhll.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yuanzhike.top/Article/details/gtwvbtzgho.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhixingplan.top/Article/details/gtcsvusakx.html

Py:   pickle.dumps(obj)
来源：http://dali.tian-w.cn/Article/details/gtdxsqebjm.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhijiandao.cn/Article/details/gtlpsqanag.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.316326.xyz/Article/details/gtucvycatv.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.ybcxt.top/Article/details/gtllnkftox.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.pycfn.com/Article/details/gtedhwsahn.html

Go:   encoding/gob
来源：http://dali.yj20258888.top/Article/details/gttfchucau.html

Ruby: Marshal.dump(obj)
来源：http://dali.cucudq.cn/Article/details/gtlbrfaxht.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.shzxlz.cn/Article/details/gtfkfachpo.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtetfpsixy.html

L. 网络请求
来源：http://dali.daria6918.cn/Article/details/gtnaqougkh.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtoxwmjyls.html

[L01] 发送 GET 请求
来源：http://dali.meibo888.top/Article/details/gtmrepmqdb.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jyoumei.cn/Article/details/gtaovmbctg.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.iojbl.cn/Article/details/gtgvhosios.html

JS:   await fetch(url)
来源：http://dali.zhixingplan.top/Article/details/gtueimtlid.html

TS:   await fetch(url)
来源：http://dali.tanke756.top/Article/details/gtittapybf.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jinyuanbaomall.cn/Article/details/gttbzubqeg.html

Go:   resp, err := http.Get(url)
来源：http://dali.meibo888.top/Article/details/gtmuoagajo.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.gogol.net.cn/Article/details/gtqgexbdwi.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jiagoushi.top/Article/details/gtapvvvzcn.html

[L02] 发送 POST JSON
来源：http://dali.jyoumei.cn/Article/details/gtuthodskt.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.0kj1m.cn/Article/details/gtfisgfslq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.0kj1m.cn/Article/details/gtxtzmfsdk.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.haohaochexian.top/Article/details/gtcvlgmevs.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yuanzhike.top/Article/details/gtprprxfoy.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.316326.xyz/Article/details/gtkxmxgmak.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.shzxlz.cn/Article/details/gtvcjfzngl.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jinghuilouyu.cn/Article/details/gtedrjbkez.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.sysykeji.top/Article/details/gtntmayzie.html

[L03] 设置自定义请求头
来源：http://dali.feifeiyinyue.top/Article/details/gtwxehkivp.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.sweek.top/Article/details/gtkhgeiagr.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.wangdashe.top/Article/details/gtykzpgkun.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.chenlongwang.top/Article/details/gtglqkqajx.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.tanke756.top/Article/details/gtdkoetigu.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gtfnfsyfvk.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.haohaochexian.top/Article/details/gtpzdnhyht.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.cdnleiting.top/Article/details/gteeuvquzn.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.vqdsnc.cn/Article/details/gttihptjyd.html

[L04] 设置超时
来源：http://dali.zycfv.cn/Article/details/gtwxfpymba.html

Py:   requests.get(url, timeout=5)
来源：http://dali.sufxvd.cn/Article/details/gtvbubiche.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.c1oappe.top/Article/details/gtwtbbtauv.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.guowangkeji.top/Article/details/gtxduvplmp.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hongshengwenyu.top/Article/details/gtgtailwaq.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.ybcxt.top/Article/details/gtrrwurjbf.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.svipenyu.cn/Article/details/gtfaedqpig.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.cdnleiting.top/Article/details/gtlonjfgpn.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.hammf.cn/Article/details/gtogtubvmd.html

[L05] 上传文件（multipart）
来源：http://dali.jqgfzy.top/Article/details/gtghxpphqz.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.cdnleiting.top/Article/details/gtgcahxcyj.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnznhjorn.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhiwuduotai.top/Article/details/gtojtlbwkh.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.ehwqpu.com/Article/details/gtszichsdg.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.snrcjt.cn/Article/details/gtqgjbdrtd.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yj202588.top/Article/details/gtwbavwuie.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.hysaishi.cn/Article/details/gttesymlyg.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.cucudq.cn/Article/details/gtdjslhwuj.html

[L06] 解析响应为 JSON
来源：http://dali.yuxming.cn/Article/details/gtnzniohsx.html

Py:   resp.json()
来源：http://dali.yuanzhike.top/Article/details/gteacwjjmo.html

PHP:  json_decode($body, true);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjqmuknoc.html

JS:   await resp.json()
来源：http://dali.zhixingplan.top/Article/details/gtkuwngoyi.html

TS:   await resp.json()
来源：http://dali.gzhubu.top/Article/details/gtvtynrdbd.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhixingplan.top/Article/details/gtamoiqjzy.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.cheryme.top/Article/details/gtspxzciye.html

Ruby: JSON.parse(resp.body)
来源：http://dali.daxiang520.top/Article/details/gteftqoywx.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.ehwqpu.com/Article/details/gttnbgmulj.html

[L07] 处理 HTTP 状态码
来源：http://dali.shanyushiyangtech.top/Article/details/gtkdyzeijg.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.gzhubu.top/Article/details/gtqiflmqfo.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jqgufenzy.top/Article/details/gtqgzoqbyx.html

JS:   resp.ok;  resp.status
来源：http://dali.svipenyu.cn/Article/details/gtsjxpjkgu.html

TS:   resp.ok;  resp.status
来源：http://dali.jinqigufen.top/Article/details/gttkmsykhx.html

Java: resp.statusCode()
来源：http://dali.yonumen.top/Article/details/gtecqisgxd.html

Go:   resp.StatusCode
来源：http://dali.sysykeji.top/Article/details/gtgbgvmqto.html

Ruby: resp.code.to_i
来源：http://dali.jlsjyb.cn/Article/details/gtxiikflpt.html

C#:   (int)resp.StatusCode
来源：http://dali.hongshengwenyu.top/Article/details/gttpzjnuvq.html

[L08] 并发请求多个地址
来源：http://dali.xuanzx.com/Article/details/gtavoevljj.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhengqikj.top/Article/details/gtesidmfpk.html

PHP:  curl_multi_init() 系列
来源：http://dali.tanke756.top/Article/details/gtsafppnwc.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hammf.cn/Article/details/gtplukbmkh.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shanyushiyangtech.top/Article/details/gtpdndgate.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.nwbrower.top/Article/details/gttpldhphl.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.xziqi.cn/Article/details/gtwpcditpe.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.dianchejie.cn/Article/details/gtzremzdbg.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.pengpengdd.cyou/Article/details/gtostpmgjb.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtttwrhjza.html

M. 命令行 / 进程 / 环境
来源：http://dali.daxiang520.top/Article/details/gtuiqnnoyl.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtsrghxsjd.html

[M01] 读取命令行参数
来源：http://dali.vqdsnc.cn/Article/details/gttomcbxbp.html

Py:   sys.argv[1:]
来源：http://dali.gogol.net.cn/Article/details/gtamloldxn.html

PHP:  $argv;  $argc;
来源：http://dali.9152youxi.cn/Article/details/gtketqsoxt.html

JS:   process.argv.slice(2)
来源：http://dali.nanxuanxn.top/Article/details/gtrodobmbq.html

TS:   process.argv.slice(2)
来源：http://dali.iojbl.cn/Article/details/gttbgeeaaf.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gtnpsldtmq.html

Go:   os.Args[1:]
来源：http://dali.haohaochexian.top/Article/details/gtkktoheod.html

Ruby: ARGV
来源：http://dali.yongpay.top/Article/details/gtqydnaiij.html

C#:   args 数组（Main 方法参数）
来源：http://dali.pengpengdd.cyou/Article/details/gtltvfecyj.html

[M02] 读取环境变量
来源：http://dali.yj20258.top/Article/details/gtglmrghya.html

Py:   os.environ.get("HOME")
来源：http://dali.wangdashe.top/Article/details/gtswwnujux.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.guannengcc.top/Article/details/gtamlnyyih.html

JS:   process.env.HOME
来源：http://dali.xuanzx.com/Article/details/gtrjmndcwo.html

TS:   process.env.HOME
来源：http://dali.dashuyun.cn/Article/details/gtmzqeklsd.html

Java: System.getenv("HOME")
来源：http://dali.xylfe.cn/Article/details/gtvssanwyy.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.aizwys.cn/Article/details/gtsfyujzne.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gtyqftgyjm.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.snrcjt.cn/Article/details/gtzjampptv.html

[M03] 执行外部命令
来源：http://dali.havefunace.top/Article/details/gtciwfukqv.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.kuanghao11.cn/Article/details/gtisjlhfxf.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.nwbrower.top/Article/details/gtgblxsbei.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.redwolf501.top/Article/details/gtcdwleroh.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyeqgvjvu.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.ppjwa.cn/Article/details/gtfogujxjp.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.ppjwa.cn/Article/details/gtgfijiiam.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.kuanghao11.cn/Article/details/gtcbztqucp.html

C#:   Process.Start("ls", "-l");
来源：http://dali.ywan-chungtsiang.top/Article/details/gthtgstxtk.html

[M04] 获取当前工作目录
来源：http://dali.vqdsnc.cn/Article/details/gtrbejtalo.html

Py:   os.getcwd()
来源：http://dali.xylfe.cn/Article/details/gtsfmyzvaw.html

PHP:  getcwd();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtshppggra.html

JS:   process.cwd()
来源：http://dali.zhengqikj.top/Article/details/gtqgszekor.html

TS:   process.cwd()
来源：http://dali.aizwys.cn/Article/details/gtvvnkecjp.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhongyouzk.top/Article/details/gttijkpnop.html

Go:   os.Getwd()
来源：http://dali.hnqzz.top/Article/details/gtgpwmkcmb.html

Ruby: Dir.pwd
来源：http://dali.yangfankeji.com/Article/details/gtfkvnguas.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jyoumei.cn/Article/details/gtslehxrzn.html

[M05] 设置退出码
来源：http://dali.0kj1m.cn/Article/details/gtkkdtfveg.html

Py:   sys.exit(1)
来源：http://dali.xuanzx.com/Article/details/gtqbtnuuhw.html

PHP:  exit(1);
来源：http://dali.yueranfly.top/Article/details/gtdsdjhlwl.html

JS:   process.exit(1)
来源：http://dali.shangyingyoupin.top/Article/details/gtkdrxrzmv.html

TS:   process.exit(1)
来源：http://dali.gaohongyu789.top/Article/details/gtofujokuw.html

Java: System.exit(1)
来源：http://dali.tanke756.top/Article/details/gteacggrjz.html

Go:   os.Exit(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtanronfxv.html

Ruby: exit 1
来源：http://dali.quarkkingdee.top/Article/details/gtvitfkdam.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.chenzaomai.com/Article/details/gtoedntfak.html

[M06] 向标准错误输出
来源：http://dali.jinqigufen.top/Article/details/gtwtdqtcxn.html

Py:   print("err", file=sys.stderr)
来源：http://dali.mhx1999.top/Article/details/gtozaqkiyc.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.birdmap.top/Article/details/gtutpngboq.html

JS:   console.error("err")
来源：http://dali.jqgfzy.top/Article/details/gtcidmkwtc.html

TS:   console.error("err")
来源：http://dali.yonumen.top/Article/details/gtohojqilr.html

Java: System.err.println("err")
来源：http://dali.zhoulong.xyz/Article/details/gtivbdqnos.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.cucudq.cn/Article/details/gtblplaade.html

Ruby: warn "err"
来源：http://dali.kuanghao11.cn/Article/details/gtfmrfxicz.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.gaohongyu789.top/Article/details/gtpdnzegft.html

[M07] 判断是否为主入口
来源：http://dali.meibo888.top/Article/details/gtrcjacaxn.html

Py:   if __name__ == "__main__":
来源：http://dali.jqgfzy.top/Article/details/gtdkfvudba.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhoulong.xyz/Article/details/gtzkkouujd.html

JS:   require.main === module
来源：http://dali.chenzaomai.com/Article/details/gtjuohknjo.html

TS:   require.main === module
来源：http://dali.ydzc1.top/Article/details/gtefdnrgyo.html

Java: public static void main(String[] args)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpjbjzdzm.html

Go:   func main()
来源：http://dali.yj20258888.top/Article/details/gtavsqefca.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.gotoacloud.top/Article/details/gtyklmgbsm.html

C#:   static void Main(string[] args)
来源：http://dali.jinqigufen.top/Article/details/gtawkjwekn.html

[M08] 获取系统与运行时信息
来源：http://dali.yangfankeji.com/Article/details/gtgrnvtlbz.html

Py:   platform.system();  platform.python_version()
来源：http://dali.pengpengdd.cyou/Article/details/gtlfurdzip.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yueranfly.top/Article/details/gtlywdqfcs.html

JS:   process.platform;  process.version
来源：http://dali.haohaochexian.top/Article/details/gtztshmsgs.html

TS:   process.platform;  process.version
来源：http://dali.shuidangran.top/Article/details/gtsaeadrok.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.svipenyu.cn/Article/details/gtratmlmak.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhengqikj.top/Article/details/gtwtvnyuzy.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.fzhhl.top/Article/details/gthkvpvsqy.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.sysykeji.top/Article/details/gtwsesnfuf.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtcleipzjp.html

N. 数据结构与算法
来源：http://dali.hysaishi.cn/Article/details/gtojjwmepq.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtbecsfvtg.html

[N01] 二分查找（有序数组）
来源：http://dali.tianlin.xyz/Article/details/gtrvlsnlil.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yj20258.top/Article/details/gtxssmfusg.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.sufxvd.cn/Article/details/gtoclrxawq.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.snrcjt.cn/Article/details/gthknefleo.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.tanke756.top/Article/details/gtxefqzqjf.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.xziqi.cn/Article/details/gtcqsjdghx.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yuanzhike.top/Article/details/gtpqpjvsvk.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.daxiang520.top/Article/details/gtvvlmdjir.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.guowangkeji.top/Article/details/gteoupoflr.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhengqikj.top/Article/details/gtalcnwdsa.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xziqi.cn/Article/details/gtirczhyee.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.shanyushiyangtech.top/Article/details/gtapsbucwx.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.haohaochexian.top/Article/details/gtlvjzknip.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ybcxt.top/Article/details/gthptouvdh.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.tanke756.top/Article/details/gtcopocweq.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gtwjncoqjv.html

Ruby: arr.sort
来源：http://dali.cdnleiting.top/Article/details/gthiyrfuel.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.xuetiantiany.cn/Article/details/gtqszasyoe.html

[N03] 快速排序（分治示例）
来源：http://dali.yongpay.top/Article/details/gtcluqvawu.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.cashguo.top/Article/details/gtgeiuwfwl.html

PHP:  // 递归实现，或用 usort
来源：http://dali.xinyue.icu/Article/details/gtqydqivzh.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.sysykeji.top/Article/details/gtrfhkahbb.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.vqdsnc.cn/Article/details/gtnmtcjdkp.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhoulong.xyz/Article/details/gtbaxhpebj.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.bjfxy.top/Article/details/gtalgwfqrh.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.tian-w.cn/Article/details/gtypfepeni.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.haohaochexian.top/Article/details/gtpgnokvgq.html

[N04] 斐波那契数列
来源：http://dali.0kj1m.cn/Article/details/gtyrmnejyj.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.hysaishi.cn/Article/details/gthzpyngvi.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.hammf.cn/Article/details/gtruswyxno.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.mhx1999.top/Article/details/gtqwvamgta.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yuanzhike.top/Article/details/gtqvegecfh.html


<!-- 参考信息 -->