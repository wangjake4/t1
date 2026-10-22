代发 wailian999

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.shzxlz.cn/Article/details/gt2txfvtnur.html

[J04] 时间戳与日期互转
来源：http://dali.sufxvd.cn/Article/details/gt2rfyubunh.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.hywenlv.cn/Article/details/gt2nvmmprmt.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yangfankeji.com/Article/details/gt2wujqejdi.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.fengsongda.top/Article/details/gt2bpnfwxih.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.fzhhl.top/Article/details/gt2arcdtkqt.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jqgufenzy.top/Article/details/gt2raqmtdof.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.sysykeji.top/Article/details/gt2xbgyvplq.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.aizwys.cn/Article/details/gt2tozgazws.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.pengpengdd.cyou/Article/details/gt2auiafiri.html

[J05] 时间加减（加 7 天）
来源：http://dali.xuetiantiany.cn/Article/details/gt2vhtzpfdi.html

Py:   now + timedelta(days=7)
来源：http://dali.kuanghao11.cn/Article/details/gt2dwchhuaf.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uemqhhph.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shuidangran.top/Article/details/gt2qzcpopno.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.pengpengdd.cyou/Article/details/gt2kvxbiwuj.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ijnqrloe.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.aibaodan.cn/Article/details/gt2jsrzpmsq.html

Ruby: Time.now + 7 * 86400
来源：http://dali.andypj.xyz/Article/details/gt2rdnciqln.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.smart0.xyz/Article/details/gt2akdtouwv.html

[J06] 计算两时间之差
来源：http://dali.9152youxi.cn/Article/details/gt2padmitoh.html

Py:   (end - start).total_seconds()
来源：http://dali.yanxiufei.cn/Article/details/gt2pnisztgl.html

PHP:  $end->diff($start)->days;
来源：http://dali.daxiang520.top/Article/details/gt2aqrrwvpq.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.wangshuangyany.cn/Article/details/gt2xnyhutlc.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.nwbrower.top/Article/details/gt2ygefadqb.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.kuanghao11.cn/Article/details/gt2yzjcnzcd.html

Go:   end.Sub(start).Hours()
来源：http://dali.jinqigufen.top/Article/details/gt2ezobiage.html

Ruby: end - start                 # 返回秒数
来源：http://dali.cdnleiting.top/Article/details/gt2jarbcacl.html

C#:   (end - start).TotalSeconds
来源：http://dali.jinqigufen.top/Article/details/gt2hxfyzxjk.html

[J07] 比较两个日期
来源：http://dali.hywenlv.cn/Article/details/gt2qorcwund.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.tanke756.top/Article/details/gt2ohkteawr.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.wangshuangyany.cn/Article/details/gt2qinvfpsg.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhixingplan.top/Article/details/gt2jjzirgeh.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.tian-w.cn/Article/details/gt2xuyunvci.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.cdnleiting.top/Article/details/gt2nhuuxvmd.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.snrcjt.cn/Article/details/gt2dcrigmad.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jqgufenzy.top/Article/details/gt2syzvzbwd.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ywtsqwkb.html

[J08] 提取年月日与星期
来源：http://dali.tian-w.cn/Article/details/gt2tcpfxjnd.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.bjfxy.top/Article/details/gt2cagamvdk.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.xuetiantiany.cn/Article/details/gt2wedomrjv.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yj202588.top/Article/details/gt2zhedckzd.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.tanke756.top/Article/details/gt2shkfjyxj.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.sysykeji.top/Article/details/gt2qvqcbvyo.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hysaishi.cn/Article/details/gt2vshifrqu.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yonumen.top/Article/details/gt2zoxgbqwi.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hlixyqgp.html

[J09] 时区处理
来源：http://dali.chenzaomai.com/Article/details/gt2xdiacnal.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.sufxvd.cn/Article/details/gt2jwnnctqb.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.sysykeji.top/Article/details/gt2epnbthmr.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.nwbrower.top/Article/details/gt2mrtagtav.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.sysykeji.top/Article/details/gt2hbronqal.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.daria6918.cn/Article/details/gt2acdoghlk.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yonumen.top/Article/details/gt2vigyvcpu.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jqgufenzy.top/Article/details/gt2lumpcfbl.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.hnqzz.top/Article/details/gt2ritlppap.html

[J10] 取今天 / 本月第一天
来源：http://dali.fengsongda.top/Article/details/gt2lwwwtyjv.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.meibo888.top/Article/details/gt2jhlupuha.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yj20258.top/Article/details/gt2kxygerpl.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.0kj1m.cn/Article/details/gt2lvnkrmra.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.ehwqpu.com/Article/details/gt2zjoekmtb.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.redwolf501.top/Article/details/gt2hykqhdzk.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.dianchejie.cn/Article/details/gt2gtkjyrme.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.ehwqpu.com/Article/details/gt2dmkwoymk.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.hywenlv.cn/Article/details/gt2mawblbch.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2tdjdnwfh.html

K. JSON 与序列化
来源：http://dali.sxryk.cn/Article/details/gt2rzsoicfe.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2cwqgyezb.html

[K01] 对象转 JSON 字符串
来源：http://dali.xuanzx.com/Article/details/gt2scwrcoth.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.xziqi.cn/Article/details/gt2yydftdfe.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yuanzhike.top/Article/details/gt2ilkgbvyr.html

JS:   JSON.stringify(obj)
来源：http://dali.xziqi.cn/Article/details/gt2ouzpsffl.html

TS:   JSON.stringify(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oxmcvmkx.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.xuetiantiany.cn/Article/details/gt2jsvpcjch.html

Go:   json.Marshal(obj)
来源：http://dali.nwbrower.top/Article/details/gt2rbfxtgzk.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.andypj.xyz/Article/details/gt2bzsylatv.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.hysaishi.cn/Article/details/gt2aerevlvu.html

[K02] JSON 字符串转对象
来源：http://dali.chenlongwang.top/Article/details/gt2yinryasv.html

Py:   json.loads(s)
来源：http://dali.meibo888.top/Article/details/gt2vfuapjxc.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.daria6918.cn/Article/details/gt2lixeehwh.html

JS:   JSON.parse(s)
来源：http://dali.hnqzz.top/Article/details/gt2zwuqohlq.html

TS:   JSON.parse(s)
来源：http://dali.yangfankeji.com/Article/details/gt2jvqenkrs.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pmeulwmw.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.hnqzz.top/Article/details/gt2jpayuire.html

Ruby: JSON.parse(s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2mjokgpwa.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.zhoulong.xyz/Article/details/gt2cnhwtchg.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mbzezamm.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.9152youxi.cn/Article/details/gt2fcdmuent.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zdqjudy.top/Article/details/gt2mjbjdabt.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.xylfe.cn/Article/details/gt2hgichqvu.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhiwuduotai.top/Article/details/gt2lyhewait.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2czicpcwc.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yangfankeji.com/Article/details/gt2krnmuxvk.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xxlbetyx.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhoulong.xyz/Article/details/gt2vrzmcehm.html

[K04] 读取 JSON 文件
来源：http://dali.guannengcc.top/Article/details/gt2neqqhfmd.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.bjfxy.top/Article/details/gt2pxfpxawu.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mapqrmju.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2risywyar.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yj20258888.top/Article/details/gt2hwvsuaun.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yj20258888.top/Article/details/gt2intkgosh.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.gogol.net.cn/Article/details/gt2lbulskpg.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.shangyingyoupin.top/Article/details/gt2vbsfjcnr.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.316326.xyz/Article/details/gt2aabclmex.html

[K05] 深拷贝对象
来源：http://dali.tanke756.top/Article/details/gt2lvtaocxc.html

Py:   copy.deepcopy(obj)
来源：http://dali.jinqigfzy.top/Article/details/gt2wvfidbbt.html

PHP:  unserialize(serialize($obj));
来源：http://dali.bjfxy.top/Article/details/gt2zaddepoa.html

JS:   structuredClone(obj)
来源：http://dali.yonumen.top/Article/details/gt2syprcwua.html

TS:   structuredClone(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gt2hqvxrtct.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.shangyingyoupin.top/Article/details/gt2fnooeqvr.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.fengsongda.top/Article/details/gt2bcuiymqq.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.chenlongwang.top/Article/details/gt2fiovnyek.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.andypj.xyz/Article/details/gt2fgwvhvep.html

[K06] 解析 URL 查询串
来源：http://dali.aibaodan.cn/Article/details/gt2ehcfdiay.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yvedp.cn/Article/details/gt2lelveobu.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhongyouzk.top/Article/details/gt2cercuzoe.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhongyouzk.top/Article/details/gt2qjykjjpw.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wsknkyaz.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.xuetiantiany.cn/Article/details/gt2xtsasoch.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yonumen.top/Article/details/gt2hitddmwl.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.hnxiangtu.top/Article/details/gt2aztusxlz.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.guowangkeji.top/Article/details/gt2smcmbpeo.html

[K07] 进制转换
来源：http://dali.yuanzhike.top/Article/details/gt2anqmkjom.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.0kj1m.cn/Article/details/gt2xmwdxtkq.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yuxming.cn/Article/details/gt2wszagpjl.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.xziqi.cn/Article/details/gt2yvtovfhp.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.fengsongda.top/Article/details/gt2tzsaadap.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.tian-w.cn/Article/details/gt2vkximaef.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.birdmap.top/Article/details/gt2zlquqtpk.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.feifeiyinyue.top/Article/details/gt2rhcznjgs.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jianghu66.top/Article/details/gt2esjuzupr.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.sysykeji.top/Article/details/gt2tsmjjpvl.html

Py:   pickle.dumps(obj)
来源：http://dali.yj202588.top/Article/details/gt2rnrsbxor.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.xuanzx.com/Article/details/gt2mefhkfwx.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.shzxlz.cn/Article/details/gt2xqbhukqa.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.gzhubu.top/Article/details/gt2pibvbggp.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.xuetiantiany.cn/Article/details/gt2auppcuih.html

Go:   encoding/gob
来源：http://dali.cucudq.cn/Article/details/gt2vmfzsamo.html

Ruby: Marshal.dump(obj)
来源：http://dali.yanxiufei.cn/Article/details/gt2cgyavwvy.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yuxming.cn/Article/details/gt2yhnffqjc.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2lzvvunvs.html

L. 网络请求
来源：http://dali.chenzaomai.com/Article/details/gt2zsvxoyrx.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2ougdfavh.html

[L01] 发送 GET 请求
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ducishji.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jyoumei.cn/Article/details/gt2guefoblj.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.0kj1m.cn/Article/details/gt2qzwtphfx.html

JS:   await fetch(url)
来源：http://dali.hnqzz.top/Article/details/gt2esluuuqz.html

TS:   await fetch(url)
来源：http://dali.andypj.xyz/Article/details/gt2deskkvkq.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.nanxuanxn.top/Article/details/gt2kvxosmgy.html

Go:   resp, err := http.Get(url)
来源：http://dali.yongpay.top/Article/details/gt2xugmbaed.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zdqjudy.top/Article/details/gt2bffqqxcf.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.andypj.xyz/Article/details/gt2actznkke.html

[L02] 发送 POST JSON
来源：http://dali.gogol.net.cn/Article/details/gt2lttoighi.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.fengsongda.top/Article/details/gt2imrmqaqo.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.xuanzx.com/Article/details/gt2jreczocz.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yueranfly.top/Article/details/gt2lhmhnone.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.pycfn.com/Article/details/gt2dvrguupk.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qnlzfrrz.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.xziqi.cn/Article/details/gt2zxskupfe.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.tanke756.top/Article/details/gt2isbawqvd.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yueranfly.top/Article/details/gt2lggjgusf.html

[L03] 设置自定义请求头
来源：http://dali.c1oappe.top/Article/details/gt2smekoupz.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.cdnleiting.top/Article/details/gt2oafiuscs.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.sufxvd.cn/Article/details/gt2xlxxrotg.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jianghu66.top/Article/details/gt2kwveshdi.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cashguo.top/Article/details/gt2ltqjyldc.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.smart0.xyz/Article/details/gt2xmmbsglz.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.ybcxt.top/Article/details/gt2ritbqclc.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yuanzhike.top/Article/details/gt2tnwpitol.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.gzhubu.top/Article/details/gt2dhkjrauo.html

[L04] 设置超时
来源：http://dali.guannengcc.top/Article/details/gt2olfkkghm.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2stcmuslc.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.nwbrower.top/Article/details/gt2bykjixdj.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.nanxuanxn.top/Article/details/gt2gkoolxtm.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jqgfzy.top/Article/details/gt2cgsdoeze.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.hysaishi.cn/Article/details/gt2sxmvazwm.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.316326.xyz/Article/details/gt2qsowbaef.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.meibo888.top/Article/details/gt2ojzrxysp.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhoulong.xyz/Article/details/gt2uledjyku.html

[L05] 上传文件（multipart）
来源：http://dali.jqgufenzy.top/Article/details/gt2vhhhqhmh.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2guffqhmv.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yanxiufei.cn/Article/details/gt2meulqpem.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.andypj.xyz/Article/details/gt2fflytqvd.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.gogol.net.cn/Article/details/gt2pqanhlow.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nrrkfpeh.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.pengpengdd.cyou/Article/details/gt2xaglyain.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.vqdsnc.cn/Article/details/gt2plenmood.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.hysaishi.cn/Article/details/gt2osgilddn.html

[L06] 解析响应为 JSON
来源：http://dali.hywenlv.cn/Article/details/gt2ylfwykof.html

Py:   resp.json()
来源：http://dali.gogol.net.cn/Article/details/gt2xgkxwbhx.html

PHP:  json_decode($body, true);
来源：http://dali.jqgufenzy.top/Article/details/gt2uraxpnze.html

JS:   await resp.json()
来源：http://dali.nanxuanxn.top/Article/details/gt2embhxdzg.html

TS:   await resp.json()
来源：http://dali.sufxvd.cn/Article/details/gt2gtiiibac.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.tanke756.top/Article/details/gt2dcryijpi.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yj20258888.top/Article/details/gt2gsfyajqz.html

Ruby: JSON.parse(resp.body)
来源：http://dali.mhx1999.top/Article/details/gt2zmvqpycy.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zdqjudy.top/Article/details/gt2jyxnonwv.html

[L07] 处理 HTTP 状态码
来源：http://dali.sufxvd.cn/Article/details/gt2gvwergda.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.redwolf501.top/Article/details/gt2aeaddiwb.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhoulong.xyz/Article/details/gt2mkxctmgh.html

JS:   resp.ok;  resp.status
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eylhaznk.html

TS:   resp.ok;  resp.status
来源：http://dali.cucudq.cn/Article/details/gt2imsnmtdu.html

Java: resp.statusCode()
来源：http://dali.wangshuangyany.cn/Article/details/gt2ieoxawmq.html

Go:   resp.StatusCode
来源：http://dali.hnqzz.top/Article/details/gt2rbqrfmsu.html

Ruby: resp.code.to_i
来源：http://dali.sysykeji.top/Article/details/gt2ceqnfvkp.html

C#:   (int)resp.StatusCode
来源：http://dali.xuetiantiany.cn/Article/details/gt2embnzlom.html

[L08] 并发请求多个地址
来源：http://dali.gaohongyu789.top/Article/details/gt2wrpeognk.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.kuanghao11.cn/Article/details/gt2zxxugvbk.html

PHP:  curl_multi_init() 系列
来源：http://dali.daxiang520.top/Article/details/gt2cocfopqr.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2akmoqwtj.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2znlhwajk.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.xziqi.cn/Article/details/gt2szxmgzkp.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yongpay.top/Article/details/gt2xmmnolqo.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zycfv.cn/Article/details/gt2nhpyhgpi.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zdqjudy.top/Article/details/gt2cbuqezkz.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2stnettoi.html

M. 命令行 / 进程 / 环境
来源：http://dali.aibaodan.cn/Article/details/gt2aeefbfwq.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2kcrijysc.html

[M01] 读取命令行参数
来源：http://dali.yuanzhike.top/Article/details/gt2cqkpvcpp.html

Py:   sys.argv[1:]
来源：http://dali.yj20258888.top/Article/details/gt2antofrgr.html

PHP:  $argv;  $argc;
来源：http://dali.dianchejie.cn/Article/details/gt2sxgasmvu.html

JS:   process.argv.slice(2)
来源：http://dali.c1oappe.top/Article/details/gt2lgwsbctf.html

TS:   process.argv.slice(2)
来源：http://dali.yongpay.top/Article/details/gt2gptxzjng.html

Java: args 数组（main 方法参数）
来源：http://dali.yongpay.top/Article/details/gt2vthttonv.html

Go:   os.Args[1:]
来源：http://dali.redwolf501.top/Article/details/gt2bqjjndgn.html

Ruby: ARGV
来源：http://dali.nanxuanxn.top/Article/details/gt2dzgnnvre.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yongpay.top/Article/details/gt2selyebvm.html

[M02] 读取环境变量
来源：http://dali.xziqi.cn/Article/details/gt2elwlohlx.html

Py:   os.environ.get("HOME")
来源：http://dali.jinqigfzy.top/Article/details/gt2irgxtcsf.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.aizwys.cn/Article/details/gt2obybcaif.html

JS:   process.env.HOME
来源：http://dali.yongpay.top/Article/details/gt2fpzwjozo.html

TS:   process.env.HOME
来源：http://dali.svipenyu.cn/Article/details/gt2dmeprglu.html

Java: System.getenv("HOME")
来源：http://dali.jqgufenzy.top/Article/details/gt2mlxxnjhd.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jinqigfzy.top/Article/details/gt2vqxtxspv.html

Ruby: ENV["HOME"]
来源：http://dali.pycfn.com/Article/details/gt2dyiuxbfv.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.cqqwz.cn/Article/details/gt2txmabpyw.html

[M03] 执行外部命令
来源：http://dali.havefunace.top/Article/details/gt2grrnrrvu.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jqgfzy.top/Article/details/gt2hainejoc.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.kuanghao11.cn/Article/details/gt2rqnxcmob.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.chenjidiqi.icu/Article/details/gt2ryroofgz.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.nanxuanxn.top/Article/details/gt2ltncoshx.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.dianchejie.cn/Article/details/gt2bhgxgkxt.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dylpkqwt.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yj20258888.top/Article/details/gt2sgmfmnhr.html

C#:   Process.Start("ls", "-l");
来源：http://dali.redwolf501.top/Article/details/gt2ncxcgthr.html

[M04] 获取当前工作目录
来源：http://dali.yuxming.cn/Article/details/gt2ybufneii.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2vsklwawp.html

PHP:  getcwd();
来源：http://dali.yongpay.top/Article/details/gt2ithctnpi.html

JS:   process.cwd()
来源：http://dali.daxiang520.top/Article/details/gt2dwarbhqw.html

TS:   process.cwd()
来源：http://dali.ydzc1.top/Article/details/gt2mcxzjufy.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.chenlongwang.top/Article/details/gt2mltupxrf.html

Go:   os.Getwd()
来源：http://dali.zycfv.cn/Article/details/gt2lvrajdng.html

Ruby: Dir.pwd
来源：http://dali.ydzc1.top/Article/details/gt2piljlfoa.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.xuanzx.com/Article/details/gt2bsgvxoof.html

[M05] 设置退出码
来源：http://dali.gaohongyu789.top/Article/details/gt2hmcietnl.html

Py:   sys.exit(1)
来源：http://dali.yongpay.top/Article/details/gt2cmqvuwiv.html

PHP:  exit(1);
来源：http://dali.chenjidiqi.icu/Article/details/gt2spdiwfyq.html

JS:   process.exit(1)
来源：http://dali.haohaochexian.top/Article/details/gt2ewcusuhk.html

TS:   process.exit(1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2sfkqgwkn.html

Java: System.exit(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dukkqnuq.html

Go:   os.Exit(1)
来源：http://dali.xziqi.cn/Article/details/gt2dqeaeaqh.html

Ruby: exit 1
来源：http://dali.snrcjt.cn/Article/details/gt2digoiopb.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.daria6918.cn/Article/details/gt2apecpbqc.html

[M06] 向标准错误输出
来源：http://dali.sysykeji.top/Article/details/gt2nfzzcsxn.html

Py:   print("err", file=sys.stderr)
来源：http://dali.cucudq.cn/Article/details/gt2rhxgrudh.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.xuanzx.com/Article/details/gt2rqlfsddu.html

JS:   console.error("err")
来源：http://dali.zhengqikj.top/Article/details/gt2uqxkgmfc.html

TS:   console.error("err")
来源：http://dali.vqdsnc.cn/Article/details/gt2cnodieyf.html

Java: System.err.println("err")
来源：http://dali.yongpay.top/Article/details/gt2fnbwwfcr.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jyoumei.cn/Article/details/gt2oglgvkkk.html

Ruby: warn "err"
来源：http://dali.cqqwz.cn/Article/details/gt2nithqrwp.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.hywenlv.cn/Article/details/gt2vityoyqp.html

[M07] 判断是否为主入口
来源：http://dali.jianghu66.top/Article/details/gt2ecjdzwjt.html

Py:   if __name__ == "__main__":
来源：http://dali.gzhubu.top/Article/details/gt2notkrztk.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.smart0.xyz/Article/details/gt2khlyvghg.html

JS:   require.main === module
来源：http://dali.sufxvd.cn/Article/details/gt2qjvfsbbz.html

TS:   require.main === module
来源：http://dali.ehwqpu.com/Article/details/gt2dendmruc.html

Java: public static void main(String[] args)
来源：http://dali.aizwys.cn/Article/details/gt2jjhdgtoz.html

Go:   func main()
来源：http://dali.jinqigufen.top/Article/details/gt2sifhilmp.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.meibo888.top/Article/details/gt2swafbugk.html

C#:   static void Main(string[] args)
来源：http://dali.yanxiufei.cn/Article/details/gt2lhspebjl.html

[M08] 获取系统与运行时信息
来源：http://dali.xinyue.icu/Article/details/gt2cjmyhbbb.html

Py:   platform.system();  platform.python_version()
来源：http://dali.shangyingyoupin.top/Article/details/gt2hneltxkz.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yxzateme.html

JS:   process.platform;  process.version
来源：http://dali.birdmap.top/Article/details/gt2cfczomzn.html

TS:   process.platform;  process.version
来源：http://dali.jlsjyb.cn/Article/details/gt2arjtmtph.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2norxbhww.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ynjhjsfa.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.birdmap.top/Article/details/gt2yjgbyonp.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.wangshuangyany.cn/Article/details/gt2enrizfnk.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2vyiectak.html

N. 数据结构与算法
来源：http://dali.jqgfzy.top/Article/details/gt2pziuzrpr.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2gzwxsuhs.html

[N01] 二分查找（有序数组）
来源：http://dali.jyoumei.cn/Article/details/gt2veqvwpkt.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yangfankeji.com/Article/details/gt2ahsfoqll.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.nanxuanxn.top/Article/details/gt2vvqicopb.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.nanxinkj.top/Article/details/gt2fmwiarnn.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jjjsppuc.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2imlfcadn.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhixingplan.top/Article/details/gt2fdbdtmon.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.hywenlv.cn/Article/details/gt2uigdyxrr.html


<!-- 参考信息 -->