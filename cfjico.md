代发 wailian999

C#:   new FileInfo("a.txt").Length
来源：http://dali.zdqjudy.top/Article/details/gtpednebiu.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.chenjidiqi.icu/Article/details/gttjjyhjxf.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtegsuzzys.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnjhackod.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.wangdashe.top/Article/details/gttmurunxk.html

TS:   path.extname("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtrrwzpsjn.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.kuanghao11.cn/Article/details/gtipazsank.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yueranfly.top/Article/details/gtejvjimhr.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtcayzdmge.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtbwyzdxda.html

[F11] 复制与移动文件
来源：http://dali.ydzc1.top/Article/details/gtmtwqobhg.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgxbwkztc.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.shzxlz.cn/Article/details/gtrkufoquf.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.chenlongwang.top/Article/details/gtrhprndxt.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrrmshkoo.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.pycfn.com/Article/details/gtydbdnzqe.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.hongshengwenyu.top/Article/details/gtbogiwuem.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yvedp.cn/Article/details/gtfyigruwc.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.pengpengdd.cyou/Article/details/gtdjsffhmo.html

[F12] CSV 读写
来源：http://dali.fengsongda.top/Article/details/gtaosfrors.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gtvesjslhc.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.daxiang520.top/Article/details/gtnvawmmro.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.shanyushiyangkeji.top/Article/details/gtehcfgqov.html

TS:   // 同上
来源：http://dali.havefunace.top/Article/details/gtjiifjraq.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.vqdsnc.cn/Article/details/gtgmofurwb.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.redwolf501.top/Article/details/gtxgwwoytk.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyvkgsjwu.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.ybcxt.top/Article/details/gtxqiyrlil.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaruhxawg.html

G. 面向对象
来源：http://dali.sysykeji.top/Article/details/gthjmbssdf.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtefcjdxsu.html

[G01] 定义类
来源：http://dali.shzxlz.cn/Article/details/gtjzharoja.html

Py:   class User: pass
来源：http://dali.nanxuanxn.top/Article/details/gtnppdhrtl.html

PHP:  class User {}
来源：http://dali.9152youxi.cn/Article/details/gthoibcpme.html

JS:   class User {}
来源：http://dali.zhongyouzk.top/Article/details/gtvutptdjo.html

TS:   class User { name: string = ""; }
来源：http://dali.guowangkeji.top/Article/details/gtirwzhlos.html

Java: class User {}
来源：http://dali.snrcjt.cn/Article/details/gtjcabmsfk.html

Go:   type User struct { Name string }
来源：http://dali.daxiang520.top/Article/details/gtoqmszoxz.html

Ruby: class User; end
来源：http://dali.hnxiangtu.top/Article/details/gtezshieta.html

C#:   class User {}
来源：http://dali.tian-w.cn/Article/details/gtqpovssmq.html

[G02] 构造函数
来源：http://dali.haohaochexian.top/Article/details/gtrldwtnjr.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.bjfxy.top/Article/details/gtcyivrljp.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtojkycguk.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.tanke756.top/Article/details/gtqjrtgjva.html

TS:   constructor(public name: string) {}
来源：http://dali.jqgufenzy.top/Article/details/gtvwvyiwil.html

Java: User(String name) { this.name = name; }
来源：http://dali.jqgfzy.top/Article/details/gtukrswtph.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.ybcxt.top/Article/details/gtshizmytg.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtldfsydsm.html

C#:   public User(string name) { Name = name; }
来源：http://dali.sysykeji.top/Article/details/gtxqtkiwsw.html

[G03] 实例属性
来源：http://dali.dashuyun.cn/Article/details/gtummhnaoq.html

Py:   self.name = "x"
来源：http://dali.xuanzx.com/Article/details/gtztfntmzg.html

PHP:  public string $name = "x";
来源：http://dali.shangyingyoupin.top/Article/details/gtssirarcq.html

JS:   this.name = "x";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrcrywtxq.html

TS:   name: string = "x";
来源：http://dali.yj20258888.top/Article/details/gtbrzdpbpf.html

Java: private String name;
来源：http://dali.jinqigufen.top/Article/details/gtddylqrhh.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.shangyingyoupin.top/Article/details/gtcboudzed.html

Ruby: @name = "x"
来源：http://dali.gzhubu.top/Article/details/gtnitaqxql.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.kuanghao11.cn/Article/details/gtywhtvcag.html

[G04] 定义方法
来源：http://dali.vqdsnc.cn/Article/details/gtaxbgksym.html

Py:   def greet(self): return self.name
来源：http://dali.zycfv.cn/Article/details/gtahjgsoex.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.xuanzx.com/Article/details/gthjriekrb.html

JS:   greet() { return this.name; }
来源：http://dali.daria6918.cn/Article/details/gtidtymina.html

TS:   greet(): string { return this.name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtualcimrr.html

Java: String greet() { return name; }
来源：http://dali.zdqjudy.top/Article/details/gtcewzwiiy.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.aibaodan.cn/Article/details/gtfejyrotr.html

Ruby: def greet; @name; end
来源：http://dali.hfpthk.cn/Article/details/gtlzbwpgzu.html

C#:   public string Greet() => Name;
来源：http://dali.redwolf501.top/Article/details/gtlcjojfnv.html

[G05] 继承
来源：http://dali.hysaishi.cn/Article/details/gtiijsusri.html

Py:   class Admin(User): pass
来源：http://dali.guowangkeji.top/Article/details/gtxforyegl.html

PHP:  class Admin extends User {}
来源：http://dali.shangyingyoupin.top/Article/details/gtspcnwchz.html

JS:   class Admin extends User {}
来源：http://dali.guannengcc.top/Article/details/gteapjlius.html

TS:   class Admin extends User {}
来源：http://dali.zycfv.cn/Article/details/gtavweufny.html

Java: class Admin extends User {}
来源：http://dali.jinqigfzy.top/Article/details/gtmvbtdysb.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zdqjudy.top/Article/details/gtgwyplgmb.html

Ruby: class Admin < User; end
来源：http://dali.9152youxi.cn/Article/details/gthmugbhgr.html

C#:   class Admin : User {}
来源：http://dali.chenjidiqi.icu/Article/details/gtmxhcmmgl.html

[G06] 重写方法
来源：http://dali.xylfe.cn/Article/details/gtgskbpntz.html

Py:   def greet(self): return "admin"
来源：http://dali.jinqigufen.top/Article/details/gtbxrwkwjt.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yj20258888.top/Article/details/gtrtdufwqr.html

JS:   greet() { return "admin"; }
来源：http://dali.yvedp.cn/Article/details/gtupwzuken.html

TS:   greet(): string { return "admin"; }
来源：http://dali.pengpengdd.cyou/Article/details/gtensjwxel.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.meibo888.top/Article/details/gtmkswwsks.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.ppjwa.cn/Article/details/gtxgacsobn.html

Ruby: def greet; "admin"; end
来源：http://dali.quarkkingdee.top/Article/details/gtiwjdgmjq.html

C#:   public override string Greet() => "admin";
来源：http://dali.xuetiantiany.cn/Article/details/gtqryfwcro.html

[G07] 调用父类方法
来源：http://dali.quarkkingdee.top/Article/details/gtrsehtucj.html

Py:   super().greet()
来源：http://dali.jqgufenzy.top/Article/details/gtotpbygcq.html

PHP:  parent::greet();
来源：http://dali.sufxvd.cn/Article/details/gtzwlgohvx.html

JS:   super.greet();
来源：http://dali.c1oappe.top/Article/details/gtmwjdyqxd.html

TS:   super.greet();
来源：http://dali.aizwys.cn/Article/details/gtgzorbuxx.html

Java: super.greet();
来源：http://dali.yonumen.top/Article/details/gtvigdskne.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hongshengwenyu.top/Article/details/gtaaapxuik.html

Ruby: super
来源：http://dali.0kj1m.cn/Article/details/gtjvvcvfvc.html

C#:   base.Greet();
来源：http://dali.fzhhl.top/Article/details/gtvgyhcwkw.html

[G08] 静态方法与属性
来源：http://dali.wangshuangyany.cn/Article/details/gtzwwhvfvz.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.cdnleiting.top/Article/details/gthlfvcave.html

PHP:  public static function f() {}
来源：http://dali.chenjidiqi.icu/Article/details/gtscqerkld.html

JS:   static f() {}
来源：http://dali.daria6918.cn/Article/details/gtjioetheu.html

TS:   static f(): void {}
来源：http://dali.xylfe.cn/Article/details/gtghxzajhb.html

Java: static void f() {}
来源：http://dali.zdqjudy.top/Article/details/gtnpvhsran.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.sxryk.cn/Article/details/gtkvjbhxwg.html

Ruby: def self.f; end
来源：http://dali.yuxming.cn/Article/details/gtgflkparp.html

C#:   public static void F() {}
来源：http://dali.cheryme.top/Article/details/gtkulzvnlt.html

[G09] 接口 / 抽象类
来源：http://dali.yj20258888.top/Article/details/gtperwvwpa.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.ehwqpu.com/Article/details/gtwdxnrcpn.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.ydzc1.top/Article/details/gtrfvheynq.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.nanxuanxn.top/Article/details/gtkrzczqes.html

TS:   interface Shape { area(): number; }
来源：http://dali.ydzc1.top/Article/details/gthhvesjgg.html

Java: interface Shape { double area(); }
来源：http://dali.sweek.top/Article/details/gthsqcmzoa.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.aizwys.cn/Article/details/gtmiosbzen.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.nanxuanxn.top/Article/details/gtyajtymxv.html

C#:   interface IShape { double Area(); }
来源：http://dali.yj20258.top/Article/details/gtyuaxfpab.html

[G10] 访问控制
来源：http://dali.havefunace.top/Article/details/gtlngappql.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yongpay.top/Article/details/gtnyozsrap.html

PHP:  public / protected / private
来源：http://dali.sysykeji.top/Article/details/gtuemtqudl.html

JS:   #private 字段；其余公开
来源：http://dali.hongshengwenyu.top/Article/details/gtpscgqrzs.html

TS:   public / protected / private
来源：http://dali.zycfv.cn/Article/details/gtctzafnog.html

Java: public / protected / private / 默认包级
来源：http://dali.daria6918.cn/Article/details/gtttmfvyer.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.316326.xyz/Article/details/gtumnsdjyb.html

Ruby: public / protected / private
来源：http://dali.yvedp.cn/Article/details/gtmxhniyjj.html

C#:   public / protected / private / internal
来源：http://dali.sweek.top/Article/details/gtpdxdrjwn.html

[G11] getter / setter
来源：http://dali.iojbl.cn/Article/details/gtspdbqehn.html

Py:   @property 与 @x.setter
来源：http://dali.hywenlv.cn/Article/details/gttacwhynh.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xylfe.cn/Article/details/gtaxojafbr.html

JS:   get name() { return this._name; }
来源：http://dali.cucudq.cn/Article/details/gtravsvmgt.html

TS:   get name(): string { return this._name; }
来源：http://dali.gogol.net.cn/Article/details/gtidrzshvl.html

Java: public String getName() { return name; }
来源：http://dali.tanke756.top/Article/details/gtwlcnbfef.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.nanxinkj.top/Article/details/gteplytdbt.html

Ruby: attr_accessor :name
来源：http://dali.snrcjt.cn/Article/details/gtmfevlfzh.html

C#:   public string Name { get; set; }
来源：http://dali.zhixingplan.top/Article/details/gtfrdmxfnt.html

[G12] 对象转字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcfpjtrwq.html

Py:   def __str__(self): return self.name
来源：http://dali.daria6918.cn/Article/details/gtshinkcbx.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.vqdsnc.cn/Article/details/gtqgzowcoi.html

JS:   toString() { return this.name; }
来源：http://dali.yongpay.top/Article/details/gtfeupjgdn.html

TS:   toString(): string { return this.name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtuldlforb.html

Java: @Override public String toString() { return name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtmqhrtdoa.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.snrcjt.cn/Article/details/gtgowqovsm.html

Ruby: def to_s; @name; end
来源：http://dali.pycfn.com/Article/details/gtticlanag.html

C#:   public override string ToString() => Name;
来源：http://dali.zhengqikj.top/Article/details/gtlephmifm.html

[G13] 判断对象类型
来源：http://dali.sysykeji.top/Article/details/gtkthvcmff.html

Py:   isinstance(u, User)
来源：http://dali.iojbl.cn/Article/details/gtvgqardjo.html

PHP:  $u instanceof User
来源：http://dali.yongpay.top/Article/details/gtkgdfqlhr.html

JS:   u instanceof User
来源：http://dali.wangdashe.top/Article/details/gtbcabqggk.html

TS:   u instanceof User
来源：http://dali.chenjidiqi.icu/Article/details/gtynaawyqx.html

Java: u instanceof User
来源：http://dali.zhengqikj.top/Article/details/gtlqwghbqm.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhoulong.xyz/Article/details/gttzcsrzqm.html

Ruby: u.is_a?(User)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdpydrkrp.html

C#:   u is User
来源：http://dali.tian-w.cn/Article/details/gthxgljlwe.html

[G14] 数据类 / record
来源：http://dali.ywan-chungtsiang.top/Article/details/gthbrflukk.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.hnqzz.top/Article/details/gthhhouenu.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yuxming.cn/Article/details/gttwzxcfwv.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.9152youxi.cn/Article/details/gtspifkgqz.html

TS:   type User = { name: string; age: number };
来源：http://dali.jqgfzy.top/Article/details/gtgjwmuwdr.html

Java: record User(String name, int age) {}
来源：http://dali.xylfe.cn/Article/details/gtnpiqigjr.html

Go:   type User struct { Name string; Age int }
来源：http://dali.aibaodan.cn/Article/details/gttcrkxzhe.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.nanxuanxn.top/Article/details/gtezmsgkbt.html

C#:   record User(string Name, int Age);
来源：http://dali.zhixingplan.top/Article/details/gtzbtvykfx.html

[G15] 枚举
来源：http://dali.wangshuangyany.cn/Article/details/gtmfccaduf.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.fzhhl.top/Article/details/gtydhfgqdd.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ivvv.top/Article/details/gtowtiqblf.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.sxryk.cn/Article/details/gttkqxohao.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shuidangran.top/Article/details/gthgcxvqex.html

Java: enum Color { RED, GREEN }
来源：http://dali.shangyingyoupin.top/Article/details/gthpfuwrje.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.cqqwz.cn/Article/details/gtwvokhxml.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jinghuilouyu.cn/Article/details/gtcofivxbt.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yj20258888.top/Article/details/gtqjdneelf.html

[G16] 对象转数组 / 字典
来源：http://dali.dianchejie.cn/Article/details/gtahbdgpxz.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhoulong.xyz/Article/details/gtxnsaspto.html

PHP:  get_object_vars($obj);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcvzvndxy.html

JS:   Object.entries(obj)
来源：http://dali.redwolf501.top/Article/details/gtblydlkrp.html

TS:   Object.entries(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gtqjgielwo.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.haohaochexian.top/Article/details/gtmusxuwxn.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.chenlongwang.top/Article/details/gtyhjltfuo.html

Ruby: obj.instance_variables
来源：http://dali.dianchejie.cn/Article/details/gtekgpztxr.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.ivvv.top/Article/details/gtqrrpoiqb.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtjweenqbu.html

H. 异常与错误处理
来源：http://dali.pengpengdd.cyou/Article/details/gtpphenene.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtfkgvjsxf.html

[H01] try / catch 基础
来源：http://dali.zdqjudy.top/Article/details/gtnhvophju.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.nanxinkj.top/Article/details/gtbsbvjzma.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.gzhubu.top/Article/details/gtwkqqeqmr.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.nanxinkj.top/Article/details/gtpeklcwzr.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yueranfly.top/Article/details/gtxofhxdso.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.smart0.xyz/Article/details/gtqdtztivr.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jinghuilouyu.cn/Article/details/gtphexnyyv.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.xylfe.cn/Article/details/gttktiswpl.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.cashguo.top/Article/details/gtkvymferv.html

[H02] finally / ensure 收尾
来源：http://dali.wangdashe.top/Article/details/gtnlgvrpvy.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yj20258.top/Article/details/gtltydgqbh.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yj20258888.top/Article/details/gtxniaotin.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.xinyue.icu/Article/details/gtelmtthnu.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.haohaochexian.top/Article/details/gterllrbki.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.pengpengdd.cyou/Article/details/gtwtgxjgay.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yj202588.top/Article/details/gtdwxnniuy.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.chenzaomai.com/Article/details/gttiohnsid.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.hnxiangtu.top/Article/details/gtvpgemgoj.html

[H03] 主动抛出异常
来源：http://dali.jinqigufen.top/Article/details/gtpbnrasok.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhiwuduotai.top/Article/details/gtpuaotpqo.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.aizwys.cn/Article/details/gtymfddrgy.html

JS:   throw new Error("错误信息");
来源：http://dali.gogol.net.cn/Article/details/gttdupjjhd.html

TS:   throw new Error("错误信息");
来源：http://dali.sxryk.cn/Article/details/gtqpswgagn.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.svipenyu.cn/Article/details/gtqkryzngq.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.sufxvd.cn/Article/details/gthwmtukzf.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.tian-w.cn/Article/details/gtxxcdqskj.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yj20258.top/Article/details/gtbkwerdqh.html

[H04] 自定义异常类型
来源：http://dali.yongpay.top/Article/details/gtxfwnwdki.html

Py:   class MyError(Exception): pass
来源：http://dali.zhiwuduotai.top/Article/details/gtvqebislt.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jinqigfzy.top/Article/details/gtqlxzympb.html

JS:   class MyError extends Error {}
来源：http://dali.zhijiandao.cn/Article/details/gtzchivqal.html

TS:   class MyError extends Error {}
来源：http://dali.shuidangran.top/Article/details/gtgbhvwhxy.html

Java: class MyException extends RuntimeException {}
来源：http://dali.haohaochexian.top/Article/details/gtkfsoxurw.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.vqdsnc.cn/Article/details/gtlujmqdwp.html

Ruby: class MyError < StandardError; end
来源：http://dali.wangshuangyany.cn/Article/details/gthgmdxmoh.html

C#:   class MyException : Exception {}
来源：http://dali.dianchejie.cn/Article/details/gtnbqlkkck.html

[H05] 捕获特定类型
来源：http://dali.aizwys.cn/Article/details/gtsyxlrmtq.html

Py:   except ValueError as e:
来源：http://dali.pengpengdd.cyou/Article/details/gtlcgcyigj.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jyoumei.cn/Article/details/gtvajnfmtd.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jqgfzy.top/Article/details/gtdnmvrcrc.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtloghppri.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.cdnleiting.top/Article/details/gtmvswdkic.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhengqikj.top/Article/details/gtyvormzmt.html

Ruby: rescue ArgumentError => e
来源：http://dali.gzhubu.top/Article/details/gtlursdjkw.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.ehwqpu.com/Article/details/gtuxtfiktc.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gtnneeudos.html

Py:   value = d.get("k") or default
来源：http://dali.yvedp.cn/Article/details/gtdhirvoxs.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.316326.xyz/Article/details/gtlvdhqfmu.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yvedp.cn/Article/details/gtsroclhwa.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.redwolf501.top/Article/details/gtwrqrxlsp.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.daxiang520.top/Article/details/gtiwaabaha.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.guannengcc.top/Article/details/gtktpdxnrw.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yonumen.top/Article/details/gtaxycdhev.html

C#:   obj?.A?.B ?? default
来源：http://dali.yonumen.top/Article/details/gthufpefgv.html

[H07] 断言
来源：http://dali.xylfe.cn/Article/details/gttmirrhzm.html

Py:   assert x > 0, "必须为正"
来源：http://dali.smart0.xyz/Article/details/gtaopnkrbx.html

PHP:  assert($x > 0);
来源：http://dali.yueranfly.top/Article/details/gtkvrcnudl.html

JS:   console.assert(x > 0);
来源：http://dali.zycfv.cn/Article/details/gtumpahfqg.html

TS:   console.assert(x > 0);
来源：http://dali.vqdsnc.cn/Article/details/gtzekfmpwf.html

Java: assert x > 0 : "必须为正";
来源：http://dali.aibaodan.cn/Article/details/gtdfmirphk.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.cashguo.top/Article/details/gtoasxmzwl.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvbfsvsja.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hfpthk.cn/Article/details/gtkpdlyzsc.html

[H08] 获取错误信息与堆栈
来源：http://dali.gaohongyu789.top/Article/details/gtgysrlulk.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yangfankeji.com/Article/details/gttozxggxm.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.chenlongwang.top/Article/details/gtidzuaskr.html

JS:   e.message;  e.stack
来源：http://dali.fengsongda.top/Article/details/gtkcjafxym.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.cheryme.top/Article/details/gtdutozkkv.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jiagoushi.top/Article/details/gtahvyxxlj.html

Go:   err.Error()
来源：http://dali.kuanghao11.cn/Article/details/gtoadiiswq.html

Ruby: e.message;  e.backtrace
来源：http://dali.yvedp.cn/Article/details/gtrakeneta.html

C#:   e.Message;  e.StackTrace
来源：http://dali.gotoacloud.top/Article/details/gtvztezsfr.html

[H09] 带错误码的异常
来源：http://dali.zhoulong.xyz/Article/details/gtgibywopb.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yj20258888.top/Article/details/gtouadihke.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.andypj.xyz/Article/details/gtrjicozzr.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.nwbrower.top/Article/details/gtemyawhvl.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jyoumei.cn/Article/details/gtgvgqrxxg.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.chenjidiqi.icu/Article/details/gtokrnkozd.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.daxiang520.top/Article/details/gtzrrztiak.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.haohaochexian.top/Article/details/gtddscruzs.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.gotoacloud.top/Article/details/gtegzusesh.html

[H10] 资源自动释放
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlvnsfokh.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwcfbwapo.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.sufxvd.cn/Article/details/gtfjoayjqj.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqboarbdn.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.fzhhl.top/Article/details/gtnswabyby.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.feifeiyinyue.top/Article/details/gtdoseulqu.html

Go:   defer f.Close()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuotwlydf.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.birdmap.top/Article/details/gtauhrvtjh.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwjdenemb.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtimzvscje.html

I. 正则表达式
来源：http://dali.cheryme.top/Article/details/gtvmbcfyob.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtcdvgcbyq.html

[I01] 判断是否匹配
来源：http://dali.wangshuangyany.cn/Article/details/gtgxppyomd.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.guowangkeji.top/Article/details/gtkkrlxnxn.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zycfv.cn/Article/details/gtxieoebtm.html

JS:   /\d+/.test(s)
来源：http://dali.pycfn.com/Article/details/gtowfjjbuz.html

TS:   /\d+/.test(s)
来源：http://dali.gaohongyu789.top/Article/details/gtvsjkreak.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.dianchejie.cn/Article/details/gtalqjkepe.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtupunfcno.html

Ruby: s.match?(/\d+/)
来源：http://dali.0kj1m.cn/Article/details/gtnuhsrpyt.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.shangyingyoupin.top/Article/details/gtnzfwklsq.html

[I02] 提取所有匹配
来源：http://dali.haohaochexian.top/Article/details/gtyeuswaav.html

Py:   re.findall(r"\d+", s)
来源：http://dali.aibaodan.cn/Article/details/gtpguovidy.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.jqgfzy.top/Article/details/gtpdpcttjy.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.jyoumei.cn/Article/details/gtnvixfjef.html

TS:   s.match(/\d+/g)
来源：http://dali.snrcjt.cn/Article/details/gtsenihldj.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.ybcxt.top/Article/details/gtvyvvhdth.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhixingplan.top/Article/details/gtcntbtanc.html

Ruby: s.scan(/\d+/)
来源：http://dali.cheryme.top/Article/details/gtljxjuhmn.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.quarkkingdee.top/Article/details/gtonficirr.html

[I03] 提取捕获分组
来源：http://dali.sufxvd.cn/Article/details/gtlhmeglic.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.ybcxt.top/Article/details/gteolgzbka.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.0kj1m.cn/Article/details/gtdhkhnvpk.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.xylfe.cn/Article/details/gtswceprws.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.hammf.cn/Article/details/gtopcixata.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.shzxlz.cn/Article/details/gtbzlieeya.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhixingplan.top/Article/details/gtelwdwqlt.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.sysykeji.top/Article/details/gtpourbysp.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.snrcjt.cn/Article/details/gtxpuozsmx.html

[I04] 正则替换
来源：http://dali.jinqigufen.top/Article/details/gtiyhuohwr.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hywenlv.cn/Article/details/gttccjbdyb.html


<!-- 参考信息 -->