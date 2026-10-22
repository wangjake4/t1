代发 wailian999

C#:   File.Exists("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtzrjacqir.html

[F06] 删除文件
来源：http://dali.feifeiyinyue.top/Article/details/gtykxjevdj.html

Py:   os.remove("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtcjgbxnfu.html

PHP:  unlink("a.txt");
来源：http://dali.iojbl.cn/Article/details/gtfidoiguv.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.pycfn.com/Article/details/gtjhcsaycp.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.cashguo.top/Article/details/gteddvdvhd.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmysjbwiz.html

Go:   os.Remove("a.txt")
来源：http://dali.daxiang520.top/Article/details/gtfxhlxaky.html

Ruby: File.delete("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtdqvpsqfr.html

C#:   File.Delete("a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gtddthxeux.html

[F07] 创建目录（含多级）
来源：http://dali.gotoacloud.top/Article/details/gturemraes.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.sxryk.cn/Article/details/gttvjzffrm.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtemtrdulr.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yuxming.cn/Article/details/gtljltuxkt.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcijymlzp.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.nanxuanxn.top/Article/details/gtodbvreuy.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.xylfe.cn/Article/details/gtwzkquidk.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yueranfly.top/Article/details/gtykdnejtx.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jinqigufen.top/Article/details/gtacqfcfef.html

[F08] 遍历目录
来源：http://dali.gotoacloud.top/Article/details/gtptisnviv.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.chenjidiqi.icu/Article/details/gthimojlcn.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.birdmap.top/Article/details/gtvvwfuudj.html

JS:   fs.readdirSync("dir")
来源：http://dali.tanke756.top/Article/details/gtnihhjcwh.html

TS:   fs.readdirSync("dir")
来源：http://dali.xinyue.icu/Article/details/gtycpgdown.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.sxryk.cn/Article/details/gtbswivybr.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.hammf.cn/Article/details/gteelzsiiq.html

Ruby: Dir.children("dir")
来源：http://dali.zycfv.cn/Article/details/gtgqtpxkiq.html

C#:   Directory.GetFiles("dir")
来源：http://dali.ehwqpu.com/Article/details/gtuaggidqr.html

[F09] 获取文件大小
来源：http://dali.havefunace.top/Article/details/gtwlakzebl.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtaadidebq.html

PHP:  filesize("a.txt");
来源：http://dali.svipenyu.cn/Article/details/gtimvftmbw.html

JS:   fs.statSync("a.txt").size
来源：http://dali.ydzc1.top/Article/details/gtsuldzjah.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yanxiufei.cn/Article/details/gtjnxgmfkz.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zdqjudy.top/Article/details/gtxmofevfp.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.tanke756.top/Article/details/gtkspdqgfc.html

Ruby: File.size("a.txt")
来源：http://dali.yj20258.top/Article/details/gtslfwayon.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yuanzhike.top/Article/details/gtpqmijkem.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yj20258.top/Article/details/gtqnzevxus.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtpmnnxhzb.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gtjayweocv.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtvkdriiio.html

TS:   path.extname("a.txt")
来源：http://dali.cheryme.top/Article/details/gtfnenqkvp.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.ehwqpu.com/Article/details/gtcoxbjfpu.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.cheryme.top/Article/details/gtpjsngtyx.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.redwolf501.top/Article/details/gtdltdivdv.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yj202588.top/Article/details/gtzntaudbt.html

[F11] 复制与移动文件
来源：http://dali.yangfankeji.com/Article/details/gtwioxnxev.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtudiunbym.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.iojbl.cn/Article/details/gtuocpasok.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.fzhhl.top/Article/details/gtiapkbiow.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ehwqpu.com/Article/details/gtvpoihtuk.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.chenlongwang.top/Article/details/gtceybfscq.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.redwolf501.top/Article/details/gtgooqmgvg.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.daxiang520.top/Article/details/gtpbhmgdqx.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.sweek.top/Article/details/gtuidvpqty.html

[F12] CSV 读写
来源：http://dali.hysaishi.cn/Article/details/gtfxcgwqmv.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.kuanghao11.cn/Article/details/gtebpruwuo.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaakholhf.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.chenzaomai.com/Article/details/gtmeovniqk.html

TS:   // 同上
来源：http://dali.birdmap.top/Article/details/gtayaqcjmk.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zdqjudy.top/Article/details/gtmpeuvbvm.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.shzxlz.cn/Article/details/gtjmwuejwe.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.wangshuangyany.cn/Article/details/gtaxopqhtd.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.tianlin.xyz/Article/details/gtdaskitsf.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gttlowdksa.html

G. 面向对象
来源：http://dali.yangfankeji.com/Article/details/gtejriawjb.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gticvdifkr.html

[G01] 定义类
来源：http://dali.xinyue.icu/Article/details/gtwbfokjfj.html

Py:   class User: pass
来源：http://dali.ehwqpu.com/Article/details/gtqxelyrmy.html

PHP:  class User {}
来源：http://dali.chenjidiqi.icu/Article/details/gtqheawhhm.html

JS:   class User {}
来源：http://dali.quarkkingdee.top/Article/details/gtdpgahmbw.html

TS:   class User { name: string = ""; }
来源：http://dali.jqgfzy.top/Article/details/gtpomkcyxg.html

Java: class User {}
来源：http://dali.xuanzx.com/Article/details/gtwxwlohij.html

Go:   type User struct { Name string }
来源：http://dali.xylfe.cn/Article/details/gtchyfqkga.html

Ruby: class User; end
来源：http://dali.gogol.net.cn/Article/details/gtpdjwyvvi.html

C#:   class User {}
来源：http://dali.hywenlv.cn/Article/details/gtkdipzcus.html

[G02] 构造函数
来源：http://dali.tian-w.cn/Article/details/gtrrdkddsa.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuanukwpf.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.ppjwa.cn/Article/details/gtkgplopqy.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gthnfraidt.html

TS:   constructor(public name: string) {}
来源：http://dali.ydzc1.top/Article/details/gtaooyvtoe.html

Java: User(String name) { this.name = name; }
来源：http://dali.zycfv.cn/Article/details/gtsfvjtgni.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.sysykeji.top/Article/details/gtqdynjmkj.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.tian-w.cn/Article/details/gtskysgvvc.html

C#:   public User(string name) { Name = name; }
来源：http://dali.tian-w.cn/Article/details/gtcvwoecfn.html

[G03] 实例属性
来源：http://dali.xinyue.icu/Article/details/gtjsjmjbge.html

Py:   self.name = "x"
来源：http://dali.yj202588.top/Article/details/gtvdaoumzc.html

PHP:  public string $name = "x";
来源：http://dali.jiagoushi.top/Article/details/gtpuzddlmd.html

JS:   this.name = "x";
来源：http://dali.yueranfly.top/Article/details/gtbckaacln.html

TS:   name: string = "x";
来源：http://dali.zhongyouzk.top/Article/details/gtatmyoqjy.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gtnocvjhsm.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.wangshuangyany.cn/Article/details/gtrmguaibv.html

Ruby: @name = "x"
来源：http://dali.pengpengdd.cyou/Article/details/gtpewfwqtz.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.hnqzz.top/Article/details/gtwgtznfiu.html

[G04] 定义方法
来源：http://dali.nanxuanxn.top/Article/details/gtatkqipky.html

Py:   def greet(self): return self.name
来源：http://dali.snrcjt.cn/Article/details/gtntauyrmq.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.xylfe.cn/Article/details/gtuhpjuxec.html

JS:   greet() { return this.name; }
来源：http://dali.fzhhl.top/Article/details/gtvhzqmeqv.html

TS:   greet(): string { return this.name; }
来源：http://dali.fengsongda.top/Article/details/gtzafiibdt.html

Java: String greet() { return name; }
来源：http://dali.birdmap.top/Article/details/gtjvtrvseu.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hnxiangtu.top/Article/details/gtpwuvgice.html

Ruby: def greet; @name; end
来源：http://dali.kuanghao11.cn/Article/details/gtjdrwedns.html

C#:   public string Greet() => Name;
来源：http://dali.shanyushiyangtech.top/Article/details/gtxlhoaved.html

[G05] 继承
来源：http://dali.jinqigfzy.top/Article/details/gtseorqqgb.html

Py:   class Admin(User): pass
来源：http://dali.yvedp.cn/Article/details/gtiohbnrhg.html

PHP:  class Admin extends User {}
来源：http://dali.yj20258.top/Article/details/gtaryxfcnz.html

JS:   class Admin extends User {}
来源：http://dali.0kj1m.cn/Article/details/gtxvrosypu.html

TS:   class Admin extends User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtllnulxcp.html

Java: class Admin extends User {}
来源：http://dali.yanxiufei.cn/Article/details/gtzkerqqef.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.havefunace.top/Article/details/gtxwaatduo.html

Ruby: class Admin < User; end
来源：http://dali.hywenlv.cn/Article/details/gttqdtoqmv.html

C#:   class Admin : User {}
来源：http://dali.316326.xyz/Article/details/gtgezvxjse.html

[G06] 重写方法
来源：http://dali.hnqzz.top/Article/details/gtolbzdxid.html

Py:   def greet(self): return "admin"
来源：http://dali.nwbrower.top/Article/details/gtvcuufbnr.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.kuanghao11.cn/Article/details/gtswypeeru.html

JS:   greet() { return "admin"; }
来源：http://dali.316326.xyz/Article/details/gtrhhabvwk.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yuanzhike.top/Article/details/gtjscbuqkc.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqrfsands.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.nwbrower.top/Article/details/gtirokpdqj.html

Ruby: def greet; "admin"; end
来源：http://dali.yvedp.cn/Article/details/gtprsyfkyk.html

C#:   public override string Greet() => "admin";
来源：http://dali.yueranfly.top/Article/details/gtqazfcpwr.html

[G07] 调用父类方法
来源：http://dali.quarkkingdee.top/Article/details/gtnhpxdncz.html

Py:   super().greet()
来源：http://dali.tanke756.top/Article/details/gtpvqakswh.html

PHP:  parent::greet();
来源：http://dali.yj20258888.top/Article/details/gtzhndgdfk.html

JS:   super.greet();
来源：http://dali.hammf.cn/Article/details/gtpqzgwrvf.html

TS:   super.greet();
来源：http://dali.zhongyouzk.top/Article/details/gtdyjgflfq.html

Java: super.greet();
来源：http://dali.guowangkeji.top/Article/details/gtyfrewcvm.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.chenjidiqi.icu/Article/details/gtnteamlhy.html

Ruby: super
来源：http://dali.smart0.xyz/Article/details/gtwvkicxjx.html

C#:   base.Greet();
来源：http://dali.andypj.xyz/Article/details/gtsuqhbcfr.html

[G08] 静态方法与属性
来源：http://dali.c1oappe.top/Article/details/gtjymuvrug.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jinqigfzy.top/Article/details/gteqtfnvtf.html

PHP:  public static function f() {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsuwxjryx.html

JS:   static f() {}
来源：http://dali.nanxinkj.top/Article/details/gtfkeciots.html

TS:   static f(): void {}
来源：http://dali.xuanzx.com/Article/details/gtwtvchzib.html

Java: static void f() {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcvbuukrd.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.xinyue.icu/Article/details/gtfmnmgzwy.html

Ruby: def self.f; end
来源：http://dali.cheryme.top/Article/details/gtiyfqxnys.html

C#:   public static void F() {}
来源：http://dali.tianlin.xyz/Article/details/gtqbslkzgw.html

[G09] 接口 / 抽象类
来源：http://dali.zhiwuduotai.top/Article/details/gtqirtrira.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.gogol.net.cn/Article/details/gtnvfqjdrt.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.guowangkeji.top/Article/details/gtbdptsmxv.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoegudnjx.html

TS:   interface Shape { area(): number; }
来源：http://dali.aibaodan.cn/Article/details/gtlapidaed.html

Java: interface Shape { double area(); }
来源：http://dali.jyoumei.cn/Article/details/gtqtnxrkyc.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhijiandao.cn/Article/details/gtgokljcei.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jlsjyb.cn/Article/details/gtpvcbveaf.html

C#:   interface IShape { double Area(); }
来源：http://dali.sweek.top/Article/details/gtzbejjlnx.html

[G10] 访问控制
来源：http://dali.xuetiantiany.cn/Article/details/gtjdwinigz.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.ydzc1.top/Article/details/gtyhdeorvt.html

PHP:  public / protected / private
来源：http://dali.xylfe.cn/Article/details/gtvvnfbwgk.html

JS:   #private 字段；其余公开
来源：http://dali.zhixingplan.top/Article/details/gtpdemltjy.html

TS:   public / protected / private
来源：http://dali.xylfe.cn/Article/details/gtatdffovg.html

Java: public / protected / private / 默认包级
来源：http://dali.hywenlv.cn/Article/details/gtnqpevgez.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.tianlin.xyz/Article/details/gtdrtpcljk.html

Ruby: public / protected / private
来源：http://dali.mhx1999.top/Article/details/gthxjokrmj.html

C#:   public / protected / private / internal
来源：http://dali.guowangkeji.top/Article/details/gtsbieocqc.html

[G11] getter / setter
来源：http://dali.hongshengwenyu.top/Article/details/gtndxbilzr.html

Py:   @property 与 @x.setter
来源：http://dali.cashguo.top/Article/details/gttguxjrkn.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.svipenyu.cn/Article/details/gtvlrmquxz.html

JS:   get name() { return this._name; }
来源：http://dali.yj20258.top/Article/details/gthtxoocof.html

TS:   get name(): string { return this._name; }
来源：http://dali.cqqwz.cn/Article/details/gtycgzncge.html

Java: public String getName() { return name; }
来源：http://dali.hnqzz.top/Article/details/gtuoiwawqc.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.sufxvd.cn/Article/details/gtnmclltel.html

Ruby: attr_accessor :name
来源：http://dali.hywenlv.cn/Article/details/gtuuvnkual.html

C#:   public string Name { get; set; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtiowgjusr.html

[G12] 对象转字符串
来源：http://dali.aizwys.cn/Article/details/gtkztajsjp.html

Py:   def __str__(self): return self.name
来源：http://dali.kuanghao11.cn/Article/details/gtnmogqdzy.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yuanzhike.top/Article/details/gtuvcuwieh.html

JS:   toString() { return this.name; }
来源：http://dali.smart0.xyz/Article/details/gtjamekfcu.html

TS:   toString(): string { return this.name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtnusdyowp.html

Java: @Override public String toString() { return name; }
来源：http://dali.sxryk.cn/Article/details/gtvewwazib.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yueranfly.top/Article/details/gtiiqgsbln.html

Ruby: def to_s; @name; end
来源：http://dali.ppjwa.cn/Article/details/gttmvwpbjl.html

C#:   public override string ToString() => Name;
来源：http://dali.ydzc1.top/Article/details/gtwtpcbkiu.html

[G13] 判断对象类型
来源：http://dali.yueranfly.top/Article/details/gtyzbpvket.html

Py:   isinstance(u, User)
来源：http://dali.yj20258888.top/Article/details/gtlercbbql.html

PHP:  $u instanceof User
来源：http://dali.pengpengdd.cyou/Article/details/gtsoesozxi.html

JS:   u instanceof User
来源：http://dali.c1oappe.top/Article/details/gtfsqdjzaa.html

TS:   u instanceof User
来源：http://dali.hammf.cn/Article/details/gtjixozpgc.html

Java: u instanceof User
来源：http://dali.guannengcc.top/Article/details/gtjrurtzya.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jlsjyb.cn/Article/details/gthklrbqad.html

Ruby: u.is_a?(User)
来源：http://dali.aibaodan.cn/Article/details/gtvrppture.html

C#:   u is User
来源：http://dali.pycfn.com/Article/details/gtmhvuhhjm.html

[G14] 数据类 / record
来源：http://dali.chenjidiqi.icu/Article/details/gtvguosgrq.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.gaohongyu789.top/Article/details/gthsbustdi.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.sufxvd.cn/Article/details/gtlyyyzrrw.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.ydzc1.top/Article/details/gtlrhsmvhz.html

TS:   type User = { name: string; age: number };
来源：http://dali.ehwqpu.com/Article/details/gtfzjwpwnq.html

Java: record User(String name, int age) {}
来源：http://dali.hnxiangtu.top/Article/details/gthvnoocls.html

Go:   type User struct { Name string; Age int }
来源：http://dali.ehwqpu.com/Article/details/gtxnrnrati.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.redwolf501.top/Article/details/gttygqadoi.html

C#:   record User(string Name, int Age);
来源：http://dali.cheryme.top/Article/details/gtsqgkxdif.html

[G15] 枚举
来源：http://dali.hnqzz.top/Article/details/gtudznyrsm.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.mhx1999.top/Article/details/gteimnpbzg.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jlsjyb.cn/Article/details/gtbovahknj.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.fzhhl.top/Article/details/gtdmmmlclq.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.dashuyun.cn/Article/details/gtejusixyp.html

Java: enum Color { RED, GREEN }
来源：http://dali.zycfv.cn/Article/details/gtenlmeflj.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yvedp.cn/Article/details/gtprxsqnkl.html

Ruby: Color = %i[red green].freeze
来源：http://dali.andypj.xyz/Article/details/gtejbyrmhb.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jyoumei.cn/Article/details/gtxddnhjrj.html

[G16] 对象转数组 / 字典
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnppzhtyo.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.andypj.xyz/Article/details/gtmifbffxa.html

PHP:  get_object_vars($obj);
来源：http://dali.gaohongyu789.top/Article/details/gtmwemvboy.html

JS:   Object.entries(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gtmvcnofci.html

TS:   Object.entries(obj)
来源：http://dali.jianghu66.top/Article/details/gtbmphcyev.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhongyouzk.top/Article/details/gtuvhgamdi.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.shanyushiyangtech.top/Article/details/gtffjdkubg.html

Ruby: obj.instance_variables
来源：http://dali.hongshengwenyu.top/Article/details/gtnzsuoaae.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.chenlongwang.top/Article/details/gtnqljvrvq.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtlxhraqku.html

H. 异常与错误处理
来源：http://dali.pengpengdd.cyou/Article/details/gtkmszsczh.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtvmfexmil.html

[H01] try / catch 基础
来源：http://dali.shangyingyoupin.top/Article/details/gtnnwtiwue.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwenstykz.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.dianchejie.cn/Article/details/gtfelrtygc.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.cqqwz.cn/Article/details/gtrftsjvmv.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.sysykeji.top/Article/details/gtvulkihyk.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.aibaodan.cn/Article/details/gtzbnsqvgl.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.pycfn.com/Article/details/gtzbfzpevd.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.xuetiantiany.cn/Article/details/gtkrnhagij.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.meibo888.top/Article/details/gtqqstxgdh.html

[H02] finally / ensure 收尾
来源：http://dali.snrcjt.cn/Article/details/gteqjdxdat.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yongpay.top/Article/details/gtdmwryuka.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.sysykeji.top/Article/details/gtcapzwxax.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtdaxyhgln.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.aibaodan.cn/Article/details/gtfavoikbg.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.feifeiyinyue.top/Article/details/gturavjycz.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.fengsongda.top/Article/details/gtdqmgfyhf.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yangfankeji.com/Article/details/gtrokkloiu.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtqltldgqb.html

[H03] 主动抛出异常
来源：http://dali.shanyushiyangtech.top/Article/details/gtuvdkaiwj.html

Py:   raise ValueError("错误信息")
来源：http://dali.ivvv.top/Article/details/gtiwlrjopz.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.nanxuanxn.top/Article/details/gtcreftakc.html

JS:   throw new Error("错误信息");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoogbujeo.html

TS:   throw new Error("错误信息");
来源：http://dali.9152youxi.cn/Article/details/gtjfnmytle.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.havefunace.top/Article/details/gtcitvxemd.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhijiandao.cn/Article/details/gtbeguanbi.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.shuidangran.top/Article/details/gtaryxcqvn.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.shanyushiyangtech.top/Article/details/gttflncndn.html

[H04] 自定义异常类型
来源：http://dali.hammf.cn/Article/details/gtyoycdyoi.html

Py:   class MyError(Exception): pass
来源：http://dali.gzhubu.top/Article/details/gtmcixrvnd.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.daria6918.cn/Article/details/gtyfmatwqn.html

JS:   class MyError extends Error {}
来源：http://dali.meibo888.top/Article/details/gtmaknotfg.html

TS:   class MyError extends Error {}
来源：http://dali.cashguo.top/Article/details/gtgdvjaiio.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiwokwpzs.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.shuidangran.top/Article/details/gthdoqlaoj.html

Ruby: class MyError < StandardError; end
来源：http://dali.jianghu66.top/Article/details/gtcpgornxq.html

C#:   class MyException : Exception {}
来源：http://dali.xylfe.cn/Article/details/gtvwubwlkn.html

[H05] 捕获特定类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnosletmm.html

Py:   except ValueError as e:
来源：http://dali.gzhubu.top/Article/details/gtdltxvjos.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.hfpthk.cn/Article/details/gtuxkcgdma.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.birdmap.top/Article/details/gtuudtygft.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.hysaishi.cn/Article/details/gtienjtrle.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.nwbrower.top/Article/details/gtqdlytelo.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.ydzc1.top/Article/details/gteqkvpzjv.html

Ruby: rescue ArgumentError => e
来源：http://dali.shanyushiyangkeji.top/Article/details/gtveexnlrd.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hnxiangtu.top/Article/details/gtdqpyajwu.html

[H06] 可选值 / 空值安全访问
来源：http://dali.aibaodan.cn/Article/details/gttzwixyfn.html

Py:   value = d.get("k") or default
来源：http://dali.sysykeji.top/Article/details/gtmfgzrjwf.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.ivvv.top/Article/details/gtnezhzyaj.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jinghuilouyu.cn/Article/details/gtkzhaiubx.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zdqjudy.top/Article/details/gtcptfsbfu.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.chenjidiqi.icu/Article/details/gtwqxobbso.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.cqqwz.cn/Article/details/gtcpcrudmf.html

Ruby: d&.dig(:a, :b)
来源：http://dali.aizwys.cn/Article/details/gtcxwybcmb.html

C#:   obj?.A?.B ?? default
来源：http://dali.sxryk.cn/Article/details/gtfmxvlffr.html

[H07] 断言
来源：http://dali.hnqzz.top/Article/details/gthmcisoau.html

Py:   assert x > 0, "必须为正"
来源：http://dali.shanyushiyangtech.top/Article/details/gtmgtvrbti.html

PHP:  assert($x > 0);
来源：http://dali.daxiang520.top/Article/details/gtztafaqyw.html

JS:   console.assert(x > 0);
来源：http://dali.chenjidiqi.icu/Article/details/gtderxpyre.html

TS:   console.assert(x > 0);
来源：http://dali.sxryk.cn/Article/details/gtclbdskpc.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yuxming.cn/Article/details/gthavhdcgk.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.shangyingyoupin.top/Article/details/gtgtkxrzak.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yueranfly.top/Article/details/gtaclsxapv.html

C#:   Debug.Assert(x > 0);
来源：http://dali.bjfxy.top/Article/details/gtkpcgdqca.html

[H08] 获取错误信息与堆栈
来源：http://dali.sysykeji.top/Article/details/gtkcpvbwvj.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.daxiang520.top/Article/details/gtmdkowmzj.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yj20258888.top/Article/details/gtkteetoek.html

JS:   e.message;  e.stack
来源：http://dali.cdnleiting.top/Article/details/gtelvfnnsc.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yangfankeji.com/Article/details/gttmpzbpuq.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhixingplan.top/Article/details/gtogzzfylf.html

Go:   err.Error()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzzvtyice.html

Ruby: e.message;  e.backtrace
来源：http://dali.gzhubu.top/Article/details/gtclcvoihj.html

C#:   e.Message;  e.StackTrace
来源：http://dali.tianlin.xyz/Article/details/gtbwquvdsc.html

[H09] 带错误码的异常
来源：http://dali.daxiang520.top/Article/details/gtwfzgiove.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.feifeiyinyue.top/Article/details/gtvbqavccj.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.wangdashe.top/Article/details/gtaupribrr.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.mhx1999.top/Article/details/gtozgwknwf.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhoulong.xyz/Article/details/gtrujwyidh.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.quarkkingdee.top/Article/details/gtmywyttun.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.ppjwa.cn/Article/details/gtfrgcrpjg.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.gogol.net.cn/Article/details/gtqssnmyfo.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jinqigfzy.top/Article/details/gtgvuumfkp.html

[H10] 资源自动释放
来源：http://dali.jiagoushi.top/Article/details/gtkeflpmie.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.sxryk.cn/Article/details/gttivatsnx.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhiwuduotai.top/Article/details/gtgesjqmtc.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.svipenyu.cn/Article/details/gtvocznfbr.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.fengsongda.top/Article/details/gttqqmildp.html


<!-- 参考信息 -->