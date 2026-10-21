代发 wailian999

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtzrpdokxw.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtkyyrahas.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hnqzz.top/Article/details/gtpyuccqkj.html

Go:   os.Remove("a.txt")
来源：http://dali.daxiang520.top/Article/details/gtuftofviy.html

Ruby: File.delete("a.txt")
来源：http://dali.tian-w.cn/Article/details/gtsjpamusq.html

C#:   File.Delete("a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmmgcjyqf.html

[F07] 创建目录（含多级）
来源：http://dali.jqgfzy.top/Article/details/gtvpqbcelb.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yj202588.top/Article/details/gtdkhcrdfx.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.nanxuanxn.top/Article/details/gtbwkbcrzz.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jyoumei.cn/Article/details/gthfhlgpww.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtynllkqvp.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.xinyue.icu/Article/details/gtznfbwkln.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.shuidangran.top/Article/details/gtjvyaragt.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.guannengcc.top/Article/details/gtjgfarxnq.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gtjqtrvedq.html

[F08] 遍历目录
来源：http://dali.shanyushiyangtech.top/Article/details/gtvindlfjq.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.fzhhl.top/Article/details/gtvpgkbvnc.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgwsrvnnt.html

JS:   fs.readdirSync("dir")
来源：http://dali.tanke756.top/Article/details/gtsnurjodn.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhoulong.xyz/Article/details/gtgmvybbkg.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.haohaochexian.top/Article/details/gtgfkrdpek.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.ybcxt.top/Article/details/gtztvvtele.html

Ruby: Dir.children("dir")
来源：http://dali.shangyingyoupin.top/Article/details/gtugerctvd.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yuxming.cn/Article/details/gtopisdlwl.html

[F09] 获取文件大小
来源：http://dali.gaohongyu789.top/Article/details/gtyafuapja.html

Py:   os.path.getsize("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gthwjstqhl.html

PHP:  filesize("a.txt");
来源：http://dali.yuanzhike.top/Article/details/gtanqkdskg.html

JS:   fs.statSync("a.txt").size
来源：http://dali.gzhubu.top/Article/details/gtefngvhid.html

TS:   fs.statSync("a.txt").size
来源：http://dali.smart0.xyz/Article/details/gttnwdbsgh.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yongpay.top/Article/details/gtdokivsse.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.cheryme.top/Article/details/gtnstsagrq.html

Ruby: File.size("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtlgoipfih.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.tanke756.top/Article/details/gtkbdikytg.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jinqigfzy.top/Article/details/gtrvmswzko.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.gzhubu.top/Article/details/gtsftzsypg.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.daria6918.cn/Article/details/gthwdhscuh.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtmpcknjvp.html

TS:   path.extname("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtqgjnhroj.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.pengpengdd.cyou/Article/details/gtfqmfddws.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yj20258888.top/Article/details/gtdmlwfgep.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtrnsbjwbn.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyohifjzk.html

[F11] 复制与移动文件
来源：http://dali.guannengcc.top/Article/details/gtlrayvhce.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zdqjudy.top/Article/details/gtmxwvifzm.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.quarkkingdee.top/Article/details/gtbpdxyssp.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.0kj1m.cn/Article/details/gtcazzwsyb.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.havefunace.top/Article/details/gtcdiithfv.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.ivvv.top/Article/details/gtmvrbiqfj.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.nwbrower.top/Article/details/gtfiamsbgu.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.hammf.cn/Article/details/gtsxsppdkj.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.gzhubu.top/Article/details/gtadcgdagp.html

[F12] CSV 读写
来源：http://dali.yuxming.cn/Article/details/gtlkputisk.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.guowangkeji.top/Article/details/gtuzogleac.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhiwuduotai.top/Article/details/gtucletkbc.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jinyuanbaomall.cn/Article/details/gtohbtsayw.html

TS:   // 同上
来源：http://dali.pycfn.com/Article/details/gtiklesmgj.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.iojbl.cn/Article/details/gticncvowi.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.sysykeji.top/Article/details/gtyglqygsh.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.kuanghao11.cn/Article/details/gtqhhuqfou.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.smart0.xyz/Article/details/gtxsfbyjwg.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtrbpipxya.html

G. 面向对象
来源：http://dali.tian-w.cn/Article/details/gtidwabozy.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtpgkapwnb.html

[G01] 定义类
来源：http://dali.yj20258888.top/Article/details/gthxkgevmg.html

Py:   class User: pass
来源：http://dali.feifeiyinyue.top/Article/details/gttrourats.html

PHP:  class User {}
来源：http://dali.chenzaomai.com/Article/details/gtfraeznxz.html

JS:   class User {}
来源：http://dali.snrcjt.cn/Article/details/gtcetbyqyd.html

TS:   class User { name: string = ""; }
来源：http://dali.hammf.cn/Article/details/gtlwfwbrqi.html

Java: class User {}
来源：http://dali.tian-w.cn/Article/details/gtyvdddfef.html

Go:   type User struct { Name string }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzivntfui.html

Ruby: class User; end
来源：http://dali.nanxuanxn.top/Article/details/gtgmhpqwgs.html

C#:   class User {}
来源：http://dali.chenzaomai.com/Article/details/gtfjejrxjf.html

[G02] 构造函数
来源：http://dali.jqgufenzy.top/Article/details/gtnlycyyvx.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jyoumei.cn/Article/details/gtolhlmelj.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yj202588.top/Article/details/gtuxhhwide.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.xziqi.cn/Article/details/gtucmoovtg.html

TS:   constructor(public name: string) {}
来源：http://dali.yueranfly.top/Article/details/gtiwabqqpq.html

Java: User(String name) { this.name = name; }
来源：http://dali.daria6918.cn/Article/details/gtuavqgmmn.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhixingplan.top/Article/details/gtjbrlbfvi.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhoulong.xyz/Article/details/gtjmmxhxfk.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jiagoushi.top/Article/details/gtfqrswqwx.html

[G03] 实例属性
来源：http://dali.yj202588.top/Article/details/gtmvgcptcw.html

Py:   self.name = "x"
来源：http://dali.zycfv.cn/Article/details/gtjdameqxz.html

PHP:  public string $name = "x";
来源：http://dali.haohaochexian.top/Article/details/gtjkwaaowd.html

JS:   this.name = "x";
来源：http://dali.jinghuilouyu.cn/Article/details/gtytpnvxkm.html

TS:   name: string = "x";
来源：http://dali.gogol.net.cn/Article/details/gtunzkcrua.html

Java: private String name;
来源：http://dali.vqdsnc.cn/Article/details/gtcqjodtxk.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.gaohongyu789.top/Article/details/gtdiijadhs.html

Ruby: @name = "x"
来源：http://dali.tian-w.cn/Article/details/gtityroiup.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zycfv.cn/Article/details/gtbidrbhzm.html

[G04] 定义方法
来源：http://dali.cheryme.top/Article/details/gtvqxctiql.html

Py:   def greet(self): return self.name
来源：http://dali.0kj1m.cn/Article/details/gtgvgxouwo.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.xinyue.icu/Article/details/gtvdugyoml.html

JS:   greet() { return this.name; }
来源：http://dali.jqgfzy.top/Article/details/gtcoxufaxq.html

TS:   greet(): string { return this.name; }
来源：http://dali.xylfe.cn/Article/details/gtoujqijir.html

Java: String greet() { return name; }
来源：http://dali.zhongyouzk.top/Article/details/gtuakpjkiu.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.gogol.net.cn/Article/details/gtqgisttbd.html

Ruby: def greet; @name; end
来源：http://dali.svipenyu.cn/Article/details/gtnembwtkj.html

C#:   public string Greet() => Name;
来源：http://dali.shanyushiyangtech.top/Article/details/gtfqmfavkr.html

[G05] 继承
来源：http://dali.vqdsnc.cn/Article/details/gtkygcgsqj.html

Py:   class Admin(User): pass
来源：http://dali.svipenyu.cn/Article/details/gtdtwzmykc.html

PHP:  class Admin extends User {}
来源：http://dali.316326.xyz/Article/details/gtbypjtick.html

JS:   class Admin extends User {}
来源：http://dali.aibaodan.cn/Article/details/gtqzzaffob.html

TS:   class Admin extends User {}
来源：http://dali.shzxlz.cn/Article/details/gtgpqmxwqw.html

Java: class Admin extends User {}
来源：http://dali.zhixingplan.top/Article/details/gtgydfbehr.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhoulong.xyz/Article/details/gtaadzorqq.html

Ruby: class Admin < User; end
来源：http://dali.ppjwa.cn/Article/details/gtynhsaueu.html

C#:   class Admin : User {}
来源：http://dali.yueranfly.top/Article/details/gtdipquzbw.html

[G06] 重写方法
来源：http://dali.tian-w.cn/Article/details/gtfunvtetz.html

Py:   def greet(self): return "admin"
来源：http://dali.cucudq.cn/Article/details/gtjusprwbo.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yj202588.top/Article/details/gtmiyqcsfw.html

JS:   greet() { return "admin"; }
来源：http://dali.316326.xyz/Article/details/gtrajjckys.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jqgufenzy.top/Article/details/gtobutixvo.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.aizwys.cn/Article/details/gtdfajxvsn.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.aibaodan.cn/Article/details/gtgcskrllv.html

Ruby: def greet; "admin"; end
来源：http://dali.xylfe.cn/Article/details/gtivbmmfwd.html

C#:   public override string Greet() => "admin";
来源：http://dali.hywenlv.cn/Article/details/gtdjuxxawm.html

[G07] 调用父类方法
来源：http://dali.ivvv.top/Article/details/gtzrxmujcl.html

Py:   super().greet()
来源：http://dali.sweek.top/Article/details/gthfifchru.html

PHP:  parent::greet();
来源：http://dali.zhiwuduotai.top/Article/details/gtxokobyug.html

JS:   super.greet();
来源：http://dali.sufxvd.cn/Article/details/gtbmstllpy.html

TS:   super.greet();
来源：http://dali.chenlongwang.top/Article/details/gtmxuhqhqi.html

Java: super.greet();
来源：http://dali.zhiwuduotai.top/Article/details/gtzujndhjt.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhiwuduotai.top/Article/details/gtzsymklcr.html

Ruby: super
来源：http://dali.quarkkingdee.top/Article/details/gtkjziwnwe.html

C#:   base.Greet();
来源：http://dali.fzhhl.top/Article/details/gtzcpqjqcm.html

[G08] 静态方法与属性
来源：http://dali.yvedp.cn/Article/details/gtdxuqvfrp.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.gaohongyu789.top/Article/details/gtgcvjwawz.html

PHP:  public static function f() {}
来源：http://dali.jinqigfzy.top/Article/details/gtxumhuvkj.html

JS:   static f() {}
来源：http://dali.birdmap.top/Article/details/gtwaglapsi.html

TS:   static f(): void {}
来源：http://dali.guowangkeji.top/Article/details/gtzquzmism.html

Java: static void f() {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqhcwyopm.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkgawzdgz.html

Ruby: def self.f; end
来源：http://dali.wangdashe.top/Article/details/gtruwwxhjo.html

C#:   public static void F() {}
来源：http://dali.zdqjudy.top/Article/details/gtjjekoeut.html

[G09] 接口 / 抽象类
来源：http://dali.ehwqpu.com/Article/details/gteieboext.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.vqdsnc.cn/Article/details/gtsnntycbq.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.mhx1999.top/Article/details/gtnucjvmhl.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.shangyingyoupin.top/Article/details/gtgnlcsulp.html

TS:   interface Shape { area(): number; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdkbiukwy.html

Java: interface Shape { double area(); }
来源：http://dali.daria6918.cn/Article/details/gtwkminvjg.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jinqigufen.top/Article/details/gteqajpyqz.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.wangdashe.top/Article/details/gtaswruyup.html

C#:   interface IShape { double Area(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbylomdta.html

[G10] 访问控制
来源：http://dali.quarkkingdee.top/Article/details/gtutsqtbrs.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.cdnleiting.top/Article/details/gtbncjgssa.html

PHP:  public / protected / private
来源：http://dali.jlsjyb.cn/Article/details/gtvwllabdp.html

JS:   #private 字段；其余公开
来源：http://dali.sxryk.cn/Article/details/gtfwvfecor.html

TS:   public / protected / private
来源：http://dali.0kj1m.cn/Article/details/gtglhfktcp.html

Java: public / protected / private / 默认包级
来源：http://dali.dianchejie.cn/Article/details/gtzxrdyquv.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlgnajugb.html

Ruby: public / protected / private
来源：http://dali.xuetiantiany.cn/Article/details/gtgklgemcd.html

C#:   public / protected / private / internal
来源：http://dali.feifeiyinyue.top/Article/details/gtkopdwyhm.html

[G11] getter / setter
来源：http://dali.hfpthk.cn/Article/details/gtflcvobhi.html

Py:   @property 与 @x.setter
来源：http://dali.shuidangran.top/Article/details/gtdztabcei.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsnhrhxql.html

JS:   get name() { return this._name; }
来源：http://dali.jianghu66.top/Article/details/gtfaywtmve.html

TS:   get name(): string { return this._name; }
来源：http://dali.yj20258.top/Article/details/gtgsjhfyrq.html

Java: public String getName() { return name; }
来源：http://dali.meibo888.top/Article/details/gtlaeonoxt.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xuanzx.com/Article/details/gtrzhryjdq.html

Ruby: attr_accessor :name
来源：http://dali.feifeiyinyue.top/Article/details/gtzgaihian.html

C#:   public string Name { get; set; }
来源：http://dali.feifeiyinyue.top/Article/details/gtbyhhwdeq.html

[G12] 对象转字符串
来源：http://dali.yj20258.top/Article/details/gtlyyvoaet.html

Py:   def __str__(self): return self.name
来源：http://dali.xziqi.cn/Article/details/gtruwcywyt.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.chenlongwang.top/Article/details/gtaydfvuhc.html

JS:   toString() { return this.name; }
来源：http://dali.ydzc1.top/Article/details/gtqkuheanq.html

TS:   toString(): string { return this.name; }
来源：http://dali.tianlin.xyz/Article/details/gtydcqluqe.html

Java: @Override public String toString() { return name; }
来源：http://dali.jlsjyb.cn/Article/details/gtxfinpxje.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.xylfe.cn/Article/details/gtbtdmipra.html

Ruby: def to_s; @name; end
来源：http://dali.gotoacloud.top/Article/details/gtunofdhqk.html

C#:   public override string ToString() => Name;
来源：http://dali.ivvv.top/Article/details/gtmukrzqel.html

[G13] 判断对象类型
来源：http://dali.iojbl.cn/Article/details/gtcguqvbei.html

Py:   isinstance(u, User)
来源：http://dali.chenlongwang.top/Article/details/gtvxlmxmwm.html

PHP:  $u instanceof User
来源：http://dali.0kj1m.cn/Article/details/gtixxuxsqi.html

JS:   u instanceof User
来源：http://dali.yj20258888.top/Article/details/gtvuapnpxj.html

TS:   u instanceof User
来源：http://dali.yj202588.top/Article/details/gtkcvfzijs.html

Java: u instanceof User
来源：http://dali.jyoumei.cn/Article/details/gtddmhnawj.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.dashuyun.cn/Article/details/gtxmvlrhcd.html

Ruby: u.is_a?(User)
来源：http://dali.yuanzhike.top/Article/details/gtkdtqduhr.html

C#:   u is User
来源：http://dali.zhixingplan.top/Article/details/gtkmzbcaqy.html

[G14] 数据类 / record
来源：http://dali.yongpay.top/Article/details/gtzvxllauc.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yangfankeji.com/Article/details/gtgnvkrgye.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hfpthk.cn/Article/details/gtgiitjtre.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.wangshuangyany.cn/Article/details/gtibppsdwc.html

TS:   type User = { name: string; age: number };
来源：http://dali.jqgfzy.top/Article/details/gtucrfocix.html

Java: record User(String name, int age) {}
来源：http://dali.yangfankeji.com/Article/details/gtkisoyupx.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zdqjudy.top/Article/details/gtotlruxow.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.9152youxi.cn/Article/details/gtjubwzwvm.html

C#:   record User(string Name, int Age);
来源：http://dali.yuanzhike.top/Article/details/gtbeubtseo.html

[G15] 枚举
来源：http://dali.nwbrower.top/Article/details/gtlijgtkqq.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yongpay.top/Article/details/gtewpkocex.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yueranfly.top/Article/details/gthdskxuem.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jinghuilouyu.cn/Article/details/gtotdtximh.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yuanzhike.top/Article/details/gtnciugjph.html

Java: enum Color { RED, GREEN }
来源：http://dali.0kj1m.cn/Article/details/gtjuijgxza.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.tanke756.top/Article/details/gtiojoljen.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ehwqpu.com/Article/details/gtnegcaqtj.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ivvv.top/Article/details/gtolwmxtix.html

[G16] 对象转数组 / 字典
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmfumnlna.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpywkgetw.html

PHP:  get_object_vars($obj);
来源：http://dali.daxiang520.top/Article/details/gtfeqfahip.html

JS:   Object.entries(obj)
来源：http://dali.dianchejie.cn/Article/details/gttefkcbvm.html

TS:   Object.entries(obj)
来源：http://dali.zhengqikj.top/Article/details/gtxvagzyow.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.chenjidiqi.icu/Article/details/gtqjwtyxlc.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.cqqwz.cn/Article/details/gtbgmarjam.html

Ruby: obj.instance_variables
来源：http://dali.yj20258888.top/Article/details/gtiasuhmwr.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jqgufenzy.top/Article/details/gtebjbosrd.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtsxzqbjzj.html

H. 异常与错误处理
来源：http://dali.feifeiyinyue.top/Article/details/gtzgrqympi.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtkdqzcgzt.html

[H01] try / catch 基础
来源：http://dali.hysaishi.cn/Article/details/gtehoyjqig.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.gzhubu.top/Article/details/gtbpcibhli.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.gogol.net.cn/Article/details/gtgcarvujf.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgdfifasw.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.ppjwa.cn/Article/details/gtfsggyszv.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.cucudq.cn/Article/details/gtzziimfsh.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jinqigfzy.top/Article/details/gtisxqloyh.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jqgufenzy.top/Article/details/gtndpqswtn.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.sweek.top/Article/details/gtczmshihy.html

[H02] finally / ensure 收尾
来源：http://dali.quarkkingdee.top/Article/details/gteawzmwvo.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.pengpengdd.cyou/Article/details/gtkumxjizq.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.sxryk.cn/Article/details/gtclaumrqt.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.c1oappe.top/Article/details/gtabffisww.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hammf.cn/Article/details/gtmprvlhut.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbpeykntm.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.shangyingyoupin.top/Article/details/gtweazhird.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.redwolf501.top/Article/details/gtoxjjwowa.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.fzhhl.top/Article/details/gtmytfytdr.html

[H03] 主动抛出异常
来源：http://dali.nanxinkj.top/Article/details/gtukyhcjmv.html

Py:   raise ValueError("错误信息")
来源：http://dali.chenjidiqi.icu/Article/details/gtsolalnxa.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.tian-w.cn/Article/details/gttwldefok.html

JS:   throw new Error("错误信息");
来源：http://dali.shuidangran.top/Article/details/gtpevdksyf.html

TS:   throw new Error("错误信息");
来源：http://dali.zhoulong.xyz/Article/details/gtxahufjab.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yvedp.cn/Article/details/gtqgmazole.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yuxming.cn/Article/details/gtzifdgwsl.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.xuanzx.com/Article/details/gtgedtcsau.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.shzxlz.cn/Article/details/gtqbrtsduu.html

[H04] 自定义异常类型
来源：http://dali.jiagoushi.top/Article/details/gtjpmxakhm.html

Py:   class MyError(Exception): pass
来源：http://dali.hfpthk.cn/Article/details/gtfzfgcsah.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.sweek.top/Article/details/gtnlabxwqp.html

JS:   class MyError extends Error {}
来源：http://dali.zhixingplan.top/Article/details/gtambipzua.html

TS:   class MyError extends Error {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtvuktkafv.html

Java: class MyException extends RuntimeException {}
来源：http://dali.svipenyu.cn/Article/details/gtpoilcuaq.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ybcxt.top/Article/details/gtyiqtauvy.html

Ruby: class MyError < StandardError; end
来源：http://dali.tianlin.xyz/Article/details/gtjtqjupft.html

C#:   class MyException : Exception {}
来源：http://dali.meibo888.top/Article/details/gtgiydeqro.html

[H05] 捕获特定类型
来源：http://dali.yuxming.cn/Article/details/gtjcsrbaja.html

Py:   except ValueError as e:
来源：http://dali.jqgufenzy.top/Article/details/gteyqruwli.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yongpay.top/Article/details/gtyrerbxzk.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtjlxkeolq.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.daxiang520.top/Article/details/gttliakfaq.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.xuanzx.com/Article/details/gtfudwvomm.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.vqdsnc.cn/Article/details/gtylrlnmze.html

Ruby: rescue ArgumentError => e
来源：http://dali.cashguo.top/Article/details/gthbdgjryr.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtlbvpzdti.html

[H06] 可选值 / 空值安全访问
来源：http://dali.iojbl.cn/Article/details/gttpvumkpl.html

Py:   value = d.get("k") or default
来源：http://dali.shuidangran.top/Article/details/gtxkpbluml.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.xylfe.cn/Article/details/gtuftdpnhx.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.pengpengdd.cyou/Article/details/gtdqqrpijk.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.xuetiantiany.cn/Article/details/gtlnrgwuwy.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jlsjyb.cn/Article/details/gtykdoeyyp.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zycfv.cn/Article/details/gtgoxolvqc.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hammf.cn/Article/details/gteubmypyd.html

C#:   obj?.A?.B ?? default
来源：http://dali.jinyuanbaomall.cn/Article/details/gtihhwsapr.html

[H07] 断言
来源：http://dali.0kj1m.cn/Article/details/gtyiuyqcml.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yuanzhike.top/Article/details/gtpfhgkjcu.html

PHP:  assert($x > 0);
来源：http://dali.chenjidiqi.icu/Article/details/gtbaihzmqs.html

JS:   console.assert(x > 0);
来源：http://dali.zhengqikj.top/Article/details/gtscrmlwhu.html

TS:   console.assert(x > 0);
来源：http://dali.c1oappe.top/Article/details/gtnkaokwuo.html

Java: assert x > 0 : "必须为正";
来源：http://dali.cheryme.top/Article/details/gthjmjucga.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.nanxinkj.top/Article/details/gttgboegyh.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yongpay.top/Article/details/gtmaxdombc.html

C#:   Debug.Assert(x > 0);
来源：http://dali.xuetiantiany.cn/Article/details/gtycckmfum.html

[H08] 获取错误信息与堆栈
来源：http://dali.cdnleiting.top/Article/details/gtniweksgk.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.wangdashe.top/Article/details/gtcivyyvaw.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.meibo888.top/Article/details/gthzjpzljc.html

JS:   e.message;  e.stack
来源：http://dali.sxryk.cn/Article/details/gtafdzovye.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhongyouzk.top/Article/details/gtukshgjcc.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hfpthk.cn/Article/details/gtkafkkcjs.html

Go:   err.Error()
来源：http://dali.mhx1999.top/Article/details/gtewjksoai.html

Ruby: e.message;  e.backtrace
来源：http://dali.chenzaomai.com/Article/details/gteyjemdcr.html

C#:   e.Message;  e.StackTrace
来源：http://dali.dianchejie.cn/Article/details/gtpwlmhasc.html

[H09] 带错误码的异常
来源：http://dali.jinghuilouyu.cn/Article/details/gtastpdpqr.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.pycfn.com/Article/details/gtattpkxyx.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.0kj1m.cn/Article/details/gtqumapakb.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.aizwys.cn/Article/details/gtpbnrxtqg.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zdqjudy.top/Article/details/gtvyejsyft.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.pycfn.com/Article/details/gtzbkcpfit.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.shangyingyoupin.top/Article/details/gtexdfqwii.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.chenlongwang.top/Article/details/gtosrmsgfy.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.birdmap.top/Article/details/gtsjmmghdu.html

[H10] 资源自动释放
来源：http://dali.wangdashe.top/Article/details/gtdhoprzjv.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yuxming.cn/Article/details/gtvenfowjj.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yj20258888.top/Article/details/gtfohanitw.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.wangdashe.top/Article/details/gtrnerrsxp.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.aibaodan.cn/Article/details/gtfmbhalmy.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jinqigufen.top/Article/details/gtkhbzftvs.html

Go:   defer f.Close()
来源：http://dali.andypj.xyz/Article/details/gtydrmlqju.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.xziqi.cn/Article/details/gtzwfqmftg.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.fzhhl.top/Article/details/gtlarrztui.html


<!-- 参考信息 -->