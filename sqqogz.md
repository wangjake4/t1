代发 wailian999

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhengqikj.top/Article/details/gtfmwnqxki.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhoulong.xyz/Article/details/gtidaaweey.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtkhcpfrcc.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.haohaochexian.top/Article/details/gtvpvaqkdj.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.iojbl.cn/Article/details/gtiaxcoetp.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yonumen.top/Article/details/gtcdckzxtu.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.0kj1m.cn/Article/details/gtlwnnvqcs.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.feifeiyinyue.top/Article/details/gtnwopstci.html

[H03] 主动抛出异常
来源：http://dali.tianlin.xyz/Article/details/gtiafxyrtb.html

Py:   raise ValueError("错误信息")
来源：http://dali.yuxming.cn/Article/details/gttlogupfa.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gtzxxwksdy.html

JS:   throw new Error("错误信息");
来源：http://dali.wangdashe.top/Article/details/gtzrjintrh.html

TS:   throw new Error("错误信息");
来源：http://dali.yj20258.top/Article/details/gtealoyrqs.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yj20258.top/Article/details/gtfjiijjue.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.fzhhl.top/Article/details/gtwgnzrykr.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.wangdashe.top/Article/details/gtiahquzbp.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.tian-w.cn/Article/details/gtszgkckyu.html

[H04] 自定义异常类型
来源：http://dali.yvedp.cn/Article/details/gtzesdftnc.html

Py:   class MyError(Exception): pass
来源：http://dali.jinqigfzy.top/Article/details/gtxtgrbrfi.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yvedp.cn/Article/details/gtyiuudxbv.html

JS:   class MyError extends Error {}
来源：http://dali.wangshuangyany.cn/Article/details/gtconxjypm.html

TS:   class MyError extends Error {}
来源：http://dali.guowangkeji.top/Article/details/gtmpednlwi.html

Java: class MyException extends RuntimeException {}
来源：http://dali.gogol.net.cn/Article/details/gtygqifoaj.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.shuidangran.top/Article/details/gtloipvkhx.html

Ruby: class MyError < StandardError; end
来源：http://dali.hysaishi.cn/Article/details/gtduwfilqv.html

C#:   class MyException : Exception {}
来源：http://dali.yj202588.top/Article/details/gtbiatjlgv.html

[H05] 捕获特定类型
来源：http://dali.xuetiantiany.cn/Article/details/gtnmbhkvpm.html

Py:   except ValueError as e:
来源：http://dali.jyoumei.cn/Article/details/gtawhcgtrt.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhiwuduotai.top/Article/details/gtjwsagboy.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.quarkkingdee.top/Article/details/gthivgtfun.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.kuanghao11.cn/Article/details/gtlyxernpn.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gthseghmis.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jianghu66.top/Article/details/gtpxzdeftw.html

Ruby: rescue ArgumentError => e
来源：http://dali.smart0.xyz/Article/details/gtpbflclts.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.haohaochexian.top/Article/details/gtpiwzrpqe.html

[H06] 可选值 / 空值安全访问
来源：http://dali.cashguo.top/Article/details/gtttfukyru.html

Py:   value = d.get("k") or default
来源：http://dali.hongshengwenyu.top/Article/details/gtagvxptbl.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hnxiangtu.top/Article/details/gtwmxeillq.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.andypj.xyz/Article/details/gtqecdsswq.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.nanxinkj.top/Article/details/gtysqeflvz.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.cucudq.cn/Article/details/gtoyzuigxw.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zycfv.cn/Article/details/gtijqlgsck.html

Ruby: d&.dig(:a, :b)
来源：http://dali.tanke756.top/Article/details/gteekswhjm.html

C#:   obj?.A?.B ?? default
来源：http://dali.yj20258888.top/Article/details/gtsibmetqk.html

[H07] 断言
来源：http://dali.aizwys.cn/Article/details/gtcwlpcpvd.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zdqjudy.top/Article/details/gtvxroxyuq.html

PHP:  assert($x > 0);
来源：http://dali.jinqigfzy.top/Article/details/gtjhfvmtkn.html

JS:   console.assert(x > 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnjyzuisa.html

TS:   console.assert(x > 0);
来源：http://dali.316326.xyz/Article/details/gthkvcfkrw.html

Java: assert x > 0 : "必须为正";
来源：http://dali.hnxiangtu.top/Article/details/gtyjpuwggz.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.birdmap.top/Article/details/gtthbttdfh.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.birdmap.top/Article/details/gtkvebcqel.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yj20258.top/Article/details/gtgxzpgwxw.html

[H08] 获取错误信息与堆栈
来源：http://dali.jinqigufen.top/Article/details/gtabxwgfvr.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.cqqwz.cn/Article/details/gtltikolqt.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.fzhhl.top/Article/details/gtwewtbtfg.html

JS:   e.message;  e.stack
来源：http://dali.cheryme.top/Article/details/gtcjexuupj.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.meibo888.top/Article/details/gtuzgdwuiw.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.9152youxi.cn/Article/details/gthrcoywmd.html

Go:   err.Error()
来源：http://dali.jinqigufen.top/Article/details/gtmycecmvm.html

Ruby: e.message;  e.backtrace
来源：http://dali.jyoumei.cn/Article/details/gtoyrlrfxi.html

C#:   e.Message;  e.StackTrace
来源：http://dali.0kj1m.cn/Article/details/gtmcrfhdcf.html

[H09] 带错误码的异常
来源：http://dali.birdmap.top/Article/details/gtfdtrqilo.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yuxming.cn/Article/details/gtbnyrkyzb.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.gzhubu.top/Article/details/gticmmapwy.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.feifeiyinyue.top/Article/details/gtkdfomfht.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.xuetiantiany.cn/Article/details/gtuhtxxukd.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.pengpengdd.cyou/Article/details/gtskwmodpu.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.vqdsnc.cn/Article/details/gtyvrurudu.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.snrcjt.cn/Article/details/gtvmgredpv.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.ppjwa.cn/Article/details/gtnipluffr.html

[H10] 资源自动释放
来源：http://dali.cqqwz.cn/Article/details/gtivmsseop.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhiwuduotai.top/Article/details/gtrscltykn.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.mhx1999.top/Article/details/gtvpzenvrl.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yonumen.top/Article/details/gtoynurelh.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.feifeiyinyue.top/Article/details/gtovutcxmy.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.iojbl.cn/Article/details/gtnvgwjhpp.html

Go:   defer f.Close()
来源：http://dali.hongshengwenyu.top/Article/details/gtbcibnnaz.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.sysykeji.top/Article/details/gtgxltgmyg.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.nwbrower.top/Article/details/gtnlaenyuc.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnqrykaco.html

I. 正则表达式
来源：http://dali.chenzaomai.com/Article/details/gtzlazjlau.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtgetyifrq.html

[I01] 判断是否匹配
来源：http://dali.yj20258888.top/Article/details/gtnxbewljb.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.hammf.cn/Article/details/gtebyschzb.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.tian-w.cn/Article/details/gtvhhhzqbo.html

JS:   /\d+/.test(s)
来源：http://dali.gogol.net.cn/Article/details/gtxopkhsml.html

TS:   /\d+/.test(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtkfmrrvtn.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.ybcxt.top/Article/details/gtndzdffcu.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.cheryme.top/Article/details/gtmwtbnrvd.html

Ruby: s.match?(/\d+/)
来源：http://dali.gotoacloud.top/Article/details/gtgvkqolrv.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jinqigufen.top/Article/details/gttvxumhyj.html

[I02] 提取所有匹配
来源：http://dali.cdnleiting.top/Article/details/gtcnwajfxp.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yvedp.cn/Article/details/gtxoptohne.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.sweek.top/Article/details/gthosfnvwl.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.ydzc1.top/Article/details/gtlbwssdzm.html

TS:   s.match(/\d+/g)
来源：http://dali.jyoumei.cn/Article/details/gtavtpvqsc.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jlsjyb.cn/Article/details/gtdpepjbsw.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jqgfzy.top/Article/details/gtruntgcea.html

Ruby: s.scan(/\d+/)
来源：http://dali.jianghu66.top/Article/details/gttvjbqprg.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.quarkkingdee.top/Article/details/gtwlxmwupf.html

[I03] 提取捕获分组
来源：http://dali.xuanzx.com/Article/details/gtugpwuilv.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.cdnleiting.top/Article/details/gthxuvwmri.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.sufxvd.cn/Article/details/gtwarxfheb.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.xziqi.cn/Article/details/gttgxonjsq.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.iojbl.cn/Article/details/gtuqkrcxes.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.pengpengdd.cyou/Article/details/gthinbtcav.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.aizwys.cn/Article/details/gtzuxkeehh.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yonumen.top/Article/details/gtfaimnwcz.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.nanxinkj.top/Article/details/gttrshxaun.html

[I04] 正则替换
来源：http://dali.wangshuangyany.cn/Article/details/gttcvxrmhn.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtseywgzpc.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.xinyue.icu/Article/details/gtfhjbcpef.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yanxiufei.cn/Article/details/gtcnepipzp.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.316326.xyz/Article/details/gtjkpbjquz.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.cucudq.cn/Article/details/gthecrqsys.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jinqigufen.top/Article/details/gtzhouxtks.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.cucudq.cn/Article/details/gtiomvziwv.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.bjfxy.top/Article/details/gtgodcster.html

[I05] 按正则拆分
来源：http://dali.aizwys.cn/Article/details/gtovbvihzg.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.haohaochexian.top/Article/details/gtcadpnjbc.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlplvdaia.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.birdmap.top/Article/details/gtbstdcxqq.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.316326.xyz/Article/details/gtukkqcurj.html

Java: s.split("\\s*,\\s*")
来源：http://dali.xuanzx.com/Article/details/gtpndgjflf.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jinqigfzy.top/Article/details/gtlpfnylde.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.cqqwz.cn/Article/details/gtnteelyop.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.nwbrower.top/Article/details/gteozeghji.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.chenlongwang.top/Article/details/gtcyukjutp.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.tanke756.top/Article/details/gtiucqutzy.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.xziqi.cn/Article/details/gtegxqzkyc.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jlsjyb.cn/Article/details/gtgwgafbqy.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hnqzz.top/Article/details/gthcxuhtqp.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.tianlin.xyz/Article/details/gtavmncaxo.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.yueranfly.top/Article/details/gtdzmydmch.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqtflxgfw.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.hongshengwenyu.top/Article/details/gtfgkoheoh.html

[I07] 忽略大小写与多行模式
来源：http://dali.guowangkeji.top/Article/details/gtllqlfztj.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jinqigfzy.top/Article/details/gtndjyhgwr.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yvedp.cn/Article/details/gtcdsiztrk.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.cqqwz.cn/Article/details/gtcncbpxpl.html

TS:   /error/gim
来源：http://dali.zhiwuduotai.top/Article/details/gtriuauqjq.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.vqdsnc.cn/Article/details/gtwrgypmio.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.xuetiantiany.cn/Article/details/gttkrfndnj.html

Ruby: s.scan(/error/i)
来源：http://dali.jqgufenzy.top/Article/details/gtdbwkkgpg.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.cucudq.cn/Article/details/gtwgburatn.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.dianchejie.cn/Article/details/gtxdmjfcoe.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.gotoacloud.top/Article/details/gtujgercop.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.gzhubu.top/Article/details/gtfhvssobi.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.dianchejie.cn/Article/details/gtiylsibly.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhixingplan.top/Article/details/gtenixgocy.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.smart0.xyz/Article/details/gthlrujxzf.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.kuanghao11.cn/Article/details/gtnsyjrtif.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jqgfzy.top/Article/details/gtuthdkglk.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yangfankeji.com/Article/details/gtysixdsgw.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtezvqoxie.html

J. 日期与时间
来源：http://dali.shuidangran.top/Article/details/gtlgczsclp.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtxthgyhas.html

[J01] 获取当前时间
来源：http://dali.zycfv.cn/Article/details/gtjkmxkxgm.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.iojbl.cn/Article/details/gtsftdazkj.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yongpay.top/Article/details/gtjigokaxb.html

JS:   new Date();  Date.now()
来源：http://dali.hongshengwenyu.top/Article/details/gtwtkvhejp.html

TS:   new Date();  Date.now()
来源：http://dali.shanyushiyangtech.top/Article/details/gtxusxcxob.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jianghu66.top/Article/details/gtjojhgkgo.html

Go:   time.Now()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzifieieh.html

Ruby: Time.now
来源：http://dali.cqqwz.cn/Article/details/gtujfisuqm.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhiwuduotai.top/Article/details/gtesdbemkt.html

[J02] 格式化输出
来源：http://dali.cashguo.top/Article/details/gtwvkfzpht.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ehwqpu.com/Article/details/gtcrnwgpok.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.shuidangran.top/Article/details/gtedutpxas.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.9152youxi.cn/Article/details/gtcomcdsxo.html

TS:   d.toISOString()
来源：http://dali.pycfn.com/Article/details/gtzsgbowut.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.hfpthk.cn/Article/details/gtnunpkpzm.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.hywenlv.cn/Article/details/gtverboyjn.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xinyue.icu/Article/details/gthxujcwwe.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jiagoushi.top/Article/details/gtwrtgiehw.html

[J03] 字符串解析为日期
来源：http://dali.cucudq.cn/Article/details/gtnvjyejrt.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.hongshengwenyu.top/Article/details/gtkyoervdv.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.jinghuilouyu.cn/Article/details/gtsqrvfbfj.html

JS:   new Date("2024-01-02")
来源：http://dali.aizwys.cn/Article/details/gtadbsmvvf.html

TS:   new Date("2024-01-02")
来源：http://dali.sufxvd.cn/Article/details/gtufcuyuuy.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.shangyingyoupin.top/Article/details/gtkqzzifkl.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.nanxinkj.top/Article/details/gtbjrfobkx.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxjtrahfl.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.quarkkingdee.top/Article/details/gtqdypfrcy.html

[J04] 时间戳与日期互转
来源：http://dali.ydzc1.top/Article/details/gtpgazwhvh.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.aibaodan.cn/Article/details/gtqipkphnw.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jlsjyb.cn/Article/details/gtfitneidh.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.xinyue.icu/Article/details/gtbhftmrxj.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.shzxlz.cn/Article/details/gtkworcfjw.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.havefunace.top/Article/details/gtiqqumdjo.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.fengsongda.top/Article/details/gtwjzmcsva.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.pycfn.com/Article/details/gtrttamqfc.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yonumen.top/Article/details/gtsknqldqe.html

[J05] 时间加减（加 7 天）
来源：http://dali.yj202588.top/Article/details/gtfgkvealk.html

Py:   now + timedelta(days=7)
来源：http://dali.fzhhl.top/Article/details/gtgdmqcign.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jqgufenzy.top/Article/details/gtpdvovdft.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.sufxvd.cn/Article/details/gtnnwmdowk.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhijiandao.cn/Article/details/gtkrwhnimd.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.gzhubu.top/Article/details/gtphppsrht.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.aibaodan.cn/Article/details/gtsrujlmaf.html

Ruby: Time.now + 7 * 86400
来源：http://dali.pengpengdd.cyou/Article/details/gtbxmdxzbs.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.cashguo.top/Article/details/gtxcjullmq.html

[J06] 计算两时间之差
来源：http://dali.pycfn.com/Article/details/gtqdrwqank.html

Py:   (end - start).total_seconds()
来源：http://dali.yj20258888.top/Article/details/gtsdwjgtqv.html

PHP:  $end->diff($start)->days;
来源：http://dali.tian-w.cn/Article/details/gtavacvthn.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.sxryk.cn/Article/details/gtochlnrev.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhongyouzk.top/Article/details/gtuuiltply.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.ybcxt.top/Article/details/gtixhdbzif.html

Go:   end.Sub(start).Hours()
来源：http://dali.xuetiantiany.cn/Article/details/gttxunrsei.html

Ruby: end - start                 # 返回秒数
来源：http://dali.0kj1m.cn/Article/details/gtrpvxhqmh.html

C#:   (end - start).TotalSeconds
来源：http://dali.yonumen.top/Article/details/gtjvgernpb.html

[J07] 比较两个日期
来源：http://dali.shangyingyoupin.top/Article/details/gtfhauuruj.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.zycfv.cn/Article/details/gtgazsctry.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.aizwys.cn/Article/details/gtckeqazpw.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yj20258.top/Article/details/gtkmrtpwzw.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.shzxlz.cn/Article/details/gtsvojpizf.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.birdmap.top/Article/details/gtlotvttkt.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.chenlongwang.top/Article/details/gtymorpnvi.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.0kj1m.cn/Article/details/gtcwmlqamq.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.aibaodan.cn/Article/details/gtiliqfzlo.html

[J08] 提取年月日与星期
来源：http://dali.yj20258.top/Article/details/gtexxcuhji.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.pengpengdd.cyou/Article/details/gtzpcxvryg.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.jinghuilouyu.cn/Article/details/gtbhumezad.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.daxiang520.top/Article/details/gtzvrsvhth.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.smart0.xyz/Article/details/gtkgmedheb.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.guannengcc.top/Article/details/gtmeaayclk.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.nwbrower.top/Article/details/gtgihckynb.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.vqdsnc.cn/Article/details/gtavukulxh.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.ydzc1.top/Article/details/gtitpgcrwd.html

[J09] 时区处理
来源：http://dali.bjfxy.top/Article/details/gtndufhnxv.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.gotoacloud.top/Article/details/gtudvzucia.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.chenjidiqi.icu/Article/details/gtpglzdkhp.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.quarkkingdee.top/Article/details/gtcjwvbkwr.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhoulong.xyz/Article/details/gtwhcninwu.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.snrcjt.cn/Article/details/gtfqcwaisr.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.chenzaomai.com/Article/details/gtzokrneam.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.fzhhl.top/Article/details/gtgypyefil.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yongpay.top/Article/details/gtgtdcuhau.html

[J10] 取今天 / 本月第一天
来源：http://dali.yvedp.cn/Article/details/gtgcueftud.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.tanke756.top/Article/details/gtqonojcqu.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.sufxvd.cn/Article/details/gtphhqvfzz.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.ydzc1.top/Article/details/gtlarnaahr.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.sweek.top/Article/details/gttswvlijh.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.zhoulong.xyz/Article/details/gtoercihrz.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.chenzaomai.com/Article/details/gtofwyyedd.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.sysykeji.top/Article/details/gtwnxkdxzf.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.9152youxi.cn/Article/details/gthbsnxcvt.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtdcuowcbh.html

K. JSON 与序列化
来源：http://dali.yangfankeji.com/Article/details/gtofdfjjoz.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtdvlcxfdw.html

[K01] 对象转 JSON 字符串
来源：http://dali.andypj.xyz/Article/details/gtsmfqwapn.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.hongshengwenyu.top/Article/details/gtgtsueupz.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.cashguo.top/Article/details/gtkoqpwpdb.html

JS:   JSON.stringify(obj)
来源：http://dali.nwbrower.top/Article/details/gtsqfruvrr.html

TS:   JSON.stringify(obj)
来源：http://dali.zdqjudy.top/Article/details/gtjwakqjha.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtotuhxqai.html

Go:   json.Marshal(obj)
来源：http://dali.nanxinkj.top/Article/details/gtjacazyam.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.316326.xyz/Article/details/gtwsmyjiym.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.snrcjt.cn/Article/details/gtavemlaim.html

[K02] JSON 字符串转对象
来源：http://dali.svipenyu.cn/Article/details/gtpmfnmpkr.html

Py:   json.loads(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuaoxgcba.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.shangyingyoupin.top/Article/details/gtwcthrhlu.html

JS:   JSON.parse(s)
来源：http://dali.havefunace.top/Article/details/gtzhtoanrz.html

TS:   JSON.parse(s)
来源：http://dali.nanxinkj.top/Article/details/gtdotbynis.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.bjfxy.top/Article/details/gtsqjpezgg.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiebmdjcu.html

Ruby: JSON.parse(s)
来源：http://dali.yj20258888.top/Article/details/gtycvplfal.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.gzhubu.top/Article/details/gtsmaltuqm.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlctuuadx.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.dianchejie.cn/Article/details/gtkkimdlhl.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.fengsongda.top/Article/details/gtdnpllyfj.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.xylfe.cn/Article/details/gtkpuuhvca.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yangfankeji.com/Article/details/gteqqmtixi.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtwtprhosg.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.cdnleiting.top/Article/details/gtreilckmy.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtpuptsoiq.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.feifeiyinyue.top/Article/details/gthllqhifk.html

[K04] 读取 JSON 文件
来源：http://dali.chenjidiqi.icu/Article/details/gtahaumgyx.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.birdmap.top/Article/details/gtoowqdpis.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.mhx1999.top/Article/details/gtztgpnhlq.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.pycfn.com/Article/details/gtfblgvzqq.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yj202588.top/Article/details/gtqisxpjqy.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gtswnccsnm.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.sxryk.cn/Article/details/gtvbxawkxl.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yuanzhike.top/Article/details/gthnkpkkdg.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.jinqigufen.top/Article/details/gtnjmnavvo.html

[K05] 深拷贝对象
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcmdquumv.html

Py:   copy.deepcopy(obj)
来源：http://dali.daria6918.cn/Article/details/gtqrjdjvzc.html

PHP:  unserialize(serialize($obj));
来源：http://dali.birdmap.top/Article/details/gttaozqplm.html

JS:   structuredClone(obj)
来源：http://dali.ybcxt.top/Article/details/gtmzrazkzd.html

TS:   structuredClone(obj)
来源：http://dali.zhixingplan.top/Article/details/gtykqfgadt.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.daria6918.cn/Article/details/gtjrfbgcif.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.fzhhl.top/Article/details/gtadhwjqme.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtimruawlj.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.shanyushiyangtech.top/Article/details/gtyhokqkzq.html

[K06] 解析 URL 查询串
来源：http://dali.tianlin.xyz/Article/details/gtphqupwvf.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.haohaochexian.top/Article/details/gtcikwzjem.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.zhengqikj.top/Article/details/gttgqgbnia.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.haohaochexian.top/Article/details/gtqpzxyvnx.html


<!-- 参考信息 -->