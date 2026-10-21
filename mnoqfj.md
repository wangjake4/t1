代发 wailian999

C#:   File.ReadAllText("a.txt");
来源：http://dali.gzhubu.top/Article/details/gtwavpjkmh.html

[F02] 逐行读取文件
来源：http://dali.yueranfly.top/Article/details/gtutghcviu.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.hysaishi.cn/Article/details/gtkijcnugs.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.feifeiyinyue.top/Article/details/gtucsypfjv.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hywenlv.cn/Article/details/gtrvxeeglb.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.redwolf501.top/Article/details/gtdwvofkxy.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.nanxinkj.top/Article/details/gtnwfuscty.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.ydzc1.top/Article/details/gtlmqvlkft.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.tanke756.top/Article/details/gtqmbrlcul.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jinqigfzy.top/Article/details/gtftriiasy.html

[F03] 写入文件（覆盖）
来源：http://dali.yueranfly.top/Article/details/gtnhwvglji.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.nanxinkj.top/Article/details/gtrbzricxq.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.andypj.xyz/Article/details/gtukrsuups.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xziqi.cn/Article/details/gtdbisbaib.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnfuywgsz.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcopdtfkj.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yangfankeji.com/Article/details/gtcknfamwi.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.guowangkeji.top/Article/details/gtgbymykul.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zycfv.cn/Article/details/gtyjfccgsh.html

[F04] 追加写入文件
来源：http://dali.shzxlz.cn/Article/details/gtsroqkxsn.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.ppjwa.cn/Article/details/gtnptzebtj.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.shzxlz.cn/Article/details/gtlnvhvksa.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhiwuduotai.top/Article/details/gtlllviodv.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yj20258.top/Article/details/gtjcepdchq.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.gzhubu.top/Article/details/gtiihosikm.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.ybcxt.top/Article/details/gtruoppiqa.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhongyouzk.top/Article/details/gtrlbifqnm.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jinghuilouyu.cn/Article/details/gtlyuuatka.html

[F05] 判断文件或目录是否存在
来源：http://dali.feifeiyinyue.top/Article/details/gtytmmrlry.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.gogol.net.cn/Article/details/gtamfhmpdw.html

PHP:  file_exists("a.txt");
来源：http://dali.smart0.xyz/Article/details/gtelfwiglw.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtnueyrukz.html

TS:   fs.existsSync("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtepfgojaa.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yongpay.top/Article/details/gtppvwbsor.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jinghuilouyu.cn/Article/details/gtgfvlljin.html

Ruby: File.exist?("a.txt")
来源：http://dali.yongpay.top/Article/details/gtjsmgopqs.html

C#:   File.Exists("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtbovbbcvk.html

[F06] 删除文件
来源：http://dali.havefunace.top/Article/details/gtbydcblum.html

Py:   os.remove("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtqbvbpmwi.html

PHP:  unlink("a.txt");
来源：http://dali.sweek.top/Article/details/gttglplecf.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtmisnifbe.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gturmydofc.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.xziqi.cn/Article/details/gtppqswmnj.html

Go:   os.Remove("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtrqceeszz.html

Ruby: File.delete("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtyzolqixs.html

C#:   File.Delete("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gtbonxtxah.html

[F07] 创建目录（含多级）
来源：http://dali.cdnleiting.top/Article/details/gtquxafznw.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.hfpthk.cn/Article/details/gtpovsxybn.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtelsohnpx.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhixingplan.top/Article/details/gtkqenxgmi.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hywenlv.cn/Article/details/gtijeuzhmb.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.xziqi.cn/Article/details/gtjbovlgvj.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.chenjidiqi.icu/Article/details/gtkonftwyl.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zdqjudy.top/Article/details/gtcummkeaf.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yongpay.top/Article/details/gtzycjmgtw.html

[F08] 遍历目录
来源：http://dali.smart0.xyz/Article/details/gtdghualej.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.svipenyu.cn/Article/details/gtmhupbhoa.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jyoumei.cn/Article/details/gtczonziac.html

JS:   fs.readdirSync("dir")
来源：http://dali.guannengcc.top/Article/details/gtyuktzetl.html

TS:   fs.readdirSync("dir")
来源：http://dali.hfpthk.cn/Article/details/gtpwzarfwo.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hnxiangtu.top/Article/details/gthmcpsztt.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhoulong.xyz/Article/details/gthnnxbrjb.html

Ruby: Dir.children("dir")
来源：http://dali.gaohongyu789.top/Article/details/gtqcivcaxm.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yuxming.cn/Article/details/gtbmuvzzol.html

[F09] 获取文件大小
来源：http://dali.yuxming.cn/Article/details/gtsiqtgysl.html

Py:   os.path.getsize("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtmloeaaaj.html

PHP:  filesize("a.txt");
来源：http://dali.hnqzz.top/Article/details/gtknaokwqp.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhiwuduotai.top/Article/details/gtaiwvldid.html

TS:   fs.statSync("a.txt").size
来源：http://dali.shuidangran.top/Article/details/gtkjoaevsr.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.quarkkingdee.top/Article/details/gtlgaoxiyj.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.guowangkeji.top/Article/details/gtravjzyqc.html

Ruby: File.size("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtyznkkrwr.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jinqigufen.top/Article/details/gtmeotlpad.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.nwbrower.top/Article/details/gtdtggqron.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtmjdsuqea.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gtrxwbxhsq.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.xinyue.icu/Article/details/gtmrvxqdmy.html

TS:   path.extname("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtljakzkgc.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hnxiangtu.top/Article/details/gtxsfppqll.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtxklqbvmk.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtwsmuyyac.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.xinyue.icu/Article/details/gtqjzevfie.html

[F11] 复制与移动文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtjkxljnlc.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.xinyue.icu/Article/details/gtridhfpcf.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gttycfbvqk.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ydzc1.top/Article/details/gtwltickbd.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yj20258888.top/Article/details/gtbyqiitjv.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jianghu66.top/Article/details/gtgwsmnyie.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.c1oappe.top/Article/details/gtrbgucahy.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.ppjwa.cn/Article/details/gtbfdugrxy.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhengqikj.top/Article/details/gtuudqnnow.html

[F12] CSV 读写
来源：http://dali.shzxlz.cn/Article/details/gtesafsfgi.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zycfv.cn/Article/details/gtgjqqblgr.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.meibo888.top/Article/details/gtiwyxvprm.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.shzxlz.cn/Article/details/gtzguobevj.html

TS:   // 同上
来源：http://dali.shangyingyoupin.top/Article/details/gtbciwugob.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hongshengwenyu.top/Article/details/gtkylghayj.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.sufxvd.cn/Article/details/gtaboyjzfc.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.gaohongyu789.top/Article/details/gtvjwkewcz.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yvedp.cn/Article/details/gtgkfhyszo.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtqwuaxfjg.html

G. 面向对象
来源：http://dali.sxryk.cn/Article/details/gtetdilzcu.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gttmypkibc.html

[G01] 定义类
来源：http://dali.fzhhl.top/Article/details/gtrareuxkw.html

Py:   class User: pass
来源：http://dali.sysykeji.top/Article/details/gtpokmdxem.html

PHP:  class User {}
来源：http://dali.nanxinkj.top/Article/details/gtouuhujra.html

JS:   class User {}
来源：http://dali.dianchejie.cn/Article/details/gtcooasemo.html

TS:   class User { name: string = ""; }
来源：http://dali.yj20258.top/Article/details/gtigcvmpzg.html

Java: class User {}
来源：http://dali.cqqwz.cn/Article/details/gtpzbkdcgk.html

Go:   type User struct { Name string }
来源：http://dali.ydzc1.top/Article/details/gthcfmggbr.html

Ruby: class User; end
来源：http://dali.iojbl.cn/Article/details/gtjfhjavnn.html

C#:   class User {}
来源：http://dali.9152youxi.cn/Article/details/gtwjrlbqzl.html

[G02] 构造函数
来源：http://dali.cheryme.top/Article/details/gtzgyxblej.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.aibaodan.cn/Article/details/gtcgjaavcj.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jqgfzy.top/Article/details/gtuhuxuinj.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.chenzaomai.com/Article/details/gtgwtvjrzs.html

TS:   constructor(public name: string) {}
来源：http://dali.jinqigfzy.top/Article/details/gttihwcgde.html

Java: User(String name) { this.name = name; }
来源：http://dali.cheryme.top/Article/details/gthcmvihgp.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.havefunace.top/Article/details/gtlrgboegk.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.tianlin.xyz/Article/details/gtvvarsuon.html

C#:   public User(string name) { Name = name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtwsepzgsx.html

[G03] 实例属性
来源：http://dali.ivvv.top/Article/details/gtaktljlkh.html

Py:   self.name = "x"
来源：http://dali.guowangkeji.top/Article/details/gtxjatpbrh.html

PHP:  public string $name = "x";
来源：http://dali.nwbrower.top/Article/details/gtvxxvhzfy.html

JS:   this.name = "x";
来源：http://dali.guowangkeji.top/Article/details/gtorxjvfqs.html

TS:   name: string = "x";
来源：http://dali.jyoumei.cn/Article/details/gtxitbswrg.html

Java: private String name;
来源：http://dali.shuidangran.top/Article/details/gtuvgucnfd.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.cashguo.top/Article/details/gtntjdxxsg.html

Ruby: @name = "x"
来源：http://dali.zhongyouzk.top/Article/details/gthutwdbws.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbrlyawad.html

[G04] 定义方法
来源：http://dali.meibo888.top/Article/details/gtoolathub.html

Py:   def greet(self): return self.name
来源：http://dali.hongshengwenyu.top/Article/details/gtegrqudzy.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.tanke756.top/Article/details/gtlrjxcidc.html

JS:   greet() { return this.name; }
来源：http://dali.gaohongyu789.top/Article/details/gtdkblxsll.html

TS:   greet(): string { return this.name; }
来源：http://dali.ppjwa.cn/Article/details/gtubvnsnqm.html

Java: String greet() { return name; }
来源：http://dali.yongpay.top/Article/details/gtwcybvses.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.aizwys.cn/Article/details/gtyxfbhpmr.html

Ruby: def greet; @name; end
来源：http://dali.xziqi.cn/Article/details/gtyzyvgjrw.html

C#:   public string Greet() => Name;
来源：http://dali.cqqwz.cn/Article/details/gtzxtutqzh.html

[G05] 继承
来源：http://dali.yongpay.top/Article/details/gtpzvfiuet.html

Py:   class Admin(User): pass
来源：http://dali.wangshuangyany.cn/Article/details/gtzwkwpyjs.html

PHP:  class Admin extends User {}
来源：http://dali.tianlin.xyz/Article/details/gtgrcrntkw.html

JS:   class Admin extends User {}
来源：http://dali.jqgufenzy.top/Article/details/gtxrymbhpc.html

TS:   class Admin extends User {}
来源：http://dali.hongshengwenyu.top/Article/details/gtrzwlcqqm.html

Java: class Admin extends User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvvkzxoom.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.nwbrower.top/Article/details/gtpefebhlk.html

Ruby: class Admin < User; end
来源：http://dali.feifeiyinyue.top/Article/details/gthaiafhzr.html

C#:   class Admin : User {}
来源：http://dali.zdqjudy.top/Article/details/gtviiomrit.html

[G06] 重写方法
来源：http://dali.cucudq.cn/Article/details/gtnozmnxlb.html

Py:   def greet(self): return "admin"
来源：http://dali.zhixingplan.top/Article/details/gtzgdzwtoz.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.svipenyu.cn/Article/details/gtmiyazxnf.html

JS:   greet() { return "admin"; }
来源：http://dali.meibo888.top/Article/details/gtqtdrdwfh.html

TS:   greet(): string { return "admin"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtifukuazz.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhongyouzk.top/Article/details/gthfhdrakg.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.sufxvd.cn/Article/details/gtelgxzpls.html

Ruby: def greet; "admin"; end
来源：http://dali.pengpengdd.cyou/Article/details/gtduljuhpl.html

C#:   public override string Greet() => "admin";
来源：http://dali.yangfankeji.com/Article/details/gtwhsncdee.html

[G07] 调用父类方法
来源：http://dali.havefunace.top/Article/details/gtsorpoqla.html

Py:   super().greet()
来源：http://dali.bjfxy.top/Article/details/gtgplpaahd.html

PHP:  parent::greet();
来源：http://dali.0kj1m.cn/Article/details/gtzdpwsdxp.html

JS:   super.greet();
来源：http://dali.yongpay.top/Article/details/gtdnjirxpt.html

TS:   super.greet();
来源：http://dali.jqgufenzy.top/Article/details/gtoucqtohm.html

Java: super.greet();
来源：http://dali.0kj1m.cn/Article/details/gtcovfaofx.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.aizwys.cn/Article/details/gtofpjawbp.html

Ruby: super
来源：http://dali.bjfxy.top/Article/details/gtllgxytwg.html

C#:   base.Greet();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrdtmtzpa.html

[G08] 静态方法与属性
来源：http://dali.tanke756.top/Article/details/gtxiiucyvf.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.shuidangran.top/Article/details/gttpiykfim.html

PHP:  public static function f() {}
来源：http://dali.cucudq.cn/Article/details/gtdiqxjabi.html

JS:   static f() {}
来源：http://dali.hywenlv.cn/Article/details/gtsylulgyq.html

TS:   static f(): void {}
来源：http://dali.yueranfly.top/Article/details/gtcsgmzvxz.html

Java: static void f() {}
来源：http://dali.hywenlv.cn/Article/details/gtkaqklmey.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.shuidangran.top/Article/details/gtmjzzexsh.html

Ruby: def self.f; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtzcoldfwi.html

C#:   public static void F() {}
来源：http://dali.cqqwz.cn/Article/details/gtafysjmah.html

[G09] 接口 / 抽象类
来源：http://dali.guowangkeji.top/Article/details/gtnqhpedzu.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jqgfzy.top/Article/details/gtwkxqqckc.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.daxiang520.top/Article/details/gtunvmqimq.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.kuanghao11.cn/Article/details/gtxayebuyn.html

TS:   interface Shape { area(): number; }
来源：http://dali.yuanzhike.top/Article/details/gtivomkwvv.html

Java: interface Shape { double area(); }
来源：http://dali.dashuyun.cn/Article/details/gtghwptnfg.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.cashguo.top/Article/details/gtopigkhfu.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yvedp.cn/Article/details/gtdvrzvnzb.html

C#:   interface IShape { double Area(); }
来源：http://dali.shuidangran.top/Article/details/gteeffjkah.html

[G10] 访问控制
来源：http://dali.xinyue.icu/Article/details/gtolbavaec.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzphywdlh.html

PHP:  public / protected / private
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxhmykdzy.html

JS:   #private 字段；其余公开
来源：http://dali.xinyue.icu/Article/details/gtpxpnpame.html

TS:   public / protected / private
来源：http://dali.shzxlz.cn/Article/details/gtztgqbjwz.html

Java: public / protected / private / 默认包级
来源：http://dali.smart0.xyz/Article/details/gtlbrhbcso.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jyoumei.cn/Article/details/gtdoujymff.html

Ruby: public / protected / private
来源：http://dali.dianchejie.cn/Article/details/gtwjyiffpt.html

C#:   public / protected / private / internal
来源：http://dali.ybcxt.top/Article/details/gtcifvsdwx.html

[G11] getter / setter
来源：http://dali.zhengqikj.top/Article/details/gtpbvudfbb.html

Py:   @property 与 @x.setter
来源：http://dali.sysykeji.top/Article/details/gtafaviwjp.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxrqabxdf.html

JS:   get name() { return this._name; }
来源：http://dali.jiagoushi.top/Article/details/gtbkpsectr.html

TS:   get name(): string { return this._name; }
来源：http://dali.aibaodan.cn/Article/details/gtqsctrncv.html

Java: public String getName() { return name; }
来源：http://dali.zdqjudy.top/Article/details/gtavqimjjo.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.sweek.top/Article/details/gtvkvvafnj.html

Ruby: attr_accessor :name
来源：http://dali.tian-w.cn/Article/details/gtmxnhkswh.html

C#:   public string Name { get; set; }
来源：http://dali.gogol.net.cn/Article/details/gtjjkrjlou.html

[G12] 对象转字符串
来源：http://dali.sxryk.cn/Article/details/gtqqqzgflg.html

Py:   def __str__(self): return self.name
来源：http://dali.9152youxi.cn/Article/details/gtefqzjycr.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yuxming.cn/Article/details/gthcvbgvid.html

JS:   toString() { return this.name; }
来源：http://dali.haohaochexian.top/Article/details/gtjphxhvll.html

TS:   toString(): string { return this.name; }
来源：http://dali.hnxiangtu.top/Article/details/gtltrtedhw.html

Java: @Override public String toString() { return name; }
来源：http://dali.sufxvd.cn/Article/details/gtnypyfcgs.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhixingplan.top/Article/details/gtrybvardg.html

Ruby: def to_s; @name; end
来源：http://dali.nwbrower.top/Article/details/gtbxmxnfqk.html

C#:   public override string ToString() => Name;
来源：http://dali.yuanzhike.top/Article/details/gteopjawln.html

[G13] 判断对象类型
来源：http://dali.9152youxi.cn/Article/details/gtclsshfnu.html

Py:   isinstance(u, User)
来源：http://dali.zhengqikj.top/Article/details/gtwlznzhfw.html

PHP:  $u instanceof User
来源：http://dali.chenzaomai.com/Article/details/gtpmonwkie.html

JS:   u instanceof User
来源：http://dali.xuetiantiany.cn/Article/details/gtyiwwbiiz.html

TS:   u instanceof User
来源：http://dali.daxiang520.top/Article/details/gtayyymezh.html

Java: u instanceof User
来源：http://dali.aizwys.cn/Article/details/gtiyqjifny.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yj20258.top/Article/details/gtxvclmioz.html

Ruby: u.is_a?(User)
来源：http://dali.yongpay.top/Article/details/gthbivlpbw.html

C#:   u is User
来源：http://dali.316326.xyz/Article/details/gtsivfujmz.html

[G14] 数据类 / record
来源：http://dali.nwbrower.top/Article/details/gtegerprtk.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.0kj1m.cn/Article/details/gtkejnbmci.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.shzxlz.cn/Article/details/gtvlreljgm.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.nanxinkj.top/Article/details/gtqhmazeie.html

TS:   type User = { name: string; age: number };
来源：http://dali.fengsongda.top/Article/details/gttpfaycrg.html

Java: record User(String name, int age) {}
来源：http://dali.ehwqpu.com/Article/details/gtyzjqroxd.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yueranfly.top/Article/details/gttjkowhrv.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.shzxlz.cn/Article/details/gtcdtdkkiv.html

C#:   record User(string Name, int Age);
来源：http://dali.hysaishi.cn/Article/details/gtgtrgbmik.html

[G15] 枚举
来源：http://dali.sufxvd.cn/Article/details/gtuyfykihn.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jinqigufen.top/Article/details/gtfgheveso.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.nwbrower.top/Article/details/gtcnilozgz.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jqgfzy.top/Article/details/gtqjawfahb.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xinyue.icu/Article/details/gtluoqarpq.html

Java: enum Color { RED, GREEN }
来源：http://dali.yj20258.top/Article/details/gtwjcmnrvs.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zdqjudy.top/Article/details/gticejvcxi.html

Ruby: Color = %i[red green].freeze
来源：http://dali.hammf.cn/Article/details/gtysxhzdac.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.bjfxy.top/Article/details/gttmmjcqpo.html

[G16] 对象转数组 / 字典
来源：http://dali.c1oappe.top/Article/details/gtgfxpywov.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.hammf.cn/Article/details/gtiwzppdaj.html

PHP:  get_object_vars($obj);
来源：http://dali.hysaishi.cn/Article/details/gtkauqsuzg.html

JS:   Object.entries(obj)
来源：http://dali.daria6918.cn/Article/details/gtmuxmhoqu.html

TS:   Object.entries(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtlfyftkcm.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yuxming.cn/Article/details/gtfigarxle.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.snrcjt.cn/Article/details/gtppdrpkur.html

Ruby: obj.instance_variables
来源：http://dali.yj202588.top/Article/details/gtewviymnl.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.cheryme.top/Article/details/gtuofkjyqm.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtxurhnssd.html

H. 异常与错误处理
来源：http://dali.zdqjudy.top/Article/details/gtkzoiupaf.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtgyyiueek.html

[H01] try / catch 基础
来源：http://dali.hnxiangtu.top/Article/details/gtfrnpndyw.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.gaohongyu789.top/Article/details/gtzkqpftyd.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.hysaishi.cn/Article/details/gtjpuuxzjm.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jinqigfzy.top/Article/details/gtthhjmkis.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.fengsongda.top/Article/details/gtrxxnfrwq.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtliscoflv.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.chenzaomai.com/Article/details/gtzdtirori.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.dianchejie.cn/Article/details/gtzdldxqmd.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.meibo888.top/Article/details/gtcuhrnsew.html

[H02] finally / ensure 收尾
来源：http://dali.aibaodan.cn/Article/details/gtlkimiwqi.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.fengsongda.top/Article/details/gtikovmgzz.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hywenlv.cn/Article/details/gtntxvzwbe.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.chenjidiqi.icu/Article/details/gtzdpaosns.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.ehwqpu.com/Article/details/gtmahonwxc.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.gotoacloud.top/Article/details/gtuibxmjxo.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.gzhubu.top/Article/details/gtbpwzdbwf.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.mhx1999.top/Article/details/gtvimihjfl.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtlviusrbu.html

[H03] 主动抛出异常
来源：http://dali.tianlin.xyz/Article/details/gtnffouewl.html

Py:   raise ValueError("错误信息")
来源：http://dali.ppjwa.cn/Article/details/gtooqjjfxc.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yangfankeji.com/Article/details/gtiugquhey.html

JS:   throw new Error("错误信息");
来源：http://dali.wangdashe.top/Article/details/gtdtgsgujd.html

TS:   throw new Error("错误信息");
来源：http://dali.jlsjyb.cn/Article/details/gtydwvlblk.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.shuidangran.top/Article/details/gtuxverukn.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.cqqwz.cn/Article/details/gtfvebmfdy.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hnqzz.top/Article/details/gtogtzfeyz.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.bjfxy.top/Article/details/gttarqwvbv.html

[H04] 自定义异常类型
来源：http://dali.hywenlv.cn/Article/details/gtavbyjacq.html

Py:   class MyError(Exception): pass
来源：http://dali.jiagoushi.top/Article/details/gtmmtslcup.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.aizwys.cn/Article/details/gtufhlfame.html

JS:   class MyError extends Error {}
来源：http://dali.gzhubu.top/Article/details/gtnsidpcve.html

TS:   class MyError extends Error {}
来源：http://dali.chenlongwang.top/Article/details/gtecfpjeze.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jinqigufen.top/Article/details/gtyicipahh.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jianghu66.top/Article/details/gtsqjnpdcq.html

Ruby: class MyError < StandardError; end
来源：http://dali.yuxming.cn/Article/details/gtzvspjsnx.html

C#:   class MyException : Exception {}
来源：http://dali.ehwqpu.com/Article/details/gthhqfypry.html

[H05] 捕获特定类型
来源：http://dali.gaohongyu789.top/Article/details/gtrjmlcpch.html

Py:   except ValueError as e:
来源：http://dali.zhixingplan.top/Article/details/gtxsrohisd.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yuanzhike.top/Article/details/gtskewrbwd.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jianghu66.top/Article/details/gthnyncvpi.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.mhx1999.top/Article/details/gtzxlcsaxl.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.shzxlz.cn/Article/details/gtakyltrfe.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.hywenlv.cn/Article/details/gtwnblnotk.html

Ruby: rescue ArgumentError => e
来源：http://dali.quarkkingdee.top/Article/details/gtuyhrycjl.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtwdenoslt.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yanxiufei.cn/Article/details/gtlcftlejx.html

Py:   value = d.get("k") or default
来源：http://dali.gogol.net.cn/Article/details/gtxrjlojik.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.chenlongwang.top/Article/details/gtvfphxavc.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhiwuduotai.top/Article/details/gtycuoxahb.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.fzhhl.top/Article/details/gtotitufpc.html


<!-- 参考信息 -->