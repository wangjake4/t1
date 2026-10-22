代发 wailian999

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtfmizbdwg.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.chenlongwang.top/Article/details/gthdrqkrln.html

[F11] 复制与移动文件
来源：http://dali.hfpthk.cn/Article/details/gttvpbeeeb.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.nanxinkj.top/Article/details/gtrwxzkmms.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.daxiang520.top/Article/details/gtrawttciw.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ppjwa.cn/Article/details/gtfdvonhrg.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtowzbdbsq.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.feifeiyinyue.top/Article/details/gtjjptfhwh.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.haohaochexian.top/Article/details/gtqlveadag.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jinqigufen.top/Article/details/gtmitagnpi.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zdqjudy.top/Article/details/gtfebtfkav.html

[F12] CSV 读写
来源：http://dali.quarkkingdee.top/Article/details/gtkrqqqmor.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.aizwys.cn/Article/details/gtudwzrixn.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yj20258.top/Article/details/gtvfnjtmva.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.smart0.xyz/Article/details/gtckvquutx.html

TS:   // 同上
来源：http://dali.snrcjt.cn/Article/details/gtnrxumpvw.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.nanxuanxn.top/Article/details/gtxkelbbht.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hywenlv.cn/Article/details/gtxrjxjfka.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.dianchejie.cn/Article/details/gtnyoxanvh.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.meibo888.top/Article/details/gtijrtkqkw.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtwnmqcmdy.html

G. 面向对象
来源：http://dali.hammf.cn/Article/details/gtwuuodehy.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdiprhnmc.html

[G01] 定义类
来源：http://dali.chenlongwang.top/Article/details/gtwmuspmgk.html

Py:   class User: pass
来源：http://dali.chenjidiqi.icu/Article/details/gtruutrcpx.html

PHP:  class User {}
来源：http://dali.fengsongda.top/Article/details/gtvyynotmp.html

JS:   class User {}
来源：http://dali.guowangkeji.top/Article/details/gtxmiqhads.html

TS:   class User { name: string = ""; }
来源：http://dali.sxryk.cn/Article/details/gtyhzyxxuk.html

Java: class User {}
来源：http://dali.gogol.net.cn/Article/details/gtqohxhvvo.html

Go:   type User struct { Name string }
来源：http://dali.tianlin.xyz/Article/details/gtzwqnysqz.html

Ruby: class User; end
来源：http://dali.meibo888.top/Article/details/gtwfykmtwx.html

C#:   class User {}
来源：http://dali.iojbl.cn/Article/details/gtbmqjhfgf.html

[G02] 构造函数
来源：http://dali.dianchejie.cn/Article/details/gtgvgscniy.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhixingplan.top/Article/details/gtwaycktsi.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.ivvv.top/Article/details/gtrrjixytp.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.tianlin.xyz/Article/details/gtuovkzgzq.html

TS:   constructor(public name: string) {}
来源：http://dali.jyoumei.cn/Article/details/gthltcjjrw.html

Java: User(String name) { this.name = name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtvscucjdm.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.dashuyun.cn/Article/details/gtejywdxlj.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yuanzhike.top/Article/details/gtyztwvpne.html

C#:   public User(string name) { Name = name; }
来源：http://dali.smart0.xyz/Article/details/gtxvbezdea.html

[G03] 实例属性
来源：http://dali.yanxiufei.cn/Article/details/gttwkefvyt.html

Py:   self.name = "x"
来源：http://dali.zhixingplan.top/Article/details/gtjnkugnvv.html

PHP:  public string $name = "x";
来源：http://dali.cashguo.top/Article/details/gtjnnsauil.html

JS:   this.name = "x";
来源：http://dali.wangshuangyany.cn/Article/details/gtuopenvjj.html

TS:   name: string = "x";
来源：http://dali.smart0.xyz/Article/details/gtxcryfbjp.html

Java: private String name;
来源：http://dali.ehwqpu.com/Article/details/gtpkdrnhte.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.wangshuangyany.cn/Article/details/gtspfkdmno.html

Ruby: @name = "x"
来源：http://dali.redwolf501.top/Article/details/gtqjvvkyla.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yueranfly.top/Article/details/gtxvxwhovc.html

[G04] 定义方法
来源：http://dali.guannengcc.top/Article/details/gtbwkegjxu.html

Py:   def greet(self): return self.name
来源：http://dali.daria6918.cn/Article/details/gtpkjfkltl.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtafamhuup.html

JS:   greet() { return this.name; }
来源：http://dali.jinqigfzy.top/Article/details/gtphstxdwo.html

TS:   greet(): string { return this.name; }
来源：http://dali.sweek.top/Article/details/gtlkesjspd.html

Java: String greet() { return name; }
来源：http://dali.jqgfzy.top/Article/details/gtuquvloxu.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hammf.cn/Article/details/gtjdofhpxy.html

Ruby: def greet; @name; end
来源：http://dali.sxryk.cn/Article/details/gtrcuyywpb.html

C#:   public string Greet() => Name;
来源：http://dali.snrcjt.cn/Article/details/gtarmzrtfs.html

[G05] 继承
来源：http://dali.zhixingplan.top/Article/details/gtwdcncscw.html

Py:   class Admin(User): pass
来源：http://dali.jinqigufen.top/Article/details/gtijydskei.html

PHP:  class Admin extends User {}
来源：http://dali.andypj.xyz/Article/details/gtzafueovb.html

JS:   class Admin extends User {}
来源：http://dali.wangdashe.top/Article/details/gtqhrepdxv.html

TS:   class Admin extends User {}
来源：http://dali.yj202588.top/Article/details/gtpxeqsvan.html

Java: class Admin extends User {}
来源：http://dali.ppjwa.cn/Article/details/gtjtqbflxj.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.gaohongyu789.top/Article/details/gtdmivltax.html

Ruby: class Admin < User; end
来源：http://dali.yanxiufei.cn/Article/details/gtvbfqgigf.html

C#:   class Admin : User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvmkbxrid.html

[G06] 重写方法
来源：http://dali.fengsongda.top/Article/details/gtafpqrcyn.html

Py:   def greet(self): return "admin"
来源：http://dali.snrcjt.cn/Article/details/gtiizcpsoh.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.ydzc1.top/Article/details/gtvhgylnfw.html

JS:   greet() { return "admin"; }
来源：http://dali.yueranfly.top/Article/details/gtqxbzgeay.html

TS:   greet(): string { return "admin"; }
来源：http://dali.tian-w.cn/Article/details/gtnxnwbyro.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.redwolf501.top/Article/details/gtpomfasrd.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yj20258.top/Article/details/gtsbfwgryp.html

Ruby: def greet; "admin"; end
来源：http://dali.redwolf501.top/Article/details/gtuebiffaj.html

C#:   public override string Greet() => "admin";
来源：http://dali.aibaodan.cn/Article/details/gtviuhqgci.html

[G07] 调用父类方法
来源：http://dali.guannengcc.top/Article/details/gtlqqoevgx.html

Py:   super().greet()
来源：http://dali.yvedp.cn/Article/details/gteltklgvl.html

PHP:  parent::greet();
来源：http://dali.wangdashe.top/Article/details/gtxdqktuzc.html

JS:   super.greet();
来源：http://dali.yj20258.top/Article/details/gtrqokwcpa.html

TS:   super.greet();
来源：http://dali.nanxinkj.top/Article/details/gthewowumd.html

Java: super.greet();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteyilakkb.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.aibaodan.cn/Article/details/gtrhtqfsta.html

Ruby: super
来源：http://dali.gaohongyu789.top/Article/details/gthsxmzgzl.html

C#:   base.Greet();
来源：http://dali.guannengcc.top/Article/details/gtwfegrlik.html

[G08] 静态方法与属性
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtchdbjips.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.wangdashe.top/Article/details/gtoclzqjhp.html

PHP:  public static function f() {}
来源：http://dali.pengpengdd.cyou/Article/details/gtwmqusyml.html

JS:   static f() {}
来源：http://dali.daxiang520.top/Article/details/gtxrsykvzo.html

TS:   static f(): void {}
来源：http://dali.feifeiyinyue.top/Article/details/gtbxnbwfgl.html

Java: static void f() {}
来源：http://dali.gaohongyu789.top/Article/details/gtjrngiswk.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.ivvv.top/Article/details/gtttfmscou.html

Ruby: def self.f; end
来源：http://dali.havefunace.top/Article/details/gtlptzgvum.html

C#:   public static void F() {}
来源：http://dali.andypj.xyz/Article/details/gtrlhqgney.html

[G09] 接口 / 抽象类
来源：http://dali.birdmap.top/Article/details/gtqnnxllbg.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.gzhubu.top/Article/details/gtofrylmnh.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.fengsongda.top/Article/details/gtxyhhuycq.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jinqigufen.top/Article/details/gteegaiuxd.html

TS:   interface Shape { area(): number; }
来源：http://dali.andypj.xyz/Article/details/gtotrazrjj.html

Java: interface Shape { double area(); }
来源：http://dali.fengsongda.top/Article/details/gtfobuucsc.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.smart0.xyz/Article/details/gtgsgzywyr.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.sysykeji.top/Article/details/gtjvtuaiwo.html

C#:   interface IShape { double Area(); }
来源：http://dali.kuanghao11.cn/Article/details/gtonwjgvnb.html

[G10] 访问控制
来源：http://dali.svipenyu.cn/Article/details/gtlexknlzt.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.316326.xyz/Article/details/gttflzvyim.html

PHP:  public / protected / private
来源：http://dali.fzhhl.top/Article/details/gtyvwsfsow.html

JS:   #private 字段；其余公开
来源：http://dali.nanxinkj.top/Article/details/gtglwpyrcz.html

TS:   public / protected / private
来源：http://dali.chenlongwang.top/Article/details/gtznubshmj.html

Java: public / protected / private / 默认包级
来源：http://dali.xinyue.icu/Article/details/gtjfgxwhzr.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.shuidangran.top/Article/details/gtpoaxtsdx.html

Ruby: public / protected / private
来源：http://dali.jlsjyb.cn/Article/details/gttlqfxuro.html

C#:   public / protected / private / internal
来源：http://dali.gogol.net.cn/Article/details/gtsoylqcfu.html

[G11] getter / setter
来源：http://dali.shzxlz.cn/Article/details/gtixyqnbcn.html

Py:   @property 与 @x.setter
来源：http://dali.wangshuangyany.cn/Article/details/gtcclokhev.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.0kj1m.cn/Article/details/gtixmtediy.html

JS:   get name() { return this._name; }
来源：http://dali.dianchejie.cn/Article/details/gtbepbxhwv.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjfkiypzs.html

Java: public String getName() { return name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvlgjjkfb.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xinyue.icu/Article/details/gtjfqchawl.html

Ruby: attr_accessor :name
来源：http://dali.jqgfzy.top/Article/details/gtdkrmnoqm.html

C#:   public string Name { get; set; }
来源：http://dali.jyoumei.cn/Article/details/gtjrnwoyjj.html

[G12] 对象转字符串
来源：http://dali.c1oappe.top/Article/details/gtyntdtfpz.html

Py:   def __str__(self): return self.name
来源：http://dali.yvedp.cn/Article/details/gtvlmjvyds.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yanxiufei.cn/Article/details/gtljgqctrq.html

JS:   toString() { return this.name; }
来源：http://dali.chenzaomai.com/Article/details/gtezfbdnfx.html

TS:   toString(): string { return this.name; }
来源：http://dali.zycfv.cn/Article/details/gtzszncsnb.html

Java: @Override public String toString() { return name; }
来源：http://dali.zycfv.cn/Article/details/gttsoxfuos.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.dianchejie.cn/Article/details/gtowaypdkb.html

Ruby: def to_s; @name; end
来源：http://dali.jianghu66.top/Article/details/gtummdibev.html

C#:   public override string ToString() => Name;
来源：http://dali.jinqigufen.top/Article/details/gtafgzortt.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gtfomsrtvg.html

Py:   isinstance(u, User)
来源：http://dali.yangfankeji.com/Article/details/gtalsijsdv.html

PHP:  $u instanceof User
来源：http://dali.shangyingyoupin.top/Article/details/gttqgasboi.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gtcmitpwpp.html

TS:   u instanceof User
来源：http://dali.hnxiangtu.top/Article/details/gtpknezqxh.html

Java: u instanceof User
来源：http://dali.fengsongda.top/Article/details/gthxusetmv.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zycfv.cn/Article/details/gtujjykoee.html

Ruby: u.is_a?(User)
来源：http://dali.chenjidiqi.icu/Article/details/gthowouuvg.html

C#:   u is User
来源：http://dali.zhoulong.xyz/Article/details/gticobmfzg.html

[G14] 数据类 / record
来源：http://dali.zhoulong.xyz/Article/details/gtxxjdajno.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.cucudq.cn/Article/details/gtwefhbnjf.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.xinyue.icu/Article/details/gtpnondydv.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zdqjudy.top/Article/details/gtdiujgihs.html

TS:   type User = { name: string; age: number };
来源：http://dali.jqgufenzy.top/Article/details/gtnoeakehm.html

Java: record User(String name, int age) {}
来源：http://dali.yj202588.top/Article/details/gtegygoxjl.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jinqigfzy.top/Article/details/gttvntkamv.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.ybcxt.top/Article/details/gtsdrzetqa.html

C#:   record User(string Name, int Age);
来源：http://dali.redwolf501.top/Article/details/gtnjwulquy.html

[G15] 枚举
来源：http://dali.haohaochexian.top/Article/details/gtomnndvjq.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.shangyingyoupin.top/Article/details/gtzbltbmep.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.hnxiangtu.top/Article/details/gtpmfcwzlp.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhixingplan.top/Article/details/gtrdkfoche.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xziqi.cn/Article/details/gtxhdnueen.html

Java: enum Color { RED, GREEN }
来源：http://dali.ivvv.top/Article/details/gtrfqrhaij.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.redwolf501.top/Article/details/gtrqjnkzfl.html

Ruby: Color = %i[red green].freeze
来源：http://dali.hammf.cn/Article/details/gtxgehovzr.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.haohaochexian.top/Article/details/gtrzqobpvu.html

[G16] 对象转数组 / 字典
来源：http://dali.ehwqpu.com/Article/details/gtgyuswaop.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.shanyushiyangtech.top/Article/details/gtmqfdoqpj.html

PHP:  get_object_vars($obj);
来源：http://dali.pycfn.com/Article/details/gtmlmvvmwy.html

JS:   Object.entries(obj)
来源：http://dali.chenlongwang.top/Article/details/gtxofbnxyu.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gtwrklsgqx.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhongyouzk.top/Article/details/gtabrzntoo.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.hnqzz.top/Article/details/gtenbkxjkg.html

Ruby: obj.instance_variables
来源：http://dali.cucudq.cn/Article/details/gtkwusleeh.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yangfankeji.com/Article/details/gtkemzmmzl.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtnueivmzh.html

H. 异常与错误处理
来源：http://dali.hammf.cn/Article/details/gtdyusqrya.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtqssdjcku.html

[H01] try / catch 基础
来源：http://dali.yongpay.top/Article/details/gtuilmlgpj.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.daxiang520.top/Article/details/gtokinrqvn.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtqlguwcng.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.xinyue.icu/Article/details/gtqnflryxi.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvpgiqqcz.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.sysykeji.top/Article/details/gtvwsyphig.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.bjfxy.top/Article/details/gtgirkaydf.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.aizwys.cn/Article/details/gtrjwgqlgr.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.cucudq.cn/Article/details/gtveviprme.html

[H02] finally / ensure 收尾
来源：http://dali.havefunace.top/Article/details/gtfrrqxhlh.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.dianchejie.cn/Article/details/gtzalowyst.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jianghu66.top/Article/details/gtwwlcitli.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.guannengcc.top/Article/details/gtunfngfnd.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yuxming.cn/Article/details/gtqhjxaqsl.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.cdnleiting.top/Article/details/gtuuqctmzc.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yuxming.cn/Article/details/gtmydarqxh.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.hfpthk.cn/Article/details/gtdmlvuako.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.sysykeji.top/Article/details/gtnfqcpwbo.html

[H03] 主动抛出异常
来源：http://dali.hysaishi.cn/Article/details/gtlcfocoog.html

Py:   raise ValueError("错误信息")
来源：http://dali.yj202588.top/Article/details/gtwitvtviw.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsrpgxxsw.html

JS:   throw new Error("错误信息");
来源：http://dali.gaohongyu789.top/Article/details/gtqxhixnco.html

TS:   throw new Error("错误信息");
来源：http://dali.svipenyu.cn/Article/details/gtotfnqpwg.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hnqzz.top/Article/details/gtzaudluoo.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yj20258.top/Article/details/gtpzdkregc.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hfpthk.cn/Article/details/gtsukyhoiq.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jyoumei.cn/Article/details/gtptntcgrn.html

[H04] 自定义异常类型
来源：http://dali.hammf.cn/Article/details/gttgajxdfw.html

Py:   class MyError(Exception): pass
来源：http://dali.hysaishi.cn/Article/details/gtzdktjybh.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.svipenyu.cn/Article/details/gtajttdpae.html

JS:   class MyError extends Error {}
来源：http://dali.tianlin.xyz/Article/details/gtlcwqlros.html

TS:   class MyError extends Error {}
来源：http://dali.meibo888.top/Article/details/gtxbwhrlex.html

Java: class MyException extends RuntimeException {}
来源：http://dali.kuanghao11.cn/Article/details/gtlwqznrro.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jinghuilouyu.cn/Article/details/gtsietqdgs.html

Ruby: class MyError < StandardError; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcsybqevj.html

C#:   class MyException : Exception {}
来源：http://dali.tian-w.cn/Article/details/gtabwspgoq.html

[H05] 捕获特定类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvomlpdfw.html

Py:   except ValueError as e:
来源：http://dali.jqgufenzy.top/Article/details/gtdkbnwfjh.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zdqjudy.top/Article/details/gtgyxkmeln.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.fzhhl.top/Article/details/gtnkbpfiyc.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.aizwys.cn/Article/details/gtefovtleo.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.aibaodan.cn/Article/details/gtwtkgtmpl.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yangfankeji.com/Article/details/gticxhsenz.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhiwuduotai.top/Article/details/gtoxqpckti.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.birdmap.top/Article/details/gtpxwazbqp.html

[H06] 可选值 / 空值安全访问
来源：http://dali.svipenyu.cn/Article/details/gthpygkewm.html

Py:   value = d.get("k") or default
来源：http://dali.yonumen.top/Article/details/gtlvoyodsk.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.xziqi.cn/Article/details/gtyvbcozzq.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.gogol.net.cn/Article/details/gtxqbbqrbp.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jianghu66.top/Article/details/gtaqroclzd.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.feifeiyinyue.top/Article/details/gtjncvslrn.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.hammf.cn/Article/details/gtwnhcktvf.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuzquujhe.html

C#:   obj?.A?.B ?? default
来源：http://dali.snrcjt.cn/Article/details/gtmitqnlla.html

[H07] 断言
来源：http://dali.jqgufenzy.top/Article/details/gtjzoujajr.html

Py:   assert x > 0, "必须为正"
来源：http://dali.daxiang520.top/Article/details/gtikvyupoc.html

PHP:  assert($x > 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtybjztgot.html

JS:   console.assert(x > 0);
来源：http://dali.daria6918.cn/Article/details/gtmwkxckyb.html

TS:   console.assert(x > 0);
来源：http://dali.chenzaomai.com/Article/details/gtqeqvtpki.html

Java: assert x > 0 : "必须为正";
来源：http://dali.meibo888.top/Article/details/gtntmdpmrt.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.hywenlv.cn/Article/details/gtlbkmccvi.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hongshengwenyu.top/Article/details/gtdimbynhy.html

C#:   Debug.Assert(x > 0);
来源：http://dali.sxryk.cn/Article/details/gtcrvwtzmz.html

[H08] 获取错误信息与堆栈
来源：http://dali.shangyingyoupin.top/Article/details/gtblhrqjan.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.ppjwa.cn/Article/details/gtcgpraeer.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yueranfly.top/Article/details/gtkwnbpwvp.html

JS:   e.message;  e.stack
来源：http://dali.dashuyun.cn/Article/details/gtdmfoewby.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.guowangkeji.top/Article/details/gtyeurtvyy.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhixingplan.top/Article/details/gtogbimifc.html

Go:   err.Error()
来源：http://dali.hfpthk.cn/Article/details/gtizengkni.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlhpiztle.html

C#:   e.Message;  e.StackTrace
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxnimauhs.html

[H09] 带错误码的异常
来源：http://dali.hongshengwenyu.top/Article/details/gtxtzjxggx.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.shzxlz.cn/Article/details/gtohkzalyz.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.ppjwa.cn/Article/details/gtdzxywfcy.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.kuanghao11.cn/Article/details/gtxnyivurp.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.sysykeji.top/Article/details/gtpmdsgkoh.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.ybcxt.top/Article/details/gttajadamv.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yj20258.top/Article/details/gtnxiehems.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gtkkdybbkn.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.pycfn.com/Article/details/gthpndcudu.html

[H10] 资源自动释放
来源：http://dali.xziqi.cn/Article/details/gtolhqsyou.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.0kj1m.cn/Article/details/gtftabwsdk.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.9152youxi.cn/Article/details/gtbbcrjvsz.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gzhubu.top/Article/details/gtohncyrlk.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.kuanghao11.cn/Article/details/gtyvyvbdxx.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hywenlv.cn/Article/details/gtizgzmaqk.html

Go:   defer f.Close()
来源：http://dali.jianghu66.top/Article/details/gtdidwdqqp.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yanxiufei.cn/Article/details/gtqyebukmh.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.sysykeji.top/Article/details/gtbugaxbtl.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtvjltyfsb.html

I. 正则表达式
来源：http://dali.andypj.xyz/Article/details/gtuiyrccyn.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gttjlhecfs.html

[I01] 判断是否匹配
来源：http://dali.xinyue.icu/Article/details/gtnqdtqufv.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.cashguo.top/Article/details/gtpaxoulyq.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jlsjyb.cn/Article/details/gtwhwusfzd.html

JS:   /\d+/.test(s)
来源：http://dali.snrcjt.cn/Article/details/gtnzwjegxv.html

TS:   /\d+/.test(s)
来源：http://dali.316326.xyz/Article/details/gtwxbirglw.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.gzhubu.top/Article/details/gtqfhrirdg.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jqgufenzy.top/Article/details/gtfmganpfo.html

Ruby: s.match?(/\d+/)
来源：http://dali.jinghuilouyu.cn/Article/details/gtwvurdhwt.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yj20258.top/Article/details/gtknygfmbl.html

[I02] 提取所有匹配
来源：http://dali.jinqigufen.top/Article/details/gthycsktgm.html

Py:   re.findall(r"\d+", s)
来源：http://dali.cucudq.cn/Article/details/gtufdewuik.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.hnqzz.top/Article/details/gtrpumfuto.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jiagoushi.top/Article/details/gtclmxgxiu.html

TS:   s.match(/\d+/g)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtynjjoalt.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.mhx1999.top/Article/details/gttciiheii.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.gogol.net.cn/Article/details/gtvjldibit.html

Ruby: s.scan(/\d+/)
来源：http://dali.bjfxy.top/Article/details/gtoaiueooh.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.wangshuangyany.cn/Article/details/gtcvnjwmev.html

[I03] 提取捕获分组
来源：http://dali.ybcxt.top/Article/details/gtahwcjmmr.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.ybcxt.top/Article/details/gtbhwvqxqv.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.316326.xyz/Article/details/gtuijuhmmn.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.hfpthk.cn/Article/details/gtjbdxuehz.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.sweek.top/Article/details/gtlgfxdelo.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.meibo888.top/Article/details/gtwbujnbns.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yvedp.cn/Article/details/gtcecjewtx.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.havefunace.top/Article/details/gtmtkczorb.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.hnxiangtu.top/Article/details/gtuktgchht.html

[I04] 正则替换
来源：http://dali.sweek.top/Article/details/gtlyqbzwiu.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.ivvv.top/Article/details/gtfqotiwkb.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yongpay.top/Article/details/gtnnhbsigr.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.iojbl.cn/Article/details/gtuyzugkpd.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.zycfv.cn/Article/details/gtkwwqcehd.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jinqigfzy.top/Article/details/gtzmxcbghm.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.tian-w.cn/Article/details/gtpoxdjpug.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.vqdsnc.cn/Article/details/gtlgpcprpe.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.ivvv.top/Article/details/gtzgcssnlz.html

[I05] 按正则拆分
来源：http://dali.shanyushiyangtech.top/Article/details/gtsfltkudv.html


<!-- 参考信息 -->