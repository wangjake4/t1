代发 wailian999

JS:   fs.unlinkSync("a.txt")
来源：http://dali.hnqzz.top/Article/details/gt2mymjhwkv.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.xinyue.icu/Article/details/gt2znfdljoh.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.cheryme.top/Article/details/gt2muihisvt.html

Go:   os.Remove("a.txt")
来源：http://dali.pycfn.com/Article/details/gt2zmbwfqzg.html

Ruby: File.delete("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2osjnkznx.html

C#:   File.Delete("a.txt");
来源：http://dali.xinyue.icu/Article/details/gt2dppvsvvu.html

[F07] 创建目录（含多级）
来源：http://dali.hnqzz.top/Article/details/gt2qlvigder.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.nanxinkj.top/Article/details/gt2cmxybywq.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yangfankeji.com/Article/details/gt2bsotccgg.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.redwolf501.top/Article/details/gt2tgzqwlvd.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xuanzx.com/Article/details/gt2cixbcloe.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hysaishi.cn/Article/details/gt2ybnhsnar.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.hysaishi.cn/Article/details/gt2jturlssc.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhoulong.xyz/Article/details/gt2wxqtpvdm.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.cashguo.top/Article/details/gt2icdrbwmy.html

[F08] 遍历目录
来源：http://dali.xuetiantiany.cn/Article/details/gt2yurfuhle.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.cheryme.top/Article/details/gt2cbgivvmt.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.nwbrower.top/Article/details/gt2roxnacms.html

JS:   fs.readdirSync("dir")
来源：http://dali.fengsongda.top/Article/details/gt2oxxbvscl.html

TS:   fs.readdirSync("dir")
来源：http://dali.mhx1999.top/Article/details/gt2sxgazisf.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhengqikj.top/Article/details/gt2nunfiuix.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.feifeiyinyue.top/Article/details/gt2idnwrgff.html

Ruby: Dir.children("dir")
来源：http://dali.xuanzx.com/Article/details/gt2wziwtmak.html

C#:   Directory.GetFiles("dir")
来源：http://dali.kuanghao11.cn/Article/details/gt2kglfroxd.html

[F09] 获取文件大小
来源：http://dali.smart0.xyz/Article/details/gt2ximmqgyz.html

Py:   os.path.getsize("a.txt")
来源：http://dali.tian-w.cn/Article/details/gt2rdkhplbp.html

PHP:  filesize("a.txt");
来源：http://dali.sysykeji.top/Article/details/gt2yqklxwdw.html

JS:   fs.statSync("a.txt").size
来源：http://dali.ydzc1.top/Article/details/gt2amemfonn.html

TS:   fs.statSync("a.txt").size
来源：http://dali.bjfxy.top/Article/details/gt2jewngvma.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.xuanzx.com/Article/details/gt2nhdpymtm.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.tian-w.cn/Article/details/gt2lhmemfax.html

Ruby: File.size("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gt2vnaunypq.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.chenjidiqi.icu/Article/details/gt2idrsokiu.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.redwolf501.top/Article/details/gt2zzrnvfvc.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gt2jhojxlxs.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.xinyue.icu/Article/details/gt2bukifbdf.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yueranfly.top/Article/details/gt2jpcevjko.html

TS:   path.extname("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gt2eorfazdy.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2klqlvtrp.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2pejdxxqc.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2fjbkaixu.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2ecgzzpfv.html

[F11] 复制与移动文件
来源：http://dali.wangshuangyany.cn/Article/details/gt2qsgldlfw.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2ksxbuwqa.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.hywenlv.cn/Article/details/gt2rqlphcxu.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hysaishi.cn/Article/details/gt2wcdteiuz.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cucudq.cn/Article/details/gt2skqqmiwg.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.birdmap.top/Article/details/gt2wyhlpili.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.pengpengdd.cyou/Article/details/gt2liudtujb.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2gajuhzvt.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jqgufenzy.top/Article/details/gt2isazdplr.html

[F12] CSV 读写
来源：http://dali.yueranfly.top/Article/details/gt2iddrpvcv.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.tianlin.xyz/Article/details/gt2izkrliap.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.shzxlz.cn/Article/details/gt2hxmvtmys.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.guannengcc.top/Article/details/gt2dclvflxj.html

TS:   // 同上
来源：http://dali.hnqzz.top/Article/details/gt2ktwxeetw.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tfnllaei.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yanxiufei.cn/Article/details/gt2ulkjwacn.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.snrcjt.cn/Article/details/gt2rjdjgedz.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.haohaochexian.top/Article/details/gt2wasauiqp.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2gfaxavfw.html

G. 面向对象
来源：http://dali.havefunace.top/Article/details/gt2akefpsfd.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2mqoykmkp.html

[G01] 定义类
来源：http://dali.guannengcc.top/Article/details/gt2trktbwez.html

Py:   class User: pass
来源：http://dali.tianlin.xyz/Article/details/gt2nenduqzf.html

PHP:  class User {}
来源：http://dali.jianghu66.top/Article/details/gt2oqiuldcf.html

JS:   class User {}
来源：http://dali.ehwqpu.com/Article/details/gt2noyficbv.html

TS:   class User { name: string = ""; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2qikxhcbx.html

Java: class User {}
来源：http://dali.yonumen.top/Article/details/gt2myaznjcp.html

Go:   type User struct { Name string }
来源：http://dali.bjfxy.top/Article/details/gt2ejkbkcbm.html

Ruby: class User; end
来源：http://dali.sweek.top/Article/details/gt2qffnguqy.html

C#:   class User {}
来源：http://dali.haohaochexian.top/Article/details/gt2hxlbtyuh.html

[G02] 构造函数
来源：http://dali.ehwqpu.com/Article/details/gt2rntilbca.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.svipenyu.cn/Article/details/gt2agfzoqna.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.guannengcc.top/Article/details/gt2ebyflppx.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.c1oappe.top/Article/details/gt2xbtcmgxy.html

TS:   constructor(public name: string) {}
来源：http://dali.jyoumei.cn/Article/details/gt2pirwpsry.html

Java: User(String name) { this.name = name; }
来源：http://dali.ehwqpu.com/Article/details/gt2zmzdyane.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.vqdsnc.cn/Article/details/gt2efakwskw.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.fzhhl.top/Article/details/gt2rvqmrkqj.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zycfv.cn/Article/details/gt2bpotucsd.html

[G03] 实例属性
来源：http://dali.sweek.top/Article/details/gt2kldquwhy.html

Py:   self.name = "x"
来源：http://dali.gotoacloud.top/Article/details/gt2pvpxlegu.html

PHP:  public string $name = "x";
来源：http://dali.yangfankeji.com/Article/details/gt2mptbfpme.html

JS:   this.name = "x";
来源：http://dali.yueranfly.top/Article/details/gt2mwywoylc.html

TS:   name: string = "x";
来源：http://dali.sysykeji.top/Article/details/gt2elapgpmv.html

Java: private String name;
来源：http://dali.9152youxi.cn/Article/details/gt2ddnryfec.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yanxiufei.cn/Article/details/gt2rpjagboh.html

Ruby: @name = "x"
来源：http://dali.sysykeji.top/Article/details/gt2jlkaimib.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.kuanghao11.cn/Article/details/gt2atkbqgjr.html

[G04] 定义方法
来源：http://dali.chenzaomai.com/Article/details/gt2xordlgtv.html

Py:   def greet(self): return self.name
来源：http://dali.yangfankeji.com/Article/details/gt2zlkizazb.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.mhx1999.top/Article/details/gt2gdzethar.html

JS:   greet() { return this.name; }
来源：http://dali.jinqigfzy.top/Article/details/gt2ehyvsqvl.html

TS:   greet(): string { return this.name; }
来源：http://dali.xylfe.cn/Article/details/gt2ummverzz.html

Java: String greet() { return name; }
来源：http://dali.guannengcc.top/Article/details/gt2bgaucygv.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hammf.cn/Article/details/gt2tcrrmbda.html

Ruby: def greet; @name; end
来源：http://dali.yanxiufei.cn/Article/details/gt2pegnyxtp.html

C#:   public string Greet() => Name;
来源：http://dali.tian-w.cn/Article/details/gt2lyajtctd.html

[G05] 继承
来源：http://dali.tanke756.top/Article/details/gt2oqnxqdow.html

Py:   class Admin(User): pass
来源：http://dali.yueranfly.top/Article/details/gt2npyffoin.html

PHP:  class Admin extends User {}
来源：http://dali.haohaochexian.top/Article/details/gt2oppvijjr.html

JS:   class Admin extends User {}
来源：http://dali.hfpthk.cn/Article/details/gt2hmqfmoru.html

TS:   class Admin extends User {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2uefhigcp.html

Java: class Admin extends User {}
来源：http://dali.tanke756.top/Article/details/gt2mrolnpco.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bzqzqlvi.html

Ruby: class Admin < User; end
来源：http://dali.sweek.top/Article/details/gt2ehgqrgzx.html

C#:   class Admin : User {}
来源：http://dali.tian-w.cn/Article/details/gt2zikzmgtb.html

[G06] 重写方法
来源：http://dali.jinqigufen.top/Article/details/gt2jkwtuxpl.html

Py:   def greet(self): return "admin"
来源：http://dali.aizwys.cn/Article/details/gt2ulhcfgqs.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.mhx1999.top/Article/details/gt2gmbhklqi.html

JS:   greet() { return "admin"; }
来源：http://dali.gaohongyu789.top/Article/details/gt2rnkhajnu.html

TS:   greet(): string { return "admin"; }
来源：http://dali.chenlongwang.top/Article/details/gt2rpqztmmf.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2ffxsnrgy.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.dianchejie.cn/Article/details/gt2zrtigdwe.html

Ruby: def greet; "admin"; end
来源：http://dali.chenjidiqi.icu/Article/details/gt2zrtdnhoo.html

C#:   public override string Greet() => "admin";
来源：http://dali.chenjidiqi.icu/Article/details/gt2dsjieqys.html

[G07] 调用父类方法
来源：http://dali.shangyingyoupin.top/Article/details/gt2ihhpioqc.html

Py:   super().greet()
来源：http://dali.cqqwz.cn/Article/details/gt2gdifrisv.html

PHP:  parent::greet();
来源：http://dali.yueranfly.top/Article/details/gt2vddffgwv.html

JS:   super.greet();
来源：http://dali.hnqzz.top/Article/details/gt2gowqgvtr.html

TS:   super.greet();
来源：http://dali.zhoulong.xyz/Article/details/gt2znphytsl.html

Java: super.greet();
来源：http://dali.hammf.cn/Article/details/gt2dfgdpvks.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.sweek.top/Article/details/gt2gqwchsgn.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gt2qgwmpqtn.html

C#:   base.Greet();
来源：http://dali.gzhubu.top/Article/details/gt2dblargqk.html

[G08] 静态方法与属性
来源：http://dali.xuanzx.com/Article/details/gt2vyvmlyfn.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.cdnleiting.top/Article/details/gt2jrlhivmu.html

PHP:  public static function f() {}
来源：http://dali.fengsongda.top/Article/details/gt2shjgbcoy.html

JS:   static f() {}
来源：http://dali.ehwqpu.com/Article/details/gt2iqcjmhyo.html

TS:   static f(): void {}
来源：http://dali.daria6918.cn/Article/details/gt2umjrrywl.html

Java: static void f() {}
来源：http://dali.birdmap.top/Article/details/gt2emlcjvwz.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.smart0.xyz/Article/details/gt2nwjjuije.html

Ruby: def self.f; end
来源：http://dali.wangshuangyany.cn/Article/details/gt2pchrgstn.html

C#:   public static void F() {}
来源：http://dali.fengsongda.top/Article/details/gt2wmbiyplc.html

[G09] 接口 / 抽象类
来源：http://dali.yuxming.cn/Article/details/gt2owooquik.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.aibaodan.cn/Article/details/gt2tsotvzgh.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.xuanzx.com/Article/details/gt2mqnovzuu.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.guowangkeji.top/Article/details/gt2uzaldshu.html

TS:   interface Shape { area(): number; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2ssoroims.html

Java: interface Shape { double area(); }
来源：http://dali.yueranfly.top/Article/details/gt2srmdaffm.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yuxming.cn/Article/details/gt2ubtrdkwm.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.bjfxy.top/Article/details/gt2pxfbrccc.html

C#:   interface IShape { double Area(); }
来源：http://dali.havefunace.top/Article/details/gt2pdlwbnhy.html

[G10] 访问控制
来源：http://dali.tanke756.top/Article/details/gt2iaivbsnr.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yanxiufei.cn/Article/details/gt2yrmdujiy.html

PHP:  public / protected / private
来源：http://dali.9152youxi.cn/Article/details/gt2jhutvovi.html

JS:   #private 字段；其余公开
来源：http://dali.yangfankeji.com/Article/details/gt2vsdpeowu.html

TS:   public / protected / private
来源：http://dali.zycfv.cn/Article/details/gt2skaytqpu.html

Java: public / protected / private / 默认包级
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2onnvpnlb.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dcdvikmy.html

Ruby: public / protected / private
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rnvtlhjb.html

C#:   public / protected / private / internal
来源：http://dali.cheryme.top/Article/details/gt2qzugqmfr.html

[G11] getter / setter
来源：http://dali.hnqzz.top/Article/details/gt2uectkvoh.html

Py:   @property 与 @x.setter
来源：http://dali.haohaochexian.top/Article/details/gt2utguziza.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jlsjyb.cn/Article/details/gt2wdzskcuz.html

JS:   get name() { return this._name; }
来源：http://dali.hnxiangtu.top/Article/details/gt2nfzalzqb.html

TS:   get name(): string { return this._name; }
来源：http://dali.quarkkingdee.top/Article/details/gt2czbozinz.html

Java: public String getName() { return name; }
来源：http://dali.tian-w.cn/Article/details/gt2zzktmehu.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jinqigufen.top/Article/details/gt2xtgiwxmi.html

Ruby: attr_accessor :name
来源：http://dali.ehwqpu.com/Article/details/gt2ruhkuccx.html

C#:   public string Name { get; set; }
来源：http://dali.quarkkingdee.top/Article/details/gt2evpifiqe.html

[G12] 对象转字符串
来源：http://dali.shangyingyoupin.top/Article/details/gt2ktjysdgk.html

Py:   def __str__(self): return self.name
来源：http://dali.cheryme.top/Article/details/gt2xnauqavj.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2kwgjztkw.html

JS:   toString() { return this.name; }
来源：http://dali.nwbrower.top/Article/details/gt2dlswioyt.html

TS:   toString(): string { return this.name; }
来源：http://dali.yuanzhike.top/Article/details/gt2asslhdum.html

Java: @Override public String toString() { return name; }
来源：http://dali.cdnleiting.top/Article/details/gt2icddgoqi.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.guannengcc.top/Article/details/gt2kcqgedcj.html

Ruby: def to_s; @name; end
来源：http://dali.vqdsnc.cn/Article/details/gt2cxaukuna.html

C#:   public override string ToString() => Name;
来源：http://dali.0kj1m.cn/Article/details/gt2iahhocdt.html

[G13] 判断对象类型
来源：http://dali.cucudq.cn/Article/details/gt2nodbcmrd.html

Py:   isinstance(u, User)
来源：http://dali.daria6918.cn/Article/details/gt2ocgbuxno.html

PHP:  $u instanceof User
来源：http://dali.ehwqpu.com/Article/details/gt2lzizinrv.html

JS:   u instanceof User
来源：http://dali.daxiang520.top/Article/details/gt2gmugladx.html

TS:   u instanceof User
来源：http://dali.fzhhl.top/Article/details/gt2abqnrwrl.html

Java: u instanceof User
来源：http://dali.hnxiangtu.top/Article/details/gt2ruldqimk.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jinqigfzy.top/Article/details/gt2xogpezhu.html

Ruby: u.is_a?(User)
来源：http://dali.yj20258888.top/Article/details/gt2kvdvhtto.html

C#:   u is User
来源：http://dali.yj20258.top/Article/details/gt2tgqnzqka.html

[G14] 数据类 / record
来源：http://dali.hnqzz.top/Article/details/gt2qsnkacyx.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.quarkkingdee.top/Article/details/gt2tsszruwf.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.haohaochexian.top/Article/details/gt2poskakxm.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.fengsongda.top/Article/details/gt2ejcstmfc.html

TS:   type User = { name: string; age: number };
来源：http://dali.hammf.cn/Article/details/gt2rvasnlsu.html

Java: record User(String name, int age) {}
来源：http://dali.zhengqikj.top/Article/details/gt2jxbvblom.html

Go:   type User struct { Name string; Age int }
来源：http://dali.guannengcc.top/Article/details/gt2vjseosqj.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yuxming.cn/Article/details/gt2cbhuhmxd.html

C#:   record User(string Name, int Age);
来源：http://dali.tianlin.xyz/Article/details/gt2qjzxxcrr.html

[G15] 枚举
来源：http://dali.pycfn.com/Article/details/gt2bcoqzceb.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.mhx1999.top/Article/details/gt2dcqlznxo.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.dashuyun.cn/Article/details/gt2phxhxkxu.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jqgufenzy.top/Article/details/gt2ohjzteer.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yangfankeji.com/Article/details/gt2ouxrnmkj.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhoulong.xyz/Article/details/gt2esbfhfpj.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yongpay.top/Article/details/gt2qpwgxxrt.html

Ruby: Color = %i[red green].freeze
来源：http://dali.c1oappe.top/Article/details/gt2oalhhoka.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.daria6918.cn/Article/details/gt2vlkqhiez.html

[G16] 对象转数组 / 字典
来源：http://dali.yj20258888.top/Article/details/gt2sxtwcuzn.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.iojbl.cn/Article/details/gt2zcfrpbzv.html

PHP:  get_object_vars($obj);
来源：http://dali.svipenyu.cn/Article/details/gt2rtesfcwo.html

JS:   Object.entries(obj)
来源：http://dali.jqgufenzy.top/Article/details/gt2askkjtcf.html

TS:   Object.entries(obj)
来源：http://dali.daria6918.cn/Article/details/gt2ekoajizj.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.dashuyun.cn/Article/details/gt2pkdcbawb.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.cucudq.cn/Article/details/gt2zndzrfbq.html

Ruby: obj.instance_variables
来源：http://dali.yueranfly.top/Article/details/gt2uanzhaeu.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.iojbl.cn/Article/details/gt2eldkuacw.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2pebidfoo.html

H. 异常与错误处理
来源：http://dali.yuanzhike.top/Article/details/gt2wvwmgbfy.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2fxxqmhti.html

[H01] try / catch 基础
来源：http://dali.gogol.net.cn/Article/details/gt2ndefmlee.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.aibaodan.cn/Article/details/gt2muvdlmhn.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.guannengcc.top/Article/details/gt2czxiwcap.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.ybcxt.top/Article/details/gt2nnnlmrhr.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yonumen.top/Article/details/gt2cuigaudh.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jqgufenzy.top/Article/details/gt2izyxuszq.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yuxming.cn/Article/details/gt2grfyjjoo.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.pengpengdd.cyou/Article/details/gt2braaklao.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.gzhubu.top/Article/details/gt2imymhzql.html

[H02] finally / ensure 收尾
来源：http://dali.cashguo.top/Article/details/gt2zfqdzbfx.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2njbkkpds.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.birdmap.top/Article/details/gt2cwzbotsj.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2adrjayiu.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2dkfuvpeg.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.sysykeji.top/Article/details/gt2srqlqusq.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.chenlongwang.top/Article/details/gt2pnjpjhea.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.hywenlv.cn/Article/details/gt2vslusunx.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.tianlin.xyz/Article/details/gt2zwteugvn.html

[H03] 主动抛出异常
来源：http://dali.birdmap.top/Article/details/gt2thtormrg.html

Py:   raise ValueError("错误信息")
来源：http://dali.yuxming.cn/Article/details/gt2azgwrpgd.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.tanke756.top/Article/details/gt2hivgsrxd.html

JS:   throw new Error("错误信息");
来源：http://dali.ydzc1.top/Article/details/gt2qactzbna.html

TS:   throw new Error("错误信息");
来源：http://dali.guowangkeji.top/Article/details/gt2gzofvyxq.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xuetiantiany.cn/Article/details/gt2iclxnwtv.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.nwbrower.top/Article/details/gt2uiiwxzxd.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.xuanzx.com/Article/details/gt2oxvdfgca.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.redwolf501.top/Article/details/gt2qqefaycn.html

[H04] 自定义异常类型
来源：http://dali.jqgfzy.top/Article/details/gt2dgweoedd.html

Py:   class MyError(Exception): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2hpyscaie.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.fzhhl.top/Article/details/gt2zpmxkzai.html

JS:   class MyError extends Error {}
来源：http://dali.yvedp.cn/Article/details/gt2ikfjozxy.html

TS:   class MyError extends Error {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2futeehpl.html

Java: class MyException extends RuntimeException {}
来源：http://dali.c1oappe.top/Article/details/gt2mxjfhzqf.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kavbcypz.html

Ruby: class MyError < StandardError; end
来源：http://dali.wangshuangyany.cn/Article/details/gt2zalubsvl.html

C#:   class MyException : Exception {}
来源：http://dali.haohaochexian.top/Article/details/gt2qaxjisfa.html

[H05] 捕获特定类型
来源：http://dali.cashguo.top/Article/details/gt2mtuyajmv.html

Py:   except ValueError as e:
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vtygbnab.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.hnqzz.top/Article/details/gt2xtoqrwjf.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.hnxiangtu.top/Article/details/gt2kdyjwtro.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.fzhhl.top/Article/details/gt2bkbwqwyn.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hnxiangtu.top/Article/details/gt2sirwcocx.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhixingplan.top/Article/details/gt2bukwfdei.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhiwuduotai.top/Article/details/gt2gepyhtlv.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.guowangkeji.top/Article/details/gt2hhysqesw.html

[H06] 可选值 / 空值安全访问
来源：http://dali.andypj.xyz/Article/details/gt2skvpkzvt.html

Py:   value = d.get("k") or default
来源：http://dali.jiagoushi.top/Article/details/gt2ohrkbsgh.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.iojbl.cn/Article/details/gt2rdijbeay.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.iojbl.cn/Article/details/gt2gayhyxnx.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jiagoushi.top/Article/details/gt2akmuubqe.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.ybcxt.top/Article/details/gt2lhnkthgv.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.birdmap.top/Article/details/gt2vfsbhxcg.html

Ruby: d&.dig(:a, :b)
来源：http://dali.c1oappe.top/Article/details/gt2mdqgubcx.html

C#:   obj?.A?.B ?? default
来源：http://dali.fzhhl.top/Article/details/gt2bkbnshyo.html

[H07] 断言
来源：http://dali.9152youxi.cn/Article/details/gt2eougxfod.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhixingplan.top/Article/details/gt2axjrqevy.html

PHP:  assert($x > 0);
来源：http://dali.xylfe.cn/Article/details/gt2osgbfdbu.html

JS:   console.assert(x > 0);
来源：http://dali.yvedp.cn/Article/details/gt2mwwukgaw.html

TS:   console.assert(x > 0);
来源：http://dali.wangshuangyany.cn/Article/details/gt2lumyrbrd.html

Java: assert x > 0 : "必须为正";
来源：http://dali.feifeiyinyue.top/Article/details/gt2ldynqrrv.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.hammf.cn/Article/details/gt2cbylnufr.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.chenjidiqi.icu/Article/details/gt2sekgynka.html

C#:   Debug.Assert(x > 0);
来源：http://dali.sxryk.cn/Article/details/gt2huvskwet.html

[H08] 获取错误信息与堆栈
来源：http://dali.wangshuangyany.cn/Article/details/gt2ditlodjy.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.iojbl.cn/Article/details/gt2papobmcv.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.wangdashe.top/Article/details/gt2qeleofks.html

JS:   e.message;  e.stack
来源：http://dali.gzhubu.top/Article/details/gt2vrnikknf.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nreqlnmo.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhengqikj.top/Article/details/gt2hwsboxze.html

Go:   err.Error()
来源：http://dali.yongpay.top/Article/details/gt2kpkgeagn.html

Ruby: e.message;  e.backtrace
来源：http://dali.hammf.cn/Article/details/gt2ttzunyaz.html

C#:   e.Message;  e.StackTrace
来源：http://dali.dashuyun.cn/Article/details/gt2rchzgbyo.html

[H09] 带错误码的异常
来源：http://dali.kuanghao11.cn/Article/details/gt2rixuaglu.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.smart0.xyz/Article/details/gt2yucqhbqz.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.shuidangran.top/Article/details/gt2qqsfqvuv.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.snrcjt.cn/Article/details/gt2qikjobkf.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.gotoacloud.top/Article/details/gt2lxkrynzn.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.cqqwz.cn/Article/details/gt2jarajdgs.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yvedp.cn/Article/details/gt2acyrmhhi.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.nwbrower.top/Article/details/gt2xpamjbhr.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.vqdsnc.cn/Article/details/gt2zsmpyeka.html

[H10] 资源自动释放
来源：http://dali.sysykeji.top/Article/details/gt2bmatyzhk.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.pengpengdd.cyou/Article/details/gt2tefvoewe.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.hnxiangtu.top/Article/details/gt2lbizvvsw.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.pengpengdd.cyou/Article/details/gt2rnyiluwp.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.feifeiyinyue.top/Article/details/gt2hlouhzgd.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.ydzc1.top/Article/details/gt2zwkysdhb.html

Go:   defer f.Close()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nycnxqyn.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hywenlv.cn/Article/details/gt2gsjvmuyj.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xinmhvzd.html


<!-- 参考信息 -->