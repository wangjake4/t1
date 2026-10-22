代发 wailian999

[F05] 判断文件或目录是否存在
来源：http://dali.jqgfzy.top/Article/details/gtklmvjksd.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.hysaishi.cn/Article/details/gtemkmwcce.html

PHP:  file_exists("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gtnpybceib.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtqyaaigph.html

TS:   fs.existsSync("a.txt")
来源：http://dali.sweek.top/Article/details/gtyooboukg.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.fzhhl.top/Article/details/gtbtqwedmk.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jqgfzy.top/Article/details/gtzgxpyomd.html

Ruby: File.exist?("a.txt")
来源：http://dali.sweek.top/Article/details/gtwxkmgdze.html

C#:   File.Exists("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtegwagqjv.html

[F06] 删除文件
来源：http://dali.sxryk.cn/Article/details/gttqpoujdn.html

Py:   os.remove("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtbwazqsbe.html

PHP:  unlink("a.txt");
来源：http://dali.cdnleiting.top/Article/details/gtzxezhjzf.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.cheryme.top/Article/details/gtvttgvcla.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yj202588.top/Article/details/gtgzieiwvu.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yj20258888.top/Article/details/gtrwjuiabg.html

Go:   os.Remove("a.txt")
来源：http://dali.mhx1999.top/Article/details/gttaywnzzu.html

Ruby: File.delete("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtetdfcrnb.html

C#:   File.Delete("a.txt");
来源：http://dali.yonumen.top/Article/details/gthavrfhqb.html

[F07] 创建目录（含多级）
来源：http://dali.meibo888.top/Article/details/gtubzsxmei.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.tanke756.top/Article/details/gticmsjjkz.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hnxiangtu.top/Article/details/gtdlkvegdy.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zycfv.cn/Article/details/gtgfgkvvso.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gtbkysstew.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hywenlv.cn/Article/details/gtygnlfiix.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.gzhubu.top/Article/details/gtxejkjcqd.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.cheryme.top/Article/details/gtltpzocem.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.ehwqpu.com/Article/details/gtdgwhqjqp.html

[F08] 遍历目录
来源：http://dali.zhongyouzk.top/Article/details/gtokhxyhpw.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jinqigfzy.top/Article/details/gtqyfkrrgv.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.gzhubu.top/Article/details/gtkzglpeab.html

JS:   fs.readdirSync("dir")
来源：http://dali.gogol.net.cn/Article/details/gtwxvrvgdn.html

TS:   fs.readdirSync("dir")
来源：http://dali.sysykeji.top/Article/details/gtvhmqmtdc.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.xziqi.cn/Article/details/gtvqfucjoo.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhongyouzk.top/Article/details/gtnmsxzofg.html

Ruby: Dir.children("dir")
来源：http://dali.c1oappe.top/Article/details/gtapnfkrcm.html

C#:   Directory.GetFiles("dir")
来源：http://dali.nanxuanxn.top/Article/details/gtsjvdprym.html

[F09] 获取文件大小
来源：http://dali.cheryme.top/Article/details/gtgkarqnyz.html

Py:   os.path.getsize("a.txt")
来源：http://dali.birdmap.top/Article/details/gtavbjmybd.html

PHP:  filesize("a.txt");
来源：http://dali.tanke756.top/Article/details/gtcjmktqnl.html

JS:   fs.statSync("a.txt").size
来源：http://dali.ivvv.top/Article/details/gtolvkoppj.html

TS:   fs.statSync("a.txt").size
来源：http://dali.meibo888.top/Article/details/gtjxoouymy.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yonumen.top/Article/details/gtxuinnkvn.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zdqjudy.top/Article/details/gtyrjjuknw.html

Ruby: File.size("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtsinzwrnv.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jlsjyb.cn/Article/details/gttmgqmzwx.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.sweek.top/Article/details/gtjcvtgalx.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.fzhhl.top/Article/details/gtoqrczzyj.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jyoumei.cn/Article/details/gtwzlquiml.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gteftqtgas.html

TS:   path.extname("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtjozgefso.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.9152youxi.cn/Article/details/gtrxjwrksc.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtrecewflw.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtawpozkid.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.xylfe.cn/Article/details/gtkrqouztt.html

[F11] 复制与移动文件
来源：http://dali.sweek.top/Article/details/gthyxrzudh.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.aibaodan.cn/Article/details/gtxrnvxtjy.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.sufxvd.cn/Article/details/gttvrywwkk.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yj20258.top/Article/details/gtdubylydg.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gogol.net.cn/Article/details/gtjixzcfnu.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.hnxiangtu.top/Article/details/gtuvcsyazy.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.wangdashe.top/Article/details/gtmhkrjmps.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.hfpthk.cn/Article/details/gtbzwiahrw.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yangfankeji.com/Article/details/gtqxhfducf.html

[F12] CSV 读写
来源：http://dali.jianghu66.top/Article/details/gttlunvrfn.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jinghuilouyu.cn/Article/details/gthfgvxrrt.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yonumen.top/Article/details/gtpaqhchjf.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hongshengwenyu.top/Article/details/gtxhjzrupz.html

TS:   // 同上
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgpceurhx.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.tianlin.xyz/Article/details/gtvgahzukc.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.redwolf501.top/Article/details/gtlrbmwdqi.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jinghuilouyu.cn/Article/details/gtldfvmhwm.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.svipenyu.cn/Article/details/gtkrmavtce.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtjiepmfyc.html

G. 面向对象
来源：http://dali.jqgfzy.top/Article/details/gtuqouciai.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gttwgzajze.html

[G01] 定义类
来源：http://dali.yangfankeji.com/Article/details/gtknngtbqz.html

Py:   class User: pass
来源：http://dali.aibaodan.cn/Article/details/gtwngnrarz.html

PHP:  class User {}
来源：http://dali.fzhhl.top/Article/details/gtnxeamoek.html

JS:   class User {}
来源：http://dali.meibo888.top/Article/details/gttmgdlezu.html

TS:   class User { name: string = ""; }
来源：http://dali.sweek.top/Article/details/gtcwzioyrb.html

Java: class User {}
来源：http://dali.havefunace.top/Article/details/gtvsuiahyu.html

Go:   type User struct { Name string }
来源：http://dali.ehwqpu.com/Article/details/gthelrwofq.html

Ruby: class User; end
来源：http://dali.birdmap.top/Article/details/gtabdbhwst.html

C#:   class User {}
来源：http://dali.jianghu66.top/Article/details/gtzgoapkhi.html

[G02] 构造函数
来源：http://dali.xuanzx.com/Article/details/gtbjtqlwia.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.redwolf501.top/Article/details/gtzwicggqg.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtjtbwweud.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yuxming.cn/Article/details/gtwathtbtt.html

TS:   constructor(public name: string) {}
来源：http://dali.ybcxt.top/Article/details/gtmvwakdlr.html

Java: User(String name) { this.name = name; }
来源：http://dali.meibo888.top/Article/details/gtrjwtzqyr.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.shzxlz.cn/Article/details/gtmljxzsqk.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.xuetiantiany.cn/Article/details/gtrbfntloq.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yj20258888.top/Article/details/gtdxxwxdel.html

[G03] 实例属性
来源：http://dali.sysykeji.top/Article/details/gtnzjbjccn.html

Py:   self.name = "x"
来源：http://dali.shanyushiyangtech.top/Article/details/gtjicstdea.html

PHP:  public string $name = "x";
来源：http://dali.xziqi.cn/Article/details/gtxzbljckh.html

JS:   this.name = "x";
来源：http://dali.xziqi.cn/Article/details/gtrxvtuqlg.html

TS:   name: string = "x";
来源：http://dali.guowangkeji.top/Article/details/gtxvlvxjip.html

Java: private String name;
来源：http://dali.jianghu66.top/Article/details/gtaardnqqc.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.cqqwz.cn/Article/details/gtmzmnvgoa.html

Ruby: @name = "x"
来源：http://dali.chenlongwang.top/Article/details/gtymregazq.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.haohaochexian.top/Article/details/gtmyvpsmhx.html

[G04] 定义方法
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuomrgqgq.html

Py:   def greet(self): return self.name
来源：http://dali.ybcxt.top/Article/details/gtjahjurod.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtcdkapyau.html

JS:   greet() { return this.name; }
来源：http://dali.hywenlv.cn/Article/details/gtfkrlnqsl.html

TS:   greet(): string { return this.name; }
来源：http://dali.fzhhl.top/Article/details/gtabpzwskp.html

Java: String greet() { return name; }
来源：http://dali.jinqigufen.top/Article/details/gtdudvvgeo.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hnxiangtu.top/Article/details/gtpjsdlgxy.html

Ruby: def greet; @name; end
来源：http://dali.guannengcc.top/Article/details/gtszvamvvw.html

C#:   public string Greet() => Name;
来源：http://dali.cucudq.cn/Article/details/gtmeqiwlag.html

[G05] 继承
来源：http://dali.birdmap.top/Article/details/gthlscmikp.html

Py:   class Admin(User): pass
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqloeajvw.html

PHP:  class Admin extends User {}
来源：http://dali.chenlongwang.top/Article/details/gtijqfucta.html

JS:   class Admin extends User {}
来源：http://dali.jinqigufen.top/Article/details/gtxcatxtla.html

TS:   class Admin extends User {}
来源：http://dali.shzxlz.cn/Article/details/gtlytfmodj.html

Java: class Admin extends User {}
来源：http://dali.c1oappe.top/Article/details/gtbchjklyl.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.cdnleiting.top/Article/details/gtaurknctb.html

Ruby: class Admin < User; end
来源：http://dali.gogol.net.cn/Article/details/gteamorqcn.html

C#:   class Admin : User {}
来源：http://dali.dianchejie.cn/Article/details/gtvdizzcut.html

[G06] 重写方法
来源：http://dali.jiagoushi.top/Article/details/gthqkyljnv.html

Py:   def greet(self): return "admin"
来源：http://dali.iojbl.cn/Article/details/gtzcwmkyub.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.9152youxi.cn/Article/details/gtdecgbwcu.html

JS:   greet() { return "admin"; }
来源：http://dali.quarkkingdee.top/Article/details/gtodamuqes.html

TS:   greet(): string { return "admin"; }
来源：http://dali.pycfn.com/Article/details/gtsvymfedq.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yj20258888.top/Article/details/gthubzfizu.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.daxiang520.top/Article/details/gtjrdrixst.html

Ruby: def greet; "admin"; end
来源：http://dali.daria6918.cn/Article/details/gtdjdcrudk.html

C#:   public override string Greet() => "admin";
来源：http://dali.hywenlv.cn/Article/details/gtfehgxvcd.html

[G07] 调用父类方法
来源：http://dali.nwbrower.top/Article/details/gtwtvagnzn.html

Py:   super().greet()
来源：http://dali.havefunace.top/Article/details/gtixpezpmw.html

PHP:  parent::greet();
来源：http://dali.aibaodan.cn/Article/details/gtncurljhi.html

JS:   super.greet();
来源：http://dali.xziqi.cn/Article/details/gtozhdtrft.html

TS:   super.greet();
来源：http://dali.guannengcc.top/Article/details/gtnvirlspy.html

Java: super.greet();
来源：http://dali.jianghu66.top/Article/details/gtvrmoaury.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zdqjudy.top/Article/details/gtioucfoff.html

Ruby: super
来源：http://dali.gotoacloud.top/Article/details/gtdokkgepf.html

C#:   base.Greet();
来源：http://dali.redwolf501.top/Article/details/gtbmkzhrvd.html

[G08] 静态方法与属性
来源：http://dali.hnqzz.top/Article/details/gtffibbzwh.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhixingplan.top/Article/details/gtrzdihdbm.html

PHP:  public static function f() {}
来源：http://dali.sxryk.cn/Article/details/gtcpgdfelp.html

JS:   static f() {}
来源：http://dali.sysykeji.top/Article/details/gtojmuqxxw.html

TS:   static f(): void {}
来源：http://dali.hammf.cn/Article/details/gtwzzfwiab.html

Java: static void f() {}
来源：http://dali.yueranfly.top/Article/details/gtfoyxvdva.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jyoumei.cn/Article/details/gttmnugxxj.html

Ruby: def self.f; end
来源：http://dali.hywenlv.cn/Article/details/gtmokfcvsb.html

C#:   public static void F() {}
来源：http://dali.jinqigfzy.top/Article/details/gtcjmoqkck.html

[G09] 接口 / 抽象类
来源：http://dali.xziqi.cn/Article/details/gtfsgnnagd.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.snrcjt.cn/Article/details/gtqbnvccid.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yj20258.top/Article/details/gtekutwtrk.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ydzc1.top/Article/details/gteeridcvo.html

TS:   interface Shape { area(): number; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtogpzhjwk.html

Java: interface Shape { double area(); }
来源：http://dali.vqdsnc.cn/Article/details/gtdgewnblp.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.fengsongda.top/Article/details/gtglmtycig.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gticlikiuj.html

C#:   interface IShape { double Area(); }
来源：http://dali.quarkkingdee.top/Article/details/gtyqxfhybm.html

[G10] 访问控制
来源：http://dali.0kj1m.cn/Article/details/gtnrsbwlad.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthhbxguvp.html

PHP:  public / protected / private
来源：http://dali.0kj1m.cn/Article/details/gtlwnnvwgx.html

JS:   #private 字段；其余公开
来源：http://dali.cheryme.top/Article/details/gtludxazyy.html

TS:   public / protected / private
来源：http://dali.haohaochexian.top/Article/details/gtfptcrysb.html

Java: public / protected / private / 默认包级
来源：http://dali.gogol.net.cn/Article/details/gtruotsasq.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yueranfly.top/Article/details/gtjfjqcjoo.html

Ruby: public / protected / private
来源：http://dali.gotoacloud.top/Article/details/gtnhqojgzu.html

C#:   public / protected / private / internal
来源：http://dali.yangfankeji.com/Article/details/gtcxnyotxw.html

[G11] getter / setter
来源：http://dali.nanxinkj.top/Article/details/gtnexghcul.html

Py:   @property 与 @x.setter
来源：http://dali.jianghu66.top/Article/details/gtdowziklx.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.fzhhl.top/Article/details/gtzmnzingq.html

JS:   get name() { return this._name; }
来源：http://dali.jinqigufen.top/Article/details/gtrjyjkxks.html

TS:   get name(): string { return this._name; }
来源：http://dali.chenlongwang.top/Article/details/gtedlvvllo.html

Java: public String getName() { return name; }
来源：http://dali.gaohongyu789.top/Article/details/gtfrbjdkoz.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.tianlin.xyz/Article/details/gtegijkdyq.html

Ruby: attr_accessor :name
来源：http://dali.jinghuilouyu.cn/Article/details/gttnblgznp.html

C#:   public string Name { get; set; }
来源：http://dali.chenlongwang.top/Article/details/gtmfuyiwbb.html

[G12] 对象转字符串
来源：http://dali.fengsongda.top/Article/details/gthbtivbuh.html

Py:   def __str__(self): return self.name
来源：http://dali.svipenyu.cn/Article/details/gtvalxntwh.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.svipenyu.cn/Article/details/gtzwxmbvkk.html

JS:   toString() { return this.name; }
来源：http://dali.daria6918.cn/Article/details/gtvorxgxkr.html

TS:   toString(): string { return this.name; }
来源：http://dali.yj20258888.top/Article/details/gtllxhtzjm.html

Java: @Override public String toString() { return name; }
来源：http://dali.jiagoushi.top/Article/details/gtxoyyskpv.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yuxming.cn/Article/details/gtxoylwpnk.html

Ruby: def to_s; @name; end
来源：http://dali.chenjidiqi.icu/Article/details/gthzqruoyo.html

C#:   public override string ToString() => Name;
来源：http://dali.ehwqpu.com/Article/details/gtucfpaaow.html

[G13] 判断对象类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvrzkxofb.html

Py:   isinstance(u, User)
来源：http://dali.yangfankeji.com/Article/details/gtlqlzlhyt.html

PHP:  $u instanceof User
来源：http://dali.yuanzhike.top/Article/details/gtxpoxrbuo.html

JS:   u instanceof User
来源：http://dali.0kj1m.cn/Article/details/gtuqhiodrf.html

TS:   u instanceof User
来源：http://dali.pengpengdd.cyou/Article/details/gtvuvwzlfp.html

Java: u instanceof User
来源：http://dali.vqdsnc.cn/Article/details/gtrivaeege.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.chenjidiqi.icu/Article/details/gtpycegjdb.html

Ruby: u.is_a?(User)
来源：http://dali.gzhubu.top/Article/details/gtphwpxbhu.html

C#:   u is User
来源：http://dali.tianlin.xyz/Article/details/gtjktoiesk.html

[G14] 数据类 / record
来源：http://dali.gotoacloud.top/Article/details/gtkgkynwyz.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.ybcxt.top/Article/details/gtuljpneii.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.9152youxi.cn/Article/details/gttkbayfch.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.bjfxy.top/Article/details/gtdsmfinfr.html

TS:   type User = { name: string; age: number };
来源：http://dali.yueranfly.top/Article/details/gtpewaejsm.html

Java: record User(String name, int age) {}
来源：http://dali.cashguo.top/Article/details/gtylkdxuzm.html

Go:   type User struct { Name string; Age int }
来源：http://dali.ehwqpu.com/Article/details/gtdxgziygu.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhoulong.xyz/Article/details/gthnbxymxe.html

C#:   record User(string Name, int Age);
来源：http://dali.pycfn.com/Article/details/gtyvasfwqq.html

[G15] 枚举
来源：http://dali.jqgufenzy.top/Article/details/gtfdcgodwl.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.wangshuangyany.cn/Article/details/gtljvrckzb.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.kuanghao11.cn/Article/details/gtmlnnzyzu.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.hfpthk.cn/Article/details/gtcnyvsorb.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yongpay.top/Article/details/gtlxmntzah.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxziqgmoo.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yj20258.top/Article/details/gtulvkofbp.html

Ruby: Color = %i[red green].freeze
来源：http://dali.sxryk.cn/Article/details/gtayqtpfvv.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yanxiufei.cn/Article/details/gtndibbgfx.html

[G16] 对象转数组 / 字典
来源：http://dali.gogol.net.cn/Article/details/gtlpxsgpos.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jqgfzy.top/Article/details/gtymmgbjur.html

PHP:  get_object_vars($obj);
来源：http://dali.cdnleiting.top/Article/details/gtxlnmgpsc.html

JS:   Object.entries(obj)
来源：http://dali.zhongyouzk.top/Article/details/gtibmmxgit.html

TS:   Object.entries(obj)
来源：http://dali.xinyue.icu/Article/details/gtnpyavvdj.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.9152youxi.cn/Article/details/gtlntmkuzq.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yongpay.top/Article/details/gtgyjjrkrv.html

Ruby: obj.instance_variables
来源：http://dali.zycfv.cn/Article/details/gtpmcyhigj.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.birdmap.top/Article/details/gttrzgtewi.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtaleiktwb.html

H. 异常与错误处理
来源：http://dali.jiagoushi.top/Article/details/gtbgvrfddd.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtjpnrjqnk.html

[H01] try / catch 基础
来源：http://dali.hysaishi.cn/Article/details/gttfcbdiyp.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.gogol.net.cn/Article/details/gtqvoeykrk.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.guowangkeji.top/Article/details/gtmyopjcbu.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.havefunace.top/Article/details/gtalbdmpys.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.dianchejie.cn/Article/details/gtinuferwc.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.kuanghao11.cn/Article/details/gtummrkjir.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.dashuyun.cn/Article/details/gtriyqtwci.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.ehwqpu.com/Article/details/gtdslgkwtc.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yanxiufei.cn/Article/details/gtgqgzszwk.html

[H02] finally / ensure 收尾
来源：http://dali.yonumen.top/Article/details/gturtefhxq.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jinqigfzy.top/Article/details/gtjhfxaudh.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.chenzaomai.com/Article/details/gttrsoukhd.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ehwqpu.com/Article/details/gtlygvvrgd.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinqigufen.top/Article/details/gtwpcemyed.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.xuetiantiany.cn/Article/details/gtxtniedon.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.cdnleiting.top/Article/details/gtntjnultx.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.tianlin.xyz/Article/details/gtopthyqbs.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.pycfn.com/Article/details/gtkwvoavis.html

[H03] 主动抛出异常
来源：http://dali.svipenyu.cn/Article/details/gtmimupwzw.html

Py:   raise ValueError("错误信息")
来源：http://dali.zdqjudy.top/Article/details/gtmyctyigs.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.nanxuanxn.top/Article/details/gtcyjjprlq.html

JS:   throw new Error("错误信息");
来源：http://dali.hysaishi.cn/Article/details/gtvgeizncj.html

TS:   throw new Error("错误信息");
来源：http://dali.0kj1m.cn/Article/details/gtsgfrcmlp.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jqgufenzy.top/Article/details/gtybozimuh.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zdqjudy.top/Article/details/gtbhsrzjma.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.wangdashe.top/Article/details/gtvvyesvip.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.hywenlv.cn/Article/details/gtmvqkhspu.html

[H04] 自定义异常类型
来源：http://dali.dianchejie.cn/Article/details/gtumaagrmp.html

Py:   class MyError(Exception): pass
来源：http://dali.jqgfzy.top/Article/details/gtcvukvatz.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.sweek.top/Article/details/gtyizntxyz.html

JS:   class MyError extends Error {}
来源：http://dali.yueranfly.top/Article/details/gtsodtmoem.html

TS:   class MyError extends Error {}
来源：http://dali.ivvv.top/Article/details/gtpgnsmveg.html

Java: class MyException extends RuntimeException {}
来源：http://dali.andypj.xyz/Article/details/gtpshjgoyl.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.hywenlv.cn/Article/details/gtzbsbaohw.html

Ruby: class MyError < StandardError; end
来源：http://dali.ydzc1.top/Article/details/gtfoehpakn.html

C#:   class MyException : Exception {}
来源：http://dali.ybcxt.top/Article/details/gterclwzar.html

[H05] 捕获特定类型
来源：http://dali.ppjwa.cn/Article/details/gtcfngptwl.html

Py:   except ValueError as e:
来源：http://dali.feifeiyinyue.top/Article/details/gtuzgmbzhz.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yongpay.top/Article/details/gtembbekeb.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.sweek.top/Article/details/gtiimuhzdy.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.hnqzz.top/Article/details/gtgmmxkhod.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.dashuyun.cn/Article/details/gtwwcacxxj.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.kuanghao11.cn/Article/details/gthrgseujj.html

Ruby: rescue ArgumentError => e
来源：http://dali.yj20258888.top/Article/details/gtehdjvvqn.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtifxsdyso.html

[H06] 可选值 / 空值安全访问
来源：http://dali.cucudq.cn/Article/details/gtcfqlevfj.html

Py:   value = d.get("k") or default
来源：http://dali.gaohongyu789.top/Article/details/gtzzfuntsy.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jlsjyb.cn/Article/details/gthhwwsnhn.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.shangyingyoupin.top/Article/details/gtffhewktm.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.shzxlz.cn/Article/details/gtzollddmj.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.xinyue.icu/Article/details/gtbsyaijlz.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.shuidangran.top/Article/details/gtuoclyznp.html

Ruby: d&.dig(:a, :b)
来源：http://dali.cqqwz.cn/Article/details/gtizehxovc.html

C#:   obj?.A?.B ?? default
来源：http://dali.ivvv.top/Article/details/gtbkztfelv.html

[H07] 断言
来源：http://dali.ydzc1.top/Article/details/gtxyngvtth.html

Py:   assert x > 0, "必须为正"
来源：http://dali.ydzc1.top/Article/details/gtobkihcxt.html

PHP:  assert($x > 0);
来源：http://dali.pengpengdd.cyou/Article/details/gthlbrlzrg.html

JS:   console.assert(x > 0);
来源：http://dali.xuanzx.com/Article/details/gtkmpubiao.html

TS:   console.assert(x > 0);
来源：http://dali.smart0.xyz/Article/details/gtqngcskrd.html

Java: assert x > 0 : "必须为正";
来源：http://dali.cashguo.top/Article/details/gthgtclxbb.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.shuidangran.top/Article/details/gtfrhjkfad.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.gotoacloud.top/Article/details/gtmyuinxiq.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jlsjyb.cn/Article/details/gtoujahbmb.html

[H08] 获取错误信息与堆栈
来源：http://dali.gaohongyu789.top/Article/details/gtixedpukx.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yueranfly.top/Article/details/gtbrdfimag.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwvydwxaa.html

JS:   e.message;  e.stack
来源：http://dali.gogol.net.cn/Article/details/gtatjoqyyp.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zycfv.cn/Article/details/gtlahsdvnq.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zdqjudy.top/Article/details/gtfhmqkuno.html

Go:   err.Error()
来源：http://dali.gotoacloud.top/Article/details/gttzlzyesx.html

Ruby: e.message;  e.backtrace
来源：http://dali.daxiang520.top/Article/details/gtvfwhgofd.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jinghuilouyu.cn/Article/details/gtexdhpqrr.html

[H09] 带错误码的异常
来源：http://dali.yuxming.cn/Article/details/gtaovknnka.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.sysykeji.top/Article/details/gtlmyvtewz.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yuxming.cn/Article/details/gtlngumvps.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.chenlongwang.top/Article/details/gtwthjrytr.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.snrcjt.cn/Article/details/gtcgrotggn.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yangfankeji.com/Article/details/gtfpkevmkv.html


<!-- 参考信息 -->