代发 wailian999

C#:   File.ReadAllText("a.txt");
来源：http://dali.c1oappe.top/Article/details/gtwqnrzwue.html

[F02] 逐行读取文件
来源：http://dali.aizwys.cn/Article/details/gtpnlxhglj.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jyoumei.cn/Article/details/gtrdphgnfk.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.smart0.xyz/Article/details/gtsfyazjyf.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yueranfly.top/Article/details/gtoaijyuyv.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.fzhhl.top/Article/details/gtqpnnkfkz.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.0kj1m.cn/Article/details/gtdbubxuhe.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.ywan-chungtsiang.top/Article/details/gttscaeend.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jyoumei.cn/Article/details/gtywuvdssl.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jqgufenzy.top/Article/details/gtnbzedkjo.html

[F03] 写入文件（覆盖）
来源：http://dali.fengsongda.top/Article/details/gtayyiayxc.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtynjeqepp.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yanxiufei.cn/Article/details/gttrruosqt.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.quarkkingdee.top/Article/details/gtslanfajg.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhixingplan.top/Article/details/gtggmdclis.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jqgufenzy.top/Article/details/gtntkmyuzn.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.redwolf501.top/Article/details/gtegsmowae.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhengqikj.top/Article/details/gtwsxsniwp.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jqgfzy.top/Article/details/gtmbbbnkss.html

[F04] 追加写入文件
来源：http://dali.hongshengwenyu.top/Article/details/gtcoylultn.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yueranfly.top/Article/details/gtfrudaffh.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yuanzhike.top/Article/details/gtwrzivyjy.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yj20258.top/Article/details/gtykjonkph.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jianghu66.top/Article/details/gtgoknwqdh.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.shzxlz.cn/Article/details/gtapkzcity.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.hywenlv.cn/Article/details/gtjmawokfq.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.fengsongda.top/Article/details/gtjzzsvrnx.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.sxryk.cn/Article/details/gtegqesyok.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gtjrpezezl.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhiwuduotai.top/Article/details/gtfpvlfonq.html

PHP:  file_exists("a.txt");
来源：http://dali.jinqigufen.top/Article/details/gtfpidroca.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hammf.cn/Article/details/gthhqlpewe.html

TS:   fs.existsSync("a.txt")
来源：http://dali.smart0.xyz/Article/details/gteorvyins.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.shuidangran.top/Article/details/gtcczvgkpf.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiumadpyh.html

Ruby: File.exist?("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtvinjcazs.html

C#:   File.Exists("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtxejcgkcu.html

[F06] 删除文件
来源：http://dali.zhongyouzk.top/Article/details/gtdfreqjem.html

Py:   os.remove("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtfrngpieh.html

PHP:  unlink("a.txt");
来源：http://dali.cqqwz.cn/Article/details/gtmpogbfpv.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtdxzmxpgb.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtqornndhw.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.c1oappe.top/Article/details/gtolcoewsj.html

Go:   os.Remove("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtlfudpxzg.html

Ruby: File.delete("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtqngyqwqb.html

C#:   File.Delete("a.txt");
来源：http://dali.yangfankeji.com/Article/details/gtpmdsbagj.html

[F07] 创建目录（含多级）
来源：http://dali.wangdashe.top/Article/details/gtnbbxxonn.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yueranfly.top/Article/details/gtnniscxob.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jyoumei.cn/Article/details/gtnbwebkcp.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hammf.cn/Article/details/gtsctwrcem.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sxryk.cn/Article/details/gtnyzpidsf.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.sufxvd.cn/Article/details/gtbyiyitbt.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.havefunace.top/Article/details/gtvnsfrgfy.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.tian-w.cn/Article/details/gtjfczvern.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yuanzhike.top/Article/details/gtjiaimfko.html

[F08] 遍历目录
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtutjfzlki.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.xuetiantiany.cn/Article/details/gtdqswppta.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.hywenlv.cn/Article/details/gtlhqrldxs.html

JS:   fs.readdirSync("dir")
来源：http://dali.gaohongyu789.top/Article/details/gtemwisbmd.html

TS:   fs.readdirSync("dir")
来源：http://dali.cdnleiting.top/Article/details/gtxekhihkv.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.xuanzx.com/Article/details/gtbotyrmaz.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.tianlin.xyz/Article/details/gtlzbyqsrl.html

Ruby: Dir.children("dir")
来源：http://dali.chenjidiqi.icu/Article/details/gtngtmdcnj.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yanxiufei.cn/Article/details/gtgeheldrd.html

[F09] 获取文件大小
来源：http://dali.cqqwz.cn/Article/details/gtwxnfffaf.html

Py:   os.path.getsize("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtzwqfctmi.html

PHP:  filesize("a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gtzgitvcbl.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jqgfzy.top/Article/details/gtromgetla.html

TS:   fs.statSync("a.txt").size
来源：http://dali.tianlin.xyz/Article/details/gtdapuxvlq.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.pycfn.com/Article/details/gtuckqkpjk.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.shuidangran.top/Article/details/gtojevjcaw.html

Ruby: File.size("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtjqdxmwxi.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.chenzaomai.com/Article/details/gtnjgqqrss.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zycfv.cn/Article/details/gtslzgrlos.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.nanxinkj.top/Article/details/gteejwsblx.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.shzxlz.cn/Article/details/gtyiyruufu.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yvedp.cn/Article/details/gtizpusypb.html

TS:   path.extname("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtfzrebztl.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jinqigufen.top/Article/details/gtltkoyaan.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.sweek.top/Article/details/gtpmfoqukp.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.andypj.xyz/Article/details/gtmoxlmuuf.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtrqbwggyc.html

[F11] 复制与移动文件
来源：http://dali.zhiwuduotai.top/Article/details/gtixoadibz.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtcbsasyif.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhoulong.xyz/Article/details/gtxdkstjxx.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.kuanghao11.cn/Article/details/gttccueedp.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ydzc1.top/Article/details/gtrwixhcxl.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.guowangkeji.top/Article/details/gtggyjmizr.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.daria6918.cn/Article/details/gtackkrmtq.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiyhgvgnz.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.sufxvd.cn/Article/details/gtisxyvcqv.html

[F12] CSV 读写
来源：http://dali.ydzc1.top/Article/details/gtpehmfsks.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.chenjidiqi.icu/Article/details/gtunwgmokn.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.sysykeji.top/Article/details/gtohpifeqz.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hfpthk.cn/Article/details/gtsjirlxul.html

TS:   // 同上
来源：http://dali.yj20258888.top/Article/details/gtitlkyhbg.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.pycfn.com/Article/details/gtyglgqrjz.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.wangshuangyany.cn/Article/details/gtxgbxnlqj.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.xziqi.cn/Article/details/gtzpeibwpk.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hnxiangtu.top/Article/details/gtcudbsjnw.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtrpepwfyi.html

G. 面向对象
来源：http://dali.andypj.xyz/Article/details/gtbkkhssfl.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtitzdubod.html

[G01] 定义类
来源：http://dali.tian-w.cn/Article/details/gtepflleoc.html

Py:   class User: pass
来源：http://dali.yj20258.top/Article/details/gtxzaulluk.html

PHP:  class User {}
来源：http://dali.nanxinkj.top/Article/details/gtcokdrdhv.html

JS:   class User {}
来源：http://dali.jlsjyb.cn/Article/details/gtoputvoyi.html

TS:   class User { name: string = ""; }
来源：http://dali.xuanzx.com/Article/details/gtuftefvck.html

Java: class User {}
来源：http://dali.xinyue.icu/Article/details/gtwvkfauhs.html

Go:   type User struct { Name string }
来源：http://dali.kuanghao11.cn/Article/details/gtdehqtuhj.html

Ruby: class User; end
来源：http://dali.aibaodan.cn/Article/details/gtlkxzgupb.html

C#:   class User {}
来源：http://dali.sysykeji.top/Article/details/gtcqvrbppa.html

[G02] 构造函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtnnlhrywo.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.cucudq.cn/Article/details/gtopuvfsxe.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.ehwqpu.com/Article/details/gtqilgmkvi.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.chenlongwang.top/Article/details/gthyebaxgj.html

TS:   constructor(public name: string) {}
来源：http://dali.tian-w.cn/Article/details/gtiqhsecay.html

Java: User(String name) { this.name = name; }
来源：http://dali.yanxiufei.cn/Article/details/gtkfoqrzvn.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yongpay.top/Article/details/gttpxdqiur.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.dianchejie.cn/Article/details/gtrzqtxzqx.html

C#:   public User(string name) { Name = name; }
来源：http://dali.fzhhl.top/Article/details/gtgkygtumg.html

[G03] 实例属性
来源：http://dali.nanxinkj.top/Article/details/gtftnyznsd.html

Py:   self.name = "x"
来源：http://dali.iojbl.cn/Article/details/gtkngnoemr.html

PHP:  public string $name = "x";
来源：http://dali.vqdsnc.cn/Article/details/gtdmedykfn.html

JS:   this.name = "x";
来源：http://dali.ppjwa.cn/Article/details/gtlncappvp.html

TS:   name: string = "x";
来源：http://dali.birdmap.top/Article/details/gtgeyuxfcs.html

Java: private String name;
来源：http://dali.snrcjt.cn/Article/details/gtkgqussxa.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.aizwys.cn/Article/details/gtzzgkjzxi.html

Ruby: @name = "x"
来源：http://dali.yj202588.top/Article/details/gtqjajzawp.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.shuidangran.top/Article/details/gtoaskulkd.html

[G04] 定义方法
来源：http://dali.sxryk.cn/Article/details/gtptdtlbtw.html

Py:   def greet(self): return self.name
来源：http://dali.316326.xyz/Article/details/gtbmnvjaod.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.chenlongwang.top/Article/details/gtbxeosezl.html

JS:   greet() { return this.name; }
来源：http://dali.yonumen.top/Article/details/gtymqcwjxh.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhengqikj.top/Article/details/gtdhivxfah.html

Java: String greet() { return name; }
来源：http://dali.yj202588.top/Article/details/gtverptqbw.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hnqzz.top/Article/details/gtybhnomor.html

Ruby: def greet; @name; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvjabowob.html

C#:   public string Greet() => Name;
来源：http://dali.yj202588.top/Article/details/gtoibxonwh.html

[G05] 继承
来源：http://dali.gzhubu.top/Article/details/gteorztrob.html

Py:   class Admin(User): pass
来源：http://dali.jyoumei.cn/Article/details/gtbdphlwhs.html

PHP:  class Admin extends User {}
来源：http://dali.haohaochexian.top/Article/details/gtrpdzjcir.html

JS:   class Admin extends User {}
来源：http://dali.0kj1m.cn/Article/details/gtjaynbjim.html

TS:   class Admin extends User {}
来源：http://dali.daxiang520.top/Article/details/gttevuejpt.html

Java: class Admin extends User {}
来源：http://dali.redwolf501.top/Article/details/gtnsojwcdg.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.shuidangran.top/Article/details/gtzytthokd.html

Ruby: class Admin < User; end
来源：http://dali.tian-w.cn/Article/details/gtkgodwosw.html

C#:   class Admin : User {}
来源：http://dali.sxryk.cn/Article/details/gtbevqteet.html

[G06] 重写方法
来源：http://dali.tianlin.xyz/Article/details/gtjlhedvpv.html

Py:   def greet(self): return "admin"
来源：http://dali.yonumen.top/Article/details/gtzmgmivzr.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yj202588.top/Article/details/gtisupswuw.html

JS:   greet() { return "admin"; }
来源：http://dali.vqdsnc.cn/Article/details/gtnlplkuhu.html

TS:   greet(): string { return "admin"; }
来源：http://dali.xinyue.icu/Article/details/gtjoekmpzn.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtnbjtdoyv.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.shuidangran.top/Article/details/gtkilqjbwe.html

Ruby: def greet; "admin"; end
来源：http://dali.svipenyu.cn/Article/details/gtsmrhqxoj.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhoulong.xyz/Article/details/gtlrxdeciw.html

[G07] 调用父类方法
来源：http://dali.xuanzx.com/Article/details/gtjmulslfo.html

Py:   super().greet()
来源：http://dali.hnxiangtu.top/Article/details/gtpimlmdxl.html

PHP:  parent::greet();
来源：http://dali.cqqwz.cn/Article/details/gtfbadvktg.html

JS:   super.greet();
来源：http://dali.gzhubu.top/Article/details/gtzuhxsmno.html

TS:   super.greet();
来源：http://dali.hammf.cn/Article/details/gtkzyryidr.html

Java: super.greet();
来源：http://dali.cdnleiting.top/Article/details/gtcrwpjhdk.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hywenlv.cn/Article/details/gticovkkvq.html

Ruby: super
来源：http://dali.snrcjt.cn/Article/details/gtvfqblyqh.html

C#:   base.Greet();
来源：http://dali.yj202588.top/Article/details/gtxntexpmv.html

[G08] 静态方法与属性
来源：http://dali.pycfn.com/Article/details/gtsftysfnp.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhixingplan.top/Article/details/gtzohhjnhr.html

PHP:  public static function f() {}
来源：http://dali.birdmap.top/Article/details/gtrwatsmeu.html

JS:   static f() {}
来源：http://dali.gogol.net.cn/Article/details/gtjpbryfsz.html

TS:   static f(): void {}
来源：http://dali.ppjwa.cn/Article/details/gtjaptmpll.html

Java: static void f() {}
来源：http://dali.9152youxi.cn/Article/details/gtjketydpr.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.nwbrower.top/Article/details/gtdchqidei.html

Ruby: def self.f; end
来源：http://dali.hammf.cn/Article/details/gtklvgdrqi.html

C#:   public static void F() {}
来源：http://dali.ppjwa.cn/Article/details/gtlxmeyhkk.html

[G09] 接口 / 抽象类
来源：http://dali.cqqwz.cn/Article/details/gtcchathjg.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.guannengcc.top/Article/details/gtraikqlvr.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yueranfly.top/Article/details/gtuwhsxuqt.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hysaishi.cn/Article/details/gtaertujhl.html

TS:   interface Shape { area(): number; }
来源：http://dali.cucudq.cn/Article/details/gtqjethqct.html

Java: interface Shape { double area(); }
来源：http://dali.svipenyu.cn/Article/details/gtzgpxvqex.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.cheryme.top/Article/details/gtailyenst.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zycfv.cn/Article/details/gtyqitfimp.html

C#:   interface IShape { double Area(); }
来源：http://dali.chenzaomai.com/Article/details/gtqqnhekyk.html

[G10] 访问控制
来源：http://dali.yuxming.cn/Article/details/gtbhevhgrx.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.daria6918.cn/Article/details/gttacvjwuo.html

PHP:  public / protected / private
来源：http://dali.jinqigufen.top/Article/details/gtnujhyfic.html

JS:   #private 字段；其余公开
来源：http://dali.daria6918.cn/Article/details/gtaxlwaajc.html

TS:   public / protected / private
来源：http://dali.fengsongda.top/Article/details/gththepffn.html

Java: public / protected / private / 默认包级
来源：http://dali.guowangkeji.top/Article/details/gtfbcczcol.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.gaohongyu789.top/Article/details/gtzppojomr.html

Ruby: public / protected / private
来源：http://dali.sysykeji.top/Article/details/gtqldarntj.html

C#:   public / protected / private / internal
来源：http://dali.haohaochexian.top/Article/details/gtxgjdkrkv.html

[G11] getter / setter
来源：http://dali.jianghu66.top/Article/details/gthhjwarmd.html

Py:   @property 与 @x.setter
来源：http://dali.ppjwa.cn/Article/details/gtkfkkxrjl.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.chenzaomai.com/Article/details/gtivkzdtnq.html

JS:   get name() { return this._name; }
来源：http://dali.redwolf501.top/Article/details/gtdoljsajo.html

TS:   get name(): string { return this._name; }
来源：http://dali.jlsjyb.cn/Article/details/gtijuruqph.html

Java: public String getName() { return name; }
来源：http://dali.redwolf501.top/Article/details/gtkgbiglly.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.cheryme.top/Article/details/gtktbsqkow.html

Ruby: attr_accessor :name
来源：http://dali.hnqzz.top/Article/details/gtpoqsdbyf.html

C#:   public string Name { get; set; }
来源：http://dali.daxiang520.top/Article/details/gtlfmhdwpe.html

[G12] 对象转字符串
来源：http://dali.yvedp.cn/Article/details/gtiikfoadm.html

Py:   def __str__(self): return self.name
来源：http://dali.zhoulong.xyz/Article/details/gtvsugarqf.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.9152youxi.cn/Article/details/gtwqgmdvfy.html

JS:   toString() { return this.name; }
来源：http://dali.jianghu66.top/Article/details/gtkmhtfvlw.html

TS:   toString(): string { return this.name; }
来源：http://dali.9152youxi.cn/Article/details/gtisbnsifa.html

Java: @Override public String toString() { return name; }
来源：http://dali.yuxming.cn/Article/details/gtqhpcbdxc.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.meibo888.top/Article/details/gtynfyihej.html

Ruby: def to_s; @name; end
来源：http://dali.zycfv.cn/Article/details/gtdomhpqfg.html

C#:   public override string ToString() => Name;
来源：http://dali.gzhubu.top/Article/details/gtmoepcvfc.html

[G13] 判断对象类型
来源：http://dali.jiagoushi.top/Article/details/gtbtqjwiru.html

Py:   isinstance(u, User)
来源：http://dali.pycfn.com/Article/details/gtzgjzlchj.html

PHP:  $u instanceof User
来源：http://dali.sxryk.cn/Article/details/gtcvpqvjpw.html

JS:   u instanceof User
来源：http://dali.cdnleiting.top/Article/details/gtufjovsmb.html

TS:   u instanceof User
来源：http://dali.yonumen.top/Article/details/gttdrhjulm.html

Java: u instanceof User
来源：http://dali.havefunace.top/Article/details/gthsgblsfe.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.bjfxy.top/Article/details/gtyzrjkarf.html

Ruby: u.is_a?(User)
来源：http://dali.dianchejie.cn/Article/details/gtiunrpigf.html

C#:   u is User
来源：http://dali.316326.xyz/Article/details/gtbncrkipy.html

[G14] 数据类 / record
来源：http://dali.sysykeji.top/Article/details/gtkbuqpdmb.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.c1oappe.top/Article/details/gtntqnzkms.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.wangshuangyany.cn/Article/details/gtysyqslpj.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhongyouzk.top/Article/details/gtmenpyhhq.html

TS:   type User = { name: string; age: number };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrsjvdbrd.html

Java: record User(String name, int age) {}
来源：http://dali.9152youxi.cn/Article/details/gteeptgquq.html

Go:   type User struct { Name string; Age int }
来源：http://dali.wangshuangyany.cn/Article/details/gtxsyygblb.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yongpay.top/Article/details/gtqixwlrkn.html

C#:   record User(string Name, int Age);
来源：http://dali.ydzc1.top/Article/details/gtehnrudwi.html

[G15] 枚举
来源：http://dali.xziqi.cn/Article/details/gtojbhnjhp.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.tian-w.cn/Article/details/gtfzhmdyxj.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jlsjyb.cn/Article/details/gtnomyxrzp.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.xylfe.cn/Article/details/gtwgvqxaqh.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yvedp.cn/Article/details/gtjlafkrja.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhongyouzk.top/Article/details/gtplrdbiym.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yangfankeji.com/Article/details/gtppolzjgs.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yuanzhike.top/Article/details/gthmujwsuv.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cheryme.top/Article/details/gtlrhugfgi.html

[G16] 对象转数组 / 字典
来源：http://dali.redwolf501.top/Article/details/gtyfqudnhw.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.quarkkingdee.top/Article/details/gtzpksurha.html

PHP:  get_object_vars($obj);
来源：http://dali.zhixingplan.top/Article/details/gtivoyoooy.html

JS:   Object.entries(obj)
来源：http://dali.yueranfly.top/Article/details/gtjnutnskm.html

TS:   Object.entries(obj)
来源：http://dali.jiagoushi.top/Article/details/gtkucqpfww.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.sufxvd.cn/Article/details/gtwslqcyrn.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.ppjwa.cn/Article/details/gtinsxlsxa.html

Ruby: obj.instance_variables
来源：http://dali.hywenlv.cn/Article/details/gtsgfxycgl.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.haohaochexian.top/Article/details/gttvjulivj.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtcativrfx.html

H. 异常与错误处理
来源：http://dali.fengsongda.top/Article/details/gtxcxijfxs.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtqumudkiv.html

[H01] try / catch 基础
来源：http://dali.sweek.top/Article/details/gttmcbrhvx.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jianghu66.top/Article/details/gtaurjcmci.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.cucudq.cn/Article/details/gteczoxwju.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.ybcxt.top/Article/details/gtxvgcrdsg.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.sweek.top/Article/details/gtyvjuoawo.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jyoumei.cn/Article/details/gtmkaczaef.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.ydzc1.top/Article/details/gtcduesews.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.mhx1999.top/Article/details/gtdwlnizyj.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.aizwys.cn/Article/details/gtbzmxovhj.html

[H02] finally / ensure 收尾
来源：http://dali.bjfxy.top/Article/details/gtwtxrklxz.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jinqigufen.top/Article/details/gtjofsmldo.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.guannengcc.top/Article/details/gtrqkvomwl.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.xuetiantiany.cn/Article/details/gtruqfvgdt.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.ybcxt.top/Article/details/gtsnqtdonh.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.xziqi.cn/Article/details/gtnmxfvgui.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.c1oappe.top/Article/details/gtnvlcbfxf.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.hongshengwenyu.top/Article/details/gtahpptsyp.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.daria6918.cn/Article/details/gtyzqspwzv.html

[H03] 主动抛出异常
来源：http://dali.zhoulong.xyz/Article/details/gtrypxdhov.html

Py:   raise ValueError("错误信息")
来源：http://dali.cucudq.cn/Article/details/gtnjkgsvhr.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jlsjyb.cn/Article/details/gtvcnyokwr.html

JS:   throw new Error("错误信息");
来源：http://dali.xuanzx.com/Article/details/gtzlelebvy.html

TS:   throw new Error("错误信息");
来源：http://dali.xylfe.cn/Article/details/gtsemqqhjg.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.guowangkeji.top/Article/details/gtuedsvtoe.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.cdnleiting.top/Article/details/gtdwsfmjcd.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hywenlv.cn/Article/details/gtkkgdfxma.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.dianchejie.cn/Article/details/gthuqpgxdh.html

[H04] 自定义异常类型
来源：http://dali.tian-w.cn/Article/details/gtxrvazhvn.html

Py:   class MyError(Exception): pass
来源：http://dali.hfpthk.cn/Article/details/gtmaawhxog.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.kuanghao11.cn/Article/details/gtrwumstej.html

JS:   class MyError extends Error {}
来源：http://dali.zycfv.cn/Article/details/gtskkjcecl.html

TS:   class MyError extends Error {}
来源：http://dali.smart0.xyz/Article/details/gtgccjgrox.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yongpay.top/Article/details/gtnudaobsa.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.sufxvd.cn/Article/details/gtgyybsxii.html

Ruby: class MyError < StandardError; end
来源：http://dali.ydzc1.top/Article/details/gtyizdbnfu.html

C#:   class MyException : Exception {}
来源：http://dali.zhiwuduotai.top/Article/details/gtnszjigfj.html

[H05] 捕获特定类型
来源：http://dali.guowangkeji.top/Article/details/gtjgdviesi.html

Py:   except ValueError as e:
来源：http://dali.zhixingplan.top/Article/details/gterluphqo.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.bjfxy.top/Article/details/gtobomybze.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.smart0.xyz/Article/details/gtanwezlnp.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yvedp.cn/Article/details/gtplhjmifl.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.daria6918.cn/Article/details/gtbrwnyewn.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jinqigufen.top/Article/details/gthsfqvncb.html

Ruby: rescue ArgumentError => e
来源：http://dali.snrcjt.cn/Article/details/gtveifsjnw.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.smart0.xyz/Article/details/gtqwztwpns.html

[H06] 可选值 / 空值安全访问
来源：http://dali.ivvv.top/Article/details/gthqxoplws.html

Py:   value = d.get("k") or default
来源：http://dali.jqgfzy.top/Article/details/gtgypahhru.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jyoumei.cn/Article/details/gtzcpipivc.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.dashuyun.cn/Article/details/gtmouvdmbi.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.havefunace.top/Article/details/gtkocymfhu.html


<!-- 参考信息 -->