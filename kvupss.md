代发 wailian999

PHP:  get_object_vars($obj);
来源：http://dali.mhx1999.top/Article/details/gtennyxhnl.html

JS:   Object.entries(obj)
来源：http://dali.zhixingplan.top/Article/details/gtdkvcwxye.html

TS:   Object.entries(obj)
来源：http://dali.ppjwa.cn/Article/details/gtrozqxcdn.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.ppjwa.cn/Article/details/gtthtihash.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.guowangkeji.top/Article/details/gtvozwsyjk.html

Ruby: obj.instance_variables
来源：http://dali.guowangkeji.top/Article/details/gtnhdrfzpy.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.fzhhl.top/Article/details/gtkzodamlo.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtdvoqefzr.html

H. 异常与错误处理
来源：http://dali.gogol.net.cn/Article/details/gtuvvfprli.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtwyxdzave.html

[H01] try / catch 基础
来源：http://dali.c1oappe.top/Article/details/gthyrebsil.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.0kj1m.cn/Article/details/gtqwoeyhjs.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.nwbrower.top/Article/details/gtsfululko.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yanxiufei.cn/Article/details/gtoaqqdcji.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhoulong.xyz/Article/details/gtimhhogvj.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jiagoushi.top/Article/details/gtjlegkytx.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.ehwqpu.com/Article/details/gtgrfsdrde.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.iojbl.cn/Article/details/gtlddindng.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jlsjyb.cn/Article/details/gtanxtzcmd.html

[H02] finally / ensure 收尾
来源：http://dali.wangdashe.top/Article/details/gtnesclutt.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.cashguo.top/Article/details/gtixupkwdq.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.ivvv.top/Article/details/gtholcnvxm.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.hammf.cn/Article/details/gtoudyazuy.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.nanxinkj.top/Article/details/gtvqutztva.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.smart0.xyz/Article/details/gtfezwqyzh.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hongshengwenyu.top/Article/details/gtyrfsnwip.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.aizwys.cn/Article/details/gtwjjbnhhi.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yonumen.top/Article/details/gtnlpwemtn.html

[H03] 主动抛出异常
来源：http://dali.yonumen.top/Article/details/gtxdktlqrd.html

Py:   raise ValueError("错误信息")
来源：http://dali.fengsongda.top/Article/details/gthmtbmjyr.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.9152youxi.cn/Article/details/gtphsdmmum.html

JS:   throw new Error("错误信息");
来源：http://dali.sweek.top/Article/details/gtwwfzloge.html

TS:   throw new Error("错误信息");
来源：http://dali.havefunace.top/Article/details/gttoxyrwpn.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.fengsongda.top/Article/details/gtxumoxgmo.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yangfankeji.com/Article/details/gtrqkcxnoh.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.316326.xyz/Article/details/gtihjtevjj.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jinghuilouyu.cn/Article/details/gtncomcbxd.html

[H04] 自定义异常类型
来源：http://dali.cqqwz.cn/Article/details/gtatxvfulu.html

Py:   class MyError(Exception): pass
来源：http://dali.fengsongda.top/Article/details/gthqrxnepw.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.mhx1999.top/Article/details/gtwfhwwxra.html

JS:   class MyError extends Error {}
来源：http://dali.316326.xyz/Article/details/gtqyjfpgbp.html

TS:   class MyError extends Error {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsasgmhed.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtodnivjol.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhoulong.xyz/Article/details/gtiriupjil.html

Ruby: class MyError < StandardError; end
来源：http://dali.quarkkingdee.top/Article/details/gtnckzjcbl.html

C#:   class MyException : Exception {}
来源：http://dali.zdqjudy.top/Article/details/gtroxlbzru.html

[H05] 捕获特定类型
来源：http://dali.pycfn.com/Article/details/gtneyqemoa.html

Py:   except ValueError as e:
来源：http://dali.bjfxy.top/Article/details/gtvfkeswop.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.nanxuanxn.top/Article/details/gtreasronw.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.gzhubu.top/Article/details/gtjmfslftp.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.chenzaomai.com/Article/details/gtcsdeoujr.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yuxming.cn/Article/details/gthluimwqm.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yuanzhike.top/Article/details/gtymhnuzuw.html

Ruby: rescue ArgumentError => e
来源：http://dali.ybcxt.top/Article/details/gtojkwzaht.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.birdmap.top/Article/details/gtpsoeohbh.html

[H06] 可选值 / 空值安全访问
来源：http://dali.tianlin.xyz/Article/details/gtriatfrxz.html

Py:   value = d.get("k") or default
来源：http://dali.cheryme.top/Article/details/gtgskvhpel.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.sufxvd.cn/Article/details/gtwjufuemn.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.cashguo.top/Article/details/gtughndzqb.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yj20258.top/Article/details/gtcngyyeyu.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.vqdsnc.cn/Article/details/gtoxpynfhe.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.smart0.xyz/Article/details/gtblbusmrp.html

Ruby: d&.dig(:a, :b)
来源：http://dali.wangshuangyany.cn/Article/details/gtbyiebhds.html

C#:   obj?.A?.B ?? default
来源：http://dali.guannengcc.top/Article/details/gtklljtnnq.html

[H07] 断言
来源：http://dali.quarkkingdee.top/Article/details/gtojsetcaq.html

Py:   assert x > 0, "必须为正"
来源：http://dali.cqqwz.cn/Article/details/gtcbpphfzu.html

PHP:  assert($x > 0);
来源：http://dali.yongpay.top/Article/details/gtxxocirnn.html

JS:   console.assert(x > 0);
来源：http://dali.jinqigfzy.top/Article/details/gtkqnodmif.html

TS:   console.assert(x > 0);
来源：http://dali.9152youxi.cn/Article/details/gtbkgehobs.html

Java: assert x > 0 : "必须为正";
来源：http://dali.wangdashe.top/Article/details/gtxxvlmpkm.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.cheryme.top/Article/details/gtcouevcmc.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.cqqwz.cn/Article/details/gtspjpxgdk.html

C#:   Debug.Assert(x > 0);
来源：http://dali.316326.xyz/Article/details/gtaeawsibt.html

[H08] 获取错误信息与堆栈
来源：http://dali.mhx1999.top/Article/details/gtmhhcqsvm.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.cucudq.cn/Article/details/gtnkiwjdjq.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.ybcxt.top/Article/details/gtlmjfmcsj.html

JS:   e.message;  e.stack
来源：http://dali.yueranfly.top/Article/details/gtclequmdn.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yj202588.top/Article/details/gtfodaiqbh.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jlsjyb.cn/Article/details/gtowtukacg.html

Go:   err.Error()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoqvbtpte.html

Ruby: e.message;  e.backtrace
来源：http://dali.shzxlz.cn/Article/details/gtullbrcus.html

C#:   e.Message;  e.StackTrace
来源：http://dali.iojbl.cn/Article/details/gttytpwzdn.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gtqqoxgkdd.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.bjfxy.top/Article/details/gtpnyngdgg.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.tian-w.cn/Article/details/gthzmlphpl.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.iojbl.cn/Article/details/gtaoiojyvd.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.hfpthk.cn/Article/details/gtmjtnpgpe.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtochcxmoo.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.hnxiangtu.top/Article/details/gtrgqvaduf.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.chenzaomai.com/Article/details/gtmunqylyt.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.tianlin.xyz/Article/details/gtzxwjvnwk.html

[H10] 资源自动释放
来源：http://dali.guowangkeji.top/Article/details/gtltyjnkap.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.meibo888.top/Article/details/gtvrqfvigj.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jianghu66.top/Article/details/gtipljsayk.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.daria6918.cn/Article/details/gtojgztkvx.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.havefunace.top/Article/details/gtpqjdlbet.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yvedp.cn/Article/details/gtgyxkubra.html

Go:   defer f.Close()
来源：http://dali.hywenlv.cn/Article/details/gtmgfejkhe.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.ehwqpu.com/Article/details/gtcqusphvx.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gtfaosjqxk.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtdaxpvajy.html

I. 正则表达式
来源：http://dali.gotoacloud.top/Article/details/gtljuzvpsq.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtltvwqlir.html

[I01] 判断是否匹配
来源：http://dali.tian-w.cn/Article/details/gtiwicknso.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.hongshengwenyu.top/Article/details/gtkpjgytyr.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.tianlin.xyz/Article/details/gtfyzgmnhi.html

JS:   /\d+/.test(s)
来源：http://dali.gotoacloud.top/Article/details/gtodpuujgc.html

TS:   /\d+/.test(s)
来源：http://dali.sxryk.cn/Article/details/gtlqtpgxuo.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.pycfn.com/Article/details/gtviizbeky.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.0kj1m.cn/Article/details/gtrdzvpngr.html

Ruby: s.match?(/\d+/)
来源：http://dali.wangshuangyany.cn/Article/details/gtuihlrimn.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.tianlin.xyz/Article/details/gtouiekkze.html

[I02] 提取所有匹配
来源：http://dali.zycfv.cn/Article/details/gtlvxnvzar.html

Py:   re.findall(r"\d+", s)
来源：http://dali.hammf.cn/Article/details/gtstehweli.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.hfpthk.cn/Article/details/gtuusnvnwk.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.gotoacloud.top/Article/details/gtebhxhzmt.html

TS:   s.match(/\d+/g)
来源：http://dali.sweek.top/Article/details/gtdnzqoxta.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.bjfxy.top/Article/details/gtllwmnlhc.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.haohaochexian.top/Article/details/gtuhtefepi.html

Ruby: s.scan(/\d+/)
来源：http://dali.redwolf501.top/Article/details/gtjwqazqsf.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zdqjudy.top/Article/details/gtoyxggzga.html

[I03] 提取捕获分组
来源：http://dali.nwbrower.top/Article/details/gtlopttmoi.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyuekbvrv.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.daria6918.cn/Article/details/gtmgpvwgok.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.iojbl.cn/Article/details/gteehvyigh.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.andypj.xyz/Article/details/gtdlztqonc.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.fengsongda.top/Article/details/gtljfffrts.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.xuanzx.com/Article/details/gtpbpciqbo.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.c1oappe.top/Article/details/gthsbixohj.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.9152youxi.cn/Article/details/gtcpihgxvr.html

[I04] 正则替换
来源：http://dali.feifeiyinyue.top/Article/details/gtvtdluaay.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.ivvv.top/Article/details/gtvtjdpsgi.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zdqjudy.top/Article/details/gtigeduzrw.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.ybcxt.top/Article/details/gtipkaikzr.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.nwbrower.top/Article/details/gtpwkfiuqy.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.guowangkeji.top/Article/details/gtqvxghdkc.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zdqjudy.top/Article/details/gtzvckejdn.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.hnxiangtu.top/Article/details/gtryfyrlcs.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.gzhubu.top/Article/details/gtvbjemuhh.html

[I05] 按正则拆分
来源：http://dali.0kj1m.cn/Article/details/gthnjgbtlj.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.shangyingyoupin.top/Article/details/gtsdwjbezo.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gtgvtugkwv.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.gzhubu.top/Article/details/gtnspsjkri.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhoulong.xyz/Article/details/gtgznufgzs.html

Java: s.split("\\s*,\\s*")
来源：http://dali.9152youxi.cn/Article/details/gttepnveoz.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.xylfe.cn/Article/details/gtmrltttie.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.daxiang520.top/Article/details/gtursnzdkq.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.wangdashe.top/Article/details/gttcyqvilm.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.xuetiantiany.cn/Article/details/gtwbxerckl.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.snrcjt.cn/Article/details/gtyawkueby.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.ivvv.top/Article/details/gtinhemklx.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yueranfly.top/Article/details/gtbyybjrah.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.birdmap.top/Article/details/gtiqxdumjm.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.cheryme.top/Article/details/gtcyudhvck.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.andypj.xyz/Article/details/gtusxnndkg.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.ppjwa.cn/Article/details/gtyrjgfzfp.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.tianlin.xyz/Article/details/gtqdifckno.html

[I07] 忽略大小写与多行模式
来源：http://dali.dashuyun.cn/Article/details/gtdafymqvk.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdxwnjfhs.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.tian-w.cn/Article/details/gthdtbgfqp.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.smart0.xyz/Article/details/gtauxcikgy.html

TS:   /error/gim
来源：http://dali.jlsjyb.cn/Article/details/gtgfwbxmmb.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.haohaochexian.top/Article/details/gtzhlryxfx.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.xinyue.icu/Article/details/gtpjledwdy.html

Ruby: s.scan(/error/i)
来源：http://dali.yuxming.cn/Article/details/gteqmilahw.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jlsjyb.cn/Article/details/gtichqegkb.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.chenjidiqi.icu/Article/details/gtshamjgve.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.andypj.xyz/Article/details/gtbcaypyri.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.hongshengwenyu.top/Article/details/gtmtudamvi.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.316326.xyz/Article/details/gtmkqnozuz.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yuxming.cn/Article/details/gtluzezohh.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.chenjidiqi.icu/Article/details/gtyybqxeko.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zhongyouzk.top/Article/details/gtmkkfpoal.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.birdmap.top/Article/details/gtikqjvntw.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.dianchejie.cn/Article/details/gtdattpick.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtpkiwsuua.html

J. 日期与时间
来源：http://dali.aibaodan.cn/Article/details/gtmpqvvctq.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gttzlljuru.html

[J01] 获取当前时间
来源：http://dali.xylfe.cn/Article/details/gtrsnzewgr.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yj202588.top/Article/details/gtmekaensn.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.xinyue.icu/Article/details/gtqdnujztr.html

JS:   new Date();  Date.now()
来源：http://dali.ydzc1.top/Article/details/gtqxgozrtz.html

TS:   new Date();  Date.now()
来源：http://dali.haohaochexian.top/Article/details/gtgadzskyh.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jinqigfzy.top/Article/details/gtkgrkayai.html

Go:   time.Now()
来源：http://dali.jinghuilouyu.cn/Article/details/gtwexpjger.html

Ruby: Time.now
来源：http://dali.cheryme.top/Article/details/gtfrjmuzdr.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.wangshuangyany.cn/Article/details/gtvapfenoo.html

[J02] 格式化输出
来源：http://dali.jlsjyb.cn/Article/details/gtfpjakrxp.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.iojbl.cn/Article/details/gtanwounln.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.bjfxy.top/Article/details/gtulrgviqs.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.guowangkeji.top/Article/details/gtvcprccwz.html

TS:   d.toISOString()
来源：http://dali.xuanzx.com/Article/details/gtugjymnnw.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.wangshuangyany.cn/Article/details/gtxcwpioyu.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.guowangkeji.top/Article/details/gtjypngarh.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hammf.cn/Article/details/gtsomfzbtr.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.quarkkingdee.top/Article/details/gtswaparqx.html

[J03] 字符串解析为日期
来源：http://dali.c1oappe.top/Article/details/gtuctrblzk.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.iojbl.cn/Article/details/gtmcsmkxeq.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.sysykeji.top/Article/details/gtjvzqfrag.html

JS:   new Date("2024-01-02")
来源：http://dali.9152youxi.cn/Article/details/gtcncxpnht.html

TS:   new Date("2024-01-02")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfumpqpvb.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhixingplan.top/Article/details/gtujlhjung.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.cheryme.top/Article/details/gtwrnofidp.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoorsypld.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yj202588.top/Article/details/gtmvtfeohl.html

[J04] 时间戳与日期互转
来源：http://dali.gzhubu.top/Article/details/gtyiisfree.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yvedp.cn/Article/details/gtpucmumaf.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.cucudq.cn/Article/details/gthbzvquyq.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.wangdashe.top/Article/details/gtlldfsnea.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jlsjyb.cn/Article/details/gtoaueoeqr.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.meibo888.top/Article/details/gtlnhvrhwi.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.xylfe.cn/Article/details/gtcnfblviz.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.quarkkingdee.top/Article/details/gtmmxlmtkk.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.jinqigufen.top/Article/details/gtmpecozna.html

[J05] 时间加减（加 7 天）
来源：http://dali.gaohongyu789.top/Article/details/gtmunuwkrx.html

Py:   now + timedelta(days=7)
来源：http://dali.sufxvd.cn/Article/details/gtaphnctus.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.meibo888.top/Article/details/gtfnqmrwlc.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvpbpomvk.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhixingplan.top/Article/details/gtbzkerfkw.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.ybcxt.top/Article/details/gtqutxxzyp.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.ivvv.top/Article/details/gtllyacuxw.html

Ruby: Time.now + 7 * 86400
来源：http://dali.cashguo.top/Article/details/gtmxgzlwnt.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yanxiufei.cn/Article/details/gttnscnivm.html

[J06] 计算两时间之差
来源：http://dali.cucudq.cn/Article/details/gtqcyxiloz.html

Py:   (end - start).total_seconds()
来源：http://dali.xuetiantiany.cn/Article/details/gthwiuuvpd.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhengqikj.top/Article/details/gtwmuldbdf.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.shuidangran.top/Article/details/gtjpmeaxus.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jinqigfzy.top/Article/details/gtqjhvnfnk.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.cheryme.top/Article/details/gtsyfvmoez.html

Go:   end.Sub(start).Hours()
来源：http://dali.gzhubu.top/Article/details/gthhtjhngd.html

Ruby: end - start                 # 返回秒数
来源：http://dali.nanxinkj.top/Article/details/gttoivuuwt.html

C#:   (end - start).TotalSeconds
来源：http://dali.hnxiangtu.top/Article/details/gtdbylftfl.html

[J07] 比较两个日期
来源：http://dali.chenzaomai.com/Article/details/gtgkdjhxbq.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.chenlongwang.top/Article/details/gtcajeiaok.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.pengpengdd.cyou/Article/details/gtibxykomz.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.shuidangran.top/Article/details/gtosgpfykx.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.pengpengdd.cyou/Article/details/gtrwmqsymd.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.chenjidiqi.icu/Article/details/gtyrgmryjh.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.sufxvd.cn/Article/details/gtstgcrzqh.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yuanzhike.top/Article/details/gtbozkpkpb.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.0kj1m.cn/Article/details/gtgwgzfnsr.html

[J08] 提取年月日与星期
来源：http://dali.jqgfzy.top/Article/details/gthvsuxmap.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.cucudq.cn/Article/details/gtzohjakmo.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.cucudq.cn/Article/details/gtmnxysvzu.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.jqgfzy.top/Article/details/gtrsuducul.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.gaohongyu789.top/Article/details/gtypygxpzp.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.cheryme.top/Article/details/gtbscsuoju.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yj20258.top/Article/details/gtichpjmdm.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.jqgfzy.top/Article/details/gtxtuwnrxv.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.hammf.cn/Article/details/gttxqqlsgf.html

[J09] 时区处理
来源：http://dali.gzhubu.top/Article/details/gtamvhjoup.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.bjfxy.top/Article/details/gtftmkmrzp.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.pengpengdd.cyou/Article/details/gtgqfpjrsw.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.iojbl.cn/Article/details/gtqqjcsdbz.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.sufxvd.cn/Article/details/gtowjdfqyq.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.aibaodan.cn/Article/details/gtbbbiibdz.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yj202588.top/Article/details/gtuoiuuwli.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.hywenlv.cn/Article/details/gtscltsgzb.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvdlxmpwz.html

[J10] 取今天 / 本月第一天
来源：http://dali.yanxiufei.cn/Article/details/gturldficr.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.fzhhl.top/Article/details/gtcotwchpo.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.guowangkeji.top/Article/details/gtulpqoauo.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.kuanghao11.cn/Article/details/gtoprpjpwm.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.mhx1999.top/Article/details/gtbvannutf.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yuxming.cn/Article/details/gtbbsrkvon.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.aizwys.cn/Article/details/gtzovdttzr.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.0kj1m.cn/Article/details/gteujmsekh.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.zhixingplan.top/Article/details/gtxrplmcgq.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtyfongebr.html

K. JSON 与序列化
来源：http://dali.chenlongwang.top/Article/details/gtoihgqsti.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtltkmmvdf.html

[K01] 对象转 JSON 字符串
来源：http://dali.yueranfly.top/Article/details/gtztetdvoj.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtddbcjawn.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.yanxiufei.cn/Article/details/gtjguxizee.html

JS:   JSON.stringify(obj)
来源：http://dali.iojbl.cn/Article/details/gtkcyhvnea.html

TS:   JSON.stringify(obj)
来源：http://dali.jqgfzy.top/Article/details/gtvujmyytk.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.havefunace.top/Article/details/gtlkgcqmld.html

Go:   json.Marshal(obj)
来源：http://dali.pycfn.com/Article/details/gtyhhhgqrr.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.hysaishi.cn/Article/details/gtsengqxlc.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.jqgfzy.top/Article/details/gtyzfiulci.html

[K02] JSON 字符串转对象
来源：http://dali.hnqzz.top/Article/details/gtilmlkehx.html

Py:   json.loads(s)
来源：http://dali.hysaishi.cn/Article/details/gttmvhojup.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jinqigfzy.top/Article/details/gtednpwgja.html

JS:   JSON.parse(s)
来源：http://dali.tian-w.cn/Article/details/gtedxxomtj.html

TS:   JSON.parse(s)
来源：http://dali.snrcjt.cn/Article/details/gtqpdxwtqe.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.jinghuilouyu.cn/Article/details/gtkpyltkzd.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.c1oappe.top/Article/details/gtgcjrynzc.html

Ruby: JSON.parse(s)
来源：http://dali.cucudq.cn/Article/details/gtrhczvdtx.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtulqkizby.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yonumen.top/Article/details/gtlyzgtqgx.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.sweek.top/Article/details/gtktrgnxtd.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.bjfxy.top/Article/details/gtepryvyvr.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.tianlin.xyz/Article/details/gtiqnmaroe.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhongyouzk.top/Article/details/gtcbgzluly.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.hnxiangtu.top/Article/details/gtlaeqerjy.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.shanyushiyangtech.top/Article/details/gtvezwacex.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtfyuvkuar.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.pycfn.com/Article/details/gttgpdzblp.html

[K04] 读取 JSON 文件
来源：http://dali.hnxiangtu.top/Article/details/gtxkoupslq.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.shzxlz.cn/Article/details/gtsmowknos.html


<!-- 参考信息 -->