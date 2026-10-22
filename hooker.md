代发 wailian999

C#:   File.ReadAllText("a.txt");
来源：http://dali.yuxming.cn/Article/details/gtpgmvesgl.html

[F02] 逐行读取文件
来源：http://dali.ybcxt.top/Article/details/gtriyjyulr.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jianghu66.top/Article/details/gthbyqteoa.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.birdmap.top/Article/details/gtsdmwmjbv.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gotoacloud.top/Article/details/gtefgvrgby.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gthomtknns.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jinqigfzy.top/Article/details/gtnzdgvlgi.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.0kj1m.cn/Article/details/gtnsozzlzx.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.sysykeji.top/Article/details/gtgnqcnegq.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.fengsongda.top/Article/details/gtjhuruvzg.html

[F03] 写入文件（覆盖）
来源：http://dali.jinghuilouyu.cn/Article/details/gtcymtaozi.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.gzhubu.top/Article/details/gtudszurhw.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gtkvuzqwkb.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sysykeji.top/Article/details/gtakjfuipg.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sysykeji.top/Article/details/gtiazkikii.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.sxryk.cn/Article/details/gtohktcrls.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.nanxinkj.top/Article/details/gtbhttaube.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.xuanzx.com/Article/details/gtkqhyjrhb.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhengqikj.top/Article/details/gtssyubufs.html

[F04] 追加写入文件
来源：http://dali.gotoacloud.top/Article/details/gtsnnfjpgl.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jinqigufen.top/Article/details/gtehtylvvr.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yanxiufei.cn/Article/details/gtqivxpevk.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.tian-w.cn/Article/details/gtzfqdpwtw.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.daxiang520.top/Article/details/gtcuetbslk.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.c1oappe.top/Article/details/gtclbzpmnu.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.gotoacloud.top/Article/details/gtugsxwmrm.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.dianchejie.cn/Article/details/gtsgoepejd.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.mhx1999.top/Article/details/gthesofnbg.html

[F05] 判断文件或目录是否存在
来源：http://dali.hnxiangtu.top/Article/details/gtpcxxqkav.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.316326.xyz/Article/details/gtembhipes.html

PHP:  file_exists("a.txt");
来源：http://dali.xuanzx.com/Article/details/gtascsmqqr.html

JS:   fs.existsSync("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gthachkwot.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtvjalmthu.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.shuidangran.top/Article/details/gtbecsdhon.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.iojbl.cn/Article/details/gtehiojxdi.html

Ruby: File.exist?("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtbifccvcj.html

C#:   File.Exists("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gthftrnpfv.html

[F06] 删除文件
来源：http://dali.jinqigfzy.top/Article/details/gtuwofxmge.html

Py:   os.remove("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gttfqviobq.html

PHP:  unlink("a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gtrhxnxlks.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtsnxmsjyd.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtloxzeeaf.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.mhx1999.top/Article/details/gtldrayybt.html

Go:   os.Remove("a.txt")
来源：http://dali.pycfn.com/Article/details/gtrxfzreoh.html

Ruby: File.delete("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtwulsxugd.html

C#:   File.Delete("a.txt");
来源：http://dali.mhx1999.top/Article/details/gtmwtpvozn.html

[F07] 创建目录（含多级）
来源：http://dali.zycfv.cn/Article/details/gtrocekprj.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmtgjotob.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.smart0.xyz/Article/details/gtrxutdbjt.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ehwqpu.com/Article/details/gttevyzxxt.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hnqzz.top/Article/details/gttkchrbpk.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hfpthk.cn/Article/details/gttjbaitna.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.andypj.xyz/Article/details/gtbpwfupbz.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.9152youxi.cn/Article/details/gtlpcohwex.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.pengpengdd.cyou/Article/details/gtcapigkkd.html

[F08] 遍历目录
来源：http://dali.zhoulong.xyz/Article/details/gtzwieajsl.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jyoumei.cn/Article/details/gtfvlhppod.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.c1oappe.top/Article/details/gtymdjwdsg.html

JS:   fs.readdirSync("dir")
来源：http://dali.xuanzx.com/Article/details/gtipgvhigb.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhiwuduotai.top/Article/details/gtcoojirhk.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jinghuilouyu.cn/Article/details/gtbqfjxpnb.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jianghu66.top/Article/details/gtnxjycduc.html

Ruby: Dir.children("dir")
来源：http://dali.yonumen.top/Article/details/gtaeztzird.html

C#:   Directory.GetFiles("dir")
来源：http://dali.birdmap.top/Article/details/gtbpqgynme.html

[F09] 获取文件大小
来源：http://dali.jinqigufen.top/Article/details/gtlrlxevak.html

Py:   os.path.getsize("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtusdaodid.html

PHP:  filesize("a.txt");
来源：http://dali.yj202588.top/Article/details/gttkzevnte.html

JS:   fs.statSync("a.txt").size
来源：http://dali.daxiang520.top/Article/details/gtqrbvnkru.html

TS:   fs.statSync("a.txt").size
来源：http://dali.chenzaomai.com/Article/details/gtqbfpcmqb.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.tianlin.xyz/Article/details/gtvoqcsjys.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yj202588.top/Article/details/gtoteanuut.html

Ruby: File.size("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtuuyidyhu.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmoqdgkmf.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jinqigufen.top/Article/details/gtrxhuiwca.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtknzgyasw.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.hnqzz.top/Article/details/gtarcbawve.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yj20258.top/Article/details/gtlhrjfnag.html

TS:   path.extname("a.txt")
来源：http://dali.iojbl.cn/Article/details/gtmefvdkmg.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yuanzhike.top/Article/details/gtdqwwusdk.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.cheryme.top/Article/details/gtphgnhdeh.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtpllbdtdm.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.pycfn.com/Article/details/gtqpyuslws.html

[F11] 复制与移动文件
来源：http://dali.hammf.cn/Article/details/gtbudftulo.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.sxryk.cn/Article/details/gtlwfpadts.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.ehwqpu.com/Article/details/gtkmccclgi.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.guowangkeji.top/Article/details/gtzhhvahsi.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinqigufen.top/Article/details/gtaohfxxvt.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jqgufenzy.top/Article/details/gtdfqiowad.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.meibo888.top/Article/details/gtabjmcpsn.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtftjekqvg.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.feifeiyinyue.top/Article/details/gtuaciieus.html

[F12] CSV 读写
来源：http://dali.zhongyouzk.top/Article/details/gtltemljtb.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfbqfeyaa.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jqgufenzy.top/Article/details/gtgwqirdfj.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.redwolf501.top/Article/details/gtrlbvqzdb.html

TS:   // 同上
来源：http://dali.shuidangran.top/Article/details/gtflhhmoec.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jqgufenzy.top/Article/details/gtidajcncq.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.cheryme.top/Article/details/gtlsezxvdr.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.xylfe.cn/Article/details/gtqwbvfiti.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.fzhhl.top/Article/details/gtbvawsnai.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtrlbnnlei.html

G. 面向对象
来源：http://dali.vqdsnc.cn/Article/details/gtxvwdsoli.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtsohzcvei.html

[G01] 定义类
来源：http://dali.andypj.xyz/Article/details/gtlahlxnny.html

Py:   class User: pass
来源：http://dali.hnxiangtu.top/Article/details/gtpfycyzmz.html

PHP:  class User {}
来源：http://dali.zhiwuduotai.top/Article/details/gthjwrsfjd.html

JS:   class User {}
来源：http://dali.jyoumei.cn/Article/details/gtqdtpcost.html

TS:   class User { name: string = ""; }
来源：http://dali.jinqigfzy.top/Article/details/gtojdvvlwn.html

Java: class User {}
来源：http://dali.quarkkingdee.top/Article/details/gthetljine.html

Go:   type User struct { Name string }
来源：http://dali.sxryk.cn/Article/details/gtpaudxemc.html

Ruby: class User; end
来源：http://dali.xinyue.icu/Article/details/gtyplyvjpa.html

C#:   class User {}
来源：http://dali.ehwqpu.com/Article/details/gtfpsaneus.html

[G02] 构造函数
来源：http://dali.316326.xyz/Article/details/gtakceqqtt.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.redwolf501.top/Article/details/gtdgboulmz.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hywenlv.cn/Article/details/gtrtdxvzne.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yj20258.top/Article/details/gtfmgvkciu.html

TS:   constructor(public name: string) {}
来源：http://dali.dashuyun.cn/Article/details/gtvfhyvtjp.html

Java: User(String name) { this.name = name; }
来源：http://dali.dianchejie.cn/Article/details/gtmolewaok.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.vqdsnc.cn/Article/details/gtcypegjhk.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.andypj.xyz/Article/details/gtequldfas.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zycfv.cn/Article/details/gthtunvgtv.html

[G03] 实例属性
来源：http://dali.jqgfzy.top/Article/details/gtycwnevgn.html

Py:   self.name = "x"
来源：http://dali.aizwys.cn/Article/details/gtucnrbrjt.html

PHP:  public string $name = "x";
来源：http://dali.wangshuangyany.cn/Article/details/gtwlembvlf.html

JS:   this.name = "x";
来源：http://dali.xziqi.cn/Article/details/gtscdyvveb.html

TS:   name: string = "x";
来源：http://dali.zycfv.cn/Article/details/gtmpkqkayo.html

Java: private String name;
来源：http://dali.mhx1999.top/Article/details/gtgdovwehk.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.cqqwz.cn/Article/details/gtyooovlcv.html

Ruby: @name = "x"
来源：http://dali.chenlongwang.top/Article/details/gthayukdqt.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.xuanzx.com/Article/details/gtsnesbxiu.html

[G04] 定义方法
来源：http://dali.c1oappe.top/Article/details/gtcuuloclf.html

Py:   def greet(self): return self.name
来源：http://dali.fzhhl.top/Article/details/gtkunifgfk.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.sxryk.cn/Article/details/gtrpouedqu.html

JS:   greet() { return this.name; }
来源：http://dali.gzhubu.top/Article/details/gttkynjlcz.html

TS:   greet(): string { return this.name; }
来源：http://dali.jlsjyb.cn/Article/details/gtwmobltip.html

Java: String greet() { return name; }
来源：http://dali.yuxming.cn/Article/details/gtxsxyrepj.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jiagoushi.top/Article/details/gtffthbqmp.html

Ruby: def greet; @name; end
来源：http://dali.zhongyouzk.top/Article/details/gtrtonsong.html

C#:   public string Greet() => Name;
来源：http://dali.yuxming.cn/Article/details/gttaaargbv.html

[G05] 继承
来源：http://dali.sxryk.cn/Article/details/gtdzreokcg.html

Py:   class Admin(User): pass
来源：http://dali.hnxiangtu.top/Article/details/gtlohnalts.html

PHP:  class Admin extends User {}
来源：http://dali.chenjidiqi.icu/Article/details/gtpukxzfne.html

JS:   class Admin extends User {}
来源：http://dali.tianlin.xyz/Article/details/gtjhlayvdv.html

TS:   class Admin extends User {}
来源：http://dali.jqgufenzy.top/Article/details/gtljsiqrgv.html

Java: class Admin extends User {}
来源：http://dali.hongshengwenyu.top/Article/details/gthbmnxnsp.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.fengsongda.top/Article/details/gtvepnvhcm.html

Ruby: class Admin < User; end
来源：http://dali.snrcjt.cn/Article/details/gtakbyvngk.html

C#:   class Admin : User {}
来源：http://dali.yangfankeji.com/Article/details/gtjyxqoexd.html

[G06] 重写方法
来源：http://dali.ppjwa.cn/Article/details/gtvctalkra.html

Py:   def greet(self): return "admin"
来源：http://dali.jinqigfzy.top/Article/details/gtobzeeyiu.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.shuidangran.top/Article/details/gtddwfttfu.html

JS:   greet() { return "admin"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdpazfpun.html

TS:   greet(): string { return "admin"; }
来源：http://dali.snrcjt.cn/Article/details/gtowtsorij.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.meibo888.top/Article/details/gtscqtqpav.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.tianlin.xyz/Article/details/gtachjociq.html

Ruby: def greet; "admin"; end
来源：http://dali.zhiwuduotai.top/Article/details/gtlttjiciu.html

C#:   public override string Greet() => "admin";
来源：http://dali.shuidangran.top/Article/details/gtzamrnbll.html

[G07] 调用父类方法
来源：http://dali.yuanzhike.top/Article/details/gtfydaapmc.html

Py:   super().greet()
来源：http://dali.yvedp.cn/Article/details/gtigfshwnc.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gthsbldfwq.html

JS:   super.greet();
来源：http://dali.gaohongyu789.top/Article/details/gtxkbqoojm.html

TS:   super.greet();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlnslkelv.html

Java: super.greet();
来源：http://dali.sufxvd.cn/Article/details/gtakiujjfy.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.xuetiantiany.cn/Article/details/gtfgomrkuc.html

Ruby: super
来源：http://dali.jianghu66.top/Article/details/gtlusswoln.html

C#:   base.Greet();
来源：http://dali.yj202588.top/Article/details/gtnlexgxqz.html

[G08] 静态方法与属性
来源：http://dali.nanxinkj.top/Article/details/gtqudjztxk.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.gaohongyu789.top/Article/details/gtwvhxlzee.html

PHP:  public static function f() {}
来源：http://dali.zhengqikj.top/Article/details/gtbdbodpmh.html

JS:   static f() {}
来源：http://dali.sweek.top/Article/details/gttsrilifk.html

TS:   static f(): void {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlizhaqjm.html

Java: static void f() {}
来源：http://dali.gaohongyu789.top/Article/details/gtdsiszjtq.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.pycfn.com/Article/details/gtlplcaxhs.html

Ruby: def self.f; end
来源：http://dali.zhengqikj.top/Article/details/gtotioqjni.html

C#:   public static void F() {}
来源：http://dali.316326.xyz/Article/details/gtwenvtjim.html

[G09] 接口 / 抽象类
来源：http://dali.ydzc1.top/Article/details/gttvqtaffy.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.316326.xyz/Article/details/gtbekzvlxn.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.chenzaomai.com/Article/details/gttdhkjutt.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.cdnleiting.top/Article/details/gtdtawrdtx.html

TS:   interface Shape { area(): number; }
来源：http://dali.hysaishi.cn/Article/details/gtpbvrntwy.html

Java: interface Shape { double area(); }
来源：http://dali.nwbrower.top/Article/details/gtscqajycy.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.cqqwz.cn/Article/details/gtnwjddwyl.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yj20258888.top/Article/details/gtmnogmcxf.html

C#:   interface IShape { double Area(); }
来源：http://dali.jlsjyb.cn/Article/details/gtazxagopb.html

[G10] 访问控制
来源：http://dali.xylfe.cn/Article/details/gtwlkwvluz.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yuxming.cn/Article/details/gtaeifoflm.html

PHP:  public / protected / private
来源：http://dali.xuanzx.com/Article/details/gtbjxqbiob.html

JS:   #private 字段；其余公开
来源：http://dali.hnqzz.top/Article/details/gtvcobjwww.html

TS:   public / protected / private
来源：http://dali.yuxming.cn/Article/details/gtwmgahvcw.html

Java: public / protected / private / 默认包级
来源：http://dali.andypj.xyz/Article/details/gtxedtglot.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.redwolf501.top/Article/details/gtrofekgrm.html

Ruby: public / protected / private
来源：http://dali.xuetiantiany.cn/Article/details/gtkxcedsye.html

C#:   public / protected / private / internal
来源：http://dali.yanxiufei.cn/Article/details/gtxgkkqjmb.html

[G11] getter / setter
来源：http://dali.jiagoushi.top/Article/details/gtqjaynhrr.html

Py:   @property 与 @x.setter
来源：http://dali.yueranfly.top/Article/details/gtupsnertk.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.cashguo.top/Article/details/gtzhwezukb.html

JS:   get name() { return this._name; }
来源：http://dali.yj202588.top/Article/details/gtmzeonlou.html

TS:   get name(): string { return this._name; }
来源：http://dali.gotoacloud.top/Article/details/gtynpebigg.html

Java: public String getName() { return name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtfnjbvbwa.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.haohaochexian.top/Article/details/gtzudhbwkq.html

Ruby: attr_accessor :name
来源：http://dali.vqdsnc.cn/Article/details/gtlsejjvdl.html

C#:   public string Name { get; set; }
来源：http://dali.fengsongda.top/Article/details/gtsljebyar.html

[G12] 对象转字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgxhkzoya.html

Py:   def __str__(self): return self.name
来源：http://dali.jinghuilouyu.cn/Article/details/gtbuoavgzi.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.andypj.xyz/Article/details/gtuyndvmdi.html

JS:   toString() { return this.name; }
来源：http://dali.sweek.top/Article/details/gtqaucuaem.html

TS:   toString(): string { return this.name; }
来源：http://dali.nanxuanxn.top/Article/details/gtzvcjbavr.html

Java: @Override public String toString() { return name; }
来源：http://dali.9152youxi.cn/Article/details/gtxkdwshqn.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jinghuilouyu.cn/Article/details/gtlioopzaa.html

Ruby: def to_s; @name; end
来源：http://dali.zhengqikj.top/Article/details/gtqybhzthp.html

C#:   public override string ToString() => Name;
来源：http://dali.havefunace.top/Article/details/gtmktckift.html

[G13] 判断对象类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxcizifrq.html

Py:   isinstance(u, User)
来源：http://dali.hysaishi.cn/Article/details/gtfvjvrfpv.html

PHP:  $u instanceof User
来源：http://dali.xuetiantiany.cn/Article/details/gtkqzmmmga.html

JS:   u instanceof User
来源：http://dali.hnqzz.top/Article/details/gtedmbrwik.html

TS:   u instanceof User
来源：http://dali.xuetiantiany.cn/Article/details/gtzfxrwmrf.html

Java: u instanceof User
来源：http://dali.gaohongyu789.top/Article/details/gthrghfvvd.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.c1oappe.top/Article/details/gtmupyzlrj.html

Ruby: u.is_a?(User)
来源：http://dali.birdmap.top/Article/details/gtvfcmjltt.html

C#:   u is User
来源：http://dali.zhixingplan.top/Article/details/gtgqqlsbme.html

[G14] 数据类 / record
来源：http://dali.fengsongda.top/Article/details/gtgwxoxlne.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.sweek.top/Article/details/gtncsfjytg.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zycfv.cn/Article/details/gtepxmzsoy.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.smart0.xyz/Article/details/gtywndinsq.html

TS:   type User = { name: string; age: number };
来源：http://dali.xuanzx.com/Article/details/gtfbffnajt.html

Java: record User(String name, int age) {}
来源：http://dali.nanxinkj.top/Article/details/gtdcycezef.html

Go:   type User struct { Name string; Age int }
来源：http://dali.sufxvd.cn/Article/details/gtbcxfutkg.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.haohaochexian.top/Article/details/gtgxpvpubi.html

C#:   record User(string Name, int Age);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtayewqucy.html

[G15] 枚举
来源：http://dali.meibo888.top/Article/details/gtsbizvcpi.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.pengpengdd.cyou/Article/details/gtxxsmwvom.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jqgfzy.top/Article/details/gtkjvnelqq.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.aibaodan.cn/Article/details/gtcaitteqm.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ppjwa.cn/Article/details/gtpcvdnvab.html

Java: enum Color { RED, GREEN }
来源：http://dali.xziqi.cn/Article/details/gttdpgxetj.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.cdnleiting.top/Article/details/gtjlvplilr.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ydzc1.top/Article/details/gtcuopptjl.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.kuanghao11.cn/Article/details/gtvzpwtqhu.html

[G16] 对象转数组 / 字典
来源：http://dali.zycfv.cn/Article/details/gtqnfuoiju.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.hammf.cn/Article/details/gtkpgfsomp.html

PHP:  get_object_vars($obj);
来源：http://dali.shangyingyoupin.top/Article/details/gtmajrsxoq.html

JS:   Object.entries(obj)
来源：http://dali.zdqjudy.top/Article/details/gtepuwzkap.html

TS:   Object.entries(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpycqdheb.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.ybcxt.top/Article/details/gtyvrfmsgy.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jqgufenzy.top/Article/details/gtviqjnrnj.html

Ruby: obj.instance_variables
来源：http://dali.yj20258.top/Article/details/gtvdjxhepi.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.pengpengdd.cyou/Article/details/gtdxsjajtk.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtcytmdgza.html

H. 异常与错误处理
来源：http://dali.ivvv.top/Article/details/gtnylsrazn.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtnkqfusfe.html

[H01] try / catch 基础
来源：http://dali.iojbl.cn/Article/details/gtsntmyokf.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.ppjwa.cn/Article/details/gtmutnimzi.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.xuetiantiany.cn/Article/details/gtqzahhvtk.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gtwyoubsyf.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.xziqi.cn/Article/details/gtklvifqlp.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhiwuduotai.top/Article/details/gtzxeiacju.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.wangshuangyany.cn/Article/details/gtpgjtiqjh.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jlsjyb.cn/Article/details/gtuccrqsrq.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.pycfn.com/Article/details/gtggfobusf.html

[H02] finally / ensure 收尾
来源：http://dali.jianghu66.top/Article/details/gtxnrmoudh.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhoulong.xyz/Article/details/gtrdbfzrjw.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.xuetiantiany.cn/Article/details/gtqvqdfyaf.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.feifeiyinyue.top/Article/details/gtmdwcpqgk.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yonumen.top/Article/details/gtplleayac.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yangfankeji.com/Article/details/gtuxzsnjjv.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.gzhubu.top/Article/details/gtxczbbgre.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.pengpengdd.cyou/Article/details/gtqlpnbete.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yuanzhike.top/Article/details/gtedwkegbm.html

[H03] 主动抛出异常
来源：http://dali.sxryk.cn/Article/details/gtjestnwon.html

Py:   raise ValueError("错误信息")
来源：http://dali.zdqjudy.top/Article/details/gtsyrxsbba.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.guannengcc.top/Article/details/gtqzfohjqg.html

JS:   throw new Error("错误信息");
来源：http://dali.hfpthk.cn/Article/details/gteshfqfhp.html

TS:   throw new Error("错误信息");
来源：http://dali.jiagoushi.top/Article/details/gtlnsivuei.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.cucudq.cn/Article/details/gtxwjgjsjo.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.xinyue.icu/Article/details/gtczrijeds.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.meibo888.top/Article/details/gtgnhvnhen.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhoulong.xyz/Article/details/gtguptpouw.html

[H04] 自定义异常类型
来源：http://dali.jinqigufen.top/Article/details/gtrjzeqvkx.html

Py:   class MyError(Exception): pass
来源：http://dali.dianchejie.cn/Article/details/gtukqmxqmn.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtafmmbdoe.html

JS:   class MyError extends Error {}
来源：http://dali.dianchejie.cn/Article/details/gtkmqgzlmt.html

TS:   class MyError extends Error {}
来源：http://dali.shuidangran.top/Article/details/gtekbrlizx.html

Java: class MyException extends RuntimeException {}
来源：http://dali.mhx1999.top/Article/details/gtdnnghlnr.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.aibaodan.cn/Article/details/gtzlpclxnx.html

Ruby: class MyError < StandardError; end
来源：http://dali.guowangkeji.top/Article/details/gtatjyerxx.html

C#:   class MyException : Exception {}
来源：http://dali.nwbrower.top/Article/details/gtsjevucax.html

[H05] 捕获特定类型
来源：http://dali.zycfv.cn/Article/details/gtlyqwhrnt.html

Py:   except ValueError as e:
来源：http://dali.meibo888.top/Article/details/gteceqxxzw.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.tianlin.xyz/Article/details/gtzviwmoqx.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.daxiang520.top/Article/details/gtxicxxhix.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.dashuyun.cn/Article/details/gtteujsdjk.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.gotoacloud.top/Article/details/gtoyqagujl.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.tian-w.cn/Article/details/gtsrsrodwu.html

Ruby: rescue ArgumentError => e
来源：http://dali.ivvv.top/Article/details/gtcqqspddf.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.guowangkeji.top/Article/details/gtvhhiyiot.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhixingplan.top/Article/details/gtsitjguko.html

Py:   value = d.get("k") or default
来源：http://dali.shuidangran.top/Article/details/gtmexoymzq.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.gaohongyu789.top/Article/details/gtaxfbjldt.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.shzxlz.cn/Article/details/gttbvbqwzy.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.fengsongda.top/Article/details/gteopwcany.html


<!-- 参考信息 -->