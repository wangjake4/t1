代发 wailian999

C#:   new FileInfo("a.txt").Length
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hjfstzju.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.gzhubu.top/Article/details/gt2rkoxsklo.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2dilcteav.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wcacjazf.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2yvvsvtbc.html

TS:   path.extname("a.txt")
来源：http://dali.c1oappe.top/Article/details/gt2mhwprjyr.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jqgfzy.top/Article/details/gt2tzmynvhs.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.andypj.xyz/Article/details/gt2uptsuadr.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2evtwbpno.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2btyfimuf.html

[F11] 复制与移动文件
来源：http://dali.quarkkingdee.top/Article/details/gt2zilnkfau.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hysaishi.cn/Article/details/gt2ogpadwsa.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.sufxvd.cn/Article/details/gt2fnpzgtaq.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yanxiufei.cn/Article/details/gt2xwyeukey.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gogol.net.cn/Article/details/gt2ahblflzl.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.quarkkingdee.top/Article/details/gt2mqqaajzc.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.aibaodan.cn/Article/details/gt2ssazjdrz.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.xuanzx.com/Article/details/gt2wfpcgsqx.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.xinyue.icu/Article/details/gt2fzjifxvz.html

[F12] CSV 读写
来源：http://dali.yvedp.cn/Article/details/gt2kkyqcvwr.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.shangyingyoupin.top/Article/details/gt2lvcmdxsv.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhoulong.xyz/Article/details/gt2kmgzpgvp.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zdqjudy.top/Article/details/gt2hijxxceh.html

TS:   // 同上
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fwqodnob.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhijiandao.cn/Article/details/gt2uarsaaqs.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.chenzaomai.com/Article/details/gt2nhxvupgd.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yj20258.top/Article/details/gt2aoucgvzw.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hnqzz.top/Article/details/gt2ltptcgag.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2ottibtui.html

G. 面向对象
来源：http://dali.smart0.xyz/Article/details/gt2hobvuxer.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2xjgrjbns.html

[G01] 定义类
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mpxilaff.html

Py:   class User: pass
来源：http://dali.aizwys.cn/Article/details/gt2kyxfnsha.html

PHP:  class User {}
来源：http://dali.cucudq.cn/Article/details/gt2kvwhfzln.html

JS:   class User {}
来源：http://dali.guannengcc.top/Article/details/gt2lgogitsa.html

TS:   class User { name: string = ""; }
来源：http://dali.zhoulong.xyz/Article/details/gt2asdykynp.html

Java: class User {}
来源：http://dali.ehwqpu.com/Article/details/gt2ewegxzrk.html

Go:   type User struct { Name string }
来源：http://dali.sweek.top/Article/details/gt2crgiyvee.html

Ruby: class User; end
来源：http://dali.xuanzx.com/Article/details/gt2dskawgfo.html

C#:   class User {}
来源：http://dali.vqdsnc.cn/Article/details/gt2gluwgxbe.html

[G02] 构造函数
来源：http://dali.nwbrower.top/Article/details/gt2dibxbkab.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qxlctmxc.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2avmwiftq.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.aibaodan.cn/Article/details/gt2fbpoujao.html

TS:   constructor(public name: string) {}
来源：http://dali.vqdsnc.cn/Article/details/gt2ujovzpzk.html

Java: User(String name) { this.name = name; }
来源：http://dali.birdmap.top/Article/details/gt2gmgigtdl.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.haohaochexian.top/Article/details/gt2ltooauhe.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vnvegcxx.html

C#:   public User(string name) { Name = name; }
来源：http://dali.ppjwa.cn/Article/details/gt2iygcatno.html

[G03] 实例属性
来源：http://dali.zhoulong.xyz/Article/details/gt2rwkryuns.html

Py:   self.name = "x"
来源：http://dali.0kj1m.cn/Article/details/gt2dixhtcci.html

PHP:  public string $name = "x";
来源：http://dali.xziqi.cn/Article/details/gt2fvmqvqym.html

JS:   this.name = "x";
来源：http://dali.jiagoushi.top/Article/details/gt2isbypelj.html

TS:   name: string = "x";
来源：http://dali.jiagoushi.top/Article/details/gt2kbxpjlsf.html

Java: private String name;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iewrfxgl.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rrsmdoss.html

Ruby: @name = "x"
来源：http://dali.bjfxy.top/Article/details/gt2twwgopyn.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pdlaodgy.html

[G04] 定义方法
来源：http://dali.gogol.net.cn/Article/details/gt2tjhxsukp.html

Py:   def greet(self): return self.name
来源：http://dali.yonumen.top/Article/details/gt2tapelslm.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.cashguo.top/Article/details/gt2fmgoxvcb.html

JS:   greet() { return this.name; }
来源：http://dali.haohaochexian.top/Article/details/gt2gweahefc.html

TS:   greet(): string { return this.name; }
来源：http://dali.yonumen.top/Article/details/gt2mrjdmudw.html

Java: String greet() { return name; }
来源：http://dali.yuxming.cn/Article/details/gt2dxaowvqe.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.ivvv.top/Article/details/gt2fyxkabbf.html

Ruby: def greet; @name; end
来源：http://dali.xylfe.cn/Article/details/gt2xaahbtod.html

C#:   public string Greet() => Name;
来源：http://dali.0kj1m.cn/Article/details/gt2oqxntyav.html

[G05] 继承
来源：http://dali.tanke756.top/Article/details/gt2erqcwolf.html

Py:   class Admin(User): pass
来源：http://dali.zhiwuduotai.top/Article/details/gt2mnktgpep.html

PHP:  class Admin extends User {}
来源：http://dali.cqqwz.cn/Article/details/gt2mkftbqpd.html

JS:   class Admin extends User {}
来源：http://dali.havefunace.top/Article/details/gt2tdauscjp.html

TS:   class Admin extends User {}
来源：http://dali.zhengqikj.top/Article/details/gt2aomhrpue.html

Java: class Admin extends User {}
来源：http://dali.mhx1999.top/Article/details/gt2pxfbfykf.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.pycfn.com/Article/details/gt2eihdmlht.html

Ruby: class Admin < User; end
来源：http://dali.sysykeji.top/Article/details/gt2bygxanqe.html

C#:   class Admin : User {}
来源：http://dali.guannengcc.top/Article/details/gt2jzzwutax.html

[G06] 重写方法
来源：http://dali.zhoulong.xyz/Article/details/gt2zufkhsfa.html

Py:   def greet(self): return "admin"
来源：http://dali.gzhubu.top/Article/details/gt2rgruzirs.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhengqikj.top/Article/details/gt2brogyvuo.html

JS:   greet() { return "admin"; }
来源：http://dali.xinyue.icu/Article/details/gt2ahivxdys.html

TS:   greet(): string { return "admin"; }
来源：http://dali.guowangkeji.top/Article/details/gt2ezrddjrk.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.sxryk.cn/Article/details/gt2zoguuwyn.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yueranfly.top/Article/details/gt2vfofjjas.html

Ruby: def greet; "admin"; end
来源：http://dali.jqgufenzy.top/Article/details/gt2twiytpyn.html

C#:   public override string Greet() => "admin";
来源：http://dali.ppjwa.cn/Article/details/gt2cdipzupz.html

[G07] 调用父类方法
来源：http://dali.andypj.xyz/Article/details/gt2qysswoqk.html

Py:   super().greet()
来源：http://dali.316326.xyz/Article/details/gt2ighnejdy.html

PHP:  parent::greet();
来源：http://dali.fzhhl.top/Article/details/gt2iusvjeps.html

JS:   super.greet();
来源：http://dali.tian-w.cn/Article/details/gt2vixcoccv.html

TS:   super.greet();
来源：http://dali.cashguo.top/Article/details/gt2fnqcwkmb.html

Java: super.greet();
来源：http://dali.xziqi.cn/Article/details/gt2tjubdead.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.haohaochexian.top/Article/details/gt2jhqdrgeq.html

Ruby: super
来源：http://dali.fzhhl.top/Article/details/gt2vobwemlx.html

C#:   base.Greet();
来源：http://dali.jinqigfzy.top/Article/details/gt2piimlrzc.html

[G08] 静态方法与属性
来源：http://dali.9152youxi.cn/Article/details/gt2mfansgnx.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jqgfzy.top/Article/details/gt2hhtxbjhq.html

PHP:  public static function f() {}
来源：http://dali.chenlongwang.top/Article/details/gt2ytosskfc.html

JS:   static f() {}
来源：http://dali.zhixingplan.top/Article/details/gt2xpjvkdld.html

TS:   static f(): void {}
来源：http://dali.guowangkeji.top/Article/details/gt2dtqxyczl.html

Java: static void f() {}
来源：http://dali.jinqigfzy.top/Article/details/gt2euzlvvju.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.ybcxt.top/Article/details/gt2sehuqyrr.html

Ruby: def self.f; end
来源：http://dali.316326.xyz/Article/details/gt2rzbijufx.html

C#:   public static void F() {}
来源：http://dali.iojbl.cn/Article/details/gt2prooklzi.html

[G09] 接口 / 抽象类
来源：http://dali.svipenyu.cn/Article/details/gt2txmctrnu.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.cqqwz.cn/Article/details/gt2xizccopz.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.cashguo.top/Article/details/gt2yxvnpnmc.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hfpthk.cn/Article/details/gt2ikzvljhd.html

TS:   interface Shape { area(): number; }
来源：http://dali.xylfe.cn/Article/details/gt2qozhtmno.html

Java: interface Shape { double area(); }
来源：http://dali.316326.xyz/Article/details/gt2ehexfzvk.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.nanxinkj.top/Article/details/gt2tffzsygy.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jinqigfzy.top/Article/details/gt2jjbcfqaa.html

C#:   interface IShape { double Area(); }
来源：http://dali.xinyue.icu/Article/details/gt2pnbelvpf.html

[G10] 访问控制
来源：http://dali.cdnleiting.top/Article/details/gt2vinbekdr.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.cqqwz.cn/Article/details/gt2enorkxvb.html

PHP:  public / protected / private
来源：http://dali.nanxinkj.top/Article/details/gt2hkplgyvi.html

JS:   #private 字段；其余公开
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hutjzyax.html

TS:   public / protected / private
来源：http://dali.cucudq.cn/Article/details/gt2katqpkkb.html

Java: public / protected / private / 默认包级
来源：http://dali.fzhhl.top/Article/details/gt2mjvdbwxw.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.wangshuangyany.cn/Article/details/gt2zgudcotr.html

Ruby: public / protected / private
来源：http://dali.0kj1m.cn/Article/details/gt2wzphqkms.html

C#:   public / protected / private / internal
来源：http://dali.yuxming.cn/Article/details/gt2yocjquup.html

[G11] getter / setter
来源：http://dali.vqdsnc.cn/Article/details/gt2qdydoqsc.html

Py:   @property 与 @x.setter
来源：http://dali.shangyingyoupin.top/Article/details/gt2mnallsif.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xuanzx.com/Article/details/gt2imxiwsrn.html

JS:   get name() { return this._name; }
来源：http://dali.cucudq.cn/Article/details/gt2debxxwwp.html

TS:   get name(): string { return this._name; }
来源：http://dali.yj20258.top/Article/details/gt2chhtnlvy.html

Java: public String getName() { return name; }
来源：http://dali.yuxming.cn/Article/details/gt2prcjkxdz.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.birdmap.top/Article/details/gt2bnunchtj.html

Ruby: attr_accessor :name
来源：http://dali.zycfv.cn/Article/details/gt2vzgcwxny.html

C#:   public string Name { get; set; }
来源：http://dali.haohaochexian.top/Article/details/gt2oysfptbv.html

[G12] 对象转字符串
来源：http://dali.shangyingyoupin.top/Article/details/gt2onubxuwu.html

Py:   def __str__(self): return self.name
来源：http://dali.ehwqpu.com/Article/details/gt2pwprgoqp.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.haohaochexian.top/Article/details/gt2yzmpzmcw.html

JS:   toString() { return this.name; }
来源：http://dali.daria6918.cn/Article/details/gt2zxjxjaik.html

TS:   toString(): string { return this.name; }
来源：http://dali.yongpay.top/Article/details/gt2xygzfszu.html

Java: @Override public String toString() { return name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bunptxcy.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.daria6918.cn/Article/details/gt2flmlpkam.html

Ruby: def to_s; @name; end
来源：http://dali.0kj1m.cn/Article/details/gt2qveigbim.html

C#:   public override string ToString() => Name;
来源：http://dali.cashguo.top/Article/details/gt2ooxbydwk.html

[G13] 判断对象类型
来源：http://dali.cheryme.top/Article/details/gt2lpfmkqef.html

Py:   isinstance(u, User)
来源：http://dali.smart0.xyz/Article/details/gt2xarqquaj.html

PHP:  $u instanceof User
来源：http://dali.nanxuanxn.top/Article/details/gt2bwuknosg.html

JS:   u instanceof User
来源：http://dali.quarkkingdee.top/Article/details/gt2wluzcwnm.html

TS:   u instanceof User
来源：http://dali.gotoacloud.top/Article/details/gt2mlrpeqod.html

Java: u instanceof User
来源：http://dali.hnxiangtu.top/Article/details/gt2strgnyxm.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yuanzhike.top/Article/details/gt2jbmreezw.html

Ruby: u.is_a?(User)
来源：http://dali.chenzaomai.com/Article/details/gt2rvrnkdyn.html

C#:   u is User
来源：http://dali.wangshuangyany.cn/Article/details/gt2xpuemhsd.html

[G14] 数据类 / record
来源：http://dali.jqgfzy.top/Article/details/gt2yxgvstlz.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.dashuyun.cn/Article/details/gt2sgrdvnyg.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.dianchejie.cn/Article/details/gt2oczlrsvl.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.guannengcc.top/Article/details/gt2pdapwqcn.html

TS:   type User = { name: string; age: number };
来源：http://dali.9152youxi.cn/Article/details/gt2mlupritm.html

Java: record User(String name, int age) {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2spklftys.html

Go:   type User struct { Name string; Age int }
来源：http://dali.kuanghao11.cn/Article/details/gt2nkmupjgc.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.0kj1m.cn/Article/details/gt2fsxdfpez.html

C#:   record User(string Name, int Age);
来源：http://dali.guowangkeji.top/Article/details/gt2rvjcvpri.html

[G15] 枚举
来源：http://dali.hammf.cn/Article/details/gt2rrxfkrmr.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jinqigufen.top/Article/details/gt2szpfrhvf.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yueranfly.top/Article/details/gt2otymqtfq.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.haohaochexian.top/Article/details/gt2wkekantr.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.chenzaomai.com/Article/details/gt2iukouwib.html

Java: enum Color { RED, GREEN }
来源：http://dali.ybcxt.top/Article/details/gt2bkqcmsch.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jqgufenzy.top/Article/details/gt2gpphgrpo.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yj20258888.top/Article/details/gt2pskwiivk.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.tian-w.cn/Article/details/gt2bmmzctrb.html

[G16] 对象转数组 / 字典
来源：http://dali.ybcxt.top/Article/details/gt2vbeupudj.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.sxryk.cn/Article/details/gt2goanhrmy.html

PHP:  get_object_vars($obj);
来源：http://dali.hysaishi.cn/Article/details/gt2rovvczfz.html

JS:   Object.entries(obj)
来源：http://dali.0kj1m.cn/Article/details/gt2qhuihqzs.html

TS:   Object.entries(obj)
来源：http://dali.zhengqikj.top/Article/details/gt2wfqirgkv.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jqgfzy.top/Article/details/gt2nkbbcqnu.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jyoumei.cn/Article/details/gt2zobfcpuu.html

Ruby: obj.instance_variables
来源：http://dali.cashguo.top/Article/details/gt2jmiughqr.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.shzxlz.cn/Article/details/gt2bmxuiqmb.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2xyvdglab.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2raxjthno.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2bzciwtzu.html

[H01] try / catch 基础
来源：http://dali.cashguo.top/Article/details/gt2rtlzcnpv.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yj20258.top/Article/details/gt2mfdsqmms.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yangfankeji.com/Article/details/gt2msxrfevl.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.xylfe.cn/Article/details/gt2qulkvnpn.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.pycfn.com/Article/details/gt2xwxtendj.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2ijxanhbe.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yvedp.cn/Article/details/gt2qraeemig.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jqgufenzy.top/Article/details/gt2bkqglxrj.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.fengsongda.top/Article/details/gt2aduiyhgq.html

[H02] finally / ensure 收尾
来源：http://dali.jlsjyb.cn/Article/details/gt2bzgtkrdf.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yanxiufei.cn/Article/details/gt2mjxlaema.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.ehwqpu.com/Article/details/gt2ozmfahoi.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.fengsongda.top/Article/details/gt2ewsugjcr.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ntzzqmxk.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.xylfe.cn/Article/details/gt2ofbtcekd.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yangfankeji.com/Article/details/gt2ajxrfxkj.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.0kj1m.cn/Article/details/gt2vhrhwzhp.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.gotoacloud.top/Article/details/gt2kyfptpxn.html

[H03] 主动抛出异常
来源：http://dali.hammf.cn/Article/details/gt2slxnvhdy.html

Py:   raise ValueError("错误信息")
来源：http://dali.ehwqpu.com/Article/details/gt2ueoozhhm.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yuxming.cn/Article/details/gt2rvuobwzl.html

JS:   throw new Error("错误信息");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wziomcmk.html

TS:   throw new Error("错误信息");
来源：http://dali.xylfe.cn/Article/details/gt2zlixaxyf.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.gzhubu.top/Article/details/gt2ghahmcil.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hywenlv.cn/Article/details/gt2lxvcbiuu.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.redwolf501.top/Article/details/gt2bwtavayc.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zycfv.cn/Article/details/gt2tbvhkatz.html

[H04] 自定义异常类型
来源：http://dali.yueranfly.top/Article/details/gt2tgefafmn.html

Py:   class MyError(Exception): pass
来源：http://dali.yanxiufei.cn/Article/details/gt2jzokejun.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhoulong.xyz/Article/details/gt2rjpfjmor.html

JS:   class MyError extends Error {}
来源：http://dali.redwolf501.top/Article/details/gt2doneipgp.html

TS:   class MyError extends Error {}
来源：http://dali.9152youxi.cn/Article/details/gt2wutblnae.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yueranfly.top/Article/details/gt2dapdklxh.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yj20258888.top/Article/details/gt2cszqqpaz.html

Ruby: class MyError < StandardError; end
来源：http://dali.bjfxy.top/Article/details/gt2rlpdscst.html

C#:   class MyException : Exception {}
来源：http://dali.andypj.xyz/Article/details/gt2kxzqqlhj.html

[H05] 捕获特定类型
来源：http://dali.9152youxi.cn/Article/details/gt2ydrtikyp.html

Py:   except ValueError as e:
来源：http://dali.xziqi.cn/Article/details/gt2gqnqltot.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.xziqi.cn/Article/details/gt2vezqmpnc.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.ydzc1.top/Article/details/gt2gawdmaiw.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.ivvv.top/Article/details/gt2zhtfldar.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.gzhubu.top/Article/details/gt2xqkpftsw.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.guannengcc.top/Article/details/gt2gpcpwlnc.html

Ruby: rescue ArgumentError => e
来源：http://dali.meibo888.top/Article/details/gt2wxfxutpi.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yonumen.top/Article/details/gt2erslikmm.html

[H06] 可选值 / 空值安全访问
来源：http://dali.wangdashe.top/Article/details/gt2cpacpbqu.html

Py:   value = d.get("k") or default
来源：http://dali.tianlin.xyz/Article/details/gt2omtuiogt.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2alwfubdy.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.ydzc1.top/Article/details/gt2udnogvwz.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tceqtgco.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.ehwqpu.com/Article/details/gt2yinjxhby.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.hfpthk.cn/Article/details/gt2khrswtwt.html

Ruby: d&.dig(:a, :b)
来源：http://dali.dashuyun.cn/Article/details/gt2mypeqizv.html

C#:   obj?.A?.B ?? default
来源：http://dali.xylfe.cn/Article/details/gt2aesiynhp.html

[H07] 断言
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2whbvsjes.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2skbdzubh.html

PHP:  assert($x > 0);
来源：http://dali.jqgfzy.top/Article/details/gt2uzuxinmk.html

JS:   console.assert(x > 0);
来源：http://dali.iojbl.cn/Article/details/gt2affdtezl.html

TS:   console.assert(x > 0);
来源：http://dali.aizwys.cn/Article/details/gt2ohzuntgp.html

Java: assert x > 0 : "必须为正";
来源：http://dali.fzhhl.top/Article/details/gt2ejbkpdir.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.cashguo.top/Article/details/gt2yzmdbcue.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.meibo888.top/Article/details/gt2cieguigo.html

C#:   Debug.Assert(x > 0);
来源：http://dali.chenlongwang.top/Article/details/gt2bufwhexp.html

[H08] 获取错误信息与堆栈
来源：http://dali.cqqwz.cn/Article/details/gt2yphdcddn.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jqgufenzy.top/Article/details/gt2qpbwcuxe.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.cdnleiting.top/Article/details/gt2bnbknmre.html

JS:   e.message;  e.stack
来源：http://dali.shzxlz.cn/Article/details/gt2pjfvieqn.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhixingplan.top/Article/details/gt2xmsujzzg.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.redwolf501.top/Article/details/gt2rjaqqcpy.html

Go:   err.Error()
来源：http://dali.cqqwz.cn/Article/details/gt2ujlxzuvc.html

Ruby: e.message;  e.backtrace
来源：http://dali.ehwqpu.com/Article/details/gt2uymbzlri.html

C#:   e.Message;  e.StackTrace
来源：http://dali.ivvv.top/Article/details/gt2asfmibnn.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gt2mbqpraga.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.nwbrower.top/Article/details/gt2obmzbqie.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jinqigufen.top/Article/details/gt2nacclhsy.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.hnqzz.top/Article/details/gt2tbvbockz.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.xinyue.icu/Article/details/gt2mabkyonp.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.ppjwa.cn/Article/details/gt2fvabrsem.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.guowangkeji.top/Article/details/gt2merbpzxb.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.redwolf501.top/Article/details/gt2hgxlkgaa.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zycfv.cn/Article/details/gt2fmfvqahj.html

[H10] 资源自动释放
来源：http://dali.zycfv.cn/Article/details/gt2jjjtiyjo.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yvedp.cn/Article/details/gt2lufzjdwz.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jinqigfzy.top/Article/details/gt2inpjevza.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ydzc1.top/Article/details/gt2ethopqsv.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.haohaochexian.top/Article/details/gt2rjfjsgxe.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.birdmap.top/Article/details/gt2bqfalglx.html

Go:   defer f.Close()
来源：http://dali.chenzaomai.com/Article/details/gt2kdtuxmjn.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.yueranfly.top/Article/details/gt2qjknwiwp.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.chenzaomai.com/Article/details/gt2rstpyssn.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2agaymkxm.html

I. 正则表达式
来源：http://dali.smart0.xyz/Article/details/gt2ehxbapmy.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2ralcwcur.html

[I01] 判断是否匹配
来源：http://dali.yuanzhike.top/Article/details/gt2dkoblpyd.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.jqgfzy.top/Article/details/gt2zhomtyvj.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.meibo888.top/Article/details/gt2hjnbdety.html

JS:   /\d+/.test(s)
来源：http://dali.guowangkeji.top/Article/details/gt2ytudzwyx.html

TS:   /\d+/.test(s)
来源：http://dali.fzhhl.top/Article/details/gt2osasvamm.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.0kj1m.cn/Article/details/gt2nsiqexvg.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.daria6918.cn/Article/details/gt2zscutwfj.html

Ruby: s.match?(/\d+/)
来源：http://dali.ivvv.top/Article/details/gt2zxnxhsuv.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yj20258.top/Article/details/gt2izayeitr.html

[I02] 提取所有匹配
来源：http://dali.hammf.cn/Article/details/gt2nlwosfif.html

Py:   re.findall(r"\d+", s)
来源：http://dali.sysykeji.top/Article/details/gt2pkrozuio.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.tanke756.top/Article/details/gt2hodkqmhe.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yj202588.top/Article/details/gt2gqimvfrd.html

TS:   s.match(/\d+/g)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2auhipxjb.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yongpay.top/Article/details/gt2ayifuxdd.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.sweek.top/Article/details/gt2bzkxrjan.html

Ruby: s.scan(/\d+/)
来源：http://dali.mhx1999.top/Article/details/gt2dokaoqgb.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.guowangkeji.top/Article/details/gt2glyhckxd.html

[I03] 提取捕获分组
来源：http://dali.9152youxi.cn/Article/details/gt2wksswfnr.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.9152youxi.cn/Article/details/gt2rlcvckjm.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yuanzhike.top/Article/details/gt2bfcpqgtl.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.ehwqpu.com/Article/details/gt2ivdsgzlv.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.gzhubu.top/Article/details/gt2pjkpwmqv.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yongpay.top/Article/details/gt2pfsrkhgd.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.guannengcc.top/Article/details/gt2bkuezlxj.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.vqdsnc.cn/Article/details/gt2lxjqjnfu.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.ydzc1.top/Article/details/gt2nebtpyct.html

[I04] 正则替换
来源：http://dali.hnqzz.top/Article/details/gt2zuqclltn.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.quarkkingdee.top/Article/details/gt2dpddpmtl.html


<!-- 参考信息 -->