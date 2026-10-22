代发 wailian999

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.snrcjt.cn/Article/details/gtehhldcxd.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yvedp.cn/Article/details/gtjrpksngy.html

Ruby: Dir.children("dir")
来源：http://dali.aizwys.cn/Article/details/gtbsgdcplp.html

C#:   Directory.GetFiles("dir")
来源：http://dali.sweek.top/Article/details/gtzbcbyeim.html

[F09] 获取文件大小
来源：http://dali.redwolf501.top/Article/details/gtfltlyfee.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtbtdhoqly.html

PHP:  filesize("a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gtjjxoczto.html

JS:   fs.statSync("a.txt").size
来源：http://dali.ivvv.top/Article/details/gthkeeckkv.html

TS:   fs.statSync("a.txt").size
来源：http://dali.tianlin.xyz/Article/details/gtsdsdaqxg.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.redwolf501.top/Article/details/gtbxfmycnu.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.sufxvd.cn/Article/details/gtnfmzckhc.html

Ruby: File.size("a.txt")
来源：http://dali.hammf.cn/Article/details/gtmmxcghhc.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.andypj.xyz/Article/details/gtvinxbkji.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jianghu66.top/Article/details/gtjtwrwexz.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtlxniqfdt.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.chenzaomai.com/Article/details/gtpardlebc.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.shuidangran.top/Article/details/gtrgjkjtdx.html

TS:   path.extname("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtynyjydbc.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.xuanzx.com/Article/details/gtcylkcavz.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.guannengcc.top/Article/details/gtzxzgghfe.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yvedp.cn/Article/details/gtkwyypqfv.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtqzcisvpa.html

[F11] 复制与移动文件
来源：http://dali.ehwqpu.com/Article/details/gttxnfhyfd.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.ydzc1.top/Article/details/gtgjyknqgu.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zycfv.cn/Article/details/gtvkpgmayf.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.birdmap.top/Article/details/gtetfxgqdz.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.aibaodan.cn/Article/details/gtivricfvu.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.birdmap.top/Article/details/gtokjzqbdr.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcocqitff.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.gotoacloud.top/Article/details/gtptccdoct.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbmoxiknh.html

[F12] CSV 读写
来源：http://dali.zdqjudy.top/Article/details/gtdliqqnum.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.daria6918.cn/Article/details/gtdamgsjws.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hfpthk.cn/Article/details/gttuxtafwv.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.shanyushiyangkeji.top/Article/details/gtncuesoan.html

TS:   // 同上
来源：http://dali.sweek.top/Article/details/gtihaexmob.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.vqdsnc.cn/Article/details/gtvraoxbah.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yanxiufei.cn/Article/details/gtfopoanjl.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.shangyingyoupin.top/Article/details/gtvkvdsxuy.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhengqikj.top/Article/details/gtsakmcxex.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtholjeury.html

G. 面向对象
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbkpyryzg.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtzugkaoyb.html

[G01] 定义类
来源：http://dali.feifeiyinyue.top/Article/details/gthmzqvpka.html

Py:   class User: pass
来源：http://dali.hfpthk.cn/Article/details/gtnfnakhij.html

PHP:  class User {}
来源：http://dali.aizwys.cn/Article/details/gthgobtggr.html

JS:   class User {}
来源：http://dali.pengpengdd.cyou/Article/details/gtxzlihqzo.html

TS:   class User { name: string = ""; }
来源：http://dali.yj20258888.top/Article/details/gtdeyiuiht.html

Java: class User {}
来源：http://dali.cdnleiting.top/Article/details/gtvwbczfzg.html

Go:   type User struct { Name string }
来源：http://dali.daxiang520.top/Article/details/gtedjjbytg.html

Ruby: class User; end
来源：http://dali.daxiang520.top/Article/details/gtyfwusuvt.html

C#:   class User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwualsihl.html

[G02] 构造函数
来源：http://dali.aizwys.cn/Article/details/gtafwyeuka.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.hammf.cn/Article/details/gtqhcgdbzl.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.ehwqpu.com/Article/details/gtbdsookbb.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.aizwys.cn/Article/details/gtwhvzsusf.html

TS:   constructor(public name: string) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtnfdiflwy.html

Java: User(String name) { this.name = name; }
来源：http://dali.fengsongda.top/Article/details/gtgmyvxrmr.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.shzxlz.cn/Article/details/gtepaeqpxu.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.xuanzx.com/Article/details/gtgrhgnbjq.html

C#:   public User(string name) { Name = name; }
来源：http://dali.chenzaomai.com/Article/details/gtwlmmgfay.html

[G03] 实例属性
来源：http://dali.snrcjt.cn/Article/details/gtrmsuldao.html

Py:   self.name = "x"
来源：http://dali.zycfv.cn/Article/details/gtkewsvshf.html

PHP:  public string $name = "x";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjfyfrbwh.html

JS:   this.name = "x";
来源：http://dali.shangyingyoupin.top/Article/details/gtjgxnfbfy.html

TS:   name: string = "x";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjzxvpuin.html

Java: private String name;
来源：http://dali.jiagoushi.top/Article/details/gtnjdxhgpw.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zdqjudy.top/Article/details/gtjnwfxafa.html

Ruby: @name = "x"
来源：http://dali.sweek.top/Article/details/gtaqytyjno.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.vqdsnc.cn/Article/details/gtzpuczgxa.html

[G04] 定义方法
来源：http://dali.sysykeji.top/Article/details/gtjmkqqzoj.html

Py:   def greet(self): return self.name
来源：http://dali.c1oappe.top/Article/details/gtbvcjsuxv.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.haohaochexian.top/Article/details/gtlxkubwib.html

JS:   greet() { return this.name; }
来源：http://dali.quarkkingdee.top/Article/details/gtarsmgxoe.html

TS:   greet(): string { return this.name; }
来源：http://dali.ehwqpu.com/Article/details/gtnqxoumjm.html

Java: String greet() { return name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgksisczg.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtahoabwat.html

Ruby: def greet; @name; end
来源：http://dali.jinghuilouyu.cn/Article/details/gtkbipxqpx.html

C#:   public string Greet() => Name;
来源：http://dali.andypj.xyz/Article/details/gtuzfxboro.html

[G05] 继承
来源：http://dali.cucudq.cn/Article/details/gtuwzdyrat.html

Py:   class Admin(User): pass
来源：http://dali.hammf.cn/Article/details/gtbsltiumw.html

PHP:  class Admin extends User {}
来源：http://dali.ydzc1.top/Article/details/gtrtfahxeb.html

JS:   class Admin extends User {}
来源：http://dali.yj20258888.top/Article/details/gtwguvcdtk.html

TS:   class Admin extends User {}
来源：http://dali.yangfankeji.com/Article/details/gtishlhkhh.html

Java: class Admin extends User {}
来源：http://dali.shzxlz.cn/Article/details/gtgyfoycup.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.guowangkeji.top/Article/details/gtnnuxdbdl.html

Ruby: class Admin < User; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsazvqcds.html

C#:   class Admin : User {}
来源：http://dali.dianchejie.cn/Article/details/gtaeqiscfz.html

[G06] 重写方法
来源：http://dali.shzxlz.cn/Article/details/gtvlzivpsz.html

Py:   def greet(self): return "admin"
来源：http://dali.jianghu66.top/Article/details/gtaiqgkyaw.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.quarkkingdee.top/Article/details/gtqguuyuqb.html

JS:   greet() { return "admin"; }
来源：http://dali.gotoacloud.top/Article/details/gtlefplccj.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hammf.cn/Article/details/gtmunxvjzx.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yj20258.top/Article/details/gteirppvwm.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.chenjidiqi.icu/Article/details/gtxdplcctm.html

Ruby: def greet; "admin"; end
来源：http://dali.yanxiufei.cn/Article/details/gtqzvatdmy.html

C#:   public override string Greet() => "admin";
来源：http://dali.ivvv.top/Article/details/gtxnbaadld.html

[G07] 调用父类方法
来源：http://dali.zhixingplan.top/Article/details/gtndfwtpqo.html

Py:   super().greet()
来源：http://dali.ivvv.top/Article/details/gtyiqrvmsz.html

PHP:  parent::greet();
来源：http://dali.daria6918.cn/Article/details/gtsrpysiad.html

JS:   super.greet();
来源：http://dali.jlsjyb.cn/Article/details/gthsgslaso.html

TS:   super.greet();
来源：http://dali.redwolf501.top/Article/details/gtwfssecwf.html

Java: super.greet();
来源：http://dali.gotoacloud.top/Article/details/gtnkmaunqn.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.cheryme.top/Article/details/gtamolizgv.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gttokowyji.html

C#:   base.Greet();
来源：http://dali.wangshuangyany.cn/Article/details/gtacpeeheb.html

[G08] 静态方法与属性
来源：http://dali.gzhubu.top/Article/details/gtmzqrwrfk.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xziqi.cn/Article/details/gtjwknunxn.html

PHP:  public static function f() {}
来源：http://dali.zhengqikj.top/Article/details/gtvmdcyysh.html

JS:   static f() {}
来源：http://dali.xuetiantiany.cn/Article/details/gtyjkwmmsc.html

TS:   static f(): void {}
来源：http://dali.xziqi.cn/Article/details/gttiyhmjpg.html

Java: static void f() {}
来源：http://dali.zhiwuduotai.top/Article/details/gtsmdjmiww.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.quarkkingdee.top/Article/details/gttyaefztv.html

Ruby: def self.f; end
来源：http://dali.aibaodan.cn/Article/details/gtlecialti.html

C#:   public static void F() {}
来源：http://dali.smart0.xyz/Article/details/gtzkzjfzqe.html

[G09] 接口 / 抽象类
来源：http://dali.iojbl.cn/Article/details/gtebtfqgca.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.hnxiangtu.top/Article/details/gtrtjfewkw.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.pengpengdd.cyou/Article/details/gtkorsygsp.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yongpay.top/Article/details/gtafykxuoq.html

TS:   interface Shape { area(): number; }
来源：http://dali.shzxlz.cn/Article/details/gtkaajezrf.html

Java: interface Shape { double area(); }
来源：http://dali.cashguo.top/Article/details/gtedtfjaqj.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.sweek.top/Article/details/gtmbtaeosq.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.cucudq.cn/Article/details/gtkbopsomz.html

C#:   interface IShape { double Area(); }
来源：http://dali.andypj.xyz/Article/details/gtroacnovm.html

[G10] 访问控制
来源：http://dali.dashuyun.cn/Article/details/gtrcxkdrdc.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.iojbl.cn/Article/details/gtprdouyyv.html

PHP:  public / protected / private
来源：http://dali.jiagoushi.top/Article/details/gtreiyecyh.html

JS:   #private 字段；其余公开
来源：http://dali.c1oappe.top/Article/details/gtpzntntoy.html

TS:   public / protected / private
来源：http://dali.yangfankeji.com/Article/details/gttgkujatn.html

Java: public / protected / private / 默认包级
来源：http://dali.shanyushiyangtech.top/Article/details/gtoswzyhfv.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hysaishi.cn/Article/details/gtasuqsodv.html

Ruby: public / protected / private
来源：http://dali.cdnleiting.top/Article/details/gtmbpedpoo.html

C#:   public / protected / private / internal
来源：http://dali.chenjidiqi.icu/Article/details/gtsldsraug.html

[G11] getter / setter
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjepdqdmt.html

Py:   @property 与 @x.setter
来源：http://dali.redwolf501.top/Article/details/gtqyfisirz.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.birdmap.top/Article/details/gtgaqgdgno.html

JS:   get name() { return this._name; }
来源：http://dali.jiagoushi.top/Article/details/gtsuqwltpw.html

TS:   get name(): string { return this._name; }
来源：http://dali.sufxvd.cn/Article/details/gtbxkedxio.html

Java: public String getName() { return name; }
来源：http://dali.meibo888.top/Article/details/gtuczanmet.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jinyuanbaomall.cn/Article/details/gttvmswmys.html

Ruby: attr_accessor :name
来源：http://dali.yangfankeji.com/Article/details/gthcgeziyw.html

C#:   public string Name { get; set; }
来源：http://dali.jqgfzy.top/Article/details/gtqxneyzfv.html

[G12] 对象转字符串
来源：http://dali.havefunace.top/Article/details/gtiyifihdz.html

Py:   def __str__(self): return self.name
来源：http://dali.svipenyu.cn/Article/details/gtpmnxamal.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.svipenyu.cn/Article/details/gtupudhfla.html

JS:   toString() { return this.name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtgftsuvng.html

TS:   toString(): string { return this.name; }
来源：http://dali.jianghu66.top/Article/details/gtjqguawdq.html

Java: @Override public String toString() { return name; }
来源：http://dali.kuanghao11.cn/Article/details/gtdsujlnqt.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jqgufenzy.top/Article/details/gtvtaufzog.html

Ruby: def to_s; @name; end
来源：http://dali.tanke756.top/Article/details/gtatxrnqyb.html

C#:   public override string ToString() => Name;
来源：http://dali.xinyue.icu/Article/details/gtwtiflgfi.html

[G13] 判断对象类型
来源：http://dali.pengpengdd.cyou/Article/details/gtzvvzwywd.html

Py:   isinstance(u, User)
来源：http://dali.zycfv.cn/Article/details/gtvyceekls.html

PHP:  $u instanceof User
来源：http://dali.shangyingyoupin.top/Article/details/gtnteehqko.html

JS:   u instanceof User
来源：http://dali.smart0.xyz/Article/details/gtorayszvh.html

TS:   u instanceof User
来源：http://dali.9152youxi.cn/Article/details/gtwehhcurk.html

Java: u instanceof User
来源：http://dali.jinqigfzy.top/Article/details/gtbgyxunlm.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.xylfe.cn/Article/details/gtrvlnfrbg.html

Ruby: u.is_a?(User)
来源：http://dali.316326.xyz/Article/details/gtfzxtmhkf.html

C#:   u is User
来源：http://dali.guowangkeji.top/Article/details/gtkambuhkz.html

[G14] 数据类 / record
来源：http://dali.c1oappe.top/Article/details/gtdxopppya.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.kuanghao11.cn/Article/details/gtocsphpbd.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.xuanzx.com/Article/details/gtsdpubjea.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yongpay.top/Article/details/gtvomjgupu.html

TS:   type User = { name: string; age: number };
来源：http://dali.yongpay.top/Article/details/gtygstuqlu.html

Java: record User(String name, int age) {}
来源：http://dali.yj20258.top/Article/details/gtspznvvua.html

Go:   type User struct { Name string; Age int }
来源：http://dali.gzhubu.top/Article/details/gtsowqaeov.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.guannengcc.top/Article/details/gtkxvwgrwb.html

C#:   record User(string Name, int Age);
来源：http://dali.haohaochexian.top/Article/details/gtsdnelrqh.html

[G15] 枚举
来源：http://dali.vqdsnc.cn/Article/details/gtlvjvunzo.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hongshengwenyu.top/Article/details/gtiipgpvmh.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.c1oappe.top/Article/details/gtwnjzyjpa.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.dianchejie.cn/Article/details/gthbaywkoj.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cucudq.cn/Article/details/gtmusrasin.html

Java: enum Color { RED, GREEN }
来源：http://dali.ybcxt.top/Article/details/gtrdrlxatm.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhoulong.xyz/Article/details/gtcwcntjtg.html

Ruby: Color = %i[red green].freeze
来源：http://dali.hywenlv.cn/Article/details/gtzyvthczt.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhongyouzk.top/Article/details/gtvaosjfuz.html

[G16] 对象转数组 / 字典
来源：http://dali.daxiang520.top/Article/details/gtxvasfymx.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.dianchejie.cn/Article/details/gtjnjpwler.html

PHP:  get_object_vars($obj);
来源：http://dali.dashuyun.cn/Article/details/gtsyfdwxbl.html

JS:   Object.entries(obj)
来源：http://dali.jinqigufen.top/Article/details/gtuzccerdp.html

TS:   Object.entries(obj)
来源：http://dali.xinyue.icu/Article/details/gtetyfvirl.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.bjfxy.top/Article/details/gtkpxzgyyx.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.cdnleiting.top/Article/details/gtypxdydii.html

Ruby: obj.instance_variables
来源：http://dali.c1oappe.top/Article/details/gtijefyjxk.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.fengsongda.top/Article/details/gtzsnqporo.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtfeqecqoc.html

H. 异常与错误处理
来源：http://dali.nanxinkj.top/Article/details/gtxazctllh.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmewesjab.html

[H01] try / catch 基础
来源：http://dali.jlsjyb.cn/Article/details/gtyckilqdi.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yvedp.cn/Article/details/gtlfbffxfm.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.svipenyu.cn/Article/details/gtrbnwsvzl.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.tanke756.top/Article/details/gtrdhajuxr.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.andypj.xyz/Article/details/gthoyrrozn.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.pycfn.com/Article/details/gtkrrlywcx.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hywenlv.cn/Article/details/gtbrrxubuy.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.havefunace.top/Article/details/gtujvmdlmx.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yvedp.cn/Article/details/gtarbvmlko.html

[H02] finally / ensure 收尾
来源：http://dali.gaohongyu789.top/Article/details/gtgyxqagnv.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.snrcjt.cn/Article/details/gtclzquboq.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.pengpengdd.cyou/Article/details/gtpohcdfda.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.iojbl.cn/Article/details/gtipyiljar.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.sxryk.cn/Article/details/gtjhulxppe.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.sufxvd.cn/Article/details/gtgaacpsnm.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hnqzz.top/Article/details/gtjppbgzla.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jinqigufen.top/Article/details/gtezxjqsir.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.dianchejie.cn/Article/details/gtkbprlqhv.html

[H03] 主动抛出异常
来源：http://dali.zdqjudy.top/Article/details/gtcooqkide.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gtzcnbozci.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.vqdsnc.cn/Article/details/gthsjsycuu.html

JS:   throw new Error("错误信息");
来源：http://dali.yj202588.top/Article/details/gtmyhybtwv.html

TS:   throw new Error("错误信息");
来源：http://dali.gaohongyu789.top/Article/details/gtytjekokd.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.iojbl.cn/Article/details/gtjooxrqih.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yanxiufei.cn/Article/details/gtisqpnbsw.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.9152youxi.cn/Article/details/gtvukbvhgk.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jinghuilouyu.cn/Article/details/gtompixfus.html

[H04] 自定义异常类型
来源：http://dali.gaohongyu789.top/Article/details/gtbpasvcus.html

Py:   class MyError(Exception): pass
来源：http://dali.yuanzhike.top/Article/details/gtpafuyhra.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jianghu66.top/Article/details/gtbdjpkrtz.html

JS:   class MyError extends Error {}
来源：http://dali.redwolf501.top/Article/details/gtzkumqyhx.html

TS:   class MyError extends Error {}
来源：http://dali.xinyue.icu/Article/details/gtlpmmvgud.html

Java: class MyException extends RuntimeException {}
来源：http://dali.316326.xyz/Article/details/gtpujkywzr.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.shzxlz.cn/Article/details/gtiuubpdri.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhengqikj.top/Article/details/gtmlsgmlgv.html

C#:   class MyException : Exception {}
来源：http://dali.wangshuangyany.cn/Article/details/gtkshrjljd.html

[H05] 捕获特定类型
来源：http://dali.shanyushiyangtech.top/Article/details/gthbibzknr.html

Py:   except ValueError as e:
来源：http://dali.yuanzhike.top/Article/details/gtbowxxjlf.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jyoumei.cn/Article/details/gtmrmrfkwn.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.xylfe.cn/Article/details/gtcjruisks.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.nanxinkj.top/Article/details/gtbsmygmnz.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.dashuyun.cn/Article/details/gtnfbhnkzk.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.sufxvd.cn/Article/details/gtqefavrhe.html

Ruby: rescue ArgumentError => e
来源：http://dali.dashuyun.cn/Article/details/gtmyymzphh.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jianghu66.top/Article/details/gtygevmbao.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yj202588.top/Article/details/gtrsabkvrz.html

Py:   value = d.get("k") or default
来源：http://dali.zhengqikj.top/Article/details/gtzhjvbtkp.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jiagoushi.top/Article/details/gtiwyhvpom.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.cheryme.top/Article/details/gtnnifvdmo.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yongpay.top/Article/details/gtjmpdbgbs.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.sysykeji.top/Article/details/gtcapppdvx.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwruhskot.html

Ruby: d&.dig(:a, :b)
来源：http://dali.mhx1999.top/Article/details/gthrcypkjs.html

C#:   obj?.A?.B ?? default
来源：http://dali.havefunace.top/Article/details/gtynqmxbhe.html

[H07] 断言
来源：http://dali.jinqigufen.top/Article/details/gtbdwkhuth.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jqgfzy.top/Article/details/gtsoiwpcij.html

PHP:  assert($x > 0);
来源：http://dali.gogol.net.cn/Article/details/gtptmnzgpt.html

JS:   console.assert(x > 0);
来源：http://dali.kuanghao11.cn/Article/details/gtozwrgayf.html

TS:   console.assert(x > 0);
来源：http://dali.feifeiyinyue.top/Article/details/gtrmopyyll.html

Java: assert x > 0 : "必须为正";
来源：http://dali.ybcxt.top/Article/details/gtkrouxdoa.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.andypj.xyz/Article/details/gtywbqumms.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.0kj1m.cn/Article/details/gtymazvqry.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gtclvwhpef.html

[H08] 获取错误信息与堆栈
来源：http://dali.fengsongda.top/Article/details/gttvymhzzq.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.tanke756.top/Article/details/gtvotxfxlz.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.mhx1999.top/Article/details/gtexdoeewe.html

JS:   e.message;  e.stack
来源：http://dali.hnqzz.top/Article/details/gtnpqecvog.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.aizwys.cn/Article/details/gtliccxcvk.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.316326.xyz/Article/details/gtgjncbwef.html

Go:   err.Error()
来源：http://dali.jinqigfzy.top/Article/details/gtkyjwmdow.html

Ruby: e.message;  e.backtrace
来源：http://dali.hfpthk.cn/Article/details/gtidfjybdl.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zycfv.cn/Article/details/gteadlgijs.html

[H09] 带错误码的异常
来源：http://dali.dianchejie.cn/Article/details/gtohuuyvra.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttstqlfox.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.xinyue.icu/Article/details/gtzmtdkudt.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.smart0.xyz/Article/details/gtzpgicagt.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.xinyue.icu/Article/details/gtrztimurs.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqkrmskgo.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.tian-w.cn/Article/details/gtrhetcbwn.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.ybcxt.top/Article/details/gtqdltvrmn.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jinqigufen.top/Article/details/gthnhcxxvc.html

[H10] 资源自动释放
来源：http://dali.yj20258888.top/Article/details/gtauaxrzqp.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.gaohongyu789.top/Article/details/gtsddacxve.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.sweek.top/Article/details/gtipjwoeni.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gzhubu.top/Article/details/gthcikdkdh.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.nanxinkj.top/Article/details/gtbuvcjvsb.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.0kj1m.cn/Article/details/gttpmthcbu.html

Go:   defer f.Close()
来源：http://dali.zhixingplan.top/Article/details/gtobysttax.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yangfankeji.com/Article/details/gtyvkpasvo.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.cheryme.top/Article/details/gtnqqkduqv.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbbsrzmku.html

I. 正则表达式
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvxzjignk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtsuncazhe.html

[I01] 判断是否匹配
来源：http://dali.jianghu66.top/Article/details/gtzewmivcr.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.hysaishi.cn/Article/details/gtvagjqoos.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.meibo888.top/Article/details/gtnjdkmsyt.html

JS:   /\d+/.test(s)
来源：http://dali.316326.xyz/Article/details/gtacendrps.html

TS:   /\d+/.test(s)
来源：http://dali.cdnleiting.top/Article/details/gtfkqpmdrt.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.hysaishi.cn/Article/details/gtuuskaovg.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.sysykeji.top/Article/details/gtcfeniiez.html

Ruby: s.match?(/\d+/)
来源：http://dali.aizwys.cn/Article/details/gtzosiyhow.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.gotoacloud.top/Article/details/gticlvcgss.html

[I02] 提取所有匹配
来源：http://dali.chenzaomai.com/Article/details/gtpiuhfjub.html

Py:   re.findall(r"\d+", s)
来源：http://dali.xziqi.cn/Article/details/gtnngurish.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.0kj1m.cn/Article/details/gtuukccgmh.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.haohaochexian.top/Article/details/gtnfklioch.html

TS:   s.match(/\d+/g)
来源：http://dali.yvedp.cn/Article/details/gtaiwmvibj.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.sweek.top/Article/details/gtqgcbjohr.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.cucudq.cn/Article/details/gtgneqasgj.html

Ruby: s.scan(/\d+/)
来源：http://dali.mhx1999.top/Article/details/gtdtwzhwtj.html


<!-- 参考信息 -->