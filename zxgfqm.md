代发 wailian999

Ruby: Color = %i[red green].freeze
来源：http://dali.shuidangran.top/Article/details/gtacfpdzsq.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shanyushiyangtech.top/Article/details/gtosempnhz.html

[G16] 对象转数组 / 字典
来源：http://dali.jianghu66.top/Article/details/gtfitqyfll.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.daxiang520.top/Article/details/gtgjxrhftd.html

PHP:  get_object_vars($obj);
来源：http://dali.aibaodan.cn/Article/details/gtvxbifbvh.html

JS:   Object.entries(obj)
来源：http://dali.zdqjudy.top/Article/details/gthkfccuvm.html

TS:   Object.entries(obj)
来源：http://dali.ppjwa.cn/Article/details/gtzokozlgt.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zdqjudy.top/Article/details/gtofcpwvzm.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.gzhubu.top/Article/details/gtcwqdcpfz.html

Ruby: obj.instance_variables
来源：http://dali.ywan-chungtsiang.top/Article/details/gttywqelpw.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.havefunace.top/Article/details/gtxzhrzgah.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtwiftdgma.html

H. 异常与错误处理
来源：http://dali.jqgufenzy.top/Article/details/gtlarxsdut.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtolueiwim.html

[H01] try / catch 基础
来源：http://dali.chenzaomai.com/Article/details/gtddijxkum.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jlsjyb.cn/Article/details/gtygpeptrc.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.fengsongda.top/Article/details/gtrcvrifql.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gtkmzxcvom.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jqgufenzy.top/Article/details/gtoudwnjlt.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.xylfe.cn/Article/details/gtebvuhwdo.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.xinyue.icu/Article/details/gtiybgamcs.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.hysaishi.cn/Article/details/gtmopogasa.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hfpthk.cn/Article/details/gtfbstftrd.html

[H02] finally / ensure 收尾
来源：http://dali.9152youxi.cn/Article/details/gtbgigancy.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yuanzhike.top/Article/details/gtzuplkdzf.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.wangdashe.top/Article/details/gtqmzflozk.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.shzxlz.cn/Article/details/gtuekambqm.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.cucudq.cn/Article/details/gtmgymxdno.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.tian-w.cn/Article/details/gtzjevbghu.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.quarkkingdee.top/Article/details/gtvjjszeoo.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.sufxvd.cn/Article/details/gtfymhjyoa.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gttyxzhzio.html

[H03] 主动抛出异常
来源：http://dali.hfpthk.cn/Article/details/gtavtbhouz.html

Py:   raise ValueError("错误信息")
来源：http://dali.cashguo.top/Article/details/gtaafezqvc.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zycfv.cn/Article/details/gtohwyegpc.html

JS:   throw new Error("错误信息");
来源：http://dali.jqgufenzy.top/Article/details/gtqtmdwjjb.html

TS:   throw new Error("错误信息");
来源：http://dali.zhiwuduotai.top/Article/details/gtshxpmkjh.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jianghu66.top/Article/details/gtsutmpfof.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.cheryme.top/Article/details/gtpnhdjfwf.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.nanxinkj.top/Article/details/gtyirwmzch.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.cashguo.top/Article/details/gtiyecifsu.html

[H04] 自定义异常类型
来源：http://dali.gzhubu.top/Article/details/gtvljqipdk.html

Py:   class MyError(Exception): pass
来源：http://dali.vqdsnc.cn/Article/details/gtdtemjjrn.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jqgufenzy.top/Article/details/gtmuumpcij.html

JS:   class MyError extends Error {}
来源：http://dali.yuanzhike.top/Article/details/gtandchems.html

TS:   class MyError extends Error {}
来源：http://dali.yvedp.cn/Article/details/gtrnadmhon.html

Java: class MyException extends RuntimeException {}
来源：http://dali.kuanghao11.cn/Article/details/gtszejrqgg.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.iojbl.cn/Article/details/gtdguilkhq.html

Ruby: class MyError < StandardError; end
来源：http://dali.yongpay.top/Article/details/gtfmklmugi.html

C#:   class MyException : Exception {}
来源：http://dali.yj20258.top/Article/details/gtmmgiswae.html

[H05] 捕获特定类型
来源：http://dali.kuanghao11.cn/Article/details/gtzauutval.html

Py:   except ValueError as e:
来源：http://dali.shuidangran.top/Article/details/gtcdygixgs.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.daria6918.cn/Article/details/gtqdpqiupy.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.gzhubu.top/Article/details/gtyvnhpoxb.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.quarkkingdee.top/Article/details/gtsyqyeafn.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jqgufenzy.top/Article/details/gtmdbialew.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zdqjudy.top/Article/details/gtferqhzsb.html

Ruby: rescue ArgumentError => e
来源：http://dali.yvedp.cn/Article/details/gtbordczyj.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.kuanghao11.cn/Article/details/gtzzoozqml.html

[H06] 可选值 / 空值安全访问
来源：http://dali.cucudq.cn/Article/details/gtrypxrfkb.html

Py:   value = d.get("k") or default
来源：http://dali.jyoumei.cn/Article/details/gttuxsraim.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.chenjidiqi.icu/Article/details/gtpdnyshbj.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.gogol.net.cn/Article/details/gtojdhfbsu.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.chenjidiqi.icu/Article/details/gtxtzwrwes.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhoulong.xyz/Article/details/gthiiiwrwl.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.ivvv.top/Article/details/gtokgwlnpn.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jinqigfzy.top/Article/details/gthlxqdzup.html

C#:   obj?.A?.B ?? default
来源：http://dali.ywan-chungtsiang.top/Article/details/gteixcdhor.html

[H07] 断言
来源：http://dali.jinqigfzy.top/Article/details/gtiglaxvwl.html

Py:   assert x > 0, "必须为正"
来源：http://dali.shanyushiyangtech.top/Article/details/gtzzlnwjeq.html

PHP:  assert($x > 0);
来源：http://dali.sufxvd.cn/Article/details/gtjveibpxk.html

JS:   console.assert(x > 0);
来源：http://dali.jianghu66.top/Article/details/gtfjdmuqxp.html

TS:   console.assert(x > 0);
来源：http://dali.gzhubu.top/Article/details/gtodnmqcqb.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yongpay.top/Article/details/gtxeqhrzat.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.gzhubu.top/Article/details/gtqmywwsnd.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhiwuduotai.top/Article/details/gtigyuqirw.html

C#:   Debug.Assert(x > 0);
来源：http://dali.vqdsnc.cn/Article/details/gtypajyrdy.html

[H08] 获取错误信息与堆栈
来源：http://dali.ppjwa.cn/Article/details/gtxsqsqhmk.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.snrcjt.cn/Article/details/gtyghakscl.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.ppjwa.cn/Article/details/gtdirafxud.html

JS:   e.message;  e.stack
来源：http://dali.ywan-chungtsiang.top/Article/details/gtboiuapal.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.hongshengwenyu.top/Article/details/gtkfjzaplp.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.smart0.xyz/Article/details/gtlnelalzq.html

Go:   err.Error()
来源：http://dali.daria6918.cn/Article/details/gtfudcxwes.html

Ruby: e.message;  e.backtrace
来源：http://dali.yueranfly.top/Article/details/gtgvvivfhj.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hywenlv.cn/Article/details/gtqwdxnuol.html

[H09] 带错误码的异常
来源：http://dali.yvedp.cn/Article/details/gtsbppiujf.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.pycfn.com/Article/details/gtmaulsxre.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkvkrhatc.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.quarkkingdee.top/Article/details/gtmjisxxsy.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yuanzhike.top/Article/details/gtuglyhgcu.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhiwuduotai.top/Article/details/gtagshvvxz.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.fzhhl.top/Article/details/gttlgmsler.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yueranfly.top/Article/details/gteexnpzpp.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.tianlin.xyz/Article/details/gtbzmihwks.html

[H10] 资源自动释放
来源：http://dali.zhengqikj.top/Article/details/gtrliakwzo.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jlsjyb.cn/Article/details/gtzzvfgbsi.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.xylfe.cn/Article/details/gtutupgoji.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.havefunace.top/Article/details/gtbiphijnq.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cucudq.cn/Article/details/gtinfreyxp.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.ybcxt.top/Article/details/gtmaadicmc.html

Go:   defer f.Close()
来源：http://dali.daria6918.cn/Article/details/gtgwiegdxq.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zdqjudy.top/Article/details/gtarxxkqqk.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jqgfzy.top/Article/details/gttpzfvrfs.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtvqbhmmns.html

I. 正则表达式
来源：http://dali.zhiwuduotai.top/Article/details/gthpnhpbye.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtqlyjvsha.html

[I01] 判断是否匹配
来源：http://dali.feifeiyinyue.top/Article/details/gtdqdgrycy.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.wangdashe.top/Article/details/gtkfprlmka.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.hfpthk.cn/Article/details/gtkhnbwmhj.html

JS:   /\d+/.test(s)
来源：http://dali.svipenyu.cn/Article/details/gtbixirzkf.html

TS:   /\d+/.test(s)
来源：http://dali.xziqi.cn/Article/details/gtcbducjjs.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.chenlongwang.top/Article/details/gtidpikwmd.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.cheryme.top/Article/details/gtjsgzrmfr.html

Ruby: s.match?(/\d+/)
来源：http://dali.ybcxt.top/Article/details/gtawupcvii.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.xylfe.cn/Article/details/gtlxzzifch.html

[I02] 提取所有匹配
来源：http://dali.hongshengwenyu.top/Article/details/gtxgdmgjhr.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zdqjudy.top/Article/details/gtsgarwcog.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.shzxlz.cn/Article/details/gtalbdfeer.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.guowangkeji.top/Article/details/gtlljkcncb.html

TS:   s.match(/\d+/g)
来源：http://dali.zhongyouzk.top/Article/details/gthwfyfdsb.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yueranfly.top/Article/details/gtxmzejali.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yj202588.top/Article/details/gtfkihntxg.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhongyouzk.top/Article/details/gtrdyqijrk.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.nwbrower.top/Article/details/gtqcyaymqn.html

[I03] 提取捕获分组
来源：http://dali.yvedp.cn/Article/details/gtrltzrkzi.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.xylfe.cn/Article/details/gtmnuljwgk.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hfpthk.cn/Article/details/gtjqztvxwz.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.c1oappe.top/Article/details/gtzfhccheg.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.nanxinkj.top/Article/details/gtupasjnwf.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jlsjyb.cn/Article/details/gtuwoxgmfz.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yj202588.top/Article/details/gtwbsiabzu.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.chenjidiqi.icu/Article/details/gtkbhmypqr.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.gogol.net.cn/Article/details/gttogkrxpm.html

[I04] 正则替换
来源：http://dali.chenlongwang.top/Article/details/gtcqcuyvef.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.meibo888.top/Article/details/gtsehuyvtd.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.sweek.top/Article/details/gtldmebftn.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.xziqi.cn/Article/details/gtxflrkcon.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuseioxzm.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.daxiang520.top/Article/details/gtbbblstrj.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.xziqi.cn/Article/details/gtkxnthczz.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.gaohongyu789.top/Article/details/gtcdewigob.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jqgfzy.top/Article/details/gtdcibrfhz.html

[I05] 按正则拆分
来源：http://dali.yj202588.top/Article/details/gthfpghdxn.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhongyouzk.top/Article/details/gtloqimqkl.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.cheryme.top/Article/details/gttisclcfp.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhixingplan.top/Article/details/gtqvlcpmhq.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.kuanghao11.cn/Article/details/gtlehkcwym.html

Java: s.split("\\s*,\\s*")
来源：http://dali.tanke756.top/Article/details/gtgeuvbway.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhijiandao.cn/Article/details/gtqupnbgck.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.xinyue.icu/Article/details/gtdqymimbv.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.feifeiyinyue.top/Article/details/gtkixdelbs.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.quarkkingdee.top/Article/details/gtonvpzxfp.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.ppjwa.cn/Article/details/gtkynvkabl.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtppceopuj.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.316326.xyz/Article/details/gtohgcoere.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jqgfzy.top/Article/details/gtjqvolfst.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgnjadjmb.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.hywenlv.cn/Article/details/gtlegupaic.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.yuxming.cn/Article/details/gtghojahtr.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.pengpengdd.cyou/Article/details/gtirawxhkt.html

[I07] 忽略大小写与多行模式
来源：http://dali.hysaishi.cn/Article/details/gtyjkgurlx.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.zhengqikj.top/Article/details/gtjmddzkbu.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.snrcjt.cn/Article/details/gtnvmrwxqb.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.haohaochexian.top/Article/details/gtlbanmdij.html

TS:   /error/gim
来源：http://dali.quarkkingdee.top/Article/details/gthfngidog.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.zhiwuduotai.top/Article/details/gthltncjod.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.sxryk.cn/Article/details/gtxawxpeks.html

Ruby: s.scan(/error/i)
来源：http://dali.ehwqpu.com/Article/details/gtucstsyon.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.xuanzx.com/Article/details/gtrllfdhfu.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.wangdashe.top/Article/details/gtullkflhi.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.cdnleiting.top/Article/details/gtskxlmjgg.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhongyouzk.top/Article/details/gtzaqacoic.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhongyouzk.top/Article/details/gtogoyxcoe.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ehwqpu.com/Article/details/gtyzezmsvr.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.dashuyun.cn/Article/details/gteyznrjym.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.ppjwa.cn/Article/details/gtrkbmnqsl.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jiagoushi.top/Article/details/gthbgxmlis.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.hywenlv.cn/Article/details/gtmfvdodst.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtnoblzwzw.html

J. 日期与时间
来源：http://dali.gotoacloud.top/Article/details/gtjqgsykhs.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtjorafdor.html

[J01] 获取当前时间
来源：http://dali.hywenlv.cn/Article/details/gtjvayvylx.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.haohaochexian.top/Article/details/gtdrmhuigo.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrcnxbsvj.html

JS:   new Date();  Date.now()
来源：http://dali.hywenlv.cn/Article/details/gtkesnwfrm.html

TS:   new Date();  Date.now()
来源：http://dali.dashuyun.cn/Article/details/gtydtxxabt.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzuhoftld.html

Go:   time.Now()
来源：http://dali.hongshengwenyu.top/Article/details/gtxmvsdzid.html

Ruby: Time.now
来源：http://dali.aibaodan.cn/Article/details/gtrcpegchm.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.bjfxy.top/Article/details/gtotsywsao.html

[J02] 格式化输出
来源：http://dali.smart0.xyz/Article/details/gtqjcueqkt.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yuanzhike.top/Article/details/gtcsfkasqx.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.c1oappe.top/Article/details/gtkagahkdf.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.redwolf501.top/Article/details/gtompypkal.html

TS:   d.toISOString()
来源：http://dali.yuxming.cn/Article/details/gtvhldqayz.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.gaohongyu789.top/Article/details/gtsmwollrx.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.havefunace.top/Article/details/gtjlqknjan.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gzhubu.top/Article/details/gtlryoxqhn.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.sxryk.cn/Article/details/gtwrvomkqq.html

[J03] 字符串解析为日期
来源：http://dali.xylfe.cn/Article/details/gtwnifjkpy.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.chenlongwang.top/Article/details/gtzfvuvikb.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zhoulong.xyz/Article/details/gtixpetrci.html

JS:   new Date("2024-01-02")
来源：http://dali.cucudq.cn/Article/details/gtdmooooie.html

TS:   new Date("2024-01-02")
来源：http://dali.jqgufenzy.top/Article/details/gtizetkodo.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.birdmap.top/Article/details/gtvfglyfzl.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.hfpthk.cn/Article/details/gtlfwtwlng.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdrlxjfsb.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.meibo888.top/Article/details/gthgqweywf.html

[J04] 时间戳与日期互转
来源：http://dali.jqgfzy.top/Article/details/gtvsedaxlv.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.nwbrower.top/Article/details/gtfruyjogd.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.yuxming.cn/Article/details/gthcmejjnb.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yongpay.top/Article/details/gtelcsagap.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.daxiang520.top/Article/details/gtwbcgolpu.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.316326.xyz/Article/details/gttseezmmi.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.smart0.xyz/Article/details/gtzdpoxopw.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.yueranfly.top/Article/details/gtykfvwlxa.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zdqjudy.top/Article/details/gtmjqseizo.html

[J05] 时间加减（加 7 天）
来源：http://dali.sufxvd.cn/Article/details/gtuudstbmy.html

Py:   now + timedelta(days=7)
来源：http://dali.cheryme.top/Article/details/gtpesjwzbn.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.sweek.top/Article/details/gtoqotqnhc.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.tanke756.top/Article/details/gtoztmhjwt.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jlsjyb.cn/Article/details/gtlxkagrsz.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.meibo888.top/Article/details/gtjqpraeuf.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.sysykeji.top/Article/details/gtdkvgmcgl.html

Ruby: Time.now + 7 * 86400
来源：http://dali.ppjwa.cn/Article/details/gtmzputoyk.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.zhengqikj.top/Article/details/gtflbwzsxt.html

[J06] 计算两时间之差
来源：http://dali.dashuyun.cn/Article/details/gtmleldrtf.html

Py:   (end - start).total_seconds()
来源：http://dali.smart0.xyz/Article/details/gtsmlegmfw.html

PHP:  $end->diff($start)->days;
来源：http://dali.zhoulong.xyz/Article/details/gtcpxhogmc.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yueranfly.top/Article/details/gtcgjprmop.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbxueuymj.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.nwbrower.top/Article/details/gtxuwejlre.html

Go:   end.Sub(start).Hours()
来源：http://dali.zhoulong.xyz/Article/details/gtnqwdgony.html

Ruby: end - start                 # 返回秒数
来源：http://dali.shanyushiyangtech.top/Article/details/gtewgcqdeu.html

C#:   (end - start).TotalSeconds
来源：http://dali.xinyue.icu/Article/details/gtduydkqnf.html

[J07] 比较两个日期
来源：http://dali.jinqigfzy.top/Article/details/gtgpkfopma.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.cucudq.cn/Article/details/gtoqnpqtav.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhijiandao.cn/Article/details/gtgfsbvlel.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.sufxvd.cn/Article/details/gtwohqzuvt.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.gotoacloud.top/Article/details/gtscjbpane.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.aizwys.cn/Article/details/gtqwseypka.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yj20258888.top/Article/details/gtsuvwyrni.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.ywan-chungtsiang.top/Article/details/gtykmaumdp.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.quarkkingdee.top/Article/details/gtprduhikl.html

[J08] 提取年月日与星期
来源：http://dali.0kj1m.cn/Article/details/gtsrritvon.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.nwbrower.top/Article/details/gtqnuccpnb.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zdqjudy.top/Article/details/gttrgzebvb.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.cucudq.cn/Article/details/gtvryojczl.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yj202588.top/Article/details/gthxctulfn.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.sysykeji.top/Article/details/gtgwsebyxg.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.jianghu66.top/Article/details/gtooemazta.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.sysykeji.top/Article/details/gtoduhthgz.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsunonndi.html

[J09] 时区处理
来源：http://dali.jiagoushi.top/Article/details/gtwjvosoak.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.wangshuangyany.cn/Article/details/gtwxyssrqq.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.sysykeji.top/Article/details/gteinrzmts.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gogol.net.cn/Article/details/gtburpqkhs.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.jyoumei.cn/Article/details/gtisgsamoi.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.9152youxi.cn/Article/details/gtoxplfuhi.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.guannengcc.top/Article/details/gtopfyrhaq.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhengqikj.top/Article/details/gticulpgxf.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.cheryme.top/Article/details/gtyjopemuo.html

[J10] 取今天 / 本月第一天
来源：http://dali.haohaochexian.top/Article/details/gtiubqcokk.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jinqigfzy.top/Article/details/gtonxgwyjs.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.birdmap.top/Article/details/gtvqjftqsg.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.guannengcc.top/Article/details/gtauvhnbrz.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.shuidangran.top/Article/details/gtqxdepawq.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.dianchejie.cn/Article/details/gtydmkpzog.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.guannengcc.top/Article/details/gtubnmctwd.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jinqigufen.top/Article/details/gtuyfuyzsg.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.guowangkeji.top/Article/details/gtkxizwjrn.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtmztqnkry.html

K. JSON 与序列化
来源：http://dali.zhoulong.xyz/Article/details/gtxyonlymb.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfvdydaan.html

[K01] 对象转 JSON 字符串
来源：http://dali.0kj1m.cn/Article/details/gtywfqewyn.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.meibo888.top/Article/details/gtaeoprqnl.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.xinyue.icu/Article/details/gtwszxcmee.html

JS:   JSON.stringify(obj)
来源：http://dali.guannengcc.top/Article/details/gtlavjfyzh.html

TS:   JSON.stringify(obj)
来源：http://dali.vqdsnc.cn/Article/details/gtpoqrxwxd.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zycfv.cn/Article/details/gtbxessuhp.html

Go:   json.Marshal(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtrwyfuxue.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.zycfv.cn/Article/details/gtsstocdub.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.ybcxt.top/Article/details/gtzpsopjuy.html

[K02] JSON 字符串转对象
来源：http://dali.jyoumei.cn/Article/details/gtyhpiuovn.html

Py:   json.loads(s)
来源：http://dali.dianchejie.cn/Article/details/gtsnrkkpbl.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.ppjwa.cn/Article/details/gtxcqiuvca.html

JS:   JSON.parse(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxqcaxstr.html

TS:   JSON.parse(s)
来源：http://dali.sweek.top/Article/details/gtjaaiumah.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.0kj1m.cn/Article/details/gtkrcrkvds.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.zhengqikj.top/Article/details/gtvqpjjixe.html

Ruby: JSON.parse(s)
来源：http://dali.cqqwz.cn/Article/details/gtektidqcr.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.xylfe.cn/Article/details/gttlydszht.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yj20258.top/Article/details/gtdibavvie.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yj20258.top/Article/details/gtrxskroes.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.fzhhl.top/Article/details/gtpjdmtiyp.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.chenlongwang.top/Article/details/gtxmjsspep.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.ppjwa.cn/Article/details/gtflkkxlfm.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtdbsneyff.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.jqgfzy.top/Article/details/gtidvfmrdl.html


<!-- 参考信息 -->