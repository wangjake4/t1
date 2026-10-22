代发 wailian999

TS:   constructor(public name: string) {}
来源：http://dali.andypj.xyz/Article/details/gtsaemgvko.html

Java: User(String name) { this.name = name; }
来源：http://dali.jqgufenzy.top/Article/details/gtmnxfnivd.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jlsjyb.cn/Article/details/gtxrbgkvmo.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yanxiufei.cn/Article/details/gtpmycsryn.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yuxming.cn/Article/details/gtokenpyna.html

[G03] 实例属性
来源：http://dali.tian-w.cn/Article/details/gtpnpktwry.html

Py:   self.name = "x"
来源：http://dali.hongshengwenyu.top/Article/details/gtsnqvugye.html

PHP:  public string $name = "x";
来源：http://dali.guannengcc.top/Article/details/gtbnelbxjr.html

JS:   this.name = "x";
来源：http://dali.snrcjt.cn/Article/details/gtxhlwqucl.html

TS:   name: string = "x";
来源：http://dali.xylfe.cn/Article/details/gtjyiqojcu.html

Java: private String name;
来源：http://dali.shzxlz.cn/Article/details/gtqmqrrdkx.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.daria6918.cn/Article/details/gtugpckcgt.html

Ruby: @name = "x"
来源：http://dali.chenzaomai.com/Article/details/gtcyzpkggn.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.cdnleiting.top/Article/details/gtfigxtudp.html

[G04] 定义方法
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqxozfljs.html

Py:   def greet(self): return self.name
来源：http://dali.hfpthk.cn/Article/details/gtdtozlztw.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.gotoacloud.top/Article/details/gtusuugmnh.html

JS:   greet() { return this.name; }
来源：http://dali.smart0.xyz/Article/details/gtwhxgqiok.html

TS:   greet(): string { return this.name; }
来源：http://dali.c1oappe.top/Article/details/gtpwpckejs.html

Java: String greet() { return name; }
来源：http://dali.hnqzz.top/Article/details/gtughkadhd.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jqgufenzy.top/Article/details/gtoqcktbtl.html

Ruby: def greet; @name; end
来源：http://dali.guannengcc.top/Article/details/gtnbecxirm.html

C#:   public string Greet() => Name;
来源：http://dali.316326.xyz/Article/details/gtaicsoyou.html

[G05] 继承
来源：http://dali.jiagoushi.top/Article/details/gthiztlwdj.html

Py:   class Admin(User): pass
来源：http://dali.pengpengdd.cyou/Article/details/gtsjnpzevl.html

PHP:  class Admin extends User {}
来源：http://dali.sxryk.cn/Article/details/gtmplaqtes.html

JS:   class Admin extends User {}
来源：http://dali.yueranfly.top/Article/details/gtywligvyx.html

TS:   class Admin extends User {}
来源：http://dali.jqgfzy.top/Article/details/gtrtcrfejx.html

Java: class Admin extends User {}
来源：http://dali.nanxuanxn.top/Article/details/gtwiuqvjjy.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.feifeiyinyue.top/Article/details/gtawfwfnct.html

Ruby: class Admin < User; end
来源：http://dali.quarkkingdee.top/Article/details/gtamxcrkzr.html

C#:   class Admin : User {}
来源：http://dali.yangfankeji.com/Article/details/gtwuuqulmu.html

[G06] 重写方法
来源：http://dali.nanxinkj.top/Article/details/gtxkijjhkn.html

Py:   def greet(self): return "admin"
来源：http://dali.pycfn.com/Article/details/gtxovcvzcf.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.chenlongwang.top/Article/details/gtszuwriqy.html

JS:   greet() { return "admin"; }
来源：http://dali.jyoumei.cn/Article/details/gtqntycdql.html

TS:   greet(): string { return "admin"; }
来源：http://dali.xziqi.cn/Article/details/gthdfhqznj.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zycfv.cn/Article/details/gtqbhnwrjo.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jinghuilouyu.cn/Article/details/gtdgdcqymr.html

Ruby: def greet; "admin"; end
来源：http://dali.chenlongwang.top/Article/details/gtmphihdsb.html

C#:   public override string Greet() => "admin";
来源：http://dali.smart0.xyz/Article/details/gtfmfhsiys.html

[G07] 调用父类方法
来源：http://dali.hnxiangtu.top/Article/details/gttrdfpwtn.html

Py:   super().greet()
来源：http://dali.nanxuanxn.top/Article/details/gtecryrgof.html

PHP:  parent::greet();
来源：http://dali.sweek.top/Article/details/gttkyeqpck.html

JS:   super.greet();
来源：http://dali.hnxiangtu.top/Article/details/gtxekicayq.html

TS:   super.greet();
来源：http://dali.chenlongwang.top/Article/details/gtlcrroivk.html

Java: super.greet();
来源：http://dali.daxiang520.top/Article/details/gtwxuzdxbe.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yonumen.top/Article/details/gtihkcojey.html

Ruby: super
来源：http://dali.chenlongwang.top/Article/details/gtthwnbfoi.html

C#:   base.Greet();
来源：http://dali.gogol.net.cn/Article/details/gtyaeqyxqn.html

[G08] 静态方法与属性
来源：http://dali.jinghuilouyu.cn/Article/details/gtfvvzfsym.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.daxiang520.top/Article/details/gtqwuzjljw.html

PHP:  public static function f() {}
来源：http://dali.0kj1m.cn/Article/details/gtwvkcapwd.html

JS:   static f() {}
来源：http://dali.xuetiantiany.cn/Article/details/gtnvsndgro.html

TS:   static f(): void {}
来源：http://dali.vqdsnc.cn/Article/details/gtcdndhbgw.html

Java: static void f() {}
来源：http://dali.hnqzz.top/Article/details/gtcjezibac.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzpaiirej.html

Ruby: def self.f; end
来源：http://dali.xuanzx.com/Article/details/gtkqiwddtt.html

C#:   public static void F() {}
来源：http://dali.cqqwz.cn/Article/details/gtruthmakc.html

[G09] 接口 / 抽象类
来源：http://dali.jinqigufen.top/Article/details/gtgpkgqvmg.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.tianlin.xyz/Article/details/gtsgulcanh.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.chenlongwang.top/Article/details/gtfgdfbwia.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.chenjidiqi.icu/Article/details/gtulwkqtgq.html

TS:   interface Shape { area(): number; }
来源：http://dali.yueranfly.top/Article/details/gtxleiuphp.html

Java: interface Shape { double area(); }
来源：http://dali.xuanzx.com/Article/details/gtfyuylatt.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hysaishi.cn/Article/details/gtfsmiqdtf.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.9152youxi.cn/Article/details/gtjmdlpips.html

C#:   interface IShape { double Area(); }
来源：http://dali.nwbrower.top/Article/details/gtlhhamnqb.html

[G10] 访问控制
来源：http://dali.nwbrower.top/Article/details/gtctnrlvvs.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yanxiufei.cn/Article/details/gtkqslnfmi.html

PHP:  public / protected / private
来源：http://dali.hnqzz.top/Article/details/gtilopuwum.html

JS:   #private 字段；其余公开
来源：http://dali.zhixingplan.top/Article/details/gtjwkhajca.html

TS:   public / protected / private
来源：http://dali.redwolf501.top/Article/details/gtzsrwlwhi.html

Java: public / protected / private / 默认包级
来源：http://dali.daria6918.cn/Article/details/gtivofoxtp.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.shangyingyoupin.top/Article/details/gthkrasrjb.html

Ruby: public / protected / private
来源：http://dali.dianchejie.cn/Article/details/gtwomrrndk.html

C#:   public / protected / private / internal
来源：http://dali.vqdsnc.cn/Article/details/gtmvkueugs.html

[G11] getter / setter
来源：http://dali.vqdsnc.cn/Article/details/gtljzldiqa.html

Py:   @property 与 @x.setter
来源：http://dali.mhx1999.top/Article/details/gtuohwzrth.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jlsjyb.cn/Article/details/gtmwvmwyoz.html

JS:   get name() { return this._name; }
来源：http://dali.zhixingplan.top/Article/details/gtcqhjsgqi.html

TS:   get name(): string { return this._name; }
来源：http://dali.nwbrower.top/Article/details/gtarmuzopt.html

Java: public String getName() { return name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwrzdzboc.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jinqigfzy.top/Article/details/gtmawwtnuc.html

Ruby: attr_accessor :name
来源：http://dali.yj20258.top/Article/details/gtwyihught.html

C#:   public string Name { get; set; }
来源：http://dali.birdmap.top/Article/details/gtrfzuogua.html

[G12] 对象转字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gtqoecpdrz.html

Py:   def __str__(self): return self.name
来源：http://dali.sxryk.cn/Article/details/gtkhporluv.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.316326.xyz/Article/details/gtwaprhkaz.html

JS:   toString() { return this.name; }
来源：http://dali.ybcxt.top/Article/details/gtbekmqobw.html

TS:   toString(): string { return this.name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvcgkjyxu.html

Java: @Override public String toString() { return name; }
来源：http://dali.shzxlz.cn/Article/details/gtqeklwwnt.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jinghuilouyu.cn/Article/details/gtvqxurncq.html

Ruby: def to_s; @name; end
来源：http://dali.yongpay.top/Article/details/gtlomezfbn.html

C#:   public override string ToString() => Name;
来源：http://dali.chenlongwang.top/Article/details/gtkmaeawsr.html

[G13] 判断对象类型
来源：http://dali.zhongyouzk.top/Article/details/gtozfhsima.html

Py:   isinstance(u, User)
来源：http://dali.svipenyu.cn/Article/details/gttnvvmktm.html

PHP:  $u instanceof User
来源：http://dali.zhiwuduotai.top/Article/details/gtaqctervi.html

JS:   u instanceof User
来源：http://dali.zhiwuduotai.top/Article/details/gtjpumutns.html

TS:   u instanceof User
来源：http://dali.yvedp.cn/Article/details/gtimpkmmrr.html

Java: u instanceof User
来源：http://dali.zycfv.cn/Article/details/gtnhpgqdum.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhiwuduotai.top/Article/details/gtskrwfsos.html

Ruby: u.is_a?(User)
来源：http://dali.jqgfzy.top/Article/details/gtpmawtrin.html

C#:   u is User
来源：http://dali.jianghu66.top/Article/details/gtbcxjuxkq.html

[G14] 数据类 / record
来源：http://dali.hongshengwenyu.top/Article/details/gtibpwhakl.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.hysaishi.cn/Article/details/gtsucahrrz.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.nanxinkj.top/Article/details/gtjxjnkefx.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.guowangkeji.top/Article/details/gtqmivvrad.html

TS:   type User = { name: string; age: number };
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwbxsxdbn.html

Java: record User(String name, int age) {}
来源：http://dali.yangfankeji.com/Article/details/gtebopdway.html

Go:   type User struct { Name string; Age int }
来源：http://dali.nanxinkj.top/Article/details/gtlyidvwze.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.aibaodan.cn/Article/details/gtvnuxarxs.html

C#:   record User(string Name, int Age);
来源：http://dali.nwbrower.top/Article/details/gtysuswwjg.html

[G15] 枚举
来源：http://dali.bjfxy.top/Article/details/gtmujyeiwa.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.fengsongda.top/Article/details/gtlfkctmjo.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.wangshuangyany.cn/Article/details/gtmymhzckd.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.kuanghao11.cn/Article/details/gtesivnpmq.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.svipenyu.cn/Article/details/gtydpeflhj.html

Java: enum Color { RED, GREEN }
来源：http://dali.ppjwa.cn/Article/details/gtqqjrrgpq.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.gaohongyu789.top/Article/details/gtcwqzebgp.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yonumen.top/Article/details/gtthnkbonb.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yanxiufei.cn/Article/details/gtlgntpntk.html

[G16] 对象转数组 / 字典
来源：http://dali.zhiwuduotai.top/Article/details/gtzcjpuxtd.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.xziqi.cn/Article/details/gtouaeeyqj.html

PHP:  get_object_vars($obj);
来源：http://dali.zhoulong.xyz/Article/details/gtgyobwbec.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gtarqcozsn.html

TS:   Object.entries(obj)
来源：http://dali.iojbl.cn/Article/details/gtyepxpcnt.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yueranfly.top/Article/details/gtgghmyfpg.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.xinyue.icu/Article/details/gthtpaksdk.html

Ruby: obj.instance_variables
来源：http://dali.pycfn.com/Article/details/gttalvwasa.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hammf.cn/Article/details/gtylxjcydn.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtmiduepop.html

H. 异常与错误处理
来源：http://dali.haohaochexian.top/Article/details/gtsqiympwy.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtjocnpsgk.html

[H01] try / catch 基础
来源：http://dali.kuanghao11.cn/Article/details/gtrrtuvssj.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.sxryk.cn/Article/details/gtymmngkni.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.quarkkingdee.top/Article/details/gtuebjwydf.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.snrcjt.cn/Article/details/gteteaqkot.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yvedp.cn/Article/details/gtpizbdadd.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jlsjyb.cn/Article/details/gtuntxymki.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hfpthk.cn/Article/details/gtstzaqsih.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.vqdsnc.cn/Article/details/gtrxadmpcp.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hysaishi.cn/Article/details/gtewjfbzqc.html

[H02] finally / ensure 收尾
来源：http://dali.ydzc1.top/Article/details/gtnvhugopd.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.cqqwz.cn/Article/details/gtmvrrqjvm.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.xylfe.cn/Article/details/gthcjtnwaj.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zycfv.cn/Article/details/gtckoaqlxa.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.vqdsnc.cn/Article/details/gtnvepjiai.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yuanzhike.top/Article/details/gtdsmirotp.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yangfankeji.com/Article/details/gtsfthkzbv.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.svipenyu.cn/Article/details/gtqlxwtrij.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yvedp.cn/Article/details/gtbziituqq.html

[H03] 主动抛出异常
来源：http://dali.jlsjyb.cn/Article/details/gtrmxkpfzj.html

Py:   raise ValueError("错误信息")
来源：http://dali.hnxiangtu.top/Article/details/gtljvxqeef.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.shzxlz.cn/Article/details/gtmokegxqx.html

JS:   throw new Error("错误信息");
来源：http://dali.gaohongyu789.top/Article/details/gtkxniakya.html

TS:   throw new Error("错误信息");
来源：http://dali.316326.xyz/Article/details/gtonqgbpse.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.9152youxi.cn/Article/details/gtffsmwkeo.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.redwolf501.top/Article/details/gtmjufpnji.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.tian-w.cn/Article/details/gtzoucyecj.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yanxiufei.cn/Article/details/gtvanzdckc.html

[H04] 自定义异常类型
来源：http://dali.xziqi.cn/Article/details/gtmarqogyb.html

Py:   class MyError(Exception): pass
来源：http://dali.shangyingyoupin.top/Article/details/gtitfekeut.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.sufxvd.cn/Article/details/gtntzmsoxi.html

JS:   class MyError extends Error {}
来源：http://dali.feifeiyinyue.top/Article/details/gthzrevcxz.html

TS:   class MyError extends Error {}
来源：http://dali.jlsjyb.cn/Article/details/gtimbtvear.html

Java: class MyException extends RuntimeException {}
来源：http://dali.aizwys.cn/Article/details/gtsjsawhbr.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jqgfzy.top/Article/details/gtwsultajj.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhengqikj.top/Article/details/gtizfsbocg.html

C#:   class MyException : Exception {}
来源：http://dali.wangdashe.top/Article/details/gtjwfrvbhj.html

[H05] 捕获特定类型
来源：http://dali.ydzc1.top/Article/details/gtdczhjmxo.html

Py:   except ValueError as e:
来源：http://dali.sysykeji.top/Article/details/gtfhxslkfc.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhengqikj.top/Article/details/gtrxhzkims.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.shuidangran.top/Article/details/gtpnamaxvj.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.hnqzz.top/Article/details/gtdzckuqxy.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtntnskmlq.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jiagoushi.top/Article/details/gtyxtmwvcj.html

Ruby: rescue ArgumentError => e
来源：http://dali.nwbrower.top/Article/details/gtmibsmjgm.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.gaohongyu789.top/Article/details/gtulhsmayi.html

[H06] 可选值 / 空值安全访问
来源：http://dali.iojbl.cn/Article/details/gtenzhbydb.html

Py:   value = d.get("k") or default
来源：http://dali.xuetiantiany.cn/Article/details/gtxxaffggt.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hfpthk.cn/Article/details/gtoonejmcv.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhengqikj.top/Article/details/gtsqortnld.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jyoumei.cn/Article/details/gtieyejcly.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.haohaochexian.top/Article/details/gtzklhgiab.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwjucjvzq.html

Ruby: d&.dig(:a, :b)
来源：http://dali.fengsongda.top/Article/details/gtklrknqkl.html

C#:   obj?.A?.B ?? default
来源：http://dali.jinghuilouyu.cn/Article/details/gtxkcqfuny.html

[H07] 断言
来源：http://dali.chenjidiqi.icu/Article/details/gtqzjgqowv.html

Py:   assert x > 0, "必须为正"
来源：http://dali.sufxvd.cn/Article/details/gtlmaesops.html

PHP:  assert($x > 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwiqrzxsm.html

JS:   console.assert(x > 0);
来源：http://dali.ppjwa.cn/Article/details/gtykegxxqy.html

TS:   console.assert(x > 0);
来源：http://dali.wangdashe.top/Article/details/gtdojknmav.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zycfv.cn/Article/details/gtidpxltuz.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.ppjwa.cn/Article/details/gthwvvcfun.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.ppjwa.cn/Article/details/gtqlerbsvc.html

C#:   Debug.Assert(x > 0);
来源：http://dali.nwbrower.top/Article/details/gtoluxdgui.html

[H08] 获取错误信息与堆栈
来源：http://dali.jiagoushi.top/Article/details/gtwoyomlql.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.haohaochexian.top/Article/details/gthowxudqt.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.andypj.xyz/Article/details/gtqkdrztup.html

JS:   e.message;  e.stack
来源：http://dali.svipenyu.cn/Article/details/gtrzqtlvqs.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.gzhubu.top/Article/details/gtheyowech.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.shuidangran.top/Article/details/gtpdbydfmj.html

Go:   err.Error()
来源：http://dali.sysykeji.top/Article/details/gtujoehvkc.html

Ruby: e.message;  e.backtrace
来源：http://dali.guowangkeji.top/Article/details/gtehtqqljq.html

C#:   e.Message;  e.StackTrace
来源：http://dali.ydzc1.top/Article/details/gtsuendrul.html

[H09] 带错误码的异常
来源：http://dali.haohaochexian.top/Article/details/gtumpyivro.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yj20258.top/Article/details/gtkmztvifu.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.fzhhl.top/Article/details/gtkdgeyzhb.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.9152youxi.cn/Article/details/gtagsydygo.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.ehwqpu.com/Article/details/gtfvixcxjo.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.cqqwz.cn/Article/details/gtzlpwpcjt.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.ehwqpu.com/Article/details/gthyegdgts.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.smart0.xyz/Article/details/gthcpcbpnv.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.xziqi.cn/Article/details/gtrltpulcj.html

[H10] 资源自动释放
来源：http://dali.jqgfzy.top/Article/details/gtmonffled.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.pycfn.com/Article/details/gtyrdvijwx.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zdqjudy.top/Article/details/gtatjdbtii.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.havefunace.top/Article/details/gtzjufvnpw.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.chenlongwang.top/Article/details/gttzcebjwo.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.sysykeji.top/Article/details/gtfrjltxlt.html

Go:   defer f.Close()
来源：http://dali.aizwys.cn/Article/details/gtstospsyn.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yj20258.top/Article/details/gtryeidugy.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcewwdmfb.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtxaevbpkf.html

I. 正则表达式
来源：http://dali.daria6918.cn/Article/details/gtmbesggon.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtykwekqtr.html

[I01] 判断是否匹配
来源：http://dali.zycfv.cn/Article/details/gtqkswipuz.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.quarkkingdee.top/Article/details/gtyekvlljp.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhengqikj.top/Article/details/gtywdujpop.html

JS:   /\d+/.test(s)
来源：http://dali.yuanzhike.top/Article/details/gtvlayspnt.html

TS:   /\d+/.test(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtgecflhmy.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.zdqjudy.top/Article/details/gtqyxrijie.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jyoumei.cn/Article/details/gtnfotwsft.html

Ruby: s.match?(/\d+/)
来源：http://dali.sweek.top/Article/details/gtgqxkknmm.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jianghu66.top/Article/details/gteyfedtcf.html

[I02] 提取所有匹配
来源：http://dali.jiagoushi.top/Article/details/gtvrmpomqz.html

Py:   re.findall(r"\d+", s)
来源：http://dali.sweek.top/Article/details/gtgkpidgjt.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jinqigfzy.top/Article/details/gtprivzhtn.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zycfv.cn/Article/details/gtofealoal.html

TS:   s.match(/\d+/g)
来源：http://dali.jlsjyb.cn/Article/details/gtiurgymbr.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.wangdashe.top/Article/details/gtplhqqkwj.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.sweek.top/Article/details/gtrlpyndes.html

Ruby: s.scan(/\d+/)
来源：http://dali.316326.xyz/Article/details/gtrzrxlfqw.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.pengpengdd.cyou/Article/details/gtafbzielh.html

[I03] 提取捕获分组
来源：http://dali.hfpthk.cn/Article/details/gtdcrjvysy.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.mhx1999.top/Article/details/gtoswypzoc.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.feifeiyinyue.top/Article/details/gtghwsktls.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.wangdashe.top/Article/details/gtzgzrstnp.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvuhatdhh.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.hongshengwenyu.top/Article/details/gttpjscfnh.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhongyouzk.top/Article/details/gtkzzkqymv.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yangfankeji.com/Article/details/gtcjcpxnro.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxakgrexf.html

[I04] 正则替换
来源：http://dali.xylfe.cn/Article/details/gtelpgikvq.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.cqqwz.cn/Article/details/gtcjxpeezu.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jinqigufen.top/Article/details/gtxusftuqk.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.sufxvd.cn/Article/details/gtvnqjrbbn.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.sysykeji.top/Article/details/gtiihvmdrt.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.sxryk.cn/Article/details/gtsaaizlgn.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.zhixingplan.top/Article/details/gtczzhvpjg.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.cucudq.cn/Article/details/gtzhuaydmc.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zdqjudy.top/Article/details/gtxvexqblj.html

[I05] 按正则拆分
来源：http://dali.havefunace.top/Article/details/gtiqorljkj.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.hnqzz.top/Article/details/gtzycayeef.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gtwsbvdwjk.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.zhijiandao.cn/Article/details/gtkfbgwgdm.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.shanyushiyangtech.top/Article/details/gtkgefttfb.html

Java: s.split("\\s*,\\s*")
来源：http://dali.cdnleiting.top/Article/details/gtmrnclvlo.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlhovykmi.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.jinqigfzy.top/Article/details/gthpgzwisy.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.c1oappe.top/Article/details/gtsethbrar.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.gzhubu.top/Article/details/gtighyvofn.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.pycfn.com/Article/details/gtntclahto.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.hywenlv.cn/Article/details/gtfxriyhdb.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.bjfxy.top/Article/details/gtimxfohst.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhixingplan.top/Article/details/gtgehfdbrm.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.vqdsnc.cn/Article/details/gtlimpvkgx.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.jyoumei.cn/Article/details/gtbyqlbedg.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.xuetiantiany.cn/Article/details/gtzoubspoo.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jinyuanbaomall.cn/Article/details/gteukllowv.html

[I07] 忽略大小写与多行模式
来源：http://dali.guannengcc.top/Article/details/gthkjolvoi.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.jqgfzy.top/Article/details/gttyyqtvxt.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.yuxming.cn/Article/details/gtuejealld.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.zhiwuduotai.top/Article/details/gtrvazyero.html

TS:   /error/gim
来源：http://dali.jqgufenzy.top/Article/details/gtnswnzdru.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.daria6918.cn/Article/details/gtviuymeib.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.xylfe.cn/Article/details/gtrfhnikud.html

Ruby: s.scan(/error/i)
来源：http://dali.tanke756.top/Article/details/gtcwfqjunh.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnjvfxaga.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.iojbl.cn/Article/details/gtjucpspus.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.jyoumei.cn/Article/details/gtotnyotyn.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.aibaodan.cn/Article/details/gtfrmftwud.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.chenjidiqi.icu/Article/details/gtzniirbkr.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.ybcxt.top/Article/details/gtrqjziecx.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.sweek.top/Article/details/gtiqvnxuyt.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.iojbl.cn/Article/details/gtdkdiubit.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.aibaodan.cn/Article/details/gtsvjybyar.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.guannengcc.top/Article/details/gttgchajer.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtpzqunezn.html


<!-- 参考信息 -->