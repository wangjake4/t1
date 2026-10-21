代发 wailian999

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtkxjscrgz.html

TS:   path.extname("a.txt")
来源：http://dali.sweek.top/Article/details/gtrrhtlnee.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.chenlongwang.top/Article/details/gtbsncewax.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtwiuaqhcf.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hnqzz.top/Article/details/gtusvgkjaq.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yj202588.top/Article/details/gtpmdvjkxf.html

[F11] 复制与移动文件
来源：http://dali.yj202588.top/Article/details/gtstvkapqe.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.shzxlz.cn/Article/details/gtmnfmmkcx.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhoulong.xyz/Article/details/gthjotfapc.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jianghu66.top/Article/details/gtwxkuzrwt.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.snrcjt.cn/Article/details/gtsfgdbzsk.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.haohaochexian.top/Article/details/gtafcfvvet.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.c1oappe.top/Article/details/gtiuglavfz.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.c1oappe.top/Article/details/gttyucjeck.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jqgufenzy.top/Article/details/gtnwxwlseh.html

[F12] CSV 读写
来源：http://dali.ivvv.top/Article/details/gtzgaozqek.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.cucudq.cn/Article/details/gthmlhqsqd.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.andypj.xyz/Article/details/gtjemsctqa.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.sweek.top/Article/details/gtglkfpubz.html

TS:   // 同上
来源：http://dali.fzhhl.top/Article/details/gtudlfnjkt.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.smart0.xyz/Article/details/gtvpfgbenx.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhaomingkeji.xyz/Article/details/gtohxajkav.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.nanxuanxn.top/Article/details/gththgawyk.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.sxryk.cn/Article/details/gtfhnxxlnk.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtegqlidac.html

G. 面向对象
来源：http://dali.cdnleiting.top/Article/details/gtcwstbhad.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gttlyxjywt.html

[G01] 定义类
来源：http://dali.zhixingplan.top/Article/details/gtrgsgqqah.html

Py:   class User: pass
来源：http://dali.hfpthk.cn/Article/details/gtbaygwuve.html

PHP:  class User {}
来源：http://dali.jqgufenzy.top/Article/details/gtyueyktlb.html

JS:   class User {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gttaqdaoqj.html

TS:   class User { name: string = ""; }
来源：http://dali.cucudq.cn/Article/details/gttgoleypv.html

Java: class User {}
来源：http://dali.zdqjudy.top/Article/details/gtnsjnmwcn.html

Go:   type User struct { Name string }
来源：http://dali.pycfn.com/Article/details/gtnxownhjn.html

Ruby: class User; end
来源：http://dali.kuanghao11.cn/Article/details/gtlhotvtrj.html

C#:   class User {}
来源：http://dali.vqdsnc.cn/Article/details/gtnbvseudq.html

[G02] 构造函数
来源：http://dali.ivvv.top/Article/details/gtebtlmcyh.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhixingplan.top/Article/details/gtmkmxagfm.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.dashuyun.cn/Article/details/gtfljaqmkc.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhongyouzk.top/Article/details/gterweeoel.html

TS:   constructor(public name: string) {}
来源：http://dali.mhx1999.top/Article/details/gtaljlzevl.html

Java: User(String name) { this.name = name; }
来源：http://dali.xylfe.cn/Article/details/gthrrjlwkc.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.wangshuangyany.cn/Article/details/gtdynrdilt.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.haohaochexian.top/Article/details/gtlhbwhsvq.html

C#:   public User(string name) { Name = name; }
来源：http://dali.guannengcc.top/Article/details/gtefzyusxx.html

[G03] 实例属性
来源：http://dali.dianchejie.cn/Article/details/gtuveektus.html

Py:   self.name = "x"
来源：http://dali.ydzc1.top/Article/details/gtlyhidpdk.html

PHP:  public string $name = "x";
来源：http://dali.zhongyouzk.top/Article/details/gtpjtqdmzo.html

JS:   this.name = "x";
来源：http://dali.iojbl.cn/Article/details/gtlgipdqxz.html

TS:   name: string = "x";
来源：http://dali.gzhubu.top/Article/details/gtebvvurov.html

Java: private String name;
来源：http://dali.shangyingyoupin.top/Article/details/gtcvcyufkl.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.dianchejie.cn/Article/details/gtpepdvdbe.html

Ruby: @name = "x"
来源：http://dali.fzhhl.top/Article/details/gtxbkazwmy.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yanxiufei.cn/Article/details/gteovhkcze.html

[G04] 定义方法
来源：http://dali.daria6918.cn/Article/details/gtzzzewjmk.html

Py:   def greet(self): return self.name
来源：http://dali.cdnleiting.top/Article/details/gtntzbhfvk.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.ehwqpu.com/Article/details/gtmxdvupgz.html

JS:   greet() { return this.name; }
来源：http://dali.chenzaomai.com/Article/details/gtfozjjlfp.html

TS:   greet(): string { return this.name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtdjzbsahg.html

Java: String greet() { return name; }
来源：http://dali.yj20258.top/Article/details/gttilllxqz.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.aibaodan.cn/Article/details/gtxsyroepr.html

Ruby: def greet; @name; end
来源：http://dali.hongshengwenyu.top/Article/details/gtfzbzguih.html

C#:   public string Greet() => Name;
来源：http://dali.ybcxt.top/Article/details/gtuaxysnut.html

[G05] 继承
来源：http://dali.yj20258888.top/Article/details/gtcwpyuytj.html

Py:   class Admin(User): pass
来源：http://dali.nwbrower.top/Article/details/gtkdtowqzu.html

PHP:  class Admin extends User {}
来源：http://dali.ybcxt.top/Article/details/gtmfojapwc.html

JS:   class Admin extends User {}
来源：http://dali.hnqzz.top/Article/details/gtweabhpmh.html

TS:   class Admin extends User {}
来源：http://dali.c1oappe.top/Article/details/gtcmvuezhl.html

Java: class Admin extends User {}
来源：http://dali.xziqi.cn/Article/details/gtrdkhysll.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.xylfe.cn/Article/details/gtgznkuenw.html

Ruby: class Admin < User; end
来源：http://dali.sxryk.cn/Article/details/gtwmopngrd.html

C#:   class Admin : User {}
来源：http://dali.dashuyun.cn/Article/details/gtrgrwqasg.html

[G06] 重写方法
来源：http://dali.yongpay.top/Article/details/gtjosiogzn.html

Py:   def greet(self): return "admin"
来源：http://dali.9152youxi.cn/Article/details/gtwsjvlpxt.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.redwolf501.top/Article/details/gtejygoexd.html

JS:   greet() { return "admin"; }
来源：http://dali.guannengcc.top/Article/details/gtaqixpifq.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yanxiufei.cn/Article/details/gtzbobrvqv.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.tianlin.xyz/Article/details/gttmkawrdw.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.cdnleiting.top/Article/details/gtyodwjrpr.html

Ruby: def greet; "admin"; end
来源：http://dali.xziqi.cn/Article/details/gtdcmndsuc.html

C#:   public override string Greet() => "admin";
来源：http://dali.aibaodan.cn/Article/details/gttmbeepjq.html

[G07] 调用父类方法
来源：http://dali.cheryme.top/Article/details/gtglebhwjt.html

Py:   super().greet()
来源：http://dali.haohaochexian.top/Article/details/gtvyvpujke.html

PHP:  parent::greet();
来源：http://dali.feifeiyinyue.top/Article/details/gtjdiijuoa.html

JS:   super.greet();
来源：http://dali.yonumen.top/Article/details/gtfrukgjcz.html

TS:   super.greet();
来源：http://dali.smart0.xyz/Article/details/gtvpewppky.html

Java: super.greet();
来源：http://dali.daxiang520.top/Article/details/gtwvhajnqx.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.cqqwz.cn/Article/details/gtrkzttksd.html

Ruby: super
来源：http://dali.hongshengwenyu.top/Article/details/gtuslzwknu.html

C#:   base.Greet();
来源：http://dali.yueranfly.top/Article/details/gtvxbvpxwh.html

[G08] 静态方法与属性
来源：http://dali.guowangkeji.top/Article/details/gtntwziqdv.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.cucudq.cn/Article/details/gttgaacijj.html

PHP:  public static function f() {}
来源：http://dali.jqgufenzy.top/Article/details/gtjrgvzzud.html

JS:   static f() {}
来源：http://dali.yj20258.top/Article/details/gtdjgppcfq.html

TS:   static f(): void {}
来源：http://dali.hnxiangtu.top/Article/details/gtzzfvrsir.html

Java: static void f() {}
来源：http://dali.vqdsnc.cn/Article/details/gtbtrugqjp.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.smart0.xyz/Article/details/gtlrrrccoh.html

Ruby: def self.f; end
来源：http://dali.fzhhl.top/Article/details/gtnfabygqh.html

C#:   public static void F() {}
来源：http://dali.daxiang520.top/Article/details/gtehrfmkba.html

[G09] 接口 / 抽象类
来源：http://dali.tian-w.cn/Article/details/gtnamwptoi.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.dashuyun.cn/Article/details/gtfwyfksev.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.svipenyu.cn/Article/details/gtbztuqbns.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yueranfly.top/Article/details/gtzssdbmxb.html

TS:   interface Shape { area(): number; }
来源：http://dali.svipenyu.cn/Article/details/gtiqyeuibw.html

Java: interface Shape { double area(); }
来源：http://dali.zhongyouzk.top/Article/details/gtzbbhjgzy.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.snrcjt.cn/Article/details/gtbsiucapk.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yongpay.top/Article/details/gtbhedeetz.html

C#:   interface IShape { double Area(); }
来源：http://dali.yanxiufei.cn/Article/details/gtmzmambzg.html

[G10] 访问控制
来源：http://dali.ehwqpu.com/Article/details/gtcvgzvwiq.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.316326.xyz/Article/details/gtskbrtpzo.html

PHP:  public / protected / private
来源：http://dali.hnxiangtu.top/Article/details/gtjdlowgmt.html

JS:   #private 字段；其余公开
来源：http://dali.tanke756.top/Article/details/gtfymplydh.html

TS:   public / protected / private
来源：http://dali.xuetiantiany.cn/Article/details/gtkcbtkyuy.html

Java: public / protected / private / 默认包级
来源：http://dali.shanyushiyangtech.top/Article/details/gtfavkulck.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.cucudq.cn/Article/details/gtvuztlobk.html

Ruby: public / protected / private
来源：http://dali.ppjwa.cn/Article/details/gtwirdhyxf.html

C#:   public / protected / private / internal
来源：http://dali.sufxvd.cn/Article/details/gtilcsndla.html

[G11] getter / setter
来源：http://dali.xinyue.icu/Article/details/gtsfvgvxmb.html

Py:   @property 与 @x.setter
来源：http://dali.shanyushiyangtech.top/Article/details/gtftmapbml.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.nwbrower.top/Article/details/gtnctyfyfa.html

JS:   get name() { return this._name; }
来源：http://dali.yj20258.top/Article/details/gtgaivwsqp.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtutiikyqb.html

Java: public String getName() { return name; }
来源：http://dali.hysaishi.cn/Article/details/gtsihntptj.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.fengsongda.top/Article/details/gtszxrdkim.html

Ruby: attr_accessor :name
来源：http://dali.nwbrower.top/Article/details/gtoqowbror.html

C#:   public string Name { get; set; }
来源：http://dali.zdqjudy.top/Article/details/gtjzdpaemj.html

[G12] 对象转字符串
来源：http://dali.zhengqikj.top/Article/details/gtaxyybjkv.html

Py:   def __str__(self): return self.name
来源：http://dali.yongpay.top/Article/details/gtkfogqjhf.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.316326.xyz/Article/details/gtpdfojljg.html

JS:   toString() { return this.name; }
来源：http://dali.zhoulong.xyz/Article/details/gtopulgfqr.html

TS:   toString(): string { return this.name; }
来源：http://dali.havefunace.top/Article/details/gtcsdqgtrx.html

Java: @Override public String toString() { return name; }
来源：http://dali.gzhubu.top/Article/details/gtauugaktw.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.fengsongda.top/Article/details/gtehuvqtra.html

Ruby: def to_s; @name; end
来源：http://dali.ybcxt.top/Article/details/gtiluadyla.html

C#:   public override string ToString() => Name;
来源：http://dali.meibo888.top/Article/details/gthnyutknm.html

[G13] 判断对象类型
来源：http://dali.fengsongda.top/Article/details/gtjqbdnktp.html

Py:   isinstance(u, User)
来源：http://dali.bjfxy.top/Article/details/gtjzrcdpwt.html

PHP:  $u instanceof User
来源：http://dali.jlsjyb.cn/Article/details/gtlcegjxwm.html

JS:   u instanceof User
来源：http://dali.feifeiyinyue.top/Article/details/gtgtsaxbns.html

TS:   u instanceof User
来源：http://dali.9152youxi.cn/Article/details/gtjtfpybni.html

Java: u instanceof User
来源：http://dali.shanyushiyangkeji.top/Article/details/gthtxczkkd.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zycfv.cn/Article/details/gtcqbmtuqu.html

Ruby: u.is_a?(User)
来源：http://dali.zhongyouzk.top/Article/details/gtmznmvque.html

C#:   u is User
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnjyjhvap.html

[G14] 数据类 / record
来源：http://dali.yangfankeji.com/Article/details/gtviohdkgv.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jyoumei.cn/Article/details/gteoyvrnxz.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.aibaodan.cn/Article/details/gtmgjodfea.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.sweek.top/Article/details/gtbnrmvsfj.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhoulong.xyz/Article/details/gtmgrnzkkb.html

Java: record User(String name, int age) {}
来源：http://dali.316326.xyz/Article/details/gtlpvjstyv.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yueranfly.top/Article/details/gtdunfbnwm.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.cqqwz.cn/Article/details/gtodyvsfzc.html

C#:   record User(string Name, int Age);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmqnelmsy.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gtmvkcbnus.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.cucudq.cn/Article/details/gttlzwdtas.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.chenzaomai.com/Article/details/gtrhalysya.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.shangyingyoupin.top/Article/details/gtbwnklzhw.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gotoacloud.top/Article/details/gtnhzayyhw.html

Java: enum Color { RED, GREEN }
来源：http://dali.jqgfzy.top/Article/details/gtspilgtqe.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.tanke756.top/Article/details/gtpohswsua.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jqgfzy.top/Article/details/gtoqhpeqdp.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jqgfzy.top/Article/details/gtcfesdnsg.html

[G16] 对象转数组 / 字典
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcxpgmadv.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.smart0.xyz/Article/details/gtonzcyybb.html

PHP:  get_object_vars($obj);
来源：http://dali.nanxinkj.top/Article/details/gtbwlcjabl.html

JS:   Object.entries(obj)
来源：http://dali.hysaishi.cn/Article/details/gtnmchgwcd.html

TS:   Object.entries(obj)
来源：http://dali.aizwys.cn/Article/details/gtfiwbderi.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hongshengwenyu.top/Article/details/gtwmldnqmv.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.meibo888.top/Article/details/gtrekemqsa.html

Ruby: obj.instance_variables
来源：http://dali.birdmap.top/Article/details/gtgzdehpze.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.fzhhl.top/Article/details/gthaumlmum.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtearkpcsm.html

H. 异常与错误处理
来源：http://dali.aizwys.cn/Article/details/gtwszsgxrs.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtsvheenyb.html

[H01] try / catch 基础
来源：http://dali.smart0.xyz/Article/details/gtcbmqvnhz.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.sweek.top/Article/details/gtxygpwgtk.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.tian-w.cn/Article/details/gtgndolpna.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhiwuduotai.top/Article/details/gtncdzztge.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.smart0.xyz/Article/details/gtqyaodmdm.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.xuetiantiany.cn/Article/details/gtgojihlrz.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.bjfxy.top/Article/details/gtnxyykpmz.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zycfv.cn/Article/details/gtmxnwgeew.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.sweek.top/Article/details/gtfvebmjlt.html

[H02] finally / ensure 收尾
来源：http://dali.jiagoushi.top/Article/details/gtffwxdxmb.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.wangshuangyany.cn/Article/details/gtgctuqpdd.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.gotoacloud.top/Article/details/gttswpkzen.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtzsbdtobo.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yj20258888.top/Article/details/gtpkxbzwdn.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.quarkkingdee.top/Article/details/gtnowaunkf.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.smart0.xyz/Article/details/gtdqzdrxua.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmurxfasp.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.gogol.net.cn/Article/details/gtflclvjki.html

[H03] 主动抛出异常
来源：http://dali.gaohongyu789.top/Article/details/gtrqofkhom.html

Py:   raise ValueError("错误信息")
来源：http://dali.wangdashe.top/Article/details/gtmrhflfqb.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yuxming.cn/Article/details/gtkgzpqkcz.html

JS:   throw new Error("错误信息");
来源：http://dali.cqqwz.cn/Article/details/gtjqlludsm.html

TS:   throw new Error("错误信息");
来源：http://dali.hnxiangtu.top/Article/details/gtystcuhea.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.dashuyun.cn/Article/details/gtxsrpxfdq.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jinghuilouyu.cn/Article/details/gtkvwbyboy.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.smart0.xyz/Article/details/gtnrunxjld.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.c1oappe.top/Article/details/gtunhdppcf.html

[H04] 自定义异常类型
来源：http://dali.gogol.net.cn/Article/details/gtzriysjxl.html

Py:   class MyError(Exception): pass
来源：http://dali.xuanzx.com/Article/details/gtfagqdetw.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gtfuqyznug.html

JS:   class MyError extends Error {}
来源：http://dali.316326.xyz/Article/details/gtzdozhuwi.html

TS:   class MyError extends Error {}
来源：http://dali.xuetiantiany.cn/Article/details/gtirzdwbyq.html

Java: class MyException extends RuntimeException {}
来源：http://dali.fzhhl.top/Article/details/gtdsmjwviv.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.c1oappe.top/Article/details/gtridsgjhn.html

Ruby: class MyError < StandardError; end
来源：http://dali.cashguo.top/Article/details/gtcmvnscjr.html

C#:   class MyException : Exception {}
来源：http://dali.cheryme.top/Article/details/gtbbzmnoqz.html

[H05] 捕获特定类型
来源：http://dali.xuanzx.com/Article/details/gtswceeeap.html

Py:   except ValueError as e:
来源：http://dali.gzhubu.top/Article/details/gtqvevycif.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.vqdsnc.cn/Article/details/gticddbpmu.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yanxiufei.cn/Article/details/gtnxappika.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yuxming.cn/Article/details/gtllycusrf.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yj20258888.top/Article/details/gtksrcewva.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.sufxvd.cn/Article/details/gtexluycxg.html

Ruby: rescue ArgumentError => e
来源：http://dali.cheryme.top/Article/details/gtdlkgunwy.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.quarkkingdee.top/Article/details/gtbkvdvljl.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zycfv.cn/Article/details/gtrxbxbdgu.html

Py:   value = d.get("k") or default
来源：http://dali.zhongyouzk.top/Article/details/gtsmicowcx.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.c1oappe.top/Article/details/gtnsquiqux.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jqgufenzy.top/Article/details/gtyfslahkt.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jqgfzy.top/Article/details/gtiqtwvjof.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmjnozsig.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.cashguo.top/Article/details/gtedyjqvzs.html

Ruby: d&.dig(:a, :b)
来源：http://dali.bjfxy.top/Article/details/gtkcqnboyo.html

C#:   obj?.A?.B ?? default
来源：http://dali.ehwqpu.com/Article/details/gtaeebvcph.html

[H07] 断言
来源：http://dali.dianchejie.cn/Article/details/gtezvkyisp.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yj202588.top/Article/details/gtipbpgvyz.html

PHP:  assert($x > 0);
来源：http://dali.shzxlz.cn/Article/details/gtcfblynpi.html

JS:   console.assert(x > 0);
来源：http://dali.ehwqpu.com/Article/details/gtwzpnyled.html

TS:   console.assert(x > 0);
来源：http://dali.iojbl.cn/Article/details/gtclehgaui.html

Java: assert x > 0 : "必须为正";
来源：http://dali.ybcxt.top/Article/details/gtnihmkdul.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jlsjyb.cn/Article/details/gtsuxnjzvd.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.daxiang520.top/Article/details/gtcippigzu.html

C#:   Debug.Assert(x > 0);
来源：http://dali.316326.xyz/Article/details/gtnuwkbkls.html

[H08] 获取错误信息与堆栈
来源：http://dali.0kj1m.cn/Article/details/gtjuxjdgdd.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.xinyue.icu/Article/details/gtsixertme.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhoulong.xyz/Article/details/gtymqzpelg.html

JS:   e.message;  e.stack
来源：http://dali.cqqwz.cn/Article/details/gtvdnjeazl.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.nwbrower.top/Article/details/gtxbvvvfir.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.bjfxy.top/Article/details/gtsguwxzge.html

Go:   err.Error()
来源：http://dali.jinqigufen.top/Article/details/gtkkadxoyg.html

Ruby: e.message;  e.backtrace
来源：http://dali.yj202588.top/Article/details/gtdthnhwfy.html

C#:   e.Message;  e.StackTrace
来源：http://dali.wangdashe.top/Article/details/gtbaihcogo.html

[H09] 带错误码的异常
来源：http://dali.zhengqikj.top/Article/details/gthrpacgmv.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yanxiufei.cn/Article/details/gtgxcuzqmj.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yj20258888.top/Article/details/gtniexdkrp.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yvedp.cn/Article/details/gtmeijlsof.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.havefunace.top/Article/details/gtvtmlrrjr.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.shuidangran.top/Article/details/gtbtlduoaa.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmbcffmyz.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.sufxvd.cn/Article/details/gtbecipmlg.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.gzhubu.top/Article/details/gtdrnrnhpv.html

[H10] 资源自动释放
来源：http://dali.yj202588.top/Article/details/gtmtbqlqqh.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.sufxvd.cn/Article/details/gtgqzvnzyw.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.smart0.xyz/Article/details/gtdpdiryfr.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.nanxinkj.top/Article/details/gtpoumlofv.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.havefunace.top/Article/details/gttbdzojvb.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.quarkkingdee.top/Article/details/gtigsbogiq.html

Go:   defer f.Close()
来源：http://dali.xuetiantiany.cn/Article/details/gtbfuxhrfd.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.xuanzx.com/Article/details/gtaslvchbc.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.gotoacloud.top/Article/details/gtdoxfztfh.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtgpjslxki.html

I. 正则表达式
来源：http://dali.shangyingyoupin.top/Article/details/gtwwusasgj.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gttniebxtr.html

[I01] 判断是否匹配
来源：http://dali.tanke756.top/Article/details/gtntvkngob.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.chenlongwang.top/Article/details/gtiwybgsik.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.nanxuanxn.top/Article/details/gtefiuwynv.html

JS:   /\d+/.test(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtrvpkgtmr.html

TS:   /\d+/.test(s)
来源：http://dali.smart0.xyz/Article/details/gtomvhswhn.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yj20258.top/Article/details/gtwkxrhqmh.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.sufxvd.cn/Article/details/gtqdlnvhyk.html

Ruby: s.match?(/\d+/)
来源：http://dali.xinyue.icu/Article/details/gtdnbokgui.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.hongshengwenyu.top/Article/details/gtcrttgvcp.html

[I02] 提取所有匹配
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiaezojjq.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhongyouzk.top/Article/details/gtobntkdeq.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.meibo888.top/Article/details/gtrmngdvai.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.vqdsnc.cn/Article/details/gtlgjbodya.html

TS:   s.match(/\d+/g)
来源：http://dali.316326.xyz/Article/details/gtbballmbt.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.snrcjt.cn/Article/details/gtjkxmpvwa.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.shanyushiyangtech.top/Article/details/gttedrpfio.html

Ruby: s.scan(/\d+/)
来源：http://dali.0kj1m.cn/Article/details/gtgozjaitt.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.andypj.xyz/Article/details/gtsqjueoyr.html

[I03] 提取捕获分组
来源：http://dali.shanyushiyangtech.top/Article/details/gttxocozmf.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhongyouzk.top/Article/details/gtrqiyqcjy.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.c1oappe.top/Article/details/gttumnisda.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhixingplan.top/Article/details/gtrlevbmuy.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.cashguo.top/Article/details/gtodejppia.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.9152youxi.cn/Article/details/gtyufwtxib.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.xuanzx.com/Article/details/gtzlxvszam.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.nwbrower.top/Article/details/gtoiqtycya.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.nwbrower.top/Article/details/gtuoheayzw.html

[I04] 正则替换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsojtpjfv.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.jinqigfzy.top/Article/details/gtotrmibdb.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtgoyjruwn.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.guowangkeji.top/Article/details/gthqhyjfoj.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.chenjidiqi.icu/Article/details/gteznkgmey.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.gogol.net.cn/Article/details/gtnjnnyxzq.html


<!-- 参考信息 -->