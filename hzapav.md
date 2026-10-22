代发 wailian999

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yonumen.top/Article/details/gtwoloribj.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.cdnleiting.top/Article/details/gtstbffabq.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.hammf.cn/Article/details/gtagpososn.html

Ruby: File.read("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtnxkomvhz.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jiagoushi.top/Article/details/gtnkcqrywj.html

[F02] 逐行读取文件
来源：http://dali.yongpay.top/Article/details/gtvhzcjsbk.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.dashuyun.cn/Article/details/gtnfpguewp.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.316326.xyz/Article/details/gttjaimqjs.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jqgfzy.top/Article/details/gtiajuocrt.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gzhubu.top/Article/details/gtpbssdkir.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwltefbgm.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.shanyushiyangtech.top/Article/details/gtktrpadtz.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yj20258888.top/Article/details/gtvtqdtimy.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.cheryme.top/Article/details/gtmdxpaogm.html

[F03] 写入文件（覆盖）
来源：http://dali.yvedp.cn/Article/details/gtmhxhqglw.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.kuanghao11.cn/Article/details/gtikxcdsdn.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.fzhhl.top/Article/details/gtiwnfnqaw.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jqgfzy.top/Article/details/gtnkrhyjmx.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinghuilouyu.cn/Article/details/gtmuektelx.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.hysaishi.cn/Article/details/gtqjhonsjf.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.snrcjt.cn/Article/details/gtjtmusmnd.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.hfpthk.cn/Article/details/gtqlgqoqhe.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.316326.xyz/Article/details/gtomfvjrhh.html

[F04] 追加写入文件
来源：http://dali.fzhhl.top/Article/details/gtstcfdkyr.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.shuidangran.top/Article/details/gtrkalkzvi.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.sufxvd.cn/Article/details/gtvmofrwsd.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shanyushiyangtech.top/Article/details/gtokkgpcaz.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ivvv.top/Article/details/gtgtgtekae.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhixingplan.top/Article/details/gttasyrqtt.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.hysaishi.cn/Article/details/gtmlkmlbax.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.ivvv.top/Article/details/gtfqvnyhtc.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.havefunace.top/Article/details/gtdufltwdj.html

[F05] 判断文件或目录是否存在
来源：http://dali.dashuyun.cn/Article/details/gtfavimcbw.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yuanzhike.top/Article/details/gtkwxarkrm.html

PHP:  file_exists("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gtekolnmop.html

JS:   fs.existsSync("a.txt")
来源：http://dali.cheryme.top/Article/details/gtvbyfpyqr.html

TS:   fs.existsSync("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlfediwcq.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yj202588.top/Article/details/gtablxzlwm.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.sweek.top/Article/details/gtuionxmxs.html

Ruby: File.exist?("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtzbyykdfs.html

C#:   File.Exists("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtkxpvrisl.html

[F06] 删除文件
来源：http://dali.xylfe.cn/Article/details/gtecewznwx.html

Py:   os.remove("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtzddniabv.html

PHP:  unlink("a.txt");
来源：http://dali.zycfv.cn/Article/details/gthjqomyet.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtkueizbdu.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtfhvuntcy.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yuanzhike.top/Article/details/gtvlzvyxmi.html

Go:   os.Remove("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtcmxnoyvi.html

Ruby: File.delete("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtebzquzfg.html

C#:   File.Delete("a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gtwbyzwerm.html

[F07] 创建目录（含多级）
来源：http://dali.cdnleiting.top/Article/details/gtmrlwvtic.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jyoumei.cn/Article/details/gtgpthmaod.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.fzhhl.top/Article/details/gtufaocyjt.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.svipenyu.cn/Article/details/gtbytnkklt.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yj20258.top/Article/details/gtntmewqhy.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yongpay.top/Article/details/gtgcjosawh.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.hfpthk.cn/Article/details/gtxpexdkgc.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.gogol.net.cn/Article/details/gtymprcxbb.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.xuetiantiany.cn/Article/details/gtrowjowth.html

[F08] 遍历目录
来源：http://dali.sysykeji.top/Article/details/gtduhmyiqy.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhiwuduotai.top/Article/details/gtmgygtwgb.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zycfv.cn/Article/details/gtddobygla.html

JS:   fs.readdirSync("dir")
来源：http://dali.jqgfzy.top/Article/details/gtqcgrsqbb.html

TS:   fs.readdirSync("dir")
来源：http://dali.bjfxy.top/Article/details/gtmfdoyqlh.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.feifeiyinyue.top/Article/details/gtfljnokdm.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.kuanghao11.cn/Article/details/gttaaiquke.html

Ruby: Dir.children("dir")
来源：http://dali.hongshengwenyu.top/Article/details/gttiwcqjgv.html

C#:   Directory.GetFiles("dir")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzozucjpf.html

[F09] 获取文件大小
来源：http://dali.vqdsnc.cn/Article/details/gtmkrpvoql.html

Py:   os.path.getsize("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gttgnjmvxp.html

PHP:  filesize("a.txt");
来源：http://dali.yuanzhike.top/Article/details/gtmhpjkcfs.html

JS:   fs.statSync("a.txt").size
来源：http://dali.vqdsnc.cn/Article/details/gterpbhixq.html

TS:   fs.statSync("a.txt").size
来源：http://dali.nanxinkj.top/Article/details/gtgdvznfbu.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.mhx1999.top/Article/details/gtpebmrcbo.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yuanzhike.top/Article/details/gtjhmknrzs.html

Ruby: File.size("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtxfshdnux.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yueranfly.top/Article/details/gtteceocjm.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yanxiufei.cn/Article/details/gtwhcqpgdz.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtdmeabint.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.redwolf501.top/Article/details/gteyteingp.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gteerijisg.html

TS:   path.extname("a.txt")
来源：http://dali.cashguo.top/Article/details/gtboqbdgyu.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yj20258.top/Article/details/gtjeicbcea.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.ydzc1.top/Article/details/gtjnkkctbr.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.cheryme.top/Article/details/gtmxgnyclm.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hnqzz.top/Article/details/gtdsbuibyi.html

[F11] 复制与移动文件
来源：http://dali.shanyushiyangtech.top/Article/details/gthpsexfzs.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtogmfrjbr.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhijiandao.cn/Article/details/gtivekdcsm.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gzhubu.top/Article/details/gtkmpihcao.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.mhx1999.top/Article/details/gtwqdxroxg.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.nanxinkj.top/Article/details/gtogduehle.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.pycfn.com/Article/details/gtajgsflir.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.aizwys.cn/Article/details/gthtklswrb.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.ppjwa.cn/Article/details/gtbexlcrkz.html

[F12] CSV 读写
来源：http://dali.xziqi.cn/Article/details/gtgydteiyq.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yuanzhike.top/Article/details/gtyrnsebbn.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.havefunace.top/Article/details/gtrrbunpqa.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.birdmap.top/Article/details/gtwjolvvkx.html

TS:   // 同上
来源：http://dali.zdqjudy.top/Article/details/gthcauchfj.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.9152youxi.cn/Article/details/gtffoinozz.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.ybcxt.top/Article/details/gtcquoyzqj.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.guowangkeji.top/Article/details/gtlspeierw.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hongshengwenyu.top/Article/details/gtypxlgsul.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtfjbkqihg.html

G. 面向对象
来源：http://dali.snrcjt.cn/Article/details/gtvwmcwovi.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtbdrearmf.html

[G01] 定义类
来源：http://dali.jlsjyb.cn/Article/details/gtjzesidke.html

Py:   class User: pass
来源：http://dali.hywenlv.cn/Article/details/gtaecuwdkk.html

PHP:  class User {}
来源：http://dali.zhoulong.xyz/Article/details/gtxcccbuwl.html

JS:   class User {}
来源：http://dali.yuanzhike.top/Article/details/gteuoahsgu.html

TS:   class User { name: string = ""; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gthcznvrar.html

Java: class User {}
来源：http://dali.sysykeji.top/Article/details/gtckagxvew.html

Go:   type User struct { Name string }
来源：http://dali.daxiang520.top/Article/details/gtproulpuj.html

Ruby: class User; end
来源：http://dali.wangshuangyany.cn/Article/details/gtxjjcwmbn.html

C#:   class User {}
来源：http://dali.havefunace.top/Article/details/gtipirnhtt.html

[G02] 构造函数
来源：http://dali.yueranfly.top/Article/details/gtlspkfkje.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.cucudq.cn/Article/details/gtovasgrhx.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhoulong.xyz/Article/details/gtbivfyxyw.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtiqotdvkz.html

TS:   constructor(public name: string) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtjlajwnfa.html

Java: User(String name) { this.name = name; }
来源：http://dali.guannengcc.top/Article/details/gtogsaxqvg.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.smart0.xyz/Article/details/gtvchhirea.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.andypj.xyz/Article/details/gtiqbhflra.html

C#:   public User(string name) { Name = name; }
来源：http://dali.gotoacloud.top/Article/details/gthylctbmo.html

[G03] 实例属性
来源：http://dali.cdnleiting.top/Article/details/gtoviaydih.html

Py:   self.name = "x"
来源：http://dali.jlsjyb.cn/Article/details/gtreirroga.html

PHP:  public string $name = "x";
来源：http://dali.cdnleiting.top/Article/details/gtegwpgskj.html

JS:   this.name = "x";
来源：http://dali.jqgufenzy.top/Article/details/gtmawbhwzg.html

TS:   name: string = "x";
来源：http://dali.jqgufenzy.top/Article/details/gtftllesct.html

Java: private String name;
来源：http://dali.wangdashe.top/Article/details/gtdveuxgrk.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yj20258888.top/Article/details/gtwfosfqkw.html

Ruby: @name = "x"
来源：http://dali.sufxvd.cn/Article/details/gtdnxpuayj.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.hfpthk.cn/Article/details/gtqzkqgfgo.html

[G04] 定义方法
来源：http://dali.ppjwa.cn/Article/details/gtvyrldhxh.html

Py:   def greet(self): return self.name
来源：http://dali.iojbl.cn/Article/details/gtfiobuvdh.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hfpthk.cn/Article/details/gtocajbzvo.html

JS:   greet() { return this.name; }
来源：http://dali.jianghu66.top/Article/details/gtounpzqnt.html

TS:   greet(): string { return this.name; }
来源：http://dali.haohaochexian.top/Article/details/gtiakbconu.html

Java: String greet() { return name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtovzqfdrt.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.cheryme.top/Article/details/gtmrcpurfo.html

Ruby: def greet; @name; end
来源：http://dali.pycfn.com/Article/details/gtjgefqzsk.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gtwabtzcsw.html

[G05] 继承
来源：http://dali.tanke756.top/Article/details/gteqkswprv.html

Py:   class Admin(User): pass
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbsmmcdkw.html

PHP:  class Admin extends User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtlyuuoyup.html

JS:   class Admin extends User {}
来源：http://dali.shzxlz.cn/Article/details/gtgydzrqnx.html

TS:   class Admin extends User {}
来源：http://dali.ppjwa.cn/Article/details/gtbswucack.html

Java: class Admin extends User {}
来源：http://dali.hongshengwenyu.top/Article/details/gtsamuufxm.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hnqzz.top/Article/details/gtyifwzvfm.html

Ruby: class Admin < User; end
来源：http://dali.redwolf501.top/Article/details/gtqezjvbcs.html

C#:   class Admin : User {}
来源：http://dali.fzhhl.top/Article/details/gtiqrqslks.html

[G06] 重写方法
来源：http://dali.sweek.top/Article/details/gtjevwldyp.html

Py:   def greet(self): return "admin"
来源：http://dali.fengsongda.top/Article/details/gtxrzmlmtq.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.ppjwa.cn/Article/details/gtadswdlzg.html

JS:   greet() { return "admin"; }
来源：http://dali.dashuyun.cn/Article/details/gtxmrvxghj.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yueranfly.top/Article/details/gtyhenftxl.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.wangshuangyany.cn/Article/details/gtaazvdhab.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.ehwqpu.com/Article/details/gtmileglcf.html

Ruby: def greet; "admin"; end
来源：http://dali.snrcjt.cn/Article/details/gtdckhodya.html

C#:   public override string Greet() => "admin";
来源：http://dali.pengpengdd.cyou/Article/details/gtrkdigiwn.html

[G07] 调用父类方法
来源：http://dali.tanke756.top/Article/details/gtucdvrpqa.html

Py:   super().greet()
来源：http://dali.ppjwa.cn/Article/details/gtcotpiazw.html

PHP:  parent::greet();
来源：http://dali.vqdsnc.cn/Article/details/gtucvvhyzs.html

JS:   super.greet();
来源：http://dali.chenzaomai.com/Article/details/gtquflluvz.html

TS:   super.greet();
来源：http://dali.tian-w.cn/Article/details/gtqgdqcver.html

Java: super.greet();
来源：http://dali.sxryk.cn/Article/details/gtsvdtukyk.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmtiwipjp.html

Ruby: super
来源：http://dali.zhengqikj.top/Article/details/gtfokixflm.html

C#:   base.Greet();
来源：http://dali.fzhhl.top/Article/details/gtineavriy.html

[G08] 静态方法与属性
来源：http://dali.0kj1m.cn/Article/details/gtuaoocjkj.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.sufxvd.cn/Article/details/gtjkrhsxep.html

PHP:  public static function f() {}
来源：http://dali.yongpay.top/Article/details/gtjzvtyvua.html

JS:   static f() {}
来源：http://dali.yj20258888.top/Article/details/gtybvlahcy.html

TS:   static f(): void {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbeacgnab.html

Java: static void f() {}
来源：http://dali.zhiwuduotai.top/Article/details/gtvtdbzibm.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.ywan-chungtsiang.top/Article/details/gtizzzeehb.html

Ruby: def self.f; end
来源：http://dali.yvedp.cn/Article/details/gtskjydgrc.html

C#:   public static void F() {}
来源：http://dali.xylfe.cn/Article/details/gtwkljfgbj.html

[G09] 接口 / 抽象类
来源：http://dali.jinqigfzy.top/Article/details/gtgyootvyt.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yangfankeji.com/Article/details/gtbhbowtsp.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jianghu66.top/Article/details/gtziwmrvmr.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.gzhubu.top/Article/details/gtemnvhmjt.html

TS:   interface Shape { area(): number; }
来源：http://dali.wangdashe.top/Article/details/gtybhvepqi.html

Java: interface Shape { double area(); }
来源：http://dali.xziqi.cn/Article/details/gtdqimqbil.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.redwolf501.top/Article/details/gtjqmqcqgz.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xuetiantiany.cn/Article/details/gtrvailcxy.html

C#:   interface IShape { double Area(); }
来源：http://dali.nanxuanxn.top/Article/details/gtvqjsrnbx.html

[G10] 访问控制
来源：http://dali.vqdsnc.cn/Article/details/gtbnqkpgxz.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.smart0.xyz/Article/details/gtinomlxap.html

PHP:  public / protected / private
来源：http://dali.yanxiufei.cn/Article/details/gtyconjduu.html

JS:   #private 字段；其余公开
来源：http://dali.zhiwuduotai.top/Article/details/gtsjoigsaw.html

TS:   public / protected / private
来源：http://dali.cqqwz.cn/Article/details/gtitrwcsws.html

Java: public / protected / private / 默认包级
来源：http://dali.xinyue.icu/Article/details/gtetxcdhtk.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yangfankeji.com/Article/details/gtoqrgfogj.html

Ruby: public / protected / private
来源：http://dali.gzhubu.top/Article/details/gtxrjehgjg.html

C#:   public / protected / private / internal
来源：http://dali.wangshuangyany.cn/Article/details/gtujfzblgv.html

[G11] getter / setter
来源：http://dali.aizwys.cn/Article/details/gtemvbdfty.html

Py:   @property 与 @x.setter
来源：http://dali.yangfankeji.com/Article/details/gtykbkkske.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jqgfzy.top/Article/details/gtuavcsvhp.html

JS:   get name() { return this._name; }
来源：http://dali.yuanzhike.top/Article/details/gtmeffazxc.html

TS:   get name(): string { return this._name; }
来源：http://dali.cdnleiting.top/Article/details/gtwtkzittk.html

Java: public String getName() { return name; }
来源：http://dali.daxiang520.top/Article/details/gttrpxwxnx.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.snrcjt.cn/Article/details/gtsipijrhy.html

Ruby: attr_accessor :name
来源：http://dali.nanxinkj.top/Article/details/gttgjvzgkf.html

C#:   public string Name { get; set; }
来源：http://dali.kuanghao11.cn/Article/details/gtbqvwjaze.html

[G12] 对象转字符串
来源：http://dali.andypj.xyz/Article/details/gtztchekko.html

Py:   def __str__(self): return self.name
来源：http://dali.haohaochexian.top/Article/details/gtqvcfhcbz.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtkhvddzfz.html

JS:   toString() { return this.name; }
来源：http://dali.zdqjudy.top/Article/details/gtrkhwwpse.html

TS:   toString(): string { return this.name; }
来源：http://dali.yuxming.cn/Article/details/gtvgrysdff.html

Java: @Override public String toString() { return name; }
来源：http://dali.gaohongyu789.top/Article/details/gtankgsxxo.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.guannengcc.top/Article/details/gtqwvrkzbp.html

Ruby: def to_s; @name; end
来源：http://dali.zdqjudy.top/Article/details/gtipaevqye.html

C#:   public override string ToString() => Name;
来源：http://dali.ybcxt.top/Article/details/gtzzbshxiz.html

[G13] 判断对象类型
来源：http://dali.chenzaomai.com/Article/details/gtbvduxypq.html

Py:   isinstance(u, User)
来源：http://dali.redwolf501.top/Article/details/gtcsoridxn.html

PHP:  $u instanceof User
来源：http://dali.daria6918.cn/Article/details/gtubgdraip.html

JS:   u instanceof User
来源：http://dali.vqdsnc.cn/Article/details/gtsosgtsgu.html

TS:   u instanceof User
来源：http://dali.xziqi.cn/Article/details/gtrrdfbryt.html

Java: u instanceof User
来源：http://dali.gotoacloud.top/Article/details/gtnzwoawiw.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.redwolf501.top/Article/details/gtgwvxwmrv.html

Ruby: u.is_a?(User)
来源：http://dali.jinqigfzy.top/Article/details/gthhvmbfzl.html

C#:   u is User
来源：http://dali.yongpay.top/Article/details/gttybnloeq.html

[G14] 数据类 / record
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtomilejyt.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhixingplan.top/Article/details/gtplwwwsfi.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.xylfe.cn/Article/details/gtycsxnprf.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.gaohongyu789.top/Article/details/gtmyebflfx.html

TS:   type User = { name: string; age: number };
来源：http://dali.yanxiufei.cn/Article/details/gtorqhossw.html

Java: record User(String name, int age) {}
来源：http://dali.zdqjudy.top/Article/details/gtzizsjktj.html

Go:   type User struct { Name string; Age int }
来源：http://dali.nanxuanxn.top/Article/details/gtsewzitpt.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhoulong.xyz/Article/details/gtwvrxgjua.html

C#:   record User(string Name, int Age);
来源：http://dali.ppjwa.cn/Article/details/gtohilhxqp.html

[G15] 枚举
来源：http://dali.cqqwz.cn/Article/details/gtsurvlzoy.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.shuidangran.top/Article/details/gtdqvzsodb.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtpnkixrfb.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhaomingkeji.xyz/Article/details/gtygtkmmud.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.tian-w.cn/Article/details/gtdcsrfiqw.html

Java: enum Color { RED, GREEN }
来源：http://dali.wangshuangyany.cn/Article/details/gtrcjygiia.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.tianlin.xyz/Article/details/gtpdmusjbh.html

Ruby: Color = %i[red green].freeze
来源：http://dali.sweek.top/Article/details/gtlwhtbyxs.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.iojbl.cn/Article/details/gtwuhbfvbm.html

[G16] 对象转数组 / 字典
来源：http://dali.jinqigfzy.top/Article/details/gtucugpxco.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.gogol.net.cn/Article/details/gtqeovirwy.html

PHP:  get_object_vars($obj);
来源：http://dali.daxiang520.top/Article/details/gtdqoftlzs.html

JS:   Object.entries(obj)
来源：http://dali.quarkkingdee.top/Article/details/gtwosfqlna.html

TS:   Object.entries(obj)
来源：http://dali.yj202588.top/Article/details/gtfdcaxsqs.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.c1oappe.top/Article/details/gthcsstleu.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.cheryme.top/Article/details/gtftpowvdx.html

Ruby: obj.instance_variables
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmrqccdzf.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhoulong.xyz/Article/details/gttitsbusb.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtwmvkdoaz.html

H. 异常与错误处理
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsuezuepp.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtuwloqmtl.html

[H01] try / catch 基础
来源：http://dali.yj20258888.top/Article/details/gtrcwdlbag.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.wangshuangyany.cn/Article/details/gtqqtffekt.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.tian-w.cn/Article/details/gtymovmkvn.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.9152youxi.cn/Article/details/gtvgyglvem.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.ydzc1.top/Article/details/gtvqgwsmlg.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.fengsongda.top/Article/details/gtbvzbifew.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jinghuilouyu.cn/Article/details/gtnkbufkgv.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.sxryk.cn/Article/details/gtqhjvebzl.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvcgvnmib.html

[H02] finally / ensure 收尾
来源：http://dali.hnqzz.top/Article/details/gtmzlrdojg.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yongpay.top/Article/details/gtgqfbqanu.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.sufxvd.cn/Article/details/gtlfrrdjpu.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.chenzaomai.com/Article/details/gtpjyfdcko.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.pengpengdd.cyou/Article/details/gtnflldhxs.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtxtvbqfum.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.quarkkingdee.top/Article/details/gtgqpvrkpo.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.feifeiyinyue.top/Article/details/gtxeswpfeq.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.daxiang520.top/Article/details/gtvrekfyzr.html

[H03] 主动抛出异常
来源：http://dali.316326.xyz/Article/details/gtvkotoamw.html

Py:   raise ValueError("错误信息")
来源：http://dali.hammf.cn/Article/details/gtydqujglz.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtarckltje.html

JS:   throw new Error("错误信息");
来源：http://dali.snrcjt.cn/Article/details/gtmyhxqjrp.html

TS:   throw new Error("错误信息");
来源：http://dali.guannengcc.top/Article/details/gticifofje.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhaomingkeji.xyz/Article/details/gthiwstgbo.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.aibaodan.cn/Article/details/gtfamyvube.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.cdnleiting.top/Article/details/gtogrlmrmd.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.redwolf501.top/Article/details/gtnfbnmejm.html

[H04] 自定义异常类型
来源：http://dali.hywenlv.cn/Article/details/gttnzeaeig.html

Py:   class MyError(Exception): pass
来源：http://dali.yonumen.top/Article/details/gtddmvdapt.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.sxryk.cn/Article/details/gtupbvvcmx.html

JS:   class MyError extends Error {}
来源：http://dali.yueranfly.top/Article/details/gtibawulrj.html

TS:   class MyError extends Error {}
来源：http://dali.gotoacloud.top/Article/details/gtglrevyhi.html

Java: class MyException extends RuntimeException {}
来源：http://dali.chenlongwang.top/Article/details/gthoyqdvvo.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.vqdsnc.cn/Article/details/gtxxmpipig.html

Ruby: class MyError < StandardError; end
来源：http://dali.cucudq.cn/Article/details/gtantnfvuf.html

C#:   class MyException : Exception {}
来源：http://dali.ehwqpu.com/Article/details/gttwrdyfqq.html

[H05] 捕获特定类型
来源：http://dali.shanyushiyangtech.top/Article/details/gtcamdsosy.html

Py:   except ValueError as e:
来源：http://dali.tanke756.top/Article/details/gtysornula.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.shuidangran.top/Article/details/gtdvthsara.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.0kj1m.cn/Article/details/gtraevspif.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.aizwys.cn/Article/details/gtxdwhcygy.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhengqikj.top/Article/details/gtvwiiusbt.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.hfpthk.cn/Article/details/gtqzozrvfd.html

Ruby: rescue ArgumentError => e
来源：http://dali.wangdashe.top/Article/details/gtmycpzahp.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.redwolf501.top/Article/details/gtfivezszo.html

[H06] 可选值 / 空值安全访问
来源：http://dali.xylfe.cn/Article/details/gtxzzzylfy.html


<!-- 参考信息 -->