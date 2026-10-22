代发 wailian999

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ybcxt.top/Article/details/gt2oglgrupy.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yuanzhike.top/Article/details/gt2kxdxiqsk.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.dianchejie.cn/Article/details/gt2sifsqlol.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yongpay.top/Article/details/gt2ebcwyiqh.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jinqigufen.top/Article/details/gt2usmamajf.html

[I07] 忽略大小写与多行模式
来源：http://dali.sufxvd.cn/Article/details/gt2ddwoyqel.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yvedp.cn/Article/details/gt2wrqnayrw.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.bjfxy.top/Article/details/gt2fxoifphi.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.xuanzx.com/Article/details/gt2jcklclsc.html

TS:   /error/gim
来源：http://dali.zhongyouzk.top/Article/details/gt2cdajltfo.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.xziqi.cn/Article/details/gt2rgkxalge.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.snrcjt.cn/Article/details/gt2xbntocpy.html

Ruby: s.scan(/error/i)
来源：http://dali.jlsjyb.cn/Article/details/gt2rtuujcvi.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhijiandao.cn/Article/details/gt2nojbhnbk.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.pengpengdd.cyou/Article/details/gt2chbfugsz.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.sysykeji.top/Article/details/gt2lzmqdycq.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yongpay.top/Article/details/gt2xicfsxiy.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gsoaidci.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yafobxlv.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jqgfzy.top/Article/details/gt2uxwdjdnb.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cibhjxtv.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhongyouzk.top/Article/details/gt2kmrsntcx.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.bjfxy.top/Article/details/gt2hknmvnib.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2xbzhobxf.html

J. 日期与时间
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gocvipmq.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2kiymkwxk.html

[J01] 获取当前时间
来源：http://dali.dianchejie.cn/Article/details/gt2jjindhnl.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jqgfzy.top/Article/details/gt2xkzbvczz.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.xylfe.cn/Article/details/gt2qsdofvyf.html

JS:   new Date();  Date.now()
来源：http://dali.jianghu66.top/Article/details/gt2yopmvnsp.html

TS:   new Date();  Date.now()
来源：http://dali.yvedp.cn/Article/details/gt2tqzdxirz.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.wangdashe.top/Article/details/gt2gpgjtdsm.html

Go:   time.Now()
来源：http://dali.shangyingyoupin.top/Article/details/gt2orbtgpem.html

Ruby: Time.now
来源：http://dali.tianlin.xyz/Article/details/gt2xjqlzbvb.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.dianchejie.cn/Article/details/gt2fzuvpmug.html

[J02] 格式化输出
来源：http://dali.gaohongyu789.top/Article/details/gt2pcjowitg.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hammf.cn/Article/details/gt2znolfgsq.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhengqikj.top/Article/details/gt2vodnvluv.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.fengsongda.top/Article/details/gt2trifrjmv.html

TS:   d.toISOString()
来源：http://dali.chenjidiqi.icu/Article/details/gt2mshvprnf.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yueranfly.top/Article/details/gt2fcdqspaa.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.snrcjt.cn/Article/details/gt2gqkjdvvc.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sxryk.cn/Article/details/gt2tympvnum.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.cashguo.top/Article/details/gt2ycrrohpd.html

[J03] 字符串解析为日期
来源：http://dali.jinqigufen.top/Article/details/gt2fzlhidwn.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.quarkkingdee.top/Article/details/gt2bspnkojw.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.xuanzx.com/Article/details/gt2josiccjz.html

JS:   new Date("2024-01-02")
来源：http://dali.iojbl.cn/Article/details/gt2jlhtugih.html

TS:   new Date("2024-01-02")
来源：http://dali.jianghu66.top/Article/details/gt2etfrrjhn.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hnqzz.top/Article/details/gt2syzkmobi.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zycfv.cn/Article/details/gt2mjrfzhhs.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.iojbl.cn/Article/details/gt2hhmiiits.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.hfpthk.cn/Article/details/gt2iosnbtlh.html

[J04] 时间戳与日期互转
来源：http://dali.vqdsnc.cn/Article/details/gt2ixdmxgtt.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wnutmiih.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wuxjtpij.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.xinyue.icu/Article/details/gt2kllvyefs.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.shuidangran.top/Article/details/gt2hdnbohqq.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.kuanghao11.cn/Article/details/gt2laqqdlma.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.cashguo.top/Article/details/gt2gsgpczfc.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zhoulong.xyz/Article/details/gt2icwglkzm.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhengqikj.top/Article/details/gt2figogtkm.html

[J05] 时间加减（加 7 天）
来源：http://dali.chenlongwang.top/Article/details/gt2rmtsudwa.html

Py:   now + timedelta(days=7)
来源：http://dali.iojbl.cn/Article/details/gt2qxxsmkyi.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.316326.xyz/Article/details/gt2jlgvqwun.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.iojbl.cn/Article/details/gt2peaokpds.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xziqi.cn/Article/details/gt2jvecvmvh.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.316326.xyz/Article/details/gt2taholjte.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.xziqi.cn/Article/details/gt2qudbvppp.html

Ruby: Time.now + 7 * 86400
来源：http://dali.chenzaomai.com/Article/details/gt2hvjmuuwj.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.cashguo.top/Article/details/gt2ahfpzxtt.html

[J06] 计算两时间之差
来源：http://dali.svipenyu.cn/Article/details/gt2uheexdan.html

Py:   (end - start).total_seconds()
来源：http://dali.ehwqpu.com/Article/details/gt2xmivjhdy.html

PHP:  $end->diff($start)->days;
来源：http://dali.daxiang520.top/Article/details/gt2owoewxri.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.kuanghao11.cn/Article/details/gt2sltoxbvd.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhiwuduotai.top/Article/details/gt2jcddikew.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.chenjidiqi.icu/Article/details/gt2zrbcsyuc.html

Go:   end.Sub(start).Hours()
来源：http://dali.c1oappe.top/Article/details/gt2jycreuqp.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yvedp.cn/Article/details/gt2vawebrov.html

C#:   (end - start).TotalSeconds
来源：http://dali.jqgufenzy.top/Article/details/gt2xuxexpyz.html

[J07] 比较两个日期
来源：http://dali.zhengqikj.top/Article/details/gt2gpjxrtzu.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.xuetiantiany.cn/Article/details/gt2sqyvpzri.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.aizwys.cn/Article/details/gt2wgrrhlkp.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jinqigufen.top/Article/details/gt2egzmzrgh.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.xuetiantiany.cn/Article/details/gt2ghkicjaa.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.mhx1999.top/Article/details/gt2xxqncmai.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.shuidangran.top/Article/details/gt2ygcszlcc.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.xuetiantiany.cn/Article/details/gt2sqzgeytp.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.guannengcc.top/Article/details/gt2owsjvngk.html

[J08] 提取年月日与星期
来源：http://dali.vqdsnc.cn/Article/details/gt2vlpwruxn.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.snrcjt.cn/Article/details/gt2xkgaeyon.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.sufxvd.cn/Article/details/gt2jnglkftj.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.hywenlv.cn/Article/details/gt2lvexkatl.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yueranfly.top/Article/details/gt2pmilfoap.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.tianlin.xyz/Article/details/gt2cncgrmoz.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.tianlin.xyz/Article/details/gt2yhqnggch.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.hnqzz.top/Article/details/gt2npwyqznu.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.0kj1m.cn/Article/details/gt2onvelite.html

[J09] 时区处理
来源：http://dali.ppjwa.cn/Article/details/gt2xpbubepw.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.cashguo.top/Article/details/gt2vkznavym.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.cheryme.top/Article/details/gt2kpoqktpo.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bexxwras.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.dianchejie.cn/Article/details/gt2ydygsieg.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.pengpengdd.cyou/Article/details/gt2leywmuub.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.xylfe.cn/Article/details/gt2lpktfkkl.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yuanzhike.top/Article/details/gt2ltrwpqww.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.xinyue.icu/Article/details/gt2njblggls.html

[J10] 取今天 / 本月第一天
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cnytpmmu.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.xziqi.cn/Article/details/gt2abheifnw.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.bjfxy.top/Article/details/gt2znexdjwy.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.cheryme.top/Article/details/gt2uaevljmv.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.hywenlv.cn/Article/details/gt2aqvbuinp.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.gotoacloud.top/Article/details/gt2jtkfbigi.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.xuanzx.com/Article/details/gt2ishoxikh.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.bjfxy.top/Article/details/gt2zcbbimjn.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.sysykeji.top/Article/details/gt2nvhgwptx.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2ezzqpexn.html

K. JSON 与序列化
来源：http://dali.hnqzz.top/Article/details/gt2eonfawpn.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2awyndlkl.html

[K01] 对象转 JSON 字符串
来源：http://dali.guannengcc.top/Article/details/gt2gebezmdl.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qsweidzx.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.guowangkeji.top/Article/details/gt2qnmyxfop.html

JS:   JSON.stringify(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2inkhafvp.html

TS:   JSON.stringify(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dzjtvotn.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.hysaishi.cn/Article/details/gt2ylcuytlj.html

Go:   json.Marshal(obj)
来源：http://dali.tian-w.cn/Article/details/gt2xqtbblzx.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.chenlongwang.top/Article/details/gt2bhhnuwpu.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.andypj.xyz/Article/details/gt2dcyivirr.html

[K02] JSON 字符串转对象
来源：http://dali.chenjidiqi.icu/Article/details/gt2onlfnejb.html

Py:   json.loads(s)
来源：http://dali.jianghu66.top/Article/details/gt2xogksikm.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jqgfzy.top/Article/details/gt2mpgrapqi.html

JS:   JSON.parse(s)
来源：http://dali.sysykeji.top/Article/details/gt2zjeoawil.html

TS:   JSON.parse(s)
来源：http://dali.havefunace.top/Article/details/gt2ptuhykuh.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.0kj1m.cn/Article/details/gt2elesrunl.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.dianchejie.cn/Article/details/gt2thvkkaor.html

Ruby: JSON.parse(s)
来源：http://dali.tianlin.xyz/Article/details/gt2iwbndyrf.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.dashuyun.cn/Article/details/gt2qwvezwhz.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhengqikj.top/Article/details/gt2zolkpdin.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.xylfe.cn/Article/details/gt2wygrcobj.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.ppjwa.cn/Article/details/gt2iuzrduiy.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.feifeiyinyue.top/Article/details/gt2dbpzdmyf.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.sysykeji.top/Article/details/gt2uuibitsk.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gt2gqwriayj.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qqofcpub.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.tanke756.top/Article/details/gt2zficrhkn.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.c1oappe.top/Article/details/gt2nypmlofr.html

[K04] 读取 JSON 文件
来源：http://dali.cdnleiting.top/Article/details/gt2msaofdci.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.cashguo.top/Article/details/gt2ibhcnxbb.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.gzhubu.top/Article/details/gt2hzxlpjhu.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sysykeji.top/Article/details/gt2dyozrcfa.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.chenlongwang.top/Article/details/gt2ukxhslpc.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.guannengcc.top/Article/details/gt2pqwnhhtr.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zycfv.cn/Article/details/gt2partyzyn.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.ehwqpu.com/Article/details/gt2dekexwkg.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.haohaochexian.top/Article/details/gt2rdkwnpdr.html

[K05] 深拷贝对象
来源：http://dali.dashuyun.cn/Article/details/gt2lhvehndx.html

Py:   copy.deepcopy(obj)
来源：http://dali.shuidangran.top/Article/details/gt2qwsxtmov.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yueranfly.top/Article/details/gt2twdjqxzp.html

JS:   structuredClone(obj)
来源：http://dali.kuanghao11.cn/Article/details/gt2kysoirwh.html

TS:   structuredClone(obj)
来源：http://dali.haohaochexian.top/Article/details/gt2mfmwvxck.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.yueranfly.top/Article/details/gt2auprqubp.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.sufxvd.cn/Article/details/gt2idsrvjei.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.xuetiantiany.cn/Article/details/gt2digkvtzv.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.wangshuangyany.cn/Article/details/gt2cgpbgvhp.html

[K06] 解析 URL 查询串
来源：http://dali.sxryk.cn/Article/details/gt2mzjwrbhm.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.sweek.top/Article/details/gt2zlyzmznp.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.pycfn.com/Article/details/gt2ofabszeb.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.meibo888.top/Article/details/gt2kwrmptez.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.chenzaomai.com/Article/details/gt2bngiokbg.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.sufxvd.cn/Article/details/gt2hxnncwlf.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.cucudq.cn/Article/details/gt2zyjysins.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.aibaodan.cn/Article/details/gt2yauaucvi.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.svipenyu.cn/Article/details/gt2ojvisixo.html

[K07] 进制转换
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bpiqvluw.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.sufxvd.cn/Article/details/gt2gwdxmapb.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.meibo888.top/Article/details/gt2jdcnxeeb.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.sweek.top/Article/details/gt2nhqlmywm.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yj20258.top/Article/details/gt2xsuphhvi.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.haohaochexian.top/Article/details/gt2etvovmdq.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.hnxiangtu.top/Article/details/gt2roghzyzw.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yonumen.top/Article/details/gt2pwnsuwrn.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.9152youxi.cn/Article/details/gt2ylueovge.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sfwcpsaz.html

Py:   pickle.dumps(obj)
来源：http://dali.c1oappe.top/Article/details/gt2lduujjxy.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.sxryk.cn/Article/details/gt2pxhtzpql.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.sxryk.cn/Article/details/gt2itlywrhr.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.316326.xyz/Article/details/gt2lzeupshc.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yongpay.top/Article/details/gt2xdaqwwrn.html

Go:   encoding/gob
来源：http://dali.vqdsnc.cn/Article/details/gt2kmqwwsot.html

Ruby: Marshal.dump(obj)
来源：http://dali.sxryk.cn/Article/details/gt2rbaqrhbq.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.vqdsnc.cn/Article/details/gt2jsprmklm.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2itkpwvje.html

L. 网络请求
来源：http://dali.daria6918.cn/Article/details/gt2qmcsnnjn.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2fwyosone.html

[L01] 发送 GET 请求
来源：http://dali.shanyushiyangtech.top/Article/details/gt2evginrcm.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jinqigufen.top/Article/details/gt2ucyrtxap.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.smart0.xyz/Article/details/gt2ynlezptn.html

JS:   await fetch(url)
来源：http://dali.hfpthk.cn/Article/details/gt2dvoyydax.html

TS:   await fetch(url)
来源：http://dali.chenlongwang.top/Article/details/gt2acuucusp.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jinqigfzy.top/Article/details/gt2avpmyopf.html

Go:   resp, err := http.Get(url)
来源：http://dali.guannengcc.top/Article/details/gt2fddqkwfw.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.pycfn.com/Article/details/gt2kmjzzsav.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.nwbrower.top/Article/details/gt2domlvutf.html

[L02] 发送 POST JSON
来源：http://dali.ppjwa.cn/Article/details/gt2todemtbe.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jinqigfzy.top/Article/details/gt2slpxgqyu.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hnnnkipy.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hysaishi.cn/Article/details/gt2mryibzpu.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jyoumei.cn/Article/details/gt2glqewnjc.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.vqdsnc.cn/Article/details/gt2xhcbsibo.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yanxiufei.cn/Article/details/gt2fnxvvoad.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zycfv.cn/Article/details/gt2upmnjhoo.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhoulong.xyz/Article/details/gt2boriumfo.html

[L03] 设置自定义请求头
来源：http://dali.xuanzx.com/Article/details/gt2siesxqkc.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cxwmgsoh.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.chenlongwang.top/Article/details/gt2qefpdtqa.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gzhubu.top/Article/details/gt2epeaerti.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xuetiantiany.cn/Article/details/gt2bdonqrbt.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.ivvv.top/Article/details/gt2erzwltno.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yvedp.cn/Article/details/gt2zwzzvrbu.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhixingplan.top/Article/details/gt2njyqbpov.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.ehwqpu.com/Article/details/gt2ihgxkdqi.html

[L04] 设置超时
来源：http://dali.nwbrower.top/Article/details/gt2akskmtpo.html

Py:   requests.get(url, timeout=5)
来源：http://dali.sysykeji.top/Article/details/gt2hmdsmpzm.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jinqigufen.top/Article/details/gt2tjktnvqz.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ybcxt.top/Article/details/gt2xtpykpbs.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.chenlongwang.top/Article/details/gt2svusupfc.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yvedp.cn/Article/details/gt2iaxltjvr.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.xuetiantiany.cn/Article/details/gt2rrzrksmh.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.ydzc1.top/Article/details/gt2yuklxujv.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.9152youxi.cn/Article/details/gt2eyrrbtyu.html

[L05] 上传文件（multipart）
来源：http://dali.wangshuangyany.cn/Article/details/gt2hpojdfdy.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jinqigfzy.top/Article/details/gt2ojmpkchi.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.cdnleiting.top/Article/details/gt2fmfnmzfu.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.xylfe.cn/Article/details/gt2ppjrhpry.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.gaohongyu789.top/Article/details/gt2sfhgvksk.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.chenlongwang.top/Article/details/gt2awvwofls.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.ybcxt.top/Article/details/gt2kstqgpxf.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.kuanghao11.cn/Article/details/gt2rrhfpala.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.guannengcc.top/Article/details/gt2iijyugjm.html

[L06] 解析响应为 JSON
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jspqwide.html

Py:   resp.json()
来源：http://dali.hysaishi.cn/Article/details/gt2hpiwjlxt.html

PHP:  json_decode($body, true);
来源：http://dali.snrcjt.cn/Article/details/gt2wzsbxoia.html

JS:   await resp.json()
来源：http://dali.redwolf501.top/Article/details/gt2cusovxlv.html

TS:   await resp.json()
来源：http://dali.xuetiantiany.cn/Article/details/gt2mnyimilm.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.chenlongwang.top/Article/details/gt2cgeleqoh.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.andypj.xyz/Article/details/gt2ldzpwrcx.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jlsjyb.cn/Article/details/gt2duozwjbx.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.guannengcc.top/Article/details/gt2uhkikgqg.html

[L07] 处理 HTTP 状态码
来源：http://dali.hnqzz.top/Article/details/gt2hayfdigp.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.aizwys.cn/Article/details/gt2cpdidlun.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.haohaochexian.top/Article/details/gt2dlolisrw.html

JS:   resp.ok;  resp.status
来源：http://dali.daria6918.cn/Article/details/gt2pirdjcne.html

TS:   resp.ok;  resp.status
来源：http://dali.feifeiyinyue.top/Article/details/gt2ygqtzwyg.html

Java: resp.statusCode()
来源：http://dali.hfpthk.cn/Article/details/gt2lpkbfbmt.html

Go:   resp.StatusCode
来源：http://dali.zhoulong.xyz/Article/details/gt2uayaingx.html

Ruby: resp.code.to_i
来源：http://dali.yj202588.top/Article/details/gt2mkpqtutl.html

C#:   (int)resp.StatusCode
来源：http://dali.sweek.top/Article/details/gt2viawlrvx.html

[L08] 并发请求多个地址
来源：http://dali.pengpengdd.cyou/Article/details/gt2ysrdlsrt.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.mhx1999.top/Article/details/gt2fodbysbi.html

PHP:  curl_multi_init() 系列
来源：http://dali.haohaochexian.top/Article/details/gt2xztfocly.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.bjfxy.top/Article/details/gt2ppgtbucy.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.fzhhl.top/Article/details/gt2azopadmz.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.wangdashe.top/Article/details/gt2dharyqwu.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.tian-w.cn/Article/details/gt2ruclvhke.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.kuanghao11.cn/Article/details/gt2fhgoevwx.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.chenzaomai.com/Article/details/gt2ofmtwioe.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2ioovvkkh.html

M. 命令行 / 进程 / 环境
来源：http://dali.sweek.top/Article/details/gt2qnwmjiic.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2txptkdrc.html

[M01] 读取命令行参数
来源：http://dali.ppjwa.cn/Article/details/gt2issjghre.html

Py:   sys.argv[1:]
来源：http://dali.quarkkingdee.top/Article/details/gt2cysdxhtt.html

PHP:  $argv;  $argc;
来源：http://dali.gaohongyu789.top/Article/details/gt2oblthbun.html

JS:   process.argv.slice(2)
来源：http://dali.xuetiantiany.cn/Article/details/gt2bacemhjn.html

TS:   process.argv.slice(2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dnczdlck.html

Java: args 数组（main 方法参数）
来源：http://dali.zdqjudy.top/Article/details/gt2sholtjay.html

Go:   os.Args[1:]
来源：http://dali.havefunace.top/Article/details/gt2wglsgyga.html

Ruby: ARGV
来源：http://dali.snrcjt.cn/Article/details/gt2bkcemjdf.html

C#:   args 数组（Main 方法参数）
来源：http://dali.hnqzz.top/Article/details/gt2pjyxtrfb.html

[M02] 读取环境变量
来源：http://dali.ydzc1.top/Article/details/gt2sifrossc.html

Py:   os.environ.get("HOME")
来源：http://dali.zdqjudy.top/Article/details/gt2onhlnbjy.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.daxiang520.top/Article/details/gt2nseihdys.html

JS:   process.env.HOME
来源：http://dali.chenjidiqi.icu/Article/details/gt2lnbsvwqt.html

TS:   process.env.HOME
来源：http://dali.hnxiangtu.top/Article/details/gt2lzmljhpx.html

Java: System.getenv("HOME")
来源：http://dali.zhiwuduotai.top/Article/details/gt2xgdmcpmg.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.dashuyun.cn/Article/details/gt2ijrdrqtx.html

Ruby: ENV["HOME"]
来源：http://dali.nwbrower.top/Article/details/gt2qdrzrnvi.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.wangdashe.top/Article/details/gt2crimtiss.html

[M03] 执行外部命令
来源：http://dali.ydzc1.top/Article/details/gt2rzlbkjax.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.mhx1999.top/Article/details/gt2broalduw.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pwygbgwa.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.ppjwa.cn/Article/details/gt2oufkqsyt.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.ydzc1.top/Article/details/gt2npsrmqms.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.hnqzz.top/Article/details/gt2ggbnlpck.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2elighplr.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.ehwqpu.com/Article/details/gt2kvrchjvr.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yj20258888.top/Article/details/gt2ozmhtbvk.html

[M04] 获取当前工作目录
来源：http://dali.andypj.xyz/Article/details/gt2iyioqtfo.html

Py:   os.getcwd()
来源：http://dali.dashuyun.cn/Article/details/gt2bwywlnva.html

PHP:  getcwd();
来源：http://dali.sufxvd.cn/Article/details/gt2evxfcmks.html

JS:   process.cwd()
来源：http://dali.aibaodan.cn/Article/details/gt2fbwgtbuu.html


<!-- 参考信息 -->