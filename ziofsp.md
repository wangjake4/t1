代发 wailian999

[F01] 读取整个文件
来源：http://dali.ybcxt.top/Article/details/gtjqrbndrg.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yj20258888.top/Article/details/gtsqeudjwy.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jiagoushi.top/Article/details/gtzxgmsumx.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.tian-w.cn/Article/details/gtwmbhwode.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jqgufenzy.top/Article/details/gtyagspmvq.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.shzxlz.cn/Article/details/gtwvgyobjr.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.xinyue.icu/Article/details/gtxjgjigek.html

Ruby: File.read("a.txt")
来源：http://dali.yj202588.top/Article/details/gtmdlxgtuf.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yvedp.cn/Article/details/gtejyiddml.html

[F02] 逐行读取文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtaxrkqebs.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yvedp.cn/Article/details/gtthzenued.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yonumen.top/Article/details/gtduwnsfko.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.tianlin.xyz/Article/details/gtjdyelotu.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jianghu66.top/Article/details/gtqoxarhns.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.guannengcc.top/Article/details/gtrwmgimlg.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.dianchejie.cn/Article/details/gtxsflshck.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hysaishi.cn/Article/details/gteuurtesr.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.guannengcc.top/Article/details/gtskifjers.html

[F03] 写入文件（覆盖）
来源：http://dali.yonumen.top/Article/details/gtudzfprmf.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jiagoushi.top/Article/details/gtowkgnmej.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.redwolf501.top/Article/details/gtpoyhoxau.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.feifeiyinyue.top/Article/details/gtbxgoajfp.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.havefunace.top/Article/details/gtesctqjwb.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yonumen.top/Article/details/gtntizflzq.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yanxiufei.cn/Article/details/gtbftoyosm.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.tianlin.xyz/Article/details/gtuyhakium.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yvedp.cn/Article/details/gtkkcnrimf.html

[F04] 追加写入文件
来源：http://dali.sufxvd.cn/Article/details/gteptvfxyf.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yonumen.top/Article/details/gtgmquyewj.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.vqdsnc.cn/Article/details/gtjecbrwlo.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.redwolf501.top/Article/details/gtoyrakyzb.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yvedp.cn/Article/details/gtpfirgzib.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.cdnleiting.top/Article/details/gtgdsrohvd.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jyoumei.cn/Article/details/gtjpcvdrvg.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.xuanzx.com/Article/details/gtbtjsszzs.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.redwolf501.top/Article/details/gtckwcjtmi.html

[F05] 判断文件或目录是否存在
来源：http://dali.xuanzx.com/Article/details/gtbvclhzvz.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.wangdashe.top/Article/details/gtbdwpvrar.html

PHP:  file_exists("a.txt");
来源：http://dali.nwbrower.top/Article/details/gtklbivhrc.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtxjnmiroi.html

TS:   fs.existsSync("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtzmvunetw.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.gotoacloud.top/Article/details/gtgxkusvjp.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jinqigufen.top/Article/details/gtbaatowmj.html

Ruby: File.exist?("a.txt")
来源：http://dali.tanke756.top/Article/details/gtnwrvayla.html

C#:   File.Exists("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtigwzhfhx.html

[F06] 删除文件
来源：http://dali.jlsjyb.cn/Article/details/gtrrqzfcsj.html

Py:   os.remove("a.txt")
来源：http://dali.yonumen.top/Article/details/gtdxbntfas.html

PHP:  unlink("a.txt");
来源：http://dali.yuxming.cn/Article/details/gtotjyycun.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtsajsuiom.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.xziqi.cn/Article/details/gtbuqfyzod.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zycfv.cn/Article/details/gtqsmbapqt.html

Go:   os.Remove("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyjbzkxwe.html

Ruby: File.delete("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtxvpbzsxc.html

C#:   File.Delete("a.txt");
来源：http://dali.xylfe.cn/Article/details/gtxvcmrmse.html

[F07] 创建目录（含多级）
来源：http://dali.yanxiufei.cn/Article/details/gtsoshvaes.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.pengpengdd.cyou/Article/details/gtdhnbvpkb.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.pengpengdd.cyou/Article/details/gthmvxvqbx.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhongyouzk.top/Article/details/gtpqrakuef.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.0kj1m.cn/Article/details/gttfxcugmk.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhongyouzk.top/Article/details/gtypqfuufg.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yueranfly.top/Article/details/gtgnemjfhs.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.xuanzx.com/Article/details/gtpddhiubx.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.hnxiangtu.top/Article/details/gtuwgcrasu.html

[F08] 遍历目录
来源：http://dali.meibo888.top/Article/details/gteficgvud.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.andypj.xyz/Article/details/gtiithqwpd.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.haohaochexian.top/Article/details/gteblwsrcz.html

JS:   fs.readdirSync("dir")
来源：http://dali.cucudq.cn/Article/details/gtpxkxjenq.html

TS:   fs.readdirSync("dir")
来源：http://dali.sxryk.cn/Article/details/gtremhnyme.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.mhx1999.top/Article/details/gtirxfcsaq.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.kuanghao11.cn/Article/details/gtfzifdtbc.html

Ruby: Dir.children("dir")
来源：http://dali.guannengcc.top/Article/details/gtvnezwxjl.html

C#:   Directory.GetFiles("dir")
来源：http://dali.fengsongda.top/Article/details/gteebgzslv.html

[F09] 获取文件大小
来源：http://dali.guowangkeji.top/Article/details/gtadqbrxly.html

Py:   os.path.getsize("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtxaiocmfi.html

PHP:  filesize("a.txt");
来源：http://dali.yuanzhike.top/Article/details/gtvcildsou.html

JS:   fs.statSync("a.txt").size
来源：http://dali.guowangkeji.top/Article/details/gtakjaejhm.html

TS:   fs.statSync("a.txt").size
来源：http://dali.xinyue.icu/Article/details/gtbfqobecy.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gtkurmelfo.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.ppjwa.cn/Article/details/gteqakguiu.html

Ruby: File.size("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtmikqnvrf.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.vqdsnc.cn/Article/details/gthplfdnjr.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jqgfzy.top/Article/details/gtadfznulb.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yj202588.top/Article/details/gtzmzcvtix.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jianghu66.top/Article/details/gtirhesogo.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtfjviruzs.html

TS:   path.extname("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtjjsbulou.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jiagoushi.top/Article/details/gtmflhoyaa.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtefzfdycm.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtrrnkdspb.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtjuqtsrqz.html

[F11] 复制与移动文件
来源：http://dali.bjfxy.top/Article/details/gtxywzadnr.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.sufxvd.cn/Article/details/gtbmpfuutg.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.birdmap.top/Article/details/gtdqvnkyhi.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.birdmap.top/Article/details/gtoptrjgtj.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cashguo.top/Article/details/gtefmieefu.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.xuanzx.com/Article/details/gtirrnmujd.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.hywenlv.cn/Article/details/gtpwxjtcrj.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zycfv.cn/Article/details/gtjtrfjewy.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.fzhhl.top/Article/details/gtsragozpx.html

[F12] CSV 读写
来源：http://dali.zhaomingkeji.xyz/Article/details/gtveyuxvqp.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.meibo888.top/Article/details/gtbbnyehnu.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jyoumei.cn/Article/details/gtjapaupyl.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hnxiangtu.top/Article/details/gtdcqngony.html

TS:   // 同上
来源：http://dali.xinyue.icu/Article/details/gtzykfdhdt.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfvbbqqyi.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxgrnfbbb.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.dashuyun.cn/Article/details/gtbmavzeec.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hysaishi.cn/Article/details/gtqwrliqap.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtquyccnfh.html

G. 面向对象
来源：http://dali.yj20258.top/Article/details/gtthovkpfo.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtrvqnyupv.html

[G01] 定义类
来源：http://dali.cdnleiting.top/Article/details/gtahfohwrf.html

Py:   class User: pass
来源：http://dali.ivvv.top/Article/details/gtqwqvdhem.html

PHP:  class User {}
来源：http://dali.hywenlv.cn/Article/details/gtddjkuohm.html

JS:   class User {}
来源：http://dali.andypj.xyz/Article/details/gtzxcfocaq.html

TS:   class User { name: string = ""; }
来源：http://dali.mhx1999.top/Article/details/gtoxntuxxj.html

Java: class User {}
来源：http://dali.andypj.xyz/Article/details/gtvqorggdq.html

Go:   type User struct { Name string }
来源：http://dali.sweek.top/Article/details/gtqfhkbusu.html

Ruby: class User; end
来源：http://dali.zycfv.cn/Article/details/gtqgsngzxt.html

C#:   class User {}
来源：http://dali.zhengqikj.top/Article/details/gtktjzdegu.html

[G02] 构造函数
来源：http://dali.iojbl.cn/Article/details/gtuouziyar.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.daxiang520.top/Article/details/gtggvucvfz.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.birdmap.top/Article/details/gtdxucgpzo.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.wangdashe.top/Article/details/gtxzjgggwf.html

TS:   constructor(public name: string) {}
来源：http://dali.cheryme.top/Article/details/gttwbcroeb.html

Java: User(String name) { this.name = name; }
来源：http://dali.cqqwz.cn/Article/details/gtibciroem.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtavxmsvjh.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.cdnleiting.top/Article/details/gtyfszzkae.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhixingplan.top/Article/details/gthtuektbg.html

[G03] 实例属性
来源：http://dali.iojbl.cn/Article/details/gtkixsszgn.html

Py:   self.name = "x"
来源：http://dali.nwbrower.top/Article/details/gtvnroactd.html

PHP:  public string $name = "x";
来源：http://dali.hnxiangtu.top/Article/details/gtevypmsea.html

JS:   this.name = "x";
来源：http://dali.yj20258.top/Article/details/gtdriceirt.html

TS:   name: string = "x";
来源：http://dali.shzxlz.cn/Article/details/gtsrfykyae.html

Java: private String name;
来源：http://dali.dianchejie.cn/Article/details/gthxspcpcr.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jiagoushi.top/Article/details/gtbtjjbjzr.html

Ruby: @name = "x"
来源：http://dali.sweek.top/Article/details/gtyzfrzilb.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.sufxvd.cn/Article/details/gtveozrxxu.html

[G04] 定义方法
来源：http://dali.aizwys.cn/Article/details/gthmugbwlz.html

Py:   def greet(self): return self.name
来源：http://dali.9152youxi.cn/Article/details/gtxphwhjui.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.9152youxi.cn/Article/details/gtpepytiub.html

JS:   greet() { return this.name; }
来源：http://dali.ybcxt.top/Article/details/gtgawmzyoo.html

TS:   greet(): string { return this.name; }
来源：http://dali.guannengcc.top/Article/details/gtxlokizet.html

Java: String greet() { return name; }
来源：http://dali.zdqjudy.top/Article/details/gtzwkkiwmm.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.ivvv.top/Article/details/gtijejzsif.html

Ruby: def greet; @name; end
来源：http://dali.xylfe.cn/Article/details/gtlescjomn.html

C#:   public string Greet() => Name;
来源：http://dali.havefunace.top/Article/details/gtzdeawkqq.html

[G05] 继承
来源：http://dali.guowangkeji.top/Article/details/gtyemjppfl.html

Py:   class Admin(User): pass
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdpqvehll.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gtuoewzyap.html

JS:   class Admin extends User {}
来源：http://dali.yangfankeji.com/Article/details/gtuugzkchy.html

TS:   class Admin extends User {}
来源：http://dali.9152youxi.cn/Article/details/gtlqomcaus.html

Java: class Admin extends User {}
来源：http://dali.hfpthk.cn/Article/details/gtzuyhcqab.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yuanzhike.top/Article/details/gtftitlcmm.html

Ruby: class Admin < User; end
来源：http://dali.ppjwa.cn/Article/details/gtydusezhj.html

C#:   class Admin : User {}
来源：http://dali.dianchejie.cn/Article/details/gtgddtqmqb.html

[G06] 重写方法
来源：http://dali.nwbrower.top/Article/details/gtledasdhi.html

Py:   def greet(self): return "admin"
来源：http://dali.jqgfzy.top/Article/details/gtesrvivgq.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.9152youxi.cn/Article/details/gtenxqlles.html

JS:   greet() { return "admin"; }
来源：http://dali.tanke756.top/Article/details/gtbdqbmbtr.html

TS:   greet(): string { return "admin"; }
来源：http://dali.andypj.xyz/Article/details/gtdudlcsgt.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.fengsongda.top/Article/details/gttyvzyqcn.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yj20258.top/Article/details/gtponohswb.html

Ruby: def greet; "admin"; end
来源：http://dali.gogol.net.cn/Article/details/gtevcoppbv.html

C#:   public override string Greet() => "admin";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtixhdsjat.html

[G07] 调用父类方法
来源：http://dali.cqqwz.cn/Article/details/gtrjrfwqfy.html

Py:   super().greet()
来源：http://dali.ivvv.top/Article/details/gtbxtazcge.html

PHP:  parent::greet();
来源：http://dali.hnqzz.top/Article/details/gtuhvqvohj.html

JS:   super.greet();
来源：http://dali.yj202588.top/Article/details/gtlnpldtfs.html

TS:   super.greet();
来源：http://dali.gaohongyu789.top/Article/details/gtyzhgjcos.html

Java: super.greet();
来源：http://dali.sxryk.cn/Article/details/gtgpkraaif.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yj20258.top/Article/details/gthxzwprfq.html

Ruby: super
来源：http://dali.jinqigfzy.top/Article/details/gtvxledgpd.html

C#:   base.Greet();
来源：http://dali.sweek.top/Article/details/gtbshjoexo.html

[G08] 静态方法与属性
来源：http://dali.hnqzz.top/Article/details/gtbjjgajku.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yonumen.top/Article/details/gtmgkeggvo.html

PHP:  public static function f() {}
来源：http://dali.gogol.net.cn/Article/details/gtxqsfqmim.html

JS:   static f() {}
来源：http://dali.gotoacloud.top/Article/details/gthwqupmlp.html

TS:   static f(): void {}
来源：http://dali.havefunace.top/Article/details/gtgmwcbvgu.html

Java: static void f() {}
来源：http://dali.nwbrower.top/Article/details/gtdjwloekt.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.316326.xyz/Article/details/gtjjyrpuud.html

Ruby: def self.f; end
来源：http://dali.tianlin.xyz/Article/details/gtyivmtbqi.html

C#:   public static void F() {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtplodhkvw.html

[G09] 接口 / 抽象类
来源：http://dali.0kj1m.cn/Article/details/gtsmqerssf.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.fengsongda.top/Article/details/gtrysusyly.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.hongshengwenyu.top/Article/details/gtcxgdaiyd.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hysaishi.cn/Article/details/gtgcskkwxy.html

TS:   interface Shape { area(): number; }
来源：http://dali.hammf.cn/Article/details/gtrzzpzgij.html

Java: interface Shape { double area(); }
来源：http://dali.tianlin.xyz/Article/details/gtuypaqqbi.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.wangshuangyany.cn/Article/details/gtmqjqntpz.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.iojbl.cn/Article/details/gtmabzhuox.html

C#:   interface IShape { double Area(); }
来源：http://dali.hnxiangtu.top/Article/details/gtuwgtqeax.html

[G10] 访问控制
来源：http://dali.chenlongwang.top/Article/details/gtofrsgazl.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.sxryk.cn/Article/details/gtbwbyfqbn.html

PHP:  public / protected / private
来源：http://dali.gogol.net.cn/Article/details/gtgucfqkzv.html

JS:   #private 字段；其余公开
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaaobbamx.html

TS:   public / protected / private
来源：http://dali.chenlongwang.top/Article/details/gtwotpmhjj.html

Java: public / protected / private / 默认包级
来源：http://dali.jiagoushi.top/Article/details/gthmnrejhb.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jinqigufen.top/Article/details/gtmehncboy.html

Ruby: public / protected / private
来源：http://dali.birdmap.top/Article/details/gtmdtbgaiw.html

C#:   public / protected / private / internal
来源：http://dali.dianchejie.cn/Article/details/gtnwdudzdk.html

[G11] getter / setter
来源：http://dali.yuanzhike.top/Article/details/gtrsnlsuap.html

Py:   @property 与 @x.setter
来源：http://dali.redwolf501.top/Article/details/gttdvkhqui.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.gzhubu.top/Article/details/gtxvjqryfv.html

JS:   get name() { return this._name; }
来源：http://dali.wangdashe.top/Article/details/gtlirpvott.html

TS:   get name(): string { return this._name; }
来源：http://dali.chenzaomai.com/Article/details/gtzxygekqk.html

Java: public String getName() { return name; }
来源：http://dali.nanxinkj.top/Article/details/gtudfpniyi.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jinqigufen.top/Article/details/gtjjnglehl.html

Ruby: attr_accessor :name
来源：http://dali.cqqwz.cn/Article/details/gtdqhmlljy.html

C#:   public string Name { get; set; }
来源：http://dali.xylfe.cn/Article/details/gtkquavyxv.html

[G12] 对象转字符串
来源：http://dali.yanxiufei.cn/Article/details/gtvmtrbcsc.html

Py:   def __str__(self): return self.name
来源：http://dali.xuanzx.com/Article/details/gtuialnnyz.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.cdnleiting.top/Article/details/gtgfzonkyw.html

JS:   toString() { return this.name; }
来源：http://dali.ybcxt.top/Article/details/gtvsdlhtbs.html

TS:   toString(): string { return this.name; }
来源：http://dali.yangfankeji.com/Article/details/gtvltblbwa.html

Java: @Override public String toString() { return name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gthmdbingl.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yonumen.top/Article/details/gtwtejicti.html

Ruby: def to_s; @name; end
来源：http://dali.ydzc1.top/Article/details/gtgvofuapf.html

C#:   public override string ToString() => Name;
来源：http://dali.smart0.xyz/Article/details/gtkdcnsatj.html

[G13] 判断对象类型
来源：http://dali.yvedp.cn/Article/details/gtulsuqfvf.html

Py:   isinstance(u, User)
来源：http://dali.xylfe.cn/Article/details/gtmdtaivfy.html

PHP:  $u instanceof User
来源：http://dali.yuanzhike.top/Article/details/gtnjfkslno.html

JS:   u instanceof User
来源：http://dali.yuanzhike.top/Article/details/gtgpplzbse.html

TS:   u instanceof User
来源：http://dali.bjfxy.top/Article/details/gtakoeznvo.html

Java: u instanceof User
来源：http://dali.redwolf501.top/Article/details/gtveeifkfg.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hnxiangtu.top/Article/details/gtpkodvlfe.html

Ruby: u.is_a?(User)
来源：http://dali.wangshuangyany.cn/Article/details/gtfwsdiegv.html

C#:   u is User
来源：http://dali.cdnleiting.top/Article/details/gtyejrtdlo.html

[G14] 数据类 / record
来源：http://dali.sufxvd.cn/Article/details/gtznrmvfpn.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.gogol.net.cn/Article/details/gtkkygxwfx.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jianghu66.top/Article/details/gtvzlcmknz.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yangfankeji.com/Article/details/gtcvvjbipr.html

TS:   type User = { name: string; age: number };
来源：http://dali.mhx1999.top/Article/details/gtfjqvefee.html

Java: record User(String name, int age) {}
来源：http://dali.hysaishi.cn/Article/details/gtldnvdfdm.html

Go:   type User struct { Name string; Age int }
来源：http://dali.svipenyu.cn/Article/details/gtkdvyvlmc.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hfpthk.cn/Article/details/gtivtjsckk.html

C#:   record User(string Name, int Age);
来源：http://dali.316326.xyz/Article/details/gtujpaqhbt.html

[G15] 枚举
来源：http://dali.nwbrower.top/Article/details/gtdhljyjof.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.cdnleiting.top/Article/details/gttctggvtk.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.sxryk.cn/Article/details/gtibpttmql.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.snrcjt.cn/Article/details/gtdcucaeuf.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cheryme.top/Article/details/gtjnpmahzs.html

Java: enum Color { RED, GREEN }
来源：http://dali.daria6918.cn/Article/details/gtwjmpdnot.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.xuetiantiany.cn/Article/details/gtfxdialri.html

Ruby: Color = %i[red green].freeze
来源：http://dali.snrcjt.cn/Article/details/gtthxitgnv.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ydzc1.top/Article/details/gtreazcffv.html

[G16] 对象转数组 / 字典
来源：http://dali.daxiang520.top/Article/details/gthocbiaji.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhengqikj.top/Article/details/gtnsljdewn.html

PHP:  get_object_vars($obj);
来源：http://dali.xinyue.icu/Article/details/gtdkrfuvwj.html

JS:   Object.entries(obj)
来源：http://dali.svipenyu.cn/Article/details/gtqrmozwmk.html

TS:   Object.entries(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtnhbdmjtm.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yangfankeji.com/Article/details/gtpbeyljfb.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.smart0.xyz/Article/details/gtsyragujf.html

Ruby: obj.instance_variables
来源：http://dali.guowangkeji.top/Article/details/gtltnxjkvj.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.chenjidiqi.icu/Article/details/gtdfmdlpdx.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtpbetnbzv.html

H. 异常与错误处理
来源：http://dali.hammf.cn/Article/details/gtsvphyynv.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtakgbkach.html

[H01] try / catch 基础
来源：http://dali.xuanzx.com/Article/details/gtqacqfrix.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.pycfn.com/Article/details/gtacswagpw.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.haohaochexian.top/Article/details/gtqmofrebl.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jianghu66.top/Article/details/gtenvdnydm.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.sysykeji.top/Article/details/gtgxqwrejz.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.meibo888.top/Article/details/gtneuzexte.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yangfankeji.com/Article/details/gtbqibrnww.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.cqqwz.cn/Article/details/gtbnpanftv.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.cdnleiting.top/Article/details/gtbxniqpwa.html

[H02] finally / ensure 收尾
来源：http://dali.feifeiyinyue.top/Article/details/gtfllnxcla.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.fengsongda.top/Article/details/gtaiscoamb.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.redwolf501.top/Article/details/gtxqspcfeb.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ppjwa.cn/Article/details/gtktvfvcwr.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.wangdashe.top/Article/details/gtgqkgtshp.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.vqdsnc.cn/Article/details/gtytfegyur.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhixingplan.top/Article/details/gtavryxbjh.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.hnxiangtu.top/Article/details/gtyownghqb.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.ivvv.top/Article/details/gtfvlezlsc.html

[H03] 主动抛出异常
来源：http://dali.dashuyun.cn/Article/details/gtjhlktpnf.html

Py:   raise ValueError("错误信息")
来源：http://dali.chenlongwang.top/Article/details/gtsdiqhhqd.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yj20258.top/Article/details/gtocfxlawp.html

JS:   throw new Error("错误信息");
来源：http://dali.cdnleiting.top/Article/details/gtkafqlnyk.html

TS:   throw new Error("错误信息");
来源：http://dali.shanyushiyangtech.top/Article/details/gtvaqfrbyb.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.chenjidiqi.icu/Article/details/gtfwnqtouj.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.dashuyun.cn/Article/details/gteoqimsqx.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.smart0.xyz/Article/details/gtasrusgwd.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yongpay.top/Article/details/gtfsggsbyo.html

[H04] 自定义异常类型
来源：http://dali.cheryme.top/Article/details/gtjnwhdfbx.html

Py:   class MyError(Exception): pass
来源：http://dali.andypj.xyz/Article/details/gthalhdieg.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.birdmap.top/Article/details/gtjbszyycr.html

JS:   class MyError extends Error {}
来源：http://dali.fzhhl.top/Article/details/gtebpvbzeu.html

TS:   class MyError extends Error {}
来源：http://dali.jinghuilouyu.cn/Article/details/gttqlgjepo.html

Java: class MyException extends RuntimeException {}
来源：http://dali.wangshuangyany.cn/Article/details/gtqxwdcgfm.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zycfv.cn/Article/details/gtqbkkefba.html

Ruby: class MyError < StandardError; end
来源：http://dali.hfpthk.cn/Article/details/gtpnkxmmeu.html

C#:   class MyException : Exception {}
来源：http://dali.cashguo.top/Article/details/gtmvahtcnn.html

[H05] 捕获特定类型
来源：http://dali.zhengqikj.top/Article/details/gtyidvjlxm.html

Py:   except ValueError as e:
来源：http://dali.sxryk.cn/Article/details/gtnteafkzl.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.nanxinkj.top/Article/details/gtnhrlcirr.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnewwvjxv.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.dashuyun.cn/Article/details/gttcwvczae.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.chenlongwang.top/Article/details/gtoiuohldi.html


<!-- 参考信息 -->