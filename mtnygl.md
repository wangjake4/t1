代发 wailian999

Ruby: File.delete("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtpsbdnnuj.html

C#:   File.Delete("a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjxwlmudh.html

[F07] 创建目录（含多级）
来源：http://dali.cdnleiting.top/Article/details/gtkaiqyzqd.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.snrcjt.cn/Article/details/gtwrxgrval.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.redwolf501.top/Article/details/gtznjtrarg.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yanxiufei.cn/Article/details/gtiuponrhq.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yj20258888.top/Article/details/gtzhxdffwc.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.gotoacloud.top/Article/details/gttyzrqfdt.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.hongshengwenyu.top/Article/details/gtwmnwhsoe.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.chenjidiqi.icu/Article/details/gtmbprcfsn.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.gzhubu.top/Article/details/gtphhgdvpf.html

[F08] 遍历目录
来源：http://dali.zdqjudy.top/Article/details/gtbqtgoyoi.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.snrcjt.cn/Article/details/gtgttagiri.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yj20258.top/Article/details/gtofkxrnbm.html

JS:   fs.readdirSync("dir")
来源：http://dali.smart0.xyz/Article/details/gttyryanml.html

TS:   fs.readdirSync("dir")
来源：http://dali.yueranfly.top/Article/details/gtpvptgohh.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hnqzz.top/Article/details/gttagzvpfs.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.chenjidiqi.icu/Article/details/gtyvacrode.html

Ruby: Dir.children("dir")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoedfwtvm.html

C#:   Directory.GetFiles("dir")
来源：http://dali.ybcxt.top/Article/details/gtusqwsian.html

[F09] 获取文件大小
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiyxnndkc.html

Py:   os.path.getsize("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtajcipaxi.html

PHP:  filesize("a.txt");
来源：http://dali.xziqi.cn/Article/details/gtxthfzomg.html

JS:   fs.statSync("a.txt").size
来源：http://dali.nanxinkj.top/Article/details/gtxdrqixuo.html

TS:   fs.statSync("a.txt").size
来源：http://dali.xziqi.cn/Article/details/gtthxhbqnl.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.pengpengdd.cyou/Article/details/gtkaymvhnb.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zdqjudy.top/Article/details/gtlbblomop.html

Ruby: File.size("a.txt")
来源：http://dali.yongpay.top/Article/details/gtbdhlndmm.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgsxlzlpw.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hywenlv.cn/Article/details/gtwehlbujr.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.c1oappe.top/Article/details/gtfjphvbbs.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gtegtakypc.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.wangdashe.top/Article/details/gtpxylfmpm.html

TS:   path.extname("a.txt")
来源：http://dali.birdmap.top/Article/details/gtjutlelgc.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.nanxinkj.top/Article/details/gttrecbrjy.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtxfrpjwbm.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtohvutqdq.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtlwzxzlsc.html

[F11] 复制与移动文件
来源：http://dali.pycfn.com/Article/details/gtlyfkktsn.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.0kj1m.cn/Article/details/gtcucjvyby.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gtzivqmnsa.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ehwqpu.com/Article/details/gtakwwjiyv.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yangfankeji.com/Article/details/gthmwzxrqj.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.bjfxy.top/Article/details/gtylqdpgfh.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.gaohongyu789.top/Article/details/gtcvojplap.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.cucudq.cn/Article/details/gtmdotdfgw.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.bjfxy.top/Article/details/gtmgxqfgnk.html

[F12] CSV 读写
来源：http://dali.xuetiantiany.cn/Article/details/gtexaknmuz.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hywenlv.cn/Article/details/gtmjykrvgz.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yangfankeji.com/Article/details/gtgjlmnfia.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hammf.cn/Article/details/gtlgrmnrxz.html

TS:   // 同上
来源：http://dali.c1oappe.top/Article/details/gtjjsybtib.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hammf.cn/Article/details/gtsgkunmar.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.tanke756.top/Article/details/gtpensuojh.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jinqigufen.top/Article/details/gtidqorvhe.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwgggllco.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtaiytikzy.html

G. 面向对象
来源：http://dali.shangyingyoupin.top/Article/details/gthnksfely.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtylfrkcgm.html

[G01] 定义类
来源：http://dali.yuanzhike.top/Article/details/gtelstqhju.html

Py:   class User: pass
来源：http://dali.meibo888.top/Article/details/gtcbbhftoi.html

PHP:  class User {}
来源：http://dali.yvedp.cn/Article/details/gtxzmfpqhd.html

JS:   class User {}
来源：http://dali.hnxiangtu.top/Article/details/gtwsuzxyjc.html

TS:   class User { name: string = ""; }
来源：http://dali.iojbl.cn/Article/details/gtcbyzlxkr.html

Java: class User {}
来源：http://dali.andypj.xyz/Article/details/gtkgcoxyym.html

Go:   type User struct { Name string }
来源：http://dali.jiagoushi.top/Article/details/gtcufkvzzx.html

Ruby: class User; end
来源：http://dali.dashuyun.cn/Article/details/gtpdmlcawj.html

C#:   class User {}
来源：http://dali.316326.xyz/Article/details/gthalxlojw.html

[G02] 构造函数
来源：http://dali.yj202588.top/Article/details/gtsqqpdjox.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhoulong.xyz/Article/details/gtxxtdntxk.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hfpthk.cn/Article/details/gtohgliwyz.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yonumen.top/Article/details/gtxthfmulw.html

TS:   constructor(public name: string) {}
来源：http://dali.dianchejie.cn/Article/details/gtpgmdbjno.html

Java: User(String name) { this.name = name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtjtjredde.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.tianlin.xyz/Article/details/gtwrbfftip.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.cqqwz.cn/Article/details/gtxijsdrwg.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jqgfzy.top/Article/details/gtpebapbke.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gtrfnqyksl.html

Py:   self.name = "x"
来源：http://dali.yvedp.cn/Article/details/gtxqhyxjob.html

PHP:  public string $name = "x";
来源：http://dali.chenjidiqi.icu/Article/details/gtaitysuwz.html

JS:   this.name = "x";
来源：http://dali.hnqzz.top/Article/details/gtajwssqcl.html

TS:   name: string = "x";
来源：http://dali.birdmap.top/Article/details/gtpgmlvmwe.html

Java: private String name;
来源：http://dali.hammf.cn/Article/details/gtberwcfvf.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.wangdashe.top/Article/details/gtikvyimfi.html

Ruby: @name = "x"
来源：http://dali.yongpay.top/Article/details/gtdeusrpnq.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.gaohongyu789.top/Article/details/gtkwvwozpn.html

[G04] 定义方法
来源：http://dali.smart0.xyz/Article/details/gtriaqyjbi.html

Py:   def greet(self): return self.name
来源：http://dali.sufxvd.cn/Article/details/gtzifvycbo.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.fengsongda.top/Article/details/gtjbvjmnrj.html

JS:   greet() { return this.name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtlvawodrz.html

TS:   greet(): string { return this.name; }
来源：http://dali.hnxiangtu.top/Article/details/gtzsdofior.html

Java: String greet() { return name; }
来源：http://dali.sufxvd.cn/Article/details/gtmhjwotxz.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.havefunace.top/Article/details/gtufxtawmz.html

Ruby: def greet; @name; end
来源：http://dali.svipenyu.cn/Article/details/gtclvzvont.html

C#:   public string Greet() => Name;
来源：http://dali.zhixingplan.top/Article/details/gtwoldkhvq.html

[G05] 继承
来源：http://dali.dashuyun.cn/Article/details/gtiubidgxv.html

Py:   class Admin(User): pass
来源：http://dali.shuidangran.top/Article/details/gtdibjicdm.html

PHP:  class Admin extends User {}
来源：http://dali.xuanzx.com/Article/details/gtttafhzov.html

JS:   class Admin extends User {}
来源：http://dali.zycfv.cn/Article/details/gtaqeschij.html

TS:   class Admin extends User {}
来源：http://dali.yj20258888.top/Article/details/gtcvkaghqz.html

Java: class Admin extends User {}
来源：http://dali.wangdashe.top/Article/details/gtybncxajl.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.pycfn.com/Article/details/gtzvsjctur.html

Ruby: class Admin < User; end
来源：http://dali.nwbrower.top/Article/details/gtifubmvyv.html

C#:   class Admin : User {}
来源：http://dali.jqgfzy.top/Article/details/gtjkmhsdds.html

[G06] 重写方法
来源：http://dali.gzhubu.top/Article/details/gtdcsmzvyw.html

Py:   def greet(self): return "admin"
来源：http://dali.shuidangran.top/Article/details/gtrxbyrdeh.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.shzxlz.cn/Article/details/gtcuqrbapq.html

JS:   greet() { return "admin"; }
来源：http://dali.redwolf501.top/Article/details/gthjyyhwoi.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjqlemfae.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.dashuyun.cn/Article/details/gtncyipbpb.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.chenzaomai.com/Article/details/gtokkvlvur.html

Ruby: def greet; "admin"; end
来源：http://dali.chenzaomai.com/Article/details/gtlklolcbl.html

C#:   public override string Greet() => "admin";
来源：http://dali.shzxlz.cn/Article/details/gtynenmzjr.html

[G07] 调用父类方法
来源：http://dali.zhixingplan.top/Article/details/gtlsppylfa.html

Py:   super().greet()
来源：http://dali.ivvv.top/Article/details/gtzbmfpsnt.html

PHP:  parent::greet();
来源：http://dali.nanxinkj.top/Article/details/gtzhniuduq.html

JS:   super.greet();
来源：http://dali.zdqjudy.top/Article/details/gtsijcxybc.html

TS:   super.greet();
来源：http://dali.jinqigfzy.top/Article/details/gtuewazkbk.html

Java: super.greet();
来源：http://dali.svipenyu.cn/Article/details/gtaiucvkqi.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.shuidangran.top/Article/details/gtxpzpvtkf.html

Ruby: super
来源：http://dali.pengpengdd.cyou/Article/details/gtazhjqieb.html

C#:   base.Greet();
来源：http://dali.gogol.net.cn/Article/details/gtraucpnwv.html

[G08] 静态方法与属性
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyvexmzhz.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.gzhubu.top/Article/details/gtbidjflme.html

PHP:  public static function f() {}
来源：http://dali.chenzaomai.com/Article/details/gtlsgemzdm.html

JS:   static f() {}
来源：http://dali.yj202588.top/Article/details/gtdqwpwglh.html

TS:   static f(): void {}
来源：http://dali.jqgfzy.top/Article/details/gtdjmkylvj.html

Java: static void f() {}
来源：http://dali.quarkkingdee.top/Article/details/gtfdsljruq.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hywenlv.cn/Article/details/gtiwkewlaz.html

Ruby: def self.f; end
来源：http://dali.hywenlv.cn/Article/details/gtpyqhrcop.html

C#:   public static void F() {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtjliyshxx.html

[G09] 接口 / 抽象类
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtonyhtokt.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.tianlin.xyz/Article/details/gtjdrpyfiw.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlrjdywrd.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.vqdsnc.cn/Article/details/gtivkjwysc.html

TS:   interface Shape { area(): number; }
来源：http://dali.nwbrower.top/Article/details/gtmntavaoq.html

Java: interface Shape { double area(); }
来源：http://dali.cdnleiting.top/Article/details/gtcegoreer.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.cdnleiting.top/Article/details/gtmexrxnfu.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.havefunace.top/Article/details/gtssludysc.html

C#:   interface IShape { double Area(); }
来源：http://dali.cucudq.cn/Article/details/gtdwfomqqu.html

[G10] 访问控制
来源：http://dali.gzhubu.top/Article/details/gtklpxxeza.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwmwthtbs.html

PHP:  public / protected / private
来源：http://dali.chenjidiqi.icu/Article/details/gtmebbgfvg.html

JS:   #private 字段；其余公开
来源：http://dali.yvedp.cn/Article/details/gtxhvacuos.html

TS:   public / protected / private
来源：http://dali.yonumen.top/Article/details/gtkfgeozrx.html

Java: public / protected / private / 默认包级
来源：http://dali.shuidangran.top/Article/details/gtawyndexk.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.nwbrower.top/Article/details/gtncnmejap.html

Ruby: public / protected / private
来源：http://dali.hongshengwenyu.top/Article/details/gtxfyqrlmf.html

C#:   public / protected / private / internal
来源：http://dali.chenlongwang.top/Article/details/gtepaaypys.html

[G11] getter / setter
来源：http://dali.jinqigfzy.top/Article/details/gtpkbjvxjx.html

Py:   @property 与 @x.setter
来源：http://dali.guowangkeji.top/Article/details/gtctycdoet.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.tianlin.xyz/Article/details/gtxxrtkycr.html

JS:   get name() { return this._name; }
来源：http://dali.gaohongyu789.top/Article/details/gtsmzvzxre.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhixingplan.top/Article/details/gtlkilgpyv.html

Java: public String getName() { return name; }
来源：http://dali.zhixingplan.top/Article/details/gtyyiefvls.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.fengsongda.top/Article/details/gttmbxwjqv.html

Ruby: attr_accessor :name
来源：http://dali.fengsongda.top/Article/details/gtlhvhnsue.html

C#:   public string Name { get; set; }
来源：http://dali.meibo888.top/Article/details/gtzntyzvxx.html

[G12] 对象转字符串
来源：http://dali.gogol.net.cn/Article/details/gtrheqxgzp.html

Py:   def __str__(self): return self.name
来源：http://dali.cheryme.top/Article/details/gtdfbeajmi.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtpwwcqzem.html

JS:   toString() { return this.name; }
来源：http://dali.nwbrower.top/Article/details/gtthojxsob.html

TS:   toString(): string { return this.name; }
来源：http://dali.yvedp.cn/Article/details/gtgjgtqmvh.html

Java: @Override public String toString() { return name; }
来源：http://dali.9152youxi.cn/Article/details/gtuezaqsab.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.ydzc1.top/Article/details/gtbeuhpeuf.html

Ruby: def to_s; @name; end
来源：http://dali.gaohongyu789.top/Article/details/gtxudjmbwz.html

C#:   public override string ToString() => Name;
来源：http://dali.316326.xyz/Article/details/gtahquwglj.html

[G13] 判断对象类型
来源：http://dali.yonumen.top/Article/details/gttzyedsbu.html

Py:   isinstance(u, User)
来源：http://dali.c1oappe.top/Article/details/gtpcrtqqab.html

PHP:  $u instanceof User
来源：http://dali.ywan-chungtsiang.top/Article/details/gtduymbtio.html

JS:   u instanceof User
来源：http://dali.hnqzz.top/Article/details/gtbzercpyo.html

TS:   u instanceof User
来源：http://dali.yj202588.top/Article/details/gtsyvfliau.html

Java: u instanceof User
来源：http://dali.yonumen.top/Article/details/gtmxlmuvbm.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.nwbrower.top/Article/details/gtdfdhmvhu.html

Ruby: u.is_a?(User)
来源：http://dali.aibaodan.cn/Article/details/gtvpzrmdxu.html

C#:   u is User
来源：http://dali.zhoulong.xyz/Article/details/gttybuidpc.html

[G14] 数据类 / record
来源：http://dali.yuxming.cn/Article/details/gtyfbvzdvt.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.ehwqpu.com/Article/details/gtnonumric.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwaxoiufa.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhoulong.xyz/Article/details/gtuzzmlgjt.html

TS:   type User = { name: string; age: number };
来源：http://dali.shzxlz.cn/Article/details/gtzhhhhglw.html

Java: record User(String name, int age) {}
来源：http://dali.cucudq.cn/Article/details/gthhbyxpim.html

Go:   type User struct { Name string; Age int }
来源：http://dali.xinyue.icu/Article/details/gthvuhtfjr.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.0kj1m.cn/Article/details/gtqligwagg.html

C#:   record User(string Name, int Age);
来源：http://dali.jianghu66.top/Article/details/gtmedosdxx.html

[G15] 枚举
来源：http://dali.chenjidiqi.icu/Article/details/gtpktlnkpe.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.aibaodan.cn/Article/details/gtczvwnplc.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.fengsongda.top/Article/details/gtxshouuzy.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.svipenyu.cn/Article/details/gtsbbjlodz.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yj202588.top/Article/details/gtvlrpceme.html

Java: enum Color { RED, GREEN }
来源：http://dali.yj20258.top/Article/details/gthymdreio.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yuanzhike.top/Article/details/gtbpsniavt.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ppjwa.cn/Article/details/gtqcnbrwfm.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gotoacloud.top/Article/details/gtgmwkokcb.html

[G16] 对象转数组 / 字典
来源：http://dali.yanxiufei.cn/Article/details/gtwlzreeri.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.bjfxy.top/Article/details/gtwcuoblns.html

PHP:  get_object_vars($obj);
来源：http://dali.fengsongda.top/Article/details/gtuczlsrxa.html

JS:   Object.entries(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gtomidxrbu.html

TS:   Object.entries(obj)
来源：http://dali.ivvv.top/Article/details/gtyhwzmfww.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.iojbl.cn/Article/details/gtfjwhowcv.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.nwbrower.top/Article/details/gtidknqxqk.html

Ruby: obj.instance_variables
来源：http://dali.pycfn.com/Article/details/gttnkjvwhw.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.shangyingyoupin.top/Article/details/gtorpmebzz.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtoibmoeen.html

H. 异常与错误处理
来源：http://dali.tanke756.top/Article/details/gtqoxpluqv.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtsujtyvqa.html

[H01] try / catch 基础
来源：http://dali.svipenyu.cn/Article/details/gtzhnrwtvd.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.meibo888.top/Article/details/gtmfnymbkq.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.daria6918.cn/Article/details/gtsivbnoxf.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.gotoacloud.top/Article/details/gtgeqsnwrg.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.kuanghao11.cn/Article/details/gtkduoywvs.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.quarkkingdee.top/Article/details/gtypndhdkp.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.mhx1999.top/Article/details/gtpiyyjjzd.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.shangyingyoupin.top/Article/details/gtwnnpmtpu.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.dashuyun.cn/Article/details/gtdfcojogq.html

[H02] finally / ensure 收尾
来源：http://dali.nanxinkj.top/Article/details/gtudbxwnhi.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zycfv.cn/Article/details/gtgiifmefw.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.ehwqpu.com/Article/details/gtdmdogqai.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.xuetiantiany.cn/Article/details/gtkyuagqfe.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtmluuojws.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.bjfxy.top/Article/details/gtuaaoxpsp.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yj202588.top/Article/details/gtqoqwwvkf.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.sweek.top/Article/details/gtnxxnbkpo.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yj20258888.top/Article/details/gtbdwuplgr.html

[H03] 主动抛出异常
来源：http://dali.yongpay.top/Article/details/gttadljoar.html

Py:   raise ValueError("错误信息")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfuziktaw.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.pengpengdd.cyou/Article/details/gtfyqezter.html

JS:   throw new Error("错误信息");
来源：http://dali.cashguo.top/Article/details/gtmffkmpiy.html

TS:   throw new Error("错误信息");
来源：http://dali.cheryme.top/Article/details/gtnbhopuqr.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.chenjidiqi.icu/Article/details/gtwxybwdev.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yangfankeji.com/Article/details/gtrifbrzmv.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhoulong.xyz/Article/details/gtfpcmrmam.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.wangdashe.top/Article/details/gtajlamriz.html

[H04] 自定义异常类型
来源：http://dali.gzhubu.top/Article/details/gtbzxxizmv.html

Py:   class MyError(Exception): pass
来源：http://dali.guowangkeji.top/Article/details/gtiehpmtbj.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.cashguo.top/Article/details/gtyouvupwp.html

JS:   class MyError extends Error {}
来源：http://dali.dianchejie.cn/Article/details/gtnppjdqyn.html

TS:   class MyError extends Error {}
来源：http://dali.gzhubu.top/Article/details/gtfqkyefbm.html

Java: class MyException extends RuntimeException {}
来源：http://dali.nwbrower.top/Article/details/gtfsgjvidx.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthrkzysmf.html

Ruby: class MyError < StandardError; end
来源：http://dali.quarkkingdee.top/Article/details/gtkctcnupn.html

C#:   class MyException : Exception {}
来源：http://dali.fzhhl.top/Article/details/gtlcftbzfw.html

[H05] 捕获特定类型
来源：http://dali.nwbrower.top/Article/details/gtmlzzszmj.html

Py:   except ValueError as e:
来源：http://dali.smart0.xyz/Article/details/gtlylmeyky.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.aizwys.cn/Article/details/gtpgudhsnp.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.aizwys.cn/Article/details/gtcbzixwew.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.hammf.cn/Article/details/gtxdvffvps.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jinqigufen.top/Article/details/gtgculjnnr.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.fzhhl.top/Article/details/gtmtzkwqyc.html

Ruby: rescue ArgumentError => e
来源：http://dali.feifeiyinyue.top/Article/details/gtwlrpdjta.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.pycfn.com/Article/details/gtfdrswnbg.html

[H06] 可选值 / 空值安全访问
来源：http://dali.sysykeji.top/Article/details/gttiouwszr.html

Py:   value = d.get("k") or default
来源：http://dali.zhixingplan.top/Article/details/gtafiakmww.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.sysykeji.top/Article/details/gtdycxqlvo.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.ywan-chungtsiang.top/Article/details/gtegcyfxib.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.shanyushiyangkeji.top/Article/details/gtroegxgte.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yanxiufei.cn/Article/details/gtvdyforje.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.redwolf501.top/Article/details/gtrcgzjgnw.html

Ruby: d&.dig(:a, :b)
来源：http://dali.guowangkeji.top/Article/details/gtxhmttcqq.html

C#:   obj?.A?.B ?? default
来源：http://dali.jyoumei.cn/Article/details/gteliksbse.html

[H07] 断言
来源：http://dali.dashuyun.cn/Article/details/gtbvjqtono.html

Py:   assert x > 0, "必须为正"
来源：http://dali.gogol.net.cn/Article/details/gtmobsmdue.html

PHP:  assert($x > 0);
来源：http://dali.pengpengdd.cyou/Article/details/gthzezqrln.html

JS:   console.assert(x > 0);
来源：http://dali.iojbl.cn/Article/details/gtrcawvfei.html

TS:   console.assert(x > 0);
来源：http://dali.nanxinkj.top/Article/details/gtnuiwmqah.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jianghu66.top/Article/details/gtpabwmhlx.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yj20258888.top/Article/details/gtpxkozkfd.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.0kj1m.cn/Article/details/gtzhbkkpyu.html

C#:   Debug.Assert(x > 0);
来源：http://dali.cdnleiting.top/Article/details/gtdpmacdcr.html

[H08] 获取错误信息与堆栈
来源：http://dali.yj20258.top/Article/details/gtxazlwizx.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.svipenyu.cn/Article/details/gtagprpquu.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yj202588.top/Article/details/gtahtdzvaz.html

JS:   e.message;  e.stack
来源：http://dali.nanxuanxn.top/Article/details/gtinewqnjg.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.dashuyun.cn/Article/details/gtyxfjgagc.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.nwbrower.top/Article/details/gtuwjmejof.html

Go:   err.Error()
来源：http://dali.shzxlz.cn/Article/details/gtrnjbhfic.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhijiandao.cn/Article/details/gtimibpqbu.html

C#:   e.Message;  e.StackTrace
来源：http://dali.sufxvd.cn/Article/details/gtxukqwqzc.html

[H09] 带错误码的异常
来源：http://dali.yangfankeji.com/Article/details/gtpnapcbhu.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jianghu66.top/Article/details/gtpkyrawxe.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.shangyingyoupin.top/Article/details/gtddxvcyvf.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jinghuilouyu.cn/Article/details/gtkuhaqxnx.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.ppjwa.cn/Article/details/gtybyhhmka.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.0kj1m.cn/Article/details/gtzrtempap.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.hfpthk.cn/Article/details/gtzremgexl.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.pengpengdd.cyou/Article/details/gtmrbjmatc.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.iojbl.cn/Article/details/gtptjyfmhc.html

[H10] 资源自动释放
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlibxwout.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhijiandao.cn/Article/details/gtadagoxbe.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.ybcxt.top/Article/details/gtjotkjmun.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hfpthk.cn/Article/details/gtmyolfnjr.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.snrcjt.cn/Article/details/gtktbrlcih.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.gzhubu.top/Article/details/gtyinmcthu.html

Go:   defer f.Close()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiqozfkfr.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.havefunace.top/Article/details/gtoytazzta.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yj20258.top/Article/details/gtqrtguodp.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmuuzvjzc.html

I. 正则表达式
来源：http://dali.smart0.xyz/Article/details/gtwqhnlpoc.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtnqcnkoqk.html

[I01] 判断是否匹配
来源：http://dali.zhongyouzk.top/Article/details/gtczecjron.html


<!-- 参考信息 -->