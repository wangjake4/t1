代发 wailian999

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yuxming.cn/Article/details/gttiwxcfus.html

Ruby: rescue ArgumentError => e
来源：http://dali.haohaochexian.top/Article/details/gtokvydqlx.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtkzcifvuw.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhoulong.xyz/Article/details/gtnroosoqt.html

Py:   value = d.get("k") or default
来源：http://dali.shzxlz.cn/Article/details/gtsparjhqt.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.shzxlz.cn/Article/details/gttmgasqjx.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yonumen.top/Article/details/gtlwjuosfu.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jinghuilouyu.cn/Article/details/gtdhuzixnp.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.nwbrower.top/Article/details/gtviyweqri.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.gogol.net.cn/Article/details/gtkoijgsho.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hfpthk.cn/Article/details/gtkeygiqqq.html

C#:   obj?.A?.B ?? default
来源：http://dali.yuxming.cn/Article/details/gtioqjgiiy.html

[H07] 断言
来源：http://dali.jyoumei.cn/Article/details/gtnanqktep.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yueranfly.top/Article/details/gtsogrxyax.html

PHP:  assert($x > 0);
来源：http://dali.guannengcc.top/Article/details/gtjtqztcxs.html

JS:   console.assert(x > 0);
来源：http://dali.hysaishi.cn/Article/details/gtaproaqbr.html

TS:   console.assert(x > 0);
来源：http://dali.jyoumei.cn/Article/details/gthxpuqtpq.html

Java: assert x > 0 : "必须为正";
来源：http://dali.havefunace.top/Article/details/gtjtvyqurz.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.9152youxi.cn/Article/details/gtvsozshao.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hnxiangtu.top/Article/details/gtxcahkrsd.html

C#:   Debug.Assert(x > 0);
来源：http://dali.gotoacloud.top/Article/details/gtdmzfmgxy.html

[H08] 获取错误信息与堆栈
来源：http://dali.xziqi.cn/Article/details/gtpcpqwmhe.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.cucudq.cn/Article/details/gtnsbmlpmn.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yueranfly.top/Article/details/gtnwpyuvff.html

JS:   e.message;  e.stack
来源：http://dali.sufxvd.cn/Article/details/gtkymxnsgd.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjxvlqdcn.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhijiandao.cn/Article/details/gtcqkxfasn.html

Go:   err.Error()
来源：http://dali.xylfe.cn/Article/details/gtsiejvylb.html

Ruby: e.message;  e.backtrace
来源：http://dali.andypj.xyz/Article/details/gttrdktvss.html

C#:   e.Message;  e.StackTrace
来源：http://dali.ywan-chungtsiang.top/Article/details/gtamukfzbu.html

[H09] 带错误码的异常
来源：http://dali.yongpay.top/Article/details/gtasafwdah.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.daria6918.cn/Article/details/gthfidyknu.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.tian-w.cn/Article/details/gtahgdhxgl.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yj202588.top/Article/details/gtntueaheb.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.dianchejie.cn/Article/details/gtuuznluup.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zycfv.cn/Article/details/gtkpmnyfeh.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.ehwqpu.com/Article/details/gtxqzzefpz.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yj20258888.top/Article/details/gtgjcnhpdh.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhixingplan.top/Article/details/gtqmiwlpnc.html

[H10] 资源自动释放
来源：http://dali.zycfv.cn/Article/details/gtvgvcnsdq.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yvedp.cn/Article/details/gtzlinwzhf.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jlsjyb.cn/Article/details/gtctvhcmij.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.andypj.xyz/Article/details/gtubchrzxi.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.aibaodan.cn/Article/details/gtmqfytfun.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.sufxvd.cn/Article/details/gtdjjrfyki.html

Go:   defer f.Close()
来源：http://dali.sufxvd.cn/Article/details/gtfcqxaqth.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hysaishi.cn/Article/details/gtfxrpuiml.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.wangdashe.top/Article/details/gtrqoaxdgb.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtkxzpsedq.html

I. 正则表达式
来源：http://dali.ybcxt.top/Article/details/gtruaijnvi.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gteklcvjak.html

[I01] 判断是否匹配
来源：http://dali.jinqigufen.top/Article/details/gtuhtswyeg.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgpkaenqo.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yanxiufei.cn/Article/details/gtqvdetdkn.html

JS:   /\d+/.test(s)
来源：http://dali.jianghu66.top/Article/details/gtmhsxmhke.html

TS:   /\d+/.test(s)
来源：http://dali.yvedp.cn/Article/details/gtxzttmxol.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.dashuyun.cn/Article/details/gtuuhfqxth.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yj20258888.top/Article/details/gtmkgkytoq.html

Ruby: s.match?(/\d+/)
来源：http://dali.andypj.xyz/Article/details/gtrovqtqop.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.gotoacloud.top/Article/details/gtwmolcwky.html

[I02] 提取所有匹配
来源：http://dali.sweek.top/Article/details/gtsguqazsf.html

Py:   re.findall(r"\d+", s)
来源：http://dali.fengsongda.top/Article/details/gtfqjtinqr.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.sweek.top/Article/details/gtvtmnwyrf.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.gotoacloud.top/Article/details/gtjvuamrny.html

TS:   s.match(/\d+/g)
来源：http://dali.kuanghao11.cn/Article/details/gtrtloeqnl.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.nwbrower.top/Article/details/gtzmxpsedq.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqlhzwixk.html

Ruby: s.scan(/\d+/)
来源：http://dali.andypj.xyz/Article/details/gtwahefmkw.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yangfankeji.com/Article/details/gtfyxgdcpi.html

[I03] 提取捕获分组
来源：http://dali.aibaodan.cn/Article/details/gtbcmldlnd.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.guowangkeji.top/Article/details/gtrtmhzcve.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hfpthk.cn/Article/details/gtuzuysuos.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.feifeiyinyue.top/Article/details/gtjpnfqski.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.birdmap.top/Article/details/gtnldfcfkq.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yonumen.top/Article/details/gtsgzvyyud.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhixingplan.top/Article/details/gtigtwqhhe.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.shzxlz.cn/Article/details/gtnjjpjjrg.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yj20258.top/Article/details/gtvloapwpc.html

[I04] 正则替换
来源：http://dali.jqgfzy.top/Article/details/gtkrkrytkw.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhoulong.xyz/Article/details/gtpysanulm.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.iojbl.cn/Article/details/gtfyidercx.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.snrcjt.cn/Article/details/gtcggbpscu.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.hnqzz.top/Article/details/gtyfajfnjv.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.haohaochexian.top/Article/details/gtelfimwxj.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.dashuyun.cn/Article/details/gtpavxhwez.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yvedp.cn/Article/details/gtldyhlvzx.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.chenjidiqi.icu/Article/details/gthujlioin.html

[I05] 按正则拆分
来源：http://dali.gaohongyu789.top/Article/details/gtddorkhgd.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.sysykeji.top/Article/details/gtjylxjkim.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.hammf.cn/Article/details/gtoucwezeh.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.hnqzz.top/Article/details/gtatrqiinj.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jqgfzy.top/Article/details/gtxttdhrrz.html

Java: s.split("\\s*,\\s*")
来源：http://dali.aibaodan.cn/Article/details/gteyvxlsvb.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.0kj1m.cn/Article/details/gteubljqtz.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.shzxlz.cn/Article/details/gtzpdnchzo.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.sweek.top/Article/details/gtpzjkmsmd.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.chenzaomai.com/Article/details/gtbhauacjx.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.xziqi.cn/Article/details/gtfyvwclrh.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.tianlin.xyz/Article/details/gtqwyhlxrc.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shzxlz.cn/Article/details/gtsdelypwy.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.nwbrower.top/Article/details/gtrixiydjn.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.shangyingyoupin.top/Article/details/gtwletahom.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.aibaodan.cn/Article/details/gtrmztuyka.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.sweek.top/Article/details/gtsrgsxksv.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.hammf.cn/Article/details/gtanznuadk.html

[I07] 忽略大小写与多行模式
来源：http://dali.shuidangran.top/Article/details/gtmlrolsfw.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yj20258888.top/Article/details/gtpfeslfut.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.ydzc1.top/Article/details/gtujiiccge.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.sysykeji.top/Article/details/gtununtwsb.html

TS:   /error/gim
来源：http://dali.9152youxi.cn/Article/details/gtiokjxrpq.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.shangyingyoupin.top/Article/details/gturxcfysc.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.aibaodan.cn/Article/details/gtntvxoxvn.html

Ruby: s.scan(/error/i)
来源：http://dali.tanke756.top/Article/details/gtdhphxudf.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yj20258888.top/Article/details/gtbospbpgh.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhengqikj.top/Article/details/gtjmuzfpjq.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.sweek.top/Article/details/gtnduwlxqq.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jlsjyb.cn/Article/details/gtqakcjeqq.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hfpthk.cn/Article/details/gtxcuxmlkg.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.andypj.xyz/Article/details/gtanoxtkqh.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yj202588.top/Article/details/gtmdpndezx.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.gotoacloud.top/Article/details/gtbscascrh.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhixingplan.top/Article/details/gtwacghnvd.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.cheryme.top/Article/details/gtdtnahjse.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtsimyupwn.html

J. 日期与时间
来源：http://dali.gotoacloud.top/Article/details/gtugeialky.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtmgycvxuv.html

[J01] 获取当前时间
来源：http://dali.tian-w.cn/Article/details/gtshcxdxks.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.iojbl.cn/Article/details/gtptdazogu.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.hnqzz.top/Article/details/gtyihlsjkq.html

JS:   new Date();  Date.now()
来源：http://dali.mhx1999.top/Article/details/gtgkcpfmel.html

TS:   new Date();  Date.now()
来源：http://dali.shzxlz.cn/Article/details/gthqkuvcmo.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.gzhubu.top/Article/details/gtlkdxfzhw.html

Go:   time.Now()
来源：http://dali.daxiang520.top/Article/details/gttmfyadwr.html

Ruby: Time.now
来源：http://dali.pycfn.com/Article/details/gtilxnwviy.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.smart0.xyz/Article/details/gtcziywpub.html

[J02] 格式化输出
来源：http://dali.jinqigfzy.top/Article/details/gtycjjukln.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yueranfly.top/Article/details/gtjvjqqnqq.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.sufxvd.cn/Article/details/gtjrqniohb.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.cqqwz.cn/Article/details/gtyxeynffr.html

TS:   d.toISOString()
来源：http://dali.quarkkingdee.top/Article/details/gtnjwcqcsk.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yuxming.cn/Article/details/gtintycrev.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.316326.xyz/Article/details/gtbfbhixcw.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.redwolf501.top/Article/details/gtlrbeayld.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.mhx1999.top/Article/details/gtcnkhentb.html

[J03] 字符串解析为日期
来源：http://dali.sweek.top/Article/details/gtvgqynyfv.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.gotoacloud.top/Article/details/gtyozfypki.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.0kj1m.cn/Article/details/gtygrzuudu.html

JS:   new Date("2024-01-02")
来源：http://dali.dashuyun.cn/Article/details/gtlszfojhv.html

TS:   new Date("2024-01-02")
来源：http://dali.gaohongyu789.top/Article/details/gtnhuhlnaq.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.bjfxy.top/Article/details/gtksvazexp.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.nanxinkj.top/Article/details/gtzdkghouc.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.pengpengdd.cyou/Article/details/gttjtqpsuo.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yj202588.top/Article/details/gtlftoedrf.html

[J04] 时间戳与日期互转
来源：http://dali.yj20258888.top/Article/details/gtpvebvngq.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.ybcxt.top/Article/details/gtwmnluypd.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yuxming.cn/Article/details/gtedosaboh.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.ydzc1.top/Article/details/gtgzbefuiy.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.vqdsnc.cn/Article/details/gtvbdorloc.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jinghuilouyu.cn/Article/details/gtdazqlius.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.sysykeji.top/Article/details/gtsbdfsscf.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.nanxinkj.top/Article/details/gtxmkecfha.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.meibo888.top/Article/details/gtnyyctklx.html

[J05] 时间加减（加 7 天）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlnvxzfgo.html

Py:   now + timedelta(days=7)
来源：http://dali.fengsongda.top/Article/details/gtqbwxfezq.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.chenzaomai.com/Article/details/gtpumhtcqe.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yongpay.top/Article/details/gtgdojlzdi.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yueranfly.top/Article/details/gtrihofrin.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.jinqigfzy.top/Article/details/gtevafiahe.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yvedp.cn/Article/details/gtcvauhfcv.html

Ruby: Time.now + 7 * 86400
来源：http://dali.chenjidiqi.icu/Article/details/gtqwpugamh.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.aibaodan.cn/Article/details/gtxtwkjsna.html

[J06] 计算两时间之差
来源：http://dali.guannengcc.top/Article/details/gtntrzjhwd.html

Py:   (end - start).total_seconds()
来源：http://dali.gotoacloud.top/Article/details/gttnwtoqvv.html

PHP:  $end->diff($start)->days;
来源：http://dali.cqqwz.cn/Article/details/gtbfpfhgwm.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.hywenlv.cn/Article/details/gtcyadohnx.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhiwuduotai.top/Article/details/gteknvznmu.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.nanxuanxn.top/Article/details/gtmgpfbvro.html

Go:   end.Sub(start).Hours()
来源：http://dali.zhijiandao.cn/Article/details/gtdnwfzpjs.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zhixingplan.top/Article/details/gthjwvqrwv.html

C#:   (end - start).TotalSeconds
来源：http://dali.shangyingyoupin.top/Article/details/gtvynspoxq.html

[J07] 比较两个日期
来源：http://dali.xziqi.cn/Article/details/gtvfkkwlqs.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.guannengcc.top/Article/details/gtqdzbtkvn.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.chenlongwang.top/Article/details/gthaoylisf.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.havefunace.top/Article/details/gthnwqkehq.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.yangfankeji.com/Article/details/gtambhubge.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.0kj1m.cn/Article/details/gtvlmsqzse.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.cqqwz.cn/Article/details/gtkqbslanu.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.gogol.net.cn/Article/details/gtgnoyosim.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhoulong.xyz/Article/details/gthizslaey.html

[J08] 提取年月日与星期
来源：http://dali.gotoacloud.top/Article/details/gtgfaghwfo.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.bjfxy.top/Article/details/gtgpozkaca.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.birdmap.top/Article/details/gtszzfeqle.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.pycfn.com/Article/details/gtgevbszuc.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.xziqi.cn/Article/details/gtdyzlpvdm.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.birdmap.top/Article/details/gtuampqqhm.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hfpthk.cn/Article/details/gtqgtsixvh.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.chenlongwang.top/Article/details/gtuibiqlru.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.guannengcc.top/Article/details/gtetzfdmuw.html

[J09] 时区处理
来源：http://dali.chenlongwang.top/Article/details/gtktstphzu.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.chenzaomai.com/Article/details/gtupkmgyfu.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.ehwqpu.com/Article/details/gtqnwfqpvj.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.tianlin.xyz/Article/details/gtwetfnaqe.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zdqjudy.top/Article/details/gtwdnaghuy.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jiagoushi.top/Article/details/gtqvvwrwhq.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.pengpengdd.cyou/Article/details/gthjebkohe.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.haohaochexian.top/Article/details/gttpucwzxa.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.smart0.xyz/Article/details/gtaesbvljq.html

[J10] 取今天 / 本月第一天
来源：http://dali.fzhhl.top/Article/details/gtgtnaloyu.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.hnqzz.top/Article/details/gtqjalurnt.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.dashuyun.cn/Article/details/gtdwibezcl.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.dianchejie.cn/Article/details/gtitisfthx.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.cdnleiting.top/Article/details/gtdaqfqjie.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.9152youxi.cn/Article/details/gtcqdyjqnq.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.kuanghao11.cn/Article/details/gtpjecmphi.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.ehwqpu.com/Article/details/gtkkarrjui.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yj202588.top/Article/details/gtcvhpxfow.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtsggizbfg.html

K. JSON 与序列化
来源：http://dali.dashuyun.cn/Article/details/gthnbxjikr.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtmmcovwau.html

[K01] 对象转 JSON 字符串
来源：http://dali.jlsjyb.cn/Article/details/gtcstjixor.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.shanyushiyangtech.top/Article/details/gtpjazzuad.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.ybcxt.top/Article/details/gtxxlenvdh.html

JS:   JSON.stringify(obj)
来源：http://dali.quarkkingdee.top/Article/details/gtmoriwvpb.html

TS:   JSON.stringify(obj)
来源：http://dali.jinqigufen.top/Article/details/gtkjovimvh.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.ppjwa.cn/Article/details/gtzvbikenk.html

Go:   json.Marshal(obj)
来源：http://dali.vqdsnc.cn/Article/details/gtzvthxxan.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhongyouzk.top/Article/details/gtjvvwbbgt.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.ivvv.top/Article/details/gtznwzpjoj.html

[K02] JSON 字符串转对象
来源：http://dali.cdnleiting.top/Article/details/gtuihcfedr.html

Py:   json.loads(s)
来源：http://dali.mhx1999.top/Article/details/gtgeyrfbhz.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.cucudq.cn/Article/details/gtxqiepwcs.html

JS:   JSON.parse(s)
来源：http://dali.zhengqikj.top/Article/details/gtvsiovwyy.html

TS:   JSON.parse(s)
来源：http://dali.bjfxy.top/Article/details/gtecwdcjsw.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.pycfn.com/Article/details/gtmrotfqdb.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.feifeiyinyue.top/Article/details/gtprioefqs.html

Ruby: JSON.parse(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtumatykfp.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtpxnknlje.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.ybcxt.top/Article/details/gtxnbxioqf.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jinyuanbaomall.cn/Article/details/gttitmnbzn.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.shangyingyoupin.top/Article/details/gtldykebvd.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.meibo888.top/Article/details/gtloqlrcky.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.ybcxt.top/Article/details/gtdqwyyxay.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.shzxlz.cn/Article/details/gtczcrzhgt.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.ivvv.top/Article/details/gtwckfqssk.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.gogol.net.cn/Article/details/gtjcdbtmbp.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmqzvpxok.html

[K04] 读取 JSON 文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gthtxrzclh.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.fengsongda.top/Article/details/gtzyycepkx.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yj202588.top/Article/details/gtgshkydql.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzcenyani.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ivvv.top/Article/details/gtoddgmzsi.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.dashuyun.cn/Article/details/gtgafiwtmd.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhoulong.xyz/Article/details/gtfbspccox.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.dianchejie.cn/Article/details/gtkopmgayd.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jlsjyb.cn/Article/details/gthfalkkvv.html

[K05] 深拷贝对象
来源：http://dali.nwbrower.top/Article/details/gtlrwwxawr.html

Py:   copy.deepcopy(obj)
来源：http://dali.guowangkeji.top/Article/details/gturuuvqoy.html

PHP:  unserialize(serialize($obj));
来源：http://dali.cdnleiting.top/Article/details/gtjawdnapt.html

JS:   structuredClone(obj)
来源：http://dali.hysaishi.cn/Article/details/gteosgjnjk.html

TS:   structuredClone(obj)
来源：http://dali.hnqzz.top/Article/details/gtffzwscxx.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zhengqikj.top/Article/details/gthfbngbma.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.gotoacloud.top/Article/details/gtbrfengvs.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.guowangkeji.top/Article/details/gtxdsfmuff.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.aibaodan.cn/Article/details/gtjditftta.html

[K06] 解析 URL 查询串
来源：http://dali.mhx1999.top/Article/details/gtresguhiz.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaqpsvkqn.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.daxiang520.top/Article/details/gtbvmgpaek.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.birdmap.top/Article/details/gtxnsnphaz.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xuanzx.com/Article/details/gtwvvrrjam.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.guowangkeji.top/Article/details/gtrbqqvjvd.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjubqiuqg.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.sxryk.cn/Article/details/gtcpqhoohs.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.ybcxt.top/Article/details/gtnumeisck.html

[K07] 进制转换
来源：http://dali.chenlongwang.top/Article/details/gtejgedwvg.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.pycfn.com/Article/details/gtgitbemid.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.hammf.cn/Article/details/gtpviteznq.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.chenlongwang.top/Article/details/gtmolwzsbh.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.jiagoushi.top/Article/details/gtxoxjpxyq.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.xuanzx.com/Article/details/gtzuimtrig.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jianghu66.top/Article/details/gtcbmxmbol.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.guannengcc.top/Article/details/gtovdyzlpc.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.hfpthk.cn/Article/details/gtkleuhxlw.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.ivvv.top/Article/details/gtjsexyboq.html

Py:   pickle.dumps(obj)
来源：http://dali.yonumen.top/Article/details/gtjiyoalqx.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.ydzc1.top/Article/details/gtrfgkecvg.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.daria6918.cn/Article/details/gthuegaoay.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jinqigfzy.top/Article/details/gtcewimcsf.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.haohaochexian.top/Article/details/gtsgrmilkc.html

Go:   encoding/gob
来源：http://dali.tian-w.cn/Article/details/gtruchsnwg.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtsmzetbxl.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.hammf.cn/Article/details/gtkfukzuxc.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtjyrsqozo.html

L. 网络请求
来源：http://dali.xuetiantiany.cn/Article/details/gtonyghfnm.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtzckmkcmv.html

[L01] 发送 GET 请求
来源：http://dali.jqgfzy.top/Article/details/gtfvxvwvmn.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.zhoulong.xyz/Article/details/gtgcvmiuss.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.xuanzx.com/Article/details/gtsdoiavug.html

JS:   await fetch(url)
来源：http://dali.bjfxy.top/Article/details/gtevhuafsg.html

TS:   await fetch(url)
来源：http://dali.zhoulong.xyz/Article/details/gtahucacoa.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.cheryme.top/Article/details/gtlypgmntj.html


<!-- 参考信息 -->