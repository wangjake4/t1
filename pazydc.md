代发 wailian999

PHP:  get_object_vars($obj);
来源：http://dali.jianghu66.top/Article/details/gtljlpflkh.html

JS:   Object.entries(obj)
来源：http://dali.c1oappe.top/Article/details/gtdhexktgg.html

TS:   Object.entries(obj)
来源：http://dali.birdmap.top/Article/details/gtgpnovqxz.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hnxiangtu.top/Article/details/gtgvfizgce.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.xuetiantiany.cn/Article/details/gtvqpogjao.html

Ruby: obj.instance_variables
来源：http://dali.ppjwa.cn/Article/details/gtzppuanza.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.cheryme.top/Article/details/gtbwvyolzb.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtobsqbwsg.html

H. 异常与错误处理
来源：http://dali.snrcjt.cn/Article/details/gtgmzwdauf.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gthszrhdpn.html

[H01] try / catch 基础
来源：http://dali.jinqigfzy.top/Article/details/gtlrtmgevh.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.ppjwa.cn/Article/details/gtvsrkviaf.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zycfv.cn/Article/details/gtukhktkeu.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.dashuyun.cn/Article/details/gtczakhwmc.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.chenzaomai.com/Article/details/gtshnqkykk.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.cashguo.top/Article/details/gtttbrrxzh.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yj20258.top/Article/details/gtmmvqghrz.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zycfv.cn/Article/details/gtxqufkbfo.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.gzhubu.top/Article/details/gtnifhhkre.html

[H02] finally / ensure 收尾
来源：http://dali.cdnleiting.top/Article/details/gtyrwuzpne.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.vqdsnc.cn/Article/details/gtagnrqnjl.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yuxming.cn/Article/details/gthbihysds.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.daria6918.cn/Article/details/gtloetundp.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yj202588.top/Article/details/gtlcgywznp.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.xylfe.cn/Article/details/gtzkmazuyr.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.sysykeji.top/Article/details/gtjiimttgb.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.fzhhl.top/Article/details/gtqptlhmvn.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.shzxlz.cn/Article/details/gtmrdqexyc.html

[H03] 主动抛出异常
来源：http://dali.sufxvd.cn/Article/details/gtmwmpasmh.html

Py:   raise ValueError("错误信息")
来源：http://dali.shanyushiyangtech.top/Article/details/gtbodrcuzm.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.cheryme.top/Article/details/gtismwnvgp.html

JS:   throw new Error("错误信息");
来源：http://dali.jinqigfzy.top/Article/details/gtwfuhmavc.html

TS:   throw new Error("错误信息");
来源：http://dali.ehwqpu.com/Article/details/gtjuwaanmh.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.dashuyun.cn/Article/details/gteefbtvtx.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.chenzaomai.com/Article/details/gtkovxgzgj.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jlsjyb.cn/Article/details/gtlmrsopue.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.tanke756.top/Article/details/gtmpwnqsar.html

[H04] 自定义异常类型
来源：http://dali.ivvv.top/Article/details/gtvlzlhrfs.html

Py:   class MyError(Exception): pass
来源：http://dali.hywenlv.cn/Article/details/gtvqsjunyo.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.sysykeji.top/Article/details/gtpmdhiqge.html

JS:   class MyError extends Error {}
来源：http://dali.zhixingplan.top/Article/details/gtlhzaqink.html

TS:   class MyError extends Error {}
来源：http://dali.xinyue.icu/Article/details/gtqdrrkftw.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhixingplan.top/Article/details/gtcgpwnucl.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.tian-w.cn/Article/details/gtqmhysoci.html

Ruby: class MyError < StandardError; end
来源：http://dali.sweek.top/Article/details/gtptbcoutx.html

C#:   class MyException : Exception {}
来源：http://dali.jqgfzy.top/Article/details/gtfyviwywe.html

[H05] 捕获特定类型
来源：http://dali.gzhubu.top/Article/details/gtzptgicgg.html

Py:   except ValueError as e:
来源：http://dali.shanyushiyangtech.top/Article/details/gtcklsvdkz.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.birdmap.top/Article/details/gtjouwrcky.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.ppjwa.cn/Article/details/gtlgmxmurh.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yj20258888.top/Article/details/gtcfblhhaz.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.fzhhl.top/Article/details/gtmosriqcw.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.cashguo.top/Article/details/gtppyzhxtx.html

Ruby: rescue ArgumentError => e
来源：http://dali.jqgfzy.top/Article/details/gtlgwhjezh.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.birdmap.top/Article/details/gtcsfxfmwh.html

[H06] 可选值 / 空值安全访问
来源：http://dali.havefunace.top/Article/details/gtogidvgbw.html

Py:   value = d.get("k") or default
来源：http://dali.fengsongda.top/Article/details/gtxlampvtp.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.dianchejie.cn/Article/details/gtqvzygiqi.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.sufxvd.cn/Article/details/gtrcsgffiv.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.shzxlz.cn/Article/details/gtnzdsxkti.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.shuidangran.top/Article/details/gtfzcperav.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.xziqi.cn/Article/details/gtcqeoiqoq.html

Ruby: d&.dig(:a, :b)
来源：http://dali.ehwqpu.com/Article/details/gtnjauxran.html

C#:   obj?.A?.B ?? default
来源：http://dali.cashguo.top/Article/details/gtvcxcankn.html

[H07] 断言
来源：http://dali.zhengqikj.top/Article/details/gtyvoptwfe.html

Py:   assert x > 0, "必须为正"
来源：http://dali.daxiang520.top/Article/details/gtgvnxvcfr.html

PHP:  assert($x > 0);
来源：http://dali.hnxiangtu.top/Article/details/gtrhyiohxo.html

JS:   console.assert(x > 0);
来源：http://dali.yangfankeji.com/Article/details/gtavgupghm.html

TS:   console.assert(x > 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdzpxntoy.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhengqikj.top/Article/details/gtgqiuxlju.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.haohaochexian.top/Article/details/gtaagkwdlv.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jlsjyb.cn/Article/details/gtmpljpyvd.html

C#:   Debug.Assert(x > 0);
来源：http://dali.sufxvd.cn/Article/details/gtdsavgnia.html

[H08] 获取错误信息与堆栈
来源：http://dali.cashguo.top/Article/details/gtmwpissag.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yvedp.cn/Article/details/gtpgizcwps.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.shangyingyoupin.top/Article/details/gtrpzvvzhz.html

JS:   e.message;  e.stack
来源：http://dali.chenlongwang.top/Article/details/gtyydggrjf.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.aibaodan.cn/Article/details/gtpibctzlf.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.snrcjt.cn/Article/details/gttbczlprb.html

Go:   err.Error()
来源：http://dali.9152youxi.cn/Article/details/gtrcqjqgih.html

Ruby: e.message;  e.backtrace
来源：http://dali.svipenyu.cn/Article/details/gtflwocptq.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhoulong.xyz/Article/details/gtomoffksp.html

[H09] 带错误码的异常
来源：http://dali.birdmap.top/Article/details/gtuyreuxuz.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhiwuduotai.top/Article/details/gtljgyiagm.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yj20258.top/Article/details/gtqrkzpvci.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhiwuduotai.top/Article/details/gtyporcayk.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.redwolf501.top/Article/details/gtuwgfzilf.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.hammf.cn/Article/details/gtoxwylnov.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yonumen.top/Article/details/gteqneuspj.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.sufxvd.cn/Article/details/gtdlizbukr.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.tanke756.top/Article/details/gtutwwimeg.html

[H10] 资源自动释放
来源：http://dali.shangyingyoupin.top/Article/details/gtzgenkjcc.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.ybcxt.top/Article/details/gtrvesjkih.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.nwbrower.top/Article/details/gtdjrevoao.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.aizwys.cn/Article/details/gtejcqzotr.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.pengpengdd.cyou/Article/details/gtmynupnba.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yj20258888.top/Article/details/gtykzxfoat.html

Go:   defer f.Close()
来源：http://dali.mhx1999.top/Article/details/gttynwjmhh.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jinqigfzy.top/Article/details/gtwmzsdzqw.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yuanzhike.top/Article/details/gtabzjlxbw.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtptoyfbva.html

I. 正则表达式
来源：http://dali.ivvv.top/Article/details/gtyspxepou.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtfuwumvov.html

[I01] 判断是否匹配
来源：http://dali.yuanzhike.top/Article/details/gtnttywmsz.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.svipenyu.cn/Article/details/gtibgpzkrc.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.sweek.top/Article/details/gtpfjesvbn.html

JS:   /\d+/.test(s)
来源：http://dali.fzhhl.top/Article/details/gtanuncvas.html

TS:   /\d+/.test(s)
来源：http://dali.guowangkeji.top/Article/details/gtkzyzvrhy.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.guowangkeji.top/Article/details/gtizbpcgdd.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.shuidangran.top/Article/details/gtwvkvffsh.html

Ruby: s.match?(/\d+/)
来源：http://dali.gaohongyu789.top/Article/details/gtjwyigrdb.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.ybcxt.top/Article/details/gtvetwjbts.html

[I02] 提取所有匹配
来源：http://dali.zhaomingkeji.xyz/Article/details/gtppwrhmie.html

Py:   re.findall(r"\d+", s)
来源：http://dali.sufxvd.cn/Article/details/gtegffpzce.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jyoumei.cn/Article/details/gtdwmtkexf.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.hywenlv.cn/Article/details/gtadzzkxzy.html

TS:   s.match(/\d+/g)
来源：http://dali.havefunace.top/Article/details/gtxyhphmqx.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jinqigfzy.top/Article/details/gtkxvduxtp.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.cheryme.top/Article/details/gtogoozpof.html

Ruby: s.scan(/\d+/)
来源：http://dali.guowangkeji.top/Article/details/gtmorujpxx.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.ybcxt.top/Article/details/gtqkgqzuoc.html

[I03] 提取捕获分组
来源：http://dali.yj202588.top/Article/details/gtwthgziys.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.hnqzz.top/Article/details/gtwktbvfcx.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.pycfn.com/Article/details/gtdypgqrdh.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yj20258.top/Article/details/gtzrfsctwa.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.gotoacloud.top/Article/details/gtlwjgxxhl.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.guannengcc.top/Article/details/gtxukmexjv.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.xuanzx.com/Article/details/gtwetnvywj.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.aibaodan.cn/Article/details/gtpkgeupkw.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.gotoacloud.top/Article/details/gtjbtvkuni.html

[I04] 正则替换
来源：http://dali.yonumen.top/Article/details/gtitcuoagr.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.ybcxt.top/Article/details/gtxpzxkxhg.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yvedp.cn/Article/details/gtdmspmfli.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.feifeiyinyue.top/Article/details/gtwtduurnr.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.ppjwa.cn/Article/details/gtvfpzjsmf.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.nanxuanxn.top/Article/details/gtpzjhcdkv.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jyoumei.cn/Article/details/gtikyhasoa.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.daria6918.cn/Article/details/gtlatxpyfq.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtacrhgjrb.html

[I05] 按正则拆分
来源：http://dali.dianchejie.cn/Article/details/gtsyulktei.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.tanke756.top/Article/details/gtkkofmctn.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.nanxuanxn.top/Article/details/gtjtitkwxj.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.cashguo.top/Article/details/gtslogjpij.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.ydzc1.top/Article/details/gtxjsyfdoj.html

Java: s.split("\\s*,\\s*")
来源：http://dali.birdmap.top/Article/details/gtsooznrls.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhengqikj.top/Article/details/gtvpvjiaqn.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.redwolf501.top/Article/details/gtgvgpnjxg.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.cucudq.cn/Article/details/gtnzvyjdsp.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.cashguo.top/Article/details/gtyhvclnqv.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.wangshuangyany.cn/Article/details/gtytyhctfy.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.xinyue.icu/Article/details/gtjbbfrgdh.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.9152youxi.cn/Article/details/gtgowbrsta.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.pengpengdd.cyou/Article/details/gtlfjdtsqp.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.svipenyu.cn/Article/details/gtxizzdjhf.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.pycfn.com/Article/details/gtwfewcvuw.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.jinyuanbaomall.cn/Article/details/gtimqzyedm.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.hywenlv.cn/Article/details/gtrpeyudsu.html

[I07] 忽略大小写与多行模式
来源：http://dali.ppjwa.cn/Article/details/gtgrjjfjyx.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.hammf.cn/Article/details/gtuwaahwun.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yanxiufei.cn/Article/details/gtlgqbmywv.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.ppjwa.cn/Article/details/gtlfkpuimh.html

TS:   /error/gim
来源：http://dali.hywenlv.cn/Article/details/gtxflgdxyt.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.redwolf501.top/Article/details/gtuaabgtvf.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.vqdsnc.cn/Article/details/gtrvkwhnrb.html

Ruby: s.scan(/error/i)
来源：http://dali.shzxlz.cn/Article/details/gtzqczqmwe.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.aibaodan.cn/Article/details/gtcphrlvnh.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.nanxuanxn.top/Article/details/gtrxrbckbe.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.hnxiangtu.top/Article/details/gthxkbupxr.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.xinyue.icu/Article/details/gtbcfamjme.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.chenlongwang.top/Article/details/gtdilvcrsm.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zdqjudy.top/Article/details/gtnvudpall.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.gzhubu.top/Article/details/gtgznlyghl.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.gogol.net.cn/Article/details/gtkzkyvryq.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.zhijiandao.cn/Article/details/gtysfntobb.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.gotoacloud.top/Article/details/gtpplgzkjw.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtdiwkrpgl.html

J. 日期与时间
来源：http://dali.cashguo.top/Article/details/gthlrvoroc.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtsefswuds.html

[J01] 获取当前时间
来源：http://dali.shuidangran.top/Article/details/gtwodbkwul.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqvoybfvh.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.aibaodan.cn/Article/details/gttndgbiws.html

JS:   new Date();  Date.now()
来源：http://dali.tianlin.xyz/Article/details/gtmgrvjsot.html

TS:   new Date();  Date.now()
来源：http://dali.cheryme.top/Article/details/gtgskggivz.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.pycfn.com/Article/details/gtxtordwos.html

Go:   time.Now()
来源：http://dali.0kj1m.cn/Article/details/gtqrwlvrdr.html

Ruby: Time.now
来源：http://dali.nanxuanxn.top/Article/details/gtaxwfxbjy.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.tianlin.xyz/Article/details/gtqcdtrxcb.html

[J02] 格式化输出
来源：http://dali.nanxuanxn.top/Article/details/gtprckadmf.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.svipenyu.cn/Article/details/gtxbmgbsgu.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.hysaishi.cn/Article/details/gtahkpcvsx.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.yonumen.top/Article/details/gtyrjrxfpa.html

TS:   d.toISOString()
来源：http://dali.birdmap.top/Article/details/gtqjwdlfeu.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdpxwskyi.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.quarkkingdee.top/Article/details/gtslewvptk.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.nanxinkj.top/Article/details/gtbdblzker.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.xziqi.cn/Article/details/gtjxcuqhvz.html

[J03] 字符串解析为日期
来源：http://dali.cdnleiting.top/Article/details/gtdgwvcmfu.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.ybcxt.top/Article/details/gtpzvpocpf.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.andypj.xyz/Article/details/gtibmksivh.html

JS:   new Date("2024-01-02")
来源：http://dali.zhengqikj.top/Article/details/gtjkfvhdqz.html

TS:   new Date("2024-01-02")
来源：http://dali.fzhhl.top/Article/details/gtfntuzedj.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnxhyaxfn.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.yanxiufei.cn/Article/details/gtsqonlgaz.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.dashuyun.cn/Article/details/gtltcfclqo.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jianghu66.top/Article/details/gtapkqrfiu.html

[J04] 时间戳与日期互转
来源：http://dali.tian-w.cn/Article/details/gtqtpbxoow.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yuxming.cn/Article/details/gtqnipgvkv.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.cqqwz.cn/Article/details/gttfxvhavh.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.daria6918.cn/Article/details/gtefjagsqh.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.feifeiyinyue.top/Article/details/gtehmmnncr.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.xinyue.icu/Article/details/gtbwcovvgn.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.nanxinkj.top/Article/details/gtlehgmyxz.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.shuidangran.top/Article/details/gtdfdafkdf.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.andypj.xyz/Article/details/gtibecvxhe.html

[J05] 时间加减（加 7 天）
来源：http://dali.hfpthk.cn/Article/details/gtxluccqjt.html

Py:   now + timedelta(days=7)
来源：http://dali.zycfv.cn/Article/details/gtajqokkgn.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.havefunace.top/Article/details/gtwaglfxxj.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ppjwa.cn/Article/details/gtudimsfar.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.smart0.xyz/Article/details/gtzcplmixy.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfquyhrpt.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.316326.xyz/Article/details/gtsnnkzmqa.html

Ruby: Time.now + 7 * 86400
来源：http://dali.ivvv.top/Article/details/gtgchyaytr.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.hammf.cn/Article/details/gtgwvubcpg.html

[J06] 计算两时间之差
来源：http://dali.ivvv.top/Article/details/gteysbyypl.html

Py:   (end - start).total_seconds()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtexuesaeq.html

PHP:  $end->diff($start)->days;
来源：http://dali.jlsjyb.cn/Article/details/gtxrfotjtn.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.haohaochexian.top/Article/details/gtuixferzj.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.ivvv.top/Article/details/gtlzciicli.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zycfv.cn/Article/details/gtjkbyvbni.html

Go:   end.Sub(start).Hours()
来源：http://dali.fengsongda.top/Article/details/gtnxkcmaua.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yueranfly.top/Article/details/gtaqcuvddo.html

C#:   (end - start).TotalSeconds
来源：http://dali.daxiang520.top/Article/details/gtnbifnzia.html

[J07] 比较两个日期
来源：http://dali.hfpthk.cn/Article/details/gtgzcgqezu.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yj202588.top/Article/details/gttuijnpad.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.gzhubu.top/Article/details/gtutmfpvpo.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.vqdsnc.cn/Article/details/gthcenbqcn.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.hnqzz.top/Article/details/gtegajzzby.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.pycfn.com/Article/details/gttpiybonu.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhijiandao.cn/Article/details/gtrpkpcolr.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.shangyingyoupin.top/Article/details/gtslljbpvu.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.gzhubu.top/Article/details/gtrdpisbhv.html

[J08] 提取年月日与星期
来源：http://dali.nwbrower.top/Article/details/gtnqsircpi.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.kuanghao11.cn/Article/details/gtcnaizevm.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.nwbrower.top/Article/details/gtrbxzwlzo.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.daxiang520.top/Article/details/gtuqdgpqrn.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpvxfqkjs.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.ybcxt.top/Article/details/gtyakrhtfz.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.xinyue.icu/Article/details/gtrtkcmwto.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.chenlongwang.top/Article/details/gtiallpqyx.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.aizwys.cn/Article/details/gtktywtonj.html

[J09] 时区处理
来源：http://dali.nanxinkj.top/Article/details/gtaqagihli.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.aibaodan.cn/Article/details/gtodshbgti.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.xuanzx.com/Article/details/gtcbcxioru.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.feifeiyinyue.top/Article/details/gtlbbrbsqn.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yuanzhike.top/Article/details/gtvwnigfjr.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yj20258.top/Article/details/gtngnzuwuw.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yvedp.cn/Article/details/gtsmfkvtmj.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.nanxuanxn.top/Article/details/gtnadwfqzx.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.gzhubu.top/Article/details/gtdhzxenss.html

[J10] 取今天 / 本月第一天
来源：http://dali.yvedp.cn/Article/details/gtmebeluqp.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.shanyushiyangtech.top/Article/details/gttnjiyuws.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.fengsongda.top/Article/details/gtekwponjb.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmtncbxxb.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.aibaodan.cn/Article/details/gtqiwasuvf.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.havefunace.top/Article/details/gttxuokrng.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.havefunace.top/Article/details/gtnyiomdwg.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.dashuyun.cn/Article/details/gtsfbpycdi.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.shangyingyoupin.top/Article/details/gtirlksryx.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqqelheau.html

K. JSON 与序列化
来源：http://dali.hysaishi.cn/Article/details/gtbzevlhyf.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtacscmriz.html

[K01] 对象转 JSON 字符串
来源：http://dali.hnqzz.top/Article/details/gtshiovzgh.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.shangyingyoupin.top/Article/details/gtlneemxmx.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.xinyue.icu/Article/details/gtjjagigsz.html

JS:   JSON.stringify(obj)
来源：http://dali.fzhhl.top/Article/details/gtruaujaxq.html

TS:   JSON.stringify(obj)
来源：http://dali.hammf.cn/Article/details/gthymbopoj.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.ehwqpu.com/Article/details/gtammkejlf.html

Go:   json.Marshal(obj)
来源：http://dali.tian-w.cn/Article/details/gtbbdieaze.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yongpay.top/Article/details/gtiqopinex.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.chenzaomai.com/Article/details/gtvvpdllbz.html

[K02] JSON 字符串转对象
来源：http://dali.chenlongwang.top/Article/details/gtqbrxvokn.html

Py:   json.loads(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtglxvurff.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.zhoulong.xyz/Article/details/gtxadllens.html

JS:   JSON.parse(s)
来源：http://dali.ppjwa.cn/Article/details/gtlfewyqwr.html

TS:   JSON.parse(s)
来源：http://dali.sysykeji.top/Article/details/gtnuzuluhh.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.hnxiangtu.top/Article/details/gtueodxwir.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.shzxlz.cn/Article/details/gtxfbketaf.html

Ruby: JSON.parse(s)
来源：http://dali.aizwys.cn/Article/details/gtaxqtedar.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.chenlongwang.top/Article/details/gtruzfbeah.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.c1oappe.top/Article/details/gtcwzusido.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.cdnleiting.top/Article/details/gtjfdnzwiq.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.fengsongda.top/Article/details/gtqsnosdgh.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yonumen.top/Article/details/gtzwpxeqiz.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.zhoulong.xyz/Article/details/gtzuryfhgt.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.aizwys.cn/Article/details/gtbttivfcf.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.dashuyun.cn/Article/details/gteumnjikp.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.kuanghao11.cn/Article/details/gtvxumcizy.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.yueranfly.top/Article/details/gtwbovegot.html

[K04] 读取 JSON 文件
来源：http://dali.quarkkingdee.top/Article/details/gtrzufywdw.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.xuetiantiany.cn/Article/details/gttlwyovax.html


<!-- 参考信息 -->