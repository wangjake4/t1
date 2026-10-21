代发 wailian999

[F01] 读取整个文件
来源：http://dali.yonumen.top/Article/details/gtrdlesuzu.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.tianlin.xyz/Article/details/gtsnpvyrnz.html

PHP:  file_get_contents("a.txt");
来源：http://dali.chenlongwang.top/Article/details/gtfcbtmelz.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.sysykeji.top/Article/details/gtlfyuhtpr.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.hongshengwenyu.top/Article/details/gtbbdwsiod.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yonumen.top/Article/details/gtnvcwntly.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.kuanghao11.cn/Article/details/gtgwlwlkst.html

Ruby: File.read("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtlliuoxhk.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gtydcqtpfe.html

[F02] 逐行读取文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtwipfjqgn.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.0kj1m.cn/Article/details/gtlatbbhkz.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhijiandao.cn/Article/details/gtqqipzlew.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gaohongyu789.top/Article/details/gtbznzsmdf.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrnfjtpix.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.ywan-chungtsiang.top/Article/details/gthyefqzsr.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.andypj.xyz/Article/details/gtfftyckud.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.aibaodan.cn/Article/details/gtxnrkucmm.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.hfpthk.cn/Article/details/gtdjvzlkur.html

[F03] 写入文件（覆盖）
来源：http://dali.zhiwuduotai.top/Article/details/gtpmwotjlm.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.daxiang520.top/Article/details/gtrphisswj.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.chenlongwang.top/Article/details/gtqvvkmgde.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.chenzaomai.com/Article/details/gtlcsdjjmz.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cashguo.top/Article/details/gtvsymqlzu.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.xuanzx.com/Article/details/gtehtvsbak.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.kuanghao11.cn/Article/details/gtbihjqcnc.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhixingplan.top/Article/details/gtfboyemmv.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtixnkkgbj.html

[F04] 追加写入文件
来源：http://dali.yueranfly.top/Article/details/gtncuiaqdq.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.hongshengwenyu.top/Article/details/gtwanxisge.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.bjfxy.top/Article/details/gthpktzbqj.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hongshengwenyu.top/Article/details/gtosygnwmf.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.daxiang520.top/Article/details/gtkcbmbius.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhongyouzk.top/Article/details/gteocqampa.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.0kj1m.cn/Article/details/gtpkzxaufx.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.ybcxt.top/Article/details/gtxptczlla.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.chenjidiqi.icu/Article/details/gtnhptfcsr.html

[F05] 判断文件或目录是否存在
来源：http://dali.ivvv.top/Article/details/gtjrsiddqr.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.tian-w.cn/Article/details/gtdlbbbnjx.html

PHP:  file_exists("a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gtmrhhmitw.html

JS:   fs.existsSync("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtfxudkseq.html

TS:   fs.existsSync("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtbxnlmuyt.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jinqigfzy.top/Article/details/gtvuphgpfs.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jyoumei.cn/Article/details/gtztioslvf.html

Ruby: File.exist?("a.txt")
来源：http://dali.daxiang520.top/Article/details/gtqnmihbhl.html

C#:   File.Exists("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gthchivmya.html

[F06] 删除文件
来源：http://dali.vqdsnc.cn/Article/details/gtrsvseiot.html

Py:   os.remove("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtkiaekejb.html

PHP:  unlink("a.txt");
来源：http://dali.xziqi.cn/Article/details/gtjlcevuhb.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtnfgayvrr.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtwwfglafe.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yangfankeji.com/Article/details/gtcizmpkiy.html

Go:   os.Remove("a.txt")
来源：http://dali.smart0.xyz/Article/details/gtgdkwmrvd.html

Ruby: File.delete("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtkzfinlor.html

C#:   File.Delete("a.txt");
来源：http://dali.havefunace.top/Article/details/gtqixuhnyj.html

[F07] 创建目录（含多级）
来源：http://dali.yanxiufei.cn/Article/details/gtvylerwal.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtroczelpu.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.gzhubu.top/Article/details/gtsnpshvbo.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sysykeji.top/Article/details/gtcamkrhsg.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.smart0.xyz/Article/details/gtcgqjlwfu.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hysaishi.cn/Article/details/gtewydncpf.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.0kj1m.cn/Article/details/gtwrhwptgy.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.ybcxt.top/Article/details/gttlrtnuhu.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.cashguo.top/Article/details/gtlmgsahfh.html

[F08] 遍历目录
来源：http://dali.jinqigfzy.top/Article/details/gtngoxfsoy.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.fengsongda.top/Article/details/gtssygmzkj.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yangfankeji.com/Article/details/gtmbuktrpd.html

JS:   fs.readdirSync("dir")
来源：http://dali.chenjidiqi.icu/Article/details/gtrobflsmx.html

TS:   fs.readdirSync("dir")
来源：http://dali.xylfe.cn/Article/details/gtbsqaaqcv.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhiwuduotai.top/Article/details/gtmxiemulx.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.0kj1m.cn/Article/details/gtfuvricjo.html

Ruby: Dir.children("dir")
来源：http://dali.yuanzhike.top/Article/details/gtuiqeadhq.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hnqzz.top/Article/details/gtqejputrw.html

[F09] 获取文件大小
来源：http://dali.xylfe.cn/Article/details/gtltphruqt.html

Py:   os.path.getsize("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtswwyyafh.html

PHP:  filesize("a.txt");
来源：http://dali.zycfv.cn/Article/details/gtupgistaz.html

JS:   fs.statSync("a.txt").size
来源：http://dali.sufxvd.cn/Article/details/gtzxxbuyty.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhaomingkeji.xyz/Article/details/gtghcxsngo.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.kuanghao11.cn/Article/details/gtrknvwjqz.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yj20258888.top/Article/details/gtlnrdpvxy.html

Ruby: File.size("a.txt")
来源：http://dali.hammf.cn/Article/details/gtcajfrafh.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.mhx1999.top/Article/details/gtciajrbcz.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhengqikj.top/Article/details/gteoksxtxg.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yj20258.top/Article/details/gtzuerocad.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jinqigufen.top/Article/details/gtaorgyrjp.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.meibo888.top/Article/details/gtcgszgoxk.html

TS:   path.extname("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtayeipwjs.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.nanxinkj.top/Article/details/gtqskifkds.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtpeozdsmz.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.316326.xyz/Article/details/gtrasjgnma.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.bjfxy.top/Article/details/gtfjdldixp.html

[F11] 复制与移动文件
来源：http://dali.havefunace.top/Article/details/gtccjxewva.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hywenlv.cn/Article/details/gtvztukktm.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.ydzc1.top/Article/details/gtjvyxqhtr.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtdpjhbogc.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hnqzz.top/Article/details/gtfcirkyjp.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.mhx1999.top/Article/details/gtegtrygmm.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yangfankeji.com/Article/details/gtnuieetwx.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yj20258.top/Article/details/gtpsiqxjwh.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.fzhhl.top/Article/details/gtqoxddbde.html

[F12] CSV 读写
来源：http://dali.ybcxt.top/Article/details/gtiqjoisdg.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.ivvv.top/Article/details/gtcnkclhuv.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.redwolf501.top/Article/details/gtbmxlenph.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxmqohrvb.html

TS:   // 同上
来源：http://dali.chenzaomai.com/Article/details/gtlvlvwxuy.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.xinyue.icu/Article/details/gtjpvygmqe.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.wangdashe.top/Article/details/gtussglkro.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtevczhnhz.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.fengsongda.top/Article/details/gtvnmmqilq.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtsdwtzqus.html

G. 面向对象
来源：http://dali.zhiwuduotai.top/Article/details/gtcsriohva.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtpabuaanc.html

[G01] 定义类
来源：http://dali.xinyue.icu/Article/details/gtwuzqimyu.html

Py:   class User: pass
来源：http://dali.nanxinkj.top/Article/details/gthsiezinn.html

PHP:  class User {}
来源：http://dali.xuetiantiany.cn/Article/details/gtcozpxscs.html

JS:   class User {}
来源：http://dali.birdmap.top/Article/details/gtglityont.html

TS:   class User { name: string = ""; }
来源：http://dali.cheryme.top/Article/details/gtaeifpycq.html

Java: class User {}
来源：http://dali.ivvv.top/Article/details/gtlejagsgo.html

Go:   type User struct { Name string }
来源：http://dali.wangdashe.top/Article/details/gtqtamznqu.html

Ruby: class User; end
来源：http://dali.sufxvd.cn/Article/details/gtxxxizvao.html

C#:   class User {}
来源：http://dali.jiagoushi.top/Article/details/gthwnfctie.html

[G02] 构造函数
来源：http://dali.meibo888.top/Article/details/gtqgbpoxat.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yuxming.cn/Article/details/gttzbhgzxq.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.gaohongyu789.top/Article/details/gtrcsenyju.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jqgfzy.top/Article/details/gtmjuwfwbh.html

TS:   constructor(public name: string) {}
来源：http://dali.haohaochexian.top/Article/details/gtapliyajl.html

Java: User(String name) { this.name = name; }
来源：http://dali.daxiang520.top/Article/details/gtbsypqepl.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hywenlv.cn/Article/details/gtkezfocdx.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhixingplan.top/Article/details/gtonleimra.html

C#:   public User(string name) { Name = name; }
来源：http://dali.shzxlz.cn/Article/details/gtllygtajy.html

[G03] 实例属性
来源：http://dali.cheryme.top/Article/details/gtdhfmbaxl.html

Py:   self.name = "x"
来源：http://dali.jinqigufen.top/Article/details/gtpcfnwagj.html

PHP:  public string $name = "x";
来源：http://dali.vqdsnc.cn/Article/details/gtcztowmxr.html

JS:   this.name = "x";
来源：http://dali.wangdashe.top/Article/details/gtkptyhkui.html

TS:   name: string = "x";
来源：http://dali.dashuyun.cn/Article/details/gtxqzfeusw.html

Java: private String name;
来源：http://dali.sweek.top/Article/details/gtcqfuujce.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.sufxvd.cn/Article/details/gteqzeozrq.html

Ruby: @name = "x"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuulnxwcr.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.c1oappe.top/Article/details/gtdjdfaopw.html

[G04] 定义方法
来源：http://dali.jiagoushi.top/Article/details/gtlvmlcqgu.html

Py:   def greet(self): return self.name
来源：http://dali.shzxlz.cn/Article/details/gtjfoxvecu.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtffjjatnw.html

JS:   greet() { return this.name; }
来源：http://dali.0kj1m.cn/Article/details/gtdallvjpx.html

TS:   greet(): string { return this.name; }
来源：http://dali.jiagoushi.top/Article/details/gtlutsmdce.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gtxigcrvrc.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.shangyingyoupin.top/Article/details/gtiqpvhfpo.html

Ruby: def greet; @name; end
来源：http://dali.sxryk.cn/Article/details/gtbamzcqba.html

C#:   public string Greet() => Name;
来源：http://dali.chenzaomai.com/Article/details/gtsggyukkl.html

[G05] 继承
来源：http://dali.haohaochexian.top/Article/details/gtnyvgfozl.html

Py:   class Admin(User): pass
来源：http://dali.tanke756.top/Article/details/gthjygpphl.html

PHP:  class Admin extends User {}
来源：http://dali.zhiwuduotai.top/Article/details/gtkccixegg.html

JS:   class Admin extends User {}
来源：http://dali.ivvv.top/Article/details/gtlmydaiyb.html

TS:   class Admin extends User {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gthonfkvft.html

Java: class Admin extends User {}
来源：http://dali.yongpay.top/Article/details/gtrkcsegxn.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ybcxt.top/Article/details/gtjscdkyjm.html

Ruby: class Admin < User; end
来源：http://dali.sufxvd.cn/Article/details/gtjibzoeak.html

C#:   class Admin : User {}
来源：http://dali.yanxiufei.cn/Article/details/gtdzufsnzg.html

[G06] 重写方法
来源：http://dali.guowangkeji.top/Article/details/gtxtsippwu.html

Py:   def greet(self): return "admin"
来源：http://dali.yuxming.cn/Article/details/gtbshxygfc.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.redwolf501.top/Article/details/gtajusmkxb.html

JS:   greet() { return "admin"; }
来源：http://dali.aizwys.cn/Article/details/gtchmnlojn.html

TS:   greet(): string { return "admin"; }
来源：http://dali.cucudq.cn/Article/details/gtfrkxgzkn.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yvedp.cn/Article/details/gtlpuwdnpa.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hfpthk.cn/Article/details/gtgmaflevg.html

Ruby: def greet; "admin"; end
来源：http://dali.hysaishi.cn/Article/details/gtzbdaxtgr.html

C#:   public override string Greet() => "admin";
来源：http://dali.chenlongwang.top/Article/details/gtiyzskxjg.html

[G07] 调用父类方法
来源：http://dali.jyoumei.cn/Article/details/gtflyuvmkv.html

Py:   super().greet()
来源：http://dali.gotoacloud.top/Article/details/gtgtuzzysp.html

PHP:  parent::greet();
来源：http://dali.vqdsnc.cn/Article/details/gtxxrfstus.html

JS:   super.greet();
来源：http://dali.sysykeji.top/Article/details/gtudfktnll.html

TS:   super.greet();
来源：http://dali.hysaishi.cn/Article/details/gtwurknanu.html

Java: super.greet();
来源：http://dali.iojbl.cn/Article/details/gtlxapzsyi.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gteoxcsgsj.html

Ruby: super
来源：http://dali.guannengcc.top/Article/details/gtvalmpobn.html

C#:   base.Greet();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiucpkyws.html

[G08] 静态方法与属性
来源：http://dali.pycfn.com/Article/details/gtqsorpqhr.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.gaohongyu789.top/Article/details/gtenngwaol.html

PHP:  public static function f() {}
来源：http://dali.zhengqikj.top/Article/details/gtypmnreoy.html

JS:   static f() {}
来源：http://dali.xziqi.cn/Article/details/gtbrnqzmtf.html

TS:   static f(): void {}
来源：http://dali.redwolf501.top/Article/details/gteypaaelb.html

Java: static void f() {}
来源：http://dali.xuanzx.com/Article/details/gtlhganbjn.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yonumen.top/Article/details/gttvdtczkh.html

Ruby: def self.f; end
来源：http://dali.wangshuangyany.cn/Article/details/gtgfceynyx.html

C#:   public static void F() {}
来源：http://dali.mhx1999.top/Article/details/gtllvsgrls.html

[G09] 接口 / 抽象类
来源：http://dali.chenjidiqi.icu/Article/details/gtewsnhtqy.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.iojbl.cn/Article/details/gtoxausjvo.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.birdmap.top/Article/details/gtcmgzrtrv.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hammf.cn/Article/details/gtzmvyvxwo.html

TS:   interface Shape { area(): number; }
来源：http://dali.pycfn.com/Article/details/gtgmuzoyfv.html

Java: interface Shape { double area(); }
来源：http://dali.redwolf501.top/Article/details/gtzbrjcszw.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jinqigufen.top/Article/details/gtcmwtqncr.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.fzhhl.top/Article/details/gtrftpvvtt.html

C#:   interface IShape { double Area(); }
来源：http://dali.daria6918.cn/Article/details/gtijbjhixv.html

[G10] 访问控制
来源：http://dali.hammf.cn/Article/details/gtjeigyyzz.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.hammf.cn/Article/details/gtchsgvuvi.html

PHP:  public / protected / private
来源：http://dali.tian-w.cn/Article/details/gtpofkscnq.html

JS:   #private 字段；其余公开
来源：http://dali.ydzc1.top/Article/details/gtsvqwgixm.html

TS:   public / protected / private
来源：http://dali.tian-w.cn/Article/details/gtjqvqjzja.html

Java: public / protected / private / 默认包级
来源：http://dali.ydzc1.top/Article/details/gtjlsqnoso.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yvedp.cn/Article/details/gtbvgbfntt.html

Ruby: public / protected / private
来源：http://dali.aibaodan.cn/Article/details/gtussyowam.html

C#:   public / protected / private / internal
来源：http://dali.xuanzx.com/Article/details/gtjzprqwiw.html

[G11] getter / setter
来源：http://dali.cdnleiting.top/Article/details/gtiasldsef.html

Py:   @property 与 @x.setter
来源：http://dali.tanke756.top/Article/details/gtmwrkxasp.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.vqdsnc.cn/Article/details/gtyynnwjum.html

JS:   get name() { return this._name; }
来源：http://dali.jqgfzy.top/Article/details/gtwcykkrcz.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gtkyyfsdsz.html

Java: public String getName() { return name; }
来源：http://dali.yueranfly.top/Article/details/gtqgkgnhvf.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.hongshengwenyu.top/Article/details/gtzpomozad.html

Ruby: attr_accessor :name
来源：http://dali.daria6918.cn/Article/details/gtfdzfdghw.html

C#:   public string Name { get; set; }
来源：http://dali.ppjwa.cn/Article/details/gtamqokpwf.html

[G12] 对象转字符串
来源：http://dali.hnqzz.top/Article/details/gtfqonomvh.html

Py:   def __str__(self): return self.name
来源：http://dali.pengpengdd.cyou/Article/details/gtonbeyfax.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.xuetiantiany.cn/Article/details/gttxmqsoce.html

JS:   toString() { return this.name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtllzvtwye.html

TS:   toString(): string { return this.name; }
来源：http://dali.jqgufenzy.top/Article/details/gtzuehhcky.html

Java: @Override public String toString() { return name; }
来源：http://dali.c1oappe.top/Article/details/gtippetade.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yueranfly.top/Article/details/gtopvipuyu.html

Ruby: def to_s; @name; end
来源：http://dali.pengpengdd.cyou/Article/details/gticysxnjc.html

C#:   public override string ToString() => Name;
来源：http://dali.jinqigufen.top/Article/details/gtmfppmaiw.html

[G13] 判断对象类型
来源：http://dali.jianghu66.top/Article/details/gttcekfnck.html

Py:   isinstance(u, User)
来源：http://dali.guowangkeji.top/Article/details/gtcjnzysgc.html

PHP:  $u instanceof User
来源：http://dali.nwbrower.top/Article/details/gtigwxdeim.html

JS:   u instanceof User
来源：http://dali.nwbrower.top/Article/details/gtftgjzlfl.html

TS:   u instanceof User
来源：http://dali.hammf.cn/Article/details/gtxqfdzrok.html

Java: u instanceof User
来源：http://dali.yvedp.cn/Article/details/gtkmbosulu.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzbqwsyhm.html

Ruby: u.is_a?(User)
来源：http://dali.havefunace.top/Article/details/gttsgzeytc.html

C#:   u is User
来源：http://dali.smart0.xyz/Article/details/gtmgpivppk.html

[G14] 数据类 / record
来源：http://dali.feifeiyinyue.top/Article/details/gttcdvlfiu.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhiwuduotai.top/Article/details/gtwmcvarad.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jlsjyb.cn/Article/details/gtxkmwixom.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.cheryme.top/Article/details/gtyaepiapt.html

TS:   type User = { name: string; age: number };
来源：http://dali.svipenyu.cn/Article/details/gtczmkegzq.html

Java: record User(String name, int age) {}
来源：http://dali.zhoulong.xyz/Article/details/gtirmkirqs.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtihqgibhx.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.pengpengdd.cyou/Article/details/gtcxupqsso.html

C#:   record User(string Name, int Age);
来源：http://dali.daxiang520.top/Article/details/gtgzhocaiy.html

[G15] 枚举
来源：http://dali.bjfxy.top/Article/details/gtffmhsdvg.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhixingplan.top/Article/details/gtpeumygfj.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.xylfe.cn/Article/details/gtyhmpnfrh.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.bjfxy.top/Article/details/gtdoilwmiw.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.nanxinkj.top/Article/details/gtrzkrbbvc.html

Java: enum Color { RED, GREEN }
来源：http://dali.mhx1999.top/Article/details/gtbvbdaajn.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.cheryme.top/Article/details/gtsrluottw.html

Ruby: Color = %i[red green].freeze
来源：http://dali.havefunace.top/Article/details/gtiwzvbjpj.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.aizwys.cn/Article/details/gtfsoosbjl.html

[G16] 对象转数组 / 字典
来源：http://dali.jinghuilouyu.cn/Article/details/gtgcvtwzbm.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.ywan-chungtsiang.top/Article/details/gthfwygmhv.html

PHP:  get_object_vars($obj);
来源：http://dali.yj202588.top/Article/details/gtteoueemd.html

JS:   Object.entries(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyfnbctqa.html

TS:   Object.entries(obj)
来源：http://dali.zhengqikj.top/Article/details/gtbbuoexls.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.havefunace.top/Article/details/gtuxxkclev.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.sweek.top/Article/details/gtjepygezh.html

Ruby: obj.instance_variables
来源：http://dali.chenlongwang.top/Article/details/gtcumwdjnj.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yueranfly.top/Article/details/gthslfavnc.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtibzbfoyf.html

H. 异常与错误处理
来源：http://dali.cashguo.top/Article/details/gtlljffcsv.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gttlzvwfan.html

[H01] try / catch 基础
来源：http://dali.aizwys.cn/Article/details/gtjflkbajx.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.cucudq.cn/Article/details/gtraimtjrj.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.smart0.xyz/Article/details/gtalzrgmim.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hongshengwenyu.top/Article/details/gtfnfkfywf.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.shangyingyoupin.top/Article/details/gtgssetvjo.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jinqigufen.top/Article/details/gtwvskjmjt.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.0kj1m.cn/Article/details/gtossjcfym.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yvedp.cn/Article/details/gtzuizzhgh.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jiagoushi.top/Article/details/gtknfcncly.html

[H02] finally / ensure 收尾
来源：http://dali.yj20258.top/Article/details/gteghglhxw.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hnqzz.top/Article/details/gtrrvsodmp.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.dashuyun.cn/Article/details/gtofmkrrmj.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.dianchejie.cn/Article/details/gtykvzkbnj.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jqgfzy.top/Article/details/gtoadyfyys.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.quarkkingdee.top/Article/details/gtoxocszeb.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.gzhubu.top/Article/details/gtvfgvvuej.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.wangshuangyany.cn/Article/details/gtnaevcern.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhongyouzk.top/Article/details/gtiroidcjs.html

[H03] 主动抛出异常
来源：http://dali.yuanzhike.top/Article/details/gtpzwyyjur.html

Py:   raise ValueError("错误信息")
来源：http://dali.nanxuanxn.top/Article/details/gtbttecrxa.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.cashguo.top/Article/details/gtkrdhtlip.html

JS:   throw new Error("错误信息");
来源：http://dali.c1oappe.top/Article/details/gtiokkrvxz.html

TS:   throw new Error("错误信息");
来源：http://dali.hnxiangtu.top/Article/details/gtydravsvo.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jiagoushi.top/Article/details/gtkzbwvdre.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jqgufenzy.top/Article/details/gturfxflpq.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jyoumei.cn/Article/details/gtzwgrggpm.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhiwuduotai.top/Article/details/gtyzmzygze.html

[H04] 自定义异常类型
来源：http://dali.yangfankeji.com/Article/details/gtrukgnhqt.html

Py:   class MyError(Exception): pass
来源：http://dali.hysaishi.cn/Article/details/gtngpmxkqp.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.bjfxy.top/Article/details/gtrhstrahp.html

JS:   class MyError extends Error {}
来源：http://dali.ivvv.top/Article/details/gtrwjsrmbs.html

TS:   class MyError extends Error {}
来源：http://dali.chenjidiqi.icu/Article/details/gtydsnxsyv.html

Java: class MyException extends RuntimeException {}
来源：http://dali.cucudq.cn/Article/details/gtqbnhojup.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.sufxvd.cn/Article/details/gtwjzlguow.html

Ruby: class MyError < StandardError; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkwlaagjr.html

C#:   class MyException : Exception {}
来源：http://dali.birdmap.top/Article/details/gtncgwnajr.html

[H05] 捕获特定类型
来源：http://dali.cashguo.top/Article/details/gtvzxxxwyi.html

Py:   except ValueError as e:
来源：http://dali.shanyushiyangkeji.top/Article/details/gtycunntdk.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yanxiufei.cn/Article/details/gthhkidfml.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yj202588.top/Article/details/gtakdekhde.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.nwbrower.top/Article/details/gtnnqvyukp.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtphplwgnj.html


<!-- 参考信息 -->