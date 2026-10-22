代发 wailian999

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.gogol.net.cn/Article/details/gtjmqardct.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtanefwluq.html

Ruby: Dir.children("dir")
来源：http://dali.hnxiangtu.top/Article/details/gtyaidrsrk.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zycfv.cn/Article/details/gtucmkysxx.html

[F09] 获取文件大小
来源：http://dali.sufxvd.cn/Article/details/gtltghxzbo.html

Py:   os.path.getsize("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gttpggeibr.html

PHP:  filesize("a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gtoscydnia.html

JS:   fs.statSync("a.txt").size
来源：http://dali.vqdsnc.cn/Article/details/gtcujywxzy.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gtdfusoogb.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.hnxiangtu.top/Article/details/gtaqwpdftf.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.aizwys.cn/Article/details/gtgiooozjg.html

Ruby: File.size("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtgppcermw.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.nanxuanxn.top/Article/details/gtcdaoxzxh.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.sufxvd.cn/Article/details/gtbwcbbmxs.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.ydzc1.top/Article/details/gtpyiyouax.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gtxvswkmjf.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtrsukzswk.html

TS:   path.extname("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtawpekuam.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.cdnleiting.top/Article/details/gtfejpizom.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvxnqsjpf.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtxtkrvfrb.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.ydzc1.top/Article/details/gtdfclrjfs.html

[F11] 复制与移动文件
来源：http://dali.316326.xyz/Article/details/gtgadaokay.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtxmskavkp.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.aizwys.cn/Article/details/gtdnydhrcm.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jyoumei.cn/Article/details/gtuguglfnw.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.nanxinkj.top/Article/details/gtmnwueulx.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.tian-w.cn/Article/details/gtcufneabi.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.aizwys.cn/Article/details/gtsaoeoigd.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtyohzchkk.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxdktlpuo.html

[F12] CSV 读写
来源：http://dali.yvedp.cn/Article/details/gtcbgrpgru.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxbrhoxyx.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhixingplan.top/Article/details/gticqeivrx.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.tian-w.cn/Article/details/gtznvtnghh.html

TS:   // 同上
来源：http://dali.xylfe.cn/Article/details/gteiyujzes.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.316326.xyz/Article/details/gttdtqlwum.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.meibo888.top/Article/details/gtwmuwvyzm.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.kuanghao11.cn/Article/details/gtinkvajtz.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjkzasvyz.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtxxdomwgt.html

G. 面向对象
来源：http://dali.jinghuilouyu.cn/Article/details/gteswuvxdr.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnhqjjpps.html

[G01] 定义类
来源：http://dali.snrcjt.cn/Article/details/gtexjzwekx.html

Py:   class User: pass
来源：http://dali.xinyue.icu/Article/details/gtmhrinmeo.html

PHP:  class User {}
来源：http://dali.sysykeji.top/Article/details/gtlpgishmt.html

JS:   class User {}
来源：http://dali.dianchejie.cn/Article/details/gtsjnrfvbb.html

TS:   class User { name: string = ""; }
来源：http://dali.cashguo.top/Article/details/gtvaawbbde.html

Java: class User {}
来源：http://dali.zhiwuduotai.top/Article/details/gtermkzohl.html

Go:   type User struct { Name string }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtajeftevu.html

Ruby: class User; end
来源：http://dali.shuidangran.top/Article/details/gtgrdcewki.html

C#:   class User {}
来源：http://dali.316326.xyz/Article/details/gtzwnhwvhf.html

[G02] 构造函数
来源：http://dali.ehwqpu.com/Article/details/gtoldthnmf.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jiagoushi.top/Article/details/gtgikjntuj.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.guowangkeji.top/Article/details/gtrlxddrca.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.chenzaomai.com/Article/details/gtfdpuvfrv.html

TS:   constructor(public name: string) {}
来源：http://dali.haohaochexian.top/Article/details/gtxmipxwle.html

Java: User(String name) { this.name = name; }
来源：http://dali.xziqi.cn/Article/details/gtgzlxoimf.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.guannengcc.top/Article/details/gtwgortruu.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.9152youxi.cn/Article/details/gtxavcqavj.html

C#:   public User(string name) { Name = name; }
来源：http://dali.haohaochexian.top/Article/details/gtahygeczy.html

[G03] 实例属性
来源：http://dali.jinyuanbaomall.cn/Article/details/gtivwtyscy.html

Py:   self.name = "x"
来源：http://dali.guowangkeji.top/Article/details/gtgvijeugs.html

PHP:  public string $name = "x";
来源：http://dali.birdmap.top/Article/details/gtmnpapkup.html

JS:   this.name = "x";
来源：http://dali.daria6918.cn/Article/details/gtpmlnkhwe.html

TS:   name: string = "x";
来源：http://dali.0kj1m.cn/Article/details/gtpmeheops.html

Java: private String name;
来源：http://dali.zhixingplan.top/Article/details/gttgynufkf.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.fengsongda.top/Article/details/gtxiarjuee.html

Ruby: @name = "x"
来源：http://dali.9152youxi.cn/Article/details/gtdcnvmxcm.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.wangshuangyany.cn/Article/details/gtdlzppjts.html

[G04] 定义方法
来源：http://dali.xuetiantiany.cn/Article/details/gtmdkxnwok.html

Py:   def greet(self): return self.name
来源：http://dali.fengsongda.top/Article/details/gtrrfljfdi.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.ydzc1.top/Article/details/gtouvxvvfh.html

JS:   greet() { return this.name; }
来源：http://dali.aibaodan.cn/Article/details/gtwtkfsugo.html

TS:   greet(): string { return this.name; }
来源：http://dali.hnxiangtu.top/Article/details/gtzhttndig.html

Java: String greet() { return name; }
来源：http://dali.gogol.net.cn/Article/details/gtlnfflatj.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.fengsongda.top/Article/details/gtyyxcapob.html

Ruby: def greet; @name; end
来源：http://dali.yj20258888.top/Article/details/gtbjobuzef.html

C#:   public string Greet() => Name;
来源：http://dali.hfpthk.cn/Article/details/gtyjdftevf.html

[G05] 继承
来源：http://dali.chenlongwang.top/Article/details/gtnfwaxusn.html

Py:   class Admin(User): pass
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfbvotbys.html

PHP:  class Admin extends User {}
来源：http://dali.yangfankeji.com/Article/details/gtprdbezwk.html

JS:   class Admin extends User {}
来源：http://dali.ivvv.top/Article/details/gtksfstonp.html

TS:   class Admin extends User {}
来源：http://dali.cucudq.cn/Article/details/gtljeekswi.html

Java: class Admin extends User {}
来源：http://dali.meibo888.top/Article/details/gtibrkcfyu.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ybcxt.top/Article/details/gthqqeuycn.html

Ruby: class Admin < User; end
来源：http://dali.sysykeji.top/Article/details/gteoplbssu.html

C#:   class Admin : User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtccltaxyu.html

[G06] 重写方法
来源：http://dali.yanxiufei.cn/Article/details/gtvhdqjavn.html

Py:   def greet(self): return "admin"
来源：http://dali.mhx1999.top/Article/details/gtyekczfvz.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.pengpengdd.cyou/Article/details/gtdhlhetxn.html

JS:   greet() { return "admin"; }
来源：http://dali.yj202588.top/Article/details/gthxnnqivf.html

TS:   greet(): string { return "admin"; }
来源：http://dali.ehwqpu.com/Article/details/gtpmdmimde.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.shzxlz.cn/Article/details/gtwpaschhd.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.gogol.net.cn/Article/details/gtfvkywkfc.html

Ruby: def greet; "admin"; end
来源：http://dali.jqgufenzy.top/Article/details/gtdwodwmqh.html

C#:   public override string Greet() => "admin";
来源：http://dali.nwbrower.top/Article/details/gtczsaqtmf.html

[G07] 调用父类方法
来源：http://dali.pengpengdd.cyou/Article/details/gtlfrjpehj.html

Py:   super().greet()
来源：http://dali.hnxiangtu.top/Article/details/gtewtkgjfs.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gtatrwtqjr.html

JS:   super.greet();
来源：http://dali.316326.xyz/Article/details/gtgxrtuujy.html

TS:   super.greet();
来源：http://dali.bjfxy.top/Article/details/gtrpwjiwhf.html

Java: super.greet();
来源：http://dali.xylfe.cn/Article/details/gtishrxudu.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yj202588.top/Article/details/gtouqzgbhs.html

Ruby: super
来源：http://dali.pycfn.com/Article/details/gttulwpasz.html

C#:   base.Greet();
来源：http://dali.chenjidiqi.icu/Article/details/gtrqmmszqi.html

[G08] 静态方法与属性
来源：http://dali.xylfe.cn/Article/details/gtzjpomnau.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.cqqwz.cn/Article/details/gtkahofnpe.html

PHP:  public static function f() {}
来源：http://dali.cheryme.top/Article/details/gtxkdkkwmq.html

JS:   static f() {}
来源：http://dali.sufxvd.cn/Article/details/gtnfduelkq.html

TS:   static f(): void {}
来源：http://dali.sxryk.cn/Article/details/gtnxuwwhsh.html

Java: static void f() {}
来源：http://dali.iojbl.cn/Article/details/gtezkzvjff.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.andypj.xyz/Article/details/gtsegdwcta.html

Ruby: def self.f; end
来源：http://dali.haohaochexian.top/Article/details/gtphgmpmeo.html

C#:   public static void F() {}
来源：http://dali.redwolf501.top/Article/details/gtwrzooifn.html

[G09] 接口 / 抽象类
来源：http://dali.nwbrower.top/Article/details/gtlwlhfadi.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jqgfzy.top/Article/details/gtnrlvluiw.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.quarkkingdee.top/Article/details/gtbztpqbko.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ehwqpu.com/Article/details/gtjhfvckbz.html

TS:   interface Shape { area(): number; }
来源：http://dali.cqqwz.cn/Article/details/gtbvsjrqql.html

Java: interface Shape { double area(); }
来源：http://dali.cheryme.top/Article/details/gtbtwdpgph.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.pycfn.com/Article/details/gtbxwyizgv.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.kuanghao11.cn/Article/details/gtsooehcdb.html

C#:   interface IShape { double Area(); }
来源：http://dali.bjfxy.top/Article/details/gtdzjuxnzo.html

[G10] 访问控制
来源：http://dali.jiagoushi.top/Article/details/gtzriddtdn.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.birdmap.top/Article/details/gtrbvqkuwe.html

PHP:  public / protected / private
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmgeyexjd.html

JS:   #private 字段；其余公开
来源：http://dali.jyoumei.cn/Article/details/gtidbrydzl.html

TS:   public / protected / private
来源：http://dali.jianghu66.top/Article/details/gtaerubtao.html

Java: public / protected / private / 默认包级
来源：http://dali.yongpay.top/Article/details/gtfbfmrgxk.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.sxryk.cn/Article/details/gtbarknwdh.html

Ruby: public / protected / private
来源：http://dali.yanxiufei.cn/Article/details/gtbycjupdg.html

C#:   public / protected / private / internal
来源：http://dali.zhixingplan.top/Article/details/gtgoqohtyb.html

[G11] getter / setter
来源：http://dali.jinqigfzy.top/Article/details/gtcugjlipi.html

Py:   @property 与 @x.setter
来源：http://dali.cashguo.top/Article/details/gthqujmnqc.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.hammf.cn/Article/details/gtimoustpx.html

JS:   get name() { return this._name; }
来源：http://dali.ivvv.top/Article/details/gtadxyfkei.html

TS:   get name(): string { return this._name; }
来源：http://dali.chenlongwang.top/Article/details/gtyohdtnda.html

Java: public String getName() { return name; }
来源：http://dali.wangdashe.top/Article/details/gtlqzzolfq.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.aizwys.cn/Article/details/gtohruoovc.html

Ruby: attr_accessor :name
来源：http://dali.yueranfly.top/Article/details/gtzjqylntw.html

C#:   public string Name { get; set; }
来源：http://dali.shuidangran.top/Article/details/gteqevdvxd.html

[G12] 对象转字符串
来源：http://dali.xuetiantiany.cn/Article/details/gtdjgcwxnl.html

Py:   def __str__(self): return self.name
来源：http://dali.yongpay.top/Article/details/gtxhryscmy.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zdqjudy.top/Article/details/gtcyvowhsc.html

JS:   toString() { return this.name; }
来源：http://dali.yj20258888.top/Article/details/gtdmgfadiz.html

TS:   toString(): string { return this.name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtsnhvikvp.html

Java: @Override public String toString() { return name; }
来源：http://dali.vqdsnc.cn/Article/details/gtstrmsgmt.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.c1oappe.top/Article/details/gtwocawhsh.html

Ruby: def to_s; @name; end
来源：http://dali.chenlongwang.top/Article/details/gtkdqghvlz.html

C#:   public override string ToString() => Name;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtagrmcqnf.html

[G13] 判断对象类型
来源：http://dali.guannengcc.top/Article/details/gtwxqwpirt.html

Py:   isinstance(u, User)
来源：http://dali.zhengqikj.top/Article/details/gtgpasoxft.html

PHP:  $u instanceof User
来源：http://dali.ydzc1.top/Article/details/gtcurslhma.html

JS:   u instanceof User
来源：http://dali.fzhhl.top/Article/details/gtrufcoami.html

TS:   u instanceof User
来源：http://dali.jianghu66.top/Article/details/gtlmufubml.html

Java: u instanceof User
来源：http://dali.yanxiufei.cn/Article/details/gtknbuccsc.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.xziqi.cn/Article/details/gtbuiffkut.html

Ruby: u.is_a?(User)
来源：http://dali.zhoulong.xyz/Article/details/gtsnjpkovq.html

C#:   u is User
来源：http://dali.sweek.top/Article/details/gtlygjcene.html

[G14] 数据类 / record
来源：http://dali.hywenlv.cn/Article/details/gttssolopj.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhiwuduotai.top/Article/details/gthaoqcwua.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.gogol.net.cn/Article/details/gtozduvmxa.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yonumen.top/Article/details/gtdnpfjvfj.html

TS:   type User = { name: string; age: number };
来源：http://dali.jinqigufen.top/Article/details/gtydogczgc.html

Java: record User(String name, int age) {}
来源：http://dali.aibaodan.cn/Article/details/gtifxtngpf.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jqgufenzy.top/Article/details/gtabvaosfn.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yvedp.cn/Article/details/gtsvwntrzk.html

C#:   record User(string Name, int Age);
来源：http://dali.daxiang520.top/Article/details/gtsspocdcb.html

[G15] 枚举
来源：http://dali.tianlin.xyz/Article/details/gtyekwhhfs.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.redwolf501.top/Article/details/gttigcxnen.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.xuanzx.com/Article/details/gtvbedlcjb.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.chenjidiqi.icu/Article/details/gtptgjgcsv.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.nwbrower.top/Article/details/gtxvsduvyw.html

Java: enum Color { RED, GREEN }
来源：http://dali.jinqigfzy.top/Article/details/gtjhploxct.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.guannengcc.top/Article/details/gtplcvinto.html

Ruby: Color = %i[red green].freeze
来源：http://dali.havefunace.top/Article/details/gtcrlujoas.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.havefunace.top/Article/details/gtezkbvmmt.html

[G16] 对象转数组 / 字典
来源：http://dali.fzhhl.top/Article/details/gtxmjejech.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.hongshengwenyu.top/Article/details/gtxnqwbtab.html

PHP:  get_object_vars($obj);
来源：http://dali.xziqi.cn/Article/details/gtsgbfdrgb.html

JS:   Object.entries(obj)
来源：http://dali.iojbl.cn/Article/details/gtrlhmmqdz.html

TS:   Object.entries(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtiiarvxtk.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.pycfn.com/Article/details/gthslgwhqa.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.cashguo.top/Article/details/gtiafevtin.html

Ruby: obj.instance_variables
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzfhovtaw.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zycfv.cn/Article/details/gtgjxkfhuk.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtixldizrr.html

H. 异常与错误处理
来源：http://dali.hnqzz.top/Article/details/gtbrshjoxg.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtbdywzdxb.html

[H01] try / catch 基础
来源：http://dali.haohaochexian.top/Article/details/gtpihayxha.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yangfankeji.com/Article/details/gtfqvnzkzr.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.nanxinkj.top/Article/details/gtunmymimc.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.fzhhl.top/Article/details/gtfxdjwffd.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.birdmap.top/Article/details/gtdgdgcahv.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.c1oappe.top/Article/details/gtfsxfwnjo.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhengqikj.top/Article/details/gtfokabiut.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.guowangkeji.top/Article/details/gtelpmwuok.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtksbnbbnz.html

[H02] finally / ensure 收尾
来源：http://dali.cqqwz.cn/Article/details/gtbacbphig.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yvedp.cn/Article/details/gtyufocboa.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jyoumei.cn/Article/details/gtaxmewzst.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.tian-w.cn/Article/details/gtgtekpnju.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.feifeiyinyue.top/Article/details/gtktninuak.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.0kj1m.cn/Article/details/gtcdnnxiyp.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.tianlin.xyz/Article/details/gtchsbvpvz.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.fzhhl.top/Article/details/gtfxnwhznx.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jyoumei.cn/Article/details/gthzrymick.html

[H03] 主动抛出异常
来源：http://dali.redwolf501.top/Article/details/gtsergmwsx.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhengqikj.top/Article/details/gtulryupti.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jiagoushi.top/Article/details/gtvuqtdkrx.html

JS:   throw new Error("错误信息");
来源：http://dali.gogol.net.cn/Article/details/gtfktiqzkk.html

TS:   throw new Error("错误信息");
来源：http://dali.tianlin.xyz/Article/details/gtjewyggaa.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.meibo888.top/Article/details/gtekyvrnkz.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.ivvv.top/Article/details/gtruawoedi.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.xuetiantiany.cn/Article/details/gtnpivnivg.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.gogol.net.cn/Article/details/gtqvnjvdxc.html

[H04] 自定义异常类型
来源：http://dali.xylfe.cn/Article/details/gtspkgneba.html

Py:   class MyError(Exception): pass
来源：http://dali.cashguo.top/Article/details/gtckbxiexu.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.ydzc1.top/Article/details/gtiykupwfe.html

JS:   class MyError extends Error {}
来源：http://dali.bjfxy.top/Article/details/gttvwkjzng.html

TS:   class MyError extends Error {}
来源：http://dali.hammf.cn/Article/details/gtpluxfwfr.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yj20258.top/Article/details/gtkgxllgnn.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yj20258.top/Article/details/gtqouvhlee.html

Ruby: class MyError < StandardError; end
来源：http://dali.jinghuilouyu.cn/Article/details/gtbrgrthaj.html

C#:   class MyException : Exception {}
来源：http://dali.gogol.net.cn/Article/details/gtojsgdwcj.html

[H05] 捕获特定类型
来源：http://dali.ydzc1.top/Article/details/gtmwlfxelg.html

Py:   except ValueError as e:
来源：http://dali.gogol.net.cn/Article/details/gtzintojoz.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yuanzhike.top/Article/details/gtskrbwxas.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.svipenyu.cn/Article/details/gthirdwizn.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.ydzc1.top/Article/details/gtlpvfzivi.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gtumnhbydk.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.pycfn.com/Article/details/gtrzhzuyyy.html

Ruby: rescue ArgumentError => e
来源：http://dali.pengpengdd.cyou/Article/details/gtcmfhmkih.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.redwolf501.top/Article/details/gtovyttwsx.html

[H06] 可选值 / 空值安全访问
来源：http://dali.hnxiangtu.top/Article/details/gtuaeeptae.html

Py:   value = d.get("k") or default
来源：http://dali.ehwqpu.com/Article/details/gtthxpbgdp.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zdqjudy.top/Article/details/gtugdeofod.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.aizwys.cn/Article/details/gtrvmpnoat.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.fzhhl.top/Article/details/gtgsuukpcw.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.c1oappe.top/Article/details/gtslakgfap.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.ydzc1.top/Article/details/gtfbgdkdst.html

Ruby: d&.dig(:a, :b)
来源：http://dali.bjfxy.top/Article/details/gthcqqogrg.html

C#:   obj?.A?.B ?? default
来源：http://dali.snrcjt.cn/Article/details/gtwenoljym.html

[H07] 断言
来源：http://dali.hongshengwenyu.top/Article/details/gtuvdzxrdy.html

Py:   assert x > 0, "必须为正"
来源：http://dali.cdnleiting.top/Article/details/gtkabvdqra.html

PHP:  assert($x > 0);
来源：http://dali.ppjwa.cn/Article/details/gtjfgukedr.html

JS:   console.assert(x > 0);
来源：http://dali.pycfn.com/Article/details/gtfvwwdkkp.html

TS:   console.assert(x > 0);
来源：http://dali.zhongyouzk.top/Article/details/gtbfnlkcaf.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yj20258888.top/Article/details/gtdqduiuqn.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.cashguo.top/Article/details/gtinhgqngu.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jinqigufen.top/Article/details/gtqxjfzvyy.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hammf.cn/Article/details/gtitugxykn.html

[H08] 获取错误信息与堆栈
来源：http://dali.tianlin.xyz/Article/details/gtdukifmdd.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.316326.xyz/Article/details/gtgjkznxov.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.tanke756.top/Article/details/gtrgfpcydo.html

JS:   e.message;  e.stack
来源：http://dali.hnxiangtu.top/Article/details/gtvjiasmon.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.cqqwz.cn/Article/details/gtdnceygfn.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.xziqi.cn/Article/details/gtgtqksual.html

Go:   err.Error()
来源：http://dali.fengsongda.top/Article/details/gtlsuezldp.html

Ruby: e.message;  e.backtrace
来源：http://dali.gogol.net.cn/Article/details/gtjekzyvuo.html

C#:   e.Message;  e.StackTrace
来源：http://dali.shuidangran.top/Article/details/gtfupynjts.html

[H09] 带错误码的异常
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbrxioyjm.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.bjfxy.top/Article/details/gtxmnmjobl.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jiagoushi.top/Article/details/gtckrwdmxe.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.ivvv.top/Article/details/gtbzjgbbdd.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.shuidangran.top/Article/details/gtssgbdrpf.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yueranfly.top/Article/details/gtionrdscl.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.birdmap.top/Article/details/gtyhdohzhk.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.jiagoushi.top/Article/details/gtwvegpwws.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.mhx1999.top/Article/details/gtfecjnkkh.html

[H10] 资源自动释放
来源：http://dali.ivvv.top/Article/details/gtwpamcoja.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.cqqwz.cn/Article/details/gtkytstkwx.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.nanxuanxn.top/Article/details/gtxtyipknx.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.tian-w.cn/Article/details/gtfgkippxf.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gotoacloud.top/Article/details/gtalclaffd.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yonumen.top/Article/details/gthmpjvyco.html

Go:   defer f.Close()
来源：http://dali.yueranfly.top/Article/details/gtocswgyre.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.ehwqpu.com/Article/details/gtdsxnfxiz.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.shuidangran.top/Article/details/gtriwsuzoq.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtchnnmtyy.html

I. 正则表达式
来源：http://dali.chenzaomai.com/Article/details/gtludwlspa.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtbnijptft.html

[I01] 判断是否匹配
来源：http://dali.yuanzhike.top/Article/details/gtehofgvlz.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zdqjudy.top/Article/details/gtrunhqxaq.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.fzhhl.top/Article/details/gthicyhosz.html

JS:   /\d+/.test(s)
来源：http://dali.chenlongwang.top/Article/details/gtmrtfoyog.html

TS:   /\d+/.test(s)
来源：http://dali.shuidangran.top/Article/details/gteimfysjm.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.chenzaomai.com/Article/details/gtmfugodex.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.pycfn.com/Article/details/gtlkdyvhfy.html

Ruby: s.match?(/\d+/)
来源：http://dali.aizwys.cn/Article/details/gtmvpaxmcd.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrbsjfpho.html

[I02] 提取所有匹配
来源：http://dali.vqdsnc.cn/Article/details/gtemfyvqhw.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yj20258888.top/Article/details/gtngkgvlzk.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.chenlongwang.top/Article/details/gtekgihjnj.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.gaohongyu789.top/Article/details/gtduskmqau.html

TS:   s.match(/\d+/g)
来源：http://dali.haohaochexian.top/Article/details/gtfnsyduqr.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yonumen.top/Article/details/gttwkczgnm.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.ppjwa.cn/Article/details/gtgubyeesb.html

Ruby: s.scan(/\d+/)
来源：http://dali.shuidangran.top/Article/details/gtptsvxpsz.html


<!-- 参考信息 -->