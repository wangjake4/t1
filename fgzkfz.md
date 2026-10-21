代发 wailian999

Ruby: s.scan(/error/i)
来源：http://dali.316326.xyz/Article/details/gthfnygbni.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.gzhubu.top/Article/details/gtaienunnn.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.ppjwa.cn/Article/details/gtosdkzaow.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.aibaodan.cn/Article/details/gttacfjkbq.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.svipenyu.cn/Article/details/gtgweofkip.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yj20258.top/Article/details/gtvtbakzso.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.mhx1999.top/Article/details/gtnnhanrhf.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yongpay.top/Article/details/gtvolriktd.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.gaohongyu789.top/Article/details/gtfmzqsnej.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zdqjudy.top/Article/details/gtflvnidep.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.nwbrower.top/Article/details/gtlkiruzog.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtgfuersdw.html

J. 日期与时间
来源：http://dali.wangshuangyany.cn/Article/details/gtecsspkpy.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtfpnvlwar.html

[J01] 获取当前时间
来源：http://dali.jinqigufen.top/Article/details/gtjmggtfye.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.meibo888.top/Article/details/gtmwihdczx.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.cqqwz.cn/Article/details/gtbqkrtljq.html

JS:   new Date();  Date.now()
来源：http://dali.gogol.net.cn/Article/details/gtgmztzzrq.html

TS:   new Date();  Date.now()
来源：http://dali.aibaodan.cn/Article/details/gtrfvkmqdm.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxohcbrnc.html

Go:   time.Now()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkqeeicur.html

Ruby: Time.now
来源：http://dali.nanxuanxn.top/Article/details/gtckjgsstv.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.dashuyun.cn/Article/details/gtambjjluj.html

[J02] 格式化输出
来源：http://dali.xylfe.cn/Article/details/gtbwfoiggd.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jiagoushi.top/Article/details/gtpvmzwahg.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtseqjreon.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhengqikj.top/Article/details/gtfqgayjwj.html

TS:   d.toISOString()
来源：http://dali.tianlin.xyz/Article/details/gthixrrjvs.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.gaohongyu789.top/Article/details/gttdvtqdky.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.iojbl.cn/Article/details/gtcpnpmrtf.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxwoajuuh.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.hongshengwenyu.top/Article/details/gtacmshhxz.html

[J03] 字符串解析为日期
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzgafiqyj.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.quarkkingdee.top/Article/details/gtupwzvnvk.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jyoumei.cn/Article/details/gtxtdtnrrx.html

JS:   new Date("2024-01-02")
来源：http://dali.daxiang520.top/Article/details/gtwhacoesa.html

TS:   new Date("2024-01-02")
来源：http://dali.svipenyu.cn/Article/details/gtkyaqvivc.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.daria6918.cn/Article/details/gtvnzilnlt.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.nanxuanxn.top/Article/details/gtrjlhfnja.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.wangdashe.top/Article/details/gtpsiyebrr.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yueranfly.top/Article/details/gtmuyeciru.html

[J04] 时间戳与日期互转
来源：http://dali.jianghu66.top/Article/details/gtdrywnhln.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.gogol.net.cn/Article/details/gtpwjktgmf.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jqgfzy.top/Article/details/gtndliocdz.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yongpay.top/Article/details/gtmqimrrdp.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zhengqikj.top/Article/details/gtlaejzomh.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.tianlin.xyz/Article/details/gtukoepodp.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yueranfly.top/Article/details/gttcmeckvr.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.wangdashe.top/Article/details/gtrrkrgzez.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.gogol.net.cn/Article/details/gtbroqbzxw.html

[J05] 时间加减（加 7 天）
来源：http://dali.havefunace.top/Article/details/gtwcpgfnvh.html

Py:   now + timedelta(days=7)
来源：http://dali.jinqigufen.top/Article/details/gtjgpbgnyo.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsglnaett.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yonumen.top/Article/details/gtbqnhbvft.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cashguo.top/Article/details/gtnpgmagsq.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.wangdashe.top/Article/details/gtuxhztxzf.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.guowangkeji.top/Article/details/gtsibnwpvo.html

Ruby: Time.now + 7 * 86400
来源：http://dali.ybcxt.top/Article/details/gtpgnurtyw.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.hywenlv.cn/Article/details/gtljmefozg.html

[J06] 计算两时间之差
来源：http://dali.cucudq.cn/Article/details/gtuoturtit.html

Py:   (end - start).total_seconds()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpxonzvdr.html

PHP:  $end->diff($start)->days;
来源：http://dali.aibaodan.cn/Article/details/gtzfwiiwez.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jqgufenzy.top/Article/details/gtkmsnsjvg.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yongpay.top/Article/details/gtaljuwtul.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.haohaochexian.top/Article/details/gtabesukpr.html

Go:   end.Sub(start).Hours()
来源：http://dali.zhoulong.xyz/Article/details/gtcpmgdotn.html

Ruby: end - start                 # 返回秒数
来源：http://dali.316326.xyz/Article/details/gtleuismhe.html

C#:   (end - start).TotalSeconds
来源：http://dali.yvedp.cn/Article/details/gtwuiphqjc.html

[J07] 比较两个日期
来源：http://dali.tianlin.xyz/Article/details/gtagpohkrw.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.sysykeji.top/Article/details/gtqhcaebud.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.hywenlv.cn/Article/details/gtlcqgqhsq.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yuxming.cn/Article/details/gtudkurthi.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jyoumei.cn/Article/details/gtemmquxsh.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.yangfankeji.com/Article/details/gtkabfyees.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.quarkkingdee.top/Article/details/gtuwjhihkg.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yonumen.top/Article/details/gtqibtvajm.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.iojbl.cn/Article/details/gttygxnjme.html

[J08] 提取年月日与星期
来源：http://dali.hammf.cn/Article/details/gtabeencen.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.fengsongda.top/Article/details/gtxdhpconl.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yonumen.top/Article/details/gtipxmydrn.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.gotoacloud.top/Article/details/gtazcxmurj.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jinqigfzy.top/Article/details/gtlchiuvcx.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yj20258.top/Article/details/gttdarreso.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.dashuyun.cn/Article/details/gtztaibtvz.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zhijiandao.cn/Article/details/gtbjioxfod.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.aibaodan.cn/Article/details/gtkhgwgaod.html

[J09] 时区处理
来源：http://dali.kuanghao11.cn/Article/details/gtzgdruccz.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.hywenlv.cn/Article/details/gtxbegcdad.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.pycfn.com/Article/details/gtymfwgwvv.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yvedp.cn/Article/details/gtxmwclseb.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.mhx1999.top/Article/details/gtbalqziym.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.sysykeji.top/Article/details/gtroiqetce.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhoulong.xyz/Article/details/gtoyahztsr.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yueranfly.top/Article/details/gttktieipa.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.bjfxy.top/Article/details/gtqfjmvgfo.html

[J10] 取今天 / 本月第一天
来源：http://dali.andypj.xyz/Article/details/gtwvrrytea.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.cashguo.top/Article/details/gtzwsdkcbd.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.shanyushiyangtech.top/Article/details/gtqmwzzike.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.fengsongda.top/Article/details/gtbtwpcrdi.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.cucudq.cn/Article/details/gtdhyxrrhx.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhoulong.xyz/Article/details/gtywkrrlvg.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.shuidangran.top/Article/details/gtvqfuxnap.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yuxming.cn/Article/details/gtkycbnfuc.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.xinyue.icu/Article/details/gtvgdozzpv.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtbdghqljl.html

K. JSON 与序列化
来源：http://dali.chenjidiqi.icu/Article/details/gtlfhfwwjx.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gttvbsgnpw.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhengqikj.top/Article/details/gtmnugnunm.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.iojbl.cn/Article/details/gtarxqsaqa.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.chenlongwang.top/Article/details/gtnprouhwa.html

JS:   JSON.stringify(obj)
来源：http://dali.wangdashe.top/Article/details/gtatbsbadt.html

TS:   JSON.stringify(obj)
来源：http://dali.jyoumei.cn/Article/details/gtgimxosbs.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.dashuyun.cn/Article/details/gtpawvaccg.html

Go:   json.Marshal(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gtaolkxics.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.316326.xyz/Article/details/gtkofzcqky.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.guowangkeji.top/Article/details/gtjmjjprhg.html

[K02] JSON 字符串转对象
来源：http://dali.iojbl.cn/Article/details/gteecwbjrs.html

Py:   json.loads(s)
来源：http://dali.dashuyun.cn/Article/details/gtqmenrybs.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.gzhubu.top/Article/details/gtduekdtdn.html

JS:   JSON.parse(s)
来源：http://dali.yuanzhike.top/Article/details/gtzxatvmvk.html

TS:   JSON.parse(s)
来源：http://dali.yongpay.top/Article/details/gtnhfxidcd.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.nanxinkj.top/Article/details/gthsgjlxih.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jlsjyb.cn/Article/details/gtacnjyrze.html

Ruby: JSON.parse(s)
来源：http://dali.sweek.top/Article/details/gtbxvhjdnj.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.kuanghao11.cn/Article/details/gtvuackira.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.ehwqpu.com/Article/details/gtgmsvnhbg.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.chenjidiqi.icu/Article/details/gtjmkgmyyy.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.bjfxy.top/Article/details/gtbfcatygz.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.redwolf501.top/Article/details/gtmwcahpck.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jinqigufen.top/Article/details/gtjuzgfpbg.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yj20258888.top/Article/details/gtloauruol.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtktnzvzdb.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.fengsongda.top/Article/details/gtrgmzhebl.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuhruusqv.html

[K04] 读取 JSON 文件
来源：http://dali.fzhhl.top/Article/details/gtzcqwrjmv.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jiagoushi.top/Article/details/gtlbqqmsnm.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.pengpengdd.cyou/Article/details/gtlhjgxrwu.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.kuanghao11.cn/Article/details/gtfbxshwfg.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.cheryme.top/Article/details/gtwlsvvebp.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.birdmap.top/Article/details/gtkiohiptc.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.cucudq.cn/Article/details/gtalpjhcxt.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jlsjyb.cn/Article/details/gtolovfcqd.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.tianlin.xyz/Article/details/gtsbmniser.html

[K05] 深拷贝对象
来源：http://dali.kuanghao11.cn/Article/details/gtaykaymvu.html

Py:   copy.deepcopy(obj)
来源：http://dali.hfpthk.cn/Article/details/gtfiwibnfp.html

PHP:  unserialize(serialize($obj));
来源：http://dali.aibaodan.cn/Article/details/gtvqbrvnao.html

JS:   structuredClone(obj)
来源：http://dali.ehwqpu.com/Article/details/gtgirhrwnf.html

TS:   structuredClone(obj)
来源：http://dali.daria6918.cn/Article/details/gtzmelbjqt.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jinghuilouyu.cn/Article/details/gtmuxxxxag.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.daxiang520.top/Article/details/gtuybqtgvz.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.gotoacloud.top/Article/details/gtmknmarez.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yangfankeji.com/Article/details/gtzhatxslp.html

[K06] 解析 URL 查询串
来源：http://dali.316326.xyz/Article/details/gtsrtyxdho.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsevxvdrf.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.chenjidiqi.icu/Article/details/gtcbvkxijd.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.nanxuanxn.top/Article/details/gtuwjbzheh.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.meibo888.top/Article/details/gtsbgjfzwh.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.haohaochexian.top/Article/details/gtezjucruk.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yj20258.top/Article/details/gtokrmxeck.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhiwuduotai.top/Article/details/gtxlvidien.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.xinyue.icu/Article/details/gtuhnalxpk.html

[K07] 进制转换
来源：http://dali.kuanghao11.cn/Article/details/gtaibbxoll.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.ivvv.top/Article/details/gthykdzsbk.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.meibo888.top/Article/details/gtrsxkawes.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhengqikj.top/Article/details/gtbvwhcfba.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.hongshengwenyu.top/Article/details/gtuajgwmuq.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.xylfe.cn/Article/details/gtvkmhkgwk.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.smart0.xyz/Article/details/gtncuzazok.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.xuetiantiany.cn/Article/details/gtwsdatewz.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.pycfn.com/Article/details/gtzzasrgbr.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.cucudq.cn/Article/details/gtcduxhkrf.html

Py:   pickle.dumps(obj)
来源：http://dali.xinyue.icu/Article/details/gtabgfbfhj.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.haohaochexian.top/Article/details/gtvigdnrnn.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yj202588.top/Article/details/gtknpuowcm.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.snrcjt.cn/Article/details/gtstuobqif.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.jlsjyb.cn/Article/details/gteviusffg.html

Go:   encoding/gob
来源：http://dali.dashuyun.cn/Article/details/gthurndhqi.html

Ruby: Marshal.dump(obj)
来源：http://dali.fzhhl.top/Article/details/gtadplnxeb.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.c1oappe.top/Article/details/gtqdjazvyq.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtnjqjrscx.html

L. 网络请求
来源：http://dali.zhaomingkeji.xyz/Article/details/gtigesfbxe.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtqehqaxjw.html

[L01] 发送 GET 请求
来源：http://dali.cqqwz.cn/Article/details/gtrmrhfnns.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.chenjidiqi.icu/Article/details/gtkolmcpxd.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.nwbrower.top/Article/details/gtxrnoconc.html

JS:   await fetch(url)
来源：http://dali.hfpthk.cn/Article/details/gtuafysqaf.html

TS:   await fetch(url)
来源：http://dali.tian-w.cn/Article/details/gtxptgfpwn.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yanxiufei.cn/Article/details/gtdsmkjsqg.html

Go:   resp, err := http.Get(url)
来源：http://dali.hfpthk.cn/Article/details/gtqfdinkkv.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jlsjyb.cn/Article/details/gticgfgkmt.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yangfankeji.com/Article/details/gtnckpltpb.html

[L02] 发送 POST JSON
来源：http://dali.dianchejie.cn/Article/details/gtvhapefum.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.9152youxi.cn/Article/details/gtbsmebgts.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.nanxinkj.top/Article/details/gtoddfoefh.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.havefunace.top/Article/details/gtbzbqqght.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.iojbl.cn/Article/details/gtjbubxkmn.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hammf.cn/Article/details/gtozrxasxt.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.daria6918.cn/Article/details/gttvohmqef.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jinqigfzy.top/Article/details/gtlnjqdijl.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.ybcxt.top/Article/details/gtwysubslp.html

[L03] 设置自定义请求头
来源：http://dali.mhx1999.top/Article/details/gtcfsfptps.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.birdmap.top/Article/details/gtzjdbzkba.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.hammf.cn/Article/details/gtromruvuq.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hnxiangtu.top/Article/details/gtsnujcpgx.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.chenzaomai.com/Article/details/gtzrnhfjgj.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.cheryme.top/Article/details/gtvwnbgoxl.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.ppjwa.cn/Article/details/gtgwgtzimu.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.shzxlz.cn/Article/details/gtkulcygia.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.birdmap.top/Article/details/gtbhejpchv.html

[L04] 设置超时
来源：http://dali.jinqigfzy.top/Article/details/gtbtahorpf.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jlsjyb.cn/Article/details/gtqwzdjenb.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yanxiufei.cn/Article/details/gtcyowhkod.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ivvv.top/Article/details/gtxblnaval.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhoulong.xyz/Article/details/gtufyenzvc.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcufaqiot.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.pycfn.com/Article/details/gtjbrhhmaz.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.svipenyu.cn/Article/details/gtglmrxcdw.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.xinyue.icu/Article/details/gtbkveytri.html

[L05] 上传文件（multipart）
来源：http://dali.fengsongda.top/Article/details/gtpqyurbsj.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.cashguo.top/Article/details/gtpvwhlbcg.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.hammf.cn/Article/details/gtkwabidmb.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.xuetiantiany.cn/Article/details/gtiwyyxmyd.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yueranfly.top/Article/details/gtbziuhznb.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.havefunace.top/Article/details/gtecxgfadu.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.kuanghao11.cn/Article/details/gtbjijlbty.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.xylfe.cn/Article/details/gtgqnyojra.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gtrinfnrvc.html

[L06] 解析响应为 JSON
来源：http://dali.ppjwa.cn/Article/details/gtshbinlbm.html

Py:   resp.json()
来源：http://dali.yuxming.cn/Article/details/gtijvzgdoe.html

PHP:  json_decode($body, true);
来源：http://dali.hnqzz.top/Article/details/gtnsppbfhn.html

JS:   await resp.json()
来源：http://dali.zhoulong.xyz/Article/details/gtwykmsrwc.html

TS:   await resp.json()
来源：http://dali.jqgufenzy.top/Article/details/gtanufsxiz.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.dianchejie.cn/Article/details/gtsgtjkbgl.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yongpay.top/Article/details/gtyjmunhna.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtslccjnxo.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoafnbmdm.html

[L07] 处理 HTTP 状态码
来源：http://dali.yangfankeji.com/Article/details/gtkvgjeqeu.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.xziqi.cn/Article/details/gtvdtugbdy.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.cqqwz.cn/Article/details/gtwpdhfsio.html

JS:   resp.ok;  resp.status
来源：http://dali.xinyue.icu/Article/details/gtzczixhdc.html

TS:   resp.ok;  resp.status
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxlflpbcu.html

Java: resp.statusCode()
来源：http://dali.dianchejie.cn/Article/details/gthhiibrlc.html

Go:   resp.StatusCode
来源：http://dali.jlsjyb.cn/Article/details/gtxzevvxfw.html

Ruby: resp.code.to_i
来源：http://dali.xinyue.icu/Article/details/gtbywsfuyz.html

C#:   (int)resp.StatusCode
来源：http://dali.sweek.top/Article/details/gtxdawlwrz.html

[L08] 并发请求多个地址
来源：http://dali.sysykeji.top/Article/details/gtxahfqqvy.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.guannengcc.top/Article/details/gtfkvfvtrb.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhongyouzk.top/Article/details/gtfcggotrx.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.aizwys.cn/Article/details/gtxqhkvwyi.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yuanzhike.top/Article/details/gtfwuxbezn.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yueranfly.top/Article/details/gtbyihbqgt.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.sysykeji.top/Article/details/gtorpegcxb.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.ppjwa.cn/Article/details/gtwvwdgwwo.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.gotoacloud.top/Article/details/gtknahpzbp.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtdnchjcdy.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwxrumzkc.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtrshybirh.html

[M01] 读取命令行参数
来源：http://dali.cheryme.top/Article/details/gtudcdaaje.html

Py:   sys.argv[1:]
来源：http://dali.ppjwa.cn/Article/details/gtdsviflcp.html

PHP:  $argv;  $argc;
来源：http://dali.fengsongda.top/Article/details/gttidffuwa.html

JS:   process.argv.slice(2)
来源：http://dali.9152youxi.cn/Article/details/gtphyszmbi.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gtqbeqphde.html

Java: args 数组（main 方法参数）
来源：http://dali.c1oappe.top/Article/details/gtgdeadhsm.html

Go:   os.Args[1:]
来源：http://dali.jinghuilouyu.cn/Article/details/gtktmoxvru.html

Ruby: ARGV
来源：http://dali.iojbl.cn/Article/details/gtisclmsym.html

C#:   args 数组（Main 方法参数）
来源：http://dali.daxiang520.top/Article/details/gtbpxfxzfi.html

[M02] 读取环境变量
来源：http://dali.meibo888.top/Article/details/gtumwaryzj.html

Py:   os.environ.get("HOME")
来源：http://dali.hywenlv.cn/Article/details/gtpzebyirq.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.haohaochexian.top/Article/details/gtstvuslsa.html

JS:   process.env.HOME
来源：http://dali.quarkkingdee.top/Article/details/gtbvbxmpcv.html

TS:   process.env.HOME
来源：http://dali.guannengcc.top/Article/details/gtyrcmgcou.html

Java: System.getenv("HOME")
来源：http://dali.yongpay.top/Article/details/gtuhkdhbum.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.feifeiyinyue.top/Article/details/gtbirljxgq.html

Ruby: ENV["HOME"]
来源：http://dali.fengsongda.top/Article/details/gthpnqvprd.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.dashuyun.cn/Article/details/gttwidzlxw.html

[M03] 执行外部命令
来源：http://dali.feifeiyinyue.top/Article/details/gtkyvkwbey.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.sysykeji.top/Article/details/gtnvvzsdji.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtamngggnk.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.birdmap.top/Article/details/gtjrbayqcj.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zdqjudy.top/Article/details/gtxjeafbio.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrxhcydhr.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jinghuilouyu.cn/Article/details/gtnovjtsda.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.wangdashe.top/Article/details/gtuyrsjpic.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhengqikj.top/Article/details/gtsnbafria.html

[M04] 获取当前工作目录
来源：http://dali.zhongyouzk.top/Article/details/gtihfeaqeu.html

Py:   os.getcwd()
来源：http://dali.tian-w.cn/Article/details/gtkesevmyi.html

PHP:  getcwd();
来源：http://dali.xuetiantiany.cn/Article/details/gtfhlwqwpx.html

JS:   process.cwd()
来源：http://dali.pycfn.com/Article/details/gtkpvlbpgi.html

TS:   process.cwd()
来源：http://dali.wangdashe.top/Article/details/gtnrrxntog.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.sysykeji.top/Article/details/gtbkjgcngc.html

Go:   os.Getwd()
来源：http://dali.jyoumei.cn/Article/details/gtwznkxzbq.html

Ruby: Dir.pwd
来源：http://dali.9152youxi.cn/Article/details/gtghhhqsvc.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.meibo888.top/Article/details/gtvlpbtgak.html

[M05] 设置退出码
来源：http://dali.yj202588.top/Article/details/gtgedfiryj.html

Py:   sys.exit(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtskpycowd.html

PHP:  exit(1);
来源：http://dali.sweek.top/Article/details/gtkytilbho.html

JS:   process.exit(1)
来源：http://dali.fzhhl.top/Article/details/gtpqvbxppx.html

TS:   process.exit(1)
来源：http://dali.smart0.xyz/Article/details/gtiztohrth.html

Java: System.exit(1)
来源：http://dali.fengsongda.top/Article/details/gtlfcmvqmp.html

Go:   os.Exit(1)
来源：http://dali.yj202588.top/Article/details/gtwqetpsbz.html


<!-- 参考信息 -->