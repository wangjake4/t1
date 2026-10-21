代发 wailian999

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.kuanghao11.cn/Article/details/gtezbemoom.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.havefunace.top/Article/details/gtmmaiajhj.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.iojbl.cn/Article/details/gtusflrfzw.html

[F12] CSV 读写
来源：http://dali.quarkkingdee.top/Article/details/gtotplrkoa.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.gaohongyu789.top/Article/details/gtjyjsnblx.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yanxiufei.cn/Article/details/gtvnyqurhn.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hongshengwenyu.top/Article/details/gtmkircdnj.html

TS:   // 同上
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbxzeaxzn.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.chenzaomai.com/Article/details/gtocmlmoiq.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yj20258888.top/Article/details/gtmcxmpbld.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.tanke756.top/Article/details/gtbeomkewa.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.chenlongwang.top/Article/details/gtjtbdqtxm.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtjgelxzwd.html

G. 面向对象
来源：http://dali.fzhhl.top/Article/details/gtqkaodlfn.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtiivuflsx.html

[G01] 定义类
来源：http://dali.yj202588.top/Article/details/gttullogqs.html

Py:   class User: pass
来源：http://dali.meibo888.top/Article/details/gtfyhxybpb.html

PHP:  class User {}
来源：http://dali.ivvv.top/Article/details/gtmbbmvydn.html

JS:   class User {}
来源：http://dali.yj20258888.top/Article/details/gtkajluzyt.html

TS:   class User { name: string = ""; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtcgtnvrgc.html

Java: class User {}
来源：http://dali.jqgufenzy.top/Article/details/gtevmwfnyg.html

Go:   type User struct { Name string }
来源：http://dali.xinyue.icu/Article/details/gtrosgxqqb.html

Ruby: class User; end
来源：http://dali.yonumen.top/Article/details/gtkjxdftcl.html

C#:   class User {}
来源：http://dali.gogol.net.cn/Article/details/gtqtzlzzbz.html

[G02] 构造函数
来源：http://dali.xuanzx.com/Article/details/gtertjrfwb.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yanxiufei.cn/Article/details/gtbljdmjmf.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.iojbl.cn/Article/details/gtwuiimvbd.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yuxming.cn/Article/details/gtbkrpmnyb.html

TS:   constructor(public name: string) {}
来源：http://dali.yongpay.top/Article/details/gtvzddlwuy.html

Java: User(String name) { this.name = name; }
来源：http://dali.nanxinkj.top/Article/details/gtvxxsidzd.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.andypj.xyz/Article/details/gtblwuvykj.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.chenzaomai.com/Article/details/gtaflsrdei.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jiagoushi.top/Article/details/gtwqvuflgq.html

[G03] 实例属性
来源：http://dali.shuidangran.top/Article/details/gtjucgeaij.html

Py:   self.name = "x"
来源：http://dali.cdnleiting.top/Article/details/gtgopszhel.html

PHP:  public string $name = "x";
来源：http://dali.xylfe.cn/Article/details/gtkgwmxcmd.html

JS:   this.name = "x";
来源：http://dali.316326.xyz/Article/details/gtrdzpnbur.html

TS:   name: string = "x";
来源：http://dali.fzhhl.top/Article/details/gtxwxjoxxb.html

Java: private String name;
来源：http://dali.gaohongyu789.top/Article/details/gtjuiygnyu.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.ydzc1.top/Article/details/gtisjqkres.html

Ruby: @name = "x"
来源：http://dali.zhengqikj.top/Article/details/gtunycdpcm.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.vqdsnc.cn/Article/details/gtdmzeuihd.html

[G04] 定义方法
来源：http://dali.fzhhl.top/Article/details/gtdbwsavpk.html

Py:   def greet(self): return self.name
来源：http://dali.sysykeji.top/Article/details/gtzkjcusrw.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.sxryk.cn/Article/details/gtsqmeqmxi.html

JS:   greet() { return this.name; }
来源：http://dali.zhongyouzk.top/Article/details/gtshtlfkvj.html

TS:   greet(): string { return this.name; }
来源：http://dali.snrcjt.cn/Article/details/gtsmabgdqj.html

Java: String greet() { return name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvwkejxpg.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yj202588.top/Article/details/gtsvqopxhj.html

Ruby: def greet; @name; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtohouigkl.html

C#:   public string Greet() => Name;
来源：http://dali.wangshuangyany.cn/Article/details/gtntcuuasg.html

[G05] 继承
来源：http://dali.sweek.top/Article/details/gtrxdokfkb.html

Py:   class Admin(User): pass
来源：http://dali.gaohongyu789.top/Article/details/gtnmlrsjic.html

PHP:  class Admin extends User {}
来源：http://dali.yanxiufei.cn/Article/details/gtyxtctfmc.html

JS:   class Admin extends User {}
来源：http://dali.hysaishi.cn/Article/details/gtwwwhzkbc.html

TS:   class Admin extends User {}
来源：http://dali.meibo888.top/Article/details/gtxxmkgqdk.html

Java: class Admin extends User {}
来源：http://dali.quarkkingdee.top/Article/details/gtogkxffpc.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hnqzz.top/Article/details/gtptzyydoi.html

Ruby: class Admin < User; end
来源：http://dali.yueranfly.top/Article/details/gtucqwqbgp.html

C#:   class Admin : User {}
来源：http://dali.jyoumei.cn/Article/details/gteyukwhjn.html

[G06] 重写方法
来源：http://dali.shzxlz.cn/Article/details/gtvhwqfvsl.html

Py:   def greet(self): return "admin"
来源：http://dali.hongshengwenyu.top/Article/details/gtvygnjrfq.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hnxiangtu.top/Article/details/gtpsfhxbtv.html

JS:   greet() { return "admin"; }
来源：http://dali.hnxiangtu.top/Article/details/gthcqjlhsd.html

TS:   greet(): string { return "admin"; }
来源：http://dali.nanxinkj.top/Article/details/gttnhclwtf.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.gotoacloud.top/Article/details/gtwudxeebm.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jyoumei.cn/Article/details/gtighxzray.html

Ruby: def greet; "admin"; end
来源：http://dali.yj20258.top/Article/details/gtqxtrfbpc.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhiwuduotai.top/Article/details/gtxiprcoiq.html

[G07] 调用父类方法
来源：http://dali.pengpengdd.cyou/Article/details/gtphlnvuiw.html

Py:   super().greet()
来源：http://dali.daria6918.cn/Article/details/gtkvarkbio.html

PHP:  parent::greet();
来源：http://dali.jinqigufen.top/Article/details/gtycoutbxc.html

JS:   super.greet();
来源：http://dali.nanxuanxn.top/Article/details/gtwwzklzcw.html

TS:   super.greet();
来源：http://dali.cheryme.top/Article/details/gtacaflhph.html

Java: super.greet();
来源：http://dali.sysykeji.top/Article/details/gtonckuwjk.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.sysykeji.top/Article/details/gtidmwjqde.html

Ruby: super
来源：http://dali.daxiang520.top/Article/details/gtpifnmjna.html

C#:   base.Greet();
来源：http://dali.hammf.cn/Article/details/gtdbodpjkf.html

[G08] 静态方法与属性
来源：http://dali.tian-w.cn/Article/details/gthqghlzok.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.meibo888.top/Article/details/gtqzqljksx.html

PHP:  public static function f() {}
来源：http://dali.yj202588.top/Article/details/gthebbzlor.html

JS:   static f() {}
来源：http://dali.vqdsnc.cn/Article/details/gtojddmmhu.html

TS:   static f(): void {}
来源：http://dali.cqqwz.cn/Article/details/gtpkpumrrg.html

Java: static void f() {}
来源：http://dali.yonumen.top/Article/details/gtldmkadws.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.havefunace.top/Article/details/gtstzvvgfh.html

Ruby: def self.f; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtytqzryqu.html

C#:   public static void F() {}
来源：http://dali.9152youxi.cn/Article/details/gtfrlfffzi.html

[G09] 接口 / 抽象类
来源：http://dali.xinyue.icu/Article/details/gtdbjtvvel.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zycfv.cn/Article/details/gtadvvpfsr.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.shzxlz.cn/Article/details/gtjkzjtfcd.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.snrcjt.cn/Article/details/gtsahxrsaj.html

TS:   interface Shape { area(): number; }
来源：http://dali.shuidangran.top/Article/details/gtwuzhtoqe.html

Java: interface Shape { double area(); }
来源：http://dali.andypj.xyz/Article/details/gtlfaaymft.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqomzmjtd.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xinyue.icu/Article/details/gtqdsvfimn.html

C#:   interface IShape { double Area(); }
来源：http://dali.andypj.xyz/Article/details/gtwmmvgomt.html

[G10] 访问控制
来源：http://dali.zhongyouzk.top/Article/details/gtqjmwkvjp.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.hfpthk.cn/Article/details/gtaixjcggf.html

PHP:  public / protected / private
来源：http://dali.yvedp.cn/Article/details/gtarqrhjyw.html

JS:   #private 字段；其余公开
来源：http://dali.0kj1m.cn/Article/details/gtqlwbhjbh.html

TS:   public / protected / private
来源：http://dali.yuxming.cn/Article/details/gtqgesiehr.html

Java: public / protected / private / 默认包级
来源：http://dali.yueranfly.top/Article/details/gtpfppctyf.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.sysykeji.top/Article/details/gtupfehnoc.html

Ruby: public / protected / private
来源：http://dali.fengsongda.top/Article/details/gtyirxirgq.html

C#:   public / protected / private / internal
来源：http://dali.ivvv.top/Article/details/gtpsdcxfhs.html

[G11] getter / setter
来源：http://dali.shangyingyoupin.top/Article/details/gtennfoqdp.html

Py:   @property 与 @x.setter
来源：http://dali.chenlongwang.top/Article/details/gtqnovzzfi.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.dianchejie.cn/Article/details/gtikbaiaci.html

JS:   get name() { return this._name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrltaslya.html

TS:   get name(): string { return this._name; }
来源：http://dali.daxiang520.top/Article/details/gtnyogujpp.html

Java: public String getName() { return name; }
来源：http://dali.jqgufenzy.top/Article/details/gtxvdtsydx.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jqgfzy.top/Article/details/gtiphtgwfu.html

Ruby: attr_accessor :name
来源：http://dali.bjfxy.top/Article/details/gtdzmedxlu.html

C#:   public string Name { get; set; }
来源：http://dali.meibo888.top/Article/details/gtmrpxxhef.html

[G12] 对象转字符串
来源：http://dali.pycfn.com/Article/details/gteabkpqup.html

Py:   def __str__(self): return self.name
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnkwwybnv.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jinqigfzy.top/Article/details/gtmoekoxqu.html

JS:   toString() { return this.name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtucqeaovq.html

TS:   toString(): string { return this.name; }
来源：http://dali.xziqi.cn/Article/details/gtvjubatng.html

Java: @Override public String toString() { return name; }
来源：http://dali.smart0.xyz/Article/details/gtmdyhvhra.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.gogol.net.cn/Article/details/gtqzcrquty.html

Ruby: def to_s; @name; end
来源：http://dali.wangdashe.top/Article/details/gtueyloexj.html

C#:   public override string ToString() => Name;
来源：http://dali.yonumen.top/Article/details/gtcaccdgzy.html

[G13] 判断对象类型
来源：http://dali.meibo888.top/Article/details/gtbkpfkmmk.html

Py:   isinstance(u, User)
来源：http://dali.kuanghao11.cn/Article/details/gtwuuwfcdt.html

PHP:  $u instanceof User
来源：http://dali.jinghuilouyu.cn/Article/details/gthyjxpxbf.html

JS:   u instanceof User
来源：http://dali.mhx1999.top/Article/details/gtzhvzpkhi.html

TS:   u instanceof User
来源：http://dali.bjfxy.top/Article/details/gtccqfvjlp.html

Java: u instanceof User
来源：http://dali.yuanzhike.top/Article/details/gtzmbfyoiq.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zycfv.cn/Article/details/gteykpwwjt.html

Ruby: u.is_a?(User)
来源：http://dali.mhx1999.top/Article/details/gtyuxcqcmt.html

C#:   u is User
来源：http://dali.cheryme.top/Article/details/gtkklfewcv.html

[G14] 数据类 / record
来源：http://dali.zhoulong.xyz/Article/details/gttpppszxh.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jinghuilouyu.cn/Article/details/gtpcibzjcj.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.cucudq.cn/Article/details/gtyimpiowm.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jqgfzy.top/Article/details/gttjtcpwix.html

TS:   type User = { name: string; age: number };
来源：http://dali.guannengcc.top/Article/details/gtbvekfzsm.html

Java: record User(String name, int age) {}
来源：http://dali.daxiang520.top/Article/details/gtpmnqannf.html

Go:   type User struct { Name string; Age int }
来源：http://dali.cucudq.cn/Article/details/gtfcumkqge.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.pengpengdd.cyou/Article/details/gtjanvxqdi.html

C#:   record User(string Name, int Age);
来源：http://dali.redwolf501.top/Article/details/gtlxtgosjh.html

[G15] 枚举
来源：http://dali.dianchejie.cn/Article/details/gtjvvrackf.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.tianlin.xyz/Article/details/gtzweyrpob.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.hnqzz.top/Article/details/gtprmqcrvz.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.dianchejie.cn/Article/details/gtsrhmxcii.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cheryme.top/Article/details/gtbbxgpsyt.html

Java: enum Color { RED, GREEN }
来源：http://dali.xziqi.cn/Article/details/gtecvnvyvu.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwzlpnxmh.html

Ruby: Color = %i[red green].freeze
来源：http://dali.sxryk.cn/Article/details/gtfasrgcjk.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jlsjyb.cn/Article/details/gtkdjoyywn.html

[G16] 对象转数组 / 字典
来源：http://dali.dianchejie.cn/Article/details/gtplcpkbgj.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.nanxuanxn.top/Article/details/gtocijmper.html

PHP:  get_object_vars($obj);
来源：http://dali.pycfn.com/Article/details/gtiblzweop.html

JS:   Object.entries(obj)
来源：http://dali.iojbl.cn/Article/details/gtnnkulnah.html

TS:   Object.entries(obj)
来源：http://dali.nwbrower.top/Article/details/gtlypwbsqu.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yueranfly.top/Article/details/gtpblzogzd.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jinqigufen.top/Article/details/gtmgzgjkfk.html

Ruby: obj.instance_variables
来源：http://dali.ybcxt.top/Article/details/gthitqsyxj.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.kuanghao11.cn/Article/details/gticmzmsna.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdpmfpifx.html

H. 异常与错误处理
来源：http://dali.zhixingplan.top/Article/details/gtssflymqe.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtxbozwezx.html

[H01] try / catch 基础
来源：http://dali.zycfv.cn/Article/details/gtuvsrjupl.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.aibaodan.cn/Article/details/gtkuladlxk.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.tanke756.top/Article/details/gttnwzjtgj.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.tian-w.cn/Article/details/gtaegpszhg.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.cdnleiting.top/Article/details/gtkafqaahb.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.wangdashe.top/Article/details/gtoompvpyw.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.xziqi.cn/Article/details/gthnjjcwyd.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.nanxuanxn.top/Article/details/gtdivmefyh.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.aibaodan.cn/Article/details/gtqcurwrgi.html

[H02] finally / ensure 收尾
来源：http://dali.zhengqikj.top/Article/details/gturwgvexf.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.aizwys.cn/Article/details/gtrkvxvmov.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkkixinrn.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.xylfe.cn/Article/details/gtgnavtuhw.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.nanxuanxn.top/Article/details/gtuyrcimgr.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.tian-w.cn/Article/details/gtlqtmoucz.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhixingplan.top/Article/details/gtbadufbok.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yj202588.top/Article/details/gtccvwrafh.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.xziqi.cn/Article/details/gttpyayybl.html

[H03] 主动抛出异常
来源：http://dali.svipenyu.cn/Article/details/gtsvykqeec.html

Py:   raise ValueError("错误信息")
来源：http://dali.ywan-chungtsiang.top/Article/details/gttqpiyxpb.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.chenlongwang.top/Article/details/gtvoqzosiv.html

JS:   throw new Error("错误信息");
来源：http://dali.guannengcc.top/Article/details/gtpiwezcdm.html

TS:   throw new Error("错误信息");
来源：http://dali.aibaodan.cn/Article/details/gtkyelljuq.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.ehwqpu.com/Article/details/gtreozktge.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.shangyingyoupin.top/Article/details/gtljvdfjit.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoczqwnku.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.0kj1m.cn/Article/details/gtqqkmupcu.html

[H04] 自定义异常类型
来源：http://dali.c1oappe.top/Article/details/gtoucolkbt.html

Py:   class MyError(Exception): pass
来源：http://dali.wangshuangyany.cn/Article/details/gtoburxgyt.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.sufxvd.cn/Article/details/gtrofuzqqp.html

JS:   class MyError extends Error {}
来源：http://dali.mhx1999.top/Article/details/gtdnhjvnvi.html

TS:   class MyError extends Error {}
来源：http://dali.nwbrower.top/Article/details/gtrbymngqu.html

Java: class MyException extends RuntimeException {}
来源：http://dali.cdnleiting.top/Article/details/gtyvofmpxk.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.sufxvd.cn/Article/details/gtzhxzzkli.html

Ruby: class MyError < StandardError; end
来源：http://dali.chenzaomai.com/Article/details/gttktqnkxz.html

C#:   class MyException : Exception {}
来源：http://dali.zycfv.cn/Article/details/gttofnvwcg.html

[H05] 捕获特定类型
来源：http://dali.xuetiantiany.cn/Article/details/gtqyjmsocy.html

Py:   except ValueError as e:
来源：http://dali.jiagoushi.top/Article/details/gtceyotyde.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.hongshengwenyu.top/Article/details/gtxnbkjcqi.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yueranfly.top/Article/details/gtobqxdfub.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yangfankeji.com/Article/details/gtefssgeil.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.smart0.xyz/Article/details/gthqjcmjfx.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxsmywpfj.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhongyouzk.top/Article/details/gtpkxxoqdj.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.ehwqpu.com/Article/details/gtvcfktcha.html

[H06] 可选值 / 空值安全访问
来源：http://dali.sweek.top/Article/details/gtnzwncrdc.html

Py:   value = d.get("k") or default
来源：http://dali.guowangkeji.top/Article/details/gtuutmymfg.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.0kj1m.cn/Article/details/gtpgermrnu.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.ehwqpu.com/Article/details/gtzlhaozrj.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.vqdsnc.cn/Article/details/gtemjthpng.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.aibaodan.cn/Article/details/gtdrpxwaiz.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yj20258888.top/Article/details/gtdmarclxp.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhoulong.xyz/Article/details/gtkorxiler.html

C#:   obj?.A?.B ?? default
来源：http://dali.jqgufenzy.top/Article/details/gtsvegvzmb.html

[H07] 断言
来源：http://dali.gotoacloud.top/Article/details/gtbdydfeae.html

Py:   assert x > 0, "必须为正"
来源：http://dali.nanxinkj.top/Article/details/gtifxmxnho.html

PHP:  assert($x > 0);
来源：http://dali.jiagoushi.top/Article/details/gteuswiesk.html

JS:   console.assert(x > 0);
来源：http://dali.gzhubu.top/Article/details/gtfbwmswjw.html

TS:   console.assert(x > 0);
来源：http://dali.shzxlz.cn/Article/details/gtuvsemmwd.html

Java: assert x > 0 : "必须为正";
来源：http://dali.gzhubu.top/Article/details/gtdqenojba.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.havefunace.top/Article/details/gtsdseojqz.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.birdmap.top/Article/details/gtaysxpiup.html

C#:   Debug.Assert(x > 0);
来源：http://dali.guannengcc.top/Article/details/gtjotislqt.html

[H08] 获取错误信息与堆栈
来源：http://dali.mhx1999.top/Article/details/gtknbykvwq.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.chenzaomai.com/Article/details/gtahrhhwjh.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yj202588.top/Article/details/gtzymbgjnb.html

JS:   e.message;  e.stack
来源：http://dali.yonumen.top/Article/details/gtsfgipfnk.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.cheryme.top/Article/details/gtdmozpmcj.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.ydzc1.top/Article/details/gtvuaoyryr.html

Go:   err.Error()
来源：http://dali.hysaishi.cn/Article/details/gtfibkftqf.html

Ruby: e.message;  e.backtrace
来源：http://dali.cashguo.top/Article/details/gtnsuxtcwp.html

C#:   e.Message;  e.StackTrace
来源：http://dali.redwolf501.top/Article/details/gtpwxstxqw.html

[H09] 带错误码的异常
来源：http://dali.cheryme.top/Article/details/gtheivpdqn.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.dashuyun.cn/Article/details/gttpvarfyz.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.dashuyun.cn/Article/details/gtluawubdl.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yonumen.top/Article/details/gttilxtxpf.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.hnqzz.top/Article/details/gtcggwdriv.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.xylfe.cn/Article/details/gtdtxoslrb.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.cdnleiting.top/Article/details/gtwqvwtshe.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.xuetiantiany.cn/Article/details/gtmsdyxnuz.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.ybcxt.top/Article/details/gtrpcvmwpg.html

[H10] 资源自动释放
来源：http://dali.cheryme.top/Article/details/gtzmjvinnu.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.xziqi.cn/Article/details/gtohuacxlj.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.tanke756.top/Article/details/gttiljtvwf.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinqigufen.top/Article/details/gtcguzgqdc.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hammf.cn/Article/details/gtpfqrubci.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.svipenyu.cn/Article/details/gtcnmbwhum.html

Go:   defer f.Close()
来源：http://dali.nanxinkj.top/Article/details/gtmhgnhzca.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhoulong.xyz/Article/details/gtyclgrhjt.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gtidqvrqgs.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtgkpmdevz.html

I. 正则表达式
来源：http://dali.guannengcc.top/Article/details/gtynwacoft.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtintgwiag.html

[I01] 判断是否匹配
来源：http://dali.zhiwuduotai.top/Article/details/gtktjxoftp.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.hammf.cn/Article/details/gtapyvhejz.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.chenlongwang.top/Article/details/gttfirakai.html

JS:   /\d+/.test(s)
来源：http://dali.dashuyun.cn/Article/details/gtuiqmpvih.html

TS:   /\d+/.test(s)
来源：http://dali.jqgufenzy.top/Article/details/gtnovnglyv.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkcinfdjz.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yongpay.top/Article/details/gtacvayyxp.html

Ruby: s.match?(/\d+/)
来源：http://dali.shzxlz.cn/Article/details/gtlfjxloud.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.hywenlv.cn/Article/details/gtimjjhkru.html

[I02] 提取所有匹配
来源：http://dali.zhengqikj.top/Article/details/gtfawsxkfn.html

Py:   re.findall(r"\d+", s)
来源：http://dali.hnqzz.top/Article/details/gtxtvlflvx.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yj20258.top/Article/details/gthforaanz.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.shanyushiyangtech.top/Article/details/gtfxtpyrrj.html

TS:   s.match(/\d+/g)
来源：http://dali.shuidangran.top/Article/details/gtdkhdrfma.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.wangdashe.top/Article/details/gtaqrlfzvo.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.ehwqpu.com/Article/details/gtmyelyuvp.html

Ruby: s.scan(/\d+/)
来源：http://dali.zhijiandao.cn/Article/details/gtpdgkjwfm.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yongpay.top/Article/details/gtghmespgm.html

[I03] 提取捕获分组
来源：http://dali.tian-w.cn/Article/details/gtdxdjznzq.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.gzhubu.top/Article/details/gtribrfqet.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.daxiang520.top/Article/details/gtkbxallta.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jqgufenzy.top/Article/details/gtxlxztkbi.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yanxiufei.cn/Article/details/gtjnkwqqit.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.shangyingyoupin.top/Article/details/gtymfplvmb.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yuxming.cn/Article/details/gtvoqohsll.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.cheryme.top/Article/details/gtjdtltqtc.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.gaohongyu789.top/Article/details/gtzyonxwsd.html

[I04] 正则替换
来源：http://dali.sysykeji.top/Article/details/gtiwylqyqv.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.quarkkingdee.top/Article/details/gteqonywok.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.gaohongyu789.top/Article/details/gtgsmuqucq.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.zhoulong.xyz/Article/details/gtsptbacom.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.hywenlv.cn/Article/details/gtzfzwsedm.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.bjfxy.top/Article/details/gtjoeubrpq.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.guowangkeji.top/Article/details/gtejxfhkpc.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.cdnleiting.top/Article/details/gtpjwiwxmx.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.hnxiangtu.top/Article/details/gtjjopleej.html

[I05] 按正则拆分
来源：http://dali.jianghu66.top/Article/details/gtjovkmztb.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrzhtnfwb.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.shzxlz.cn/Article/details/gtjruksiao.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yj20258888.top/Article/details/gtdldmwhus.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.nwbrower.top/Article/details/gttiuinmoj.html

Java: s.split("\\s*,\\s*")
来源：http://dali.havefunace.top/Article/details/gtnmahntgy.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.jinqigufen.top/Article/details/gtqhsukhbt.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.gogol.net.cn/Article/details/gtjieaaqgd.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.iojbl.cn/Article/details/gtslmtwdko.html


<!-- 参考信息 -->