代发 wailian999

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.cashguo.top/Article/details/gt2brolvxif.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jiagoushi.top/Article/details/gt2debdvdbi.html

[F11] 复制与移动文件
来源：http://dali.yonumen.top/Article/details/gt2ifqvfyjh.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2wakzejnw.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhixingplan.top/Article/details/gt2abxzmxli.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yongpay.top/Article/details/gt2fwszpyld.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2slmlirao.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.dianchejie.cn/Article/details/gt2vrznhuxz.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2djgemjza.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.tanke756.top/Article/details/gt2frtumqqf.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.sysykeji.top/Article/details/gt2tkcfysae.html

[F12] CSV 读写
来源：http://dali.zhengqikj.top/Article/details/gt2qpbaipws.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.0kj1m.cn/Article/details/gt2hxwbvfts.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.snrcjt.cn/Article/details/gt2yiglxdqk.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.nanxinkj.top/Article/details/gt2itwccbuk.html

TS:   // 同上
来源：http://dali.andypj.xyz/Article/details/gt2prbtzanu.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.wangshuangyany.cn/Article/details/gt2ruifevrn.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.dashuyun.cn/Article/details/gt2jtwszmou.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.feifeiyinyue.top/Article/details/gt2oubqsxnh.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jianghu66.top/Article/details/gt2mfersjyn.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2ezwehpim.html

G. 面向对象
来源：http://dali.cqqwz.cn/Article/details/gt2tpohxggk.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2ofskponn.html

[G01] 定义类
来源：http://dali.chenjidiqi.icu/Article/details/gt2kitrvjhy.html

Py:   class User: pass
来源：http://dali.hnxiangtu.top/Article/details/gt2jojsfbld.html

PHP:  class User {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2asojehch.html

JS:   class User {}
来源：http://dali.yj20258.top/Article/details/gt2oiqyctft.html

TS:   class User { name: string = ""; }
来源：http://dali.zhengqikj.top/Article/details/gt2ykxqeqxv.html

Java: class User {}
来源：http://dali.gogol.net.cn/Article/details/gt2ijabcxep.html

Go:   type User struct { Name string }
来源：http://dali.guannengcc.top/Article/details/gt2dbkicgdw.html

Ruby: class User; end
来源：http://dali.guowangkeji.top/Article/details/gt2qzwjutrr.html

C#:   class User {}
来源：http://dali.c1oappe.top/Article/details/gt2ixhcbxvp.html

[G02] 构造函数
来源：http://dali.jqgufenzy.top/Article/details/gt2qlkhahic.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.c1oappe.top/Article/details/gt2jmriatmw.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.tianlin.xyz/Article/details/gt2oqfgpjxu.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.nwbrower.top/Article/details/gt2sfisirrd.html

TS:   constructor(public name: string) {}
来源：http://dali.fzhhl.top/Article/details/gt2byntgmcy.html

Java: User(String name) { this.name = name; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2lysqvtrt.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.meibo888.top/Article/details/gt2qdwurcvw.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xpywbbfz.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jinqigufen.top/Article/details/gt2pknpfyou.html

[G03] 实例属性
来源：http://dali.xuanzx.com/Article/details/gt2qsdsasrd.html

Py:   self.name = "x"
来源：http://dali.jyoumei.cn/Article/details/gt2lilmtsew.html

PHP:  public string $name = "x";
来源：http://dali.gotoacloud.top/Article/details/gt2nmvqlfrv.html

JS:   this.name = "x";
来源：http://dali.aizwys.cn/Article/details/gt2hcaexwxr.html

TS:   name: string = "x";
来源：http://dali.cqqwz.cn/Article/details/gt2zeudcvtv.html

Java: private String name;
来源：http://dali.quarkkingdee.top/Article/details/gt2mafxjipx.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.sufxvd.cn/Article/details/gt2eiokcvet.html

Ruby: @name = "x"
来源：http://dali.fzhhl.top/Article/details/gt2bamluzmg.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.havefunace.top/Article/details/gt2vlzyttyu.html

[G04] 定义方法
来源：http://dali.yj20258888.top/Article/details/gt2indtdovr.html

Py:   def greet(self): return self.name
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kewwngbm.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.316326.xyz/Article/details/gt2fciahkkn.html

JS:   greet() { return this.name; }
来源：http://dali.pycfn.com/Article/details/gt2pvmziiqo.html

TS:   greet(): string { return this.name; }
来源：http://dali.vqdsnc.cn/Article/details/gt2dexcjwpy.html

Java: String greet() { return name; }
来源：http://dali.wangdashe.top/Article/details/gt2djlwtfiq.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.shuidangran.top/Article/details/gt2rypdvmev.html

Ruby: def greet; @name; end
来源：http://dali.hnqzz.top/Article/details/gt2qpnupcng.html

C#:   public string Greet() => Name;
来源：http://dali.wangdashe.top/Article/details/gt2czolkyjp.html

[G05] 继承
来源：http://dali.zhixingplan.top/Article/details/gt2ayxrslpa.html

Py:   class Admin(User): pass
来源：http://dali.yj202588.top/Article/details/gt2bqobiwxp.html

PHP:  class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2njlosmcj.html

JS:   class Admin extends User {}
来源：http://dali.snrcjt.cn/Article/details/gt2gsmmfrar.html

TS:   class Admin extends User {}
来源：http://dali.pycfn.com/Article/details/gt2tddazmdv.html

Java: class Admin extends User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cwwyzjqp.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xxbiyjzw.html

Ruby: class Admin < User; end
来源：http://dali.havefunace.top/Article/details/gt2aiyfzxxn.html

C#:   class Admin : User {}
来源：http://dali.ehwqpu.com/Article/details/gt2mmblwsrm.html

[G06] 重写方法
来源：http://dali.aibaodan.cn/Article/details/gt2lrvddkik.html

Py:   def greet(self): return "admin"
来源：http://dali.gogol.net.cn/Article/details/gt2czsebcan.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hnqzz.top/Article/details/gt2rjliheoq.html

JS:   greet() { return "admin"; }
来源：http://dali.dianchejie.cn/Article/details/gt2mhvctpgt.html

TS:   greet(): string { return "admin"; }
来源：http://dali.sufxvd.cn/Article/details/gt2qwhafrxz.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.gzhubu.top/Article/details/gt2fafxvbgp.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yanxiufei.cn/Article/details/gt2sznrmqck.html

Ruby: def greet; "admin"; end
来源：http://dali.aizwys.cn/Article/details/gt2etuihrjh.html

C#:   public override string Greet() => "admin";
来源：http://dali.cqqwz.cn/Article/details/gt2koxuqgmc.html

[G07] 调用父类方法
来源：http://dali.kuanghao11.cn/Article/details/gt2pkbcezdj.html

Py:   super().greet()
来源：http://dali.yuanzhike.top/Article/details/gt2lwnknxqh.html

PHP:  parent::greet();
来源：http://dali.yanxiufei.cn/Article/details/gt2nmwmjoyr.html

JS:   super.greet();
来源：http://dali.jyoumei.cn/Article/details/gt2ecyjslsk.html

TS:   super.greet();
来源：http://dali.yj20258888.top/Article/details/gt2hxzcvpdx.html

Java: super.greet();
来源：http://dali.meibo888.top/Article/details/gt2fbaxevay.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.wangdashe.top/Article/details/gt2iivjgkft.html

Ruby: super
来源：http://dali.aizwys.cn/Article/details/gt2hwbufgug.html

C#:   base.Greet();
来源：http://dali.sxryk.cn/Article/details/gt2mbexjefa.html

[G08] 静态方法与属性
来源：http://dali.cheryme.top/Article/details/gt2wnvrmyts.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hywenlv.cn/Article/details/gt2mfxzskqq.html

PHP:  public static function f() {}
来源：http://dali.tanke756.top/Article/details/gt2wwitiqbd.html

JS:   static f() {}
来源：http://dali.yanxiufei.cn/Article/details/gt2emjkxqtf.html

TS:   static f(): void {}
来源：http://dali.sweek.top/Article/details/gt2uijaepwf.html

Java: static void f() {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ggycfgpm.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yonumen.top/Article/details/gt2ojaytjqo.html

Ruby: def self.f; end
来源：http://dali.jqgfzy.top/Article/details/gt2wovbhchu.html

C#:   public static void F() {}
来源：http://dali.hywenlv.cn/Article/details/gt2viionsbp.html

[G09] 接口 / 抽象类
来源：http://dali.shuidangran.top/Article/details/gt2sjxxcuzu.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yj202588.top/Article/details/gt2lytjksks.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.andypj.xyz/Article/details/gt2dmfuicso.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yj20258888.top/Article/details/gt2glpcbpjj.html

TS:   interface Shape { area(): number; }
来源：http://dali.yangfankeji.com/Article/details/gt2vsegchcd.html

Java: interface Shape { double area(); }
来源：http://dali.gaohongyu789.top/Article/details/gt2eldekjgh.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.guowangkeji.top/Article/details/gt2bedmvcmd.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nvdakkgx.html

C#:   interface IShape { double Area(); }
来源：http://dali.jiagoushi.top/Article/details/gt2abjpogas.html

[G10] 访问控制
来源：http://dali.redwolf501.top/Article/details/gt2jjwiprbv.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yj20258888.top/Article/details/gt2hkxbtbvh.html

PHP:  public / protected / private
来源：http://dali.aibaodan.cn/Article/details/gt2ybscmqkg.html

JS:   #private 字段；其余公开
来源：http://dali.zhoulong.xyz/Article/details/gt2duicwhww.html

TS:   public / protected / private
来源：http://dali.xuetiantiany.cn/Article/details/gt2hutbyhxn.html

Java: public / protected / private / 默认包级
来源：http://dali.zhoulong.xyz/Article/details/gt2esbpkmnr.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.snrcjt.cn/Article/details/gt2jicfxrrh.html

Ruby: public / protected / private
来源：http://dali.xuanzx.com/Article/details/gt2strcueih.html

C#:   public / protected / private / internal
来源：http://dali.dashuyun.cn/Article/details/gt2skjmsymz.html

[G11] getter / setter
来源：http://dali.yuanzhike.top/Article/details/gt2ffwpmrvl.html

Py:   @property 与 @x.setter
来源：http://dali.xziqi.cn/Article/details/gt2holrejmd.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.bjfxy.top/Article/details/gt2gmvotsvd.html

JS:   get name() { return this._name; }
来源：http://dali.pycfn.com/Article/details/gt2tkfewmvj.html

TS:   get name(): string { return this._name; }
来源：http://dali.smart0.xyz/Article/details/gt2vbclxpod.html

Java: public String getName() { return name; }
来源：http://dali.tian-w.cn/Article/details/gt2edvhjdve.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.pengpengdd.cyou/Article/details/gt2kbsssusk.html

Ruby: attr_accessor :name
来源：http://dali.gaohongyu789.top/Article/details/gt2pyygogwt.html

C#:   public string Name { get; set; }
来源：http://dali.chenzaomai.com/Article/details/gt2xqfllthl.html

[G12] 对象转字符串
来源：http://dali.iojbl.cn/Article/details/gt2xviuatgp.html

Py:   def __str__(self): return self.name
来源：http://dali.hywenlv.cn/Article/details/gt2vqeqojkz.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.ppjwa.cn/Article/details/gt2kfgsgoxv.html

JS:   toString() { return this.name; }
来源：http://dali.yuxming.cn/Article/details/gt2pfmsulqw.html

TS:   toString(): string { return this.name; }
来源：http://dali.0kj1m.cn/Article/details/gt2tmmzkftd.html

Java: @Override public String toString() { return name; }
来源：http://dali.chenzaomai.com/Article/details/gt2dunwtqye.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.redwolf501.top/Article/details/gt2atopzjfx.html

Ruby: def to_s; @name; end
来源：http://dali.fengsongda.top/Article/details/gt2xrstjlmm.html

C#:   public override string ToString() => Name;
来源：http://dali.daria6918.cn/Article/details/gt2kqvbjjcg.html

[G13] 判断对象类型
来源：http://dali.zhiwuduotai.top/Article/details/gt2zlwxmjvc.html

Py:   isinstance(u, User)
来源：http://dali.yangfankeji.com/Article/details/gt2xcyeqdhy.html

PHP:  $u instanceof User
来源：http://dali.haohaochexian.top/Article/details/gt2ednyjmcy.html

JS:   u instanceof User
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2unpeencr.html

TS:   u instanceof User
来源：http://dali.gaohongyu789.top/Article/details/gt2jxqdlxoc.html

Java: u instanceof User
来源：http://dali.sufxvd.cn/Article/details/gt2kwcurofh.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.ybcxt.top/Article/details/gt2ekhyepzu.html

Ruby: u.is_a?(User)
来源：http://dali.tian-w.cn/Article/details/gt2hsplxzzn.html

C#:   u is User
来源：http://dali.xinyue.icu/Article/details/gt2gmpjqngl.html

[G14] 数据类 / record
来源：http://dali.yongpay.top/Article/details/gt2innnotrd.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yueranfly.top/Article/details/gt2xblgjadc.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2heqjsqxr.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.cdnleiting.top/Article/details/gt2eutlybml.html

TS:   type User = { name: string; age: number };
来源：http://dali.bjfxy.top/Article/details/gt2ntcaxuvp.html

Java: record User(String name, int age) {}
来源：http://dali.hnqzz.top/Article/details/gt2nmrjcqom.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yj20258888.top/Article/details/gt2qsueljkg.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zycfv.cn/Article/details/gt2wibekfvy.html

C#:   record User(string Name, int Age);
来源：http://dali.yuanzhike.top/Article/details/gt2fkdhnamx.html

[G15] 枚举
来源：http://dali.hnqzz.top/Article/details/gt2rceznsge.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.wangdashe.top/Article/details/gt2ihjehinz.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yvedp.cn/Article/details/gt2jachjqxe.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.dianchejie.cn/Article/details/gt2mymrrqqh.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.daxiang520.top/Article/details/gt2zmwycwtj.html

Java: enum Color { RED, GREEN }
来源：http://dali.316326.xyz/Article/details/gt2ugzftgwq.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.hywenlv.cn/Article/details/gt2hfszcnew.html

Ruby: Color = %i[red green].freeze
来源：http://dali.daxiang520.top/Article/details/gt2vkapxsnu.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sxryk.cn/Article/details/gt2lpdtjmtg.html

[G16] 对象转数组 / 字典
来源：http://dali.quarkkingdee.top/Article/details/gt2gwexloln.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2udqqlpyx.html

PHP:  get_object_vars($obj);
来源：http://dali.gzhubu.top/Article/details/gt2puufiffa.html

JS:   Object.entries(obj)
来源：http://dali.hnqzz.top/Article/details/gt2tmugkmvk.html

TS:   Object.entries(obj)
来源：http://dali.daxiang520.top/Article/details/gt2zxvfutrl.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yueranfly.top/Article/details/gt2orxsqtkj.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jqgfzy.top/Article/details/gt2jwlmkmuw.html

Ruby: obj.instance_variables
来源：http://dali.zhoulong.xyz/Article/details/gt2vopwudaz.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.316326.xyz/Article/details/gt2fkfrviic.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2urobvukt.html

H. 异常与错误处理
来源：http://dali.hongshengwenyu.top/Article/details/gt2dinobfnp.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2njwseiji.html

[H01] try / catch 基础
来源：http://dali.jinqigfzy.top/Article/details/gt2cjyxgayq.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.cheryme.top/Article/details/gt2wexdhbeh.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.ppjwa.cn/Article/details/gt2jnxedqpd.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhengqikj.top/Article/details/gt2uoqhebde.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jlsjyb.cn/Article/details/gt2gqrqnpyq.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.daria6918.cn/Article/details/gt2yigykuwu.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.chenjidiqi.icu/Article/details/gt2oagdfmzn.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.shangyingyoupin.top/Article/details/gt2qmeubjvf.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.guannengcc.top/Article/details/gt2vdwyrfxe.html

[H02] finally / ensure 收尾
来源：http://dali.nanxinkj.top/Article/details/gt2fndjufnd.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.wangdashe.top/Article/details/gt2uycyxnxy.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jqgufenzy.top/Article/details/gt2bcolzwlm.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.quarkkingdee.top/Article/details/gt2pjecllnv.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yj20258.top/Article/details/gt2wyzurlta.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.andypj.xyz/Article/details/gt2gddidhjt.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.meibo888.top/Article/details/gt2hupfmhqw.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.cdnleiting.top/Article/details/gt2siikknvq.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2emfcddfk.html

[H03] 主动抛出异常
来源：http://dali.jyoumei.cn/Article/details/gt2bkohfokw.html

Py:   raise ValueError("错误信息")
来源：http://dali.yueranfly.top/Article/details/gt2bcsyipxw.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.ybcxt.top/Article/details/gt2ahlppndz.html

JS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gt2dcxphobo.html

TS:   throw new Error("错误信息");
来源：http://dali.jqgfzy.top/Article/details/gt2psxnkwlh.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hnqzz.top/Article/details/gt2qusjadcn.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.svipenyu.cn/Article/details/gt2ecsuqvsb.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.daxiang520.top/Article/details/gt2fomvcnof.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.hnxiangtu.top/Article/details/gt2fgygmtwm.html

[H04] 自定义异常类型
来源：http://dali.sxryk.cn/Article/details/gt2jqkaltoc.html

Py:   class MyError(Exception): pass
来源：http://dali.aizwys.cn/Article/details/gt2oevhwxzv.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.hfpthk.cn/Article/details/gt2dwpharwl.html

JS:   class MyError extends Error {}
来源：http://dali.tanke756.top/Article/details/gt2owgcgidh.html

TS:   class MyError extends Error {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iwrkqyaw.html

Java: class MyException extends RuntimeException {}
来源：http://dali.daria6918.cn/Article/details/gt2focrxvki.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.haohaochexian.top/Article/details/gt2ruoipxkh.html

Ruby: class MyError < StandardError; end
来源：http://dali.tian-w.cn/Article/details/gt2rrslrbgx.html

C#:   class MyException : Exception {}
来源：http://dali.aizwys.cn/Article/details/gt2jhvkaoto.html

[H05] 捕获特定类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2houkkkbk.html

Py:   except ValueError as e:
来源：http://dali.svipenyu.cn/Article/details/gt2zwheddpj.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.pycfn.com/Article/details/gt2ahfwfocc.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.cqqwz.cn/Article/details/gt2itobiguz.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iakmdiei.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2hfwtohnt.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zycfv.cn/Article/details/gt2vrfefzkc.html

Ruby: rescue ArgumentError => e
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tglrlcmr.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.iojbl.cn/Article/details/gt2ldndoakc.html

[H06] 可选值 / 空值安全访问
来源：http://dali.9152youxi.cn/Article/details/gt2nmhvvedd.html

Py:   value = d.get("k") or default
来源：http://dali.yonumen.top/Article/details/gt2duefnxix.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.shuidangran.top/Article/details/gt2miwtgqbb.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.zhixingplan.top/Article/details/gt2uogwdfek.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.iojbl.cn/Article/details/gt2znbtvwid.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.9152youxi.cn/Article/details/gt2kehbxodc.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.hywenlv.cn/Article/details/gt2kjcshhny.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jqgufenzy.top/Article/details/gt2gndnezjy.html

C#:   obj?.A?.B ?? default
来源：http://dali.jinqigfzy.top/Article/details/gt2zhqgkwhc.html

[H07] 断言
来源：http://dali.zhoulong.xyz/Article/details/gt2nnupgqpv.html

Py:   assert x > 0, "必须为正"
来源：http://dali.mhx1999.top/Article/details/gt2lwlmfqgq.html

PHP:  assert($x > 0);
来源：http://dali.cashguo.top/Article/details/gt2rtfhynuo.html

JS:   console.assert(x > 0);
来源：http://dali.zhengqikj.top/Article/details/gt2yuoinxjf.html

TS:   console.assert(x > 0);
来源：http://dali.fzhhl.top/Article/details/gt2qnnltqby.html

Java: assert x > 0 : "必须为正";
来源：http://dali.hongshengwenyu.top/Article/details/gt2tfqqxzzg.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.daxiang520.top/Article/details/gt2nkhuacdm.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhoulong.xyz/Article/details/gt2phfyzaua.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yuanzhike.top/Article/details/gt2hlqvkhjx.html

[H08] 获取错误信息与堆栈
来源：http://dali.yj202588.top/Article/details/gt2jhsentza.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.gotoacloud.top/Article/details/gt2ldbvejen.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.c1oappe.top/Article/details/gt2ilubktje.html

JS:   e.message;  e.stack
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xxwkyqja.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.dianchejie.cn/Article/details/gt2jqhmxpym.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhongyouzk.top/Article/details/gt2olkgtipc.html

Go:   err.Error()
来源：http://dali.fengsongda.top/Article/details/gt2xvweykzh.html

Ruby: e.message;  e.backtrace
来源：http://dali.shuidangran.top/Article/details/gt2cgxpsvvn.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jinqigfzy.top/Article/details/gt2fpbwffub.html

[H09] 带错误码的异常
来源：http://dali.zhengqikj.top/Article/details/gt2rcnyggbd.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.0kj1m.cn/Article/details/gt2zjuuyszk.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.snrcjt.cn/Article/details/gt2dvidkpgc.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhoulong.xyz/Article/details/gt2ofjdllgf.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pkbvkfdj.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2wqrhwutw.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.mhx1999.top/Article/details/gt2ifqqvyti.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.cucudq.cn/Article/details/gt2wywehlkg.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.sxryk.cn/Article/details/gt2ksetxrmv.html

[H10] 资源自动释放
来源：http://dali.wangshuangyany.cn/Article/details/gt2rvxfbyrd.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yj20258888.top/Article/details/gt2plranhue.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.cashguo.top/Article/details/gt2ricfcwim.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.c1oappe.top/Article/details/gt2nrwddzbv.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.birdmap.top/Article/details/gt2jwbfaiek.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.birdmap.top/Article/details/gt2fssxetli.html

Go:   defer f.Close()
来源：http://dali.cdnleiting.top/Article/details/gt2incsiuug.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.svipenyu.cn/Article/details/gt2tzqvixjq.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gxifkwix.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2hywygvqc.html

I. 正则表达式
来源：http://dali.yongpay.top/Article/details/gt2cotjkhws.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2yzllgfvt.html

[I01] 判断是否匹配
来源：http://dali.316326.xyz/Article/details/gt2evduszyu.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.ivvv.top/Article/details/gt2qwjyvhgr.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jinqigufen.top/Article/details/gt2meoarbrb.html

JS:   /\d+/.test(s)
来源：http://dali.ivvv.top/Article/details/gt2tjsmltxs.html

TS:   /\d+/.test(s)
来源：http://dali.0kj1m.cn/Article/details/gt2ufjjigtv.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.xylfe.cn/Article/details/gt2ekraqvfh.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.yuanzhike.top/Article/details/gt2teoyjscx.html

Ruby: s.match?(/\d+/)
来源：http://dali.meibo888.top/Article/details/gt2xkfowcrw.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.zhongyouzk.top/Article/details/gt2fdzyfwqx.html

[I02] 提取所有匹配
来源：http://dali.yj202588.top/Article/details/gt2qnpqimpe.html

Py:   re.findall(r"\d+", s)
来源：http://dali.tianlin.xyz/Article/details/gt2yumpngkf.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.snrcjt.cn/Article/details/gt2trdjltzp.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.nwbrower.top/Article/details/gt2dasuqtuf.html

TS:   s.match(/\d+/g)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tcsgsjid.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zdqjudy.top/Article/details/gt2zknfeolx.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.0kj1m.cn/Article/details/gt2dvrixrko.html

Ruby: s.scan(/\d+/)
来源：http://dali.pycfn.com/Article/details/gt2tvehtuhx.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.haohaochexian.top/Article/details/gt2ezbnpbde.html

[I03] 提取捕获分组
来源：http://dali.yj202588.top/Article/details/gt2xxkycvte.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cfacntzi.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.zhoulong.xyz/Article/details/gt2clmvymsq.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.gaohongyu789.top/Article/details/gt2bnmswlsr.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.ehwqpu.com/Article/details/gt2poxaveas.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.yvedp.cn/Article/details/gt2tvdktyjs.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.wangshuangyany.cn/Article/details/gt2uajecbyb.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.shzxlz.cn/Article/details/gt2rytlnafn.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.xylfe.cn/Article/details/gt2vsdgbiuh.html

[I04] 正则替换
来源：http://dali.yongpay.top/Article/details/gt2mvqmtkmd.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2kchplftq.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gt2otucixuh.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yj202588.top/Article/details/gt2jpysfuux.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.daxiang520.top/Article/details/gt2wklbyrvn.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qvpmzjmf.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dolvecff.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.xziqi.cn/Article/details/gt2tdtzxjeo.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.wangshuangyany.cn/Article/details/gt2kbewwrpe.html

[I05] 按正则拆分
来源：http://dali.guowangkeji.top/Article/details/gt2ygvewims.html


<!-- 参考信息 -->