代发 wailian999

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.pengpengdd.cyou/Article/details/gtrxmwdrrb.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jinqigfzy.top/Article/details/gtfkrgrjya.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.tanke756.top/Article/details/gtioiawjwd.html

[F08] 遍历目录
来源：http://dali.xinyue.icu/Article/details/gtpsikilex.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jqgfzy.top/Article/details/gtzsdjbqpx.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.chenjidiqi.icu/Article/details/gtntefqhrx.html

JS:   fs.readdirSync("dir")
来源：http://dali.gotoacloud.top/Article/details/gtuowhkjrm.html

TS:   fs.readdirSync("dir")
来源：http://dali.haohaochexian.top/Article/details/gtqfazqvbe.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gtizrnwkao.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.hammf.cn/Article/details/gtegzvvthp.html

Ruby: Dir.children("dir")
来源：http://dali.316326.xyz/Article/details/gtlefxchtw.html

C#:   Directory.GetFiles("dir")
来源：http://dali.shzxlz.cn/Article/details/gtmconbnbh.html

[F09] 获取文件大小
来源：http://dali.svipenyu.cn/Article/details/gtofonmtfk.html

Py:   os.path.getsize("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtcribcjjz.html

PHP:  filesize("a.txt");
来源：http://dali.gotoacloud.top/Article/details/gtdermkdwn.html

JS:   fs.statSync("a.txt").size
来源：http://dali.daria6918.cn/Article/details/gthtamouxd.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gtiivndltm.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.hnxiangtu.top/Article/details/gtusdweauv.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.bjfxy.top/Article/details/gtzjwwixtw.html

Ruby: File.size("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtqiobbwih.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jqgfzy.top/Article/details/gthjuielru.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yj202588.top/Article/details/gtiqpmonkz.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yongpay.top/Article/details/gtstoniurg.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.xinyue.icu/Article/details/gtvefygwel.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.bjfxy.top/Article/details/gtknjczipv.html

TS:   path.extname("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtycjbfhet.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.0kj1m.cn/Article/details/gtfkpzhbzb.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yvedp.cn/Article/details/gtqesnestg.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtllyrqcru.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtxwjaybvs.html

[F11] 复制与移动文件
来源：http://dali.yanxiufei.cn/Article/details/gtmdzvgeqd.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.daxiang520.top/Article/details/gtmyowqknh.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtreebyhgm.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sweek.top/Article/details/gteljbprvj.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sweek.top/Article/details/gtilrbiyhj.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zycfv.cn/Article/details/gtyzirthmm.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.iojbl.cn/Article/details/gtrsanwmgx.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.andypj.xyz/Article/details/gtzahllqsw.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.fzhhl.top/Article/details/gtafrqnyeo.html

[F12] CSV 读写
来源：http://dali.wangdashe.top/Article/details/gtlkttmimo.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.shangyingyoupin.top/Article/details/gthzgyfdhh.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.sysykeji.top/Article/details/gtguwayjpg.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jlsjyb.cn/Article/details/gtrrhlrpfq.html

TS:   // 同上
来源：http://dali.zhoulong.xyz/Article/details/gtfrkfdssl.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.quarkkingdee.top/Article/details/gtnovdsxzx.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuhizjonr.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.hfpthk.cn/Article/details/gtozjkthlh.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.smart0.xyz/Article/details/gttuzvcmet.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtulxljmob.html

G. 面向对象
来源：http://dali.sxryk.cn/Article/details/gtplrceltz.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gttjhyygdy.html

[G01] 定义类
来源：http://dali.sufxvd.cn/Article/details/gtgiwzbada.html

Py:   class User: pass
来源：http://dali.zhijiandao.cn/Article/details/gtyuuwkjqp.html

PHP:  class User {}
来源：http://dali.birdmap.top/Article/details/gtcdeltegk.html

JS:   class User {}
来源：http://dali.gogol.net.cn/Article/details/gtzcyfibtx.html

TS:   class User { name: string = ""; }
来源：http://dali.cheryme.top/Article/details/gtjqqmgjiz.html

Java: class User {}
来源：http://dali.gzhubu.top/Article/details/gtxcoxpuse.html

Go:   type User struct { Name string }
来源：http://dali.snrcjt.cn/Article/details/gtezfxrtvy.html

Ruby: class User; end
来源：http://dali.xuanzx.com/Article/details/gtshaihlki.html

C#:   class User {}
来源：http://dali.cashguo.top/Article/details/gtspmraiyz.html

[G02] 构造函数
来源：http://dali.jiagoushi.top/Article/details/gtvlfoyqrt.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.sxryk.cn/Article/details/gtlaqsfxsn.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.snrcjt.cn/Article/details/gtjtqruxpw.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.hysaishi.cn/Article/details/gtysttpkhu.html

TS:   constructor(public name: string) {}
来源：http://dali.redwolf501.top/Article/details/gtjonaxdfm.html

Java: User(String name) { this.name = name; }
来源：http://dali.iojbl.cn/Article/details/gtdbqtcclc.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.redwolf501.top/Article/details/gtezqxqonf.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yongpay.top/Article/details/gtoexfihls.html

C#:   public User(string name) { Name = name; }
来源：http://dali.aizwys.cn/Article/details/gtcixvvrbb.html

[G03] 实例属性
来源：http://dali.wangshuangyany.cn/Article/details/gtmfxgyhgw.html

Py:   self.name = "x"
来源：http://dali.meibo888.top/Article/details/gtkctfrhsx.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gtjmumdwuo.html

JS:   this.name = "x";
来源：http://dali.tian-w.cn/Article/details/gtzjdbkbds.html

TS:   name: string = "x";
来源：http://dali.zhengqikj.top/Article/details/gtawvoynxv.html

Java: private String name;
来源：http://dali.dianchejie.cn/Article/details/gtplgparfi.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hammf.cn/Article/details/gtdsajhold.html

Ruby: @name = "x"
来源：http://dali.cucudq.cn/Article/details/gtondbxglf.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.c1oappe.top/Article/details/gtjnxzzupo.html

[G04] 定义方法
来源：http://dali.feifeiyinyue.top/Article/details/gtxrrvzrjg.html

Py:   def greet(self): return self.name
来源：http://dali.guowangkeji.top/Article/details/gtfsrfobjm.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhoulong.xyz/Article/details/gtvxfyynch.html

JS:   greet() { return this.name; }
来源：http://dali.snrcjt.cn/Article/details/gtymimjddj.html

TS:   greet(): string { return this.name; }
来源：http://dali.ppjwa.cn/Article/details/gtdoakmwpz.html

Java: String greet() { return name; }
来源：http://dali.nanxuanxn.top/Article/details/gtkjaajtfg.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hnqzz.top/Article/details/gtpdkrrama.html

Ruby: def greet; @name; end
来源：http://dali.iojbl.cn/Article/details/gtfaugwbyf.html

C#:   public string Greet() => Name;
来源：http://dali.yj20258888.top/Article/details/gtfqpptkko.html

[G05] 继承
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyimhclmw.html

Py:   class Admin(User): pass
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsqwavnon.html

PHP:  class Admin extends User {}
来源：http://dali.gaohongyu789.top/Article/details/gtifhfgqhk.html

JS:   class Admin extends User {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtygseyvcv.html

TS:   class Admin extends User {}
来源：http://dali.pengpengdd.cyou/Article/details/gtyfkqdvgi.html

Java: class Admin extends User {}
来源：http://dali.xinyue.icu/Article/details/gtsgnlquxe.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jinqigfzy.top/Article/details/gtstykotlv.html

Ruby: class Admin < User; end
来源：http://dali.zhoulong.xyz/Article/details/gtkinnmwyg.html

C#:   class Admin : User {}
来源：http://dali.hongshengwenyu.top/Article/details/gtfrkdiesc.html

[G06] 重写方法
来源：http://dali.yonumen.top/Article/details/gtqicxzipm.html

Py:   def greet(self): return "admin"
来源：http://dali.9152youxi.cn/Article/details/gtrxgqmwag.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jlsjyb.cn/Article/details/gtnvhyiefp.html

JS:   greet() { return "admin"; }
来源：http://dali.hnxiangtu.top/Article/details/gtmdxibobs.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhixingplan.top/Article/details/gtdwbexxkc.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jyoumei.cn/Article/details/gtqchleiiz.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhaomingkeji.xyz/Article/details/gtirdotwpq.html

Ruby: def greet; "admin"; end
来源：http://dali.sxryk.cn/Article/details/gtuymorvbo.html

C#:   public override string Greet() => "admin";
来源：http://dali.guannengcc.top/Article/details/gtmpanqfcc.html

[G07] 调用父类方法
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvqmrqwed.html

Py:   super().greet()
来源：http://dali.ivvv.top/Article/details/gtuukqsqub.html

PHP:  parent::greet();
来源：http://dali.pycfn.com/Article/details/gttlzkbeju.html

JS:   super.greet();
来源：http://dali.cashguo.top/Article/details/gtezupdpki.html

TS:   super.greet();
来源：http://dali.quarkkingdee.top/Article/details/gtxtvveral.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gtwpejysgl.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.birdmap.top/Article/details/gtbixpyuqr.html

Ruby: super
来源：http://dali.shangyingyoupin.top/Article/details/gtgekqkchq.html

C#:   base.Greet();
来源：http://dali.xziqi.cn/Article/details/gtqdqhxxbd.html

[G08] 静态方法与属性
来源：http://dali.jinqigfzy.top/Article/details/gtxbizmppc.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.0kj1m.cn/Article/details/gtthdpcrhe.html

PHP:  public static function f() {}
来源：http://dali.iojbl.cn/Article/details/gtxyiznbzk.html

JS:   static f() {}
来源：http://dali.daxiang520.top/Article/details/gtnnvusylu.html

TS:   static f(): void {}
来源：http://dali.shangyingyoupin.top/Article/details/gtqhiecbcl.html

Java: static void f() {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfnsfeyem.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.tian-w.cn/Article/details/gtgekualyw.html

Ruby: def self.f; end
来源：http://dali.gogol.net.cn/Article/details/gthdfknpef.html

C#:   public static void F() {}
来源：http://dali.zhengqikj.top/Article/details/gtfleiuwxt.html

[G09] 接口 / 抽象类
来源：http://dali.nwbrower.top/Article/details/gtalgoigjo.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhongyouzk.top/Article/details/gtwaetiomg.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhoulong.xyz/Article/details/gtwuissnki.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jiagoushi.top/Article/details/gtdeazazzq.html

TS:   interface Shape { area(): number; }
来源：http://dali.zdqjudy.top/Article/details/gtjqdqbaxx.html

Java: interface Shape { double area(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtxeqxneiv.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jqgfzy.top/Article/details/gtnpuilnof.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.fzhhl.top/Article/details/gtivfvlkeo.html

C#:   interface IShape { double Area(); }
来源：http://dali.fzhhl.top/Article/details/gtduyunkkj.html

[G10] 访问控制
来源：http://dali.wangshuangyany.cn/Article/details/gtozwkrxzw.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.iojbl.cn/Article/details/gtvyyqlcaj.html

PHP:  public / protected / private
来源：http://dali.jiagoushi.top/Article/details/gtbbzqhvzk.html

JS:   #private 字段；其余公开
来源：http://dali.nwbrower.top/Article/details/gtkrdugxxp.html

TS:   public / protected / private
来源：http://dali.gzhubu.top/Article/details/gtefykdmhw.html

Java: public / protected / private / 默认包级
来源：http://dali.gzhubu.top/Article/details/gtiaqgwzun.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.vqdsnc.cn/Article/details/gtgqshndup.html

Ruby: public / protected / private
来源：http://dali.zhixingplan.top/Article/details/gtxqoknzaq.html

C#:   public / protected / private / internal
来源：http://dali.tian-w.cn/Article/details/gtfxzmzcsd.html

[G11] getter / setter
来源：http://dali.gogol.net.cn/Article/details/gtawhyrnty.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gthdjxeqzn.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhoulong.xyz/Article/details/gtndejiqrq.html

JS:   get name() { return this._name; }
来源：http://dali.snrcjt.cn/Article/details/gtqhquzwab.html

TS:   get name(): string { return this._name; }
来源：http://dali.hfpthk.cn/Article/details/gtitsvsmxf.html

Java: public String getName() { return name; }
来源：http://dali.sysykeji.top/Article/details/gtfgtsfmbh.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.chenlongwang.top/Article/details/gtwtwusyjw.html

Ruby: attr_accessor :name
来源：http://dali.yonumen.top/Article/details/gthfdhcstm.html

C#:   public string Name { get; set; }
来源：http://dali.sufxvd.cn/Article/details/gtexenwygv.html

[G12] 对象转字符串
来源：http://dali.xylfe.cn/Article/details/gtnjciyutb.html

Py:   def __str__(self): return self.name
来源：http://dali.andypj.xyz/Article/details/gtzpalyljv.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.pycfn.com/Article/details/gtekeuglyh.html

JS:   toString() { return this.name; }
来源：http://dali.xziqi.cn/Article/details/gtyksuswzd.html

TS:   toString(): string { return this.name; }
来源：http://dali.smart0.xyz/Article/details/gtidxjskdh.html

Java: @Override public String toString() { return name; }
来源：http://dali.cqqwz.cn/Article/details/gtfgigxzet.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.sysykeji.top/Article/details/gtlqqfumym.html

Ruby: def to_s; @name; end
来源：http://dali.chenzaomai.com/Article/details/gtefaibaij.html

C#:   public override string ToString() => Name;
来源：http://dali.yvedp.cn/Article/details/gtaxukftjm.html

[G13] 判断对象类型
来源：http://dali.hnxiangtu.top/Article/details/gtbpkylnfy.html

Py:   isinstance(u, User)
来源：http://dali.cheryme.top/Article/details/gtodnkusdb.html

PHP:  $u instanceof User
来源：http://dali.nwbrower.top/Article/details/gtcecdfzqm.html

JS:   u instanceof User
来源：http://dali.xziqi.cn/Article/details/gtefruboif.html

TS:   u instanceof User
来源：http://dali.feifeiyinyue.top/Article/details/gtuyvsnxdn.html

Java: u instanceof User
来源：http://dali.yj20258.top/Article/details/gtmkrydnyy.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yj20258.top/Article/details/gtxttfvoyc.html

Ruby: u.is_a?(User)
来源：http://dali.tanke756.top/Article/details/gttagoiknf.html

C#:   u is User
来源：http://dali.smart0.xyz/Article/details/gthokflzns.html

[G14] 数据类 / record
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvecokgan.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.chenjidiqi.icu/Article/details/gtablovtwr.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.0kj1m.cn/Article/details/gtrnnkvxdw.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.sweek.top/Article/details/gtfpmifcju.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhoulong.xyz/Article/details/gtdmwkxesg.html

Java: record User(String name, int age) {}
来源：http://dali.fzhhl.top/Article/details/gtauweyeko.html

Go:   type User struct { Name string; Age int }
来源：http://dali.quarkkingdee.top/Article/details/gtbgrqyhkd.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.haohaochexian.top/Article/details/gtjexaeelv.html

C#:   record User(string Name, int Age);
来源：http://dali.xuetiantiany.cn/Article/details/gtlivwzsjk.html

[G15] 枚举
来源：http://dali.birdmap.top/Article/details/gtnykxrzxa.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxqulkmkf.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.svipenyu.cn/Article/details/gtdzcvgzok.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yongpay.top/Article/details/gtobymzihw.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.vqdsnc.cn/Article/details/gtlvvxjhmz.html

Java: enum Color { RED, GREEN }
来源：http://dali.smart0.xyz/Article/details/gtprxfswdr.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.smart0.xyz/Article/details/gtimduvpqd.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yuanzhike.top/Article/details/gtvzoengnx.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhongyouzk.top/Article/details/gtdnhqeayd.html

[G16] 对象转数组 / 字典
来源：http://dali.tianlin.xyz/Article/details/gtmiirvklh.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yongpay.top/Article/details/gtrkpmgbwi.html

PHP:  get_object_vars($obj);
来源：http://dali.9152youxi.cn/Article/details/gtcsecekbk.html

JS:   Object.entries(obj)
来源：http://dali.snrcjt.cn/Article/details/gtvapvoyii.html

TS:   Object.entries(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtykpabauh.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.feifeiyinyue.top/Article/details/gtnirxmpkc.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jyoumei.cn/Article/details/gtazuyixkx.html

Ruby: obj.instance_variables
来源：http://dali.daria6918.cn/Article/details/gttwdjqkws.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuthgfxkz.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtxhrhllyb.html

H. 异常与错误处理
来源：http://dali.cdnleiting.top/Article/details/gthimopitc.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtstlidkft.html

[H01] try / catch 基础
来源：http://dali.xuanzx.com/Article/details/gtgyvhydyn.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.cqqwz.cn/Article/details/gtcdyfibhj.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtkyquilsc.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.xinyue.icu/Article/details/gtwqswrity.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhiwuduotai.top/Article/details/gtbdiatqdf.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.svipenyu.cn/Article/details/gtfdixvipp.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.guannengcc.top/Article/details/gtckylfbmq.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.sweek.top/Article/details/gtpvdzwiko.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhongyouzk.top/Article/details/gtsdzcxtuu.html

[H02] finally / ensure 收尾
来源：http://dali.jinyuanbaomall.cn/Article/details/gteeqhqgbm.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhengqikj.top/Article/details/gtmigcizhy.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.chenlongwang.top/Article/details/gtlmkhvmpl.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yvedp.cn/Article/details/gtnzyudoot.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.guowangkeji.top/Article/details/gtbkpblbvc.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jiagoushi.top/Article/details/gtxcvjvqmy.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.sxryk.cn/Article/details/gtlyrdodzr.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jlsjyb.cn/Article/details/gtblfjrjqg.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.xylfe.cn/Article/details/gtheqahcho.html

[H03] 主动抛出异常
来源：http://dali.xuanzx.com/Article/details/gtktrtpykk.html

Py:   raise ValueError("错误信息")
来源：http://dali.sweek.top/Article/details/gtbnkefgnj.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.cdnleiting.top/Article/details/gtlmqnvtln.html

JS:   throw new Error("错误信息");
来源：http://dali.ydzc1.top/Article/details/gtlhmmaskk.html

TS:   throw new Error("错误信息");
来源：http://dali.yongpay.top/Article/details/gtwxjsrjls.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yongpay.top/Article/details/gtkchcymfw.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jinqigfzy.top/Article/details/gtsnevyfvi.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.haohaochexian.top/Article/details/gthlptmmne.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jlsjyb.cn/Article/details/gtjcvbxjad.html

[H04] 自定义异常类型
来源：http://dali.yuxming.cn/Article/details/gtqclrlbge.html

Py:   class MyError(Exception): pass
来源：http://dali.shzxlz.cn/Article/details/gtrdnjzfui.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yanxiufei.cn/Article/details/gteeqqywgv.html

JS:   class MyError extends Error {}
来源：http://dali.daxiang520.top/Article/details/gtzbpakdcr.html

TS:   class MyError extends Error {}
来源：http://dali.smart0.xyz/Article/details/gtpgjatzzh.html

Java: class MyException extends RuntimeException {}
来源：http://dali.smart0.xyz/Article/details/gtzjadhrdv.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.sweek.top/Article/details/gttbtwzawi.html

Ruby: class MyError < StandardError; end
来源：http://dali.jianghu66.top/Article/details/gtcxkoxbnw.html

C#:   class MyException : Exception {}
来源：http://dali.xziqi.cn/Article/details/gtknjxisrn.html

[H05] 捕获特定类型
来源：http://dali.redwolf501.top/Article/details/gtoxnsdgxw.html

Py:   except ValueError as e:
来源：http://dali.dashuyun.cn/Article/details/gtkauyotri.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.ivvv.top/Article/details/gtaeubwphi.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtaelkwvhe.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.sysykeji.top/Article/details/gteqhtlplf.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtzaxfxeus.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.tian-w.cn/Article/details/gtgylubtdv.html

Ruby: rescue ArgumentError => e
来源：http://dali.xylfe.cn/Article/details/gtdbcaiztc.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.0kj1m.cn/Article/details/gtpysjvurk.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jqgufenzy.top/Article/details/gtrnhexygs.html

Py:   value = d.get("k") or default
来源：http://dali.gotoacloud.top/Article/details/gtpvsfnyrq.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhiwuduotai.top/Article/details/gtrslsdjnn.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.ehwqpu.com/Article/details/gthihzhixo.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.haohaochexian.top/Article/details/gtehdrtkow.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.chenlongwang.top/Article/details/gtayuqachl.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.cdnleiting.top/Article/details/gtckrraobu.html

Ruby: d&.dig(:a, :b)
来源：http://dali.sxryk.cn/Article/details/gtmkklbhjn.html

C#:   obj?.A?.B ?? default
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpcdfamhg.html

[H07] 断言
来源：http://dali.nwbrower.top/Article/details/gtrthibpns.html

Py:   assert x > 0, "必须为正"
来源：http://dali.shzxlz.cn/Article/details/gtwqdnrlya.html

PHP:  assert($x > 0);
来源：http://dali.hongshengwenyu.top/Article/details/gtyxfgwosj.html

JS:   console.assert(x > 0);
来源：http://dali.yangfankeji.com/Article/details/gtpjpghmnd.html

TS:   console.assert(x > 0);
来源：http://dali.fengsongda.top/Article/details/gtiqxqdacn.html

Java: assert x > 0 : "必须为正";
来源：http://dali.gogol.net.cn/Article/details/gtlghnqvia.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.hfpthk.cn/Article/details/gtdqspclzy.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.dashuyun.cn/Article/details/gtrywhafye.html

C#:   Debug.Assert(x > 0);
来源：http://dali.guowangkeji.top/Article/details/gthobcqijd.html

[H08] 获取错误信息与堆栈
来源：http://dali.jqgufenzy.top/Article/details/gtzuonrwzx.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jlsjyb.cn/Article/details/gtcinraefp.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hfpthk.cn/Article/details/gtybloxmbs.html

JS:   e.message;  e.stack
来源：http://dali.aibaodan.cn/Article/details/gttznvinel.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnpmtzymb.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.snrcjt.cn/Article/details/gtbgrnkjez.html

Go:   err.Error()
来源：http://dali.zhiwuduotai.top/Article/details/gttznmvvty.html

Ruby: e.message;  e.backtrace
来源：http://dali.pycfn.com/Article/details/gtfrtnscnd.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkxbrxovd.html

[H09] 带错误码的异常
来源：http://dali.yuxming.cn/Article/details/gtrgyszkeh.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yuanzhike.top/Article/details/gtarnhqewk.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.dianchejie.cn/Article/details/gtjalepmlu.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.dashuyun.cn/Article/details/gtvhudfqpn.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jinqigfzy.top/Article/details/gtcamokcqm.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.shuidangran.top/Article/details/gtbvitwevp.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.mhx1999.top/Article/details/gtrfkynkcu.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.sysykeji.top/Article/details/gtesrapekq.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.cucudq.cn/Article/details/gtpducstsq.html

[H10] 资源自动释放
来源：http://dali.wangdashe.top/Article/details/gtkbvubfeh.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.316326.xyz/Article/details/gtlmnxdpse.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.dashuyun.cn/Article/details/gtzgwdkvjy.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.havefunace.top/Article/details/gtiswhcdhy.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yj20258888.top/Article/details/gtrycagnej.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.birdmap.top/Article/details/gtscgbdyyi.html

Go:   defer f.Close()
来源：http://dali.tianlin.xyz/Article/details/gtxcmdgrha.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.shuidangran.top/Article/details/gtslexqapc.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.iojbl.cn/Article/details/gtqruyssbh.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqaupvwrv.html

I. 正则表达式
来源：http://dali.jianghu66.top/Article/details/gttmxqavla.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtlrrputty.html

[I01] 判断是否匹配
来源：http://dali.hammf.cn/Article/details/gtvcxkutnx.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.cucudq.cn/Article/details/gtenylsykx.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jqgfzy.top/Article/details/gtinhdjpcb.html

JS:   /\d+/.test(s)
来源：http://dali.cqqwz.cn/Article/details/gtpajsafnk.html

TS:   /\d+/.test(s)
来源：http://dali.yongpay.top/Article/details/gtfwceqoid.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jiagoushi.top/Article/details/gtxuojsayu.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.xylfe.cn/Article/details/gtlrellqza.html

Ruby: s.match?(/\d+/)
来源：http://dali.ehwqpu.com/Article/details/gtnexvrbnb.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.wangdashe.top/Article/details/gtxpexdxya.html


<!-- 参考信息 -->