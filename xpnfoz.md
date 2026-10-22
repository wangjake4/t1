代发 wailian999

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.shangyingyoupin.top/Article/details/gt2mapmkuud.html

TS:   /error/gim
来源：http://dali.shuidangran.top/Article/details/gt2gzxsusxy.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.tianlin.xyz/Article/details/gt2tnmjdrvy.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.ydzc1.top/Article/details/gt2upyshhcv.html

Ruby: s.scan(/error/i)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gxstofaw.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jianghu66.top/Article/details/gt2iaofupeb.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.cheryme.top/Article/details/gt2vhvueykc.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.shzxlz.cn/Article/details/gt2zesrgmjo.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pxqkscfj.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.aibaodan.cn/Article/details/gt2ggggxytv.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.pengpengdd.cyou/Article/details/gt2wjhvofwg.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.sxryk.cn/Article/details/gt2qqqcnqlr.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kcwkxxwh.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.9152youxi.cn/Article/details/gt2yxcublcq.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.hfpthk.cn/Article/details/gt2axknuxit.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2tqwwrpmp.html

J. 日期与时间
来源：http://dali.hammf.cn/Article/details/gt2skypyqrl.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2vmgayqay.html

[J01] 获取当前时间
来源：http://dali.xuanzx.com/Article/details/gt2ferdgfom.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.chenjidiqi.icu/Article/details/gt2vxsjbhvt.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cvezhmmt.html

JS:   new Date();  Date.now()
来源：http://dali.wangshuangyany.cn/Article/details/gt2outtoxsp.html

TS:   new Date();  Date.now()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eweljdzf.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.ivvv.top/Article/details/gt2dkcomknb.html

Go:   time.Now()
来源：http://dali.shangyingyoupin.top/Article/details/gt2xuzybenj.html

Ruby: Time.now
来源：http://dali.cdnleiting.top/Article/details/gt2uzqxjtxx.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yuxming.cn/Article/details/gt2zagpomvg.html

[J02] 格式化输出
来源：http://dali.hnxiangtu.top/Article/details/gt2gfbvmbfi.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yvedp.cn/Article/details/gt2omrsordx.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.ehwqpu.com/Article/details/gt2krexezcd.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.tian-w.cn/Article/details/gt2gziavjju.html

TS:   d.toISOString()
来源：http://dali.bjfxy.top/Article/details/gt2zyaqmzqv.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhoulong.xyz/Article/details/gt2orsranlf.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.pycfn.com/Article/details/gt2ybgfsavh.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.316326.xyz/Article/details/gt2lwljzqbl.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zdqjudy.top/Article/details/gt2yscpwetf.html

[J03] 字符串解析为日期
来源：http://dali.quarkkingdee.top/Article/details/gt2ononegzc.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zdqjudy.top/Article/details/gt2dwcneahh.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.fzhhl.top/Article/details/gt2ckuqxavf.html

JS:   new Date("2024-01-02")
来源：http://dali.zhoulong.xyz/Article/details/gt2fvimfqnz.html

TS:   new Date("2024-01-02")
来源：http://dali.sxryk.cn/Article/details/gt2jgyhihdl.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhongyouzk.top/Article/details/gt2gdobtqbf.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jinqigufen.top/Article/details/gt2ecvclycs.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yanxiufei.cn/Article/details/gt2wxpdwicj.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.sysykeji.top/Article/details/gt2nyihjgfp.html

[J04] 时间戳与日期互转
来源：http://dali.sweek.top/Article/details/gt2beciiduf.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.svipenyu.cn/Article/details/gt2liuieogy.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.xylfe.cn/Article/details/gt2hxytzvjp.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.nanxuanxn.top/Article/details/gt2ekanksor.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.guowangkeji.top/Article/details/gt2qeyqgpdf.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yangfankeji.com/Article/details/gt2gyipqaeg.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.smart0.xyz/Article/details/gt2gsbtsxew.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.pengpengdd.cyou/Article/details/gt2seqffios.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yvedp.cn/Article/details/gt2zocybsnp.html

[J05] 时间加减（加 7 天）
来源：http://dali.shangyingyoupin.top/Article/details/gt2kvbepill.html

Py:   now + timedelta(days=7)
来源：http://dali.zhixingplan.top/Article/details/gt2lswxjmur.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yongpay.top/Article/details/gt2ffgjrjea.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gaohongyu789.top/Article/details/gt2hgaorkze.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinqigufen.top/Article/details/gt2gvbssuxh.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.aibaodan.cn/Article/details/gt2iukrhbot.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.xylfe.cn/Article/details/gt2docjsagd.html

Ruby: Time.now + 7 * 86400
来源：http://dali.cqqwz.cn/Article/details/gt2lqumzdym.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jqgufenzy.top/Article/details/gt2mtppgyij.html

[J06] 计算两时间之差
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jdqikskd.html

Py:   (end - start).total_seconds()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qgkodvxc.html

PHP:  $end->diff($start)->days;
来源：http://dali.cqqwz.cn/Article/details/gt2vtfhwvjk.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.chenlongwang.top/Article/details/gt2kblizknu.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.aizwys.cn/Article/details/gt2ogktyopt.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.hfpthk.cn/Article/details/gt2hlgvojca.html

Go:   end.Sub(start).Hours()
来源：http://dali.chenlongwang.top/Article/details/gt2mdqfevob.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dikpnyal.html

C#:   (end - start).TotalSeconds
来源：http://dali.gaohongyu789.top/Article/details/gt2xwjnngls.html

[J07] 比较两个日期
来源：http://dali.wangdashe.top/Article/details/gt2ndmobltb.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.nwbrower.top/Article/details/gt2yivfvkpg.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.9152youxi.cn/Article/details/gt2dqarzxkp.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yongpay.top/Article/details/gt2ozxqzxun.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.wangdashe.top/Article/details/gt2ieqhqrym.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jyoumei.cn/Article/details/gt2jllwkfbp.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhixingplan.top/Article/details/gt2vifmrodf.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.andypj.xyz/Article/details/gt2xzycluvl.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.wangshuangyany.cn/Article/details/gt2kbtjtiwj.html

[J08] 提取年月日与星期
来源：http://dali.tanke756.top/Article/details/gt2poolzqhb.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.fzhhl.top/Article/details/gt2fcybefmw.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.9152youxi.cn/Article/details/gt2myrwbyyq.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.tianlin.xyz/Article/details/gt2ifhxuyvo.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.svipenyu.cn/Article/details/gt2czxbvdky.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.redwolf501.top/Article/details/gt2zufwhdxr.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.shuidangran.top/Article/details/gt2ywmahbqo.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.316326.xyz/Article/details/gt2mzslxnki.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.gogol.net.cn/Article/details/gt2whsiodmo.html

[J09] 时区处理
来源：http://dali.sweek.top/Article/details/gt2hbjlegzy.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.sweek.top/Article/details/gt2tflxnwsn.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jianghu66.top/Article/details/gt2gassivrd.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.feifeiyinyue.top/Article/details/gt2yznnuglc.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.feifeiyinyue.top/Article/details/gt2gwlqngak.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.daria6918.cn/Article/details/gt2ojwzcrym.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.hfpthk.cn/Article/details/gt2ffnzmdvb.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhixingplan.top/Article/details/gt2trnyhchz.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.shangyingyoupin.top/Article/details/gt2kaslivpg.html

[J10] 取今天 / 本月第一天
来源：http://dali.hywenlv.cn/Article/details/gt2unukdihr.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.ppjwa.cn/Article/details/gt2knxrlepg.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ptouhzwi.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2xuajopsw.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.pycfn.com/Article/details/gt2codhjxel.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hqlsotbx.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jqgfzy.top/Article/details/gt2fzekmjwn.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.birdmap.top/Article/details/gt2nvqwgnfx.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.dianchejie.cn/Article/details/gt2txgoqdce.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2gximtnqf.html

K. JSON 与序列化
来源：http://dali.jlsjyb.cn/Article/details/gt2vgaaqqom.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2temdfrxj.html

[K01] 对象转 JSON 字符串
来源：http://dali.nanxuanxn.top/Article/details/gt2wpjvrzik.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jinqigufen.top/Article/details/gt2byikpzbw.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yj202588.top/Article/details/gt2kulimbjj.html

JS:   JSON.stringify(obj)
来源：http://dali.fengsongda.top/Article/details/gt2pqsrapwt.html

TS:   JSON.stringify(obj)
来源：http://dali.dianchejie.cn/Article/details/gt2kfakglwu.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.sysykeji.top/Article/details/gt2ewlqllpy.html

Go:   json.Marshal(obj)
来源：http://dali.snrcjt.cn/Article/details/gt2xwbvzpfm.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ievvbyjj.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.sysykeji.top/Article/details/gt2rshflvwp.html

[K02] JSON 字符串转对象
来源：http://dali.hammf.cn/Article/details/gt2osbyicnx.html

Py:   json.loads(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2eyrpujpl.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yuxming.cn/Article/details/gt2ktwasfxb.html

JS:   JSON.parse(s)
来源：http://dali.tianlin.xyz/Article/details/gt2fxvfyqfp.html

TS:   JSON.parse(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qewttapk.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.snrcjt.cn/Article/details/gt2lcvvjwpf.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.quarkkingdee.top/Article/details/gt2ghqqisbi.html

Ruby: JSON.parse(s)
来源：http://dali.chenzaomai.com/Article/details/gt2ygsddhhv.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fmiypulo.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.c1oappe.top/Article/details/gt2baqartgh.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yongpay.top/Article/details/gt2kpvhylvz.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.xziqi.cn/Article/details/gt2nersmabh.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.hysaishi.cn/Article/details/gt2brnavizi.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.aibaodan.cn/Article/details/gt2spstbhoe.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.c1oappe.top/Article/details/gt2wfncskre.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wwgwwfeg.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.hfpthk.cn/Article/details/gt2msblwbma.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yuanzhike.top/Article/details/gt2ukdjbccu.html

[K04] 读取 JSON 文件
来源：http://dali.xuanzx.com/Article/details/gt2aldwypjx.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.tianlin.xyz/Article/details/gt2lbtubdlo.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.pengpengdd.cyou/Article/details/gt2ybddmlnf.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xinyue.icu/Article/details/gt2vtwjrfbg.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.feifeiyinyue.top/Article/details/gt2scagnkho.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jianghu66.top/Article/details/gt2xipwvxbl.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.hongshengwenyu.top/Article/details/gt2kakhdvso.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yj202588.top/Article/details/gt2biltorug.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.zycfv.cn/Article/details/gt2cyxuqrjg.html

[K05] 深拷贝对象
来源：http://dali.yj202588.top/Article/details/gt2geckmqrx.html

Py:   copy.deepcopy(obj)
来源：http://dali.gzhubu.top/Article/details/gt2eakyndfo.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yvedp.cn/Article/details/gt2msqjtpwv.html

JS:   structuredClone(obj)
来源：http://dali.jqgufenzy.top/Article/details/gt2oiphtvyd.html

TS:   structuredClone(obj)
来源：http://dali.nanxuanxn.top/Article/details/gt2jjrtjwgb.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.haohaochexian.top/Article/details/gt2hpngrssi.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yj202588.top/Article/details/gt2vztovkbi.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.sweek.top/Article/details/gt2jwiurfhc.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.snrcjt.cn/Article/details/gt2ixxmfely.html

[K06] 解析 URL 查询串
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wmhfczql.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.meibo888.top/Article/details/gt2iepgaghd.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.aizwys.cn/Article/details/gt2dzmnfclk.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.nanxuanxn.top/Article/details/gt2ctfoucft.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uztfbddu.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.gaohongyu789.top/Article/details/gt2tcovymcy.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.fzhhl.top/Article/details/gt2ibdbrabw.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.guannengcc.top/Article/details/gt2ecjtgjoh.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.sufxvd.cn/Article/details/gt2snhddjzf.html

[K07] 进制转换
来源：http://dali.shzxlz.cn/Article/details/gt2xhilzfgw.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.gzhubu.top/Article/details/gt2duwcvcva.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.hnxiangtu.top/Article/details/gt2pcvtgzev.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.iojbl.cn/Article/details/gt2xsxydihc.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.aizwys.cn/Article/details/gt2mwiewnqr.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.tianlin.xyz/Article/details/gt2srouwrvl.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.chenjidiqi.icu/Article/details/gt2yinwqvzs.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.smart0.xyz/Article/details/gt2kpxjyhwu.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.316326.xyz/Article/details/gt2noinnjwr.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.xziqi.cn/Article/details/gt2kpoufodm.html

Py:   pickle.dumps(obj)
来源：http://dali.shzxlz.cn/Article/details/gt2smooowei.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zycfv.cn/Article/details/gt2duphwfix.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yueranfly.top/Article/details/gt2jyboennh.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.chenlongwang.top/Article/details/gt2xtrwxjvi.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.xuanzx.com/Article/details/gt2ntgizpgt.html

Go:   encoding/gob
来源：http://dali.gotoacloud.top/Article/details/gt2yqsjmawd.html

Ruby: Marshal.dump(obj)
来源：http://dali.yj202588.top/Article/details/gt2myhenasi.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.birdmap.top/Article/details/gt2stfqvfsd.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2jaawlaxu.html

L. 网络请求
来源：http://dali.xinyue.icu/Article/details/gt2hbtlthqq.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2jgmcrszk.html

[L01] 发送 GET 请求
来源：http://dali.yueranfly.top/Article/details/gt2myxifchs.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.meibo888.top/Article/details/gt2ojwtfmqr.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.aizwys.cn/Article/details/gt2bgjqnwwi.html

JS:   await fetch(url)
来源：http://dali.birdmap.top/Article/details/gt2lbxfzomq.html

TS:   await fetch(url)
来源：http://dali.fengsongda.top/Article/details/gt2htmihtss.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.xinyue.icu/Article/details/gt2aqoujcqu.html

Go:   resp, err := http.Get(url)
来源：http://dali.jiagoushi.top/Article/details/gt2ownxkwmi.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zdqjudy.top/Article/details/gt2qmfcuxro.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zhengqikj.top/Article/details/gt2yoitalwh.html

[L02] 发送 POST JSON
来源：http://dali.havefunace.top/Article/details/gt2tmmzlaoj.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jinqigufen.top/Article/details/gt2hifqejzg.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.gzhubu.top/Article/details/gt2obcykcwo.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shuidangran.top/Article/details/gt2jznlimtf.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.pengpengdd.cyou/Article/details/gt2ylypffeg.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.ivvv.top/Article/details/gt2ffkoxxfm.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.sysykeji.top/Article/details/gt2lflffxfh.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.yuxming.cn/Article/details/gt2tbmubiwn.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yanxiufei.cn/Article/details/gt2rjqbganr.html

[L03] 设置自定义请求头
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wxzdjvja.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.cdnleiting.top/Article/details/gt2jhreyepp.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhiwuduotai.top/Article/details/gt2okhjwrxj.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yongpay.top/Article/details/gt2nicstmmc.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yangfankeji.com/Article/details/gt2brksfooq.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.sufxvd.cn/Article/details/gt2gveoyhvb.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gsckynku.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.ybcxt.top/Article/details/gt2csrxvnqv.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.cdnleiting.top/Article/details/gt2syimgvml.html

[L04] 设置超时
来源：http://dali.guannengcc.top/Article/details/gt2bkeghdet.html

Py:   requests.get(url, timeout=5)
来源：http://dali.shangyingyoupin.top/Article/details/gt2xzumjezg.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.chenlongwang.top/Article/details/gt2esdryyvu.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zdqjudy.top/Article/details/gt2imkjbfnu.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ivvv.top/Article/details/gt2uirppaop.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.meibo888.top/Article/details/gt2wwlqkhcl.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.cucudq.cn/Article/details/gt2dwruufwo.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.feifeiyinyue.top/Article/details/gt2pjfbajwo.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.mhx1999.top/Article/details/gt2tjtdxgot.html

[L05] 上传文件（multipart）
来源：http://dali.redwolf501.top/Article/details/gt2vesklegr.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.vqdsnc.cn/Article/details/gt2qcqohqet.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.cucudq.cn/Article/details/gt2vnfyyrqv.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yuxming.cn/Article/details/gt2xxdygthx.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.mhx1999.top/Article/details/gt2kuxzaluv.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.chenlongwang.top/Article/details/gt2ktggxrkr.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yj202588.top/Article/details/gt2yljfdtml.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhixingplan.top/Article/details/gt2xmkgphlm.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yj202588.top/Article/details/gt2zcokgbgv.html

[L06] 解析响应为 JSON
来源：http://dali.havefunace.top/Article/details/gt2slczzphw.html

Py:   resp.json()
来源：http://dali.ivvv.top/Article/details/gt2byoifdbm.html

PHP:  json_decode($body, true);
来源：http://dali.c1oappe.top/Article/details/gt2rgsquzfe.html

JS:   await resp.json()
来源：http://dali.gzhubu.top/Article/details/gt2hqcomuef.html

TS:   await resp.json()
来源：http://dali.jinqigfzy.top/Article/details/gt2tdmbygph.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.hnxiangtu.top/Article/details/gt2twdeyvqw.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.cdnleiting.top/Article/details/gt2idxilwuv.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jyoumei.cn/Article/details/gt2mcpezxlo.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jyoumei.cn/Article/details/gt2zwqbxgny.html

[L07] 处理 HTTP 状态码
来源：http://dali.yj20258888.top/Article/details/gt2ugoumvbm.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.ydzc1.top/Article/details/gt2vdnnedba.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.sufxvd.cn/Article/details/gt2ozlmfllb.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2pxqdoyrz.html

TS:   resp.ok;  resp.status
来源：http://dali.hfpthk.cn/Article/details/gt2kcdrtddw.html

Java: resp.statusCode()
来源：http://dali.fzhhl.top/Article/details/gt2kqxthupm.html

Go:   resp.StatusCode
来源：http://dali.sysykeji.top/Article/details/gt2bstxlmtl.html

Ruby: resp.code.to_i
来源：http://dali.yj202588.top/Article/details/gt2kamxhxcr.html

C#:   (int)resp.StatusCode
来源：http://dali.daria6918.cn/Article/details/gt2olxhmrne.html

[L08] 并发请求多个地址
来源：http://dali.xuanzx.com/Article/details/gt2agkmoehv.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.gotoacloud.top/Article/details/gt2abcvreez.html

PHP:  curl_multi_init() 系列
来源：http://dali.hfpthk.cn/Article/details/gt2tvfxaehy.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hnqzz.top/Article/details/gt2xlorgdwc.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xuetiantiany.cn/Article/details/gt2spxbzvqd.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yuanzhike.top/Article/details/gt2ajbjtedp.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.hysaishi.cn/Article/details/gt2zavfwuij.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yangfankeji.com/Article/details/gt2ggootkxz.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.xuanzx.com/Article/details/gt2jmdbjuui.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2uicnronl.html

M. 命令行 / 进程 / 环境
来源：http://dali.guannengcc.top/Article/details/gt2bffghhgm.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2usjdxysv.html

[M01] 读取命令行参数
来源：http://dali.pengpengdd.cyou/Article/details/gt2azsyshvb.html

Py:   sys.argv[1:]
来源：http://dali.xuetiantiany.cn/Article/details/gt2oindbntr.html

PHP:  $argv;  $argc;
来源：http://dali.yangfankeji.com/Article/details/gt2raudjmza.html

JS:   process.argv.slice(2)
来源：http://dali.gotoacloud.top/Article/details/gt2sauqwmmq.html

TS:   process.argv.slice(2)
来源：http://dali.yj202588.top/Article/details/gt2ziuixvsg.html

Java: args 数组（main 方法参数）
来源：http://dali.tian-w.cn/Article/details/gt2ebsbddfy.html

Go:   os.Args[1:]
来源：http://dali.aibaodan.cn/Article/details/gt2olxlfgvo.html

Ruby: ARGV
来源：http://dali.smart0.xyz/Article/details/gt2wtpygblt.html

C#:   args 数组（Main 方法参数）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2awhmcdvh.html

[M02] 读取环境变量
来源：http://dali.dianchejie.cn/Article/details/gt2gkhvhzkm.html

Py:   os.environ.get("HOME")
来源：http://dali.pengpengdd.cyou/Article/details/gt2vecbkqsa.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.xuanzx.com/Article/details/gt2vnahsnbq.html

JS:   process.env.HOME
来源：http://dali.hnqzz.top/Article/details/gt2ghnekcxo.html

TS:   process.env.HOME
来源：http://dali.daria6918.cn/Article/details/gt2jdsvabkk.html

Java: System.getenv("HOME")
来源：http://dali.gotoacloud.top/Article/details/gt2ykgqtjke.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.tanke756.top/Article/details/gt2kppilpfl.html

Ruby: ENV["HOME"]
来源：http://dali.mhx1999.top/Article/details/gt2cgjzuube.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yuxming.cn/Article/details/gt2svfmpbpp.html

[M03] 执行外部命令
来源：http://dali.xylfe.cn/Article/details/gt2uvzmtwvr.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jqgfzy.top/Article/details/gt2mdpbjuoq.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hnqzz.top/Article/details/gt2ywwoeatv.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.cdnleiting.top/Article/details/gt2ejcgqtdv.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.wangshuangyany.cn/Article/details/gt2sfteuvrf.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.bjfxy.top/Article/details/gt2vjaegoha.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.hongshengwenyu.top/Article/details/gt2egtbmfmd.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jiagoushi.top/Article/details/gt2agkafiml.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jqgfzy.top/Article/details/gt2aqtqmbuc.html

[M04] 获取当前工作目录
来源：http://dali.zhengqikj.top/Article/details/gt2ttkaswel.html

Py:   os.getcwd()
来源：http://dali.cheryme.top/Article/details/gt2byhhvnlz.html

PHP:  getcwd();
来源：http://dali.jinqigufen.top/Article/details/gt2tlnlscpx.html

JS:   process.cwd()
来源：http://dali.hywenlv.cn/Article/details/gt2cujgsxrd.html

TS:   process.cwd()
来源：http://dali.zdqjudy.top/Article/details/gt2ltgikydo.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.gotoacloud.top/Article/details/gt2nddhgepa.html

Go:   os.Getwd()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mgjbfblo.html

Ruby: Dir.pwd
来源：http://dali.yuxming.cn/Article/details/gt2gnqwmbvs.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.ehwqpu.com/Article/details/gt2pqcfxxys.html

[M05] 设置退出码
来源：http://dali.nwbrower.top/Article/details/gt2jpogeyyx.html

Py:   sys.exit(1)
来源：http://dali.jiagoushi.top/Article/details/gt2awjhlkwh.html

PHP:  exit(1);
来源：http://dali.guannengcc.top/Article/details/gt2sopcbzjv.html


<!-- 参考信息 -->