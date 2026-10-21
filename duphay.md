代发 wailian999

C#:   Debug.Assert(x > 0);
来源：http://dali.hfpthk.cn/Article/details/gtdfcjihpa.html

[H08] 获取错误信息与堆栈
来源：http://dali.jyoumei.cn/Article/details/gtiobkseff.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.andypj.xyz/Article/details/gtyoyosiba.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yvedp.cn/Article/details/gtnoaxziib.html

JS:   e.message;  e.stack
来源：http://dali.yj202588.top/Article/details/gteustolux.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhiwuduotai.top/Article/details/gtvcbxshys.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.tanke756.top/Article/details/gtianwoitl.html

Go:   err.Error()
来源：http://dali.svipenyu.cn/Article/details/gtegivaocx.html

Ruby: e.message;  e.backtrace
来源：http://dali.yangfankeji.com/Article/details/gtkuesgaen.html

C#:   e.Message;  e.StackTrace
来源：http://dali.c1oappe.top/Article/details/gtcfgojafw.html

[H09] 带错误码的异常
来源：http://dali.jinghuilouyu.cn/Article/details/gtiwvloqcy.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.cdnleiting.top/Article/details/gtjfiblwnp.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.nanxuanxn.top/Article/details/gtyttusuwi.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yangfankeji.com/Article/details/gtjayqoexe.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.vqdsnc.cn/Article/details/gtimwocrug.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.gotoacloud.top/Article/details/gtmzayxfiq.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.hnqzz.top/Article/details/gtwykvydoi.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.shzxlz.cn/Article/details/gtsugrrifo.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhoulong.xyz/Article/details/gtslwzkxxw.html

[H10] 资源自动释放
来源：http://dali.andypj.xyz/Article/details/gtoaayqdyf.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhaomingkeji.xyz/Article/details/gthcyiioyg.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhengqikj.top/Article/details/gtfhdqiiph.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shzxlz.cn/Article/details/gtzcntmzdo.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.havefunace.top/Article/details/gtdmstwdwh.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhoulong.xyz/Article/details/gtjkpwuezv.html

Go:   defer f.Close()
来源：http://dali.gotoacloud.top/Article/details/gtyrkjkerz.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yongpay.top/Article/details/gtvuamtxyz.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gtchhloevu.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtyykejtyh.html

I. 正则表达式
来源：http://dali.hysaishi.cn/Article/details/gtbvptdhqr.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtudzdjdxl.html

[I01] 判断是否匹配
来源：http://dali.gotoacloud.top/Article/details/gtbtmanqgv.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.smart0.xyz/Article/details/gtdhqbnlne.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.fzhhl.top/Article/details/gtcmwbtqjg.html

JS:   /\d+/.test(s)
来源：http://dali.gaohongyu789.top/Article/details/gttgfujttt.html

TS:   /\d+/.test(s)
来源：http://dali.jinqigufen.top/Article/details/gtidmigfkl.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.sweek.top/Article/details/gtqmijvnvt.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jinqigufen.top/Article/details/gtkzymjmdz.html

Ruby: s.match?(/\d+/)
来源：http://dali.cqqwz.cn/Article/details/gtwcpdhftq.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.0kj1m.cn/Article/details/gtntjehzei.html

[I02] 提取所有匹配
来源：http://dali.iojbl.cn/Article/details/gtwbtxzouj.html

Py:   re.findall(r"\d+", s)
来源：http://dali.nwbrower.top/Article/details/gtwobggoqz.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.pengpengdd.cyou/Article/details/gttuwluvdn.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yangfankeji.com/Article/details/gtfkmkvzxy.html

TS:   s.match(/\d+/g)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxfixbtab.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.sysykeji.top/Article/details/gtxglebwvz.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.gotoacloud.top/Article/details/gtctakmino.html

Ruby: s.scan(/\d+/)
来源：http://dali.yongpay.top/Article/details/gtzpqlcoys.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.havefunace.top/Article/details/gtleweobej.html

[I03] 提取捕获分组
来源：http://dali.yj20258.top/Article/details/gtgnrdqipe.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yj20258.top/Article/details/gticpxtpqk.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.tanke756.top/Article/details/gtxwgbwhgl.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.shzxlz.cn/Article/details/gtcujyvbcb.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.gaohongyu789.top/Article/details/gtxevfdccg.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.ppjwa.cn/Article/details/gtvxqnawfm.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.ivvv.top/Article/details/gtpfjobmrl.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.birdmap.top/Article/details/gtsmgyxkbp.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.aizwys.cn/Article/details/gtsiqmyjlp.html

[I04] 正则替换
来源：http://dali.jqgfzy.top/Article/details/gtcvhsoprg.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.gaohongyu789.top/Article/details/gtoechxjbo.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.hongshengwenyu.top/Article/details/gtqfnlrvup.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jqgufenzy.top/Article/details/gtgjmianlp.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhoulong.xyz/Article/details/gtkasxcxfh.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.snrcjt.cn/Article/details/gtgrrrufvk.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.ppjwa.cn/Article/details/gtwxynhzvv.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtviozaarz.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.ppjwa.cn/Article/details/gtivznimuo.html

[I05] 按正则拆分
来源：http://dali.gotoacloud.top/Article/details/gtdxxzbxiw.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.ybcxt.top/Article/details/gtvwrobbkb.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.dianchejie.cn/Article/details/gtuwqojtxi.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.guannengcc.top/Article/details/gtztaiopdl.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.aizwys.cn/Article/details/gtdrzrfybf.html

Java: s.split("\\s*,\\s*")
来源：http://dali.shanyushiyangtech.top/Article/details/gttpsliuoz.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.wangdashe.top/Article/details/gtcmjmshds.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzidwqjjf.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.guowangkeji.top/Article/details/gtxrupecyi.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.pengpengdd.cyou/Article/details/gtlqxakuxy.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.kuanghao11.cn/Article/details/gtcwlmcniv.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.dashuyun.cn/Article/details/gtmacfwdji.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zdqjudy.top/Article/details/gtljmpxnui.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhoulong.xyz/Article/details/gtznvdjufy.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yuanzhike.top/Article/details/gtzmscuwjl.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.fzhhl.top/Article/details/gtyvaemjvv.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgflkcsxb.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.sufxvd.cn/Article/details/gtcuvedftm.html

[I07] 忽略大小写与多行模式
来源：http://dali.yj202588.top/Article/details/gthbfcuuwh.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.sufxvd.cn/Article/details/gtiegjqmoq.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.aibaodan.cn/Article/details/gtnzydejgm.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.redwolf501.top/Article/details/gtjgtjmrrh.html

TS:   /error/gim
来源：http://dali.guowangkeji.top/Article/details/gtxzuczbia.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.shuidangran.top/Article/details/gtpasqmqxa.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.sysykeji.top/Article/details/gtjuvdhjbe.html

Ruby: s.scan(/error/i)
来源：http://dali.zhiwuduotai.top/Article/details/gtyhhceqwi.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.hammf.cn/Article/details/gtyvxurmxp.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.havefunace.top/Article/details/gtagyngwaw.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.shzxlz.cn/Article/details/gtsnnljzhi.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yueranfly.top/Article/details/gtmgmmmugg.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhongyouzk.top/Article/details/gtzqwnizop.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtviftgkcr.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.nanxuanxn.top/Article/details/gtsnkypksn.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.dashuyun.cn/Article/details/gtepkplyyr.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.aizwys.cn/Article/details/gtvjtjtngz.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhiwuduotai.top/Article/details/gtinzhbvux.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtciinthkm.html

J. 日期与时间
来源：http://dali.ppjwa.cn/Article/details/gtwnwlwvmh.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtzmiszjgv.html

[J01] 获取当前时间
来源：http://dali.hysaishi.cn/Article/details/gthwkzabak.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwfglztdj.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.ehwqpu.com/Article/details/gtxzyihrau.html

JS:   new Date();  Date.now()
来源：http://dali.jianghu66.top/Article/details/gtgowxyvjo.html

TS:   new Date();  Date.now()
来源：http://dali.zdqjudy.top/Article/details/gtqwkcatbv.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.hnxiangtu.top/Article/details/gtqplfitkr.html

Go:   time.Now()
来源：http://dali.jqgufenzy.top/Article/details/gtgsbyffav.html

Ruby: Time.now
来源：http://dali.sxryk.cn/Article/details/gtbbonzcxf.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.snrcjt.cn/Article/details/gtewtcrhsh.html

[J02] 格式化输出
来源：http://dali.pengpengdd.cyou/Article/details/gtinvoaqmg.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yongpay.top/Article/details/gtwxqmipni.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yonumen.top/Article/details/gtueuvhfxa.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.ybcxt.top/Article/details/gtoddlwsfl.html

TS:   d.toISOString()
来源：http://dali.cdnleiting.top/Article/details/gtzunpogdb.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.hysaishi.cn/Article/details/gtndlqphza.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.hnqzz.top/Article/details/gtcrcfcaal.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yonumen.top/Article/details/gtidwdlgnj.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.svipenyu.cn/Article/details/gttsgnllsu.html

[J03] 字符串解析为日期
来源：http://dali.bjfxy.top/Article/details/gtranhrfpg.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.gotoacloud.top/Article/details/gttmepquxv.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.xinyue.icu/Article/details/gtisbohfcw.html

JS:   new Date("2024-01-02")
来源：http://dali.aizwys.cn/Article/details/gttwccvget.html

TS:   new Date("2024-01-02")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcjggeezu.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yuanzhike.top/Article/details/gthdjluxfd.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.wangdashe.top/Article/details/gtqqumcgse.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.shzxlz.cn/Article/details/gtfpdoyzad.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yueranfly.top/Article/details/gtakeeqlfd.html

[J04] 时间戳与日期互转
来源：http://dali.hnxiangtu.top/Article/details/gtqzaqfzlh.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.bjfxy.top/Article/details/gtpwhtdobh.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.hongshengwenyu.top/Article/details/gtateixskt.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxdmcfikk.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.guowangkeji.top/Article/details/gtldtgrtkd.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.c1oappe.top/Article/details/gtdlexampr.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.ydzc1.top/Article/details/gtzgmjfbqu.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.hongshengwenyu.top/Article/details/gtqsndklla.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.nanxinkj.top/Article/details/gtcygqiiwe.html

[J05] 时间加减（加 7 天）
来源：http://dali.meibo888.top/Article/details/gtukksbvpw.html

Py:   now + timedelta(days=7)
来源：http://dali.ivvv.top/Article/details/gthzhulrvy.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.tian-w.cn/Article/details/gthdhecaoj.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ydzc1.top/Article/details/gtadfddfgn.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yvedp.cn/Article/details/gtlbsndhtm.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.wangdashe.top/Article/details/gttikjalnb.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jinqigfzy.top/Article/details/gtbibzamuk.html

Ruby: Time.now + 7 * 86400
来源：http://dali.sweek.top/Article/details/gtrzjzcprh.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jlsjyb.cn/Article/details/gtxdgiiynd.html

[J06] 计算两时间之差
来源：http://dali.zhiwuduotai.top/Article/details/gtkhxvpqbh.html

Py:   (end - start).total_seconds()
来源：http://dali.nanxuanxn.top/Article/details/gtxegrwdhj.html

PHP:  $end->diff($start)->days;
来源：http://dali.tianlin.xyz/Article/details/gtianhdqha.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yueranfly.top/Article/details/gtcpdzyfub.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.guannengcc.top/Article/details/gtygxnshue.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.chenjidiqi.icu/Article/details/gtwxxpuzrh.html

Go:   end.Sub(start).Hours()
来源：http://dali.tanke756.top/Article/details/gtmlqoelxa.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdyqigavc.html

C#:   (end - start).TotalSeconds
来源：http://dali.yuxming.cn/Article/details/gtafjxfqtc.html

[J07] 比较两个日期
来源：http://dali.pengpengdd.cyou/Article/details/gtuyzkbqtj.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.ivvv.top/Article/details/gtrlawpucz.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.sysykeji.top/Article/details/gtpttsknif.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.nanxuanxn.top/Article/details/gtmydeolmt.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.tian-w.cn/Article/details/gtwycdvnam.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.ehwqpu.com/Article/details/gtfesmiumc.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.chenjidiqi.icu/Article/details/gthkawxvdp.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.316326.xyz/Article/details/gtiynzijnj.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.cucudq.cn/Article/details/gtudjriqtv.html

[J08] 提取年月日与星期
来源：http://dali.tanke756.top/Article/details/gtdcpddtgm.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.gogol.net.cn/Article/details/gtpvlgieyp.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.c1oappe.top/Article/details/gtpisdjghz.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.guowangkeji.top/Article/details/gtmwoblwsl.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.xziqi.cn/Article/details/gtxkqwwcwn.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yonumen.top/Article/details/gteaweedqo.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.316326.xyz/Article/details/gtatwnhdsw.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jqgufenzy.top/Article/details/gtrnrxdcad.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.gotoacloud.top/Article/details/gtubivalrx.html

[J09] 时区处理
来源：http://dali.jyoumei.cn/Article/details/gttzbdehgx.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.shzxlz.cn/Article/details/gtlknjuvea.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.iojbl.cn/Article/details/gtuapjdwam.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.aibaodan.cn/Article/details/gtccmbtmwn.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jqgufenzy.top/Article/details/gthlubtsjh.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.wangdashe.top/Article/details/gttzgryopd.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.ivvv.top/Article/details/gtamlmydgh.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.ybcxt.top/Article/details/gtskaxjscx.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yj20258.top/Article/details/gttrlpguny.html

[J10] 取今天 / 本月第一天
来源：http://dali.nanxuanxn.top/Article/details/gtxdbnplgv.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.redwolf501.top/Article/details/gtmltqkvqa.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.0kj1m.cn/Article/details/gtsmwowkpd.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.xuanzx.com/Article/details/gtoctkwsha.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.chenjidiqi.icu/Article/details/gttddhugva.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yj20258888.top/Article/details/gtlmhwsvcr.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.dashuyun.cn/Article/details/gtxsyosomp.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.hfpthk.cn/Article/details/gtcybhsgvw.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.nanxuanxn.top/Article/details/gtvqhbbjsv.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtrzjkxdnd.html

K. JSON 与序列化
来源：http://dali.meibo888.top/Article/details/gtgckviaqp.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtblzqowra.html

[K01] 对象转 JSON 字符串
来源：http://dali.hnxiangtu.top/Article/details/gtzztcdinv.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.jlsjyb.cn/Article/details/gttlvpsqux.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.birdmap.top/Article/details/gtfkbuujuy.html

JS:   JSON.stringify(obj)
来源：http://dali.yvedp.cn/Article/details/gteuyivfbk.html

TS:   JSON.stringify(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtnvvsadtk.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.meibo888.top/Article/details/gtengsuviq.html

Go:   json.Marshal(obj)
来源：http://dali.cqqwz.cn/Article/details/gtempqnjkb.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.cdnleiting.top/Article/details/gtovnsvqhn.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gtihiblzfv.html

[K02] JSON 字符串转对象
来源：http://dali.dianchejie.cn/Article/details/gtgxamdenh.html

Py:   json.loads(s)
来源：http://dali.hnqzz.top/Article/details/gtorwtdokz.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.gaohongyu789.top/Article/details/gthjoqsvne.html

JS:   JSON.parse(s)
来源：http://dali.ehwqpu.com/Article/details/gtunxehzmo.html

TS:   JSON.parse(s)
来源：http://dali.jinqigfzy.top/Article/details/gtvadfludp.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.quarkkingdee.top/Article/details/gtznorzizm.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.snrcjt.cn/Article/details/gtatkxjdxt.html

Ruby: JSON.parse(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtcwmrzeaj.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.hammf.cn/Article/details/gtdjwypofv.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.cashguo.top/Article/details/gtjrhhcfqi.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.aibaodan.cn/Article/details/gttqjdhsrf.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdsmumqqg.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.feifeiyinyue.top/Article/details/gtpeksdqmr.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.guowangkeji.top/Article/details/gterzwiovw.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.birdmap.top/Article/details/gtahftpdir.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yueranfly.top/Article/details/gtnpaetdfd.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.xinyue.icu/Article/details/gtxlxjyphg.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhixingplan.top/Article/details/gthasafbav.html

[K04] 读取 JSON 文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttblwfyqm.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.daxiang520.top/Article/details/gteglchigx.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.gogol.net.cn/Article/details/gtdzlkdwfq.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jqgufenzy.top/Article/details/gtnhlkuqlo.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.nanxinkj.top/Article/details/gtzynbkjrb.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jinghuilouyu.cn/Article/details/gtbiyzcogw.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.shzxlz.cn/Article/details/gtalyinjrz.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.bjfxy.top/Article/details/gtswxebiow.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yvedp.cn/Article/details/gtlbyqboxa.html

[K05] 深拷贝对象
来源：http://dali.jiagoushi.top/Article/details/gtkplnwujd.html

Py:   copy.deepcopy(obj)
来源：http://dali.yj202588.top/Article/details/gtihuyzqmv.html

PHP:  unserialize(serialize($obj));
来源：http://dali.meibo888.top/Article/details/gtmbudjowm.html

JS:   structuredClone(obj)
来源：http://dali.cdnleiting.top/Article/details/gtuevanuac.html

TS:   structuredClone(obj)
来源：http://dali.yonumen.top/Article/details/gtktbtlgyz.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.bjfxy.top/Article/details/gtjutyyyuf.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.guannengcc.top/Article/details/gtodtnvaue.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.wangdashe.top/Article/details/gthptrpxty.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.xziqi.cn/Article/details/gtknzdzrxf.html

[K06] 解析 URL 查询串
来源：http://dali.aizwys.cn/Article/details/gtptcdcjlx.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.cheryme.top/Article/details/gtbprasjuk.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.nanxinkj.top/Article/details/gtznflvhod.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.tian-w.cn/Article/details/gtechmscxw.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.chenjidiqi.icu/Article/details/gtwnonwftr.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.feifeiyinyue.top/Article/details/gthwcgfmtj.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.nanxinkj.top/Article/details/gtqmqeblvy.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.c1oappe.top/Article/details/gthzuluivy.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.tanke756.top/Article/details/gtfkpkpgdy.html

[K07] 进制转换
来源：http://dali.pycfn.com/Article/details/gtafxlgvjz.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yangfankeji.com/Article/details/gtzphbskws.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.c1oappe.top/Article/details/gtdwaturgj.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jinghuilouyu.cn/Article/details/gtlixjchhx.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.sweek.top/Article/details/gtfthrxumn.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwjthtwjb.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.nwbrower.top/Article/details/gtcwmbyyhx.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.guowangkeji.top/Article/details/gtradmezbt.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.birdmap.top/Article/details/gtgdikqdhs.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.9152youxi.cn/Article/details/gtwqsocdmt.html

Py:   pickle.dumps(obj)
来源：http://dali.jiagoushi.top/Article/details/gtyscpyqxl.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.ehwqpu.com/Article/details/gtroqidhdj.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.hnqzz.top/Article/details/gtkiicewde.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.redwolf501.top/Article/details/gtunkugbsb.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.gzhubu.top/Article/details/gttnffndvt.html

Go:   encoding/gob
来源：http://dali.yanxiufei.cn/Article/details/gtcqpyjzhr.html

Ruby: Marshal.dump(obj)
来源：http://dali.ydzc1.top/Article/details/gtifyuebap.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yj202588.top/Article/details/gtbfljjate.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtckeqxfmh.html

L. 网络请求
来源：http://dali.bjfxy.top/Article/details/gttmyqsefp.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtmqhimkjp.html

[L01] 发送 GET 请求
来源：http://dali.havefunace.top/Article/details/gtiuztpesw.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yj202588.top/Article/details/gtgvzkdeop.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.shangyingyoupin.top/Article/details/gtmukhxspe.html

JS:   await fetch(url)
来源：http://dali.birdmap.top/Article/details/gtmmbupojg.html

TS:   await fetch(url)
来源：http://dali.guannengcc.top/Article/details/gtokdasvpb.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.hnqzz.top/Article/details/gtjzjlsnps.html

Go:   resp, err := http.Get(url)
来源：http://dali.quarkkingdee.top/Article/details/gtpvwknpjy.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.ehwqpu.com/Article/details/gtomlxbkou.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.gzhubu.top/Article/details/gtdfnsujiv.html

[L02] 发送 POST JSON
来源：http://dali.yanxiufei.cn/Article/details/gtkqzidpdf.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.gaohongyu789.top/Article/details/gtppevjdmy.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.gzhubu.top/Article/details/gtrokeqamo.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xuetiantiany.cn/Article/details/gtynywntdi.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yueranfly.top/Article/details/gtyldtnpzv.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.shangyingyoupin.top/Article/details/gtbyvluegu.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.meibo888.top/Article/details/gtiudtbydq.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.xuetiantiany.cn/Article/details/gtlsoqvaxo.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhijiandao.cn/Article/details/gtuztztclu.html

[L03] 设置自定义请求头
来源：http://dali.hammf.cn/Article/details/gtgtovofgd.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jinqigufen.top/Article/details/gtikscofcx.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.redwolf501.top/Article/details/gtfhfgmyvn.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yvedp.cn/Article/details/gtvpthdcuj.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.guannengcc.top/Article/details/gtuydslxgb.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.haohaochexian.top/Article/details/gtrzhqnzhk.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.snrcjt.cn/Article/details/gtruwgyflu.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.dianchejie.cn/Article/details/gtkvgratlg.html


<!-- 参考信息 -->