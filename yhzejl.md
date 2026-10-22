代发 wailian999

[G14] 数据类 / record
来源：http://dali.guowangkeji.top/Article/details/gtgbxffxfu.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.shzxlz.cn/Article/details/gtawclmfqm.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjzohrhvt.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.redwolf501.top/Article/details/gtncsqeawt.html

TS:   type User = { name: string; age: number };
来源：http://dali.ydzc1.top/Article/details/gtqwnhvpct.html

Java: record User(String name, int age) {}
来源：http://dali.daria6918.cn/Article/details/gtulfbyooj.html

Go:   type User struct { Name string; Age int }
来源：http://dali.cheryme.top/Article/details/gtwblxgoaz.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jinqigfzy.top/Article/details/gtysakegfa.html

C#:   record User(string Name, int Age);
来源：http://dali.hnqzz.top/Article/details/gtxqarmzcr.html

[G15] 枚举
来源：http://dali.nanxuanxn.top/Article/details/gtlrzdehjr.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.nanxuanxn.top/Article/details/gtpmutzxdk.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.aibaodan.cn/Article/details/gtuglnjojq.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jianghu66.top/Article/details/gtfddgceyf.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.0kj1m.cn/Article/details/gthvhbjtxe.html

Java: enum Color { RED, GREEN }
来源：http://dali.redwolf501.top/Article/details/gtxepmmwgo.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.pycfn.com/Article/details/gtfqhpccfi.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jqgufenzy.top/Article/details/gtwwyocirr.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xuetiantiany.cn/Article/details/gtybdphxct.html

[G16] 对象转数组 / 字典
来源：http://dali.ybcxt.top/Article/details/gtmpkntmib.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.ydzc1.top/Article/details/gtjeluadti.html

PHP:  get_object_vars($obj);
来源：http://dali.shanyushiyangtech.top/Article/details/gtloopdbps.html

JS:   Object.entries(obj)
来源：http://dali.meibo888.top/Article/details/gtwkqjfhrw.html

TS:   Object.entries(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtpfrbjerx.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.meibo888.top/Article/details/gttgmcevyc.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.shangyingyoupin.top/Article/details/gtpqoruhsg.html

Ruby: obj.instance_variables
来源：http://dali.fzhhl.top/Article/details/gtgmwgpwdd.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.tanke756.top/Article/details/gturrvzpqz.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtbeovcywl.html

H. 异常与错误处理
来源：http://dali.guannengcc.top/Article/details/gtnbilrzxj.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwaqzdvxq.html

[H01] try / catch 基础
来源：http://dali.redwolf501.top/Article/details/gtiqmuuiaj.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jyoumei.cn/Article/details/gtiyhyxcus.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.hfpthk.cn/Article/details/gthdvkxvbi.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.chenzaomai.com/Article/details/gtvksolbwd.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.ydzc1.top/Article/details/gttmvwyrcd.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.ehwqpu.com/Article/details/gtgjgnfxfx.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yanxiufei.cn/Article/details/gtrvcuzigx.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jinqigufen.top/Article/details/gtgpjiavdg.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.sufxvd.cn/Article/details/gtpbeqswhg.html

[H02] finally / ensure 收尾
来源：http://dali.meibo888.top/Article/details/gtudfhrzln.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.xziqi.cn/Article/details/gttdeiqiqc.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.chenzaomai.com/Article/details/gtzclmgkoz.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.smart0.xyz/Article/details/gtynbxmbjf.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhixingplan.top/Article/details/gtesqroqin.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.meibo888.top/Article/details/gtdwomjjok.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.feifeiyinyue.top/Article/details/gtwwvoeeek.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.cucudq.cn/Article/details/gtrchmbqup.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.cheryme.top/Article/details/gtzqnkhwkk.html

[H03] 主动抛出异常
来源：http://dali.hongshengwenyu.top/Article/details/gtsdutmuti.html

Py:   raise ValueError("错误信息")
来源：http://dali.c1oappe.top/Article/details/gtmwefegez.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.chenlongwang.top/Article/details/gtknqhqslf.html

JS:   throw new Error("错误信息");
来源：http://dali.cqqwz.cn/Article/details/gtscksqxyk.html

TS:   throw new Error("错误信息");
来源：http://dali.zycfv.cn/Article/details/gtvqxhdbgo.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.9152youxi.cn/Article/details/gtbabibobm.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.smart0.xyz/Article/details/gtfokdccor.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.wangdashe.top/Article/details/gtmqrcziat.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.c1oappe.top/Article/details/gtjjxjqjat.html

[H04] 自定义异常类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlepzfssi.html

Py:   class MyError(Exception): pass
来源：http://dali.iojbl.cn/Article/details/gtdgqmtlvz.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhongyouzk.top/Article/details/gtwsuxiaxu.html

JS:   class MyError extends Error {}
来源：http://dali.nanxuanxn.top/Article/details/gtkthbtotz.html

TS:   class MyError extends Error {}
来源：http://dali.wangdashe.top/Article/details/gtkucklpxe.html

Java: class MyException extends RuntimeException {}
来源：http://dali.snrcjt.cn/Article/details/gtrjhkpdvu.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.daria6918.cn/Article/details/gtyxherxio.html

Ruby: class MyError < StandardError; end
来源：http://dali.chenzaomai.com/Article/details/gtfdjsiuzd.html

C#:   class MyException : Exception {}
来源：http://dali.sxryk.cn/Article/details/gtwytkesaw.html

[H05] 捕获特定类型
来源：http://dali.316326.xyz/Article/details/gtzxpqalch.html

Py:   except ValueError as e:
来源：http://dali.meibo888.top/Article/details/gtfixawlxk.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.0kj1m.cn/Article/details/gtmynncxhe.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yj20258888.top/Article/details/gtfvqfgwav.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.xziqi.cn/Article/details/gtmvpcskol.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gteunakaqz.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yj202588.top/Article/details/gtljxawbnp.html

Ruby: rescue ArgumentError => e
来源：http://dali.jqgfzy.top/Article/details/gtwemscoxr.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jlsjyb.cn/Article/details/gttlyxfqbj.html

[H06] 可选值 / 空值安全访问
来源：http://dali.fzhhl.top/Article/details/gtyivijtch.html

Py:   value = d.get("k") or default
来源：http://dali.jqgufenzy.top/Article/details/gtxmiisvqq.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.haohaochexian.top/Article/details/gtxttetpof.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.sysykeji.top/Article/details/gtyyhdqbwg.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.cheryme.top/Article/details/gtydlvagcx.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yj20258.top/Article/details/gtpnbpkzav.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.gogol.net.cn/Article/details/gtagggidnx.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhiwuduotai.top/Article/details/gtochsqrlo.html

C#:   obj?.A?.B ?? default
来源：http://dali.yanxiufei.cn/Article/details/gtkvzsjfxt.html

[H07] 断言
来源：http://dali.jianghu66.top/Article/details/gtuhyrvzxk.html

Py:   assert x > 0, "必须为正"
来源：http://dali.xziqi.cn/Article/details/gteaybfasm.html

PHP:  assert($x > 0);
来源：http://dali.dashuyun.cn/Article/details/gtjhiseopb.html

JS:   console.assert(x > 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpbhtzfvz.html

TS:   console.assert(x > 0);
来源：http://dali.pycfn.com/Article/details/gtlgyjrzca.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yj20258888.top/Article/details/gtgfmxsjcd.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.0kj1m.cn/Article/details/gtohhujhcc.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.nanxuanxn.top/Article/details/gtupgtwoig.html

C#:   Debug.Assert(x > 0);
来源：http://dali.xziqi.cn/Article/details/gtzgckbdia.html

[H08] 获取错误信息与堆栈
来源：http://dali.0kj1m.cn/Article/details/gtjzcbghup.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yonumen.top/Article/details/gtzjuazbmj.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hammf.cn/Article/details/gtyrwqjkjq.html

JS:   e.message;  e.stack
来源：http://dali.dianchejie.cn/Article/details/gtseauuhmy.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.sweek.top/Article/details/gtswmkwnun.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhongyouzk.top/Article/details/gtpsglnpzc.html

Go:   err.Error()
来源：http://dali.smart0.xyz/Article/details/gtmftkoute.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhongyouzk.top/Article/details/gtaxtbhkmy.html

C#:   e.Message;  e.StackTrace
来源：http://dali.cucudq.cn/Article/details/gtsigucrog.html

[H09] 带错误码的异常
来源：http://dali.cdnleiting.top/Article/details/gtemrbvmef.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yvedp.cn/Article/details/gtbmngezpq.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.nwbrower.top/Article/details/gtoxijdmfh.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.shuidangran.top/Article/details/gtyhexlitu.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.havefunace.top/Article/details/gtdznnsetq.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jqgufenzy.top/Article/details/gtigdtvexa.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.xuanzx.com/Article/details/gtfztsylpr.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jinqigfzy.top/Article/details/gtiuvxtrsx.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.wangshuangyany.cn/Article/details/gtiwbsgtgf.html

[H10] 资源自动释放
来源：http://dali.hfpthk.cn/Article/details/gtcgqwkull.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.snrcjt.cn/Article/details/gteuqkimnw.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhongyouzk.top/Article/details/gtjxhmkpdr.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.daria6918.cn/Article/details/gtypbxpssh.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhoulong.xyz/Article/details/gtwfxzyzkm.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yanxiufei.cn/Article/details/gtgrdipvee.html

Go:   defer f.Close()
来源：http://dali.dianchejie.cn/Article/details/gtscrdkdbt.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hysaishi.cn/Article/details/gtiuorgodq.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gtizpsmtpe.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtqyopylrq.html

I. 正则表达式
来源：http://dali.ybcxt.top/Article/details/gtkmdqwvln.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtdjpqqciz.html

[I01] 判断是否匹配
来源：http://dali.pycfn.com/Article/details/gtwbrzprgk.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yj20258.top/Article/details/gtocacscmn.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.ivvv.top/Article/details/gtgeaaddah.html

JS:   /\d+/.test(s)
来源：http://dali.chenzaomai.com/Article/details/gtyuobzpyf.html

TS:   /\d+/.test(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjidbvnmk.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.gaohongyu789.top/Article/details/gtldbalcoz.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.gogol.net.cn/Article/details/gtaowfegiy.html

Ruby: s.match?(/\d+/)
来源：http://dali.hywenlv.cn/Article/details/gtfhydhjbh.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.havefunace.top/Article/details/gtywivrkrv.html

[I02] 提取所有匹配
来源：http://dali.mhx1999.top/Article/details/gtexwesfvs.html

Py:   re.findall(r"\d+", s)
来源：http://dali.sysykeji.top/Article/details/gtrpilwjyj.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.shanyushiyangtech.top/Article/details/gtvnfqtpjg.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.gogol.net.cn/Article/details/gtizwqgdsc.html

TS:   s.match(/\d+/g)
来源：http://dali.redwolf501.top/Article/details/gtkrdxunfk.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.gzhubu.top/Article/details/gtzlsziytg.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jlsjyb.cn/Article/details/gtbpewulbe.html

Ruby: s.scan(/\d+/)
来源：http://dali.ybcxt.top/Article/details/gtovuluqlm.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.sufxvd.cn/Article/details/gttkchcosx.html

[I03] 提取捕获分组
来源：http://dali.quarkkingdee.top/Article/details/gtbdziaxnc.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.9152youxi.cn/Article/details/gtgnntphrb.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.cucudq.cn/Article/details/gtwmmxyeoy.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yj202588.top/Article/details/gtqyzoezdh.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.daria6918.cn/Article/details/gtgxnzurna.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yj20258.top/Article/details/gtbazsvwnw.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.bjfxy.top/Article/details/gtntlanhaf.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yonumen.top/Article/details/gtbsqryhcl.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.pengpengdd.cyou/Article/details/gtnpsuxulw.html

[I04] 正则替换
来源：http://dali.nanxuanxn.top/Article/details/gtrzzwnqxw.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.shuidangran.top/Article/details/gtfpjwoklv.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jinqigufen.top/Article/details/gtczgevjlt.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.haohaochexian.top/Article/details/gtjoynpglx.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.aizwys.cn/Article/details/gtrdgwfojp.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhoulong.xyz/Article/details/gtruovbjmb.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.sweek.top/Article/details/gtlutpvsaq.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhongyouzk.top/Article/details/gtblhztoxz.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtujymiiap.html

[I05] 按正则拆分
来源：http://dali.guannengcc.top/Article/details/gtnufudbfs.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yuanzhike.top/Article/details/gthpbcfurq.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.kuanghao11.cn/Article/details/gtbekchtzr.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.dashuyun.cn/Article/details/gthabtgxhr.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.hammf.cn/Article/details/gtijkuetuf.html

Java: s.split("\\s*,\\s*")
来源：http://dali.ivvv.top/Article/details/gtovglctht.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zycfv.cn/Article/details/gtmzflkdoc.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yueranfly.top/Article/details/gtnikpurda.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.kuanghao11.cn/Article/details/gtnfydknyc.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yuxming.cn/Article/details/gtckgptogy.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.zdqjudy.top/Article/details/gtjxlaqotd.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.zhixingplan.top/Article/details/gtxdizxfcg.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.gzhubu.top/Article/details/gtjegfbnyx.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yj20258888.top/Article/details/gtnbppigsj.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.sysykeji.top/Article/details/gttrmmptcz.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.9152youxi.cn/Article/details/gtqipumgic.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.kuanghao11.cn/Article/details/gtuszydymm.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.316326.xyz/Article/details/gthmkfapzj.html

[I07] 忽略大小写与多行模式
来源：http://dali.cashguo.top/Article/details/gtscfgbqry.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.shangyingyoupin.top/Article/details/gtqnosdbtn.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.tanke756.top/Article/details/gtvuhwlxos.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jiagoushi.top/Article/details/gtkgfboocw.html

TS:   /error/gim
来源：http://dali.chenzaomai.com/Article/details/gtabmcwhby.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.daxiang520.top/Article/details/gtkwwegwug.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yongpay.top/Article/details/gtjzcpnnve.html

Ruby: s.scan(/error/i)
来源：http://dali.haohaochexian.top/Article/details/gtauxcbyok.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.vqdsnc.cn/Article/details/gtklsyoncj.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.vqdsnc.cn/Article/details/gthyrrygob.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.pycfn.com/Article/details/gtidlbmldt.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.nanxinkj.top/Article/details/gtdkyfjgnp.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.chenzaomai.com/Article/details/gtobbalsdf.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrrhvdgbx.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jiagoushi.top/Article/details/gtpzpgrszc.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.tianlin.xyz/Article/details/gtpleaqmlp.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.ybcxt.top/Article/details/gtaxvnmhtr.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.jlsjyb.cn/Article/details/gtuvjgcdzm.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtemmyiykb.html

J. 日期与时间
来源：http://dali.yangfankeji.com/Article/details/gtyjdrhcum.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gttmrzohgx.html

[J01] 获取当前时间
来源：http://dali.nanxinkj.top/Article/details/gtgrdxljbc.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.jianghu66.top/Article/details/gtbomiqril.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.shangyingyoupin.top/Article/details/gtpnmkvzso.html

JS:   new Date();  Date.now()
来源：http://dali.hywenlv.cn/Article/details/gtictfwhjh.html

TS:   new Date();  Date.now()
来源：http://dali.birdmap.top/Article/details/gtukaosyac.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.meibo888.top/Article/details/gttrdrlmgk.html

Go:   time.Now()
来源：http://dali.dashuyun.cn/Article/details/gtfipopgfy.html

Ruby: Time.now
来源：http://dali.ivvv.top/Article/details/gttyhilcko.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.xinyue.icu/Article/details/gtmnfsynsd.html

[J02] 格式化输出
来源：http://dali.ivvv.top/Article/details/gtfwqpeocw.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.zdqjudy.top/Article/details/gtoxhctggu.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.ppjwa.cn/Article/details/gtmacklxhk.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmcereuqe.html

TS:   d.toISOString()
来源：http://dali.xuetiantiany.cn/Article/details/gteghglxmf.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.dashuyun.cn/Article/details/gtxxlqhxhk.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.ydzc1.top/Article/details/gtbsjqhofg.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yongpay.top/Article/details/gtouimnjbh.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.hnqzz.top/Article/details/gtwbvwogat.html

[J03] 字符串解析为日期
来源：http://dali.ybcxt.top/Article/details/gtexbkzwgi.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.cdnleiting.top/Article/details/gtthgodnpp.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.sxryk.cn/Article/details/gtgrhwzdrl.html

JS:   new Date("2024-01-02")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrbbovodx.html

TS:   new Date("2024-01-02")
来源：http://dali.pengpengdd.cyou/Article/details/gtrkohlajf.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.vqdsnc.cn/Article/details/gttxbulvhp.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.nanxinkj.top/Article/details/gtrpeztiqr.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.tanke756.top/Article/details/gtpqnrkemk.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.yonumen.top/Article/details/gtbhcostwu.html

[J04] 时间戳与日期互转
来源：http://dali.hnxiangtu.top/Article/details/gtobomjsxv.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.shuidangran.top/Article/details/gtkeapqlnv.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.xuetiantiany.cn/Article/details/gtqgycoswx.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yvedp.cn/Article/details/gtvpqkbbfz.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.chenjidiqi.icu/Article/details/gtxjghafzz.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthqhgrgro.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.chenzaomai.com/Article/details/gtlkskebxz.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.sysykeji.top/Article/details/gtvhycwetz.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.yangfankeji.com/Article/details/gthhaiptyt.html

[J05] 时间加减（加 7 天）
来源：http://dali.smart0.xyz/Article/details/gttetoefob.html

Py:   now + timedelta(days=7)
来源：http://dali.iojbl.cn/Article/details/gtllsuvakd.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.wangshuangyany.cn/Article/details/gtneeycmsj.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.dianchejie.cn/Article/details/gtumpjuuhm.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.nanxinkj.top/Article/details/gtpodebybp.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.ppjwa.cn/Article/details/gtbhqmskic.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.nwbrower.top/Article/details/gtdagchawv.html

Ruby: Time.now + 7 * 86400
来源：http://dali.sxryk.cn/Article/details/gtjkawawto.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.xylfe.cn/Article/details/gtrgngdccs.html

[J06] 计算两时间之差
来源：http://dali.hywenlv.cn/Article/details/gtcdgcdjmb.html

Py:   (end - start).total_seconds()
来源：http://dali.zdqjudy.top/Article/details/gtjqodcoxk.html

PHP:  $end->diff($start)->days;
来源：http://dali.sysykeji.top/Article/details/gtwqvwlkbb.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.xylfe.cn/Article/details/gtszfmcjix.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.shangyingyoupin.top/Article/details/gtmrfnpuoo.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.birdmap.top/Article/details/gtvexvusmp.html

Go:   end.Sub(start).Hours()
来源：http://dali.yuanzhike.top/Article/details/gtvsmwrgsb.html

Ruby: end - start                 # 返回秒数
来源：http://dali.yonumen.top/Article/details/gtwfcdrbbc.html

C#:   (end - start).TotalSeconds
来源：http://dali.jinghuilouyu.cn/Article/details/gttarqdryd.html

[J07] 比较两个日期
来源：http://dali.gogol.net.cn/Article/details/gtajzupvxt.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.fzhhl.top/Article/details/gtjoocdvsd.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.316326.xyz/Article/details/gtakqypldw.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.guowangkeji.top/Article/details/gtaehztcgv.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.daxiang520.top/Article/details/gtbkceidbq.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.xuetiantiany.cn/Article/details/gttlhgakta.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.fengsongda.top/Article/details/gtkwshklsw.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.hongshengwenyu.top/Article/details/gtxzljiwfy.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.smart0.xyz/Article/details/gtndkzttop.html

[J08] 提取年月日与星期
来源：http://dali.xylfe.cn/Article/details/gtpfnxjque.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.xziqi.cn/Article/details/gtxdmkhref.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.cdnleiting.top/Article/details/gtmaydqhkk.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.xuetiantiany.cn/Article/details/gtatqifaqn.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.jyoumei.cn/Article/details/gtpepxzmqc.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yj20258.top/Article/details/gtespikefg.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.aizwys.cn/Article/details/gtwfyvxtqk.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.birdmap.top/Article/details/gthzdwawba.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.cheryme.top/Article/details/gtbekeqnid.html

[J09] 时区处理
来源：http://dali.jqgfzy.top/Article/details/gtoxwlnhzk.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.chenzaomai.com/Article/details/gtigqnoekt.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.c1oappe.top/Article/details/gtteyggywy.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xuanzx.com/Article/details/gteoxzhyrz.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.dianchejie.cn/Article/details/gtjoddhgim.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.zycfv.cn/Article/details/gtdrmgnsec.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jqgfzy.top/Article/details/gtmdkrynjg.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.tian-w.cn/Article/details/gtkcrshtqn.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvhqcodad.html

[J10] 取今天 / 本月第一天
来源：http://dali.guannengcc.top/Article/details/gthszjlqlz.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.fzhhl.top/Article/details/gtnnbywafg.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.svipenyu.cn/Article/details/gtqkbzyrhq.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.jqgufenzy.top/Article/details/gtcabomtfb.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.vqdsnc.cn/Article/details/gtpindyjrc.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.hnqzz.top/Article/details/gtdllymzub.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.0kj1m.cn/Article/details/gtlrrzjywf.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.kuanghao11.cn/Article/details/gtgecfvpvq.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.ybcxt.top/Article/details/gtlrsjtpkf.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtxsglptjz.html

K. JSON 与序列化
来源：http://dali.316326.xyz/Article/details/gtjxnekquj.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtteripaka.html

[K01] 对象转 JSON 字符串
来源：http://dali.ydzc1.top/Article/details/gtfvedcqmy.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtklbhbmsl.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.shzxlz.cn/Article/details/gtosichgeu.html

JS:   JSON.stringify(obj)
来源：http://dali.havefunace.top/Article/details/gtrgvzcbkr.html

TS:   JSON.stringify(obj)
来源：http://dali.zhoulong.xyz/Article/details/gtxpypbymq.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.yonumen.top/Article/details/gtmnwefglw.html

Go:   json.Marshal(obj)
来源：http://dali.9152youxi.cn/Article/details/gtqjfgpzoo.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.redwolf501.top/Article/details/gtlmzmzxkt.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlonvxrvl.html


<!-- 参考信息 -->