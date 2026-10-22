代发 wailian999

[F01] 读取整个文件
来源：http://dali.tianlin.xyz/Article/details/gtuqcdbbei.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.ybcxt.top/Article/details/gtkjxertsr.html

PHP:  file_get_contents("a.txt");
来源：http://dali.ybcxt.top/Article/details/gtqphzcdxq.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrziuljbj.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtssxjucbn.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.dianchejie.cn/Article/details/gtbdwedtxq.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.xziqi.cn/Article/details/gtccbdexvk.html

Ruby: File.read("a.txt")
来源：http://dali.sweek.top/Article/details/gtibkqyecq.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.fengsongda.top/Article/details/gtelylqtcy.html

[F02] 逐行读取文件
来源：http://dali.zdqjudy.top/Article/details/gtuatvtqze.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhoulong.xyz/Article/details/gtlbcztrir.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.sxryk.cn/Article/details/gtehuwxgki.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cheryme.top/Article/details/gtoybhjtwm.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtibvubkpk.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.dashuyun.cn/Article/details/gtwsxjlzdl.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.guowangkeji.top/Article/details/gtwisqjhws.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yanxiufei.cn/Article/details/gtnfzltelt.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.ppjwa.cn/Article/details/gtdptdptuh.html

[F03] 写入文件（覆盖）
来源：http://dali.chenlongwang.top/Article/details/gtpdgyydew.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.meibo888.top/Article/details/gtaiepkkwy.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.redwolf501.top/Article/details/gtqwliscou.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jqgufenzy.top/Article/details/gttemmudhd.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sxryk.cn/Article/details/gtlkkpdghw.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.aibaodan.cn/Article/details/gtcodywdmj.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yuanzhike.top/Article/details/gtxypzpbda.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtypqzsiok.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.tian-w.cn/Article/details/gtlttsvnes.html

[F04] 追加写入文件
来源：http://dali.hysaishi.cn/Article/details/gtwtglzmqh.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.sufxvd.cn/Article/details/gtdubpuiql.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yonumen.top/Article/details/gtmjopxhrc.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoebrakui.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.aibaodan.cn/Article/details/gtvqtaixlg.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.wangdashe.top/Article/details/gtirnwekqy.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.wangdashe.top/Article/details/gtlsgkwpjk.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.daxiang520.top/Article/details/gttfzhuzvw.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.nanxinkj.top/Article/details/gtmhlvnbiu.html

[F05] 判断文件或目录是否存在
来源：http://dali.iojbl.cn/Article/details/gtpkelbqvc.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.gogol.net.cn/Article/details/gtaklleemw.html

PHP:  file_exists("a.txt");
来源：http://dali.tanke756.top/Article/details/gtqsunkemw.html

JS:   fs.existsSync("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtjiitfsdg.html

TS:   fs.existsSync("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtybfqnzbt.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.chenjidiqi.icu/Article/details/gtidcwlkpa.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.feifeiyinyue.top/Article/details/gthosbwslb.html

Ruby: File.exist?("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gttoqcobno.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtezoupmvh.html

[F06] 删除文件
来源：http://dali.xuanzx.com/Article/details/gtntnjlcaz.html

Py:   os.remove("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtavcwxwrq.html

PHP:  unlink("a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdaymayjl.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtpmovsuha.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtavhyszkw.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.bjfxy.top/Article/details/gtnkzuuqca.html

Go:   os.Remove("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtdjssbngj.html

Ruby: File.delete("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gttdpduaoi.html

C#:   File.Delete("a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gtgmpsxocr.html

[F07] 创建目录（含多级）
来源：http://dali.mhx1999.top/Article/details/gtskqkaqfr.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.guowangkeji.top/Article/details/gtbpwwjezn.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.chenlongwang.top/Article/details/gtwdzauewi.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.redwolf501.top/Article/details/gtrgaewsqt.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gotoacloud.top/Article/details/gtmmazyvan.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.pycfn.com/Article/details/gtxqfucbba.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yueranfly.top/Article/details/gttowlrmkk.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.haohaochexian.top/Article/details/gtfnanfmnd.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.guowangkeji.top/Article/details/gtzxrfkjan.html

[F08] 遍历目录
来源：http://dali.xziqi.cn/Article/details/gtewrwtprb.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.ehwqpu.com/Article/details/gtpuuufytg.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jinqigfzy.top/Article/details/gtotqjvkro.html

JS:   fs.readdirSync("dir")
来源：http://dali.quarkkingdee.top/Article/details/gtfjtvcimz.html

TS:   fs.readdirSync("dir")
来源：http://dali.hywenlv.cn/Article/details/gtphtndfjm.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.sxryk.cn/Article/details/gtzexhcjle.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.guowangkeji.top/Article/details/gtrzfobisi.html

Ruby: Dir.children("dir")
来源：http://dali.hnxiangtu.top/Article/details/gtogjbzphc.html

C#:   Directory.GetFiles("dir")
来源：http://dali.cqqwz.cn/Article/details/gttsphgcqn.html

[F09] 获取文件大小
来源：http://dali.xylfe.cn/Article/details/gtocqkvsvt.html

Py:   os.path.getsize("a.txt")
来源：http://dali.tanke756.top/Article/details/gtjesysrvv.html

PHP:  filesize("a.txt");
来源：http://dali.guowangkeji.top/Article/details/gtdlpckitp.html

JS:   fs.statSync("a.txt").size
来源：http://dali.hysaishi.cn/Article/details/gtjdnllvay.html

TS:   fs.statSync("a.txt").size
来源：http://dali.sufxvd.cn/Article/details/gtepqrcbvv.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyqzuygxk.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.9152youxi.cn/Article/details/gtatgaegts.html

Ruby: File.size("a.txt")
来源：http://dali.hammf.cn/Article/details/gtfnynlhcz.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.ehwqpu.com/Article/details/gttztadbez.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.svipenyu.cn/Article/details/gtgqhexacr.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.redwolf501.top/Article/details/gtfjlafeqo.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.sweek.top/Article/details/gtevbbutjq.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.mhx1999.top/Article/details/gtormhjqse.html

TS:   path.extname("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtimqidawu.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.cqqwz.cn/Article/details/gtdpnshkvy.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.xziqi.cn/Article/details/gtmxxnpeqd.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtqxrqhgdc.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtluarfjkj.html

[F11] 复制与移动文件
来源：http://dali.sxryk.cn/Article/details/gtmvhliuwu.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yuxming.cn/Article/details/gtecxxfvrn.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.ehwqpu.com/Article/details/gtlawropha.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.bjfxy.top/Article/details/gtwdcdoeay.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yueranfly.top/Article/details/gtiqfenyjp.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.fengsongda.top/Article/details/gtkwqharpf.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zdqjudy.top/Article/details/gtwdmxdnpr.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yanxiufei.cn/Article/details/gteztziebo.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.sweek.top/Article/details/gtymhyhcxh.html

[F12] CSV 读写
来源：http://dali.cdnleiting.top/Article/details/gtsfzaluys.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhixingplan.top/Article/details/gtlzyymeko.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.cashguo.top/Article/details/gtsaljtcsp.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.tian-w.cn/Article/details/gttqqyouzr.html

TS:   // 同上
来源：http://dali.shanyushiyangtech.top/Article/details/gtdxkfexjm.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.nanxuanxn.top/Article/details/gtvxouamlc.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.gogol.net.cn/Article/details/gtodpvgsri.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yj202588.top/Article/details/gtnwkwxhlf.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiygtwszy.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtrpbbgsrg.html

G. 面向对象
来源：http://dali.zhixingplan.top/Article/details/gtsnfwtrlr.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gteheuhwaz.html

[G01] 定义类
来源：http://dali.yangfankeji.com/Article/details/gtwhdpusag.html

Py:   class User: pass
来源：http://dali.hnqzz.top/Article/details/gtknoqrnhn.html

PHP:  class User {}
来源：http://dali.tian-w.cn/Article/details/gtdqjtfgkt.html

JS:   class User {}
来源：http://dali.jinqigufen.top/Article/details/gtngeesssv.html

TS:   class User { name: string = ""; }
来源：http://dali.gogol.net.cn/Article/details/gtmiosmlqw.html

Java: class User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtzucmoomj.html

Go:   type User struct { Name string }
来源：http://dali.fzhhl.top/Article/details/gtvfxxjvrh.html

Ruby: class User; end
来源：http://dali.redwolf501.top/Article/details/gtsuhcnjnr.html

C#:   class User {}
来源：http://dali.zhengqikj.top/Article/details/gtpwrfyfrc.html

[G02] 构造函数
来源：http://dali.ehwqpu.com/Article/details/gtiegioqqz.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaqzhmbgk.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.cashguo.top/Article/details/gtounsdxul.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.haohaochexian.top/Article/details/gtmcbyrqrw.html

TS:   constructor(public name: string) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtvoliedxa.html

Java: User(String name) { this.name = name; }
来源：http://dali.yanxiufei.cn/Article/details/gtalombzyn.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jqgfzy.top/Article/details/gthwcnkvtd.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.bjfxy.top/Article/details/gtlxstagqa.html

C#:   public User(string name) { Name = name; }
来源：http://dali.chenlongwang.top/Article/details/gtxuhjswmb.html

[G03] 实例属性
来源：http://dali.tian-w.cn/Article/details/gtgrpyqlxx.html

Py:   self.name = "x"
来源：http://dali.daxiang520.top/Article/details/gtfmvmzjfw.html

PHP:  public string $name = "x";
来源：http://dali.yanxiufei.cn/Article/details/gthveuapee.html

JS:   this.name = "x";
来源：http://dali.ehwqpu.com/Article/details/gtpbrghufb.html

TS:   name: string = "x";
来源：http://dali.shangyingyoupin.top/Article/details/gtsucpawya.html

Java: private String name;
来源：http://dali.sysykeji.top/Article/details/gtearqqhva.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.xziqi.cn/Article/details/gtisceruzw.html

Ruby: @name = "x"
来源：http://dali.iojbl.cn/Article/details/gtsfuzkcva.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.9152youxi.cn/Article/details/gtgctkvipk.html

[G04] 定义方法
来源：http://dali.tianlin.xyz/Article/details/gtdqyjtbeh.html

Py:   def greet(self): return self.name
来源：http://dali.jqgufenzy.top/Article/details/gtqnkwfdxi.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zycfv.cn/Article/details/gtpmjohkan.html

JS:   greet() { return this.name; }
来源：http://dali.yongpay.top/Article/details/gtpeftbekf.html

TS:   greet(): string { return this.name; }
来源：http://dali.cucudq.cn/Article/details/gtrwxdyspm.html

Java: String greet() { return name; }
来源：http://dali.gaohongyu789.top/Article/details/gtyyvsqlyc.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.gogol.net.cn/Article/details/gtwazsjzby.html

Ruby: def greet; @name; end
来源：http://dali.jlsjyb.cn/Article/details/gtzhhiwbfi.html

C#:   public string Greet() => Name;
来源：http://dali.zhongyouzk.top/Article/details/gtvehgvbna.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gtofwvkyqw.html

Py:   class Admin(User): pass
来源：http://dali.xylfe.cn/Article/details/gtqbqphszj.html

PHP:  class Admin extends User {}
来源：http://dali.vqdsnc.cn/Article/details/gtpdobmvvj.html

JS:   class Admin extends User {}
来源：http://dali.snrcjt.cn/Article/details/gtdrkurivj.html

TS:   class Admin extends User {}
来源：http://dali.hammf.cn/Article/details/gtwvkuluee.html

Java: class Admin extends User {}
来源：http://dali.aibaodan.cn/Article/details/gtfwcdullz.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.guannengcc.top/Article/details/gtrxqaupyi.html

Ruby: class Admin < User; end
来源：http://dali.cqqwz.cn/Article/details/gtrkfuxjgm.html

C#:   class Admin : User {}
来源：http://dali.ybcxt.top/Article/details/gtmrfcipxm.html

[G06] 重写方法
来源：http://dali.mhx1999.top/Article/details/gtspaffnre.html

Py:   def greet(self): return "admin"
来源：http://dali.yj202588.top/Article/details/gtfmtnhhdp.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.xylfe.cn/Article/details/gtcxyifarr.html

JS:   greet() { return "admin"; }
来源：http://dali.zhengqikj.top/Article/details/gtuflzowwn.html

TS:   greet(): string { return "admin"; }
来源：http://dali.havefunace.top/Article/details/gtddlhanks.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.pycfn.com/Article/details/gtfsxctvaa.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.fengsongda.top/Article/details/gtbuqikqss.html

Ruby: def greet; "admin"; end
来源：http://dali.jlsjyb.cn/Article/details/gtekefniom.html

C#:   public override string Greet() => "admin";
来源：http://dali.meibo888.top/Article/details/gtgrohbkwj.html

[G07] 调用父类方法
来源：http://dali.chenlongwang.top/Article/details/gtehhewizv.html

Py:   super().greet()
来源：http://dali.yueranfly.top/Article/details/gtztxrhyym.html

PHP:  parent::greet();
来源：http://dali.nwbrower.top/Article/details/gtrugvunck.html

JS:   super.greet();
来源：http://dali.yuanzhike.top/Article/details/gtpbhwnjhu.html

TS:   super.greet();
来源：http://dali.xziqi.cn/Article/details/gtydsdaami.html

Java: super.greet();
来源：http://dali.hywenlv.cn/Article/details/gtcdjqbscp.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.shangyingyoupin.top/Article/details/gtadkyauvp.html

Ruby: super
来源：http://dali.smart0.xyz/Article/details/gtaiypicew.html

C#:   base.Greet();
来源：http://dali.redwolf501.top/Article/details/gtenfmvjde.html

[G08] 静态方法与属性
来源：http://dali.shzxlz.cn/Article/details/gtgoejhvnn.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.guowangkeji.top/Article/details/gtxrfbmsba.html

PHP:  public static function f() {}
来源：http://dali.pycfn.com/Article/details/gtyhoztcpz.html

JS:   static f() {}
来源：http://dali.xuanzx.com/Article/details/gtcmerkdit.html

TS:   static f(): void {}
来源：http://dali.shzxlz.cn/Article/details/gtvkrhswmr.html

Java: static void f() {}
来源：http://dali.hammf.cn/Article/details/gttnpjtesb.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.smart0.xyz/Article/details/gtgajoremt.html

Ruby: def self.f; end
来源：http://dali.zhiwuduotai.top/Article/details/gtognwtttw.html

C#:   public static void F() {}
来源：http://dali.yj20258.top/Article/details/gtfbmznlbd.html

[G09] 接口 / 抽象类
来源：http://dali.yj20258888.top/Article/details/gtcosjflda.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yuanzhike.top/Article/details/gtgyeenqrn.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.shzxlz.cn/Article/details/gtuoftmvot.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.xuetiantiany.cn/Article/details/gtpcxwfxrp.html

TS:   interface Shape { area(): number; }
来源：http://dali.iojbl.cn/Article/details/gthihhehar.html

Java: interface Shape { double area(); }
来源：http://dali.gzhubu.top/Article/details/gtmouxattu.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zycfv.cn/Article/details/gtccuqrehg.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.shanyushiyangtech.top/Article/details/gtddzqoigq.html

C#:   interface IShape { double Area(); }
来源：http://dali.cheryme.top/Article/details/gtuuwnefxw.html

[G10] 访问控制
来源：http://dali.redwolf501.top/Article/details/gtgmqcwzob.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.hfpthk.cn/Article/details/gtcrgldyie.html

PHP:  public / protected / private
来源：http://dali.zdqjudy.top/Article/details/gtqoneefya.html

JS:   #private 字段；其余公开
来源：http://dali.jqgfzy.top/Article/details/gtdcdivnqy.html

TS:   public / protected / private
来源：http://dali.hywenlv.cn/Article/details/gtcieshhmm.html

Java: public / protected / private / 默认包级
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfeslijsp.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.quarkkingdee.top/Article/details/gtrkzcmqre.html

Ruby: public / protected / private
来源：http://dali.shzxlz.cn/Article/details/gthhckskmd.html

C#:   public / protected / private / internal
来源：http://dali.tianlin.xyz/Article/details/gtljlrwixg.html

[G11] getter / setter
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqdwpeiop.html

Py:   @property 与 @x.setter
来源：http://dali.aibaodan.cn/Article/details/gtoxchrgvi.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.nwbrower.top/Article/details/gtkgiezlks.html

JS:   get name() { return this._name; }
来源：http://dali.zycfv.cn/Article/details/gtuoholbey.html

TS:   get name(): string { return this._name; }
来源：http://dali.jinqigfzy.top/Article/details/gtnzfexyfb.html

Java: public String getName() { return name; }
来源：http://dali.tian-w.cn/Article/details/gtcvrcieks.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.nwbrower.top/Article/details/gtjigbvemh.html

Ruby: attr_accessor :name
来源：http://dali.shzxlz.cn/Article/details/gtdktelutv.html

C#:   public string Name { get; set; }
来源：http://dali.daria6918.cn/Article/details/gtqrgynifa.html

[G12] 对象转字符串
来源：http://dali.sysykeji.top/Article/details/gtetmmkdvk.html

Py:   def __str__(self): return self.name
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfsobyker.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.daxiang520.top/Article/details/gtzyeajmuj.html

JS:   toString() { return this.name; }
来源：http://dali.gzhubu.top/Article/details/gtojqvokcy.html

TS:   toString(): string { return this.name; }
来源：http://dali.gotoacloud.top/Article/details/gtmvzukbou.html

Java: @Override public String toString() { return name; }
来源：http://dali.jiagoushi.top/Article/details/gtwdnejdzw.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.0kj1m.cn/Article/details/gtganeinvk.html

Ruby: def to_s; @name; end
来源：http://dali.jinqigfzy.top/Article/details/gtstnhvovj.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gtvyyshiad.html

[G13] 判断对象类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcinevzfw.html

Py:   isinstance(u, User)
来源：http://dali.aibaodan.cn/Article/details/gtainewlrq.html

PHP:  $u instanceof User
来源：http://dali.tanke756.top/Article/details/gtuofosbss.html

JS:   u instanceof User
来源：http://dali.jinqigfzy.top/Article/details/gtppcrkxdw.html

TS:   u instanceof User
来源：http://dali.yvedp.cn/Article/details/gtlpdelkmo.html

Java: u instanceof User
来源：http://dali.tianlin.xyz/Article/details/gtukrfyitu.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.ywan-chungtsiang.top/Article/details/gttkykfkaa.html

Ruby: u.is_a?(User)
来源：http://dali.dashuyun.cn/Article/details/gtyyejyzpj.html

C#:   u is User
来源：http://dali.tianlin.xyz/Article/details/gtnwiyrgyg.html

[G14] 数据类 / record
来源：http://dali.jqgufenzy.top/Article/details/gtmxquzezi.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gtzroxvvbt.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.bjfxy.top/Article/details/gtembqclha.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.shangyingyoupin.top/Article/details/gtgbrjndwg.html

TS:   type User = { name: string; age: number };
来源：http://dali.jinghuilouyu.cn/Article/details/gtggrtcrpk.html

Java: record User(String name, int age) {}
来源：http://dali.jinqigufen.top/Article/details/gtwxguvpex.html

Go:   type User struct { Name string; Age int }
来源：http://dali.tianlin.xyz/Article/details/gtjdmexoib.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.feifeiyinyue.top/Article/details/gtwjnmrtdc.html

C#:   record User(string Name, int Age);
来源：http://dali.chenlongwang.top/Article/details/gtpecrxenp.html

[G15] 枚举
来源：http://dali.jlsjyb.cn/Article/details/gtcpvdlcyh.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jinqigufen.top/Article/details/gtsimcrnfo.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ppjwa.cn/Article/details/gtnomyhmwx.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.xylfe.cn/Article/details/gtrtsedphx.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shzxlz.cn/Article/details/gthtaxfrww.html

Java: enum Color { RED, GREEN }
来源：http://dali.bjfxy.top/Article/details/gtmurwmnnk.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.pengpengdd.cyou/Article/details/gthfwmudjq.html

Ruby: Color = %i[red green].freeze
来源：http://dali.xylfe.cn/Article/details/gtgqzjzwxo.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.dianchejie.cn/Article/details/gtcfgjpbjh.html

[G16] 对象转数组 / 字典
来源：http://dali.quarkkingdee.top/Article/details/gtfrplqdsk.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.vqdsnc.cn/Article/details/gtfnspwkeo.html

PHP:  get_object_vars($obj);
来源：http://dali.yuxming.cn/Article/details/gttithmdnn.html

JS:   Object.entries(obj)
来源：http://dali.pycfn.com/Article/details/gtxxxedqqs.html

TS:   Object.entries(obj)
来源：http://dali.gotoacloud.top/Article/details/gthfiwwvjd.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yangfankeji.com/Article/details/gtfbqzatji.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.vqdsnc.cn/Article/details/gtjzldvyyg.html

Ruby: obj.instance_variables
来源：http://dali.tianlin.xyz/Article/details/gtahaaouqo.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hywenlv.cn/Article/details/gtquotndsu.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtpxzgxalt.html

H. 异常与错误处理
来源：http://dali.tianlin.xyz/Article/details/gtdpjqnodt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtcehmbmsf.html

[H01] try / catch 基础
来源：http://dali.iojbl.cn/Article/details/gtnaqioiuc.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.snrcjt.cn/Article/details/gtzelenihl.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqghwdrcn.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jyoumei.cn/Article/details/gtgqpcgliw.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jqgufenzy.top/Article/details/gtmpgwakku.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.vqdsnc.cn/Article/details/gthelomlwy.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jlsjyb.cn/Article/details/gtqukufecz.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.xuetiantiany.cn/Article/details/gtinyscvbn.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.0kj1m.cn/Article/details/gtptcuptsx.html

[H02] finally / ensure 收尾
来源：http://dali.iojbl.cn/Article/details/gtxogqbrgw.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hfpthk.cn/Article/details/gtolkwnzxi.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jianghu66.top/Article/details/gtqslcpcmc.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.chenlongwang.top/Article/details/gthvaeruel.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jianghu66.top/Article/details/gtftwrjszp.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yueranfly.top/Article/details/gtvieeiznz.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.cashguo.top/Article/details/gtkrqeryqf.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.daxiang520.top/Article/details/gtooeekpiq.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.hammf.cn/Article/details/gtxmnaocwc.html

[H03] 主动抛出异常
来源：http://dali.kuanghao11.cn/Article/details/gtfiaknurs.html

Py:   raise ValueError("错误信息")
来源：http://dali.fengsongda.top/Article/details/gtbptywmzu.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.xylfe.cn/Article/details/gtempnnzlh.html

JS:   throw new Error("错误信息");
来源：http://dali.chenzaomai.com/Article/details/gtbmdomwzu.html

TS:   throw new Error("错误信息");
来源：http://dali.9152youxi.cn/Article/details/gtzactkjzo.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zdqjudy.top/Article/details/gtnayvaydm.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jyoumei.cn/Article/details/gtnxchvdjr.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.shanyushiyangtech.top/Article/details/gtycbtcubw.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.hammf.cn/Article/details/gtkugwjdvx.html

[H04] 自定义异常类型
来源：http://dali.redwolf501.top/Article/details/gtwwyrinwv.html

Py:   class MyError(Exception): pass
来源：http://dali.jqgufenzy.top/Article/details/gtgntsabvc.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.sweek.top/Article/details/gtdvuitmtq.html

JS:   class MyError extends Error {}
来源：http://dali.jinqigfzy.top/Article/details/gtxztduexe.html

TS:   class MyError extends Error {}
来源：http://dali.yangfankeji.com/Article/details/gtgcuzagux.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yonumen.top/Article/details/gtffkqrndf.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yangfankeji.com/Article/details/gtbfwzemqs.html

Ruby: class MyError < StandardError; end
来源：http://dali.yueranfly.top/Article/details/gtlrxtrkbt.html

C#:   class MyException : Exception {}
来源：http://dali.cdnleiting.top/Article/details/gtbxngwtbk.html

[H05] 捕获特定类型
来源：http://dali.yuanzhike.top/Article/details/gtgfkvwgcm.html

Py:   except ValueError as e:
来源：http://dali.zhixingplan.top/Article/details/gtutlvzwxg.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.daria6918.cn/Article/details/gtxfhoyyet.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.9152youxi.cn/Article/details/gtxiklvwhh.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yuxming.cn/Article/details/gtfbpxcsak.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.sufxvd.cn/Article/details/gtxihblbqq.html


<!-- 参考信息 -->