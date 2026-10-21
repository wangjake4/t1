代发 wailian999

C#:   File.ReadAllText("a.txt");
来源：http://dali.yonumen.top/Article/details/gtndcdvcsn.html

[F02] 逐行读取文件
来源：http://dali.jinqigfzy.top/Article/details/gtooygucnd.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.sufxvd.cn/Article/details/gtrjqtalvc.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.tian-w.cn/Article/details/gtxqnpxkjp.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hysaishi.cn/Article/details/gtocaqfcmp.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.svipenyu.cn/Article/details/gtnpgksjpo.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.cqqwz.cn/Article/details/gtwhkndwab.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jqgfzy.top/Article/details/gtjpkurmkh.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.tianlin.xyz/Article/details/gtoqrofduv.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.smart0.xyz/Article/details/gtwoitpkro.html

[F03] 写入文件（覆盖）
来源：http://dali.yuanzhike.top/Article/details/gtmuaxgabo.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhiwuduotai.top/Article/details/gtaesbsvnj.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.chenzaomai.com/Article/details/gtzcwzaizb.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yongpay.top/Article/details/gtwbavjohs.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.aizwys.cn/Article/details/gtlipayeuw.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.redwolf501.top/Article/details/gteikjvedn.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.fzhhl.top/Article/details/gtgagmndsk.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.c1oappe.top/Article/details/gtbptmgyuq.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.tian-w.cn/Article/details/gtusczdxvf.html

[F04] 追加写入文件
来源：http://dali.zhixingplan.top/Article/details/gtidzhmdhi.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yongpay.top/Article/details/gtsdkcwxjs.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.snrcjt.cn/Article/details/gtfnqnykjw.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shzxlz.cn/Article/details/gtmvfwthjh.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cdnleiting.top/Article/details/gtjmdykpuf.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.snrcjt.cn/Article/details/gtwmpdyoje.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpfxyrkaq.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.daxiang520.top/Article/details/gtcnbimhhe.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.mhx1999.top/Article/details/gtmbmfbuyu.html

[F05] 判断文件或目录是否存在
来源：http://dali.feifeiyinyue.top/Article/details/gtlasdprum.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.redwolf501.top/Article/details/gtrdrccsgj.html

PHP:  file_exists("a.txt");
来源：http://dali.smart0.xyz/Article/details/gtltfryezf.html

JS:   fs.existsSync("a.txt")
来源：http://dali.pycfn.com/Article/details/gtclpjquku.html

TS:   fs.existsSync("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtfrmeyfik.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.gaohongyu789.top/Article/details/gtyaebbryt.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhiwuduotai.top/Article/details/gtbdqiaxxw.html

Ruby: File.exist?("a.txt")
来源：http://dali.mhx1999.top/Article/details/gthsbvrpfi.html

C#:   File.Exists("a.txt")
来源：http://dali.cashguo.top/Article/details/gtimueqigs.html

[F06] 删除文件
来源：http://dali.9152youxi.cn/Article/details/gtkhvskhrp.html

Py:   os.remove("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtaadvumew.html

PHP:  unlink("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gtenjeonqb.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.hammf.cn/Article/details/gtegvfeffx.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtxuweyumj.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.iojbl.cn/Article/details/gttlhuijfc.html

Go:   os.Remove("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtdktyoahu.html

Ruby: File.delete("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtsabdtbkt.html

C#:   File.Delete("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gtbyvlevvq.html

[F07] 创建目录（含多级）
来源：http://dali.gotoacloud.top/Article/details/gtsstvgudx.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.sxryk.cn/Article/details/gtbfsafiqd.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jqgfzy.top/Article/details/gtkwhshmiz.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ehwqpu.com/Article/details/gtriyslbuc.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.fengsongda.top/Article/details/gtulzyjumd.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.tanke756.top/Article/details/gtgkkdyjcn.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.xziqi.cn/Article/details/gtgewaogbc.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jlsjyb.cn/Article/details/gtjcmivbao.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.ydzc1.top/Article/details/gtvnzxjfko.html

[F08] 遍历目录
来源：http://dali.smart0.xyz/Article/details/gtmjwykqfe.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.xuanzx.com/Article/details/gtbfvjnubh.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.pycfn.com/Article/details/gtmixklyom.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhiwuduotai.top/Article/details/gttgfsmdku.html

TS:   fs.readdirSync("dir")
来源：http://dali.yuxming.cn/Article/details/gtrcapjfjv.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.ybcxt.top/Article/details/gtjxpsqmoj.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yonumen.top/Article/details/gteorrpysb.html

Ruby: Dir.children("dir")
来源：http://dali.aibaodan.cn/Article/details/gtdumvgfan.html

C#:   Directory.GetFiles("dir")
来源：http://dali.andypj.xyz/Article/details/gtnnyxyzde.html

[F09] 获取文件大小
来源：http://dali.yongpay.top/Article/details/gtrnpyhpkn.html

Py:   os.path.getsize("a.txt")
来源：http://dali.gzhubu.top/Article/details/gturiuuxjg.html

PHP:  filesize("a.txt");
来源：http://dali.hnqzz.top/Article/details/gtypeswrrz.html

JS:   fs.statSync("a.txt").size
来源：http://dali.quarkkingdee.top/Article/details/gtmjvhczfy.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhiwuduotai.top/Article/details/gtdvwarskr.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhiwuduotai.top/Article/details/gtoasvslne.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yonumen.top/Article/details/gtjnlwksvi.html

Ruby: File.size("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtzvxibdks.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.dashuyun.cn/Article/details/gtciexyuoi.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.wangdashe.top/Article/details/gtudbrxfmj.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtjrisiyaq.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.ydzc1.top/Article/details/gtkwcxzkcx.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtzqtrtqld.html

TS:   path.extname("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtlscdouue.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.sxryk.cn/Article/details/gtlaaabbqv.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.andypj.xyz/Article/details/gthjpaomem.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtpwdutbee.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtvhgmdotc.html

[F11] 复制与移动文件
来源：http://dali.zhongyouzk.top/Article/details/gtmgryxdim.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtfqzypmyd.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jlsjyb.cn/Article/details/gtmjqhkprw.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sweek.top/Article/details/gthwsvslmv.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.birdmap.top/Article/details/gtucnyqvfs.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyktyvnlo.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.pengpengdd.cyou/Article/details/gtjwzzpbcb.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.ydzc1.top/Article/details/gtgmofmnli.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.feifeiyinyue.top/Article/details/gtynvwawpk.html

[F12] CSV 读写
来源：http://dali.hnqzz.top/Article/details/gtnfjoesld.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yj202588.top/Article/details/gtyyardzoa.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.wangdashe.top/Article/details/gtbleucyux.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.316326.xyz/Article/details/gtflpcpgjz.html

TS:   // 同上
来源：http://dali.jinqigfzy.top/Article/details/gtwpgrkaig.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.smart0.xyz/Article/details/gtnhbzthsx.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.9152youxi.cn/Article/details/gtcnfezvvx.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtglusdmpi.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yj202588.top/Article/details/gtytwrfuuq.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gteayjwxkp.html

G. 面向对象
来源：http://dali.xylfe.cn/Article/details/gtspsmxhbg.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtwbzwneod.html

[G01] 定义类
来源：http://dali.hnxiangtu.top/Article/details/gtkkrxhtmu.html

Py:   class User: pass
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyddilkva.html

PHP:  class User {}
来源：http://dali.jlsjyb.cn/Article/details/gtgyofgbzc.html

JS:   class User {}
来源：http://dali.cashguo.top/Article/details/gteakslhca.html

TS:   class User { name: string = ""; }
来源：http://dali.hammf.cn/Article/details/gtbusxzpay.html

Java: class User {}
来源：http://dali.gogol.net.cn/Article/details/gtmpejshkv.html

Go:   type User struct { Name string }
来源：http://dali.jlsjyb.cn/Article/details/gtfjaagple.html

Ruby: class User; end
来源：http://dali.meibo888.top/Article/details/gtuppmogmh.html

C#:   class User {}
来源：http://dali.fengsongda.top/Article/details/gtnwynfqea.html

[G02] 构造函数
来源：http://dali.nanxuanxn.top/Article/details/gtkjhsoekv.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.cucudq.cn/Article/details/gthkptkkbq.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtvetgmxuj.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jqgufenzy.top/Article/details/gtqwmrwspa.html

TS:   constructor(public name: string) {}
来源：http://dali.xuanzx.com/Article/details/gtbegyxzfl.html

Java: User(String name) { this.name = name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkwfqymfc.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.sufxvd.cn/Article/details/gtmfdyjqri.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.pycfn.com/Article/details/gtdfeazvwj.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhixingplan.top/Article/details/gtwyewwaks.html

[G03] 实例属性
来源：http://dali.shanyushiyangkeji.top/Article/details/gtujcjbpvu.html

Py:   self.name = "x"
来源：http://dali.zycfv.cn/Article/details/gtqwqfypee.html

PHP:  public string $name = "x";
来源：http://dali.jlsjyb.cn/Article/details/gtjaprrini.html

JS:   this.name = "x";
来源：http://dali.yangfankeji.com/Article/details/gtdrbwxctd.html

TS:   name: string = "x";
来源：http://dali.jyoumei.cn/Article/details/gtrxabstbo.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gtenyjeepk.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.gzhubu.top/Article/details/gtsifvbvja.html

Ruby: @name = "x"
来源：http://dali.zhengqikj.top/Article/details/gtpwkesfsv.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.smart0.xyz/Article/details/gtsfcjcdyg.html

[G04] 定义方法
来源：http://dali.cashguo.top/Article/details/gtekdmrwdq.html

Py:   def greet(self): return self.name
来源：http://dali.jinqigfzy.top/Article/details/gtgpigyzpu.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hywenlv.cn/Article/details/gtnkjstezh.html

JS:   greet() { return this.name; }
来源：http://dali.zhoulong.xyz/Article/details/gtltjjfcja.html

TS:   greet(): string { return this.name; }
来源：http://dali.tian-w.cn/Article/details/gtcpafhhcz.html

Java: String greet() { return name; }
来源：http://dali.9152youxi.cn/Article/details/gtdkkodvug.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhengqikj.top/Article/details/gtcphpwcqi.html

Ruby: def greet; @name; end
来源：http://dali.yj20258.top/Article/details/gtcusabmub.html

C#:   public string Greet() => Name;
来源：http://dali.sufxvd.cn/Article/details/gtkmejvbrf.html

[G05] 继承
来源：http://dali.yvedp.cn/Article/details/gttezqciwm.html

Py:   class Admin(User): pass
来源：http://dali.meibo888.top/Article/details/gtsextamvr.html

PHP:  class Admin extends User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gttypmgbnd.html

JS:   class Admin extends User {}
来源：http://dali.xuanzx.com/Article/details/gtrvbfaxqo.html

TS:   class Admin extends User {}
来源：http://dali.smart0.xyz/Article/details/gtgfurgixm.html

Java: class Admin extends User {}
来源：http://dali.quarkkingdee.top/Article/details/gtbkbdcilw.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.andypj.xyz/Article/details/gtypvrlcfl.html

Ruby: class Admin < User; end
来源：http://dali.sweek.top/Article/details/gtwmnwyizq.html

C#:   class Admin : User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqgshieto.html

[G06] 重写方法
来源：http://dali.andypj.xyz/Article/details/gtxgzzealp.html

Py:   def greet(self): return "admin"
来源：http://dali.svipenyu.cn/Article/details/gtmawxfmnh.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yj20258888.top/Article/details/gtknscgmwa.html

JS:   greet() { return "admin"; }
来源：http://dali.bjfxy.top/Article/details/gtvriyrneo.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jyoumei.cn/Article/details/gtgqvupuiv.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.cashguo.top/Article/details/gtqmfjidox.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.dianchejie.cn/Article/details/gtumhhjeuu.html

Ruby: def greet; "admin"; end
来源：http://dali.c1oappe.top/Article/details/gtoibewsbi.html

C#:   public override string Greet() => "admin";
来源：http://dali.svipenyu.cn/Article/details/gtmaiyjkde.html

[G07] 调用父类方法
来源：http://dali.guannengcc.top/Article/details/gttxpguofm.html

Py:   super().greet()
来源：http://dali.jinghuilouyu.cn/Article/details/gtpojijnbp.html

PHP:  parent::greet();
来源：http://dali.shanyushiyangtech.top/Article/details/gthrnjdxxo.html

JS:   super.greet();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbljpruqj.html

TS:   super.greet();
来源：http://dali.sufxvd.cn/Article/details/gtnwnqbqtb.html

Java: super.greet();
来源：http://dali.ppjwa.cn/Article/details/gtikrpoqri.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.xinyue.icu/Article/details/gtuobsvcdh.html

Ruby: super
来源：http://dali.nanxinkj.top/Article/details/gtobjmrrsf.html

C#:   base.Greet();
来源：http://dali.xuetiantiany.cn/Article/details/gtjqvxmhhy.html

[G08] 静态方法与属性
来源：http://dali.yj20258.top/Article/details/gtbknxecgh.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.gaohongyu789.top/Article/details/gtnqgjfjck.html

PHP:  public static function f() {}
来源：http://dali.cucudq.cn/Article/details/gtopjviymv.html

JS:   static f() {}
来源：http://dali.0kj1m.cn/Article/details/gtnczrcftm.html

TS:   static f(): void {}
来源：http://dali.guannengcc.top/Article/details/gtzqsitbfn.html

Java: static void f() {}
来源：http://dali.hysaishi.cn/Article/details/gteigzwbzc.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.mhx1999.top/Article/details/gtzngzesym.html

Ruby: def self.f; end
来源：http://dali.daxiang520.top/Article/details/gtmsvukaue.html

C#:   public static void F() {}
来源：http://dali.yongpay.top/Article/details/gtqzekzudh.html

[G09] 接口 / 抽象类
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrnizcvsm.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yongpay.top/Article/details/gtsrbnxurp.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jinqigufen.top/Article/details/gthdeqbqle.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.birdmap.top/Article/details/gtfbvhnduu.html

TS:   interface Shape { area(): number; }
来源：http://dali.jiagoushi.top/Article/details/gtcaxifkpu.html

Java: interface Shape { double area(); }
来源：http://dali.kuanghao11.cn/Article/details/gtrgpjanlu.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.smart0.xyz/Article/details/gtazfdirnj.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.shanyushiyangtech.top/Article/details/gtpckcrrhw.html

C#:   interface IShape { double Area(); }
来源：http://dali.quarkkingdee.top/Article/details/gttysgwscn.html

[G10] 访问控制
来源：http://dali.hfpthk.cn/Article/details/gtkxiaahjb.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.cdnleiting.top/Article/details/gtesnnejlj.html

PHP:  public / protected / private
来源：http://dali.jlsjyb.cn/Article/details/gtrzifgawf.html

JS:   #private 字段；其余公开
来源：http://dali.hnqzz.top/Article/details/gthztbfkjw.html

TS:   public / protected / private
来源：http://dali.hammf.cn/Article/details/gtxbbpoffj.html

Java: public / protected / private / 默认包级
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwjlbyaxz.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hongshengwenyu.top/Article/details/gthlkkznuc.html

Ruby: public / protected / private
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvefxbimx.html

C#:   public / protected / private / internal
来源：http://dali.c1oappe.top/Article/details/gtoegbvnjr.html

[G11] getter / setter
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlwsbesbt.html

Py:   @property 与 @x.setter
来源：http://dali.sufxvd.cn/Article/details/gtyuxcmlhi.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.birdmap.top/Article/details/gtqqkesotu.html

JS:   get name() { return this._name; }
来源：http://dali.xinyue.icu/Article/details/gterpxcywe.html

TS:   get name(): string { return this._name; }
来源：http://dali.gogol.net.cn/Article/details/gtcdxtcwgq.html

Java: public String getName() { return name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtvyepbepw.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.wangshuangyany.cn/Article/details/gtlnugxaaa.html

Ruby: attr_accessor :name
来源：http://dali.9152youxi.cn/Article/details/gtfwqmmpze.html

C#:   public string Name { get; set; }
来源：http://dali.jyoumei.cn/Article/details/gtkexrgnsy.html

[G12] 对象转字符串
来源：http://dali.9152youxi.cn/Article/details/gtonskfiuh.html

Py:   def __str__(self): return self.name
来源：http://dali.chenzaomai.com/Article/details/gtvocyejmc.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.birdmap.top/Article/details/gtcuuieoap.html

JS:   toString() { return this.name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthagxfhst.html

TS:   toString(): string { return this.name; }
来源：http://dali.mhx1999.top/Article/details/gtfmxbpxlq.html

Java: @Override public String toString() { return name; }
来源：http://dali.jqgfzy.top/Article/details/gtrsqvadxe.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.pengpengdd.cyou/Article/details/gtoqyfnaxe.html

Ruby: def to_s; @name; end
来源：http://dali.jyoumei.cn/Article/details/gtvwxexkjw.html

C#:   public override string ToString() => Name;
来源：http://dali.gaohongyu789.top/Article/details/gtrvdzfkjj.html

[G13] 判断对象类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzkidrhqx.html

Py:   isinstance(u, User)
来源：http://dali.jinqigfzy.top/Article/details/gtimrinqjo.html

PHP:  $u instanceof User
来源：http://dali.dianchejie.cn/Article/details/gttrfdhnsd.html

JS:   u instanceof User
来源：http://dali.zhongyouzk.top/Article/details/gtvqochdxd.html

TS:   u instanceof User
来源：http://dali.pycfn.com/Article/details/gteciurprg.html

Java: u instanceof User
来源：http://dali.sweek.top/Article/details/gtcppxyiif.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.316326.xyz/Article/details/gttfpjkwik.html

Ruby: u.is_a?(User)
来源：http://dali.shzxlz.cn/Article/details/gtejpkiifn.html

C#:   u is User
来源：http://dali.tianlin.xyz/Article/details/gtysdgjdzt.html

[G14] 数据类 / record
来源：http://dali.tian-w.cn/Article/details/gtaldtwbkm.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jiagoushi.top/Article/details/gtifijfryu.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.tianlin.xyz/Article/details/gtzrknzkcz.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.gotoacloud.top/Article/details/gtymmgfcgr.html

TS:   type User = { name: string; age: number };
来源：http://dali.yanxiufei.cn/Article/details/gtglhxletd.html

Java: record User(String name, int age) {}
来源：http://dali.fzhhl.top/Article/details/gtfphxkmou.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jiagoushi.top/Article/details/gtwxwdpaut.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.shanyushiyangtech.top/Article/details/gtdeiztbma.html

C#:   record User(string Name, int Age);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtepmjisfp.html

[G15] 枚举
来源：http://dali.ehwqpu.com/Article/details/gtpkwehvun.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yj202588.top/Article/details/gttmrxeisi.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtojtslycu.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.chenlongwang.top/Article/details/gtoujxyrsu.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yuanzhike.top/Article/details/gtlotfuram.html

Java: enum Color { RED, GREEN }
来源：http://dali.aizwys.cn/Article/details/gtityoxfuh.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.iojbl.cn/Article/details/gtqkctiuuu.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jiagoushi.top/Article/details/gtiltzilqy.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.nwbrower.top/Article/details/gtcerjyxna.html

[G16] 对象转数组 / 字典
来源：http://dali.tian-w.cn/Article/details/gttjnbhtei.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.sufxvd.cn/Article/details/gtyibfbdqi.html

PHP:  get_object_vars($obj);
来源：http://dali.daria6918.cn/Article/details/gtxdbugryu.html

JS:   Object.entries(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gtkkudvmfs.html

TS:   Object.entries(obj)
来源：http://dali.guowangkeji.top/Article/details/gtygywaetd.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.andypj.xyz/Article/details/gtgkntduqp.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yonumen.top/Article/details/gtobjofirg.html

Ruby: obj.instance_variables
来源：http://dali.sweek.top/Article/details/gtvonzvyas.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.gzhubu.top/Article/details/gtrpdsbkul.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtqdzzpqpq.html

H. 异常与错误处理
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkwlvnpew.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtcimctcns.html

[H01] try / catch 基础
来源：http://dali.jinyuanbaomall.cn/Article/details/gtolfckdrd.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.tanke756.top/Article/details/gtwkpdccds.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.smart0.xyz/Article/details/gthjinqooq.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yangfankeji.com/Article/details/gtmaxbxdwy.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.ivvv.top/Article/details/gtkqgtbizk.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.birdmap.top/Article/details/gtlsfhibvk.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.fengsongda.top/Article/details/gtdixroeiy.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqdspjhnu.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.xuetiantiany.cn/Article/details/gthqnypczd.html

[H02] finally / ensure 收尾
来源：http://dali.sweek.top/Article/details/gtbaciqmrg.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.feifeiyinyue.top/Article/details/gtpgnvpfov.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.cucudq.cn/Article/details/gtyzfwnuzl.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jyoumei.cn/Article/details/gtlwrlzcic.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtpbwssooi.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.ppjwa.cn/Article/details/gtspmrqmoc.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hfpthk.cn/Article/details/gtfmvpayvq.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.birdmap.top/Article/details/gtoprysvpi.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.shuidangran.top/Article/details/gtegbtwjhc.html

[H03] 主动抛出异常
来源：http://dali.hnxiangtu.top/Article/details/gtwuqesaqc.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhongyouzk.top/Article/details/gtodmmjjyw.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hnxiangtu.top/Article/details/gtiujmguti.html

JS:   throw new Error("错误信息");
来源：http://dali.ydzc1.top/Article/details/gtwhtsrmuk.html

TS:   throw new Error("错误信息");
来源：http://dali.snrcjt.cn/Article/details/gtuajaquoe.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hnqzz.top/Article/details/gtnniyvndh.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yuxming.cn/Article/details/gtypwcjqoi.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.xuanzx.com/Article/details/gtahdhlpct.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.nwbrower.top/Article/details/gtyubwdfxq.html

[H04] 自定义异常类型
来源：http://dali.yueranfly.top/Article/details/gtfnxwbzcx.html

Py:   class MyError(Exception): pass
来源：http://dali.hfpthk.cn/Article/details/gtqrzduzyq.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbynvbnwx.html

JS:   class MyError extends Error {}
来源：http://dali.316326.xyz/Article/details/gtkymzvknm.html

TS:   class MyError extends Error {}
来源：http://dali.jinqigufen.top/Article/details/gtzlpqhqgi.html

Java: class MyException extends RuntimeException {}
来源：http://dali.tanke756.top/Article/details/gtqjszbefn.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ybcxt.top/Article/details/gtsdiosrtp.html

Ruby: class MyError < StandardError; end
来源：http://dali.svipenyu.cn/Article/details/gtjkyjuizk.html

C#:   class MyException : Exception {}
来源：http://dali.jqgfzy.top/Article/details/gtoqyekecm.html

[H05] 捕获特定类型
来源：http://dali.hongshengwenyu.top/Article/details/gtlhyjbjmb.html

Py:   except ValueError as e:
来源：http://dali.chenzaomai.com/Article/details/gtobuumgit.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.nanxuanxn.top/Article/details/gttiipjmhx.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.hywenlv.cn/Article/details/gtjqixvdgo.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.ehwqpu.com/Article/details/gtwvkrwdou.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.snrcjt.cn/Article/details/gtpdwpricw.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.cdnleiting.top/Article/details/gtokeekpmg.html

Ruby: rescue ArgumentError => e
来源：http://dali.fengsongda.top/Article/details/gtiwthfeog.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.birdmap.top/Article/details/gtkazvydcz.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gtbinbmfqg.html

Py:   value = d.get("k") or default
来源：http://dali.jinqigufen.top/Article/details/gttjpfmksg.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.cucudq.cn/Article/details/gtdhirepgu.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.sxryk.cn/Article/details/gtecuvglvd.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.shanyushiyangtech.top/Article/details/gtiuczlold.html


<!-- 参考信息 -->