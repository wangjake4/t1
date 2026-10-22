代发 wailian999

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.guowangkeji.top/Article/details/gt2wjhgjrtb.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cucudq.cn/Article/details/gt2ehdswote.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.tanke756.top/Article/details/gt2cwjtgsqu.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.xuanzx.com/Article/details/gt2twsqdwxh.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.tanke756.top/Article/details/gt2jatdefrp.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.nanxinkj.top/Article/details/gt2fdijeeqz.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jinqigufen.top/Article/details/gt2nqtemhmh.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2unkuvhnq.html

J. 日期与时间
来源：http://dali.smart0.xyz/Article/details/gt2ubyyqfxm.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2oymnqade.html

[J01] 获取当前时间
来源：http://dali.yongpay.top/Article/details/gt2efjnfixx.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.pengpengdd.cyou/Article/details/gt2zimfnbfw.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.sweek.top/Article/details/gt2armujbco.html

JS:   new Date();  Date.now()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nztafkae.html

TS:   new Date();  Date.now()
来源：http://dali.316326.xyz/Article/details/gt2uovfeiwg.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.ydzc1.top/Article/details/gt2tusyxpzj.html

Go:   time.Now()
来源：http://dali.fengsongda.top/Article/details/gt2estyqbdf.html

Ruby: Time.now
来源：http://dali.aizwys.cn/Article/details/gt2ljjthszl.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.xuanzx.com/Article/details/gt2fnstmyyf.html

[J02] 格式化输出
来源：http://dali.gotoacloud.top/Article/details/gt2uyapquqj.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gzhubu.top/Article/details/gt2lwhjgibt.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.ydzc1.top/Article/details/gt2ofdxzset.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.xylfe.cn/Article/details/gt2szasufjz.html

TS:   d.toISOString()
来源：http://dali.svipenyu.cn/Article/details/gt2nfxrsmnb.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.xuetiantiany.cn/Article/details/gt2bmekutln.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.chenjidiqi.icu/Article/details/gt2eqvzbnku.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.dianchejie.cn/Article/details/gt2ozdnxykq.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.aizwys.cn/Article/details/gt2iooxqmic.html

[J03] 字符串解析为日期
来源：http://dali.zhiwuduotai.top/Article/details/gt2ongykqae.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.hammf.cn/Article/details/gt2ulivimrs.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.tanke756.top/Article/details/gt2lniovsji.html

JS:   new Date("2024-01-02")
来源：http://dali.0kj1m.cn/Article/details/gt2dnytbtqq.html

TS:   new Date("2024-01-02")
来源：http://dali.9152youxi.cn/Article/details/gt2slrimtau.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.birdmap.top/Article/details/gt2mdyxtydz.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.sweek.top/Article/details/gt2oeuwucqr.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.hongshengwenyu.top/Article/details/gt2xetnskru.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.hongshengwenyu.top/Article/details/gt2hhcqgsxq.html

[J04] 时间戳与日期互转
来源：http://dali.aizwys.cn/Article/details/gt2aotcvvut.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.hnxiangtu.top/Article/details/gt2bvirglea.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zdqjudy.top/Article/details/gt2spykldwh.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.cdnleiting.top/Article/details/gt2ztovdgsc.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.kuanghao11.cn/Article/details/gt2eyggykbi.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.svipenyu.cn/Article/details/gt2jazfpudh.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.gaohongyu789.top/Article/details/gt2vgerwfyg.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.fzhhl.top/Article/details/gt2hkfdkpqd.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kbyyxruz.html

[J05] 时间加减（加 7 天）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tnfmcsal.html

Py:   now + timedelta(days=7)
来源：http://dali.cheryme.top/Article/details/gt2abbcqusk.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jyoumei.cn/Article/details/gt2napacwrz.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yongpay.top/Article/details/gt2osoksmdq.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.redwolf501.top/Article/details/gt2zfcxwlnn.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2memboiso.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.smart0.xyz/Article/details/gt2ckkgwkbg.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hongshengwenyu.top/Article/details/gt2xkrfjqhy.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.nanxuanxn.top/Article/details/gt2diudqnak.html

[J06] 计算两时间之差
来源：http://dali.cqqwz.cn/Article/details/gt2myhqsldj.html

Py:   (end - start).total_seconds()
来源：http://dali.wangdashe.top/Article/details/gt2bpbuayaj.html

PHP:  $end->diff($start)->days;
来源：http://dali.guowangkeji.top/Article/details/gt2qwchadql.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.svipenyu.cn/Article/details/gt2dgxwlxtu.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.ehwqpu.com/Article/details/gt2iwwntcls.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.tianlin.xyz/Article/details/gt2pzsshvye.html

Go:   end.Sub(start).Hours()
来源：http://dali.hysaishi.cn/Article/details/gt2xrhidtzv.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jqgufenzy.top/Article/details/gt2wdjlhvav.html

C#:   (end - start).TotalSeconds
来源：http://dali.jlsjyb.cn/Article/details/gt2aknligpr.html

[J07] 比较两个日期
来源：http://dali.jinqigfzy.top/Article/details/gt2bqurtlif.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jyoumei.cn/Article/details/gt2cvelppdq.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.fengsongda.top/Article/details/gt2aqfhxqxx.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.redwolf501.top/Article/details/gt2hmvhlctp.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.hongshengwenyu.top/Article/details/gt2cddlmqmx.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.nanxuanxn.top/Article/details/gt2spqfvfgm.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yonumen.top/Article/details/gt2gbijvlel.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yanxiufei.cn/Article/details/gt2jbdduwyj.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.chenjidiqi.icu/Article/details/gt2vvzyufac.html

[J08] 提取年月日与星期
来源：http://dali.yvedp.cn/Article/details/gt2szkgvsyu.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.cdnleiting.top/Article/details/gt2zssjkrjb.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.hnxiangtu.top/Article/details/gt2rsfmkadf.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mpypwvld.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.xinyue.icu/Article/details/gt2gipekdjz.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yraprblx.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.xuetiantiany.cn/Article/details/gt2sxxqsujz.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.chenlongwang.top/Article/details/gt2uhzolswa.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.316326.xyz/Article/details/gt2fpcxsqaw.html

[J09] 时区处理
来源：http://dali.chenjidiqi.icu/Article/details/gt2txyryili.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.tianlin.xyz/Article/details/gt2boxvvgwr.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.cdnleiting.top/Article/details/gt2dandlpkq.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jqgfzy.top/Article/details/gt2cofdgqez.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ivvv.top/Article/details/gt2qkutredh.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jyoumei.cn/Article/details/gt2qboyggaf.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.shzxlz.cn/Article/details/gt2jitgkykq.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhoulong.xyz/Article/details/gt2yguijfky.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.fzhhl.top/Article/details/gt2zqwuviji.html

[J10] 取今天 / 本月第一天
来源：http://dali.shuidangran.top/Article/details/gt2xteihusj.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.snrcjt.cn/Article/details/gt2pxuznbnw.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.gaohongyu789.top/Article/details/gt2irxsgndq.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.yonumen.top/Article/details/gt2pxrbnhlf.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.316326.xyz/Article/details/gt2eivtiyzp.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.gotoacloud.top/Article/details/gt2novzqves.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jinqigfzy.top/Article/details/gt2vhuuzbnj.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lqmjsczb.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.gzhubu.top/Article/details/gt2lotanixh.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2qqlsootc.html

K. JSON 与序列化
来源：http://dali.vqdsnc.cn/Article/details/gt2qprtwrud.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2pnkvhclg.html

[K01] 对象转 JSON 字符串
来源：http://dali.meibo888.top/Article/details/gt2oibmhfcz.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rpotpgcn.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jqgufenzy.top/Article/details/gt2imwrfxpt.html

JS:   JSON.stringify(obj)
来源：http://dali.yj202588.top/Article/details/gt2nhjubzwf.html

TS:   JSON.stringify(obj)
来源：http://dali.meibo888.top/Article/details/gt2mgirglgp.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhijiandao.cn/Article/details/gt2usdclcqp.html

Go:   json.Marshal(obj)
来源：http://dali.gogol.net.cn/Article/details/gt2emgchsbr.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.daxiang520.top/Article/details/gt2xakbovdt.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gt2kpazpotc.html

[K02] JSON 字符串转对象
来源：http://dali.xuetiantiany.cn/Article/details/gt2sbzmdmth.html

Py:   json.loads(s)
来源：http://dali.0kj1m.cn/Article/details/gt2ebaaliuk.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.fzhhl.top/Article/details/gt2aghvmfpf.html

JS:   JSON.parse(s)
来源：http://dali.chenzaomai.com/Article/details/gt2dmfjkvqf.html

TS:   JSON.parse(s)
来源：http://dali.gotoacloud.top/Article/details/gt2fffggeka.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.cashguo.top/Article/details/gt2xsjxasnt.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xvrqpzgu.html

Ruby: JSON.parse(s)
来源：http://dali.zhiwuduotai.top/Article/details/gt2dwnhdlrw.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.nanxuanxn.top/Article/details/gt2caapqltw.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhengqikj.top/Article/details/gt2dtsstcah.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.tianlin.xyz/Article/details/gt2wiszdqmn.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.chenjidiqi.icu/Article/details/gt2tuldedch.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.xinyue.icu/Article/details/gt2vmnyryvh.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.nwbrower.top/Article/details/gt2ofmvntdx.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cxnmyfrb.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mghrvfit.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gt2qemguwyx.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yongpay.top/Article/details/gt2ivnljtbm.html

[K04] 读取 JSON 文件
来源：http://dali.yangfankeji.com/Article/details/gt2jviahtya.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.feifeiyinyue.top/Article/details/gt2ffdskvuy.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.bjfxy.top/Article/details/gt2hdmwrplr.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yuanzhike.top/Article/details/gt2ayozyefk.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yj202588.top/Article/details/gt2evotemer.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.sweek.top/Article/details/gt2lpzazchz.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yongpay.top/Article/details/gt2vpdynbik.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.snrcjt.cn/Article/details/gt2xicdabtr.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jlsjyb.cn/Article/details/gt2jvmrihou.html

[K05] 深拷贝对象
来源：http://dali.gaohongyu789.top/Article/details/gt2ixezqkpa.html

Py:   copy.deepcopy(obj)
来源：http://dali.jinqigufen.top/Article/details/gt2ouhuwpug.html

PHP:  unserialize(serialize($obj));
来源：http://dali.hysaishi.cn/Article/details/gt2tdgffsvo.html

JS:   structuredClone(obj)
来源：http://dali.nanxinkj.top/Article/details/gt2bvvnynuj.html

TS:   structuredClone(obj)
来源：http://dali.sweek.top/Article/details/gt2rtblrjow.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.gotoacloud.top/Article/details/gt2cffyehck.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jqgufenzy.top/Article/details/gt2mcqfvzxn.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.aibaodan.cn/Article/details/gt2swctfyhu.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.cqqwz.cn/Article/details/gt2vhabigqh.html

[K06] 解析 URL 查询串
来源：http://dali.mhx1999.top/Article/details/gt2rdwjazlf.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.vqdsnc.cn/Article/details/gt2osezdqso.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.feifeiyinyue.top/Article/details/gt2rixskfkk.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.snrcjt.cn/Article/details/gt2vdlyioxb.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.dashuyun.cn/Article/details/gt2wtiuryme.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.ybcxt.top/Article/details/gt2hsedsgro.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhoulong.xyz/Article/details/gt2timoumsl.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.fzhhl.top/Article/details/gt2opetcvud.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jianghu66.top/Article/details/gt2xxmsdbwu.html

[K07] 进制转换
来源：http://dali.daria6918.cn/Article/details/gt2qsneayhe.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.svipenyu.cn/Article/details/gt2lsyvcxcm.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.shzxlz.cn/Article/details/gt2ohyqkbky.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2twkfarzl.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.birdmap.top/Article/details/gt2jemvarpd.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.xuetiantiany.cn/Article/details/gt2hxubswct.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zycfv.cn/Article/details/gt2tsxnmywh.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zdqjudy.top/Article/details/gt2igheihff.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.daria6918.cn/Article/details/gt2tekqrrug.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhixingplan.top/Article/details/gt2frrhojuz.html

Py:   pickle.dumps(obj)
来源：http://dali.yj20258888.top/Article/details/gt2abffsmrm.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.bjfxy.top/Article/details/gt2witenwho.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jyoumei.cn/Article/details/gt2mlwndbna.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.0kj1m.cn/Article/details/gt2mewjtcqk.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhoulong.xyz/Article/details/gt2nsjtbrba.html

Go:   encoding/gob
来源：http://dali.svipenyu.cn/Article/details/gt2vvwrgaao.html

Ruby: Marshal.dump(obj)
来源：http://dali.quarkkingdee.top/Article/details/gt2jyiptjlf.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.pengpengdd.cyou/Article/details/gt2umunkmag.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2cfyaizna.html

L. 网络请求
来源：http://dali.chenzaomai.com/Article/details/gt2zlcaspzp.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2cnvqdekt.html

[L01] 发送 GET 请求
来源：http://dali.jinqigfzy.top/Article/details/gt2xqsutcfp.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tgcbusoz.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.shuidangran.top/Article/details/gt2inaoofgi.html

JS:   await fetch(url)
来源：http://dali.shzxlz.cn/Article/details/gt2rfjcukmh.html

TS:   await fetch(url)
来源：http://dali.jyoumei.cn/Article/details/gt2ffjsspcr.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.guowangkeji.top/Article/details/gt2efysquxb.html

Go:   resp, err := http.Get(url)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2znbrimmb.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jvktfoal.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kxmygrhg.html

[L02] 发送 POST JSON
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ngyojddh.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.kuanghao11.cn/Article/details/gt2eqicecpi.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.gzhubu.top/Article/details/gt2cbpcszei.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shzxlz.cn/Article/details/gt2pxnljvtq.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.meibo888.top/Article/details/gt2sohvjwhc.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.fengsongda.top/Article/details/gt2sdsrwtoh.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.nanxinkj.top/Article/details/gt2cddomnee.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uheqbgrn.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.daxiang520.top/Article/details/gt2ddfwxicu.html

[L03] 设置自定义请求头
来源：http://dali.pengpengdd.cyou/Article/details/gt2pjwywznr.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.chenjidiqi.icu/Article/details/gt2zvnxiyhj.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.9152youxi.cn/Article/details/gt2imnlgkap.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jinqigufen.top/Article/details/gt2zjdfflfn.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.haohaochexian.top/Article/details/gt2nkdsvlzh.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bmeafoor.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yongpay.top/Article/details/gt2oxfdgcau.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.shzxlz.cn/Article/details/gt2sbxryetm.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.shuidangran.top/Article/details/gt2ovdfytpc.html

[L04] 设置超时
来源：http://dali.ppjwa.cn/Article/details/gt2krqsoxpe.html

Py:   requests.get(url, timeout=5)
来源：http://dali.ydzc1.top/Article/details/gt2cqzadqgl.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jianghu66.top/Article/details/gt2wffaqxiv.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.vqdsnc.cn/Article/details/gt2ffjcslpj.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.svipenyu.cn/Article/details/gt2axqbvjrm.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yvedp.cn/Article/details/gt2pekdnnpk.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.dashuyun.cn/Article/details/gt2zwdhihgw.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yj20258888.top/Article/details/gt2avayevja.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.c1oappe.top/Article/details/gt2lzyjevuv.html

[L05] 上传文件（multipart）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vhcohtqx.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jqgfzy.top/Article/details/gt2rpqnnvwq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.haohaochexian.top/Article/details/gt2rrehaesm.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yuxming.cn/Article/details/gt2gtyyjnnc.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhongyouzk.top/Article/details/gt2xzyuphsg.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.nwbrower.top/Article/details/gt2rsfvhblw.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.ybcxt.top/Article/details/gt2djnfczhx.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yonumen.top/Article/details/gt2ssmwlwoj.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.xinyue.icu/Article/details/gt2bllxpqst.html

[L06] 解析响应为 JSON
来源：http://dali.snrcjt.cn/Article/details/gt2jxliwgaa.html

Py:   resp.json()
来源：http://dali.daxiang520.top/Article/details/gt2llsrwuxq.html

PHP:  json_decode($body, true);
来源：http://dali.gotoacloud.top/Article/details/gt2hroawjth.html

JS:   await resp.json()
来源：http://dali.xziqi.cn/Article/details/gt2ejgfnigl.html

TS:   await resp.json()
来源：http://dali.gotoacloud.top/Article/details/gt2ledycudp.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.tianlin.xyz/Article/details/gt2jdjcaymp.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jlsjyb.cn/Article/details/gt2fffsrjoq.html

Ruby: JSON.parse(resp.body)
来源：http://dali.aibaodan.cn/Article/details/gt2yiniswzh.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yj20258.top/Article/details/gt2ubqipfch.html

[L07] 处理 HTTP 状态码
来源：http://dali.mhx1999.top/Article/details/gt2imnpgxuk.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.daxiang520.top/Article/details/gt2drzvfhfz.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.nanxinkj.top/Article/details/gt2vdzufvyk.html

JS:   resp.ok;  resp.status
来源：http://dali.pycfn.com/Article/details/gt2bapsbciv.html

TS:   resp.ok;  resp.status
来源：http://dali.jiagoushi.top/Article/details/gt2eidaakhp.html

Java: resp.statusCode()
来源：http://dali.sweek.top/Article/details/gt2fwxgceth.html

Go:   resp.StatusCode
来源：http://dali.sweek.top/Article/details/gt2kocneblc.html

Ruby: resp.code.to_i
来源：http://dali.xinyue.icu/Article/details/gt2xyimkkho.html

C#:   (int)resp.StatusCode
来源：http://dali.havefunace.top/Article/details/gt2hknkwwfq.html

[L08] 并发请求多个地址
来源：http://dali.sxryk.cn/Article/details/gt2hllufzdk.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhoulong.xyz/Article/details/gt2oqsjjdbf.html

PHP:  curl_multi_init() 系列
来源：http://dali.smart0.xyz/Article/details/gt2czbmsfbu.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nwbrower.top/Article/details/gt2uqsmtgyu.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jyoumei.cn/Article/details/gt2wojywtsh.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yangfankeji.com/Article/details/gt2vqyeiypb.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.fzhhl.top/Article/details/gt2ubmdetbo.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.cucudq.cn/Article/details/gt2ankytqse.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2asjjkqbg.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2mfbylfaw.html

M. 命令行 / 进程 / 环境
来源：http://dali.havefunace.top/Article/details/gt2tzkqxjol.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2legzgzbr.html

[M01] 读取命令行参数
来源：http://dali.fengsongda.top/Article/details/gt2bguvxjtr.html

Py:   sys.argv[1:]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mpfctrlm.html

PHP:  $argv;  $argc;
来源：http://dali.dianchejie.cn/Article/details/gt2rjjktjyy.html

JS:   process.argv.slice(2)
来源：http://dali.sysykeji.top/Article/details/gt2ylqpewph.html

TS:   process.argv.slice(2)
来源：http://dali.yanxiufei.cn/Article/details/gt2pkzyelgr.html

Java: args 数组（main 方法参数）
来源：http://dali.hammf.cn/Article/details/gt2bckofuid.html

Go:   os.Args[1:]
来源：http://dali.316326.xyz/Article/details/gt2cnjzjejg.html

Ruby: ARGV
来源：http://dali.quarkkingdee.top/Article/details/gt2dscgaiet.html

C#:   args 数组（Main 方法参数）
来源：http://dali.meibo888.top/Article/details/gt2nrniyeeo.html

[M02] 读取环境变量
来源：http://dali.xinyue.icu/Article/details/gt2qdvacyfr.html

Py:   os.environ.get("HOME")
来源：http://dali.sxryk.cn/Article/details/gt2heeskxze.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.aibaodan.cn/Article/details/gt2ymqklnim.html

JS:   process.env.HOME
来源：http://dali.vqdsnc.cn/Article/details/gt2ydmysfcf.html

TS:   process.env.HOME
来源：http://dali.0kj1m.cn/Article/details/gt2jtazoaba.html

Java: System.getenv("HOME")
来源：http://dali.ydzc1.top/Article/details/gt2xrfhaukw.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zdqjudy.top/Article/details/gt2xdqccwnv.html

Ruby: ENV["HOME"]
来源：http://dali.gaohongyu789.top/Article/details/gt2exeheiib.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yuanzhike.top/Article/details/gt2flxeexcv.html

[M03] 执行外部命令
来源：http://dali.jinqigufen.top/Article/details/gt2sejmlejm.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hammf.cn/Article/details/gt2vawwkplo.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yongpay.top/Article/details/gt2ceubzzky.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.guowangkeji.top/Article/details/gt2faespxnh.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2dtcphxbj.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.quarkkingdee.top/Article/details/gt2jcbptbvi.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.nanxuanxn.top/Article/details/gt2qzomsrty.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhengqikj.top/Article/details/gt2elrzqgss.html

C#:   Process.Start("ls", "-l");
来源：http://dali.316326.xyz/Article/details/gt2opgzbwrr.html

[M04] 获取当前工作目录
来源：http://dali.gotoacloud.top/Article/details/gt2gyeimizq.html

Py:   os.getcwd()
来源：http://dali.chenjidiqi.icu/Article/details/gt2zdvmcmau.html

PHP:  getcwd();
来源：http://dali.hfpthk.cn/Article/details/gt2kavlcaru.html

JS:   process.cwd()
来源：http://dali.bjfxy.top/Article/details/gt2mmsirome.html

TS:   process.cwd()
来源：http://dali.yuanzhike.top/Article/details/gt2pgtovxyv.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yangfankeji.com/Article/details/gt2oinwmvau.html

Go:   os.Getwd()
来源：http://dali.ivvv.top/Article/details/gt2ocvqaxxp.html

Ruby: Dir.pwd
来源：http://dali.xuanzx.com/Article/details/gt2vvjkmdxg.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.nanxuanxn.top/Article/details/gt2ukanmmfn.html

[M05] 设置退出码
来源：http://dali.tanke756.top/Article/details/gt2cznacziu.html

Py:   sys.exit(1)
来源：http://dali.redwolf501.top/Article/details/gt2bukszndh.html

PHP:  exit(1);
来源：http://dali.aibaodan.cn/Article/details/gt2icqbrdpq.html

JS:   process.exit(1)
来源：http://dali.jqgufenzy.top/Article/details/gt2hsfzmluy.html

TS:   process.exit(1)
来源：http://dali.mhx1999.top/Article/details/gt2qhiimtcu.html

Java: System.exit(1)
来源：http://dali.9152youxi.cn/Article/details/gt2jnhgzdqb.html

Go:   os.Exit(1)
来源：http://dali.sxryk.cn/Article/details/gt2axbriajo.html

Ruby: exit 1
来源：http://dali.zhixingplan.top/Article/details/gt2snluhums.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.hysaishi.cn/Article/details/gt2dljpwqzg.html

[M06] 向标准错误输出
来源：http://dali.sufxvd.cn/Article/details/gt2srmrywxm.html

Py:   print("err", file=sys.stderr)
来源：http://dali.iojbl.cn/Article/details/gt2onelygdk.html


<!-- 参考信息 -->