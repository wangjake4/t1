代发 wailian999

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pbiuazic.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jinqigfzy.top/Article/details/gt2qlddsenw.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.316326.xyz/Article/details/gt2checxgoz.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jqgufenzy.top/Article/details/gt2idqgqkpv.html

[F05] 判断文件或目录是否存在
来源：http://dali.jinqigfzy.top/Article/details/gt2dptupzwr.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.guowangkeji.top/Article/details/gt2wiexavww.html

PHP:  file_exists("a.txt");
来源：http://dali.havefunace.top/Article/details/gt2lcfxqqra.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yj20258.top/Article/details/gt2brjfhocp.html

TS:   fs.existsSync("a.txt")
来源：http://dali.xziqi.cn/Article/details/gt2txlkdmwc.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gtbyfaum.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.smart0.xyz/Article/details/gt2eugcesdi.html

Ruby: File.exist?("a.txt")
来源：http://dali.meibo888.top/Article/details/gt2ehpmicad.html

C#:   File.Exists("a.txt")
来源：http://dali.xziqi.cn/Article/details/gt2bpjvcmjr.html

[F06] 删除文件
来源：http://dali.shzxlz.cn/Article/details/gt2qffqzbru.html

Py:   os.remove("a.txt")
来源：http://dali.xuanzx.com/Article/details/gt2abmguhhu.html

PHP:  unlink("a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gt2vncgzcsm.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2ahextcrz.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oiepfdwk.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.pengpengdd.cyou/Article/details/gt2ajdytiso.html

Go:   os.Remove("a.txt")
来源：http://dali.bjfxy.top/Article/details/gt2cajnkeub.html

Ruby: File.delete("a.txt")
来源：http://dali.xziqi.cn/Article/details/gt2aoyxkgxg.html

C#:   File.Delete("a.txt");
来源：http://dali.smart0.xyz/Article/details/gt2tdrtsrce.html

[F07] 创建目录（含多级）
来源：http://dali.zycfv.cn/Article/details/gt2zyucdpih.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jianghu66.top/Article/details/gt2eemrhpvj.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yangfankeji.com/Article/details/gt2ymyxbzty.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hnqzz.top/Article/details/gt2nxiiqggi.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yvedp.cn/Article/details/gt2qqdgcogz.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.shzxlz.cn/Article/details/gt2yhmdnzzy.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.aibaodan.cn/Article/details/gt2vakcpiza.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.chenzaomai.com/Article/details/gt2yahjdsui.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.meibo888.top/Article/details/gt2mtclxnpb.html

[F08] 遍历目录
来源：http://dali.chenlongwang.top/Article/details/gt2lqdzzivl.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yongpay.top/Article/details/gt2xkvkjvbt.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.daria6918.cn/Article/details/gt2zfgzrevm.html

JS:   fs.readdirSync("dir")
来源：http://dali.tanke756.top/Article/details/gt2zdrieypy.html

TS:   fs.readdirSync("dir")
来源：http://dali.cqqwz.cn/Article/details/gt2jzwalfdv.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.smart0.xyz/Article/details/gt2izggisto.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.0kj1m.cn/Article/details/gt2ehzqzsxq.html

Ruby: Dir.children("dir")
来源：http://dali.9152youxi.cn/Article/details/gt2zwnzdiok.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jinqigfzy.top/Article/details/gt2ugxygjlq.html

[F09] 获取文件大小
来源：http://dali.aibaodan.cn/Article/details/gt2gbztqfse.html

Py:   os.path.getsize("a.txt")
来源：http://dali.tanke756.top/Article/details/gt2repnrvxq.html

PHP:  filesize("a.txt");
来源：http://dali.cdnleiting.top/Article/details/gt2afvtrhab.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jqgfzy.top/Article/details/gt2rycwnnyn.html

TS:   fs.statSync("a.txt").size
来源：http://dali.feifeiyinyue.top/Article/details/gt2eqoqcfln.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yj20258888.top/Article/details/gt2wyuixdrf.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.quarkkingdee.top/Article/details/gt2qagxhfpm.html

Ruby: File.size("a.txt")
来源：http://dali.cheryme.top/Article/details/gt2rhyskmbw.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.hysaishi.cn/Article/details/gt2ddmuowyh.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.tian-w.cn/Article/details/gt2vjdfmxxe.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.shzxlz.cn/Article/details/gt2bkgxiesb.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.sweek.top/Article/details/gt2qcqgzsyl.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2skppdfuq.html

TS:   path.extname("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2wmppjmsr.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.iojbl.cn/Article/details/gt2lvpsqefw.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2zfgcvikz.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.birdmap.top/Article/details/gt2kfdunsrz.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gt2shrekxqs.html

[F11] 复制与移动文件
来源：http://dali.kuanghao11.cn/Article/details/gt2scfzyubn.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gt2pcgbsvei.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.guannengcc.top/Article/details/gt2wbzxeevb.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2mrtacryp.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2qciixdrb.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jianghu66.top/Article/details/gt2eliwcvnh.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ybcxt.top/Article/details/gt2vhrbtuiw.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.ivvv.top/Article/details/gt2vjlfaazt.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.redwolf501.top/Article/details/gt2acnfwttp.html

[F12] CSV 读写
来源：http://dali.nanxinkj.top/Article/details/gt2fultovgm.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jinqigufen.top/Article/details/gt2oltysxnd.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.xuanzx.com/Article/details/gt2qulyawnh.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jinqigfzy.top/Article/details/gt2plkxqkqs.html

TS:   // 同上
来源：http://dali.316326.xyz/Article/details/gt2yucjoxng.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gakzgnhl.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.aibaodan.cn/Article/details/gt2txmmzble.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2spunmsov.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2njjxliec.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2dooyaufg.html

G. 面向对象
来源：http://dali.jianghu66.top/Article/details/gt2qwppykcw.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2awqrekqz.html

[G01] 定义类
来源：http://dali.guannengcc.top/Article/details/gt2zufvgswd.html

Py:   class User: pass
来源：http://dali.tian-w.cn/Article/details/gt2leyvaxeq.html

PHP:  class User {}
来源：http://dali.nanxuanxn.top/Article/details/gt2pxdadkuz.html

JS:   class User {}
来源：http://dali.fzhhl.top/Article/details/gt2jtemnqzm.html

TS:   class User { name: string = ""; }
来源：http://dali.sxryk.cn/Article/details/gt2iccyqbfx.html

Java: class User {}
来源：http://dali.xinyue.icu/Article/details/gt2oyzllkyj.html

Go:   type User struct { Name string }
来源：http://dali.shuidangran.top/Article/details/gt2vfvmwvgf.html

Ruby: class User; end
来源：http://dali.vqdsnc.cn/Article/details/gt2ztluvtll.html

C#:   class User {}
来源：http://dali.ppjwa.cn/Article/details/gt2vxiqzook.html

[G02] 构造函数
来源：http://dali.vqdsnc.cn/Article/details/gt2qxsftakc.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.ydzc1.top/Article/details/gt2evypafkk.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.c1oappe.top/Article/details/gt2nthqetna.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ybcxt.top/Article/details/gt2tyhuatzl.html

TS:   constructor(public name: string) {}
来源：http://dali.jinqigfzy.top/Article/details/gt2wniygmyw.html

Java: User(String name) { this.name = name; }
来源：http://dali.dashuyun.cn/Article/details/gt2sfncnkqz.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhengqikj.top/Article/details/gt2phsfbfoj.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zanunwnd.html

C#:   public User(string name) { Name = name; }
来源：http://dali.aibaodan.cn/Article/details/gt2jiogolmt.html

[G03] 实例属性
来源：http://dali.cheryme.top/Article/details/gt2nhgkffki.html

Py:   self.name = "x"
来源：http://dali.meibo888.top/Article/details/gt2kzyvawjk.html

PHP:  public string $name = "x";
来源：http://dali.snrcjt.cn/Article/details/gt2cioxdary.html

JS:   this.name = "x";
来源：http://dali.yj20258.top/Article/details/gt2garhqmqx.html

TS:   name: string = "x";
来源：http://dali.jqgufenzy.top/Article/details/gt2ynbnuqim.html

Java: private String name;
来源：http://dali.hammf.cn/Article/details/gt2maurmxqo.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.xylfe.cn/Article/details/gt2pbpttscw.html

Ruby: @name = "x"
来源：http://dali.cashguo.top/Article/details/gt2vgovmvap.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.vqdsnc.cn/Article/details/gt2wnczlkfk.html

[G04] 定义方法
来源：http://dali.hywenlv.cn/Article/details/gt2wnizofdy.html

Py:   def greet(self): return self.name
来源：http://dali.ydzc1.top/Article/details/gt2vkxncrqd.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.gaohongyu789.top/Article/details/gt2lnbdprtx.html

JS:   greet() { return this.name; }
来源：http://dali.tian-w.cn/Article/details/gt2jqgofaig.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhoulong.xyz/Article/details/gt2cqaoyhwo.html

Java: String greet() { return name; }
来源：http://dali.xuanzx.com/Article/details/gt2bwrfcnkd.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yvedp.cn/Article/details/gt2qlrqcgrw.html

Ruby: def greet; @name; end
来源：http://dali.hnqzz.top/Article/details/gt2mdixzwgv.html

C#:   public string Greet() => Name;
来源：http://dali.chenzaomai.com/Article/details/gt2hdxejlor.html

[G05] 继承
来源：http://dali.tanke756.top/Article/details/gt2cbimfkum.html

Py:   class Admin(User): pass
来源：http://dali.tanke756.top/Article/details/gt2blkktxdz.html

PHP:  class Admin extends User {}
来源：http://dali.yongpay.top/Article/details/gt2lqvqpfyg.html

JS:   class Admin extends User {}
来源：http://dali.guowangkeji.top/Article/details/gt2alfqzhyq.html

TS:   class Admin extends User {}
来源：http://dali.jinqigfzy.top/Article/details/gt2qzclkokc.html

Java: class Admin extends User {}
来源：http://dali.yueranfly.top/Article/details/gt2pwgxqafm.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.sysykeji.top/Article/details/gt2pcibpvzf.html

Ruby: class Admin < User; end
来源：http://dali.c1oappe.top/Article/details/gt2bozpqxim.html

C#:   class Admin : User {}
来源：http://dali.aibaodan.cn/Article/details/gt2ngnouvps.html

[G06] 重写方法
来源：http://dali.zycfv.cn/Article/details/gt2gmtvyrwz.html

Py:   def greet(self): return "admin"
来源：http://dali.yonumen.top/Article/details/gt2pscoyqel.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zycfv.cn/Article/details/gt2akevlsnj.html

JS:   greet() { return "admin"; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2lbpnlbmo.html

TS:   greet(): string { return "admin"; }
来源：http://dali.ppjwa.cn/Article/details/gt2tzmfpzhh.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.gogol.net.cn/Article/details/gt2qivabjes.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yj20258888.top/Article/details/gt2fhnqwepl.html

Ruby: def greet; "admin"; end
来源：http://dali.yueranfly.top/Article/details/gt2fkdmtarm.html

C#:   public override string Greet() => "admin";
来源：http://dali.yuanzhike.top/Article/details/gt2tmhpdqho.html

[G07] 调用父类方法
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xfzfopst.html

Py:   super().greet()
来源：http://dali.ydzc1.top/Article/details/gt2ogldbvkn.html

PHP:  parent::greet();
来源：http://dali.ybcxt.top/Article/details/gt2phnwlntm.html

JS:   super.greet();
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xbqfboxu.html

TS:   super.greet();
来源：http://dali.shzxlz.cn/Article/details/gt2djboctin.html

Java: super.greet();
来源：http://dali.mhx1999.top/Article/details/gt2flwuvphv.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhengqikj.top/Article/details/gt2qoowbiag.html

Ruby: super
来源：http://dali.zhengqikj.top/Article/details/gt2wxeblome.html

C#:   base.Greet();
来源：http://dali.jinqigfzy.top/Article/details/gt2qkdaqjwj.html

[G08] 静态方法与属性
来源：http://dali.wangdashe.top/Article/details/gt2zqkjwgsw.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.ivvv.top/Article/details/gt2lnmrpizl.html

PHP:  public static function f() {}
来源：http://dali.meibo888.top/Article/details/gt2ixbddpnp.html

JS:   static f() {}
来源：http://dali.svipenyu.cn/Article/details/gt2hzsfepwq.html

TS:   static f(): void {}
来源：http://dali.hysaishi.cn/Article/details/gt2eymwlece.html

Java: static void f() {}
来源：http://dali.jqgufenzy.top/Article/details/gt2wxkgescx.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jiagoushi.top/Article/details/gt2ldwkkbzg.html

Ruby: def self.f; end
来源：http://dali.haohaochexian.top/Article/details/gt2moyrfpga.html

C#:   public static void F() {}
来源：http://dali.gaohongyu789.top/Article/details/gt2ydttmysn.html

[G09] 接口 / 抽象类
来源：http://dali.pengpengdd.cyou/Article/details/gt2fjanaets.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.c1oappe.top/Article/details/gt2vabyumgn.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.shuidangran.top/Article/details/gt2kenbinvr.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jlsjyb.cn/Article/details/gt2dwxctxlv.html

TS:   interface Shape { area(): number; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2mummceso.html

Java: interface Shape { double area(); }
来源：http://dali.hnqzz.top/Article/details/gt2gqewlbsn.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.haohaochexian.top/Article/details/gt2dsochkzo.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.meibo888.top/Article/details/gt2hcitbyzf.html

C#:   interface IShape { double Area(); }
来源：http://dali.sysykeji.top/Article/details/gt2aqnavjof.html

[G10] 访问控制
来源：http://dali.sufxvd.cn/Article/details/gt2ohaqmorn.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.cheryme.top/Article/details/gt2gzqcmnbl.html

PHP:  public / protected / private
来源：http://dali.nwbrower.top/Article/details/gt2cuvinnax.html

JS:   #private 字段；其余公开
来源：http://dali.yj20258.top/Article/details/gt2ocdztbqz.html

TS:   public / protected / private
来源：http://dali.sufxvd.cn/Article/details/gt2efivecic.html

Java: public / protected / private / 默认包级
来源：http://dali.redwolf501.top/Article/details/gt2utmrhshm.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xuetiantiany.cn/Article/details/gt2dsdllyxb.html

Ruby: public / protected / private
来源：http://dali.tian-w.cn/Article/details/gt2umufjxux.html

C#:   public / protected / private / internal
来源：http://dali.dashuyun.cn/Article/details/gt2wppxaxpm.html

[G11] getter / setter
来源：http://dali.jiagoushi.top/Article/details/gt2lgtsddmm.html

Py:   @property 与 @x.setter
来源：http://dali.nanxinkj.top/Article/details/gt2tpupqvcb.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.smart0.xyz/Article/details/gt2dcqofocf.html

JS:   get name() { return this._name; }
来源：http://dali.jyoumei.cn/Article/details/gt2tovjqgcc.html

TS:   get name(): string { return this._name; }
来源：http://dali.vqdsnc.cn/Article/details/gt2eqybhfgo.html

Java: public String getName() { return name; }
来源：http://dali.fengsongda.top/Article/details/gt2nwubmwmn.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jyoumei.cn/Article/details/gt2cwwvevez.html

Ruby: attr_accessor :name
来源：http://dali.zdqjudy.top/Article/details/gt2qmdtlfza.html

C#:   public string Name { get; set; }
来源：http://dali.xinyue.icu/Article/details/gt2ccoqykad.html

[G12] 对象转字符串
来源：http://dali.guowangkeji.top/Article/details/gt2nmjfnrym.html

Py:   def __str__(self): return self.name
来源：http://dali.sxryk.cn/Article/details/gt2xcihcqsd.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yuanzhike.top/Article/details/gt2iovddtkc.html

JS:   toString() { return this.name; }
来源：http://dali.9152youxi.cn/Article/details/gt2hqdwnqtp.html

TS:   toString(): string { return this.name; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2dtspuhyx.html

Java: @Override public String toString() { return name; }
来源：http://dali.sweek.top/Article/details/gt2kpfdziln.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.mhx1999.top/Article/details/gt2qzgblpwb.html

Ruby: def to_s; @name; end
来源：http://dali.yj20258.top/Article/details/gt2tthhfafx.html

C#:   public override string ToString() => Name;
来源：http://dali.feifeiyinyue.top/Article/details/gt2ceibbwch.html

[G13] 判断对象类型
来源：http://dali.cheryme.top/Article/details/gt2ggueiziz.html

Py:   isinstance(u, User)
来源：http://dali.chenzaomai.com/Article/details/gt2ylpmsowh.html

PHP:  $u instanceof User
来源：http://dali.9152youxi.cn/Article/details/gt2ypmcguop.html

JS:   u instanceof User
来源：http://dali.cdnleiting.top/Article/details/gt2wzkhoswh.html

TS:   u instanceof User
来源：http://dali.yj20258.top/Article/details/gt2kjbilcpr.html

Java: u instanceof User
来源：http://dali.hammf.cn/Article/details/gt2enshzlov.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.xinyue.icu/Article/details/gt2twlvnszw.html

Ruby: u.is_a?(User)
来源：http://dali.xuanzx.com/Article/details/gt2izfmrjtu.html

C#:   u is User
来源：http://dali.meibo888.top/Article/details/gt2fnqhgkqw.html

[G14] 数据类 / record
来源：http://dali.ppjwa.cn/Article/details/gt2immlyvqk.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhongyouzk.top/Article/details/gt2vchszlbh.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.tian-w.cn/Article/details/gt2jgcddpss.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.meibo888.top/Article/details/gt2dqtzyuox.html

TS:   type User = { name: string; age: number };
来源：http://dali.aibaodan.cn/Article/details/gt2uukabtrm.html

Java: record User(String name, int age) {}
来源：http://dali.ybcxt.top/Article/details/gt2zapfsvti.html

Go:   type User struct { Name string; Age int }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xhgllhdc.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.chenzaomai.com/Article/details/gt2xckwisoe.html

C#:   record User(string Name, int Age);
来源：http://dali.aizwys.cn/Article/details/gt2sxojvhde.html

[G15] 枚举
来源：http://dali.yj20258888.top/Article/details/gt2jaepqqkx.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.tianlin.xyz/Article/details/gt2oxavevxe.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yj20258888.top/Article/details/gt2cniulqeu.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yuanzhike.top/Article/details/gt2qmchaglm.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jianghu66.top/Article/details/gt2cifisjvz.html

Java: enum Color { RED, GREEN }
来源：http://dali.fengsongda.top/Article/details/gt2laieijyx.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.haohaochexian.top/Article/details/gt2amdxqrkd.html

Ruby: Color = %i[red green].freeze
来源：http://dali.hnxiangtu.top/Article/details/gt2swiiyqkr.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.nwbrower.top/Article/details/gt2aoqawnjp.html

[G16] 对象转数组 / 字典
来源：http://dali.jinqigfzy.top/Article/details/gt2pqefxbip.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.xylfe.cn/Article/details/gt2gugjrict.html

PHP:  get_object_vars($obj);
来源：http://dali.xuetiantiany.cn/Article/details/gt2ajwdamei.html

JS:   Object.entries(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ikoiusde.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2xuxmjqon.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jyoumei.cn/Article/details/gt2rshiehcy.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yj20258.top/Article/details/gt2emdmykgr.html

Ruby: obj.instance_variables
来源：http://dali.hnqzz.top/Article/details/gt2zugipjod.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yuxming.cn/Article/details/gt2twqujkdh.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2gvonklyf.html

H. 异常与错误处理
来源：http://dali.sufxvd.cn/Article/details/gt2qkmzeoom.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2ncjcwtqq.html

[H01] try / catch 基础
来源：http://dali.aizwys.cn/Article/details/gt2xjpavxfm.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zdqjudy.top/Article/details/gt2lfuybpey.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.chenlongwang.top/Article/details/gt2skipcntj.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.meibo888.top/Article/details/gt2vigkattq.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.gaohongyu789.top/Article/details/gt2rqohwtxz.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.cashguo.top/Article/details/gt2yyntlbtp.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.cashguo.top/Article/details/gt2adwhjftv.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.xuanzx.com/Article/details/gt2gonqjoyd.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2rocfwmdw.html

[H02] finally / ensure 收尾
来源：http://dali.xinyue.icu/Article/details/gt2usteugdy.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jlsjyb.cn/Article/details/gt2oueytzfi.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.tianlin.xyz/Article/details/gt2emauuaqw.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.hfpthk.cn/Article/details/gt2bohybyhe.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hysaishi.cn/Article/details/gt2xdyosthp.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jqgfzy.top/Article/details/gt2yetaycxm.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yongpay.top/Article/details/gt2wzxlmrdm.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.daxiang520.top/Article/details/gt2fwcpbtad.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.ydzc1.top/Article/details/gt2ujlqzghe.html

[H03] 主动抛出异常
来源：http://dali.hfpthk.cn/Article/details/gt2hibinkqh.html

Py:   raise ValueError("错误信息")
来源：http://dali.hfpthk.cn/Article/details/gt2aoppppyb.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.daria6918.cn/Article/details/gt2djhjclcq.html

JS:   throw new Error("错误信息");
来源：http://dali.aibaodan.cn/Article/details/gt2gygkjpcb.html

TS:   throw new Error("错误信息");
来源：http://dali.tianlin.xyz/Article/details/gt2jqjchgso.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.ydzc1.top/Article/details/gt2izynfqnm.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.mhx1999.top/Article/details/gt2zjaaevnr.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jinqigfzy.top/Article/details/gt2rknauuej.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.daria6918.cn/Article/details/gt2jzqgdiad.html

[H04] 自定义异常类型
来源：http://dali.chenzaomai.com/Article/details/gt2iovwqyft.html

Py:   class MyError(Exception): pass
来源：http://dali.sysykeji.top/Article/details/gt2ljzdzwnb.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.shzxlz.cn/Article/details/gt2czrhhbaj.html

JS:   class MyError extends Error {}
来源：http://dali.xylfe.cn/Article/details/gt2zkshhaux.html

TS:   class MyError extends Error {}
来源：http://dali.kuanghao11.cn/Article/details/gt2dnyplvey.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhoulong.xyz/Article/details/gt2pphwlcqx.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ydzc1.top/Article/details/gt2kvygcmtf.html

Ruby: class MyError < StandardError; end
来源：http://dali.gotoacloud.top/Article/details/gt2mgyttcot.html

C#:   class MyException : Exception {}
来源：http://dali.jqgfzy.top/Article/details/gt2ksttyfpd.html

[H05] 捕获特定类型
来源：http://dali.ybcxt.top/Article/details/gt2liroqgoe.html

Py:   except ValueError as e:
来源：http://dali.shangyingyoupin.top/Article/details/gt2bnaubmao.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.316326.xyz/Article/details/gt2ckdabxrn.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.nanxinkj.top/Article/details/gt2rvzdzfty.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.fengsongda.top/Article/details/gt2oqzbhbrn.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.ybcxt.top/Article/details/gt2rawezjwh.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.gotoacloud.top/Article/details/gt2szsdeicn.html

Ruby: rescue ArgumentError => e
来源：http://dali.pycfn.com/Article/details/gt2pgkopafu.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jiagoushi.top/Article/details/gt2bpxwxbhv.html

[H06] 可选值 / 空值安全访问
来源：http://dali.sweek.top/Article/details/gt2ghgaylcc.html

Py:   value = d.get("k") or default
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yadtilsq.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yangfankeji.com/Article/details/gt2raqcvtgr.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.chenzaomai.com/Article/details/gt2aynzzmtf.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hywenlv.cn/Article/details/gt2immdwlrr.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhongyouzk.top/Article/details/gt2qzouyfic.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.ydzc1.top/Article/details/gt2nbfudbya.html

Ruby: d&.dig(:a, :b)
来源：http://dali.shangyingyoupin.top/Article/details/gt2obxexsce.html

C#:   obj?.A?.B ?? default
来源：http://dali.dianchejie.cn/Article/details/gt2lnoexbvn.html

[H07] 断言
来源：http://dali.fzhhl.top/Article/details/gt2zuafiyff.html

Py:   assert x > 0, "必须为正"
来源：http://dali.smart0.xyz/Article/details/gt2ydhyzygg.html

PHP:  assert($x > 0);
来源：http://dali.guowangkeji.top/Article/details/gt2owyexwzo.html

JS:   console.assert(x > 0);
来源：http://dali.jqgufenzy.top/Article/details/gt2xdbdnvac.html

TS:   console.assert(x > 0);
来源：http://dali.hammf.cn/Article/details/gt2shoqptbl.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jqgfzy.top/Article/details/gt2wwdbeqpi.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.pengpengdd.cyou/Article/details/gt2bxwwhvrl.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.snrcjt.cn/Article/details/gt2mwppnwxw.html

C#:   Debug.Assert(x > 0);
来源：http://dali.xziqi.cn/Article/details/gt2shbjbsyx.html

[H08] 获取错误信息与堆栈
来源：http://dali.cashguo.top/Article/details/gt2gwcsblkf.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gt2fsgjoqta.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhixingplan.top/Article/details/gt2ahwbbgjp.html

JS:   e.message;  e.stack
来源：http://dali.shzxlz.cn/Article/details/gt2rejpukgs.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.tanke756.top/Article/details/gt2xnjfrtro.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.gotoacloud.top/Article/details/gt2qvwgnctp.html

Go:   err.Error()
来源：http://dali.snrcjt.cn/Article/details/gt2dhooaogn.html

Ruby: e.message;  e.backtrace
来源：http://dali.xylfe.cn/Article/details/gt2wgzblfaw.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jinghuilouyu.cn/Article/details/gt2durdused.html

[H09] 带错误码的异常
来源：http://dali.andypj.xyz/Article/details/gt2rmiaqxqc.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.ehwqpu.com/Article/details/gt2zistnnnf.html


<!-- 参考信息 -->