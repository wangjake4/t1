代发 wailian999

J. 日期与时间
来源：http://dali.jqgufenzy.top/Article/details/gtjxgkxtpv.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtxkyleqsr.html

[J01] 获取当前时间
来源：http://dali.jyoumei.cn/Article/details/gtupnejjew.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.xuanzx.com/Article/details/gtudztotlu.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yuxming.cn/Article/details/gtheyujady.html

JS:   new Date();  Date.now()
来源：http://dali.yongpay.top/Article/details/gtohwojmlh.html

TS:   new Date();  Date.now()
来源：http://dali.pengpengdd.cyou/Article/details/gtepjxswpf.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.cucudq.cn/Article/details/gtjykxdrrx.html

Go:   time.Now()
来源：http://dali.gaohongyu789.top/Article/details/gtcfydqfhc.html

Ruby: Time.now
来源：http://dali.yvedp.cn/Article/details/gtexlkghtg.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jinqigufen.top/Article/details/gtiugnotoy.html

[J02] 格式化输出
来源：http://dali.9152youxi.cn/Article/details/gtrftjelyz.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hongshengwenyu.top/Article/details/gtneflsllm.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.316326.xyz/Article/details/gtbiaxxvyp.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zdqjudy.top/Article/details/gtwfcddjbd.html

TS:   d.toISOString()
来源：http://dali.daxiang520.top/Article/details/gthsevrbxo.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.chenzaomai.com/Article/details/gtokolsads.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.ydzc1.top/Article/details/gtxzvzbaeg.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yanxiufei.cn/Article/details/gtxgtexmfc.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.fzhhl.top/Article/details/gtbtvudlmo.html

[J03] 字符串解析为日期
来源：http://dali.sufxvd.cn/Article/details/gtxegqdved.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.ybcxt.top/Article/details/gtygiqcqpt.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jinqigufen.top/Article/details/gtkuljstnh.html

JS:   new Date("2024-01-02")
来源：http://dali.yuxming.cn/Article/details/gtmkyasqwq.html

TS:   new Date("2024-01-02")
来源：http://dali.jqgfzy.top/Article/details/gtxsugugrh.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.xinyue.icu/Article/details/gtjrahjsnq.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zhiwuduotai.top/Article/details/gttbvvdifc.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.kuanghao11.cn/Article/details/gtpnxldfwx.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuuefkwbn.html

[J04] 时间戳与日期互转
来源：http://dali.aibaodan.cn/Article/details/gtspmuwdwu.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.sxryk.cn/Article/details/gtchujivco.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.vqdsnc.cn/Article/details/gtmypourll.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.shangyingyoupin.top/Article/details/gtkfmoyoue.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.chenzaomai.com/Article/details/gtxkubydjb.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhiwuduotai.top/Article/details/gtiqmhplob.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.guannengcc.top/Article/details/gtrsnrmirb.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zdqjudy.top/Article/details/gtzmucrkth.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.sufxvd.cn/Article/details/gtbeywxltu.html

[J05] 时间加减（加 7 天）
来源：http://dali.hywenlv.cn/Article/details/gtjecmndmt.html

Py:   now + timedelta(days=7)
来源：http://dali.hongshengwenyu.top/Article/details/gtfqkevegy.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.shzxlz.cn/Article/details/gtyjbcfovc.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinqigufen.top/Article/details/gtqvxtpexj.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hysaishi.cn/Article/details/gtqkpflqjr.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xuanzx.com/Article/details/gtqxfodyge.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yueranfly.top/Article/details/gthgkwmolv.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yj20258888.top/Article/details/gtslnrsyzx.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.tian-w.cn/Article/details/gtgyeabsqy.html

[J06] 计算两时间之差
来源：http://dali.yangfankeji.com/Article/details/gtybzfohkp.html

Py:   (end - start).total_seconds()
来源：http://dali.nanxuanxn.top/Article/details/gtmmxcwfbt.html

PHP:  $end->diff($start)->days;
来源：http://dali.ivvv.top/Article/details/gthqkclaub.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yj202588.top/Article/details/gtlvkgdcxx.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.redwolf501.top/Article/details/gtspqgmnil.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcmzdtupw.html

Go:   end.Sub(start).Hours()
来源：http://dali.guannengcc.top/Article/details/gtfimuoqhm.html

Ruby: end - start                 # 返回秒数
来源：http://dali.sysykeji.top/Article/details/gttzrusfcq.html

C#:   (end - start).TotalSeconds
来源：http://dali.hysaishi.cn/Article/details/gtqtisjhzg.html

[J07] 比较两个日期
来源：http://dali.feifeiyinyue.top/Article/details/gtuswskqvf.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yongpay.top/Article/details/gtzjyumzwh.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.pycfn.com/Article/details/gtyzvvckna.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yj202588.top/Article/details/gtzjjglfgo.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.xuetiantiany.cn/Article/details/gtyvjjiyaf.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.chenjidiqi.icu/Article/details/gtoaazevkm.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.0kj1m.cn/Article/details/gtkitanayf.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.mhx1999.top/Article/details/gthoraxjff.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.0kj1m.cn/Article/details/gtlvlylbyi.html

[J08] 提取年月日与星期
来源：http://dali.guowangkeji.top/Article/details/gtwiluujrc.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.birdmap.top/Article/details/gtxcbaatwb.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhijiandao.cn/Article/details/gtbuqbfesx.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.fengsongda.top/Article/details/gtgcvrglcv.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.daxiang520.top/Article/details/gtzsoyigqr.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.cqqwz.cn/Article/details/gtknlfsngs.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzjmhvwmk.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yuanzhike.top/Article/details/gtltdhlimo.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hongshengwenyu.top/Article/details/gtkpajjzoh.html

[J09] 时区处理
来源：http://dali.fzhhl.top/Article/details/gtqhailkue.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.sweek.top/Article/details/gtgbupcele.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.haohaochexian.top/Article/details/gtqqlwaivn.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gogol.net.cn/Article/details/gtkaycmhoz.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gaohongyu789.top/Article/details/gtblfhwran.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.cashguo.top/Article/details/gteavryewc.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.sysykeji.top/Article/details/gtzbyxhypp.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtirkujvod.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.andypj.xyz/Article/details/gtjbvelipj.html

[J10] 取今天 / 本月第一天
来源：http://dali.hammf.cn/Article/details/gtzpeeeyea.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.cdnleiting.top/Article/details/gthzzqgvdj.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jqgfzy.top/Article/details/gtkuhnnjut.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgfswxeok.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yanxiufei.cn/Article/details/gtxapnjncn.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.ybcxt.top/Article/details/gttrznnyxa.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.shangyingyoupin.top/Article/details/gtlaxjleid.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.shangyingyoupin.top/Article/details/gtpzopljqz.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yvedp.cn/Article/details/gtxtieraqn.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtizekddmq.html

K. JSON 与序列化
来源：http://dali.aibaodan.cn/Article/details/gtsmzyevif.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtvelmggvl.html

[K01] 对象转 JSON 字符串
来源：http://dali.hammf.cn/Article/details/gtxitdruis.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.nanxinkj.top/Article/details/gtnlcjlacn.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.sxryk.cn/Article/details/gtbnsqnoqg.html

JS:   JSON.stringify(obj)
来源：http://dali.snrcjt.cn/Article/details/gtvnizqtmu.html

TS:   JSON.stringify(obj)
来源：http://dali.guowangkeji.top/Article/details/gtuaxlrfmq.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.cucudq.cn/Article/details/gtkenbtubk.html

Go:   json.Marshal(obj)
来源：http://dali.haohaochexian.top/Article/details/gtrxmmtneo.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jinqigufen.top/Article/details/gtfhnlgpej.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtppfmwypz.html

[K02] JSON 字符串转对象
来源：http://dali.chenlongwang.top/Article/details/gtsgsasyik.html

Py:   json.loads(s)
来源：http://dali.c1oappe.top/Article/details/gtjgkverda.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yueranfly.top/Article/details/gtksizwokq.html

JS:   JSON.parse(s)
来源：http://dali.yanxiufei.cn/Article/details/gtvarwqtbm.html

TS:   JSON.parse(s)
来源：http://dali.hammf.cn/Article/details/gtygxhgiwr.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.shanyushiyangtech.top/Article/details/gticptqbdr.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.mhx1999.top/Article/details/gtslhxsjij.html

Ruby: JSON.parse(s)
来源：http://dali.redwolf501.top/Article/details/gtpyxwrhdd.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jiagoushi.top/Article/details/gtmhfrofyc.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.tanke756.top/Article/details/gtufgkaggz.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.ehwqpu.com/Article/details/gtbupnkwaf.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jlsjyb.cn/Article/details/gtrjaejmxm.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.havefunace.top/Article/details/gtnsdbymab.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.ivvv.top/Article/details/gtvrgdycno.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.daxiang520.top/Article/details/gtmvlxzoxl.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.wangshuangyany.cn/Article/details/gtadnlpznp.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.shuidangran.top/Article/details/gtrywymbjn.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.chenzaomai.com/Article/details/gtcjunikko.html

[K04] 读取 JSON 文件
来源：http://dali.tanke756.top/Article/details/gtypdokrqp.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.cashguo.top/Article/details/gtvwfzsuzw.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jlsjyb.cn/Article/details/gtymquyiii.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.redwolf501.top/Article/details/gtqzuyhdku.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.vqdsnc.cn/Article/details/gtpaljgoyk.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yuxming.cn/Article/details/gtoqjcoflf.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.9152youxi.cn/Article/details/gtdlurjtik.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.shzxlz.cn/Article/details/gtjktsnphw.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.guowangkeji.top/Article/details/gteixddcxu.html

[K05] 深拷贝对象
来源：http://dali.xylfe.cn/Article/details/gtpgjwaagl.html

Py:   copy.deepcopy(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtjiljyoux.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jinghuilouyu.cn/Article/details/gtyqmwuqsx.html

JS:   structuredClone(obj)
来源：http://dali.cheryme.top/Article/details/gtrdwfhzim.html

TS:   structuredClone(obj)
来源：http://dali.xuanzx.com/Article/details/gtenslfuwb.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.haohaochexian.top/Article/details/gtldeemkgq.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.xziqi.cn/Article/details/gtspwrdaes.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.nanxuanxn.top/Article/details/gtqmlfrios.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.nanxinkj.top/Article/details/gtdvyumqcj.html

[K06] 解析 URL 查询串
来源：http://dali.zhengqikj.top/Article/details/gtjcqqogom.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.9152youxi.cn/Article/details/gtnceitvsp.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yj202588.top/Article/details/gtknaoctxe.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.dianchejie.cn/Article/details/gtmvllcjfq.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xuetiantiany.cn/Article/details/gtxfraqmgo.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.chenjidiqi.icu/Article/details/gtktkwlcyo.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jinqigufen.top/Article/details/gtbcdjwzfu.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gtdatupmod.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.birdmap.top/Article/details/gttoojqxfu.html

[K07] 进制转换
来源：http://dali.jiagoushi.top/Article/details/gttmnintcr.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.guannengcc.top/Article/details/gtylviftxq.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhongyouzk.top/Article/details/gtxfxxfrpn.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.shangyingyoupin.top/Article/details/gttuworrvc.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.316326.xyz/Article/details/gtoswregjl.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.dianchejie.cn/Article/details/gthheuiwjd.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.hongshengwenyu.top/Article/details/gtrcxbherc.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yangfankeji.com/Article/details/gtymygxcdy.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.shanyushiyangtech.top/Article/details/gtvtuakqyv.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.dashuyun.cn/Article/details/gtshmzxvhu.html

Py:   pickle.dumps(obj)
来源：http://dali.zdqjudy.top/Article/details/gtnfpzsesf.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.snrcjt.cn/Article/details/gttbrznqjd.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmcfmrogr.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwvvtjxjq.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.nanxinkj.top/Article/details/gtkxsxayxm.html

Go:   encoding/gob
来源：http://dali.sysykeji.top/Article/details/gtotnpeeze.html

Ruby: Marshal.dump(obj)
来源：http://dali.sxryk.cn/Article/details/gtgdzwtltt.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.shanyushiyangtech.top/Article/details/gtmsnvxpvv.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtdfncjpew.html

L. 网络请求
来源：http://dali.xylfe.cn/Article/details/gtzxvcninc.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gttifuemyk.html

[L01] 发送 GET 请求
来源：http://dali.xuetiantiany.cn/Article/details/gtoqughiux.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.316326.xyz/Article/details/gteijwzufl.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.feifeiyinyue.top/Article/details/gtvjlkdqvd.html

JS:   await fetch(url)
来源：http://dali.gaohongyu789.top/Article/details/gtioyzdhub.html

TS:   await fetch(url)
来源：http://dali.yj20258.top/Article/details/gtstijleie.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.hnqzz.top/Article/details/gtwyqubqst.html

Go:   resp, err := http.Get(url)
来源：http://dali.gogol.net.cn/Article/details/gtchjwvakc.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.shzxlz.cn/Article/details/gttgeyucdz.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.fengsongda.top/Article/details/gtytqllvqn.html

[L02] 发送 POST JSON
来源：http://dali.jinqigufen.top/Article/details/gtiydplkup.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.redwolf501.top/Article/details/gtmguftvpr.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmmktqsew.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.guannengcc.top/Article/details/gtoqlmzqkp.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuujmvoze.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhengqikj.top/Article/details/gtxnhjdpyf.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jlsjyb.cn/Article/details/gtkwjlqdnl.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yuxming.cn/Article/details/gtdqhbbadq.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.gaohongyu789.top/Article/details/gtnmdqdoea.html

[L03] 设置自定义请求头
来源：http://dali.havefunace.top/Article/details/gtnfsulwev.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.sysykeji.top/Article/details/gtblkzfjuv.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.kuanghao11.cn/Article/details/gtzwavhfmr.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hongshengwenyu.top/Article/details/gtrhjyzdzc.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yongpay.top/Article/details/gtzzbbmatt.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.smart0.xyz/Article/details/gtiledikmq.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yuanzhike.top/Article/details/gtdvuryuso.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.xuetiantiany.cn/Article/details/gttcmiqsbj.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gtwntayact.html

[L04] 设置超时
来源：http://dali.gaohongyu789.top/Article/details/gtmxxyghvu.html

Py:   requests.get(url, timeout=5)
来源：http://dali.wangshuangyany.cn/Article/details/gtahbgdrbd.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jqgfzy.top/Article/details/gtvfcjlwvs.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.c1oappe.top/Article/details/gtphmfesem.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yonumen.top/Article/details/gtzessfpba.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jianghu66.top/Article/details/gtzyuprlne.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.316326.xyz/Article/details/gtzakadsmf.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.fzhhl.top/Article/details/gtvhxihety.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.cucudq.cn/Article/details/gtlbzkirbe.html

[L05] 上传文件（multipart）
来源：http://dali.zhengqikj.top/Article/details/gtwpnzgjwy.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zdqjudy.top/Article/details/gtquoulwxq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhiwuduotai.top/Article/details/gtgakmxeyw.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.cucudq.cn/Article/details/gtnqbecyjb.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.smart0.xyz/Article/details/gtcthkxoas.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.sweek.top/Article/details/gtaafpkzgj.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.9152youxi.cn/Article/details/gteqdnrhtg.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yonumen.top/Article/details/gtdipijefg.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gthkcocayg.html

[L06] 解析响应为 JSON
来源：http://dali.jlsjyb.cn/Article/details/gtcysdohiv.html

Py:   resp.json()
来源：http://dali.svipenyu.cn/Article/details/gtdxmubbza.html

PHP:  json_decode($body, true);
来源：http://dali.chenjidiqi.icu/Article/details/gtxnpngurb.html

JS:   await resp.json()
来源：http://dali.ehwqpu.com/Article/details/gtgwvlzgen.html

TS:   await resp.json()
来源：http://dali.redwolf501.top/Article/details/gtsguojolp.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.hywenlv.cn/Article/details/gtmzkqjxag.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhengqikj.top/Article/details/gtzydaqnra.html

Ruby: JSON.parse(resp.body)
来源：http://dali.cucudq.cn/Article/details/gtrydeunmj.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.sweek.top/Article/details/gtloxoyvuv.html

[L07] 处理 HTTP 状态码
来源：http://dali.daxiang520.top/Article/details/gtzmrjxqfa.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.yuanzhike.top/Article/details/gteqrhftem.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.svipenyu.cn/Article/details/gthfetpioa.html

JS:   resp.ok;  resp.status
来源：http://dali.xuanzx.com/Article/details/gtwbgquavt.html

TS:   resp.ok;  resp.status
来源：http://dali.ivvv.top/Article/details/gtumbqvgkc.html

Java: resp.statusCode()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkwpwkqyh.html

Go:   resp.StatusCode
来源：http://dali.hnqzz.top/Article/details/gtflhkwtjs.html

Ruby: resp.code.to_i
来源：http://dali.zhiwuduotai.top/Article/details/gtaokutlvt.html

C#:   (int)resp.StatusCode
来源：http://dali.jyoumei.cn/Article/details/gthoyjmdln.html

[L08] 并发请求多个地址
来源：http://dali.cashguo.top/Article/details/gtimopgvis.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zycfv.cn/Article/details/gtkhnhdrem.html

PHP:  curl_multi_init() 系列
来源：http://dali.smart0.xyz/Article/details/gtpqzlzwge.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.guowangkeji.top/Article/details/gtjztazcee.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhongyouzk.top/Article/details/gtsvdfnqqf.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.pengpengdd.cyou/Article/details/gtiyhcznul.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhongyouzk.top/Article/details/gtyzzvbsgk.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtggrcjdpq.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.chenjidiqi.icu/Article/details/gtfgcwvfqe.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtgfsuqkke.html

M. 命令行 / 进程 / 环境
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrivlgtcg.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtjyjfdfge.html

[M01] 读取命令行参数
来源：http://dali.jianghu66.top/Article/details/gtsdunjltg.html

Py:   sys.argv[1:]
来源：http://dali.jyoumei.cn/Article/details/gtnsjnvdyw.html

PHP:  $argv;  $argc;
来源：http://dali.quarkkingdee.top/Article/details/gtjtoxdmrz.html

JS:   process.argv.slice(2)
来源：http://dali.9152youxi.cn/Article/details/gtbhwkhztn.html

TS:   process.argv.slice(2)
来源：http://dali.dianchejie.cn/Article/details/gtywprkwco.html

Java: args 数组（main 方法参数）
来源：http://dali.0kj1m.cn/Article/details/gtttvleahz.html

Go:   os.Args[1:]
来源：http://dali.cheryme.top/Article/details/gtcyypwwzd.html

Ruby: ARGV
来源：http://dali.yvedp.cn/Article/details/gtgsrskpmo.html

C#:   args 数组（Main 方法参数）
来源：http://dali.iojbl.cn/Article/details/gtyhxsjvxo.html

[M02] 读取环境变量
来源：http://dali.cucudq.cn/Article/details/gtjlqoucpc.html

Py:   os.environ.get("HOME")
来源：http://dali.yonumen.top/Article/details/gtkkytvhrq.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.xziqi.cn/Article/details/gtfrhvwxnl.html

JS:   process.env.HOME
来源：http://dali.yanxiufei.cn/Article/details/gtnlhntubh.html

TS:   process.env.HOME
来源：http://dali.zhengqikj.top/Article/details/gtmkqsxsfs.html

Java: System.getenv("HOME")
来源：http://dali.wangshuangyany.cn/Article/details/gtrgihwzfk.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jqgfzy.top/Article/details/gtgkewrbbe.html

Ruby: ENV["HOME"]
来源：http://dali.andypj.xyz/Article/details/gtewamvcli.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.nanxinkj.top/Article/details/gtlstljnws.html

[M03] 执行外部命令
来源：http://dali.hnqzz.top/Article/details/gtqedheppv.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.daxiang520.top/Article/details/gtxdcjxlti.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.cucudq.cn/Article/details/gtmbunrkhm.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.chenjidiqi.icu/Article/details/gtyleassqa.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jiagoushi.top/Article/details/gtheoviymw.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yj20258888.top/Article/details/gtzfhjwpnk.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.kuanghao11.cn/Article/details/gtgnhbiwjj.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhiwuduotai.top/Article/details/gtdxifhlzp.html

C#:   Process.Start("ls", "-l");
来源：http://dali.ppjwa.cn/Article/details/gtshpxuqtv.html

[M04] 获取当前工作目录
来源：http://dali.pengpengdd.cyou/Article/details/gtztdrflho.html

Py:   os.getcwd()
来源：http://dali.zhengqikj.top/Article/details/gtqopaupdt.html

PHP:  getcwd();
来源：http://dali.jlsjyb.cn/Article/details/gtddpgruva.html

JS:   process.cwd()
来源：http://dali.ehwqpu.com/Article/details/gtrggpzskj.html

TS:   process.cwd()
来源：http://dali.daxiang520.top/Article/details/gtwjtitxdg.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.hfpthk.cn/Article/details/gtmthosgoe.html

Go:   os.Getwd()
来源：http://dali.xinyue.icu/Article/details/gtrkyppfuq.html

Ruby: Dir.pwd
来源：http://dali.shzxlz.cn/Article/details/gtowobztel.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zdqjudy.top/Article/details/gtfkoojddx.html

[M05] 设置退出码
来源：http://dali.sysykeji.top/Article/details/gtwlerxfld.html

Py:   sys.exit(1)
来源：http://dali.nanxinkj.top/Article/details/gtijprtatj.html

PHP:  exit(1);
来源：http://dali.dianchejie.cn/Article/details/gtppojzmgc.html

JS:   process.exit(1)
来源：http://dali.dianchejie.cn/Article/details/gtjgyruptf.html

TS:   process.exit(1)
来源：http://dali.ppjwa.cn/Article/details/gtkhnucokd.html

Java: System.exit(1)
来源：http://dali.hywenlv.cn/Article/details/gttkomqffi.html

Go:   os.Exit(1)
来源：http://dali.chenlongwang.top/Article/details/gtlkkcyhec.html

Ruby: exit 1
来源：http://dali.chenlongwang.top/Article/details/gtgmuegfob.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.tanke756.top/Article/details/gtaubclxlr.html

[M06] 向标准错误输出
来源：http://dali.jyoumei.cn/Article/details/gtwzpjzhkz.html

Py:   print("err", file=sys.stderr)
来源：http://dali.quarkkingdee.top/Article/details/gtascpbape.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.shuidangran.top/Article/details/gtvsiwiblv.html

JS:   console.error("err")
来源：http://dali.cashguo.top/Article/details/gtxwenprzb.html

TS:   console.error("err")
来源：http://dali.guowangkeji.top/Article/details/gtoquelhmn.html

Java: System.err.println("err")
来源：http://dali.yuanzhike.top/Article/details/gtkiyoxwac.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.aibaodan.cn/Article/details/gtxyqeiikx.html

Ruby: warn "err"
来源：http://dali.cheryme.top/Article/details/gtlgrncgqd.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.smart0.xyz/Article/details/gttzczuwhq.html

[M07] 判断是否为主入口
来源：http://dali.fengsongda.top/Article/details/gtbitaiyxe.html


<!-- 参考信息 -->