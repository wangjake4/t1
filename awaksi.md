代发 wailian999

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.kuanghao11.cn/Article/details/gtxpbfqogc.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.pengpengdd.cyou/Article/details/gtyatmpbmj.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yangfankeji.com/Article/details/gtjslcsirj.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.cashguo.top/Article/details/gtfvyugmzn.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.tian-w.cn/Article/details/gtwfnvnkfh.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jyoumei.cn/Article/details/gtxzmvlsgp.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.cqqwz.cn/Article/details/gtggosodbd.html

[F08] 遍历目录
来源：http://dali.hongshengwenyu.top/Article/details/gtvnpanhkp.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.shanyushiyangtech.top/Article/details/gtgnbbqibq.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.guannengcc.top/Article/details/gtacjxtxcg.html

JS:   fs.readdirSync("dir")
来源：http://dali.havefunace.top/Article/details/gtfpeiogbm.html

TS:   fs.readdirSync("dir")
来源：http://dali.jqgfzy.top/Article/details/gtxpludkxa.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.nanxuanxn.top/Article/details/gtjsuwuhua.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jiagoushi.top/Article/details/gtvygqlfqd.html

Ruby: Dir.children("dir")
来源：http://dali.chenzaomai.com/Article/details/gtldivtwcq.html

C#:   Directory.GetFiles("dir")
来源：http://dali.sxryk.cn/Article/details/gtabcnurwy.html

[F09] 获取文件大小
来源：http://dali.gaohongyu789.top/Article/details/gtbhdqnwax.html

Py:   os.path.getsize("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtqssiysrl.html

PHP:  filesize("a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkzgjdsfu.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yj202588.top/Article/details/gtapgnhijh.html

TS:   fs.statSync("a.txt").size
来源：http://dali.ybcxt.top/Article/details/gtkxxqllwl.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.andypj.xyz/Article/details/gtbnaebaqd.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhiwuduotai.top/Article/details/gtoxdtcqnz.html

Ruby: File.size("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtsvjrqmwb.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.hywenlv.cn/Article/details/gtpekvpynw.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.tianlin.xyz/Article/details/gtioemmnkp.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtxmrywucd.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.cucudq.cn/Article/details/gtlvfxspvy.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtbhvtasuz.html

TS:   path.extname("a.txt")
来源：http://dali.daxiang520.top/Article/details/gtptwjdqsq.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhoulong.xyz/Article/details/gtoiddnwce.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtyfmevfzy.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jianghu66.top/Article/details/gtexgruxog.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtamnsiesa.html

[F11] 复制与移动文件
来源：http://dali.cdnleiting.top/Article/details/gtcljjwtqb.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.meibo888.top/Article/details/gtvufybovv.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yj202588.top/Article/details/gtpeeztozf.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.snrcjt.cn/Article/details/gtxmuvpbkf.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtdejxxssc.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.316326.xyz/Article/details/gtghhmwglr.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.wangdashe.top/Article/details/gtrarnfvya.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.c1oappe.top/Article/details/gtdrzssfoa.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.gogol.net.cn/Article/details/gtabtzpbho.html

[F12] CSV 读写
来源：http://dali.zycfv.cn/Article/details/gtpmvxtqbb.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.ybcxt.top/Article/details/gtydarybvz.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hywenlv.cn/Article/details/gtbjdeprpt.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.smart0.xyz/Article/details/gtcawmotlx.html

TS:   // 同上
来源：http://dali.wangdashe.top/Article/details/gtaheapeda.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.ywan-chungtsiang.top/Article/details/gtprnrhfbe.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hfpthk.cn/Article/details/gtkhjpojiq.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.ehwqpu.com/Article/details/gtpbxsliuv.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.ydzc1.top/Article/details/gtmftulrpm.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtdigcszgu.html

G. 面向对象
来源：http://dali.chenlongwang.top/Article/details/gtweddteby.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtplsaibha.html

[G01] 定义类
来源：http://dali.wangshuangyany.cn/Article/details/gtdvnypnkm.html

Py:   class User: pass
来源：http://dali.shangyingyoupin.top/Article/details/gtezsfhpaa.html

PHP:  class User {}
来源：http://dali.aibaodan.cn/Article/details/gttphvpjjr.html

JS:   class User {}
来源：http://dali.316326.xyz/Article/details/gtyapifxci.html

TS:   class User { name: string = ""; }
来源：http://dali.yueranfly.top/Article/details/gtmxihvgxs.html

Java: class User {}
来源：http://dali.sxryk.cn/Article/details/gtyuxngddb.html

Go:   type User struct { Name string }
来源：http://dali.feifeiyinyue.top/Article/details/gtiqwggimd.html

Ruby: class User; end
来源：http://dali.ydzc1.top/Article/details/gtrmaqygrv.html

C#:   class User {}
来源：http://dali.daxiang520.top/Article/details/gtwppsrukf.html

[G02] 构造函数
来源：http://dali.feifeiyinyue.top/Article/details/gthixrbusm.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.cashguo.top/Article/details/gtupeyjamj.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.svipenyu.cn/Article/details/gtkhidxtlp.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.gaohongyu789.top/Article/details/gteptarwqv.html

TS:   constructor(public name: string) {}
来源：http://dali.shzxlz.cn/Article/details/gtiyynqivw.html

Java: User(String name) { this.name = name; }
来源：http://dali.gotoacloud.top/Article/details/gtliozcjdy.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.cqqwz.cn/Article/details/gtgrbnzfce.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yuanzhike.top/Article/details/gtukghgrlt.html

C#:   public User(string name) { Name = name; }
来源：http://dali.aibaodan.cn/Article/details/gtmbpwvime.html

[G03] 实例属性
来源：http://dali.iojbl.cn/Article/details/gtwtwatprn.html

Py:   self.name = "x"
来源：http://dali.cheryme.top/Article/details/gtdouvmrnv.html

PHP:  public string $name = "x";
来源：http://dali.havefunace.top/Article/details/gtxsgdoozf.html

JS:   this.name = "x";
来源：http://dali.shangyingyoupin.top/Article/details/gtkrqzlqlv.html

TS:   name: string = "x";
来源：http://dali.guowangkeji.top/Article/details/gtenijwiwq.html

Java: private String name;
来源：http://dali.zhengqikj.top/Article/details/gtzejzlmca.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.kuanghao11.cn/Article/details/gtqxqxzvbb.html

Ruby: @name = "x"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtldzfhsex.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.ydzc1.top/Article/details/gtufshsjij.html

[G04] 定义方法
来源：http://dali.hysaishi.cn/Article/details/gtmxakrshh.html

Py:   def greet(self): return self.name
来源：http://dali.yuxming.cn/Article/details/gtssfkxlfh.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jlsjyb.cn/Article/details/gtvqutsukr.html

JS:   greet() { return this.name; }
来源：http://dali.daria6918.cn/Article/details/gtcdqregff.html

TS:   greet(): string { return this.name; }
来源：http://dali.guannengcc.top/Article/details/gthfcgzrod.html

Java: String greet() { return name; }
来源：http://dali.cdnleiting.top/Article/details/gtzllaiztd.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.tianlin.xyz/Article/details/gtlkadjpqx.html

Ruby: def greet; @name; end
来源：http://dali.hywenlv.cn/Article/details/gtiljysise.html

C#:   public string Greet() => Name;
来源：http://dali.pengpengdd.cyou/Article/details/gtntilnrjc.html

[G05] 继承
来源：http://dali.aibaodan.cn/Article/details/gtjrlibkii.html

Py:   class Admin(User): pass
来源：http://dali.gogol.net.cn/Article/details/gtlfmkwzla.html

PHP:  class Admin extends User {}
来源：http://dali.pycfn.com/Article/details/gtmylojnyy.html

JS:   class Admin extends User {}
来源：http://dali.andypj.xyz/Article/details/gteooqggrn.html

TS:   class Admin extends User {}
来源：http://dali.cucudq.cn/Article/details/gtjzgmdkvx.html

Java: class Admin extends User {}
来源：http://dali.nwbrower.top/Article/details/gtcajzrqgc.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zdqjudy.top/Article/details/gtwlwaudgm.html

Ruby: class Admin < User; end
来源：http://dali.xylfe.cn/Article/details/gtwdmdlmse.html

C#:   class Admin : User {}
来源：http://dali.ydzc1.top/Article/details/gtxmqjlyqt.html

[G06] 重写方法
来源：http://dali.yvedp.cn/Article/details/gttecbsloj.html

Py:   def greet(self): return "admin"
来源：http://dali.nanxinkj.top/Article/details/gtqynrbppl.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jianghu66.top/Article/details/gtipjkbseg.html

JS:   greet() { return "admin"; }
来源：http://dali.hysaishi.cn/Article/details/gttetvisee.html

TS:   greet(): string { return "admin"; }
来源：http://dali.aibaodan.cn/Article/details/gtaucdojid.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.snrcjt.cn/Article/details/gtvpfjtjma.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yanxiufei.cn/Article/details/gtzzlmtovv.html

Ruby: def greet; "admin"; end
来源：http://dali.jqgfzy.top/Article/details/gtswgtygez.html

C#:   public override string Greet() => "admin";
来源：http://dali.jinqigufen.top/Article/details/gtrvxarjyj.html

[G07] 调用父类方法
来源：http://dali.sxryk.cn/Article/details/gtzrsoigqq.html

Py:   super().greet()
来源：http://dali.chenzaomai.com/Article/details/gtfnyhsdil.html

PHP:  parent::greet();
来源：http://dali.316326.xyz/Article/details/gtokirmodi.html

JS:   super.greet();
来源：http://dali.aibaodan.cn/Article/details/gtdmrvvaxy.html

TS:   super.greet();
来源：http://dali.cqqwz.cn/Article/details/gtcnofakgz.html

Java: super.greet();
来源：http://dali.jlsjyb.cn/Article/details/gthjrfdzdn.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.xuanzx.com/Article/details/gtyxsezgvi.html

Ruby: super
来源：http://dali.aibaodan.cn/Article/details/gtlfjyhftb.html

C#:   base.Greet();
来源：http://dali.cashguo.top/Article/details/gtantjqoxf.html

[G08] 静态方法与属性
来源：http://dali.fengsongda.top/Article/details/gtkyptjdqb.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xuetiantiany.cn/Article/details/gtgmtvcfnh.html

PHP:  public static function f() {}
来源：http://dali.zycfv.cn/Article/details/gtfvqahaef.html

JS:   static f() {}
来源：http://dali.chenjidiqi.icu/Article/details/gtxgomeuqb.html

TS:   static f(): void {}
来源：http://dali.iojbl.cn/Article/details/gtehwsvdkn.html

Java: static void f() {}
来源：http://dali.zdqjudy.top/Article/details/gttbphpewt.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.nwbrower.top/Article/details/gtbmhhbhgg.html

Ruby: def self.f; end
来源：http://dali.havefunace.top/Article/details/gturwroqud.html

C#:   public static void F() {}
来源：http://dali.sufxvd.cn/Article/details/gtjhplplef.html

[G09] 接口 / 抽象类
来源：http://dali.hammf.cn/Article/details/gthjcafsgf.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.vqdsnc.cn/Article/details/gtwfdqxhcc.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.chenjidiqi.icu/Article/details/gtqtfpemzh.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhixingplan.top/Article/details/gtxeljgjcn.html

TS:   interface Shape { area(): number; }
来源：http://dali.jqgufenzy.top/Article/details/gtixpqdkpm.html

Java: interface Shape { double area(); }
来源：http://dali.cashguo.top/Article/details/gttjclkuna.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.sufxvd.cn/Article/details/gtwucmtmam.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.tian-w.cn/Article/details/gtvyvqsrsg.html

C#:   interface IShape { double Area(); }
来源：http://dali.mhx1999.top/Article/details/gtmohhnzdr.html

[G10] 访问控制
来源：http://dali.xziqi.cn/Article/details/gtjrdxpqqk.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.shzxlz.cn/Article/details/gtzotggmqq.html

PHP:  public / protected / private
来源：http://dali.yuanzhike.top/Article/details/gthcehixyj.html

JS:   #private 字段；其余公开
来源：http://dali.fzhhl.top/Article/details/gtxaezdluq.html

TS:   public / protected / private
来源：http://dali.guowangkeji.top/Article/details/gtwypvvezt.html

Java: public / protected / private / 默认包级
来源：http://dali.dianchejie.cn/Article/details/gtyevyzjgp.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.havefunace.top/Article/details/gtkqufdqml.html

Ruby: public / protected / private
来源：http://dali.cashguo.top/Article/details/gterdqjsfx.html

C#:   public / protected / private / internal
来源：http://dali.tianlin.xyz/Article/details/gtaefksqai.html

[G11] getter / setter
来源：http://dali.sxryk.cn/Article/details/gtvnqafncn.html

Py:   @property 与 @x.setter
来源：http://dali.gzhubu.top/Article/details/gtwrjcboen.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.tanke756.top/Article/details/gtvvizmxya.html

JS:   get name() { return this._name; }
来源：http://dali.wangdashe.top/Article/details/gtnhldhwmh.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhoulong.xyz/Article/details/gtzhfywvah.html

Java: public String getName() { return name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtbdwnjdau.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.ehwqpu.com/Article/details/gtfqjpsplw.html

Ruby: attr_accessor :name
来源：http://dali.fengsongda.top/Article/details/gtsqwgrssp.html

C#:   public string Name { get; set; }
来源：http://dali.redwolf501.top/Article/details/gttldoyzhl.html

[G12] 对象转字符串
来源：http://dali.gaohongyu789.top/Article/details/gtlsmcxtbz.html

Py:   def __str__(self): return self.name
来源：http://dali.zhoulong.xyz/Article/details/gtlxgnpvxl.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yonumen.top/Article/details/gtruzuvgaw.html

JS:   toString() { return this.name; }
来源：http://dali.ppjwa.cn/Article/details/gtpqoiaomb.html

TS:   toString(): string { return this.name; }
来源：http://dali.nanxuanxn.top/Article/details/gtvpeotacs.html

Java: @Override public String toString() { return name; }
来源：http://dali.jinqigufen.top/Article/details/gtbuwecmip.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.xylfe.cn/Article/details/gtdpmcujgn.html

Ruby: def to_s; @name; end
来源：http://dali.wangdashe.top/Article/details/gtioavvpnf.html

C#:   public override string ToString() => Name;
来源：http://dali.pycfn.com/Article/details/gtqxupdbwc.html

[G13] 判断对象类型
来源：http://dali.shzxlz.cn/Article/details/gtunsycpaz.html

Py:   isinstance(u, User)
来源：http://dali.ybcxt.top/Article/details/gtivdrqjro.html

PHP:  $u instanceof User
来源：http://dali.jinghuilouyu.cn/Article/details/gtxzxsikuo.html

JS:   u instanceof User
来源：http://dali.jinqigufen.top/Article/details/gtbkavqyck.html

TS:   u instanceof User
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoajqllcf.html

Java: u instanceof User
来源：http://dali.jiagoushi.top/Article/details/gtogpgdnjt.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.dashuyun.cn/Article/details/gtbobgbjgn.html

Ruby: u.is_a?(User)
来源：http://dali.yj202588.top/Article/details/gtpfajivbb.html

C#:   u is User
来源：http://dali.xuetiantiany.cn/Article/details/gtjhohlqsr.html

[G14] 数据类 / record
来源：http://dali.yangfankeji.com/Article/details/gtidgfrnhh.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.aibaodan.cn/Article/details/gtbbbtkucn.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hfpthk.cn/Article/details/gtbnidbwgk.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.pengpengdd.cyou/Article/details/gtcytapnni.html

TS:   type User = { name: string; age: number };
来源：http://dali.jianghu66.top/Article/details/gtxmrshrqt.html

Java: record User(String name, int age) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuzlbjqcp.html

Go:   type User struct { Name string; Age int }
来源：http://dali.sufxvd.cn/Article/details/gtwmuwnqxb.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.snrcjt.cn/Article/details/gtyfgbknil.html

C#:   record User(string Name, int Age);
来源：http://dali.pengpengdd.cyou/Article/details/gtmrciuhyi.html

[G15] 枚举
来源：http://dali.jianghu66.top/Article/details/gtzdewvfru.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hywenlv.cn/Article/details/gtahjstmuc.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.dianchejie.cn/Article/details/gtzpilktwm.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jinqigfzy.top/Article/details/gtrrcqrkyg.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhengqikj.top/Article/details/gtfolmhxwt.html

Java: enum Color { RED, GREEN }
来源：http://dali.shanyushiyangtech.top/Article/details/gtxilvrqqs.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jinghuilouyu.cn/Article/details/gtyjdmqgcs.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ivvv.top/Article/details/gtvyjzadox.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sysykeji.top/Article/details/gtshbmmnnt.html

[G16] 对象转数组 / 字典
来源：http://dali.cqqwz.cn/Article/details/gtgbmgdntn.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.wangshuangyany.cn/Article/details/gtwwoctwtu.html

PHP:  get_object_vars($obj);
来源：http://dali.ybcxt.top/Article/details/gtpgnpqibl.html

JS:   Object.entries(obj)
来源：http://dali.hnqzz.top/Article/details/gtvfcouhwk.html

TS:   Object.entries(obj)
来源：http://dali.hfpthk.cn/Article/details/gtzravmxij.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhiwuduotai.top/Article/details/gttpprqnvk.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdkeqjmgq.html

Ruby: obj.instance_variables
来源：http://dali.jqgfzy.top/Article/details/gtcddjjjat.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jianghu66.top/Article/details/gtctumrpgx.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtjamldbqn.html

H. 异常与错误处理
来源：http://dali.sysykeji.top/Article/details/gtwlphqmof.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gteldnzpzz.html

[H01] try / catch 基础
来源：http://dali.xinyue.icu/Article/details/gtpmhrvunh.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yonumen.top/Article/details/gtybepzswd.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.birdmap.top/Article/details/gtvhzfgjix.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.shangyingyoupin.top/Article/details/gtyngoehmh.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jinqigufen.top/Article/details/gtswaphrmf.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.chenzaomai.com/Article/details/gtzdwybzap.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.daria6918.cn/Article/details/gtohcmgils.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.cqqwz.cn/Article/details/gtdjroddmy.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jiagoushi.top/Article/details/gtznlfoend.html

[H02] finally / ensure 收尾
来源：http://dali.nanxuanxn.top/Article/details/gtzdywdqja.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.xinyue.icu/Article/details/gtyinfyyvp.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.cucudq.cn/Article/details/gttcmqwbvk.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.tianlin.xyz/Article/details/gtqgffnvii.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.xylfe.cn/Article/details/gtuuiqzwky.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiqnhaiuk.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.ybcxt.top/Article/details/gtbcyhavrz.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhongyouzk.top/Article/details/gtsowmkuey.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zdqjudy.top/Article/details/gttpohlbqh.html

[H03] 主动抛出异常
来源：http://dali.gotoacloud.top/Article/details/gtwegdnvxo.html

Py:   raise ValueError("错误信息")
来源：http://dali.xuetiantiany.cn/Article/details/gtoqjzxybk.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.kuanghao11.cn/Article/details/gtdznucuqa.html

JS:   throw new Error("错误信息");
来源：http://dali.ivvv.top/Article/details/gtrjtqlcek.html

TS:   throw new Error("错误信息");
来源：http://dali.cheryme.top/Article/details/gtnzjnpmgd.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hywenlv.cn/Article/details/gtaaadptdb.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.tian-w.cn/Article/details/gtbkhnuhvu.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hywenlv.cn/Article/details/gtcpcmqvbt.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.shuidangran.top/Article/details/gtztfilwnh.html

[H04] 自定义异常类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfiupttsi.html

Py:   class MyError(Exception): pass
来源：http://dali.wangshuangyany.cn/Article/details/gtsoczpfbe.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.sufxvd.cn/Article/details/gtxbivuzkg.html

JS:   class MyError extends Error {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqwawlhyc.html

TS:   class MyError extends Error {}
来源：http://dali.yangfankeji.com/Article/details/gthnrgxphh.html

Java: class MyException extends RuntimeException {}
来源：http://dali.redwolf501.top/Article/details/gtdikapyia.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.sufxvd.cn/Article/details/gtewmcmsei.html

Ruby: class MyError < StandardError; end
来源：http://dali.hnqzz.top/Article/details/gtqjdchctb.html

C#:   class MyException : Exception {}
来源：http://dali.mhx1999.top/Article/details/gtrhnzwacw.html

[H05] 捕获特定类型
来源：http://dali.dianchejie.cn/Article/details/gtvcziztgb.html

Py:   except ValueError as e:
来源：http://dali.chenjidiqi.icu/Article/details/gtxqqitson.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.gotoacloud.top/Article/details/gtohdlqrwj.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yj20258888.top/Article/details/gtabsjnexa.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jlsjyb.cn/Article/details/gtnfugzjjt.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jiagoushi.top/Article/details/gttvnzksqg.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.shangyingyoupin.top/Article/details/gtiufkajdv.html

Ruby: rescue ArgumentError => e
来源：http://dali.jinyuanbaomall.cn/Article/details/gtclxlblyu.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hnqzz.top/Article/details/gtifoevyyk.html

[H06] 可选值 / 空值安全访问
来源：http://dali.birdmap.top/Article/details/gtpdkfipim.html

Py:   value = d.get("k") or default
来源：http://dali.9152youxi.cn/Article/details/gtyzqymirs.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.9152youxi.cn/Article/details/gtuoavnaqf.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jianghu66.top/Article/details/gtebqxgmav.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.chenlongwang.top/Article/details/gtirnxxhlt.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.daxiang520.top/Article/details/gthtoybqtx.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.sysykeji.top/Article/details/gtugicudoo.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zdqjudy.top/Article/details/gtvqunjmqz.html

C#:   obj?.A?.B ?? default
来源：http://dali.quarkkingdee.top/Article/details/gtzabnpmeu.html

[H07] 断言
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbuncjddm.html

Py:   assert x > 0, "必须为正"
来源：http://dali.guowangkeji.top/Article/details/gtlqjpmovg.html

PHP:  assert($x > 0);
来源：http://dali.hongshengwenyu.top/Article/details/gtcogehayj.html

JS:   console.assert(x > 0);
来源：http://dali.hnqzz.top/Article/details/gtjdbpdzgc.html

TS:   console.assert(x > 0);
来源：http://dali.ybcxt.top/Article/details/gtarksxgpm.html

Java: assert x > 0 : "必须为正";
来源：http://dali.redwolf501.top/Article/details/gtzmtlqwgr.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jinqigfzy.top/Article/details/gtauzjfjjx.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hfpthk.cn/Article/details/gtslhpazwg.html

C#:   Debug.Assert(x > 0);
来源：http://dali.chenzaomai.com/Article/details/gtzbjhdioq.html

[H08] 获取错误信息与堆栈
来源：http://dali.cashguo.top/Article/details/gtfkbmpauc.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.chenlongwang.top/Article/details/gtfwwjwobk.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.ydzc1.top/Article/details/gtovdaptmb.html

JS:   e.message;  e.stack
来源：http://dali.ppjwa.cn/Article/details/gttyezcqsy.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.guowangkeji.top/Article/details/gtoupkzhmu.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.nwbrower.top/Article/details/gtnvcjnqrq.html

Go:   err.Error()
来源：http://dali.ybcxt.top/Article/details/gtticackpb.html

Ruby: e.message;  e.backtrace
来源：http://dali.fzhhl.top/Article/details/gtbwtgqxyg.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hnxiangtu.top/Article/details/gttjkqdeed.html

[H09] 带错误码的异常
来源：http://dali.jinqigufen.top/Article/details/gtnpqlojll.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.cheryme.top/Article/details/gtvcztcorx.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.wangshuangyany.cn/Article/details/gtcoflgpmt.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.hammf.cn/Article/details/gtenmamgov.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhengqikj.top/Article/details/gtzedmknma.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.c1oappe.top/Article/details/gtimbfygmh.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.hammf.cn/Article/details/gtafcmmwzp.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.fzhhl.top/Article/details/gtcziislfk.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhengqikj.top/Article/details/gtennjwncx.html

[H10] 资源自动释放
来源：http://dali.shzxlz.cn/Article/details/gtngyiqbhy.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yanxiufei.cn/Article/details/gtzxozmuzh.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhixingplan.top/Article/details/gtitvgibdd.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hnqzz.top/Article/details/gtyfvxwcll.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sysykeji.top/Article/details/gtwzljdjxr.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.ydzc1.top/Article/details/gtimyeetut.html

Go:   defer f.Close()
来源：http://dali.bjfxy.top/Article/details/gtnpjgrdgr.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zhongyouzk.top/Article/details/gtbizokybx.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gtziblqdql.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtdqluzyqj.html

I. 正则表达式
来源：http://dali.iojbl.cn/Article/details/gtoezhoedz.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtzjerodpt.html

[I01] 判断是否匹配
来源：http://dali.havefunace.top/Article/details/gtappunkrk.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yj20258888.top/Article/details/gtnfcmxjvf.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkixicqkh.html

JS:   /\d+/.test(s)
来源：http://dali.316326.xyz/Article/details/gtzryctmvi.html

TS:   /\d+/.test(s)
来源：http://dali.yonumen.top/Article/details/gttxaevgeg.html


<!-- 参考信息 -->