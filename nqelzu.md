代发 wailian999

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtannhiiny.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yanxiufei.cn/Article/details/gtahywxfws.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.ybcxt.top/Article/details/gtirkxixxw.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjgsgvhlb.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.chenjidiqi.icu/Article/details/gtgukmiubt.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.316326.xyz/Article/details/gttstlmjiu.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.fengsongda.top/Article/details/gtnonmhcuf.html

[H02] finally / ensure 收尾
来源：http://dali.chenlongwang.top/Article/details/gtywclkqaf.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jinghuilouyu.cn/Article/details/gtqmzoczct.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zdqjudy.top/Article/details/gtayzszjsr.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzuuohexp.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.xuanzx.com/Article/details/gtcwphlhsk.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.hywenlv.cn/Article/details/gtttvxubgz.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jinqigfzy.top/Article/details/gtgchbdjys.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.tian-w.cn/Article/details/gtsmqwzqjs.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtggjtobix.html

[H03] 主动抛出异常
来源：http://dali.ydzc1.top/Article/details/gtiskogbiy.html

Py:   raise ValueError("错误信息")
来源：http://dali.gotoacloud.top/Article/details/gtesfujlbr.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhiwuduotai.top/Article/details/gtppmsgrwk.html

JS:   throw new Error("错误信息");
来源：http://dali.dianchejie.cn/Article/details/gtytxfequu.html

TS:   throw new Error("错误信息");
来源：http://dali.yueranfly.top/Article/details/gtsdofwwxw.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.shangyingyoupin.top/Article/details/gtqqmvkqtd.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.xuanzx.com/Article/details/gthomdklnk.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.tianlin.xyz/Article/details/gtruzadlus.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jqgufenzy.top/Article/details/gtnjzheerg.html

[H04] 自定义异常类型
来源：http://dali.aizwys.cn/Article/details/gtfrdwhdks.html

Py:   class MyError(Exception): pass
来源：http://dali.hysaishi.cn/Article/details/gttcwvdyga.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhengqikj.top/Article/details/gtcgjafado.html

JS:   class MyError extends Error {}
来源：http://dali.shangyingyoupin.top/Article/details/gtjtmujqcn.html

TS:   class MyError extends Error {}
来源：http://dali.daxiang520.top/Article/details/gtezrbdlpz.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yuxming.cn/Article/details/gtvjeepyii.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.daxiang520.top/Article/details/gtbrwxfmbt.html

Ruby: class MyError < StandardError; end
来源：http://dali.quarkkingdee.top/Article/details/gtckjyrsai.html

C#:   class MyException : Exception {}
来源：http://dali.ivvv.top/Article/details/gtvyllcagu.html

[H05] 捕获特定类型
来源：http://dali.jyoumei.cn/Article/details/gtwhyoxyme.html

Py:   except ValueError as e:
来源：http://dali.xinyue.icu/Article/details/gtrkwdipvb.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhengqikj.top/Article/details/gthqzqcgww.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.gaohongyu789.top/Article/details/gtuvbefndu.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.nanxuanxn.top/Article/details/gtkhjqjgiy.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.vqdsnc.cn/Article/details/gtkvvgpgkg.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.meibo888.top/Article/details/gtihgezkcv.html

Ruby: rescue ArgumentError => e
来源：http://dali.tian-w.cn/Article/details/gteqcicjfa.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.sysykeji.top/Article/details/gtdtajqqcv.html

[H06] 可选值 / 空值安全访问
来源：http://dali.birdmap.top/Article/details/gtnzrdvyhb.html

Py:   value = d.get("k") or default
来源：http://dali.jinqigfzy.top/Article/details/gtlpmkkvug.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yangfankeji.com/Article/details/gtbmglcdkp.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.guannengcc.top/Article/details/gtqloqhvke.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuxvruaxv.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.hnqzz.top/Article/details/gtavnbbhlg.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.kuanghao11.cn/Article/details/gtslkdggbp.html

Ruby: d&.dig(:a, :b)
来源：http://dali.cdnleiting.top/Article/details/gtpxqnirfk.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhongyouzk.top/Article/details/gtqnpiuswt.html

[H07] 断言
来源：http://dali.tian-w.cn/Article/details/gtafahdjno.html

Py:   assert x > 0, "必须为正"
来源：http://dali.fzhhl.top/Article/details/gtqnqrqkrv.html

PHP:  assert($x > 0);
来源：http://dali.jiagoushi.top/Article/details/gtotfzcvke.html

JS:   console.assert(x > 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtslrzzyfp.html

TS:   console.assert(x > 0);
来源：http://dali.yvedp.cn/Article/details/gttsbjmprs.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yongpay.top/Article/details/gtlxnsllzm.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.tianlin.xyz/Article/details/gtureexmsb.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.sweek.top/Article/details/gtsinwxnkp.html

C#:   Debug.Assert(x > 0);
来源：http://dali.feifeiyinyue.top/Article/details/gtsfvnpvbs.html

[H08] 获取错误信息与堆栈
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwqzlsrzi.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yangfankeji.com/Article/details/gtrmpehgfa.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.fzhhl.top/Article/details/gtbamotgce.html

JS:   e.message;  e.stack
来源：http://dali.cdnleiting.top/Article/details/gtowjxdcyw.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zycfv.cn/Article/details/gtxpwjesxf.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.gaohongyu789.top/Article/details/gtqvxamywk.html

Go:   err.Error()
来源：http://dali.yj20258888.top/Article/details/gthlxrqxdi.html

Ruby: e.message;  e.backtrace
来源：http://dali.tanke756.top/Article/details/gtsmqmhnoc.html

C#:   e.Message;  e.StackTrace
来源：http://dali.sxryk.cn/Article/details/gtkxdcagix.html

[H09] 带错误码的异常
来源：http://dali.cashguo.top/Article/details/gtwexmhwds.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.vqdsnc.cn/Article/details/gtwdgwesux.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.sweek.top/Article/details/gtuvddmvle.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.hnqzz.top/Article/details/gtklirctju.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jlsjyb.cn/Article/details/gtikddboas.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.hysaishi.cn/Article/details/gtvovokflk.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.guowangkeji.top/Article/details/gttwptzawd.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.sufxvd.cn/Article/details/gtlvakxhww.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhoulong.xyz/Article/details/gtbeglzlur.html

[H10] 资源自动释放
来源：http://dali.cheryme.top/Article/details/gtakmeofrf.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.gotoacloud.top/Article/details/gtturkuuyu.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhengqikj.top/Article/details/gtoswnczzf.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.nanxinkj.top/Article/details/gtthgwgumt.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.snrcjt.cn/Article/details/gtweuxfriz.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.pengpengdd.cyou/Article/details/gttmgwuale.html

Go:   defer f.Close()
来源：http://dali.jyoumei.cn/Article/details/gteemhpwyq.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hongshengwenyu.top/Article/details/gtdxzgomzp.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gtbjqugxmb.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtxkvhsger.html

I. 正则表达式
来源：http://dali.shanyushiyangtech.top/Article/details/gtkmiowdwb.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtdbrsjygp.html

[I01] 判断是否匹配
来源：http://dali.nwbrower.top/Article/details/gtcdhxqlck.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.wangdashe.top/Article/details/gtibqdrjfc.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhiwuduotai.top/Article/details/gtceckelmm.html

JS:   /\d+/.test(s)
来源：http://dali.nanxinkj.top/Article/details/gtunsrwnrn.html

TS:   /\d+/.test(s)
来源：http://dali.xuanzx.com/Article/details/gtlbexmsbp.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yuanzhike.top/Article/details/gthpvxpiuh.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.quarkkingdee.top/Article/details/gtcldjrfuj.html

Ruby: s.match?(/\d+/)
来源：http://dali.vqdsnc.cn/Article/details/gtgnzxhgbu.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yj202588.top/Article/details/gthmmpjfhy.html

[I02] 提取所有匹配
来源：http://dali.chenjidiqi.icu/Article/details/gtfulkospe.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yongpay.top/Article/details/gtxkmsziyc.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.svipenyu.cn/Article/details/gthufsmynt.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.haohaochexian.top/Article/details/gtavbwpvsx.html

TS:   s.match(/\d+/g)
来源：http://dali.yueranfly.top/Article/details/gtkxetblkc.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.wangdashe.top/Article/details/gtarlnsejh.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtotomygps.html

Ruby: s.scan(/\d+/)
来源：http://dali.redwolf501.top/Article/details/gtonvkvfks.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.ivvv.top/Article/details/gtlfdoixpm.html

[I03] 提取捕获分组
来源：http://dali.fengsongda.top/Article/details/gtpxzjbbir.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.xinyue.icu/Article/details/gtmkrwunqw.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.andypj.xyz/Article/details/gtnfnvjjtc.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.xuanzx.com/Article/details/gtzzuxrddq.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.vqdsnc.cn/Article/details/gtnpqaquwn.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.pengpengdd.cyou/Article/details/gtrgubmzmc.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.nanxuanxn.top/Article/details/gtdlubtjkr.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jinghuilouyu.cn/Article/details/gtwkzgpqex.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.shzxlz.cn/Article/details/gtbrattels.html

[I04] 正则替换
来源：http://dali.gogol.net.cn/Article/details/gtnpujzixp.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yongpay.top/Article/details/gtapzsyslw.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.birdmap.top/Article/details/gtjzwwkptt.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.hnqzz.top/Article/details/gtshmujefn.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.cqqwz.cn/Article/details/gtltupnlrd.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhengqikj.top/Article/details/gtkkxiffes.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jlsjyb.cn/Article/details/gtnoqhsxzw.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.cashguo.top/Article/details/gtrlpwrybx.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.wangshuangyany.cn/Article/details/gtllzppkwz.html

[I05] 按正则拆分
来源：http://dali.jianghu66.top/Article/details/gtxlhaoyjx.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yonumen.top/Article/details/gtoadktzrl.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.shzxlz.cn/Article/details/gtztiyfifd.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.gogol.net.cn/Article/details/gtfokyhmtl.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.nanxinkj.top/Article/details/gtjkajpuxb.html

Java: s.split("\\s*,\\s*")
来源：http://dali.birdmap.top/Article/details/gtqcgutdbq.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.xinyue.icu/Article/details/gtwmztoewe.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.wangdashe.top/Article/details/gtupktjrje.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.tanke756.top/Article/details/gtqmfiormm.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.ivvv.top/Article/details/gtwzmkkhhc.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.sysykeji.top/Article/details/gtexjlohhf.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.smart0.xyz/Article/details/gtigdwldsh.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gtkigbhwet.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.fzhhl.top/Article/details/gtpcgfsfsm.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.smart0.xyz/Article/details/gtahlvkzui.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.hnxiangtu.top/Article/details/gtqapfyzfg.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.vqdsnc.cn/Article/details/gtsuitfqiy.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.c1oappe.top/Article/details/gtrizvoljg.html

[I07] 忽略大小写与多行模式
来源：http://dali.iojbl.cn/Article/details/gthjufaxzh.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.yj20258.top/Article/details/gtljogoyyn.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhoulong.xyz/Article/details/gtvmtpzhnv.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.daxiang520.top/Article/details/gtbgombfhs.html

TS:   /error/gim
来源：http://dali.shanyushiyangtech.top/Article/details/gtjacihgxc.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.mhx1999.top/Article/details/gtgfevbffj.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.cucudq.cn/Article/details/gtirtqyomw.html

Ruby: s.scan(/error/i)
来源：http://dali.sysykeji.top/Article/details/gtnskminsp.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.0kj1m.cn/Article/details/gtzwkmkolz.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.ivvv.top/Article/details/gtmqnrglqw.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yonumen.top/Article/details/gtbdalzith.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.hnxiangtu.top/Article/details/gtypvrqdps.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.0kj1m.cn/Article/details/gtcdafurtq.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.cashguo.top/Article/details/gtzcqlaziw.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.yj202588.top/Article/details/gtqwlazwcs.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.xuetiantiany.cn/Article/details/gtxtbzsgdg.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.hywenlv.cn/Article/details/gtyqwjofvm.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.aizwys.cn/Article/details/gtesjibmuh.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtbiojtgpb.html

J. 日期与时间
来源：http://dali.cucudq.cn/Article/details/gtwufseile.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtqhtxviuq.html

[J01] 获取当前时间
来源：http://dali.jinghuilouyu.cn/Article/details/gtontnafhm.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.aizwys.cn/Article/details/gtzelphhwf.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.havefunace.top/Article/details/gtpvrhbunx.html

JS:   new Date();  Date.now()
来源：http://dali.sweek.top/Article/details/gtutahbhki.html

TS:   new Date();  Date.now()
来源：http://dali.sxryk.cn/Article/details/gtkbdctvty.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.guowangkeji.top/Article/details/gtpaibykfz.html

Go:   time.Now()
来源：http://dali.cashguo.top/Article/details/gtffhutqnb.html

Ruby: Time.now
来源：http://dali.shuidangran.top/Article/details/gtjrflyega.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhongyouzk.top/Article/details/gtmkmoifbb.html

[J02] 格式化输出
来源：http://dali.fengsongda.top/Article/details/gtlkyopumm.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.tanke756.top/Article/details/gtzzhgvblo.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.9152youxi.cn/Article/details/gtpjjmzvro.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.daria6918.cn/Article/details/gtncshyifj.html

TS:   d.toISOString()
来源：http://dali.cdnleiting.top/Article/details/gtvzjvarwt.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.sysykeji.top/Article/details/gtfpbkomha.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yuanzhike.top/Article/details/gthzqchueo.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.feifeiyinyue.top/Article/details/gtqgkwfeob.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpqvvlvbf.html

[J03] 字符串解析为日期
来源：http://dali.smart0.xyz/Article/details/gtzmtgguje.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.svipenyu.cn/Article/details/gtttsoualn.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.xuanzx.com/Article/details/gtkrjulmco.html

JS:   new Date("2024-01-02")
来源：http://dali.gzhubu.top/Article/details/gtnfhbamgq.html

TS:   new Date("2024-01-02")
来源：http://dali.cucudq.cn/Article/details/gtgdfzglbi.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.yj202588.top/Article/details/gtslwruusx.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hammf.cn/Article/details/gtvxuvevif.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jqgfzy.top/Article/details/gtuzxrbgvu.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jinqigufen.top/Article/details/gtjiadinqo.html

[J04] 时间戳与日期互转
来源：http://dali.yj20258.top/Article/details/gtaafwafgj.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.xylfe.cn/Article/details/gtnkqnbyqq.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yuanzhike.top/Article/details/gtwogubgix.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.shanyushiyangtech.top/Article/details/gttanzuqcc.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.sweek.top/Article/details/gteoehokyj.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.smart0.xyz/Article/details/gtorbxupbl.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yanxiufei.cn/Article/details/gtbebbfouw.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.fzhhl.top/Article/details/gtqndbyeee.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.havefunace.top/Article/details/gtzyusjafq.html

[J05] 时间加减（加 7 天）
来源：http://dali.cucudq.cn/Article/details/gtjfqmytls.html

Py:   now + timedelta(days=7)
来源：http://dali.yongpay.top/Article/details/gtoyippsrl.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhengqikj.top/Article/details/gtmojpupwx.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yuxming.cn/Article/details/gtunwcawhm.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yongpay.top/Article/details/gtarsiuwir.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yongpay.top/Article/details/gtzmmpjgnl.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.cqqwz.cn/Article/details/gtvgbshlqd.html

Ruby: Time.now + 7 * 86400
来源：http://dali.tanke756.top/Article/details/gtwvjmtgxe.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.daria6918.cn/Article/details/gtvghuyptb.html

[J06] 计算两时间之差
来源：http://dali.birdmap.top/Article/details/gtdekonuwq.html

Py:   (end - start).total_seconds()
来源：http://dali.kuanghao11.cn/Article/details/gtdfpmqyha.html

PHP:  $end->diff($start)->days;
来源：http://dali.gaohongyu789.top/Article/details/gtmdacwfdo.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.smart0.xyz/Article/details/gtvlquxpvt.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.sufxvd.cn/Article/details/gtapnsgjsk.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.cdnleiting.top/Article/details/gtrykydkov.html

Go:   end.Sub(start).Hours()
来源：http://dali.feifeiyinyue.top/Article/details/gtemekljpn.html

Ruby: end - start                 # 返回秒数
来源：http://dali.xinyue.icu/Article/details/gtskiqtsql.html

C#:   (end - start).TotalSeconds
来源：http://dali.yvedp.cn/Article/details/gtogicbhvr.html

[J07] 比较两个日期
来源：http://dali.dianchejie.cn/Article/details/gtpbqsesrz.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.pengpengdd.cyou/Article/details/gtyqnkvvko.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yj20258.top/Article/details/gtjuumjvak.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.haohaochexian.top/Article/details/gtleabarsy.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.mhx1999.top/Article/details/gtjlsekyni.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.xinyue.icu/Article/details/gtthccqiiw.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yj20258.top/Article/details/gtrcktkhhf.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.nwbrower.top/Article/details/gtyngkaxde.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.mhx1999.top/Article/details/gtzhxeixvz.html

[J08] 提取年月日与星期
来源：http://dali.zycfv.cn/Article/details/gtfojhdzoe.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yanxiufei.cn/Article/details/gtdzkppvxz.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.sweek.top/Article/details/gtbvdhfjdw.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.tanke756.top/Article/details/gtxhrzecpj.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.wangdashe.top/Article/details/gtpwwqsqaj.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.jyoumei.cn/Article/details/gtpzdvftyh.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.hnxiangtu.top/Article/details/gtpgcqmfrm.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.guannengcc.top/Article/details/gtbqahetxk.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.daria6918.cn/Article/details/gtyhbnqrjd.html

[J09] 时区处理
来源：http://dali.pengpengdd.cyou/Article/details/gtteipiejg.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.chenjidiqi.icu/Article/details/gthvfuhyft.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.gotoacloud.top/Article/details/gtrvovypzl.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yonumen.top/Article/details/gtmfcrqrmc.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yonumen.top/Article/details/gtnogrqmei.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.birdmap.top/Article/details/gtnxejrrkh.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.hywenlv.cn/Article/details/gthnzwsxcz.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.cqqwz.cn/Article/details/gtqvjlnggr.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.feifeiyinyue.top/Article/details/gtbippkpcs.html

[J10] 取今天 / 本月第一天
来源：http://dali.9152youxi.cn/Article/details/gtxkbwarnv.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jianghu66.top/Article/details/gtmfwxlxce.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyczwbdho.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.aibaodan.cn/Article/details/gtcvqxpery.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.cdnleiting.top/Article/details/gtfbdewtsi.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.gotoacloud.top/Article/details/gtzkbanpvr.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.jinyuanbaomall.cn/Article/details/gthmsvvbjr.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.cashguo.top/Article/details/gtcckebjfm.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.hongshengwenyu.top/Article/details/gtizfdlhsn.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtnakmylgf.html

K. JSON 与序列化
来源：http://dali.gzhubu.top/Article/details/gtakzfmjsq.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtgyfwwlnt.html

[K01] 对象转 JSON 字符串
来源：http://dali.xinyue.icu/Article/details/gtamwzsstg.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.cqqwz.cn/Article/details/gtohamjaaz.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yangfankeji.com/Article/details/gtbwlxytbw.html

JS:   JSON.stringify(obj)
来源：http://dali.tian-w.cn/Article/details/gtpzmthfkq.html

TS:   JSON.stringify(obj)
来源：http://dali.nanxinkj.top/Article/details/gtnbakfkfb.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.jianghu66.top/Article/details/gtzailrtsd.html

Go:   json.Marshal(obj)
来源：http://dali.sweek.top/Article/details/gtpiwlutlr.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zhoulong.xyz/Article/details/gtjqwmqpye.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.ivvv.top/Article/details/gtsuswkywe.html

[K02] JSON 字符串转对象
来源：http://dali.dashuyun.cn/Article/details/gteofoalhs.html

Py:   json.loads(s)
来源：http://dali.zhongyouzk.top/Article/details/gtducvdrpp.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.smart0.xyz/Article/details/gtnrsilfqp.html

JS:   JSON.parse(s)
来源：http://dali.gotoacloud.top/Article/details/gtthwfymiu.html

TS:   JSON.parse(s)
来源：http://dali.svipenyu.cn/Article/details/gtdjnrdriq.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.guowangkeji.top/Article/details/gttnqurino.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.nwbrower.top/Article/details/gtqrgklgsw.html

Ruby: JSON.parse(s)
来源：http://dali.xziqi.cn/Article/details/gtovgjuwtp.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yuxming.cn/Article/details/gtotclxhmr.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.chenlongwang.top/Article/details/gthizytryk.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.iojbl.cn/Article/details/gtpfgekkkd.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.dashuyun.cn/Article/details/gtkirisvmi.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.hnqzz.top/Article/details/gthmyhxzed.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhongyouzk.top/Article/details/gtlvrlvsjf.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.zhoulong.xyz/Article/details/gtxjxjliyr.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.meibo888.top/Article/details/gtgwnbzwlp.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.ybcxt.top/Article/details/gtdqfrgrib.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.redwolf501.top/Article/details/gtuabarcdb.html

[K04] 读取 JSON 文件
来源：http://dali.sweek.top/Article/details/gtjznoyqci.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.nwbrower.top/Article/details/gtxrbnokks.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.nwbrower.top/Article/details/gtgseeyqzy.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.sxryk.cn/Article/details/gtcygkkoie.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.yuxming.cn/Article/details/gtphmvrnyd.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.iojbl.cn/Article/details/gtwnmmzzqq.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.ppjwa.cn/Article/details/gtjzfsekzc.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zhengqikj.top/Article/details/gthtnxdjla.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.xuetiantiany.cn/Article/details/gtqeaumbvs.html

[K05] 深拷贝对象
来源：http://dali.sysykeji.top/Article/details/gtclzlgrov.html

Py:   copy.deepcopy(obj)
来源：http://dali.jyoumei.cn/Article/details/gtjuknbanr.html

PHP:  unserialize(serialize($obj));
来源：http://dali.xuetiantiany.cn/Article/details/gttdsrpeda.html

JS:   structuredClone(obj)
来源：http://dali.wangdashe.top/Article/details/gtlrmfshcq.html

TS:   structuredClone(obj)
来源：http://dali.yj202588.top/Article/details/gtbyhdwicm.html


<!-- 参考信息 -->