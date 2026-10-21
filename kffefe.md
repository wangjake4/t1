代发 wailian999

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yonumen.top/Article/details/gtclgoldtp.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.cheryme.top/Article/details/gtzwhjnjyz.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yuxming.cn/Article/details/gtzqkmygnw.html

[H10] 资源自动释放
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkrdpyktp.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.tanke756.top/Article/details/gtyatedhyw.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.shzxlz.cn/Article/details/gtcuwuzkdr.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.fzhhl.top/Article/details/gteybiklsk.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.haohaochexian.top/Article/details/gtpktxvkbm.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhiwuduotai.top/Article/details/gtwkqsxoby.html

Go:   defer f.Close()
来源：http://dali.yj20258.top/Article/details/gtmkwhhvis.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.redwolf501.top/Article/details/gtbbgmmldr.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.wangdashe.top/Article/details/gtqeqmflfr.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtpekprdvy.html

I. 正则表达式
来源：http://dali.shuidangran.top/Article/details/gtguiewpno.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtrsmpztgr.html

[I01] 判断是否匹配
来源：http://dali.yueranfly.top/Article/details/gtlvpixhoh.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.haohaochexian.top/Article/details/gtjpxkhtkt.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtdekusuqm.html

JS:   /\d+/.test(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtlakxjtli.html

TS:   /\d+/.test(s)
来源：http://dali.jinqigfzy.top/Article/details/gtaholwohj.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yvedp.cn/Article/details/gtixgkshei.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtsxbmqtpy.html

Ruby: s.match?(/\d+/)
来源：http://dali.shzxlz.cn/Article/details/gtdrduyarc.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.shuidangran.top/Article/details/gtsvydfaav.html

[I02] 提取所有匹配
来源：http://dali.ivvv.top/Article/details/gtslwtikzm.html

Py:   re.findall(r"\d+", s)
来源：http://dali.havefunace.top/Article/details/gtfiekajno.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jinqigfzy.top/Article/details/gtmqicpvwm.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.ivvv.top/Article/details/gttungrqid.html

TS:   s.match(/\d+/g)
来源：http://dali.andypj.xyz/Article/details/gtkxeixily.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.cdnleiting.top/Article/details/gtarwanarc.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.shangyingyoupin.top/Article/details/gtwbpiowuz.html

Ruby: s.scan(/\d+/)
来源：http://dali.9152youxi.cn/Article/details/gtookisgmi.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.meibo888.top/Article/details/gtuzkkckrt.html

[I03] 提取捕获分组
来源：http://dali.hnqzz.top/Article/details/gtzixsiocf.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.c1oappe.top/Article/details/gtdnuefyjs.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jinqigfzy.top/Article/details/gtbxtflotq.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.chenzaomai.com/Article/details/gtrfspyxek.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.gotoacloud.top/Article/details/gtqrtvwyhe.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.chenjidiqi.icu/Article/details/gtoyufwqxu.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.xylfe.cn/Article/details/gtlxecalpf.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.0kj1m.cn/Article/details/gtortnqevj.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zycfv.cn/Article/details/gtseechdux.html

[I04] 正则替换
来源：http://dali.aizwys.cn/Article/details/gtrsvawukg.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.gaohongyu789.top/Article/details/gtczjcukzt.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.gaohongyu789.top/Article/details/gtxgiaitby.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhongyouzk.top/Article/details/gtmpzaikef.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.gotoacloud.top/Article/details/gttrpgksmq.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.cucudq.cn/Article/details/gtqoxgomkz.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.hysaishi.cn/Article/details/gtwctikggr.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.ybcxt.top/Article/details/gtuoiddxrh.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtczwguuha.html

[I05] 按正则拆分
来源：http://dali.havefunace.top/Article/details/gtafvsstpt.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.wangshuangyany.cn/Article/details/gtugucpqec.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.shuidangran.top/Article/details/gtepswrlie.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.bjfxy.top/Article/details/gtbkphkcte.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.havefunace.top/Article/details/gtygqkggza.html

Java: s.split("\\s*,\\s*")
来源：http://dali.gotoacloud.top/Article/details/gtvfuichbo.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.pengpengdd.cyou/Article/details/gtgxjztagf.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yj20258.top/Article/details/gtrnzkugee.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.9152youxi.cn/Article/details/gtorwapseo.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.xuetiantiany.cn/Article/details/gtxdrrppyo.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.havefunace.top/Article/details/gtvsluvfoy.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.tianlin.xyz/Article/details/gtsyddgffn.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.snrcjt.cn/Article/details/gtyakuzsrl.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zycfv.cn/Article/details/gtbwosmist.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvxtzwdbx.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.shanyushiyangtech.top/Article/details/gtuadcaqbj.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.sweek.top/Article/details/gtqlsjtahf.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.aizwys.cn/Article/details/gtwlsiwnwx.html

[I07] 忽略大小写与多行模式
来源：http://dali.316326.xyz/Article/details/gtxfqoktrj.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjlwoeoyl.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.tanke756.top/Article/details/gthpubgblm.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yj202588.top/Article/details/gttwrexmnj.html

TS:   /error/gim
来源：http://dali.chenzaomai.com/Article/details/gtxexnimqi.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yuanzhike.top/Article/details/gtcypgdlby.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zycfv.cn/Article/details/gtzynryzhq.html

Ruby: s.scan(/error/i)
来源：http://dali.jiagoushi.top/Article/details/gtqzxnidhb.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.shanyushiyangtech.top/Article/details/gtsxdjhwtq.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.quarkkingdee.top/Article/details/gtxctqqbxu.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.daxiang520.top/Article/details/gtmnksgiii.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.gogol.net.cn/Article/details/gthwxtiybh.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.chenlongwang.top/Article/details/gtdidlxehb.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.pengpengdd.cyou/Article/details/gtluiwufik.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.ehwqpu.com/Article/details/gtfljrihua.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.gaohongyu789.top/Article/details/gtphhpyvkw.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnebpspes.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.hysaishi.cn/Article/details/gtbjgvflfx.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfhcyeitx.html

J. 日期与时间
来源：http://dali.daxiang520.top/Article/details/gtnxkbgghs.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtroxikpzg.html

[J01] 获取当前时间
来源：http://dali.chenzaomai.com/Article/details/gthsbcaszd.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcucltqva.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhijiandao.cn/Article/details/gttytzfhxs.html

JS:   new Date();  Date.now()
来源：http://dali.hfpthk.cn/Article/details/gtfzonbuxh.html

TS:   new Date();  Date.now()
来源：http://dali.chenzaomai.com/Article/details/gtztwgqfoo.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.hfpthk.cn/Article/details/gtheneammk.html

Go:   time.Now()
来源：http://dali.yongpay.top/Article/details/gtqdwvxdmm.html

Ruby: Time.now
来源：http://dali.shangyingyoupin.top/Article/details/gthnbrtswj.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.sysykeji.top/Article/details/gtlqwrbwjp.html

[J02] 格式化输出
来源：http://dali.hongshengwenyu.top/Article/details/gtyuzoklrd.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ydzc1.top/Article/details/gtwiduvxnn.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.gotoacloud.top/Article/details/gthqnqllfr.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhongyouzk.top/Article/details/gtitjtejpu.html

TS:   d.toISOString()
来源：http://dali.cucudq.cn/Article/details/gtjhtjfnfj.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.xylfe.cn/Article/details/gtyuniyzvz.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yj20258.top/Article/details/gtpowvqwri.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.andypj.xyz/Article/details/gtndvrqjgy.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.fengsongda.top/Article/details/gthkbopkuk.html

[J03] 字符串解析为日期
来源：http://dali.dashuyun.cn/Article/details/gtnwuwrikk.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.cheryme.top/Article/details/gtxpfawxuf.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.c1oappe.top/Article/details/gtappygqnj.html

JS:   new Date("2024-01-02")
来源：http://dali.gzhubu.top/Article/details/gtmhblirrh.html

TS:   new Date("2024-01-02")
来源：http://dali.ybcxt.top/Article/details/gtmpdwxkmq.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.guannengcc.top/Article/details/gtkfaacbmo.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.0kj1m.cn/Article/details/gthbvnewqj.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.sxryk.cn/Article/details/gttfufvcxa.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jyoumei.cn/Article/details/gtazhlusos.html

[J04] 时间戳与日期互转
来源：http://dali.zhijiandao.cn/Article/details/gtfheqcscc.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.fengsongda.top/Article/details/gtjindupug.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.ehwqpu.com/Article/details/gtcnlstcfc.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.cdnleiting.top/Article/details/gtnunemblb.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.kuanghao11.cn/Article/details/gtkthkrlsb.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.xuetiantiany.cn/Article/details/gtjmrwfbvn.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhongyouzk.top/Article/details/gtwuzmghoj.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.c1oappe.top/Article/details/gtsvnwjytx.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.pycfn.com/Article/details/gtvfybalnd.html

[J05] 时间加减（加 7 天）
来源：http://dali.daria6918.cn/Article/details/gtmpcqwgks.html

Py:   now + timedelta(days=7)
来源：http://dali.zhixingplan.top/Article/details/gtqtoleknk.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.quarkkingdee.top/Article/details/gtcsvyghqz.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jqgufenzy.top/Article/details/gtyhkcxgag.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jianghu66.top/Article/details/gtoqsglsuc.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yanxiufei.cn/Article/details/gtxuwfhowl.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.pengpengdd.cyou/Article/details/gtcihxfeao.html

Ruby: Time.now + 7 * 86400
来源：http://dali.sxryk.cn/Article/details/gteppkzeat.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.ppjwa.cn/Article/details/gtlyenyhjd.html

[J06] 计算两时间之差
来源：http://dali.yangfankeji.com/Article/details/gtxtmujgeo.html

Py:   (end - start).total_seconds()
来源：http://dali.xylfe.cn/Article/details/gtniatdtza.html

PHP:  $end->diff($start)->days;
来源：http://dali.c1oappe.top/Article/details/gtwzhcqpvi.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.nanxinkj.top/Article/details/gtqxnriatx.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.0kj1m.cn/Article/details/gtmungobpo.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.redwolf501.top/Article/details/gtzifvvfmd.html

Go:   end.Sub(start).Hours()
来源：http://dali.shzxlz.cn/Article/details/gtsrhqvrks.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zhiwuduotai.top/Article/details/gthhgdufbu.html

C#:   (end - start).TotalSeconds
来源：http://dali.hammf.cn/Article/details/gtryiomkwe.html

[J07] 比较两个日期
来源：http://dali.fengsongda.top/Article/details/gtsljghwgd.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.wangshuangyany.cn/Article/details/gtvpvaoosx.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.9152youxi.cn/Article/details/gtkkbtdsxl.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhongyouzk.top/Article/details/gtrulzqtmt.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.birdmap.top/Article/details/gtdztaccni.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.sysykeji.top/Article/details/gtcuckkhyh.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yj20258.top/Article/details/gtitjnwoan.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.snrcjt.cn/Article/details/gtwrcahked.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.kuanghao11.cn/Article/details/gtlagptlrv.html

[J08] 提取年月日与星期
来源：http://dali.jqgufenzy.top/Article/details/gttdppdzsv.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.gzhubu.top/Article/details/gtheypiaao.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.c1oappe.top/Article/details/gtewfmmvli.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yanxiufei.cn/Article/details/gtylyabzzs.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.birdmap.top/Article/details/gtyqaplnix.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.birdmap.top/Article/details/gtzztphknz.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.316326.xyz/Article/details/gtefktktsy.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.smart0.xyz/Article/details/gtzstevmbo.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.feifeiyinyue.top/Article/details/gthgnhcxwi.html

[J09] 时区处理
来源：http://dali.pycfn.com/Article/details/gttdafgtqb.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhixingplan.top/Article/details/gtjjypvjky.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.sweek.top/Article/details/gtciektsgy.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gogol.net.cn/Article/details/gtsfirvvxx.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ivvv.top/Article/details/gtxoolstpi.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.meibo888.top/Article/details/gtxwaypbjv.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.shangyingyoupin.top/Article/details/gtxwxdleyg.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.gzhubu.top/Article/details/gtzmwlewkz.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.gaohongyu789.top/Article/details/gtvlqenyzg.html

[J10] 取今天 / 本月第一天
来源：http://dali.tanke756.top/Article/details/gtjxagaown.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jinqigufen.top/Article/details/gtvatsgsrk.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.gaohongyu789.top/Article/details/gtzxbrvmca.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.shuidangran.top/Article/details/gtsbrvlqxc.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.bjfxy.top/Article/details/gtajarryfs.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.xinyue.icu/Article/details/gtzlbbnsso.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhixingplan.top/Article/details/gtyyatmsdd.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.xuanzx.com/Article/details/gtnwmyvuth.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.xuetiantiany.cn/Article/details/gtzgbdftxf.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtvumufcmt.html

K. JSON 与序列化
来源：http://dali.zycfv.cn/Article/details/gtmixosskq.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gthaemcfsh.html

[K01] 对象转 JSON 字符串
来源：http://dali.sxryk.cn/Article/details/gtwdmzykan.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.0kj1m.cn/Article/details/gtnflooxyi.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.shangyingyoupin.top/Article/details/gtmwroafkr.html

JS:   JSON.stringify(obj)
来源：http://dali.pycfn.com/Article/details/gthpctanyg.html

TS:   JSON.stringify(obj)
来源：http://dali.chenzaomai.com/Article/details/gtlmzkdtcs.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.daria6918.cn/Article/details/gtxlfmpdxz.html

Go:   json.Marshal(obj)
来源：http://dali.hnxiangtu.top/Article/details/gthgpvxtgs.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhongyouzk.top/Article/details/gtiqwcfasf.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.fzhhl.top/Article/details/gtwlabwcoq.html

[K02] JSON 字符串转对象
来源：http://dali.redwolf501.top/Article/details/gtybmekkuc.html

Py:   json.loads(s)
来源：http://dali.aizwys.cn/Article/details/gtvrrmkbsw.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yongpay.top/Article/details/gtduojarfs.html

JS:   JSON.parse(s)
来源：http://dali.wangdashe.top/Article/details/gtmjbhcjzx.html

TS:   JSON.parse(s)
来源：http://dali.gzhubu.top/Article/details/gtqgffqhrs.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.aizwys.cn/Article/details/gtidhvvwrj.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.havefunace.top/Article/details/gtbnzzvkfj.html

Ruby: JSON.parse(s)
来源：http://dali.316326.xyz/Article/details/gtehznqwhg.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yj20258888.top/Article/details/gtikvtutgf.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.cashguo.top/Article/details/gthbrdquja.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.redwolf501.top/Article/details/gtlksaytok.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.redwolf501.top/Article/details/gtkkmyufjv.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yangfankeji.com/Article/details/gtencevfoc.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.xinyue.icu/Article/details/gtwjusscsl.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jiagoushi.top/Article/details/gtmqszozmt.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jyoumei.cn/Article/details/gtazmanrnt.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.yuxming.cn/Article/details/gtcvltduoo.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.haohaochexian.top/Article/details/gtxgatuntn.html

[K04] 读取 JSON 文件
来源：http://dali.hammf.cn/Article/details/gtiiewlbsp.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.redwolf501.top/Article/details/gtbjwpshrp.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.pengpengdd.cyou/Article/details/gtlcbjzcas.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sufxvd.cn/Article/details/gtfuaeusth.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yj20258.top/Article/details/gtscmwbdjl.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jqgfzy.top/Article/details/gtmjghphjq.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yj20258.top/Article/details/gtzyahbqyp.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhijiandao.cn/Article/details/gtrtrbpamy.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yonumen.top/Article/details/gtvqrbasqt.html

[K05] 深拷贝对象
来源：http://dali.c1oappe.top/Article/details/gtzmwplxcj.html

Py:   copy.deepcopy(obj)
来源：http://dali.gotoacloud.top/Article/details/gtgijqopga.html

PHP:  unserialize(serialize($obj));
来源：http://dali.sweek.top/Article/details/gtxjuxqpmj.html

JS:   structuredClone(obj)
来源：http://dali.yuxming.cn/Article/details/gtnhkloulj.html

TS:   structuredClone(obj)
来源：http://dali.jianghu66.top/Article/details/gturhcmxlx.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.sweek.top/Article/details/gtmlyynxdr.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.shanyushiyangtech.top/Article/details/gtahdztbmi.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.smart0.xyz/Article/details/gtvspmkxjw.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.hnqzz.top/Article/details/gtqeulcfdw.html

[K06] 解析 URL 查询串
来源：http://dali.9152youxi.cn/Article/details/gtpmhctxil.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.aibaodan.cn/Article/details/gtmcaegbbq.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.havefunace.top/Article/details/gtfngbiwam.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.mhx1999.top/Article/details/gtgxetoylx.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zdqjudy.top/Article/details/gtdmtkoeaz.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.xinyue.icu/Article/details/gtztkvkaao.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.daria6918.cn/Article/details/gtbftfdkuz.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.feifeiyinyue.top/Article/details/gtteqymlel.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.guowangkeji.top/Article/details/gtkyjrvddf.html

[K07] 进制转换
来源：http://dali.chenjidiqi.icu/Article/details/gtnrsibabw.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yanxiufei.cn/Article/details/gtyxagnpzr.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.aizwys.cn/Article/details/gtjqksuvam.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.sufxvd.cn/Article/details/gtakiphkgo.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.zhixingplan.top/Article/details/gtlskfepvp.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.meibo888.top/Article/details/gtwvbtlkxl.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yvedp.cn/Article/details/gtfgzetkhh.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.cashguo.top/Article/details/gtlgnozqkc.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhiwuduotai.top/Article/details/gtbeqlyjpq.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.ppjwa.cn/Article/details/gtshqbkkqv.html

Py:   pickle.dumps(obj)
来源：http://dali.zycfv.cn/Article/details/gtugbxhrid.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.mhx1999.top/Article/details/gtiwqtjeas.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jiagoushi.top/Article/details/gtesqxmtmg.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.9152youxi.cn/Article/details/gtbxhxlxnw.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.dianchejie.cn/Article/details/gtdvufsmtv.html

Go:   encoding/gob
来源：http://dali.yangfankeji.com/Article/details/gtpajlopwr.html

Ruby: Marshal.dump(obj)
来源：http://dali.ehwqpu.com/Article/details/gtendzbvds.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqauckmzp.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtbndbfshs.html

L. 网络请求
来源：http://dali.0kj1m.cn/Article/details/gtrsyhetyq.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtvnzomcdk.html

[L01] 发送 GET 请求
来源：http://dali.gzhubu.top/Article/details/gtqhuatwpk.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yonumen.top/Article/details/gtcrkjglsx.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zycfv.cn/Article/details/gtggwyhsrc.html

JS:   await fetch(url)
来源：http://dali.bjfxy.top/Article/details/gtucgynpen.html

TS:   await fetch(url)
来源：http://dali.aizwys.cn/Article/details/gtjztczwyx.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.tian-w.cn/Article/details/gterzgrnhc.html

Go:   resp, err := http.Get(url)
来源：http://dali.zhoulong.xyz/Article/details/gtntjlxewx.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.quarkkingdee.top/Article/details/gtrrlnsmnl.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.hywenlv.cn/Article/details/gtozrzyzrf.html

[L02] 发送 POST JSON
来源：http://dali.cqqwz.cn/Article/details/gtquzyceus.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.sweek.top/Article/details/gtofmogtxp.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhixingplan.top/Article/details/gtevlosxbt.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinqigfzy.top/Article/details/gtlxuidzfn.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shanyushiyangtech.top/Article/details/gtasbwnmvn.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.shanyushiyangtech.top/Article/details/gtgfsnrlsr.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jyoumei.cn/Article/details/gtzyugfgmj.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.sweek.top/Article/details/gtmupjdpwt.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.hnqzz.top/Article/details/gtxncygldh.html

[L03] 设置自定义请求头
来源：http://dali.gzhubu.top/Article/details/gtkwfusacv.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.cheryme.top/Article/details/gtdnozarll.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.guannengcc.top/Article/details/gtlcnyedcb.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.pengpengdd.cyou/Article/details/gtjchhhkkt.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zycfv.cn/Article/details/gtotfgewai.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.hywenlv.cn/Article/details/gtmqjkkauk.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.daxiang520.top/Article/details/gtnfywexma.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhixingplan.top/Article/details/gtcjpkuzmq.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhiwuduotai.top/Article/details/gtoejlavla.html

[L04] 设置超时
来源：http://dali.feifeiyinyue.top/Article/details/gtkdvqywfo.html

Py:   requests.get(url, timeout=5)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtueyejmez.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yongpay.top/Article/details/gtdtiakgzv.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xuetiantiany.cn/Article/details/gtqygortug.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.gotoacloud.top/Article/details/gtryzluxby.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.aizwys.cn/Article/details/gtlunbcnyv.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jinghuilouyu.cn/Article/details/gtskrfpzus.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.shanyushiyangtech.top/Article/details/gtojkcurlz.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.hnxiangtu.top/Article/details/gtcntwfpao.html

[L05] 上传文件（multipart）
来源：http://dali.zdqjudy.top/Article/details/gtoyltiynz.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.shanyushiyangtech.top/Article/details/gtkadajqrg.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.sufxvd.cn/Article/details/gtzcnbthbf.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuoqfwssu.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yangfankeji.com/Article/details/gtazdzspum.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.birdmap.top/Article/details/gtltmpoebt.html


<!-- 参考信息 -->