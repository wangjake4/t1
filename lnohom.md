代发 wailian999

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2tozpqtca.html

TS:   path.extname("a.txt")
来源：http://dali.havefunace.top/Article/details/gt2dsgumgqy.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yj20258.top/Article/details/gt2wgzwsbcu.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.daria6918.cn/Article/details/gt2uzdboiff.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2swveonqg.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.chenzaomai.com/Article/details/gt2hrshzcpb.html

[F11] 复制与移动文件
来源：http://dali.hongshengwenyu.top/Article/details/gt2ltfbgjgu.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2wfwasnmn.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.dianchejie.cn/Article/details/gt2mcsgzkri.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2jyksmatn.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.guannengcc.top/Article/details/gt2zrwsivlp.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.wangdashe.top/Article/details/gt2poodubzy.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jinqigufen.top/Article/details/gt2kvdrdqjt.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yongpay.top/Article/details/gt2xwwruano.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yuanzhike.top/Article/details/gt2cmlvrpob.html

[F12] CSV 读写
来源：http://dali.aizwys.cn/Article/details/gt2qzbdpbrs.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.ppjwa.cn/Article/details/gt2abmjhdvn.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.gaohongyu789.top/Article/details/gt2fwimpiwe.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.9152youxi.cn/Article/details/gt2yuttxtyd.html

TS:   // 同上
来源：http://dali.smart0.xyz/Article/details/gt2xrhczguj.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.sufxvd.cn/Article/details/gt2ddqnnqxb.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.bjfxy.top/Article/details/gt2rkhtgsqg.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.shuidangran.top/Article/details/gt2taldswcn.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.xinyue.icu/Article/details/gt2yvyvzjkl.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2btogfjew.html

G. 面向对象
来源：http://dali.jyoumei.cn/Article/details/gt2cdanfwss.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2rsmxokpw.html

[G01] 定义类
来源：http://dali.tanke756.top/Article/details/gt2kqoxzfsg.html

Py:   class User: pass
来源：http://dali.zdqjudy.top/Article/details/gt2vmgqscbp.html

PHP:  class User {}
来源：http://dali.aibaodan.cn/Article/details/gt2evckxxfv.html

JS:   class User {}
来源：http://dali.zhongyouzk.top/Article/details/gt2nmennoop.html

TS:   class User { name: string = ""; }
来源：http://dali.hysaishi.cn/Article/details/gt2esdqsydj.html

Java: class User {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2csoghzyd.html

Go:   type User struct { Name string }
来源：http://dali.daxiang520.top/Article/details/gt2fkdesfph.html

Ruby: class User; end
来源：http://dali.ydzc1.top/Article/details/gt2jptqcrek.html

C#:   class User {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2cjttxoky.html

[G02] 构造函数
来源：http://dali.ybcxt.top/Article/details/gt2dbmjoxev.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ttltvijk.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.ybcxt.top/Article/details/gt2jcqirsrf.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.guowangkeji.top/Article/details/gt2okxkrqko.html

TS:   constructor(public name: string) {}
来源：http://dali.cheryme.top/Article/details/gt2ochettxo.html

Java: User(String name) { this.name = name; }
来源：http://dali.yuxming.cn/Article/details/gt2vbxfsdax.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bkbgxyqa.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hnqzz.top/Article/details/gt2pyqipzlx.html

C#:   public User(string name) { Name = name; }
来源：http://dali.andypj.xyz/Article/details/gt2xkmnlhux.html

[G03] 实例属性
来源：http://dali.hnxiangtu.top/Article/details/gt2uywmqdqx.html

Py:   self.name = "x"
来源：http://dali.bjfxy.top/Article/details/gt2btjacotq.html

PHP:  public string $name = "x";
来源：http://dali.chenjidiqi.icu/Article/details/gt2xymmvpkl.html

JS:   this.name = "x";
来源：http://dali.jiagoushi.top/Article/details/gt2gmvmruie.html

TS:   name: string = "x";
来源：http://dali.bjfxy.top/Article/details/gt2obrtdiuf.html

Java: private String name;
来源：http://dali.shzxlz.cn/Article/details/gt2awaodcqp.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.xinyue.icu/Article/details/gt2poawynxa.html

Ruby: @name = "x"
来源：http://dali.daria6918.cn/Article/details/gt2eqnojprp.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.hnxiangtu.top/Article/details/gt2zmayjbby.html

[G04] 定义方法
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tiqctlbl.html

Py:   def greet(self): return self.name
来源：http://dali.ivvv.top/Article/details/gt2fjpiaizv.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.xziqi.cn/Article/details/gt2ooifkaej.html

JS:   greet() { return this.name; }
来源：http://dali.gogol.net.cn/Article/details/gt2fpqxybvb.html

TS:   greet(): string { return this.name; }
来源：http://dali.fengsongda.top/Article/details/gt2tjexdscq.html

Java: String greet() { return name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zkoqzozn.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.mhx1999.top/Article/details/gt2cevdyxrn.html

Ruby: def greet; @name; end
来源：http://dali.ivvv.top/Article/details/gt2kcntmqth.html

C#:   public string Greet() => Name;
来源：http://dali.dashuyun.cn/Article/details/gt2guwsdamt.html

[G05] 继承
来源：http://dali.iojbl.cn/Article/details/gt2ocvajjlh.html

Py:   class Admin(User): pass
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xvsvwshz.html

PHP:  class Admin extends User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lntfpbex.html

JS:   class Admin extends User {}
来源：http://dali.zhengqikj.top/Article/details/gt2jqhesuxs.html

TS:   class Admin extends User {}
来源：http://dali.guowangkeji.top/Article/details/gt2zkzlnoku.html

Java: class Admin extends User {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2pkcwotpp.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.chenzaomai.com/Article/details/gt2endixbzj.html

Ruby: class Admin < User; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rmddybnn.html

C#:   class Admin : User {}
来源：http://dali.hammf.cn/Article/details/gt2yztdefyg.html

[G06] 重写方法
来源：http://dali.chenzaomai.com/Article/details/gt2bozxfmcs.html

Py:   def greet(self): return "admin"
来源：http://dali.chenjidiqi.icu/Article/details/gt2kbhwqoiw.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jinqigfzy.top/Article/details/gt2zljmgrjx.html

JS:   greet() { return "admin"; }
来源：http://dali.jlsjyb.cn/Article/details/gt2gulfwmzz.html

TS:   greet(): string { return "admin"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2owruxjpu.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.ivvv.top/Article/details/gt2urexbrms.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.cdnleiting.top/Article/details/gt2vmtrpjhx.html

Ruby: def greet; "admin"; end
来源：http://dali.chenzaomai.com/Article/details/gt2ppdbcwsk.html

C#:   public override string Greet() => "admin";
来源：http://dali.sweek.top/Article/details/gt2rbzlqlkz.html

[G07] 调用父类方法
来源：http://dali.yj20258.top/Article/details/gt2isczhxtl.html

Py:   super().greet()
来源：http://dali.daxiang520.top/Article/details/gt2dlzhdnxi.html

PHP:  parent::greet();
来源：http://dali.jqgufenzy.top/Article/details/gt2tzpqjkev.html

JS:   super.greet();
来源：http://dali.yuxming.cn/Article/details/gt2tuwdnddb.html

TS:   super.greet();
来源：http://dali.cheryme.top/Article/details/gt2bnubktty.html

Java: super.greet();
来源：http://dali.yueranfly.top/Article/details/gt2ahenfegm.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yvedp.cn/Article/details/gt2heokkcof.html

Ruby: super
来源：http://dali.daria6918.cn/Article/details/gt2tlyptshz.html

C#:   base.Greet();
来源：http://dali.quarkkingdee.top/Article/details/gt2ptrddcab.html

[G08] 静态方法与属性
来源：http://dali.aizwys.cn/Article/details/gt2gvqpwdaq.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.cqqwz.cn/Article/details/gt2rhwrbxys.html

PHP:  public static function f() {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2zoirjpil.html

JS:   static f() {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gedkovbs.html

TS:   static f(): void {}
来源：http://dali.yanxiufei.cn/Article/details/gt2pclthumm.html

Java: static void f() {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dwxngozh.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.cucudq.cn/Article/details/gt2ndfihwgb.html

Ruby: def self.f; end
来源：http://dali.tianlin.xyz/Article/details/gt2vznzdzhu.html

C#:   public static void F() {}
来源：http://dali.yanxiufei.cn/Article/details/gt2umdthfoh.html

[G09] 接口 / 抽象类
来源：http://dali.yj20258888.top/Article/details/gt2smpqdhtk.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.birdmap.top/Article/details/gt2jcuvepjm.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jlsjyb.cn/Article/details/gt2zrvjjvai.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zdqjudy.top/Article/details/gt2btmlwvee.html

TS:   interface Shape { area(): number; }
来源：http://dali.xinyue.icu/Article/details/gt2fyldlwpc.html

Java: interface Shape { double area(); }
来源：http://dali.haohaochexian.top/Article/details/gt2kestjipf.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.sysykeji.top/Article/details/gt2kvnffwon.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jqgufenzy.top/Article/details/gt2eejybkqp.html

C#:   interface IShape { double Area(); }
来源：http://dali.gogol.net.cn/Article/details/gt2txnesbfi.html

[G10] 访问控制
来源：http://dali.tian-w.cn/Article/details/gt2bsadwkia.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.hammf.cn/Article/details/gt2ciexsazi.html

PHP:  public / protected / private
来源：http://dali.snrcjt.cn/Article/details/gt2lyflhsam.html

JS:   #private 字段；其余公开
来源：http://dali.jlsjyb.cn/Article/details/gt2bwnltoxo.html

TS:   public / protected / private
来源：http://dali.jiagoushi.top/Article/details/gt2sbbzkpzw.html

Java: public / protected / private / 默认包级
来源：http://dali.yangfankeji.com/Article/details/gt2vzlctnad.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vzdfkugv.html

Ruby: public / protected / private
来源：http://dali.fzhhl.top/Article/details/gt2tmvcuqti.html

C#:   public / protected / private / internal
来源：http://dali.zhoulong.xyz/Article/details/gt2zidrtzxp.html

[G11] getter / setter
来源：http://dali.0kj1m.cn/Article/details/gt2iqykrmvx.html

Py:   @property 与 @x.setter
来源：http://dali.bjfxy.top/Article/details/gt2wpirizpg.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.bjfxy.top/Article/details/gt2bvndetfp.html

JS:   get name() { return this._name; }
来源：http://dali.pycfn.com/Article/details/gt2ywskdyhs.html

TS:   get name(): string { return this._name; }
来源：http://dali.tian-w.cn/Article/details/gt2aoxxcrxr.html

Java: public String getName() { return name; }
来源：http://dali.yangfankeji.com/Article/details/gt2fgkgmzqx.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.birdmap.top/Article/details/gt2kjzejzeu.html

Ruby: attr_accessor :name
来源：http://dali.zhixingplan.top/Article/details/gt2gvevoyck.html

C#:   public string Name { get; set; }
来源：http://dali.mhx1999.top/Article/details/gt2ysvqvlvy.html

[G12] 对象转字符串
来源：http://dali.snrcjt.cn/Article/details/gt2fmpgjefl.html

Py:   def __str__(self): return self.name
来源：http://dali.aizwys.cn/Article/details/gt2wcjmqcgs.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jianghu66.top/Article/details/gt2ptoanhrc.html

JS:   toString() { return this.name; }
来源：http://dali.aizwys.cn/Article/details/gt2rlpdydim.html

TS:   toString(): string { return this.name; }
来源：http://dali.yj20258.top/Article/details/gt2ccftxugr.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhongyouzk.top/Article/details/gt2edslcald.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yj20258888.top/Article/details/gt2wzoysveo.html

Ruby: def to_s; @name; end
来源：http://dali.chenjidiqi.icu/Article/details/gt2vfgujnmr.html

C#:   public override string ToString() => Name;
来源：http://dali.iojbl.cn/Article/details/gt2kakgsbdj.html

[G13] 判断对象类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cyssteyd.html

Py:   isinstance(u, User)
来源：http://dali.dianchejie.cn/Article/details/gt2jrdcoixv.html

PHP:  $u instanceof User
来源：http://dali.yanxiufei.cn/Article/details/gt2mkbnhavt.html

JS:   u instanceof User
来源：http://dali.jinghuilouyu.cn/Article/details/gt2twfjdlnz.html

TS:   u instanceof User
来源：http://dali.dashuyun.cn/Article/details/gt2ivxhmwzj.html

Java: u instanceof User
来源：http://dali.pengpengdd.cyou/Article/details/gt2iparwfka.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.gotoacloud.top/Article/details/gt2loabwcxw.html

Ruby: u.is_a?(User)
来源：http://dali.sysykeji.top/Article/details/gt2ksaktybq.html

C#:   u is User
来源：http://dali.wangdashe.top/Article/details/gt2xclrugsb.html

[G14] 数据类 / record
来源：http://dali.snrcjt.cn/Article/details/gt2fbkbtyko.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.gaohongyu789.top/Article/details/gt2ycbgyzay.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.redwolf501.top/Article/details/gt2jzvzcusk.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.sweek.top/Article/details/gt2thyuggyj.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhengqikj.top/Article/details/gt2vjlzrssz.html

Java: record User(String name, int age) {}
来源：http://dali.tanke756.top/Article/details/gt2xgtwkouu.html

Go:   type User struct { Name string; Age int }
来源：http://dali.daria6918.cn/Article/details/gt2nufvkuxi.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.haohaochexian.top/Article/details/gt2oddnuage.html

C#:   record User(string Name, int Age);
来源：http://dali.aibaodan.cn/Article/details/gt2bopusxky.html

[G15] 枚举
来源：http://dali.ybcxt.top/Article/details/gt2uyspyfrt.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hongshengwenyu.top/Article/details/gt2qenymvby.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.fengsongda.top/Article/details/gt2mhuvayyl.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.kuanghao11.cn/Article/details/gt2gcfhezjh.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhengqikj.top/Article/details/gt2nmbqyxvn.html

Java: enum Color { RED, GREEN }
来源：http://dali.sxryk.cn/Article/details/gt2iwhyxizt.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.9152youxi.cn/Article/details/gt2fhdrzduz.html

Ruby: Color = %i[red green].freeze
来源：http://dali.sweek.top/Article/details/gt2mgieqplk.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinqigufen.top/Article/details/gt2rwcmecxd.html

[G16] 对象转数组 / 字典
来源：http://dali.guannengcc.top/Article/details/gt2ljjawimq.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yangfankeji.com/Article/details/gt2oizhxmhj.html

PHP:  get_object_vars($obj);
来源：http://dali.zhoulong.xyz/Article/details/gt2tizftebd.html

JS:   Object.entries(obj)
来源：http://dali.zdqjudy.top/Article/details/gt2wqfetvdi.html

TS:   Object.entries(obj)
来源：http://dali.jqgufenzy.top/Article/details/gt2efasbakg.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.tanke756.top/Article/details/gt2dycmpdyw.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nyfcdjyv.html

Ruby: obj.instance_variables
来源：http://dali.shuidangran.top/Article/details/gt2dbuyovmx.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zdqjudy.top/Article/details/gt2jkibsmma.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2mhnnmcfy.html

H. 异常与错误处理
来源：http://dali.yj20258.top/Article/details/gt2ituozgqm.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2fignvsmv.html

[H01] try / catch 基础
来源：http://dali.gzhubu.top/Article/details/gt2cqeomolc.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.shzxlz.cn/Article/details/gt2whqjhqhp.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.shuidangran.top/Article/details/gt2zwlwwdhn.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2gouhdcqm.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.smart0.xyz/Article/details/gt2bpymzdbt.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jlsjyb.cn/Article/details/gt2ppxobwba.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.chenzaomai.com/Article/details/gt2njomwsgr.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.hammf.cn/Article/details/gt2cqdwrzay.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hnqzz.top/Article/details/gt2gqqdmjtr.html

[H02] finally / ensure 收尾
来源：http://dali.sweek.top/Article/details/gt2nxdkfcbc.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.havefunace.top/Article/details/gt2vpohcbhl.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.sxryk.cn/Article/details/gt2dqynlbkt.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.guannengcc.top/Article/details/gt2eedzzybu.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinqigufen.top/Article/details/gt2cdzzqlxj.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2qfmeiiqd.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zdqjudy.top/Article/details/gt2nhhifqzf.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.xuanzx.com/Article/details/gt2nantjata.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wdbtlvjj.html

[H03] 主动抛出异常
来源：http://dali.hysaishi.cn/Article/details/gt2pekykefk.html

Py:   raise ValueError("错误信息")
来源：http://dali.pengpengdd.cyou/Article/details/gt2pqnlfecg.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.316326.xyz/Article/details/gt2jesbhdhb.html

JS:   throw new Error("错误信息");
来源：http://dali.meibo888.top/Article/details/gt2abrrypzu.html

TS:   throw new Error("错误信息");
来源：http://dali.zhoulong.xyz/Article/details/gt2tmqvhkpg.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.0kj1m.cn/Article/details/gt2hadagtty.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.guowangkeji.top/Article/details/gt2onxqauug.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.aizwys.cn/Article/details/gt2apkkrsxw.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.svipenyu.cn/Article/details/gt2zvobexkv.html

[H04] 自定义异常类型
来源：http://dali.shzxlz.cn/Article/details/gt2kyyobhev.html

Py:   class MyError(Exception): pass
来源：http://dali.jianghu66.top/Article/details/gt2qxnpxzex.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.gotoacloud.top/Article/details/gt2ksigbiih.html

JS:   class MyError extends Error {}
来源：http://dali.jyoumei.cn/Article/details/gt2qgtdhvus.html

TS:   class MyError extends Error {}
来源：http://dali.hywenlv.cn/Article/details/gt2wciqttvc.html

Java: class MyException extends RuntimeException {}
来源：http://dali.cheryme.top/Article/details/gt2jnipttqw.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.xziqi.cn/Article/details/gt2uyvfjbob.html

Ruby: class MyError < StandardError; end
来源：http://dali.xziqi.cn/Article/details/gt2qsseosso.html

C#:   class MyException : Exception {}
来源：http://dali.yuxming.cn/Article/details/gt2fbvszakm.html

[H05] 捕获特定类型
来源：http://dali.cucudq.cn/Article/details/gt2gumqmdqm.html

Py:   except ValueError as e:
来源：http://dali.cucudq.cn/Article/details/gt2uqqgjnpo.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.xuanzx.com/Article/details/gt2apivtrny.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.meibo888.top/Article/details/gt2ooxuilrv.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jiagoushi.top/Article/details/gt2kcfagrbm.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.smart0.xyz/Article/details/gt2zdxqtixn.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhiwuduotai.top/Article/details/gt2vnpgnyvx.html

Ruby: rescue ArgumentError => e
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vgoxctuq.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.vqdsnc.cn/Article/details/gt2ysdacjgs.html

[H06] 可选值 / 空值安全访问
来源：http://dali.hywenlv.cn/Article/details/gt2yfnkekii.html

Py:   value = d.get("k") or default
来源：http://dali.9152youxi.cn/Article/details/gt2rlvfnqwq.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jqgfzy.top/Article/details/gt2zxaynyft.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.vqdsnc.cn/Article/details/gt2cnorvcxv.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.daxiang520.top/Article/details/gt2umxfxzij.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.wangshuangyany.cn/Article/details/gt2mmftdcws.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.hfpthk.cn/Article/details/gt2ucnkjrfl.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pflclijl.html

C#:   obj?.A?.B ?? default
来源：http://dali.ybcxt.top/Article/details/gt2jkxhfxsc.html

[H07] 断言
来源：http://dali.mhx1999.top/Article/details/gt2tqdfndyd.html

Py:   assert x > 0, "必须为正"
来源：http://dali.havefunace.top/Article/details/gt2fdxhwhxc.html

PHP:  assert($x > 0);
来源：http://dali.chenzaomai.com/Article/details/gt2igvbhjfp.html

JS:   console.assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2sgwviwhu.html

TS:   console.assert(x > 0);
来源：http://dali.ydzc1.top/Article/details/gt2kfzxrlky.html

Java: assert x > 0 : "必须为正";
来源：http://dali.hammf.cn/Article/details/gt2clbddtyy.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.hysaishi.cn/Article/details/gt2lzktipzv.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhixingplan.top/Article/details/gt2flaqgfat.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yongpay.top/Article/details/gt2ntxgzzgv.html

[H08] 获取错误信息与堆栈
来源：http://dali.guannengcc.top/Article/details/gt2sewwtbpe.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yanxiufei.cn/Article/details/gt2irudcqjl.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jqgfzy.top/Article/details/gt2tsvrjafb.html

JS:   e.message;  e.stack
来源：http://dali.yanxiufei.cn/Article/details/gt2lqmytcfe.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.hysaishi.cn/Article/details/gt2bnczselq.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.chenlongwang.top/Article/details/gt2opndfihq.html

Go:   err.Error()
来源：http://dali.havefunace.top/Article/details/gt2gkcklenc.html

Ruby: e.message;  e.backtrace
来源：http://dali.chenzaomai.com/Article/details/gt2pysylbij.html

C#:   e.Message;  e.StackTrace
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pcpcqnhq.html

[H09] 带错误码的异常
来源：http://dali.gotoacloud.top/Article/details/gt2vzlvtxab.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jqgfzy.top/Article/details/gt2smtcxynk.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.kuanghao11.cn/Article/details/gt2mgtbflqw.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yangfankeji.com/Article/details/gt2jhxreotz.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.tianlin.xyz/Article/details/gt2pdqcizhg.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.sweek.top/Article/details/gt2jncuufjc.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.tianlin.xyz/Article/details/gt2yyntkgxx.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.fengsongda.top/Article/details/gt2gcsqjczd.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jyoumei.cn/Article/details/gt2vbpbjsoo.html

[H10] 资源自动释放
来源：http://dali.xinyue.icu/Article/details/gt2dgzsssqw.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.hywenlv.cn/Article/details/gt2jlqmvmax.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jinqigufen.top/Article/details/gt2fvkytsin.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.316326.xyz/Article/details/gt2beyagytf.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yonumen.top/Article/details/gt2xdktcpmm.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.cdnleiting.top/Article/details/gt2rfrtfkzy.html

Go:   defer f.Close()
来源：http://dali.haohaochexian.top/Article/details/gt2vsjurlxk.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jianghu66.top/Article/details/gt2nwqyrwwd.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.0kj1m.cn/Article/details/gt2ohslifok.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2hjfemshd.html

I. 正则表达式
来源：http://dali.jianghu66.top/Article/details/gt2mlqvdsom.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2vnzzcipd.html

[I01] 判断是否匹配
来源：http://dali.jiagoushi.top/Article/details/gt2hmjqvudh.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.shuidangran.top/Article/details/gt2cyyhwcot.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.quarkkingdee.top/Article/details/gt2zpbyscuv.html

JS:   /\d+/.test(s)
来源：http://dali.jqgfzy.top/Article/details/gt2nahaeuqj.html

TS:   /\d+/.test(s)
来源：http://dali.pycfn.com/Article/details/gt2dchherip.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.xuetiantiany.cn/Article/details/gt2hawdtkpn.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.chenzaomai.com/Article/details/gt2arjlzbje.html

Ruby: s.match?(/\d+/)
来源：http://dali.shzxlz.cn/Article/details/gt2nwedzfbx.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.nwbrower.top/Article/details/gt2pvdfhnic.html

[I02] 提取所有匹配
来源：http://dali.daria6918.cn/Article/details/gt2jfcmburd.html

Py:   re.findall(r"\d+", s)
来源：http://dali.hnxiangtu.top/Article/details/gt2zrpqrokj.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.andypj.xyz/Article/details/gt2umbcsibg.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.xuanzx.com/Article/details/gt2pedghgcr.html

TS:   s.match(/\d+/g)
来源：http://dali.jqgfzy.top/Article/details/gt2rifttcma.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2akshggrt.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.havefunace.top/Article/details/gt2kbgooomz.html

Ruby: s.scan(/\d+/)
来源：http://dali.gotoacloud.top/Article/details/gt2auqkxebr.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jinqigfzy.top/Article/details/gt2yqowvsnm.html

[I03] 提取捕获分组
来源：http://dali.zhiwuduotai.top/Article/details/gt2hqzlxxzy.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.nanxinkj.top/Article/details/gt2nupkfnkq.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.svipenyu.cn/Article/details/gt2jobcpndn.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.bjfxy.top/Article/details/gt2zlgzpjzn.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.shanyushiyangtech.top/Article/details/gt2somcijhm.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.ivvv.top/Article/details/gt2idbgvtag.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.xylfe.cn/Article/details/gt2ayeqwswk.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.cqqwz.cn/Article/details/gt2lhyfwxui.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.cucudq.cn/Article/details/gt2byygzmjc.html

[I04] 正则替换
来源：http://dali.shzxlz.cn/Article/details/gt2efcbjihq.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2mkywzicj.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.snrcjt.cn/Article/details/gt2wwinvtxm.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jqgufenzy.top/Article/details/gt2ivitmtrn.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.jinqigufen.top/Article/details/gt2bxkzkixx.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jlsjyb.cn/Article/details/gt2mdhqolbp.html


<!-- 参考信息 -->