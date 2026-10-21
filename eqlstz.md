代发 wailian999

Py:   class Admin(User): pass
来源：http://dali.xuetiantiany.cn/Article/details/gtoyvpybgv.html

PHP:  class Admin extends User {}
来源：http://dali.sysykeji.top/Article/details/gtxzpbvrhz.html

JS:   class Admin extends User {}
来源：http://dali.kuanghao11.cn/Article/details/gtvdwivzrx.html

TS:   class Admin extends User {}
来源：http://dali.chenjidiqi.icu/Article/details/gtcsuuktvf.html

Java: class Admin extends User {}
来源：http://dali.jiagoushi.top/Article/details/gtagbxkftt.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hnqzz.top/Article/details/gtjyqmfkxj.html

Ruby: class Admin < User; end
来源：http://dali.9152youxi.cn/Article/details/gtfziainsc.html

C#:   class Admin : User {}
来源：http://dali.sysykeji.top/Article/details/gtdtlcnqtq.html

[G06] 重写方法
来源：http://dali.316326.xyz/Article/details/gtqmjfnhcc.html

Py:   def greet(self): return "admin"
来源：http://dali.hongshengwenyu.top/Article/details/gtpbdqpfxz.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jlsjyb.cn/Article/details/gthumjofli.html

JS:   greet() { return "admin"; }
来源：http://dali.gzhubu.top/Article/details/gthwholazg.html

TS:   greet(): string { return "admin"; }
来源：http://dali.nanxuanxn.top/Article/details/gttuhdedkg.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhengqikj.top/Article/details/gtkwzizolg.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.shuidangran.top/Article/details/gtjhxxxpbk.html

Ruby: def greet; "admin"; end
来源：http://dali.ehwqpu.com/Article/details/gtumbozsxa.html

C#:   public override string Greet() => "admin";
来源：http://dali.hnxiangtu.top/Article/details/gtfzbaaalt.html

[G07] 调用父类方法
来源：http://dali.birdmap.top/Article/details/gtmynkixzd.html

Py:   super().greet()
来源：http://dali.jinghuilouyu.cn/Article/details/gttcmkvxnj.html

PHP:  parent::greet();
来源：http://dali.xuetiantiany.cn/Article/details/gthxbxatsq.html

JS:   super.greet();
来源：http://dali.yvedp.cn/Article/details/gtxdewzwem.html

TS:   super.greet();
来源：http://dali.iojbl.cn/Article/details/gtdfcbjsxg.html

Java: super.greet();
来源：http://dali.guowangkeji.top/Article/details/gtfjvihsdn.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.dashuyun.cn/Article/details/gtjifokcka.html

Ruby: super
来源：http://dali.xylfe.cn/Article/details/gtmpbanchs.html

C#:   base.Greet();
来源：http://dali.cashguo.top/Article/details/gtnfhgqyci.html

[G08] 静态方法与属性
来源：http://dali.mhx1999.top/Article/details/gtmkpsxjtz.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.sysykeji.top/Article/details/gtcpndggjl.html

PHP:  public static function f() {}
来源：http://dali.ybcxt.top/Article/details/gtsyfwzmxo.html

JS:   static f() {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjzrdbtwd.html

TS:   static f(): void {}
来源：http://dali.yvedp.cn/Article/details/gtvoougpjk.html

Java: static void f() {}
来源：http://dali.sxryk.cn/Article/details/gtrisjnmga.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.tian-w.cn/Article/details/gtdpupzhlh.html

Ruby: def self.f; end
来源：http://dali.chenzaomai.com/Article/details/gtvsfqlgxz.html

C#:   public static void F() {}
来源：http://dali.zhixingplan.top/Article/details/gtdoxmcrfm.html

[G09] 接口 / 抽象类
来源：http://dali.hfpthk.cn/Article/details/gtlzwkpnju.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.guowangkeji.top/Article/details/gthfrsyanw.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtelszflyy.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.gotoacloud.top/Article/details/gtspslarmf.html

TS:   interface Shape { area(): number; }
来源：http://dali.daxiang520.top/Article/details/gthxrejgid.html

Java: interface Shape { double area(); }
来源：http://dali.haohaochexian.top/Article/details/gtbstpswnc.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.svipenyu.cn/Article/details/gtsoejjboi.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hywenlv.cn/Article/details/gtyzgwqecf.html

C#:   interface IShape { double Area(); }
来源：http://dali.kuanghao11.cn/Article/details/gtaxhiuyna.html

[G10] 访问控制
来源：http://dali.hammf.cn/Article/details/gtnexslrtl.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yonumen.top/Article/details/gtatgndzha.html

PHP:  public / protected / private
来源：http://dali.sysykeji.top/Article/details/gtmhmrdjvz.html

JS:   #private 字段；其余公开
来源：http://dali.fengsongda.top/Article/details/gtcettczbf.html

TS:   public / protected / private
来源：http://dali.cdnleiting.top/Article/details/gtnmxiiacw.html

Java: public / protected / private / 默认包级
来源：http://dali.hysaishi.cn/Article/details/gtcgdlhbbf.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.cashguo.top/Article/details/gtbmbgljbn.html

Ruby: public / protected / private
来源：http://dali.aibaodan.cn/Article/details/gtqwpfjhgh.html

C#:   public / protected / private / internal
来源：http://dali.wangshuangyany.cn/Article/details/gtqfyfodfm.html

[G11] getter / setter
来源：http://dali.kuanghao11.cn/Article/details/gthrgfuqor.html

Py:   @property 与 @x.setter
来源：http://dali.jinqigfzy.top/Article/details/gtwaecxriw.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.nwbrower.top/Article/details/gttzlnlzua.html

JS:   get name() { return this._name; }
来源：http://dali.haohaochexian.top/Article/details/gtwwigmqpo.html

TS:   get name(): string { return this._name; }
来源：http://dali.yanxiufei.cn/Article/details/gtebihrjld.html

Java: public String getName() { return name; }
来源：http://dali.yj20258.top/Article/details/gtqrgkdisa.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.nanxuanxn.top/Article/details/gtrcwrhzka.html

Ruby: attr_accessor :name
来源：http://dali.shuidangran.top/Article/details/gtdfcpjcir.html

C#:   public string Name { get; set; }
来源：http://dali.9152youxi.cn/Article/details/gttmbxzbnj.html

[G12] 对象转字符串
来源：http://dali.aibaodan.cn/Article/details/gtcznkhwwh.html

Py:   def __str__(self): return self.name
来源：http://dali.jinghuilouyu.cn/Article/details/gthcbhdmrd.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zdqjudy.top/Article/details/gtnrolpxpj.html

JS:   toString() { return this.name; }
来源：http://dali.ivvv.top/Article/details/gtimgeqdxq.html

TS:   toString(): string { return this.name; }
来源：http://dali.pycfn.com/Article/details/gtenvifbso.html

Java: @Override public String toString() { return name; }
来源：http://dali.xinyue.icu/Article/details/gtacwpbtwy.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zycfv.cn/Article/details/gtwddfbdob.html

Ruby: def to_s; @name; end
来源：http://dali.zhengqikj.top/Article/details/gttwymieqd.html

C#:   public override string ToString() => Name;
来源：http://dali.daria6918.cn/Article/details/gtxxavobpk.html

[G13] 判断对象类型
来源：http://dali.fzhhl.top/Article/details/gtwsbdtgcj.html

Py:   isinstance(u, User)
来源：http://dali.yj202588.top/Article/details/gtmscbohzw.html

PHP:  $u instanceof User
来源：http://dali.xinyue.icu/Article/details/gtqkunacji.html

JS:   u instanceof User
来源：http://dali.gotoacloud.top/Article/details/gtnsvgrvfx.html

TS:   u instanceof User
来源：http://dali.ivvv.top/Article/details/gtpgevokgf.html

Java: u instanceof User
来源：http://dali.nanxinkj.top/Article/details/gtutdkijpo.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnbtsoavt.html

Ruby: u.is_a?(User)
来源：http://dali.cdnleiting.top/Article/details/gtqqkqvwgc.html

C#:   u is User
来源：http://dali.guowangkeji.top/Article/details/gtqbzwadqq.html

[G14] 数据类 / record
来源：http://dali.ppjwa.cn/Article/details/gtdlxwrgiu.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.wangdashe.top/Article/details/gtcbajozak.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.gaohongyu789.top/Article/details/gtuejrlhry.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.gogol.net.cn/Article/details/gtwiudnqha.html

TS:   type User = { name: string; age: number };
来源：http://dali.sweek.top/Article/details/gtufxgqbwp.html

Java: record User(String name, int age) {}
来源：http://dali.ydzc1.top/Article/details/gtrovrxjmx.html

Go:   type User struct { Name string; Age int }
来源：http://dali.daxiang520.top/Article/details/gtawzvhpxe.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hysaishi.cn/Article/details/gtrywcqqjj.html

C#:   record User(string Name, int Age);
来源：http://dali.hnxiangtu.top/Article/details/gtuwfnctsy.html

[G15] 枚举
来源：http://dali.wangdashe.top/Article/details/gtqqbzjdkb.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hysaishi.cn/Article/details/gtodbpsifu.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.sweek.top/Article/details/gthoslucej.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.tanke756.top/Article/details/gtkpobypew.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xuanzx.com/Article/details/gtgqwoirpl.html

Java: enum Color { RED, GREEN }
来源：http://dali.nanxuanxn.top/Article/details/gtiqotmyen.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.gzhubu.top/Article/details/gtqowdyzrx.html

Ruby: Color = %i[red green].freeze
来源：http://dali.kuanghao11.cn/Article/details/gtrkadwruc.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxcxawrbf.html

[G16] 对象转数组 / 字典
来源：http://dali.316326.xyz/Article/details/gtwlkomzeu.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yongpay.top/Article/details/gtxngcpugf.html

PHP:  get_object_vars($obj);
来源：http://dali.andypj.xyz/Article/details/gtuwvlgfmt.html

JS:   Object.entries(obj)
来源：http://dali.tian-w.cn/Article/details/gtrpvbddsx.html

TS:   Object.entries(obj)
来源：http://dali.jiagoushi.top/Article/details/gtcsrcttwq.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtivzjqiqj.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gtplnrblcf.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gtmrehlclz.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.nanxinkj.top/Article/details/gtjsbgzuzv.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtosekmrvo.html

H. 异常与错误处理
来源：http://dali.cdnleiting.top/Article/details/gtaraubpqo.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtjupkegpo.html

[H01] try / catch 基础
来源：http://dali.tianlin.xyz/Article/details/gtmylpsycu.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.316326.xyz/Article/details/gtqautmlxr.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhiwuduotai.top/Article/details/gtxujrysdw.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.vqdsnc.cn/Article/details/gtbmakvdwb.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.c1oappe.top/Article/details/gtsetkcdzq.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gtgetujxyj.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yueranfly.top/Article/details/gtumryyjud.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.cdnleiting.top/Article/details/gtoupxwshw.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.sysykeji.top/Article/details/gtbgyolqxv.html

[H02] finally / ensure 收尾
来源：http://dali.jqgufenzy.top/Article/details/gtrzejaghy.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.pengpengdd.cyou/Article/details/gtubpavoad.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.xuetiantiany.cn/Article/details/gtbxlqqweh.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ydzc1.top/Article/details/gtmgndqyka.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yangfankeji.com/Article/details/gtzbbdsgnk.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gtpnohulpa.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jyoumei.cn/Article/details/gthkznevfg.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.pengpengdd.cyou/Article/details/gteqlxrian.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtgeojormu.html

[H03] 主动抛出异常
来源：http://dali.yuanzhike.top/Article/details/gtabzjbayb.html

Py:   raise ValueError("错误信息")
来源：http://dali.havefunace.top/Article/details/gtpzldmxwd.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.snrcjt.cn/Article/details/gtgajeeglr.html

JS:   throw new Error("错误信息");
来源：http://dali.vqdsnc.cn/Article/details/gttexetrua.html

TS:   throw new Error("错误信息");
来源：http://dali.yuanzhike.top/Article/details/gtebytedqf.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.ivvv.top/Article/details/gtbaxhknhe.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.xuetiantiany.cn/Article/details/gtbobrbhdj.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yj20258888.top/Article/details/gturghstqf.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gtrhlwfqce.html

[H04] 自定义异常类型
来源：http://dali.hysaishi.cn/Article/details/gtetihhozm.html

Py:   class MyError(Exception): pass
来源：http://dali.yueranfly.top/Article/details/gttlvizmwf.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.kuanghao11.cn/Article/details/gtwnmbhfad.html

JS:   class MyError extends Error {}
来源：http://dali.zhoulong.xyz/Article/details/gtttnpgkpi.html

TS:   class MyError extends Error {}
来源：http://dali.shanyushiyangtech.top/Article/details/gthzydrhcw.html

Java: class MyException extends RuntimeException {}
来源：http://dali.shangyingyoupin.top/Article/details/gtlyqzotxx.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.guowangkeji.top/Article/details/gtffsnibqb.html

Ruby: class MyError < StandardError; end
来源：http://dali.meibo888.top/Article/details/gtbyqeuyej.html

C#:   class MyException : Exception {}
来源：http://dali.zycfv.cn/Article/details/gtzultupsf.html

[H05] 捕获特定类型
来源：http://dali.kuanghao11.cn/Article/details/gtnxmocnvl.html

Py:   except ValueError as e:
来源：http://dali.daria6918.cn/Article/details/gtpifzkgwy.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlfgsiteo.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.snrcjt.cn/Article/details/gtbkuyymij.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zdqjudy.top/Article/details/gtsazyfdlw.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.fengsongda.top/Article/details/gtdbrkqojs.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.smart0.xyz/Article/details/gtysponpoa.html

Ruby: rescue ArgumentError => e
来源：http://dali.yanxiufei.cn/Article/details/gtmuopyxxn.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yuxming.cn/Article/details/gtsedipvqg.html

[H06] 可选值 / 空值安全访问
来源：http://dali.c1oappe.top/Article/details/gtqdaynxfu.html

Py:   value = d.get("k") or default
来源：http://dali.birdmap.top/Article/details/gtakpgnnsy.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.guowangkeji.top/Article/details/gtshpajnrr.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.316326.xyz/Article/details/gtsesdforh.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.tanke756.top/Article/details/gtaegwoxam.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtasoaldtu.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yj202588.top/Article/details/gtlkmpigzt.html

Ruby: d&.dig(:a, :b)
来源：http://dali.birdmap.top/Article/details/gtoszauxlh.html

C#:   obj?.A?.B ?? default
来源：http://dali.ydzc1.top/Article/details/gtvwhdoifx.html

[H07] 断言
来源：http://dali.gzhubu.top/Article/details/gtukazzpxd.html

Py:   assert x > 0, "必须为正"
来源：http://dali.daria6918.cn/Article/details/gtjhnjajwl.html

PHP:  assert($x > 0);
来源：http://dali.xuetiantiany.cn/Article/details/gtrmmmvknc.html

JS:   console.assert(x > 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmounyfih.html

TS:   console.assert(x > 0);
来源：http://dali.zhiwuduotai.top/Article/details/gtkzkqwcmt.html

Java: assert x > 0 : "必须为正";
来源：http://dali.chenjidiqi.icu/Article/details/gtbiralsik.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.gotoacloud.top/Article/details/gtcymepumv.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jinghuilouyu.cn/Article/details/gtjswmbfex.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqmxbnzvl.html

[H08] 获取错误信息与堆栈
来源：http://dali.tianlin.xyz/Article/details/gtdqvaliof.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhongyouzk.top/Article/details/gtzhbjlvyc.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hysaishi.cn/Article/details/gttxfxdqao.html

JS:   e.message;  e.stack
来源：http://dali.yuanzhike.top/Article/details/gtlxfjatst.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.nanxuanxn.top/Article/details/gthkpvyfpb.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.chenjidiqi.icu/Article/details/gtvfbsvsiv.html

Go:   err.Error()
来源：http://dali.9152youxi.cn/Article/details/gttvfttauq.html

Ruby: e.message;  e.backtrace
来源：http://dali.jinqigufen.top/Article/details/gtjrqspomw.html

C#:   e.Message;  e.StackTrace
来源：http://dali.shanyushiyangtech.top/Article/details/gtairrvxcw.html

[H09] 带错误码的异常
来源：http://dali.svipenyu.cn/Article/details/gtpwfytizh.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhongyouzk.top/Article/details/gtfypjypzl.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.ivvv.top/Article/details/gtwhiaohpi.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.xylfe.cn/Article/details/gtlezubwuo.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jqgfzy.top/Article/details/gtpmhbdwtc.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.bjfxy.top/Article/details/gtgzaohqsn.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.fzhhl.top/Article/details/gtmbzbrrao.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.cucudq.cn/Article/details/gtzefsujqz.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.nwbrower.top/Article/details/gttsbiszjt.html

[H10] 资源自动释放
来源：http://dali.vqdsnc.cn/Article/details/gtauekidvt.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yanxiufei.cn/Article/details/gtsnhpzeuv.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.dianchejie.cn/Article/details/gtxnpwcier.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.birdmap.top/Article/details/gtpbzgdzsa.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.svipenyu.cn/Article/details/gtpdibuksf.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.chenzaomai.com/Article/details/gtoyejxhwh.html

Go:   defer f.Close()
来源：http://dali.jlsjyb.cn/Article/details/gtxirgyklr.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.meibo888.top/Article/details/gtjwedftyk.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.guannengcc.top/Article/details/gtzexcxyqh.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtdqryrggm.html

I. 正则表达式
来源：http://dali.daxiang520.top/Article/details/gtxvkcwecf.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtzveixkfd.html

[I01] 判断是否匹配
来源：http://dali.shuidangran.top/Article/details/gtiymuxjsi.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.nanxuanxn.top/Article/details/gtfhvslnnr.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.dashuyun.cn/Article/details/gtcfluugri.html

JS:   /\d+/.test(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gttnfartbx.html

TS:   /\d+/.test(s)
来源：http://dali.zhengqikj.top/Article/details/gtlczczowe.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.hammf.cn/Article/details/gtznzetrje.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.nanxinkj.top/Article/details/gttlayrpyl.html

Ruby: s.match?(/\d+/)
来源：http://dali.0kj1m.cn/Article/details/gtxuycppyg.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.hnqzz.top/Article/details/gtysqhxasi.html

[I02] 提取所有匹配
来源：http://dali.xziqi.cn/Article/details/gtztlkblti.html

Py:   re.findall(r"\d+", s)
来源：http://dali.shzxlz.cn/Article/details/gtkwuwstxn.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.cheryme.top/Article/details/gtffqlhzdt.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.aizwys.cn/Article/details/gtuqrquufp.html

TS:   s.match(/\d+/g)
来源：http://dali.nanxuanxn.top/Article/details/gtnzekfgtt.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtooqejbuj.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.mhx1999.top/Article/details/gtmgsovzmc.html

Ruby: s.scan(/\d+/)
来源：http://dali.hnxiangtu.top/Article/details/gtawdlmelc.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.ybcxt.top/Article/details/gtwlhnygpo.html

[I03] 提取捕获分组
来源：http://dali.shuidangran.top/Article/details/gtkqgogrih.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtabpwosbo.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.ppjwa.cn/Article/details/gtwhiclqix.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.feifeiyinyue.top/Article/details/gtptvdizwk.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.birdmap.top/Article/details/gthgptefzd.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhengqikj.top/Article/details/gtteexpghv.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjtrneetp.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.ydzc1.top/Article/details/gtymctuvfb.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.pycfn.com/Article/details/gtaltyxijw.html

[I04] 正则替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gticpflfeo.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.gzhubu.top/Article/details/gtmrtomzjr.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.kuanghao11.cn/Article/details/gtsyuxnnay.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcqjhgubb.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.svipenyu.cn/Article/details/gtloxbxzuu.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.ivvv.top/Article/details/gttbeolgfz.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.wangdashe.top/Article/details/gtwwbxqxpj.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.mhx1999.top/Article/details/gtgewtkxnm.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.pengpengdd.cyou/Article/details/gtbtdvnleq.html

[I05] 按正则拆分
来源：http://dali.c1oappe.top/Article/details/gtllwrgnoi.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.andypj.xyz/Article/details/gtbbqwgmnj.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yvedp.cn/Article/details/gtvqgjbsuu.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.pycfn.com/Article/details/gtlwcuyblh.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zhongyouzk.top/Article/details/gtelxkwjvg.html

Java: s.split("\\s*,\\s*")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtycsfiqpb.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.nanxuanxn.top/Article/details/gtkhidplev.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.zhengqikj.top/Article/details/gtnuomumal.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.zhengqikj.top/Article/details/gtllqeefav.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.vqdsnc.cn/Article/details/gtubiepvpv.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.jianghu66.top/Article/details/gtvzzcoktv.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.jinghuilouyu.cn/Article/details/gtosoiljdh.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.tanke756.top/Article/details/gtummwjhwv.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.kuanghao11.cn/Article/details/gtmgkvehec.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.feifeiyinyue.top/Article/details/gteabyoibl.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.aibaodan.cn/Article/details/gthuccctkl.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.cucudq.cn/Article/details/gtomtafnhe.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.guannengcc.top/Article/details/gtiakvbgiq.html

[I07] 忽略大小写与多行模式
来源：http://dali.andypj.xyz/Article/details/gtqyjwbuut.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jinqigfzy.top/Article/details/gtreigswiu.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.cheryme.top/Article/details/gtyxfcvygs.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.pengpengdd.cyou/Article/details/gtvdyduygm.html

TS:   /error/gim
来源：http://dali.zhoulong.xyz/Article/details/gtnnpiecgt.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvfcswnrq.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.sysykeji.top/Article/details/gtvecafyva.html

Ruby: s.scan(/error/i)
来源：http://dali.ppjwa.cn/Article/details/gtssnozbag.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.hnxiangtu.top/Article/details/gtaiwxddqq.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.dashuyun.cn/Article/details/gtramseebt.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.redwolf501.top/Article/details/gtwjfhidia.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.shuidangran.top/Article/details/gtygxedusl.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zdqjudy.top/Article/details/gtsndgumku.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.nanxinkj.top/Article/details/gtlychydex.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.svipenyu.cn/Article/details/gtbyjcfipm.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.gotoacloud.top/Article/details/gtqjvgrytp.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.mhx1999.top/Article/details/gtwdzrgnic.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.mhx1999.top/Article/details/gtfyxyahza.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtdlvyxayj.html

J. 日期与时间
来源：http://dali.yonumen.top/Article/details/gtslvbrrfm.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtbhemmabw.html

[J01] 获取当前时间
来源：http://dali.meibo888.top/Article/details/gtitwjgsnc.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.tianlin.xyz/Article/details/gtylxadhnv.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.jinqigufen.top/Article/details/gtgweatmof.html

JS:   new Date();  Date.now()
来源：http://dali.guannengcc.top/Article/details/gtkabpirrm.html

TS:   new Date();  Date.now()
来源：http://dali.daria6918.cn/Article/details/gtnosgvztt.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.fzhhl.top/Article/details/gtzvinvfjf.html

Go:   time.Now()
来源：http://dali.vqdsnc.cn/Article/details/gtedlooqbu.html

Ruby: Time.now
来源：http://dali.cheryme.top/Article/details/gtpngytgyg.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.xuetiantiany.cn/Article/details/gtvirnogjd.html

[J02] 格式化输出
来源：http://dali.ppjwa.cn/Article/details/gtlcymlddk.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xinyue.icu/Article/details/gtctbqzlrq.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.ybcxt.top/Article/details/gtqxqztats.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.c1oappe.top/Article/details/gtmchnunvd.html

TS:   d.toISOString()
来源：http://dali.jyoumei.cn/Article/details/gtumbcprfo.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.xuanzx.com/Article/details/gtrsobbzlc.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.mhx1999.top/Article/details/gtjeighclr.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.gotoacloud.top/Article/details/gtgaohcuse.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.daria6918.cn/Article/details/gtfnexgruw.html

[J03] 字符串解析为日期
来源：http://dali.sysykeji.top/Article/details/gtbhyjmghv.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.hywenlv.cn/Article/details/gtnxalvape.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hysaishi.cn/Article/details/gtakjrcifk.html

JS:   new Date("2024-01-02")
来源：http://dali.yuanzhike.top/Article/details/gtvdqnozel.html


<!-- 参考信息 -->