代发 wailian999

TS:   fs.statSync("a.txt").size
来源：http://dali.gaohongyu789.top/Article/details/gtairnoqih.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhoulong.xyz/Article/details/gtdjhbvojf.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.birdmap.top/Article/details/gtilnczaqu.html

Ruby: File.size("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtqeoqwpwu.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zycfv.cn/Article/details/gtjsgednxm.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yj20258.top/Article/details/gtntpldila.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtnyoeodol.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.ybcxt.top/Article/details/gtkbimbsuu.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.fengsongda.top/Article/details/gtmvohbxhh.html

TS:   path.extname("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtetugcdha.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hysaishi.cn/Article/details/gtubumwyty.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtpwibrvjj.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yj20258.top/Article/details/gtbgebhtqj.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.xylfe.cn/Article/details/gtictljmpi.html

[F11] 复制与移动文件
来源：http://dali.xylfe.cn/Article/details/gtmxudpxqa.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.cdnleiting.top/Article/details/gtsanbrwjw.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.hywenlv.cn/Article/details/gtctvoxjea.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.iojbl.cn/Article/details/gtfoktywcj.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xuanzx.com/Article/details/gtutoizern.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.hongshengwenyu.top/Article/details/gtjcfsrcsq.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.quarkkingdee.top/Article/details/gtjgrrdvmc.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.fengsongda.top/Article/details/gtfcsipgaa.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yonumen.top/Article/details/gtfovwpykm.html

[F12] CSV 读写
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbirvjvcx.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.snrcjt.cn/Article/details/gticmaitem.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.0kj1m.cn/Article/details/gtkqipqklx.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.cashguo.top/Article/details/gtfdtelymi.html

TS:   // 同上
来源：http://dali.zhengqikj.top/Article/details/gtjipnajdr.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yanxiufei.cn/Article/details/gtozbkwhdk.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.ehwqpu.com/Article/details/gtrirxneze.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yangfankeji.com/Article/details/gtrvccjnru.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.redwolf501.top/Article/details/gtfbcrrstd.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtvphwuwvp.html

G. 面向对象
来源：http://dali.sxryk.cn/Article/details/gtlyhktdcp.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzlprqdjo.html

[G01] 定义类
来源：http://dali.yongpay.top/Article/details/gtrvxawhlp.html

Py:   class User: pass
来源：http://dali.yj20258888.top/Article/details/gtfpxpqkmn.html

PHP:  class User {}
来源：http://dali.xuetiantiany.cn/Article/details/gtpagxrtuz.html

JS:   class User {}
来源：http://dali.yj20258.top/Article/details/gtubpalhll.html

TS:   class User { name: string = ""; }
来源：http://dali.yanxiufei.cn/Article/details/gtakteelow.html

Java: class User {}
来源：http://dali.ppjwa.cn/Article/details/gtfityynue.html

Go:   type User struct { Name string }
来源：http://dali.wangshuangyany.cn/Article/details/gtfhmfovhl.html

Ruby: class User; end
来源：http://dali.smart0.xyz/Article/details/gtisorqkjt.html

C#:   class User {}
来源：http://dali.pycfn.com/Article/details/gtcxzwzitp.html

[G02] 构造函数
来源：http://dali.xziqi.cn/Article/details/gtdqcsrcjr.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhengqikj.top/Article/details/gttjjltamf.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnmmqscio.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jiagoushi.top/Article/details/gtcnosyiff.html

TS:   constructor(public name: string) {}
来源：http://dali.bjfxy.top/Article/details/gtylzpryqp.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhongyouzk.top/Article/details/gtchonpdou.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.kuanghao11.cn/Article/details/gtabznzumx.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.cashguo.top/Article/details/gtgsdtdiga.html

C#:   public User(string name) { Name = name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtepybctbp.html

[G03] 实例属性
来源：http://dali.hywenlv.cn/Article/details/gtzrwvzjxy.html

Py:   self.name = "x"
来源：http://dali.c1oappe.top/Article/details/gtsaxrisuc.html

PHP:  public string $name = "x";
来源：http://dali.chenlongwang.top/Article/details/gttucqzfkk.html

JS:   this.name = "x";
来源：http://dali.birdmap.top/Article/details/gtohjgaioi.html

TS:   name: string = "x";
来源：http://dali.smart0.xyz/Article/details/gtmyxzqnpr.html

Java: private String name;
来源：http://dali.hammf.cn/Article/details/gtmwtvyuyk.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.aibaodan.cn/Article/details/gtmepnfvsq.html

Ruby: @name = "x"
来源：http://dali.gogol.net.cn/Article/details/gtbpmqeogj.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.hnqzz.top/Article/details/gtrbqfnmca.html

[G04] 定义方法
来源：http://dali.daxiang520.top/Article/details/gtwfymqwem.html

Py:   def greet(self): return self.name
来源：http://dali.zdqjudy.top/Article/details/gtrodkxejz.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zycfv.cn/Article/details/gtdnzbkafa.html

JS:   greet() { return this.name; }
来源：http://dali.chenzaomai.com/Article/details/gtocqsgltw.html

TS:   greet(): string { return this.name; }
来源：http://dali.yj20258888.top/Article/details/gtxovwuhhb.html

Java: String greet() { return name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtaayteivm.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zdqjudy.top/Article/details/gtufrvnrgo.html

Ruby: def greet; @name; end
来源：http://dali.yj20258888.top/Article/details/gtmgabrlze.html

C#:   public string Greet() => Name;
来源：http://dali.bjfxy.top/Article/details/gtkfuddzrp.html

[G05] 继承
来源：http://dali.zdqjudy.top/Article/details/gtrtumwatw.html

Py:   class Admin(User): pass
来源：http://dali.zhengqikj.top/Article/details/gthoizwjpd.html

PHP:  class Admin extends User {}
来源：http://dali.smart0.xyz/Article/details/gtpikhufcp.html

JS:   class Admin extends User {}
来源：http://dali.shuidangran.top/Article/details/gthhbojnsa.html

TS:   class Admin extends User {}
来源：http://dali.fengsongda.top/Article/details/gtiawnpztz.html

Java: class Admin extends User {}
来源：http://dali.redwolf501.top/Article/details/gtxkdvrukn.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jiagoushi.top/Article/details/gtgwjbrouw.html

Ruby: class Admin < User; end
来源：http://dali.guannengcc.top/Article/details/gtgbtmvjdi.html

C#:   class Admin : User {}
来源：http://dali.zhongyouzk.top/Article/details/gtensquwbn.html

[G06] 重写方法
来源：http://dali.jiagoushi.top/Article/details/gtinmrczsb.html

Py:   def greet(self): return "admin"
来源：http://dali.316326.xyz/Article/details/gtprjstept.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.gogol.net.cn/Article/details/gtlulomqub.html

JS:   greet() { return "admin"; }
来源：http://dali.quarkkingdee.top/Article/details/gtbbkpyuzx.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yvedp.cn/Article/details/gtqkggsmip.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.wangdashe.top/Article/details/gtsgqgkkls.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.fzhhl.top/Article/details/gtjcndtter.html

Ruby: def greet; "admin"; end
来源：http://dali.ppjwa.cn/Article/details/gtpsuobccx.html

C#:   public override string Greet() => "admin";
来源：http://dali.haohaochexian.top/Article/details/gtqxextnqa.html

[G07] 调用父类方法
来源：http://dali.pycfn.com/Article/details/gtttqslaop.html

Py:   super().greet()
来源：http://dali.quarkkingdee.top/Article/details/gtfwueoycw.html

PHP:  parent::greet();
来源：http://dali.sufxvd.cn/Article/details/gtldxplrpk.html

JS:   super.greet();
来源：http://dali.pengpengdd.cyou/Article/details/gtboxuxcty.html

TS:   super.greet();
来源：http://dali.316326.xyz/Article/details/gtvlxpvwjb.html

Java: super.greet();
来源：http://dali.aibaodan.cn/Article/details/gtbifqumpy.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.birdmap.top/Article/details/gtzblbctgb.html

Ruby: super
来源：http://dali.guowangkeji.top/Article/details/gtaduuieiu.html

C#:   base.Greet();
来源：http://dali.kuanghao11.cn/Article/details/gtdpnoyaml.html

[G08] 静态方法与属性
来源：http://dali.cqqwz.cn/Article/details/gtpcooairi.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jlsjyb.cn/Article/details/gtcvjtnyri.html

PHP:  public static function f() {}
来源：http://dali.zycfv.cn/Article/details/gtamtzohxt.html

JS:   static f() {}
来源：http://dali.jqgfzy.top/Article/details/gtcbgcsija.html

TS:   static f(): void {}
来源：http://dali.iojbl.cn/Article/details/gthvgdmlkj.html

Java: static void f() {}
来源：http://dali.wangdashe.top/Article/details/gtgajngbzt.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.feifeiyinyue.top/Article/details/gtwrzuoxss.html

Ruby: def self.f; end
来源：http://dali.hywenlv.cn/Article/details/gtgqaswnib.html

C#:   public static void F() {}
来源：http://dali.zycfv.cn/Article/details/gtngxnuedm.html

[G09] 接口 / 抽象类
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtferrgdkx.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.chenlongwang.top/Article/details/gtsezuhvxl.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.aibaodan.cn/Article/details/gttcawmwjj.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.aibaodan.cn/Article/details/gtswruyltg.html

TS:   interface Shape { area(): number; }
来源：http://dali.guannengcc.top/Article/details/gtmnxthgzn.html

Java: interface Shape { double area(); }
来源：http://dali.dianchejie.cn/Article/details/gtvfconpna.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.shuidangran.top/Article/details/gtfmgkogod.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yueranfly.top/Article/details/gtvtadmrmw.html

C#:   interface IShape { double Area(); }
来源：http://dali.hysaishi.cn/Article/details/gtidjxshrs.html

[G10] 访问控制
来源：http://dali.birdmap.top/Article/details/gtrscccygh.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.mhx1999.top/Article/details/gtfupthkst.html

PHP:  public / protected / private
来源：http://dali.ydzc1.top/Article/details/gtpapwksxw.html

JS:   #private 字段；其余公开
来源：http://dali.dianchejie.cn/Article/details/gtopqybtch.html

TS:   public / protected / private
来源：http://dali.xylfe.cn/Article/details/gthtnnhvyb.html

Java: public / protected / private / 默认包级
来源：http://dali.sweek.top/Article/details/gtwmslqfnw.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.gzhubu.top/Article/details/gtwsavmrfj.html

Ruby: public / protected / private
来源：http://dali.zhongyouzk.top/Article/details/gtmbmgypjl.html

C#:   public / protected / private / internal
来源：http://dali.cqqwz.cn/Article/details/gtfxuplpvh.html

[G11] getter / setter
来源：http://dali.jiagoushi.top/Article/details/gtxbkeswum.html

Py:   @property 与 @x.setter
来源：http://dali.shzxlz.cn/Article/details/gtfbwvkjvn.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yj20258.top/Article/details/gtolyqzkeb.html

JS:   get name() { return this._name; }
来源：http://dali.guannengcc.top/Article/details/gtxclnvwou.html

TS:   get name(): string { return this._name; }
来源：http://dali.0kj1m.cn/Article/details/gtjmfkfivw.html

Java: public String getName() { return name; }
来源：http://dali.cheryme.top/Article/details/gtcwevhlpb.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.nwbrower.top/Article/details/gtcjfitnhy.html

Ruby: attr_accessor :name
来源：http://dali.zycfv.cn/Article/details/gtzsllkijz.html

C#:   public string Name { get; set; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzshbkusy.html

[G12] 对象转字符串
来源：http://dali.zhiwuduotai.top/Article/details/gtzbjpliss.html

Py:   def __str__(self): return self.name
来源：http://dali.gogol.net.cn/Article/details/gtlrqkwxcm.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yongpay.top/Article/details/gttprrgrxd.html

JS:   toString() { return this.name; }
来源：http://dali.chenlongwang.top/Article/details/gtycqzjhcg.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gtsxittaem.html

Java: @Override public String toString() { return name; }
来源：http://dali.haohaochexian.top/Article/details/gtedfrjxgf.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.sufxvd.cn/Article/details/gtaffgvcna.html

Ruby: def to_s; @name; end
来源：http://dali.jqgfzy.top/Article/details/gtwlgaeshe.html

C#:   public override string ToString() => Name;
来源：http://dali.tanke756.top/Article/details/gtibuxlldv.html

[G13] 判断对象类型
来源：http://dali.meibo888.top/Article/details/gtcrypkhdg.html

Py:   isinstance(u, User)
来源：http://dali.wangdashe.top/Article/details/gtxqvuknwb.html

PHP:  $u instanceof User
来源：http://dali.aizwys.cn/Article/details/gtbeuafjuj.html

JS:   u instanceof User
来源：http://dali.yuxming.cn/Article/details/gtyqoaijbi.html

TS:   u instanceof User
来源：http://dali.fengsongda.top/Article/details/gtdmmfcwnp.html

Java: u instanceof User
来源：http://dali.chenlongwang.top/Article/details/gtzanzlfxn.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jlsjyb.cn/Article/details/gttjyxdlft.html

Ruby: u.is_a?(User)
来源：http://dali.snrcjt.cn/Article/details/gttvfzfeym.html

C#:   u is User
来源：http://dali.yanxiufei.cn/Article/details/gtpavuwnfd.html

[G14] 数据类 / record
来源：http://dali.mhx1999.top/Article/details/gttxyecasg.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.sysykeji.top/Article/details/gtjnyvxacs.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.ehwqpu.com/Article/details/gtlpjxgehi.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.dianchejie.cn/Article/details/gtwrmiixxo.html

TS:   type User = { name: string; age: number };
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbujwkylr.html

Java: record User(String name, int age) {}
来源：http://dali.fzhhl.top/Article/details/gtzgcbcwcd.html

Go:   type User struct { Name string; Age int }
来源：http://dali.svipenyu.cn/Article/details/gtqrhzvryg.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yvedp.cn/Article/details/gtwwdnuuig.html

C#:   record User(string Name, int Age);
来源：http://dali.ybcxt.top/Article/details/gtqikzqwhn.html

[G15] 枚举
来源：http://dali.jinqigufen.top/Article/details/gtulaenvjc.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.xziqi.cn/Article/details/gthyaewnzt.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.tian-w.cn/Article/details/gtelpjlfrl.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yanxiufei.cn/Article/details/gttdoqmadh.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhongyouzk.top/Article/details/gtqaynbwgp.html

Java: enum Color { RED, GREEN }
来源：http://dali.guannengcc.top/Article/details/gtlgcrzdlz.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.xziqi.cn/Article/details/gtbnlqbtmt.html

Ruby: Color = %i[red green].freeze
来源：http://dali.nanxuanxn.top/Article/details/gtlyzfirvm.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.smart0.xyz/Article/details/gthzuscvvr.html

[G16] 对象转数组 / 字典
来源：http://dali.ivvv.top/Article/details/gtdtryrtpr.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.andypj.xyz/Article/details/gtenpyqfyq.html

PHP:  get_object_vars($obj);
来源：http://dali.hammf.cn/Article/details/gtdexnjghs.html

JS:   Object.entries(obj)
来源：http://dali.daria6918.cn/Article/details/gtbpfuczxb.html

TS:   Object.entries(obj)
来源：http://dali.ehwqpu.com/Article/details/gtryxiatrk.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.mhx1999.top/Article/details/gtvrzlspum.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.gzhubu.top/Article/details/gtkyrtsrog.html

Ruby: obj.instance_variables
来源：http://dali.zdqjudy.top/Article/details/gtlfnmxsck.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hysaishi.cn/Article/details/gtvautpppx.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtckxlxjgz.html

H. 异常与错误处理
来源：http://dali.birdmap.top/Article/details/gtqmwsznok.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtidhplsbz.html

[H01] try / catch 基础
来源：http://dali.havefunace.top/Article/details/gtzvtmojdq.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.xuanzx.com/Article/details/gtvwisgkxc.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yuanzhike.top/Article/details/gtrttmlkaj.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yj20258888.top/Article/details/gtchegjtue.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.cqqwz.cn/Article/details/gtauojpnvf.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.sysykeji.top/Article/details/gtidwaacjh.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jlsjyb.cn/Article/details/gtkedgfxqe.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.daxiang520.top/Article/details/gtyaaglztn.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.c1oappe.top/Article/details/gtkksxbgan.html

[H02] finally / ensure 收尾
来源：http://dali.zycfv.cn/Article/details/gtnwrxhvqi.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.gogol.net.cn/Article/details/gtrivbphpz.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.nanxinkj.top/Article/details/gtygisoljt.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ppjwa.cn/Article/details/gtockobdmf.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.cqqwz.cn/Article/details/gtvsdtsepa.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.tian-w.cn/Article/details/gtgluifexk.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.ehwqpu.com/Article/details/gtgaifqfuh.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.nanxuanxn.top/Article/details/gtlnpifjco.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.guannengcc.top/Article/details/gtjezspnhe.html

[H03] 主动抛出异常
来源：http://dali.jinqigufen.top/Article/details/gtnuzbdqxr.html

Py:   raise ValueError("错误信息")
来源：http://dali.shangyingyoupin.top/Article/details/gtlstkospd.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.iojbl.cn/Article/details/gtejtjiujj.html

JS:   throw new Error("错误信息");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfetommsm.html

TS:   throw new Error("错误信息");
来源：http://dali.shuidangran.top/Article/details/gtnvaguicv.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.snrcjt.cn/Article/details/gtcwzflorm.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.birdmap.top/Article/details/gtkypsqfhe.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.ybcxt.top/Article/details/gtbyhcrros.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.dianchejie.cn/Article/details/gtfxqphnnq.html

[H04] 自定义异常类型
来源：http://dali.yj202588.top/Article/details/gtjmtakart.html

Py:   class MyError(Exception): pass
来源：http://dali.chenlongwang.top/Article/details/gtggmyvrdx.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.cashguo.top/Article/details/gtkeazewab.html

JS:   class MyError extends Error {}
来源：http://dali.gaohongyu789.top/Article/details/gtxubwgoku.html

TS:   class MyError extends Error {}
来源：http://dali.316326.xyz/Article/details/gtpknewjmi.html

Java: class MyException extends RuntimeException {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcbcvyzyq.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.haohaochexian.top/Article/details/gtxstrhkfw.html

Ruby: class MyError < StandardError; end
来源：http://dali.jianghu66.top/Article/details/gterrtrgiy.html

C#:   class MyException : Exception {}
来源：http://dali.chenlongwang.top/Article/details/gtmzdxofsg.html

[H05] 捕获特定类型
来源：http://dali.jqgfzy.top/Article/details/gtmteykvip.html

Py:   except ValueError as e:
来源：http://dali.nwbrower.top/Article/details/gtumlzsxwc.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhoulong.xyz/Article/details/gthgeumvbi.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.xylfe.cn/Article/details/gtvfvjduge.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yvedp.cn/Article/details/gtzfmnekik.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.xylfe.cn/Article/details/gtkeamayvd.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.cashguo.top/Article/details/gtlazrylkm.html

Ruby: rescue ArgumentError => e
来源：http://dali.ybcxt.top/Article/details/gtfhrnbudm.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.c1oappe.top/Article/details/gtjpsdxzvv.html

[H06] 可选值 / 空值安全访问
来源：http://dali.smart0.xyz/Article/details/gtqocitqvy.html

Py:   value = d.get("k") or default
来源：http://dali.gaohongyu789.top/Article/details/gtybbgklop.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.shanyushiyangtech.top/Article/details/gtyuogobme.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.pengpengdd.cyou/Article/details/gtnahsguhq.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.tanke756.top/Article/details/gtwkksfkeg.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yuxming.cn/Article/details/gtrcmhwwwl.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhengqikj.top/Article/details/gtnmvtnfgb.html

Ruby: d&.dig(:a, :b)
来源：http://dali.xziqi.cn/Article/details/gtcdvixdul.html

C#:   obj?.A?.B ?? default
来源：http://dali.316326.xyz/Article/details/gtuhajaxar.html

[H07] 断言
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnmkahzdi.html

Py:   assert x > 0, "必须为正"
来源：http://dali.chenjidiqi.icu/Article/details/gthxqeapcu.html

PHP:  assert($x > 0);
来源：http://dali.jianghu66.top/Article/details/gttldliqow.html

JS:   console.assert(x > 0);
来源：http://dali.zhoulong.xyz/Article/details/gtgvwodjuk.html

TS:   console.assert(x > 0);
来源：http://dali.hysaishi.cn/Article/details/gtbiehtwiv.html

Java: assert x > 0 : "必须为正";
来源：http://dali.fzhhl.top/Article/details/gtyxplpwze.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jiagoushi.top/Article/details/gtvtbpvygu.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.andypj.xyz/Article/details/gtcrspeddf.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yanxiufei.cn/Article/details/gtbohbsjgy.html

[H08] 获取错误信息与堆栈
来源：http://dali.jlsjyb.cn/Article/details/gtwaghovps.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jinqigufen.top/Article/details/gtsjwtxgjz.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.smart0.xyz/Article/details/gtlzccgqgh.html

JS:   e.message;  e.stack
来源：http://dali.haohaochexian.top/Article/details/gtqpsrogql.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvfzdquit.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.ydzc1.top/Article/details/gtqntgnsqe.html

Go:   err.Error()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtexfofydr.html

Ruby: e.message;  e.backtrace
来源：http://dali.yj202588.top/Article/details/gtuwplaoph.html

C#:   e.Message;  e.StackTrace
来源：http://dali.nwbrower.top/Article/details/gthgvbkbgx.html

[H09] 带错误码的异常
来源：http://dali.gzhubu.top/Article/details/gtgftugnvb.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zdqjudy.top/Article/details/gtnmdlrmha.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yonumen.top/Article/details/gtsijiojun.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jinqigfzy.top/Article/details/gtaggzausq.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.hammf.cn/Article/details/gtxskziked.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.shzxlz.cn/Article/details/gtflpkbbxd.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.jinqigfzy.top/Article/details/gteuwwuels.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.dashuyun.cn/Article/details/gtkscmwdbv.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhiwuduotai.top/Article/details/gtcnghxxhy.html

[H10] 资源自动释放
来源：http://dali.ivvv.top/Article/details/gtblbknltz.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.9152youxi.cn/Article/details/gtkybhcunb.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.sysykeji.top/Article/details/gtlicfxxjc.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sysykeji.top/Article/details/gthauslijo.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinqigfzy.top/Article/details/gtbesaawts.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.smart0.xyz/Article/details/gtgavtjveq.html

Go:   defer f.Close()
来源：http://dali.hnqzz.top/Article/details/gtzpbgsgpz.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jyoumei.cn/Article/details/gtfkowjjwb.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jinqigufen.top/Article/details/gtyojppeps.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrutwivuz.html

I. 正则表达式
来源：http://dali.cucudq.cn/Article/details/gtkijdtgxk.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtcjhpfswp.html

[I01] 判断是否匹配
来源：http://dali.sweek.top/Article/details/gtssxzjsjw.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.fengsongda.top/Article/details/gtrjjpcfde.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.hfpthk.cn/Article/details/gtcircqbsx.html

JS:   /\d+/.test(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtbsvxicxr.html

TS:   /\d+/.test(s)
来源：http://dali.jianghu66.top/Article/details/gtbsheeozy.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.c1oappe.top/Article/details/gtufndqkou.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.guannengcc.top/Article/details/gtnruekyap.html

Ruby: s.match?(/\d+/)
来源：http://dali.yongpay.top/Article/details/gtlkyghacl.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.ybcxt.top/Article/details/gtukkrwsvu.html

[I02] 提取所有匹配
来源：http://dali.hywenlv.cn/Article/details/gtxawebbws.html

Py:   re.findall(r"\d+", s)
来源：http://dali.hongshengwenyu.top/Article/details/gtxfhvmxri.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yuxming.cn/Article/details/gtypkdwomx.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.xziqi.cn/Article/details/gtzconeiqv.html

TS:   s.match(/\d+/g)
来源：http://dali.iojbl.cn/Article/details/gtkflembkn.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zycfv.cn/Article/details/gtpkknuzyn.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.xylfe.cn/Article/details/gttkxdhsyo.html

Ruby: s.scan(/\d+/)
来源：http://dali.tianlin.xyz/Article/details/gtggujohff.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.zhoulong.xyz/Article/details/gtcdxnvmrz.html

[I03] 提取捕获分组
来源：http://dali.shanyushiyangtech.top/Article/details/gtcxzpsusu.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.xylfe.cn/Article/details/gtvlutbuam.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.sysykeji.top/Article/details/gteptpbckg.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.jianghu66.top/Article/details/gtjvxrsetg.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.mhx1999.top/Article/details/gtcnbxlgtf.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.316326.xyz/Article/details/gtnfaweiau.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.gogol.net.cn/Article/details/gtduwpyndl.html


<!-- 参考信息 -->