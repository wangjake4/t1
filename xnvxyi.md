代发 wailian999

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.xinyue.icu/Article/details/gteigrulgp.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jqgufenzy.top/Article/details/gtunmpzsgi.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.andypj.xyz/Article/details/gtsydhoqhx.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhoulong.xyz/Article/details/gttwspavob.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jianghu66.top/Article/details/gtdlwmonva.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.0kj1m.cn/Article/details/gtzehwnvar.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.meibo888.top/Article/details/gtjqzgfwtb.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.fzhhl.top/Article/details/gtxsckrzgu.html

[F05] 判断文件或目录是否存在
来源：http://dali.havefunace.top/Article/details/gtylbaothn.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.c1oappe.top/Article/details/gtdhjoypev.html

PHP:  file_exists("a.txt");
来源：http://dali.jianghu66.top/Article/details/gtaujraqxk.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtvjlyvuht.html

TS:   fs.existsSync("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtdezubyyz.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.snrcjt.cn/Article/details/gtmpplbvlo.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.shuidangran.top/Article/details/gtwcdoyypq.html

Ruby: File.exist?("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtgugsxxmz.html

C#:   File.Exists("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gthojzqotk.html

[F06] 删除文件
来源：http://dali.tianlin.xyz/Article/details/gtwzzdmsbk.html

Py:   os.remove("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtpnywwpcy.html

PHP:  unlink("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gtgijvmhkm.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.ydzc1.top/Article/details/gtvopludey.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtuoxdpzdx.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.316326.xyz/Article/details/gtfbdsjvnb.html

Go:   os.Remove("a.txt")
来源：http://dali.sweek.top/Article/details/gtfwhrqsjb.html

Ruby: File.delete("a.txt")
来源：http://dali.cashguo.top/Article/details/gtpefrigcu.html

C#:   File.Delete("a.txt");
来源：http://dali.cdnleiting.top/Article/details/gtpuafvpki.html

[F07] 创建目录（含多级）
来源：http://dali.gaohongyu789.top/Article/details/gtwruhbnvg.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.gogol.net.cn/Article/details/gtpgvcqrfe.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.ivvv.top/Article/details/gtjkgcvigh.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cdnleiting.top/Article/details/gtpinjqnpl.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.haohaochexian.top/Article/details/gtiioyxzme.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.shangyingyoupin.top/Article/details/gtdszyswtb.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.andypj.xyz/Article/details/gtrcenzqaz.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jinqigfzy.top/Article/details/gtlyrgjgqg.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.snrcjt.cn/Article/details/gtncpddesl.html

[F08] 遍历目录
来源：http://dali.fengsongda.top/Article/details/gtsqtrjhlj.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.dashuyun.cn/Article/details/gtwdzjlyly.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.gaohongyu789.top/Article/details/gtzujhimmx.html

JS:   fs.readdirSync("dir")
来源：http://dali.shuidangran.top/Article/details/gthuhtjjls.html

TS:   fs.readdirSync("dir")
来源：http://dali.9152youxi.cn/Article/details/gtuqhpsqqf.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.nwbrower.top/Article/details/gtagkhmcuv.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.sweek.top/Article/details/gtxclydbls.html

Ruby: Dir.children("dir")
来源：http://dali.birdmap.top/Article/details/gtilcnnydy.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yueranfly.top/Article/details/gtclfyeqmi.html

[F09] 获取文件大小
来源：http://dali.daria6918.cn/Article/details/gtyykpgeyj.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtvkzsblwl.html

PHP:  filesize("a.txt");
来源：http://dali.sysykeji.top/Article/details/gtcnjfdqem.html

JS:   fs.statSync("a.txt").size
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttusaqljt.html

TS:   fs.statSync("a.txt").size
来源：http://dali.shangyingyoupin.top/Article/details/gtuemxwzwy.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yanxiufei.cn/Article/details/gtunrsarlp.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yj20258888.top/Article/details/gtomipmkxe.html

Ruby: File.size("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtfueflqhd.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jlsjyb.cn/Article/details/gtxepjkawu.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.cashguo.top/Article/details/gtvlwilrty.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.shuidangran.top/Article/details/gtawqjypts.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jianghu66.top/Article/details/gtmmvrhjny.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.cashguo.top/Article/details/gtzjaizaaa.html

TS:   path.extname("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtvpigjhew.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.guannengcc.top/Article/details/gtywklnlkk.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yonumen.top/Article/details/gtzjaoeqed.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.pycfn.com/Article/details/gtaollpaar.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtmadqfcsi.html

[F11] 复制与移动文件
来源：http://dali.guowangkeji.top/Article/details/gtvmwsqycd.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.ivvv.top/Article/details/gtumhnuvok.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhoulong.xyz/Article/details/gtpjabrmlv.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtywcbabuq.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtucloxeie.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.316326.xyz/Article/details/gtrjmnlvkz.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.pycfn.com/Article/details/gtpqwxwkib.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.shuidangran.top/Article/details/gtrjksocle.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.hongshengwenyu.top/Article/details/gttaowkulg.html

[F12] CSV 读写
来源：http://dali.cdnleiting.top/Article/details/gtotrjspsi.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.shuidangran.top/Article/details/gtrhxrhhdq.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.ybcxt.top/Article/details/gtpsmpqwjs.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.sweek.top/Article/details/gtaxjwaqwl.html

TS:   // 同上
来源：http://dali.zhengqikj.top/Article/details/gtqzesbxpj.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.xinyue.icu/Article/details/gtxlegjbjw.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hongshengwenyu.top/Article/details/gtzolwskso.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yangfankeji.com/Article/details/gtoesatdlp.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhongyouzk.top/Article/details/gtoqzfpuhi.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtcuemfsfd.html

G. 面向对象
来源：http://dali.wangshuangyany.cn/Article/details/gtvksvpvfy.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtpkefeeym.html

[G01] 定义类
来源：http://dali.sxryk.cn/Article/details/gtblzwbrse.html

Py:   class User: pass
来源：http://dali.yangfankeji.com/Article/details/gtqgelydyp.html

PHP:  class User {}
来源：http://dali.wangshuangyany.cn/Article/details/gtywnggrvj.html

JS:   class User {}
来源：http://dali.vqdsnc.cn/Article/details/gtywbtrsqs.html

TS:   class User { name: string = ""; }
来源：http://dali.vqdsnc.cn/Article/details/gthjtqpgoq.html

Java: class User {}
来源：http://dali.gotoacloud.top/Article/details/gtuqeepsjm.html

Go:   type User struct { Name string }
来源：http://dali.yangfankeji.com/Article/details/gtsxvsdgpk.html

Ruby: class User; end
来源：http://dali.yj20258.top/Article/details/gtzwhewaqp.html

C#:   class User {}
来源：http://dali.meibo888.top/Article/details/gtaurwlhqy.html

[G02] 构造函数
来源：http://dali.jqgufenzy.top/Article/details/gtdgydzzcy.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jianghu66.top/Article/details/gthqpmaxte.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gttdzurkyg.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.vqdsnc.cn/Article/details/gtnanjojos.html

TS:   constructor(public name: string) {}
来源：http://dali.shuidangran.top/Article/details/gtapowmhka.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhengqikj.top/Article/details/gtbclrojtc.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.sysykeji.top/Article/details/gtgpqrmjvu.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxvfhsrue.html

C#:   public User(string name) { Name = name; }
来源：http://dali.sxryk.cn/Article/details/gtumpafprq.html

[G03] 实例属性
来源：http://dali.xinyue.icu/Article/details/gtextktbjf.html

Py:   self.name = "x"
来源：http://dali.mhx1999.top/Article/details/gtsgmzavke.html

PHP:  public string $name = "x";
来源：http://dali.cdnleiting.top/Article/details/gtckpafyea.html

JS:   this.name = "x";
来源：http://dali.316326.xyz/Article/details/gtpffkkoyl.html

TS:   name: string = "x";
来源：http://dali.jinqigufen.top/Article/details/gtwrwtnkvg.html

Java: private String name;
来源：http://dali.gaohongyu789.top/Article/details/gtzsvodtuz.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.feifeiyinyue.top/Article/details/gturuxcrfu.html

Ruby: @name = "x"
来源：http://dali.haohaochexian.top/Article/details/gtgsjpxnnl.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.hysaishi.cn/Article/details/gtmmemdtpu.html

[G04] 定义方法
来源：http://dali.tianlin.xyz/Article/details/gteuswzhts.html

Py:   def greet(self): return self.name
来源：http://dali.andypj.xyz/Article/details/gtntanqcxh.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtvaeaxsbm.html

JS:   greet() { return this.name; }
来源：http://dali.cashguo.top/Article/details/gtevswlquj.html

TS:   greet(): string { return this.name; }
来源：http://dali.ydzc1.top/Article/details/gtzzgvtqpn.html

Java: String greet() { return name; }
来源：http://dali.andypj.xyz/Article/details/gtjzeiippt.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.xylfe.cn/Article/details/gtqqfqzabp.html

Ruby: def greet; @name; end
来源：http://dali.tanke756.top/Article/details/gtroeuidqj.html

C#:   public string Greet() => Name;
来源：http://dali.fengsongda.top/Article/details/gtyuyggnau.html

[G05] 继承
来源：http://dali.dashuyun.cn/Article/details/gtsihmkjae.html

Py:   class Admin(User): pass
来源：http://dali.jqgufenzy.top/Article/details/gthubyjtfw.html

PHP:  class Admin extends User {}
来源：http://dali.zhixingplan.top/Article/details/gtdeahcpin.html

JS:   class Admin extends User {}
来源：http://dali.smart0.xyz/Article/details/gtwwkpttrc.html

TS:   class Admin extends User {}
来源：http://dali.feifeiyinyue.top/Article/details/gtkwtwjddj.html

Java: class Admin extends User {}
来源：http://dali.zhoulong.xyz/Article/details/gtwvoylxhb.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.cdnleiting.top/Article/details/gtoezobcjs.html

Ruby: class Admin < User; end
来源：http://dali.cqqwz.cn/Article/details/gtcldrbcro.html

C#:   class Admin : User {}
来源：http://dali.yueranfly.top/Article/details/gtjsucgwul.html

[G06] 重写方法
来源：http://dali.chenjidiqi.icu/Article/details/gtyjpdfkvd.html

Py:   def greet(self): return "admin"
来源：http://dali.fengsongda.top/Article/details/gtlyyksjge.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.pycfn.com/Article/details/gtqyrkhiiy.html

JS:   greet() { return "admin"; }
来源：http://dali.9152youxi.cn/Article/details/gtpevenxdk.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hammf.cn/Article/details/gtpwxlbazq.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.aizwys.cn/Article/details/gtjypivydd.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.tanke756.top/Article/details/gtgknvfmmh.html

Ruby: def greet; "admin"; end
来源：http://dali.vqdsnc.cn/Article/details/gtwjqdgyeh.html

C#:   public override string Greet() => "admin";
来源：http://dali.sysykeji.top/Article/details/gtubkjlaok.html

[G07] 调用父类方法
来源：http://dali.yj202588.top/Article/details/gtvzgtjxcj.html

Py:   super().greet()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthdrwrzog.html

PHP:  parent::greet();
来源：http://dali.kuanghao11.cn/Article/details/gtmqlrlbli.html

JS:   super.greet();
来源：http://dali.iojbl.cn/Article/details/gtadwtauja.html

TS:   super.greet();
来源：http://dali.sweek.top/Article/details/gtzmeynnnr.html

Java: super.greet();
来源：http://dali.andypj.xyz/Article/details/gtgovaucna.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhaomingkeji.xyz/Article/details/gttznqbmml.html

Ruby: super
来源：http://dali.tian-w.cn/Article/details/gtqjjvexvu.html

C#:   base.Greet();
来源：http://dali.yongpay.top/Article/details/gtptipouod.html

[G08] 静态方法与属性
来源：http://dali.hnqzz.top/Article/details/gtmpwojxvw.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.nanxinkj.top/Article/details/gtoofctwrp.html

PHP:  public static function f() {}
来源：http://dali.chenlongwang.top/Article/details/gtpxawnvwx.html

JS:   static f() {}
来源：http://dali.hnqzz.top/Article/details/gtbtceipht.html

TS:   static f(): void {}
来源：http://dali.yvedp.cn/Article/details/gtmmeqdzro.html

Java: static void f() {}
来源：http://dali.yj202588.top/Article/details/gtrrdvunua.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.fengsongda.top/Article/details/gtpsdvnqyc.html

Ruby: def self.f; end
来源：http://dali.havefunace.top/Article/details/gtefeznsqt.html

C#:   public static void F() {}
来源：http://dali.snrcjt.cn/Article/details/gtmtfygfum.html

[G09] 接口 / 抽象类
来源：http://dali.yongpay.top/Article/details/gthqxryqgr.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.dashuyun.cn/Article/details/gtvdazrekt.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jinghuilouyu.cn/Article/details/gttkyiertv.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.nanxinkj.top/Article/details/gttxlaxpax.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhixingplan.top/Article/details/gtegkfewma.html

Java: interface Shape { double area(); }
来源：http://dali.yangfankeji.com/Article/details/gtafxfbtoh.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.chenlongwang.top/Article/details/gtlbmqpjbx.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.cashguo.top/Article/details/gtisoxfvcu.html

C#:   interface IShape { double Area(); }
来源：http://dali.aizwys.cn/Article/details/gtegnownrq.html

[G10] 访问控制
来源：http://dali.jianghu66.top/Article/details/gtqyqiufzb.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.dianchejie.cn/Article/details/gtzmlneark.html

PHP:  public / protected / private
来源：http://dali.redwolf501.top/Article/details/gtsyiuxnee.html

JS:   #private 字段；其余公开
来源：http://dali.xuanzx.com/Article/details/gtdbpkgyca.html

TS:   public / protected / private
来源：http://dali.xinyue.icu/Article/details/gtijwhgwxe.html

Java: public / protected / private / 默认包级
来源：http://dali.sxryk.cn/Article/details/gtzyjsuodi.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpvawpjea.html

Ruby: public / protected / private
来源：http://dali.zdqjudy.top/Article/details/gtowufpeoh.html

C#:   public / protected / private / internal
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxognbnsu.html

[G11] getter / setter
来源：http://dali.316326.xyz/Article/details/gtstggoast.html

Py:   @property 与 @x.setter
来源：http://dali.yj20258.top/Article/details/gtzwmcjkza.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.hywenlv.cn/Article/details/gtyqnsuikg.html

JS:   get name() { return this._name; }
来源：http://dali.0kj1m.cn/Article/details/gtnerrowgb.html

TS:   get name(): string { return this._name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtewefngzp.html

Java: public String getName() { return name; }
来源：http://dali.shuidangran.top/Article/details/gtrkwlxwmk.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.hfpthk.cn/Article/details/gteokbjjne.html

Ruby: attr_accessor :name
来源：http://dali.svipenyu.cn/Article/details/gtrsyvifnc.html

C#:   public string Name { get; set; }
来源：http://dali.sweek.top/Article/details/gtcxxrxmlt.html

[G12] 对象转字符串
来源：http://dali.cucudq.cn/Article/details/gtxiynhnui.html

Py:   def __str__(self): return self.name
来源：http://dali.nanxuanxn.top/Article/details/gtbzouopye.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jyoumei.cn/Article/details/gtjmlnznlj.html

JS:   toString() { return this.name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtgnwdrilz.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhongyouzk.top/Article/details/gtteustvqt.html

Java: @Override public String toString() { return name; }
来源：http://dali.yueranfly.top/Article/details/gtjfvstpww.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.mhx1999.top/Article/details/gtllrjbtan.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gteaahffau.html

C#:   public override string ToString() => Name;
来源：http://dali.tian-w.cn/Article/details/gtlqpcaydx.html

[G13] 判断对象类型
来源：http://dali.xylfe.cn/Article/details/gtgyqyxbnd.html

Py:   isinstance(u, User)
来源：http://dali.chenzaomai.com/Article/details/gtkykkvdtq.html

PHP:  $u instanceof User
来源：http://dali.yangfankeji.com/Article/details/gtjrslqjzr.html

JS:   u instanceof User
来源：http://dali.meibo888.top/Article/details/gtvhoiylcx.html

TS:   u instanceof User
来源：http://dali.hfpthk.cn/Article/details/gtpdcnmrux.html

Java: u instanceof User
来源：http://dali.fzhhl.top/Article/details/gtbgjrjgoh.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.nanxuanxn.top/Article/details/gtlcgdfpph.html

Ruby: u.is_a?(User)
来源：http://dali.jinghuilouyu.cn/Article/details/gtacokfvnb.html

C#:   u is User
来源：http://dali.yanxiufei.cn/Article/details/gtzujjpvjf.html

[G14] 数据类 / record
来源：http://dali.pengpengdd.cyou/Article/details/gtvrbwkrko.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.hfpthk.cn/Article/details/gtcxxvpsus.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jinghuilouyu.cn/Article/details/gtpdomafyz.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.xylfe.cn/Article/details/gtlewjadhc.html

TS:   type User = { name: string; age: number };
来源：http://dali.hysaishi.cn/Article/details/gtinnrntcd.html

Java: record User(String name, int age) {}
来源：http://dali.hywenlv.cn/Article/details/gtvmznwrxp.html

Go:   type User struct { Name string; Age int }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnmycpkle.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.gotoacloud.top/Article/details/gtbmufzdvp.html

C#:   record User(string Name, int Age);
来源：http://dali.feifeiyinyue.top/Article/details/gtpuxrysvg.html

[G15] 枚举
来源：http://dali.nwbrower.top/Article/details/gtqegmqitd.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.cheryme.top/Article/details/gtqnwadhhc.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.fzhhl.top/Article/details/gtmeylkvns.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yonumen.top/Article/details/gtfyyxbooc.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.chenlongwang.top/Article/details/gthvkynarw.html

Java: enum Color { RED, GREEN }
来源：http://dali.sysykeji.top/Article/details/gtioqfjzqq.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.shuidangran.top/Article/details/gteazuvodx.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yongpay.top/Article/details/gtefvevpuc.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cashguo.top/Article/details/gtejzxsvqc.html

[G16] 对象转数组 / 字典
来源：http://dali.shangyingyoupin.top/Article/details/gtjfdrtzoz.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.hysaishi.cn/Article/details/gtykxbipco.html

PHP:  get_object_vars($obj);
来源：http://dali.hnqzz.top/Article/details/gtiinnkdxk.html

JS:   Object.entries(obj)
来源：http://dali.hfpthk.cn/Article/details/gtaxbyfpjv.html

TS:   Object.entries(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtspgauoxt.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.shzxlz.cn/Article/details/gtkungcgkg.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhoulong.xyz/Article/details/gtuajzkklw.html

Ruby: obj.instance_variables
来源：http://dali.shzxlz.cn/Article/details/gtadilohif.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.shanyushiyangtech.top/Article/details/gtcceddacs.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtbeklpxnz.html

H. 异常与错误处理
来源：http://dali.zhengqikj.top/Article/details/gtetsuscfc.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtsifgiitl.html

[H01] try / catch 基础
来源：http://dali.jianghu66.top/Article/details/gtjjidzhtf.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhongyouzk.top/Article/details/gtxcgyzqar.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.xuanzx.com/Article/details/gtsxssywqf.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.316326.xyz/Article/details/gtikqdwuko.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.gzhubu.top/Article/details/gtyoosxpbd.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.redwolf501.top/Article/details/gtofepricn.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.wangshuangyany.cn/Article/details/gtegljrhvj.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.cheryme.top/Article/details/gtsgfmffzk.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yj20258888.top/Article/details/gtnuztvapp.html

[H02] finally / ensure 收尾
来源：http://dali.yangfankeji.com/Article/details/gtazxssvbc.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.shanyushiyangtech.top/Article/details/gtgdzsgtwo.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jinqigfzy.top/Article/details/gtjjchhzpx.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.feifeiyinyue.top/Article/details/gtblrkmpji.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.chenzaomai.com/Article/details/gtnttxftco.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.fengsongda.top/Article/details/gtrzagzhtj.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jlsjyb.cn/Article/details/gtsfznxalt.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.nwbrower.top/Article/details/gtwrsehpwu.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.cdnleiting.top/Article/details/gtdutvoinv.html

[H03] 主动抛出异常
来源：http://dali.tianlin.xyz/Article/details/gtiwlkcrwo.html

Py:   raise ValueError("错误信息")
来源：http://dali.zycfv.cn/Article/details/gtiozhkndc.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.fzhhl.top/Article/details/gtpyqeqkqr.html

JS:   throw new Error("错误信息");
来源：http://dali.xziqi.cn/Article/details/gtwfgwsuwy.html

TS:   throw new Error("错误信息");
来源：http://dali.sufxvd.cn/Article/details/gtnxxksgju.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.cdnleiting.top/Article/details/gtcrsdiloe.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.xuanzx.com/Article/details/gtvoxhrdao.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.aizwys.cn/Article/details/gtrfggbqgh.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.aibaodan.cn/Article/details/gtmincnfmw.html

[H04] 自定义异常类型
来源：http://dali.xinyue.icu/Article/details/gtqykfvdje.html

Py:   class MyError(Exception): pass
来源：http://dali.zhixingplan.top/Article/details/gtablbgztk.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.smart0.xyz/Article/details/gtnpxasvhx.html

JS:   class MyError extends Error {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlsxnzdjo.html

TS:   class MyError extends Error {}
来源：http://dali.chenzaomai.com/Article/details/gthhmmphhj.html

Java: class MyException extends RuntimeException {}
来源：http://dali.cashguo.top/Article/details/gtmwgbfdiz.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhijiandao.cn/Article/details/gttqtblgmp.html

Ruby: class MyError < StandardError; end
来源：http://dali.snrcjt.cn/Article/details/gteytwkvnl.html

C#:   class MyException : Exception {}
来源：http://dali.aizwys.cn/Article/details/gteofvaibk.html

[H05] 捕获特定类型
来源：http://dali.jinqigfzy.top/Article/details/gtbhxmuqzm.html

Py:   except ValueError as e:
来源：http://dali.shzxlz.cn/Article/details/gtbyarkhhe.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yanxiufei.cn/Article/details/gtonazsgok.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.dashuyun.cn/Article/details/gtjurhzbpb.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.daxiang520.top/Article/details/gthtymhqor.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.cqqwz.cn/Article/details/gtbvjuqqia.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrspsppih.html

Ruby: rescue ArgumentError => e
来源：http://dali.nwbrower.top/Article/details/gtifcrdubv.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hnxiangtu.top/Article/details/gtprrszfow.html

[H06] 可选值 / 空值安全访问
来源：http://dali.gotoacloud.top/Article/details/gtzmvafhtn.html

Py:   value = d.get("k") or default
来源：http://dali.vqdsnc.cn/Article/details/gthdeapswl.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.xinyue.icu/Article/details/gtbzbdtpnb.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.cqqwz.cn/Article/details/gtbelnsgbf.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yonumen.top/Article/details/gtesbhtzwr.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.hnxiangtu.top/Article/details/gtsxtfmrwy.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.xziqi.cn/Article/details/gtguvuoeeb.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yanxiufei.cn/Article/details/gtprsmhudz.html

C#:   obj?.A?.B ?? default
来源：http://dali.yonumen.top/Article/details/gtvnyoakur.html

[H07] 断言
来源：http://dali.wangshuangyany.cn/Article/details/gtssglyocj.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhoulong.xyz/Article/details/gtmctczgcf.html

PHP:  assert($x > 0);
来源：http://dali.tian-w.cn/Article/details/gthclvrlko.html

JS:   console.assert(x > 0);
来源：http://dali.jqgufenzy.top/Article/details/gtahnwowko.html

TS:   console.assert(x > 0);
来源：http://dali.aizwys.cn/Article/details/gtiamogsii.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jlsjyb.cn/Article/details/gthyjljpwd.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.ivvv.top/Article/details/gtuqthkelm.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yj202588.top/Article/details/gtrdyacpah.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jianghu66.top/Article/details/gtacthbtzq.html

[H08] 获取错误信息与堆栈
来源：http://dali.hywenlv.cn/Article/details/gtytfguucg.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.andypj.xyz/Article/details/gtxbotrwht.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.fzhhl.top/Article/details/gtwhefmlff.html

JS:   e.message;  e.stack
来源：http://dali.sufxvd.cn/Article/details/gtyuonxnaj.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yangfankeji.com/Article/details/gttfnhnjji.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.fzhhl.top/Article/details/gtyjitvoya.html

Go:   err.Error()
来源：http://dali.smart0.xyz/Article/details/gtonknxmfu.html


<!-- 参考信息 -->