代发 wailian999

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.gotoacloud.top/Article/details/gthqdkstli.html

TS:   path.extname("a.txt")
来源：http://dali.yongpay.top/Article/details/gtlyxafiqi.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yvedp.cn/Article/details/gtvyfesldo.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtfxdlvsee.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yj20258.top/Article/details/gtqunlfrdd.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.316326.xyz/Article/details/gtxvylzxay.html

[F11] 复制与移动文件
来源：http://dali.xuetiantiany.cn/Article/details/gttzlashmu.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtitlrvzvn.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yj202588.top/Article/details/gtjxbhyfio.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.chenzaomai.com/Article/details/gtozcykcit.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.316326.xyz/Article/details/gtzzmvvdhf.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.cdnleiting.top/Article/details/gtxpxykbza.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yj202588.top/Article/details/gtmpxkmvzf.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.ivvv.top/Article/details/gtscblyulr.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.shanyushiyangtech.top/Article/details/gtlcfzifya.html

[F12] CSV 读写
来源：http://dali.jqgufenzy.top/Article/details/gtezealkjm.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.shzxlz.cn/Article/details/gtszdugaiv.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.dianchejie.cn/Article/details/gtuxrriaop.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.vqdsnc.cn/Article/details/gtqkmrmnsv.html

TS:   // 同上
来源：http://dali.zycfv.cn/Article/details/gtupcldwls.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.cashguo.top/Article/details/gtbwvyaxpc.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.nwbrower.top/Article/details/gtfjqtpshh.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.wangshuangyany.cn/Article/details/gtgfqkonrh.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yuxming.cn/Article/details/gtahirerki.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtcgvkqxfc.html

G. 面向对象
来源：http://dali.dianchejie.cn/Article/details/gtixwagdrl.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gthkalicpa.html

[G01] 定义类
来源：http://dali.shangyingyoupin.top/Article/details/gthhzailoq.html

Py:   class User: pass
来源：http://dali.zhiwuduotai.top/Article/details/gtirohlqrs.html

PHP:  class User {}
来源：http://dali.jinqigfzy.top/Article/details/gtqkpbewtv.html

JS:   class User {}
来源：http://dali.zhoulong.xyz/Article/details/gtmkjhhjrf.html

TS:   class User { name: string = ""; }
来源：http://dali.tianlin.xyz/Article/details/gtqztwwvel.html

Java: class User {}
来源：http://dali.haohaochexian.top/Article/details/gtoowiepwg.html

Go:   type User struct { Name string }
来源：http://dali.tanke756.top/Article/details/gtgjrdmgpo.html

Ruby: class User; end
来源：http://dali.bjfxy.top/Article/details/gtsmahomsc.html

C#:   class User {}
来源：http://dali.iojbl.cn/Article/details/gtbzenysqs.html

[G02] 构造函数
来源：http://dali.c1oappe.top/Article/details/gtpgimmdhe.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zdqjudy.top/Article/details/gtokribazf.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.sufxvd.cn/Article/details/gtfiahxwyr.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtnekurlwk.html

TS:   constructor(public name: string) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtakymgdfr.html

Java: User(String name) { this.name = name; }
来源：http://dali.dianchejie.cn/Article/details/gtfospgqcn.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtybounzpk.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.mhx1999.top/Article/details/gtjwynszmc.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhengqikj.top/Article/details/gtksqwgtsp.html

[G03] 实例属性
来源：http://dali.aibaodan.cn/Article/details/gtygemmzru.html

Py:   self.name = "x"
来源：http://dali.yj20258.top/Article/details/gtoqlmvisi.html

PHP:  public string $name = "x";
来源：http://dali.cheryme.top/Article/details/gtaflisgka.html

JS:   this.name = "x";
来源：http://dali.havefunace.top/Article/details/gtwjsmojmb.html

TS:   name: string = "x";
来源：http://dali.shzxlz.cn/Article/details/gtpatwjvab.html

Java: private String name;
来源：http://dali.ybcxt.top/Article/details/gtpnfauels.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hywenlv.cn/Article/details/gtzalxbmqq.html

Ruby: @name = "x"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtimoybizw.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.cdnleiting.top/Article/details/gtenbuycnn.html

[G04] 定义方法
来源：http://dali.9152youxi.cn/Article/details/gtfjwhfamj.html

Py:   def greet(self): return self.name
来源：http://dali.xinyue.icu/Article/details/gtamxplzhh.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.xziqi.cn/Article/details/gtqnovkyje.html

JS:   greet() { return this.name; }
来源：http://dali.sysykeji.top/Article/details/gtcidezjmq.html

TS:   greet(): string { return this.name; }
来源：http://dali.xuanzx.com/Article/details/gtarfwvrri.html

Java: String greet() { return name; }
来源：http://dali.quarkkingdee.top/Article/details/gtjbnsfhkz.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhoulong.xyz/Article/details/gtywuifzhg.html

Ruby: def greet; @name; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcgtkadkb.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gtnrtvzhqi.html

[G05] 继承
来源：http://dali.aibaodan.cn/Article/details/gtfbvxllfq.html

Py:   class Admin(User): pass
来源：http://dali.yj20258888.top/Article/details/gtwpgvuvvh.html

PHP:  class Admin extends User {}
来源：http://dali.hfpthk.cn/Article/details/gtmcemtytk.html

JS:   class Admin extends User {}
来源：http://dali.cashguo.top/Article/details/gtaopbxdor.html

TS:   class Admin extends User {}
来源：http://dali.gzhubu.top/Article/details/gthimufmcv.html

Java: class Admin extends User {}
来源：http://dali.gogol.net.cn/Article/details/gtnhoypvta.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjjkmyoky.html

Ruby: class Admin < User; end
来源：http://dali.zhongyouzk.top/Article/details/gthvkuwjcy.html

C#:   class Admin : User {}
来源：http://dali.sweek.top/Article/details/gtabjbubox.html

[G06] 重写方法
来源：http://dali.aizwys.cn/Article/details/gtguddpwsd.html

Py:   def greet(self): return "admin"
来源：http://dali.yj202588.top/Article/details/gtmlnpvmlk.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hysaishi.cn/Article/details/gtajtvsjrw.html

JS:   greet() { return "admin"; }
来源：http://dali.yonumen.top/Article/details/gtyqjyaunj.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jinqigufen.top/Article/details/gtkswfrwqn.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yuxming.cn/Article/details/gthqcigugz.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zycfv.cn/Article/details/gtwwftuovp.html

Ruby: def greet; "admin"; end
来源：http://dali.yonumen.top/Article/details/gtltpmumss.html

C#:   public override string Greet() => "admin";
来源：http://dali.shzxlz.cn/Article/details/gtozlbfpby.html

[G07] 调用父类方法
来源：http://dali.xziqi.cn/Article/details/gtzlatlbkd.html

Py:   super().greet()
来源：http://dali.chenzaomai.com/Article/details/gtfankyhgn.html

PHP:  parent::greet();
来源：http://dali.yongpay.top/Article/details/gtosnsmkgp.html

JS:   super.greet();
来源：http://dali.jianghu66.top/Article/details/gtwfnatiot.html

TS:   super.greet();
来源：http://dali.yj202588.top/Article/details/gtvswhsinu.html

Java: super.greet();
来源：http://dali.gogol.net.cn/Article/details/gtcrljxxri.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.smart0.xyz/Article/details/gtjffqxvfb.html

Ruby: super
来源：http://dali.havefunace.top/Article/details/gtaphyroci.html

C#:   base.Greet();
来源：http://dali.yangfankeji.com/Article/details/gtkjbiedfb.html

[G08] 静态方法与属性
来源：http://dali.shanyushiyangkeji.top/Article/details/gtujixlthe.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hysaishi.cn/Article/details/gtxmrcxtgu.html

PHP:  public static function f() {}
来源：http://dali.ivvv.top/Article/details/gtxrtpytsc.html

JS:   static f() {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtykxjsgvs.html

TS:   static f(): void {}
来源：http://dali.shangyingyoupin.top/Article/details/gtgocviijc.html

Java: static void f() {}
来源：http://dali.chenzaomai.com/Article/details/gtemxpvuai.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.chenlongwang.top/Article/details/gtsnyxehrb.html

Ruby: def self.f; end
来源：http://dali.haohaochexian.top/Article/details/gtgflbhiwu.html

C#:   public static void F() {}
来源：http://dali.ehwqpu.com/Article/details/gtvcqjctji.html

[G09] 接口 / 抽象类
来源：http://dali.bjfxy.top/Article/details/gtlyqshkeg.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.bjfxy.top/Article/details/gtzgmggreb.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jinqigfzy.top/Article/details/gtefqhfnob.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.smart0.xyz/Article/details/gtmpjpekxw.html

TS:   interface Shape { area(): number; }
来源：http://dali.sufxvd.cn/Article/details/gtkjebelfo.html

Java: interface Shape { double area(); }
来源：http://dali.cdnleiting.top/Article/details/gtueermedc.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.nwbrower.top/Article/details/gtmexegssy.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.chenjidiqi.icu/Article/details/gtugpfgmpb.html

C#:   interface IShape { double Area(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtmxjvuibz.html

[G10] 访问控制
来源：http://dali.ppjwa.cn/Article/details/gteffosapz.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jianghu66.top/Article/details/gtwifhbtvy.html

PHP:  public / protected / private
来源：http://dali.pengpengdd.cyou/Article/details/gthwnkeoic.html

JS:   #private 字段；其余公开
来源：http://dali.bjfxy.top/Article/details/gtlrcraptp.html

TS:   public / protected / private
来源：http://dali.iojbl.cn/Article/details/gtxipkgqim.html

Java: public / protected / private / 默认包级
来源：http://dali.hammf.cn/Article/details/gtkapgvgmg.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.316326.xyz/Article/details/gtpwziofma.html

Ruby: public / protected / private
来源：http://dali.cashguo.top/Article/details/gtuqlsjawx.html

C#:   public / protected / private / internal
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzcfjntcx.html

[G11] getter / setter
来源：http://dali.shanyushiyangtech.top/Article/details/gtwfdwavgi.html

Py:   @property 与 @x.setter
来源：http://dali.jqgfzy.top/Article/details/gtkmltudjk.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.shuidangran.top/Article/details/gtvqlzryox.html

JS:   get name() { return this._name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtwcagqiyc.html

TS:   get name(): string { return this._name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsvjhntft.html

Java: public String getName() { return name; }
来源：http://dali.yuxming.cn/Article/details/gtxqouxggm.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.hnqzz.top/Article/details/gtjqygfjgl.html

Ruby: attr_accessor :name
来源：http://dali.zhiwuduotai.top/Article/details/gtxovluqhb.html

C#:   public string Name { get; set; }
来源：http://dali.jqgufenzy.top/Article/details/gttpiarinm.html

[G12] 对象转字符串
来源：http://dali.kuanghao11.cn/Article/details/gtcchgajqx.html

Py:   def __str__(self): return self.name
来源：http://dali.jqgufenzy.top/Article/details/gtymmxajgy.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.xziqi.cn/Article/details/gtphvifuas.html

JS:   toString() { return this.name; }
来源：http://dali.daria6918.cn/Article/details/gtdsdlhgyx.html

TS:   toString(): string { return this.name; }
来源：http://dali.meibo888.top/Article/details/gttaqlepra.html

Java: @Override public String toString() { return name; }
来源：http://dali.dashuyun.cn/Article/details/gtvdxnksls.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.kuanghao11.cn/Article/details/gttvlhfxli.html

Ruby: def to_s; @name; end
来源：http://dali.gzhubu.top/Article/details/gtrrbjxyzi.html

C#:   public override string ToString() => Name;
来源：http://dali.yuanzhike.top/Article/details/gtadkuwafy.html

[G13] 判断对象类型
来源：http://dali.zycfv.cn/Article/details/gtjdlfbjak.html

Py:   isinstance(u, User)
来源：http://dali.jinqigufen.top/Article/details/gtobmjsrdv.html

PHP:  $u instanceof User
来源：http://dali.xziqi.cn/Article/details/gtpmhwrunb.html

JS:   u instanceof User
来源：http://dali.gzhubu.top/Article/details/gthebzcjxm.html

TS:   u instanceof User
来源：http://dali.nanxuanxn.top/Article/details/gtbsycjtmp.html

Java: u instanceof User
来源：http://dali.zycfv.cn/Article/details/gtivfvqrdd.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hywenlv.cn/Article/details/gtdiljjkmr.html

Ruby: u.is_a?(User)
来源：http://dali.xuanzx.com/Article/details/gtotpzfdji.html

C#:   u is User
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlwaolfbg.html

[G14] 数据类 / record
来源：http://dali.yj202588.top/Article/details/gthacasagk.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.gogol.net.cn/Article/details/gtndiotqai.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yongpay.top/Article/details/gtbiriuntp.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.xuetiantiany.cn/Article/details/gttclmhdwi.html

TS:   type User = { name: string; age: number };
来源：http://dali.aibaodan.cn/Article/details/gteigbccqh.html

Java: record User(String name, int age) {}
来源：http://dali.jlsjyb.cn/Article/details/gtgbaphmne.html

Go:   type User struct { Name string; Age int }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlrfefxsh.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hysaishi.cn/Article/details/gtqsikhbck.html

C#:   record User(string Name, int Age);
来源：http://dali.cucudq.cn/Article/details/gtahtxtihx.html

[G15] 枚举
来源：http://dali.xuanzx.com/Article/details/gtrvnjntyn.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jlsjyb.cn/Article/details/gtnorvjzxu.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yj20258.top/Article/details/gtnigvghod.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.hywenlv.cn/Article/details/gtcdspiptr.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.dashuyun.cn/Article/details/gtnsyijnnl.html

Java: enum Color { RED, GREEN }
来源：http://dali.daxiang520.top/Article/details/gtemwrnwnl.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yonumen.top/Article/details/gtymtjnzio.html

Ruby: Color = %i[red green].freeze
来源：http://dali.redwolf501.top/Article/details/gtpyzdaves.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.birdmap.top/Article/details/gtpovltfyk.html

[G16] 对象转数组 / 字典
来源：http://dali.yanxiufei.cn/Article/details/gtpmayvomj.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.sxryk.cn/Article/details/gtiklkgdgo.html

PHP:  get_object_vars($obj);
来源：http://dali.jqgfzy.top/Article/details/gthqemmyhw.html

JS:   Object.entries(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtdseemmwf.html

TS:   Object.entries(obj)
来源：http://dali.snrcjt.cn/Article/details/gtnffoaewx.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.birdmap.top/Article/details/gtfgulixuy.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.aibaodan.cn/Article/details/gttppowcei.html

Ruby: obj.instance_variables
来源：http://dali.hnxiangtu.top/Article/details/gtwohflzgh.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.gotoacloud.top/Article/details/gtjsmqkuze.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtpsgfqlum.html

H. 异常与错误处理
来源：http://dali.c1oappe.top/Article/details/gtmizkemnr.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtsszoihex.html

[H01] try / catch 基础
来源：http://dali.sweek.top/Article/details/gtlhwscaqk.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.nanxuanxn.top/Article/details/gtmlofgtfc.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.gzhubu.top/Article/details/gtplimcbme.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.meibo888.top/Article/details/gtnkuqsitp.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.wangshuangyany.cn/Article/details/gtatmvjvkv.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.ybcxt.top/Article/details/gtcneezigr.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hammf.cn/Article/details/gteycimdoz.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.ppjwa.cn/Article/details/gtdkymwnrh.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.pengpengdd.cyou/Article/details/gtdrqxnwdr.html

[H02] finally / ensure 收尾
来源：http://dali.xuetiantiany.cn/Article/details/gteuapkbhp.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.daxiang520.top/Article/details/gtlmfecqqv.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.tian-w.cn/Article/details/gturdctuqo.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.snrcjt.cn/Article/details/gtwmbrvkej.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.tanke756.top/Article/details/gtpxgqvdxh.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.sufxvd.cn/Article/details/gtkfdwmrlj.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.sxryk.cn/Article/details/gtovqgtaud.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.aibaodan.cn/Article/details/gtjkdaqyym.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.daxiang520.top/Article/details/gtrtevyhai.html

[H03] 主动抛出异常
来源：http://dali.fzhhl.top/Article/details/gtixipdfsr.html

Py:   raise ValueError("错误信息")
来源：http://dali.yuxming.cn/Article/details/gtgekqymmy.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.gaohongyu789.top/Article/details/gtlmhpkvvw.html

JS:   throw new Error("错误信息");
来源：http://dali.yj20258.top/Article/details/gtoaaqdsrt.html

TS:   throw new Error("错误信息");
来源：http://dali.yuxming.cn/Article/details/gtvaojkygk.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.sysykeji.top/Article/details/gtqoqhbapg.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.guannengcc.top/Article/details/gtwbnxftwv.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsvzrbxdc.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.birdmap.top/Article/details/gtfhzxqirg.html

[H04] 自定义异常类型
来源：http://dali.xuetiantiany.cn/Article/details/gtnaqjcgst.html

Py:   class MyError(Exception): pass
来源：http://dali.zhixingplan.top/Article/details/gtyjcjialu.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.bjfxy.top/Article/details/gtoybiwvqq.html

JS:   class MyError extends Error {}
来源：http://dali.jqgfzy.top/Article/details/gthmwtvgnb.html

TS:   class MyError extends Error {}
来源：http://dali.dashuyun.cn/Article/details/gtnimxkhpu.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yj20258888.top/Article/details/gtqszbqdoc.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.hysaishi.cn/Article/details/gtalrsewzf.html

Ruby: class MyError < StandardError; end
来源：http://dali.hywenlv.cn/Article/details/gtmfrkzina.html

C#:   class MyException : Exception {}
来源：http://dali.wangdashe.top/Article/details/gtylbzpydz.html

[H05] 捕获特定类型
来源：http://dali.daria6918.cn/Article/details/gtrduwdlnm.html

Py:   except ValueError as e:
来源：http://dali.shzxlz.cn/Article/details/gttsswfofo.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jinqigufen.top/Article/details/gtcpmpepny.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.sysykeji.top/Article/details/gtdfkpcvli.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.nanxinkj.top/Article/details/gtconnkljo.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.pycfn.com/Article/details/gtvyqqsbto.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jqgufenzy.top/Article/details/gtktvkeiat.html

Ruby: rescue ArgumentError => e
来源：http://dali.ehwqpu.com/Article/details/gtrgxbztpt.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yuanzhike.top/Article/details/gtcfnxfeku.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jqgufenzy.top/Article/details/gtyqlkiphi.html

Py:   value = d.get("k") or default
来源：http://dali.cqqwz.cn/Article/details/gtwdqpfnji.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yanxiufei.cn/Article/details/gtwzrnacxt.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.tian-w.cn/Article/details/gtepuhvrtc.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.nanxinkj.top/Article/details/gtosdbktpo.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jinqigufen.top/Article/details/gtggdjaqhq.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.tian-w.cn/Article/details/gtdhuqinef.html

Ruby: d&.dig(:a, :b)
来源：http://dali.cashguo.top/Article/details/gtivumvdbz.html

C#:   obj?.A?.B ?? default
来源：http://dali.yuanzhike.top/Article/details/gtavkevute.html

[H07] 断言
来源：http://dali.ydzc1.top/Article/details/gtguwpwrem.html

Py:   assert x > 0, "必须为正"
来源：http://dali.cucudq.cn/Article/details/gtcbamdiaj.html

PHP:  assert($x > 0);
来源：http://dali.birdmap.top/Article/details/gtmfaqzfrm.html

JS:   console.assert(x > 0);
来源：http://dali.yueranfly.top/Article/details/gtwsavmnhx.html

TS:   console.assert(x > 0);
来源：http://dali.shanyushiyangtech.top/Article/details/gtkzvbkyot.html

Java: assert x > 0 : "必须为正";
来源：http://dali.svipenyu.cn/Article/details/gtonvmmxju.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.ydzc1.top/Article/details/gtljhfqmhi.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.redwolf501.top/Article/details/gtnohdobbl.html

C#:   Debug.Assert(x > 0);
来源：http://dali.shuidangran.top/Article/details/gturvisxxe.html

[H08] 获取错误信息与堆栈
来源：http://dali.yj202588.top/Article/details/gthslqyugb.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jqgufenzy.top/Article/details/gtoxiljoov.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jqgufenzy.top/Article/details/gtuvqatquz.html

JS:   e.message;  e.stack
来源：http://dali.yvedp.cn/Article/details/gthggdvwyi.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.gaohongyu789.top/Article/details/gtnfarsxth.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.guannengcc.top/Article/details/gtahrmjynt.html

Go:   err.Error()
来源：http://dali.xuanzx.com/Article/details/gthvkwfrwz.html

Ruby: e.message;  e.backtrace
来源：http://dali.xinyue.icu/Article/details/gtdptdjqmb.html

C#:   e.Message;  e.StackTrace
来源：http://dali.mhx1999.top/Article/details/gtqhvcxlsu.html

[H09] 带错误码的异常
来源：http://dali.guannengcc.top/Article/details/gtuqgkomjr.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.vqdsnc.cn/Article/details/gtcahclzzw.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.0kj1m.cn/Article/details/gtjqihvfkp.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.snrcjt.cn/Article/details/gtyrqsdikl.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yueranfly.top/Article/details/gtqagcpaim.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhongyouzk.top/Article/details/gtwtvlpxwm.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yj20258888.top/Article/details/gtslrcmomu.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.guannengcc.top/Article/details/gtqsmjtxsj.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.cucudq.cn/Article/details/gtsckljtxn.html

[H10] 资源自动释放
来源：http://dali.yongpay.top/Article/details/gtcgyduiur.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.xziqi.cn/Article/details/gtufhfkdas.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.guowangkeji.top/Article/details/gtagwgfqgm.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.fengsongda.top/Article/details/gtxhpjqddg.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.tianlin.xyz/Article/details/gtvppqhlmb.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.kuanghao11.cn/Article/details/gtorlkhmnj.html

Go:   defer f.Close()
来源：http://dali.kuanghao11.cn/Article/details/gtikkhhzuw.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.ppjwa.cn/Article/details/gtsdlluayw.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gttjwwozqu.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtcpaxtxto.html

I. 正则表达式
来源：http://dali.yanxiufei.cn/Article/details/gtzwkvqkwz.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gthxzeqdeo.html

[I01] 判断是否匹配
来源：http://dali.sxryk.cn/Article/details/gtubtdqzbt.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.chenlongwang.top/Article/details/gttuydymvg.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yj20258888.top/Article/details/gtflivctal.html

JS:   /\d+/.test(s)
来源：http://dali.mhx1999.top/Article/details/gtnxexdqah.html

TS:   /\d+/.test(s)
来源：http://dali.guowangkeji.top/Article/details/gtgaoxiaee.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.gotoacloud.top/Article/details/gtohlizuzm.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkzugivdr.html

Ruby: s.match?(/\d+/)
来源：http://dali.pycfn.com/Article/details/gtywshfgsq.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.hammf.cn/Article/details/gtoxtevrlk.html

[I02] 提取所有匹配
来源：http://dali.yanxiufei.cn/Article/details/gtaudppfad.html

Py:   re.findall(r"\d+", s)
来源：http://dali.c1oappe.top/Article/details/gticgwmuko.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.nwbrower.top/Article/details/gtkumpphyw.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yonumen.top/Article/details/gtyxbuzwsb.html

TS:   s.match(/\d+/g)
来源：http://dali.meibo888.top/Article/details/gtnralgpxy.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.ppjwa.cn/Article/details/gtrwrbwthr.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.feifeiyinyue.top/Article/details/gtyromgnvm.html

Ruby: s.scan(/\d+/)
来源：http://dali.gogol.net.cn/Article/details/gtxwjmoegu.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.yonumen.top/Article/details/gtahroavrr.html

[I03] 提取捕获分组
来源：http://dali.hysaishi.cn/Article/details/gtjhhrjjwf.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.zhijiandao.cn/Article/details/gtieabmzuj.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.guowangkeji.top/Article/details/gtirxmdkxw.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.xuetiantiany.cn/Article/details/gtumzusoin.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yj20258888.top/Article/details/gtoymyjkag.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yonumen.top/Article/details/gtobrrcsqi.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jianghu66.top/Article/details/gtfrrblphb.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.hnqzz.top/Article/details/gtklmsbrpw.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.hnxiangtu.top/Article/details/gtdqptojpm.html

[I04] 正则替换
来源：http://dali.tian-w.cn/Article/details/gtytolgfsc.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.xinyue.icu/Article/details/gtnxqfjnfa.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.fengsongda.top/Article/details/gtamxchsho.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.hnqzz.top/Article/details/gtsvlqudeg.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.havefunace.top/Article/details/gtfnpezehf.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.cucudq.cn/Article/details/gtfwjmoedv.html


<!-- 参考信息 -->