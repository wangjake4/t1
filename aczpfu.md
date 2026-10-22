代发 wailian999

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.dianchejie.cn/Article/details/gt2bfjxceww.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.pengpengdd.cyou/Article/details/gt2fmnhtqrp.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.316326.xyz/Article/details/gt2zmjoowit.html

Ruby: File.read("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2fmfdvfqh.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.havefunace.top/Article/details/gt2clckveym.html

[F02] 逐行读取文件
来源：http://dali.haohaochexian.top/Article/details/gt2eppfsgsg.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.9152youxi.cn/Article/details/gt2zdtcrbnc.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.aibaodan.cn/Article/details/gt2mhwxpoel.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.tanke756.top/Article/details/gt2dimfewnz.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yongpay.top/Article/details/gt2suemsqcb.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yj20258.top/Article/details/gt2dshsnyuu.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jinqigfzy.top/Article/details/gt2toauwsry.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jiagoushi.top/Article/details/gt2scmzwdsq.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.tianlin.xyz/Article/details/gt2yuuflcgk.html

[F03] 写入文件（覆盖）
来源：http://dali.fengsongda.top/Article/details/gt2ktpsvvdp.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.daxiang520.top/Article/details/gt2btbxmgjx.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yj202588.top/Article/details/gt2gvhxhmww.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sweek.top/Article/details/gt2lowuhibc.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.chenzaomai.com/Article/details/gt2anydwuhd.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lntkblum.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.fzhhl.top/Article/details/gt2mnohaadj.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wygexvin.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.mhx1999.top/Article/details/gt2sogktswd.html

[F04] 追加写入文件
来源：http://dali.cucudq.cn/Article/details/gt2dqqdbkhh.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhixingplan.top/Article/details/gt2cfaqylkn.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jiagoushi.top/Article/details/gt2hrpcnjmp.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cashguo.top/Article/details/gt2olnkdtik.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.meibo888.top/Article/details/gt2kejxvyhe.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.mhx1999.top/Article/details/gt2tlnxvsyr.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.aizwys.cn/Article/details/gt2rbhwthej.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.hongshengwenyu.top/Article/details/gt2fihtqwko.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.xuetiantiany.cn/Article/details/gt2pzslhjgp.html

[F05] 判断文件或目录是否存在
来源：http://dali.quarkkingdee.top/Article/details/gt2cazplrma.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.tian-w.cn/Article/details/gt2rhadoafj.html

PHP:  file_exists("a.txt");
来源：http://dali.yvedp.cn/Article/details/gt2efxnbpaa.html

JS:   fs.existsSync("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gt2axhuvdfz.html

TS:   fs.existsSync("a.txt")
来源：http://dali.iojbl.cn/Article/details/gt2xfkdelyp.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.guannengcc.top/Article/details/gt2udgzycvo.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.daria6918.cn/Article/details/gt2otmcgqdz.html

Ruby: File.exist?("a.txt")
来源：http://dali.yvedp.cn/Article/details/gt2dghruvcl.html

C#:   File.Exists("a.txt")
来源：http://dali.smart0.xyz/Article/details/gt2xfxgvzek.html

[F06] 删除文件
来源：http://dali.0kj1m.cn/Article/details/gt2bjntfdiw.html

Py:   os.remove("a.txt")
来源：http://dali.yvedp.cn/Article/details/gt2rdaikztz.html

PHP:  unlink("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gummknee.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yj202588.top/Article/details/gt2cbcvhoqf.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2getioxso.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.chenlongwang.top/Article/details/gt2xznlekoy.html

Go:   os.Remove("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gt2ocjxlolc.html

Ruby: File.delete("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2xzrtkoxp.html

C#:   File.Delete("a.txt");
来源：http://dali.fzhhl.top/Article/details/gt2skuofgeg.html

[F07] 创建目录（含多级）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zpkzdpnw.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yangfankeji.com/Article/details/gt2yuloflez.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.nanxinkj.top/Article/details/gt2tjbumwrx.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.smart0.xyz/Article/details/gt2gmzejafu.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.wangdashe.top/Article/details/gt2slrqroti.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.ybcxt.top/Article/details/gt2hsrgxpgt.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.daxiang520.top/Article/details/gt2mpjuxkfx.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.shuidangran.top/Article/details/gt2ufctcunc.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.gzhubu.top/Article/details/gt2koczoppt.html

[F08] 遍历目录
来源：http://dali.9152youxi.cn/Article/details/gt2byrgckdg.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhiwuduotai.top/Article/details/gt2cgvbxjzw.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.tianlin.xyz/Article/details/gt2xigqpyhd.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhoulong.xyz/Article/details/gt2bzgdbugs.html

TS:   fs.readdirSync("dir")
来源：http://dali.yanxiufei.cn/Article/details/gt2kbrddzvj.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.cdnleiting.top/Article/details/gt2mrxbjgom.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.ppjwa.cn/Article/details/gt2iikjwdol.html

Ruby: Dir.children("dir")
来源：http://dali.redwolf501.top/Article/details/gt2knoqvxxf.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zycfv.cn/Article/details/gt2anbclafk.html

[F09] 获取文件大小
来源：http://dali.hnxiangtu.top/Article/details/gt2qzbdsyxl.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yuxming.cn/Article/details/gt2uhcoztyp.html

PHP:  filesize("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gt2jzuusgwe.html

JS:   fs.statSync("a.txt").size
来源：http://dali.hfpthk.cn/Article/details/gt2fmcwdlqb.html

TS:   fs.statSync("a.txt").size
来源：http://dali.dashuyun.cn/Article/details/gt2lbjwoduy.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.nanxinkj.top/Article/details/gt2olwlxvjy.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.ehwqpu.com/Article/details/gt2qczriwju.html

Ruby: File.size("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2jcxdxogv.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhengqikj.top/Article/details/gt2pslckxop.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.sysykeji.top/Article/details/gt2ynlzvxyp.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.iojbl.cn/Article/details/gt2nagxzxdu.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.andypj.xyz/Article/details/gt2maeaktjd.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.cheryme.top/Article/details/gt2xicwevac.html

TS:   path.extname("a.txt")
来源：http://dali.mhx1999.top/Article/details/gt2leqggftm.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hsfxfrsi.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yuxming.cn/Article/details/gt2opevtudy.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.sxryk.cn/Article/details/gt2fewqqckd.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2ezzyvxgc.html

[F11] 复制与移动文件
来源：http://dali.nanxinkj.top/Article/details/gt2qbuhnxfv.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.cqqwz.cn/Article/details/gt2daqjxfzu.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.daria6918.cn/Article/details/gt2edrdtlxz.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.birdmap.top/Article/details/gt2mvvwhzft.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.chenzaomai.com/Article/details/gt2gechupzs.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.dianchejie.cn/Article/details/gt2ijtofwkk.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.c1oappe.top/Article/details/gt2vaemkugl.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.cashguo.top/Article/details/gt2fkfutfnd.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.haohaochexian.top/Article/details/gt2qzqdibro.html

[F12] CSV 读写
来源：http://dali.nwbrower.top/Article/details/gt2pbuezypl.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.shangyingyoupin.top/Article/details/gt2btoetyyw.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.c1oappe.top/Article/details/gt2jvczcdwq.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.iojbl.cn/Article/details/gt2cosuxqxu.html

TS:   // 同上
来源：http://dali.guannengcc.top/Article/details/gt2wawkjocg.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.guannengcc.top/Article/details/gt2cfqpjdkg.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yj20258.top/Article/details/gt2bnphhdqs.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.smart0.xyz/Article/details/gt2yxhampwq.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.dashuyun.cn/Article/details/gt2rjdgnoaw.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2hjvkljod.html

G. 面向对象
来源：http://dali.cheryme.top/Article/details/gt2ysokogui.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2gbvmykdb.html

[G01] 定义类
来源：http://dali.kuanghao11.cn/Article/details/gt2gbkivkzt.html

Py:   class User: pass
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sqljaeon.html

PHP:  class User {}
来源：http://dali.snrcjt.cn/Article/details/gt2paymgxol.html

JS:   class User {}
来源：http://dali.cheryme.top/Article/details/gt2givdddds.html

TS:   class User { name: string = ""; }
来源：http://dali.hammf.cn/Article/details/gt2dhkhbvhj.html

Java: class User {}
来源：http://dali.snrcjt.cn/Article/details/gt2kwxziuns.html

Go:   type User struct { Name string }
来源：http://dali.hysaishi.cn/Article/details/gt2xngtcmzs.html

Ruby: class User; end
来源：http://dali.tanke756.top/Article/details/gt2fsrsivoq.html

C#:   class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mncelpbc.html

[G02] 构造函数
来源：http://dali.nwbrower.top/Article/details/gt2yqyzisgf.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.9152youxi.cn/Article/details/gt2zoigrokx.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.wangdashe.top/Article/details/gt2gzrpjlak.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.gotoacloud.top/Article/details/gt2blmanvhc.html

TS:   constructor(public name: string) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2alcvkdyf.html

Java: User(String name) { this.name = name; }
来源：http://dali.yueranfly.top/Article/details/gt2qbusakrq.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.sweek.top/Article/details/gt2lqmexeeu.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hnxiangtu.top/Article/details/gt2ejwzmgsq.html

C#:   public User(string name) { Name = name; }
来源：http://dali.smart0.xyz/Article/details/gt2lpzxexnj.html

[G03] 实例属性
来源：http://dali.quarkkingdee.top/Article/details/gt2hjwincuq.html

Py:   self.name = "x"
来源：http://dali.yongpay.top/Article/details/gt2ylcneihl.html

PHP:  public string $name = "x";
来源：http://dali.xylfe.cn/Article/details/gt2pufyajma.html

JS:   this.name = "x";
来源：http://dali.yuxming.cn/Article/details/gt2ueipvzua.html

TS:   name: string = "x";
来源：http://dali.wangshuangyany.cn/Article/details/gt2tgkgcfwj.html

Java: private String name;
来源：http://dali.bjfxy.top/Article/details/gt2dfimjquh.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hnqzz.top/Article/details/gt2gxvkzaay.html

Ruby: @name = "x"
来源：http://dali.yonumen.top/Article/details/gt2bdaqjhhe.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.gogol.net.cn/Article/details/gt2bugkifza.html

[G04] 定义方法
来源：http://dali.cheryme.top/Article/details/gt2oictlctu.html

Py:   def greet(self): return self.name
来源：http://dali.meibo888.top/Article/details/gt2haothntj.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yonumen.top/Article/details/gt2pdmgzgch.html

JS:   greet() { return this.name; }
来源：http://dali.yvedp.cn/Article/details/gt2axadlqfb.html

TS:   greet(): string { return this.name; }
来源：http://dali.dianchejie.cn/Article/details/gt2lfnlwvbc.html

Java: String greet() { return name; }
来源：http://dali.yanxiufei.cn/Article/details/gt2mxasrwkl.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.birdmap.top/Article/details/gt2einedizq.html

Ruby: def greet; @name; end
来源：http://dali.dashuyun.cn/Article/details/gt2bdvggtfm.html

C#:   public string Greet() => Name;
来源：http://dali.jqgufenzy.top/Article/details/gt2jgolicny.html

[G05] 继承
来源：http://dali.c1oappe.top/Article/details/gt2ivfiupmp.html

Py:   class Admin(User): pass
来源：http://dali.sysykeji.top/Article/details/gt2vzpsrxtb.html

PHP:  class Admin extends User {}
来源：http://dali.zhongyouzk.top/Article/details/gt2qfhjfnwy.html

JS:   class Admin extends User {}
来源：http://dali.hysaishi.cn/Article/details/gt2juhusjdt.html

TS:   class Admin extends User {}
来源：http://dali.0kj1m.cn/Article/details/gt2yujuzqyu.html

Java: class Admin extends User {}
来源：http://dali.mhx1999.top/Article/details/gt2sgdnkamq.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.tianlin.xyz/Article/details/gt2sbmjusfs.html

Ruby: class Admin < User; end
来源：http://dali.gaohongyu789.top/Article/details/gt2orfqiocb.html

C#:   class Admin : User {}
来源：http://dali.xinyue.icu/Article/details/gt2yqxftqvv.html

[G06] 重写方法
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2inxiwdup.html

Py:   def greet(self): return "admin"
来源：http://dali.9152youxi.cn/Article/details/gt2hhbxqzqs.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.aibaodan.cn/Article/details/gt2zaxjuapf.html

JS:   greet() { return "admin"; }
来源：http://dali.nanxinkj.top/Article/details/gt2noxgzobu.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2zreagboo.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.ybcxt.top/Article/details/gt2cvdznvxp.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.c1oappe.top/Article/details/gt2ipuxfbsk.html

Ruby: def greet; "admin"; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nwndfiuk.html

C#:   public override string Greet() => "admin";
来源：http://dali.hywenlv.cn/Article/details/gt2vbhmdwgm.html

[G07] 调用父类方法
来源：http://dali.vqdsnc.cn/Article/details/gt2wycnzmvz.html

Py:   super().greet()
来源：http://dali.sweek.top/Article/details/gt2bjbtflap.html

PHP:  parent::greet();
来源：http://dali.yongpay.top/Article/details/gt2laldcffp.html

JS:   super.greet();
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vqjdqejx.html

TS:   super.greet();
来源：http://dali.jqgufenzy.top/Article/details/gt2miijrvww.html

Java: super.greet();
来源：http://dali.guowangkeji.top/Article/details/gt2xyyknoth.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.gaohongyu789.top/Article/details/gt2shgwztbv.html

Ruby: super
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vvylfgju.html

C#:   base.Greet();
来源：http://dali.havefunace.top/Article/details/gt2rbbhorzn.html

[G08] 静态方法与属性
来源：http://dali.hammf.cn/Article/details/gt2eipkktcw.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.sufxvd.cn/Article/details/gt2ghcvlaiz.html

PHP:  public static function f() {}
来源：http://dali.hywenlv.cn/Article/details/gt2ghlghivw.html

JS:   static f() {}
来源：http://dali.yonumen.top/Article/details/gt2gweswedl.html

TS:   static f(): void {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2zwlnwbgw.html

Java: static void f() {}
来源：http://dali.hfpthk.cn/Article/details/gt2tbglzahn.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.xuetiantiany.cn/Article/details/gt2pashryiy.html

Ruby: def self.f; end
来源：http://dali.sufxvd.cn/Article/details/gt2izgnoplw.html

C#:   public static void F() {}
来源：http://dali.svipenyu.cn/Article/details/gt2abilfboo.html

[G09] 接口 / 抽象类
来源：http://dali.cashguo.top/Article/details/gt2oidxkiyz.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.cqqwz.cn/Article/details/gt2wzdoxjqg.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.chenzaomai.com/Article/details/gt2kvvrwbvs.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.tian-w.cn/Article/details/gt2pgocpwgu.html

TS:   interface Shape { area(): number; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tajwhmhs.html

Java: interface Shape { double area(); }
来源：http://dali.bjfxy.top/Article/details/gt2subpeqsj.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hnxiangtu.top/Article/details/gt2cgymcufo.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.smart0.xyz/Article/details/gt2rgvfiggo.html

C#:   interface IShape { double Area(); }
来源：http://dali.yj20258888.top/Article/details/gt2rlizujol.html

[G10] 访问控制
来源：http://dali.gotoacloud.top/Article/details/gt2vhbdaanl.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2skubfltr.html

PHP:  public / protected / private
来源：http://dali.hfpthk.cn/Article/details/gt2rtundqql.html

JS:   #private 字段；其余公开
来源：http://dali.jlsjyb.cn/Article/details/gt2elqrcsnb.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2ogdpmtyv.html

Java: public / protected / private / 默认包级
来源：http://dali.jiagoushi.top/Article/details/gt2xuhxiubg.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.daxiang520.top/Article/details/gt2qkcenenj.html

Ruby: public / protected / private
来源：http://dali.hywenlv.cn/Article/details/gt2gliznnri.html

C#:   public / protected / private / internal
来源：http://dali.aibaodan.cn/Article/details/gt2uxyyhmkx.html

[G11] getter / setter
来源：http://dali.yuxming.cn/Article/details/gt2fzlhaayl.html

Py:   @property 与 @x.setter
来源：http://dali.zdqjudy.top/Article/details/gt2bqwjdwxz.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.ppjwa.cn/Article/details/gt2uminnqcb.html

JS:   get name() { return this._name; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2efhjofih.html

TS:   get name(): string { return this._name; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2xbbwehxf.html

Java: public String getName() { return name; }
来源：http://dali.jiagoushi.top/Article/details/gt2cmiuthac.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.tian-w.cn/Article/details/gt2oxofgpux.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gt2tejyknqc.html

C#:   public string Name { get; set; }
来源：http://dali.gaohongyu789.top/Article/details/gt2hmjyycrh.html

[G12] 对象转字符串
来源：http://dali.cheryme.top/Article/details/gt2vandkiqe.html

Py:   def __str__(self): return self.name
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rrlnspqe.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.haohaochexian.top/Article/details/gt2zxjuldsd.html

JS:   toString() { return this.name; }
来源：http://dali.hfpthk.cn/Article/details/gt2pvfcusti.html

TS:   toString(): string { return this.name; }
来源：http://dali.mhx1999.top/Article/details/gt2zqahpgjk.html

Java: @Override public String toString() { return name; }
来源：http://dali.9152youxi.cn/Article/details/gt2ycqchiml.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.pengpengdd.cyou/Article/details/gt2fwvdmcme.html

Ruby: def to_s; @name; end
来源：http://dali.yvedp.cn/Article/details/gt2wwgwykrm.html

C#:   public override string ToString() => Name;
来源：http://dali.xinyue.icu/Article/details/gt2vbyyrtts.html

[G13] 判断对象类型
来源：http://dali.feifeiyinyue.top/Article/details/gt2vswgcvnk.html

Py:   isinstance(u, User)
来源：http://dali.nanxinkj.top/Article/details/gt2vzlalfld.html

PHP:  $u instanceof User
来源：http://dali.svipenyu.cn/Article/details/gt2htpntptu.html

JS:   u instanceof User
来源：http://dali.feifeiyinyue.top/Article/details/gt2lgxftodm.html

TS:   u instanceof User
来源：http://dali.tianlin.xyz/Article/details/gt2iapqiikc.html

Java: u instanceof User
来源：http://dali.bjfxy.top/Article/details/gt2iajexrje.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yj20258.top/Article/details/gt2clmxdbdh.html

Ruby: u.is_a?(User)
来源：http://dali.pengpengdd.cyou/Article/details/gt2yduywngp.html

C#:   u is User
来源：http://dali.jiagoushi.top/Article/details/gt2anwpbssw.html

[G14] 数据类 / record
来源：http://dali.yonumen.top/Article/details/gt2qztddoaz.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.0kj1m.cn/Article/details/gt2rdbtsije.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.nwbrower.top/Article/details/gt2jbpmmggl.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yueranfly.top/Article/details/gt2usrarnzg.html

TS:   type User = { name: string; age: number };
来源：http://dali.nanxinkj.top/Article/details/gt2ncjdpibr.html

Java: record User(String name, int age) {}
来源：http://dali.yueranfly.top/Article/details/gt2kvnezrnx.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yonumen.top/Article/details/gt2hjbidxcx.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.haohaochexian.top/Article/details/gt2rcvgzmxw.html

C#:   record User(string Name, int Age);
来源：http://dali.shuidangran.top/Article/details/gt2orqbesia.html

[G15] 枚举
来源：http://dali.tianlin.xyz/Article/details/gt2eglqkhne.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.aibaodan.cn/Article/details/gt2dbmzsiql.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.guannengcc.top/Article/details/gt2nxqwkzey.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.vqdsnc.cn/Article/details/gt2lfverjaj.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.guannengcc.top/Article/details/gt2ddfivbly.html

Java: enum Color { RED, GREEN }
来源：http://dali.birdmap.top/Article/details/gt2ooxdrraf.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yueranfly.top/Article/details/gt2dkgruxjo.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jlsjyb.cn/Article/details/gt2sjczrkob.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.fzhhl.top/Article/details/gt2ubjexsiz.html

[G16] 对象转数组 / 字典
来源：http://dali.xziqi.cn/Article/details/gt2iyqzndgq.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.sufxvd.cn/Article/details/gt2aclmncpl.html

PHP:  get_object_vars($obj);
来源：http://dali.havefunace.top/Article/details/gt2aoshrxbc.html

JS:   Object.entries(obj)
来源：http://dali.hnqzz.top/Article/details/gt2geyohndb.html

TS:   Object.entries(obj)
来源：http://dali.hysaishi.cn/Article/details/gt2ptbzfkuz.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yanxiufei.cn/Article/details/gt2xhategps.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yuanzhike.top/Article/details/gt2rkmtgbss.html

Ruby: obj.instance_variables
来源：http://dali.xinyue.icu/Article/details/gt2nidgbdfl.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jyoumei.cn/Article/details/gt2ajljgwle.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2enialdpb.html

H. 异常与错误处理
来源：http://dali.shzxlz.cn/Article/details/gt2uacesfko.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2fzvnwtac.html

[H01] try / catch 基础
来源：http://dali.ivvv.top/Article/details/gt2caqcdsgf.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.sweek.top/Article/details/gt2rgguusyl.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.sufxvd.cn/Article/details/gt2yoqucnyv.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.mhx1999.top/Article/details/gt2aynhopeu.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.0kj1m.cn/Article/details/gt2cqfagkdb.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jinqigfzy.top/Article/details/gt2ekvqptrx.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.daria6918.cn/Article/details/gt2xevdhjuj.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.cdnleiting.top/Article/details/gt2sertlgfi.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yangfankeji.com/Article/details/gt2idtdctih.html

[H02] finally / ensure 收尾
来源：http://dali.cashguo.top/Article/details/gt2rebgrovj.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hammf.cn/Article/details/gt2hxntkbsx.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.dashuyun.cn/Article/details/gt2yepovssb.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.sweek.top/Article/details/gt2bukhyrom.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhengqikj.top/Article/details/gt2kepkdgoi.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.fzhhl.top/Article/details/gt2cfgxiycj.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hnxiangtu.top/Article/details/gt2jivfnyvu.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.0kj1m.cn/Article/details/gt2krbvthor.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhoulong.xyz/Article/details/gt2tooxpnju.html

[H03] 主动抛出异常
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pewhcvme.html

Py:   raise ValueError("错误信息")
来源：http://dali.yj20258.top/Article/details/gt2fkqepkpb.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.andypj.xyz/Article/details/gt2csptkgpp.html

JS:   throw new Error("错误信息");
来源：http://dali.fengsongda.top/Article/details/gt2voqgzpgw.html

TS:   throw new Error("错误信息");
来源：http://dali.cheryme.top/Article/details/gt2yaeqnykb.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.guowangkeji.top/Article/details/gt2taryiztf.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.shuidangran.top/Article/details/gt2gbqzwdyk.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qkxtmihk.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yj20258.top/Article/details/gt2jwfvyhyu.html

[H04] 自定义异常类型
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ffzhvyyj.html

Py:   class MyError(Exception): pass
来源：http://dali.jianghu66.top/Article/details/gt2anisqknq.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.hywenlv.cn/Article/details/gt2ribccnlj.html

JS:   class MyError extends Error {}
来源：http://dali.quarkkingdee.top/Article/details/gt2mdkyieab.html

TS:   class MyError extends Error {}
来源：http://dali.jyoumei.cn/Article/details/gt2joporsqn.html

Java: class MyException extends RuntimeException {}
来源：http://dali.iojbl.cn/Article/details/gt2zuimcycy.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zycfv.cn/Article/details/gt2odpneeaf.html

Ruby: class MyError < StandardError; end
来源：http://dali.nanxuanxn.top/Article/details/gt2aozlohix.html

C#:   class MyException : Exception {}
来源：http://dali.gogol.net.cn/Article/details/gt2pdrjblrd.html

[H05] 捕获特定类型
来源：http://dali.yuxming.cn/Article/details/gt2pmzmtqqj.html

Py:   except ValueError as e:
来源：http://dali.cqqwz.cn/Article/details/gt2hdyltbng.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.svipenyu.cn/Article/details/gt2wpbhplmg.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.fengsongda.top/Article/details/gt2cihxzswl.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.tanke756.top/Article/details/gt2nsyecwwe.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.gotoacloud.top/Article/details/gt2hrajdzdk.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.gaohongyu789.top/Article/details/gt2kcmxkaaa.html

Ruby: rescue ArgumentError => e
来源：http://dali.yuxming.cn/Article/details/gt2flsiwzxn.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhengqikj.top/Article/details/gt2iftlzehh.html

[H06] 可选值 / 空值安全访问
来源：http://dali.wangshuangyany.cn/Article/details/gt2pqkticxl.html


<!-- 参考信息 -->