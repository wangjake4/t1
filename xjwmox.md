代发 wailian999

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhongyouzk.top/Article/details/gttvlinkqz.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jyoumei.cn/Article/details/gtenhmahfz.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.quarkkingdee.top/Article/details/gtrptaaxub.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zycfv.cn/Article/details/gtfkyapomt.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.shzxlz.cn/Article/details/gteuuvzstw.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.ppjwa.cn/Article/details/gtkkchzfdf.html

[F03] 写入文件（覆盖）
来源：http://dali.zhiwuduotai.top/Article/details/gtumdjhnrt.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yangfankeji.com/Article/details/gtiuavsbov.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtestqejpz.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.svipenyu.cn/Article/details/gtitgalism.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.dashuyun.cn/Article/details/gtbqxpylqb.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.cucudq.cn/Article/details/gttydiypmj.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.guannengcc.top/Article/details/gtaqoqwyie.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.pycfn.com/Article/details/gtstpbvgrw.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.dashuyun.cn/Article/details/gtchovrnqu.html

[F04] 追加写入文件
来源：http://dali.jqgufenzy.top/Article/details/gtecrtrwtc.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.ydzc1.top/Article/details/gtjrxszayf.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvmevfbzs.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.havefunace.top/Article/details/gtxlcunqrt.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hysaishi.cn/Article/details/gtfexggkbf.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.wangshuangyany.cn/Article/details/gtfeujirmo.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.iojbl.cn/Article/details/gtcazbtqnq.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.chenzaomai.com/Article/details/gtopenrxwc.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhoulong.xyz/Article/details/gtzxnsgnlj.html

[F05] 判断文件或目录是否存在
来源：http://dali.redwolf501.top/Article/details/gtdpnuffdc.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.cheryme.top/Article/details/gtjbuvqyts.html

PHP:  file_exists("a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gtttiotzhd.html

JS:   fs.existsSync("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtzeoyetdk.html

TS:   fs.existsSync("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtjztgdwcc.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.kuanghao11.cn/Article/details/gtvwwzictz.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyibzvmmr.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtbbvnxjon.html

C#:   File.Exists("a.txt")
来源：http://dali.iojbl.cn/Article/details/gtyhozhymi.html

[F06] 删除文件
来源：http://dali.kuanghao11.cn/Article/details/gthmfbjozt.html

Py:   os.remove("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtopzbxyar.html

PHP:  unlink("a.txt");
来源：http://dali.yonumen.top/Article/details/gtxsudaegr.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtuotkcuwj.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.smart0.xyz/Article/details/gtejratara.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.xziqi.cn/Article/details/gtoezkiifk.html

Go:   os.Remove("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtimdrjvjp.html

Ruby: File.delete("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtmgsmrfsf.html

C#:   File.Delete("a.txt");
来源：http://dali.hammf.cn/Article/details/gtujlgukbw.html

[F07] 创建目录（含多级）
来源：http://dali.hammf.cn/Article/details/gtfopinqdo.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.chenzaomai.com/Article/details/gtbpvpkawm.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.gaohongyu789.top/Article/details/gtyugsxpuy.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.chenlongwang.top/Article/details/gtjjxuhsrg.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xinyue.icu/Article/details/gtrzqwwcjr.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.shuidangran.top/Article/details/gtupscebux.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jqgufenzy.top/Article/details/gtivzbwzur.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.smart0.xyz/Article/details/gtpxyjpxbm.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.tanke756.top/Article/details/gtavpvmqgl.html

[F08] 遍历目录
来源：http://dali.xziqi.cn/Article/details/gtkvtcmuyx.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zdqjudy.top/Article/details/gtwobovouq.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.xuanzx.com/Article/details/gtkdqjyeqv.html

JS:   fs.readdirSync("dir")
来源：http://dali.nwbrower.top/Article/details/gtskujwkkr.html

TS:   fs.readdirSync("dir")
来源：http://dali.pengpengdd.cyou/Article/details/gtsdoqrmad.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.xinyue.icu/Article/details/gtlvytxnre.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.hnqzz.top/Article/details/gtmppxayfp.html

Ruby: Dir.children("dir")
来源：http://dali.shzxlz.cn/Article/details/gtytdogdrp.html

C#:   Directory.GetFiles("dir")
来源：http://dali.ivvv.top/Article/details/gtcacldgpw.html

[F09] 获取文件大小
来源：http://dali.hfpthk.cn/Article/details/gtxoygikha.html

Py:   os.path.getsize("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtmkwagwuq.html

PHP:  filesize("a.txt");
来源：http://dali.fzhhl.top/Article/details/gtqbbyhawm.html

JS:   fs.statSync("a.txt").size
来源：http://dali.haohaochexian.top/Article/details/gtvfjnfqfu.html

TS:   fs.statSync("a.txt").size
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqiwhpzlp.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.redwolf501.top/Article/details/gtndgxipvl.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.cucudq.cn/Article/details/gtcaswtoni.html

Ruby: File.size("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtczaktgqx.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.ydzc1.top/Article/details/gtjwiaucyn.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthyptrtjv.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gthaagzlnb.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.sxryk.cn/Article/details/gtdgmhgrtd.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtxwstyhcy.html

TS:   path.extname("a.txt")
来源：http://dali.tian-w.cn/Article/details/gtcegmvnco.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yanxiufei.cn/Article/details/gtrrnnjuyp.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtehjlyhor.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.cheryme.top/Article/details/gtncccgint.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yj20258888.top/Article/details/gtoxgjehpe.html

[F11] 复制与移动文件
来源：http://dali.zhiwuduotai.top/Article/details/gtaznpehxp.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.9152youxi.cn/Article/details/gtczzrrsio.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.snrcjt.cn/Article/details/gtbcshdlln.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.316326.xyz/Article/details/gtvcnkjoqd.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtunsvhcxc.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yanxiufei.cn/Article/details/gtpxixiwoy.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.xziqi.cn/Article/details/gtqnfcyxnk.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.xylfe.cn/Article/details/gtbwlglufi.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.hongshengwenyu.top/Article/details/gtcetcvhqn.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gtqhngzaiw.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhoulong.xyz/Article/details/gtxummethf.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jinqigfzy.top/Article/details/gtguvcvgoi.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.chenzaomai.com/Article/details/gtszzyoywt.html

TS:   // 同上
来源：http://dali.yuanzhike.top/Article/details/gtjafbhclk.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.shanyushiyangkeji.top/Article/details/gtigeiwjbu.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.xinyue.icu/Article/details/gtahhtsdbg.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.dianchejie.cn/Article/details/gtxvbvsybl.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkirlmxrf.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtplqzpodz.html

G. 面向对象
来源：http://dali.ivvv.top/Article/details/gtnhadrafq.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtnqltlonp.html

[G01] 定义类
来源：http://dali.andypj.xyz/Article/details/gttrhxuguz.html

Py:   class User: pass
来源：http://dali.gotoacloud.top/Article/details/gtoglbjnlf.html

PHP:  class User {}
来源：http://dali.xinyue.icu/Article/details/gthwzsdrjv.html

JS:   class User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtklkjgniy.html

TS:   class User { name: string = ""; }
来源：http://dali.iojbl.cn/Article/details/gtjnhudnat.html

Java: class User {}
来源：http://dali.cheryme.top/Article/details/gtyublltpp.html

Go:   type User struct { Name string }
来源：http://dali.yangfankeji.com/Article/details/gtnqytshyd.html

Ruby: class User; end
来源：http://dali.sweek.top/Article/details/gtawtnaotf.html

C#:   class User {}
来源：http://dali.ivvv.top/Article/details/gthxavvemu.html

[G02] 构造函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsnwhctcx.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.sweek.top/Article/details/gtzyjazzte.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yj20258.top/Article/details/gtpuodfnvk.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.andypj.xyz/Article/details/gtccrxtjtr.html

TS:   constructor(public name: string) {}
来源：http://dali.jinqigfzy.top/Article/details/gtajeapqkd.html

Java: User(String name) { this.name = name; }
来源：http://dali.jyoumei.cn/Article/details/gtrkriuqcd.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.cashguo.top/Article/details/gtacrxoqly.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.xuetiantiany.cn/Article/details/gtupppjhwh.html

C#:   public User(string name) { Name = name; }
来源：http://dali.iojbl.cn/Article/details/gtqmfdsfks.html

[G03] 实例属性
来源：http://dali.vqdsnc.cn/Article/details/gtknrawkmf.html

Py:   self.name = "x"
来源：http://dali.jqgfzy.top/Article/details/gtnqypmdqj.html

PHP:  public string $name = "x";
来源：http://dali.andypj.xyz/Article/details/gtwqfkbzhc.html

JS:   this.name = "x";
来源：http://dali.nwbrower.top/Article/details/gtxhulfbwv.html

TS:   name: string = "x";
来源：http://dali.tianlin.xyz/Article/details/gtvgmhgtwh.html

Java: private String name;
来源：http://dali.jqgufenzy.top/Article/details/gtgfxicudo.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.c1oappe.top/Article/details/gtkteledsr.html

Ruby: @name = "x"
来源：http://dali.fzhhl.top/Article/details/gtzjxoqoqw.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.guowangkeji.top/Article/details/gtmcarolnu.html

[G04] 定义方法
来源：http://dali.0kj1m.cn/Article/details/gtynomygom.html

Py:   def greet(self): return self.name
来源：http://dali.sxryk.cn/Article/details/gtjlrmrqcg.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.chenlongwang.top/Article/details/gtvneqssae.html

JS:   greet() { return this.name; }
来源：http://dali.cashguo.top/Article/details/gtrzglcjvh.html

TS:   greet(): string { return this.name; }
来源：http://dali.ppjwa.cn/Article/details/gtzossbgsf.html

Java: String greet() { return name; }
来源：http://dali.hysaishi.cn/Article/details/gtflcyakab.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.snrcjt.cn/Article/details/gtdkphvjhm.html

Ruby: def greet; @name; end
来源：http://dali.andypj.xyz/Article/details/gtstkkyhec.html

C#:   public string Greet() => Name;
来源：http://dali.gogol.net.cn/Article/details/gtqezedqnf.html

[G05] 继承
来源：http://dali.ppjwa.cn/Article/details/gtvkuelfqq.html

Py:   class Admin(User): pass
来源：http://dali.guannengcc.top/Article/details/gtpoijohgs.html

PHP:  class Admin extends User {}
来源：http://dali.zdqjudy.top/Article/details/gtfhlmmpos.html

JS:   class Admin extends User {}
来源：http://dali.mhx1999.top/Article/details/gtzhzbpiix.html

TS:   class Admin extends User {}
来源：http://dali.chenjidiqi.icu/Article/details/gtexjlhigp.html

Java: class Admin extends User {}
来源：http://dali.yj20258888.top/Article/details/gtpzhbcxkk.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.guowangkeji.top/Article/details/gtpcyjfhad.html

Ruby: class Admin < User; end
来源：http://dali.fengsongda.top/Article/details/gtykirzckx.html

C#:   class Admin : User {}
来源：http://dali.zhiwuduotai.top/Article/details/gtoxzgitgk.html

[G06] 重写方法
来源：http://dali.xziqi.cn/Article/details/gtuusommjf.html

Py:   def greet(self): return "admin"
来源：http://dali.jianghu66.top/Article/details/gtpiffcsjh.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoxacmgyj.html

JS:   greet() { return "admin"; }
来源：http://dali.vqdsnc.cn/Article/details/gtpttiinga.html

TS:   greet(): string { return "admin"; }
来源：http://dali.sxryk.cn/Article/details/gtdabpqdmg.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.cashguo.top/Article/details/gtndqtetnj.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.vqdsnc.cn/Article/details/gthogffmpq.html

Ruby: def greet; "admin"; end
来源：http://dali.0kj1m.cn/Article/details/gteivtbaku.html

C#:   public override string Greet() => "admin";
来源：http://dali.yongpay.top/Article/details/gtwqjhqwxi.html

[G07] 调用父类方法
来源：http://dali.cheryme.top/Article/details/gthukatrin.html

Py:   super().greet()
来源：http://dali.zhengqikj.top/Article/details/gtpypfglcd.html

PHP:  parent::greet();
来源：http://dali.daxiang520.top/Article/details/gtrvuwdmbi.html

JS:   super.greet();
来源：http://dali.c1oappe.top/Article/details/gtlozrwdfx.html

TS:   super.greet();
来源：http://dali.zhixingplan.top/Article/details/gtcvwgygjo.html

Java: super.greet();
来源：http://dali.tanke756.top/Article/details/gtxxwbizlz.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hnxiangtu.top/Article/details/gtmlomrjnd.html

Ruby: super
来源：http://dali.havefunace.top/Article/details/gtcamcgfwa.html

C#:   base.Greet();
来源：http://dali.guowangkeji.top/Article/details/gtzzckvoyu.html

[G08] 静态方法与属性
来源：http://dali.hysaishi.cn/Article/details/gtegodgtci.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yvedp.cn/Article/details/gtmrfoawyr.html

PHP:  public static function f() {}
来源：http://dali.sufxvd.cn/Article/details/gtmoazncjb.html

JS:   static f() {}
来源：http://dali.snrcjt.cn/Article/details/gtmmkpqalc.html

TS:   static f(): void {}
来源：http://dali.hfpthk.cn/Article/details/gtbajvrids.html

Java: static void f() {}
来源：http://dali.snrcjt.cn/Article/details/gtdcksxnfh.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfwuqmgng.html

Ruby: def self.f; end
来源：http://dali.jqgufenzy.top/Article/details/gtvjuzjmmo.html

C#:   public static void F() {}
来源：http://dali.hywenlv.cn/Article/details/gtwmbizimv.html

[G09] 接口 / 抽象类
来源：http://dali.yongpay.top/Article/details/gtycvjdcqh.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhengqikj.top/Article/details/gtybjtkwrv.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.ydzc1.top/Article/details/gtrdxlgxsj.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.nwbrower.top/Article/details/gtrnyknndg.html

TS:   interface Shape { area(): number; }
来源：http://dali.jinqigufen.top/Article/details/gtrwzupqfu.html

Java: interface Shape { double area(); }
来源：http://dali.meibo888.top/Article/details/gtizhigqtx.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yj20258888.top/Article/details/gtduimeyzn.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.dianchejie.cn/Article/details/gtuytvniaw.html

C#:   interface IShape { double Area(); }
来源：http://dali.daria6918.cn/Article/details/gtgwsqkeky.html

[G10] 访问控制
来源：http://dali.zhiwuduotai.top/Article/details/gtqysrounw.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.fzhhl.top/Article/details/gtghhtpoft.html

PHP:  public / protected / private
来源：http://dali.ehwqpu.com/Article/details/gtjqxsgcae.html

JS:   #private 字段；其余公开
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzkawmcpw.html

TS:   public / protected / private
来源：http://dali.jiagoushi.top/Article/details/gtykduxogd.html

Java: public / protected / private / 默认包级
来源：http://dali.cucudq.cn/Article/details/gtsaeaqlnq.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.daria6918.cn/Article/details/gtymptanfp.html

Ruby: public / protected / private
来源：http://dali.chenzaomai.com/Article/details/gtglcltytw.html

C#:   public / protected / private / internal
来源：http://dali.daxiang520.top/Article/details/gtijkipqtk.html

[G11] getter / setter
来源：http://dali.cqqwz.cn/Article/details/gtwzzxgkik.html

Py:   @property 与 @x.setter
来源：http://dali.cqqwz.cn/Article/details/gttiwtukih.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.aibaodan.cn/Article/details/gtbtdacmhw.html

JS:   get name() { return this._name; }
来源：http://dali.yuanzhike.top/Article/details/gtdxpdoiht.html

TS:   get name(): string { return this._name; }
来源：http://dali.vqdsnc.cn/Article/details/gtirhkkdpl.html

Java: public String getName() { return name; }
来源：http://dali.fengsongda.top/Article/details/gtxieqhapz.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.snrcjt.cn/Article/details/gtsxbvfiyp.html

Ruby: attr_accessor :name
来源：http://dali.wangshuangyany.cn/Article/details/gttzrcaqvh.html

C#:   public string Name { get; set; }
来源：http://dali.iojbl.cn/Article/details/gtvvflrgzm.html

[G12] 对象转字符串
来源：http://dali.nanxuanxn.top/Article/details/gtxrbunqww.html

Py:   def __str__(self): return self.name
来源：http://dali.jinqigfzy.top/Article/details/gtneydvrxc.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.kuanghao11.cn/Article/details/gtrspfpgoh.html

JS:   toString() { return this.name; }
来源：http://dali.sxryk.cn/Article/details/gthvttiluu.html

TS:   toString(): string { return this.name; }
来源：http://dali.shzxlz.cn/Article/details/gtebhmecms.html

Java: @Override public String toString() { return name; }
来源：http://dali.jlsjyb.cn/Article/details/gthtelfsob.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.iojbl.cn/Article/details/gtmienzpyd.html

Ruby: def to_s; @name; end
来源：http://dali.ybcxt.top/Article/details/gtobonwwgi.html

C#:   public override string ToString() => Name;
来源：http://dali.daxiang520.top/Article/details/gteyhphyxt.html

[G13] 判断对象类型
来源：http://dali.hammf.cn/Article/details/gtbexyfcmi.html

Py:   isinstance(u, User)
来源：http://dali.dianchejie.cn/Article/details/gtapxdoygl.html

PHP:  $u instanceof User
来源：http://dali.xinyue.icu/Article/details/gtxmktsqxu.html

JS:   u instanceof User
来源：http://dali.havefunace.top/Article/details/gthylfzlye.html

TS:   u instanceof User
来源：http://dali.sufxvd.cn/Article/details/gtdiswkdsv.html

Java: u instanceof User
来源：http://dali.cqqwz.cn/Article/details/gtvlytsgen.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhoulong.xyz/Article/details/gtydphegfw.html

Ruby: u.is_a?(User)
来源：http://dali.nwbrower.top/Article/details/gtisqpssqw.html

C#:   u is User
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtemumnafq.html

[G14] 数据类 / record
来源：http://dali.haohaochexian.top/Article/details/gtaqeykfsm.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yvedp.cn/Article/details/gtczsskhhb.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.mhx1999.top/Article/details/gtubltzczq.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.xuetiantiany.cn/Article/details/gtjhgripgp.html

TS:   type User = { name: string; age: number };
来源：http://dali.cdnleiting.top/Article/details/gtmzvjrxgd.html

Java: record User(String name, int age) {}
来源：http://dali.aibaodan.cn/Article/details/gtywbcyuba.html

Go:   type User struct { Name string; Age int }
来源：http://dali.redwolf501.top/Article/details/gttttmlgfc.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jinqigufen.top/Article/details/gtfyurqtld.html

C#:   record User(string Name, int Age);
来源：http://dali.daria6918.cn/Article/details/gtldouljhq.html

[G15] 枚举
来源：http://dali.smart0.xyz/Article/details/gtinlkckap.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yueranfly.top/Article/details/gtilmfygtf.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.nanxuanxn.top/Article/details/gtjnqyound.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.daria6918.cn/Article/details/gttfztzovs.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.guannengcc.top/Article/details/gtukforaha.html

Java: enum Color { RED, GREEN }
来源：http://dali.jinqigfzy.top/Article/details/gtevflfusa.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zycfv.cn/Article/details/gtocpgstqt.html

Ruby: Color = %i[red green].freeze
来源：http://dali.havefunace.top/Article/details/gtqrzgokac.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hywenlv.cn/Article/details/gtpgsxfryh.html

[G16] 对象转数组 / 字典
来源：http://dali.hnxiangtu.top/Article/details/gtpueaksgv.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrhsdcipg.html

PHP:  get_object_vars($obj);
来源：http://dali.cashguo.top/Article/details/gtbymwblae.html

JS:   Object.entries(obj)
来源：http://dali.redwolf501.top/Article/details/gtuvdzowos.html

TS:   Object.entries(obj)
来源：http://dali.hnqzz.top/Article/details/gtdhiiumvy.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.iojbl.cn/Article/details/gtgeqjejag.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yanxiufei.cn/Article/details/gtxiapyzhv.html

Ruby: obj.instance_variables
来源：http://dali.sysykeji.top/Article/details/gtevmeqtvg.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.cucudq.cn/Article/details/gtcbgvtdca.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtzvksklct.html

H. 异常与错误处理
来源：http://dali.hfpthk.cn/Article/details/gtafagqjjk.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtavlxkitp.html

[H01] try / catch 基础
来源：http://dali.daria6918.cn/Article/details/gthbhkzsyo.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yj202588.top/Article/details/gtfzxsaolz.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.gotoacloud.top/Article/details/gtprzrrkja.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.mhx1999.top/Article/details/gttjfukjkg.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.meibo888.top/Article/details/gtjssrrvmw.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhiwuduotai.top/Article/details/gtnmwhgjce.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jinghuilouyu.cn/Article/details/gtuheragen.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.iojbl.cn/Article/details/gtnvitqltv.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtmxhxcdxs.html

[H02] finally / ensure 收尾
来源：http://dali.nwbrower.top/Article/details/gtejgimzab.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yj20258888.top/Article/details/gtnssqrffc.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.cucudq.cn/Article/details/gtujkjfnlh.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ivvv.top/Article/details/gtrgvzinwl.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtntcjnast.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.nwbrower.top/Article/details/gthvlwoeyx.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.kuanghao11.cn/Article/details/gtrfpparyj.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.fengsongda.top/Article/details/gtidjxmolh.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.hysaishi.cn/Article/details/gtahucdneh.html

[H03] 主动抛出异常
来源：http://dali.yuanzhike.top/Article/details/gtabbdfvub.html

Py:   raise ValueError("错误信息")
来源：http://dali.dashuyun.cn/Article/details/gtvpwlfxor.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.xylfe.cn/Article/details/gtwvqpwqrx.html

JS:   throw new Error("错误信息");
来源：http://dali.zhengqikj.top/Article/details/gtogatrhwb.html

TS:   throw new Error("错误信息");
来源：http://dali.zhixingplan.top/Article/details/gtxqdcstnv.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yongpay.top/Article/details/gtvwbiowfm.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hammf.cn/Article/details/gtxottxlsr.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yj20258888.top/Article/details/gtmnglmmfe.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.dashuyun.cn/Article/details/gtntlhxksi.html

[H04] 自定义异常类型
来源：http://dali.jqgufenzy.top/Article/details/gthwsnjukl.html

Py:   class MyError(Exception): pass
来源：http://dali.jinqigfzy.top/Article/details/gtialgazpn.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jianghu66.top/Article/details/gtafdbuyyh.html

JS:   class MyError extends Error {}
来源：http://dali.xuetiantiany.cn/Article/details/gtnnmdodzx.html

TS:   class MyError extends Error {}
来源：http://dali.zhoulong.xyz/Article/details/gtuzfstayq.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hammf.cn/Article/details/gtkkbuwdyq.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.mhx1999.top/Article/details/gtqycfqfom.html

Ruby: class MyError < StandardError; end
来源：http://dali.316326.xyz/Article/details/gtcufqxevu.html

C#:   class MyException : Exception {}
来源：http://dali.sysykeji.top/Article/details/gtytsidzpl.html

[H05] 捕获特定类型
来源：http://dali.yuanzhike.top/Article/details/gttkbovzdd.html

Py:   except ValueError as e:
来源：http://dali.sxryk.cn/Article/details/gttrqslmxt.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.gzhubu.top/Article/details/gtccmyqqrb.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jianghu66.top/Article/details/gtayieakik.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.vqdsnc.cn/Article/details/gtqdvlrgik.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yonumen.top/Article/details/gtlhojwcxj.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfsrsehqz.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhongyouzk.top/Article/details/gtkpylmufo.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.sysykeji.top/Article/details/gthkzkitvg.html

[H06] 可选值 / 空值安全访问
来源：http://dali.shanyushiyangtech.top/Article/details/gttlrquxhi.html

Py:   value = d.get("k") or default
来源：http://dali.shangyingyoupin.top/Article/details/gtskxmogdk.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhixingplan.top/Article/details/gtjmnlemws.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.shanyushiyangtech.top/Article/details/gthhlnkfwj.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.wangshuangyany.cn/Article/details/gtfujbmfvz.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jinghuilouyu.cn/Article/details/gtlcfiveqg.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.hfpthk.cn/Article/details/gthivgmakn.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hongshengwenyu.top/Article/details/gtcokaxphk.html

C#:   obj?.A?.B ?? default
来源：http://dali.bjfxy.top/Article/details/gthrkpthdl.html


<!-- 参考信息 -->