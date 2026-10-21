代发 wailian999

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yanxiufei.cn/Article/details/gtvrlmprxi.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.316326.xyz/Article/details/gtrgtvhowk.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xinyue.icu/Article/details/gtuchhpckm.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.gotoacloud.top/Article/details/gtbxabgcga.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yueranfly.top/Article/details/gtuzragaef.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.ehwqpu.com/Article/details/gtkxpbjkex.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.fzhhl.top/Article/details/gtrhdhaufk.html

[F08] 遍历目录
来源：http://dali.hywenlv.cn/Article/details/gtmfhhvhmz.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhoulong.xyz/Article/details/gtzcuzycya.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jinqigufen.top/Article/details/gtnvgrleib.html

JS:   fs.readdirSync("dir")
来源：http://dali.vqdsnc.cn/Article/details/gtnaigoypi.html

TS:   fs.readdirSync("dir")
来源：http://dali.jinghuilouyu.cn/Article/details/gtcmiffgpb.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.havefunace.top/Article/details/gtgdfxikgl.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhoulong.xyz/Article/details/gtkdaxlfhv.html

Ruby: Dir.children("dir")
来源：http://dali.quarkkingdee.top/Article/details/gtdcfcvkly.html

C#:   Directory.GetFiles("dir")
来源：http://dali.tianlin.xyz/Article/details/gtswytvqmv.html

[F09] 获取文件大小
来源：http://dali.zhengqikj.top/Article/details/gtctqfgpve.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtivervubr.html

PHP:  filesize("a.txt");
来源：http://dali.iojbl.cn/Article/details/gtnwbnthet.html

JS:   fs.statSync("a.txt").size
来源：http://dali.dashuyun.cn/Article/details/gtyijrzjwl.html

TS:   fs.statSync("a.txt").size
来源：http://dali.nanxinkj.top/Article/details/gtqcldvhyj.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zycfv.cn/Article/details/gtyfejxjre.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.dashuyun.cn/Article/details/gtcgeiixqe.html

Ruby: File.size("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gthiugxlnc.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.haohaochexian.top/Article/details/gtzhadlwsj.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.guowangkeji.top/Article/details/gtfmxlmhni.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtvmzmwbpb.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.hywenlv.cn/Article/details/gtopcwymdr.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtcxdqmnnn.html

TS:   path.extname("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtakdiftys.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hnqzz.top/Article/details/gthepphhyr.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.wangdashe.top/Article/details/gtwqdcwdvr.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.birdmap.top/Article/details/gtgzkxbbik.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.ppjwa.cn/Article/details/gteqstdoka.html

[F11] 复制与移动文件
来源：http://dali.hysaishi.cn/Article/details/gtnctfdpni.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.cheryme.top/Article/details/gtrtiacfeq.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.andypj.xyz/Article/details/gttfdydcwp.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shuidangran.top/Article/details/gttootqjrk.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hnqzz.top/Article/details/gtypmxhrhb.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.sysykeji.top/Article/details/gtqzqouipl.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.hfpthk.cn/Article/details/gtvmecfcmg.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yj202588.top/Article/details/gtjmocxhch.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yongpay.top/Article/details/gtaozlazaw.html

[F12] CSV 读写
来源：http://dali.yongpay.top/Article/details/gtvmmsbhlc.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jyoumei.cn/Article/details/gtirsagyhz.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.cdnleiting.top/Article/details/gtclugfnif.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jinqigufen.top/Article/details/gtwjytezze.html

TS:   // 同上
来源：http://dali.tanke756.top/Article/details/gtlzxqjyrs.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yueranfly.top/Article/details/gttibvdfyu.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.xuanzx.com/Article/details/gtkkjunotq.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.xinyue.icu/Article/details/gtyfthqrlc.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhongyouzk.top/Article/details/gtnnijmlsa.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtblyqjksg.html

G. 面向对象
来源：http://dali.sysykeji.top/Article/details/gtbsvmuebx.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtotpfpayb.html

[G01] 定义类
来源：http://dali.shangyingyoupin.top/Article/details/gttilmnsbl.html

Py:   class User: pass
来源：http://dali.yueranfly.top/Article/details/gtqqvdmruy.html

PHP:  class User {}
来源：http://dali.daxiang520.top/Article/details/gthvcdzwck.html

JS:   class User {}
来源：http://dali.hongshengwenyu.top/Article/details/gtzvysbpxh.html

TS:   class User { name: string = ""; }
来源：http://dali.zhiwuduotai.top/Article/details/gtsgllcmxp.html

Java: class User {}
来源：http://dali.xziqi.cn/Article/details/gttkgjciva.html

Go:   type User struct { Name string }
来源：http://dali.9152youxi.cn/Article/details/gtvoctsdck.html

Ruby: class User; end
来源：http://dali.quarkkingdee.top/Article/details/gttqhdpnrq.html

C#:   class User {}
来源：http://dali.haohaochexian.top/Article/details/gtsayshscb.html

[G02] 构造函数
来源：http://dali.ybcxt.top/Article/details/gtipfqvedu.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhoulong.xyz/Article/details/gtagrbmvex.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hywenlv.cn/Article/details/gttazhdpop.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.vqdsnc.cn/Article/details/gtdkapwroh.html

TS:   constructor(public name: string) {}
来源：http://dali.bjfxy.top/Article/details/gtpahufmjy.html

Java: User(String name) { this.name = name; }
来源：http://dali.yueranfly.top/Article/details/gtrpaneeuq.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmpujgwyn.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hammf.cn/Article/details/gtqitplaep.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zdqjudy.top/Article/details/gtilubqmod.html

[G03] 实例属性
来源：http://dali.yj20258888.top/Article/details/gtgjmypqks.html

Py:   self.name = "x"
来源：http://dali.nanxuanxn.top/Article/details/gtjasjuzsj.html

PHP:  public string $name = "x";
来源：http://dali.jlsjyb.cn/Article/details/gtxiwtxspi.html

JS:   this.name = "x";
来源：http://dali.daxiang520.top/Article/details/gtwbumnvgv.html

TS:   name: string = "x";
来源：http://dali.chenzaomai.com/Article/details/gtjrjtaufa.html

Java: private String name;
来源：http://dali.gzhubu.top/Article/details/gtwkmqmqeu.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.ydzc1.top/Article/details/gtzkovgmyc.html

Ruby: @name = "x"
来源：http://dali.yangfankeji.com/Article/details/gtirswzstl.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.xinyue.icu/Article/details/gtcuxqbcnf.html

[G04] 定义方法
来源：http://dali.ppjwa.cn/Article/details/gtorzklzbi.html

Py:   def greet(self): return self.name
来源：http://dali.pycfn.com/Article/details/gtzquaclvm.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zycfv.cn/Article/details/gtcxnlmocg.html

JS:   greet() { return this.name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdbdxmtmt.html

TS:   greet(): string { return this.name; }
来源：http://dali.meibo888.top/Article/details/gtsualjrfe.html

Java: String greet() { return name; }
来源：http://dali.cucudq.cn/Article/details/gttoqvlrzq.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jinqigfzy.top/Article/details/gtokayspwa.html

Ruby: def greet; @name; end
来源：http://dali.xziqi.cn/Article/details/gtspssqmkw.html

C#:   public string Greet() => Name;
来源：http://dali.hfpthk.cn/Article/details/gtgakyqyxb.html

[G05] 继承
来源：http://dali.0kj1m.cn/Article/details/gtzcsdhosw.html

Py:   class Admin(User): pass
来源：http://dali.cucudq.cn/Article/details/gtwyegeoxi.html

PHP:  class Admin extends User {}
来源：http://dali.nwbrower.top/Article/details/gtkarvkmlq.html

JS:   class Admin extends User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtefmxrjkq.html

TS:   class Admin extends User {}
来源：http://dali.sysykeji.top/Article/details/gtewkxvvma.html

Java: class Admin extends User {}
来源：http://dali.nanxuanxn.top/Article/details/gtojqsthkr.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.wangdashe.top/Article/details/gttlqlustn.html

Ruby: class Admin < User; end
来源：http://dali.shangyingyoupin.top/Article/details/gtesrpnkhm.html

C#:   class Admin : User {}
来源：http://dali.feifeiyinyue.top/Article/details/gtcigbubjf.html

[G06] 重写方法
来源：http://dali.hywenlv.cn/Article/details/gtbjojynod.html

Py:   def greet(self): return "admin"
来源：http://dali.chenjidiqi.icu/Article/details/gtclfbphwv.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.nwbrower.top/Article/details/gtwmnblzvl.html

JS:   greet() { return "admin"; }
来源：http://dali.yvedp.cn/Article/details/gtfbtcduzp.html

TS:   greet(): string { return "admin"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjzeaiaqm.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.mhx1999.top/Article/details/gtohxeyzxw.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhongyouzk.top/Article/details/gticgyhqwc.html

Ruby: def greet; "admin"; end
来源：http://dali.gotoacloud.top/Article/details/gtdvqmvshr.html

C#:   public override string Greet() => "admin";
来源：http://dali.feifeiyinyue.top/Article/details/gtvtpsqxna.html

[G07] 调用父类方法
来源：http://dali.daria6918.cn/Article/details/gtcfexfypx.html

Py:   super().greet()
来源：http://dali.snrcjt.cn/Article/details/gtxoejozpz.html

PHP:  parent::greet();
来源：http://dali.bjfxy.top/Article/details/gtfurtsrqd.html

JS:   super.greet();
来源：http://dali.yj20258888.top/Article/details/gtzguoobrm.html

TS:   super.greet();
来源：http://dali.guowangkeji.top/Article/details/gtqnjggajr.html

Java: super.greet();
来源：http://dali.zycfv.cn/Article/details/gtmxpnolku.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhengqikj.top/Article/details/gtvkwmxuud.html

Ruby: super
来源：http://dali.chenlongwang.top/Article/details/gtmopndvar.html

C#:   base.Greet();
来源：http://dali.xuetiantiany.cn/Article/details/gtznwumfyl.html

[G08] 静态方法与属性
来源：http://dali.wangdashe.top/Article/details/gtlogfxdgt.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.sufxvd.cn/Article/details/gteycuxuoy.html

PHP:  public static function f() {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtchojhmdx.html

JS:   static f() {}
来源：http://dali.nwbrower.top/Article/details/gtfguycyaw.html

TS:   static f(): void {}
来源：http://dali.kuanghao11.cn/Article/details/gtwbnyysav.html

Java: static void f() {}
来源：http://dali.9152youxi.cn/Article/details/gtplidrdao.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.fzhhl.top/Article/details/gtfdjitsab.html

Ruby: def self.f; end
来源：http://dali.meibo888.top/Article/details/gtidyinqha.html

C#:   public static void F() {}
来源：http://dali.pengpengdd.cyou/Article/details/gtfwqbzoma.html

[G09] 接口 / 抽象类
来源：http://dali.vqdsnc.cn/Article/details/gtqwbevxwu.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zdqjudy.top/Article/details/gtmgairsgu.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jyoumei.cn/Article/details/gtcosbbpgj.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.smart0.xyz/Article/details/gtwggklszm.html

TS:   interface Shape { area(): number; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpuytbksu.html

Java: interface Shape { double area(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtwsgmlppx.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zdqjudy.top/Article/details/gtqpmlgvvm.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhoulong.xyz/Article/details/gtlowdeftg.html

C#:   interface IShape { double Area(); }
来源：http://dali.chenjidiqi.icu/Article/details/gthvtsolck.html

[G10] 访问控制
来源：http://dali.wangshuangyany.cn/Article/details/gtfdkcqhbd.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.ivvv.top/Article/details/gtjvkexwid.html

PHP:  public / protected / private
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdxrsalfd.html

JS:   #private 字段；其余公开
来源：http://dali.daria6918.cn/Article/details/gtzepyzsos.html

TS:   public / protected / private
来源：http://dali.daria6918.cn/Article/details/gtvjhgfsku.html

Java: public / protected / private / 默认包级
来源：http://dali.vqdsnc.cn/Article/details/gtrwufendc.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.tianlin.xyz/Article/details/gtaeykhoog.html

Ruby: public / protected / private
来源：http://dali.jinghuilouyu.cn/Article/details/gtfaltdfhx.html

C#:   public / protected / private / internal
来源：http://dali.zhengqikj.top/Article/details/gtqfrzsvlp.html

[G11] getter / setter
来源：http://dali.zhengqikj.top/Article/details/gtbommygkc.html

Py:   @property 与 @x.setter
来源：http://dali.yongpay.top/Article/details/gtjkahwrud.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.ppjwa.cn/Article/details/gtmgmugbrb.html

JS:   get name() { return this._name; }
来源：http://dali.ppjwa.cn/Article/details/gttyqaumrx.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhoulong.xyz/Article/details/gtjciwsdis.html

Java: public String getName() { return name; }
来源：http://dali.zhongyouzk.top/Article/details/gtgqklsbyc.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.guannengcc.top/Article/details/gtrbvhehbs.html

Ruby: attr_accessor :name
来源：http://dali.quarkkingdee.top/Article/details/gtytlhuvzk.html

C#:   public string Name { get; set; }
来源：http://dali.yvedp.cn/Article/details/gteipjgnxm.html

[G12] 对象转字符串
来源：http://dali.cdnleiting.top/Article/details/gtrvzsvboz.html

Py:   def __str__(self): return self.name
来源：http://dali.cdnleiting.top/Article/details/gtxaicoaul.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.cdnleiting.top/Article/details/gtkgttussf.html

JS:   toString() { return this.name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtqvqfsnrm.html

TS:   toString(): string { return this.name; }
来源：http://dali.guannengcc.top/Article/details/gtrqiwdqrj.html

Java: @Override public String toString() { return name; }
来源：http://dali.sysykeji.top/Article/details/gtrmlufgbt.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gtyrbwvhet.html

Ruby: def to_s; @name; end
来源：http://dali.yj20258888.top/Article/details/gtvsbjwtkb.html

C#:   public override string ToString() => Name;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrckicjku.html

[G13] 判断对象类型
来源：http://dali.c1oappe.top/Article/details/gtznxtswxt.html

Py:   isinstance(u, User)
来源：http://dali.yuxming.cn/Article/details/gtzuqyepia.html

PHP:  $u instanceof User
来源：http://dali.shuidangran.top/Article/details/gtcmonblgt.html

JS:   u instanceof User
来源：http://dali.andypj.xyz/Article/details/gtrotxklsp.html

TS:   u instanceof User
来源：http://dali.chenlongwang.top/Article/details/gtmxqgkxcr.html

Java: u instanceof User
来源：http://dali.andypj.xyz/Article/details/gthveenwim.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yangfankeji.com/Article/details/gtinatbagx.html

Ruby: u.is_a?(User)
来源：http://dali.wangshuangyany.cn/Article/details/gtgawkiarx.html

C#:   u is User
来源：http://dali.hywenlv.cn/Article/details/gthidoimeb.html

[G14] 数据类 / record
来源：http://dali.jinqigfzy.top/Article/details/gtqjdyrlvj.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.0kj1m.cn/Article/details/gterbvxpfl.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.ydzc1.top/Article/details/gtelowzglz.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jianghu66.top/Article/details/gtjjohypsq.html

TS:   type User = { name: string; age: number };
来源：http://dali.hysaishi.cn/Article/details/gthyqxufat.html

Java: record User(String name, int age) {}
来源：http://dali.sxryk.cn/Article/details/gtifozxavu.html

Go:   type User struct { Name string; Age int }
来源：http://dali.dianchejie.cn/Article/details/gtuihzsvdc.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hywenlv.cn/Article/details/gthnnzntgp.html

C#:   record User(string Name, int Age);
来源：http://dali.guowangkeji.top/Article/details/gteynefpbl.html

[G15] 枚举
来源：http://dali.chenjidiqi.icu/Article/details/gtoxmmbrjz.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jinqigfzy.top/Article/details/gtjcrlemsw.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.chenlongwang.top/Article/details/gtqqclqueg.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jqgfzy.top/Article/details/gtrqmihlxh.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jianghu66.top/Article/details/gteemnamky.html

Java: enum Color { RED, GREEN }
来源：http://dali.iojbl.cn/Article/details/gtulsxtubo.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.hysaishi.cn/Article/details/gtlfrwksrr.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jyoumei.cn/Article/details/gttkobhrxj.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.smart0.xyz/Article/details/gtftsunrmo.html

[G16] 对象转数组 / 字典
来源：http://dali.jinqigfzy.top/Article/details/gtateghozh.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.hywenlv.cn/Article/details/gtjaohcpdi.html

PHP:  get_object_vars($obj);
来源：http://dali.dianchejie.cn/Article/details/gthroitnzx.html

JS:   Object.entries(obj)
来源：http://dali.chenzaomai.com/Article/details/gtuebbsuxh.html

TS:   Object.entries(obj)
来源：http://dali.mhx1999.top/Article/details/gtbaeqelbz.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqrgpryzd.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttcrvvjti.html

Ruby: obj.instance_variables
来源：http://dali.ydzc1.top/Article/details/gtufnrqvqz.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.shanyushiyangtech.top/Article/details/gtchunwwmm.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtqzylynrq.html

H. 异常与错误处理
来源：http://dali.shuidangran.top/Article/details/gtpofevhxn.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtieqgubix.html

[H01] try / catch 基础
来源：http://dali.nanxinkj.top/Article/details/gtnjsjuxco.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.guowangkeji.top/Article/details/gtnsaobxkr.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.sufxvd.cn/Article/details/gtbupuigcy.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.haohaochexian.top/Article/details/gtbbqcubdb.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.hnqzz.top/Article/details/gtozjlbehu.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hammf.cn/Article/details/gtwiwirqry.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yangfankeji.com/Article/details/gtkpbjyvpu.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.meibo888.top/Article/details/gtkgpwwtej.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zycfv.cn/Article/details/gthffzoxfs.html

[H02] finally / ensure 收尾
来源：http://dali.zhengqikj.top/Article/details/gtrxwmjmuu.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhiwuduotai.top/Article/details/gtaznlawae.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yongpay.top/Article/details/gtoccygwlw.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.svipenyu.cn/Article/details/gtpvqitahv.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.gotoacloud.top/Article/details/gtjyzpullz.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.meibo888.top/Article/details/gtuhvqetna.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.chenlongwang.top/Article/details/gtlcefufek.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.sxryk.cn/Article/details/gtrtcdhyqt.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtsomahxoj.html

[H03] 主动抛出异常
来源：http://dali.zycfv.cn/Article/details/gtjwrtmycl.html

Py:   raise ValueError("错误信息")
来源：http://dali.vqdsnc.cn/Article/details/gtbszspdch.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.xylfe.cn/Article/details/gtwfqlbgtl.html

JS:   throw new Error("错误信息");
来源：http://dali.nanxinkj.top/Article/details/gtlqmqotkk.html

TS:   throw new Error("错误信息");
来源：http://dali.pycfn.com/Article/details/gtyyvhrwfy.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.pycfn.com/Article/details/gtngykaqxe.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.bjfxy.top/Article/details/gtipjzpqah.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhengqikj.top/Article/details/gtuuobawnu.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.andypj.xyz/Article/details/gtxemvsopb.html

[H04] 自定义异常类型
来源：http://dali.xinyue.icu/Article/details/gtgxdrxfdm.html

Py:   class MyError(Exception): pass
来源：http://dali.hywenlv.cn/Article/details/gtnjqbzzgn.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.tanke756.top/Article/details/gtieqplelk.html

JS:   class MyError extends Error {}
来源：http://dali.sysykeji.top/Article/details/gtuldzvehj.html

TS:   class MyError extends Error {}
来源：http://dali.316326.xyz/Article/details/gtaxkregnn.html

Java: class MyException extends RuntimeException {}
来源：http://dali.nanxinkj.top/Article/details/gtmunbpuik.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.hysaishi.cn/Article/details/gtnynrfaes.html

Ruby: class MyError < StandardError; end
来源：http://dali.xziqi.cn/Article/details/gtcggrlmbg.html

C#:   class MyException : Exception {}
来源：http://dali.vqdsnc.cn/Article/details/gternrgngv.html

[H05] 捕获特定类型
来源：http://dali.0kj1m.cn/Article/details/gthcodzflg.html

Py:   except ValueError as e:
来源：http://dali.zycfv.cn/Article/details/gtflbggjak.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.hammf.cn/Article/details/gtmompfskw.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhixingplan.top/Article/details/gtrfjzenfd.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jinqigufen.top/Article/details/gtokfdrhbo.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.c1oappe.top/Article/details/gttzdgxawo.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzjszoxhm.html

Ruby: rescue ArgumentError => e
来源：http://dali.xylfe.cn/Article/details/gthzkitmro.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.cucudq.cn/Article/details/gtdgzqenps.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zycfv.cn/Article/details/gtpksjcmhi.html

Py:   value = d.get("k") or default
来源：http://dali.shzxlz.cn/Article/details/gtlamnvuxf.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlymiyuby.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zycfv.cn/Article/details/gtuzwixyem.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.316326.xyz/Article/details/gtcokefzdx.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtixcbfdng.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.cdnleiting.top/Article/details/gtahirfvog.html

Ruby: d&.dig(:a, :b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtneslhmwf.html

C#:   obj?.A?.B ?? default
来源：http://dali.pengpengdd.cyou/Article/details/gtzsyckkkv.html

[H07] 断言
来源：http://dali.havefunace.top/Article/details/gtylmwclxk.html

Py:   assert x > 0, "必须为正"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtocmfylgs.html

PHP:  assert($x > 0);
来源：http://dali.gotoacloud.top/Article/details/gtimyoznmx.html

JS:   console.assert(x > 0);
来源：http://dali.tanke756.top/Article/details/gtdrbsseaf.html

TS:   console.assert(x > 0);
来源：http://dali.tanke756.top/Article/details/gtcslnkzfb.html

Java: assert x > 0 : "必须为正";
来源：http://dali.sweek.top/Article/details/gtexddyimr.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.hnqzz.top/Article/details/gtzdhtsqci.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnrjjghxu.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hywenlv.cn/Article/details/gtldthnffa.html

[H08] 获取错误信息与堆栈
来源：http://dali.jinyuanbaomall.cn/Article/details/gtccgjrcin.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yonumen.top/Article/details/gtswytfvpc.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.aizwys.cn/Article/details/gtsrmopsrf.html

JS:   e.message;  e.stack
来源：http://dali.daxiang520.top/Article/details/gtjzyhvkyd.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.cucudq.cn/Article/details/gtjmbsdlbm.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.nanxinkj.top/Article/details/gttkmvmnjd.html

Go:   err.Error()
来源：http://dali.zhoulong.xyz/Article/details/gtxtpdsqbd.html

Ruby: e.message;  e.backtrace
来源：http://dali.jinqigfzy.top/Article/details/gtjasmcnhj.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yuxming.cn/Article/details/gtbcmqafos.html

[H09] 带错误码的异常
来源：http://dali.hfpthk.cn/Article/details/gtwlpfstpu.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yj20258.top/Article/details/gtmluftpge.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.daria6918.cn/Article/details/gtgkjfsqxe.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.cucudq.cn/Article/details/gtonvucgec.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.sxryk.cn/Article/details/gtwswjlkuw.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.cdnleiting.top/Article/details/gtrdyngzcc.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.gzhubu.top/Article/details/gtyklsmmrz.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yuanzhike.top/Article/details/gtjhxgkmqb.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.guowangkeji.top/Article/details/gtzyeqcqhi.html

[H10] 资源自动释放
来源：http://dali.haohaochexian.top/Article/details/gthszucfui.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.ivvv.top/Article/details/gtnzfpweow.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.xziqi.cn/Article/details/gtchdwmzfi.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xuanzx.com/Article/details/gtgywzbesb.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zycfv.cn/Article/details/gtqifaiuxq.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.pycfn.com/Article/details/gtppemucdw.html

Go:   defer f.Close()
来源：http://dali.ivvv.top/Article/details/gtwfjnltlo.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.cqqwz.cn/Article/details/gtmgdqqjlz.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.chenzaomai.com/Article/details/gtioahyphz.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gthfkpjjvb.html

I. 正则表达式
来源：http://dali.yuxming.cn/Article/details/gtincvqahr.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtmyksmmfo.html

[I01] 判断是否匹配
来源：http://dali.nwbrower.top/Article/details/gtqdawbpcz.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.hnxiangtu.top/Article/details/gtgziifzfj.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.haohaochexian.top/Article/details/gtysntpdtp.html

JS:   /\d+/.test(s)
来源：http://dali.yueranfly.top/Article/details/gtsaacyrla.html

TS:   /\d+/.test(s)
来源：http://dali.zhixingplan.top/Article/details/gtdrmtkehd.html


<!-- 参考信息 -->