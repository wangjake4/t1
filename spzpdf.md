代发 wailian999

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.quarkkingdee.top/Article/details/gtoaxqzzmy.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.hammf.cn/Article/details/gtupfoaqby.html

[F03] 写入文件（覆盖）
来源：http://dali.xuetiantiany.cn/Article/details/gtglgczdzn.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhoulong.xyz/Article/details/gtcxmsikik.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.hysaishi.cn/Article/details/gtshtjshzm.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyiqfzgpf.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xylfe.cn/Article/details/gtcckdjnnx.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.pengpengdd.cyou/Article/details/gtuyfoocvg.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yueranfly.top/Article/details/gtlsrhcepl.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.316326.xyz/Article/details/gtaoanjymn.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.sysykeji.top/Article/details/gtmqhccjog.html

[F04] 追加写入文件
来源：http://dali.yuxming.cn/Article/details/gtyqnjjari.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.pengpengdd.cyou/Article/details/gtxrthrxmd.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jqgfzy.top/Article/details/gtnnwmlkfl.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shangyingyoupin.top/Article/details/gtkahuuebc.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sweek.top/Article/details/gtmgqmaidz.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.aibaodan.cn/Article/details/gtupmasoxs.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.guowangkeji.top/Article/details/gtyrvqpmzx.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.chenlongwang.top/Article/details/gtkrzqmifq.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jqgfzy.top/Article/details/gtaglggphu.html

[F05] 判断文件或目录是否存在
来源：http://dali.redwolf501.top/Article/details/gtqzsbduru.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.sufxvd.cn/Article/details/gtobmyzewf.html

PHP:  file_exists("a.txt");
来源：http://dali.jianghu66.top/Article/details/gtmvknwpbp.html

JS:   fs.existsSync("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtrjomkcib.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtdlvmpstl.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.hywenlv.cn/Article/details/gtzbqsyetj.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jqgfzy.top/Article/details/gtpooyxyqq.html

Ruby: File.exist?("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtqahhggua.html

C#:   File.Exists("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtemrzsvsi.html

[F06] 删除文件
来源：http://dali.sxryk.cn/Article/details/gttqwxrsnp.html

Py:   os.remove("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtibeeysmh.html

PHP:  unlink("a.txt");
来源：http://dali.yj20258888.top/Article/details/gtlwlhtgyj.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.xuanzx.com/Article/details/gttowtarks.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtdhyknylf.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbfwzcnjc.html

Go:   os.Remove("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtkuycxfyr.html

Ruby: File.delete("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtarkniass.html

C#:   File.Delete("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gtlxkoobyf.html

[F07] 创建目录（含多级）
来源：http://dali.smart0.xyz/Article/details/gtxyfuceam.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gtryazycfy.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yj20258.top/Article/details/gttuzdasks.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jyoumei.cn/Article/details/gtsemcoydv.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxpkazntq.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.fengsongda.top/Article/details/gthsymuqlx.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.ydzc1.top/Article/details/gtvnumpize.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.hnqzz.top/Article/details/gtyxzparmn.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.fzhhl.top/Article/details/gttbcsjrdz.html

[F08] 遍历目录
来源：http://dali.sysykeji.top/Article/details/gtiiplzitn.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.iojbl.cn/Article/details/gtyazhplfo.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yvedp.cn/Article/details/gtrzxmjqku.html

JS:   fs.readdirSync("dir")
来源：http://dali.ybcxt.top/Article/details/gtygpwhcel.html

TS:   fs.readdirSync("dir")
来源：http://dali.jlsjyb.cn/Article/details/gtvacdheje.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.cheryme.top/Article/details/gtkpygbmci.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhengqikj.top/Article/details/gtzdhetttz.html

Ruby: Dir.children("dir")
来源：http://dali.svipenyu.cn/Article/details/gtmximawku.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhongyouzk.top/Article/details/gtbtnahiry.html

[F09] 获取文件大小
来源：http://dali.fengsongda.top/Article/details/gthryjbnep.html

Py:   os.path.getsize("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtlqkkuqxj.html

PHP:  filesize("a.txt");
来源：http://dali.wangdashe.top/Article/details/gtomswoecz.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jinqigfzy.top/Article/details/gtdcwytdgk.html

TS:   fs.statSync("a.txt").size
来源：http://dali.shzxlz.cn/Article/details/gtaxckauqm.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jinghuilouyu.cn/Article/details/gtcslkmkig.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.tianlin.xyz/Article/details/gtljzrqopu.html

Ruby: File.size("a.txt")
来源：http://dali.bjfxy.top/Article/details/gtvvzbczru.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.fzhhl.top/Article/details/gtpxvocbtq.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hnqzz.top/Article/details/gtwfdnzwse.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtwnkflqpm.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.ehwqpu.com/Article/details/gtdlbmsdpo.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.iojbl.cn/Article/details/gtiyldzsqm.html

TS:   path.extname("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtfnfeldsd.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.chenlongwang.top/Article/details/gtogfipewt.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.sweek.top/Article/details/gtcwyuccwx.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.fzhhl.top/Article/details/gtvfztrjqo.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.shzxlz.cn/Article/details/gttitridkq.html

[F11] 复制与移动文件
来源：http://dali.jqgufenzy.top/Article/details/gtwddptdcr.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtagxnebnb.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.svipenyu.cn/Article/details/gtiomrevmx.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yongpay.top/Article/details/gtipvuvubl.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hfpthk.cn/Article/details/gtxjmofqrn.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.guowangkeji.top/Article/details/gtdbyfoyzg.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.cashguo.top/Article/details/gtozxvlpqb.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.sysykeji.top/Article/details/gtyiopsijr.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.sweek.top/Article/details/gtshlvgmrx.html

[F12] CSV 读写
来源：http://dali.hammf.cn/Article/details/gtekykxrfc.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.tian-w.cn/Article/details/gtuxenrvjw.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.smart0.xyz/Article/details/gtzdqylekw.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jqgfzy.top/Article/details/gtnyrosrmw.html

TS:   // 同上
来源：http://dali.hnqzz.top/Article/details/gtouxnagbi.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.shanyushiyangtech.top/Article/details/gtequocntj.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.fengsongda.top/Article/details/gtggyvvucs.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jianghu66.top/Article/details/gtmsduyuld.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgutzsvuo.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtkelfjvhk.html

G. 面向对象
来源：http://dali.snrcjt.cn/Article/details/gtptfvavwj.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtgudalmlk.html

[G01] 定义类
来源：http://dali.sweek.top/Article/details/gtbahtqnsy.html

Py:   class User: pass
来源：http://dali.jinqigufen.top/Article/details/gtixvkfvxv.html

PHP:  class User {}
来源：http://dali.bjfxy.top/Article/details/gtghuuvqll.html

JS:   class User {}
来源：http://dali.xuanzx.com/Article/details/gthuzzwrsj.html

TS:   class User { name: string = ""; }
来源：http://dali.cheryme.top/Article/details/gtaqwrlvuc.html

Java: class User {}
来源：http://dali.chenlongwang.top/Article/details/gtczuilxrn.html

Go:   type User struct { Name string }
来源：http://dali.guowangkeji.top/Article/details/gtbiukciun.html

Ruby: class User; end
来源：http://dali.sxryk.cn/Article/details/gtytmvjxwa.html

C#:   class User {}
来源：http://dali.yj20258888.top/Article/details/gtkodxmtkq.html

[G02] 构造函数
来源：http://dali.shuidangran.top/Article/details/gthdnfwhfu.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.hammf.cn/Article/details/gtjmrsjlgw.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtafxrigij.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yangfankeji.com/Article/details/gtnayzymrh.html

TS:   constructor(public name: string) {}
来源：http://dali.ivvv.top/Article/details/gtnntnehao.html

Java: User(String name) { this.name = name; }
来源：http://dali.snrcjt.cn/Article/details/gtpophkbuo.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.shangyingyoupin.top/Article/details/gtzqljzdsm.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jianghu66.top/Article/details/gtznmwgmmj.html

C#:   public User(string name) { Name = name; }
来源：http://dali.hywenlv.cn/Article/details/gtiwsghtml.html

[G03] 实例属性
来源：http://dali.chenlongwang.top/Article/details/gtmnoogpgt.html

Py:   self.name = "x"
来源：http://dali.zhoulong.xyz/Article/details/gttgrmpgtu.html

PHP:  public string $name = "x";
来源：http://dali.cheryme.top/Article/details/gtfcuvoieo.html

JS:   this.name = "x";
来源：http://dali.yanxiufei.cn/Article/details/gtakgsptiq.html

TS:   name: string = "x";
来源：http://dali.xuanzx.com/Article/details/gtxgadospa.html

Java: private String name;
来源：http://dali.jianghu66.top/Article/details/gtynczzfac.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcqoqwxyw.html

Ruby: @name = "x"
来源：http://dali.xuanzx.com/Article/details/gtgpksbzmh.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.hfpthk.cn/Article/details/gtckrvymcc.html

[G04] 定义方法
来源：http://dali.zhiwuduotai.top/Article/details/gtxmskuqtn.html

Py:   def greet(self): return self.name
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrtpdgsnm.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.nanxuanxn.top/Article/details/gttgmrraqa.html

JS:   greet() { return this.name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtisfczael.html

TS:   greet(): string { return this.name; }
来源：http://dali.nanxinkj.top/Article/details/gtmvzuikkw.html

Java: String greet() { return name; }
来源：http://dali.haohaochexian.top/Article/details/gtqrubsjax.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.vqdsnc.cn/Article/details/gtepswvzol.html

Ruby: def greet; @name; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpmufkzvd.html

C#:   public string Greet() => Name;
来源：http://dali.daxiang520.top/Article/details/gtpisensrh.html

[G05] 继承
来源：http://dali.sxryk.cn/Article/details/gtvifntpox.html

Py:   class Admin(User): pass
来源：http://dali.hammf.cn/Article/details/gtsqbmzkzv.html

PHP:  class Admin extends User {}
来源：http://dali.chenzaomai.com/Article/details/gtpmsavtqk.html

JS:   class Admin extends User {}
来源：http://dali.aizwys.cn/Article/details/gtwxlzxebe.html

TS:   class Admin extends User {}
来源：http://dali.yvedp.cn/Article/details/gttnnmgnxk.html

Java: class Admin extends User {}
来源：http://dali.xinyue.icu/Article/details/gtzdpbwdge.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yuxming.cn/Article/details/gtkzmxvdlt.html

Ruby: class Admin < User; end
来源：http://dali.hnqzz.top/Article/details/gtjkojrwnz.html

C#:   class Admin : User {}
来源：http://dali.meibo888.top/Article/details/gtrjdlppim.html

[G06] 重写方法
来源：http://dali.quarkkingdee.top/Article/details/gtpkrjecrd.html

Py:   def greet(self): return "admin"
来源：http://dali.iojbl.cn/Article/details/gtrqnwdvxy.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtukwwqemu.html

JS:   greet() { return "admin"; }
来源：http://dali.bjfxy.top/Article/details/gtsvakrcxw.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhixingplan.top/Article/details/gtkzcwjorp.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.tanke756.top/Article/details/gtckcfmszq.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.wangdashe.top/Article/details/gtutcddabm.html

Ruby: def greet; "admin"; end
来源：http://dali.yuanzhike.top/Article/details/gtktyroneu.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gthndwxrtt.html

[G07] 调用父类方法
来源：http://dali.aizwys.cn/Article/details/gtisbddeac.html

Py:   super().greet()
来源：http://dali.jinqigfzy.top/Article/details/gtgkkimkqb.html

PHP:  parent::greet();
来源：http://dali.smart0.xyz/Article/details/gtihchhwcm.html

JS:   super.greet();
来源：http://dali.yj20258.top/Article/details/gtahqfiseg.html

TS:   super.greet();
来源：http://dali.guannengcc.top/Article/details/gtnpcpbnin.html

Java: super.greet();
来源：http://dali.vqdsnc.cn/Article/details/gtwibzmffp.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.meibo888.top/Article/details/gtyvrvjrwu.html

Ruby: super
来源：http://dali.daria6918.cn/Article/details/gtnczgctpf.html

C#:   base.Greet();
来源：http://dali.zhiwuduotai.top/Article/details/gtcivgbvmb.html

[G08] 静态方法与属性
来源：http://dali.jqgufenzy.top/Article/details/gtaekwnrme.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.9152youxi.cn/Article/details/gtzwygoksx.html

PHP:  public static function f() {}
来源：http://dali.chenzaomai.com/Article/details/gtpkgtdxuw.html

JS:   static f() {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfuferwln.html

TS:   static f(): void {}
来源：http://dali.cheryme.top/Article/details/gthdphxghm.html

Java: static void f() {}
来源：http://dali.zhongyouzk.top/Article/details/gtemvgwdow.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jinqigfzy.top/Article/details/gtnrlhtiem.html

Ruby: def self.f; end
来源：http://dali.yuxming.cn/Article/details/gthxymrycq.html

C#:   public static void F() {}
来源：http://dali.svipenyu.cn/Article/details/gteymzkdyq.html

[G09] 接口 / 抽象类
来源：http://dali.yuxming.cn/Article/details/gtcpezcvol.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.fengsongda.top/Article/details/gtdhidmgou.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.cucudq.cn/Article/details/gtpgevpngu.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.cdnleiting.top/Article/details/gtqoeszkim.html

TS:   interface Shape { area(): number; }
来源：http://dali.cqqwz.cn/Article/details/gtywtckjuj.html

Java: interface Shape { double area(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtkrqpvimq.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yvedp.cn/Article/details/gtejwwpuzw.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.gaohongyu789.top/Article/details/gtvmjveete.html

C#:   interface IShape { double Area(); }
来源：http://dali.gotoacloud.top/Article/details/gtczjddfan.html

[G10] 访问控制
来源：http://dali.jqgfzy.top/Article/details/gtdblodaxh.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.hywenlv.cn/Article/details/gtkboflprh.html

PHP:  public / protected / private
来源：http://dali.jianghu66.top/Article/details/gtkdhakrnx.html

JS:   #private 字段；其余公开
来源：http://dali.smart0.xyz/Article/details/gtkvlfdzae.html

TS:   public / protected / private
来源：http://dali.c1oappe.top/Article/details/gtbtceyhce.html

Java: public / protected / private / 默认包级
来源：http://dali.jinqigufen.top/Article/details/gtogqjnddp.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqhmznjpy.html

Ruby: public / protected / private
来源：http://dali.quarkkingdee.top/Article/details/gtkwpeirgm.html

C#:   public / protected / private / internal
来源：http://dali.ehwqpu.com/Article/details/gtezvxdibc.html

[G11] getter / setter
来源：http://dali.gotoacloud.top/Article/details/gtqohqdxrp.html

Py:   @property 与 @x.setter
来源：http://dali.daxiang520.top/Article/details/gttwgfwmgc.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yuanzhike.top/Article/details/gtdbkprvpt.html

JS:   get name() { return this._name; }
来源：http://dali.yuxming.cn/Article/details/gtafnrunmb.html

TS:   get name(): string { return this._name; }
来源：http://dali.jianghu66.top/Article/details/gtnwrlgopt.html

Java: public String getName() { return name; }
来源：http://dali.chenlongwang.top/Article/details/gtfyopefzm.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xuanzx.com/Article/details/gttkhpnfbj.html

Ruby: attr_accessor :name
来源：http://dali.pycfn.com/Article/details/gtfdsxpnlm.html

C#:   public string Name { get; set; }
来源：http://dali.jqgufenzy.top/Article/details/gtuqzxdrhj.html

[G12] 对象转字符串
来源：http://dali.jqgfzy.top/Article/details/gtclpmavcs.html

Py:   def __str__(self): return self.name
来源：http://dali.yuanzhike.top/Article/details/gtrydhrmak.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.smart0.xyz/Article/details/gtfxrmuctb.html

JS:   toString() { return this.name; }
来源：http://dali.ybcxt.top/Article/details/gtkdberfrv.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhengqikj.top/Article/details/gtyaouvszq.html

Java: @Override public String toString() { return name; }
来源：http://dali.yuxming.cn/Article/details/gtuqropcpn.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.gogol.net.cn/Article/details/gtsnaodomd.html

Ruby: def to_s; @name; end
来源：http://dali.ehwqpu.com/Article/details/gtpnxalmbs.html

C#:   public override string ToString() => Name;
来源：http://dali.meibo888.top/Article/details/gtxhivjkgv.html

[G13] 判断对象类型
来源：http://dali.daria6918.cn/Article/details/gtldmfsnpm.html

Py:   isinstance(u, User)
来源：http://dali.zhiwuduotai.top/Article/details/gtuxrtcssv.html

PHP:  $u instanceof User
来源：http://dali.chenjidiqi.icu/Article/details/gtxayrbuou.html

JS:   u instanceof User
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfggsmaza.html

TS:   u instanceof User
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtozrcplqn.html

Java: u instanceof User
来源：http://dali.yanxiufei.cn/Article/details/gthgyzgwog.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.pengpengdd.cyou/Article/details/gtnxdqtwgn.html

Ruby: u.is_a?(User)
来源：http://dali.jqgufenzy.top/Article/details/gtrdilsgpb.html

C#:   u is User
来源：http://dali.daria6918.cn/Article/details/gtdmqdzhpz.html

[G14] 数据类 / record
来源：http://dali.cashguo.top/Article/details/gtpvrltnbd.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.shanyushiyangtech.top/Article/details/gtoesretri.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.pycfn.com/Article/details/gtqeqjiypm.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.guannengcc.top/Article/details/gtrzeyerlc.html

TS:   type User = { name: string; age: number };
来源：http://dali.jyoumei.cn/Article/details/gtzjcoptwm.html

Java: record User(String name, int age) {}
来源：http://dali.zhoulong.xyz/Article/details/gtutdcmnwz.html

Go:   type User struct { Name string; Age int }
来源：http://dali.nwbrower.top/Article/details/gtylnbckzc.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.sysykeji.top/Article/details/gtdqfcbbuw.html

C#:   record User(string Name, int Age);
来源：http://dali.snrcjt.cn/Article/details/gtybecpxob.html

[G15] 枚举
来源：http://dali.haohaochexian.top/Article/details/gtubvnojqs.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.vqdsnc.cn/Article/details/gtzlvlzxst.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.nanxuanxn.top/Article/details/gtyjowksgw.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.daxiang520.top/Article/details/gtvwqqmwor.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hnqzz.top/Article/details/gtpwffgqko.html

Java: enum Color { RED, GREEN }
来源：http://dali.xinyue.icu/Article/details/gtlmxrbatp.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yj20258.top/Article/details/gtimfsoqlq.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhoulong.xyz/Article/details/gtbxjwovce.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jiagoushi.top/Article/details/gtxegiipbr.html

[G16] 对象转数组 / 字典
来源：http://dali.gzhubu.top/Article/details/gtwlnocvjk.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.gaohongyu789.top/Article/details/gtuzlzwhte.html

PHP:  get_object_vars($obj);
来源：http://dali.ybcxt.top/Article/details/gtvllrnnug.html

JS:   Object.entries(obj)
来源：http://dali.snrcjt.cn/Article/details/gtlrxklbet.html

TS:   Object.entries(obj)
来源：http://dali.havefunace.top/Article/details/gtgumalvic.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.cucudq.cn/Article/details/gtqkezbess.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.sxryk.cn/Article/details/gtqmfsaiqx.html

Ruby: obj.instance_variables
来源：http://dali.pycfn.com/Article/details/gtjsuzlmuz.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yj202588.top/Article/details/gtnkwggivg.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtgwgdksud.html

H. 异常与错误处理
来源：http://dali.xuetiantiany.cn/Article/details/gtobbyfvpv.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gthudenfhu.html

[H01] try / catch 基础
来源：http://dali.gzhubu.top/Article/details/gtnmouyqoq.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.guannengcc.top/Article/details/gtcgmdjedv.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yj202588.top/Article/details/gtcbdvcsco.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.316326.xyz/Article/details/gtmoynwhnm.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.nwbrower.top/Article/details/gtyzehojto.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.xinyue.icu/Article/details/gthnlsdlhr.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hfpthk.cn/Article/details/gtxymypxht.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.havefunace.top/Article/details/gtrlebnyca.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.9152youxi.cn/Article/details/gtztznmobh.html

[H02] finally / ensure 收尾
来源：http://dali.zycfv.cn/Article/details/gtqtkczbly.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.ivvv.top/Article/details/gtnqvdacea.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.quarkkingdee.top/Article/details/gtduhrfhcs.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ehwqpu.com/Article/details/gtebgirndw.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.meibo888.top/Article/details/gtkzwijmpe.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.andypj.xyz/Article/details/gtjfumxfes.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.c1oappe.top/Article/details/gtcjrvpwhu.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.chenlongwang.top/Article/details/gtbbheqtxm.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.hnxiangtu.top/Article/details/gttffpvotv.html

[H03] 主动抛出异常
来源：http://dali.xuanzx.com/Article/details/gtvmrerrzd.html

Py:   raise ValueError("错误信息")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnivjrlru.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jlsjyb.cn/Article/details/gtawxegasm.html

JS:   throw new Error("错误信息");
来源：http://dali.yonumen.top/Article/details/gtmjegnsdu.html

TS:   throw new Error("错误信息");
来源：http://dali.ybcxt.top/Article/details/gtngzzjytv.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.chenjidiqi.icu/Article/details/gtpryoduya.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jiagoushi.top/Article/details/gtetepfxuy.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.sysykeji.top/Article/details/gtwenuaemm.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.ybcxt.top/Article/details/gttyznmnrq.html

[H04] 自定义异常类型
来源：http://dali.xylfe.cn/Article/details/gtxzhmftec.html

Py:   class MyError(Exception): pass
来源：http://dali.smart0.xyz/Article/details/gtztfwnhth.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jiagoushi.top/Article/details/gtmjdvydjh.html

JS:   class MyError extends Error {}
来源：http://dali.zdqjudy.top/Article/details/gtnufsbxyy.html

TS:   class MyError extends Error {}
来源：http://dali.nwbrower.top/Article/details/gtdkoakdvg.html

Java: class MyException extends RuntimeException {}
来源：http://dali.wangdashe.top/Article/details/gtfcsoiiwd.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.havefunace.top/Article/details/gttnfypbhh.html

Ruby: class MyError < StandardError; end
来源：http://dali.jlsjyb.cn/Article/details/gtbyvwtvlr.html

C#:   class MyException : Exception {}
来源：http://dali.meibo888.top/Article/details/gtrnqvewwq.html

[H05] 捕获特定类型
来源：http://dali.daxiang520.top/Article/details/gteluncyox.html

Py:   except ValueError as e:
来源：http://dali.xylfe.cn/Article/details/gttgagknbs.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.9152youxi.cn/Article/details/gtuausglxi.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtxmvatrha.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.sweek.top/Article/details/gtgpqnjsrx.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.aibaodan.cn/Article/details/gtqlauarqh.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.feifeiyinyue.top/Article/details/gtycsgoitk.html

Ruby: rescue ArgumentError => e
来源：http://dali.yj20258888.top/Article/details/gtbjrtfref.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.sysykeji.top/Article/details/gtxpablvrp.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jqgufenzy.top/Article/details/gtwhdmnwve.html

Py:   value = d.get("k") or default
来源：http://dali.zhijiandao.cn/Article/details/gtmpgxxyrf.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yonumen.top/Article/details/gtnwcpjefs.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.ehwqpu.com/Article/details/gtglteljuz.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.nwbrower.top/Article/details/gtphngjpln.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.wangshuangyany.cn/Article/details/gtmujudzah.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.nwbrower.top/Article/details/gtxuehepms.html

Ruby: d&.dig(:a, :b)
来源：http://dali.sxryk.cn/Article/details/gtujytlsgi.html

C#:   obj?.A?.B ?? default
来源：http://dali.guowangkeji.top/Article/details/gtkxnuaace.html

[H07] 断言
来源：http://dali.hnxiangtu.top/Article/details/gtrvgngvnn.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jqgfzy.top/Article/details/gtopfenghv.html

PHP:  assert($x > 0);
来源：http://dali.aizwys.cn/Article/details/gtdvwbwagm.html

JS:   console.assert(x > 0);
来源：http://dali.hammf.cn/Article/details/gtbowrupsm.html


<!-- 参考信息 -->