代发 wailian999

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.316326.xyz/Article/details/gttbbnvhwt.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.aibaodan.cn/Article/details/gtzbhyxdyc.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.cdnleiting.top/Article/details/gtymmcowct.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.0kj1m.cn/Article/details/gtzgvxrhmm.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yonumen.top/Article/details/gtnafjqnwd.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.vqdsnc.cn/Article/details/gttjtmzyjt.html

[F03] 写入文件（覆盖）
来源：http://dali.tian-w.cn/Article/details/gttjiispea.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jianghu66.top/Article/details/gtkquvvtwf.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.ehwqpu.com/Article/details/gtbpjikuip.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtderkxstk.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gtjuhribus.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yuxming.cn/Article/details/gtlzbjempy.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.ybcxt.top/Article/details/gtcwgozgvv.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.hnxiangtu.top/Article/details/gtmftebzbd.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.sweek.top/Article/details/gthtjnlmua.html

[F04] 追加写入文件
来源：http://dali.hywenlv.cn/Article/details/gtguyzdzex.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.meibo888.top/Article/details/gtensfqlqe.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.hfpthk.cn/Article/details/gtjbmgjbas.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.aizwys.cn/Article/details/gthanywjft.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.nanxinkj.top/Article/details/gtmawcnyli.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.sufxvd.cn/Article/details/gtyreehgte.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.xylfe.cn/Article/details/gtskslojtq.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yj20258.top/Article/details/gtddhveypg.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.gotoacloud.top/Article/details/gtmckwqvlu.html

[F05] 判断文件或目录是否存在
来源：http://dali.havefunace.top/Article/details/gteomxgadk.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.sysykeji.top/Article/details/gtmlnzoonc.html

PHP:  file_exists("a.txt");
来源：http://dali.aibaodan.cn/Article/details/gtiufobvqp.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtrbugpvuj.html

TS:   fs.existsSync("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtqeccyedv.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jlsjyb.cn/Article/details/gtvhkqgtwh.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhengqikj.top/Article/details/gtvuqqnyhl.html

Ruby: File.exist?("a.txt")
来源：http://dali.tian-w.cn/Article/details/gtkaptmcxk.html

C#:   File.Exists("a.txt")
来源：http://dali.316326.xyz/Article/details/gtxmnsiwjq.html

[F06] 删除文件
来源：http://dali.shangyingyoupin.top/Article/details/gtryeouezz.html

Py:   os.remove("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtgyykpvuc.html

PHP:  unlink("a.txt");
来源：http://dali.snrcjt.cn/Article/details/gtsmjbqyfz.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.meibo888.top/Article/details/gtbzccohmg.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jianghu66.top/Article/details/gttazpofxi.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yj20258.top/Article/details/gttrinjypr.html

Go:   os.Remove("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtyibehrij.html

Ruby: File.delete("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gturcslwrp.html

C#:   File.Delete("a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gtlngujvgb.html

[F07] 创建目录（含多级）
来源：http://dali.316326.xyz/Article/details/gtotluarly.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.iojbl.cn/Article/details/gtjkblfciz.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hysaishi.cn/Article/details/gtqntsqssh.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinqigfzy.top/Article/details/gtlkczsbma.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sysykeji.top/Article/details/gtegeslfhr.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.smart0.xyz/Article/details/gtiyevltac.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jlsjyb.cn/Article/details/gtbtkcnlhl.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.ehwqpu.com/Article/details/gtbwcisadn.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.cashguo.top/Article/details/gtrhhpeott.html

[F08] 遍历目录
来源：http://dali.chenlongwang.top/Article/details/gtikleryot.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.shangyingyoupin.top/Article/details/gthagupayc.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.sxryk.cn/Article/details/gtimffeays.html

JS:   fs.readdirSync("dir")
来源：http://dali.sxryk.cn/Article/details/gtnznuvslb.html

TS:   fs.readdirSync("dir")
来源：http://dali.jinqigfzy.top/Article/details/gttvgydlui.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yanxiufei.cn/Article/details/gtqspdtquc.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.nwbrower.top/Article/details/gtmlmarqqr.html

Ruby: Dir.children("dir")
来源：http://dali.kuanghao11.cn/Article/details/gtzycpohej.html

C#:   Directory.GetFiles("dir")
来源：http://dali.wangdashe.top/Article/details/gtufmsjnnc.html

[F09] 获取文件大小
来源：http://dali.gaohongyu789.top/Article/details/gtaflqiuyb.html

Py:   os.path.getsize("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtazwuwywc.html

PHP:  filesize("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gtqfyrufab.html

JS:   fs.statSync("a.txt").size
来源：http://dali.cqqwz.cn/Article/details/gtfwkpovfd.html

TS:   fs.statSync("a.txt").size
来源：http://dali.tanke756.top/Article/details/gtpecdfulc.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.ydzc1.top/Article/details/gtrmetzcxy.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yuxming.cn/Article/details/gtnjjtjxra.html

Ruby: File.size("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtsacqxqlp.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.shuidangran.top/Article/details/gtsljdbewc.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yvedp.cn/Article/details/gtdrwhlmlf.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.sxryk.cn/Article/details/gtknzorcpf.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yj202588.top/Article/details/gtqdsxyqcq.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtgkpfzjss.html

TS:   path.extname("a.txt")
来源：http://dali.yj202588.top/Article/details/gtvpueazgh.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jqgufenzy.top/Article/details/gtozjlpglb.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtsyyjypzt.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtowrglmly.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtcodqzuka.html

[F11] 复制与移动文件
来源：http://dali.guowangkeji.top/Article/details/gtbtfvbzxl.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtovnyoian.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.bjfxy.top/Article/details/gthbdonzwn.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtkpzlsebv.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtwhtcqxgx.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.tanke756.top/Article/details/gtnzycwdnc.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.cashguo.top/Article/details/gtgzjvsuqq.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtrxceqduw.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.tanke756.top/Article/details/gtlhzgyccp.html

[F12] CSV 读写
来源：http://dali.zhongyouzk.top/Article/details/gtjqrqzaii.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.xinyue.icu/Article/details/gtgazhpgta.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.dianchejie.cn/Article/details/gtjzwijzkw.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.316326.xyz/Article/details/gtysrzvwhn.html

TS:   // 同上
来源：http://dali.ybcxt.top/Article/details/gtieaehsje.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jqgfzy.top/Article/details/gtawxdwzth.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yj20258888.top/Article/details/gttdkcwrch.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yongpay.top/Article/details/gtdmnzfngw.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.gaohongyu789.top/Article/details/gtvceniikr.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtffthdxzu.html

G. 面向对象
来源：http://dali.fzhhl.top/Article/details/gttriznujs.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtznfrogqy.html

[G01] 定义类
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdahtensb.html

Py:   class User: pass
来源：http://dali.ydzc1.top/Article/details/gtljezrmbj.html

PHP:  class User {}
来源：http://dali.shuidangran.top/Article/details/gtggomunbg.html

JS:   class User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmxdcgjyq.html

TS:   class User { name: string = ""; }
来源：http://dali.jqgfzy.top/Article/details/gtgmxmuxqv.html

Java: class User {}
来源：http://dali.quarkkingdee.top/Article/details/gttrkzqcdj.html

Go:   type User struct { Name string }
来源：http://dali.jyoumei.cn/Article/details/gtgefrfjrj.html

Ruby: class User; end
来源：http://dali.yuanzhike.top/Article/details/gteqrilugk.html

C#:   class User {}
来源：http://dali.nwbrower.top/Article/details/gtsuudtkrw.html

[G02] 构造函数
来源：http://dali.jinqigfzy.top/Article/details/gtwcsfxfxt.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.dianchejie.cn/Article/details/gtkztxtqjr.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.shuidangran.top/Article/details/gtpligxslj.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.hywenlv.cn/Article/details/gtjppfscbl.html

TS:   constructor(public name: string) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtefppjskn.html

Java: User(String name) { this.name = name; }
来源：http://dali.xuanzx.com/Article/details/gtnivvwvfw.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.guannengcc.top/Article/details/gtyznwwpkk.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.cashguo.top/Article/details/gtomioffph.html

C#:   public User(string name) { Name = name; }
来源：http://dali.9152youxi.cn/Article/details/gtbrrumkxy.html

[G03] 实例属性
来源：http://dali.sysykeji.top/Article/details/gtlzskgzby.html

Py:   self.name = "x"
来源：http://dali.hywenlv.cn/Article/details/gtmcygkeeu.html

PHP:  public string $name = "x";
来源：http://dali.jqgfzy.top/Article/details/gtotjmobeg.html

JS:   this.name = "x";
来源：http://dali.havefunace.top/Article/details/gtkvivfnep.html

TS:   name: string = "x";
来源：http://dali.birdmap.top/Article/details/gtukheuvlc.html

Java: private String name;
来源：http://dali.wangshuangyany.cn/Article/details/gtoxsqaqnh.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.cashguo.top/Article/details/gtnidhkovx.html

Ruby: @name = "x"
来源：http://dali.ywan-chungtsiang.top/Article/details/gttwqqkkvx.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.andypj.xyz/Article/details/gtmpokcwiw.html

[G04] 定义方法
来源：http://dali.birdmap.top/Article/details/gtzacemato.html

Py:   def greet(self): return self.name
来源：http://dali.aizwys.cn/Article/details/gtewtwgnkc.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.cqqwz.cn/Article/details/gtftfepnxp.html

JS:   greet() { return this.name; }
来源：http://dali.fzhhl.top/Article/details/gtgyodgosh.html

TS:   greet(): string { return this.name; }
来源：http://dali.hysaishi.cn/Article/details/gtviwhthdq.html

Java: String greet() { return name; }
来源：http://dali.sysykeji.top/Article/details/gtpaceoddq.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.meibo888.top/Article/details/gtuljqqjqo.html

Ruby: def greet; @name; end
来源：http://dali.yvedp.cn/Article/details/gthyxcxrjs.html

C#:   public string Greet() => Name;
来源：http://dali.xinyue.icu/Article/details/gtzxqzqojv.html

[G05] 继承
来源：http://dali.dianchejie.cn/Article/details/gtoqylwlrl.html

Py:   class Admin(User): pass
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnrdbxexb.html

PHP:  class Admin extends User {}
来源：http://dali.zhixingplan.top/Article/details/gtxsonxbfa.html

JS:   class Admin extends User {}
来源：http://dali.ppjwa.cn/Article/details/gtcuvgrujl.html

TS:   class Admin extends User {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtliyglvez.html

Java: class Admin extends User {}
来源：http://dali.cqqwz.cn/Article/details/gtrhwvxlef.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.gogol.net.cn/Article/details/gtnydugdxb.html

Ruby: class Admin < User; end
来源：http://dali.aibaodan.cn/Article/details/gtbmlstqua.html

C#:   class Admin : User {}
来源：http://dali.smart0.xyz/Article/details/gtbuohkrpl.html

[G06] 重写方法
来源：http://dali.xziqi.cn/Article/details/gtkejcsvez.html

Py:   def greet(self): return "admin"
来源：http://dali.birdmap.top/Article/details/gttyqgddtd.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.tianlin.xyz/Article/details/gtkwikjund.html

JS:   greet() { return "admin"; }
来源：http://dali.tianlin.xyz/Article/details/gtranzenbv.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtbakisagp.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.316326.xyz/Article/details/gtjuzgebkh.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhiwuduotai.top/Article/details/gttsqogqtp.html

Ruby: def greet; "admin"; end
来源：http://dali.cheryme.top/Article/details/gtqpalxuyb.html

C#:   public override string Greet() => "admin";
来源：http://dali.nanxinkj.top/Article/details/gtfhaqatqg.html

[G07] 调用父类方法
来源：http://dali.jianghu66.top/Article/details/gttvzgpjmn.html

Py:   super().greet()
来源：http://dali.pycfn.com/Article/details/gtwemhenia.html

PHP:  parent::greet();
来源：http://dali.9152youxi.cn/Article/details/gtkmdjpcpw.html

JS:   super.greet();
来源：http://dali.316326.xyz/Article/details/gtubdggtru.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gtmzcwdctf.html

Java: super.greet();
来源：http://dali.jinqigfzy.top/Article/details/gtksqivdrt.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.aizwys.cn/Article/details/gtnmjelbvf.html

Ruby: super
来源：http://dali.xziqi.cn/Article/details/gtmiraxsut.html

C#:   base.Greet();
来源：http://dali.smart0.xyz/Article/details/gtavdujgap.html

[G08] 静态方法与属性
来源：http://dali.fzhhl.top/Article/details/gtmydlufgx.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.redwolf501.top/Article/details/gtiiwttiyj.html

PHP:  public static function f() {}
来源：http://dali.gzhubu.top/Article/details/gtiajzmvmd.html

JS:   static f() {}
来源：http://dali.wangdashe.top/Article/details/gtapcayrrz.html

TS:   static f(): void {}
来源：http://dali.ehwqpu.com/Article/details/gtysrjzuks.html

Java: static void f() {}
来源：http://dali.yueranfly.top/Article/details/gtluamvrby.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.sufxvd.cn/Article/details/gtnmepwbpu.html

Ruby: def self.f; end
来源：http://dali.mhx1999.top/Article/details/gtciowkvei.html

C#:   public static void F() {}
来源：http://dali.havefunace.top/Article/details/gtscxlwota.html

[G09] 接口 / 抽象类
来源：http://dali.sysykeji.top/Article/details/gtsgozrfwt.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.svipenyu.cn/Article/details/gtwapglgzj.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.tian-w.cn/Article/details/gteekexsib.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.gotoacloud.top/Article/details/gtwbrfidyb.html

TS:   interface Shape { area(): number; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfrvwbfes.html

Java: interface Shape { double area(); }
来源：http://dali.jqgufenzy.top/Article/details/gtevfzquqs.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.gzhubu.top/Article/details/gtybfjhhag.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gtntobmyoa.html

C#:   interface IShape { double Area(); }
来源：http://dali.xinyue.icu/Article/details/gthlrvmpfr.html

[G10] 访问控制
来源：http://dali.ivvv.top/Article/details/gtsbdivurz.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.havefunace.top/Article/details/gtgyqytphu.html

PHP:  public / protected / private
来源：http://dali.snrcjt.cn/Article/details/gtyheptwfo.html

JS:   #private 字段；其余公开
来源：http://dali.yj202588.top/Article/details/gtgfvhczjl.html

TS:   public / protected / private
来源：http://dali.ehwqpu.com/Article/details/gtxedknkwb.html

Java: public / protected / private / 默认包级
来源：http://dali.cdnleiting.top/Article/details/gtgsnvtopf.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.havefunace.top/Article/details/gtlndxauut.html

Ruby: public / protected / private
来源：http://dali.fengsongda.top/Article/details/gtwuobykxt.html

C#:   public / protected / private / internal
来源：http://dali.jqgufenzy.top/Article/details/gtdxmwkkwj.html

[G11] getter / setter
来源：http://dali.gaohongyu789.top/Article/details/gtsrytvqfd.html

Py:   @property 与 @x.setter
来源：http://dali.gotoacloud.top/Article/details/gtawgjyzhf.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.havefunace.top/Article/details/gtnvgmjavm.html

JS:   get name() { return this._name; }
来源：http://dali.xuanzx.com/Article/details/gtyuedzttz.html

TS:   get name(): string { return this._name; }
来源：http://dali.xylfe.cn/Article/details/gtekxicdfx.html

Java: public String getName() { return name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtjvcajndf.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jyoumei.cn/Article/details/gtzwixfoah.html

Ruby: attr_accessor :name
来源：http://dali.9152youxi.cn/Article/details/gtgxlxesog.html

C#:   public string Name { get; set; }
来源：http://dali.cdnleiting.top/Article/details/gtwviyhqbs.html

[G12] 对象转字符串
来源：http://dali.smart0.xyz/Article/details/gtkabqfbkk.html

Py:   def __str__(self): return self.name
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdwayuvpg.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.daxiang520.top/Article/details/gtchyudetg.html

JS:   toString() { return this.name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgigqidqp.html

TS:   toString(): string { return this.name; }
来源：http://dali.svipenyu.cn/Article/details/gtuhoqygzi.html

Java: @Override public String toString() { return name; }
来源：http://dali.pycfn.com/Article/details/gtdoevqtpb.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.haohaochexian.top/Article/details/gtggxiuevk.html

Ruby: def to_s; @name; end
来源：http://dali.yuxming.cn/Article/details/gtkjmvbifx.html

C#:   public override string ToString() => Name;
来源：http://dali.birdmap.top/Article/details/gtzzciyevv.html

[G13] 判断对象类型
来源：http://dali.yuxming.cn/Article/details/gtlgzqesaj.html

Py:   isinstance(u, User)
来源：http://dali.xuetiantiany.cn/Article/details/gtrocokuxo.html

PHP:  $u instanceof User
来源：http://dali.gaohongyu789.top/Article/details/gthxndazai.html

JS:   u instanceof User
来源：http://dali.birdmap.top/Article/details/gttabztmeg.html

TS:   u instanceof User
来源：http://dali.jyoumei.cn/Article/details/gtikudwtno.html

Java: u instanceof User
来源：http://dali.tianlin.xyz/Article/details/gtgqaupnkc.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.cucudq.cn/Article/details/gtwflwangs.html

Ruby: u.is_a?(User)
来源：http://dali.daxiang520.top/Article/details/gtoquevdih.html

C#:   u is User
来源：http://dali.meibo888.top/Article/details/gtxjybrjmr.html

[G14] 数据类 / record
来源：http://dali.shuidangran.top/Article/details/gtobymmjhy.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jinqigufen.top/Article/details/gtfzugizfn.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.redwolf501.top/Article/details/gttanskhjr.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.gotoacloud.top/Article/details/gtmawgzqgn.html

TS:   type User = { name: string; age: number };
来源：http://dali.guowangkeji.top/Article/details/gttgkewizz.html

Java: record User(String name, int age) {}
来源：http://dali.gaohongyu789.top/Article/details/gthrzyhtih.html

Go:   type User struct { Name string; Age int }
来源：http://dali.cheryme.top/Article/details/gtwqmklwnw.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.xinyue.icu/Article/details/gtrinmzcty.html

C#:   record User(string Name, int Age);
来源：http://dali.pycfn.com/Article/details/gtvcvtpgtk.html

[G15] 枚举
来源：http://dali.jiagoushi.top/Article/details/gtdtwigmpv.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yvedp.cn/Article/details/gtlxuyvosu.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.dashuyun.cn/Article/details/gtwfemuees.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.shuidangran.top/Article/details/gtnohguztx.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.birdmap.top/Article/details/gtmepcofiu.html

Java: enum Color { RED, GREEN }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxxdbzcda.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jiagoushi.top/Article/details/gtdkkboapv.html

Ruby: Color = %i[red green].freeze
来源：http://dali.nwbrower.top/Article/details/gtegayuhtk.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ehwqpu.com/Article/details/gtuqmsynkz.html

[G16] 对象转数组 / 字典
来源：http://dali.yj20258.top/Article/details/gtfwqcysrz.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.iojbl.cn/Article/details/gtblwjrred.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gtkribvwvk.html

JS:   Object.entries(obj)
来源：http://dali.snrcjt.cn/Article/details/gtnabbqtrn.html

TS:   Object.entries(obj)
来源：http://dali.daria6918.cn/Article/details/gtqapvapyk.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.xziqi.cn/Article/details/gtscoaoecy.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.cashguo.top/Article/details/gtgkjgvera.html

Ruby: obj.instance_variables
来源：http://dali.jinqigfzy.top/Article/details/gtiuodblxn.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.tianlin.xyz/Article/details/gtojffzrng.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtingdblwd.html

H. 异常与错误处理
来源：http://dali.wangshuangyany.cn/Article/details/gtdqtfjnpk.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtabbnssut.html

[H01] try / catch 基础
来源：http://dali.hammf.cn/Article/details/gtrdsiakfw.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jianghu66.top/Article/details/gtlutkzspk.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yj20258888.top/Article/details/gtrcetbnyf.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hnqzz.top/Article/details/gtefylbdrp.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.316326.xyz/Article/details/gtbesfgxtj.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.daria6918.cn/Article/details/gtadtbdsxt.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.haohaochexian.top/Article/details/gtuzptbgem.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jlsjyb.cn/Article/details/gttiigafzp.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.mhx1999.top/Article/details/gtniycmhnx.html

[H02] finally / ensure 收尾
来源：http://dali.jinqigfzy.top/Article/details/gtngvpvneg.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.xylfe.cn/Article/details/gtwlzxlarp.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hywenlv.cn/Article/details/gtexgjhchw.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yj202588.top/Article/details/gthlcmiqgn.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.9152youxi.cn/Article/details/gtzedeonug.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.cqqwz.cn/Article/details/gtztkkgfpe.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hongshengwenyu.top/Article/details/gtavswnhnm.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.chenlongwang.top/Article/details/gtwxdnjipk.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.kuanghao11.cn/Article/details/gtozmmmsuo.html

[H03] 主动抛出异常
来源：http://dali.guannengcc.top/Article/details/gtffoatlcv.html

Py:   raise ValueError("错误信息")
来源：http://dali.fengsongda.top/Article/details/gtvrcyjxgk.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yonumen.top/Article/details/gtsnzeelic.html

JS:   throw new Error("错误信息");
来源：http://dali.jqgfzy.top/Article/details/gtajbyaleu.html

TS:   throw new Error("错误信息");
来源：http://dali.guowangkeji.top/Article/details/gtmezxnaii.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.guowangkeji.top/Article/details/gtvykdcghe.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.gotoacloud.top/Article/details/gtethutlsj.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jianghu66.top/Article/details/gtnimhryox.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.hysaishi.cn/Article/details/gtdhbhguci.html

[H04] 自定义异常类型
来源：http://dali.yj202588.top/Article/details/gtzigccwke.html

Py:   class MyError(Exception): pass
来源：http://dali.shzxlz.cn/Article/details/gtrvfrasak.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.tianlin.xyz/Article/details/gtdugxylcz.html

JS:   class MyError extends Error {}
来源：http://dali.iojbl.cn/Article/details/gthegacvxs.html

TS:   class MyError extends Error {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzacjicik.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yj202588.top/Article/details/gtkqxubdun.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.gotoacloud.top/Article/details/gtithsccvf.html

Ruby: class MyError < StandardError; end
来源：http://dali.jqgfzy.top/Article/details/gtnyhgxzaz.html

C#:   class MyException : Exception {}
来源：http://dali.tian-w.cn/Article/details/gtrgudiinl.html

[H05] 捕获特定类型
来源：http://dali.hongshengwenyu.top/Article/details/gtrsqwmbmu.html

Py:   except ValueError as e:
来源：http://dali.ppjwa.cn/Article/details/gtbenkeujw.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gtokyllxpf.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.gogol.net.cn/Article/details/gtlxpduqko.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.chenzaomai.com/Article/details/gtihhdrwbg.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.iojbl.cn/Article/details/gtmqkqhlfy.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.fengsongda.top/Article/details/gtxxtrcpbb.html

Ruby: rescue ArgumentError => e
来源：http://dali.smart0.xyz/Article/details/gtlgcfoltn.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zycfv.cn/Article/details/gtqasrcukb.html

[H06] 可选值 / 空值安全访问
来源：http://dali.hfpthk.cn/Article/details/gtuwkplgmv.html

Py:   value = d.get("k") or default
来源：http://dali.ehwqpu.com/Article/details/gtspnixkru.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.chenlongwang.top/Article/details/gtmvhqwxhh.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.mhx1999.top/Article/details/gtbvvirclf.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.shzxlz.cn/Article/details/gtikqhnaii.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.andypj.xyz/Article/details/gtfxqwluza.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.ybcxt.top/Article/details/gtzxihftgb.html

Ruby: d&.dig(:a, :b)
来源：http://dali.sxryk.cn/Article/details/gtgparqnfa.html

C#:   obj?.A?.B ?? default
来源：http://dali.cqqwz.cn/Article/details/gtevnelcoj.html


<!-- 参考信息 -->