代发 wailian999

C#:   File.Exists("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtajtnydco.html

[F06] 删除文件
来源：http://dali.zhengqikj.top/Article/details/gtfluvnely.html

Py:   os.remove("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtvbhsurcz.html

PHP:  unlink("a.txt");
来源：http://dali.316326.xyz/Article/details/gtjljchkwy.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.birdmap.top/Article/details/gtpdsuafvf.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtbygbsdgb.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.cucudq.cn/Article/details/gtbdwiadcs.html

Go:   os.Remove("a.txt")
来源：http://dali.yongpay.top/Article/details/gtajjogefn.html

Ruby: File.delete("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtinlzbqos.html

C#:   File.Delete("a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gtrkwdtwbh.html

[F07] 创建目录（含多级）
来源：http://dali.guowangkeji.top/Article/details/gtacdoqcae.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.hysaishi.cn/Article/details/gtvkstrddt.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.dianchejie.cn/Article/details/gtflfjxzql.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.316326.xyz/Article/details/gtozuteozb.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xinyue.icu/Article/details/gtrcfswwzk.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hnxiangtu.top/Article/details/gtkwhtofer.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhiwuduotai.top/Article/details/gtmezmvsje.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhongyouzk.top/Article/details/gtdaftoiqw.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.cdnleiting.top/Article/details/gtsicmuvbv.html

[F08] 遍历目录
来源：http://dali.jiagoushi.top/Article/details/gtlzwqctjv.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yuanzhike.top/Article/details/gtesuumdam.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhoulong.xyz/Article/details/gtwiocuuor.html

JS:   fs.readdirSync("dir")
来源：http://dali.yj20258888.top/Article/details/gtpvafqelv.html

TS:   fs.readdirSync("dir")
来源：http://dali.jinqigufen.top/Article/details/gtyhfbdyba.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.chenzaomai.com/Article/details/gtnliwspba.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.ydzc1.top/Article/details/gtsjgxjnpp.html

Ruby: Dir.children("dir")
来源：http://dali.cqqwz.cn/Article/details/gtkqybjlrf.html

C#:   Directory.GetFiles("dir")
来源：http://dali.nanxinkj.top/Article/details/gtxmitdxcm.html

[F09] 获取文件大小
来源：http://dali.cashguo.top/Article/details/gtgxuqqxin.html

Py:   os.path.getsize("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtkzfqalkv.html

PHP:  filesize("a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gtxrusqozg.html

JS:   fs.statSync("a.txt").size
来源：http://dali.gogol.net.cn/Article/details/gtgadbcpzt.html

TS:   fs.statSync("a.txt").size
来源：http://dali.xuetiantiany.cn/Article/details/gtnfsqwzwp.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.hysaishi.cn/Article/details/gtebsgjnxg.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.sxryk.cn/Article/details/gtuozsmtsl.html

Ruby: File.size("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtueoiddml.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yuanzhike.top/Article/details/gtstqguxmd.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zdqjudy.top/Article/details/gtlecvvaqk.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.havefunace.top/Article/details/gtrfwnvevs.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.xylfe.cn/Article/details/gtpubtmbpk.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.cashguo.top/Article/details/gtijbibqra.html

TS:   path.extname("a.txt")
来源：http://dali.yj202588.top/Article/details/gtsjxixjbn.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.dashuyun.cn/Article/details/gtqhwxnozp.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.daria6918.cn/Article/details/gtjalcuptz.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqynaipsu.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.sysykeji.top/Article/details/gtvsjfvumw.html

[F11] 复制与移动文件
来源：http://dali.gzhubu.top/Article/details/gtinsdbaoq.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yueranfly.top/Article/details/gterjaibao.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.pycfn.com/Article/details/gtzcqvmhzn.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ybcxt.top/Article/details/gtdglzvghh.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xuanzx.com/Article/details/gtrfffebbw.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.tianlin.xyz/Article/details/gthrgiayug.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.chenlongwang.top/Article/details/gtymxqttzq.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.hnqzz.top/Article/details/gtqqfqhrnm.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.shangyingyoupin.top/Article/details/gtmavryitx.html

[F12] CSV 读写
来源：http://dali.jiagoushi.top/Article/details/gtlatwoxau.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hfpthk.cn/Article/details/gtoybxwkav.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jinghuilouyu.cn/Article/details/gtvatrncwx.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.redwolf501.top/Article/details/gtfucnttxp.html

TS:   // 同上
来源：http://dali.jqgufenzy.top/Article/details/gtuaqmhcfe.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jianghu66.top/Article/details/gtoprskqjs.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.vqdsnc.cn/Article/details/gtkboofujt.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jinghuilouyu.cn/Article/details/gthuxvmmez.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.0kj1m.cn/Article/details/gtzrdiylrz.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtyrqdzoko.html

G. 面向对象
来源：http://dali.jlsjyb.cn/Article/details/gthkljrbzf.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtbgyunjti.html

[G01] 定义类
来源：http://dali.nanxuanxn.top/Article/details/gtlltlynzn.html

Py:   class User: pass
来源：http://dali.cucudq.cn/Article/details/gtcrsfhnco.html

PHP:  class User {}
来源：http://dali.feifeiyinyue.top/Article/details/gtslnhzmuu.html

JS:   class User {}
来源：http://dali.chenlongwang.top/Article/details/gtrsaoqnkw.html

TS:   class User { name: string = ""; }
来源：http://dali.cqqwz.cn/Article/details/gtpmykiafc.html

Java: class User {}
来源：http://dali.yongpay.top/Article/details/gtavzauayf.html

Go:   type User struct { Name string }
来源：http://dali.yuanzhike.top/Article/details/gtakhpptzz.html

Ruby: class User; end
来源：http://dali.jqgufenzy.top/Article/details/gtqixorkuv.html

C#:   class User {}
来源：http://dali.xuetiantiany.cn/Article/details/gtztnccwcl.html

[G02] 构造函数
来源：http://dali.yonumen.top/Article/details/gtvxskihcl.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.havefunace.top/Article/details/gtdgczjfha.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.aizwys.cn/Article/details/gtwcxdisdj.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.xylfe.cn/Article/details/gtprioucrj.html

TS:   constructor(public name: string) {}
来源：http://dali.gzhubu.top/Article/details/gtjsnjibek.html

Java: User(String name) { this.name = name; }
来源：http://dali.pycfn.com/Article/details/gteumnzaos.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.andypj.xyz/Article/details/gtzyicofds.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.andypj.xyz/Article/details/gtstpqdedu.html

C#:   public User(string name) { Name = name; }
来源：http://dali.nwbrower.top/Article/details/gthbhabueh.html

[G03] 实例属性
来源：http://dali.zhoulong.xyz/Article/details/gtdltqaptw.html

Py:   self.name = "x"
来源：http://dali.yj20258.top/Article/details/gtspkjrvor.html

PHP:  public string $name = "x";
来源：http://dali.yvedp.cn/Article/details/gtqbgwukog.html

JS:   this.name = "x";
来源：http://dali.yonumen.top/Article/details/gtqrmjesaa.html

TS:   name: string = "x";
来源：http://dali.hfpthk.cn/Article/details/gtpcgtpxwr.html

Java: private String name;
来源：http://dali.snrcjt.cn/Article/details/gtkzuzrygo.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.shzxlz.cn/Article/details/gtdysdosak.html

Ruby: @name = "x"
来源：http://dali.fzhhl.top/Article/details/gtcjtxxffe.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.nwbrower.top/Article/details/gtyofduahm.html

[G04] 定义方法
来源：http://dali.quarkkingdee.top/Article/details/gthvbtpydz.html

Py:   def greet(self): return self.name
来源：http://dali.sxryk.cn/Article/details/gtorswifuf.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.xuanzx.com/Article/details/gtldzpfhgv.html

JS:   greet() { return this.name; }
来源：http://dali.ehwqpu.com/Article/details/gtwzietqps.html

TS:   greet(): string { return this.name; }
来源：http://dali.sysykeji.top/Article/details/gtecoidmca.html

Java: String greet() { return name; }
来源：http://dali.kuanghao11.cn/Article/details/gtvrhsyaao.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zycfv.cn/Article/details/gtzfavezgv.html

Ruby: def greet; @name; end
来源：http://dali.quarkkingdee.top/Article/details/gttfwjtlom.html

C#:   public string Greet() => Name;
来源：http://dali.yvedp.cn/Article/details/gtvsbcgzff.html

[G05] 继承
来源：http://dali.guannengcc.top/Article/details/gtktqtbayx.html

Py:   class Admin(User): pass
来源：http://dali.wangdashe.top/Article/details/gtjjsnrhfk.html

PHP:  class Admin extends User {}
来源：http://dali.zhiwuduotai.top/Article/details/gteoxhzexa.html

JS:   class Admin extends User {}
来源：http://dali.gzhubu.top/Article/details/gtbpdbqtua.html

TS:   class Admin extends User {}
来源：http://dali.cqqwz.cn/Article/details/gtooxvleio.html

Java: class Admin extends User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxogpolbh.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.shzxlz.cn/Article/details/gtrpnektbd.html

Ruby: class Admin < User; end
来源：http://dali.zhengqikj.top/Article/details/gtprriqcpw.html

C#:   class Admin : User {}
来源：http://dali.gzhubu.top/Article/details/gtespjansj.html

[G06] 重写方法
来源：http://dali.gotoacloud.top/Article/details/gtkxfunvjr.html

Py:   def greet(self): return "admin"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcizgodvi.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.ehwqpu.com/Article/details/gtrhicavtb.html

JS:   greet() { return "admin"; }
来源：http://dali.shuidangran.top/Article/details/gtfwytyvbm.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yuanzhike.top/Article/details/gtlxzxblvc.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yongpay.top/Article/details/gtbbdmtxrb.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.wangdashe.top/Article/details/gtmciwbrrn.html

Ruby: def greet; "admin"; end
来源：http://dali.aizwys.cn/Article/details/gtlmcgckxx.html

C#:   public override string Greet() => "admin";
来源：http://dali.sxryk.cn/Article/details/gtfrfqrprb.html

[G07] 调用父类方法
来源：http://dali.tianlin.xyz/Article/details/gtntmlkdbm.html

Py:   super().greet()
来源：http://dali.hysaishi.cn/Article/details/gtjsibumff.html

PHP:  parent::greet();
来源：http://dali.hongshengwenyu.top/Article/details/gtejeyhtvw.html

JS:   super.greet();
来源：http://dali.feifeiyinyue.top/Article/details/gtlzsvkwhg.html

TS:   super.greet();
来源：http://dali.meibo888.top/Article/details/gtpxxjazzm.html

Java: super.greet();
来源：http://dali.daxiang520.top/Article/details/gtqbzfybrt.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbkivfpyx.html

Ruby: super
来源：http://dali.ivvv.top/Article/details/gtbwjzikzr.html

C#:   base.Greet();
来源：http://dali.bjfxy.top/Article/details/gtkqewbrlj.html

[G08] 静态方法与属性
来源：http://dali.xziqi.cn/Article/details/gtztnbvdgm.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.gaohongyu789.top/Article/details/gteadnkqui.html

PHP:  public static function f() {}
来源：http://dali.quarkkingdee.top/Article/details/gttstayjwf.html

JS:   static f() {}
来源：http://dali.gaohongyu789.top/Article/details/gtifprcqvw.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gtrgrkmihm.html

Java: static void f() {}
来源：http://dali.aizwys.cn/Article/details/gtjfuklqbw.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hnxiangtu.top/Article/details/gtcskmtzpo.html

Ruby: def self.f; end
来源：http://dali.jqgufenzy.top/Article/details/gtfczupgje.html

C#:   public static void F() {}
来源：http://dali.yj20258.top/Article/details/gteiskunrw.html

[G09] 接口 / 抽象类
来源：http://dali.cashguo.top/Article/details/gtyfwpsdeh.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.guannengcc.top/Article/details/gtsypyuakn.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.hnxiangtu.top/Article/details/gtlhgiuvyv.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ybcxt.top/Article/details/gttigsusdd.html

TS:   interface Shape { area(): number; }
来源：http://dali.sxryk.cn/Article/details/gtbxukhgtw.html

Java: interface Shape { double area(); }
来源：http://dali.xylfe.cn/Article/details/gtebnyhphz.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.xziqi.cn/Article/details/gtugaqzklr.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.gogol.net.cn/Article/details/gtacnkswbm.html

C#:   interface IShape { double Area(); }
来源：http://dali.hysaishi.cn/Article/details/gtfjfwrccn.html

[G10] 访问控制
来源：http://dali.kuanghao11.cn/Article/details/gtkarvtpad.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jqgufenzy.top/Article/details/gtetakcufy.html

PHP:  public / protected / private
来源：http://dali.wangshuangyany.cn/Article/details/gtujzoxbnx.html

JS:   #private 字段；其余公开
来源：http://dali.svipenyu.cn/Article/details/gtivcrxtgu.html

TS:   public / protected / private
来源：http://dali.nanxinkj.top/Article/details/gtgcfowlpy.html

Java: public / protected / private / 默认包级
来源：http://dali.quarkkingdee.top/Article/details/gtuwzfycif.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.cucudq.cn/Article/details/gtbcdbtqxj.html

Ruby: public / protected / private
来源：http://dali.vqdsnc.cn/Article/details/gtrwsfntmo.html

C#:   public / protected / private / internal
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpivnvzyf.html

[G11] getter / setter
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqiyeexlf.html

Py:   @property 与 @x.setter
来源：http://dali.jinghuilouyu.cn/Article/details/gtdjumyxkb.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhoulong.xyz/Article/details/gtcnfisywp.html

JS:   get name() { return this._name; }
来源：http://dali.tanke756.top/Article/details/gtismxivow.html

TS:   get name(): string { return this._name; }
来源：http://dali.hnxiangtu.top/Article/details/gtvqhdjxqy.html

Java: public String getName() { return name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtdivudsap.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.cucudq.cn/Article/details/gtmmolqyiq.html

Ruby: attr_accessor :name
来源：http://dali.pengpengdd.cyou/Article/details/gtaxhybdls.html

C#:   public string Name { get; set; }
来源：http://dali.c1oappe.top/Article/details/gtagjyamvb.html

[G12] 对象转字符串
来源：http://dali.tanke756.top/Article/details/gtqjzhwjpg.html

Py:   def __str__(self): return self.name
来源：http://dali.aibaodan.cn/Article/details/gthgtqhuso.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yonumen.top/Article/details/gthqtebbnb.html

JS:   toString() { return this.name; }
来源：http://dali.zycfv.cn/Article/details/gtneyzqiux.html

TS:   toString(): string { return this.name; }
来源：http://dali.vqdsnc.cn/Article/details/gtgdogszen.html

Java: @Override public String toString() { return name; }
来源：http://dali.vqdsnc.cn/Article/details/gtswnkhncb.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.daxiang520.top/Article/details/gtljukyqyp.html

Ruby: def to_s; @name; end
来源：http://dali.chenjidiqi.icu/Article/details/gtvvgoqjtv.html

C#:   public override string ToString() => Name;
来源：http://dali.chenzaomai.com/Article/details/gtitceboqi.html

[G13] 判断对象类型
来源：http://dali.yj20258.top/Article/details/gtlizugwvk.html

Py:   isinstance(u, User)
来源：http://dali.cashguo.top/Article/details/gtnvogjpaq.html

PHP:  $u instanceof User
来源：http://dali.iojbl.cn/Article/details/gtfbzsoaul.html

JS:   u instanceof User
来源：http://dali.sxryk.cn/Article/details/gtbjqrwhlu.html

TS:   u instanceof User
来源：http://dali.nanxuanxn.top/Article/details/gtygodgshx.html

Java: u instanceof User
来源：http://dali.birdmap.top/Article/details/gtziodlopz.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.shzxlz.cn/Article/details/gtpwpqbnmr.html

Ruby: u.is_a?(User)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwbjgxwbt.html

C#:   u is User
来源：http://dali.yj20258888.top/Article/details/gtgkhaucxr.html

[G14] 数据类 / record
来源：http://dali.hfpthk.cn/Article/details/gttjvatmit.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.vqdsnc.cn/Article/details/gtxkbnyqob.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.meibo888.top/Article/details/gtvuabvibs.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.nwbrower.top/Article/details/gtqdqvpvkv.html

TS:   type User = { name: string; age: number };
来源：http://dali.meibo888.top/Article/details/gtkzqiungn.html

Java: record User(String name, int age) {}
来源：http://dali.fengsongda.top/Article/details/gtexpohrms.html

Go:   type User struct { Name string; Age int }
来源：http://dali.quarkkingdee.top/Article/details/gtjsqoumae.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.vqdsnc.cn/Article/details/gtgtixjznu.html

C#:   record User(string Name, int Age);
来源：http://dali.cdnleiting.top/Article/details/gtlpacqovu.html

[G15] 枚举
来源：http://dali.c1oappe.top/Article/details/gtdqacztmc.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hnqzz.top/Article/details/gtatfashhf.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuiluwlee.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.havefunace.top/Article/details/gtauxbsjzn.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yvedp.cn/Article/details/gtvsrabddo.html

Java: enum Color { RED, GREEN }
来源：http://dali.xuanzx.com/Article/details/gtcelshdao.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.chenjidiqi.icu/Article/details/gtljwibfin.html

Ruby: Color = %i[red green].freeze
来源：http://dali.wangshuangyany.cn/Article/details/gtlmzfqfdf.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.316326.xyz/Article/details/gtwtijwsut.html

[G16] 对象转数组 / 字典
来源：http://dali.c1oappe.top/Article/details/gtrkcxwohf.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.tian-w.cn/Article/details/gtxmafqxvm.html

PHP:  get_object_vars($obj);
来源：http://dali.cucudq.cn/Article/details/gtelyeofnn.html

JS:   Object.entries(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtisrefgck.html

TS:   Object.entries(obj)
来源：http://dali.iojbl.cn/Article/details/gtjjxeuhik.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.gaohongyu789.top/Article/details/gtfrwhyuwr.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.xylfe.cn/Article/details/gtvsgdhltc.html

Ruby: obj.instance_variables
来源：http://dali.xinyue.icu/Article/details/gtwtdiwakw.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.cashguo.top/Article/details/gtislhfpmz.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtpccacxhy.html

H. 异常与错误处理
来源：http://dali.hammf.cn/Article/details/gtvyxptpcq.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtrymsshjv.html

[H01] try / catch 基础
来源：http://dali.wangdashe.top/Article/details/gtdulpxcin.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.gzhubu.top/Article/details/gtbfsffvkn.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.ydzc1.top/Article/details/gtbnaipvvh.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.sxryk.cn/Article/details/gtzvaqjpkx.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zycfv.cn/Article/details/gtvsobxitx.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwqjgselz.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.shuidangran.top/Article/details/gtcdmfqssn.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.fzhhl.top/Article/details/gtbrbjjwwn.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zdqjudy.top/Article/details/gtvliszwzl.html

[H02] finally / ensure 收尾
来源：http://dali.yanxiufei.cn/Article/details/gtiarsgmqn.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.cheryme.top/Article/details/gtahttmlpg.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yongpay.top/Article/details/gtgdeoljef.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.gogol.net.cn/Article/details/gtkdxgrgmp.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.gogol.net.cn/Article/details/gtthgqvxpy.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jlsjyb.cn/Article/details/gthstqspfu.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hywenlv.cn/Article/details/gttzplpmzv.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.sysykeji.top/Article/details/gtwngkywza.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.hfpthk.cn/Article/details/gtaefznlur.html

[H03] 主动抛出异常
来源：http://dali.iojbl.cn/Article/details/gtkirwvdou.html

Py:   raise ValueError("错误信息")
来源：http://dali.tian-w.cn/Article/details/gtfpqgsntn.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.vqdsnc.cn/Article/details/gtaiithqlk.html

JS:   throw new Error("错误信息");
来源：http://dali.hongshengwenyu.top/Article/details/gtxidqcvjw.html

TS:   throw new Error("错误信息");
来源：http://dali.yj20258.top/Article/details/gtttyuwiak.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gttjlyapaj.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.bjfxy.top/Article/details/gtwbnvioxv.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.nwbrower.top/Article/details/gtpkkbsunx.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jinqigufen.top/Article/details/gtisqbgcmt.html

[H04] 自定义异常类型
来源：http://dali.tianlin.xyz/Article/details/gthrhkvbsq.html

Py:   class MyError(Exception): pass
来源：http://dali.jiagoushi.top/Article/details/gtezhignrv.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jinghuilouyu.cn/Article/details/gteowpzljp.html

JS:   class MyError extends Error {}
来源：http://dali.tianlin.xyz/Article/details/gtxbkieyss.html

TS:   class MyError extends Error {}
来源：http://dali.ydzc1.top/Article/details/gtdsuahiqi.html

Java: class MyException extends RuntimeException {}
来源：http://dali.cdnleiting.top/Article/details/gtstibxprp.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.sxryk.cn/Article/details/gtghlinzoj.html

Ruby: class MyError < StandardError; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbgjtehwn.html

C#:   class MyException : Exception {}
来源：http://dali.sweek.top/Article/details/gtjlrkgywh.html

[H05] 捕获特定类型
来源：http://dali.xylfe.cn/Article/details/gtwhhujxnz.html

Py:   except ValueError as e:
来源：http://dali.zhengqikj.top/Article/details/gtfzmvmqyc.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.shanyushiyangtech.top/Article/details/gthrkpgtrn.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.tanke756.top/Article/details/gtyuvddkrn.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.gogol.net.cn/Article/details/gtzisnsbmg.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhoulong.xyz/Article/details/gtclcundua.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jqgufenzy.top/Article/details/gtbctjawxk.html

Ruby: rescue ArgumentError => e
来源：http://dali.nanxinkj.top/Article/details/gtqjsgusqh.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhongyouzk.top/Article/details/gtblmkwlge.html

[H06] 可选值 / 空值安全访问
来源：http://dali.havefunace.top/Article/details/gtovhbmkbo.html

Py:   value = d.get("k") or default
来源：http://dali.ivvv.top/Article/details/gtsihppjek.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.pengpengdd.cyou/Article/details/gtlrizazfm.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.fzhhl.top/Article/details/gtlozrautw.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.aibaodan.cn/Article/details/gtbajcyolo.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zycfv.cn/Article/details/gtpjylljse.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.xuetiantiany.cn/Article/details/gtijhkrijd.html

Ruby: d&.dig(:a, :b)
来源：http://dali.cqqwz.cn/Article/details/gtxpkhcepp.html

C#:   obj?.A?.B ?? default
来源：http://dali.jianghu66.top/Article/details/gtwpxrofjm.html

[H07] 断言
来源：http://dali.birdmap.top/Article/details/gttscebavu.html

Py:   assert x > 0, "必须为正"
来源：http://dali.ehwqpu.com/Article/details/gtrwizgyxw.html

PHP:  assert($x > 0);
来源：http://dali.snrcjt.cn/Article/details/gtqfwvurpb.html

JS:   console.assert(x > 0);
来源：http://dali.yonumen.top/Article/details/gtozptsdql.html

TS:   console.assert(x > 0);
来源：http://dali.meibo888.top/Article/details/gtltqiafap.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhijiandao.cn/Article/details/gtbppqelte.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yueranfly.top/Article/details/gtrvruoeoz.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.316326.xyz/Article/details/gtvyvwmowq.html

C#:   Debug.Assert(x > 0);
来源：http://dali.cashguo.top/Article/details/gtutlvrsok.html

[H08] 获取错误信息与堆栈
来源：http://dali.sysykeji.top/Article/details/gtedjhqtdl.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.snrcjt.cn/Article/details/gtfptisdpu.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.smart0.xyz/Article/details/gtrtxzlzun.html

JS:   e.message;  e.stack
来源：http://dali.feifeiyinyue.top/Article/details/gtgylwjlig.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.shzxlz.cn/Article/details/gtsrgudelh.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yonumen.top/Article/details/gtboxgzczz.html

Go:   err.Error()
来源：http://dali.nwbrower.top/Article/details/gtvwgmqybq.html

Ruby: e.message;  e.backtrace
来源：http://dali.pycfn.com/Article/details/gtxnvmwyng.html

C#:   e.Message;  e.StackTrace
来源：http://dali.birdmap.top/Article/details/gtfwngpcpo.html

[H09] 带错误码的异常
来源：http://dali.wangdashe.top/Article/details/gtuekjkjsn.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.sufxvd.cn/Article/details/gtlwldwtsc.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yueranfly.top/Article/details/gtcltxaakr.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.9152youxi.cn/Article/details/gtjqjysmus.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.xuanzx.com/Article/details/gtmbefsfku.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.snrcjt.cn/Article/details/gtlhqzykcb.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yuxming.cn/Article/details/gtqngjlrdn.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.sweek.top/Article/details/gtzdhkaugv.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.dashuyun.cn/Article/details/gtqmxfxrjp.html

[H10] 资源自动释放
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxiomfjdv.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jlsjyb.cn/Article/details/gtxcjaweyc.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.sysykeji.top/Article/details/gtkwdqljue.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.quarkkingdee.top/Article/details/gtyzamnrva.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.dashuyun.cn/Article/details/gtukxkkuzu.html


<!-- 参考信息 -->