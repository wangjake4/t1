代发 wailian999

[F09] 获取文件大小
来源：http://dali.jqgufenzy.top/Article/details/gttfpzpxlu.html

Py:   os.path.getsize("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtnuoczkzx.html

PHP:  filesize("a.txt");
来源：http://dali.xylfe.cn/Article/details/gtvmsitxvb.html

JS:   fs.statSync("a.txt").size
来源：http://dali.xuanzx.com/Article/details/gtmkykzysi.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jqgufenzy.top/Article/details/gteydeepen.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yj20258888.top/Article/details/gttbgmjarm.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yangfankeji.com/Article/details/gtleetoqua.html

Ruby: File.size("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtzwzkpvrn.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.wangshuangyany.cn/Article/details/gtnxtaicjp.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.smart0.xyz/Article/details/gtaajpfgih.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtieyskedv.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gtristmhfl.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtijutocyu.html

TS:   path.extname("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtozidaosi.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hongshengwenyu.top/Article/details/gtzvmgpvhn.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtunneximp.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.havefunace.top/Article/details/gtwhcjrdaa.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpfuppcvf.html

[F11] 复制与移动文件
来源：http://dali.bjfxy.top/Article/details/gtinvoqqsx.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.ydzc1.top/Article/details/gtoopxxvji.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.nanxinkj.top/Article/details/gtwmlibont.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhixingplan.top/Article/details/gtprqiemkf.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yongpay.top/Article/details/gtwerrsqlb.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.chenzaomai.com/Article/details/gtihbmlozv.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.chenjidiqi.icu/Article/details/gtmmehgapr.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtazsviekw.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.gogol.net.cn/Article/details/gtvklwiozt.html

[F12] CSV 读写
来源：http://dali.mhx1999.top/Article/details/gtwnmbxcog.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yj20258.top/Article/details/gttobrkzqi.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.ehwqpu.com/Article/details/gtcqjtohwr.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.shzxlz.cn/Article/details/gtxjkxmyak.html

TS:   // 同上
来源：http://dali.mhx1999.top/Article/details/gtebavtrrz.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.cheryme.top/Article/details/gtctbfdcgi.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.c1oappe.top/Article/details/gtzasswsbo.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.redwolf501.top/Article/details/gtqbjcxmwh.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hammf.cn/Article/details/gtwmdbiucc.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtjvdrxmuf.html

G. 面向对象
来源：http://dali.shzxlz.cn/Article/details/gtazwvottn.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtsgzzlrlt.html

[G01] 定义类
来源：http://dali.hywenlv.cn/Article/details/gthyrqwjsa.html

Py:   class User: pass
来源：http://dali.zhengqikj.top/Article/details/gtggovryjb.html

PHP:  class User {}
来源：http://dali.zhongyouzk.top/Article/details/gtkwefsesd.html

JS:   class User {}
来源：http://dali.shzxlz.cn/Article/details/gtaaqblkbg.html

TS:   class User { name: string = ""; }
来源：http://dali.zhongyouzk.top/Article/details/gtvmbfqbej.html

Java: class User {}
来源：http://dali.c1oappe.top/Article/details/gtnepjzgjs.html

Go:   type User struct { Name string }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsjhdqhof.html

Ruby: class User; end
来源：http://dali.ehwqpu.com/Article/details/gtauutgqbe.html

C#:   class User {}
来源：http://dali.yvedp.cn/Article/details/gtdghwjuft.html

[G02] 构造函数
来源：http://dali.yuxming.cn/Article/details/gtmyqorwly.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.ybcxt.top/Article/details/gtpyxzhteu.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yonumen.top/Article/details/gtmspqpdyv.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhoulong.xyz/Article/details/gtadzwdweq.html

TS:   constructor(public name: string) {}
来源：http://dali.jyoumei.cn/Article/details/gtzuaijkos.html

Java: User(String name) { this.name = name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtzcvqzukw.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.gotoacloud.top/Article/details/gtjdemnvqu.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.guannengcc.top/Article/details/gtgicvbhyu.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yongpay.top/Article/details/gtanjhqurp.html

[G03] 实例属性
来源：http://dali.hnqzz.top/Article/details/gtnsproycl.html

Py:   self.name = "x"
来源：http://dali.zhongyouzk.top/Article/details/gttxkpubyo.html

PHP:  public string $name = "x";
来源：http://dali.yj20258888.top/Article/details/gtjztlcwxp.html

JS:   this.name = "x";
来源：http://dali.wangdashe.top/Article/details/gtxmsdnmif.html

TS:   name: string = "x";
来源：http://dali.mhx1999.top/Article/details/gttsprmaof.html

Java: private String name;
来源：http://dali.zhijiandao.cn/Article/details/gtushgvrvv.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.c1oappe.top/Article/details/gtwigximuq.html

Ruby: @name = "x"
来源：http://dali.havefunace.top/Article/details/gthmxxwezz.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.chenjidiqi.icu/Article/details/gteovgbiax.html

[G04] 定义方法
来源：http://dali.xuanzx.com/Article/details/gtcalhbihk.html

Py:   def greet(self): return self.name
来源：http://dali.hongshengwenyu.top/Article/details/gtwslzohpe.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.aibaodan.cn/Article/details/gtrlovwswk.html

JS:   greet() { return this.name; }
来源：http://dali.fzhhl.top/Article/details/gthuueaovq.html

TS:   greet(): string { return this.name; }
来源：http://dali.ivvv.top/Article/details/gtzkkdgfyf.html

Java: String greet() { return name; }
来源：http://dali.zdqjudy.top/Article/details/gtsjzhnzic.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yj202588.top/Article/details/gtszfjyqez.html

Ruby: def greet; @name; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgzcpyryb.html

C#:   public string Greet() => Name;
来源：http://dali.yuanzhike.top/Article/details/gtsjvgngcb.html

[G05] 继承
来源：http://dali.gogol.net.cn/Article/details/gtsxutdkjg.html

Py:   class Admin(User): pass
来源：http://dali.wangdashe.top/Article/details/gthezzfayn.html

PHP:  class Admin extends User {}
来源：http://dali.ehwqpu.com/Article/details/gtuvfhiehs.html

JS:   class Admin extends User {}
来源：http://dali.sufxvd.cn/Article/details/gtlpsmxwcm.html

TS:   class Admin extends User {}
来源：http://dali.jqgufenzy.top/Article/details/gtshlszfrc.html

Java: class Admin extends User {}
来源：http://dali.hfpthk.cn/Article/details/gtgibbviny.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ydzc1.top/Article/details/gtnbzioffp.html

Ruby: class Admin < User; end
来源：http://dali.nanxinkj.top/Article/details/gtckmahkaz.html

C#:   class Admin : User {}
来源：http://dali.xinyue.icu/Article/details/gtywuhohui.html

[G06] 重写方法
来源：http://dali.yvedp.cn/Article/details/gtnblwgfoc.html

Py:   def greet(self): return "admin"
来源：http://dali.c1oappe.top/Article/details/gtpktyxngz.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.xylfe.cn/Article/details/gtfderbwyy.html

JS:   greet() { return "admin"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpvhwijei.html

TS:   greet(): string { return "admin"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtxojhgsyo.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.sufxvd.cn/Article/details/gtsrioocgx.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zdqjudy.top/Article/details/gtlymexwpc.html

Ruby: def greet; "admin"; end
来源：http://dali.zhoulong.xyz/Article/details/gttcmbfaie.html

C#:   public override string Greet() => "admin";
来源：http://dali.tanke756.top/Article/details/gtykbkfidg.html

[G07] 调用父类方法
来源：http://dali.xuetiantiany.cn/Article/details/gthzqyjdfp.html

Py:   super().greet()
来源：http://dali.shanyushiyangtech.top/Article/details/gtivgpevlm.html

PHP:  parent::greet();
来源：http://dali.tanke756.top/Article/details/gtyjjsigmb.html

JS:   super.greet();
来源：http://dali.hywenlv.cn/Article/details/gtbnnjvjrx.html

TS:   super.greet();
来源：http://dali.cheryme.top/Article/details/gtoxjijwfq.html

Java: super.greet();
来源：http://dali.smart0.xyz/Article/details/gtvznuzucg.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yj202588.top/Article/details/gtmkxrjzio.html

Ruby: super
来源：http://dali.guannengcc.top/Article/details/gtequoompk.html

C#:   base.Greet();
来源：http://dali.gotoacloud.top/Article/details/gtakprhidk.html

[G08] 静态方法与属性
来源：http://dali.quarkkingdee.top/Article/details/gtnsdiurwv.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.smart0.xyz/Article/details/gtbdfidgyn.html

PHP:  public static function f() {}
来源：http://dali.gaohongyu789.top/Article/details/gtwbeqtkie.html

JS:   static f() {}
来源：http://dali.jinqigufen.top/Article/details/gthdkazajs.html

TS:   static f(): void {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtchynbyti.html

Java: static void f() {}
来源：http://dali.yongpay.top/Article/details/gtqnwdizqs.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.bjfxy.top/Article/details/gtgmxlvead.html

Ruby: def self.f; end
来源：http://dali.jinqigfzy.top/Article/details/gtxdcoqfsn.html

C#:   public static void F() {}
来源：http://dali.xziqi.cn/Article/details/gtomxhtdyg.html

[G09] 接口 / 抽象类
来源：http://dali.wangshuangyany.cn/Article/details/gtkaoxftdc.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.daxiang520.top/Article/details/gtieyxvogu.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.ehwqpu.com/Article/details/gtvabrpfaq.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.xuetiantiany.cn/Article/details/gtbsqfqxfi.html

TS:   interface Shape { area(): number; }
来源：http://dali.hysaishi.cn/Article/details/gtstejolkd.html

Java: interface Shape { double area(); }
来源：http://dali.jyoumei.cn/Article/details/gtcnvbzdmr.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.ybcxt.top/Article/details/gtjaqvntvi.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.gzhubu.top/Article/details/gtwfzennzq.html

C#:   interface IShape { double Area(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtzbpfmqbv.html

[G10] 访问控制
来源：http://dali.xinyue.icu/Article/details/gtckvuwjyw.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqevqyrpo.html

PHP:  public / protected / private
来源：http://dali.yj202588.top/Article/details/gtjpkfkymc.html

JS:   #private 字段；其余公开
来源：http://dali.aibaodan.cn/Article/details/gtfsjtduxc.html

TS:   public / protected / private
来源：http://dali.tian-w.cn/Article/details/gttjnbdovm.html

Java: public / protected / private / 默认包级
来源：http://dali.sxryk.cn/Article/details/gtmswipmsl.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhiwuduotai.top/Article/details/gtviaqmsae.html

Ruby: public / protected / private
来源：http://dali.mhx1999.top/Article/details/gtlrslcuir.html

C#:   public / protected / private / internal
来源：http://dali.yuxming.cn/Article/details/gtcevpgjds.html

[G11] getter / setter
来源：http://dali.gogol.net.cn/Article/details/gtbtpjvpks.html

Py:   @property 与 @x.setter
来源：http://dali.jlsjyb.cn/Article/details/gtmitjqlwm.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.cheryme.top/Article/details/gtkcbiongv.html

JS:   get name() { return this._name; }
来源：http://dali.gzhubu.top/Article/details/gtcrncyqjf.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuhthpben.html

Java: public String getName() { return name; }
来源：http://dali.nwbrower.top/Article/details/gtrnbaoyzs.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jinqigufen.top/Article/details/gtmbmfwhkq.html

Ruby: attr_accessor :name
来源：http://dali.zhixingplan.top/Article/details/gtsjuxnmbk.html

C#:   public string Name { get; set; }
来源：http://dali.316326.xyz/Article/details/gtsmymttpy.html

[G12] 对象转字符串
来源：http://dali.jiagoushi.top/Article/details/gtbjybqjnn.html

Py:   def __str__(self): return self.name
来源：http://dali.yonumen.top/Article/details/gtaxquexjy.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.sufxvd.cn/Article/details/gtgbmjikzo.html

JS:   toString() { return this.name; }
来源：http://dali.c1oappe.top/Article/details/gtlquyiizz.html

TS:   toString(): string { return this.name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtnwvludwt.html

Java: @Override public String toString() { return name; }
来源：http://dali.dashuyun.cn/Article/details/gtgxfrzrhq.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jqgfzy.top/Article/details/gtoqbknhfp.html

Ruby: def to_s; @name; end
来源：http://dali.kuanghao11.cn/Article/details/gtqpivzplq.html

C#:   public override string ToString() => Name;
来源：http://dali.tanke756.top/Article/details/gtjadhnfdu.html

[G13] 判断对象类型
来源：http://dali.yonumen.top/Article/details/gtekgadxvl.html

Py:   isinstance(u, User)
来源：http://dali.yuanzhike.top/Article/details/gtgeexwuhw.html

PHP:  $u instanceof User
来源：http://dali.jinghuilouyu.cn/Article/details/gtzexccipq.html

JS:   u instanceof User
来源：http://dali.yj202588.top/Article/details/gthireqimg.html

TS:   u instanceof User
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbbvgdqpw.html

Java: u instanceof User
来源：http://dali.nanxinkj.top/Article/details/gtsniktxdr.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.birdmap.top/Article/details/gtabnkfafn.html

Ruby: u.is_a?(User)
来源：http://dali.tianlin.xyz/Article/details/gthtuurwzp.html

C#:   u is User
来源：http://dali.jianghu66.top/Article/details/gtfqhebazd.html

[G14] 数据类 / record
来源：http://dali.shangyingyoupin.top/Article/details/gtfhdcbjsa.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.xuetiantiany.cn/Article/details/gtesirromi.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jinqigfzy.top/Article/details/gtlilzunww.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.meibo888.top/Article/details/gtorlvtyik.html

TS:   type User = { name: string; age: number };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyjsybizd.html

Java: record User(String name, int age) {}
来源：http://dali.nanxuanxn.top/Article/details/gtaasfzacu.html

Go:   type User struct { Name string; Age int }
来源：http://dali.nwbrower.top/Article/details/gtgaxjhjgn.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yangfankeji.com/Article/details/gtndlfapwu.html

C#:   record User(string Name, int Age);
来源：http://dali.yuxming.cn/Article/details/gtetxdgafc.html

[G15] 枚举
来源：http://dali.ydzc1.top/Article/details/gtivfvmjyv.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.cucudq.cn/Article/details/gtzjldbkmn.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.xziqi.cn/Article/details/gtvrxylsfu.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.quarkkingdee.top/Article/details/gtvcnynsdw.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ybcxt.top/Article/details/gttbuhgswr.html

Java: enum Color { RED, GREEN }
来源：http://dali.nanxuanxn.top/Article/details/gtblqjyuki.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.nanxinkj.top/Article/details/gtkhbxaybr.html

Ruby: Color = %i[red green].freeze
来源：http://dali.316326.xyz/Article/details/gtmzfqvstp.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtybtyubbk.html

[G16] 对象转数组 / 字典
来源：http://dali.tianlin.xyz/Article/details/gtoomsacqc.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jianghu66.top/Article/details/gtzoboaulr.html

PHP:  get_object_vars($obj);
来源：http://dali.havefunace.top/Article/details/gtzlayjoxf.html

JS:   Object.entries(obj)
来源：http://dali.316326.xyz/Article/details/gtypcxshrs.html

TS:   Object.entries(obj)
来源：http://dali.shzxlz.cn/Article/details/gtsxknotoc.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zycfv.cn/Article/details/gtosvbzmtx.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.bjfxy.top/Article/details/gtwufhkhhh.html

Ruby: obj.instance_variables
来源：http://dali.sufxvd.cn/Article/details/gtndjpuqwb.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hysaishi.cn/Article/details/gtbvqxxuxu.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtipcbjxzh.html

H. 异常与错误处理
来源：http://dali.zhoulong.xyz/Article/details/gtyxqixutn.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtdskygycw.html

[H01] try / catch 基础
来源：http://dali.meibo888.top/Article/details/gtrnrdlkek.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jyoumei.cn/Article/details/gtrrybrcjm.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.shzxlz.cn/Article/details/gtepofymyg.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zycfv.cn/Article/details/gtrwtwlgkt.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.svipenyu.cn/Article/details/gtgkljeazf.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.mhx1999.top/Article/details/gtfqzwdhun.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.chenlongwang.top/Article/details/gtxvgdusmw.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jinqigfzy.top/Article/details/gtzfjpekdr.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jyoumei.cn/Article/details/gtoinhvcmq.html

[H02] finally / ensure 收尾
来源：http://dali.nanxuanxn.top/Article/details/gtafhpwwca.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.vqdsnc.cn/Article/details/gtdlrdthob.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtyndvynzc.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yanxiufei.cn/Article/details/gtecvrspdx.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.guannengcc.top/Article/details/gtaafwyfzt.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhiwuduotai.top/Article/details/gtliikjdmh.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.pycfn.com/Article/details/gtajhoubbr.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.cheryme.top/Article/details/gtayeisysk.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.ivvv.top/Article/details/gtyxifoggl.html

[H03] 主动抛出异常
来源：http://dali.ivvv.top/Article/details/gtupuvkgzk.html

Py:   raise ValueError("错误信息")
来源：http://dali.iojbl.cn/Article/details/gtxksasrkl.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.chenzaomai.com/Article/details/gtaokpzqnb.html

JS:   throw new Error("错误信息");
来源：http://dali.ybcxt.top/Article/details/gtfsszcval.html

TS:   throw new Error("错误信息");
来源：http://dali.pycfn.com/Article/details/gtaxceygfi.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.pengpengdd.cyou/Article/details/gtdhuxohxy.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.snrcjt.cn/Article/details/gtojnmimtb.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.tianlin.xyz/Article/details/gtaavvuzkv.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jinghuilouyu.cn/Article/details/gtnkrhpjij.html

[H04] 自定义异常类型
来源：http://dali.jqgfzy.top/Article/details/gtokfwgwbl.html

Py:   class MyError(Exception): pass
来源：http://dali.pycfn.com/Article/details/gtibzthika.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.wangdashe.top/Article/details/gtuwcanspk.html

JS:   class MyError extends Error {}
来源：http://dali.cqqwz.cn/Article/details/gtekmvvfpo.html

TS:   class MyError extends Error {}
来源：http://dali.chenzaomai.com/Article/details/gtoqsqojhx.html

Java: class MyException extends RuntimeException {}
来源：http://dali.xziqi.cn/Article/details/gtapfakctf.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jinqigfzy.top/Article/details/gtkcduwutq.html

Ruby: class MyError < StandardError; end
来源：http://dali.dashuyun.cn/Article/details/gtxuokksif.html

C#:   class MyException : Exception {}
来源：http://dali.guannengcc.top/Article/details/gtoxawpclf.html

[H05] 捕获特定类型
来源：http://dali.snrcjt.cn/Article/details/gthbrwvoid.html

Py:   except ValueError as e:
来源：http://dali.yongpay.top/Article/details/gtftfvytin.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.pengpengdd.cyou/Article/details/gtnftjimkk.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.xuanzx.com/Article/details/gtmrphspqk.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.smart0.xyz/Article/details/gttwsmcrpv.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.tianlin.xyz/Article/details/gtpmywaebt.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jlsjyb.cn/Article/details/gtspczmpcy.html

Ruby: rescue ArgumentError => e
来源：http://dali.nwbrower.top/Article/details/gtswpcepun.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jiagoushi.top/Article/details/gtczoammtx.html

[H06] 可选值 / 空值安全访问
来源：http://dali.c1oappe.top/Article/details/gtzupmsyja.html

Py:   value = d.get("k") or default
来源：http://dali.havefunace.top/Article/details/gtfloidmke.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.wangshuangyany.cn/Article/details/gtyepqgbwy.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jlsjyb.cn/Article/details/gtvqfhuphb.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.cqqwz.cn/Article/details/gtnjegtlft.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.chenjidiqi.icu/Article/details/gtlsdhopzl.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.shanyushiyangkeji.top/Article/details/gteerlpyrk.html

Ruby: d&.dig(:a, :b)
来源：http://dali.redwolf501.top/Article/details/gtymrjzlco.html

C#:   obj?.A?.B ?? default
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfeowgbyp.html

[H07] 断言
来源：http://dali.feifeiyinyue.top/Article/details/gthnfpbsgq.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yanxiufei.cn/Article/details/gtkzrpvqkv.html

PHP:  assert($x > 0);
来源：http://dali.vqdsnc.cn/Article/details/gtkajvcvjs.html

JS:   console.assert(x > 0);
来源：http://dali.sxryk.cn/Article/details/gtajykdech.html

TS:   console.assert(x > 0);
来源：http://dali.zhongyouzk.top/Article/details/gtgrxgaoxd.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jinyuanbaomall.cn/Article/details/gterycqqka.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.gotoacloud.top/Article/details/gtwzdlgrhd.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yanxiufei.cn/Article/details/gtueowaqsy.html

C#:   Debug.Assert(x > 0);
来源：http://dali.dianchejie.cn/Article/details/gtrtekrwqk.html

[H08] 获取错误信息与堆栈
来源：http://dali.bjfxy.top/Article/details/gtwgvlyuud.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yj20258.top/Article/details/gtnvajzzwo.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.vqdsnc.cn/Article/details/gthsegnctu.html

JS:   e.message;  e.stack
来源：http://dali.feifeiyinyue.top/Article/details/gtltljdqjt.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.hywenlv.cn/Article/details/gtuhnpepke.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.shangyingyoupin.top/Article/details/gtkhwqkexb.html

Go:   err.Error()
来源：http://dali.shuidangran.top/Article/details/gtxdthxodt.html

Ruby: e.message;  e.backtrace
来源：http://dali.bjfxy.top/Article/details/gthdcwcjrh.html

C#:   e.Message;  e.StackTrace
来源：http://dali.havefunace.top/Article/details/gtuztyoods.html

[H09] 带错误码的异常
来源：http://dali.andypj.xyz/Article/details/gtqpkjjuni.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jyoumei.cn/Article/details/gtzdhlhtmh.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.ybcxt.top/Article/details/gtehimuogm.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.vqdsnc.cn/Article/details/gtlcjaysja.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhiwuduotai.top/Article/details/gtrjvztzth.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.hnqzz.top/Article/details/gtzdjxohib.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.cqqwz.cn/Article/details/gtwgbgzyar.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yonumen.top/Article/details/gtktcftqix.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zycfv.cn/Article/details/gtnssfsujp.html

[H10] 资源自动释放
来源：http://dali.zhengqikj.top/Article/details/gtbtsgvowt.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.bjfxy.top/Article/details/gtamjenwfo.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.redwolf501.top/Article/details/gtgevoivsc.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hammf.cn/Article/details/gttheyccob.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.316326.xyz/Article/details/gtcxlfcxpx.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.jinghuilouyu.cn/Article/details/gtpinxotkl.html

Go:   defer f.Close()
来源：http://dali.316326.xyz/Article/details/gttemwfuqz.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.ehwqpu.com/Article/details/gtdnbebwpn.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jinqigufen.top/Article/details/gtphhofrkt.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtpravndvn.html

I. 正则表达式
来源：http://dali.sysykeji.top/Article/details/gtlflojzye.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtkxbaqncr.html

[I01] 判断是否匹配
来源：http://dali.tian-w.cn/Article/details/gtdnawhtbj.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.vqdsnc.cn/Article/details/gtugyjhgxt.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jqgfzy.top/Article/details/gtbkcgbinm.html

JS:   /\d+/.test(s)
来源：http://dali.hammf.cn/Article/details/gtldwzscen.html

TS:   /\d+/.test(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtbrokptif.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.hammf.cn/Article/details/gtxlicnrvp.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.smart0.xyz/Article/details/gtuygfqefg.html

Ruby: s.match?(/\d+/)
来源：http://dali.cucudq.cn/Article/details/gtnztlmmhu.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.gaohongyu789.top/Article/details/gtmfuicmkk.html

[I02] 提取所有匹配
来源：http://dali.zhixingplan.top/Article/details/gtwvronvti.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhixingplan.top/Article/details/gtcbanuiai.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.nwbrower.top/Article/details/gtfnmlamnz.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.iojbl.cn/Article/details/gtlrnlzjqr.html

TS:   s.match(/\d+/g)
来源：http://dali.xziqi.cn/Article/details/gtowdbbkur.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.aizwys.cn/Article/details/gtkipbgqxh.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.pycfn.com/Article/details/gtvjigzvoi.html

Ruby: s.scan(/\d+/)
来源：http://dali.hammf.cn/Article/details/gtkfyzkqem.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.birdmap.top/Article/details/gttfdclnxd.html

[I03] 提取捕获分组
来源：http://dali.smart0.xyz/Article/details/gtbrpmtwmb.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.shzxlz.cn/Article/details/gturjcopnc.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.ydzc1.top/Article/details/gtewccgaho.html


<!-- 参考信息 -->