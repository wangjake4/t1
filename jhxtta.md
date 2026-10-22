代发 wailian999

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jiagoushi.top/Article/details/gt2qopzhsfq.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jinqigfzy.top/Article/details/gt2lrifmnpg.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.chenlongwang.top/Article/details/gt2cknsrxqb.html

Ruby: File.read("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2faamsvzx.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.cucudq.cn/Article/details/gt2mpmisdod.html

[F02] 逐行读取文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dkblrijg.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.haohaochexian.top/Article/details/gt2ukcfahvl.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.sweek.top/Article/details/gt2vxmsbtxt.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zdqjudy.top/Article/details/gt2kpoohcls.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cucudq.cn/Article/details/gt2xpbzrmgz.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jqgufenzy.top/Article/details/gt2njrqulba.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yj202588.top/Article/details/gt2micidlhn.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2suttgkvc.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.pycfn.com/Article/details/gt2vndkdezq.html

[F03] 写入文件（覆盖）
来源：http://dali.havefunace.top/Article/details/gt2wcrwygsn.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.tianlin.xyz/Article/details/gt2ihvpifhl.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.ydzc1.top/Article/details/gt2xosfsvlj.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.wangshuangyany.cn/Article/details/gt2edikpfas.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yvedp.cn/Article/details/gt2wdywfolo.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yonumen.top/Article/details/gt2tfwuuciz.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jinqigufen.top/Article/details/gt2dmeigvcj.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.mhx1999.top/Article/details/gt2yowakbih.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.hnqzz.top/Article/details/gt2qqectxdd.html

[F04] 追加写入文件
来源：http://dali.havefunace.top/Article/details/gt2ccspeflm.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.ppjwa.cn/Article/details/gt2ocscjrbc.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.meibo888.top/Article/details/gt2etobwixa.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zycfv.cn/Article/details/gt2ywlpmdux.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hfpthk.cn/Article/details/gt2jcpazvdi.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.shangyingyoupin.top/Article/details/gt2mfimqayr.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.redwolf501.top/Article/details/gt2yfgsesfs.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.c1oappe.top/Article/details/gt2nkgedjzb.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jyoumei.cn/Article/details/gt2reoemxul.html

[F05] 判断文件或目录是否存在
来源：http://dali.wangshuangyany.cn/Article/details/gt2squpvxvt.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.xuanzx.com/Article/details/gt2luiiynbz.html

PHP:  file_exists("a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gt2mipxkswd.html

JS:   fs.existsSync("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2bcgpikum.html

TS:   fs.existsSync("a.txt")
来源：http://dali.cheryme.top/Article/details/gt2mdcmocbv.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jyoumei.cn/Article/details/gt2qvmfnjft.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yueranfly.top/Article/details/gt2zkuxiuqw.html

Ruby: File.exist?("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gt2xrxebmuq.html

C#:   File.Exists("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2dqngxtwp.html

[F06] 删除文件
来源：http://dali.jianghu66.top/Article/details/gt2nuoefuoz.html

Py:   os.remove("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ipgueoqo.html

PHP:  unlink("a.txt");
来源：http://dali.jianghu66.top/Article/details/gt2zbrcpqph.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zycfv.cn/Article/details/gt2whewnrbc.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yongpay.top/Article/details/gt2vroawldt.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ywmaaspq.html

Go:   os.Remove("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gt2ybydznlp.html

Ruby: File.delete("a.txt")
来源：http://dali.xuanzx.com/Article/details/gt2fmnmsrdp.html

C#:   File.Delete("a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gt2gmbxredr.html

[F07] 创建目录（含多级）
来源：http://dali.havefunace.top/Article/details/gt2jabqbfsu.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.316326.xyz/Article/details/gt2sirkcspb.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhengqikj.top/Article/details/gt2exsptzwd.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ydzc1.top/Article/details/gt2xjvtenpn.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.iojbl.cn/Article/details/gt2hmkicygy.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhixingplan.top/Article/details/gt2caawutrd.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zdqjudy.top/Article/details/gt2rqvbtzny.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.sxryk.cn/Article/details/gt2ndszeskl.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pooaxrfk.html

[F08] 遍历目录
来源：http://dali.cucudq.cn/Article/details/gt2vrxgveoc.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.fzhhl.top/Article/details/gt2mzpykdot.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.xylfe.cn/Article/details/gt2bvqvyjrh.html

JS:   fs.readdirSync("dir")
来源：http://dali.cucudq.cn/Article/details/gt2ptsiaokh.html

TS:   fs.readdirSync("dir")
来源：http://dali.jianghu66.top/Article/details/gt2psqkasrl.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yueranfly.top/Article/details/gt2spvnoghj.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.vqdsnc.cn/Article/details/gt2elpzedsr.html

Ruby: Dir.children("dir")
来源：http://dali.yueranfly.top/Article/details/gt2kcpjvzcy.html

C#:   Directory.GetFiles("dir")
来源：http://dali.tanke756.top/Article/details/gt2makpddew.html

[F09] 获取文件大小
来源：http://dali.zdqjudy.top/Article/details/gt2zfhbyxah.html

Py:   os.path.getsize("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gt2fvwapymh.html

PHP:  filesize("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gt2xrnouzek.html

JS:   fs.statSync("a.txt").size
来源：http://dali.ppjwa.cn/Article/details/gt2osxptucl.html

TS:   fs.statSync("a.txt").size
来源：http://dali.smart0.xyz/Article/details/gt2remeaeek.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.aizwys.cn/Article/details/gt2skqdwkob.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.sweek.top/Article/details/gt2muguupcl.html

Ruby: File.size("a.txt")
来源：http://dali.yj202588.top/Article/details/gt2drwcvyas.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.kuanghao11.cn/Article/details/gt2wrklnvbm.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.sxryk.cn/Article/details/gt2xyvmxmoo.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2crkbwivo.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.cashguo.top/Article/details/gt2nhokhhfn.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gjsdaoat.html

TS:   path.extname("a.txt")
来源：http://dali.c1oappe.top/Article/details/gt2uhfbqvkx.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.snrcjt.cn/Article/details/gt2njnrtamj.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2ukkbablh.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gt2zwebnqlw.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.ivvv.top/Article/details/gt2hbmtpkwn.html

[F11] 复制与移动文件
来源：http://dali.jqgufenzy.top/Article/details/gt2dsqujoqw.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.mhx1999.top/Article/details/gt2gplvotjn.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.fengsongda.top/Article/details/gt2ilwoqwsy.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cucudq.cn/Article/details/gt2xygdsaeo.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2tegdnzmi.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jlsjyb.cn/Article/details/gt2nnmfnhra.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.hfpthk.cn/Article/details/gt2savwqliy.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2xlqbumip.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yangfankeji.com/Article/details/gt2itriphdy.html

[F12] CSV 读写
来源：http://dali.yangfankeji.com/Article/details/gt2eqvdsdgo.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yvedp.cn/Article/details/gt2szadvfjb.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhijiandao.cn/Article/details/gt2vyeawaee.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yuanzhike.top/Article/details/gt2kcvooqpi.html

TS:   // 同上
来源：http://dali.shangyingyoupin.top/Article/details/gt2zgebscsj.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cwqijgun.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.chenlongwang.top/Article/details/gt2usqbcxfl.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.meibo888.top/Article/details/gt2qtmumutx.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.mhx1999.top/Article/details/gt2needqvaa.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2tdehuhzm.html

G. 面向对象
来源：http://dali.hnxiangtu.top/Article/details/gt2ibegsbug.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2wujbuvty.html

[G01] 定义类
来源：http://dali.hammf.cn/Article/details/gt2uhpucrqi.html

Py:   class User: pass
来源：http://dali.hysaishi.cn/Article/details/gt2lsbwjmlk.html

PHP:  class User {}
来源：http://dali.jiagoushi.top/Article/details/gt2ygxehdfn.html

JS:   class User {}
来源：http://dali.dianchejie.cn/Article/details/gt2blngtwir.html

TS:   class User { name: string = ""; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wyrsecxh.html

Java: class User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xnvpcdpl.html

Go:   type User struct { Name string }
来源：http://dali.chenjidiqi.icu/Article/details/gt2gowgsgox.html

Ruby: class User; end
来源：http://dali.meibo888.top/Article/details/gt2ywatkayn.html

C#:   class User {}
来源：http://dali.hfpthk.cn/Article/details/gt2iamlnzdt.html

[G02] 构造函数
来源：http://dali.jianghu66.top/Article/details/gt2mthxmbjf.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.shzxlz.cn/Article/details/gt2tofcqjeg.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.sweek.top/Article/details/gt2wfxnhzfg.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.hysaishi.cn/Article/details/gt2dzyxmoeo.html

TS:   constructor(public name: string) {}
来源：http://dali.nanxinkj.top/Article/details/gt2hssexybm.html

Java: User(String name) { this.name = name; }
来源：http://dali.xylfe.cn/Article/details/gt2prwuglii.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hnxiangtu.top/Article/details/gt2dwmovfwm.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yvedp.cn/Article/details/gt2usterdly.html

C#:   public User(string name) { Name = name; }
来源：http://dali.shzxlz.cn/Article/details/gt2abqilaib.html

[G03] 实例属性
来源：http://dali.jianghu66.top/Article/details/gt2lkgiqegx.html

Py:   self.name = "x"
来源：http://dali.dashuyun.cn/Article/details/gt2zofqybbh.html

PHP:  public string $name = "x";
来源：http://dali.redwolf501.top/Article/details/gt2cyabktbd.html

JS:   this.name = "x";
来源：http://dali.xziqi.cn/Article/details/gt2gheppdxb.html

TS:   name: string = "x";
来源：http://dali.gogol.net.cn/Article/details/gt2zijtxbpl.html

Java: private String name;
来源：http://dali.daria6918.cn/Article/details/gt2fxgwmewe.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wbgnhire.html

Ruby: @name = "x"
来源：http://dali.meibo888.top/Article/details/gt2hrvxfijm.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.pengpengdd.cyou/Article/details/gt2nrfkuash.html

[G04] 定义方法
来源：http://dali.yueranfly.top/Article/details/gt2xvumapuv.html

Py:   def greet(self): return self.name
来源：http://dali.c1oappe.top/Article/details/gt2gdmchewn.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2dsencgsy.html

JS:   greet() { return this.name; }
来源：http://dali.zycfv.cn/Article/details/gt2civflzzz.html

TS:   greet(): string { return this.name; }
来源：http://dali.jianghu66.top/Article/details/gt2sdwlcsru.html

Java: String greet() { return name; }
来源：http://dali.ehwqpu.com/Article/details/gt2ydmvyiox.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jinqigufen.top/Article/details/gt2xqyehcgk.html

Ruby: def greet; @name; end
来源：http://dali.gotoacloud.top/Article/details/gt2jdwwfbdf.html

C#:   public string Greet() => Name;
来源：http://dali.fengsongda.top/Article/details/gt2semntagh.html

[G05] 继承
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bdakbtiv.html

Py:   class Admin(User): pass
来源：http://dali.jinqigufen.top/Article/details/gt2owzcccjo.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tpqgnmsd.html

JS:   class Admin extends User {}
来源：http://dali.smart0.xyz/Article/details/gt2yjlgargp.html

TS:   class Admin extends User {}
来源：http://dali.gotoacloud.top/Article/details/gt2rhniines.html

Java: class Admin extends User {}
来源：http://dali.haohaochexian.top/Article/details/gt2amjglcsu.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yj20258888.top/Article/details/gt2duhnqpqz.html

Ruby: class Admin < User; end
来源：http://dali.pycfn.com/Article/details/gt2euwztshc.html

C#:   class Admin : User {}
来源：http://dali.chenlongwang.top/Article/details/gt2ibvtxfcb.html

[G06] 重写方法
来源：http://dali.nanxuanxn.top/Article/details/gt2eofcdftr.html

Py:   def greet(self): return "admin"
来源：http://dali.yuanzhike.top/Article/details/gt2nixkjnqr.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.chenlongwang.top/Article/details/gt2qjkbbtce.html

JS:   greet() { return "admin"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bosfkfxu.html

TS:   greet(): string { return "admin"; }
来源：http://dali.pycfn.com/Article/details/gt2qchyctkg.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.meibo888.top/Article/details/gt2clldypeb.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jinqigfzy.top/Article/details/gt2sdskrdld.html

Ruby: def greet; "admin"; end
来源：http://dali.daxiang520.top/Article/details/gt2nvylabgy.html

C#:   public override string Greet() => "admin";
来源：http://dali.guowangkeji.top/Article/details/gt2dqqrbqhz.html

[G07] 调用父类方法
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cewvjnzk.html

Py:   super().greet()
来源：http://dali.haohaochexian.top/Article/details/gt2bgosprxs.html

PHP:  parent::greet();
来源：http://dali.yj202588.top/Article/details/gt2iubeedcd.html

JS:   super.greet();
来源：http://dali.gzhubu.top/Article/details/gt2zgrckhzx.html

TS:   super.greet();
来源：http://dali.shangyingyoupin.top/Article/details/gt2iwzxzfta.html

Java: super.greet();
来源：http://dali.yonumen.top/Article/details/gt2iduldzcu.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.cucudq.cn/Article/details/gt2imgubkup.html

Ruby: super
来源：http://dali.guannengcc.top/Article/details/gt2nxfydwib.html

C#:   base.Greet();
来源：http://dali.vqdsnc.cn/Article/details/gt2rmnmtnts.html

[G08] 静态方法与属性
来源：http://dali.yongpay.top/Article/details/gt2crcdktlm.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jqgfzy.top/Article/details/gt2ocrhcktd.html

PHP:  public static function f() {}
来源：http://dali.dianchejie.cn/Article/details/gt2pnqcdjqx.html

JS:   static f() {}
来源：http://dali.havefunace.top/Article/details/gt2vcjgwzyw.html

TS:   static f(): void {}
来源：http://dali.zhongyouzk.top/Article/details/gt2rnxefbhj.html

Java: static void f() {}
来源：http://dali.dianchejie.cn/Article/details/gt2ctkfoiql.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.andypj.xyz/Article/details/gt2ejubyomc.html

Ruby: def self.f; end
来源：http://dali.cucudq.cn/Article/details/gt2ifztiynx.html

C#:   public static void F() {}
来源：http://dali.yuanzhike.top/Article/details/gt2oqhwplpr.html

[G09] 接口 / 抽象类
来源：http://dali.sweek.top/Article/details/gt2qcchsqdk.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yonumen.top/Article/details/gt2ugezkqzh.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.pycfn.com/Article/details/gt2labcizjo.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jinqigufen.top/Article/details/gt2cuuuaktq.html

TS:   interface Shape { area(): number; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wzzmfvbv.html

Java: interface Shape { double area(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vjogiiic.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yangfankeji.com/Article/details/gt2zrvxtmhs.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xuanzx.com/Article/details/gt2nngwiuke.html

C#:   interface IShape { double Area(); }
来源：http://dali.xuanzx.com/Article/details/gt2agosspku.html

[G10] 访问控制
来源：http://dali.tianlin.xyz/Article/details/gt2yqnolljw.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mshnsecn.html

PHP:  public / protected / private
来源：http://dali.yuanzhike.top/Article/details/gt2dpbbtbts.html

JS:   #private 字段；其余公开
来源：http://dali.tian-w.cn/Article/details/gt2almoqerv.html

TS:   public / protected / private
来源：http://dali.xuanzx.com/Article/details/gt2homusini.html

Java: public / protected / private / 默认包级
来源：http://dali.zhixingplan.top/Article/details/gt2lntvpwxp.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2wnibdmoa.html

Ruby: public / protected / private
来源：http://dali.316326.xyz/Article/details/gt2uwoxgxqu.html

C#:   public / protected / private / internal
来源：http://dali.sweek.top/Article/details/gt2shysmkmg.html

[G11] getter / setter
来源：http://dali.dashuyun.cn/Article/details/gt2jtiacetl.html

Py:   @property 与 @x.setter
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ogdntewn.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.chenlongwang.top/Article/details/gt2gpnofzmn.html

JS:   get name() { return this._name; }
来源：http://dali.sufxvd.cn/Article/details/gt2wxkuwrqv.html

TS:   get name(): string { return this._name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yqojigld.html

Java: public String getName() { return name; }
来源：http://dali.nanxinkj.top/Article/details/gt2gxsehocu.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.ybcxt.top/Article/details/gt2lstmehyz.html

Ruby: attr_accessor :name
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pupiyyte.html

C#:   public string Name { get; set; }
来源：http://dali.andypj.xyz/Article/details/gt2chnngcpq.html

[G12] 对象转字符串
来源：http://dali.chenjidiqi.icu/Article/details/gt2ogupcvhu.html

Py:   def __str__(self): return self.name
来源：http://dali.nwbrower.top/Article/details/gt2oyummivh.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lqibezmy.html

JS:   toString() { return this.name; }
来源：http://dali.yangfankeji.com/Article/details/gt2xubsktsz.html

TS:   toString(): string { return this.name; }
来源：http://dali.xuanzx.com/Article/details/gt2mnvujmqw.html

Java: @Override public String toString() { return name; }
来源：http://dali.fengsongda.top/Article/details/gt2ionphjfd.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.chenlongwang.top/Article/details/gt2jdopqmql.html

Ruby: def to_s; @name; end
来源：http://dali.fzhhl.top/Article/details/gt2gaxezhmv.html

C#:   public override string ToString() => Name;
来源：http://dali.jqgufenzy.top/Article/details/gt2jubtyrvy.html

[G13] 判断对象类型
来源：http://dali.gaohongyu789.top/Article/details/gt2rpgkfqpv.html

Py:   isinstance(u, User)
来源：http://dali.havefunace.top/Article/details/gt2mxzzuspf.html

PHP:  $u instanceof User
来源：http://dali.jyoumei.cn/Article/details/gt2akfuzbzc.html

JS:   u instanceof User
来源：http://dali.cdnleiting.top/Article/details/gt2wfscmpvy.html

TS:   u instanceof User
来源：http://dali.ehwqpu.com/Article/details/gt2zdujrfxi.html

Java: u instanceof User
来源：http://dali.xuetiantiany.cn/Article/details/gt2rwvlagpu.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.daria6918.cn/Article/details/gt2mdaahrmz.html

Ruby: u.is_a?(User)
来源：http://dali.ybcxt.top/Article/details/gt2lzcixwzk.html

C#:   u is User
来源：http://dali.c1oappe.top/Article/details/gt2qsbvkgkl.html

[G14] 数据类 / record
来源：http://dali.fzhhl.top/Article/details/gt2oxqwquwl.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yvedp.cn/Article/details/gt2drltiicf.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.cucudq.cn/Article/details/gt2shjohnyz.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hongshengwenyu.top/Article/details/gt2xzxcriio.html

TS:   type User = { name: string; age: number };
来源：http://dali.wangdashe.top/Article/details/gt2kbdhamfa.html

Java: record User(String name, int age) {}
来源：http://dali.hnxiangtu.top/Article/details/gt2vzhbvcsg.html

Go:   type User struct { Name string; Age int }
来源：http://dali.0kj1m.cn/Article/details/gt2phmqlmnm.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.andypj.xyz/Article/details/gt2cmdwoscp.html

C#:   record User(string Name, int Age);
来源：http://dali.zhongyouzk.top/Article/details/gt2jbhfuagx.html

[G15] 枚举
来源：http://dali.pycfn.com/Article/details/gt2jyffstgp.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.sysykeji.top/Article/details/gt2bdjfgbfz.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.sysykeji.top/Article/details/gt2sikoifzb.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.snrcjt.cn/Article/details/gt2wnmodfed.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hammf.cn/Article/details/gt2hpjyjxkk.html

Java: enum Color { RED, GREEN }
来源：http://dali.guannengcc.top/Article/details/gt2fhzisnjv.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.feifeiyinyue.top/Article/details/gt2jbqlwgsl.html

Ruby: Color = %i[red green].freeze
来源：http://dali.chenzaomai.com/Article/details/gt2zdqdilrn.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cheryme.top/Article/details/gt2etnomzvu.html

[G16] 对象转数组 / 字典
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gydjnfsc.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.ehwqpu.com/Article/details/gt2qxxtklhe.html

PHP:  get_object_vars($obj);
来源：http://dali.svipenyu.cn/Article/details/gt2saqxmtrd.html

JS:   Object.entries(obj)
来源：http://dali.zhoulong.xyz/Article/details/gt2smyaqnsr.html

TS:   Object.entries(obj)
来源：http://dali.wangdashe.top/Article/details/gt2icwouozp.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yongpay.top/Article/details/gt2ayitbztz.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.fzhhl.top/Article/details/gt2vbzqmmos.html

Ruby: obj.instance_variables
来源：http://dali.ydzc1.top/Article/details/gt2mxjonskg.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.xziqi.cn/Article/details/gt2aicjfzjb.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2yfhsdytt.html

H. 异常与错误处理
来源：http://dali.yueranfly.top/Article/details/gt2iolkeszm.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2stetgcbr.html

[H01] try / catch 基础
来源：http://dali.vqdsnc.cn/Article/details/gt2wxrhmluu.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yanxiufei.cn/Article/details/gt2keaotyaz.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yuxming.cn/Article/details/gt2yezoyclc.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.9152youxi.cn/Article/details/gt2erhqvnwg.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.ydzc1.top/Article/details/gt2zuhobpxx.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.quarkkingdee.top/Article/details/gt2ehguhmiu.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.chenzaomai.com/Article/details/gt2tntrgief.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.sweek.top/Article/details/gt2ynqngabk.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.cheryme.top/Article/details/gt2tgjnozkt.html

[H02] finally / ensure 收尾
来源：http://dali.yangfankeji.com/Article/details/gt2wyjvfrma.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hmitpmyu.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.9152youxi.cn/Article/details/gt2qpgzsmio.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jqgfzy.top/Article/details/gt2hyqqrokf.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.shzxlz.cn/Article/details/gt2ebzkarqx.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.hywenlv.cn/Article/details/gt2hyasuwru.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.cheryme.top/Article/details/gt2kbsbzmec.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jqgufenzy.top/Article/details/gt2yhytviri.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.xuanzx.com/Article/details/gt2qumvhmfy.html

[H03] 主动抛出异常
来源：http://dali.hysaishi.cn/Article/details/gt2khndckqj.html

Py:   raise ValueError("错误信息")
来源：http://dali.jqgfzy.top/Article/details/gt2vjagigib.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.xuanzx.com/Article/details/gt2faxlfcgy.html

JS:   throw new Error("错误信息");
来源：http://dali.vqdsnc.cn/Article/details/gt2adolfpfr.html

TS:   throw new Error("错误信息");
来源：http://dali.guannengcc.top/Article/details/gt2dfbaoxnn.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rdpcjftu.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.daria6918.cn/Article/details/gt2oujxnluf.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.cashguo.top/Article/details/gt2hwydexxx.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.guowangkeji.top/Article/details/gt2ifmsejkm.html

[H04] 自定义异常类型
来源：http://dali.gogol.net.cn/Article/details/gt2yomnatvp.html

Py:   class MyError(Exception): pass
来源：http://dali.quarkkingdee.top/Article/details/gt2flepzdwa.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2ljaclege.html

JS:   class MyError extends Error {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2npzzixny.html

TS:   class MyError extends Error {}
来源：http://dali.kuanghao11.cn/Article/details/gt2eerjjunx.html

Java: class MyException extends RuntimeException {}
来源：http://dali.iojbl.cn/Article/details/gt2aurbrgey.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhoulong.xyz/Article/details/gt2xyrxxpbz.html

Ruby: class MyError < StandardError; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wswmzgvf.html

C#:   class MyException : Exception {}
来源：http://dali.yanxiufei.cn/Article/details/gt2vywworwx.html

[H05] 捕获特定类型
来源：http://dali.xuanzx.com/Article/details/gt2mppqqvhs.html

Py:   except ValueError as e:
来源：http://dali.wangdashe.top/Article/details/gt2unnsqrvk.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.hfpthk.cn/Article/details/gt2fbwcysjh.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.nwbrower.top/Article/details/gt2zpxpcnrj.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.ehwqpu.com/Article/details/gt2gygefukh.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.wangdashe.top/Article/details/gt2xdqgsgla.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.pycfn.com/Article/details/gt2muzsjrns.html

Ruby: rescue ArgumentError => e
来源：http://dali.aibaodan.cn/Article/details/gt2rzpkgtlf.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.chenlongwang.top/Article/details/gt2refgbuuk.html

[H06] 可选值 / 空值安全访问
来源：http://dali.andypj.xyz/Article/details/gt2trdpvbpc.html


<!-- 参考信息 -->