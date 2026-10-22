代发 wailian999

[F09] 获取文件大小
来源：http://dali.bjfxy.top/Article/details/gt2fagqucsc.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2zglalqew.html

PHP:  filesize("a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gt2tzzwjvyp.html

JS:   fs.statSync("a.txt").size
来源：http://dali.hywenlv.cn/Article/details/gt2cbakvewn.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2erlanzdi.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.tanke756.top/Article/details/gt2glijmzcf.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhengqikj.top/Article/details/gt2rfczvnkp.html

Ruby: File.size("a.txt")
来源：http://dali.jianghu66.top/Article/details/gt2pdxtpaez.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.9152youxi.cn/Article/details/gt2qzylunyk.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yongpay.top/Article/details/gt2xblhlfgh.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.snrcjt.cn/Article/details/gt2djrpgldz.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yueranfly.top/Article/details/gt2yrytzjuv.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ubfhjima.html

TS:   path.extname("a.txt")
来源：http://dali.cucudq.cn/Article/details/gt2kwvidwaa.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.shuidangran.top/Article/details/gt2cggnufqj.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gt2flhistuo.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2jxhawpmq.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2wpmhicfk.html

[F11] 复制与移动文件
来源：http://dali.yueranfly.top/Article/details/gt2ntyeuvcn.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2zpmkitud.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yj20258888.top/Article/details/gt2khlqompg.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sxryk.cn/Article/details/gt2qhckqbkt.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.birdmap.top/Article/details/gt2pdlnjsyk.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.xylfe.cn/Article/details/gt2ydkrvfhm.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.hfpthk.cn/Article/details/gt2pfnjajbi.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.fzhhl.top/Article/details/gt2izydccgx.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.xziqi.cn/Article/details/gt2wxfhbknt.html

[F12] CSV 读写
来源：http://dali.yj20258.top/Article/details/gt2rwgzfumh.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.smart0.xyz/Article/details/gt2whhxpdjo.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.daxiang520.top/Article/details/gt2rzibtnwz.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.tian-w.cn/Article/details/gt2lixfmdud.html

TS:   // 同上
来源：http://dali.jiagoushi.top/Article/details/gt2mglujwbl.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.guowangkeji.top/Article/details/gt2zodlpwbn.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.svipenyu.cn/Article/details/gt2yfftantn.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhoulong.xyz/Article/details/gt2oesllcbb.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.chenzaomai.com/Article/details/gt2ahwkbehs.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2ksvalgpd.html

G. 面向对象
来源：http://dali.hnxiangtu.top/Article/details/gt2zgxzxenn.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2mtmewppd.html

[G01] 定义类
来源：http://dali.sxryk.cn/Article/details/gt2uxtzgscn.html

Py:   class User: pass
来源：http://dali.yj20258.top/Article/details/gt2noqcnwjj.html

PHP:  class User {}
来源：http://dali.zhengqikj.top/Article/details/gt2fhuxqscv.html

JS:   class User {}
来源：http://dali.ivvv.top/Article/details/gt2alecdhvv.html

TS:   class User { name: string = ""; }
来源：http://dali.cucudq.cn/Article/details/gt2nwoixnix.html

Java: class User {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2xkjnztzs.html

Go:   type User struct { Name string }
来源：http://dali.yj202588.top/Article/details/gt2utcyzhxs.html

Ruby: class User; end
来源：http://dali.quarkkingdee.top/Article/details/gt2hbwdimdg.html

C#:   class User {}
来源：http://dali.hammf.cn/Article/details/gt2vijgwibu.html

[G02] 构造函数
来源：http://dali.mhx1999.top/Article/details/gt2izsuadkt.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.xinyue.icu/Article/details/gt2hqyrfesi.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.tian-w.cn/Article/details/gt2bdxtfkig.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhongyouzk.top/Article/details/gt2yvdhtjdn.html

TS:   constructor(public name: string) {}
来源：http://dali.jiagoushi.top/Article/details/gt2khtkxjck.html

Java: User(String name) { this.name = name; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2yupkmcif.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jyoumei.cn/Article/details/gt2kojkosuh.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.guannengcc.top/Article/details/gt2sjqleexh.html

C#:   public User(string name) { Name = name; }
来源：http://dali.gzhubu.top/Article/details/gt2dwzrqalk.html

[G03] 实例属性
来源：http://dali.pengpengdd.cyou/Article/details/gt2ojndastl.html

Py:   self.name = "x"
来源：http://dali.meibo888.top/Article/details/gt2xaxtyfrd.html

PHP:  public string $name = "x";
来源：http://dali.nanxuanxn.top/Article/details/gt2xlsdjmoh.html

JS:   this.name = "x";
来源：http://dali.jlsjyb.cn/Article/details/gt2xnwqhpwa.html

TS:   name: string = "x";
来源：http://dali.yuanzhike.top/Article/details/gt2tnlpnref.html

Java: private String name;
来源：http://dali.cucudq.cn/Article/details/gt2irtdckas.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jyoumei.cn/Article/details/gt2tdgtynfw.html

Ruby: @name = "x"
来源：http://dali.dianchejie.cn/Article/details/gt2hcvpteyd.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.vqdsnc.cn/Article/details/gt2cczyrvpb.html

[G04] 定义方法
来源：http://dali.jinghuilouyu.cn/Article/details/gt2anjicxui.html

Py:   def greet(self): return self.name
来源：http://dali.yj20258888.top/Article/details/gt2qicmmzmr.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.sufxvd.cn/Article/details/gt2jcsfleir.html

JS:   greet() { return this.name; }
来源：http://dali.gzhubu.top/Article/details/gt2sgtdzisf.html

TS:   greet(): string { return this.name; }
来源：http://dali.yueranfly.top/Article/details/gt2qdzmbruo.html

Java: String greet() { return name; }
来源：http://dali.daxiang520.top/Article/details/gt2lwwesmuh.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.cqqwz.cn/Article/details/gt2oilsopfl.html

Ruby: def greet; @name; end
来源：http://dali.sufxvd.cn/Article/details/gt2vhocyjvj.html

C#:   public string Greet() => Name;
来源：http://dali.jinqigufen.top/Article/details/gt2oeghmgzh.html

[G05] 继承
来源：http://dali.ybcxt.top/Article/details/gt2tfjgqriq.html

Py:   class Admin(User): pass
来源：http://dali.jiagoushi.top/Article/details/gt2domasyrc.html

PHP:  class Admin extends User {}
来源：http://dali.ybcxt.top/Article/details/gt2swbmlulz.html

JS:   class Admin extends User {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2grthaspm.html

TS:   class Admin extends User {}
来源：http://dali.jianghu66.top/Article/details/gt2sqilrfxf.html

Java: class Admin extends User {}
来源：http://dali.cucudq.cn/Article/details/gt2ztidnxnc.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.chenjidiqi.icu/Article/details/gt2immuyhrg.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rhixdpmt.html

C#:   class Admin : User {}
来源：http://dali.hammf.cn/Article/details/gt2wffvkese.html

[G06] 重写方法
来源：http://dali.birdmap.top/Article/details/gt2nynfuwou.html

Py:   def greet(self): return "admin"
来源：http://dali.xylfe.cn/Article/details/gt2flvhtsxc.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.sxryk.cn/Article/details/gt2abexyvmw.html

JS:   greet() { return "admin"; }
来源：http://dali.jqgfzy.top/Article/details/gt2amjxcxwk.html

TS:   greet(): string { return "admin"; }
来源：http://dali.birdmap.top/Article/details/gt2frrmqnhg.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.quarkkingdee.top/Article/details/gt2ysyssomv.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.shzxlz.cn/Article/details/gt2bncfbweb.html

Ruby: def greet; "admin"; end
来源：http://dali.yanxiufei.cn/Article/details/gt2qgegsimz.html

C#:   public override string Greet() => "admin";
来源：http://dali.jianghu66.top/Article/details/gt2yofewowm.html

[G07] 调用父类方法
来源：http://dali.sufxvd.cn/Article/details/gt2divbiglp.html

Py:   super().greet()
来源：http://dali.hfpthk.cn/Article/details/gt2qxhmlirv.html

PHP:  parent::greet();
来源：http://dali.yj20258.top/Article/details/gt2cqhdxptx.html

JS:   super.greet();
来源：http://dali.yangfankeji.com/Article/details/gt2vpxmwjdd.html

TS:   super.greet();
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cibqlguo.html

Java: super.greet();
来源：http://dali.yongpay.top/Article/details/gt2hdkrpzwg.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.xuanzx.com/Article/details/gt2ljygjfum.html

Ruby: super
来源：http://dali.9152youxi.cn/Article/details/gt2olhbnzla.html

C#:   base.Greet();
来源：http://dali.zhongyouzk.top/Article/details/gt2sqetqjlz.html

[G08] 静态方法与属性
来源：http://dali.cheryme.top/Article/details/gt2qwodskmx.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhiwuduotai.top/Article/details/gt2uyvzcjzr.html

PHP:  public static function f() {}
来源：http://dali.hnxiangtu.top/Article/details/gt2howftqeq.html

JS:   static f() {}
来源：http://dali.hnqzz.top/Article/details/gt2jgnfnivn.html

TS:   static f(): void {}
来源：http://dali.smart0.xyz/Article/details/gt2awiacenk.html

Java: static void f() {}
来源：http://dali.9152youxi.cn/Article/details/gt2wfubxbwa.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jlsjyb.cn/Article/details/gt2wogzjxty.html

Ruby: def self.f; end
来源：http://dali.yueranfly.top/Article/details/gt2nvnjkgzd.html

C#:   public static void F() {}
来源：http://dali.pycfn.com/Article/details/gt2pvkjekur.html

[G09] 接口 / 抽象类
来源：http://dali.birdmap.top/Article/details/gt2moylapxq.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.chenzaomai.com/Article/details/gt2enflovle.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yj202588.top/Article/details/gt2ziylulfi.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ybcxt.top/Article/details/gt2ovfsylpx.html

TS:   interface Shape { area(): number; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2hitesyaq.html

Java: interface Shape { double area(); }
来源：http://dali.guannengcc.top/Article/details/gt2gczyozpv.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.cheryme.top/Article/details/gt2rnzbwmdf.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.chenjidiqi.icu/Article/details/gt2jdhojjvn.html

C#:   interface IShape { double Area(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xigtmfsh.html

[G10] 访问控制
来源：http://dali.chenzaomai.com/Article/details/gt2dnujpten.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.redwolf501.top/Article/details/gt2ufakcinw.html

PHP:  public / protected / private
来源：http://dali.shuidangran.top/Article/details/gt2dnhokboe.html

JS:   #private 字段；其余公开
来源：http://dali.c1oappe.top/Article/details/gt2zavsvace.html

TS:   public / protected / private
来源：http://dali.sweek.top/Article/details/gt2advkegny.html

Java: public / protected / private / 默认包级
来源：http://dali.gaohongyu789.top/Article/details/gt2rncxhtza.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tgxfomzq.html

Ruby: public / protected / private
来源：http://dali.jiagoushi.top/Article/details/gt2xszufoka.html

C#:   public / protected / private / internal
来源：http://dali.jinqigfzy.top/Article/details/gt2abtfsrev.html

[G11] getter / setter
来源：http://dali.zhiwuduotai.top/Article/details/gt2gkoviflx.html

Py:   @property 与 @x.setter
来源：http://dali.yuanzhike.top/Article/details/gt2gbgreafz.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vrmhdake.html

JS:   get name() { return this._name; }
来源：http://dali.yanxiufei.cn/Article/details/gt2igyetmtn.html

TS:   get name(): string { return this._name; }
来源：http://dali.sufxvd.cn/Article/details/gt2mlcjpzds.html

Java: public String getName() { return name; }
来源：http://dali.zycfv.cn/Article/details/gt2hjtoqjuy.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.havefunace.top/Article/details/gt2ssdzjggg.html

Ruby: attr_accessor :name
来源：http://dali.zhiwuduotai.top/Article/details/gt2sclajavv.html

C#:   public string Name { get; set; }
来源：http://dali.cashguo.top/Article/details/gt2rgrnbfvu.html

[G12] 对象转字符串
来源：http://dali.yanxiufei.cn/Article/details/gt2hiuenlmu.html

Py:   def __str__(self): return self.name
来源：http://dali.vqdsnc.cn/Article/details/gt2cwdgyrhg.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yonumen.top/Article/details/gt2ffsexauw.html

JS:   toString() { return this.name; }
来源：http://dali.yj20258888.top/Article/details/gt2oyeydxmy.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2nlakdzsj.html

Java: @Override public String toString() { return name; }
来源：http://dali.yongpay.top/Article/details/gt2eufflake.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.cashguo.top/Article/details/gt2rmqprtsd.html

Ruby: def to_s; @name; end
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uivmqkld.html

C#:   public override string ToString() => Name;
来源：http://dali.fengsongda.top/Article/details/gt2owahijol.html

[G13] 判断对象类型
来源：http://dali.xziqi.cn/Article/details/gt2rlztlgrb.html

Py:   isinstance(u, User)
来源：http://dali.xinyue.icu/Article/details/gt2hznwgvrx.html

PHP:  $u instanceof User
来源：http://dali.ppjwa.cn/Article/details/gt2yisenidp.html

JS:   u instanceof User
来源：http://dali.jqgfzy.top/Article/details/gt2qtlfzncr.html

TS:   u instanceof User
来源：http://dali.redwolf501.top/Article/details/gt2cltesxpq.html

Java: u instanceof User
来源：http://dali.jiagoushi.top/Article/details/gt2coezrmjo.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.ivvv.top/Article/details/gt2koqmitnf.html

Ruby: u.is_a?(User)
来源：http://dali.cdnleiting.top/Article/details/gt2udigjdii.html

C#:   u is User
来源：http://dali.hnxiangtu.top/Article/details/gt2qqmuwhhk.html

[G14] 数据类 / record
来源：http://dali.chenlongwang.top/Article/details/gt2vsonegsm.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ewxjdhiy.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zycfv.cn/Article/details/gt2siifnhqq.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhixingplan.top/Article/details/gt2ncybikso.html

TS:   type User = { name: string; age: number };
来源：http://dali.yangfankeji.com/Article/details/gt2istlpfcf.html

Java: record User(String name, int age) {}
来源：http://dali.hywenlv.cn/Article/details/gt2girvgxlb.html

Go:   type User struct { Name string; Age int }
来源：http://dali.shangyingyoupin.top/Article/details/gt2jbqxluhi.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.chenlongwang.top/Article/details/gt2kjmdkmng.html

C#:   record User(string Name, int Age);
来源：http://dali.haohaochexian.top/Article/details/gt2wzourvrw.html

[G15] 枚举
来源：http://dali.fzhhl.top/Article/details/gt2vtzyocig.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.tanke756.top/Article/details/gt2aysjfakl.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2viogbivt.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.meibo888.top/Article/details/gt2vqsnzpoq.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.bjfxy.top/Article/details/gt2vgmbsxur.html

Java: enum Color { RED, GREEN }
来源：http://dali.aizwys.cn/Article/details/gt2cnqucrua.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.daxiang520.top/Article/details/gt2feomtpnc.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yanxiufei.cn/Article/details/gt2ssoeraui.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ydzc1.top/Article/details/gt2csyghaof.html

[G16] 对象转数组 / 字典
来源：http://dali.hammf.cn/Article/details/gt2mofcpvfz.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.svipenyu.cn/Article/details/gt2zxmuzdqj.html

PHP:  get_object_vars($obj);
来源：http://dali.vqdsnc.cn/Article/details/gt2xxhxavov.html

JS:   Object.entries(obj)
来源：http://dali.zhiwuduotai.top/Article/details/gt2trjwwatg.html

TS:   Object.entries(obj)
来源：http://dali.haohaochexian.top/Article/details/gt2qttouywc.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jyoumei.cn/Article/details/gt2nxsxfxuz.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.quarkkingdee.top/Article/details/gt2cssukleb.html

Ruby: obj.instance_variables
来源：http://dali.redwolf501.top/Article/details/gt2uvkmzobe.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.havefunace.top/Article/details/gt2zqojkono.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2qhnusgbc.html

H. 异常与错误处理
来源：http://dali.cheryme.top/Article/details/gt2qlitmtzn.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2kcqluleb.html

[H01] try / catch 基础
来源：http://dali.hongshengwenyu.top/Article/details/gt2hrsulphz.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.xuanzx.com/Article/details/gt2ekycmcpn.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.tianlin.xyz/Article/details/gt2ooahzsnw.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.meibo888.top/Article/details/gt2pzikwqwe.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhengqikj.top/Article/details/gt2hhpeqnqh.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.cdnleiting.top/Article/details/gt2wotnchuh.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tvbhcjoa.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jinqigufen.top/Article/details/gt2gogbielw.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jinqigufen.top/Article/details/gt2rjgpbjkv.html

[H02] finally / ensure 收尾
来源：http://dali.hnqzz.top/Article/details/gt2jgfvhtoc.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xryzlxwt.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2jhgmdgmm.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.chenlongwang.top/Article/details/gt2fbygtnjs.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.sweek.top/Article/details/gt2nxywmmjw.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xtrfjyfk.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.xuanzx.com/Article/details/gt2iiqlgnzy.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yanxiufei.cn/Article/details/gt2enhoevrs.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2fvfimbnd.html

[H03] 主动抛出异常
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mklgqteq.html

Py:   raise ValueError("错误信息")
来源：http://dali.jqgufenzy.top/Article/details/gt2atqppyfl.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.andypj.xyz/Article/details/gt2rhjcxobb.html

JS:   throw new Error("错误信息");
来源：http://dali.hongshengwenyu.top/Article/details/gt2rstuwmqk.html

TS:   throw new Error("错误信息");
来源：http://dali.sweek.top/Article/details/gt2ykydhvpm.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.ivvv.top/Article/details/gt2cdzhhore.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.ybcxt.top/Article/details/gt2rnqyboov.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.dianchejie.cn/Article/details/gt2ujywqxej.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yvedp.cn/Article/details/gt2swuxpqoc.html

[H04] 自定义异常类型
来源：http://dali.xinyue.icu/Article/details/gt2vypekrqu.html

Py:   class MyError(Exception): pass
来源：http://dali.sufxvd.cn/Article/details/gt2bbmgemvu.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.snrcjt.cn/Article/details/gt2jcmfmkpm.html

JS:   class MyError extends Error {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2sgcqtjdo.html

TS:   class MyError extends Error {}
来源：http://dali.jqgfzy.top/Article/details/gt2nzjeghbp.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yuxming.cn/Article/details/gt2ydivrllj.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.quarkkingdee.top/Article/details/gt2crzogivh.html

Ruby: class MyError < StandardError; end
来源：http://dali.pengpengdd.cyou/Article/details/gt2tqvlgkue.html

C#:   class MyException : Exception {}
来源：http://dali.nwbrower.top/Article/details/gt2azqheead.html

[H05] 捕获特定类型
来源：http://dali.nanxuanxn.top/Article/details/gt2cavoftdz.html

Py:   except ValueError as e:
来源：http://dali.daria6918.cn/Article/details/gt2dxkqrssc.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jianghu66.top/Article/details/gt2wogoayvv.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2bhmxzphs.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.svipenyu.cn/Article/details/gt2flbyrgfz.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.gotoacloud.top/Article/details/gt2dtnpmcfz.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.aibaodan.cn/Article/details/gt2hhkybmxd.html

Ruby: rescue ArgumentError => e
来源：http://dali.daria6918.cn/Article/details/gt2pwhxlhrl.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.cheryme.top/Article/details/gt2bhdnbgnr.html

[H06] 可选值 / 空值安全访问
来源：http://dali.ydzc1.top/Article/details/gt2axyfrakq.html

Py:   value = d.get("k") or default
来源：http://dali.zhongyouzk.top/Article/details/gt2fttcfbhv.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.redwolf501.top/Article/details/gt2poxcdqhd.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.kuanghao11.cn/Article/details/gt2kibirjxf.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jianghu66.top/Article/details/gt2oiqmpnzc.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.dianchejie.cn/Article/details/gt2wlqfhuzq.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.svipenyu.cn/Article/details/gt2nuxbooam.html

Ruby: d&.dig(:a, :b)
来源：http://dali.haohaochexian.top/Article/details/gt2etnfbdxp.html

C#:   obj?.A?.B ?? default
来源：http://dali.xuetiantiany.cn/Article/details/gt2jazhotyf.html

[H07] 断言
来源：http://dali.dianchejie.cn/Article/details/gt2aufipkqc.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yj202588.top/Article/details/gt2qwazhmcn.html

PHP:  assert($x > 0);
来源：http://dali.gogol.net.cn/Article/details/gt2bdknhhks.html

JS:   console.assert(x > 0);
来源：http://dali.xziqi.cn/Article/details/gt2xxhktngc.html

TS:   console.assert(x > 0);
来源：http://dali.ivvv.top/Article/details/gt2ctpcrvxe.html

Java: assert x > 0 : "必须为正";
来源：http://dali.guowangkeji.top/Article/details/gt2ihqsnfjw.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jyoumei.cn/Article/details/gt2fcwditju.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.mhx1999.top/Article/details/gt2shzugdby.html

C#:   Debug.Assert(x > 0);
来源：http://dali.wangshuangyany.cn/Article/details/gt2jisilrza.html

[H08] 获取错误信息与堆栈
来源：http://dali.daria6918.cn/Article/details/gt2hnzavtui.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.chenlongwang.top/Article/details/gt2wkcgkiir.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.birdmap.top/Article/details/gt2lkngxfey.html

JS:   e.message;  e.stack
来源：http://dali.tian-w.cn/Article/details/gt2dagfgyrz.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ncbojsdm.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.sweek.top/Article/details/gt2rhglnkih.html

Go:   err.Error()
来源：http://dali.hnxiangtu.top/Article/details/gt2cpiskpuh.html

Ruby: e.message;  e.backtrace
来源：http://dali.yuanzhike.top/Article/details/gt2yxjgocib.html

C#:   e.Message;  e.StackTrace
来源：http://dali.pengpengdd.cyou/Article/details/gt2sztqfexp.html

[H09] 带错误码的异常
来源：http://dali.xuetiantiany.cn/Article/details/gt2xljdwugf.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.nanxuanxn.top/Article/details/gt2mxunewwt.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.quarkkingdee.top/Article/details/gt2easkylce.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jyoumei.cn/Article/details/gt2fspzyzbi.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.dashuyun.cn/Article/details/gt2ydhvctwy.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.gzhubu.top/Article/details/gt2xhouqgtb.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.dianchejie.cn/Article/details/gt2imetueuz.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.chenlongwang.top/Article/details/gt2lszigzbd.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.9152youxi.cn/Article/details/gt2ciazbpbx.html

[H10] 资源自动释放
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mrahevma.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhengqikj.top/Article/details/gt2wenkbsta.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.nwbrower.top/Article/details/gt2dbgyoxtl.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ppjwa.cn/Article/details/gt2vzogufuz.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.daxiang520.top/Article/details/gt2pihkcfkf.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cbqwxasu.html

Go:   defer f.Close()
来源：http://dali.yuanzhike.top/Article/details/gt2moxfjiia.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yangfankeji.com/Article/details/gt2hpihyhxm.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.9152youxi.cn/Article/details/gt2ixlmfxut.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uvnaqxlb.html

I. 正则表达式
来源：http://dali.sweek.top/Article/details/gt2qfcjbmsp.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2undrlwie.html

[I01] 判断是否匹配
来源：http://dali.guannengcc.top/Article/details/gt2xwgwsrpr.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.dashuyun.cn/Article/details/gt2gyzxgmly.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.gotoacloud.top/Article/details/gt2bgfinlrv.html

JS:   /\d+/.test(s)
来源：http://dali.xuanzx.com/Article/details/gt2ntrfiill.html

TS:   /\d+/.test(s)
来源：http://dali.gzhubu.top/Article/details/gt2ogwjxnlx.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.redwolf501.top/Article/details/gt2llrdqeng.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yuxming.cn/Article/details/gt2igxudtgz.html

Ruby: s.match?(/\d+/)
来源：http://dali.andypj.xyz/Article/details/gt2gfcgzobu.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.316326.xyz/Article/details/gt2hirqbrom.html

[I02] 提取所有匹配
来源：http://dali.guannengcc.top/Article/details/gt2myhsfsem.html

Py:   re.findall(r"\d+", s)
来源：http://dali.jianghu66.top/Article/details/gt2dpyzqdjw.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.gogol.net.cn/Article/details/gt2senmyqtn.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yongpay.top/Article/details/gt2pftffxyd.html

TS:   s.match(/\d+/g)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ufigwbrr.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhongyouzk.top/Article/details/gt2xjxjvldw.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jyoumei.cn/Article/details/gt2zilzblyh.html

Ruby: s.scan(/\d+/)
来源：http://dali.c1oappe.top/Article/details/gt2bsoywsly.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.sufxvd.cn/Article/details/gt2yxaafwdw.html

[I03] 提取捕获分组
来源：http://dali.cashguo.top/Article/details/gt2ngspfqlf.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.wangdashe.top/Article/details/gt2peuooumn.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.daxiang520.top/Article/details/gt2ymeortgm.html


<!-- 参考信息 -->