代发 wailian999

[F01] 读取整个文件
来源：http://dali.chenjidiqi.icu/Article/details/gtvlzqzaty.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jlsjyb.cn/Article/details/gtidzxpekb.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yj202588.top/Article/details/gthvbluvre.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.pengpengdd.cyou/Article/details/gtdlnxckyq.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.tian-w.cn/Article/details/gthbrcicuz.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.dianchejie.cn/Article/details/gtxvpyyuhd.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.shanyushiyangkeji.top/Article/details/gtibvazbcy.html

Ruby: File.read("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtpebgknqj.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxipyoaxd.html

[F02] 逐行读取文件
来源：http://dali.ppjwa.cn/Article/details/gtzfwmgugi.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.svipenyu.cn/Article/details/gtbvlicsqf.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.hongshengwenyu.top/Article/details/gtnaomyygj.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.dianchejie.cn/Article/details/gtwrycbbax.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.nanxuanxn.top/Article/details/gtrcqlkcxm.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jianghu66.top/Article/details/gttuirhvtt.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yongpay.top/Article/details/gtqspriehx.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hywenlv.cn/Article/details/gtlnosaqba.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.gzhubu.top/Article/details/gteezmflue.html

[F03] 写入文件（覆盖）
来源：http://dali.wangshuangyany.cn/Article/details/gtnlmhmaau.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.snrcjt.cn/Article/details/gtyzpjclgr.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.nwbrower.top/Article/details/gtpfdqbluf.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gtkobbzlef.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.smart0.xyz/Article/details/gttxtqrimg.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.fzhhl.top/Article/details/gtxafonpbd.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.chenjidiqi.icu/Article/details/gtafbvpotg.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.ybcxt.top/Article/details/gtmhvvvedt.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.ppjwa.cn/Article/details/gtmvywkarr.html

[F04] 追加写入文件
来源：http://dali.zycfv.cn/Article/details/gthibesubk.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.mhx1999.top/Article/details/gtpopwibfd.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.cashguo.top/Article/details/gtkuolxxhl.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.snrcjt.cn/Article/details/gtyppwsbcp.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hysaishi.cn/Article/details/gtsbbmliyx.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.gaohongyu789.top/Article/details/gtnsxhnjxy.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.havefunace.top/Article/details/gtkzcdhfyd.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqdntjkia.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yvedp.cn/Article/details/gtngfgjtjj.html

[F05] 判断文件或目录是否存在
来源：http://dali.sufxvd.cn/Article/details/gtgxoacqtj.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.nanxinkj.top/Article/details/gtrjaecrnh.html

PHP:  file_exists("a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gtsxnuxktl.html

JS:   fs.existsSync("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtbjygivsl.html

TS:   fs.existsSync("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtjzgukkjr.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zycfv.cn/Article/details/gttoniqyit.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yangfankeji.com/Article/details/gtzzafzajz.html

Ruby: File.exist?("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtoqkmapba.html

C#:   File.Exists("a.txt")
来源：http://dali.ydzc1.top/Article/details/gtigsdzxsl.html

[F06] 删除文件
来源：http://dali.yueranfly.top/Article/details/gtvmfeppax.html

Py:   os.remove("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtqavcyhth.html

PHP:  unlink("a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gtrtqfimnq.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtxzslbiay.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yj202588.top/Article/details/gtqorudcpg.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhengqikj.top/Article/details/gtwqukaaut.html

Go:   os.Remove("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtxxystqzq.html

Ruby: File.delete("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtauvuydrv.html

C#:   File.Delete("a.txt");
来源：http://dali.ydzc1.top/Article/details/gtjvvyteuy.html

[F07] 创建目录（含多级）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxalinkdk.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.hfpthk.cn/Article/details/gttdmouwfv.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jyoumei.cn/Article/details/gtoytoznul.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yangfankeji.com/Article/details/gtqpycqagy.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ydzc1.top/Article/details/gtfsgnisoo.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoieknucv.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.andypj.xyz/Article/details/gtrthpghpn.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.wangshuangyany.cn/Article/details/gtsmssgaoj.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhiwuduotai.top/Article/details/gtlleijgug.html

[F08] 遍历目录
来源：http://dali.xuetiantiany.cn/Article/details/gtcdmtwwmz.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.hammf.cn/Article/details/gtgmuolbds.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.ehwqpu.com/Article/details/gtswbytick.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhengqikj.top/Article/details/gttabqzbcc.html

TS:   fs.readdirSync("dir")
来源：http://dali.yangfankeji.com/Article/details/gtmbpclzmy.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.ehwqpu.com/Article/details/gtcgugaklk.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhiwuduotai.top/Article/details/gthnuaiwdw.html

Ruby: Dir.children("dir")
来源：http://dali.yuxming.cn/Article/details/gtmuvhohek.html

C#:   Directory.GetFiles("dir")
来源：http://dali.iojbl.cn/Article/details/gthxzgxqxf.html

[F09] 获取文件大小
来源：http://dali.9152youxi.cn/Article/details/gtesqqgsii.html

Py:   os.path.getsize("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtukgzkyly.html

PHP:  filesize("a.txt");
来源：http://dali.xylfe.cn/Article/details/gtsgxaajrz.html

JS:   fs.statSync("a.txt").size
来源：http://dali.tian-w.cn/Article/details/gtbnsrgryh.html

TS:   fs.statSync("a.txt").size
来源：http://dali.gzhubu.top/Article/details/gtnzcaigyc.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yj20258888.top/Article/details/gtqbwatzsr.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jinqigufen.top/Article/details/gtahkqmnfd.html

Ruby: File.size("a.txt")
来源：http://dali.316326.xyz/Article/details/gtwovoruxz.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.shangyingyoupin.top/Article/details/gtmflrbitg.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hammf.cn/Article/details/gtcvxyczii.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.smart0.xyz/Article/details/gtgzuvmqlm.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.cdnleiting.top/Article/details/gtbppcisnf.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.c1oappe.top/Article/details/gtbvqqrrty.html

TS:   path.extname("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtysnrwsjs.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yuanzhike.top/Article/details/gtfqxtzlyg.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yj20258888.top/Article/details/gthmnhlysl.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtpwgkdiyh.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.sxryk.cn/Article/details/gtkfzgzdoi.html

[F11] 复制与移动文件
来源：http://dali.guannengcc.top/Article/details/gtdjwdndso.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.sysykeji.top/Article/details/gtpkyvcyfn.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.guowangkeji.top/Article/details/gtadgcrlmz.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jiagoushi.top/Article/details/gtjvdgpabm.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtipjabhkm.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yuanzhike.top/Article/details/gtzzqclzgg.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jqgufenzy.top/Article/details/gtjrxuojqm.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.ydzc1.top/Article/details/gtyfdxckji.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.wangshuangyany.cn/Article/details/gtfupwyuxu.html

[F12] CSV 读写
来源：http://dali.sweek.top/Article/details/gteagfvbmy.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.chenzaomai.com/Article/details/gtftxsceua.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.dashuyun.cn/Article/details/gttndfydzc.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.0kj1m.cn/Article/details/gtkgcnjyzp.html

TS:   // 同上
来源：http://dali.yj20258.top/Article/details/gthstupofs.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.nanxuanxn.top/Article/details/gteuwefkcc.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.shuidangran.top/Article/details/gtzzkayari.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.nwbrower.top/Article/details/gtuxmtedwk.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yangfankeji.com/Article/details/gtwwgttzgy.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtxkzylarg.html

G. 面向对象
来源：http://dali.hysaishi.cn/Article/details/gtubxrursg.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtklxpylfz.html

[G01] 定义类
来源：http://dali.ydzc1.top/Article/details/gtjtyewdbh.html

Py:   class User: pass
来源：http://dali.jlsjyb.cn/Article/details/gtgbkgyqjg.html

PHP:  class User {}
来源：http://dali.9152youxi.cn/Article/details/gtimsreutk.html

JS:   class User {}
来源：http://dali.zhoulong.xyz/Article/details/gtxfhbnexa.html

TS:   class User { name: string = ""; }
来源：http://dali.jianghu66.top/Article/details/gtglhmgtdv.html

Java: class User {}
来源：http://dali.jianghu66.top/Article/details/gthqsnubbf.html

Go:   type User struct { Name string }
来源：http://dali.hnxiangtu.top/Article/details/gtizifpdel.html

Ruby: class User; end
来源：http://dali.chenzaomai.com/Article/details/gtrfnvutgy.html

C#:   class User {}
来源：http://dali.zdqjudy.top/Article/details/gtmqdewkbr.html

[G02] 构造函数
来源：http://dali.sxryk.cn/Article/details/gtgpdzhpsk.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.chenlongwang.top/Article/details/gtlzigpstn.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jyoumei.cn/Article/details/gtgppmrjgn.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhongyouzk.top/Article/details/gtgccyhbel.html

TS:   constructor(public name: string) {}
来源：http://dali.zhijiandao.cn/Article/details/gtdraguvra.html

Java: User(String name) { this.name = name; }
来源：http://dali.shuidangran.top/Article/details/gtpdsuovur.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yj202588.top/Article/details/gtvuzzurys.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.snrcjt.cn/Article/details/gtcqubyiya.html

C#:   public User(string name) { Name = name; }
来源：http://dali.hnxiangtu.top/Article/details/gtmsogwydn.html

[G03] 实例属性
来源：http://dali.jqgufenzy.top/Article/details/gtbmnxuhtt.html

Py:   self.name = "x"
来源：http://dali.fengsongda.top/Article/details/gtfuzxomoj.html

PHP:  public string $name = "x";
来源：http://dali.yvedp.cn/Article/details/gtygxoxwwb.html

JS:   this.name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gtfubzynxg.html

TS:   name: string = "x";
来源：http://dali.cheryme.top/Article/details/gtavyhxoge.html

Java: private String name;
来源：http://dali.guannengcc.top/Article/details/gtzhucglzn.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdyuggozh.html

Ruby: @name = "x"
来源：http://dali.dashuyun.cn/Article/details/gtbwgzixen.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpwkcddjw.html

[G04] 定义方法
来源：http://dali.jqgfzy.top/Article/details/gtpocascgq.html

Py:   def greet(self): return self.name
来源：http://dali.tianlin.xyz/Article/details/gtpantkslx.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.havefunace.top/Article/details/gtfcusjuev.html

JS:   greet() { return this.name; }
来源：http://dali.jiagoushi.top/Article/details/gtbouxgoxr.html

TS:   greet(): string { return this.name; }
来源：http://dali.nwbrower.top/Article/details/gtnzunuynn.html

Java: String greet() { return name; }
来源：http://dali.haohaochexian.top/Article/details/gtuxdtmalp.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jqgfzy.top/Article/details/gtfuhixlan.html

Ruby: def greet; @name; end
来源：http://dali.hfpthk.cn/Article/details/gtcaxixvvh.html

C#:   public string Greet() => Name;
来源：http://dali.yanxiufei.cn/Article/details/gteshdnnzd.html

[G05] 继承
来源：http://dali.zhaomingkeji.xyz/Article/details/gtauvlrpzv.html

Py:   class Admin(User): pass
来源：http://dali.tianlin.xyz/Article/details/gtvoxvpskz.html

PHP:  class Admin extends User {}
来源：http://dali.gzhubu.top/Article/details/gtzyeuhirx.html

JS:   class Admin extends User {}
来源：http://dali.316326.xyz/Article/details/gttsentddi.html

TS:   class Admin extends User {}
来源：http://dali.yuxming.cn/Article/details/gtjjjxyzpn.html

Java: class Admin extends User {}
来源：http://dali.havefunace.top/Article/details/gtvkkbwhal.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hongshengwenyu.top/Article/details/gtgmjxpaat.html

Ruby: class Admin < User; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlzyysnmf.html

C#:   class Admin : User {}
来源：http://dali.jqgufenzy.top/Article/details/gtfmkprzqk.html

[G06] 重写方法
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkkxmitdq.html

Py:   def greet(self): return "admin"
来源：http://dali.wangdashe.top/Article/details/gtzfjfhwie.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.0kj1m.cn/Article/details/gtswvdeszm.html

JS:   greet() { return "admin"; }
来源：http://dali.cheryme.top/Article/details/gtqxzniyry.html

TS:   greet(): string { return "admin"; }
来源：http://dali.havefunace.top/Article/details/gttbiapsqy.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.aizwys.cn/Article/details/gtmbrpbwzy.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yongpay.top/Article/details/gtfgplyzwf.html

Ruby: def greet; "admin"; end
来源：http://dali.birdmap.top/Article/details/gtqdfeehum.html

C#:   public override string Greet() => "admin";
来源：http://dali.yvedp.cn/Article/details/gtjzhsayxw.html

[G07] 调用父类方法
来源：http://dali.meibo888.top/Article/details/gtymsvxhqf.html

Py:   super().greet()
来源：http://dali.jianghu66.top/Article/details/gtfyzwsldo.html

PHP:  parent::greet();
来源：http://dali.nanxuanxn.top/Article/details/gtfmlpdoel.html

JS:   super.greet();
来源：http://dali.andypj.xyz/Article/details/gturfckxgs.html

TS:   super.greet();
来源：http://dali.sxryk.cn/Article/details/gtajiudrwn.html

Java: super.greet();
来源：http://dali.xziqi.cn/Article/details/gtarrtiirr.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yj202588.top/Article/details/gtjopkbjjl.html

Ruby: super
来源：http://dali.nwbrower.top/Article/details/gttgmnqsfm.html

C#:   base.Greet();
来源：http://dali.gogol.net.cn/Article/details/gtsssfyupg.html

[G08] 静态方法与属性
来源：http://dali.shangyingyoupin.top/Article/details/gtpqdkgzau.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hfpthk.cn/Article/details/gtsokltxxq.html

PHP:  public static function f() {}
来源：http://dali.wangdashe.top/Article/details/gtdgfbxbdp.html

JS:   static f() {}
来源：http://dali.smart0.xyz/Article/details/gtuqfkcviu.html

TS:   static f(): void {}
来源：http://dali.yongpay.top/Article/details/gtxsxpcnsl.html

Java: static void f() {}
来源：http://dali.jiagoushi.top/Article/details/gtreuhwfni.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiaknnbjt.html

Ruby: def self.f; end
来源：http://dali.zdqjudy.top/Article/details/gtljnogcsg.html

C#:   public static void F() {}
来源：http://dali.gotoacloud.top/Article/details/gtalqohqgx.html

[G09] 接口 / 抽象类
来源：http://dali.xuanzx.com/Article/details/gtnytvyjwf.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.smart0.xyz/Article/details/gtejnlvhek.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.fzhhl.top/Article/details/gtopotrfrp.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.nanxinkj.top/Article/details/gtqziszcwc.html

TS:   interface Shape { area(): number; }
来源：http://dali.iojbl.cn/Article/details/gttjhouyhm.html

Java: interface Shape { double area(); }
来源：http://dali.mhx1999.top/Article/details/gtpvehvgkz.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hysaishi.cn/Article/details/gtscpluzvq.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xziqi.cn/Article/details/gtudbhpwcv.html

C#:   interface IShape { double Area(); }
来源：http://dali.xuanzx.com/Article/details/gtibqnduwk.html

[G10] 访问控制
来源：http://dali.daxiang520.top/Article/details/gtpklbybww.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.daria6918.cn/Article/details/gtgjsfcnie.html

PHP:  public / protected / private
来源：http://dali.mhx1999.top/Article/details/gthrvugjog.html

JS:   #private 字段；其余公开
来源：http://dali.shuidangran.top/Article/details/gtonmakhgm.html

TS:   public / protected / private
来源：http://dali.yj20258888.top/Article/details/gtklqfpaym.html

Java: public / protected / private / 默认包级
来源：http://dali.316326.xyz/Article/details/gtyrzlhluz.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.shangyingyoupin.top/Article/details/gthtmypais.html

Ruby: public / protected / private
来源：http://dali.tian-w.cn/Article/details/gtclypqoyd.html

C#:   public / protected / private / internal
来源：http://dali.hfpthk.cn/Article/details/gtjblmeidp.html

[G11] getter / setter
来源：http://dali.gzhubu.top/Article/details/gtdjuvuend.html

Py:   @property 与 @x.setter
来源：http://dali.jinqigfzy.top/Article/details/gtwxlkchgr.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.sysykeji.top/Article/details/gttlnqgkgn.html

JS:   get name() { return this._name; }
来源：http://dali.zhoulong.xyz/Article/details/gtdlwhhixq.html

TS:   get name(): string { return this._name; }
来源：http://dali.hysaishi.cn/Article/details/gtfbyhbrye.html

Java: public String getName() { return name; }
来源：http://dali.yueranfly.top/Article/details/gtikpmzaeg.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.hysaishi.cn/Article/details/gtyiqotvdh.html

Ruby: attr_accessor :name
来源：http://dali.jinqigfzy.top/Article/details/gtazfudgut.html

C#:   public string Name { get; set; }
来源：http://dali.feifeiyinyue.top/Article/details/gtegcsypnd.html

[G12] 对象转字符串
来源：http://dali.kuanghao11.cn/Article/details/gtrqpqtmwc.html

Py:   def __str__(self): return self.name
来源：http://dali.ivvv.top/Article/details/gtkjbqugqc.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhoulong.xyz/Article/details/gtdyczwtax.html

JS:   toString() { return this.name; }
来源：http://dali.zhoulong.xyz/Article/details/gtszfodkyg.html

TS:   toString(): string { return this.name; }
来源：http://dali.mhx1999.top/Article/details/gtvpjlkzzm.html

Java: @Override public String toString() { return name; }
来源：http://dali.redwolf501.top/Article/details/gtnfvkwwvs.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.andypj.xyz/Article/details/gtpoldycar.html

Ruby: def to_s; @name; end
来源：http://dali.cqqwz.cn/Article/details/gtkgvsqogo.html

C#:   public override string ToString() => Name;
来源：http://dali.9152youxi.cn/Article/details/gtxkceauok.html

[G13] 判断对象类型
来源：http://dali.gzhubu.top/Article/details/gtcxtrlbro.html

Py:   isinstance(u, User)
来源：http://dali.hysaishi.cn/Article/details/gtngqhfyuh.html

PHP:  $u instanceof User
来源：http://dali.fzhhl.top/Article/details/gtcubhimwv.html

JS:   u instanceof User
来源：http://dali.hfpthk.cn/Article/details/gtkyumaoix.html

TS:   u instanceof User
来源：http://dali.jyoumei.cn/Article/details/gtfwgpvfue.html

Java: u instanceof User
来源：http://dali.xuetiantiany.cn/Article/details/gtimqbsqrm.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhoulong.xyz/Article/details/gtwmnujaaz.html

Ruby: u.is_a?(User)
来源：http://dali.zhoulong.xyz/Article/details/gttfqlwpcq.html

C#:   u is User
来源：http://dali.xuetiantiany.cn/Article/details/gtubpkdasp.html

[G14] 数据类 / record
来源：http://dali.cqqwz.cn/Article/details/gtlloftwbf.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jinyuanbaomall.cn/Article/details/gtviawcade.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.chenlongwang.top/Article/details/gtsedxvlzm.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.ydzc1.top/Article/details/gtpfazfhxk.html

TS:   type User = { name: string; age: number };
来源：http://dali.aibaodan.cn/Article/details/gtvfxdjovh.html

Java: record User(String name, int age) {}
来源：http://dali.svipenyu.cn/Article/details/gtrocdrkob.html

Go:   type User struct { Name string; Age int }
来源：http://dali.fengsongda.top/Article/details/gtjfwaphhr.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yangfankeji.com/Article/details/gtjqhrjkiq.html

C#:   record User(string Name, int Age);
来源：http://dali.ybcxt.top/Article/details/gteyscjfkf.html

[G15] 枚举
来源：http://dali.yangfankeji.com/Article/details/gttftadthn.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yj20258888.top/Article/details/gtueyqijkt.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhongyouzk.top/Article/details/gtrkraprcr.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhongyouzk.top/Article/details/gtlplamopk.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.daxiang520.top/Article/details/gtcqelfezv.html

Java: enum Color { RED, GREEN }
来源：http://dali.ivvv.top/Article/details/gteakeusgs.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yj202588.top/Article/details/gtinmpsire.html

Ruby: Color = %i[red green].freeze
来源：http://dali.feifeiyinyue.top/Article/details/gtaqroxhod.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.wangshuangyany.cn/Article/details/gttfdohchj.html

[G16] 对象转数组 / 字典
来源：http://dali.cqqwz.cn/Article/details/gtkuhsmvtg.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.dashuyun.cn/Article/details/gtghwccvpy.html

PHP:  get_object_vars($obj);
来源：http://dali.aizwys.cn/Article/details/gthpeqbbnk.html

JS:   Object.entries(obj)
来源：http://dali.sxryk.cn/Article/details/gthoyatvzf.html

TS:   Object.entries(obj)
来源：http://dali.jinqigfzy.top/Article/details/gtldrqsoki.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhoulong.xyz/Article/details/gtntfydwpc.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.fzhhl.top/Article/details/gtakqhqhem.html

Ruby: obj.instance_variables
来源：http://dali.hnxiangtu.top/Article/details/gtdjqajqhe.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.tianlin.xyz/Article/details/gtglprxfro.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtnbuqoqbf.html

H. 异常与错误处理
来源：http://dali.snrcjt.cn/Article/details/gthetfubtu.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtndzgrisd.html

[H01] try / catch 基础
来源：http://dali.sxryk.cn/Article/details/gtebmmhhic.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.fengsongda.top/Article/details/gtzyugzzhv.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yonumen.top/Article/details/gtmjgiajpt.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yvedp.cn/Article/details/gtuszhnbfo.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.xziqi.cn/Article/details/gtbweiawvk.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zdqjudy.top/Article/details/gtlgsdpadq.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yj20258888.top/Article/details/gtlxxrrphw.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.9152youxi.cn/Article/details/gtqzaxmlwn.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.tanke756.top/Article/details/gtpwsyzvtf.html

[H02] finally / ensure 收尾
来源：http://dali.yj20258.top/Article/details/gtuapkicob.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhengqikj.top/Article/details/gtyvbnvvcz.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yj202588.top/Article/details/gtbzxppbfu.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.nanxinkj.top/Article/details/gtnirydcfi.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.9152youxi.cn/Article/details/gtrixxtfyl.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.nwbrower.top/Article/details/gtnemhjyia.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.sufxvd.cn/Article/details/gtgrgtsmjn.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.hongshengwenyu.top/Article/details/gtaxyzbhla.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zdqjudy.top/Article/details/gtnhkihogt.html

[H03] 主动抛出异常
来源：http://dali.ywan-chungtsiang.top/Article/details/gtabvrdekr.html

Py:   raise ValueError("错误信息")
来源：http://dali.nanxuanxn.top/Article/details/gtczmmdkij.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhoulong.xyz/Article/details/gtwkvheogb.html

JS:   throw new Error("错误信息");
来源：http://dali.shangyingyoupin.top/Article/details/gtetoehefd.html

TS:   throw new Error("错误信息");
来源：http://dali.daxiang520.top/Article/details/gtdgfqpofr.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtclvgavzh.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.guannengcc.top/Article/details/gtjqwwzgag.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.cucudq.cn/Article/details/gtzqusorsp.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.wangdashe.top/Article/details/gtshkrpfll.html

[H04] 自定义异常类型
来源：http://dali.yangfankeji.com/Article/details/gthmefdfuc.html

Py:   class MyError(Exception): pass
来源：http://dali.yuxming.cn/Article/details/gtozrzezfm.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.vqdsnc.cn/Article/details/gtnrnuzzni.html

JS:   class MyError extends Error {}
来源：http://dali.sufxvd.cn/Article/details/gtijyosjha.html

TS:   class MyError extends Error {}
来源：http://dali.ydzc1.top/Article/details/gtfqjbxood.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yvedp.cn/Article/details/gtqxobecbz.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.gaohongyu789.top/Article/details/gthtfjiwdi.html

Ruby: class MyError < StandardError; end
来源：http://dali.vqdsnc.cn/Article/details/gtmkffxizw.html

C#:   class MyException : Exception {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtppiliyqm.html

[H05] 捕获特定类型
来源：http://dali.tian-w.cn/Article/details/gtzddutixb.html

Py:   except ValueError as e:
来源：http://dali.gogol.net.cn/Article/details/gtzdzqclzn.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.daxiang520.top/Article/details/gtqlutrkko.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.iojbl.cn/Article/details/gtuvyssbmn.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.fzhhl.top/Article/details/gtndybhxiy.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.wangdashe.top/Article/details/gtsockpwjh.html


<!-- 参考信息 -->