代发 wailian999

Java: class User {}
来源：http://dali.nanxinkj.top/Article/details/gtibwomcij.html

Go:   type User struct { Name string }
来源：http://dali.guannengcc.top/Article/details/gtckijueds.html

Ruby: class User; end
来源：http://dali.pengpengdd.cyou/Article/details/gtalqcjuzx.html

C#:   class User {}
来源：http://dali.fzhhl.top/Article/details/gthgdelgqp.html

[G02] 构造函数
来源：http://dali.hnxiangtu.top/Article/details/gtfcaegqfm.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yuanzhike.top/Article/details/gtcphrwmdt.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtiaakgbcc.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yuanzhike.top/Article/details/gttxjuzpkt.html

TS:   constructor(public name: string) {}
来源：http://dali.yanxiufei.cn/Article/details/gtugtdbsiz.html

Java: User(String name) { this.name = name; }
来源：http://dali.vqdsnc.cn/Article/details/gtdpsagodb.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.haohaochexian.top/Article/details/gtitlxwkim.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jiagoushi.top/Article/details/gthkztnxui.html

C#:   public User(string name) { Name = name; }
来源：http://dali.guowangkeji.top/Article/details/gtjsoozrut.html

[G03] 实例属性
来源：http://dali.316326.xyz/Article/details/gtgsfajgja.html

Py:   self.name = "x"
来源：http://dali.yj20258888.top/Article/details/gtwxtcazkf.html

PHP:  public string $name = "x";
来源：http://dali.0kj1m.cn/Article/details/gtkhwsfunf.html

JS:   this.name = "x";
来源：http://dali.shzxlz.cn/Article/details/gtyfvyhjjo.html

TS:   name: string = "x";
来源：http://dali.iojbl.cn/Article/details/gthuxlzipo.html

Java: private String name;
来源：http://dali.yvedp.cn/Article/details/gtexkcjjxf.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yonumen.top/Article/details/gtnnfbepbx.html

Ruby: @name = "x"
来源：http://dali.hysaishi.cn/Article/details/gtxptcnivb.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.meibo888.top/Article/details/gtkaydgsie.html

[G04] 定义方法
来源：http://dali.chenjidiqi.icu/Article/details/gtokmebzoq.html

Py:   def greet(self): return self.name
来源：http://dali.c1oappe.top/Article/details/gtumzxxank.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtoqbpqnwj.html

JS:   greet() { return this.name; }
来源：http://dali.vqdsnc.cn/Article/details/gtkiosphyy.html

TS:   greet(): string { return this.name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtngysvqws.html

Java: String greet() { return name; }
来源：http://dali.xziqi.cn/Article/details/gtugtflppe.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.tianlin.xyz/Article/details/gtbxjxakop.html

Ruby: def greet; @name; end
来源：http://dali.daxiang520.top/Article/details/gtsfsynbja.html

C#:   public string Greet() => Name;
来源：http://dali.chenlongwang.top/Article/details/gtwxxlbkmx.html

[G05] 继承
来源：http://dali.zhoulong.xyz/Article/details/gtbhwijszl.html

Py:   class Admin(User): pass
来源：http://dali.gotoacloud.top/Article/details/gtdfsckbch.html

PHP:  class Admin extends User {}
来源：http://dali.yuxming.cn/Article/details/gtxdkqzkll.html

JS:   class Admin extends User {}
来源：http://dali.zhoulong.xyz/Article/details/gtiwylsnad.html

TS:   class Admin extends User {}
来源：http://dali.svipenyu.cn/Article/details/gtiadbrsdn.html

Java: class Admin extends User {}
来源：http://dali.zhongyouzk.top/Article/details/gtsgtasldn.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yj202588.top/Article/details/gttiesvllh.html

Ruby: class Admin < User; end
来源：http://dali.wangshuangyany.cn/Article/details/gtazfnylub.html

C#:   class Admin : User {}
来源：http://dali.zycfv.cn/Article/details/gtocqsosoq.html

[G06] 重写方法
来源：http://dali.shanyushiyangtech.top/Article/details/gtrwrpyfbu.html

Py:   def greet(self): return "admin"
来源：http://dali.chenjidiqi.icu/Article/details/gtrdptsmcj.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.sufxvd.cn/Article/details/gthubljoms.html

JS:   greet() { return "admin"; }
来源：http://dali.shzxlz.cn/Article/details/gtlgfgykvl.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hysaishi.cn/Article/details/gtrqbyhmrb.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jinqigfzy.top/Article/details/gtbqqiknwf.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.gaohongyu789.top/Article/details/gtfbwxymsc.html

Ruby: def greet; "admin"; end
来源：http://dali.jianghu66.top/Article/details/gtkszzwvvw.html

C#:   public override string Greet() => "admin";
来源：http://dali.hnxiangtu.top/Article/details/gttyfzkqoq.html

[G07] 调用父类方法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtydcwokyz.html

Py:   super().greet()
来源：http://dali.hywenlv.cn/Article/details/gtbrbmvntx.html

PHP:  parent::greet();
来源：http://dali.gzhubu.top/Article/details/gtcccofqbg.html

JS:   super.greet();
来源：http://dali.pycfn.com/Article/details/gtgfyciods.html

TS:   super.greet();
来源：http://dali.guowangkeji.top/Article/details/gtqxbubwxt.html

Java: super.greet();
来源：http://dali.vqdsnc.cn/Article/details/gtiablbfyq.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jinqigfzy.top/Article/details/gtovefrqqm.html

Ruby: super
来源：http://dali.hywenlv.cn/Article/details/gtaxlvmpka.html

C#:   base.Greet();
来源：http://dali.zhixingplan.top/Article/details/gtjwaatxmk.html

[G08] 静态方法与属性
来源：http://dali.gaohongyu789.top/Article/details/gtrlmouxod.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.shuidangran.top/Article/details/gtizfsrsfb.html

PHP:  public static function f() {}
来源：http://dali.gogol.net.cn/Article/details/gtzmaxjynl.html

JS:   static f() {}
来源：http://dali.cdnleiting.top/Article/details/gtljzskmtw.html

TS:   static f(): void {}
来源：http://dali.316326.xyz/Article/details/gtyexuwjri.html

Java: static void f() {}
来源：http://dali.sysykeji.top/Article/details/gtffwczezs.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhiwuduotai.top/Article/details/gtvvpdfvpm.html

Ruby: def self.f; end
来源：http://dali.xylfe.cn/Article/details/gtgfrxtnzx.html

C#:   public static void F() {}
来源：http://dali.aizwys.cn/Article/details/gtuhceffhl.html

[G09] 接口 / 抽象类
来源：http://dali.cashguo.top/Article/details/gthbeybvej.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.smart0.xyz/Article/details/gtlvrzntdq.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.sufxvd.cn/Article/details/gtkwbrglok.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.guannengcc.top/Article/details/gtoogalwtp.html

TS:   interface Shape { area(): number; }
来源：http://dali.cashguo.top/Article/details/gtclgckhpd.html

Java: interface Shape { double area(); }
来源：http://dali.jinqigufen.top/Article/details/gtumxfyjvk.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hysaishi.cn/Article/details/gtanxdjtwa.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yvedp.cn/Article/details/gtmorprbgp.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhijiandao.cn/Article/details/gtialiiztg.html

[G10] 访问控制
来源：http://dali.yanxiufei.cn/Article/details/gtsfmipgfg.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zycfv.cn/Article/details/gtgbvehieq.html

PHP:  public / protected / private
来源：http://dali.dashuyun.cn/Article/details/gthntkecat.html

JS:   #private 字段；其余公开
来源：http://dali.guannengcc.top/Article/details/gtsfmsjrgt.html

TS:   public / protected / private
来源：http://dali.jinqigfzy.top/Article/details/gtzrciirsn.html

Java: public / protected / private / 默认包级
来源：http://dali.yanxiufei.cn/Article/details/gtgotijdds.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yangfankeji.com/Article/details/gtushvjuoc.html

Ruby: public / protected / private
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsrxxkdaf.html

C#:   public / protected / private / internal
来源：http://dali.jinghuilouyu.cn/Article/details/gtribeswqj.html

[G11] getter / setter
来源：http://dali.redwolf501.top/Article/details/gtwzyubdcq.html

Py:   @property 与 @x.setter
来源：http://dali.haohaochexian.top/Article/details/gtkwkpeznn.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.shuidangran.top/Article/details/gtqazywpmf.html

JS:   get name() { return this._name; }
来源：http://dali.yueranfly.top/Article/details/gtweqkfzvu.html

TS:   get name(): string { return this._name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtallaqjch.html

Java: public String getName() { return name; }
来源：http://dali.jqgufenzy.top/Article/details/gtkcmlmmus.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xuanzx.com/Article/details/gterqgczam.html

Ruby: attr_accessor :name
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpbxeadkj.html

C#:   public string Name { get; set; }
来源：http://dali.cheryme.top/Article/details/gtajpvhaaz.html

[G12] 对象转字符串
来源：http://dali.yj20258.top/Article/details/gtszpajrjb.html

Py:   def __str__(self): return self.name
来源：http://dali.guowangkeji.top/Article/details/gtcjppvncj.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.iojbl.cn/Article/details/gtjuzzisty.html

JS:   toString() { return this.name; }
来源：http://dali.sweek.top/Article/details/gtmcdlcfnx.html

TS:   toString(): string { return this.name; }
来源：http://dali.shzxlz.cn/Article/details/gtfdxkkrye.html

Java: @Override public String toString() { return name; }
来源：http://dali.xziqi.cn/Article/details/gtulodmliu.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hywenlv.cn/Article/details/gtjwepsdan.html

Ruby: def to_s; @name; end
来源：http://dali.zhixingplan.top/Article/details/gthxoeizcn.html

C#:   public override string ToString() => Name;
来源：http://dali.jlsjyb.cn/Article/details/gtnesfekhd.html

[G13] 判断对象类型
来源：http://dali.yuanzhike.top/Article/details/gtlkigesat.html

Py:   isinstance(u, User)
来源：http://dali.xinyue.icu/Article/details/gtprymfyak.html

PHP:  $u instanceof User
来源：http://dali.ivvv.top/Article/details/gtxajrkfjt.html

JS:   u instanceof User
来源：http://dali.c1oappe.top/Article/details/gtuidzcvyu.html

TS:   u instanceof User
来源：http://dali.hysaishi.cn/Article/details/gtnlcxihos.html

Java: u instanceof User
来源：http://dali.0kj1m.cn/Article/details/gtpvmjjovw.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.sufxvd.cn/Article/details/gtspqucgsr.html

Ruby: u.is_a?(User)
来源：http://dali.yuxming.cn/Article/details/gtehwclkvx.html

C#:   u is User
来源：http://dali.jqgfzy.top/Article/details/gteukckjhr.html

[G14] 数据类 / record
来源：http://dali.xylfe.cn/Article/details/gtonaobawk.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.ivvv.top/Article/details/gtjjtqpcam.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yuxming.cn/Article/details/gtfkwhhgks.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.quarkkingdee.top/Article/details/gtjlfqqhqq.html

TS:   type User = { name: string; age: number };
来源：http://dali.jyoumei.cn/Article/details/gtjjwzzkko.html

Java: record User(String name, int age) {}
来源：http://dali.iojbl.cn/Article/details/gtlhgonaxg.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hfpthk.cn/Article/details/gtwuwuszpb.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hongshengwenyu.top/Article/details/gtxqtzmznb.html

C#:   record User(string Name, int Age);
来源：http://dali.cucudq.cn/Article/details/gtypmovamp.html

[G15] 枚举
来源：http://dali.yj20258888.top/Article/details/gtrghblwhl.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.gaohongyu789.top/Article/details/gtsfjcgezq.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yj202588.top/Article/details/gtexwvcpqt.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.tanke756.top/Article/details/gtirvvgrud.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sweek.top/Article/details/gtbngzxhug.html

Java: enum Color { RED, GREEN }
来源：http://dali.tianlin.xyz/Article/details/gtzkcwunlx.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.shzxlz.cn/Article/details/gtjvzijrxl.html

Ruby: Color = %i[red green].freeze
来源：http://dali.nanxinkj.top/Article/details/gtdiklveto.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.tian-w.cn/Article/details/gtmlcwuizn.html

[G16] 对象转数组 / 字典
来源：http://dali.jianghu66.top/Article/details/gticlffpkz.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.andypj.xyz/Article/details/gtrquixrkm.html

PHP:  get_object_vars($obj);
来源：http://dali.vqdsnc.cn/Article/details/gtdyvzwvje.html

JS:   Object.entries(obj)
来源：http://dali.chenzaomai.com/Article/details/gtqgivblyh.html

TS:   Object.entries(obj)
来源：http://dali.chenlongwang.top/Article/details/gtvqeudjuq.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjccwviaz.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yuanzhike.top/Article/details/gthjdegtbi.html

Ruby: obj.instance_variables
来源：http://dali.guannengcc.top/Article/details/gtpatsepzl.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yuxming.cn/Article/details/gtmmqulpnb.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtnudunyyu.html

H. 异常与错误处理
来源：http://dali.shzxlz.cn/Article/details/gtqcxqmshc.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtgnpvliof.html

[H01] try / catch 基础
来源：http://dali.zdqjudy.top/Article/details/gtxpchryay.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gtqqvmgmuk.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yj202588.top/Article/details/gtidhnqayd.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hammf.cn/Article/details/gtwvkngofk.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.haohaochexian.top/Article/details/gtzdclvwid.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.gotoacloud.top/Article/details/gteupgyujd.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.sysykeji.top/Article/details/gtkkpvvylp.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.sysykeji.top/Article/details/gtwbeqxjmj.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.cheryme.top/Article/details/gtkahrkcyz.html

[H02] finally / ensure 收尾
来源：http://dali.jinghuilouyu.cn/Article/details/gtqtltpohe.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.shzxlz.cn/Article/details/gtnmbbuwrc.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.xylfe.cn/Article/details/gtxtuschaj.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnqqslorx.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.gogol.net.cn/Article/details/gtpignaxho.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.feifeiyinyue.top/Article/details/gtjcpuisaf.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jinghuilouyu.cn/Article/details/gtvzcoykja.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.svipenyu.cn/Article/details/gtmyevmuwc.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jinqigfzy.top/Article/details/gthtghzzjf.html

[H03] 主动抛出异常
来源：http://dali.hongshengwenyu.top/Article/details/gtvrustqik.html

Py:   raise ValueError("错误信息")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtansvpsxy.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jinyuanbaomall.cn/Article/details/gttimbhnpr.html

JS:   throw new Error("错误信息");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaqmrogoz.html

TS:   throw new Error("错误信息");
来源：http://dali.dianchejie.cn/Article/details/gthfceqtbx.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.feifeiyinyue.top/Article/details/gtzzstymsi.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jinghuilouyu.cn/Article/details/gtlsxypwpz.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yvedp.cn/Article/details/gthilngdhs.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.c1oappe.top/Article/details/gtjtpzbbdr.html

[H04] 自定义异常类型
来源：http://dali.shuidangran.top/Article/details/gtgiyybsvv.html

Py:   class MyError(Exception): pass
来源：http://dali.yanxiufei.cn/Article/details/gtwjroiokp.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.sweek.top/Article/details/gtgzcweatz.html

JS:   class MyError extends Error {}
来源：http://dali.iojbl.cn/Article/details/gtkjvuysqg.html

TS:   class MyError extends Error {}
来源：http://dali.svipenyu.cn/Article/details/gticytlgzi.html

Java: class MyException extends RuntimeException {}
来源：http://dali.nwbrower.top/Article/details/gtfjbnvxnv.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.feifeiyinyue.top/Article/details/gtuxctickd.html

Ruby: class MyError < StandardError; end
来源：http://dali.birdmap.top/Article/details/gtvjhqfopy.html

C#:   class MyException : Exception {}
来源：http://dali.snrcjt.cn/Article/details/gtzuxfaheq.html

[H05] 捕获特定类型
来源：http://dali.birdmap.top/Article/details/gtesyayisa.html

Py:   except ValueError as e:
来源：http://dali.ehwqpu.com/Article/details/gthkiphitv.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhoulong.xyz/Article/details/gtyewpsuwn.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtcznzutch.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.hammf.cn/Article/details/gttbpkinns.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.gzhubu.top/Article/details/gtvvlebdlg.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.nanxinkj.top/Article/details/gtnhhdvypk.html

Ruby: rescue ArgumentError => e
来源：http://dali.yj20258.top/Article/details/gtkhcywcaq.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hnqzz.top/Article/details/gtbuquqaow.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhixingplan.top/Article/details/gtrptciuvv.html

Py:   value = d.get("k") or default
来源：http://dali.snrcjt.cn/Article/details/gtmrcukggk.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.smart0.xyz/Article/details/gtngsshadb.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.fengsongda.top/Article/details/gtsphjmscw.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.sysykeji.top/Article/details/gtmdaqxhfl.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.xuanzx.com/Article/details/gtrtuiuohn.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jyoumei.cn/Article/details/gtsyqfkmwr.html

Ruby: d&.dig(:a, :b)
来源：http://dali.xuanzx.com/Article/details/gtkgfllbua.html

C#:   obj?.A?.B ?? default
来源：http://dali.kuanghao11.cn/Article/details/gtrqxlikls.html

[H07] 断言
来源：http://dali.quarkkingdee.top/Article/details/gtdikczzgo.html

Py:   assert x > 0, "必须为正"
来源：http://dali.ivvv.top/Article/details/gtjgmnpmer.html

PHP:  assert($x > 0);
来源：http://dali.cashguo.top/Article/details/gtqvieuvmq.html

JS:   console.assert(x > 0);
来源：http://dali.jinqigfzy.top/Article/details/gtoywfbjly.html

TS:   console.assert(x > 0);
来源：http://dali.guannengcc.top/Article/details/gtowionnkp.html

Java: assert x > 0 : "必须为正";
来源：http://dali.chenzaomai.com/Article/details/gtuxzuwxfi.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jianghu66.top/Article/details/gtduefhyjv.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hywenlv.cn/Article/details/gtohjngpgk.html

C#:   Debug.Assert(x > 0);
来源：http://dali.xinyue.icu/Article/details/gtcnqyjfsp.html

[H08] 获取错误信息与堆栈
来源：http://dali.sufxvd.cn/Article/details/gtbncdhzin.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yangfankeji.com/Article/details/gttcewjzar.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.guannengcc.top/Article/details/gtjxejfqbd.html

JS:   e.message;  e.stack
来源：http://dali.fengsongda.top/Article/details/gtwsfmdbbr.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.feifeiyinyue.top/Article/details/gtmbagwgdy.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.316326.xyz/Article/details/gtaptteiev.html

Go:   err.Error()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtviawvmlj.html

Ruby: e.message;  e.backtrace
来源：http://dali.iojbl.cn/Article/details/gtnujeatji.html

C#:   e.Message;  e.StackTrace
来源：http://dali.gotoacloud.top/Article/details/gtkbfrvvgc.html

[H09] 带错误码的异常
来源：http://dali.yj202588.top/Article/details/gtprxsnhcy.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.chenlongwang.top/Article/details/gtplntmwti.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.tanke756.top/Article/details/gtthkrasjn.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.xuanzx.com/Article/details/gtxkhjwmvc.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zycfv.cn/Article/details/gtopnytowr.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.nanxuanxn.top/Article/details/gtpcoqllag.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jyoumei.cn/Article/details/gtvykizydn.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jlsjyb.cn/Article/details/gtvrjwoica.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yonumen.top/Article/details/gtsghiinhr.html

[H10] 资源自动释放
来源：http://dali.dianchejie.cn/Article/details/gtkhbwgstn.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yonumen.top/Article/details/gttumffkyv.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.wangdashe.top/Article/details/gtkgndhiei.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.guannengcc.top/Article/details/gtnlcbniir.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.daxiang520.top/Article/details/gtdpuxftyr.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.pengpengdd.cyou/Article/details/gtmezffurn.html

Go:   defer f.Close()
来源：http://dali.hywenlv.cn/Article/details/gtslppcgui.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.shzxlz.cn/Article/details/gtoqgvzbim.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.aizwys.cn/Article/details/gtppclvilf.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gthpbznvuj.html

I. 正则表达式
来源：http://dali.birdmap.top/Article/details/gtfbbeolli.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtfbqqxgml.html

[I01] 判断是否匹配
来源：http://dali.nwbrower.top/Article/details/gtqwhcryks.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.pycfn.com/Article/details/gtidqpxjum.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.hfpthk.cn/Article/details/gthucvyzes.html

JS:   /\d+/.test(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcshzmkuz.html

TS:   /\d+/.test(s)
来源：http://dali.0kj1m.cn/Article/details/gtbbbvnivb.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.hnqzz.top/Article/details/gtzdwupqfy.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.ehwqpu.com/Article/details/gtgsekdfsu.html

Ruby: s.match?(/\d+/)
来源：http://dali.andypj.xyz/Article/details/gtogmwbcqq.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsxwpthkc.html

[I02] 提取所有匹配
来源：http://dali.fengsongda.top/Article/details/gtcvhjpdwe.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jinqigfzy.top/Article/details/gtqdaoccut.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.kuanghao11.cn/Article/details/gtgbxbuxwk.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.snrcjt.cn/Article/details/gtfkyskjep.html

TS:   s.match(/\d+/g)
来源：http://dali.cdnleiting.top/Article/details/gtjqsmpjux.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.wangdashe.top/Article/details/gtywiokzgj.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhongyouzk.top/Article/details/gtrhzpvxce.html

Ruby: s.scan(/\d+/)
来源：http://dali.tian-w.cn/Article/details/gtmddljrsf.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.mhx1999.top/Article/details/gtxmatjged.html

[I03] 提取捕获分组
来源：http://dali.gaohongyu789.top/Article/details/gtcvckiomq.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.bjfxy.top/Article/details/gtqhqwwfxp.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.fzhhl.top/Article/details/gtarpgvfjf.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yuxming.cn/Article/details/gtdzwrabuk.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jinqigufen.top/Article/details/gtlwjmqxjg.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.ybcxt.top/Article/details/gtpgtlogez.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.cheryme.top/Article/details/gtlxsxpicn.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.jqgufenzy.top/Article/details/gtwvrblnmy.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.zhengqikj.top/Article/details/gtfvrktcua.html

[I04] 正则替换
来源：http://dali.chenlongwang.top/Article/details/gtqciznhkt.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jlsjyb.cn/Article/details/gtocmehmax.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.fzhhl.top/Article/details/gtyhpcbfii.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.dashuyun.cn/Article/details/gtazsytmjq.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.nwbrower.top/Article/details/gtrtfksjrb.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.kuanghao11.cn/Article/details/gtranqoqkr.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.birdmap.top/Article/details/gtpniwbiwv.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteeheyead.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.gotoacloud.top/Article/details/gtidjaqqmj.html

[I05] 按正则拆分
来源：http://dali.mhx1999.top/Article/details/gtgqwkzyea.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.shuidangran.top/Article/details/gtwewcbcjc.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yuxming.cn/Article/details/gtheqpthay.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhongyouzk.top/Article/details/gtlvnqtmzh.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.pycfn.com/Article/details/gtlhwpscpb.html

Java: s.split("\\s*,\\s*")
来源：http://dali.cucudq.cn/Article/details/gtrszyiaer.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.iojbl.cn/Article/details/gtsebcurkb.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.yvedp.cn/Article/details/gtwwbemvcl.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.tanke756.top/Article/details/gtjnvchufm.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.guannengcc.top/Article/details/gtdhrnamzo.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.c1oappe.top/Article/details/gtsgeihzln.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.bjfxy.top/Article/details/gtcazvtwpw.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.iojbl.cn/Article/details/gtxnzqaxfm.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.haohaochexian.top/Article/details/gtlkqdzmog.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.gzhubu.top/Article/details/gtbbbveoxy.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.quarkkingdee.top/Article/details/gtrgvmlxqa.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.cucudq.cn/Article/details/gtcllowswx.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.cdnleiting.top/Article/details/gtkedrlufu.html

[I07] 忽略大小写与多行模式
来源：http://dali.zhijiandao.cn/Article/details/gtofrqzfhd.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdksfvpfv.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.daria6918.cn/Article/details/gtculjxmct.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.316326.xyz/Article/details/gtarfjwdod.html

TS:   /error/gim
来源：http://dali.xziqi.cn/Article/details/gtmrjdfagz.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.shangyingyoupin.top/Article/details/gtninuotve.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.daxiang520.top/Article/details/gtrrfqmyya.html

Ruby: s.scan(/error/i)
来源：http://dali.zhongyouzk.top/Article/details/gtiujdtesd.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.ehwqpu.com/Article/details/gtksenkdxs.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.yongpay.top/Article/details/gtejkuepas.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.dashuyun.cn/Article/details/gtmnfryevp.html


<!-- 参考信息 -->