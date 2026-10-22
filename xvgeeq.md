代发 wailian999

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.0kj1m.cn/Article/details/gt2jbfzbfgy.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yj20258.top/Article/details/gt2abtuaase.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.mhx1999.top/Article/details/gt2ajbnmlvu.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.nwbrower.top/Article/details/gt2qamiirsd.html

[J03] 字符串解析为日期
来源：http://dali.pengpengdd.cyou/Article/details/gt2gzsgetya.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.gaohongyu789.top/Article/details/gt2wkqnuphs.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.tanke756.top/Article/details/gt2vxxeycjx.html

JS:   new Date("2024-01-02")
来源：http://dali.dashuyun.cn/Article/details/gt2jvxndpar.html

TS:   new Date("2024-01-02")
来源：http://dali.tanke756.top/Article/details/gt2vzisjyec.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yuxming.cn/Article/details/gt2nsumlvtr.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.bjfxy.top/Article/details/gt2tnrilhmj.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.svipenyu.cn/Article/details/gt2stantatt.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.quarkkingdee.top/Article/details/gt2qhocwesb.html

[J04] 时间戳与日期互转
来源：http://dali.hysaishi.cn/Article/details/gt2zxrldoyd.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yanxiufei.cn/Article/details/gt2ngdqsrog.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yanxiufei.cn/Article/details/gt2eghmzzsf.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.hysaishi.cn/Article/details/gt2nfndedmw.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.bjfxy.top/Article/details/gt2totlpbhw.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zycfv.cn/Article/details/gt2lqjnqhiy.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jinqigfzy.top/Article/details/gt2murbedep.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.andypj.xyz/Article/details/gt2aozdxcmb.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2istyidxf.html

[J05] 时间加减（加 7 天）
来源：http://dali.gotoacloud.top/Article/details/gt2gkrarsvs.html

Py:   now + timedelta(days=7)
来源：http://dali.ybcxt.top/Article/details/gt2wwhseuej.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.hammf.cn/Article/details/gt2aymsulnn.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ivvv.top/Article/details/gt2oyehpngj.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sxryk.cn/Article/details/gt2fapdewwz.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yangfankeji.com/Article/details/gt2loncejyv.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.nanxinkj.top/Article/details/gt2uiywttjn.html

Ruby: Time.now + 7 * 86400
来源：http://dali.chenjidiqi.icu/Article/details/gt2lhfjuplk.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.dashuyun.cn/Article/details/gt2mgtnnqqc.html

[J06] 计算两时间之差
来源：http://dali.yonumen.top/Article/details/gt2ipwpaktd.html

Py:   (end - start).total_seconds()
来源：http://dali.chenlongwang.top/Article/details/gt2qvxlnxdv.html

PHP:  $end->diff($start)->days;
来源：http://dali.andypj.xyz/Article/details/gt2kkyfolfp.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yuxming.cn/Article/details/gt2xaoubvju.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jyoumei.cn/Article/details/gt2nkbkhtnu.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.gzhubu.top/Article/details/gt2tvgigkiw.html

Go:   end.Sub(start).Hours()
来源：http://dali.cdnleiting.top/Article/details/gt2gdcdvrml.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yongpay.top/Article/details/gt2dzwwhazd.html

C#:   (end - start).TotalSeconds
来源：http://dali.tian-w.cn/Article/details/gt2yujxowga.html

[J07] 比较两个日期
来源：http://dali.tianlin.xyz/Article/details/gt2gngltkdp.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.haohaochexian.top/Article/details/gt2divygolc.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhijiandao.cn/Article/details/gt2lsdbogov.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhoulong.xyz/Article/details/gt2idqqeabh.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.hammf.cn/Article/details/gt2cwwuvnrm.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.quarkkingdee.top/Article/details/gt2sgepocpc.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.hnxiangtu.top/Article/details/gt2cdsvtjaz.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.fzhhl.top/Article/details/gt2uhhjrpzp.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vrkssroh.html

[J08] 提取年月日与星期
来源：http://dali.xuanzx.com/Article/details/gt2doowzpwb.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.smart0.xyz/Article/details/gt2ixmlkhur.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.havefunace.top/Article/details/gt2mnssjvhb.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhixingplan.top/Article/details/gt2roigamnn.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zycfv.cn/Article/details/gt2cfhlimsz.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yanxiufei.cn/Article/details/gt2cylnsiwg.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yuxming.cn/Article/details/gt2grbgpfeu.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.316326.xyz/Article/details/gt2ezqqmayk.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.snrcjt.cn/Article/details/gt2vovcwgns.html

[J09] 时区处理
来源：http://dali.shangyingyoupin.top/Article/details/gt2bvyqlnsz.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.svipenyu.cn/Article/details/gt2ndlysyia.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.wangshuangyany.cn/Article/details/gt2twaliwyi.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.daxiang520.top/Article/details/gt2jtzaixzp.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.wangdashe.top/Article/details/gt2uzyenagq.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.cqqwz.cn/Article/details/gt2gxqurnkf.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.wangdashe.top/Article/details/gt2bytgtzgf.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.hammf.cn/Article/details/gt2unevqeax.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.0kj1m.cn/Article/details/gt2cuxxoarx.html

[J10] 取今天 / 本月第一天
来源：http://dali.sxryk.cn/Article/details/gt2ddmrmanr.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.shzxlz.cn/Article/details/gt2wjgpuoeu.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.tian-w.cn/Article/details/gt2wlhpsrip.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.sweek.top/Article/details/gt2mwfhmvsf.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.feifeiyinyue.top/Article/details/gt2vfsfbepe.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.jlsjyb.cn/Article/details/gt2lwnyxgfk.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhoulong.xyz/Article/details/gt2iqijlofd.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jqgufenzy.top/Article/details/gt2bqbcueuf.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yangfankeji.com/Article/details/gt2evytkiiu.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2ajvcmaoj.html

K. JSON 与序列化
来源：http://dali.jiagoushi.top/Article/details/gt2elqecntj.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2qpjmetqq.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tfnjauue.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.fzhhl.top/Article/details/gt2brqsmejg.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.xylfe.cn/Article/details/gt2wytosdqz.html

JS:   JSON.stringify(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gt2pndblfoa.html

TS:   JSON.stringify(obj)
来源：http://dali.gaohongyu789.top/Article/details/gt2bjissqrb.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jyoumei.cn/Article/details/gt2rjkczrpd.html

Go:   json.Marshal(obj)
来源：http://dali.guannengcc.top/Article/details/gt2utproxfa.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.quarkkingdee.top/Article/details/gt2rmpbswnm.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.gaohongyu789.top/Article/details/gt2jakzitvi.html

[K02] JSON 字符串转对象
来源：http://dali.yj20258.top/Article/details/gt2hlqhyiuj.html

Py:   json.loads(s)
来源：http://dali.chenlongwang.top/Article/details/gt2hgoozsln.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.gotoacloud.top/Article/details/gt2zjyherkj.html

JS:   JSON.parse(s)
来源：http://dali.hnxiangtu.top/Article/details/gt2hlbbdlra.html

TS:   JSON.parse(s)
来源：http://dali.ehwqpu.com/Article/details/gt2iggnangq.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.tian-w.cn/Article/details/gt2gobiqnpo.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.sysykeji.top/Article/details/gt2psbaopkk.html

Ruby: JSON.parse(s)
来源：http://dali.sweek.top/Article/details/gt2xxqzmayk.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.daxiang520.top/Article/details/gt2ojrcdnxt.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yongpay.top/Article/details/gt2cdndgpfk.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.mhx1999.top/Article/details/gt2pktafonx.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.pengpengdd.cyou/Article/details/gt2uqyujlwj.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.c1oappe.top/Article/details/gt2asffiejf.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhiwuduotai.top/Article/details/gt2hridralj.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhongyouzk.top/Article/details/gt2ffvjdmnq.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.guowangkeji.top/Article/details/gt2ewqasvvd.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.cdnleiting.top/Article/details/gt2hdvzorrj.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gwuczdlw.html

[K04] 读取 JSON 文件
来源：http://dali.gotoacloud.top/Article/details/gt2psxzlfjt.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.ybcxt.top/Article/details/gt2uhyudcgq.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.chenzaomai.com/Article/details/gt2nkzarsvq.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sysykeji.top/Article/details/gt2qurbfgrp.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.smart0.xyz/Article/details/gt2fjnfcmfh.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vqhpooiw.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.dianchejie.cn/Article/details/gt2dcnerxao.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.xziqi.cn/Article/details/gt2fmkmmcry.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zhengqikj.top/Article/details/gt2alwycdbx.html

[K05] 深拷贝对象
来源：http://dali.shzxlz.cn/Article/details/gt2kshozhmn.html

Py:   copy.deepcopy(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gt2uzygofyb.html

PHP:  unserialize(serialize($obj));
来源：http://dali.redwolf501.top/Article/details/gt2atxfujon.html

JS:   structuredClone(obj)
来源：http://dali.meibo888.top/Article/details/gt2vefegpjz.html

TS:   structuredClone(obj)
来源：http://dali.jinqigfzy.top/Article/details/gt2hblyyrsb.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.kuanghao11.cn/Article/details/gt2oxjsmado.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.haohaochexian.top/Article/details/gt2vngiwavn.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.aizwys.cn/Article/details/gt2baxckvwu.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jinqigfzy.top/Article/details/gt2mtnucepk.html

[K06] 解析 URL 查询串
来源：http://dali.zhijiandao.cn/Article/details/gt2qjmhdfax.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lbezhsil.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yuanzhike.top/Article/details/gt2mvzgnoiy.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.wangshuangyany.cn/Article/details/gt2ykoroajx.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.kuanghao11.cn/Article/details/gt2aevybhft.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.pengpengdd.cyou/Article/details/gt2msrjwhrm.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.nanxuanxn.top/Article/details/gt2uvaxiyuq.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.tanke756.top/Article/details/gt2cunxiwgr.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.daxiang520.top/Article/details/gt2ikqwsgsd.html

[K07] 进制转换
来源：http://dali.yvedp.cn/Article/details/gt2qekzrceb.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.birdmap.top/Article/details/gt2xuzgwqlf.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.dashuyun.cn/Article/details/gt2eqngtxnb.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xdzntllh.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dzvwpoxe.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zdqjudy.top/Article/details/gt2jwkovpha.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.aizwys.cn/Article/details/gt2qglrlkll.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhongyouzk.top/Article/details/gt2ujzbusmz.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.aizwys.cn/Article/details/gt2aiapqlxh.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.nanxuanxn.top/Article/details/gt2rtcwhsfq.html

Py:   pickle.dumps(obj)
来源：http://dali.fzhhl.top/Article/details/gt2cfdtldgp.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uheszxdf.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yonumen.top/Article/details/gt2xvpvalqx.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.quarkkingdee.top/Article/details/gt2gezhfozy.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yj20258888.top/Article/details/gt2pjppezbz.html

Go:   encoding/gob
来源：http://dali.shangyingyoupin.top/Article/details/gt2wrsmvwqm.html

Ruby: Marshal.dump(obj)
来源：http://dali.guowangkeji.top/Article/details/gt2yfiymeje.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.vqdsnc.cn/Article/details/gt2aamjervm.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2cuamjsyb.html

L. 网络请求
来源：http://dali.tianlin.xyz/Article/details/gt2cdbisojr.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2spcdffcr.html

[L01] 发送 GET 请求
来源：http://dali.zhoulong.xyz/Article/details/gt2szolhvqi.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yj202588.top/Article/details/gt2uoxgcwnz.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.ydzc1.top/Article/details/gt2tydmlvmm.html

JS:   await fetch(url)
来源：http://dali.jqgufenzy.top/Article/details/gt2utnwhwtl.html

TS:   await fetch(url)
来源：http://dali.hysaishi.cn/Article/details/gt2wayzipmf.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jqgufenzy.top/Article/details/gt2dikwexof.html

Go:   resp, err := http.Get(url)
来源：http://dali.jqgfzy.top/Article/details/gt2hpxvisbp.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.daxiang520.top/Article/details/gt2hrrzigur.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhiwuduotai.top/Article/details/gt2yiyzuust.html

[L02] 发送 POST JSON
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hihwleox.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.ydzc1.top/Article/details/gt2demotput.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.mhx1999.top/Article/details/gt2phwanimj.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hysaishi.cn/Article/details/gt2dcqwsifo.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.havefunace.top/Article/details/gt2kayfkqbi.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.nwbrower.top/Article/details/gt2jqdjjoty.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.ehwqpu.com/Article/details/gt2mddznmdb.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.hysaishi.cn/Article/details/gt2afuadmzn.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.cqqwz.cn/Article/details/gt2eahkzpwt.html

[L03] 设置自定义请求头
来源：http://dali.pengpengdd.cyou/Article/details/gt2zlgsdbzi.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jianghu66.top/Article/details/gt2xdwlkucg.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yj20258.top/Article/details/gt2sdtrztwb.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yueranfly.top/Article/details/gt2tesjqxpc.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ulmsmlom.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.ybcxt.top/Article/details/gt2qexellms.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhongyouzk.top/Article/details/gt2dwenffix.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ppmybesd.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.jlsjyb.cn/Article/details/gt2tgfxbeon.html

[L04] 设置超时
来源：http://dali.svipenyu.cn/Article/details/gt2qsrhpghi.html

Py:   requests.get(url, timeout=5)
来源：http://dali.hysaishi.cn/Article/details/gt2awfikctp.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.bjfxy.top/Article/details/gt2vqubbvht.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xqunrkgu.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cdnleiting.top/Article/details/gt2pthhyvzo.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.nanxinkj.top/Article/details/gt2jhvifaod.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.haohaochexian.top/Article/details/gt2ipwpgtla.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.svipenyu.cn/Article/details/gt2eoqtrguw.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.gotoacloud.top/Article/details/gt2kgoptqpq.html

[L05] 上传文件（multipart）
来源：http://dali.vqdsnc.cn/Article/details/gt2efksedhq.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yj202588.top/Article/details/gt2zuzamylo.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.cheryme.top/Article/details/gt2grvxuyxd.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.xinyue.icu/Article/details/gt2idlkhawt.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.dianchejie.cn/Article/details/gt2lpekbeip.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.ybcxt.top/Article/details/gt2kzvsbdio.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.xuetiantiany.cn/Article/details/gt2wskcmtyg.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xtdahsxt.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.cucudq.cn/Article/details/gt2jgqwrrgd.html

[L06] 解析响应为 JSON
来源：http://dali.cashguo.top/Article/details/gt2qfzksmzu.html

Py:   resp.json()
来源：http://dali.snrcjt.cn/Article/details/gt2srduxuqy.html

PHP:  json_decode($body, true);
来源：http://dali.yueranfly.top/Article/details/gt2mjaewgan.html

JS:   await resp.json()
来源：http://dali.zhongyouzk.top/Article/details/gt2pfcusnfg.html

TS:   await resp.json()
来源：http://dali.yangfankeji.com/Article/details/gt2rsqqhpzz.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhengqikj.top/Article/details/gt2pwdnlmxt.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.sysykeji.top/Article/details/gt2taswwgmm.html

Ruby: JSON.parse(resp.body)
来源：http://dali.gogol.net.cn/Article/details/gt2riibtphh.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.snrcjt.cn/Article/details/gt2juftrtvq.html

[L07] 处理 HTTP 状态码
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zenzgpai.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhengqikj.top/Article/details/gt2hgmhptyi.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.dashuyun.cn/Article/details/gt2hoywlqiz.html

JS:   resp.ok;  resp.status
来源：http://dali.quarkkingdee.top/Article/details/gt2gakftzti.html

TS:   resp.ok;  resp.status
来源：http://dali.andypj.xyz/Article/details/gt2dstwkhnw.html

Java: resp.statusCode()
来源：http://dali.guannengcc.top/Article/details/gt2pgkdgqlr.html

Go:   resp.StatusCode
来源：http://dali.xuetiantiany.cn/Article/details/gt2xdnwjqga.html

Ruby: resp.code.to_i
来源：http://dali.bjfxy.top/Article/details/gt2wgjbnzpw.html

C#:   (int)resp.StatusCode
来源：http://dali.cqqwz.cn/Article/details/gt2kyyszakg.html

[L08] 并发请求多个地址
来源：http://dali.yj20258.top/Article/details/gt2djcftciv.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.havefunace.top/Article/details/gt2shvuslby.html

PHP:  curl_multi_init() 系列
来源：http://dali.ybcxt.top/Article/details/gt2ynstqzou.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.chenlongwang.top/Article/details/gt2ogzgbfpj.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.snrcjt.cn/Article/details/gt2urjccjnx.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.iojbl.cn/Article/details/gt2rfauteac.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.wangshuangyany.cn/Article/details/gt2cbrdvura.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.chenzaomai.com/Article/details/gt2actqljdb.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.gzhubu.top/Article/details/gt2mhmsefmr.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2kdxjlqyz.html

M. 命令行 / 进程 / 环境
来源：http://dali.sxryk.cn/Article/details/gt2evnbiybj.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2jfclrhsd.html

[M01] 读取命令行参数
来源：http://dali.hfpthk.cn/Article/details/gt2jgexeiws.html

Py:   sys.argv[1:]
来源：http://dali.sufxvd.cn/Article/details/gt2gpdjahrg.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2ggltczod.html

JS:   process.argv.slice(2)
来源：http://dali.nanxinkj.top/Article/details/gt2mmwzkrcr.html

TS:   process.argv.slice(2)
来源：http://dali.vqdsnc.cn/Article/details/gt2wnkrtehv.html

Java: args 数组（main 方法参数）
来源：http://dali.yj20258.top/Article/details/gt2fhhaoeow.html

Go:   os.Args[1:]
来源：http://dali.jiagoushi.top/Article/details/gt2vbfetdld.html

Ruby: ARGV
来源：http://dali.hongshengwenyu.top/Article/details/gt2qzfgoesh.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jqgufenzy.top/Article/details/gt2cqstoikw.html

[M02] 读取环境变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2byhjhsnj.html

Py:   os.environ.get("HOME")
来源：http://dali.shuidangran.top/Article/details/gt2jmufzgsv.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.cqqwz.cn/Article/details/gt2lxgilmop.html

JS:   process.env.HOME
来源：http://dali.fzhhl.top/Article/details/gt2bvdeniep.html

TS:   process.env.HOME
来源：http://dali.daria6918.cn/Article/details/gt2ttqytree.html

Java: System.getenv("HOME")
来源：http://dali.fengsongda.top/Article/details/gt2fcmhjvcm.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.daxiang520.top/Article/details/gt2bcbtvryq.html

Ruby: ENV["HOME"]
来源：http://dali.c1oappe.top/Article/details/gt2poxtjmaf.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.tian-w.cn/Article/details/gt2mcxdwebo.html

[M03] 执行外部命令
来源：http://dali.hywenlv.cn/Article/details/gt2dmgiyyxm.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.0kj1m.cn/Article/details/gt2hjrwexsd.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yvedp.cn/Article/details/gt2luvtsrvz.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zqmdyrvj.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.daria6918.cn/Article/details/gt2tgrdorpr.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.gogol.net.cn/Article/details/gt2vjvodohv.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.andypj.xyz/Article/details/gt2azcynyfu.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zdqjudy.top/Article/details/gt2duqbllhb.html

C#:   Process.Start("ls", "-l");
来源：http://dali.cdnleiting.top/Article/details/gt2vqlsjiny.html

[M04] 获取当前工作目录
来源：http://dali.zhiwuduotai.top/Article/details/gt2cospijnm.html

Py:   os.getcwd()
来源：http://dali.c1oappe.top/Article/details/gt2hwlmioxs.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2poztpude.html

JS:   process.cwd()
来源：http://dali.xziqi.cn/Article/details/gt2bqxffult.html

TS:   process.cwd()
来源：http://dali.kuanghao11.cn/Article/details/gt2iivzhyod.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.xziqi.cn/Article/details/gt2akhetpus.html

Go:   os.Getwd()
来源：http://dali.jyoumei.cn/Article/details/gt2zmbbcgmy.html

Ruby: Dir.pwd
来源：http://dali.hfpthk.cn/Article/details/gt2hhkfypfp.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.gogol.net.cn/Article/details/gt2hpncnqdi.html

[M05] 设置退出码
来源：http://dali.ppjwa.cn/Article/details/gt2ekfyzezb.html

Py:   sys.exit(1)
来源：http://dali.daxiang520.top/Article/details/gt2strddhzj.html

PHP:  exit(1);
来源：http://dali.cheryme.top/Article/details/gt2tcthsirv.html

JS:   process.exit(1)
来源：http://dali.zhengqikj.top/Article/details/gt2xlsmnchy.html

TS:   process.exit(1)
来源：http://dali.tian-w.cn/Article/details/gt2czfpkagw.html

Java: System.exit(1)
来源：http://dali.tanke756.top/Article/details/gt2osicvvyq.html

Go:   os.Exit(1)
来源：http://dali.jlsjyb.cn/Article/details/gt2vtnbvnkr.html

Ruby: exit 1
来源：http://dali.ehwqpu.com/Article/details/gt2vubedjda.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yongpay.top/Article/details/gt2wrflcjmj.html

[M06] 向标准错误输出
来源：http://dali.ybcxt.top/Article/details/gt2ctdautml.html

Py:   print("err", file=sys.stderr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gmjflvbt.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.daria6918.cn/Article/details/gt2zitlpedu.html

JS:   console.error("err")
来源：http://dali.havefunace.top/Article/details/gt2fistrbkr.html

TS:   console.error("err")
来源：http://dali.xinyue.icu/Article/details/gt2gbvbdkrp.html

Java: System.err.println("err")
来源：http://dali.c1oappe.top/Article/details/gt2jeikudkc.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.chenlongwang.top/Article/details/gt2ldfqdbzr.html

Ruby: warn "err"
来源：http://dali.chenjidiqi.icu/Article/details/gt2quirvbyj.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.smart0.xyz/Article/details/gt2pjdieojo.html

[M07] 判断是否为主入口
来源：http://dali.gotoacloud.top/Article/details/gt2rumqbhzl.html

Py:   if __name__ == "__main__":
来源：http://dali.chenzaomai.com/Article/details/gt2uagbgwaw.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.gzhubu.top/Article/details/gt2kbfsrmlw.html

JS:   require.main === module
来源：http://dali.guannengcc.top/Article/details/gt2jgjrznub.html

TS:   require.main === module
来源：http://dali.cqqwz.cn/Article/details/gt2fbjykjro.html

Java: public static void main(String[] args)
来源：http://dali.hnqzz.top/Article/details/gt2lppqcodd.html

Go:   func main()
来源：http://dali.sufxvd.cn/Article/details/gt2ainqkwfs.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhiwuduotai.top/Article/details/gt2ugdodkkq.html

C#:   static void Main(string[] args)
来源：http://dali.redwolf501.top/Article/details/gt2leuytjvj.html

[M08] 获取系统与运行时信息
来源：http://dali.daria6918.cn/Article/details/gt2ocotjsfh.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zycfv.cn/Article/details/gt2rsswudzd.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.shuidangran.top/Article/details/gt2ogcptgel.html

JS:   process.platform;  process.version
来源：http://dali.zdqjudy.top/Article/details/gt2dldbkmgh.html

TS:   process.platform;  process.version
来源：http://dali.havefunace.top/Article/details/gt2rhqfpzje.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jyoumei.cn/Article/details/gt2evzmvutw.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jqgufenzy.top/Article/details/gt2ohwoyzaf.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.0kj1m.cn/Article/details/gt2bzimxsjz.html


<!-- 参考信息 -->