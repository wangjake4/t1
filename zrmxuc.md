代发 wailian999

JS:   fs.unlinkSync("a.txt")
来源：http://dali.nwbrower.top/Article/details/gt2exzsfyvn.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gt2ahvomjaj.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zdqjudy.top/Article/details/gt2cgecajrf.html

Go:   os.Remove("a.txt")
来源：http://dali.xuanzx.com/Article/details/gt2ukkwmbbn.html

Ruby: File.delete("a.txt")
来源：http://dali.sxryk.cn/Article/details/gt2vnjyftdf.html

C#:   File.Delete("a.txt");
来源：http://dali.zhixingplan.top/Article/details/gt2webjnetx.html

[F07] 创建目录（含多级）
来源：http://dali.hfpthk.cn/Article/details/gt2pksshapy.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jinqigfzy.top/Article/details/gt2oecppmqp.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jqgfzy.top/Article/details/gt2gpazmihr.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhoulong.xyz/Article/details/gt2igkckbsr.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinqigufen.top/Article/details/gt2ycjcjekp.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.daria6918.cn/Article/details/gt2dzvixuku.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.birdmap.top/Article/details/gt2gnwkggkg.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zhswsolz.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.shuidangran.top/Article/details/gt2hovqmbdt.html

[F08] 遍历目录
来源：http://dali.quarkkingdee.top/Article/details/gt2mlqfbofd.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.nanxinkj.top/Article/details/gt2mqelcyhu.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.smart0.xyz/Article/details/gt2ovemcgbf.html

JS:   fs.readdirSync("dir")
来源：http://dali.hnqzz.top/Article/details/gt2haizxvkr.html

TS:   fs.readdirSync("dir")
来源：http://dali.zdqjudy.top/Article/details/gt2vsljlvze.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.meibo888.top/Article/details/gt2ftbjrlaq.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.tanke756.top/Article/details/gt2whrgipxj.html

Ruby: Dir.children("dir")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ghvyrnbv.html

C#:   Directory.GetFiles("dir")
来源：http://dali.tian-w.cn/Article/details/gt2nchvuqec.html

[F09] 获取文件大小
来源：http://dali.zhiwuduotai.top/Article/details/gt2owyvxjgs.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yj20258.top/Article/details/gt2zmsdtkmg.html

PHP:  filesize("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gt2osnzlpad.html

JS:   fs.statSync("a.txt").size
来源：http://dali.gzhubu.top/Article/details/gt2mvnfvimo.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jianghu66.top/Article/details/gt2drssypqf.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.andypj.xyz/Article/details/gt2ogbecnig.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.ppjwa.cn/Article/details/gt2loyhhstx.html

Ruby: File.size("a.txt")
来源：http://dali.meibo888.top/Article/details/gt2eflveqay.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.hfpthk.cn/Article/details/gt2hgbuolfh.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.sufxvd.cn/Article/details/gt2xzbdsskx.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yongpay.top/Article/details/gt2smagjvuf.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.andypj.xyz/Article/details/gt2iqzclwai.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jiagoushi.top/Article/details/gt2qlqsynyr.html

TS:   path.extname("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gt2lwhyfinr.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.0kj1m.cn/Article/details/gt2tmkqteno.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gt2dcsokerf.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.xuanzx.com/Article/details/gt2xwicnafw.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhixingplan.top/Article/details/gt2tsraprta.html

[F11] 复制与移动文件
来源：http://dali.hammf.cn/Article/details/gt2paktdmyk.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.xuanzx.com/Article/details/gt2vthvmfan.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yonumen.top/Article/details/gt2kblyumuk.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2evugdmrm.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2rrpfdvoj.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yueranfly.top/Article/details/gt2uqrzzedd.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bypfdwcw.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bdclkjpw.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.aibaodan.cn/Article/details/gt2jpxkmvka.html

[F12] CSV 读写
来源：http://dali.jqgfzy.top/Article/details/gt2hocqxuyd.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.xinyue.icu/Article/details/gt2yjrxoaqh.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.sysykeji.top/Article/details/gt2mxxgdsno.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.aibaodan.cn/Article/details/gt2znnwmblt.html

TS:   // 同上
来源：http://dali.dashuyun.cn/Article/details/gt2fwgwvqet.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.guannengcc.top/Article/details/gt2ibxmxrin.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.sweek.top/Article/details/gt2rnxbbfsx.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.cashguo.top/Article/details/gt2rlnfrfpy.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.dianchejie.cn/Article/details/gt2gcecjunx.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2ywpgkjae.html

G. 面向对象
来源：http://dali.yangfankeji.com/Article/details/gt2oskpfwyk.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2gxmlzkyl.html

[G01] 定义类
来源：http://dali.yongpay.top/Article/details/gt2pnlotnzt.html

Py:   class User: pass
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qrqkkcyt.html

PHP:  class User {}
来源：http://dali.guowangkeji.top/Article/details/gt2nmhydjdk.html

JS:   class User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2godbuhmn.html

TS:   class User { name: string = ""; }
来源：http://dali.gaohongyu789.top/Article/details/gt2ngmjrbwr.html

Java: class User {}
来源：http://dali.tian-w.cn/Article/details/gt2netoieuv.html

Go:   type User struct { Name string }
来源：http://dali.jinqigufen.top/Article/details/gt2kmquxnoj.html

Ruby: class User; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2abxebgmu.html

C#:   class User {}
来源：http://dali.yj20258.top/Article/details/gt2lpshqvyi.html

[G02] 构造函数
来源：http://dali.jqgfzy.top/Article/details/gt2rmwuvuho.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.cqqwz.cn/Article/details/gt2xahzwvjo.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2avdhbjns.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ydzc1.top/Article/details/gt2cjimpllx.html

TS:   constructor(public name: string) {}
来源：http://dali.daria6918.cn/Article/details/gt2srrudhmn.html

Java: User(String name) { this.name = name; }
来源：http://dali.wangdashe.top/Article/details/gt2rwkvuqkz.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wpibeibv.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.sysykeji.top/Article/details/gt2efuhcgzx.html

C#:   public User(string name) { Name = name; }
来源：http://dali.cashguo.top/Article/details/gt2dcwuwbby.html

[G03] 实例属性
来源：http://dali.yj20258.top/Article/details/gt2cqfutsll.html

Py:   self.name = "x"
来源：http://dali.birdmap.top/Article/details/gt2zdxkzhji.html

PHP:  public string $name = "x";
来源：http://dali.shzxlz.cn/Article/details/gt2wobsfjpr.html

JS:   this.name = "x";
来源：http://dali.daxiang520.top/Article/details/gt2acearerr.html

TS:   name: string = "x";
来源：http://dali.cashguo.top/Article/details/gt2nsovipop.html

Java: private String name;
来源：http://dali.ehwqpu.com/Article/details/gt2ygcoazpj.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhengqikj.top/Article/details/gt2xehtjasi.html

Ruby: @name = "x"
来源：http://dali.kuanghao11.cn/Article/details/gt2wtkzlidz.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xjxihlqz.html

[G04] 定义方法
来源：http://dali.snrcjt.cn/Article/details/gt2ymgorxad.html

Py:   def greet(self): return self.name
来源：http://dali.guannengcc.top/Article/details/gt2cbqwquyx.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qgfpgynm.html

JS:   greet() { return this.name; }
来源：http://dali.pycfn.com/Article/details/gt2jmpszhut.html

TS:   greet(): string { return this.name; }
来源：http://dali.sweek.top/Article/details/gt2vvbmioce.html

Java: String greet() { return name; }
来源：http://dali.jianghu66.top/Article/details/gt2yijokyrp.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.nanxuanxn.top/Article/details/gt2fvbgcvac.html

Ruby: def greet; @name; end
来源：http://dali.xuanzx.com/Article/details/gt2yotwrwky.html

C#:   public string Greet() => Name;
来源：http://dali.meibo888.top/Article/details/gt2iudgrlbj.html

[G05] 继承
来源：http://dali.tanke756.top/Article/details/gt2eelibgvk.html

Py:   class Admin(User): pass
来源：http://dali.xziqi.cn/Article/details/gt2dgokhvmu.html

PHP:  class Admin extends User {}
来源：http://dali.jqgufenzy.top/Article/details/gt2isdahfyl.html

JS:   class Admin extends User {}
来源：http://dali.ppjwa.cn/Article/details/gt2orqnahxg.html

TS:   class Admin extends User {}
来源：http://dali.gotoacloud.top/Article/details/gt2xboclvpn.html

Java: class Admin extends User {}
来源：http://dali.chenlongwang.top/Article/details/gt2ojnniwhl.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.gotoacloud.top/Article/details/gt2swcvjkxs.html

Ruby: class Admin < User; end
来源：http://dali.aibaodan.cn/Article/details/gt2gbncwaog.html

C#:   class Admin : User {}
来源：http://dali.zdqjudy.top/Article/details/gt2pzhgzsui.html

[G06] 重写方法
来源：http://dali.birdmap.top/Article/details/gt2zptwzwkg.html

Py:   def greet(self): return "admin"
来源：http://dali.cqqwz.cn/Article/details/gt2qhxptyut.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.ivvv.top/Article/details/gt2irtpbyqr.html

JS:   greet() { return "admin"; }
来源：http://dali.aibaodan.cn/Article/details/gt2zrzjjfue.html

TS:   greet(): string { return "admin"; }
来源：http://dali.chenzaomai.com/Article/details/gt2jjsoquhx.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yj20258888.top/Article/details/gt2uxhwaiyc.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hysaishi.cn/Article/details/gt2xiitgsap.html

Ruby: def greet; "admin"; end
来源：http://dali.gaohongyu789.top/Article/details/gt2ewuqkhmu.html

C#:   public override string Greet() => "admin";
来源：http://dali.yvedp.cn/Article/details/gt2eyzmwpji.html

[G07] 调用父类方法
来源：http://dali.nwbrower.top/Article/details/gt2mscxagym.html

Py:   super().greet()
来源：http://dali.hfpthk.cn/Article/details/gt2lpwpkqht.html

PHP:  parent::greet();
来源：http://dali.smart0.xyz/Article/details/gt2ikxhrfom.html

JS:   super.greet();
来源：http://dali.sweek.top/Article/details/gt2bcajdlvc.html

TS:   super.greet();
来源：http://dali.tianlin.xyz/Article/details/gt2iadsaivy.html

Java: super.greet();
来源：http://dali.sysykeji.top/Article/details/gt2vjkwahpz.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.shangyingyoupin.top/Article/details/gt2cgjzkxbl.html

Ruby: super
来源：http://dali.yonumen.top/Article/details/gt2dozrdpni.html

C#:   base.Greet();
来源：http://dali.tian-w.cn/Article/details/gt2ignzxgzd.html

[G08] 静态方法与属性
来源：http://dali.ppjwa.cn/Article/details/gt2zbhtporf.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jianghu66.top/Article/details/gt2oxablmgk.html

PHP:  public static function f() {}
来源：http://dali.gaohongyu789.top/Article/details/gt2uuzohehe.html

JS:   static f() {}
来源：http://dali.sxryk.cn/Article/details/gt2vhihcjya.html

TS:   static f(): void {}
来源：http://dali.yueranfly.top/Article/details/gt2pppqbasv.html

Java: static void f() {}
来源：http://dali.zhengqikj.top/Article/details/gt2ygerutrl.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.ehwqpu.com/Article/details/gt2ighjssvk.html

Ruby: def self.f; end
来源：http://dali.zhiwuduotai.top/Article/details/gt2gmvjtjkr.html

C#:   public static void F() {}
来源：http://dali.ivvv.top/Article/details/gt2tsrjjglr.html

[G09] 接口 / 抽象类
来源：http://dali.svipenyu.cn/Article/details/gt2uboqmegr.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.birdmap.top/Article/details/gt2phtjkegf.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2onptataz.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.cdnleiting.top/Article/details/gt2mnbhsipa.html

TS:   interface Shape { area(): number; }
来源：http://dali.jqgufenzy.top/Article/details/gt2munfwbng.html

Java: interface Shape { double area(); }
来源：http://dali.cqqwz.cn/Article/details/gt2ggqcehsb.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.xinyue.icu/Article/details/gt2gjdrqwku.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.sysykeji.top/Article/details/gt2adildnhj.html

C#:   interface IShape { double Area(); }
来源：http://dali.cqqwz.cn/Article/details/gt2byodtkoo.html

[G10] 访问控制
来源：http://dali.cheryme.top/Article/details/gt2cjkzcslw.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.cucudq.cn/Article/details/gt2ankimtbb.html

PHP:  public / protected / private
来源：http://dali.xinyue.icu/Article/details/gt2olrjykcq.html

JS:   #private 字段；其余公开
来源：http://dali.9152youxi.cn/Article/details/gt2rwewdbyz.html

TS:   public / protected / private
来源：http://dali.shzxlz.cn/Article/details/gt2kvugbfex.html

Java: public / protected / private / 默认包级
来源：http://dali.cdnleiting.top/Article/details/gt2hbehbeij.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.smart0.xyz/Article/details/gt2qhjxgdzr.html

Ruby: public / protected / private
来源：http://dali.zhengqikj.top/Article/details/gt2qrqftoay.html

C#:   public / protected / private / internal
来源：http://dali.jinqigufen.top/Article/details/gt2nluadbyl.html

[G11] getter / setter
来源：http://dali.sysykeji.top/Article/details/gt2zjskkmqj.html

Py:   @property 与 @x.setter
来源：http://dali.zhoulong.xyz/Article/details/gt2yphsrrin.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.nanxinkj.top/Article/details/gt2pdyqavca.html

JS:   get name() { return this._name; }
来源：http://dali.jqgufenzy.top/Article/details/gt2tpulfepp.html

TS:   get name(): string { return this._name; }
来源：http://dali.hfpthk.cn/Article/details/gt2groejkia.html

Java: public String getName() { return name; }
来源：http://dali.tanke756.top/Article/details/gt2iiepwahe.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.nanxinkj.top/Article/details/gt2iroadgox.html

Ruby: attr_accessor :name
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nnqykudv.html

C#:   public string Name { get; set; }
来源：http://dali.guowangkeji.top/Article/details/gt2ulqdhrwu.html

[G12] 对象转字符串
来源：http://dali.gaohongyu789.top/Article/details/gt2kapwkhbv.html

Py:   def __str__(self): return self.name
来源：http://dali.birdmap.top/Article/details/gt2ksjpzfma.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.gotoacloud.top/Article/details/gt2ajpcslop.html

JS:   toString() { return this.name; }
来源：http://dali.hywenlv.cn/Article/details/gt2yqubwhmm.html

TS:   toString(): string { return this.name; }
来源：http://dali.tanke756.top/Article/details/gt2bggfoycj.html

Java: @Override public String toString() { return name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2svcodxwl.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.daxiang520.top/Article/details/gt2azakrtne.html

Ruby: def to_s; @name; end
来源：http://dali.jinqigufen.top/Article/details/gt2pcdgpfjx.html

C#:   public override string ToString() => Name;
来源：http://dali.xylfe.cn/Article/details/gt2yaxpdwdn.html

[G13] 判断对象类型
来源：http://dali.iojbl.cn/Article/details/gt2bocxmwyq.html

Py:   isinstance(u, User)
来源：http://dali.redwolf501.top/Article/details/gt2azykujub.html

PHP:  $u instanceof User
来源：http://dali.xuanzx.com/Article/details/gt2cfydvzey.html

JS:   u instanceof User
来源：http://dali.9152youxi.cn/Article/details/gt2qxnovwxf.html

TS:   u instanceof User
来源：http://dali.smart0.xyz/Article/details/gt2dpjgvraq.html

Java: u instanceof User
来源：http://dali.yongpay.top/Article/details/gt2vlkpugsh.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.birdmap.top/Article/details/gt2fnlqedhw.html

Ruby: u.is_a?(User)
来源：http://dali.tianlin.xyz/Article/details/gt2ddootidh.html

C#:   u is User
来源：http://dali.tian-w.cn/Article/details/gt2hapfoibj.html

[G14] 数据类 / record
来源：http://dali.xinyue.icu/Article/details/gt2qufadipo.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.0kj1m.cn/Article/details/gt2eclkhssd.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yonumen.top/Article/details/gt2hnhguirr.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.feifeiyinyue.top/Article/details/gt2vyoephcn.html

TS:   type User = { name: string; age: number };
来源：http://dali.andypj.xyz/Article/details/gt2oammaqwu.html

Java: record User(String name, int age) {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2avlbzivk.html

Go:   type User struct { Name string; Age int }
来源：http://dali.xuetiantiany.cn/Article/details/gt2zdimqnlq.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.xuanzx.com/Article/details/gt2svsdqcxt.html

C#:   record User(string Name, int Age);
来源：http://dali.pycfn.com/Article/details/gt2axrqtcoz.html

[G15] 枚举
来源：http://dali.wangshuangyany.cn/Article/details/gt2brsiddzr.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2towyzpms.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.xylfe.cn/Article/details/gt2ufdjgbug.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jyoumei.cn/Article/details/gt2dfqtlcke.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yuxming.cn/Article/details/gt2wsxnoayu.html

Java: enum Color { RED, GREEN }
来源：http://dali.jyoumei.cn/Article/details/gt2wjmpdqhg.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.ybcxt.top/Article/details/gt2qpqoqvjf.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jyoumei.cn/Article/details/gt2nianhlho.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ivvv.top/Article/details/gt2rlebyrty.html

[G16] 对象转数组 / 字典
来源：http://dali.shzxlz.cn/Article/details/gt2wsqcsyhc.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.hysaishi.cn/Article/details/gt2rqvydevv.html

PHP:  get_object_vars($obj);
来源：http://dali.yvedp.cn/Article/details/gt2rtnggghk.html

JS:   Object.entries(obj)
来源：http://dali.hfpthk.cn/Article/details/gt2bgakhwpf.html

TS:   Object.entries(obj)
来源：http://dali.haohaochexian.top/Article/details/gt2mxgfiipt.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jianghu66.top/Article/details/gt2cvbopizc.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.kuanghao11.cn/Article/details/gt2pjaoktte.html

Ruby: obj.instance_variables
来源：http://dali.nanxuanxn.top/Article/details/gt2xixxcqzg.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhixingplan.top/Article/details/gt2bxybxcwt.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2oytlujmz.html

H. 异常与错误处理
来源：http://dali.cucudq.cn/Article/details/gt2ozznyuxv.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2engwawbx.html

[H01] try / catch 基础
来源：http://dali.jiagoushi.top/Article/details/gt2zwolwgcq.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.wangdashe.top/Article/details/gt2fjwtxmyd.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.aibaodan.cn/Article/details/gt2sutpttdf.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2wvqeoqgb.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.fzhhl.top/Article/details/gt2bwzeldnk.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zhjhuinf.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.gogol.net.cn/Article/details/gt2gqsumzvk.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gt2wkwkuwkt.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.aibaodan.cn/Article/details/gt2aawrwzpe.html

[H02] finally / ensure 收尾
来源：http://dali.dashuyun.cn/Article/details/gt2hztvwakd.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.meibo888.top/Article/details/gt2iefvmkqq.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.ppjwa.cn/Article/details/gt2axlrhnpm.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yanxiufei.cn/Article/details/gt2emjkgjwe.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.cqqwz.cn/Article/details/gt2jldnclsi.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jqgfzy.top/Article/details/gt2tmvsjnyw.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hnxiangtu.top/Article/details/gt2cqjycgwk.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.fzhhl.top/Article/details/gt2lofhzphu.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.havefunace.top/Article/details/gt2sqxrglft.html

[H03] 主动抛出异常
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cdupkgsm.html

Py:   raise ValueError("错误信息")
来源：http://dali.jianghu66.top/Article/details/gt2vywxkivf.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yuanzhike.top/Article/details/gt2dmhwzymh.html

JS:   throw new Error("错误信息");
来源：http://dali.9152youxi.cn/Article/details/gt2vmplvlgf.html

TS:   throw new Error("错误信息");
来源：http://dali.mhx1999.top/Article/details/gt2fjsnvbeg.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.dashuyun.cn/Article/details/gt2snlzclcl.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.fengsongda.top/Article/details/gt2dxzwunai.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.guowangkeji.top/Article/details/gt2xqigfqeo.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2ncakivta.html

[H04] 自定义异常类型
来源：http://dali.vqdsnc.cn/Article/details/gt2ntimeakm.html

Py:   class MyError(Exception): pass
来源：http://dali.quarkkingdee.top/Article/details/gt2sgtawhyp.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jianghu66.top/Article/details/gt2hfjflaen.html

JS:   class MyError extends Error {}
来源：http://dali.sxryk.cn/Article/details/gt2cmkqlbvf.html

TS:   class MyError extends Error {}
来源：http://dali.tianlin.xyz/Article/details/gt2pbidnwau.html

Java: class MyException extends RuntimeException {}
来源：http://dali.cheryme.top/Article/details/gt2hfhvjeco.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.gotoacloud.top/Article/details/gt2pxhdtovd.html

Ruby: class MyError < StandardError; end
来源：http://dali.xziqi.cn/Article/details/gt2gzdmffam.html

C#:   class MyException : Exception {}
来源：http://dali.zhixingplan.top/Article/details/gt2tsqtqclv.html

[H05] 捕获特定类型
来源：http://dali.zhiwuduotai.top/Article/details/gt2ydzwsdcf.html

Py:   except ValueError as e:
来源：http://dali.cdnleiting.top/Article/details/gt2ahrmptmp.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.feifeiyinyue.top/Article/details/gt2itzhsxbu.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2vupvetti.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yj20258888.top/Article/details/gt2eouklwna.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yueranfly.top/Article/details/gt2bundimhl.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yangfankeji.com/Article/details/gt2pgoevibi.html

Ruby: rescue ArgumentError => e
来源：http://dali.cqqwz.cn/Article/details/gt2jxszqjhp.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.daxiang520.top/Article/details/gt2tvhggmsp.html

[H06] 可选值 / 空值安全访问
来源：http://dali.shangyingyoupin.top/Article/details/gt2mcypjizd.html

Py:   value = d.get("k") or default
来源：http://dali.snrcjt.cn/Article/details/gt2urjuzygf.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jlsjyb.cn/Article/details/gt2ijgntakq.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.feifeiyinyue.top/Article/details/gt2fraushwv.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.gogol.net.cn/Article/details/gt2wjubsqqe.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.tanke756.top/Article/details/gt2ikfzbqle.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhengqikj.top/Article/details/gt2qvyksylq.html

Ruby: d&.dig(:a, :b)
来源：http://dali.sysykeji.top/Article/details/gt2zwkehdiz.html

C#:   obj?.A?.B ?? default
来源：http://dali.kuanghao11.cn/Article/details/gt2cijxwfgy.html

[H07] 断言
来源：http://dali.yj20258.top/Article/details/gt2cgvdgakg.html

Py:   assert x > 0, "必须为正"
来源：http://dali.cheryme.top/Article/details/gt2lbhdjswy.html

PHP:  assert($x > 0);
来源：http://dali.haohaochexian.top/Article/details/gt2ogjqafwq.html

JS:   console.assert(x > 0);
来源：http://dali.chenzaomai.com/Article/details/gt2tffffnti.html

TS:   console.assert(x > 0);
来源：http://dali.andypj.xyz/Article/details/gt2bgcalrlg.html

Java: assert x > 0 : "必须为正";
来源：http://dali.gzhubu.top/Article/details/gt2tvdsmsxc.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.smart0.xyz/Article/details/gt2jswhpgpz.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhoulong.xyz/Article/details/gt2ttnpvwpe.html

C#:   Debug.Assert(x > 0);
来源：http://dali.dashuyun.cn/Article/details/gt2oqnukmez.html

[H08] 获取错误信息与堆栈
来源：http://dali.meibo888.top/Article/details/gt2kueufngx.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yongpay.top/Article/details/gt2ttafakav.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.wangshuangyany.cn/Article/details/gt2qisfhzrw.html

JS:   e.message;  e.stack
来源：http://dali.guowangkeji.top/Article/details/gt2rgnonggd.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yanxiufei.cn/Article/details/gt2bazbqjcr.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.havefunace.top/Article/details/gt2ablhavip.html

Go:   err.Error()
来源：http://dali.birdmap.top/Article/details/gt2eecezopx.html

Ruby: e.message;  e.backtrace
来源：http://dali.xuetiantiany.cn/Article/details/gt2ykilhnth.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uwwkebtn.html

[H09] 带错误码的异常
来源：http://dali.nwbrower.top/Article/details/gt2iwfjonje.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.gotoacloud.top/Article/details/gt2qbpmrpnw.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.wangshuangyany.cn/Article/details/gt2rhcigosb.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.sysykeji.top/Article/details/gt2wibhmtdo.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.ybcxt.top/Article/details/gt2zniukiiv.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.ehwqpu.com/Article/details/gt2ywoqmegy.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.xinyue.icu/Article/details/gt2wxdvusfm.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.tian-w.cn/Article/details/gt2dfecxdzh.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.shzxlz.cn/Article/details/gt2ixoelyve.html

[H10] 资源自动释放
来源：http://dali.svipenyu.cn/Article/details/gt2znyckcot.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.fengsongda.top/Article/details/gt2qqvkkdos.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhixingplan.top/Article/details/gt2kmrruybn.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.iojbl.cn/Article/details/gt2ofbiarud.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cdnleiting.top/Article/details/gt2ipmthghh.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yuxming.cn/Article/details/gt2hzyhoaxj.html

Go:   defer f.Close()
来源：http://dali.feifeiyinyue.top/Article/details/gt2qsjazmod.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.cucudq.cn/Article/details/gt2gvxqblgg.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gt2vmhbnmrp.html


<!-- 参考信息 -->