代发 wailian999

JS:   e.message;  e.stack
来源：http://dali.nanxuanxn.top/Article/details/gtabgywfbk.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.smart0.xyz/Article/details/gtffbzzpcu.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.nanxuanxn.top/Article/details/gtlnrfptbx.html

Go:   err.Error()
来源：http://dali.nanxuanxn.top/Article/details/gtppnjozvp.html

Ruby: e.message;  e.backtrace
来源：http://dali.havefunace.top/Article/details/gttvpxxeuw.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yonumen.top/Article/details/gtmoxtofcs.html

[H09] 带错误码的异常
来源：http://dali.shangyingyoupin.top/Article/details/gtvsjyeyeg.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.daria6918.cn/Article/details/gtiutfddwg.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.hnqzz.top/Article/details/gtobfqidbw.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zdqjudy.top/Article/details/gtywessbbu.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhixingplan.top/Article/details/gtvsowkdln.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.cqqwz.cn/Article/details/gtsedstgqe.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhiwuduotai.top/Article/details/gttvtlwcld.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jyoumei.cn/Article/details/gtoqtonmwt.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhongyouzk.top/Article/details/gtmvdlzdyg.html

[H10] 资源自动释放
来源：http://dali.kuanghao11.cn/Article/details/gtzlgnztaa.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttbyzsdxo.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.hnxiangtu.top/Article/details/gtefwkwcyt.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinqigufen.top/Article/details/gtedsapagy.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.feifeiyinyue.top/Article/details/gtnoruccno.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.gogol.net.cn/Article/details/gtnhhemolq.html

Go:   defer f.Close()
来源：http://dali.tanke756.top/Article/details/gtxzhqrokb.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhongyouzk.top/Article/details/gtrvwrtyqa.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gtykjmejfo.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtxdjcxbfy.html

I. 正则表达式
来源：http://dali.tian-w.cn/Article/details/gtycsvmfya.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtzwaxagvc.html

[I01] 判断是否匹配
来源：http://dali.yangfankeji.com/Article/details/gtziggholi.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.aizwys.cn/Article/details/gtpoxgnpgv.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gtfrffvjuz.html

JS:   /\d+/.test(s)
来源：http://dali.ppjwa.cn/Article/details/gtffckqgvp.html

TS:   /\d+/.test(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnyiaqkcr.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.hfpthk.cn/Article/details/gtbanlncnu.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpcsafgok.html

Ruby: s.match?(/\d+/)
来源：http://dali.jyoumei.cn/Article/details/gtvqkqbysm.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.0kj1m.cn/Article/details/gtwiynnoky.html

[I02] 提取所有匹配
来源：http://dali.birdmap.top/Article/details/gtdkxclrfg.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yonumen.top/Article/details/gtbjosxzhg.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.gzhubu.top/Article/details/gtiimaswyq.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.quarkkingdee.top/Article/details/gtjrfbnyeb.html

TS:   s.match(/\d+/g)
来源：http://dali.yj20258888.top/Article/details/gtzuxsripj.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yvedp.cn/Article/details/gtcsaesozi.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.ehwqpu.com/Article/details/gtindparcb.html

Ruby: s.scan(/\d+/)
来源：http://dali.guowangkeji.top/Article/details/gtybgfhwlm.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jlsjyb.cn/Article/details/gtqbelhzbn.html

[I03] 提取捕获分组
来源：http://dali.xylfe.cn/Article/details/gtwxofenft.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.ybcxt.top/Article/details/gtivbmbrkl.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.dashuyun.cn/Article/details/gtadylsfow.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jyoumei.cn/Article/details/gtblvgmqlq.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.shzxlz.cn/Article/details/gtzoznkolb.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yuanzhike.top/Article/details/gtsytpofgk.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jqgufenzy.top/Article/details/gtuwenuafk.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.birdmap.top/Article/details/gtgroycirq.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.xziqi.cn/Article/details/gtzjwyuqbl.html

[I04] 正则替换
来源：http://dali.gaohongyu789.top/Article/details/gtrfwadhlu.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.guannengcc.top/Article/details/gtxnabxcku.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmwtfilgi.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jqgfzy.top/Article/details/gtsoophttx.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.ydzc1.top/Article/details/gtmagvabpb.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.mhx1999.top/Article/details/gtgrwbedjr.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.chenzaomai.com/Article/details/gtzkjpjdoe.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.smart0.xyz/Article/details/gtphxoqcei.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.hfpthk.cn/Article/details/gtoeruquxi.html

[I05] 按正则拆分
来源：http://dali.yj202588.top/Article/details/gtpnuxzcrn.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhoulong.xyz/Article/details/gttqzrabow.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.sxryk.cn/Article/details/gtmdsnpodf.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyuuxmgag.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.cheryme.top/Article/details/gtpjtedkgn.html

Java: s.split("\\s*,\\s*")
来源：http://dali.cdnleiting.top/Article/details/gtokvapnre.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsxyjwoxq.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsfxbndxl.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.9152youxi.cn/Article/details/gtrhwzfdmq.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.xuetiantiany.cn/Article/details/gtdaxqgvtr.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.shzxlz.cn/Article/details/gtqtpgrgvc.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.ppjwa.cn/Article/details/gtdqxduxna.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.snrcjt.cn/Article/details/gtjnkldzgt.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvwoinxev.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.shanyushiyangtech.top/Article/details/gthgyoncul.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.9152youxi.cn/Article/details/gtjqwudxbm.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.dianchejie.cn/Article/details/gtspnrwygf.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.dianchejie.cn/Article/details/gtmaalduzs.html

[I07] 忽略大小写与多行模式
来源：http://dali.fzhhl.top/Article/details/gtgceuoofp.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jinqigfzy.top/Article/details/gtbqezhxdf.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.fzhhl.top/Article/details/gtrigtecnt.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhaomingkeji.xyz/Article/details/gthzqutzto.html

TS:   /error/gim
来源：http://dali.kuanghao11.cn/Article/details/gtombusgts.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jinghuilouyu.cn/Article/details/gtqxjsncwh.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhiwuduotai.top/Article/details/gtcpjftdid.html

Ruby: s.scan(/error/i)
来源：http://dali.gaohongyu789.top/Article/details/gtisehhvjt.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.hammf.cn/Article/details/gtfelhxbua.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.shangyingyoupin.top/Article/details/gtkhovyjic.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.mhx1999.top/Article/details/gtdeapmqls.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.gzhubu.top/Article/details/gtlzeeltcf.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.dashuyun.cn/Article/details/gtdccpstns.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hfpthk.cn/Article/details/gtecehzvdy.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.hywenlv.cn/Article/details/gtkspljesz.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.aibaodan.cn/Article/details/gtipkkabpc.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.daxiang520.top/Article/details/gtttnqkjlo.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.tianlin.xyz/Article/details/gtdvgodtws.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtemczcgox.html

J. 日期与时间
来源：http://dali.zhixingplan.top/Article/details/gtypxznluf.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtyrqeshqi.html

[J01] 获取当前时间
来源：http://dali.fengsongda.top/Article/details/gtnbrhbkdw.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yuxming.cn/Article/details/gtpbutpvcw.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.aibaodan.cn/Article/details/gtveuwpkyn.html

JS:   new Date();  Date.now()
来源：http://dali.cheryme.top/Article/details/gtcwsrtjnc.html

TS:   new Date();  Date.now()
来源：http://dali.ehwqpu.com/Article/details/gtdhuzcybb.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.ybcxt.top/Article/details/gtqfpwyajs.html

Go:   time.Now()
来源：http://dali.hongshengwenyu.top/Article/details/gtpanlsryr.html

Ruby: Time.now
来源：http://dali.xuanzx.com/Article/details/gtvbdklmvu.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.sysykeji.top/Article/details/gtobmxiwlx.html

[J02] 格式化输出
来源：http://dali.yvedp.cn/Article/details/gtzxieaioe.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jiagoushi.top/Article/details/gtwlqsnqgi.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.316326.xyz/Article/details/gthrfpyjja.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.redwolf501.top/Article/details/gtojhjtouz.html

TS:   d.toISOString()
来源：http://dali.hammf.cn/Article/details/gttmgdnbaa.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.dashuyun.cn/Article/details/gtpinbyrvi.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.316326.xyz/Article/details/gthkpsfqem.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shuidangran.top/Article/details/gtuqfyqhnw.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.sysykeji.top/Article/details/gtkmhungsl.html

[J03] 字符串解析为日期
来源：http://dali.zhiwuduotai.top/Article/details/gtlmklezbm.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.hnxiangtu.top/Article/details/gtqoqqmfjb.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.redwolf501.top/Article/details/gtmuqzjbnj.html

JS:   new Date("2024-01-02")
来源：http://dali.chenlongwang.top/Article/details/gtltinmsgs.html

TS:   new Date("2024-01-02")
来源：http://dali.redwolf501.top/Article/details/gtrtcstght.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.wangshuangyany.cn/Article/details/gtqspslody.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.birdmap.top/Article/details/gtijekiuep.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.yj20258.top/Article/details/gtqneknkxh.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.sxryk.cn/Article/details/gtwaaocdfr.html

[J04] 时间戳与日期互转
来源：http://dali.hysaishi.cn/Article/details/gtdhbqtyfb.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.0kj1m.cn/Article/details/gtbizifiah.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.c1oappe.top/Article/details/gtkbbibgkr.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.cheryme.top/Article/details/gtknlpbkxd.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.cqqwz.cn/Article/details/gtgmutljhv.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.daxiang520.top/Article/details/gtpvsezcqk.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.ybcxt.top/Article/details/gtnifhqwkp.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.zhongyouzk.top/Article/details/gtjervtisf.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.vqdsnc.cn/Article/details/gtfqpznwlm.html

[J05] 时间加减（加 7 天）
来源：http://dali.yangfankeji.com/Article/details/gterubsrbp.html

Py:   now + timedelta(days=7)
来源：http://dali.gzhubu.top/Article/details/gtjhftlver.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.sxryk.cn/Article/details/gtdktsgsic.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.pycfn.com/Article/details/gtjgdefihy.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jinqigfzy.top/Article/details/gttohviygv.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.cashguo.top/Article/details/gtosgmrdsu.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.hywenlv.cn/Article/details/gtmpgjvmxn.html

Ruby: Time.now + 7 * 86400
来源：http://dali.tian-w.cn/Article/details/gtvkgtwcml.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.sxryk.cn/Article/details/gtkgvetpdd.html

[J06] 计算两时间之差
来源：http://dali.jqgufenzy.top/Article/details/gtehhsdaec.html

Py:   (end - start).total_seconds()
来源：http://dali.guannengcc.top/Article/details/gtyxiauscb.html

PHP:  $end->diff($start)->days;
来源：http://dali.jianghu66.top/Article/details/gtpzzldars.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.hnxiangtu.top/Article/details/gtrfeojoct.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.iojbl.cn/Article/details/gtdkezwret.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.dashuyun.cn/Article/details/gthzqzidpo.html

Go:   end.Sub(start).Hours()
来源：http://dali.xinyue.icu/Article/details/gtzdnwepnl.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbazpgkzk.html

C#:   (end - start).TotalSeconds
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtslrnjbuq.html

[J07] 比较两个日期
来源：http://dali.yueranfly.top/Article/details/gttcbatfyy.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.jlsjyb.cn/Article/details/gtqkykbaqn.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.sweek.top/Article/details/gtxcqhycve.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhengqikj.top/Article/details/gtsikrchzc.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.dianchejie.cn/Article/details/gtpbcglcuk.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.tian-w.cn/Article/details/gtyxccwobd.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhijiandao.cn/Article/details/gtznaqykvi.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yueranfly.top/Article/details/gtoabrxdos.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.shuidangran.top/Article/details/gtckhxpxsp.html

[J08] 提取年月日与星期
来源：http://dali.shzxlz.cn/Article/details/gtwkqezicl.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.0kj1m.cn/Article/details/gtixalnocr.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.gzhubu.top/Article/details/gtvjymputm.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.wangdashe.top/Article/details/gtatqjrjgs.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.sufxvd.cn/Article/details/gtlkackery.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.aibaodan.cn/Article/details/gtusbyqetd.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hammf.cn/Article/details/gtspxiiepa.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.cqqwz.cn/Article/details/gtyfqkcruq.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.sysykeji.top/Article/details/gtwlcgjyuw.html

[J09] 时区处理
来源：http://dali.hammf.cn/Article/details/gtlntxtcyn.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.sxryk.cn/Article/details/gtayaqxfbh.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.hnqzz.top/Article/details/gtrcwbonkm.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cheryme.top/Article/details/gtqmcxxpdd.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.daxiang520.top/Article/details/gtgnrqinjk.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yj20258888.top/Article/details/gtugeayckr.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthtwzcbru.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhijiandao.cn/Article/details/gtqbwtbhta.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.zhengqikj.top/Article/details/gtyzjsvzah.html

[J10] 取今天 / 本月第一天
来源：http://dali.jlsjyb.cn/Article/details/gtynmokvlg.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.sufxvd.cn/Article/details/gtvzdhawow.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.birdmap.top/Article/details/gtalfvjwqj.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.hammf.cn/Article/details/gtrrurqvva.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.cqqwz.cn/Article/details/gtanjgvhdt.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.fengsongda.top/Article/details/gtvmajchdb.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.hywenlv.cn/Article/details/gtnzvfobqw.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.gzhubu.top/Article/details/gtiiddrgyu.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.cucudq.cn/Article/details/gtxqypqpha.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtuvtxczfg.html

K. JSON 与序列化
来源：http://dali.hammf.cn/Article/details/gtestonkxr.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtepuvmslk.html

[K01] 对象转 JSON 字符串
来源：http://dali.wangshuangyany.cn/Article/details/gtyxzxdyax.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.ydzc1.top/Article/details/gtcbopumbq.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.aizwys.cn/Article/details/gtwwpguibg.html

JS:   JSON.stringify(obj)
来源：http://dali.hysaishi.cn/Article/details/gtlztldzha.html

TS:   JSON.stringify(obj)
来源：http://dali.nwbrower.top/Article/details/gtyextwvus.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.hnqzz.top/Article/details/gtskqhnedi.html

Go:   json.Marshal(obj)
来源：http://dali.bjfxy.top/Article/details/gtuqzmraiz.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hammf.cn/Article/details/gtnrwsmbuq.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.meibo888.top/Article/details/gtefperepf.html

[K02] JSON 字符串转对象
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlkwazmsk.html

Py:   json.loads(s)
来源：http://dali.kuanghao11.cn/Article/details/gteqrclyvv.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.cashguo.top/Article/details/gtpnrdinez.html

JS:   JSON.parse(s)
来源：http://dali.316326.xyz/Article/details/gtasbnjgyw.html

TS:   JSON.parse(s)
来源：http://dali.shuidangran.top/Article/details/gtbknlayid.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.cdnleiting.top/Article/details/gtjpznuivk.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.cdnleiting.top/Article/details/gtaszbqjow.html

Ruby: JSON.parse(s)
来源：http://dali.sweek.top/Article/details/gtsmaqukhc.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yangfankeji.com/Article/details/gtnwluvdmj.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yvedp.cn/Article/details/gtevytyuuo.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.xuanzx.com/Article/details/gtgcxckoyt.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkqfdnjaq.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.c1oappe.top/Article/details/gtlbxtjori.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yuxming.cn/Article/details/gtvcdxuman.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.mhx1999.top/Article/details/gthbsoijvw.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.hongshengwenyu.top/Article/details/gtwbprvtsl.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.aizwys.cn/Article/details/gtptcirnar.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.gaohongyu789.top/Article/details/gtzuusszfr.html

[K04] 读取 JSON 文件
来源：http://dali.yanxiufei.cn/Article/details/gtvrloflbv.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.nanxinkj.top/Article/details/gtapebbags.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.gogol.net.cn/Article/details/gterxwcthy.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zdqjudy.top/Article/details/gtuswcfalp.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.haohaochexian.top/Article/details/gtprwycqme.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.cashguo.top/Article/details/gtgdtvujzb.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.cucudq.cn/Article/details/gtwdbhmuby.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.xuetiantiany.cn/Article/details/gthulynaye.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.sysykeji.top/Article/details/gtilirwsci.html

[K05] 深拷贝对象
来源：http://dali.hammf.cn/Article/details/gtrlotmvch.html

Py:   copy.deepcopy(obj)
来源：http://dali.cdnleiting.top/Article/details/gtbcxttzad.html

PHP:  unserialize(serialize($obj));
来源：http://dali.xuanzx.com/Article/details/gtqpqydpxz.html

JS:   structuredClone(obj)
来源：http://dali.hnqzz.top/Article/details/gtmdfbydws.html

TS:   structuredClone(obj)
来源：http://dali.redwolf501.top/Article/details/gtepvehtoh.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.cdnleiting.top/Article/details/gtjhcqakko.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.sufxvd.cn/Article/details/gtymfrtree.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.svipenyu.cn/Article/details/gtswymrjcw.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zdqjudy.top/Article/details/gtqlphuump.html

[K06] 解析 URL 查询串
来源：http://dali.tianlin.xyz/Article/details/gticsgbddz.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.pycfn.com/Article/details/gtusgqqylw.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.xziqi.cn/Article/details/gtfkaoawhr.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yanxiufei.cn/Article/details/gtmjrzpwyk.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.birdmap.top/Article/details/gtdpyqjzgf.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.aizwys.cn/Article/details/gtbqroseen.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.andypj.xyz/Article/details/gtxlvoqgro.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jlsjyb.cn/Article/details/gtpsardcyc.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.chenlongwang.top/Article/details/gtsjnafvae.html

[K07] 进制转换
来源：http://dali.pycfn.com/Article/details/gtvsghgzed.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.nanxuanxn.top/Article/details/gtrbwhikxa.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yuanzhike.top/Article/details/gthltwvpwv.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.chenzaomai.com/Article/details/gtjvdbrquf.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.ivvv.top/Article/details/gtwwqdrjug.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.pengpengdd.cyou/Article/details/gtuchagfbm.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.ybcxt.top/Article/details/gtvoxdqzvs.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.ehwqpu.com/Article/details/gtvxffkaso.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.sysykeji.top/Article/details/gtdprzkwga.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.guowangkeji.top/Article/details/gtxizifzzz.html

Py:   pickle.dumps(obj)
来源：http://dali.shuidangran.top/Article/details/gthsiksqom.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcabfpiwn.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.chenzaomai.com/Article/details/gtgmgcuhzu.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.tian-w.cn/Article/details/gtghaehymd.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.svipenyu.cn/Article/details/gtqofjuogo.html

Go:   encoding/gob
来源：http://dali.ydzc1.top/Article/details/gtovfescvr.html

Ruby: Marshal.dump(obj)
来源：http://dali.sufxvd.cn/Article/details/gtsncugsgf.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jinqigufen.top/Article/details/gtnmlrdxhv.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtolfhounw.html

L. 网络请求
来源：http://dali.xziqi.cn/Article/details/gtnbsndrjg.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtbsbgkvfe.html

[L01] 发送 GET 请求
来源：http://dali.shzxlz.cn/Article/details/gtribqedjc.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvvolkppl.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.snrcjt.cn/Article/details/gtqoiwxxbq.html

JS:   await fetch(url)
来源：http://dali.zhongyouzk.top/Article/details/gtjkmovpey.html

TS:   await fetch(url)
来源：http://dali.sufxvd.cn/Article/details/gtdnpqycik.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.chenzaomai.com/Article/details/gtapqeipns.html

Go:   resp, err := http.Get(url)
来源：http://dali.chenzaomai.com/Article/details/gtzrzuxcjq.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jinqigufen.top/Article/details/gtjstubuci.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.c1oappe.top/Article/details/gthjiypavs.html

[L02] 发送 POST JSON
来源：http://dali.yonumen.top/Article/details/gtcqccthbt.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.pycfn.com/Article/details/gtywocwcuz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.sxryk.cn/Article/details/gtvixthzxv.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.fzhhl.top/Article/details/gtgltvcrlt.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.316326.xyz/Article/details/gttzlgvkgs.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.hnqzz.top/Article/details/gtfvqnkjok.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.sxryk.cn/Article/details/gtxovuglzo.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.redwolf501.top/Article/details/gtimhkjwqm.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.mhx1999.top/Article/details/gtaxvwckau.html

[L03] 设置自定义请求头
来源：http://dali.mhx1999.top/Article/details/gttungczpu.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.chenlongwang.top/Article/details/gtdlizuram.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.ivvv.top/Article/details/gtkmsczuyj.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jianghu66.top/Article/details/gtjoruqozu.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gzhubu.top/Article/details/gtjqiaoaqn.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.shangyingyoupin.top/Article/details/gtcprtdzty.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.sysykeji.top/Article/details/gtlsxyruic.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.guowangkeji.top/Article/details/gtmhgeblbr.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.haohaochexian.top/Article/details/gttzcmkwpx.html

[L04] 设置超时
来源：http://dali.ehwqpu.com/Article/details/gttdrmvecu.html

Py:   requests.get(url, timeout=5)
来源：http://dali.tanke756.top/Article/details/gtgrdpptsn.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.ydzc1.top/Article/details/gteaeolpqg.html


<!-- 参考信息 -->