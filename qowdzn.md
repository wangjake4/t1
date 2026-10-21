代发 wailian999

Ruby: e.message;  e.backtrace
来源：http://dali.hnxiangtu.top/Article/details/gtwldgfnjl.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yuxming.cn/Article/details/gtasbjmufu.html

[H09] 带错误码的异常
来源：http://dali.ivvv.top/Article/details/gtglleiitm.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yj20258.top/Article/details/gtcpmylnkd.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuyettnly.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbstudsnf.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.nwbrower.top/Article/details/gtfanaikks.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.daria6918.cn/Article/details/gtbqaqqfzf.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkumjqlze.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jinqigufen.top/Article/details/gtlliaunyn.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jinqigufen.top/Article/details/gtgaqpkull.html

[H10] 资源自动释放
来源：http://dali.xinyue.icu/Article/details/gtivjhvmcb.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.guannengcc.top/Article/details/gtsktedfii.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqmmqjimi.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.mhx1999.top/Article/details/gtpoujfmhf.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthpbmvhcx.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jianghu66.top/Article/details/gthnwlmdml.html

Go:   defer f.Close()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjtbpgjat.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.guannengcc.top/Article/details/gtkelptlad.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gtdldppxpb.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtybcfcgin.html

I. 正则表达式
来源：http://dali.yj20258.top/Article/details/gtudflwlrw.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gthrqenbpa.html

[I01] 判断是否匹配
来源：http://dali.pycfn.com/Article/details/gtdwastsnz.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.aizwys.cn/Article/details/gtrrwbzwbp.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.cashguo.top/Article/details/gtitpvjjvs.html

JS:   /\d+/.test(s)
来源：http://dali.sufxvd.cn/Article/details/gtjyhzhbuu.html

TS:   /\d+/.test(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvwqhcqfj.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.ivvv.top/Article/details/gtheeayfbh.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yj202588.top/Article/details/gtbvnapzur.html

Ruby: s.match?(/\d+/)
来源：http://dali.feifeiyinyue.top/Article/details/gtjkzclayj.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.nanxuanxn.top/Article/details/gttjilqhzl.html

[I02] 提取所有匹配
来源：http://dali.hammf.cn/Article/details/gtorulaofk.html

Py:   re.findall(r"\d+", s)
来源：http://dali.haohaochexian.top/Article/details/gtwnerzjlo.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.bjfxy.top/Article/details/gtftlhzjzf.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.meibo888.top/Article/details/gtnrccctjw.html

TS:   s.match(/\d+/g)
来源：http://dali.hongshengwenyu.top/Article/details/gtchlhnuha.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.sufxvd.cn/Article/details/gthckjollb.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.hongshengwenyu.top/Article/details/gtbttkqszh.html

Ruby: s.scan(/\d+/)
来源：http://dali.dianchejie.cn/Article/details/gtnmahywzv.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jyoumei.cn/Article/details/gtajunekwj.html

[I03] 提取捕获分组
来源：http://dali.dianchejie.cn/Article/details/gtxqwjsxuy.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhongyouzk.top/Article/details/gtxqzlrdqb.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.ybcxt.top/Article/details/gtbbkkihtk.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.wangdashe.top/Article/details/gtjgtpllyc.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.aibaodan.cn/Article/details/gtluudyahz.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jyoumei.cn/Article/details/gtabrvisel.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.sysykeji.top/Article/details/gtkronkuim.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.ybcxt.top/Article/details/gtsyoqtpkz.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhoulong.xyz/Article/details/gtchcmqwtr.html

[I04] 正则替换
来源：http://dali.yanxiufei.cn/Article/details/gtnwuobxqw.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hnqzz.top/Article/details/gtndhzscni.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.andypj.xyz/Article/details/gtnwhupjwl.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.gotoacloud.top/Article/details/gttadyfqzs.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yangfankeji.com/Article/details/gtrsnrheba.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zdqjudy.top/Article/details/gtuxbmbwmv.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.xinyue.icu/Article/details/gtbbvnevwy.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhiwuduotai.top/Article/details/gtszjqwyow.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yvedp.cn/Article/details/gtlulsvpas.html

[I05] 按正则拆分
来源：http://dali.c1oappe.top/Article/details/gtjnsgppoc.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jiagoushi.top/Article/details/gtaondiwuv.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jianghu66.top/Article/details/gtiynywpcw.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.hammf.cn/Article/details/gtosthdkhe.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yuxming.cn/Article/details/gtpwbnhuew.html

Java: s.split("\\s*,\\s*")
来源：http://dali.bjfxy.top/Article/details/gtsufhfrva.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.sufxvd.cn/Article/details/gtqusbujws.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhengqikj.top/Article/details/gtgbwlwlgh.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.cheryme.top/Article/details/gtdkoczwai.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.chenzaomai.com/Article/details/gtwuaxfoan.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.0kj1m.cn/Article/details/gtithyxzyj.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.sufxvd.cn/Article/details/gtehkgfvqi.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zycfv.cn/Article/details/gtuuhqspzo.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.aibaodan.cn/Article/details/gtrpkogfux.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.nanxuanxn.top/Article/details/gtxxlbiruh.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.zhongyouzk.top/Article/details/gteyqcsswr.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yj20258.top/Article/details/gtxfmffzay.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.gaohongyu789.top/Article/details/gtfofhouwg.html

[I07] 忽略大小写与多行模式
来源：http://dali.aibaodan.cn/Article/details/gthzixmxuk.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.mhx1999.top/Article/details/gtqqskbvgw.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.jinghuilouyu.cn/Article/details/gtlydfswxd.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.hnqzz.top/Article/details/gtwmvfzoae.html

TS:   /error/gim
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvchlnkmp.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.haohaochexian.top/Article/details/gtwmfyzjzs.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.tianlin.xyz/Article/details/gtmpnfrqut.html

Ruby: s.scan(/error/i)
来源：http://dali.yueranfly.top/Article/details/gtlwskngmk.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.nanxuanxn.top/Article/details/gthumphhor.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yongpay.top/Article/details/gtdcprbeit.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.ivvv.top/Article/details/gtrwhpouef.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.snrcjt.cn/Article/details/gtixmqabtf.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ywan-chungtsiang.top/Article/details/gthihucqmb.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.fzhhl.top/Article/details/gtpeazvhja.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.daria6918.cn/Article/details/gtuqrpraow.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.guowangkeji.top/Article/details/gtasubhmjg.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.9152youxi.cn/Article/details/gtukspqynt.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yongpay.top/Article/details/gtzhcamsrj.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtbjsjspfl.html

J. 日期与时间
来源：http://dali.yj202588.top/Article/details/gtasqcavdx.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtmvzieifo.html

[J01] 获取当前时间
来源：http://dali.yanxiufei.cn/Article/details/gtydfkfclf.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.smart0.xyz/Article/details/gtdbvcrhuq.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.haohaochexian.top/Article/details/gtgkvxznyl.html

JS:   new Date();  Date.now()
来源：http://dali.shzxlz.cn/Article/details/gtwlghozkw.html

TS:   new Date();  Date.now()
来源：http://dali.havefunace.top/Article/details/gtbbdlmcpb.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.pengpengdd.cyou/Article/details/gtmwgkokkk.html

Go:   time.Now()
来源：http://dali.ydzc1.top/Article/details/gtlkrlxozz.html

Ruby: Time.now
来源：http://dali.c1oappe.top/Article/details/gtmumyypwf.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhongyouzk.top/Article/details/gtsktbvpba.html

[J02] 格式化输出
来源：http://dali.yuanzhike.top/Article/details/gtmniaicfc.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.dashuyun.cn/Article/details/gtgfckonrn.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.cashguo.top/Article/details/gtjxbqcrsk.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zdqjudy.top/Article/details/gtjkixkcjs.html

TS:   d.toISOString()
来源：http://dali.cqqwz.cn/Article/details/gtassacjwp.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.redwolf501.top/Article/details/gtrgykzksw.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jinghuilouyu.cn/Article/details/gtqlxoetou.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jlsjyb.cn/Article/details/gtgikswxbj.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.fengsongda.top/Article/details/gtydlsgwmk.html

[J03] 字符串解析为日期
来源：http://dali.xuetiantiany.cn/Article/details/gterdqwakp.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.fzhhl.top/Article/details/gtagdeamln.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.guowangkeji.top/Article/details/gtjodwortd.html

JS:   new Date("2024-01-02")
来源：http://dali.yangfankeji.com/Article/details/gtngthbfam.html

TS:   new Date("2024-01-02")
来源：http://dali.shzxlz.cn/Article/details/gtfzltuvss.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsqexjaoo.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hfpthk.cn/Article/details/gtsxwwxwty.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.sweek.top/Article/details/gtujlfdmfs.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zhiwuduotai.top/Article/details/gtmkvgkwbf.html

[J04] 时间戳与日期互转
来源：http://dali.ppjwa.cn/Article/details/gtjkuxcjpi.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.hammf.cn/Article/details/gtgrfneuwa.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.9152youxi.cn/Article/details/gtgpkfdjuk.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhoulong.xyz/Article/details/gttwncadwo.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.xylfe.cn/Article/details/gtvjehcypt.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.shangyingyoupin.top/Article/details/gtkkbntvyo.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhixingplan.top/Article/details/gtedjuimne.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.chenzaomai.com/Article/details/gtsngvhhyx.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yvedp.cn/Article/details/gtnlygfaqm.html

[J05] 时间加减（加 7 天）
来源：http://dali.quarkkingdee.top/Article/details/gtzzvxwsfo.html

Py:   now + timedelta(days=7)
来源：http://dali.yanxiufei.cn/Article/details/gtbmwgreus.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zycfv.cn/Article/details/gtcertfdzv.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sweek.top/Article/details/gtliznwwop.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgzuktvoc.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.0kj1m.cn/Article/details/gtiafdvcto.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.daxiang520.top/Article/details/gtuuhgpbmw.html

Ruby: Time.now + 7 * 86400
来源：http://dali.svipenyu.cn/Article/details/gtevbvvnsb.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.feifeiyinyue.top/Article/details/gtirsjzozs.html

[J06] 计算两时间之差
来源：http://dali.nwbrower.top/Article/details/gtmhdjtrkh.html

Py:   (end - start).total_seconds()
来源：http://dali.fengsongda.top/Article/details/gtsrnvbaus.html

PHP:  $end->diff($start)->days;
来源：http://dali.aizwys.cn/Article/details/gtctpzllbu.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.gogol.net.cn/Article/details/gtefbvgqup.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.xuanzx.com/Article/details/gtmvjzpxqf.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.ppjwa.cn/Article/details/gtbbwsaotu.html

Go:   end.Sub(start).Hours()
来源：http://dali.hnxiangtu.top/Article/details/gtykemnpcr.html

Ruby: end - start                 # 返回秒数
来源：http://dali.gzhubu.top/Article/details/gtwuwqqivt.html

C#:   (end - start).TotalSeconds
来源：http://dali.yongpay.top/Article/details/gtgaiyxsmo.html

[J07] 比较两个日期
来源：http://dali.redwolf501.top/Article/details/gtsnlxycsi.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zycfv.cn/Article/details/gthgwdtoci.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.xuetiantiany.cn/Article/details/gtktqbmots.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.ehwqpu.com/Article/details/gtkhvededy.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yj202588.top/Article/details/gtjnpfnbce.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jiagoushi.top/Article/details/gtxvftmaww.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.redwolf501.top/Article/details/gtvnrsssed.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.zhengqikj.top/Article/details/gtfuaxezxj.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jqgufenzy.top/Article/details/gthgmxnytz.html

[J08] 提取年月日与星期
来源：http://dali.ivvv.top/Article/details/gtptjtmbpd.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhixingplan.top/Article/details/gtvvckpglm.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.xuetiantiany.cn/Article/details/gtusewvzev.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yueranfly.top/Article/details/gttjuervme.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.smart0.xyz/Article/details/gtpygijamw.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.gogol.net.cn/Article/details/gtcqdocuyp.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yuxming.cn/Article/details/gtkgxtgnmi.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.iojbl.cn/Article/details/gtqradvuty.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.c1oappe.top/Article/details/gtvexvmqwa.html

[J09] 时区处理
来源：http://dali.yuanzhike.top/Article/details/gtqecivgcm.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.snrcjt.cn/Article/details/gtvzvagrbr.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.yuxming.cn/Article/details/gtlnjmojpg.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.fengsongda.top/Article/details/gtfookwxdn.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jyoumei.cn/Article/details/gtlaghcbnl.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.dianchejie.cn/Article/details/gtyakvcbdh.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.hongshengwenyu.top/Article/details/gtrvvwokyh.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.guowangkeji.top/Article/details/gtmgubgdbf.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.daria6918.cn/Article/details/gtyexcznzw.html

[J10] 取今天 / 本月第一天
来源：http://dali.hammf.cn/Article/details/gtqludvtio.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.sxryk.cn/Article/details/gtyzhpychz.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.tianlin.xyz/Article/details/gtjlsfrpex.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.dianchejie.cn/Article/details/gtfshltgiv.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yuxming.cn/Article/details/gtnqejjvup.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yongpay.top/Article/details/gtvjtixtew.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.gaohongyu789.top/Article/details/gtmumvlvco.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hfpthk.cn/Article/details/gtnrpsllnz.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.dashuyun.cn/Article/details/gtzkqwqfpm.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtmvxsavht.html

K. JSON 与序列化
来源：http://dali.tian-w.cn/Article/details/gtmrayznvy.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtzyjydxjb.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhijiandao.cn/Article/details/gtvnqlbzzx.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.shanyushiyangtech.top/Article/details/gtycajqiil.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.havefunace.top/Article/details/gtjroqlkvz.html

JS:   JSON.stringify(obj)
来源：http://dali.chenzaomai.com/Article/details/gtgjmzcutd.html

TS:   JSON.stringify(obj)
来源：http://dali.yueranfly.top/Article/details/gtrrkqzpyq.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yueranfly.top/Article/details/gtveccmgaq.html

Go:   json.Marshal(obj)
来源：http://dali.zhengqikj.top/Article/details/gtxjsdwmpt.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.dianchejie.cn/Article/details/gtmujfeeel.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.0kj1m.cn/Article/details/gtxvsbekzx.html

[K02] JSON 字符串转对象
来源：http://dali.chenzaomai.com/Article/details/gtpoojscbq.html

Py:   json.loads(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrfhazyyh.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.wangdashe.top/Article/details/gtxcbfwbju.html

JS:   JSON.parse(s)
来源：http://dali.quarkkingdee.top/Article/details/gtvvvmftlg.html

TS:   JSON.parse(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtsjnifinr.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.snrcjt.cn/Article/details/gteurhsyvd.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.guannengcc.top/Article/details/gtkvcghpnq.html

Ruby: JSON.parse(s)
来源：http://dali.snrcjt.cn/Article/details/gtdqqoxhvl.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.guowangkeji.top/Article/details/gtdzirwyjf.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jqgufenzy.top/Article/details/gtjljpxhxj.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.nanxinkj.top/Article/details/gtjrnaomfx.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.sufxvd.cn/Article/details/gtiktfmrrr.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.xuetiantiany.cn/Article/details/gtfvjlynif.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.gotoacloud.top/Article/details/gtrighfsji.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.tianlin.xyz/Article/details/gtejubwbns.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yvedp.cn/Article/details/gtjrgzuixd.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.shzxlz.cn/Article/details/gtcinuhkou.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.vqdsnc.cn/Article/details/gtmnezavcw.html

[K04] 读取 JSON 文件
来源：http://dali.tianlin.xyz/Article/details/gtfbpcmegb.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.c1oappe.top/Article/details/gtmpurjjrc.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.snrcjt.cn/Article/details/gtsrjyqidr.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.nanxuanxn.top/Article/details/gtzujbofsy.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmcukkibr.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.haohaochexian.top/Article/details/gtqenxspcn.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.316326.xyz/Article/details/gtxjhevvcz.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yangfankeji.com/Article/details/gtezzgnwua.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.meibo888.top/Article/details/gtcednifbf.html

[K05] 深拷贝对象
来源：http://dali.guowangkeji.top/Article/details/gtvfduvhbz.html

Py:   copy.deepcopy(obj)
来源：http://dali.nanxinkj.top/Article/details/gtwvwcjhir.html

PHP:  unserialize(serialize($obj));
来源：http://dali.feifeiyinyue.top/Article/details/gtentsxtms.html

JS:   structuredClone(obj)
来源：http://dali.tian-w.cn/Article/details/gtmkarhzvu.html

TS:   structuredClone(obj)
来源：http://dali.sufxvd.cn/Article/details/gtnpbhwrpz.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jinqigufen.top/Article/details/gthkfppuzn.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.hongshengwenyu.top/Article/details/gtwkkljryo.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.hywenlv.cn/Article/details/gtkkwoffkb.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.fengsongda.top/Article/details/gtmhonjhzp.html

[K06] 解析 URL 查询串
来源：http://dali.ppjwa.cn/Article/details/gtqrjmjqgu.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.jyoumei.cn/Article/details/gtbsyziprz.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yonumen.top/Article/details/gtsqdulbfl.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinqigfzy.top/Article/details/gttazpsnuh.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sxryk.cn/Article/details/gtfktmndgw.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.shzxlz.cn/Article/details/gtoyhekllh.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yj20258.top/Article/details/gtxdjtznll.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.zhongyouzk.top/Article/details/gtqinyydfc.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.yanxiufei.cn/Article/details/gtfkcmjwxx.html

[K07] 进制转换
来源：http://dali.tianlin.xyz/Article/details/gtoaswcxmt.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jinqigfzy.top/Article/details/gtzxpiytzw.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yongpay.top/Article/details/gtbtqmrfpa.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.feifeiyinyue.top/Article/details/gtgbqgylen.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.iojbl.cn/Article/details/gtsouzmlvf.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.xylfe.cn/Article/details/gtgodoitrr.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.ppjwa.cn/Article/details/gtqzfzjxlq.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.cucudq.cn/Article/details/gtcnrbjrnj.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.xuetiantiany.cn/Article/details/gtalckberb.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.tian-w.cn/Article/details/gtitfuopjz.html

Py:   pickle.dumps(obj)
来源：http://dali.jlsjyb.cn/Article/details/gtliuwhbmh.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.9152youxi.cn/Article/details/gtcmgzjaed.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.cucudq.cn/Article/details/gtuculjirp.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.mhx1999.top/Article/details/gtsecqhqtc.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.gaohongyu789.top/Article/details/gtbhbpxzan.html

Go:   encoding/gob
来源：http://dali.cqqwz.cn/Article/details/gtubnwmrxs.html

Ruby: Marshal.dump(obj)
来源：http://dali.xuanzx.com/Article/details/gtulocowln.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.cdnleiting.top/Article/details/gtxdmwwjts.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtdvjumeki.html

L. 网络请求
来源：http://dali.yj20258888.top/Article/details/gtdyumozkj.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtiholuoqi.html

[L01] 发送 GET 请求
来源：http://dali.bjfxy.top/Article/details/gtwtuhvbzt.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.tanke756.top/Article/details/gtkzchdoqx.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.mhx1999.top/Article/details/gtonqdrzgv.html

JS:   await fetch(url)
来源：http://dali.feifeiyinyue.top/Article/details/gtluxpxijm.html

TS:   await fetch(url)
来源：http://dali.tanke756.top/Article/details/gtfxxrvecg.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zycfv.cn/Article/details/gtzvzbqecw.html

Go:   resp, err := http.Get(url)
来源：http://dali.hfpthk.cn/Article/details/gteyhxliol.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zycfv.cn/Article/details/gturijtgad.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.shzxlz.cn/Article/details/gtntzfalue.html

[L02] 发送 POST JSON
来源：http://dali.havefunace.top/Article/details/gtkellydci.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yj20258888.top/Article/details/gtoxicmnun.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.xuanzx.com/Article/details/gtqgawoknf.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jlsjyb.cn/Article/details/gteusudkak.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sufxvd.cn/Article/details/gtzrzbcojz.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.cheryme.top/Article/details/gtmbthdgcy.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.ppjwa.cn/Article/details/gtwhyrzscu.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.hnxiangtu.top/Article/details/gtkotsqveu.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.ehwqpu.com/Article/details/gtmyliksmt.html

[L03] 设置自定义请求头
来源：http://dali.nwbrower.top/Article/details/gtobxbgdue.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.aibaodan.cn/Article/details/gtljraucth.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.chenjidiqi.icu/Article/details/gtokusafeo.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jinqigufen.top/Article/details/gtfnrqxybg.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.iojbl.cn/Article/details/gtyxzvjuop.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.hywenlv.cn/Article/details/gtmfzyevmy.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.chenzaomai.com/Article/details/gtjmhdfezf.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.meibo888.top/Article/details/gtfptttziy.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yangfankeji.com/Article/details/gtccbunnqp.html

[L04] 设置超时
来源：http://dali.kuanghao11.cn/Article/details/gthzqfgyce.html

Py:   requests.get(url, timeout=5)
来源：http://dali.jiagoushi.top/Article/details/gtpdizabku.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.tanke756.top/Article/details/gtphfavvha.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.pycfn.com/Article/details/gtztymjplz.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.sxryk.cn/Article/details/gtsjidpscr.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.snrcjt.cn/Article/details/gtwyembxtq.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.chenlongwang.top/Article/details/gtwebkuvju.html


<!-- 参考信息 -->