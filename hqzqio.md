代发 wailian999

Ruby: File.delete("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtluybetbt.html

C#:   File.Delete("a.txt");
来源：http://dali.hfpthk.cn/Article/details/gtxvsytudv.html

[F07] 创建目录（含多级）
来源：http://dali.gogol.net.cn/Article/details/gtsfkvzlcg.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.ybcxt.top/Article/details/gtqqxhfcdf.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jyoumei.cn/Article/details/gtktkfihxn.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jqgufenzy.top/Article/details/gtamyvxxqa.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zycfv.cn/Article/details/gtfpekxbmk.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhoulong.xyz/Article/details/gtrhplrmgt.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.0kj1m.cn/Article/details/gtztrgfjsm.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.cucudq.cn/Article/details/gtdacqkxrp.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.xuetiantiany.cn/Article/details/gthpjrdnmm.html

[F08] 遍历目录
来源：http://dali.haohaochexian.top/Article/details/gtvluqytyo.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.9152youxi.cn/Article/details/gtrzekahat.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuvvwlvxp.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhongyouzk.top/Article/details/gtxerfjeis.html

TS:   fs.readdirSync("dir")
来源：http://dali.zdqjudy.top/Article/details/gthhrlyypu.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.daxiang520.top/Article/details/gtjvxizlnx.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.hywenlv.cn/Article/details/gtwryaxytd.html

Ruby: Dir.children("dir")
来源：http://dali.hnxiangtu.top/Article/details/gtgwkekodj.html

C#:   Directory.GetFiles("dir")
来源：http://dali.shuidangran.top/Article/details/gtqcpoyggg.html

[F09] 获取文件大小
来源：http://dali.yongpay.top/Article/details/gtmagysdht.html

Py:   os.path.getsize("a.txt")
来源：http://dali.shuidangran.top/Article/details/gtvroeewsb.html

PHP:  filesize("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gtoormnuei.html

JS:   fs.statSync("a.txt").size
来源：http://dali.fzhhl.top/Article/details/gthiquqsvb.html

TS:   fs.statSync("a.txt").size
来源：http://dali.fzhhl.top/Article/details/gtkbrghqyo.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yuxming.cn/Article/details/gtdajpewrw.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.ybcxt.top/Article/details/gthuynvhgp.html

Ruby: File.size("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtbsuxazgy.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.feifeiyinyue.top/Article/details/gtdmyzhotz.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.gzhubu.top/Article/details/gttvampape.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtibscfpax.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yvedp.cn/Article/details/gtyxrtouip.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gthtwxsuuo.html

TS:   path.extname("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtotkpowwa.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.gzhubu.top/Article/details/gtrelmpqpu.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtmknlcdyd.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtaxjnuyrn.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtbaorpeso.html

[F11] 复制与移动文件
来源：http://dali.yj20258.top/Article/details/gtpbnadqeb.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.cdnleiting.top/Article/details/gtmfzscovv.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.sweek.top/Article/details/gtlsvfbdtg.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yuanzhike.top/Article/details/gtfwtwttjf.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtvurluxhu.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhongyouzk.top/Article/details/gtlksbhxxi.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.hnqzz.top/Article/details/gtgmrrxjbu.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yangfankeji.com/Article/details/gtjbteueqr.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jyoumei.cn/Article/details/gtcwehzzct.html

[F12] CSV 读写
来源：http://dali.pycfn.com/Article/details/gtlcyjltkz.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.havefunace.top/Article/details/gtducgnvyj.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.xziqi.cn/Article/details/gtxlfksoai.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmftnxqbr.html

TS:   // 同上
来源：http://dali.yueranfly.top/Article/details/gtxtyahonz.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.chenlongwang.top/Article/details/gtrgbkvzzc.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yongpay.top/Article/details/gtrsxzysgt.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.cashguo.top/Article/details/gtyymrjnzd.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.sxryk.cn/Article/details/gtsffxehjc.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtiqzppszv.html

G. 面向对象
来源：http://dali.aizwys.cn/Article/details/gtzvbfayda.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxahnnbji.html

[G01] 定义类
来源：http://dali.0kj1m.cn/Article/details/gtwlywazlv.html

Py:   class User: pass
来源：http://dali.ybcxt.top/Article/details/gtakxsblcf.html

PHP:  class User {}
来源：http://dali.vqdsnc.cn/Article/details/gtmutuljkz.html

JS:   class User {}
来源：http://dali.shzxlz.cn/Article/details/gtkvkcnzxj.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gtnxovgthc.html

Java: class User {}
来源：http://dali.hongshengwenyu.top/Article/details/gtiklwlusg.html

Go:   type User struct { Name string }
来源：http://dali.jlsjyb.cn/Article/details/gtnnxqtthe.html

Ruby: class User; end
来源：http://dali.jyoumei.cn/Article/details/gtlrrzutgx.html

C#:   class User {}
来源：http://dali.nwbrower.top/Article/details/gtmteruufe.html

[G02] 构造函数
来源：http://dali.jqgufenzy.top/Article/details/gtdgacbean.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.ppjwa.cn/Article/details/gtqqvbwxjx.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtcxmrsedq.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqluktmpn.html

TS:   constructor(public name: string) {}
来源：http://dali.gotoacloud.top/Article/details/gtqklvhzee.html

Java: User(String name) { this.name = name; }
来源：http://dali.snrcjt.cn/Article/details/gtnpvtbzym.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hysaishi.cn/Article/details/gtsdjtnhwm.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hongshengwenyu.top/Article/details/gtmkullzfb.html

C#:   public User(string name) { Name = name; }
来源：http://dali.gzhubu.top/Article/details/gtygnxkzkl.html

[G03] 实例属性
来源：http://dali.yuanzhike.top/Article/details/gtnwxyfpgx.html

Py:   self.name = "x"
来源：http://dali.ivvv.top/Article/details/gtplvuyrzu.html

PHP:  public string $name = "x";
来源：http://dali.hfpthk.cn/Article/details/gtwqtltplp.html

JS:   this.name = "x";
来源：http://dali.cheryme.top/Article/details/gtuxiqqemn.html

TS:   name: string = "x";
来源：http://dali.jyoumei.cn/Article/details/gtowybnosk.html

Java: private String name;
来源：http://dali.0kj1m.cn/Article/details/gtfglwzbxu.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yj202588.top/Article/details/gtemkxdvqq.html

Ruby: @name = "x"
来源：http://dali.jlsjyb.cn/Article/details/gtnrzvtqqs.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.guowangkeji.top/Article/details/gtdvgfjzeb.html

[G04] 定义方法
来源：http://dali.yj202588.top/Article/details/gtgaodqwps.html

Py:   def greet(self): return self.name
来源：http://dali.feifeiyinyue.top/Article/details/gtinlrsuvw.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.haohaochexian.top/Article/details/gtxpyxptgq.html

JS:   greet() { return this.name; }
来源：http://dali.zhixingplan.top/Article/details/gtovzqqlbd.html

TS:   greet(): string { return this.name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkglholwg.html

Java: String greet() { return name; }
来源：http://dali.andypj.xyz/Article/details/gtpocvuzdy.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zycfv.cn/Article/details/gtaxadgmoj.html

Ruby: def greet; @name; end
来源：http://dali.tianlin.xyz/Article/details/gtfkaczogo.html

C#:   public string Greet() => Name;
来源：http://dali.aizwys.cn/Article/details/gttmlhpeul.html

[G05] 继承
来源：http://dali.pycfn.com/Article/details/gtzilwaauw.html

Py:   class Admin(User): pass
来源：http://dali.ydzc1.top/Article/details/gtqivmuito.html

PHP:  class Admin extends User {}
来源：http://dali.jyoumei.cn/Article/details/gtegajurnq.html

JS:   class Admin extends User {}
来源：http://dali.sysykeji.top/Article/details/gtkqlzugnh.html

TS:   class Admin extends User {}
来源：http://dali.hammf.cn/Article/details/gthwlliwnb.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gtizgsvlia.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hammf.cn/Article/details/gtfuoymbhm.html

Ruby: class Admin < User; end
来源：http://dali.gzhubu.top/Article/details/gtwqvawyzx.html

C#:   class Admin : User {}
来源：http://dali.shuidangran.top/Article/details/gtbyztbjxc.html

[G06] 重写方法
来源：http://dali.fzhhl.top/Article/details/gtjzvykwbb.html

Py:   def greet(self): return "admin"
来源：http://dali.gaohongyu789.top/Article/details/gtnailffcq.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.svipenyu.cn/Article/details/gtijrwkopi.html

JS:   greet() { return "admin"; }
来源：http://dali.vqdsnc.cn/Article/details/gttjizyskg.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zdqjudy.top/Article/details/gtkpqynyvg.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.meibo888.top/Article/details/gtltxtlhzh.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.xylfe.cn/Article/details/gtvlendsbh.html

Ruby: def greet; "admin"; end
来源：http://dali.yvedp.cn/Article/details/gtfdmixkbe.html

C#:   public override string Greet() => "admin";
来源：http://dali.yj20258888.top/Article/details/gtclrevuxf.html

[G07] 调用父类方法
来源：http://dali.jianghu66.top/Article/details/gtxehlufzm.html

Py:   super().greet()
来源：http://dali.cdnleiting.top/Article/details/gtdegecdyp.html

PHP:  parent::greet();
来源：http://dali.xinyue.icu/Article/details/gtfjbbcqbw.html

JS:   super.greet();
来源：http://dali.zycfv.cn/Article/details/gtnxxsfnca.html

TS:   super.greet();
来源：http://dali.yangfankeji.com/Article/details/gttihoovpp.html

Java: super.greet();
来源：http://dali.ehwqpu.com/Article/details/gtsjljeyax.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.xuetiantiany.cn/Article/details/gtngxxgwyc.html

Ruby: super
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqghiczvq.html

C#:   base.Greet();
来源：http://dali.mhx1999.top/Article/details/gtawumfkll.html

[G08] 静态方法与属性
来源：http://dali.zycfv.cn/Article/details/gtgkktxxwo.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnezsiylq.html

PHP:  public static function f() {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuqbhvett.html

JS:   static f() {}
来源：http://dali.zhengqikj.top/Article/details/gtbsqzkmgd.html

TS:   static f(): void {}
来源：http://dali.shzxlz.cn/Article/details/gtpvpcoulj.html

Java: static void f() {}
来源：http://dali.gotoacloud.top/Article/details/gtxxnzcfeu.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hysaishi.cn/Article/details/gtlpkpjehn.html

Ruby: def self.f; end
来源：http://dali.ehwqpu.com/Article/details/gtqmfvetdt.html

C#:   public static void F() {}
来源：http://dali.jiagoushi.top/Article/details/gtnsgnhcdv.html

[G09] 接口 / 抽象类
来源：http://dali.yuxming.cn/Article/details/gtyygoaceq.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yonumen.top/Article/details/gtsngvmnln.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.cucudq.cn/Article/details/gtbbsktmhk.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zycfv.cn/Article/details/gtwvprixwu.html

TS:   interface Shape { area(): number; }
来源：http://dali.hnqzz.top/Article/details/gtuuazhgfr.html

Java: interface Shape { double area(); }
来源：http://dali.nanxuanxn.top/Article/details/gtxiezjoym.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jianghu66.top/Article/details/gtnmbkzosx.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.tianlin.xyz/Article/details/gtqvyrhbtt.html

C#:   interface IShape { double Area(); }
来源：http://dali.snrcjt.cn/Article/details/gtmmofbrhw.html

[G10] 访问控制
来源：http://dali.wangshuangyany.cn/Article/details/gtvkmiwquo.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.havefunace.top/Article/details/gtkwxorexv.html

PHP:  public / protected / private
来源：http://dali.jqgfzy.top/Article/details/gtezzrjnvy.html

JS:   #private 字段；其余公开
来源：http://dali.zhiwuduotai.top/Article/details/gtbkumjvjh.html

TS:   public / protected / private
来源：http://dali.hnqzz.top/Article/details/gtiuterphc.html

Java: public / protected / private / 默认包级
来源：http://dali.tian-w.cn/Article/details/gtlebjfdvl.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xylfe.cn/Article/details/gtkdylcvps.html

Ruby: public / protected / private
来源：http://dali.zhixingplan.top/Article/details/gtsmpkvkjh.html

C#:   public / protected / private / internal
来源：http://dali.cashguo.top/Article/details/gtsiuqrofb.html

[G11] getter / setter
来源：http://dali.mhx1999.top/Article/details/gtssghexfv.html

Py:   @property 与 @x.setter
来源：http://dali.cdnleiting.top/Article/details/gtmcnksajl.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.9152youxi.cn/Article/details/gtaoyhuozg.html

JS:   get name() { return this._name; }
来源：http://dali.quarkkingdee.top/Article/details/gtyhxnhkjp.html

TS:   get name(): string { return this._name; }
来源：http://dali.andypj.xyz/Article/details/gtfpbbbfck.html

Java: public String getName() { return name; }
来源：http://dali.zhixingplan.top/Article/details/gttopxywhy.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xuetiantiany.cn/Article/details/gtbafmxjgh.html

Ruby: attr_accessor :name
来源：http://dali.xuanzx.com/Article/details/gtoahicqrf.html

C#:   public string Name { get; set; }
来源：http://dali.yanxiufei.cn/Article/details/gttzrudqlg.html

[G12] 对象转字符串
来源：http://dali.xinyue.icu/Article/details/gtpwbwaddv.html

Py:   def __str__(self): return self.name
来源：http://dali.sweek.top/Article/details/gtdwhptjyp.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.aizwys.cn/Article/details/gtndtuowdv.html

JS:   toString() { return this.name; }
来源：http://dali.zhongyouzk.top/Article/details/gtveizvacg.html

TS:   toString(): string { return this.name; }
来源：http://dali.vqdsnc.cn/Article/details/gtkugidlit.html

Java: @Override public String toString() { return name; }
来源：http://dali.sxryk.cn/Article/details/gtpeyrcuza.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.ivvv.top/Article/details/gtbroroigs.html

Ruby: def to_s; @name; end
来源：http://dali.gzhubu.top/Article/details/gtymwsdtih.html

C#:   public override string ToString() => Name;
来源：http://dali.redwolf501.top/Article/details/gtalujrryx.html

[G13] 判断对象类型
来源：http://dali.fzhhl.top/Article/details/gtivzmdvvs.html

Py:   isinstance(u, User)
来源：http://dali.yj20258.top/Article/details/gtnoyzveqd.html

PHP:  $u instanceof User
来源：http://dali.sxryk.cn/Article/details/gttnfexbda.html

JS:   u instanceof User
来源：http://dali.316326.xyz/Article/details/gtvtewhaqs.html

TS:   u instanceof User
来源：http://dali.jianghu66.top/Article/details/gtkxfdbnbf.html

Java: u instanceof User
来源：http://dali.shzxlz.cn/Article/details/gtyebslyfz.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.cdnleiting.top/Article/details/gtspppaabg.html

Ruby: u.is_a?(User)
来源：http://dali.yanxiufei.cn/Article/details/gtwivdvmre.html

C#:   u is User
来源：http://dali.wangshuangyany.cn/Article/details/gtgqpdxnni.html

[G14] 数据类 / record
来源：http://dali.yueranfly.top/Article/details/gttufakrac.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.daxiang520.top/Article/details/gtfmlyqnzw.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.andypj.xyz/Article/details/gtpbxmqmiu.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yvedp.cn/Article/details/gtwnprayvc.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdoltyoob.html

Java: record User(String name, int age) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtnvwglnsx.html

Go:   type User struct { Name string; Age int }
来源：http://dali.meibo888.top/Article/details/gtkurclodx.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.0kj1m.cn/Article/details/gtjterrbol.html

C#:   record User(string Name, int Age);
来源：http://dali.andypj.xyz/Article/details/gtjvfijmnp.html

[G15] 枚举
来源：http://dali.snrcjt.cn/Article/details/gtoiewxrhb.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yvedp.cn/Article/details/gtpjqfprar.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtsglftneb.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.pycfn.com/Article/details/gteemhifsx.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cdnleiting.top/Article/details/gtworslpbp.html

Java: enum Color { RED, GREEN }
来源：http://dali.smart0.xyz/Article/details/gtgqsazoer.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.xylfe.cn/Article/details/gthsabdmvy.html

Ruby: Color = %i[red green].freeze
来源：http://dali.hnxiangtu.top/Article/details/gtoktcyyia.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.tianlin.xyz/Article/details/gtnuxlnflj.html

[G16] 对象转数组 / 字典
来源：http://dali.tian-w.cn/Article/details/gtbybjasbi.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhoulong.xyz/Article/details/gtoqoahysu.html

PHP:  get_object_vars($obj);
来源：http://dali.chenjidiqi.icu/Article/details/gtvgfmjvta.html

JS:   Object.entries(obj)
来源：http://dali.chenlongwang.top/Article/details/gtfvjhawnr.html

TS:   Object.entries(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjsllrhsz.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.aibaodan.cn/Article/details/gtateuqypp.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jqgufenzy.top/Article/details/gtelslqjhv.html

Ruby: obj.instance_variables
来源：http://dali.iojbl.cn/Article/details/gtwerzwmtf.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hammf.cn/Article/details/gtigeuhgrx.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtwlrwjkmj.html

H. 异常与错误处理
来源：http://dali.zhengqikj.top/Article/details/gtkyfizijh.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gthqairppl.html

[H01] try / catch 基础
来源：http://dali.bjfxy.top/Article/details/gtpqmlmeib.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtangtxbma.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.xuanzx.com/Article/details/gtmkdqjqpi.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.shangyingyoupin.top/Article/details/gtjvxarxal.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.sysykeji.top/Article/details/gtrknztgxd.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yj20258888.top/Article/details/gtnultvnrl.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.chenzaomai.com/Article/details/gtzkcdwgky.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.hnqzz.top/Article/details/gtkwrjtsmh.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ppjwa.cn/Article/details/gtjtkxkuvp.html

[H02] finally / ensure 收尾
来源：http://dali.cdnleiting.top/Article/details/gtwhwfustr.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.xziqi.cn/Article/details/gthinzaaye.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yuanzhike.top/Article/details/gtwovkplik.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yangfankeji.com/Article/details/gtwedwkepe.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jiagoushi.top/Article/details/gtujcabgvf.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.ehwqpu.com/Article/details/gtlbruxair.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.xinyue.icu/Article/details/gtzypkyteb.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.meibo888.top/Article/details/gtkeuhbjtl.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.xziqi.cn/Article/details/gtopeysvri.html

[H03] 主动抛出异常
来源：http://dali.svipenyu.cn/Article/details/gtwisyaqqo.html

Py:   raise ValueError("错误信息")
来源：http://dali.nanxuanxn.top/Article/details/gtskzgsjjq.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.ybcxt.top/Article/details/gtakrwinkp.html

JS:   throw new Error("错误信息");
来源：http://dali.hywenlv.cn/Article/details/gtjefyamlf.html

TS:   throw new Error("错误信息");
来源：http://dali.ybcxt.top/Article/details/gtcaxmhcfi.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.gogol.net.cn/Article/details/gtvqskorrm.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jqgufenzy.top/Article/details/gtaqhfgvui.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.xziqi.cn/Article/details/gtkminkihv.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.haohaochexian.top/Article/details/gtrgblypad.html

[H04] 自定义异常类型
来源：http://dali.wangshuangyany.cn/Article/details/gtrnmnaqqi.html

Py:   class MyError(Exception): pass
来源：http://dali.chenzaomai.com/Article/details/gtvcijcwne.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.wangdashe.top/Article/details/gtdrsuncai.html

JS:   class MyError extends Error {}
来源：http://dali.chenlongwang.top/Article/details/gtjmvjreej.html

TS:   class MyError extends Error {}
来源：http://dali.shuidangran.top/Article/details/gttqvgphtw.html

Java: class MyException extends RuntimeException {}
来源：http://dali.dashuyun.cn/Article/details/gtrkycvznq.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.haohaochexian.top/Article/details/gtxjkqpihl.html

Ruby: class MyError < StandardError; end
来源：http://dali.tianlin.xyz/Article/details/gtdspuqwjr.html

C#:   class MyException : Exception {}
来源：http://dali.yangfankeji.com/Article/details/gtbxidlpii.html

[H05] 捕获特定类型
来源：http://dali.hywenlv.cn/Article/details/gtfurcajtw.html

Py:   except ValueError as e:
来源：http://dali.jinyuanbaomall.cn/Article/details/gtahxuslnv.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.aibaodan.cn/Article/details/gtplctarwp.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.andypj.xyz/Article/details/gtdhpdlghg.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtegbewljc.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.fzhhl.top/Article/details/gtnorminfb.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.hysaishi.cn/Article/details/gtbybgnutx.html

Ruby: rescue ArgumentError => e
来源：http://dali.sweek.top/Article/details/gtiynkcasw.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jqgufenzy.top/Article/details/gtyrkadmxa.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yanxiufei.cn/Article/details/gtqolreijp.html

Py:   value = d.get("k") or default
来源：http://dali.zhongyouzk.top/Article/details/gtlaojbtaq.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hfpthk.cn/Article/details/gtifubgxjv.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.316326.xyz/Article/details/gtwejsvkdz.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.nanxinkj.top/Article/details/gtsjfvigmk.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yanxiufei.cn/Article/details/gtsyssobab.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhongyouzk.top/Article/details/gttjzuujnc.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yanxiufei.cn/Article/details/gtcdxmipyg.html

C#:   obj?.A?.B ?? default
来源：http://dali.xylfe.cn/Article/details/gthjfsiksp.html

[H07] 断言
来源：http://dali.fengsongda.top/Article/details/gthqyyckrq.html

Py:   assert x > 0, "必须为正"
来源：http://dali.quarkkingdee.top/Article/details/gtmsvfvkqu.html

PHP:  assert($x > 0);
来源：http://dali.ehwqpu.com/Article/details/gtjwhzopyn.html

JS:   console.assert(x > 0);
来源：http://dali.ybcxt.top/Article/details/gtqofhttxc.html

TS:   console.assert(x > 0);
来源：http://dali.wangshuangyany.cn/Article/details/gtbrvoruom.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yj20258.top/Article/details/gttglfeaud.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jqgufenzy.top/Article/details/gtbvpotulz.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.svipenyu.cn/Article/details/gtttcwxgxf.html

C#:   Debug.Assert(x > 0);
来源：http://dali.shangyingyoupin.top/Article/details/gtpcsuhnfp.html

[H08] 获取错误信息与堆栈
来源：http://dali.xuetiantiany.cn/Article/details/gtivhlxizl.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.hywenlv.cn/Article/details/gtxhyvgetg.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hammf.cn/Article/details/gtltrevowk.html

JS:   e.message;  e.stack
来源：http://dali.9152youxi.cn/Article/details/gtvdvqcpyf.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yonumen.top/Article/details/gtggshwmfi.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.dianchejie.cn/Article/details/gtpuxitkjr.html

Go:   err.Error()
来源：http://dali.zycfv.cn/Article/details/gtzqydejxb.html

Ruby: e.message;  e.backtrace
来源：http://dali.jyoumei.cn/Article/details/gthyfpazby.html

C#:   e.Message;  e.StackTrace
来源：http://dali.shzxlz.cn/Article/details/gtznyhhiki.html

[H09] 带错误码的异常
来源：http://dali.ybcxt.top/Article/details/gtvqjtqhwk.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jyoumei.cn/Article/details/gtkpypatzd.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.gotoacloud.top/Article/details/gtvkhklcxe.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.ybcxt.top/Article/details/gtyygrcrpt.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.cqqwz.cn/Article/details/gtrjyebmkm.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.316326.xyz/Article/details/gtmlwquglg.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhengqikj.top/Article/details/gtuekojkev.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.sweek.top/Article/details/gtysgdqwmc.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.c1oappe.top/Article/details/gtoqcidqrk.html

[H10] 资源自动释放
来源：http://dali.yj20258.top/Article/details/gtnvkdjbvz.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.daxiang520.top/Article/details/gtlhqmbcdz.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.sysykeji.top/Article/details/gtsxnlobdu.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhiwuduotai.top/Article/details/gtlnemlbcg.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xuanzx.com/Article/details/gtpyhnekdx.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jinyuanbaomall.cn/Article/details/gttvosdaeg.html

Go:   defer f.Close()
来源：http://dali.meibo888.top/Article/details/gthvjsqdst.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.gotoacloud.top/Article/details/gtcmgsbncc.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhengqikj.top/Article/details/gtpxhkgmvq.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtseyjhukk.html

I. 正则表达式
来源：http://dali.zhijiandao.cn/Article/details/gtprywxvkl.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtcdqoxziy.html

[I01] 判断是否匹配
来源：http://dali.nanxinkj.top/Article/details/gthgmjmdby.html


<!-- 参考信息 -->