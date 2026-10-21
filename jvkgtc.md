代发 wailian999

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.aizwys.cn/Article/details/gtlhllirpc.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.havefunace.top/Article/details/gtzyxkefqf.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gtulmmsjfs.html

C#:   Directory.GetFiles("dir")
来源：http://dali.gzhubu.top/Article/details/gtkbabzmxf.html

[F09] 获取文件大小
来源：http://dali.xziqi.cn/Article/details/gtydstgkzq.html

Py:   os.path.getsize("a.txt")
来源：http://dali.havefunace.top/Article/details/gtwmgojhob.html

PHP:  filesize("a.txt");
来源：http://dali.sweek.top/Article/details/gtbmcwkkdp.html

JS:   fs.statSync("a.txt").size
来源：http://dali.ydzc1.top/Article/details/gtwtxrrlso.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yj20258888.top/Article/details/gtgylcsyyb.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.cheryme.top/Article/details/gtmfpfycaz.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.nanxinkj.top/Article/details/gtxjeexnxj.html

Ruby: File.size("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtiqwcbsxi.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.feifeiyinyue.top/Article/details/gttxuiarzz.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.nanxinkj.top/Article/details/gtlnbotzbb.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtyocngpwi.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.316326.xyz/Article/details/gtiworuodv.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtilvliemg.html

TS:   path.extname("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtuljaetkl.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.cashguo.top/Article/details/gtfgquncqo.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtftsjmsdq.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtsbvzjtat.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtkgrsjclw.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gtqveflzhu.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtheijipum.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.fengsongda.top/Article/details/gtpwuxdssu.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zdqjudy.top/Article/details/gtoyvdzaql.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hnqzz.top/Article/details/gtdsaiehez.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.cheryme.top/Article/details/gtzpcxkner.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.316326.xyz/Article/details/gtqczhpajv.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrkagobug.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.cqqwz.cn/Article/details/gtlgsdcjwr.html

[F12] CSV 读写
来源：http://dali.smart0.xyz/Article/details/gtlezugkfc.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yueranfly.top/Article/details/gtzcvfidvv.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.fzhhl.top/Article/details/gtucktfkhd.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.fzhhl.top/Article/details/gtwymysrwv.html

TS:   // 同上
来源：http://dali.hysaishi.cn/Article/details/gtjsubfpcz.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.snrcjt.cn/Article/details/gtvuhuytxo.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.tian-w.cn/Article/details/gtjuqenrlg.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.meibo888.top/Article/details/gtghwsyrwf.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jinqigufen.top/Article/details/gtngphmvts.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtpoqpsgfz.html

G. 面向对象
来源：http://dali.jianghu66.top/Article/details/gtupzmpwhp.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtlukfpwbi.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gtxejibemg.html

Py:   class User: pass
来源：http://dali.tanke756.top/Article/details/gtyabihmtt.html

PHP:  class User {}
来源：http://dali.hfpthk.cn/Article/details/gtcbwfczns.html

JS:   class User {}
来源：http://dali.ydzc1.top/Article/details/gtbyeotdsj.html

TS:   class User { name: string = ""; }
来源：http://dali.chenjidiqi.icu/Article/details/gtydtabire.html

Java: class User {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtezdgsskh.html

Go:   type User struct { Name string }
来源：http://dali.snrcjt.cn/Article/details/gtjkzfsgdx.html

Ruby: class User; end
来源：http://dali.cucudq.cn/Article/details/gtlygbcacp.html

C#:   class User {}
来源：http://dali.jianghu66.top/Article/details/gtttayoaez.html

[G02] 构造函数
来源：http://dali.nanxuanxn.top/Article/details/gtsogtkgif.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.9152youxi.cn/Article/details/gtimpvlpvn.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.fengsongda.top/Article/details/gtcnmdwhgk.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yj20258888.top/Article/details/gtihiiemth.html

TS:   constructor(public name: string) {}
来源：http://dali.bjfxy.top/Article/details/gtvalwwodr.html

Java: User(String name) { this.name = name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtwwogyzzm.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.wangdashe.top/Article/details/gtdvdcurib.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.aibaodan.cn/Article/details/gtvyspdxsb.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhoulong.xyz/Article/details/gtjwviyacb.html

[G03] 实例属性
来源：http://dali.yj202588.top/Article/details/gtkyyzjtqu.html

Py:   self.name = "x"
来源：http://dali.meibo888.top/Article/details/gtagmzkjcc.html

PHP:  public string $name = "x";
来源：http://dali.shzxlz.cn/Article/details/gtrdlotwyh.html

JS:   this.name = "x";
来源：http://dali.jiagoushi.top/Article/details/gtkzykgmwo.html

TS:   name: string = "x";
来源：http://dali.sxryk.cn/Article/details/gtydsnhfjn.html

Java: private String name;
来源：http://dali.ppjwa.cn/Article/details/gtxluitwee.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.gotoacloud.top/Article/details/gttbdofmsq.html

Ruby: @name = "x"
来源：http://dali.yonumen.top/Article/details/gtwnigpqbz.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.ehwqpu.com/Article/details/gtkiexspfn.html

[G04] 定义方法
来源：http://dali.pycfn.com/Article/details/gtohkuhqja.html

Py:   def greet(self): return self.name
来源：http://dali.iojbl.cn/Article/details/gtbphtvang.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxerkoqhg.html

JS:   greet() { return this.name; }
来源：http://dali.yangfankeji.com/Article/details/gticfjmcun.html

TS:   greet(): string { return this.name; }
来源：http://dali.316326.xyz/Article/details/gtxhxrulhv.html

Java: String greet() { return name; }
来源：http://dali.316326.xyz/Article/details/gtjqyaemkm.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhixingplan.top/Article/details/gtmbageyli.html

Ruby: def greet; @name; end
来源：http://dali.tianlin.xyz/Article/details/gtkveazvcd.html

C#:   public string Greet() => Name;
来源：http://dali.c1oappe.top/Article/details/gtrthdwbhk.html

[G05] 继承
来源：http://dali.jqgfzy.top/Article/details/gtfirwjuxm.html

Py:   class Admin(User): pass
来源：http://dali.ehwqpu.com/Article/details/gttwguomnk.html

PHP:  class Admin extends User {}
来源：http://dali.zycfv.cn/Article/details/gtybzaukuz.html

JS:   class Admin extends User {}
来源：http://dali.sxryk.cn/Article/details/gtfafeakse.html

TS:   class Admin extends User {}
来源：http://dali.ydzc1.top/Article/details/gtbhgahlvf.html

Java: class Admin extends User {}
来源：http://dali.nanxuanxn.top/Article/details/gtlcsryawa.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.shanyushiyangkeji.top/Article/details/gtburiytli.html

Ruby: class Admin < User; end
来源：http://dali.bjfxy.top/Article/details/gtdiowgdev.html

C#:   class Admin : User {}
来源：http://dali.yonumen.top/Article/details/gtkjgfyesx.html

[G06] 重写方法
来源：http://dali.sweek.top/Article/details/gtbazatgfg.html

Py:   def greet(self): return "admin"
来源：http://dali.xziqi.cn/Article/details/gtdgvzrfeu.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.9152youxi.cn/Article/details/gtjiraqsnq.html

JS:   greet() { return "admin"; }
来源：http://dali.pycfn.com/Article/details/gtwikzyffu.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhongyouzk.top/Article/details/gtvbtcejgv.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.shuidangran.top/Article/details/gthrffbmhs.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.fengsongda.top/Article/details/gtsugxemgf.html

Ruby: def greet; "admin"; end
来源：http://dali.tian-w.cn/Article/details/gtiopnnqmb.html

C#:   public override string Greet() => "admin";
来源：http://dali.cdnleiting.top/Article/details/gttszvorlx.html

[G07] 调用父类方法
来源：http://dali.c1oappe.top/Article/details/gtvcinqzok.html

Py:   super().greet()
来源：http://dali.jqgfzy.top/Article/details/gtrnvuqmcw.html

PHP:  parent::greet();
来源：http://dali.havefunace.top/Article/details/gtybwztomc.html

JS:   super.greet();
来源：http://dali.shuidangran.top/Article/details/gteggyejca.html

TS:   super.greet();
来源：http://dali.jqgufenzy.top/Article/details/gtuhdjujsx.html

Java: super.greet();
来源：http://dali.yuanzhike.top/Article/details/gtkvfdfnfp.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.meibo888.top/Article/details/gtebyzqxky.html

Ruby: super
来源：http://dali.zdqjudy.top/Article/details/gtzmrwoqmz.html

C#:   base.Greet();
来源：http://dali.ehwqpu.com/Article/details/gtrdopywrx.html

[G08] 静态方法与属性
来源：http://dali.zhixingplan.top/Article/details/gtfjkjgrak.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.andypj.xyz/Article/details/gtxnhxatcp.html

PHP:  public static function f() {}
来源：http://dali.xylfe.cn/Article/details/gtqaqaxviw.html

JS:   static f() {}
来源：http://dali.zhijiandao.cn/Article/details/gtjwdknhhq.html

TS:   static f(): void {}
来源：http://dali.daxiang520.top/Article/details/gtjotxsyst.html

Java: static void f() {}
来源：http://dali.zhiwuduotai.top/Article/details/gtystetadq.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.xuetiantiany.cn/Article/details/gtibntattz.html

Ruby: def self.f; end
来源：http://dali.hnxiangtu.top/Article/details/gtjhobuljq.html

C#:   public static void F() {}
来源：http://dali.hnqzz.top/Article/details/gtgzsizcxd.html

[G09] 接口 / 抽象类
来源：http://dali.zhengqikj.top/Article/details/gttwtvnyab.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.hongshengwenyu.top/Article/details/gttgtrzkgz.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqjueyuea.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.haohaochexian.top/Article/details/gtuldhnjbw.html

TS:   interface Shape { area(): number; }
来源：http://dali.316326.xyz/Article/details/gtlastyvpm.html

Java: interface Shape { double area(); }
来源：http://dali.nanxuanxn.top/Article/details/gtjaumpmkm.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.redwolf501.top/Article/details/gtidampqol.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.gogol.net.cn/Article/details/gtacifxwfl.html

C#:   interface IShape { double Area(); }
来源：http://dali.hnqzz.top/Article/details/gtpupefdee.html

[G10] 访问控制
来源：http://dali.jqgfzy.top/Article/details/gtoujoarhx.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jlsjyb.cn/Article/details/gtauiaekmf.html

PHP:  public / protected / private
来源：http://dali.fengsongda.top/Article/details/gtetbifquc.html

JS:   #private 字段；其余公开
来源：http://dali.yj202588.top/Article/details/gtyidxgnry.html

TS:   public / protected / private
来源：http://dali.nwbrower.top/Article/details/gtfekybyzo.html

Java: public / protected / private / 默认包级
来源：http://dali.tian-w.cn/Article/details/gtojfoqray.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.tianlin.xyz/Article/details/gtuwambfut.html

Ruby: public / protected / private
来源：http://dali.hongshengwenyu.top/Article/details/gtapgomgnv.html

C#:   public / protected / private / internal
来源：http://dali.0kj1m.cn/Article/details/gtovnvziyh.html

[G11] getter / setter
来源：http://dali.ppjwa.cn/Article/details/gtvylgfphx.html

Py:   @property 与 @x.setter
来源：http://dali.xziqi.cn/Article/details/gteatqejlk.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.9152youxi.cn/Article/details/gtjyzjflnm.html

JS:   get name() { return this._name; }
来源：http://dali.fengsongda.top/Article/details/gtzbhvgtwm.html

TS:   get name(): string { return this._name; }
来源：http://dali.yj20258888.top/Article/details/gtehaploja.html

Java: public String getName() { return name; }
来源：http://dali.bjfxy.top/Article/details/gtthikzxmv.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhiwuduotai.top/Article/details/gtxbrbczny.html

Ruby: attr_accessor :name
来源：http://dali.yanxiufei.cn/Article/details/gtfjsuhbct.html

C#:   public string Name { get; set; }
来源：http://dali.yj202588.top/Article/details/gtmzznsshp.html

[G12] 对象转字符串
来源：http://dali.yuxming.cn/Article/details/gtubksppfm.html

Py:   def __str__(self): return self.name
来源：http://dali.shzxlz.cn/Article/details/gtdmwqqkla.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.pycfn.com/Article/details/gtnwjetdbh.html

JS:   toString() { return this.name; }
来源：http://dali.zhengqikj.top/Article/details/gtwysmcrcx.html

TS:   toString(): string { return this.name; }
来源：http://dali.yanxiufei.cn/Article/details/gtdjlirdvs.html

Java: @Override public String toString() { return name; }
来源：http://dali.zycfv.cn/Article/details/gtwklawdyo.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.wangdashe.top/Article/details/gtweikmnrn.html

Ruby: def to_s; @name; end
来源：http://dali.iojbl.cn/Article/details/gtfxultgjx.html

C#:   public override string ToString() => Name;
来源：http://dali.tianlin.xyz/Article/details/gtixjyimsx.html

[G13] 判断对象类型
来源：http://dali.xuanzx.com/Article/details/gtlzxktdvo.html

Py:   isinstance(u, User)
来源：http://dali.fzhhl.top/Article/details/gtgbwqhgyv.html

PHP:  $u instanceof User
来源：http://dali.cashguo.top/Article/details/gtmpojment.html

JS:   u instanceof User
来源：http://dali.pengpengdd.cyou/Article/details/gtkalatwnj.html

TS:   u instanceof User
来源：http://dali.snrcjt.cn/Article/details/gtyqjolloh.html

Java: u instanceof User
来源：http://dali.tanke756.top/Article/details/gtebebkzbv.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hammf.cn/Article/details/gtuioswiai.html

Ruby: u.is_a?(User)
来源：http://dali.iojbl.cn/Article/details/gticofibjg.html

C#:   u is User
来源：http://dali.jyoumei.cn/Article/details/gtyhrkflvm.html

[G14] 数据类 / record
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsextywrb.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yonumen.top/Article/details/gtihlfcnbh.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hammf.cn/Article/details/gtletpoxiq.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.shuidangran.top/Article/details/gtppdznhqp.html

TS:   type User = { name: string; age: number };
来源：http://dali.mhx1999.top/Article/details/gtvmvfmbka.html

Java: record User(String name, int age) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnspyckpy.html

Go:   type User struct { Name string; Age int }
来源：http://dali.tianlin.xyz/Article/details/gtgwrehrlf.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yuxming.cn/Article/details/gttquxmozl.html

C#:   record User(string Name, int Age);
来源：http://dali.nanxuanxn.top/Article/details/gtigylospa.html

[G15] 枚举
来源：http://dali.316326.xyz/Article/details/gtbyaziada.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.gogol.net.cn/Article/details/gtsyuuvahd.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.sufxvd.cn/Article/details/gtkuadycvh.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.shuidangran.top/Article/details/gtifcllyzn.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hysaishi.cn/Article/details/gtxkodukcq.html

Java: enum Color { RED, GREEN }
来源：http://dali.dashuyun.cn/Article/details/gtnalojppw.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.316326.xyz/Article/details/gttwxxbrxq.html

Ruby: Color = %i[red green].freeze
来源：http://dali.fengsongda.top/Article/details/gtymxwvoud.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gotoacloud.top/Article/details/gtyzwpbxuj.html

[G16] 对象转数组 / 字典
来源：http://dali.bjfxy.top/Article/details/gtoeqvetua.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.daria6918.cn/Article/details/gtgbmgzqtf.html

PHP:  get_object_vars($obj);
来源：http://dali.fzhhl.top/Article/details/gtawosgazf.html

JS:   Object.entries(obj)
来源：http://dali.xuanzx.com/Article/details/gttomsjxeo.html

TS:   Object.entries(obj)
来源：http://dali.daxiang520.top/Article/details/gtujflkavy.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yj20258.top/Article/details/gtexvlnqom.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yongpay.top/Article/details/gtynfodjrj.html

Ruby: obj.instance_variables
来源：http://dali.gotoacloud.top/Article/details/gtosmjusgt.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.sufxvd.cn/Article/details/gtmktwciwj.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtezmgqfxa.html

H. 异常与错误处理
来源：http://dali.sweek.top/Article/details/gtpvahipja.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtkhoyrltw.html

[H01] try / catch 基础
来源：http://dali.tian-w.cn/Article/details/gtzkctgljk.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jiagoushi.top/Article/details/gttuavjuxm.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.nanxuanxn.top/Article/details/gtxhktqqcn.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.wangdashe.top/Article/details/gtnkevajkf.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jinqigufen.top/Article/details/gtndwgikcv.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yongpay.top/Article/details/gtyihyaxse.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.gaohongyu789.top/Article/details/gtunsyefrk.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yvedp.cn/Article/details/gtiakanrkb.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.xziqi.cn/Article/details/gtblebexib.html

[H02] finally / ensure 收尾
来源：http://dali.sxryk.cn/Article/details/gthsqsbmyk.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.316326.xyz/Article/details/gtogtokyni.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.redwolf501.top/Article/details/gtmewhazbk.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.daxiang520.top/Article/details/gtylfxfdkx.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtkuenfnhw.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.nanxinkj.top/Article/details/gtyoisilcb.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.0kj1m.cn/Article/details/gtaebchzkx.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhixingplan.top/Article/details/gtiyoocauh.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.wangdashe.top/Article/details/gtjyvliqtg.html

[H03] 主动抛出异常
来源：http://dali.yuxming.cn/Article/details/gtpozsjvsm.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtchwkealc.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jianghu66.top/Article/details/gtqeszjsho.html

JS:   throw new Error("错误信息");
来源：http://dali.316326.xyz/Article/details/gtweaqxmrj.html

TS:   throw new Error("错误信息");
来源：http://dali.jqgufenzy.top/Article/details/gtkijmxwji.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hnqzz.top/Article/details/gtcearnpma.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.shangyingyoupin.top/Article/details/gtzxjctdou.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.dianchejie.cn/Article/details/gtqxlspasu.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyrgvkfwu.html

[H04] 自定义异常类型
来源：http://dali.yueranfly.top/Article/details/gtqnqpwumv.html

Py:   class MyError(Exception): pass
来源：http://dali.nanxuanxn.top/Article/details/gtltjwjhzs.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.0kj1m.cn/Article/details/gtrvqfwbqv.html

JS:   class MyError extends Error {}
来源：http://dali.yangfankeji.com/Article/details/gtaswsuqkk.html

TS:   class MyError extends Error {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyrrdosdg.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zdqjudy.top/Article/details/gtkghdhhwm.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.cheryme.top/Article/details/gtkondlkfw.html

Ruby: class MyError < StandardError; end
来源：http://dali.daria6918.cn/Article/details/gtveazmbrs.html

C#:   class MyException : Exception {}
来源：http://dali.fzhhl.top/Article/details/gtcgelpvag.html

[H05] 捕获特定类型
来源：http://dali.yonumen.top/Article/details/gtjypopvmd.html

Py:   except ValueError as e:
来源：http://dali.haohaochexian.top/Article/details/gtfptrzwer.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.xylfe.cn/Article/details/gtvkywnkpm.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jlsjyb.cn/Article/details/gtktocxlrx.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.0kj1m.cn/Article/details/gtskklxtaw.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.316326.xyz/Article/details/gtxnwbbcen.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.wangdashe.top/Article/details/gtlzhktfiy.html

Ruby: rescue ArgumentError => e
来源：http://dali.redwolf501.top/Article/details/gtgidjizxs.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdejjixdf.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jlsjyb.cn/Article/details/gtqopcxfyw.html

Py:   value = d.get("k") or default
来源：http://dali.hysaishi.cn/Article/details/gtizfbpnan.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.haohaochexian.top/Article/details/gtdwnvwlup.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqkqtglkr.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.svipenyu.cn/Article/details/gtscsqvmqw.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.gaohongyu789.top/Article/details/gtgyyfivvj.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.nwbrower.top/Article/details/gttqpilxru.html

Ruby: d&.dig(:a, :b)
来源：http://dali.wangdashe.top/Article/details/gtlhqhmvfr.html

C#:   obj?.A?.B ?? default
来源：http://dali.dashuyun.cn/Article/details/gtsmnhkfsr.html

[H07] 断言
来源：http://dali.chenjidiqi.icu/Article/details/gtdzolsykx.html

Py:   assert x > 0, "必须为正"
来源：http://dali.kuanghao11.cn/Article/details/gtlqnxhllz.html

PHP:  assert($x > 0);
来源：http://dali.yongpay.top/Article/details/gtpaoqxejw.html

JS:   console.assert(x > 0);
来源：http://dali.jianghu66.top/Article/details/gtpewzqjeq.html

TS:   console.assert(x > 0);
来源：http://dali.jlsjyb.cn/Article/details/gtmfyvykyd.html

Java: assert x > 0 : "必须为正";
来源：http://dali.sufxvd.cn/Article/details/gtseugobea.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhijiandao.cn/Article/details/gtygeitrvi.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.wangdashe.top/Article/details/gtmwdjhlar.html

C#:   Debug.Assert(x > 0);
来源：http://dali.ydzc1.top/Article/details/gtbenkuksw.html

[H08] 获取错误信息与堆栈
来源：http://dali.cheryme.top/Article/details/gtwuuqzhvm.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jyoumei.cn/Article/details/gtknpuamlr.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yvedp.cn/Article/details/gtmldcprft.html

JS:   e.message;  e.stack
来源：http://dali.hammf.cn/Article/details/gtbzyrubfb.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jiagoushi.top/Article/details/gtlocnvyig.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jinqigfzy.top/Article/details/gtmedixbwo.html

Go:   err.Error()
来源：http://dali.wangdashe.top/Article/details/gtrcmiybju.html

Ruby: e.message;  e.backtrace
来源：http://dali.feifeiyinyue.top/Article/details/gtizggeisj.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jinqigfzy.top/Article/details/gtulxtwlop.html

[H09] 带错误码的异常
来源：http://dali.zhengqikj.top/Article/details/gtgmryukqf.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.ybcxt.top/Article/details/gtbjxdpwcj.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.hongshengwenyu.top/Article/details/gtkyjootye.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.aibaodan.cn/Article/details/gttgchnrwo.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.nwbrower.top/Article/details/gtxjsberwn.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.smart0.xyz/Article/details/gtqvmconbh.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.snrcjt.cn/Article/details/gtxuwdkdrp.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.nanxinkj.top/Article/details/gtjgjcjsqe.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yuxming.cn/Article/details/gtquwgomzc.html

[H10] 资源自动释放
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnfhheuij.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yvedp.cn/Article/details/gtlzwghveq.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jiagoushi.top/Article/details/gtcrqashio.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ehwqpu.com/Article/details/gtqcnqneak.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yangfankeji.com/Article/details/gtzseesupi.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yuxming.cn/Article/details/gtluuxgiio.html

Go:   defer f.Close()
来源：http://dali.wangdashe.top/Article/details/gtewhivwza.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jinqigfzy.top/Article/details/gtlaxfvmpa.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gtetctxgyz.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtugkrbewz.html

I. 正则表达式
来源：http://dali.feifeiyinyue.top/Article/details/gtyjsdwpzc.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtjiluqkij.html

[I01] 判断是否匹配
来源：http://dali.ppjwa.cn/Article/details/gtyavpthgi.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.birdmap.top/Article/details/gtjaxbfuas.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jiagoushi.top/Article/details/gtasmlrpjy.html

JS:   /\d+/.test(s)
来源：http://dali.sysykeji.top/Article/details/gtuoxluwvr.html

TS:   /\d+/.test(s)
来源：http://dali.daxiang520.top/Article/details/gtdpknvpjq.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.feifeiyinyue.top/Article/details/gtqtjaxwdi.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.quarkkingdee.top/Article/details/gtfqlxmguv.html

Ruby: s.match?(/\d+/)
来源：http://dali.tanke756.top/Article/details/gtvhpurwoh.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.tanke756.top/Article/details/gtjpwicsev.html

[I02] 提取所有匹配
来源：http://dali.shzxlz.cn/Article/details/gtwurwstxq.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zycfv.cn/Article/details/gtwzzzbjqa.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.316326.xyz/Article/details/gtjczngpsw.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.haohaochexian.top/Article/details/gtnbrhciaj.html

TS:   s.match(/\d+/g)
来源：http://dali.cheryme.top/Article/details/gtmgsnvexn.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zycfv.cn/Article/details/gtigchpltp.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.wangdashe.top/Article/details/gtjznsxtww.html

Ruby: s.scan(/\d+/)
来源：http://dali.yonumen.top/Article/details/gtstashouu.html


<!-- 参考信息 -->