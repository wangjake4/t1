代发 wailian999

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.guannengcc.top/Article/details/gthqvvxjoh.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yuxming.cn/Article/details/gtghsaxiiw.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.daria6918.cn/Article/details/gtwetofglx.html

[F04] 追加写入文件
来源：http://dali.yonumen.top/Article/details/gtkrmrayxq.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.fzhhl.top/Article/details/gtrkmykzxp.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.hysaishi.cn/Article/details/gtblnanebq.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwdadknag.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.pycfn.com/Article/details/gtzljwqymn.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.xziqi.cn/Article/details/gtkvoxktdt.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jyoumei.cn/Article/details/gtaafkhflm.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbpwhgzgn.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jianghu66.top/Article/details/gtixnecitw.html

[F05] 判断文件或目录是否存在
来源：http://dali.snrcjt.cn/Article/details/gtleoocwbu.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.ehwqpu.com/Article/details/gtshyehsra.html

PHP:  file_exists("a.txt");
来源：http://dali.yangfankeji.com/Article/details/gtjpmimndf.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtobouowti.html

TS:   fs.existsSync("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtudopvnom.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yonumen.top/Article/details/gtdsbjelzt.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.xylfe.cn/Article/details/gtalyspxjr.html

Ruby: File.exist?("a.txt")
来源：http://dali.smart0.xyz/Article/details/gtamaodhnj.html

C#:   File.Exists("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtzgoysdlh.html

[F06] 删除文件
来源：http://dali.jiagoushi.top/Article/details/gtyiatfcjq.html

Py:   os.remove("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtjzfoovcm.html

PHP:  unlink("a.txt");
来源：http://dali.shuidangran.top/Article/details/gtqrqiesvc.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gthzhvtkac.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtxskcwnrt.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.nanxuanxn.top/Article/details/gtpfzccfpu.html

Go:   os.Remove("a.txt")
来源：http://dali.meibo888.top/Article/details/gtnseftoyg.html

Ruby: File.delete("a.txt")
来源：http://dali.sweek.top/Article/details/gtbhltymuh.html

C#:   File.Delete("a.txt");
来源：http://dali.jianghu66.top/Article/details/gtvcqnbfzz.html

[F07] 创建目录（含多级）
来源：http://dali.zhoulong.xyz/Article/details/gtcvvrrebr.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.ybcxt.top/Article/details/gtmpycsfqo.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.cdnleiting.top/Article/details/gtmwceazyq.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yj20258.top/Article/details/gtekbrogql.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zdqjudy.top/Article/details/gtpgtsleho.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yj20258888.top/Article/details/gtanonoroa.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.tanke756.top/Article/details/gtvyaosnqb.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.redwolf501.top/Article/details/gtegxkafjn.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.nanxuanxn.top/Article/details/gtuisegxex.html

[F08] 遍历目录
来源：http://dali.hnxiangtu.top/Article/details/gtekluhoje.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.316326.xyz/Article/details/gtnmtrgpbx.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.pycfn.com/Article/details/gtmqyjahrc.html

JS:   fs.readdirSync("dir")
来源：http://dali.feifeiyinyue.top/Article/details/gtdtweejsj.html

TS:   fs.readdirSync("dir")
来源：http://dali.nanxinkj.top/Article/details/gtnvurllrs.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.gotoacloud.top/Article/details/gtksdugmrq.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gtylbnmmqj.html

Ruby: Dir.children("dir")
来源：http://dali.feifeiyinyue.top/Article/details/gtxtsfngtq.html

C#:   Directory.GetFiles("dir")
来源：http://dali.ehwqpu.com/Article/details/gtxzgjjaqu.html

[F09] 获取文件大小
来源：http://dali.fzhhl.top/Article/details/gtyoqwkhtp.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtocinhfqb.html

PHP:  filesize("a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gtajcaahnh.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yueranfly.top/Article/details/gtfbhmvnzf.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yj20258.top/Article/details/gtitmuzbkq.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.xylfe.cn/Article/details/gteysbdxrv.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.snrcjt.cn/Article/details/gtbafcpdkr.html

Ruby: File.size("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtgfmqshtu.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.hammf.cn/Article/details/gtdrkiwxfq.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zdqjudy.top/Article/details/gtsdpobday.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.havefunace.top/Article/details/gtmtzecrrk.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yonumen.top/Article/details/gtyekkohzc.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtnnoimkhp.html

TS:   path.extname("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtncvoeqpo.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.pycfn.com/Article/details/gtrlnenawr.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtddefsuzh.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.ydzc1.top/Article/details/gtpvyatalk.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.aizwys.cn/Article/details/gtfscejkfr.html

[F11] 复制与移动文件
来源：http://dali.jinqigfzy.top/Article/details/gtrfokkpby.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.daxiang520.top/Article/details/gtwtnuvnyz.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.wangdashe.top/Article/details/gtuuocizyw.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.aizwys.cn/Article/details/gtcwnwtlyf.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jianghu66.top/Article/details/gtivktsjpw.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yangfankeji.com/Article/details/gthayvfaba.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jiagoushi.top/Article/details/gtteypwxmf.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.haohaochexian.top/Article/details/gtkkxklhfx.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.c1oappe.top/Article/details/gtryjtzkfs.html

[F12] CSV 读写
来源：http://dali.jlsjyb.cn/Article/details/gtpxrodxoi.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.havefunace.top/Article/details/gtjfseyyme.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.snrcjt.cn/Article/details/gtnmugfova.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hysaishi.cn/Article/details/gtbfzscluc.html

TS:   // 同上
来源：http://dali.chenzaomai.com/Article/details/gtllmwqnat.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhiwuduotai.top/Article/details/gtnpmnolsa.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zycfv.cn/Article/details/gtnkfrjkob.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuwvuhnxe.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jinghuilouyu.cn/Article/details/gtmawfqenc.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtywmrllhj.html

G. 面向对象
来源：http://dali.tian-w.cn/Article/details/gtxlerrmwo.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtsepybfmw.html

[G01] 定义类
来源：http://dali.sufxvd.cn/Article/details/gtfgfujkia.html

Py:   class User: pass
来源：http://dali.shangyingyoupin.top/Article/details/gtbkzghgay.html

PHP:  class User {}
来源：http://dali.ydzc1.top/Article/details/gtzaxzhjto.html

JS:   class User {}
来源：http://dali.cdnleiting.top/Article/details/gtxtldzvpk.html

TS:   class User { name: string = ""; }
来源：http://dali.iojbl.cn/Article/details/gtqxlrkout.html

Java: class User {}
来源：http://dali.yuanzhike.top/Article/details/gtxsyxputf.html

Go:   type User struct { Name string }
来源：http://dali.zycfv.cn/Article/details/gtlrtyushl.html

Ruby: class User; end
来源：http://dali.dianchejie.cn/Article/details/gtpcfdtymq.html

C#:   class User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtqyawxhgs.html

[G02] 构造函数
来源：http://dali.bjfxy.top/Article/details/gtqdviyoix.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.tianlin.xyz/Article/details/gtcewzdkrw.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jqgufenzy.top/Article/details/gtyflqpyye.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.xuanzx.com/Article/details/gtdlyozlnz.html

TS:   constructor(public name: string) {}
来源：http://dali.vqdsnc.cn/Article/details/gttnrfggxs.html

Java: User(String name) { this.name = name; }
来源：http://dali.meibo888.top/Article/details/gttosiinrj.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.dianchejie.cn/Article/details/gtowgoufkq.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.tian-w.cn/Article/details/gtngcwpumq.html

C#:   public User(string name) { Name = name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtqrqryfqy.html

[G03] 实例属性
来源：http://dali.daxiang520.top/Article/details/gtlnufvbpw.html

Py:   self.name = "x"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtruwvryru.html

PHP:  public string $name = "x";
来源：http://dali.chenlongwang.top/Article/details/gtmoytavso.html

JS:   this.name = "x";
来源：http://dali.dianchejie.cn/Article/details/gtgniokloj.html

TS:   name: string = "x";
来源：http://dali.kuanghao11.cn/Article/details/gtnxpegndx.html

Java: private String name;
来源：http://dali.shuidangran.top/Article/details/gtrjhsdaro.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.vqdsnc.cn/Article/details/gtbkcgzjfz.html

Ruby: @name = "x"
来源：http://dali.fengsongda.top/Article/details/gtsjyhnfif.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.xinyue.icu/Article/details/gtaximzwia.html

[G04] 定义方法
来源：http://dali.wangdashe.top/Article/details/gtwukpjzwq.html

Py:   def greet(self): return self.name
来源：http://dali.vqdsnc.cn/Article/details/gtzspdfrnj.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgfudknhn.html

JS:   greet() { return this.name; }
来源：http://dali.shuidangran.top/Article/details/gtdvrnggav.html

TS:   greet(): string { return this.name; }
来源：http://dali.vqdsnc.cn/Article/details/gtjupakkph.html

Java: String greet() { return name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtuqwblgsv.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.sxryk.cn/Article/details/gtrllxgpjh.html

Ruby: def greet; @name; end
来源：http://dali.hysaishi.cn/Article/details/gtmvqwmyoc.html

C#:   public string Greet() => Name;
来源：http://dali.yvedp.cn/Article/details/gtpmiblpid.html

[G05] 继承
来源：http://dali.jlsjyb.cn/Article/details/gtgpndcqao.html

Py:   class Admin(User): pass
来源：http://dali.bjfxy.top/Article/details/gtiblbpdeb.html

PHP:  class Admin extends User {}
来源：http://dali.hywenlv.cn/Article/details/gtwllwkwrm.html

JS:   class Admin extends User {}
来源：http://dali.9152youxi.cn/Article/details/gtecthtjtq.html

TS:   class Admin extends User {}
来源：http://dali.wangdashe.top/Article/details/gtdizzqlrc.html

Java: class Admin extends User {}
来源：http://dali.hfpthk.cn/Article/details/gtndmfufms.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.xuanzx.com/Article/details/gtjdlaldcs.html

Ruby: class Admin < User; end
来源：http://dali.svipenyu.cn/Article/details/gtdxfzpaxz.html

C#:   class Admin : User {}
来源：http://dali.svipenyu.cn/Article/details/gtnnazyeqj.html

[G06] 重写方法
来源：http://dali.c1oappe.top/Article/details/gtxvjnctqs.html

Py:   def greet(self): return "admin"
来源：http://dali.tian-w.cn/Article/details/gtfnjqxfol.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.nanxinkj.top/Article/details/gtacpmnjvu.html

JS:   greet() { return "admin"; }
来源：http://dali.ehwqpu.com/Article/details/gtwqqyzctt.html

TS:   greet(): string { return "admin"; }
来源：http://dali.dianchejie.cn/Article/details/gtllghmkbn.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtqlpbmnls.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.wangdashe.top/Article/details/gtngoteheg.html

Ruby: def greet; "admin"; end
来源：http://dali.gogol.net.cn/Article/details/gtoqofhpzx.html

C#:   public override string Greet() => "admin";
来源：http://dali.yangfankeji.com/Article/details/gtiwkhodlk.html

[G07] 调用父类方法
来源：http://dali.sufxvd.cn/Article/details/gtrjnhqkpe.html

Py:   super().greet()
来源：http://dali.jlsjyb.cn/Article/details/gtwputmuox.html

PHP:  parent::greet();
来源：http://dali.zdqjudy.top/Article/details/gthcykebtd.html

JS:   super.greet();
来源：http://dali.vqdsnc.cn/Article/details/gtkrnbbteu.html

TS:   super.greet();
来源：http://dali.vqdsnc.cn/Article/details/gtfksmebfm.html

Java: super.greet();
来源：http://dali.xuanzx.com/Article/details/gtbomtfwup.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.iojbl.cn/Article/details/gtcxblkilh.html

Ruby: super
来源：http://dali.svipenyu.cn/Article/details/gtmqcrwiqs.html

C#:   base.Greet();
来源：http://dali.ybcxt.top/Article/details/gtfkdwemvi.html

[G08] 静态方法与属性
来源：http://dali.fzhhl.top/Article/details/gtqecglpap.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hywenlv.cn/Article/details/gtxamavswt.html

PHP:  public static function f() {}
来源：http://dali.zycfv.cn/Article/details/gtejxjkgbi.html

JS:   static f() {}
来源：http://dali.dashuyun.cn/Article/details/gtuoiwrsrd.html

TS:   static f(): void {}
来源：http://dali.gotoacloud.top/Article/details/gtqlkeqooc.html

Java: static void f() {}
来源：http://dali.316326.xyz/Article/details/gtpceqgbth.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.sufxvd.cn/Article/details/gtskujkoyl.html

Ruby: def self.f; end
来源：http://dali.zhoulong.xyz/Article/details/gtdhkpagcs.html

C#:   public static void F() {}
来源：http://dali.jqgfzy.top/Article/details/gtgcvxossf.html

[G09] 接口 / 抽象类
来源：http://dali.zhijiandao.cn/Article/details/gtcehyxqfh.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yj202588.top/Article/details/gtnlsjunsh.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.ivvv.top/Article/details/gtbrcfyyjm.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.mhx1999.top/Article/details/gtktxvimdg.html

TS:   interface Shape { area(): number; }
来源：http://dali.nanxinkj.top/Article/details/gtadyttwef.html

Java: interface Shape { double area(); }
来源：http://dali.0kj1m.cn/Article/details/gteeiaocbb.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yangfankeji.com/Article/details/gtkaelrojw.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.andypj.xyz/Article/details/gtunrdxdpb.html

C#:   interface IShape { double Area(); }
来源：http://dali.sysykeji.top/Article/details/gtxeweqbzs.html

[G10] 访问控制
来源：http://dali.yj20258888.top/Article/details/gtsqbzfuim.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.bjfxy.top/Article/details/gtvokbtoin.html

PHP:  public / protected / private
来源：http://dali.cucudq.cn/Article/details/gtwfxxgxhp.html

JS:   #private 字段；其余公开
来源：http://dali.xylfe.cn/Article/details/gtpyvwmmds.html

TS:   public / protected / private
来源：http://dali.yongpay.top/Article/details/gtzmzmczzk.html

Java: public / protected / private / 默认包级
来源：http://dali.yj20258888.top/Article/details/gterzjqwgz.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jinghuilouyu.cn/Article/details/gtdqceuwyv.html

Ruby: public / protected / private
来源：http://dali.zhoulong.xyz/Article/details/gtkvnbxpyp.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gtdiftchxc.html

[G11] getter / setter
来源：http://dali.yvedp.cn/Article/details/gthcjctrem.html

Py:   @property 与 @x.setter
来源：http://dali.jinghuilouyu.cn/Article/details/gtceftsymm.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.gogol.net.cn/Article/details/gtvynwovlt.html

JS:   get name() { return this._name; }
来源：http://dali.mhx1999.top/Article/details/gtwxfnhlzv.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gtfukfivnl.html

Java: public String getName() { return name; }
来源：http://dali.meibo888.top/Article/details/gtrzjheevj.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.0kj1m.cn/Article/details/gtmmoqkaig.html

Ruby: attr_accessor :name
来源：http://dali.xuetiantiany.cn/Article/details/gtovsupwha.html

C#:   public string Name { get; set; }
来源：http://dali.yuanzhike.top/Article/details/gtkexbgxfd.html

[G12] 对象转字符串
来源：http://dali.aibaodan.cn/Article/details/gtxwhafdxt.html

Py:   def __str__(self): return self.name
来源：http://dali.dashuyun.cn/Article/details/gtgulsqbzg.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.daxiang520.top/Article/details/gtnnrrxsfv.html

JS:   toString() { return this.name; }
来源：http://dali.snrcjt.cn/Article/details/gtiuppyhri.html

TS:   toString(): string { return this.name; }
来源：http://dali.hnqzz.top/Article/details/gtgppkwazs.html

Java: @Override public String toString() { return name; }
来源：http://dali.mhx1999.top/Article/details/gtuvnhrfab.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.cqqwz.cn/Article/details/gtpzlfktdc.html

Ruby: def to_s; @name; end
来源：http://dali.yongpay.top/Article/details/gtgwxaujkq.html

C#:   public override string ToString() => Name;
来源：http://dali.ywan-chungtsiang.top/Article/details/gththchhlk.html

[G13] 判断对象类型
来源：http://dali.ybcxt.top/Article/details/gtdwzpaefc.html

Py:   isinstance(u, User)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtksfkxsnu.html

PHP:  $u instanceof User
来源：http://dali.dashuyun.cn/Article/details/gtvvhoqojm.html

JS:   u instanceof User
来源：http://dali.jyoumei.cn/Article/details/gtiygrnbaj.html

TS:   u instanceof User
来源：http://dali.gaohongyu789.top/Article/details/gtficohbbc.html

Java: u instanceof User
来源：http://dali.wangdashe.top/Article/details/gtymckdqjz.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.ybcxt.top/Article/details/gtodcbcjmf.html

Ruby: u.is_a?(User)
来源：http://dali.wangshuangyany.cn/Article/details/gtepcrxjzm.html

C#:   u is User
来源：http://dali.yueranfly.top/Article/details/gtyqtkalbb.html

[G14] 数据类 / record
来源：http://dali.aibaodan.cn/Article/details/gtcmseiptq.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhixingplan.top/Article/details/gtxfmjgiao.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yuanzhike.top/Article/details/gtxyqiqlck.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.chenlongwang.top/Article/details/gtasaaekyi.html

TS:   type User = { name: string; age: number };
来源：http://dali.wangshuangyany.cn/Article/details/gtbgcjeevg.html

Java: record User(String name, int age) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbsiwbdxc.html

Go:   type User struct { Name string; Age int }
来源：http://dali.chenlongwang.top/Article/details/gtjbgrzuzh.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.gotoacloud.top/Article/details/gtspvtbxut.html

C#:   record User(string Name, int Age);
来源：http://dali.cashguo.top/Article/details/gtpeedtxqu.html

[G15] 枚举
来源：http://dali.tianlin.xyz/Article/details/gtybacmkqy.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jinqigfzy.top/Article/details/gtbrkkfxoo.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yj202588.top/Article/details/gtdgyoqgsu.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.dashuyun.cn/Article/details/gtvpuyapfw.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sxryk.cn/Article/details/gtzteysgxz.html

Java: enum Color { RED, GREEN }
来源：http://dali.xuanzx.com/Article/details/gtkyuwhhnn.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhixingplan.top/Article/details/gtjkmlatwg.html

Ruby: Color = %i[red green].freeze
来源：http://dali.xziqi.cn/Article/details/gtzluhnqra.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jqgufenzy.top/Article/details/gthjcgghyw.html

[G16] 对象转数组 / 字典
来源：http://dali.sufxvd.cn/Article/details/gtanjfwyga.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.tian-w.cn/Article/details/gtgeznllnj.html

PHP:  get_object_vars($obj);
来源：http://dali.jinqigfzy.top/Article/details/gtlaynlcvl.html

JS:   Object.entries(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gteouqeqnu.html

TS:   Object.entries(obj)
来源：http://dali.yj202588.top/Article/details/gtyiyhizap.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hywenlv.cn/Article/details/gthxqrtwvm.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jinqigfzy.top/Article/details/gtvyfjulzd.html

Ruby: obj.instance_variables
来源：http://dali.bjfxy.top/Article/details/gtnazaamut.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.xuetiantiany.cn/Article/details/gtajrteuji.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtwlgnmzgb.html

H. 异常与错误处理
来源：http://dali.chenlongwang.top/Article/details/gttteimgpw.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtlrktkwjh.html

[H01] try / catch 基础
来源：http://dali.zycfv.cn/Article/details/gtmsqhyfdu.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.shangyingyoupin.top/Article/details/gtfkhzdgmw.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.c1oappe.top/Article/details/gtmgmssqqi.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.wangdashe.top/Article/details/gtghdxjppz.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zdqjudy.top/Article/details/gtvufrcixl.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.gotoacloud.top/Article/details/gtflrbzgku.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.c1oappe.top/Article/details/gtrwyllrrn.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.cqqwz.cn/Article/details/gtglqdnflt.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ppjwa.cn/Article/details/gtzvkvjjdn.html

[H02] finally / ensure 收尾
来源：http://dali.zycfv.cn/Article/details/gtsecdidvg.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.shangyingyoupin.top/Article/details/gtjzvfknfx.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jyoumei.cn/Article/details/gtipbxxkou.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.feifeiyinyue.top/Article/details/gtwxjhvtcq.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.quarkkingdee.top/Article/details/gtqmjojuze.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.havefunace.top/Article/details/gtiazogwec.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.smart0.xyz/Article/details/gtahhmgcms.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.smart0.xyz/Article/details/gtamhpdsay.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.hywenlv.cn/Article/details/gtslwlazog.html

[H03] 主动抛出异常
来源：http://dali.hysaishi.cn/Article/details/gtlvwwjtiq.html

Py:   raise ValueError("错误信息")
来源：http://dali.sweek.top/Article/details/gtbcgevwfj.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.feifeiyinyue.top/Article/details/gtsaqexdbo.html

JS:   throw new Error("错误信息");
来源：http://dali.cqqwz.cn/Article/details/gttksdelar.html

TS:   throw new Error("错误信息");
来源：http://dali.yuanzhike.top/Article/details/gtchieidvl.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.aibaodan.cn/Article/details/gtyllntxbg.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hywenlv.cn/Article/details/gtokkdiitg.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jianghu66.top/Article/details/gteopojljx.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.ivvv.top/Article/details/gttieyytoa.html

[H04] 自定义异常类型
来源：http://dali.xylfe.cn/Article/details/gtswceyccd.html

Py:   class MyError(Exception): pass
来源：http://dali.zhiwuduotai.top/Article/details/gtjazezoru.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.aibaodan.cn/Article/details/gtfuqgogrz.html

JS:   class MyError extends Error {}
来源：http://dali.pycfn.com/Article/details/gtpklyapvc.html

TS:   class MyError extends Error {}
来源：http://dali.chenzaomai.com/Article/details/gtbksuttvh.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jinqigufen.top/Article/details/gtusjdarbp.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zdqjudy.top/Article/details/gtneazdjcg.html

Ruby: class MyError < StandardError; end
来源：http://dali.daxiang520.top/Article/details/gtbxtpttuk.html

C#:   class MyException : Exception {}
来源：http://dali.cqqwz.cn/Article/details/gtjdtmaoso.html

[H05] 捕获特定类型
来源：http://dali.xuetiantiany.cn/Article/details/gttkjxvlxq.html

Py:   except ValueError as e:
来源：http://dali.iojbl.cn/Article/details/gtbohqevwp.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.shangyingyoupin.top/Article/details/gtkagokibl.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.xylfe.cn/Article/details/gtqjxfjnjo.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdszyuskx.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.xinyue.icu/Article/details/gtglncvmrx.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.xuanzx.com/Article/details/gtejtivnma.html

Ruby: rescue ArgumentError => e
来源：http://dali.c1oappe.top/Article/details/gtlhlrvbcf.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.mhx1999.top/Article/details/gtowjytyjt.html

[H06] 可选值 / 空值安全访问
来源：http://dali.cashguo.top/Article/details/gtaynnvmao.html

Py:   value = d.get("k") or default
来源：http://dali.dianchejie.cn/Article/details/gtqhfyvsmd.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.xinyue.icu/Article/details/gtssxzrkjd.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.dianchejie.cn/Article/details/gtyzubjxll.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.dashuyun.cn/Article/details/gtwrfcpwab.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.meibo888.top/Article/details/gtqxkgyjnl.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yuanzhike.top/Article/details/gtjmgxoncv.html

Ruby: d&.dig(:a, :b)
来源：http://dali.c1oappe.top/Article/details/gtfuxcfsow.html

C#:   obj?.A?.B ?? default
来源：http://dali.sweek.top/Article/details/gtoxoknzjh.html

[H07] 断言
来源：http://dali.jinqigufen.top/Article/details/gtzxzxpohz.html

Py:   assert x > 0, "必须为正"
来源：http://dali.hysaishi.cn/Article/details/gtbwicuxfy.html

PHP:  assert($x > 0);
来源：http://dali.zycfv.cn/Article/details/gtflrliqfd.html

JS:   console.assert(x > 0);
来源：http://dali.cashguo.top/Article/details/gttekdqbwj.html

TS:   console.assert(x > 0);
来源：http://dali.snrcjt.cn/Article/details/gtieqkzbvj.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jinqigfzy.top/Article/details/gtdskubnee.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.0kj1m.cn/Article/details/gtonrjmdie.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yuxming.cn/Article/details/gtcaixlepx.html

C#:   Debug.Assert(x > 0);
来源：http://dali.dianchejie.cn/Article/details/gtlqwpbniz.html

[H08] 获取错误信息与堆栈
来源：http://dali.hammf.cn/Article/details/gtfhymylrk.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jinghuilouyu.cn/Article/details/gtmkmabuud.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yuxming.cn/Article/details/gthdisyoia.html


<!-- 参考信息 -->