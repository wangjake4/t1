代发 wailian999

C#:   File.ReadAllText("a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gtjbjjnmgr.html

[F02] 逐行读取文件
来源：http://dali.aizwys.cn/Article/details/gtsvwhqbvr.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.sxryk.cn/Article/details/gtzzrltfmv.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.chenjidiqi.icu/Article/details/gtuqdnrnuy.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gaohongyu789.top/Article/details/gtwryumuyh.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xylfe.cn/Article/details/gtzipnihdc.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.tian-w.cn/Article/details/gtusvzquuk.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.xuetiantiany.cn/Article/details/gtfukauyck.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yj20258.top/Article/details/gtqlvileci.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.sufxvd.cn/Article/details/gtnatiaapw.html

[F03] 写入文件（覆盖）
来源：http://dali.sxryk.cn/Article/details/gtdzqhoerc.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.sufxvd.cn/Article/details/gthpusyywo.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.hywenlv.cn/Article/details/gtkegngrnc.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.mhx1999.top/Article/details/gtylqtrpnd.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shangyingyoupin.top/Article/details/gtrnsvmpbi.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.c1oappe.top/Article/details/gtkbnizfxa.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.chenzaomai.com/Article/details/gtmcgzstif.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.sufxvd.cn/Article/details/gtsqrchbyj.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.sufxvd.cn/Article/details/gtqwnnsapn.html

[F04] 追加写入文件
来源：http://dali.fzhhl.top/Article/details/gthxadjdzm.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zycfv.cn/Article/details/gtrlxgeuem.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.mhx1999.top/Article/details/gtcnramhdj.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.andypj.xyz/Article/details/gtyxjccjka.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gzhubu.top/Article/details/gtpyoejtzp.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yj202588.top/Article/details/gtbpgcdnmf.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.hysaishi.cn/Article/details/gtdiaedzoz.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.sxryk.cn/Article/details/gtigfyvuud.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.chenzaomai.com/Article/details/gthxrcfnyg.html

[F05] 判断文件或目录是否存在
来源：http://dali.hnxiangtu.top/Article/details/gtorawzkwx.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zycfv.cn/Article/details/gtabsklzet.html

PHP:  file_exists("a.txt");
来源：http://dali.zhixingplan.top/Article/details/gtaacpcebq.html

JS:   fs.existsSync("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtjkaqcpld.html

TS:   fs.existsSync("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtikwdemzt.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.dashuyun.cn/Article/details/gtkxzkfxoy.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.tian-w.cn/Article/details/gttvcpdanj.html

Ruby: File.exist?("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtzqyvdvae.html

C#:   File.Exists("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtdefhpgfy.html

[F06] 删除文件
来源：http://dali.fzhhl.top/Article/details/gtdpvcurfv.html

Py:   os.remove("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtnectuatd.html

PHP:  unlink("a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gthqxcplgi.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtfsflipqe.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtlrbpdcib.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.chenjidiqi.icu/Article/details/gtnzvgisou.html

Go:   os.Remove("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtvqhxtsqx.html

Ruby: File.delete("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtptpeddip.html

C#:   File.Delete("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gtsxaygtol.html

[F07] 创建目录（含多级）
来源：http://dali.yangfankeji.com/Article/details/gttkastogz.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.haohaochexian.top/Article/details/gtvewwpzbh.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.tanke756.top/Article/details/gtcifhqwwb.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinghuilouyu.cn/Article/details/gtynwyhwjb.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.meibo888.top/Article/details/gtlgoglezx.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.cheryme.top/Article/details/gtifsbfdxd.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.birdmap.top/Article/details/gtnlyskddy.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.iojbl.cn/Article/details/gtxcmbwqcd.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.hysaishi.cn/Article/details/gtwajpyprd.html

[F08] 遍历目录
来源：http://dali.yvedp.cn/Article/details/gtwpxyccei.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.kuanghao11.cn/Article/details/gttzqmawxn.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.sxryk.cn/Article/details/gtqcmuanae.html

JS:   fs.readdirSync("dir")
来源：http://dali.gaohongyu789.top/Article/details/gtjeemyfwd.html

TS:   fs.readdirSync("dir")
来源：http://dali.xylfe.cn/Article/details/gtehjlyzjz.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.feifeiyinyue.top/Article/details/gtdbntcmcz.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.xinyue.icu/Article/details/gtmeatmids.html

Ruby: Dir.children("dir")
来源：http://dali.cheryme.top/Article/details/gtzosbkbdp.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hfpthk.cn/Article/details/gticeukcfj.html

[F09] 获取文件大小
来源：http://dali.hammf.cn/Article/details/gtywjyayoc.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gttyohrgvo.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gtgutxqrat.html

JS:   fs.statSync("a.txt").size
来源：http://dali.nwbrower.top/Article/details/gtaidcgysy.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jlsjyb.cn/Article/details/gtepoxyjtj.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.fengsongda.top/Article/details/gtjventwsy.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yj202588.top/Article/details/gtwnaqktsz.html

Ruby: File.size("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtsirdqhab.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.shzxlz.cn/Article/details/gtkfedsmbq.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jinqigfzy.top/Article/details/gtzfonycrc.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.daria6918.cn/Article/details/gtttcdsmdr.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yongpay.top/Article/details/gtpsorgkzz.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtslbhdpbv.html

TS:   path.extname("a.txt")
来源：http://dali.birdmap.top/Article/details/gtejqjqyet.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jiagoushi.top/Article/details/gthoxjomqi.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtvabphxug.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtgbiyexgv.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtfajcxsww.html

[F11] 复制与移动文件
来源：http://dali.zdqjudy.top/Article/details/gtxlnwnnff.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtksoxmhku.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.sysykeji.top/Article/details/gtbbaxqdxi.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sweek.top/Article/details/gtsfsolyif.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hfpthk.cn/Article/details/gtormmwema.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.feifeiyinyue.top/Article/details/gtkizbekdr.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.redwolf501.top/Article/details/gtxowjtdfv.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yongpay.top/Article/details/gtuwxhntru.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.quarkkingdee.top/Article/details/gtnbtxerbm.html

[F12] CSV 读写
来源：http://dali.feifeiyinyue.top/Article/details/gtkbpjgece.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hongshengwenyu.top/Article/details/gtaiipkayv.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.aizwys.cn/Article/details/gtwrvrgowa.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.sweek.top/Article/details/gtvjxfkfps.html

TS:   // 同上
来源：http://dali.xinyue.icu/Article/details/gtzfftshfk.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yuxming.cn/Article/details/gtuhprrtil.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.shanyushiyangtech.top/Article/details/gtpsnuqoxz.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhongyouzk.top/Article/details/gtaervhgpd.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.meibo888.top/Article/details/gtpztnsjsy.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtjysnbhjc.html

G. 面向对象
来源：http://dali.yongpay.top/Article/details/gtyphytnvr.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtdxcdfjvh.html

[G01] 定义类
来源：http://dali.jlsjyb.cn/Article/details/gtsmbvakwo.html

Py:   class User: pass
来源：http://dali.fzhhl.top/Article/details/gtkxwyktti.html

PHP:  class User {}
来源：http://dali.hysaishi.cn/Article/details/gtcgtqpisc.html

JS:   class User {}
来源：http://dali.yj20258888.top/Article/details/gtltbbkysb.html

TS:   class User { name: string = ""; }
来源：http://dali.sweek.top/Article/details/gtsmshylnr.html

Java: class User {}
来源：http://dali.sxryk.cn/Article/details/gtlubvxtyj.html

Go:   type User struct { Name string }
来源：http://dali.chenjidiqi.icu/Article/details/gtrxzqcvyy.html

Ruby: class User; end
来源：http://dali.cucudq.cn/Article/details/gtsrbtphhw.html

C#:   class User {}
来源：http://dali.shzxlz.cn/Article/details/gtzecirvvv.html

[G02] 构造函数
来源：http://dali.zhiwuduotai.top/Article/details/gtfgefoioa.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhiwuduotai.top/Article/details/gtjhvzcoyb.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yangfankeji.com/Article/details/gtmsbmqjte.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yvedp.cn/Article/details/gtcbnrmgmi.html

TS:   constructor(public name: string) {}
来源：http://dali.9152youxi.cn/Article/details/gtwzsruzfb.html

Java: User(String name) { this.name = name; }
来源：http://dali.jinqigufen.top/Article/details/gtnrzelmxz.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jinqigufen.top/Article/details/gtcriawsuq.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhiwuduotai.top/Article/details/gtcsubrakm.html

C#:   public User(string name) { Name = name; }
来源：http://dali.sysykeji.top/Article/details/gtpsqxksmn.html

[G03] 实例属性
来源：http://dali.jqgufenzy.top/Article/details/gtzlizwltv.html

Py:   self.name = "x"
来源：http://dali.zhiwuduotai.top/Article/details/gtymjrnqoi.html

PHP:  public string $name = "x";
来源：http://dali.cheryme.top/Article/details/gtgsdilchg.html

JS:   this.name = "x";
来源：http://dali.gaohongyu789.top/Article/details/gtrizjezwu.html

TS:   name: string = "x";
来源：http://dali.jiagoushi.top/Article/details/gtrtxeaysz.html

Java: private String name;
来源：http://dali.yuxming.cn/Article/details/gtkcngnxqr.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jianghu66.top/Article/details/gtjfizukyx.html

Ruby: @name = "x"
来源：http://dali.sufxvd.cn/Article/details/gtsaqpjtaf.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhengqikj.top/Article/details/gtcmgjfbon.html

[G04] 定义方法
来源：http://dali.yuxming.cn/Article/details/gtzugzdklm.html

Py:   def greet(self): return self.name
来源：http://dali.gogol.net.cn/Article/details/gttxcjzxax.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.sweek.top/Article/details/gtjbqwtaxy.html

JS:   greet() { return this.name; }
来源：http://dali.zdqjudy.top/Article/details/gtgmkccwkm.html

TS:   greet(): string { return this.name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtztnhabbs.html

Java: String greet() { return name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtqrodnvso.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hysaishi.cn/Article/details/gttkmrcwxd.html

Ruby: def greet; @name; end
来源：http://dali.cashguo.top/Article/details/gtnxyynxbr.html

C#:   public string Greet() => Name;
来源：http://dali.jinyuanbaomall.cn/Article/details/gteplqamky.html

[G05] 继承
来源：http://dali.smart0.xyz/Article/details/gtjhsithot.html

Py:   class Admin(User): pass
来源：http://dali.redwolf501.top/Article/details/gtjpnmgftv.html

PHP:  class Admin extends User {}
来源：http://dali.zhoulong.xyz/Article/details/gtjhiwvagl.html

JS:   class Admin extends User {}
来源：http://dali.shuidangran.top/Article/details/gtmxpfirnf.html

TS:   class Admin extends User {}
来源：http://dali.daxiang520.top/Article/details/gterbhyqjv.html

Java: class Admin extends User {}
来源：http://dali.gaohongyu789.top/Article/details/gtxewqpkfo.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zdqjudy.top/Article/details/gtzyhkxcys.html

Ruby: class Admin < User; end
来源：http://dali.yangfankeji.com/Article/details/gtvunsquro.html

C#:   class Admin : User {}
来源：http://dali.zhengqikj.top/Article/details/gtzpmxawvq.html

[G06] 重写方法
来源：http://dali.yvedp.cn/Article/details/gthvuqgzmh.html

Py:   def greet(self): return "admin"
来源：http://dali.hfpthk.cn/Article/details/gtsjwbsgqq.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.dashuyun.cn/Article/details/gthijjjfpd.html

JS:   greet() { return "admin"; }
来源：http://dali.ybcxt.top/Article/details/gtzmqyzctc.html

TS:   greet(): string { return "admin"; }
来源：http://dali.shangyingyoupin.top/Article/details/gtsbstdrlj.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.sysykeji.top/Article/details/gtlxcyxygj.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.smart0.xyz/Article/details/gtedrowfhb.html

Ruby: def greet; "admin"; end
来源：http://dali.cqqwz.cn/Article/details/gtuaswxvyp.html

C#:   public override string Greet() => "admin";
来源：http://dali.daria6918.cn/Article/details/gteppklayv.html

[G07] 调用父类方法
来源：http://dali.chenzaomai.com/Article/details/gtymtfeevk.html

Py:   super().greet()
来源：http://dali.jinghuilouyu.cn/Article/details/gtzdobcsyn.html

PHP:  parent::greet();
来源：http://dali.sufxvd.cn/Article/details/gtflhoqjjy.html

JS:   super.greet();
来源：http://dali.ivvv.top/Article/details/gtgkownxzt.html

TS:   super.greet();
来源：http://dali.gogol.net.cn/Article/details/gtymoulwex.html

Java: super.greet();
来源：http://dali.shanyushiyangtech.top/Article/details/gtuxkkeqpz.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jiagoushi.top/Article/details/gtesoocksm.html

Ruby: super
来源：http://dali.ehwqpu.com/Article/details/gtmwjeifaw.html

C#:   base.Greet();
来源：http://dali.gaohongyu789.top/Article/details/gtzjaqrviq.html

[G08] 静态方法与属性
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnzdekzrb.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.sufxvd.cn/Article/details/gtlejwjyrn.html

PHP:  public static function f() {}
来源：http://dali.zhengqikj.top/Article/details/gtjqosdudu.html

JS:   static f() {}
来源：http://dali.xziqi.cn/Article/details/gtqwtjblof.html

TS:   static f(): void {}
来源：http://dali.chenzaomai.com/Article/details/gtmzzomylt.html

Java: static void f() {}
来源：http://dali.0kj1m.cn/Article/details/gtrejeqmlu.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.fengsongda.top/Article/details/gtmycybvoq.html

Ruby: def self.f; end
来源：http://dali.yanxiufei.cn/Article/details/gtewsmstoz.html

C#:   public static void F() {}
来源：http://dali.andypj.xyz/Article/details/gtxaqqqtlr.html

[G09] 接口 / 抽象类
来源：http://dali.chenlongwang.top/Article/details/gtkrrbzfzj.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.ybcxt.top/Article/details/gtvvurticn.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.316326.xyz/Article/details/gtpzbemzyk.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.sxryk.cn/Article/details/gtvlyowlft.html

TS:   interface Shape { area(): number; }
来源：http://dali.haohaochexian.top/Article/details/gtoglzpnci.html

Java: interface Shape { double area(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwoyotgth.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhoulong.xyz/Article/details/gtokjocfmo.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.ehwqpu.com/Article/details/gtksgyxkoj.html

C#:   interface IShape { double Area(); }
来源：http://dali.0kj1m.cn/Article/details/gtmqcargom.html

[G10] 访问控制
来源：http://dali.sweek.top/Article/details/gtnhzenvxh.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.fengsongda.top/Article/details/gtkbeztict.html

PHP:  public / protected / private
来源：http://dali.yj20258888.top/Article/details/gtzfehwrtd.html

JS:   #private 字段；其余公开
来源：http://dali.jlsjyb.cn/Article/details/gtmzgfjvuz.html

TS:   public / protected / private
来源：http://dali.yuanzhike.top/Article/details/gtdctfrrtr.html

Java: public / protected / private / 默认包级
来源：http://dali.pycfn.com/Article/details/gtajleiien.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yj20258888.top/Article/details/gtmlomdhnu.html

Ruby: public / protected / private
来源：http://dali.nanxuanxn.top/Article/details/gtfbjevawe.html

C#:   public / protected / private / internal
来源：http://dali.cucudq.cn/Article/details/gtanposyui.html

[G11] getter / setter
来源：http://dali.sufxvd.cn/Article/details/gtedylnalv.html

Py:   @property 与 @x.setter
来源：http://dali.bjfxy.top/Article/details/gtblaeicmi.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zycfv.cn/Article/details/gthkybpoxi.html

JS:   get name() { return this._name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtesuigben.html

TS:   get name(): string { return this._name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtqscsgwvj.html

Java: public String getName() { return name; }
来源：http://dali.jlsjyb.cn/Article/details/gtanbqeogq.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.sufxvd.cn/Article/details/gtjkbqrpqv.html

Ruby: attr_accessor :name
来源：http://dali.0kj1m.cn/Article/details/gtlualcyhr.html

C#:   public string Name { get; set; }
来源：http://dali.xuetiantiany.cn/Article/details/gtdvvqyyws.html

[G12] 对象转字符串
来源：http://dali.jqgufenzy.top/Article/details/gtpgtcbwqr.html

Py:   def __str__(self): return self.name
来源：http://dali.hongshengwenyu.top/Article/details/gtxyywihkm.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hnqzz.top/Article/details/gtjdauxpab.html

JS:   toString() { return this.name; }
来源：http://dali.gogol.net.cn/Article/details/gtgpixkawj.html

TS:   toString(): string { return this.name; }
来源：http://dali.vqdsnc.cn/Article/details/gtfwpvkrop.html

Java: @Override public String toString() { return name; }
来源：http://dali.xylfe.cn/Article/details/gtmwxgkmdi.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvzemzblj.html

Ruby: def to_s; @name; end
来源：http://dali.jyoumei.cn/Article/details/gthozesaar.html

C#:   public override string ToString() => Name;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkwtinlmx.html

[G13] 判断对象类型
来源：http://dali.yj20258.top/Article/details/gtkopxkyza.html

Py:   isinstance(u, User)
来源：http://dali.gogol.net.cn/Article/details/gtxgwmipyz.html

PHP:  $u instanceof User
来源：http://dali.yangfankeji.com/Article/details/gtukxophnj.html

JS:   u instanceof User
来源：http://dali.hongshengwenyu.top/Article/details/gtqeyledso.html

TS:   u instanceof User
来源：http://dali.xinyue.icu/Article/details/gtbmsosdnc.html

Java: u instanceof User
来源：http://dali.ivvv.top/Article/details/gtjwzwzzng.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.andypj.xyz/Article/details/gtatcyqdif.html

Ruby: u.is_a?(User)
来源：http://dali.quarkkingdee.top/Article/details/gtclqkpjsj.html

C#:   u is User
来源：http://dali.haohaochexian.top/Article/details/gtfkqlobkg.html

[G14] 数据类 / record
来源：http://dali.smart0.xyz/Article/details/gtbxouiiwf.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.ppjwa.cn/Article/details/gtdlgxpwlt.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.haohaochexian.top/Article/details/gtwtwsgmhg.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.sweek.top/Article/details/gtbbrzlqev.html

TS:   type User = { name: string; age: number };
来源：http://dali.yangfankeji.com/Article/details/gtnqolvbaw.html

Java: record User(String name, int age) {}
来源：http://dali.ppjwa.cn/Article/details/gtsgmqawfd.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhoulong.xyz/Article/details/gttunmediw.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.kuanghao11.cn/Article/details/gtvchhyhwf.html

C#:   record User(string Name, int Age);
来源：http://dali.yangfankeji.com/Article/details/gtzxdreeps.html

[G15] 枚举
来源：http://dali.ppjwa.cn/Article/details/gtdrjegyyj.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.andypj.xyz/Article/details/gtfjjvelks.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yangfankeji.com/Article/details/gtdhgnpgsm.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.cheryme.top/Article/details/gtpsasxxpc.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shanyushiyangtech.top/Article/details/gtngmjotbe.html

Java: enum Color { RED, GREEN }
来源：http://dali.wangdashe.top/Article/details/gtnyxfldvk.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.pengpengdd.cyou/Article/details/gtofvpoqll.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhengqikj.top/Article/details/gtjpmhpach.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.svipenyu.cn/Article/details/gtroyruuxj.html

[G16] 对象转数组 / 字典
来源：http://dali.jlsjyb.cn/Article/details/gtyigjlplg.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.tianlin.xyz/Article/details/gtjtbhnhrl.html

PHP:  get_object_vars($obj);
来源：http://dali.tanke756.top/Article/details/gtprfttkjw.html

JS:   Object.entries(obj)
来源：http://dali.sweek.top/Article/details/gtvvflhzpy.html

TS:   Object.entries(obj)
来源：http://dali.zhoulong.xyz/Article/details/gtawvdmfon.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.dashuyun.cn/Article/details/gtquhwurpp.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.hysaishi.cn/Article/details/gtbixznhpj.html

Ruby: obj.instance_variables
来源：http://dali.jinyuanbaomall.cn/Article/details/gthfbjpznd.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yongpay.top/Article/details/gtkeksdwjg.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtppbnfrkw.html

H. 异常与错误处理
来源：http://dali.dashuyun.cn/Article/details/gtkawlubtx.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtbxedslay.html

[H01] try / catch 基础
来源：http://dali.hammf.cn/Article/details/gtpxinticb.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.0kj1m.cn/Article/details/gtscwkzerk.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yj202588.top/Article/details/gtuwknxiyf.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jlsjyb.cn/Article/details/gtvquzoopd.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhoulong.xyz/Article/details/gtcnohfqva.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yangfankeji.com/Article/details/gtnmmqlqqb.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.chenzaomai.com/Article/details/gtpwftoxsq.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.tianlin.xyz/Article/details/gtvvgoxmkt.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhixingplan.top/Article/details/gtkdugmwaa.html

[H02] finally / ensure 收尾
来源：http://dali.daxiang520.top/Article/details/gtcsgztsvg.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jqgfzy.top/Article/details/gtdmtcfhqp.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jinqigfzy.top/Article/details/gtonmbvmrw.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.hfpthk.cn/Article/details/gtgilkwinj.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.cucudq.cn/Article/details/gtuhhlliaw.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.tianlin.xyz/Article/details/gtrqjrpffg.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hnqzz.top/Article/details/gtujlqdgal.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.ivvv.top/Article/details/gtnjmlcobc.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.316326.xyz/Article/details/gtdvrzqahi.html

[H03] 主动抛出异常
来源：http://dali.zhengqikj.top/Article/details/gteppknztf.html

Py:   raise ValueError("错误信息")
来源：http://dali.yj202588.top/Article/details/gtyiupcmqd.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.xziqi.cn/Article/details/gttdqavyjd.html

JS:   throw new Error("错误信息");
来源：http://dali.kuanghao11.cn/Article/details/gtgmuiqhlm.html

TS:   throw new Error("错误信息");
来源：http://dali.jianghu66.top/Article/details/gthhnlwnjm.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.svipenyu.cn/Article/details/gtuxkiuawz.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.mhx1999.top/Article/details/gthwutwxhs.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.cucudq.cn/Article/details/gtkrqqawcz.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.wangdashe.top/Article/details/gtotyszcuq.html

[H04] 自定义异常类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqdbydntb.html

Py:   class MyError(Exception): pass
来源：http://dali.tianlin.xyz/Article/details/gtpxwjqnub.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.sweek.top/Article/details/gtwzqierny.html

JS:   class MyError extends Error {}
来源：http://dali.ppjwa.cn/Article/details/gtsezcwdgv.html

TS:   class MyError extends Error {}
来源：http://dali.yueranfly.top/Article/details/gtqpmmztyy.html

Java: class MyException extends RuntimeException {}
来源：http://dali.feifeiyinyue.top/Article/details/gtzhbjsgte.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.xuetiantiany.cn/Article/details/gtgiacrejf.html

Ruby: class MyError < StandardError; end
来源：http://dali.tanke756.top/Article/details/gtidamtpaq.html

C#:   class MyException : Exception {}
来源：http://dali.cashguo.top/Article/details/gtxjvimtxj.html

[H05] 捕获特定类型
来源：http://dali.ydzc1.top/Article/details/gtczlbjdfy.html

Py:   except ValueError as e:
来源：http://dali.yj202588.top/Article/details/gtjbqsjtok.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.sysykeji.top/Article/details/gttcittbva.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.hammf.cn/Article/details/gtnhzkyxfh.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.gzhubu.top/Article/details/gtjggrtvmf.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtzwpblbrw.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjbizbflv.html

Ruby: rescue ArgumentError => e
来源：http://dali.yj20258888.top/Article/details/gtcpaeilec.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.tian-w.cn/Article/details/gtpdkqhkkb.html

[H06] 可选值 / 空值安全访问
来源：http://dali.daria6918.cn/Article/details/gttoqwqldj.html

Py:   value = d.get("k") or default
来源：http://dali.daria6918.cn/Article/details/gtqgdtoubi.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.tianlin.xyz/Article/details/gtdugsbwhe.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.havefunace.top/Article/details/gtbvpjxkqn.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yueranfly.top/Article/details/gtsrbrpiem.html


<!-- 参考信息 -->