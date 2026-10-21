代发 wailian999

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jianghu66.top/Article/details/gtinxzikkg.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtsjzowjfp.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yueranfly.top/Article/details/gtzvtiupcg.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.aizwys.cn/Article/details/gtqwyvmixx.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.havefunace.top/Article/details/gtgybjzwvs.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.hnqzz.top/Article/details/gtmfqgfglj.html

[F03] 写入文件（覆盖）
来源：http://dali.redwolf501.top/Article/details/gtgzvxsgzo.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.fzhhl.top/Article/details/gttldpjzqp.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.cashguo.top/Article/details/gtwfywugxh.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ehwqpu.com/Article/details/gtceytcbxj.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yonumen.top/Article/details/gttgyppukk.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yangfankeji.com/Article/details/gtfyxkfxkg.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jinghuilouyu.cn/Article/details/gtuspbqyjc.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.xziqi.cn/Article/details/gttmudfidh.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.cucudq.cn/Article/details/gtxxyhnvfg.html

[F04] 追加写入文件
来源：http://dali.tanke756.top/Article/details/gtbqawcotp.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.ehwqpu.com/Article/details/gtijmgniun.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jlsjyb.cn/Article/details/gtsaaxvwyr.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ydzc1.top/Article/details/gthhmumngi.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.iojbl.cn/Article/details/gtdhorsbgi.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.c1oappe.top/Article/details/gtxxhroiaz.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.hysaishi.cn/Article/details/gtlaldjekv.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yuxming.cn/Article/details/gtdkkqenif.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.pycfn.com/Article/details/gtlxdscqtx.html

[F05] 判断文件或目录是否存在
来源：http://dali.shangyingyoupin.top/Article/details/gtfnvrlfop.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.hnxiangtu.top/Article/details/gttuqijjbc.html

PHP:  file_exists("a.txt");
来源：http://dali.shuidangran.top/Article/details/gteomcfbws.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yongpay.top/Article/details/gtslkhizor.html

TS:   fs.existsSync("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtokuwtgox.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yonumen.top/Article/details/gtnxonmsvt.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.aizwys.cn/Article/details/gteqrijmds.html

Ruby: File.exist?("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtcmidifsn.html

C#:   File.Exists("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtvfoprbpm.html

[F06] 删除文件
来源：http://dali.gogol.net.cn/Article/details/gtgnjzasvr.html

Py:   os.remove("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtztvoleni.html

PHP:  unlink("a.txt");
来源：http://dali.daxiang520.top/Article/details/gtzppbcxtv.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtddwdhpkq.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtkgchhnfb.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.gzhubu.top/Article/details/gtgidoshzf.html

Go:   os.Remove("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtdfiounct.html

Ruby: File.delete("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtajwrjsok.html

C#:   File.Delete("a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwtfndtmz.html

[F07] 创建目录（含多级）
来源：http://dali.hfpthk.cn/Article/details/gtkjryuvqk.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jinqigfzy.top/Article/details/gtcgpwaicf.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.bjfxy.top/Article/details/gtuyaipcwn.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sysykeji.top/Article/details/gtcbixcgyk.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhengqikj.top/Article/details/gtjxxwjhow.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.redwolf501.top/Article/details/gtuescqoii.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.gzhubu.top/Article/details/gtrrwnzyjj.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.xylfe.cn/Article/details/gthznsuags.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.hammf.cn/Article/details/gtsdygmlja.html

[F08] 遍历目录
来源：http://dali.gogol.net.cn/Article/details/gtjokbqgjb.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.xziqi.cn/Article/details/gtachvxack.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jianghu66.top/Article/details/gtfvbhubxo.html

JS:   fs.readdirSync("dir")
来源：http://dali.jinghuilouyu.cn/Article/details/gtcshfsfaq.html

TS:   fs.readdirSync("dir")
来源：http://dali.yueranfly.top/Article/details/gtupwdgaem.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.cucudq.cn/Article/details/gtyoxripne.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.hysaishi.cn/Article/details/gthoefcnhj.html

Ruby: Dir.children("dir")
来源：http://dali.fzhhl.top/Article/details/gttxogdgxf.html

C#:   Directory.GetFiles("dir")
来源：http://dali.meibo888.top/Article/details/gtrtryrvzx.html

[F09] 获取文件大小
来源：http://dali.ydzc1.top/Article/details/gtqvggsvop.html

Py:   os.path.getsize("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtnlaxhhjz.html

PHP:  filesize("a.txt");
来源：http://dali.cqqwz.cn/Article/details/gtceempkwr.html

JS:   fs.statSync("a.txt").size
来源：http://dali.haohaochexian.top/Article/details/gtssmyvdwo.html

TS:   fs.statSync("a.txt").size
来源：http://dali.fengsongda.top/Article/details/gtrdlieuwf.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.fzhhl.top/Article/details/gtclrivcvw.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yj202588.top/Article/details/gtfrjzovmn.html

Ruby: File.size("a.txt")
来源：http://dali.ivvv.top/Article/details/gthvpzdxrf.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.xylfe.cn/Article/details/gtppiyxlxk.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.pycfn.com/Article/details/gtvtmygkkw.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpzkgtzdh.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.guowangkeji.top/Article/details/gtrxxpndlh.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtvvtyubol.html

TS:   path.extname("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtjzvwsgpr.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.havefunace.top/Article/details/gtnryvsmoj.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgrpayaga.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gttrfcykgz.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.sweek.top/Article/details/gtmladqtxu.html

[F11] 复制与移动文件
来源：http://dali.jiagoushi.top/Article/details/gtxbcafdds.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.chenzaomai.com/Article/details/gteyojxixr.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gtuknlhvot.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hnxiangtu.top/Article/details/gttdvfjkmp.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.nanxinkj.top/Article/details/gtkrrffrim.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yonumen.top/Article/details/gtmvcibbag.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.iojbl.cn/Article/details/gtoreeusbb.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.shuidangran.top/Article/details/gtygphficw.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gtisnlkjfl.html

[F12] CSV 读写
来源：http://dali.zhongyouzk.top/Article/details/gtinqzvcla.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yuxming.cn/Article/details/gtmacmznli.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yvedp.cn/Article/details/gteqqxxsdo.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.quarkkingdee.top/Article/details/gtqdoutypw.html

TS:   // 同上
来源：http://dali.fzhhl.top/Article/details/gtcnhinnii.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.xinyue.icu/Article/details/gtjbrkabbg.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.andypj.xyz/Article/details/gtytuyirxp.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yongpay.top/Article/details/gterhndeww.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.guannengcc.top/Article/details/gtdzwdslka.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtvasbwzrl.html

G. 面向对象
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjpcbgopf.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtjzcqlrvo.html

[G01] 定义类
来源：http://dali.cheryme.top/Article/details/gtxtweieou.html

Py:   class User: pass
来源：http://dali.sufxvd.cn/Article/details/gtnkphofmq.html

PHP:  class User {}
来源：http://dali.meibo888.top/Article/details/gtdenkrwaj.html

JS:   class User {}
来源：http://dali.vqdsnc.cn/Article/details/gtoulngfpv.html

TS:   class User { name: string = ""; }
来源：http://dali.tanke756.top/Article/details/gtrsxtdpqu.html

Java: class User {}
来源：http://dali.ydzc1.top/Article/details/gtrnnqbzyw.html

Go:   type User struct { Name string }
来源：http://dali.yanxiufei.cn/Article/details/gtrdnqhexg.html

Ruby: class User; end
来源：http://dali.hnqzz.top/Article/details/gtkroajauw.html

C#:   class User {}
来源：http://dali.ehwqpu.com/Article/details/gtywamnjlf.html

[G02] 构造函数
来源：http://dali.chenjidiqi.icu/Article/details/gtzoknprks.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.fzhhl.top/Article/details/gtbaptisbm.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.tian-w.cn/Article/details/gtdqqklbmr.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.xuanzx.com/Article/details/gtodxqdhxv.html

TS:   constructor(public name: string) {}
来源：http://dali.zhongyouzk.top/Article/details/gtasozkukd.html

Java: User(String name) { this.name = name; }
来源：http://dali.shangyingyoupin.top/Article/details/gthuugitym.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.c1oappe.top/Article/details/gttodmrgiq.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.xuetiantiany.cn/Article/details/gtmictzujz.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yongpay.top/Article/details/gtwhaknajx.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gtfujnqfwc.html

Py:   self.name = "x"
来源：http://dali.guannengcc.top/Article/details/gthoatjzbj.html

PHP:  public string $name = "x";
来源：http://dali.gaohongyu789.top/Article/details/gtelcoshbc.html

JS:   this.name = "x";
来源：http://dali.wangshuangyany.cn/Article/details/gtouurfnhj.html

TS:   name: string = "x";
来源：http://dali.hongshengwenyu.top/Article/details/gtregxbvay.html

Java: private String name;
来源：http://dali.zhoulong.xyz/Article/details/gtqzwmmlfw.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hammf.cn/Article/details/gtnycoqwqq.html

Ruby: @name = "x"
来源：http://dali.hfpthk.cn/Article/details/gtjkmhhnax.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yj202588.top/Article/details/gtbklxjgso.html

[G04] 定义方法
来源：http://dali.ehwqpu.com/Article/details/gtukedkpyk.html

Py:   def greet(self): return self.name
来源：http://dali.zhixingplan.top/Article/details/gtyxijmpig.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zdqjudy.top/Article/details/gtqzwqaoje.html

JS:   greet() { return this.name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxavpvsfp.html

TS:   greet(): string { return this.name; }
来源：http://dali.316326.xyz/Article/details/gtqhakgkws.html

Java: String greet() { return name; }
来源：http://dali.yj202588.top/Article/details/gtdgostdit.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.c1oappe.top/Article/details/gtyxegzugq.html

Ruby: def greet; @name; end
来源：http://dali.hysaishi.cn/Article/details/gtrjkawwyz.html

C#:   public string Greet() => Name;
来源：http://dali.shanyushiyangtech.top/Article/details/gtordgulzi.html

[G05] 继承
来源：http://dali.cdnleiting.top/Article/details/gtlbdqncni.html

Py:   class Admin(User): pass
来源：http://dali.chenzaomai.com/Article/details/gtqdgnxxvc.html

PHP:  class Admin extends User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjhlvswmq.html

JS:   class Admin extends User {}
来源：http://dali.zycfv.cn/Article/details/gtjpgdlnkj.html

TS:   class Admin extends User {}
来源：http://dali.xylfe.cn/Article/details/gtlcevxkkj.html

Java: class Admin extends User {}
来源：http://dali.nanxinkj.top/Article/details/gtqmqxgvfo.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jinqigfzy.top/Article/details/gtgizvjfbw.html

Ruby: class Admin < User; end
来源：http://dali.aizwys.cn/Article/details/gtzzvguktm.html

C#:   class Admin : User {}
来源：http://dali.yongpay.top/Article/details/gtigqijuel.html

[G06] 重写方法
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwkkyjlxt.html

Py:   def greet(self): return "admin"
来源：http://dali.quarkkingdee.top/Article/details/gtlmusdpfb.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.ehwqpu.com/Article/details/gtrvmwmlal.html

JS:   greet() { return "admin"; }
来源：http://dali.zycfv.cn/Article/details/gtsdujbwxv.html

TS:   greet(): string { return "admin"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtbxyemmgp.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.guannengcc.top/Article/details/gtnaiizpyg.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.aizwys.cn/Article/details/gtucnkqhix.html

Ruby: def greet; "admin"; end
来源：http://dali.gzhubu.top/Article/details/gthkjoddgb.html

C#:   public override string Greet() => "admin";
来源：http://dali.yangfankeji.com/Article/details/gtodickwpn.html

[G07] 调用父类方法
来源：http://dali.sufxvd.cn/Article/details/gtacxkmceu.html

Py:   super().greet()
来源：http://dali.redwolf501.top/Article/details/gtnwzrrser.html

PHP:  parent::greet();
来源：http://dali.cdnleiting.top/Article/details/gtpuzgbqgg.html

JS:   super.greet();
来源：http://dali.jlsjyb.cn/Article/details/gtwedyamnm.html

TS:   super.greet();
来源：http://dali.xuanzx.com/Article/details/gtatvxvoue.html

Java: super.greet();
来源：http://dali.ybcxt.top/Article/details/gtspienhfr.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jqgufenzy.top/Article/details/gtqzdqexne.html

Ruby: super
来源：http://dali.cdnleiting.top/Article/details/gtpjtderru.html

C#:   base.Greet();
来源：http://dali.xinyue.icu/Article/details/gtyfmatvxg.html

[G08] 静态方法与属性
来源：http://dali.cucudq.cn/Article/details/gtaxflqjri.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.svipenyu.cn/Article/details/gtofkewwao.html

PHP:  public static function f() {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtepeksbag.html

JS:   static f() {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmihzvvsw.html

TS:   static f(): void {}
来源：http://dali.nwbrower.top/Article/details/gtklrsqurt.html

Java: static void f() {}
来源：http://dali.smart0.xyz/Article/details/gtgtqhwprb.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jqgfzy.top/Article/details/gtsrijjwrj.html

Ruby: def self.f; end
来源：http://dali.wangshuangyany.cn/Article/details/gtinicwqae.html

C#:   public static void F() {}
来源：http://dali.yongpay.top/Article/details/gtmasyuvrf.html

[G09] 接口 / 抽象类
来源：http://dali.gzhubu.top/Article/details/gtljmlrpdl.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.hywenlv.cn/Article/details/gtbcvsosmr.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.sufxvd.cn/Article/details/gtkdgvxwya.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yuanzhike.top/Article/details/gtethrlmuw.html

TS:   interface Shape { area(): number; }
来源：http://dali.nwbrower.top/Article/details/gtgsgpdwnk.html

Java: interface Shape { double area(); }
来源：http://dali.zhongyouzk.top/Article/details/gtnliahybm.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yj202588.top/Article/details/gtmluuhpul.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.sufxvd.cn/Article/details/gtvqfbtooa.html

C#:   interface IShape { double Area(); }
来源：http://dali.jiagoushi.top/Article/details/gtemaspihy.html

[G10] 访问控制
来源：http://dali.pengpengdd.cyou/Article/details/gtrvrzgjfx.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.vqdsnc.cn/Article/details/gtfmmfglrx.html

PHP:  public / protected / private
来源：http://dali.hysaishi.cn/Article/details/gtjmvffdca.html

JS:   #private 字段；其余公开
来源：http://dali.dashuyun.cn/Article/details/gtnynnlecf.html

TS:   public / protected / private
来源：http://dali.hammf.cn/Article/details/gtupfbzqic.html

Java: public / protected / private / 默认包级
来源：http://dali.hywenlv.cn/Article/details/gtbacbdrlw.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.chenjidiqi.icu/Article/details/gtmqqseviv.html

Ruby: public / protected / private
来源：http://dali.daxiang520.top/Article/details/gtukuamdgp.html

C#:   public / protected / private / internal
来源：http://dali.xuanzx.com/Article/details/gtgsgjabqa.html

[G11] getter / setter
来源：http://dali.shanyushiyangtech.top/Article/details/gthigxnblt.html

Py:   @property 与 @x.setter
来源：http://dali.mhx1999.top/Article/details/gtmqztceof.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.kuanghao11.cn/Article/details/gtcomphxjd.html

JS:   get name() { return this._name; }
来源：http://dali.fzhhl.top/Article/details/gtnwkkrklt.html

TS:   get name(): string { return this._name; }
来源：http://dali.xylfe.cn/Article/details/gtxghzhpcg.html

Java: public String getName() { return name; }
来源：http://dali.jiagoushi.top/Article/details/gtmqscdpgm.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yuanzhike.top/Article/details/gtafyrdjph.html

Ruby: attr_accessor :name
来源：http://dali.guowangkeji.top/Article/details/gtxicnembx.html

C#:   public string Name { get; set; }
来源：http://dali.quarkkingdee.top/Article/details/gtqryewjxd.html

[G12] 对象转字符串
来源：http://dali.jiagoushi.top/Article/details/gtkxhtoffh.html

Py:   def __str__(self): return self.name
来源：http://dali.fzhhl.top/Article/details/gtholrwvyz.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hysaishi.cn/Article/details/gtwfcwlqsh.html

JS:   toString() { return this.name; }
来源：http://dali.xinyue.icu/Article/details/gtaradosnm.html

TS:   toString(): string { return this.name; }
来源：http://dali.mhx1999.top/Article/details/gtfmoibpnz.html

Java: @Override public String toString() { return name; }
来源：http://dali.jqgfzy.top/Article/details/gterbuuell.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhengqikj.top/Article/details/gteqhhgcey.html

Ruby: def to_s; @name; end
来源：http://dali.cqqwz.cn/Article/details/gtexiuiniz.html

C#:   public override string ToString() => Name;
来源：http://dali.ppjwa.cn/Article/details/gtyhdwnpoo.html

[G13] 判断对象类型
来源：http://dali.guannengcc.top/Article/details/gtramokhqd.html

Py:   isinstance(u, User)
来源：http://dali.chenzaomai.com/Article/details/gtzlmalilx.html

PHP:  $u instanceof User
来源：http://dali.nanxinkj.top/Article/details/gtzkjtivym.html

JS:   u instanceof User
来源：http://dali.hongshengwenyu.top/Article/details/gtzmkkokpc.html

TS:   u instanceof User
来源：http://dali.jlsjyb.cn/Article/details/gtvacxkfqq.html

Java: u instanceof User
来源：http://dali.ppjwa.cn/Article/details/gtimjlffxn.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkpduqfwm.html

Ruby: u.is_a?(User)
来源：http://dali.gaohongyu789.top/Article/details/gtswncrzuc.html

C#:   u is User
来源：http://dali.fzhhl.top/Article/details/gtxyhrjmth.html

[G14] 数据类 / record
来源：http://dali.kuanghao11.cn/Article/details/gtnlggxwwq.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.xylfe.cn/Article/details/gtqxccqlpq.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.wangshuangyany.cn/Article/details/gtovockjam.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.chenzaomai.com/Article/details/gtgnrbuzkb.html

TS:   type User = { name: string; age: number };
来源：http://dali.yongpay.top/Article/details/gthhwheszx.html

Java: record User(String name, int age) {}
来源：http://dali.xziqi.cn/Article/details/gtyetjtlow.html

Go:   type User struct { Name string; Age int }
来源：http://dali.haohaochexian.top/Article/details/gtpdthouam.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hongshengwenyu.top/Article/details/gtxcstxcwj.html

C#:   record User(string Name, int Age);
来源：http://dali.quarkkingdee.top/Article/details/gtjaoarbyn.html

[G15] 枚举
来源：http://dali.jqgufenzy.top/Article/details/gtnhlcerlg.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.guannengcc.top/Article/details/gtwtxxhteo.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yanxiufei.cn/Article/details/gtsiwldjje.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.316326.xyz/Article/details/gtcpfgccxc.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.birdmap.top/Article/details/gtnhyogeud.html

Java: enum Color { RED, GREEN }
来源：http://dali.gogol.net.cn/Article/details/gtfuasgpnv.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.tianlin.xyz/Article/details/gtxudgkzrb.html

Ruby: Color = %i[red green].freeze
来源：http://dali.iojbl.cn/Article/details/gtdbofkkvu.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.0kj1m.cn/Article/details/gtgdpnvgza.html

[G16] 对象转数组 / 字典
来源：http://dali.jinqigufen.top/Article/details/gthkjohrdv.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.shangyingyoupin.top/Article/details/gtmgiopyiy.html

PHP:  get_object_vars($obj);
来源：http://dali.xinyue.icu/Article/details/gtmqtaxuuj.html

JS:   Object.entries(obj)
来源：http://dali.zycfv.cn/Article/details/gtscqiumff.html

TS:   Object.entries(obj)
来源：http://dali.cheryme.top/Article/details/gtrikjulzc.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.cqqwz.cn/Article/details/gtbvfolvtv.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.xinyue.icu/Article/details/gtltqpvhmo.html

Ruby: obj.instance_variables
来源：http://dali.shanyushiyangtech.top/Article/details/gtgcbfsmva.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.ivvv.top/Article/details/gtrmgurwaj.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtfghhzfac.html

H. 异常与错误处理
来源：http://dali.sysykeji.top/Article/details/gtcxbkscmd.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gttuexnxnt.html

[H01] try / catch 基础
来源：http://dali.dashuyun.cn/Article/details/gtbrmctwso.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.ivvv.top/Article/details/gtnqxjrebg.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.0kj1m.cn/Article/details/gthyjuzmnh.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.xuanzx.com/Article/details/gthtbjpxwv.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.sxryk.cn/Article/details/gtgvgaxhjq.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.fengsongda.top/Article/details/gtdigwtvht.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yj20258.top/Article/details/gtdcmqciqp.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.redwolf501.top/Article/details/gtdqcbrvym.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.nwbrower.top/Article/details/gtrqzzbmsm.html

[H02] finally / ensure 收尾
来源：http://dali.ybcxt.top/Article/details/gtumwbzsvi.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.ivvv.top/Article/details/gthlcupgrb.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtwdvsgcbg.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ehwqpu.com/Article/details/gtkhgfrbgw.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yvedp.cn/Article/details/gtjzujmooh.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.smart0.xyz/Article/details/gtjykliahb.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.andypj.xyz/Article/details/gtwzxtlksd.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jyoumei.cn/Article/details/gttvgoggli.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yangfankeji.com/Article/details/gtgqzippbl.html

[H03] 主动抛出异常
来源：http://dali.iojbl.cn/Article/details/gtthyinzym.html

Py:   raise ValueError("错误信息")
来源：http://dali.jqgfzy.top/Article/details/gtbihugolv.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.shangyingyoupin.top/Article/details/gtizdukwir.html

JS:   throw new Error("错误信息");
来源：http://dali.shzxlz.cn/Article/details/gtsxiwmcjg.html

TS:   throw new Error("错误信息");
来源：http://dali.cheryme.top/Article/details/gtblyyzlrl.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkbuobpst.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.cucudq.cn/Article/details/gtlojkxzhn.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhixingplan.top/Article/details/gtrdpmnuqe.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jinyuanbaomall.cn/Article/details/gthujpeqxe.html

[H04] 自定义异常类型
来源：http://dali.zhongyouzk.top/Article/details/gtqbrujdke.html

Py:   class MyError(Exception): pass
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttlsnvajb.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.nanxuanxn.top/Article/details/gtiqswqtwd.html

JS:   class MyError extends Error {}
来源：http://dali.zhixingplan.top/Article/details/gtldodrntm.html

TS:   class MyError extends Error {}
来源：http://dali.redwolf501.top/Article/details/gtcbpyitvg.html

Java: class MyException extends RuntimeException {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtywjhqbno.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jqgufenzy.top/Article/details/gtgkxzlmtu.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhiwuduotai.top/Article/details/gtwrqbfiou.html

C#:   class MyException : Exception {}
来源：http://dali.cqqwz.cn/Article/details/gtixgsckoi.html

[H05] 捕获特定类型
来源：http://dali.quarkkingdee.top/Article/details/gtzzhqwwhx.html

Py:   except ValueError as e:
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzcpgcivj.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhijiandao.cn/Article/details/gtrbphmthm.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.cheryme.top/Article/details/gtktclivyq.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gtrlgwixzk.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtfxxbuknb.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.9152youxi.cn/Article/details/gtzgqvhuuf.html

Ruby: rescue ArgumentError => e
来源：http://dali.shuidangran.top/Article/details/gtpwrjuphf.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.mhx1999.top/Article/details/gtbhewugtg.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yanxiufei.cn/Article/details/gtmisgnnxt.html

Py:   value = d.get("k") or default
来源：http://dali.andypj.xyz/Article/details/gtvmqkmlxx.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.cashguo.top/Article/details/gtlxbrdsbt.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.gogol.net.cn/Article/details/gtqlxhrvtq.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.guowangkeji.top/Article/details/gtrmoaievz.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.xinyue.icu/Article/details/gtjtbprctx.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jlsjyb.cn/Article/details/gtwmtmobkp.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yvedp.cn/Article/details/gtxfwwyiav.html

C#:   obj?.A?.B ?? default
来源：http://dali.tanke756.top/Article/details/gtfciaazjt.html


<!-- 参考信息 -->