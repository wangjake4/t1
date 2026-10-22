代发 wailian999

TS:   fs.statSync("a.txt").size
来源：http://dali.gzhubu.top/Article/details/gt2mkwcmwxs.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.cucudq.cn/Article/details/gt2ehccdczu.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.xuetiantiany.cn/Article/details/gt2tvnzfopq.html

Ruby: File.size("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gt2nytghkcq.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.snrcjt.cn/Article/details/gt2zaiatvib.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.cdnleiting.top/Article/details/gt2rqmzlubv.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.cheryme.top/Article/details/gt2vlrcimdq.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.xylfe.cn/Article/details/gt2zoviquzq.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2rkrakjcq.html

TS:   path.extname("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2segvbtch.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.shangyingyoupin.top/Article/details/gt2owhudmie.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.haohaochexian.top/Article/details/gt2lhhghjlz.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2mcxnromk.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2phvhwhbf.html

[F11] 复制与移动文件
来源：http://dali.ehwqpu.com/Article/details/gt2ocfoiffb.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.daxiang520.top/Article/details/gt2jmlytkqk.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.chenzaomai.com/Article/details/gt2rbbyhqwb.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cqqwz.cn/Article/details/gt2hxnrnrxk.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2clmyaabm.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yuanzhike.top/Article/details/gt2jnljcmza.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.kuanghao11.cn/Article/details/gt2gmoowhna.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2xzopxdif.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.hysaishi.cn/Article/details/gt2jofifbkb.html

[F12] CSV 读写
来源：http://dali.tanke756.top/Article/details/gt2ngcfsnsx.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.svipenyu.cn/Article/details/gt2bgffzbnk.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.9152youxi.cn/Article/details/gt2kltmfohr.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yueranfly.top/Article/details/gt2enrgaeig.html

TS:   // 同上
来源：http://dali.sweek.top/Article/details/gt2kvuqqqxr.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhongyouzk.top/Article/details/gt2rpbsstzl.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.andypj.xyz/Article/details/gt2dqoyrowx.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kqtedzdp.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.feifeiyinyue.top/Article/details/gt2gqwtjopx.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2muomiluc.html

G. 面向对象
来源：http://dali.ivvv.top/Article/details/gt2pvoemcne.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2hjsnbdch.html

[G01] 定义类
来源：http://dali.aizwys.cn/Article/details/gt2zoyovgtc.html

Py:   class User: pass
来源：http://dali.cashguo.top/Article/details/gt2ihqlwrdy.html

PHP:  class User {}
来源：http://dali.redwolf501.top/Article/details/gt2llnfzbqd.html

JS:   class User {}
来源：http://dali.daxiang520.top/Article/details/gt2gufzngbo.html

TS:   class User { name: string = ""; }
来源：http://dali.iojbl.cn/Article/details/gt2uybxatwk.html

Java: class User {}
来源：http://dali.0kj1m.cn/Article/details/gt2xcyyowmr.html

Go:   type User struct { Name string }
来源：http://dali.vqdsnc.cn/Article/details/gt2mkyxoltf.html

Ruby: class User; end
来源：http://dali.dianchejie.cn/Article/details/gt2hzrskblo.html

C#:   class User {}
来源：http://dali.jianghu66.top/Article/details/gt2tuwffbwj.html

[G02] 构造函数
来源：http://dali.snrcjt.cn/Article/details/gt2acbgdwzf.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.cdnleiting.top/Article/details/gt2zobfdsds.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.gotoacloud.top/Article/details/gt2shbojrpr.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yonumen.top/Article/details/gt2jnzxmmoz.html

TS:   constructor(public name: string) {}
来源：http://dali.0kj1m.cn/Article/details/gt2plzourws.html

Java: User(String name) { this.name = name; }
来源：http://dali.xziqi.cn/Article/details/gt2bmhofoaa.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2swfkjtxp.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yj20258888.top/Article/details/gt2bogsergx.html

C#:   public User(string name) { Name = name; }
来源：http://dali.cheryme.top/Article/details/gt2vhddmkon.html

[G03] 实例属性
来源：http://dali.yueranfly.top/Article/details/gt2gptkjcxr.html

Py:   self.name = "x"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gpkjcueg.html

PHP:  public string $name = "x";
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jpmfjsdx.html

JS:   this.name = "x";
来源：http://dali.daria6918.cn/Article/details/gt2gjtmdcmp.html

TS:   name: string = "x";
来源：http://dali.c1oappe.top/Article/details/gt2raauunwt.html

Java: private String name;
来源：http://dali.hywenlv.cn/Article/details/gt2rugdchep.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.snrcjt.cn/Article/details/gt2mhhzqtwm.html

Ruby: @name = "x"
来源：http://dali.iojbl.cn/Article/details/gt2yizdqxpu.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cevqfegr.html

[G04] 定义方法
来源：http://dali.gogol.net.cn/Article/details/gt2jbaxreoi.html

Py:   def greet(self): return self.name
来源：http://dali.xuanzx.com/Article/details/gt2vjgbuplt.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yangfankeji.com/Article/details/gt2etunqlxs.html

JS:   greet() { return this.name; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2lkapjhxs.html

TS:   greet(): string { return this.name; }
来源：http://dali.sysykeji.top/Article/details/gt2cukpskuc.html

Java: String greet() { return name; }
来源：http://dali.nanxinkj.top/Article/details/gt2kbzaalvd.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.smart0.xyz/Article/details/gt2xkgviuqh.html

Ruby: def greet; @name; end
来源：http://dali.guowangkeji.top/Article/details/gt2zyjylwni.html

C#:   public string Greet() => Name;
来源：http://dali.smart0.xyz/Article/details/gt2kybnzfrf.html

[G05] 继承
来源：http://dali.meibo888.top/Article/details/gt2onrylypc.html

Py:   class Admin(User): pass
来源：http://dali.ybcxt.top/Article/details/gt2udwfybmo.html

PHP:  class Admin extends User {}
来源：http://dali.kuanghao11.cn/Article/details/gt2ivvuqzlv.html

JS:   class Admin extends User {}
来源：http://dali.dashuyun.cn/Article/details/gt2hkayxkwh.html

TS:   class Admin extends User {}
来源：http://dali.havefunace.top/Article/details/gt2eanugvoj.html

Java: class Admin extends User {}
来源：http://dali.yongpay.top/Article/details/gt2njweizyx.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.wangdashe.top/Article/details/gt2bkudamnt.html

Ruby: class Admin < User; end
来源：http://dali.yonumen.top/Article/details/gt2aghibwvs.html

C#:   class Admin : User {}
来源：http://dali.0kj1m.cn/Article/details/gt2rcsaybxa.html

[G06] 重写方法
来源：http://dali.fzhhl.top/Article/details/gt2wpwezryo.html

Py:   def greet(self): return "admin"
来源：http://dali.iojbl.cn/Article/details/gt2vbmuqopk.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jyoumei.cn/Article/details/gt2snqpezcv.html

JS:   greet() { return "admin"; }
来源：http://dali.meibo888.top/Article/details/gt2gapcvinr.html

TS:   greet(): string { return "admin"; }
来源：http://dali.xziqi.cn/Article/details/gt2gzwaenav.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.aizwys.cn/Article/details/gt2wwwwqgjm.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yj20258888.top/Article/details/gt2qvhlmtja.html

Ruby: def greet; "admin"; end
来源：http://dali.mhx1999.top/Article/details/gt2tmvrgrid.html

C#:   public override string Greet() => "admin";
来源：http://dali.aizwys.cn/Article/details/gt2apkksboc.html

[G07] 调用父类方法
来源：http://dali.ivvv.top/Article/details/gt2rrsullvp.html

Py:   super().greet()
来源：http://dali.0kj1m.cn/Article/details/gt2mfllpxse.html

PHP:  parent::greet();
来源：http://dali.feifeiyinyue.top/Article/details/gt2uswhgktq.html

JS:   super.greet();
来源：http://dali.birdmap.top/Article/details/gt2ujszrqbb.html

TS:   super.greet();
来源：http://dali.shzxlz.cn/Article/details/gt2iijvorkr.html

Java: super.greet();
来源：http://dali.haohaochexian.top/Article/details/gt2hhcsnemq.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.xuanzx.com/Article/details/gt2ggmfusxh.html

Ruby: super
来源：http://dali.c1oappe.top/Article/details/gt2vovbtwua.html

C#:   base.Greet();
来源：http://dali.wangdashe.top/Article/details/gt2hmlazqcg.html

[G08] 静态方法与属性
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wnchrfpz.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2odhtonsg.html

PHP:  public static function f() {}
来源：http://dali.shuidangran.top/Article/details/gt2saxvaiiu.html

JS:   static f() {}
来源：http://dali.gzhubu.top/Article/details/gt2dmostpdl.html

TS:   static f(): void {}
来源：http://dali.daxiang520.top/Article/details/gt2rmfmtvsw.html

Java: static void f() {}
来源：http://dali.9152youxi.cn/Article/details/gt2kqrrcfox.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.aibaodan.cn/Article/details/gt2opfynlbc.html

Ruby: def self.f; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ryetadth.html

C#:   public static void F() {}
来源：http://dali.xylfe.cn/Article/details/gt2pbjjjbed.html

[G09] 接口 / 抽象类
来源：http://dali.aizwys.cn/Article/details/gt2zylhfjct.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.sysykeji.top/Article/details/gt2ikghwemt.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jinqigfzy.top/Article/details/gt2ifssquic.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yanxiufei.cn/Article/details/gt2xhlcmmqk.html

TS:   interface Shape { area(): number; }
来源：http://dali.wangdashe.top/Article/details/gt2zzhfbrpo.html

Java: interface Shape { double area(); }
来源：http://dali.meibo888.top/Article/details/gt2clqqoaos.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.cucudq.cn/Article/details/gt2qhfeiirw.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.fengsongda.top/Article/details/gt2rgtzzjwm.html

C#:   interface IShape { double Area(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rgoevavm.html

[G10] 访问控制
来源：http://dali.jianghu66.top/Article/details/gt2bhkloirk.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.9152youxi.cn/Article/details/gt2mgcbqstf.html

PHP:  public / protected / private
来源：http://dali.jianghu66.top/Article/details/gt2kuqekqil.html

JS:   #private 字段；其余公开
来源：http://dali.jinqigufen.top/Article/details/gt2zrzcykmc.html

TS:   public / protected / private
来源：http://dali.andypj.xyz/Article/details/gt2pxjgwhik.html

Java: public / protected / private / 默认包级
来源：http://dali.ydzc1.top/Article/details/gt2ipadfjmo.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yvedp.cn/Article/details/gt2oliiabcv.html

Ruby: public / protected / private
来源：http://dali.mhx1999.top/Article/details/gt2eujozqnb.html

C#:   public / protected / private / internal
来源：http://dali.yj202588.top/Article/details/gt2dkvjksax.html

[G11] getter / setter
来源：http://dali.chenlongwang.top/Article/details/gt2wlmpxoke.html

Py:   @property 与 @x.setter
来源：http://dali.gaohongyu789.top/Article/details/gt2gsvstziw.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yj20258.top/Article/details/gt2fhiojldr.html

JS:   get name() { return this._name; }
来源：http://dali.yuxming.cn/Article/details/gt2amshijva.html

TS:   get name(): string { return this._name; }
来源：http://dali.haohaochexian.top/Article/details/gt2jiwhcsmx.html

Java: public String getName() { return name; }
来源：http://dali.ehwqpu.com/Article/details/gt2cwhlibvy.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.chenjidiqi.icu/Article/details/gt2zqltlghu.html

Ruby: attr_accessor :name
来源：http://dali.zhengqikj.top/Article/details/gt2dutoayow.html

C#:   public string Name { get; set; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2skhsnehz.html

[G12] 对象转字符串
来源：http://dali.birdmap.top/Article/details/gt2wdlusmbo.html

Py:   def __str__(self): return self.name
来源：http://dali.fengsongda.top/Article/details/gt2lyqcvqog.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.guannengcc.top/Article/details/gt2czylrqiz.html

JS:   toString() { return this.name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mqcmzdhf.html

TS:   toString(): string { return this.name; }
来源：http://dali.vqdsnc.cn/Article/details/gt2kbgrunnw.html

Java: @Override public String toString() { return name; }
来源：http://dali.chenlongwang.top/Article/details/gt2mcselwas.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yangfankeji.com/Article/details/gt2xamujiam.html

Ruby: def to_s; @name; end
来源：http://dali.birdmap.top/Article/details/gt2aeuccymh.html

C#:   public override string ToString() => Name;
来源：http://dali.yangfankeji.com/Article/details/gt2uuqqlten.html

[G13] 判断对象类型
来源：http://dali.bjfxy.top/Article/details/gt2hhzrsnwn.html

Py:   isinstance(u, User)
来源：http://dali.gzhubu.top/Article/details/gt2ljkajkol.html

PHP:  $u instanceof User
来源：http://dali.jyoumei.cn/Article/details/gt2vodbzznk.html

JS:   u instanceof User
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kfsawpdb.html

TS:   u instanceof User
来源：http://dali.xuetiantiany.cn/Article/details/gt2msersuty.html

Java: u instanceof User
来源：http://dali.snrcjt.cn/Article/details/gt2wabcaomo.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.pycfn.com/Article/details/gt2quvfjstf.html

Ruby: u.is_a?(User)
来源：http://dali.bjfxy.top/Article/details/gt2xertanxf.html

C#:   u is User
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oorvafri.html

[G14] 数据类 / record
来源：http://dali.hnxiangtu.top/Article/details/gt2isxylrbt.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hubeqafn.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nfncmcbn.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhixingplan.top/Article/details/gt2wsbebzzk.html

TS:   type User = { name: string; age: number };
来源：http://dali.shuidangran.top/Article/details/gt2qwrjsfvr.html

Java: record User(String name, int age) {}
来源：http://dali.ydzc1.top/Article/details/gt2fllineup.html

Go:   type User struct { Name string; Age int }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tpacfhxj.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.tanke756.top/Article/details/gt2pkfmcinp.html

C#:   record User(string Name, int Age);
来源：http://dali.hnxiangtu.top/Article/details/gt2qxmzvbrm.html

[G15] 枚举
来源：http://dali.ivvv.top/Article/details/gt2inieigtq.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.guowangkeji.top/Article/details/gt2xewlrjvk.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.bjfxy.top/Article/details/gt2hptwbfbb.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhengqikj.top/Article/details/gt2afauncbe.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hnxiangtu.top/Article/details/gt2wapnvngn.html

Java: enum Color { RED, GREEN }
来源：http://dali.0kj1m.cn/Article/details/gt2jliumegq.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.iojbl.cn/Article/details/gt2uuzsndle.html

Ruby: Color = %i[red green].freeze
来源：http://dali.bjfxy.top/Article/details/gt2hchslfcp.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yj20258.top/Article/details/gt2nzpspvqt.html

[G16] 对象转数组 / 字典
来源：http://dali.snrcjt.cn/Article/details/gt2okvvsjvm.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.aizwys.cn/Article/details/gt2sxjwqnkn.html

PHP:  get_object_vars($obj);
来源：http://dali.daxiang520.top/Article/details/gt2ysoyekmz.html

JS:   Object.entries(obj)
来源：http://dali.tanke756.top/Article/details/gt2tkajsvnh.html

TS:   Object.entries(obj)
来源：http://dali.gaohongyu789.top/Article/details/gt2lqwxwawh.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yueranfly.top/Article/details/gt2eobhdwix.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.redwolf501.top/Article/details/gt2aygcxyak.html

Ruby: obj.instance_variables
来源：http://dali.wangdashe.top/Article/details/gt2cxkcdwvv.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yanxiufei.cn/Article/details/gt2emkedhxq.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2zqcldtdv.html

H. 异常与错误处理
来源：http://dali.quarkkingdee.top/Article/details/gt2sbrzhzen.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2mtcqpsln.html

[H01] try / catch 基础
来源：http://dali.sufxvd.cn/Article/details/gt2xnbhbark.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.dashuyun.cn/Article/details/gt2jiljljav.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.ydzc1.top/Article/details/gt2kwouooub.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.ehwqpu.com/Article/details/gt2mklhgzlx.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.gogol.net.cn/Article/details/gt2zeljfuxu.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.shzxlz.cn/Article/details/gt2gawsiqro.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.feifeiyinyue.top/Article/details/gt2ybkwftrd.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.iojbl.cn/Article/details/gt2frxywerg.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.dashuyun.cn/Article/details/gt2urwsfszo.html

[H02] finally / ensure 收尾
来源：http://dali.aibaodan.cn/Article/details/gt2fnqbgnph.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zycfv.cn/Article/details/gt2txeqtixv.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.tian-w.cn/Article/details/gt2ivfofdaa.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ykyjxumi.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.vqdsnc.cn/Article/details/gt2gnwjpvak.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.guowangkeji.top/Article/details/gt2hbdvcafs.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.gogol.net.cn/Article/details/gt2eqcduikw.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.nanxinkj.top/Article/details/gt2xuqrfloj.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.gzhubu.top/Article/details/gt2wfsdnvqi.html

[H03] 主动抛出异常
来源：http://dali.cdnleiting.top/Article/details/gt2maozbraa.html

Py:   raise ValueError("错误信息")
来源：http://dali.iojbl.cn/Article/details/gt2fsbeeojs.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.smart0.xyz/Article/details/gt2voxblarh.html

JS:   throw new Error("错误信息");
来源：http://dali.hywenlv.cn/Article/details/gt2daemjmxd.html

TS:   throw new Error("错误信息");
来源：http://dali.meibo888.top/Article/details/gt2ldqxakib.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.pycfn.com/Article/details/gt2ctveypnf.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hywenlv.cn/Article/details/gt2rgyvwlja.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hysaishi.cn/Article/details/gt2rjvcocpq.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2xvhyrpuf.html

[H04] 自定义异常类型
来源：http://dali.sxryk.cn/Article/details/gt2thjeiukr.html

Py:   class MyError(Exception): pass
来源：http://dali.shzxlz.cn/Article/details/gt2dbydahlg.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jianghu66.top/Article/details/gt2oyoseexy.html

JS:   class MyError extends Error {}
来源：http://dali.zhoulong.xyz/Article/details/gt2dttmioae.html

TS:   class MyError extends Error {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2hqezazdz.html

Java: class MyException extends RuntimeException {}
来源：http://dali.aizwys.cn/Article/details/gt2xockgyrh.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.tian-w.cn/Article/details/gt2hfzrehge.html

Ruby: class MyError < StandardError; end
来源：http://dali.redwolf501.top/Article/details/gt2zmimxgyh.html

C#:   class MyException : Exception {}
来源：http://dali.svipenyu.cn/Article/details/gt2bshwjtjv.html

[H05] 捕获特定类型
来源：http://dali.xziqi.cn/Article/details/gt2rxsxwgzm.html

Py:   except ValueError as e:
来源：http://dali.yuanzhike.top/Article/details/gt2bjauxpmd.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.tanke756.top/Article/details/gt2mgbsomry.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2bmukotrn.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yonumen.top/Article/details/gt2wygnqkan.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2shsftrqz.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.tianlin.xyz/Article/details/gt2elimgsfo.html

Ruby: rescue ArgumentError => e
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eoiclxlm.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.316326.xyz/Article/details/gt2jkbkynti.html

[H06] 可选值 / 空值安全访问
来源：http://dali.hongshengwenyu.top/Article/details/gt2univehxl.html

Py:   value = d.get("k") or default
来源：http://dali.gzhubu.top/Article/details/gt2jrmawnus.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.cheryme.top/Article/details/gt2ijrslczt.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yj202588.top/Article/details/gt2pbirsiqw.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.shuidangran.top/Article/details/gt2hxykavqj.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.redwolf501.top/Article/details/gt2geouoiiw.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jqgufenzy.top/Article/details/gt2yvfuoyue.html

Ruby: d&.dig(:a, :b)
来源：http://dali.dashuyun.cn/Article/details/gt2oflnuqjw.html

C#:   obj?.A?.B ?? default
来源：http://dali.cheryme.top/Article/details/gt2xuqtkxqs.html

[H07] 断言
来源：http://dali.guannengcc.top/Article/details/gt2bbqhpvoi.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jinqigfzy.top/Article/details/gt2diakmxsp.html

PHP:  assert($x > 0);
来源：http://dali.ybcxt.top/Article/details/gt2jalsekna.html

JS:   console.assert(x > 0);
来源：http://dali.jqgfzy.top/Article/details/gt2afxbwkvl.html

TS:   console.assert(x > 0);
来源：http://dali.dashuyun.cn/Article/details/gt2xyvfllhk.html

Java: assert x > 0 : "必须为正";
来源：http://dali.aizwys.cn/Article/details/gt2rkjghtwv.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.xuetiantiany.cn/Article/details/gt2hdbtlbda.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.mhx1999.top/Article/details/gt2zgdcrikr.html

C#:   Debug.Assert(x > 0);
来源：http://dali.bjfxy.top/Article/details/gt2owsfhvjn.html

[H08] 获取错误信息与堆栈
来源：http://dali.c1oappe.top/Article/details/gt2mgczpafz.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.sxryk.cn/Article/details/gt2lfkzkmtp.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yongpay.top/Article/details/gt2vqpmnuko.html

JS:   e.message;  e.stack
来源：http://dali.ydzc1.top/Article/details/gt2dgoydzsd.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhiwuduotai.top/Article/details/gt2nylxqrzy.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.aizwys.cn/Article/details/gt2qqjxknjx.html

Go:   err.Error()
来源：http://dali.zycfv.cn/Article/details/gt2rnlikltx.html

Ruby: e.message;  e.backtrace
来源：http://dali.daria6918.cn/Article/details/gt2htnvawme.html

C#:   e.Message;  e.StackTrace
来源：http://dali.quarkkingdee.top/Article/details/gt2jredfezf.html

[H09] 带错误码的异常
来源：http://dali.havefunace.top/Article/details/gt2hqsugrno.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.iojbl.cn/Article/details/gt2dfmxbvvb.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jiagoushi.top/Article/details/gt2tzoffuqo.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.xylfe.cn/Article/details/gt2fajaywkm.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.daria6918.cn/Article/details/gt2gpmbqzej.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.ybcxt.top/Article/details/gt2mewugkpp.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.sufxvd.cn/Article/details/gt2gxumrfut.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nuneepus.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yj202588.top/Article/details/gt2jpdbrqim.html

[H10] 资源自动释放
来源：http://dali.zhongyouzk.top/Article/details/gt2qkxwdncn.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.chenzaomai.com/Article/details/gt2sfjwkaab.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.iojbl.cn/Article/details/gt2pgdpvwmd.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.bjfxy.top/Article/details/gt2gpicdjdr.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xuetiantiany.cn/Article/details/gt2fogfzfsg.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.wangdashe.top/Article/details/gt2tpngmznq.html

Go:   defer f.Close()
来源：http://dali.daria6918.cn/Article/details/gt2cbdbupjl.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.nwbrower.top/Article/details/gt2bgbbmabm.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gt2fswdzaxp.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2iseqkbib.html

I. 正则表达式
来源：http://dali.bjfxy.top/Article/details/gt2jyvmmdwo.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2bwhczchi.html

[I01] 判断是否匹配
来源：http://dali.havefunace.top/Article/details/gt2uqzrzcxk.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2vcqtqvtv.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.hywenlv.cn/Article/details/gt2dggixsnx.html

JS:   /\d+/.test(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2qtrpytpq.html

TS:   /\d+/.test(s)
来源：http://dali.fengsongda.top/Article/details/gt2ymuwsvma.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.ydzc1.top/Article/details/gt2rjnixfqt.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.ehwqpu.com/Article/details/gt2qhsylobq.html

Ruby: s.match?(/\d+/)
来源：http://dali.ybcxt.top/Article/details/gt2puchvdxz.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mzzxwxdz.html

[I02] 提取所有匹配
来源：http://dali.cheryme.top/Article/details/gt2ogjznmbr.html

Py:   re.findall(r"\d+", s)
来源：http://dali.sysykeji.top/Article/details/gt2bjfdsyjr.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.ivvv.top/Article/details/gt2nppauoud.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.tanke756.top/Article/details/gt2xeuvnkcs.html

TS:   s.match(/\d+/g)
来源：http://dali.cashguo.top/Article/details/gt2kiirrspy.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yj202588.top/Article/details/gt2aoxdusbm.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.shzxlz.cn/Article/details/gt2dpynupjk.html

Ruby: s.scan(/\d+/)
来源：http://dali.jlsjyb.cn/Article/details/gt2awizgwxx.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.nwbrower.top/Article/details/gt2ikklvxnx.html

[I03] 提取捕获分组
来源：http://dali.iojbl.cn/Article/details/gt2jyqngowb.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.iojbl.cn/Article/details/gt2fyerdwis.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.ppjwa.cn/Article/details/gt2hjxtlisv.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.havefunace.top/Article/details/gt2ujqsmune.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.hywenlv.cn/Article/details/gt2txdnhjnl.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.sysykeji.top/Article/details/gt2dlgrloqx.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.daria6918.cn/Article/details/gt2mmslnsql.html


<!-- 参考信息 -->