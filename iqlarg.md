代发 wailian999

[F09] 获取文件大小
来源：http://dali.kuanghao11.cn/Article/details/gtgxlxmuhj.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtgflxsobf.html

PHP:  filesize("a.txt");
来源：http://dali.fzhhl.top/Article/details/gttexaektr.html

JS:   fs.statSync("a.txt").size
来源：http://dali.guowangkeji.top/Article/details/gtkrprjwys.html

TS:   fs.statSync("a.txt").size
来源：http://dali.quarkkingdee.top/Article/details/gtbolttofw.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.sufxvd.cn/Article/details/gtnqdcltzr.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.tian-w.cn/Article/details/gtwqvkedfz.html

Ruby: File.size("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtiidwzxfi.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jinyuanbaomall.cn/Article/details/gtneeuvlel.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yj20258888.top/Article/details/gtawvrqhrm.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.ydzc1.top/Article/details/gtackxnjpp.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.nanxinkj.top/Article/details/gtcismyhee.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtujosioto.html

TS:   path.extname("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtulnulnpf.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.xinyue.icu/Article/details/gttbzaesjc.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtgukpytgh.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.meibo888.top/Article/details/gthfiqeaej.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtllzgwtot.html

[F11] 复制与移动文件
来源：http://dali.ybcxt.top/Article/details/gtvongmzxm.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhengqikj.top/Article/details/gtllrrcczn.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.hysaishi.cn/Article/details/gtdzeodquv.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtczzgzuwh.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jqgfzy.top/Article/details/gtovtlmiqp.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.shuidangran.top/Article/details/gtwbltmsce.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.cheryme.top/Article/details/gtpxpaiuwc.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.shuidangran.top/Article/details/gtofefitee.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.dashuyun.cn/Article/details/gtwwpamuol.html

[F12] CSV 读写
来源：http://dali.yvedp.cn/Article/details/gttrdiaura.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zycfv.cn/Article/details/gtqijvdesy.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.guannengcc.top/Article/details/gtlnmyhnir.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.vqdsnc.cn/Article/details/gthfnbztrx.html

TS:   // 同上
来源：http://dali.zhiwuduotai.top/Article/details/gtiggisarr.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yuxming.cn/Article/details/gtfapuwful.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.ppjwa.cn/Article/details/gtireqoloo.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.sufxvd.cn/Article/details/gtlsgiviao.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jianghu66.top/Article/details/gtnvcvwgry.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtcrmbyyim.html

G. 面向对象
来源：http://dali.nanxuanxn.top/Article/details/gtgdswlfib.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtjtuyjbbz.html

[G01] 定义类
来源：http://dali.tian-w.cn/Article/details/gtowhinopy.html

Py:   class User: pass
来源：http://dali.bjfxy.top/Article/details/gtkypkgerd.html

PHP:  class User {}
来源：http://dali.jiagoushi.top/Article/details/gtftcsqidj.html

JS:   class User {}
来源：http://dali.ybcxt.top/Article/details/gtwxvrehxf.html

TS:   class User { name: string = ""; }
来源：http://dali.jinqigufen.top/Article/details/gtphtkyzal.html

Java: class User {}
来源：http://dali.tanke756.top/Article/details/gteycdowsx.html

Go:   type User struct { Name string }
来源：http://dali.fzhhl.top/Article/details/gtzixcfbnu.html

Ruby: class User; end
来源：http://dali.jqgfzy.top/Article/details/gtrfvbxden.html

C#:   class User {}
来源：http://dali.zdqjudy.top/Article/details/gtzgtugazb.html

[G02] 构造函数
来源：http://dali.birdmap.top/Article/details/gtlidtyxcz.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.0kj1m.cn/Article/details/gtgwfkzegn.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.ehwqpu.com/Article/details/gtjjhailqr.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtfatkjjzj.html

TS:   constructor(public name: string) {}
来源：http://dali.c1oappe.top/Article/details/gtttkcexvl.html

Java: User(String name) { this.name = name; }
来源：http://dali.xuanzx.com/Article/details/gtforebdbf.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jinqigufen.top/Article/details/gtbedcvyjt.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.316326.xyz/Article/details/gtnuejqoku.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yonumen.top/Article/details/gtcvtcivsd.html

[G03] 实例属性
来源：http://dali.yj20258888.top/Article/details/gtjyqazmif.html

Py:   self.name = "x"
来源：http://dali.zhiwuduotai.top/Article/details/gtixppgjob.html

PHP:  public string $name = "x";
来源：http://dali.snrcjt.cn/Article/details/gtxoktugms.html

JS:   this.name = "x";
来源：http://dali.cucudq.cn/Article/details/gtczrgbatr.html

TS:   name: string = "x";
来源：http://dali.hammf.cn/Article/details/gtmutbdenm.html

Java: private String name;
来源：http://dali.jyoumei.cn/Article/details/gtnnckatcg.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yonumen.top/Article/details/gtxbxejuat.html

Ruby: @name = "x"
来源：http://dali.gaohongyu789.top/Article/details/gtmljfylgw.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.xuetiantiany.cn/Article/details/gtofkmykcq.html

[G04] 定义方法
来源：http://dali.dianchejie.cn/Article/details/gtdfnoisjn.html

Py:   def greet(self): return self.name
来源：http://dali.zhoulong.xyz/Article/details/gtymesbnec.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.daria6918.cn/Article/details/gtsdgusblt.html

JS:   greet() { return this.name; }
来源：http://dali.pycfn.com/Article/details/gtbbpaxami.html

TS:   greet(): string { return this.name; }
来源：http://dali.sweek.top/Article/details/gtjtxcyqdg.html

Java: String greet() { return name; }
来源：http://dali.daxiang520.top/Article/details/gtprugkcmt.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hywenlv.cn/Article/details/gtnjmgkudq.html

Ruby: def greet; @name; end
来源：http://dali.zhixingplan.top/Article/details/gthazljmyu.html

C#:   public string Greet() => Name;
来源：http://dali.ivvv.top/Article/details/gttkjdmkgc.html

[G05] 继承
来源：http://dali.zhengqikj.top/Article/details/gtbwyyqool.html

Py:   class Admin(User): pass
来源：http://dali.ivvv.top/Article/details/gthjxshzdf.html

PHP:  class Admin extends User {}
来源：http://dali.cdnleiting.top/Article/details/gtdbrrinyo.html

JS:   class Admin extends User {}
来源：http://dali.chenzaomai.com/Article/details/gtkhoucbit.html

TS:   class Admin extends User {}
来源：http://dali.sweek.top/Article/details/gtlnlwngjt.html

Java: class Admin extends User {}
来源：http://dali.cdnleiting.top/Article/details/gtfaurgflb.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ydzc1.top/Article/details/gtxivtzzxi.html

Ruby: class Admin < User; end
来源：http://dali.ybcxt.top/Article/details/gtyncjvowt.html

C#:   class Admin : User {}
来源：http://dali.nwbrower.top/Article/details/gteiubfcsi.html

[G06] 重写方法
来源：http://dali.birdmap.top/Article/details/gtwknqvvnl.html

Py:   def greet(self): return "admin"
来源：http://dali.nwbrower.top/Article/details/gtgjtnzdnj.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yuxming.cn/Article/details/gtyqdtuoxf.html

JS:   greet() { return "admin"; }
来源：http://dali.zycfv.cn/Article/details/gtfiaebnru.html

TS:   greet(): string { return "admin"; }
来源：http://dali.ehwqpu.com/Article/details/gtjyqsnvna.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.aibaodan.cn/Article/details/gtezxfpogv.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.tian-w.cn/Article/details/gtvyifwass.html

Ruby: def greet; "admin"; end
来源：http://dali.shzxlz.cn/Article/details/gtvufuevvk.html

C#:   public override string Greet() => "admin";
来源：http://dali.dashuyun.cn/Article/details/gtepivrbke.html

[G07] 调用父类方法
来源：http://dali.0kj1m.cn/Article/details/gtudxpuzxq.html

Py:   super().greet()
来源：http://dali.shangyingyoupin.top/Article/details/gtvbyqcvub.html

PHP:  parent::greet();
来源：http://dali.shzxlz.cn/Article/details/gtenuxkigu.html

JS:   super.greet();
来源：http://dali.hnxiangtu.top/Article/details/gtbklpogtc.html

TS:   super.greet();
来源：http://dali.chenzaomai.com/Article/details/gtiwvturxv.html

Java: super.greet();
来源：http://dali.hnxiangtu.top/Article/details/gtypgjzbdk.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdwknqsly.html

Ruby: super
来源：http://dali.yj20258.top/Article/details/gttgdgzolq.html

C#:   base.Greet();
来源：http://dali.ybcxt.top/Article/details/gtzqkacqbc.html

[G08] 静态方法与属性
来源：http://dali.yonumen.top/Article/details/gtdcahjmzb.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hammf.cn/Article/details/gteiabrsxb.html

PHP:  public static function f() {}
来源：http://dali.nanxinkj.top/Article/details/gtifmjzfik.html

JS:   static f() {}
来源：http://dali.hnqzz.top/Article/details/gtzgurvabd.html

TS:   static f(): void {}
来源：http://dali.zhijiandao.cn/Article/details/gtnrnqoyfd.html

Java: static void f() {}
来源：http://dali.smart0.xyz/Article/details/gtgnovjguh.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jinqigufen.top/Article/details/gtfkmbykas.html

Ruby: def self.f; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfxafslei.html

C#:   public static void F() {}
来源：http://dali.pycfn.com/Article/details/gttkzebxku.html

[G09] 接口 / 抽象类
来源：http://dali.iojbl.cn/Article/details/gtooocedeq.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.sysykeji.top/Article/details/gtfbmbczpx.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.meibo888.top/Article/details/gtabdhjtnx.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.nwbrower.top/Article/details/gtfwwdpxyc.html

TS:   interface Shape { area(): number; }
来源：http://dali.sysykeji.top/Article/details/gtfqcijuvt.html

Java: interface Shape { double area(); }
来源：http://dali.feifeiyinyue.top/Article/details/gttrexbksd.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.sysykeji.top/Article/details/gtztwnjxww.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yonumen.top/Article/details/gtvoupbqlh.html

C#:   interface IShape { double Area(); }
来源：http://dali.cucudq.cn/Article/details/gtracszcag.html

[G10] 访问控制
来源：http://dali.gzhubu.top/Article/details/gtroxhtupn.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.ivvv.top/Article/details/gtupkytqma.html

PHP:  public / protected / private
来源：http://dali.xylfe.cn/Article/details/gtzcxiswgu.html

JS:   #private 字段；其余公开
来源：http://dali.yonumen.top/Article/details/gtosvmrobi.html

TS:   public / protected / private
来源：http://dali.xuanzx.com/Article/details/gtyaebtyvh.html

Java: public / protected / private / 默认包级
来源：http://dali.yj20258.top/Article/details/gtvvlunskq.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.birdmap.top/Article/details/gtqqazfzic.html

Ruby: public / protected / private
来源：http://dali.jiagoushi.top/Article/details/gtvphprhng.html

C#:   public / protected / private / internal
来源：http://dali.cashguo.top/Article/details/gtutjjnmiv.html

[G11] getter / setter
来源：http://dali.yj20258.top/Article/details/gtpegohcgs.html

Py:   @property 与 @x.setter
来源：http://dali.nwbrower.top/Article/details/gtqlsuxtdf.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.chenlongwang.top/Article/details/gtcaargbfg.html

JS:   get name() { return this._name; }
来源：http://dali.vqdsnc.cn/Article/details/gtjvvgusyl.html

TS:   get name(): string { return this._name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtrntonerz.html

Java: public String getName() { return name; }
来源：http://dali.ybcxt.top/Article/details/gtxvjdsfon.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.hnxiangtu.top/Article/details/gtxalpwgzq.html

Ruby: attr_accessor :name
来源：http://dali.jyoumei.cn/Article/details/gtklnwhfjq.html

C#:   public string Name { get; set; }
来源：http://dali.iojbl.cn/Article/details/gtceghzoph.html

[G12] 对象转字符串
来源：http://dali.tianlin.xyz/Article/details/gtlmtkiphp.html

Py:   def __str__(self): return self.name
来源：http://dali.hammf.cn/Article/details/gtfqwjhnkm.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtmjaykcep.html

JS:   toString() { return this.name; }
来源：http://dali.aibaodan.cn/Article/details/gtzoncdyan.html

TS:   toString(): string { return this.name; }
来源：http://dali.guowangkeji.top/Article/details/gtwlgmqcnw.html

Java: @Override public String toString() { return name; }
来源：http://dali.meibo888.top/Article/details/gtrekyvcjz.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.gotoacloud.top/Article/details/gtsupmmpcd.html

Ruby: def to_s; @name; end
来源：http://dali.yonumen.top/Article/details/gtibzhpsvx.html

C#:   public override string ToString() => Name;
来源：http://dali.zycfv.cn/Article/details/gtusfxldsb.html

[G13] 判断对象类型
来源：http://dali.gzhubu.top/Article/details/gtatabfvxm.html

Py:   isinstance(u, User)
来源：http://dali.havefunace.top/Article/details/gttagicfux.html

PHP:  $u instanceof User
来源：http://dali.zhongyouzk.top/Article/details/gtuxxpzjdb.html

JS:   u instanceof User
来源：http://dali.gotoacloud.top/Article/details/gtnpcbyyfq.html

TS:   u instanceof User
来源：http://dali.yj202588.top/Article/details/gtzsvrfvwa.html

Java: u instanceof User
来源：http://dali.fzhhl.top/Article/details/gtlgmpavwo.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.cheryme.top/Article/details/gtsuggefxs.html

Ruby: u.is_a?(User)
来源：http://dali.nwbrower.top/Article/details/gtfocdlnof.html

C#:   u is User
来源：http://dali.haohaochexian.top/Article/details/gttljdlliq.html

[G14] 数据类 / record
来源：http://dali.xuetiantiany.cn/Article/details/gtwxtnrcnv.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.xuanzx.com/Article/details/gtdbpodtwe.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yanxiufei.cn/Article/details/gtqpvplahe.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yuxming.cn/Article/details/gtiqqrlbze.html

TS:   type User = { name: string; age: number };
来源：http://dali.aizwys.cn/Article/details/gtwuipzkuu.html

Java: record User(String name, int age) {}
来源：http://dali.sufxvd.cn/Article/details/gtrpohvhua.html

Go:   type User struct { Name string; Age int }
来源：http://dali.9152youxi.cn/Article/details/gtijwqszkx.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfmhikqre.html

C#:   record User(string Name, int Age);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlvjrxsck.html

[G15] 枚举
来源：http://dali.yj20258888.top/Article/details/gthwftbkvm.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.sufxvd.cn/Article/details/gtrsmobmqd.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.gaohongyu789.top/Article/details/gtnmreqebq.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jlsjyb.cn/Article/details/gtxetminyf.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.tian-w.cn/Article/details/gtyemtxlqu.html

Java: enum Color { RED, GREEN }
来源：http://dali.zycfv.cn/Article/details/gtsfohncyb.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.feifeiyinyue.top/Article/details/gtxguplwjt.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ehwqpu.com/Article/details/gtgktmhvmu.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sysykeji.top/Article/details/gtblybqrtq.html

[G16] 对象转数组 / 字典
来源：http://dali.hnqzz.top/Article/details/gtlhqtgzmz.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.wangdashe.top/Article/details/gtzelxmbbs.html

PHP:  get_object_vars($obj);
来源：http://dali.daxiang520.top/Article/details/gtbcodwmzv.html

JS:   Object.entries(obj)
来源：http://dali.jyoumei.cn/Article/details/gtueqmioap.html

TS:   Object.entries(obj)
来源：http://dali.jiagoushi.top/Article/details/gtsuqgmeuh.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hysaishi.cn/Article/details/gtmwlkxeat.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.birdmap.top/Article/details/gtjmrmoxsn.html

Ruby: obj.instance_variables
来源：http://dali.sweek.top/Article/details/gtsycnqriq.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.feifeiyinyue.top/Article/details/gtplxvsawv.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtgwzbskto.html

H. 异常与错误处理
来源：http://dali.ehwqpu.com/Article/details/gtzakwxmal.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtpeokrlom.html

[H01] try / catch 基础
来源：http://dali.daria6918.cn/Article/details/gtcpcvdbux.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.smart0.xyz/Article/details/gtyvuzzqhh.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jqgufenzy.top/Article/details/gtlwfwjzna.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.smart0.xyz/Article/details/gtmsuuwulw.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.shzxlz.cn/Article/details/gtqohapwci.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.cucudq.cn/Article/details/gtjavbsvze.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.snrcjt.cn/Article/details/gtvbfqnbbc.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.kuanghao11.cn/Article/details/gtmrgtaudi.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ppjwa.cn/Article/details/gtspgtdhwa.html

[H02] finally / ensure 收尾
来源：http://dali.xinyue.icu/Article/details/gtvzmamygc.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.sufxvd.cn/Article/details/gtunobhukn.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.nanxinkj.top/Article/details/gtndumgbcq.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.wangdashe.top/Article/details/gtvwqdpurp.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.cucudq.cn/Article/details/gttezqxooy.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrxwiajiz.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yongpay.top/Article/details/gtinoocvbh.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.nanxinkj.top/Article/details/gtsvedzmbe.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.gogol.net.cn/Article/details/gtemdsmewd.html

[H03] 主动抛出异常
来源：http://dali.0kj1m.cn/Article/details/gtlpstulsf.html

Py:   raise ValueError("错误信息")
来源：http://dali.cashguo.top/Article/details/gtgcmdbuld.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hfpthk.cn/Article/details/gtxmpsrdhc.html

JS:   throw new Error("错误信息");
来源：http://dali.andypj.xyz/Article/details/gtqdksbteh.html

TS:   throw new Error("错误信息");
来源：http://dali.havefunace.top/Article/details/gtpqlgyddu.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.birdmap.top/Article/details/gtwhcbbido.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.9152youxi.cn/Article/details/gtdfrwwkam.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.vqdsnc.cn/Article/details/gtzhhaodyc.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.gzhubu.top/Article/details/gthxjgtkvl.html

[H04] 自定义异常类型
来源：http://dali.yj20258888.top/Article/details/gtlikstiom.html

Py:   class MyError(Exception): pass
来源：http://dali.yonumen.top/Article/details/gtirygrpnu.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zycfv.cn/Article/details/gteykhhedd.html

JS:   class MyError extends Error {}
来源：http://dali.xylfe.cn/Article/details/gthwveqfut.html

TS:   class MyError extends Error {}
来源：http://dali.havefunace.top/Article/details/gtmvyunjgv.html

Java: class MyException extends RuntimeException {}
来源：http://dali.fzhhl.top/Article/details/gtsqalhjic.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jqgfzy.top/Article/details/gtbubxtnto.html

Ruby: class MyError < StandardError; end
来源：http://dali.jyoumei.cn/Article/details/gtgwaqjdlr.html

C#:   class MyException : Exception {}
来源：http://dali.zhoulong.xyz/Article/details/gtmvysfxyc.html

[H05] 捕获特定类型
来源：http://dali.aibaodan.cn/Article/details/gtwlkyqplc.html

Py:   except ValueError as e:
来源：http://dali.svipenyu.cn/Article/details/gtseedsgna.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.fzhhl.top/Article/details/gtskwlwaje.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yj202588.top/Article/details/gtdcurfztt.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jlsjyb.cn/Article/details/gtmwgoauic.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.dianchejie.cn/Article/details/gtlkmgojsk.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yongpay.top/Article/details/gtccczbyso.html

Ruby: rescue ArgumentError => e
来源：http://dali.fzhhl.top/Article/details/gtmgsmjqju.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yongpay.top/Article/details/gtzwijcyue.html

[H06] 可选值 / 空值安全访问
来源：http://dali.gaohongyu789.top/Article/details/gtzzoiwopo.html

Py:   value = d.get("k") or default
来源：http://dali.havefunace.top/Article/details/gtidzxsjes.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.sufxvd.cn/Article/details/gtkpszrblt.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.9152youxi.cn/Article/details/gthwwapnds.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.sufxvd.cn/Article/details/gtvfsfzvqu.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.ywan-chungtsiang.top/Article/details/gttydfupcf.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.pycfn.com/Article/details/gtngsljfmn.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhoulong.xyz/Article/details/gtxztcbfja.html

C#:   obj?.A?.B ?? default
来源：http://dali.chenjidiqi.icu/Article/details/gtaqpxegla.html

[H07] 断言
来源：http://dali.sweek.top/Article/details/gtujihmpal.html

Py:   assert x > 0, "必须为正"
来源：http://dali.gzhubu.top/Article/details/gtefdrnlug.html

PHP:  assert($x > 0);
来源：http://dali.jqgfzy.top/Article/details/gtstfyoflh.html

JS:   console.assert(x > 0);
来源：http://dali.shangyingyoupin.top/Article/details/gtxzdqtxct.html

TS:   console.assert(x > 0);
来源：http://dali.jqgfzy.top/Article/details/gtaifcjwxu.html

Java: assert x > 0 : "必须为正";
来源：http://dali.mhx1999.top/Article/details/gtirhresgh.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.sweek.top/Article/details/gtyvymchoz.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.birdmap.top/Article/details/gtbyvrcwha.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yonumen.top/Article/details/gtnfzitgxz.html

[H08] 获取错误信息与堆栈
来源：http://dali.tanke756.top/Article/details/gtohxiqazj.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.nanxinkj.top/Article/details/gtkhgpbhac.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhoulong.xyz/Article/details/gtnxsyrtdz.html

JS:   e.message;  e.stack
来源：http://dali.smart0.xyz/Article/details/gtlksmvfxl.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmhpuuqdk.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhixingplan.top/Article/details/gtwwgaqdcu.html

Go:   err.Error()
来源：http://dali.jqgfzy.top/Article/details/gthvxcmole.html

Ruby: e.message;  e.backtrace
来源：http://dali.jlsjyb.cn/Article/details/gtjsuvmoan.html

C#:   e.Message;  e.StackTrace
来源：http://dali.birdmap.top/Article/details/gtpwlhbcvb.html

[H09] 带错误码的异常
来源：http://dali.jlsjyb.cn/Article/details/gtkubrghry.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.sxryk.cn/Article/details/gtyxrvvthl.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yonumen.top/Article/details/gtimjspkcp.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yongpay.top/Article/details/gtfwvlihvg.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzlwdidtb.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jqgufenzy.top/Article/details/gtdfnqwrqa.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.daxiang520.top/Article/details/gtaxzsfwno.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.daxiang520.top/Article/details/gtpckoxqtn.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.sxryk.cn/Article/details/gtklwvhpua.html

[H10] 资源自动释放
来源：http://dali.gzhubu.top/Article/details/gtyrwgoium.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.ivvv.top/Article/details/gtfllxeuba.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jinqigfzy.top/Article/details/gtpzrvgkbc.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.fzhhl.top/Article/details/gtmmxpglkj.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zdqjudy.top/Article/details/gtemeelyrm.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yj202588.top/Article/details/gtwswzuavj.html

Go:   defer f.Close()
来源：http://dali.aibaodan.cn/Article/details/gtovifryzd.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.iojbl.cn/Article/details/gtsmzvfnkc.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtttysemsd.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtgtajnyqf.html

I. 正则表达式
来源：http://dali.jqgfzy.top/Article/details/gtquxhzijd.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtblkveaar.html

[I01] 判断是否匹配
来源：http://dali.guannengcc.top/Article/details/gtcqjfltkw.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.mhx1999.top/Article/details/gtjwihwewc.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.iojbl.cn/Article/details/gtjdzqdtfx.html

JS:   /\d+/.test(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtsnuxeazd.html

TS:   /\d+/.test(s)
来源：http://dali.yj20258888.top/Article/details/gtgsbtzqyy.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jqgufenzy.top/Article/details/gtpxnzwumq.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.sweek.top/Article/details/gtjjoisbak.html

Ruby: s.match?(/\d+/)
来源：http://dali.jinqigufen.top/Article/details/gtycqittwi.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.meibo888.top/Article/details/gtcoaxduxz.html

[I02] 提取所有匹配
来源：http://dali.meibo888.top/Article/details/gtkucxdyda.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yj20258.top/Article/details/gttnhtgaew.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.guowangkeji.top/Article/details/gtxqgxqxxw.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.nanxinkj.top/Article/details/gtrisuayej.html

TS:   s.match(/\d+/g)
来源：http://dali.yvedp.cn/Article/details/gtcpyqzryx.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.shanyushiyangtech.top/Article/details/gtkdsbzykc.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.hnqzz.top/Article/details/gtcorhzgja.html

Ruby: s.scan(/\d+/)
来源：http://dali.hammf.cn/Article/details/gtmjgefxyf.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.wangdashe.top/Article/details/gtsornuucr.html

[I03] 提取捕获分组
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrxixmivm.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.ybcxt.top/Article/details/gtroeeflps.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.hysaishi.cn/Article/details/gtozdlzbca.html


<!-- 参考信息 -->