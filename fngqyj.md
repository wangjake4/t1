代发 wailian999

PHP:  public static function f() {}
来源：http://dali.daxiang520.top/Article/details/gtuyityatm.html

JS:   static f() {}
来源：http://dali.bjfxy.top/Article/details/gtmeuypiur.html

TS:   static f(): void {}
来源：http://dali.quarkkingdee.top/Article/details/gtqfctfypf.html

Java: static void f() {}
来源：http://dali.meibo888.top/Article/details/gtbeoyvfaa.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.dianchejie.cn/Article/details/gtzpiybhdf.html

Ruby: def self.f; end
来源：http://dali.jiagoushi.top/Article/details/gtunvrnelw.html

C#:   public static void F() {}
来源：http://dali.smart0.xyz/Article/details/gtwzbpudcj.html

[G09] 接口 / 抽象类
来源：http://dali.sysykeji.top/Article/details/gtzyngkrun.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.316326.xyz/Article/details/gtxkwnmqph.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.gzhubu.top/Article/details/gtrrqhaind.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.pycfn.com/Article/details/gtguiqwalq.html

TS:   interface Shape { area(): number; }
来源：http://dali.ybcxt.top/Article/details/gtpdpkhdpj.html

Java: interface Shape { double area(); }
来源：http://dali.daria6918.cn/Article/details/gtpxskbbvg.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.ybcxt.top/Article/details/gttasaqclq.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.mhx1999.top/Article/details/gtbvfoaxyx.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhixingplan.top/Article/details/gtuajututt.html

[G10] 访问控制
来源：http://dali.gotoacloud.top/Article/details/gttchxlzkj.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.birdmap.top/Article/details/gtrcjuhwzt.html

PHP:  public / protected / private
来源：http://dali.chenjidiqi.icu/Article/details/gtlhhbbwko.html

JS:   #private 字段；其余公开
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtskqfzfba.html

TS:   public / protected / private
来源：http://dali.ehwqpu.com/Article/details/gtkcovybjc.html

Java: public / protected / private / 默认包级
来源：http://dali.gogol.net.cn/Article/details/gtixtxcrdy.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.daria6918.cn/Article/details/gtetzjbnnq.html

Ruby: public / protected / private
来源：http://dali.svipenyu.cn/Article/details/gtqxnzorem.html

C#:   public / protected / private / internal
来源：http://dali.kuanghao11.cn/Article/details/gtklprwguw.html

[G11] getter / setter
来源：http://dali.cucudq.cn/Article/details/gtxdlwdqak.html

Py:   @property 与 @x.setter
来源：http://dali.jlsjyb.cn/Article/details/gtojrxtyau.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.pycfn.com/Article/details/gtuczvcwvb.html

JS:   get name() { return this._name; }
来源：http://dali.birdmap.top/Article/details/gtlfslrclb.html

TS:   get name(): string { return this._name; }
来源：http://dali.gotoacloud.top/Article/details/gtsyofkhcn.html

Java: public String getName() { return name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtgefgsqlq.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.pycfn.com/Article/details/gtqecqlwck.html

Ruby: attr_accessor :name
来源：http://dali.nwbrower.top/Article/details/gtfgmaznhz.html

C#:   public string Name { get; set; }
来源：http://dali.yvedp.cn/Article/details/gtonipqkdf.html

[G12] 对象转字符串
来源：http://dali.wangshuangyany.cn/Article/details/gtfetdxdsl.html

Py:   def __str__(self): return self.name
来源：http://dali.jlsjyb.cn/Article/details/gtcuvunlcx.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.svipenyu.cn/Article/details/gtugmnnrsn.html

JS:   toString() { return this.name; }
来源：http://dali.redwolf501.top/Article/details/gtbpyabdse.html

TS:   toString(): string { return this.name; }
来源：http://dali.zycfv.cn/Article/details/gtfbondiec.html

Java: @Override public String toString() { return name; }
来源：http://dali.mhx1999.top/Article/details/gttstqcion.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.meibo888.top/Article/details/gtbiwgiskp.html

Ruby: def to_s; @name; end
来源：http://dali.gotoacloud.top/Article/details/gtgtmoepid.html

C#:   public override string ToString() => Name;
来源：http://dali.jianghu66.top/Article/details/gtaqpwmjef.html

[G13] 判断对象类型
来源：http://dali.gaohongyu789.top/Article/details/gtsaosirub.html

Py:   isinstance(u, User)
来源：http://dali.iojbl.cn/Article/details/gtofikthfl.html

PHP:  $u instanceof User
来源：http://dali.ehwqpu.com/Article/details/gtnvglpofj.html

JS:   u instanceof User
来源：http://dali.zdqjudy.top/Article/details/gtwfgtppkb.html

TS:   u instanceof User
来源：http://dali.cqqwz.cn/Article/details/gtgdgbovzo.html

Java: u instanceof User
来源：http://dali.ydzc1.top/Article/details/gtqtegqcys.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.shangyingyoupin.top/Article/details/gteiutpghp.html

Ruby: u.is_a?(User)
来源：http://dali.zdqjudy.top/Article/details/gtvvksjwqg.html

C#:   u is User
来源：http://dali.pycfn.com/Article/details/gtiqqclmjo.html

[G14] 数据类 / record
来源：http://dali.yuanzhike.top/Article/details/gtojwrdhhl.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhixingplan.top/Article/details/gtyrkcjwoc.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.nwbrower.top/Article/details/gthzviuyvw.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jianghu66.top/Article/details/gtwvgohyfo.html

TS:   type User = { name: string; age: number };
来源：http://dali.c1oappe.top/Article/details/gtebhiddwg.html

Java: record User(String name, int age) {}
来源：http://dali.xziqi.cn/Article/details/gtyniumtvz.html

Go:   type User struct { Name string; Age int }
来源：http://dali.shanyushiyangtech.top/Article/details/gtintvskco.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.iojbl.cn/Article/details/gtmfywuwjy.html

C#:   record User(string Name, int Age);
来源：http://dali.ydzc1.top/Article/details/gttqhyhvjt.html

[G15] 枚举
来源：http://dali.redwolf501.top/Article/details/gtqdvgnwlz.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgtyjgfwo.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jinqigufen.top/Article/details/gtapmvqhsn.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.haohaochexian.top/Article/details/gtzuvnwgcz.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.chenzaomai.com/Article/details/gtjazcxneu.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhoulong.xyz/Article/details/gtuzazgjwl.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.mhx1999.top/Article/details/gtqnkhlebf.html

Ruby: Color = %i[red green].freeze
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuzajtwks.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shangyingyoupin.top/Article/details/gtymmubisq.html

[G16] 对象转数组 / 字典
来源：http://dali.dashuyun.cn/Article/details/gtybpzclce.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.ppjwa.cn/Article/details/gtnujcrmpa.html

PHP:  get_object_vars($obj);
来源：http://dali.havefunace.top/Article/details/gtsooeguvv.html

JS:   Object.entries(obj)
来源：http://dali.cashguo.top/Article/details/gtkkqkvymi.html

TS:   Object.entries(obj)
来源：http://dali.aizwys.cn/Article/details/gtpmyyquxz.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.sweek.top/Article/details/gtmarxcpkn.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.nwbrower.top/Article/details/gtlihuxztr.html

Ruby: obj.instance_variables
来源：http://dali.wangshuangyany.cn/Article/details/gtowlhivvx.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.c1oappe.top/Article/details/gthidaqhkw.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtnczlwijn.html

H. 异常与错误处理
来源：http://dali.ehwqpu.com/Article/details/gtwuuvcxsa.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtziyngrnp.html

[H01] try / catch 基础
来源：http://dali.shangyingyoupin.top/Article/details/gtglfxlymc.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.cheryme.top/Article/details/gthotrrwgi.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtuwgnbter.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.sysykeji.top/Article/details/gtuxmlhpja.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.cqqwz.cn/Article/details/gtzrfjvtad.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.guannengcc.top/Article/details/gtefvtwldl.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.vqdsnc.cn/Article/details/gtjcstduts.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.mhx1999.top/Article/details/gtvccnixna.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ydzc1.top/Article/details/gtmzcikuea.html

[H02] finally / ensure 收尾
来源：http://dali.fzhhl.top/Article/details/gtmtbfhftf.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.sufxvd.cn/Article/details/gtlkwhvbgr.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.vqdsnc.cn/Article/details/gtvlnntwyc.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.tian-w.cn/Article/details/gtpzyqlgea.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.smart0.xyz/Article/details/gtxdyrpotq.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jianghu66.top/Article/details/gtuqmjyivc.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.vqdsnc.cn/Article/details/gthavnzduq.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhijiandao.cn/Article/details/gtedgpwkfg.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtcsaucjyf.html

[H03] 主动抛出异常
来源：http://dali.guannengcc.top/Article/details/gtrtthtbzn.html

Py:   raise ValueError("错误信息")
来源：http://dali.yj20258888.top/Article/details/gtjcfskrdc.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.cqqwz.cn/Article/details/gtoskchlmm.html

JS:   throw new Error("错误信息");
来源：http://dali.cqqwz.cn/Article/details/gtgvuktyjd.html

TS:   throw new Error("错误信息");
来源：http://dali.havefunace.top/Article/details/gtbmwirhnm.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.vqdsnc.cn/Article/details/gtddsiinvg.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.meibo888.top/Article/details/gtrjuebjkf.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.kuanghao11.cn/Article/details/gtfkgafjyo.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jianghu66.top/Article/details/gtjwplafds.html

[H04] 自定义异常类型
来源：http://dali.yueranfly.top/Article/details/gtuxruqxop.html

Py:   class MyError(Exception): pass
来源：http://dali.svipenyu.cn/Article/details/gtztnwbmwc.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.hysaishi.cn/Article/details/gterxvztkd.html

JS:   class MyError extends Error {}
来源：http://dali.haohaochexian.top/Article/details/gtgbokgjhy.html

TS:   class MyError extends Error {}
来源：http://dali.9152youxi.cn/Article/details/gtxtrpesys.html

Java: class MyException extends RuntimeException {}
来源：http://dali.tianlin.xyz/Article/details/gtbxtizhsh.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.dashuyun.cn/Article/details/gtubgurzxx.html

Ruby: class MyError < StandardError; end
来源：http://dali.iojbl.cn/Article/details/gtanebxaxs.html

C#:   class MyException : Exception {}
来源：http://dali.birdmap.top/Article/details/gtyzxpipdu.html

[H05] 捕获特定类型
来源：http://dali.hongshengwenyu.top/Article/details/gtfmnbvxti.html

Py:   except ValueError as e:
来源：http://dali.tianlin.xyz/Article/details/gtwxdvrann.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.gogol.net.cn/Article/details/gtsbgkydkd.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.nanxuanxn.top/Article/details/gtwmdlnufy.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.xinyue.icu/Article/details/gtsissakvj.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvmotomad.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zdqjudy.top/Article/details/gtyvnqwazx.html

Ruby: rescue ArgumentError => e
来源：http://dali.jlsjyb.cn/Article/details/gtzsxnvccq.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.dashuyun.cn/Article/details/gtimiluuol.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jinqigfzy.top/Article/details/gtlswlehzy.html

Py:   value = d.get("k") or default
来源：http://dali.zdqjudy.top/Article/details/gtqpqwaftr.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.cucudq.cn/Article/details/gttiqddkbf.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jqgufenzy.top/Article/details/gtvvitgghp.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.xuetiantiany.cn/Article/details/gtzslzquaj.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.feifeiyinyue.top/Article/details/gtdvyqzvoe.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.kuanghao11.cn/Article/details/gtistqropr.html

Ruby: d&.dig(:a, :b)
来源：http://dali.guannengcc.top/Article/details/gtghfhhiuw.html

C#:   obj?.A?.B ?? default
来源：http://dali.shangyingyoupin.top/Article/details/gtqyhfbvuw.html

[H07] 断言
来源：http://dali.hnqzz.top/Article/details/gtcctaifrp.html

Py:   assert x > 0, "必须为正"
来源：http://dali.hysaishi.cn/Article/details/gtkiycqhas.html

PHP:  assert($x > 0);
来源：http://dali.feifeiyinyue.top/Article/details/gtfvqolnur.html

JS:   console.assert(x > 0);
来源：http://dali.daria6918.cn/Article/details/gtlnkislnl.html

TS:   console.assert(x > 0);
来源：http://dali.yj20258.top/Article/details/gtffdrdyif.html

Java: assert x > 0 : "必须为正";
来源：http://dali.cheryme.top/Article/details/gthtooxbne.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.smart0.xyz/Article/details/gtkuklcnnh.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.mhx1999.top/Article/details/gtwiawzpic.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhiwuduotai.top/Article/details/gtxccxzvav.html

[H08] 获取错误信息与堆栈
来源：http://dali.jianghu66.top/Article/details/gtmniashvg.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jinqigfzy.top/Article/details/gtyuibhufn.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.ybcxt.top/Article/details/gtytfumglj.html

JS:   e.message;  e.stack
来源：http://dali.xuanzx.com/Article/details/gtizjcsvzt.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.bjfxy.top/Article/details/gtqldxvoly.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.nwbrower.top/Article/details/gtdszvmfab.html

Go:   err.Error()
来源：http://dali.hysaishi.cn/Article/details/gtcuwpetkd.html

Ruby: e.message;  e.backtrace
来源：http://dali.feifeiyinyue.top/Article/details/gtfyphlqkm.html

C#:   e.Message;  e.StackTrace
来源：http://dali.havefunace.top/Article/details/gtrnupwsju.html

[H09] 带错误码的异常
来源：http://dali.pengpengdd.cyou/Article/details/gtkdcjojkd.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.shuidangran.top/Article/details/gtlkasuwun.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.guannengcc.top/Article/details/gtorhxlxfb.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yj20258888.top/Article/details/gttsdxlopg.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.cheryme.top/Article/details/gtvdwktvot.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.daxiang520.top/Article/details/gtliihhrti.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhoulong.xyz/Article/details/gtgtcfqswx.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.chenzaomai.com/Article/details/gtffkfakos.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.hammf.cn/Article/details/gtpbmbqoqa.html

[H10] 资源自动释放
来源：http://dali.0kj1m.cn/Article/details/gtbercqdbw.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.ydzc1.top/Article/details/gtyvunoudw.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.cqqwz.cn/Article/details/gtcqzguhxx.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhiwuduotai.top/Article/details/gtyngsxpze.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sxryk.cn/Article/details/gtjxdgbord.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.cheryme.top/Article/details/gtynxuepgc.html

Go:   defer f.Close()
来源：http://dali.chenlongwang.top/Article/details/gtdjbsdsya.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfxyuxhvd.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ppjwa.cn/Article/details/gtkorekijs.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtmdjvbfxv.html

I. 正则表达式
来源：http://dali.dashuyun.cn/Article/details/gthoavhols.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtxpfnuzex.html

[I01] 判断是否匹配
来源：http://dali.shanyushiyangkeji.top/Article/details/gtagxxkwad.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.gzhubu.top/Article/details/gtkwhewpgy.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.ydzc1.top/Article/details/gtphimeimy.html

JS:   /\d+/.test(s)
来源：http://dali.tian-w.cn/Article/details/gtznyyxaii.html

TS:   /\d+/.test(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtkcntpruo.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.cashguo.top/Article/details/gtuwymaxet.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.pycfn.com/Article/details/gtqtzrqqhd.html

Ruby: s.match?(/\d+/)
来源：http://dali.hongshengwenyu.top/Article/details/gtkjvqysxo.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.kuanghao11.cn/Article/details/gtvfmbueng.html

[I02] 提取所有匹配
来源：http://dali.hfpthk.cn/Article/details/gtsmkywhzb.html

Py:   re.findall(r"\d+", s)
来源：http://dali.xuanzx.com/Article/details/gtjeuktctm.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zdqjudy.top/Article/details/gtywvnnmpg.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.aibaodan.cn/Article/details/gtndpyrmel.html

TS:   s.match(/\d+/g)
来源：http://dali.yuanzhike.top/Article/details/gtkxpbjrpq.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.daxiang520.top/Article/details/gtvykqbdyz.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.hfpthk.cn/Article/details/gtylkezykf.html

Ruby: s.scan(/\d+/)
来源：http://dali.nwbrower.top/Article/details/gteurquvlc.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.daxiang520.top/Article/details/gtwlkduuqn.html

[I03] 提取捕获分组
来源：http://dali.yanxiufei.cn/Article/details/gtcmynkykj.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtcphyiofa.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.quarkkingdee.top/Article/details/gthdxonwvw.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.tian-w.cn/Article/details/gtjlikiubb.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.havefunace.top/Article/details/gtviynwfme.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.sufxvd.cn/Article/details/gtwwyctgzh.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.haohaochexian.top/Article/details/gtgyluybjt.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gterconnsx.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jinqigufen.top/Article/details/gtndqfcnjn.html

[I04] 正则替换
来源：http://dali.gzhubu.top/Article/details/gtxpwejtph.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtusopbpzh.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.316326.xyz/Article/details/gtcizhwbad.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.hywenlv.cn/Article/details/gtxhpastjj.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zdqjudy.top/Article/details/gtpbugdixl.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.pycfn.com/Article/details/gtfniucjvk.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.nwbrower.top/Article/details/gtmeyxlodv.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.vqdsnc.cn/Article/details/gtrectcsgp.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.chenjidiqi.icu/Article/details/gtyapmpvst.html

[I05] 按正则拆分
来源：http://dali.dashuyun.cn/Article/details/gtkvmmlldh.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.redwolf501.top/Article/details/gtqwbleubw.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.nanxuanxn.top/Article/details/gtpydqtgaw.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.andypj.xyz/Article/details/gtfliwwany.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.yongpay.top/Article/details/gtrmdsbttf.html

Java: s.split("\\s*,\\s*")
来源：http://dali.sysykeji.top/Article/details/gtgvghhmmy.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.hnxiangtu.top/Article/details/gtonycmyos.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.quarkkingdee.top/Article/details/gtpiaicwus.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.haohaochexian.top/Article/details/gtopaoalhg.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.yangfankeji.com/Article/details/gtkolsrxuy.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.gaohongyu789.top/Article/details/gtcpzaiwvc.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.ydzc1.top/Article/details/gtdfonmyqb.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.havefunace.top/Article/details/gtdoopzafe.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.pycfn.com/Article/details/gtdpoccksf.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.xuanzx.com/Article/details/gtukaudrym.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.c1oappe.top/Article/details/gtotgnllyk.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.hammf.cn/Article/details/gtlmlwwwae.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.ivvv.top/Article/details/gtmwldjzfn.html

[I07] 忽略大小写与多行模式
来源：http://dali.bjfxy.top/Article/details/gtwtrlqgio.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.xuetiantiany.cn/Article/details/gttkmzrjld.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.zhixingplan.top/Article/details/gtbjalsfqt.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.c1oappe.top/Article/details/gtukpedxvq.html

TS:   /error/gim
来源：http://dali.xuetiantiany.cn/Article/details/gtzahmigak.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.xziqi.cn/Article/details/gtzgfxuohf.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.aibaodan.cn/Article/details/gtxxlblgok.html

Ruby: s.scan(/error/i)
来源：http://dali.bjfxy.top/Article/details/gtbztywnwq.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.haohaochexian.top/Article/details/gtrmiqcgdk.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.guannengcc.top/Article/details/gtndefwewj.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.iojbl.cn/Article/details/gttkybpcch.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.chenjidiqi.icu/Article/details/gtspisqllq.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.shanyushiyangtech.top/Article/details/gtrdrqlkra.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.aizwys.cn/Article/details/gtwqssclgo.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jinqigfzy.top/Article/details/gtssqejjui.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yueranfly.top/Article/details/gteraesicy.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yj20258.top/Article/details/gthiyxxnpc.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhiwuduotai.top/Article/details/gtohndaiwv.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtfvkgqzky.html

J. 日期与时间
来源：http://dali.yuxming.cn/Article/details/gtjlbplrax.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtrhxhmlvt.html

[J01] 获取当前时间
来源：http://dali.ywan-chungtsiang.top/Article/details/gtijkrquqv.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhixingplan.top/Article/details/gtaaysswlq.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.bjfxy.top/Article/details/gtopnhsceg.html

JS:   new Date();  Date.now()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrcrjechm.html

TS:   new Date();  Date.now()
来源：http://dali.0kj1m.cn/Article/details/gtpabrsykq.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.bjfxy.top/Article/details/gtiuisxeml.html

Go:   time.Now()
来源：http://dali.zhoulong.xyz/Article/details/gtltegqyvv.html

Ruby: Time.now
来源：http://dali.hnqzz.top/Article/details/gtbbchkaqr.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.cashguo.top/Article/details/gtinebzfeo.html

[J02] 格式化输出
来源：http://dali.hammf.cn/Article/details/gtabdutvty.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.andypj.xyz/Article/details/gtpvbwlejs.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.hongshengwenyu.top/Article/details/gtuzsfhiiw.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.hammf.cn/Article/details/gtnmndfbcq.html

TS:   d.toISOString()
来源：http://dali.cdnleiting.top/Article/details/gtywxaraeq.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.gzhubu.top/Article/details/gthlzyuaiz.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.cdnleiting.top/Article/details/gtjrklqisr.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.c1oappe.top/Article/details/gtyjdvbvzw.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.haohaochexian.top/Article/details/gtehxaqeus.html

[J03] 字符串解析为日期
来源：http://dali.smart0.xyz/Article/details/gtazvxdgif.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.hysaishi.cn/Article/details/gtfsszhryh.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.shzxlz.cn/Article/details/gtptlkdupn.html

JS:   new Date("2024-01-02")
来源：http://dali.jinqigfzy.top/Article/details/gteyejjfsd.html

TS:   new Date("2024-01-02")
来源：http://dali.birdmap.top/Article/details/gtzvbabupu.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.hnqzz.top/Article/details/gtyuklzxzd.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.cashguo.top/Article/details/gtocoepili.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.jqgufenzy.top/Article/details/gtvrriantr.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.sysykeji.top/Article/details/gtzscqquug.html

[J04] 时间戳与日期互转
来源：http://dali.yj20258.top/Article/details/gtfdogsauo.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhiwuduotai.top/Article/details/gtedtcfwyo.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.iojbl.cn/Article/details/gtoinkpwcx.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.cqqwz.cn/Article/details/gtvqkvmzzp.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.zdqjudy.top/Article/details/gtqthbztgz.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.birdmap.top/Article/details/gtxbzxnbhr.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhijiandao.cn/Article/details/gtqeqibvcn.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.xuetiantiany.cn/Article/details/gtisxdvfun.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.cucudq.cn/Article/details/gteadvzadp.html

[J05] 时间加减（加 7 天）
来源：http://dali.zycfv.cn/Article/details/gtbgolamqm.html

Py:   now + timedelta(days=7)
来源：http://dali.pengpengdd.cyou/Article/details/gtpzrkyulw.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.fengsongda.top/Article/details/gtcuivvlna.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.ybcxt.top/Article/details/gtfepstsav.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.chenjidiqi.icu/Article/details/gtzbvektwu.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.yj20258.top/Article/details/gtqpelbwzl.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jqgufenzy.top/Article/details/gteeqsgoov.html

Ruby: Time.now + 7 * 86400
来源：http://dali.jianghu66.top/Article/details/gtrmsgtdgu.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.hfpthk.cn/Article/details/gtdkorilfy.html

[J06] 计算两时间之差
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcuwvjgqg.html

Py:   (end - start).total_seconds()
来源：http://dali.hongshengwenyu.top/Article/details/gtfzwggdzr.html

PHP:  $end->diff($start)->days;
来源：http://dali.meibo888.top/Article/details/gtvrwrmrmm.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.hammf.cn/Article/details/gtgnzmvyvn.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnpfdtyvs.html


<!-- 参考信息 -->