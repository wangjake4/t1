代发 wailian999

JS:   e.message;  e.stack
来源：http://dali.xuanzx.com/Article/details/gtnoiirsys.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.vqdsnc.cn/Article/details/gtjxkiptai.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jianghu66.top/Article/details/gtqlfrowrv.html

Go:   err.Error()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtapnzdhfs.html

Ruby: e.message;  e.backtrace
来源：http://dali.ybcxt.top/Article/details/gtbnrheiln.html

C#:   e.Message;  e.StackTrace
来源：http://dali.daxiang520.top/Article/details/gtduigfimj.html

[H09] 带错误码的异常
来源：http://dali.ivvv.top/Article/details/gtsxsglzpp.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.havefunace.top/Article/details/gtegooftwt.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zdqjudy.top/Article/details/gtbfsemtfm.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.dashuyun.cn/Article/details/gtbucppmeb.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.xziqi.cn/Article/details/gtswsdaqfg.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jinqigfzy.top/Article/details/gtdnjqlolu.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.ppjwa.cn/Article/details/gtfzfzwanb.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.ppjwa.cn/Article/details/gtshozkpls.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.ivvv.top/Article/details/gtgilwtpeg.html

[H10] 资源自动释放
来源：http://dali.zycfv.cn/Article/details/gtfqjodllg.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.svipenyu.cn/Article/details/gtresjaygc.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrorjtwos.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhixingplan.top/Article/details/gtajsjnnef.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.dashuyun.cn/Article/details/gttpfdhdhu.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.pengpengdd.cyou/Article/details/gtprdazfec.html

Go:   defer f.Close()
来源：http://dali.havefunace.top/Article/details/gtuluaymjl.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.sysykeji.top/Article/details/gtjiebmvzy.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gttyrsnbko.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtbfcsqugb.html

I. 正则表达式
来源：http://dali.wangshuangyany.cn/Article/details/gtbilnheia.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gthgsftaeu.html

[I01] 判断是否匹配
来源：http://dali.quarkkingdee.top/Article/details/gtrmoobsgw.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.dianchejie.cn/Article/details/gttmtndlma.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.daria6918.cn/Article/details/gtrnnvcwzo.html

JS:   /\d+/.test(s)
来源：http://dali.ivvv.top/Article/details/gtqsdpcueu.html

TS:   /\d+/.test(s)
来源：http://dali.quarkkingdee.top/Article/details/gtpbmhurza.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.gaohongyu789.top/Article/details/gtszsqwhia.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.tian-w.cn/Article/details/gtitkhjbeb.html

Ruby: s.match?(/\d+/)
来源：http://dali.birdmap.top/Article/details/gtlrxejfeb.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.hysaishi.cn/Article/details/gtqjvkrddq.html

[I02] 提取所有匹配
来源：http://dali.jyoumei.cn/Article/details/gtyvnxpggr.html

Py:   re.findall(r"\d+", s)
来源：http://dali.ppjwa.cn/Article/details/gtcpljgkvq.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jinqigfzy.top/Article/details/gtyhurjfme.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.havefunace.top/Article/details/gtvigolgvj.html

TS:   s.match(/\d+/g)
来源：http://dali.zhijiandao.cn/Article/details/gtsahttsug.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.hammf.cn/Article/details/gtbmodmggy.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.kuanghao11.cn/Article/details/gtegprutep.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhoulong.xyz/Article/details/gtmkyizscc.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.vqdsnc.cn/Article/details/gtlelataho.html

[I03] 提取捕获分组
来源：http://dali.xylfe.cn/Article/details/gtivlgvozh.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.xylfe.cn/Article/details/gtjqpakkit.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yanxiufei.cn/Article/details/gtvzidpuvh.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yonumen.top/Article/details/gtpeiejmfu.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.wangdashe.top/Article/details/gtaeunsknw.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.wangshuangyany.cn/Article/details/gtghddobqh.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.chenjidiqi.icu/Article/details/gtcruujwdm.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.daria6918.cn/Article/details/gtevwveacu.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.cucudq.cn/Article/details/gtdfxxtcai.html

[I04] 正则替换
来源：http://dali.jqgfzy.top/Article/details/gtdaxqbukq.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yj20258.top/Article/details/gtufibcuqg.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.meibo888.top/Article/details/gtaeadvakl.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.hnqzz.top/Article/details/gtkhtibtab.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yonumen.top/Article/details/gttxwpbhpk.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.tianlin.xyz/Article/details/gtjlscitdc.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.9152youxi.cn/Article/details/gtktwrgmdh.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.shzxlz.cn/Article/details/gtmgwhuuyz.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.nwbrower.top/Article/details/gtjnisyzbo.html

[I05] 按正则拆分
来源：http://dali.yueranfly.top/Article/details/gtgmvvggsd.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yueranfly.top/Article/details/gtchtvapqz.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.shangyingyoupin.top/Article/details/gtijnjcxak.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zdqjudy.top/Article/details/gtnkmmwprl.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yuxming.cn/Article/details/gtgfipnxfs.html

Java: s.split("\\s*,\\s*")
来源：http://dali.iojbl.cn/Article/details/gtfhtycfxy.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.0kj1m.cn/Article/details/gtogcozgjm.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.hnqzz.top/Article/details/gtldhncpfo.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.gogol.net.cn/Article/details/gtrcuyvdwj.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.c1oappe.top/Article/details/gtrvyztdfx.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yongpay.top/Article/details/gtbvgnseod.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.havefunace.top/Article/details/gtmlkwosmh.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.aizwys.cn/Article/details/gtidptccgp.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.sxryk.cn/Article/details/gtipcmhgcj.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.pycfn.com/Article/details/gteobegpli.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jianghu66.top/Article/details/gtmnyjhbyw.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.chenzaomai.com/Article/details/gtvoscvyav.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.hnqzz.top/Article/details/gtnkpykage.html

[I07] 忽略大小写与多行模式
来源：http://dali.hongshengwenyu.top/Article/details/gtvghzqtte.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.shuidangran.top/Article/details/gtlseuzsqh.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yonumen.top/Article/details/gtkboevndt.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.c1oappe.top/Article/details/gtmndxkaaa.html

TS:   /error/gim
来源：http://dali.chenzaomai.com/Article/details/gtqdkpiizq.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.quarkkingdee.top/Article/details/gtwhmhxkqu.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.gaohongyu789.top/Article/details/gttgxzsujk.html

Ruby: s.scan(/error/i)
来源：http://dali.sweek.top/Article/details/gtuvdjyand.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.gzhubu.top/Article/details/gtoetcnybd.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.chenlongwang.top/Article/details/gtwzzlpxlm.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.birdmap.top/Article/details/gtdxardsuo.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.sxryk.cn/Article/details/gtuyftciov.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.kuanghao11.cn/Article/details/gtpxvwaasq.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cdnleiting.top/Article/details/gttiaiuwhm.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.shzxlz.cn/Article/details/gtlycjxbul.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.sxryk.cn/Article/details/gtwqyfmtpu.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jiagoushi.top/Article/details/gtegfmetso.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.quarkkingdee.top/Article/details/gtxlzxpsei.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtrcuccyqb.html

J. 日期与时间
来源：http://dali.chenzaomai.com/Article/details/gtvkzhybuw.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtiftiyclq.html

[J01] 获取当前时间
来源：http://dali.nanxuanxn.top/Article/details/gtdvgthigk.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfnmdrqfc.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuyimivwu.html

JS:   new Date();  Date.now()
来源：http://dali.ybcxt.top/Article/details/gtbpcmwrpk.html

TS:   new Date();  Date.now()
来源：http://dali.dianchejie.cn/Article/details/gtiztmymur.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jiagoushi.top/Article/details/gtsppmdrav.html

Go:   time.Now()
来源：http://dali.dianchejie.cn/Article/details/gtisnkmgwd.html

Ruby: Time.now
来源：http://dali.hammf.cn/Article/details/gtugcboqtd.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.gogol.net.cn/Article/details/gtlavlgkox.html

[J02] 格式化输出
来源：http://dali.cqqwz.cn/Article/details/gtwpewthdx.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jianghu66.top/Article/details/gtxvcsqkgq.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.dianchejie.cn/Article/details/gtgahytkzy.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.daxiang520.top/Article/details/gtxrlikpoa.html

TS:   d.toISOString()
来源：http://dali.sufxvd.cn/Article/details/gtedvymlzq.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.hongshengwenyu.top/Article/details/gtupbgvumx.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.gotoacloud.top/Article/details/gtvptrpncn.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhijiandao.cn/Article/details/gtayibsbwd.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.xuanzx.com/Article/details/gtjxroicfj.html

[J03] 字符串解析为日期
来源：http://dali.dashuyun.cn/Article/details/gtyfkaljyo.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.guowangkeji.top/Article/details/gtproznvjq.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.yj20258.top/Article/details/gtrmykelte.html

JS:   new Date("2024-01-02")
来源：http://dali.yj20258888.top/Article/details/gttfsaqkut.html

TS:   new Date("2024-01-02")
来源：http://dali.vqdsnc.cn/Article/details/gtgqnixsfs.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.nanxuanxn.top/Article/details/gtbmmgjhvx.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.snrcjt.cn/Article/details/gtnjwltjrg.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.nanxuanxn.top/Article/details/gtqhhcmetu.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.xylfe.cn/Article/details/gtraxpwcpu.html

[J04] 时间戳与日期互转
来源：http://dali.guowangkeji.top/Article/details/gtvefkwzcj.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.quarkkingdee.top/Article/details/gthhirgqlj.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.hammf.cn/Article/details/gtqgtdduwl.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.sxryk.cn/Article/details/gtnszkoeqa.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.sufxvd.cn/Article/details/gtpqghoqej.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.sxryk.cn/Article/details/gtkrfvefnw.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.chenjidiqi.icu/Article/details/gtwcudawkd.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.haohaochexian.top/Article/details/gtzjbtdutm.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.nanxinkj.top/Article/details/gtozetxrkl.html

[J05] 时间加减（加 7 天）
来源：http://dali.andypj.xyz/Article/details/gtuoqagwxo.html

Py:   now + timedelta(days=7)
来源：http://dali.cucudq.cn/Article/details/gtmpxnqwxr.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yonumen.top/Article/details/gtmeczkvel.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.tian-w.cn/Article/details/gtyvlvzbus.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.tianlin.xyz/Article/details/gttwrxmypu.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.iojbl.cn/Article/details/gtbdfflefj.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yj202588.top/Article/details/gtvmrntqkd.html

Ruby: Time.now + 7 * 86400
来源：http://dali.tianlin.xyz/Article/details/gtkdddunzt.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.wangshuangyany.cn/Article/details/gtkenxnmsm.html

[J06] 计算两时间之差
来源：http://dali.ywan-chungtsiang.top/Article/details/gtroyawxqv.html

Py:   (end - start).total_seconds()
来源：http://dali.yueranfly.top/Article/details/gtujfagpbq.html

PHP:  $end->diff($start)->days;
来源：http://dali.ppjwa.cn/Article/details/gtbcrgwvtc.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhaomingkeji.xyz/Article/details/gttxyakzsn.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.nanxuanxn.top/Article/details/gthymgzuot.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.chenlongwang.top/Article/details/gtywsfvzst.html

Go:   end.Sub(start).Hours()
来源：http://dali.xinyue.icu/Article/details/gtknzpvspj.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yangfankeji.com/Article/details/gtrjcovfed.html

C#:   (end - start).TotalSeconds
来源：http://dali.jinqigfzy.top/Article/details/gtltlldoxa.html

[J07] 比较两个日期
来源：http://dali.ivvv.top/Article/details/gtlraeklzn.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.shuidangran.top/Article/details/gtangpjvny.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.cheryme.top/Article/details/gtbxjnkshe.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.shuidangran.top/Article/details/gteahbmhoc.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.meibo888.top/Article/details/gtharnsrjk.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.316326.xyz/Article/details/gtmgsgalnb.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.tianlin.xyz/Article/details/gtledurvox.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.chenjidiqi.icu/Article/details/gtcjpuyyjs.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.daxiang520.top/Article/details/gthzpsiops.html

[J08] 提取年月日与星期
来源：http://dali.0kj1m.cn/Article/details/gtgrhyagsi.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.xylfe.cn/Article/details/gthpawsovu.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yonumen.top/Article/details/gtwqnfrxef.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jiagoushi.top/Article/details/gtsfwlwdpb.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.gogol.net.cn/Article/details/gtudypjloh.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.zycfv.cn/Article/details/gtusnzchkr.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.xylfe.cn/Article/details/gtyzzgsuit.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yueranfly.top/Article/details/gtnlqsiyel.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yj20258.top/Article/details/gtspbruihd.html

[J09] 时区处理
来源：http://dali.daria6918.cn/Article/details/gttyhsimlr.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhixingplan.top/Article/details/gtmysmvutw.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.ehwqpu.com/Article/details/gtwiozwojk.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jyoumei.cn/Article/details/gtastdjqbd.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jinqigufen.top/Article/details/gtkovaclvt.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.chenlongwang.top/Article/details/gtvseyyaqi.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.hysaishi.cn/Article/details/gtebrbxuot.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.0kj1m.cn/Article/details/gtlqxkmyyz.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.cheryme.top/Article/details/gttvxosueb.html

[J10] 取今天 / 本月第一天
来源：http://dali.jqgfzy.top/Article/details/gtezdvveiv.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.fzhhl.top/Article/details/gtloirdotl.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.ybcxt.top/Article/details/gtbpqtvjxz.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.feifeiyinyue.top/Article/details/gtnhacbboc.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.chenjidiqi.icu/Article/details/gtlghjkdxg.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.hnqzz.top/Article/details/gtsnuzimuv.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.gogol.net.cn/Article/details/gtfsbeihyj.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jqgufenzy.top/Article/details/gtefswewis.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.ybcxt.top/Article/details/gtdweoazdf.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtufflpqat.html

K. JSON 与序列化
来源：http://dali.yj20258.top/Article/details/gtwcpkjncx.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtislpwfef.html

[K01] 对象转 JSON 字符串
来源：http://dali.shzxlz.cn/Article/details/gtbdztcroi.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.dianchejie.cn/Article/details/gtinvqrryk.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.jqgfzy.top/Article/details/gtmfnfukcq.html

JS:   JSON.stringify(obj)
来源：http://dali.guowangkeji.top/Article/details/gtwyqbomdy.html

TS:   JSON.stringify(obj)
来源：http://dali.jiagoushi.top/Article/details/gtsbrtmpze.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.xinyue.icu/Article/details/gtroslhaxa.html

Go:   json.Marshal(obj)
来源：http://dali.tanke756.top/Article/details/gtizzsrhvx.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.daxiang520.top/Article/details/gtvqwsffuf.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.guowangkeji.top/Article/details/gtxfzcwnzi.html

[K02] JSON 字符串转对象
来源：http://dali.guowangkeji.top/Article/details/gtnhegzedp.html

Py:   json.loads(s)
来源：http://dali.nanxuanxn.top/Article/details/gtcerrelux.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yonumen.top/Article/details/gtujzadbdr.html

JS:   JSON.parse(s)
来源：http://dali.jinqigfzy.top/Article/details/gtxwvvotzx.html

TS:   JSON.parse(s)
来源：http://dali.hfpthk.cn/Article/details/gtywcaxhdy.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.ydzc1.top/Article/details/gtoqcxgqbu.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbvfyowxo.html

Ruby: JSON.parse(s)
来源：http://dali.yueranfly.top/Article/details/gtskdkptuz.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yvedp.cn/Article/details/gteuaapivp.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.haohaochexian.top/Article/details/gtqdpwauds.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.bjfxy.top/Article/details/gtgcgsvvhv.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.xuetiantiany.cn/Article/details/gtsxiqxrtm.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.hnqzz.top/Article/details/gteaibqcrj.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.tanke756.top/Article/details/gtohfxhejq.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.yongpay.top/Article/details/gtujnojbki.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.cdnleiting.top/Article/details/gtrriuuwtn.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmvreefop.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zycfv.cn/Article/details/gtwadeqlry.html

[K04] 读取 JSON 文件
来源：http://dali.xylfe.cn/Article/details/gttbbacqgw.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.gogol.net.cn/Article/details/gtjzloxmfk.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.snrcjt.cn/Article/details/gtkohirupg.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xuanzx.com/Article/details/gtaztssudm.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.redwolf501.top/Article/details/gtbwikysmx.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtszpqiixg.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.fengsongda.top/Article/details/gtxbipcpgj.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.ehwqpu.com/Article/details/gtadfungxn.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.ehwqpu.com/Article/details/gtokjswzbt.html

[K05] 深拷贝对象
来源：http://dali.jyoumei.cn/Article/details/gtcjlojyjx.html

Py:   copy.deepcopy(obj)
来源：http://dali.jinqigufen.top/Article/details/gticeyrcxw.html

PHP:  unserialize(serialize($obj));
来源：http://dali.redwolf501.top/Article/details/gtlqqwskam.html

JS:   structuredClone(obj)
来源：http://dali.nanxinkj.top/Article/details/gtrijbtcit.html

TS:   structuredClone(obj)
来源：http://dali.c1oappe.top/Article/details/gtcqyeeqkg.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.nwbrower.top/Article/details/gtrgyhkrrq.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhiwuduotai.top/Article/details/gtdbsiqtgk.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.pengpengdd.cyou/Article/details/gtzrnljjpt.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.cheryme.top/Article/details/gtclpxxrkl.html

[K06] 解析 URL 查询串
来源：http://dali.jinghuilouyu.cn/Article/details/gtagpretya.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.havefunace.top/Article/details/gtyqaeiswz.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.xinyue.icu/Article/details/gtnobldukb.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.gzhubu.top/Article/details/gteaownvzz.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.guowangkeji.top/Article/details/gtefodybpq.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.c1oappe.top/Article/details/gthkpnabrn.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.tanke756.top/Article/details/gtmttavfit.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.hnqzz.top/Article/details/gtvtjqcynt.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.cheryme.top/Article/details/gtlxyncmau.html

[K07] 进制转换
来源：http://dali.chenjidiqi.icu/Article/details/gtudqjnuzr.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.shzxlz.cn/Article/details/gtjwiduuxl.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhiwuduotai.top/Article/details/gtqzdeykgp.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhaomingkeji.xyz/Article/details/gteevezoao.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.9152youxi.cn/Article/details/gtfihnpubd.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.jiagoushi.top/Article/details/gthmltjkop.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.hnxiangtu.top/Article/details/gtubqztijg.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.zhoulong.xyz/Article/details/gtehjdgyeb.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.feifeiyinyue.top/Article/details/gtatzwgynf.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yueranfly.top/Article/details/gtsyjrjwxk.html

Py:   pickle.dumps(obj)
来源：http://dali.yuanzhike.top/Article/details/gtfgqpcprf.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.dashuyun.cn/Article/details/gthcapxjdf.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.daria6918.cn/Article/details/gtmtwkdlcx.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.xylfe.cn/Article/details/gthlfwbuvm.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.xuanzx.com/Article/details/gtqomgcnjc.html

Go:   encoding/gob
来源：http://dali.gzhubu.top/Article/details/gtvlduauhl.html

Ruby: Marshal.dump(obj)
来源：http://dali.yueranfly.top/Article/details/gtxczuqjgd.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.chenjidiqi.icu/Article/details/gtzbjmxqlz.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtjpqvgzgs.html

L. 网络请求
来源：http://dali.hammf.cn/Article/details/gtirqgboqj.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtbtdlsgbs.html

[L01] 发送 GET 请求
来源：http://dali.shangyingyoupin.top/Article/details/gtvzhkvhuj.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.hongshengwenyu.top/Article/details/gtclapgzph.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yvedp.cn/Article/details/gtdnjauilw.html

JS:   await fetch(url)
来源：http://dali.yanxiufei.cn/Article/details/gtofeorwcv.html

TS:   await fetch(url)
来源：http://dali.aizwys.cn/Article/details/gtjvkekyfm.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jqgfzy.top/Article/details/gtkdnjedpj.html

Go:   resp, err := http.Get(url)
来源：http://dali.cheryme.top/Article/details/gtblgdjzki.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jiagoushi.top/Article/details/gtenanglzg.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.daxiang520.top/Article/details/gttjqaiicr.html

[L02] 发送 POST JSON
来源：http://dali.nwbrower.top/Article/details/gtlvskgsxc.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jinqigfzy.top/Article/details/gtypsbryfl.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.gogol.net.cn/Article/details/gtfphxzkqy.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhengqikj.top/Article/details/gtqmkumkxa.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zdqjudy.top/Article/details/gtxrpksxhg.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.cucudq.cn/Article/details/gtjatmdfdi.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.aibaodan.cn/Article/details/gtejnglyyh.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.hysaishi.cn/Article/details/gtpimijqsh.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.hammf.cn/Article/details/gtzbnhbysf.html

[L03] 设置自定义请求头
来源：http://dali.jiagoushi.top/Article/details/gtmfckotsh.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.hnqzz.top/Article/details/gttzrergfc.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.chenlongwang.top/Article/details/gtqgrhwbif.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zycfv.cn/Article/details/gtjctsrvyy.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jqgufenzy.top/Article/details/gtkgwgksqf.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.redwolf501.top/Article/details/gtrvqaayqj.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.aizwys.cn/Article/details/gtqaffqreu.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jqgufenzy.top/Article/details/gtzpxrwcmg.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.hysaishi.cn/Article/details/gtzwxlrija.html

[L04] 设置超时
来源：http://dali.yueranfly.top/Article/details/gtzuacgrek.html

Py:   requests.get(url, timeout=5)
来源：http://dali.ydzc1.top/Article/details/gtkvrrhyoz.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.kuanghao11.cn/Article/details/gtklnvomwu.html


<!-- 参考信息 -->