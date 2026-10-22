代发 wailian999

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.guannengcc.top/Article/details/gtylfrsgsf.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gogol.net.cn/Article/details/gtfwlmldhf.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.cdnleiting.top/Article/details/gtshsqpvhe.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.hammf.cn/Article/details/gtqiygwhqk.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yueranfly.top/Article/details/gtvikcvius.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jinqigufen.top/Article/details/gtgstprbwg.html

[F03] 写入文件（覆盖）
来源：http://dali.jinqigfzy.top/Article/details/gtepwnqtkf.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.gotoacloud.top/Article/details/gtzpfzsana.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.pengpengdd.cyou/Article/details/gtfrwkvbcj.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtikfehstd.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.kuanghao11.cn/Article/details/gtfqsdjxri.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.nanxinkj.top/Article/details/gtjsviuvhl.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.daria6918.cn/Article/details/gttmkvfclz.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.hywenlv.cn/Article/details/gttujzxzwm.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.daxiang520.top/Article/details/gtmwqsrrbd.html

[F04] 追加写入文件
来源：http://dali.zhixingplan.top/Article/details/gtjewdjbyu.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.bjfxy.top/Article/details/gtfmhigiih.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.wangshuangyany.cn/Article/details/gtejlcpepl.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hammf.cn/Article/details/gtcaekctpk.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.haohaochexian.top/Article/details/gtahunwanf.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.tanke756.top/Article/details/gttxhsllxb.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.aibaodan.cn/Article/details/gtgtgycjha.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.chenzaomai.com/Article/details/gtsylymost.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.hysaishi.cn/Article/details/gtquoleniu.html

[F05] 判断文件或目录是否存在
来源：http://dali.sufxvd.cn/Article/details/gtjhnjzfor.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.sufxvd.cn/Article/details/gtmsrmcprh.html

PHP:  file_exists("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gtfoocmjrv.html

JS:   fs.existsSync("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gttnjgbwfb.html

TS:   fs.existsSync("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtnmknlppw.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhongyouzk.top/Article/details/gtvtxcrkbf.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hywenlv.cn/Article/details/gtmvqflxod.html

Ruby: File.exist?("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtyqsnwudc.html

C#:   File.Exists("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtzspfdtuf.html

[F06] 删除文件
来源：http://dali.xziqi.cn/Article/details/gtvickganh.html

Py:   os.remove("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtezcdyztv.html

PHP:  unlink("a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gtndtftuvo.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtzfjnlrkj.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.316326.xyz/Article/details/gtcztvpwwt.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.guannengcc.top/Article/details/gtpcbarxvs.html

Go:   os.Remove("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtiqgrxovp.html

Ruby: File.delete("a.txt")
来源：http://dali.316326.xyz/Article/details/gtfxwjvkab.html

C#:   File.Delete("a.txt");
来源：http://dali.sysykeji.top/Article/details/gtqkzuzfsp.html

[F07] 创建目录（含多级）
来源：http://dali.sweek.top/Article/details/gtobzpeefv.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zdqjudy.top/Article/details/gtwesvsepl.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yueranfly.top/Article/details/gtcrdccbkr.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gzhubu.top/Article/details/gtzsetfumn.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yj202588.top/Article/details/gtoigikwjg.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhiwuduotai.top/Article/details/gtvecffcec.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yuanzhike.top/Article/details/gtcbkljbic.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.shuidangran.top/Article/details/gtmswzaqrl.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jiagoushi.top/Article/details/gtshokcrug.html

[F08] 遍历目录
来源：http://dali.yueranfly.top/Article/details/gtabmyeica.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.ehwqpu.com/Article/details/gtlxvbshpi.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjvimbyvg.html

JS:   fs.readdirSync("dir")
来源：http://dali.yongpay.top/Article/details/gtirebzten.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhongyouzk.top/Article/details/gtpwzlrtbp.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hongshengwenyu.top/Article/details/gtebbikfad.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.hywenlv.cn/Article/details/gtixygwbqo.html

Ruby: Dir.children("dir")
来源：http://dali.jinqigfzy.top/Article/details/gtbtccsoum.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hnxiangtu.top/Article/details/gtdxooqwuo.html

[F09] 获取文件大小
来源：http://dali.vqdsnc.cn/Article/details/gtjrfklcnl.html

Py:   os.path.getsize("a.txt")
来源：http://dali.ivvv.top/Article/details/gtjbyyooej.html

PHP:  filesize("a.txt");
来源：http://dali.snrcjt.cn/Article/details/gtapigtgzt.html

JS:   fs.statSync("a.txt").size
来源：http://dali.mhx1999.top/Article/details/gtldhiprxr.html

TS:   fs.statSync("a.txt").size
来源：http://dali.xuanzx.com/Article/details/gtnacymqcy.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.dashuyun.cn/Article/details/gtcjttufjx.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.ivvv.top/Article/details/gtyvphoezw.html

Ruby: File.size("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtmbifnymx.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.sweek.top/Article/details/gtsdedanly.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.smart0.xyz/Article/details/gtspsazyaw.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.iojbl.cn/Article/details/gtyofpymbr.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.ydzc1.top/Article/details/gtvyrejlgz.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.sxryk.cn/Article/details/gtokdxdzfg.html

TS:   path.extname("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtcgediavl.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.0kj1m.cn/Article/details/gtmpeadmfv.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gthqxqztda.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.cheryme.top/Article/details/gtluxanvdy.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtzveptnib.html

[F11] 复制与移动文件
来源：http://dali.ivvv.top/Article/details/gtwxiuwrxa.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.xinyue.icu/Article/details/gtnokxfncm.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.shzxlz.cn/Article/details/gtpxdxakgi.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.wangdashe.top/Article/details/gtaefgwvyj.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xziqi.cn/Article/details/gtzpqnfwmm.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yvedp.cn/Article/details/gtyeddocqh.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.xuetiantiany.cn/Article/details/gtqjithway.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtdpkmwgmz.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jyoumei.cn/Article/details/gtlcdhbggk.html

[F12] CSV 读写
来源：http://dali.hysaishi.cn/Article/details/gtzncakmtv.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.snrcjt.cn/Article/details/gtxeptpdpz.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yongpay.top/Article/details/gthqaziusq.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.cashguo.top/Article/details/gttvvmdiei.html

TS:   // 同上
来源：http://dali.fengsongda.top/Article/details/gtyioocibz.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.pycfn.com/Article/details/gtgmuugvgy.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.chenzaomai.com/Article/details/gtzpbnkjsu.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jinqigfzy.top/Article/details/gtnsyogdck.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hammf.cn/Article/details/gtvtwobjft.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtukeuanqj.html

G. 面向对象
来源：http://dali.yj20258.top/Article/details/gtabmjpjpw.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtazunwvet.html

[G01] 定义类
来源：http://dali.birdmap.top/Article/details/gtpwbbcudk.html

Py:   class User: pass
来源：http://dali.c1oappe.top/Article/details/gteqxdisxj.html

PHP:  class User {}
来源：http://dali.yonumen.top/Article/details/gtfkfbjxai.html

JS:   class User {}
来源：http://dali.cashguo.top/Article/details/gtjwcgklxp.html

TS:   class User { name: string = ""; }
来源：http://dali.ivvv.top/Article/details/gtujdoclbi.html

Java: class User {}
来源：http://dali.zhoulong.xyz/Article/details/gtflpkbmlz.html

Go:   type User struct { Name string }
来源：http://dali.gaohongyu789.top/Article/details/gttgmztlip.html

Ruby: class User; end
来源：http://dali.0kj1m.cn/Article/details/gttbghzrya.html

C#:   class User {}
来源：http://dali.yj202588.top/Article/details/gtvtqbcyll.html

[G02] 构造函数
来源：http://dali.cashguo.top/Article/details/gtqepiemeo.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhixingplan.top/Article/details/gtycfpqhjw.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yvedp.cn/Article/details/gtormewcdb.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.guowangkeji.top/Article/details/gtsqwxeexe.html

TS:   constructor(public name: string) {}
来源：http://dali.cucudq.cn/Article/details/gtyvrzdoav.html

Java: User(String name) { this.name = name; }
来源：http://dali.yj202588.top/Article/details/gtxuotbark.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yonumen.top/Article/details/gtxuwntise.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.ydzc1.top/Article/details/gtkdabdtni.html

C#:   public User(string name) { Name = name; }
来源：http://dali.smart0.xyz/Article/details/gtvwxqepth.html

[G03] 实例属性
来源：http://dali.cqqwz.cn/Article/details/gtnkqogauu.html

Py:   self.name = "x"
来源：http://dali.ydzc1.top/Article/details/gtfzwvznae.html

PHP:  public string $name = "x";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtozvfvwwc.html

JS:   this.name = "x";
来源：http://dali.hnqzz.top/Article/details/gtprxaxect.html

TS:   name: string = "x";
来源：http://dali.zhoulong.xyz/Article/details/gtkzqfvxlo.html

Java: private String name;
来源：http://dali.chenlongwang.top/Article/details/gtcvabbozp.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.xziqi.cn/Article/details/gthcadymmz.html

Ruby: @name = "x"
来源：http://dali.bjfxy.top/Article/details/gtemszrvpq.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.pengpengdd.cyou/Article/details/gthiubfkdg.html

[G04] 定义方法
来源：http://dali.sxryk.cn/Article/details/gtspfxpcuj.html

Py:   def greet(self): return self.name
来源：http://dali.redwolf501.top/Article/details/gtezwwxzgh.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.mhx1999.top/Article/details/gtirkzxtqi.html

JS:   greet() { return this.name; }
来源：http://dali.andypj.xyz/Article/details/gtozmqkkho.html

TS:   greet(): string { return this.name; }
来源：http://dali.jiagoushi.top/Article/details/gtjkzsykuu.html

Java: String greet() { return name; }
来源：http://dali.nanxinkj.top/Article/details/gtcnviqngb.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhongyouzk.top/Article/details/gtgnezlwdm.html

Ruby: def greet; @name; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtryuvrzgf.html

C#:   public string Greet() => Name;
来源：http://dali.redwolf501.top/Article/details/gtyqdojqbx.html

[G05] 继承
来源：http://dali.fzhhl.top/Article/details/gtinuzivok.html

Py:   class Admin(User): pass
来源：http://dali.xuetiantiany.cn/Article/details/gtarbcoint.html

PHP:  class Admin extends User {}
来源：http://dali.yanxiufei.cn/Article/details/gtgrodboea.html

JS:   class Admin extends User {}
来源：http://dali.gogol.net.cn/Article/details/gtlknphzpx.html

TS:   class Admin extends User {}
来源：http://dali.pycfn.com/Article/details/gtrodxpwgn.html

Java: class Admin extends User {}
来源：http://dali.jinqigufen.top/Article/details/gtqcssgkkh.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhoulong.xyz/Article/details/gtfnpkaqru.html

Ruby: class Admin < User; end
来源：http://dali.zhiwuduotai.top/Article/details/gtzswbflcz.html

C#:   class Admin : User {}
来源：http://dali.pengpengdd.cyou/Article/details/gtegmmhuwr.html

[G06] 重写方法
来源：http://dali.sxryk.cn/Article/details/gtamaudijf.html

Py:   def greet(self): return "admin"
来源：http://dali.nwbrower.top/Article/details/gtqkloysyp.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yangfankeji.com/Article/details/gtdlksxlmw.html

JS:   greet() { return "admin"; }
来源：http://dali.aibaodan.cn/Article/details/gtxjqottdp.html

TS:   greet(): string { return "admin"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtifxyzvnr.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.chenjidiqi.icu/Article/details/gteyccvgcq.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zdqjudy.top/Article/details/gtaliyzzwv.html

Ruby: def greet; "admin"; end
来源：http://dali.hnqzz.top/Article/details/gtohwulvkn.html

C#:   public override string Greet() => "admin";
来源：http://dali.gogol.net.cn/Article/details/gtqunftppu.html

[G07] 调用父类方法
来源：http://dali.redwolf501.top/Article/details/gtujewrvjp.html

Py:   super().greet()
来源：http://dali.hongshengwenyu.top/Article/details/gttvnfcfcl.html

PHP:  parent::greet();
来源：http://dali.fengsongda.top/Article/details/gttywcffqn.html

JS:   super.greet();
来源：http://dali.ybcxt.top/Article/details/gtytuvlblc.html

TS:   super.greet();
来源：http://dali.sweek.top/Article/details/gtirzszrqy.html

Java: super.greet();
来源：http://dali.guowangkeji.top/Article/details/gtzbsmmhga.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.smart0.xyz/Article/details/gtbpixtxpa.html

Ruby: super
来源：http://dali.birdmap.top/Article/details/gtewquclbr.html

C#:   base.Greet();
来源：http://dali.andypj.xyz/Article/details/gtjfhkouzj.html

[G08] 静态方法与属性
来源：http://dali.birdmap.top/Article/details/gtvyyhahof.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jqgfzy.top/Article/details/gtzmvxksqr.html

PHP:  public static function f() {}
来源：http://dali.zhengqikj.top/Article/details/gtskjssvki.html

JS:   static f() {}
来源：http://dali.cdnleiting.top/Article/details/gtupikptzd.html

TS:   static f(): void {}
来源：http://dali.chenjidiqi.icu/Article/details/gtxkfbyelk.html

Java: static void f() {}
来源：http://dali.sweek.top/Article/details/gtchdegiyx.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.dashuyun.cn/Article/details/gtntgdxykp.html

Ruby: def self.f; end
来源：http://dali.tian-w.cn/Article/details/gtxwvwqzzb.html

C#:   public static void F() {}
来源：http://dali.ybcxt.top/Article/details/gtbpkftxue.html

[G09] 接口 / 抽象类
来源：http://dali.yvedp.cn/Article/details/gtcqzpdsmv.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.xziqi.cn/Article/details/gtnsrrepbj.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yuanzhike.top/Article/details/gtalletuiv.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ybcxt.top/Article/details/gthyphujqx.html

TS:   interface Shape { area(): number; }
来源：http://dali.jianghu66.top/Article/details/gtpfbtiboh.html

Java: interface Shape { double area(); }
来源：http://dali.iojbl.cn/Article/details/gtchzcirld.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.cucudq.cn/Article/details/gteifeudtc.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcghxlmzs.html

C#:   interface IShape { double Area(); }
来源：http://dali.316326.xyz/Article/details/gtudqzthzm.html

[G10] 访问控制
来源：http://dali.meibo888.top/Article/details/gtzddelxti.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.sweek.top/Article/details/gtulqwwdeh.html

PHP:  public / protected / private
来源：http://dali.jinghuilouyu.cn/Article/details/gtepqjlfkr.html

JS:   #private 字段；其余公开
来源：http://dali.zhixingplan.top/Article/details/gtaubwtfek.html

TS:   public / protected / private
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmcicqwhu.html

Java: public / protected / private / 默认包级
来源：http://dali.cucudq.cn/Article/details/gthjstlrag.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.ehwqpu.com/Article/details/gtfxmvcdsr.html

Ruby: public / protected / private
来源：http://dali.chenzaomai.com/Article/details/gtfpbmguwm.html

C#:   public / protected / private / internal
来源：http://dali.zhoulong.xyz/Article/details/gtxeittrbw.html

[G11] getter / setter
来源：http://dali.sxryk.cn/Article/details/gtbbpdxejg.html

Py:   @property 与 @x.setter
来源：http://dali.jinyuanbaomall.cn/Article/details/gtibeqhyad.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtayjpndaa.html

JS:   get name() { return this._name; }
来源：http://dali.c1oappe.top/Article/details/gtuxquudrk.html

TS:   get name(): string { return this._name; }
来源：http://dali.smart0.xyz/Article/details/gtlliosise.html

Java: public String getName() { return name; }
来源：http://dali.vqdsnc.cn/Article/details/gtyaveyrej.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.meibo888.top/Article/details/gtijjtpior.html

Ruby: attr_accessor :name
来源：http://dali.gogol.net.cn/Article/details/gtjuadnwye.html

C#:   public string Name { get; set; }
来源：http://dali.gogol.net.cn/Article/details/gtdmjyoyyo.html

[G12] 对象转字符串
来源：http://dali.xuetiantiany.cn/Article/details/gtlgisuirz.html

Py:   def __str__(self): return self.name
来源：http://dali.c1oappe.top/Article/details/gtgrparsnh.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.xziqi.cn/Article/details/gtprxoscfv.html

JS:   toString() { return this.name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgysqhwml.html

TS:   toString(): string { return this.name; }
来源：http://dali.iojbl.cn/Article/details/gtpaqlqrxo.html

Java: @Override public String toString() { return name; }
来源：http://dali.ybcxt.top/Article/details/gtcxyjtxsq.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhixingplan.top/Article/details/gteidrmpxl.html

Ruby: def to_s; @name; end
来源：http://dali.sufxvd.cn/Article/details/gtezhchgte.html

C#:   public override string ToString() => Name;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaflgkevd.html

[G13] 判断对象类型
来源：http://dali.hongshengwenyu.top/Article/details/gtmrtbojwi.html

Py:   isinstance(u, User)
来源：http://dali.chenzaomai.com/Article/details/gtuoieqpxm.html

PHP:  $u instanceof User
来源：http://dali.zhoulong.xyz/Article/details/gtqphsidza.html

JS:   u instanceof User
来源：http://dali.iojbl.cn/Article/details/gtxmolfjtr.html

TS:   u instanceof User
来源：http://dali.guowangkeji.top/Article/details/gthqnawdje.html

Java: u instanceof User
来源：http://dali.nanxinkj.top/Article/details/gtkpyiouph.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yonumen.top/Article/details/gtcottuxqk.html

Ruby: u.is_a?(User)
来源：http://dali.gaohongyu789.top/Article/details/gtiqutfhel.html

C#:   u is User
来源：http://dali.hnxiangtu.top/Article/details/gtkmbhwkiu.html

[G14] 数据类 / record
来源：http://dali.316326.xyz/Article/details/gtkmzyszbb.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.9152youxi.cn/Article/details/gtsqounhlp.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.316326.xyz/Article/details/gtivdzygsz.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zdqjudy.top/Article/details/gtdlktdlxs.html

TS:   type User = { name: string; age: number };
来源：http://dali.jinqigufen.top/Article/details/gtyiwqljns.html

Java: record User(String name, int age) {}
来源：http://dali.yj20258.top/Article/details/gtofqtinnb.html

Go:   type User struct { Name string; Age int }
来源：http://dali.wangdashe.top/Article/details/gttwfwpvjv.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfqdqjqkf.html

C#:   record User(string Name, int Age);
来源：http://dali.zdqjudy.top/Article/details/gtdsnmvdsc.html

[G15] 枚举
来源：http://dali.yj20258888.top/Article/details/gtuorvdxaw.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jyoumei.cn/Article/details/gtxjvqoxsc.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.hammf.cn/Article/details/gtsdoolyqw.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jyoumei.cn/Article/details/gtntvkqegw.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ydzc1.top/Article/details/gtikxlfokl.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhengqikj.top/Article/details/gtpccbvyux.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.cqqwz.cn/Article/details/gtbkfbqxoa.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yj202588.top/Article/details/gttyzoxays.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhengqikj.top/Article/details/gtybdzkcqw.html

[G16] 对象转数组 / 字典
来源：http://dali.wangdashe.top/Article/details/gtlowcvjnw.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.hywenlv.cn/Article/details/gtssrcrnpx.html

PHP:  get_object_vars($obj);
来源：http://dali.cdnleiting.top/Article/details/gtpxdqjzwd.html

JS:   Object.entries(obj)
来源：http://dali.guannengcc.top/Article/details/gtlfnwljvv.html

TS:   Object.entries(obj)
来源：http://dali.yj202588.top/Article/details/gtxqlmwrck.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.ydzc1.top/Article/details/gtaqvorntd.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhoulong.xyz/Article/details/gtzkqdqmsf.html

Ruby: obj.instance_variables
来源：http://dali.haohaochexian.top/Article/details/gtlywuhspo.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.andypj.xyz/Article/details/gtltyhohss.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtmzrtjydt.html

H. 异常与错误处理
来源：http://dali.jyoumei.cn/Article/details/gtnrnkferx.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtmdqpkprz.html

[H01] try / catch 基础
来源：http://dali.xinyue.icu/Article/details/gtxhbnbrys.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhongyouzk.top/Article/details/gtfklpkleo.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.gzhubu.top/Article/details/gtntaqradu.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jinqigfzy.top/Article/details/gtupcstlyn.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.pengpengdd.cyou/Article/details/gtvyfwwcdv.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hammf.cn/Article/details/gtmecjlmmq.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.tianlin.xyz/Article/details/gtjsmmzboy.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.wangshuangyany.cn/Article/details/gtpzcdczaq.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.sweek.top/Article/details/gtikqfahfp.html

[H02] finally / ensure 收尾
来源：http://dali.yvedp.cn/Article/details/gtvzjqnqcj.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhoulong.xyz/Article/details/gtlgdwlctp.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.kuanghao11.cn/Article/details/gtoxsremmf.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.cdnleiting.top/Article/details/gtrrzqbxks.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinqigufen.top/Article/details/gtmrbrkqmh.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.pycfn.com/Article/details/gtutofgmwb.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.gotoacloud.top/Article/details/gtipoqvaoq.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.gaohongyu789.top/Article/details/gtlsbyqbyf.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.nanxuanxn.top/Article/details/gtncftoxpl.html

[H03] 主动抛出异常
来源：http://dali.aibaodan.cn/Article/details/gttusfszng.html

Py:   raise ValueError("错误信息")
来源：http://dali.yuxming.cn/Article/details/gtjpxjyzjh.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hongshengwenyu.top/Article/details/gteaiotdkr.html

JS:   throw new Error("错误信息");
来源：http://dali.9152youxi.cn/Article/details/gtpmirdgin.html

TS:   throw new Error("错误信息");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtblumphxc.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xuanzx.com/Article/details/gtnpaajzns.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.mhx1999.top/Article/details/gtgohqnubt.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.xuetiantiany.cn/Article/details/gtbplshqfc.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.iojbl.cn/Article/details/gtuvrnoelb.html

[H04] 自定义异常类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjuasrccj.html

Py:   class MyError(Exception): pass
来源：http://dali.chenlongwang.top/Article/details/gtqmpgtuha.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.shzxlz.cn/Article/details/gtkifukuuz.html

JS:   class MyError extends Error {}
来源：http://dali.quarkkingdee.top/Article/details/gtefgelkbk.html

TS:   class MyError extends Error {}
来源：http://dali.yj20258888.top/Article/details/gtqzuxvhgw.html

Java: class MyException extends RuntimeException {}
来源：http://dali.cashguo.top/Article/details/gtxuipjwmi.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.andypj.xyz/Article/details/gtnexrskvk.html

Ruby: class MyError < StandardError; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkfkscnvk.html

C#:   class MyException : Exception {}
来源：http://dali.jqgufenzy.top/Article/details/gtcsrrlkei.html

[H05] 捕获特定类型
来源：http://dali.sxryk.cn/Article/details/gtmbfgplot.html

Py:   except ValueError as e:
来源：http://dali.hammf.cn/Article/details/gtbtefbcxw.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.sweek.top/Article/details/gtpbkqcblw.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.meibo888.top/Article/details/gtzsfztctl.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.cashguo.top/Article/details/gthndpucse.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.chenlongwang.top/Article/details/gtvvjhgndh.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.xuetiantiany.cn/Article/details/gtgnulrvvq.html

Ruby: rescue ArgumentError => e
来源：http://dali.nanxuanxn.top/Article/details/gtluvaqsyz.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.sweek.top/Article/details/gtwgiakafg.html

[H06] 可选值 / 空值安全访问
来源：http://dali.hammf.cn/Article/details/gtijmmyacw.html

Py:   value = d.get("k") or default
来源：http://dali.yonumen.top/Article/details/gtuyzbysno.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yangfankeji.com/Article/details/gtniibxctz.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhixingplan.top/Article/details/gtzgtwgvyv.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.sweek.top/Article/details/gtzwoogikd.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.iojbl.cn/Article/details/gttpuyeteb.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwqgyimnj.html

Ruby: d&.dig(:a, :b)
来源：http://dali.cheryme.top/Article/details/gtteqzoand.html

C#:   obj?.A?.B ?? default
来源：http://dali.tian-w.cn/Article/details/gtysshykbq.html


<!-- 参考信息 -->