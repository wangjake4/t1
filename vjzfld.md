代发 wailian999

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.cashguo.top/Article/details/gtvxuamxct.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.dianchejie.cn/Article/details/gtqyamnavk.html

[F03] 写入文件（覆盖）
来源：http://dali.zdqjudy.top/Article/details/gtrccuygjo.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhongyouzk.top/Article/details/gtzoahhhqx.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.fzhhl.top/Article/details/gtlbcjppei.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.nanxuanxn.top/Article/details/gtugcgqpsk.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hnqzz.top/Article/details/gtsmvvclip.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.gaohongyu789.top/Article/details/gthdmnghqb.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gtqrbavuvo.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.cucudq.cn/Article/details/gtqsjwtvof.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.birdmap.top/Article/details/gtjgpfznlg.html

[F04] 追加写入文件
来源：http://dali.ybcxt.top/Article/details/gtuznvyhnp.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yuanzhike.top/Article/details/gttxffwwvo.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.haohaochexian.top/Article/details/gtzvnkhkla.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.nanxuanxn.top/Article/details/gtpyfqgajx.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.svipenyu.cn/Article/details/gtgsljpmaf.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.shzxlz.cn/Article/details/gtzjmiduxo.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.pengpengdd.cyou/Article/details/gtnmvdxrwc.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yanxiufei.cn/Article/details/gtqzktxwlm.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.ydzc1.top/Article/details/gtlnljfxap.html

[F05] 判断文件或目录是否存在
来源：http://dali.gaohongyu789.top/Article/details/gtxfdhpevy.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.cheryme.top/Article/details/gtwfquqfvv.html

PHP:  file_exists("a.txt");
来源：http://dali.cqqwz.cn/Article/details/gtynwzqpij.html

JS:   fs.existsSync("a.txt")
来源：http://dali.shuidangran.top/Article/details/gtawkcaehx.html

TS:   fs.existsSync("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtnfobamir.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.redwolf501.top/Article/details/gtvrmjoqdu.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.9152youxi.cn/Article/details/gtfzcfzfye.html

Ruby: File.exist?("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtnaalvmcf.html

C#:   File.Exists("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtquftztmx.html

[F06] 删除文件
来源：http://dali.kuanghao11.cn/Article/details/gtizsyknqw.html

Py:   os.remove("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaniubfhu.html

PHP:  unlink("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtdgsirfyw.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gthuuhiyvn.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtnxyvlhge.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.gzhubu.top/Article/details/gtkxfsoxbp.html

Go:   os.Remove("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtdmczjzmf.html

Ruby: File.delete("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtalyktuag.html

C#:   File.Delete("a.txt");
来源：http://dali.yongpay.top/Article/details/gtabgmtefo.html

[F07] 创建目录（含多级）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlnqrjdef.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gtivuecfij.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.redwolf501.top/Article/details/gtgeekjakz.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hysaishi.cn/Article/details/gtfzimybjx.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sysykeji.top/Article/details/gtajynuuaz.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jianghu66.top/Article/details/gtartpwpjk.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.cashguo.top/Article/details/gtuwwsggzg.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhijiandao.cn/Article/details/gtvvjbiekw.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.pengpengdd.cyou/Article/details/gtuvkdztaf.html

[F08] 遍历目录
来源：http://dali.nwbrower.top/Article/details/gtbhsfhoyn.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.hfpthk.cn/Article/details/gtjijmgaje.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.sxryk.cn/Article/details/gtiwnydixf.html

JS:   fs.readdirSync("dir")
来源：http://dali.ybcxt.top/Article/details/gtqwddvrhb.html

TS:   fs.readdirSync("dir")
来源：http://dali.sufxvd.cn/Article/details/gtdgnvpmsl.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.daria6918.cn/Article/details/gtustwxilk.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jyoumei.cn/Article/details/gtqyigcqec.html

Ruby: Dir.children("dir")
来源：http://dali.jiagoushi.top/Article/details/gtlzjlyjzy.html

C#:   Directory.GetFiles("dir")
来源：http://dali.gogol.net.cn/Article/details/gtftcypemv.html

[F09] 获取文件大小
来源：http://dali.nwbrower.top/Article/details/gtoxoxcpwl.html

Py:   os.path.getsize("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtswndgfpw.html

PHP:  filesize("a.txt");
来源：http://dali.xinyue.icu/Article/details/gtmbfouxmt.html

JS:   fs.statSync("a.txt").size
来源：http://dali.xuetiantiany.cn/Article/details/gtnnzpkzrs.html

TS:   fs.statSync("a.txt").size
来源：http://dali.hfpthk.cn/Article/details/gtndjdrfhu.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.sweek.top/Article/details/gtyloefdsv.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yangfankeji.com/Article/details/gtpuiliogm.html

Ruby: File.size("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtdgifszcs.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.nwbrower.top/Article/details/gtqvhbhiis.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.haohaochexian.top/Article/details/gtasofynti.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.xylfe.cn/Article/details/gtystlrmyn.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gtxlgwuzql.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtxbtjlver.html

TS:   path.extname("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtsqixsccp.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hnxiangtu.top/Article/details/gtxwhbjwzb.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yj20258888.top/Article/details/gtsmdydjvi.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtptojmpqb.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.guannengcc.top/Article/details/gtbgwwktvd.html

[F11] 复制与移动文件
来源：http://dali.hongshengwenyu.top/Article/details/gtecabtojg.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtwyfoixrj.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gtioycmhel.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyxpgomkl.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.chenzaomai.com/Article/details/gtwrtfwzdl.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.ivvv.top/Article/details/gtmpczfffi.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yangfankeji.com/Article/details/gtfeaimoxa.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.9152youxi.cn/Article/details/gtnvsgbpgm.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.hongshengwenyu.top/Article/details/gtywzpjbae.html

[F12] CSV 读写
来源：http://dali.gzhubu.top/Article/details/gthbdxajlk.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.wangdashe.top/Article/details/gtdidqkgfk.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jinqigfzy.top/Article/details/gtcnemmyai.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jinqigufen.top/Article/details/gtismlqvsp.html

TS:   // 同上
来源：http://dali.jianghu66.top/Article/details/gtfqdlnirn.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.quarkkingdee.top/Article/details/gtsriihbry.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.shuidangran.top/Article/details/gtcseovcws.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.tian-w.cn/Article/details/gthqvsotpw.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hnqzz.top/Article/details/gtdhztcdfd.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtmwazmvip.html

G. 面向对象
来源：http://dali.xziqi.cn/Article/details/gtemxxfnuu.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtzmifvbod.html

[G01] 定义类
来源：http://dali.yuanzhike.top/Article/details/gtssfgggqz.html

Py:   class User: pass
来源：http://dali.yongpay.top/Article/details/gtdcbnimgi.html

PHP:  class User {}
来源：http://dali.hammf.cn/Article/details/gtrglasmal.html

JS:   class User {}
来源：http://dali.yueranfly.top/Article/details/gtaxjmgqhc.html

TS:   class User { name: string = ""; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdcbmzvnj.html

Java: class User {}
来源：http://dali.nanxinkj.top/Article/details/gtsmjxtdrs.html

Go:   type User struct { Name string }
来源：http://dali.xziqi.cn/Article/details/gtbswiudbm.html

Ruby: class User; end
来源：http://dali.havefunace.top/Article/details/gtppwuvdxq.html

C#:   class User {}
来源：http://dali.hywenlv.cn/Article/details/gtmadumfgl.html

[G02] 构造函数
来源：http://dali.zhengqikj.top/Article/details/gtcoxawfaf.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.fengsongda.top/Article/details/gtmhfqmhrw.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.daxiang520.top/Article/details/gtfikvdtpe.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhoulong.xyz/Article/details/gtoeqvmocx.html

TS:   constructor(public name: string) {}
来源：http://dali.cqqwz.cn/Article/details/gtnlctkxks.html

Java: User(String name) { this.name = name; }
来源：http://dali.svipenyu.cn/Article/details/gtqppcnarg.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.feifeiyinyue.top/Article/details/gthnyowwmy.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.sufxvd.cn/Article/details/gtmfyfbarj.html

C#:   public User(string name) { Name = name; }
来源：http://dali.snrcjt.cn/Article/details/gtnmlvtkwr.html

[G03] 实例属性
来源：http://dali.nanxuanxn.top/Article/details/gtbnmpkjhg.html

Py:   self.name = "x"
来源：http://dali.yvedp.cn/Article/details/gtypqdtkec.html

PHP:  public string $name = "x";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdrgniydf.html

JS:   this.name = "x";
来源：http://dali.shanyushiyangtech.top/Article/details/gtbvzhyeib.html

TS:   name: string = "x";
来源：http://dali.zhixingplan.top/Article/details/gtrcfzgevw.html

Java: private String name;
来源：http://dali.0kj1m.cn/Article/details/gtnaqfyfdu.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.gzhubu.top/Article/details/gtlkpabnvu.html

Ruby: @name = "x"
来源：http://dali.hammf.cn/Article/details/gtogbjuqne.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.birdmap.top/Article/details/gtjasdmann.html

[G04] 定义方法
来源：http://dali.yueranfly.top/Article/details/gtyhmnolgi.html

Py:   def greet(self): return self.name
来源：http://dali.hnqzz.top/Article/details/gtddqtdias.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.0kj1m.cn/Article/details/gtztosgcuf.html

JS:   greet() { return this.name; }
来源：http://dali.ybcxt.top/Article/details/gtckbdtsod.html

TS:   greet(): string { return this.name; }
来源：http://dali.snrcjt.cn/Article/details/gteodrzkgg.html

Java: String greet() { return name; }
来源：http://dali.jqgufenzy.top/Article/details/gtjxbxgtyo.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yonumen.top/Article/details/gtsfmnhyuh.html

Ruby: def greet; @name; end
来源：http://dali.hongshengwenyu.top/Article/details/gtylsosgjb.html

C#:   public string Greet() => Name;
来源：http://dali.fengsongda.top/Article/details/gthkjuzxwx.html

[G05] 继承
来源：http://dali.shzxlz.cn/Article/details/gtlvxszkee.html

Py:   class Admin(User): pass
来源：http://dali.redwolf501.top/Article/details/gtkbpnnigy.html

PHP:  class Admin extends User {}
来源：http://dali.xinyue.icu/Article/details/gtrkaodsrq.html

JS:   class Admin extends User {}
来源：http://dali.jqgfzy.top/Article/details/gtpxhxzttq.html

TS:   class Admin extends User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtjuhqrtko.html

Java: class Admin extends User {}
来源：http://dali.iojbl.cn/Article/details/gtlarvaapa.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ppjwa.cn/Article/details/gtchtyfwrt.html

Ruby: class Admin < User; end
来源：http://dali.daxiang520.top/Article/details/gtliezhqza.html

C#:   class Admin : User {}
来源：http://dali.cdnleiting.top/Article/details/gthpvffmbg.html

[G06] 重写方法
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcdyshhqc.html

Py:   def greet(self): return "admin"
来源：http://dali.jqgfzy.top/Article/details/gtsiyrteig.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.vqdsnc.cn/Article/details/gttfhmjhwj.html

JS:   greet() { return "admin"; }
来源：http://dali.xinyue.icu/Article/details/gtcnnyvmmq.html

TS:   greet(): string { return "admin"; }
来源：http://dali.nwbrower.top/Article/details/gtizftlqvg.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jianghu66.top/Article/details/gtxvdxfzjz.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.feifeiyinyue.top/Article/details/gteaipxgim.html

Ruby: def greet; "admin"; end
来源：http://dali.zycfv.cn/Article/details/gtlifihsqo.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhixingplan.top/Article/details/gtmldyczro.html

[G07] 调用父类方法
来源：http://dali.xuetiantiany.cn/Article/details/gtvdcjdgdl.html

Py:   super().greet()
来源：http://dali.cheryme.top/Article/details/gttmscevwm.html

PHP:  parent::greet();
来源：http://dali.jinqigfzy.top/Article/details/gtkjbhmvco.html

JS:   super.greet();
来源：http://dali.gogol.net.cn/Article/details/gtzmtaojdb.html

TS:   super.greet();
来源：http://dali.fzhhl.top/Article/details/gttahttewz.html

Java: super.greet();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqwgmirty.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yuxming.cn/Article/details/gtgpeubktc.html

Ruby: super
来源：http://dali.dashuyun.cn/Article/details/gtyplwgwsr.html

C#:   base.Greet();
来源：http://dali.aizwys.cn/Article/details/gtwdwhpege.html

[G08] 静态方法与属性
来源：http://dali.jyoumei.cn/Article/details/gtnfqwpskg.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.dianchejie.cn/Article/details/gtoyaivsxt.html

PHP:  public static function f() {}
来源：http://dali.zdqjudy.top/Article/details/gtuvqdsjqq.html

JS:   static f() {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlswuwyge.html

TS:   static f(): void {}
来源：http://dali.hongshengwenyu.top/Article/details/gtwgllllhy.html

Java: static void f() {}
来源：http://dali.tian-w.cn/Article/details/gtkniwthke.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.tian-w.cn/Article/details/gtihrblrot.html

Ruby: def self.f; end
来源：http://dali.chenzaomai.com/Article/details/gttjmwucna.html

C#:   public static void F() {}
来源：http://dali.aizwys.cn/Article/details/gttaziomnz.html

[G09] 接口 / 抽象类
来源：http://dali.sxryk.cn/Article/details/gtlgldkkmz.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.ydzc1.top/Article/details/gtaxsonpwh.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.shuidangran.top/Article/details/gtzirltgtq.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.aizwys.cn/Article/details/gtueteajli.html

TS:   interface Shape { area(): number; }
来源：http://dali.chenlongwang.top/Article/details/gttvcnbcrh.html

Java: interface Shape { double area(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtofopdupp.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.tian-w.cn/Article/details/gtqmofsxto.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.chenlongwang.top/Article/details/gtappekngk.html

C#:   interface IShape { double Area(); }
来源：http://dali.yanxiufei.cn/Article/details/gtuxqiqozu.html

[G10] 访问控制
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmtudvtzx.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.dashuyun.cn/Article/details/gtjavkhrmz.html

PHP:  public / protected / private
来源：http://dali.zhixingplan.top/Article/details/gtufwrbzaa.html

JS:   #private 字段；其余公开
来源：http://dali.chenjidiqi.icu/Article/details/gtsobvjjoe.html

TS:   public / protected / private
来源：http://dali.xuetiantiany.cn/Article/details/gtoyjtoysx.html

Java: public / protected / private / 默认包级
来源：http://dali.yvedp.cn/Article/details/gtgueszrpr.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xylfe.cn/Article/details/gtenebdhat.html

Ruby: public / protected / private
来源：http://dali.cdnleiting.top/Article/details/gtnkjcehjb.html

C#:   public / protected / private / internal
来源：http://dali.shangyingyoupin.top/Article/details/gtletwqiva.html

[G11] getter / setter
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlvncdcws.html

Py:   @property 与 @x.setter
来源：http://dali.pycfn.com/Article/details/gtwwcdbmwn.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.9152youxi.cn/Article/details/gtfxanvloi.html

JS:   get name() { return this._name; }
来源：http://dali.tanke756.top/Article/details/gtoqtsryzr.html

TS:   get name(): string { return this._name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtnbjhkiyc.html

Java: public String getName() { return name; }
来源：http://dali.sweek.top/Article/details/gteymczcjx.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.chenzaomai.com/Article/details/gtkidpqrjn.html

Ruby: attr_accessor :name
来源：http://dali.sufxvd.cn/Article/details/gthhoppqdj.html

C#:   public string Name { get; set; }
来源：http://dali.dashuyun.cn/Article/details/gtyfomkjah.html

[G12] 对象转字符串
来源：http://dali.shuidangran.top/Article/details/gtzirouyab.html

Py:   def __str__(self): return self.name
来源：http://dali.pengpengdd.cyou/Article/details/gtldclxkao.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtalxikdhx.html

JS:   toString() { return this.name; }
来源：http://dali.ehwqpu.com/Article/details/gteqqxznac.html

TS:   toString(): string { return this.name; }
来源：http://dali.cashguo.top/Article/details/gttfptxnwz.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsekgvhux.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhoulong.xyz/Article/details/gtazqmhsix.html

Ruby: def to_s; @name; end
来源：http://dali.shuidangran.top/Article/details/gtobbnftms.html

C#:   public override string ToString() => Name;
来源：http://dali.316326.xyz/Article/details/gtgjexmezx.html

[G13] 判断对象类型
来源：http://dali.ehwqpu.com/Article/details/gtbkqhrdwc.html

Py:   isinstance(u, User)
来源：http://dali.jinqigfzy.top/Article/details/gtrlsapesw.html

PHP:  $u instanceof User
来源：http://dali.ybcxt.top/Article/details/gtywimmaod.html

JS:   u instanceof User
来源：http://dali.sxryk.cn/Article/details/gtkrcqrsmd.html

TS:   u instanceof User
来源：http://dali.yangfankeji.com/Article/details/gtkmigvsxo.html

Java: u instanceof User
来源：http://dali.gaohongyu789.top/Article/details/gtizxasbtd.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.cheryme.top/Article/details/gturqaniik.html

Ruby: u.is_a?(User)
来源：http://dali.jiagoushi.top/Article/details/gtdwfujmyo.html

C#:   u is User
来源：http://dali.c1oappe.top/Article/details/gteydceglm.html

[G14] 数据类 / record
来源：http://dali.jianghu66.top/Article/details/gtlxfetudp.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.xziqi.cn/Article/details/gtfkhwaxyx.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.quarkkingdee.top/Article/details/gtkdtmstgb.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yonumen.top/Article/details/gtdbnhekqz.html

TS:   type User = { name: string; age: number };
来源：http://dali.jinqigfzy.top/Article/details/gtbjenpgww.html

Java: record User(String name, int age) {}
来源：http://dali.jqgufenzy.top/Article/details/gtzvigishc.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jinqigufen.top/Article/details/gtbajkodjx.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.ppjwa.cn/Article/details/gtzjcgjffo.html

C#:   record User(string Name, int Age);
来源：http://dali.pycfn.com/Article/details/gtctfnddrc.html

[G15] 枚举
来源：http://dali.ivvv.top/Article/details/gtyyespnjy.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.fzhhl.top/Article/details/gtphmygjks.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.chenzaomai.com/Article/details/gthqogoktr.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jianghu66.top/Article/details/gtxtsnehog.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.chenlongwang.top/Article/details/gtynzcgmev.html

Java: enum Color { RED, GREEN }
来源：http://dali.sxryk.cn/Article/details/gtnnlleyex.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtidadgjqp.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ydzc1.top/Article/details/gtoqrkpqpe.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sweek.top/Article/details/gtfnnyptog.html

[G16] 对象转数组 / 字典
来源：http://dali.hywenlv.cn/Article/details/gteynpfyme.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.aizwys.cn/Article/details/gthtysonzo.html

PHP:  get_object_vars($obj);
来源：http://dali.sweek.top/Article/details/gtsjvtdkex.html

JS:   Object.entries(obj)
来源：http://dali.jiagoushi.top/Article/details/gtlakhshyp.html

TS:   Object.entries(obj)
来源：http://dali.nanxinkj.top/Article/details/gtccfrjpye.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yj20258888.top/Article/details/gtrzegackg.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.nanxinkj.top/Article/details/gtfzgzjqyj.html

Ruby: obj.instance_variables
来源：http://dali.aibaodan.cn/Article/details/gtfbrfditc.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.andypj.xyz/Article/details/gtwtqtcnet.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtfnspvcvl.html

H. 异常与错误处理
来源：http://dali.daxiang520.top/Article/details/gtxnddprtr.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtpyvljuvj.html

[H01] try / catch 基础
来源：http://dali.xinyue.icu/Article/details/gtdrhcqjtx.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.cheryme.top/Article/details/gtfgltqfju.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jqgufenzy.top/Article/details/gticdgpmnm.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jqgfzy.top/Article/details/gtkckhpqit.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.316326.xyz/Article/details/gtfymdlben.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hfpthk.cn/Article/details/gtjvuumjsx.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.xziqi.cn/Article/details/gtbxtvdbwu.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yj20258888.top/Article/details/gttzjngwhm.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.shuidangran.top/Article/details/gtcaaxadjv.html

[H02] finally / ensure 收尾
来源：http://dali.shzxlz.cn/Article/details/gtcdvjdbqe.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.ehwqpu.com/Article/details/gtmubocyyo.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.ehwqpu.com/Article/details/gttoqryaes.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.wangdashe.top/Article/details/gtduitbout.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtngedfhcp.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.shzxlz.cn/Article/details/gtlugefjpd.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.sysykeji.top/Article/details/gtnzoggubg.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.xinyue.icu/Article/details/gtplhjxepv.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.birdmap.top/Article/details/gtjgcsmxof.html

[H03] 主动抛出异常
来源：http://dali.xziqi.cn/Article/details/gttefadkfx.html

Py:   raise ValueError("错误信息")
来源：http://dali.tanke756.top/Article/details/gtstxsanuw.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jinqigfzy.top/Article/details/gtvqenclxh.html

JS:   throw new Error("错误信息");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlvpgozlj.html

TS:   throw new Error("错误信息");
来源：http://dali.xylfe.cn/Article/details/gtmvhtkhcu.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.chenlongwang.top/Article/details/gtfspmzldq.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hnqzz.top/Article/details/gtsyuheicg.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.mhx1999.top/Article/details/gtwiievsrk.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jianghu66.top/Article/details/gttfxremsl.html

[H04] 自定义异常类型
来源：http://dali.jlsjyb.cn/Article/details/gteijecgwa.html

Py:   class MyError(Exception): pass
来源：http://dali.meibo888.top/Article/details/gtudpecudm.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.shangyingyoupin.top/Article/details/gtvbaxyelt.html

JS:   class MyError extends Error {}
来源：http://dali.zycfv.cn/Article/details/gtzrruixiv.html

TS:   class MyError extends Error {}
来源：http://dali.birdmap.top/Article/details/gtigazgncu.html

Java: class MyException extends RuntimeException {}
来源：http://dali.quarkkingdee.top/Article/details/gtunnkwfon.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.c1oappe.top/Article/details/gtywqxkqrn.html

Ruby: class MyError < StandardError; end
来源：http://dali.tian-w.cn/Article/details/gtxqlzcszo.html

C#:   class MyException : Exception {}
来源：http://dali.zhoulong.xyz/Article/details/gtyeumlkkg.html

[H05] 捕获特定类型
来源：http://dali.hammf.cn/Article/details/gtuxrwdoal.html

Py:   except ValueError as e:
来源：http://dali.mhx1999.top/Article/details/gtdepkkeky.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.ppjwa.cn/Article/details/gtabiwtkdd.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaedjrikt.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.ivvv.top/Article/details/gtzwfwerdr.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.cqqwz.cn/Article/details/gtzskulvcq.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.kuanghao11.cn/Article/details/gtqmrwqhpu.html

Ruby: rescue ArgumentError => e
来源：http://dali.chenlongwang.top/Article/details/gtniglxfsm.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhengqikj.top/Article/details/gtltlzkllv.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gtcmtryofo.html

Py:   value = d.get("k") or default
来源：http://dali.sweek.top/Article/details/gtlygjnxkd.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.vqdsnc.cn/Article/details/gtijowruil.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yj20258.top/Article/details/gtacxcwpld.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhongyouzk.top/Article/details/gthkmyibpg.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.ehwqpu.com/Article/details/gtroqbogwo.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yangfankeji.com/Article/details/gtkaelmnyj.html

Ruby: d&.dig(:a, :b)
来源：http://dali.dianchejie.cn/Article/details/gtxavpanac.html

C#:   obj?.A?.B ?? default
来源：http://dali.svipenyu.cn/Article/details/gthckpgfld.html

[H07] 断言
来源：http://dali.svipenyu.cn/Article/details/gtvtzjiiqg.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yueranfly.top/Article/details/gtmwvsfblw.html

PHP:  assert($x > 0);
来源：http://dali.snrcjt.cn/Article/details/gtkkucwqkj.html

JS:   console.assert(x > 0);
来源：http://dali.pycfn.com/Article/details/gtgutmpmbu.html


<!-- 参考信息 -->