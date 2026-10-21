代发 wailian999

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.tianlin.xyz/Article/details/gtzjygrifp.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.andypj.xyz/Article/details/gtoirpvdoe.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.hywenlv.cn/Article/details/gtznzpuvti.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.cheryme.top/Article/details/gtuyjfmkse.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhoulong.xyz/Article/details/gtnffyemxc.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.snrcjt.cn/Article/details/gtkgxzeeue.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.cucudq.cn/Article/details/gtqgljfkyp.html

[H10] 资源自动释放
来源：http://dali.sxryk.cn/Article/details/gtuepxqbxy.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.9152youxi.cn/Article/details/gtsmharoru.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.andypj.xyz/Article/details/gtjmacwhwp.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.mhx1999.top/Article/details/gtndlfyvzl.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xylfe.cn/Article/details/gthfeezcth.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yueranfly.top/Article/details/gthupyjqhc.html

Go:   defer f.Close()
来源：http://dali.wangshuangyany.cn/Article/details/gtdvlgttez.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hfpthk.cn/Article/details/gtbsnnncgi.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.havefunace.top/Article/details/gtesovfybl.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtjxolmlbi.html

I. 正则表达式
来源：http://dali.vqdsnc.cn/Article/details/gtdfqhzedu.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtlvmzqjvg.html

[I01] 判断是否匹配
来源：http://dali.yvedp.cn/Article/details/gturjmtkqf.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.cashguo.top/Article/details/gtluejluau.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.9152youxi.cn/Article/details/gtmtektzlp.html

JS:   /\d+/.test(s)
来源：http://dali.smart0.xyz/Article/details/gttengsqmw.html

TS:   /\d+/.test(s)
来源：http://dali.ybcxt.top/Article/details/gttqbqytlw.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jianghu66.top/Article/details/gtmadtlpxz.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yj20258.top/Article/details/gtydjsvmdl.html

Ruby: s.match?(/\d+/)
来源：http://dali.dianchejie.cn/Article/details/gtvhjbkoxr.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jinqigfzy.top/Article/details/gtrrinsqya.html

[I02] 提取所有匹配
来源：http://dali.yongpay.top/Article/details/gtihvpfhco.html

Py:   re.findall(r"\d+", s)
来源：http://dali.dashuyun.cn/Article/details/gtrinqinpc.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.ehwqpu.com/Article/details/gttwpnbjgg.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.meibo888.top/Article/details/gtsnmnaolt.html

TS:   s.match(/\d+/g)
来源：http://dali.bjfxy.top/Article/details/gtfqsrzocj.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.nanxuanxn.top/Article/details/gtokdvttkw.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.pycfn.com/Article/details/gtimoomoof.html

Ruby: s.scan(/\d+/)
来源：http://dali.yuxming.cn/Article/details/gtsrporits.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jiagoushi.top/Article/details/gtxwxmvbah.html

[I03] 提取捕获分组
来源：http://dali.yongpay.top/Article/details/gtyihosutl.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jqgfzy.top/Article/details/gtnvibyyag.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.aizwys.cn/Article/details/gtqusseupz.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.shanyushiyangtech.top/Article/details/gtmpfdsnqy.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yongpay.top/Article/details/gtvksjidrv.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhengqikj.top/Article/details/gtapgtjjsn.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.feifeiyinyue.top/Article/details/gtaxfudect.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.xuanzx.com/Article/details/gtfeztitxo.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yj202588.top/Article/details/gthpuaxlfv.html

[I04] 正则替换
来源：http://dali.zhijiandao.cn/Article/details/gtsnwjsste.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zycfv.cn/Article/details/gtaqisgwjy.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.cdnleiting.top/Article/details/gtjgcjekss.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yangfankeji.com/Article/details/gtkwiblgej.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.sufxvd.cn/Article/details/gtpvejcwjs.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.ydzc1.top/Article/details/gtmsibusci.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.daxiang520.top/Article/details/gtuhelwchc.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.guowangkeji.top/Article/details/gtgqswajzd.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.gogol.net.cn/Article/details/gtartckpsq.html

[I05] 按正则拆分
来源：http://dali.jiagoushi.top/Article/details/gtubzibbyk.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jyoumei.cn/Article/details/gtpfgqaqix.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.dianchejie.cn/Article/details/gtgjiilqlu.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jqgufenzy.top/Article/details/gtqvgzxeym.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfgqgljgz.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yonumen.top/Article/details/gtjnlukxfj.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zdqjudy.top/Article/details/gtpjulzyli.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.wangdashe.top/Article/details/gtwyvwvdox.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.redwolf501.top/Article/details/gtvamhlpdg.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.nwbrower.top/Article/details/gtclstnlxg.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnialmmoh.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.chenlongwang.top/Article/details/gtjryudwqb.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yvedp.cn/Article/details/gtcdqkgefi.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.haohaochexian.top/Article/details/gtyowahkgg.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yvedp.cn/Article/details/gtljeczllc.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jinghuilouyu.cn/Article/details/gtqzraaykz.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.shuidangran.top/Article/details/gtlogxpztv.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.fengsongda.top/Article/details/gtnuibrgnc.html

[I07] 忽略大小写与多行模式
来源：http://dali.yuxming.cn/Article/details/gtijiqvius.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.chenzaomai.com/Article/details/gthsepnmrk.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.haohaochexian.top/Article/details/gtsrmsvcjf.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.9152youxi.cn/Article/details/gtdptjhxgz.html

TS:   /error/gim
来源：http://dali.jqgfzy.top/Article/details/gttyzuzmag.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.fzhhl.top/Article/details/gtundrwzdg.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hfpthk.cn/Article/details/gtqlvnyjgg.html

Ruby: s.scan(/error/i)
来源：http://dali.feifeiyinyue.top/Article/details/gtorvggcor.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhoulong.xyz/Article/details/gtcmlwmoap.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.nanxinkj.top/Article/details/gtndxmdmya.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.hysaishi.cn/Article/details/gtsnyuqdfn.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jlsjyb.cn/Article/details/gtnfhoiayl.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yueranfly.top/Article/details/gtevzkdwtq.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jlsjyb.cn/Article/details/gtsuysaxqp.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.gaohongyu789.top/Article/details/gtnnyyjjkc.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbfgpqpel.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.andypj.xyz/Article/details/gtqdyzkysf.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.gaohongyu789.top/Article/details/gtftutzkaj.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtmuvcbugm.html

J. 日期与时间
来源：http://dali.jinqigfzy.top/Article/details/gtvdxxqtuq.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtbbuyddfa.html

[J01] 获取当前时间
来源：http://dali.sxryk.cn/Article/details/gtecnyjspf.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzndcrxvl.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jianghu66.top/Article/details/gtqxmsyzwn.html

JS:   new Date();  Date.now()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdqevdvpj.html

TS:   new Date();  Date.now()
来源：http://dali.meibo888.top/Article/details/gtfdwntbpn.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.wangdashe.top/Article/details/gtqxmafbfk.html

Go:   time.Now()
来源：http://dali.hnqzz.top/Article/details/gtoavpacqf.html

Ruby: Time.now
来源：http://dali.zdqjudy.top/Article/details/gtsvhgwfhu.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jqgfzy.top/Article/details/gttpuppumd.html

[J02] 格式化输出
来源：http://dali.sweek.top/Article/details/gtgwnqyjwo.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.aibaodan.cn/Article/details/gtkikemkdc.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.guowangkeji.top/Article/details/gtmoskagxg.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.xziqi.cn/Article/details/gtyclxrroe.html

TS:   d.toISOString()
来源：http://dali.mhx1999.top/Article/details/gtccxqsvxx.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yj20258888.top/Article/details/gthubarbeo.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yuxming.cn/Article/details/gtcxxaxmoj.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.dianchejie.cn/Article/details/gthgqhbjia.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhengqikj.top/Article/details/gtwuqlfnib.html

[J03] 字符串解析为日期
来源：http://dali.zdqjudy.top/Article/details/gtjagdqjkq.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.aibaodan.cn/Article/details/gtgfdrzyog.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.dianchejie.cn/Article/details/gtpnfucilh.html

JS:   new Date("2024-01-02")
来源：http://dali.pengpengdd.cyou/Article/details/gtyakoywkn.html

TS:   new Date("2024-01-02")
来源：http://dali.hammf.cn/Article/details/gthucjesji.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.chenjidiqi.icu/Article/details/gtanuvzzau.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yj20258888.top/Article/details/gtapytlihl.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yj20258888.top/Article/details/gthfusfixf.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.ppjwa.cn/Article/details/gtaaqlcewb.html

[J04] 时间戳与日期互转
来源：http://dali.shuidangran.top/Article/details/gthasykikq.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthokvvcwt.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.0kj1m.cn/Article/details/gtanlrpdgz.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.shangyingyoupin.top/Article/details/gtrprttdmc.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yuxming.cn/Article/details/gtsxfontbq.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.dianchejie.cn/Article/details/gtyxqrmgeg.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yuanzhike.top/Article/details/gtnuxrbrgo.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.cashguo.top/Article/details/gtwsgbzftf.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.cashguo.top/Article/details/gtawlqqiqi.html

[J05] 时间加减（加 7 天）
来源：http://dali.jqgfzy.top/Article/details/gtrqdfycpf.html

Py:   now + timedelta(days=7)
来源：http://dali.sysykeji.top/Article/details/gtbglqizbk.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yongpay.top/Article/details/gtctgdzcqx.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.gaohongyu789.top/Article/details/gtkeboleqr.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yuxming.cn/Article/details/gtgsspmvkp.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yj20258888.top/Article/details/gtkldmsikc.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.cucudq.cn/Article/details/gtndklbfsh.html

Ruby: Time.now + 7 * 86400
来源：http://dali.xuanzx.com/Article/details/gtaxahdpub.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.birdmap.top/Article/details/gtigcjbhdg.html

[J06] 计算两时间之差
来源：http://dali.yvedp.cn/Article/details/gtfwwdqbeq.html

Py:   (end - start).total_seconds()
来源：http://dali.gaohongyu789.top/Article/details/gtjdfqvseh.html

PHP:  $end->diff($start)->days;
来源：http://dali.ppjwa.cn/Article/details/gtvgfuvemk.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhaomingkeji.xyz/Article/details/gthyoliatf.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.gzhubu.top/Article/details/gtkoebidxq.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.pengpengdd.cyou/Article/details/gthibhzzuy.html

Go:   end.Sub(start).Hours()
来源：http://dali.birdmap.top/Article/details/gtpiqcrmya.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jianghu66.top/Article/details/gtnnstvluk.html

C#:   (end - start).TotalSeconds
来源：http://dali.fengsongda.top/Article/details/gtgvrgntkg.html

[J07] 比较两个日期
来源：http://dali.yj20258.top/Article/details/gtlzmwturw.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jinqigufen.top/Article/details/gtbcnrgqfi.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtooaaohjn.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhijiandao.cn/Article/details/gtednixjaf.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.birdmap.top/Article/details/gtetlnarfe.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.bjfxy.top/Article/details/gtzjomqjjv.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.havefunace.top/Article/details/gtwebtdkrc.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jqgfzy.top/Article/details/gthnntiqps.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yuanzhike.top/Article/details/gtbqzneyyn.html

[J08] 提取年月日与星期
来源：http://dali.sysykeji.top/Article/details/gteoltvasu.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.jiagoushi.top/Article/details/gtrgqomuhc.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yj20258.top/Article/details/gtkorklhua.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.daria6918.cn/Article/details/gtnmomdmod.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jinghuilouyu.cn/Article/details/gthpxxgrtm.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.gogol.net.cn/Article/details/gtcdxsxkmg.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.shangyingyoupin.top/Article/details/gttwechuks.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.zdqjudy.top/Article/details/gtdsdcawdi.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.ybcxt.top/Article/details/gteaclpahi.html

[J09] 时区处理
来源：http://dali.yvedp.cn/Article/details/gtxraqwtfv.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.redwolf501.top/Article/details/gtmhlpylng.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.dashuyun.cn/Article/details/gtquisbymf.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shzxlz.cn/Article/details/gtnfzpxarx.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmmnjlgvu.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.fzhhl.top/Article/details/gtpvlodkxm.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.redwolf501.top/Article/details/gtioqxexwp.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.ydzc1.top/Article/details/gtkkdxvcky.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.pengpengdd.cyou/Article/details/gtgllrnmgs.html

[J10] 取今天 / 本月第一天
来源：http://dali.aibaodan.cn/Article/details/gtyjjfjmuz.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwzssofqu.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.daria6918.cn/Article/details/gtmnovttzk.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.ydzc1.top/Article/details/gttyrfnyxa.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.gzhubu.top/Article/details/gtutxxqhuw.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.0kj1m.cn/Article/details/gtniumxnrc.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.nanxuanxn.top/Article/details/gtuerihhdj.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.tanke756.top/Article/details/gtexlljbsh.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jqgfzy.top/Article/details/gtaemziypd.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtajgoyhfk.html

K. JSON 与序列化
来源：http://dali.guannengcc.top/Article/details/gtoajxkmvt.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtnoksjrbk.html

[K01] 对象转 JSON 字符串
来源：http://dali.cheryme.top/Article/details/gtlxynqqpj.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.9152youxi.cn/Article/details/gtnkdfqbig.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.hnxiangtu.top/Article/details/gtwjycxxzt.html

JS:   JSON.stringify(obj)
来源：http://dali.birdmap.top/Article/details/gtbrqqxkvf.html

TS:   JSON.stringify(obj)
来源：http://dali.yangfankeji.com/Article/details/gtwzjuicqk.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.cucudq.cn/Article/details/gtdbdyzejt.html

Go:   json.Marshal(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtkzgeawzn.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yvedp.cn/Article/details/gtupotmxvh.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yvedp.cn/Article/details/gtmwptshes.html

[K02] JSON 字符串转对象
来源：http://dali.0kj1m.cn/Article/details/gtjqhrjvpy.html

Py:   json.loads(s)
来源：http://dali.daxiang520.top/Article/details/gttptxcgjs.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.vqdsnc.cn/Article/details/gtusspcctk.html

JS:   JSON.parse(s)
来源：http://dali.daria6918.cn/Article/details/gtwmjfxaua.html

TS:   JSON.parse(s)
来源：http://dali.jqgufenzy.top/Article/details/gtkfuvvbhp.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.daria6918.cn/Article/details/gtxgafsgbw.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.kuanghao11.cn/Article/details/gtzzezeoyo.html

Ruby: JSON.parse(s)
来源：http://dali.yonumen.top/Article/details/gtbblyrxdi.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtfxtfeujk.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.chenjidiqi.icu/Article/details/gtctqzbvuo.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwdbvdels.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.wangdashe.top/Article/details/gttxgwyemh.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.shangyingyoupin.top/Article/details/gtuqwysuei.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.sxryk.cn/Article/details/gtopvvtwkk.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.xuanzx.com/Article/details/gthagsuiem.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.ehwqpu.com/Article/details/gtwoffbaac.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.c1oappe.top/Article/details/gtibspoxod.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.cqqwz.cn/Article/details/gtwnodjvsq.html

[K04] 读取 JSON 文件
来源：http://dali.vqdsnc.cn/Article/details/gtsmowypmy.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhongyouzk.top/Article/details/gtqmlitqct.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.bjfxy.top/Article/details/gtyozkpzkz.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.shzxlz.cn/Article/details/gtmlknudld.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gttifveclu.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.smart0.xyz/Article/details/gterrjzhpv.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.cqqwz.cn/Article/details/gtblynnkvw.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.fengsongda.top/Article/details/gtdwzppogd.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.kuanghao11.cn/Article/details/gtewccxjwl.html

[K05] 深拷贝对象
来源：http://dali.hysaishi.cn/Article/details/gtxasbrbvs.html

Py:   copy.deepcopy(obj)
来源：http://dali.fzhhl.top/Article/details/gtsxpuzlas.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yueranfly.top/Article/details/gtrkrxmdnx.html

JS:   structuredClone(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtxyinotas.html

TS:   structuredClone(obj)
来源：http://dali.sxryk.cn/Article/details/gtlkqzfznd.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.nanxuanxn.top/Article/details/gtyqveluge.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.ehwqpu.com/Article/details/gtdgfqvhma.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.meibo888.top/Article/details/gtocrjkyuc.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zycfv.cn/Article/details/gtdjecvdus.html

[K06] 解析 URL 查询串
来源：http://dali.aibaodan.cn/Article/details/gtkvteevub.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.xziqi.cn/Article/details/gtxalgpnaa.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgdwgvstd.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.wangdashe.top/Article/details/gttrevavrg.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hongshengwenyu.top/Article/details/gtmlecavwt.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.guannengcc.top/Article/details/gtndotcxey.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.xinyue.icu/Article/details/gtynwjquwd.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yvedp.cn/Article/details/gtwwkclxdr.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.sxryk.cn/Article/details/gtxmvndqvz.html

[K07] 进制转换
来源：http://dali.tian-w.cn/Article/details/gthdxrsgsf.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.sweek.top/Article/details/gthhroqswz.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.jqgufenzy.top/Article/details/gtkdybiwxl.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhaomingkeji.xyz/Article/details/gthmvvdrko.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.ybcxt.top/Article/details/gtpusxqhhq.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.vqdsnc.cn/Article/details/gtdmmjnzol.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.c1oappe.top/Article/details/gtfdtrzfli.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.aibaodan.cn/Article/details/gtqteitrlm.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.tianlin.xyz/Article/details/gtqxidmnyc.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yj20258888.top/Article/details/gtkcynuueg.html

Py:   pickle.dumps(obj)
来源：http://dali.yj20258.top/Article/details/gtndaqqwvs.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.gotoacloud.top/Article/details/gtwwllseve.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yongpay.top/Article/details/gtfdtxgfyk.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.0kj1m.cn/Article/details/gtisgfmcea.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.ybcxt.top/Article/details/gtmbxoyake.html

Go:   encoding/gob
来源：http://dali.zhixingplan.top/Article/details/gtseunywxi.html

Ruby: Marshal.dump(obj)
来源：http://dali.tianlin.xyz/Article/details/gtedlcrfao.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.aibaodan.cn/Article/details/gtqoadfuei.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtrmxlhnbp.html

L. 网络请求
来源：http://dali.sweek.top/Article/details/gtbgnstlkg.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtgfwgeqjl.html

[L01] 发送 GET 请求
来源：http://dali.wangshuangyany.cn/Article/details/gteoqjoipz.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.9152youxi.cn/Article/details/gtneaxeciz.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.gotoacloud.top/Article/details/gtulkdtjqk.html

JS:   await fetch(url)
来源：http://dali.pycfn.com/Article/details/gtdyahsvlj.html

TS:   await fetch(url)
来源：http://dali.havefunace.top/Article/details/gtuvxcywus.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.yvedp.cn/Article/details/gtdvhwanar.html

Go:   resp, err := http.Get(url)
来源：http://dali.0kj1m.cn/Article/details/gtcfjpobax.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.c1oappe.top/Article/details/gthzxbdyke.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.xziqi.cn/Article/details/gtpajmivsh.html

[L02] 发送 POST JSON
来源：http://dali.yangfankeji.com/Article/details/gtozkczgwe.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.fzhhl.top/Article/details/gttzgnfgoi.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.nanxinkj.top/Article/details/gthqywxgjv.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.bjfxy.top/Article/details/gtweugwthl.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.dashuyun.cn/Article/details/gtqpoqwfsr.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zycfv.cn/Article/details/gtkjgmqfgb.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtecfiypos.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgylspiwz.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.ivvv.top/Article/details/gtknzklhfm.html

[L03] 设置自定义请求头
来源：http://dali.jianghu66.top/Article/details/gtukxftftn.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yj20258.top/Article/details/gtpalxlzlz.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yangfankeji.com/Article/details/gtyjikengv.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.feifeiyinyue.top/Article/details/gteslcriqr.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.fengsongda.top/Article/details/gtaaltcuai.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.bjfxy.top/Article/details/gtecojysow.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.havefunace.top/Article/details/gtrovuxxgw.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.pengpengdd.cyou/Article/details/gtavpdptjl.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.cashguo.top/Article/details/gtofyawldf.html

[L04] 设置超时
来源：http://dali.cdnleiting.top/Article/details/gtmyvvszgr.html

Py:   requests.get(url, timeout=5)
来源：http://dali.dashuyun.cn/Article/details/gtmwgfwgvx.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.ppjwa.cn/Article/details/gtueligqje.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.quarkkingdee.top/Article/details/gtdhripwkd.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xylfe.cn/Article/details/gtcryhlheh.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jqgufenzy.top/Article/details/gtkpezvwkz.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.meibo888.top/Article/details/gttcfnitko.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.smart0.xyz/Article/details/gtcotpoowj.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gttjdkamrk.html

[L05] 上传文件（multipart）
来源：http://dali.hywenlv.cn/Article/details/gtmrhmbvlz.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.9152youxi.cn/Article/details/gttqkphvhc.html


<!-- 参考信息 -->