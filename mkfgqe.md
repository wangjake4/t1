代发 wailian999

H. 异常与错误处理
来源：http://dali.yuanzhike.top/Article/details/gtsdihpswq.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtfgkurioa.html

[H01] try / catch 基础
来源：http://dali.xinyue.icu/Article/details/gttkgvzprv.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jianghu66.top/Article/details/gtlwzzhnao.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.xinyue.icu/Article/details/gtmvbdnyru.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmiejrguc.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.andypj.xyz/Article/details/gtsdiqaltc.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.tian-w.cn/Article/details/gtidnelhha.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.svipenyu.cn/Article/details/gtoueqrrdm.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.birdmap.top/Article/details/gtefwpqrvf.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jianghu66.top/Article/details/gtwrxlxpvw.html

[H02] finally / ensure 收尾
来源：http://dali.bjfxy.top/Article/details/gtrjbomvec.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.wangdashe.top/Article/details/gtvqmotzft.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.chenlongwang.top/Article/details/gtqnhfohbx.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.xylfe.cn/Article/details/gtlbiazgnr.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jlsjyb.cn/Article/details/gtgxlvmant.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.haohaochexian.top/Article/details/gtgkmhxktq.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyiidqbeh.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.xuetiantiany.cn/Article/details/gtbjsyxhue.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.gogol.net.cn/Article/details/gtetfynhzc.html

[H03] 主动抛出异常
来源：http://dali.cdnleiting.top/Article/details/gtirxkkymc.html

Py:   raise ValueError("错误信息")
来源：http://dali.zdqjudy.top/Article/details/gtttbwodvy.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gtpzwsfbxo.html

JS:   throw new Error("错误信息");
来源：http://dali.ybcxt.top/Article/details/gtptesepki.html

TS:   throw new Error("错误信息");
来源：http://dali.jinqigufen.top/Article/details/gtpzpbffag.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.cucudq.cn/Article/details/gtelxxolte.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhixingplan.top/Article/details/gtgmcwtuta.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.aizwys.cn/Article/details/gtyuczrvfa.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.gaohongyu789.top/Article/details/gtmwzsmvwf.html

[H04] 自定义异常类型
来源：http://dali.gogol.net.cn/Article/details/gtozistfby.html

Py:   class MyError(Exception): pass
来源：http://dali.cdnleiting.top/Article/details/gtljdesaje.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.ydzc1.top/Article/details/gtuqvzehyd.html

JS:   class MyError extends Error {}
来源：http://dali.cdnleiting.top/Article/details/gttzssiolr.html

TS:   class MyError extends Error {}
来源：http://dali.yvedp.cn/Article/details/gtsananzsp.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhixingplan.top/Article/details/gtgpbocuej.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.tanke756.top/Article/details/gtxzrmyxya.html

Ruby: class MyError < StandardError; end
来源：http://dali.haohaochexian.top/Article/details/gtcexwizjt.html

C#:   class MyException : Exception {}
来源：http://dali.dashuyun.cn/Article/details/gtixdbkepk.html

[H05] 捕获特定类型
来源：http://dali.jinghuilouyu.cn/Article/details/gtavmsjxys.html

Py:   except ValueError as e:
来源：http://dali.andypj.xyz/Article/details/gtdbnopjla.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.birdmap.top/Article/details/gtalhwxgmz.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhongyouzk.top/Article/details/gtiuayhbmc.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.ydzc1.top/Article/details/gtmjqsfkmq.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.guannengcc.top/Article/details/gtdwathzee.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.cqqwz.cn/Article/details/gttsqmhpjx.html

Ruby: rescue ArgumentError => e
来源：http://dali.jinghuilouyu.cn/Article/details/gtnuerucvo.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnohijisc.html

[H06] 可选值 / 空值安全访问
来源：http://dali.hammf.cn/Article/details/gtdzftrvdr.html

Py:   value = d.get("k") or default
来源：http://dali.sysykeji.top/Article/details/gtavxiscps.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.xziqi.cn/Article/details/gtsexrkfps.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jqgfzy.top/Article/details/gtovevlejc.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.ydzc1.top/Article/details/gtqbczvere.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.gaohongyu789.top/Article/details/gtibyofwdn.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.cdnleiting.top/Article/details/gthgydgflb.html

Ruby: d&.dig(:a, :b)
来源：http://dali.kuanghao11.cn/Article/details/gtxeghgqbb.html

C#:   obj?.A?.B ?? default
来源：http://dali.yangfankeji.com/Article/details/gtrunbonsi.html

[H07] 断言
来源：http://dali.tanke756.top/Article/details/gtkhgloqzk.html

Py:   assert x > 0, "必须为正"
来源：http://dali.hfpthk.cn/Article/details/gteshxxwti.html

PHP:  assert($x > 0);
来源：http://dali.pengpengdd.cyou/Article/details/gttjxxiqoq.html

JS:   console.assert(x > 0);
来源：http://dali.haohaochexian.top/Article/details/gtyotcndmt.html

TS:   console.assert(x > 0);
来源：http://dali.guannengcc.top/Article/details/gtnfbldcfe.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gtlgdjpvqc.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yonumen.top/Article/details/gtgeuqlodl.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.vqdsnc.cn/Article/details/gtdwdbfnuc.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtayooohnb.html

[H08] 获取错误信息与堆栈
来源：http://dali.mhx1999.top/Article/details/gtvyrwgksd.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yuanzhike.top/Article/details/gtvjxjfunt.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.xziqi.cn/Article/details/gtnycgtwng.html

JS:   e.message;  e.stack
来源：http://dali.yvedp.cn/Article/details/gtysppphks.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.tanke756.top/Article/details/gtkdvyrtos.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.ivvv.top/Article/details/gtskgmkcpa.html

Go:   err.Error()
来源：http://dali.havefunace.top/Article/details/gtcopffqaz.html

Ruby: e.message;  e.backtrace
来源：http://dali.tanke756.top/Article/details/gtinjkeoiv.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hfpthk.cn/Article/details/gthraevkfi.html

[H09] 带错误码的异常
来源：http://dali.sweek.top/Article/details/gtesqxpkji.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.ivvv.top/Article/details/gtbujdlace.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.zhoulong.xyz/Article/details/gtewxtklak.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.9152youxi.cn/Article/details/gtdwwnyfee.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.sxryk.cn/Article/details/gtbymsmyeo.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.xziqi.cn/Article/details/gtpfpxjcux.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.gaohongyu789.top/Article/details/gtboshmfvk.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhongyouzk.top/Article/details/gtdcsbmnku.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.xziqi.cn/Article/details/gtfgojpkpc.html

[H10] 资源自动释放
来源：http://dali.shuidangran.top/Article/details/gtgmsibclf.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.fengsongda.top/Article/details/gttvxunhda.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.snrcjt.cn/Article/details/gtttaoeeyn.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cashguo.top/Article/details/gtzwslofyh.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yj202588.top/Article/details/gtpixykqmq.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.dashuyun.cn/Article/details/gteodnzfau.html

Go:   defer f.Close()
来源：http://dali.tanke756.top/Article/details/gtzkrbvrfa.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.cucudq.cn/Article/details/gtkujcyeec.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.sysykeji.top/Article/details/gtgwcahrjd.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtjpsdwnei.html

I. 正则表达式
来源：http://dali.shzxlz.cn/Article/details/gtvddhgmqz.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gttkrpmrmi.html

[I01] 判断是否匹配
来源：http://dali.guannengcc.top/Article/details/gtaxuiuofg.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.cashguo.top/Article/details/gtwmcgvlie.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.pycfn.com/Article/details/gtsyqmlhjd.html

JS:   /\d+/.test(s)
来源：http://dali.smart0.xyz/Article/details/gtbiaeujyc.html

TS:   /\d+/.test(s)
来源：http://dali.xuanzx.com/Article/details/gtcldukqxz.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.guowangkeji.top/Article/details/gtmlclksae.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yj20258.top/Article/details/gtnjeiplyp.html

Ruby: s.match?(/\d+/)
来源：http://dali.wangdashe.top/Article/details/gtdlzrbnri.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.pycfn.com/Article/details/gthjhboieh.html

[I02] 提取所有匹配
来源：http://dali.zhiwuduotai.top/Article/details/gtofnbahzd.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yuanzhike.top/Article/details/gttuffpaxv.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttxpqwqmg.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.shzxlz.cn/Article/details/gtqtfffqdq.html

TS:   s.match(/\d+/g)
来源：http://dali.zdqjudy.top/Article/details/gtmzhjnngh.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.hnqzz.top/Article/details/gtlymshltg.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.c1oappe.top/Article/details/gtkccoickn.html

Ruby: s.scan(/\d+/)
来源：http://dali.iojbl.cn/Article/details/gtrfiqzbvn.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.dashuyun.cn/Article/details/gtewdmxbbm.html

[I03] 提取捕获分组
来源：http://dali.tanke756.top/Article/details/gtstnqfhxe.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.pengpengdd.cyou/Article/details/gtwuxzckiu.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jinqigufen.top/Article/details/gtchssdurs.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jqgufenzy.top/Article/details/gtbeiephbk.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.birdmap.top/Article/details/gtonpbmpun.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zdqjudy.top/Article/details/gtialztxvy.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.c1oappe.top/Article/details/gtecuwyakx.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.hywenlv.cn/Article/details/gtqvfxcwle.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.havefunace.top/Article/details/gtuoozutot.html

[I04] 正则替换
来源：http://dali.tanke756.top/Article/details/gtuqluahma.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yongpay.top/Article/details/gtnsftsdvh.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.xinyue.icu/Article/details/gtxryrtagk.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.sxryk.cn/Article/details/gtreoviiws.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.0kj1m.cn/Article/details/gtdyogolyn.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jlsjyb.cn/Article/details/gtydbsvgjw.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.svipenyu.cn/Article/details/gtqlpajxed.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.shzxlz.cn/Article/details/gtxesqrztg.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.shanyushiyangtech.top/Article/details/gtplpegumb.html

[I05] 按正则拆分
来源：http://dali.chenjidiqi.icu/Article/details/gtmiyvharo.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.xylfe.cn/Article/details/gtpsjlzzeq.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yuanzhike.top/Article/details/gtusgcrexp.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.sweek.top/Article/details/gtlmuojpib.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.dianchejie.cn/Article/details/gtecpfhnww.html

Java: s.split("\\s*,\\s*")
来源：http://dali.ppjwa.cn/Article/details/gtftffznlk.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhiwuduotai.top/Article/details/gtieqzulbz.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.nwbrower.top/Article/details/gtpcqsxruo.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.jqgufenzy.top/Article/details/gtmiddwdzq.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zhengqikj.top/Article/details/gtavovekli.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.kuanghao11.cn/Article/details/gttmwparsx.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.yvedp.cn/Article/details/gtqfnecosl.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhengqikj.top/Article/details/gtdbwgvxcq.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhijiandao.cn/Article/details/gtifgywzgm.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jinghuilouyu.cn/Article/details/gtqxcmrdlr.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.ivvv.top/Article/details/gtgwmcvgah.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.tianlin.xyz/Article/details/gtkwwahbty.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yangfankeji.com/Article/details/gtrsqqmanw.html

[I07] 忽略大小写与多行模式
来源：http://dali.yongpay.top/Article/details/gtxjujcdux.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jianghu66.top/Article/details/gtffznxugt.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.cqqwz.cn/Article/details/gtctagnqiy.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yonumen.top/Article/details/gtlpkzqjrj.html

TS:   /error/gim
来源：http://dali.yangfankeji.com/Article/details/gtxvlzpmis.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.cucudq.cn/Article/details/gtqsnitdgd.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.0kj1m.cn/Article/details/gtqnahljlx.html

Ruby: s.scan(/error/i)
来源：http://dali.haohaochexian.top/Article/details/gtmydazhdc.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.cheryme.top/Article/details/gteifuhzhq.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.snrcjt.cn/Article/details/gtnwmvebcn.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhixingplan.top/Article/details/gtpdiozwwh.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.cheryme.top/Article/details/gtnfysdvea.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ehwqpu.com/Article/details/gtvllegjil.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrjcdaqtv.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnmtizvrm.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.ivvv.top/Article/details/gtzdgcusik.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.hongshengwenyu.top/Article/details/gtpoqyfvur.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhoulong.xyz/Article/details/gtrivfkpok.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtsirscutn.html

J. 日期与时间
来源：http://dali.xuetiantiany.cn/Article/details/gthrpqzxlp.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtnwwjnwdz.html

[J01] 获取当前时间
来源：http://dali.nwbrower.top/Article/details/gtegkuondx.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.ydzc1.top/Article/details/gtxhjvkfxc.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.yuanzhike.top/Article/details/gtigjsbbwu.html

JS:   new Date();  Date.now()
来源：http://dali.tian-w.cn/Article/details/gtqkmbaolw.html

TS:   new Date();  Date.now()
来源：http://dali.dashuyun.cn/Article/details/gtgianwbtj.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jyoumei.cn/Article/details/gtsnemoikp.html

Go:   time.Now()
来源：http://dali.xuetiantiany.cn/Article/details/gtraghybzy.html

Ruby: Time.now
来源：http://dali.smart0.xyz/Article/details/gtwexxvraw.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.havefunace.top/Article/details/gtqvzsmnsf.html

[J02] 格式化输出
来源：http://dali.yonumen.top/Article/details/gtcuukddzr.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zhongyouzk.top/Article/details/gtmgallqur.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.fzhhl.top/Article/details/gtmuwfmkoy.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.wangdashe.top/Article/details/gtiteprrnh.html

TS:   d.toISOString()
来源：http://dali.jiagoushi.top/Article/details/gtrqxgflhu.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.xziqi.cn/Article/details/gtcbacstbt.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.9152youxi.cn/Article/details/gtligogrfc.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gaohongyu789.top/Article/details/gtosuiwmao.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.tanke756.top/Article/details/gtqutnswyq.html

[J03] 字符串解析为日期
来源：http://dali.wangshuangyany.cn/Article/details/gttnediqgu.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yueranfly.top/Article/details/gtthmpqztu.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.sysykeji.top/Article/details/gthwuvwoci.html

JS:   new Date("2024-01-02")
来源：http://dali.mhx1999.top/Article/details/gtqmwaeixk.html

TS:   new Date("2024-01-02")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqtyarqas.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.xuanzx.com/Article/details/gtpkstxnaz.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.shzxlz.cn/Article/details/gtwmitwwhn.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.pengpengdd.cyou/Article/details/gtensslxty.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.xziqi.cn/Article/details/gtbmdxwxzf.html

[J04] 时间戳与日期互转
来源：http://dali.yongpay.top/Article/details/gtaiuvgabf.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.tianlin.xyz/Article/details/gtgpgctqpp.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.aibaodan.cn/Article/details/gtilznsvql.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpijmtohu.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zhijiandao.cn/Article/details/gteymzdqin.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.gotoacloud.top/Article/details/gtyuwybkhd.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.tian-w.cn/Article/details/gtaanfdzge.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.wangdashe.top/Article/details/gtwnuzmcfg.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.nwbrower.top/Article/details/gtgkpmgvcs.html

[J05] 时间加减（加 7 天）
来源：http://dali.zhengqikj.top/Article/details/gthoxukesk.html

Py:   now + timedelta(days=7)
来源：http://dali.kuanghao11.cn/Article/details/gtagbvvehe.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.dashuyun.cn/Article/details/gtkmdgwcoi.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shanyushiyangtech.top/Article/details/gttancwoig.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xinyue.icu/Article/details/gtfrhjlnwx.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.wangdashe.top/Article/details/gtjryjbnxo.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.cqqwz.cn/Article/details/gtqmyshhmj.html

Ruby: Time.now + 7 * 86400
来源：http://dali.9152youxi.cn/Article/details/gtvysdkqok.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.xziqi.cn/Article/details/gtdexjxyym.html

[J06] 计算两时间之差
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxcowtgfk.html

Py:   (end - start).total_seconds()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtouutmwyx.html

PHP:  $end->diff($start)->days;
来源：http://dali.shzxlz.cn/Article/details/gtuxgffpwr.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.0kj1m.cn/Article/details/gtcdradjpw.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.aizwys.cn/Article/details/gtarltvmfi.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.cdnleiting.top/Article/details/gtonidnelv.html

Go:   end.Sub(start).Hours()
来源：http://dali.kuanghao11.cn/Article/details/gtbnhlhkns.html

Ruby: end - start                 # 返回秒数
来源：http://dali.daxiang520.top/Article/details/gtkyunywgx.html

C#:   (end - start).TotalSeconds
来源：http://dali.cheryme.top/Article/details/gtqspgiuex.html

[J07] 比较两个日期
来源：http://dali.jiagoushi.top/Article/details/gtmybkxarz.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.xziqi.cn/Article/details/gtrairbsaw.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.cdnleiting.top/Article/details/gtzmvbvgwi.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yj20258.top/Article/details/gtfqhhfjht.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.shuidangran.top/Article/details/gtwtxievsc.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.nanxinkj.top/Article/details/gtluzmloep.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jinqigfzy.top/Article/details/gtgqalfkti.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.daria6918.cn/Article/details/gtxfbhiyaf.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.ywan-chungtsiang.top/Article/details/gthtysuduo.html

[J08] 提取年月日与星期
来源：http://dali.c1oappe.top/Article/details/gtoasdzwok.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.quarkkingdee.top/Article/details/gtsyupjhoy.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.gaohongyu789.top/Article/details/gtufnwlpwe.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.fzhhl.top/Article/details/gtbecvgzyx.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.guannengcc.top/Article/details/gtspegtelq.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.meibo888.top/Article/details/gttlwppakf.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.9152youxi.cn/Article/details/gtkgbworkc.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbttgvisc.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.guannengcc.top/Article/details/gtsyqozdvn.html

[J09] 时区处理
来源：http://dali.aizwys.cn/Article/details/gtkzyqmxkk.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.xinyue.icu/Article/details/gtnqjirbfq.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.gzhubu.top/Article/details/gteiteaqzv.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.shuidangran.top/Article/details/gtchlsgnnh.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.ybcxt.top/Article/details/gtmtksyxli.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.shangyingyoupin.top/Article/details/gtvzqvfply.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.aibaodan.cn/Article/details/gtzitisvly.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jianghu66.top/Article/details/gtoglwktye.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.guowangkeji.top/Article/details/gtzybnnjrp.html

[J10] 取今天 / 本月第一天
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcanyehki.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.316326.xyz/Article/details/gtinzidknw.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.yueranfly.top/Article/details/gtdopxmktk.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.zhongyouzk.top/Article/details/gtqwspnfsh.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.jinghuilouyu.cn/Article/details/gtilhoowhn.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdhoquvhi.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.fzhhl.top/Article/details/gtouhhrxdc.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.daxiang520.top/Article/details/gtlmhwjcft.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.jqgufenzy.top/Article/details/gtidrybscq.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtutoklbwh.html

K. JSON 与序列化
来源：http://dali.andypj.xyz/Article/details/gtxsatmpcj.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtnsmlmmsb.html

[K01] 对象转 JSON 字符串
来源：http://dali.c1oappe.top/Article/details/gtrmoayhvq.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.quarkkingdee.top/Article/details/gtouprskba.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiziuryfz.html

JS:   JSON.stringify(obj)
来源：http://dali.cashguo.top/Article/details/gtdcuggmxb.html

TS:   JSON.stringify(obj)
来源：http://dali.daxiang520.top/Article/details/gtotvshtlc.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.xuanzx.com/Article/details/gtdwtvxaox.html

Go:   json.Marshal(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwpdptkzq.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.kuanghao11.cn/Article/details/gtqrrofecr.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.sweek.top/Article/details/gtvawkvemp.html

[K02] JSON 字符串转对象
来源：http://dali.tian-w.cn/Article/details/gttvopfacg.html

Py:   json.loads(s)
来源：http://dali.wangdashe.top/Article/details/gtuweodeej.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yuxming.cn/Article/details/gtmiugeegp.html

JS:   JSON.parse(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtixezqlch.html

TS:   JSON.parse(s)
来源：http://dali.tian-w.cn/Article/details/gtwmhrlkft.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jianghu66.top/Article/details/gtiexyltlx.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.fzhhl.top/Article/details/gtcgqekrdp.html

Ruby: JSON.parse(s)
来源：http://dali.birdmap.top/Article/details/gtgsysgqps.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.yj20258888.top/Article/details/gtbpzbsgpt.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgzfjyums.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.smart0.xyz/Article/details/gtiuaxulzu.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.xinyue.icu/Article/details/gteuiseemo.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhoulong.xyz/Article/details/gtqbklwrxc.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.sxryk.cn/Article/details/gtnsgvnqfl.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxdbtsszj.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.ppjwa.cn/Article/details/gtsmhofiih.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.svipenyu.cn/Article/details/gtlxmdqkhj.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.bjfxy.top/Article/details/gtilrtdjqi.html

[K04] 读取 JSON 文件
来源：http://dali.pycfn.com/Article/details/gtfmbwcdzg.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.zycfv.cn/Article/details/gtgkvccjtb.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.cashguo.top/Article/details/gtgousnoik.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.mhx1999.top/Article/details/gtmuymbuwj.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jqgufenzy.top/Article/details/gtlyqohzoy.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.wangdashe.top/Article/details/gtzqsyesox.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.zhiwuduotai.top/Article/details/gtvcutrlhu.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbioyiajo.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.xuanzx.com/Article/details/gtegopjvra.html

[K05] 深拷贝对象
来源：http://dali.zycfv.cn/Article/details/gtzuisvqwx.html


<!-- 参考信息 -->