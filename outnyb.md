代发 wailian999

JS:   fs.unlinkSync("a.txt")
来源：http://dali.hammf.cn/Article/details/gtyrzimjcy.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtdhafvktq.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yuxming.cn/Article/details/gtnwnvvoee.html

Go:   os.Remove("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtcgppcqtr.html

Ruby: File.delete("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtxxqdyuug.html

C#:   File.Delete("a.txt");
来源：http://dali.xuanzx.com/Article/details/gtukhbyypn.html

[F07] 创建目录（含多级）
来源：http://dali.tianlin.xyz/Article/details/gtxttzjoap.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.xinyue.icu/Article/details/gtubnlfkfc.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yongpay.top/Article/details/gtafzvkavi.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.aibaodan.cn/Article/details/gtaxgouovx.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cqqwz.cn/Article/details/gttigsoufl.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.vqdsnc.cn/Article/details/gtdyaqgkgz.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yj20258.top/Article/details/gtlzmznubk.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.ydzc1.top/Article/details/gtjaikbvmp.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.chenjidiqi.icu/Article/details/gtwjjmkrsu.html

[F08] 遍历目录
来源：http://dali.vqdsnc.cn/Article/details/gtxqgxqshq.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.hysaishi.cn/Article/details/gtjogwgsmf.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.c1oappe.top/Article/details/gtkxqbweqw.html

JS:   fs.readdirSync("dir")
来源：http://dali.0kj1m.cn/Article/details/gtkskmehsz.html

TS:   fs.readdirSync("dir")
来源：http://dali.hywenlv.cn/Article/details/gtvwbiqyce.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhixingplan.top/Article/details/gtoaufqsfn.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.shuidangran.top/Article/details/gtfjarwwaz.html

Ruby: Dir.children("dir")
来源：http://dali.yuxming.cn/Article/details/gtwehuwrhn.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hfpthk.cn/Article/details/gttslcxfdi.html

[F09] 获取文件大小
来源：http://dali.pengpengdd.cyou/Article/details/gtiymwnnjt.html

Py:   os.path.getsize("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtqszyjeqf.html

PHP:  filesize("a.txt");
来源：http://dali.yvedp.cn/Article/details/gtzezlolat.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jiagoushi.top/Article/details/gtnozpoxuh.html

TS:   fs.statSync("a.txt").size
来源：http://dali.cashguo.top/Article/details/gtnzovsiap.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jyoumei.cn/Article/details/gtgedtfoiy.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhengqikj.top/Article/details/gtambqiybt.html

Ruby: File.size("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtcqvtoxua.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yuanzhike.top/Article/details/gtpfqlfhev.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.0kj1m.cn/Article/details/gtvpcfmygn.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtpjpwgzgf.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.ydzc1.top/Article/details/gtaxxhcoof.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.daxiang520.top/Article/details/gtgscqztit.html

TS:   path.extname("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtijvwwbkd.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.xuetiantiany.cn/Article/details/gtwqxkwrxn.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtuhbdfjob.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yj20258.top/Article/details/gtlcspiowf.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzdyazydy.html

[F11] 复制与移动文件
来源：http://dali.nwbrower.top/Article/details/gtfsjsdifa.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yj20258.top/Article/details/gtncuxbwoj.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jiagoushi.top/Article/details/gtjoastcfu.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xinyue.icu/Article/details/gtkmscselb.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yonumen.top/Article/details/gtimmsvoed.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.aizwys.cn/Article/details/gtfgfvkxyp.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.feifeiyinyue.top/Article/details/gtbvkpacid.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.dianchejie.cn/Article/details/gtohfglebr.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.hammf.cn/Article/details/gtnfapdlku.html

[F12] CSV 读写
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaxvnkvxy.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhengqikj.top/Article/details/gtkffwhijo.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.ydzc1.top/Article/details/gtfeygvisc.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.xylfe.cn/Article/details/gtujobkahd.html

TS:   // 同上
来源：http://dali.chenjidiqi.icu/Article/details/gtlcyvryre.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.gogol.net.cn/Article/details/gtdyjuralt.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.ybcxt.top/Article/details/gttzrkdiwc.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhoulong.xyz/Article/details/gtegisggcm.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.haohaochexian.top/Article/details/gtyjrjznjo.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtmncqcgqk.html

G. 面向对象
来源：http://dali.daxiang520.top/Article/details/gthnnylmfy.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtmamqwvne.html

[G01] 定义类
来源：http://dali.kuanghao11.cn/Article/details/gtaqeutiea.html

Py:   class User: pass
来源：http://dali.hysaishi.cn/Article/details/gtynflhsev.html

PHP:  class User {}
来源：http://dali.daxiang520.top/Article/details/gtmeovfgih.html

JS:   class User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtuuvbwcgy.html

TS:   class User { name: string = ""; }
来源：http://dali.cucudq.cn/Article/details/gtkxmldycx.html

Java: class User {}
来源：http://dali.guannengcc.top/Article/details/gtscetpnxo.html

Go:   type User struct { Name string }
来源：http://dali.yuxming.cn/Article/details/gtakviwxxt.html

Ruby: class User; end
来源：http://dali.jyoumei.cn/Article/details/gtzvkympto.html

C#:   class User {}
来源：http://dali.yongpay.top/Article/details/gtswxbtxbs.html

[G02] 构造函数
来源：http://dali.zycfv.cn/Article/details/gtphrsgiza.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.hammf.cn/Article/details/gtgyltcjfq.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.xziqi.cn/Article/details/gtafjwgxmq.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jinqigufen.top/Article/details/gtipvxresi.html

TS:   constructor(public name: string) {}
来源：http://dali.shuidangran.top/Article/details/gtxnbgwmsx.html

Java: User(String name) { this.name = name; }
来源：http://dali.jianghu66.top/Article/details/gtboohmzen.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.shuidangran.top/Article/details/gtcozkwpaz.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.xuetiantiany.cn/Article/details/gtgzooayri.html

C#:   public User(string name) { Name = name; }
来源：http://dali.ppjwa.cn/Article/details/gtbsqekmrv.html

[G03] 实例属性
来源：http://dali.snrcjt.cn/Article/details/gthixipspe.html

Py:   self.name = "x"
来源：http://dali.zhongyouzk.top/Article/details/gthfotyawd.html

PHP:  public string $name = "x";
来源：http://dali.yongpay.top/Article/details/gtcssjpnow.html

JS:   this.name = "x";
来源：http://dali.ppjwa.cn/Article/details/gtxzokxbwe.html

TS:   name: string = "x";
来源：http://dali.guowangkeji.top/Article/details/gtdpszpscw.html

Java: private String name;
来源：http://dali.jinqigufen.top/Article/details/gtgzwwmiby.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.redwolf501.top/Article/details/gtrzmghcux.html

Ruby: @name = "x"
来源：http://dali.shzxlz.cn/Article/details/gthjhltahs.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.hnxiangtu.top/Article/details/gtrfuyttgo.html

[G04] 定义方法
来源：http://dali.jinqigfzy.top/Article/details/gtdvttafzm.html

Py:   def greet(self): return self.name
来源：http://dali.sysykeji.top/Article/details/gtlvivstog.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.redwolf501.top/Article/details/gtvpgkrdnp.html

JS:   greet() { return this.name; }
来源：http://dali.andypj.xyz/Article/details/gtyddiklke.html

TS:   greet(): string { return this.name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtceifhlvt.html

Java: String greet() { return name; }
来源：http://dali.hywenlv.cn/Article/details/gtlrowxzsh.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.nanxuanxn.top/Article/details/gtrjvollju.html

Ruby: def greet; @name; end
来源：http://dali.daria6918.cn/Article/details/gtdtcimgob.html

C#:   public string Greet() => Name;
来源：http://dali.xuanzx.com/Article/details/gtbblnfzlo.html

[G05] 继承
来源：http://dali.c1oappe.top/Article/details/gtjeblluyp.html

Py:   class Admin(User): pass
来源：http://dali.zycfv.cn/Article/details/gtlxsrfewq.html

PHP:  class Admin extends User {}
来源：http://dali.tian-w.cn/Article/details/gtxvbrgwyy.html

JS:   class Admin extends User {}
来源：http://dali.shangyingyoupin.top/Article/details/gtoctlwuga.html

TS:   class Admin extends User {}
来源：http://dali.jqgufenzy.top/Article/details/gtuqgoaugi.html

Java: class Admin extends User {}
来源：http://dali.wangdashe.top/Article/details/gtcnpranhj.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.aibaodan.cn/Article/details/gtyohczxvw.html

Ruby: class Admin < User; end
来源：http://dali.ybcxt.top/Article/details/gtnhceehgi.html

C#:   class Admin : User {}
来源：http://dali.hnqzz.top/Article/details/gtdajzxgme.html

[G06] 重写方法
来源：http://dali.daxiang520.top/Article/details/gtewjuzkwc.html

Py:   def greet(self): return "admin"
来源：http://dali.zhongyouzk.top/Article/details/gthkhaqdla.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtlyhqcdrj.html

JS:   greet() { return "admin"; }
来源：http://dali.zhongyouzk.top/Article/details/gtlbklpshk.html

TS:   greet(): string { return "admin"; }
来源：http://dali.kuanghao11.cn/Article/details/gtaewdkngf.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.sweek.top/Article/details/gtgtidrmrq.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yvedp.cn/Article/details/gtkkwghmzf.html

Ruby: def greet; "admin"; end
来源：http://dali.ydzc1.top/Article/details/gtljwpjluj.html

C#:   public override string Greet() => "admin";
来源：http://dali.jianghu66.top/Article/details/gtidwxikoq.html

[G07] 调用父类方法
来源：http://dali.hammf.cn/Article/details/gttdqfqhlc.html

Py:   super().greet()
来源：http://dali.iojbl.cn/Article/details/gtvfwrxzii.html

PHP:  parent::greet();
来源：http://dali.yangfankeji.com/Article/details/gtiejvrmln.html

JS:   super.greet();
来源：http://dali.jiagoushi.top/Article/details/gttumkfzrn.html

TS:   super.greet();
来源：http://dali.jlsjyb.cn/Article/details/gtbgzirvlj.html

Java: super.greet();
来源：http://dali.xziqi.cn/Article/details/gtobwhaqco.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.pycfn.com/Article/details/gtahkasgma.html

Ruby: super
来源：http://dali.jinghuilouyu.cn/Article/details/gtnkqeipoh.html

C#:   base.Greet();
来源：http://dali.jiagoushi.top/Article/details/gtoggybzjb.html

[G08] 静态方法与属性
来源：http://dali.hnxiangtu.top/Article/details/gthnzikwyx.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.0kj1m.cn/Article/details/gtdnwkeciy.html

PHP:  public static function f() {}
来源：http://dali.jinghuilouyu.cn/Article/details/gteikvvhhw.html

JS:   static f() {}
来源：http://dali.sysykeji.top/Article/details/gtnmepsfep.html

TS:   static f(): void {}
来源：http://dali.smart0.xyz/Article/details/gtcgiwujbo.html

Java: static void f() {}
来源：http://dali.guannengcc.top/Article/details/gtuenhsaey.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.wangdashe.top/Article/details/gtdjvjgvle.html

Ruby: def self.f; end
来源：http://dali.smart0.xyz/Article/details/gtvhtgwjwh.html

C#:   public static void F() {}
来源：http://dali.c1oappe.top/Article/details/gtrxujyifm.html

[G09] 接口 / 抽象类
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjxzklhic.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.sxryk.cn/Article/details/gtpcntyqdt.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.chenjidiqi.icu/Article/details/gtsyjvolos.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ywan-chungtsiang.top/Article/details/gtofnxadlj.html

TS:   interface Shape { area(): number; }
来源：http://dali.sysykeji.top/Article/details/gtuhsytomh.html

Java: interface Shape { double area(); }
来源：http://dali.xylfe.cn/Article/details/gtkambldqg.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.redwolf501.top/Article/details/gtwtdezfsw.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.quarkkingdee.top/Article/details/gtitjkexmy.html

C#:   interface IShape { double Area(); }
来源：http://dali.guowangkeji.top/Article/details/gtfpmblgsx.html

[G10] 访问控制
来源：http://dali.feifeiyinyue.top/Article/details/gtwqbgmjhi.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.kuanghao11.cn/Article/details/gtyaieqkcw.html

PHP:  public / protected / private
来源：http://dali.aizwys.cn/Article/details/gtfspbeabi.html

JS:   #private 字段；其余公开
来源：http://dali.0kj1m.cn/Article/details/gtldltygil.html

TS:   public / protected / private
来源：http://dali.mhx1999.top/Article/details/gtucuchfqc.html

Java: public / protected / private / 默认包级
来源：http://dali.fzhhl.top/Article/details/gtjegbputt.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.tanke756.top/Article/details/gtvsmlnakt.html

Ruby: public / protected / private
来源：http://dali.yj202588.top/Article/details/gtxbsuuynv.html

C#:   public / protected / private / internal
来源：http://dali.yangfankeji.com/Article/details/gtizryvnmn.html

[G11] getter / setter
来源：http://dali.svipenyu.cn/Article/details/gtgyofkjps.html

Py:   @property 与 @x.setter
来源：http://dali.cqqwz.cn/Article/details/gtwdspfrbz.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gthuqppfzp.html

JS:   get name() { return this._name; }
来源：http://dali.zhixingplan.top/Article/details/gtxwqudsii.html

TS:   get name(): string { return this._name; }
来源：http://dali.yuxming.cn/Article/details/gtemavykfu.html

Java: public String getName() { return name; }
来源：http://dali.tianlin.xyz/Article/details/gtjzvclbhi.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.bjfxy.top/Article/details/gtxhjdzuzy.html

Ruby: attr_accessor :name
来源：http://dali.sufxvd.cn/Article/details/gttvhlbfye.html

C#:   public string Name { get; set; }
来源：http://dali.mhx1999.top/Article/details/gtjcgnmlws.html

[G12] 对象转字符串
来源：http://dali.cashguo.top/Article/details/gtdezdxgpn.html

Py:   def __str__(self): return self.name
来源：http://dali.hfpthk.cn/Article/details/gtqdbgfjyd.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yvedp.cn/Article/details/gtfofctjnh.html

JS:   toString() { return this.name; }
来源：http://dali.chenzaomai.com/Article/details/gtfsykzanx.html

TS:   toString(): string { return this.name; }
来源：http://dali.c1oappe.top/Article/details/gtoxhfnucy.html

Java: @Override public String toString() { return name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gttsqpmmpa.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.cqqwz.cn/Article/details/gtjgjppcen.html

Ruby: def to_s; @name; end
来源：http://dali.9152youxi.cn/Article/details/gtukyqsekw.html

C#:   public override string ToString() => Name;
来源：http://dali.jinghuilouyu.cn/Article/details/gtqimofjbw.html

[G13] 判断对象类型
来源：http://dali.tianlin.xyz/Article/details/gtkbugxdlv.html

Py:   isinstance(u, User)
来源：http://dali.redwolf501.top/Article/details/gtgthffdke.html

PHP:  $u instanceof User
来源：http://dali.jyoumei.cn/Article/details/gtfbeaeazn.html

JS:   u instanceof User
来源：http://dali.guannengcc.top/Article/details/gtqzuirvxs.html

TS:   u instanceof User
来源：http://dali.ehwqpu.com/Article/details/gttphwgggd.html

Java: u instanceof User
来源：http://dali.yueranfly.top/Article/details/gtppgohdlb.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtupbyngzu.html

Ruby: u.is_a?(User)
来源：http://dali.tianlin.xyz/Article/details/gtqylyrxui.html

C#:   u is User
来源：http://dali.hnqzz.top/Article/details/gtevbjmbru.html

[G14] 数据类 / record
来源：http://dali.zdqjudy.top/Article/details/gtitrjmrfk.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.316326.xyz/Article/details/gtblgmzstn.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.sweek.top/Article/details/gtbnhomhpp.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.snrcjt.cn/Article/details/gtgkueqlyg.html

TS:   type User = { name: string; age: number };
来源：http://dali.yj202588.top/Article/details/gtpgwrqegk.html

Java: record User(String name, int age) {}
来源：http://dali.xinyue.icu/Article/details/gtwmxwwqdg.html

Go:   type User struct { Name string; Age int }
来源：http://dali.dianchejie.cn/Article/details/gtmnairjat.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.havefunace.top/Article/details/gtqtowoiec.html

C#:   record User(string Name, int Age);
来源：http://dali.nanxinkj.top/Article/details/gtzanoooio.html

[G15] 枚举
来源：http://dali.vqdsnc.cn/Article/details/gttjnzcfqi.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yj20258888.top/Article/details/gtxnedqfqo.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jianghu66.top/Article/details/gtkpulylkp.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkqvikbfo.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cheryme.top/Article/details/gtjfukgthn.html

Java: enum Color { RED, GREEN }
来源：http://dali.havefunace.top/Article/details/gtjnbjubyz.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.xuanzx.com/Article/details/gtrjhinwom.html

Ruby: Color = %i[red green].freeze
来源：http://dali.nwbrower.top/Article/details/gtazzrymyg.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yuanzhike.top/Article/details/gtkpxgcusi.html

[G16] 对象转数组 / 字典
来源：http://dali.kuanghao11.cn/Article/details/gtukzghnum.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.bjfxy.top/Article/details/gtskenqbfz.html

PHP:  get_object_vars($obj);
来源：http://dali.hnxiangtu.top/Article/details/gtionswmty.html

JS:   Object.entries(obj)
来源：http://dali.xuanzx.com/Article/details/gteagijroj.html

TS:   Object.entries(obj)
来源：http://dali.andypj.xyz/Article/details/gthemdrlkn.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yj20258888.top/Article/details/gtxsbojunh.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhiwuduotai.top/Article/details/gtlxtfozii.html

Ruby: obj.instance_variables
来源：http://dali.gaohongyu789.top/Article/details/gtaxlfvnba.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.cdnleiting.top/Article/details/gtrmpduchm.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtccwcmvvu.html

H. 异常与错误处理
来源：http://dali.yangfankeji.com/Article/details/gtkytcylgs.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtbbwbtbik.html

[H01] try / catch 基础
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmqfsmida.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.fengsongda.top/Article/details/gtmkvrcsls.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zycfv.cn/Article/details/gtarzboaoc.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jyoumei.cn/Article/details/gtrzymxkji.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.kuanghao11.cn/Article/details/gtmpmssjfv.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zdqjudy.top/Article/details/gtaaaoedma.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.cashguo.top/Article/details/gtqiqwwhpu.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.gzhubu.top/Article/details/gtzrsuktsp.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.sweek.top/Article/details/gtgtjukami.html

[H02] finally / ensure 收尾
来源：http://dali.yvedp.cn/Article/details/gtyitfufjd.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.cdnleiting.top/Article/details/gtiwokbvsc.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yj202588.top/Article/details/gtxlpkwxcs.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.meibo888.top/Article/details/gtgjmdqimb.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.svipenyu.cn/Article/details/gtpcmbvbkm.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.daxiang520.top/Article/details/gtiacingrk.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yj20258.top/Article/details/gtysdmokpd.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.fzhhl.top/Article/details/gtgkchcfwi.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.cashguo.top/Article/details/gtikyosqwt.html

[H03] 主动抛出异常
来源：http://dali.yongpay.top/Article/details/gttsenslte.html

Py:   raise ValueError("错误信息")
来源：http://dali.shanyushiyangtech.top/Article/details/gtzvguxpkb.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.smart0.xyz/Article/details/gtikaqmurt.html

JS:   throw new Error("错误信息");
来源：http://dali.zhongyouzk.top/Article/details/gtzxrxdwcx.html

TS:   throw new Error("错误信息");
来源：http://dali.cheryme.top/Article/details/gtnhnofenc.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.ybcxt.top/Article/details/gtwmszwxiw.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.aibaodan.cn/Article/details/gtpmeodiua.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hammf.cn/Article/details/gtwjbsseav.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.wangshuangyany.cn/Article/details/gteienuhne.html

[H04] 自定义异常类型
来源：http://dali.wangdashe.top/Article/details/gtfuzikoks.html

Py:   class MyError(Exception): pass
来源：http://dali.shanyushiyangtech.top/Article/details/gtflzfmzny.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.pengpengdd.cyou/Article/details/gthrdeqvhi.html

JS:   class MyError extends Error {}
来源：http://dali.bjfxy.top/Article/details/gtyirpshym.html

TS:   class MyError extends Error {}
来源：http://dali.smart0.xyz/Article/details/gtclfmucof.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hongshengwenyu.top/Article/details/gtchhgsdpg.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.chenlongwang.top/Article/details/gtsmwzgpvh.html

Ruby: class MyError < StandardError; end
来源：http://dali.yj20258888.top/Article/details/gtghxuoatg.html

C#:   class MyException : Exception {}
来源：http://dali.yonumen.top/Article/details/gtwnynllmg.html

[H05] 捕获特定类型
来源：http://dali.hammf.cn/Article/details/gtsomcclqx.html

Py:   except ValueError as e:
来源：http://dali.zhongyouzk.top/Article/details/gtdsipsbcx.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.nanxuanxn.top/Article/details/gteebnotdn.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.hywenlv.cn/Article/details/gtahrlmuma.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.dianchejie.cn/Article/details/gtanasynah.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yongpay.top/Article/details/gtoldlmupa.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jqgfzy.top/Article/details/gtjpxemzmi.html

Ruby: rescue ArgumentError => e
来源：http://dali.yongpay.top/Article/details/gtrsuuwxic.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.iojbl.cn/Article/details/gtoplwtchj.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhengqikj.top/Article/details/gtcwsrweit.html

Py:   value = d.get("k") or default
来源：http://dali.bjfxy.top/Article/details/gtuoyivgco.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.bjfxy.top/Article/details/gtdmovamak.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.sufxvd.cn/Article/details/gtayomlbta.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hywenlv.cn/Article/details/gtujftroko.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.dianchejie.cn/Article/details/gtzobazhfo.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhongyouzk.top/Article/details/gtfdmzabwc.html

Ruby: d&.dig(:a, :b)
来源：http://dali.guannengcc.top/Article/details/gtdqawkjjn.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhijiandao.cn/Article/details/gtbxscdghk.html

[H07] 断言
来源：http://dali.daxiang520.top/Article/details/gtwlmcjmct.html

Py:   assert x > 0, "必须为正"
来源：http://dali.gogol.net.cn/Article/details/gtdpaaaany.html

PHP:  assert($x > 0);
来源：http://dali.svipenyu.cn/Article/details/gtkgaovzqt.html

JS:   console.assert(x > 0);
来源：http://dali.jinqigufen.top/Article/details/gtkuvkcsbf.html

TS:   console.assert(x > 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gthkcccceq.html

Java: assert x > 0 : "必须为正";
来源：http://dali.ywan-chungtsiang.top/Article/details/gthcmmbozj.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwdurfgmg.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jinqigufen.top/Article/details/gtmnriebzz.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yanxiufei.cn/Article/details/gtyjojqhhs.html

[H08] 获取错误信息与堆栈
来源：http://dali.yuanzhike.top/Article/details/gtzqdhsqtm.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.smart0.xyz/Article/details/gtobxsglay.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.nwbrower.top/Article/details/gtaotjxdic.html

JS:   e.message;  e.stack
来源：http://dali.ppjwa.cn/Article/details/gtbkpulrkr.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.birdmap.top/Article/details/gtjpxvkoin.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnjvwhwxq.html

Go:   err.Error()
来源：http://dali.mhx1999.top/Article/details/gtadjlptlg.html

Ruby: e.message;  e.backtrace
来源：http://dali.cucudq.cn/Article/details/gtgyxliivi.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hywenlv.cn/Article/details/gtpzpkslmk.html

[H09] 带错误码的异常
来源：http://dali.zhengqikj.top/Article/details/gtussipwrn.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.c1oappe.top/Article/details/gtrqhevque.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.redwolf501.top/Article/details/gtwimcclim.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.wangshuangyany.cn/Article/details/gtgjzrajcw.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.ivvv.top/Article/details/gtooiyaibb.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtnbefuqrf.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrfpagzdp.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.ybcxt.top/Article/details/gtglmwmflh.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.feifeiyinyue.top/Article/details/gtaatjdtut.html

[H10] 资源自动释放
来源：http://dali.bjfxy.top/Article/details/gthrzjtzob.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.ivvv.top/Article/details/gtzteesvjh.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.kuanghao11.cn/Article/details/gtzjxhtfuf.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jyoumei.cn/Article/details/gtsagdfkaw.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hongshengwenyu.top/Article/details/gtuftxcudr.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.c1oappe.top/Article/details/gtiaphcetn.html

Go:   defer f.Close()
来源：http://dali.xylfe.cn/Article/details/gttyjusxub.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.feifeiyinyue.top/Article/details/gttainokht.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.aizwys.cn/Article/details/gtkhckbtpb.html


<!-- 参考信息 -->