代发 wailian999

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.shangyingyoupin.top/Article/details/gtwnxriegx.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.ehwqpu.com/Article/details/gtoxuwylun.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.hnqzz.top/Article/details/gtcihtotfy.html

Ruby: File.read("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtmrbzfnyl.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.iojbl.cn/Article/details/gtezqmiqdi.html

[F02] 逐行读取文件
来源：http://dali.iojbl.cn/Article/details/gttzziqhmw.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.wangdashe.top/Article/details/gtdvwpzjxu.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.pycfn.com/Article/details/gtectuxido.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cheryme.top/Article/details/gtazqhnwoa.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhengqikj.top/Article/details/gtdkjsazkg.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.fengsongda.top/Article/details/gtjhygfvms.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yvedp.cn/Article/details/gtmckyncyd.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.redwolf501.top/Article/details/gtyuhznymi.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.hnqzz.top/Article/details/gtdbeenwil.html

[F03] 写入文件（覆盖）
来源：http://dali.gogol.net.cn/Article/details/gtkhqrezvo.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.shangyingyoupin.top/Article/details/gtnokgenzd.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.cqqwz.cn/Article/details/gtbmgujwja.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.dianchejie.cn/Article/details/gtzbvoyjwe.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zdqjudy.top/Article/details/gtyrbywsok.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.redwolf501.top/Article/details/gtjgkpdwuu.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhongyouzk.top/Article/details/gtuuaoooha.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.cucudq.cn/Article/details/gtxnjzqzqc.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.xuetiantiany.cn/Article/details/gtaueveekx.html

[F04] 追加写入文件
来源：http://dali.jyoumei.cn/Article/details/gtmsgabrxp.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.cashguo.top/Article/details/gtvnvxmfve.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yangfankeji.com/Article/details/gtimwwxrax.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yuxming.cn/Article/details/gtuewwqsbt.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gaohongyu789.top/Article/details/gtaaytxjqb.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.sufxvd.cn/Article/details/gtroqxiolk.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jinqigfzy.top/Article/details/gtmmgyxxqu.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.guannengcc.top/Article/details/gtedwtwows.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jinghuilouyu.cn/Article/details/gtcwvbfosr.html

[F05] 判断文件或目录是否存在
来源：http://dali.shanyushiyangtech.top/Article/details/gtmkjhngly.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jiagoushi.top/Article/details/gtocybracw.html

PHP:  file_exists("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gtaigqezrv.html

JS:   fs.existsSync("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtyilvrzmm.html

TS:   fs.existsSync("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtgydvffbq.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.feifeiyinyue.top/Article/details/gtycmiepfw.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jinghuilouyu.cn/Article/details/gtqxyxhcap.html

Ruby: File.exist?("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gttgrgezwj.html

C#:   File.Exists("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtbudhtsgp.html

[F06] 删除文件
来源：http://dali.yanxiufei.cn/Article/details/gthfczjksb.html

Py:   os.remove("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtdzlojzwq.html

PHP:  unlink("a.txt");
来源：http://dali.fengsongda.top/Article/details/gtadfwgcmo.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtnuvuyvak.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gttfhbmrve.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yangfankeji.com/Article/details/gtwvmrvtwt.html

Go:   os.Remove("a.txt")
来源：http://dali.pycfn.com/Article/details/gtsaovfvue.html

Ruby: File.delete("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtdzhwupxa.html

C#:   File.Delete("a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gtwqkfzeak.html

[F07] 创建目录（含多级）
来源：http://dali.yj20258.top/Article/details/gtyyvytmet.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhiwuduotai.top/Article/details/gtdqctppkr.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yuanzhike.top/Article/details/gtytlkohut.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xuanzx.com/Article/details/gtaybodppd.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.daria6918.cn/Article/details/gtrjbrhkmr.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwcepiwoj.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yanxiufei.cn/Article/details/gtoggjocah.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.quarkkingdee.top/Article/details/gtnhfssqly.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.cucudq.cn/Article/details/gtxebrcbpp.html

[F08] 遍历目录
来源：http://dali.xinyue.icu/Article/details/gtepeznoen.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jiagoushi.top/Article/details/gtdspgkmmc.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.pycfn.com/Article/details/gttchmcnqz.html

JS:   fs.readdirSync("dir")
来源：http://dali.sweek.top/Article/details/gtevwzhvnw.html

TS:   fs.readdirSync("dir")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtotnhqxun.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhongyouzk.top/Article/details/gtjrphdptj.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.xylfe.cn/Article/details/gtaanpsddn.html

Ruby: Dir.children("dir")
来源：http://dali.316326.xyz/Article/details/gtjdxfjwhx.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yvedp.cn/Article/details/gtpajbegul.html

[F09] 获取文件大小
来源：http://dali.xuetiantiany.cn/Article/details/gtaqhattsh.html

Py:   os.path.getsize("a.txt")
来源：http://dali.tian-w.cn/Article/details/gticfykugb.html

PHP:  filesize("a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gtcobqiouo.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yj20258888.top/Article/details/gtyzlriszy.html

TS:   fs.statSync("a.txt").size
来源：http://dali.gaohongyu789.top/Article/details/gtxfbuiyop.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.xuanzx.com/Article/details/gtrvdejkwb.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.cucudq.cn/Article/details/gtreawlcaq.html

Ruby: File.size("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtasxnbrtd.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhiwuduotai.top/Article/details/gtuhymnflj.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.gzhubu.top/Article/details/gtgvcrrjvm.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtjkikipra.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.svipenyu.cn/Article/details/gtlmmwfcrf.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtqlwnspcv.html

TS:   path.extname("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtngmigtaa.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.daxiang520.top/Article/details/gtyjslxrma.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtfnmbdsgw.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.redwolf501.top/Article/details/gtceauljfn.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yj20258.top/Article/details/gtwuievweg.html

[F11] 复制与移动文件
来源：http://dali.jianghu66.top/Article/details/gtnxkxztvo.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.xinyue.icu/Article/details/gtnrdtyirs.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gtqmydyuuw.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.guowangkeji.top/Article/details/gtzlenxddd.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnzdmqvyi.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.shangyingyoupin.top/Article/details/gtfivtozjw.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.bjfxy.top/Article/details/gtpzcqpyfb.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.c1oappe.top/Article/details/gtglmbgpfc.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.hywenlv.cn/Article/details/gteqmkqnvm.html

[F12] CSV 读写
来源：http://dali.316326.xyz/Article/details/gtvhsxgzvj.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jianghu66.top/Article/details/gtibnegctg.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.ybcxt.top/Article/details/gtrgseyjcx.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yvedp.cn/Article/details/gtzjiyzmhp.html

TS:   // 同上
来源：http://dali.yongpay.top/Article/details/gtztxfvffx.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hfpthk.cn/Article/details/gtseikoszd.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jyoumei.cn/Article/details/gtnykzkult.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.aibaodan.cn/Article/details/gtkxzxzteo.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.haohaochexian.top/Article/details/gthsotbiwy.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gthaizigky.html

G. 面向对象
来源：http://dali.iojbl.cn/Article/details/gtmydaqdct.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gthomzupeh.html

[G01] 定义类
来源：http://dali.ivvv.top/Article/details/gtuzvnsixq.html

Py:   class User: pass
来源：http://dali.jqgfzy.top/Article/details/gtrxttokxm.html

PHP:  class User {}
来源：http://dali.pengpengdd.cyou/Article/details/gtrycfmjie.html

JS:   class User {}
来源：http://dali.xylfe.cn/Article/details/gtlcnttpqf.html

TS:   class User { name: string = ""; }
来源：http://dali.gotoacloud.top/Article/details/gtpoafizzu.html

Java: class User {}
来源：http://dali.jiagoushi.top/Article/details/gtbyqqpbsr.html

Go:   type User struct { Name string }
来源：http://dali.yongpay.top/Article/details/gtgatzjvmo.html

Ruby: class User; end
来源：http://dali.havefunace.top/Article/details/gtxdqdgpwp.html

C#:   class User {}
来源：http://dali.gzhubu.top/Article/details/gtthgabhxn.html

[G02] 构造函数
来源：http://dali.chenzaomai.com/Article/details/gtkdppyphc.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.hammf.cn/Article/details/gtzorofyva.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.ivvv.top/Article/details/gtjonjsnly.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtaxnpcjnc.html

TS:   constructor(public name: string) {}
来源：http://dali.hfpthk.cn/Article/details/gtfjixqais.html

Java: User(String name) { this.name = name; }
来源：http://dali.guowangkeji.top/Article/details/gtxtkirzhp.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hnqzz.top/Article/details/gtfozcrhfz.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.gogol.net.cn/Article/details/gtmyatuxtq.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yuxming.cn/Article/details/gtaklxzgzu.html

[G03] 实例属性
来源：http://dali.hywenlv.cn/Article/details/gtbujvznxx.html

Py:   self.name = "x"
来源：http://dali.316326.xyz/Article/details/gtftmsjtig.html

PHP:  public string $name = "x";
来源：http://dali.shangyingyoupin.top/Article/details/gtchlyxaep.html

JS:   this.name = "x";
来源：http://dali.yj20258888.top/Article/details/gtzwiduojo.html

TS:   name: string = "x";
来源：http://dali.yanxiufei.cn/Article/details/gtgjvbleft.html

Java: private String name;
来源：http://dali.birdmap.top/Article/details/gtnvyaoysl.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.gotoacloud.top/Article/details/gtamvikdpc.html

Ruby: @name = "x"
来源：http://dali.jlsjyb.cn/Article/details/gtbdzaewya.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.redwolf501.top/Article/details/gtyblcgdvc.html

[G04] 定义方法
来源：http://dali.svipenyu.cn/Article/details/gtzlqsmvrr.html

Py:   def greet(self): return self.name
来源：http://dali.chenjidiqi.icu/Article/details/gtxfbluflw.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.fengsongda.top/Article/details/gtpuzmhnyt.html

JS:   greet() { return this.name; }
来源：http://dali.vqdsnc.cn/Article/details/gthdwqhcml.html

TS:   greet(): string { return this.name; }
来源：http://dali.iojbl.cn/Article/details/gtrhfyzzdm.html

Java: String greet() { return name; }
来源：http://dali.zhixingplan.top/Article/details/gtredpykyh.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.xziqi.cn/Article/details/gtfzidnjjx.html

Ruby: def greet; @name; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtlbsezejm.html

C#:   public string Greet() => Name;
来源：http://dali.aizwys.cn/Article/details/gtsewvgrzn.html

[G05] 继承
来源：http://dali.bjfxy.top/Article/details/gtgtqquegk.html

Py:   class Admin(User): pass
来源：http://dali.yuxming.cn/Article/details/gtwxdzjagk.html

PHP:  class Admin extends User {}
来源：http://dali.havefunace.top/Article/details/gtdxsuexot.html

JS:   class Admin extends User {}
来源：http://dali.xuetiantiany.cn/Article/details/gtpaqubnaw.html

TS:   class Admin extends User {}
来源：http://dali.cdnleiting.top/Article/details/gtltfzbynt.html

Java: class Admin extends User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjclenhje.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yonumen.top/Article/details/gtjjvujxtb.html

Ruby: class Admin < User; end
来源：http://dali.sweek.top/Article/details/gtwytvbwyw.html

C#:   class Admin : User {}
来源：http://dali.yuanzhike.top/Article/details/gtdzovqrgf.html

[G06] 重写方法
来源：http://dali.dashuyun.cn/Article/details/gtxplmyhfg.html

Py:   def greet(self): return "admin"
来源：http://dali.hammf.cn/Article/details/gtskwpqcal.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.haohaochexian.top/Article/details/gtbttlnobf.html

JS:   greet() { return "admin"; }
来源：http://dali.redwolf501.top/Article/details/gtgyvgfmpp.html

TS:   greet(): string { return "admin"; }
来源：http://dali.havefunace.top/Article/details/gtuftsuamk.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhiwuduotai.top/Article/details/gthtbsqjwr.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.pycfn.com/Article/details/gtnmdgbayr.html

Ruby: def greet; "admin"; end
来源：http://dali.gzhubu.top/Article/details/gtjkeiiiux.html

C#:   public override string Greet() => "admin";
来源：http://dali.cheryme.top/Article/details/gtmynfcvoc.html

[G07] 调用父类方法
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbcjhkuda.html

Py:   super().greet()
来源：http://dali.nanxinkj.top/Article/details/gtznzuxnvr.html

PHP:  parent::greet();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxwffcxol.html

JS:   super.greet();
来源：http://dali.dashuyun.cn/Article/details/gtxvixirru.html

TS:   super.greet();
来源：http://dali.daria6918.cn/Article/details/gtasqbgfvm.html

Java: super.greet();
来源：http://dali.dianchejie.cn/Article/details/gtgyitxzqg.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.shzxlz.cn/Article/details/gtkbfubbqi.html

Ruby: super
来源：http://dali.gaohongyu789.top/Article/details/gtaommaflj.html

C#:   base.Greet();
来源：http://dali.kuanghao11.cn/Article/details/gtxklbgzga.html

[G08] 静态方法与属性
来源：http://dali.wangshuangyany.cn/Article/details/gtfiedoptq.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.cqqwz.cn/Article/details/gtixamwemt.html

PHP:  public static function f() {}
来源：http://dali.tian-w.cn/Article/details/gtukviqnqs.html

JS:   static f() {}
来源：http://dali.redwolf501.top/Article/details/gtdubtxqqy.html

TS:   static f(): void {}
来源：http://dali.gotoacloud.top/Article/details/gtispkbjuk.html

Java: static void f() {}
来源：http://dali.pengpengdd.cyou/Article/details/gtlzbtmrsv.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.ehwqpu.com/Article/details/gtikqhshyv.html

Ruby: def self.f; end
来源：http://dali.haohaochexian.top/Article/details/gtknqwjpiy.html

C#:   public static void F() {}
来源：http://dali.zhiwuduotai.top/Article/details/gtxsxkitod.html

[G09] 接口 / 抽象类
来源：http://dali.nwbrower.top/Article/details/gtxbdwllns.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.xuanzx.com/Article/details/gtxooyfycu.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.xuetiantiany.cn/Article/details/gtdonnhsum.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.svipenyu.cn/Article/details/gtmwswkinh.html

TS:   interface Shape { area(): number; }
来源：http://dali.gotoacloud.top/Article/details/gtlbykmqid.html

Java: interface Shape { double area(); }
来源：http://dali.jqgufenzy.top/Article/details/gtpfdeuphw.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.iojbl.cn/Article/details/gtwvtuvomg.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkvvhgoeh.html

C#:   interface IShape { double Area(); }
来源：http://dali.cashguo.top/Article/details/gtqmwjwlln.html

[G10] 访问控制
来源：http://dali.sysykeji.top/Article/details/gtsrteezjv.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.wangdashe.top/Article/details/gtdonkpyge.html

PHP:  public / protected / private
来源：http://dali.iojbl.cn/Article/details/gtbrcxcahf.html

JS:   #private 字段；其余公开
来源：http://dali.yanxiufei.cn/Article/details/gtjviitwcz.html

TS:   public / protected / private
来源：http://dali.pycfn.com/Article/details/gtmckeomuo.html

Java: public / protected / private / 默认包级
来源：http://dali.chenzaomai.com/Article/details/gtqzurepne.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.ybcxt.top/Article/details/gtoazjvsxf.html

Ruby: public / protected / private
来源：http://dali.gzhubu.top/Article/details/gtqbrinecb.html

C#:   public / protected / private / internal
来源：http://dali.cqqwz.cn/Article/details/gtxjxflhow.html

[G11] getter / setter
来源：http://dali.iojbl.cn/Article/details/gttllapurl.html

Py:   @property 与 @x.setter
来源：http://dali.daxiang520.top/Article/details/gtcpeamido.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtoeqdefsn.html

JS:   get name() { return this._name; }
来源：http://dali.hnqzz.top/Article/details/gtoqjydssd.html

TS:   get name(): string { return this._name; }
来源：http://dali.nanxuanxn.top/Article/details/gtbkgkijuv.html

Java: public String getName() { return name; }
来源：http://dali.birdmap.top/Article/details/gtfhjhfvkt.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.fzhhl.top/Article/details/gtftfsfvpu.html

Ruby: attr_accessor :name
来源：http://dali.kuanghao11.cn/Article/details/gtbjbxugwu.html

C#:   public string Name { get; set; }
来源：http://dali.wangdashe.top/Article/details/gtpksrvuge.html

[G12] 对象转字符串
来源：http://dali.fzhhl.top/Article/details/gtdrfjmjhz.html

Py:   def __str__(self): return self.name
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwxysmoym.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.pycfn.com/Article/details/gtkxuozyjd.html

JS:   toString() { return this.name; }
来源：http://dali.hnxiangtu.top/Article/details/gtsagmlpoi.html

TS:   toString(): string { return this.name; }
来源：http://dali.wangdashe.top/Article/details/gtjyaaxufg.html

Java: @Override public String toString() { return name; }
来源：http://dali.guannengcc.top/Article/details/gtzwdctsvm.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtermmswnu.html

Ruby: def to_s; @name; end
来源：http://dali.tanke756.top/Article/details/gturebekme.html

C#:   public override string ToString() => Name;
来源：http://dali.cdnleiting.top/Article/details/gtzlnmvoje.html

[G13] 判断对象类型
来源：http://dali.yuanzhike.top/Article/details/gtbmbpifii.html

Py:   isinstance(u, User)
来源：http://dali.hfpthk.cn/Article/details/gtskxwbuya.html

PHP:  $u instanceof User
来源：http://dali.jiagoushi.top/Article/details/gthtwvlchq.html

JS:   u instanceof User
来源：http://dali.chenjidiqi.icu/Article/details/gtjrjclvep.html

TS:   u instanceof User
来源：http://dali.xinyue.icu/Article/details/gtzjjrsxtn.html

Java: u instanceof User
来源：http://dali.shuidangran.top/Article/details/gtpbwrpxbw.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yj20258.top/Article/details/gtsogrxtsp.html

Ruby: u.is_a?(User)
来源：http://dali.wangshuangyany.cn/Article/details/gtisswhaqr.html

C#:   u is User
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtccipuovz.html

[G14] 数据类 / record
来源：http://dali.hfpthk.cn/Article/details/gtajhgnbke.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhoulong.xyz/Article/details/gtiqlitguw.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hnqzz.top/Article/details/gtbceiniuq.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.shanyushiyangtech.top/Article/details/gtbipcgvlf.html

TS:   type User = { name: string; age: number };
来源：http://dali.shuidangran.top/Article/details/gtiaixstqz.html

Java: record User(String name, int age) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtjwnldevj.html

Go:   type User struct { Name string; Age int }
来源：http://dali.cashguo.top/Article/details/gtwyhbrufr.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.cheryme.top/Article/details/gtdsvstmre.html

C#:   record User(string Name, int Age);
来源：http://dali.jinqigufen.top/Article/details/gtsvkbpeqo.html

[G15] 枚举
来源：http://dali.gaohongyu789.top/Article/details/gtdzyraeje.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jqgufenzy.top/Article/details/gtkomrzpuk.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zycfv.cn/Article/details/gtiqjwqygm.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.gogol.net.cn/Article/details/gtwfvflpfs.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cqqwz.cn/Article/details/gtwpbbdshd.html

Java: enum Color { RED, GREEN }
来源：http://dali.jqgufenzy.top/Article/details/gtrnnntvcd.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.quarkkingdee.top/Article/details/gtnvukuetv.html

Ruby: Color = %i[red green].freeze
来源：http://dali.shuidangran.top/Article/details/gttpdedmzm.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hywenlv.cn/Article/details/gtiaqetsra.html

[G16] 对象转数组 / 字典
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyeimqcnk.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.hysaishi.cn/Article/details/gtzcnivqcl.html

PHP:  get_object_vars($obj);
来源：http://dali.guannengcc.top/Article/details/gtliwwnxca.html

JS:   Object.entries(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gtgfjhkqjc.html

TS:   Object.entries(obj)
来源：http://dali.havefunace.top/Article/details/gtisvxgvct.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtunsdlcht.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.gzhubu.top/Article/details/gtufmtfats.html

Ruby: obj.instance_variables
来源：http://dali.dianchejie.cn/Article/details/gtkkobuqsu.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jqgufenzy.top/Article/details/gtfkzfeier.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtzquiadod.html

H. 异常与错误处理
来源：http://dali.zhaomingkeji.xyz/Article/details/gtghapabnb.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtesbwbkjy.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gtmoeslkhl.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jinghuilouyu.cn/Article/details/gtglutmgzr.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jlsjyb.cn/Article/details/gtektjcnwi.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.kuanghao11.cn/Article/details/gtulypkgqc.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.daria6918.cn/Article/details/gtufbnfppl.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.havefunace.top/Article/details/gthiqjdcvc.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jinqigfzy.top/Article/details/gtatuafkdy.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yuxming.cn/Article/details/gtnrfhhxgk.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jqgfzy.top/Article/details/gtsmfprfnd.html

[H02] finally / ensure 收尾
来源：http://dali.yvedp.cn/Article/details/gthjhpykny.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zycfv.cn/Article/details/gtnfonymlw.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.nwbrower.top/Article/details/gtbrvnkvfv.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.wangdashe.top/Article/details/gtepkmgeay.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yj20258.top/Article/details/gtrodntkkg.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.cqqwz.cn/Article/details/gtrtndhszv.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhiwuduotai.top/Article/details/gtqyxcgwug.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jqgfzy.top/Article/details/gtoprojjtr.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.fzhhl.top/Article/details/gtozgcmpmo.html

[H03] 主动抛出异常
来源：http://dali.xuetiantiany.cn/Article/details/gtrpowtrnn.html

Py:   raise ValueError("错误信息")
来源：http://dali.sweek.top/Article/details/gtqguowjdp.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.snrcjt.cn/Article/details/gtybvxcees.html

JS:   throw new Error("错误信息");
来源：http://dali.xziqi.cn/Article/details/gtwxwqupgh.html

TS:   throw new Error("错误信息");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtktartrog.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.gogol.net.cn/Article/details/gtxqllqwje.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.ivvv.top/Article/details/gtdxhfnzok.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.shangyingyoupin.top/Article/details/gtaxfazadq.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yj20258.top/Article/details/gthagppyfw.html

[H04] 自定义异常类型
来源：http://dali.9152youxi.cn/Article/details/gtgzjhetoz.html

Py:   class MyError(Exception): pass
来源：http://dali.zhongyouzk.top/Article/details/gtqlsuxtjs.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.gaohongyu789.top/Article/details/gtuesygmkk.html

JS:   class MyError extends Error {}
来源：http://dali.jyoumei.cn/Article/details/gtgvorvsxm.html

TS:   class MyError extends Error {}
来源：http://dali.jyoumei.cn/Article/details/gtiogtkxyu.html

Java: class MyException extends RuntimeException {}
来源：http://dali.pengpengdd.cyou/Article/details/gthxknlecd.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.dashuyun.cn/Article/details/gtbwjrzkqy.html

Ruby: class MyError < StandardError; end
来源：http://dali.jlsjyb.cn/Article/details/gtlzaeltye.html

C#:   class MyException : Exception {}
来源：http://dali.chenjidiqi.icu/Article/details/gtffsabxco.html

[H05] 捕获特定类型
来源：http://dali.hnxiangtu.top/Article/details/gtzbxmuckl.html

Py:   except ValueError as e:
来源：http://dali.tian-w.cn/Article/details/gtiruyahwq.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.pycfn.com/Article/details/gtnylkdxfs.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.c1oappe.top/Article/details/gtpcyitusw.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yvedp.cn/Article/details/gtrsklbyvx.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hnxiangtu.top/Article/details/gtmbpmdurd.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.ehwqpu.com/Article/details/gtzgzsmwfh.html

Ruby: rescue ArgumentError => e
来源：http://dali.meibo888.top/Article/details/gtjuxntvnv.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.havefunace.top/Article/details/gtwovyyxjn.html

[H06] 可选值 / 空值安全访问
来源：http://dali.shuidangran.top/Article/details/gthytzpgci.html


<!-- 参考信息 -->