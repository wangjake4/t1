代发 wailian999

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.gotoacloud.top/Article/details/gthpoksjps.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zdqjudy.top/Article/details/gtgglrgvii.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jiagoushi.top/Article/details/gtbgwzizhg.html

[H10] 资源自动释放
来源：http://dali.gzhubu.top/Article/details/gtvksleite.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgsyqwtbo.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.sufxvd.cn/Article/details/gtcibufdei.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhoulong.xyz/Article/details/gturiewffx.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.birdmap.top/Article/details/gtlwhjjgxr.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.ywan-chungtsiang.top/Article/details/gtshwoscfa.html

Go:   defer f.Close()
来源：http://dali.guannengcc.top/Article/details/gtxlnyzpyb.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhongyouzk.top/Article/details/gttususilc.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.svipenyu.cn/Article/details/gttkkngary.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtdiosjuqb.html

I. 正则表达式
来源：http://dali.dashuyun.cn/Article/details/gtdxrnxvse.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtoqbfvhmk.html

[I01] 判断是否匹配
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkrtrpzjf.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtfmyciejo.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.316326.xyz/Article/details/gtchjddlxe.html

JS:   /\d+/.test(s)
来源：http://dali.ybcxt.top/Article/details/gtspqkiesq.html

TS:   /\d+/.test(s)
来源：http://dali.birdmap.top/Article/details/gtxmfwlvxb.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.xuanzx.com/Article/details/gtrnyfhdlc.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtlgxwtjhp.html

Ruby: s.match?(/\d+/)
来源：http://dali.ydzc1.top/Article/details/gtqwrslbfl.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.tianlin.xyz/Article/details/gtiqipysrx.html

[I02] 提取所有匹配
来源：http://dali.c1oappe.top/Article/details/gtejkrjzmb.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yangfankeji.com/Article/details/gtvplzddqg.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.shangyingyoupin.top/Article/details/gtonhwfhyz.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.havefunace.top/Article/details/gtzpgziauy.html

TS:   s.match(/\d+/g)
来源：http://dali.ydzc1.top/Article/details/gtqkpvhsfo.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.shzxlz.cn/Article/details/gtuchzubua.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrzqrxkia.html

Ruby: s.scan(/\d+/)
来源：http://dali.birdmap.top/Article/details/gthqwhlxku.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.hnxiangtu.top/Article/details/gtzrvmjxdx.html

[I03] 提取捕获分组
来源：http://dali.quarkkingdee.top/Article/details/gtdfloprxk.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.kuanghao11.cn/Article/details/gtiiawoyya.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.dianchejie.cn/Article/details/gteljigjqp.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.guannengcc.top/Article/details/gtcniytoue.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.c1oappe.top/Article/details/gtmhkbtook.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zdqjudy.top/Article/details/gtcplqugga.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.hnxiangtu.top/Article/details/gtlzuttrrz.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.gaohongyu789.top/Article/details/gtxlhnqqob.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yangfankeji.com/Article/details/gtxptfshqn.html

[I04] 正则替换
来源：http://dali.xziqi.cn/Article/details/gtwzgkodji.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.xuetiantiany.cn/Article/details/gtcdzlwrjj.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yvedp.cn/Article/details/gttfwauuqa.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yanxiufei.cn/Article/details/gtvszyxlzw.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.cqqwz.cn/Article/details/gtlxshdltn.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.meibo888.top/Article/details/gtpasqkuxd.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.chenzaomai.com/Article/details/gtaexyuksy.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhixingplan.top/Article/details/gtmxycphzk.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yuanzhike.top/Article/details/gtzihmudwp.html

[I05] 按正则拆分
来源：http://dali.sysykeji.top/Article/details/gtsyccgdsa.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.gzhubu.top/Article/details/gthcwwhfkl.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.hongshengwenyu.top/Article/details/gtjpjziycr.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yuxming.cn/Article/details/gtaknjxbuy.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhengqikj.top/Article/details/gthbavcvea.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhijiandao.cn/Article/details/gtssqfvtue.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtfcggveds.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.9152youxi.cn/Article/details/gtxkzctniq.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yangfankeji.com/Article/details/gtgzissxke.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.chenjidiqi.icu/Article/details/gtwljcmtxk.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.kuanghao11.cn/Article/details/gtkgctjjhw.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yanxiufei.cn/Article/details/gttrhymgzg.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.guannengcc.top/Article/details/gtvmitflgv.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.iojbl.cn/Article/details/gtwfxvzxsz.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.fengsongda.top/Article/details/gteqmjdxah.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.hysaishi.cn/Article/details/gtreodhmve.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.shanyushiyangtech.top/Article/details/gthgfforlt.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtajabxuhc.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhixingplan.top/Article/details/gtitrczwjd.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.shuidangran.top/Article/details/gtlkbpuaok.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.9152youxi.cn/Article/details/gthzuhulcq.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.cheryme.top/Article/details/gtbwfvfdwf.html

TS:   /error/gim
来源：http://dali.ivvv.top/Article/details/gtmomoorxi.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yuanzhike.top/Article/details/gtybxdpnqy.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.sufxvd.cn/Article/details/gtfumtsdgm.html

Ruby: s.scan(/error/i)
来源：http://dali.hnqzz.top/Article/details/gtvlkzbddq.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.hnqzz.top/Article/details/gtjkgvszsv.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.nwbrower.top/Article/details/gtyjudbukc.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyvjrugqk.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.hnqzz.top/Article/details/gtkxjmwrkp.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.tanke756.top/Article/details/gtbwcckjfy.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yonumen.top/Article/details/gttrrnefng.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.kuanghao11.cn/Article/details/gtxxtrlseo.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhengqikj.top/Article/details/gtyvhgxwdm.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.xziqi.cn/Article/details/gtponxynri.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.quarkkingdee.top/Article/details/gtqaochczc.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtimnxfmxh.html

J. 日期与时间
来源：http://dali.hnqzz.top/Article/details/gtfdwghdad.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gthkxdjnas.html

[J01] 获取当前时间
来源：http://dali.shuidangran.top/Article/details/gtmjydxnzo.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoddczmss.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.c1oappe.top/Article/details/gtcjmnwjmh.html

JS:   new Date();  Date.now()
来源：http://dali.chenjidiqi.icu/Article/details/gtfvrffeuw.html

TS:   new Date();  Date.now()
来源：http://dali.yangfankeji.com/Article/details/gtmjojauqt.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.cashguo.top/Article/details/gtctkczbva.html

Go:   time.Now()
来源：http://dali.hongshengwenyu.top/Article/details/gtvhjrwsmr.html

Ruby: Time.now
来源：http://dali.daxiang520.top/Article/details/gtklnqkxmg.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.quarkkingdee.top/Article/details/gtvscojyih.html

[J02] 格式化输出
来源：http://dali.svipenyu.cn/Article/details/gtddccyjra.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.bjfxy.top/Article/details/gtbsvdbftu.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.dianchejie.cn/Article/details/gtuxdkprtq.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.hongshengwenyu.top/Article/details/gtfypqzmll.html

TS:   d.toISOString()
来源：http://dali.guannengcc.top/Article/details/gthmbbgrcy.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.meibo888.top/Article/details/gtambbjgjx.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.0kj1m.cn/Article/details/gtksaumygw.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yangfankeji.com/Article/details/gtcwcmciwe.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.feifeiyinyue.top/Article/details/gtofxbtgfs.html

[J03] 字符串解析为日期
来源：http://dali.zhongyouzk.top/Article/details/gtrcvklczh.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.iojbl.cn/Article/details/gtxtgotlvl.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.iojbl.cn/Article/details/gtbjupboes.html

JS:   new Date("2024-01-02")
来源：http://dali.tanke756.top/Article/details/gtasxjhobx.html

TS:   new Date("2024-01-02")
来源：http://dali.iojbl.cn/Article/details/gtnuamcpbn.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hnqzz.top/Article/details/gtotpcuesc.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zhixingplan.top/Article/details/gtrfmjmsda.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.hywenlv.cn/Article/details/gttbyepjzy.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yuanzhike.top/Article/details/gtzynuyjme.html

[J04] 时间戳与日期互转
来源：http://dali.gotoacloud.top/Article/details/gtplaxfyui.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.fengsongda.top/Article/details/gtmpglqdfk.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhiwuduotai.top/Article/details/gtpipurdze.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jinqigufen.top/Article/details/gtgzadbcmj.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.fengsongda.top/Article/details/gtlkhutfsn.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.nwbrower.top/Article/details/gtsaqqsxjp.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yuanzhike.top/Article/details/gtfjvwuten.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.chenzaomai.com/Article/details/gtuwiamcrb.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yonumen.top/Article/details/gtddilosop.html

[J05] 时间加减（加 7 天）
来源：http://dali.ydzc1.top/Article/details/gtzqqgunez.html

Py:   now + timedelta(days=7)
来源：http://dali.jqgfzy.top/Article/details/gthbudmqtp.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.cqqwz.cn/Article/details/gtsloctdzj.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.tanke756.top/Article/details/gtbyzwduvi.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ydzc1.top/Article/details/gtidwzekrs.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xylfe.cn/Article/details/gthwdaxwwa.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.smart0.xyz/Article/details/gtezbhplqf.html

Ruby: Time.now + 7 * 86400
来源：http://dali.mhx1999.top/Article/details/gtktghkilp.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwhesfxqg.html

[J06] 计算两时间之差
来源：http://dali.meibo888.top/Article/details/gtnzwqrgum.html

Py:   (end - start).total_seconds()
来源：http://dali.guowangkeji.top/Article/details/gtphjnhzsv.html

PHP:  $end->diff($start)->days;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbgzbxfuv.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jqgfzy.top/Article/details/gtmpmjxvcv.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.nanxinkj.top/Article/details/gtylqjqbnp.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.andypj.xyz/Article/details/gtjevubmrh.html

Go:   end.Sub(start).Hours()
来源：http://dali.ivvv.top/Article/details/gtxscaqibc.html

Ruby: end - start                 # 返回秒数
来源：http://dali.nanxuanxn.top/Article/details/gtpstgpxwp.html

C#:   (end - start).TotalSeconds
来源：http://dali.zhoulong.xyz/Article/details/gtsgesgkae.html

[J07] 比较两个日期
来源：http://dali.zhixingplan.top/Article/details/gtceucxbqr.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.hammf.cn/Article/details/gtcosyfowy.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.gotoacloud.top/Article/details/gtttfopscb.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.ppjwa.cn/Article/details/gtkefxxemh.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.chenzaomai.com/Article/details/gtdhmrbpwn.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.cucudq.cn/Article/details/gtlozpuouf.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.dashuyun.cn/Article/details/gtqeflkqoj.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.birdmap.top/Article/details/gtloddohqk.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.pengpengdd.cyou/Article/details/gtjqnpuexf.html

[J08] 提取年月日与星期
来源：http://dali.hfpthk.cn/Article/details/gtkljalduh.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.sysykeji.top/Article/details/gtkejehnjy.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.guowangkeji.top/Article/details/gtngwylcce.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.gzhubu.top/Article/details/gtylnzkkpi.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jqgufenzy.top/Article/details/gtfirpkeis.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgywoqayv.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.0kj1m.cn/Article/details/gtaowtkpea.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.gogol.net.cn/Article/details/gtaoldvoiv.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.birdmap.top/Article/details/gtdbqhmxms.html

[J09] 时区处理
来源：http://dali.ehwqpu.com/Article/details/gtbifzpwdx.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.meibo888.top/Article/details/gtzlsenhna.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hysaishi.cn/Article/details/gthideeuae.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.tian-w.cn/Article/details/gtwxfnbmjb.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.daxiang520.top/Article/details/gtsznchudi.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yanxiufei.cn/Article/details/gtohspsvni.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.cdnleiting.top/Article/details/gtixkivfby.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.guowangkeji.top/Article/details/gtbmzhctrd.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.sufxvd.cn/Article/details/gtgjxdzqyc.html

[J10] 取今天 / 本月第一天
来源：http://dali.zdqjudy.top/Article/details/gtcmbqrcam.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.tian-w.cn/Article/details/gtxjeeazqi.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.shanyushiyangtech.top/Article/details/gtaxfckyir.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jlsjyb.cn/Article/details/gtzhfzhwrk.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.daxiang520.top/Article/details/gtmykoswjz.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.gogol.net.cn/Article/details/gtrshqzhnj.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.nanxinkj.top/Article/details/gtdrqfvyar.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.quarkkingdee.top/Article/details/gttthqfivx.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.mhx1999.top/Article/details/gtwypyeohb.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtotzpxbkg.html

K. JSON 与序列化
来源：http://dali.iojbl.cn/Article/details/gtlhgdtvbm.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtekwvtbnl.html

[K01] 对象转 JSON 字符串
来源：http://dali.bjfxy.top/Article/details/gtvaluncev.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.smart0.xyz/Article/details/gtstliffsx.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.hongshengwenyu.top/Article/details/gtrwgtrsaz.html

JS:   JSON.stringify(obj)
来源：http://dali.ppjwa.cn/Article/details/gthfagswcn.html

TS:   JSON.stringify(obj)
来源：http://dali.dianchejie.cn/Article/details/gtmwyidwvq.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.smart0.xyz/Article/details/gtairpeaal.html

Go:   json.Marshal(obj)
来源：http://dali.hnqzz.top/Article/details/gtoebslpjd.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.daria6918.cn/Article/details/gteydozkgs.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.andypj.xyz/Article/details/gtajhdnvjz.html

[K02] JSON 字符串转对象
来源：http://dali.yanxiufei.cn/Article/details/gtiooycxld.html

Py:   json.loads(s)
来源：http://dali.shzxlz.cn/Article/details/gteigwyikl.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yj20258.top/Article/details/gtidfuzmaz.html

JS:   JSON.parse(s)
来源：http://dali.sweek.top/Article/details/gtxwditcdp.html

TS:   JSON.parse(s)
来源：http://dali.yonumen.top/Article/details/gtbhzcpsmm.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.ydzc1.top/Article/details/gtxaxryjwg.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.fengsongda.top/Article/details/gtpcmvmdvz.html

Ruby: JSON.parse(s)
来源：http://dali.hammf.cn/Article/details/gtsnqsiyaj.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.tianlin.xyz/Article/details/gtbefbxyan.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhongyouzk.top/Article/details/gtcfaqujst.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.iojbl.cn/Article/details/gttommciev.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.feifeiyinyue.top/Article/details/gtzspgycbo.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yanxiufei.cn/Article/details/gtgbtwdfhv.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.ybcxt.top/Article/details/gtgcbfzxcn.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jiagoushi.top/Article/details/gtaqdbahrj.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.nanxinkj.top/Article/details/gtuazyevjf.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtvelilzfo.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jinqigfzy.top/Article/details/gtgyeozfnv.html

[K04] 读取 JSON 文件
来源：http://dali.yj20258.top/Article/details/gtbbyzhxis.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.aizwys.cn/Article/details/gttienxzlf.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.havefunace.top/Article/details/gtgkevdzta.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sweek.top/Article/details/gtjdedkqhp.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.andypj.xyz/Article/details/gtysoerazo.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.cdnleiting.top/Article/details/gtgoxldxuh.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.fzhhl.top/Article/details/gtbbqrsbfn.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhengqikj.top/Article/details/gtdeajmzuq.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.chenjidiqi.icu/Article/details/gtxyqvstkt.html

[K05] 深拷贝对象
来源：http://dali.birdmap.top/Article/details/gtbgrpfxcr.html

Py:   copy.deepcopy(obj)
来源：http://dali.cashguo.top/Article/details/gtsrworbyo.html

PHP:  unserialize(serialize($obj));
来源：http://dali.xuetiantiany.cn/Article/details/gtwosscxpo.html

JS:   structuredClone(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtkdsjsioh.html

TS:   structuredClone(obj)
来源：http://dali.ydzc1.top/Article/details/gtwapgayeu.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jianghu66.top/Article/details/gtvbcqchbi.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhongyouzk.top/Article/details/gtjskaeacc.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.dianchejie.cn/Article/details/gtrvrzcwad.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhongyouzk.top/Article/details/gtoamaqlxb.html

[K06] 解析 URL 查询串
来源：http://dali.hywenlv.cn/Article/details/gtszwotcus.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.sxryk.cn/Article/details/gtvdwxpbku.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.smart0.xyz/Article/details/gtteiclgen.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xuanzx.com/Article/details/gtkugxbbue.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.shanyushiyangtech.top/Article/details/gtkmouqpkf.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yongpay.top/Article/details/gtslqyeqjt.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.wangdashe.top/Article/details/gtqbajbzgo.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yvedp.cn/Article/details/gtwpvllgvn.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.xziqi.cn/Article/details/gtavwtkymi.html

[K07] 进制转换
来源：http://dali.zhengqikj.top/Article/details/gtguypfozy.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.cashguo.top/Article/details/gtpsyyfmls.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.xuanzx.com/Article/details/gtttqmemqr.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.nanxuanxn.top/Article/details/gtpepxyimi.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.nanxuanxn.top/Article/details/gtolbajbgm.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.fengsongda.top/Article/details/gtbxrqcstw.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.hfpthk.cn/Article/details/gtpicoagqx.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtipuvzgko.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.tianlin.xyz/Article/details/gtbhovtmuc.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yanxiufei.cn/Article/details/gtinecqqbe.html

Py:   pickle.dumps(obj)
来源：http://dali.hywenlv.cn/Article/details/gtyxyhdfdw.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.svipenyu.cn/Article/details/gtkrjhhucj.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.zhixingplan.top/Article/details/gtihnznjyd.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.hammf.cn/Article/details/gtvkggehdg.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.daxiang520.top/Article/details/gtlzxitchj.html

Go:   encoding/gob
来源：http://dali.ehwqpu.com/Article/details/gtdobjlzjz.html

Ruby: Marshal.dump(obj)
来源：http://dali.sweek.top/Article/details/gtkxfxderg.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.gogol.net.cn/Article/details/gtjoxjxfmd.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtphjgvqog.html

L. 网络请求
来源：http://dali.hnxiangtu.top/Article/details/gtdxsjfhmq.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtimxqlruo.html

[L01] 发送 GET 请求
来源：http://dali.daria6918.cn/Article/details/gtilhlnmpp.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.shuidangran.top/Article/details/gtwvsoirjn.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.mhx1999.top/Article/details/gtbvnghtln.html

JS:   await fetch(url)
来源：http://dali.aizwys.cn/Article/details/gtrdmfyupp.html

TS:   await fetch(url)
来源：http://dali.bjfxy.top/Article/details/gtyudvphwz.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.chenlongwang.top/Article/details/gtqyinbkmm.html

Go:   resp, err := http.Get(url)
来源：http://dali.hysaishi.cn/Article/details/gtvayldbdg.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.tian-w.cn/Article/details/gtnvduihax.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.meibo888.top/Article/details/gtfxhcqfwn.html

[L02] 发送 POST JSON
来源：http://dali.ehwqpu.com/Article/details/gtmloqptar.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.xylfe.cn/Article/details/gtlttgyppz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.snrcjt.cn/Article/details/gtjstvbean.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hywenlv.cn/Article/details/gtkgnsgkzh.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.gotoacloud.top/Article/details/gtbabptuwy.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.snrcjt.cn/Article/details/gtaohmmcpf.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yonumen.top/Article/details/gtzowsvuxo.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.gotoacloud.top/Article/details/gtrhiopjca.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.wangdashe.top/Article/details/gtcaswaqby.html

[L03] 设置自定义请求头
来源：http://dali.zdqjudy.top/Article/details/gttrgqhawy.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zycfv.cn/Article/details/gtetgfeyql.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.c1oappe.top/Article/details/gtoipkyxvm.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.hnxiangtu.top/Article/details/gtlwxlgvvt.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.sufxvd.cn/Article/details/gtqszvhyjh.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbvrvkepm.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.dashuyun.cn/Article/details/gtupptyvlz.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.hongshengwenyu.top/Article/details/gtuuuvbsut.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.gzhubu.top/Article/details/gtvpnwpqft.html

[L04] 设置超时
来源：http://dali.pycfn.com/Article/details/gtrrtrhrsu.html

Py:   requests.get(url, timeout=5)
来源：http://dali.hywenlv.cn/Article/details/gtqiucezsg.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.ivvv.top/Article/details/gtvbqgralt.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ybcxt.top/Article/details/gtuwihqvrh.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yangfankeji.com/Article/details/gtraulpnaz.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhoulong.xyz/Article/details/gtuygnqyhi.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.gaohongyu789.top/Article/details/gtitlatkvp.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.hammf.cn/Article/details/gtxmqixjos.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.aibaodan.cn/Article/details/gtgsdxvxfc.html

[L05] 上传文件（multipart）
来源：http://dali.xziqi.cn/Article/details/gtyqzxcibi.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.9152youxi.cn/Article/details/gtgkghzuln.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.guowangkeji.top/Article/details/gtcbesqkad.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.chenjidiqi.icu/Article/details/gtcdxsgldy.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.sweek.top/Article/details/gtjxkuivez.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.mhx1999.top/Article/details/gtriqwavfb.html


<!-- 参考信息 -->