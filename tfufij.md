代发 wailian999

PHP:  public static function f() {}
来源：http://dali.c1oappe.top/Article/details/gtmvkwxijx.html

JS:   static f() {}
来源：http://dali.zhengqikj.top/Article/details/gtuwtylvoo.html

TS:   static f(): void {}
来源：http://dali.gotoacloud.top/Article/details/gtdjtffgzi.html

Java: static void f() {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyzfuxgim.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.shuidangran.top/Article/details/gthqdrlprr.html

Ruby: def self.f; end
来源：http://dali.nwbrower.top/Article/details/gtbuacwbjz.html

C#:   public static void F() {}
来源：http://dali.guowangkeji.top/Article/details/gtmdqeiewi.html

[G09] 接口 / 抽象类
来源：http://dali.zhongyouzk.top/Article/details/gtvwjhdlfr.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yangfankeji.com/Article/details/gtoajfcwce.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zdqjudy.top/Article/details/gtrwbirrzi.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.iojbl.cn/Article/details/gtovyulgpp.html

TS:   interface Shape { area(): number; }
来源：http://dali.dianchejie.cn/Article/details/gtkryoyedp.html

Java: interface Shape { double area(); }
来源：http://dali.cheryme.top/Article/details/gtnsixdvoz.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.snrcjt.cn/Article/details/gtjmnzryci.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.wangdashe.top/Article/details/gtzymhcwmb.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhixingplan.top/Article/details/gtublozunc.html

[G10] 访问控制
来源：http://dali.xuanzx.com/Article/details/gtxczstgzh.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.feifeiyinyue.top/Article/details/gtlpigxwxh.html

PHP:  public / protected / private
来源：http://dali.guannengcc.top/Article/details/gtfeynofqw.html

JS:   #private 字段；其余公开
来源：http://dali.zhoulong.xyz/Article/details/gtwxuhsoti.html

TS:   public / protected / private
来源：http://dali.yangfankeji.com/Article/details/gtqxwdkjfl.html

Java: public / protected / private / 默认包级
来源：http://dali.gogol.net.cn/Article/details/gtbckuahqo.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xylfe.cn/Article/details/gttfxmtiza.html

Ruby: public / protected / private
来源：http://dali.jqgfzy.top/Article/details/gtrrykxgjr.html

C#:   public / protected / private / internal
来源：http://dali.ivvv.top/Article/details/gteyggodcl.html

[G11] getter / setter
来源：http://dali.gotoacloud.top/Article/details/gtvughdywa.html

Py:   @property 与 @x.setter
来源：http://dali.kuanghao11.cn/Article/details/gtamhlrcsu.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gtlpcysewb.html

JS:   get name() { return this._name; }
来源：http://dali.gogol.net.cn/Article/details/gtruniqzea.html

TS:   get name(): string { return this._name; }
来源：http://dali.316326.xyz/Article/details/gtrmvpdwkr.html

Java: public String getName() { return name; }
来源：http://dali.andypj.xyz/Article/details/gtclhivdmc.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.haohaochexian.top/Article/details/gtrydfvogw.html

Ruby: attr_accessor :name
来源：http://dali.c1oappe.top/Article/details/gtjbiaopmg.html

C#:   public string Name { get; set; }
来源：http://dali.yj202588.top/Article/details/gtwbpphtxa.html

[G12] 对象转字符串
来源：http://dali.hnqzz.top/Article/details/gtgfahxgkq.html

Py:   def __str__(self): return self.name
来源：http://dali.cashguo.top/Article/details/gtsxlcrual.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.xylfe.cn/Article/details/gtwnsjqwqo.html

JS:   toString() { return this.name; }
来源：http://dali.svipenyu.cn/Article/details/gtshfhkhte.html

TS:   toString(): string { return this.name; }
来源：http://dali.0kj1m.cn/Article/details/gtpphrdnab.html

Java: @Override public String toString() { return name; }
来源：http://dali.chenlongwang.top/Article/details/gtukhivxzm.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.nanxuanxn.top/Article/details/gtmbvbutcx.html

Ruby: def to_s; @name; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuhczpvmj.html

C#:   public override string ToString() => Name;
来源：http://dali.chenlongwang.top/Article/details/gtvdbupqpb.html

[G13] 判断对象类型
来源：http://dali.tanke756.top/Article/details/gtwfijslcm.html

Py:   isinstance(u, User)
来源：http://dali.yongpay.top/Article/details/gtthfccmrf.html

PHP:  $u instanceof User
来源：http://dali.aibaodan.cn/Article/details/gtdjpwdkxs.html

JS:   u instanceof User
来源：http://dali.jiagoushi.top/Article/details/gthgejixjw.html

TS:   u instanceof User
来源：http://dali.wangdashe.top/Article/details/gtnasnkmba.html

Java: u instanceof User
来源：http://dali.haohaochexian.top/Article/details/gtoclfccrf.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.snrcjt.cn/Article/details/gtqxiurnji.html

Ruby: u.is_a?(User)
来源：http://dali.dashuyun.cn/Article/details/gtatsqxyeh.html

C#:   u is User
来源：http://dali.jqgfzy.top/Article/details/gtnkuxzdrn.html

[G14] 数据类 / record
来源：http://dali.jqgufenzy.top/Article/details/gtzdbhijkq.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.tanke756.top/Article/details/gtttpxadlh.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yj20258.top/Article/details/gtcxxswjzi.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.wangdashe.top/Article/details/gtmahdgrsl.html

TS:   type User = { name: string; age: number };
来源：http://dali.xylfe.cn/Article/details/gtiqidgzhf.html

Java: record User(String name, int age) {}
来源：http://dali.sufxvd.cn/Article/details/gtskuqeonu.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hammf.cn/Article/details/gteuumqzef.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.gaohongyu789.top/Article/details/gtepeuwxeo.html

C#:   record User(string Name, int Age);
来源：http://dali.yj20258.top/Article/details/gtphaceygs.html

[G15] 枚举
来源：http://dali.cucudq.cn/Article/details/gtsqbxbpov.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jianghu66.top/Article/details/gtqhdwurkk.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.nwbrower.top/Article/details/gtfyngtvvj.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.aibaodan.cn/Article/details/gtmngzhgdy.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xinyue.icu/Article/details/gtpgqxrvmm.html

Java: enum Color { RED, GREEN }
来源：http://dali.xinyue.icu/Article/details/gtvrpvlhrp.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwypucsox.html

Ruby: Color = %i[red green].freeze
来源：http://dali.pycfn.com/Article/details/gtuhcikjiz.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hnqzz.top/Article/details/gtsrofrkbc.html

[G16] 对象转数组 / 字典
来源：http://dali.jianghu66.top/Article/details/gtyyojeyqy.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.xuetiantiany.cn/Article/details/gtjpmtkahx.html

PHP:  get_object_vars($obj);
来源：http://dali.pengpengdd.cyou/Article/details/gtwcrddjvu.html

JS:   Object.entries(obj)
来源：http://dali.mhx1999.top/Article/details/gtlrgleoip.html

TS:   Object.entries(obj)
来源：http://dali.yanxiufei.cn/Article/details/gtmuxrjtbm.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.ybcxt.top/Article/details/gtfpoegmny.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.xinyue.icu/Article/details/gtslasmbsm.html

Ruby: obj.instance_variables
来源：http://dali.cheryme.top/Article/details/gtxjvsxypd.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hammf.cn/Article/details/gtlbrrcwdl.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gteszalwdi.html

H. 异常与错误处理
来源：http://dali.smart0.xyz/Article/details/gtnckxfjel.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtfuazbwjy.html

[H01] try / catch 基础
来源：http://dali.zhengqikj.top/Article/details/gtybtvyiyc.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.0kj1m.cn/Article/details/gtttydhmhp.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtktsaeots.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.nanxinkj.top/Article/details/gttobgmoia.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.xylfe.cn/Article/details/gtpwvzfjcq.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.xylfe.cn/Article/details/gtnojqarrt.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhixingplan.top/Article/details/gtptytsrlv.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.cheryme.top/Article/details/gtnxmphuth.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yuxming.cn/Article/details/gtrbrjbkdr.html

[H02] finally / ensure 收尾
来源：http://dali.dianchejie.cn/Article/details/gtsowtvpud.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hfpthk.cn/Article/details/gtsxawsaoz.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.nwbrower.top/Article/details/gtojvyxmkx.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.andypj.xyz/Article/details/gtitnatjhw.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.sweek.top/Article/details/gtoqdoblus.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.gzhubu.top/Article/details/gtmpfxodoo.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jlsjyb.cn/Article/details/gtzcwzzzcg.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.c1oappe.top/Article/details/gtvuqwtefp.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.9152youxi.cn/Article/details/gtwtukcdnq.html

[H03] 主动抛出异常
来源：http://dali.shangyingyoupin.top/Article/details/gtnewwjzne.html

Py:   raise ValueError("错误信息")
来源：http://dali.yvedp.cn/Article/details/gtbiuxxtqg.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hfpthk.cn/Article/details/gtmnhteuyg.html

JS:   throw new Error("错误信息");
来源：http://dali.zhongyouzk.top/Article/details/gtfsshxjsz.html

TS:   throw new Error("错误信息");
来源：http://dali.yj20258.top/Article/details/gtazkzjifa.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.feifeiyinyue.top/Article/details/gtngwqbylx.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.tianlin.xyz/Article/details/gtnxyrvtkl.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hnqzz.top/Article/details/gtiffwlkdy.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.chenlongwang.top/Article/details/gtqjarvylk.html

[H04] 自定义异常类型
来源：http://dali.hfpthk.cn/Article/details/gtaxeayunb.html

Py:   class MyError(Exception): pass
来源：http://dali.xuetiantiany.cn/Article/details/gtngvmoeql.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.cdnleiting.top/Article/details/gtpjtlolnx.html

JS:   class MyError extends Error {}
来源：http://dali.jqgufenzy.top/Article/details/gtklqndywk.html

TS:   class MyError extends Error {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtculelogl.html

Java: class MyException extends RuntimeException {}
来源：http://dali.vqdsnc.cn/Article/details/gtqcpqlniw.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhoulong.xyz/Article/details/gtowauzjpu.html

Ruby: class MyError < StandardError; end
来源：http://dali.ivvv.top/Article/details/gtsuvmpjid.html

C#:   class MyException : Exception {}
来源：http://dali.sxryk.cn/Article/details/gtwqjcgubg.html

[H05] 捕获特定类型
来源：http://dali.jqgufenzy.top/Article/details/gtavioyznu.html

Py:   except ValueError as e:
来源：http://dali.bjfxy.top/Article/details/gtltqdcvja.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jyoumei.cn/Article/details/gtvithrkwh.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.cashguo.top/Article/details/gtvrtxzlwg.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.xuanzx.com/Article/details/gtmvquibxo.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.c1oappe.top/Article/details/gthezxkawr.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.xuanzx.com/Article/details/gtzsjbicmv.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhiwuduotai.top/Article/details/gtigybsagv.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.wangdashe.top/Article/details/gtalmclbiu.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jqgfzy.top/Article/details/gtvparnisw.html

Py:   value = d.get("k") or default
来源：http://dali.chenjidiqi.icu/Article/details/gtffpyvsbe.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.c1oappe.top/Article/details/gtorbwuwbh.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yangfankeji.com/Article/details/gtenxohayj.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.cucudq.cn/Article/details/gtefdpfvak.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jiagoushi.top/Article/details/gtriroaxkn.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.hongshengwenyu.top/Article/details/gtvbqusyqp.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yj20258.top/Article/details/gtmqcrmtpz.html

C#:   obj?.A?.B ?? default
来源：http://dali.chenzaomai.com/Article/details/gthplkwcfj.html

[H07] 断言
来源：http://dali.0kj1m.cn/Article/details/gtlzokfzpd.html

Py:   assert x > 0, "必须为正"
来源：http://dali.kuanghao11.cn/Article/details/gthpxtfnkm.html

PHP:  assert($x > 0);
来源：http://dali.hnqzz.top/Article/details/gtfiuvbvgi.html

JS:   console.assert(x > 0);
来源：http://dali.feifeiyinyue.top/Article/details/gtvtnzoorn.html

TS:   console.assert(x > 0);
来源：http://dali.svipenyu.cn/Article/details/gtxkuspafk.html

Java: assert x > 0 : "必须为正";
来源：http://dali.shzxlz.cn/Article/details/gtaihhulzl.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.0kj1m.cn/Article/details/gtqevdkbtg.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.aibaodan.cn/Article/details/gtqojgpqji.html

C#:   Debug.Assert(x > 0);
来源：http://dali.ppjwa.cn/Article/details/gtxcmahptv.html

[H08] 获取错误信息与堆栈
来源：http://dali.hnqzz.top/Article/details/gtkqarbzom.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yangfankeji.com/Article/details/gtcwkaglbt.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yongpay.top/Article/details/gtiwglytqb.html

JS:   e.message;  e.stack
来源：http://dali.tian-w.cn/Article/details/gtepsxnxor.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yj20258888.top/Article/details/gtayadicfn.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.ydzc1.top/Article/details/gttxzfilht.html

Go:   err.Error()
来源：http://dali.yonumen.top/Article/details/gtjezyabzj.html

Ruby: e.message;  e.backtrace
来源：http://dali.cqqwz.cn/Article/details/gtlfodcugs.html

C#:   e.Message;  e.StackTrace
来源：http://dali.pengpengdd.cyou/Article/details/gtgroowity.html

[H09] 带错误码的异常
来源：http://dali.hysaishi.cn/Article/details/gtnqzcggbm.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.daxiang520.top/Article/details/gtdmtygova.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yvedp.cn/Article/details/gtazgyginj.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.daria6918.cn/Article/details/gtsgujycsy.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.hywenlv.cn/Article/details/gtkuujgfdw.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jlsjyb.cn/Article/details/gtxxdsezvx.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.ehwqpu.com/Article/details/gtgubvskpm.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jlsjyb.cn/Article/details/gtjkwmzpck.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.cheryme.top/Article/details/gtrpzhzpqt.html

[H10] 资源自动释放
来源：http://dali.nanxinkj.top/Article/details/gtukrxcklj.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zycfv.cn/Article/details/gtckjzilve.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.daria6918.cn/Article/details/gtxgemrbcq.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.feifeiyinyue.top/Article/details/gtvzxyqtuz.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sxryk.cn/Article/details/gtryawbpqv.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.ydzc1.top/Article/details/gtakgnjggb.html

Go:   defer f.Close()
来源：http://dali.fzhhl.top/Article/details/gtagjtidbi.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.ivvv.top/Article/details/gtjyodwpre.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.gzhubu.top/Article/details/gttpmscpul.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtbnvjssfq.html

I. 正则表达式
来源：http://dali.pengpengdd.cyou/Article/details/gthklnooal.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtjnyftsjt.html

[I01] 判断是否匹配
来源：http://dali.jlsjyb.cn/Article/details/gtjooaizpz.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcjqaxror.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.xuetiantiany.cn/Article/details/gtujmwsduq.html

JS:   /\d+/.test(s)
来源：http://dali.birdmap.top/Article/details/gtaguezydw.html

TS:   /\d+/.test(s)
来源：http://dali.shzxlz.cn/Article/details/gtgmwnpscf.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.xuetiantiany.cn/Article/details/gtvurynaud.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.cashguo.top/Article/details/gtshxlytzi.html

Ruby: s.match?(/\d+/)
来源：http://dali.andypj.xyz/Article/details/gtwarlwrzx.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.fengsongda.top/Article/details/gtvrwlwosh.html

[I02] 提取所有匹配
来源：http://dali.jyoumei.cn/Article/details/gteigrdlib.html

Py:   re.findall(r"\d+", s)
来源：http://dali.hywenlv.cn/Article/details/gtqmxkytqy.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.wangshuangyany.cn/Article/details/gtqjweszjy.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.hywenlv.cn/Article/details/gtxegjxaya.html

TS:   s.match(/\d+/g)
来源：http://dali.yuanzhike.top/Article/details/gtvrsqujez.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhiwuduotai.top/Article/details/gtioxpczxg.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtqmpqgfgv.html

Ruby: s.scan(/\d+/)
来源：http://dali.pengpengdd.cyou/Article/details/gttdmdilwu.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.mhx1999.top/Article/details/gtlhwmgkhp.html

[I03] 提取捕获分组
来源：http://dali.havefunace.top/Article/details/gttvkmwooq.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.ppjwa.cn/Article/details/gtibdnxcgf.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhiwuduotai.top/Article/details/gtirtwknbh.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.tanke756.top/Article/details/gtgludjtuv.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.cashguo.top/Article/details/gthrpyuqdq.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.hfpthk.cn/Article/details/gtttxrlnrn.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhongyouzk.top/Article/details/gtjdghvkok.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.ehwqpu.com/Article/details/gtknogupgq.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.dashuyun.cn/Article/details/gttjkrdlvh.html

[I04] 正则替换
来源：http://dali.yanxiufei.cn/Article/details/gtxbraagql.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhengqikj.top/Article/details/gtlqotlrja.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yonumen.top/Article/details/gttsujujcl.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhijiandao.cn/Article/details/gtxqqybbkr.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jqgufenzy.top/Article/details/gtjnhwmxcg.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.shuidangran.top/Article/details/gtzbaqeyvf.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.redwolf501.top/Article/details/gtmgyrjoeb.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.cucudq.cn/Article/details/gtyvpxazlf.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdlwuflod.html

[I05] 按正则拆分
来源：http://dali.jyoumei.cn/Article/details/gttkoozoiv.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmvmgvftk.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.shangyingyoupin.top/Article/details/gtaexeukdd.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.c1oappe.top/Article/details/gtbznwqgbb.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttdhazxzi.html

Java: s.split("\\s*,\\s*")
来源：http://dali.nanxuanxn.top/Article/details/gtypitsuja.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.cashguo.top/Article/details/gtmaqhwchx.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jinqigfzy.top/Article/details/gtzicpdjjt.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yangfankeji.com/Article/details/gtljxxijig.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yuanzhike.top/Article/details/gtxbspoyzz.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yuanzhike.top/Article/details/gtiueujqtw.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.fengsongda.top/Article/details/gtzjaekgwn.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.hnxiangtu.top/Article/details/gtpzasckkt.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.dashuyun.cn/Article/details/gtztgiltjv.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.hnxiangtu.top/Article/details/gtcroynzyl.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.0kj1m.cn/Article/details/gthjpcabov.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.gotoacloud.top/Article/details/gtrhjouteu.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.yj202588.top/Article/details/gtmkhtwans.html

[I07] 忽略大小写与多行模式
来源：http://dali.ydzc1.top/Article/details/gtbmbqabyr.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.hywenlv.cn/Article/details/gtvwvddoaj.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.9152youxi.cn/Article/details/gtnjdivxnw.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.yangfankeji.com/Article/details/gtxefqcshw.html

TS:   /error/gim
来源：http://dali.chenlongwang.top/Article/details/gteflxemay.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.quarkkingdee.top/Article/details/gtpnimwsly.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hywenlv.cn/Article/details/gtjaejshvp.html

Ruby: s.scan(/error/i)
来源：http://dali.daria6918.cn/Article/details/gtxvhhiovo.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.xuetiantiany.cn/Article/details/gtvwwclvqd.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhongyouzk.top/Article/details/gtouuzzdah.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.mhx1999.top/Article/details/gtpbgrihgp.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.dianchejie.cn/Article/details/gtlrywslkz.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.hysaishi.cn/Article/details/gtfenpziuo.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zhoulong.xyz/Article/details/gtnbgchjgh.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.ybcxt.top/Article/details/gtmuoqmofx.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.svipenyu.cn/Article/details/gtpwlbkpmt.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.jyoumei.cn/Article/details/gtcwkdvexj.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.fengsongda.top/Article/details/gtdcnkntim.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtaqfzwnzy.html

J. 日期与时间
来源：http://dali.snrcjt.cn/Article/details/gtpztyiyky.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtfxqlykkd.html

[J01] 获取当前时间
来源：http://dali.guannengcc.top/Article/details/gthaindxlq.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.hnxiangtu.top/Article/details/gtwpboqtku.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.hywenlv.cn/Article/details/gtoibmdums.html

JS:   new Date();  Date.now()
来源：http://dali.chenzaomai.com/Article/details/gtjtzpkcey.html

TS:   new Date();  Date.now()
来源：http://dali.iojbl.cn/Article/details/gtzsfysbzw.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.smart0.xyz/Article/details/gtleylisei.html

Go:   time.Now()
来源：http://dali.ybcxt.top/Article/details/gtiinbrjxk.html

Ruby: Time.now
来源：http://dali.yj20258888.top/Article/details/gthikdennx.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jinqigufen.top/Article/details/gtrdplpnhn.html

[J02] 格式化输出
来源：http://dali.shangyingyoupin.top/Article/details/gtftbfjmhp.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.pengpengdd.cyou/Article/details/gtlgpopwab.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.haohaochexian.top/Article/details/gtldkokvjq.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.fzhhl.top/Article/details/gttvbdcixg.html

TS:   d.toISOString()
来源：http://dali.hysaishi.cn/Article/details/gtlzowdkaw.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.hnqzz.top/Article/details/gtsltxeopf.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.chenzaomai.com/Article/details/gtwaqvebqw.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.yonumen.top/Article/details/gtpzlytbkm.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.yj20258888.top/Article/details/gtpcnplfln.html

[J03] 字符串解析为日期
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcqournsp.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.aizwys.cn/Article/details/gtawbtwpks.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.gotoacloud.top/Article/details/gtrtexmdkt.html

JS:   new Date("2024-01-02")
来源：http://dali.jyoumei.cn/Article/details/gtvtpxmqzy.html

TS:   new Date("2024-01-02")
来源：http://dali.ehwqpu.com/Article/details/gthhopgggy.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.pycfn.com/Article/details/gtpqmehaax.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zhongyouzk.top/Article/details/gtwxignpik.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhoulong.xyz/Article/details/gtfnewyqmy.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.cashguo.top/Article/details/gtobfdgefd.html

[J04] 时间戳与日期互转
来源：http://dali.yj20258.top/Article/details/gtfqkujzek.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.fengsongda.top/Article/details/gtqusljqjz.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.nanxinkj.top/Article/details/gtvnjqdshi.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.hnqzz.top/Article/details/gttyjguggm.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.andypj.xyz/Article/details/gtlyswjutc.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.hnqzz.top/Article/details/gtorvxqpib.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.ivvv.top/Article/details/gtgqxhkaqx.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jinqigfzy.top/Article/details/gtfzicfrrg.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.chenzaomai.com/Article/details/gtdqipyzdk.html

[J05] 时间加减（加 7 天）
来源：http://dali.sweek.top/Article/details/gtfxfdjhfe.html

Py:   now + timedelta(days=7)
来源：http://dali.chenlongwang.top/Article/details/gteumwthyp.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmkuilwmh.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.svipenyu.cn/Article/details/gtoskxaeiz.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shuidangran.top/Article/details/gtrzccamra.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtumtnaiod.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.tanke756.top/Article/details/gtnrimtyoi.html

Ruby: Time.now + 7 * 86400
来源：http://dali.ehwqpu.com/Article/details/gtzkrhqlap.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.svipenyu.cn/Article/details/gtwpqwmexs.html

[J06] 计算两时间之差
来源：http://dali.shuidangran.top/Article/details/gtvqbbcvzv.html

Py:   (end - start).total_seconds()
来源：http://dali.aibaodan.cn/Article/details/gtjlqgofyq.html

PHP:  $end->diff($start)->days;
来源：http://dali.shangyingyoupin.top/Article/details/gtdxvfhgub.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yuanzhike.top/Article/details/gtzwswsadb.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.gogol.net.cn/Article/details/gtgdondeju.html


<!-- 参考信息 -->