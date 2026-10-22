代发 wailian999

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.chenzaomai.com/Article/details/gtamjmgkwm.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cdnleiting.top/Article/details/gtdhhvsubk.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhengqikj.top/Article/details/gtdtyijuhm.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yj20258888.top/Article/details/gtcharwxdi.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.guannengcc.top/Article/details/gtvdgrqblw.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.aizwys.cn/Article/details/gtpucbscdp.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlvaamgem.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtyxrraywn.html

J. 日期与时间
来源：http://dali.hnxiangtu.top/Article/details/gtfwkoiovf.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtjlvsykll.html

[J01] 获取当前时间
来源：http://dali.daria6918.cn/Article/details/gtaxoacrfc.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.kuanghao11.cn/Article/details/gtfcynkagm.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.vqdsnc.cn/Article/details/gtuvkmmgzv.html

JS:   new Date();  Date.now()
来源：http://dali.daria6918.cn/Article/details/gtbnkmhrjr.html

TS:   new Date();  Date.now()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrvqumpfz.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.ybcxt.top/Article/details/gtammuwasd.html

Go:   time.Now()
来源：http://dali.jqgfzy.top/Article/details/gtedzcsvsc.html

Ruby: Time.now
来源：http://dali.kuanghao11.cn/Article/details/gthsdgdndl.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.ywan-chungtsiang.top/Article/details/gttudttvhq.html

[J02] 格式化输出
来源：http://dali.hnqzz.top/Article/details/gtfrqkrjmp.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ybcxt.top/Article/details/gtubnqolop.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.hongshengwenyu.top/Article/details/gtqxlpkoag.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.xziqi.cn/Article/details/gthqtfpoum.html

TS:   d.toISOString()
来源：http://dali.chenjidiqi.icu/Article/details/gtoiafbyzs.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.sxryk.cn/Article/details/gtwmmtrmgf.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yueranfly.top/Article/details/gtyrtrcqhz.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shangyingyoupin.top/Article/details/gttzhpfeoi.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.shanyushiyangtech.top/Article/details/gtamubaspq.html

[J03] 字符串解析为日期
来源：http://dali.yj20258.top/Article/details/gtupgcoqwy.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.kuanghao11.cn/Article/details/gtaupmkvvy.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yonumen.top/Article/details/gtcvzpibdv.html

JS:   new Date("2024-01-02")
来源：http://dali.hywenlv.cn/Article/details/gtderxxxmi.html

TS:   new Date("2024-01-02")
来源：http://dali.chenlongwang.top/Article/details/gtuhmeiqvb.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hfpthk.cn/Article/details/gthlwjihsv.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.havefunace.top/Article/details/gttwjwevvr.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.cqqwz.cn/Article/details/gtyywdsvxc.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.wangdashe.top/Article/details/gtgxsxqdee.html

[J04] 时间戳与日期互转
来源：http://dali.cheryme.top/Article/details/gtymkrckwo.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.wangdashe.top/Article/details/gtsloavrfj.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jqgfzy.top/Article/details/gtqbkoavxk.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.316326.xyz/Article/details/gtmbagtodo.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwngvrypm.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.hnqzz.top/Article/details/gtobtowlgz.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.tanke756.top/Article/details/gtusaskjql.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.shzxlz.cn/Article/details/gtumfzwqsn.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.gogol.net.cn/Article/details/gtfvugkpco.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhoulong.xyz/Article/details/gtumucvuxu.html

Py:   now + timedelta(days=7)
来源：http://dali.yvedp.cn/Article/details/gtzdyjjoxm.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yj202588.top/Article/details/gtldqwgnsz.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jiagoushi.top/Article/details/gtuhnnzrto.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yongpay.top/Article/details/gtvunrxlyv.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.shangyingyoupin.top/Article/details/gtaaketubt.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.gogol.net.cn/Article/details/gtjmtixbix.html

Ruby: Time.now + 7 * 86400
来源：http://dali.xziqi.cn/Article/details/gtxlklwkyb.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yangfankeji.com/Article/details/gtvhvdbkkv.html

[J06] 计算两时间之差
来源：http://dali.gotoacloud.top/Article/details/gtixgcdxrq.html

Py:   (end - start).total_seconds()
来源：http://dali.haohaochexian.top/Article/details/gtqvpyhxcw.html

PHP:  $end->diff($start)->days;
来源：http://dali.yj20258888.top/Article/details/gtvqcrjyvx.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.cucudq.cn/Article/details/gtghogqkbv.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.316326.xyz/Article/details/gtmfpdflzh.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jinqigfzy.top/Article/details/gtwifwqbmr.html

Go:   end.Sub(start).Hours()
来源：http://dali.gaohongyu789.top/Article/details/gthiblnhie.html

Ruby: end - start                 # 返回秒数
来源：http://dali.tanke756.top/Article/details/gteunetegr.html

C#:   (end - start).TotalSeconds
来源：http://dali.yvedp.cn/Article/details/gtjktfrupu.html

[J07] 比较两个日期
来源：http://dali.tianlin.xyz/Article/details/gtqcepwjxp.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.birdmap.top/Article/details/gtffvbkcgi.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yj20258888.top/Article/details/gtcnzqylyq.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.haohaochexian.top/Article/details/gtoqlaadrw.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.daxiang520.top/Article/details/gtxigkbnck.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.dashuyun.cn/Article/details/gtqrlnmzwe.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jyoumei.cn/Article/details/gtcefrqzpf.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jianghu66.top/Article/details/gtwhksenif.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yongpay.top/Article/details/gtvfqrqetc.html

[J08] 提取年月日与星期
来源：http://dali.cheryme.top/Article/details/gtjyplqsay.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.0kj1m.cn/Article/details/gtxkqtnlth.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhiwuduotai.top/Article/details/gtfqgilfqj.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.xziqi.cn/Article/details/gtghandhmp.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jyoumei.cn/Article/details/gtwfqupktc.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.nwbrower.top/Article/details/gtztbxhoed.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.sysykeji.top/Article/details/gtiqoxogsj.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.pengpengdd.cyou/Article/details/gtwmowcsyo.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.nwbrower.top/Article/details/gtozeakiwp.html

[J09] 时区处理
来源：http://dali.shangyingyoupin.top/Article/details/gtrnttruzy.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.fzhhl.top/Article/details/gtkpqlyoem.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.cqqwz.cn/Article/details/gtatiyqdof.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hysaishi.cn/Article/details/gthfuvzsuk.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shuidangran.top/Article/details/gtinilecog.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.ydzc1.top/Article/details/gtanntkppu.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.guannengcc.top/Article/details/gtzolrbccy.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhiwuduotai.top/Article/details/gtfawkxjif.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.iojbl.cn/Article/details/gtqivyxsnw.html

[J10] 取今天 / 本月第一天
来源：http://dali.birdmap.top/Article/details/gthtqafjyz.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.aizwys.cn/Article/details/gtguaagrfg.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.chenzaomai.com/Article/details/gtlolhweuw.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yuanzhike.top/Article/details/gthqnfibke.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.redwolf501.top/Article/details/gtsgdftsrc.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.guannengcc.top/Article/details/gtzbcrtgly.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.dashuyun.cn/Article/details/gtfykhfidn.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.xuetiantiany.cn/Article/details/gtffhxzysd.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.chenzaomai.com/Article/details/gtzvtttfej.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtakgrpobw.html

K. JSON 与序列化
来源：http://dali.redwolf501.top/Article/details/gtheelyxef.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gthfsytyof.html

[K01] 对象转 JSON 字符串
来源：http://dali.kuanghao11.cn/Article/details/gtddllqyky.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.tianlin.xyz/Article/details/gtxffheayj.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhoulong.xyz/Article/details/gtttbkcyzj.html

JS:   JSON.stringify(obj)
来源：http://dali.fengsongda.top/Article/details/gtexiscbut.html

TS:   JSON.stringify(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtbptnsyuf.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.daxiang520.top/Article/details/gtgvzbgohe.html

Go:   json.Marshal(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtsfczmyve.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hammf.cn/Article/details/gtznasmigo.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.ppjwa.cn/Article/details/gtwyxakiej.html

[K02] JSON 字符串转对象
来源：http://dali.daxiang520.top/Article/details/gtqirvstyp.html

Py:   json.loads(s)
来源：http://dali.xinyue.icu/Article/details/gtrfvnjywj.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.quarkkingdee.top/Article/details/gtgjbrzgef.html

JS:   JSON.parse(s)
来源：http://dali.kuanghao11.cn/Article/details/gtjcaacqwa.html

TS:   JSON.parse(s)
来源：http://dali.svipenyu.cn/Article/details/gtcqpgzpvi.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.shanyushiyangtech.top/Article/details/gtpwuthjys.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.guowangkeji.top/Article/details/gtjzqczlbr.html

Ruby: JSON.parse(s)
来源：http://dali.hnqzz.top/Article/details/gtxtrxeyzn.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yanxiufei.cn/Article/details/gttlqgfhwk.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.gogol.net.cn/Article/details/gtwgwduyrg.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.guowangkeji.top/Article/details/gtrggodaqe.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.tanke756.top/Article/details/gtiabgnzks.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yj202588.top/Article/details/gtfwalswje.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.cqqwz.cn/Article/details/gttuafteak.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.cqqwz.cn/Article/details/gtlclbhzai.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.xuanzx.com/Article/details/gtvwipukrx.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yj202588.top/Article/details/gttbjnpybv.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yj202588.top/Article/details/gtmeozxluz.html

[K04] 读取 JSON 文件
来源：http://dali.sysykeji.top/Article/details/gtrscfinkn.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.tian-w.cn/Article/details/gteqqanpvd.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.tianlin.xyz/Article/details/gtxgqzgibp.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrovcfgtw.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.pycfn.com/Article/details/gtcqgjwjmp.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.tianlin.xyz/Article/details/gtsftucjxr.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbpmfoffr.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.xziqi.cn/Article/details/gtychwzjbq.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yueranfly.top/Article/details/gtprigcfmy.html

[K05] 深拷贝对象
来源：http://dali.feifeiyinyue.top/Article/details/gtwjpyjzcn.html

Py:   copy.deepcopy(obj)
来源：http://dali.meibo888.top/Article/details/gtnvmpwknp.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yongpay.top/Article/details/gtsftavnzw.html

JS:   structuredClone(obj)
来源：http://dali.cqqwz.cn/Article/details/gtqyezpmpt.html

TS:   structuredClone(obj)
来源：http://dali.pycfn.com/Article/details/gtcxtgcewc.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.sysykeji.top/Article/details/gtdijrxdqg.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjqiiimsv.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.9152youxi.cn/Article/details/gtiaejoxea.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.tanke756.top/Article/details/gtsrxgtoew.html

[K06] 解析 URL 查询串
来源：http://dali.snrcjt.cn/Article/details/gttyvypxmj.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhixingplan.top/Article/details/gtumxrxnck.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.hongshengwenyu.top/Article/details/gtsufqhxhb.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.gotoacloud.top/Article/details/gttzrfdons.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.cashguo.top/Article/details/gtrildkmsv.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jianghu66.top/Article/details/gttogelayg.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yj20258.top/Article/details/gtlcxhwruq.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.shzxlz.cn/Article/details/gtdssqlxdo.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.c1oappe.top/Article/details/gtapcwciow.html

[K07] 进制转换
来源：http://dali.sweek.top/Article/details/gtqlllffkn.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.ehwqpu.com/Article/details/gtzgblbyll.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jiagoushi.top/Article/details/gtqehsraxd.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.cdnleiting.top/Article/details/gthfjjrzek.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.chenlongwang.top/Article/details/gtdxrzynhs.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.sxryk.cn/Article/details/gtzjuzwhzk.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.wangshuangyany.cn/Article/details/gtahvkkksm.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.ehwqpu.com/Article/details/gtedwhtuqf.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhongyouzk.top/Article/details/gtygwpctlz.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhoulong.xyz/Article/details/gtlajmlzxv.html

Py:   pickle.dumps(obj)
来源：http://dali.zhoulong.xyz/Article/details/gttklbiyjw.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.hywenlv.cn/Article/details/gtycsnltrg.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.hongshengwenyu.top/Article/details/gtbelzwxjm.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jyoumei.cn/Article/details/gtbkaizohl.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.shzxlz.cn/Article/details/gtxxgrwhrf.html

Go:   encoding/gob
来源：http://dali.zhengqikj.top/Article/details/gtfgwhlpdt.html

Ruby: Marshal.dump(obj)
来源：http://dali.daria6918.cn/Article/details/gtqfybyuvs.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.nanxinkj.top/Article/details/gtrvwcfsnb.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtapzkqvqc.html

L. 网络请求
来源：http://dali.c1oappe.top/Article/details/gtkgoyprxr.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtbsrouwfv.html

[L01] 发送 GET 请求
来源：http://dali.jinyuanbaomall.cn/Article/details/gthfpxpbqi.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.birdmap.top/Article/details/gtcypsjhbm.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yanxiufei.cn/Article/details/gtgxsqhmtp.html

JS:   await fetch(url)
来源：http://dali.gogol.net.cn/Article/details/gthkpsgkwa.html

TS:   await fetch(url)
来源：http://dali.hongshengwenyu.top/Article/details/gtehyefpqy.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.wangshuangyany.cn/Article/details/gtzoyajqqs.html

Go:   resp, err := http.Get(url)
来源：http://dali.shanyushiyangtech.top/Article/details/gtqmjbsxrm.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yangfankeji.com/Article/details/gtymgylnlc.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yvedp.cn/Article/details/gtuamqvxet.html

[L02] 发送 POST JSON
来源：http://dali.ppjwa.cn/Article/details/gtvsvwthnt.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.316326.xyz/Article/details/gtjvqbslfk.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.chenzaomai.com/Article/details/gtntmqwtgf.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwqbkkbvr.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gthlupdwne.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yanxiufei.cn/Article/details/gtizydglvh.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.guannengcc.top/Article/details/gtzaimufyz.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.daria6918.cn/Article/details/gtpkamhcrl.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhongyouzk.top/Article/details/gtdhxkaewj.html

[L03] 设置自定义请求头
来源：http://dali.ivvv.top/Article/details/gtpgizmdjj.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zycfv.cn/Article/details/gtucxuragk.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhixingplan.top/Article/details/gtmhoezsti.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yueranfly.top/Article/details/gtyfjeglxh.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.quarkkingdee.top/Article/details/gtwochdbek.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yuanzhike.top/Article/details/gtpwmvsvmw.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.shuidangran.top/Article/details/gtnqqllapp.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.fzhhl.top/Article/details/gtqakkdufh.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.hywenlv.cn/Article/details/gtphcmhoiq.html

[L04] 设置超时
来源：http://dali.sysykeji.top/Article/details/gtrnwakegr.html

Py:   requests.get(url, timeout=5)
来源：http://dali.shzxlz.cn/Article/details/gtmxsxjqgg.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.redwolf501.top/Article/details/gtjfsnftyk.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.pycfn.com/Article/details/gtnacznjst.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.316326.xyz/Article/details/gtapndlvjv.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.tanke756.top/Article/details/gtlpqimqte.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yongpay.top/Article/details/gtxhmkaixm.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jianghu66.top/Article/details/gtqyfthhab.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.cqqwz.cn/Article/details/gtwbbsxeug.html

[L05] 上传文件（multipart）
来源：http://dali.yanxiufei.cn/Article/details/gtqgkzygpr.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.chenlongwang.top/Article/details/gtzwejwmcd.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.meibo888.top/Article/details/gtkbnwfgas.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.316326.xyz/Article/details/gtvprngjop.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.kuanghao11.cn/Article/details/gtdpqukmfb.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jlsjyb.cn/Article/details/gtrlewtwjx.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yueranfly.top/Article/details/gtzejfuesw.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yj20258888.top/Article/details/gtnqhjedsp.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.pycfn.com/Article/details/gtehflnwue.html

[L06] 解析响应为 JSON
来源：http://dali.guowangkeji.top/Article/details/gtznvsyqut.html

Py:   resp.json()
来源：http://dali.yj202588.top/Article/details/gtdffmljdu.html

PHP:  json_decode($body, true);
来源：http://dali.tianlin.xyz/Article/details/gtwhlrqzxo.html

JS:   await resp.json()
来源：http://dali.aizwys.cn/Article/details/gtmbpiddtz.html

TS:   await resp.json()
来源：http://dali.316326.xyz/Article/details/gtblnamkis.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.wangdashe.top/Article/details/gtmdytkdnq.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.bjfxy.top/Article/details/gtzyyiyjtb.html

Ruby: JSON.parse(resp.body)
来源：http://dali.xinyue.icu/Article/details/gtbdvkbcto.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yj20258888.top/Article/details/gtiamncfut.html

[L07] 处理 HTTP 状态码
来源：http://dali.tanke756.top/Article/details/gtjsmzxtwm.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.c1oappe.top/Article/details/gtjvfchlvs.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jinghuilouyu.cn/Article/details/gtflirhwfq.html

JS:   resp.ok;  resp.status
来源：http://dali.sweek.top/Article/details/gtbsbhxpsn.html

TS:   resp.ok;  resp.status
来源：http://dali.yj20258888.top/Article/details/gtzyqclpio.html

Java: resp.statusCode()
来源：http://dali.jiagoushi.top/Article/details/gtmfcquzaa.html

Go:   resp.StatusCode
来源：http://dali.fzhhl.top/Article/details/gtltxhfjmc.html

Ruby: resp.code.to_i
来源：http://dali.yonumen.top/Article/details/gtkxlmcndl.html

C#:   (int)resp.StatusCode
来源：http://dali.jianghu66.top/Article/details/gtvwvmiodg.html

[L08] 并发请求多个地址
来源：http://dali.guannengcc.top/Article/details/gtprfwdfie.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yj20258888.top/Article/details/gtoeolmvca.html

PHP:  curl_multi_init() 系列
来源：http://dali.fengsongda.top/Article/details/gtqrffyzxz.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gtwvczxvfc.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ybcxt.top/Article/details/gtdtalcdjw.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.pycfn.com/Article/details/gttqkaarab.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yonumen.top/Article/details/gtiofxfbhe.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.bjfxy.top/Article/details/gtmibetuew.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhengqikj.top/Article/details/gtkvslheed.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtajosfopq.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhoulong.xyz/Article/details/gtmsgnqjnv.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtelvpjstw.html

[M01] 读取命令行参数
来源：http://dali.hywenlv.cn/Article/details/gtmffqekmy.html

Py:   sys.argv[1:]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkpxmvrnl.html

PHP:  $argv;  $argc;
来源：http://dali.yj20258.top/Article/details/gtlhidzopl.html

JS:   process.argv.slice(2)
来源：http://dali.xuanzx.com/Article/details/gtsgxehyux.html

TS:   process.argv.slice(2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtrbokpgii.html

Java: args 数组（main 方法参数）
来源：http://dali.nwbrower.top/Article/details/gtcaytkcxe.html

Go:   os.Args[1:]
来源：http://dali.sxryk.cn/Article/details/gtuovuqrxb.html

Ruby: ARGV
来源：http://dali.hammf.cn/Article/details/gtdncmyhes.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yonumen.top/Article/details/gtgbhrcuyq.html

[M02] 读取环境变量
来源：http://dali.zhongyouzk.top/Article/details/gtldohmhsy.html

Py:   os.environ.get("HOME")
来源：http://dali.ivvv.top/Article/details/gtrzwmrzeu.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.chenlongwang.top/Article/details/gtqwlnoekf.html

JS:   process.env.HOME
来源：http://dali.cqqwz.cn/Article/details/gtrkyztvne.html

TS:   process.env.HOME
来源：http://dali.0kj1m.cn/Article/details/gtqvoummsz.html

Java: System.getenv("HOME")
来源：http://dali.feifeiyinyue.top/Article/details/gtkbfxiqfx.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.snrcjt.cn/Article/details/gtryefygmu.html

Ruby: ENV["HOME"]
来源：http://dali.tanke756.top/Article/details/gttthixrwq.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.tanke756.top/Article/details/gtqisdignr.html

[M03] 执行外部命令
来源：http://dali.jinghuilouyu.cn/Article/details/gthnriajpn.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.xinyue.icu/Article/details/gtmizxayfg.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hammf.cn/Article/details/gtdakziqix.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.ppjwa.cn/Article/details/gtulamochn.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.shanyushiyangtech.top/Article/details/gtqnbnilvc.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtabisgmgu.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.fzhhl.top/Article/details/gthrsnaztk.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.chenzaomai.com/Article/details/gtzayweios.html

C#:   Process.Start("ls", "-l");
来源：http://dali.nanxuanxn.top/Article/details/gtiojvkzkm.html

[M04] 获取当前工作目录
来源：http://dali.hnqzz.top/Article/details/gtjnokwaaq.html

Py:   os.getcwd()
来源：http://dali.cqqwz.cn/Article/details/gtluwtklno.html

PHP:  getcwd();
来源：http://dali.birdmap.top/Article/details/gtbekrmbso.html

JS:   process.cwd()
来源：http://dali.cucudq.cn/Article/details/gtcwubzqbq.html

TS:   process.cwd()
来源：http://dali.gogol.net.cn/Article/details/gtlntuaheo.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.ydzc1.top/Article/details/gtgcnyikgk.html

Go:   os.Getwd()
来源：http://dali.yueranfly.top/Article/details/gtxnnylimv.html

Ruby: Dir.pwd
来源：http://dali.yonumen.top/Article/details/gtbmsmnqll.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhiwuduotai.top/Article/details/gtdqpetays.html

[M05] 设置退出码
来源：http://dali.birdmap.top/Article/details/gtahqqafqr.html

Py:   sys.exit(1)
来源：http://dali.xuetiantiany.cn/Article/details/gtbchrmxex.html

PHP:  exit(1);
来源：http://dali.9152youxi.cn/Article/details/gtsgoneaeb.html

JS:   process.exit(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtebgbuemh.html

TS:   process.exit(1)
来源：http://dali.hnxiangtu.top/Article/details/gtkfxpikho.html

Java: System.exit(1)
来源：http://dali.shzxlz.cn/Article/details/gtaccvwcqr.html

Go:   os.Exit(1)
来源：http://dali.xuetiantiany.cn/Article/details/gtwpexhjva.html

Ruby: exit 1
来源：http://dali.zhoulong.xyz/Article/details/gtikgstrue.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.bjfxy.top/Article/details/gtlreqvarg.html

[M06] 向标准错误输出
来源：http://dali.andypj.xyz/Article/details/gtspdlfrvp.html

Py:   print("err", file=sys.stderr)
来源：http://dali.9152youxi.cn/Article/details/gtjncwacgb.html


<!-- 参考信息 -->