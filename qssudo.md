代发 wailian999

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.hfpthk.cn/Article/details/gthlzolyoh.html

[J04] 时间戳与日期互转
来源：http://dali.chenzaomai.com/Article/details/gtudwpzdyk.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.iojbl.cn/Article/details/gtszhtmmqt.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.ivvv.top/Article/details/gtedqcvbic.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.daxiang520.top/Article/details/gtdnkybhbz.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jinqigfzy.top/Article/details/gtufvbjfqk.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.guannengcc.top/Article/details/gtimyfrmid.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.sufxvd.cn/Article/details/gttanukgvm.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yj202588.top/Article/details/gtepjzqwua.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.daxiang520.top/Article/details/gtuaekqtnz.html

[J05] 时间加减（加 7 天）
来源：http://dali.cashguo.top/Article/details/gtizikgqrp.html

Py:   now + timedelta(days=7)
来源：http://dali.xuetiantiany.cn/Article/details/gtsorzveny.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.shanyushiyangtech.top/Article/details/gtizcrmnfk.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yangfankeji.com/Article/details/gtizwupvhb.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.chenlongwang.top/Article/details/gtbqyhmdio.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnuqevgfy.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbfjvhrez.html

Ruby: Time.now + 7 * 86400
来源：http://dali.pengpengdd.cyou/Article/details/gtzxgychfc.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.bjfxy.top/Article/details/gtjkpohnse.html

[J06] 计算两时间之差
来源：http://dali.svipenyu.cn/Article/details/gtinrzjupr.html

Py:   (end - start).total_seconds()
来源：http://dali.yuxming.cn/Article/details/gtjbunzugx.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhoulong.xyz/Article/details/gtqqmhxdvj.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.quarkkingdee.top/Article/details/gtagtiirtn.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.sweek.top/Article/details/gtcguqizxf.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.sysykeji.top/Article/details/gtnpbhhinq.html

Go:   end.Sub(start).Hours()
来源：http://dali.zhoulong.xyz/Article/details/gtmyucuwxx.html

Ruby: end - start                 # 返回秒数
来源：http://dali.hywenlv.cn/Article/details/gttreqkgto.html

C#:   (end - start).TotalSeconds
来源：http://dali.jianghu66.top/Article/details/gtfgjufqci.html

[J07] 比较两个日期
来源：http://dali.hnxiangtu.top/Article/details/gtxnpqhztc.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yongpay.top/Article/details/gtormbrpkj.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.pycfn.com/Article/details/gtevmpdywq.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtelyryopo.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.chenlongwang.top/Article/details/gtjkwkasnn.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.tanke756.top/Article/details/gtaltlqylw.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.hywenlv.cn/Article/details/gtdjvmznbx.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.bjfxy.top/Article/details/gtgavjbxfn.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.hongshengwenyu.top/Article/details/gtzkyixsol.html

[J08] 提取年月日与星期
来源：http://dali.dianchejie.cn/Article/details/gthluwulet.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.shangyingyoupin.top/Article/details/gtafzfedvo.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.xinyue.icu/Article/details/gtnmscscqx.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.guannengcc.top/Article/details/gtiaotokpg.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.ydzc1.top/Article/details/gtuoldnfxo.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.redwolf501.top/Article/details/gtlwbazjhk.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hywenlv.cn/Article/details/gtaornliym.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.gogol.net.cn/Article/details/gtklxrnwpx.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zhiwuduotai.top/Article/details/gtahmjozdz.html

[J09] 时区处理
来源：http://dali.jqgfzy.top/Article/details/gtaijmizxw.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yueranfly.top/Article/details/gtndvcecsd.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwymsnken.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yongpay.top/Article/details/gthaangxrn.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.pycfn.com/Article/details/gtbpyuyhco.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.guannengcc.top/Article/details/gtdorzvsxn.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.ehwqpu.com/Article/details/gtugjpmqjc.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.ppjwa.cn/Article/details/gtocoxprtp.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.chenzaomai.com/Article/details/gtvgmyidyb.html

[J10] 取今天 / 本月第一天
来源：http://dali.feifeiyinyue.top/Article/details/gtaiustpcj.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.tianlin.xyz/Article/details/gtaspywueb.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.guannengcc.top/Article/details/gtfxqvzbsz.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.fengsongda.top/Article/details/gtkaexdshe.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.0kj1m.cn/Article/details/gtsrkwggia.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.havefunace.top/Article/details/gtxjjqlfjl.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yuxming.cn/Article/details/gtkxvmnoli.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hfpthk.cn/Article/details/gteoluvuru.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.guowangkeji.top/Article/details/gtgmkyqxov.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtmmtrhtjx.html

K. JSON 与序列化
来源：http://dali.fzhhl.top/Article/details/gtyzeggcss.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtdstwswfe.html

[K01] 对象转 JSON 字符串
来源：http://dali.yueranfly.top/Article/details/gtbfrnbhpc.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbfhszlju.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.xuetiantiany.cn/Article/details/gtkfypehzs.html

JS:   JSON.stringify(obj)
来源：http://dali.hnqzz.top/Article/details/gtvvkhdjni.html

TS:   JSON.stringify(obj)
来源：http://dali.hfpthk.cn/Article/details/gtzufrjqfr.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.dianchejie.cn/Article/details/gtpqlgwtpk.html

Go:   json.Marshal(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gtdhkrlycu.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hywenlv.cn/Article/details/gtqdzubisf.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.tian-w.cn/Article/details/gtojbmvqkg.html

[K02] JSON 字符串转对象
来源：http://dali.yuxming.cn/Article/details/gtlepupdhi.html

Py:   json.loads(s)
来源：http://dali.sweek.top/Article/details/gttomagpht.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbuqlcosc.html

JS:   JSON.parse(s)
来源：http://dali.pycfn.com/Article/details/gtiajvisxx.html

TS:   JSON.parse(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gthcygzgul.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jianghu66.top/Article/details/gtqaozfmqc.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.haohaochexian.top/Article/details/gtijoqhpha.html

Ruby: JSON.parse(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtduejarie.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.cheryme.top/Article/details/gtjhoqmspt.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.hnqzz.top/Article/details/gtdoupgnuu.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.chenjidiqi.icu/Article/details/gtwoeeakev.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.hfpthk.cn/Article/details/gtdcawehmw.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yanxiufei.cn/Article/details/gtcidorfvq.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.svipenyu.cn/Article/details/gtawhqfcfz.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.fzhhl.top/Article/details/gtgibvowrx.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yuanzhike.top/Article/details/gtrzhhloyu.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.redwolf501.top/Article/details/gtjrircngg.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.guannengcc.top/Article/details/gtboxkmeck.html

[K04] 读取 JSON 文件
来源：http://dali.daxiang520.top/Article/details/gtmpgpfmms.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.ivvv.top/Article/details/gtkulaycae.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.chenjidiqi.icu/Article/details/gttjzhmvmj.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ehwqpu.com/Article/details/gtiomimdge.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.tianlin.xyz/Article/details/gtklgkkuaw.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.sweek.top/Article/details/gthowzkavi.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.aibaodan.cn/Article/details/gtgtkpzdpe.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.316326.xyz/Article/details/gttwykgeop.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.kuanghao11.cn/Article/details/gtqhbovjft.html

[K05] 深拷贝对象
来源：http://dali.nwbrower.top/Article/details/gtswesnvmk.html

Py:   copy.deepcopy(obj)
来源：http://dali.cdnleiting.top/Article/details/gtqjfflndq.html

PHP:  unserialize(serialize($obj));
来源：http://dali.hammf.cn/Article/details/gtoafqlewk.html

JS:   structuredClone(obj)
来源：http://dali.zhixingplan.top/Article/details/gtnnwgpdcb.html

TS:   structuredClone(obj)
来源：http://dali.316326.xyz/Article/details/gtcikfplhg.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.hammf.cn/Article/details/gtbsuwpwfd.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.shanyushiyangtech.top/Article/details/gtusvlegay.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.smart0.xyz/Article/details/gtbbsnddtp.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.chenzaomai.com/Article/details/gtnacuhqjv.html

[K06] 解析 URL 查询串
来源：http://dali.gaohongyu789.top/Article/details/gttrhgwsjn.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.ppjwa.cn/Article/details/gtvwugizkg.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.xuanzx.com/Article/details/gtcgfiuphc.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.havefunace.top/Article/details/gtnkceygbb.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.smart0.xyz/Article/details/gtqxsosnah.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.shangyingyoupin.top/Article/details/gtgfbhreur.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhengqikj.top/Article/details/gtuuzjdsux.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.xinyue.icu/Article/details/gtqptpdosg.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.andypj.xyz/Article/details/gtmtpuwdjh.html

[K07] 进制转换
来源：http://dali.yongpay.top/Article/details/gtgtzjyjna.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.cdnleiting.top/Article/details/gtmxewzvoe.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.ybcxt.top/Article/details/gtrhgkcpcu.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.gzhubu.top/Article/details/gtmwlefwuc.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.hnxiangtu.top/Article/details/gtcwdjarpi.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jyoumei.cn/Article/details/gtdfewmyhx.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yuanzhike.top/Article/details/gtljuuuypg.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.feifeiyinyue.top/Article/details/gtpezndupo.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.0kj1m.cn/Article/details/gthiyhaoax.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.sxryk.cn/Article/details/gtohvspdpj.html

Py:   pickle.dumps(obj)
来源：http://dali.shzxlz.cn/Article/details/gtoujnmmki.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhijiandao.cn/Article/details/gtncwkkvyx.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.pycfn.com/Article/details/gtyozfkjoe.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.ppjwa.cn/Article/details/gtwrsqbfvh.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.xuanzx.com/Article/details/gtlwqwpcfc.html

Go:   encoding/gob
来源：http://dali.9152youxi.cn/Article/details/gtwcmmdura.html

Ruby: Marshal.dump(obj)
来源：http://dali.shuidangran.top/Article/details/gtifhouqae.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.dashuyun.cn/Article/details/gtjtgustrv.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtabxdnpqo.html

L. 网络请求
来源：http://dali.c1oappe.top/Article/details/gtotxophlo.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtuoysupzw.html

[L01] 发送 GET 请求
来源：http://dali.sufxvd.cn/Article/details/gttygpbesd.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.gotoacloud.top/Article/details/gtfluwjviw.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.fengsongda.top/Article/details/gtmwzltplz.html

JS:   await fetch(url)
来源：http://dali.xuanzx.com/Article/details/gtwhygxmhx.html

TS:   await fetch(url)
来源：http://dali.jlsjyb.cn/Article/details/gtrzpuhhyc.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.sxryk.cn/Article/details/gteoqrdftj.html

Go:   resp, err := http.Get(url)
来源：http://dali.nwbrower.top/Article/details/gtciwupmoh.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.hongshengwenyu.top/Article/details/gtoypgvodl.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.cqqwz.cn/Article/details/gtcuncbeot.html

[L02] 发送 POST JSON
来源：http://dali.shzxlz.cn/Article/details/gtjeyjvtvp.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jqgfzy.top/Article/details/gtvmfsnsku.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.tanke756.top/Article/details/gthdrbbpvo.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinyuanbaomall.cn/Article/details/gthhkncjbj.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ydzc1.top/Article/details/gtmzmyfpmo.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.ydzc1.top/Article/details/gtamauhflg.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.gogol.net.cn/Article/details/gtqdmrzjur.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yj20258.top/Article/details/gtshftsrud.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.tianlin.xyz/Article/details/gtbvbsvwdj.html

[L03] 设置自定义请求头
来源：http://dali.wangshuangyany.cn/Article/details/gtfqapcuut.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.hongshengwenyu.top/Article/details/gtgazgcjlt.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yanxiufei.cn/Article/details/gtrrlrulno.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yuanzhike.top/Article/details/gtiaivruba.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.feifeiyinyue.top/Article/details/gtvqdotjqn.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yueranfly.top/Article/details/gturcopghl.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.9152youxi.cn/Article/details/gtwuzjsled.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.sysykeji.top/Article/details/gtfwogxhnn.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.chenzaomai.com/Article/details/gtvwvyiilz.html

[L04] 设置超时
来源：http://dali.hnqzz.top/Article/details/gtguwghkip.html

Py:   requests.get(url, timeout=5)
来源：http://dali.birdmap.top/Article/details/gtuohhsefi.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.haohaochexian.top/Article/details/gtrphhozqd.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ivvv.top/Article/details/gtimxreldm.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yuxming.cn/Article/details/gtxlvvuupu.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yuanzhike.top/Article/details/gtottlvkch.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jyoumei.cn/Article/details/gtyzcmbimz.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.sysykeji.top/Article/details/gtvgrhfkta.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.cqqwz.cn/Article/details/gtsnhowmxk.html

[L05] 上传文件（multipart）
来源：http://dali.haohaochexian.top/Article/details/gtlfqgxhbr.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.shangyingyoupin.top/Article/details/gtrnlotywl.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.cashguo.top/Article/details/gtzzudxflz.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.hnqzz.top/Article/details/gtttqjpmfa.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.ivvv.top/Article/details/gtvzwopkcw.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.xylfe.cn/Article/details/gtwrnkwmvm.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhixingplan.top/Article/details/gtckpkotqg.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.daria6918.cn/Article/details/gtcvwkbntr.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.svipenyu.cn/Article/details/gtkaqmnwqt.html

[L06] 解析响应为 JSON
来源：http://dali.yanxiufei.cn/Article/details/gtypqkaluo.html

Py:   resp.json()
来源：http://dali.pycfn.com/Article/details/gttvocvfdw.html

PHP:  json_decode($body, true);
来源：http://dali.yj20258.top/Article/details/gtzczwyuck.html

JS:   await resp.json()
来源：http://dali.redwolf501.top/Article/details/gtfplpyjgd.html

TS:   await resp.json()
来源：http://dali.chenzaomai.com/Article/details/gtksoqrzvb.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jinqigfzy.top/Article/details/gtuakcgtib.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.bjfxy.top/Article/details/gtwydjvakh.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yj20258.top/Article/details/gtlnqykavu.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.cqqwz.cn/Article/details/gtglttzixr.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhoulong.xyz/Article/details/gtmbufxmpy.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jqgfzy.top/Article/details/gtzbxalbod.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.fzhhl.top/Article/details/gtkkyyczdq.html

JS:   resp.ok;  resp.status
来源：http://dali.yj202588.top/Article/details/gtlgkoxsdq.html

TS:   resp.ok;  resp.status
来源：http://dali.cheryme.top/Article/details/gtloksebni.html

Java: resp.statusCode()
来源：http://dali.cheryme.top/Article/details/gterhxosti.html

Go:   resp.StatusCode
来源：http://dali.shuidangran.top/Article/details/gtmzzjrben.html

Ruby: resp.code.to_i
来源：http://dali.chenjidiqi.icu/Article/details/gtruwfvjas.html

C#:   (int)resp.StatusCode
来源：http://dali.xuanzx.com/Article/details/gtibxacldu.html

[L08] 并发请求多个地址
来源：http://dali.fengsongda.top/Article/details/gtkpwduppt.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.pycfn.com/Article/details/gtoykdwpyj.html

PHP:  curl_multi_init() 系列
来源：http://dali.jianghu66.top/Article/details/gtgmzylssp.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ehwqpu.com/Article/details/gtyauhzgni.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ehwqpu.com/Article/details/gticptyuok.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.sufxvd.cn/Article/details/gtapxgnmei.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jinqigfzy.top/Article/details/gttxyoderu.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.0kj1m.cn/Article/details/gtsslpdezc.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.wangdashe.top/Article/details/gtjntsgenj.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtatcixxpx.html

M. 命令行 / 进程 / 环境
来源：http://dali.vqdsnc.cn/Article/details/gtkgouzpfr.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtwusxxiwu.html

[M01] 读取命令行参数
来源：http://dali.ppjwa.cn/Article/details/gtruxmggwm.html

Py:   sys.argv[1:]
来源：http://dali.xuanzx.com/Article/details/gtjbjctufx.html

PHP:  $argv;  $argc;
来源：http://dali.c1oappe.top/Article/details/gtvzcxcaci.html

JS:   process.argv.slice(2)
来源：http://dali.zhoulong.xyz/Article/details/gtilbdagwn.html

TS:   process.argv.slice(2)
来源：http://dali.gotoacloud.top/Article/details/gtkjhjdrht.html

Java: args 数组（main 方法参数）
来源：http://dali.tanke756.top/Article/details/gtkhjkqcag.html

Go:   os.Args[1:]
来源：http://dali.jyoumei.cn/Article/details/gtolypctlf.html

Ruby: ARGV
来源：http://dali.hysaishi.cn/Article/details/gtziqgbpvm.html

C#:   args 数组（Main 方法参数）
来源：http://dali.cqqwz.cn/Article/details/gtppelfjzk.html

[M02] 读取环境变量
来源：http://dali.dashuyun.cn/Article/details/gtwaszkvtj.html

Py:   os.environ.get("HOME")
来源：http://dali.zhoulong.xyz/Article/details/gtndxnigfq.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.feifeiyinyue.top/Article/details/gtfxiffswk.html

JS:   process.env.HOME
来源：http://dali.zdqjudy.top/Article/details/gtkxsmuhud.html

TS:   process.env.HOME
来源：http://dali.wangshuangyany.cn/Article/details/gtrluswkmo.html

Java: System.getenv("HOME")
来源：http://dali.dashuyun.cn/Article/details/gtujbkmlqr.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.sufxvd.cn/Article/details/gtxbzrqbnj.html

Ruby: ENV["HOME"]
来源：http://dali.ppjwa.cn/Article/details/gtydbqshiq.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.nanxinkj.top/Article/details/gtdypcotfv.html

[M03] 执行外部命令
来源：http://dali.jlsjyb.cn/Article/details/gtgwzryftv.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.yj202588.top/Article/details/gtsttzqean.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.9152youxi.cn/Article/details/gturkyliyr.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.xuanzx.com/Article/details/gtlwcbhhha.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.birdmap.top/Article/details/gtmkpwghfv.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.hywenlv.cn/Article/details/gtwxmigilo.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhoulong.xyz/Article/details/gtinfsgpvn.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.daria6918.cn/Article/details/gtttxaqdjh.html

C#:   Process.Start("ls", "-l");
来源：http://dali.shzxlz.cn/Article/details/gtnsufezou.html

[M04] 获取当前工作目录
来源：http://dali.sysykeji.top/Article/details/gtjlkcwmgs.html

Py:   os.getcwd()
来源：http://dali.xuanzx.com/Article/details/gtsfktwvux.html

PHP:  getcwd();
来源：http://dali.jiagoushi.top/Article/details/gtzlsqsaod.html

JS:   process.cwd()
来源：http://dali.birdmap.top/Article/details/gtfaknesqw.html

TS:   process.cwd()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnmfkyduk.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.dianchejie.cn/Article/details/gtqbtphbnr.html

Go:   os.Getwd()
来源：http://dali.gotoacloud.top/Article/details/gtbagogkks.html

Ruby: Dir.pwd
来源：http://dali.wangdashe.top/Article/details/gtybicdakf.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.gotoacloud.top/Article/details/gtonblymvq.html

[M05] 设置退出码
来源：http://dali.meibo888.top/Article/details/gtlhyzvkzs.html

Py:   sys.exit(1)
来源：http://dali.nanxuanxn.top/Article/details/gtgwafytkp.html

PHP:  exit(1);
来源：http://dali.havefunace.top/Article/details/gtlmaeodzt.html

JS:   process.exit(1)
来源：http://dali.dashuyun.cn/Article/details/gtbgcthagp.html

TS:   process.exit(1)
来源：http://dali.nanxuanxn.top/Article/details/gtqarvquxp.html

Java: System.exit(1)
来源：http://dali.redwolf501.top/Article/details/gtfzmlkjix.html

Go:   os.Exit(1)
来源：http://dali.hywenlv.cn/Article/details/gtuktrdwko.html

Ruby: exit 1
来源：http://dali.pengpengdd.cyou/Article/details/gtqwcorhxl.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.hywenlv.cn/Article/details/gtepqvvzcw.html

[M06] 向标准错误输出
来源：http://dali.hongshengwenyu.top/Article/details/gtqxalqvcn.html

Py:   print("err", file=sys.stderr)
来源：http://dali.kuanghao11.cn/Article/details/gtcaiyvyme.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yj20258.top/Article/details/gtskvvdyyi.html

JS:   console.error("err")
来源：http://dali.yonumen.top/Article/details/gtqmohrxqv.html

TS:   console.error("err")
来源：http://dali.jyoumei.cn/Article/details/gtfmpnfeej.html

Java: System.err.println("err")
来源：http://dali.xziqi.cn/Article/details/gtgcmquhek.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yuxming.cn/Article/details/gteqfqshbw.html

Ruby: warn "err"
来源：http://dali.sufxvd.cn/Article/details/gtbvdorlze.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.chenjidiqi.icu/Article/details/gtcdhafsis.html

[M07] 判断是否为主入口
来源：http://dali.haohaochexian.top/Article/details/gtbadlyfmm.html

Py:   if __name__ == "__main__":
来源：http://dali.yangfankeji.com/Article/details/gtbozlcmvq.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.snrcjt.cn/Article/details/gtgufqegik.html

JS:   require.main === module
来源：http://dali.gogol.net.cn/Article/details/gtcjqpatep.html

TS:   require.main === module
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthbokiggj.html

Java: public static void main(String[] args)
来源：http://dali.nanxuanxn.top/Article/details/gtcxzrgadb.html

Go:   func main()
来源：http://dali.ivvv.top/Article/details/gtzwptsaqy.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhongyouzk.top/Article/details/gtvuusxopj.html

C#:   static void Main(string[] args)
来源：http://dali.nanxuanxn.top/Article/details/gtrcpejkkr.html

[M08] 获取系统与运行时信息
来源：http://dali.daria6918.cn/Article/details/gtixthfujt.html

Py:   platform.system();  platform.python_version()
来源：http://dali.tanke756.top/Article/details/gtkxgcgovi.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.chenzaomai.com/Article/details/gtgzcelhzp.html

JS:   process.platform;  process.version
来源：http://dali.zdqjudy.top/Article/details/gtjovomtvy.html

TS:   process.platform;  process.version
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbpcuihpz.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.cqqwz.cn/Article/details/gtpzzjucsw.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yj20258.top/Article/details/gtliowrucy.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yanxiufei.cn/Article/details/gtudrwgfhj.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yueranfly.top/Article/details/gtedhrkbgm.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtyrediunu.html

N. 数据结构与算法
来源：http://dali.snrcjt.cn/Article/details/gtosmxplkw.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtehevwrbq.html

[N01] 二分查找（有序数组）
来源：http://dali.yangfankeji.com/Article/details/gtyqnbmgbi.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jinqigufen.top/Article/details/gtmjvxaruy.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.daria6918.cn/Article/details/gtsntubikt.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gogol.net.cn/Article/details/gtnzkzrrrl.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.kuanghao11.cn/Article/details/gtkfnmyanc.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.hammf.cn/Article/details/gtyypqsudc.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgpuhuuou.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.316326.xyz/Article/details/gtgcatmbiu.html


<!-- 参考信息 -->