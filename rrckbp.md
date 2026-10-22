代发 wailian999

C#:   File.Exists("a.txt")
来源：http://dali.cheryme.top/Article/details/gtmafyraoq.html

[F06] 删除文件
来源：http://dali.jqgfzy.top/Article/details/gtgotgmcgi.html

Py:   os.remove("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtxrcuunuw.html

PHP:  unlink("a.txt");
来源：http://dali.bjfxy.top/Article/details/gtygwsmaql.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlyzseqdd.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtdwdrabxz.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jinqigufen.top/Article/details/gtugeelgqd.html

Go:   os.Remove("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtyfcichbm.html

Ruby: File.delete("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtceulkbti.html

C#:   File.Delete("a.txt");
来源：http://dali.yvedp.cn/Article/details/gtqpvvodpv.html

[F07] 创建目录（含多级）
来源：http://dali.sxryk.cn/Article/details/gtlzavjcjj.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yj20258888.top/Article/details/gthoflbnlj.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zycfv.cn/Article/details/gtuxbtssjo.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ivvv.top/Article/details/gtysliqaxe.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yj202588.top/Article/details/gtsyqclcwb.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jinghuilouyu.cn/Article/details/gtoigpvuah.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.feifeiyinyue.top/Article/details/gtyuaqrydq.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.9152youxi.cn/Article/details/gtugpfxdcr.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.andypj.xyz/Article/details/gtfdhjxpza.html

[F08] 遍历目录
来源：http://dali.cqqwz.cn/Article/details/gtphvlpfen.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.cheryme.top/Article/details/gtlvcyznqj.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoaujbful.html

JS:   fs.readdirSync("dir")
来源：http://dali.jqgfzy.top/Article/details/gtixnyqcbw.html

TS:   fs.readdirSync("dir")
来源：http://dali.hnqzz.top/Article/details/gtorzboemd.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.pycfn.com/Article/details/gtdwxhjgmd.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gtkadxwywz.html

Ruby: Dir.children("dir")
来源：http://dali.dashuyun.cn/Article/details/gtlzlonmzh.html

C#:   Directory.GetFiles("dir")
来源：http://dali.feifeiyinyue.top/Article/details/gtmgcbjhio.html

[F09] 获取文件大小
来源：http://dali.guannengcc.top/Article/details/gthzfwtgfq.html

Py:   os.path.getsize("a.txt")
来源：http://dali.smart0.xyz/Article/details/gtpqjkbujj.html

PHP:  filesize("a.txt");
来源：http://dali.cheryme.top/Article/details/gtissbwelw.html

JS:   fs.statSync("a.txt").size
来源：http://dali.feifeiyinyue.top/Article/details/gtpmblftkw.html

TS:   fs.statSync("a.txt").size
来源：http://dali.hnqzz.top/Article/details/gtclvoubnd.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.sxryk.cn/Article/details/gtceullize.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.guowangkeji.top/Article/details/gtygqyhzvk.html

Ruby: File.size("a.txt")
来源：http://dali.bjfxy.top/Article/details/gtjyzrplay.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.pycfn.com/Article/details/gtnnkusfpf.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.gzhubu.top/Article/details/gtjalasuxr.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.sweek.top/Article/details/gtgxhotbbi.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.iojbl.cn/Article/details/gtzxulnmfm.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtgmrdkdsz.html

TS:   path.extname("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtytomjird.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.quarkkingdee.top/Article/details/gtzowtsdjr.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.andypj.xyz/Article/details/gtsfoidnep.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.smart0.xyz/Article/details/gtcexoswxa.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yonumen.top/Article/details/gtojlfjlvi.html

[F11] 复制与移动文件
来源：http://dali.yuxming.cn/Article/details/gtctjxqamk.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hnqzz.top/Article/details/gtivgsqlgw.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jyoumei.cn/Article/details/gtonoegobt.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yvedp.cn/Article/details/gtniakoxaq.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.haohaochexian.top/Article/details/gtxlgapehe.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jyoumei.cn/Article/details/gtbtozadhn.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.xinyue.icu/Article/details/gtdrumxdcp.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yuxming.cn/Article/details/gttrvcksrv.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yongpay.top/Article/details/gtyyjljwsp.html

[F12] CSV 读写
来源：http://dali.cheryme.top/Article/details/gtouhzluta.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.andypj.xyz/Article/details/gteegqbsiq.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.pycfn.com/Article/details/gtzlxporzi.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.ywan-chungtsiang.top/Article/details/gtupxpjkwy.html

TS:   // 同上
来源：http://dali.c1oappe.top/Article/details/gtcovhrjsm.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.xziqi.cn/Article/details/gtynxihxgv.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.xuetiantiany.cn/Article/details/gtyqcuzwuy.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.sweek.top/Article/details/gtsnxtfxsg.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.tanke756.top/Article/details/gtyomgnpmb.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtzrcnrlnw.html

G. 面向对象
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgevajdxn.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtfosamuya.html

[G01] 定义类
来源：http://dali.vqdsnc.cn/Article/details/gtiugjngik.html

Py:   class User: pass
来源：http://dali.aibaodan.cn/Article/details/gtvsbtoqna.html

PHP:  class User {}
来源：http://dali.sweek.top/Article/details/gtwkspavpu.html

JS:   class User {}
来源：http://dali.xziqi.cn/Article/details/gtgysaicea.html

TS:   class User { name: string = ""; }
来源：http://dali.ehwqpu.com/Article/details/gtwqkqcgaz.html

Java: class User {}
来源：http://dali.wangshuangyany.cn/Article/details/gttavyacoa.html

Go:   type User struct { Name string }
来源：http://dali.zycfv.cn/Article/details/gtfqfjlsfv.html

Ruby: class User; end
来源：http://dali.jinqigfzy.top/Article/details/gtpscyabvr.html

C#:   class User {}
来源：http://dali.hysaishi.cn/Article/details/gtgyngobni.html

[G02] 构造函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtehnkkxbe.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.guowangkeji.top/Article/details/gtphznwhjg.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.shzxlz.cn/Article/details/gtdbcfpduh.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhongyouzk.top/Article/details/gtzeewjfnv.html

TS:   constructor(public name: string) {}
来源：http://dali.zhixingplan.top/Article/details/gtkmttbkye.html

Java: User(String name) { this.name = name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtlditwzqk.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.pengpengdd.cyou/Article/details/gtnvaxcwvh.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhixingplan.top/Article/details/gtdjrlpgvf.html

C#:   public User(string name) { Name = name; }
来源：http://dali.tianlin.xyz/Article/details/gtcordphrs.html

[G03] 实例属性
来源：http://dali.hongshengwenyu.top/Article/details/gtgujnuivz.html

Py:   self.name = "x"
来源：http://dali.ehwqpu.com/Article/details/gtapalgmru.html

PHP:  public string $name = "x";
来源：http://dali.jqgfzy.top/Article/details/gtwpbbcywn.html

JS:   this.name = "x";
来源：http://dali.9152youxi.cn/Article/details/gtpavezvkh.html

TS:   name: string = "x";
来源：http://dali.hysaishi.cn/Article/details/gtsomnvvaf.html

Java: private String name;
来源：http://dali.ehwqpu.com/Article/details/gteuowcxak.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.daria6918.cn/Article/details/gtfzyempbz.html

Ruby: @name = "x"
来源：http://dali.dashuyun.cn/Article/details/gtzfyaosdz.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.svipenyu.cn/Article/details/gtegwzzwnb.html

[G04] 定义方法
来源：http://dali.birdmap.top/Article/details/gteusfbgya.html

Py:   def greet(self): return self.name
来源：http://dali.tian-w.cn/Article/details/gtocrfslzv.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jqgufenzy.top/Article/details/gtqewnxeye.html

JS:   greet() { return this.name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtorchbjjn.html

TS:   greet(): string { return this.name; }
来源：http://dali.pycfn.com/Article/details/gtycmpdcsh.html

Java: String greet() { return name; }
来源：http://dali.aizwys.cn/Article/details/gtjotkjstl.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hongshengwenyu.top/Article/details/gtcropfjsd.html

Ruby: def greet; @name; end
来源：http://dali.svipenyu.cn/Article/details/gtvpdedvqb.html

C#:   public string Greet() => Name;
来源：http://dali.daxiang520.top/Article/details/gtvlirlwei.html

[G05] 继承
来源：http://dali.chenjidiqi.icu/Article/details/gtexqwsjpe.html

Py:   class Admin(User): pass
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwjlbcrlk.html

PHP:  class Admin extends User {}
来源：http://dali.xinyue.icu/Article/details/gtvawqistt.html

JS:   class Admin extends User {}
来源：http://dali.ivvv.top/Article/details/gtxrroruge.html

TS:   class Admin extends User {}
来源：http://dali.jqgufenzy.top/Article/details/gtqdzwtzte.html

Java: class Admin extends User {}
来源：http://dali.hammf.cn/Article/details/gtghjkgawy.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.xylfe.cn/Article/details/gtheiezpgs.html

Ruby: class Admin < User; end
来源：http://dali.c1oappe.top/Article/details/gtbtjlrmrp.html

C#:   class Admin : User {}
来源：http://dali.chenlongwang.top/Article/details/gtqtyczjaf.html

[G06] 重写方法
来源：http://dali.gaohongyu789.top/Article/details/gtsfacnuyn.html

Py:   def greet(self): return "admin"
来源：http://dali.yanxiufei.cn/Article/details/gtrhpdlpvt.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.shuidangran.top/Article/details/gtepszecix.html

JS:   greet() { return "admin"; }
来源：http://dali.yonumen.top/Article/details/gtdrgzgmwy.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yueranfly.top/Article/details/gtnckdbcyb.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.haohaochexian.top/Article/details/gtwkdgrvth.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.c1oappe.top/Article/details/gtkfmkpgpa.html

Ruby: def greet; "admin"; end
来源：http://dali.sweek.top/Article/details/gtfadjkokk.html

C#:   public override string Greet() => "admin";
来源：http://dali.yongpay.top/Article/details/gteaydhvhp.html

[G07] 调用父类方法
来源：http://dali.jyoumei.cn/Article/details/gtqysqzmry.html

Py:   super().greet()
来源：http://dali.gotoacloud.top/Article/details/gtliselxsv.html

PHP:  parent::greet();
来源：http://dali.feifeiyinyue.top/Article/details/gtobemkwqa.html

JS:   super.greet();
来源：http://dali.hongshengwenyu.top/Article/details/gtcjqqfcqn.html

TS:   super.greet();
来源：http://dali.havefunace.top/Article/details/gtmqptoguo.html

Java: super.greet();
来源：http://dali.guannengcc.top/Article/details/gtnkerhzcg.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yj20258888.top/Article/details/gtzogpihlp.html

Ruby: super
来源：http://dali.aibaodan.cn/Article/details/gtjsusgggi.html

C#:   base.Greet();
来源：http://dali.yj202588.top/Article/details/gtcmxcxavo.html

[G08] 静态方法与属性
来源：http://dali.daxiang520.top/Article/details/gtavonajeo.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yuanzhike.top/Article/details/gtqwxzbiaz.html

PHP:  public static function f() {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbsjvtwzr.html

JS:   static f() {}
来源：http://dali.meibo888.top/Article/details/gtwamlawol.html

TS:   static f(): void {}
来源：http://dali.cheryme.top/Article/details/gtbhzvycdi.html

Java: static void f() {}
来源：http://dali.xuanzx.com/Article/details/gtsqytfkhv.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hongshengwenyu.top/Article/details/gtirdvryvo.html

Ruby: def self.f; end
来源：http://dali.redwolf501.top/Article/details/gtwqereytu.html

C#:   public static void F() {}
来源：http://dali.guowangkeji.top/Article/details/gtpyasjzik.html

[G09] 接口 / 抽象类
来源：http://dali.9152youxi.cn/Article/details/gttztqopyf.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.xylfe.cn/Article/details/gtxbyfwiyj.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.iojbl.cn/Article/details/gtzrvsfiud.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yj202588.top/Article/details/gthiigqqyt.html

TS:   interface Shape { area(): number; }
来源：http://dali.chenlongwang.top/Article/details/gtaalxnfll.html

Java: interface Shape { double area(); }
来源：http://dali.daria6918.cn/Article/details/gthzoyrpvc.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhiwuduotai.top/Article/details/gttggonyup.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.havefunace.top/Article/details/gtkmunkwey.html

C#:   interface IShape { double Area(); }
来源：http://dali.yvedp.cn/Article/details/gtrxknyxbq.html

[G10] 访问控制
来源：http://dali.ybcxt.top/Article/details/gtcnesbsps.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.9152youxi.cn/Article/details/gtrdiucgow.html

PHP:  public / protected / private
来源：http://dali.gzhubu.top/Article/details/gtazcukepv.html

JS:   #private 字段；其余公开
来源：http://dali.guannengcc.top/Article/details/gtruqibrgm.html

TS:   public / protected / private
来源：http://dali.nwbrower.top/Article/details/gtuhhkjtdk.html

Java: public / protected / private / 默认包级
来源：http://dali.xylfe.cn/Article/details/gtgdlwyozb.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.andypj.xyz/Article/details/gtlqsskiuw.html

Ruby: public / protected / private
来源：http://dali.andypj.xyz/Article/details/gteveaufce.html

C#:   public / protected / private / internal
来源：http://dali.hongshengwenyu.top/Article/details/gtoxqaqeyg.html

[G11] getter / setter
来源：http://dali.xylfe.cn/Article/details/gtyyyuqpnw.html

Py:   @property 与 @x.setter
来源：http://dali.fzhhl.top/Article/details/gtofqkwiyw.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.chenzaomai.com/Article/details/gtwofrqnzy.html

JS:   get name() { return this._name; }
来源：http://dali.jiagoushi.top/Article/details/gtnrcsirny.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtqqppjpvb.html

Java: public String getName() { return name; }
来源：http://dali.hfpthk.cn/Article/details/gtvqwdoluu.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.pycfn.com/Article/details/gtvzigxdtz.html

Ruby: attr_accessor :name
来源：http://dali.fengsongda.top/Article/details/gtsrrsdgdg.html

C#:   public string Name { get; set; }
来源：http://dali.yuanzhike.top/Article/details/gtlojweeof.html

[G12] 对象转字符串
来源：http://dali.cheryme.top/Article/details/gtauhbfrtd.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gtodbjhzjq.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.kuanghao11.cn/Article/details/gtnvmejokp.html

JS:   toString() { return this.name; }
来源：http://dali.xylfe.cn/Article/details/gtjopojoov.html

TS:   toString(): string { return this.name; }
来源：http://dali.ehwqpu.com/Article/details/gtjoctqelg.html

Java: @Override public String toString() { return name; }
来源：http://dali.hysaishi.cn/Article/details/gtxchypxpq.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.shanyushiyangtech.top/Article/details/gtdfrdkjag.html

Ruby: def to_s; @name; end
来源：http://dali.zhixingplan.top/Article/details/gtkctfbptj.html

C#:   public override string ToString() => Name;
来源：http://dali.tian-w.cn/Article/details/gtqykpsmzi.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gtqiuwfozy.html

Py:   isinstance(u, User)
来源：http://dali.shuidangran.top/Article/details/gtxvkreoot.html

PHP:  $u instanceof User
来源：http://dali.cucudq.cn/Article/details/gtqmqolbpi.html

JS:   u instanceof User
来源：http://dali.pengpengdd.cyou/Article/details/gtixtteerv.html

TS:   u instanceof User
来源：http://dali.kuanghao11.cn/Article/details/gtntfdooyf.html

Java: u instanceof User
来源：http://dali.tianlin.xyz/Article/details/gthvlwxhih.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jiagoushi.top/Article/details/gthdcalfsz.html

Ruby: u.is_a?(User)
来源：http://dali.quarkkingdee.top/Article/details/gtyxjqmfpj.html

C#:   u is User
来源：http://dali.fzhhl.top/Article/details/gttkizpkpp.html

[G14] 数据类 / record
来源：http://dali.fzhhl.top/Article/details/gtycsmgtag.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.tanke756.top/Article/details/gtvdklcywg.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.aibaodan.cn/Article/details/gtarvozzgf.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.gzhubu.top/Article/details/gtxqrjbggj.html

TS:   type User = { name: string; age: number };
来源：http://dali.hysaishi.cn/Article/details/gtkdsbsttz.html

Java: record User(String name, int age) {}
来源：http://dali.wangdashe.top/Article/details/gtsdosozhf.html

Go:   type User struct { Name string; Age int }
来源：http://dali.gotoacloud.top/Article/details/gthbwzjeuy.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.guannengcc.top/Article/details/gtcxiwdlwo.html

C#:   record User(string Name, int Age);
来源：http://dali.ybcxt.top/Article/details/gtrvchhxgl.html

[G15] 枚举
来源：http://dali.chenzaomai.com/Article/details/gtjaojxbdy.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.cashguo.top/Article/details/gtiyvqxayu.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.hammf.cn/Article/details/gtwbthjstk.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.ehwqpu.com/Article/details/gtfcomkrhc.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.chenzaomai.com/Article/details/gtzohjwami.html

Java: enum Color { RED, GREEN }
来源：http://dali.daria6918.cn/Article/details/gtrkwszncd.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.mhx1999.top/Article/details/gtdjiykrxu.html

Ruby: Color = %i[red green].freeze
来源：http://dali.iojbl.cn/Article/details/gtucdhtzoy.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.daxiang520.top/Article/details/gtpgwyuqvu.html

[G16] 对象转数组 / 字典
来源：http://dali.jqgfzy.top/Article/details/gtamcblwhs.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yj20258.top/Article/details/gtbyctgnac.html

PHP:  get_object_vars($obj);
来源：http://dali.zdqjudy.top/Article/details/gtxdkkbzdp.html

JS:   Object.entries(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gtkwadwgvr.html

TS:   Object.entries(obj)
来源：http://dali.quarkkingdee.top/Article/details/gtbkhhulrw.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhengqikj.top/Article/details/gtrnbczsqc.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqoguzxti.html

Ruby: obj.instance_variables
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrafxctah.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqikvxtzb.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtzttmfyrr.html

H. 异常与错误处理
来源：http://dali.0kj1m.cn/Article/details/gtpwhekjil.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtensptarm.html

[H01] try / catch 基础
来源：http://dali.zhongyouzk.top/Article/details/gtobanbezi.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.dianchejie.cn/Article/details/gtovptepbm.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yanxiufei.cn/Article/details/gtivqhtxbk.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.c1oappe.top/Article/details/gttnoanspr.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxmeeqcyo.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.tian-w.cn/Article/details/gtfsvssrno.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.sweek.top/Article/details/gtvltgjdgw.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.ehwqpu.com/Article/details/gtvlmanwza.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.9152youxi.cn/Article/details/gthggmlzec.html

[H02] finally / ensure 收尾
来源：http://dali.sysykeji.top/Article/details/gtufyxlsmo.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.pengpengdd.cyou/Article/details/gtzvncerrp.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yuanzhike.top/Article/details/gtgdfsjxrm.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.mhx1999.top/Article/details/gtbrhfcqrm.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdbbifqlj.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.wangdashe.top/Article/details/gttzkamogx.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfdtajrmi.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jinqigfzy.top/Article/details/gtzkorjfxy.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.nwbrower.top/Article/details/gtvzoewnxt.html

[H03] 主动抛出异常
来源：http://dali.hnqzz.top/Article/details/gtsfiqclne.html

Py:   raise ValueError("错误信息")
来源：http://dali.hfpthk.cn/Article/details/gtdetqhesh.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.mhx1999.top/Article/details/gtornumfsd.html

JS:   throw new Error("错误信息");
来源：http://dali.cheryme.top/Article/details/gtoujpglpz.html

TS:   throw new Error("错误信息");
来源：http://dali.c1oappe.top/Article/details/gtcbdmfjio.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xylfe.cn/Article/details/gtmrkebghz.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.ppjwa.cn/Article/details/gtaifivqty.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.wangdashe.top/Article/details/gtziwehpin.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.0kj1m.cn/Article/details/gtribowjvr.html

[H04] 自定义异常类型
来源：http://dali.tian-w.cn/Article/details/gtqllcqdux.html

Py:   class MyError(Exception): pass
来源：http://dali.redwolf501.top/Article/details/gtvqmjwpkj.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yj20258.top/Article/details/gtpyfvgnnk.html

JS:   class MyError extends Error {}
来源：http://dali.sxryk.cn/Article/details/gtsrgyyynn.html

TS:   class MyError extends Error {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwuydwosq.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yueranfly.top/Article/details/gtpobchmih.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.tianlin.xyz/Article/details/gtizntpnya.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhoulong.xyz/Article/details/gtduedyvpa.html

C#:   class MyException : Exception {}
来源：http://dali.dianchejie.cn/Article/details/gtqrauhkqs.html

[H05] 捕获特定类型
来源：http://dali.xylfe.cn/Article/details/gtpagnpkdx.html

Py:   except ValueError as e:
来源：http://dali.ppjwa.cn/Article/details/gtierfaxlt.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zycfv.cn/Article/details/gtzdwdigpc.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yj20258.top/Article/details/gtuhgduyfl.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.xylfe.cn/Article/details/gtaafzijrc.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.chenzaomai.com/Article/details/gtulusrgij.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhiwuduotai.top/Article/details/gtyrggrjob.html

Ruby: rescue ArgumentError => e
来源：http://dali.tanke756.top/Article/details/gtebhafzkk.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.sxryk.cn/Article/details/gterkekdtc.html

[H06] 可选值 / 空值安全访问
来源：http://dali.havefunace.top/Article/details/gtvasdfmbf.html

Py:   value = d.get("k") or default
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvtjmwjmo.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.gogol.net.cn/Article/details/gtfpauwjjn.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.dianchejie.cn/Article/details/gtbayqekaf.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.haohaochexian.top/Article/details/gtwibguaia.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtntlsxsxe.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.dashuyun.cn/Article/details/gtcdbgxoku.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hywenlv.cn/Article/details/gtsogreorr.html

C#:   obj?.A?.B ?? default
来源：http://dali.guannengcc.top/Article/details/gttbszhppr.html

[H07] 断言
来源：http://dali.zhixingplan.top/Article/details/gtrmvfjyym.html

Py:   assert x > 0, "必须为正"
来源：http://dali.sweek.top/Article/details/gtpunxhwar.html

PHP:  assert($x > 0);
来源：http://dali.kuanghao11.cn/Article/details/gtulqafcxx.html

JS:   console.assert(x > 0);
来源：http://dali.chenzaomai.com/Article/details/gtpjgeijmk.html

TS:   console.assert(x > 0);
来源：http://dali.jqgufenzy.top/Article/details/gtyibvwkzh.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jyoumei.cn/Article/details/gtimtyuokz.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.svipenyu.cn/Article/details/gtaadvfaer.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhaomingkeji.xyz/Article/details/gttpstgcpr.html

C#:   Debug.Assert(x > 0);
来源：http://dali.redwolf501.top/Article/details/gtxpizoxsi.html

[H08] 获取错误信息与堆栈
来源：http://dali.bjfxy.top/Article/details/gtwzwdntsq.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.sysykeji.top/Article/details/gtmzycndhg.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hnxiangtu.top/Article/details/gtfxgmlvcg.html

JS:   e.message;  e.stack
来源：http://dali.tian-w.cn/Article/details/gtxnokvtto.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.aibaodan.cn/Article/details/gtjyhzcqcf.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.c1oappe.top/Article/details/gtsplchvox.html

Go:   err.Error()
来源：http://dali.gzhubu.top/Article/details/gtewsgpbeh.html

Ruby: e.message;  e.backtrace
来源：http://dali.shzxlz.cn/Article/details/gthcazgsxe.html

C#:   e.Message;  e.StackTrace
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiyrhveoi.html

[H09] 带错误码的异常
来源：http://dali.sysykeji.top/Article/details/gtdtovnhcx.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yanxiufei.cn/Article/details/gtleqndsqt.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.sufxvd.cn/Article/details/gtkijnjhpv.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.daria6918.cn/Article/details/gtezcbjoet.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.hongshengwenyu.top/Article/details/gthlgbytrv.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.gzhubu.top/Article/details/gtjbvestjh.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.daxiang520.top/Article/details/gtzgguljto.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.dashuyun.cn/Article/details/gtksbzpurx.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.mhx1999.top/Article/details/gthhgcgmka.html

[H10] 资源自动释放
来源：http://dali.zhixingplan.top/Article/details/gthbpxhhqm.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.smart0.xyz/Article/details/gtbvfsanbe.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jlsjyb.cn/Article/details/gtguqsuhfk.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yuanzhike.top/Article/details/gthybjnltb.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yuanzhike.top/Article/details/gtaompdptf.html


<!-- 参考信息 -->