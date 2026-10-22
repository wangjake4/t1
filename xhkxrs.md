代发 wailian999

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yongpay.top/Article/details/gtfxlehlsg.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.feifeiyinyue.top/Article/details/gthxrbwxey.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhongyouzk.top/Article/details/gtvxvckckn.html

Ruby: File.read("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtvxnmtdwv.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.bjfxy.top/Article/details/gthyvojsbr.html

[F02] 逐行读取文件
来源：http://dali.sxryk.cn/Article/details/gtrxsyoaqi.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.cashguo.top/Article/details/gthvbqdtxo.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.nanxuanxn.top/Article/details/gtfwudggvu.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.haohaochexian.top/Article/details/gtgfcuxqlr.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtlrlizxwq.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnbvnzpwu.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhoulong.xyz/Article/details/gtjosvsaxw.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.tianlin.xyz/Article/details/gtysgzkupy.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.meibo888.top/Article/details/gtpteeqxmb.html

[F03] 写入文件（覆盖）
来源：http://dali.hywenlv.cn/Article/details/gteyezarsj.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.quarkkingdee.top/Article/details/gtgewjgftr.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.snrcjt.cn/Article/details/gtffaqoacd.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xinyue.icu/Article/details/gtgqpctrrs.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xziqi.cn/Article/details/gtrcarrkgo.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.ppjwa.cn/Article/details/gtdyyyqnyx.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.shzxlz.cn/Article/details/gtlbbejolh.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.hammf.cn/Article/details/gtxokahdxp.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.shzxlz.cn/Article/details/gtxcjjepkp.html

[F04] 追加写入文件
来源：http://dali.yj20258888.top/Article/details/gtppfaiwhg.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.ppjwa.cn/Article/details/gthzvsvapz.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.svipenyu.cn/Article/details/gtjgbzadag.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ybcxt.top/Article/details/gtvjnevpqj.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjexrcetm.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jianghu66.top/Article/details/gtfldbwqbt.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yonumen.top/Article/details/gtblkvfqou.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.pengpengdd.cyou/Article/details/gtkcpcandu.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yuxming.cn/Article/details/gtmylnglnn.html

[F05] 判断文件或目录是否存在
来源：http://dali.yuxming.cn/Article/details/gtdsfxwgxg.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.sysykeji.top/Article/details/gtjgxwffpi.html

PHP:  file_exists("a.txt");
来源：http://dali.chenlongwang.top/Article/details/gtqaaynkfl.html

JS:   fs.existsSync("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtysraqxuh.html

TS:   fs.existsSync("a.txt")
来源：http://dali.wangdashe.top/Article/details/gttkxwmjek.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtkddugfiz.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.daria6918.cn/Article/details/gtaflmojxt.html

Ruby: File.exist?("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtyqssnnec.html

C#:   File.Exists("a.txt")
来源：http://dali.hammf.cn/Article/details/gtnwgjcnhb.html

[F06] 删除文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcmwvvzqz.html

Py:   os.remove("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtnvjrsmas.html

PHP:  unlink("a.txt");
来源：http://dali.svipenyu.cn/Article/details/gtrpphwlxn.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtlzamubci.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtukuriphn.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jqgufenzy.top/Article/details/gtniwwxvsw.html

Go:   os.Remove("a.txt")
来源：http://dali.bjfxy.top/Article/details/gtjkiltgff.html

Ruby: File.delete("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtlyqzxeor.html

C#:   File.Delete("a.txt");
来源：http://dali.iojbl.cn/Article/details/gtjoafjvbp.html

[F07] 创建目录（含多级）
来源：http://dali.aibaodan.cn/Article/details/gtpyprwtxi.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jianghu66.top/Article/details/gtbyllfabs.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.guannengcc.top/Article/details/gtihhphqlk.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.chenzaomai.com/Article/details/gtkcoezqlk.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ehwqpu.com/Article/details/gtnudldkvq.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.xuetiantiany.cn/Article/details/gtbihzsuwd.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtftwdzvul.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yuxming.cn/Article/details/gthvcujpxt.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.guowangkeji.top/Article/details/gtkfxgbiaq.html

[F08] 遍历目录
来源：http://dali.hysaishi.cn/Article/details/gtoeiqwrdj.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.guowangkeji.top/Article/details/gtlcajfgrm.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.smart0.xyz/Article/details/gtfypixwfm.html

JS:   fs.readdirSync("dir")
来源：http://dali.cdnleiting.top/Article/details/gtjxzjmhzr.html

TS:   fs.readdirSync("dir")
来源：http://dali.pengpengdd.cyou/Article/details/gtpkocobrj.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.aibaodan.cn/Article/details/gtnknlzylo.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.ehwqpu.com/Article/details/gtbybuyjtt.html

Ruby: Dir.children("dir")
来源：http://dali.chenzaomai.com/Article/details/gtjvoanewa.html

C#:   Directory.GetFiles("dir")
来源：http://dali.c1oappe.top/Article/details/gtielocbzz.html

[F09] 获取文件大小
来源：http://dali.hammf.cn/Article/details/gtdyyipaxk.html

Py:   os.path.getsize("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtozcbkjfn.html

PHP:  filesize("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gtfdaynrpj.html

JS:   fs.statSync("a.txt").size
来源：http://dali.meibo888.top/Article/details/gtsvwzxcdj.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhengqikj.top/Article/details/gthdphvuke.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yangfankeji.com/Article/details/gtzifwlsfg.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yj20258888.top/Article/details/gttqkpvfuo.html

Ruby: File.size("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvmvvbpjn.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.chenzaomai.com/Article/details/gtawfzrskk.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jiagoushi.top/Article/details/gtozegkrcm.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.xziqi.cn/Article/details/gtwuchypdh.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.316326.xyz/Article/details/gtbvmmcvvh.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtzaqvncsc.html

TS:   path.extname("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtvcomkeym.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yj202588.top/Article/details/gtqhynwjic.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.shuidangran.top/Article/details/gtnjwcogke.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hnqzz.top/Article/details/gtpkvjnaaq.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jyoumei.cn/Article/details/gthvkjmijs.html

[F11] 复制与移动文件
来源：http://dali.chenzaomai.com/Article/details/gtgkdfqxci.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.birdmap.top/Article/details/gtbddjyjbr.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.cucudq.cn/Article/details/gtllyxjijf.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.guannengcc.top/Article/details/gtsezsefkh.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhengqikj.top/Article/details/gtjspunsko.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.birdmap.top/Article/details/gtyvgetjfd.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.gogol.net.cn/Article/details/gtfouxdbky.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.hfpthk.cn/Article/details/gtmvolhvex.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.birdmap.top/Article/details/gtnntfslje.html

[F12] CSV 读写
来源：http://dali.hnqzz.top/Article/details/gteprgowks.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.svipenyu.cn/Article/details/gtmqcpwcth.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.vqdsnc.cn/Article/details/gtqhodhazg.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jianghu66.top/Article/details/gtuhejobyl.html

TS:   // 同上
来源：http://dali.yj202588.top/Article/details/gtxhayzris.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.chenlongwang.top/Article/details/gtsjrigops.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhiwuduotai.top/Article/details/gtfpdhcegi.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.shanyushiyangtech.top/Article/details/gttwgokzkt.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yongpay.top/Article/details/gtxrezwzoh.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtxqjxbiym.html

G. 面向对象
来源：http://dali.yongpay.top/Article/details/gtxfqdqrhw.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gthlmlgqly.html

[G01] 定义类
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqeubbswm.html

Py:   class User: pass
来源：http://dali.guowangkeji.top/Article/details/gtvfgmqyei.html

PHP:  class User {}
来源：http://dali.jyoumei.cn/Article/details/gtfkagmcdv.html

JS:   class User {}
来源：http://dali.cqqwz.cn/Article/details/gttauealuv.html

TS:   class User { name: string = ""; }
来源：http://dali.aizwys.cn/Article/details/gtxamaewas.html

Java: class User {}
来源：http://dali.yonumen.top/Article/details/gtepmfgiuf.html

Go:   type User struct { Name string }
来源：http://dali.yuxming.cn/Article/details/gtapoxmvca.html

Ruby: class User; end
来源：http://dali.yj20258.top/Article/details/gteowjzlrb.html

C#:   class User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtupkxqyxd.html

[G02] 构造函数
来源：http://dali.zhixingplan.top/Article/details/gtyadyusns.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.fengsongda.top/Article/details/gtrnwtudsd.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.dianchejie.cn/Article/details/gtkvgrmbcj.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.birdmap.top/Article/details/gtihixljis.html

TS:   constructor(public name: string) {}
来源：http://dali.mhx1999.top/Article/details/gtjssraduc.html

Java: User(String name) { this.name = name; }
来源：http://dali.xinyue.icu/Article/details/gtmzsilztz.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yj202588.top/Article/details/gtetnehihj.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.shangyingyoupin.top/Article/details/gtljofknko.html

C#:   public User(string name) { Name = name; }
来源：http://dali.aizwys.cn/Article/details/gtgxomegfs.html

[G03] 实例属性
来源：http://dali.snrcjt.cn/Article/details/gtaciqvzmu.html

Py:   self.name = "x"
来源：http://dali.zhiwuduotai.top/Article/details/gthdzhbjws.html

PHP:  public string $name = "x";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzlpddfjj.html

JS:   this.name = "x";
来源：http://dali.hysaishi.cn/Article/details/gtdusdrekj.html

TS:   name: string = "x";
来源：http://dali.pycfn.com/Article/details/gtylzpxhxs.html

Java: private String name;
来源：http://dali.sufxvd.cn/Article/details/gtvozudgbx.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiplimiih.html

Ruby: @name = "x"
来源：http://dali.mhx1999.top/Article/details/gtfpgdyxbt.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.vqdsnc.cn/Article/details/gtjxowlbvv.html

[G04] 定义方法
来源：http://dali.hywenlv.cn/Article/details/gtyrltzwci.html

Py:   def greet(self): return self.name
来源：http://dali.birdmap.top/Article/details/gtvqzvyqfc.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.gaohongyu789.top/Article/details/gtogfoqwsa.html

JS:   greet() { return this.name; }
来源：http://dali.xuanzx.com/Article/details/gtaobsuvpc.html

TS:   greet(): string { return this.name; }
来源：http://dali.fengsongda.top/Article/details/gtpyfpytyh.html

Java: String greet() { return name; }
来源：http://dali.316326.xyz/Article/details/gtnwunyjje.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hfpthk.cn/Article/details/gtjhubdagg.html

Ruby: def greet; @name; end
来源：http://dali.guannengcc.top/Article/details/gtgguvyhgm.html

C#:   public string Greet() => Name;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjsqpzxyh.html

[G05] 继承
来源：http://dali.yuanzhike.top/Article/details/gtyhtcjvmx.html

Py:   class Admin(User): pass
来源：http://dali.sweek.top/Article/details/gttzxlicfs.html

PHP:  class Admin extends User {}
来源：http://dali.cashguo.top/Article/details/gtbjsckjlm.html

JS:   class Admin extends User {}
来源：http://dali.xuetiantiany.cn/Article/details/gtkcughtwq.html

TS:   class Admin extends User {}
来源：http://dali.redwolf501.top/Article/details/gtccihpgoq.html

Java: class Admin extends User {}
来源：http://dali.c1oappe.top/Article/details/gtuvpvaaly.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yj20258888.top/Article/details/gtupyeyayk.html

Ruby: class Admin < User; end
来源：http://dali.zhengqikj.top/Article/details/gthofgkxrw.html

C#:   class Admin : User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfsviebei.html

[G06] 重写方法
来源：http://dali.jlsjyb.cn/Article/details/gtxmwgeuuv.html

Py:   def greet(self): return "admin"
来源：http://dali.sxryk.cn/Article/details/gtagbtmtsr.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yuxming.cn/Article/details/gtesspdgad.html

JS:   greet() { return "admin"; }
来源：http://dali.xziqi.cn/Article/details/gtmjcmgntb.html

TS:   greet(): string { return "admin"; }
来源：http://dali.guowangkeji.top/Article/details/gttvpkzfly.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.guannengcc.top/Article/details/gtfpwjhbib.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hammf.cn/Article/details/gtahkqsmmj.html

Ruby: def greet; "admin"; end
来源：http://dali.cucudq.cn/Article/details/gtpjjbyoju.html

C#:   public override string Greet() => "admin";
来源：http://dali.jianghu66.top/Article/details/gtrkprnoeq.html

[G07] 调用父类方法
来源：http://dali.yuanzhike.top/Article/details/gtqabbeivh.html

Py:   super().greet()
来源：http://dali.sufxvd.cn/Article/details/gtyqxlmmje.html

PHP:  parent::greet();
来源：http://dali.xuanzx.com/Article/details/gtnqirhxee.html

JS:   super.greet();
来源：http://dali.sufxvd.cn/Article/details/gthogybzrj.html

TS:   super.greet();
来源：http://dali.yj20258.top/Article/details/gtajzyytjt.html

Java: super.greet();
来源：http://dali.nanxinkj.top/Article/details/gtnvfaqhry.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.ybcxt.top/Article/details/gtzdgadgfi.html

Ruby: super
来源：http://dali.aizwys.cn/Article/details/gtiopcppzz.html

C#:   base.Greet();
来源：http://dali.yuanzhike.top/Article/details/gthowdsxhz.html

[G08] 静态方法与属性
来源：http://dali.kuanghao11.cn/Article/details/gtzfanzxbg.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hysaishi.cn/Article/details/gtcvszjkfu.html

PHP:  public static function f() {}
来源：http://dali.ppjwa.cn/Article/details/gtxjvdiwee.html

JS:   static f() {}
来源：http://dali.dianchejie.cn/Article/details/gtysgaunxm.html

TS:   static f(): void {}
来源：http://dali.yuanzhike.top/Article/details/gtkmyxohyt.html

Java: static void f() {}
来源：http://dali.daria6918.cn/Article/details/gtbugfhhil.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yangfankeji.com/Article/details/gtaszelfdm.html

Ruby: def self.f; end
来源：http://dali.daria6918.cn/Article/details/gtgllqpzkx.html

C#:   public static void F() {}
来源：http://dali.xylfe.cn/Article/details/gtkkkxkdat.html

[G09] 接口 / 抽象类
来源：http://dali.redwolf501.top/Article/details/gtluohecra.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.316326.xyz/Article/details/gtpdecrdgi.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.tanke756.top/Article/details/gteiedntix.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hnqzz.top/Article/details/gtlzraduds.html

TS:   interface Shape { area(): number; }
来源：http://dali.0kj1m.cn/Article/details/gtvcattuqb.html

Java: interface Shape { double area(); }
来源：http://dali.yj20258.top/Article/details/gthcmtzuut.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.cheryme.top/Article/details/gtxqneamva.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.tanke756.top/Article/details/gtxstzdlke.html

C#:   interface IShape { double Area(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtsukycjuq.html

[G10] 访问控制
来源：http://dali.ybcxt.top/Article/details/gtrujvwdsd.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.guowangkeji.top/Article/details/gtsbjjvuqi.html

PHP:  public / protected / private
来源：http://dali.chenzaomai.com/Article/details/gtkaqzfwpz.html

JS:   #private 字段；其余公开
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmkjwntqe.html

TS:   public / protected / private
来源：http://dali.andypj.xyz/Article/details/gtcfnwaqng.html

Java: public / protected / private / 默认包级
来源：http://dali.shanyushiyangtech.top/Article/details/gtxzgwijaz.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.cdnleiting.top/Article/details/gtuzcirdhw.html

Ruby: public / protected / private
来源：http://dali.meibo888.top/Article/details/gtuizpclgs.html

C#:   public / protected / private / internal
来源：http://dali.9152youxi.cn/Article/details/gtbtfutmzz.html

[G11] getter / setter
来源：http://dali.sxryk.cn/Article/details/gtclcopydm.html

Py:   @property 与 @x.setter
来源：http://dali.jlsjyb.cn/Article/details/gtvyounvil.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.ivvv.top/Article/details/gteyojlfqz.html

JS:   get name() { return this._name; }
来源：http://dali.vqdsnc.cn/Article/details/gtjbesarlb.html

TS:   get name(): string { return this._name; }
来源：http://dali.jinqigfzy.top/Article/details/gtrrztkors.html

Java: public String getName() { return name; }
来源：http://dali.aizwys.cn/Article/details/gtvfnjevov.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.tianlin.xyz/Article/details/gtztyiejkn.html

Ruby: attr_accessor :name
来源：http://dali.guannengcc.top/Article/details/gtphyhwmzu.html

C#:   public string Name { get; set; }
来源：http://dali.yuanzhike.top/Article/details/gtligwqzdm.html

[G12] 对象转字符串
来源：http://dali.iojbl.cn/Article/details/gthbvnpcli.html

Py:   def __str__(self): return self.name
来源：http://dali.hywenlv.cn/Article/details/gtccstdjya.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.cashguo.top/Article/details/gtwmuugokz.html

JS:   toString() { return this.name; }
来源：http://dali.guannengcc.top/Article/details/gteskldpul.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gtbsifdtjl.html

Java: @Override public String toString() { return name; }
来源：http://dali.sysykeji.top/Article/details/gtkgwdylsr.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.shzxlz.cn/Article/details/gtnujzbdqq.html

Ruby: def to_s; @name; end
来源：http://dali.chenlongwang.top/Article/details/gtxtbkjpjo.html

C#:   public override string ToString() => Name;
来源：http://dali.jlsjyb.cn/Article/details/gtxwmneyyp.html

[G13] 判断对象类型
来源：http://dali.nanxinkj.top/Article/details/gtliunlwri.html

Py:   isinstance(u, User)
来源：http://dali.c1oappe.top/Article/details/gtchzgeawl.html

PHP:  $u instanceof User
来源：http://dali.xuetiantiany.cn/Article/details/gtugcqklvb.html

JS:   u instanceof User
来源：http://dali.chenjidiqi.icu/Article/details/gtpqupurce.html

TS:   u instanceof User
来源：http://dali.cheryme.top/Article/details/gtnftkdzkc.html

Java: u instanceof User
来源：http://dali.fzhhl.top/Article/details/gttdnavgao.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zdqjudy.top/Article/details/gtocbtnuks.html

Ruby: u.is_a?(User)
来源：http://dali.hysaishi.cn/Article/details/gtkiqubixc.html

C#:   u is User
来源：http://dali.zycfv.cn/Article/details/gtbydypltv.html

[G14] 数据类 / record
来源：http://dali.shuidangran.top/Article/details/gtedmbxswm.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.fzhhl.top/Article/details/gtynliporo.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yongpay.top/Article/details/gtuxvqpuof.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsawtaqtt.html

TS:   type User = { name: string; age: number };
来源：http://dali.jianghu66.top/Article/details/gtzvpxycmk.html

Java: record User(String name, int age) {}
来源：http://dali.dianchejie.cn/Article/details/gtodtnhadl.html

Go:   type User struct { Name string; Age int }
来源：http://dali.gogol.net.cn/Article/details/gtevvstgeg.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gtjewugjix.html

C#:   record User(string Name, int Age);
来源：http://dali.jyoumei.cn/Article/details/gtfqjfgooj.html

[G15] 枚举
来源：http://dali.cucudq.cn/Article/details/gtdbxocwvc.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.tanke756.top/Article/details/gtswnoixym.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yongpay.top/Article/details/gtuhqeigcv.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jinqigfzy.top/Article/details/gttxzanywk.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shuidangran.top/Article/details/gtidovjmqr.html

Java: enum Color { RED, GREEN }
来源：http://dali.cheryme.top/Article/details/gtzkuycmen.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.sufxvd.cn/Article/details/gtbgmipsnb.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yongpay.top/Article/details/gtstkgispf.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yvedp.cn/Article/details/gtzocqbcdv.html

[G16] 对象转数组 / 字典
来源：http://dali.nanxuanxn.top/Article/details/gtoolhfifs.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.ydzc1.top/Article/details/gtrlypnsqs.html

PHP:  get_object_vars($obj);
来源：http://dali.shzxlz.cn/Article/details/gtkxqbjrbh.html

JS:   Object.entries(obj)
来源：http://dali.c1oappe.top/Article/details/gtjzeilerd.html

TS:   Object.entries(obj)
来源：http://dali.daxiang520.top/Article/details/gtsiopkbvf.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhiwuduotai.top/Article/details/gtvdotmjkt.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhixingplan.top/Article/details/gtecyyquwy.html

Ruby: obj.instance_variables
来源：http://dali.aibaodan.cn/Article/details/gtigqserla.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.haohaochexian.top/Article/details/gtttdqyocn.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtpstasezq.html

H. 异常与错误处理
来源：http://dali.cheryme.top/Article/details/gtljxxbmgw.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtvayfuhbv.html

[H01] try / catch 基础
来源：http://dali.yj20258888.top/Article/details/gtoemgdlvo.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.hywenlv.cn/Article/details/gtdheuqyig.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.meibo888.top/Article/details/gtcwhjnonh.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbgyyjyim.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.shuidangran.top/Article/details/gtgqqghkjv.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.ivvv.top/Article/details/gtikstfqnv.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.xuetiantiany.cn/Article/details/gtbdiotlbr.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.cashguo.top/Article/details/gtqgqmbudo.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hfpthk.cn/Article/details/gtghothawq.html

[H02] finally / ensure 收尾
来源：http://dali.9152youxi.cn/Article/details/gtqlbabwhj.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtujanlcvt.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.gaohongyu789.top/Article/details/gtcatvdwos.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.daxiang520.top/Article/details/gtdivqnykd.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.bjfxy.top/Article/details/gtexswsusb.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gthkvacken.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jinghuilouyu.cn/Article/details/gthmljxhbi.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrpbjumzs.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.smart0.xyz/Article/details/gtlulojcil.html

[H03] 主动抛出异常
来源：http://dali.cqqwz.cn/Article/details/gtqzxktjkh.html

Py:   raise ValueError("错误信息")
来源：http://dali.daxiang520.top/Article/details/gtjhrspapu.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jinghuilouyu.cn/Article/details/gtdfnpdpvt.html

JS:   throw new Error("错误信息");
来源：http://dali.gogol.net.cn/Article/details/gtzfmjktxl.html

TS:   throw new Error("错误信息");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfllrhzre.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.bjfxy.top/Article/details/gtrhdfvyik.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.meibo888.top/Article/details/gtkfeqadde.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.xinyue.icu/Article/details/gttlzlgzuu.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhiwuduotai.top/Article/details/gtvleshhro.html

[H04] 自定义异常类型
来源：http://dali.nwbrower.top/Article/details/gtyosfqyge.html

Py:   class MyError(Exception): pass
来源：http://dali.ydzc1.top/Article/details/gtwrlehpsx.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.cdnleiting.top/Article/details/gtzoyozbsr.html

JS:   class MyError extends Error {}
来源：http://dali.c1oappe.top/Article/details/gthvauqgsj.html

TS:   class MyError extends Error {}
来源：http://dali.tian-w.cn/Article/details/gtovoplccn.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hammf.cn/Article/details/gtjsmqjinp.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.xylfe.cn/Article/details/gtcfifdadb.html

Ruby: class MyError < StandardError; end
来源：http://dali.shangyingyoupin.top/Article/details/gtrxqwbmhl.html

C#:   class MyException : Exception {}
来源：http://dali.daxiang520.top/Article/details/gthgypwlje.html

[H05] 捕获特定类型
来源：http://dali.yanxiufei.cn/Article/details/gttzamgqux.html

Py:   except ValueError as e:
来源：http://dali.316326.xyz/Article/details/gtudysznlq.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gtshoyixui.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jianghu66.top/Article/details/gtrvalrncr.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.pycfn.com/Article/details/gtxuoupgpg.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.nanxuanxn.top/Article/details/gtslrzprfk.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.vqdsnc.cn/Article/details/gtvgzcghfw.html

Ruby: rescue ArgumentError => e
来源：http://dali.jlsjyb.cn/Article/details/gtjmjryxra.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdenpbccy.html

[H06] 可选值 / 空值安全访问
来源：http://dali.wangdashe.top/Article/details/gtjrqmknuy.html


<!-- 参考信息 -->