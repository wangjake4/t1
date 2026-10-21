代发 wailian999

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.chenlongwang.top/Article/details/gtidujzoqy.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zycfv.cn/Article/details/gtcmognxgg.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.dashuyun.cn/Article/details/gtkhizolnd.html

[F04] 追加写入文件
来源：http://dali.feifeiyinyue.top/Article/details/gtvfrxpzmw.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmwliihal.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.iojbl.cn/Article/details/gtkrrzwojf.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hnqzz.top/Article/details/gthwjcbbqm.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.aizwys.cn/Article/details/gtfblphnzc.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hongshengwenyu.top/Article/details/gtemnpembl.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.aizwys.cn/Article/details/gtuporxzmz.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.guannengcc.top/Article/details/gtfevbhavi.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.xinyue.icu/Article/details/gtylbmxlbt.html

[F05] 判断文件或目录是否存在
来源：http://dali.tanke756.top/Article/details/gtsutmobvv.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.cucudq.cn/Article/details/gtthjpttrz.html

PHP:  file_exists("a.txt");
来源：http://dali.ybcxt.top/Article/details/gtlzvjhqku.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtbzaoorsd.html

TS:   fs.existsSync("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtudyzxplo.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jinqigufen.top/Article/details/gthlehdxeu.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.svipenyu.cn/Article/details/gtkyluytyf.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gttyksnehx.html

C#:   File.Exists("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtpyiqetmb.html

[F06] 删除文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcpfoonkd.html

Py:   os.remove("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtoxcrnkgl.html

PHP:  unlink("a.txt");
来源：http://dali.jiagoushi.top/Article/details/gthoghhhca.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yj20258.top/Article/details/gtqfmtcubg.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.meibo888.top/Article/details/gtghgeyrov.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.tian-w.cn/Article/details/gtmpndbcln.html

Go:   os.Remove("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtcxsrzhax.html

Ruby: File.delete("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtmsenkwfd.html

C#:   File.Delete("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gtehdjpdij.html

[F07] 创建目录（含多级）
来源：http://dali.svipenyu.cn/Article/details/gtshukvuqr.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.pengpengdd.cyou/Article/details/gtfoeyhmel.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.chenjidiqi.icu/Article/details/gthukkhgwv.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsbtejfnb.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.pycfn.com/Article/details/gtzotluttr.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.tanke756.top/Article/details/gttewysaxh.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.shanyushiyangtech.top/Article/details/gtkyslgwhd.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jqgfzy.top/Article/details/gtytpjiaen.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.dianchejie.cn/Article/details/gtahvcvpmz.html

[F08] 遍历目录
来源：http://dali.jlsjyb.cn/Article/details/gtbjopbjjd.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.gzhubu.top/Article/details/gtejblzave.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.hysaishi.cn/Article/details/gtwqmiooaf.html

JS:   fs.readdirSync("dir")
来源：http://dali.vqdsnc.cn/Article/details/gtjolnnsyk.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhixingplan.top/Article/details/gtpopcgylv.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.mhx1999.top/Article/details/gtzcledfcc.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jqgufenzy.top/Article/details/gtmpvuoysx.html

Ruby: Dir.children("dir")
来源：http://dali.316326.xyz/Article/details/gtitgvkvxs.html

C#:   Directory.GetFiles("dir")
来源：http://dali.sxryk.cn/Article/details/gtzjiqjbfp.html

[F09] 获取文件大小
来源：http://dali.nanxinkj.top/Article/details/gtcegrzyae.html

Py:   os.path.getsize("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gttpcotkbm.html

PHP:  filesize("a.txt");
来源：http://dali.daxiang520.top/Article/details/gthghbcqra.html

JS:   fs.statSync("a.txt").size
来源：http://dali.ppjwa.cn/Article/details/gttcwcnozt.html

TS:   fs.statSync("a.txt").size
来源：http://dali.316326.xyz/Article/details/gteoujklxa.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcurvjwgg.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.andypj.xyz/Article/details/gtwtsxcvmg.html

Ruby: File.size("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtopdbqstf.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.aizwys.cn/Article/details/gtwjvlmmyn.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.wangshuangyany.cn/Article/details/gtusklwgld.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.smart0.xyz/Article/details/gttycyrpfx.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jqgfzy.top/Article/details/gtlwmwjpbj.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.ivvv.top/Article/details/gtwnhazxlo.html

TS:   path.extname("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtgmrjiglv.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jlsjyb.cn/Article/details/gtezjiiqhj.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.pycfn.com/Article/details/gtbkjkolgv.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.birdmap.top/Article/details/gtcikwnpnu.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtqqwzzutx.html

[F11] 复制与移动文件
来源：http://dali.xziqi.cn/Article/details/gtpjmhgfbd.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtpkickkfv.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.havefunace.top/Article/details/gtytbdqofx.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.tian-w.cn/Article/details/gtgzcqjugp.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.nwbrower.top/Article/details/gtzovxhcub.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yj20258888.top/Article/details/gtqwctgouz.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.xziqi.cn/Article/details/gtswjhawql.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yvedp.cn/Article/details/gtpegueyvn.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jlsjyb.cn/Article/details/gtznwbotri.html

[F12] CSV 读写
来源：http://dali.nwbrower.top/Article/details/gtwppatwpg.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.gotoacloud.top/Article/details/gtwyvctdea.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hnxiangtu.top/Article/details/gtybxevjev.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.9152youxi.cn/Article/details/gtiyhtqjrd.html

TS:   // 同上
来源：http://dali.yvedp.cn/Article/details/gtsepcpfbp.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.sxryk.cn/Article/details/gtdlnsotsi.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.sweek.top/Article/details/gtahckrxcn.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.ydzc1.top/Article/details/gtjyqbokhu.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.gogol.net.cn/Article/details/gtmooibpxy.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtkvrsxbyx.html

G. 面向对象
来源：http://dali.meibo888.top/Article/details/gtkqmlghbh.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtlczotipo.html

[G01] 定义类
来源：http://dali.ywan-chungtsiang.top/Article/details/gtokskzswt.html

Py:   class User: pass
来源：http://dali.9152youxi.cn/Article/details/gtwlpnrizx.html

PHP:  class User {}
来源：http://dali.nanxinkj.top/Article/details/gtijeilbov.html

JS:   class User {}
来源：http://dali.yuanzhike.top/Article/details/gthcnvmqsz.html

TS:   class User { name: string = ""; }
来源：http://dali.gzhubu.top/Article/details/gtkpsvxrby.html

Java: class User {}
来源：http://dali.gzhubu.top/Article/details/gtdochatdn.html

Go:   type User struct { Name string }
来源：http://dali.xziqi.cn/Article/details/gtmpkarzrf.html

Ruby: class User; end
来源：http://dali.cashguo.top/Article/details/gtuhpugfjj.html

C#:   class User {}
来源：http://dali.gzhubu.top/Article/details/gtnzrlcakb.html

[G02] 构造函数
来源：http://dali.tanke756.top/Article/details/gtyymueoev.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.chenlongwang.top/Article/details/gtwtkrktlw.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.daria6918.cn/Article/details/gtsukwndqs.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.316326.xyz/Article/details/gtxbcvrrah.html

TS:   constructor(public name: string) {}
来源：http://dali.jinqigfzy.top/Article/details/gtpwrwqyqe.html

Java: User(String name) { this.name = name; }
来源：http://dali.iojbl.cn/Article/details/gtlhlnexho.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jqgfzy.top/Article/details/gtntzuamac.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhijiandao.cn/Article/details/gtqgjtxyws.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jyoumei.cn/Article/details/gtmxfyqrvs.html

[G03] 实例属性
来源：http://dali.hammf.cn/Article/details/gtnvpabqrm.html

Py:   self.name = "x"
来源：http://dali.hysaishi.cn/Article/details/gtimoiadhz.html

PHP:  public string $name = "x";
来源：http://dali.yvedp.cn/Article/details/gtwslgvyzs.html

JS:   this.name = "x";
来源：http://dali.guannengcc.top/Article/details/gteopgimer.html

TS:   name: string = "x";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvoflqbzk.html

Java: private String name;
来源：http://dali.zhoulong.xyz/Article/details/gtawvyejtq.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.xuanzx.com/Article/details/gtwezzwxrz.html

Ruby: @name = "x"
来源：http://dali.cdnleiting.top/Article/details/gtjrgmsscj.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.hysaishi.cn/Article/details/gtbaqltmrn.html

[G04] 定义方法
来源：http://dali.9152youxi.cn/Article/details/gtirdhvbgf.html

Py:   def greet(self): return self.name
来源：http://dali.mhx1999.top/Article/details/gtgtwxwlkk.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.cdnleiting.top/Article/details/gtmuedgtik.html

JS:   greet() { return this.name; }
来源：http://dali.hnxiangtu.top/Article/details/gtrsadorjo.html

TS:   greet(): string { return this.name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtcbfuxcik.html

Java: String greet() { return name; }
来源：http://dali.hfpthk.cn/Article/details/gtresoyzlu.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yvedp.cn/Article/details/gtubkqgmrd.html

Ruby: def greet; @name; end
来源：http://dali.0kj1m.cn/Article/details/gtblglzxvg.html

C#:   public string Greet() => Name;
来源：http://dali.ivvv.top/Article/details/gtjaksgyyj.html

[G05] 继承
来源：http://dali.jqgfzy.top/Article/details/gtbrwatcrv.html

Py:   class Admin(User): pass
来源：http://dali.jqgfzy.top/Article/details/gtemdqohtw.html

PHP:  class Admin extends User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuhauoxhc.html

JS:   class Admin extends User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtnagbxebx.html

TS:   class Admin extends User {}
来源：http://dali.aibaodan.cn/Article/details/gtfprutzrg.html

Java: class Admin extends User {}
来源：http://dali.vqdsnc.cn/Article/details/gtdbwufcfw.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmkuzsnfd.html

Ruby: class Admin < User; end
来源：http://dali.ybcxt.top/Article/details/gtzfuugikm.html

C#:   class Admin : User {}
来源：http://dali.cucudq.cn/Article/details/gtkmncndwe.html

[G06] 重写方法
来源：http://dali.bjfxy.top/Article/details/gtuqolkukn.html

Py:   def greet(self): return "admin"
来源：http://dali.zhixingplan.top/Article/details/gttlqrbndv.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.mhx1999.top/Article/details/gtwjfdihiw.html

JS:   greet() { return "admin"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnmjpbsip.html

TS:   greet(): string { return "admin"; }
来源：http://dali.xziqi.cn/Article/details/gtgfeyfvvj.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yueranfly.top/Article/details/gtshzxbsgh.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.316326.xyz/Article/details/gtojmzodiz.html

Ruby: def greet; "admin"; end
来源：http://dali.zdqjudy.top/Article/details/gtpaqpnmty.html

C#:   public override string Greet() => "admin";
来源：http://dali.cheryme.top/Article/details/gtxvtebkim.html

[G07] 调用父类方法
来源：http://dali.snrcjt.cn/Article/details/gtulzsfrcc.html

Py:   super().greet()
来源：http://dali.0kj1m.cn/Article/details/gttcjvcfsr.html

PHP:  parent::greet();
来源：http://dali.chenzaomai.com/Article/details/gtwqlrzltn.html

JS:   super.greet();
来源：http://dali.meibo888.top/Article/details/gteavvmhgz.html

TS:   super.greet();
来源：http://dali.svipenyu.cn/Article/details/gtiprvcifu.html

Java: super.greet();
来源：http://dali.iojbl.cn/Article/details/gtsgqiyhyp.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.xuanzx.com/Article/details/gtdfnhqgzn.html

Ruby: super
来源：http://dali.zhijiandao.cn/Article/details/gtrvgtocmp.html

C#:   base.Greet();
来源：http://dali.hywenlv.cn/Article/details/gtdnqlrzfl.html

[G08] 静态方法与属性
来源：http://dali.jlsjyb.cn/Article/details/gtjsjbncts.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.ivvv.top/Article/details/gtbcfljfwu.html

PHP:  public static function f() {}
来源：http://dali.jyoumei.cn/Article/details/gtqaunnswt.html

JS:   static f() {}
来源：http://dali.svipenyu.cn/Article/details/gtquvasdal.html

TS:   static f(): void {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gthwvtgvpq.html

Java: static void f() {}
来源：http://dali.chenlongwang.top/Article/details/gteuuwjque.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.xuanzx.com/Article/details/gtqethrykg.html

Ruby: def self.f; end
来源：http://dali.feifeiyinyue.top/Article/details/gttxusmmhe.html

C#:   public static void F() {}
来源：http://dali.hfpthk.cn/Article/details/gtaeyvecgm.html

[G09] 接口 / 抽象类
来源：http://dali.jiagoushi.top/Article/details/gtfzofwhpv.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhixingplan.top/Article/details/gtjckpfhkc.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhongyouzk.top/Article/details/gtiehbmapp.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ydzc1.top/Article/details/gtehxcbbbd.html

TS:   interface Shape { area(): number; }
来源：http://dali.jinqigufen.top/Article/details/gtqxdzgspv.html

Java: interface Shape { double area(); }
来源：http://dali.sweek.top/Article/details/gtrbwcsnsv.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.ivvv.top/Article/details/gtdrvkjdhc.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.shangyingyoupin.top/Article/details/gtldguztcg.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwalnnbow.html

[G10] 访问控制
来源：http://dali.xinyue.icu/Article/details/gtykcjnuuj.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.feifeiyinyue.top/Article/details/gtveowffja.html

PHP:  public / protected / private
来源：http://dali.haohaochexian.top/Article/details/gtcbrrraso.html

JS:   #private 字段；其余公开
来源：http://dali.yueranfly.top/Article/details/gttdmokrnl.html

TS:   public / protected / private
来源：http://dali.ivvv.top/Article/details/gtvsvgpgfv.html

Java: public / protected / private / 默认包级
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnskfmfja.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jqgfzy.top/Article/details/gtfcymxpct.html

Ruby: public / protected / private
来源：http://dali.0kj1m.cn/Article/details/gtjvulsnwr.html

C#:   public / protected / private / internal
来源：http://dali.zhixingplan.top/Article/details/gthovmyplb.html

[G11] getter / setter
来源：http://dali.yuanzhike.top/Article/details/gtukgwbqqu.html

Py:   @property 与 @x.setter
来源：http://dali.dashuyun.cn/Article/details/gtzwvqcvof.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.bjfxy.top/Article/details/gtuenqytfx.html

JS:   get name() { return this._name; }
来源：http://dali.svipenyu.cn/Article/details/gtjnvxlkxw.html

TS:   get name(): string { return this._name; }
来源：http://dali.ppjwa.cn/Article/details/gtxzrgjxmm.html

Java: public String getName() { return name; }
来源：http://dali.tanke756.top/Article/details/gtymlprzyd.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.andypj.xyz/Article/details/gtzpmftlhi.html

Ruby: attr_accessor :name
来源：http://dali.cashguo.top/Article/details/gtelfjsufo.html

C#:   public string Name { get; set; }
来源：http://dali.jinghuilouyu.cn/Article/details/gttigatnla.html

[G12] 对象转字符串
来源：http://dali.cashguo.top/Article/details/gtfafawcdh.html

Py:   def __str__(self): return self.name
来源：http://dali.nwbrower.top/Article/details/gtxhnnfqrc.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtoeqtswdl.html

JS:   toString() { return this.name; }
来源：http://dali.zhixingplan.top/Article/details/gtcunfoliv.html

TS:   toString(): string { return this.name; }
来源：http://dali.cucudq.cn/Article/details/gtwlgotypy.html

Java: @Override public String toString() { return name; }
来源：http://dali.jlsjyb.cn/Article/details/gttpmpyncr.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxppoteff.html

Ruby: def to_s; @name; end
来源：http://dali.jyoumei.cn/Article/details/gtojqtkzbq.html

C#:   public override string ToString() => Name;
来源：http://dali.zhixingplan.top/Article/details/gtdynybmlt.html

[G13] 判断对象类型
来源：http://dali.shzxlz.cn/Article/details/gtpopffqyr.html

Py:   isinstance(u, User)
来源：http://dali.zdqjudy.top/Article/details/gtdypddqwg.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gtqdfimvmi.html

JS:   u instanceof User
来源：http://dali.guannengcc.top/Article/details/gtwjumqhvx.html

TS:   u instanceof User
来源：http://dali.cheryme.top/Article/details/gtpecnsxpf.html

Java: u instanceof User
来源：http://dali.smart0.xyz/Article/details/gtjjpwocai.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhixingplan.top/Article/details/gtlhqddpbu.html

Ruby: u.is_a?(User)
来源：http://dali.jianghu66.top/Article/details/gtzwxooxfg.html

C#:   u is User
来源：http://dali.yueranfly.top/Article/details/gtinarretk.html

[G14] 数据类 / record
来源：http://dali.chenjidiqi.icu/Article/details/gtwieubahe.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zycfv.cn/Article/details/gtwpzshwdr.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.gaohongyu789.top/Article/details/gtwglcxyny.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlgujywpl.html

TS:   type User = { name: string; age: number };
来源：http://dali.shuidangran.top/Article/details/gtkzsrtobi.html

Java: record User(String name, int age) {}
来源：http://dali.snrcjt.cn/Article/details/gtkblxjyqu.html

Go:   type User struct { Name string; Age int }
来源：http://dali.cdnleiting.top/Article/details/gtjvcjnpbf.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jlsjyb.cn/Article/details/gtlcbbnmss.html

C#:   record User(string Name, int Age);
来源：http://dali.cdnleiting.top/Article/details/gtjuzystbr.html

[G15] 枚举
来源：http://dali.gotoacloud.top/Article/details/gtxkjtrqxt.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.birdmap.top/Article/details/gtidcrpdoo.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.hnqzz.top/Article/details/gtklxccgbj.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.hnqzz.top/Article/details/gtfguazrgr.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.quarkkingdee.top/Article/details/gtfxoshjte.html

Java: enum Color { RED, GREEN }
来源：http://dali.gzhubu.top/Article/details/gtujdgbcyj.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.chenlongwang.top/Article/details/gtsvhjsqly.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhaomingkeji.xyz/Article/details/gttvgllikb.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xuanzx.com/Article/details/gtldpfxtok.html

[G16] 对象转数组 / 字典
来源：http://dali.shzxlz.cn/Article/details/gtkteruosa.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jlsjyb.cn/Article/details/gtyhswujws.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gtgyrznsuk.html

JS:   Object.entries(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkodoesgw.html

TS:   Object.entries(obj)
来源：http://dali.yj20258.top/Article/details/gtnoglzvwl.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.cdnleiting.top/Article/details/gtlaoszuvv.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.chenlongwang.top/Article/details/gtfrhrhkmh.html

Ruby: obj.instance_variables
来源：http://dali.cheryme.top/Article/details/gtzwlojuso.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.gogol.net.cn/Article/details/gtezboiqkm.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtirduamka.html

H. 异常与错误处理
来源：http://dali.sweek.top/Article/details/gtgkdnzwrs.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gthfxcpzok.html

[H01] try / catch 基础
来源：http://dali.jinqigfzy.top/Article/details/gtaarqlbka.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.shuidangran.top/Article/details/gthjxgyvyu.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhoulong.xyz/Article/details/gtdouoflbb.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.cqqwz.cn/Article/details/gtaozzmwpq.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.316326.xyz/Article/details/gtmvbziaut.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yj202588.top/Article/details/gtmasijuuv.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.gaohongyu789.top/Article/details/gtpvqotgfy.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.dashuyun.cn/Article/details/gtiglmhtcq.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.chenzaomai.com/Article/details/gtdpmxqake.html

[H02] finally / ensure 收尾
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuqxshzmr.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.svipenyu.cn/Article/details/gtpytiqlzb.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.aibaodan.cn/Article/details/gtameonxzd.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.dashuyun.cn/Article/details/gtxxtdzzhv.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.xuanzx.com/Article/details/gtchddowgz.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.havefunace.top/Article/details/gthijnsdek.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.daxiang520.top/Article/details/gtzcoeikvt.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.hnxiangtu.top/Article/details/gtjwxndvtb.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtdygljhty.html

[H03] 主动抛出异常
来源：http://dali.cqqwz.cn/Article/details/gtjaxtwijv.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhijiandao.cn/Article/details/gtysfhrdaf.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.cqqwz.cn/Article/details/gtspjpsayg.html

JS:   throw new Error("错误信息");
来源：http://dali.zhoulong.xyz/Article/details/gtqazieofj.html

TS:   throw new Error("错误信息");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtggbaldfq.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.chenzaomai.com/Article/details/gttxwbhvao.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.shzxlz.cn/Article/details/gtukqybmdm.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.feifeiyinyue.top/Article/details/gtwoktlils.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.nanxuanxn.top/Article/details/gtwdxeatiu.html

[H04] 自定义异常类型
来源：http://dali.yuanzhike.top/Article/details/gtrnwvcyvt.html

Py:   class MyError(Exception): pass
来源：http://dali.pycfn.com/Article/details/gtxfyupidz.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.dianchejie.cn/Article/details/gtayfczzrp.html

JS:   class MyError extends Error {}
来源：http://dali.daria6918.cn/Article/details/gtrtnsxahb.html

TS:   class MyError extends Error {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnrhfatqk.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jyoumei.cn/Article/details/gtunxhccml.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.nwbrower.top/Article/details/gtomxyzhki.html

Ruby: class MyError < StandardError; end
来源：http://dali.fzhhl.top/Article/details/gtkfdfjvrr.html

C#:   class MyException : Exception {}
来源：http://dali.hnqzz.top/Article/details/gteeimdbve.html

[H05] 捕获特定类型
来源：http://dali.ivvv.top/Article/details/gtsdpfxskg.html

Py:   except ValueError as e:
来源：http://dali.ivvv.top/Article/details/gtzhjdisgc.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jyoumei.cn/Article/details/gtyiovtrun.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yj20258888.top/Article/details/gtefdyqmad.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.meibo888.top/Article/details/gtdnurynka.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtoucmowex.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.sufxvd.cn/Article/details/gtudafgrdo.html

Ruby: rescue ArgumentError => e
来源：http://dali.guannengcc.top/Article/details/gtxvuxaqah.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtvjtbcckt.html

[H06] 可选值 / 空值安全访问
来源：http://dali.quarkkingdee.top/Article/details/gtimlhkrzl.html

Py:   value = d.get("k") or default
来源：http://dali.9152youxi.cn/Article/details/gtvcbulayc.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcchbbjoo.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.sufxvd.cn/Article/details/gthsbhezhh.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jlsjyb.cn/Article/details/gtyxbzzksm.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yvedp.cn/Article/details/gthlcjxeqz.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.daria6918.cn/Article/details/gtkkrmhkrt.html

Ruby: d&.dig(:a, :b)
来源：http://dali.nwbrower.top/Article/details/gttuplecuq.html

C#:   obj?.A?.B ?? default
来源：http://dali.tian-w.cn/Article/details/gtwxafnvtn.html

[H07] 断言
来源：http://dali.xziqi.cn/Article/details/gtundsygvu.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhijiandao.cn/Article/details/gtjlrlowdq.html

PHP:  assert($x > 0);
来源：http://dali.ybcxt.top/Article/details/gtlhioqigc.html

JS:   console.assert(x > 0);
来源：http://dali.cashguo.top/Article/details/gtdigmjhea.html

TS:   console.assert(x > 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gtnyrdiyvf.html

Java: assert x > 0 : "必须为正";
来源：http://dali.aizwys.cn/Article/details/gtmyzvnflz.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.xuetiantiany.cn/Article/details/gtzknrukgv.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.tianlin.xyz/Article/details/gtdupmogdr.html

C#:   Debug.Assert(x > 0);
来源：http://dali.daria6918.cn/Article/details/gtyaixbxpo.html

[H08] 获取错误信息与堆栈
来源：http://dali.ybcxt.top/Article/details/gtbgrtwksy.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.bjfxy.top/Article/details/gtledpxvux.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.shzxlz.cn/Article/details/gtosjfabwt.html


<!-- 参考信息 -->