代发 wailian999

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.smart0.xyz/Article/details/gt2dkxldvla.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.haohaochexian.top/Article/details/gt2axedjhyu.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.hfpthk.cn/Article/details/gt2qhjibuca.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2ylwkgnki.html

J. 日期与时间
来源：http://dali.wangdashe.top/Article/details/gt2cxzpjbxy.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2xjfltimc.html

[J01] 获取当前时间
来源：http://dali.yonumen.top/Article/details/gt2myqyfkts.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.vqdsnc.cn/Article/details/gt2wrcnvbvq.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yanxiufei.cn/Article/details/gt2wopsmgav.html

JS:   new Date();  Date.now()
来源：http://dali.shangyingyoupin.top/Article/details/gt2yvfbqtgs.html

TS:   new Date();  Date.now()
来源：http://dali.havefunace.top/Article/details/gt2rmaadojn.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.hfpthk.cn/Article/details/gt2tvohhszd.html

Go:   time.Now()
来源：http://dali.jinqigfzy.top/Article/details/gt2dteprqwj.html

Ruby: Time.now
来源：http://dali.aibaodan.cn/Article/details/gt2cidavggv.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.sysykeji.top/Article/details/gt2guqtzxqo.html

[J02] 格式化输出
来源：http://dali.jiagoushi.top/Article/details/gt2mykxxlvh.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cqqwz.cn/Article/details/gt2qvowkacp.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lfwebsjs.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jqgufenzy.top/Article/details/gt2fzlsehfs.html

TS:   d.toISOString()
来源：http://dali.havefunace.top/Article/details/gt2ffeiiszj.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.nanxuanxn.top/Article/details/gt2wldfsaml.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.9152youxi.cn/Article/details/gt2llaslzjk.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yvedp.cn/Article/details/gt2rksddxff.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.birdmap.top/Article/details/gt2yxruzmve.html

[J03] 字符串解析为日期
来源：http://dali.redwolf501.top/Article/details/gt2jbalqytg.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.hnxiangtu.top/Article/details/gt2vqapeekl.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hnqzz.top/Article/details/gt2sfdizbze.html

JS:   new Date("2024-01-02")
来源：http://dali.jianghu66.top/Article/details/gt2ngktcruu.html

TS:   new Date("2024-01-02")
来源：http://dali.hnxiangtu.top/Article/details/gt2tqhxicqs.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jianghu66.top/Article/details/gt2ijlnryhh.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hnqzz.top/Article/details/gt2gzogthve.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.shangyingyoupin.top/Article/details/gt2gbfvhmii.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.0kj1m.cn/Article/details/gt2nqlpnjlb.html

[J04] 时间戳与日期互转
来源：http://dali.yvedp.cn/Article/details/gt2ddmphgsg.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhixingplan.top/Article/details/gt2rhaxlhxr.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dkpewnsn.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.feifeiyinyue.top/Article/details/gt2bpedhsuo.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.c1oappe.top/Article/details/gt2xjbytahj.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.ydzc1.top/Article/details/gt2nqlnnhqo.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.gzhubu.top/Article/details/gt2izrxiaml.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.tian-w.cn/Article/details/gt2xfpxmqun.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2udydxdby.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2orhnlovn.html

Py:   now + timedelta(days=7)
来源：http://dali.zhengqikj.top/Article/details/gt2rlkfenkf.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.andypj.xyz/Article/details/gt2jqkdrvvf.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gotoacloud.top/Article/details/gt2loojwhpl.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ybcxt.top/Article/details/gt2apavsqaw.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.tanke756.top/Article/details/gt2tpqyydgy.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2blropskx.html

Ruby: Time.now + 7 * 86400
来源：http://dali.nanxinkj.top/Article/details/gt2rllxazkp.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.tianlin.xyz/Article/details/gt2owbzewzf.html

[J06] 计算两时间之差
来源：http://dali.daxiang520.top/Article/details/gt2ifmvfoja.html

Py:   (end - start).total_seconds()
来源：http://dali.hywenlv.cn/Article/details/gt2cwdlwhph.html

PHP:  $end->diff($start)->days;
来源：http://dali.tianlin.xyz/Article/details/gt2waemqlqj.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yuanzhike.top/Article/details/gt2gyvtogva.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.cheryme.top/Article/details/gt2crlqffkj.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jlsjyb.cn/Article/details/gt2qugxllbe.html

Go:   end.Sub(start).Hours()
来源：http://dali.zhiwuduotai.top/Article/details/gt2zpgtqggv.html

Ruby: end - start                 # 返回秒数
来源：http://dali.svipenyu.cn/Article/details/gt2xjqolzex.html

C#:   (end - start).TotalSeconds
来源：http://dali.smart0.xyz/Article/details/gt2syzzcgxi.html

[J07] 比较两个日期
来源：http://dali.yuanzhike.top/Article/details/gt2yflcmaai.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.xziqi.cn/Article/details/gt2qwfpdqos.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.aizwys.cn/Article/details/gt2qxnomlrj.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zdqjudy.top/Article/details/gt2iljdfdzd.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.hysaishi.cn/Article/details/gt2nzvhthfw.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.shuidangran.top/Article/details/gt2ugecymtt.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zsnapxtg.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jqgfzy.top/Article/details/gt2npbwfgna.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.vqdsnc.cn/Article/details/gt2etbcvgag.html

[J08] 提取年月日与星期
来源：http://dali.andypj.xyz/Article/details/gt2rvrcylaw.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.chenzaomai.com/Article/details/gt2zzxofgen.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.cqqwz.cn/Article/details/gt2qlcwzkrt.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yonumen.top/Article/details/gt2bkjwfpjj.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.nanxuanxn.top/Article/details/gt2krfxmyxm.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jpypdlfn.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.cashguo.top/Article/details/gt2nkibqrjf.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jyoumei.cn/Article/details/gt2upcuefro.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.shuidangran.top/Article/details/gt2izqkixvn.html

[J09] 时区处理
来源：http://dali.birdmap.top/Article/details/gt2otegmyav.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.xylfe.cn/Article/details/gt2ckjlptto.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhijiandao.cn/Article/details/gt2eoowkdrx.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yj202588.top/Article/details/gt2fcmbzfef.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.guannengcc.top/Article/details/gt2hkrsmosi.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.aibaodan.cn/Article/details/gt2mbguuloe.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yuxming.cn/Article/details/gt2xbubrebx.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.meibo888.top/Article/details/gt2biqrgxlb.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.aibaodan.cn/Article/details/gt2jgwgsivl.html

[J10] 取今天 / 本月第一天
来源：http://dali.daxiang520.top/Article/details/gt2xmrerksw.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2jszpognr.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.pycfn.com/Article/details/gt2yneuvyhb.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.hnxiangtu.top/Article/details/gt2xsqfjnev.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.pycfn.com/Article/details/gt2dbdmiywj.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.sysykeji.top/Article/details/gt2colsttqs.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.hongshengwenyu.top/Article/details/gt2ntowbruo.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.ppjwa.cn/Article/details/gt2fmmviper.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2tsiqfzqr.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2sztuktvi.html

K. JSON 与序列化
来源：http://dali.wangshuangyany.cn/Article/details/gt2vahfhaie.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2pwxnzezz.html

[K01] 对象转 JSON 字符串
来源：http://dali.birdmap.top/Article/details/gt2yzkudgbq.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.gaohongyu789.top/Article/details/gt2ajysonft.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.feifeiyinyue.top/Article/details/gt2ljqyzego.html

JS:   JSON.stringify(obj)
来源：http://dali.sweek.top/Article/details/gt2wwwvmmkr.html

TS:   JSON.stringify(obj)
来源：http://dali.hammf.cn/Article/details/gt2hyxtepqy.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhijiandao.cn/Article/details/gt2tlobxptj.html

Go:   json.Marshal(obj)
来源：http://dali.hammf.cn/Article/details/gt2bprdrcjy.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hongshengwenyu.top/Article/details/gt2rqhjabao.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.xziqi.cn/Article/details/gt2qjmckgoj.html

[K02] JSON 字符串转对象
来源：http://dali.yanxiufei.cn/Article/details/gt2erfzwlci.html

Py:   json.loads(s)
来源：http://dali.tanke756.top/Article/details/gt2ujfgfrgd.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kosyjayl.html

JS:   JSON.parse(s)
来源：http://dali.xuanzx.com/Article/details/gt2ehujdhfj.html

TS:   JSON.parse(s)
来源：http://dali.zycfv.cn/Article/details/gt2ortcloue.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.snrcjt.cn/Article/details/gt2fbadihxx.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.xuanzx.com/Article/details/gt2wkoqfbmh.html

Ruby: JSON.parse(s)
来源：http://dali.pycfn.com/Article/details/gt2cnzjttaw.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.gogol.net.cn/Article/details/gt2fwqdiivu.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.bjfxy.top/Article/details/gt2nzmacmkl.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.xinyue.icu/Article/details/gt2yripazzl.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.0kj1m.cn/Article/details/gt2qpbczvma.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.daxiang520.top/Article/details/gt2tvaapjau.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jqgufenzy.top/Article/details/gt2qdhhdknm.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.fzhhl.top/Article/details/gt2roynvbvc.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.sufxvd.cn/Article/details/gt2zmmuafcd.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jinqigfzy.top/Article/details/gt2qonwswvy.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ueshxzce.html

[K04] 读取 JSON 文件
来源：http://dali.hnxiangtu.top/Article/details/gt2kphmuqfc.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhiwuduotai.top/Article/details/gt2uoshzhwg.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.xziqi.cn/Article/details/gt2xcnqoftr.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yj202588.top/Article/details/gt2vhgicwxe.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jianghu66.top/Article/details/gt2ziiicxdn.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.hywenlv.cn/Article/details/gt2kighbgdq.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhengqikj.top/Article/details/gt2chwebuqq.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.aizwys.cn/Article/details/gt2rgmvfiuk.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.ydzc1.top/Article/details/gt2nfkeqduk.html

[K05] 深拷贝对象
来源：http://dali.9152youxi.cn/Article/details/gt2qnpjjqaz.html

Py:   copy.deepcopy(obj)
来源：http://dali.cashguo.top/Article/details/gt2bmjlvxfa.html

PHP:  unserialize(serialize($obj));
来源：http://dali.xuanzx.com/Article/details/gt2oqpsgqcy.html

JS:   structuredClone(obj)
来源：http://dali.smart0.xyz/Article/details/gt2nzhvfojx.html

TS:   structuredClone(obj)
来源：http://dali.xziqi.cn/Article/details/gt2zliftejx.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.fengsongda.top/Article/details/gt2ryxwdfpp.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.gaohongyu789.top/Article/details/gt2zkwjmbbv.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.snrcjt.cn/Article/details/gt2qunqqbii.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yj202588.top/Article/details/gt2ahoonbrs.html

[K06] 解析 URL 查询串
来源：http://dali.sufxvd.cn/Article/details/gt2drneexcb.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.sysykeji.top/Article/details/gt2gwmkanaa.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhixingplan.top/Article/details/gt2klwvudux.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ppjwa.cn/Article/details/gt2naynifmv.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xuetiantiany.cn/Article/details/gt2wmqqwhdo.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.9152youxi.cn/Article/details/gt2kzoyuwjp.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.dashuyun.cn/Article/details/gt2ribdexxe.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.smart0.xyz/Article/details/gt2kggpowqk.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.cdnleiting.top/Article/details/gt2ffdmjbbc.html

[K07] 进制转换
来源：http://dali.fengsongda.top/Article/details/gt2zexlgdiz.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wkvuahwv.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jianghu66.top/Article/details/gt2kyahdkwu.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.kuanghao11.cn/Article/details/gt2cwxqlwoy.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.tianlin.xyz/Article/details/gt2fmmplrdv.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.daxiang520.top/Article/details/gt2cnizfmuv.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tdgtfsks.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.nanxuanxn.top/Article/details/gt2tgkbmziz.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.c1oappe.top/Article/details/gt2fnanhwxv.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.xinyue.icu/Article/details/gt2chcpheky.html

Py:   pickle.dumps(obj)
来源：http://dali.birdmap.top/Article/details/gt2vtpnrfng.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhiwuduotai.top/Article/details/gt2lorwnmpe.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.cashguo.top/Article/details/gt2zdgogmqa.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yj20258888.top/Article/details/gt2wzrywbok.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhoulong.xyz/Article/details/gt2sqttzqwu.html

Go:   encoding/gob
来源：http://dali.zhongyouzk.top/Article/details/gt2dnxxgyqr.html

Ruby: Marshal.dump(obj)
来源：http://dali.hywenlv.cn/Article/details/gt2rfmvljpp.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jqgfzy.top/Article/details/gt2dxoicmuh.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2dzlsxosp.html

L. 网络请求
来源：http://dali.redwolf501.top/Article/details/gt2jegjzehr.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2msspvnyk.html

[L01] 发送 GET 请求
来源：http://dali.hammf.cn/Article/details/gt2sxvcyuqz.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.chenzaomai.com/Article/details/gt2axjmktxw.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.svipenyu.cn/Article/details/gt2azcmrohv.html

JS:   await fetch(url)
来源：http://dali.yonumen.top/Article/details/gt2pztrmssc.html

TS:   await fetch(url)
来源：http://dali.shzxlz.cn/Article/details/gt2pnwvlrcm.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.ppjwa.cn/Article/details/gt2oisdpesa.html

Go:   resp, err := http.Get(url)
来源：http://dali.jinqigufen.top/Article/details/gt2ahkotwuc.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.hnqzz.top/Article/details/gt2caatrwcs.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.tianlin.xyz/Article/details/gt2qxvsvgzb.html

[L02] 发送 POST JSON
来源：http://dali.quarkkingdee.top/Article/details/gt2bleldxxj.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.0kj1m.cn/Article/details/gt2wcwzwlzf.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jianghu66.top/Article/details/gt2wvcqphwv.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.guannengcc.top/Article/details/gt2ygizfchf.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.bjfxy.top/Article/details/gt2vnnzhpty.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.sufxvd.cn/Article/details/gt2eredfvzf.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jqgufenzy.top/Article/details/gt2nhnsticf.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.sufxvd.cn/Article/details/gt2lmenihno.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhongyouzk.top/Article/details/gt2kjgprtrg.html

[L03] 设置自定义请求头
来源：http://dali.quarkkingdee.top/Article/details/gt2nsennheq.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.sxryk.cn/Article/details/gt2ekebbzmd.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yangfankeji.com/Article/details/gt2hlvugxut.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cashguo.top/Article/details/gt2otylvgzv.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cucudq.cn/Article/details/gt2ldfncwfa.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jianghu66.top/Article/details/gt2gxjnlmza.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2magrzwzf.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.hammf.cn/Article/details/gt2alclyvti.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.birdmap.top/Article/details/gt2gweaswez.html

[L04] 设置超时
来源：http://dali.hammf.cn/Article/details/gt2yoylomnm.html

Py:   requests.get(url, timeout=5)
来源：http://dali.iojbl.cn/Article/details/gt2ogkpbwvc.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.gaohongyu789.top/Article/details/gt2ogeejqeg.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cheryme.top/Article/details/gt2aaeoynbu.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.snrcjt.cn/Article/details/gt2nhxgkeet.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.birdmap.top/Article/details/gt2npzflelf.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.hnqzz.top/Article/details/gt2jzzklekd.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.shangyingyoupin.top/Article/details/gt2tvrauhtd.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.hysaishi.cn/Article/details/gt2lpcllymo.html

[L05] 上传文件（multipart）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mdxuvhee.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhixingplan.top/Article/details/gt2ktcgrktu.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.tianlin.xyz/Article/details/gt2hxihugwq.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.bjfxy.top/Article/details/gt2odfbllio.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.xinyue.icu/Article/details/gt2lepblxit.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.haohaochexian.top/Article/details/gt2gjwdpsnx.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.shuidangran.top/Article/details/gt2udkclzoo.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.chenlongwang.top/Article/details/gt2vkcoiyti.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.ydzc1.top/Article/details/gt2xhutajhb.html

[L06] 解析响应为 JSON
来源：http://dali.ppjwa.cn/Article/details/gt2krozpkmt.html

Py:   resp.json()
来源：http://dali.daria6918.cn/Article/details/gt2ozcwhjnf.html

PHP:  json_decode($body, true);
来源：http://dali.bjfxy.top/Article/details/gt2itlthire.html

JS:   await resp.json()
来源：http://dali.zhongyouzk.top/Article/details/gt2bejuaxif.html

TS:   await resp.json()
来源：http://dali.yuxming.cn/Article/details/gt2nhtmmwqs.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.havefunace.top/Article/details/gt2cudrjqvy.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.kuanghao11.cn/Article/details/gt2tjlmdjbj.html

Ruby: JSON.parse(resp.body)
来源：http://dali.xziqi.cn/Article/details/gt2uqyrhcux.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yongpay.top/Article/details/gt2tsvayiwl.html

[L07] 处理 HTTP 状态码
来源：http://dali.bjfxy.top/Article/details/gt2yccdafip.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.wangdashe.top/Article/details/gt2zlanjnmp.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.cucudq.cn/Article/details/gt2mresfwnu.html

JS:   resp.ok;  resp.status
来源：http://dali.nanxuanxn.top/Article/details/gt2meigawfk.html

TS:   resp.ok;  resp.status
来源：http://dali.zhengqikj.top/Article/details/gt2oybjsoel.html

Java: resp.statusCode()
来源：http://dali.xuanzx.com/Article/details/gt2lkjapbfk.html

Go:   resp.StatusCode
来源：http://dali.cqqwz.cn/Article/details/gt2qnwjlgdn.html

Ruby: resp.code.to_i
来源：http://dali.nanxuanxn.top/Article/details/gt2ifmkgjcb.html

C#:   (int)resp.StatusCode
来源：http://dali.havefunace.top/Article/details/gt2usboueam.html

[L08] 并发请求多个地址
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zpsexoju.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.fengsongda.top/Article/details/gt2vxydaptv.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhengqikj.top/Article/details/gt2bixlcquy.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hywenlv.cn/Article/details/gt2epiecxdn.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.haohaochexian.top/Article/details/gt2wsmiruip.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yonumen.top/Article/details/gt2kwfnlgvk.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.fzhhl.top/Article/details/gt2izhwzcdq.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.shzxlz.cn/Article/details/gt2cmxggejn.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.wangdashe.top/Article/details/gt2vsjncbdo.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2dtphowgp.html

M. 命令行 / 进程 / 环境
来源：http://dali.hywenlv.cn/Article/details/gt2wrucmlmv.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qgirdvpj.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2iltlgdlq.html

Py:   sys.argv[1:]
来源：http://dali.jqgfzy.top/Article/details/gt2ksidqpkw.html

PHP:  $argv;  $argc;
来源：http://dali.shuidangran.top/Article/details/gt2jmzpvons.html

JS:   process.argv.slice(2)
来源：http://dali.cdnleiting.top/Article/details/gt2oweflvui.html

TS:   process.argv.slice(2)
来源：http://dali.redwolf501.top/Article/details/gt2eoyukpdf.html

Java: args 数组（main 方法参数）
来源：http://dali.sysykeji.top/Article/details/gt2koawxfxv.html

Go:   os.Args[1:]
来源：http://dali.hysaishi.cn/Article/details/gt2mtrwetww.html

Ruby: ARGV
来源：http://dali.daria6918.cn/Article/details/gt2afmrmzmr.html

C#:   args 数组（Main 方法参数）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bmqmyagu.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wcudibxo.html

Py:   os.environ.get("HOME")
来源：http://dali.yj20258888.top/Article/details/gt2jkaavpqs.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.xuetiantiany.cn/Article/details/gt2ylinfqkp.html

JS:   process.env.HOME
来源：http://dali.chenlongwang.top/Article/details/gt2ftstvkoi.html

TS:   process.env.HOME
来源：http://dali.shuidangran.top/Article/details/gt2jtfzommy.html

Java: System.getenv("HOME")
来源：http://dali.jinqigfzy.top/Article/details/gt2ffgnyuuw.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.daxiang520.top/Article/details/gt2kvtbfkmq.html

Ruby: ENV["HOME"]
来源：http://dali.hysaishi.cn/Article/details/gt2juyrbusx.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zdqjudy.top/Article/details/gt2jjckcafm.html

[M03] 执行外部命令
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zrdvvowu.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.chenzaomai.com/Article/details/gt2zxrgwzly.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.ppjwa.cn/Article/details/gt2mzrcpgnz.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.dashuyun.cn/Article/details/gt2knuqfvnt.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yuxming.cn/Article/details/gt2oppisgtw.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.hfpthk.cn/Article/details/gt2urswrcps.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.aibaodan.cn/Article/details/gt2isnehsib.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.shuidangran.top/Article/details/gt2ilkgezkc.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jqgfzy.top/Article/details/gt2rfqbqfdu.html

[M04] 获取当前工作目录
来源：http://dali.aibaodan.cn/Article/details/gt2aecgstdp.html

Py:   os.getcwd()
来源：http://dali.ehwqpu.com/Article/details/gt2yxdeqitg.html

PHP:  getcwd();
来源：http://dali.chenzaomai.com/Article/details/gt2tvthfzsi.html

JS:   process.cwd()
来源：http://dali.xuanzx.com/Article/details/gt2qlezzrwn.html

TS:   process.cwd()
来源：http://dali.hfpthk.cn/Article/details/gt2shdfvjgr.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.sufxvd.cn/Article/details/gt2ozyeqfof.html

Go:   os.Getwd()
来源：http://dali.mhx1999.top/Article/details/gt2nvjmxink.html

Ruby: Dir.pwd
来源：http://dali.ehwqpu.com/Article/details/gt2qjqcbnvx.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.ybcxt.top/Article/details/gt2xrukplfk.html

[M05] 设置退出码
来源：http://dali.zhoulong.xyz/Article/details/gt2xyilogpo.html

Py:   sys.exit(1)
来源：http://dali.bjfxy.top/Article/details/gt2vjlrofzh.html

PHP:  exit(1);
来源：http://dali.nanxuanxn.top/Article/details/gt2tnvwwdxp.html

JS:   process.exit(1)
来源：http://dali.cucudq.cn/Article/details/gt2gydpewsg.html

TS:   process.exit(1)
来源：http://dali.nanxuanxn.top/Article/details/gt2ktyxiywb.html

Java: System.exit(1)
来源：http://dali.hammf.cn/Article/details/gt2vvnjikaw.html

Go:   os.Exit(1)
来源：http://dali.ivvv.top/Article/details/gt2vzbusstr.html

Ruby: exit 1
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oiqotziq.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.wangdashe.top/Article/details/gt2lzseprum.html

[M06] 向标准错误输出
来源：http://dali.cdnleiting.top/Article/details/gt2tzsmpukj.html

Py:   print("err", file=sys.stderr)
来源：http://dali.xuanzx.com/Article/details/gt2dbbbahog.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.nanxinkj.top/Article/details/gt2fewwytva.html

JS:   console.error("err")
来源：http://dali.zdqjudy.top/Article/details/gt2geupcbdv.html

TS:   console.error("err")
来源：http://dali.hywenlv.cn/Article/details/gt2bedrtscl.html

Java: System.err.println("err")
来源：http://dali.hnqzz.top/Article/details/gt2zhlgsups.html


<!-- 参考信息 -->