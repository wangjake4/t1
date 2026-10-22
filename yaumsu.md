代发 wailian999

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2cvamufvw.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gt2clgcyvlu.html

[F11] 复制与移动文件
来源：http://dali.quarkkingdee.top/Article/details/gt2lkeddbfd.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.pycfn.com/Article/details/gt2lklibpww.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.wangdashe.top/Article/details/gt2vvftsbmk.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.havefunace.top/Article/details/gt2wpkytfns.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2shwksqqy.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.daxiang520.top/Article/details/gt2jzkrvdyj.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.gogol.net.cn/Article/details/gt2bgbxhtfb.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.guannengcc.top/Article/details/gt2eiqrgotm.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.iojbl.cn/Article/details/gt2cnaqdjkm.html

[F12] CSV 读写
来源：http://dali.vqdsnc.cn/Article/details/gt2jmpdccxz.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.sxryk.cn/Article/details/gt2rzzwwvuu.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yj202588.top/Article/details/gt2anhtjayy.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rdphcmvy.html

TS:   // 同上
来源：http://dali.quarkkingdee.top/Article/details/gt2glyefidm.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jinqigufen.top/Article/details/gt2gmbgyvff.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.gzhubu.top/Article/details/gt2omiqwkng.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhoulong.xyz/Article/details/gt2wauiwpta.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.cheryme.top/Article/details/gt2pdbpkxsv.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2yuhwlkyu.html

G. 面向对象
来源：http://dali.quarkkingdee.top/Article/details/gt2xbybeqrh.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2pydqsumd.html

[G01] 定义类
来源：http://dali.jianghu66.top/Article/details/gt2fvwkfbwf.html

Py:   class User: pass
来源：http://dali.sxryk.cn/Article/details/gt2cxnvslem.html

PHP:  class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2unkrataj.html

JS:   class User {}
来源：http://dali.bjfxy.top/Article/details/gt2pmdxpvwk.html

TS:   class User { name: string = ""; }
来源：http://dali.quarkkingdee.top/Article/details/gt2jqfvjawv.html

Java: class User {}
来源：http://dali.ehwqpu.com/Article/details/gt2dwokleaz.html

Go:   type User struct { Name string }
来源：http://dali.daria6918.cn/Article/details/gt2mhzltoza.html

Ruby: class User; end
来源：http://dali.haohaochexian.top/Article/details/gt2ygtwxiqj.html

C#:   class User {}
来源：http://dali.dashuyun.cn/Article/details/gt2nxpkkcqt.html

[G02] 构造函数
来源：http://dali.andypj.xyz/Article/details/gt2rfgvvqgu.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.c1oappe.top/Article/details/gt2jprcwsfx.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.xziqi.cn/Article/details/gt2dxldzxuo.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.guannengcc.top/Article/details/gt2pbcwmpzi.html

TS:   constructor(public name: string) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2djnehosr.html

Java: User(String name) { this.name = name; }
来源：http://dali.sufxvd.cn/Article/details/gt2ynpcxirx.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yuanzhike.top/Article/details/gt2nlwhvteb.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.vqdsnc.cn/Article/details/gt2qznaaihq.html

C#:   public User(string name) { Name = name; }
来源：http://dali.fzhhl.top/Article/details/gt2gudujnuu.html

[G03] 实例属性
来源：http://dali.jinqigfzy.top/Article/details/gt2xsdphncc.html

Py:   self.name = "x"
来源：http://dali.snrcjt.cn/Article/details/gt2genwwuhb.html

PHP:  public string $name = "x";
来源：http://dali.jinqigfzy.top/Article/details/gt2bpievyxw.html

JS:   this.name = "x";
来源：http://dali.tanke756.top/Article/details/gt2yocfqczv.html

TS:   name: string = "x";
来源：http://dali.havefunace.top/Article/details/gt2ccfwlixq.html

Java: private String name;
来源：http://dali.shuidangran.top/Article/details/gt2pjsqtfwg.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2imvercpv.html

Ruby: @name = "x"
来源：http://dali.sxryk.cn/Article/details/gt2zktcveck.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jinqigfzy.top/Article/details/gt2vmumbica.html

[G04] 定义方法
来源：http://dali.dashuyun.cn/Article/details/gt2yboslgpe.html

Py:   def greet(self): return self.name
来源：http://dali.ydzc1.top/Article/details/gt2xcqaskps.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhongyouzk.top/Article/details/gt2gxvadfnx.html

JS:   greet() { return this.name; }
来源：http://dali.hammf.cn/Article/details/gt2aithsdxm.html

TS:   greet(): string { return this.name; }
来源：http://dali.sysykeji.top/Article/details/gt2mjbklogh.html

Java: String greet() { return name; }
来源：http://dali.redwolf501.top/Article/details/gt2tsbvyynd.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.mhx1999.top/Article/details/gt2weabbgid.html

Ruby: def greet; @name; end
来源：http://dali.daria6918.cn/Article/details/gt2oiwpwecx.html

C#:   public string Greet() => Name;
来源：http://dali.sxryk.cn/Article/details/gt2qxgbiznm.html

[G05] 继承
来源：http://dali.cqqwz.cn/Article/details/gt2ipbpwlae.html

Py:   class Admin(User): pass
来源：http://dali.fengsongda.top/Article/details/gt2jaibrksj.html

PHP:  class Admin extends User {}
来源：http://dali.redwolf501.top/Article/details/gt2inrjcwei.html

JS:   class Admin extends User {}
来源：http://dali.xinyue.icu/Article/details/gt2ugvxuvzm.html

TS:   class Admin extends User {}
来源：http://dali.gzhubu.top/Article/details/gt2kklcydve.html

Java: class Admin extends User {}
来源：http://dali.xziqi.cn/Article/details/gt2pspnxbrv.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.gaohongyu789.top/Article/details/gt2mxivxsfs.html

Ruby: class Admin < User; end
来源：http://dali.tanke756.top/Article/details/gt2hkgxxiva.html

C#:   class Admin : User {}
来源：http://dali.pycfn.com/Article/details/gt2elbfilos.html

[G06] 重写方法
来源：http://dali.zdqjudy.top/Article/details/gt2cacdyyan.html

Py:   def greet(self): return "admin"
来源：http://dali.wangdashe.top/Article/details/gt2fwhqgehk.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.ybcxt.top/Article/details/gt2nxzjzlrj.html

JS:   greet() { return "admin"; }
来源：http://dali.tian-w.cn/Article/details/gt2scnzddoq.html

TS:   greet(): string { return "admin"; }
来源：http://dali.fzhhl.top/Article/details/gt2afekzjly.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhoulong.xyz/Article/details/gt2vhtjsebb.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yanxiufei.cn/Article/details/gt2vwywqesf.html

Ruby: def greet; "admin"; end
来源：http://dali.jiagoushi.top/Article/details/gt2fkbybarr.html

C#:   public override string Greet() => "admin";
来源：http://dali.hnqzz.top/Article/details/gt2lessngvo.html

[G07] 调用父类方法
来源：http://dali.jiagoushi.top/Article/details/gt2oclaxlcs.html

Py:   super().greet()
来源：http://dali.xylfe.cn/Article/details/gt2esprodld.html

PHP:  parent::greet();
来源：http://dali.bjfxy.top/Article/details/gt2hgqaugmv.html

JS:   super.greet();
来源：http://dali.smart0.xyz/Article/details/gt2hewurylk.html

TS:   super.greet();
来源：http://dali.ybcxt.top/Article/details/gt2mdxonyvj.html

Java: super.greet();
来源：http://dali.meibo888.top/Article/details/gt2ryebwgen.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.shuidangran.top/Article/details/gt2gjtfbjoq.html

Ruby: super
来源：http://dali.0kj1m.cn/Article/details/gt2bsltdfaq.html

C#:   base.Greet();
来源：http://dali.zhiwuduotai.top/Article/details/gt2zwqbowxz.html

[G08] 静态方法与属性
来源：http://dali.ehwqpu.com/Article/details/gt2gzeuvmij.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.chenlongwang.top/Article/details/gt2hahfcaug.html

PHP:  public static function f() {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2zszdotda.html

JS:   static f() {}
来源：http://dali.aibaodan.cn/Article/details/gt2wpzfoyek.html

TS:   static f(): void {}
来源：http://dali.zhongyouzk.top/Article/details/gt2xfuqlktt.html

Java: static void f() {}
来源：http://dali.dashuyun.cn/Article/details/gt2crvuhelm.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.dashuyun.cn/Article/details/gt2jzumfuol.html

Ruby: def self.f; end
来源：http://dali.dianchejie.cn/Article/details/gt2goyqndyx.html

C#:   public static void F() {}
来源：http://dali.cashguo.top/Article/details/gt2pcsaexpi.html

[G09] 接口 / 抽象类
来源：http://dali.smart0.xyz/Article/details/gt2rqjorfpg.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vrnbhpgt.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.wangdashe.top/Article/details/gt2hwkdwgvm.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.sufxvd.cn/Article/details/gt2utxkyyuo.html

TS:   interface Shape { area(): number; }
来源：http://dali.xylfe.cn/Article/details/gt2rhssmmkf.html

Java: interface Shape { double area(); }
来源：http://dali.cucudq.cn/Article/details/gt2begovejd.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.vqdsnc.cn/Article/details/gt2zhczjrkl.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.wangshuangyany.cn/Article/details/gt2geepkwuz.html

C#:   interface IShape { double Area(); }
来源：http://dali.guannengcc.top/Article/details/gt2qzjrqdpt.html

[G10] 访问控制
来源：http://dali.svipenyu.cn/Article/details/gt2dihlhdfx.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.hywenlv.cn/Article/details/gt2ibkwjwen.html

PHP:  public / protected / private
来源：http://dali.jinqigfzy.top/Article/details/gt2yxhczwgo.html

JS:   #private 字段；其余公开
来源：http://dali.cheryme.top/Article/details/gt2pmbecglc.html

TS:   public / protected / private
来源：http://dali.gaohongyu789.top/Article/details/gt2zvszlrws.html

Java: public / protected / private / 默认包级
来源：http://dali.xylfe.cn/Article/details/gt2gghschge.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xuetiantiany.cn/Article/details/gt2mmuhlzwk.html

Ruby: public / protected / private
来源：http://dali.9152youxi.cn/Article/details/gt2xdtlxcat.html

C#:   public / protected / private / internal
来源：http://dali.xuanzx.com/Article/details/gt2xkoxfjkd.html

[G11] getter / setter
来源：http://dali.haohaochexian.top/Article/details/gt2katrnnhr.html

Py:   @property 与 @x.setter
来源：http://dali.gotoacloud.top/Article/details/gt2bgswhyqy.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.gogol.net.cn/Article/details/gt2igipqzrk.html

JS:   get name() { return this._name; }
来源：http://dali.cdnleiting.top/Article/details/gt2vkjxligv.html

TS:   get name(): string { return this._name; }
来源：http://dali.snrcjt.cn/Article/details/gt2nakgkxfx.html

Java: public String getName() { return name; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2husxwiau.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.gaohongyu789.top/Article/details/gt2isyjqzuu.html

Ruby: attr_accessor :name
来源：http://dali.shzxlz.cn/Article/details/gt2fegkfnqe.html

C#:   public string Name { get; set; }
来源：http://dali.yvedp.cn/Article/details/gt2kshkotos.html

[G12] 对象转字符串
来源：http://dali.cheryme.top/Article/details/gt2pfpkcryy.html

Py:   def __str__(self): return self.name
来源：http://dali.gotoacloud.top/Article/details/gt2xrrwsdzv.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yuxming.cn/Article/details/gt2xsmiotka.html

JS:   toString() { return this.name; }
来源：http://dali.hnxiangtu.top/Article/details/gt2oxgdkvsa.html

TS:   toString(): string { return this.name; }
来源：http://dali.yonumen.top/Article/details/gt2auogypav.html

Java: @Override public String toString() { return name; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2yyzxkncz.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hysaishi.cn/Article/details/gt2fstezufr.html

Ruby: def to_s; @name; end
来源：http://dali.gaohongyu789.top/Article/details/gt2vfbgxbsn.html

C#:   public override string ToString() => Name;
来源：http://dali.daxiang520.top/Article/details/gt2cymyxctd.html

[G13] 判断对象类型
来源：http://dali.cheryme.top/Article/details/gt2snyashgl.html

Py:   isinstance(u, User)
来源：http://dali.zhijiandao.cn/Article/details/gt2ikiwzfsb.html

PHP:  $u instanceof User
来源：http://dali.quarkkingdee.top/Article/details/gt2sqrklbhh.html

JS:   u instanceof User
来源：http://dali.hnqzz.top/Article/details/gt2iiutdhag.html

TS:   u instanceof User
来源：http://dali.gogol.net.cn/Article/details/gt2hsxybofc.html

Java: u instanceof User
来源：http://dali.tanke756.top/Article/details/gt2axxzqjxl.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.cashguo.top/Article/details/gt2wizftebr.html

Ruby: u.is_a?(User)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bkvbnilk.html

C#:   u is User
来源：http://dali.svipenyu.cn/Article/details/gt2biokfwnu.html

[G14] 数据类 / record
来源：http://dali.yuxming.cn/Article/details/gt2zxdezrvx.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qeskethw.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yj202588.top/Article/details/gt2hxepoitr.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.gzhubu.top/Article/details/gt2eezszjgx.html

TS:   type User = { name: string; age: number };
来源：http://dali.haohaochexian.top/Article/details/gt2odqfpxzx.html

Java: record User(String name, int age) {}
来源：http://dali.chenlongwang.top/Article/details/gt2hizoqgxr.html

Go:   type User struct { Name string; Age int }
来源：http://dali.nanxinkj.top/Article/details/gt2jkzvlaxn.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yongpay.top/Article/details/gt2fghkktvt.html

C#:   record User(string Name, int Age);
来源：http://dali.feifeiyinyue.top/Article/details/gt2bxzramlq.html

[G15] 枚举
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fkzfoxye.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.chenzaomai.com/Article/details/gt2cyvkhrjs.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.vqdsnc.cn/Article/details/gt2tcevyawv.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.tianlin.xyz/Article/details/gt2yubbibbm.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gotoacloud.top/Article/details/gt2ucrthhgq.html

Java: enum Color { RED, GREEN }
来源：http://dali.shuidangran.top/Article/details/gt2jaslkabu.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.sweek.top/Article/details/gt2wqcnvgkt.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yangfankeji.com/Article/details/gt2ebczcshb.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.tanke756.top/Article/details/gt2amtpibdy.html

[G16] 对象转数组 / 字典
来源：http://dali.zycfv.cn/Article/details/gt2ddvkekul.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.ppjwa.cn/Article/details/gt2btchbxfm.html

PHP:  get_object_vars($obj);
来源：http://dali.ehwqpu.com/Article/details/gt2tfapxqfk.html

JS:   Object.entries(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ajyvlrjg.html

TS:   Object.entries(obj)
来源：http://dali.svipenyu.cn/Article/details/gt2zmvbcsqd.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.xziqi.cn/Article/details/gt2ajpjexog.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.sxryk.cn/Article/details/gt2nmfzkpfm.html

Ruby: obj.instance_variables
来源：http://dali.gzhubu.top/Article/details/gt2stvfqvtp.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.quarkkingdee.top/Article/details/gt2zxzjejpa.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2wgqgaiye.html

H. 异常与错误处理
来源：http://dali.cdnleiting.top/Article/details/gt2nfnhpjjg.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2jhkrycpw.html

[H01] try / catch 基础
来源：http://dali.zycfv.cn/Article/details/gt2sryqazch.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.sufxvd.cn/Article/details/gt2fadktadq.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.dianchejie.cn/Article/details/gt2dxhcuafb.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.sysykeji.top/Article/details/gt2lwfatnde.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.bjfxy.top/Article/details/gt2hilkwudf.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhongyouzk.top/Article/details/gt2bzkvjdii.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.nanxinkj.top/Article/details/gt2wqknjhcn.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.svipenyu.cn/Article/details/gt2salaqqhr.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jyoumei.cn/Article/details/gt2dxpnzoqu.html

[H02] finally / ensure 收尾
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yjnqgywk.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zdqjudy.top/Article/details/gt2psvpuici.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2ftdxajor.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zycfv.cn/Article/details/gt2vderipqg.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2bkyjugfe.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.redwolf501.top/Article/details/gt2neatrplk.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.bjfxy.top/Article/details/gt2wijrpicw.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.ehwqpu.com/Article/details/gt2jrkcqvwg.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.chenlongwang.top/Article/details/gt2lfctbtog.html

[H03] 主动抛出异常
来源：http://dali.birdmap.top/Article/details/gt2fjgvkmro.html

Py:   raise ValueError("错误信息")
来源：http://dali.xinyue.icu/Article/details/gt2yaaopkcz.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.quarkkingdee.top/Article/details/gt2drsjeofr.html

JS:   throw new Error("错误信息");
来源：http://dali.bjfxy.top/Article/details/gt2adplfxfc.html

TS:   throw new Error("错误信息");
来源：http://dali.xinyue.icu/Article/details/gt2rpykusow.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.sufxvd.cn/Article/details/gt2arcjlxnn.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.sysykeji.top/Article/details/gt2jpbchnnv.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.cqqwz.cn/Article/details/gt2edabzmez.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yj202588.top/Article/details/gt2wilyydwp.html

[H04] 自定义异常类型
来源：http://dali.jqgfzy.top/Article/details/gt2qpegdiqc.html

Py:   class MyError(Exception): pass
来源：http://dali.ybcxt.top/Article/details/gt2wgjvsxso.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.tian-w.cn/Article/details/gt2zowcbygv.html

JS:   class MyError extends Error {}
来源：http://dali.jianghu66.top/Article/details/gt2elczugrl.html

TS:   class MyError extends Error {}
来源：http://dali.hfpthk.cn/Article/details/gt2lhfjvxcf.html

Java: class MyException extends RuntimeException {}
来源：http://dali.ydzc1.top/Article/details/gt2tpwmhqzq.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.aibaodan.cn/Article/details/gt2gmvavorg.html

Ruby: class MyError < StandardError; end
来源：http://dali.shuidangran.top/Article/details/gt2ffvinsmv.html

C#:   class MyException : Exception {}
来源：http://dali.wangdashe.top/Article/details/gt2yfbmjxek.html

[H05] 捕获特定类型
来源：http://dali.yuanzhike.top/Article/details/gt2tpighmpl.html

Py:   except ValueError as e:
来源：http://dali.pengpengdd.cyou/Article/details/gt2cdpugbvh.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.sysykeji.top/Article/details/gt2tovwlawe.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.aizwys.cn/Article/details/gt2ygpnfqwo.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.tanke756.top/Article/details/gt2aktdlmym.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dcrwgmfa.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.daxiang520.top/Article/details/gt2hcpopdjo.html

Ruby: rescue ArgumentError => e
来源：http://dali.gogol.net.cn/Article/details/gt2ednbknby.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yonumen.top/Article/details/gt2hwtqxlze.html

[H06] 可选值 / 空值安全访问
来源：http://dali.fzhhl.top/Article/details/gt2nlxuzuvr.html

Py:   value = d.get("k") or default
来源：http://dali.xuanzx.com/Article/details/gt2brmboffr.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.xuetiantiany.cn/Article/details/gt2haeutevq.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.xylfe.cn/Article/details/gt2sfolpucq.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.kuanghao11.cn/Article/details/gt2qzmlhhtb.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gt2etzkywui.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yjvagbud.html

Ruby: d&.dig(:a, :b)
来源：http://dali.nwbrower.top/Article/details/gt2kvhepjmi.html

C#:   obj?.A?.B ?? default
来源：http://dali.dashuyun.cn/Article/details/gt2hovijklo.html

[H07] 断言
来源：http://dali.ehwqpu.com/Article/details/gt2nbkymtgo.html

Py:   assert x > 0, "必须为正"
来源：http://dali.gaohongyu789.top/Article/details/gt2fwbcceuc.html

PHP:  assert($x > 0);
来源：http://dali.tianlin.xyz/Article/details/gt2vpweaorl.html

JS:   console.assert(x > 0);
来源：http://dali.tianlin.xyz/Article/details/gt2faslttoy.html

TS:   console.assert(x > 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2izlznbeq.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhengqikj.top/Article/details/gt2xcpzujjn.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.hnqzz.top/Article/details/gt2bzrrcdtt.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.pycfn.com/Article/details/gt2gbxppowk.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jinqigfzy.top/Article/details/gt2fntjmidj.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhiwuduotai.top/Article/details/gt2iyatqcph.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.sxryk.cn/Article/details/gt2kywopyhd.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.xinyue.icu/Article/details/gt2cqwvyjuy.html

JS:   e.message;  e.stack
来源：http://dali.cdnleiting.top/Article/details/gt2wxxuqduv.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.meibo888.top/Article/details/gt2antckeft.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.sweek.top/Article/details/gt2qnerkrwg.html

Go:   err.Error()
来源：http://dali.redwolf501.top/Article/details/gt2zoqptzqy.html

Ruby: e.message;  e.backtrace
来源：http://dali.guannengcc.top/Article/details/gt2pabvgczk.html

C#:   e.Message;  e.StackTrace
来源：http://dali.aizwys.cn/Article/details/gt2nltbltri.html

[H09] 带错误码的异常
来源：http://dali.yueranfly.top/Article/details/gt2knzdmtva.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.aibaodan.cn/Article/details/gt2omfnhzcf.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.ybcxt.top/Article/details/gt2vkwuuttw.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.pycfn.com/Article/details/gt2smozujpu.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.tianlin.xyz/Article/details/gt2ddfgzytt.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.316326.xyz/Article/details/gt2otmuucqr.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.gzhubu.top/Article/details/gt2lphgbuhj.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.bjfxy.top/Article/details/gt2gebdlftq.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.gzhubu.top/Article/details/gt2nngoussa.html

[H10] 资源自动释放
来源：http://dali.sweek.top/Article/details/gt2jaszsift.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.daria6918.cn/Article/details/gt2npfganlb.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.cucudq.cn/Article/details/gt2znzsdnbe.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jianghu66.top/Article/details/gt2rsyxzhha.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.9152youxi.cn/Article/details/gt2ovksrpwm.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.9152youxi.cn/Article/details/gt2ifuhpmut.html

Go:   defer f.Close()
来源：http://dali.sufxvd.cn/Article/details/gt2noeqknut.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.cucudq.cn/Article/details/gt2wrzdqhim.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gt2cfksubwd.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2xkmhgdwf.html

I. 正则表达式
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wpcgngrw.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2pphzybwe.html

[I01] 判断是否匹配
来源：http://dali.vqdsnc.cn/Article/details/gt2tsyscrtx.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2pszzpqgi.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.smart0.xyz/Article/details/gt2gccikeqz.html

JS:   /\d+/.test(s)
来源：http://dali.fzhhl.top/Article/details/gt2cexsvbdb.html

TS:   /\d+/.test(s)
来源：http://dali.yanxiufei.cn/Article/details/gt2dxalused.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.ybcxt.top/Article/details/gt2ehvpnwsw.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yj20258.top/Article/details/gt2dwnmjraq.html

Ruby: s.match?(/\d+/)
来源：http://dali.sufxvd.cn/Article/details/gt2tqmmrfpx.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yj20258888.top/Article/details/gt2ulngjghv.html

[I02] 提取所有匹配
来源：http://dali.hnxiangtu.top/Article/details/gt2lsbyhulj.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yuxming.cn/Article/details/gt2qeksvrdx.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.sufxvd.cn/Article/details/gt2ifvojhug.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jiagoushi.top/Article/details/gt2fmsaibfv.html

TS:   s.match(/\d+/g)
来源：http://dali.pengpengdd.cyou/Article/details/gt2lkhtmocc.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.chenjidiqi.icu/Article/details/gt2jslzgmyu.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.nanxuanxn.top/Article/details/gt2rashmmqv.html

Ruby: s.scan(/\d+/)
来源：http://dali.wangshuangyany.cn/Article/details/gt2foxadetp.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jqgufenzy.top/Article/details/gt2hncgtdzw.html

[I03] 提取捕获分组
来源：http://dali.wangdashe.top/Article/details/gt2acapstjz.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2fwecujvo.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.andypj.xyz/Article/details/gt2xavjqfwl.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.nwbrower.top/Article/details/gt2jpzfxfyi.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.jqgfzy.top/Article/details/gt2mcvgiyng.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.guowangkeji.top/Article/details/gt2lmgdvtiv.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.hammf.cn/Article/details/gt2jfcrwlir.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dzgwbtsi.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.hfpthk.cn/Article/details/gt2deeoxncz.html

[I04] 正则替换
来源：http://dali.jlsjyb.cn/Article/details/gt2yufwgcpr.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.ybcxt.top/Article/details/gt2lfpozglp.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.andypj.xyz/Article/details/gt2tcbmigqp.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.xinyue.icu/Article/details/gt2igstfhso.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.guannengcc.top/Article/details/gt2evzxkham.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jinqigufen.top/Article/details/gt2mqlozrfz.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.xuetiantiany.cn/Article/details/gt2wuazqapw.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.shuidangran.top/Article/details/gt2rcwxkzoc.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yj20258.top/Article/details/gt2vcdjbgww.html

[I05] 按正则拆分
来源：http://dali.yuanzhike.top/Article/details/gt2gmpxnvuw.html


<!-- 参考信息 -->