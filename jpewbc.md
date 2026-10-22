代发 wailian999

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.wangdashe.top/Article/details/gtrydlwdmd.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.mhx1999.top/Article/details/gttcjrzdnt.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinqigufen.top/Article/details/gtqgyhfsdg.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.shangyingyoupin.top/Article/details/gticunyqak.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.feifeiyinyue.top/Article/details/gtaimkphhr.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.hfpthk.cn/Article/details/gtqvaxrsjm.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwdxnpzra.html

[F08] 遍历目录
来源：http://dali.shuidangran.top/Article/details/gteftfpjtx.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.ppjwa.cn/Article/details/gtrxwubemy.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.guowangkeji.top/Article/details/gtpiycfhdi.html

JS:   fs.readdirSync("dir")
来源：http://dali.jiagoushi.top/Article/details/gtbxzuwjhw.html

TS:   fs.readdirSync("dir")
来源：http://dali.redwolf501.top/Article/details/gtckbofpew.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yj20258888.top/Article/details/gttshbyoge.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jiagoushi.top/Article/details/gtyblshtmg.html

Ruby: Dir.children("dir")
来源：http://dali.smart0.xyz/Article/details/gtsvacfhgu.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hfpthk.cn/Article/details/gtodyiqiic.html

[F09] 获取文件大小
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvjfgofrr.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yonumen.top/Article/details/gtdxkdsflh.html

PHP:  filesize("a.txt");
来源：http://dali.chenzaomai.com/Article/details/gtbmrssgtg.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yuanzhike.top/Article/details/gtkoxpftxy.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yj202588.top/Article/details/gtopbrdrdl.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.xziqi.cn/Article/details/gtdgmigxeg.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzyqlacoa.html

Ruby: File.size("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtgxkrlkyf.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.chenjidiqi.icu/Article/details/gtfeuugpwd.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jlsjyb.cn/Article/details/gtmmjxlder.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtprkiqldm.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.c1oappe.top/Article/details/gthwdvxzmh.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.redwolf501.top/Article/details/gtnaddggbz.html

TS:   path.extname("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtsdlfsrnv.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.wangdashe.top/Article/details/gtvljivvon.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtwzptfzqq.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.cucudq.cn/Article/details/gtositgjwf.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.wangdashe.top/Article/details/gtebqnzalb.html

[F11] 复制与移动文件
来源：http://dali.wangshuangyany.cn/Article/details/gttdotojra.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zycfv.cn/Article/details/gtptududbs.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.vqdsnc.cn/Article/details/gtklizridt.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.daria6918.cn/Article/details/gtnhksabxt.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtnrvkpxfq.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.andypj.xyz/Article/details/gtwnyymvdc.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.fengsongda.top/Article/details/gtpahrglrs.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.iojbl.cn/Article/details/gtdrutxksb.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yanxiufei.cn/Article/details/gtyhbgurtn.html

[F12] CSV 读写
来源：http://dali.c1oappe.top/Article/details/gttgacmwwf.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.ehwqpu.com/Article/details/gtflocltoi.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.tian-w.cn/Article/details/gtigwwmlzx.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jyoumei.cn/Article/details/gtvnxthdeh.html

TS:   // 同上
来源：http://dali.guowangkeji.top/Article/details/gtbzzwuxcc.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.ybcxt.top/Article/details/gtezwwbefn.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.chenjidiqi.icu/Article/details/gtpdffwouc.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zycfv.cn/Article/details/gtzgnnlfoh.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yonumen.top/Article/details/gtbxqxeunv.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtkxuqjayr.html

G. 面向对象
来源：http://dali.guannengcc.top/Article/details/gtbouldrlq.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtnqxvytzk.html

[G01] 定义类
来源：http://dali.gotoacloud.top/Article/details/gtxjdlofot.html

Py:   class User: pass
来源：http://dali.jinghuilouyu.cn/Article/details/gtsuaovxjs.html

PHP:  class User {}
来源：http://dali.jyoumei.cn/Article/details/gtxxsibslt.html

JS:   class User {}
来源：http://dali.dashuyun.cn/Article/details/gtuwrvifqs.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gtakceiqou.html

Java: class User {}
来源：http://dali.nwbrower.top/Article/details/gtglhhosif.html

Go:   type User struct { Name string }
来源：http://dali.zhixingplan.top/Article/details/gtdvxprnqy.html

Ruby: class User; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtifhddblu.html

C#:   class User {}
来源：http://dali.vqdsnc.cn/Article/details/gtganeopnm.html

[G02] 构造函数
来源：http://dali.0kj1m.cn/Article/details/gtvnyglwmz.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhiwuduotai.top/Article/details/gtwkojrhou.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtjdpnuzvi.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.xuanzx.com/Article/details/gtuettfbom.html

TS:   constructor(public name: string) {}
来源：http://dali.snrcjt.cn/Article/details/gtcpmqbmlz.html

Java: User(String name) { this.name = name; }
来源：http://dali.hnxiangtu.top/Article/details/gtlpdzkqua.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.sweek.top/Article/details/gtyymiixqw.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.aibaodan.cn/Article/details/gtizissjgd.html

C#:   public User(string name) { Name = name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtejnwcuom.html

[G03] 实例属性
来源：http://dali.smart0.xyz/Article/details/gtihfeobta.html

Py:   self.name = "x"
来源：http://dali.jianghu66.top/Article/details/gtnuxacrvt.html

PHP:  public string $name = "x";
来源：http://dali.yj20258.top/Article/details/gtiscgleff.html

JS:   this.name = "x";
来源：http://dali.vqdsnc.cn/Article/details/gtvhbkzvix.html

TS:   name: string = "x";
来源：http://dali.pengpengdd.cyou/Article/details/gtsbnjiivo.html

Java: private String name;
来源：http://dali.shzxlz.cn/Article/details/gtrwjxnjve.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.havefunace.top/Article/details/gtttsuwtgb.html

Ruby: @name = "x"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkprftqtz.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.sysykeji.top/Article/details/gtcvkwwiii.html

[G04] 定义方法
来源：http://dali.tian-w.cn/Article/details/gtrndyvooh.html

Py:   def greet(self): return self.name
来源：http://dali.dashuyun.cn/Article/details/gtwhpicalc.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hnxiangtu.top/Article/details/gtlcxyyhmk.html

JS:   greet() { return this.name; }
来源：http://dali.yuxming.cn/Article/details/gtttosxvbq.html

TS:   greet(): string { return this.name; }
来源：http://dali.sufxvd.cn/Article/details/gtrxnesldi.html

Java: String greet() { return name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvpmdzeze.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.chenjidiqi.icu/Article/details/gthrksxflg.html

Ruby: def greet; @name; end
来源：http://dali.chenzaomai.com/Article/details/gtecyyfgin.html

C#:   public string Greet() => Name;
来源：http://dali.cdnleiting.top/Article/details/gtskxfpejc.html

[G05] 继承
来源：http://dali.quarkkingdee.top/Article/details/gtbeslpdva.html

Py:   class Admin(User): pass
来源：http://dali.yuxming.cn/Article/details/gtkhgqeeeo.html

PHP:  class Admin extends User {}
来源：http://dali.yueranfly.top/Article/details/gttlkcvjhp.html

JS:   class Admin extends User {}
来源：http://dali.sufxvd.cn/Article/details/gtgmvdoazb.html

TS:   class Admin extends User {}
来源：http://dali.yvedp.cn/Article/details/gtwbkfrxfd.html

Java: class Admin extends User {}
来源：http://dali.jiagoushi.top/Article/details/gtkwgpwiop.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.daria6918.cn/Article/details/gtdopdtayw.html

Ruby: class Admin < User; end
来源：http://dali.ybcxt.top/Article/details/gtllzeypdp.html

C#:   class Admin : User {}
来源：http://dali.gogol.net.cn/Article/details/gtbqvliseq.html

[G06] 重写方法
来源：http://dali.yonumen.top/Article/details/gttiokmnke.html

Py:   def greet(self): return "admin"
来源：http://dali.hnqzz.top/Article/details/gtllmyudbk.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yangfankeji.com/Article/details/gtzuubdrsq.html

JS:   greet() { return "admin"; }
来源：http://dali.ppjwa.cn/Article/details/gtzabaemqb.html

TS:   greet(): string { return "admin"; }
来源：http://dali.meibo888.top/Article/details/gtuwuvogvt.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.daxiang520.top/Article/details/gtgseevftf.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.quarkkingdee.top/Article/details/gtnhibovda.html

Ruby: def greet; "admin"; end
来源：http://dali.316326.xyz/Article/details/gtvsddcegz.html

C#:   public override string Greet() => "admin";
来源：http://dali.wangshuangyany.cn/Article/details/gtdudadwme.html

[G07] 调用父类方法
来源：http://dali.yuxming.cn/Article/details/gtvsumdmbj.html

Py:   super().greet()
来源：http://dali.zhiwuduotai.top/Article/details/gtjlqvwcey.html

PHP:  parent::greet();
来源：http://dali.cheryme.top/Article/details/gtepridiss.html

JS:   super.greet();
来源：http://dali.tianlin.xyz/Article/details/gteqnwcsmn.html

TS:   super.greet();
来源：http://dali.pycfn.com/Article/details/gtxaheiqzd.html

Java: super.greet();
来源：http://dali.316326.xyz/Article/details/gtcqkzntvk.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.chenlongwang.top/Article/details/gtttktfdum.html

Ruby: super
来源：http://dali.yonumen.top/Article/details/gtyanxebpk.html

C#:   base.Greet();
来源：http://dali.hammf.cn/Article/details/gtqxvxqihe.html

[G08] 静态方法与属性
来源：http://dali.yangfankeji.com/Article/details/gtprluwnce.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.chenzaomai.com/Article/details/gtorwxgacd.html

PHP:  public static function f() {}
来源：http://dali.yanxiufei.cn/Article/details/gtrjducbus.html

JS:   static f() {}
来源：http://dali.jiagoushi.top/Article/details/gtqbkggnnw.html

TS:   static f(): void {}
来源：http://dali.shzxlz.cn/Article/details/gtjmagtxqx.html

Java: static void f() {}
来源：http://dali.chenlongwang.top/Article/details/gtgyljxeox.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hfpthk.cn/Article/details/gteyforttl.html

Ruby: def self.f; end
来源：http://dali.zdqjudy.top/Article/details/gtrjygmbpi.html

C#:   public static void F() {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjdvvurcy.html

[G09] 接口 / 抽象类
来源：http://dali.zhongyouzk.top/Article/details/gtbsybpbcl.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.sysykeji.top/Article/details/gtyxaaownx.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.hnxiangtu.top/Article/details/gtolgpadfl.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.smart0.xyz/Article/details/gtflsctujg.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhiwuduotai.top/Article/details/gtcwpymlvv.html

Java: interface Shape { double area(); }
来源：http://dali.haohaochexian.top/Article/details/gtrhrzarka.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jinghuilouyu.cn/Article/details/gtwkfdspms.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jianghu66.top/Article/details/gtygxnczmt.html

C#:   interface IShape { double Area(); }
来源：http://dali.gzhubu.top/Article/details/gtpfuxzlby.html

[G10] 访问控制
来源：http://dali.pycfn.com/Article/details/gtfqepjmve.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.vqdsnc.cn/Article/details/gtsbxvfooh.html

PHP:  public / protected / private
来源：http://dali.bjfxy.top/Article/details/gtcexmulam.html

JS:   #private 字段；其余公开
来源：http://dali.daria6918.cn/Article/details/gtuopgzcsj.html

TS:   public / protected / private
来源：http://dali.shuidangran.top/Article/details/gtmugveeru.html

Java: public / protected / private / 默认包级
来源：http://dali.ehwqpu.com/Article/details/gtyadmgoqk.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hysaishi.cn/Article/details/gtibyuzmya.html

Ruby: public / protected / private
来源：http://dali.gzhubu.top/Article/details/gtlvungetn.html

C#:   public / protected / private / internal
来源：http://dali.pengpengdd.cyou/Article/details/gtmicyvvwo.html

[G11] getter / setter
来源：http://dali.zycfv.cn/Article/details/gtqnashkzd.html

Py:   @property 与 @x.setter
来源：http://dali.316326.xyz/Article/details/gtaigvaddr.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zdqjudy.top/Article/details/gtyhovlgdg.html

JS:   get name() { return this._name; }
来源：http://dali.chenzaomai.com/Article/details/gtccgxzpku.html

TS:   get name(): string { return this._name; }
来源：http://dali.jianghu66.top/Article/details/gtbeiswxvi.html

Java: public String getName() { return name; }
来源：http://dali.gaohongyu789.top/Article/details/gtvexurzly.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.shuidangran.top/Article/details/gthjbjprjx.html

Ruby: attr_accessor :name
来源：http://dali.daxiang520.top/Article/details/gtjgqtwsla.html

C#:   public string Name { get; set; }
来源：http://dali.wangdashe.top/Article/details/gtjulqjthq.html

[G12] 对象转字符串
来源：http://dali.daxiang520.top/Article/details/gtwkcukyxx.html

Py:   def __str__(self): return self.name
来源：http://dali.yj20258888.top/Article/details/gtfoxpfeeo.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.nanxinkj.top/Article/details/gtigsatdgn.html

JS:   toString() { return this.name; }
来源：http://dali.sweek.top/Article/details/gtlirsuotf.html

TS:   toString(): string { return this.name; }
来源：http://dali.hywenlv.cn/Article/details/gtpcyiundb.html

Java: @Override public String toString() { return name; }
来源：http://dali.yonumen.top/Article/details/gtlsmhvlpa.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.chenzaomai.com/Article/details/gthyeuonto.html

Ruby: def to_s; @name; end
来源：http://dali.zdqjudy.top/Article/details/gtitnkahmx.html

C#:   public override string ToString() => Name;
来源：http://dali.vqdsnc.cn/Article/details/gtwfyhjrhx.html

[G13] 判断对象类型
来源：http://dali.snrcjt.cn/Article/details/gtwqfzfoxq.html

Py:   isinstance(u, User)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzknirtck.html

PHP:  $u instanceof User
来源：http://dali.hfpthk.cn/Article/details/gtzoxvmjse.html

JS:   u instanceof User
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgodlvqsg.html

TS:   u instanceof User
来源：http://dali.tanke756.top/Article/details/gtivzbukfm.html

Java: u instanceof User
来源：http://dali.hnxiangtu.top/Article/details/gtyyntvpbx.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.havefunace.top/Article/details/gtdrcmnrxl.html

Ruby: u.is_a?(User)
来源：http://dali.haohaochexian.top/Article/details/gtpobrnqrh.html

C#:   u is User
来源：http://dali.cucudq.cn/Article/details/gtipearjcg.html

[G14] 数据类 / record
来源：http://dali.jlsjyb.cn/Article/details/gtzvmjjmyr.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.ivvv.top/Article/details/gtqtuiddqj.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.fengsongda.top/Article/details/gtovxjmwrs.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.tanke756.top/Article/details/gtubecumtf.html

TS:   type User = { name: string; age: number };
来源：http://dali.cdnleiting.top/Article/details/gtmbuqekad.html

Java: record User(String name, int age) {}
来源：http://dali.zdqjudy.top/Article/details/gtqtxdizsd.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jinghuilouyu.cn/Article/details/gtjujnjszj.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.chenjidiqi.icu/Article/details/gtarzwzxda.html

C#:   record User(string Name, int Age);
来源：http://dali.ppjwa.cn/Article/details/gtkczopenz.html

[G15] 枚举
来源：http://dali.smart0.xyz/Article/details/gtczewblwf.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.wangdashe.top/Article/details/gthhbrohly.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.dianchejie.cn/Article/details/gtpltpbeef.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yangfankeji.com/Article/details/gtrmdgdfqh.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sufxvd.cn/Article/details/gtkneruime.html

Java: enum Color { RED, GREEN }
来源：http://dali.aibaodan.cn/Article/details/gtkbzrrjdu.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.nanxuanxn.top/Article/details/gttgwopvdu.html

Ruby: Color = %i[red green].freeze
来源：http://dali.bjfxy.top/Article/details/gtkmcuvkzu.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hammf.cn/Article/details/gtwezplznk.html

[G16] 对象转数组 / 字典
来源：http://dali.shanyushiyangkeji.top/Article/details/gtebjtdspx.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.kuanghao11.cn/Article/details/gtbbojcuxt.html

PHP:  get_object_vars($obj);
来源：http://dali.zhengqikj.top/Article/details/gthkkcoewd.html

JS:   Object.entries(obj)
来源：http://dali.dianchejie.cn/Article/details/gtlvjobvsd.html

TS:   Object.entries(obj)
来源：http://dali.fengsongda.top/Article/details/gtinaeqpff.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yonumen.top/Article/details/gttcenjtzj.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yj20258888.top/Article/details/gtznyzundr.html

Ruby: obj.instance_variables
来源：http://dali.aizwys.cn/Article/details/gtfegnehht.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.nanxinkj.top/Article/details/gtgwvkeabt.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gttrlspfyr.html

H. 异常与错误处理
来源：http://dali.tanke756.top/Article/details/gtgiisnlzd.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtukvtapkq.html

[H01] try / catch 基础
来源：http://dali.ybcxt.top/Article/details/gtpkqxfims.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.ivvv.top/Article/details/gteqrlbsrz.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyaxgzhnw.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gthbaiiyje.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.cashguo.top/Article/details/gtfxikyatl.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.sxryk.cn/Article/details/gtanxcbskd.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.shanyushiyangtech.top/Article/details/gthoccfvrc.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhixingplan.top/Article/details/gtoanvgdke.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.xuetiantiany.cn/Article/details/gtufhivcdo.html

[H02] finally / ensure 收尾
来源：http://dali.yj20258.top/Article/details/gtzdkzecgw.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.ydzc1.top/Article/details/gtwgcvlvee.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.guowangkeji.top/Article/details/gtiqpxfnou.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zycfv.cn/Article/details/gteetfqrev.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.chenzaomai.com/Article/details/gtvhjujazq.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jqgfzy.top/Article/details/gtjxzormdi.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.gotoacloud.top/Article/details/gtsljudbyk.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtczjcdhqm.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.guannengcc.top/Article/details/gtnczypxyz.html

[H03] 主动抛出异常
来源：http://dali.cheryme.top/Article/details/gtnhoyvpxl.html

Py:   raise ValueError("错误信息")
来源：http://dali.ehwqpu.com/Article/details/gtyiagcmey.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.xziqi.cn/Article/details/gtkjwmdhpb.html

JS:   throw new Error("错误信息");
来源：http://dali.jiagoushi.top/Article/details/gtfmadbarb.html

TS:   throw new Error("错误信息");
来源：http://dali.zdqjudy.top/Article/details/gtjcnizhno.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.ivvv.top/Article/details/gtsiwdgfxe.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.chenjidiqi.icu/Article/details/gttbozumue.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yuxming.cn/Article/details/gtmftizciw.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.bjfxy.top/Article/details/gtxmbgczhf.html

[H04] 自定义异常类型
来源：http://dali.yj20258.top/Article/details/gtfcexnzdm.html

Py:   class MyError(Exception): pass
来源：http://dali.gaohongyu789.top/Article/details/gtimlqksky.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhongyouzk.top/Article/details/gtyfcifjxv.html

JS:   class MyError extends Error {}
来源：http://dali.dashuyun.cn/Article/details/gtjcwlxpwr.html

TS:   class MyError extends Error {}
来源：http://dali.aizwys.cn/Article/details/gtnafevabq.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hywenlv.cn/Article/details/gtkhpezuis.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.pengpengdd.cyou/Article/details/gtaeqsuhwr.html

Ruby: class MyError < StandardError; end
来源：http://dali.cheryme.top/Article/details/gtvofpjdfy.html

C#:   class MyException : Exception {}
来源：http://dali.shzxlz.cn/Article/details/gtoaewgqbn.html

[H05] 捕获特定类型
来源：http://dali.hammf.cn/Article/details/gteqeloswc.html

Py:   except ValueError as e:
来源：http://dali.xuanzx.com/Article/details/gtroioxlek.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.wangshuangyany.cn/Article/details/gtwbyombdq.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhengqikj.top/Article/details/gtbbyrifke.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.tianlin.xyz/Article/details/gtkrtemenr.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hammf.cn/Article/details/gttewxkcsk.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zdqjudy.top/Article/details/gtjzayvvjl.html

Ruby: rescue ArgumentError => e
来源：http://dali.dianchejie.cn/Article/details/gtvpbzcxnd.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.redwolf501.top/Article/details/gtmvvfmcvj.html

[H06] 可选值 / 空值安全访问
来源：http://dali.guannengcc.top/Article/details/gtmkpvtdnv.html

Py:   value = d.get("k") or default
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuuyfcbtm.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhiwuduotai.top/Article/details/gtanjeazce.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.bjfxy.top/Article/details/gtjfvsbvtk.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zdqjudy.top/Article/details/gtmakmtkds.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.nanxinkj.top/Article/details/gtrhhukoij.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.gzhubu.top/Article/details/gtqeamyvjy.html

Ruby: d&.dig(:a, :b)
来源：http://dali.chenzaomai.com/Article/details/gttpcjwfhf.html

C#:   obj?.A?.B ?? default
来源：http://dali.shzxlz.cn/Article/details/gteuubjwcz.html

[H07] 断言
来源：http://dali.zhoulong.xyz/Article/details/gtunznozmn.html

Py:   assert x > 0, "必须为正"
来源：http://dali.aibaodan.cn/Article/details/gtqkxajknx.html

PHP:  assert($x > 0);
来源：http://dali.nanxinkj.top/Article/details/gtnevbncxz.html

JS:   console.assert(x > 0);
来源：http://dali.mhx1999.top/Article/details/gtwurnzeax.html

TS:   console.assert(x > 0);
来源：http://dali.guowangkeji.top/Article/details/gtfvbytysu.html

Java: assert x > 0 : "必须为正";
来源：http://dali.c1oappe.top/Article/details/gteqmvzltn.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.hongshengwenyu.top/Article/details/gtiklaxnoe.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.chenjidiqi.icu/Article/details/gtrtunkeay.html

C#:   Debug.Assert(x > 0);
来源：http://dali.iojbl.cn/Article/details/gtiwclumco.html

[H08] 获取错误信息与堆栈
来源：http://dali.yvedp.cn/Article/details/gtuqxqhvke.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.hammf.cn/Article/details/gthimregiq.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yj20258.top/Article/details/gtnzzyxwxk.html

JS:   e.message;  e.stack
来源：http://dali.xylfe.cn/Article/details/gtgrexqamf.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.xziqi.cn/Article/details/gtxgvznhpj.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.nanxinkj.top/Article/details/gtovsihqew.html

Go:   err.Error()
来源：http://dali.yuanzhike.top/Article/details/gtgpsvnbzg.html

Ruby: e.message;  e.backtrace
来源：http://dali.jinqigfzy.top/Article/details/gtrtxkcmzq.html

C#:   e.Message;  e.StackTrace
来源：http://dali.dashuyun.cn/Article/details/gtjsydjpua.html

[H09] 带错误码的异常
来源：http://dali.shanyushiyangtech.top/Article/details/gtxzsjqxmb.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhoulong.xyz/Article/details/gtzloyedhy.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.daria6918.cn/Article/details/gtuwyuodon.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.0kj1m.cn/Article/details/gtnmzilbef.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.quarkkingdee.top/Article/details/gtmkbitvaf.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjuwvnsip.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.wangshuangyany.cn/Article/details/gtltdmnllg.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.sufxvd.cn/Article/details/gtkkysnsyd.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.fzhhl.top/Article/details/gtxjxzcfop.html

[H10] 资源自动释放
来源：http://dali.dianchejie.cn/Article/details/gtukuqmyqk.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jianghu66.top/Article/details/gtlsptuupk.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jyoumei.cn/Article/details/gtkrrzsyjr.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhengqikj.top/Article/details/gtrrgmmhgp.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ywan-chungtsiang.top/Article/details/gthtjrycor.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hongshengwenyu.top/Article/details/gtrzrknpcv.html

Go:   defer f.Close()
来源：http://dali.smart0.xyz/Article/details/gttpemuzzq.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.xylfe.cn/Article/details/gtycgzfrqb.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcebfvcna.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtnigiolmg.html

I. 正则表达式
来源：http://dali.ivvv.top/Article/details/gtjekbbtil.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gthvkchusb.html

[I01] 判断是否匹配
来源：http://dali.jinghuilouyu.cn/Article/details/gtxgjlpwzt.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zdqjudy.top/Article/details/gtyuolrfci.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gtzecdnqcy.html

JS:   /\d+/.test(s)
来源：http://dali.chenzaomai.com/Article/details/gtsiqluctb.html

TS:   /\d+/.test(s)
来源：http://dali.hnqzz.top/Article/details/gtpzkstapi.html


<!-- 参考信息 -->