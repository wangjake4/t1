代发 wailian999

C#:   File.Exists("a.txt")
来源：http://dali.pycfn.com/Article/details/gt2jkadsfbc.html

[F06] 删除文件
来源：http://dali.zhixingplan.top/Article/details/gt2itpgskhi.html

Py:   os.remove("a.txt")
来源：http://dali.fzhhl.top/Article/details/gt2mnvcjvzp.html

PHP:  unlink("a.txt");
来源：http://dali.shuidangran.top/Article/details/gt2ekxjgogf.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gt2lmfnfjxu.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yonumen.top/Article/details/gt2pablzlmm.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.pycfn.com/Article/details/gt2iyqjfqow.html

Go:   os.Remove("a.txt")
来源：http://dali.bjfxy.top/Article/details/gt2tnqxwzig.html

Ruby: File.delete("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gt2vbxrwzaw.html

C#:   File.Delete("a.txt");
来源：http://dali.birdmap.top/Article/details/gt2nlslkhrv.html

[F07] 创建目录（含多级）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dvyqdtyi.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jqgfzy.top/Article/details/gt2stcmpduy.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.bjfxy.top/Article/details/gt2dxcqhlax.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.nwbrower.top/Article/details/gt2seygsgzt.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhongyouzk.top/Article/details/gt2walnrzfy.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhengqikj.top/Article/details/gt2ywdatlbt.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.aizwys.cn/Article/details/gt2okzjwcxu.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.redwolf501.top/Article/details/gt2gnqldnur.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xicrxapp.html

[F08] 遍历目录
来源：http://dali.0kj1m.cn/Article/details/gt2fuxigyyd.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yj202588.top/Article/details/gt2gvupfnii.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.cheryme.top/Article/details/gt2zrzeiznn.html

JS:   fs.readdirSync("dir")
来源：http://dali.nanxuanxn.top/Article/details/gt2nerbndxa.html

TS:   fs.readdirSync("dir")
来源：http://dali.jqgufenzy.top/Article/details/gt2eabacrbw.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.redwolf501.top/Article/details/gt2yalgqjcu.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.0kj1m.cn/Article/details/gt2akrwynar.html

Ruby: Dir.children("dir")
来源：http://dali.ivvv.top/Article/details/gt2qnnbvist.html

C#:   Directory.GetFiles("dir")
来源：http://dali.xuetiantiany.cn/Article/details/gt2vowxmksn.html

[F09] 获取文件大小
来源：http://dali.xziqi.cn/Article/details/gt2ezpbpzmd.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2krzawhjh.html

PHP:  filesize("a.txt");
来源：http://dali.cdnleiting.top/Article/details/gt2zxekcbip.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jiagoushi.top/Article/details/gt2ljphqxrd.html

TS:   fs.statSync("a.txt").size
来源：http://dali.tianlin.xyz/Article/details/gt2zvkeiaqt.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.ydzc1.top/Article/details/gt2iduyykgq.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.fengsongda.top/Article/details/gt2uwbgsbjc.html

Ruby: File.size("a.txt")
来源：http://dali.havefunace.top/Article/details/gt2ednlxeup.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rgvhmubj.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhiwuduotai.top/Article/details/gt2qrzxevmt.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2mrjkltnw.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gt2shtevjes.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.pycfn.com/Article/details/gt2wanxtxgp.html

TS:   path.extname("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rbzzaecc.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.andypj.xyz/Article/details/gt2qtzgiyre.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yj20258888.top/Article/details/gt2slcwilxf.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yueranfly.top/Article/details/gt2cpxoqmhr.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.cucudq.cn/Article/details/gt2nmsrfykz.html

[F11] 复制与移动文件
来源：http://dali.hnqzz.top/Article/details/gt2ttqxcpht.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.meibo888.top/Article/details/gt2wqqgkhyr.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.fengsongda.top/Article/details/gt2mjcnneox.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pucgkbxi.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xuanzx.com/Article/details/gt2diwaddvp.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.birdmap.top/Article/details/gt2ugqfwxlk.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.gotoacloud.top/Article/details/gt2obznbdcz.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2xvztgwvs.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yanxiufei.cn/Article/details/gt2osacejxg.html

[F12] CSV 读写
来源：http://dali.hysaishi.cn/Article/details/gt2rhpcupiu.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.nanxuanxn.top/Article/details/gt2yxfbsmcw.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hnqzz.top/Article/details/gt2vtvhgsra.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hysaishi.cn/Article/details/gt2znkhijlv.html

TS:   // 同上
来源：http://dali.sysykeji.top/Article/details/gt2pnhvtwqq.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.gaohongyu789.top/Article/details/gt2kmcocjmt.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yuanzhike.top/Article/details/gt2vlgafpri.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.chenlongwang.top/Article/details/gt2oslpsgjj.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.cashguo.top/Article/details/gt2ohlaqgbe.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2hazhtort.html

G. 面向对象
来源：http://dali.zhongyouzk.top/Article/details/gt2ukthorjv.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2kplkaamy.html

[G01] 定义类
来源：http://dali.snrcjt.cn/Article/details/gt2miuskwko.html

Py:   class User: pass
来源：http://dali.hammf.cn/Article/details/gt2tikdoylf.html

PHP:  class User {}
来源：http://dali.xinyue.icu/Article/details/gt2ykrycymi.html

JS:   class User {}
来源：http://dali.gaohongyu789.top/Article/details/gt2pfeqqwaa.html

TS:   class User { name: string = ""; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qtfrlozk.html

Java: class User {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2adssmsjh.html

Go:   type User struct { Name string }
来源：http://dali.ivvv.top/Article/details/gt2xdydbrox.html

Ruby: class User; end
来源：http://dali.jinghuilouyu.cn/Article/details/gt2svduirkd.html

C#:   class User {}
来源：http://dali.hammf.cn/Article/details/gt2iowofrwp.html

[G02] 构造函数
来源：http://dali.nanxuanxn.top/Article/details/gt2whznfrzz.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jianghu66.top/Article/details/gt2idxbpfry.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.kuanghao11.cn/Article/details/gt2ebxbcsfx.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yueranfly.top/Article/details/gt2amfonurq.html

TS:   constructor(public name: string) {}
来源：http://dali.tanke756.top/Article/details/gt2ccbbgzyu.html

Java: User(String name) { this.name = name; }
来源：http://dali.aizwys.cn/Article/details/gt2euykoond.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.tian-w.cn/Article/details/gt2qmriowjn.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.tanke756.top/Article/details/gt2ihvyvqwa.html

C#:   public User(string name) { Name = name; }
来源：http://dali.gogol.net.cn/Article/details/gt2scghkfia.html

[G03] 实例属性
来源：http://dali.hongshengwenyu.top/Article/details/gt2svspoyul.html

Py:   self.name = "x"
来源：http://dali.xinyue.icu/Article/details/gt2iyeplxdv.html

PHP:  public string $name = "x";
来源：http://dali.zhongyouzk.top/Article/details/gt2smdjorcf.html

JS:   this.name = "x";
来源：http://dali.aibaodan.cn/Article/details/gt2ihitswny.html

TS:   name: string = "x";
来源：http://dali.andypj.xyz/Article/details/gt2ihxwqufb.html

Java: private String name;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uqqfkfca.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.andypj.xyz/Article/details/gt2apcxzmic.html

Ruby: @name = "x"
来源：http://dali.xinyue.icu/Article/details/gt2bwimpycn.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.tianlin.xyz/Article/details/gt2wcjhuvit.html

[G04] 定义方法
来源：http://dali.sufxvd.cn/Article/details/gt2ecaiushk.html

Py:   def greet(self): return self.name
来源：http://dali.meibo888.top/Article/details/gt2fenrxtev.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.gotoacloud.top/Article/details/gt2qzokjpgc.html

JS:   greet() { return this.name; }
来源：http://dali.cdnleiting.top/Article/details/gt2qegczonp.html

TS:   greet(): string { return this.name; }
来源：http://dali.ehwqpu.com/Article/details/gt2xyeieoxg.html

Java: String greet() { return name; }
来源：http://dali.hywenlv.cn/Article/details/gt2dmwqcixy.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.xziqi.cn/Article/details/gt2fcwgyvff.html

Ruby: def greet; @name; end
来源：http://dali.dianchejie.cn/Article/details/gt2jezdiyay.html

C#:   public string Greet() => Name;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2spcqtvva.html

[G05] 继承
来源：http://dali.0kj1m.cn/Article/details/gt2tbhdraoz.html

Py:   class Admin(User): pass
来源：http://dali.nanxuanxn.top/Article/details/gt2qgqkthin.html

PHP:  class Admin extends User {}
来源：http://dali.havefunace.top/Article/details/gt2ttbzkdpk.html

JS:   class Admin extends User {}
来源：http://dali.tanke756.top/Article/details/gt2jtbzgozk.html

TS:   class Admin extends User {}
来源：http://dali.yj202588.top/Article/details/gt2vxpppbuq.html

Java: class Admin extends User {}
来源：http://dali.c1oappe.top/Article/details/gt2jofrejcz.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.gotoacloud.top/Article/details/gt2jgrmtdwj.html

Ruby: class Admin < User; end
来源：http://dali.yonumen.top/Article/details/gt2miedtmhh.html

C#:   class Admin : User {}
来源：http://dali.hammf.cn/Article/details/gt2qmwpnzic.html

[G06] 重写方法
来源：http://dali.gzhubu.top/Article/details/gt2paxcflyo.html

Py:   def greet(self): return "admin"
来源：http://dali.hfpthk.cn/Article/details/gt2veuoojfp.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.smart0.xyz/Article/details/gt2yrybnhyc.html

JS:   greet() { return "admin"; }
来源：http://dali.hysaishi.cn/Article/details/gt2dcmafkdx.html

TS:   greet(): string { return "admin"; }
来源：http://dali.sweek.top/Article/details/gt2pinfoaom.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.vqdsnc.cn/Article/details/gt2ciexqbxm.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.guannengcc.top/Article/details/gt2tbuuqeld.html

Ruby: def greet; "admin"; end
来源：http://dali.yj202588.top/Article/details/gt2ymzogszv.html

C#:   public override string Greet() => "admin";
来源：http://dali.ehwqpu.com/Article/details/gt2iolvqpan.html

[G07] 调用父类方法
来源：http://dali.daria6918.cn/Article/details/gt2ykfnskvv.html

Py:   super().greet()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bebtmiky.html

PHP:  parent::greet();
来源：http://dali.ydzc1.top/Article/details/gt2vxglvgjx.html

JS:   super.greet();
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vsjwgzjw.html

TS:   super.greet();
来源：http://dali.guannengcc.top/Article/details/gt2bkqlxbht.html

Java: super.greet();
来源：http://dali.quarkkingdee.top/Article/details/gt2febogdeg.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.sufxvd.cn/Article/details/gt2nnoecaap.html

Ruby: super
来源：http://dali.fzhhl.top/Article/details/gt2tkntsfvl.html

C#:   base.Greet();
来源：http://dali.hongshengwenyu.top/Article/details/gt2pkouxumz.html

[G08] 静态方法与属性
来源：http://dali.zhongyouzk.top/Article/details/gt2lyasivty.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.bjfxy.top/Article/details/gt2hspiwlio.html

PHP:  public static function f() {}
来源：http://dali.zycfv.cn/Article/details/gt2cdlwmuad.html

JS:   static f() {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2xtlpzbzy.html

TS:   static f(): void {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xqoogjem.html

Java: static void f() {}
来源：http://dali.kuanghao11.cn/Article/details/gt2jmshxcgo.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.gaohongyu789.top/Article/details/gt2qrpjcydy.html

Ruby: def self.f; end
来源：http://dali.andypj.xyz/Article/details/gt2rwamcxzk.html

C#:   public static void F() {}
来源：http://dali.jianghu66.top/Article/details/gt2iucdxaat.html

[G09] 接口 / 抽象类
来源：http://dali.zhongyouzk.top/Article/details/gt2atfwibkd.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.9152youxi.cn/Article/details/gt2qtyxhghy.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.sysykeji.top/Article/details/gt2gcrtgarf.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.cucudq.cn/Article/details/gt2camqoogw.html

TS:   interface Shape { area(): number; }
来源：http://dali.yonumen.top/Article/details/gt2bruflkvk.html

Java: interface Shape { double area(); }
来源：http://dali.xziqi.cn/Article/details/gt2bzdlyddq.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jianghu66.top/Article/details/gt2qdxtwzwu.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.svipenyu.cn/Article/details/gt2lrebmogp.html

C#:   interface IShape { double Area(); }
来源：http://dali.aizwys.cn/Article/details/gt2iynxroeo.html

[G10] 访问控制
来源：http://dali.cashguo.top/Article/details/gt2vjbuyhkr.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.aibaodan.cn/Article/details/gt2jzyfiocc.html

PHP:  public / protected / private
来源：http://dali.jianghu66.top/Article/details/gt2otnxazyx.html

JS:   #private 字段；其余公开
来源：http://dali.nanxuanxn.top/Article/details/gt2drmimfye.html

TS:   public / protected / private
来源：http://dali.yvedp.cn/Article/details/gt2eudvjgbk.html

Java: public / protected / private / 默认包级
来源：http://dali.zdqjudy.top/Article/details/gt2zdguvsrn.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jiagoushi.top/Article/details/gt2mpwigbyx.html

Ruby: public / protected / private
来源：http://dali.jinqigufen.top/Article/details/gt2tnpqxtlr.html

C#:   public / protected / private / internal
来源：http://dali.aibaodan.cn/Article/details/gt2falxzhka.html

[G11] getter / setter
来源：http://dali.gaohongyu789.top/Article/details/gt2qyjciwvv.html

Py:   @property 与 @x.setter
来源：http://dali.zhengqikj.top/Article/details/gt2xeoxrnra.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.ybcxt.top/Article/details/gt2jmwjoaby.html

JS:   get name() { return this._name; }
来源：http://dali.mhx1999.top/Article/details/gt2roklheyn.html

TS:   get name(): string { return this._name; }
来源：http://dali.jinqigfzy.top/Article/details/gt2hgqoppge.html

Java: public String getName() { return name; }
来源：http://dali.yj20258.top/Article/details/gt2ccvhlszl.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.redwolf501.top/Article/details/gt2blandupv.html

Ruby: attr_accessor :name
来源：http://dali.birdmap.top/Article/details/gt2putasoih.html

C#:   public string Name { get; set; }
来源：http://dali.jianghu66.top/Article/details/gt2qzjoiibs.html

[G12] 对象转字符串
来源：http://dali.yvedp.cn/Article/details/gt2xeyfpfjj.html

Py:   def __str__(self): return self.name
来源：http://dali.316326.xyz/Article/details/gt2jfsealrc.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jlsjyb.cn/Article/details/gt2vgtmqlec.html

JS:   toString() { return this.name; }
来源：http://dali.hnxiangtu.top/Article/details/gt2towvfjpv.html

TS:   toString(): string { return this.name; }
来源：http://dali.fzhhl.top/Article/details/gt2dsjyvfdn.html

Java: @Override public String toString() { return name; }
来源：http://dali.birdmap.top/Article/details/gt2cxxirpgh.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.xinyue.icu/Article/details/gt2wixthkjx.html

Ruby: def to_s; @name; end
来源：http://dali.birdmap.top/Article/details/gt2jxikvijy.html

C#:   public override string ToString() => Name;
来源：http://dali.bjfxy.top/Article/details/gt2jschoyhn.html

[G13] 判断对象类型
来源：http://dali.yongpay.top/Article/details/gt2mtwwcrmp.html

Py:   isinstance(u, User)
来源：http://dali.0kj1m.cn/Article/details/gt2qozmfruk.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2beqoywyd.html

JS:   u instanceof User
来源：http://dali.wangdashe.top/Article/details/gt2smbyudzz.html

TS:   u instanceof User
来源：http://dali.pengpengdd.cyou/Article/details/gt2ugcdxjub.html

Java: u instanceof User
来源：http://dali.hnqzz.top/Article/details/gt2fqsrmwtw.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zycfv.cn/Article/details/gt2riwyiffl.html

Ruby: u.is_a?(User)
来源：http://dali.sxryk.cn/Article/details/gt2lwxulobl.html

C#:   u is User
来源：http://dali.guowangkeji.top/Article/details/gt2gmaittqn.html

[G14] 数据类 / record
来源：http://dali.chenjidiqi.icu/Article/details/gt2ijvqeepp.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.tian-w.cn/Article/details/gt2oevybhpu.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hnxiangtu.top/Article/details/gt2cwjqmsat.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.birdmap.top/Article/details/gt2uyeviowi.html

TS:   type User = { name: string; age: number };
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2svswhvrx.html

Java: record User(String name, int age) {}
来源：http://dali.zdqjudy.top/Article/details/gt2fkpuxuyq.html

Go:   type User struct { Name string; Age int }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yyxmjplx.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhongyouzk.top/Article/details/gt2nwzpnfiy.html

C#:   record User(string Name, int Age);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xoqwqnek.html

[G15] 枚举
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2knlqfpyu.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.guowangkeji.top/Article/details/gt2kwmqsbbj.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cbykcpsl.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.dashuyun.cn/Article/details/gt2rvhrfjhv.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.316326.xyz/Article/details/gt2vqvygrxc.html

Java: enum Color { RED, GREEN }
来源：http://dali.havefunace.top/Article/details/gt2tclddkqr.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.guannengcc.top/Article/details/gt2eqqqxone.html

Ruby: Color = %i[red green].freeze
来源：http://dali.guowangkeji.top/Article/details/gt2qmbnyxpg.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xziqi.cn/Article/details/gt2uxptcsob.html

[G16] 对象转数组 / 字典
来源：http://dali.ivvv.top/Article/details/gt2xexsbsog.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aawvtsrw.html

PHP:  get_object_vars($obj);
来源：http://dali.ppjwa.cn/Article/details/gt2yiwynmug.html

JS:   Object.entries(obj)
来源：http://dali.snrcjt.cn/Article/details/gt2lmxpippe.html

TS:   Object.entries(obj)
来源：http://dali.vqdsnc.cn/Article/details/gt2quasfuge.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.gotoacloud.top/Article/details/gt2prutgwmm.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.gzhubu.top/Article/details/gt2kpfknlop.html

Ruby: obj.instance_variables
来源：http://dali.dashuyun.cn/Article/details/gt2fasvbokz.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.daxiang520.top/Article/details/gt2noyixtoi.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2imwrhlkh.html

H. 异常与错误处理
来源：http://dali.jianghu66.top/Article/details/gt2dcosynyz.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2nwamxkgk.html

[H01] try / catch 基础
来源：http://dali.dashuyun.cn/Article/details/gt2bqogafzf.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zdqjudy.top/Article/details/gt2aaqttkeu.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhixingplan.top/Article/details/gt2wyedrjhc.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.tanke756.top/Article/details/gt2yslgihmz.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2svrdvdmw.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.kuanghao11.cn/Article/details/gt2aohqobfh.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.dashuyun.cn/Article/details/gt2qkjzhdlv.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jyoumei.cn/Article/details/gt2lyqoyuok.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.9152youxi.cn/Article/details/gt2gnqousbh.html

[H02] finally / ensure 收尾
来源：http://dali.tanke756.top/Article/details/gt2mcgerone.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.nwbrower.top/Article/details/gt2pguwsgrg.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hysaishi.cn/Article/details/gt2pfufvpsg.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.gogol.net.cn/Article/details/gt2ilttkjia.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.xylfe.cn/Article/details/gt2pvtcshyo.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.svipenyu.cn/Article/details/gt2kgpytelu.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zdqjudy.top/Article/details/gt2yiztwhkq.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zdqjudy.top/Article/details/gt2phfxybys.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.cheryme.top/Article/details/gt2xevbxtld.html

[H03] 主动抛出异常
来源：http://dali.yj202588.top/Article/details/gt2fmncttdx.html

Py:   raise ValueError("错误信息")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ildyaxja.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.chenzaomai.com/Article/details/gt2bwwzlxad.html

JS:   throw new Error("错误信息");
来源：http://dali.sufxvd.cn/Article/details/gt2mnfimwnv.html

TS:   throw new Error("错误信息");
来源：http://dali.kuanghao11.cn/Article/details/gt2xgixmnxp.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jyoumei.cn/Article/details/gt2tojzpday.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.shuidangran.top/Article/details/gt2neugfqma.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.feifeiyinyue.top/Article/details/gt2wguqrwnk.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.daxiang520.top/Article/details/gt2mdrctztv.html

[H04] 自定义异常类型
来源：http://dali.ybcxt.top/Article/details/gt2xogxkbnk.html

Py:   class MyError(Exception): pass
来源：http://dali.tian-w.cn/Article/details/gt2attffuap.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.hysaishi.cn/Article/details/gt2ipefeejb.html

JS:   class MyError extends Error {}
来源：http://dali.xziqi.cn/Article/details/gt2enrxczuk.html

TS:   class MyError extends Error {}
来源：http://dali.birdmap.top/Article/details/gt2hfowuuhq.html

Java: class MyException extends RuntimeException {}
来源：http://dali.nanxuanxn.top/Article/details/gt2pxfkspys.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.nanxuanxn.top/Article/details/gt2frztnvuh.html

Ruby: class MyError < StandardError; end
来源：http://dali.fzhhl.top/Article/details/gt2amsxbdxa.html

C#:   class MyException : Exception {}
来源：http://dali.vqdsnc.cn/Article/details/gt2mcezqzwh.html

[H05] 捕获特定类型
来源：http://dali.yangfankeji.com/Article/details/gt2nkfodxlf.html

Py:   except ValueError as e:
来源：http://dali.guannengcc.top/Article/details/gt2pexjxcqj.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.pengpengdd.cyou/Article/details/gt2izufhoye.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2phtlgfhy.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.smart0.xyz/Article/details/gt2oolkfuih.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tywjikga.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.hnqzz.top/Article/details/gt2xaeirbvl.html

Ruby: rescue ArgumentError => e
来源：http://dali.chenjidiqi.icu/Article/details/gt2xnqqmgfa.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hfpthk.cn/Article/details/gt2koqjzgmu.html

[H06] 可选值 / 空值安全访问
来源：http://dali.mhx1999.top/Article/details/gt2rfasqxpw.html

Py:   value = d.get("k") or default
来源：http://dali.ybcxt.top/Article/details/gt2tsuigwdj.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.xziqi.cn/Article/details/gt2kzcjtirv.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jqgufenzy.top/Article/details/gt2niqawoax.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.9152youxi.cn/Article/details/gt2bsqmosju.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yangfankeji.com/Article/details/gt2fakjiivv.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.haohaochexian.top/Article/details/gt2vndcissr.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hnxiangtu.top/Article/details/gt2cougcwcr.html

C#:   obj?.A?.B ?? default
来源：http://dali.yj202588.top/Article/details/gt2tvybvosk.html

[H07] 断言
来源：http://dali.daxiang520.top/Article/details/gt2cyjcoitr.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jlsjyb.cn/Article/details/gt2uhkxprtp.html

PHP:  assert($x > 0);
来源：http://dali.dashuyun.cn/Article/details/gt2ttggzvrg.html

JS:   console.assert(x > 0);
来源：http://dali.xziqi.cn/Article/details/gt2yetlzayd.html

TS:   console.assert(x > 0);
来源：http://dali.xziqi.cn/Article/details/gt2dbhnurwf.html

Java: assert x > 0 : "必须为正";
来源：http://dali.hfpthk.cn/Article/details/gt2gytulctq.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.fzhhl.top/Article/details/gt2dkmcpxsw.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhiwuduotai.top/Article/details/gt2qsspkrkv.html

C#:   Debug.Assert(x > 0);
来源：http://dali.aizwys.cn/Article/details/gt2qqmtzimk.html

[H08] 获取错误信息与堆栈
来源：http://dali.yongpay.top/Article/details/gt2dvelzxnv.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.guowangkeji.top/Article/details/gt2epkzekae.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yuanzhike.top/Article/details/gt2pijhhrpn.html

JS:   e.message;  e.stack
来源：http://dali.sysykeji.top/Article/details/gt2jtlmpldg.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.cashguo.top/Article/details/gt2amnrzuhi.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hammf.cn/Article/details/gt2grnipxdm.html

Go:   err.Error()
来源：http://dali.zhiwuduotai.top/Article/details/gt2gedbqfml.html

Ruby: e.message;  e.backtrace
来源：http://dali.chenzaomai.com/Article/details/gt2bmolapgz.html

C#:   e.Message;  e.StackTrace
来源：http://dali.snrcjt.cn/Article/details/gt2ihbukdrd.html

[H09] 带错误码的异常
来源：http://dali.yvedp.cn/Article/details/gt2vcuyaxrv.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.redwolf501.top/Article/details/gt2ljzawevw.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.wangdashe.top/Article/details/gt2pxerhiop.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhoulong.xyz/Article/details/gt2qygmoyko.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.andypj.xyz/Article/details/gt2qybpnynk.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.andypj.xyz/Article/details/gt2mgpfotmg.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.c1oappe.top/Article/details/gt2umsgssiy.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.fzhhl.top/Article/details/gt2qzvhpqax.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.cheryme.top/Article/details/gt2vmmernzp.html

[H10] 资源自动释放
来源：http://dali.chenzaomai.com/Article/details/gt2xcupacvw.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.wangshuangyany.cn/Article/details/gt2bgahkbbc.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.dianchejie.cn/Article/details/gt2ldjctyet.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.dianchejie.cn/Article/details/gt2lyrvnlfv.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.wangshuangyany.cn/Article/details/gt2ojengtoa.html


<!-- 参考信息 -->