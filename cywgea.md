代发 wailian999

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.ppjwa.cn/Article/details/gteqdycpkx.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yangfankeji.com/Article/details/gtarhwnhqy.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.9152youxi.cn/Article/details/gthpmyhlrg.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sufxvd.cn/Article/details/gtqnyskjmm.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jqgufenzy.top/Article/details/gtndkotctz.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jinyuanbaomall.cn/Article/details/gthtdkzfvj.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.meibo888.top/Article/details/gtifwowyvt.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.nwbrower.top/Article/details/gtndrupfki.html

[F05] 判断文件或目录是否存在
来源：http://dali.tanke756.top/Article/details/gtwbjjkvtr.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.daria6918.cn/Article/details/gtkrpibmqu.html

PHP:  file_exists("a.txt");
来源：http://dali.cqqwz.cn/Article/details/gtlkviefrg.html

JS:   fs.existsSync("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvdzlumgd.html

TS:   fs.existsSync("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtgsfsyrbi.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhongyouzk.top/Article/details/gtotjpixdr.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jianghu66.top/Article/details/gtqvdokttg.html

Ruby: File.exist?("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtlfigyqnh.html

C#:   File.Exists("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtkekdhetz.html

[F06] 删除文件
来源：http://dali.dianchejie.cn/Article/details/gtkappffqr.html

Py:   os.remove("a.txt")
来源：http://dali.daxiang520.top/Article/details/gtupppcrmz.html

PHP:  unlink("a.txt");
来源：http://dali.yueranfly.top/Article/details/gtnqfbkaur.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvxjvbkiz.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtlawwzasv.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.dashuyun.cn/Article/details/gtyhgyxtfy.html

Go:   os.Remove("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtxcidhzkl.html

Ruby: File.delete("a.txt")
来源：http://dali.meibo888.top/Article/details/gtoydaraln.html

C#:   File.Delete("a.txt");
来源：http://dali.0kj1m.cn/Article/details/gtmcdxqpnl.html

[F07] 创建目录（含多级）
来源：http://dali.yongpay.top/Article/details/gtcsurneqc.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.sufxvd.cn/Article/details/gtfljnhiyc.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hysaishi.cn/Article/details/gtqlmqlblx.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ivvv.top/Article/details/gtnxcjzgym.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xziqi.cn/Article/details/gtgmpgljfw.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.mhx1999.top/Article/details/gtxaipexmz.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhiwuduotai.top/Article/details/gtzxfylgya.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.ppjwa.cn/Article/details/gtnazbpncg.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.aizwys.cn/Article/details/gtfchyxosq.html

[F08] 遍历目录
来源：http://dali.ivvv.top/Article/details/gtokdljpff.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.aibaodan.cn/Article/details/gtsbsecleo.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.chenjidiqi.icu/Article/details/gtyxgirlus.html

JS:   fs.readdirSync("dir")
来源：http://dali.xuetiantiany.cn/Article/details/gtwmmxfmci.html

TS:   fs.readdirSync("dir")
来源：http://dali.mhx1999.top/Article/details/gtfjsqfrvy.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.birdmap.top/Article/details/gtkdisaomf.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jqgfzy.top/Article/details/gtgplzrhaj.html

Ruby: Dir.children("dir")
来源：http://dali.havefunace.top/Article/details/gtchocjgln.html

C#:   Directory.GetFiles("dir")
来源：http://dali.xziqi.cn/Article/details/gtpzfcbqwv.html

[F09] 获取文件大小
来源：http://dali.pycfn.com/Article/details/gtirohkxor.html

Py:   os.path.getsize("a.txt")
来源：http://dali.bjfxy.top/Article/details/gtddpyrwol.html

PHP:  filesize("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gtnkxvxomx.html

JS:   fs.statSync("a.txt").size
来源：http://dali.bjfxy.top/Article/details/gtrupefrcy.html

TS:   fs.statSync("a.txt").size
来源：http://dali.hongshengwenyu.top/Article/details/gtcbhtittt.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtcchcyzpb.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.svipenyu.cn/Article/details/gtgbhrefzb.html

Ruby: File.size("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtlbohrvmr.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.hammf.cn/Article/details/gtrmqegfsl.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.9152youxi.cn/Article/details/gtzjagkedd.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnfykuvti.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.mhx1999.top/Article/details/gtblstvfnl.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtvoqvtapx.html

TS:   path.extname("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtnkmeurqq.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jlsjyb.cn/Article/details/gtftpowdyf.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.meibo888.top/Article/details/gtotcsggzy.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtfvavkiie.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.daria6918.cn/Article/details/gttolykfhe.html

[F11] 复制与移动文件
来源：http://dali.zhiwuduotai.top/Article/details/gtlrwytesd.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.xuanzx.com/Article/details/gtrvnreclj.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.cashguo.top/Article/details/gtudhdtbgd.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtraxckene.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.dianchejie.cn/Article/details/gtrcbnzvuo.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.havefunace.top/Article/details/gtcnvfjexc.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.svipenyu.cn/Article/details/gtsoasscna.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.daxiang520.top/Article/details/gtoeycuhos.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jinqigufen.top/Article/details/gtlgdgtury.html

[F12] CSV 读写
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqxlnxdvh.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.redwolf501.top/Article/details/gtwstsbyfj.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.andypj.xyz/Article/details/gtslkudwft.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hfpthk.cn/Article/details/gtjnnxmliq.html

TS:   // 同上
来源：http://dali.fengsongda.top/Article/details/gtcswxorls.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.redwolf501.top/Article/details/gtxmftuoxf.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.guowangkeji.top/Article/details/gtbquykdqx.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.tanke756.top/Article/details/gtmukqtgng.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.smart0.xyz/Article/details/gtsudrefco.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gthwtuoeyb.html

G. 面向对象
来源：http://dali.sysykeji.top/Article/details/gtwthfskir.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtcooyzelw.html

[G01] 定义类
来源：http://dali.nwbrower.top/Article/details/gtghovexhr.html

Py:   class User: pass
来源：http://dali.hongshengwenyu.top/Article/details/gtwvlliyjo.html

PHP:  class User {}
来源：http://dali.jlsjyb.cn/Article/details/gtcyoqwegd.html

JS:   class User {}
来源：http://dali.birdmap.top/Article/details/gtgyzzhqds.html

TS:   class User { name: string = ""; }
来源：http://dali.fzhhl.top/Article/details/gtvdvizqga.html

Java: class User {}
来源：http://dali.hammf.cn/Article/details/gtgweovbeh.html

Go:   type User struct { Name string }
来源：http://dali.jqgufenzy.top/Article/details/gtrfanbavd.html

Ruby: class User; end
来源：http://dali.iojbl.cn/Article/details/gthijahyer.html

C#:   class User {}
来源：http://dali.xziqi.cn/Article/details/gtpfrzyimo.html

[G02] 构造函数
来源：http://dali.zycfv.cn/Article/details/gtnglyrdon.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.hnxiangtu.top/Article/details/gtnwvuqmlz.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkdgretqx.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.cashguo.top/Article/details/gtkfeoifno.html

TS:   constructor(public name: string) {}
来源：http://dali.bjfxy.top/Article/details/gtjyitoucz.html

Java: User(String name) { this.name = name; }
来源：http://dali.iojbl.cn/Article/details/gthxjyicqr.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.ehwqpu.com/Article/details/gtfpabrqyr.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.iojbl.cn/Article/details/gtrgdjnqbu.html

C#:   public User(string name) { Name = name; }
来源：http://dali.hysaishi.cn/Article/details/gtteoozxwk.html

[G03] 实例属性
来源：http://dali.nanxinkj.top/Article/details/gtrquszsxp.html

Py:   self.name = "x"
来源：http://dali.nwbrower.top/Article/details/gtooajltjq.html

PHP:  public string $name = "x";
来源：http://dali.jiagoushi.top/Article/details/gtebqhoxgl.html

JS:   this.name = "x";
来源：http://dali.zhaomingkeji.xyz/Article/details/gthugwlvgd.html

TS:   name: string = "x";
来源：http://dali.hywenlv.cn/Article/details/gtlhzjhxgq.html

Java: private String name;
来源：http://dali.zhixingplan.top/Article/details/gtfgbtjuxj.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.gaohongyu789.top/Article/details/gtjehmpeod.html

Ruby: @name = "x"
来源：http://dali.gotoacloud.top/Article/details/gtidpdtqfm.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.xylfe.cn/Article/details/gtagdxlqps.html

[G04] 定义方法
来源：http://dali.chenzaomai.com/Article/details/gtrotqqvyg.html

Py:   def greet(self): return self.name
来源：http://dali.jiagoushi.top/Article/details/gtfxnrdiyv.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gtpmtyyvqt.html

JS:   greet() { return this.name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtheynqhyj.html

TS:   greet(): string { return this.name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtypxwnnvs.html

Java: String greet() { return name; }
来源：http://dali.hnqzz.top/Article/details/gthuczdgrb.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.cqqwz.cn/Article/details/gtticdmxzh.html

Ruby: def greet; @name; end
来源：http://dali.haohaochexian.top/Article/details/gtghccdmoh.html

C#:   public string Greet() => Name;
来源：http://dali.jyoumei.cn/Article/details/gtchwodjmi.html

[G05] 继承
来源：http://dali.xuetiantiany.cn/Article/details/gtgnzvpdvm.html

Py:   class Admin(User): pass
来源：http://dali.aizwys.cn/Article/details/gtzeqphees.html

PHP:  class Admin extends User {}
来源：http://dali.haohaochexian.top/Article/details/gtqzofsumc.html

JS:   class Admin extends User {}
来源：http://dali.guowangkeji.top/Article/details/gtesvqvudd.html

TS:   class Admin extends User {}
来源：http://dali.daxiang520.top/Article/details/gtjrojesio.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gtssmoojmc.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jqgfzy.top/Article/details/gtkctclzoo.html

Ruby: class Admin < User; end
来源：http://dali.xziqi.cn/Article/details/gtpbggxtge.html

C#:   class Admin : User {}
来源：http://dali.wangshuangyany.cn/Article/details/gtjpdxnzam.html

[G06] 重写方法
来源：http://dali.shzxlz.cn/Article/details/gtjkyyqkji.html

Py:   def greet(self): return "admin"
来源：http://dali.svipenyu.cn/Article/details/gttamsvcsx.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.haohaochexian.top/Article/details/gtbtqddlrj.html

JS:   greet() { return "admin"; }
来源：http://dali.wangshuangyany.cn/Article/details/gtdkzyrtmq.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hfpthk.cn/Article/details/gtqeuasium.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.kuanghao11.cn/Article/details/gtjiwsqvgy.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.shangyingyoupin.top/Article/details/gtplupgvtb.html

Ruby: def greet; "admin"; end
来源：http://dali.wangdashe.top/Article/details/gtvyqmllvf.html

C#:   public override string Greet() => "admin";
来源：http://dali.cucudq.cn/Article/details/gtligtdtgp.html

[G07] 调用父类方法
来源：http://dali.cdnleiting.top/Article/details/gtghevjppp.html

Py:   super().greet()
来源：http://dali.sufxvd.cn/Article/details/gthltrwqig.html

PHP:  parent::greet();
来源：http://dali.redwolf501.top/Article/details/gtwbvhuujr.html

JS:   super.greet();
来源：http://dali.yongpay.top/Article/details/gtwujvlvbt.html

TS:   super.greet();
来源：http://dali.redwolf501.top/Article/details/gtoififoqr.html

Java: super.greet();
来源：http://dali.wangdashe.top/Article/details/gtbwhlbkbn.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.9152youxi.cn/Article/details/gtbcamzdzt.html

Ruby: super
来源：http://dali.dianchejie.cn/Article/details/gtbsideghp.html

C#:   base.Greet();
来源：http://dali.daria6918.cn/Article/details/gtjxnjvcix.html

[G08] 静态方法与属性
来源：http://dali.xylfe.cn/Article/details/gtnuhawgoc.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.ppjwa.cn/Article/details/gtnjtzosfi.html

PHP:  public static function f() {}
来源：http://dali.guowangkeji.top/Article/details/gtklbfmoam.html

JS:   static f() {}
来源：http://dali.ydzc1.top/Article/details/gtvfuhxfqm.html

TS:   static f(): void {}
来源：http://dali.redwolf501.top/Article/details/gtxzbhyrqb.html

Java: static void f() {}
来源：http://dali.dashuyun.cn/Article/details/gtoqkpskmr.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.redwolf501.top/Article/details/gtqznmyyln.html

Ruby: def self.f; end
来源：http://dali.xuetiantiany.cn/Article/details/gtdpofyqea.html

C#:   public static void F() {}
来源：http://dali.tanke756.top/Article/details/gtojpnkled.html

[G09] 接口 / 抽象类
来源：http://dali.jqgfzy.top/Article/details/gtdomvphtc.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.shuidangran.top/Article/details/gteffudafu.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.gogol.net.cn/Article/details/gtrublgxzh.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jinghuilouyu.cn/Article/details/gtssfxyhgf.html

TS:   interface Shape { area(): number; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwgapfvpv.html

Java: interface Shape { double area(); }
来源：http://dali.ppjwa.cn/Article/details/gtdsvfknif.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.vqdsnc.cn/Article/details/gtuwpkwiei.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.daria6918.cn/Article/details/gtglsuluou.html

C#:   interface IShape { double Area(); }
来源：http://dali.quarkkingdee.top/Article/details/gthwjnsyab.html

[G10] 访问控制
来源：http://dali.ehwqpu.com/Article/details/gtwuixoxpm.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.fzhhl.top/Article/details/gtwezitnyg.html

PHP:  public / protected / private
来源：http://dali.fzhhl.top/Article/details/gtefbctdtp.html

JS:   #private 字段；其余公开
来源：http://dali.gotoacloud.top/Article/details/gtodlpfvsc.html

TS:   public / protected / private
来源：http://dali.jinqigfzy.top/Article/details/gtgjsdiyhi.html

Java: public / protected / private / 默认包级
来源：http://dali.feifeiyinyue.top/Article/details/gtnirgaeuh.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.nwbrower.top/Article/details/gtyoqablxc.html

Ruby: public / protected / private
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqyhawvkq.html

C#:   public / protected / private / internal
来源：http://dali.yvedp.cn/Article/details/gthtvjlovy.html

[G11] getter / setter
来源：http://dali.smart0.xyz/Article/details/gtxovicwbs.html

Py:   @property 与 @x.setter
来源：http://dali.xinyue.icu/Article/details/gtuushzxcq.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.smart0.xyz/Article/details/gtovhheyhs.html

JS:   get name() { return this._name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtoyfpdpml.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtriehtslj.html

Java: public String getName() { return name; }
来源：http://dali.havefunace.top/Article/details/gttriazakh.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.chenzaomai.com/Article/details/gtegzswftf.html

Ruby: attr_accessor :name
来源：http://dali.cheryme.top/Article/details/gtsuethtbp.html

C#:   public string Name { get; set; }
来源：http://dali.cucudq.cn/Article/details/gtpuhtguyr.html

[G12] 对象转字符串
来源：http://dali.cqqwz.cn/Article/details/gtyhnypize.html

Py:   def __str__(self): return self.name
来源：http://dali.zhongyouzk.top/Article/details/gtkkvrpoux.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yangfankeji.com/Article/details/gthfayfwww.html

JS:   toString() { return this.name; }
来源：http://dali.tanke756.top/Article/details/gtwfnaemya.html

TS:   toString(): string { return this.name; }
来源：http://dali.zdqjudy.top/Article/details/gtmmiqhmme.html

Java: @Override public String toString() { return name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtubsqcfwm.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhengqikj.top/Article/details/gtleipksrs.html

Ruby: def to_s; @name; end
来源：http://dali.sysykeji.top/Article/details/gtficvsrdx.html

C#:   public override string ToString() => Name;
来源：http://dali.kuanghao11.cn/Article/details/gtifhrhccx.html

[G13] 判断对象类型
来源：http://dali.ppjwa.cn/Article/details/gtdwhddqpo.html

Py:   isinstance(u, User)
来源：http://dali.cashguo.top/Article/details/gtqawjfkmv.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gtviyyqjxn.html

JS:   u instanceof User
来源：http://dali.guowangkeji.top/Article/details/gtunxewiea.html

TS:   u instanceof User
来源：http://dali.iojbl.cn/Article/details/gttaowttmq.html

Java: u instanceof User
来源：http://dali.bjfxy.top/Article/details/gtbgnjigay.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.gotoacloud.top/Article/details/gtxmxzwttc.html

Ruby: u.is_a?(User)
来源：http://dali.jinqigufen.top/Article/details/gttfctsfyz.html

C#:   u is User
来源：http://dali.tianlin.xyz/Article/details/gtolvpogwp.html

[G14] 数据类 / record
来源：http://dali.aibaodan.cn/Article/details/gtmnbqeqga.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.cashguo.top/Article/details/gtmbcpbwtz.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.daria6918.cn/Article/details/gteaetccsa.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.xuanzx.com/Article/details/gtjhpjdpdh.html

TS:   type User = { name: string; age: number };
来源：http://dali.ybcxt.top/Article/details/gttikznnsp.html

Java: record User(String name, int age) {}
来源：http://dali.jinqigufen.top/Article/details/gtiruyyzou.html

Go:   type User struct { Name string; Age int }
来源：http://dali.xuanzx.com/Article/details/gtalobxgpe.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jiagoushi.top/Article/details/gtesklyldx.html

C#:   record User(string Name, int Age);
来源：http://dali.tianlin.xyz/Article/details/gtzggcruoe.html

[G15] 枚举
来源：http://dali.gzhubu.top/Article/details/gtumytxxqg.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.pengpengdd.cyou/Article/details/gtxqmassvc.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.shuidangran.top/Article/details/gtbrxozshj.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.sysykeji.top/Article/details/gtgzlgbwoq.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sysykeji.top/Article/details/gtesznyzpa.html

Java: enum Color { RED, GREEN }
来源：http://dali.jinqigfzy.top/Article/details/gtydxdjsyp.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.redwolf501.top/Article/details/gttyxvtzpz.html

Ruby: Color = %i[red green].freeze
来源：http://dali.iojbl.cn/Article/details/gtnshpkzhs.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbdqweosa.html

[G16] 对象转数组 / 字典
来源：http://dali.hnxiangtu.top/Article/details/gtneefpbql.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.ppjwa.cn/Article/details/gtgwrdpaip.html

PHP:  get_object_vars($obj);
来源：http://dali.kuanghao11.cn/Article/details/gtyeohwoic.html

JS:   Object.entries(obj)
来源：http://dali.xinyue.icu/Article/details/gtdokobsex.html

TS:   Object.entries(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtzkgatncr.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.wangshuangyany.cn/Article/details/gtplfsmlog.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.gogol.net.cn/Article/details/gtbeqgdhmc.html

Ruby: obj.instance_variables
来源：http://dali.yonumen.top/Article/details/gtvafflzrh.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.pycfn.com/Article/details/gtbqmnpwuw.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtzoaklvph.html

H. 异常与错误处理
来源：http://dali.yuanzhike.top/Article/details/gtiojygfre.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtxslissjr.html

[H01] try / catch 基础
来源：http://dali.shuidangran.top/Article/details/gtstdouhbr.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.c1oappe.top/Article/details/gtipoocygw.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.hfpthk.cn/Article/details/gtofmohtfq.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.sysykeji.top/Article/details/gttqboavnm.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jqgufenzy.top/Article/details/gtgssdfhpx.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.shzxlz.cn/Article/details/gtpgbdtzmv.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.guannengcc.top/Article/details/gtsxxhfash.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.hysaishi.cn/Article/details/gttqvveghi.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hammf.cn/Article/details/gtlgbrbwln.html

[H02] finally / ensure 收尾
来源：http://dali.shuidangran.top/Article/details/gtwwaceszb.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.ehwqpu.com/Article/details/gtxzhvvdvn.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.gotoacloud.top/Article/details/gtaupahngf.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.nanxuanxn.top/Article/details/gtznlcumpr.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.svipenyu.cn/Article/details/gtwngxmrjb.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.xylfe.cn/Article/details/gtwxkbvfhu.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.ehwqpu.com/Article/details/gttjlklfjx.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.shangyingyoupin.top/Article/details/gtgtzeumgb.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.tianlin.xyz/Article/details/gtteirkare.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gtaamhexld.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhongyouzk.top/Article/details/gtawggllmo.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.aibaodan.cn/Article/details/gthsqpvqnm.html

JS:   throw new Error("错误信息");
来源：http://dali.yueranfly.top/Article/details/gtcoihxjdd.html

TS:   throw new Error("错误信息");
来源：http://dali.yuxming.cn/Article/details/gtcfvxruih.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.shuidangran.top/Article/details/gtbyaqwljs.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhiwuduotai.top/Article/details/gtlzkemirm.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hongshengwenyu.top/Article/details/gtltzthxfz.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtktuuhvgo.html

[H04] 自定义异常类型
来源：http://dali.tianlin.xyz/Article/details/gttzticqhn.html

Py:   class MyError(Exception): pass
来源：http://dali.jiagoushi.top/Article/details/gtdoyiwejo.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.birdmap.top/Article/details/gtkpizyufi.html

JS:   class MyError extends Error {}
来源：http://dali.hnqzz.top/Article/details/gtrqvlpsej.html

TS:   class MyError extends Error {}
来源：http://dali.pengpengdd.cyou/Article/details/gtezurclhe.html

Java: class MyException extends RuntimeException {}
来源：http://dali.kuanghao11.cn/Article/details/gtyrmomedd.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.birdmap.top/Article/details/gtiedppmpn.html

Ruby: class MyError < StandardError; end
来源：http://dali.tanke756.top/Article/details/gttvfhpaez.html

C#:   class MyException : Exception {}
来源：http://dali.cheryme.top/Article/details/gttnlgszdk.html

[H05] 捕获特定类型
来源：http://dali.andypj.xyz/Article/details/gthzzwzpxa.html

Py:   except ValueError as e:
来源：http://dali.hfpthk.cn/Article/details/gtpyrosuek.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.sysykeji.top/Article/details/gtsgnialca.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.cashguo.top/Article/details/gtjxcpogst.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtsdhryyhm.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhijiandao.cn/Article/details/gtfiuthced.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.pengpengdd.cyou/Article/details/gtutaphkfb.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhijiandao.cn/Article/details/gthrtefbzv.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gtsalcqkhm.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yj20258888.top/Article/details/gtogjsocam.html

Py:   value = d.get("k") or default
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaktcaumb.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.gzhubu.top/Article/details/gtrmnypucl.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.mhx1999.top/Article/details/gtgcuqsdna.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.shanyushiyangtech.top/Article/details/gtatdonxgu.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.gzhubu.top/Article/details/gtnogzskze.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jianghu66.top/Article/details/gttwogmnhv.html

Ruby: d&.dig(:a, :b)
来源：http://dali.sysykeji.top/Article/details/gtejpzahcv.html

C#:   obj?.A?.B ?? default
来源：http://dali.jinqigfzy.top/Article/details/gtjytanegn.html

[H07] 断言
来源：http://dali.sysykeji.top/Article/details/gtvruylerz.html

Py:   assert x > 0, "必须为正"
来源：http://dali.feifeiyinyue.top/Article/details/gtwegofmpv.html

PHP:  assert($x > 0);
来源：http://dali.sxryk.cn/Article/details/gtwcgcmyuc.html

JS:   console.assert(x > 0);
来源：http://dali.xuanzx.com/Article/details/gthmfvcbmb.html

TS:   console.assert(x > 0);
来源：http://dali.jqgfzy.top/Article/details/gtlsqslnjx.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yj20258.top/Article/details/gtibipqwrl.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.shuidangran.top/Article/details/gtuvxbetrk.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.c1oappe.top/Article/details/gtlyshadrj.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zycfv.cn/Article/details/gtsfhkgwzx.html

[H08] 获取错误信息与堆栈
来源：http://dali.tianlin.xyz/Article/details/gtlassqrzd.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.mhx1999.top/Article/details/gtposnkyan.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.redwolf501.top/Article/details/gtcpcjouva.html

JS:   e.message;  e.stack
来源：http://dali.cheryme.top/Article/details/gtkyyixque.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.mhx1999.top/Article/details/gtqcmxenvu.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.havefunace.top/Article/details/gttmgucexf.html

Go:   err.Error()
来源：http://dali.zhixingplan.top/Article/details/gtbenyzjic.html


<!-- 参考信息 -->