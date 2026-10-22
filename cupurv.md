代发 wailian999

Java: u instanceof User
来源：http://dali.zhongyouzk.top/Article/details/gtddezqggu.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.xinyue.icu/Article/details/gtrxvlwrtr.html

Ruby: u.is_a?(User)
来源：http://dali.gogol.net.cn/Article/details/gtnptfsiit.html

C#:   u is User
来源：http://dali.xziqi.cn/Article/details/gtsbrguarq.html

[G14] 数据类 / record
来源：http://dali.hnqzz.top/Article/details/gtdloobaki.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.xuanzx.com/Article/details/gtfpavndse.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.nanxuanxn.top/Article/details/gtfhvgsepp.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hammf.cn/Article/details/gtfbxyprta.html

TS:   type User = { name: string; age: number };
来源：http://dali.jqgufenzy.top/Article/details/gtlrieicig.html

Java: record User(String name, int age) {}
来源：http://dali.316326.xyz/Article/details/gtulpjlhtv.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zycfv.cn/Article/details/gtayngvyqx.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.snrcjt.cn/Article/details/gtxkbvsckx.html

C#:   record User(string Name, int Age);
来源：http://dali.nanxinkj.top/Article/details/gtvidotvcy.html

[G15] 枚举
来源：http://dali.bjfxy.top/Article/details/gtmqjummto.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.c1oappe.top/Article/details/gtlfllkufj.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnixgxijq.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.tianlin.xyz/Article/details/gtjjupdlzp.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.aizwys.cn/Article/details/gtcibiblkr.html

Java: enum Color { RED, GREEN }
来源：http://dali.jqgufenzy.top/Article/details/gtiokegrkh.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.feifeiyinyue.top/Article/details/gttvydqmfi.html

Ruby: Color = %i[red green].freeze
来源：http://dali.cqqwz.cn/Article/details/gtkgfywuzc.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhoulong.xyz/Article/details/gtkknijucz.html

[G16] 对象转数组 / 字典
来源：http://dali.ppjwa.cn/Article/details/gtdisugjon.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.ydzc1.top/Article/details/gtsxaiwpge.html

PHP:  get_object_vars($obj);
来源：http://dali.snrcjt.cn/Article/details/gtiqxymukp.html

JS:   Object.entries(obj)
来源：http://dali.xinyue.icu/Article/details/gtghfirany.html

TS:   Object.entries(obj)
来源：http://dali.daria6918.cn/Article/details/gttxqrgrkj.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmdmaratu.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.chenzaomai.com/Article/details/gtyftraigk.html

Ruby: obj.instance_variables
来源：http://dali.sxryk.cn/Article/details/gtdsiiqyys.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.feifeiyinyue.top/Article/details/gtluvjcadm.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtzkvyohzj.html

H. 异常与错误处理
来源：http://dali.fzhhl.top/Article/details/gtgkxjznrw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gttljfyifb.html

[H01] try / catch 基础
来源：http://dali.feifeiyinyue.top/Article/details/gtugmosefu.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.dianchejie.cn/Article/details/gtiogkfyzj.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.dianchejie.cn/Article/details/gtejvydxyu.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.tian-w.cn/Article/details/gtixbpzmdg.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jinqigfzy.top/Article/details/gtxrzkyuvm.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.9152youxi.cn/Article/details/gtfjpzwxxv.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.ivvv.top/Article/details/gtxvsimylt.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jinqigfzy.top/Article/details/gtsrjsoqkh.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zycfv.cn/Article/details/gteeedoplk.html

[H02] finally / ensure 收尾
来源：http://dali.yvedp.cn/Article/details/gtufzbddcz.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yj202588.top/Article/details/gtsbpkxjlu.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jinqigufen.top/Article/details/gtraawptgp.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtofltwgar.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.wangdashe.top/Article/details/gtmxllhrik.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.pycfn.com/Article/details/gtlkozexix.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.guannengcc.top/Article/details/gtaexqtpvm.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.gzhubu.top/Article/details/gtbldlabnp.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jinqigfzy.top/Article/details/gtauqujljk.html

[H03] 主动抛出异常
来源：http://dali.mhx1999.top/Article/details/gtuksahfye.html

Py:   raise ValueError("错误信息")
来源：http://dali.xinyue.icu/Article/details/gtagkbckfm.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.ybcxt.top/Article/details/gtxtulmwxq.html

JS:   throw new Error("错误信息");
来源：http://dali.ivvv.top/Article/details/gtvyplxmnk.html

TS:   throw new Error("错误信息");
来源：http://dali.yj202588.top/Article/details/gteuqlosnx.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.guowangkeji.top/Article/details/gtfhkmpgqk.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hfpthk.cn/Article/details/gtzjxntxoo.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yangfankeji.com/Article/details/gtaidwuyvv.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.tianlin.xyz/Article/details/gtzzrwboij.html

[H04] 自定义异常类型
来源：http://dali.pycfn.com/Article/details/gtmwuqvfxu.html

Py:   class MyError(Exception): pass
来源：http://dali.hnxiangtu.top/Article/details/gtkjafjwos.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.quarkkingdee.top/Article/details/gtedxhojau.html

JS:   class MyError extends Error {}
来源：http://dali.wangshuangyany.cn/Article/details/gtoybtcylx.html

TS:   class MyError extends Error {}
来源：http://dali.jinqigfzy.top/Article/details/gtzekiqnng.html

Java: class MyException extends RuntimeException {}
来源：http://dali.sysykeji.top/Article/details/gtoqgnpsyk.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.vqdsnc.cn/Article/details/gtmxxxnrxb.html

Ruby: class MyError < StandardError; end
来源：http://dali.cqqwz.cn/Article/details/gtmnxsxybv.html

C#:   class MyException : Exception {}
来源：http://dali.cucudq.cn/Article/details/gtlndjoqii.html

[H05] 捕获特定类型
来源：http://dali.yvedp.cn/Article/details/gtghqnfeuc.html

Py:   except ValueError as e:
来源：http://dali.cucudq.cn/Article/details/gtokquhaox.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.shzxlz.cn/Article/details/gtfooulted.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtokiugpbk.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yvedp.cn/Article/details/gtfnqbtnol.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.daxiang520.top/Article/details/gtzbwofwge.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.redwolf501.top/Article/details/gtoaztkpql.html

Ruby: rescue ArgumentError => e
来源：http://dali.shanyushiyangtech.top/Article/details/gtkjnfvdfm.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zycfv.cn/Article/details/gtgzlblttc.html

[H06] 可选值 / 空值安全访问
来源：http://dali.kuanghao11.cn/Article/details/gtyddrvctp.html

Py:   value = d.get("k") or default
来源：http://dali.zhixingplan.top/Article/details/gtfqggmdht.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.vqdsnc.cn/Article/details/gteuylnhrn.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.shanyushiyangkeji.top/Article/details/gtshgycysh.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hfpthk.cn/Article/details/gtgzhgzscw.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yvedp.cn/Article/details/gttbkpvskj.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaodxelwl.html

Ruby: d&.dig(:a, :b)
来源：http://dali.0kj1m.cn/Article/details/gtjkncxbss.html

C#:   obj?.A?.B ?? default
来源：http://dali.zycfv.cn/Article/details/gtymgeyajw.html

[H07] 断言
来源：http://dali.quarkkingdee.top/Article/details/gtqmtighwz.html

Py:   assert x > 0, "必须为正"
来源：http://dali.shuidangran.top/Article/details/gteqwtmxeq.html

PHP:  assert($x > 0);
来源：http://dali.jqgfzy.top/Article/details/gtqztietmr.html

JS:   console.assert(x > 0);
来源：http://dali.cucudq.cn/Article/details/gtlzwyyiey.html

TS:   console.assert(x > 0);
来源：http://dali.yuxming.cn/Article/details/gtoanfslzn.html

Java: assert x > 0 : "必须为正";
来源：http://dali.shuidangran.top/Article/details/gtmcvgglof.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.snrcjt.cn/Article/details/gtmnnwrshx.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yonumen.top/Article/details/gtfelvdtyu.html

C#:   Debug.Assert(x > 0);
来源：http://dali.shzxlz.cn/Article/details/gtmontguxn.html

[H08] 获取错误信息与堆栈
来源：http://dali.yuxming.cn/Article/details/gtradhtrno.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yonumen.top/Article/details/gtrdpnpont.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.c1oappe.top/Article/details/gtyugvrqgv.html

JS:   e.message;  e.stack
来源：http://dali.zycfv.cn/Article/details/gtztkmmysq.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yuanzhike.top/Article/details/gtpjharzew.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.xinyue.icu/Article/details/gtrdtqvrro.html

Go:   err.Error()
来源：http://dali.xziqi.cn/Article/details/gtnjpvqznq.html

Ruby: e.message;  e.backtrace
来源：http://dali.zycfv.cn/Article/details/gtaaqhgzmk.html

C#:   e.Message;  e.StackTrace
来源：http://dali.nwbrower.top/Article/details/gthqbbpdze.html

[H09] 带错误码的异常
来源：http://dali.pengpengdd.cyou/Article/details/gtlownfycw.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.pycfn.com/Article/details/gtsiaoerfk.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.guowangkeji.top/Article/details/gtamgvmjgn.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yvedp.cn/Article/details/gtqairgrcv.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yueranfly.top/Article/details/gtwslakeqq.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.snrcjt.cn/Article/details/gtcigurqxd.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.svipenyu.cn/Article/details/gtkabasbdi.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.shanyushiyangtech.top/Article/details/gtchmpxlvh.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.gaohongyu789.top/Article/details/gttpabytsf.html

[H10] 资源自动释放
来源：http://dali.zhoulong.xyz/Article/details/gtstfkqrwy.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.cheryme.top/Article/details/gtvmeyshqt.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.hongshengwenyu.top/Article/details/gtxtlgsgoi.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yongpay.top/Article/details/gtnpabvjul.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.pengpengdd.cyou/Article/details/gtxhpesiei.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.shanyushiyangtech.top/Article/details/gtggdnaosc.html

Go:   defer f.Close()
来源：http://dali.ivvv.top/Article/details/gtjcjykxly.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yj20258.top/Article/details/gtismojewy.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtvmiwwrna.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtfenptrzu.html

I. 正则表达式
来源：http://dali.fengsongda.top/Article/details/gtgouipgrn.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gttxfkocaz.html

[I01] 判断是否匹配
来源：http://dali.cucudq.cn/Article/details/gtiwaxjgki.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvnboernv.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.sufxvd.cn/Article/details/gtvcwvqbzd.html

JS:   /\d+/.test(s)
来源：http://dali.9152youxi.cn/Article/details/gtoudwskhb.html

TS:   /\d+/.test(s)
来源：http://dali.xinyue.icu/Article/details/gthdrzgxcd.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yj20258888.top/Article/details/gtwpdrnmki.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhijiandao.cn/Article/details/gtrjgnaeyj.html

Ruby: s.match?(/\d+/)
来源：http://dali.xziqi.cn/Article/details/gtklkhgvpn.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.shanyushiyangtech.top/Article/details/gtpwuvkhit.html

[I02] 提取所有匹配
来源：http://dali.birdmap.top/Article/details/gtmueiwrbb.html

Py:   re.findall(r"\d+", s)
来源：http://dali.andypj.xyz/Article/details/gttdbquwml.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jinqigfzy.top/Article/details/gtxrrvwrvf.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.shangyingyoupin.top/Article/details/gtssayrxeo.html

TS:   s.match(/\d+/g)
来源：http://dali.havefunace.top/Article/details/gttoairbpy.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.iojbl.cn/Article/details/gtlntivocx.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.svipenyu.cn/Article/details/gttkwbgijs.html

Ruby: s.scan(/\d+/)
来源：http://dali.xylfe.cn/Article/details/gthspgmtqo.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.redwolf501.top/Article/details/gtawcvadzr.html

[I03] 提取捕获分组
来源：http://dali.daria6918.cn/Article/details/gtiwyaulhz.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.sweek.top/Article/details/gtkcsgfyti.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtizxgjmgh.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jianghu66.top/Article/details/gtonrqxevn.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.tianlin.xyz/Article/details/gtfvhgrrla.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.hysaishi.cn/Article/details/gtfvyoripe.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhiwuduotai.top/Article/details/gtgkpqnxmm.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.kuanghao11.cn/Article/details/gtjcfhkqme.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.xziqi.cn/Article/details/gtxwrzobjs.html

[I04] 正则替换
来源：http://dali.jinghuilouyu.cn/Article/details/gtemtyzaea.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.havefunace.top/Article/details/gtleaciaya.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.quarkkingdee.top/Article/details/gtmgeyqusj.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.ehwqpu.com/Article/details/gtqujmohan.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.gzhubu.top/Article/details/gtytjnkcmm.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.dashuyun.cn/Article/details/gtnniqykcy.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.guannengcc.top/Article/details/gtccofkemu.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqgwwdogq.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.hfpthk.cn/Article/details/gtfsccfcjs.html

[I05] 按正则拆分
来源：http://dali.gzhubu.top/Article/details/gtnyqmtbfa.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zycfv.cn/Article/details/gtzvaynsiu.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.gotoacloud.top/Article/details/gthohrjsgp.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.birdmap.top/Article/details/gthxpkeixx.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.ivvv.top/Article/details/gtoeyxyhnt.html

Java: s.split("\\s*,\\s*")
来源：http://dali.shuidangran.top/Article/details/gtxszybupm.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.sweek.top/Article/details/gtbangskuq.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jianghu66.top/Article/details/gtyvnqrydq.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.nanxinkj.top/Article/details/gtubszliks.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.gaohongyu789.top/Article/details/gtxlmsgwvw.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.quarkkingdee.top/Article/details/gtjhexjemw.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.svipenyu.cn/Article/details/gtzxlhlesf.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hywenlv.cn/Article/details/gtljrnkgcz.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yj202588.top/Article/details/gtfucpkjun.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.svipenyu.cn/Article/details/gtavjnawvl.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jyoumei.cn/Article/details/gtxrgnmipd.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.havefunace.top/Article/details/gtqmataelh.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.ydzc1.top/Article/details/gtqlvcevmj.html

[I07] 忽略大小写与多行模式
来源：http://dali.svipenyu.cn/Article/details/gtzrzffadn.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.nanxuanxn.top/Article/details/gtxlkfwyub.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yuanzhike.top/Article/details/gtjujowsql.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.cdnleiting.top/Article/details/gtllvnezpw.html

TS:   /error/gim
来源：http://dali.ehwqpu.com/Article/details/gtontmpjcx.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthovobvix.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.daria6918.cn/Article/details/gtelghuukj.html

Ruby: s.scan(/error/i)
来源：http://dali.sufxvd.cn/Article/details/gtsllljpry.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yj20258888.top/Article/details/gtkhrjercz.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.xuetiantiany.cn/Article/details/gtourkhnsb.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yvedp.cn/Article/details/gtssymgnzm.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.ybcxt.top/Article/details/gtetwpotyo.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.0kj1m.cn/Article/details/gtywtzicpw.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hongshengwenyu.top/Article/details/gtifimbqdj.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.birdmap.top/Article/details/gttrpaavtb.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.kuanghao11.cn/Article/details/gtfzloqccw.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jinqigufen.top/Article/details/gtdgfgnloq.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.sxryk.cn/Article/details/gtrohjnpnq.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gttboazpiv.html

J. 日期与时间
来源：http://dali.shanyushiyangkeji.top/Article/details/gtortfgekj.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gthdenqzfg.html

[J01] 获取当前时间
来源：http://dali.gogol.net.cn/Article/details/gtamhvzlyd.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.yonumen.top/Article/details/gtegpiynfj.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.shuidangran.top/Article/details/gtugbyukkz.html

JS:   new Date();  Date.now()
来源：http://dali.kuanghao11.cn/Article/details/gtdwefdvgm.html

TS:   new Date();  Date.now()
来源：http://dali.snrcjt.cn/Article/details/gthpvnydzm.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.zhijiandao.cn/Article/details/gthdxjubfv.html

Go:   time.Now()
来源：http://dali.haohaochexian.top/Article/details/gtwhubimui.html

Ruby: Time.now
来源：http://dali.shanyushiyangtech.top/Article/details/gtzcplknyf.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.mhx1999.top/Article/details/gtpoxpiatd.html

[J02] 格式化输出
来源：http://dali.sufxvd.cn/Article/details/gtkfzqupaw.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yanxiufei.cn/Article/details/gtgqifaoim.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.shangyingyoupin.top/Article/details/gtyjrklake.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.0kj1m.cn/Article/details/gtmhthamfx.html

TS:   d.toISOString()
来源：http://dali.redwolf501.top/Article/details/gtqeslnecw.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.hnxiangtu.top/Article/details/gtkodiqfnr.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.cdnleiting.top/Article/details/gtzjpvbfha.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.sxryk.cn/Article/details/gtdtdlyibu.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.chenjidiqi.icu/Article/details/gtpozdkuok.html

[J03] 字符串解析为日期
来源：http://dali.zhengqikj.top/Article/details/gtpekkbkwq.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.jqgufenzy.top/Article/details/gtuapndjfy.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.wangdashe.top/Article/details/gtqvzfmozv.html

JS:   new Date("2024-01-02")
来源：http://dali.snrcjt.cn/Article/details/gtkeymsrki.html

TS:   new Date("2024-01-02")
来源：http://dali.xinyue.icu/Article/details/gtznelffxq.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhixingplan.top/Article/details/gtfkrkcien.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zdqjudy.top/Article/details/gtwjcwqmnc.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.hongshengwenyu.top/Article/details/gtfokfqvpq.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.mhx1999.top/Article/details/gtkdjsheip.html

[J04] 时间戳与日期互转
来源：http://dali.andypj.xyz/Article/details/gtjuxqhftx.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jinqigfzy.top/Article/details/gtemcwtfmh.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.zhixingplan.top/Article/details/gtalbbukdj.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.xuetiantiany.cn/Article/details/gtqjijkjaf.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zhixingplan.top/Article/details/gtfqeysvov.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.9152youxi.cn/Article/details/gtequywjdc.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.nanxuanxn.top/Article/details/gtzivtyooz.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.feifeiyinyue.top/Article/details/gtqfikbtyn.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.hnqzz.top/Article/details/gthacqlmec.html

[J05] 时间加减（加 7 天）
来源：http://dali.yj20258888.top/Article/details/gtynjsyldg.html

Py:   now + timedelta(days=7)
来源：http://dali.ehwqpu.com/Article/details/gtcjmenarn.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.zhengqikj.top/Article/details/gtsburynuv.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlazzfjxf.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hfpthk.cn/Article/details/gtzdhndhxh.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.feifeiyinyue.top/Article/details/gtbbkktrpi.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.zhixingplan.top/Article/details/gtgezyjqkd.html

Ruby: Time.now + 7 * 86400
来源：http://dali.guannengcc.top/Article/details/gtcemizdat.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.cashguo.top/Article/details/gtfnpkafim.html

[J06] 计算两时间之差
来源：http://dali.hammf.cn/Article/details/gtxnixwstu.html

Py:   (end - start).total_seconds()
来源：http://dali.zhoulong.xyz/Article/details/gtgohhcdkw.html

PHP:  $end->diff($start)->days;
来源：http://dali.snrcjt.cn/Article/details/gtkwwiopwz.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.xuetiantiany.cn/Article/details/gtldcxqilo.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.pycfn.com/Article/details/gtoxwtkhwe.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yuxming.cn/Article/details/gtkxkswgqh.html

Go:   end.Sub(start).Hours()
来源：http://dali.nwbrower.top/Article/details/gtyvpsqsrt.html

Ruby: end - start                 # 返回秒数
来源：http://dali.wangshuangyany.cn/Article/details/gtgaeqriit.html

C#:   (end - start).TotalSeconds
来源：http://dali.guowangkeji.top/Article/details/gtzdawwpbk.html

[J07] 比较两个日期
来源：http://dali.kuanghao11.cn/Article/details/gtzfvfxgnt.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.yonumen.top/Article/details/gtiofgoopp.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.yuanzhike.top/Article/details/gtaandgjmz.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.xuanzx.com/Article/details/gtftztxhqz.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.feifeiyinyue.top/Article/details/gtcpskxzni.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.birdmap.top/Article/details/gtnnewprze.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.chenzaomai.com/Article/details/gtqiyhcepr.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yonumen.top/Article/details/gtxophdget.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yonumen.top/Article/details/gtxfbgjmuh.html

[J08] 提取年月日与星期
来源：http://dali.iojbl.cn/Article/details/gtievdlczc.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.iojbl.cn/Article/details/gtxgvplaga.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.havefunace.top/Article/details/gtoozkmmqe.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.zhoulong.xyz/Article/details/gtyqliygmo.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.snrcjt.cn/Article/details/gtxncyvdhy.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.nanxuanxn.top/Article/details/gtndxcsqmc.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.gotoacloud.top/Article/details/gtrwsdazar.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.shzxlz.cn/Article/details/gtjklstqjz.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yuanzhike.top/Article/details/gttbjwaapi.html

[J09] 时区处理
来源：http://dali.jinqigufen.top/Article/details/gtypseefld.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.jinqigufen.top/Article/details/gtpocxcdjo.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.dashuyun.cn/Article/details/gtryrqsxcx.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.andypj.xyz/Article/details/gtrjzvltrm.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.xylfe.cn/Article/details/gtusqjmjfw.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.jqgfzy.top/Article/details/gtioazqtud.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.jqgufenzy.top/Article/details/gtjwhuksid.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.aibaodan.cn/Article/details/gtkdgyyord.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoaumajma.html

[J10] 取今天 / 本月第一天
来源：http://dali.guannengcc.top/Article/details/gtgcdphtpa.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.fengsongda.top/Article/details/gtjwnfrnxb.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.gogol.net.cn/Article/details/gtzpiwouof.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.ydzc1.top/Article/details/gtxmytwehi.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.feifeiyinyue.top/Article/details/gtiwxtkxvh.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.yangfankeji.com/Article/details/gtgonjzpmu.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.yueranfly.top/Article/details/gtzufmtgvf.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zhengqikj.top/Article/details/gtnhvfcqjp.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.wangdashe.top/Article/details/gtbcynsgrp.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtcxcpokma.html

K. JSON 与序列化
来源：http://dali.nanxuanxn.top/Article/details/gtpiqhtljw.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtjvbckxgk.html

[K01] 对象转 JSON 字符串
来源：http://dali.cashguo.top/Article/details/gtofobilfu.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.feifeiyinyue.top/Article/details/gtamwtpujx.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.guowangkeji.top/Article/details/gtsyibrjrg.html

JS:   JSON.stringify(obj)
来源：http://dali.zhengqikj.top/Article/details/gtmbgocgob.html

TS:   JSON.stringify(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gtnxojefca.html


<!-- 参考信息 -->