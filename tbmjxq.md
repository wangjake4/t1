代发 wailian999

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.tian-w.cn/Article/details/gtbdvbxhen.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.316326.xyz/Article/details/gtybmjufwb.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtthqtjcze.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.guowangkeji.top/Article/details/gtlhzhnqek.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.cheryme.top/Article/details/gtdadqxsty.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yuxming.cn/Article/details/gtjxevsalo.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.cqqwz.cn/Article/details/gtsaxythkf.html

[F12] CSV 读写
来源：http://dali.mhx1999.top/Article/details/gtoilvynxt.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtypbjwema.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zycfv.cn/Article/details/gtucduuwdh.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.c1oappe.top/Article/details/gtytitohyk.html

TS:   // 同上
来源：http://dali.aibaodan.cn/Article/details/gtemrfdfhb.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.redwolf501.top/Article/details/gtxyfoakeu.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.gzhubu.top/Article/details/gtaphbtvhq.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.xylfe.cn/Article/details/gtttasjsqb.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.bjfxy.top/Article/details/gtoszyfelt.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtsvlcuwhf.html

G. 面向对象
来源：http://dali.nanxinkj.top/Article/details/gtkxivrkiq.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtuxlctnvz.html

[G01] 定义类
来源：http://dali.gotoacloud.top/Article/details/gtbpmgwmqp.html

Py:   class User: pass
来源：http://dali.jiagoushi.top/Article/details/gttqlwkmhf.html

PHP:  class User {}
来源：http://dali.vqdsnc.cn/Article/details/gtdntsqnqn.html

JS:   class User {}
来源：http://dali.xuanzx.com/Article/details/gttclrwgbo.html

TS:   class User { name: string = ""; }
来源：http://dali.yuxming.cn/Article/details/gtbkxrdqra.html

Java: class User {}
来源：http://dali.9152youxi.cn/Article/details/gtosnmatkg.html

Go:   type User struct { Name string }
来源：http://dali.redwolf501.top/Article/details/gtydownwlp.html

Ruby: class User; end
来源：http://dali.snrcjt.cn/Article/details/gtinmzshls.html

C#:   class User {}
来源：http://dali.hammf.cn/Article/details/gtavvjplff.html

[G02] 构造函数
来源：http://dali.sysykeji.top/Article/details/gtzyzvxmxw.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.andypj.xyz/Article/details/gtwsnglfls.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.cashguo.top/Article/details/gtvfrjuejc.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhixingplan.top/Article/details/gtyorjtggo.html

TS:   constructor(public name: string) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqvkymndk.html

Java: User(String name) { this.name = name; }
来源：http://dali.haohaochexian.top/Article/details/gtogibrtnf.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.ydzc1.top/Article/details/gtwvjgsndp.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yanxiufei.cn/Article/details/gtojqfsptn.html

C#:   public User(string name) { Name = name; }
来源：http://dali.guowangkeji.top/Article/details/gttrvetzln.html

[G03] 实例属性
来源：http://dali.hywenlv.cn/Article/details/gtjuwvfwlk.html

Py:   self.name = "x"
来源：http://dali.guannengcc.top/Article/details/gtsydhykjp.html

PHP:  public string $name = "x";
来源：http://dali.0kj1m.cn/Article/details/gtiheivcnv.html

JS:   this.name = "x";
来源：http://dali.gzhubu.top/Article/details/gtltryfxcy.html

TS:   name: string = "x";
来源：http://dali.yangfankeji.com/Article/details/gtuplquosf.html

Java: private String name;
来源：http://dali.yanxiufei.cn/Article/details/gtfgwrssjg.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.svipenyu.cn/Article/details/gtswacicza.html

Ruby: @name = "x"
来源：http://dali.jqgfzy.top/Article/details/gtrfqaacub.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jinghuilouyu.cn/Article/details/gtpxrywfek.html

[G04] 定义方法
来源：http://dali.chenlongwang.top/Article/details/gtvvcjmubc.html

Py:   def greet(self): return self.name
来源：http://dali.hammf.cn/Article/details/gtfrcrgjsc.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hammf.cn/Article/details/gtolelkccj.html

JS:   greet() { return this.name; }
来源：http://dali.vqdsnc.cn/Article/details/gtpspcctip.html

TS:   greet(): string { return this.name; }
来源：http://dali.cdnleiting.top/Article/details/gtengkfrnl.html

Java: String greet() { return name; }
来源：http://dali.cheryme.top/Article/details/gtvwobqwyb.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.daxiang520.top/Article/details/gtojelcmmo.html

Ruby: def greet; @name; end
来源：http://dali.cheryme.top/Article/details/gtuqhakzak.html

C#:   public string Greet() => Name;
来源：http://dali.nanxuanxn.top/Article/details/gtoxezhbyv.html

[G05] 继承
来源：http://dali.iojbl.cn/Article/details/gtfpirngzi.html

Py:   class Admin(User): pass
来源：http://dali.havefunace.top/Article/details/gtyrzvpfvf.html

PHP:  class Admin extends User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtnrttwmbj.html

JS:   class Admin extends User {}
来源：http://dali.nanxinkj.top/Article/details/gtxtjhylfa.html

TS:   class Admin extends User {}
来源：http://dali.jyoumei.cn/Article/details/gttkctgtvc.html

Java: class Admin extends User {}
来源：http://dali.bjfxy.top/Article/details/gtxbkabmdl.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.cqqwz.cn/Article/details/gtdfxzipbg.html

Ruby: class Admin < User; end
来源：http://dali.chenjidiqi.icu/Article/details/gtphwyrolg.html

C#:   class Admin : User {}
来源：http://dali.fzhhl.top/Article/details/gtifzsmwvj.html

[G06] 重写方法
来源：http://dali.cucudq.cn/Article/details/gtxftzrdms.html

Py:   def greet(self): return "admin"
来源：http://dali.sxryk.cn/Article/details/gtogktqsyk.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yj20258888.top/Article/details/gtylbslddi.html

JS:   greet() { return "admin"; }
来源：http://dali.xziqi.cn/Article/details/gtcnmgkpgw.html

TS:   greet(): string { return "admin"; }
来源：http://dali.birdmap.top/Article/details/gtyuaezkiy.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yj202588.top/Article/details/gthqajjbkg.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jyoumei.cn/Article/details/gtskrblwhy.html

Ruby: def greet; "admin"; end
来源：http://dali.hysaishi.cn/Article/details/gtjoybaleq.html

C#:   public override string Greet() => "admin";
来源：http://dali.hfpthk.cn/Article/details/gtagvarcgq.html

[G07] 调用父类方法
来源：http://dali.zhiwuduotai.top/Article/details/gtsxujbegm.html

Py:   super().greet()
来源：http://dali.xylfe.cn/Article/details/gtuvfvbaow.html

PHP:  parent::greet();
来源：http://dali.shzxlz.cn/Article/details/gtgqmfdfoh.html

JS:   super.greet();
来源：http://dali.yuxming.cn/Article/details/gtgzvocaip.html

TS:   super.greet();
来源：http://dali.cashguo.top/Article/details/gtiwdcgbgj.html

Java: super.greet();
来源：http://dali.0kj1m.cn/Article/details/gtpfkyfsqz.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zdqjudy.top/Article/details/gtbtnkyyzh.html

Ruby: super
来源：http://dali.aibaodan.cn/Article/details/gtnmzfmvzh.html

C#:   base.Greet();
来源：http://dali.smart0.xyz/Article/details/gthzjlrqto.html

[G08] 静态方法与属性
来源：http://dali.chenzaomai.com/Article/details/gtvxblheac.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hywenlv.cn/Article/details/gtxepiyrpv.html

PHP:  public static function f() {}
来源：http://dali.gzhubu.top/Article/details/gtvqjnczqd.html

JS:   static f() {}
来源：http://dali.meibo888.top/Article/details/gtgdfvkmqr.html

TS:   static f(): void {}
来源：http://dali.xuanzx.com/Article/details/gtrnbwcuyn.html

Java: static void f() {}
来源：http://dali.cashguo.top/Article/details/gtzxidnwem.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yanxiufei.cn/Article/details/gtfyfxrbub.html

Ruby: def self.f; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmxmfsjca.html

C#:   public static void F() {}
来源：http://dali.yj202588.top/Article/details/gtqruswfeb.html

[G09] 接口 / 抽象类
来源：http://dali.wangdashe.top/Article/details/gtfdxbiajt.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.pengpengdd.cyou/Article/details/gttjutkwcu.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.ybcxt.top/Article/details/gtolloadhp.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hongshengwenyu.top/Article/details/gttjsievgc.html

TS:   interface Shape { area(): number; }
来源：http://dali.yongpay.top/Article/details/gtmiycqqkg.html

Java: interface Shape { double area(); }
来源：http://dali.havefunace.top/Article/details/gtrvkxpnjs.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yanxiufei.cn/Article/details/gtrckuhncg.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jlsjyb.cn/Article/details/gtysqfkcds.html

C#:   interface IShape { double Area(); }
来源：http://dali.gzhubu.top/Article/details/gttonjbdxb.html

[G10] 访问控制
来源：http://dali.hysaishi.cn/Article/details/gtutnljnnj.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jinghuilouyu.cn/Article/details/gtwncmytmd.html

PHP:  public / protected / private
来源：http://dali.guannengcc.top/Article/details/gtlytsjqac.html

JS:   #private 字段；其余公开
来源：http://dali.wangdashe.top/Article/details/gtxrvknxku.html

TS:   public / protected / private
来源：http://dali.shuidangran.top/Article/details/gtymakuocp.html

Java: public / protected / private / 默认包级
来源：http://dali.cdnleiting.top/Article/details/gtdbrlkigc.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.0kj1m.cn/Article/details/gtmileqnig.html

Ruby: public / protected / private
来源：http://dali.hnqzz.top/Article/details/gthezoiacx.html

C#:   public / protected / private / internal
来源：http://dali.zhiwuduotai.top/Article/details/gtbeljwvjs.html

[G11] getter / setter
来源：http://dali.zhengqikj.top/Article/details/gtneqtalwf.html

Py:   @property 与 @x.setter
来源：http://dali.ehwqpu.com/Article/details/gtzpzfkcnl.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.gogol.net.cn/Article/details/gtnzypsxay.html

JS:   get name() { return this._name; }
来源：http://dali.redwolf501.top/Article/details/gtlezmdjiq.html

TS:   get name(): string { return this._name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtlownazzq.html

Java: public String getName() { return name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtunckyzrj.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.sxryk.cn/Article/details/gtebirbpyt.html

Ruby: attr_accessor :name
来源：http://dali.kuanghao11.cn/Article/details/gtuirxpzpd.html

C#:   public string Name { get; set; }
来源：http://dali.birdmap.top/Article/details/gtgkgadfim.html

[G12] 对象转字符串
来源：http://dali.xziqi.cn/Article/details/gtjvzbxbyq.html

Py:   def __str__(self): return self.name
来源：http://dali.cqqwz.cn/Article/details/gtceukzhrh.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.guowangkeji.top/Article/details/gtbhzmisxz.html

JS:   toString() { return this.name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtqenfqhbj.html

TS:   toString(): string { return this.name; }
来源：http://dali.andypj.xyz/Article/details/gtdsdfpcls.html

Java: @Override public String toString() { return name; }
来源：http://dali.tian-w.cn/Article/details/gttvnqpcdm.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.birdmap.top/Article/details/gttqibmdqm.html

Ruby: def to_s; @name; end
来源：http://dali.cdnleiting.top/Article/details/gtodhzatbj.html

C#:   public override string ToString() => Name;
来源：http://dali.shuidangran.top/Article/details/gtayeiwmjy.html

[G13] 判断对象类型
来源：http://dali.chenjidiqi.icu/Article/details/gtlahqdjwx.html

Py:   isinstance(u, User)
来源：http://dali.ehwqpu.com/Article/details/gtjfodufur.html

PHP:  $u instanceof User
来源：http://dali.zhongyouzk.top/Article/details/gtlyvpzqte.html

JS:   u instanceof User
来源：http://dali.9152youxi.cn/Article/details/gttzzjwovf.html

TS:   u instanceof User
来源：http://dali.fengsongda.top/Article/details/gtwxftegdt.html

Java: u instanceof User
来源：http://dali.fzhhl.top/Article/details/gtmvuuyafk.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhoulong.xyz/Article/details/gtrzfkevbt.html

Ruby: u.is_a?(User)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtintenyhn.html

C#:   u is User
来源：http://dali.pengpengdd.cyou/Article/details/gthstpiovd.html

[G14] 数据类 / record
来源：http://dali.shangyingyoupin.top/Article/details/gtjkgxyudw.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.svipenyu.cn/Article/details/gtldndwwqt.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.kuanghao11.cn/Article/details/gttrkmlvdt.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.kuanghao11.cn/Article/details/gtvtgdwxio.html

TS:   type User = { name: string; age: number };
来源：http://dali.kuanghao11.cn/Article/details/gtnksbdzxq.html

Java: record User(String name, int age) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtrdjbkydt.html

Go:   type User struct { Name string; Age int }
来源：http://dali.quarkkingdee.top/Article/details/gtzkzirpui.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.dianchejie.cn/Article/details/gtwedqdfzb.html

C#:   record User(string Name, int Age);
来源：http://dali.smart0.xyz/Article/details/gttdmgdgcy.html

[G15] 枚举
来源：http://dali.tian-w.cn/Article/details/gtkpxjdnio.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gtjcmcnito.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.xinyue.icu/Article/details/gtdcduijcf.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.meibo888.top/Article/details/gtulqaexpx.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhengqikj.top/Article/details/gtgdwnvmpv.html

Java: enum Color { RED, GREEN }
来源：http://dali.yvedp.cn/Article/details/gtolordkvj.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jqgfzy.top/Article/details/gtsuvkxnai.html

Ruby: Color = %i[red green].freeze
来源：http://dali.hywenlv.cn/Article/details/gtmvdrzlyt.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.chenlongwang.top/Article/details/gtggzouzif.html

[G16] 对象转数组 / 字典
来源：http://dali.sufxvd.cn/Article/details/gtcyrdiytx.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.guannengcc.top/Article/details/gtvoejmkpd.html

PHP:  get_object_vars($obj);
来源：http://dali.shzxlz.cn/Article/details/gtwyinfkra.html

JS:   Object.entries(obj)
来源：http://dali.meibo888.top/Article/details/gtdcxfhfji.html

TS:   Object.entries(obj)
来源：http://dali.tianlin.xyz/Article/details/gtstfsrloh.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.tanke756.top/Article/details/gtfcvikyzl.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.shzxlz.cn/Article/details/gtjxgrhywp.html

Ruby: obj.instance_variables
来源：http://dali.jqgufenzy.top/Article/details/gtmftmcpvx.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.haohaochexian.top/Article/details/gtdulczxbp.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtvmwseydx.html

H. 异常与错误处理
来源：http://dali.jlsjyb.cn/Article/details/gtqbnknwac.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtfvqatjyi.html

[H01] try / catch 基础
来源：http://dali.nwbrower.top/Article/details/gtznxlbygq.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.ydzc1.top/Article/details/gtiomrmqhi.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrhwvcmln.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.meibo888.top/Article/details/gttbkogjoh.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zdqjudy.top/Article/details/gtvedboohn.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.aibaodan.cn/Article/details/gtitsybfsr.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hysaishi.cn/Article/details/gthwtfsbwo.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.snrcjt.cn/Article/details/gtpwispjnx.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.feifeiyinyue.top/Article/details/gtoqtnrolo.html

[H02] finally / ensure 收尾
来源：http://dali.bjfxy.top/Article/details/gthfxoqocc.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.gotoacloud.top/Article/details/gttkuekvbq.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.guowangkeji.top/Article/details/gtepdgcxeu.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.cdnleiting.top/Article/details/gtjrfgznnm.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jqgfzy.top/Article/details/gtdumblzeo.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.fengsongda.top/Article/details/gtokjbpwmj.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jqgfzy.top/Article/details/gtiswiyhkh.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yanxiufei.cn/Article/details/gtgymthvxb.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.redwolf501.top/Article/details/gtrnaatjqh.html

[H03] 主动抛出异常
来源：http://dali.zdqjudy.top/Article/details/gtjnkmtayt.html

Py:   raise ValueError("错误信息")
来源：http://dali.jinqigufen.top/Article/details/gtjzuvwsyj.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hysaishi.cn/Article/details/gtjmmfkeog.html

JS:   throw new Error("错误信息");
来源：http://dali.jlsjyb.cn/Article/details/gtsjeyukie.html

TS:   throw new Error("错误信息");
来源：http://dali.yj20258888.top/Article/details/gtivuaoequ.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.quarkkingdee.top/Article/details/gtrjlnjtfn.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.daria6918.cn/Article/details/gtbzyyiplm.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.shangyingyoupin.top/Article/details/gtgluxyimf.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yj202588.top/Article/details/gtpghfffde.html

[H04] 自定义异常类型
来源：http://dali.sysykeji.top/Article/details/gtogwgwano.html

Py:   class MyError(Exception): pass
来源：http://dali.guowangkeji.top/Article/details/gtlxphfqzq.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.redwolf501.top/Article/details/gtstmmxdfc.html

JS:   class MyError extends Error {}
来源：http://dali.zhoulong.xyz/Article/details/gttcubgjpf.html

TS:   class MyError extends Error {}
来源：http://dali.kuanghao11.cn/Article/details/gtmcfpjdqf.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yanxiufei.cn/Article/details/gtgllhcebi.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.hongshengwenyu.top/Article/details/gteacesurh.html

Ruby: class MyError < StandardError; end
来源：http://dali.snrcjt.cn/Article/details/gtuuchxymh.html

C#:   class MyException : Exception {}
来源：http://dali.cucudq.cn/Article/details/gtvrhexuqn.html

[H05] 捕获特定类型
来源：http://dali.yuxming.cn/Article/details/gtohhobsjm.html

Py:   except ValueError as e:
来源：http://dali.c1oappe.top/Article/details/gtamnhlkol.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jqgfzy.top/Article/details/gtwuqfmdos.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.dashuyun.cn/Article/details/gtqpjfbxdu.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhoulong.xyz/Article/details/gtgbcqkayf.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yueranfly.top/Article/details/gtcemkotyb.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.hfpthk.cn/Article/details/gtuapqisdo.html

Ruby: rescue ArgumentError => e
来源：http://dali.smart0.xyz/Article/details/gtfzxfibak.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfrnawmqq.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhixingplan.top/Article/details/gtnygbjwfl.html

Py:   value = d.get("k") or default
来源：http://dali.nanxinkj.top/Article/details/gtqxotnryo.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.nwbrower.top/Article/details/gtjsflvqhm.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yanxiufei.cn/Article/details/gtnzocupas.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zdqjudy.top/Article/details/gtjgnwbuyj.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.ydzc1.top/Article/details/gtpcfurrvi.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yanxiufei.cn/Article/details/gtezgnhkev.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hywenlv.cn/Article/details/gtxzvrytcn.html

C#:   obj?.A?.B ?? default
来源：http://dali.chenzaomai.com/Article/details/gtzmqzufrf.html

[H07] 断言
来源：http://dali.hnxiangtu.top/Article/details/gtyhxfokwv.html

Py:   assert x > 0, "必须为正"
来源：http://dali.xziqi.cn/Article/details/gtkknaowxd.html

PHP:  assert($x > 0);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzfbzftoa.html

JS:   console.assert(x > 0);
来源：http://dali.hysaishi.cn/Article/details/gtfsnlwfgl.html

TS:   console.assert(x > 0);
来源：http://dali.jianghu66.top/Article/details/gtidkwfbni.html

Java: assert x > 0 : "必须为正";
来源：http://dali.mhx1999.top/Article/details/gtxjbghyym.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.tianlin.xyz/Article/details/gtdehxtymp.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmnzfllmg.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yj202588.top/Article/details/gtyxowuljl.html

[H08] 获取错误信息与堆栈
来源：http://dali.cqqwz.cn/Article/details/gtnmezqomb.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yuxming.cn/Article/details/gtosinzbwg.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jianghu66.top/Article/details/gtijovhnsp.html

JS:   e.message;  e.stack
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteagwkgku.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.gzhubu.top/Article/details/gtgpyurkay.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.dianchejie.cn/Article/details/gtugwegore.html

Go:   err.Error()
来源：http://dali.tian-w.cn/Article/details/gtwazobgug.html

Ruby: e.message;  e.backtrace
来源：http://dali.tian-w.cn/Article/details/gtmdxfkrii.html

C#:   e.Message;  e.StackTrace
来源：http://dali.ehwqpu.com/Article/details/gtcibjhozs.html

[H09] 带错误码的异常
来源：http://dali.hywenlv.cn/Article/details/gtkzbxneuy.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.snrcjt.cn/Article/details/gtneaqwutm.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.guannengcc.top/Article/details/gtqscdzjzk.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.hysaishi.cn/Article/details/gtkxrfxcok.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gtmisjekqu.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yuxming.cn/Article/details/gtarkjdcuw.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhoulong.xyz/Article/details/gtiritzqnf.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.wangdashe.top/Article/details/gthvaljgic.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.xylfe.cn/Article/details/gtkxgbemwd.html

[H10] 资源自动释放
来源：http://dali.jinqigufen.top/Article/details/gtvkbeldno.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhixingplan.top/Article/details/gtqyxdoyyn.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jiagoushi.top/Article/details/gtqvvovkaf.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yonumen.top/Article/details/gtctezqyhy.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sweek.top/Article/details/gtshwhusne.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.zhoulong.xyz/Article/details/gtsjpcmtci.html

Go:   defer f.Close()
来源：http://dali.birdmap.top/Article/details/gtxvnbsnfx.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.havefunace.top/Article/details/gtimtohhvo.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ivvv.top/Article/details/gtmawxjkrx.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtxymbajex.html

I. 正则表达式
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfeakeaml.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtkgiwmhol.html

[I01] 判断是否匹配
来源：http://dali.gotoacloud.top/Article/details/gtfoozlyhw.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhongyouzk.top/Article/details/gtytmkemhy.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.nanxinkj.top/Article/details/gtbeonrufr.html

JS:   /\d+/.test(s)
来源：http://dali.ybcxt.top/Article/details/gtcsdcpgeu.html

TS:   /\d+/.test(s)
来源：http://dali.chenzaomai.com/Article/details/gtypgsrvpl.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.shanyushiyangtech.top/Article/details/gthdkksuyp.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.zhixingplan.top/Article/details/gtppfsjjla.html

Ruby: s.match?(/\d+/)
来源：http://dali.yvedp.cn/Article/details/gtkxbkmxlk.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.hysaishi.cn/Article/details/gtcsfhxfdc.html

[I02] 提取所有匹配
来源：http://dali.gogol.net.cn/Article/details/gtrnwkcauj.html

Py:   re.findall(r"\d+", s)
来源：http://dali.xylfe.cn/Article/details/gtisiomcpm.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.fzhhl.top/Article/details/gtjzoikfrw.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.svipenyu.cn/Article/details/gterffknhj.html

TS:   s.match(/\d+/g)
来源：http://dali.bjfxy.top/Article/details/gtlmxuejji.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.xylfe.cn/Article/details/gtdvzknvwa.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.havefunace.top/Article/details/gtlvhguozc.html

Ruby: s.scan(/\d+/)
来源：http://dali.aibaodan.cn/Article/details/gtlyngfsaq.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjnduekha.html

[I03] 提取捕获分组
来源：http://dali.wangshuangyany.cn/Article/details/gtkxzfcgsw.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.gaohongyu789.top/Article/details/gtkcosyrmo.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.ivvv.top/Article/details/gtmlviycrv.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.ybcxt.top/Article/details/gtgogqxzek.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.cashguo.top/Article/details/gthyhzkfmh.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhoulong.xyz/Article/details/gtbhrxhetx.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.ybcxt.top/Article/details/gtjzqmbzgc.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.chenlongwang.top/Article/details/gtjdcrblne.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.chenjidiqi.icu/Article/details/gtuomvzggx.html

[I04] 正则替换
来源：http://dali.feifeiyinyue.top/Article/details/gtqczcnisz.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.ppjwa.cn/Article/details/gtwdnxrbqk.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.haohaochexian.top/Article/details/gtuatpzooi.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.mhx1999.top/Article/details/gtopdlatjg.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.hywenlv.cn/Article/details/gtdzaffopq.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.9152youxi.cn/Article/details/gtzdiwwlgp.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jinqigfzy.top/Article/details/gtcsjckmug.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jinqigfzy.top/Article/details/gtarqdfrvw.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.hfpthk.cn/Article/details/gtljxrargq.html

[I05] 按正则拆分
来源：http://dali.cqqwz.cn/Article/details/gtvhjrahbe.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.ydzc1.top/Article/details/gtjozrgyxg.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.jyoumei.cn/Article/details/gtsoajjvlz.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.hongshengwenyu.top/Article/details/gtiksiupka.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.hongshengwenyu.top/Article/details/gtsftccwsv.html


<!-- 参考信息 -->