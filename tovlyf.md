代发 wailian999

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.sweek.top/Article/details/gt2efjopeqy.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.kuanghao11.cn/Article/details/gt2whtmvqdu.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.daxiang520.top/Article/details/gt2krvdzhat.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yuxming.cn/Article/details/gt2gytgdoxj.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.gzhubu.top/Article/details/gt2scghufuu.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yueranfly.top/Article/details/gt2jlqdljoy.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.cucudq.cn/Article/details/gt2prwqzyqm.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2nddjdrsa.html

J. 日期与时间
来源：http://dali.havefunace.top/Article/details/gt2fkvzejis.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2vbxxbzah.html

[J01] 获取当前时间
来源：http://dali.0kj1m.cn/Article/details/gt2glrvtoau.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.daria6918.cn/Article/details/gt2kxmwpdcf.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.andypj.xyz/Article/details/gt2anciqzco.html

JS:   new Date();  Date.now()
来源：http://dali.shangyingyoupin.top/Article/details/gt2rzfcmyls.html

TS:   new Date();  Date.now()
来源：http://dali.iojbl.cn/Article/details/gt2etldwcon.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.316326.xyz/Article/details/gt2jyzvlxsn.html

Go:   time.Now()
来源：http://dali.jianghu66.top/Article/details/gt2rnsfzgfn.html

Ruby: Time.now
来源：http://dali.fzhhl.top/Article/details/gt2ttducehh.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.svipenyu.cn/Article/details/gt2lwgazpto.html

[J02] 格式化输出
来源：http://dali.316326.xyz/Article/details/gt2ijazulos.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.tian-w.cn/Article/details/gt2jylgvwfg.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.nanxuanxn.top/Article/details/gt2kppaurpc.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.wangshuangyany.cn/Article/details/gt2axbkwgmv.html

TS:   d.toISOString()
来源：http://dali.yj202588.top/Article/details/gt2hryryxgg.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.pycfn.com/Article/details/gt2rngorzcs.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hqnupxcy.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yj20258.top/Article/details/gt2mgqghhhq.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.nanxinkj.top/Article/details/gt2dcawjibk.html

[J03] 字符串解析为日期
来源：http://dali.pengpengdd.cyou/Article/details/gt2zvausufc.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.xinyue.icu/Article/details/gt2dwgpsbhv.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.chenlongwang.top/Article/details/gt2dlhlxfce.html

JS:   new Date("2024-01-02")
来源：http://dali.jianghu66.top/Article/details/gt2aavyogzt.html

TS:   new Date("2024-01-02")
来源：http://dali.snrcjt.cn/Article/details/gt2cdvbswvq.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.quarkkingdee.top/Article/details/gt2sdmcqvfw.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.haohaochexian.top/Article/details/gt2wsbqsweg.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.gogol.net.cn/Article/details/gt2hkwlfuoe.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kwrjuxye.html

[J04] 时间戳与日期互转
来源：http://dali.quarkkingdee.top/Article/details/gt2houpwjum.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jqgufenzy.top/Article/details/gt2vhxhobkg.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.0kj1m.cn/Article/details/gt2bmrqttcd.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.tianlin.xyz/Article/details/gt2vxoarrsi.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.svipenyu.cn/Article/details/gt2sgioravs.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.gaohongyu789.top/Article/details/gt2fdznlqtx.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.sxryk.cn/Article/details/gt2ekjbiwkc.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.ydzc1.top/Article/details/gt2thwuijnh.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.sufxvd.cn/Article/details/gt2ugxdkpfu.html

[J05] 时间加减（加 7 天）
来源：http://dali.chenzaomai.com/Article/details/gt2dozgvvrs.html

Py:   now + timedelta(days=7)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2slkjgquq.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zycfv.cn/Article/details/gt2pvrdecne.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.0kj1m.cn/Article/details/gt2oohsfseo.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jqgufenzy.top/Article/details/gt2sspevqoo.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zhoulong.xyz/Article/details/gt2fzjjfryz.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.bjfxy.top/Article/details/gt2faqehhsf.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhengqikj.top/Article/details/gt2oxbghjxd.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2okgyfpdv.html

[J06] 计算两时间之差
来源：http://dali.snrcjt.cn/Article/details/gt2ptqboebj.html

Py:   (end - start).total_seconds()
来源：http://dali.yj20258888.top/Article/details/gt2vbaykuge.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhoulong.xyz/Article/details/gt2tcrzevaj.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.pycfn.com/Article/details/gt2naypbrrq.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.bjfxy.top/Article/details/gt2dntlfrsx.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhengqikj.top/Article/details/gt2mlvdknfe.html

Go:   end.Sub(start).Hours()
来源：http://dali.xuetiantiany.cn/Article/details/gt2tvncgaxz.html

Ruby: end - start                 # 返回秒数
来源：http://dali.hnxiangtu.top/Article/details/gt2ddandoks.html

C#:   (end - start).TotalSeconds
来源：http://dali.haohaochexian.top/Article/details/gt2yjpbmcdf.html

[J07] 比较两个日期
来源：http://dali.daria6918.cn/Article/details/gt2vdevxzoq.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zhixingplan.top/Article/details/gt2sttcousi.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fybuldtp.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.shzxlz.cn/Article/details/gt2cokjbwir.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhijiandao.cn/Article/details/gt2jqozefsj.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.mhx1999.top/Article/details/gt2lwxggajx.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.redwolf501.top/Article/details/gt2irzgtpqn.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.bjfxy.top/Article/details/gt2eyvwkpid.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.chenlongwang.top/Article/details/gt2rvqrqauz.html

[J08] 提取年月日与星期
来源：http://dali.wangdashe.top/Article/details/gt2xdvfirmu.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.bjfxy.top/Article/details/gt2mehzwtus.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jinqigfzy.top/Article/details/gt2qcdhwrew.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.haohaochexian.top/Article/details/gt2asuqgucu.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.gzhubu.top/Article/details/gt2bywuyuwk.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.sufxvd.cn/Article/details/gt2vupinqdg.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.shuidangran.top/Article/details/gt2aausypkr.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.bjfxy.top/Article/details/gt2gkdsqvcj.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.cucudq.cn/Article/details/gt2wlxactzr.html

[J09] 时区处理
来源：http://dali.xziqi.cn/Article/details/gt2pfduvwsv.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.dianchejie.cn/Article/details/gt2ypayeuel.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.9152youxi.cn/Article/details/gt2ndaidddi.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhixingplan.top/Article/details/gt2tgorekqs.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jqgfzy.top/Article/details/gt2ajdghmhy.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.xinyue.icu/Article/details/gt2kzolxzmu.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.xinyue.icu/Article/details/gt2vzencirl.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2smxerrmg.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.316326.xyz/Article/details/gt2nzthaiwy.html

[J10] 取今天 / 本月第一天
来源：http://dali.sysykeji.top/Article/details/gt2jgbztgno.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yueranfly.top/Article/details/gt2ldvrcnim.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ahybuldw.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.nanxuanxn.top/Article/details/gt2skvdygpv.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jinqigufen.top/Article/details/gt2ohmvnyic.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.chenlongwang.top/Article/details/gt2kflrcfgd.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.snrcjt.cn/Article/details/gt2lcvzpahh.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jianghu66.top/Article/details/gt2hjdahnhn.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.aibaodan.cn/Article/details/gt2iwxquhkj.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2kvzivwom.html

K. JSON 与序列化
来源：http://dali.jqgufenzy.top/Article/details/gt2qgozphnz.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2gsloirbv.html

[K01] 对象转 JSON 字符串
来源：http://dali.snrcjt.cn/Article/details/gt2hmhapsbj.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.dianchejie.cn/Article/details/gt2lqktvwgn.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhixingplan.top/Article/details/gt2pcnyprmf.html

JS:   JSON.stringify(obj)
来源：http://dali.guannengcc.top/Article/details/gt2sflbeeqf.html

TS:   JSON.stringify(obj)
来源：http://dali.zhengqikj.top/Article/details/gt2hugbrqns.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.pycfn.com/Article/details/gt2dzdffyxk.html

Go:   json.Marshal(obj)
来源：http://dali.havefunace.top/Article/details/gt2aydicsmw.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.chenzaomai.com/Article/details/gt2ketkvddi.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.hnqzz.top/Article/details/gt2zjlmhprl.html

[K02] JSON 字符串转对象
来源：http://dali.meibo888.top/Article/details/gt2dwejjhnb.html

Py:   json.loads(s)
来源：http://dali.iojbl.cn/Article/details/gt2hljnqxvo.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.ivvv.top/Article/details/gt2ybwljdrj.html

JS:   JSON.parse(s)
来源：http://dali.dashuyun.cn/Article/details/gt2nymqqcwr.html

TS:   JSON.parse(s)
来源：http://dali.jqgfzy.top/Article/details/gt2qygmbxvr.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.dianchejie.cn/Article/details/gt2cbnkkqnq.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.hywenlv.cn/Article/details/gt2wocnueqb.html

Ruby: JSON.parse(s)
来源：http://dali.yanxiufei.cn/Article/details/gt2fszqnknd.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.mhx1999.top/Article/details/gt2rabduvng.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yj202588.top/Article/details/gt2duirufct.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.dianchejie.cn/Article/details/gt2zrqukrpb.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.wangdashe.top/Article/details/gt2tznzrovb.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.smart0.xyz/Article/details/gt2gkabltdm.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.shzxlz.cn/Article/details/gt2jgdgznrh.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.birdmap.top/Article/details/gt2tecgddeg.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.kuanghao11.cn/Article/details/gt2zkozwjgt.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2emfoihyr.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zdqjudy.top/Article/details/gt2qzowujvi.html

[K04] 读取 JSON 文件
来源：http://dali.yvedp.cn/Article/details/gt2ompebxue.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.hfpthk.cn/Article/details/gt2mhxrnluv.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.redwolf501.top/Article/details/gt2qanwpilm.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zycfv.cn/Article/details/gt2bnudwhjh.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.guowangkeji.top/Article/details/gt2naiblkmc.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.xuanzx.com/Article/details/gt2gtovyqjp.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.cqqwz.cn/Article/details/gt2cnezuqeo.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.cashguo.top/Article/details/gt2lcthtbiz.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yongpay.top/Article/details/gt2uurrdcmg.html

[K05] 深拷贝对象
来源：http://dali.yvedp.cn/Article/details/gt2kqxxunsb.html

Py:   copy.deepcopy(obj)
来源：http://dali.gogol.net.cn/Article/details/gt2oamtoexc.html

PHP:  unserialize(serialize($obj));
来源：http://dali.gzhubu.top/Article/details/gt2ievywghr.html

JS:   structuredClone(obj)
来源：http://dali.zdqjudy.top/Article/details/gt2jwtxpdaa.html

TS:   structuredClone(obj)
来源：http://dali.yonumen.top/Article/details/gt2fdxcywxs.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.andypj.xyz/Article/details/gt2ipmlpdbx.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.yangfankeji.com/Article/details/gt2nyyvfycq.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jinqigfzy.top/Article/details/gt2dpxcdiuc.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.feifeiyinyue.top/Article/details/gt2waxptmju.html

[K06] 解析 URL 查询串
来源：http://dali.wangshuangyany.cn/Article/details/gt2oyegcxmu.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.cheryme.top/Article/details/gt2zxkrtkfv.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.daria6918.cn/Article/details/gt2flrsdcdy.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.chenjidiqi.icu/Article/details/gt2pkvbrtxe.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.chenjidiqi.icu/Article/details/gt2fjpngdlt.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.shzxlz.cn/Article/details/gt2zhnkfpnn.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.hnqzz.top/Article/details/gt2npkvrryx.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.xuetiantiany.cn/Article/details/gt2fqwryhsu.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.gzhubu.top/Article/details/gt2dxqjhfrs.html

[K07] 进制转换
来源：http://dali.zhengqikj.top/Article/details/gt2mqccvkoz.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.cucudq.cn/Article/details/gt2rzgdxfoc.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhixingplan.top/Article/details/gt2xijxjtlf.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zycfv.cn/Article/details/gt2cbiczyry.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.pycfn.com/Article/details/gt2yhpfmucn.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vgjyzqay.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.hnqzz.top/Article/details/gt2eirfdcxe.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2aysguvur.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.jqgfzy.top/Article/details/gt2kidrengy.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.gotoacloud.top/Article/details/gt2rzaseirx.html

Py:   pickle.dumps(obj)
来源：http://dali.nwbrower.top/Article/details/gt2yidlcrwt.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.yj20258.top/Article/details/gt2vubzldco.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhengqikj.top/Article/details/gt2vjrzbtoz.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jiagoushi.top/Article/details/gt2bpylgdvl.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhixingplan.top/Article/details/gt2mvaizpkd.html

Go:   encoding/gob
来源：http://dali.hongshengwenyu.top/Article/details/gt2iuqjkdjs.html

Ruby: Marshal.dump(obj)
来源：http://dali.hammf.cn/Article/details/gt2wvgswygb.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.dashuyun.cn/Article/details/gt2rbvkxsce.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pqmgddkt.html

L. 网络请求
来源：http://dali.zhixingplan.top/Article/details/gt2unbcpjvk.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2cnkbgldn.html

[L01] 发送 GET 请求
来源：http://dali.9152youxi.cn/Article/details/gt2pbnkvyvj.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.mhx1999.top/Article/details/gt2nmijpefc.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yj20258888.top/Article/details/gt2luyackpe.html

JS:   await fetch(url)
来源：http://dali.fzhhl.top/Article/details/gt2jmctojcv.html

TS:   await fetch(url)
来源：http://dali.hfpthk.cn/Article/details/gt2mchvtnyb.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jcdngtbl.html

Go:   resp, err := http.Get(url)
来源：http://dali.fengsongda.top/Article/details/gt2nigmdtpx.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jianghu66.top/Article/details/gt2ozezdnxq.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.jyoumei.cn/Article/details/gt2pbuawmvf.html

[L02] 发送 POST JSON
来源：http://dali.jinqigufen.top/Article/details/gt2xrrptwjl.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.gzhubu.top/Article/details/gt2ypqiajct.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.daxiang520.top/Article/details/gt2cwievcut.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xuetiantiany.cn/Article/details/gt2skhlgaaa.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ehwqpu.com/Article/details/gt2ecntprxf.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.nanxuanxn.top/Article/details/gt2nmkmmpag.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.316326.xyz/Article/details/gt2ehxxxuio.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.cucudq.cn/Article/details/gt2fvciapdi.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.xziqi.cn/Article/details/gt2ticncect.html

[L03] 设置自定义请求头
来源：http://dali.cdnleiting.top/Article/details/gt2umvukrju.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yonumen.top/Article/details/gt2vsgasgui.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yuxming.cn/Article/details/gt2foeuirzm.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.meibo888.top/Article/details/gt2ltzchbzw.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gzhubu.top/Article/details/gt2kgkhanzg.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.ydzc1.top/Article/details/gt2gtyrkcqe.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.mhx1999.top/Article/details/gt2stlqtdix.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.quarkkingdee.top/Article/details/gt2ufcndxdl.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.hysaishi.cn/Article/details/gt2zbjnlzgs.html

[L04] 设置超时
来源：http://dali.zhiwuduotai.top/Article/details/gt2vhccslql.html

Py:   requests.get(url, timeout=5)
来源：http://dali.hongshengwenyu.top/Article/details/gt2bqilguid.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.tianlin.xyz/Article/details/gt2qofgwelf.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yangfankeji.com/Article/details/gt2kvukfpyg.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.aibaodan.cn/Article/details/gt2rdyvznqd.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.sysykeji.top/Article/details/gt2gcteqnzl.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.hysaishi.cn/Article/details/gt2pmhajsdj.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.c1oappe.top/Article/details/gt2hxoikqei.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.sysykeji.top/Article/details/gt2fcspyvlh.html

[L05] 上传文件（multipart）
来源：http://dali.mhx1999.top/Article/details/gt2loiadysd.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.gaohongyu789.top/Article/details/gt2zxcsynvn.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.hammf.cn/Article/details/gt2nocxeubk.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jqgfzy.top/Article/details/gt2jatakeln.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.c1oappe.top/Article/details/gt2mrmwmrsu.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.cdnleiting.top/Article/details/gt2sknzjtmn.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kpcnziyz.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.gotoacloud.top/Article/details/gt2amuhjdwz.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.hfpthk.cn/Article/details/gt2bgemecnx.html

[L06] 解析响应为 JSON
来源：http://dali.9152youxi.cn/Article/details/gt2cjdmydqc.html

Py:   resp.json()
来源：http://dali.haohaochexian.top/Article/details/gt2riqnfayp.html

PHP:  json_decode($body, true);
来源：http://dali.zhiwuduotai.top/Article/details/gt2gvihaqku.html

JS:   await resp.json()
来源：http://dali.sxryk.cn/Article/details/gt2lzioqkhs.html

TS:   await resp.json()
来源：http://dali.pycfn.com/Article/details/gt2ymkntpuv.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jqgfzy.top/Article/details/gt2crpwnzvx.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jyoumei.cn/Article/details/gt2phzzrkap.html

Ruby: JSON.parse(resp.body)
来源：http://dali.gotoacloud.top/Article/details/gt2gnnpszzr.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.ivvv.top/Article/details/gt2uwzkiauw.html

[L07] 处理 HTTP 状态码
来源：http://dali.xuanzx.com/Article/details/gt2wnlesule.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.ehwqpu.com/Article/details/gt2qalbxlmz.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.ivvv.top/Article/details/gt2khqokmxo.html

JS:   resp.ok;  resp.status
来源：http://dali.yongpay.top/Article/details/gt2qedgjcfx.html

TS:   resp.ok;  resp.status
来源：http://dali.redwolf501.top/Article/details/gt2lmvoxujo.html

Java: resp.statusCode()
来源：http://dali.daria6918.cn/Article/details/gt2jxnswyjg.html

Go:   resp.StatusCode
来源：http://dali.dashuyun.cn/Article/details/gt2mqqvbxvh.html

Ruby: resp.code.to_i
来源：http://dali.ppjwa.cn/Article/details/gt2jtewccwv.html

C#:   (int)resp.StatusCode
来源：http://dali.tanke756.top/Article/details/gt2rmcymogi.html

[L08] 并发请求多个地址
来源：http://dali.cdnleiting.top/Article/details/gt2odmcjpkb.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.tianlin.xyz/Article/details/gt2woyyacgo.html

PHP:  curl_multi_init() 系列
来源：http://dali.guowangkeji.top/Article/details/gt2zlzrbdee.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xylfe.cn/Article/details/gt2dgxmprlu.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.vqdsnc.cn/Article/details/gt2hnzosplh.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.aibaodan.cn/Article/details/gt2kxziyfyt.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.0kj1m.cn/Article/details/gt2mcwfwmpw.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.hongshengwenyu.top/Article/details/gt2joucrxtd.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.nanxuanxn.top/Article/details/gt2fvjnhnxf.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fiykerqv.html

M. 命令行 / 进程 / 环境
来源：http://dali.wangshuangyany.cn/Article/details/gt2gyfeghfz.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2rtutkyhq.html

[M01] 读取命令行参数
来源：http://dali.gogol.net.cn/Article/details/gt2vqfmwang.html

Py:   sys.argv[1:]
来源：http://dali.haohaochexian.top/Article/details/gt2lqakuacg.html

PHP:  $argv;  $argc;
来源：http://dali.xuanzx.com/Article/details/gt2avcgjfgf.html

JS:   process.argv.slice(2)
来源：http://dali.jiagoushi.top/Article/details/gt2ylccjgfl.html

TS:   process.argv.slice(2)
来源：http://dali.jiagoushi.top/Article/details/gt2rxyrqset.html

Java: args 数组（main 方法参数）
来源：http://dali.ppjwa.cn/Article/details/gt2jcbaskjn.html

Go:   os.Args[1:]
来源：http://dali.daxiang520.top/Article/details/gt2ptjonvjx.html

Ruby: ARGV
来源：http://dali.jqgufenzy.top/Article/details/gt2cyshxhba.html

C#:   args 数组（Main 方法参数）
来源：http://dali.chenlongwang.top/Article/details/gt2fwzwgrby.html

[M02] 读取环境变量
来源：http://dali.gogol.net.cn/Article/details/gt2bcyckxev.html

Py:   os.environ.get("HOME")
来源：http://dali.ydzc1.top/Article/details/gt2toajqrsp.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.wangdashe.top/Article/details/gt2pzswfpwq.html

JS:   process.env.HOME
来源：http://dali.chenjidiqi.icu/Article/details/gt2lyqzvcnb.html

TS:   process.env.HOME
来源：http://dali.sxryk.cn/Article/details/gt2vvbgavjq.html

Java: System.getenv("HOME")
来源：http://dali.guowangkeji.top/Article/details/gt2pwtqxyvn.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhixingplan.top/Article/details/gt2lxnzjbgw.html

Ruby: ENV["HOME"]
来源：http://dali.sweek.top/Article/details/gt2buirwnxe.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jqgufenzy.top/Article/details/gt2cpkmjxcw.html

[M03] 执行外部命令
来源：http://dali.yj202588.top/Article/details/gt2dedifzyk.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.chenjidiqi.icu/Article/details/gt2jstqilvn.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhixingplan.top/Article/details/gt2laifyube.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.ehwqpu.com/Article/details/gt2vwksvyrd.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fmphamaq.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.aibaodan.cn/Article/details/gt2kzaujkfh.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.tian-w.cn/Article/details/gt2vvuijonf.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.dashuyun.cn/Article/details/gt2aeqrcmwx.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yanxiufei.cn/Article/details/gt2tdccrcyf.html

[M04] 获取当前工作目录
来源：http://dali.sxryk.cn/Article/details/gt2krodwdjq.html

Py:   os.getcwd()
来源：http://dali.bjfxy.top/Article/details/gt2vcaceyrg.html

PHP:  getcwd();
来源：http://dali.yuxming.cn/Article/details/gt2kyttfpdg.html

JS:   process.cwd()
来源：http://dali.sweek.top/Article/details/gt2rlbhdhys.html

TS:   process.cwd()
来源：http://dali.yuanzhike.top/Article/details/gt2tukqliwk.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.sweek.top/Article/details/gt2shklppml.html

Go:   os.Getwd()
来源：http://dali.yj202588.top/Article/details/gt2txvnjaue.html

Ruby: Dir.pwd
来源：http://dali.pengpengdd.cyou/Article/details/gt2yqedvowj.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2abcycide.html

[M05] 设置退出码
来源：http://dali.ehwqpu.com/Article/details/gt2mnufndac.html

Py:   sys.exit(1)
来源：http://dali.yueranfly.top/Article/details/gt2kmuahimc.html

PHP:  exit(1);
来源：http://dali.shangyingyoupin.top/Article/details/gt2svsdxbkn.html

JS:   process.exit(1)
来源：http://dali.sysykeji.top/Article/details/gt2srgxjgkp.html

TS:   process.exit(1)
来源：http://dali.gotoacloud.top/Article/details/gt2vqlaauux.html

Java: System.exit(1)
来源：http://dali.sysykeji.top/Article/details/gt2ufhzrbbc.html

Go:   os.Exit(1)
来源：http://dali.yj20258888.top/Article/details/gt2pxeevpci.html

Ruby: exit 1
来源：http://dali.xziqi.cn/Article/details/gt2pihtisys.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.haohaochexian.top/Article/details/gt2mdonhjfj.html

[M06] 向标准错误输出
来源：http://dali.ehwqpu.com/Article/details/gt2jtdzyrhl.html

Py:   print("err", file=sys.stderr)
来源：http://dali.quarkkingdee.top/Article/details/gt2knhkhjut.html


<!-- 参考信息 -->