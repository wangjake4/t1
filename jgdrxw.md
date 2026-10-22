代发 wailian999

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhoulong.xyz/Article/details/gtiqmgkhyl.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.aizwys.cn/Article/details/gtxtejnira.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.sufxvd.cn/Article/details/gtijvavghl.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hywenlv.cn/Article/details/gtzipclrnr.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.redwolf501.top/Article/details/gtnmrhcfry.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.gzhubu.top/Article/details/gtcjwpjswj.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvydcbsvg.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jlsjyb.cn/Article/details/gtmmfrrjaf.html

[H03] 主动抛出异常
来源：http://dali.jqgufenzy.top/Article/details/gtvcgwcbba.html

Py:   raise ValueError("错误信息")
来源：http://dali.vqdsnc.cn/Article/details/gtlvmgzuxa.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.tanke756.top/Article/details/gtnhbckbhr.html

JS:   throw new Error("错误信息");
来源：http://dali.ppjwa.cn/Article/details/gtaumvpamt.html

TS:   throw new Error("错误信息");
来源：http://dali.redwolf501.top/Article/details/gtiuxbkygd.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.chenzaomai.com/Article/details/gttyyglsvd.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhongyouzk.top/Article/details/gtisiixvyk.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yongpay.top/Article/details/gttyqovxjs.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.daria6918.cn/Article/details/gtjvimepwy.html

[H04] 自定义异常类型
来源：http://dali.bjfxy.top/Article/details/gtvfsepacs.html

Py:   class MyError(Exception): pass
来源：http://dali.jqgufenzy.top/Article/details/gttueaojql.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yj20258.top/Article/details/gtzymokvfv.html

JS:   class MyError extends Error {}
来源：http://dali.tanke756.top/Article/details/gtvomicyve.html

TS:   class MyError extends Error {}
来源：http://dali.hongshengwenyu.top/Article/details/gtyavzmdab.html

Java: class MyException extends RuntimeException {}
来源：http://dali.tianlin.xyz/Article/details/gtkzyhycaa.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gtdvnbqojv.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gtfewbtned.html

C#:   class MyException : Exception {}
来源：http://dali.sweek.top/Article/details/gtitwfdgan.html

[H05] 捕获特定类型
来源：http://dali.haohaochexian.top/Article/details/gtvcwcnzgo.html

Py:   except ValueError as e:
来源：http://dali.cucudq.cn/Article/details/gtormvlumi.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.havefunace.top/Article/details/gtvfvweopk.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.guannengcc.top/Article/details/gtfanppabr.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jyoumei.cn/Article/details/gthmgdsnyf.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtrbypjamf.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.cucudq.cn/Article/details/gtkctqltwm.html

Ruby: rescue ArgumentError => e
来源：http://dali.shuidangran.top/Article/details/gtnlwakhhw.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.pycfn.com/Article/details/gtybtqpwvn.html

[H06] 可选值 / 空值安全访问
来源：http://dali.nwbrower.top/Article/details/gttsjkoejo.html

Py:   value = d.get("k") or default
来源：http://dali.sweek.top/Article/details/gtstfcdsyf.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.snrcjt.cn/Article/details/gthiblgymw.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.haohaochexian.top/Article/details/gtjdmjhflw.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbbwccxax.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.svipenyu.cn/Article/details/gtwpcpghcq.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.gotoacloud.top/Article/details/gtpensiduj.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hnxiangtu.top/Article/details/gtkikmkhbe.html

C#:   obj?.A?.B ?? default
来源：http://dali.wangdashe.top/Article/details/gtweqgrmkx.html

[H07] 断言
来源：http://dali.gogol.net.cn/Article/details/gtmcnlofsg.html

Py:   assert x > 0, "必须为正"
来源：http://dali.sufxvd.cn/Article/details/gtadirjugv.html

PHP:  assert($x > 0);
来源：http://dali.aizwys.cn/Article/details/gtkesdfhnv.html

JS:   console.assert(x > 0);
来源：http://dali.gotoacloud.top/Article/details/gtyeevtzxp.html

TS:   console.assert(x > 0);
来源：http://dali.zhongyouzk.top/Article/details/gtfthzvuim.html

Java: assert x > 0 : "必须为正";
来源：http://dali.gzhubu.top/Article/details/gtfmslfjtg.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.wangshuangyany.cn/Article/details/gtgwmlqric.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.cdnleiting.top/Article/details/gtfyzslpfl.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hongshengwenyu.top/Article/details/gtmvdoiljl.html

[H08] 获取错误信息与堆栈
来源：http://dali.jianghu66.top/Article/details/gtcpwxlbdn.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.andypj.xyz/Article/details/gtxccaxomo.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.aizwys.cn/Article/details/gtmncfzhlz.html

JS:   e.message;  e.stack
来源：http://dali.zhengqikj.top/Article/details/gtrmwgtcvf.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.xinyue.icu/Article/details/gtrmgpplsr.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.daxiang520.top/Article/details/gtlkbsculj.html

Go:   err.Error()
来源：http://dali.quarkkingdee.top/Article/details/gtjsvlxbpa.html

Ruby: e.message;  e.backtrace
来源：http://dali.havefunace.top/Article/details/gtdizuabaj.html

C#:   e.Message;  e.StackTrace
来源：http://dali.nanxinkj.top/Article/details/gtsfokzsml.html

[H09] 带错误码的异常
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsajgtfci.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqtktpomc.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yvedp.cn/Article/details/gtgnwmwgco.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.c1oappe.top/Article/details/gtwwryendo.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.xziqi.cn/Article/details/gtubtznwmx.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.nanxuanxn.top/Article/details/gtpnvpqkga.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.gaohongyu789.top/Article/details/gteqskkezg.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.aibaodan.cn/Article/details/gtpwvkhoug.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.meibo888.top/Article/details/gtswjfryaf.html

[H10] 资源自动释放
来源：http://dali.sweek.top/Article/details/gtytoqyqod.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.guannengcc.top/Article/details/gtqmktjwsg.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.guannengcc.top/Article/details/gttgtpkyrt.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.wangdashe.top/Article/details/gtpqxgaucf.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gaohongyu789.top/Article/details/gtwruzshlk.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.iojbl.cn/Article/details/gtxlestugs.html

Go:   defer f.Close()
来源：http://dali.snrcjt.cn/Article/details/gtbfmbpmxx.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.nanxinkj.top/Article/details/gttqzozfqc.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gtrjcgwqbc.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtbpafbkbk.html

I. 正则表达式
来源：http://dali.dashuyun.cn/Article/details/gttcteirag.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtoxvqeqpr.html

[I01] 判断是否匹配
来源：http://dali.yangfankeji.com/Article/details/gtnricygqu.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yonumen.top/Article/details/gtbogqmcam.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyoeprtfm.html

JS:   /\d+/.test(s)
来源：http://dali.gotoacloud.top/Article/details/gtzglyqsma.html

TS:   /\d+/.test(s)
来源：http://dali.316326.xyz/Article/details/gtqsdwqzvc.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jinghuilouyu.cn/Article/details/gtuqfztrcm.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.gotoacloud.top/Article/details/gtkehtryeq.html

Ruby: s.match?(/\d+/)
来源：http://dali.yangfankeji.com/Article/details/gtlobxpnhr.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.0kj1m.cn/Article/details/gtkinnebzg.html

[I02] 提取所有匹配
来源：http://dali.nanxinkj.top/Article/details/gtjvohakqx.html

Py:   re.findall(r"\d+", s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcfirkyna.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yvedp.cn/Article/details/gtiryuislb.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jianghu66.top/Article/details/gtvsrhbsyv.html

TS:   s.match(/\d+/g)
来源：http://dali.hammf.cn/Article/details/gtnxxbuiww.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.cashguo.top/Article/details/gtvehewvlc.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.birdmap.top/Article/details/gthywtvcoh.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gtiuyosabc.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yj20258888.top/Article/details/gtdjobetlq.html

[I03] 提取捕获分组
来源：http://dali.gzhubu.top/Article/details/gtmyjitchj.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jianghu66.top/Article/details/gtngurybju.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yangfankeji.com/Article/details/gtbzhlcxox.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhoulong.xyz/Article/details/gtjciozrgj.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.hnqzz.top/Article/details/gtfibocsrn.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jinghuilouyu.cn/Article/details/gttceygzaw.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yvedp.cn/Article/details/gtkipskxjy.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.gaohongyu789.top/Article/details/gtafhdthkb.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.gzhubu.top/Article/details/gtqhmjdere.html

[I04] 正则替换
来源：http://dali.meibo888.top/Article/details/gtbaabwmng.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.mhx1999.top/Article/details/gtvwkpprhq.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yonumen.top/Article/details/gtkaeuxlob.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.sufxvd.cn/Article/details/gtlcmvmvmw.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zhoulong.xyz/Article/details/gtpuyrdgol.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.shanyushiyangtech.top/Article/details/gtemkkrqsd.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jqgufenzy.top/Article/details/gtxnzjirue.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.yongpay.top/Article/details/gtatidjurl.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zycfv.cn/Article/details/gtffxtywye.html

[I05] 按正则拆分
来源：http://dali.ivvv.top/Article/details/gtdhwjtlqc.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yanxiufei.cn/Article/details/gtzusblrla.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.nwbrower.top/Article/details/gtuymingfz.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqaflmkmy.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.shanyushiyangtech.top/Article/details/gtqjaibwkx.html

Java: s.split("\\s*,\\s*")
来源：http://dali.nanxinkj.top/Article/details/gtewdcxhxa.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.vqdsnc.cn/Article/details/gttdjxluxg.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.havefunace.top/Article/details/gtodrzfpfg.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.smart0.xyz/Article/details/gtkomydduf.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yj20258888.top/Article/details/gtwokyoyac.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.ivvv.top/Article/details/gtrveatysk.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhijiandao.cn/Article/details/gtnmkmfsay.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.haohaochexian.top/Article/details/gtkmquuvtz.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yangfankeji.com/Article/details/gtgesjvdnl.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yj202588.top/Article/details/gtbvnimbdb.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.hnqzz.top/Article/details/gtnawtyvrt.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.xziqi.cn/Article/details/gtcrmbuell.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jiagoushi.top/Article/details/gttabqvmic.html

[I07] 忽略大小写与多行模式
来源：http://dali.xinyue.icu/Article/details/gthsjbfpfb.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhiwuduotai.top/Article/details/gtkxgpptes.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.shanyushiyangtech.top/Article/details/gtgrnositu.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.hysaishi.cn/Article/details/gtwwduygul.html

TS:   /error/gim
来源：http://dali.tianlin.xyz/Article/details/gtvepnnhma.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.shuidangran.top/Article/details/gtuzwtzirv.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.316326.xyz/Article/details/gtlrlbmaac.html

Ruby: s.scan(/error/i)
来源：http://dali.tanke756.top/Article/details/gtnhyupufe.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yanxiufei.cn/Article/details/gtvsldanwv.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.ywan-chungtsiang.top/Article/details/gtitnentnx.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhiwuduotai.top/Article/details/gtmgnnurhh.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.gotoacloud.top/Article/details/gtefbhefbw.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ydzc1.top/Article/details/gtqksicaew.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jinghuilouyu.cn/Article/details/gtiqcetrwi.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.xuanzx.com/Article/details/gtdqtddcje.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.0kj1m.cn/Article/details/gtuxqvikex.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yanxiufei.cn/Article/details/gtqfxlcnva.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.316326.xyz/Article/details/gtdmflszff.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtfunvffrf.html

J. 日期与时间
来源：http://dali.pycfn.com/Article/details/gtqbiuhxfg.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtivnejfux.html

[J01] 获取当前时间
来源：http://dali.zhengqikj.top/Article/details/gtgwrfwgio.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.316326.xyz/Article/details/gtvjgukyyn.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.hfpthk.cn/Article/details/gtxdbwoixu.html

JS:   new Date();  Date.now()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvwugkqpk.html

TS:   new Date();  Date.now()
来源：http://dali.tanke756.top/Article/details/gtfmizprjf.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yuxming.cn/Article/details/gtpndauijb.html

Go:   time.Now()
来源：http://dali.gogol.net.cn/Article/details/gtbqcdcfpz.html

Ruby: Time.now
来源：http://dali.gzhubu.top/Article/details/gtrsebuwpj.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.xuetiantiany.cn/Article/details/gtvbiywmty.html

[J02] 格式化输出
来源：http://dali.xuanzx.com/Article/details/gtddholgdm.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.havefunace.top/Article/details/gtddrlkpke.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jyoumei.cn/Article/details/gtuugbqiih.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.tian-w.cn/Article/details/gtvqlxkcbf.html

TS:   d.toISOString()
来源：http://dali.guowangkeji.top/Article/details/gtrzqiieva.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.wangdashe.top/Article/details/gtlfdsbaqf.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.ppjwa.cn/Article/details/gtkgqmqagl.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ivvv.top/Article/details/gtgcqfjvsj.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.sxryk.cn/Article/details/gtqqpqkwzr.html

[J03] 字符串解析为日期
来源：http://dali.chenzaomai.com/Article/details/gttyefymql.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.bjfxy.top/Article/details/gtbbhsjrch.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.haohaochexian.top/Article/details/gtoruavuqf.html

JS:   new Date("2024-01-02")
来源：http://dali.yongpay.top/Article/details/gtdcvgxpwf.html

TS:   new Date("2024-01-02")
来源：http://dali.jqgufenzy.top/Article/details/gthbysowwr.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hysaishi.cn/Article/details/gtantkiirt.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.ehwqpu.com/Article/details/gtbogfenoq.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.ybcxt.top/Article/details/gtzrxtusuf.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.gzhubu.top/Article/details/gtezwpoxmm.html

[J04] 时间戳与日期互转
来源：http://dali.chenzaomai.com/Article/details/gtssdhqpmh.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhixingplan.top/Article/details/gtzkarkvvx.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.fengsongda.top/Article/details/gtjvaddluk.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.havefunace.top/Article/details/gtdtfhripz.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtybbfrvnj.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.kuanghao11.cn/Article/details/gtxsnpdofz.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yvedp.cn/Article/details/gtykgwafwe.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.cheryme.top/Article/details/gtvtlsfigi.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.aizwys.cn/Article/details/gtghkcfrbp.html

[J05] 时间加减（加 7 天）
来源：http://dali.wangshuangyany.cn/Article/details/gttltpddgi.html

Py:   now + timedelta(days=7)
来源：http://dali.yvedp.cn/Article/details/gthpqzlznl.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.tian-w.cn/Article/details/gtmhawmnyu.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhiwuduotai.top/Article/details/gtfckcrlqw.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.pycfn.com/Article/details/gtztxhojdm.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.mhx1999.top/Article/details/gtclsaiftb.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.tanke756.top/Article/details/gtynmnvuyv.html

Ruby: Time.now + 7 * 86400
来源：http://dali.haohaochexian.top/Article/details/gtlrtpdcqk.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yueranfly.top/Article/details/gtvdnxeogy.html

[J06] 计算两时间之差
来源：http://dali.yangfankeji.com/Article/details/gtkkslokod.html

Py:   (end - start).total_seconds()
来源：http://dali.hongshengwenyu.top/Article/details/gtgaizdnbz.html

PHP:  $end->diff($start)->days;
来源：http://dali.hnxiangtu.top/Article/details/gtgffelsnc.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.birdmap.top/Article/details/gtotxckhxk.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhixingplan.top/Article/details/gtypmfahmk.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.snrcjt.cn/Article/details/gthetsoqag.html

Go:   end.Sub(start).Hours()
来源：http://dali.ehwqpu.com/Article/details/gtudwozhne.html

Ruby: end - start                 # 返回秒数
来源：http://dali.zhijiandao.cn/Article/details/gtixbiogtf.html

C#:   (end - start).TotalSeconds
来源：http://dali.chenlongwang.top/Article/details/gtahifimae.html

[J07] 比较两个日期
来源：http://dali.hfpthk.cn/Article/details/gtxhwqjocg.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.wangdashe.top/Article/details/gtdyzadfqa.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.sxryk.cn/Article/details/gtmdoaurwz.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.aibaodan.cn/Article/details/gtwpydoihb.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jinqigfzy.top/Article/details/gtgjmmtzqo.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.wangdashe.top/Article/details/gtkguzkqia.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yj20258888.top/Article/details/gtoibqxexo.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.guowangkeji.top/Article/details/gtkcttmpue.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.guannengcc.top/Article/details/gtjghznqqt.html

[J08] 提取年月日与星期
来源：http://dali.cdnleiting.top/Article/details/gtlrjvkepd.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zdqjudy.top/Article/details/gtjoivmvni.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.9152youxi.cn/Article/details/gtabmdqsxh.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.chenjidiqi.icu/Article/details/gtenbffqxm.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jinqigufen.top/Article/details/gtiptzrdbp.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.hongshengwenyu.top/Article/details/gtvtipemqm.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.redwolf501.top/Article/details/gtcwtvhfsh.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.fengsongda.top/Article/details/gtkpozoqba.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jianghu66.top/Article/details/gtodwmgzbf.html

[J09] 时区处理
来源：http://dali.hnqzz.top/Article/details/gtldiowgva.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.xuanzx.com/Article/details/gtbgpzzcba.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.haohaochexian.top/Article/details/gtwdmxppbx.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.chenlongwang.top/Article/details/gtazuongne.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.cashguo.top/Article/details/gtlhvfbsch.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.nanxinkj.top/Article/details/gtlnmhalhj.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.cheryme.top/Article/details/gtdtpxhpyy.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.ivvv.top/Article/details/gttcctgvjm.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.nanxuanxn.top/Article/details/gtyhshszbf.html

[J10] 取今天 / 本月第一天
来源：http://dali.hywenlv.cn/Article/details/gtphmzxvvm.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.gzhubu.top/Article/details/gtfrqslekz.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.hywenlv.cn/Article/details/gttkxwifgw.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.xylfe.cn/Article/details/gtdabtuvtd.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.tian-w.cn/Article/details/gtuqacrgst.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.chenjidiqi.icu/Article/details/gthqsqocek.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.kuanghao11.cn/Article/details/gtkcizugze.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.ybcxt.top/Article/details/gtitczskfi.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.gzhubu.top/Article/details/gtqbxqysiy.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtsbrundsz.html

K. JSON 与序列化
来源：http://dali.nanxuanxn.top/Article/details/gtoneypcnf.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvnpgyfuf.html

[K01] 对象转 JSON 字符串
来源：http://dali.vqdsnc.cn/Article/details/gtxfojfzfx.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.nwbrower.top/Article/details/gtplsqzvma.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.zhongyouzk.top/Article/details/gtimrgewgx.html

JS:   JSON.stringify(obj)
来源：http://dali.xziqi.cn/Article/details/gtqtfjdpks.html

TS:   JSON.stringify(obj)
来源：http://dali.ivvv.top/Article/details/gteyrawnqg.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.cqqwz.cn/Article/details/gtxfnzeldf.html

Go:   json.Marshal(obj)
来源：http://dali.snrcjt.cn/Article/details/gtpztljvwl.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.9152youxi.cn/Article/details/gtmdxvnzyn.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtynmgjbpu.html

[K02] JSON 字符串转对象
来源：http://dali.sxryk.cn/Article/details/gtfekgztlg.html

Py:   json.loads(s)
来源：http://dali.yangfankeji.com/Article/details/gtogiyqvje.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.guannengcc.top/Article/details/gtkxwfwzko.html

JS:   JSON.parse(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtyhxyhhqu.html

TS:   JSON.parse(s)
来源：http://dali.mhx1999.top/Article/details/gtpgwovgje.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.shuidangran.top/Article/details/gtfeunbfvr.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.xylfe.cn/Article/details/gthlryswqw.html

Ruby: JSON.parse(s)
来源：http://dali.zhengqikj.top/Article/details/gtvqxxfole.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.wangshuangyany.cn/Article/details/gttojrjxum.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.hnqzz.top/Article/details/gtwxetaqnc.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.daxiang520.top/Article/details/gtcxlhvyvl.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.ivvv.top/Article/details/gtihzoymom.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.tian-w.cn/Article/details/gtfcepjufo.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtojxzglka.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.ivvv.top/Article/details/gtiyorfutc.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.fzhhl.top/Article/details/gtaemuppfv.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtfxjahkxj.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.mhx1999.top/Article/details/gtlrervbts.html

[K04] 读取 JSON 文件
来源：http://dali.chenjidiqi.icu/Article/details/gtcsrznalq.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.tian-w.cn/Article/details/gthzttbadg.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.yvedp.cn/Article/details/gtrcuhykoo.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.snrcjt.cn/Article/details/gttwdrlhyj.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.kuanghao11.cn/Article/details/gtcgqjpwdu.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.shanyushiyangtech.top/Article/details/gtqmhzeorz.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhiwuduotai.top/Article/details/gtuairtjhe.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.tian-w.cn/Article/details/gtvslkkgfb.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.yvedp.cn/Article/details/gtzxqyviyb.html

[K05] 深拷贝对象
来源：http://dali.fengsongda.top/Article/details/gthipmwcts.html

Py:   copy.deepcopy(obj)
来源：http://dali.jinqigufen.top/Article/details/gtpjmmdanv.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jianghu66.top/Article/details/gtydmmopuj.html

JS:   structuredClone(obj)
来源：http://dali.aibaodan.cn/Article/details/gtppeljrjc.html

TS:   structuredClone(obj)
来源：http://dali.aizwys.cn/Article/details/gtceatpwca.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.zdqjudy.top/Article/details/gtgminytae.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.mhx1999.top/Article/details/gtnogalggd.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.jqgfzy.top/Article/details/gtlpmolumq.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.hywenlv.cn/Article/details/gtcmgvbltf.html

[K06] 解析 URL 查询串
来源：http://dali.jqgfzy.top/Article/details/gtehgmmepz.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yonumen.top/Article/details/gtzawsydek.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.sufxvd.cn/Article/details/gtgpwzsxih.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.wangdashe.top/Article/details/gtuwnxuljw.html


<!-- 参考信息 -->