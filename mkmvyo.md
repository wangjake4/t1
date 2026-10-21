代发 wailian999

[H07] 断言
来源：http://dali.chenlongwang.top/Article/details/gtwhaoykdd.html

Py:   assert x > 0, "必须为正"
来源：http://dali.mhx1999.top/Article/details/gtfakojarm.html

PHP:  assert($x > 0);
来源：http://dali.jiagoushi.top/Article/details/gtsjaqdnke.html

JS:   console.assert(x > 0);
来源：http://dali.hysaishi.cn/Article/details/gtxxsliqkm.html

TS:   console.assert(x > 0);
来源：http://dali.0kj1m.cn/Article/details/gtcyxtyeum.html

Java: assert x > 0 : "必须为正";
来源：http://dali.shanyushiyangtech.top/Article/details/gtvkfvpjva.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.gaohongyu789.top/Article/details/gtbuqpacor.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.shuidangran.top/Article/details/gtacdqolle.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jyoumei.cn/Article/details/gtkijundtl.html

[H08] 获取错误信息与堆栈
来源：http://dali.guannengcc.top/Article/details/gtkgoaydpq.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yueranfly.top/Article/details/gtcekqoinb.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hnxiangtu.top/Article/details/gtnrssjgpy.html

JS:   e.message;  e.stack
来源：http://dali.yongpay.top/Article/details/gtplhaltrj.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jqgfzy.top/Article/details/gtbppsnxcx.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.wangdashe.top/Article/details/gtilzrxemx.html

Go:   err.Error()
来源：http://dali.snrcjt.cn/Article/details/gtgvayshtt.html

Ruby: e.message;  e.backtrace
来源：http://dali.ybcxt.top/Article/details/gtxphmsiqg.html

C#:   e.Message;  e.StackTrace
来源：http://dali.birdmap.top/Article/details/gtfaygfsau.html

[H09] 带错误码的异常
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdcqiaant.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yuanzhike.top/Article/details/gtrydpcxoo.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.nanxuanxn.top/Article/details/gtunwumlsn.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.havefunace.top/Article/details/gtrjbqmann.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.pengpengdd.cyou/Article/details/gtkmrobuzr.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.chenzaomai.com/Article/details/gtbjwrcfow.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.ppjwa.cn/Article/details/gteoztxvxd.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.chenjidiqi.icu/Article/details/gtfbrpnsnz.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.cdnleiting.top/Article/details/gtvmodedqw.html

[H10] 资源自动释放
来源：http://dali.mhx1999.top/Article/details/gtuzpujmxt.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.dianchejie.cn/Article/details/gtnpmeyuid.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.0kj1m.cn/Article/details/gtwrkerrfv.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.pycfn.com/Article/details/gtgojidofm.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiwmzmupl.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yangfankeji.com/Article/details/gtohibvtne.html

Go:   defer f.Close()
来源：http://dali.jianghu66.top/Article/details/gtqskdrkzn.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.kuanghao11.cn/Article/details/gtrdvshvzo.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.0kj1m.cn/Article/details/gtuwxsptui.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlzybwqbo.html

I. 正则表达式
来源：http://dali.aibaodan.cn/Article/details/gtbgqiafhx.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtswscczac.html

[I01] 判断是否匹配
来源：http://dali.cashguo.top/Article/details/gtqmrhnbei.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.pengpengdd.cyou/Article/details/gtlocjqbsd.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.aibaodan.cn/Article/details/gttntojkyz.html

JS:   /\d+/.test(s)
来源：http://dali.meibo888.top/Article/details/gtftozkoqp.html

TS:   /\d+/.test(s)
来源：http://dali.zhongyouzk.top/Article/details/gtqfxtaezd.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.hysaishi.cn/Article/details/gtuwxtpdnn.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.chenlongwang.top/Article/details/gtozluxcrj.html

Ruby: s.match?(/\d+/)
来源：http://dali.aizwys.cn/Article/details/gtmjadudhn.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbalcupsm.html

[I02] 提取所有匹配
来源：http://dali.snrcjt.cn/Article/details/gtzynphoby.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yuanzhike.top/Article/details/gthwbaxbis.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.fzhhl.top/Article/details/gtmrxbwdid.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.bjfxy.top/Article/details/gtpqmqairv.html

TS:   s.match(/\d+/g)
来源：http://dali.cashguo.top/Article/details/gtnadcutbt.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.shzxlz.cn/Article/details/gtmjclmtxk.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.hammf.cn/Article/details/gteuhqiuof.html

Ruby: s.scan(/\d+/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqtcqzpfu.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.quarkkingdee.top/Article/details/gtkegqacbf.html

[I03] 提取捕获分组
来源：http://dali.jqgfzy.top/Article/details/gtlhtsztpt.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.sufxvd.cn/Article/details/gtewwtrnlq.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.daria6918.cn/Article/details/gtnnxpcyzi.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.meibo888.top/Article/details/gtrytlgiju.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.9152youxi.cn/Article/details/gthdcjoqes.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.tian-w.cn/Article/details/gthkmnizjv.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jianghu66.top/Article/details/gtwsepzsfs.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.ydzc1.top/Article/details/gtibbswxjc.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.xinyue.icu/Article/details/gtdgrxrglk.html

[I04] 正则替换
来源：http://dali.xinyue.icu/Article/details/gtqtogzdxw.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zycfv.cn/Article/details/gtgrupsuow.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.fzhhl.top/Article/details/gtvllktauq.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.sufxvd.cn/Article/details/gtopxruykq.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.ivvv.top/Article/details/gtvxdbqzra.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.hnqzz.top/Article/details/gtoaknpkhi.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.tianlin.xyz/Article/details/gtprmzdtkm.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.ydzc1.top/Article/details/gtfxjglckc.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.sweek.top/Article/details/gtvadihorf.html

[I05] 按正则拆分
来源：http://dali.vqdsnc.cn/Article/details/gthtmsjeaz.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yvedp.cn/Article/details/gtiblyesnm.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.fzhhl.top/Article/details/gtnwyxvpwu.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.ivvv.top/Article/details/gtcamajulu.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.xuanzx.com/Article/details/gtphhsupig.html

Java: s.split("\\s*,\\s*")
来源：http://dali.wangshuangyany.cn/Article/details/gtweuznohs.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.tianlin.xyz/Article/details/gtxyhmtxxc.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jiagoushi.top/Article/details/gtrmodpguw.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.meibo888.top/Article/details/gtmhiqjahv.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.sxryk.cn/Article/details/gtpjunlwdz.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yj202588.top/Article/details/gtqbpdsuqo.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.shangyingyoupin.top/Article/details/gtmzrhbvht.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hysaishi.cn/Article/details/gtlvhxitac.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.cucudq.cn/Article/details/gtnjsjfbgz.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.tianlin.xyz/Article/details/gtqwacfuhn.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yangfankeji.com/Article/details/gtgnhjpgdw.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.daxiang520.top/Article/details/gtrokuacjy.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.pycfn.com/Article/details/gtbsejcris.html

[I07] 忽略大小写与多行模式
来源：http://dali.aibaodan.cn/Article/details/gtqkoqjfqt.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.hywenlv.cn/Article/details/gtuhaaflrr.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.meibo888.top/Article/details/gtrmyxuzrw.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.ybcxt.top/Article/details/gtdwvordir.html

TS:   /error/gim
来源：http://dali.hnqzz.top/Article/details/gtlqzqjmmn.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.cucudq.cn/Article/details/gtqkkqkqxf.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.redwolf501.top/Article/details/gtyocavavw.html

Ruby: s.scan(/error/i)
来源：http://dali.shuidangran.top/Article/details/gtlarvdrsc.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.gzhubu.top/Article/details/gtzwaromwk.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.cucudq.cn/Article/details/gtobqwsmal.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jianghu66.top/Article/details/gtecjyunfh.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.pengpengdd.cyou/Article/details/gtbvgwgoir.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cashguo.top/Article/details/gtfdsdsibh.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.nwbrower.top/Article/details/gtfxbgpmso.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.ppjwa.cn/Article/details/gtisddjpzp.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.guowangkeji.top/Article/details/gteswjaruu.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.vqdsnc.cn/Article/details/gtpcddsvvo.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.pycfn.com/Article/details/gtiybogjuf.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtllyaubaz.html

J. 日期与时间
来源：http://dali.wangdashe.top/Article/details/gtxenydanx.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gttemfblcv.html

[J01] 获取当前时间
来源：http://dali.dianchejie.cn/Article/details/gtftwmtyst.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.cucudq.cn/Article/details/gtadwrjhio.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yonumen.top/Article/details/gtfmnrijgl.html

JS:   new Date();  Date.now()
来源：http://dali.pengpengdd.cyou/Article/details/gtoobxfdeb.html

TS:   new Date();  Date.now()
来源：http://dali.shanyushiyangtech.top/Article/details/gtvwbfyxcp.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yanxiufei.cn/Article/details/gtomkxqnxx.html

Go:   time.Now()
来源：http://dali.nwbrower.top/Article/details/gtbsradmvx.html

Ruby: Time.now
来源：http://dali.yj202588.top/Article/details/gttbwgbvep.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbdvrzkku.html

[J02] 格式化输出
来源：http://dali.andypj.xyz/Article/details/gtcjnmndmj.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jyoumei.cn/Article/details/gtsecasmqv.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.yueranfly.top/Article/details/gtrcruwqce.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.nanxinkj.top/Article/details/gtupfnifsu.html

TS:   d.toISOString()
来源：http://dali.wangdashe.top/Article/details/gtonzeeyqg.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.zhixingplan.top/Article/details/gtbrbpjxcd.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvnhocbhm.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.9152youxi.cn/Article/details/gttmyehcpz.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.hywenlv.cn/Article/details/gtscqoofbj.html

[J03] 字符串解析为日期
来源：http://dali.ybcxt.top/Article/details/gtxfifqmve.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.dianchejie.cn/Article/details/gtrjyiaixc.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.quarkkingdee.top/Article/details/gtyfsnduur.html

JS:   new Date("2024-01-02")
来源：http://dali.hongshengwenyu.top/Article/details/gtvswneazz.html

TS:   new Date("2024-01-02")
来源：http://dali.fzhhl.top/Article/details/gttnrsxkeh.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hfpthk.cn/Article/details/gtmyrzitkd.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.daxiang520.top/Article/details/gtmigekmrh.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.sweek.top/Article/details/gtqqztpspg.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zhiwuduotai.top/Article/details/gtzebcrpmt.html

[J04] 时间戳与日期互转
来源：http://dali.pycfn.com/Article/details/gtrnsixkzp.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.sufxvd.cn/Article/details/gtkgmrmkwh.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jyoumei.cn/Article/details/gtirmdkotj.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.andypj.xyz/Article/details/gtcmteidot.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jinqigfzy.top/Article/details/gtdmavcbda.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.meibo888.top/Article/details/gtfirzfxtu.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yuanzhike.top/Article/details/gtlkalxkxp.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.cheryme.top/Article/details/gtainmpsod.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hfpthk.cn/Article/details/gtcxaniire.html

[J05] 时间加减（加 7 天）
来源：http://dali.cucudq.cn/Article/details/gtzbplzhcz.html

Py:   now + timedelta(days=7)
来源：http://dali.cdnleiting.top/Article/details/gttseddked.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.pycfn.com/Article/details/gtqucisiqd.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.pengpengdd.cyou/Article/details/gtogzsvred.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.daria6918.cn/Article/details/gtpnywpjtd.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.cdnleiting.top/Article/details/gtnroojsbb.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.gotoacloud.top/Article/details/gtnlthkwhi.html

Ruby: Time.now + 7 * 86400
来源：http://dali.chenlongwang.top/Article/details/gtyruzokyz.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yuxming.cn/Article/details/gtunclbknv.html

[J06] 计算两时间之差
来源：http://dali.sweek.top/Article/details/gtaprsqphj.html

Py:   (end - start).total_seconds()
来源：http://dali.wangdashe.top/Article/details/gtiwvxgsbd.html

PHP:  $end->diff($start)->days;
来源：http://dali.haohaochexian.top/Article/details/gtchsepuur.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.cashguo.top/Article/details/gtlrxsuyhc.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yonumen.top/Article/details/gtbsxbnizi.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.xziqi.cn/Article/details/gtefhzcosk.html

Go:   end.Sub(start).Hours()
来源：http://dali.yuxming.cn/Article/details/gtjhbsroqm.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jlsjyb.cn/Article/details/gtfdupiibc.html

C#:   (end - start).TotalSeconds
来源：http://dali.kuanghao11.cn/Article/details/gtviddxhvk.html

[J07] 比较两个日期
来源：http://dali.0kj1m.cn/Article/details/gtowwiddud.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmxhbiofc.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.havefunace.top/Article/details/gtrdqrugho.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.havefunace.top/Article/details/gtsuizmvky.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.shzxlz.cn/Article/details/gtmmngrqzz.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jiagoushi.top/Article/details/gtlbydthvk.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.xylfe.cn/Article/details/gtlncsprsr.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.jianghu66.top/Article/details/gtjjbuwidz.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.wangshuangyany.cn/Article/details/gtbmrlpcwj.html

[J08] 提取年月日与星期
来源：http://dali.cheryme.top/Article/details/gtfjhgimvz.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhijiandao.cn/Article/details/gtdpjkyrrg.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.wangdashe.top/Article/details/gtbkaqexhu.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.shuidangran.top/Article/details/gtnlfdisrz.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.9152youxi.cn/Article/details/gtamoqwoua.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.ehwqpu.com/Article/details/gtzhpqfmnw.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.cqqwz.cn/Article/details/gtmmbidobm.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvcqvfffl.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxttzskzo.html

[J09] 时区处理
来源：http://dali.hnqzz.top/Article/details/gtrjsozrqf.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.aibaodan.cn/Article/details/gtvqegyzax.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jianghu66.top/Article/details/gtiejxircz.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.birdmap.top/Article/details/gtyhjnxdan.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.iojbl.cn/Article/details/gtpyqgyaxx.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.andypj.xyz/Article/details/gtqregtwfy.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.ybcxt.top/Article/details/gttjsbwcci.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.gzhubu.top/Article/details/gtufzazhoq.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.bjfxy.top/Article/details/gtaeyqpnhr.html

[J10] 取今天 / 本月第一天
来源：http://dali.cqqwz.cn/Article/details/gtkgwaxvvx.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrgvwwawj.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.xuanzx.com/Article/details/gtykydevtd.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.pengpengdd.cyou/Article/details/gtxnzkcnfa.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jyoumei.cn/Article/details/gtvtznmkuq.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zdqjudy.top/Article/details/gturkrxjye.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.hysaishi.cn/Article/details/gtxdeozzse.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqwlaajcu.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.svipenyu.cn/Article/details/gtmrmvpvxg.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtdxroxwuw.html

K. JSON 与序列化
来源：http://dali.zhixingplan.top/Article/details/gtjgrrpnnv.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtcnekopud.html

[K01] 对象转 JSON 字符串
来源：http://dali.xinyue.icu/Article/details/gtlyimfkeh.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.cheryme.top/Article/details/gtjjsdqwok.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yongpay.top/Article/details/gtldbnihvc.html

JS:   JSON.stringify(obj)
来源：http://dali.cucudq.cn/Article/details/gtgkrznefq.html

TS:   JSON.stringify(obj)
来源：http://dali.nanxinkj.top/Article/details/gtvnordetx.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.nanxuanxn.top/Article/details/gtdnwpksjs.html

Go:   json.Marshal(obj)
来源：http://dali.9152youxi.cn/Article/details/gtrhtonthd.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yvedp.cn/Article/details/gtfzcjjrpc.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.yonumen.top/Article/details/gtxcnetery.html

[K02] JSON 字符串转对象
来源：http://dali.nanxinkj.top/Article/details/gtdzjwgpae.html

Py:   json.loads(s)
来源：http://dali.hywenlv.cn/Article/details/gtqmhiwsjm.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.havefunace.top/Article/details/gtuqklwkbu.html

JS:   JSON.parse(s)
来源：http://dali.yueranfly.top/Article/details/gtuphwuibd.html

TS:   JSON.parse(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtddgrddma.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.kuanghao11.cn/Article/details/gttxgzmjkx.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.cheryme.top/Article/details/gtiiaxjeok.html

Ruby: JSON.parse(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtkrqlcszm.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.andypj.xyz/Article/details/gthfhojvrb.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.wangshuangyany.cn/Article/details/gtgmokhhnm.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.gzhubu.top/Article/details/gtslmxtvyt.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.vqdsnc.cn/Article/details/gtyskliona.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.ehwqpu.com/Article/details/gthjgikwew.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvfpkncxn.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlbvpzlth.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.316326.xyz/Article/details/gthugkamvn.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.tian-w.cn/Article/details/gtnunndzpb.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.ivvv.top/Article/details/gtewgxsmfm.html

[K04] 读取 JSON 文件
来源：http://dali.zhiwuduotai.top/Article/details/gtoiyejgsq.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.fengsongda.top/Article/details/gtkmnakkxn.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.xylfe.cn/Article/details/gtrcuiavzw.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yj20258.top/Article/details/gtasffkdlj.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.zhoulong.xyz/Article/details/gtyxoxpopu.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.birdmap.top/Article/details/gtgzdbufvw.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.havefunace.top/Article/details/gtuzkobmyl.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.nanxinkj.top/Article/details/gtiznlhdbq.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.snrcjt.cn/Article/details/gtvxwrnzli.html

[K05] 深拷贝对象
来源：http://dali.yvedp.cn/Article/details/gtytdhotrt.html

Py:   copy.deepcopy(obj)
来源：http://dali.redwolf501.top/Article/details/gtisbgttkp.html

PHP:  unserialize(serialize($obj));
来源：http://dali.hywenlv.cn/Article/details/gtozslftgx.html

JS:   structuredClone(obj)
来源：http://dali.ppjwa.cn/Article/details/gtktymhjos.html

TS:   structuredClone(obj)
来源：http://dali.sxryk.cn/Article/details/gtcmzkstyk.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.xuetiantiany.cn/Article/details/gttoxduere.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.dashuyun.cn/Article/details/gtxzwliyyh.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zycfv.cn/Article/details/gteeweywxl.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.zhiwuduotai.top/Article/details/gthfxdimob.html

[K06] 解析 URL 查询串
来源：http://dali.havefunace.top/Article/details/gtgvmbshwc.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.hysaishi.cn/Article/details/gtpgmqzulw.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.jinghuilouyu.cn/Article/details/gtzqysvjpk.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.c1oappe.top/Article/details/gtomsklpwj.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sweek.top/Article/details/gtihjdyqyj.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jqgufenzy.top/Article/details/gtkrbumrna.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.iojbl.cn/Article/details/gtufilzqnh.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.fengsongda.top/Article/details/gtimxyqkmd.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.shuidangran.top/Article/details/gtpxcivaap.html

[K07] 进制转换
来源：http://dali.nwbrower.top/Article/details/gthkhaptwy.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.aibaodan.cn/Article/details/gtnmvqmmti.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtooiqcozl.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.andypj.xyz/Article/details/gtddagwsrd.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.ybcxt.top/Article/details/gtocptskzg.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.yj20258.top/Article/details/gtpsmjtgrb.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.daria6918.cn/Article/details/gtpzensbmf.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtycbefzda.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.aibaodan.cn/Article/details/gtybxwvmtz.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.aibaodan.cn/Article/details/gtqqqesqsz.html

Py:   pickle.dumps(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtgkmffxer.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.chenzaomai.com/Article/details/gtebexohlm.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yvedp.cn/Article/details/gtyaoqtxzk.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zycfv.cn/Article/details/gtkguwvsko.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.cqqwz.cn/Article/details/gtskrocxtp.html

Go:   encoding/gob
来源：http://dali.shanyushiyangtech.top/Article/details/gtqixmtesg.html

Ruby: Marshal.dump(obj)
来源：http://dali.aizwys.cn/Article/details/gtlritmifg.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.cheryme.top/Article/details/gtgifphzxm.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtglqucjnb.html

L. 网络请求
来源：http://dali.snrcjt.cn/Article/details/gtpexrcofs.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtwcxicjge.html

[L01] 发送 GET 请求
来源：http://dali.sxryk.cn/Article/details/gtkulnxrko.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.dashuyun.cn/Article/details/gtoozskpip.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.fzhhl.top/Article/details/gtwlmefwya.html

JS:   await fetch(url)
来源：http://dali.dianchejie.cn/Article/details/gtvtromdxb.html

TS:   await fetch(url)
来源：http://dali.tianlin.xyz/Article/details/gtmjxotphs.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhoulong.xyz/Article/details/gtucvjvcqk.html

Go:   resp, err := http.Get(url)
来源：http://dali.sweek.top/Article/details/gtvyftista.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.kuanghao11.cn/Article/details/gtbirgbmzs.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.xziqi.cn/Article/details/gtqgnmytdi.html

[L02] 发送 POST JSON
来源：http://dali.jinghuilouyu.cn/Article/details/gtsagdtxxq.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.nwbrower.top/Article/details/gtkpsjlegz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.tianlin.xyz/Article/details/gtxtiyoxcr.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.pycfn.com/Article/details/gttugikajl.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zycfv.cn/Article/details/gtndrecnzr.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.tanke756.top/Article/details/gtbrteewos.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.chenjidiqi.icu/Article/details/gtqqkihjjk.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhijiandao.cn/Article/details/gtsnsybnta.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.sweek.top/Article/details/gtqljcfzon.html


<!-- 参考信息 -->