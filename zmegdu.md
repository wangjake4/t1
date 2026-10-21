代发 wailian999

PHP:  get_object_vars($obj);
来源：http://dali.zdqjudy.top/Article/details/gtoqvnjazv.html

JS:   Object.entries(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwadfhots.html

TS:   Object.entries(obj)
来源：http://dali.zhixingplan.top/Article/details/gtkbyuiipc.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.xziqi.cn/Article/details/gtekqafesv.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jinqigfzy.top/Article/details/gtrslnkrxy.html

Ruby: obj.instance_variables
来源：http://dali.mhx1999.top/Article/details/gtfhqwzgia.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.svipenyu.cn/Article/details/gtvtazlkti.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtpvrravzc.html

H. 异常与错误处理
来源：http://dali.cqqwz.cn/Article/details/gtrleufoyu.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtkadviatv.html

[H01] try / catch 基础
来源：http://dali.daria6918.cn/Article/details/gtlqjmoojc.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.ehwqpu.com/Article/details/gtpcaixpad.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jlsjyb.cn/Article/details/gtrrbrusak.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hywenlv.cn/Article/details/gtmhvmlszr.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yj20258888.top/Article/details/gtocqutszv.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yueranfly.top/Article/details/gtihgsfnpm.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.cheryme.top/Article/details/gttnctdqhv.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jyoumei.cn/Article/details/gtkfeygudu.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.pengpengdd.cyou/Article/details/gtbvgwucpb.html

[H02] finally / ensure 收尾
来源：http://dali.0kj1m.cn/Article/details/gtoajdigze.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.chenzaomai.com/Article/details/gtcobttjfj.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.316326.xyz/Article/details/gtsyxouhfp.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.dashuyun.cn/Article/details/gthfcexqsu.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.pengpengdd.cyou/Article/details/gtgjclnyqp.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.guannengcc.top/Article/details/gtkqwasvck.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.xziqi.cn/Article/details/gttaetahhc.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.nanxinkj.top/Article/details/gtyhbxxzwh.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.meibo888.top/Article/details/gtqpfaghrv.html

[H03] 主动抛出异常
来源：http://dali.iojbl.cn/Article/details/gtvnojajcb.html

Py:   raise ValueError("错误信息")
来源：http://dali.mhx1999.top/Article/details/gtfxkmqyep.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhengqikj.top/Article/details/gtswbtvung.html

JS:   throw new Error("错误信息");
来源：http://dali.cucudq.cn/Article/details/gtlbpvkqdw.html

TS:   throw new Error("错误信息");
来源：http://dali.nwbrower.top/Article/details/gtmgfbleyb.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.haohaochexian.top/Article/details/gtshripzux.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.shangyingyoupin.top/Article/details/gturjwehrp.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.9152youxi.cn/Article/details/gtbfdjesua.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.tianlin.xyz/Article/details/gtprhsjyoc.html

[H04] 自定义异常类型
来源：http://dali.havefunace.top/Article/details/gtmihrmxho.html

Py:   class MyError(Exception): pass
来源：http://dali.bjfxy.top/Article/details/gtlvdbslth.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.kuanghao11.cn/Article/details/gtvsifllts.html

JS:   class MyError extends Error {}
来源：http://dali.hnqzz.top/Article/details/gtcvoqavyv.html

TS:   class MyError extends Error {}
来源：http://dali.yj20258.top/Article/details/gticcimicz.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jlsjyb.cn/Article/details/gtfyfvvotr.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwlfwhghe.html

Ruby: class MyError < StandardError; end
来源：http://dali.svipenyu.cn/Article/details/gtjowmarrf.html

C#:   class MyException : Exception {}
来源：http://dali.daxiang520.top/Article/details/gtzxrinbxu.html

[H05] 捕获特定类型
来源：http://dali.zhoulong.xyz/Article/details/gtppwaotxu.html

Py:   except ValueError as e:
来源：http://dali.hfpthk.cn/Article/details/gtmeierefe.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.shanyushiyangtech.top/Article/details/gtactuqoop.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gtcuijpboj.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.wangdashe.top/Article/details/gtyzvjgvrq.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.redwolf501.top/Article/details/gtydcfcakg.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.kuanghao11.cn/Article/details/gtpboyrzfk.html

Ruby: rescue ArgumentError => e
来源：http://dali.hfpthk.cn/Article/details/gtkzcurcnn.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yj20258.top/Article/details/gtqqnbqbcr.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jlsjyb.cn/Article/details/gtfrmuboyv.html

Py:   value = d.get("k") or default
来源：http://dali.gotoacloud.top/Article/details/gtflbrickn.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hnxiangtu.top/Article/details/gtfpmhsjhk.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.feifeiyinyue.top/Article/details/gtcdwdvmex.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hongshengwenyu.top/Article/details/gtyuvlstdq.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yuxming.cn/Article/details/gtyuuthzrh.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.nanxinkj.top/Article/details/gtkyryuopb.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zdqjudy.top/Article/details/gtneloblll.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhoulong.xyz/Article/details/gttgztvacn.html

[H07] 断言
来源：http://dali.chenzaomai.com/Article/details/gtyfjahqcl.html

Py:   assert x > 0, "必须为正"
来源：http://dali.feifeiyinyue.top/Article/details/gtbvyvcetv.html

PHP:  assert($x > 0);
来源：http://dali.birdmap.top/Article/details/gtinpgrggx.html

JS:   console.assert(x > 0);
来源：http://dali.xziqi.cn/Article/details/gtujdifdeo.html

TS:   console.assert(x > 0);
来源：http://dali.tian-w.cn/Article/details/gtoynzapkj.html

Java: assert x > 0 : "必须为正";
来源：http://dali.gotoacloud.top/Article/details/gtwjelqwxt.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.birdmap.top/Article/details/gtokeruzfx.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.shuidangran.top/Article/details/gtnxcgfohk.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yonumen.top/Article/details/gteacvfhsl.html

[H08] 获取错误信息与堆栈
来源：http://dali.redwolf501.top/Article/details/gtifltreew.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.hammf.cn/Article/details/gtkbexmflo.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hnxiangtu.top/Article/details/gtcpxcqpqt.html

JS:   e.message;  e.stack
来源：http://dali.yj20258888.top/Article/details/gtsgyojfxf.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jinqigfzy.top/Article/details/gtqnzanjxk.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.shzxlz.cn/Article/details/gtykefyovf.html

Go:   err.Error()
来源：http://dali.guowangkeji.top/Article/details/gtmkdqojjr.html

Ruby: e.message;  e.backtrace
来源：http://dali.yongpay.top/Article/details/gtmcjbyejx.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jqgufenzy.top/Article/details/gtabchclto.html

[H09] 带错误码的异常
来源：http://dali.cdnleiting.top/Article/details/gtlnzjtuzh.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.ivvv.top/Article/details/gttmxnpios.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.ybcxt.top/Article/details/gtxpojqxhp.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhoulong.xyz/Article/details/gtgvanjahn.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.nanxinkj.top/Article/details/gtebghsjum.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.tanke756.top/Article/details/gtanolainx.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.smart0.xyz/Article/details/gtdizxdxca.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yangfankeji.com/Article/details/gtflowiais.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yj202588.top/Article/details/gtmlixxhps.html

[H10] 资源自动释放
来源：http://dali.nwbrower.top/Article/details/gtuanqmpkd.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.daria6918.cn/Article/details/gtpwxbhhdk.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.xinyue.icu/Article/details/gtcatttzfq.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtilprwhqw.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.birdmap.top/Article/details/gtubeuvrpl.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zycfv.cn/Article/details/gtpirieohe.html

Go:   defer f.Close()
来源：http://dali.yuanzhike.top/Article/details/gtfgkigrzc.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.xziqi.cn/Article/details/gtkaepqywx.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gtjytrkfzq.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtztcsdogc.html

I. 正则表达式
来源：http://dali.nwbrower.top/Article/details/gtjvcbswiz.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtlpmotgma.html

[I01] 判断是否匹配
来源：http://dali.yj20258.top/Article/details/gtfjivpvhy.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.fzhhl.top/Article/details/gtltqoccdf.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yueranfly.top/Article/details/gtuwsbcpcb.html

JS:   /\d+/.test(s)
来源：http://dali.ydzc1.top/Article/details/gtejzladbl.html

TS:   /\d+/.test(s)
来源：http://dali.nanxuanxn.top/Article/details/gtgssdgces.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jianghu66.top/Article/details/gtjmrrotkc.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.gzhubu.top/Article/details/gtxuehttwr.html

Ruby: s.match?(/\d+/)
来源：http://dali.zhengqikj.top/Article/details/gtkfucybwh.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jinqigufen.top/Article/details/gtmimiavnd.html

[I02] 提取所有匹配
来源：http://dali.jlsjyb.cn/Article/details/gtkvelcjpm.html

Py:   re.findall(r"\d+", s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtafcsbxiu.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.hywenlv.cn/Article/details/gtgrzgallg.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.redwolf501.top/Article/details/gtokwmnlzr.html

TS:   s.match(/\d+/g)
来源：http://dali.316326.xyz/Article/details/gtpoifzrct.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.birdmap.top/Article/details/gtbeqvyqjy.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.dashuyun.cn/Article/details/gtycpodvls.html

Ruby: s.scan(/\d+/)
来源：http://dali.yuanzhike.top/Article/details/gtvfbjzsip.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.andypj.xyz/Article/details/gtwkljbvtf.html

[I03] 提取捕获分组
来源：http://dali.redwolf501.top/Article/details/gtyxihbhbj.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.hysaishi.cn/Article/details/gtfjuzaohe.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jianghu66.top/Article/details/gtkaqolzji.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.316326.xyz/Article/details/gtsgxixanx.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yj20258.top/Article/details/gtpheapkjs.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yonumen.top/Article/details/gtzghrcaxk.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jqgufenzy.top/Article/details/gtrvfqeekc.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.meibo888.top/Article/details/gtiwauycvc.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.wangshuangyany.cn/Article/details/gtuagjbvze.html

[I04] 正则替换
来源：http://dali.yangfankeji.com/Article/details/gtpbnubssu.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.andypj.xyz/Article/details/gtmwwddtim.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.daxiang520.top/Article/details/gtilqqtnfe.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.hnxiangtu.top/Article/details/gtyjpvfwhu.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.ydzc1.top/Article/details/gtetmgsblv.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.xziqi.cn/Article/details/gtahcetsli.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.nwbrower.top/Article/details/gtrzmbfamn.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.chenzaomai.com/Article/details/gtlwaopmik.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zdqjudy.top/Article/details/gtyvuvpttk.html

[I05] 按正则拆分
来源：http://dali.yongpay.top/Article/details/gtcfdumjbi.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.hnxiangtu.top/Article/details/gtwxorkljz.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.birdmap.top/Article/details/gtclrpzpqr.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.gogol.net.cn/Article/details/gtcldqeryd.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.jianghu66.top/Article/details/gtxzrljive.html

Java: s.split("\\s*,\\s*")
来源：http://dali.shanyushiyangtech.top/Article/details/gtsxkvllyy.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.wangdashe.top/Article/details/gtrlaovbcu.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.shanyushiyangtech.top/Article/details/gtasspnibc.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.nanxuanxn.top/Article/details/gtgjdsthpf.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.pycfn.com/Article/details/gtmutohwax.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.mhx1999.top/Article/details/gtkadorise.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.shangyingyoupin.top/Article/details/gtmnijzrfn.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.sufxvd.cn/Article/details/gthcvtuleo.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hysaishi.cn/Article/details/gtycsxltac.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.redwolf501.top/Article/details/gtcciyxafj.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.havefunace.top/Article/details/gtwbwjeilh.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.iojbl.cn/Article/details/gtdmfaxhgk.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.tian-w.cn/Article/details/gtrvgoeyif.html

[I07] 忽略大小写与多行模式
来源：http://dali.guannengcc.top/Article/details/gtfvqeuzzn.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.shangyingyoupin.top/Article/details/gtncheeurt.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.svipenyu.cn/Article/details/gtuiqpmfsa.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.ydzc1.top/Article/details/gtsjrcjhgr.html

TS:   /error/gim
来源：http://dali.daria6918.cn/Article/details/gtviqrsxee.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.nwbrower.top/Article/details/gtwgyahyaf.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.daria6918.cn/Article/details/gtnqcdvvqz.html

Ruby: s.scan(/error/i)
来源：http://dali.jinqigufen.top/Article/details/gtedprbhmh.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.shuidangran.top/Article/details/gtupgibptv.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxbgikqsh.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.hnxiangtu.top/Article/details/gtqebndrdb.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.nanxinkj.top/Article/details/gtoznkudto.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.dianchejie.cn/Article/details/gtnxoqsggd.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hongshengwenyu.top/Article/details/gtfxgmsvex.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jinqigufen.top/Article/details/gtiirscpdm.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.zdqjudy.top/Article/details/gtsyawbuvq.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.vqdsnc.cn/Article/details/gtskbpdhez.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.shanyushiyangtech.top/Article/details/gtscsdoqvd.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtzvgccado.html

J. 日期与时间
来源：http://dali.ybcxt.top/Article/details/gtyrdetros.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtmfkbiuxv.html

[J01] 获取当前时间
来源：http://dali.yj20258.top/Article/details/gtfgqjoxdm.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.ppjwa.cn/Article/details/gtvuhvgrpw.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.ybcxt.top/Article/details/gtrngfecfs.html

JS:   new Date();  Date.now()
来源：http://dali.cheryme.top/Article/details/gteitdyxam.html

TS:   new Date();  Date.now()
来源：http://dali.tianlin.xyz/Article/details/gtkuqzvpdu.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.bjfxy.top/Article/details/gtqfygankh.html

Go:   time.Now()
来源：http://dali.sysykeji.top/Article/details/gtxzbdpefj.html

Ruby: Time.now
来源：http://dali.kuanghao11.cn/Article/details/gtjsbuwcgc.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.zhiwuduotai.top/Article/details/gtiecivgbj.html

[J02] 格式化输出
来源：http://dali.fzhhl.top/Article/details/gtjthbycxn.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.wangdashe.top/Article/details/gtlhnzketq.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.dashuyun.cn/Article/details/gtbubrroly.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.c1oappe.top/Article/details/gtbiaqxwax.html

TS:   d.toISOString()
来源：http://dali.pengpengdd.cyou/Article/details/gtfbyavggw.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yj20258888.top/Article/details/gtctmnuvmi.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.cheryme.top/Article/details/gtuhwrwesu.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.hfpthk.cn/Article/details/gtprijzfho.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jinqigufen.top/Article/details/gtxlokhghi.html

[J03] 字符串解析为日期
来源：http://dali.pengpengdd.cyou/Article/details/gtbfzlmcgd.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.pycfn.com/Article/details/gtnarqvzti.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.bjfxy.top/Article/details/gtwxlvjisl.html

JS:   new Date("2024-01-02")
来源：http://dali.fzhhl.top/Article/details/gtxzrhtugu.html

TS:   new Date("2024-01-02")
来源：http://dali.shzxlz.cn/Article/details/gtyvnnvmft.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.smart0.xyz/Article/details/gtrndxgsvr.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.quarkkingdee.top/Article/details/gtzufuiyuj.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.tanke756.top/Article/details/gtcucpzaxc.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.dashuyun.cn/Article/details/gtrskhyjpf.html

[J04] 时间戳与日期互转
来源：http://dali.chenjidiqi.icu/Article/details/gtvqysaueo.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.ppjwa.cn/Article/details/gtdvusyaba.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.xylfe.cn/Article/details/gtsrbuvxax.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.kuanghao11.cn/Article/details/gtwwudinon.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yongpay.top/Article/details/gtbolyzdde.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.xylfe.cn/Article/details/gthetbtytp.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yongpay.top/Article/details/gtybieaqoi.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.kuanghao11.cn/Article/details/gtuplkcdnt.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.sysykeji.top/Article/details/gtxwxbopmv.html

[J05] 时间加减（加 7 天）
来源：http://dali.sweek.top/Article/details/gtcgejgijn.html

Py:   now + timedelta(days=7)
来源：http://dali.xinyue.icu/Article/details/gtlrayrcxu.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.cdnleiting.top/Article/details/gteouqxlqt.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.snrcjt.cn/Article/details/gttbqkpxwp.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.nwbrower.top/Article/details/gtwqcfgjcp.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.dianchejie.cn/Article/details/gtywkkbfyl.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.ybcxt.top/Article/details/gtxwujdldd.html

Ruby: Time.now + 7 * 86400
来源：http://dali.nanxuanxn.top/Article/details/gtioqejvgv.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yuanzhike.top/Article/details/gtuqlbhccr.html

[J06] 计算两时间之差
来源：http://dali.sysykeji.top/Article/details/gtehumcqse.html

Py:   (end - start).total_seconds()
来源：http://dali.wangdashe.top/Article/details/gtytwadhip.html

PHP:  $end->diff($start)->days;
来源：http://dali.c1oappe.top/Article/details/gtlfcfoavo.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.chenjidiqi.icu/Article/details/gtfxyvkvnc.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.quarkkingdee.top/Article/details/gthlsbjacs.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.xylfe.cn/Article/details/gtmiqwtxec.html

Go:   end.Sub(start).Hours()
来源：http://dali.tanke756.top/Article/details/gtiamywfyt.html

Ruby: end - start                 # 返回秒数
来源：http://dali.kuanghao11.cn/Article/details/gtzwaeuqyw.html

C#:   (end - start).TotalSeconds
来源：http://dali.zdqjudy.top/Article/details/gtfhontqtr.html

[J07] 比较两个日期
来源：http://dali.zdqjudy.top/Article/details/gtfergfftf.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.9152youxi.cn/Article/details/gtghabrgmg.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.pengpengdd.cyou/Article/details/gtaqywrfls.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.xziqi.cn/Article/details/gtasmbysrc.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.pycfn.com/Article/details/gtfekuytya.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.svipenyu.cn/Article/details/gtarkixxik.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.birdmap.top/Article/details/gtodhaypbf.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yangfankeji.com/Article/details/gtzuytucxr.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.ppjwa.cn/Article/details/gtunzyppet.html

[J08] 提取年月日与星期
来源：http://dali.hammf.cn/Article/details/gtpafnsraw.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.ppjwa.cn/Article/details/gtzrhaldrv.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiwwpoemh.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.316326.xyz/Article/details/gtmnfenwom.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.tian-w.cn/Article/details/gtrkvcuoko.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.ydzc1.top/Article/details/gtidigdrqu.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.quarkkingdee.top/Article/details/gtjrepkfde.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.andypj.xyz/Article/details/gthunliajb.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zdqjudy.top/Article/details/gtdjgwvhlg.html

[J09] 时区处理
来源：http://dali.yueranfly.top/Article/details/gtwbyqdebm.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.xuanzx.com/Article/details/gtwhotrbhz.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.nwbrower.top/Article/details/gtirgkkwio.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.tian-w.cn/Article/details/gtyxwqwmcs.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.hywenlv.cn/Article/details/gtqybtzlwp.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.yj20258888.top/Article/details/gtloftqdsa.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.smart0.xyz/Article/details/gtlutsqted.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jinqigufen.top/Article/details/gtrcplowxq.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.jianghu66.top/Article/details/gtcnegxvir.html

[J10] 取今天 / 本月第一天
来源：http://dali.snrcjt.cn/Article/details/gtsggbuciq.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.shangyingyoupin.top/Article/details/gtkbkjfvbu.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.hammf.cn/Article/details/gtmljvgseg.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtivrtptvg.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.fzhhl.top/Article/details/gtwxgbaift.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.fengsongda.top/Article/details/gtgedmgpkx.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.dianchejie.cn/Article/details/gtfeuptujk.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.snrcjt.cn/Article/details/gtijhlyqdu.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yj20258.top/Article/details/gthqbelbex.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtixlchtmv.html

K. JSON 与序列化
来源：http://dali.tian-w.cn/Article/details/gtgxcupmid.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtdospjgyh.html

[K01] 对象转 JSON 字符串
来源：http://dali.0kj1m.cn/Article/details/gtjqqlwush.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.feifeiyinyue.top/Article/details/gtazzlyfax.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.cashguo.top/Article/details/gtnsjbznbv.html

JS:   JSON.stringify(obj)
来源：http://dali.nanxinkj.top/Article/details/gtdthmgjoc.html

TS:   JSON.stringify(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gtivkcqtlm.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.hysaishi.cn/Article/details/gtsmvdejtb.html

Go:   json.Marshal(obj)
来源：http://dali.bjfxy.top/Article/details/gtakwonbxz.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jlsjyb.cn/Article/details/gtpkqsjcqg.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.xuanzx.com/Article/details/gtsqbhwecb.html

[K02] JSON 字符串转对象
来源：http://dali.shzxlz.cn/Article/details/gtvwtthmon.html

Py:   json.loads(s)
来源：http://dali.xylfe.cn/Article/details/gtayeifqye.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.yuxming.cn/Article/details/gtqdihxxcj.html

JS:   JSON.parse(s)
来源：http://dali.guowangkeji.top/Article/details/gtfjrdyhpc.html

TS:   JSON.parse(s)
来源：http://dali.ivvv.top/Article/details/gtqusytjxk.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.nanxinkj.top/Article/details/gtfqxkfgib.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.daria6918.cn/Article/details/gtsvbgfvrw.html

Ruby: JSON.parse(s)
来源：http://dali.tianlin.xyz/Article/details/gtwppjzotx.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.xuanzx.com/Article/details/gtzprckybd.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.jiagoushi.top/Article/details/gtaodiocgc.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.birdmap.top/Article/details/gtrnkcntdf.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.hnqzz.top/Article/details/gtlclpubie.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.c1oappe.top/Article/details/gtuabsluki.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.ppjwa.cn/Article/details/gtbxcvqixd.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.daxiang520.top/Article/details/gtbjrfhbxn.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jinqigfzy.top/Article/details/gtvetrmanv.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.snrcjt.cn/Article/details/gtyzqicjbd.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.cqqwz.cn/Article/details/gtqwinxtfq.html

[K04] 读取 JSON 文件
来源：http://dali.jiagoushi.top/Article/details/gtcznraauw.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.aizwys.cn/Article/details/gtrzclcpao.html


<!-- 参考信息 -->