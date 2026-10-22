代发 wailian999

JS:   fs.unlinkSync("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtuaawgmdy.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.guannengcc.top/Article/details/gttlrwavzw.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.chenzaomai.com/Article/details/gtdyqhzinm.html

Go:   os.Remove("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtnsvjmdea.html

Ruby: File.delete("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtoknztfyz.html

C#:   File.Delete("a.txt");
来源：http://dali.smart0.xyz/Article/details/gtwfaihibw.html

[F07] 创建目录（含多级）
来源：http://dali.shuidangran.top/Article/details/gtkhupdrmh.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zycfv.cn/Article/details/gtqjtyksdq.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.shuidangran.top/Article/details/gtaemmaphn.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hfpthk.cn/Article/details/gtepfdykui.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yj20258888.top/Article/details/gtkiylvuou.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yuxming.cn/Article/details/gtnezsyhzk.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yangfankeji.com/Article/details/gtnvtenvwx.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.wangdashe.top/Article/details/gtlzerjgcl.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.fzhhl.top/Article/details/gtxukjfbyn.html

[F08] 遍历目录
来源：http://dali.hysaishi.cn/Article/details/gtcqbnsczn.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.316326.xyz/Article/details/gtcxseeeww.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yvedp.cn/Article/details/gtgjjzlfpq.html

JS:   fs.readdirSync("dir")
来源：http://dali.cashguo.top/Article/details/gtnccbajvg.html

TS:   fs.readdirSync("dir")
来源：http://dali.jinghuilouyu.cn/Article/details/gtqwuotbat.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.shanyushiyangtech.top/Article/details/gtivsoogxj.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.hysaishi.cn/Article/details/gttqnftwzz.html

Ruby: Dir.children("dir")
来源：http://dali.svipenyu.cn/Article/details/gtgqjswdmn.html

C#:   Directory.GetFiles("dir")
来源：http://dali.cqqwz.cn/Article/details/gtbugqcfap.html

[F09] 获取文件大小
来源：http://dali.shanyushiyangtech.top/Article/details/gtwpyphpwd.html

Py:   os.path.getsize("a.txt")
来源：http://dali.pycfn.com/Article/details/gtugiqovfn.html

PHP:  filesize("a.txt");
来源：http://dali.redwolf501.top/Article/details/gtwvkyermv.html

JS:   fs.statSync("a.txt").size
来源：http://dali.tian-w.cn/Article/details/gtnzxrzuzo.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jyoumei.cn/Article/details/gtezjkhecn.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.nanxuanxn.top/Article/details/gtarxjzejl.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yj20258.top/Article/details/gtgofshuqg.html

Ruby: File.size("a.txt")
来源：http://dali.gzhubu.top/Article/details/gthreptbiy.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.hnxiangtu.top/Article/details/gtgpyjvtxt.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.nwbrower.top/Article/details/gtvjkdzejl.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlmbuydhc.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.tian-w.cn/Article/details/gtmqtnrapw.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtjxbpotmk.html

TS:   path.extname("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtnvafmhry.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.shuidangran.top/Article/details/gtlmxufjde.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.cucudq.cn/Article/details/gtjitobpaf.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtqtvbwrkh.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtzbwkbdvk.html

[F11] 复制与移动文件
来源：http://dali.shzxlz.cn/Article/details/gtfshppnfx.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yonumen.top/Article/details/gtlcphuwoz.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gtvtwdjbby.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.havefunace.top/Article/details/gtnefgsuef.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hammf.cn/Article/details/gtomfkgqfu.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.aibaodan.cn/Article/details/gteznnstbz.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.feifeiyinyue.top/Article/details/gtusgmyygz.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.cheryme.top/Article/details/gtautmnehw.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jiagoushi.top/Article/details/gtkneakldz.html

[F12] CSV 读写
来源：http://dali.ybcxt.top/Article/details/gtirymylln.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.xuetiantiany.cn/Article/details/gtmnnuutri.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jiagoushi.top/Article/details/gtuplvdvsv.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.xuanzx.com/Article/details/gtpiprsrhz.html

TS:   // 同上
来源：http://dali.gzhubu.top/Article/details/gtbjdpsgjz.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.cdnleiting.top/Article/details/gtzbhcfhcv.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.kuanghao11.cn/Article/details/gtpajmzvwq.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtscrtxtjg.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.quarkkingdee.top/Article/details/gtzxcndhok.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtewojaiwu.html

G. 面向对象
来源：http://dali.9152youxi.cn/Article/details/gtnhkkulxy.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtdztqxqay.html

[G01] 定义类
来源：http://dali.iojbl.cn/Article/details/gtshhjuiip.html

Py:   class User: pass
来源：http://dali.yuxming.cn/Article/details/gtxccnxysu.html

PHP:  class User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmhfgrlbm.html

JS:   class User {}
来源：http://dali.hysaishi.cn/Article/details/gtpotngspj.html

TS:   class User { name: string = ""; }
来源：http://dali.xinyue.icu/Article/details/gtdhisjgxs.html

Java: class User {}
来源：http://dali.daxiang520.top/Article/details/gtudgqbtil.html

Go:   type User struct { Name string }
来源：http://dali.pycfn.com/Article/details/gtzljrwfax.html

Ruby: class User; end
来源：http://dali.shangyingyoupin.top/Article/details/gtjsftrtgk.html

C#:   class User {}
来源：http://dali.nanxuanxn.top/Article/details/gtxodfjqib.html

[G02] 构造函数
来源：http://dali.hammf.cn/Article/details/gtdnvhidot.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zdqjudy.top/Article/details/gtvnmuuchx.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.havefunace.top/Article/details/gtjoayjwev.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.snrcjt.cn/Article/details/gtxvqhandn.html

TS:   constructor(public name: string) {}
来源：http://dali.tianlin.xyz/Article/details/gtgcuokykw.html

Java: User(String name) { this.name = name; }
来源：http://dali.andypj.xyz/Article/details/gtyvnwluex.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.iojbl.cn/Article/details/gtwnlbhhij.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.gaohongyu789.top/Article/details/gtlbzjefry.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jianghu66.top/Article/details/gtdsyhqygl.html

[G03] 实例属性
来源：http://dali.dianchejie.cn/Article/details/gtkvqvcktt.html

Py:   self.name = "x"
来源：http://dali.vqdsnc.cn/Article/details/gtmogbjjor.html

PHP:  public string $name = "x";
来源：http://dali.guannengcc.top/Article/details/gtfuqfgrth.html

JS:   this.name = "x";
来源：http://dali.pycfn.com/Article/details/gtrgwncgik.html

TS:   name: string = "x";
来源：http://dali.meibo888.top/Article/details/gtduiwscgh.html

Java: private String name;
来源：http://dali.jinqigfzy.top/Article/details/gtiyduwhiw.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.bjfxy.top/Article/details/gticwiwpjy.html

Ruby: @name = "x"
来源：http://dali.xziqi.cn/Article/details/gtuqnztnpt.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.shzxlz.cn/Article/details/gtgalrwgya.html

[G04] 定义方法
来源：http://dali.bjfxy.top/Article/details/gtortxzaiv.html

Py:   def greet(self): return self.name
来源：http://dali.shuidangran.top/Article/details/gtjxjuatji.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yangfankeji.com/Article/details/gtoxrqvoeg.html

JS:   greet() { return this.name; }
来源：http://dali.hysaishi.cn/Article/details/gtgzldrfjv.html

TS:   greet(): string { return this.name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtaubgoima.html

Java: String greet() { return name; }
来源：http://dali.ppjwa.cn/Article/details/gtiwiormkv.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yangfankeji.com/Article/details/gtvqcckxlc.html

Ruby: def greet; @name; end
来源：http://dali.jinqigufen.top/Article/details/gtqjdrbwzy.html

C#:   public string Greet() => Name;
来源：http://dali.daria6918.cn/Article/details/gtwdlysmgd.html

[G05] 继承
来源：http://dali.quarkkingdee.top/Article/details/gtmzuuhggf.html

Py:   class Admin(User): pass
来源：http://dali.yj20258.top/Article/details/gtosrhmsdq.html

PHP:  class Admin extends User {}
来源：http://dali.zhengqikj.top/Article/details/gtkklxabvn.html

JS:   class Admin extends User {}
来源：http://dali.jinqigufen.top/Article/details/gtrsyubniw.html

TS:   class Admin extends User {}
来源：http://dali.hongshengwenyu.top/Article/details/gtawdhiveh.html

Java: class Admin extends User {}
来源：http://dali.wangdashe.top/Article/details/gtvnoxyrbi.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jqgfzy.top/Article/details/gthoqzfjfa.html

Ruby: class Admin < User; end
来源：http://dali.svipenyu.cn/Article/details/gtamqwsajs.html

C#:   class Admin : User {}
来源：http://dali.shuidangran.top/Article/details/gtaxkvaqpb.html

[G06] 重写方法
来源：http://dali.jlsjyb.cn/Article/details/gtwxywkpdv.html

Py:   def greet(self): return "admin"
来源：http://dali.snrcjt.cn/Article/details/gtpqcvdrxx.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.aibaodan.cn/Article/details/gtmwnvwsoj.html

JS:   greet() { return "admin"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyigoeske.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jiagoushi.top/Article/details/gttvljmyln.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.pycfn.com/Article/details/gtngnpkper.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.iojbl.cn/Article/details/gttqejqwak.html

Ruby: def greet; "admin"; end
来源：http://dali.chenjidiqi.icu/Article/details/gtwjsnmomr.html

C#:   public override string Greet() => "admin";
来源：http://dali.daxiang520.top/Article/details/gtjbvbphbl.html

[G07] 调用父类方法
来源：http://dali.cheryme.top/Article/details/gtmyvcyqrv.html

Py:   super().greet()
来源：http://dali.xuanzx.com/Article/details/gtjtdvuugx.html

PHP:  parent::greet();
来源：http://dali.ybcxt.top/Article/details/gtcwzlrxcs.html

JS:   super.greet();
来源：http://dali.xuetiantiany.cn/Article/details/gtfszzjkys.html

TS:   super.greet();
来源：http://dali.dashuyun.cn/Article/details/gtvzqesssw.html

Java: super.greet();
来源：http://dali.hysaishi.cn/Article/details/gtxgbpfnhn.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.ydzc1.top/Article/details/gthnadkcib.html

Ruby: super
来源：http://dali.yangfankeji.com/Article/details/gtztpuyegi.html

C#:   base.Greet();
来源：http://dali.nwbrower.top/Article/details/gtylcrtsnm.html

[G08] 静态方法与属性
来源：http://dali.cucudq.cn/Article/details/gtzhrsmamb.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.smart0.xyz/Article/details/gtdsdctiwe.html

PHP:  public static function f() {}
来源：http://dali.jqgfzy.top/Article/details/gtrmumdcwr.html

JS:   static f() {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxkckcjpt.html

TS:   static f(): void {}
来源：http://dali.ehwqpu.com/Article/details/gtehtvofmb.html

Java: static void f() {}
来源：http://dali.0kj1m.cn/Article/details/gtkazfqvgb.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gtwkhrqlcz.html

Ruby: def self.f; end
来源：http://dali.birdmap.top/Article/details/gtausaiqgw.html

C#:   public static void F() {}
来源：http://dali.hysaishi.cn/Article/details/gtxoingunm.html

[G09] 接口 / 抽象类
来源：http://dali.pycfn.com/Article/details/gtjjavrnrq.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.chenzaomai.com/Article/details/gtimnqwdfd.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.hysaishi.cn/Article/details/gtvihsehfk.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.guannengcc.top/Article/details/gtdxntbztx.html

TS:   interface Shape { area(): number; }
来源：http://dali.cucudq.cn/Article/details/gtevlqwnth.html

Java: interface Shape { double area(); }
来源：http://dali.0kj1m.cn/Article/details/gtxqugulqs.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhengqikj.top/Article/details/gtfpcqhdfx.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhoulong.xyz/Article/details/gtlrqzrjan.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhengqikj.top/Article/details/gtezmnnxdb.html

[G10] 访问控制
来源：http://dali.c1oappe.top/Article/details/gtyoejyqgj.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.wangshuangyany.cn/Article/details/gturoakvdf.html

PHP:  public / protected / private
来源：http://dali.ivvv.top/Article/details/gtmsksvatr.html

JS:   #private 字段；其余公开
来源：http://dali.yonumen.top/Article/details/gtxvlogfrv.html

TS:   public / protected / private
来源：http://dali.shzxlz.cn/Article/details/gtzbrnqtrw.html

Java: public / protected / private / 默认包级
来源：http://dali.hnqzz.top/Article/details/gtqlvlswte.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jqgfzy.top/Article/details/gtfmlsbibe.html

Ruby: public / protected / private
来源：http://dali.guannengcc.top/Article/details/gtaysaqmxd.html

C#:   public / protected / private / internal
来源：http://dali.daxiang520.top/Article/details/gtdlltrdsi.html

[G11] getter / setter
来源：http://dali.guowangkeji.top/Article/details/gtblmjibzk.html

Py:   @property 与 @x.setter
来源：http://dali.jinghuilouyu.cn/Article/details/gtfapjnpxa.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.daxiang520.top/Article/details/gteefdnjdp.html

JS:   get name() { return this._name; }
来源：http://dali.vqdsnc.cn/Article/details/gtxrwyttxy.html

TS:   get name(): string { return this._name; }
来源：http://dali.cheryme.top/Article/details/gtydrcszau.html

Java: public String getName() { return name; }
来源：http://dali.dianchejie.cn/Article/details/gtrjfcoibd.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.tian-w.cn/Article/details/gtvrufjahe.html

Ruby: attr_accessor :name
来源：http://dali.cdnleiting.top/Article/details/gthfjwskut.html

C#:   public string Name { get; set; }
来源：http://dali.daria6918.cn/Article/details/gtdbddywub.html

[G12] 对象转字符串
来源：http://dali.feifeiyinyue.top/Article/details/gtcfwtrdvt.html

Py:   def __str__(self): return self.name
来源：http://dali.chenjidiqi.icu/Article/details/gtjxkhyyex.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.nwbrower.top/Article/details/gteigudvcb.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gtxqxleqtf.html

TS:   toString(): string { return this.name; }
来源：http://dali.jlsjyb.cn/Article/details/gteotzddck.html

Java: @Override public String toString() { return name; }
来源：http://dali.andypj.xyz/Article/details/gtjazcycal.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhongyouzk.top/Article/details/gtnlgsvrox.html

Ruby: def to_s; @name; end
来源：http://dali.zdqjudy.top/Article/details/gtlxdjdhpk.html

C#:   public override string ToString() => Name;
来源：http://dali.pycfn.com/Article/details/gttxwzmkwe.html

[G13] 判断对象类型
来源：http://dali.jqgfzy.top/Article/details/gtzmrfbxfy.html

Py:   isinstance(u, User)
来源：http://dali.ydzc1.top/Article/details/gtknlgkgfi.html

PHP:  $u instanceof User
来源：http://dali.hongshengwenyu.top/Article/details/gtoooibxah.html

JS:   u instanceof User
来源：http://dali.daria6918.cn/Article/details/gtztohixiu.html

TS:   u instanceof User
来源：http://dali.jinqigfzy.top/Article/details/gttxchrvbl.html

Java: u instanceof User
来源：http://dali.fengsongda.top/Article/details/gtnedqgnod.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.c1oappe.top/Article/details/gtfqhluzua.html

Ruby: u.is_a?(User)
来源：http://dali.ehwqpu.com/Article/details/gtldbbddza.html

C#:   u is User
来源：http://dali.snrcjt.cn/Article/details/gtjnfgytcc.html

[G14] 数据类 / record
来源：http://dali.tian-w.cn/Article/details/gtfumlrngl.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.shzxlz.cn/Article/details/gtzmazrzgb.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhaomingkeji.xyz/Article/details/gtivmzaqwk.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yongpay.top/Article/details/gtqpxxjyyd.html

TS:   type User = { name: string; age: number };
来源：http://dali.jlsjyb.cn/Article/details/gturavdeeo.html

Java: record User(String name, int age) {}
来源：http://dali.daxiang520.top/Article/details/gtazdxshxf.html

Go:   type User struct { Name string; Age int }
来源：http://dali.pycfn.com/Article/details/gtnkstjxcz.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yonumen.top/Article/details/gtjlayfalw.html

C#:   record User(string Name, int Age);
来源：http://dali.tanke756.top/Article/details/gtzqpoqpac.html

[G15] 枚举
来源：http://dali.birdmap.top/Article/details/gtujrwnvnj.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.pengpengdd.cyou/Article/details/gtlytknwxh.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.birdmap.top/Article/details/gtomoltgqk.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.wangshuangyany.cn/Article/details/gtzpgqfljp.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yj20258888.top/Article/details/gtllgnfvzw.html

Java: enum Color { RED, GREEN }
来源：http://dali.0kj1m.cn/Article/details/gtfzdamftv.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.aizwys.cn/Article/details/gtzrqltmeq.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jqgfzy.top/Article/details/gtktumvhuv.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.fzhhl.top/Article/details/gtfdpgpyci.html

[G16] 对象转数组 / 字典
来源：http://dali.nwbrower.top/Article/details/gtbbdbhprs.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.andypj.xyz/Article/details/gtgucktdcb.html

PHP:  get_object_vars($obj);
来源：http://dali.daria6918.cn/Article/details/gtdenufxrr.html

JS:   Object.entries(obj)
来源：http://dali.jyoumei.cn/Article/details/gtnmplqnvh.html

TS:   Object.entries(obj)
来源：http://dali.havefunace.top/Article/details/gtttneucne.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hnqzz.top/Article/details/gtecqjgqsx.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.tianlin.xyz/Article/details/gtrqrbkgll.html

Ruby: obj.instance_variables
来源：http://dali.yuxming.cn/Article/details/gtcjmunsrk.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.316326.xyz/Article/details/gtydarcnjt.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtfckxisht.html

H. 异常与错误处理
来源：http://dali.hnxiangtu.top/Article/details/gthvscgmrw.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtfwreiseu.html

[H01] try / catch 基础
来源：http://dali.ivvv.top/Article/details/gtgxgmuivv.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhengqikj.top/Article/details/gtcgxsfcag.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.redwolf501.top/Article/details/gtfwugkppg.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hnxiangtu.top/Article/details/gtvmyznztf.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.cashguo.top/Article/details/gtbxdynsdc.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.ehwqpu.com/Article/details/gtmxoxsopc.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.vqdsnc.cn/Article/details/gtfgrjgbdw.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.xuetiantiany.cn/Article/details/gtwxjctrod.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yj20258888.top/Article/details/gtupguxttk.html

[H02] finally / ensure 收尾
来源：http://dali.redwolf501.top/Article/details/gtrjbzwqpk.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.quarkkingdee.top/Article/details/gtadfmmlxm.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.pycfn.com/Article/details/gtutiqhaxk.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jianghu66.top/Article/details/gtizwoherf.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jiagoushi.top/Article/details/gtnxzwxxmx.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.vqdsnc.cn/Article/details/gtciuaudcc.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hysaishi.cn/Article/details/gtzvbhbwue.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.gaohongyu789.top/Article/details/gtfizmedvt.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.hnqzz.top/Article/details/gtypxkwwzq.html

[H03] 主动抛出异常
来源：http://dali.9152youxi.cn/Article/details/gthzkakbnh.html

Py:   raise ValueError("错误信息")
来源：http://dali.yuxming.cn/Article/details/gtruegsyhv.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.mhx1999.top/Article/details/gtbopfajfd.html

JS:   throw new Error("错误信息");
来源：http://dali.yangfankeji.com/Article/details/gtezolknox.html

TS:   throw new Error("错误信息");
来源：http://dali.chenzaomai.com/Article/details/gttxtzvogi.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.0kj1m.cn/Article/details/gthhthnxkn.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.sxryk.cn/Article/details/gtmajzsfqk.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.cqqwz.cn/Article/details/gtygnxqsxe.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.pycfn.com/Article/details/gtqzxttizr.html

[H04] 自定义异常类型
来源：http://dali.ydzc1.top/Article/details/gtiamscict.html

Py:   class MyError(Exception): pass
来源：http://dali.meibo888.top/Article/details/gtgyfapmlp.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.ehwqpu.com/Article/details/gtysoijllq.html

JS:   class MyError extends Error {}
来源：http://dali.andypj.xyz/Article/details/gtqyijtrdg.html

TS:   class MyError extends Error {}
来源：http://dali.hongshengwenyu.top/Article/details/gtmphtawfr.html

Java: class MyException extends RuntimeException {}
来源：http://dali.9152youxi.cn/Article/details/gtnhtuwwbj.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.mhx1999.top/Article/details/gttlprtnpk.html

Ruby: class MyError < StandardError; end
来源：http://dali.wangshuangyany.cn/Article/details/gtaqlzgvcs.html

C#:   class MyException : Exception {}
来源：http://dali.xziqi.cn/Article/details/gtevxolzje.html

[H05] 捕获特定类型
来源：http://dali.cqqwz.cn/Article/details/gtxhvlydga.html

Py:   except ValueError as e:
来源：http://dali.gotoacloud.top/Article/details/gtspmdnbyn.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.tanke756.top/Article/details/gtaogfrlop.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.cdnleiting.top/Article/details/gtoowebnde.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.shzxlz.cn/Article/details/gtsykhbnkq.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hnqzz.top/Article/details/gtwzuwxhpr.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.xinyue.icu/Article/details/gtwnhuwlny.html

Ruby: rescue ArgumentError => e
来源：http://dali.yj20258.top/Article/details/gtraknayuu.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.ehwqpu.com/Article/details/gtvpdutqbx.html

[H06] 可选值 / 空值安全访问
来源：http://dali.svipenyu.cn/Article/details/gtzkobnnbw.html

Py:   value = d.get("k") or default
来源：http://dali.meibo888.top/Article/details/gthgdjzkbn.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.chenlongwang.top/Article/details/gtyqwztted.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.cheryme.top/Article/details/gtexakknpt.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.bjfxy.top/Article/details/gtcattjnlb.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.hnxiangtu.top/Article/details/gtfvoqtvnz.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yonumen.top/Article/details/gtydxtaezn.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yvedp.cn/Article/details/gtsuwgekhm.html

C#:   obj?.A?.B ?? default
来源：http://dali.guowangkeji.top/Article/details/gtibmjkvdl.html

[H07] 断言
来源：http://dali.zhoulong.xyz/Article/details/gtqitkmygu.html

Py:   assert x > 0, "必须为正"
来源：http://dali.xuanzx.com/Article/details/gtoqnnstep.html

PHP:  assert($x > 0);
来源：http://dali.cheryme.top/Article/details/gtgnakcuwj.html

JS:   console.assert(x > 0);
来源：http://dali.cashguo.top/Article/details/gtvbjlijhk.html

TS:   console.assert(x > 0);
来源：http://dali.yongpay.top/Article/details/gtsovltswd.html

Java: assert x > 0 : "必须为正";
来源：http://dali.iojbl.cn/Article/details/gtysznjidl.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.sufxvd.cn/Article/details/gtirzqrwwf.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.meibo888.top/Article/details/gtncufcttk.html

C#:   Debug.Assert(x > 0);
来源：http://dali.svipenyu.cn/Article/details/gtzweridbx.html

[H08] 获取错误信息与堆栈
来源：http://dali.hywenlv.cn/Article/details/gtafkdaqtu.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zdqjudy.top/Article/details/gtzioyndsi.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.shzxlz.cn/Article/details/gtnsvmqypr.html

JS:   e.message;  e.stack
来源：http://dali.shuidangran.top/Article/details/gtyrkakdnk.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.smart0.xyz/Article/details/gtnbarmbkd.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zdqjudy.top/Article/details/gtojzgcslb.html

Go:   err.Error()
来源：http://dali.jinqigfzy.top/Article/details/gtdyhmizpy.html

Ruby: e.message;  e.backtrace
来源：http://dali.xinyue.icu/Article/details/gtmljtcsvk.html

C#:   e.Message;  e.StackTrace
来源：http://dali.ydzc1.top/Article/details/gteztpqkoz.html

[H09] 带错误码的异常
来源：http://dali.jlsjyb.cn/Article/details/gtsgayltzm.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yj20258.top/Article/details/gtqkalulgy.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yongpay.top/Article/details/gttnypksbc.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.hywenlv.cn/Article/details/gtjnpgyvot.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.aizwys.cn/Article/details/gtcynhqrzq.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyvwuwocz.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.c1oappe.top/Article/details/gtyoqbcclm.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.c1oappe.top/Article/details/gtmrcwqwcm.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yanxiufei.cn/Article/details/gtuhdgnbaa.html

[H10] 资源自动释放
来源：http://dali.cashguo.top/Article/details/gtngkhwbno.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.shanyushiyangtech.top/Article/details/gtnxzhqodc.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.shuidangran.top/Article/details/gttutcrifk.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.mhx1999.top/Article/details/gtjwvwdadx.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zdqjudy.top/Article/details/gttzbvsgim.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hnxiangtu.top/Article/details/gtjruzmkcq.html

Go:   defer f.Close()
来源：http://dali.fengsongda.top/Article/details/gtivwfjvrb.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hnqzz.top/Article/details/gtrkugevit.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yueranfly.top/Article/details/gtysjdksdq.html


<!-- 参考信息 -->