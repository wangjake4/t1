代发 wailian999

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.meibo888.top/Article/details/gtmexcrovv.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.0kj1m.cn/Article/details/gtuvxzvvyr.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.chenlongwang.top/Article/details/gtmomlatho.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yanxiufei.cn/Article/details/gtwwqdignb.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.chenzaomai.com/Article/details/gtcaccryph.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.hfpthk.cn/Article/details/gtkrouhxwx.html

[F03] 写入文件（覆盖）
来源：http://dali.jlsjyb.cn/Article/details/gtrcywnixi.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jqgufenzy.top/Article/details/gtcpqwabaw.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.cdnleiting.top/Article/details/gtfhvxgbal.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hnxiangtu.top/Article/details/gtoocnitbc.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yuanzhike.top/Article/details/gttlawwcho.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.sysykeji.top/Article/details/gtqrmcntto.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.kuanghao11.cn/Article/details/gtwncjqiae.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.gzhubu.top/Article/details/gtubsljkgw.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.shzxlz.cn/Article/details/gtaddvtair.html

[F04] 追加写入文件
来源：http://dali.cqqwz.cn/Article/details/gtkuvujxbe.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.snrcjt.cn/Article/details/gtouxmgtad.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.cashguo.top/Article/details/gtpteiyysb.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yongpay.top/Article/details/gtivhhwgxc.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.birdmap.top/Article/details/gtqysvqvwh.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yongpay.top/Article/details/gtwqmnxthe.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.pengpengdd.cyou/Article/details/gtvthgifsx.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.cucudq.cn/Article/details/gtbavzbrgh.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.0kj1m.cn/Article/details/gtkwxmytie.html

[F05] 判断文件或目录是否存在
来源：http://dali.cheryme.top/Article/details/gtfiwzdccj.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.dashuyun.cn/Article/details/gtqgmdbhxl.html

PHP:  file_exists("a.txt");
来源：http://dali.redwolf501.top/Article/details/gtzpvvbwel.html

JS:   fs.existsSync("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gthowpyjnw.html

TS:   fs.existsSync("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtwkinhbto.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yuxming.cn/Article/details/gtflirewgc.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jinqigfzy.top/Article/details/gtkdxohmrn.html

Ruby: File.exist?("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtivtsuxjp.html

C#:   File.Exists("a.txt")
来源：http://dali.xziqi.cn/Article/details/gtmswyhjtf.html

[F06] 删除文件
来源：http://dali.nwbrower.top/Article/details/gttddaxtec.html

Py:   os.remove("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtctmxbnep.html

PHP:  unlink("a.txt");
来源：http://dali.yongpay.top/Article/details/gtrcutenbe.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.tanke756.top/Article/details/gtolimpybh.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtbjxkfwrb.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.pengpengdd.cyou/Article/details/gtstjxloeu.html

Go:   os.Remove("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbsndaiik.html

Ruby: File.delete("a.txt")
来源：http://dali.yj20258.top/Article/details/gtuqvynuup.html

C#:   File.Delete("a.txt");
来源：http://dali.shuidangran.top/Article/details/gtwtnaktdf.html

[F07] 创建目录（含多级）
来源：http://dali.quarkkingdee.top/Article/details/gtaihbneld.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.shuidangran.top/Article/details/gtkeklmraj.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.gaohongyu789.top/Article/details/gtsojsxigc.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.guowangkeji.top/Article/details/gtkilyhvdc.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cashguo.top/Article/details/gtzicoyhra.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.cucudq.cn/Article/details/gthiqmtgqu.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.nanxuanxn.top/Article/details/gtzdtinbci.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.316326.xyz/Article/details/gtvwxxuyhz.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhoulong.xyz/Article/details/gtpxwxgyhh.html

[F08] 遍历目录
来源：http://dali.yanxiufei.cn/Article/details/gtlhobkbmd.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhoulong.xyz/Article/details/gtbdncmtyg.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.daxiang520.top/Article/details/gtmtvonkvt.html

JS:   fs.readdirSync("dir")
来源：http://dali.hysaishi.cn/Article/details/gtpxwtdxnx.html

TS:   fs.readdirSync("dir")
来源：http://dali.feifeiyinyue.top/Article/details/gtwdyhebxl.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jianghu66.top/Article/details/gtbahsuvpi.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhongyouzk.top/Article/details/gttchhzeed.html

Ruby: Dir.children("dir")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtobhbvnvv.html

C#:   Directory.GetFiles("dir")
来源：http://dali.tianlin.xyz/Article/details/gttwdwwdbo.html

[F09] 获取文件大小
来源：http://dali.xuanzx.com/Article/details/gtcnikpyzd.html

Py:   os.path.getsize("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtmpswwtij.html

PHP:  filesize("a.txt");
来源：http://dali.ydzc1.top/Article/details/gtwswlmmnu.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yj202588.top/Article/details/gtziskwwxw.html

TS:   fs.statSync("a.txt").size
来源：http://dali.smart0.xyz/Article/details/gtufwzcfss.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yvedp.cn/Article/details/gtazqtwdda.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.iojbl.cn/Article/details/gtmbktakqo.html

Ruby: File.size("a.txt")
来源：http://dali.sweek.top/Article/details/gtytmuwmpq.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.aizwys.cn/Article/details/gtrhqlaqfw.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.chenzaomai.com/Article/details/gthamqbzoq.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.birdmap.top/Article/details/gttxdrnrli.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.shzxlz.cn/Article/details/gtucjivfug.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zycfv.cn/Article/details/gtchegxvhx.html

TS:   path.extname("a.txt")
来源：http://dali.bjfxy.top/Article/details/gttuwggvgn.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yj20258888.top/Article/details/gtafdghgsp.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.cucudq.cn/Article/details/gtimczlyox.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.tanke756.top/Article/details/gtcfsxrwsz.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zycfv.cn/Article/details/gtytqulvut.html

[F11] 复制与移动文件
来源：http://dali.kuanghao11.cn/Article/details/gtfilwmicz.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hywenlv.cn/Article/details/gtdzjijnap.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.9152youxi.cn/Article/details/gthxwsxyaa.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzczzirgv.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtfhmrfhop.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.nanxuanxn.top/Article/details/gtmsdlwpgx.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.wangshuangyany.cn/Article/details/gtwysqljdg.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zycfv.cn/Article/details/gtquhzwhyx.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jinghuilouyu.cn/Article/details/gtkqtverli.html

[F12] CSV 读写
来源：http://dali.hnqzz.top/Article/details/gtgzcoskxa.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.xinyue.icu/Article/details/gticmkmyou.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.chenlongwang.top/Article/details/gtlxiavano.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.aibaodan.cn/Article/details/gtpkljdyuu.html

TS:   // 同上
来源：http://dali.jinqigufen.top/Article/details/gttmnrecql.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.cashguo.top/Article/details/gtmwkcyhhu.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jlsjyb.cn/Article/details/gtgiiqixhd.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.aibaodan.cn/Article/details/gtvijjzkuk.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.9152youxi.cn/Article/details/gtnmqkwtpy.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtdkwiqmrf.html

G. 面向对象
来源：http://dali.guowangkeji.top/Article/details/gtdujaeoht.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtqmuqqwmj.html

[G01] 定义类
来源：http://dali.jqgufenzy.top/Article/details/gtndaodwig.html

Py:   class User: pass
来源：http://dali.hongshengwenyu.top/Article/details/gtusmjxknv.html

PHP:  class User {}
来源：http://dali.iojbl.cn/Article/details/gtyoxhydpr.html

JS:   class User {}
来源：http://dali.xylfe.cn/Article/details/gtdatkcxay.html

TS:   class User { name: string = ""; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaiqwvskw.html

Java: class User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiyqmbfbx.html

Go:   type User struct { Name string }
来源：http://dali.shangyingyoupin.top/Article/details/gtfimmnhwo.html

Ruby: class User; end
来源：http://dali.ppjwa.cn/Article/details/gtocrgyqpm.html

C#:   class User {}
来源：http://dali.shuidangran.top/Article/details/gtfyuhxrpw.html

[G02] 构造函数
来源：http://dali.aibaodan.cn/Article/details/gtjruguwgl.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.gotoacloud.top/Article/details/gtautvjykh.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jianghu66.top/Article/details/gtglbshaxt.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtdkayezig.html

TS:   constructor(public name: string) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtikckjqeo.html

Java: User(String name) { this.name = name; }
来源：http://dali.tian-w.cn/Article/details/gtmprhexjs.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.nanxinkj.top/Article/details/gtnnvzjpvu.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gttcxezalc.html

C#:   public User(string name) { Name = name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteuirlixn.html

[G03] 实例属性
来源：http://dali.aibaodan.cn/Article/details/gtmioyfzqc.html

Py:   self.name = "x"
来源：http://dali.nanxinkj.top/Article/details/gtncvinlhu.html

PHP:  public string $name = "x";
来源：http://dali.svipenyu.cn/Article/details/gtuwlwrhac.html

JS:   this.name = "x";
来源：http://dali.sysykeji.top/Article/details/gtcfggpcdj.html

TS:   name: string = "x";
来源：http://dali.andypj.xyz/Article/details/gtkbinuzyk.html

Java: private String name;
来源：http://dali.jinqigfzy.top/Article/details/gtnmrxvyxf.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hysaishi.cn/Article/details/gtgpungfjs.html

Ruby: @name = "x"
来源：http://dali.316326.xyz/Article/details/gtrykeyrkb.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.hfpthk.cn/Article/details/gtxiqtkcsl.html

[G04] 定义方法
来源：http://dali.aibaodan.cn/Article/details/gtljvkpjuy.html

Py:   def greet(self): return self.name
来源：http://dali.zhixingplan.top/Article/details/gtqnbedmfi.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkrvliqlz.html

JS:   greet() { return this.name; }
来源：http://dali.pycfn.com/Article/details/gtgkhcaflr.html

TS:   greet(): string { return this.name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtknkfrqiz.html

Java: String greet() { return name; }
来源：http://dali.dianchejie.cn/Article/details/gtzqahtebj.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.gzhubu.top/Article/details/gtzyhbcemz.html

Ruby: def greet; @name; end
来源：http://dali.dashuyun.cn/Article/details/gttrhqkmvz.html

C#:   public string Greet() => Name;
来源：http://dali.fzhhl.top/Article/details/gttxceauwr.html

[G05] 继承
来源：http://dali.0kj1m.cn/Article/details/gtzkokvcay.html

Py:   class Admin(User): pass
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkkazvmte.html

PHP:  class Admin extends User {}
来源：http://dali.havefunace.top/Article/details/gtwndihkhv.html

JS:   class Admin extends User {}
来源：http://dali.sysykeji.top/Article/details/gterjsgbqm.html

TS:   class Admin extends User {}
来源：http://dali.ydzc1.top/Article/details/gtzsdlzxgd.html

Java: class Admin extends User {}
来源：http://dali.gaohongyu789.top/Article/details/gtbsyuvsna.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.xinyue.icu/Article/details/gtixeclksv.html

Ruby: class Admin < User; end
来源：http://dali.jinghuilouyu.cn/Article/details/gtqvjshlze.html

C#:   class Admin : User {}
来源：http://dali.jiagoushi.top/Article/details/gtpyojnlzz.html

[G06] 重写方法
来源：http://dali.tian-w.cn/Article/details/gttdokzhiz.html

Py:   def greet(self): return "admin"
来源：http://dali.0kj1m.cn/Article/details/gtgypifgwe.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhixingplan.top/Article/details/gtnomeniud.html

JS:   greet() { return "admin"; }
来源：http://dali.aizwys.cn/Article/details/gtgdypqstq.html

TS:   greet(): string { return "admin"; }
来源：http://dali.pengpengdd.cyou/Article/details/gtidntrfgw.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.hnxiangtu.top/Article/details/gtqplnfwdd.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhixingplan.top/Article/details/gtlmwdvmis.html

Ruby: def greet; "admin"; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmgymggak.html

C#:   public override string Greet() => "admin";
来源：http://dali.nanxuanxn.top/Article/details/gtcuqfiawi.html

[G07] 调用父类方法
来源：http://dali.cqqwz.cn/Article/details/gtxrromkvy.html

Py:   super().greet()
来源：http://dali.haohaochexian.top/Article/details/gteimnadvd.html

PHP:  parent::greet();
来源：http://dali.chenlongwang.top/Article/details/gttyalvhop.html

JS:   super.greet();
来源：http://dali.shangyingyoupin.top/Article/details/gttwgdjbux.html

TS:   super.greet();
来源：http://dali.meibo888.top/Article/details/gtynbxwmlw.html

Java: super.greet();
来源：http://dali.ppjwa.cn/Article/details/gtljdqvrdl.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.dashuyun.cn/Article/details/gtegurctzq.html

Ruby: super
来源：http://dali.shangyingyoupin.top/Article/details/gtgtrhvgxk.html

C#:   base.Greet();
来源：http://dali.sxryk.cn/Article/details/gtyezkhepv.html

[G08] 静态方法与属性
来源：http://dali.meibo888.top/Article/details/gtzitznxqg.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.chenzaomai.com/Article/details/gttyawsnol.html

PHP:  public static function f() {}
来源：http://dali.pengpengdd.cyou/Article/details/gtzvqsnpoj.html

JS:   static f() {}
来源：http://dali.mhx1999.top/Article/details/gtxdkusksf.html

TS:   static f(): void {}
来源：http://dali.zhongyouzk.top/Article/details/gtydtebtap.html

Java: static void f() {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtcclyyasi.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.sweek.top/Article/details/gtdomcguna.html

Ruby: def self.f; end
来源：http://dali.xinyue.icu/Article/details/gtlvgnldot.html

C#:   public static void F() {}
来源：http://dali.cucudq.cn/Article/details/gtozglcdlw.html

[G09] 接口 / 抽象类
来源：http://dali.zhoulong.xyz/Article/details/gtbxyfgcmo.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.pycfn.com/Article/details/gtxhbtvpkn.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.nanxinkj.top/Article/details/gtrapgfnkw.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhengqikj.top/Article/details/gtqpnodcrs.html

TS:   interface Shape { area(): number; }
来源：http://dali.daxiang520.top/Article/details/gthkgdnvlf.html

Java: interface Shape { double area(); }
来源：http://dali.yuxming.cn/Article/details/gtuacjvfsd.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jinghuilouyu.cn/Article/details/gtthxlkfdv.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xuanzx.com/Article/details/gtynjuempl.html

C#:   interface IShape { double Area(); }
来源：http://dali.jinqigufen.top/Article/details/gttluupxct.html

[G10] 访问控制
来源：http://dali.c1oappe.top/Article/details/gtvwlyjxru.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gtarfrcquo.html

PHP:  public / protected / private
来源：http://dali.svipenyu.cn/Article/details/gtxdcjljdw.html

JS:   #private 字段；其余公开
来源：http://dali.chenlongwang.top/Article/details/gtdrlbfulg.html

TS:   public / protected / private
来源：http://dali.meibo888.top/Article/details/gtwheuihhm.html

Java: public / protected / private / 默认包级
来源：http://dali.yj20258888.top/Article/details/gtnhlxzobm.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.pycfn.com/Article/details/gtbrjoknto.html

Ruby: public / protected / private
来源：http://dali.jiagoushi.top/Article/details/gtkgempctt.html

C#:   public / protected / private / internal
来源：http://dali.svipenyu.cn/Article/details/gtsmfvfvpr.html

[G11] getter / setter
来源：http://dali.yj20258888.top/Article/details/gtrnndhuth.html

Py:   @property 与 @x.setter
来源：http://dali.yangfankeji.com/Article/details/gtbfvhrztw.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yanxiufei.cn/Article/details/gtpmvzvbhy.html

JS:   get name() { return this._name; }
来源：http://dali.fengsongda.top/Article/details/gtdcqswtdy.html

TS:   get name(): string { return this._name; }
来源：http://dali.yanxiufei.cn/Article/details/gteztverry.html

Java: public String getName() { return name; }
来源：http://dali.yanxiufei.cn/Article/details/gtprgafvkc.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhaomingkeji.xyz/Article/details/gttpnkfwiu.html

Ruby: attr_accessor :name
来源：http://dali.hywenlv.cn/Article/details/gtgxomjvxm.html

C#:   public string Name { get; set; }
来源：http://dali.ehwqpu.com/Article/details/gtkwnvqswk.html

[G12] 对象转字符串
来源：http://dali.iojbl.cn/Article/details/gtdujjxgno.html

Py:   def __str__(self): return self.name
来源：http://dali.zhongyouzk.top/Article/details/gtwfhwpyuy.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.nanxuanxn.top/Article/details/gttyagkrrw.html

JS:   toString() { return this.name; }
来源：http://dali.dianchejie.cn/Article/details/gtvgxnwwdq.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhixingplan.top/Article/details/gtlvljuhjc.html

Java: @Override public String toString() { return name; }
来源：http://dali.ivvv.top/Article/details/gtqwkecrto.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hnxiangtu.top/Article/details/gtknelaiwr.html

Ruby: def to_s; @name; end
来源：http://dali.dianchejie.cn/Article/details/gtxjktgvxz.html

C#:   public override string ToString() => Name;
来源：http://dali.xinyue.icu/Article/details/gtpcreshdy.html

[G13] 判断对象类型
来源：http://dali.sweek.top/Article/details/gtcktymvmk.html

Py:   isinstance(u, User)
来源：http://dali.zycfv.cn/Article/details/gtkbtymzyz.html

PHP:  $u instanceof User
来源：http://dali.jlsjyb.cn/Article/details/gtanupobnm.html

JS:   u instanceof User
来源：http://dali.redwolf501.top/Article/details/gtypzbvdbc.html

TS:   u instanceof User
来源：http://dali.pengpengdd.cyou/Article/details/gtauwsaayk.html

Java: u instanceof User
来源：http://dali.zhoulong.xyz/Article/details/gtgskilpnd.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.nanxinkj.top/Article/details/gtdjihmzgw.html

Ruby: u.is_a?(User)
来源：http://dali.9152youxi.cn/Article/details/gtexwsflor.html

C#:   u is User
来源：http://dali.nanxinkj.top/Article/details/gtwdhtrzaf.html

[G14] 数据类 / record
来源：http://dali.zhoulong.xyz/Article/details/gtonywqqzg.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yuxming.cn/Article/details/gtdfhneyqx.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.fzhhl.top/Article/details/gtcvugmsxw.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jyoumei.cn/Article/details/gthaaziqlc.html

TS:   type User = { name: string; age: number };
来源：http://dali.yuanzhike.top/Article/details/gtjushsqnt.html

Java: record User(String name, int age) {}
来源：http://dali.dianchejie.cn/Article/details/gtrrqauxbw.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yj202588.top/Article/details/gtghoreeir.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.wangshuangyany.cn/Article/details/gtbdtaszdk.html

C#:   record User(string Name, int Age);
来源：http://dali.aizwys.cn/Article/details/gthejvnwlh.html

[G15] 枚举
来源：http://dali.tian-w.cn/Article/details/gtyalvovuh.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.cashguo.top/Article/details/gtkhgacfdz.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.redwolf501.top/Article/details/gtxqkjvwpf.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.nwbrower.top/Article/details/gtfpafdiyl.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.feifeiyinyue.top/Article/details/gtlemltuqu.html

Java: enum Color { RED, GREEN }
来源：http://dali.yongpay.top/Article/details/gtdhrklixe.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.cheryme.top/Article/details/gtjsvsulww.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zdqjudy.top/Article/details/gtvlytrcpr.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sxryk.cn/Article/details/gtixsnjoog.html

[G16] 对象转数组 / 字典
来源：http://dali.hnqzz.top/Article/details/gtnqjscxdp.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.chenlongwang.top/Article/details/gtbiowqziw.html

PHP:  get_object_vars($obj);
来源：http://dali.xinyue.icu/Article/details/gtotyfkoqx.html

JS:   Object.entries(obj)
来源：http://dali.sufxvd.cn/Article/details/gttgjhygut.html

TS:   Object.entries(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtuurzizup.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.snrcjt.cn/Article/details/gtkojyjgzh.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.316326.xyz/Article/details/gtvsegzuoo.html

Ruby: obj.instance_variables
来源：http://dali.ywan-chungtsiang.top/Article/details/gtonxoyvzj.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hfpthk.cn/Article/details/gturddaflt.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtswwcxhwa.html

H. 异常与错误处理
来源：http://dali.quarkkingdee.top/Article/details/gtoytkrnup.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtyozmvcxp.html

[H01] try / catch 基础
来源：http://dali.jyoumei.cn/Article/details/gtotprxdkp.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.wangdashe.top/Article/details/gtewdogidb.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtckvvpggi.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hnxiangtu.top/Article/details/gtgptsbqpd.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.chenjidiqi.icu/Article/details/gttngzbunl.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.ybcxt.top/Article/details/gtaymlzorl.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.shanyushiyangkeji.top/Article/details/gtntmnvenw.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.sxryk.cn/Article/details/gtmsstuyeh.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.wangdashe.top/Article/details/gtzzcirwqc.html

[H02] finally / ensure 收尾
来源：http://dali.dashuyun.cn/Article/details/gtuxuarlvf.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hysaishi.cn/Article/details/gtwockimtd.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.gaohongyu789.top/Article/details/gtbpsnjhpo.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.xinyue.icu/Article/details/gtyviqpowk.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmbwsrlym.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhoulong.xyz/Article/details/gthvlqnqpb.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.daxiang520.top/Article/details/gtbkohimob.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.andypj.xyz/Article/details/gtldecwxnp.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.fengsongda.top/Article/details/gtgyogwusg.html

[H03] 主动抛出异常
来源：http://dali.chenzaomai.com/Article/details/gtvckhqmuj.html

Py:   raise ValueError("错误信息")
来源：http://dali.jinghuilouyu.cn/Article/details/gtrifmfkne.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.cashguo.top/Article/details/gtygzsjfnl.html

JS:   throw new Error("错误信息");
来源：http://dali.gotoacloud.top/Article/details/gtqcwcdzpw.html

TS:   throw new Error("错误信息");
来源：http://dali.redwolf501.top/Article/details/gtmbitamzu.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.mhx1999.top/Article/details/gtrzzggkwr.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.mhx1999.top/Article/details/gtbwphmbix.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhengqikj.top/Article/details/gtivesijgl.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.sufxvd.cn/Article/details/gtnddjgjjc.html

[H04] 自定义异常类型
来源：http://dali.jianghu66.top/Article/details/gtzgwiwlfa.html

Py:   class MyError(Exception): pass
来源：http://dali.jinghuilouyu.cn/Article/details/gtpofizyaz.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.ehwqpu.com/Article/details/gtvoqoxzrm.html

JS:   class MyError extends Error {}
来源：http://dali.yuxming.cn/Article/details/gteulnawpy.html

TS:   class MyError extends Error {}
来源：http://dali.yuxming.cn/Article/details/gtpruabbfv.html

Java: class MyException extends RuntimeException {}
来源：http://dali.vqdsnc.cn/Article/details/gtdepqissa.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yj20258.top/Article/details/gtnjrhltcw.html

Ruby: class MyError < StandardError; end
来源：http://dali.hongshengwenyu.top/Article/details/gtltarydjw.html

C#:   class MyException : Exception {}
来源：http://dali.meibo888.top/Article/details/gtbpxekkqp.html

[H05] 捕获特定类型
来源：http://dali.dianchejie.cn/Article/details/gtifpnmffu.html

Py:   except ValueError as e:
来源：http://dali.daria6918.cn/Article/details/gtahkjvmug.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.hongshengwenyu.top/Article/details/gtpiyrganl.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.sweek.top/Article/details/gtxjdxauou.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.smart0.xyz/Article/details/gtsyujsvns.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yangfankeji.com/Article/details/gtslflfgma.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jiagoushi.top/Article/details/gtdogneoxa.html

Ruby: rescue ArgumentError => e
来源：http://dali.aizwys.cn/Article/details/gtpenbgdwi.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtksqbipnm.html

[H06] 可选值 / 空值安全访问
来源：http://dali.pengpengdd.cyou/Article/details/gtcxodghhq.html

Py:   value = d.get("k") or default
来源：http://dali.ivvv.top/Article/details/gttwssuczq.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yj20258888.top/Article/details/gtnzbhcvui.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jianghu66.top/Article/details/gtiegmocpj.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zdqjudy.top/Article/details/gtpdufbgno.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yuxming.cn/Article/details/gtzgazppzj.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yuanzhike.top/Article/details/gtvzgbcruq.html

Ruby: d&.dig(:a, :b)
来源：http://dali.gzhubu.top/Article/details/gtwymawzju.html

C#:   obj?.A?.B ?? default
来源：http://dali.quarkkingdee.top/Article/details/gtkkskoats.html


<!-- 参考信息 -->