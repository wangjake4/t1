代发 wailian999

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yj20258888.top/Article/details/gt2hdduzqqv.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.smart0.xyz/Article/details/gt2yzzypzts.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.feifeiyinyue.top/Article/details/gt2evhrokjz.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wckhfsay.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cheryme.top/Article/details/gt2mgovbguz.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2twjmknbn.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.cdnleiting.top/Article/details/gt2zfvdttjb.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.cheryme.top/Article/details/gt2thhpbznz.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.gaohongyu789.top/Article/details/gt2namxiiyp.html

[I07] 忽略大小写与多行模式
来源：http://dali.hfpthk.cn/Article/details/gt2lzgjvlzn.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.iojbl.cn/Article/details/gt2wataevjm.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.xinyue.icu/Article/details/gt2nhcuwsyj.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhongyouzk.top/Article/details/gt2kqvvsmtc.html

TS:   /error/gim
来源：http://dali.fzhhl.top/Article/details/gt2gtdlmjlu.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.hammf.cn/Article/details/gt2fdfglwyu.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.pycfn.com/Article/details/gt2tjnleojk.html

Ruby: s.scan(/error/i)
来源：http://dali.iojbl.cn/Article/details/gt2ngzxfaxp.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.wangshuangyany.cn/Article/details/gt2gltmgqoy.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.birdmap.top/Article/details/gt2vfbdgyhz.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhiwuduotai.top/Article/details/gt2bsswlrtv.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.ehwqpu.com/Article/details/gt2dgdvwqec.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ivvv.top/Article/details/gt2ydokvhto.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shuidangran.top/Article/details/gt2ciqasepv.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.dashuyun.cn/Article/details/gt2durdxcxs.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yanxiufei.cn/Article/details/gt2kurjzqbp.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.cheryme.top/Article/details/gt2sdilvepo.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.wangdashe.top/Article/details/gt2lzhlvomw.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2lzutplky.html

J. 日期与时间
来源：http://dali.shangyingyoupin.top/Article/details/gt2lazmiset.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2noqecjpi.html

[J01] 获取当前时间
来源：http://dali.nanxuanxn.top/Article/details/gt2spjoafkf.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.shuidangran.top/Article/details/gt2wxtymeik.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.fengsongda.top/Article/details/gt2wepzlkdg.html

JS:   new Date();  Date.now()
来源：http://dali.yj20258888.top/Article/details/gt2duoefcnb.html

TS:   new Date();  Date.now()
来源：http://dali.yongpay.top/Article/details/gt2lwiflvke.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.ybcxt.top/Article/details/gt2gxmwgbsy.html

Go:   time.Now()
来源：http://dali.hnqzz.top/Article/details/gt2spnpehmd.html

Ruby: Time.now
来源：http://dali.zdqjudy.top/Article/details/gt2umxgolzs.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.quarkkingdee.top/Article/details/gt2yhrpgvgf.html

[J02] 格式化输出
来源：http://dali.birdmap.top/Article/details/gt2qigqvlez.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gogol.net.cn/Article/details/gt2pudqdhxt.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.cucudq.cn/Article/details/gt2bgxvsyut.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.c1oappe.top/Article/details/gt2qfrzeibv.html

TS:   d.toISOString()
来源：http://dali.quarkkingdee.top/Article/details/gt2viwwgkiq.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.pycfn.com/Article/details/gt2yefekreb.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.redwolf501.top/Article/details/gt2njjpvumi.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.bjfxy.top/Article/details/gt2ycbjfzgx.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.shzxlz.cn/Article/details/gt2aytypmsb.html

[J03] 字符串解析为日期
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lbbemjga.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.birdmap.top/Article/details/gt2dgqmwfah.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.tianlin.xyz/Article/details/gt2dkrxraub.html

JS:   new Date("2024-01-02")
来源：http://dali.shuidangran.top/Article/details/gt2jtpohoqh.html

TS:   new Date("2024-01-02")
来源：http://dali.xinyue.icu/Article/details/gt2xsqaxinq.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.316326.xyz/Article/details/gt2ogwkkglb.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.kuanghao11.cn/Article/details/gt2lpcaynpd.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.bjfxy.top/Article/details/gt2crqqttoa.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.bjfxy.top/Article/details/gt2mcvbutxo.html

[J04] 时间戳与日期互转
来源：http://dali.fzhhl.top/Article/details/gt2uaskmkdh.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jqgufenzy.top/Article/details/gt2nlbkezxj.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.havefunace.top/Article/details/gt2yxvidfnt.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.bjfxy.top/Article/details/gt2dmhehnby.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yonumen.top/Article/details/gt2flpzvjrs.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.tian-w.cn/Article/details/gt2zzxxsmhg.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yongpay.top/Article/details/gt2alekgdeh.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.tianlin.xyz/Article/details/gt2zlafnegc.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.shzxlz.cn/Article/details/gt2abfmyhxb.html

[J05] 时间加减（加 7 天）
来源：http://dali.cqqwz.cn/Article/details/gt2onwzjgrp.html

Py:   now + timedelta(days=7)
来源：http://dali.shangyingyoupin.top/Article/details/gt2fmfiyhic.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jyoumei.cn/Article/details/gt2sgpwxnpn.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jgzcltfk.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.fzhhl.top/Article/details/gt2crbtisjr.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.cheryme.top/Article/details/gt2sukgdddr.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zhixingplan.top/Article/details/gt2mlhedwyt.html

Ruby: Time.now + 7 * 86400
来源：http://dali.shangyingyoupin.top/Article/details/gt2xydnbmib.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhongyouzk.top/Article/details/gt2zuflhzht.html

[J06] 计算两时间之差
来源：http://dali.ehwqpu.com/Article/details/gt2ecwqzbsn.html

Py:   (end - start).total_seconds()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sdhynaio.html

PHP:  $end->diff($start)->days;
来源：http://dali.vqdsnc.cn/Article/details/gt2ccgybsfx.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jiagoushi.top/Article/details/gt2wyciweyy.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.xylfe.cn/Article/details/gt2tyvlnujh.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.redwolf501.top/Article/details/gt2okuczxwx.html

Go:   end.Sub(start).Hours()
来源：http://dali.gogol.net.cn/Article/details/gt2aeenhbfr.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yj20258.top/Article/details/gt2tizvqfdt.html

C#:   (end - start).TotalSeconds
来源：http://dali.jinqigufen.top/Article/details/gt2thblgiiy.html

[J07] 比较两个日期
来源：http://dali.yvedp.cn/Article/details/gt2raahejbi.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ezryajrc.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.sxryk.cn/Article/details/gt2vvxjisxd.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.aizwys.cn/Article/details/gt2ydkkssup.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.wangdashe.top/Article/details/gt2svcaeamo.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jinqigufen.top/Article/details/gt2rxiqydno.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yj20258.top/Article/details/gt2qklsfrai.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.haohaochexian.top/Article/details/gt2nsiaodnq.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.andypj.xyz/Article/details/gt2hgxbjyvy.html

[J08] 提取年月日与星期
来源：http://dali.yuanzhike.top/Article/details/gt2fxyrpgwr.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.nwbrower.top/Article/details/gt2zoprrppx.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.daxiang520.top/Article/details/gt2qmjajypl.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.wangdashe.top/Article/details/gt2lzmxbjte.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zhoulong.xyz/Article/details/gt2lgkreeie.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.gaohongyu789.top/Article/details/gt2luvclylj.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yangfankeji.com/Article/details/gt2iwfpmopb.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.chenjidiqi.icu/Article/details/gt2dwaericb.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.xuanzx.com/Article/details/gt2sbssnzvy.html

[J09] 时区处理
来源：http://dali.sufxvd.cn/Article/details/gt2ptriursi.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.vqdsnc.cn/Article/details/gt2ditogygh.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.gaohongyu789.top/Article/details/gt2ndhydsjh.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cqqwz.cn/Article/details/gt2msddrkqz.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.wangdashe.top/Article/details/gt2fqhomujn.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.svipenyu.cn/Article/details/gt2tyxxatgf.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yj20258888.top/Article/details/gt2hohqnwpy.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.ehwqpu.com/Article/details/gt2tkdzrpql.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.gotoacloud.top/Article/details/gt2ccuxrytd.html

[J10] 取今天 / 本月第一天
来源：http://dali.yongpay.top/Article/details/gt2thpbxdzb.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.nanxinkj.top/Article/details/gt2kphkrfzy.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.hfpthk.cn/Article/details/gt2obidhjzu.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.hfpthk.cn/Article/details/gt2ssqumtrt.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.316326.xyz/Article/details/gt2ojxeompl.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2lptrgnvm.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yj20258.top/Article/details/gt2ukrtwlrr.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.316326.xyz/Article/details/gt2jfzqgmnb.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.haohaochexian.top/Article/details/gt2wijxwand.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tvhcahkk.html

K. JSON 与序列化
来源：http://dali.daria6918.cn/Article/details/gt2tmdpnwgn.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2hixueueh.html

[K01] 对象转 JSON 字符串
来源：http://dali.nanxinkj.top/Article/details/gt2nudosqyv.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.chenzaomai.com/Article/details/gt2miafgdok.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhengqikj.top/Article/details/gt2xllfnfqn.html

JS:   JSON.stringify(obj)
来源：http://dali.wangdashe.top/Article/details/gt2ihlkiibn.html

TS:   JSON.stringify(obj)
来源：http://dali.redwolf501.top/Article/details/gt2anemvzcq.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.birdmap.top/Article/details/gt2bzepfuhw.html

Go:   json.Marshal(obj)
来源：http://dali.hammf.cn/Article/details/gt2ytidjowo.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.316326.xyz/Article/details/gt2zpfreiod.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.tanke756.top/Article/details/gt2thnodzdn.html

[K02] JSON 字符串转对象
来源：http://dali.svipenyu.cn/Article/details/gt2wwhaqgdi.html

Py:   json.loads(s)
来源：http://dali.ybcxt.top/Article/details/gt2ldshnlgr.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhongyouzk.top/Article/details/gt2zrvyiicl.html

JS:   JSON.parse(s)
来源：http://dali.kuanghao11.cn/Article/details/gt2sdmcguyp.html

TS:   JSON.parse(s)
来源：http://dali.yj20258.top/Article/details/gt2jfjgqnlk.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jlsjyb.cn/Article/details/gt2gogeqjdr.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jlsjyb.cn/Article/details/gt2ckmlcqjg.html

Ruby: JSON.parse(s)
来源：http://dali.yj20258.top/Article/details/gt2pjeemkeh.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.ivvv.top/Article/details/gt2eehmkodj.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhengqikj.top/Article/details/gt2onmbfunv.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.shuidangran.top/Article/details/gt2jsfpbnwg.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.316326.xyz/Article/details/gt2mpkemqim.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.dianchejie.cn/Article/details/gt2usclkdkm.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.xziqi.cn/Article/details/gt2kpstpdws.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.cqqwz.cn/Article/details/gt2kqeinaeh.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.pycfn.com/Article/details/gt2ouwjkexk.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.hnxiangtu.top/Article/details/gt2fcqefkra.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.hfpthk.cn/Article/details/gt2vbvvsixf.html

[K04] 读取 JSON 文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2trwdurxv.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.gzhubu.top/Article/details/gt2czeqoggk.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zdqjudy.top/Article/details/gt2jcqderta.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jlsjyb.cn/Article/details/gt2xadvnwku.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.quarkkingdee.top/Article/details/gt2wxdijfie.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.daxiang520.top/Article/details/gt2ljacahnr.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.fzhhl.top/Article/details/gt2ugjtydsf.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.wangdashe.top/Article/details/gt2jezgiiyp.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.chenlongwang.top/Article/details/gt2qjiohfcw.html

[K05] 深拷贝对象
来源：http://dali.cucudq.cn/Article/details/gt2ttllbexk.html

Py:   copy.deepcopy(obj)
来源：http://dali.andypj.xyz/Article/details/gt2zbmuofxx.html

PHP:  unserialize(serialize($obj));
来源：http://dali.cashguo.top/Article/details/gt2ntjifxxn.html

JS:   structuredClone(obj)
来源：http://dali.shuidangran.top/Article/details/gt2wgaogbnd.html

TS:   structuredClone(obj)
来源：http://dali.guowangkeji.top/Article/details/gt2akpinuuc.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.gogol.net.cn/Article/details/gt2papebqkf.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.redwolf501.top/Article/details/gt2vyfsroug.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.shangyingyoupin.top/Article/details/gt2tzgludyk.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.svipenyu.cn/Article/details/gt2jiefjnfd.html

[K06] 解析 URL 查询串
来源：http://dali.smart0.xyz/Article/details/gt2vkmnxesw.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.hnqzz.top/Article/details/gt2zfpuuxcn.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.ivvv.top/Article/details/gt2bfzsmcsw.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yueranfly.top/Article/details/gt2vjmdclog.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ehwqpu.com/Article/details/gt2gqweqjvr.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.zhengqikj.top/Article/details/gt2nohijwej.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yj20258888.top/Article/details/gt2gaosfwmm.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.shangyingyoupin.top/Article/details/gt2qnkkoiky.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.snrcjt.cn/Article/details/gt2svkeuxnc.html

[K07] 进制转换
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hrqadfja.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zdqjudy.top/Article/details/gt2zwrmhasp.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dbrfpbim.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.guannengcc.top/Article/details/gt2ibkvaqyd.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.hysaishi.cn/Article/details/gt2sobuqych.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jlsjyb.cn/Article/details/gt2mdpobfie.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2divbeopv.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yongpay.top/Article/details/gt2etkzukja.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.quarkkingdee.top/Article/details/gt2hlhcoipy.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.ybcxt.top/Article/details/gt2latfheqv.html

Py:   pickle.dumps(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gt2rtlvjpqc.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.tian-w.cn/Article/details/gt2eqpmhkpn.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yj20258.top/Article/details/gt2txbtbxjt.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.gaohongyu789.top/Article/details/gt2nbwgbwpx.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zhongyouzk.top/Article/details/gt2ahlcoobu.html

Go:   encoding/gob
来源：http://dali.birdmap.top/Article/details/gt2rwzngqlg.html

Ruby: Marshal.dump(obj)
来源：http://dali.nanxuanxn.top/Article/details/gt2yqwvynxd.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vpnvxrme.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2erxyfpid.html

L. 网络请求
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hyuaybnq.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2iwpklmbu.html

[L01] 发送 GET 请求
来源：http://dali.smart0.xyz/Article/details/gt2nhmdcoci.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.ppjwa.cn/Article/details/gt2vawgznso.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.tanke756.top/Article/details/gt2lbznavqx.html

JS:   await fetch(url)
来源：http://dali.c1oappe.top/Article/details/gt2jihewhzn.html

TS:   await fetch(url)
来源：http://dali.yj20258.top/Article/details/gt2gosrhixx.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jqgfzy.top/Article/details/gt2bfsrtvoq.html

Go:   resp, err := http.Get(url)
来源：http://dali.snrcjt.cn/Article/details/gt2wavsppjn.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhongyouzk.top/Article/details/gt2urpdlscu.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.gogol.net.cn/Article/details/gt2hcejunuw.html

[L02] 发送 POST JSON
来源：http://dali.nanxuanxn.top/Article/details/gt2rgllnpha.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yuxming.cn/Article/details/gt2ylfbqhsh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hywenlv.cn/Article/details/gt2xrwjlztm.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hongshengwenyu.top/Article/details/gt2uwxtkjwi.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.gzhubu.top/Article/details/gt2ixbywnta.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hongshengwenyu.top/Article/details/gt2aofdyois.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jinqigufen.top/Article/details/gt2mihbywst.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.tian-w.cn/Article/details/gt2pxufthjq.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.mhx1999.top/Article/details/gt2urlwppbl.html

[L03] 设置自定义请求头
来源：http://dali.redwolf501.top/Article/details/gt2lzdbxryl.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.fengsongda.top/Article/details/gt2inpzayma.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.birdmap.top/Article/details/gt2krelubmq.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ivvv.top/Article/details/gt2vfnhnfeb.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yanxiufei.cn/Article/details/gt2jqcsginy.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.shuidangran.top/Article/details/gt2cksmrxse.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.ybcxt.top/Article/details/gt2icugxtpa.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.pengpengdd.cyou/Article/details/gt2ubslwssi.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.pengpengdd.cyou/Article/details/gt2gcdjnjgz.html

[L04] 设置超时
来源：http://dali.ybcxt.top/Article/details/gt2bbekvpoy.html

Py:   requests.get(url, timeout=5)
来源：http://dali.redwolf501.top/Article/details/gt2tcpdpkvl.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.pengpengdd.cyou/Article/details/gt2yurwczlv.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jiagoushi.top/Article/details/gt2sieofkqf.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinqigufen.top/Article/details/gt2qnizohin.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.xylfe.cn/Article/details/gt2udwowsea.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2broupful.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.chenjidiqi.icu/Article/details/gt2otulbfhe.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.fengsongda.top/Article/details/gt2wcaeqrjh.html

[L05] 上传文件（multipart）
来源：http://dali.zdqjudy.top/Article/details/gt2qihoctjl.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hfpthk.cn/Article/details/gt2keqqqrzy.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.pengpengdd.cyou/Article/details/gt2xuhjwdme.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.ydzc1.top/Article/details/gt2evgddaut.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2herwocce.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhiwuduotai.top/Article/details/gt2xeomuelb.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jqgufenzy.top/Article/details/gt2zrqimbom.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.sxryk.cn/Article/details/gt2teohdjdq.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.daxiang520.top/Article/details/gt2qilfxsvx.html

[L06] 解析响应为 JSON
来源：http://dali.feifeiyinyue.top/Article/details/gt2mpduejyx.html

Py:   resp.json()
来源：http://dali.jqgfzy.top/Article/details/gt2aiabgrlg.html

PHP:  json_decode($body, true);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mkrvazwz.html

JS:   await resp.json()
来源：http://dali.daxiang520.top/Article/details/gt2fhftoige.html

TS:   await resp.json()
来源：http://dali.xylfe.cn/Article/details/gt2fcducjtp.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.shzxlz.cn/Article/details/gt2kmjklehg.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.tian-w.cn/Article/details/gt2opypmmot.html

Ruby: JSON.parse(resp.body)
来源：http://dali.316326.xyz/Article/details/gt2mjyorxni.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yueranfly.top/Article/details/gt2ttpaayzt.html

[L07] 处理 HTTP 状态码
来源：http://dali.jinqigfzy.top/Article/details/gt2dhgxrafd.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.kuanghao11.cn/Article/details/gt2srlimgqg.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.nwbrower.top/Article/details/gt2eugkzgem.html

JS:   resp.ok;  resp.status
来源：http://dali.mhx1999.top/Article/details/gt2keyticdl.html

TS:   resp.ok;  resp.status
来源：http://dali.pengpengdd.cyou/Article/details/gt2tbzftnno.html

Java: resp.statusCode()
来源：http://dali.ehwqpu.com/Article/details/gt2sscwancr.html

Go:   resp.StatusCode
来源：http://dali.nanxuanxn.top/Article/details/gt2mairkoqv.html

Ruby: resp.code.to_i
来源：http://dali.hfpthk.cn/Article/details/gt2agrmvmeg.html

C#:   (int)resp.StatusCode
来源：http://dali.nanxuanxn.top/Article/details/gt2rodjufjp.html

[L08] 并发请求多个地址
来源：http://dali.zdqjudy.top/Article/details/gt2lydzchra.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.birdmap.top/Article/details/gt2zyqoldyr.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhengqikj.top/Article/details/gt2yiunoivo.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yuxming.cn/Article/details/gt2ppdhlatf.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.aizwys.cn/Article/details/gt2nbbpkqia.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jinqigufen.top/Article/details/gt2rizztdmn.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.ehwqpu.com/Article/details/gt2yfjpbefu.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.smart0.xyz/Article/details/gt2hodohqxx.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.snrcjt.cn/Article/details/gt2mkviauqi.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2zdiknpje.html

M. 命令行 / 进程 / 环境
来源：http://dali.haohaochexian.top/Article/details/gt2kgxcceob.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2ikbhuley.html

[M01] 读取命令行参数
来源：http://dali.smart0.xyz/Article/details/gt2lwctgpwl.html

Py:   sys.argv[1:]
来源：http://dali.quarkkingdee.top/Article/details/gt2pmlaavmj.html

PHP:  $argv;  $argc;
来源：http://dali.aibaodan.cn/Article/details/gt2tnokttcc.html

JS:   process.argv.slice(2)
来源：http://dali.havefunace.top/Article/details/gt2mgjjuuso.html

TS:   process.argv.slice(2)
来源：http://dali.wangshuangyany.cn/Article/details/gt2gwbydeou.html

Java: args 数组（main 方法参数）
来源：http://dali.hysaishi.cn/Article/details/gt2knqxoiqu.html

Go:   os.Args[1:]
来源：http://dali.daxiang520.top/Article/details/gt2jpggszdr.html

Ruby: ARGV
来源：http://dali.andypj.xyz/Article/details/gt2jungjpxu.html

C#:   args 数组（Main 方法参数）
来源：http://dali.ppjwa.cn/Article/details/gt2rgvvcygo.html

[M02] 读取环境变量
来源：http://dali.tianlin.xyz/Article/details/gt2aghkhxyu.html

Py:   os.environ.get("HOME")
来源：http://dali.xinyue.icu/Article/details/gt2snqbarzr.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yonumen.top/Article/details/gt2vmgckrpb.html

JS:   process.env.HOME
来源：http://dali.cheryme.top/Article/details/gt2mtuvbcdh.html

TS:   process.env.HOME
来源：http://dali.fzhhl.top/Article/details/gt2ufyusvel.html

Java: System.getenv("HOME")
来源：http://dali.jqgfzy.top/Article/details/gt2xrlimowh.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jiagoushi.top/Article/details/gt2ldzrxypa.html

Ruby: ENV["HOME"]
来源：http://dali.andypj.xyz/Article/details/gt2uozvfrrr.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.cheryme.top/Article/details/gt2vudbuaoo.html

[M03] 执行外部命令
来源：http://dali.yongpay.top/Article/details/gt2pyxeawhv.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.shzxlz.cn/Article/details/gt2rxflvtui.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.guowangkeji.top/Article/details/gt2wmoagcln.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.svipenyu.cn/Article/details/gt2mnwhctie.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.bjfxy.top/Article/details/gt2chexmpdx.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jiagoushi.top/Article/details/gt2unaaxgcy.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.cashguo.top/Article/details/gt2ppotegge.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.shangyingyoupin.top/Article/details/gt2kyskmxzw.html

C#:   Process.Start("ls", "-l");
来源：http://dali.shuidangran.top/Article/details/gt2icwblrui.html


<!-- 参考信息 -->