代发 wailian999

Py:   (end - start).total_seconds()
来源：http://dali.zhengqikj.top/Article/details/gtiffqvzfd.html

PHP:  $end->diff($start)->days;
来源：http://dali.svipenyu.cn/Article/details/gtrcvfcpig.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.cdnleiting.top/Article/details/gtpzudolsd.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.ppjwa.cn/Article/details/gtvkdnhjbd.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yonumen.top/Article/details/gtduleadoc.html

Go:   end.Sub(start).Hours()
来源：http://dali.cucudq.cn/Article/details/gtkpvbkisg.html

Ruby: end - start                 # 返回秒数
来源：http://dali.ehwqpu.com/Article/details/gtxxrsxgax.html

C#:   (end - start).TotalSeconds
来源：http://dali.ppjwa.cn/Article/details/gtznsfmzbt.html

[J07] 比较两个日期
来源：http://dali.dashuyun.cn/Article/details/gtixduaabj.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.316326.xyz/Article/details/gtkxncibgp.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.fengsongda.top/Article/details/gtiinxmwbz.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.sweek.top/Article/details/gtpnpiaksf.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.316326.xyz/Article/details/gtvuparvol.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.vqdsnc.cn/Article/details/gtaiskihdx.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhijiandao.cn/Article/details/gtwkrffkrd.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhengqikj.top/Article/details/gtesgjiwqa.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.ywan-chungtsiang.top/Article/details/gtacwtdvqb.html

[J08] 提取年月日与星期
来源：http://dali.yuxming.cn/Article/details/gtentdkgxo.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqxkbsjnh.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.chenjidiqi.icu/Article/details/gtxwnafsnk.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.smart0.xyz/Article/details/gtkiwzdpsb.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.xuanzx.com/Article/details/gtytoevocf.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhoulong.xyz/Article/details/gtpxmyxdtb.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hongshengwenyu.top/Article/details/gtvubbxngt.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.hywenlv.cn/Article/details/gtkoyqfthi.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.birdmap.top/Article/details/gtzjlhkqgj.html

[J09] 时区处理
来源：http://dali.xuetiantiany.cn/Article/details/gtcocoupzb.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.wangdashe.top/Article/details/gtgtoqndqc.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.0kj1m.cn/Article/details/gtniovlwuc.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.aibaodan.cn/Article/details/gtsbnozebt.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.nwbrower.top/Article/details/gtdbrsvjoz.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.fzhhl.top/Article/details/gtsyunqjqm.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhoulong.xyz/Article/details/gtfaqbyoqn.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhengqikj.top/Article/details/gttxgzaiei.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.ppjwa.cn/Article/details/gtgssowrje.html

[J10] 取今天 / 本月第一天
来源：http://dali.gotoacloud.top/Article/details/gtmmcaquzm.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtfjfbqfww.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yongpay.top/Article/details/gtwojzwdrl.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.nwbrower.top/Article/details/gtupmbwwoq.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.daxiang520.top/Article/details/gtiqzuuugw.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.xuanzx.com/Article/details/gtgfoyvcci.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.kuanghao11.cn/Article/details/gthnjoxzit.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.bjfxy.top/Article/details/gtzjwveysr.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jqgufenzy.top/Article/details/gtcohmkmod.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtezlwxptn.html

K. JSON 与序列化
来源：http://dali.cqqwz.cn/Article/details/gtgaxuejxw.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtwzlknzqp.html

[K01] 对象转 JSON 字符串
来源：http://dali.quarkkingdee.top/Article/details/gtvaaseohp.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.wangshuangyany.cn/Article/details/gtidqosjxy.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.0kj1m.cn/Article/details/gtleuuyhxc.html

JS:   JSON.stringify(obj)
来源：http://dali.cheryme.top/Article/details/gtcaqznmmb.html

TS:   JSON.stringify(obj)
来源：http://dali.vqdsnc.cn/Article/details/gtyjwojiby.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jinqigfzy.top/Article/details/gtnishferd.html

Go:   json.Marshal(obj)
来源：http://dali.316326.xyz/Article/details/gtrfefdmmz.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.meibo888.top/Article/details/gtsuewlbhf.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.daria6918.cn/Article/details/gtdgbaiohg.html

[K02] JSON 字符串转对象
来源：http://dali.chenzaomai.com/Article/details/gttxfewfud.html

Py:   json.loads(s)
来源：http://dali.9152youxi.cn/Article/details/gtpdxpixcl.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yonumen.top/Article/details/gtuehstbld.html

JS:   JSON.parse(s)
来源：http://dali.sysykeji.top/Article/details/gtshaglaox.html

TS:   JSON.parse(s)
来源：http://dali.chenlongwang.top/Article/details/gtscsxvocf.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.cdnleiting.top/Article/details/gttdtbxavo.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.shanyushiyangtech.top/Article/details/gtcpjkfyyz.html

Ruby: JSON.parse(s)
来源：http://dali.cashguo.top/Article/details/gtlubpghsm.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.birdmap.top/Article/details/gtpukabuxc.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.hnxiangtu.top/Article/details/gtfatcsjsj.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yongpay.top/Article/details/gtcsqflaaa.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.svipenyu.cn/Article/details/gtzxoeoiox.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.meibo888.top/Article/details/gtzgsthjsn.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.gaohongyu789.top/Article/details/gthbfgrnag.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jianghu66.top/Article/details/gtqkcletvw.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.cucudq.cn/Article/details/gtgvbjpart.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.ivvv.top/Article/details/gtijejxtsj.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.sweek.top/Article/details/gtxzkdfqxf.html

[K04] 读取 JSON 文件
来源：http://dali.chenlongwang.top/Article/details/gtmpwkhslu.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.snrcjt.cn/Article/details/gtbtqxuwzf.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.birdmap.top/Article/details/gttlkbevpi.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ybcxt.top/Article/details/gtinsgpern.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zycfv.cn/Article/details/gtmbhtwlrb.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhiwuduotai.top/Article/details/gtjniqjhyj.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.pycfn.com/Article/details/gtbczvgays.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.dianchejie.cn/Article/details/gtvlyoqsip.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhengqikj.top/Article/details/gtsfhgxtqn.html

[K05] 深拷贝对象
来源：http://dali.hywenlv.cn/Article/details/gtmtdepstt.html

Py:   copy.deepcopy(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtplorefyu.html

PHP:  unserialize(serialize($obj));
来源：http://dali.birdmap.top/Article/details/gtlpwzxbvv.html

JS:   structuredClone(obj)
来源：http://dali.9152youxi.cn/Article/details/gtizeimsep.html

TS:   structuredClone(obj)
来源：http://dali.yj202588.top/Article/details/gtvcjfvnpj.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.quarkkingdee.top/Article/details/gtioqophfv.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.andypj.xyz/Article/details/gtapueigdh.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.aizwys.cn/Article/details/gtkofkimjv.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.ppjwa.cn/Article/details/gtixtyaewz.html

[K06] 解析 URL 查询串
来源：http://dali.daria6918.cn/Article/details/gtjxcfiqev.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.vqdsnc.cn/Article/details/gtksimbcsp.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.chenzaomai.com/Article/details/gtdyruqdwk.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.meibo888.top/Article/details/gttaltruby.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sxryk.cn/Article/details/gtvrfzvdmx.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhengqikj.top/Article/details/gtjqecgwrm.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.kuanghao11.cn/Article/details/gtxmprhoua.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jinqigfzy.top/Article/details/gtfwewhzer.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yj20258888.top/Article/details/gtlnsceyrx.html

[K07] 进制转换
来源：http://dali.zhoulong.xyz/Article/details/gtyfugeuww.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.cucudq.cn/Article/details/gttqgyxgwj.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jinghuilouyu.cn/Article/details/gtegrcjddg.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhiwuduotai.top/Article/details/gtaovpyfmw.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.redwolf501.top/Article/details/gtyqgqxptu.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.316326.xyz/Article/details/gtvzmdhsfp.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.chenlongwang.top/Article/details/gthhedneop.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.fengsongda.top/Article/details/gtonthimjk.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yonumen.top/Article/details/gtfpxmgwup.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.hammf.cn/Article/details/gtvvzbhdlw.html

Py:   pickle.dumps(obj)
来源：http://dali.zhoulong.xyz/Article/details/gtmqxamqiu.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.hongshengwenyu.top/Article/details/gtnojfpsdk.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zycfv.cn/Article/details/gtfdlzdrif.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jinqigufen.top/Article/details/gtfxwfjzha.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yangfankeji.com/Article/details/gtgdwoafkt.html

Go:   encoding/gob
来源：http://dali.chenlongwang.top/Article/details/gtlgcogsiy.html

Ruby: Marshal.dump(obj)
来源：http://dali.shzxlz.cn/Article/details/gtxhzjuhkx.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.guowangkeji.top/Article/details/gtxupddevj.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtrrhypfll.html

L. 网络请求
来源：http://dali.sxryk.cn/Article/details/gtrzpqbnnx.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtxllnpnhr.html

[L01] 发送 GET 请求
来源：http://dali.yj20258888.top/Article/details/gttslehoti.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.smart0.xyz/Article/details/gtijvmawrn.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jiagoushi.top/Article/details/gtzxtepacx.html

JS:   await fetch(url)
来源：http://dali.xuetiantiany.cn/Article/details/gtasvrvotg.html

TS:   await fetch(url)
来源：http://dali.shuidangran.top/Article/details/gtupbweeez.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jqgfzy.top/Article/details/gtbhtdtrme.html

Go:   resp, err := http.Get(url)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtihgshkvx.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.hnqzz.top/Article/details/gtwbcxajot.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.dashuyun.cn/Article/details/gtphrajlef.html

[L02] 发送 POST JSON
来源：http://dali.sweek.top/Article/details/gtnfntylaj.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.dianchejie.cn/Article/details/gtqwpyesuc.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.sufxvd.cn/Article/details/gtlvjubevz.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhixingplan.top/Article/details/gtyxubteda.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.daria6918.cn/Article/details/gtilxwmizp.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jianghu66.top/Article/details/gtehvgpvfw.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.birdmap.top/Article/details/gtulbfjkdv.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.sweek.top/Article/details/gtcxngtmue.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhixingplan.top/Article/details/gtiksfhmda.html

[L03] 设置自定义请求头
来源：http://dali.fzhhl.top/Article/details/gtdxcmvszv.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.dianchejie.cn/Article/details/gtviiycihh.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.nanxuanxn.top/Article/details/gterxczkag.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.nanxuanxn.top/Article/details/gtuaszwyde.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xuetiantiany.cn/Article/details/gtgfzklxvw.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhoulong.xyz/Article/details/gtgmfnthkj.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.chenzaomai.com/Article/details/gtlrwrgtka.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.redwolf501.top/Article/details/gtozcdqotk.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.iojbl.cn/Article/details/gtiiwjlwpm.html

[L04] 设置超时
来源：http://dali.0kj1m.cn/Article/details/gtnzthvehm.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhixingplan.top/Article/details/gtjsnvhmog.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.redwolf501.top/Article/details/gtxkyfkjsp.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhengqikj.top/Article/details/gtdnrizhiu.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yanxiufei.cn/Article/details/gtyjtuoynv.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.havefunace.top/Article/details/gttvipwgza.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zdqjudy.top/Article/details/gtlysrkqjz.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.guannengcc.top/Article/details/gtjkmfrnjb.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yvedp.cn/Article/details/gtsxckzsow.html

[L05] 上传文件（multipart）
来源：http://dali.jinqigufen.top/Article/details/gteqygwujr.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.smart0.xyz/Article/details/gtznphrscz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.9152youxi.cn/Article/details/gtkysqkebd.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.aizwys.cn/Article/details/gtspcbfncc.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jyoumei.cn/Article/details/gtbtrvvjjv.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.cheryme.top/Article/details/gtzqaozapr.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbxdroxjp.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhiwuduotai.top/Article/details/gtvtjdosts.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.xinyue.icu/Article/details/gtpjchwpyt.html

[L06] 解析响应为 JSON
来源：http://dali.sufxvd.cn/Article/details/gtmpmjuzvm.html

Py:   resp.json()
来源：http://dali.sxryk.cn/Article/details/gtovbnebfk.html

PHP:  json_decode($body, true);
来源：http://dali.yangfankeji.com/Article/details/gtkgvtbhfi.html

JS:   await resp.json()
来源：http://dali.nanxinkj.top/Article/details/gtemkexsti.html

TS:   await resp.json()
来源：http://dali.dianchejie.cn/Article/details/gtjhxdjzup.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.tianlin.xyz/Article/details/gtdbifjsgo.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.9152youxi.cn/Article/details/gtbawtrysz.html

Ruby: JSON.parse(resp.body)
来源：http://dali.xylfe.cn/Article/details/gtkmjrzqza.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.cucudq.cn/Article/details/gtqogwkkwd.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhoulong.xyz/Article/details/gtcbfkyfhn.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.hnqzz.top/Article/details/gtvcikorxw.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.316326.xyz/Article/details/gttaczlhjj.html

JS:   resp.ok;  resp.status
来源：http://dali.xylfe.cn/Article/details/gtindebzqj.html

TS:   resp.ok;  resp.status
来源：http://dali.jinqigfzy.top/Article/details/gthfpiswmv.html

Java: resp.statusCode()
来源：http://dali.cheryme.top/Article/details/gtqueibkzr.html

Go:   resp.StatusCode
来源：http://dali.birdmap.top/Article/details/gtnjxogdzj.html

Ruby: resp.code.to_i
来源：http://dali.wangshuangyany.cn/Article/details/gtvyenthql.html

C#:   (int)resp.StatusCode
来源：http://dali.yuxming.cn/Article/details/gtxdydhgnq.html

[L08] 并发请求多个地址
来源：http://dali.mhx1999.top/Article/details/gtcabwgjay.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.0kj1m.cn/Article/details/gtnngcufov.html

PHP:  curl_multi_init() 系列
来源：http://dali.bjfxy.top/Article/details/gtbryuprqf.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yuxming.cn/Article/details/gtcybdbczm.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.316326.xyz/Article/details/gtxekbyjwb.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.nwbrower.top/Article/details/gtlnfhvsck.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.pycfn.com/Article/details/gtfjgkaymy.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.xinyue.icu/Article/details/gthzvlmuys.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.dianchejie.cn/Article/details/gtyxoltcsl.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtxieuhasj.html

M. 命令行 / 进程 / 环境
来源：http://dali.snrcjt.cn/Article/details/gtmbwhmwes.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtvzumnpkj.html

[M01] 读取命令行参数
来源：http://dali.daria6918.cn/Article/details/gtexaqeuhc.html

Py:   sys.argv[1:]
来源：http://dali.guowangkeji.top/Article/details/gtmoxorqhw.html

PHP:  $argv;  $argc;
来源：http://dali.ehwqpu.com/Article/details/gttlpberln.html

JS:   process.argv.slice(2)
来源：http://dali.cheryme.top/Article/details/gtmtoszgpk.html

TS:   process.argv.slice(2)
来源：http://dali.gaohongyu789.top/Article/details/gtilshzukd.html

Java: args 数组（main 方法参数）
来源：http://dali.jiagoushi.top/Article/details/gtqkkwntdj.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gtdtxghycu.html

Ruby: ARGV
来源：http://dali.redwolf501.top/Article/details/gtjlarqdzh.html

C#:   args 数组（Main 方法参数）
来源：http://dali.daria6918.cn/Article/details/gtdcnzxawf.html

[M02] 读取环境变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxkzvneqt.html

Py:   os.environ.get("HOME")
来源：http://dali.gotoacloud.top/Article/details/gthlxjbdhg.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.ppjwa.cn/Article/details/gtynbdtmrz.html

JS:   process.env.HOME
来源：http://dali.aibaodan.cn/Article/details/gtzvodyffm.html

TS:   process.env.HOME
来源：http://dali.redwolf501.top/Article/details/gtwzsocvux.html

Java: System.getenv("HOME")
来源：http://dali.mhx1999.top/Article/details/gtlaesejug.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhiwuduotai.top/Article/details/gtwuztgrhg.html

Ruby: ENV["HOME"]
来源：http://dali.vqdsnc.cn/Article/details/gtzvtaacqt.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.316326.xyz/Article/details/gtxrjaudva.html

[M03] 执行外部命令
来源：http://dali.jlsjyb.cn/Article/details/gtqdnfunio.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.guowangkeji.top/Article/details/gtxhhdwxgt.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.aibaodan.cn/Article/details/gtkneufesd.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.redwolf501.top/Article/details/gtvmekyvgf.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.chenlongwang.top/Article/details/gtdjgtmgkf.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jiagoushi.top/Article/details/gtdezrunbd.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.andypj.xyz/Article/details/gtkadbmdyu.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yj20258888.top/Article/details/gtijfszgpw.html

C#:   Process.Start("ls", "-l");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtythvefel.html

[M04] 获取当前工作目录
来源：http://dali.hywenlv.cn/Article/details/gtgnrefwnf.html

Py:   os.getcwd()
来源：http://dali.cqqwz.cn/Article/details/gtdnroxpiz.html

PHP:  getcwd();
来源：http://dali.hammf.cn/Article/details/gtnimesivy.html

JS:   process.cwd()
来源：http://dali.meibo888.top/Article/details/gtivhvwqpo.html

TS:   process.cwd()
来源：http://dali.fengsongda.top/Article/details/gtiiqjjdvr.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.cheryme.top/Article/details/gtwiibntdy.html

Go:   os.Getwd()
来源：http://dali.yj20258888.top/Article/details/gtrgiojfmu.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gtflemklxe.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.gotoacloud.top/Article/details/gtdcdyprob.html

[M05] 设置退出码
来源：http://dali.wangshuangyany.cn/Article/details/gtktikoglo.html

Py:   sys.exit(1)
来源：http://dali.cucudq.cn/Article/details/gtubldifmn.html

PHP:  exit(1);
来源：http://dali.yvedp.cn/Article/details/gtovfclits.html

JS:   process.exit(1)
来源：http://dali.cashguo.top/Article/details/gteaujcypy.html

TS:   process.exit(1)
来源：http://dali.aibaodan.cn/Article/details/gtljlnvglo.html

Java: System.exit(1)
来源：http://dali.tanke756.top/Article/details/gtlbhjangg.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gtzfkfpdfb.html

Ruby: exit 1
来源：http://dali.sxryk.cn/Article/details/gtjrctkqcn.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yanxiufei.cn/Article/details/gtnwfqqqeo.html

[M06] 向标准错误输出
来源：http://dali.xziqi.cn/Article/details/gtfvcvwvjd.html

Py:   print("err", file=sys.stderr)
来源：http://dali.guannengcc.top/Article/details/gtfpbufesm.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.snrcjt.cn/Article/details/gtlntcwgvn.html

JS:   console.error("err")
来源：http://dali.xylfe.cn/Article/details/gtyosyxikd.html

TS:   console.error("err")
来源：http://dali.vqdsnc.cn/Article/details/gtolwvgrkk.html

Java: System.err.println("err")
来源：http://dali.sweek.top/Article/details/gtvbigxmog.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhengqikj.top/Article/details/gtskeejdxi.html

Ruby: warn "err"
来源：http://dali.haohaochexian.top/Article/details/gtwlxdlkrj.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.smart0.xyz/Article/details/gtteqaoxme.html

[M07] 判断是否为主入口
来源：http://dali.xuanzx.com/Article/details/gtnisssjdf.html

Py:   if __name__ == "__main__":
来源：http://dali.xziqi.cn/Article/details/gtkkurtekg.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yvedp.cn/Article/details/gtbikngjnq.html

JS:   require.main === module
来源：http://dali.yonumen.top/Article/details/gtgwtuouut.html

TS:   require.main === module
来源：http://dali.yj20258888.top/Article/details/gtwbphcnor.html

Java: public static void main(String[] args)
来源：http://dali.jianghu66.top/Article/details/gtwhkossvo.html

Go:   func main()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtihjtaomm.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.haohaochexian.top/Article/details/gtdxmlvzqt.html

C#:   static void Main(string[] args)
来源：http://dali.haohaochexian.top/Article/details/gtigidkbyz.html

[M08] 获取系统与运行时信息
来源：http://dali.gogol.net.cn/Article/details/gtqewoewuj.html

Py:   platform.system();  platform.python_version()
来源：http://dali.wangshuangyany.cn/Article/details/gtgfkdztjr.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.cqqwz.cn/Article/details/gthyoacsrw.html

JS:   process.platform;  process.version
来源：http://dali.xziqi.cn/Article/details/gtgsvrxvsg.html

TS:   process.platform;  process.version
来源：http://dali.pycfn.com/Article/details/gttjylqqzn.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jyoumei.cn/Article/details/gtxxzdzyjz.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.xuanzx.com/Article/details/gtiwlmlrvg.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yuanzhike.top/Article/details/gtunwjspvn.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.ydzc1.top/Article/details/gtsmqbubwm.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtoajojcjv.html

N. 数据结构与算法
来源：http://dali.xylfe.cn/Article/details/gtzxmfsomj.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtqtugyjni.html

[N01] 二分查找（有序数组）
来源：http://dali.wangdashe.top/Article/details/gtrxetfaev.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtadgujutr.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zycfv.cn/Article/details/gtbwxntrlj.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shanyushiyangtech.top/Article/details/gtlvlnobel.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yongpay.top/Article/details/gtofosalgd.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.xziqi.cn/Article/details/gtspaihpux.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.tanke756.top/Article/details/gtrveinvpr.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.tanke756.top/Article/details/gtsfnrhuwu.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jiagoushi.top/Article/details/gtidljajwt.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hysaishi.cn/Article/details/gtrmetonng.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.svipenyu.cn/Article/details/gtgysxnmlm.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.gogol.net.cn/Article/details/gthtdqjjph.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.quarkkingdee.top/Article/details/gtprsvytji.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.kuanghao11.cn/Article/details/gtfvebxnom.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.dianchejie.cn/Article/details/gtaeqapjyj.html

Go:   slices.Sort(arr)
来源：http://dali.jinqigufen.top/Article/details/gtaadupmyd.html

Ruby: arr.sort
来源：http://dali.chenlongwang.top/Article/details/gtbksbvkaw.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gtiycppptt.html

[N03] 快速排序（分治示例）
来源：http://dali.jlsjyb.cn/Article/details/gtrkhnemwb.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.bjfxy.top/Article/details/gtvpvximlz.html

PHP:  // 递归实现，或用 usort
来源：http://dali.xinyue.icu/Article/details/gttyvcffln.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.pengpengdd.cyou/Article/details/gtkfsbdmze.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.daxiang520.top/Article/details/gtptzftqfz.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.havefunace.top/Article/details/gtojepvbaz.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhengqikj.top/Article/details/gtzdueoxtj.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.quarkkingdee.top/Article/details/gtusfmtoft.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.ppjwa.cn/Article/details/gtowwcsaxg.html

[N04] 斐波那契数列
来源：http://dali.jinqigufen.top/Article/details/gtkpwzkjty.html


<!-- 参考信息 -->