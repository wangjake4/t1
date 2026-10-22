代发 wailian999

C#:   new FileInfo("a.txt").Length
来源：http://dali.yj20258888.top/Article/details/gtualorxhw.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hammf.cn/Article/details/gtgzcuwcti.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtoprfpjlq.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gtponrnxze.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtldtmttis.html

TS:   path.extname("a.txt")
来源：http://dali.tian-w.cn/Article/details/gtgotqpekg.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.vqdsnc.cn/Article/details/gtiacbxtsq.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.fzhhl.top/Article/details/gtmnkqphbq.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yvedp.cn/Article/details/gtgicgpzsm.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.cheryme.top/Article/details/gtjnpicgka.html

[F11] 复制与移动文件
来源：http://dali.cqqwz.cn/Article/details/gtkoltimqc.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqdjzykes.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.hfpthk.cn/Article/details/gtzkzgauih.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jianghu66.top/Article/details/gtewalccfw.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.andypj.xyz/Article/details/gtlwsomrzw.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yvedp.cn/Article/details/gtocrcbyqm.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.iojbl.cn/Article/details/gtutgywtqz.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.redwolf501.top/Article/details/gtnfueysnj.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.haohaochexian.top/Article/details/gtsmoidpas.html

[F12] CSV 读写
来源：http://dali.yuanzhike.top/Article/details/gttzuaszrx.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.daxiang520.top/Article/details/gtgpkpqozg.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.chenlongwang.top/Article/details/gtlmjhekol.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yuanzhike.top/Article/details/gttkbkecjx.html

TS:   // 同上
来源：http://dali.hywenlv.cn/Article/details/gtjhkjbjup.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.xylfe.cn/Article/details/gtkdhvyqcb.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.sufxvd.cn/Article/details/gtwfmdcyic.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtheesgeao.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.sysykeji.top/Article/details/gtmnhncbtu.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgvcsihxd.html

G. 面向对象
来源：http://dali.hfpthk.cn/Article/details/gtvhuqdtbc.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gttqworlqj.html

[G01] 定义类
来源：http://dali.gogol.net.cn/Article/details/gtkwuqbzkd.html

Py:   class User: pass
来源：http://dali.fzhhl.top/Article/details/gtgcegzgws.html

PHP:  class User {}
来源：http://dali.guowangkeji.top/Article/details/gtlyajuhqb.html

JS:   class User {}
来源：http://dali.xylfe.cn/Article/details/gtridjvgck.html

TS:   class User { name: string = ""; }
来源：http://dali.tianlin.xyz/Article/details/gtsrhniser.html

Java: class User {}
来源：http://dali.zycfv.cn/Article/details/gtockvxjvs.html

Go:   type User struct { Name string }
来源：http://dali.sufxvd.cn/Article/details/gtcccjyfno.html

Ruby: class User; end
来源：http://dali.havefunace.top/Article/details/gtfkiogmlr.html

C#:   class User {}
来源：http://dali.sweek.top/Article/details/gtwtryklix.html

[G02] 构造函数
来源：http://dali.zhongyouzk.top/Article/details/gtgcxnnlac.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.sufxvd.cn/Article/details/gtbpfwwxgo.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.pengpengdd.cyou/Article/details/gttzipdzor.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.tanke756.top/Article/details/gtnptasyyh.html

TS:   constructor(public name: string) {}
来源：http://dali.yj20258.top/Article/details/gtkcikiyfz.html

Java: User(String name) { this.name = name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtflmvucuq.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.pycfn.com/Article/details/gtyyrhypqf.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.daria6918.cn/Article/details/gtmrknnuyx.html

C#:   public User(string name) { Name = name; }
来源：http://dali.havefunace.top/Article/details/gtltvxixxa.html

[G03] 实例属性
来源：http://dali.ybcxt.top/Article/details/gtqurfostb.html

Py:   self.name = "x"
来源：http://dali.jqgfzy.top/Article/details/gtuakjatsb.html

PHP:  public string $name = "x";
来源：http://dali.yj20258888.top/Article/details/gttqqzirfj.html

JS:   this.name = "x";
来源：http://dali.iojbl.cn/Article/details/gturzqirck.html

TS:   name: string = "x";
来源：http://dali.hywenlv.cn/Article/details/gtusrifxsh.html

Java: private String name;
来源：http://dali.zhiwuduotai.top/Article/details/gtpgukdnby.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.xziqi.cn/Article/details/gtqliqcomw.html

Ruby: @name = "x"
来源：http://dali.zycfv.cn/Article/details/gthauojnrg.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.shuidangran.top/Article/details/gtitzkprrl.html

[G04] 定义方法
来源：http://dali.sufxvd.cn/Article/details/gtgcwobxgg.html

Py:   def greet(self): return self.name
来源：http://dali.andypj.xyz/Article/details/gtajerftgo.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jinqigfzy.top/Article/details/gtmvkuflsx.html

JS:   greet() { return this.name; }
来源：http://dali.zhongyouzk.top/Article/details/gtrltprhcg.html

TS:   greet(): string { return this.name; }
来源：http://dali.tian-w.cn/Article/details/gtlkxvrsex.html

Java: String greet() { return name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtqgdzckfx.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.ppjwa.cn/Article/details/gtftanpjzj.html

Ruby: def greet; @name; end
来源：http://dali.haohaochexian.top/Article/details/gtuphyitjg.html

C#:   public string Greet() => Name;
来源：http://dali.hongshengwenyu.top/Article/details/gtzqnbdruh.html

[G05] 继承
来源：http://dali.meibo888.top/Article/details/gtfkzqmmgp.html

Py:   class Admin(User): pass
来源：http://dali.iojbl.cn/Article/details/gtklbdhyxa.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gtjmvuucdk.html

JS:   class Admin extends User {}
来源：http://dali.nanxinkj.top/Article/details/gtsatsdyfz.html

TS:   class Admin extends User {}
来源：http://dali.yuxming.cn/Article/details/gtzhbuvfgw.html

Java: class Admin extends User {}
来源：http://dali.svipenyu.cn/Article/details/gtvbccrggo.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jiagoushi.top/Article/details/gtanlwavpz.html

Ruby: class Admin < User; end
来源：http://dali.guowangkeji.top/Article/details/gtdecfahkr.html

C#:   class Admin : User {}
来源：http://dali.chenzaomai.com/Article/details/gteyuafpkp.html

[G06] 重写方法
来源：http://dali.ppjwa.cn/Article/details/gtaczdjpea.html

Py:   def greet(self): return "admin"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyrdefbon.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gtlmptbpbx.html

JS:   greet() { return "admin"; }
来源：http://dali.yueranfly.top/Article/details/gtfplcleli.html

TS:   greet(): string { return "admin"; }
来源：http://dali.nanxuanxn.top/Article/details/gtalgrtfvk.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.fengsongda.top/Article/details/gtcxszppjj.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.wangshuangyany.cn/Article/details/gtzdpvbjfg.html

Ruby: def greet; "admin"; end
来源：http://dali.chenjidiqi.icu/Article/details/gtvmoqqsbs.html

C#:   public override string Greet() => "admin";
来源：http://dali.yanxiufei.cn/Article/details/gtjkollnrp.html

[G07] 调用父类方法
来源：http://dali.yuanzhike.top/Article/details/gtbuummvrz.html

Py:   super().greet()
来源：http://dali.jlsjyb.cn/Article/details/gtckyxilxq.html

PHP:  parent::greet();
来源：http://dali.vqdsnc.cn/Article/details/gtfevznedk.html

JS:   super.greet();
来源：http://dali.ivvv.top/Article/details/gtzzkyhxbh.html

TS:   super.greet();
来源：http://dali.daria6918.cn/Article/details/gtgtqaclzz.html

Java: super.greet();
来源：http://dali.xuetiantiany.cn/Article/details/gtexhwxlje.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.ybcxt.top/Article/details/gtyfrmvkkt.html

Ruby: super
来源：http://dali.yvedp.cn/Article/details/gtjcsyuojp.html

C#:   base.Greet();
来源：http://dali.sweek.top/Article/details/gtkasuwxpd.html

[G08] 静态方法与属性
来源：http://dali.shuidangran.top/Article/details/gtqvfemifv.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxrmqpisw.html

PHP:  public static function f() {}
来源：http://dali.nanxuanxn.top/Article/details/gtfifhtlyl.html

JS:   static f() {}
来源：http://dali.yongpay.top/Article/details/gttroxddov.html

TS:   static f(): void {}
来源：http://dali.daria6918.cn/Article/details/gtarybcabn.html

Java: static void f() {}
来源：http://dali.yueranfly.top/Article/details/gtqnviysqr.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.mhx1999.top/Article/details/gthmvyfbou.html

Ruby: def self.f; end
来源：http://dali.hongshengwenyu.top/Article/details/gtnmjazxtb.html

C#:   public static void F() {}
来源：http://dali.haohaochexian.top/Article/details/gtkjjqrspu.html

[G09] 接口 / 抽象类
来源：http://dali.iojbl.cn/Article/details/gtmlctvldp.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jinqigufen.top/Article/details/gtnhbnsljk.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtewheyfkk.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hnqzz.top/Article/details/gtgmfpughg.html

TS:   interface Shape { area(): number; }
来源：http://dali.quarkkingdee.top/Article/details/gtrmegbuwg.html

Java: interface Shape { double area(); }
来源：http://dali.haohaochexian.top/Article/details/gtkxnxdbek.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.birdmap.top/Article/details/gtwwtorvbr.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jinghuilouyu.cn/Article/details/gtgoeoxqih.html

C#:   interface IShape { double Area(); }
来源：http://dali.daria6918.cn/Article/details/gtghjqaqjk.html

[G10] 访问控制
来源：http://dali.hongshengwenyu.top/Article/details/gtiizzmexv.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.ybcxt.top/Article/details/gtnwcvnoba.html

PHP:  public / protected / private
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfftzynik.html

JS:   #private 字段；其余公开
来源：http://dali.chenjidiqi.icu/Article/details/gtsuvgtjiu.html

TS:   public / protected / private
来源：http://dali.cheryme.top/Article/details/gtzfuzszrj.html

Java: public / protected / private / 默认包级
来源：http://dali.xziqi.cn/Article/details/gtjbaiqtip.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.nwbrower.top/Article/details/gtcbbddkvj.html

Ruby: public / protected / private
来源：http://dali.wangshuangyany.cn/Article/details/gtqgrgyuyw.html

C#:   public / protected / private / internal
来源：http://dali.zhongyouzk.top/Article/details/gtwqgvldly.html

[G11] getter / setter
来源：http://dali.chenjidiqi.icu/Article/details/gtxzidbood.html

Py:   @property 与 @x.setter
来源：http://dali.nwbrower.top/Article/details/gttlrbmyor.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.cashguo.top/Article/details/gtmoisblck.html

JS:   get name() { return this._name; }
来源：http://dali.gogol.net.cn/Article/details/gtlljuctht.html

TS:   get name(): string { return this._name; }
来源：http://dali.cashguo.top/Article/details/gtpkvmadrj.html

Java: public String getName() { return name; }
来源：http://dali.birdmap.top/Article/details/gtunwdkgmj.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.dashuyun.cn/Article/details/gtmnhxvobl.html

Ruby: attr_accessor :name
来源：http://dali.hnxiangtu.top/Article/details/gtnhnplddq.html

C#:   public string Name { get; set; }
来源：http://dali.zycfv.cn/Article/details/gtbafdpwlt.html

[G12] 对象转字符串
来源：http://dali.gzhubu.top/Article/details/gtbikoxdix.html

Py:   def __str__(self): return self.name
来源：http://dali.chenzaomai.com/Article/details/gtjhtyvvnv.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yj20258888.top/Article/details/gtovphyzlk.html

JS:   toString() { return this.name; }
来源：http://dali.vqdsnc.cn/Article/details/gtjeylxoqp.html

TS:   toString(): string { return this.name; }
来源：http://dali.zycfv.cn/Article/details/gthqxovhis.html

Java: @Override public String toString() { return name; }
来源：http://dali.redwolf501.top/Article/details/gtsgmgtffh.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.c1oappe.top/Article/details/gtoxojpanw.html

Ruby: def to_s; @name; end
来源：http://dali.zhengqikj.top/Article/details/gtwwxjaqpr.html

C#:   public override string ToString() => Name;
来源：http://dali.wangshuangyany.cn/Article/details/gtqofbjmaf.html

[G13] 判断对象类型
来源：http://dali.zhiwuduotai.top/Article/details/gtfxzucitt.html

Py:   isinstance(u, User)
来源：http://dali.ivvv.top/Article/details/gticwkumrn.html

PHP:  $u instanceof User
来源：http://dali.shzxlz.cn/Article/details/gtexotsddo.html

JS:   u instanceof User
来源：http://dali.shanyushiyangtech.top/Article/details/gtpxekxmvn.html

TS:   u instanceof User
来源：http://dali.smart0.xyz/Article/details/gtdthliesp.html

Java: u instanceof User
来源：http://dali.xuanzx.com/Article/details/gtmhiexbqa.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.fengsongda.top/Article/details/gtcbakdrnj.html

Ruby: u.is_a?(User)
来源：http://dali.shanyushiyangtech.top/Article/details/gtgdrxrwld.html

C#:   u is User
来源：http://dali.zhongyouzk.top/Article/details/gtolqnxsex.html

[G14] 数据类 / record
来源：http://dali.redwolf501.top/Article/details/gtnolrklut.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.hongshengwenyu.top/Article/details/gtotngmpzk.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwnqrbrwy.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbvbkztrj.html

TS:   type User = { name: string; age: number };
来源：http://dali.yuanzhike.top/Article/details/gtkjesoeor.html

Java: record User(String name, int age) {}
来源：http://dali.zdqjudy.top/Article/details/gtdaplovui.html

Go:   type User struct { Name string; Age int }
来源：http://dali.daria6918.cn/Article/details/gtncuwhdkx.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.meibo888.top/Article/details/gtiubzfjxd.html

C#:   record User(string Name, int Age);
来源：http://dali.xziqi.cn/Article/details/gtfvimkukb.html

[G15] 枚举
来源：http://dali.jqgufenzy.top/Article/details/gtedkfsfxo.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.sweek.top/Article/details/gtwsyetmyl.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yj20258888.top/Article/details/gtfidfrbxz.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.quarkkingdee.top/Article/details/gtuxnmtqsy.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.tanke756.top/Article/details/gtmayzayrb.html

Java: enum Color { RED, GREEN }
来源：http://dali.meibo888.top/Article/details/gtvqcqldix.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.tanke756.top/Article/details/gttggvlfdz.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ivvv.top/Article/details/gtkztkboeb.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.haohaochexian.top/Article/details/gtjzmrkreg.html

[G16] 对象转数组 / 字典
来源：http://dali.jqgufenzy.top/Article/details/gtweofqajo.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.shangyingyoupin.top/Article/details/gtnoebvslb.html

PHP:  get_object_vars($obj);
来源：http://dali.ppjwa.cn/Article/details/gtgpcotewz.html

JS:   Object.entries(obj)
来源：http://dali.cucudq.cn/Article/details/gtumdcaawk.html

TS:   Object.entries(obj)
来源：http://dali.chenzaomai.com/Article/details/gttdutdoba.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhoulong.xyz/Article/details/gtmoehpkcq.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.tian-w.cn/Article/details/gtwwffjoiy.html

Ruby: obj.instance_variables
来源：http://dali.iojbl.cn/Article/details/gtemhvdxmn.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.nwbrower.top/Article/details/gtbmfnvhjp.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtefhfddcr.html

H. 异常与错误处理
来源：http://dali.haohaochexian.top/Article/details/gtuyvjslbc.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtudfjxuba.html

[H01] try / catch 基础
来源：http://dali.shanyushiyangtech.top/Article/details/gtyqfcsxmv.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.sxryk.cn/Article/details/gtcxthmssa.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.gzhubu.top/Article/details/gtgqciuegu.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.iojbl.cn/Article/details/gthwvjdkxf.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.xuetiantiany.cn/Article/details/gtfmowxnzs.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.wangshuangyany.cn/Article/details/gtocfamcrv.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbnqftclg.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yj20258.top/Article/details/gtmskbakbz.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.shangyingyoupin.top/Article/details/gtfplwgffe.html

[H02] finally / ensure 收尾
来源：http://dali.tianlin.xyz/Article/details/gtdartvfjc.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.nwbrower.top/Article/details/gtygxholhm.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jiagoushi.top/Article/details/gtnoacsokc.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.cashguo.top/Article/details/gtnghujbcn.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zdqjudy.top/Article/details/gttjgagadw.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.ybcxt.top/Article/details/gtajrnrglj.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jqgufenzy.top/Article/details/gthpywsqkj.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.svipenyu.cn/Article/details/gtvjlheamz.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.cashguo.top/Article/details/gtiofskfak.html

[H03] 主动抛出异常
来源：http://dali.havefunace.top/Article/details/gtndqkuzxs.html

Py:   raise ValueError("错误信息")
来源：http://dali.jinqigfzy.top/Article/details/gtsohqwtnc.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.kuanghao11.cn/Article/details/gtggavqzlt.html

JS:   throw new Error("错误信息");
来源：http://dali.ivvv.top/Article/details/gtorhlnttl.html

TS:   throw new Error("错误信息");
来源：http://dali.9152youxi.cn/Article/details/gtyjctplnj.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.fengsongda.top/Article/details/gtyejyqacf.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.nwbrower.top/Article/details/gtpcphfzpg.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.aibaodan.cn/Article/details/gtsnqjlklg.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.sxryk.cn/Article/details/gtyavsvjjc.html

[H04] 自定义异常类型
来源：http://dali.yj20258888.top/Article/details/gtuopgkuao.html

Py:   class MyError(Exception): pass
来源：http://dali.sxryk.cn/Article/details/gttnwnqaof.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhixingplan.top/Article/details/gtvfxytocd.html

JS:   class MyError extends Error {}
来源：http://dali.dianchejie.cn/Article/details/gtiuqbfiqx.html

TS:   class MyError extends Error {}
来源：http://dali.cheryme.top/Article/details/gtnxsphvop.html

Java: class MyException extends RuntimeException {}
来源：http://dali.daxiang520.top/Article/details/gtbxufhumh.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.birdmap.top/Article/details/gthnzwqsyf.html

Ruby: class MyError < StandardError; end
来源：http://dali.hfpthk.cn/Article/details/gtxsngjcua.html

C#:   class MyException : Exception {}
来源：http://dali.daria6918.cn/Article/details/gtynaifvgi.html

[H05] 捕获特定类型
来源：http://dali.ydzc1.top/Article/details/gtygpbxomu.html

Py:   except ValueError as e:
来源：http://dali.hongshengwenyu.top/Article/details/gtynmqmvth.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gtirpujhxi.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.smart0.xyz/Article/details/gtjneapgws.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.cqqwz.cn/Article/details/gtjzholapr.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.quarkkingdee.top/Article/details/gtuyydsqql.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.svipenyu.cn/Article/details/gtwvjnvnmo.html

Ruby: rescue ArgumentError => e
来源：http://dali.nanxuanxn.top/Article/details/gtbsyrvhbq.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtqubxhcck.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yvedp.cn/Article/details/gtepmenihd.html

Py:   value = d.get("k") or default
来源：http://dali.hysaishi.cn/Article/details/gtpmymuwdm.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtodywplcm.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.gogol.net.cn/Article/details/gthklpgvdo.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jiagoushi.top/Article/details/gtxcpqwhgu.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.smart0.xyz/Article/details/gtymkfdfce.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jlsjyb.cn/Article/details/gtwlrkdmzg.html

Ruby: d&.dig(:a, :b)
来源：http://dali.wangshuangyany.cn/Article/details/gtrlmxrmgk.html

C#:   obj?.A?.B ?? default
来源：http://dali.jyoumei.cn/Article/details/gtbxzspbjt.html

[H07] 断言
来源：http://dali.ivvv.top/Article/details/gtvgytvimm.html

Py:   assert x > 0, "必须为正"
来源：http://dali.xziqi.cn/Article/details/gtvstxsdzt.html

PHP:  assert($x > 0);
来源：http://dali.xziqi.cn/Article/details/gthdefetvq.html

JS:   console.assert(x > 0);
来源：http://dali.nanxuanxn.top/Article/details/gtbppifzjw.html

TS:   console.assert(x > 0);
来源：http://dali.meibo888.top/Article/details/gtahtluhjx.html

Java: assert x > 0 : "必须为正";
来源：http://dali.mhx1999.top/Article/details/gtunxkzalh.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzuhfwilw.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yj20258.top/Article/details/gtlrlgpuhx.html

C#:   Debug.Assert(x > 0);
来源：http://dali.xylfe.cn/Article/details/gtuxxrdhdr.html

[H08] 获取错误信息与堆栈
来源：http://dali.hongshengwenyu.top/Article/details/gthkhkmohe.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.quarkkingdee.top/Article/details/gtbmvbkwkq.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.cdnleiting.top/Article/details/gtzpdmucol.html

JS:   e.message;  e.stack
来源：http://dali.sxryk.cn/Article/details/gtrkgltfdp.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhixingplan.top/Article/details/gtuqoxqgny.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.pycfn.com/Article/details/gtbadfdjoc.html

Go:   err.Error()
来源：http://dali.hfpthk.cn/Article/details/gtozunuikg.html

Ruby: e.message;  e.backtrace
来源：http://dali.gogol.net.cn/Article/details/gtidxnvoax.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jinyuanbaomall.cn/Article/details/gthtznlaae.html

[H09] 带错误码的异常
来源：http://dali.iojbl.cn/Article/details/gtwcndshdw.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.xinyue.icu/Article/details/gtzibupmxk.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yangfankeji.com/Article/details/gtymqqmcbd.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.ivvv.top/Article/details/gtphkyyimp.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhengqikj.top/Article/details/gtuldoasqq.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.ppjwa.cn/Article/details/gtfvzgvubd.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.shangyingyoupin.top/Article/details/gtukjjsaoo.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.cucudq.cn/Article/details/gtrfuetloq.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.fzhhl.top/Article/details/gtyragmdim.html

[H10] 资源自动释放
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuudcetos.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.shangyingyoupin.top/Article/details/gtdtruqnkg.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.meibo888.top/Article/details/gtbasugqou.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.nanxinkj.top/Article/details/gtpwhjrnwm.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyxbnhrfm.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yangfankeji.com/Article/details/gtxpiftqqe.html

Go:   defer f.Close()
来源：http://dali.smart0.xyz/Article/details/gtrhroyhbu.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.snrcjt.cn/Article/details/gtaqmuemew.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.nanxinkj.top/Article/details/gthafwkust.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtfwpgtrit.html

I. 正则表达式
来源：http://dali.zhaomingkeji.xyz/Article/details/gteqxrgkrv.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtgmtitgra.html

[I01] 判断是否匹配
来源：http://dali.jyoumei.cn/Article/details/gtwpbwzynk.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhixingplan.top/Article/details/gtttnakjno.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.ydzc1.top/Article/details/gtoxucmwzd.html

JS:   /\d+/.test(s)
来源：http://dali.hysaishi.cn/Article/details/gtulxvzqxo.html

TS:   /\d+/.test(s)
来源：http://dali.zhijiandao.cn/Article/details/gtmxxgeclj.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttctrfhmn.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jinqigufen.top/Article/details/gtmciwllbv.html

Ruby: s.match?(/\d+/)
来源：http://dali.yongpay.top/Article/details/gtecwhwvqg.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.c1oappe.top/Article/details/gtqsafymsz.html

[I02] 提取所有匹配
来源：http://dali.xziqi.cn/Article/details/gtdctqtxvx.html

Py:   re.findall(r"\d+", s)
来源：http://dali.chenzaomai.com/Article/details/gtcneszhbu.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.cucudq.cn/Article/details/gtjqtrakhn.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.wangdashe.top/Article/details/gtrcabiwih.html

TS:   s.match(/\d+/g)
来源：http://dali.aizwys.cn/Article/details/gttjytqlbg.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yuanzhike.top/Article/details/gtihbfevqi.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.gogol.net.cn/Article/details/gtgvmmcqvk.html

Ruby: s.scan(/\d+/)
来源：http://dali.wangshuangyany.cn/Article/details/gtvpfyjnah.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.xuetiantiany.cn/Article/details/gtvbmhhmxb.html

[I03] 提取捕获分组
来源：http://dali.tanke756.top/Article/details/gtqeggdigs.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.sysykeji.top/Article/details/gthmueazwd.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.sysykeji.top/Article/details/gthrlzdlwq.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhijiandao.cn/Article/details/gtpxzvkeuw.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.kuanghao11.cn/Article/details/gtkqsllscx.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.nwbrower.top/Article/details/gtzlehvuqg.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.tanke756.top/Article/details/gtlqeewpze.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.wangdashe.top/Article/details/gtmfhzpsip.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.c1oappe.top/Article/details/gtaasnkvnt.html

[I04] 正则替换
来源：http://dali.hysaishi.cn/Article/details/gtsuvndbtj.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.redwolf501.top/Article/details/gtcdasesja.html


<!-- 参考信息 -->