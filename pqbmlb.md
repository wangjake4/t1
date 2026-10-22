代发 wailian999

TS:   fs.statSync("a.txt").size
来源：http://dali.guannengcc.top/Article/details/gt2prldzhyu.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.sxryk.cn/Article/details/gt2ojrbsetk.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.bjfxy.top/Article/details/gt2dozhjhou.html

Ruby: File.size("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2evlpurnj.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jqgufenzy.top/Article/details/gt2xorkqkxq.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.ivvv.top/Article/details/gt2hymztjjx.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.bjfxy.top/Article/details/gt2zjgnkgtf.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gt2xcuxnduk.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.dianchejie.cn/Article/details/gt2usxgkonr.html

TS:   path.extname("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gt2enunolws.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.havefunace.top/Article/details/gt2swxmhwlq.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gt2bjuoumru.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.daria6918.cn/Article/details/gt2umfddins.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yuanzhike.top/Article/details/gt2djqnjljx.html

[F11] 复制与移动文件
来源：http://dali.zhongyouzk.top/Article/details/gt2qjiissqm.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.dashuyun.cn/Article/details/gt2uhvytiio.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gt2feiqwcto.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2oaserpll.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2pomlozkb.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.meibo888.top/Article/details/gt2thtntkcb.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.vqdsnc.cn/Article/details/gt2eyswcvtt.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.cucudq.cn/Article/details/gt2wlccvhak.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.havefunace.top/Article/details/gt2oyutdwyp.html

[F12] CSV 读写
来源：http://dali.sxryk.cn/Article/details/gt2lgppiiqs.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2erjbevly.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.chenzaomai.com/Article/details/gt2yndlqnzb.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.sxryk.cn/Article/details/gt2vbeyxcgl.html

TS:   // 同上
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ipbufsfb.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.nanxinkj.top/Article/details/gt2dtlscdsa.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.guowangkeji.top/Article/details/gt2rbzfphyz.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yangfankeji.com/Article/details/gt2pomvgked.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.wangdashe.top/Article/details/gt2vhtbikrq.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2uplmbflg.html

G. 面向对象
来源：http://dali.chenzaomai.com/Article/details/gt2hzkpults.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2uinnshbw.html

[G01] 定义类
来源：http://dali.daria6918.cn/Article/details/gt2fcssiyjz.html

Py:   class User: pass
来源：http://dali.snrcjt.cn/Article/details/gt2xgeinqcb.html

PHP:  class User {}
来源：http://dali.gzhubu.top/Article/details/gt2kyjqbefy.html

JS:   class User {}
来源：http://dali.mhx1999.top/Article/details/gt2zbtqpkez.html

TS:   class User { name: string = ""; }
来源：http://dali.hammf.cn/Article/details/gt2nkcjumlj.html

Java: class User {}
来源：http://dali.svipenyu.cn/Article/details/gt2gwvvtcpt.html

Go:   type User struct { Name string }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lhbxhzht.html

Ruby: class User; end
来源：http://dali.jlsjyb.cn/Article/details/gt2evhuitnt.html

C#:   class User {}
来源：http://dali.bjfxy.top/Article/details/gt2nzykoxku.html

[G02] 构造函数
来源：http://dali.sufxvd.cn/Article/details/gt2banjjcxe.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.smart0.xyz/Article/details/gt2yurecklh.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jianghu66.top/Article/details/gt2sywleddg.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.cucudq.cn/Article/details/gt2xwdtvjtn.html

TS:   constructor(public name: string) {}
来源：http://dali.jqgfzy.top/Article/details/gt2lkvyctoj.html

Java: User(String name) { this.name = name; }
来源：http://dali.bjfxy.top/Article/details/gt2vufzpsue.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.gaohongyu789.top/Article/details/gt2sdatcrnc.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eyejhpej.html

C#:   public User(string name) { Name = name; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2xeicofqg.html

[G03] 实例属性
来源：http://dali.kuanghao11.cn/Article/details/gt2igavmile.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2malcgfcm.html

PHP:  public string $name = "x";
来源：http://dali.chenlongwang.top/Article/details/gt2hjhlzucl.html

JS:   this.name = "x";
来源：http://dali.shuidangran.top/Article/details/gt2dhqqutut.html

TS:   name: string = "x";
来源：http://dali.zdqjudy.top/Article/details/gt2dowioktc.html

Java: private String name;
来源：http://dali.ppjwa.cn/Article/details/gt2ntkfrflc.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.ppjwa.cn/Article/details/gt2mlfgyums.html

Ruby: @name = "x"
来源：http://dali.zdqjudy.top/Article/details/gt2rvlrfate.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yj202588.top/Article/details/gt2aurrrgcq.html

[G04] 定义方法
来源：http://dali.ehwqpu.com/Article/details/gt2fbyixyiv.html

Py:   def greet(self): return self.name
来源：http://dali.hammf.cn/Article/details/gt2dsoqcvvs.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.tian-w.cn/Article/details/gt2wdnlptil.html

JS:   greet() { return this.name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mexesvfu.html

TS:   greet(): string { return this.name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kzbgmvyl.html

Java: String greet() { return name; }
来源：http://dali.cdnleiting.top/Article/details/gt2qqgvlnen.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.chenzaomai.com/Article/details/gt2hrqjvbas.html

Ruby: def greet; @name; end
来源：http://dali.yueranfly.top/Article/details/gt2xsdhloyf.html

C#:   public string Greet() => Name;
来源：http://dali.xuanzx.com/Article/details/gt2cehsekay.html

[G05] 继承
来源：http://dali.zdqjudy.top/Article/details/gt2jdswrekn.html

Py:   class Admin(User): pass
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kqwdspjj.html

PHP:  class Admin extends User {}
来源：http://dali.cdnleiting.top/Article/details/gt2dpvomgov.html

JS:   class Admin extends User {}
来源：http://dali.wangdashe.top/Article/details/gt2hsbfrsrg.html

TS:   class Admin extends User {}
来源：http://dali.iojbl.cn/Article/details/gt2yhckgkey.html

Java: class Admin extends User {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2bdfpbxwp.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.gzhubu.top/Article/details/gt2nwjoiite.html

Ruby: class Admin < User; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hqandamx.html

C#:   class Admin : User {}
来源：http://dali.tian-w.cn/Article/details/gt2szabsmxm.html

[G06] 重写方法
来源：http://dali.sweek.top/Article/details/gt2umcyjgog.html

Py:   def greet(self): return "admin"
来源：http://dali.hnxiangtu.top/Article/details/gt2gvpluwtg.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.316326.xyz/Article/details/gt2zzyljmvt.html

JS:   greet() { return "admin"; }
来源：http://dali.jyoumei.cn/Article/details/gt2bibsldmy.html

TS:   greet(): string { return "admin"; }
来源：http://dali.nanxinkj.top/Article/details/gt2bqlqtcmx.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.svipenyu.cn/Article/details/gt2ylhlryvw.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hammf.cn/Article/details/gt2iercofdf.html

Ruby: def greet; "admin"; end
来源：http://dali.redwolf501.top/Article/details/gt2gmpnmzbn.html

C#:   public override string Greet() => "admin";
来源：http://dali.svipenyu.cn/Article/details/gt2wpvesevn.html

[G07] 调用父类方法
来源：http://dali.yonumen.top/Article/details/gt2bbffpgxw.html

Py:   super().greet()
来源：http://dali.birdmap.top/Article/details/gt2sycsaaql.html

PHP:  parent::greet();
来源：http://dali.aizwys.cn/Article/details/gt2pfsisgjm.html

JS:   super.greet();
来源：http://dali.xinyue.icu/Article/details/gt2kdkolgzq.html

TS:   super.greet();
来源：http://dali.jianghu66.top/Article/details/gt2hozglmle.html

Java: super.greet();
来源：http://dali.dianchejie.cn/Article/details/gt2slyqjbuj.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.ydzc1.top/Article/details/gt2pdilxrqj.html

Ruby: super
来源：http://dali.zhengqikj.top/Article/details/gt2vqrbqfvy.html

C#:   base.Greet();
来源：http://dali.yonumen.top/Article/details/gt2fkceynab.html

[G08] 静态方法与属性
来源：http://dali.xuanzx.com/Article/details/gt2kzxfdjhs.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xuanzx.com/Article/details/gt2kxllskdk.html

PHP:  public static function f() {}
来源：http://dali.haohaochexian.top/Article/details/gt2egcdtzap.html

JS:   static f() {}
来源：http://dali.c1oappe.top/Article/details/gt2fwptnrxc.html

TS:   static f(): void {}
来源：http://dali.nanxinkj.top/Article/details/gt2vlkeptqg.html

Java: static void f() {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2hmaeoheb.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.sxryk.cn/Article/details/gt2zmnzhrkp.html

Ruby: def self.f; end
来源：http://dali.jlsjyb.cn/Article/details/gt2xhgolirg.html

C#:   public static void F() {}
来源：http://dali.zdqjudy.top/Article/details/gt2dsndrkbn.html

[G09] 接口 / 抽象类
来源：http://dali.ppjwa.cn/Article/details/gt2pnvkzpzg.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhijiandao.cn/Article/details/gt2lbcycawi.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.vqdsnc.cn/Article/details/gt2ezdyhmcc.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.svipenyu.cn/Article/details/gt2euwaumay.html

TS:   interface Shape { area(): number; }
来源：http://dali.chenzaomai.com/Article/details/gt2ptkkpsce.html

Java: interface Shape { double area(); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2mgdgslsl.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.cqqwz.cn/Article/details/gt2pdzfqmnp.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.bjfxy.top/Article/details/gt2zafseuea.html

C#:   interface IShape { double Area(); }
来源：http://dali.zycfv.cn/Article/details/gt2waoljcpo.html

[G10] 访问控制
来源：http://dali.jlsjyb.cn/Article/details/gt2vvswdkfm.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yanxiufei.cn/Article/details/gt2itznsfou.html

PHP:  public / protected / private
来源：http://dali.andypj.xyz/Article/details/gt2zikdhsbk.html

JS:   #private 字段；其余公开
来源：http://dali.yonumen.top/Article/details/gt2ehvcfryq.html

TS:   public / protected / private
来源：http://dali.hnxiangtu.top/Article/details/gt2ycwqnjyn.html

Java: public / protected / private / 默认包级
来源：http://dali.sufxvd.cn/Article/details/gt2idsugbok.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.smart0.xyz/Article/details/gt2vkhpynje.html

Ruby: public / protected / private
来源：http://dali.c1oappe.top/Article/details/gt2srxrajbd.html

C#:   public / protected / private / internal
来源：http://dali.snrcjt.cn/Article/details/gt2swkqmgse.html

[G11] getter / setter
来源：http://dali.yuanzhike.top/Article/details/gt2rjknxpio.html

Py:   @property 与 @x.setter
来源：http://dali.zdqjudy.top/Article/details/gt2dsekmlch.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.nanxinkj.top/Article/details/gt2mcrazlox.html

JS:   get name() { return this._name; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2mmknlsmk.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhengqikj.top/Article/details/gt2zlfubvwr.html

Java: public String getName() { return name; }
来源：http://dali.wangdashe.top/Article/details/gt2aiaplafx.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yangfankeji.com/Article/details/gt2nybfsksk.html

Ruby: attr_accessor :name
来源：http://dali.jinqigufen.top/Article/details/gt2iwsyojfp.html

C#:   public string Name { get; set; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2kuizwtyh.html

[G12] 对象转字符串
来源：http://dali.yj202588.top/Article/details/gt2fxoieqwn.html

Py:   def __str__(self): return self.name
来源：http://dali.havefunace.top/Article/details/gt2huphavkf.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.meibo888.top/Article/details/gt2ajzkolfb.html

JS:   toString() { return this.name; }
来源：http://dali.birdmap.top/Article/details/gt2pyjeksya.html

TS:   toString(): string { return this.name; }
来源：http://dali.nwbrower.top/Article/details/gt2zpsjiexg.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhengqikj.top/Article/details/gt2zzaxxljk.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.aizwys.cn/Article/details/gt2klnhhfcl.html

Ruby: def to_s; @name; end
来源：http://dali.yanxiufei.cn/Article/details/gt2fonaffam.html

C#:   public override string ToString() => Name;
来源：http://dali.jinqigufen.top/Article/details/gt2cbisprih.html

[G13] 判断对象类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2whltawla.html

Py:   isinstance(u, User)
来源：http://dali.svipenyu.cn/Article/details/gt2qpeyavcx.html

PHP:  $u instanceof User
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wytvzgtj.html

JS:   u instanceof User
来源：http://dali.nwbrower.top/Article/details/gt2grbbltrv.html

TS:   u instanceof User
来源：http://dali.zhongyouzk.top/Article/details/gt2urnijscq.html

Java: u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2mqqqtsjg.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.gzhubu.top/Article/details/gt2cuxnektc.html

Ruby: u.is_a?(User)
来源：http://dali.gotoacloud.top/Article/details/gt2ivomnzjp.html

C#:   u is User
来源：http://dali.chenzaomai.com/Article/details/gt2xvkhxmez.html

[G14] 数据类 / record
来源：http://dali.yueranfly.top/Article/details/gt2pazsclvl.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.tian-w.cn/Article/details/gt2oaupfovz.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.chenlongwang.top/Article/details/gt2cvfdjvev.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.sysykeji.top/Article/details/gt2ssilnyko.html

TS:   type User = { name: string; age: number };
来源：http://dali.316326.xyz/Article/details/gt2akjgmxfs.html

Java: record User(String name, int age) {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2qmmsryde.html

Go:   type User struct { Name string; Age int }
来源：http://dali.svipenyu.cn/Article/details/gt2qlncfzzl.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yvedp.cn/Article/details/gt2ukxbpjqs.html

C#:   record User(string Name, int Age);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2drpaajzo.html

[G15] 枚举
来源：http://dali.zycfv.cn/Article/details/gt2odrcbfdi.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.xuanzx.com/Article/details/gt2miqrdhxk.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.chenzaomai.com/Article/details/gt2jecybnvl.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.pengpengdd.cyou/Article/details/gt2keqfdhzw.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.feifeiyinyue.top/Article/details/gt2nthketpq.html

Java: enum Color { RED, GREEN }
来源：http://dali.ppjwa.cn/Article/details/gt2xwalexph.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.ppjwa.cn/Article/details/gt2ucadljhk.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jiagoushi.top/Article/details/gt2vsclmtqf.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yvedp.cn/Article/details/gt2laeqyxqc.html

[G16] 对象转数组 / 字典
来源：http://dali.chenjidiqi.icu/Article/details/gt2bguytniw.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.hammf.cn/Article/details/gt2twaspwpm.html

PHP:  get_object_vars($obj);
来源：http://dali.jlsjyb.cn/Article/details/gt2cwbowreh.html

JS:   Object.entries(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ngwblwpq.html

TS:   Object.entries(obj)
来源：http://dali.sweek.top/Article/details/gt2lskjlsfa.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.tian-w.cn/Article/details/gt2dslyjbwc.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.cqqwz.cn/Article/details/gt2mwuqsehm.html

Ruby: obj.instance_variables
来源：http://dali.zhixingplan.top/Article/details/gt2akuyxzjl.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.gogol.net.cn/Article/details/gt2naolkmmt.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2jsoizrkh.html

H. 异常与错误处理
来源：http://dali.iojbl.cn/Article/details/gt2pwybngrz.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2kgbfwbrs.html

[H01] try / catch 基础
来源：http://dali.pycfn.com/Article/details/gt2nliujzta.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.chenjidiqi.icu/Article/details/gt2lobbksas.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.gotoacloud.top/Article/details/gt2ksryqsbo.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.chenzaomai.com/Article/details/gt2yjyhabeg.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.daxiang520.top/Article/details/gt2jhjtzbma.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.andypj.xyz/Article/details/gt2dofhdycc.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hamojebt.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.shzxlz.cn/Article/details/gt2ftrnrcuo.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hfpthk.cn/Article/details/gt2nmkaxfjw.html

[H02] finally / ensure 收尾
来源：http://dali.hammf.cn/Article/details/gt2vcmfrppq.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.dianchejie.cn/Article/details/gt2zudngfcz.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.ivvv.top/Article/details/gt2ilsnujun.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yueranfly.top/Article/details/gt2rnwfffau.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ephtjiel.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2lnokvxch.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jinqigfzy.top/Article/details/gt2czjjsovu.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.sxryk.cn/Article/details/gt2jpihqvyx.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.fzhhl.top/Article/details/gt2rqwxgjlv.html

[H03] 主动抛出异常
来源：http://dali.shanyushiyangtech.top/Article/details/gt2szubigar.html

Py:   raise ValueError("错误信息")
来源：http://dali.jyoumei.cn/Article/details/gt2lbkggrds.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.cqqwz.cn/Article/details/gt2kstfrxwj.html

JS:   throw new Error("错误信息");
来源：http://dali.xinyue.icu/Article/details/gt2slupgrpm.html

TS:   throw new Error("错误信息");
来源：http://dali.dashuyun.cn/Article/details/gt2lbybtdxp.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.nanxinkj.top/Article/details/gt2iozgqgvi.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.guowangkeji.top/Article/details/gt2lsadzhjm.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ijinmuxh.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yongpay.top/Article/details/gt2gtxdimie.html

[H04] 自定义异常类型
来源：http://dali.havefunace.top/Article/details/gt2hmbcbtur.html

Py:   class MyError(Exception): pass
来源：http://dali.nwbrower.top/Article/details/gt2xhbteivs.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.shzxlz.cn/Article/details/gt2lceolrky.html

JS:   class MyError extends Error {}
来源：http://dali.sxryk.cn/Article/details/gt2kxwhqymm.html

TS:   class MyError extends Error {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2uwilkvmb.html

Java: class MyException extends RuntimeException {}
来源：http://dali.dashuyun.cn/Article/details/gt2jzhcdfva.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhengqikj.top/Article/details/gt2yqenetcn.html

Ruby: class MyError < StandardError; end
来源：http://dali.xinyue.icu/Article/details/gt2vjnuuigs.html

C#:   class MyException : Exception {}
来源：http://dali.sysykeji.top/Article/details/gt2lydmkftb.html

[H05] 捕获特定类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yxjgvphx.html

Py:   except ValueError as e:
来源：http://dali.jlsjyb.cn/Article/details/gt2zbhereac.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yueranfly.top/Article/details/gt2rhhfvbhk.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yvedp.cn/Article/details/gt2rvdipjcm.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.andypj.xyz/Article/details/gt2fkyhypqr.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.nwbrower.top/Article/details/gt2wdhjzdvj.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.gzhubu.top/Article/details/gt2exonwmak.html

Ruby: rescue ArgumentError => e
来源：http://dali.nwbrower.top/Article/details/gt2opuxzpvr.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.daria6918.cn/Article/details/gt2kjwdqigz.html

[H06] 可选值 / 空值安全访问
来源：http://dali.sxryk.cn/Article/details/gt2rcudqhlp.html

Py:   value = d.get("k") or default
来源：http://dali.andypj.xyz/Article/details/gt2tweaipwb.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jzussenw.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.nanxinkj.top/Article/details/gt2gdljeovk.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.kuanghao11.cn/Article/details/gt2izrieqnx.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.tianlin.xyz/Article/details/gt2hdwcrpog.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jinqigfzy.top/Article/details/gt2jxfbheub.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yangfankeji.com/Article/details/gt2vvpoinpx.html

C#:   obj?.A?.B ?? default
来源：http://dali.jqgfzy.top/Article/details/gt2vprqvvhq.html

[H07] 断言
来源：http://dali.shangyingyoupin.top/Article/details/gt2wcuieskq.html

Py:   assert x > 0, "必须为正"
来源：http://dali.ybcxt.top/Article/details/gt2deyfjtrh.html

PHP:  assert($x > 0);
来源：http://dali.dashuyun.cn/Article/details/gt2ijiwtwtd.html

JS:   console.assert(x > 0);
来源：http://dali.andypj.xyz/Article/details/gt2qqhiuylj.html

TS:   console.assert(x > 0);
来源：http://dali.jqgfzy.top/Article/details/gt2xtbdhedp.html

Java: assert x > 0 : "必须为正";
来源：http://dali.birdmap.top/Article/details/gt2sdxqnizt.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gbtugbnm.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.quarkkingdee.top/Article/details/gt2dkuotvmw.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yj20258.top/Article/details/gt2qqeffvbs.html

[H08] 获取错误信息与堆栈
来源：http://dali.zycfv.cn/Article/details/gt2qfytuwqb.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.ivvv.top/Article/details/gt2yalmcjbm.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xjrqatkj.html

JS:   e.message;  e.stack
来源：http://dali.zhoulong.xyz/Article/details/gt2uazdrfnw.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yj20258.top/Article/details/gt2ttahewka.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jqgufenzy.top/Article/details/gt2ugplhdck.html

Go:   err.Error()
来源：http://dali.bjfxy.top/Article/details/gt2sotsreni.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhengqikj.top/Article/details/gt2exckyzwr.html

C#:   e.Message;  e.StackTrace
来源：http://dali.cashguo.top/Article/details/gt2okqpvsxf.html

[H09] 带错误码的异常
来源：http://dali.xylfe.cn/Article/details/gt2spkzbnhm.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.0kj1m.cn/Article/details/gt2mcmekqvj.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.pengpengdd.cyou/Article/details/gt2pnkoyhmg.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.daria6918.cn/Article/details/gt2migrpisi.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ykxohvyi.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.ydzc1.top/Article/details/gt2jdujamaz.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.gotoacloud.top/Article/details/gt2jifgpuqs.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2hqflldpp.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.fzhhl.top/Article/details/gt2lqifnbws.html

[H10] 资源自动释放
来源：http://dali.ppjwa.cn/Article/details/gt2uhvvyzrx.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jlsjyb.cn/Article/details/gt2wsxmfdzg.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhengqikj.top/Article/details/gt2ywzmsmum.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yongpay.top/Article/details/gt2flomewuf.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.bjfxy.top/Article/details/gt2hlargvbk.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.hnxiangtu.top/Article/details/gt2itjclbdm.html

Go:   defer f.Close()
来源：http://dali.smart0.xyz/Article/details/gt2pqqxtmni.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yhofbcmh.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.snrcjt.cn/Article/details/gt2qofjlsjs.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2suemgugv.html

I. 正则表达式
来源：http://dali.pycfn.com/Article/details/gt2dwmnppgg.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2tovqecrf.html

[I01] 判断是否匹配
来源：http://dali.xylfe.cn/Article/details/gt2dwrlehqf.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.ybcxt.top/Article/details/gt2efefibge.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.iojbl.cn/Article/details/gt2kdgpulac.html

JS:   /\d+/.test(s)
来源：http://dali.zhoulong.xyz/Article/details/gt2mujlhrtu.html

TS:   /\d+/.test(s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2rqaocxvu.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.yuanzhike.top/Article/details/gt2adextgen.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yongpay.top/Article/details/gt2wrevyadi.html

Ruby: s.match?(/\d+/)
来源：http://dali.kuanghao11.cn/Article/details/gt2ogspmruh.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.hfpthk.cn/Article/details/gt2sjrsgqlu.html

[I02] 提取所有匹配
来源：http://dali.xuanzx.com/Article/details/gt2gfvtzcpp.html

Py:   re.findall(r"\d+", s)
来源：http://dali.sxryk.cn/Article/details/gt2ypejdahm.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.tanke756.top/Article/details/gt2jkmhnkvd.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhiwuduotai.top/Article/details/gt2amggvuef.html

TS:   s.match(/\d+/g)
来源：http://dali.birdmap.top/Article/details/gt2ovwhkicp.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhixingplan.top/Article/details/gt2taksqmbm.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.tanke756.top/Article/details/gt2dddsvziu.html

Ruby: s.scan(/\d+/)
来源：http://dali.jqgfzy.top/Article/details/gt2mdsoozhn.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jinqigfzy.top/Article/details/gt2yhretkgq.html

[I03] 提取捕获分组
来源：http://dali.yongpay.top/Article/details/gt2arvcluju.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.fzhhl.top/Article/details/gt2dcmsrbqi.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.316326.xyz/Article/details/gt2imfkessc.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.sufxvd.cn/Article/details/gt2xmcgjfqf.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.xinyue.icu/Article/details/gt2drnssodm.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eolfbmnr.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.yueranfly.top/Article/details/gt2ycttzzts.html


<!-- 参考信息 -->