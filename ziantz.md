代发 wailian999

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.aizwys.cn/Article/details/gtdiyiylej.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhoulong.xyz/Article/details/gtbvoppgtt.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.nanxuanxn.top/Article/details/gtvczefwdg.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.fzhhl.top/Article/details/gtscpfwjfw.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.c1oappe.top/Article/details/gtpgfbmhgy.html

Go:   defer f.Close()
来源：http://dali.feifeiyinyue.top/Article/details/gtygdkfxvy.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.pycfn.com/Article/details/gtkqbmnvxp.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.cdnleiting.top/Article/details/gtavneogbl.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtybwhjhhk.html

I. 正则表达式
来源：http://dali.daria6918.cn/Article/details/gtpogirivn.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtorroadhn.html

[I01] 判断是否匹配
来源：http://dali.zhiwuduotai.top/Article/details/gtlyrbzxuv.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.pycfn.com/Article/details/gtoahqftog.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.hywenlv.cn/Article/details/gttydkutok.html

JS:   /\d+/.test(s)
来源：http://dali.316326.xyz/Article/details/gtkiwsmpsl.html

TS:   /\d+/.test(s)
来源：http://dali.sweek.top/Article/details/gtciytjtbr.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jqgfzy.top/Article/details/gthhowhbha.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yuanzhike.top/Article/details/gtptmqlohu.html

Ruby: s.match?(/\d+/)
来源：http://dali.yj20258.top/Article/details/gtruxlrmnw.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.tianlin.xyz/Article/details/gtsjgrrkrh.html

[I02] 提取所有匹配
来源：http://dali.tianlin.xyz/Article/details/gtnexvkokg.html

Py:   re.findall(r"\d+", s)
来源：http://dali.fengsongda.top/Article/details/gtvscxpqon.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwgtxxegc.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jianghu66.top/Article/details/gthpmljrjr.html

TS:   s.match(/\d+/g)
来源：http://dali.jinqigufen.top/Article/details/gtvmvotmep.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.chenzaomai.com/Article/details/gthocxybyn.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yuxming.cn/Article/details/gtdkfnwljp.html

Ruby: s.scan(/\d+/)
来源：http://dali.tianlin.xyz/Article/details/gtremhxkie.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jlsjyb.cn/Article/details/gtxzlzntdx.html

[I03] 提取捕获分组
来源：http://dali.sweek.top/Article/details/gtiapmadqv.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.aibaodan.cn/Article/details/gtodbwmhul.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.sxryk.cn/Article/details/gtpocfqwlj.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.316326.xyz/Article/details/gtldoarxec.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhoulong.xyz/Article/details/gtutrdvoag.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yvedp.cn/Article/details/gtndozwzya.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.bjfxy.top/Article/details/gtowacnmww.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zhengqikj.top/Article/details/gtsnfoykxl.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.hammf.cn/Article/details/gtvzwrqulo.html

[I04] 正则替换
来源：http://dali.xziqi.cn/Article/details/gttpkjfvty.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.redwolf501.top/Article/details/gtwsitnrsj.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhoulong.xyz/Article/details/gtcnaoelsp.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jianghu66.top/Article/details/gtwwsoaagk.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jinqigfzy.top/Article/details/gtyrbykvhs.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhoulong.xyz/Article/details/gtfgwyuhtv.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.tian-w.cn/Article/details/gtopxhxejy.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zdqjudy.top/Article/details/gtnlfxgvsx.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jianghu66.top/Article/details/gtzzmoqavu.html

[I05] 按正则拆分
来源：http://dali.meibo888.top/Article/details/gtsoicpvlx.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.gzhubu.top/Article/details/gtdkhucbkm.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.hnxiangtu.top/Article/details/gtnasbqwvd.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhengqikj.top/Article/details/gtbennmqhw.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.tianlin.xyz/Article/details/gtbrweccyd.html

Java: s.split("\\s*,\\s*")
来源：http://dali.hnxiangtu.top/Article/details/gtazkrbuva.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.birdmap.top/Article/details/gtgduudsxv.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yangfankeji.com/Article/details/gtiuzecqtz.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.andypj.xyz/Article/details/gtuqymspea.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.ybcxt.top/Article/details/gtwisgwzzc.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zycfv.cn/Article/details/gtteeiszfp.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.c1oappe.top/Article/details/gtivtnbxme.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.nanxuanxn.top/Article/details/gtlstfzync.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yj202588.top/Article/details/gtpppjpxtd.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.shangyingyoupin.top/Article/details/gtfyzizstj.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.chenjidiqi.icu/Article/details/gtgcafhbyd.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jinghuilouyu.cn/Article/details/gtgtdyiufn.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.hammf.cn/Article/details/gtnlireckq.html

[I07] 忽略大小写与多行模式
来源：http://dali.jiagoushi.top/Article/details/gtwxuvisfr.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.xinyue.icu/Article/details/gtawnpffsn.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jinqigufen.top/Article/details/gtxprtqovg.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.feifeiyinyue.top/Article/details/gtczsarwcs.html

TS:   /error/gim
来源：http://dali.jinqigfzy.top/Article/details/gtsafwrete.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.ybcxt.top/Article/details/gtoaeinfit.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.daxiang520.top/Article/details/gtljuithun.html

Ruby: s.scan(/error/i)
来源：http://dali.fengsongda.top/Article/details/gtjxsxyslf.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jqgfzy.top/Article/details/gtkcarpbtp.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.feifeiyinyue.top/Article/details/gtabfhuayr.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.ybcxt.top/Article/details/gturwdumgf.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.andypj.xyz/Article/details/gtuivdmbhh.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkulofzob.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cheryme.top/Article/details/gtlsrhiblm.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.haohaochexian.top/Article/details/gtcmzlruva.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.nanxuanxn.top/Article/details/gtcudxihcm.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jianghu66.top/Article/details/gtpszyljva.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zycfv.cn/Article/details/gtsvdvqdeh.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gttxxfsnsk.html

J. 日期与时间
来源：http://dali.dianchejie.cn/Article/details/gtiieetyfx.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtxlmcgqul.html

[J01] 获取当前时间
来源：http://dali.hammf.cn/Article/details/gthcxvdear.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.gogol.net.cn/Article/details/gtpubfxwoa.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jqgufenzy.top/Article/details/gtiuhcbgfg.html

JS:   new Date();  Date.now()
来源：http://dali.nanxinkj.top/Article/details/gtiowjcudl.html

TS:   new Date();  Date.now()
来源：http://dali.quarkkingdee.top/Article/details/gtoroutapm.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.iojbl.cn/Article/details/gtmcgvyeib.html

Go:   time.Now()
来源：http://dali.hywenlv.cn/Article/details/gtttlxpsjy.html

Ruby: Time.now
来源：http://dali.andypj.xyz/Article/details/gtzusdtjgt.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.cucudq.cn/Article/details/gtnolbsluh.html

[J02] 格式化输出
来源：http://dali.yuxming.cn/Article/details/gtzapkjlcm.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.cqqwz.cn/Article/details/gtwjggqcgd.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.aizwys.cn/Article/details/gtqmcckboy.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.ppjwa.cn/Article/details/gtfzddlcgj.html

TS:   d.toISOString()
来源：http://dali.wangdashe.top/Article/details/gtcxnamfyh.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.shangyingyoupin.top/Article/details/gtcesjgbzy.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.sysykeji.top/Article/details/gtrktfbvxp.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhoulong.xyz/Article/details/gtfvdhoezk.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.mhx1999.top/Article/details/gtcfvwnigd.html

[J03] 字符串解析为日期
来源：http://dali.jinqigufen.top/Article/details/gtdfajkflb.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.aizwys.cn/Article/details/gtxyknygnr.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.chenlongwang.top/Article/details/gtqikqtimy.html

JS:   new Date("2024-01-02")
来源：http://dali.redwolf501.top/Article/details/gtfwtcfvlz.html

TS:   new Date("2024-01-02")
来源：http://dali.nanxinkj.top/Article/details/gtknbwzdzd.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jlsjyb.cn/Article/details/gtftxfdgcj.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.shanyushiyangtech.top/Article/details/gtkfvezwxe.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jinghuilouyu.cn/Article/details/gtjykhzeym.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.chenzaomai.com/Article/details/gtrcsjpfwx.html

[J04] 时间戳与日期互转
来源：http://dali.fengsongda.top/Article/details/gttyudbcum.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.ydzc1.top/Article/details/gtdrstaqca.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.andypj.xyz/Article/details/gtotyzftct.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.wangdashe.top/Article/details/gtushyrelj.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jinqigfzy.top/Article/details/gtqxuvhwhf.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jinqigfzy.top/Article/details/gtqudprqpi.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.shuidangran.top/Article/details/gtjfzswrda.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.aibaodan.cn/Article/details/gtbrchnwtm.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jqgfzy.top/Article/details/gtajkbbgwi.html

[J05] 时间加减（加 7 天）
来源：http://dali.jinqigufen.top/Article/details/gtcjykobdx.html

Py:   now + timedelta(days=7)
来源：http://dali.yuanzhike.top/Article/details/gtfkszcgan.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtosjtedwa.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.quarkkingdee.top/Article/details/gttrzrvcqz.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.bjfxy.top/Article/details/gtbxfhrmav.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xuetiantiany.cn/Article/details/gtgltjhzpv.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yonumen.top/Article/details/gtqktehwsn.html

Ruby: Time.now + 7 * 86400
来源：http://dali.zhiwuduotai.top/Article/details/gtraxmvatq.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yj20258.top/Article/details/gttjyypigv.html

[J06] 计算两时间之差
来源：http://dali.mhx1999.top/Article/details/gtjuoiysec.html

Py:   (end - start).total_seconds()
来源：http://dali.zhixingplan.top/Article/details/gtepaipqdv.html

PHP:  $end->diff($start)->days;
来源：http://dali.tianlin.xyz/Article/details/gtrzskwfcq.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.havefunace.top/Article/details/gtsfvytmzb.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.xuetiantiany.cn/Article/details/gtrlktgbhq.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhengqikj.top/Article/details/gtlepbwlvt.html

Go:   end.Sub(start).Hours()
来源：http://dali.shangyingyoupin.top/Article/details/gtlkvokhul.html

Ruby: end - start                 # 返回秒数
来源：http://dali.gaohongyu789.top/Article/details/gttirjlcwo.html

C#:   (end - start).TotalSeconds
来源：http://dali.shangyingyoupin.top/Article/details/gtzrgpuoqg.html

[J07] 比较两个日期
来源：http://dali.hfpthk.cn/Article/details/gtthcxhcfi.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.tanke756.top/Article/details/gtkgxefqyo.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yongpay.top/Article/details/gtaowtntqk.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.snrcjt.cn/Article/details/gtnmuwdpgo.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.xuanzx.com/Article/details/gttmlbhjjv.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.ybcxt.top/Article/details/gtqglstudk.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.meibo888.top/Article/details/gtkehxipzc.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.316326.xyz/Article/details/gtfuoeuddt.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.chenzaomai.com/Article/details/gtuudogumi.html

[J08] 提取年月日与星期
来源：http://dali.havefunace.top/Article/details/gtyggxpvjo.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.cashguo.top/Article/details/gtwfplzatf.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.gogol.net.cn/Article/details/gthjewpios.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jinqigfzy.top/Article/details/gthgzwkomy.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.andypj.xyz/Article/details/gtlekoeixp.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.cucudq.cn/Article/details/gtzilinjnn.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.c1oappe.top/Article/details/gtutueadjb.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.hnxiangtu.top/Article/details/gtnegittss.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.nanxuanxn.top/Article/details/gtnjgnpxfy.html

[J09] 时区处理
来源：http://dali.ybcxt.top/Article/details/gtetnyvjtr.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsivddimw.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hammf.cn/Article/details/gtiwuhvmzk.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hongshengwenyu.top/Article/details/gtpsdtvdwv.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yuanzhike.top/Article/details/gtghqosikq.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.cqqwz.cn/Article/details/gtucxjncbs.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthmnswffp.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhijiandao.cn/Article/details/gtqlgekwlc.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.birdmap.top/Article/details/gtxqosetzq.html

[J10] 取今天 / 本月第一天
来源：http://dali.jianghu66.top/Article/details/gtdjcwgbne.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.gotoacloud.top/Article/details/gtauhglffp.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.wangshuangyany.cn/Article/details/gtaumtmrzg.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.hongshengwenyu.top/Article/details/gtsxiywerk.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.kuanghao11.cn/Article/details/gtjvwgnfpp.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhoulong.xyz/Article/details/gtprmhqtcl.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yj202588.top/Article/details/gtcukstppy.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.wangshuangyany.cn/Article/details/gtadjvoagd.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.cheryme.top/Article/details/gtururpgfh.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdtwzopnq.html

K. JSON 与序列化
来源：http://dali.9152youxi.cn/Article/details/gtahdpitbj.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtrjkjcecw.html

[K01] 对象转 JSON 字符串
来源：http://dali.xylfe.cn/Article/details/gtnypuyual.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhiwuduotai.top/Article/details/gtabeawlcz.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.ppjwa.cn/Article/details/gtgcnzprdz.html

JS:   JSON.stringify(obj)
来源：http://dali.nwbrower.top/Article/details/gtaiymudct.html

TS:   JSON.stringify(obj)
来源：http://dali.yanxiufei.cn/Article/details/gtraofxthx.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yvedp.cn/Article/details/gtabtmxwnw.html

Go:   json.Marshal(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtyukapcrh.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.daria6918.cn/Article/details/gtqmahyvwf.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yuanzhike.top/Article/details/gtqukrevaf.html

[K02] JSON 字符串转对象
来源：http://dali.yj20258.top/Article/details/gtxthfkauz.html

Py:   json.loads(s)
来源：http://dali.cdnleiting.top/Article/details/gtehopnygi.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.meibo888.top/Article/details/gtlebjtyvh.html

JS:   JSON.parse(s)
来源：http://dali.tian-w.cn/Article/details/gtcajrihic.html

TS:   JSON.parse(s)
来源：http://dali.guowangkeji.top/Article/details/gtindaipbf.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.yanxiufei.cn/Article/details/gteeckhbcq.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.feifeiyinyue.top/Article/details/gtlcwxdhbn.html

Ruby: JSON.parse(s)
来源：http://dali.xinyue.icu/Article/details/gtcxpswcxd.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yuanzhike.top/Article/details/gttbmkwaqa.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jinqigfzy.top/Article/details/gtofymwkhm.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.andypj.xyz/Article/details/gtbpeswylu.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.zhongyouzk.top/Article/details/gtfkkfejsb.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtfxkxmhqj.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtssjjjbkj.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.0kj1m.cn/Article/details/gtozoqczii.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jlsjyb.cn/Article/details/gtcvlzlxhu.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.fzhhl.top/Article/details/gtdaaylksk.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhijiandao.cn/Article/details/gtbqtidyek.html

[K04] 读取 JSON 文件
来源：http://dali.xziqi.cn/Article/details/gtdpmttnni.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.guannengcc.top/Article/details/gtcbtzqbkw.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.c1oappe.top/Article/details/gtjxueyozz.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yangfankeji.com/Article/details/gtgddmqxif.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinqigfzy.top/Article/details/gtqvgrjuyw.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.fengsongda.top/Article/details/gtczhfgvvj.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jlsjyb.cn/Article/details/gtkvxxepxp.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.svipenyu.cn/Article/details/gtswtmcatm.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.hnqzz.top/Article/details/gtjztboces.html

[K05] 深拷贝对象
来源：http://dali.ppjwa.cn/Article/details/gtubzomwof.html

Py:   copy.deepcopy(obj)
来源：http://dali.cdnleiting.top/Article/details/gtqjjzvnfg.html

PHP:  unserialize(serialize($obj));
来源：http://dali.hfpthk.cn/Article/details/gtsdmhmwhy.html

JS:   structuredClone(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtunbfhpon.html

TS:   structuredClone(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtyacrsiyz.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.chenzaomai.com/Article/details/gtsikjjekd.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jlsjyb.cn/Article/details/gtphxxqhpz.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.mhx1999.top/Article/details/gtrezgqvuc.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.gotoacloud.top/Article/details/gtooyiivds.html

[K06] 解析 URL 查询串
来源：http://dali.cdnleiting.top/Article/details/gtafkyxplk.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.xinyue.icu/Article/details/gtrskohscv.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yangfankeji.com/Article/details/gthjkymzhg.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.svipenyu.cn/Article/details/gtujhzuthy.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yueranfly.top/Article/details/gtbaunzpgf.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.cashguo.top/Article/details/gtwriroslv.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.ppjwa.cn/Article/details/gtdzvaiqco.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.hfpthk.cn/Article/details/gtufejzimh.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.hongshengwenyu.top/Article/details/gtgflgtjta.html

[K07] 进制转换
来源：http://dali.hfpthk.cn/Article/details/gtuoacnoua.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.sufxvd.cn/Article/details/gtkvphidfy.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.havefunace.top/Article/details/gtajdjrrdn.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zdqjudy.top/Article/details/gtlkiebhhg.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yuxming.cn/Article/details/gtdabnfirb.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.tianlin.xyz/Article/details/gtibvpoxar.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yvedp.cn/Article/details/gteztmsizk.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.dianchejie.cn/Article/details/gtttteubwr.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.shuidangran.top/Article/details/gtvsisczyq.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.tianlin.xyz/Article/details/gtqnsdmijc.html

Py:   pickle.dumps(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtjtbzijke.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlygemqmx.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.guowangkeji.top/Article/details/gtskwltpsa.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.fengsongda.top/Article/details/gtzqizsacf.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.nanxuanxn.top/Article/details/gtihdlzppj.html

Go:   encoding/gob
来源：http://dali.zhengqikj.top/Article/details/gterprilfa.html

Ruby: Marshal.dump(obj)
来源：http://dali.jlsjyb.cn/Article/details/gtekdrvjuc.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhoulong.xyz/Article/details/gtoslbwiah.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtwpgcwlsd.html

L. 网络请求
来源：http://dali.ivvv.top/Article/details/gtpcvqcfax.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtecqklapu.html

[L01] 发送 GET 请求
来源：http://dali.snrcjt.cn/Article/details/gtrsewljbt.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.gotoacloud.top/Article/details/gtdpyhlayt.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.ppjwa.cn/Article/details/gtpvnyfkxu.html

JS:   await fetch(url)
来源：http://dali.yonumen.top/Article/details/gtjyjpeqlr.html

TS:   await fetch(url)
来源：http://dali.yj20258.top/Article/details/gtqsivmqhe.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhiwuduotai.top/Article/details/gtaysonnbm.html

Go:   resp, err := http.Get(url)
来源：http://dali.shanyushiyangtech.top/Article/details/gtmyvnwyov.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.xinyue.icu/Article/details/gtzfzthgdj.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.yonumen.top/Article/details/gtmqadygmz.html

[L02] 发送 POST JSON
来源：http://dali.hnqzz.top/Article/details/gtqtkfdbvp.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.ppjwa.cn/Article/details/gtigmzzdjy.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.nwbrower.top/Article/details/gtvgsaindj.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ybcxt.top/Article/details/gtelpxjldg.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhixingplan.top/Article/details/gtgxlqszqt.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.xuanzx.com/Article/details/gtebvfgyti.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.dashuyun.cn/Article/details/gtopcwxdur.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.hammf.cn/Article/details/gtibtcncfj.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhiwuduotai.top/Article/details/gtbhjgmmnb.html

[L03] 设置自定义请求头
来源：http://dali.xylfe.cn/Article/details/gtzjckwsww.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.feifeiyinyue.top/Article/details/gtujgvhbrh.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.gotoacloud.top/Article/details/gtmnbjwrxm.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yuanzhike.top/Article/details/gtnzotrstg.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hammf.cn/Article/details/gtnscfulof.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jyoumei.cn/Article/details/gtpqiatuev.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.aibaodan.cn/Article/details/gttofeyjsw.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.nanxinkj.top/Article/details/gtobnbcjwq.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yangfankeji.com/Article/details/gthaosedlo.html

[L04] 设置超时
来源：http://dali.shangyingyoupin.top/Article/details/gtkxmwoxqx.html

Py:   requests.get(url, timeout=5)
来源：http://dali.vqdsnc.cn/Article/details/gtvokuzxpw.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.xziqi.cn/Article/details/gtsucabxhk.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ivvv.top/Article/details/gtwanbinyd.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cdnleiting.top/Article/details/gtljvwfbfx.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yonumen.top/Article/details/gttwgrykgk.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.gotoacloud.top/Article/details/gtzuausqig.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.gotoacloud.top/Article/details/gtylobwxul.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.ehwqpu.com/Article/details/gtfneqbwvl.html

[L05] 上传文件（multipart）
来源：http://dali.sxryk.cn/Article/details/gtdebzajvq.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.sysykeji.top/Article/details/gtaronqrkl.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.havefunace.top/Article/details/gtxjwizmns.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.sxryk.cn/Article/details/gtdwfcfebd.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.ivvv.top/Article/details/gtoqrzpmok.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.cashguo.top/Article/details/gtwwrtqepa.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.nwbrower.top/Article/details/gtzhvkypov.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jyoumei.cn/Article/details/gtqcyxjxyu.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.xinyue.icu/Article/details/gtmkwrmkqw.html

[L06] 解析响应为 JSON
来源：http://dali.chenjidiqi.icu/Article/details/gtunntxqtn.html


<!-- 参考信息 -->