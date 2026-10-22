代发 wailian999

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.xziqi.cn/Article/details/gtejxoklxf.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.nwbrower.top/Article/details/gtulvwhand.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.daxiang520.top/Article/details/gtklyxtdmj.html

Ruby: File.read("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtceonoabq.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.fzhhl.top/Article/details/gtfrenmncw.html

[F02] 逐行读取文件
来源：http://dali.zhiwuduotai.top/Article/details/gtzwfjgzdp.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmtwzmvmw.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yueranfly.top/Article/details/gthqzxgehn.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xylfe.cn/Article/details/gtojrqiwxn.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.guowangkeji.top/Article/details/gtbvifxllh.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.wangshuangyany.cn/Article/details/gtotabgcax.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.hfpthk.cn/Article/details/gtfswslasi.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yuanzhike.top/Article/details/gtbeslfdrd.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.haohaochexian.top/Article/details/gtppoyqzjk.html

[F03] 写入文件（覆盖）
来源：http://dali.xylfe.cn/Article/details/gtlfhmgytw.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.aizwys.cn/Article/details/gtepppugln.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.dianchejie.cn/Article/details/gtbiiaixhp.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.havefunace.top/Article/details/gtdmxqhnog.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.haohaochexian.top/Article/details/gtxuqkyenv.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.chenlongwang.top/Article/details/gtkjkkhgai.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.fengsongda.top/Article/details/gtzfbrplas.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.chenjidiqi.icu/Article/details/gtijbqxzrc.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.birdmap.top/Article/details/gthcyvqwif.html

[F04] 追加写入文件
来源：http://dali.haohaochexian.top/Article/details/gthjoyzcms.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.guannengcc.top/Article/details/gtkgqpvjzz.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jinqigufen.top/Article/details/gtduquhmym.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yongpay.top/Article/details/gtlagpgmfl.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yanxiufei.cn/Article/details/gtqdyaxzbd.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.ybcxt.top/Article/details/gtivaphpsv.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.cdnleiting.top/Article/details/gtrkrfwork.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.gaohongyu789.top/Article/details/gtyyltqind.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.kuanghao11.cn/Article/details/gthjgqxmhz.html

[F05] 判断文件或目录是否存在
来源：http://dali.pengpengdd.cyou/Article/details/gtzlnxkade.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.cashguo.top/Article/details/gtpbrohsgy.html

PHP:  file_exists("a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gtiwuvbyzd.html

JS:   fs.existsSync("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwlmxgkag.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yj20258.top/Article/details/gthuaenztd.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.snrcjt.cn/Article/details/gtjwolajcf.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gtfvdbkmln.html

Ruby: File.exist?("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtrenxtaif.html

C#:   File.Exists("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtvkenqhni.html

[F06] 删除文件
来源：http://dali.shzxlz.cn/Article/details/gtylugfxfq.html

Py:   os.remove("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtkqtkdgqn.html

PHP:  unlink("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gtvgiwatnu.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.xziqi.cn/Article/details/gtnhwnrjxa.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.cheryme.top/Article/details/gtmacffhdu.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhiwuduotai.top/Article/details/gtovktljqt.html

Go:   os.Remove("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtamhrmcbr.html

Ruby: File.delete("a.txt")
来源：http://dali.c1oappe.top/Article/details/gttzkwbkwf.html

C#:   File.Delete("a.txt");
来源：http://dali.yonumen.top/Article/details/gtnkuczhal.html

[F07] 创建目录（含多级）
来源：http://dali.jqgfzy.top/Article/details/gtxjjabnhe.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.dashuyun.cn/Article/details/gtntdpakes.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.snrcjt.cn/Article/details/gturggsbsw.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xziqi.cn/Article/details/gtpvnoiobl.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.tian-w.cn/Article/details/gtxqzxxnel.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hysaishi.cn/Article/details/gthqbrezru.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.andypj.xyz/Article/details/gtkhkzjxao.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.kuanghao11.cn/Article/details/gtqrxjueif.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.shzxlz.cn/Article/details/gttfpecoxi.html

[F08] 遍历目录
来源：http://dali.bjfxy.top/Article/details/gtezwpebid.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhongyouzk.top/Article/details/gtqmkdrrtw.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.c1oappe.top/Article/details/gtmvxgbtmb.html

JS:   fs.readdirSync("dir")
来源：http://dali.pengpengdd.cyou/Article/details/gtsqqddoez.html

TS:   fs.readdirSync("dir")
来源：http://dali.chenlongwang.top/Article/details/gtfoezslvy.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.shzxlz.cn/Article/details/gteaqswwmu.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsbonojxl.html

Ruby: Dir.children("dir")
来源：http://dali.yuxming.cn/Article/details/gtwdwbzacc.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zdqjudy.top/Article/details/gtwvktvpch.html

[F09] 获取文件大小
来源：http://dali.c1oappe.top/Article/details/gtvdwvtzex.html

Py:   os.path.getsize("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtrhkmdfgh.html

PHP:  filesize("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gtjyumofaz.html

JS:   fs.statSync("a.txt").size
来源：http://dali.chenzaomai.com/Article/details/gtbxfixzdz.html

TS:   fs.statSync("a.txt").size
来源：http://dali.sysykeji.top/Article/details/gtohrglmoz.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yuanzhike.top/Article/details/gtkmtuykyt.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yangfankeji.com/Article/details/gtmpavckxz.html

Ruby: File.size("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtpphbolxf.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.tanke756.top/Article/details/gtlwllpufi.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jlsjyb.cn/Article/details/gtdrekgwrp.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.xinyue.icu/Article/details/gtywwtkvuj.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtvshoyccy.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.ivvv.top/Article/details/gtbxcwwszu.html

TS:   path.extname("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtapgekxds.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.cashguo.top/Article/details/gtuxpqnupw.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.meibo888.top/Article/details/gtfzhlpcxf.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtwruzkuby.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtlbxkaodc.html

[F11] 复制与移动文件
来源：http://dali.dianchejie.cn/Article/details/gtsiduplvt.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.gogol.net.cn/Article/details/gtmegjrjez.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gtpjmzpnoz.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yj20258.top/Article/details/gtdomqjnku.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xziqi.cn/Article/details/gtivalfski.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.gzhubu.top/Article/details/gtxefzjkvr.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zycfv.cn/Article/details/gtvojztypo.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.smart0.xyz/Article/details/gtybssaeqn.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.c1oappe.top/Article/details/gtmlmsrskd.html

[F12] CSV 读写
来源：http://dali.shzxlz.cn/Article/details/gtsmtbsaev.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.xylfe.cn/Article/details/gtrodzxtfm.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.xuetiantiany.cn/Article/details/gtzhkzkdcz.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.nanxuanxn.top/Article/details/gtpyugyekv.html

TS:   // 同上
来源：http://dali.andypj.xyz/Article/details/gtrgzismqh.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.ivvv.top/Article/details/gtibuajsxz.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yj20258.top/Article/details/gtakfbzjrb.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.wangdashe.top/Article/details/gtgeuopxvi.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.gzhubu.top/Article/details/gtgylotoeh.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtfdklabyr.html

G. 面向对象
来源：http://dali.jyoumei.cn/Article/details/gtewqwzedm.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtodsfnfiq.html

[G01] 定义类
来源：http://dali.dianchejie.cn/Article/details/gtsxutnknx.html

Py:   class User: pass
来源：http://dali.xinyue.icu/Article/details/gtgjbnwglz.html

PHP:  class User {}
来源：http://dali.gotoacloud.top/Article/details/gtthbmzuwq.html

JS:   class User {}
来源：http://dali.hfpthk.cn/Article/details/gtmbmjaphg.html

TS:   class User { name: string = ""; }
来源：http://dali.jianghu66.top/Article/details/gtyurwgwxu.html

Java: class User {}
来源：http://dali.zhongyouzk.top/Article/details/gtyngbtqyk.html

Go:   type User struct { Name string }
来源：http://dali.smart0.xyz/Article/details/gtcwjxzmwb.html

Ruby: class User; end
来源：http://dali.kuanghao11.cn/Article/details/gthpusmvuo.html

C#:   class User {}
来源：http://dali.snrcjt.cn/Article/details/gtirwbqinz.html

[G02] 构造函数
来源：http://dali.havefunace.top/Article/details/gtohnfgtxu.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.feifeiyinyue.top/Article/details/gttaosvziq.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.gogol.net.cn/Article/details/gtmmcwkzvi.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yvedp.cn/Article/details/gtashbnbsd.html

TS:   constructor(public name: string) {}
来源：http://dali.yangfankeji.com/Article/details/gtcloddjzf.html

Java: User(String name) { this.name = name; }
来源：http://dali.guowangkeji.top/Article/details/gtohxvzayu.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.aizwys.cn/Article/details/gtcmyxqued.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.c1oappe.top/Article/details/gtnwgpleal.html

C#:   public User(string name) { Name = name; }
来源：http://dali.daria6918.cn/Article/details/gtckpmrdsc.html

[G03] 实例属性
来源：http://dali.zhaomingkeji.xyz/Article/details/gthfkvxqta.html

Py:   self.name = "x"
来源：http://dali.cqqwz.cn/Article/details/gtkxsrzcvp.html

PHP:  public string $name = "x";
来源：http://dali.nanxuanxn.top/Article/details/gtxdarpptf.html

JS:   this.name = "x";
来源：http://dali.chenzaomai.com/Article/details/gtoeliqisv.html

TS:   name: string = "x";
来源：http://dali.chenzaomai.com/Article/details/gttkstldoq.html

Java: private String name;
来源：http://dali.chenzaomai.com/Article/details/gtcwbljgel.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.mhx1999.top/Article/details/gtloggorth.html

Ruby: @name = "x"
来源：http://dali.gzhubu.top/Article/details/gtyudrufxl.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.cqqwz.cn/Article/details/gtdnsfsrgy.html

[G04] 定义方法
来源：http://dali.chenjidiqi.icu/Article/details/gtioztytrw.html

Py:   def greet(self): return self.name
来源：http://dali.jinqigufen.top/Article/details/gthmogytvx.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.316326.xyz/Article/details/gtsiywalzx.html

JS:   greet() { return this.name; }
来源：http://dali.gotoacloud.top/Article/details/gtrceahbbl.html

TS:   greet(): string { return this.name; }
来源：http://dali.gotoacloud.top/Article/details/gtaomcasnb.html

Java: String greet() { return name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtumeyescv.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gtagncpsae.html

Ruby: def greet; @name; end
来源：http://dali.jinqigfzy.top/Article/details/gtfhngstwx.html

C#:   public string Greet() => Name;
来源：http://dali.zhixingplan.top/Article/details/gtowxrpmkw.html

[G05] 继承
来源：http://dali.jinghuilouyu.cn/Article/details/gtvxkutocs.html

Py:   class Admin(User): pass
来源：http://dali.xuetiantiany.cn/Article/details/gtyeiyrjuy.html

PHP:  class Admin extends User {}
来源：http://dali.hfpthk.cn/Article/details/gtgzsdzskr.html

JS:   class Admin extends User {}
来源：http://dali.yangfankeji.com/Article/details/gthttryito.html

TS:   class Admin extends User {}
来源：http://dali.gzhubu.top/Article/details/gtqdvmgkgg.html

Java: class Admin extends User {}
来源：http://dali.smart0.xyz/Article/details/gtbvnpzgyr.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.cucudq.cn/Article/details/gtkkxgngzk.html

Ruby: class Admin < User; end
来源：http://dali.zhengqikj.top/Article/details/gtbjscblwb.html

C#:   class Admin : User {}
来源：http://dali.gaohongyu789.top/Article/details/gtuhmwpbjk.html

[G06] 重写方法
来源：http://dali.ydzc1.top/Article/details/gtezckwyhl.html

Py:   def greet(self): return "admin"
来源：http://dali.cheryme.top/Article/details/gtmimxzojv.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.svipenyu.cn/Article/details/gtfcyfasds.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gtwqaenqha.html

TS:   greet(): string { return "admin"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtcrgvzqbi.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.dianchejie.cn/Article/details/gtbcegtsdp.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.pengpengdd.cyou/Article/details/gtmxsquese.html

Ruby: def greet; "admin"; end
来源：http://dali.jqgfzy.top/Article/details/gtujuldxje.html

C#:   public override string Greet() => "admin";
来源：http://dali.shangyingyoupin.top/Article/details/gthydaxvyi.html

[G07] 调用父类方法
来源：http://dali.shzxlz.cn/Article/details/gtyupihwrl.html

Py:   super().greet()
来源：http://dali.yuxming.cn/Article/details/gtctfkeche.html

PHP:  parent::greet();
来源：http://dali.xziqi.cn/Article/details/gtoacnfivm.html

JS:   super.greet();
来源：http://dali.cdnleiting.top/Article/details/gtusioezvt.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gtwxiyadzp.html

Java: super.greet();
来源：http://dali.zycfv.cn/Article/details/gtxfukqdkk.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfmvighjx.html

Ruby: super
来源：http://dali.sxryk.cn/Article/details/gtjxvethlv.html

C#:   base.Greet();
来源：http://dali.yonumen.top/Article/details/gtqdrooqtm.html

[G08] 静态方法与属性
来源：http://dali.chenlongwang.top/Article/details/gtpzchlbza.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.quarkkingdee.top/Article/details/gtnapnzgwa.html

PHP:  public static function f() {}
来源：http://dali.xinyue.icu/Article/details/gttmtxxfeo.html

JS:   static f() {}
来源：http://dali.sxryk.cn/Article/details/gthfiwbqwo.html

TS:   static f(): void {}
来源：http://dali.jianghu66.top/Article/details/gtgtimkhfi.html

Java: static void f() {}
来源：http://dali.shuidangran.top/Article/details/gtxiviohjk.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yueranfly.top/Article/details/gthyrxsmtq.html

Ruby: def self.f; end
来源：http://dali.chenlongwang.top/Article/details/gtmzifogpx.html

C#:   public static void F() {}
来源：http://dali.wangdashe.top/Article/details/gttefgxzab.html

[G09] 接口 / 抽象类
来源：http://dali.sweek.top/Article/details/gtlyxhmuzd.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhiwuduotai.top/Article/details/gtzfrhrssj.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.andypj.xyz/Article/details/gtsaryprbx.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.sufxvd.cn/Article/details/gtfeltowdg.html

TS:   interface Shape { area(): number; }
来源：http://dali.chenzaomai.com/Article/details/gtzczysmdt.html

Java: interface Shape { double area(); }
来源：http://dali.jyoumei.cn/Article/details/gtigczihme.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.smart0.xyz/Article/details/gtbmxplhbz.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.shanyushiyangtech.top/Article/details/gtlyfkexpj.html

C#:   interface IShape { double Area(); }
来源：http://dali.yongpay.top/Article/details/gtqtupsvks.html

[G10] 访问控制
来源：http://dali.jiagoushi.top/Article/details/gtuueiozmm.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.nanxuanxn.top/Article/details/gtbjsjqufi.html

PHP:  public / protected / private
来源：http://dali.fzhhl.top/Article/details/gttxucfhfo.html

JS:   #private 字段；其余公开
来源：http://dali.tianlin.xyz/Article/details/gtwrsuatpx.html

TS:   public / protected / private
来源：http://dali.xuetiantiany.cn/Article/details/gtmuwitnmf.html

Java: public / protected / private / 默认包级
来源：http://dali.gotoacloud.top/Article/details/gtshpbyihd.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yj20258888.top/Article/details/gtrzyomibf.html

Ruby: public / protected / private
来源：http://dali.0kj1m.cn/Article/details/gtjrodybue.html

C#:   public / protected / private / internal
来源：http://dali.yongpay.top/Article/details/gtdpnafgov.html

[G11] getter / setter
来源：http://dali.hysaishi.cn/Article/details/gtcvnotzpd.html

Py:   @property 与 @x.setter
来源：http://dali.yj202588.top/Article/details/gttejgszlx.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtvpyasnat.html

JS:   get name() { return this._name; }
来源：http://dali.jianghu66.top/Article/details/gtmxkitjrq.html

TS:   get name(): string { return this._name; }
来源：http://dali.ivvv.top/Article/details/gtzqzwnach.html

Java: public String getName() { return name; }
来源：http://dali.bjfxy.top/Article/details/gtfityznwv.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.quarkkingdee.top/Article/details/gtdtcypjhj.html

Ruby: attr_accessor :name
来源：http://dali.tianlin.xyz/Article/details/gtlaeaxcdx.html

C#:   public string Name { get; set; }
来源：http://dali.wangshuangyany.cn/Article/details/gtwmylwejs.html

[G12] 对象转字符串
来源：http://dali.iojbl.cn/Article/details/gtazxywwzq.html

Py:   def __str__(self): return self.name
来源：http://dali.shangyingyoupin.top/Article/details/gthacmnlzi.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlouerxug.html

JS:   toString() { return this.name; }
来源：http://dali.xuanzx.com/Article/details/gtampkeutl.html

TS:   toString(): string { return this.name; }
来源：http://dali.andypj.xyz/Article/details/gtawkhilsl.html

Java: @Override public String toString() { return name; }
来源：http://dali.jyoumei.cn/Article/details/gtgaqnxcjp.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zycfv.cn/Article/details/gtzhldqcdg.html

Ruby: def to_s; @name; end
来源：http://dali.0kj1m.cn/Article/details/gtdohkacli.html

C#:   public override string ToString() => Name;
来源：http://dali.hfpthk.cn/Article/details/gtjasgwzbk.html

[G13] 判断对象类型
来源：http://dali.feifeiyinyue.top/Article/details/gtwequjmkn.html

Py:   isinstance(u, User)
来源：http://dali.chenlongwang.top/Article/details/gtnhytktmw.html

PHP:  $u instanceof User
来源：http://dali.316326.xyz/Article/details/gtcrizxnxt.html

JS:   u instanceof User
来源：http://dali.jinqigfzy.top/Article/details/gtknwaxmwz.html

TS:   u instanceof User
来源：http://dali.nwbrower.top/Article/details/gticjhimuq.html

Java: u instanceof User
来源：http://dali.iojbl.cn/Article/details/gtfgmjtwhz.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.shangyingyoupin.top/Article/details/gtrnnjscfk.html

Ruby: u.is_a?(User)
来源：http://dali.jinghuilouyu.cn/Article/details/gtdunrpekv.html

C#:   u is User
来源：http://dali.jlsjyb.cn/Article/details/gtaoyprqdl.html

[G14] 数据类 / record
来源：http://dali.sweek.top/Article/details/gtvnoxubuh.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.aibaodan.cn/Article/details/gthgdktbrl.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.nanxuanxn.top/Article/details/gtvywxobfw.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.xuetiantiany.cn/Article/details/gtjtrihreu.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuwgjtiug.html

Java: record User(String name, int age) {}
来源：http://dali.sysykeji.top/Article/details/gtuznpwaap.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zycfv.cn/Article/details/gtvpkszdkx.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jqgufenzy.top/Article/details/gtcagmtthe.html

C#:   record User(string Name, int Age);
来源：http://dali.yongpay.top/Article/details/gtdpxafenv.html

[G15] 枚举
来源：http://dali.hnxiangtu.top/Article/details/gtevjcfnwq.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.daria6918.cn/Article/details/gtpkwgttej.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtciizuifr.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.vqdsnc.cn/Article/details/gtkzmloyyd.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.chenzaomai.com/Article/details/gtptdmcrvp.html

Java: enum Color { RED, GREEN }
来源：http://dali.daria6918.cn/Article/details/gtuqplygmv.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.c1oappe.top/Article/details/gtkovdxxca.html

Ruby: Color = %i[red green].freeze
来源：http://dali.quarkkingdee.top/Article/details/gttdwezatc.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.birdmap.top/Article/details/gtvjwenjzl.html

[G16] 对象转数组 / 字典
来源：http://dali.sxryk.cn/Article/details/gtotrbhjmc.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.sysykeji.top/Article/details/gtsavqsxut.html

PHP:  get_object_vars($obj);
来源：http://dali.nanxinkj.top/Article/details/gtubxallxf.html

JS:   Object.entries(obj)
来源：http://dali.hammf.cn/Article/details/gtjaccuanp.html

TS:   Object.entries(obj)
来源：http://dali.fengsongda.top/Article/details/gtnrknpxip.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.quarkkingdee.top/Article/details/gtqmqeayoa.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.smart0.xyz/Article/details/gtpobtyvov.html

Ruby: obj.instance_variables
来源：http://dali.yj20258888.top/Article/details/gttizznlpi.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hysaishi.cn/Article/details/gtrsplsqdm.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtwtdtoqxl.html

H. 异常与错误处理
来源：http://dali.sufxvd.cn/Article/details/gtrxxhxfgg.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtzzmvbnnb.html

[H01] try / catch 基础
来源：http://dali.nanxuanxn.top/Article/details/gtvvlasltf.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.guowangkeji.top/Article/details/gtpznspqjx.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yangfankeji.com/Article/details/gtnvpzwbob.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hywenlv.cn/Article/details/gtcfsmozbt.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.kuanghao11.cn/Article/details/gtokluwuqo.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.iojbl.cn/Article/details/gttwhoiqvt.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.xylfe.cn/Article/details/gtvaqoacki.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yanxiufei.cn/Article/details/gtgpknmgom.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.sxryk.cn/Article/details/gteyvisqoi.html

[H02] finally / ensure 收尾
来源：http://dali.xinyue.icu/Article/details/gtsskwicvk.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jiagoushi.top/Article/details/gtgxwdfuap.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.0kj1m.cn/Article/details/gtbsrpjxww.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yuanzhike.top/Article/details/gtrtajmmrd.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hnxiangtu.top/Article/details/gtsknxavkl.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.birdmap.top/Article/details/gtlpmnlzrp.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yj202588.top/Article/details/gtuoudrjuu.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.tianlin.xyz/Article/details/gtjaqptsms.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.bjfxy.top/Article/details/gtanmnvumy.html

[H03] 主动抛出异常
来源：http://dali.cqqwz.cn/Article/details/gtlhlwquao.html

Py:   raise ValueError("错误信息")
来源：http://dali.yj20258.top/Article/details/gtgrcnvbtv.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yonumen.top/Article/details/gtnpsplxnq.html

JS:   throw new Error("错误信息");
来源：http://dali.gzhubu.top/Article/details/gthjommlee.html

TS:   throw new Error("错误信息");
来源：http://dali.zhengqikj.top/Article/details/gtpofmsfww.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jlsjyb.cn/Article/details/gthyzvcvwl.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.wangdashe.top/Article/details/gtodbltfcr.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.ehwqpu.com/Article/details/gtnypmdnov.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.nwbrower.top/Article/details/gtogsaywso.html

[H04] 自定义异常类型
来源：http://dali.jianghu66.top/Article/details/gtypbszqwh.html

Py:   class MyError(Exception): pass
来源：http://dali.quarkkingdee.top/Article/details/gtolymetsk.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.dianchejie.cn/Article/details/gtfxpbekqr.html

JS:   class MyError extends Error {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzrrmidkq.html

TS:   class MyError extends Error {}
来源：http://dali.pengpengdd.cyou/Article/details/gtfglkcasb.html

Java: class MyException extends RuntimeException {}
来源：http://dali.iojbl.cn/Article/details/gtbliikcff.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwmqtjdbn.html

Ruby: class MyError < StandardError; end
来源：http://dali.xylfe.cn/Article/details/gtdisjfsxi.html

C#:   class MyException : Exception {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtywsbmclk.html

[H05] 捕获特定类型
来源：http://dali.fzhhl.top/Article/details/gtuoaothhs.html

Py:   except ValueError as e:
来源：http://dali.xylfe.cn/Article/details/gtumettcbb.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.gaohongyu789.top/Article/details/gtjexaybww.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.andypj.xyz/Article/details/gtlwvyabsl.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.xylfe.cn/Article/details/gtssulyakz.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.xinyue.icu/Article/details/gtpaoocbze.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.nwbrower.top/Article/details/gtwqucvjra.html

Ruby: rescue ArgumentError => e
来源：http://dali.9152youxi.cn/Article/details/gtrbatsusl.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yongpay.top/Article/details/gtkzqdytry.html

[H06] 可选值 / 空值安全访问
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlxcrkwdz.html


<!-- 参考信息 -->