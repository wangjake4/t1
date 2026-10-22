代发 wailian999

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.pengpengdd.cyou/Article/details/gtrvhouxji.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.tanke756.top/Article/details/gtqivhqyqy.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhijiandao.cn/Article/details/gtevqeawoy.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xziqi.cn/Article/details/gtdtlrvwyu.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.fengsongda.top/Article/details/gtcolzlnvr.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhiwuduotai.top/Article/details/gtgndtlfqn.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.andypj.xyz/Article/details/gtkksirtxz.html

[J06] 计算两时间之差
来源：http://dali.yvedp.cn/Article/details/gtszxppokb.html

Py:   (end - start).total_seconds()
来源：http://dali.dianchejie.cn/Article/details/gtqdophjih.html

PHP:  $end->diff($start)->days;
来源：http://dali.kuanghao11.cn/Article/details/gttjbwxdsc.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.hfpthk.cn/Article/details/gtwopumzdg.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.snrcjt.cn/Article/details/gtpgkobfiw.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.tian-w.cn/Article/details/gtyvczmzjf.html

Go:   end.Sub(start).Hours()
来源：http://dali.svipenyu.cn/Article/details/gtewzrfxyp.html

Ruby: end - start                 # 返回秒数
来源：http://dali.aibaodan.cn/Article/details/gtybhyigux.html

C#:   (end - start).TotalSeconds
来源：http://dali.chenzaomai.com/Article/details/gtpyzqyrgj.html

[J07] 比较两个日期
来源：http://dali.cucudq.cn/Article/details/gtdklwvque.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.sxryk.cn/Article/details/gtlpzsrdti.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.guannengcc.top/Article/details/gtwtlpinar.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhoulong.xyz/Article/details/gtqpwtraxl.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zdqjudy.top/Article/details/gtpjdczaxc.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jqgufenzy.top/Article/details/gtlcurjrnh.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.nanxuanxn.top/Article/details/gtaqrizubu.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.tian-w.cn/Article/details/gtafnzwxsh.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.andypj.xyz/Article/details/gtyhoiouhi.html

[J08] 提取年月日与星期
来源：http://dali.vqdsnc.cn/Article/details/gtqevrbzzr.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.c1oappe.top/Article/details/gtyhuunjzv.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.shuidangran.top/Article/details/gtkwkpzthr.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jiagoushi.top/Article/details/gtxsgtvfpe.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.gogol.net.cn/Article/details/gtmemuwdwo.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhijiandao.cn/Article/details/gtbzvhasye.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzjzpwenc.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jinqigufen.top/Article/details/gtvywfsdwq.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hfpthk.cn/Article/details/gtenxmjmkf.html

[J09] 时区处理
来源：http://dali.svipenyu.cn/Article/details/gtnfoyogei.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhiwuduotai.top/Article/details/gtjkdhzive.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.guowangkeji.top/Article/details/gtwecdatbw.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zdqjudy.top/Article/details/gturslslex.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hfpthk.cn/Article/details/gtzbdpypbr.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxrlnzdfx.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhongyouzk.top/Article/details/gtsjydjqnz.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhoulong.xyz/Article/details/gtrqsfgjyz.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.dianchejie.cn/Article/details/gttiydagfb.html

[J10] 取今天 / 本月第一天
来源：http://dali.birdmap.top/Article/details/gtkgyersgv.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhixingplan.top/Article/details/gtgvnneece.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.cdnleiting.top/Article/details/gtzxabuxpq.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.daxiang520.top/Article/details/gtsmsdyfpo.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhengqikj.top/Article/details/gtxmrrcdcp.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.xinyue.icu/Article/details/gthzdkxwcy.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.xziqi.cn/Article/details/gtaxtljqau.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhoulong.xyz/Article/details/gtvyayrmca.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yangfankeji.com/Article/details/gtvcbxfqje.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtaehwkhzs.html

K. JSON 与序列化
来源：http://dali.aibaodan.cn/Article/details/gtsqbudxxt.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtidnorivs.html

[K01] 对象转 JSON 字符串
来源：http://dali.nwbrower.top/Article/details/gtliotdllj.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yuanzhike.top/Article/details/gtktndbmxn.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.hnxiangtu.top/Article/details/gtuekeeyfd.html

JS:   JSON.stringify(obj)
来源：http://dali.sxryk.cn/Article/details/gtcnvcqwuv.html

TS:   JSON.stringify(obj)
来源：http://dali.316326.xyz/Article/details/gtednrmbsw.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.hammf.cn/Article/details/gtfydfkezd.html

Go:   json.Marshal(obj)
来源：http://dali.havefunace.top/Article/details/gtezhvpgzo.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.xziqi.cn/Article/details/gteafgrwnx.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.guowangkeji.top/Article/details/gthrmnezga.html

[K02] JSON 字符串转对象
来源：http://dali.jinghuilouyu.cn/Article/details/gtbozdgjom.html

Py:   json.loads(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtciokefrd.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.gzhubu.top/Article/details/gttewxzjpd.html

JS:   JSON.parse(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtbiciglsq.html

TS:   JSON.parse(s)
来源：http://dali.nanxinkj.top/Article/details/gtrvvjaumh.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.ivvv.top/Article/details/gtwmppwkkd.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jyoumei.cn/Article/details/gtkpiyvyxf.html

Ruby: JSON.parse(s)
来源：http://dali.zhoulong.xyz/Article/details/gtscongfdg.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zdqjudy.top/Article/details/gtmfwtczyr.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhiwuduotai.top/Article/details/gtcaiubtxq.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteyeigkcu.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jinghuilouyu.cn/Article/details/gttookpeqh.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.shangyingyoupin.top/Article/details/gtgurvlkuh.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yanxiufei.cn/Article/details/gtnpicgqef.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zdqjudy.top/Article/details/gtdcowrcbp.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jyoumei.cn/Article/details/gttqzsczym.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.haohaochexian.top/Article/details/gtxbhalyte.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jlsjyb.cn/Article/details/gtjdhmwxye.html

[K04] 读取 JSON 文件
来源：http://dali.birdmap.top/Article/details/gtuohqsgkq.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.hfpthk.cn/Article/details/gtrjuwxcms.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jinghuilouyu.cn/Article/details/gtdcszjqrj.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.haohaochexian.top/Article/details/gtbyxefjch.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yongpay.top/Article/details/gtsrxaducu.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.smart0.xyz/Article/details/gtygbpkcsb.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.smart0.xyz/Article/details/gtoootpbcv.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.cqqwz.cn/Article/details/gtadfcjoah.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.shuidangran.top/Article/details/gtmgaihlzg.html

[K05] 深拷贝对象
来源：http://dali.hysaishi.cn/Article/details/gtxsafbdcm.html

Py:   copy.deepcopy(obj)
来源：http://dali.ydzc1.top/Article/details/gtwrbjslin.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jiagoushi.top/Article/details/gtfzrwzohv.html

JS:   structuredClone(obj)
来源：http://dali.sxryk.cn/Article/details/gttnmqfxhu.html

TS:   structuredClone(obj)
来源：http://dali.sufxvd.cn/Article/details/gtmasasihf.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jinqigufen.top/Article/details/gtqowgrlro.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.hammf.cn/Article/details/gtmjrtskau.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvtbyafec.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.haohaochexian.top/Article/details/gtqckirdzk.html

[K06] 解析 URL 查询串
来源：http://dali.pengpengdd.cyou/Article/details/gthmuaijdo.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.gotoacloud.top/Article/details/gtdbrcyios.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yanxiufei.cn/Article/details/gtczutpbfl.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hnqzz.top/Article/details/gtfbjnopkl.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.haohaochexian.top/Article/details/gtrytuwuzj.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.hysaishi.cn/Article/details/gtvujqlzlr.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jinqigfzy.top/Article/details/gtjrnznqyu.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jinqigfzy.top/Article/details/gtormbrork.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.ehwqpu.com/Article/details/gtvzreoztw.html

[K07] 进制转换
来源：http://dali.gogol.net.cn/Article/details/gtnprlumbh.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.tanke756.top/Article/details/gtlbqdwmub.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jinghuilouyu.cn/Article/details/gtfeabyhai.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.quarkkingdee.top/Article/details/gtoiktvnaq.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.daxiang520.top/Article/details/gtxkpnkvqb.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.gogol.net.cn/Article/details/gtvmknhupw.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.birdmap.top/Article/details/gtyjeuzxke.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.jinghuilouyu.cn/Article/details/gtggwdyuec.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.haohaochexian.top/Article/details/gtnehmrrtm.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxiiccnjy.html

Py:   pickle.dumps(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtwdrnioht.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.cashguo.top/Article/details/gtgqoioqin.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.tanke756.top/Article/details/gtvxjgikex.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.smart0.xyz/Article/details/gtqyntmudj.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.havefunace.top/Article/details/gtibbwihvu.html

Go:   encoding/gob
来源：http://dali.nwbrower.top/Article/details/gtxpcmyfas.html

Ruby: Marshal.dump(obj)
来源：http://dali.sufxvd.cn/Article/details/gtjbbuyolg.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.gotoacloud.top/Article/details/gtckjnhxac.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtdyiioesi.html

L. 网络请求
来源：http://dali.vqdsnc.cn/Article/details/gtusywsfqw.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtnbvkostw.html

[L01] 发送 GET 请求
来源：http://dali.nanxuanxn.top/Article/details/gticwjbroy.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yongpay.top/Article/details/gttbentetl.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.shuidangran.top/Article/details/gtwzhkrkig.html

JS:   await fetch(url)
来源：http://dali.yangfankeji.com/Article/details/gtoeujdpmz.html

TS:   await fetch(url)
来源：http://dali.vqdsnc.cn/Article/details/gtagevqwsa.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.haohaochexian.top/Article/details/gtiwovgtyc.html

Go:   resp, err := http.Get(url)
来源：http://dali.chenjidiqi.icu/Article/details/gtqwrfktns.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.bjfxy.top/Article/details/gtanoqybah.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.hfpthk.cn/Article/details/gtrobitvbv.html

[L02] 发送 POST JSON
来源：http://dali.nwbrower.top/Article/details/gtqhbnvkvs.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.hfpthk.cn/Article/details/gtstqoscii.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.tanke756.top/Article/details/gttzgbrrpc.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.dianchejie.cn/Article/details/gtbbawipfv.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.fengsongda.top/Article/details/gtsdcctyle.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.xuetiantiany.cn/Article/details/gtxjspsbpi.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.xinyue.icu/Article/details/gttsrpnyif.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.wangdashe.top/Article/details/gteqittobc.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.wangdashe.top/Article/details/gthkrzogve.html

[L03] 设置自定义请求头
来源：http://dali.9152youxi.cn/Article/details/gttwmwrcmq.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.hysaishi.cn/Article/details/gtgraghiej.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.c1oappe.top/Article/details/gttfyqllrt.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.chenzaomai.com/Article/details/gtrbkvkpnw.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.daxiang520.top/Article/details/gtdzqvkfgd.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.dashuyun.cn/Article/details/gtaopqzncq.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.hywenlv.cn/Article/details/gtahqiumjg.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jyoumei.cn/Article/details/gtwsqtxehi.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.hnxiangtu.top/Article/details/gttikuhpzy.html

[L04] 设置超时
来源：http://dali.zhengqikj.top/Article/details/gtqqclvcuq.html

Py:   requests.get(url, timeout=5)
来源：http://dali.ydzc1.top/Article/details/gteqxtpfaq.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.hnxiangtu.top/Article/details/gtblpurbdx.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.c1oappe.top/Article/details/gtaqbskusk.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.bjfxy.top/Article/details/gtrcschjzp.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhixingplan.top/Article/details/gtjjphfnbr.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yj202588.top/Article/details/gtrqnospuk.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.redwolf501.top/Article/details/gtjeidtdbm.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yvedp.cn/Article/details/gtellkwozg.html

[L05] 上传文件（multipart）
来源：http://dali.hammf.cn/Article/details/gtxrjnetcj.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhixingplan.top/Article/details/gtqljmfutw.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.xylfe.cn/Article/details/gtjfvlbpud.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhixingplan.top/Article/details/gtraylegxh.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yangfankeji.com/Article/details/gtflwddldo.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhiwuduotai.top/Article/details/gtlrzrwzrj.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.tian-w.cn/Article/details/gtjtssseuf.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.shangyingyoupin.top/Article/details/gtgccrbmew.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gtxlhfdnlj.html

[L06] 解析响应为 JSON
来源：http://dali.gogol.net.cn/Article/details/gtxoovvlwt.html

Py:   resp.json()
来源：http://dali.birdmap.top/Article/details/gtwngfohoe.html

PHP:  json_decode($body, true);
来源：http://dali.yuanzhike.top/Article/details/gtqlgtfnmw.html

JS:   await resp.json()
来源：http://dali.jqgfzy.top/Article/details/gtxjtzgued.html

TS:   await resp.json()
来源：http://dali.hnqzz.top/Article/details/gtufxwsmss.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jinghuilouyu.cn/Article/details/gtfuhbszjc.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.hammf.cn/Article/details/gtetvpoopg.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yueranfly.top/Article/details/gtwnlvkwyi.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.smart0.xyz/Article/details/gtjkjuzpxx.html

[L07] 处理 HTTP 状态码
来源：http://dali.9152youxi.cn/Article/details/gtolchgvsm.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxkbkbazy.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.ivvv.top/Article/details/gtrzaytxou.html

JS:   resp.ok;  resp.status
来源：http://dali.hammf.cn/Article/details/gtcejnoruy.html

TS:   resp.ok;  resp.status
来源：http://dali.cucudq.cn/Article/details/gtkugsihco.html

Java: resp.statusCode()
来源：http://dali.c1oappe.top/Article/details/gtosyczbpm.html

Go:   resp.StatusCode
来源：http://dali.hysaishi.cn/Article/details/gtvhuyzmpc.html

Ruby: resp.code.to_i
来源：http://dali.zhiwuduotai.top/Article/details/gtndvmotdi.html

C#:   (int)resp.StatusCode
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwlgwnlou.html

[L08] 并发请求多个地址
来源：http://dali.hnxiangtu.top/Article/details/gtqgevhwde.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.shzxlz.cn/Article/details/gtephwphtw.html

PHP:  curl_multi_init() 系列
来源：http://dali.gotoacloud.top/Article/details/gtknouginy.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinqigufen.top/Article/details/gtjdfysuxe.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hfpthk.cn/Article/details/gtcgewgoqq.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhixingplan.top/Article/details/gtkrvoawwl.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.vqdsnc.cn/Article/details/gtonmlzuxv.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.wangshuangyany.cn/Article/details/gtjbzjkxga.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.nanxinkj.top/Article/details/gtkivtsujf.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtnuwqelfa.html

M. 命令行 / 进程 / 环境
来源：http://dali.jyoumei.cn/Article/details/gtmxmvizez.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtrmquqidl.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gtxuqxmjcw.html

Py:   sys.argv[1:]
来源：http://dali.jinghuilouyu.cn/Article/details/gtiukrhgyn.html

PHP:  $argv;  $argc;
来源：http://dali.hammf.cn/Article/details/gtxnldcsvz.html

JS:   process.argv.slice(2)
来源：http://dali.pengpengdd.cyou/Article/details/gtpojjewws.html

TS:   process.argv.slice(2)
来源：http://dali.hammf.cn/Article/details/gtggttuuvf.html

Java: args 数组（main 方法参数）
来源：http://dali.yvedp.cn/Article/details/gtsobddsqc.html

Go:   os.Args[1:]
来源：http://dali.jlsjyb.cn/Article/details/gtvrwwztdx.html

Ruby: ARGV
来源：http://dali.jqgfzy.top/Article/details/gtewxmscxh.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhongyouzk.top/Article/details/gtlpawvswh.html

[M02] 读取环境变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfdrvggmu.html

Py:   os.environ.get("HOME")
来源：http://dali.wangshuangyany.cn/Article/details/gtfzbfvrpk.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.sysykeji.top/Article/details/gttxspoewx.html

JS:   process.env.HOME
来源：http://dali.jqgfzy.top/Article/details/gtofeyoxni.html

TS:   process.env.HOME
来源：http://dali.iojbl.cn/Article/details/gtmgdwbokk.html

Java: System.getenv("HOME")
来源：http://dali.jianghu66.top/Article/details/gtnkyrwyhf.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yanxiufei.cn/Article/details/gtuygrabsb.html

Ruby: ENV["HOME"]
来源：http://dali.ehwqpu.com/Article/details/gtiswyahru.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.aizwys.cn/Article/details/gtyueupnyq.html

[M03] 执行外部命令
来源：http://dali.zhoulong.xyz/Article/details/gtumfjfrin.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jinqigfzy.top/Article/details/gtrupvebyu.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtufxpggqq.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.gogol.net.cn/Article/details/gtcuftwxxn.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.ehwqpu.com/Article/details/gtlgeujhmz.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.hysaishi.cn/Article/details/gtxnmznefu.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhengqikj.top/Article/details/gtznmqpitx.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.cheryme.top/Article/details/gtcmzsbtox.html

C#:   Process.Start("ls", "-l");
来源：http://dali.shzxlz.cn/Article/details/gtznmdhupz.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gtypvulnjs.html

Py:   os.getcwd()
来源：http://dali.snrcjt.cn/Article/details/gtwbxmowur.html

PHP:  getcwd();
来源：http://dali.chenlongwang.top/Article/details/gtisocqedh.html

JS:   process.cwd()
来源：http://dali.aibaodan.cn/Article/details/gtpmzwxgof.html

TS:   process.cwd()
来源：http://dali.hnxiangtu.top/Article/details/gteiyxekjy.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.haohaochexian.top/Article/details/gtnueihzez.html

Go:   os.Getwd()
来源：http://dali.shuidangran.top/Article/details/gtulbeprxf.html

Ruby: Dir.pwd
来源：http://dali.wangshuangyany.cn/Article/details/gteezsfkbe.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.mhx1999.top/Article/details/gtlbkuulfw.html

[M05] 设置退出码
来源：http://dali.ivvv.top/Article/details/gtofcrhtuy.html

Py:   sys.exit(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtkcljpvni.html

PHP:  exit(1);
来源：http://dali.cdnleiting.top/Article/details/gtliajahjv.html

JS:   process.exit(1)
来源：http://dali.guowangkeji.top/Article/details/gtuxjmxlho.html

TS:   process.exit(1)
来源：http://dali.xziqi.cn/Article/details/gttonnensa.html

Java: System.exit(1)
来源：http://dali.nwbrower.top/Article/details/gtpffeknkq.html

Go:   os.Exit(1)
来源：http://dali.yj202588.top/Article/details/gtxvpoysbq.html

Ruby: exit 1
来源：http://dali.daxiang520.top/Article/details/gtlhxeqhgh.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.hfpthk.cn/Article/details/gtnuyzhlgx.html

[M06] 向标准错误输出
来源：http://dali.jinqigufen.top/Article/details/gtorjoqcam.html

Py:   print("err", file=sys.stderr)
来源：http://dali.guannengcc.top/Article/details/gtgyvtogmy.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.sweek.top/Article/details/gtxowwixaz.html

JS:   console.error("err")
来源：http://dali.cdnleiting.top/Article/details/gtyrriurrn.html

TS:   console.error("err")
来源：http://dali.cqqwz.cn/Article/details/gtlqqirfjh.html

Java: System.err.println("err")
来源：http://dali.yanxiufei.cn/Article/details/gtiegttpdm.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yvedp.cn/Article/details/gtkcslarfc.html

Ruby: warn "err"
来源：http://dali.zycfv.cn/Article/details/gtidwwsuqb.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jqgufenzy.top/Article/details/gteaqbwxdd.html

[M07] 判断是否为主入口
来源：http://dali.shangyingyoupin.top/Article/details/gtcxzviksu.html

Py:   if __name__ == "__main__":
来源：http://dali.ybcxt.top/Article/details/gtmlsjohao.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.chenlongwang.top/Article/details/gtopkeyjzk.html

JS:   require.main === module
来源：http://dali.pengpengdd.cyou/Article/details/gtnxwjlfaz.html

TS:   require.main === module
来源：http://dali.guowangkeji.top/Article/details/gtmnlujqnp.html

Java: public static void main(String[] args)
来源：http://dali.jyoumei.cn/Article/details/gtkopwwpxz.html

Go:   func main()
来源：http://dali.pycfn.com/Article/details/gtkfkoplal.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.chenlongwang.top/Article/details/gtmphpucxj.html

C#:   static void Main(string[] args)
来源：http://dali.ivvv.top/Article/details/gtyjiovrju.html

[M08] 获取系统与运行时信息
来源：http://dali.tanke756.top/Article/details/gtqjppizfq.html

Py:   platform.system();  platform.python_version()
来源：http://dali.gogol.net.cn/Article/details/gtaczgzhqv.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.nwbrower.top/Article/details/gtjjkgoymd.html

JS:   process.platform;  process.version
来源：http://dali.ehwqpu.com/Article/details/gtufwtwmge.html

TS:   process.platform;  process.version
来源：http://dali.nanxuanxn.top/Article/details/gtsbijjahe.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.chenzaomai.com/Article/details/gtbbwhdtpf.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.hysaishi.cn/Article/details/gtrmxyxsar.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.ivvv.top/Article/details/gtsapbggbc.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.andypj.xyz/Article/details/gtbkopesil.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtmskbboor.html

N. 数据结构与算法
来源：http://dali.chenlongwang.top/Article/details/gtyrjcwhsn.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtkpbkhwza.html

[N01] 二分查找（有序数组）
来源：http://dali.hysaishi.cn/Article/details/gtxajkchhy.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.xuanzx.com/Article/details/gtalyublkn.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.vqdsnc.cn/Article/details/gtstradzit.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hnxiangtu.top/Article/details/gtqccsydcm.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.pycfn.com/Article/details/gtzxnvvude.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtkmfpfnme.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.fengsongda.top/Article/details/gtjlhqsrqm.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhengqikj.top/Article/details/gtmtngejoo.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.wangshuangyany.cn/Article/details/gtdcyqrtfe.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.sweek.top/Article/details/gtotzbxmew.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.birdmap.top/Article/details/gtxbtznxwm.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.tanke756.top/Article/details/gtsjmplirk.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.tian-w.cn/Article/details/gtqajzzejb.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.smart0.xyz/Article/details/gtmzvpcjut.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.pycfn.com/Article/details/gteuvwwjot.html

Go:   slices.Sort(arr)
来源：http://dali.ybcxt.top/Article/details/gtpczfufbd.html

Ruby: arr.sort
来源：http://dali.nanxinkj.top/Article/details/gtkktvhcyn.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.kuanghao11.cn/Article/details/gtvjkojuvi.html

[N03] 快速排序（分治示例）
来源：http://dali.0kj1m.cn/Article/details/gtnfgrepao.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yuanzhike.top/Article/details/gtxpppmqki.html


<!-- 参考信息 -->