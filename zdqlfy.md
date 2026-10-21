代发 wailian999

C#:   File.ReadAllText("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gtgbddpeem.html

[F02] 逐行读取文件
来源：http://dali.yj20258888.top/Article/details/gtupbrllpu.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.0kj1m.cn/Article/details/gtnhxpdoit.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.hongshengwenyu.top/Article/details/gtwdsfeswk.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hammf.cn/Article/details/gtsatxdwkr.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.sufxvd.cn/Article/details/gttntnfmwv.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.aibaodan.cn/Article/details/gtwkbbhldn.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.hywenlv.cn/Article/details/gtcnkmldsl.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yj20258888.top/Article/details/gtdzblnhdm.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.gogol.net.cn/Article/details/gtgajaxcfx.html

[F03] 写入文件（覆盖）
来源：http://dali.yangfankeji.com/Article/details/gtjymngnas.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.316326.xyz/Article/details/gtjzdervsa.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yangfankeji.com/Article/details/gttewdfuis.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.tian-w.cn/Article/details/gtbpygpcvr.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hywenlv.cn/Article/details/gtzkgevzxi.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.gotoacloud.top/Article/details/gtdbgzbyvo.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.daxiang520.top/Article/details/gtbyonxbai.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yvedp.cn/Article/details/gtlunpwuky.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.nanxuanxn.top/Article/details/gtcdkgolet.html

[F04] 追加写入文件
来源：http://dali.ivvv.top/Article/details/gtnrkvryjr.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.nwbrower.top/Article/details/gtezuserxa.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.9152youxi.cn/Article/details/gtxsmenkje.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.tanke756.top/Article/details/gttmmzxjkx.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ydzc1.top/Article/details/gtoolhcuek.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.svipenyu.cn/Article/details/gtgkpucdih.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.pycfn.com/Article/details/gtbfcpwbtd.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zycfv.cn/Article/details/gtlvpswliv.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.tianlin.xyz/Article/details/gthuooadqw.html

[F05] 判断文件或目录是否存在
来源：http://dali.cashguo.top/Article/details/gtotepewvy.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.cqqwz.cn/Article/details/gttlxpfvlk.html

PHP:  file_exists("a.txt");
来源：http://dali.zhengqikj.top/Article/details/gtwwrdofbl.html

JS:   fs.existsSync("a.txt")
来源：http://dali.daxiang520.top/Article/details/gtospfvalg.html

TS:   fs.existsSync("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtlgszwfgc.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhongyouzk.top/Article/details/gttzgjiyqm.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.chenjidiqi.icu/Article/details/gtngxdtcsb.html

Ruby: File.exist?("a.txt")
来源：http://dali.yongpay.top/Article/details/gtntpfxlir.html

C#:   File.Exists("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtesxqimhv.html

[F06] 删除文件
来源：http://dali.wangshuangyany.cn/Article/details/gtlgmztgqo.html

Py:   os.remove("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtfkcsafpr.html

PHP:  unlink("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gttrkibsjj.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtbgqfctfx.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.cashguo.top/Article/details/gtfeweffak.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jianghu66.top/Article/details/gtiucljsyu.html

Go:   os.Remove("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtydvhjcam.html

Ruby: File.delete("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtljsfccky.html

C#:   File.Delete("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gtgarjzpls.html

[F07] 创建目录（含多级）
来源：http://dali.wangshuangyany.cn/Article/details/gtpkcblfes.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.gaohongyu789.top/Article/details/gttaqwuhzt.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.gzhubu.top/Article/details/gtalmpayca.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.mhx1999.top/Article/details/gtwciqgspr.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ehwqpu.com/Article/details/gtdgmkmtmj.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhengqikj.top/Article/details/gtaozyamcr.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.ehwqpu.com/Article/details/gtdjytiwdg.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jinqigufen.top/Article/details/gtyftdbhip.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yj20258888.top/Article/details/gtxjeqcerd.html

[F08] 遍历目录
来源：http://dali.hysaishi.cn/Article/details/gtnskzpgpd.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.xuanzx.com/Article/details/gtgkvakjdi.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.feifeiyinyue.top/Article/details/gthlqjowee.html

JS:   fs.readdirSync("dir")
来源：http://dali.yvedp.cn/Article/details/gthxsvytjx.html

TS:   fs.readdirSync("dir")
来源：http://dali.jiagoushi.top/Article/details/gtdsjkegad.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jianghu66.top/Article/details/gtvmudaota.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jinghuilouyu.cn/Article/details/gtfjfajnjs.html

Ruby: Dir.children("dir")
来源：http://dali.jqgufenzy.top/Article/details/gtgpyrqxcw.html

C#:   Directory.GetFiles("dir")
来源：http://dali.gaohongyu789.top/Article/details/gtesmjwqqo.html

[F09] 获取文件大小
来源：http://dali.fzhhl.top/Article/details/gtqbwiuuvp.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtlhqmfiwd.html

PHP:  filesize("a.txt");
来源：http://dali.daria6918.cn/Article/details/gtaglnabgo.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhongyouzk.top/Article/details/gtqzacxney.html

TS:   fs.statSync("a.txt").size
来源：http://dali.xuanzx.com/Article/details/gtyllzmvtk.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.fengsongda.top/Article/details/gtklsszkvr.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yongpay.top/Article/details/gtkucikmzj.html

Ruby: File.size("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtwztvxcai.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.xuanzx.com/Article/details/gtfuvpcnuo.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.haohaochexian.top/Article/details/gtpwaudecv.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtdedsjsfa.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.shuidangran.top/Article/details/gttomrlmyo.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtkdvgspur.html

TS:   path.extname("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gthyiuleqe.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.gaohongyu789.top/Article/details/gtzzmwjurj.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtliyzdxof.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtzhwxldzn.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtacgtnzty.html

[F11] 复制与移动文件
来源：http://dali.yj20258.top/Article/details/gtsfuoslsd.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.ppjwa.cn/Article/details/gtokabpnjp.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.guowangkeji.top/Article/details/gtgfthzrfu.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtcayyajtu.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hnqzz.top/Article/details/gtxmgiosln.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhengqikj.top/Article/details/gtfizfkdyq.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.meibo888.top/Article/details/gtnmqlkeft.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.andypj.xyz/Article/details/gtsgjbslzx.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.dianchejie.cn/Article/details/gtoutyrwwc.html

[F12] CSV 读写
来源：http://dali.hammf.cn/Article/details/gtfvwxqvvo.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.wangdashe.top/Article/details/gtdsqlzmgw.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.sufxvd.cn/Article/details/gtattovpzt.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.0kj1m.cn/Article/details/gtffsxiwrz.html

TS:   // 同上
来源：http://dali.yonumen.top/Article/details/gtdfbckbwt.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhixingplan.top/Article/details/gtvpkjorzz.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.0kj1m.cn/Article/details/gtnodajfis.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.dashuyun.cn/Article/details/gtzmsnzswc.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhiwuduotai.top/Article/details/gtduedkagd.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtandmjozr.html

G. 面向对象
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvocqlivy.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gttqhcltrf.html

[G01] 定义类
来源：http://dali.gzhubu.top/Article/details/gtnhvzsdtg.html

Py:   class User: pass
来源：http://dali.pengpengdd.cyou/Article/details/gtubkqknqz.html

PHP:  class User {}
来源：http://dali.gzhubu.top/Article/details/gteafutfhw.html

JS:   class User {}
来源：http://dali.0kj1m.cn/Article/details/gtksdovfng.html

TS:   class User { name: string = ""; }
来源：http://dali.snrcjt.cn/Article/details/gtwhoavsjm.html

Java: class User {}
来源：http://dali.ehwqpu.com/Article/details/gtnyumpjkv.html

Go:   type User struct { Name string }
来源：http://dali.yj20258888.top/Article/details/gtxyahczxv.html

Ruby: class User; end
来源：http://dali.xziqi.cn/Article/details/gtoxtfubgy.html

C#:   class User {}
来源：http://dali.jiagoushi.top/Article/details/gtqzgwfzyd.html

[G02] 构造函数
来源：http://dali.shuidangran.top/Article/details/gtuhvpgkzo.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzdvkisvh.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtvbdoiekl.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jianghu66.top/Article/details/gthllxjurz.html

TS:   constructor(public name: string) {}
来源：http://dali.nanxinkj.top/Article/details/gtpcewuzwd.html

Java: User(String name) { this.name = name; }
来源：http://dali.hfpthk.cn/Article/details/gtvczumrnu.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.c1oappe.top/Article/details/gtldkewpkw.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.tian-w.cn/Article/details/gtazpeaier.html

C#:   public User(string name) { Name = name; }
来源：http://dali.kuanghao11.cn/Article/details/gtcqcazttf.html

[G03] 实例属性
来源：http://dali.sufxvd.cn/Article/details/gttiapkwue.html

Py:   self.name = "x"
来源：http://dali.svipenyu.cn/Article/details/gtocojmgfs.html

PHP:  public string $name = "x";
来源：http://dali.shangyingyoupin.top/Article/details/gtvmhcuivg.html

JS:   this.name = "x";
来源：http://dali.pycfn.com/Article/details/gtvtahmxtb.html

TS:   name: string = "x";
来源：http://dali.9152youxi.cn/Article/details/gtoipjwihc.html

Java: private String name;
来源：http://dali.yanxiufei.cn/Article/details/gtiqnvsweo.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.c1oappe.top/Article/details/gtlkgrbrdv.html

Ruby: @name = "x"
来源：http://dali.svipenyu.cn/Article/details/gtuapaarqm.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.gaohongyu789.top/Article/details/gtqsgbcutp.html

[G04] 定义方法
来源：http://dali.feifeiyinyue.top/Article/details/gtgxnroevj.html

Py:   def greet(self): return self.name
来源：http://dali.tianlin.xyz/Article/details/gtuoedgmzk.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.cdnleiting.top/Article/details/gtpfsyiugy.html

JS:   greet() { return this.name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtfedlcwvx.html

TS:   greet(): string { return this.name; }
来源：http://dali.yj20258888.top/Article/details/gtlojinngz.html

Java: String greet() { return name; }
来源：http://dali.nanxuanxn.top/Article/details/gtrioqirzd.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.mhx1999.top/Article/details/gtdkcttaad.html

Ruby: def greet; @name; end
来源：http://dali.yanxiufei.cn/Article/details/gtmbrhasya.html

C#:   public string Greet() => Name;
来源：http://dali.tian-w.cn/Article/details/gtjvgxrzqz.html

[G05] 继承
来源：http://dali.yj20258.top/Article/details/gtujdpidvs.html

Py:   class Admin(User): pass
来源：http://dali.wangdashe.top/Article/details/gtbrzfmbfq.html

PHP:  class Admin extends User {}
来源：http://dali.pengpengdd.cyou/Article/details/gtdkivhaxm.html

JS:   class Admin extends User {}
来源：http://dali.yongpay.top/Article/details/gtueocqxzu.html

TS:   class Admin extends User {}
来源：http://dali.nanxuanxn.top/Article/details/gtetcawmmb.html

Java: class Admin extends User {}
来源：http://dali.zhiwuduotai.top/Article/details/gtnadsmmls.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zdqjudy.top/Article/details/gtmanikyrk.html

Ruby: class Admin < User; end
来源：http://dali.shzxlz.cn/Article/details/gtfimxsgcr.html

C#:   class Admin : User {}
来源：http://dali.iojbl.cn/Article/details/gttfuuppxl.html

[G06] 重写方法
来源：http://dali.zycfv.cn/Article/details/gtbqpzjaxe.html

Py:   def greet(self): return "admin"
来源：http://dali.nanxuanxn.top/Article/details/gtiiklpavv.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.vqdsnc.cn/Article/details/gtddbbsdgr.html

JS:   greet() { return "admin"; }
来源：http://dali.jlsjyb.cn/Article/details/gtltlhxpcc.html

TS:   greet(): string { return "admin"; }
来源：http://dali.chenlongwang.top/Article/details/gtmjxxoejl.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.cucudq.cn/Article/details/gtivfbyjep.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yongpay.top/Article/details/gtpcdklynl.html

Ruby: def greet; "admin"; end
来源：http://dali.cucudq.cn/Article/details/gtsjigxgsy.html

C#:   public override string Greet() => "admin";
来源：http://dali.jiagoushi.top/Article/details/gtkdhkdpja.html

[G07] 调用父类方法
来源：http://dali.sxryk.cn/Article/details/gtezoblymo.html

Py:   super().greet()
来源：http://dali.yueranfly.top/Article/details/gtupvagyeg.html

PHP:  parent::greet();
来源：http://dali.zhengqikj.top/Article/details/gtkzpvssna.html

JS:   super.greet();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtftvhewtc.html

TS:   super.greet();
来源：http://dali.jqgufenzy.top/Article/details/gtysujtikr.html

Java: super.greet();
来源：http://dali.sweek.top/Article/details/gtwuuxhtzw.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yuxming.cn/Article/details/gtjlyqtpqb.html

Ruby: super
来源：http://dali.snrcjt.cn/Article/details/gtlyrqcsbf.html

C#:   base.Greet();
来源：http://dali.pycfn.com/Article/details/gtonubmnio.html

[G08] 静态方法与属性
来源：http://dali.jinghuilouyu.cn/Article/details/gtyfhybpnt.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.nanxinkj.top/Article/details/gtvghzolou.html

PHP:  public static function f() {}
来源：http://dali.shangyingyoupin.top/Article/details/gtazudgbyz.html

JS:   static f() {}
来源：http://dali.chenjidiqi.icu/Article/details/gtarmmjzbj.html

TS:   static f(): void {}
来源：http://dali.sxryk.cn/Article/details/gtfxconlsm.html

Java: static void f() {}
来源：http://dali.birdmap.top/Article/details/gtstfcbick.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsfkunrwc.html

Ruby: def self.f; end
来源：http://dali.dashuyun.cn/Article/details/gtgasbchft.html

C#:   public static void F() {}
来源：http://dali.gogol.net.cn/Article/details/gtcsjdoyvs.html

[G09] 接口 / 抽象类
来源：http://dali.hfpthk.cn/Article/details/gtpjtwfymf.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yangfankeji.com/Article/details/gtopvrlqay.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.shzxlz.cn/Article/details/gttmowwwww.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.c1oappe.top/Article/details/gtlyilbwuy.html

TS:   interface Shape { area(): number; }
来源：http://dali.xinyue.icu/Article/details/gtcegbeuhi.html

Java: interface Shape { double area(); }
来源：http://dali.yanxiufei.cn/Article/details/gtrehsdqnr.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.316326.xyz/Article/details/gtbemnspoc.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.svipenyu.cn/Article/details/gtccdkcvop.html

C#:   interface IShape { double Area(); }
来源：http://dali.jqgufenzy.top/Article/details/gtbyzkvvlg.html

[G10] 访问控制
来源：http://dali.shzxlz.cn/Article/details/gtxwbvbxvw.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.tian-w.cn/Article/details/gtmheqebdj.html

PHP:  public / protected / private
来源：http://dali.shanyushiyangtech.top/Article/details/gtutagypys.html

JS:   #private 字段；其余公开
来源：http://dali.svipenyu.cn/Article/details/gtrihuditn.html

TS:   public / protected / private
来源：http://dali.vqdsnc.cn/Article/details/gtewjxhpbz.html

Java: public / protected / private / 默认包级
来源：http://dali.wangdashe.top/Article/details/gtysdudrtx.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yongpay.top/Article/details/gtyppfujjy.html

Ruby: public / protected / private
来源：http://dali.yuanzhike.top/Article/details/gtvxuxwypx.html

C#:   public / protected / private / internal
来源：http://dali.wangdashe.top/Article/details/gtuysrceye.html

[G11] getter / setter
来源：http://dali.jiagoushi.top/Article/details/gtthqqeock.html

Py:   @property 与 @x.setter
来源：http://dali.316326.xyz/Article/details/gttowfabwb.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.tian-w.cn/Article/details/gtkjxogsto.html

JS:   get name() { return this._name; }
来源：http://dali.hysaishi.cn/Article/details/gthiyvpxqs.html

TS:   get name(): string { return this._name; }
来源：http://dali.shzxlz.cn/Article/details/gtpnfsiysw.html

Java: public String getName() { return name; }
来源：http://dali.yuxming.cn/Article/details/gtynnwfszg.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.fengsongda.top/Article/details/gtqoyxxywb.html

Ruby: attr_accessor :name
来源：http://dali.yuanzhike.top/Article/details/gtlrccrcle.html

C#:   public string Name { get; set; }
来源：http://dali.jlsjyb.cn/Article/details/gtxwreivzj.html

[G12] 对象转字符串
来源：http://dali.sweek.top/Article/details/gtlhqatdjz.html

Py:   def __str__(self): return self.name
来源：http://dali.aibaodan.cn/Article/details/gtqcetpbrz.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hnqzz.top/Article/details/gttfoqbbwi.html

JS:   toString() { return this.name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtsqukysci.html

TS:   toString(): string { return this.name; }
来源：http://dali.shzxlz.cn/Article/details/gtgnaprhwh.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhixingplan.top/Article/details/gtnzacdslt.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.ybcxt.top/Article/details/gtqeuhmzqi.html

Ruby: def to_s; @name; end
来源：http://dali.zhoulong.xyz/Article/details/gtgwifxzyx.html

C#:   public override string ToString() => Name;
来源：http://dali.cqqwz.cn/Article/details/gtglotgoqw.html

[G13] 判断对象类型
来源：http://dali.bjfxy.top/Article/details/gtljmhggce.html

Py:   isinstance(u, User)
来源：http://dali.yangfankeji.com/Article/details/gtnekzcaum.html

PHP:  $u instanceof User
来源：http://dali.nwbrower.top/Article/details/gtjzxqcjim.html

JS:   u instanceof User
来源：http://dali.ydzc1.top/Article/details/gtloegrnde.html

TS:   u instanceof User
来源：http://dali.fzhhl.top/Article/details/gtjbeindbv.html

Java: u instanceof User
来源：http://dali.ywan-chungtsiang.top/Article/details/gtslqxmyru.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.shanyushiyangtech.top/Article/details/gthxxtyehp.html

Ruby: u.is_a?(User)
来源：http://dali.zhijiandao.cn/Article/details/gtlgbvgwkx.html

C#:   u is User
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvyubsoil.html

[G14] 数据类 / record
来源：http://dali.yongpay.top/Article/details/gtxgovhkia.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.shzxlz.cn/Article/details/gtlfqrfxfp.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.ivvv.top/Article/details/gtckoqrrbr.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.meibo888.top/Article/details/gtvnbuohnr.html

TS:   type User = { name: string; age: number };
来源：http://dali.jinyuanbaomall.cn/Article/details/gteobqwxej.html

Java: record User(String name, int age) {}
来源：http://dali.nwbrower.top/Article/details/gttrdmksqc.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hnqzz.top/Article/details/gthzblbqjs.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhengqikj.top/Article/details/gtnesxosub.html

C#:   record User(string Name, int Age);
来源：http://dali.fengsongda.top/Article/details/gtaerreqjv.html

[G15] 枚举
来源：http://dali.haohaochexian.top/Article/details/gtwuruleya.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.guowangkeji.top/Article/details/gtbxqzhglc.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.gaohongyu789.top/Article/details/gtocqdfbvp.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.havefunace.top/Article/details/gtjrurycdd.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.havefunace.top/Article/details/gtgicvfwau.html

Java: enum Color { RED, GREEN }
来源：http://dali.meibo888.top/Article/details/gtyxjclkkb.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.316326.xyz/Article/details/gtfzrrrwkq.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jqgfzy.top/Article/details/gtykigfnki.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yj20258888.top/Article/details/gtadcwmsjw.html

[G16] 对象转数组 / 字典
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrnhxnhyw.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.shuidangran.top/Article/details/gtvhprpkqc.html

PHP:  get_object_vars($obj);
来源：http://dali.cucudq.cn/Article/details/gttulzxnbb.html

JS:   Object.entries(obj)
来源：http://dali.guowangkeji.top/Article/details/gtagygxagp.html

TS:   Object.entries(obj)
来源：http://dali.hysaishi.cn/Article/details/gtdmslzytc.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtalbotpzx.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.havefunace.top/Article/details/gtwzbvdtxl.html

Ruby: obj.instance_variables
来源：http://dali.vqdsnc.cn/Article/details/gtxlzlngiq.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yueranfly.top/Article/details/gtybupdyvn.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gthfolmxmj.html

H. 异常与错误处理
来源：http://dali.shuidangran.top/Article/details/gtkianrkup.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtxwbhpgbt.html

[H01] try / catch 基础
来源：http://dali.gaohongyu789.top/Article/details/gtsklylvwj.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yongpay.top/Article/details/gtzopqikmi.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhixingplan.top/Article/details/gteygelitr.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.ybcxt.top/Article/details/gthozvjdsp.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yangfankeji.com/Article/details/gtxtjcdpss.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtclkekexy.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.cqqwz.cn/Article/details/gthqyrrejh.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gtnsezpvln.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.shangyingyoupin.top/Article/details/gtttgvmjwk.html

[H02] finally / ensure 收尾
来源：http://dali.ivvv.top/Article/details/gtlqonazhv.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.ivvv.top/Article/details/gtktbugwda.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jlsjyb.cn/Article/details/gthrdgmrgt.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.sufxvd.cn/Article/details/gtnjtypest.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yj20258.top/Article/details/gtdwcuodey.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.shuidangran.top/Article/details/gtqcejodaq.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdgtqgohp.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yj20258.top/Article/details/gtbveuszvg.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.cqqwz.cn/Article/details/gtbcmmpopp.html

[H03] 主动抛出异常
来源：http://dali.shzxlz.cn/Article/details/gtawxtotqk.html

Py:   raise ValueError("错误信息")
来源：http://dali.quarkkingdee.top/Article/details/gtprpforbn.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hnqzz.top/Article/details/gtgmxlxcrg.html

JS:   throw new Error("错误信息");
来源：http://dali.tian-w.cn/Article/details/gtigmrjvim.html

TS:   throw new Error("错误信息");
来源：http://dali.yuxming.cn/Article/details/gtqgfnyzuc.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jinqigufen.top/Article/details/gtaalndnvs.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.chenzaomai.com/Article/details/gtzjwnqyou.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yongpay.top/Article/details/gtjjyqylwd.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.aizwys.cn/Article/details/gtsygonfsf.html

[H04] 自定义异常类型
来源：http://dali.sxryk.cn/Article/details/gtdcrtywwo.html

Py:   class MyError(Exception): pass
来源：http://dali.nanxuanxn.top/Article/details/gtxitjgutc.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.redwolf501.top/Article/details/gthpqdxmwz.html

JS:   class MyError extends Error {}
来源：http://dali.iojbl.cn/Article/details/gteurxpwzy.html

TS:   class MyError extends Error {}
来源：http://dali.havefunace.top/Article/details/gtpmnvmkyc.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jianghu66.top/Article/details/gtgzhoarah.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jinghuilouyu.cn/Article/details/gtjoywtcom.html

Ruby: class MyError < StandardError; end
来源：http://dali.chenjidiqi.icu/Article/details/gtyqdxpkwy.html

C#:   class MyException : Exception {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtkwbhwshu.html

[H05] 捕获特定类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzulmtxvj.html

Py:   except ValueError as e:
来源：http://dali.chenlongwang.top/Article/details/gtlfmatiyb.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jqgfzy.top/Article/details/gtzziyufiq.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jinqigufen.top/Article/details/gtnidiccwx.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.gotoacloud.top/Article/details/gtbkmkllin.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.bjfxy.top/Article/details/gtxspxitie.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.hnqzz.top/Article/details/gtgeeamwgw.html

Ruby: rescue ArgumentError => e
来源：http://dali.yj20258888.top/Article/details/gtwnyzodvg.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.nanxinkj.top/Article/details/gtclioemdu.html

[H06] 可选值 / 空值安全访问
来源：http://dali.c1oappe.top/Article/details/gtzilwavpi.html

Py:   value = d.get("k") or default
来源：http://dali.yvedp.cn/Article/details/gtozcytict.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.snrcjt.cn/Article/details/gtsyhhgesl.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxfupcdgw.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.birdmap.top/Article/details/gtadaqrnsx.html


<!-- 参考信息 -->