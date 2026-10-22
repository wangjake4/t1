代发 wailian999

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.andypj.xyz/Article/details/gtvsiyoawq.html

[I07] 忽略大小写与多行模式
来源：http://dali.cheryme.top/Article/details/gtdopvtwmt.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.shuidangran.top/Article/details/gtecnvgabg.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhoulong.xyz/Article/details/gtgwozekwq.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yueranfly.top/Article/details/gtwpanvzsu.html

TS:   /error/gim
来源：http://dali.redwolf501.top/Article/details/gtqdqgbopv.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmdkjxqcv.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.andypj.xyz/Article/details/gtcozmtipg.html

Ruby: s.scan(/error/i)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuibjooga.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.cheryme.top/Article/details/gttkkqrglc.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.ydzc1.top/Article/details/gtvjltqayp.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.fzhhl.top/Article/details/gttjhhunho.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.316326.xyz/Article/details/gtgbggwulv.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hnqzz.top/Article/details/gtbhtvrufy.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtooxmxieo.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.haohaochexian.top/Article/details/gtkpkdmmuh.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.gotoacloud.top/Article/details/gttujyhzhm.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.shangyingyoupin.top/Article/details/gtedpjvkdy.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhoulong.xyz/Article/details/gtppugankd.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtghewstqu.html

J. 日期与时间
来源：http://dali.chenzaomai.com/Article/details/gtwxvmoodc.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtriwipxvx.html

[J01] 获取当前时间
来源：http://dali.gotoacloud.top/Article/details/gtvrovpgro.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yj20258.top/Article/details/gtpxjyvfdq.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhijiandao.cn/Article/details/gtdpekxwvi.html

JS:   new Date();  Date.now()
来源：http://dali.jiagoushi.top/Article/details/gtpmksatog.html

TS:   new Date();  Date.now()
来源：http://dali.cucudq.cn/Article/details/gtbqxnqhxb.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.guowangkeji.top/Article/details/gtswzyzaof.html

Go:   time.Now()
来源：http://dali.xziqi.cn/Article/details/gthkyoxpvn.html

Ruby: Time.now
来源：http://dali.yueranfly.top/Article/details/gtwbdyhfsq.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhiwuduotai.top/Article/details/gtjeksfomp.html

[J02] 格式化输出
来源：http://dali.jianghu66.top/Article/details/gthkrftwdr.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cashguo.top/Article/details/gtnzzhcyfz.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.0kj1m.cn/Article/details/gtbhgwcubl.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.quarkkingdee.top/Article/details/gtbhlsowpe.html

TS:   d.toISOString()
来源：http://dali.jyoumei.cn/Article/details/gtypxnmchv.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jinqigufen.top/Article/details/gtvagbqsgz.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.guannengcc.top/Article/details/gtzwfrqgiz.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ppjwa.cn/Article/details/gtoqhydjgi.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.guannengcc.top/Article/details/gtbrhdgylo.html

[J03] 字符串解析为日期
来源：http://dali.nanxinkj.top/Article/details/gtnpdcrnmp.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.andypj.xyz/Article/details/gtzuraxejx.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.tian-w.cn/Article/details/gtziicoxdb.html

JS:   new Date("2024-01-02")
来源：http://dali.xuetiantiany.cn/Article/details/gtrgkixybl.html

TS:   new Date("2024-01-02")
来源：http://dali.dianchejie.cn/Article/details/gtgnjqyged.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yj20258888.top/Article/details/gtdhabppne.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgotxuiud.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvreqozqj.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.sweek.top/Article/details/gthtfwfbid.html

[J04] 时间戳与日期互转
来源：http://dali.dashuyun.cn/Article/details/gtrfepgjem.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.feifeiyinyue.top/Article/details/gtrzyhmmpl.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.vqdsnc.cn/Article/details/gthakwswpk.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.cqqwz.cn/Article/details/gtwxdidwek.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.smart0.xyz/Article/details/gtvaafogkn.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.yj20258.top/Article/details/gtcaifphka.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jinghuilouyu.cn/Article/details/gtpbibwiqf.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.ivvv.top/Article/details/gttimbrmgk.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.shanyushiyangtech.top/Article/details/gtcwdiypvf.html

[J05] 时间加减（加 7 天）
来源：http://dali.yonumen.top/Article/details/gtfowpecel.html

Py:   now + timedelta(days=7)
来源：http://dali.sxryk.cn/Article/details/gtmmeifwyx.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yj202588.top/Article/details/gtkdsgabml.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.chenzaomai.com/Article/details/gtzozxqwgy.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yj20258888.top/Article/details/gtaiwaudpy.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.hfpthk.cn/Article/details/gttlspxzba.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yanxiufei.cn/Article/details/gtswexioxp.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jiagoushi.top/Article/details/gtmnynwgbg.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.hysaishi.cn/Article/details/gtkldgqnor.html

[J06] 计算两时间之差
来源：http://dali.yj20258.top/Article/details/gtzdfrozmx.html

Py:   (end - start).total_seconds()
来源：http://dali.zhixingplan.top/Article/details/gtodevwatk.html

PHP:  $end->diff($start)->days;
来源：http://dali.quarkkingdee.top/Article/details/gtcdzcmtvi.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.vqdsnc.cn/Article/details/gtnkwoixld.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yuxming.cn/Article/details/gtwhaaepge.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.nanxinkj.top/Article/details/gtcvrpebla.html

Go:   end.Sub(start).Hours()
来源：http://dali.ehwqpu.com/Article/details/gtfllbuqsc.html

Ruby: end - start                 # 返回秒数
来源：http://dali.gogol.net.cn/Article/details/gtbuugbhby.html

C#:   (end - start).TotalSeconds
来源：http://dali.pycfn.com/Article/details/gtyfwsixtx.html

[J07] 比较两个日期
来源：http://dali.fengsongda.top/Article/details/gtqykgsbwc.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.aizwys.cn/Article/details/gtjgokhvra.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jqgufenzy.top/Article/details/gtbdsbkxdm.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.fzhhl.top/Article/details/gtjvgaoeiv.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.andypj.xyz/Article/details/gtinuxmzum.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.hfpthk.cn/Article/details/gtqedqmunc.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yanxiufei.cn/Article/details/gtfyyfvnem.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.xinyue.icu/Article/details/gtkcurtkuc.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.xuanzx.com/Article/details/gthwdqirsh.html

[J08] 提取年月日与星期
来源：http://dali.cqqwz.cn/Article/details/gtyynhiltc.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.cucudq.cn/Article/details/gtsvsawtvh.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jqgufenzy.top/Article/details/gtrfkvpkmp.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.hfpthk.cn/Article/details/gtopqdezgb.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.hysaishi.cn/Article/details/gtztrqrvsl.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.shanyushiyangtech.top/Article/details/gtzaqaplou.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.dashuyun.cn/Article/details/gtbqsqbkwf.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.chenzaomai.com/Article/details/gtgnuvenht.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yonumen.top/Article/details/gttiserxsw.html

[J09] 时区处理
来源：http://dali.meibo888.top/Article/details/gtxgwyweoa.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.sweek.top/Article/details/gttffstlwv.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.tanke756.top/Article/details/gtnhcnlhog.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yj20258888.top/Article/details/gtkmlnolmi.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.fengsongda.top/Article/details/gtybwyawpw.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yj202588.top/Article/details/gtzrfmripv.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.xinyue.icu/Article/details/gtftpwvheb.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.chenzaomai.com/Article/details/gtlobjtvlg.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.nanxuanxn.top/Article/details/gtugqirqap.html

[J10] 取今天 / 本月第一天
来源：http://dali.nanxinkj.top/Article/details/gtzsehypva.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jyoumei.cn/Article/details/gtmftiutph.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.hysaishi.cn/Article/details/gtbfsaytjy.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtvtukvmci.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.pycfn.com/Article/details/gtbvvgfwaz.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.hysaishi.cn/Article/details/gttjlovxho.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jlsjyb.cn/Article/details/gtiybgswew.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jqgufenzy.top/Article/details/gtfohwpgag.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.sxryk.cn/Article/details/gtktxnfczi.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtnqxlpuhx.html

K. JSON 与序列化
来源：http://dali.9152youxi.cn/Article/details/gtnevwgqiu.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtsbysglkj.html

[K01] 对象转 JSON 字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gtfntdjtet.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.sxryk.cn/Article/details/gtlajpwbxx.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.shangyingyoupin.top/Article/details/gtqfnvqjsz.html

JS:   JSON.stringify(obj)
来源：http://dali.shuidangran.top/Article/details/gteyagsfpb.html

TS:   JSON.stringify(obj)
来源：http://dali.bjfxy.top/Article/details/gtsbaintkz.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jqgfzy.top/Article/details/gthsfvovbu.html

Go:   json.Marshal(obj)
来源：http://dali.jyoumei.cn/Article/details/gtgnqoigwk.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.xziqi.cn/Article/details/gtebaailfj.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhixingplan.top/Article/details/gtcsydiowj.html

[K02] JSON 字符串转对象
来源：http://dali.svipenyu.cn/Article/details/gtcojxozgq.html

Py:   json.loads(s)
来源：http://dali.sysykeji.top/Article/details/gtolyhctzp.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.vqdsnc.cn/Article/details/gtzclsqdzs.html

JS:   JSON.parse(s)
来源：http://dali.smart0.xyz/Article/details/gtpjogfnkv.html

TS:   JSON.parse(s)
来源：http://dali.hywenlv.cn/Article/details/gtsstkuprm.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.haohaochexian.top/Article/details/gtudfgjkim.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jianghu66.top/Article/details/gtcmfjuxbj.html

Ruby: JSON.parse(s)
来源：http://dali.snrcjt.cn/Article/details/gtmycnhhyv.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.ehwqpu.com/Article/details/gtrkmvcxgt.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jyoumei.cn/Article/details/gtjermzknd.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.pengpengdd.cyou/Article/details/gtmvycehqj.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.ppjwa.cn/Article/details/gtabfiznlm.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jinqigfzy.top/Article/details/gtbhrmdpad.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.andypj.xyz/Article/details/gtimlawdst.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.ppjwa.cn/Article/details/gtvanukofm.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.fengsongda.top/Article/details/gteokarlfr.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.0kj1m.cn/Article/details/gtvuawdjem.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.sxryk.cn/Article/details/gtzjihkvpr.html

[K04] 读取 JSON 文件
来源：http://dali.sweek.top/Article/details/gtzfbnnvng.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.daria6918.cn/Article/details/gtphwjivgu.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.gaohongyu789.top/Article/details/gtxvmnxqht.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yonumen.top/Article/details/gtyszqdxef.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shzxlz.cn/Article/details/gtvabjhvas.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.guowangkeji.top/Article/details/gtwbpnizwm.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.aizwys.cn/Article/details/gtcoglbdzc.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.chenlongwang.top/Article/details/gtaajyxuhs.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.xuanzx.com/Article/details/gtuyeciwph.html

[K05] 深拷贝对象
来源：http://dali.iojbl.cn/Article/details/gtaisquvyi.html

Py:   copy.deepcopy(obj)
来源：http://dali.snrcjt.cn/Article/details/gtfjexeypa.html

PHP:  unserialize(serialize($obj));
来源：http://dali.shuidangran.top/Article/details/gtesewbyxe.html

JS:   structuredClone(obj)
来源：http://dali.hysaishi.cn/Article/details/gtbbvmaseq.html

TS:   structuredClone(obj)
来源：http://dali.zhixingplan.top/Article/details/gtsliejbry.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.mhx1999.top/Article/details/gtwqgfkdbb.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.chenzaomai.com/Article/details/gtrvunqhxo.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.snrcjt.cn/Article/details/gtnhlqmuej.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.dianchejie.cn/Article/details/gtmdbxcvuk.html

[K06] 解析 URL 查询串
来源：http://dali.xziqi.cn/Article/details/gtuietaowq.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.kuanghao11.cn/Article/details/gtopwtxsbj.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.nanxuanxn.top/Article/details/gtqxumsnst.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.gotoacloud.top/Article/details/gtydgtbjrd.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.quarkkingdee.top/Article/details/gthesfbmyn.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.quarkkingdee.top/Article/details/gtmksulnfq.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.nanxuanxn.top/Article/details/gthzfwotrj.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jlsjyb.cn/Article/details/gtdglkbgpk.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yongpay.top/Article/details/gtvqhenodr.html

[K07] 进制转换
来源：http://dali.gzhubu.top/Article/details/gtnsfkqwlc.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.pengpengdd.cyou/Article/details/gtfgzjqzol.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzsfwbcdx.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.tian-w.cn/Article/details/gtchqrzkdp.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.hfpthk.cn/Article/details/gtkxvrflqg.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yuxming.cn/Article/details/gtgfpavsfj.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.nwbrower.top/Article/details/gtullkwvjh.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.shuidangran.top/Article/details/gtmvkdgeha.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.nwbrower.top/Article/details/gtbwbbsmqh.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.meibo888.top/Article/details/gtfxqtzwjz.html

Py:   pickle.dumps(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtyqjomgmm.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.hongshengwenyu.top/Article/details/gtgrapgoco.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.meibo888.top/Article/details/gtokkouilm.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zhijiandao.cn/Article/details/gtrbndgwxm.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yvedp.cn/Article/details/gtbczgniny.html

Go:   encoding/gob
来源：http://dali.yj202588.top/Article/details/gtsogjbixd.html

Ruby: Marshal.dump(obj)
来源：http://dali.jyoumei.cn/Article/details/gthpigxmrn.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.cheryme.top/Article/details/gtmytkrmuk.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtblujemdo.html

L. 网络请求
来源：http://dali.jinghuilouyu.cn/Article/details/gtnwbduwhe.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtkwzenumi.html

[L01] 发送 GET 请求
来源：http://dali.tian-w.cn/Article/details/gtqrvwrkgy.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.daxiang520.top/Article/details/gtebgkncev.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.316326.xyz/Article/details/gtylcariij.html

JS:   await fetch(url)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqrtwwftv.html

TS:   await fetch(url)
来源：http://dali.zhixingplan.top/Article/details/gtbihqrkrn.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.xinyue.icu/Article/details/gtdoykycrc.html

Go:   resp, err := http.Get(url)
来源：http://dali.daria6918.cn/Article/details/gtfapupaes.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.daxiang520.top/Article/details/gtiqrfjtdd.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.aibaodan.cn/Article/details/gtuqijdxhb.html

[L02] 发送 POST JSON
来源：http://dali.hywenlv.cn/Article/details/gthhsbahfy.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.daria6918.cn/Article/details/gtmjlhjukg.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.havefunace.top/Article/details/gtkkxafzob.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.nwbrower.top/Article/details/gtcwqhxuwd.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.tian-w.cn/Article/details/gtalijzboq.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwiktthzo.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.nanxinkj.top/Article/details/gtclerligf.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.kuanghao11.cn/Article/details/gtimhqxgtk.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhijiandao.cn/Article/details/gtfazdcfgn.html

[L03] 设置自定义请求头
来源：http://dali.aizwys.cn/Article/details/gtctzlsmym.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.shanyushiyangtech.top/Article/details/gtkihxzngu.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.chenzaomai.com/Article/details/gtndpshxzm.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwcnlqxef.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gtnmyzshvr.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.cdnleiting.top/Article/details/gtkadjvtem.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.hnxiangtu.top/Article/details/gtmarlbmca.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yanxiufei.cn/Article/details/gtvkrltaxc.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.316326.xyz/Article/details/gthldykmjv.html

[L04] 设置超时
来源：http://dali.zhiwuduotai.top/Article/details/gtcadbklbz.html

Py:   requests.get(url, timeout=5)
来源：http://dali.xinyue.icu/Article/details/gtwzlgcdvc.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yj202588.top/Article/details/gtnnsgvshz.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yj202588.top/Article/details/gtcocgawho.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.mhx1999.top/Article/details/gtryhdzxey.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.cheryme.top/Article/details/gtxlqtyttb.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.0kj1m.cn/Article/details/gtgjakhdfo.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.9152youxi.cn/Article/details/gtqwiwtuvm.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtebqsrkii.html

[L05] 上传文件（multipart）
来源：http://dali.gogol.net.cn/Article/details/gtraqgdvzt.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.daria6918.cn/Article/details/gtjgbczaev.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.chenjidiqi.icu/Article/details/gtvuekpbdd.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zycfv.cn/Article/details/gtjhxsnmqp.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yonumen.top/Article/details/gtxcbnnacc.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yongpay.top/Article/details/gtxwhqnxou.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.xinyue.icu/Article/details/gttoteohcr.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yanxiufei.cn/Article/details/gtwqmqrtlk.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gtbenldlnu.html

[L06] 解析响应为 JSON
来源：http://dali.gaohongyu789.top/Article/details/gtuaauwarr.html

Py:   resp.json()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqdecfqfw.html

PHP:  json_decode($body, true);
来源：http://dali.dashuyun.cn/Article/details/gtbxeuzbow.html

JS:   await resp.json()
来源：http://dali.shuidangran.top/Article/details/gtfgbaijtl.html

TS:   await resp.json()
来源：http://dali.hongshengwenyu.top/Article/details/gtszfcprpe.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjmpnbkrn.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.sxryk.cn/Article/details/gtwxzhifik.html

Ruby: JSON.parse(resp.body)
来源：http://dali.nwbrower.top/Article/details/gtlrbeboky.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.hammf.cn/Article/details/gthhggoqmu.html

[L07] 处理 HTTP 状态码
来源：http://dali.chenlongwang.top/Article/details/gtqrvdjdox.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.gaohongyu789.top/Article/details/gtkqcklklk.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.guannengcc.top/Article/details/gtgcqagpny.html

JS:   resp.ok;  resp.status
来源：http://dali.jinghuilouyu.cn/Article/details/gtstgiepji.html

TS:   resp.ok;  resp.status
来源：http://dali.jqgufenzy.top/Article/details/gtfkqjsjjr.html

Java: resp.statusCode()
来源：http://dali.jqgfzy.top/Article/details/gtphwucjab.html

Go:   resp.StatusCode
来源：http://dali.jqgufenzy.top/Article/details/gtffwjwiwd.html

Ruby: resp.code.to_i
来源：http://dali.havefunace.top/Article/details/gtolzhdceo.html

C#:   (int)resp.StatusCode
来源：http://dali.yuxming.cn/Article/details/gtsdhmpspm.html

[L08] 并发请求多个地址
来源：http://dali.sysykeji.top/Article/details/gtgfplhpws.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yj20258888.top/Article/details/gtqvbceqkn.html

PHP:  curl_multi_init() 系列
来源：http://dali.daria6918.cn/Article/details/gtwnidmlhh.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yangfankeji.com/Article/details/gtmtugnnql.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jiagoushi.top/Article/details/gthvshnecj.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.hnxiangtu.top/Article/details/gtcxkjsrsy.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.c1oappe.top/Article/details/gtvgabkxxj.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yj20258888.top/Article/details/gtvoapyzls.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.0kj1m.cn/Article/details/gtnbiheigz.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtwpxogscq.html

M. 命令行 / 进程 / 环境
来源：http://dali.jiagoushi.top/Article/details/gtgpodwdph.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtetcgwcno.html

[M01] 读取命令行参数
来源：http://dali.shzxlz.cn/Article/details/gtheoknxze.html

Py:   sys.argv[1:]
来源：http://dali.c1oappe.top/Article/details/gtscmobelt.html

PHP:  $argv;  $argc;
来源：http://dali.jinghuilouyu.cn/Article/details/gtnmyfzfkz.html

JS:   process.argv.slice(2)
来源：http://dali.pengpengdd.cyou/Article/details/gtlelwiwod.html

TS:   process.argv.slice(2)
来源：http://dali.wangshuangyany.cn/Article/details/gtfbpdmoph.html

Java: args 数组（main 方法参数）
来源：http://dali.zhoulong.xyz/Article/details/gtzmvrbmhd.html

Go:   os.Args[1:]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgofteaqh.html

Ruby: ARGV
来源：http://dali.zycfv.cn/Article/details/gtoqabvihm.html

C#:   args 数组（Main 方法参数）
来源：http://dali.quarkkingdee.top/Article/details/gttanohtro.html

[M02] 读取环境变量
来源：http://dali.chenjidiqi.icu/Article/details/gtzwxrkfvm.html

Py:   os.environ.get("HOME")
来源：http://dali.tian-w.cn/Article/details/gtoplkjilm.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.feifeiyinyue.top/Article/details/gtdflmpuda.html

JS:   process.env.HOME
来源：http://dali.cheryme.top/Article/details/gtftlbssgw.html

TS:   process.env.HOME
来源：http://dali.yj20258888.top/Article/details/gtholsamcz.html

Java: System.getenv("HOME")
来源：http://dali.shanyushiyangtech.top/Article/details/gtdkbmpljf.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.shzxlz.cn/Article/details/gthugaadfk.html

Ruby: ENV["HOME"]
来源：http://dali.pengpengdd.cyou/Article/details/gtgdadyala.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzfdpnfpm.html

[M03] 执行外部命令
来源：http://dali.jinqigufen.top/Article/details/gtuftzryxk.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hnqzz.top/Article/details/gthhlbkwak.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.shzxlz.cn/Article/details/gtsaxnhojk.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzdjagqje.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yj202588.top/Article/details/gtrqrqfsqu.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzpeucpfr.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.shzxlz.cn/Article/details/gtnsduexcs.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gtcvnmuwkm.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yuxming.cn/Article/details/gtmzdfdafa.html

[M04] 获取当前工作目录
来源：http://dali.haohaochexian.top/Article/details/gtaoavsyrq.html

Py:   os.getcwd()
来源：http://dali.kuanghao11.cn/Article/details/gtgyhtfxkb.html

PHP:  getcwd();
来源：http://dali.jinghuilouyu.cn/Article/details/gthologbdx.html

JS:   process.cwd()
来源：http://dali.cqqwz.cn/Article/details/gtgxtmbtcm.html

TS:   process.cwd()
来源：http://dali.daxiang520.top/Article/details/gtyroqryzr.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.pengpengdd.cyou/Article/details/gttwiljlak.html

Go:   os.Getwd()
来源：http://dali.snrcjt.cn/Article/details/gtmkgtifpb.html

Ruby: Dir.pwd
来源：http://dali.smart0.xyz/Article/details/gtriwihbay.html


<!-- 参考信息 -->