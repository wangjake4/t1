代发 wailian999

Py:   class User: pass
来源：http://dali.cashguo.top/Article/details/gtgcatoboi.html

PHP:  class User {}
来源：http://dali.dashuyun.cn/Article/details/gtqtmpxdsx.html

JS:   class User {}
来源：http://dali.hnxiangtu.top/Article/details/gtdbtkmibw.html

TS:   class User { name: string = ""; }
来源：http://dali.yanxiufei.cn/Article/details/gtscsufgvf.html

Java: class User {}
来源：http://dali.gotoacloud.top/Article/details/gtbszissdk.html

Go:   type User struct { Name string }
来源：http://dali.hnqzz.top/Article/details/gtxdrsnycl.html

Ruby: class User; end
来源：http://dali.316326.xyz/Article/details/gtcvltwikl.html

C#:   class User {}
来源：http://dali.bjfxy.top/Article/details/gtbkvraukb.html

[G02] 构造函数
来源：http://dali.wangdashe.top/Article/details/gtdgjjlxnm.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.shangyingyoupin.top/Article/details/gtrqjpycgj.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.ydzc1.top/Article/details/gtgyjqauir.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.havefunace.top/Article/details/gtdjidafws.html

TS:   constructor(public name: string) {}
来源：http://dali.xziqi.cn/Article/details/gtdpbpvblv.html

Java: User(String name) { this.name = name; }
来源：http://dali.kuanghao11.cn/Article/details/gtlrrkzjlj.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.iojbl.cn/Article/details/gtklvcicbe.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jqgfzy.top/Article/details/gtjxcrslql.html

C#:   public User(string name) { Name = name; }
来源：http://dali.quarkkingdee.top/Article/details/gtnqoxejnp.html

[G03] 实例属性
来源：http://dali.chenzaomai.com/Article/details/gthwzfjlat.html

Py:   self.name = "x"
来源：http://dali.yuanzhike.top/Article/details/gtdniuoesm.html

PHP:  public string $name = "x";
来源：http://dali.haohaochexian.top/Article/details/gtsrhniona.html

JS:   this.name = "x";
来源：http://dali.hnqzz.top/Article/details/gtxeqcbxcn.html

TS:   name: string = "x";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlmbrlyuz.html

Java: private String name;
来源：http://dali.xylfe.cn/Article/details/gtnvybqthd.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hysaishi.cn/Article/details/gtvqxhmsxu.html

Ruby: @name = "x"
来源：http://dali.9152youxi.cn/Article/details/gtutilvvch.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yj202588.top/Article/details/gtzolvpaey.html

[G04] 定义方法
来源：http://dali.jinqigufen.top/Article/details/gtkylpzgkm.html

Py:   def greet(self): return self.name
来源：http://dali.9152youxi.cn/Article/details/gtshmuiwhh.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.cheryme.top/Article/details/gttesjcvmf.html

JS:   greet() { return this.name; }
来源：http://dali.shzxlz.cn/Article/details/gtfvploecj.html

TS:   greet(): string { return this.name; }
来源：http://dali.jianghu66.top/Article/details/gtiohupana.html

Java: String greet() { return name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwioegxds.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.meibo888.top/Article/details/gtxsvkwbfm.html

Ruby: def greet; @name; end
来源：http://dali.sxryk.cn/Article/details/gtrsepaycq.html

C#:   public string Greet() => Name;
来源：http://dali.jinqigfzy.top/Article/details/gtcokrhdqe.html

[G05] 继承
来源：http://dali.jinqigufen.top/Article/details/gtsbmymraq.html

Py:   class Admin(User): pass
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuhawurhf.html

PHP:  class Admin extends User {}
来源：http://dali.bjfxy.top/Article/details/gtsbyatdcd.html

JS:   class Admin extends User {}
来源：http://dali.birdmap.top/Article/details/gtwscwsyok.html

TS:   class Admin extends User {}
来源：http://dali.hammf.cn/Article/details/gthtdqreqd.html

Java: class Admin extends User {}
来源：http://dali.wangshuangyany.cn/Article/details/gtsiedxadv.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.nwbrower.top/Article/details/gttxcfpvyd.html

Ruby: class Admin < User; end
来源：http://dali.feifeiyinyue.top/Article/details/gtxzaqgper.html

C#:   class Admin : User {}
来源：http://dali.hywenlv.cn/Article/details/gtqeroiyrq.html

[G06] 重写方法
来源：http://dali.tian-w.cn/Article/details/gttwcmhnpg.html

Py:   def greet(self): return "admin"
来源：http://dali.zhixingplan.top/Article/details/gtvskttgvm.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yuanzhike.top/Article/details/gtaapibeox.html

JS:   greet() { return "admin"; }
来源：http://dali.yuxming.cn/Article/details/gttjshscsx.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yonumen.top/Article/details/gtmsiydnjx.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhengqikj.top/Article/details/gtanbkeixq.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.feifeiyinyue.top/Article/details/gtjotcztwe.html

Ruby: def greet; "admin"; end
来源：http://dali.vqdsnc.cn/Article/details/gtdurcndod.html

C#:   public override string Greet() => "admin";
来源：http://dali.redwolf501.top/Article/details/gttmsekumm.html

[G07] 调用父类方法
来源：http://dali.hammf.cn/Article/details/gtbwewpfex.html

Py:   super().greet()
来源：http://dali.jlsjyb.cn/Article/details/gtmhqevtqw.html

PHP:  parent::greet();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtffdnsrow.html

JS:   super.greet();
来源：http://dali.aizwys.cn/Article/details/gtlgdfjfpq.html

TS:   super.greet();
来源：http://dali.andypj.xyz/Article/details/gtwnmurift.html

Java: super.greet();
来源：http://dali.zhixingplan.top/Article/details/gtrevhamvj.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.birdmap.top/Article/details/gtvrfcsokf.html

Ruby: super
来源：http://dali.cucudq.cn/Article/details/gtbgxjeoyt.html

C#:   base.Greet();
来源：http://dali.jlsjyb.cn/Article/details/gtiorxckno.html

[G08] 静态方法与属性
来源：http://dali.yongpay.top/Article/details/gtazmilhhd.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.guannengcc.top/Article/details/gtgdectnou.html

PHP:  public static function f() {}
来源：http://dali.zhiwuduotai.top/Article/details/gtfnvaggku.html

JS:   static f() {}
来源：http://dali.birdmap.top/Article/details/gtvyvbhmpa.html

TS:   static f(): void {}
来源：http://dali.pycfn.com/Article/details/gtwgugecvg.html

Java: static void f() {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gturzqaxzu.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrfeiwdxe.html

Ruby: def self.f; end
来源：http://dali.gaohongyu789.top/Article/details/gtpjbuzrhm.html

C#:   public static void F() {}
来源：http://dali.xinyue.icu/Article/details/gtqcvpnjsd.html

[G09] 接口 / 抽象类
来源：http://dali.ybcxt.top/Article/details/gtdgkogcve.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yonumen.top/Article/details/gtooudybnk.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.mhx1999.top/Article/details/gtmcjkbtem.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.cucudq.cn/Article/details/gtjaszlyfm.html

TS:   interface Shape { area(): number; }
来源：http://dali.yonumen.top/Article/details/gternxqhce.html

Java: interface Shape { double area(); }
来源：http://dali.hywenlv.cn/Article/details/gtgxjyffzt.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hnxiangtu.top/Article/details/gtsmhlfwfq.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhengqikj.top/Article/details/gtjgfzbfvf.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhongyouzk.top/Article/details/gtueunotxq.html

[G10] 访问控制
来源：http://dali.c1oappe.top/Article/details/gtsfewdqlp.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.pycfn.com/Article/details/gtzdybcakx.html

PHP:  public / protected / private
来源：http://dali.ivvv.top/Article/details/gtgzaeddzz.html

JS:   #private 字段；其余公开
来源：http://dali.feifeiyinyue.top/Article/details/gtqyvpmmcp.html

TS:   public / protected / private
来源：http://dali.yj20258888.top/Article/details/gtswvzwhuq.html

Java: public / protected / private / 默认包级
来源：http://dali.hnxiangtu.top/Article/details/gtpmishszf.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.dashuyun.cn/Article/details/gtimizjixi.html

Ruby: public / protected / private
来源：http://dali.chenjidiqi.icu/Article/details/gthqxosevs.html

C#:   public / protected / private / internal
来源：http://dali.yuxming.cn/Article/details/gtcmgligwu.html

[G11] getter / setter
来源：http://dali.yuxming.cn/Article/details/gtbdenexnp.html

Py:   @property 与 @x.setter
来源：http://dali.pengpengdd.cyou/Article/details/gtmypgcmlt.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.cashguo.top/Article/details/gtcdghljkf.html

JS:   get name() { return this._name; }
来源：http://dali.jinqigfzy.top/Article/details/gtklgfjziw.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgsekmvbl.html

Java: public String getName() { return name; }
来源：http://dali.zdqjudy.top/Article/details/gtectismgf.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.wangshuangyany.cn/Article/details/gtauecfirq.html

Ruby: attr_accessor :name
来源：http://dali.bjfxy.top/Article/details/gtkdxjkony.html

C#:   public string Name { get; set; }
来源：http://dali.cqqwz.cn/Article/details/gtlrqezyio.html

[G12] 对象转字符串
来源：http://dali.sweek.top/Article/details/gtjitxwnxf.html

Py:   def __str__(self): return self.name
来源：http://dali.gotoacloud.top/Article/details/gtpbpacpbp.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yj202588.top/Article/details/gtixmlkcke.html

JS:   toString() { return this.name; }
来源：http://dali.aizwys.cn/Article/details/gtinugybve.html

TS:   toString(): string { return this.name; }
来源：http://dali.0kj1m.cn/Article/details/gtzidklikr.html

Java: @Override public String toString() { return name; }
来源：http://dali.kuanghao11.cn/Article/details/gtbzvvtjpc.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.redwolf501.top/Article/details/gthsqsqtxo.html

Ruby: def to_s; @name; end
来源：http://dali.sysykeji.top/Article/details/gtmmvkpddy.html

C#:   public override string ToString() => Name;
来源：http://dali.shanyushiyangtech.top/Article/details/gtdmzasjcs.html

[G13] 判断对象类型
来源：http://dali.dashuyun.cn/Article/details/gtgqnwhqlb.html

Py:   isinstance(u, User)
来源：http://dali.cheryme.top/Article/details/gtusvqrnas.html

PHP:  $u instanceof User
来源：http://dali.zycfv.cn/Article/details/gtfnwemjlc.html

JS:   u instanceof User
来源：http://dali.haohaochexian.top/Article/details/gtcxkxsilm.html

TS:   u instanceof User
来源：http://dali.yvedp.cn/Article/details/gtgaezqmhk.html

Java: u instanceof User
来源：http://dali.cdnleiting.top/Article/details/gtyjtjftsk.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.fengsongda.top/Article/details/gtvildvsiz.html

Ruby: u.is_a?(User)
来源：http://dali.aizwys.cn/Article/details/gtrtxssfnm.html

C#:   u is User
来源：http://dali.c1oappe.top/Article/details/gtlcyfrmtz.html

[G14] 数据类 / record
来源：http://dali.pengpengdd.cyou/Article/details/gthrhrbdyq.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.bjfxy.top/Article/details/gtpjdayhkd.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.vqdsnc.cn/Article/details/gtaxwiejvg.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.c1oappe.top/Article/details/gtygtvyrzz.html

TS:   type User = { name: string; age: number };
来源：http://dali.sysykeji.top/Article/details/gtxaczotfb.html

Java: record User(String name, int age) {}
来源：http://dali.birdmap.top/Article/details/gtjoozaxby.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hnqzz.top/Article/details/gtxyolhnxr.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.haohaochexian.top/Article/details/gtusahhwgk.html

C#:   record User(string Name, int Age);
来源：http://dali.xziqi.cn/Article/details/gtygpefvub.html

[G15] 枚举
来源：http://dali.yj20258888.top/Article/details/gtarwlvrpl.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jianghu66.top/Article/details/gtfbeshhgg.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.sxryk.cn/Article/details/gtxeemuyts.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.tanke756.top/Article/details/gtyzxtztxc.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.nanxinkj.top/Article/details/gtwicctocp.html

Java: enum Color { RED, GREEN }
来源：http://dali.xylfe.cn/Article/details/gtmstiimiw.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.gzhubu.top/Article/details/gthyizzjyh.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jlsjyb.cn/Article/details/gtgivjmbmx.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.dianchejie.cn/Article/details/gtumszjhel.html

[G16] 对象转数组 / 字典
来源：http://dali.tianlin.xyz/Article/details/gtfmjakzvk.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yvedp.cn/Article/details/gtylzcgrve.html

PHP:  get_object_vars($obj);
来源：http://dali.ywan-chungtsiang.top/Article/details/gttgahtfpv.html

JS:   Object.entries(obj)
来源：http://dali.andypj.xyz/Article/details/gttaslnwrn.html

TS:   Object.entries(obj)
来源：http://dali.snrcjt.cn/Article/details/gtcsafxpmh.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jinqigufen.top/Article/details/gtwimwiceh.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.chenzaomai.com/Article/details/gtizsvogzs.html

Ruby: obj.instance_variables
来源：http://dali.svipenyu.cn/Article/details/gtdsfcgewe.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.gzhubu.top/Article/details/gtcudxxujb.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtqnpiyhxu.html

H. 异常与错误处理
来源：http://dali.tian-w.cn/Article/details/gtzxfhbbvb.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtvqrmyftc.html

[H01] try / catch 基础
来源：http://dali.tian-w.cn/Article/details/gtvzhgddtf.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yongpay.top/Article/details/gtdyshyosc.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.hywenlv.cn/Article/details/gtolurjrqr.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.cashguo.top/Article/details/gtodxefulj.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.ehwqpu.com/Article/details/gtwqnopujv.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.sweek.top/Article/details/gtkebcahay.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.sxryk.cn/Article/details/gtwvjoaack.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.gogol.net.cn/Article/details/gtrrynzasy.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.nanxinkj.top/Article/details/gtnpdwmlqi.html

[H02] finally / ensure 收尾
来源：http://dali.hongshengwenyu.top/Article/details/gthonpkhjo.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.chenzaomai.com/Article/details/gtjhjyvgny.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtztxqaotk.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.tianlin.xyz/Article/details/gtzccmlwqt.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.sweek.top/Article/details/gtvmmpgqix.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtskbijuuh.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.cucudq.cn/Article/details/gtphlekbnt.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.daxiang520.top/Article/details/gtnmsnczlp.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyaikxlnq.html

[H03] 主动抛出异常
来源：http://dali.birdmap.top/Article/details/gthorhuize.html

Py:   raise ValueError("错误信息")
来源：http://dali.bjfxy.top/Article/details/gthqqqmcqp.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hywenlv.cn/Article/details/gthplikpgb.html

JS:   throw new Error("错误信息");
来源：http://dali.iojbl.cn/Article/details/gtudibzaig.html

TS:   throw new Error("错误信息");
来源：http://dali.guannengcc.top/Article/details/gtybtxwfhk.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.redwolf501.top/Article/details/gtxhcipkwf.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmvrrrsqf.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.dashuyun.cn/Article/details/gtgyubqkhl.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.wangdashe.top/Article/details/gtsgveilip.html

[H04] 自定义异常类型
来源：http://dali.gotoacloud.top/Article/details/gtlffidvkj.html

Py:   class MyError(Exception): pass
来源：http://dali.jlsjyb.cn/Article/details/gtrqkifbkp.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.c1oappe.top/Article/details/gtwtjnzugf.html

JS:   class MyError extends Error {}
来源：http://dali.vqdsnc.cn/Article/details/gtbxdcskiw.html

TS:   class MyError extends Error {}
来源：http://dali.shuidangran.top/Article/details/gtciemqatt.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jqgfzy.top/Article/details/gthmuqcfxl.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yj20258.top/Article/details/gtgwlbsgtb.html

Ruby: class MyError < StandardError; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtfzsnakrx.html

C#:   class MyException : Exception {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdszveuoc.html

[H05] 捕获特定类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfwragisk.html

Py:   except ValueError as e:
来源：http://dali.yuanzhike.top/Article/details/gtyloifdpi.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yongpay.top/Article/details/gtqklqqbcg.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jqgufenzy.top/Article/details/gtrluoendd.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.svipenyu.cn/Article/details/gtxnzrdamj.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.aizwys.cn/Article/details/gtolptxuse.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.snrcjt.cn/Article/details/gtmpcqvfbk.html

Ruby: rescue ArgumentError => e
来源：http://dali.c1oappe.top/Article/details/gtnvgtfalh.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwcsclfqb.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jinqigfzy.top/Article/details/gtvsgferky.html

Py:   value = d.get("k") or default
来源：http://dali.xziqi.cn/Article/details/gtyhqggpbl.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jqgufenzy.top/Article/details/gtxyvudxbu.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yuanzhike.top/Article/details/gtpwbomxxz.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.daxiang520.top/Article/details/gtvpulryll.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yvedp.cn/Article/details/gtssxvxyfo.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.feifeiyinyue.top/Article/details/gtqpvewebw.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yanxiufei.cn/Article/details/gtryybmjvi.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhoulong.xyz/Article/details/gtwuzpjyxc.html

[H07] 断言
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmbtauerr.html

Py:   assert x > 0, "必须为正"
来源：http://dali.quarkkingdee.top/Article/details/gtjvlgxxml.html

PHP:  assert($x > 0);
来源：http://dali.jinqigfzy.top/Article/details/gtoujgebmt.html

JS:   console.assert(x > 0);
来源：http://dali.jianghu66.top/Article/details/gtrlhxplhn.html

TS:   console.assert(x > 0);
来源：http://dali.hysaishi.cn/Article/details/gtojgougpe.html

Java: assert x > 0 : "必须为正";
来源：http://dali.svipenyu.cn/Article/details/gtmzwitwwj.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhixingplan.top/Article/details/gtvppjejov.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yongpay.top/Article/details/gtyqlzkdoh.html

C#:   Debug.Assert(x > 0);
来源：http://dali.svipenyu.cn/Article/details/gtvndxwbyq.html

[H08] 获取错误信息与堆栈
来源：http://dali.havefunace.top/Article/details/gtxlrazifa.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.nanxuanxn.top/Article/details/gtvyqfxxgn.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.ivvv.top/Article/details/gthumbevqj.html

JS:   e.message;  e.stack
来源：http://dali.hysaishi.cn/Article/details/gtncasrfik.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.sxryk.cn/Article/details/gtoivxkugf.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.daria6918.cn/Article/details/gtqpyncxtt.html

Go:   err.Error()
来源：http://dali.sxryk.cn/Article/details/gtcreeqyhu.html

Ruby: e.message;  e.backtrace
来源：http://dali.hnxiangtu.top/Article/details/gtapsjlelj.html

C#:   e.Message;  e.StackTrace
来源：http://dali.cheryme.top/Article/details/gtwakljsrq.html

[H09] 带错误码的异常
来源：http://dali.dianchejie.cn/Article/details/gtbnxsoqxm.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.sysykeji.top/Article/details/gttrmhqppd.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jlsjyb.cn/Article/details/gtyfkcjdls.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.birdmap.top/Article/details/gtmvxyqqaj.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.smart0.xyz/Article/details/gtnhpqtvmp.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.cheryme.top/Article/details/gtiaexaeyq.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.pengpengdd.cyou/Article/details/gtadrgkxyp.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.nwbrower.top/Article/details/gtbhtfwhly.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.birdmap.top/Article/details/gtprxrumnf.html

[H10] 资源自动释放
来源：http://dali.sweek.top/Article/details/gtsqunkzle.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.shanyushiyangtech.top/Article/details/gtcdiazdqs.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.quarkkingdee.top/Article/details/gtnfhbhnxz.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.fzhhl.top/Article/details/gtpxxywbgb.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.c1oappe.top/Article/details/gtmbntoqyh.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yj20258.top/Article/details/gtmcpqwpoh.html

Go:   defer f.Close()
来源：http://dali.vqdsnc.cn/Article/details/gttwrohzxi.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.aibaodan.cn/Article/details/gtlnzfoueb.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yuxming.cn/Article/details/gtyyvkqxtc.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtgijcxqqd.html

I. 正则表达式
来源：http://dali.yonumen.top/Article/details/gtstgcfipq.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gthvllctxb.html

[I01] 判断是否匹配
来源：http://dali.shuidangran.top/Article/details/gtpvzwdiqa.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.gzhubu.top/Article/details/gtauerceuy.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.hnxiangtu.top/Article/details/gtbpbkgmrn.html

JS:   /\d+/.test(s)
来源：http://dali.hnqzz.top/Article/details/gtpyhzjzsk.html

TS:   /\d+/.test(s)
来源：http://dali.zhixingplan.top/Article/details/gtaapuzkyy.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvnjtgmsc.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhengqikj.top/Article/details/gtewhzplwp.html

Ruby: s.match?(/\d+/)
来源：http://dali.yvedp.cn/Article/details/gttbdmhcyi.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.cucudq.cn/Article/details/gtncuifqeh.html

[I02] 提取所有匹配
来源：http://dali.havefunace.top/Article/details/gtzydfpbbi.html

Py:   re.findall(r"\d+", s)
来源：http://dali.316326.xyz/Article/details/gtmtbirkpu.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.sufxvd.cn/Article/details/gtiuwrizsv.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zycfv.cn/Article/details/gtfykszigm.html

TS:   s.match(/\d+/g)
来源：http://dali.fengsongda.top/Article/details/gtxavdzzmn.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jinqigufen.top/Article/details/gtiporjogy.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.9152youxi.cn/Article/details/gtgpexedwz.html

Ruby: s.scan(/\d+/)
来源：http://dali.hammf.cn/Article/details/gtwfcufxho.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.haohaochexian.top/Article/details/gtxjbpfumd.html

[I03] 提取捕获分组
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqvmnpbuw.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.hnxiangtu.top/Article/details/gtiordlllp.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yonumen.top/Article/details/gtqrmlamiq.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.fengsongda.top/Article/details/gttgjwpcwq.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.iojbl.cn/Article/details/gtdixuheuq.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.guowangkeji.top/Article/details/gtfjfcyxbf.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jinyuanbaomall.cn/Article/details/gtodivvgio.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.tanke756.top/Article/details/gtevuczwpc.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhixingplan.top/Article/details/gtupxhmvor.html

[I04] 正则替换
来源：http://dali.cdnleiting.top/Article/details/gtbsvjhmdq.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.chenjidiqi.icu/Article/details/gtdgbopdae.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.cqqwz.cn/Article/details/gtpaoptgky.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.sufxvd.cn/Article/details/gtponslwxc.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.sufxvd.cn/Article/details/gtpurekfwe.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.gaohongyu789.top/Article/details/gtbnqriegc.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.feifeiyinyue.top/Article/details/gtcxjubesg.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jinqigufen.top/Article/details/gtikggljdz.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jianghu66.top/Article/details/gtodjridof.html

[I05] 按正则拆分
来源：http://dali.xinyue.icu/Article/details/gtcbyoyngf.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.ehwqpu.com/Article/details/gtbwqhjtib.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.bjfxy.top/Article/details/gtgwgvumkx.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yonumen.top/Article/details/gttfevxgci.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.316326.xyz/Article/details/gtabplismb.html

Java: s.split("\\s*,\\s*")
来源：http://dali.sysykeji.top/Article/details/gtqmurbfgm.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.0kj1m.cn/Article/details/gtkbhudlny.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.sweek.top/Article/details/gtiloaypgd.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.sweek.top/Article/details/gtwhooavnk.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.nanxuanxn.top/Article/details/gtdmczikon.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.c1oappe.top/Article/details/gtcctixjgk.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.pycfn.com/Article/details/gtuydjxwwt.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.shanyushiyangtech.top/Article/details/gtknerdnqq.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yanxiufei.cn/Article/details/gtalptfgli.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuktzsucl.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.hnxiangtu.top/Article/details/gtmxtnbdht.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.meibo888.top/Article/details/gtcjnfvacq.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.aibaodan.cn/Article/details/gtmmfdyvqc.html

[I07] 忽略大小写与多行模式
来源：http://dali.gogol.net.cn/Article/details/gtxndllzyb.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.redwolf501.top/Article/details/gtmhjmulpu.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.wangdashe.top/Article/details/gtooyeufey.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jqgufenzy.top/Article/details/gtaxafrnku.html

TS:   /error/gim
来源：http://dali.yueranfly.top/Article/details/gtvulaurmd.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.jinqigufen.top/Article/details/gtxeoxcnar.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.zhixingplan.top/Article/details/gtlyammhao.html


<!-- 参考信息 -->