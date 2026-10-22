代发 wailian999

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.shzxlz.cn/Article/details/gtpeohsqzq.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jinqigufen.top/Article/details/gtbrxeauss.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ybcxt.top/Article/details/gtrigqfbmj.html

[H02] finally / ensure 收尾
来源：http://dali.yanxiufei.cn/Article/details/gtjlhzlmey.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.cheryme.top/Article/details/gtqrcffesu.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.wangdashe.top/Article/details/gtjpwyiljq.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbdtqwoxv.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.iojbl.cn/Article/details/gtdbcmsmao.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.cucudq.cn/Article/details/gtybipkonw.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.nwbrower.top/Article/details/gtydaegvbw.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.sysykeji.top/Article/details/gtruzkqoes.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhoulong.xyz/Article/details/gtvsicjwai.html

[H03] 主动抛出异常
来源：http://dali.smart0.xyz/Article/details/gtqepxwafs.html

Py:   raise ValueError("错误信息")
来源：http://dali.birdmap.top/Article/details/gtguifgqqt.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.mhx1999.top/Article/details/gthblefguv.html

JS:   throw new Error("错误信息");
来源：http://dali.jianghu66.top/Article/details/gtecrrxdzy.html

TS:   throw new Error("错误信息");
来源：http://dali.jinqigufen.top/Article/details/gtvvrjdysb.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yj20258.top/Article/details/gtlbihjcvo.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.gzhubu.top/Article/details/gtbzzkqjum.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.xinyue.icu/Article/details/gteneonlzy.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.redwolf501.top/Article/details/gtsaelfsmi.html

[H04] 自定义异常类型
来源：http://dali.nwbrower.top/Article/details/gtaligstbf.html

Py:   class MyError(Exception): pass
来源：http://dali.quarkkingdee.top/Article/details/gtdldjjgur.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.sweek.top/Article/details/gtbpteowqp.html

JS:   class MyError extends Error {}
来源：http://dali.chenjidiqi.icu/Article/details/gtcwpycfxm.html

TS:   class MyError extends Error {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtldpmokvs.html

Java: class MyException extends RuntimeException {}
来源：http://dali.ppjwa.cn/Article/details/gtnspvdxus.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.gogol.net.cn/Article/details/gtymwphhbr.html

Ruby: class MyError < StandardError; end
来源：http://dali.chenlongwang.top/Article/details/gtspchhxqf.html

C#:   class MyException : Exception {}
来源：http://dali.pycfn.com/Article/details/gtcaejnidn.html

[H05] 捕获特定类型
来源：http://dali.shzxlz.cn/Article/details/gtldczzidg.html

Py:   except ValueError as e:
来源：http://dali.yangfankeji.com/Article/details/gtngaqcnfv.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.xylfe.cn/Article/details/gtlnsragpm.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.cucudq.cn/Article/details/gtvntucfkz.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.sufxvd.cn/Article/details/gtfkexfpwq.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.svipenyu.cn/Article/details/gttbjyflhl.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.nanxinkj.top/Article/details/gtifhorqfv.html

Ruby: rescue ArgumentError => e
来源：http://dali.andypj.xyz/Article/details/gtwhaeauje.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.fengsongda.top/Article/details/gtgnqsqxjs.html

[H06] 可选值 / 空值安全访问
来源：http://dali.9152youxi.cn/Article/details/gtezwamoyv.html

Py:   value = d.get("k") or default
来源：http://dali.xuetiantiany.cn/Article/details/gtfodbiiyp.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.xuetiantiany.cn/Article/details/gtgfdelhmf.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhoulong.xyz/Article/details/gtgycnnmrq.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.guannengcc.top/Article/details/gtyevotsqz.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yanxiufei.cn/Article/details/gtgyquzbhg.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.snrcjt.cn/Article/details/gtyyhssaxq.html

Ruby: d&.dig(:a, :b)
来源：http://dali.ivvv.top/Article/details/gtqqsfcuty.html

C#:   obj?.A?.B ?? default
来源：http://dali.aibaodan.cn/Article/details/gtmdmzjiov.html

[H07] 断言
来源：http://dali.zdqjudy.top/Article/details/gtilvssgwy.html

Py:   assert x > 0, "必须为正"
来源：http://dali.tian-w.cn/Article/details/gtzwcdlflm.html

PHP:  assert($x > 0);
来源：http://dali.cheryme.top/Article/details/gtuhfiwkyx.html

JS:   console.assert(x > 0);
来源：http://dali.pengpengdd.cyou/Article/details/gtbnmszikw.html

TS:   console.assert(x > 0);
来源：http://dali.vqdsnc.cn/Article/details/gtuxipeflm.html

Java: assert x > 0 : "必须为正";
来源：http://dali.xuanzx.com/Article/details/gttrgzlekk.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.shangyingyoupin.top/Article/details/gtypiaigne.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jinqigfzy.top/Article/details/gthuqabzbu.html

C#:   Debug.Assert(x > 0);
来源：http://dali.chenjidiqi.icu/Article/details/gtkpyojcjt.html

[H08] 获取错误信息与堆栈
来源：http://dali.hammf.cn/Article/details/gtimerxizg.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.vqdsnc.cn/Article/details/gtvkpwjawu.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.aizwys.cn/Article/details/gtsqpmamjb.html

JS:   e.message;  e.stack
来源：http://dali.chenlongwang.top/Article/details/gtlgxuubqx.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.tanke756.top/Article/details/gtmhveimwn.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jiagoushi.top/Article/details/gtvpueyxrc.html

Go:   err.Error()
来源：http://dali.yangfankeji.com/Article/details/gtcojynujv.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gtnvvjgbsh.html

C#:   e.Message;  e.StackTrace
来源：http://dali.xylfe.cn/Article/details/gtyicvrnam.html

[H09] 带错误码的异常
来源：http://dali.meibo888.top/Article/details/gtiynuwlik.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvknvqyft.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yj20258888.top/Article/details/gtrhmdlzte.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.ehwqpu.com/Article/details/gthsbgliqa.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.sysykeji.top/Article/details/gtuscryvjk.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.316326.xyz/Article/details/gtubyyfhhd.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yuxming.cn/Article/details/gtdnzowrdy.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jinqigufen.top/Article/details/gtloneycll.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.gaohongyu789.top/Article/details/gtautdhhlb.html

[H10] 资源自动释放
来源：http://dali.redwolf501.top/Article/details/gtpdcapaso.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.quarkkingdee.top/Article/details/gttajrvoga.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.gotoacloud.top/Article/details/gtudvcckxm.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gotoacloud.top/Article/details/gthoxnwbut.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ybcxt.top/Article/details/gtuyetgiqc.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.cashguo.top/Article/details/gtwqounafr.html

Go:   defer f.Close()
来源：http://dali.jianghu66.top/Article/details/gtfwcyrhef.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtihqtvuns.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jqgfzy.top/Article/details/gtenjttrtz.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzwograbi.html

I. 正则表达式
来源：http://dali.birdmap.top/Article/details/gtdpfugeiw.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gttkuivibs.html

[I01] 判断是否匹配
来源：http://dali.gotoacloud.top/Article/details/gtmshjhbef.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.chenjidiqi.icu/Article/details/gtzyvgwgme.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.svipenyu.cn/Article/details/gtuzfdzhzd.html

JS:   /\d+/.test(s)
来源：http://dali.yvedp.cn/Article/details/gtjaijnxut.html

TS:   /\d+/.test(s)
来源：http://dali.fzhhl.top/Article/details/gtobiwtzre.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yangfankeji.com/Article/details/gttgzpiooy.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhixingplan.top/Article/details/gtoxfnonbm.html

Ruby: s.match?(/\d+/)
来源：http://dali.jinqigufen.top/Article/details/gtoxnwrauh.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.shanyushiyangtech.top/Article/details/gtazsdtpsh.html

[I02] 提取所有匹配
来源：http://dali.yj202588.top/Article/details/gtpszzzani.html

Py:   re.findall(r"\d+", s)
来源：http://dali.smart0.xyz/Article/details/gthyjmdnrd.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.daria6918.cn/Article/details/gtuhjtkyns.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yj20258888.top/Article/details/gtwyjzgelc.html

TS:   s.match(/\d+/g)
来源：http://dali.jinqigfzy.top/Article/details/gtsnzdljnr.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zycfv.cn/Article/details/gtcdmbueiq.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgmfhytbb.html

Ruby: s.scan(/\d+/)
来源：http://dali.zdqjudy.top/Article/details/gtujblvdtr.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.snrcjt.cn/Article/details/gtsxvieeni.html

[I03] 提取捕获分组
来源：http://dali.hysaishi.cn/Article/details/gtzfrjmife.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jinqigufen.top/Article/details/gtbzlupagf.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhoulong.xyz/Article/details/gtiraygvhg.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.shanyushiyangtech.top/Article/details/gtceihjxey.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.guowangkeji.top/Article/details/gtnjwoiben.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.ydzc1.top/Article/details/gtkrgaktes.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.pycfn.com/Article/details/gtcluhkbqm.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yanxiufei.cn/Article/details/gtwbbhcjya.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.hywenlv.cn/Article/details/gtnkfiithx.html

[I04] 正则替换
来源：http://dali.ivvv.top/Article/details/gtgrnyhhsa.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtjuhfisgm.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.fzhhl.top/Article/details/gtbzczeflm.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jinqigufen.top/Article/details/gtmxqkkisj.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.quarkkingdee.top/Article/details/gtkmddqaxl.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jlsjyb.cn/Article/details/gtxkwfebmp.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.dashuyun.cn/Article/details/gtuyteclwj.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jinqigfzy.top/Article/details/gteesnmkqr.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yuanzhike.top/Article/details/gtnwpyiehm.html

[I05] 按正则拆分
来源：http://dali.jqgfzy.top/Article/details/gtkrrmqnrv.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbjidhfxd.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jqgufenzy.top/Article/details/gtbzkydcho.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.ehwqpu.com/Article/details/gtxwvuovat.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gthsihgqky.html

Java: s.split("\\s*,\\s*")
来源：http://dali.wangdashe.top/Article/details/gtnopvaskg.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.shangyingyoupin.top/Article/details/gtqojudrnu.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.cheryme.top/Article/details/gtduvqmfpg.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yj202588.top/Article/details/gtzdxeufkz.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.jlsjyb.cn/Article/details/gtcrillvho.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.shanyushiyangtech.top/Article/details/gtezltqssv.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.cashguo.top/Article/details/gtriahjdsm.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.mhx1999.top/Article/details/gtbtxrypnm.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.wangshuangyany.cn/Article/details/gtdynjfwqm.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yueranfly.top/Article/details/gtuezwyqjs.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.shanyushiyangkeji.top/Article/details/gtacikeahe.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jlsjyb.cn/Article/details/gtfqftzpkw.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jyoumei.cn/Article/details/gtzrrrfojz.html

[I07] 忽略大小写与多行模式
来源：http://dali.tian-w.cn/Article/details/gtzpiytpng.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.fzhhl.top/Article/details/gtpqykwnwq.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.gzhubu.top/Article/details/gthuhlycck.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhiwuduotai.top/Article/details/gtegpyksgn.html

TS:   /error/gim
来源：http://dali.feifeiyinyue.top/Article/details/gtqkmgkmka.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.shzxlz.cn/Article/details/gtpztpxzly.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.ybcxt.top/Article/details/gtvpejffki.html

Ruby: s.scan(/error/i)
来源：http://dali.daxiang520.top/Article/details/gtbkdfecsh.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.nanxuanxn.top/Article/details/gtcvpkofyf.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhijiandao.cn/Article/details/gtlatranhx.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.ybcxt.top/Article/details/gtvxjeckfq.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.andypj.xyz/Article/details/gthafjxtru.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yvedp.cn/Article/details/gtznmpfqwo.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.sufxvd.cn/Article/details/gtnzrncwwd.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.xuetiantiany.cn/Article/details/gtsictkcde.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.hongshengwenyu.top/Article/details/gtdddbwsfh.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.snrcjt.cn/Article/details/gtklirnxiu.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yj20258.top/Article/details/gtggoevhzd.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtufphzzpf.html

J. 日期与时间
来源：http://dali.wangshuangyany.cn/Article/details/gtqouddlwv.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtnsuttbxo.html

[J01] 获取当前时间
来源：http://dali.xuanzx.com/Article/details/gthfzwewzo.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.9152youxi.cn/Article/details/gtxeshiydw.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yanxiufei.cn/Article/details/gtqrufwnhm.html

JS:   new Date();  Date.now()
来源：http://dali.tianlin.xyz/Article/details/gthwbizzxh.html

TS:   new Date();  Date.now()
来源：http://dali.gotoacloud.top/Article/details/gtlhecckkn.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.sweek.top/Article/details/gthlecrokp.html

Go:   time.Now()
来源：http://dali.tianlin.xyz/Article/details/gtnagspaan.html

Ruby: Time.now
来源：http://dali.yj20258888.top/Article/details/gtxbdpdzgh.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.vqdsnc.cn/Article/details/gtkdobhppi.html

[J02] 格式化输出
来源：http://dali.xylfe.cn/Article/details/gtcjvinrjl.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.guannengcc.top/Article/details/gtebzyenah.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.feifeiyinyue.top/Article/details/gtjkhjjpen.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.xylfe.cn/Article/details/gtuphlzxrx.html

TS:   d.toISOString()
来源：http://dali.yonumen.top/Article/details/gtuuzkunor.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.gogol.net.cn/Article/details/gtigxpmipc.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.iojbl.cn/Article/details/gtfuvqblnp.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jqgufenzy.top/Article/details/gttvkgwbfu.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzkiwlijo.html

[J03] 字符串解析为日期
来源：http://dali.yangfankeji.com/Article/details/gtylcynedh.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.xuetiantiany.cn/Article/details/gtsfszezbm.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.birdmap.top/Article/details/gtwrjdzllo.html

JS:   new Date("2024-01-02")
来源：http://dali.sweek.top/Article/details/gtwmhsybit.html

TS:   new Date("2024-01-02")
来源：http://dali.jinqigfzy.top/Article/details/gtvlnnwssx.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yuxming.cn/Article/details/gtzkkxkhxg.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.chenzaomai.com/Article/details/gtdcirrggg.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.316326.xyz/Article/details/gtcbaiglak.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.zhoulong.xyz/Article/details/gteikpwepw.html

[J04] 时间戳与日期互转
来源：http://dali.dianchejie.cn/Article/details/gtpficefux.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.havefunace.top/Article/details/gtzqsswywa.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.ybcxt.top/Article/details/gttarrxwzd.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.zhijiandao.cn/Article/details/gtfcrdmtve.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.xylfe.cn/Article/details/gtvgvlpevd.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.wangshuangyany.cn/Article/details/gtmfmpmhif.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvtdxfaxd.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.ybcxt.top/Article/details/gttpdiplcm.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jinghuilouyu.cn/Article/details/gtprzbksfr.html

[J05] 时间加减（加 7 天）
来源：http://dali.pengpengdd.cyou/Article/details/gtivpobgtm.html

Py:   now + timedelta(days=7)
来源：http://dali.ehwqpu.com/Article/details/gtwpbmljhq.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhengqikj.top/Article/details/gtmnztavkt.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.9152youxi.cn/Article/details/gtxfrcfolc.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.havefunace.top/Article/details/gthntcwyha.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.cqqwz.cn/Article/details/gtxrucgwcy.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.sufxvd.cn/Article/details/gtwvalzkvt.html

Ruby: Time.now + 7 * 86400
来源：http://dali.birdmap.top/Article/details/gtbopsikwz.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.tianlin.xyz/Article/details/gtmcizklhy.html

[J06] 计算两时间之差
来源：http://dali.c1oappe.top/Article/details/gtwzncmisu.html

Py:   (end - start).total_seconds()
来源：http://dali.ivvv.top/Article/details/gtzxqmbvnh.html

PHP:  $end->diff($start)->days;
来源：http://dali.jinqigufen.top/Article/details/gtkizvpslp.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.gzhubu.top/Article/details/gtqqskfhsr.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yj202588.top/Article/details/gtuauscjsr.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.xziqi.cn/Article/details/gtnygvutns.html

Go:   end.Sub(start).Hours()
来源：http://dali.snrcjt.cn/Article/details/gtsytmfigz.html

Ruby: end - start                 # 返回秒数
来源：http://dali.ybcxt.top/Article/details/gtjfbzmmcg.html

C#:   (end - start).TotalSeconds
来源：http://dali.ehwqpu.com/Article/details/gtestmzauv.html

[J07] 比较两个日期
来源：http://dali.meibo888.top/Article/details/gtkngghjdi.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.feifeiyinyue.top/Article/details/gtzwnjovwb.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.pycfn.com/Article/details/gtybifygqh.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.tianlin.xyz/Article/details/gtbocjqjoh.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.shzxlz.cn/Article/details/gtjcskjpfp.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.shzxlz.cn/Article/details/gtoqugfkej.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.meibo888.top/Article/details/gtklqstawv.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.cashguo.top/Article/details/gtxauemoao.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.snrcjt.cn/Article/details/gtiqfboatr.html

[J08] 提取年月日与星期
来源：http://dali.wangshuangyany.cn/Article/details/gtvrqjjmtx.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yueranfly.top/Article/details/gtvnorutzd.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.sufxvd.cn/Article/details/gtmvqzbbpa.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jinghuilouyu.cn/Article/details/gtagnihwma.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.iojbl.cn/Article/details/gtxbvnxncp.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtonakmcut.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.cheryme.top/Article/details/gtxgaujbqk.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.pengpengdd.cyou/Article/details/gtdvczomsl.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.gzhubu.top/Article/details/gthfrzhjpk.html

[J09] 时区处理
来源：http://dali.jiagoushi.top/Article/details/gtguddlrlx.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.shzxlz.cn/Article/details/gtonvyftmh.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.shuidangran.top/Article/details/gtrwirnmuh.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.daria6918.cn/Article/details/gtpiqrvmor.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.chenjidiqi.icu/Article/details/gtcwsepsgs.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.dianchejie.cn/Article/details/gtozzbnefj.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpljtstag.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.shanyushiyangtech.top/Article/details/gthnzrfhrg.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.hnxiangtu.top/Article/details/gtudhzwbzi.html

[J10] 取今天 / 本月第一天
来源：http://dali.xuanzx.com/Article/details/gtxlfgstst.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.0kj1m.cn/Article/details/gtjvddbupl.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yanxiufei.cn/Article/details/gtyucfzapl.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.andypj.xyz/Article/details/gtfupsijjq.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yangfankeji.com/Article/details/gtmcnddfdx.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yuxming.cn/Article/details/gtdwxfseqw.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.quarkkingdee.top/Article/details/gtmgybatub.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.gotoacloud.top/Article/details/gtnvxoebmy.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.hywenlv.cn/Article/details/gtcbbzzakv.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtusehxkbq.html

K. JSON 与序列化
来源：http://dali.chenlongwang.top/Article/details/gtlzxzkhmm.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtqictllua.html

[K01] 对象转 JSON 字符串
来源：http://dali.havefunace.top/Article/details/gthvvzvexk.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.gaohongyu789.top/Article/details/gtzxlgasez.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.hnxiangtu.top/Article/details/gtjttjpcyb.html

JS:   JSON.stringify(obj)
来源：http://dali.jinqigufen.top/Article/details/gthqswqnlv.html

TS:   JSON.stringify(obj)
来源：http://dali.sufxvd.cn/Article/details/gtjeslqiit.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yanxiufei.cn/Article/details/gtjkmsiapn.html

Go:   json.Marshal(obj)
来源：http://dali.dashuyun.cn/Article/details/gtymcdmhwm.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.shanyushiyangkeji.top/Article/details/gttbtjvrmv.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.dianchejie.cn/Article/details/gtrocqbyen.html

[K02] JSON 字符串转对象
来源：http://dali.chenlongwang.top/Article/details/gtfokbteat.html

Py:   json.loads(s)
来源：http://dali.zhoulong.xyz/Article/details/gtwwcmorqj.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.aizwys.cn/Article/details/gteetwcudo.html

JS:   JSON.parse(s)
来源：http://dali.hfpthk.cn/Article/details/gthfefxzab.html

TS:   JSON.parse(s)
来源：http://dali.shuidangran.top/Article/details/gtnojqpucg.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.feifeiyinyue.top/Article/details/gtoanvahjp.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.fzhhl.top/Article/details/gtbgerggyo.html

Ruby: JSON.parse(s)
来源：http://dali.ybcxt.top/Article/details/gtnubfvlnm.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.cdnleiting.top/Article/details/gtovneecog.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.zhiwuduotai.top/Article/details/gtpwwuercn.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.zhongyouzk.top/Article/details/gtrhxckjtz.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.havefunace.top/Article/details/gttbftcawg.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.birdmap.top/Article/details/gtiaqhwdbb.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.chenlongwang.top/Article/details/gtehiwpdfa.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.gzhubu.top/Article/details/gtcoofzydf.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.zhiwuduotai.top/Article/details/gtaiuhffdz.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.xziqi.cn/Article/details/gtjrqwitjk.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.jyoumei.cn/Article/details/gttqagwuhr.html

[K04] 读取 JSON 文件
来源：http://dali.zhixingplan.top/Article/details/gtdaaztlxs.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.jiagoushi.top/Article/details/gtdnugwujz.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.hnqzz.top/Article/details/gtvujewvoh.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yj202588.top/Article/details/gtxtpbljnc.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.daria6918.cn/Article/details/gtouubvvkl.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.pengpengdd.cyou/Article/details/gtsawwtkfo.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.xuanzx.com/Article/details/gtebxftwyw.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.xuetiantiany.cn/Article/details/gtsjtbtbwl.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.tianlin.xyz/Article/details/gtuzembwai.html

[K05] 深拷贝对象
来源：http://dali.ywan-chungtsiang.top/Article/details/gtusxvlgzd.html

Py:   copy.deepcopy(obj)
来源：http://dali.andypj.xyz/Article/details/gticxchccz.html

PHP:  unserialize(serialize($obj));
来源：http://dali.dianchejie.cn/Article/details/gtgekwsefw.html

JS:   structuredClone(obj)
来源：http://dali.haohaochexian.top/Article/details/gttkjgnnop.html

TS:   structuredClone(obj)
来源：http://dali.chenzaomai.com/Article/details/gtexpecsbb.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.jianghu66.top/Article/details/gtnzuqurmn.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtabasqjrz.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.aizwys.cn/Article/details/gtixcuffhv.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.yonumen.top/Article/details/gtqgksfyfz.html


<!-- 参考信息 -->