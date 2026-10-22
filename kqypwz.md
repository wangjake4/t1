代发 wailian999

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jyoumei.cn/Article/details/gt2debhzjyt.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jqgufenzy.top/Article/details/gt2cgtobkkz.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhongyouzk.top/Article/details/gt2gdqtfaog.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hydexbol.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.svipenyu.cn/Article/details/gt2wgwqvnvh.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2fxrpwrno.html

[F03] 写入文件（覆盖）
来源：http://dali.svipenyu.cn/Article/details/gt2nfoiigcn.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yonumen.top/Article/details/gt2uzgdqvui.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.vqdsnc.cn/Article/details/gt2bbbcbves.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhengqikj.top/Article/details/gt2dclivjnd.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ydzc1.top/Article/details/gt2uxikkwbn.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2umeborss.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2egpuusaq.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhengqikj.top/Article/details/gt2isxyksto.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.wangdashe.top/Article/details/gt2srqgonhl.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pilqrhvq.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jinqigufen.top/Article/details/gt2ucrvyoer.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.ivvv.top/Article/details/gt2eqfvsofo.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.9152youxi.cn/Article/details/gt2jllgqucy.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hywenlv.cn/Article/details/gt2gfwycgne.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.daria6918.cn/Article/details/gt2cighngic.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.kuanghao11.cn/Article/details/gt2wufiejcc.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.redwolf501.top/Article/details/gt2qolmcxnl.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.iojbl.cn/Article/details/gt2gfjoclys.html

[F05] 判断文件或目录是否存在
来源：http://dali.sxryk.cn/Article/details/gt2wzituemv.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yueranfly.top/Article/details/gt2lejxxvpg.html

PHP:  file_exists("a.txt");
来源：http://dali.tanke756.top/Article/details/gt2kggqjhbe.html

JS:   fs.existsSync("a.txt")
来源：http://dali.gzhubu.top/Article/details/gt2voaonynl.html

TS:   fs.existsSync("a.txt")
来源：http://dali.fzhhl.top/Article/details/gt2gckxsqqt.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.redwolf501.top/Article/details/gt2gtqdtmms.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.chenzaomai.com/Article/details/gt2iajuvzmb.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gt2cwpxufkr.html

C#:   File.Exists("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gt2axjpalfa.html

[F06] 删除文件
来源：http://dali.iojbl.cn/Article/details/gt2ocqtxkff.html

Py:   os.remove("a.txt")
来源：http://dali.birdmap.top/Article/details/gt2nldmojpp.html

PHP:  unlink("a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gt2yebmebcv.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yonumen.top/Article/details/gt2uiciwjve.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2ihlsmzmi.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.shzxlz.cn/Article/details/gt2ywzzazgv.html

Go:   os.Remove("a.txt")
来源：http://dali.tian-w.cn/Article/details/gt2eaxiqetv.html

Ruby: File.delete("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2ffjnntpy.html

C#:   File.Delete("a.txt");
来源：http://dali.hfpthk.cn/Article/details/gt2tgavjcqy.html

[F07] 创建目录（含多级）
来源：http://dali.cashguo.top/Article/details/gt2yijtxekp.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.316326.xyz/Article/details/gt2ctydfmkj.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhixingplan.top/Article/details/gt2wumfemtd.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cheryme.top/Article/details/gt2myrkhgup.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gotoacloud.top/Article/details/gt2mpqrlyiq.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.shangyingyoupin.top/Article/details/gt2ctgivnfz.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.guowangkeji.top/Article/details/gt2zglankcv.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jinqigfzy.top/Article/details/gt2jviqtrke.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kitnsmpq.html

[F08] 遍历目录
来源：http://dali.fengsongda.top/Article/details/gt2tqeoyqxs.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.mhx1999.top/Article/details/gt2fjfboenj.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jinqigfzy.top/Article/details/gt2orfaxsvr.html

JS:   fs.readdirSync("dir")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wgekstkp.html

TS:   fs.readdirSync("dir")
来源：http://dali.9152youxi.cn/Article/details/gt2kwpezqmv.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhixingplan.top/Article/details/gt2avltbkjw.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.ppjwa.cn/Article/details/gt2uknimflp.html

Ruby: Dir.children("dir")
来源：http://dali.pengpengdd.cyou/Article/details/gt2khowukoc.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yvedp.cn/Article/details/gt2fdkgbqso.html

[F09] 获取文件大小
来源：http://dali.jqgfzy.top/Article/details/gt2mbcdvyji.html

Py:   os.path.getsize("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2xzrrwmzj.html

PHP:  filesize("a.txt");
来源：http://dali.daxiang520.top/Article/details/gt2dcyrtszn.html

JS:   fs.statSync("a.txt").size
来源：http://dali.sufxvd.cn/Article/details/gt2xlbujfvy.html

TS:   fs.statSync("a.txt").size
来源：http://dali.gzhubu.top/Article/details/gt2rytmyreo.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.c1oappe.top/Article/details/gt2hrwuimzx.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.xuanzx.com/Article/details/gt2zfkmslbg.html

Ruby: File.size("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gt2tcrshufr.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jgbihhqy.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.pycfn.com/Article/details/gt2ygkyaujb.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2dsvvsndi.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yuanzhike.top/Article/details/gt2lqmrbrbn.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.cheryme.top/Article/details/gt2ipyudzlb.html

TS:   path.extname("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gt2sarwppjg.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yanxiufei.cn/Article/details/gt2eaxwogii.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2bfemwkjj.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.sxryk.cn/Article/details/gt2igccaxwj.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zycfv.cn/Article/details/gt2nbbatwmv.html

[F11] 复制与移动文件
来源：http://dali.xuanzx.com/Article/details/gt2uackccei.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2bdcgyojj.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gt2dfajeoci.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yueranfly.top/Article/details/gt2lohizotr.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhongyouzk.top/Article/details/gt2rfvzgzvf.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.xuanzx.com/Article/details/gt2zvexflhr.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.havefunace.top/Article/details/gt2jqfiemtw.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hmavkjkf.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yangfankeji.com/Article/details/gt2sylrrhtk.html

[F12] CSV 读写
来源：http://dali.tian-w.cn/Article/details/gt2gtttohue.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.sweek.top/Article/details/gt2wnezwxel.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yuanzhike.top/Article/details/gt2hmbbnyuf.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.daxiang520.top/Article/details/gt2wueknbpg.html

TS:   // 同上
来源：http://dali.zhengqikj.top/Article/details/gt2zmbtagdk.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hammf.cn/Article/details/gt2clrrqlee.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jqgfzy.top/Article/details/gt2lybocrpm.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yongpay.top/Article/details/gt2qlevnpkc.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hongshengwenyu.top/Article/details/gt2zlfgpbey.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2hixppjmi.html

G. 面向对象
来源：http://dali.nanxuanxn.top/Article/details/gt2miukeuhq.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2fkwepaut.html

[G01] 定义类
来源：http://dali.guowangkeji.top/Article/details/gt2klhhtuiw.html

Py:   class User: pass
来源：http://dali.sweek.top/Article/details/gt2kvhrbwrp.html

PHP:  class User {}
来源：http://dali.yongpay.top/Article/details/gt2clhiboeu.html

JS:   class User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kxtqsowj.html

TS:   class User { name: string = ""; }
来源：http://dali.aibaodan.cn/Article/details/gt2tteagqeq.html

Java: class User {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2xfjidlji.html

Go:   type User struct { Name string }
来源：http://dali.gotoacloud.top/Article/details/gt2gxeqdmuz.html

Ruby: class User; end
来源：http://dali.aizwys.cn/Article/details/gt2uowlpjbj.html

C#:   class User {}
来源：http://dali.wangdashe.top/Article/details/gt2cfjnopvg.html

[G02] 构造函数
来源：http://dali.xziqi.cn/Article/details/gt2xgbgcink.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yvedp.cn/Article/details/gt2keoisnvb.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhongyouzk.top/Article/details/gt2pnlqkdwb.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.fzhhl.top/Article/details/gt2txowhkuk.html

TS:   constructor(public name: string) {}
来源：http://dali.tianlin.xyz/Article/details/gt2vmbldmvg.html

Java: User(String name) { this.name = name; }
来源：http://dali.yuxming.cn/Article/details/gt2hlrikenz.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.daria6918.cn/Article/details/gt2vjqotaxd.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.xuetiantiany.cn/Article/details/gt2umaaphtf.html

C#:   public User(string name) { Name = name; }
来源：http://dali.meibo888.top/Article/details/gt2qnxmvwip.html

[G03] 实例属性
来源：http://dali.tian-w.cn/Article/details/gt2dkodsepk.html

Py:   self.name = "x"
来源：http://dali.xuanzx.com/Article/details/gt2gcvjxxqk.html

PHP:  public string $name = "x";
来源：http://dali.vqdsnc.cn/Article/details/gt2ewhlqkoo.html

JS:   this.name = "x";
来源：http://dali.316326.xyz/Article/details/gt2askmlzoi.html

TS:   name: string = "x";
来源：http://dali.jinghuilouyu.cn/Article/details/gt2clsrlstf.html

Java: private String name;
来源：http://dali.sweek.top/Article/details/gt2jlysmtrh.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.shuidangran.top/Article/details/gt2ibflyvkr.html

Ruby: @name = "x"
来源：http://dali.jqgufenzy.top/Article/details/gt2binzqhuv.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yj20258888.top/Article/details/gt2smvjoted.html

[G04] 定义方法
来源：http://dali.yueranfly.top/Article/details/gt2cmmjcete.html

Py:   def greet(self): return self.name
来源：http://dali.shangyingyoupin.top/Article/details/gt2xioiarqs.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yangfankeji.com/Article/details/gt2wiiiltqx.html

JS:   greet() { return this.name; }
来源：http://dali.hywenlv.cn/Article/details/gt2qjudxuaq.html

TS:   greet(): string { return this.name; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2bmgzlhyy.html

Java: String greet() { return name; }
来源：http://dali.gogol.net.cn/Article/details/gt2ezvxowjy.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.ivvv.top/Article/details/gt2jmbixkof.html

Ruby: def greet; @name; end
来源：http://dali.xuetiantiany.cn/Article/details/gt2mxsytyek.html

C#:   public string Greet() => Name;
来源：http://dali.zhongyouzk.top/Article/details/gt2djwruait.html

[G05] 继承
来源：http://dali.hywenlv.cn/Article/details/gt2txfbxwze.html

Py:   class Admin(User): pass
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qeqnyaco.html

PHP:  class Admin extends User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ukspokgf.html

JS:   class Admin extends User {}
来源：http://dali.dashuyun.cn/Article/details/gt2lfdhboxi.html

TS:   class Admin extends User {}
来源：http://dali.tanke756.top/Article/details/gt2eotgehxs.html

Java: class Admin extends User {}
来源：http://dali.9152youxi.cn/Article/details/gt2ibwrtkop.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.kuanghao11.cn/Article/details/gt2epwjivkp.html

Ruby: class Admin < User; end
来源：http://dali.nanxinkj.top/Article/details/gt2aeimfide.html

C#:   class Admin : User {}
来源：http://dali.mhx1999.top/Article/details/gt2nyuqgrna.html

[G06] 重写方法
来源：http://dali.daria6918.cn/Article/details/gt2lgxngxlu.html

Py:   def greet(self): return "admin"
来源：http://dali.zhengqikj.top/Article/details/gt2kjwpyfyx.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.shzxlz.cn/Article/details/gt2oqgjzdvz.html

JS:   greet() { return "admin"; }
来源：http://dali.xinyue.icu/Article/details/gt2nmwehoto.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jinqigufen.top/Article/details/gt2mafwgdhd.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.fzhhl.top/Article/details/gt2cmwmcstz.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.ehwqpu.com/Article/details/gt2vfldcqdg.html

Ruby: def greet; "admin"; end
来源：http://dali.fengsongda.top/Article/details/gt2qplhrzkl.html

C#:   public override string Greet() => "admin";
来源：http://dali.hywenlv.cn/Article/details/gt2ulfbncoi.html

[G07] 调用父类方法
来源：http://dali.dashuyun.cn/Article/details/gt2khqwsaoq.html

Py:   super().greet()
来源：http://dali.nwbrower.top/Article/details/gt2ohedxctn.html

PHP:  parent::greet();
来源：http://dali.tanke756.top/Article/details/gt2tovcjyfn.html

JS:   super.greet();
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rprajyib.html

TS:   super.greet();
来源：http://dali.xuanzx.com/Article/details/gt2acyluzeu.html

Java: super.greet();
来源：http://dali.snrcjt.cn/Article/details/gt2eydbbapn.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jinqigfzy.top/Article/details/gt2labihjqh.html

Ruby: super
来源：http://dali.vqdsnc.cn/Article/details/gt2pdpopmel.html

C#:   base.Greet();
来源：http://dali.tian-w.cn/Article/details/gt2fsmcjmlh.html

[G08] 静态方法与属性
来源：http://dali.yueranfly.top/Article/details/gt2rdvbfzol.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.cqqwz.cn/Article/details/gt2cfbzjuly.html

PHP:  public static function f() {}
来源：http://dali.gaohongyu789.top/Article/details/gt2rhmmwuce.html

JS:   static f() {}
来源：http://dali.fengsongda.top/Article/details/gt2ewlohfff.html

TS:   static f(): void {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2azxjynfe.html

Java: static void f() {}
来源：http://dali.shuidangran.top/Article/details/gt2mhwrekkf.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hfpthk.cn/Article/details/gt2wbqfsnyx.html

Ruby: def self.f; end
来源：http://dali.jqgufenzy.top/Article/details/gt2spdhemzj.html

C#:   public static void F() {}
来源：http://dali.fengsongda.top/Article/details/gt2jymrtfqi.html

[G09] 接口 / 抽象类
来源：http://dali.cucudq.cn/Article/details/gt2coxyhyag.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.shuidangran.top/Article/details/gt2dkchouun.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.quarkkingdee.top/Article/details/gt2ybjwunca.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.xylfe.cn/Article/details/gt2qndnxlof.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2uhjekqit.html

Java: interface Shape { double area(); }
来源：http://dali.quarkkingdee.top/Article/details/gt2jtrftfxb.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hfpthk.cn/Article/details/gt2akabrmge.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.guannengcc.top/Article/details/gt2sutoqfra.html

C#:   interface IShape { double Area(); }
来源：http://dali.jqgufenzy.top/Article/details/gt2tdxopsic.html

[G10] 访问控制
来源：http://dali.smart0.xyz/Article/details/gt2dvzccxyj.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yvedp.cn/Article/details/gt2kxlcbxlk.html

PHP:  public / protected / private
来源：http://dali.andypj.xyz/Article/details/gt2dnwwlfjw.html

JS:   #private 字段；其余公开
来源：http://dali.9152youxi.cn/Article/details/gt2ikrgvlap.html

TS:   public / protected / private
来源：http://dali.yuanzhike.top/Article/details/gt2tvvarqvs.html

Java: public / protected / private / 默认包级
来源：http://dali.mhx1999.top/Article/details/gt2hcqjkqbs.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.feifeiyinyue.top/Article/details/gt2muvijtyc.html

Ruby: public / protected / private
来源：http://dali.zhixingplan.top/Article/details/gt2eafpdnfh.html

C#:   public / protected / private / internal
来源：http://dali.sufxvd.cn/Article/details/gt2huilfdot.html

[G11] getter / setter
来源：http://dali.svipenyu.cn/Article/details/gt2wmkskiiu.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gt2utxjosoi.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.gogol.net.cn/Article/details/gt2ckzrggfw.html

JS:   get name() { return this._name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ydtpzhra.html

TS:   get name(): string { return this._name; }
来源：http://dali.guowangkeji.top/Article/details/gt2sreulesv.html

Java: public String getName() { return name; }
来源：http://dali.yangfankeji.com/Article/details/gt2iuvcozhi.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.gogol.net.cn/Article/details/gt2xjxwttcj.html

Ruby: attr_accessor :name
来源：http://dali.daria6918.cn/Article/details/gt2lezlbutt.html

C#:   public string Name { get; set; }
来源：http://dali.ppjwa.cn/Article/details/gt2awhxytnu.html

[G12] 对象转字符串
来源：http://dali.fzhhl.top/Article/details/gt2fdmzxjog.html

Py:   def __str__(self): return self.name
来源：http://dali.havefunace.top/Article/details/gt2pityhbky.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yinkkfwv.html

JS:   toString() { return this.name; }
来源：http://dali.cheryme.top/Article/details/gt2dgnvxlzu.html

TS:   toString(): string { return this.name; }
来源：http://dali.kuanghao11.cn/Article/details/gt2pxgnreyi.html

Java: @Override public String toString() { return name; }
来源：http://dali.cashguo.top/Article/details/gt2digvprdk.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jinqigufen.top/Article/details/gt2qlnlziez.html

Ruby: def to_s; @name; end
来源：http://dali.hysaishi.cn/Article/details/gt2igmwxugf.html

C#:   public override string ToString() => Name;
来源：http://dali.yj202588.top/Article/details/gt2jgjegsun.html

[G13] 判断对象类型
来源：http://dali.guowangkeji.top/Article/details/gt2pdgfnigf.html

Py:   isinstance(u, User)
来源：http://dali.yj20258888.top/Article/details/gt2onrmfkza.html

PHP:  $u instanceof User
来源：http://dali.cashguo.top/Article/details/gt2thsumhnv.html

JS:   u instanceof User
来源：http://dali.gzhubu.top/Article/details/gt2cbyheuuc.html

TS:   u instanceof User
来源：http://dali.yangfankeji.com/Article/details/gt2zzdizskn.html

Java: u instanceof User
来源：http://dali.tanke756.top/Article/details/gt2dsyzrjaw.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.svipenyu.cn/Article/details/gt2yzaibyww.html

Ruby: u.is_a?(User)
来源：http://dali.nanxuanxn.top/Article/details/gt2qkcilmfm.html

C#:   u is User
来源：http://dali.yangfankeji.com/Article/details/gt2wzeaaqnc.html

[G14] 数据类 / record
来源：http://dali.pycfn.com/Article/details/gt2vrrumevs.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wmkjaefx.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.gaohongyu789.top/Article/details/gt2wtooxsgn.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.xuanzx.com/Article/details/gt2dqqegwkv.html

TS:   type User = { name: string; age: number };
来源：http://dali.zdqjudy.top/Article/details/gt2bmlhllqa.html

Java: record User(String name, int age) {}
来源：http://dali.daxiang520.top/Article/details/gt2gvklqfyl.html

Go:   type User struct { Name string; Age int }
来源：http://dali.gzhubu.top/Article/details/gt2vobdbnzc.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.haohaochexian.top/Article/details/gt2etgzoqil.html

C#:   record User(string Name, int Age);
来源：http://dali.cashguo.top/Article/details/gt2qektrosj.html

[G15] 枚举
来源：http://dali.svipenyu.cn/Article/details/gt2nmiczmbi.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jlsjyb.cn/Article/details/gt2adsvbent.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.gaohongyu789.top/Article/details/gt2lxwyubes.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yj20258.top/Article/details/gt2pdggqzjo.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cqqwz.cn/Article/details/gt2sxnxlxva.html

Java: enum Color { RED, GREEN }
来源：http://dali.chenzaomai.com/Article/details/gt2yleuvokw.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.9152youxi.cn/Article/details/gt2tizvnprh.html

Ruby: Color = %i[red green].freeze
来源：http://dali.cqqwz.cn/Article/details/gt2xhgmrxfg.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhengqikj.top/Article/details/gt2yamduvpp.html

[G16] 对象转数组 / 字典
来源：http://dali.svipenyu.cn/Article/details/gt2njtpapej.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.316326.xyz/Article/details/gt2bzhdmakj.html

PHP:  get_object_vars($obj);
来源：http://dali.havefunace.top/Article/details/gt2imweqexz.html

JS:   Object.entries(obj)
来源：http://dali.shuidangran.top/Article/details/gt2csmftzew.html

TS:   Object.entries(obj)
来源：http://dali.nanxinkj.top/Article/details/gt2zrzymqgg.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.gaohongyu789.top/Article/details/gt2kvvokwsv.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.dianchejie.cn/Article/details/gt2sxoiagqr.html

Ruby: obj.instance_variables
来源：http://dali.cucudq.cn/Article/details/gt2hjlmpdcv.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yuxming.cn/Article/details/gt2lfeljbwz.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2wgluwwfl.html

H. 异常与错误处理
来源：http://dali.316326.xyz/Article/details/gt2bjmlsgus.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2yagjnjqp.html

[H01] try / catch 基础
来源：http://dali.ppjwa.cn/Article/details/gt2xtqkcmms.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.tian-w.cn/Article/details/gt2nysefybo.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.havefunace.top/Article/details/gt2uaqsccmc.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jyoumei.cn/Article/details/gt2lntgvkgu.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2pvrvjtze.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.tianlin.xyz/Article/details/gt2iaepqxhi.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.xuanzx.com/Article/details/gt2wdijpjyb.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.nanxuanxn.top/Article/details/gt2efkpybdv.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kecyrxhb.html

[H02] finally / ensure 收尾
来源：http://dali.vqdsnc.cn/Article/details/gt2nanyvmci.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhengqikj.top/Article/details/gt2ccmiombn.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.quarkkingdee.top/Article/details/gt2xpjgynpx.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.cucudq.cn/Article/details/gt2cfmejjqg.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.andypj.xyz/Article/details/gt2ttpeeskt.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.gaohongyu789.top/Article/details/gt2mkxsnhht.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.cdnleiting.top/Article/details/gt2lmdqsvbb.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.guannengcc.top/Article/details/gt2fiafycty.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.gaohongyu789.top/Article/details/gt2ahttcvmg.html

[H03] 主动抛出异常
来源：http://dali.tian-w.cn/Article/details/gt2pvrahazw.html

Py:   raise ValueError("错误信息")
来源：http://dali.aibaodan.cn/Article/details/gt2tnelpvem.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jlsjyb.cn/Article/details/gt2hxhuxhxe.html

JS:   throw new Error("错误信息");
来源：http://dali.guowangkeji.top/Article/details/gt2wsigwbqn.html

TS:   throw new Error("错误信息");
来源：http://dali.shangyingyoupin.top/Article/details/gt2hsultees.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yanxiufei.cn/Article/details/gt2rmztbwup.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.smart0.xyz/Article/details/gt2ugkourbk.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.haohaochexian.top/Article/details/gt2gstsahzf.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.gzhubu.top/Article/details/gt2bykaeimf.html

[H04] 自定义异常类型
来源：http://dali.cheryme.top/Article/details/gt2rgzqaypq.html

Py:   class MyError(Exception): pass
来源：http://dali.quarkkingdee.top/Article/details/gt2ovapsdfr.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zdqjudy.top/Article/details/gt2mtuzhjhe.html

JS:   class MyError extends Error {}
来源：http://dali.cdnleiting.top/Article/details/gt2dxteptct.html

TS:   class MyError extends Error {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2tafxztsv.html

Java: class MyException extends RuntimeException {}
来源：http://dali.cashguo.top/Article/details/gt2qfmpqoxt.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.quarkkingdee.top/Article/details/gt2qoynpjjx.html

Ruby: class MyError < StandardError; end
来源：http://dali.cdnleiting.top/Article/details/gt2ycljvkeq.html

C#:   class MyException : Exception {}
来源：http://dali.mhx1999.top/Article/details/gt2ylcxiwlb.html

[H05] 捕获特定类型
来源：http://dali.mhx1999.top/Article/details/gt2kfgaxjaj.html

Py:   except ValueError as e:
来源：http://dali.zhiwuduotai.top/Article/details/gt2ymfgjkqx.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jyoumei.cn/Article/details/gt2lbmosjxg.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.0kj1m.cn/Article/details/gt2necfqvks.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.quarkkingdee.top/Article/details/gt2kxpxpeht.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jlsjyb.cn/Article/details/gt2psqsgkjy.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhoulong.xyz/Article/details/gt2lvqywwed.html

Ruby: rescue ArgumentError => e
来源：http://dali.jyoumei.cn/Article/details/gt2vfagdvyb.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zeculggu.html

[H06] 可选值 / 空值安全访问
来源：http://dali.kuanghao11.cn/Article/details/gt2xrdzmrpc.html

Py:   value = d.get("k") or default
来源：http://dali.xziqi.cn/Article/details/gt2hxjjxdwn.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.9152youxi.cn/Article/details/gt2rvwlqepi.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.iojbl.cn/Article/details/gt2zdmpidpj.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.xuetiantiany.cn/Article/details/gt2uvubrvlz.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.iojbl.cn/Article/details/gt2pwbwdmxn.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.sufxvd.cn/Article/details/gt2xlmwfygk.html

Ruby: d&.dig(:a, :b)
来源：http://dali.meibo888.top/Article/details/gt2ykfhjggy.html

C#:   obj?.A?.B ?? default
来源：http://dali.cqqwz.cn/Article/details/gt2dwyzfdvk.html


<!-- 参考信息 -->