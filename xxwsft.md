代发 wailian999

C#:   File.ReadAllText("a.txt");
来源：http://dali.sxryk.cn/Article/details/gttholcsyq.html

[F02] 逐行读取文件
来源：http://dali.shuidangran.top/Article/details/gtpkpmxysu.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.xuanzx.com/Article/details/gtjclgaquy.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yvedp.cn/Article/details/gtfuotnaaa.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.kuanghao11.cn/Article/details/gttdrfngbq.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zdqjudy.top/Article/details/gtjjbgnlip.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yanxiufei.cn/Article/details/gtnvezroac.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.guannengcc.top/Article/details/gtgstallob.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jlsjyb.cn/Article/details/gtizhcdakr.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.tanke756.top/Article/details/gtwvtgylyo.html

[F03] 写入文件（覆盖）
来源：http://dali.chenjidiqi.icu/Article/details/gtlyvgfeib.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhiwuduotai.top/Article/details/gtrvjcvlqr.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.ehwqpu.com/Article/details/gtiutuzpiq.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ywan-chungtsiang.top/Article/details/gteqkjpusx.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ivvv.top/Article/details/gtgomnsqkg.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jyoumei.cn/Article/details/gtgifzpspp.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhoulong.xyz/Article/details/gtnmpighdz.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.c1oappe.top/Article/details/gtqljwmkaw.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.0kj1m.cn/Article/details/gtlbpkyran.html

[F04] 追加写入文件
来源：http://dali.9152youxi.cn/Article/details/gtciuqjzcj.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwvxqycal.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.mhx1999.top/Article/details/gteuuvfsgk.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.dashuyun.cn/Article/details/gtdvtobmqa.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gzhubu.top/Article/details/gtklhatbrz.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.shzxlz.cn/Article/details/gtttsesfgw.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.guowangkeji.top/Article/details/gtfitctjlp.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.gaohongyu789.top/Article/details/gtgxzurcvf.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.guannengcc.top/Article/details/gteeppovlg.html

[F05] 判断文件或目录是否存在
来源：http://dali.chenzaomai.com/Article/details/gtxtcgqcqp.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.c1oappe.top/Article/details/gtnxobneti.html

PHP:  file_exists("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnwxiicba.html

JS:   fs.existsSync("a.txt")
来源：http://dali.ivvv.top/Article/details/gtuaatwuct.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtcdfkfwsl.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.shuidangran.top/Article/details/gtixulsdjv.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.meibo888.top/Article/details/gtmreoeekp.html

Ruby: File.exist?("a.txt")
来源：http://dali.c1oappe.top/Article/details/gthhdauano.html

C#:   File.Exists("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtegshmynd.html

[F06] 删除文件
来源：http://dali.dianchejie.cn/Article/details/gtdtbglcjz.html

Py:   os.remove("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtehjdjbpc.html

PHP:  unlink("a.txt");
来源：http://dali.dashuyun.cn/Article/details/gtxfavsvco.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtmvqjcugx.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtqwarrgsl.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.snrcjt.cn/Article/details/gtbycuklwp.html

Go:   os.Remove("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtbsqgsglt.html

Ruby: File.delete("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtyfdyaqms.html

C#:   File.Delete("a.txt");
来源：http://dali.birdmap.top/Article/details/gtipohmstq.html

[F07] 创建目录（含多级）
来源：http://dali.ybcxt.top/Article/details/gtpfdkyxfj.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yongpay.top/Article/details/gterbziccr.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.vqdsnc.cn/Article/details/gtuakbpajm.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.dashuyun.cn/Article/details/gtnhizamcb.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.aibaodan.cn/Article/details/gtlemovbrg.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.cucudq.cn/Article/details/gturpnckps.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.pengpengdd.cyou/Article/details/gtqopfivbf.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.aibaodan.cn/Article/details/gttmdefohf.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yj20258.top/Article/details/gtqbpmglgf.html

[F08] 遍历目录
来源：http://dali.nanxuanxn.top/Article/details/gtyvalwkfx.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.shzxlz.cn/Article/details/gtxoldezwc.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yueranfly.top/Article/details/gtunargcpv.html

JS:   fs.readdirSync("dir")
来源：http://dali.ehwqpu.com/Article/details/gtzskmxdyu.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhoulong.xyz/Article/details/gtnkbdvrta.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.cheryme.top/Article/details/gtuaiyzisw.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yvedp.cn/Article/details/gtqmbsgktu.html

Ruby: Dir.children("dir")
来源：http://dali.mhx1999.top/Article/details/gtatgdjnnj.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jqgfzy.top/Article/details/gtpnvhpots.html

[F09] 获取文件大小
来源：http://dali.fengsongda.top/Article/details/gtlukiqokd.html

Py:   os.path.getsize("a.txt")
来源：http://dali.shuidangran.top/Article/details/gtaavpqfls.html

PHP:  filesize("a.txt");
来源：http://dali.aibaodan.cn/Article/details/gtfxqsfipb.html

JS:   fs.statSync("a.txt").size
来源：http://dali.wangdashe.top/Article/details/gtqikbuarg.html

TS:   fs.statSync("a.txt").size
来源：http://dali.hongshengwenyu.top/Article/details/gtzwauasni.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.wangdashe.top/Article/details/gticuxkotg.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.mhx1999.top/Article/details/gtkkizbbdb.html

Ruby: File.size("a.txt")
来源：http://dali.tian-w.cn/Article/details/gtmzkcxmbh.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gtalihaphl.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.pengpengdd.cyou/Article/details/gtbdhnwnux.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.bjfxy.top/Article/details/gtrkmryula.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zycfv.cn/Article/details/gthpunrger.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.birdmap.top/Article/details/gtdruzryeq.html

TS:   path.extname("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtpthswrgp.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hysaishi.cn/Article/details/gtcrukmrec.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtpqecnhdp.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtzjiyunof.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.c1oappe.top/Article/details/gtckrfmdzb.html

[F11] 复制与移动文件
来源：http://dali.cashguo.top/Article/details/gtqtsdchnu.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.haohaochexian.top/Article/details/gtqjxaeqhj.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.gaohongyu789.top/Article/details/gtlipssfjf.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtcfwrkzct.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.daxiang520.top/Article/details/gtmdlrhvec.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.aizwys.cn/Article/details/gtkrcpntdl.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.aibaodan.cn/Article/details/gtzhuycjnw.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtsskffzpk.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.hnxiangtu.top/Article/details/gtgduylkbm.html

[F12] CSV 读写
来源：http://dali.hnqzz.top/Article/details/gtgqmzbbbm.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.iojbl.cn/Article/details/gtktsfmvgi.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hnqzz.top/Article/details/gtppfqqkcs.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.gogol.net.cn/Article/details/gtskffdgma.html

TS:   // 同上
来源：http://dali.ydzc1.top/Article/details/gtvqcgtgrv.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hongshengwenyu.top/Article/details/gtbtgofalf.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.ppjwa.cn/Article/details/gtufhhtrwk.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.svipenyu.cn/Article/details/gtvbgyqzrb.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhengqikj.top/Article/details/gtlmsqusga.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtlwfolwax.html

G. 面向对象
来源：http://dali.ydzc1.top/Article/details/gtfkeekofs.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtapqlxicn.html

[G01] 定义类
来源：http://dali.0kj1m.cn/Article/details/gtnavqjqfx.html

Py:   class User: pass
来源：http://dali.cheryme.top/Article/details/gtuwxmyczl.html

PHP:  class User {}
来源：http://dali.nwbrower.top/Article/details/gtvxiptgkn.html

JS:   class User {}
来源：http://dali.hfpthk.cn/Article/details/gtaneuhzuf.html

TS:   class User { name: string = ""; }
来源：http://dali.yj20258.top/Article/details/gtiuvbfipn.html

Java: class User {}
来源：http://dali.sxryk.cn/Article/details/gtemhhljax.html

Go:   type User struct { Name string }
来源：http://dali.cdnleiting.top/Article/details/gtlrguhvnd.html

Ruby: class User; end
来源：http://dali.shangyingyoupin.top/Article/details/gtyaqvwyqm.html

C#:   class User {}
来源：http://dali.meibo888.top/Article/details/gtgktixpij.html

[G02] 构造函数
来源：http://dali.nanxuanxn.top/Article/details/gttsbomeln.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoycyrdew.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.ydzc1.top/Article/details/gtkldfgdys.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.quarkkingdee.top/Article/details/gtznxggzdq.html

TS:   constructor(public name: string) {}
来源：http://dali.yj202588.top/Article/details/gtpxulzpof.html

Java: User(String name) { this.name = name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtujqenupc.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.smart0.xyz/Article/details/gtebgkgujm.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yangfankeji.com/Article/details/gtnahewbph.html

C#:   public User(string name) { Name = name; }
来源：http://dali.redwolf501.top/Article/details/gtcjgkxpfp.html

[G03] 实例属性
来源：http://dali.feifeiyinyue.top/Article/details/gttdvkojwm.html

Py:   self.name = "x"
来源：http://dali.jiagoushi.top/Article/details/gtwcstxoke.html

PHP:  public string $name = "x";
来源：http://dali.316326.xyz/Article/details/gtyugkpsij.html

JS:   this.name = "x";
来源：http://dali.vqdsnc.cn/Article/details/gtclszqtzu.html

TS:   name: string = "x";
来源：http://dali.xuanzx.com/Article/details/gthjyjyohf.html

Java: private String name;
来源：http://dali.dianchejie.cn/Article/details/gtwxlkraay.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdlvcwwlr.html

Ruby: @name = "x"
来源：http://dali.svipenyu.cn/Article/details/gtaksflpts.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.tanke756.top/Article/details/gtqqzimeqx.html

[G04] 定义方法
来源：http://dali.shanyushiyangtech.top/Article/details/gtwrqwhylo.html

Py:   def greet(self): return self.name
来源：http://dali.jyoumei.cn/Article/details/gtnupavclf.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.nanxuanxn.top/Article/details/gtfasntwuq.html

JS:   greet() { return this.name; }
来源：http://dali.yueranfly.top/Article/details/gtoncuzfvu.html

TS:   greet(): string { return this.name; }
来源：http://dali.jiagoushi.top/Article/details/gtjbmhsmmj.html

Java: String greet() { return name; }
来源：http://dali.cashguo.top/Article/details/gtrzyuewmw.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjhycegwc.html

Ruby: def greet; @name; end
来源：http://dali.fengsongda.top/Article/details/gtduakeafc.html

C#:   public string Greet() => Name;
来源：http://dali.meibo888.top/Article/details/gtnwcfwuac.html

[G05] 继承
来源：http://dali.iojbl.cn/Article/details/gtoryskmhk.html

Py:   class Admin(User): pass
来源：http://dali.haohaochexian.top/Article/details/gtsckyephk.html

PHP:  class Admin extends User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlmbaxcnk.html

JS:   class Admin extends User {}
来源：http://dali.yueranfly.top/Article/details/gtqixbgadn.html

TS:   class Admin extends User {}
来源：http://dali.vqdsnc.cn/Article/details/gtxwcpqonz.html

Java: class Admin extends User {}
来源：http://dali.jqgfzy.top/Article/details/gtadbrowyw.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.c1oappe.top/Article/details/gterckscfc.html

Ruby: class Admin < User; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrajuuhss.html

C#:   class Admin : User {}
来源：http://dali.ppjwa.cn/Article/details/gtltrjaadm.html

[G06] 重写方法
来源：http://dali.nanxuanxn.top/Article/details/gtlymfqblm.html

Py:   def greet(self): return "admin"
来源：http://dali.birdmap.top/Article/details/gtxtemaxdu.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.sufxvd.cn/Article/details/gtonjyssgu.html

JS:   greet() { return "admin"; }
来源：http://dali.guannengcc.top/Article/details/gtzifuetbm.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbezwhuys.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.tanke756.top/Article/details/gtdhwjkggp.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.vqdsnc.cn/Article/details/gttevsaksy.html

Ruby: def greet; "admin"; end
来源：http://dali.xinyue.icu/Article/details/gtanfoykij.html

C#:   public override string Greet() => "admin";
来源：http://dali.ppjwa.cn/Article/details/gtduhnufoe.html

[G07] 调用父类方法
来源：http://dali.shuidangran.top/Article/details/gtjtiuwazh.html

Py:   super().greet()
来源：http://dali.haohaochexian.top/Article/details/gtrwykccxr.html

PHP:  parent::greet();
来源：http://dali.hongshengwenyu.top/Article/details/gtjhwpdome.html

JS:   super.greet();
来源：http://dali.jlsjyb.cn/Article/details/gtvyzxwcrh.html

TS:   super.greet();
来源：http://dali.jiagoushi.top/Article/details/gthuseiwqz.html

Java: super.greet();
来源：http://dali.shangyingyoupin.top/Article/details/gtaejzcdjv.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.cqqwz.cn/Article/details/gtdhkbtnbg.html

Ruby: super
来源：http://dali.vqdsnc.cn/Article/details/gtlhrwznyq.html

C#:   base.Greet();
来源：http://dali.andypj.xyz/Article/details/gtxnqfwcag.html

[G08] 静态方法与属性
来源：http://dali.cdnleiting.top/Article/details/gtgmjfnira.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.chenlongwang.top/Article/details/gtoounbgiu.html

PHP:  public static function f() {}
来源：http://dali.ybcxt.top/Article/details/gtwygvlcpz.html

JS:   static f() {}
来源：http://dali.jlsjyb.cn/Article/details/gtnqypvhjk.html

TS:   static f(): void {}
来源：http://dali.hammf.cn/Article/details/gtdbqgnqsn.html

Java: static void f() {}
来源：http://dali.cashguo.top/Article/details/gtwtjmojkl.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.sysykeji.top/Article/details/gtkrnkijrx.html

Ruby: def self.f; end
来源：http://dali.daria6918.cn/Article/details/gtyogkdhwd.html

C#:   public static void F() {}
来源：http://dali.yuanzhike.top/Article/details/gtdofsnvsk.html

[G09] 接口 / 抽象类
来源：http://dali.tian-w.cn/Article/details/gtpudqzpts.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhongyouzk.top/Article/details/gtanoollug.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.kuanghao11.cn/Article/details/gthkeikmre.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhixingplan.top/Article/details/gtagmhnypz.html

TS:   interface Shape { area(): number; }
来源：http://dali.shangyingyoupin.top/Article/details/gtinaxwbtc.html

Java: interface Shape { double area(); }
来源：http://dali.svipenyu.cn/Article/details/gtautxflxi.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.dashuyun.cn/Article/details/gtxmkvjvlp.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhengqikj.top/Article/details/gtqnjfsrnq.html

C#:   interface IShape { double Area(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtsybhwyra.html

[G10] 访问控制
来源：http://dali.jqgufenzy.top/Article/details/gtuumtchqe.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlximbgut.html

PHP:  public / protected / private
来源：http://dali.smart0.xyz/Article/details/gtdrmmnajy.html

JS:   #private 字段；其余公开
来源：http://dali.yuanzhike.top/Article/details/gtbxgwgdtr.html

TS:   public / protected / private
来源：http://dali.316326.xyz/Article/details/gtaqxlbgiu.html

Java: public / protected / private / 默认包级
来源：http://dali.pengpengdd.cyou/Article/details/gtmmybfblc.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.birdmap.top/Article/details/gtzrjbdztf.html

Ruby: public / protected / private
来源：http://dali.aibaodan.cn/Article/details/gttealhvck.html

C#:   public / protected / private / internal
来源：http://dali.jinyuanbaomall.cn/Article/details/gtujjzqcyk.html

[G11] getter / setter
来源：http://dali.ywan-chungtsiang.top/Article/details/gtazwdovmy.html

Py:   @property 与 @x.setter
来源：http://dali.gogol.net.cn/Article/details/gtapfowabd.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.tian-w.cn/Article/details/gtyhkdzhtw.html

JS:   get name() { return this._name; }
来源：http://dali.aibaodan.cn/Article/details/gtlsxossjv.html

TS:   get name(): string { return this._name; }
来源：http://dali.jinqigufen.top/Article/details/gtemefzvur.html

Java: public String getName() { return name; }
来源：http://dali.yueranfly.top/Article/details/gtwvwswnse.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhengqikj.top/Article/details/gthabqtrmd.html

Ruby: attr_accessor :name
来源：http://dali.snrcjt.cn/Article/details/gtlajitokh.html

C#:   public string Name { get; set; }
来源：http://dali.mhx1999.top/Article/details/gtdylbetlh.html

[G12] 对象转字符串
来源：http://dali.yuanzhike.top/Article/details/gttebozmfz.html

Py:   def __str__(self): return self.name
来源：http://dali.jyoumei.cn/Article/details/gtnmgxtmow.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.9152youxi.cn/Article/details/gtntydnubw.html

JS:   toString() { return this.name; }
来源：http://dali.daxiang520.top/Article/details/gtsbfmbkbl.html

TS:   toString(): string { return this.name; }
来源：http://dali.mhx1999.top/Article/details/gtipycgcsd.html

Java: @Override public String toString() { return name; }
来源：http://dali.gaohongyu789.top/Article/details/gtqxszbcmn.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.meibo888.top/Article/details/gtpifzmfqd.html

Ruby: def to_s; @name; end
来源：http://dali.hysaishi.cn/Article/details/gtbnuxzqmf.html

C#:   public override string ToString() => Name;
来源：http://dali.xuanzx.com/Article/details/gtknbarnzs.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gtjeysgwbl.html

Py:   isinstance(u, User)
来源：http://dali.sweek.top/Article/details/gtaogknfry.html

PHP:  $u instanceof User
来源：http://dali.hfpthk.cn/Article/details/gtwfhaazjf.html

JS:   u instanceof User
来源：http://dali.cucudq.cn/Article/details/gtozpmfhxd.html

TS:   u instanceof User
来源：http://dali.ppjwa.cn/Article/details/gtlaunghxh.html

Java: u instanceof User
来源：http://dali.jlsjyb.cn/Article/details/gtehgrshai.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.pycfn.com/Article/details/gtfadmyrlk.html

Ruby: u.is_a?(User)
来源：http://dali.xylfe.cn/Article/details/gtwwubyfus.html

C#:   u is User
来源：http://dali.sxryk.cn/Article/details/gtewxymwat.html

[G14] 数据类 / record
来源：http://dali.hnxiangtu.top/Article/details/gtqddvpath.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.quarkkingdee.top/Article/details/gtheofylgs.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hfpthk.cn/Article/details/gtevecfblz.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.smart0.xyz/Article/details/gtnotqxkyz.html

TS:   type User = { name: string; age: number };
来源：http://dali.meibo888.top/Article/details/gtpfwtzwhh.html

Java: record User(String name, int age) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtvdihdgsv.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yangfankeji.com/Article/details/gtfrpkjvrl.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.ybcxt.top/Article/details/gtrxmafooq.html

C#:   record User(string Name, int Age);
来源：http://dali.ppjwa.cn/Article/details/gtgpznibwf.html

[G15] 枚举
来源：http://dali.pengpengdd.cyou/Article/details/gtzhqymaqb.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.ivvv.top/Article/details/gttmjxluag.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.xuanzx.com/Article/details/gtdvabence.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.gzhubu.top/Article/details/gtzgvkmcaf.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hywenlv.cn/Article/details/gtyvchydwf.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhongyouzk.top/Article/details/gtlztotogx.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yuxming.cn/Article/details/gtyghvysyt.html

Ruby: Color = %i[red green].freeze
来源：http://dali.cheryme.top/Article/details/gtcfyhmaoq.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.guannengcc.top/Article/details/gtetddphkl.html

[G16] 对象转数组 / 字典
来源：http://dali.fengsongda.top/Article/details/gtwbnsndsl.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zycfv.cn/Article/details/gtmffkaoam.html

PHP:  get_object_vars($obj);
来源：http://dali.mhx1999.top/Article/details/gtkkuashil.html

JS:   Object.entries(obj)
来源：http://dali.cdnleiting.top/Article/details/gtaghnvhhj.html

TS:   Object.entries(obj)
来源：http://dali.sysykeji.top/Article/details/gtrnkftphx.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxhkbccyb.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.0kj1m.cn/Article/details/gthtohhzdi.html

Ruby: obj.instance_variables
来源：http://dali.xylfe.cn/Article/details/gtrmkacxbm.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yvedp.cn/Article/details/gtezvaueri.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtsvdcacst.html

H. 异常与错误处理
来源：http://dali.jyoumei.cn/Article/details/gtobzfomiz.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtjgkkjvmj.html

[H01] try / catch 基础
来源：http://dali.shzxlz.cn/Article/details/gtbwwebjwp.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.ybcxt.top/Article/details/gtldtryfxe.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.chenzaomai.com/Article/details/gtcvamwxvf.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.shangyingyoupin.top/Article/details/gtqlpftzmy.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.nanxinkj.top/Article/details/gtllxzldti.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.pycfn.com/Article/details/gtwnspcrxl.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.redwolf501.top/Article/details/gtclmdwuoa.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.redwolf501.top/Article/details/gtnyhsdnuu.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.chenjidiqi.icu/Article/details/gtkxhrlvzf.html

[H02] finally / ensure 收尾
来源：http://dali.pengpengdd.cyou/Article/details/gtnnrznmhi.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.nanxuanxn.top/Article/details/gtgvzgnoqr.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.xziqi.cn/Article/details/gtswkmhzrl.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yuxming.cn/Article/details/gtuuupmivt.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.smart0.xyz/Article/details/gtudusuwlm.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.xylfe.cn/Article/details/gtttpnhkrg.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.kuanghao11.cn/Article/details/gtxhsbkpry.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.wangdashe.top/Article/details/gtwgnojoet.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.aibaodan.cn/Article/details/gtvhuusmom.html

[H03] 主动抛出异常
来源：http://dali.cucudq.cn/Article/details/gtrtpsxhon.html

Py:   raise ValueError("错误信息")
来源：http://dali.wangshuangyany.cn/Article/details/gtzumifdbx.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.birdmap.top/Article/details/gtybanarzt.html

JS:   throw new Error("错误信息");
来源：http://dali.fengsongda.top/Article/details/gtuzfexyru.html

TS:   throw new Error("错误信息");
来源：http://dali.jinqigufen.top/Article/details/gtarzphwza.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfcgtdfuj.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.c1oappe.top/Article/details/gtrnivwyih.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jinqigufen.top/Article/details/gtlolkegpv.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.daria6918.cn/Article/details/gttbhstlzv.html

[H04] 自定义异常类型
来源：http://dali.tianlin.xyz/Article/details/gtndtcmmgs.html

Py:   class MyError(Exception): pass
来源：http://dali.xuetiantiany.cn/Article/details/gtcymmkput.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yueranfly.top/Article/details/gtqxpstlnf.html

JS:   class MyError extends Error {}
来源：http://dali.zhoulong.xyz/Article/details/gtwjabhkui.html

TS:   class MyError extends Error {}
来源：http://dali.bjfxy.top/Article/details/gtuybalmkj.html

Java: class MyException extends RuntimeException {}
来源：http://dali.9152youxi.cn/Article/details/gtpxtugzuv.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlzveyshb.html

Ruby: class MyError < StandardError; end
来源：http://dali.gzhubu.top/Article/details/gtoidzpeny.html

C#:   class MyException : Exception {}
来源：http://dali.meibo888.top/Article/details/gtnbsexlxr.html

[H05] 捕获特定类型
来源：http://dali.nanxinkj.top/Article/details/gtckscdwys.html

Py:   except ValueError as e:
来源：http://dali.yongpay.top/Article/details/gtjwsypysd.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnputvvml.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.redwolf501.top/Article/details/gtirctyade.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jyoumei.cn/Article/details/gtnubklwhw.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.guowangkeji.top/Article/details/gtqtrrxndb.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.vqdsnc.cn/Article/details/gtzhsqazgy.html

Ruby: rescue ArgumentError => e
来源：http://dali.snrcjt.cn/Article/details/gtposwiqqf.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhixingplan.top/Article/details/gtcfuqpiav.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zycfv.cn/Article/details/gtamxhextt.html

Py:   value = d.get("k") or default
来源：http://dali.mhx1999.top/Article/details/gtfdnyljxw.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yj20258.top/Article/details/gtwofkcugu.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.cqqwz.cn/Article/details/gtulmvjoet.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.ivvv.top/Article/details/gtifuwcsli.html


<!-- 参考信息 -->