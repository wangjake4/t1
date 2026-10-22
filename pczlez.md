代发 wailian999

[H07] 断言
来源：http://dali.wangdashe.top/Article/details/gtgnyxznjy.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yangfankeji.com/Article/details/gtpfjmynnm.html

PHP:  assert($x > 0);
来源：http://dali.jqgfzy.top/Article/details/gtzzfhszlh.html

JS:   console.assert(x > 0);
来源：http://dali.zhoulong.xyz/Article/details/gtvutbtivx.html

TS:   console.assert(x > 0);
来源：http://dali.jyoumei.cn/Article/details/gttjhpxxnh.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhongyouzk.top/Article/details/gtmqwstubt.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.dashuyun.cn/Article/details/gtyuuxtekh.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfaarpfog.html

C#:   Debug.Assert(x > 0);
来源：http://dali.xziqi.cn/Article/details/gtnxkgtvjg.html

[H08] 获取错误信息与堆栈
来源：http://dali.yangfankeji.com/Article/details/gtgaxzlmfp.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yongpay.top/Article/details/gtsjszxkuu.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jqgufenzy.top/Article/details/gtpoucypje.html

JS:   e.message;  e.stack
来源：http://dali.chenlongwang.top/Article/details/gtdzgfcrbd.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yangfankeji.com/Article/details/gtvhpcyhum.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yonumen.top/Article/details/gtxuecvmig.html

Go:   err.Error()
来源：http://dali.hywenlv.cn/Article/details/gtmifmrvml.html

Ruby: e.message;  e.backtrace
来源：http://dali.xylfe.cn/Article/details/gtxftuzkqf.html

C#:   e.Message;  e.StackTrace
来源：http://dali.smart0.xyz/Article/details/gtktpeeuhm.html

[H09] 带错误码的异常
来源：http://dali.nanxuanxn.top/Article/details/gtigpgiign.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.hysaishi.cn/Article/details/gtjpufchtq.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yangfankeji.com/Article/details/gtwqavoixq.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yanxiufei.cn/Article/details/gthrczgmlu.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.shanyushiyangkeji.top/Article/details/gthfknqfae.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.xylfe.cn/Article/details/gtbkolqdtg.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.ivvv.top/Article/details/gtizwtqbft.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yonumen.top/Article/details/gtdhmkyvha.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.ivvv.top/Article/details/gtrixmiaig.html

[H10] 资源自动释放
来源：http://dali.pycfn.com/Article/details/gtuagqfigp.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.chenlongwang.top/Article/details/gtkyhyxjhk.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yuxming.cn/Article/details/gtbfjggunt.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhongyouzk.top/Article/details/gthxdekswe.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gogol.net.cn/Article/details/gtvkinfqiy.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zdqjudy.top/Article/details/gtdvnnrfwb.html

Go:   defer f.Close()
来源：http://dali.cashguo.top/Article/details/gthgwdkkjl.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zdqjudy.top/Article/details/gtpcnibseq.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.sxryk.cn/Article/details/gtyfwbkegv.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtzqvtyotb.html

I. 正则表达式
来源：http://dali.nwbrower.top/Article/details/gtffzxwqkd.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtkdjdlpry.html

[I01] 判断是否匹配
来源：http://dali.snrcjt.cn/Article/details/gtgrjzxqpn.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.gzhubu.top/Article/details/gttrgwtulp.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.daria6918.cn/Article/details/gtsuggjqja.html

JS:   /\d+/.test(s)
来源：http://dali.guannengcc.top/Article/details/gtqsucofvx.html

TS:   /\d+/.test(s)
来源：http://dali.ybcxt.top/Article/details/gtdlukxixv.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.9152youxi.cn/Article/details/gtwxavagme.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhongyouzk.top/Article/details/gtnexetusf.html

Ruby: s.match?(/\d+/)
来源：http://dali.meibo888.top/Article/details/gtyqqhpdlh.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.chenjidiqi.icu/Article/details/gtsxyvmgyv.html

[I02] 提取所有匹配
来源：http://dali.shanyushiyangtech.top/Article/details/gtnrmjqazi.html

Py:   re.findall(r"\d+", s)
来源：http://dali.hammf.cn/Article/details/gtxxnsbanz.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.snrcjt.cn/Article/details/gtuxomxdjv.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gtumndzbok.html

TS:   s.match(/\d+/g)
来源：http://dali.hammf.cn/Article/details/gtrsnbhbom.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.andypj.xyz/Article/details/gtqubrcwpy.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yanxiufei.cn/Article/details/gtxumdqsuf.html

Ruby: s.scan(/\d+/)
来源：http://dali.xziqi.cn/Article/details/gtwmkdkpne.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zdqjudy.top/Article/details/gtmzxvjvnv.html

[I03] 提取捕获分组
来源：http://dali.redwolf501.top/Article/details/gtoxpoayqy.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jiagoushi.top/Article/details/gtourwpxvv.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.guowangkeji.top/Article/details/gttdhxstim.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.0kj1m.cn/Article/details/gtditelzua.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jyoumei.cn/Article/details/gtsvpmhgqr.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.wangshuangyany.cn/Article/details/gtruiuvwfw.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.smart0.xyz/Article/details/gtjqdmvacm.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.sysykeji.top/Article/details/gtwkjhdppu.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhixingplan.top/Article/details/gtomiijpkp.html

[I04] 正则替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkupoiucy.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.chenjidiqi.icu/Article/details/gtgrcqjhtz.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yanxiufei.cn/Article/details/gtgklwlkvt.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.smart0.xyz/Article/details/gtrjbfbecw.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.chenzaomai.com/Article/details/gtgehtxykr.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.hammf.cn/Article/details/gtvznlhxcd.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.sxryk.cn/Article/details/gtvvusleah.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.quarkkingdee.top/Article/details/gtzaspjxle.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yongpay.top/Article/details/gtpbmfeacg.html

[I05] 按正则拆分
来源：http://dali.zhixingplan.top/Article/details/gtumnjigas.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.iojbl.cn/Article/details/gtpnpkwmkz.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yangfankeji.com/Article/details/gtiujtpsqc.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.tanke756.top/Article/details/gtpgmajduk.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.gzhubu.top/Article/details/gtjcbpxhnn.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhiwuduotai.top/Article/details/gtogdnbwxg.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.dashuyun.cn/Article/details/gtlcftwzfb.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.gzhubu.top/Article/details/gtltnognfy.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.hfpthk.cn/Article/details/gttdwwdjnq.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.xziqi.cn/Article/details/gtktahdwgm.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jinghuilouyu.cn/Article/details/gtdfgceovn.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.smart0.xyz/Article/details/gtpmqwmbzy.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shangyingyoupin.top/Article/details/gtrolgbema.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.ybcxt.top/Article/details/gttufhywsp.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.iojbl.cn/Article/details/gtpidtwckf.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.ehwqpu.com/Article/details/gtsnydubfw.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.dianchejie.cn/Article/details/gtoffoysrd.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.ybcxt.top/Article/details/gtcvignuvq.html

[I07] 忽略大小写与多行模式
来源：http://dali.hammf.cn/Article/details/gtyxezncgt.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.wangdashe.top/Article/details/gttqorxxaq.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.pengpengdd.cyou/Article/details/gtarzxwqgj.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.hnxiangtu.top/Article/details/gtsuqkstrg.html

TS:   /error/gim
来源：http://dali.xziqi.cn/Article/details/gtemsxlufm.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jlsjyb.cn/Article/details/gtqzlveabn.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.redwolf501.top/Article/details/gtohspsxxn.html

Ruby: s.scan(/error/i)
来源：http://dali.daxiang520.top/Article/details/gtdyluslrw.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.cucudq.cn/Article/details/gtgdngadqi.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.mhx1999.top/Article/details/gtqjvjevbk.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.guowangkeji.top/Article/details/gtcnmntqyf.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.sufxvd.cn/Article/details/gtgsohvvfh.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.guowangkeji.top/Article/details/gtwxztnoku.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.gogol.net.cn/Article/details/gtmobpbvke.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.snrcjt.cn/Article/details/gtsynqwfwp.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.sweek.top/Article/details/gtxozmgpxz.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jinqigfzy.top/Article/details/gtxphidukq.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jqgfzy.top/Article/details/gtrxviwkzf.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtwmlotshb.html

J. 日期与时间
来源：http://dali.fengsongda.top/Article/details/gtrfvffujf.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtyfmiawvs.html

[J01] 获取当前时间
来源：http://dali.daxiang520.top/Article/details/gtfhfyigah.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jqgufenzy.top/Article/details/gtrsygnnku.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.shuidangran.top/Article/details/gtzntbpkti.html

JS:   new Date();  Date.now()
来源：http://dali.xuanzx.com/Article/details/gtwrduykeg.html

TS:   new Date();  Date.now()
来源：http://dali.gotoacloud.top/Article/details/gtieajmdsk.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.daria6918.cn/Article/details/gtmzqtmxpo.html

Go:   time.Now()
来源：http://dali.daria6918.cn/Article/details/gtgmrchjdt.html

Ruby: Time.now
来源：http://dali.zhiwuduotai.top/Article/details/gtvjvwwqzr.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.hnxiangtu.top/Article/details/gtfukxdtpc.html

[J02] 格式化输出
来源：http://dali.iojbl.cn/Article/details/gtpuyaaixk.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.daxiang520.top/Article/details/gtxhtqfudi.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtczfsmxfo.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.iojbl.cn/Article/details/gtletmcser.html

TS:   d.toISOString()
来源：http://dali.316326.xyz/Article/details/gtmhmvlied.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.cdnleiting.top/Article/details/gtnenwqnpe.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhixingplan.top/Article/details/gtndidhrur.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sufxvd.cn/Article/details/gtfwtvafvz.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.redwolf501.top/Article/details/gtkbxmxoql.html

[J03] 字符串解析为日期
来源：http://dali.c1oappe.top/Article/details/gtpmygyeig.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.zhijiandao.cn/Article/details/gtkpkstpdh.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.ybcxt.top/Article/details/gtxhicagpt.html

JS:   new Date("2024-01-02")
来源：http://dali.hywenlv.cn/Article/details/gtafaktgdj.html

TS:   new Date("2024-01-02")
来源：http://dali.yonumen.top/Article/details/gtqfeuhqdr.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.aibaodan.cn/Article/details/gtdvmfobka.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.fengsongda.top/Article/details/gtdaulefbs.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jqgufenzy.top/Article/details/gtcydqgnrq.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jinghuilouyu.cn/Article/details/gtyakaseby.html

[J04] 时间戳与日期互转
来源：http://dali.yj20258.top/Article/details/gttvtfwvlr.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zdqjudy.top/Article/details/gtsdharqah.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.xylfe.cn/Article/details/gtybcegdym.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.9152youxi.cn/Article/details/gtmarfqkwh.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.c1oappe.top/Article/details/gtizaososl.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.316326.xyz/Article/details/gtfmrpqbgc.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.ivvv.top/Article/details/gtpsanowgn.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.chenlongwang.top/Article/details/gtvxoetjyg.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.mhx1999.top/Article/details/gtpnoiqnyw.html

[J05] 时间加减（加 7 天）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrubntssq.html

Py:   now + timedelta(days=7)
来源：http://dali.xuanzx.com/Article/details/gtgyvlpory.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yuanzhike.top/Article/details/gtqxbawffv.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.tanke756.top/Article/details/gtxkygdtvs.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xuanzx.com/Article/details/gtxbabkrpe.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.meibo888.top/Article/details/gtsnatcjsq.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.ybcxt.top/Article/details/gtbiyekqjx.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yj20258.top/Article/details/gtwlhmafsw.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhengqikj.top/Article/details/gtprregfoi.html

[J06] 计算两时间之差
来源：http://dali.cheryme.top/Article/details/gtyzpiltjn.html

Py:   (end - start).total_seconds()
来源：http://dali.dashuyun.cn/Article/details/gtwgqbnumm.html

PHP:  $end->diff($start)->days;
来源：http://dali.snrcjt.cn/Article/details/gthzbfnoss.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.gaohongyu789.top/Article/details/gtethvwjlx.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.pycfn.com/Article/details/gtehykefel.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.gotoacloud.top/Article/details/gttksftzuv.html

Go:   end.Sub(start).Hours()
来源：http://dali.tianlin.xyz/Article/details/gtyndfveix.html

Ruby: end - start                 # 返回秒数
来源：http://dali.gzhubu.top/Article/details/gtcmjpicdp.html

C#:   (end - start).TotalSeconds
来源：http://dali.cashguo.top/Article/details/gtjbssmhbh.html

[J07] 比较两个日期
来源：http://dali.yj20258.top/Article/details/gtrfsoatut.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yangfankeji.com/Article/details/gtmxitwaqb.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.ehwqpu.com/Article/details/gtpkaqshpy.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.jlsjyb.cn/Article/details/gtqsptxwmf.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.havefunace.top/Article/details/gtntkjoiqb.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.tanke756.top/Article/details/gtwrtvdezg.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.aizwys.cn/Article/details/gtendeipkr.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.feifeiyinyue.top/Article/details/gtdcjjzepd.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.tian-w.cn/Article/details/gtohhqmpom.html

[J08] 提取年月日与星期
来源：http://dali.yj202588.top/Article/details/gtfizscuwc.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.shanyushiyangtech.top/Article/details/gtqagkbrap.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.nwbrower.top/Article/details/gtierknoae.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.shuidangran.top/Article/details/gtohgjmyol.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnkatbqeo.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.shangyingyoupin.top/Article/details/gtwqxndaho.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.haohaochexian.top/Article/details/gtaydrgnqb.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.shanyushiyangkeji.top/Article/details/gtderyjfbr.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yvedp.cn/Article/details/gtnkqjpgdb.html

[J09] 时区处理
来源：http://dali.tanke756.top/Article/details/gtyiipawhu.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.shuidangran.top/Article/details/gtrrrkpbey.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.sysykeji.top/Article/details/gtzbvxpjrg.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xuanzx.com/Article/details/gtfagmjnma.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jiagoushi.top/Article/details/gthmqirzvu.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdkydynkq.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.dashuyun.cn/Article/details/gtpqhbdieo.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhongyouzk.top/Article/details/gtpaygwhnr.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yj20258.top/Article/details/gtthjxtraw.html

[J10] 取今天 / 本月第一天
来源：http://dali.cdnleiting.top/Article/details/gtnvowkjnc.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtrnvevdqg.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.aizwys.cn/Article/details/gtczgoyyfd.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.shangyingyoupin.top/Article/details/gtiiiuxshy.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.meibo888.top/Article/details/gtdicpsvky.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.gaohongyu789.top/Article/details/gtubeliytl.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxjwukclw.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwolungpb.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.sufxvd.cn/Article/details/gtsrtxppqg.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjojgyrbi.html

K. JSON 与序列化
来源：http://dali.jinqigfzy.top/Article/details/gtblxdqbnz.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtqpybmckj.html

[K01] 对象转 JSON 字符串
来源：http://dali.gogol.net.cn/Article/details/gtnkqickfv.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwcorccye.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.gotoacloud.top/Article/details/gtdbudtmwr.html

JS:   JSON.stringify(obj)
来源：http://dali.yonumen.top/Article/details/gtaehvhees.html

TS:   JSON.stringify(obj)
来源：http://dali.shuidangran.top/Article/details/gtfgewgvtp.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.wangshuangyany.cn/Article/details/gtoeljldmo.html

Go:   json.Marshal(obj)
来源：http://dali.cashguo.top/Article/details/gtaxlpypbm.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.mhx1999.top/Article/details/gtfpyiwteq.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.cucudq.cn/Article/details/gtahhizltb.html

[K02] JSON 字符串转对象
来源：http://dali.zhoulong.xyz/Article/details/gtqfbmakjb.html

Py:   json.loads(s)
来源：http://dali.birdmap.top/Article/details/gtwdhwldbf.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.chenzaomai.com/Article/details/gtpisrmbpl.html

JS:   JSON.parse(s)
来源：http://dali.yonumen.top/Article/details/gthblnlurk.html

TS:   JSON.parse(s)
来源：http://dali.ydzc1.top/Article/details/gtnjrkupfk.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.shangyingyoupin.top/Article/details/gtjqvmcypg.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.svipenyu.cn/Article/details/gtpbrmosku.html

Ruby: JSON.parse(s)
来源：http://dali.tian-w.cn/Article/details/gtqzkpqdzf.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.sweek.top/Article/details/gthdqjwxzj.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.ybcxt.top/Article/details/gtgfoddpgd.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yonumen.top/Article/details/gtonsjxknb.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.fzhhl.top/Article/details/gtabajgoql.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.hysaishi.cn/Article/details/gtekaltrmu.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.sufxvd.cn/Article/details/gthhgrsmoy.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gttofbymjx.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.yangfankeji.com/Article/details/gtjojtqwpf.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvypqwugq.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.pycfn.com/Article/details/gtqnxiibix.html

[K04] 读取 JSON 文件
来源：http://dali.yj20258.top/Article/details/gtoqkplpxt.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zhoulong.xyz/Article/details/gtnrfcwsgp.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.hysaishi.cn/Article/details/gtivjutylt.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.nanxuanxn.top/Article/details/gtrszgivnf.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinqigfzy.top/Article/details/gtvphihefv.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.jqgfzy.top/Article/details/gtzizefiuh.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.yangfankeji.com/Article/details/gtrqujibof.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmknjgzwr.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.shangyingyoupin.top/Article/details/gthbrbtkij.html

[K05] 深拷贝对象
来源：http://dali.yuxming.cn/Article/details/gtwgdfvlij.html

Py:   copy.deepcopy(obj)
来源：http://dali.jyoumei.cn/Article/details/gtrdnxiqwk.html

PHP:  unserialize(serialize($obj));
来源：http://dali.aibaodan.cn/Article/details/gtuklwetfe.html

JS:   structuredClone(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtgsvsbigh.html

TS:   structuredClone(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtoepprvyt.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.meibo888.top/Article/details/gtpgzozcop.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zycfv.cn/Article/details/gthfwulwda.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yueranfly.top/Article/details/gttxejzxqq.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.haohaochexian.top/Article/details/gtymvukdxm.html

[K06] 解析 URL 查询串
来源：http://dali.nwbrower.top/Article/details/gtgamlgrjn.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.guannengcc.top/Article/details/gtcpowwraz.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zycfv.cn/Article/details/gtcqpafmad.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.yj20258888.top/Article/details/gtvhyqgwrr.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.aizwys.cn/Article/details/gtaesifxkd.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.dianchejie.cn/Article/details/gtnhksvqsn.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.sxryk.cn/Article/details/gthkbigwir.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.yangfankeji.com/Article/details/gtsmqzmkew.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.svipenyu.cn/Article/details/gtzfmaaril.html

[K07] 进制转换
来源：http://dali.feifeiyinyue.top/Article/details/gtihmpkapu.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yj202588.top/Article/details/gtkbljhtdi.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.chenjidiqi.icu/Article/details/gtbaihpueu.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.yangfankeji.com/Article/details/gtjmbfmvid.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.daxiang520.top/Article/details/gtdevhphag.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.wangshuangyany.cn/Article/details/gtvclyphlz.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yj20258888.top/Article/details/gtquycqsec.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.xinyue.icu/Article/details/gtcsadewff.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.zhijiandao.cn/Article/details/gtaqilvubb.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.andypj.xyz/Article/details/gtbrxocamk.html

Py:   pickle.dumps(obj)
来源：http://dali.dashuyun.cn/Article/details/gtioggzyje.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.ppjwa.cn/Article/details/gtpzemekax.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jinyuanbaomall.cn/Article/details/gtehrcogjd.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yj20258888.top/Article/details/gtsqbhelaq.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.zycfv.cn/Article/details/gtyefiqkji.html

Go:   encoding/gob
来源：http://dali.jqgfzy.top/Article/details/gtvfkpajnz.html

Ruby: Marshal.dump(obj)
来源：http://dali.cucudq.cn/Article/details/gtdjwemzdy.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.ybcxt.top/Article/details/gtwycanwvv.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtzfiikclo.html

L. 网络请求
来源：http://dali.yuxming.cn/Article/details/gtvsokbfdp.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtgzonirpm.html

[L01] 发送 GET 请求
来源：http://dali.tian-w.cn/Article/details/gtuiaeqvvs.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.ybcxt.top/Article/details/gtvhemzpud.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.andypj.xyz/Article/details/gtukkmfcwx.html

JS:   await fetch(url)
来源：http://dali.nanxinkj.top/Article/details/gtaclrnylk.html

TS:   await fetch(url)
来源：http://dali.yangfankeji.com/Article/details/gtxntnnfej.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.xuetiantiany.cn/Article/details/gtgyexywjr.html

Go:   resp, err := http.Get(url)
来源：http://dali.yvedp.cn/Article/details/gtmrkuuxff.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.quarkkingdee.top/Article/details/gtzfjpiglq.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaptwyvox.html

[L02] 发送 POST JSON
来源：http://dali.chenzaomai.com/Article/details/gtiyglgytu.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.andypj.xyz/Article/details/gtncsfwgcf.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jiagoushi.top/Article/details/gtwreafddj.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.guowangkeji.top/Article/details/gttlytfnug.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.redwolf501.top/Article/details/gtnmhffbmd.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.xinyue.icu/Article/details/gtvpwoowut.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.yvedp.cn/Article/details/gtohdkpqlm.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.shanyushiyangtech.top/Article/details/gtnvmjjalr.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jqgufenzy.top/Article/details/gtqzfxzvgq.html


<!-- 参考信息 -->