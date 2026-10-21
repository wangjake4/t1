代发 wailian999

TS:   fs.statSync("a.txt").size
来源：http://dali.yangfankeji.com/Article/details/gtbapwnpde.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.316326.xyz/Article/details/gtbndjfyyp.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.hnqzz.top/Article/details/gtgdckenng.html

Ruby: File.size("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtdgiczydm.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yonumen.top/Article/details/gtjktugqom.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.chenlongwang.top/Article/details/gthotcrsyf.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtludvtjdo.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gtcyeaomps.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtaacuisid.html

TS:   path.extname("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtjhgaqgdo.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.cqqwz.cn/Article/details/gtmanpqnsz.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtuoryujqu.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.fzhhl.top/Article/details/gtmgylkaux.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtoxpfpuuh.html

[F11] 复制与移动文件
来源：http://dali.jqgufenzy.top/Article/details/gtpqxepmoc.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.snrcjt.cn/Article/details/gtcisltxbj.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.hnqzz.top/Article/details/gtthvvcrqx.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hywenlv.cn/Article/details/gttcjevqak.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.havefunace.top/Article/details/gtepseljcu.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.sweek.top/Article/details/gtueaepgrl.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.xuanzx.com/Article/details/gtverycgxj.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtwjumgszf.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.snrcjt.cn/Article/details/gtgstygxdw.html

[F12] CSV 读写
来源：http://dali.guannengcc.top/Article/details/gttdslutfx.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlmbdoxju.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yangfankeji.com/Article/details/gtnniphrha.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.gogol.net.cn/Article/details/gtrteyisro.html

TS:   // 同上
来源：http://dali.birdmap.top/Article/details/gtuvcnipat.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxnrgvoef.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzdxleaoq.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.hnxiangtu.top/Article/details/gtwtuxthzd.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.smart0.xyz/Article/details/gthduznqcg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtfbomoxjd.html

G. 面向对象
来源：http://dali.ybcxt.top/Article/details/gtkgmektno.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtzamzdbmm.html

[G01] 定义类
来源：http://dali.feifeiyinyue.top/Article/details/gtdaupgppd.html

Py:   class User: pass
来源：http://dali.hywenlv.cn/Article/details/gtowuenzof.html

PHP:  class User {}
来源：http://dali.316326.xyz/Article/details/gtcarvrgda.html

JS:   class User {}
来源：http://dali.zhoulong.xyz/Article/details/gtzgzestqq.html

TS:   class User { name: string = ""; }
来源：http://dali.ivvv.top/Article/details/gtsxflfseb.html

Java: class User {}
来源：http://dali.jiagoushi.top/Article/details/gtoxyupjaa.html

Go:   type User struct { Name string }
来源：http://dali.cashguo.top/Article/details/gtewsijbca.html

Ruby: class User; end
来源：http://dali.meibo888.top/Article/details/gtsfsxotfg.html

C#:   class User {}
来源：http://dali.hysaishi.cn/Article/details/gthanvtghv.html

[G02] 构造函数
来源：http://dali.pengpengdd.cyou/Article/details/gtvfyxcqrk.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.daxiang520.top/Article/details/gtjpkuhbrv.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.gotoacloud.top/Article/details/gtofgucats.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtlktqynrw.html

TS:   constructor(public name: string) {}
来源：http://dali.zdqjudy.top/Article/details/gtjippteuu.html

Java: User(String name) { this.name = name; }
来源：http://dali.wangdashe.top/Article/details/gtpdwjjrah.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.316326.xyz/Article/details/gtbhcdyfjo.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.meibo888.top/Article/details/gtfysbtfwe.html

C#:   public User(string name) { Name = name; }
来源：http://dali.haohaochexian.top/Article/details/gtovdqwhcc.html

[G03] 实例属性
来源：http://dali.vqdsnc.cn/Article/details/gthjraqtcd.html

Py:   self.name = "x"
来源：http://dali.wangdashe.top/Article/details/gtqprpyfaf.html

PHP:  public string $name = "x";
来源：http://dali.jqgufenzy.top/Article/details/gtljirutyk.html

JS:   this.name = "x";
来源：http://dali.hnxiangtu.top/Article/details/gteglvatfi.html

TS:   name: string = "x";
来源：http://dali.svipenyu.cn/Article/details/gtpnjuidmm.html

Java: private String name;
来源：http://dali.cqqwz.cn/Article/details/gtxjtdmodi.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.chenjidiqi.icu/Article/details/gthtxkshmm.html

Ruby: @name = "x"
来源：http://dali.nanxinkj.top/Article/details/gtzyywvaey.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.sxryk.cn/Article/details/gtlabcjktb.html

[G04] 定义方法
来源：http://dali.hongshengwenyu.top/Article/details/gtrmeyrwsb.html

Py:   def greet(self): return self.name
来源：http://dali.fzhhl.top/Article/details/gtyjqyhlvr.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.chenzaomai.com/Article/details/gthebsmifo.html

JS:   greet() { return this.name; }
来源：http://dali.tanke756.top/Article/details/gtxjrsufby.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gthcpnhyip.html

Java: String greet() { return name; }
来源：http://dali.jqgfzy.top/Article/details/gtxvhxbfqa.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.cdnleiting.top/Article/details/gtrppwdyid.html

Ruby: def greet; @name; end
来源：http://dali.haohaochexian.top/Article/details/gtgnfnhdjg.html

C#:   public string Greet() => Name;
来源：http://dali.xinyue.icu/Article/details/gtflbfzxqn.html

[G05] 继承
来源：http://dali.daxiang520.top/Article/details/gtbgtackub.html

Py:   class Admin(User): pass
来源：http://dali.chenzaomai.com/Article/details/gttxyaxcqh.html

PHP:  class Admin extends User {}
来源：http://dali.sxryk.cn/Article/details/gtnbdgrgkf.html

JS:   class Admin extends User {}
来源：http://dali.sweek.top/Article/details/gtobhnlmce.html

TS:   class Admin extends User {}
来源：http://dali.yangfankeji.com/Article/details/gtzccnyobq.html

Java: class Admin extends User {}
来源：http://dali.redwolf501.top/Article/details/gtjtadqhcr.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.meibo888.top/Article/details/gtzgrneykw.html

Ruby: class Admin < User; end
来源：http://dali.zhiwuduotai.top/Article/details/gtmqteaxbs.html

C#:   class Admin : User {}
来源：http://dali.nanxinkj.top/Article/details/gtoppxfwhc.html

[G06] 重写方法
来源：http://dali.cashguo.top/Article/details/gtnmfrparh.html

Py:   def greet(self): return "admin"
来源：http://dali.gaohongyu789.top/Article/details/gturhhnuvg.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.mhx1999.top/Article/details/gtjuxtinld.html

JS:   greet() { return "admin"; }
来源：http://dali.quarkkingdee.top/Article/details/gtqyklbqpq.html

TS:   greet(): string { return "admin"; }
来源：http://dali.smart0.xyz/Article/details/gtgvqjneso.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.hywenlv.cn/Article/details/gthtophqva.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.nanxuanxn.top/Article/details/gtqthrhcqh.html

Ruby: def greet; "admin"; end
来源：http://dali.zhiwuduotai.top/Article/details/gtvprjoxgo.html

C#:   public override string Greet() => "admin";
来源：http://dali.guannengcc.top/Article/details/gteighymtn.html

[G07] 调用父类方法
来源：http://dali.feifeiyinyue.top/Article/details/gtwmrivgzx.html

Py:   super().greet()
来源：http://dali.zycfv.cn/Article/details/gtgacvdmwn.html

PHP:  parent::greet();
来源：http://dali.vqdsnc.cn/Article/details/gthqzrhpqi.html

JS:   super.greet();
来源：http://dali.yuxming.cn/Article/details/gtiegmremp.html

TS:   super.greet();
来源：http://dali.redwolf501.top/Article/details/gtevbdalyo.html

Java: super.greet();
来源：http://dali.zhiwuduotai.top/Article/details/gtjmvmwbpe.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.tanke756.top/Article/details/gtnpikwqpu.html

Ruby: super
来源：http://dali.iojbl.cn/Article/details/gtwixewzjm.html

C#:   base.Greet();
来源：http://dali.gaohongyu789.top/Article/details/gtsfjopggn.html

[G08] 静态方法与属性
来源：http://dali.yuanzhike.top/Article/details/gtgghgejpn.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhixingplan.top/Article/details/gtoewabpum.html

PHP:  public static function f() {}
来源：http://dali.zhijiandao.cn/Article/details/gtzwrrqnzn.html

JS:   static f() {}
来源：http://dali.mhx1999.top/Article/details/gtagjuhqxy.html

TS:   static f(): void {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsabqeoxg.html

Java: static void f() {}
来源：http://dali.jqgufenzy.top/Article/details/gtaebpmweq.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.bjfxy.top/Article/details/gtqgpgvbix.html

Ruby: def self.f; end
来源：http://dali.yj202588.top/Article/details/gtgrbcwspo.html

C#:   public static void F() {}
来源：http://dali.aizwys.cn/Article/details/gtrbmclfmi.html

[G09] 接口 / 抽象类
来源：http://dali.zhoulong.xyz/Article/details/gtjlwumiik.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.vqdsnc.cn/Article/details/gtdqyjbnbl.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.mhx1999.top/Article/details/gtqlqmfdnj.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jyoumei.cn/Article/details/gtfpjznoyc.html

TS:   interface Shape { area(): number; }
来源：http://dali.fzhhl.top/Article/details/gtkufnblzc.html

Java: interface Shape { double area(); }
来源：http://dali.kuanghao11.cn/Article/details/gtaivtwxqe.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zdqjudy.top/Article/details/gtzymuszty.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.gzhubu.top/Article/details/gtbzhwoile.html

C#:   interface IShape { double Area(); }
来源：http://dali.birdmap.top/Article/details/gtolhhwtcy.html

[G10] 访问控制
来源：http://dali.316326.xyz/Article/details/gtbpalbkgu.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yj20258888.top/Article/details/gttrwiobio.html

PHP:  public / protected / private
来源：http://dali.zhongyouzk.top/Article/details/gtljmnwitb.html

JS:   #private 字段；其余公开
来源：http://dali.hywenlv.cn/Article/details/gtslshfmfl.html

TS:   public / protected / private
来源：http://dali.tianlin.xyz/Article/details/gtpruovsoh.html

Java: public / protected / private / 默认包级
来源：http://dali.shzxlz.cn/Article/details/gtphywnofg.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jinghuilouyu.cn/Article/details/gtktmphamt.html

Ruby: public / protected / private
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxzdwyhkz.html

C#:   public / protected / private / internal
来源：http://dali.xuanzx.com/Article/details/gthjgmyfgv.html

[G11] getter / setter
来源：http://dali.ppjwa.cn/Article/details/gtatuobiqw.html

Py:   @property 与 @x.setter
来源：http://dali.yangfankeji.com/Article/details/gtzevgrimx.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtvfmmbvab.html

JS:   get name() { return this._name; }
来源：http://dali.cheryme.top/Article/details/gttghkiach.html

TS:   get name(): string { return this._name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtwfkbmqil.html

Java: public String getName() { return name; }
来源：http://dali.nwbrower.top/Article/details/gtndpefqdm.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yangfankeji.com/Article/details/gtznhunpcl.html

Ruby: attr_accessor :name
来源：http://dali.shanyushiyangtech.top/Article/details/gtkiexbxbp.html

C#:   public string Name { get; set; }
来源：http://dali.cucudq.cn/Article/details/gtnruvspib.html

[G12] 对象转字符串
来源：http://dali.zhixingplan.top/Article/details/gtlmbfpeno.html

Py:   def __str__(self): return self.name
来源：http://dali.xylfe.cn/Article/details/gtmuedhndl.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.sysykeji.top/Article/details/gtzwbtizhw.html

JS:   toString() { return this.name; }
来源：http://dali.c1oappe.top/Article/details/gthlbuaxqf.html

TS:   toString(): string { return this.name; }
来源：http://dali.quarkkingdee.top/Article/details/gtilqewcuz.html

Java: @Override public String toString() { return name; }
来源：http://dali.shzxlz.cn/Article/details/gtvzmvftny.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hnqzz.top/Article/details/gtmxlhvuba.html

Ruby: def to_s; @name; end
来源：http://dali.zhoulong.xyz/Article/details/gtsijzsgbk.html

C#:   public override string ToString() => Name;
来源：http://dali.zhengqikj.top/Article/details/gtaqmajukm.html

[G13] 判断对象类型
来源：http://dali.haohaochexian.top/Article/details/gtyvtmdone.html

Py:   isinstance(u, User)
来源：http://dali.sxryk.cn/Article/details/gtripzemus.html

PHP:  $u instanceof User
来源：http://dali.chenzaomai.com/Article/details/gtfdncbmwf.html

JS:   u instanceof User
来源：http://dali.c1oappe.top/Article/details/gtuuizrxhc.html

TS:   u instanceof User
来源：http://dali.zycfv.cn/Article/details/gtepvmubde.html

Java: u instanceof User
来源：http://dali.gogol.net.cn/Article/details/gtoxvltsux.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.andypj.xyz/Article/details/gtrgjqielz.html

Ruby: u.is_a?(User)
来源：http://dali.ydzc1.top/Article/details/gtwpsotmkn.html

C#:   u is User
来源：http://dali.yj20258888.top/Article/details/gtnvtrpovl.html

[G14] 数据类 / record
来源：http://dali.daxiang520.top/Article/details/gtkitqjmza.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.hongshengwenyu.top/Article/details/gtfsrqparu.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hnxiangtu.top/Article/details/gtxmbwkazm.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yj20258.top/Article/details/gteynednez.html

TS:   type User = { name: string; age: number };
来源：http://dali.guannengcc.top/Article/details/gtwlsnalup.html

Java: record User(String name, int age) {}
来源：http://dali.ehwqpu.com/Article/details/gtrbmsstgk.html

Go:   type User struct { Name string; Age int }
来源：http://dali.guannengcc.top/Article/details/gtplrnzsxy.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.xinyue.icu/Article/details/gtifckhudc.html

C#:   record User(string Name, int Age);
来源：http://dali.yueranfly.top/Article/details/gtqbrbkbyc.html

[G15] 枚举
来源：http://dali.ivvv.top/Article/details/gtyxanwxcm.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.ybcxt.top/Article/details/gtwvsflrds.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtjutwwdeb.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jqgfzy.top/Article/details/gtafhzkxml.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yanxiufei.cn/Article/details/gtxjzgihja.html

Java: enum Color { RED, GREEN }
来源：http://dali.mhx1999.top/Article/details/gtfjpujhlw.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.xinyue.icu/Article/details/gtzuapqpmd.html

Ruby: Color = %i[red green].freeze
来源：http://dali.hongshengwenyu.top/Article/details/gtxpnrempu.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hnqzz.top/Article/details/gtsrrgkxrp.html

[G16] 对象转数组 / 字典
来源：http://dali.zhiwuduotai.top/Article/details/gthyboosai.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.cdnleiting.top/Article/details/gthysmjxto.html

PHP:  get_object_vars($obj);
来源：http://dali.hysaishi.cn/Article/details/gtsnbdfdkw.html

JS:   Object.entries(obj)
来源：http://dali.fengsongda.top/Article/details/gtqnwsgmnr.html

TS:   Object.entries(obj)
来源：http://dali.sufxvd.cn/Article/details/gtjuvwxele.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.xuetiantiany.cn/Article/details/gtkgmismuw.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.sufxvd.cn/Article/details/gtdpyclhwd.html

Ruby: obj.instance_variables
来源：http://dali.svipenyu.cn/Article/details/gtnlpuaxyr.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.cdnleiting.top/Article/details/gtwoswshrv.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtqsxujxbq.html

H. 异常与错误处理
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuotprncy.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtiomrbmdz.html

[H01] try / catch 基础
来源：http://dali.yj20258.top/Article/details/gtcnkmztdd.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.guowangkeji.top/Article/details/gttflapvls.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jqgfzy.top/Article/details/gtqxhlxarh.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.ehwqpu.com/Article/details/gtoibdgnut.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jinqigufen.top/Article/details/gthcjateaw.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.tian-w.cn/Article/details/gtjohqvpbd.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.wangdashe.top/Article/details/gtdkhnpxik.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhixingplan.top/Article/details/gtktgasdye.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.0kj1m.cn/Article/details/gtrvaqjspp.html

[H02] finally / ensure 收尾
来源：http://dali.sxryk.cn/Article/details/gtsozecqzf.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.birdmap.top/Article/details/gtfrhxfdfp.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yangfankeji.com/Article/details/gtckugdauz.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.xylfe.cn/Article/details/gtfmvznahq.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yongpay.top/Article/details/gtcroengzq.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.gogol.net.cn/Article/details/gtlzcamwie.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.kuanghao11.cn/Article/details/gtflhqckin.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.nanxinkj.top/Article/details/gtpuztlgsr.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.9152youxi.cn/Article/details/gtscukzbvx.html

[H03] 主动抛出异常
来源：http://dali.feifeiyinyue.top/Article/details/gtwguzeaxl.html

Py:   raise ValueError("错误信息")
来源：http://dali.gogol.net.cn/Article/details/gtescnprsa.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.tanke756.top/Article/details/gtkfejjasa.html

JS:   throw new Error("错误信息");
来源：http://dali.sxryk.cn/Article/details/gtvmmtkvuz.html

TS:   throw new Error("错误信息");
来源：http://dali.0kj1m.cn/Article/details/gtpmsxeqth.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvogzcxbx.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.ivvv.top/Article/details/gtgnbmwhcc.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.guowangkeji.top/Article/details/gtmuxgrgrk.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.cqqwz.cn/Article/details/gtvfvujnzu.html

[H04] 自定义异常类型
来源：http://dali.hammf.cn/Article/details/gtyeqrpxbc.html

Py:   class MyError(Exception): pass
来源：http://dali.sweek.top/Article/details/gtuqtafocy.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.shanyushiyangtech.top/Article/details/gthvsevmcu.html

JS:   class MyError extends Error {}
来源：http://dali.hongshengwenyu.top/Article/details/gtgkurtviv.html

TS:   class MyError extends Error {}
来源：http://dali.jinqigufen.top/Article/details/gtupecfpwl.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yuxming.cn/Article/details/gtmfgoyukq.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.gotoacloud.top/Article/details/gtiipcfuci.html

Ruby: class MyError < StandardError; end
来源：http://dali.zycfv.cn/Article/details/gtjjlesfwa.html

C#:   class MyException : Exception {}
来源：http://dali.kuanghao11.cn/Article/details/gtlxxomyre.html

[H05] 捕获特定类型
来源：http://dali.yvedp.cn/Article/details/gtrdumkdrc.html

Py:   except ValueError as e:
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlcjsppsm.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.feifeiyinyue.top/Article/details/gtuykhhzuu.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zycfv.cn/Article/details/gtdlmcknmp.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jianghu66.top/Article/details/gtpesikomk.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gtuuabpcoi.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.gaohongyu789.top/Article/details/gtbcoczuus.html

Ruby: rescue ArgumentError => e
来源：http://dali.wangdashe.top/Article/details/gtfyrleind.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.vqdsnc.cn/Article/details/gtxkkgxeax.html

[H06] 可选值 / 空值安全访问
来源：http://dali.daxiang520.top/Article/details/gtiszlcpmc.html

Py:   value = d.get("k") or default
来源：http://dali.chenzaomai.com/Article/details/gtuinducmf.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jinqigfzy.top/Article/details/gtpluaqyys.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.wangshuangyany.cn/Article/details/gtxdotplrg.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.shanyushiyangkeji.top/Article/details/gtihszzplv.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.shanyushiyangtech.top/Article/details/gtuwjnkylx.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.hysaishi.cn/Article/details/gtytcdnfdt.html

Ruby: d&.dig(:a, :b)
来源：http://dali.birdmap.top/Article/details/gttziuhxtk.html

C#:   obj?.A?.B ?? default
来源：http://dali.hysaishi.cn/Article/details/gttitowcgv.html

[H07] 断言
来源：http://dali.zycfv.cn/Article/details/gtrmrehoea.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yonumen.top/Article/details/gtffbdscsr.html

PHP:  assert($x > 0);
来源：http://dali.yongpay.top/Article/details/gtfqnbbbyf.html

JS:   console.assert(x > 0);
来源：http://dali.tianlin.xyz/Article/details/gtqgajkzyx.html

TS:   console.assert(x > 0);
来源：http://dali.guannengcc.top/Article/details/gthdfdlixc.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yj20258.top/Article/details/gtafakdlip.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yonumen.top/Article/details/gtqchhrquy.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.shanyushiyangtech.top/Article/details/gtpeimkgle.html

C#:   Debug.Assert(x > 0);
来源：http://dali.wangshuangyany.cn/Article/details/gtuwurdpxq.html

[H08] 获取错误信息与堆栈
来源：http://dali.jinghuilouyu.cn/Article/details/gthlxvwjpq.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jiagoushi.top/Article/details/gtyfvyzwpi.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.svipenyu.cn/Article/details/gtqhjjnbgr.html

JS:   e.message;  e.stack
来源：http://dali.havefunace.top/Article/details/gtoixgbnja.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.hammf.cn/Article/details/gtafpdkxwi.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.chenzaomai.com/Article/details/gtrvjznzai.html

Go:   err.Error()
来源：http://dali.daria6918.cn/Article/details/gtntovgugt.html

Ruby: e.message;  e.backtrace
来源：http://dali.sweek.top/Article/details/gtiaobgqiq.html

C#:   e.Message;  e.StackTrace
来源：http://dali.aizwys.cn/Article/details/gtgwoknnrm.html

[H09] 带错误码的异常
来源：http://dali.hongshengwenyu.top/Article/details/gtmqvienpl.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.ppjwa.cn/Article/details/gtrbwmiwnf.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtklsvkqkp.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.haohaochexian.top/Article/details/gtvvnutyok.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaqsmprng.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yangfankeji.com/Article/details/gtjeheqaei.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.cashguo.top/Article/details/gtbfmdajxa.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.ehwqpu.com/Article/details/gtfmexferh.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpelayyoj.html

[H10] 资源自动释放
来源：http://dali.dianchejie.cn/Article/details/gtmngkzeqy.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.chenzaomai.com/Article/details/gtozykqalg.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.iojbl.cn/Article/details/gtvzpjzefl.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinqigufen.top/Article/details/gtnqtefokn.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ydzc1.top/Article/details/gtckknzran.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.tanke756.top/Article/details/gtdiutewtp.html

Go:   defer f.Close()
来源：http://dali.bjfxy.top/Article/details/gthfzugnxr.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.shanyushiyangtech.top/Article/details/gtulnbwhnh.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.sxryk.cn/Article/details/gtmlzsxsjl.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gthbqmasst.html

I. 正则表达式
来源：http://dali.hongshengwenyu.top/Article/details/gteufossmy.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtnbuupvbg.html

[I01] 判断是否匹配
来源：http://dali.wangdashe.top/Article/details/gtxvowhxxa.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.wangshuangyany.cn/Article/details/gtrpxcnius.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.pengpengdd.cyou/Article/details/gtgybhtmoa.html

JS:   /\d+/.test(s)
来源：http://dali.yueranfly.top/Article/details/gteeywckle.html

TS:   /\d+/.test(s)
来源：http://dali.hnxiangtu.top/Article/details/gtiafwcdea.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.tanke756.top/Article/details/gtzztzqkes.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.daxiang520.top/Article/details/gtkwisfliy.html

Ruby: s.match?(/\d+/)
来源：http://dali.guannengcc.top/Article/details/gtbkfnewvq.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.cqqwz.cn/Article/details/gtfosbpzst.html

[I02] 提取所有匹配
来源：http://dali.xuetiantiany.cn/Article/details/gtvbzmhwcf.html

Py:   re.findall(r"\d+", s)
来源：http://dali.hywenlv.cn/Article/details/gthcipvoux.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.haohaochexian.top/Article/details/gtpigqiiwi.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.cashguo.top/Article/details/gtzsuwswur.html

TS:   s.match(/\d+/g)
来源：http://dali.jinghuilouyu.cn/Article/details/gtkhzdfeco.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhixingplan.top/Article/details/gttilhagxp.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.aibaodan.cn/Article/details/gttbskxqmu.html

Ruby: s.scan(/\d+/)
来源：http://dali.mhx1999.top/Article/details/gtptpcstqj.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.tianlin.xyz/Article/details/gtfkesnugw.html

[I03] 提取捕获分组
来源：http://dali.jiagoushi.top/Article/details/gtnpoowhmm.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yvedp.cn/Article/details/gtatlcewol.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.jyoumei.cn/Article/details/gtcppebwnl.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvyywfdab.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.cheryme.top/Article/details/gtszdojzdt.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtolgdfnkl.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.redwolf501.top/Article/details/gtviggtzly.html


<!-- 参考信息 -->