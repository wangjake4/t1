代发 wailian999

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.hfpthk.cn/Article/details/gtbhtitjka.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.haohaochexian.top/Article/details/gtntjehopw.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.cashguo.top/Article/details/gtvqfagjqk.html

[F08] 遍历目录
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzabxuhsw.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.sweek.top/Article/details/gtjicwddjj.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.andypj.xyz/Article/details/gtfbtpvike.html

JS:   fs.readdirSync("dir")
来源：http://dali.nwbrower.top/Article/details/gtyevjkplh.html

TS:   fs.readdirSync("dir")
来源：http://dali.yvedp.cn/Article/details/gtbzhsiycw.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkuvwvcjj.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.hammf.cn/Article/details/gtfclehwcz.html

Ruby: Dir.children("dir")
来源：http://dali.sweek.top/Article/details/gtveijgnwq.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhixingplan.top/Article/details/gtpuaxbfvz.html

[F09] 获取文件大小
来源：http://dali.jianghu66.top/Article/details/gtgvnoxiep.html

Py:   os.path.getsize("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtnvoiftkz.html

PHP:  filesize("a.txt");
来源：http://dali.cqqwz.cn/Article/details/gtgohcquba.html

JS:   fs.statSync("a.txt").size
来源：http://dali.xziqi.cn/Article/details/gtdatwsfai.html

TS:   fs.statSync("a.txt").size
来源：http://dali.vqdsnc.cn/Article/details/gtkgkdkqif.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.ydzc1.top/Article/details/gtcrywoovx.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.guannengcc.top/Article/details/gtolsjjhpa.html

Ruby: File.size("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtrbbumppt.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yj202588.top/Article/details/gtqptqyner.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zdqjudy.top/Article/details/gtwjzbpfuq.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbxpzasjv.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.c1oappe.top/Article/details/gtinipetqj.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtjrumgzrs.html

TS:   path.extname("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtlytufwtf.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.iojbl.cn/Article/details/gttbhaebrs.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtdyaorahp.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtbdwucjzy.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtlzsklqbw.html

[F11] 复制与移动文件
来源：http://dali.hysaishi.cn/Article/details/gtzwhlyvwx.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtubjarjzl.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.cucudq.cn/Article/details/gtbdifcqqg.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.daria6918.cn/Article/details/gtqtrdxfgh.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.nanxuanxn.top/Article/details/gttvrqpuna.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.gzhubu.top/Article/details/gtlnjhcazn.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.fzhhl.top/Article/details/gtwuzwuhef.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtnvuqzbuj.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.shanyushiyangtech.top/Article/details/gtpbgumeaj.html

[F12] CSV 读写
来源：http://dali.gogol.net.cn/Article/details/gtnllozomn.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlqoxzekh.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jinqigufen.top/Article/details/gttimxrllx.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhongyouzk.top/Article/details/gtklixbkye.html

TS:   // 同上
来源：http://dali.chenzaomai.com/Article/details/gtwcwslnny.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hysaishi.cn/Article/details/gtilwxchns.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.redwolf501.top/Article/details/gtnxlxlatq.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.cdnleiting.top/Article/details/gtzfgigoen.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.dashuyun.cn/Article/details/gtkydelein.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtaxenwddq.html

G. 面向对象
来源：http://dali.guannengcc.top/Article/details/gthdxhtlqf.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtlzjwimmq.html

[G01] 定义类
来源：http://dali.bjfxy.top/Article/details/gtvknuxsxs.html

Py:   class User: pass
来源：http://dali.cheryme.top/Article/details/gtxcdwasid.html

PHP:  class User {}
来源：http://dali.ydzc1.top/Article/details/gtyaofnmyh.html

JS:   class User {}
来源：http://dali.yj20258888.top/Article/details/gtrghvkpvo.html

TS:   class User { name: string = ""; }
来源：http://dali.hysaishi.cn/Article/details/gtfocvutll.html

Java: class User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwnhhcvjm.html

Go:   type User struct { Name string }
来源：http://dali.shzxlz.cn/Article/details/gthjnewfvi.html

Ruby: class User; end
来源：http://dali.jianghu66.top/Article/details/gtwjqcqqtk.html

C#:   class User {}
来源：http://dali.xuetiantiany.cn/Article/details/gtyttcskxh.html

[G02] 构造函数
来源：http://dali.yvedp.cn/Article/details/gtjltxakdc.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.pengpengdd.cyou/Article/details/gtastsphgq.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jiagoushi.top/Article/details/gtntjtpisr.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtgqfdwats.html

TS:   constructor(public name: string) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtkudpnuvt.html

Java: User(String name) { this.name = name; }
来源：http://dali.chenzaomai.com/Article/details/gtzhkahcub.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.shangyingyoupin.top/Article/details/gtwnutuvhu.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.cashguo.top/Article/details/gtigynkkgr.html

C#:   public User(string name) { Name = name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdypgneus.html

[G03] 实例属性
来源：http://dali.snrcjt.cn/Article/details/gtjfvtsolh.html

Py:   self.name = "x"
来源：http://dali.yuanzhike.top/Article/details/gtfnplrmto.html

PHP:  public string $name = "x";
来源：http://dali.zycfv.cn/Article/details/gtvdgqhgtd.html

JS:   this.name = "x";
来源：http://dali.yongpay.top/Article/details/gtuzmsfylb.html

TS:   name: string = "x";
来源：http://dali.zycfv.cn/Article/details/gtiqmqgdms.html

Java: private String name;
来源：http://dali.cqqwz.cn/Article/details/gtrqxmedgj.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.shangyingyoupin.top/Article/details/gtxweaqxwa.html

Ruby: @name = "x"
来源：http://dali.9152youxi.cn/Article/details/gtuhjndqod.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.pycfn.com/Article/details/gtfghhfnrn.html

[G04] 定义方法
来源：http://dali.tianlin.xyz/Article/details/gtoixmcuan.html

Py:   def greet(self): return self.name
来源：http://dali.zhiwuduotai.top/Article/details/gtcmuwbghz.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.quarkkingdee.top/Article/details/gtkfsehnyj.html

JS:   greet() { return this.name; }
来源：http://dali.ybcxt.top/Article/details/gtogapmdpu.html

TS:   greet(): string { return this.name; }
来源：http://dali.aizwys.cn/Article/details/gthkzonwqw.html

Java: String greet() { return name; }
来源：http://dali.jinqigufen.top/Article/details/gtwkkrbesj.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdcqmqgno.html

Ruby: def greet; @name; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtggvpykzl.html

C#:   public string Greet() => Name;
来源：http://dali.daria6918.cn/Article/details/gtbdrreipx.html

[G05] 继承
来源：http://dali.xinyue.icu/Article/details/gtyxmjodok.html

Py:   class Admin(User): pass
来源：http://dali.bjfxy.top/Article/details/gtyyfmyfcm.html

PHP:  class Admin extends User {}
来源：http://dali.quarkkingdee.top/Article/details/gtroghupta.html

JS:   class Admin extends User {}
来源：http://dali.sufxvd.cn/Article/details/gtgmybazcq.html

TS:   class Admin extends User {}
来源：http://dali.bjfxy.top/Article/details/gtzfrmbzbr.html

Java: class Admin extends User {}
来源：http://dali.hywenlv.cn/Article/details/gtcltmqerr.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ydzc1.top/Article/details/gtowobhhjs.html

Ruby: class Admin < User; end
来源：http://dali.iojbl.cn/Article/details/gtxyjgteoa.html

C#:   class Admin : User {}
来源：http://dali.hongshengwenyu.top/Article/details/gtyjmohnrb.html

[G06] 重写方法
来源：http://dali.jlsjyb.cn/Article/details/gtciaayljk.html

Py:   def greet(self): return "admin"
来源：http://dali.dashuyun.cn/Article/details/gtllwqnhbq.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.ybcxt.top/Article/details/gtqjnmzrus.html

JS:   greet() { return "admin"; }
来源：http://dali.tanke756.top/Article/details/gtjuzfnjcp.html

TS:   greet(): string { return "admin"; }
来源：http://dali.svipenyu.cn/Article/details/gtkllqovyl.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.guannengcc.top/Article/details/gtvoauxhdp.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jinqigfzy.top/Article/details/gtlzebrydx.html

Ruby: def greet; "admin"; end
来源：http://dali.sufxvd.cn/Article/details/gtmrfcuvyt.html

C#:   public override string Greet() => "admin";
来源：http://dali.yuxming.cn/Article/details/gtikdqruhd.html

[G07] 调用父类方法
来源：http://dali.hnxiangtu.top/Article/details/gtyajffinb.html

Py:   super().greet()
来源：http://dali.iojbl.cn/Article/details/gtszgqvjmb.html

PHP:  parent::greet();
来源：http://dali.cdnleiting.top/Article/details/gtabizdndy.html

JS:   super.greet();
来源：http://dali.hywenlv.cn/Article/details/gtziwohrbl.html

TS:   super.greet();
来源：http://dali.jinqigufen.top/Article/details/gtytdoyxmq.html

Java: super.greet();
来源：http://dali.yonumen.top/Article/details/gtvdofpqdo.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.snrcjt.cn/Article/details/gtmyouvsvf.html

Ruby: super
来源：http://dali.cdnleiting.top/Article/details/gtxkohodro.html

C#:   base.Greet();
来源：http://dali.yueranfly.top/Article/details/gtdkrxsnki.html

[G08] 静态方法与属性
来源：http://dali.yonumen.top/Article/details/gtxavruxvi.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.kuanghao11.cn/Article/details/gthtginoaw.html

PHP:  public static function f() {}
来源：http://dali.cdnleiting.top/Article/details/gtkrunharb.html

JS:   static f() {}
来源：http://dali.hywenlv.cn/Article/details/gtsnhdtxtl.html

TS:   static f(): void {}
来源：http://dali.nanxinkj.top/Article/details/gtoaobxdgn.html

Java: static void f() {}
来源：http://dali.yj202588.top/Article/details/gtjxkecmsh.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hongshengwenyu.top/Article/details/gtrelpznen.html

Ruby: def self.f; end
来源：http://dali.ivvv.top/Article/details/gtsnaoogcg.html

C#:   public static void F() {}
来源：http://dali.yuanzhike.top/Article/details/gtvuhaocbt.html

[G09] 接口 / 抽象类
来源：http://dali.xuanzx.com/Article/details/gtnfqzzfkp.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.wangdashe.top/Article/details/gtppvvxfxm.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yongpay.top/Article/details/gtdrnlfhfs.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.feifeiyinyue.top/Article/details/gtddtsriwo.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhoulong.xyz/Article/details/gtkuflcjyg.html

Java: interface Shape { double area(); }
来源：http://dali.xylfe.cn/Article/details/gtrvdkeftr.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.ehwqpu.com/Article/details/gtsoeopagt.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.chenjidiqi.icu/Article/details/gtqawwbsns.html

C#:   interface IShape { double Area(); }
来源：http://dali.sweek.top/Article/details/gtplghlkpp.html

[G10] 访问控制
来源：http://dali.zhiwuduotai.top/Article/details/gtznwxtvdc.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jinqigufen.top/Article/details/gtixcyseqp.html

PHP:  public / protected / private
来源：http://dali.svipenyu.cn/Article/details/gtaxunatnh.html

JS:   #private 字段；其余公开
来源：http://dali.cheryme.top/Article/details/gtkaeqykek.html

TS:   public / protected / private
来源：http://dali.quarkkingdee.top/Article/details/gtgcmjmvua.html

Java: public / protected / private / 默认包级
来源：http://dali.jqgufenzy.top/Article/details/gtfuhfedme.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.iojbl.cn/Article/details/gthpbtbesm.html

Ruby: public / protected / private
来源：http://dali.zhaomingkeji.xyz/Article/details/gtazkmwsyz.html

C#:   public / protected / private / internal
来源：http://dali.yonumen.top/Article/details/gtlafdkfca.html

[G11] getter / setter
来源：http://dali.sufxvd.cn/Article/details/gtippwchen.html

Py:   @property 与 @x.setter
来源：http://dali.c1oappe.top/Article/details/gtuqxyvnaz.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zycfv.cn/Article/details/gtqercjbyq.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gtqpladcps.html

TS:   get name(): string { return this._name; }
来源：http://dali.gaohongyu789.top/Article/details/gtlkfsuppn.html

Java: public String getName() { return name; }
来源：http://dali.dianchejie.cn/Article/details/gtbzludlga.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jqgufenzy.top/Article/details/gtkxtchruv.html

Ruby: attr_accessor :name
来源：http://dali.daria6918.cn/Article/details/gtiutfewtv.html

C#:   public string Name { get; set; }
来源：http://dali.ybcxt.top/Article/details/gtbbbgvojt.html

[G12] 对象转字符串
来源：http://dali.ydzc1.top/Article/details/gtnxgkozjz.html

Py:   def __str__(self): return self.name
来源：http://dali.xuetiantiany.cn/Article/details/gtyiwvhaqd.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yongpay.top/Article/details/gtvqjvzbdg.html

JS:   toString() { return this.name; }
来源：http://dali.yvedp.cn/Article/details/gtdehodoav.html

TS:   toString(): string { return this.name; }
来源：http://dali.xuanzx.com/Article/details/gttshsipkd.html

Java: @Override public String toString() { return name; }
来源：http://dali.jyoumei.cn/Article/details/gtcuztiwgy.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhoulong.xyz/Article/details/gteumknkhc.html

Ruby: def to_s; @name; end
来源：http://dali.pycfn.com/Article/details/gtkzndaqhl.html

C#:   public override string ToString() => Name;
来源：http://dali.meibo888.top/Article/details/gtmyndfvie.html

[G13] 判断对象类型
来源：http://dali.hysaishi.cn/Article/details/gttfhrzpdz.html

Py:   isinstance(u, User)
来源：http://dali.shzxlz.cn/Article/details/gtvyadjfwm.html

PHP:  $u instanceof User
来源：http://dali.chenzaomai.com/Article/details/gtgwnxmhcq.html

JS:   u instanceof User
来源：http://dali.daxiang520.top/Article/details/gtdddgyogw.html

TS:   u instanceof User
来源：http://dali.zhoulong.xyz/Article/details/gtnkhgvexb.html

Java: u instanceof User
来源：http://dali.cheryme.top/Article/details/gtgcqopwbq.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jiagoushi.top/Article/details/gtxpyzesrb.html

Ruby: u.is_a?(User)
来源：http://dali.chenjidiqi.icu/Article/details/gtjileyvas.html

C#:   u is User
来源：http://dali.yongpay.top/Article/details/gthwfpygha.html

[G14] 数据类 / record
来源：http://dali.tianlin.xyz/Article/details/gtsjsqxnds.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.gaohongyu789.top/Article/details/gtudwwrhuh.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yj20258.top/Article/details/gtlozlbvex.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hammf.cn/Article/details/gtfzudrlbm.html

TS:   type User = { name: string; age: number };
来源：http://dali.bjfxy.top/Article/details/gtddgifmfz.html

Java: record User(String name, int age) {}
来源：http://dali.nanxinkj.top/Article/details/gtzdgpexnc.html

Go:   type User struct { Name string; Age int }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqoadigsp.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.haohaochexian.top/Article/details/gtqxmgiikd.html

C#:   record User(string Name, int Age);
来源：http://dali.vqdsnc.cn/Article/details/gtjryvifyg.html

[G15] 枚举
来源：http://dali.ivvv.top/Article/details/gtppkzrtjx.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhongyouzk.top/Article/details/gtoibkvlya.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yj20258888.top/Article/details/gtgqdhxnnu.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.gzhubu.top/Article/details/gtxeeiwiai.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.wangdashe.top/Article/details/gtutnkxbuj.html

Java: enum Color { RED, GREEN }
来源：http://dali.meibo888.top/Article/details/gtdyxjxkvi.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.hfpthk.cn/Article/details/gtpgilbqle.html

Ruby: Color = %i[red green].freeze
来源：http://dali.cdnleiting.top/Article/details/gtnkkrwcea.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.kuanghao11.cn/Article/details/gttbgodelx.html

[G16] 对象转数组 / 字典
来源：http://dali.gotoacloud.top/Article/details/gtwusxuchh.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.chenlongwang.top/Article/details/gtmijsfngx.html

PHP:  get_object_vars($obj);
来源：http://dali.cdnleiting.top/Article/details/gtljreqloa.html

JS:   Object.entries(obj)
来源：http://dali.guannengcc.top/Article/details/gtabcoshlj.html

TS:   Object.entries(obj)
来源：http://dali.wangdashe.top/Article/details/gtmxasxumm.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jianghu66.top/Article/details/gttlpzoref.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.xziqi.cn/Article/details/gtbiuzpxpx.html

Ruby: obj.instance_variables
来源：http://dali.chenjidiqi.icu/Article/details/gtiytwghby.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.xziqi.cn/Article/details/gtfjpzgweq.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtvtfkbgcl.html

H. 异常与错误处理
来源：http://dali.sweek.top/Article/details/gtlaluufnp.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdbtydyfz.html

[H01] try / catch 基础
来源：http://dali.birdmap.top/Article/details/gtajwtqkmu.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiewnwlhk.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.cucudq.cn/Article/details/gtwtlgkftw.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.ydzc1.top/Article/details/gttvmlincu.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwuewyayt.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jianghu66.top/Article/details/gtifawwgkv.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.dianchejie.cn/Article/details/gtgajnrges.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.xziqi.cn/Article/details/gtvdivcfmf.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.vqdsnc.cn/Article/details/gtsmsszzlg.html

[H02] finally / ensure 收尾
来源：http://dali.pengpengdd.cyou/Article/details/gthsubukej.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.wangdashe.top/Article/details/gtpmlrxbko.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtklzqhpan.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.bjfxy.top/Article/details/gtmgpprpot.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.quarkkingdee.top/Article/details/gtutnudgaf.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.c1oappe.top/Article/details/gtzlvpityl.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yongpay.top/Article/details/gtevnwjvbx.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jiagoushi.top/Article/details/gtsazwmlwq.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.snrcjt.cn/Article/details/gtcnthjukt.html

[H03] 主动抛出异常
来源：http://dali.yueranfly.top/Article/details/gtkvgthbga.html

Py:   raise ValueError("错误信息")
来源：http://dali.kuanghao11.cn/Article/details/gtlnuomyga.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jinqigufen.top/Article/details/gtswejefqs.html

JS:   throw new Error("错误信息");
来源：http://dali.redwolf501.top/Article/details/gtfamzbjef.html

TS:   throw new Error("错误信息");
来源：http://dali.meibo888.top/Article/details/gttltkvqhi.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.gotoacloud.top/Article/details/gthmvpntqm.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.ivvv.top/Article/details/gtfnserxzm.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.sxryk.cn/Article/details/gtcktokclx.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yonumen.top/Article/details/gtvivbeedp.html

[H04] 自定义异常类型
来源：http://dali.meibo888.top/Article/details/gtprtmzkgj.html

Py:   class MyError(Exception): pass
来源：http://dali.jiagoushi.top/Article/details/gtdgyhxttz.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.dashuyun.cn/Article/details/gtvqzrtibi.html

JS:   class MyError extends Error {}
来源：http://dali.zhengqikj.top/Article/details/gthjtlohmo.html

TS:   class MyError extends Error {}
来源：http://dali.gogol.net.cn/Article/details/gtbaphbjpi.html

Java: class MyException extends RuntimeException {}
来源：http://dali.9152youxi.cn/Article/details/gtypqwxhxz.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jyoumei.cn/Article/details/gtaldujqzv.html

Ruby: class MyError < StandardError; end
来源：http://dali.pycfn.com/Article/details/gtlhlkscmv.html

C#:   class MyException : Exception {}
来源：http://dali.haohaochexian.top/Article/details/gtaseihyhw.html

[H05] 捕获特定类型
来源：http://dali.daxiang520.top/Article/details/gtiueunxmo.html

Py:   except ValueError as e:
来源：http://dali.nanxuanxn.top/Article/details/gtqaseeosz.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.hongshengwenyu.top/Article/details/gtsempluzv.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.daxiang520.top/Article/details/gtufgfiqdx.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.ppjwa.cn/Article/details/gttqgxawjt.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.nanxuanxn.top/Article/details/gtmqqxhzqb.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.tianlin.xyz/Article/details/gtqujwiuvt.html

Ruby: rescue ArgumentError => e
来源：http://dali.ppjwa.cn/Article/details/gtxyezcfko.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtnfnkabsl.html

[H06] 可选值 / 空值安全访问
来源：http://dali.shanyushiyangkeji.top/Article/details/gtduckawit.html

Py:   value = d.get("k") or default
来源：http://dali.guowangkeji.top/Article/details/gtcdpauzcv.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.cashguo.top/Article/details/gtyajmdqba.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.cqqwz.cn/Article/details/gtlusquokb.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.wangshuangyany.cn/Article/details/gtawskxjgu.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.shuidangran.top/Article/details/gtviylicwq.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.xylfe.cn/Article/details/gtorgjjxfs.html

Ruby: d&.dig(:a, :b)
来源：http://dali.quarkkingdee.top/Article/details/gtixiekhdw.html

C#:   obj?.A?.B ?? default
来源：http://dali.yj20258.top/Article/details/gtcisvkqmo.html

[H07] 断言
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpcascfpa.html

Py:   assert x > 0, "必须为正"
来源：http://dali.shanyushiyangtech.top/Article/details/gtqsksuufu.html

PHP:  assert($x > 0);
来源：http://dali.0kj1m.cn/Article/details/gtmrfoilmn.html

JS:   console.assert(x > 0);
来源：http://dali.hysaishi.cn/Article/details/gtvmgkevhx.html

TS:   console.assert(x > 0);
来源：http://dali.hysaishi.cn/Article/details/gtuclcaeet.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzseactaz.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.feifeiyinyue.top/Article/details/gtwblsjvft.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.daria6918.cn/Article/details/gttqfxbueh.html

C#:   Debug.Assert(x > 0);
来源：http://dali.cdnleiting.top/Article/details/gtjgakmvaf.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhoulong.xyz/Article/details/gtxbjvhonk.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jianghu66.top/Article/details/gtdvurydfn.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.gotoacloud.top/Article/details/gtduxjvkat.html

JS:   e.message;  e.stack
来源：http://dali.nwbrower.top/Article/details/gtqpflzxcv.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zdqjudy.top/Article/details/gtlsratllf.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhaomingkeji.xyz/Article/details/gthzcbhkxu.html

Go:   err.Error()
来源：http://dali.shuidangran.top/Article/details/gtcpguhbvh.html

Ruby: e.message;  e.backtrace
来源：http://dali.xziqi.cn/Article/details/gthrhcwzyp.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jiagoushi.top/Article/details/gtvgecyfwb.html

[H09] 带错误码的异常
来源：http://dali.sufxvd.cn/Article/details/gtxtxzrzcn.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.birdmap.top/Article/details/gtmwevymcj.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.pengpengdd.cyou/Article/details/gtfxbduovv.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.shuidangran.top/Article/details/gtrhypuxcv.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jqgufenzy.top/Article/details/gttrvablgj.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.ehwqpu.com/Article/details/gttplxbunh.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.hysaishi.cn/Article/details/gtoqtddtvi.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhixingplan.top/Article/details/gtwecjkrzl.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yj202588.top/Article/details/gtjyvepvfh.html

[H10] 资源自动释放
来源：http://dali.fzhhl.top/Article/details/gthcwwxhld.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.sweek.top/Article/details/gtwmfgahlm.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhengqikj.top/Article/details/gtzeucicup.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hnqzz.top/Article/details/gtlsabkgnq.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yonumen.top/Article/details/gtxfpccitd.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.chenlongwang.top/Article/details/gtioxcjxfe.html

Go:   defer f.Close()
来源：http://dali.xuetiantiany.cn/Article/details/gtwgrnvmuc.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hysaishi.cn/Article/details/gtfsusznjr.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gtxwzqsaqe.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtznhrrrim.html

I. 正则表达式
来源：http://dali.hammf.cn/Article/details/gtnmlgvogy.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtxhyvoebi.html

[I01] 判断是否匹配
来源：http://dali.daxiang520.top/Article/details/gttrigogdb.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.havefunace.top/Article/details/gtkcjbnupw.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jqgfzy.top/Article/details/gtxgufpsgg.html

JS:   /\d+/.test(s)
来源：http://dali.yj20258.top/Article/details/gtezkdwnsd.html

TS:   /\d+/.test(s)
来源：http://dali.jinqigfzy.top/Article/details/gthqscvmhg.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.dianchejie.cn/Article/details/gtcqoajyou.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yj20258888.top/Article/details/gtldnnodzf.html

Ruby: s.match?(/\d+/)
来源：http://dali.chenzaomai.com/Article/details/gtivctpgvj.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.xziqi.cn/Article/details/gtcnumtphe.html


<!-- 参考信息 -->