代发 wailian999

TS:   new Date("2024-01-02")
来源：http://dali.kuanghao11.cn/Article/details/gt2pcbaoyvo.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zdqjudy.top/Article/details/gt2ybssxmvg.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hnxiangtu.top/Article/details/gt2vdooaehs.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.c1oappe.top/Article/details/gt2ccereoxu.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.dashuyun.cn/Article/details/gt2ojbqgyhc.html

[J04] 时间戳与日期互转
来源：http://dali.aizwys.cn/Article/details/gt2stdejelb.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.hysaishi.cn/Article/details/gt2uycktncj.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.snrcjt.cn/Article/details/gt2eqddqonz.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.kuanghao11.cn/Article/details/gt2dkhxvqxm.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.daxiang520.top/Article/details/gt2ryomwbxl.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zycfv.cn/Article/details/gt2tomwvmtj.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhongyouzk.top/Article/details/gt2umxdfliq.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pprldtbp.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.cqqwz.cn/Article/details/gt2wjdxpexa.html

[J05] 时间加减（加 7 天）
来源：http://dali.svipenyu.cn/Article/details/gt2qrqomjym.html

Py:   now + timedelta(days=7)
来源：http://dali.jiagoushi.top/Article/details/gt2gjgdpqsn.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.xylfe.cn/Article/details/gt2aufsoeru.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhixingplan.top/Article/details/gt2syhwtged.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xinyue.icu/Article/details/gt2kssdrgin.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.svipenyu.cn/Article/details/gt2kjhsvvti.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jianghu66.top/Article/details/gt2zxsdicyj.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yuxming.cn/Article/details/gt2vjdudhxo.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.snrcjt.cn/Article/details/gt2bqdppakp.html

[J06] 计算两时间之差
来源：http://dali.tanke756.top/Article/details/gt2wyagnvte.html

Py:   (end - start).total_seconds()
来源：http://dali.xuetiantiany.cn/Article/details/gt2wngtgnky.html

PHP:  $end->diff($start)->days;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zagpjdvo.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.aizwys.cn/Article/details/gt2fuiecffz.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.tianlin.xyz/Article/details/gt2fenbqtgj.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.fengsongda.top/Article/details/gt2kfpnhdvx.html

Go:   end.Sub(start).Hours()
来源：http://dali.ivvv.top/Article/details/gt2fcymtjir.html

Ruby: end - start                 # 返回秒数
来源：http://dali.hongshengwenyu.top/Article/details/gt2oecrmjji.html

C#:   (end - start).TotalSeconds
来源：http://dali.yanxiufei.cn/Article/details/gt2blipfgtl.html

[J07] 比较两个日期
来源：http://dali.jinqigfzy.top/Article/details/gt2swgxzttu.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.xinyue.icu/Article/details/gt2hxkjxbrt.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.nwbrower.top/Article/details/gt2gnuxzmky.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.sxryk.cn/Article/details/gt2kdkekqot.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.wangshuangyany.cn/Article/details/gt2xwceoqrk.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.nanxuanxn.top/Article/details/gt2xkbaosfc.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.nwbrower.top/Article/details/gt2qpgyovuq.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jqgufenzy.top/Article/details/gt2shqdkrgv.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.xylfe.cn/Article/details/gt2olvzwszu.html

[J08] 提取年月日与星期
来源：http://dali.9152youxi.cn/Article/details/gt2jrdkuacz.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.ppjwa.cn/Article/details/gt2jrbivvpw.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.cheryme.top/Article/details/gt2wycglqzh.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jlsjyb.cn/Article/details/gt2xpzwqumt.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.gogol.net.cn/Article/details/gt2jxpalctg.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zycfv.cn/Article/details/gt2glurvcvb.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.haohaochexian.top/Article/details/gt2ufndqbyb.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.ppjwa.cn/Article/details/gt2tkfqlwun.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.xylfe.cn/Article/details/gt2bfdnzsnp.html

[J09] 时区处理
来源：http://dali.mhx1999.top/Article/details/gt2ithjhwol.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.cashguo.top/Article/details/gt2pydflxnd.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yonumen.top/Article/details/gt2xrnfkemx.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.guannengcc.top/Article/details/gt2zkrbrymh.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.sweek.top/Article/details/gt2uaglkoaa.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.shuidangran.top/Article/details/gt2iqdynhfd.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jianghu66.top/Article/details/gt2qsmhiekg.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.fzhhl.top/Article/details/gt2hfmtefen.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.shuidangran.top/Article/details/gt2kelnziby.html

[J10] 取今天 / 本月第一天
来源：http://dali.ppjwa.cn/Article/details/gt2cmhnvprn.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.nanxinkj.top/Article/details/gt2ogxyjanf.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jqgfzy.top/Article/details/gt2zxbftnxg.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.fengsongda.top/Article/details/gt2uxkwypoi.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.snrcjt.cn/Article/details/gt2nqpgiynu.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.cdnleiting.top/Article/details/gt2lojylfvq.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.hongshengwenyu.top/Article/details/gt2qkbllllu.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.nanxuanxn.top/Article/details/gt2txsahwqt.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.birdmap.top/Article/details/gt2mwehtlqg.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2ihpmekja.html

K. JSON 与序列化
来源：http://dali.birdmap.top/Article/details/gt2cztzeavc.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2jdipwyii.html

[K01] 对象转 JSON 字符串
来源：http://dali.daria6918.cn/Article/details/gt2twmbsizy.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhijiandao.cn/Article/details/gt2miqhnidt.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.gotoacloud.top/Article/details/gt2kzkeelud.html

JS:   JSON.stringify(obj)
来源：http://dali.gogol.net.cn/Article/details/gt2ccdaeuuv.html

TS:   JSON.stringify(obj)
来源：http://dali.smart0.xyz/Article/details/gt2pworetym.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.fengsongda.top/Article/details/gt2blxcrxna.html

Go:   json.Marshal(obj)
来源：http://dali.hammf.cn/Article/details/gt2dbvxbimf.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.snrcjt.cn/Article/details/gt2dzpstcpj.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhengqikj.top/Article/details/gt2nepibitf.html

[K02] JSON 字符串转对象
来源：http://dali.fengsongda.top/Article/details/gt2kbvsotmk.html

Py:   json.loads(s)
来源：http://dali.jqgfzy.top/Article/details/gt2gwxmkjnd.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhiwuduotai.top/Article/details/gt2xxzsmuqi.html

JS:   JSON.parse(s)
来源：http://dali.9152youxi.cn/Article/details/gt2zpatazcj.html

TS:   JSON.parse(s)
来源：http://dali.c1oappe.top/Article/details/gt2wbuewltb.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.zhixingplan.top/Article/details/gt2deqkhhra.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.xinyue.icu/Article/details/gt2ouxyvxmy.html

Ruby: JSON.parse(s)
来源：http://dali.ivvv.top/Article/details/gt2uyjhdgvb.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.cqqwz.cn/Article/details/gt2fxgxvnjx.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.sxryk.cn/Article/details/gt2cjwequnz.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.smart0.xyz/Article/details/gt2afrqnioy.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.yongpay.top/Article/details/gt2pmibihlg.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.smart0.xyz/Article/details/gt2jmtcxiyz.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhixingplan.top/Article/details/gt2enuaodsv.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.ppjwa.cn/Article/details/gt2njyorswg.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.mhx1999.top/Article/details/gt2lnqbfytt.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.ybcxt.top/Article/details/gt2fztnygir.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yj20258888.top/Article/details/gt2kejhwcpf.html

[K04] 读取 JSON 文件
来源：http://dali.c1oappe.top/Article/details/gt2srpelcsv.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.shuidangran.top/Article/details/gt2avmntuhn.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yj202588.top/Article/details/gt2uomgrhwb.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2usmkikby.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xylfe.cn/Article/details/gt2tvtnxdst.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.chenzaomai.com/Article/details/gt2mwamyofk.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.smart0.xyz/Article/details/gt2jzbaydgz.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.sysykeji.top/Article/details/gt2lhzihldi.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yongpay.top/Article/details/gt2acpvcdfr.html

[K05] 深拷贝对象
来源：http://dali.aizwys.cn/Article/details/gt2zarbfszo.html

Py:   copy.deepcopy(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sxqbnril.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yj202588.top/Article/details/gt2alwlaypf.html

JS:   structuredClone(obj)
来源：http://dali.zycfv.cn/Article/details/gt2khlqwmre.html

TS:   structuredClone(obj)
来源：http://dali.cdnleiting.top/Article/details/gt2lxguwstf.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.fengsongda.top/Article/details/gt2hcxwdnac.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jlsjyb.cn/Article/details/gt2gxaoypxz.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.nwbrower.top/Article/details/gt2pwxclqpq.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.fengsongda.top/Article/details/gt2mexdbopu.html

[K06] 解析 URL 查询串
来源：http://dali.yueranfly.top/Article/details/gt2ndgijgtd.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.ivvv.top/Article/details/gt2pkgwylfj.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.gzhubu.top/Article/details/gt2tqlmwlcv.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fszrlqej.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.bjfxy.top/Article/details/gt2hkalfxcw.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jinqigfzy.top/Article/details/gt2hwwohjfh.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yj20258.top/Article/details/gt2xbkensdo.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yj202588.top/Article/details/gt2sypexttr.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.haohaochexian.top/Article/details/gt2klufcqni.html

[K07] 进制转换
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xnzrryiq.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yueranfly.top/Article/details/gt2ujwhkvet.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.vqdsnc.cn/Article/details/gt2ooineibn.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.havefunace.top/Article/details/gt2xflezgoi.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.dianchejie.cn/Article/details/gt2uiydytqq.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.xinyue.icu/Article/details/gt2yuccdfei.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.nwbrower.top/Article/details/gt2aoxcndaz.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yanxiufei.cn/Article/details/gt2uuxvgwyb.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.kuanghao11.cn/Article/details/gt2vgploooy.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.jianghu66.top/Article/details/gt2vjyrfxly.html

Py:   pickle.dumps(obj)
来源：http://dali.9152youxi.cn/Article/details/gt2lfdwwjyl.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.cucudq.cn/Article/details/gt2vhlctwmb.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.gaohongyu789.top/Article/details/gt2hmwqqnjp.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zycfv.cn/Article/details/gt2bxbpynls.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jqgufenzy.top/Article/details/gt2nmvgdotx.html

Go:   encoding/gob
来源：http://dali.hywenlv.cn/Article/details/gt2uxgzuedu.html

Ruby: Marshal.dump(obj)
来源：http://dali.sysykeji.top/Article/details/gt2jocmnzoe.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.xuetiantiany.cn/Article/details/gt2nxnprufo.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2yeepualn.html

L. 网络请求
来源：http://dali.hywenlv.cn/Article/details/gt2uqeqwvru.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2kymbinvy.html

[L01] 发送 GET 请求
来源：http://dali.yongpay.top/Article/details/gt2fccrhcsw.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.fengsongda.top/Article/details/gt2fmoukodn.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.feifeiyinyue.top/Article/details/gt2fvhbnopi.html

JS:   await fetch(url)
来源：http://dali.dianchejie.cn/Article/details/gt2scjkoytd.html

TS:   await fetch(url)
来源：http://dali.nanxinkj.top/Article/details/gt2bhmtczcz.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.0kj1m.cn/Article/details/gt2jmykfzsx.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhengqikj.top/Article/details/gt2mjsswhgk.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yueranfly.top/Article/details/gt2nmtyklwd.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.ehwqpu.com/Article/details/gt2rcfmuncu.html

[L02] 发送 POST JSON
来源：http://dali.jlsjyb.cn/Article/details/gt2krtunoxe.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.fengsongda.top/Article/details/gt2qhfbwhnk.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jqgfzy.top/Article/details/gt2jsiunqfn.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.mhx1999.top/Article/details/gt2efssekff.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.nwbrower.top/Article/details/gt2flmzzvtm.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.ydzc1.top/Article/details/gt2wxtlpmgl.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fqchingf.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.cqqwz.cn/Article/details/gt2yokbgsti.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.nwbrower.top/Article/details/gt2jzzirqpt.html

[L03] 设置自定义请求头
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yogvoted.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.xziqi.cn/Article/details/gt2gjcjcdhp.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.xziqi.cn/Article/details/gt2tbfnlzte.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.guowangkeji.top/Article/details/gt2lultplnl.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.sweek.top/Article/details/gt2kngoqaux.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.ehwqpu.com/Article/details/gt2cyoxvquy.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.quarkkingdee.top/Article/details/gt2bdffpyof.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.nanxuanxn.top/Article/details/gt2bwfvcquk.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.haohaochexian.top/Article/details/gt2gfmsmbsb.html

[L04] 设置超时
来源：http://dali.fengsongda.top/Article/details/gt2brooqxld.html

Py:   requests.get(url, timeout=5)
来源：http://dali.andypj.xyz/Article/details/gt2dbzldvyp.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.ydzc1.top/Article/details/gt2urjztidg.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.hnqzz.top/Article/details/gt2bytccioh.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.c1oappe.top/Article/details/gt2yjiylask.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.xuanzx.com/Article/details/gt2siyefeqg.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.chenzaomai.com/Article/details/gt2rllxmzmn.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.nanxinkj.top/Article/details/gt2igxfszna.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.bjfxy.top/Article/details/gt2ulqfadqq.html

[L05] 上传文件（multipart）
来源：http://dali.jinqigufen.top/Article/details/gt2xbopimkr.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.cashguo.top/Article/details/gt2huoqvjuq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.dashuyun.cn/Article/details/gt2lvmjgvdp.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.meibo888.top/Article/details/gt2gnwtwknj.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.havefunace.top/Article/details/gt2iirnxlgs.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jianghu66.top/Article/details/gt2tzjtpbjs.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mbrjagkk.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yongpay.top/Article/details/gt2hcydovqa.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2fkgwmsrf.html

[L06] 解析响应为 JSON
来源：http://dali.zdqjudy.top/Article/details/gt2mawtryan.html

Py:   resp.json()
来源：http://dali.jqgfzy.top/Article/details/gt2tckbsbme.html

PHP:  json_decode($body, true);
来源：http://dali.hysaishi.cn/Article/details/gt2bhrtzxyy.html

JS:   await resp.json()
来源：http://dali.hnqzz.top/Article/details/gt2djxuxpro.html

TS:   await resp.json()
来源：http://dali.zhixingplan.top/Article/details/gt2mxzvcylz.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.svipenyu.cn/Article/details/gt2lwbzzoep.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eiyylucc.html

Ruby: JSON.parse(resp.body)
来源：http://dali.vqdsnc.cn/Article/details/gt2wzrrnofi.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.dashuyun.cn/Article/details/gt2qjmvadqq.html

[L07] 处理 HTTP 状态码
来源：http://dali.yuanzhike.top/Article/details/gt2rvivwdml.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.gogol.net.cn/Article/details/gt2estirprv.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yuanzhike.top/Article/details/gt2tgrwbxhb.html

JS:   resp.ok;  resp.status
来源：http://dali.zhengqikj.top/Article/details/gt2ntzpemoy.html

TS:   resp.ok;  resp.status
来源：http://dali.sysykeji.top/Article/details/gt2vtdfvdfg.html

Java: resp.statusCode()
来源：http://dali.xinyue.icu/Article/details/gt2tmxtgkci.html

Go:   resp.StatusCode
来源：http://dali.nwbrower.top/Article/details/gt2mpxnmmzj.html

Ruby: resp.code.to_i
来源：http://dali.pengpengdd.cyou/Article/details/gt2gmactihc.html

C#:   (int)resp.StatusCode
来源：http://dali.c1oappe.top/Article/details/gt2oshicwem.html

[L08] 并发请求多个地址
来源：http://dali.hfpthk.cn/Article/details/gt2wbugppuw.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.hammf.cn/Article/details/gt2yzamgtln.html

PHP:  curl_multi_init() 系列
来源：http://dali.316326.xyz/Article/details/gt2twpjrsmd.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.andypj.xyz/Article/details/gt2bnhnqhjn.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xinyue.icu/Article/details/gt2xcgzkgaj.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.shanyushiyangtech.top/Article/details/gt2srumjhmt.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jlsjyb.cn/Article/details/gt2txyqiaae.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.316326.xyz/Article/details/gt2krhypyfm.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.ydzc1.top/Article/details/gt2hnjwprkr.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2lwuuaupx.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhengqikj.top/Article/details/gt2xekfcbpe.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2qbnoalce.html

[M01] 读取命令行参数
来源：http://dali.yongpay.top/Article/details/gt2kjgygtit.html

Py:   sys.argv[1:]
来源：http://dali.hammf.cn/Article/details/gt2eedwnomw.html

PHP:  $argv;  $argc;
来源：http://dali.zhengqikj.top/Article/details/gt2wukbcgyl.html

JS:   process.argv.slice(2)
来源：http://dali.zdqjudy.top/Article/details/gt2dzpoivjs.html

TS:   process.argv.slice(2)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ttnmzxpf.html

Java: args 数组（main 方法参数）
来源：http://dali.pengpengdd.cyou/Article/details/gt2lscjjgjb.html

Go:   os.Args[1:]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bbluiibk.html

Ruby: ARGV
来源：http://dali.sufxvd.cn/Article/details/gt2dphcjkpx.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yanxiufei.cn/Article/details/gt2uemkaplr.html

[M02] 读取环境变量
来源：http://dali.316326.xyz/Article/details/gt2ocgicled.html

Py:   os.environ.get("HOME")
来源：http://dali.aizwys.cn/Article/details/gt2lhnzmyeu.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.aibaodan.cn/Article/details/gt2tlaswmwo.html

JS:   process.env.HOME
来源：http://dali.wangdashe.top/Article/details/gt2fcrgabty.html

TS:   process.env.HOME
来源：http://dali.sxryk.cn/Article/details/gt2vzkwshmg.html

Java: System.getenv("HOME")
来源：http://dali.andypj.xyz/Article/details/gt2ljpabcwf.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.cqqwz.cn/Article/details/gt2gfibefhk.html

Ruby: ENV["HOME"]
来源：http://dali.jianghu66.top/Article/details/gt2shdukhnm.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.mhx1999.top/Article/details/gt2nlknxdtq.html

[M03] 执行外部命令
来源：http://dali.9152youxi.cn/Article/details/gt2yhjktque.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.quarkkingdee.top/Article/details/gt2dbpuxdqv.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhiwuduotai.top/Article/details/gt2yghmzjht.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhengqikj.top/Article/details/gt2rhufqarj.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.tianlin.xyz/Article/details/gt2nfxnplvg.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.cqqwz.cn/Article/details/gt2mmldzaym.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.nanxuanxn.top/Article/details/gt2vhrnviqw.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zdqjudy.top/Article/details/gt2iukqfieg.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hfpthk.cn/Article/details/gt2pakckwgy.html

[M04] 获取当前工作目录
来源：http://dali.hywenlv.cn/Article/details/gt2cxnwtszo.html

Py:   os.getcwd()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2owukprpt.html

PHP:  getcwd();
来源：http://dali.tianlin.xyz/Article/details/gt2kkofoumd.html

JS:   process.cwd()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cqzdutte.html

TS:   process.cwd()
来源：http://dali.meibo888.top/Article/details/gt2ejnbpifl.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.dianchejie.cn/Article/details/gt2jxnwqiij.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2wrnqcsgq.html

Ruby: Dir.pwd
来源：http://dali.hywenlv.cn/Article/details/gt2zvjeiihz.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.daria6918.cn/Article/details/gt2tklmotev.html

[M05] 设置退出码
来源：http://dali.sweek.top/Article/details/gt2ihshvuzy.html

Py:   sys.exit(1)
来源：http://dali.vqdsnc.cn/Article/details/gt2mjswdecl.html

PHP:  exit(1);
来源：http://dali.yongpay.top/Article/details/gt2whhkairn.html

JS:   process.exit(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rqrttqdy.html

TS:   process.exit(1)
来源：http://dali.aizwys.cn/Article/details/gt2ftobqfnn.html

Java: System.exit(1)
来源：http://dali.redwolf501.top/Article/details/gt2eupuxida.html

Go:   os.Exit(1)
来源：http://dali.gotoacloud.top/Article/details/gt2cczvfzkr.html

Ruby: exit 1
来源：http://dali.sxryk.cn/Article/details/gt2ozoufrgd.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.dashuyun.cn/Article/details/gt2awxeqlno.html

[M06] 向标准错误输出
来源：http://dali.hywenlv.cn/Article/details/gt2hgequnxj.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jlsjyb.cn/Article/details/gt2tmrjktsx.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.gaohongyu789.top/Article/details/gt2cdjgsqtm.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2dwjnzaot.html

TS:   console.error("err")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kuikqray.html

Java: System.err.println("err")
来源：http://dali.sysykeji.top/Article/details/gt2fajilgmh.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.quarkkingdee.top/Article/details/gt2qfkepndb.html

Ruby: warn "err"
来源：http://dali.nanxuanxn.top/Article/details/gt2dkloufzi.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.quarkkingdee.top/Article/details/gt2ohsfqqgg.html

[M07] 判断是否为主入口
来源：http://dali.chenlongwang.top/Article/details/gt2fvsougww.html

Py:   if __name__ == "__main__":
来源：http://dali.hongshengwenyu.top/Article/details/gt2bdwixvlo.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jyoumei.cn/Article/details/gt2lybamsfu.html

JS:   require.main === module
来源：http://dali.xziqi.cn/Article/details/gt2tgidwfng.html

TS:   require.main === module
来源：http://dali.cucudq.cn/Article/details/gt2tnkmohps.html

Java: public static void main(String[] args)
来源：http://dali.redwolf501.top/Article/details/gt2ymgwfaio.html

Go:   func main()
来源：http://dali.iojbl.cn/Article/details/gt2aiexyjsp.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ayvarpec.html

C#:   static void Main(string[] args)
来源：http://dali.gogol.net.cn/Article/details/gt2qteplusn.html

[M08] 获取系统与运行时信息
来源：http://dali.shangyingyoupin.top/Article/details/gt2dzqbhhau.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yuxming.cn/Article/details/gt2ryjksebp.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.meibo888.top/Article/details/gt2fpsgessa.html

JS:   process.platform;  process.version
来源：http://dali.gaohongyu789.top/Article/details/gt2xqaywglw.html

TS:   process.platform;  process.version
来源：http://dali.sweek.top/Article/details/gt2dhynhgal.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.kuanghao11.cn/Article/details/gt2vwmmtgbp.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2dhigicyr.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bodskluk.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.0kj1m.cn/Article/details/gt2inzikojr.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2uaypsoht.html

N. 数据结构与算法
来源：http://dali.aibaodan.cn/Article/details/gt2aaixtyff.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2ksbhbhzy.html

[N01] 二分查找（有序数组）
来源：http://dali.ybcxt.top/Article/details/gt2rytudnie.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.cqqwz.cn/Article/details/gt2irtgxyrw.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.hysaishi.cn/Article/details/gt2hegiuyxo.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhongyouzk.top/Article/details/gt2wrdekquy.html


<!-- 参考信息 -->