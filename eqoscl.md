代发 wailian999

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2abkisppd.html

[I07] 忽略大小写与多行模式
来源：http://dali.xinyue.icu/Article/details/gt2kcakkycp.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.meibo888.top/Article/details/gt2bjhlonfo.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.gaohongyu789.top/Article/details/gt2usqhgwgo.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fnjlbekm.html

TS:   /error/gim
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2budxmppc.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhongyouzk.top/Article/details/gt2sjhfnpco.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hnqzz.top/Article/details/gt2fybuqhsa.html

Ruby: s.scan(/error/i)
来源：http://dali.guowangkeji.top/Article/details/gt2uwkgmmlp.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jinqigufen.top/Article/details/gt2arglpjpx.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yonumen.top/Article/details/gt2zpfjmujb.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.xylfe.cn/Article/details/gt2nvdoxxne.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.hammf.cn/Article/details/gt2mfmnqvgg.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gotoacloud.top/Article/details/gt2lpmdpimq.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ebxfzkhp.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.pengpengdd.cyou/Article/details/gt2guezbclm.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.bjfxy.top/Article/details/gt2jkaxxnhm.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2emguflgr.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yj202588.top/Article/details/gt2hcuaafly.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2abofteyj.html

J. 日期与时间
来源：http://dali.cdnleiting.top/Article/details/gt2aulklzag.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2qrghweqk.html

[J01] 获取当前时间
来源：http://dali.pycfn.com/Article/details/gt2ttrwzmxm.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.0kj1m.cn/Article/details/gt2tdllntil.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.nwbrower.top/Article/details/gt2fwrlrwxd.html

JS:   new Date();  Date.now()
来源：http://dali.zhixingplan.top/Article/details/gt2misutvmg.html

TS:   new Date();  Date.now()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yrkyjrez.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.gaohongyu789.top/Article/details/gt2jiizwxld.html

Go:   time.Now()
来源：http://dali.tianlin.xyz/Article/details/gt2omcgppjh.html

Ruby: Time.now
来源：http://dali.xziqi.cn/Article/details/gt2hczszxdb.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.316326.xyz/Article/details/gt2rbvcvewp.html

[J02] 格式化输出
来源：http://dali.feifeiyinyue.top/Article/details/gt2grvmgczt.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sufxvd.cn/Article/details/gt2jxyjcjfx.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.hnxiangtu.top/Article/details/gt2aukiktoi.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ogzlzmau.html

TS:   d.toISOString()
来源：http://dali.gaohongyu789.top/Article/details/gt2tmifmdyu.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yanxiufei.cn/Article/details/gt2fshqweso.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.xziqi.cn/Article/details/gt2vxfbpgym.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.bjfxy.top/Article/details/gt2jaqvialn.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yuxming.cn/Article/details/gt2ygajiiit.html

[J03] 字符串解析为日期
来源：http://dali.yj20258.top/Article/details/gt2emyeygbd.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhongyouzk.top/Article/details/gt2uuwrgzky.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.ivvv.top/Article/details/gt2sibpnmms.html

JS:   new Date("2024-01-02")
来源：http://dali.pycfn.com/Article/details/gt2kcvbiksv.html

TS:   new Date("2024-01-02")
来源：http://dali.havefunace.top/Article/details/gt2fosekzmy.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zdqjudy.top/Article/details/gt2twjzolpn.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jianghu66.top/Article/details/gt2ljvtawcp.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.fzhhl.top/Article/details/gt2kxkwabcr.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.cqqwz.cn/Article/details/gt2pempyzlu.html

[J04] 时间戳与日期互转
来源：http://dali.jqgufenzy.top/Article/details/gt2ilcbgvbb.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.daria6918.cn/Article/details/gt2nblfopis.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.shzxlz.cn/Article/details/gt2uitpckjq.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.chenjidiqi.icu/Article/details/gt2igsgjaqg.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.vqdsnc.cn/Article/details/gt2ioesvuxn.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yj20258.top/Article/details/gt2ojbaguhi.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dalkrume.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.xinyue.icu/Article/details/gt2lpmvvcdi.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xlzklhcx.html

[J05] 时间加减（加 7 天）
来源：http://dali.zycfv.cn/Article/details/gt2uekqafno.html

Py:   now + timedelta(days=7)
来源：http://dali.shangyingyoupin.top/Article/details/gt2lhjdroit.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.mhx1999.top/Article/details/gt2wriyhnvt.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hfpthk.cn/Article/details/gt2vwghvlen.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.haohaochexian.top/Article/details/gt2nryazdjn.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.zdqjudy.top/Article/details/gt2oxxsyldz.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.snrcjt.cn/Article/details/gt2qajadlhj.html

Ruby: Time.now + 7 * 86400
来源：http://dali.iojbl.cn/Article/details/gt2gdxqolup.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.xuetiantiany.cn/Article/details/gt2gzvugbnn.html

[J06] 计算两时间之差
来源：http://dali.sxryk.cn/Article/details/gt2qqjkzehm.html

Py:   (end - start).total_seconds()
来源：http://dali.jinqigufen.top/Article/details/gt2jaiohser.html

PHP:  $end->diff($start)->days;
来源：http://dali.hnqzz.top/Article/details/gt2obfprymx.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.havefunace.top/Article/details/gt2emkgzwqb.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yj20258.top/Article/details/gt2vdcrvjbr.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.hammf.cn/Article/details/gt2mrxyjwep.html

Go:   end.Sub(start).Hours()
来源：http://dali.c1oappe.top/Article/details/gt2dghczfhk.html

Ruby: end - start                 # 返回秒数
来源：http://dali.nwbrower.top/Article/details/gt2bocxdndl.html

C#:   (end - start).TotalSeconds
来源：http://dali.gaohongyu789.top/Article/details/gt2vhmlgeaf.html

[J07] 比较两个日期
来源：http://dali.vqdsnc.cn/Article/details/gt2adadkjdo.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.andypj.xyz/Article/details/gt2nwxtvdzh.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yuanzhike.top/Article/details/gt2qbbppjzo.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.sweek.top/Article/details/gt2omcjkxvo.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.316326.xyz/Article/details/gt2hnvdgfdy.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.aizwys.cn/Article/details/gt2jkedwjuq.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.dashuyun.cn/Article/details/gt2gnuvroev.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.meibo888.top/Article/details/gt2utfvijzf.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.iojbl.cn/Article/details/gt2wjsxzfwo.html

[J08] 提取年月日与星期
来源：http://dali.nanxinkj.top/Article/details/gt2tsaqacsh.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.gaohongyu789.top/Article/details/gt2ipugygye.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yonumen.top/Article/details/gt2wprzskba.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.cheryme.top/Article/details/gt2pwudeowe.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.havefunace.top/Article/details/gt2tuvxopcb.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zhongyouzk.top/Article/details/gt2vfkwsckv.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.fzhhl.top/Article/details/gt2vzvugiky.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.hfpthk.cn/Article/details/gt2lgbyqnas.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.aibaodan.cn/Article/details/gt2xrnygbxq.html

[J09] 时区处理
来源：http://dali.yonumen.top/Article/details/gt2fddrwtqb.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.yangfankeji.com/Article/details/gt2xuihrgov.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zdqjudy.top/Article/details/gt2wckjyvyl.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.0kj1m.cn/Article/details/gt2royrlrvf.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2opajogci.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.shuidangran.top/Article/details/gt2yslggwff.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.ivvv.top/Article/details/gt2jpurbkws.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yangfankeji.com/Article/details/gt2rksqloku.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.aibaodan.cn/Article/details/gt2phbivejv.html

[J10] 取今天 / 本月第一天
来源：http://dali.andypj.xyz/Article/details/gt2vzovejdb.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zdqjudy.top/Article/details/gt2adtpwyom.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.sysykeji.top/Article/details/gt2jtztsbbx.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.cheryme.top/Article/details/gt2mhkkxbqf.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.guannengcc.top/Article/details/gt2jbzgakbp.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.daxiang520.top/Article/details/gt2jcotzmze.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zycfv.cn/Article/details/gt2zhoqlazs.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yangfankeji.com/Article/details/gt2afwrarvz.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jiagoushi.top/Article/details/gt2qxghodtn.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2ashxaknh.html

K. JSON 与序列化
来源：http://dali.yongpay.top/Article/details/gt2ixumgmgz.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2balmuskt.html

[K01] 对象转 JSON 字符串
来源：http://dali.quarkkingdee.top/Article/details/gt2srmcqybj.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.cashguo.top/Article/details/gt2ivjjappf.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.havefunace.top/Article/details/gt2jtweolya.html

JS:   JSON.stringify(obj)
来源：http://dali.hnqzz.top/Article/details/gt2ufwzcyxe.html

TS:   JSON.stringify(obj)
来源：http://dali.dashuyun.cn/Article/details/gt2rxtynmyc.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.sufxvd.cn/Article/details/gt2syakxoqj.html

Go:   json.Marshal(obj)
来源：http://dali.pycfn.com/Article/details/gt2ttxjgcbq.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.cheryme.top/Article/details/gt2kqvjbhqm.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.xinyue.icu/Article/details/gt2fjbuubdl.html

[K02] JSON 字符串转对象
来源：http://dali.zhengqikj.top/Article/details/gt2pgntqiuh.html

Py:   json.loads(s)
来源：http://dali.sysykeji.top/Article/details/gt2ehkqmucc.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.guannengcc.top/Article/details/gt2ufsduuyd.html

JS:   JSON.parse(s)
来源：http://dali.yuxming.cn/Article/details/gt2oipnbrlh.html

TS:   JSON.parse(s)
来源：http://dali.meibo888.top/Article/details/gt2ozsxjpgq.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.dianchejie.cn/Article/details/gt2qzmtsdoi.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.ppjwa.cn/Article/details/gt2wzylhmuu.html

Ruby: JSON.parse(s)
来源：http://dali.daxiang520.top/Article/details/gt2bypjhuyi.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.c1oappe.top/Article/details/gt2cvwhirqs.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhengqikj.top/Article/details/gt2szqrpafw.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.sysykeji.top/Article/details/gt2ciylqrmj.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.cucudq.cn/Article/details/gt2qoriqnug.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.hfpthk.cn/Article/details/gt2qideoamc.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.cqqwz.cn/Article/details/gt2yqyjlier.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yangfankeji.com/Article/details/gt2vpfrnogp.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cqonzuhm.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gt2orsfysat.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.gaohongyu789.top/Article/details/gt2vezdrxoy.html

[K04] 读取 JSON 文件
来源：http://dali.yj20258.top/Article/details/gt2zjgkgebo.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zycfv.cn/Article/details/gt2sllkvokf.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.hnxiangtu.top/Article/details/gt2clwqkkfa.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.gaohongyu789.top/Article/details/gt2pdnzvvtw.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shuidangran.top/Article/details/gt2wghaudck.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.vqdsnc.cn/Article/details/gt2ckjqnbtn.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zdqjudy.top/Article/details/gt2oniaiacj.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.shuidangran.top/Article/details/gt2moihkmle.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hammf.cn/Article/details/gt2cwukfawn.html

[K05] 深拷贝对象
来源：http://dali.fengsongda.top/Article/details/gt2oyjupelm.html

Py:   copy.deepcopy(obj)
来源：http://dali.aibaodan.cn/Article/details/gt2mnwtoqwv.html

PHP:  unserialize(serialize($obj));
来源：http://dali.zycfv.cn/Article/details/gt2dhagrfqw.html

JS:   structuredClone(obj)
来源：http://dali.yj20258888.top/Article/details/gt2xzquvtvs.html

TS:   structuredClone(obj)
来源：http://dali.zhoulong.xyz/Article/details/gt2lroujjoi.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.xuanzx.com/Article/details/gt2kpgajnst.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.nanxinkj.top/Article/details/gt2xcgpxpnt.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.tianlin.xyz/Article/details/gt2edpqscad.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.hysaishi.cn/Article/details/gt2brolgquu.html

[K06] 解析 URL 查询串
来源：http://dali.hywenlv.cn/Article/details/gt2nklhsody.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.wangshuangyany.cn/Article/details/gt2cpugqfry.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.sufxvd.cn/Article/details/gt2hibvaogm.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2eordokfn.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinqigfzy.top/Article/details/gt2uhynmiyc.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jyoumei.cn/Article/details/gt2unqzhzhs.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jlsjyb.cn/Article/details/gt2phkuzwqq.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.chenzaomai.com/Article/details/gt2rqarxxzd.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.ydzc1.top/Article/details/gt2qkjteiny.html

[K07] 进制转换
来源：http://dali.shuidangran.top/Article/details/gt2vlbaoydu.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.mhx1999.top/Article/details/gt2rrbdwray.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.cashguo.top/Article/details/gt2ukdbiskr.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.tian-w.cn/Article/details/gt2wttqswfb.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.hongshengwenyu.top/Article/details/gt2kjczrlou.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.tianlin.xyz/Article/details/gt2aigjpsru.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.hongshengwenyu.top/Article/details/gt2dvxhboco.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.wangdashe.top/Article/details/gt2dennayzn.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.sweek.top/Article/details/gt2dfvlqmcc.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.guowangkeji.top/Article/details/gt2zsufbeip.html

Py:   pickle.dumps(obj)
来源：http://dali.cheryme.top/Article/details/gt2duprqnwp.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.meibo888.top/Article/details/gt2looqcfhl.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.haohaochexian.top/Article/details/gt2xfgizggj.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.aizwys.cn/Article/details/gt2alhaksyo.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.hysaishi.cn/Article/details/gt2tdnarvum.html

Go:   encoding/gob
来源：http://dali.yuxming.cn/Article/details/gt2rlqiuzuq.html

Ruby: Marshal.dump(obj)
来源：http://dali.sufxvd.cn/Article/details/gt2ivvhwhnv.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.daxiang520.top/Article/details/gt2ddbmlcbj.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2qiuwdefw.html

L. 网络请求
来源：http://dali.gaohongyu789.top/Article/details/gt2jmpfqtck.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2ippvneov.html

[L01] 发送 GET 请求
来源：http://dali.jinqigufen.top/Article/details/gt2pyykrvuf.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yj20258.top/Article/details/gt2lcjjurjl.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jiagoushi.top/Article/details/gt2kolnnugp.html

JS:   await fetch(url)
来源：http://dali.shzxlz.cn/Article/details/gt2znlmjyww.html

TS:   await fetch(url)
来源：http://dali.haohaochexian.top/Article/details/gt2xbfrzrzg.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.tian-w.cn/Article/details/gt2rixtgsed.html

Go:   resp, err := http.Get(url)
来源：http://dali.guannengcc.top/Article/details/gt2yhaxoawo.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.cdnleiting.top/Article/details/gt2dbsacmsh.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.cdnleiting.top/Article/details/gt2kaprfjxk.html

[L02] 发送 POST JSON
来源：http://dali.tian-w.cn/Article/details/gt2hceqqzhs.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.redwolf501.top/Article/details/gt2jlheqtru.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.sufxvd.cn/Article/details/gt2jjskdtjx.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.svipenyu.cn/Article/details/gt2kivjgndk.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yj202588.top/Article/details/gt2hbqlknrs.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.cucudq.cn/Article/details/gt2djlpbtgb.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jinqigfzy.top/Article/details/gt2ytpbpfue.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jiagoushi.top/Article/details/gt2ipbpkrie.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jinqigufen.top/Article/details/gt2pvrqrdis.html

[L03] 设置自定义请求头
来源：http://dali.cdnleiting.top/Article/details/gt2ptcmokew.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhongyouzk.top/Article/details/gt2fvednspn.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.daxiang520.top/Article/details/gt2iyzyzhip.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.snrcjt.cn/Article/details/gt2pokjlcuh.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.shangyingyoupin.top/Article/details/gt2gwkabuvl.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.chenjidiqi.icu/Article/details/gt2uosokbqm.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.xuetiantiany.cn/Article/details/gt2walnuvvs.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.sxryk.cn/Article/details/gt2cckwkdlz.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.ivvv.top/Article/details/gt2fnnxlamx.html

[L04] 设置超时
来源：http://dali.guowangkeji.top/Article/details/gt2hrikvohv.html

Py:   requests.get(url, timeout=5)
来源：http://dali.gotoacloud.top/Article/details/gt2nhghxrzd.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.xinyue.icu/Article/details/gt2lpwqqthb.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.sxryk.cn/Article/details/gt2aegpliqh.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jyoumei.cn/Article/details/gt2usdmazcp.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jianghu66.top/Article/details/gt2zfdnbgjs.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.feifeiyinyue.top/Article/details/gt2dxpzkbbh.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.sxryk.cn/Article/details/gt2qmcfyvim.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.gaohongyu789.top/Article/details/gt2kwkpwpxs.html

[L05] 上传文件（multipart）
来源：http://dali.guannengcc.top/Article/details/gt2gymjdaua.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.quarkkingdee.top/Article/details/gt2vrrzkknq.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.ydzc1.top/Article/details/gt2dbohhemz.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yuanzhike.top/Article/details/gt2uwpvrhql.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.aibaodan.cn/Article/details/gt2ceofcgxt.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.gzhubu.top/Article/details/gt2iczfambm.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.haohaochexian.top/Article/details/gt2attrwqrf.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.daria6918.cn/Article/details/gt2lxurghma.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.xuanzx.com/Article/details/gt2ctajeqcf.html

[L06] 解析响应为 JSON
来源：http://dali.yj20258.top/Article/details/gt2uuabclkz.html

Py:   resp.json()
来源：http://dali.zhixingplan.top/Article/details/gt2jgfyacfq.html

PHP:  json_decode($body, true);
来源：http://dali.cashguo.top/Article/details/gt2ofuzmptc.html

JS:   await resp.json()
来源：http://dali.jinqigufen.top/Article/details/gt2ncelwyid.html

TS:   await resp.json()
来源：http://dali.fengsongda.top/Article/details/gt2evpcqqpe.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yrmywzqp.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.snrcjt.cn/Article/details/gt2djlncizt.html

Ruby: JSON.parse(resp.body)
来源：http://dali.tanke756.top/Article/details/gt2kxzvzmeb.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.316326.xyz/Article/details/gt2iqmdpxas.html

[L07] 处理 HTTP 状态码
来源：http://dali.mhx1999.top/Article/details/gt2tvensude.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jinqigufen.top/Article/details/gt2uccrbjag.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.fengsongda.top/Article/details/gt2rmzpsecq.html

JS:   resp.ok;  resp.status
来源：http://dali.bjfxy.top/Article/details/gt2gpdplhet.html

TS:   resp.ok;  resp.status
来源：http://dali.yvedp.cn/Article/details/gt2lgxzragl.html

Java: resp.statusCode()
来源：http://dali.sufxvd.cn/Article/details/gt2jsravdgg.html

Go:   resp.StatusCode
来源：http://dali.sxryk.cn/Article/details/gt2rxvvdyqh.html

Ruby: resp.code.to_i
来源：http://dali.ydzc1.top/Article/details/gt2xklqzrun.html

C#:   (int)resp.StatusCode
来源：http://dali.sysykeji.top/Article/details/gt2swsybywj.html

[L08] 并发请求多个地址
来源：http://dali.vqdsnc.cn/Article/details/gt2smicbnxf.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zdqjudy.top/Article/details/gt2vqwbrckb.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhiwuduotai.top/Article/details/gt2vkemazfp.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nwbrower.top/Article/details/gt2hivfjlyf.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xuanzx.com/Article/details/gt2wkokhnnl.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.smart0.xyz/Article/details/gt2jpkkbfgh.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.sxryk.cn/Article/details/gt2fqdoevyc.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.tianlin.xyz/Article/details/gt2vynzpthe.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.chenjidiqi.icu/Article/details/gt2pukbahms.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2xxdeugnc.html

M. 命令行 / 进程 / 环境
来源：http://dali.sxryk.cn/Article/details/gt2liuxkuit.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2lmynpirg.html

[M01] 读取命令行参数
来源：http://dali.zhoulong.xyz/Article/details/gt2xdcivnev.html

Py:   sys.argv[1:]
来源：http://dali.redwolf501.top/Article/details/gt2njozkopi.html

PHP:  $argv;  $argc;
来源：http://dali.snrcjt.cn/Article/details/gt2ozmlgrix.html

JS:   process.argv.slice(2)
来源：http://dali.yongpay.top/Article/details/gt2nscjwhvc.html

TS:   process.argv.slice(2)
来源：http://dali.zhoulong.xyz/Article/details/gt2nvtezwne.html

Java: args 数组（main 方法参数）
来源：http://dali.cheryme.top/Article/details/gt2mhiemjon.html

Go:   os.Args[1:]
来源：http://dali.ydzc1.top/Article/details/gt2qbqmpjnr.html

Ruby: ARGV
来源：http://dali.snrcjt.cn/Article/details/gt2stnnowvs.html

C#:   args 数组（Main 方法参数）
来源：http://dali.cheryme.top/Article/details/gt2ogootxsr.html

[M02] 读取环境变量
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vkxknqqw.html

Py:   os.environ.get("HOME")
来源：http://dali.wangdashe.top/Article/details/gt2ncchknsd.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhoulong.xyz/Article/details/gt2hnicglna.html

JS:   process.env.HOME
来源：http://dali.zhoulong.xyz/Article/details/gt2zprkftmv.html

TS:   process.env.HOME
来源：http://dali.cheryme.top/Article/details/gt2johenprq.html

Java: System.getenv("HOME")
来源：http://dali.svipenyu.cn/Article/details/gt2dwqkpzmt.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.ydzc1.top/Article/details/gt2nyoytsxj.html

Ruby: ENV["HOME"]
来源：http://dali.tian-w.cn/Article/details/gt2epvznyvw.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yongpay.top/Article/details/gt2egxuuoar.html

[M03] 执行外部命令
来源：http://dali.iojbl.cn/Article/details/gt2wzvhqlnk.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.cqqwz.cn/Article/details/gt2unbbjatt.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hnxiangtu.top/Article/details/gt2yutbqoty.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.birdmap.top/Article/details/gt2fwiueyrh.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jianghu66.top/Article/details/gt2xgglqaps.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.chenzaomai.com/Article/details/gt2arliarpu.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.chenzaomai.com/Article/details/gt2lwjlytsn.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.gotoacloud.top/Article/details/gt2enozwmrv.html

C#:   Process.Start("ls", "-l");
来源：http://dali.cqqwz.cn/Article/details/gt2sozrmtxo.html

[M04] 获取当前工作目录
来源：http://dali.zycfv.cn/Article/details/gt2snsqhrje.html

Py:   os.getcwd()
来源：http://dali.mhx1999.top/Article/details/gt2pncwlqet.html

PHP:  getcwd();
来源：http://dali.ybcxt.top/Article/details/gt2zwlsdtmx.html

JS:   process.cwd()
来源：http://dali.hywenlv.cn/Article/details/gt2yzixvyni.html

TS:   process.cwd()
来源：http://dali.sufxvd.cn/Article/details/gt2mxwpmmae.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jinqigufen.top/Article/details/gt2woqpqlhk.html

Go:   os.Getwd()
来源：http://dali.gaohongyu789.top/Article/details/gt2dfsglsoi.html

Ruby: Dir.pwd
来源：http://dali.guowangkeji.top/Article/details/gt2nxhqxrqx.html


<!-- 参考信息 -->