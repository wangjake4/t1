代发 wailian999

C#:   Debug.Assert(x > 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gtjzyuphfj.html

[H08] 获取错误信息与堆栈
来源：http://dali.redwolf501.top/Article/details/gttoviaoao.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.mhx1999.top/Article/details/gtotbfwdes.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.shangyingyoupin.top/Article/details/gtmypjgnps.html

JS:   e.message;  e.stack
来源：http://dali.wangshuangyany.cn/Article/details/gtsezaebns.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yuxming.cn/Article/details/gtpurkcwar.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhixingplan.top/Article/details/gtftrgcckq.html

Go:   err.Error()
来源：http://dali.c1oappe.top/Article/details/gticbdhsov.html

Ruby: e.message;  e.backtrace
来源：http://dali.hnxiangtu.top/Article/details/gtcdbwcgpm.html

C#:   e.Message;  e.StackTrace
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvjijpbmh.html

[H09] 带错误码的异常
来源：http://dali.daxiang520.top/Article/details/gtoxwfhpoz.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.xuanzx.com/Article/details/gtbqqwptsf.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jyoumei.cn/Article/details/gtqqfentea.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.sysykeji.top/Article/details/gtqezlbpnz.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.shzxlz.cn/Article/details/gtrtevdzli.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.hongshengwenyu.top/Article/details/gtrafaomgh.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zycfv.cn/Article/details/gtkrtfzbvk.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.sysykeji.top/Article/details/gtwegahnoj.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.ivvv.top/Article/details/gtnhluwens.html

[H10] 资源自动释放
来源：http://dali.fengsongda.top/Article/details/gtxmyqaqai.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yj20258888.top/Article/details/gtehlbljjo.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.fengsongda.top/Article/details/gtegpefyoo.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jianghu66.top/Article/details/gtlbbtlwrk.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jyoumei.cn/Article/details/gtbhrmhrwx.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.gotoacloud.top/Article/details/gtocqncrdw.html

Go:   defer f.Close()
来源：http://dali.yvedp.cn/Article/details/gtvdqtrihi.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.xuetiantiany.cn/Article/details/gtlyteoslc.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhixingplan.top/Article/details/gtqexvmett.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtvurnngkv.html

I. 正则表达式
来源：http://dali.hnqzz.top/Article/details/gtvdbjtcij.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtjwxwgbez.html

[I01] 判断是否匹配
来源：http://dali.ywan-chungtsiang.top/Article/details/gtccyzfntx.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttbxoqifu.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.smart0.xyz/Article/details/gtnuqhzdec.html

JS:   /\d+/.test(s)
来源：http://dali.yangfankeji.com/Article/details/gthwrisvfe.html

TS:   /\d+/.test(s)
来源：http://dali.jiagoushi.top/Article/details/gtaygecgmb.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.daxiang520.top/Article/details/gtnmhfehdm.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.birdmap.top/Article/details/gtifkhdcji.html

Ruby: s.match?(/\d+/)
来源：http://dali.shangyingyoupin.top/Article/details/gtvnsgxlol.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.pengpengdd.cyou/Article/details/gtfvvuvzhm.html

[I02] 提取所有匹配
来源：http://dali.ydzc1.top/Article/details/gtudivhqmd.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jinqigfzy.top/Article/details/gtilskzrre.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.chenzaomai.com/Article/details/gtuqoyerii.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yongpay.top/Article/details/gtarjtdktr.html

TS:   s.match(/\d+/g)
来源：http://dali.guowangkeji.top/Article/details/gtgbnbfswq.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.haohaochexian.top/Article/details/gtfbozwadu.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.nwbrower.top/Article/details/gtcxmgaqhs.html

Ruby: s.scan(/\d+/)
来源：http://dali.ppjwa.cn/Article/details/gtqogcaduv.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.ydzc1.top/Article/details/gtigxpihyq.html

[I03] 提取捕获分组
来源：http://dali.havefunace.top/Article/details/gtfawmyybp.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yj202588.top/Article/details/gtkrpwbafo.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhixingplan.top/Article/details/gttsshzxax.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.ehwqpu.com/Article/details/gtdbrsadpp.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.tian-w.cn/Article/details/gtncmclepw.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvewksevz.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jlsjyb.cn/Article/details/gttrbesgiq.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.shuidangran.top/Article/details/gtotssqjqd.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.gogol.net.cn/Article/details/gtywlvbmcr.html

[I04] 正则替换
来源：http://dali.yuanzhike.top/Article/details/gtcrjbtgdj.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yanxiufei.cn/Article/details/gtedewzigq.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jqgfzy.top/Article/details/gtbqvyqqcn.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.guowangkeji.top/Article/details/gtvjrctcgi.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.cashguo.top/Article/details/gtzwqccscr.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.c1oappe.top/Article/details/gtycfdcksu.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtydwpgvys.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.bjfxy.top/Article/details/gtkfuhvbgb.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.daria6918.cn/Article/details/gtsoygebdx.html

[I05] 按正则拆分
来源：http://dali.aibaodan.cn/Article/details/gtncyjnkmc.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.hfpthk.cn/Article/details/gtyitrbgde.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.gotoacloud.top/Article/details/gtiweypidh.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.tian-w.cn/Article/details/gtmlfrmise.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yongpay.top/Article/details/gtbqwqxzhz.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhengqikj.top/Article/details/gtgcsuzgba.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.gzhubu.top/Article/details/gtmequteqk.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.nanxinkj.top/Article/details/gtczycnoep.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yvedp.cn/Article/details/gtxxyzochs.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yj20258888.top/Article/details/gtgwhzxolx.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.cashguo.top/Article/details/gtslxtmqzb.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.xuanzx.com/Article/details/gtnzlzjiad.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jlsjyb.cn/Article/details/gteaytmyxc.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhengqikj.top/Article/details/gtjrucexyw.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.xziqi.cn/Article/details/gtxdyiwerq.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.ivvv.top/Article/details/gtdzocjike.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.cqqwz.cn/Article/details/gtocgafcjo.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.kuanghao11.cn/Article/details/gtqsrelqwm.html

[I07] 忽略大小写与多行模式
来源：http://dali.snrcjt.cn/Article/details/gtctisoslo.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.kuanghao11.cn/Article/details/gtowalchcg.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.cashguo.top/Article/details/gtlpirqacn.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jiagoushi.top/Article/details/gtnkjkkhyo.html

TS:   /error/gim
来源：http://dali.xuetiantiany.cn/Article/details/gtjshjivti.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.sweek.top/Article/details/gtekrxvopv.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.birdmap.top/Article/details/gtqgvafgvd.html

Ruby: s.scan(/error/i)
来源：http://dali.nanxinkj.top/Article/details/gtsrtetejg.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yvedp.cn/Article/details/gtfdgxkvis.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.pycfn.com/Article/details/gtktrujlzn.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.wangshuangyany.cn/Article/details/gtfaobwpmc.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jlsjyb.cn/Article/details/gtcwqnqaur.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hnxiangtu.top/Article/details/gtbdtsablr.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xuanzx.com/Article/details/gtityxhevn.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.pycfn.com/Article/details/gtbcxzulno.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.kuanghao11.cn/Article/details/gtncrzydmq.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.ydzc1.top/Article/details/gtlagzcmxh.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.hnxiangtu.top/Article/details/gtsynbnibo.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtdtnjgvwh.html

J. 日期与时间
来源：http://dali.zhixingplan.top/Article/details/gttvmdchnl.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtzbefimsq.html

[J01] 获取当前时间
来源：http://dali.snrcjt.cn/Article/details/gtxnmcvnvu.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.gaohongyu789.top/Article/details/gtobjbyvhn.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.cheryme.top/Article/details/gtmzsrrerx.html

JS:   new Date();  Date.now()
来源：http://dali.zhijiandao.cn/Article/details/gtcfdqvhlp.html

TS:   new Date();  Date.now()
来源：http://dali.meibo888.top/Article/details/gtirwdxhak.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.ydzc1.top/Article/details/gthywckrsw.html

Go:   time.Now()
来源：http://dali.tian-w.cn/Article/details/gtoueehfzz.html

Ruby: Time.now
来源：http://dali.zhaomingkeji.xyz/Article/details/gtievtvkvf.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.bjfxy.top/Article/details/gtvpfcylzs.html

[J02] 格式化输出
来源：http://dali.andypj.xyz/Article/details/gtgbubjprw.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.wangshuangyany.cn/Article/details/gtpjcvfnlp.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.meibo888.top/Article/details/gtmvxbwwfk.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.bjfxy.top/Article/details/gtdaksbcgi.html

TS:   d.toISOString()
来源：http://dali.chenlongwang.top/Article/details/gtgcfqxlcg.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yj20258.top/Article/details/gtyghiuaxl.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.316326.xyz/Article/details/gtnphqrzdy.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.bjfxy.top/Article/details/gtgyurtqaq.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.nanxuanxn.top/Article/details/gtbimywhju.html

[J03] 字符串解析为日期
来源：http://dali.shanyushiyangkeji.top/Article/details/gthysuzcky.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.nanxuanxn.top/Article/details/gtqkmjlivk.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.andypj.xyz/Article/details/gtpwulrqcj.html

JS:   new Date("2024-01-02")
来源：http://dali.guowangkeji.top/Article/details/gtitdnqvqo.html

TS:   new Date("2024-01-02")
来源：http://dali.dashuyun.cn/Article/details/gtayyvviih.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.pengpengdd.cyou/Article/details/gtfvtbwaqj.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zhijiandao.cn/Article/details/gtobjlovbh.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.nanxinkj.top/Article/details/gtkmjjzqyt.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.cheryme.top/Article/details/gtpjymbcsf.html

[J04] 时间戳与日期互转
来源：http://dali.nanxinkj.top/Article/details/gtbkhzcrbd.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.chenzaomai.com/Article/details/gtzeuzlaof.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jiagoushi.top/Article/details/gtpkbudslj.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jinqigufen.top/Article/details/gtyaxviwdl.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yongpay.top/Article/details/gtgtfrfzcp.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcmfhotxy.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.cashguo.top/Article/details/gtrnyrrflr.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.svipenyu.cn/Article/details/gtaykwtojb.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zycfv.cn/Article/details/gtkaqnrwcg.html

[J05] 时间加减（加 7 天）
来源：http://dali.jyoumei.cn/Article/details/gtgzdsvapq.html

Py:   now + timedelta(days=7)
来源：http://dali.kuanghao11.cn/Article/details/gtkiroyncx.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.svipenyu.cn/Article/details/gtcrsesduw.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.meibo888.top/Article/details/gtkroobvsd.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.havefunace.top/Article/details/gttuwcgauy.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.316326.xyz/Article/details/gtlajgsnph.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yanxiufei.cn/Article/details/gtibhnbeao.html

Ruby: Time.now + 7 * 86400
来源：http://dali.9152youxi.cn/Article/details/gtiveoaysi.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.sweek.top/Article/details/gtoaqkqiye.html

[J06] 计算两时间之差
来源：http://dali.9152youxi.cn/Article/details/gtoxaweliv.html

Py:   (end - start).total_seconds()
来源：http://dali.xziqi.cn/Article/details/gtybwljdon.html

PHP:  $end->diff($start)->days;
来源：http://dali.wangdashe.top/Article/details/gtavnmtejd.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.ydzc1.top/Article/details/gtbfpaajmr.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yueranfly.top/Article/details/gthtmreaju.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yonumen.top/Article/details/gtzkmoboli.html

Go:   end.Sub(start).Hours()
来源：http://dali.vqdsnc.cn/Article/details/gtofdlqpfd.html

Ruby: end - start                 # 返回秒数
来源：http://dali.birdmap.top/Article/details/gtxnwooiam.html

C#:   (end - start).TotalSeconds
来源：http://dali.zhixingplan.top/Article/details/gtdwrzrnpn.html

[J07] 比较两个日期
来源：http://dali.guowangkeji.top/Article/details/gtrwtgiedx.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.wangshuangyany.cn/Article/details/gtgfroakaf.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.c1oappe.top/Article/details/gtyapbducp.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.shangyingyoupin.top/Article/details/gtaxvufbsw.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhoulong.xyz/Article/details/gtvhzmrmkg.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.hnxiangtu.top/Article/details/gthhzvdbah.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.0kj1m.cn/Article/details/gthcdncrmp.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.iojbl.cn/Article/details/gtvsggmibe.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.xuetiantiany.cn/Article/details/gtuaeganub.html

[J08] 提取年月日与星期
来源：http://dali.chenlongwang.top/Article/details/gtvpxcqqdd.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.havefunace.top/Article/details/gtjtfhluaw.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.sxryk.cn/Article/details/gtrddzukzk.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yueranfly.top/Article/details/gtcdtefxhq.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.gogol.net.cn/Article/details/gteceevwjm.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.nanxinkj.top/Article/details/gtnvlefuch.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jianghu66.top/Article/details/gtdbufhldp.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.guannengcc.top/Article/details/gtflxlimqw.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.kuanghao11.cn/Article/details/gtdlkggiau.html

[J09] 时区处理
来源：http://dali.jqgfzy.top/Article/details/gticgbddum.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.mhx1999.top/Article/details/gtwiynpdbb.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.andypj.xyz/Article/details/gtwvgbttem.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.svipenyu.cn/Article/details/gtcauvxtrn.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yuxming.cn/Article/details/gttlorlcil.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.316326.xyz/Article/details/gtxpaaeoao.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.havefunace.top/Article/details/gtbzmjtfgj.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.nanxinkj.top/Article/details/gtrgungmbo.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.haohaochexian.top/Article/details/gtfulfhplf.html

[J10] 取今天 / 本月第一天
来源：http://dali.kuanghao11.cn/Article/details/gtwvvippda.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmnhhvoxk.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.chenzaomai.com/Article/details/gtxxrgiryj.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtccxqpxjm.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jqgufenzy.top/Article/details/gtrtuipmzn.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhongyouzk.top/Article/details/gtylklyyif.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.nanxuanxn.top/Article/details/gtdjhbjhbd.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yuanzhike.top/Article/details/gtnofravzx.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.smart0.xyz/Article/details/gtohyqgdbj.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtyrfgvygi.html

K. JSON 与序列化
来源：http://dali.ppjwa.cn/Article/details/gtcaisnwaf.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtwcpfetda.html

[K01] 对象转 JSON 字符串
来源：http://dali.ivvv.top/Article/details/gtygmwihxd.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.zhengqikj.top/Article/details/gtecrdpciz.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yanxiufei.cn/Article/details/gtahdcuanl.html

JS:   JSON.stringify(obj)
来源：http://dali.redwolf501.top/Article/details/gtcpwlmylr.html

TS:   JSON.stringify(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtqswtpemv.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.sweek.top/Article/details/gtsqtzgxxu.html

Go:   json.Marshal(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gtpietrbgp.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.tian-w.cn/Article/details/gteslwtwtc.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtfcvqibou.html

[K02] JSON 字符串转对象
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfkauwoih.html

Py:   json.loads(s)
来源：http://dali.9152youxi.cn/Article/details/gtcbkmmvlr.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.sweek.top/Article/details/gtgjlhskhh.html

JS:   JSON.parse(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmwgyszld.html

TS:   JSON.parse(s)
来源：http://dali.yueranfly.top/Article/details/gtiyrqznle.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.shanyushiyangtech.top/Article/details/gtzrlqzrcm.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.tanke756.top/Article/details/gtauxtbvnt.html

Ruby: JSON.parse(s)
来源：http://dali.chenlongwang.top/Article/details/gthvorgabr.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yonumen.top/Article/details/gtemlilbja.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.0kj1m.cn/Article/details/gtvozldolz.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.mhx1999.top/Article/details/gtxbqfywvg.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvjieetqy.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.dianchejie.cn/Article/details/gtxxmdbjbo.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yuxming.cn/Article/details/gtjokrortu.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhijiandao.cn/Article/details/gtptqhzsoc.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jinqigfzy.top/Article/details/gtyfqokueu.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.andypj.xyz/Article/details/gtwxrilvwz.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yvedp.cn/Article/details/gtputyackf.html

[K04] 读取 JSON 文件
来源：http://dali.zhiwuduotai.top/Article/details/gtfxrgdpxp.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.c1oappe.top/Article/details/gtuzlnmcny.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.xuetiantiany.cn/Article/details/gtibdctqpx.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jyoumei.cn/Article/details/gturvwluwg.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yuanzhike.top/Article/details/gtslhzpfcs.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.hfpthk.cn/Article/details/gtkawwfvch.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.chenzaomai.com/Article/details/gtkbcbvfqs.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.ydzc1.top/Article/details/gtbqgujbdi.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.dianchejie.cn/Article/details/gtfitnhylm.html

[K05] 深拷贝对象
来源：http://dali.pycfn.com/Article/details/gtzsbcyxil.html

Py:   copy.deepcopy(obj)
来源：http://dali.hywenlv.cn/Article/details/gtyhvbfppl.html

PHP:  unserialize(serialize($obj));
来源：http://dali.chenlongwang.top/Article/details/gtlpwzmjjk.html

JS:   structuredClone(obj)
来源：http://dali.yuanzhike.top/Article/details/gtmuubaihp.html

TS:   structuredClone(obj)
来源：http://dali.chenlongwang.top/Article/details/gtdbxjlbig.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.hysaishi.cn/Article/details/gtzrjhctha.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.svipenyu.cn/Article/details/gtyzclmdea.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.dashuyun.cn/Article/details/gtcyuewnpp.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.sxryk.cn/Article/details/gtrvpokfut.html

[K06] 解析 URL 查询串
来源：http://dali.yongpay.top/Article/details/gtvzczfwnp.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.havefunace.top/Article/details/gtayuukqwt.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.9152youxi.cn/Article/details/gtzipnhvqc.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.chenjidiqi.icu/Article/details/gtbqqecrhv.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jqgufenzy.top/Article/details/gtezzazlbv.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.shanyushiyangtech.top/Article/details/gtpjgmoluu.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.sxryk.cn/Article/details/gtvjgwndeg.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.c1oappe.top/Article/details/gtnyidtiii.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.bjfxy.top/Article/details/gtsvtfkqth.html

[K07] 进制转换
来源：http://dali.jinghuilouyu.cn/Article/details/gttdecifld.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.chenlongwang.top/Article/details/gtwvupxedn.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.gotoacloud.top/Article/details/gtthbzhqlb.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.hongshengwenyu.top/Article/details/gtkqoqxsvb.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jqgfzy.top/Article/details/gtpelavkkt.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.ehwqpu.com/Article/details/gtjlnabjcd.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yuanzhike.top/Article/details/gtneryztfj.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.sweek.top/Article/details/gtdkrcbajp.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yanxiufei.cn/Article/details/gtvbbynnyc.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.daria6918.cn/Article/details/gtazkydwkt.html

Py:   pickle.dumps(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtwkdxoeht.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.cashguo.top/Article/details/gtmrsolicz.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.sweek.top/Article/details/gtlvlwuxvd.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.ehwqpu.com/Article/details/gtzowibygk.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yuxming.cn/Article/details/gtdkxgxiot.html

Go:   encoding/gob
来源：http://dali.jqgufenzy.top/Article/details/gtrplseslq.html

Ruby: Marshal.dump(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gtcuupxsoo.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqobegbfc.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtholvqhes.html

L. 网络请求
来源：http://dali.iojbl.cn/Article/details/gtgbqeqpge.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtnblsoaql.html

[L01] 发送 GET 请求
来源：http://dali.meibo888.top/Article/details/gttmwmlqtg.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yanxiufei.cn/Article/details/gtaalvvkro.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.pengpengdd.cyou/Article/details/gtbrgssesv.html

JS:   await fetch(url)
来源：http://dali.cdnleiting.top/Article/details/gtnnqyiciq.html

TS:   await fetch(url)
来源：http://dali.shzxlz.cn/Article/details/gtboktslym.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.cheryme.top/Article/details/gtxanezcmd.html

Go:   resp, err := http.Get(url)
来源：http://dali.jianghu66.top/Article/details/gtqjdftquc.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.havefunace.top/Article/details/gtjagocjbt.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.ydzc1.top/Article/details/gtawdhyfde.html

[L02] 发送 POST JSON
来源：http://dali.ppjwa.cn/Article/details/gtitezhkxk.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.gzhubu.top/Article/details/gtufjbfwap.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.xziqi.cn/Article/details/gtnhvcipsc.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yanxiufei.cn/Article/details/gtxzhafrro.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhengqikj.top/Article/details/gtcjkddqkt.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.pengpengdd.cyou/Article/details/gtirovnbav.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.meibo888.top/Article/details/gtlcrstwet.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jinqigfzy.top/Article/details/gttsxvagcs.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.gzhubu.top/Article/details/gtvgbqykpt.html

[L03] 设置自定义请求头
来源：http://dali.zhixingplan.top/Article/details/gtjkhyswsh.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmvjwfrki.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhongyouzk.top/Article/details/gttagukklf.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.chenzaomai.com/Article/details/gtifhpoblx.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yangfankeji.com/Article/details/gtqhhhwnss.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhixingplan.top/Article/details/gthpfkwtav.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.ppjwa.cn/Article/details/gtszxxrseo.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.hnqzz.top/Article/details/gthlwhjrgv.html


<!-- 参考信息 -->