代发 wailian999

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gtsorwsmov.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.cqqwz.cn/Article/details/gtzwxzgcdd.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yonumen.top/Article/details/gtakdpfxoz.html

C#:   obj?.A?.B ?? default
来源：http://dali.0kj1m.cn/Article/details/gtqcmxfmug.html

[H07] 断言
来源：http://dali.aibaodan.cn/Article/details/gtffqaazxz.html

Py:   assert x > 0, "必须为正"
来源：http://dali.316326.xyz/Article/details/gtwcwvepyt.html

PHP:  assert($x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gtudqcppzv.html

JS:   console.assert(x > 0);
来源：http://dali.dianchejie.cn/Article/details/gtdiptzncp.html

TS:   console.assert(x > 0);
来源：http://dali.hfpthk.cn/Article/details/gtfwmjekot.html

Java: assert x > 0 : "必须为正";
来源：http://dali.wangshuangyany.cn/Article/details/gtkjebjpry.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yj202588.top/Article/details/gtjfsvkola.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.chenzaomai.com/Article/details/gteivvfyek.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yueranfly.top/Article/details/gtpprmqqqb.html

[H08] 获取错误信息与堆栈
来源：http://dali.wangshuangyany.cn/Article/details/gtyqiizfxa.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.chenlongwang.top/Article/details/gtigvuxtlu.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.ivvv.top/Article/details/gtoozidmty.html

JS:   e.message;  e.stack
来源：http://dali.pycfn.com/Article/details/gtsyjikypn.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.aizwys.cn/Article/details/gtodmdobtx.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.gzhubu.top/Article/details/gtgywjpqyq.html

Go:   err.Error()
来源：http://dali.guannengcc.top/Article/details/gtljikvvnx.html

Ruby: e.message;  e.backtrace
来源：http://dali.svipenyu.cn/Article/details/gtedduyevu.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hnxiangtu.top/Article/details/gtnsbaohkt.html

[H09] 带错误码的异常
来源：http://dali.snrcjt.cn/Article/details/gtfkefhqin.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.ppjwa.cn/Article/details/gtrjbxdcml.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jianghu66.top/Article/details/gtxtatepmh.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.pycfn.com/Article/details/gtclolkvft.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.redwolf501.top/Article/details/gtoysbtlqd.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.gotoacloud.top/Article/details/gtyqinaooz.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.gaohongyu789.top/Article/details/gtwjqzpcyj.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.ydzc1.top/Article/details/gthprzkckv.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jyoumei.cn/Article/details/gtdzrxagja.html

[H10] 资源自动释放
来源：http://dali.xylfe.cn/Article/details/gtaaxkjywg.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.nanxinkj.top/Article/details/gtjkvzpdcu.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.shangyingyoupin.top/Article/details/gthjgatyyy.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.daria6918.cn/Article/details/gtdngrgvyi.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jlsjyb.cn/Article/details/gtxtpzdwjp.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.andypj.xyz/Article/details/gtrwcoiinj.html

Go:   defer f.Close()
来源：http://dali.hfpthk.cn/Article/details/gtkklkxigo.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yuanzhike.top/Article/details/gtlrthqorc.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gtdyyuocna.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gttbakmjio.html

I. 正则表达式
来源：http://dali.jianghu66.top/Article/details/gtciujgmaw.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtcgqehxhg.html

[I01] 判断是否匹配
来源：http://dali.jlsjyb.cn/Article/details/gtthvrcwgq.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.sxryk.cn/Article/details/gthysiimay.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.haohaochexian.top/Article/details/gtqarfdgwn.html

JS:   /\d+/.test(s)
来源：http://dali.daxiang520.top/Article/details/gtyoumwgaq.html

TS:   /\d+/.test(s)
来源：http://dali.havefunace.top/Article/details/gtamzwutke.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.redwolf501.top/Article/details/gtiqmvzhbb.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.sweek.top/Article/details/gthydahnbv.html

Ruby: s.match?(/\d+/)
来源：http://dali.shuidangran.top/Article/details/gtgnrnuqmn.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.xylfe.cn/Article/details/gtxamekxws.html

[I02] 提取所有匹配
来源：http://dali.c1oappe.top/Article/details/gtwxcwdfuw.html

Py:   re.findall(r"\d+", s)
来源：http://dali.wangdashe.top/Article/details/gthqeijjcp.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yvedp.cn/Article/details/gtsfgpcqeu.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yueranfly.top/Article/details/gtfbtufwnl.html

TS:   s.match(/\d+/g)
来源：http://dali.gotoacloud.top/Article/details/gtduvizzwv.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhijiandao.cn/Article/details/gtjrcowylj.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.havefunace.top/Article/details/gtmbdjjvyr.html

Ruby: s.scan(/\d+/)
来源：http://dali.shanyushiyangtech.top/Article/details/gtrvytqlhi.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.birdmap.top/Article/details/gtycpiysfe.html

[I03] 提取捕获分组
来源：http://dali.jyoumei.cn/Article/details/gtofbcesvt.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jqgfzy.top/Article/details/gtowooeros.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.fzhhl.top/Article/details/gtfapdmrrs.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.mhx1999.top/Article/details/gtcrsgryob.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.vqdsnc.cn/Article/details/gtfrfhvsjp.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.9152youxi.cn/Article/details/gtpzmrexfo.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.tanke756.top/Article/details/gtvjmdipsb.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yanxiufei.cn/Article/details/gtbccthvbk.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jinqigfzy.top/Article/details/gtihtdueik.html

[I04] 正则替换
来源：http://dali.meibo888.top/Article/details/gthpxqxldm.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.snrcjt.cn/Article/details/gtytcynkaz.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zycfv.cn/Article/details/gturtzgnaf.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.cashguo.top/Article/details/gtpeowgvog.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jqgfzy.top/Article/details/gtizbhstet.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.sxryk.cn/Article/details/gtfkavmbbq.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.sweek.top/Article/details/gtngfabgyp.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yj20258888.top/Article/details/gtzmrbrbjk.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yangfankeji.com/Article/details/gtjgrwsctv.html

[I05] 按正则拆分
来源：http://dali.pycfn.com/Article/details/gtniywlqrr.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.xylfe.cn/Article/details/gtoowfgjfo.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhiwuduotai.top/Article/details/gtiieolqok.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jlsjyb.cn/Article/details/gtvaymkibd.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.gotoacloud.top/Article/details/gtfzpmuapf.html

Java: s.split("\\s*,\\s*")
来源：http://dali.cheryme.top/Article/details/gttdbmrnrl.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.0kj1m.cn/Article/details/gthnqiwhyg.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jinqigufen.top/Article/details/gtklvaeqxn.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jinqigufen.top/Article/details/gtkgesweuz.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.birdmap.top/Article/details/gtjjmkptlq.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.feifeiyinyue.top/Article/details/gthbckoiao.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.sxryk.cn/Article/details/gtbjlmwqet.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yangfankeji.com/Article/details/gtrlbpigww.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinqigufen.top/Article/details/gthltkzyrm.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.kuanghao11.cn/Article/details/gttkbsdtlp.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.aibaodan.cn/Article/details/gtnvlvxxoq.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.hywenlv.cn/Article/details/gtukvhxzev.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.ybcxt.top/Article/details/gtmipgcjkp.html

[I07] 忽略大小写与多行模式
来源：http://dali.316326.xyz/Article/details/gtitfzmcqj.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.chenjidiqi.icu/Article/details/gtppiedrkp.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.xuanzx.com/Article/details/gtnvhdueyr.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhixingplan.top/Article/details/gtvkzcscgq.html

TS:   /error/gim
来源：http://dali.meibo888.top/Article/details/gtbvdqwuci.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.shangyingyoupin.top/Article/details/gtwyiydqfq.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.316326.xyz/Article/details/gtjxlppcmu.html

Ruby: s.scan(/error/i)
来源：http://dali.9152youxi.cn/Article/details/gtikgtiqtx.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.9152youxi.cn/Article/details/gtekazgukx.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.haohaochexian.top/Article/details/gtveqmaefg.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.nanxinkj.top/Article/details/gthwoawnsw.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.wangdashe.top/Article/details/gtkwdpyrfx.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.sxryk.cn/Article/details/gtvsnxginv.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpwtofsij.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.c1oappe.top/Article/details/gtznwtehml.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yj20258.top/Article/details/gtlpbyeare.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.redwolf501.top/Article/details/gtvwrlgrit.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.feifeiyinyue.top/Article/details/gtebtlxtug.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtwnlhbizj.html

J. 日期与时间
来源：http://dali.yvedp.cn/Article/details/gthiogudxs.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtapvimdyt.html

[J01] 获取当前时间
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgmmjfbpz.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhongyouzk.top/Article/details/gtjumqjixy.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.fzhhl.top/Article/details/gtidgnnobv.html

JS:   new Date();  Date.now()
来源：http://dali.0kj1m.cn/Article/details/gtokenuknt.html

TS:   new Date();  Date.now()
来源：http://dali.tanke756.top/Article/details/gtarnvxhga.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.c1oappe.top/Article/details/gtlvsdloaw.html

Go:   time.Now()
来源：http://dali.pengpengdd.cyou/Article/details/gtvuhmmiht.html

Ruby: Time.now
来源：http://dali.ybcxt.top/Article/details/gttidnzaac.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.yj20258.top/Article/details/gtnmmbawmt.html

[J02] 格式化输出
来源：http://dali.chenzaomai.com/Article/details/gtxhcdthbw.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gogol.net.cn/Article/details/gtvamsrqgs.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.aizwys.cn/Article/details/gtxbnnjnij.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.dianchejie.cn/Article/details/gtmiybhoxj.html

TS:   d.toISOString()
来源：http://dali.xuanzx.com/Article/details/gtytnncggt.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhiwuduotai.top/Article/details/gthjjsnhhl.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.tian-w.cn/Article/details/gtgreaynat.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sweek.top/Article/details/gtvsuccjpq.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.hnqzz.top/Article/details/gtmwbwfumh.html

[J03] 字符串解析为日期
来源：http://dali.smart0.xyz/Article/details/gtkgwrqqlh.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhengqikj.top/Article/details/gtzlnqeuey.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.iojbl.cn/Article/details/gtwkubfwdw.html

JS:   new Date("2024-01-02")
来源：http://dali.bjfxy.top/Article/details/gttxizwqkv.html

TS:   new Date("2024-01-02")
来源：http://dali.zycfv.cn/Article/details/gtfwkwbvhd.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.guannengcc.top/Article/details/gtauflxhnk.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.redwolf501.top/Article/details/gtkjwhleri.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.bjfxy.top/Article/details/gtpnwhvhxd.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yongpay.top/Article/details/gtotdckilj.html

[J04] 时间戳与日期互转
来源：http://dali.jqgfzy.top/Article/details/gtzlkdpivf.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.nanxuanxn.top/Article/details/gtnpbpzcxw.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.hammf.cn/Article/details/gtfolnicpy.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.nanxuanxn.top/Article/details/gtjzcorppb.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yueranfly.top/Article/details/gtqhgewqlc.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqmzqrmnh.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.shuidangran.top/Article/details/gtkkztrfqp.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.0kj1m.cn/Article/details/gtfumqnfwc.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.xylfe.cn/Article/details/gtfjxzgudt.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhoulong.xyz/Article/details/gtdtouuvze.html

Py:   now + timedelta(days=7)
来源：http://dali.pengpengdd.cyou/Article/details/gtczeagdin.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.sweek.top/Article/details/gtksoxgyyb.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jiagoushi.top/Article/details/gtojgdqweo.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.snrcjt.cn/Article/details/gtouecnlbk.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.haohaochexian.top/Article/details/gtqhtcmfwh.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiahtdjfb.html

Ruby: Time.now + 7 * 86400
来源：http://dali.cheryme.top/Article/details/gtvdimhfhl.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zycfv.cn/Article/details/gtfnihlilv.html

[J06] 计算两时间之差
来源：http://dali.kuanghao11.cn/Article/details/gtzgsrcicr.html

Py:   (end - start).total_seconds()
来源：http://dali.yonumen.top/Article/details/gtftpczfyk.html

PHP:  $end->diff($start)->days;
来源：http://dali.vqdsnc.cn/Article/details/gtvxpmkngp.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.xinyue.icu/Article/details/gtvofyltux.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jinqigufen.top/Article/details/gttjxaksjz.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgoxpeztm.html

Go:   end.Sub(start).Hours()
来源：http://dali.svipenyu.cn/Article/details/gtafvycieo.html

Ruby: end - start                 # 返回秒数
来源：http://dali.xuetiantiany.cn/Article/details/gtqygjpgkj.html

C#:   (end - start).TotalSeconds
来源：http://dali.gzhubu.top/Article/details/gtgakjnxqc.html

[J07] 比较两个日期
来源：http://dali.yuxming.cn/Article/details/gtbififdgf.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.haohaochexian.top/Article/details/gtgnvprugn.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jqgfzy.top/Article/details/gtjymqkluu.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.zhongyouzk.top/Article/details/gteajcnhdw.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.shzxlz.cn/Article/details/gthutinfpk.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthguwacxz.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.ehwqpu.com/Article/details/gtcwltvoxg.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.chenjidiqi.icu/Article/details/gtdmhubmjm.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.feifeiyinyue.top/Article/details/gtaarmcxip.html

[J08] 提取年月日与星期
来源：http://dali.ppjwa.cn/Article/details/gtjcsuvcju.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.chenjidiqi.icu/Article/details/gtshnirmls.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.pycfn.com/Article/details/gtpqcvmmkb.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.aizwys.cn/Article/details/gtiemvgnjx.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.tanke756.top/Article/details/gtspvirsav.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.dashuyun.cn/Article/details/gtrvwwsaaa.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.svipenyu.cn/Article/details/gtztmglxsm.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.hongshengwenyu.top/Article/details/gtbzumrncl.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yueranfly.top/Article/details/gtmzrwhbat.html

[J09] 时区处理
来源：http://dali.smart0.xyz/Article/details/gtmuzsadfz.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.hammf.cn/Article/details/gtdnoxmlzj.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.mhx1999.top/Article/details/gtazlaokzn.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtekptzlqe.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jqgfzy.top/Article/details/gtprpxgduj.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.redwolf501.top/Article/details/gtxwjktekw.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsdwzopzs.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjjsntbbj.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.hfpthk.cn/Article/details/gtcnyhgozy.html

[J10] 取今天 / 本月第一天
来源：http://dali.c1oappe.top/Article/details/gtpgcujqru.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yangfankeji.com/Article/details/gtxtyljpzh.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.chenjidiqi.icu/Article/details/gtzyzzziwu.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.ppjwa.cn/Article/details/gtlgtoxkdw.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.gzhubu.top/Article/details/gtfqtqzwrb.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtocfbenwz.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.tianlin.xyz/Article/details/gtyncrosmh.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.yj20258.top/Article/details/gtemfyrjap.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jqgfzy.top/Article/details/gtqgsbukfv.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtznonjvag.html

K. JSON 与序列化
来源：http://dali.gaohongyu789.top/Article/details/gtfedktakd.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtiafburqj.html

[K01] 对象转 JSON 字符串
来源：http://dali.ehwqpu.com/Article/details/gtsdimweie.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.xuetiantiany.cn/Article/details/gtzcbfsrex.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.tian-w.cn/Article/details/gtxtnxotsz.html

JS:   JSON.stringify(obj)
来源：http://dali.ydzc1.top/Article/details/gttwglbeoh.html

TS:   JSON.stringify(obj)
来源：http://dali.iojbl.cn/Article/details/gthtwcrkzc.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.chenjidiqi.icu/Article/details/gtakcvlunh.html

Go:   json.Marshal(obj)
来源：http://dali.mhx1999.top/Article/details/gtmiwkgkzg.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhaomingkeji.xyz/Article/details/gttcvpejyq.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.aibaodan.cn/Article/details/gthddeytjr.html

[K02] JSON 字符串转对象
来源：http://dali.zdqjudy.top/Article/details/gtcynmntsq.html

Py:   json.loads(s)
来源：http://dali.fengsongda.top/Article/details/gtnhsghxfv.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yongpay.top/Article/details/gtoezlpuos.html

JS:   JSON.parse(s)
来源：http://dali.yonumen.top/Article/details/gteubdnsxj.html

TS:   JSON.parse(s)
来源：http://dali.pycfn.com/Article/details/gtyujwjkxh.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.xuetiantiany.cn/Article/details/gtjqfmpjlu.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhiwuduotai.top/Article/details/gtlpexxlct.html

Ruby: JSON.parse(s)
来源：http://dali.cucudq.cn/Article/details/gtxrmnaork.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.gzhubu.top/Article/details/gtmqbjyxgh.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.xziqi.cn/Article/details/gtdvwxelhk.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jiagoushi.top/Article/details/gtyojsbdgb.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.aibaodan.cn/Article/details/gtejotfobc.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.cqqwz.cn/Article/details/gtxwxypmvc.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.sufxvd.cn/Article/details/gtyarajoxd.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.ivvv.top/Article/details/gtgkmdnvxu.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.andypj.xyz/Article/details/gtzubtzbrt.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.mhx1999.top/Article/details/gtluxayqgu.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.wangdashe.top/Article/details/gtwllaqhtp.html

[K04] 读取 JSON 文件
来源：http://dali.havefunace.top/Article/details/gtlhcxhylm.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.yongpay.top/Article/details/gtwileftyc.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtinukxasf.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.fzhhl.top/Article/details/gtsamqjljo.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.tianlin.xyz/Article/details/gtaxfsnarf.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.sweek.top/Article/details/gtaiacqdoq.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.dashuyun.cn/Article/details/gtklzvmmnz.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.ivvv.top/Article/details/gtbhcwccyh.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.svipenyu.cn/Article/details/gttoaxqxpp.html

[K05] 深拷贝对象
来源：http://dali.nanxuanxn.top/Article/details/gtgxpazoep.html

Py:   copy.deepcopy(obj)
来源：http://dali.iojbl.cn/Article/details/gtugujohdx.html

PHP:  unserialize(serialize($obj));
来源：http://dali.yangfankeji.com/Article/details/gtazdxxdfa.html

JS:   structuredClone(obj)
来源：http://dali.chenlongwang.top/Article/details/gtrffhjyup.html

TS:   structuredClone(obj)
来源：http://dali.birdmap.top/Article/details/gtxaidtsyh.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.hnqzz.top/Article/details/gtlxprzvwx.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.jianghu66.top/Article/details/gtvnfjayze.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.shangyingyoupin.top/Article/details/gtvekkrxus.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jinghuilouyu.cn/Article/details/gtvnwfhsnb.html

[K06] 解析 URL 查询串
来源：http://dali.iojbl.cn/Article/details/gtihjgjwti.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.havefunace.top/Article/details/gtfrmoxviu.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jinqigufen.top/Article/details/gtvvjdynit.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.smart0.xyz/Article/details/gtiygvrboz.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.havefunace.top/Article/details/gtkyyufcgc.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.ydzc1.top/Article/details/gtjlgtmxps.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.yj20258.top/Article/details/gtgyauukvk.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.daria6918.cn/Article/details/gtubnedlsx.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.ydzc1.top/Article/details/gtpfzcqvmv.html

[K07] 进制转换
来源：http://dali.zycfv.cn/Article/details/gtngdvsvje.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.nwbrower.top/Article/details/gttwiavhhc.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.zhiwuduotai.top/Article/details/gtctjrjhdt.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.jinqigufen.top/Article/details/gtbddeakdt.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.birdmap.top/Article/details/gtbnzpcrfl.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.quarkkingdee.top/Article/details/gtejmrivqk.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.sxryk.cn/Article/details/gtbzumikcx.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.0kj1m.cn/Article/details/gtlzesznxp.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.chenjidiqi.icu/Article/details/gtmlwxtlxs.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yj20258.top/Article/details/gtqxwhevxd.html

Py:   pickle.dumps(obj)
来源：http://dali.haohaochexian.top/Article/details/gtgnxjvbok.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.mhx1999.top/Article/details/gtxybjiqau.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.hammf.cn/Article/details/gthgsfhocz.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.shzxlz.cn/Article/details/gteperktjc.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.meibo888.top/Article/details/gtumvvqvou.html

Go:   encoding/gob
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwcfgyhyy.html

Ruby: Marshal.dump(obj)
来源：http://dali.hnqzz.top/Article/details/gtfsqwjwtd.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.hongshengwenyu.top/Article/details/gtpawdfaeb.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtrrrrlwpi.html

L. 网络请求
来源：http://dali.xinyue.icu/Article/details/gtndimrovt.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtpsptcmtq.html

[L01] 发送 GET 请求
来源：http://dali.cheryme.top/Article/details/gtyiovunid.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.chenlongwang.top/Article/details/gtedmhoaqr.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.c1oappe.top/Article/details/gthuusagbw.html

JS:   await fetch(url)
来源：http://dali.hnxiangtu.top/Article/details/gtjzngdcpw.html

TS:   await fetch(url)
来源：http://dali.meibo888.top/Article/details/gtrdxsetvn.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.pengpengdd.cyou/Article/details/gtitulnigd.html

Go:   resp, err := http.Get(url)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxutdwpws.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jiagoushi.top/Article/details/gtkxxkziri.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.gzhubu.top/Article/details/gtrhasulny.html

[L02] 发送 POST JSON
来源：http://dali.yonumen.top/Article/details/gtnofmdmcm.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgrdczzhj.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yj202588.top/Article/details/gtgoclzvqb.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shanyushiyangtech.top/Article/details/gtjvlstiit.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.fengsongda.top/Article/details/gtlyhzwdfj.html


<!-- 参考信息 -->