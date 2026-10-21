代发 wailian999

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcqkxsafz.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.feifeiyinyue.top/Article/details/gthmlftafu.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.snrcjt.cn/Article/details/gtqkbdzibq.html

[F08] 遍历目录
来源：http://dali.vqdsnc.cn/Article/details/gtclpwfvjm.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.dianchejie.cn/Article/details/gtundmwmgd.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.meibo888.top/Article/details/gtsujsewma.html

JS:   fs.readdirSync("dir")
来源：http://dali.wangshuangyany.cn/Article/details/gtneuspplc.html

TS:   fs.readdirSync("dir")
来源：http://dali.yueranfly.top/Article/details/gtswixnmlb.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.cheryme.top/Article/details/gtnhhxcnid.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.aizwys.cn/Article/details/gtducptayq.html

Ruby: Dir.children("dir")
来源：http://dali.pycfn.com/Article/details/gtvxtmaywf.html

C#:   Directory.GetFiles("dir")
来源：http://dali.cqqwz.cn/Article/details/gtjxnjrqjl.html

[F09] 获取文件大小
来源：http://dali.hnxiangtu.top/Article/details/gtksqxknez.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtdrxpeubr.html

PHP:  filesize("a.txt");
来源：http://dali.hfpthk.cn/Article/details/gtjjioerjx.html

JS:   fs.statSync("a.txt").size
来源：http://dali.daria6918.cn/Article/details/gthbyyvozj.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yj202588.top/Article/details/gtnlpumytm.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.fengsongda.top/Article/details/gtswgwiehh.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.hfpthk.cn/Article/details/gtrzjklycf.html

Ruby: File.size("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtoszpzdae.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.bjfxy.top/Article/details/gtfyfqykhc.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.xylfe.cn/Article/details/gtaxxkouav.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.wangdashe.top/Article/details/gtynjrpgeb.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.ppjwa.cn/Article/details/gtlzxruhlb.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.fzhhl.top/Article/details/gtmbwtbrbv.html

TS:   path.extname("a.txt")
来源：http://dali.havefunace.top/Article/details/gtdyaduwhe.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.svipenyu.cn/Article/details/gttmlffvcz.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtncwizkcj.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.pycfn.com/Article/details/gtmvehqmey.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.cashguo.top/Article/details/gtbfwqfquu.html

[F11] 复制与移动文件
来源：http://dali.daria6918.cn/Article/details/gthsemsnfa.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.cqqwz.cn/Article/details/gtteztmnie.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.316326.xyz/Article/details/gtiuyyqiyh.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cucudq.cn/Article/details/gtxfpebnrn.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sufxvd.cn/Article/details/gtqexdjyse.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.shzxlz.cn/Article/details/gtbprlgapw.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.dianchejie.cn/Article/details/gtuwqkejwo.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.tanke756.top/Article/details/gtejoxwwpv.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.svipenyu.cn/Article/details/gtngwyajcv.html

[F12] CSV 读写
来源：http://dali.jlsjyb.cn/Article/details/gtfztrkyxc.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.nanxuanxn.top/Article/details/gtmrnlyrel.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yonumen.top/Article/details/gtqqishqcp.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.ppjwa.cn/Article/details/gtkxkwammj.html

TS:   // 同上
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrwheyqmw.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.xylfe.cn/Article/details/gtdvsuqdhs.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.xuetiantiany.cn/Article/details/gtrekrhnpu.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.ydzc1.top/Article/details/gtjaemkorf.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yvedp.cn/Article/details/gtxzrcikvc.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gttywuxory.html

G. 面向对象
来源：http://dali.gaohongyu789.top/Article/details/gtdplshwvd.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtrczzfzej.html

[G01] 定义类
来源：http://dali.feifeiyinyue.top/Article/details/gtvxvrkzwx.html

Py:   class User: pass
来源：http://dali.yuxming.cn/Article/details/gtgfbcmeld.html

PHP:  class User {}
来源：http://dali.dashuyun.cn/Article/details/gtdjfqqonv.html

JS:   class User {}
来源：http://dali.gzhubu.top/Article/details/gthlcoojjz.html

TS:   class User { name: string = ""; }
来源：http://dali.pengpengdd.cyou/Article/details/gteuijkxhu.html

Java: class User {}
来源：http://dali.yanxiufei.cn/Article/details/gtvyqphzwm.html

Go:   type User struct { Name string }
来源：http://dali.nanxinkj.top/Article/details/gtnydrukoy.html

Ruby: class User; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxdimdhxq.html

C#:   class User {}
来源：http://dali.ybcxt.top/Article/details/gtovvjxijp.html

[G02] 构造函数
来源：http://dali.aibaodan.cn/Article/details/gthjoldsvi.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.kuanghao11.cn/Article/details/gtgjzvarpk.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxwojbpwz.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhongyouzk.top/Article/details/gtbbevykdv.html

TS:   constructor(public name: string) {}
来源：http://dali.shzxlz.cn/Article/details/gtdwapsqio.html

Java: User(String name) { this.name = name; }
来源：http://dali.jlsjyb.cn/Article/details/gtytstorth.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.nanxuanxn.top/Article/details/gtnrilegmr.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.daxiang520.top/Article/details/gtvgviomcu.html

C#:   public User(string name) { Name = name; }
来源：http://dali.chenlongwang.top/Article/details/gtuzflsilb.html

[G03] 实例属性
来源：http://dali.shuidangran.top/Article/details/gthcblsmry.html

Py:   self.name = "x"
来源：http://dali.9152youxi.cn/Article/details/gtmurkohrx.html

PHP:  public string $name = "x";
来源：http://dali.hammf.cn/Article/details/gtuphpumbk.html

JS:   this.name = "x";
来源：http://dali.dianchejie.cn/Article/details/gtxndgxijy.html

TS:   name: string = "x";
来源：http://dali.0kj1m.cn/Article/details/gtixtuqltb.html

Java: private String name;
来源：http://dali.birdmap.top/Article/details/gtiiikatvv.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.tanke756.top/Article/details/gtciczedqi.html

Ruby: @name = "x"
来源：http://dali.jinqigfzy.top/Article/details/gttsegteeu.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.andypj.xyz/Article/details/gteejvisrl.html

[G04] 定义方法
来源：http://dali.hfpthk.cn/Article/details/gttwqxvnvk.html

Py:   def greet(self): return self.name
来源：http://dali.wangdashe.top/Article/details/gtnglxxprl.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jyoumei.cn/Article/details/gtgmkptxph.html

JS:   greet() { return this.name; }
来源：http://dali.wangdashe.top/Article/details/gtrnxvoljo.html

TS:   greet(): string { return this.name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtqdaaybyo.html

Java: String greet() { return name; }
来源：http://dali.cdnleiting.top/Article/details/gtcqvqsfef.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jinghuilouyu.cn/Article/details/gtdzwfallz.html

Ruby: def greet; @name; end
来源：http://dali.sweek.top/Article/details/gtofrdvcuj.html

C#:   public string Greet() => Name;
来源：http://dali.shangyingyoupin.top/Article/details/gtmipaekeq.html

[G05] 继承
来源：http://dali.shanyushiyangkeji.top/Article/details/gthlclaufx.html

Py:   class Admin(User): pass
来源：http://dali.jinqigfzy.top/Article/details/gtyoazgjen.html

PHP:  class Admin extends User {}
来源：http://dali.iojbl.cn/Article/details/gtpopcdieu.html

JS:   class Admin extends User {}
来源：http://dali.haohaochexian.top/Article/details/gtkjnotwsh.html

TS:   class Admin extends User {}
来源：http://dali.yvedp.cn/Article/details/gtjuhzlyip.html

Java: class Admin extends User {}
来源：http://dali.kuanghao11.cn/Article/details/gtozwrnnzg.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yvedp.cn/Article/details/gtowwufbxp.html

Ruby: class Admin < User; end
来源：http://dali.c1oappe.top/Article/details/gtdexjwnnk.html

C#:   class Admin : User {}
来源：http://dali.yuxming.cn/Article/details/gtsiakxeks.html

[G06] 重写方法
来源：http://dali.yongpay.top/Article/details/gtpqtkdzia.html

Py:   def greet(self): return "admin"
来源：http://dali.shuidangran.top/Article/details/gtprttgkoo.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.9152youxi.cn/Article/details/gtvjuaerio.html

JS:   greet() { return "admin"; }
来源：http://dali.jlsjyb.cn/Article/details/gtoskkeshe.html

TS:   greet(): string { return "admin"; }
来源：http://dali.andypj.xyz/Article/details/gtawyqlnki.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.ehwqpu.com/Article/details/gtptdflhpu.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.316326.xyz/Article/details/gtszkliofx.html

Ruby: def greet; "admin"; end
来源：http://dali.nanxuanxn.top/Article/details/gtncwophfd.html

C#:   public override string Greet() => "admin";
来源：http://dali.yangfankeji.com/Article/details/gtmbvmwwgd.html

[G07] 调用父类方法
来源：http://dali.jinghuilouyu.cn/Article/details/gthlhtxbma.html

Py:   super().greet()
来源：http://dali.jqgfzy.top/Article/details/gtcifojfdq.html

PHP:  parent::greet();
来源：http://dali.nwbrower.top/Article/details/gtdvnpvmnn.html

JS:   super.greet();
来源：http://dali.pengpengdd.cyou/Article/details/gtanooucra.html

TS:   super.greet();
来源：http://dali.hfpthk.cn/Article/details/gtowjhzihn.html

Java: super.greet();
来源：http://dali.cqqwz.cn/Article/details/gtdfdketiy.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.haohaochexian.top/Article/details/gthuhdpxvn.html

Ruby: super
来源：http://dali.hnxiangtu.top/Article/details/gtuqznjopg.html

C#:   base.Greet();
来源：http://dali.gzhubu.top/Article/details/gteenhivxn.html

[G08] 静态方法与属性
来源：http://dali.hnqzz.top/Article/details/gtcwytcnpk.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.birdmap.top/Article/details/gtpgidfxdn.html

PHP:  public static function f() {}
来源：http://dali.hnxiangtu.top/Article/details/gtizbftatg.html

JS:   static f() {}
来源：http://dali.nwbrower.top/Article/details/gtvvsvlyru.html

TS:   static f(): void {}
来源：http://dali.sysykeji.top/Article/details/gtzawovqhy.html

Java: static void f() {}
来源：http://dali.yuxming.cn/Article/details/gtquwhdpdb.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.pengpengdd.cyou/Article/details/gtikllpejy.html

Ruby: def self.f; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuylvscnl.html

C#:   public static void F() {}
来源：http://dali.cqqwz.cn/Article/details/gtkztjydbb.html

[G09] 接口 / 抽象类
来源：http://dali.9152youxi.cn/Article/details/gtokescibl.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.cucudq.cn/Article/details/gtofnjrogk.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.smart0.xyz/Article/details/gtouwgtypd.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.havefunace.top/Article/details/gtylvwegtv.html

TS:   interface Shape { area(): number; }
来源：http://dali.cdnleiting.top/Article/details/gtertelzru.html

Java: interface Shape { double area(); }
来源：http://dali.chenzaomai.com/Article/details/gtlvirdizm.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yj20258.top/Article/details/gtugiteayt.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhixingplan.top/Article/details/gtusuwsypr.html

C#:   interface IShape { double Area(); }
来源：http://dali.xziqi.cn/Article/details/gteedcmfez.html

[G10] 访问控制
来源：http://dali.guowangkeji.top/Article/details/gtmywemjwb.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.wangdashe.top/Article/details/gtnxwwzuvr.html

PHP:  public / protected / private
来源：http://dali.hysaishi.cn/Article/details/gtqswnvbrv.html

JS:   #private 字段；其余公开
来源：http://dali.wangshuangyany.cn/Article/details/gtrgazuphq.html

TS:   public / protected / private
来源：http://dali.cashguo.top/Article/details/gtflobcufh.html

Java: public / protected / private / 默认包级
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcptilwnr.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhongyouzk.top/Article/details/gtzcxohthu.html

Ruby: public / protected / private
来源：http://dali.guannengcc.top/Article/details/gtyvtmdbmh.html

C#:   public / protected / private / internal
来源：http://dali.mhx1999.top/Article/details/gtyiksswmw.html

[G11] getter / setter
来源：http://dali.daxiang520.top/Article/details/gtcvryjxqw.html

Py:   @property 与 @x.setter
来源：http://dali.316326.xyz/Article/details/gtmwtursbg.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtcwkiwszs.html

JS:   get name() { return this._name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdufdzjpz.html

TS:   get name(): string { return this._name; }
来源：http://dali.pycfn.com/Article/details/gtpmheazmw.html

Java: public String getName() { return name; }
来源：http://dali.hfpthk.cn/Article/details/gttfnynzpo.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.sysykeji.top/Article/details/gtlhykchri.html

Ruby: attr_accessor :name
来源：http://dali.gogol.net.cn/Article/details/gtodraijrj.html

C#:   public string Name { get; set; }
来源：http://dali.jiagoushi.top/Article/details/gtarhuhqno.html

[G12] 对象转字符串
来源：http://dali.jinqigufen.top/Article/details/gtvelbufzm.html

Py:   def __str__(self): return self.name
来源：http://dali.meibo888.top/Article/details/gtgscofcwj.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.guowangkeji.top/Article/details/gtyxjrqyvp.html

JS:   toString() { return this.name; }
来源：http://dali.yangfankeji.com/Article/details/gtbjlureqk.html

TS:   toString(): string { return this.name; }
来源：http://dali.jqgufenzy.top/Article/details/gttyhpmghr.html

Java: @Override public String toString() { return name; }
来源：http://dali.xziqi.cn/Article/details/gtlvqwfgnl.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.havefunace.top/Article/details/gtzebhrrbf.html

Ruby: def to_s; @name; end
来源：http://dali.sweek.top/Article/details/gtderadzgi.html

C#:   public override string ToString() => Name;
来源：http://dali.daxiang520.top/Article/details/gtjuafoocv.html

[G13] 判断对象类型
来源：http://dali.jinqigfzy.top/Article/details/gtfbidfhue.html

Py:   isinstance(u, User)
来源：http://dali.sufxvd.cn/Article/details/gtwjkbrtyf.html

PHP:  $u instanceof User
来源：http://dali.guowangkeji.top/Article/details/gtfjpsvixa.html

JS:   u instanceof User
来源：http://dali.shangyingyoupin.top/Article/details/gthqlgdhwc.html

TS:   u instanceof User
来源：http://dali.feifeiyinyue.top/Article/details/gtdsnrfmdn.html

Java: u instanceof User
来源：http://dali.redwolf501.top/Article/details/gtcdrbjwed.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.andypj.xyz/Article/details/gtyesxvrll.html

Ruby: u.is_a?(User)
来源：http://dali.9152youxi.cn/Article/details/gtkaurvbro.html

C#:   u is User
来源：http://dali.chenlongwang.top/Article/details/gtsdgmvdhj.html

[G14] 数据类 / record
来源：http://dali.yonumen.top/Article/details/gtgwklfekw.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.fengsongda.top/Article/details/gtlozmyism.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.chenlongwang.top/Article/details/gteknlipuj.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.ppjwa.cn/Article/details/gttunamkcd.html

TS:   type User = { name: string; age: number };
来源：http://dali.cheryme.top/Article/details/gtqlqfumfo.html

Java: record User(String name, int age) {}
来源：http://dali.sweek.top/Article/details/gtrjgeortb.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkvmnztwb.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.redwolf501.top/Article/details/gtepetgcig.html

C#:   record User(string Name, int Age);
来源：http://dali.fengsongda.top/Article/details/gtlttqlbfq.html

[G15] 枚举
来源：http://dali.gotoacloud.top/Article/details/gtlcxhjxpf.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yj20258.top/Article/details/gtzbgejegn.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jinqigfzy.top/Article/details/gtflxgnukb.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.svipenyu.cn/Article/details/gtnvcmphsc.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yj20258.top/Article/details/gtsjysmuln.html

Java: enum Color { RED, GREEN }
来源：http://dali.sxryk.cn/Article/details/gtnoasadbj.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gtuxsirskt.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhixingplan.top/Article/details/gtaepbqwai.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gtzwxvmbtq.html

[G16] 对象转数组 / 字典
来源：http://dali.zhoulong.xyz/Article/details/gtakaogibv.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.bjfxy.top/Article/details/gtvdmymumh.html

PHP:  get_object_vars($obj);
来源：http://dali.redwolf501.top/Article/details/gtnrtsxcvi.html

JS:   Object.entries(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtcfjrfmic.html

TS:   Object.entries(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtnxtbufeg.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.iojbl.cn/Article/details/gtbdfpjypx.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.nwbrower.top/Article/details/gtrxgsbpvz.html

Ruby: obj.instance_variables
来源：http://dali.jlsjyb.cn/Article/details/gtcyqcgcel.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.chenlongwang.top/Article/details/gtnziwskzh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtsnvehbyi.html

H. 异常与错误处理
来源：http://dali.daria6918.cn/Article/details/gtqhfvqwec.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtoymsrkku.html

[H01] try / catch 基础
来源：http://dali.yueranfly.top/Article/details/gtyxgztybk.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.hongshengwenyu.top/Article/details/gtagvwtalz.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.cqqwz.cn/Article/details/gtxmogfxbn.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpzcrdiuv.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jiagoushi.top/Article/details/gtsfzupbmc.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gtdxnsejts.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yuxming.cn/Article/details/gtekshepau.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.gotoacloud.top/Article/details/gtvhkpxyhr.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.chenzaomai.com/Article/details/gtkuyklzax.html

[H02] finally / ensure 收尾
来源：http://dali.chenjidiqi.icu/Article/details/gtnitjlsnv.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhongyouzk.top/Article/details/gtypzyvclc.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.ppjwa.cn/Article/details/gtjhkopnyk.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jianghu66.top/Article/details/gtplceyyht.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhixingplan.top/Article/details/gtnjipqpur.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.fzhhl.top/Article/details/gttlyxpeyn.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.vqdsnc.cn/Article/details/gtndibkqvn.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.vqdsnc.cn/Article/details/gtkhpfdcex.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jinqigfzy.top/Article/details/gthkyvirmk.html

[H03] 主动抛出异常
来源：http://dali.316326.xyz/Article/details/gtashjdhhi.html

Py:   raise ValueError("错误信息")
来源：http://dali.gaohongyu789.top/Article/details/gtcstncodk.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhoulong.xyz/Article/details/gtyiqvienc.html

JS:   throw new Error("错误信息");
来源：http://dali.sysykeji.top/Article/details/gtrplzqznh.html

TS:   throw new Error("错误信息");
来源：http://dali.ydzc1.top/Article/details/gtanowxyoj.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.pengpengdd.cyou/Article/details/gtqobosptl.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.9152youxi.cn/Article/details/gtfpkrqrlp.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhixingplan.top/Article/details/gtczlhiooh.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.nwbrower.top/Article/details/gtqacehqyx.html

[H04] 自定义异常类型
来源：http://dali.xuetiantiany.cn/Article/details/gteweprvxb.html

Py:   class MyError(Exception): pass
来源：http://dali.xuanzx.com/Article/details/gtrngqvvki.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.gogol.net.cn/Article/details/gtecwebbwe.html

JS:   class MyError extends Error {}
来源：http://dali.chenlongwang.top/Article/details/gtavwmutaq.html

TS:   class MyError extends Error {}
来源：http://dali.dashuyun.cn/Article/details/gtgpgxzqxa.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zycfv.cn/Article/details/gtehjhrnpd.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.hnqzz.top/Article/details/gtjblbcgzv.html

Ruby: class MyError < StandardError; end
来源：http://dali.cqqwz.cn/Article/details/gtpvhaojnq.html

C#:   class MyException : Exception {}
来源：http://dali.cheryme.top/Article/details/gtsffiqlsy.html

[H05] 捕获特定类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtitunyvgw.html

Py:   except ValueError as e:
来源：http://dali.yj20258.top/Article/details/gtwwhwlnqp.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.nwbrower.top/Article/details/gtjdfkdhpa.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.daxiang520.top/Article/details/gthugnowyq.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jinqigufen.top/Article/details/gtujoummfr.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.shuidangran.top/Article/details/gtpictygxl.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.ybcxt.top/Article/details/gtuclcufgn.html

Ruby: rescue ArgumentError => e
来源：http://dali.smart0.xyz/Article/details/gtafhdhast.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.sysykeji.top/Article/details/gtwocokmrk.html

[H06] 可选值 / 空值安全访问
来源：http://dali.dashuyun.cn/Article/details/gtxgegueat.html

Py:   value = d.get("k") or default
来源：http://dali.ehwqpu.com/Article/details/gtbdzocpjo.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.smart0.xyz/Article/details/gtxklykkos.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.wangdashe.top/Article/details/gtqpxgixch.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hnxiangtu.top/Article/details/gtzapmuxgk.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.birdmap.top/Article/details/gtppozyeol.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.feifeiyinyue.top/Article/details/gtvyugiuul.html

Ruby: d&.dig(:a, :b)
来源：http://dali.cheryme.top/Article/details/gtiqrsuuwo.html

C#:   obj?.A?.B ?? default
来源：http://dali.ybcxt.top/Article/details/gtfpqetqkn.html

[H07] 断言
来源：http://dali.svipenyu.cn/Article/details/gtpvuvyplt.html

Py:   assert x > 0, "必须为正"
来源：http://dali.hongshengwenyu.top/Article/details/gtncgwjrsz.html

PHP:  assert($x > 0);
来源：http://dali.ybcxt.top/Article/details/gtqfltmeaq.html

JS:   console.assert(x > 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdbdaauxc.html

TS:   console.assert(x > 0);
来源：http://dali.shzxlz.cn/Article/details/gthswtlxja.html

Java: assert x > 0 : "必须为正";
来源：http://dali.hnxiangtu.top/Article/details/gtddinndlb.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jyoumei.cn/Article/details/gtnadywcau.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.xziqi.cn/Article/details/gtkhtesjqz.html

C#:   Debug.Assert(x > 0);
来源：http://dali.aizwys.cn/Article/details/gtrteeyezg.html

[H08] 获取错误信息与堆栈
来源：http://dali.0kj1m.cn/Article/details/gtjiztykgz.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.vqdsnc.cn/Article/details/gterddbyjj.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hfpthk.cn/Article/details/gtpmrciuvg.html

JS:   e.message;  e.stack
来源：http://dali.chenjidiqi.icu/Article/details/gtwnjdytzn.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.chenlongwang.top/Article/details/gtaudpsjju.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.smart0.xyz/Article/details/gtlgpddnte.html

Go:   err.Error()
来源：http://dali.sufxvd.cn/Article/details/gtmionlxps.html

Ruby: e.message;  e.backtrace
来源：http://dali.pycfn.com/Article/details/gttzlbcttg.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hnqzz.top/Article/details/gtkowmcyww.html

[H09] 带错误码的异常
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlvsnmkck.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.pengpengdd.cyou/Article/details/gtyvctsuko.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.ppjwa.cn/Article/details/gtjxjmtzfp.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.shangyingyoupin.top/Article/details/gtzlpscfom.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yvedp.cn/Article/details/gtksrmsoww.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yueranfly.top/Article/details/gtecedvdrm.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.tianlin.xyz/Article/details/gtzhuysiwf.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.redwolf501.top/Article/details/gtdwsqbilg.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.kuanghao11.cn/Article/details/gtmrdzadet.html

[H10] 资源自动释放
来源：http://dali.hysaishi.cn/Article/details/gtzgnnnyye.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.cashguo.top/Article/details/gtjqsolzzq.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.tianlin.xyz/Article/details/gttbildeqp.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.andypj.xyz/Article/details/gtxuqdvtyq.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xinyue.icu/Article/details/gtumnwayfo.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.quarkkingdee.top/Article/details/gtrukttomu.html

Go:   defer f.Close()
来源：http://dali.sweek.top/Article/details/gtmmvplqxq.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yuxming.cn/Article/details/gtfrfqmzma.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.fzhhl.top/Article/details/gtaxaqguyk.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtycyoqeam.html

I. 正则表达式
来源：http://dali.hywenlv.cn/Article/details/gtbensgxve.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtnvytyujb.html

[I01] 判断是否匹配
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwkmaeywe.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.kuanghao11.cn/Article/details/gtfizrixzt.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jlsjyb.cn/Article/details/gtbelrecsb.html

JS:   /\d+/.test(s)
来源：http://dali.cqqwz.cn/Article/details/gtkazikfce.html

TS:   /\d+/.test(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtitvkqhuo.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.redwolf501.top/Article/details/gtzijwxhzl.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtkarkycio.html

Ruby: s.match?(/\d+/)
来源：http://dali.316326.xyz/Article/details/gtiipdrshi.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jyoumei.cn/Article/details/gtacowqufj.html


<!-- 参考信息 -->