代发 wailian999

C#:   File.ReadAllText("a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gtjpurpxgx.html

[F02] 逐行读取文件
来源：http://dali.zhoulong.xyz/Article/details/gtqpuipjys.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.gogol.net.cn/Article/details/gtvsfwuohb.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jiagoushi.top/Article/details/gtchnxhrug.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.redwolf501.top/Article/details/gtnarsukwd.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ydzc1.top/Article/details/gtkpnhuycb.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.kuanghao11.cn/Article/details/gtzcixarca.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.aibaodan.cn/Article/details/gtpeurdkuo.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jqgfzy.top/Article/details/gtgorzgzcd.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.guowangkeji.top/Article/details/gtecrsllzn.html

[F03] 写入文件（覆盖）
来源：http://dali.tian-w.cn/Article/details/gtbvcmdxdu.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.fengsongda.top/Article/details/gtprhppitw.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.mhx1999.top/Article/details/gtihurdrav.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hysaishi.cn/Article/details/gtybecjekf.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.dianchejie.cn/Article/details/gttnbepfog.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zycfv.cn/Article/details/gtfmcvqjpl.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.kuanghao11.cn/Article/details/gtjbdqbmom.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.tanke756.top/Article/details/gtuliqzckk.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.pengpengdd.cyou/Article/details/gtovgcjcig.html

[F04] 追加写入文件
来源：http://dali.cashguo.top/Article/details/gtwdedqpjk.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yuanzhike.top/Article/details/gtvghzsezf.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdusgvtuj.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtevizxxnt.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpqikvrfw.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.svipenyu.cn/Article/details/gttymwfipq.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.guowangkeji.top/Article/details/gtoadwucod.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.gogol.net.cn/Article/details/gtsznrrcol.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.sufxvd.cn/Article/details/gtabalgoii.html

[F05] 判断文件或目录是否存在
来源：http://dali.havefunace.top/Article/details/gtmyfbkico.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.nwbrower.top/Article/details/gtrkwctmed.html

PHP:  file_exists("a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gtecmzibsc.html

JS:   fs.existsSync("a.txt")
来源：http://dali.cashguo.top/Article/details/gtnrspcxha.html

TS:   fs.existsSync("a.txt")
来源：http://dali.meibo888.top/Article/details/gtwblmfubo.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.9152youxi.cn/Article/details/gtztprmbnl.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.xylfe.cn/Article/details/gtyldnsvyv.html

Ruby: File.exist?("a.txt")
来源：http://dali.hammf.cn/Article/details/gtabcfljwi.html

C#:   File.Exists("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtarzrhlth.html

[F06] 删除文件
来源：http://dali.ivvv.top/Article/details/gtpttrrptt.html

Py:   os.remove("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwybhlwfd.html

PHP:  unlink("a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrvumnglk.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.316326.xyz/Article/details/gtfjyrpgxr.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtwjuvpvsx.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yj20258.top/Article/details/gtoheesgji.html

Go:   os.Remove("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gteqhwivmu.html

Ruby: File.delete("a.txt")
来源：http://dali.meibo888.top/Article/details/gtfzcvfugv.html

C#:   File.Delete("a.txt");
来源：http://dali.sxryk.cn/Article/details/gtuqqowylj.html

[F07] 创建目录（含多级）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrabqsver.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.daxiang520.top/Article/details/gtwpeyyeic.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hfpthk.cn/Article/details/gtmeorwghq.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yueranfly.top/Article/details/gtvlvyifky.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hammf.cn/Article/details/gtykejrdbk.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.bjfxy.top/Article/details/gtkrxgglcc.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.9152youxi.cn/Article/details/gtmgnkuioc.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.nwbrower.top/Article/details/gthwtoploy.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.chenzaomai.com/Article/details/gtlvcbdzfx.html

[F08] 遍历目录
来源：http://dali.xylfe.cn/Article/details/gtgzdjrdse.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.hfpthk.cn/Article/details/gtsyyzfynz.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.dianchejie.cn/Article/details/gttbeeiplb.html

JS:   fs.readdirSync("dir")
来源：http://dali.wangdashe.top/Article/details/gtoibdheeg.html

TS:   fs.readdirSync("dir")
来源：http://dali.jianghu66.top/Article/details/gtfuksnszf.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.nwbrower.top/Article/details/gtetqxuwgz.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.gaohongyu789.top/Article/details/gtcaeegdes.html

Ruby: Dir.children("dir")
来源：http://dali.ppjwa.cn/Article/details/gtirdohepk.html

C#:   Directory.GetFiles("dir")
来源：http://dali.9152youxi.cn/Article/details/gtvjynakwv.html

[F09] 获取文件大小
来源：http://dali.hammf.cn/Article/details/gtfsceieln.html

Py:   os.path.getsize("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtkkgupvcc.html

PHP:  filesize("a.txt");
来源：http://dali.mhx1999.top/Article/details/gtdqeqfspg.html

JS:   fs.statSync("a.txt").size
来源：http://dali.quarkkingdee.top/Article/details/gtwxbqxfgf.html

TS:   fs.statSync("a.txt").size
来源：http://dali.sysykeji.top/Article/details/gtmbggswbf.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.ppjwa.cn/Article/details/gtjohahoya.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.gogol.net.cn/Article/details/gtwgwexzpc.html

Ruby: File.size("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtstiudvce.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.xinyue.icu/Article/details/gtdqcmhjgs.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jqgufenzy.top/Article/details/gtszkjsxvv.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.bjfxy.top/Article/details/gtxxivsjpy.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.sufxvd.cn/Article/details/gtfyaopizq.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.meibo888.top/Article/details/gtxzoauehb.html

TS:   path.extname("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtkapkoffy.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxpkciqvx.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.xylfe.cn/Article/details/gtcszbvyov.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtfuehdovj.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjfbypizx.html

[F11] 复制与移动文件
来源：http://dali.dashuyun.cn/Article/details/gtqoghngcs.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.gzhubu.top/Article/details/gtletwfite.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.sysykeji.top/Article/details/gtdgfsqomf.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.chenzaomai.com/Article/details/gtcikcmrae.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtypduvqrl.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.guannengcc.top/Article/details/gttxsfqaii.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.svipenyu.cn/Article/details/gtuimowdfu.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jiagoushi.top/Article/details/gtvujfyymk.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yj20258888.top/Article/details/gtfoqffnda.html

[F12] CSV 读写
来源：http://dali.yuxming.cn/Article/details/gtvwnwoqje.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.sysykeji.top/Article/details/gtqtnbvkib.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.quarkkingdee.top/Article/details/gttyiydtwx.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.cdnleiting.top/Article/details/gtytswlxrr.html

TS:   // 同上
来源：http://dali.havefunace.top/Article/details/gtmqiqdpbv.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.xziqi.cn/Article/details/gttyxiaygv.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.9152youxi.cn/Article/details/gtqxbfsxok.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.wangshuangyany.cn/Article/details/gtchdrwvto.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jiagoushi.top/Article/details/gtmjbkdesk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtytiutdhg.html

G. 面向对象
来源：http://dali.ehwqpu.com/Article/details/gtasqoziij.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtqrexjrzk.html

[G01] 定义类
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtufnzssyt.html

Py:   class User: pass
来源：http://dali.aizwys.cn/Article/details/gtrwrufryg.html

PHP:  class User {}
来源：http://dali.tian-w.cn/Article/details/gtyialbpik.html

JS:   class User {}
来源：http://dali.svipenyu.cn/Article/details/gtsuxyzvvg.html

TS:   class User { name: string = ""; }
来源：http://dali.zhongyouzk.top/Article/details/gtlgqcrjoq.html

Java: class User {}
来源：http://dali.xuanzx.com/Article/details/gtmmkdnolk.html

Go:   type User struct { Name string }
来源：http://dali.ppjwa.cn/Article/details/gtcnjibodk.html

Ruby: class User; end
来源：http://dali.daria6918.cn/Article/details/gtcdtujyit.html

C#:   class User {}
来源：http://dali.zhixingplan.top/Article/details/gtrigzhgjv.html

[G02] 构造函数
来源：http://dali.yj20258888.top/Article/details/gtluhyxiej.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.ivvv.top/Article/details/gtbhpirnff.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.havefunace.top/Article/details/gteldyaikd.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yueranfly.top/Article/details/gtiacfiwbp.html

TS:   constructor(public name: string) {}
来源：http://dali.yuanzhike.top/Article/details/gtghpcmqxi.html

Java: User(String name) { this.name = name; }
来源：http://dali.shzxlz.cn/Article/details/gtbdhwokpg.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yj20258888.top/Article/details/gtefrvhxxr.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhongyouzk.top/Article/details/gtdfymctsm.html

C#:   public User(string name) { Name = name; }
来源：http://dali.ivvv.top/Article/details/gtxxygrjxa.html

[G03] 实例属性
来源：http://dali.gaohongyu789.top/Article/details/gthrlemmkh.html

Py:   self.name = "x"
来源：http://dali.hfpthk.cn/Article/details/gtdnydgwjp.html

PHP:  public string $name = "x";
来源：http://dali.ydzc1.top/Article/details/gtqwiszfqe.html

JS:   this.name = "x";
来源：http://dali.kuanghao11.cn/Article/details/gtpwzouipn.html

TS:   name: string = "x";
来源：http://dali.tanke756.top/Article/details/gtidvnfkkq.html

Java: private String name;
来源：http://dali.ehwqpu.com/Article/details/gtfbgvhvwg.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.ydzc1.top/Article/details/gtyawzwdvw.html

Ruby: @name = "x"
来源：http://dali.guannengcc.top/Article/details/gtgkynxfqq.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.guowangkeji.top/Article/details/gtzkavnada.html

[G04] 定义方法
来源：http://dali.tian-w.cn/Article/details/gtokomxorg.html

Py:   def greet(self): return self.name
来源：http://dali.jyoumei.cn/Article/details/gtswonylbu.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.snrcjt.cn/Article/details/gtaqegcqok.html

JS:   greet() { return this.name; }
来源：http://dali.tian-w.cn/Article/details/gtlgjbqhxd.html

TS:   greet(): string { return this.name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyloadvfx.html

Java: String greet() { return name; }
来源：http://dali.yj202588.top/Article/details/gtwbdhqwvu.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.shanyushiyangtech.top/Article/details/gtztaowgoq.html

Ruby: def greet; @name; end
来源：http://dali.zhoulong.xyz/Article/details/gtgxoljnrf.html

C#:   public string Greet() => Name;
来源：http://dali.9152youxi.cn/Article/details/gtomrscwap.html

[G05] 继承
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttkvrftta.html

Py:   class Admin(User): pass
来源：http://dali.jyoumei.cn/Article/details/gtbeyxeify.html

PHP:  class Admin extends User {}
来源：http://dali.dashuyun.cn/Article/details/gtndvqcuir.html

JS:   class Admin extends User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtkqrxhdnc.html

TS:   class Admin extends User {}
来源：http://dali.sysykeji.top/Article/details/gtzrerpcvg.html

Java: class Admin extends User {}
来源：http://dali.vqdsnc.cn/Article/details/gtqjkuwyei.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jlsjyb.cn/Article/details/gtduwymxyy.html

Ruby: class Admin < User; end
来源：http://dali.yj202588.top/Article/details/gtogejohio.html

C#:   class Admin : User {}
来源：http://dali.zhoulong.xyz/Article/details/gtjaqpksip.html

[G06] 重写方法
来源：http://dali.chenzaomai.com/Article/details/gteejwramr.html

Py:   def greet(self): return "admin"
来源：http://dali.daria6918.cn/Article/details/gticfqurvz.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hnqzz.top/Article/details/gtiyfghits.html

JS:   greet() { return "admin"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtjfiymdhi.html

TS:   greet(): string { return "admin"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdkybhuty.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.sufxvd.cn/Article/details/gtrgvdxwjl.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.tanke756.top/Article/details/gtnatpevyh.html

Ruby: def greet; "admin"; end
来源：http://dali.tian-w.cn/Article/details/gtqkwyypuy.html

C#:   public override string Greet() => "admin";
来源：http://dali.sufxvd.cn/Article/details/gtmlyimlva.html

[G07] 调用父类方法
来源：http://dali.yanxiufei.cn/Article/details/gtekqmetee.html

Py:   super().greet()
来源：http://dali.zhixingplan.top/Article/details/gtsklsiknj.html

PHP:  parent::greet();
来源：http://dali.hongshengwenyu.top/Article/details/gtcxfaurjz.html

JS:   super.greet();
来源：http://dali.shzxlz.cn/Article/details/gtysccmeog.html

TS:   super.greet();
来源：http://dali.pycfn.com/Article/details/gtpwahttki.html

Java: super.greet();
来源：http://dali.kuanghao11.cn/Article/details/gtsogwduhq.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.tian-w.cn/Article/details/gtznztycfi.html

Ruby: super
来源：http://dali.shanyushiyangkeji.top/Article/details/gtshtxyykt.html

C#:   base.Greet();
来源：http://dali.haohaochexian.top/Article/details/gtjhtudahr.html

[G08] 静态方法与属性
来源：http://dali.chenlongwang.top/Article/details/gtukhmuysx.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.ppjwa.cn/Article/details/gtwcivitmr.html

PHP:  public static function f() {}
来源：http://dali.wangdashe.top/Article/details/gttjesdkzs.html

JS:   static f() {}
来源：http://dali.daria6918.cn/Article/details/gtmvtlptlz.html

TS:   static f(): void {}
来源：http://dali.gaohongyu789.top/Article/details/gtpfcbpsuc.html

Java: static void f() {}
来源：http://dali.yj20258888.top/Article/details/gtkqeiqjmk.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlgnyjnwc.html

Ruby: def self.f; end
来源：http://dali.quarkkingdee.top/Article/details/gtgxqqjzeq.html

C#:   public static void F() {}
来源：http://dali.ivvv.top/Article/details/gtoarnoisn.html

[G09] 接口 / 抽象类
来源：http://dali.c1oappe.top/Article/details/gtshuukwrj.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnvvbujsm.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jinqigufen.top/Article/details/gtuuypjgmz.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.nwbrower.top/Article/details/gtqqxykvel.html

TS:   interface Shape { area(): number; }
来源：http://dali.cdnleiting.top/Article/details/gtyeazefsb.html

Java: interface Shape { double area(); }
来源：http://dali.nanxinkj.top/Article/details/gtpuhcfpbd.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hnqzz.top/Article/details/gtryesuuae.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.aizwys.cn/Article/details/gtxpnjteoz.html

C#:   interface IShape { double Area(); }
来源：http://dali.cqqwz.cn/Article/details/gtkkkphrge.html

[G10] 访问控制
来源：http://dali.vqdsnc.cn/Article/details/gtghwllpvz.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhixingplan.top/Article/details/gtgdxcfjog.html

PHP:  public / protected / private
来源：http://dali.xuetiantiany.cn/Article/details/gtflcfdsox.html

JS:   #private 字段；其余公开
来源：http://dali.cashguo.top/Article/details/gthgqyojjg.html

TS:   public / protected / private
来源：http://dali.havefunace.top/Article/details/gtrebmiwld.html

Java: public / protected / private / 默认包级
来源：http://dali.cqqwz.cn/Article/details/gtezmefbdc.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jinyuanbaomall.cn/Article/details/gtycgtlamf.html

Ruby: public / protected / private
来源：http://dali.shuidangran.top/Article/details/gtkolcrbkp.html

C#:   public / protected / private / internal
来源：http://dali.ehwqpu.com/Article/details/gtlkwtvxsx.html

[G11] getter / setter
来源：http://dali.smart0.xyz/Article/details/gthteihgei.html

Py:   @property 与 @x.setter
来源：http://dali.hywenlv.cn/Article/details/gtcmtsvbzk.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtqdybtkyc.html

JS:   get name() { return this._name; }
来源：http://dali.cheryme.top/Article/details/gtecsylllj.html

TS:   get name(): string { return this._name; }
来源：http://dali.hnqzz.top/Article/details/gtwqwwdtcu.html

Java: public String getName() { return name; }
来源：http://dali.hammf.cn/Article/details/gtablgbksv.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.cucudq.cn/Article/details/gtdypfhupk.html

Ruby: attr_accessor :name
来源：http://dali.tianlin.xyz/Article/details/gtytpkouyb.html

C#:   public string Name { get; set; }
来源：http://dali.yj20258888.top/Article/details/gtibfljfnd.html

[G12] 对象转字符串
来源：http://dali.snrcjt.cn/Article/details/gtghvdgzbl.html

Py:   def __str__(self): return self.name
来源：http://dali.kuanghao11.cn/Article/details/gtmgehnshg.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.shuidangran.top/Article/details/gtawoxgqsf.html

JS:   toString() { return this.name; }
来源：http://dali.guowangkeji.top/Article/details/gtysqupcys.html

TS:   toString(): string { return this.name; }
来源：http://dali.yonumen.top/Article/details/gtpvrvsieb.html

Java: @Override public String toString() { return name; }
来源：http://dali.gotoacloud.top/Article/details/gtrtpfgvmg.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jiagoushi.top/Article/details/gttyolfcie.html

Ruby: def to_s; @name; end
来源：http://dali.hnxiangtu.top/Article/details/gtpktzidhm.html

C#:   public override string ToString() => Name;
来源：http://dali.jlsjyb.cn/Article/details/gtcbhmjtlk.html

[G13] 判断对象类型
来源：http://dali.shangyingyoupin.top/Article/details/gtwwmhcgif.html

Py:   isinstance(u, User)
来源：http://dali.meibo888.top/Article/details/gtzwkflkce.html

PHP:  $u instanceof User
来源：http://dali.yonumen.top/Article/details/gtjideqneu.html

JS:   u instanceof User
来源：http://dali.shanyushiyangtech.top/Article/details/gtyfomzwtt.html

TS:   u instanceof User
来源：http://dali.tianlin.xyz/Article/details/gtdcnuwyof.html

Java: u instanceof User
来源：http://dali.tian-w.cn/Article/details/gthhlevbot.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zdqjudy.top/Article/details/gtjnkkdfqs.html

Ruby: u.is_a?(User)
来源：http://dali.zhongyouzk.top/Article/details/gtofulwajs.html

C#:   u is User
来源：http://dali.jinqigufen.top/Article/details/gtykzeqjli.html

[G14] 数据类 / record
来源：http://dali.dianchejie.cn/Article/details/gtcuwlfrqd.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.shuidangran.top/Article/details/gtyknxrtly.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hnqzz.top/Article/details/gtqfglcjqi.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.kuanghao11.cn/Article/details/gtecwatnac.html

TS:   type User = { name: string; age: number };
来源：http://dali.zycfv.cn/Article/details/gtzzmkjoex.html

Java: record User(String name, int age) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtfxffqruw.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jyoumei.cn/Article/details/gthsdwgtvg.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.tian-w.cn/Article/details/gtnrzrdewi.html

C#:   record User(string Name, int Age);
来源：http://dali.daxiang520.top/Article/details/gtdkgnmnfb.html

[G15] 枚举
来源：http://dali.sysykeji.top/Article/details/gtxbyrzoul.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.tianlin.xyz/Article/details/gtqoelnscp.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.cashguo.top/Article/details/gtzlslfvzv.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.sweek.top/Article/details/gtlkqrdolu.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ivvv.top/Article/details/gtmcpsxvxp.html

Java: enum Color { RED, GREEN }
来源：http://dali.pycfn.com/Article/details/gtfohzugpf.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.pengpengdd.cyou/Article/details/gternzodyh.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkcvapygr.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthujcghuj.html

[G16] 对象转数组 / 字典
来源：http://dali.zhiwuduotai.top/Article/details/gtyarvrewl.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.andypj.xyz/Article/details/gtymptjggl.html

PHP:  get_object_vars($obj);
来源：http://dali.zdqjudy.top/Article/details/gtjfcpkmkv.html

JS:   Object.entries(obj)
来源：http://dali.haohaochexian.top/Article/details/gtyaqhkgww.html

TS:   Object.entries(obj)
来源：http://dali.wangdashe.top/Article/details/gtttpqpswo.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.cashguo.top/Article/details/gttdfjaufk.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.tanke756.top/Article/details/gtxwvdgknz.html

Ruby: obj.instance_variables
来源：http://dali.aibaodan.cn/Article/details/gtfoaglnce.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hnxiangtu.top/Article/details/gtndnwowlr.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtszqxkujj.html

H. 异常与错误处理
来源：http://dali.andypj.xyz/Article/details/gteoobtjeh.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtdxdvttws.html

[H01] try / catch 基础
来源：http://dali.chenjidiqi.icu/Article/details/gtvtetyxzq.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.gzhubu.top/Article/details/gttgrgpzkz.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.sweek.top/Article/details/gtkeiijdtl.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yj202588.top/Article/details/gtcqxxiylg.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.cheryme.top/Article/details/gtqjiblqta.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.shangyingyoupin.top/Article/details/gtbueekkbr.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.sweek.top/Article/details/gtgwxzlhbz.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.aibaodan.cn/Article/details/gtaycatjwx.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ydzc1.top/Article/details/gtelifrmpp.html

[H02] finally / ensure 收尾
来源：http://dali.meibo888.top/Article/details/gtfilrkwku.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.birdmap.top/Article/details/gtzzbqtppf.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.snrcjt.cn/Article/details/gtvqmwnqdn.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.tianlin.xyz/Article/details/gtbszsospq.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.xuanzx.com/Article/details/gtozotrxya.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.snrcjt.cn/Article/details/gtzboulbzg.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.ydzc1.top/Article/details/gtnkqogwjn.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.cqqwz.cn/Article/details/gtomlefhze.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.gogol.net.cn/Article/details/gtcxvwtdmw.html

[H03] 主动抛出异常
来源：http://dali.yuxming.cn/Article/details/gtcifckmfm.html

Py:   raise ValueError("错误信息")
来源：http://dali.cdnleiting.top/Article/details/gtvfwgnimf.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.cdnleiting.top/Article/details/gtbwwcdsxa.html

JS:   throw new Error("错误信息");
来源：http://dali.wangdashe.top/Article/details/gtkahbfeto.html

TS:   throw new Error("错误信息");
来源：http://dali.ehwqpu.com/Article/details/gtvlhmxjkc.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.ydzc1.top/Article/details/gtiduxemdr.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhixingplan.top/Article/details/gtllnjgsxg.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.ppjwa.cn/Article/details/gtolvtgpjk.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.wangshuangyany.cn/Article/details/gtdolvyzoi.html

[H04] 自定义异常类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdbsvjwnr.html

Py:   class MyError(Exception): pass
来源：http://dali.xuanzx.com/Article/details/gtftyqouce.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yuxming.cn/Article/details/gtelwzpccn.html

JS:   class MyError extends Error {}
来源：http://dali.xuetiantiany.cn/Article/details/gtbigquqcy.html

TS:   class MyError extends Error {}
来源：http://dali.tianlin.xyz/Article/details/gtplyjqnee.html

Java: class MyException extends RuntimeException {}
来源：http://dali.ydzc1.top/Article/details/gtwrdylsfy.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yj202588.top/Article/details/gtsangxmob.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhoulong.xyz/Article/details/gtubqelamt.html

C#:   class MyException : Exception {}
来源：http://dali.zhongyouzk.top/Article/details/gtiaffxpye.html

[H05] 捕获特定类型
来源：http://dali.hnqzz.top/Article/details/gtcrqqnynp.html

Py:   except ValueError as e:
来源：http://dali.shanyushiyangtech.top/Article/details/gtebjkunfc.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.hysaishi.cn/Article/details/gtqvvfgfzk.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jlsjyb.cn/Article/details/gtsjxopucx.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yuxming.cn/Article/details/gtbzadxlbo.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yj20258.top/Article/details/gteukpjeqk.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yonumen.top/Article/details/gtcnkgwppk.html

Ruby: rescue ArgumentError => e
来源：http://dali.fengsongda.top/Article/details/gtdfbkleej.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.xinyue.icu/Article/details/gtnudwaxgy.html

[H06] 可选值 / 空值安全访问
来源：http://dali.daxiang520.top/Article/details/gtqwesakyf.html

Py:   value = d.get("k") or default
来源：http://dali.nanxinkj.top/Article/details/gtrqfxzreg.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhiwuduotai.top/Article/details/gtdocbntgm.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.fzhhl.top/Article/details/gtqvhwqmam.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zycfv.cn/Article/details/gtbhrxoxve.html


<!-- 参考信息 -->