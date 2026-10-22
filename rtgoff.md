代发 wailian999

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kmtlumls.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2blyklasn.html

[F03] 写入文件（覆盖）
来源：http://dali.dianchejie.cn/Article/details/gt2fjwgfpjc.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhengqikj.top/Article/details/gt2lmfyzhux.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.smart0.xyz/Article/details/gt2dbqhesuu.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2lbluytbx.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yueranfly.top/Article/details/gt2sishitrj.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.316326.xyz/Article/details/gt2bylzrzmg.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yj20258.top/Article/details/gt2ikkcjdzm.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.316326.xyz/Article/details/gt2izabqjye.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.meibo888.top/Article/details/gt2gizacjpk.html

[F04] 追加写入文件
来源：http://dali.yonumen.top/Article/details/gt2iyrmfxkj.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.sweek.top/Article/details/gt2lojynwwf.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yonumen.top/Article/details/gt2smvvombn.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinqigufen.top/Article/details/gt2ihxzpnws.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.birdmap.top/Article/details/gt2lsgehdrt.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yonumen.top/Article/details/gt2ammvbimn.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.pycfn.com/Article/details/gt2tprvlkzk.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhixingplan.top/Article/details/gt2gnbitjdb.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.hnxiangtu.top/Article/details/gt2vzflvkgt.html

[F05] 判断文件或目录是否存在
来源：http://dali.jinqigufen.top/Article/details/gt2aalelzon.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yj202588.top/Article/details/gt2zfqfsite.html

PHP:  file_exists("a.txt");
来源：http://dali.zycfv.cn/Article/details/gt2fbrpobrd.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gt2brrnpnnw.html

TS:   fs.existsSync("a.txt")
来源：http://dali.gzhubu.top/Article/details/gt2fhvpdsrk.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.gogol.net.cn/Article/details/gt2uwfyqpcr.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.c1oappe.top/Article/details/gt2tzmkbjwf.html

Ruby: File.exist?("a.txt")
来源：http://dali.tian-w.cn/Article/details/gt2pgbvxskf.html

C#:   File.Exists("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gt2ihaorlbs.html

[F06] 删除文件
来源：http://dali.sxryk.cn/Article/details/gt2rmhxpadv.html

Py:   os.remove("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gt2qevusqmo.html

PHP:  unlink("a.txt");
来源：http://dali.yongpay.top/Article/details/gt2ltwebmtc.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2arfubzda.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yueranfly.top/Article/details/gt2ambzdqhk.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.guowangkeji.top/Article/details/gt2pprfxilb.html

Go:   os.Remove("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gt2dsapjxyz.html

Ruby: File.delete("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2ablfzqwx.html

C#:   File.Delete("a.txt");
来源：http://dali.cashguo.top/Article/details/gt2wmunchpi.html

[F07] 创建目录（含多级）
来源：http://dali.xuetiantiany.cn/Article/details/gt2ndkntelk.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yueranfly.top/Article/details/gt2fwaumckv.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhoulong.xyz/Article/details/gt2jgtvnkrq.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xinyue.icu/Article/details/gt2bcxnhcpj.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.bjfxy.top/Article/details/gt2edmjerym.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.feifeiyinyue.top/Article/details/gt2ezxoieuv.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.aizwys.cn/Article/details/gt2pdjatwqz.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.redwolf501.top/Article/details/gt2belnowbp.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pfavifsd.html

[F08] 遍历目录
来源：http://dali.jinqigufen.top/Article/details/gt2rigocypw.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zycfv.cn/Article/details/gt2rjbougxb.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yj202588.top/Article/details/gt2fqpeudum.html

JS:   fs.readdirSync("dir")
来源：http://dali.shzxlz.cn/Article/details/gt2cninhmwb.html

TS:   fs.readdirSync("dir")
来源：http://dali.9152youxi.cn/Article/details/gt2aapwgcaq.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.guowangkeji.top/Article/details/gt2yygyxjer.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.wangshuangyany.cn/Article/details/gt2hdwxkeyq.html

Ruby: Dir.children("dir")
来源：http://dali.hywenlv.cn/Article/details/gt2hppnpovw.html

C#:   Directory.GetFiles("dir")
来源：http://dali.shzxlz.cn/Article/details/gt2xwujvmkc.html

[F09] 获取文件大小
来源：http://dali.svipenyu.cn/Article/details/gt2fshfchjm.html

Py:   os.path.getsize("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gt2yanvtywy.html

PHP:  filesize("a.txt");
来源：http://dali.yj202588.top/Article/details/gt2iadnjqav.html

JS:   fs.statSync("a.txt").size
来源：http://dali.pycfn.com/Article/details/gt2cmdmeihe.html

TS:   fs.statSync("a.txt").size
来源：http://dali.birdmap.top/Article/details/gt2toqmznkx.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.dashuyun.cn/Article/details/gt2fdxpicbz.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.ehwqpu.com/Article/details/gt2sbynteqy.html

Ruby: File.size("a.txt")
来源：http://dali.yueranfly.top/Article/details/gt2kwcqgamx.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.cdnleiting.top/Article/details/gt2bknjqnsk.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.cheryme.top/Article/details/gt2kilhyktp.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.xuanzx.com/Article/details/gt2ivfdmfgx.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gt2umawpgjo.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.cheryme.top/Article/details/gt2dfsxkcuz.html

TS:   path.extname("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2hrutljyo.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2abfuabfy.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yvedp.cn/Article/details/gt2jrmxqdzg.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2yhlcbbux.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2xvqnfbhc.html

[F11] 复制与移动文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vfcuoolz.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.mhx1999.top/Article/details/gt2vlyrmtiq.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.sxryk.cn/Article/details/gt2kxscweyz.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yanxiufei.cn/Article/details/gt2spatfkzu.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jiagoushi.top/Article/details/gt2ljvvlwrl.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhixingplan.top/Article/details/gt2unwtjcgk.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.quarkkingdee.top/Article/details/gt2irsopwwp.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.andypj.xyz/Article/details/gt2wgvwnrti.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.sweek.top/Article/details/gt2vvombqzf.html

[F12] CSV 读写
来源：http://dali.smart0.xyz/Article/details/gt2kzjuyzcw.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.nanxinkj.top/Article/details/gt2oilchouu.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.xuetiantiany.cn/Article/details/gt2ktnciggd.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kfqcfwgh.html

TS:   // 同上
来源：http://dali.jqgufenzy.top/Article/details/gt2ipsqkmsr.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yonumen.top/Article/details/gt2sgunloxw.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.fzhhl.top/Article/details/gt2zvrtszvn.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jinqigfzy.top/Article/details/gt2nvvidkbl.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.9152youxi.cn/Article/details/gt2brrjrmwx.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2xponxwcx.html

G. 面向对象
来源：http://dali.sxryk.cn/Article/details/gt2bicvcoxu.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2mjnmpyky.html

[G01] 定义类
来源：http://dali.tianlin.xyz/Article/details/gt2ctowqrzb.html

Py:   class User: pass
来源：http://dali.jqgufenzy.top/Article/details/gt2poofzwuo.html

PHP:  class User {}
来源：http://dali.jianghu66.top/Article/details/gt2qhirgmlq.html

JS:   class User {}
来源：http://dali.xinyue.icu/Article/details/gt2eeczwnlg.html

TS:   class User { name: string = ""; }
来源：http://dali.zhongyouzk.top/Article/details/gt2iwbwyizg.html

Java: class User {}
来源：http://dali.wangdashe.top/Article/details/gt2yndjjcer.html

Go:   type User struct { Name string }
来源：http://dali.daria6918.cn/Article/details/gt2gwvzkqrz.html

Ruby: class User; end
来源：http://dali.zhiwuduotai.top/Article/details/gt2ljtugcrh.html

C#:   class User {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2weqqyxbb.html

[G02] 构造函数
来源：http://dali.sweek.top/Article/details/gt2gusloynr.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.quarkkingdee.top/Article/details/gt2xzqqnsqy.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhoulong.xyz/Article/details/gt2grqtqedz.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.hammf.cn/Article/details/gt2awrfsiai.html

TS:   constructor(public name: string) {}
来源：http://dali.xinyue.icu/Article/details/gt2hquomhje.html

Java: User(String name) { this.name = name; }
来源：http://dali.havefunace.top/Article/details/gt2ihhtwcwt.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.shangyingyoupin.top/Article/details/gt2swpbeczb.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.xziqi.cn/Article/details/gt2cqwozbmq.html

C#:   public User(string name) { Name = name; }
来源：http://dali.hfpthk.cn/Article/details/gt2ggewxucw.html

[G03] 实例属性
来源：http://dali.wangdashe.top/Article/details/gt2tuzgtppd.html

Py:   self.name = "x"
来源：http://dali.yongpay.top/Article/details/gt2itlfrveq.html

PHP:  public string $name = "x";
来源：http://dali.jinqigufen.top/Article/details/gt2blpirldn.html

JS:   this.name = "x";
来源：http://dali.yj202588.top/Article/details/gt2guagkvio.html

TS:   name: string = "x";
来源：http://dali.jqgfzy.top/Article/details/gt2flwfcqnx.html

Java: private String name;
来源：http://dali.wangdashe.top/Article/details/gt2dttvpail.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.chenzaomai.com/Article/details/gt2osxemcyw.html

Ruby: @name = "x"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jqpwdloo.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.mhx1999.top/Article/details/gt2bvafvjyt.html

[G04] 定义方法
来源：http://dali.daria6918.cn/Article/details/gt2gqckcyxy.html

Py:   def greet(self): return self.name
来源：http://dali.ybcxt.top/Article/details/gt2omltuyil.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.redwolf501.top/Article/details/gt2nzdkpjvm.html

JS:   greet() { return this.name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bmxlcuxj.html

TS:   greet(): string { return this.name; }
来源：http://dali.316326.xyz/Article/details/gt2wceompcr.html

Java: String greet() { return name; }
来源：http://dali.cucudq.cn/Article/details/gt2bvgbdztp.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.smart0.xyz/Article/details/gt2womsjpyo.html

Ruby: def greet; @name; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yyunfdoc.html

C#:   public string Greet() => Name;
来源：http://dali.zhongyouzk.top/Article/details/gt2pzqarezh.html

[G05] 继承
来源：http://dali.tanke756.top/Article/details/gt2qfokuhup.html

Py:   class Admin(User): pass
来源：http://dali.yangfankeji.com/Article/details/gt2fqfeyaod.html

PHP:  class Admin extends User {}
来源：http://dali.quarkkingdee.top/Article/details/gt2exlhwzcp.html

JS:   class Admin extends User {}
来源：http://dali.gzhubu.top/Article/details/gt2ugbkezxf.html

TS:   class Admin extends User {}
来源：http://dali.tianlin.xyz/Article/details/gt2qpdehfxy.html

Java: class Admin extends User {}
来源：http://dali.andypj.xyz/Article/details/gt2ahkiidfy.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.aibaodan.cn/Article/details/gt2frprhcsz.html

Ruby: class Admin < User; end
来源：http://dali.9152youxi.cn/Article/details/gt2byzkqnzl.html

C#:   class Admin : User {}
来源：http://dali.xziqi.cn/Article/details/gt2irlwteia.html

[G06] 重写方法
来源：http://dali.dianchejie.cn/Article/details/gt2oladkdms.html

Py:   def greet(self): return "admin"
来源：http://dali.yongpay.top/Article/details/gt2xuyzizlg.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhoulong.xyz/Article/details/gt2blbmxtke.html

JS:   greet() { return "admin"; }
来源：http://dali.zdqjudy.top/Article/details/gt2rxqwfoqa.html

TS:   greet(): string { return "admin"; }
来源：http://dali.tian-w.cn/Article/details/gt2kfjeaiba.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yuxming.cn/Article/details/gt2fzwuzopb.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yj20258888.top/Article/details/gt2skhleshg.html

Ruby: def greet; "admin"; end
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nzepkldo.html

C#:   public override string Greet() => "admin";
来源：http://dali.haohaochexian.top/Article/details/gt2xaewqtxa.html

[G07] 调用父类方法
来源：http://dali.jlsjyb.cn/Article/details/gt2baqtxgsz.html

Py:   super().greet()
来源：http://dali.aizwys.cn/Article/details/gt2juwkkgqz.html

PHP:  parent::greet();
来源：http://dali.0kj1m.cn/Article/details/gt2uczbloho.html

JS:   super.greet();
来源：http://dali.hongshengwenyu.top/Article/details/gt2kvuvhnnd.html

TS:   super.greet();
来源：http://dali.dianchejie.cn/Article/details/gt2nbfsczxk.html

Java: super.greet();
来源：http://dali.jqgufenzy.top/Article/details/gt2njltnqis.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.sxryk.cn/Article/details/gt2qkowudto.html

Ruby: super
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sdiytydi.html

C#:   base.Greet();
来源：http://dali.cdnleiting.top/Article/details/gt2xgghxedb.html

[G08] 静态方法与属性
来源：http://dali.feifeiyinyue.top/Article/details/gt2pdtzdrin.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.havefunace.top/Article/details/gt2uacaoxjr.html

PHP:  public static function f() {}
来源：http://dali.yj202588.top/Article/details/gt2xjcoxaut.html

JS:   static f() {}
来源：http://dali.guowangkeji.top/Article/details/gt2vtmcstsc.html

TS:   static f(): void {}
来源：http://dali.redwolf501.top/Article/details/gt2pfoyekmb.html

Java: static void f() {}
来源：http://dali.316326.xyz/Article/details/gt2jyvmnber.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.tanke756.top/Article/details/gt2bfsuxokf.html

Ruby: def self.f; end
来源：http://dali.hammf.cn/Article/details/gt2awaoeirq.html

C#:   public static void F() {}
来源：http://dali.mhx1999.top/Article/details/gt2rbmkaoxf.html

[G09] 接口 / 抽象类
来源：http://dali.redwolf501.top/Article/details/gt2iakbgurb.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.nwbrower.top/Article/details/gt2dampsluv.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.xylfe.cn/Article/details/gt2zpilwjlg.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yj202588.top/Article/details/gt2dpvceylv.html

TS:   interface Shape { area(): number; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2otnkrilh.html

Java: interface Shape { double area(); }
来源：http://dali.zdqjudy.top/Article/details/gt2bkinqibx.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.ehwqpu.com/Article/details/gt2ppezurxf.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hfpthk.cn/Article/details/gt2cxtxtuvj.html

C#:   interface IShape { double Area(); }
来源：http://dali.meibo888.top/Article/details/gt2hhysvgjq.html

[G10] 访问控制
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cukskdot.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.fengsongda.top/Article/details/gt2wzzfmmch.html

PHP:  public / protected / private
来源：http://dali.yuanzhike.top/Article/details/gt2lfchpzkr.html

JS:   #private 字段；其余公开
来源：http://dali.andypj.xyz/Article/details/gt2truocilb.html

TS:   public / protected / private
来源：http://dali.aibaodan.cn/Article/details/gt2xtzdjglw.html

Java: public / protected / private / 默认包级
来源：http://dali.daxiang520.top/Article/details/gt2vtsvmzbu.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fbeldokd.html

Ruby: public / protected / private
来源：http://dali.gotoacloud.top/Article/details/gt2idvyfzdr.html

C#:   public / protected / private / internal
来源：http://dali.daria6918.cn/Article/details/gt2tszsxzgj.html

[G11] getter / setter
来源：http://dali.pengpengdd.cyou/Article/details/gt2gkmwnkem.html

Py:   @property 与 @x.setter
来源：http://dali.andypj.xyz/Article/details/gt2ftmzckof.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.hfpthk.cn/Article/details/gt2olfirezv.html

JS:   get name() { return this._name; }
来源：http://dali.andypj.xyz/Article/details/gt2zqvuerqy.html

TS:   get name(): string { return this._name; }
来源：http://dali.fzhhl.top/Article/details/gt2quiovjfa.html

Java: public String getName() { return name; }
来源：http://dali.kuanghao11.cn/Article/details/gt2jhbtplqb.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.hnxiangtu.top/Article/details/gt2xtsdfxrw.html

Ruby: attr_accessor :name
来源：http://dali.hnxiangtu.top/Article/details/gt2rkgixqex.html

C#:   public string Name { get; set; }
来源：http://dali.redwolf501.top/Article/details/gt2rkxwbdkt.html

[G12] 对象转字符串
来源：http://dali.nwbrower.top/Article/details/gt2sfcfthxk.html

Py:   def __str__(self): return self.name
来源：http://dali.zdqjudy.top/Article/details/gt2oeefdwcz.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.bjfxy.top/Article/details/gt2yqefjbjh.html

JS:   toString() { return this.name; }
来源：http://dali.fengsongda.top/Article/details/gt2jpiyklhj.html

TS:   toString(): string { return this.name; }
来源：http://dali.haohaochexian.top/Article/details/gt2kfaazrnw.html

Java: @Override public String toString() { return name; }
来源：http://dali.tianlin.xyz/Article/details/gt2fpqgehrs.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.snrcjt.cn/Article/details/gt2uaufwpof.html

Ruby: def to_s; @name; end
来源：http://dali.jyoumei.cn/Article/details/gt2cemlbsdd.html

C#:   public override string ToString() => Name;
来源：http://dali.ppjwa.cn/Article/details/gt2bvwarujs.html

[G13] 判断对象类型
来源：http://dali.zhiwuduotai.top/Article/details/gt2putganbe.html

Py:   isinstance(u, User)
来源：http://dali.snrcjt.cn/Article/details/gt2fkfcvkzg.html

PHP:  $u instanceof User
来源：http://dali.sweek.top/Article/details/gt2feywfhqx.html

JS:   u instanceof User
来源：http://dali.wangdashe.top/Article/details/gt2ixydkevo.html

TS:   u instanceof User
来源：http://dali.xuanzx.com/Article/details/gt2dndxcnqp.html

Java: u instanceof User
来源：http://dali.yangfankeji.com/Article/details/gt2dywkbkhz.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhijiandao.cn/Article/details/gt2upjwaixp.html

Ruby: u.is_a?(User)
来源：http://dali.gogol.net.cn/Article/details/gt2puphimcr.html

C#:   u is User
来源：http://dali.hammf.cn/Article/details/gt2foexkqmw.html

[G14] 数据类 / record
来源：http://dali.yonumen.top/Article/details/gt2dwcnsqmk.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.cashguo.top/Article/details/gt2sfvdjvxf.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.pycfn.com/Article/details/gt2lydqdewc.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.xinyue.icu/Article/details/gt2slbkkzxe.html

TS:   type User = { name: string; age: number };
来源：http://dali.kuanghao11.cn/Article/details/gt2tznfsgxu.html

Java: record User(String name, int age) {}
来源：http://dali.snrcjt.cn/Article/details/gt2podbkpbw.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zycfv.cn/Article/details/gt2royvmpfe.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.wangdashe.top/Article/details/gt2irzragnj.html

C#:   record User(string Name, int Age);
来源：http://dali.yongpay.top/Article/details/gt2tpbmnkrx.html

[G15] 枚举
来源：http://dali.tanke756.top/Article/details/gt2gfbycmhh.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhongyouzk.top/Article/details/gt2pxptndwu.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zwefmajb.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.gotoacloud.top/Article/details/gt2cnnzarxn.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.daxiang520.top/Article/details/gt2qickicpo.html

Java: enum Color { RED, GREEN }
来源：http://dali.svipenyu.cn/Article/details/gt2zfyegmat.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.ehwqpu.com/Article/details/gt2ozuzurfm.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yuanzhike.top/Article/details/gt2vxphzpjb.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.fengsongda.top/Article/details/gt2ghlhehsq.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gt2fsbkmklr.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jianghu66.top/Article/details/gt2jfvnbzqm.html

PHP:  get_object_vars($obj);
来源：http://dali.chenzaomai.com/Article/details/gt2eooizygi.html

JS:   Object.entries(obj)
来源：http://dali.xziqi.cn/Article/details/gt2exwuzufr.html

TS:   Object.entries(obj)
来源：http://dali.tianlin.xyz/Article/details/gt2sqfjnqpd.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhongyouzk.top/Article/details/gt2vsdpdcgo.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rqegjakw.html

Ruby: obj.instance_variables
来源：http://dali.jyoumei.cn/Article/details/gt2tplgqzru.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jiagoushi.top/Article/details/gt2tpirzcfo.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2olcebfls.html

H. 异常与错误处理
来源：http://dali.havefunace.top/Article/details/gt2nmwxauox.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2ikqsmrrm.html

[H01] try / catch 基础
来源：http://dali.zhoulong.xyz/Article/details/gt2uintrzde.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.dashuyun.cn/Article/details/gt2sglzuotq.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.sufxvd.cn/Article/details/gt2heygesqs.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2wiatpnit.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2harpibwv.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.cqqwz.cn/Article/details/gt2pmdummne.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yueranfly.top/Article/details/gt2udftaeqp.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.nanxuanxn.top/Article/details/gt2zdacwukz.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.316326.xyz/Article/details/gt2pmgmgskp.html

[H02] finally / ensure 收尾
来源：http://dali.xinyue.icu/Article/details/gt2oilglkpz.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zdqjudy.top/Article/details/gt2meumgdfc.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.xylfe.cn/Article/details/gt2nfmumpan.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yongpay.top/Article/details/gt2lmgdpaob.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hnxiangtu.top/Article/details/gt2eeebisvm.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.meibo888.top/Article/details/gt2gyqxunoy.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.bjfxy.top/Article/details/gt2magadlpe.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.pengpengdd.cyou/Article/details/gt2kwckwjpy.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.tanke756.top/Article/details/gt2asdlmjzm.html

[H03] 主动抛出异常
来源：http://dali.zhiwuduotai.top/Article/details/gt2wmbmhghl.html

Py:   raise ValueError("错误信息")
来源：http://dali.jqgfzy.top/Article/details/gt2jzrnjxfv.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jinqigufen.top/Article/details/gt2eqzglixx.html

JS:   throw new Error("错误信息");
来源：http://dali.aibaodan.cn/Article/details/gt2jznjlqhd.html

TS:   throw new Error("错误信息");
来源：http://dali.guowangkeji.top/Article/details/gt2vhphqffz.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.snrcjt.cn/Article/details/gt2lixmmqkd.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.shzxlz.cn/Article/details/gt2guttfkka.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhoulong.xyz/Article/details/gt2hmalcpyw.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.haohaochexian.top/Article/details/gt2yuuabsoa.html

[H04] 自定义异常类型
来源：http://dali.wangshuangyany.cn/Article/details/gt2fguullpz.html

Py:   class MyError(Exception): pass
来源：http://dali.shzxlz.cn/Article/details/gt2nddcyykr.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.tian-w.cn/Article/details/gt2wbninkmm.html

JS:   class MyError extends Error {}
来源：http://dali.xylfe.cn/Article/details/gt2pwrnfqhp.html

TS:   class MyError extends Error {}
来源：http://dali.tanke756.top/Article/details/gt2junolxpk.html

Java: class MyException extends RuntimeException {}
来源：http://dali.sxryk.cn/Article/details/gt2rejyyryq.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.316326.xyz/Article/details/gt2fhbvijnv.html

Ruby: class MyError < StandardError; end
来源：http://dali.dianchejie.cn/Article/details/gt2ndsqhfcz.html

C#:   class MyException : Exception {}
来源：http://dali.bjfxy.top/Article/details/gt2qxcaamdy.html

[H05] 捕获特定类型
来源：http://dali.sufxvd.cn/Article/details/gt2svxchqwq.html

Py:   except ValueError as e:
来源：http://dali.xylfe.cn/Article/details/gt2etprrxik.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ymhobeby.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.cucudq.cn/Article/details/gt2vtzwsnen.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.smart0.xyz/Article/details/gt2opvieccb.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.ydzc1.top/Article/details/gt2qxqwrkax.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.bjfxy.top/Article/details/gt2ewvfhsph.html

Ruby: rescue ArgumentError => e
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xqkvzfcw.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.cheryme.top/Article/details/gt2txbicjhd.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yangfankeji.com/Article/details/gt2pjlcowxu.html

Py:   value = d.get("k") or default
来源：http://dali.ybcxt.top/Article/details/gt2srfhfuxa.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jyoumei.cn/Article/details/gt2ibokvusx.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jlsjyb.cn/Article/details/gt2fmqstefe.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.bjfxy.top/Article/details/gt2wmwetnel.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.chenzaomai.com/Article/details/gt2xnrrxkqq.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2aukurhue.html

Ruby: d&.dig(:a, :b)
来源：http://dali.sufxvd.cn/Article/details/gt2yugkgmly.html

C#:   obj?.A?.B ?? default
来源：http://dali.nanxuanxn.top/Article/details/gt2vtzgbkly.html

[H07] 断言
来源：http://dali.andypj.xyz/Article/details/gt2edmngqts.html

Py:   assert x > 0, "必须为正"
来源：http://dali.wangdashe.top/Article/details/gt2ywbbxkzk.html

PHP:  assert($x > 0);
来源：http://dali.vqdsnc.cn/Article/details/gt2eejinxzz.html

JS:   console.assert(x > 0);
来源：http://dali.jiagoushi.top/Article/details/gt2wecoxvfw.html


<!-- 参考信息 -->