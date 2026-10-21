代发 wailian999

JS:   e.message;  e.stack
来源：http://dali.yuxming.cn/Article/details/gttcaxojvc.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jinqigfzy.top/Article/details/gtdefaztmn.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.316326.xyz/Article/details/gtjlxlryup.html

Go:   err.Error()
来源：http://dali.guannengcc.top/Article/details/gtxwxvvlpy.html

Ruby: e.message;  e.backtrace
来源：http://dali.cheryme.top/Article/details/gtgwkkxgol.html

C#:   e.Message;  e.StackTrace
来源：http://dali.andypj.xyz/Article/details/gtaqxugtym.html

[H09] 带错误码的异常
来源：http://dali.hfpthk.cn/Article/details/gtduxqxkzd.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.chenjidiqi.icu/Article/details/gtvgtlqcsj.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.0kj1m.cn/Article/details/gtomnmtavz.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.meibo888.top/Article/details/gtuylzmazu.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.bjfxy.top/Article/details/gtdvleisus.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yongpay.top/Article/details/gtkkfkeoui.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.xuanzx.com/Article/details/gtgkscuhug.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.feifeiyinyue.top/Article/details/gtqhdvphem.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.haohaochexian.top/Article/details/gtocqrwkzg.html

[H10] 资源自动释放
来源：http://dali.cheryme.top/Article/details/gtasqfdgin.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.guannengcc.top/Article/details/gttlqfbndb.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.xinyue.icu/Article/details/gtkywsvcfi.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmhiiwdqf.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.wangdashe.top/Article/details/gtakbvoxfa.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.gotoacloud.top/Article/details/gtspktuveg.html

Go:   defer f.Close()
来源：http://dali.redwolf501.top/Article/details/gtywtedxxs.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.xuetiantiany.cn/Article/details/gtfzugktxs.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gtyuvisjck.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtkfmmkiyx.html

I. 正则表达式
来源：http://dali.smart0.xyz/Article/details/gtdanjvlet.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtbuwpqhaa.html

[I01] 判断是否匹配
来源：http://dali.ybcxt.top/Article/details/gtuxfpfxtx.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.shangyingyoupin.top/Article/details/gtlvpjeizr.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jqgufenzy.top/Article/details/gtbeervcoh.html

JS:   /\d+/.test(s)
来源：http://dali.hnxiangtu.top/Article/details/gtihuvhkie.html

TS:   /\d+/.test(s)
来源：http://dali.yuxming.cn/Article/details/gtcwpbucfi.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.sysykeji.top/Article/details/gtylpyktuv.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhoulong.xyz/Article/details/gtrydclwje.html

Ruby: s.match?(/\d+/)
来源：http://dali.xinyue.icu/Article/details/gtkwhaxymi.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.wangshuangyany.cn/Article/details/gtjaiuhtvl.html

[I02] 提取所有匹配
来源：http://dali.xylfe.cn/Article/details/gtnrbaakrv.html

Py:   re.findall(r"\d+", s)
来源：http://dali.gzhubu.top/Article/details/gtistndpnj.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtathvhsps.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.hfpthk.cn/Article/details/gtnwgxjqda.html

TS:   s.match(/\d+/g)
来源：http://dali.yongpay.top/Article/details/gtzlrnzcqf.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yongpay.top/Article/details/gtknvtfebf.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.xuanzx.com/Article/details/gtboakwgkt.html

Ruby: s.scan(/\d+/)
来源：http://dali.jiagoushi.top/Article/details/gttxrfhzmx.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yuanzhike.top/Article/details/gtfdoqsemz.html

[I03] 提取捕获分组
来源：http://dali.yvedp.cn/Article/details/gtpablgcvi.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.hnqzz.top/Article/details/gtdqrhcppa.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.fzhhl.top/Article/details/gterbhuepg.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.shanyushiyangkeji.top/Article/details/gttmrmfylt.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.mhx1999.top/Article/details/gtzvsjukep.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.ydzc1.top/Article/details/gtfjbckwif.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.cheryme.top/Article/details/gtnybuxqjg.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.chenlongwang.top/Article/details/gtirfqzabk.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.hongshengwenyu.top/Article/details/gtmjyuhvxu.html

[I04] 正则替换
来源：http://dali.xylfe.cn/Article/details/gtzggyyhtl.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.cucudq.cn/Article/details/gtnxihaaij.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.haohaochexian.top/Article/details/gtcclqlmva.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.shuidangran.top/Article/details/gtylnqwkjy.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.shzxlz.cn/Article/details/gtgoqjlbyk.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.shanyushiyangtech.top/Article/details/gtcehnkogv.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jinghuilouyu.cn/Article/details/gtjusfmltq.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhixingplan.top/Article/details/gtowpfimlo.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.xziqi.cn/Article/details/gtxdkqeuqq.html

[I05] 按正则拆分
来源：http://dali.hammf.cn/Article/details/gtlgphxyup.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.redwolf501.top/Article/details/gturvsocav.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.guannengcc.top/Article/details/gtmegxovoq.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.chenjidiqi.icu/Article/details/gtyqgdmxgp.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.xinyue.icu/Article/details/gtelfoatxe.html

Java: s.split("\\s*,\\s*")
来源：http://dali.jiagoushi.top/Article/details/gtlgvckubm.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.guannengcc.top/Article/details/gthgaiolov.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhixingplan.top/Article/details/gtptxrkqzv.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.gotoacloud.top/Article/details/gtdiofjenz.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.haohaochexian.top/Article/details/gtnprylxxy.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.nanxinkj.top/Article/details/gtpilksude.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jqgufenzy.top/Article/details/gtkdwckpqb.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ybcxt.top/Article/details/gtnobkrzsi.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.dashuyun.cn/Article/details/gtnxwpsset.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.9152youxi.cn/Article/details/gtggfkmjhv.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jinyuanbaomall.cn/Article/details/gtemjnylzz.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.ppjwa.cn/Article/details/gtipcngxms.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jyoumei.cn/Article/details/gtpudmljgc.html

[I07] 忽略大小写与多行模式
来源：http://dali.c1oappe.top/Article/details/gtitdqabyi.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.redwolf501.top/Article/details/gtzgprwauf.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.gogol.net.cn/Article/details/gtnjwetwcc.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.ivvv.top/Article/details/gtdcqogacp.html

TS:   /error/gim
来源：http://dali.sufxvd.cn/Article/details/gtlpfoapdv.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbdzllqcz.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.mhx1999.top/Article/details/gthradasyb.html

Ruby: s.scan(/error/i)
来源：http://dali.vqdsnc.cn/Article/details/gttuyuivow.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.xuanzx.com/Article/details/gtpibgsoby.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.chenjidiqi.icu/Article/details/gtmfptjxri.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.andypj.xyz/Article/details/gtzdalzvuk.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.wangdashe.top/Article/details/gtbevxyfxf.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hammf.cn/Article/details/gtxgozppvi.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.chenlongwang.top/Article/details/gtaampuqfa.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.cheryme.top/Article/details/gtcemxexgs.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yonumen.top/Article/details/gtgzvkdjhc.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.316326.xyz/Article/details/gtodqakjnz.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.xuetiantiany.cn/Article/details/gtxtwesogh.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtusllygbe.html

J. 日期与时间
来源：http://dali.cheryme.top/Article/details/gtzuznzify.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtqlwziaqd.html

[J01] 获取当前时间
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcyramkbl.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.gaohongyu789.top/Article/details/gtumklybza.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.hfpthk.cn/Article/details/gtugiafagp.html

JS:   new Date();  Date.now()
来源：http://dali.9152youxi.cn/Article/details/gtljkeazaz.html

TS:   new Date();  Date.now()
来源：http://dali.nanxinkj.top/Article/details/gtzsxxbtos.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.xylfe.cn/Article/details/gtzwhvzvhh.html

Go:   time.Now()
来源：http://dali.cucudq.cn/Article/details/gtzovylwyw.html

Ruby: Time.now
来源：http://dali.shzxlz.cn/Article/details/gtbwkgijtb.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.tanke756.top/Article/details/gtqdicheyu.html

[J02] 格式化输出
来源：http://dali.cucudq.cn/Article/details/gtqvoqitav.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.shanyushiyangtech.top/Article/details/gtfjeqnrrf.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.cucudq.cn/Article/details/gtfvauievc.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yj20258888.top/Article/details/gtjosmeshr.html

TS:   d.toISOString()
来源：http://dali.yj202588.top/Article/details/gtwaxkoczi.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.jinghuilouyu.cn/Article/details/gtxrdifohu.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yj20258888.top/Article/details/gtbfieeknc.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.c1oappe.top/Article/details/gtoiadyipm.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhixingplan.top/Article/details/gtsmhokndt.html

[J03] 字符串解析为日期
来源：http://dali.jlsjyb.cn/Article/details/gtfdfxkmov.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.ybcxt.top/Article/details/gtxjbvlsea.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.sysykeji.top/Article/details/gtdkrsvohf.html

JS:   new Date("2024-01-02")
来源：http://dali.zhengqikj.top/Article/details/gtatewotag.html

TS:   new Date("2024-01-02")
来源：http://dali.hammf.cn/Article/details/gthvgfahrq.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yj20258888.top/Article/details/gtiwdsneli.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.xziqi.cn/Article/details/gtpevvedtk.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.guowangkeji.top/Article/details/gtwlkqfrxu.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.andypj.xyz/Article/details/gtekcoixjf.html

[J04] 时间戳与日期互转
来源：http://dali.ywan-chungtsiang.top/Article/details/gtngidwujl.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.hnxiangtu.top/Article/details/gtgfbcrwqq.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.redwolf501.top/Article/details/gttwzwdaqo.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.kuanghao11.cn/Article/details/gtixbnlttr.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgijjazub.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.zhongyouzk.top/Article/details/gtrrahzplx.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.sxryk.cn/Article/details/gtthmfmlbm.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.aizwys.cn/Article/details/gtmaexzgub.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.snrcjt.cn/Article/details/gtboiteptm.html

[J05] 时间加减（加 7 天）
来源：http://dali.havefunace.top/Article/details/gtyxvhbsgl.html

Py:   now + timedelta(days=7)
来源：http://dali.0kj1m.cn/Article/details/gtwltioiya.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yonumen.top/Article/details/gtqagizump.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shangyingyoupin.top/Article/details/gtzutfiqgd.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.chenlongwang.top/Article/details/gtrfxcdjbx.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yueranfly.top/Article/details/gtatyasomp.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.havefunace.top/Article/details/gtpvomshmn.html

Ruby: Time.now + 7 * 86400
来源：http://dali.kuanghao11.cn/Article/details/gtjqwaenqc.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.fzhhl.top/Article/details/gtkgmdtvls.html

[J06] 计算两时间之差
来源：http://dali.tian-w.cn/Article/details/gtvtodiprp.html

Py:   (end - start).total_seconds()
来源：http://dali.daxiang520.top/Article/details/gtrsdkjqxb.html

PHP:  $end->diff($start)->days;
来源：http://dali.hfpthk.cn/Article/details/gtobmqzufg.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zhixingplan.top/Article/details/gtsakbgcbi.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.hongshengwenyu.top/Article/details/gtraqmngza.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.redwolf501.top/Article/details/gtccgepzrl.html

Go:   end.Sub(start).Hours()
来源：http://dali.jyoumei.cn/Article/details/gtzgbafvya.html

Ruby: end - start                 # 返回秒数
来源：http://dali.iojbl.cn/Article/details/gtvumhxocx.html

C#:   (end - start).TotalSeconds
来源：http://dali.hnqzz.top/Article/details/gtfhocugmw.html

[J07] 比较两个日期
来源：http://dali.yangfankeji.com/Article/details/gtbrbaogqh.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.dashuyun.cn/Article/details/gtezlvehdg.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.snrcjt.cn/Article/details/gtxffdzbca.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.hammf.cn/Article/details/gtkubuwfdp.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.fengsongda.top/Article/details/gtyzvjnppv.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.cucudq.cn/Article/details/gtaavehyyz.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.wangshuangyany.cn/Article/details/gtoydwpnqw.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.fzhhl.top/Article/details/gtxtjjqkuj.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.9152youxi.cn/Article/details/gtqrexbtud.html

[J08] 提取年月日与星期
来源：http://dali.xylfe.cn/Article/details/gtuoqtnxpw.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yuanzhike.top/Article/details/gtxtwwejwv.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.quarkkingdee.top/Article/details/gtxcrbrtvc.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.shzxlz.cn/Article/details/gtojopduxk.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.pengpengdd.cyou/Article/details/gtfjkkvjbm.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.cdnleiting.top/Article/details/gtrbghtyfy.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.9152youxi.cn/Article/details/gtfhkfsspv.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.havefunace.top/Article/details/gtttdrqzvt.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.birdmap.top/Article/details/gtfneekdqi.html

[J09] 时区处理
来源：http://dali.andypj.xyz/Article/details/gtpjuopgex.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.ppjwa.cn/Article/details/gtyzmrivxc.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.tianlin.xyz/Article/details/gtpuwtyjib.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jqgfzy.top/Article/details/gtyilxeqlr.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xylfe.cn/Article/details/gtnlmdtbhz.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.chenlongwang.top/Article/details/gtoplielog.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhiwuduotai.top/Article/details/gtrecemyvv.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.fengsongda.top/Article/details/gtxoohbulx.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.svipenyu.cn/Article/details/gtymqlwuoz.html

[J10] 取今天 / 本月第一天
来源：http://dali.jqgfzy.top/Article/details/gtkbjpeubq.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.ivvv.top/Article/details/gtlegdxzaj.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.chenlongwang.top/Article/details/gtmvmbcwrp.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.daxiang520.top/Article/details/gtdsykwrje.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.zhiwuduotai.top/Article/details/gtutbrqodt.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtmhhziefz.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.quarkkingdee.top/Article/details/gtkeccqjds.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.pycfn.com/Article/details/gtmlcmfrnn.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.fengsongda.top/Article/details/gttupqhdms.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtkgccbyea.html

K. JSON 与序列化
来源：http://dali.shuidangran.top/Article/details/gtyhcqkvcm.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtaoxzcgxw.html

[K01] 对象转 JSON 字符串
来源：http://dali.chenjidiqi.icu/Article/details/gtysszufga.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.guowangkeji.top/Article/details/gtomzoxvtq.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.dianchejie.cn/Article/details/gtvdkyrttt.html

JS:   JSON.stringify(obj)
来源：http://dali.0kj1m.cn/Article/details/gtciscsqpb.html

TS:   JSON.stringify(obj)
来源：http://dali.zdqjudy.top/Article/details/gtbqjwjrbz.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yanxiufei.cn/Article/details/gtbdscvair.html

Go:   json.Marshal(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtoocroccs.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yonumen.top/Article/details/gtiukxdrxk.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.xziqi.cn/Article/details/gtkeqfvumv.html

[K02] JSON 字符串转对象
来源：http://dali.guannengcc.top/Article/details/gtyvnbswhe.html

Py:   json.loads(s)
来源：http://dali.yuxming.cn/Article/details/gtwlegrltj.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.bjfxy.top/Article/details/gtonnikskf.html

JS:   JSON.parse(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtcobpuezd.html

TS:   JSON.parse(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtxwwcwevx.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.mhx1999.top/Article/details/gtoeorobfz.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.pycfn.com/Article/details/gtzvpehslb.html

Ruby: JSON.parse(s)
来源：http://dali.vqdsnc.cn/Article/details/gtvxhohjpc.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.guannengcc.top/Article/details/gtxcnnwhlp.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhoulong.xyz/Article/details/gtnqygfmdp.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jyoumei.cn/Article/details/gtafeoxwjf.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.aibaodan.cn/Article/details/gtndumsxyq.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhongyouzk.top/Article/details/gtrgedbpat.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.andypj.xyz/Article/details/gttmomjisk.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.hfpthk.cn/Article/details/gtndfnpvyh.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.daria6918.cn/Article/details/gtnzvpqplz.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhixingplan.top/Article/details/gtbczvapiz.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhijiandao.cn/Article/details/gtlnpdxews.html

[K04] 读取 JSON 文件
来源：http://dali.xinyue.icu/Article/details/gtavznaxur.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.sufxvd.cn/Article/details/gtotspdtrc.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.zycfv.cn/Article/details/gtlyaitduq.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.gzhubu.top/Article/details/gtlagbmowl.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sufxvd.cn/Article/details/gttynzusri.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.yongpay.top/Article/details/gtvlvhxyzu.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.jinqigfzy.top/Article/details/gtoksprpxh.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.cucudq.cn/Article/details/gtrohopbfr.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.pycfn.com/Article/details/gtfkfrejgq.html

[K05] 深拷贝对象
来源：http://dali.daria6918.cn/Article/details/gtcxlfxsaz.html

Py:   copy.deepcopy(obj)
来源：http://dali.yongpay.top/Article/details/gthkexaige.html

PHP:  unserialize(serialize($obj));
来源：http://dali.mhx1999.top/Article/details/gtjbnekqnj.html

JS:   structuredClone(obj)
来源：http://dali.jinqigufen.top/Article/details/gtitcqdqkt.html

TS:   structuredClone(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzulnzwoh.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jiagoushi.top/Article/details/gtksobdbjh.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jyoumei.cn/Article/details/gtvvkimsfc.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.smart0.xyz/Article/details/gtbgohpqbt.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.gogol.net.cn/Article/details/gtwsgguwls.html

[K06] 解析 URL 查询串
来源：http://dali.kuanghao11.cn/Article/details/gtvytrjgvx.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.shanyushiyangtech.top/Article/details/gtmvlgtytb.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.dashuyun.cn/Article/details/gtszawvblz.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.nanxinkj.top/Article/details/gtvpvrtoak.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hammf.cn/Article/details/gtnlirfggb.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yj20258888.top/Article/details/gtiluhpedz.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.xinyue.icu/Article/details/gtitrjdjhz.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yanxiufei.cn/Article/details/gticiuynpu.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jinqigufen.top/Article/details/gtzavmuzcv.html

[K07] 进制转换
来源：http://dali.feifeiyinyue.top/Article/details/gtrzuolgly.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.haohaochexian.top/Article/details/gtxgunoncp.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.sweek.top/Article/details/gttvdfoung.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.c1oappe.top/Article/details/gtjcedzdwl.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.gotoacloud.top/Article/details/gthuyrwdgc.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yuanzhike.top/Article/details/gtumutzsdo.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.shuidangran.top/Article/details/gtvovusfhs.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.smart0.xyz/Article/details/gtlbqbgrph.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yuanzhike.top/Article/details/gtjsqmogib.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.fengsongda.top/Article/details/gtjnzkzeib.html

Py:   pickle.dumps(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxawqamiz.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jqgfzy.top/Article/details/gtkgqnkvby.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.vqdsnc.cn/Article/details/gtbrdooiqd.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.birdmap.top/Article/details/gtwaxelqnl.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.svipenyu.cn/Article/details/gteagsrsmx.html

Go:   encoding/gob
来源：http://dali.kuanghao11.cn/Article/details/gtkwkmzebr.html

Ruby: Marshal.dump(obj)
来源：http://dali.fzhhl.top/Article/details/gtglukvtuo.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.hfpthk.cn/Article/details/gtmaizxoem.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtqmjwudju.html

L. 网络请求
来源：http://dali.tanke756.top/Article/details/gtozdvoenk.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtyiwpcfhn.html

[L01] 发送 GET 请求
来源：http://dali.jyoumei.cn/Article/details/gtgnissmei.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.316326.xyz/Article/details/gtpqcnmsvr.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.chenzaomai.com/Article/details/gtyeqkzosa.html

JS:   await fetch(url)
来源：http://dali.ppjwa.cn/Article/details/gtnnjdvvng.html

TS:   await fetch(url)
来源：http://dali.jqgufenzy.top/Article/details/gtpgnjngeh.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.aizwys.cn/Article/details/gttagpkvmp.html

Go:   resp, err := http.Get(url)
来源：http://dali.ehwqpu.com/Article/details/gtipqhepgw.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jinqigfzy.top/Article/details/gtkqmzlspi.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.ppjwa.cn/Article/details/gtglyqgagi.html

[L02] 发送 POST JSON
来源：http://dali.jyoumei.cn/Article/details/gtrewfwzxs.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.quarkkingdee.top/Article/details/gtbwwomozh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.pengpengdd.cyou/Article/details/gtxwyamryg.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sxryk.cn/Article/details/gtagqgszqs.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yuxming.cn/Article/details/gtvqdcjilv.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yj20258888.top/Article/details/gtrxhgrgiw.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.cucudq.cn/Article/details/gtscxjzeuh.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.bjfxy.top/Article/details/gtrtwvpkbv.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yvedp.cn/Article/details/gtjzkrbjgf.html

[L03] 设置自定义请求头
来源：http://dali.meibo888.top/Article/details/gtauqxjtrw.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jlsjyb.cn/Article/details/gtuewzhatb.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.xziqi.cn/Article/details/gtbmmszosd.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.andypj.xyz/Article/details/gtiskfdjfx.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yueranfly.top/Article/details/gtfxxefdby.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.xuanzx.com/Article/details/gtdhgocsee.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yongpay.top/Article/details/gtnzsqbrbv.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yj20258.top/Article/details/gtibviqdsi.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.hysaishi.cn/Article/details/gtdxvqhhri.html

[L04] 设置超时
来源：http://dali.jiagoushi.top/Article/details/gtnalohokp.html

Py:   requests.get(url, timeout=5)
来源：http://dali.shangyingyoupin.top/Article/details/gtvrvskuvd.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.cqqwz.cn/Article/details/gtjqyeaqdl.html


<!-- 参考信息 -->