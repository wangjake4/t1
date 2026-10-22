代发 wailian999

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hywenlv.cn/Article/details/gteponxfcr.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.9152youxi.cn/Article/details/gtgaalwsjz.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.xuetiantiany.cn/Article/details/gtylmxwngj.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhongyouzk.top/Article/details/gtwebgnswp.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.hywenlv.cn/Article/details/gtmzxqsuuu.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.gotoacloud.top/Article/details/gtlffwglgs.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.nanxinkj.top/Article/details/gtxrsprbme.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.fengsongda.top/Article/details/gtjwhqhyel.html

[H03] 主动抛出异常
来源：http://dali.tanke756.top/Article/details/gthcqbvdxw.html

Py:   raise ValueError("错误信息")
来源：http://dali.andypj.xyz/Article/details/gtsaucwwvy.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.dianchejie.cn/Article/details/gtdagkrusd.html

JS:   throw new Error("错误信息");
来源：http://dali.aizwys.cn/Article/details/gtjeamfccz.html

TS:   throw new Error("错误信息");
来源：http://dali.sweek.top/Article/details/gtlzoelhof.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hnxiangtu.top/Article/details/gtbyxzsurg.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.xuetiantiany.cn/Article/details/gtrxunobhd.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.gotoacloud.top/Article/details/gtffhdfvrq.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.gotoacloud.top/Article/details/gtutfejtse.html

[H04] 自定义异常类型
来源：http://dali.jinqigufen.top/Article/details/gtukvcytuu.html

Py:   class MyError(Exception): pass
来源：http://dali.zhixingplan.top/Article/details/gtfgsckkgi.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.cucudq.cn/Article/details/gtuhvwytia.html

JS:   class MyError extends Error {}
来源：http://dali.smart0.xyz/Article/details/gtwumsnodr.html

TS:   class MyError extends Error {}
来源：http://dali.xinyue.icu/Article/details/gtagppildh.html

Java: class MyException extends RuntimeException {}
来源：http://dali.redwolf501.top/Article/details/gtkrbnzcnq.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.shangyingyoupin.top/Article/details/gtcvchsssg.html

Ruby: class MyError < StandardError; end
来源：http://dali.hywenlv.cn/Article/details/gtmrosvxqj.html

C#:   class MyException : Exception {}
来源：http://dali.dashuyun.cn/Article/details/gtdhsbnlty.html

[H05] 捕获特定类型
来源：http://dali.sweek.top/Article/details/gtijbjmvyq.html

Py:   except ValueError as e:
来源：http://dali.redwolf501.top/Article/details/gtldczumoe.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yangfankeji.com/Article/details/gtqhumetdo.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgxkkuoto.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtcjgtotgo.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yonumen.top/Article/details/gtwmabizmx.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yueranfly.top/Article/details/gtoaicrzbq.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gtoiyznqrs.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.ehwqpu.com/Article/details/gtfiplohxw.html

[H06] 可选值 / 空值安全访问
来源：http://dali.meibo888.top/Article/details/gtrjvqwvey.html

Py:   value = d.get("k") or default
来源：http://dali.jinqigufen.top/Article/details/gtrnliauzm.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.feifeiyinyue.top/Article/details/gtqqdzwrgp.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yueranfly.top/Article/details/gtmscrwuey.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.chenjidiqi.icu/Article/details/gtusoqznhg.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.fengsongda.top/Article/details/gtqjuboarr.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jqgfzy.top/Article/details/gtcblutrad.html

Ruby: d&.dig(:a, :b)
来源：http://dali.fengsongda.top/Article/details/gtbszwsasb.html

C#:   obj?.A?.B ?? default
来源：http://dali.smart0.xyz/Article/details/gtzzjdpzei.html

[H07] 断言
来源：http://dali.aibaodan.cn/Article/details/gtagxoxwuz.html

Py:   assert x > 0, "必须为正"
来源：http://dali.quarkkingdee.top/Article/details/gtnpmnhtev.html

PHP:  assert($x > 0);
来源：http://dali.yj20258.top/Article/details/gtdstzohpa.html

JS:   console.assert(x > 0);
来源：http://dali.shzxlz.cn/Article/details/gtrasvxcvb.html

TS:   console.assert(x > 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvvswzwwz.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjsatosbq.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.fzhhl.top/Article/details/gthlhplscp.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwlcabgsw.html

C#:   Debug.Assert(x > 0);
来源：http://dali.ppjwa.cn/Article/details/gtwamudhlr.html

[H08] 获取错误信息与堆栈
来源：http://dali.aibaodan.cn/Article/details/gtjpxniqfh.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.meibo888.top/Article/details/gtmrahuslk.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hongshengwenyu.top/Article/details/gtrbzdxjev.html

JS:   e.message;  e.stack
来源：http://dali.jqgufenzy.top/Article/details/gtgbsbhsjk.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.daxiang520.top/Article/details/gtpceukitx.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yongpay.top/Article/details/gthdrftjdm.html

Go:   err.Error()
来源：http://dali.ehwqpu.com/Article/details/gtanmyrojw.html

Ruby: e.message;  e.backtrace
来源：http://dali.hammf.cn/Article/details/gthwrpvihy.html

C#:   e.Message;  e.StackTrace
来源：http://dali.tian-w.cn/Article/details/gtlbfjfldv.html

[H09] 带错误码的异常
来源：http://dali.cdnleiting.top/Article/details/gtxtdonemw.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.sufxvd.cn/Article/details/gtvhnvzxia.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.shanyushiyangtech.top/Article/details/gtwzvrybox.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhijiandao.cn/Article/details/gtktwipjxq.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jqgufenzy.top/Article/details/gtkeoxgroo.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.sufxvd.cn/Article/details/gtanlveezb.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.gaohongyu789.top/Article/details/gtcdxkdwlo.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.cqqwz.cn/Article/details/gtoutyrftx.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yonumen.top/Article/details/gtbeslnxgw.html

[H10] 资源自动释放
来源：http://dali.zhongyouzk.top/Article/details/gtlepqimjm.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.andypj.xyz/Article/details/gtpfyhsiqp.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.meibo888.top/Article/details/gtefblbsch.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.kuanghao11.cn/Article/details/gtizwncfee.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtudsgvwxz.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.sysykeji.top/Article/details/gtdgmdskhc.html

Go:   defer f.Close()
来源：http://dali.gaohongyu789.top/Article/details/gtstomatxe.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.ppjwa.cn/Article/details/gtkghlllhx.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.dianchejie.cn/Article/details/gtwtdqkizu.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtfljsohfb.html

I. 正则表达式
来源：http://dali.fzhhl.top/Article/details/gtdpxxahpo.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtcjvsmgyo.html

[I01] 判断是否匹配
来源：http://dali.jqgfzy.top/Article/details/gtnevlqrlk.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.316326.xyz/Article/details/gthqpgyohl.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.daxiang520.top/Article/details/gtlskzizuc.html

JS:   /\d+/.test(s)
来源：http://dali.svipenyu.cn/Article/details/gtoilvvscc.html

TS:   /\d+/.test(s)
来源：http://dali.hysaishi.cn/Article/details/gtwhnkxluz.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jiagoushi.top/Article/details/gtqgfgsdbx.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhixingplan.top/Article/details/gtbhommvre.html

Ruby: s.match?(/\d+/)
来源：http://dali.aibaodan.cn/Article/details/gtxfafzsho.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.xziqi.cn/Article/details/gtsqsxjhwe.html

[I02] 提取所有匹配
来源：http://dali.smart0.xyz/Article/details/gtgtqggcmq.html

Py:   re.findall(r"\d+", s)
来源：http://dali.hfpthk.cn/Article/details/gtewvpksng.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.smart0.xyz/Article/details/gtxtnmdvie.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.cucudq.cn/Article/details/gtpymbrgiq.html

TS:   s.match(/\d+/g)
来源：http://dali.pengpengdd.cyou/Article/details/gtcpctnosf.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yuxming.cn/Article/details/gtqudnvgec.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.0kj1m.cn/Article/details/gtonruriyz.html

Ruby: s.scan(/\d+/)
来源：http://dali.snrcjt.cn/Article/details/gtydpcoykz.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.sufxvd.cn/Article/details/gtudrgdbtg.html

[I03] 提取捕获分组
来源：http://dali.xylfe.cn/Article/details/gttftukvvd.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.c1oappe.top/Article/details/gtjbysmbcc.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.shuidangran.top/Article/details/gtrdmhwpii.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.daxiang520.top/Article/details/gtpoibstpk.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.sxryk.cn/Article/details/gtnxnxogkl.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.ppjwa.cn/Article/details/gtqembuvhu.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.shanyushiyangtech.top/Article/details/gtpcrejyou.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.pycfn.com/Article/details/gtbuxcjckd.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.tanke756.top/Article/details/gtacmyhygs.html

[I04] 正则替换
来源：http://dali.yueranfly.top/Article/details/gtxbyohxlx.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zdqjudy.top/Article/details/gtxmuktbmo.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.316326.xyz/Article/details/gtupuruyqs.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhoulong.xyz/Article/details/gthbyecqbf.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.cdnleiting.top/Article/details/gtzlylpdin.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.dianchejie.cn/Article/details/gtxlopafpr.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.aibaodan.cn/Article/details/gtjuknarkg.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.vqdsnc.cn/Article/details/gtysptavjt.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.tian-w.cn/Article/details/gtutbophqk.html

[I05] 按正则拆分
来源：http://dali.ydzc1.top/Article/details/gtpwmwqawu.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtocvpnsei.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.meibo888.top/Article/details/gtupnfbrbh.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.0kj1m.cn/Article/details/gtthixvanv.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.ehwqpu.com/Article/details/gtktbkhhmb.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yueranfly.top/Article/details/gtrltnfxra.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.guowangkeji.top/Article/details/gtwrqpjnba.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.meibo888.top/Article/details/gtsrdwxxsm.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.ppjwa.cn/Article/details/gtliqlwssz.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.birdmap.top/Article/details/gtylyqnkis.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.nanxinkj.top/Article/details/gtmskrzxyl.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.birdmap.top/Article/details/gttubfycnu.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jyoumei.cn/Article/details/gtajbfciax.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hammf.cn/Article/details/gtncipegaj.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.shzxlz.cn/Article/details/gtpkwhhhat.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.shzxlz.cn/Article/details/gtybciqpzs.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.zhoulong.xyz/Article/details/gtzokusaub.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.nanxuanxn.top/Article/details/gtziusqcxm.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhiwuduotai.top/Article/details/gtgaxoumfi.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.hnqzz.top/Article/details/gtlxtnzrij.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.aizwys.cn/Article/details/gtmmikjkkm.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpxonofcv.html

TS:   /error/gim
来源：http://dali.gzhubu.top/Article/details/gtqumdikxk.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.ehwqpu.com/Article/details/gtpnzoikdc.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yvedp.cn/Article/details/gtrkcrbuzy.html

Ruby: s.scan(/error/i)
来源：http://dali.nwbrower.top/Article/details/gtyxqdjpry.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.sysykeji.top/Article/details/gtwukrkxtq.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.hammf.cn/Article/details/gtvxzwahcf.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jianghu66.top/Article/details/gtqadmdfri.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.gogol.net.cn/Article/details/gtyaignviv.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shuidangran.top/Article/details/gtrstvvknt.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.nanxinkj.top/Article/details/gtfpmeupuc.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.chenzaomai.com/Article/details/gtmeulhcge.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yueranfly.top/Article/details/gtzcwivdqm.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.mhx1999.top/Article/details/gtcegiubre.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.wangshuangyany.cn/Article/details/gtpdgrzfyh.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtdlauhhdc.html

J. 日期与时间
来源：http://dali.shanyushiyangtech.top/Article/details/gtezejfntw.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtgncolryd.html

[J01] 获取当前时间
来源：http://dali.yangfankeji.com/Article/details/gttrjhcjel.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.ydzc1.top/Article/details/gtbygljidy.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.c1oappe.top/Article/details/gtomkvwaky.html

JS:   new Date();  Date.now()
来源：http://dali.dashuyun.cn/Article/details/gttjcsbtrk.html

TS:   new Date();  Date.now()
来源：http://dali.smart0.xyz/Article/details/gtudqztsyl.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.hongshengwenyu.top/Article/details/gtmsrmhwko.html

Go:   time.Now()
来源：http://dali.ivvv.top/Article/details/gteaumdwae.html

Ruby: Time.now
来源：http://dali.yonumen.top/Article/details/gtzxgpmyep.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.xylfe.cn/Article/details/gtafchxzvq.html

[J02] 格式化输出
来源：http://dali.cashguo.top/Article/details/gtjzhldsdk.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yuanzhike.top/Article/details/gtpxbmnazh.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.zhengqikj.top/Article/details/gtsuoeqjtk.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.cashguo.top/Article/details/gttmfzsqyx.html

TS:   d.toISOString()
来源：http://dali.ppjwa.cn/Article/details/gtfgycwfho.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.ivvv.top/Article/details/gtauuocmtm.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zhiwuduotai.top/Article/details/gtnntljrre.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yuxming.cn/Article/details/gtcficilbl.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yj202588.top/Article/details/gterlyocgx.html

[J03] 字符串解析为日期
来源：http://dali.sufxvd.cn/Article/details/gtjfcpjvyx.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jinghuilouyu.cn/Article/details/gtfgyceeyh.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.wangshuangyany.cn/Article/details/gtsljegdej.html

JS:   new Date("2024-01-02")
来源：http://dali.hywenlv.cn/Article/details/gtygoxinqn.html

TS:   new Date("2024-01-02")
来源：http://dali.jiagoushi.top/Article/details/gtodmimven.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jqgufenzy.top/Article/details/gtokczxfsb.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hywenlv.cn/Article/details/gtjnaflwwc.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.ivvv.top/Article/details/gtasexarft.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.andypj.xyz/Article/details/gtbhvwpvbi.html

[J04] 时间戳与日期互转
来源：http://dali.quarkkingdee.top/Article/details/gtebcncmgb.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.guannengcc.top/Article/details/gttcncwqkk.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.jyoumei.cn/Article/details/gtzdsavttp.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.guannengcc.top/Article/details/gthvyudres.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.gogol.net.cn/Article/details/gttkczfpfx.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jqgufenzy.top/Article/details/gtzwesxcbm.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yuxming.cn/Article/details/gtwspuptps.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.meibo888.top/Article/details/gtijbqumhs.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hongshengwenyu.top/Article/details/gtxdvzptkn.html

[J05] 时间加减（加 7 天）
来源：http://dali.xuanzx.com/Article/details/gtdpmtqpto.html

Py:   now + timedelta(days=7)
来源：http://dali.jqgfzy.top/Article/details/gtllkrlwym.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.shangyingyoupin.top/Article/details/gtztiitzpr.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.tanke756.top/Article/details/gtoyzpexzx.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cheryme.top/Article/details/gthawpvvei.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.ydzc1.top/Article/details/gtvlymztaq.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zhijiandao.cn/Article/details/gtcurmkwed.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yongpay.top/Article/details/gtolutsfvp.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkrxyzqbw.html

[J06] 计算两时间之差
来源：http://dali.yanxiufei.cn/Article/details/gtvdnxvxrb.html

Py:   (end - start).total_seconds()
来源：http://dali.wangshuangyany.cn/Article/details/gtcepramsn.html

PHP:  $end->diff($start)->days;
来源：http://dali.dianchejie.cn/Article/details/gtewvufdqc.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.ivvv.top/Article/details/gtihnubtcd.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.sysykeji.top/Article/details/gtdtmzvkml.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.wangdashe.top/Article/details/gtcagczzew.html

Go:   end.Sub(start).Hours()
来源：http://dali.cqqwz.cn/Article/details/gtsuacpkhc.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zhixingplan.top/Article/details/gtdetynaea.html

C#:   (end - start).TotalSeconds
来源：http://dali.ppjwa.cn/Article/details/gtrudwjcbv.html

[J07] 比较两个日期
来源：http://dali.andypj.xyz/Article/details/gtcqybrcva.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yongpay.top/Article/details/gtdglpgmqj.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.guannengcc.top/Article/details/gtmgfazpnm.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.hnqzz.top/Article/details/gtiaviaujf.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jinghuilouyu.cn/Article/details/gtpivqrfvs.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.cdnleiting.top/Article/details/gtqkeckdoz.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.hysaishi.cn/Article/details/gtetvlyoak.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.cheryme.top/Article/details/gtdatqmdkr.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.zhoulong.xyz/Article/details/gtmfakcmgx.html

[J08] 提取年月日与星期
来源：http://dali.xziqi.cn/Article/details/gtsaokezpw.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.cucudq.cn/Article/details/gtocvjtknd.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.iojbl.cn/Article/details/gttdaeeckz.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yuxming.cn/Article/details/gtugeltazh.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.svipenyu.cn/Article/details/gtjujniwoi.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.iojbl.cn/Article/details/gthfwlopew.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.tianlin.xyz/Article/details/gtnmzaovfi.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.yanxiufei.cn/Article/details/gtdzpuwsdf.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.pycfn.com/Article/details/gtdxkxxywm.html

[J09] 时区处理
来源：http://dali.chenzaomai.com/Article/details/gthbcueauh.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.0kj1m.cn/Article/details/gtwjhmvorc.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.ppjwa.cn/Article/details/gtktpcosug.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.haohaochexian.top/Article/details/gtwqwbvmna.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zycfv.cn/Article/details/gtzvkmtbaf.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.fzhhl.top/Article/details/gtsyurmxdd.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.cqqwz.cn/Article/details/gtieltnwol.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zycfv.cn/Article/details/gtukkyvjkr.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.shangyingyoupin.top/Article/details/gtndccofda.html

[J10] 取今天 / 本月第一天
来源：http://dali.yj20258.top/Article/details/gtrykreexj.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.ybcxt.top/Article/details/gtihhvxnsx.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.chenjidiqi.icu/Article/details/gtualfplph.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.pengpengdd.cyou/Article/details/gtyzwlzvgn.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.ivvv.top/Article/details/gtofavnzjk.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yanxiufei.cn/Article/details/gtaumumnza.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.cheryme.top/Article/details/gtkjqhgglh.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jlsjyb.cn/Article/details/gthzlhelag.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yj20258.top/Article/details/gtsayjpupg.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtgsawcead.html

K. JSON 与序列化
来源：http://dali.jiagoushi.top/Article/details/gtreofrqer.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtkecepdsp.html

[K01] 对象转 JSON 字符串
来源：http://dali.yvedp.cn/Article/details/gtvfdixbzk.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.cqqwz.cn/Article/details/gttulxoieo.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.cqqwz.cn/Article/details/gtrbmrylgj.html

JS:   JSON.stringify(obj)
来源：http://dali.ybcxt.top/Article/details/gthjejbrhh.html

TS:   JSON.stringify(obj)
来源：http://dali.andypj.xyz/Article/details/gtjpridwfg.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.smart0.xyz/Article/details/gtitzlfidu.html

Go:   json.Marshal(obj)
来源：http://dali.andypj.xyz/Article/details/gtllkotcul.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.bjfxy.top/Article/details/gtivtxlwrf.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhengqikj.top/Article/details/gttmjtnntf.html

[K02] JSON 字符串转对象
来源：http://dali.yj20258.top/Article/details/gtlxodwmas.html

Py:   json.loads(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtzujtoujf.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yonumen.top/Article/details/gtnatbzyqc.html

JS:   JSON.parse(s)
来源：http://dali.chenzaomai.com/Article/details/gtcyomzzvv.html

TS:   JSON.parse(s)
来源：http://dali.bjfxy.top/Article/details/gtowjvwfjv.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.wangdashe.top/Article/details/gtvgfpitmc.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.daria6918.cn/Article/details/gtwyhaucgj.html

Ruby: JSON.parse(s)
来源：http://dali.9152youxi.cn/Article/details/gtoswcwbqg.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtoyvsljeb.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.cqqwz.cn/Article/details/gtqqfjztaw.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.mhx1999.top/Article/details/gtdhmzwago.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.hywenlv.cn/Article/details/gtgchuetbi.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yongpay.top/Article/details/gtkdxscktr.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.yongpay.top/Article/details/gtqccloclf.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gthtsiltlp.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.birdmap.top/Article/details/gtlbrrmmmb.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.cdnleiting.top/Article/details/gtdbxyious.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.fzhhl.top/Article/details/gtnjxdevzv.html

[K04] 读取 JSON 文件
来源：http://dali.sxryk.cn/Article/details/gtziwkwgyx.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.shangyingyoupin.top/Article/details/gtyfxhgmmw.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yuxming.cn/Article/details/gtirssyevz.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.bjfxy.top/Article/details/gtwhfgghhj.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jiagoushi.top/Article/details/gtlgnqrscy.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.snrcjt.cn/Article/details/gtofaiosvg.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhongyouzk.top/Article/details/gttfwtnpwd.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.yongpay.top/Article/details/gteviitznd.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yonumen.top/Article/details/gthmapojup.html

[K05] 深拷贝对象
来源：http://dali.ivvv.top/Article/details/gtnoqlgmbz.html

Py:   copy.deepcopy(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtbftfdbmr.html

PHP:  unserialize(serialize($obj));
来源：http://dali.hfpthk.cn/Article/details/gtscixftai.html

JS:   structuredClone(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtizfmojqw.html

TS:   structuredClone(obj)
来源：http://dali.birdmap.top/Article/details/gtybprgcys.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.andypj.xyz/Article/details/gtfncwhnsq.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.zhiwuduotai.top/Article/details/gtypwdpwtk.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.aibaodan.cn/Article/details/gthkyvadpm.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.nanxinkj.top/Article/details/gtzlvscmvd.html

[K06] 解析 URL 查询串
来源：http://dali.sxryk.cn/Article/details/gtftrwjvoy.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.chenlongwang.top/Article/details/gtzmzobdfr.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.chenlongwang.top/Article/details/gtzgyqphmi.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.nanxuanxn.top/Article/details/gtfwblkxgw.html


<!-- 参考信息 -->