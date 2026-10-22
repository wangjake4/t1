代发 wailian999

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.ybcxt.top/Article/details/gt2qojqkksu.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yangfankeji.com/Article/details/gt2xieuxzbv.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ehwqpu.com/Article/details/gt2leyytspd.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.hysaishi.cn/Article/details/gt2impnobfz.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.hnxiangtu.top/Article/details/gt2tkcqxbhz.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.shzxlz.cn/Article/details/gt2mmziwpqp.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jlsjyb.cn/Article/details/gt2vntigqho.html

[F04] 追加写入文件
来源：http://dali.nanxuanxn.top/Article/details/gt2scmqbyji.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.fzhhl.top/Article/details/gt2mppoztgy.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.tianlin.xyz/Article/details/gt2smqnwtgu.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yongpay.top/Article/details/gt2nezpghfo.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ivvv.top/Article/details/gt2bwytleao.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.shuidangran.top/Article/details/gt2kfpjnywg.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.cheryme.top/Article/details/gt2giucmqft.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yj20258888.top/Article/details/gt2rtylztrb.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.hfpthk.cn/Article/details/gt2kwyvhzvk.html

[F05] 判断文件或目录是否存在
来源：http://dali.smart0.xyz/Article/details/gt2inuczpws.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.fengsongda.top/Article/details/gt2dwbdpkib.html

PHP:  file_exists("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gt2smhvahgo.html

JS:   fs.existsSync("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2cquotfep.html

TS:   fs.existsSync("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2bbuxkrjq.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhengqikj.top/Article/details/gt2tghttqtv.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yvedp.cn/Article/details/gt2phkitiry.html

Ruby: File.exist?("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gt2xbxxiybl.html

C#:   File.Exists("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2fbicffmz.html

[F06] 删除文件
来源：http://dali.chenlongwang.top/Article/details/gt2ekalvqkq.html

Py:   os.remove("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gt2zxpqkzur.html

PHP:  unlink("a.txt");
来源：http://dali.zycfv.cn/Article/details/gt2sadgbfvq.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2ercqdxhx.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gt2papjawwq.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jianghu66.top/Article/details/gt2pvlcbury.html

Go:   os.Remove("a.txt")
来源：http://dali.ydzc1.top/Article/details/gt2yqiirjwj.html

Ruby: File.delete("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2wzifebza.html

C#:   File.Delete("a.txt");
来源：http://dali.cucudq.cn/Article/details/gt2kixzeuok.html

[F07] 创建目录（含多级）
来源：http://dali.chenjidiqi.icu/Article/details/gt2vlsubyor.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zdqjudy.top/Article/details/gt2ulrfkwns.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.vqdsnc.cn/Article/details/gt2byrsrhjz.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ppjwa.cn/Article/details/gt2wytyhjxm.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.meibo888.top/Article/details/gt2vwdlewml.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.wangshuangyany.cn/Article/details/gt2ptqldphl.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yonumen.top/Article/details/gt2cffqwnml.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.wangdashe.top/Article/details/gt2yxuqpavq.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.dianchejie.cn/Article/details/gt2ejmryujw.html

[F08] 遍历目录
来源：http://dali.cucudq.cn/Article/details/gt2kdervrkg.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.dashuyun.cn/Article/details/gt2xakeienw.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhongyouzk.top/Article/details/gt2zsjjidkp.html

JS:   fs.readdirSync("dir")
来源：http://dali.gaohongyu789.top/Article/details/gt2kkdmpftw.html

TS:   fs.readdirSync("dir")
来源：http://dali.jinqigufen.top/Article/details/gt2zrxcfsvz.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhixingplan.top/Article/details/gt2dzquzzbc.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yj20258.top/Article/details/gt2jnxeyglv.html

Ruby: Dir.children("dir")
来源：http://dali.yuxming.cn/Article/details/gt2pfsgegwp.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yuxming.cn/Article/details/gt2mfvjgzpt.html

[F09] 获取文件大小
来源：http://dali.daxiang520.top/Article/details/gt2phypmxrb.html

Py:   os.path.getsize("a.txt")
来源：http://dali.316326.xyz/Article/details/gt2lmuflpvp.html

PHP:  filesize("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gt2ftpijpdl.html

JS:   fs.statSync("a.txt").size
来源：http://dali.daxiang520.top/Article/details/gt2jvljppfb.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jianghu66.top/Article/details/gt2nrdxwjwx.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.pengpengdd.cyou/Article/details/gt2rilahoct.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.nwbrower.top/Article/details/gt2zuujlrho.html

Ruby: File.size("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gt2tjsaennf.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.cheryme.top/Article/details/gt2mwplhbkr.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.sxryk.cn/Article/details/gt2eqfxnaej.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aemrweyk.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jyoumei.cn/Article/details/gt2jhwdkjwb.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yuxming.cn/Article/details/gt2hjgqtmyt.html

TS:   path.extname("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2sekmiczt.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.nwbrower.top/Article/details/gt2faxlekqb.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.hnqzz.top/Article/details/gt2jutigbzp.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2casjdoqk.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gt2acrqzmye.html

[F11] 复制与移动文件
来源：http://dali.yanxiufei.cn/Article/details/gt2goldijgy.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zycfv.cn/Article/details/gt2zfkxezac.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.ybcxt.top/Article/details/gt2gkrhawub.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2jpyfatmw.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hnqzz.top/Article/details/gt2hrjfrnio.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.hammf.cn/Article/details/gt2ikqzkgxw.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.birdmap.top/Article/details/gt2shqkesmw.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.cucudq.cn/Article/details/gt2auasipbh.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.fzhhl.top/Article/details/gt2zspsfkpr.html

[F12] CSV 读写
来源：http://dali.kuanghao11.cn/Article/details/gt2ahzukveh.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.sysykeji.top/Article/details/gt2vtzxvdeq.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.guannengcc.top/Article/details/gt2uoyyqlfx.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yvedp.cn/Article/details/gt2tlheotqy.html

TS:   // 同上
来源：http://dali.cqqwz.cn/Article/details/gt2gsbisgmt.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.dianchejie.cn/Article/details/gt2delabpnd.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.316326.xyz/Article/details/gt2vgpchxiu.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.iojbl.cn/Article/details/gt2mpckfvrz.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jyoumei.cn/Article/details/gt2zlujdmvk.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2dikoymtd.html

G. 面向对象
来源：http://dali.yuanzhike.top/Article/details/gt2qngcpzzo.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2wcxagars.html

[G01] 定义类
来源：http://dali.ehwqpu.com/Article/details/gt2yikzuico.html

Py:   class User: pass
来源：http://dali.gotoacloud.top/Article/details/gt2gwmcmwmy.html

PHP:  class User {}
来源：http://dali.yonumen.top/Article/details/gt2nithfwmk.html

JS:   class User {}
来源：http://dali.gotoacloud.top/Article/details/gt2nsbncewg.html

TS:   class User { name: string = ""; }
来源：http://dali.gzhubu.top/Article/details/gt2mlecjvoc.html

Java: class User {}
来源：http://dali.shzxlz.cn/Article/details/gt2ogygifkm.html

Go:   type User struct { Name string }
来源：http://dali.zhiwuduotai.top/Article/details/gt2xezmdrzl.html

Ruby: class User; end
来源：http://dali.yj20258888.top/Article/details/gt2zgpzmdgb.html

C#:   class User {}
来源：http://dali.hywenlv.cn/Article/details/gt2pfcqfdjc.html

[G02] 构造函数
来源：http://dali.gaohongyu789.top/Article/details/gt2riztsowa.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.gogol.net.cn/Article/details/gt2drswnonu.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jlsjyb.cn/Article/details/gt2zkgmcgpn.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhixingplan.top/Article/details/gt2dtapxram.html

TS:   constructor(public name: string) {}
来源：http://dali.daria6918.cn/Article/details/gt2qirfjwlm.html

Java: User(String name) { this.name = name; }
来源：http://dali.gogol.net.cn/Article/details/gt2qgjeypxj.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.gaohongyu789.top/Article/details/gt2mibabxnr.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hongshengwenyu.top/Article/details/gt2nuzjbakz.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhongyouzk.top/Article/details/gt2wddkeoba.html

[G03] 实例属性
来源：http://dali.jqgfzy.top/Article/details/gt2maaqewtw.html

Py:   self.name = "x"
来源：http://dali.yj20258888.top/Article/details/gt2gmteoyyl.html

PHP:  public string $name = "x";
来源：http://dali.sufxvd.cn/Article/details/gt2tijbqeir.html

JS:   this.name = "x";
来源：http://dali.yj20258.top/Article/details/gt2cmalwllp.html

TS:   name: string = "x";
来源：http://dali.ppjwa.cn/Article/details/gt2zbmwpdlj.html

Java: private String name;
来源：http://dali.mhx1999.top/Article/details/gt2kvmmjlnl.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.ppjwa.cn/Article/details/gt2zwnyjisk.html

Ruby: @name = "x"
来源：http://dali.jyoumei.cn/Article/details/gt2vcaajoit.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zdqjudy.top/Article/details/gt2yxlutprf.html

[G04] 定义方法
来源：http://dali.tianlin.xyz/Article/details/gt2qypryifa.html

Py:   def greet(self): return self.name
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gskuexwl.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.gzhubu.top/Article/details/gt2evfhxqsv.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rqydaawg.html

TS:   greet(): string { return this.name; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2ntcmddze.html

Java: String greet() { return name; }
来源：http://dali.sufxvd.cn/Article/details/gt2rarwujuq.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jianghu66.top/Article/details/gt2klgnmvcl.html

Ruby: def greet; @name; end
来源：http://dali.c1oappe.top/Article/details/gt2auoimzhm.html

C#:   public string Greet() => Name;
来源：http://dali.aibaodan.cn/Article/details/gt2bjotwafj.html

[G05] 继承
来源：http://dali.mhx1999.top/Article/details/gt2fjvlguwd.html

Py:   class Admin(User): pass
来源：http://dali.snrcjt.cn/Article/details/gt2tcauysrh.html

PHP:  class Admin extends User {}
来源：http://dali.havefunace.top/Article/details/gt2soxjgdvp.html

JS:   class Admin extends User {}
来源：http://dali.sweek.top/Article/details/gt2chbwzuca.html

TS:   class Admin extends User {}
来源：http://dali.guowangkeji.top/Article/details/gt2ugbltcmw.html

Java: class Admin extends User {}
来源：http://dali.tanke756.top/Article/details/gt2cartvybb.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ehwqpu.com/Article/details/gt2kehjvlfj.html

Ruby: class Admin < User; end
来源：http://dali.aizwys.cn/Article/details/gt2dijmmlyf.html

C#:   class Admin : User {}
来源：http://dali.tanke756.top/Article/details/gt2cmbektep.html

[G06] 重写方法
来源：http://dali.meibo888.top/Article/details/gt2xjiprnnh.html

Py:   def greet(self): return "admin"
来源：http://dali.nwbrower.top/Article/details/gt2iavvprpm.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2bmrbekcu.html

JS:   greet() { return "admin"; }
来源：http://dali.jinqigufen.top/Article/details/gt2djedectb.html

TS:   greet(): string { return "admin"; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2olobslde.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.mhx1999.top/Article/details/gt2skesaagh.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.nanxuanxn.top/Article/details/gt2bxtonigg.html

Ruby: def greet; "admin"; end
来源：http://dali.guowangkeji.top/Article/details/gt2wzuqkrgp.html

C#:   public override string Greet() => "admin";
来源：http://dali.guowangkeji.top/Article/details/gt2hdcdvjuk.html

[G07] 调用父类方法
来源：http://dali.mhx1999.top/Article/details/gt2tfpzefua.html

Py:   super().greet()
来源：http://dali.cashguo.top/Article/details/gt2cxkubftn.html

PHP:  parent::greet();
来源：http://dali.shuidangran.top/Article/details/gt2qivarbgi.html

JS:   super.greet();
来源：http://dali.redwolf501.top/Article/details/gt2almfgbdr.html

TS:   super.greet();
来源：http://dali.daria6918.cn/Article/details/gt2xlvwvtsb.html

Java: super.greet();
来源：http://dali.nanxuanxn.top/Article/details/gt2bqfpsqif.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.xylfe.cn/Article/details/gt2yatkebqr.html

Ruby: super
来源：http://dali.guowangkeji.top/Article/details/gt2bpqzlvme.html

C#:   base.Greet();
来源：http://dali.gzhubu.top/Article/details/gt2kzpzfhoz.html

[G08] 静态方法与属性
来源：http://dali.dashuyun.cn/Article/details/gt2mwlmgshk.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.cheryme.top/Article/details/gt2ixtgphzf.html

PHP:  public static function f() {}
来源：http://dali.gogol.net.cn/Article/details/gt2cptfftag.html

JS:   static f() {}
来源：http://dali.ehwqpu.com/Article/details/gt2foprssow.html

TS:   static f(): void {}
来源：http://dali.yuanzhike.top/Article/details/gt2lzmbwgnr.html

Java: static void f() {}
来源：http://dali.ybcxt.top/Article/details/gt2gdchaegr.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hammf.cn/Article/details/gt2hwlpzebt.html

Ruby: def self.f; end
来源：http://dali.ppjwa.cn/Article/details/gt2ebrtghnb.html

C#:   public static void F() {}
来源：http://dali.zhoulong.xyz/Article/details/gt2ljhevejj.html

[G09] 接口 / 抽象类
来源：http://dali.yuanzhike.top/Article/details/gt2uujpjftt.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.xylfe.cn/Article/details/gt2rgdbyjya.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.chenlongwang.top/Article/details/gt2tkwrsedn.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.aizwys.cn/Article/details/gt2gdxzykeo.html

TS:   interface Shape { area(): number; }
来源：http://dali.aibaodan.cn/Article/details/gt2kdttwimv.html

Java: interface Shape { double area(); }
来源：http://dali.andypj.xyz/Article/details/gt2sdhgultr.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.xziqi.cn/Article/details/gt2lceummjj.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yj202588.top/Article/details/gt2ikcbgvha.html

C#:   interface IShape { double Area(); }
来源：http://dali.gogol.net.cn/Article/details/gt2qlqcrjqh.html

[G10] 访问控制
来源：http://dali.hammf.cn/Article/details/gt2mkudycwb.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2odhjantr.html

PHP:  public / protected / private
来源：http://dali.tianlin.xyz/Article/details/gt2xptifhce.html

JS:   #private 字段；其余公开
来源：http://dali.cqqwz.cn/Article/details/gt2lwqcpfmt.html

TS:   public / protected / private
来源：http://dali.ivvv.top/Article/details/gt2psazkfmv.html

Java: public / protected / private / 默认包级
来源：http://dali.wangshuangyany.cn/Article/details/gt2bdxoweup.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hywenlv.cn/Article/details/gt2nhcoavzb.html

Ruby: public / protected / private
来源：http://dali.bjfxy.top/Article/details/gt2lmhqvxpr.html

C#:   public / protected / private / internal
来源：http://dali.nanxuanxn.top/Article/details/gt2uhncdnhn.html

[G11] getter / setter
来源：http://dali.quarkkingdee.top/Article/details/gt2mhmwuvdp.html

Py:   @property 与 @x.setter
来源：http://dali.sweek.top/Article/details/gt2krfapsmo.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.gaohongyu789.top/Article/details/gt2bwulpkik.html

JS:   get name() { return this._name; }
来源：http://dali.aizwys.cn/Article/details/gt2fvpltjza.html

TS:   get name(): string { return this._name; }
来源：http://dali.yuanzhike.top/Article/details/gt2owkxwtuz.html

Java: public String getName() { return name; }
来源：http://dali.zhoulong.xyz/Article/details/gt2rxwjavyn.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.wangshuangyany.cn/Article/details/gt2sgcedhrl.html

Ruby: attr_accessor :name
来源：http://dali.daxiang520.top/Article/details/gt2fscdhrkl.html

C#:   public string Name { get; set; }
来源：http://dali.hammf.cn/Article/details/gt2ozbvrmch.html

[G12] 对象转字符串
来源：http://dali.zhongyouzk.top/Article/details/gt2wcywtkjo.html

Py:   def __str__(self): return self.name
来源：http://dali.shuidangran.top/Article/details/gt2bdnxrsqt.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.kuanghao11.cn/Article/details/gt2bcmyqsfu.html

JS:   toString() { return this.name; }
来源：http://dali.yj20258888.top/Article/details/gt2igxjgcka.html

TS:   toString(): string { return this.name; }
来源：http://dali.tanke756.top/Article/details/gt2udzwllin.html

Java: @Override public String toString() { return name; }
来源：http://dali.svipenyu.cn/Article/details/gt2xepbducj.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jkltepeu.html

Ruby: def to_s; @name; end
来源：http://dali.zycfv.cn/Article/details/gt2ldzwyalh.html

C#:   public override string ToString() => Name;
来源：http://dali.jlsjyb.cn/Article/details/gt2vcvnipnv.html

[G13] 判断对象类型
来源：http://dali.ehwqpu.com/Article/details/gt2lohfbaby.html

Py:   isinstance(u, User)
来源：http://dali.yuanzhike.top/Article/details/gt2seposryv.html

PHP:  $u instanceof User
来源：http://dali.gaohongyu789.top/Article/details/gt2vfmabafx.html

JS:   u instanceof User
来源：http://dali.meibo888.top/Article/details/gt2kpubzuwc.html

TS:   u instanceof User
来源：http://dali.fengsongda.top/Article/details/gt2jrbhdmkk.html

Java: u instanceof User
来源：http://dali.vqdsnc.cn/Article/details/gt2mbpwylwz.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.9152youxi.cn/Article/details/gt2fxeonkwq.html

Ruby: u.is_a?(User)
来源：http://dali.hongshengwenyu.top/Article/details/gt2cxjnloqa.html

C#:   u is User
来源：http://dali.yonumen.top/Article/details/gt2gbpbbboa.html

[G14] 数据类 / record
来源：http://dali.zhoulong.xyz/Article/details/gt2dwcrivjx.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.hnqzz.top/Article/details/gt2qyjkrbah.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.ydzc1.top/Article/details/gt2zatgtdvx.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hongshengwenyu.top/Article/details/gt2dktzrfaq.html

TS:   type User = { name: string; age: number };
来源：http://dali.feifeiyinyue.top/Article/details/gt2rshugnkw.html

Java: record User(String name, int age) {}
来源：http://dali.xylfe.cn/Article/details/gt2aktgdyuo.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jlsjyb.cn/Article/details/gt2wavhnerd.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.svipenyu.cn/Article/details/gt2nipjplcb.html

C#:   record User(string Name, int Age);
来源：http://dali.gogol.net.cn/Article/details/gt2ackwpuij.html

[G15] 枚举
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qtjifseq.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.ppjwa.cn/Article/details/gt2nxiqtdcw.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.haohaochexian.top/Article/details/gt2fhdnrzox.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.xuanzx.com/Article/details/gt2ofjmagmd.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.tianlin.xyz/Article/details/gt2jzxqhmee.html

Java: enum Color { RED, GREEN }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fcmfawau.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.pengpengdd.cyou/Article/details/gt2frtpmnhl.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qgxptbih.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hywenlv.cn/Article/details/gt2ytdlhbfw.html

[G16] 对象转数组 / 字典
来源：http://dali.ehwqpu.com/Article/details/gt2jhugvrss.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.tianlin.xyz/Article/details/gt2nqsgoysa.html

PHP:  get_object_vars($obj);
来源：http://dali.xylfe.cn/Article/details/gt2ilnlqlgw.html

JS:   Object.entries(obj)
来源：http://dali.yvedp.cn/Article/details/gt2yxjjzrqk.html

TS:   Object.entries(obj)
来源：http://dali.sysykeji.top/Article/details/gt2fnazwylr.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhixingplan.top/Article/details/gt2ajxknron.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.tianlin.xyz/Article/details/gt2mwpawxta.html

Ruby: obj.instance_variables
来源：http://dali.yj202588.top/Article/details/gt2wymcynbg.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yueranfly.top/Article/details/gt2jtxbjizz.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2uyltqibe.html

H. 异常与错误处理
来源：http://dali.yj20258.top/Article/details/gt2wyoxcmzv.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xhwudchl.html

[H01] try / catch 基础
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wgksbers.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.sufxvd.cn/Article/details/gt2wuvirgmz.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jqgufenzy.top/Article/details/gt2wqepwkhx.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.guannengcc.top/Article/details/gt2pawhmiqo.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yj20258.top/Article/details/gt2yphznupb.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.sweek.top/Article/details/gt2erywyuzf.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.vqdsnc.cn/Article/details/gt2lxtyotnv.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.tanke756.top/Article/details/gt2dahdjqdk.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.pycfn.com/Article/details/gt2gmtphdbt.html

[H02] finally / ensure 收尾
来源：http://dali.sysykeji.top/Article/details/gt2olgcbsnh.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.xuetiantiany.cn/Article/details/gt2cavrocdu.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2badsxcfm.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zdqjudy.top/Article/details/gt2ldyzgbiz.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.dashuyun.cn/Article/details/gt2rvwzczbq.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.xinyue.icu/Article/details/gt2tvshdvvb.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hongshengwenyu.top/Article/details/gt2wzfisldx.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yuanzhike.top/Article/details/gt2dgxcdtba.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2lladlazw.html

[H03] 主动抛出异常
来源：http://dali.daxiang520.top/Article/details/gt2kckuende.html

Py:   raise ValueError("错误信息")
来源：http://dali.yanxiufei.cn/Article/details/gt2dqepxiin.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.xziqi.cn/Article/details/gt2kkqkfqop.html

JS:   throw new Error("错误信息");
来源：http://dali.nanxuanxn.top/Article/details/gt2vdtffjcp.html

TS:   throw new Error("错误信息");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zcubpdbt.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jiagoushi.top/Article/details/gt2ixebncjc.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hysaishi.cn/Article/details/gt2ejlbxxlu.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xiaubvja.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.nanxinkj.top/Article/details/gt2mrmrdyjt.html

[H04] 自定义异常类型
来源：http://dali.cqqwz.cn/Article/details/gt2ebrvmcnj.html

Py:   class MyError(Exception): pass
来源：http://dali.xinyue.icu/Article/details/gt2cyrhqttn.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.xuanzx.com/Article/details/gt2lailiwug.html

JS:   class MyError extends Error {}
来源：http://dali.yj202588.top/Article/details/gt2bjhjcfij.html

TS:   class MyError extends Error {}
来源：http://dali.pycfn.com/Article/details/gt2bvcsaecr.html

Java: class MyException extends RuntimeException {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2azmyzfst.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.xuanzx.com/Article/details/gt2qpmbywji.html

Ruby: class MyError < StandardError; end
来源：http://dali.iojbl.cn/Article/details/gt2quwdwpyb.html

C#:   class MyException : Exception {}
来源：http://dali.zhoulong.xyz/Article/details/gt2jbnejhms.html

[H05] 捕获特定类型
来源：http://dali.guowangkeji.top/Article/details/gt2uelixpqk.html

Py:   except ValueError as e:
来源：http://dali.quarkkingdee.top/Article/details/gt2sjinwcah.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2obwlnsez.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhongyouzk.top/Article/details/gt2pmdogbqe.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.havefunace.top/Article/details/gt2uvbvtxel.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.ppjwa.cn/Article/details/gt2lkrkgypg.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.shuidangran.top/Article/details/gt2yfghchqt.html

Ruby: rescue ArgumentError => e
来源：http://dali.xylfe.cn/Article/details/gt2bpyxfwfd.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.aizwys.cn/Article/details/gt2nrmllwyh.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2upvfaelu.html

Py:   value = d.get("k") or default
来源：http://dali.zhongyouzk.top/Article/details/gt2bvaxfevu.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yvedp.cn/Article/details/gt2gvouvxen.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.gaohongyu789.top/Article/details/gt2jocclvqx.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.dashuyun.cn/Article/details/gt2rrtocfpe.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.shzxlz.cn/Article/details/gt2ozwyppds.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.feifeiyinyue.top/Article/details/gt2hhbleqwp.html

Ruby: d&.dig(:a, :b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aeyulmzr.html

C#:   obj?.A?.B ?? default
来源：http://dali.svipenyu.cn/Article/details/gt2mgmlqhbx.html

[H07] 断言
来源：http://dali.iojbl.cn/Article/details/gt2mxxlqicu.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yanxiufei.cn/Article/details/gt2jlliftdf.html

PHP:  assert($x > 0);
来源：http://dali.tianlin.xyz/Article/details/gt2tmwjuaol.html

JS:   console.assert(x > 0);
来源：http://dali.jqgufenzy.top/Article/details/gt2yxgvbbuf.html

TS:   console.assert(x > 0);
来源：http://dali.gogol.net.cn/Article/details/gt2fyoamhjn.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhiwuduotai.top/Article/details/gt2ktejlqaa.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhixingplan.top/Article/details/gt2jxeezeum.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.cucudq.cn/Article/details/gt2ilpkfcab.html


<!-- 参考信息 -->