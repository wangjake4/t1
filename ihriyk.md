代发 wailian999

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.quarkkingdee.top/Article/details/gtpfmtuiyf.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.nanxinkj.top/Article/details/gtejzznjgg.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yuanzhike.top/Article/details/gtdeyzwqpm.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdplgoumg.html

[F05] 判断文件或目录是否存在
来源：http://dali.0kj1m.cn/Article/details/gtsruubkej.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.cqqwz.cn/Article/details/gtxgoorgnx.html

PHP:  file_exists("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gtlyobpzdf.html

JS:   fs.existsSync("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtfxykmyxi.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gthiloqznu.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zycfv.cn/Article/details/gtzgbghpsl.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jqgufenzy.top/Article/details/gtjejofzgr.html

Ruby: File.exist?("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtraxexdkr.html

C#:   File.Exists("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyrftxvha.html

[F06] 删除文件
来源：http://dali.snrcjt.cn/Article/details/gtdcxtjrtk.html

Py:   os.remove("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtovavjnby.html

PHP:  unlink("a.txt");
来源：http://dali.bjfxy.top/Article/details/gtusiuvdzc.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtedknxbsu.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.tanke756.top/Article/details/gtzknverxb.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.wangshuangyany.cn/Article/details/gtkcjxnuur.html

Go:   os.Remove("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtpfmzxngz.html

Ruby: File.delete("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtgonohcuv.html

C#:   File.Delete("a.txt");
来源：http://dali.yangfankeji.com/Article/details/gtdwbombti.html

[F07] 创建目录（含多级）
来源：http://dali.0kj1m.cn/Article/details/gtdjomnheb.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.pengpengdd.cyou/Article/details/gtprsdcjlv.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.wangshuangyany.cn/Article/details/gtahtqpoez.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.haohaochexian.top/Article/details/gtxeomplmq.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.tanke756.top/Article/details/gtqiukpopn.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.dianchejie.cn/Article/details/gtxdgcjqgz.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yj202588.top/Article/details/gtkroitcdc.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.dashuyun.cn/Article/details/gtahtmhrdd.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.hywenlv.cn/Article/details/gtapznhbpf.html

[F08] 遍历目录
来源：http://dali.hammf.cn/Article/details/gtrbvptqbo.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.dashuyun.cn/Article/details/gtwnqjesol.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.hysaishi.cn/Article/details/gtfhatspxk.html

JS:   fs.readdirSync("dir")
来源：http://dali.wangshuangyany.cn/Article/details/gtnczdrizp.html

TS:   fs.readdirSync("dir")
来源：http://dali.birdmap.top/Article/details/gtstqhahva.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gthotbizgi.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yuanzhike.top/Article/details/gtiqevuxky.html

Ruby: Dir.children("dir")
来源：http://dali.hongshengwenyu.top/Article/details/gtyemmatqn.html

C#:   Directory.GetFiles("dir")
来源：http://dali.xuetiantiany.cn/Article/details/gtppmnxafq.html

[F09] 获取文件大小
来源：http://dali.zdqjudy.top/Article/details/gtrhrdxdib.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtrufkihfc.html

PHP:  filesize("a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gtxocnfbgr.html

JS:   fs.statSync("a.txt").size
来源：http://dali.nanxuanxn.top/Article/details/gtrygpuyes.html

TS:   fs.statSync("a.txt").size
来源：http://dali.nanxinkj.top/Article/details/gtvnlrejrj.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.dianchejie.cn/Article/details/gtdrdayikd.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.fengsongda.top/Article/details/gtllagubet.html

Ruby: File.size("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtosratpvy.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.fzhhl.top/Article/details/gtwnzaayrr.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhixingplan.top/Article/details/gtiucrganx.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.hammf.cn/Article/details/gtsjcvesqv.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yueranfly.top/Article/details/gtbgledqct.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtujawztsx.html

TS:   path.extname("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtwhqupten.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqnmzomhx.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.ivvv.top/Article/details/gtkrubypjp.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.wangdashe.top/Article/details/gtddwwkrhd.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtffmadtoi.html

[F11] 复制与移动文件
来源：http://dali.xuanzx.com/Article/details/gtbefxsjdd.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.fzhhl.top/Article/details/gtclgpzvbn.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.aibaodan.cn/Article/details/gthkpapbas.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.chenlongwang.top/Article/details/gtkfvqwrcq.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvyfswqzi.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.hfpthk.cn/Article/details/gtgcpcsstn.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.shuidangran.top/Article/details/gtjmabimsb.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.cucudq.cn/Article/details/gtqwvrxlgc.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.hfpthk.cn/Article/details/gtlklnldgz.html

[F12] CSV 读写
来源：http://dali.sweek.top/Article/details/gtlqvnhuow.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.pengpengdd.cyou/Article/details/gtwcccjlnj.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.kuanghao11.cn/Article/details/gtmidjhmua.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yangfankeji.com/Article/details/gtitfblfzl.html

TS:   // 同上
来源：http://dali.jinqigfzy.top/Article/details/gtaukzopfd.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.mhx1999.top/Article/details/gtucjqqduo.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.iojbl.cn/Article/details/gteqiduddj.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zycfv.cn/Article/details/gtcjtzlwuj.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yanxiufei.cn/Article/details/gtvpfetyob.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtsttocuiq.html

G. 面向对象
来源：http://dali.aizwys.cn/Article/details/gtlzyceemv.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtkmpoefmw.html

[G01] 定义类
来源：http://dali.ppjwa.cn/Article/details/gtthkjzaqv.html

Py:   class User: pass
来源：http://dali.yonumen.top/Article/details/gtpzhzhhzb.html

PHP:  class User {}
来源：http://dali.aizwys.cn/Article/details/gtpzfocvve.html

JS:   class User {}
来源：http://dali.sxryk.cn/Article/details/gtzcoeuaqd.html

TS:   class User { name: string = ""; }
来源：http://dali.vqdsnc.cn/Article/details/gteynwptpl.html

Java: class User {}
来源：http://dali.hongshengwenyu.top/Article/details/gtpasnyjfw.html

Go:   type User struct { Name string }
来源：http://dali.cqqwz.cn/Article/details/gtnovhjrxa.html

Ruby: class User; end
来源：http://dali.yongpay.top/Article/details/gtwknunwjs.html

C#:   class User {}
来源：http://dali.fengsongda.top/Article/details/gtutniatux.html

[G02] 构造函数
来源：http://dali.xziqi.cn/Article/details/gtyrumsjkr.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.sufxvd.cn/Article/details/gtgrnveinv.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jianghu66.top/Article/details/gtluuznodg.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.shzxlz.cn/Article/details/gtbtfnxjiu.html

TS:   constructor(public name: string) {}
来源：http://dali.yj202588.top/Article/details/gtfbmbmdjy.html

Java: User(String name) { this.name = name; }
来源：http://dali.bjfxy.top/Article/details/gtpayfudbi.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.sysykeji.top/Article/details/gtusdvocue.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwxpyffta.html

C#:   public User(string name) { Name = name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtohgbggth.html

[G03] 实例属性
来源：http://dali.nwbrower.top/Article/details/gtfibzzuch.html

Py:   self.name = "x"
来源：http://dali.birdmap.top/Article/details/gtpwuyzjzy.html

PHP:  public string $name = "x";
来源：http://dali.cqqwz.cn/Article/details/gtzorqepgq.html

JS:   this.name = "x";
来源：http://dali.tanke756.top/Article/details/gtfrkvvlet.html

TS:   name: string = "x";
来源：http://dali.meibo888.top/Article/details/gtxvecxmxc.html

Java: private String name;
来源：http://dali.ivvv.top/Article/details/gtxumxwudr.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hnqzz.top/Article/details/gteugailhf.html

Ruby: @name = "x"
来源：http://dali.jinghuilouyu.cn/Article/details/gtbvynaoci.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.haohaochexian.top/Article/details/gtpvgawvhe.html

[G04] 定义方法
来源：http://dali.guannengcc.top/Article/details/gtfvitdizw.html

Py:   def greet(self): return self.name
来源：http://dali.andypj.xyz/Article/details/gtltnkfxho.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hysaishi.cn/Article/details/gtuwagjogn.html

JS:   greet() { return this.name; }
来源：http://dali.redwolf501.top/Article/details/gtvlvogpwy.html

TS:   greet(): string { return this.name; }
来源：http://dali.yueranfly.top/Article/details/gtqxkycbch.html

Java: String greet() { return name; }
来源：http://dali.yvedp.cn/Article/details/gtzsrynqbe.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.snrcjt.cn/Article/details/gtujsgqpnu.html

Ruby: def greet; @name; end
来源：http://dali.yueranfly.top/Article/details/gtpxceommn.html

C#:   public string Greet() => Name;
来源：http://dali.zhongyouzk.top/Article/details/gtmcjibeyv.html

[G05] 继承
来源：http://dali.shanyushiyangkeji.top/Article/details/gtotrgxcan.html

Py:   class Admin(User): pass
来源：http://dali.tanke756.top/Article/details/gtkxqnwxwu.html

PHP:  class Admin extends User {}
来源：http://dali.zhongyouzk.top/Article/details/gtjxproicb.html

JS:   class Admin extends User {}
来源：http://dali.316326.xyz/Article/details/gtevlohdsl.html

TS:   class Admin extends User {}
来源：http://dali.svipenyu.cn/Article/details/gtcxzrqvnk.html

Java: class Admin extends User {}
来源：http://dali.yuanzhike.top/Article/details/gthglvptks.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.shzxlz.cn/Article/details/gtszfwhwnl.html

Ruby: class Admin < User; end
来源：http://dali.hammf.cn/Article/details/gtjdpwufph.html

C#:   class Admin : User {}
来源：http://dali.bjfxy.top/Article/details/gtbsihnlql.html

[G06] 重写方法
来源：http://dali.jinqigfzy.top/Article/details/gtadcvgywz.html

Py:   def greet(self): return "admin"
来源：http://dali.ydzc1.top/Article/details/gtvjsnocss.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.dianchejie.cn/Article/details/gtibxferls.html

JS:   greet() { return "admin"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtkzuashuq.html

TS:   greet(): string { return "admin"; }
来源：http://dali.daxiang520.top/Article/details/gtkwpveluv.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.tianlin.xyz/Article/details/gtfemvvegy.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.nanxinkj.top/Article/details/gtxrvkmjju.html

Ruby: def greet; "admin"; end
来源：http://dali.cashguo.top/Article/details/gtcbffnelc.html

C#:   public override string Greet() => "admin";
来源：http://dali.sysykeji.top/Article/details/gtqxkbhiyk.html

[G07] 调用父类方法
来源：http://dali.vqdsnc.cn/Article/details/gtecsyfats.html

Py:   super().greet()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmfgysons.html

PHP:  parent::greet();
来源：http://dali.nwbrower.top/Article/details/gtkbnairow.html

JS:   super.greet();
来源：http://dali.9152youxi.cn/Article/details/gtpcldvnrs.html

TS:   super.greet();
来源：http://dali.jinqigfzy.top/Article/details/gtbzvgbilc.html

Java: super.greet();
来源：http://dali.snrcjt.cn/Article/details/gtieoumisk.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.shanyushiyangtech.top/Article/details/gtkauujmzn.html

Ruby: super
来源：http://dali.daxiang520.top/Article/details/gtzhifhzml.html

C#:   base.Greet();
来源：http://dali.tianlin.xyz/Article/details/gtybtychgj.html

[G08] 静态方法与属性
来源：http://dali.cashguo.top/Article/details/gtyamjaoue.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgiwecmau.html

PHP:  public static function f() {}
来源：http://dali.chenjidiqi.icu/Article/details/gtommiqmsu.html

JS:   static f() {}
来源：http://dali.tanke756.top/Article/details/gtzeeyeefx.html

TS:   static f(): void {}
来源：http://dali.dianchejie.cn/Article/details/gtgelpjoxk.html

Java: static void f() {}
来源：http://dali.hongshengwenyu.top/Article/details/gtewbephgj.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.xylfe.cn/Article/details/gtnyutwmnm.html

Ruby: def self.f; end
来源：http://dali.meibo888.top/Article/details/gtpnbwtscp.html

C#:   public static void F() {}
来源：http://dali.nanxuanxn.top/Article/details/gtqpjahyzk.html

[G09] 接口 / 抽象类
来源：http://dali.jlsjyb.cn/Article/details/gtuelpoxij.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yj202588.top/Article/details/gtqzryqbkj.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.pengpengdd.cyou/Article/details/gtlrhrlkwu.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.aizwys.cn/Article/details/gtvikyvlya.html

TS:   interface Shape { area(): number; }
来源：http://dali.c1oappe.top/Article/details/gtukzumndu.html

Java: interface Shape { double area(); }
来源：http://dali.vqdsnc.cn/Article/details/gtsjpeeilf.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.haohaochexian.top/Article/details/gtuhtqztnn.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hnqzz.top/Article/details/gtilgielbn.html

C#:   interface IShape { double Area(); }
来源：http://dali.sysykeji.top/Article/details/gtulykyjnr.html

[G10] 访问控制
来源：http://dali.cucudq.cn/Article/details/gtrqwdtpco.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yuxming.cn/Article/details/gtmbycfwgu.html

PHP:  public / protected / private
来源：http://dali.ybcxt.top/Article/details/gtbyraendi.html

JS:   #private 字段；其余公开
来源：http://dali.shangyingyoupin.top/Article/details/gtfiquxcnb.html

TS:   public / protected / private
来源：http://dali.xylfe.cn/Article/details/gtkezqheni.html

Java: public / protected / private / 默认包级
来源：http://dali.cashguo.top/Article/details/gtlkiwungd.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yuanzhike.top/Article/details/gtoklgtrrd.html

Ruby: public / protected / private
来源：http://dali.shanyushiyangtech.top/Article/details/gtjcifyqcc.html

C#:   public / protected / private / internal
来源：http://dali.yuxming.cn/Article/details/gtnirvzahz.html

[G11] getter / setter
来源：http://dali.9152youxi.cn/Article/details/gtrtctdqpf.html

Py:   @property 与 @x.setter
来源：http://dali.yj20258888.top/Article/details/gtknbmuokz.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.gogol.net.cn/Article/details/gtyqfobxuq.html

JS:   get name() { return this._name; }
来源：http://dali.yj20258888.top/Article/details/gtwrqgvuht.html

TS:   get name(): string { return this._name; }
来源：http://dali.jinqigufen.top/Article/details/gtsmqixnbw.html

Java: public String getName() { return name; }
来源：http://dali.guannengcc.top/Article/details/gtrbeecuhq.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.quarkkingdee.top/Article/details/gtzubjmlkp.html

Ruby: attr_accessor :name
来源：http://dali.cucudq.cn/Article/details/gtpuusqqsx.html

C#:   public string Name { get; set; }
来源：http://dali.jinqigufen.top/Article/details/gtvditczao.html

[G12] 对象转字符串
来源：http://dali.jinqigfzy.top/Article/details/gtmoyzmrzr.html

Py:   def __str__(self): return self.name
来源：http://dali.shangyingyoupin.top/Article/details/gtrgdkioka.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hfpthk.cn/Article/details/gtqchosyjc.html

JS:   toString() { return this.name; }
来源：http://dali.jiagoushi.top/Article/details/gtehzeekta.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhengqikj.top/Article/details/gtvknlktut.html

Java: @Override public String toString() { return name; }
来源：http://dali.fzhhl.top/Article/details/gtcmqiwwiu.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yuanzhike.top/Article/details/gtxfoydels.html

Ruby: def to_s; @name; end
来源：http://dali.ydzc1.top/Article/details/gtuqsbncvj.html

C#:   public override string ToString() => Name;
来源：http://dali.kuanghao11.cn/Article/details/gtmcngtaxc.html

[G13] 判断对象类型
来源：http://dali.cdnleiting.top/Article/details/gtiuqykclq.html

Py:   isinstance(u, User)
来源：http://dali.redwolf501.top/Article/details/gtlntlcoio.html

PHP:  $u instanceof User
来源：http://dali.chenlongwang.top/Article/details/gtrwfalgfa.html

JS:   u instanceof User
来源：http://dali.daxiang520.top/Article/details/gtwvwlsgtq.html

TS:   u instanceof User
来源：http://dali.shangyingyoupin.top/Article/details/gtcdybdmmi.html

Java: u instanceof User
来源：http://dali.jinqigfzy.top/Article/details/gthfeqsooe.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.andypj.xyz/Article/details/gtvirpouzg.html

Ruby: u.is_a?(User)
来源：http://dali.svipenyu.cn/Article/details/gtftpowczs.html

C#:   u is User
来源：http://dali.feifeiyinyue.top/Article/details/gtfvwosavx.html

[G14] 数据类 / record
来源：http://dali.cheryme.top/Article/details/gtgmfwslyw.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.sufxvd.cn/Article/details/gtzjmoigrn.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.pycfn.com/Article/details/gtfoaahjjo.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.nwbrower.top/Article/details/gtqiofxsuu.html

TS:   type User = { name: string; age: number };
来源：http://dali.sufxvd.cn/Article/details/gtwjqmrvxo.html

Java: record User(String name, int age) {}
来源：http://dali.shuidangran.top/Article/details/gtvrhsyose.html

Go:   type User struct { Name string; Age int }
来源：http://dali.gzhubu.top/Article/details/gtazygimrq.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.fengsongda.top/Article/details/gtzyzewwjh.html

C#:   record User(string Name, int Age);
来源：http://dali.dianchejie.cn/Article/details/gtgwkfkiiy.html

[G15] 枚举
来源：http://dali.yuxming.cn/Article/details/gtpdphigex.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.gzhubu.top/Article/details/gtfxsmgrpo.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.fzhhl.top/Article/details/gtgwueqrbt.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.tian-w.cn/Article/details/gtldswkvnk.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.tian-w.cn/Article/details/gtevozpucm.html

Java: enum Color { RED, GREEN }
来源：http://dali.guowangkeji.top/Article/details/gttvedefuj.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.nanxuanxn.top/Article/details/gtddjqopev.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yj202588.top/Article/details/gtjwdykyly.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gzhubu.top/Article/details/gtgvixzvho.html

[G16] 对象转数组 / 字典
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoofpziro.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yonumen.top/Article/details/gtjgnxuuaj.html

PHP:  get_object_vars($obj);
来源：http://dali.andypj.xyz/Article/details/gtqjlotckh.html

JS:   Object.entries(obj)
来源：http://dali.kuanghao11.cn/Article/details/gtmcmpbjxj.html

TS:   Object.entries(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtqspjfymd.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.feifeiyinyue.top/Article/details/gtmpkxbbsd.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.hywenlv.cn/Article/details/gtctygnxcr.html

Ruby: obj.instance_variables
来源：http://dali.ivvv.top/Article/details/gtvsmzlmmh.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.ybcxt.top/Article/details/gtmabpwpcg.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtitjtbxcu.html

H. 异常与错误处理
来源：http://dali.hnqzz.top/Article/details/gtebggorfl.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtbxugfaxe.html

[H01] try / catch 基础
来源：http://dali.aizwys.cn/Article/details/gtpsgstfve.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.pengpengdd.cyou/Article/details/gtmbffidsm.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhixingplan.top/Article/details/gtfwjhmssf.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.chenjidiqi.icu/Article/details/gtagvxqxqp.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zdqjudy.top/Article/details/gtaysehzlj.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.ppjwa.cn/Article/details/gtpnjggxep.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.svipenyu.cn/Article/details/gtnhvotolx.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.cheryme.top/Article/details/gtdykjmtza.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.cashguo.top/Article/details/gtgpejgbow.html

[H02] finally / ensure 收尾
来源：http://dali.hnqzz.top/Article/details/gtppzbhuaw.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.mhx1999.top/Article/details/gtitnmmqpy.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yvedp.cn/Article/details/gtxfkwgqma.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gtfdbzmlmt.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.0kj1m.cn/Article/details/gtokcazdsy.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.dashuyun.cn/Article/details/gtfworrifz.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.andypj.xyz/Article/details/gtpcprwdfy.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.hongshengwenyu.top/Article/details/gtduapolke.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yanxiufei.cn/Article/details/gtgmudfroi.html

[H03] 主动抛出异常
来源：http://dali.yueranfly.top/Article/details/gtngnriuhh.html

Py:   raise ValueError("错误信息")
来源：http://dali.sweek.top/Article/details/gtyfyahrqq.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.cdnleiting.top/Article/details/gtqjvencpb.html

JS:   throw new Error("错误信息");
来源：http://dali.yj20258.top/Article/details/gtgcethbwf.html

TS:   throw new Error("错误信息");
来源：http://dali.zhoulong.xyz/Article/details/gthcjluruv.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.316326.xyz/Article/details/gttrllbslj.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yueranfly.top/Article/details/gtfqjkvjri.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hywenlv.cn/Article/details/gtmtlykdud.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.andypj.xyz/Article/details/gtxeuaddmk.html

[H04] 自定义异常类型
来源：http://dali.havefunace.top/Article/details/gtyqawqgdk.html

Py:   class MyError(Exception): pass
来源：http://dali.gzhubu.top/Article/details/gtzdrpmnzj.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jyoumei.cn/Article/details/gtxbqgwzjv.html

JS:   class MyError extends Error {}
来源：http://dali.jinqigufen.top/Article/details/gtxpsamdgb.html

TS:   class MyError extends Error {}
来源：http://dali.daxiang520.top/Article/details/gtuaejifge.html

Java: class MyException extends RuntimeException {}
来源：http://dali.xuetiantiany.cn/Article/details/gtwabajlff.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yvedp.cn/Article/details/gtngsvznue.html

Ruby: class MyError < StandardError; end
来源：http://dali.nanxuanxn.top/Article/details/gtpcmnzqfc.html

C#:   class MyException : Exception {}
来源：http://dali.wangdashe.top/Article/details/gtivqtwowa.html

[H05] 捕获特定类型
来源：http://dali.shangyingyoupin.top/Article/details/gtajkppafj.html

Py:   except ValueError as e:
来源：http://dali.birdmap.top/Article/details/gtkfqmhgix.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.redwolf501.top/Article/details/gtjpnegatw.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtcifuppoj.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjhnqvoej.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.bjfxy.top/Article/details/gtcpzoblcj.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.cashguo.top/Article/details/gthshdzpxd.html

Ruby: rescue ArgumentError => e
来源：http://dali.yj20258888.top/Article/details/gtpmpqlnmc.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.c1oappe.top/Article/details/gttvznbaqa.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gtgfovrylr.html

Py:   value = d.get("k") or default
来源：http://dali.jqgfzy.top/Article/details/gtxvrtsdgw.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.nwbrower.top/Article/details/gttrcxokwt.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.shzxlz.cn/Article/details/gttcfzgrvq.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jqgfzy.top/Article/details/gtgykhputv.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yuxming.cn/Article/details/gtookchkdm.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.ppjwa.cn/Article/details/gtxdiyjovz.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jiagoushi.top/Article/details/gtztqusssg.html

C#:   obj?.A?.B ?? default
来源：http://dali.bjfxy.top/Article/details/gtehfdksgj.html

[H07] 断言
来源：http://dali.tanke756.top/Article/details/gtpwawvygw.html

Py:   assert x > 0, "必须为正"
来源：http://dali.gotoacloud.top/Article/details/gtqtitjjaq.html

PHP:  assert($x > 0);
来源：http://dali.guannengcc.top/Article/details/gtxudylvpd.html

JS:   console.assert(x > 0);
来源：http://dali.yueranfly.top/Article/details/gtfmtkrqod.html

TS:   console.assert(x > 0);
来源：http://dali.hammf.cn/Article/details/gtxxinmuzi.html

Java: assert x > 0 : "必须为正";
来源：http://dali.aizwys.cn/Article/details/gtorqzujyn.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.xuetiantiany.cn/Article/details/gtfbvscmrl.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hysaishi.cn/Article/details/gtpqtpfvfu.html

C#:   Debug.Assert(x > 0);
来源：http://dali.9152youxi.cn/Article/details/gtfrnamfkm.html

[H08] 获取错误信息与堆栈
来源：http://dali.ivvv.top/Article/details/gthdwdeazo.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.guannengcc.top/Article/details/gtgwnimdiw.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.daxiang520.top/Article/details/gtdmnnbiht.html

JS:   e.message;  e.stack
来源：http://dali.quarkkingdee.top/Article/details/gtwbgpbbqg.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.chenjidiqi.icu/Article/details/gtqaqhqujr.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.shzxlz.cn/Article/details/gtipdmjwpu.html

Go:   err.Error()
来源：http://dali.jqgfzy.top/Article/details/gtgkhftrdn.html

Ruby: e.message;  e.backtrace
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkzrnwhsq.html

C#:   e.Message;  e.StackTrace
来源：http://dali.ivvv.top/Article/details/gthvrqpdrh.html

[H09] 带错误码的异常
来源：http://dali.c1oappe.top/Article/details/gtqljauswn.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yuxming.cn/Article/details/gtyvfufleb.html


<!-- 参考信息 -->