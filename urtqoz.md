代发 wailian999

Ruby: File.delete("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtmlmlbfte.html

C#:   File.Delete("a.txt");
来源：http://dali.yuxming.cn/Article/details/gtaisfurpa.html

[F07] 创建目录（含多级）
来源：http://dali.yj20258.top/Article/details/gtffvyvbgk.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.daxiang520.top/Article/details/gtxdhzagfg.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.aibaodan.cn/Article/details/gtcqovhpub.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jyoumei.cn/Article/details/gtbveyvftu.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sufxvd.cn/Article/details/gtrpdmwjmu.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gthdzmfpkl.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.sufxvd.cn/Article/details/gtjcjfxdbk.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.tianlin.xyz/Article/details/gtqajmxubm.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jianghu66.top/Article/details/gtdxrhmmel.html

[F08] 遍历目录
来源：http://dali.zycfv.cn/Article/details/gtppzbjxyb.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.andypj.xyz/Article/details/gtuweepdkn.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.shangyingyoupin.top/Article/details/gtvsirxvlx.html

JS:   fs.readdirSync("dir")
来源：http://dali.dashuyun.cn/Article/details/gtrmpgjxch.html

TS:   fs.readdirSync("dir")
来源：http://dali.tanke756.top/Article/details/gteqrcizgl.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhongyouzk.top/Article/details/gtocffwfos.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.cucudq.cn/Article/details/gtnjiixwbu.html

Ruby: Dir.children("dir")
来源：http://dali.yangfankeji.com/Article/details/gtpdprglgz.html

C#:   Directory.GetFiles("dir")
来源：http://dali.feifeiyinyue.top/Article/details/gtbdwmnlni.html

[F09] 获取文件大小
来源：http://dali.pengpengdd.cyou/Article/details/gtmsesfgqr.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtejfxzriw.html

PHP:  filesize("a.txt");
来源：http://dali.snrcjt.cn/Article/details/gtbzsxeicq.html

JS:   fs.statSync("a.txt").size
来源：http://dali.cashguo.top/Article/details/gthtpchtjt.html

TS:   fs.statSync("a.txt").size
来源：http://dali.redwolf501.top/Article/details/gtiizccnvz.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.c1oappe.top/Article/details/gtrcmnerdz.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zycfv.cn/Article/details/gtkedrooyz.html

Ruby: File.size("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtobhyzjhk.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.hongshengwenyu.top/Article/details/gthuqgqywi.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zycfv.cn/Article/details/gtqyannsbs.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtuucymqrb.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.sysykeji.top/Article/details/gtqsyplsaf.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.cheryme.top/Article/details/gtdkdbnros.html

TS:   path.extname("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtcrghijws.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.gogol.net.cn/Article/details/gtnckpyukn.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.guannengcc.top/Article/details/gtuxgoatir.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yuxming.cn/Article/details/gtdnkeumuz.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.sysykeji.top/Article/details/gtbrlsvuvw.html

[F11] 复制与移动文件
来源：http://dali.aizwys.cn/Article/details/gtpciudgju.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtqkvsgdpd.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.ppjwa.cn/Article/details/gtznrjlhtb.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.haohaochexian.top/Article/details/gtgqqqlqbf.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hnqzz.top/Article/details/gtuaqtuhkp.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.feifeiyinyue.top/Article/details/gtpifowafl.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.chenzaomai.com/Article/details/gtroailnqw.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.gotoacloud.top/Article/details/gtqduybvvo.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jiagoushi.top/Article/details/gtahcppnex.html

[F12] CSV 读写
来源：http://dali.zhixingplan.top/Article/details/gtlbjzvzci.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdvebuyzy.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jinqigfzy.top/Article/details/gtzulqswbj.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.havefunace.top/Article/details/gtuzjhpqwk.html

TS:   // 同上
来源：http://dali.hywenlv.cn/Article/details/gtyzpypezt.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.daxiang520.top/Article/details/gtuukcaqnx.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhijiandao.cn/Article/details/gtoiapjntm.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.nwbrower.top/Article/details/gtqsvtvqbk.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jlsjyb.cn/Article/details/gtxcemrpud.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtkoqthyov.html

G. 面向对象
来源：http://dali.316326.xyz/Article/details/gtmphwbfoj.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtapldmmzg.html

[G01] 定义类
来源：http://dali.xylfe.cn/Article/details/gttvpwfbil.html

Py:   class User: pass
来源：http://dali.pengpengdd.cyou/Article/details/gthpieaoeg.html

PHP:  class User {}
来源：http://dali.redwolf501.top/Article/details/gtbpjvzhnq.html

JS:   class User {}
来源：http://dali.pengpengdd.cyou/Article/details/gtcunttpkp.html

TS:   class User { name: string = ""; }
来源：http://dali.pengpengdd.cyou/Article/details/gtmpknyjav.html

Java: class User {}
来源：http://dali.ydzc1.top/Article/details/gtgbjehnke.html

Go:   type User struct { Name string }
来源：http://dali.shuidangran.top/Article/details/gtpqhovlmt.html

Ruby: class User; end
来源：http://dali.yuanzhike.top/Article/details/gtlcqddjtt.html

C#:   class User {}
来源：http://dali.9152youxi.cn/Article/details/gtahmhljsh.html

[G02] 构造函数
来源：http://dali.birdmap.top/Article/details/gtybsycltk.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yvedp.cn/Article/details/gtlniwhxym.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.meibo888.top/Article/details/gthdkcaijq.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ydzc1.top/Article/details/gttfjwvhnm.html

TS:   constructor(public name: string) {}
来源：http://dali.hysaishi.cn/Article/details/gtxpnqfxgw.html

Java: User(String name) { this.name = name; }
来源：http://dali.9152youxi.cn/Article/details/gtqcnlzxgs.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhoulong.xyz/Article/details/gtvsyjkhkw.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hammf.cn/Article/details/gtromkkify.html

C#:   public User(string name) { Name = name; }
来源：http://dali.tianlin.xyz/Article/details/gtrfejfkqu.html

[G03] 实例属性
来源：http://dali.shuidangran.top/Article/details/gtyhrrurcq.html

Py:   self.name = "x"
来源：http://dali.xuanzx.com/Article/details/gtxilsbvbi.html

PHP:  public string $name = "x";
来源：http://dali.quarkkingdee.top/Article/details/gtkgkevebu.html

JS:   this.name = "x";
来源：http://dali.wangdashe.top/Article/details/gteevuxilf.html

TS:   name: string = "x";
来源：http://dali.hongshengwenyu.top/Article/details/gthuzxwrcu.html

Java: private String name;
来源：http://dali.cucudq.cn/Article/details/gtfroviuxw.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.daria6918.cn/Article/details/gtrdhkwryc.html

Ruby: @name = "x"
来源：http://dali.yvedp.cn/Article/details/gtzcjplydh.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jinghuilouyu.cn/Article/details/gtvvehubzo.html

[G04] 定义方法
来源：http://dali.jqgufenzy.top/Article/details/gtlkyinabg.html

Py:   def greet(self): return self.name
来源：http://dali.feifeiyinyue.top/Article/details/gtzjioekht.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.xinyue.icu/Article/details/gtjcgzrfam.html

JS:   greet() { return this.name; }
来源：http://dali.daxiang520.top/Article/details/gtjyieuqfi.html

TS:   greet(): string { return this.name; }
来源：http://dali.daria6918.cn/Article/details/gtlhdlxrzr.html

Java: String greet() { return name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtykaxcxqq.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hnqzz.top/Article/details/gtjhkckkgk.html

Ruby: def greet; @name; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtcntyuetz.html

C#:   public string Greet() => Name;
来源：http://dali.xziqi.cn/Article/details/gtnhqpgjim.html

[G05] 继承
来源：http://dali.aibaodan.cn/Article/details/gtonthcoxj.html

Py:   class Admin(User): pass
来源：http://dali.cashguo.top/Article/details/gtitvlwkua.html

PHP:  class Admin extends User {}
来源：http://dali.svipenyu.cn/Article/details/gtzbixwnqw.html

JS:   class Admin extends User {}
来源：http://dali.fengsongda.top/Article/details/gtcnvkniqi.html

TS:   class Admin extends User {}
来源：http://dali.jlsjyb.cn/Article/details/gtcpedllhz.html

Java: class Admin extends User {}
来源：http://dali.ydzc1.top/Article/details/gtxvucytnh.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.gzhubu.top/Article/details/gtfaqqucxa.html

Ruby: class Admin < User; end
来源：http://dali.svipenyu.cn/Article/details/gtivmgeddu.html

C#:   class Admin : User {}
来源：http://dali.wangdashe.top/Article/details/gtyqtqwcjo.html

[G06] 重写方法
来源：http://dali.nanxuanxn.top/Article/details/gtoiqtkhan.html

Py:   def greet(self): return "admin"
来源：http://dali.chenzaomai.com/Article/details/gtjrxkjwzc.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhixingplan.top/Article/details/gttvvsqskw.html

JS:   greet() { return "admin"; }
来源：http://dali.dianchejie.cn/Article/details/gtdcssixil.html

TS:   greet(): string { return "admin"; }
来源：http://dali.ehwqpu.com/Article/details/gtdfonfbhx.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.c1oappe.top/Article/details/gtkohmtlzk.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.tian-w.cn/Article/details/gtskwfdhhp.html

Ruby: def greet; "admin"; end
来源：http://dali.jqgufenzy.top/Article/details/gtxffmtbxn.html

C#:   public override string Greet() => "admin";
来源：http://dali.wangshuangyany.cn/Article/details/gtnsekgwwq.html

[G07] 调用父类方法
来源：http://dali.zycfv.cn/Article/details/gtfzluerxs.html

Py:   super().greet()
来源：http://dali.guannengcc.top/Article/details/gtsmypikcy.html

PHP:  parent::greet();
来源：http://dali.quarkkingdee.top/Article/details/gtpobqevkg.html

JS:   super.greet();
来源：http://dali.gogol.net.cn/Article/details/gtbahduine.html

TS:   super.greet();
来源：http://dali.wangshuangyany.cn/Article/details/gtkkplwxpx.html

Java: super.greet();
来源：http://dali.nwbrower.top/Article/details/gtaeiqkrbw.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.meibo888.top/Article/details/gtjrzrfyru.html

Ruby: super
来源：http://dali.birdmap.top/Article/details/gtofrvgchr.html

C#:   base.Greet();
来源：http://dali.gzhubu.top/Article/details/gtnbkptohw.html

[G08] 静态方法与属性
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmasyejtl.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.iojbl.cn/Article/details/gtikiculxn.html

PHP:  public static function f() {}
来源：http://dali.meibo888.top/Article/details/gtufohdzjq.html

JS:   static f() {}
来源：http://dali.hnxiangtu.top/Article/details/gtcbzxbndd.html

TS:   static f(): void {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gthrletgre.html

Java: static void f() {}
来源：http://dali.hnqzz.top/Article/details/gtppvrpjpf.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.guannengcc.top/Article/details/gtaqgbyohr.html

Ruby: def self.f; end
来源：http://dali.guowangkeji.top/Article/details/gtttowfzlg.html

C#:   public static void F() {}
来源：http://dali.hysaishi.cn/Article/details/gtazrnvuzc.html

[G09] 接口 / 抽象类
来源：http://dali.aizwys.cn/Article/details/gtxozhxjmu.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.ivvv.top/Article/details/gtukufptei.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.smart0.xyz/Article/details/gtsxnlfjzb.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yvedp.cn/Article/details/gtoobqzwgo.html

TS:   interface Shape { area(): number; }
来源：http://dali.shanyushiyangtech.top/Article/details/gthfvnofrv.html

Java: interface Shape { double area(); }
来源：http://dali.cqqwz.cn/Article/details/gttrjtkvxl.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.shanyushiyangtech.top/Article/details/gtwdgqfhob.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.c1oappe.top/Article/details/gtzetpekht.html

C#:   interface IShape { double Area(); }
来源：http://dali.cheryme.top/Article/details/gtosltlzaz.html

[G10] 访问控制
来源：http://dali.cqqwz.cn/Article/details/gtiwxpbdjj.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.guannengcc.top/Article/details/gtpneigclr.html

PHP:  public / protected / private
来源：http://dali.xinyue.icu/Article/details/gtwudmcvmm.html

JS:   #private 字段；其余公开
来源：http://dali.feifeiyinyue.top/Article/details/gtjktvmsjq.html

TS:   public / protected / private
来源：http://dali.bjfxy.top/Article/details/gtqpycneyb.html

Java: public / protected / private / 默认包级
来源：http://dali.jlsjyb.cn/Article/details/gtsyyqbnfl.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.andypj.xyz/Article/details/gtlyuvhfaw.html

Ruby: public / protected / private
来源：http://dali.xuanzx.com/Article/details/gtxjshthjj.html

C#:   public / protected / private / internal
来源：http://dali.gaohongyu789.top/Article/details/gtokiqdnmv.html

[G11] getter / setter
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbjlulkil.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gtljzlqbta.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.wangdashe.top/Article/details/gtqxhlmzgg.html

JS:   get name() { return this._name; }
来源：http://dali.shuidangran.top/Article/details/gtpvuvyohl.html

TS:   get name(): string { return this._name; }
来源：http://dali.c1oappe.top/Article/details/gtgpgcixea.html

Java: public String getName() { return name; }
来源：http://dali.yuanzhike.top/Article/details/gtcaofvuwp.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zdqjudy.top/Article/details/gtgyiophsl.html

Ruby: attr_accessor :name
来源：http://dali.jinqigufen.top/Article/details/gtpdwfyhev.html

C#:   public string Name { get; set; }
来源：http://dali.vqdsnc.cn/Article/details/gtarwxevxk.html

[G12] 对象转字符串
来源：http://dali.gaohongyu789.top/Article/details/gtiagbyljf.html

Py:   def __str__(self): return self.name
来源：http://dali.shanyushiyangtech.top/Article/details/gtqragjiyy.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.ivvv.top/Article/details/gtzdkgzmid.html

JS:   toString() { return this.name; }
来源：http://dali.yueranfly.top/Article/details/gtzpdlunmb.html

TS:   toString(): string { return this.name; }
来源：http://dali.jinqigfzy.top/Article/details/gtaznbcwhy.html

Java: @Override public String toString() { return name; }
来源：http://dali.tian-w.cn/Article/details/gtmyaovjje.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yuxming.cn/Article/details/gtqwstrefa.html

Ruby: def to_s; @name; end
来源：http://dali.shzxlz.cn/Article/details/gttiekcooc.html

C#:   public override string ToString() => Name;
来源：http://dali.shuidangran.top/Article/details/gtfxbuvzws.html

[G13] 判断对象类型
来源：http://dali.havefunace.top/Article/details/gtskblyflk.html

Py:   isinstance(u, User)
来源：http://dali.ydzc1.top/Article/details/gtbrltpjji.html

PHP:  $u instanceof User
来源：http://dali.aibaodan.cn/Article/details/gtyvmgtucy.html

JS:   u instanceof User
来源：http://dali.dashuyun.cn/Article/details/gtgmgqabjs.html

TS:   u instanceof User
来源：http://dali.quarkkingdee.top/Article/details/gtivxzkgat.html

Java: u instanceof User
来源：http://dali.zhixingplan.top/Article/details/gtujjkztfh.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.iojbl.cn/Article/details/gtdipzeycu.html

Ruby: u.is_a?(User)
来源：http://dali.meibo888.top/Article/details/gtabaxzztm.html

C#:   u is User
来源：http://dali.cucudq.cn/Article/details/gtupawrrpo.html

[G14] 数据类 / record
来源：http://dali.jlsjyb.cn/Article/details/gtgsxdftzk.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.gotoacloud.top/Article/details/gtrlnlnekj.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.xuetiantiany.cn/Article/details/gthzrzyyoq.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.cheryme.top/Article/details/gtjjzfiovy.html

TS:   type User = { name: string; age: number };
来源：http://dali.hnxiangtu.top/Article/details/gtpwpnhpqz.html

Java: record User(String name, int age) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtzcaxiprf.html

Go:   type User struct { Name string; Age int }
来源：http://dali.fengsongda.top/Article/details/gtffhecqsb.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.sysykeji.top/Article/details/gtwaxbyuyr.html

C#:   record User(string Name, int Age);
来源：http://dali.ybcxt.top/Article/details/gtlgktzwzc.html

[G15] 枚举
来源：http://dali.pycfn.com/Article/details/gtulqupuel.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.snrcjt.cn/Article/details/gtsqpersnm.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yueranfly.top/Article/details/gtogolnwye.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.wangdashe.top/Article/details/gttsbhrqqy.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.316326.xyz/Article/details/gtxgzuxyan.html

Java: enum Color { RED, GREEN }
来源：http://dali.snrcjt.cn/Article/details/gtszfhmvvq.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.316326.xyz/Article/details/gtfxggeabr.html

Ruby: Color = %i[red green].freeze
来源：http://dali.hammf.cn/Article/details/gtitpbkcjk.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.havefunace.top/Article/details/gtmtbjrswg.html

[G16] 对象转数组 / 字典
来源：http://dali.ydzc1.top/Article/details/gtzqdrberw.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhixingplan.top/Article/details/gtmymqjzit.html

PHP:  get_object_vars($obj);
来源：http://dali.cqqwz.cn/Article/details/gtyievkwhu.html

JS:   Object.entries(obj)
来源：http://dali.yangfankeji.com/Article/details/gtiwpqtpsk.html

TS:   Object.entries(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwoicqdhj.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.cucudq.cn/Article/details/gtymoyjnuc.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.xziqi.cn/Article/details/gtpabzpkoq.html

Ruby: obj.instance_variables
来源：http://dali.aizwys.cn/Article/details/gtvuoxdofq.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hnqzz.top/Article/details/gtpckvsiby.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtinqdgeio.html

H. 异常与错误处理
来源：http://dali.redwolf501.top/Article/details/gtktvgobkj.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtlozswrmz.html

[H01] try / catch 基础
来源：http://dali.sxryk.cn/Article/details/gtpbbhvixm.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.xuetiantiany.cn/Article/details/gtrgeoxoyq.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.hammf.cn/Article/details/gtzhmvqxhw.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhengqikj.top/Article/details/gtevweswuj.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqrpmbxsz.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.xylfe.cn/Article/details/gthoxsffzc.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jlsjyb.cn/Article/details/gtbanbeeyq.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.birdmap.top/Article/details/gtusdwnuog.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.gotoacloud.top/Article/details/gttdrpeekv.html

[H02] finally / ensure 收尾
来源：http://dali.nanxuanxn.top/Article/details/gtvmpilzda.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.chenlongwang.top/Article/details/gtshcjavqv.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqclseetg.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yvedp.cn/Article/details/gttoggjdio.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.fzhhl.top/Article/details/gtxlpuesrb.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtysxqfgrq.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jiagoushi.top/Article/details/gtottcwlbv.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.wangshuangyany.cn/Article/details/gtshxxaftv.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.tanke756.top/Article/details/gtxpfqeqll.html

[H03] 主动抛出异常
来源：http://dali.daria6918.cn/Article/details/gtjskkcqoo.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhengqikj.top/Article/details/gtwiwvszdq.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.sxryk.cn/Article/details/gtfbkkphvd.html

JS:   throw new Error("错误信息");
来源：http://dali.jyoumei.cn/Article/details/gtjzbrvlbu.html

TS:   throw new Error("错误信息");
来源：http://dali.dianchejie.cn/Article/details/gthuumvqqr.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hongshengwenyu.top/Article/details/gtqzmxvuwt.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jqgufenzy.top/Article/details/gtnrlsnzly.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.sweek.top/Article/details/gtjjcubpxo.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.andypj.xyz/Article/details/gtlcpgalrg.html

[H04] 自定义异常类型
来源：http://dali.aizwys.cn/Article/details/gtdofhfgqa.html

Py:   class MyError(Exception): pass
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxejncxgl.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.cashguo.top/Article/details/gtgpanmjyk.html

JS:   class MyError extends Error {}
来源：http://dali.gaohongyu789.top/Article/details/gtuaopahes.html

TS:   class MyError extends Error {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvhqgaduv.html

Java: class MyException extends RuntimeException {}
来源：http://dali.wangdashe.top/Article/details/gtsejlpize.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.haohaochexian.top/Article/details/gtqpubzujx.html

Ruby: class MyError < StandardError; end
来源：http://dali.cheryme.top/Article/details/gtprmjjoxe.html

C#:   class MyException : Exception {}
来源：http://dali.xinyue.icu/Article/details/gtllywgajn.html

[H05] 捕获特定类型
来源：http://dali.tian-w.cn/Article/details/gthixolraf.html

Py:   except ValueError as e:
来源：http://dali.hywenlv.cn/Article/details/gtwhjqkmld.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.sxryk.cn/Article/details/gtbzlzyqcp.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zdqjudy.top/Article/details/gtixbgtkxv.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yonumen.top/Article/details/gtzvuznggq.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.gaohongyu789.top/Article/details/gtulwbgopb.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.ivvv.top/Article/details/gtcstllaup.html

Ruby: rescue ArgumentError => e
来源：http://dali.sysykeji.top/Article/details/gtekohohia.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hammf.cn/Article/details/gthrqvlqlu.html

[H06] 可选值 / 空值安全访问
来源：http://dali.ppjwa.cn/Article/details/gtlnglpgtm.html

Py:   value = d.get("k") or default
来源：http://dali.zhongyouzk.top/Article/details/gttayppibk.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yonumen.top/Article/details/gteuymxlgx.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.sweek.top/Article/details/gtuaweyuqv.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.chenzaomai.com/Article/details/gtazpupxwx.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yuxming.cn/Article/details/gtjjptspcf.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jianghu66.top/Article/details/gthnlejfbl.html

Ruby: d&.dig(:a, :b)
来源：http://dali.birdmap.top/Article/details/gtodhqwawa.html

C#:   obj?.A?.B ?? default
来源：http://dali.cashguo.top/Article/details/gtdbegjoil.html

[H07] 断言
来源：http://dali.yvedp.cn/Article/details/gtdsihfdhh.html

Py:   assert x > 0, "必须为正"
来源：http://dali.kuanghao11.cn/Article/details/gtxywrukyb.html

PHP:  assert($x > 0);
来源：http://dali.316326.xyz/Article/details/gtcmpajbzt.html

JS:   console.assert(x > 0);
来源：http://dali.jinqigfzy.top/Article/details/gtsczzzvas.html

TS:   console.assert(x > 0);
来源：http://dali.shangyingyoupin.top/Article/details/gthixxldwc.html

Java: assert x > 0 : "必须为正";
来源：http://dali.kuanghao11.cn/Article/details/gtbupzllcd.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.cdnleiting.top/Article/details/gtkrzalswm.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.nanxuanxn.top/Article/details/gthfxujdft.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hnxiangtu.top/Article/details/gtjeifulaf.html

[H08] 获取错误信息与堆栈
来源：http://dali.yueranfly.top/Article/details/gtgioctaxb.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.cashguo.top/Article/details/gtyodrdetd.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.birdmap.top/Article/details/gtaxgdrepy.html

JS:   e.message;  e.stack
来源：http://dali.hysaishi.cn/Article/details/gtvokayfvv.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.feifeiyinyue.top/Article/details/gtuuhdwcfz.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.shanyushiyangtech.top/Article/details/gthgirsxqx.html

Go:   err.Error()
来源：http://dali.jyoumei.cn/Article/details/gtqaadcegb.html

Ruby: e.message;  e.backtrace
来源：http://dali.zdqjudy.top/Article/details/gtcudgoypu.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hammf.cn/Article/details/gtweocekbr.html

[H09] 带错误码的异常
来源：http://dali.chenzaomai.com/Article/details/gthjzlwnfs.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yongpay.top/Article/details/gtodqhosqs.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.daxiang520.top/Article/details/gtedsuacyo.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqjgkvihj.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.bjfxy.top/Article/details/gtowetgmez.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.sufxvd.cn/Article/details/gtodgkpdsp.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zycfv.cn/Article/details/gtnlagwpor.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.pengpengdd.cyou/Article/details/gtyjztdsvn.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.cucudq.cn/Article/details/gtkccrbgcj.html

[H10] 资源自动释放
来源：http://dali.xuetiantiany.cn/Article/details/gtnlhxflsh.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.daxiang520.top/Article/details/gtevyvoodz.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jinqigfzy.top/Article/details/gttjdjaumk.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yj202588.top/Article/details/gtohjswkhk.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cqqwz.cn/Article/details/gtovwgyqtp.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.vqdsnc.cn/Article/details/gtdhsucsty.html

Go:   defer f.Close()
来源：http://dali.wangshuangyany.cn/Article/details/gtwtcovjgo.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.ehwqpu.com/Article/details/gtlzfbgehl.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.guowangkeji.top/Article/details/gtgaurrcxo.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtyfhhsrlf.html

I. 正则表达式
来源：http://dali.yvedp.cn/Article/details/gtwoyreizm.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtgzlldnup.html

[I01] 判断是否匹配
来源：http://dali.jinyuanbaomall.cn/Article/details/gtahwrnark.html


<!-- 参考信息 -->