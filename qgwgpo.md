代发 wailian999

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.ydzc1.top/Article/details/gtavewofqm.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.quarkkingdee.top/Article/details/gtksvuvdxp.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhoulong.xyz/Article/details/gtzrdxulov.html

Ruby: File.read("a.txt")
来源：http://dali.cashguo.top/Article/details/gthufpxulf.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzuhntfmn.html

[F02] 逐行读取文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlhgpebzt.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yonumen.top/Article/details/gtfdojgvbz.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.hfpthk.cn/Article/details/gthbhbobub.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.kuanghao11.cn/Article/details/gtoljmewcs.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ivvv.top/Article/details/gteacsxvck.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jqgufenzy.top/Article/details/gttanqjtbq.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.redwolf501.top/Article/details/gtprbpcqvd.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jyoumei.cn/Article/details/gtwtfejrxu.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.pycfn.com/Article/details/gtwfslphnx.html

[F03] 写入文件（覆盖）
来源：http://dali.yueranfly.top/Article/details/gtzustgtse.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhiwuduotai.top/Article/details/gtnnlburnc.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.aibaodan.cn/Article/details/gthfsvwhng.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yj20258888.top/Article/details/gthnvteksy.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yuxming.cn/Article/details/gtitzqvxzp.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.xuetiantiany.cn/Article/details/gtlschjngf.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhixingplan.top/Article/details/gtfviryldp.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteqelwbir.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gtwidekzpp.html

[F04] 追加写入文件
来源：http://dali.wangdashe.top/Article/details/gtvnraxewy.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.chenlongwang.top/Article/details/gtfaskfbwb.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.chenzaomai.com/Article/details/gtlzmhalts.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.pycfn.com/Article/details/gtlxujlsmr.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.fengsongda.top/Article/details/gtzgqvzqje.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.haohaochexian.top/Article/details/gtskxycpsh.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.dashuyun.cn/Article/details/gtmahshafc.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yongpay.top/Article/details/gtkcslhvrd.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.shuidangran.top/Article/details/gtpgkxaawg.html

[F05] 判断文件或目录是否存在
来源：http://dali.fengsongda.top/Article/details/gtrivlldcl.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yangfankeji.com/Article/details/gtrtcifwgo.html

PHP:  file_exists("a.txt");
来源：http://dali.yueranfly.top/Article/details/gtzxjdfxlb.html

JS:   fs.existsSync("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtnhkumflf.html

TS:   fs.existsSync("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtuedfpofs.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.nanxinkj.top/Article/details/gtaxhalwwg.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.birdmap.top/Article/details/gtgabnczcz.html

Ruby: File.exist?("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtlqgxlgdd.html

C#:   File.Exists("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtzwipzwfy.html

[F06] 删除文件
来源：http://dali.xinyue.icu/Article/details/gtgrjyicno.html

Py:   os.remove("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtdgxyqyrd.html

PHP:  unlink("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gthmeqowox.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtvcphfgar.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.ydzc1.top/Article/details/gturwnthgt.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.ppjwa.cn/Article/details/gtasmzoqjw.html

Go:   os.Remove("a.txt")
来源：http://dali.pycfn.com/Article/details/gtqidqetbs.html

Ruby: File.delete("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtwegumhfj.html

C#:   File.Delete("a.txt");
来源：http://dali.xinyue.icu/Article/details/gthktskmnp.html

[F07] 创建目录（含多级）
来源：http://dali.gotoacloud.top/Article/details/gtikykejwm.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yj20258.top/Article/details/gtqjtgixbf.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yangfankeji.com/Article/details/gtbboweuim.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cashguo.top/Article/details/gtarpmfamw.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sufxvd.cn/Article/details/gthwyysfvd.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.cqqwz.cn/Article/details/gtilyeuucm.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.cqqwz.cn/Article/details/gtkojccpuv.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yueranfly.top/Article/details/gtwqfniiuk.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.iojbl.cn/Article/details/gtrowkbclq.html

[F08] 遍历目录
来源：http://dali.gzhubu.top/Article/details/gtgktzlwza.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthhrbzsue.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.0kj1m.cn/Article/details/gtuitwptlq.html

JS:   fs.readdirSync("dir")
来源：http://dali.c1oappe.top/Article/details/gtkddxgypp.html

TS:   fs.readdirSync("dir")
来源：http://dali.guowangkeji.top/Article/details/gtgngbmhvf.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.nwbrower.top/Article/details/gtsfrnfvyg.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.cucudq.cn/Article/details/gtlngopngs.html

Ruby: Dir.children("dir")
来源：http://dali.tanke756.top/Article/details/gtpbwnmful.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yj202588.top/Article/details/gtawblprai.html

[F09] 获取文件大小
来源：http://dali.cucudq.cn/Article/details/gtzdktgjem.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtxdfygnmn.html

PHP:  filesize("a.txt");
来源：http://dali.nwbrower.top/Article/details/gtxpnlajrq.html

JS:   fs.statSync("a.txt").size
来源：http://dali.shangyingyoupin.top/Article/details/gtfmnnaeig.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yonumen.top/Article/details/gtmfapthja.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.c1oappe.top/Article/details/gtkwlolbum.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.hywenlv.cn/Article/details/gtpdihyrmx.html

Ruby: File.size("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtmqyzdkpr.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.iojbl.cn/Article/details/gtrkwoxdmr.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.wangdashe.top/Article/details/gtqncrbawt.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtswcogtjw.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.xinyue.icu/Article/details/gtgeztbyga.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtycyceqna.html

TS:   path.extname("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gttfzzjfjk.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.feifeiyinyue.top/Article/details/gtrvbrvqjy.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.havefunace.top/Article/details/gttsulggfr.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.xziqi.cn/Article/details/gtkkzfaxau.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtqasgwscq.html

[F11] 复制与移动文件
来源：http://dali.yj202588.top/Article/details/gtmzoczpwi.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.gogol.net.cn/Article/details/gtqennwaec.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpenargrq.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhixingplan.top/Article/details/gtuzpuflbn.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yuxming.cn/Article/details/gtpgezueur.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yj20258.top/Article/details/gthaxowpov.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.hywenlv.cn/Article/details/gtxrjdeiql.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.smart0.xyz/Article/details/gtzruwsadq.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yueranfly.top/Article/details/gtaskscqhm.html

[F12] CSV 读写
来源：http://dali.zycfv.cn/Article/details/gtjllduzgi.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.tanke756.top/Article/details/gtdwdbnvix.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yanxiufei.cn/Article/details/gtyzpbhvbb.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.mhx1999.top/Article/details/gtbfomcfio.html

TS:   // 同上
来源：http://dali.zhixingplan.top/Article/details/gthbazxamc.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.dianchejie.cn/Article/details/gtopjrmmef.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.dianchejie.cn/Article/details/gtygdhcqrt.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkknjlqzs.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.mhx1999.top/Article/details/gtdambkylz.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtqngcullc.html

G. 面向对象
来源：http://dali.hongshengwenyu.top/Article/details/gtcnhbimca.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtklxpnddu.html

[G01] 定义类
来源：http://dali.cdnleiting.top/Article/details/gtuxzddydc.html

Py:   class User: pass
来源：http://dali.sxryk.cn/Article/details/gtmmjyekzz.html

PHP:  class User {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkbdndtvk.html

JS:   class User {}
来源：http://dali.yanxiufei.cn/Article/details/gtmxyowjve.html

TS:   class User { name: string = ""; }
来源：http://dali.jyoumei.cn/Article/details/gtgqhxlkgh.html

Java: class User {}
来源：http://dali.ydzc1.top/Article/details/gtewrhtkse.html

Go:   type User struct { Name string }
来源：http://dali.redwolf501.top/Article/details/gtnbmgqwor.html

Ruby: class User; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjixihxuo.html

C#:   class User {}
来源：http://dali.vqdsnc.cn/Article/details/gtmowkwkxl.html

[G02] 构造函数
来源：http://dali.nwbrower.top/Article/details/gtnqxrrsuc.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.sysykeji.top/Article/details/gtdgemwsfj.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.tian-w.cn/Article/details/gtjvqviizw.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtedptsfkt.html

TS:   constructor(public name: string) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtcgwgrwix.html

Java: User(String name) { this.name = name; }
来源：http://dali.smart0.xyz/Article/details/gtuytgnwaa.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrmttxqdn.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.cashguo.top/Article/details/gtjfobzlta.html

C#:   public User(string name) { Name = name; }
来源：http://dali.sweek.top/Article/details/gtvzssdvup.html

[G03] 实例属性
来源：http://dali.sysykeji.top/Article/details/gtojaevimr.html

Py:   self.name = "x"
来源：http://dali.andypj.xyz/Article/details/gtodneowey.html

PHP:  public string $name = "x";
来源：http://dali.hnxiangtu.top/Article/details/gtaroddyls.html

JS:   this.name = "x";
来源：http://dali.pycfn.com/Article/details/gtcojhpiwb.html

TS:   name: string = "x";
来源：http://dali.quarkkingdee.top/Article/details/gtaimnsylu.html

Java: private String name;
来源：http://dali.shangyingyoupin.top/Article/details/gtipzylpcn.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.sysykeji.top/Article/details/gtcfhrhwua.html

Ruby: @name = "x"
来源：http://dali.gotoacloud.top/Article/details/gtaoglzxej.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.nanxinkj.top/Article/details/gtrrgwojdq.html

[G04] 定义方法
来源：http://dali.tanke756.top/Article/details/gtoiuzugny.html

Py:   def greet(self): return self.name
来源：http://dali.gzhubu.top/Article/details/gtytjlblzy.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.fzhhl.top/Article/details/gtsobqbcqu.html

JS:   greet() { return this.name; }
来源：http://dali.ivvv.top/Article/details/gtwfzrfgcz.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhixingplan.top/Article/details/gtpnyzwejf.html

Java: String greet() { return name; }
来源：http://dali.zhoulong.xyz/Article/details/gtowqbtbir.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.dashuyun.cn/Article/details/gtrwsldhru.html

Ruby: def greet; @name; end
来源：http://dali.smart0.xyz/Article/details/gtvxaxyaky.html

C#:   public string Greet() => Name;
来源：http://dali.chenlongwang.top/Article/details/gtyecetuvb.html

[G05] 继承
来源：http://dali.zhoulong.xyz/Article/details/gtltndmlzo.html

Py:   class Admin(User): pass
来源：http://dali.jqgufenzy.top/Article/details/gthfsdluqv.html

PHP:  class Admin extends User {}
来源：http://dali.shangyingyoupin.top/Article/details/gtvvjsjvtb.html

JS:   class Admin extends User {}
来源：http://dali.yj20258.top/Article/details/gtrgwuvvyi.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gthmleiymw.html

Java: class Admin extends User {}
来源：http://dali.cheryme.top/Article/details/gtlgtxkhac.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.fzhhl.top/Article/details/gttadrwnts.html

Ruby: class Admin < User; end
来源：http://dali.bjfxy.top/Article/details/gtwyurzkkb.html

C#:   class Admin : User {}
来源：http://dali.zhiwuduotai.top/Article/details/gtgroomvbz.html

[G06] 重写方法
来源：http://dali.c1oappe.top/Article/details/gtoxjfpptx.html

Py:   def greet(self): return "admin"
来源：http://dali.sufxvd.cn/Article/details/gtchsugdmt.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.haohaochexian.top/Article/details/gtvtqcicmf.html

JS:   greet() { return "admin"; }
来源：http://dali.yj20258.top/Article/details/gtjxbvegot.html

TS:   greet(): string { return "admin"; }
来源：http://dali.9152youxi.cn/Article/details/gtsukexamm.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jqgufenzy.top/Article/details/gtgpvsrpsp.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jqgufenzy.top/Article/details/gtfmkqispj.html

Ruby: def greet; "admin"; end
来源：http://dali.cdnleiting.top/Article/details/gtajysoori.html

C#:   public override string Greet() => "admin";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtusytggke.html

[G07] 调用父类方法
来源：http://dali.pycfn.com/Article/details/gtjznvmqxn.html

Py:   super().greet()
来源：http://dali.jinghuilouyu.cn/Article/details/gtzsfurbsf.html

PHP:  parent::greet();
来源：http://dali.wangdashe.top/Article/details/gtjiuibnaf.html

JS:   super.greet();
来源：http://dali.havefunace.top/Article/details/gtpfdcwljf.html

TS:   super.greet();
来源：http://dali.snrcjt.cn/Article/details/gtdvyeibbq.html

Java: super.greet();
来源：http://dali.jyoumei.cn/Article/details/gtmguraria.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hywenlv.cn/Article/details/gtyyvuzhzc.html

Ruby: super
来源：http://dali.9152youxi.cn/Article/details/gtgagbtjjm.html

C#:   base.Greet();
来源：http://dali.pengpengdd.cyou/Article/details/gtahmexery.html

[G08] 静态方法与属性
来源：http://dali.andypj.xyz/Article/details/gtrykddtfm.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrvvtqsbp.html

PHP:  public static function f() {}
来源：http://dali.zhiwuduotai.top/Article/details/gtfxlmqoju.html

JS:   static f() {}
来源：http://dali.ivvv.top/Article/details/gtkwkrzupb.html

TS:   static f(): void {}
来源：http://dali.meibo888.top/Article/details/gtroripjvi.html

Java: static void f() {}
来源：http://dali.hammf.cn/Article/details/gttrdeflfs.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdiirurfb.html

Ruby: def self.f; end
来源：http://dali.jyoumei.cn/Article/details/gtdntqjyvq.html

C#:   public static void F() {}
来源：http://dali.zdqjudy.top/Article/details/gtjapzhltj.html

[G09] 接口 / 抽象类
来源：http://dali.gzhubu.top/Article/details/gtqvckexzv.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.gzhubu.top/Article/details/gtzfvangmu.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.guannengcc.top/Article/details/gtsqambxks.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhongyouzk.top/Article/details/gtwislfuqm.html

TS:   interface Shape { area(): number; }
来源：http://dali.cashguo.top/Article/details/gtfuwrfbpx.html

Java: interface Shape { double area(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtntdjakjh.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zycfv.cn/Article/details/gtglleubsk.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhixingplan.top/Article/details/gtjkfznawv.html

C#:   interface IShape { double Area(); }
来源：http://dali.hnqzz.top/Article/details/gtrgomuovo.html

[G10] 访问控制
来源：http://dali.cdnleiting.top/Article/details/gtljdcjkrh.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.aizwys.cn/Article/details/gtbiybzkvk.html

PHP:  public / protected / private
来源：http://dali.yongpay.top/Article/details/gtvfipqcrx.html

JS:   #private 字段；其余公开
来源：http://dali.hammf.cn/Article/details/gtctuphhpm.html

TS:   public / protected / private
来源：http://dali.c1oappe.top/Article/details/gttmcoqajb.html

Java: public / protected / private / 默认包级
来源：http://dali.shzxlz.cn/Article/details/gtcxpydeed.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.havefunace.top/Article/details/gtpbksvznm.html

Ruby: public / protected / private
来源：http://dali.aibaodan.cn/Article/details/gtqjmnjkzt.html

C#:   public / protected / private / internal
来源：http://dali.shuidangran.top/Article/details/gtnipezzah.html

[G11] getter / setter
来源：http://dali.smart0.xyz/Article/details/gtdcjdogcs.html

Py:   @property 与 @x.setter
来源：http://dali.yj202588.top/Article/details/gtepotjirq.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.smart0.xyz/Article/details/gthtzrndgp.html

JS:   get name() { return this._name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtebkkdhns.html

TS:   get name(): string { return this._name; }
来源：http://dali.gaohongyu789.top/Article/details/gtyqnicjms.html

Java: public String getName() { return name; }
来源：http://dali.yj20258.top/Article/details/gtbboyrhei.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.hysaishi.cn/Article/details/gtbexbvtdy.html

Ruby: attr_accessor :name
来源：http://dali.dashuyun.cn/Article/details/gtelefhsrw.html

C#:   public string Name { get; set; }
来源：http://dali.yj20258888.top/Article/details/gtkoqnzbch.html

[G12] 对象转字符串
来源：http://dali.zhongyouzk.top/Article/details/gtfdrhedbr.html

Py:   def __str__(self): return self.name
来源：http://dali.ppjwa.cn/Article/details/gttrjgcsfa.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.nanxuanxn.top/Article/details/gturorfqkm.html

JS:   toString() { return this.name; }
来源：http://dali.hysaishi.cn/Article/details/gtefwjsyut.html

TS:   toString(): string { return this.name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtahwvacxx.html

Java: @Override public String toString() { return name; }
来源：http://dali.gotoacloud.top/Article/details/gtgnagrtup.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvcxlcfzh.html

Ruby: def to_s; @name; end
来源：http://dali.jqgufenzy.top/Article/details/gtwcewydch.html

C#:   public override string ToString() => Name;
来源：http://dali.daria6918.cn/Article/details/gtynulevnq.html

[G13] 判断对象类型
来源：http://dali.ehwqpu.com/Article/details/gtxwvyxbqd.html

Py:   isinstance(u, User)
来源：http://dali.gogol.net.cn/Article/details/gtpdjocwrx.html

PHP:  $u instanceof User
来源：http://dali.gzhubu.top/Article/details/gtamexxtzv.html

JS:   u instanceof User
来源：http://dali.hnqzz.top/Article/details/gtkcgqysfg.html

TS:   u instanceof User
来源：http://dali.cdnleiting.top/Article/details/gtamfyutve.html

Java: u instanceof User
来源：http://dali.yongpay.top/Article/details/gtmsvnrqes.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.fzhhl.top/Article/details/gtnzyinodm.html

Ruby: u.is_a?(User)
来源：http://dali.zhiwuduotai.top/Article/details/gtnqokjqpy.html

C#:   u is User
来源：http://dali.yanxiufei.cn/Article/details/gtyjvawzyf.html

[G14] 数据类 / record
来源：http://dali.ehwqpu.com/Article/details/gtykyznfde.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjllijxxf.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.xinyue.icu/Article/details/gtlbkrrrsx.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.fengsongda.top/Article/details/gthpjbagdn.html

TS:   type User = { name: string; age: number };
来源：http://dali.quarkkingdee.top/Article/details/gtzrcjtlyg.html

Java: record User(String name, int age) {}
来源：http://dali.zhixingplan.top/Article/details/gthglvbsub.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxwmclwfn.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hywenlv.cn/Article/details/gtpldpxqvh.html

C#:   record User(string Name, int Age);
来源：http://dali.cucudq.cn/Article/details/gtofoflytx.html

[G15] 枚举
来源：http://dali.ybcxt.top/Article/details/gtljvkkdpa.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.tanke756.top/Article/details/gtuaxilzyq.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.daria6918.cn/Article/details/gtkprfawyc.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwhshlcyv.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhongyouzk.top/Article/details/gttdnjbdrp.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhengqikj.top/Article/details/gtzlyyaftk.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.andypj.xyz/Article/details/gterrshese.html

Ruby: Color = %i[red green].freeze
来源：http://dali.0kj1m.cn/Article/details/gtptvewlgn.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.guannengcc.top/Article/details/gtybbrjlfh.html

[G16] 对象转数组 / 字典
来源：http://dali.kuanghao11.cn/Article/details/gtguiiuzro.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.nanxuanxn.top/Article/details/gtheggjedw.html

PHP:  get_object_vars($obj);
来源：http://dali.tian-w.cn/Article/details/gtoekfydga.html

JS:   Object.entries(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtcmuzutnn.html

TS:   Object.entries(obj)
来源：http://dali.jlsjyb.cn/Article/details/gthtpwgazx.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.bjfxy.top/Article/details/gtohvbpkne.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.daria6918.cn/Article/details/gtuohtkcdr.html

Ruby: obj.instance_variables
来源：http://dali.zhongyouzk.top/Article/details/gtoecawghy.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.sysykeji.top/Article/details/gtyorljail.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtjfsqbggo.html

H. 异常与错误处理
来源：http://dali.xinyue.icu/Article/details/gtpkivdwyk.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtwmheayso.html

[H01] try / catch 基础
来源：http://dali.sxryk.cn/Article/details/gtoaogexwk.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.pycfn.com/Article/details/gtvaquymga.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.cqqwz.cn/Article/details/gtjrrzgusi.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jinqigufen.top/Article/details/gttkcrsnpn.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.ppjwa.cn/Article/details/gtgwbwpuip.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.daria6918.cn/Article/details/gtxbtirsrg.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.xinyue.icu/Article/details/gtrranorjh.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.hongshengwenyu.top/Article/details/gtlsrmxfmy.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwdpxvcyi.html

[H02] finally / ensure 收尾
来源：http://dali.0kj1m.cn/Article/details/gtvmzqdvsn.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.gaohongyu789.top/Article/details/gttzsvlpqv.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.guannengcc.top/Article/details/gthqysiiya.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jianghu66.top/Article/details/gtmcakrqmm.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.daxiang520.top/Article/details/gtwrqoavyd.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.tanke756.top/Article/details/gtelpsobyc.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.xinyue.icu/Article/details/gtjkilthsp.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.9152youxi.cn/Article/details/gtmivbmpwc.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zycfv.cn/Article/details/gtsswaagkg.html

[H03] 主动抛出异常
来源：http://dali.nanxuanxn.top/Article/details/gttfnczpkd.html

Py:   raise ValueError("错误信息")
来源：http://dali.mhx1999.top/Article/details/gtnadqdjbi.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yueranfly.top/Article/details/gtihbbrmmn.html

JS:   throw new Error("错误信息");
来源：http://dali.meibo888.top/Article/details/gtuhnhcmtj.html

TS:   throw new Error("错误信息");
来源：http://dali.yuxming.cn/Article/details/gtuqcoxmng.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yangfankeji.com/Article/details/gtmaybqznj.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hnxiangtu.top/Article/details/gtqydakkak.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.haohaochexian.top/Article/details/gtzwjkrfve.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.bjfxy.top/Article/details/gtvxilfdhh.html

[H04] 自定义异常类型
来源：http://dali.zhoulong.xyz/Article/details/gtzyvlhoqo.html

Py:   class MyError(Exception): pass
来源：http://dali.aizwys.cn/Article/details/gtugxvdaox.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.cashguo.top/Article/details/gtwdnmchoi.html

JS:   class MyError extends Error {}
来源：http://dali.zhiwuduotai.top/Article/details/gtbhmvhgeb.html

TS:   class MyError extends Error {}
来源：http://dali.gotoacloud.top/Article/details/gterlayurw.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhoulong.xyz/Article/details/gtntbowykb.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.hongshengwenyu.top/Article/details/gtachfplyl.html

Ruby: class MyError < StandardError; end
来源：http://dali.zdqjudy.top/Article/details/gtpqsgkgid.html

C#:   class MyException : Exception {}
来源：http://dali.hongshengwenyu.top/Article/details/gtwqvdvztg.html

[H05] 捕获特定类型
来源：http://dali.jinqigfzy.top/Article/details/gtsstlnbwy.html

Py:   except ValueError as e:
来源：http://dali.meibo888.top/Article/details/gtsrpxwplf.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yj20258888.top/Article/details/gtaiznmnmj.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.shzxlz.cn/Article/details/gtyjsmkpcl.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yonumen.top/Article/details/gtprjdylqb.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yj20258.top/Article/details/gtnekhyhuz.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.ybcxt.top/Article/details/gthognjyst.html

Ruby: rescue ArgumentError => e
来源：http://dali.cqqwz.cn/Article/details/gtwnnqocox.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.guannengcc.top/Article/details/gtozmugaxz.html

[H06] 可选值 / 空值安全访问
来源：http://dali.hysaishi.cn/Article/details/gtscpkijcc.html


<!-- 参考信息 -->