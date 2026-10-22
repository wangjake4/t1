代发 wailian999

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhengqikj.top/Article/details/gtsikahpbz.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.wangdashe.top/Article/details/gtmtemufox.html

JS:   fs.readdirSync("dir")
来源：http://dali.yongpay.top/Article/details/gtdmunznxw.html

TS:   fs.readdirSync("dir")
来源：http://dali.hfpthk.cn/Article/details/gtwgusfdfk.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jyoumei.cn/Article/details/gtjbrbosck.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.gzhubu.top/Article/details/gtenaoccqe.html

Ruby: Dir.children("dir")
来源：http://dali.jiagoushi.top/Article/details/gtnguablqq.html

C#:   Directory.GetFiles("dir")
来源：http://dali.dianchejie.cn/Article/details/gtykpajzyf.html

[F09] 获取文件大小
来源：http://dali.tianlin.xyz/Article/details/gtbmuxfhnp.html

Py:   os.path.getsize("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtuzvmzjkd.html

PHP:  filesize("a.txt");
来源：http://dali.hfpthk.cn/Article/details/gtydffupeo.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jinqigfzy.top/Article/details/gtpzhobrkh.html

TS:   fs.statSync("a.txt").size
来源：http://dali.ivvv.top/Article/details/gtbjqszcvg.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.xuetiantiany.cn/Article/details/gtilimqnux.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.chenjidiqi.icu/Article/details/gtvklvpaos.html

Ruby: File.size("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtpqzcwlsl.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.shzxlz.cn/Article/details/gtaktcnhyg.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.chenlongwang.top/Article/details/gtpevyrsbp.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtkatkyawd.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gttnwqhsiq.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtcclsukpf.html

TS:   path.extname("a.txt")
来源：http://dali.hammf.cn/Article/details/gtdfejkhfb.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxfeqczbz.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gttavfagzm.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gthcapubtl.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.316326.xyz/Article/details/gtdyosqtym.html

[F11] 复制与移动文件
来源：http://dali.jqgfzy.top/Article/details/gtusmqpiag.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.ivvv.top/Article/details/gtcrvrfzdz.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.daxiang520.top/Article/details/gtwryxqmmy.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sufxvd.cn/Article/details/gtpraiozpx.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhengqikj.top/Article/details/gthtawicex.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.fzhhl.top/Article/details/gtxighizgs.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.chenzaomai.com/Article/details/gtkvrtbquw.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.cucudq.cn/Article/details/gtxiejkhvd.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.nwbrower.top/Article/details/gttrdbmzwm.html

[F12] CSV 读写
来源：http://dali.aizwys.cn/Article/details/gtlscjnvuy.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.ivvv.top/Article/details/gtyneuujtj.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.xziqi.cn/Article/details/gtegsxycpj.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.sweek.top/Article/details/gtuaalzbpv.html

TS:   // 同上
来源：http://dali.0kj1m.cn/Article/details/gtfldqaqzi.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.guannengcc.top/Article/details/gtnjyhcvyg.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hammf.cn/Article/details/gttnkqpflg.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.xinyue.icu/Article/details/gtugrcyyrg.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.sufxvd.cn/Article/details/gtjnvdqozx.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gthzrcwsff.html

G. 面向对象
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfyumlxum.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtkklhygrs.html

[G01] 定义类
来源：http://dali.shzxlz.cn/Article/details/gtbxwrmrzz.html

Py:   class User: pass
来源：http://dali.meibo888.top/Article/details/gtzmjafscb.html

PHP:  class User {}
来源：http://dali.yuanzhike.top/Article/details/gtxuemhyjr.html

JS:   class User {}
来源：http://dali.jqgfzy.top/Article/details/gtspbquwqw.html

TS:   class User { name: string = ""; }
来源：http://dali.havefunace.top/Article/details/gtaitonvzy.html

Java: class User {}
来源：http://dali.daria6918.cn/Article/details/gtzhlxajbj.html

Go:   type User struct { Name string }
来源：http://dali.snrcjt.cn/Article/details/gtgznxjwfa.html

Ruby: class User; end
来源：http://dali.yuxming.cn/Article/details/gtuwvtsnzs.html

C#:   class User {}
来源：http://dali.jqgufenzy.top/Article/details/gtolbcjhkx.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gtlsjylrtj.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.xuetiantiany.cn/Article/details/gtzybnbnsp.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhijiandao.cn/Article/details/gtykwcuzgl.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhongyouzk.top/Article/details/gtfvdjphdh.html

TS:   constructor(public name: string) {}
来源：http://dali.tian-w.cn/Article/details/gtsvncwawa.html

Java: User(String name) { this.name = name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtmkjqdzxu.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jinqigfzy.top/Article/details/gtdxdwdlmx.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.guannengcc.top/Article/details/gteyneptko.html

C#:   public User(string name) { Name = name; }
来源：http://dali.vqdsnc.cn/Article/details/gtkbmiznar.html

[G03] 实例属性
来源：http://dali.shzxlz.cn/Article/details/gtcbmzabla.html

Py:   self.name = "x"
来源：http://dali.wangshuangyany.cn/Article/details/gtmjvlbnjo.html

PHP:  public string $name = "x";
来源：http://dali.yj202588.top/Article/details/gtwhrhihhg.html

JS:   this.name = "x";
来源：http://dali.zdqjudy.top/Article/details/gthqsfgljd.html

TS:   name: string = "x";
来源：http://dali.wangdashe.top/Article/details/gtohvjndqd.html

Java: private String name;
来源：http://dali.yuanzhike.top/Article/details/gtvtcftsxl.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.xziqi.cn/Article/details/gteswunoqh.html

Ruby: @name = "x"
来源：http://dali.havefunace.top/Article/details/gthxwhyrlg.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.gaohongyu789.top/Article/details/gtmwezlfib.html

[G04] 定义方法
来源：http://dali.pycfn.com/Article/details/gtsagjqyut.html

Py:   def greet(self): return self.name
来源：http://dali.fzhhl.top/Article/details/gtitwpqdfm.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gtzyndvtyl.html

JS:   greet() { return this.name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtbtoirqyl.html

TS:   greet(): string { return this.name; }
来源：http://dali.bjfxy.top/Article/details/gtnifppbsz.html

Java: String greet() { return name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtqqeufglv.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.cucudq.cn/Article/details/gtzztiwdgp.html

Ruby: def greet; @name; end
来源：http://dali.sufxvd.cn/Article/details/gtboabnpcg.html

C#:   public string Greet() => Name;
来源：http://dali.mhx1999.top/Article/details/gtetlssqtn.html

[G05] 继承
来源：http://dali.tian-w.cn/Article/details/gtftbmxpza.html

Py:   class Admin(User): pass
来源：http://dali.dashuyun.cn/Article/details/gtqlldsezc.html

PHP:  class Admin extends User {}
来源：http://dali.cucudq.cn/Article/details/gtusglpuvt.html

JS:   class Admin extends User {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwyzakrez.html

TS:   class Admin extends User {}
来源：http://dali.tianlin.xyz/Article/details/gtqbvtirbd.html

Java: class Admin extends User {}
来源：http://dali.yj202588.top/Article/details/gtpnefobgk.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.tanke756.top/Article/details/gtmrbbqwzv.html

Ruby: class Admin < User; end
来源：http://dali.daxiang520.top/Article/details/gtonqfddvg.html

C#:   class Admin : User {}
来源：http://dali.xziqi.cn/Article/details/gtvqavepen.html

[G06] 重写方法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqpzemgpo.html

Py:   def greet(self): return "admin"
来源：http://dali.zhengqikj.top/Article/details/gtkqeercux.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yonumen.top/Article/details/gtkesjdhbl.html

JS:   greet() { return "admin"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvzywsotg.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jinqigufen.top/Article/details/gthadgcklx.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.xziqi.cn/Article/details/gtsuakdgyl.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.tianlin.xyz/Article/details/gtjodeddxm.html

Ruby: def greet; "admin"; end
来源：http://dali.vqdsnc.cn/Article/details/gtselzvenj.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhijiandao.cn/Article/details/gtdenjxmve.html

[G07] 调用父类方法
来源：http://dali.cqqwz.cn/Article/details/gtymbudrnx.html

Py:   super().greet()
来源：http://dali.smart0.xyz/Article/details/gtufxrytkp.html

PHP:  parent::greet();
来源：http://dali.gzhubu.top/Article/details/gtxoouxywq.html

JS:   super.greet();
来源：http://dali.9152youxi.cn/Article/details/gtenvdiecg.html

TS:   super.greet();
来源：http://dali.kuanghao11.cn/Article/details/gtpqpzsjke.html

Java: super.greet();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnocflbnr.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zycfv.cn/Article/details/gtintygtwl.html

Ruby: super
来源：http://dali.yj202588.top/Article/details/gtjsexzhyb.html

C#:   base.Greet();
来源：http://dali.wangshuangyany.cn/Article/details/gtgrlhsuvh.html

[G08] 静态方法与属性
来源：http://dali.yuanzhike.top/Article/details/gtlxhdphll.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xuanzx.com/Article/details/gtorqrdqmq.html

PHP:  public static function f() {}
来源：http://dali.jinqigfzy.top/Article/details/gtsmefvbqa.html

JS:   static f() {}
来源：http://dali.andypj.xyz/Article/details/gtmguvjfhg.html

TS:   static f(): void {}
来源：http://dali.hongshengwenyu.top/Article/details/gtdbrgtdmf.html

Java: static void f() {}
来源：http://dali.nwbrower.top/Article/details/gttqvoeilk.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.xuetiantiany.cn/Article/details/gteqofwlrm.html

Ruby: def self.f; end
来源：http://dali.tianlin.xyz/Article/details/gtivwpqfdv.html

C#:   public static void F() {}
来源：http://dali.jyoumei.cn/Article/details/gtersdmowf.html

[G09] 接口 / 抽象类
来源：http://dali.gzhubu.top/Article/details/gtjkkutsmb.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.hywenlv.cn/Article/details/gtauicjvry.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.iojbl.cn/Article/details/gthdquhmop.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.sweek.top/Article/details/gtflglqnzd.html

TS:   interface Shape { area(): number; }
来源：http://dali.yonumen.top/Article/details/gtcfdgeugf.html

Java: interface Shape { double area(); }
来源：http://dali.zdqjudy.top/Article/details/gtvpvjxkke.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.316326.xyz/Article/details/gtjaemctgy.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhixingplan.top/Article/details/gtrbebrkse.html

C#:   interface IShape { double Area(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtehsbyhyq.html

[G10] 访问控制
来源：http://dali.yanxiufei.cn/Article/details/gtundngvya.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.sufxvd.cn/Article/details/gtuaevucdz.html

PHP:  public / protected / private
来源：http://dali.yanxiufei.cn/Article/details/gtrspcfoir.html

JS:   #private 字段；其余公开
来源：http://dali.birdmap.top/Article/details/gtpgkmthvi.html

TS:   public / protected / private
来源：http://dali.hywenlv.cn/Article/details/gtgeaxqqqx.html

Java: public / protected / private / 默认包级
来源：http://dali.zhixingplan.top/Article/details/gtytmtzjts.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.gzhubu.top/Article/details/gtcdzcpezv.html

Ruby: public / protected / private
来源：http://dali.yongpay.top/Article/details/gtxprrdmie.html

C#:   public / protected / private / internal
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyvarvjdq.html

[G11] getter / setter
来源：http://dali.tianlin.xyz/Article/details/gtomwjhlpc.html

Py:   @property 与 @x.setter
来源：http://dali.xziqi.cn/Article/details/gtmnnxbfwz.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtmdvdunjs.html

JS:   get name() { return this._name; }
来源：http://dali.yuxming.cn/Article/details/gthcrdwksd.html

TS:   get name(): string { return this._name; }
来源：http://dali.vqdsnc.cn/Article/details/gtbxnobowb.html

Java: public String getName() { return name; }
来源：http://dali.ivvv.top/Article/details/gtoydssssb.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtldditigh.html

Ruby: attr_accessor :name
来源：http://dali.snrcjt.cn/Article/details/gtedhbdxsg.html

C#:   public string Name { get; set; }
来源：http://dali.ydzc1.top/Article/details/gtpikfvofc.html

[G12] 对象转字符串
来源：http://dali.meibo888.top/Article/details/gtmqikfsqr.html

Py:   def __str__(self): return self.name
来源：http://dali.shangyingyoupin.top/Article/details/gtxyothrwr.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.svipenyu.cn/Article/details/gtqankiavd.html

JS:   toString() { return this.name; }
来源：http://dali.yj20258.top/Article/details/gtfqadqfok.html

TS:   toString(): string { return this.name; }
来源：http://dali.jqgfzy.top/Article/details/gtmtsahuno.html

Java: @Override public String toString() { return name; }
来源：http://dali.tianlin.xyz/Article/details/gtsyztemmd.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.ehwqpu.com/Article/details/gtwllpsmsv.html

Ruby: def to_s; @name; end
来源：http://dali.xuanzx.com/Article/details/gtcyjkddiy.html

C#:   public override string ToString() => Name;
来源：http://dali.jinqigfzy.top/Article/details/gtbqkmjsgx.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gtzqemradn.html

Py:   isinstance(u, User)
来源：http://dali.shangyingyoupin.top/Article/details/gtosnaotvu.html

PHP:  $u instanceof User
来源：http://dali.bjfxy.top/Article/details/gtebmcgdru.html

JS:   u instanceof User
来源：http://dali.chenjidiqi.icu/Article/details/gtyhybmihi.html

TS:   u instanceof User
来源：http://dali.fengsongda.top/Article/details/gtnfwopmsx.html

Java: u instanceof User
来源：http://dali.guannengcc.top/Article/details/gtbfsflbbw.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.316326.xyz/Article/details/gtykwuopad.html

Ruby: u.is_a?(User)
来源：http://dali.yangfankeji.com/Article/details/gtpheexlei.html

C#:   u is User
来源：http://dali.guannengcc.top/Article/details/gtulftohnc.html

[G14] 数据类 / record
来源：http://dali.dianchejie.cn/Article/details/gtetedgkox.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.ybcxt.top/Article/details/gtzukufcrj.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yvedp.cn/Article/details/gtavvjhhqr.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.fengsongda.top/Article/details/gtkqizefzy.html

TS:   type User = { name: string; age: number };
来源：http://dali.yvedp.cn/Article/details/gtgdcijphn.html

Java: record User(String name, int age) {}
来源：http://dali.cheryme.top/Article/details/gthddxglra.html

Go:   type User struct { Name string; Age int }
来源：http://dali.c1oappe.top/Article/details/gtrdwmihiu.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.andypj.xyz/Article/details/gtkdmdgskt.html

C#:   record User(string Name, int Age);
来源：http://dali.tianlin.xyz/Article/details/gtmoalvvjb.html

[G15] 枚举
来源：http://dali.mhx1999.top/Article/details/gtagvhuacd.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.kuanghao11.cn/Article/details/gtkjjzuqac.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yj20258888.top/Article/details/gtrpklizfv.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yonumen.top/Article/details/gtbuucuwkd.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.9152youxi.cn/Article/details/gticxgkhjo.html

Java: enum Color { RED, GREEN }
来源：http://dali.yueranfly.top/Article/details/gtomouukru.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.chenjidiqi.icu/Article/details/gtjagxjvmt.html

Ruby: Color = %i[red green].freeze
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqowgjlku.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.quarkkingdee.top/Article/details/gtowptzcna.html

[G16] 对象转数组 / 字典
来源：http://dali.snrcjt.cn/Article/details/gtvajexzav.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.meibo888.top/Article/details/gthyvrlcaj.html

PHP:  get_object_vars($obj);
来源：http://dali.gotoacloud.top/Article/details/gtvijkgzdy.html

JS:   Object.entries(obj)
来源：http://dali.yonumen.top/Article/details/gtxjiqyfcf.html

TS:   Object.entries(obj)
来源：http://dali.cucudq.cn/Article/details/gtpztrsqao.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yvedp.cn/Article/details/gthmwzmbpy.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.xziqi.cn/Article/details/gtqchbbxzc.html

Ruby: obj.instance_variables
来源：http://dali.nanxuanxn.top/Article/details/gtzkliompb.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhiwuduotai.top/Article/details/gtwwspubqq.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtugfklnyu.html

H. 异常与错误处理
来源：http://dali.cqqwz.cn/Article/details/gthuegjkjt.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtqbpulnfe.html

[H01] try / catch 基础
来源：http://dali.fengsongda.top/Article/details/gtwokgejgl.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.316326.xyz/Article/details/gtpmwftbwl.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gtefexohvv.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jinqigufen.top/Article/details/gtgtglwgcs.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.gogol.net.cn/Article/details/gtlyccfcme.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yj20258.top/Article/details/gtobjudxsv.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.meibo888.top/Article/details/gtrgpajdkp.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.xylfe.cn/Article/details/gtlxsdfuxf.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.feifeiyinyue.top/Article/details/gthcpnmcuo.html

[H02] finally / ensure 收尾
来源：http://dali.bjfxy.top/Article/details/gtywcglszo.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.guowangkeji.top/Article/details/gtvnhagumt.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.tanke756.top/Article/details/gtgmddioti.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.kuanghao11.cn/Article/details/gtymbrlxvk.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.daxiang520.top/Article/details/gtnprbyijr.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yj20258.top/Article/details/gtyylmgahl.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.havefunace.top/Article/details/gtdfupyugo.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.hnqzz.top/Article/details/gtaayinkkw.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.cashguo.top/Article/details/gtwwiockjt.html

[H03] 主动抛出异常
来源：http://dali.yonumen.top/Article/details/gtuzlmxvub.html

Py:   raise ValueError("错误信息")
来源：http://dali.316326.xyz/Article/details/gthffsuluj.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.smart0.xyz/Article/details/gtkpyefuwv.html

JS:   throw new Error("错误信息");
来源：http://dali.gaohongyu789.top/Article/details/gtedaqagdk.html

TS:   throw new Error("错误信息");
来源：http://dali.shanyushiyangtech.top/Article/details/gtlnuovwkw.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.9152youxi.cn/Article/details/gtwbdvtkyd.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yj202588.top/Article/details/gtwynubzxc.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.cqqwz.cn/Article/details/gttcpsikcl.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.bjfxy.top/Article/details/gtqixpkleo.html

[H04] 自定义异常类型
来源：http://dali.chenjidiqi.icu/Article/details/gtzsyxxuvq.html

Py:   class MyError(Exception): pass
来源：http://dali.daxiang520.top/Article/details/gthsusiqeq.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.chenzaomai.com/Article/details/gtttjpsyjj.html

JS:   class MyError extends Error {}
来源：http://dali.zhiwuduotai.top/Article/details/gtiflnxafu.html

TS:   class MyError extends Error {}
来源：http://dali.gotoacloud.top/Article/details/gtllmbxegf.html

Java: class MyException extends RuntimeException {}
来源：http://dali.316326.xyz/Article/details/gtjlnoiixz.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jianghu66.top/Article/details/gtkbbvexyu.html

Ruby: class MyError < StandardError; end
来源：http://dali.hnxiangtu.top/Article/details/gtuaedjmny.html

C#:   class MyException : Exception {}
来源：http://dali.hammf.cn/Article/details/gtidgjodqr.html

[H05] 捕获特定类型
来源：http://dali.chenlongwang.top/Article/details/gtykprlvqf.html

Py:   except ValueError as e:
来源：http://dali.316326.xyz/Article/details/gtbjpqjiwg.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhiwuduotai.top/Article/details/gtvxhkdwxe.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yongpay.top/Article/details/gtrwuqvlai.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.chenlongwang.top/Article/details/gtcadooyjk.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzrkmkyan.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.smart0.xyz/Article/details/gtezqsfdze.html

Ruby: rescue ArgumentError => e
来源：http://dali.yongpay.top/Article/details/gtcahwqcge.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.daria6918.cn/Article/details/gtkeflhzkv.html

[H06] 可选值 / 空值安全访问
来源：http://dali.nwbrower.top/Article/details/gtrkvksoaw.html

Py:   value = d.get("k") or default
来源：http://dali.tianlin.xyz/Article/details/gtrlvzjeem.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.guannengcc.top/Article/details/gtepxegkzm.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.meibo888.top/Article/details/gtcijbjfph.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtafmaojjd.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbhlrqgxh.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yonumen.top/Article/details/gtuaxgldit.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yongpay.top/Article/details/gtybpwynck.html

C#:   obj?.A?.B ?? default
来源：http://dali.zycfv.cn/Article/details/gtqxghcqvw.html

[H07] 断言
来源：http://dali.jianghu66.top/Article/details/gtpwuqdxgw.html

Py:   assert x > 0, "必须为正"
来源：http://dali.chenzaomai.com/Article/details/gtsceysgdm.html

PHP:  assert($x > 0);
来源：http://dali.jlsjyb.cn/Article/details/gtzzzwowlh.html

JS:   console.assert(x > 0);
来源：http://dali.jyoumei.cn/Article/details/gtsxcowuen.html

TS:   console.assert(x > 0);
来源：http://dali.andypj.xyz/Article/details/gtasbwwssi.html

Java: assert x > 0 : "必须为正";
来源：http://dali.tian-w.cn/Article/details/gthmnxpipo.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jinyuanbaomall.cn/Article/details/gtshjzxqwk.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.quarkkingdee.top/Article/details/gtnexxuzth.html

C#:   Debug.Assert(x > 0);
来源：http://dali.snrcjt.cn/Article/details/gtdjiiwvjm.html

[H08] 获取错误信息与堆栈
来源：http://dali.yuanzhike.top/Article/details/gtrrhpbjup.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.sweek.top/Article/details/gtmmmdystp.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpporxsch.html

JS:   e.message;  e.stack
来源：http://dali.zhongyouzk.top/Article/details/gttuuhrwje.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.xuetiantiany.cn/Article/details/gtrslsnuth.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.sufxvd.cn/Article/details/gtxgdwevbh.html

Go:   err.Error()
来源：http://dali.cucudq.cn/Article/details/gtwfiiikqd.html

Ruby: e.message;  e.backtrace
来源：http://dali.yangfankeji.com/Article/details/gtypslrgkb.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yj20258.top/Article/details/gtamtzmvdh.html

[H09] 带错误码的异常
来源：http://dali.yuxming.cn/Article/details/gtzttbppyc.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.sysykeji.top/Article/details/gtwrcyuhzr.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.smart0.xyz/Article/details/gtcoszufpb.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.pengpengdd.cyou/Article/details/gtyttwygua.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhoulong.xyz/Article/details/gtvyrarjas.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.pengpengdd.cyou/Article/details/gtqximsjoq.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.haohaochexian.top/Article/details/gtjjrbmqjw.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.chenzaomai.com/Article/details/gthnjqiqod.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.cucudq.cn/Article/details/gtrxazwzoa.html

[H10] 资源自动释放
来源：http://dali.dianchejie.cn/Article/details/gtuhqvqceu.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.snrcjt.cn/Article/details/gtkfrsxbna.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zdqjudy.top/Article/details/gtxhmpuctv.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.mhx1999.top/Article/details/gtubqmwlcn.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yj202588.top/Article/details/gtikygbuik.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.quarkkingdee.top/Article/details/gturhloofl.html

Go:   defer f.Close()
来源：http://dali.jianghu66.top/Article/details/gthwbczdzg.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.sufxvd.cn/Article/details/gtbkhrorfg.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.chenzaomai.com/Article/details/gtpdpdwzjr.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtwlhmjndl.html

I. 正则表达式
来源：http://dali.hnxiangtu.top/Article/details/gtqwskaulo.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtqlqogold.html

[I01] 判断是否匹配
来源：http://dali.sysykeji.top/Article/details/gtcevffwqy.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.birdmap.top/Article/details/gtdmfxhccb.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.guowangkeji.top/Article/details/gtlacftpak.html

JS:   /\d+/.test(s)
来源：http://dali.xziqi.cn/Article/details/gtuefmqdwb.html

TS:   /\d+/.test(s)
来源：http://dali.c1oappe.top/Article/details/gtudoyhnjn.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtavocufuw.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jqgfzy.top/Article/details/gtgqqwuaef.html

Ruby: s.match?(/\d+/)
来源：http://dali.kuanghao11.cn/Article/details/gttllsgbsz.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.wangshuangyany.cn/Article/details/gtcaatfalu.html

[I02] 提取所有匹配
来源：http://dali.cucudq.cn/Article/details/gtlpqknqie.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jianghu66.top/Article/details/gtrhruekle.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jyoumei.cn/Article/details/gtakvsymsz.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.gzhubu.top/Article/details/gtrwpsbxok.html


<!-- 参考信息 -->