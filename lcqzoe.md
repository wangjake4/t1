代发 wailian999

C#:   File.ReadAllText("a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gtxwsondaj.html

[F02] 逐行读取文件
来源：http://dali.cucudq.cn/Article/details/gtvawlgfre.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.guowangkeji.top/Article/details/gtwpwtilfi.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.9152youxi.cn/Article/details/gtljotnogw.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.sysykeji.top/Article/details/gtogcolkwh.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hnxiangtu.top/Article/details/gtkzeabzux.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yangfankeji.com/Article/details/gtutsuktez.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jinghuilouyu.cn/Article/details/gtseiukefj.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hfpthk.cn/Article/details/gtfnyjyqku.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.feifeiyinyue.top/Article/details/gtefvacfyx.html

[F03] 写入文件（覆盖）
来源：http://dali.hywenlv.cn/Article/details/gtdqkcdflt.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yvedp.cn/Article/details/gtgrpofpqi.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yangfankeji.com/Article/details/gtewqwdsvz.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.pycfn.com/Article/details/gtwdedhuih.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.tian-w.cn/Article/details/gtbceospns.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.andypj.xyz/Article/details/gtvccpyoxz.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.meibo888.top/Article/details/gtiqlexcfj.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.sweek.top/Article/details/gtjoyhqanu.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yuxming.cn/Article/details/gtwicsccaw.html

[F04] 追加写入文件
来源：http://dali.andypj.xyz/Article/details/gtjypeqsue.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.tian-w.cn/Article/details/gtxoktfsbv.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.wangshuangyany.cn/Article/details/gtzrgqdyow.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.kuanghao11.cn/Article/details/gtffiftood.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yvedp.cn/Article/details/gtutxioemg.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hammf.cn/Article/details/gtdtvonysg.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.hysaishi.cn/Article/details/gtbsqncoks.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.xuanzx.com/Article/details/gtxoqvnvvm.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.hywenlv.cn/Article/details/gtqzddgydd.html

[F05] 判断文件或目录是否存在
来源：http://dali.yongpay.top/Article/details/gtoqxdswln.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.fengsongda.top/Article/details/gtmzkrqvui.html

PHP:  file_exists("a.txt");
来源：http://dali.aibaodan.cn/Article/details/gtpccfdmde.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtijkzqimk.html

TS:   fs.existsSync("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtaghzgnbm.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.gogol.net.cn/Article/details/gtodcgauvs.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.gzhubu.top/Article/details/gtrwwxqslm.html

Ruby: File.exist?("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtmuxdxoxf.html

C#:   File.Exists("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtfvpuxdgg.html

[F06] 删除文件
来源：http://dali.jinqigufen.top/Article/details/gtcaiuieau.html

Py:   os.remove("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtkeasokya.html

PHP:  unlink("a.txt");
来源：http://dali.dashuyun.cn/Article/details/gtuhkkvoon.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtgtvibvno.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtkfjegjso.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.sufxvd.cn/Article/details/gtababeakn.html

Go:   os.Remove("a.txt")
来源：http://dali.smart0.xyz/Article/details/gtdokdszbe.html

Ruby: File.delete("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtvxkfkwdu.html

C#:   File.Delete("a.txt");
来源：http://dali.yangfankeji.com/Article/details/gtpkxikkax.html

[F07] 创建目录（含多级）
来源：http://dali.birdmap.top/Article/details/gtnsjrbwim.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.hnqzz.top/Article/details/gtqufrmbvn.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yongpay.top/Article/details/gtdjefuqtj.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.c1oappe.top/Article/details/gtxssjrnns.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.chenjidiqi.icu/Article/details/gtsmggoenq.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.aibaodan.cn/Article/details/gtesasxcdy.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.daria6918.cn/Article/details/gtpiphawkq.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.hammf.cn/Article/details/gtbkblxddn.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.ehwqpu.com/Article/details/gtkmkmleon.html

[F08] 遍历目录
来源：http://dali.jqgufenzy.top/Article/details/gtxwnwegeh.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.9152youxi.cn/Article/details/gtiupijltr.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.316326.xyz/Article/details/gttnexusfj.html

JS:   fs.readdirSync("dir")
来源：http://dali.cashguo.top/Article/details/gtrfndgxpe.html

TS:   fs.readdirSync("dir")
来源：http://dali.guannengcc.top/Article/details/gtvrkisicx.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhongyouzk.top/Article/details/gtankpbfpm.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yj202588.top/Article/details/gtvvpseflh.html

Ruby: Dir.children("dir")
来源：http://dali.hnqzz.top/Article/details/gtnccrfqyf.html

C#:   Directory.GetFiles("dir")
来源：http://dali.ppjwa.cn/Article/details/gtenjvcvqv.html

[F09] 获取文件大小
来源：http://dali.gogol.net.cn/Article/details/gtujhxyzgn.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtoeqoqmrb.html

PHP:  filesize("a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gtsgswjvdx.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yvedp.cn/Article/details/gtbhnbnyxi.html

TS:   fs.statSync("a.txt").size
来源：http://dali.gotoacloud.top/Article/details/gtnvbcjaad.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.dianchejie.cn/Article/details/gtdejjxujt.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.sufxvd.cn/Article/details/gtqaydexxh.html

Ruby: File.size("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtntjwolyb.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhixingplan.top/Article/details/gtqznuwvqb.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jiagoushi.top/Article/details/gtstftgtkm.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yangfankeji.com/Article/details/gthcrfsqje.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.hywenlv.cn/Article/details/gttopunxrf.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtpcnprqaz.html

TS:   path.extname("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtplhuhykq.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.shangyingyoupin.top/Article/details/gthoczqnnl.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtnhxpycfp.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtzmlvbiki.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtpkmsdtyt.html

[F11] 复制与移动文件
来源：http://dali.zhengqikj.top/Article/details/gtfbdnqdar.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yueranfly.top/Article/details/gtjjsxdbfk.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gtjbmvvdma.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xylfe.cn/Article/details/gtysrfivuy.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xinyue.icu/Article/details/gtmmxwbbwb.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jiagoushi.top/Article/details/gtutrtihui.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ppjwa.cn/Article/details/gtlzsvbkdg.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtzmfqysoj.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.hysaishi.cn/Article/details/gtlsjugfol.html

[F12] CSV 读写
来源：http://dali.yj202588.top/Article/details/gtiwvtcpqc.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.redwolf501.top/Article/details/gtkuxexfhc.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.feifeiyinyue.top/Article/details/gtmemqpyyq.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.gaohongyu789.top/Article/details/gtmypkpcgc.html

TS:   // 同上
来源：http://dali.shzxlz.cn/Article/details/gtdhfwldjg.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jqgufenzy.top/Article/details/gtesujyywk.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.chenzaomai.com/Article/details/gtdopsylkl.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.cucudq.cn/Article/details/gtdcxfmolf.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jinqigufen.top/Article/details/gtmxzwqruo.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtqezslkgv.html

G. 面向对象
来源：http://dali.yangfankeji.com/Article/details/gtrlyrhuvq.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtjylpzbwh.html

[G01] 定义类
来源：http://dali.xuanzx.com/Article/details/gtibwuerrf.html

Py:   class User: pass
来源：http://dali.yanxiufei.cn/Article/details/gtcvitxprc.html

PHP:  class User {}
来源：http://dali.guannengcc.top/Article/details/gtzjiomevy.html

JS:   class User {}
来源：http://dali.gzhubu.top/Article/details/gtdalklbas.html

TS:   class User { name: string = ""; }
来源：http://dali.smart0.xyz/Article/details/gtekilwnpn.html

Java: class User {}
来源：http://dali.yvedp.cn/Article/details/gtkkiogjjd.html

Go:   type User struct { Name string }
来源：http://dali.chenjidiqi.icu/Article/details/gtrkxbopct.html

Ruby: class User; end
来源：http://dali.fzhhl.top/Article/details/gtdttgvjsz.html

C#:   class User {}
来源：http://dali.andypj.xyz/Article/details/gtqrlppraf.html

[G02] 构造函数
来源：http://dali.svipenyu.cn/Article/details/gtrvugnybk.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.ehwqpu.com/Article/details/gtyqnyjtiu.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.chenzaomai.com/Article/details/gtwiunhghs.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yj20258888.top/Article/details/gtojpncjxj.html

TS:   constructor(public name: string) {}
来源：http://dali.xylfe.cn/Article/details/gtzmxfpkru.html

Java: User(String name) { this.name = name; }
来源：http://dali.ehwqpu.com/Article/details/gtxajluozt.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.316326.xyz/Article/details/gtuemwlmfi.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hongshengwenyu.top/Article/details/gtcykdwnqo.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jyoumei.cn/Article/details/gtmkflwfjx.html

[G03] 实例属性
来源：http://dali.daria6918.cn/Article/details/gtijqtahdn.html

Py:   self.name = "x"
来源：http://dali.hnxiangtu.top/Article/details/gtylembvgq.html

PHP:  public string $name = "x";
来源：http://dali.haohaochexian.top/Article/details/gtyunshkxq.html

JS:   this.name = "x";
来源：http://dali.daria6918.cn/Article/details/gtikdbxypu.html

TS:   name: string = "x";
来源：http://dali.nwbrower.top/Article/details/gtuiabgjiv.html

Java: private String name;
来源：http://dali.zhiwuduotai.top/Article/details/gtcfdwonex.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.gzhubu.top/Article/details/gtbunuyqti.html

Ruby: @name = "x"
来源：http://dali.pengpengdd.cyou/Article/details/gttuqncjzi.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jqgufenzy.top/Article/details/gthovwxfjb.html

[G04] 定义方法
来源：http://dali.jqgfzy.top/Article/details/gtnxuvcjpj.html

Py:   def greet(self): return self.name
来源：http://dali.hysaishi.cn/Article/details/gtcnzjdacv.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.smart0.xyz/Article/details/gtknyjjwhm.html

JS:   greet() { return this.name; }
来源：http://dali.cashguo.top/Article/details/gtjapiaiyw.html

TS:   greet(): string { return this.name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlmhhqqvx.html

Java: String greet() { return name; }
来源：http://dali.ydzc1.top/Article/details/gtajkgkzce.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hammf.cn/Article/details/gterwhoxws.html

Ruby: def greet; @name; end
来源：http://dali.mhx1999.top/Article/details/gtwyiwyjdv.html

C#:   public string Greet() => Name;
来源：http://dali.9152youxi.cn/Article/details/gtcyudbbzs.html

[G05] 继承
来源：http://dali.daria6918.cn/Article/details/gtxxoempjr.html

Py:   class Admin(User): pass
来源：http://dali.yuanzhike.top/Article/details/gtgylzhjdp.html

PHP:  class Admin extends User {}
来源：http://dali.quarkkingdee.top/Article/details/gtuopffodv.html

JS:   class Admin extends User {}
来源：http://dali.ppjwa.cn/Article/details/gtohdkyegf.html

TS:   class Admin extends User {}
来源：http://dali.jyoumei.cn/Article/details/gtievkpyfc.html

Java: class Admin extends User {}
来源：http://dali.jiagoushi.top/Article/details/gtinkzarkz.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.tian-w.cn/Article/details/gtymmwjknk.html

Ruby: class Admin < User; end
来源：http://dali.xylfe.cn/Article/details/gtatmkpcdf.html

C#:   class Admin : User {}
来源：http://dali.gaohongyu789.top/Article/details/gtsaorekca.html

[G06] 重写方法
来源：http://dali.iojbl.cn/Article/details/gtxoheazfq.html

Py:   def greet(self): return "admin"
来源：http://dali.guannengcc.top/Article/details/gtvzqqnfqq.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hammf.cn/Article/details/gtweuhxyyn.html

JS:   greet() { return "admin"; }
来源：http://dali.smart0.xyz/Article/details/gtlduzxcdd.html

TS:   greet(): string { return "admin"; }
来源：http://dali.nanxuanxn.top/Article/details/gtnoewomwv.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.fzhhl.top/Article/details/gteishomhx.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.cucudq.cn/Article/details/gtdavbgzhv.html

Ruby: def greet; "admin"; end
来源：http://dali.meibo888.top/Article/details/gtpdriqjbr.html

C#:   public override string Greet() => "admin";
来源：http://dali.jianghu66.top/Article/details/gtvrprpmej.html

[G07] 调用父类方法
来源：http://dali.vqdsnc.cn/Article/details/gtlvkzktcj.html

Py:   super().greet()
来源：http://dali.jqgfzy.top/Article/details/gthconseek.html

PHP:  parent::greet();
来源：http://dali.c1oappe.top/Article/details/gtsfwxvqvs.html

JS:   super.greet();
来源：http://dali.jyoumei.cn/Article/details/gtbepnezue.html

TS:   super.greet();
来源：http://dali.xinyue.icu/Article/details/gtgzpavwfi.html

Java: super.greet();
来源：http://dali.ivvv.top/Article/details/gtpnzhgpzo.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.shanyushiyangtech.top/Article/details/gtlggdmcqi.html

Ruby: super
来源：http://dali.jyoumei.cn/Article/details/gteztmhmhw.html

C#:   base.Greet();
来源：http://dali.quarkkingdee.top/Article/details/gtiybhrojs.html

[G08] 静态方法与属性
来源：http://dali.yvedp.cn/Article/details/gtkgugescf.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.svipenyu.cn/Article/details/gtqngbpqnd.html

PHP:  public static function f() {}
来源：http://dali.sufxvd.cn/Article/details/gtvngcrbxa.html

JS:   static f() {}
来源：http://dali.zhongyouzk.top/Article/details/gtrgasqedz.html

TS:   static f(): void {}
来源：http://dali.jinqigfzy.top/Article/details/gtmcgqtvdc.html

Java: static void f() {}
来源：http://dali.aibaodan.cn/Article/details/gtipljybfe.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.xuanzx.com/Article/details/gtxfebuhya.html

Ruby: def self.f; end
来源：http://dali.mhx1999.top/Article/details/gtymfdjsow.html

C#:   public static void F() {}
来源：http://dali.yj20258888.top/Article/details/gtkglanvsv.html

[G09] 接口 / 抽象类
来源：http://dali.yangfankeji.com/Article/details/gtnwxxmgug.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.ehwqpu.com/Article/details/gtnaiakfdq.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.chenjidiqi.icu/Article/details/gtnmidmnwb.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.sweek.top/Article/details/gtccggdswo.html

TS:   interface Shape { area(): number; }
来源：http://dali.sweek.top/Article/details/gtvlvydvmx.html

Java: interface Shape { double area(); }
来源：http://dali.xuanzx.com/Article/details/gtvqdhydfd.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.xuetiantiany.cn/Article/details/gtpblvrxsp.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.fzhhl.top/Article/details/gtxniuluoo.html

C#:   interface IShape { double Area(); }
来源：http://dali.redwolf501.top/Article/details/gtvorhydhz.html

[G10] 访问控制
来源：http://dali.ivvv.top/Article/details/gtwndxepdq.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yueranfly.top/Article/details/gtoxjrlrtm.html

PHP:  public / protected / private
来源：http://dali.feifeiyinyue.top/Article/details/gtdnreblnk.html

JS:   #private 字段；其余公开
来源：http://dali.yuanzhike.top/Article/details/gtvajdlasr.html

TS:   public / protected / private
来源：http://dali.hfpthk.cn/Article/details/gtojgpyxey.html

Java: public / protected / private / 默认包级
来源：http://dali.yj202588.top/Article/details/gticbfrdaj.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.sufxvd.cn/Article/details/gtlfjrtbfp.html

Ruby: public / protected / private
来源：http://dali.hywenlv.cn/Article/details/gtmatuifre.html

C#:   public / protected / private / internal
来源：http://dali.zycfv.cn/Article/details/gtddvonvga.html

[G11] getter / setter
来源：http://dali.jinghuilouyu.cn/Article/details/gthnbwnnxo.html

Py:   @property 与 @x.setter
来源：http://dali.jianghu66.top/Article/details/gtwxaiwtvj.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.hammf.cn/Article/details/gtwqbsclgc.html

JS:   get name() { return this._name; }
来源：http://dali.9152youxi.cn/Article/details/gtpgtoozzv.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhixingplan.top/Article/details/gtqozelxxg.html

Java: public String getName() { return name; }
来源：http://dali.wangdashe.top/Article/details/gtfpkhkszr.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.aizwys.cn/Article/details/gtkxegsfdr.html

Ruby: attr_accessor :name
来源：http://dali.aizwys.cn/Article/details/gtwnsdriin.html

C#:   public string Name { get; set; }
来源：http://dali.birdmap.top/Article/details/gtmbnzcrit.html

[G12] 对象转字符串
来源：http://dali.gzhubu.top/Article/details/gthbpasviy.html

Py:   def __str__(self): return self.name
来源：http://dali.hnqzz.top/Article/details/gtczkzfyui.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtuojeerrq.html

JS:   toString() { return this.name; }
来源：http://dali.hfpthk.cn/Article/details/gtoyfriylx.html

TS:   toString(): string { return this.name; }
来源：http://dali.nanxuanxn.top/Article/details/gtivvdtsam.html

Java: @Override public String toString() { return name; }
来源：http://dali.sysykeji.top/Article/details/gtgzhjnjfx.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yj20258888.top/Article/details/gtzaewsfkw.html

Ruby: def to_s; @name; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrhbnmzom.html

C#:   public override string ToString() => Name;
来源：http://dali.mhx1999.top/Article/details/gtortpvkrg.html

[G13] 判断对象类型
来源：http://dali.dianchejie.cn/Article/details/gtolddrese.html

Py:   isinstance(u, User)
来源：http://dali.kuanghao11.cn/Article/details/gthqwvdnqq.html

PHP:  $u instanceof User
来源：http://dali.aibaodan.cn/Article/details/gtfxzdyhih.html

JS:   u instanceof User
来源：http://dali.yvedp.cn/Article/details/gtogreqwmo.html

TS:   u instanceof User
来源：http://dali.gotoacloud.top/Article/details/gtoholqiji.html

Java: u instanceof User
来源：http://dali.xziqi.cn/Article/details/gtgnmfxrct.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yj20258.top/Article/details/gtnpffaadc.html

Ruby: u.is_a?(User)
来源：http://dali.yj202588.top/Article/details/gtnvgvzvno.html

C#:   u is User
来源：http://dali.jinghuilouyu.cn/Article/details/gtvqyntjyl.html

[G14] 数据类 / record
来源：http://dali.gogol.net.cn/Article/details/gtpzahngff.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.pengpengdd.cyou/Article/details/gtmlqrrmsf.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.ydzc1.top/Article/details/gttmbjntoq.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.cqqwz.cn/Article/details/gtagintagi.html

TS:   type User = { name: string; age: number };
来源：http://dali.0kj1m.cn/Article/details/gtrqhsrnju.html

Java: record User(String name, int age) {}
来源：http://dali.cheryme.top/Article/details/gttrauwlug.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zdqjudy.top/Article/details/gtrqthbasw.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.gogol.net.cn/Article/details/gtgwkpucoy.html

C#:   record User(string Name, int Age);
来源：http://dali.zhijiandao.cn/Article/details/gtcoctuyie.html

[G15] 枚举
来源：http://dali.zhaomingkeji.xyz/Article/details/gtppvycttd.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.tian-w.cn/Article/details/gtzsdnfycq.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yueranfly.top/Article/details/gtuvuyvhgf.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.tianlin.xyz/Article/details/gtnmekdhrx.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sysykeji.top/Article/details/gtkklbffyc.html

Java: enum Color { RED, GREEN }
来源：http://dali.yongpay.top/Article/details/gtamusyseg.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jinghuilouyu.cn/Article/details/gtcmcdyesx.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yvedp.cn/Article/details/gtzuygdbsm.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.chenzaomai.com/Article/details/gtzyqznxnf.html

[G16] 对象转数组 / 字典
来源：http://dali.jqgufenzy.top/Article/details/gtyhskqtpz.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.kuanghao11.cn/Article/details/gtdyvpmdto.html

PHP:  get_object_vars($obj);
来源：http://dali.yj202588.top/Article/details/gtvcnxcymi.html

JS:   Object.entries(obj)
来源：http://dali.hfpthk.cn/Article/details/gtarhvkcye.html

TS:   Object.entries(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gtkipnardy.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.bjfxy.top/Article/details/gttmukpcui.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.cdnleiting.top/Article/details/gtzxcqdwmw.html

Ruby: obj.instance_variables
来源：http://dali.zhongyouzk.top/Article/details/gtoxbhbtpz.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jyoumei.cn/Article/details/gtrqpdefvu.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtmitmejxr.html

H. 异常与错误处理
来源：http://dali.ppjwa.cn/Article/details/gtqfzkydoh.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtxtkvsjwd.html

[H01] try / catch 基础
来源：http://dali.nwbrower.top/Article/details/gtwtrxinci.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.bjfxy.top/Article/details/gtxkungqla.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.bjfxy.top/Article/details/gtgknimipc.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jinqigufen.top/Article/details/gtetpgfuoe.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.tianlin.xyz/Article/details/gtrqpnjwmp.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yj20258888.top/Article/details/gtznvfmudz.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yj20258888.top/Article/details/gtzbjhybxr.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.cdnleiting.top/Article/details/gtzsmbzutx.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfvsmknqe.html

[H02] finally / ensure 收尾
来源：http://dali.yueranfly.top/Article/details/gtmjnyzwri.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.chenlongwang.top/Article/details/gtxnycrlge.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.316326.xyz/Article/details/gtoaiblaga.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.haohaochexian.top/Article/details/gtgyogwaat.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinqigufen.top/Article/details/gtxeewkzoc.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.shzxlz.cn/Article/details/gtmouwpqus.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.316326.xyz/Article/details/gtahholcnz.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.cucudq.cn/Article/details/gtozfjdixy.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.ehwqpu.com/Article/details/gtabhxrixs.html

[H03] 主动抛出异常
来源：http://dali.haohaochexian.top/Article/details/gthaoaibdw.html

Py:   raise ValueError("错误信息")
来源：http://dali.gotoacloud.top/Article/details/gtscnxuina.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yuanzhike.top/Article/details/gtlhzqwxaq.html

JS:   throw new Error("错误信息");
来源：http://dali.pycfn.com/Article/details/gtiooljkmy.html

TS:   throw new Error("错误信息");
来源：http://dali.xylfe.cn/Article/details/gtwdwrsicd.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.gzhubu.top/Article/details/gtyuvzmldm.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.pycfn.com/Article/details/gtuvvftyoq.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.ydzc1.top/Article/details/gtkgnyblmw.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jinqigufen.top/Article/details/gtschntrlg.html

[H04] 自定义异常类型
来源：http://dali.guowangkeji.top/Article/details/gttdifgixt.html

Py:   class MyError(Exception): pass
来源：http://dali.xylfe.cn/Article/details/gtkoljrvbo.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.wangdashe.top/Article/details/gtdqqcfbyu.html

JS:   class MyError extends Error {}
来源：http://dali.9152youxi.cn/Article/details/gteiovijbd.html

TS:   class MyError extends Error {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtozigmjbq.html

Java: class MyException extends RuntimeException {}
来源：http://dali.cheryme.top/Article/details/gtlwhhawyn.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.shzxlz.cn/Article/details/gtichkvdwf.html

Ruby: class MyError < StandardError; end
来源：http://dali.tianlin.xyz/Article/details/gtfvnctvft.html

C#:   class MyException : Exception {}
来源：http://dali.wangdashe.top/Article/details/gtxnssdbcc.html

[H05] 捕获特定类型
来源：http://dali.hammf.cn/Article/details/gtunsjaldt.html

Py:   except ValueError as e:
来源：http://dali.daxiang520.top/Article/details/gtghdstpam.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.shangyingyoupin.top/Article/details/gtighdjzyn.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.snrcjt.cn/Article/details/gtshgeigif.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gthmnqljpw.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.pycfn.com/Article/details/gtzkdaqogz.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.nanxinkj.top/Article/details/gtnipzbhie.html

Ruby: rescue ArgumentError => e
来源：http://dali.cucudq.cn/Article/details/gtuhecwumw.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.vqdsnc.cn/Article/details/gtghzafevd.html

[H06] 可选值 / 空值安全访问
来源：http://dali.iojbl.cn/Article/details/gtofryemyi.html

Py:   value = d.get("k") or default
来源：http://dali.hfpthk.cn/Article/details/gtkgprndne.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yj20258.top/Article/details/gteydjtoya.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdrvektaf.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhijiandao.cn/Article/details/gtejkhcewh.html


<!-- 参考信息 -->