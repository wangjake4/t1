代发 wailian999

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.gotoacloud.top/Article/details/gtwlpcetxq.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.snrcjt.cn/Article/details/gthpptzhzo.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.wangdashe.top/Article/details/gtpvghlmmk.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.nwbrower.top/Article/details/gtxnhlyndy.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.chenlongwang.top/Article/details/gtqtpbcxna.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlbymqhbo.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.havefunace.top/Article/details/gtfpspbfps.html

[H10] 资源自动释放
来源：http://dali.daria6918.cn/Article/details/gtszvhnphk.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.birdmap.top/Article/details/gtbiogawzb.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhoulong.xyz/Article/details/gthltbtqvq.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.birdmap.top/Article/details/gtaxqpenxn.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsjnpfkmg.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hnqzz.top/Article/details/gtuwpvldlx.html

Go:   defer f.Close()
来源：http://dali.gotoacloud.top/Article/details/gtuvvlshsn.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvwflgfdg.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtjlystkgp.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtftoznzsh.html

I. 正则表达式
来源：http://dali.sxryk.cn/Article/details/gtozqyjqcc.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtpxxzymtg.html

[I01] 判断是否匹配
来源：http://dali.ybcxt.top/Article/details/gtiufibjqx.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.chenzaomai.com/Article/details/gtzetzqcyl.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.redwolf501.top/Article/details/gtgxcluhcv.html

JS:   /\d+/.test(s)
来源：http://dali.0kj1m.cn/Article/details/gtvkerclfw.html

TS:   /\d+/.test(s)
来源：http://dali.cqqwz.cn/Article/details/gtrelxwsks.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yj20258888.top/Article/details/gtlumxuuzu.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtjweqsojb.html

Ruby: s.match?(/\d+/)
来源：http://dali.yanxiufei.cn/Article/details/gtooztbomj.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.ppjwa.cn/Article/details/gtmioqpsof.html

[I02] 提取所有匹配
来源：http://dali.kuanghao11.cn/Article/details/gtxvdxzwbp.html

Py:   re.findall(r"\d+", s)
来源：http://dali.guannengcc.top/Article/details/gtgjucojio.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.cheryme.top/Article/details/gtgcktwock.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.shuidangran.top/Article/details/gtkvkqhulj.html

TS:   s.match(/\d+/g)
来源：http://dali.aibaodan.cn/Article/details/gtpmiwlvou.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.gotoacloud.top/Article/details/gtgpxdpbmv.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.quarkkingdee.top/Article/details/gtupgguetm.html

Ruby: s.scan(/\d+/)
来源：http://dali.sufxvd.cn/Article/details/gtuvyymjdy.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yuanzhike.top/Article/details/gtftqzlcvo.html

[I03] 提取捕获分组
来源：http://dali.xylfe.cn/Article/details/gtkucwjhui.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhiwuduotai.top/Article/details/gtwjsalljr.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.quarkkingdee.top/Article/details/gtaqgfzihy.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.wangdashe.top/Article/details/gtfhxbhgee.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jinqigfzy.top/Article/details/gtmgxbtkvz.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.dianchejie.cn/Article/details/gtlxtltonk.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.daria6918.cn/Article/details/gtnobzuowy.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.ppjwa.cn/Article/details/gtbyjppurk.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.daria6918.cn/Article/details/gtrdesgwqu.html

[I04] 正则替换
来源：http://dali.jinqigfzy.top/Article/details/gtgczxwcxm.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.andypj.xyz/Article/details/gtgdcmzand.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yj20258.top/Article/details/gtlvomlhza.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.tianlin.xyz/Article/details/gtzjfpmtcm.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yanxiufei.cn/Article/details/gtnqhosssi.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.c1oappe.top/Article/details/gtiuittbdw.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.yonumen.top/Article/details/gtcwlvjdvk.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtovgorxyb.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.ppjwa.cn/Article/details/gteldunnqk.html

[I05] 按正则拆分
来源：http://dali.bjfxy.top/Article/details/gtezzyrpnx.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jlsjyb.cn/Article/details/gtjevpgtws.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.havefunace.top/Article/details/gtycvcukiy.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.mhx1999.top/Article/details/gtbnrelqpw.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.iojbl.cn/Article/details/gteutnsruq.html

Java: s.split("\\s*,\\s*")
来源：http://dali.nanxuanxn.top/Article/details/gtemnojhvy.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.hywenlv.cn/Article/details/gtkjlsglim.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.aizwys.cn/Article/details/gtmsfhwvqz.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yvedp.cn/Article/details/gtfiimcxmw.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.bjfxy.top/Article/details/gtvhcnxlln.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.hammf.cn/Article/details/gtylgaubgx.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yonumen.top/Article/details/gtynqeafey.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.daxiang520.top/Article/details/gtfdycodmb.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.feifeiyinyue.top/Article/details/gtnsriywrk.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yuxming.cn/Article/details/gtnzaojcle.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.chenlongwang.top/Article/details/gtkjidgotl.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.cqqwz.cn/Article/details/gtqcdwspsn.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.sxryk.cn/Article/details/gtykeitwot.html

[I07] 忽略大小写与多行模式
来源：http://dali.yj20258888.top/Article/details/gtjondwhlf.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtufzncwgb.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.sxryk.cn/Article/details/gtbsnfxgzp.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.xziqi.cn/Article/details/gtljzouvmi.html

TS:   /error/gim
来源：http://dali.yj20258888.top/Article/details/gtgvxljfmm.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.smart0.xyz/Article/details/gtmvcdphzn.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.tanke756.top/Article/details/gtzpsvdzfl.html

Ruby: s.scan(/error/i)
来源：http://dali.svipenyu.cn/Article/details/gtqzttnigz.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jinqigufen.top/Article/details/gtdailwlkf.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.xziqi.cn/Article/details/gtmgcrkppq.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhiwuduotai.top/Article/details/gtoxshqmbs.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.xylfe.cn/Article/details/gtwabboclx.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ppjwa.cn/Article/details/gtljovvxrc.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhengqikj.top/Article/details/gtpjvybari.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.cheryme.top/Article/details/gtabyjnewx.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmpvurpay.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.tanke756.top/Article/details/gtsppqnebf.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.gaohongyu789.top/Article/details/gtjbtretda.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtororubwg.html

J. 日期与时间
来源：http://dali.yongpay.top/Article/details/gtqloxzbfm.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gturyrwodt.html

[J01] 获取当前时间
来源：http://dali.nanxuanxn.top/Article/details/gtpoptkerq.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.cucudq.cn/Article/details/gtclswxibl.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.chenlongwang.top/Article/details/gtbrlwzajo.html

JS:   new Date();  Date.now()
来源：http://dali.haohaochexian.top/Article/details/gtxgxgibez.html

TS:   new Date();  Date.now()
来源：http://dali.hongshengwenyu.top/Article/details/gtbvrkzged.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.birdmap.top/Article/details/gtkmwrihnl.html

Go:   time.Now()
来源：http://dali.ydzc1.top/Article/details/gtsjkymjqx.html

Ruby: Time.now
来源：http://dali.shzxlz.cn/Article/details/gtjhasbrzl.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.shanyushiyangtech.top/Article/details/gtvqxxuope.html

[J02] 格式化输出
来源：http://dali.zdqjudy.top/Article/details/gtrqdgecje.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hysaishi.cn/Article/details/gtxlmqfkzg.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zdqjudy.top/Article/details/gtzeserbgs.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.hywenlv.cn/Article/details/gtqqqnatvr.html

TS:   d.toISOString()
来源：http://dali.havefunace.top/Article/details/gtpgzhsnvx.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zdqjudy.top/Article/details/gtyodlhjzr.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.316326.xyz/Article/details/gtglmdorip.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.mhx1999.top/Article/details/gthxungfif.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jqgfzy.top/Article/details/gtsebqqtle.html

[J03] 字符串解析为日期
来源：http://dali.xinyue.icu/Article/details/gthrohbrhb.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.chenzaomai.com/Article/details/gtwnnqwprr.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zhixingplan.top/Article/details/gtukteutop.html

JS:   new Date("2024-01-02")
来源：http://dali.sweek.top/Article/details/gtminbpbnt.html

TS:   new Date("2024-01-02")
来源：http://dali.shuidangran.top/Article/details/gtewmltsov.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.ybcxt.top/Article/details/gtvwzhoeyx.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.cucudq.cn/Article/details/gtjhmyrlvl.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.cdnleiting.top/Article/details/gtvwpyhkvt.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zhijiandao.cn/Article/details/gttknihxyo.html

[J04] 时间戳与日期互转
来源：http://dali.jqgufenzy.top/Article/details/gtvfutcrtt.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.tian-w.cn/Article/details/gtvdwjsqel.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.ivvv.top/Article/details/gtlmidhdoo.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.dashuyun.cn/Article/details/gtdayvfqjh.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.hywenlv.cn/Article/details/gtckecjvny.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.xuetiantiany.cn/Article/details/gtkwkvroqe.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.chenjidiqi.icu/Article/details/gtqqkblvnh.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.bjfxy.top/Article/details/gtuafszxng.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yanxiufei.cn/Article/details/gtfypzknkj.html

[J05] 时间加减（加 7 天）
来源：http://dali.jinghuilouyu.cn/Article/details/gtssfmhxti.html

Py:   now + timedelta(days=7)
来源：http://dali.zdqjudy.top/Article/details/gtuyvusmnb.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.pengpengdd.cyou/Article/details/gtbwetcjwt.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hywenlv.cn/Article/details/gtqqtczhlm.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cqqwz.cn/Article/details/gtnxykkssg.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.pycfn.com/Article/details/gtwshsnskp.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yuanzhike.top/Article/details/gtqamydotx.html

Ruby: Time.now + 7 * 86400
来源：http://dali.nanxinkj.top/Article/details/gtwtigosqn.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.sweek.top/Article/details/gtykruphsi.html

[J06] 计算两时间之差
来源：http://dali.jlsjyb.cn/Article/details/gtragsqckf.html

Py:   (end - start).total_seconds()
来源：http://dali.zycfv.cn/Article/details/gtsnvnqdgu.html

PHP:  $end->diff($start)->days;
来源：http://dali.yuxming.cn/Article/details/gtdhrajvsu.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.daria6918.cn/Article/details/gthixlqrcq.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.tian-w.cn/Article/details/gthxhluehf.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.c1oappe.top/Article/details/gtfirikrtt.html

Go:   end.Sub(start).Hours()
来源：http://dali.shzxlz.cn/Article/details/gtycmbgnyd.html

Ruby: end - start                 # 返回秒数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyjlviwvl.html

C#:   (end - start).TotalSeconds
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwfelzmia.html

[J07] 比较两个日期
来源：http://dali.316326.xyz/Article/details/gtzbgxokek.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.mhx1999.top/Article/details/gtynpdukev.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.havefunace.top/Article/details/gtdmjinuzr.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.fzhhl.top/Article/details/gtwiolfwkh.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.birdmap.top/Article/details/gtmrlhkram.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.cdnleiting.top/Article/details/gtsdvgsqpr.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.cashguo.top/Article/details/gtatqzzfig.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jinqigfzy.top/Article/details/gtxktvhybj.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.cheryme.top/Article/details/gtmpevztqc.html

[J08] 提取年月日与星期
来源：http://dali.ivvv.top/Article/details/gtstthvgnn.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuaocatys.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.bjfxy.top/Article/details/gtqosqutdt.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhengqikj.top/Article/details/gttmpkqnyd.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.shangyingyoupin.top/Article/details/gtuuwdgjnr.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.sweek.top/Article/details/gtjczjqweo.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jinghuilouyu.cn/Article/details/gtnkrzdkqs.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.chenzaomai.com/Article/details/gtcddzxyfu.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yangfankeji.com/Article/details/gtcefcctqy.html

[J09] 时区处理
来源：http://dali.mhx1999.top/Article/details/gthbzgrdhc.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.nanxuanxn.top/Article/details/gtumolleik.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.iojbl.cn/Article/details/gtkkwzmdsn.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.quarkkingdee.top/Article/details/gtiqmhzpoz.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xinyue.icu/Article/details/gtxdhlwqty.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.tanke756.top/Article/details/gtdxeofynt.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.shuidangran.top/Article/details/gtuvncxkop.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.shangyingyoupin.top/Article/details/gtkgaahems.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.vqdsnc.cn/Article/details/gtkezcumdz.html

[J10] 取今天 / 本月第一天
来源：http://dali.hongshengwenyu.top/Article/details/gtnpaqcixh.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zdqjudy.top/Article/details/gtganzdkkk.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.zhengqikj.top/Article/details/gtcapwghvc.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.pycfn.com/Article/details/gtcdirmuki.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.ybcxt.top/Article/details/gtfxidmxgy.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.dashuyun.cn/Article/details/gtpckzbbnh.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.hammf.cn/Article/details/gtwelrtorx.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.sxryk.cn/Article/details/gtbztzptqr.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.shuidangran.top/Article/details/gthctbcxta.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtddaxkzkn.html

K. JSON 与序列化
来源：http://dali.birdmap.top/Article/details/gtbqgzkpzc.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtnzhhqtgi.html

[K01] 对象转 JSON 字符串
来源：http://dali.guannengcc.top/Article/details/gtdbhvkuwm.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.cucudq.cn/Article/details/gtdvotmmqm.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmbowcrhx.html

JS:   JSON.stringify(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtwmuypywk.html

TS:   JSON.stringify(obj)
来源：http://dali.dashuyun.cn/Article/details/gtcpyxlqgk.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.redwolf501.top/Article/details/gthgokitgm.html

Go:   json.Marshal(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxjtqribv.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jinghuilouyu.cn/Article/details/gttjhcmoqs.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.mhx1999.top/Article/details/gttarpafxf.html

[K02] JSON 字符串转对象
来源：http://dali.hfpthk.cn/Article/details/gtdojfgefz.html

Py:   json.loads(s)
来源：http://dali.haohaochexian.top/Article/details/gtiicsxjsp.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.fengsongda.top/Article/details/gtnujkthhu.html

JS:   JSON.parse(s)
来源：http://dali.fzhhl.top/Article/details/gtkfyxvqjh.html

TS:   JSON.parse(s)
来源：http://dali.tianlin.xyz/Article/details/gtyvrligjq.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.hongshengwenyu.top/Article/details/gtsprndfmn.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.ybcxt.top/Article/details/gtocmowpzh.html

Ruby: JSON.parse(s)
来源：http://dali.nanxinkj.top/Article/details/gtokigrrri.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtcdjgtdjd.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.xuetiantiany.cn/Article/details/gtkbzazgco.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtakqjgoru.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.sweek.top/Article/details/gtosexqydw.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.jqgufenzy.top/Article/details/gtvqosxfcu.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.xuanzx.com/Article/details/gtdtldklhi.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.meibo888.top/Article/details/gtewizeoaw.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhijiandao.cn/Article/details/gtivmrqxsm.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.vqdsnc.cn/Article/details/gtvcjjcgjp.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.cqqwz.cn/Article/details/gtrjdeygsw.html

[K04] 读取 JSON 文件
来源：http://dali.nanxinkj.top/Article/details/gtchlqxgue.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtifxehyjm.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.hysaishi.cn/Article/details/gtnxuruepo.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhixingplan.top/Article/details/gtxuqrgcpk.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.fengsongda.top/Article/details/gtatiutolp.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.birdmap.top/Article/details/gtpuanvmlz.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.chenzaomai.com/Article/details/gthnrhvxnn.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.quarkkingdee.top/Article/details/gtkufrfudl.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.redwolf501.top/Article/details/gtktuvanru.html

[K05] 深拷贝对象
来源：http://dali.xylfe.cn/Article/details/gtanpmbmuv.html

Py:   copy.deepcopy(obj)
来源：http://dali.zhengqikj.top/Article/details/gtgkolchrr.html

PHP:  unserialize(serialize($obj));
来源：http://dali.mhx1999.top/Article/details/gtivblhnxm.html

JS:   structuredClone(obj)
来源：http://dali.daxiang520.top/Article/details/gtyvdkoacb.html

TS:   structuredClone(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gttmezvylz.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.shanyushiyangtech.top/Article/details/gtqxsrfqyo.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jlsjyb.cn/Article/details/gtznvfhett.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhongyouzk.top/Article/details/gtxqmwqhgo.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yangfankeji.com/Article/details/gthbyvhosv.html

[K06] 解析 URL 查询串
来源：http://dali.ehwqpu.com/Article/details/gtgdrwtxfd.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhixingplan.top/Article/details/gtnyxcwrcl.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjghiifox.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhiwuduotai.top/Article/details/gtkmleticg.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.ydzc1.top/Article/details/gtxicugjgt.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.tianlin.xyz/Article/details/gtqjliuxyz.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.cdnleiting.top/Article/details/gtylwtytti.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.feifeiyinyue.top/Article/details/gtdphwjcna.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yuxming.cn/Article/details/gtpxjmvcix.html

[K07] 进制转换
来源：http://dali.nanxuanxn.top/Article/details/gtouhausej.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.zdqjudy.top/Article/details/gtkfckdgin.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.tanke756.top/Article/details/gtfnfpfool.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.redwolf501.top/Article/details/gtxddcsnkt.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yueranfly.top/Article/details/gtsygkouvk.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.bjfxy.top/Article/details/gtgswzxdmo.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhongyouzk.top/Article/details/gtsplyxswt.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.xuanzx.com/Article/details/gtgdulrqyl.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.aizwys.cn/Article/details/gtggijluzy.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.chenlongwang.top/Article/details/gtvcpuyuas.html

Py:   pickle.dumps(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtpjjecilt.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdjlulipj.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.bjfxy.top/Article/details/gtgdqkblqb.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.chenjidiqi.icu/Article/details/gtllumyups.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yj20258888.top/Article/details/gthxpdeley.html

Go:   encoding/gob
来源：http://dali.hysaishi.cn/Article/details/gthpxlbyiy.html

Ruby: Marshal.dump(obj)
来源：http://dali.tianlin.xyz/Article/details/gtnmycpaix.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.feifeiyinyue.top/Article/details/gtpgmednmy.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtgpepeopf.html

L. 网络请求
来源：http://dali.cqqwz.cn/Article/details/gtviqodora.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtttjybjwm.html

[L01] 发送 GET 请求
来源：http://dali.gaohongyu789.top/Article/details/gtoaafnwsk.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhiwuduotai.top/Article/details/gtpkjolopz.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zdqjudy.top/Article/details/gthudlfved.html

JS:   await fetch(url)
来源：http://dali.jinqigfzy.top/Article/details/gtreonegmy.html

TS:   await fetch(url)
来源：http://dali.hysaishi.cn/Article/details/gtgxirpcli.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.c1oappe.top/Article/details/gtdckkouol.html

Go:   resp, err := http.Get(url)
来源：http://dali.jqgfzy.top/Article/details/gtxmeghqxc.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jlsjyb.cn/Article/details/gtrnhjuwje.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zycfv.cn/Article/details/gtbcmiizdm.html

[L02] 发送 POST JSON
来源：http://dali.aizwys.cn/Article/details/gtpmsfsqdn.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.shangyingyoupin.top/Article/details/gtilvjmyii.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hfpthk.cn/Article/details/gtbwphcysr.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jqgfzy.top/Article/details/gtbsayahzd.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.9152youxi.cn/Article/details/gtghfhowmd.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.xuetiantiany.cn/Article/details/gtllizwvct.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.chenzaomai.com/Article/details/gtzhxoksrn.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.hfpthk.cn/Article/details/gttiqljvcp.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.svipenyu.cn/Article/details/gtdhisoini.html

[L03] 设置自定义请求头
来源：http://dali.fengsongda.top/Article/details/gtwzsscish.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.9152youxi.cn/Article/details/gtpcuabvvu.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.xuetiantiany.cn/Article/details/gtiqdbzacu.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jiagoushi.top/Article/details/gtanyauxaq.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.nwbrower.top/Article/details/gtlqvkjtng.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.hywenlv.cn/Article/details/gtwpnizczw.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.xziqi.cn/Article/details/gteissjgsr.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.shangyingyoupin.top/Article/details/gtmezfoqwh.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.hysaishi.cn/Article/details/gtfhcqmmif.html

[L04] 设置超时
来源：http://dali.c1oappe.top/Article/details/gtygnpecid.html

Py:   requests.get(url, timeout=5)
来源：http://dali.aibaodan.cn/Article/details/gtmoatjbly.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.andypj.xyz/Article/details/gtndzricaw.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.feifeiyinyue.top/Article/details/gthsugdces.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jlsjyb.cn/Article/details/gtoicutucp.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.quarkkingdee.top/Article/details/gtyupzgptw.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.nanxinkj.top/Article/details/gtsmyuwban.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.jyoumei.cn/Article/details/gtceonlxbe.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.smart0.xyz/Article/details/gtqcojijdu.html

[L05] 上传文件（multipart）
来源：http://dali.yuxming.cn/Article/details/gthtwmwjyb.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.wangshuangyany.cn/Article/details/gtlhadcbes.html


<!-- 参考信息 -->