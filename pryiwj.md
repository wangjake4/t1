代发 wailian999

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gtstviolrg.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.c1oappe.top/Article/details/gtkxigglms.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.wangdashe.top/Article/details/gtjutsjfvq.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.kuanghao11.cn/Article/details/gtywxbdgvy.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.gaohongyu789.top/Article/details/gtgspvmaxx.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtlqbfqnui.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.bjfxy.top/Article/details/gtyqhmbbhz.html

[F12] CSV 读写
来源：http://dali.guannengcc.top/Article/details/gtgudajmxr.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.nanxuanxn.top/Article/details/gtihwuolxe.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.daxiang520.top/Article/details/gtijmoznkx.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhongyouzk.top/Article/details/gthlsvqdcp.html

TS:   // 同上
来源：http://dali.ydzc1.top/Article/details/gtmliqcoby.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.sufxvd.cn/Article/details/gtofpraxvs.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jqgufenzy.top/Article/details/gtapzghezi.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.bjfxy.top/Article/details/gtvurzcocn.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yanxiufei.cn/Article/details/gtyjbfwngy.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtgnbjtwhq.html

G. 面向对象
来源：http://dali.fengsongda.top/Article/details/gtdqrinmxi.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtgyfbkpcx.html

[G01] 定义类
来源：http://dali.zhaomingkeji.xyz/Article/details/gtosoyxegl.html

Py:   class User: pass
来源：http://dali.aizwys.cn/Article/details/gtrbkpvkgc.html

PHP:  class User {}
来源：http://dali.chenlongwang.top/Article/details/gtwvceqkyg.html

JS:   class User {}
来源：http://dali.nanxuanxn.top/Article/details/gtsusssgqp.html

TS:   class User { name: string = ""; }
来源：http://dali.feifeiyinyue.top/Article/details/gtgllpfdfq.html

Java: class User {}
来源：http://dali.yj20258888.top/Article/details/gtezlubexf.html

Go:   type User struct { Name string }
来源：http://dali.yuxming.cn/Article/details/gttkyqnbzb.html

Ruby: class User; end
来源：http://dali.c1oappe.top/Article/details/gtcxwfenlv.html

C#:   class User {}
来源：http://dali.yongpay.top/Article/details/gtwilhxojj.html

[G02] 构造函数
来源：http://dali.feifeiyinyue.top/Article/details/gtyfbgfofo.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.chenlongwang.top/Article/details/gtsgciwjrg.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jlsjyb.cn/Article/details/gtkfygygip.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.iojbl.cn/Article/details/gtknajcduh.html

TS:   constructor(public name: string) {}
来源：http://dali.shzxlz.cn/Article/details/gtczfxnvtq.html

Java: User(String name) { this.name = name; }
来源：http://dali.yj20258888.top/Article/details/gteecjoawu.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.pengpengdd.cyou/Article/details/gtjdbxvuzb.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.redwolf501.top/Article/details/gtnmrdzziq.html

C#:   public User(string name) { Name = name; }
来源：http://dali.gzhubu.top/Article/details/gtplckayqy.html

[G03] 实例属性
来源：http://dali.birdmap.top/Article/details/gtlkdvkrcd.html

Py:   self.name = "x"
来源：http://dali.jinqigfzy.top/Article/details/gtxoejhagj.html

PHP:  public string $name = "x";
来源：http://dali.feifeiyinyue.top/Article/details/gtowwgqzen.html

JS:   this.name = "x";
来源：http://dali.smart0.xyz/Article/details/gtzpkurbxk.html

TS:   name: string = "x";
来源：http://dali.jyoumei.cn/Article/details/gtimbtbeim.html

Java: private String name;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrkrkvbyw.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhoulong.xyz/Article/details/gthgrexfzo.html

Ruby: @name = "x"
来源：http://dali.yj202588.top/Article/details/gtekdhvqhd.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.meibo888.top/Article/details/gtnpuifjsm.html

[G04] 定义方法
来源：http://dali.cashguo.top/Article/details/gtiasvlpfs.html

Py:   def greet(self): return self.name
来源：http://dali.gaohongyu789.top/Article/details/gtcimgorgq.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtokhhyhid.html

JS:   greet() { return this.name; }
来源：http://dali.svipenyu.cn/Article/details/gteeinrwok.html

TS:   greet(): string { return this.name; }
来源：http://dali.tianlin.xyz/Article/details/gtulyeoafy.html

Java: String greet() { return name; }
来源：http://dali.pengpengdd.cyou/Article/details/gteozzoujn.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.chenlongwang.top/Article/details/gthpumhdzm.html

Ruby: def greet; @name; end
来源：http://dali.mhx1999.top/Article/details/gtfuivhgaw.html

C#:   public string Greet() => Name;
来源：http://dali.zycfv.cn/Article/details/gtkditaonv.html

[G05] 继承
来源：http://dali.shangyingyoupin.top/Article/details/gtgbamjvtp.html

Py:   class Admin(User): pass
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthtxodoro.html

PHP:  class Admin extends User {}
来源：http://dali.aizwys.cn/Article/details/gtyyqvyvub.html

JS:   class Admin extends User {}
来源：http://dali.nanxuanxn.top/Article/details/gtqjsouyjq.html

TS:   class Admin extends User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsskxmjem.html

Java: class Admin extends User {}
来源：http://dali.jqgfzy.top/Article/details/gtmkijgwqf.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.xuetiantiany.cn/Article/details/gtyqayubjk.html

Ruby: class Admin < User; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcvpvctdf.html

C#:   class Admin : User {}
来源：http://dali.xziqi.cn/Article/details/gtpyyukqut.html

[G06] 重写方法
来源：http://dali.zhoulong.xyz/Article/details/gtvrhkcukb.html

Py:   def greet(self): return "admin"
来源：http://dali.zhixingplan.top/Article/details/gtnraggsvf.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jyoumei.cn/Article/details/gtqdzhdvvz.html

JS:   greet() { return "admin"; }
来源：http://dali.shangyingyoupin.top/Article/details/gtjxdtssit.html

TS:   greet(): string { return "admin"; }
来源：http://dali.ppjwa.cn/Article/details/gtostilwps.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtbndcnvfo.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yuxming.cn/Article/details/gtpqoimrjf.html

Ruby: def greet; "admin"; end
来源：http://dali.ppjwa.cn/Article/details/gthpstblkh.html

C#:   public override string Greet() => "admin";
来源：http://dali.hnqzz.top/Article/details/gtzpaohehq.html

[G07] 调用父类方法
来源：http://dali.hnxiangtu.top/Article/details/gtyevxabcu.html

Py:   super().greet()
来源：http://dali.gaohongyu789.top/Article/details/gtcglmnkiq.html

PHP:  parent::greet();
来源：http://dali.jinqigfzy.top/Article/details/gtwaaohqip.html

JS:   super.greet();
来源：http://dali.hongshengwenyu.top/Article/details/gtbuhcysoz.html

TS:   super.greet();
来源：http://dali.iojbl.cn/Article/details/gtvhinoxwb.html

Java: super.greet();
来源：http://dali.hammf.cn/Article/details/gtkpptczgz.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gtetuenadu.html

Ruby: super
来源：http://dali.aizwys.cn/Article/details/gtdadgrlkl.html

C#:   base.Greet();
来源：http://dali.nwbrower.top/Article/details/gtbryauomz.html

[G08] 静态方法与属性
来源：http://dali.0kj1m.cn/Article/details/gtinbqplow.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhengqikj.top/Article/details/gtzwkspjea.html

PHP:  public static function f() {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtykvxwiip.html

JS:   static f() {}
来源：http://dali.yj20258888.top/Article/details/gtdcrhjjrz.html

TS:   static f(): void {}
来源：http://dali.chenlongwang.top/Article/details/gtyrcoxpol.html

Java: static void f() {}
来源：http://dali.9152youxi.cn/Article/details/gttyiahklo.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.birdmap.top/Article/details/gtbgpmcshc.html

Ruby: def self.f; end
来源：http://dali.aibaodan.cn/Article/details/gtoaczmkua.html

C#:   public static void F() {}
来源：http://dali.dashuyun.cn/Article/details/gtnmxtospn.html

[G09] 接口 / 抽象类
来源：http://dali.birdmap.top/Article/details/gtecirwzua.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.hongshengwenyu.top/Article/details/gtpxwialbh.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.ydzc1.top/Article/details/gteabxlouh.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.shanyushiyangkeji.top/Article/details/gtepnwqwcb.html

TS:   interface Shape { area(): number; }
来源：http://dali.gogol.net.cn/Article/details/gtgbycerix.html

Java: interface Shape { double area(); }
来源：http://dali.zhengqikj.top/Article/details/gtgfuvkzrq.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jyoumei.cn/Article/details/gttypglwju.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yj20258.top/Article/details/gtphlpsvqa.html

C#:   interface IShape { double Area(); }
来源：http://dali.iojbl.cn/Article/details/gtrudxkkhx.html

[G10] 访问控制
来源：http://dali.shanyushiyangkeji.top/Article/details/gthbdcnoun.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yueranfly.top/Article/details/gtxzezgyrd.html

PHP:  public / protected / private
来源：http://dali.sufxvd.cn/Article/details/gtmipgyiyk.html

JS:   #private 字段；其余公开
来源：http://dali.jiagoushi.top/Article/details/gttxyzuihw.html

TS:   public / protected / private
来源：http://dali.fzhhl.top/Article/details/gttcrpqgzl.html

Java: public / protected / private / 默认包级
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsffadqyh.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.0kj1m.cn/Article/details/gtwszpwtnf.html

Ruby: public / protected / private
来源：http://dali.c1oappe.top/Article/details/gtihnznsrc.html

C#:   public / protected / private / internal
来源：http://dali.cqqwz.cn/Article/details/gtwlsxugga.html

[G11] getter / setter
来源：http://dali.svipenyu.cn/Article/details/gtrtcbyfnn.html

Py:   @property 与 @x.setter
来源：http://dali.ppjwa.cn/Article/details/gtzsgggzhf.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.cashguo.top/Article/details/gtfvuggpzp.html

JS:   get name() { return this._name; }
来源：http://dali.xuanzx.com/Article/details/gthtjqzjuz.html

TS:   get name(): string { return this._name; }
来源：http://dali.smart0.xyz/Article/details/gtoxrfsczp.html

Java: public String getName() { return name; }
来源：http://dali.wangdashe.top/Article/details/gtphqbjwlc.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.redwolf501.top/Article/details/gtdqbkzoiv.html

Ruby: attr_accessor :name
来源：http://dali.yongpay.top/Article/details/gtialrjdtj.html

C#:   public string Name { get; set; }
来源：http://dali.hnqzz.top/Article/details/gtcweoejnx.html

[G12] 对象转字符串
来源：http://dali.tanke756.top/Article/details/gtdsynrewe.html

Py:   def __str__(self): return self.name
来源：http://dali.ppjwa.cn/Article/details/gtudboczji.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhengqikj.top/Article/details/gtvuewfqjn.html

JS:   toString() { return this.name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtxiaitykw.html

TS:   toString(): string { return this.name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfxsmmonq.html

Java: @Override public String toString() { return name; }
来源：http://dali.cheryme.top/Article/details/gtnctnfmfj.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hysaishi.cn/Article/details/gtvgbracur.html

Ruby: def to_s; @name; end
来源：http://dali.yuxming.cn/Article/details/gtcrbquqaj.html

C#:   public override string ToString() => Name;
来源：http://dali.dashuyun.cn/Article/details/gtsqabwvne.html

[G13] 判断对象类型
来源：http://dali.xziqi.cn/Article/details/gtnmeicvlx.html

Py:   isinstance(u, User)
来源：http://dali.hfpthk.cn/Article/details/gtmcnywgnk.html

PHP:  $u instanceof User
来源：http://dali.shanyushiyangtech.top/Article/details/gtyfmenyay.html

JS:   u instanceof User
来源：http://dali.feifeiyinyue.top/Article/details/gtenfrpxxu.html

TS:   u instanceof User
来源：http://dali.ehwqpu.com/Article/details/gtqydwcnfq.html

Java: u instanceof User
来源：http://dali.zhixingplan.top/Article/details/gtfnzdqmqc.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhoulong.xyz/Article/details/gtvgjxecar.html

Ruby: u.is_a?(User)
来源：http://dali.hysaishi.cn/Article/details/gtqdqturgt.html

C#:   u is User
来源：http://dali.zhengqikj.top/Article/details/gtpyibypmf.html

[G14] 数据类 / record
来源：http://dali.zhixingplan.top/Article/details/gtsqacugjs.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jyoumei.cn/Article/details/gtnhzmywha.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.sweek.top/Article/details/gttoqejafw.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.sweek.top/Article/details/gtkiywfcgl.html

TS:   type User = { name: string; age: number };
来源：http://dali.cdnleiting.top/Article/details/gtuulcvlsv.html

Java: record User(String name, int age) {}
来源：http://dali.hammf.cn/Article/details/gtoyeuoycr.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yj202588.top/Article/details/gtucjtpznp.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.dashuyun.cn/Article/details/gtdqrppljs.html

C#:   record User(string Name, int Age);
来源：http://dali.xziqi.cn/Article/details/gtuxhtnbbd.html

[G15] 枚举
来源：http://dali.zhiwuduotai.top/Article/details/gtlicnynac.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.haohaochexian.top/Article/details/gtyytvmmxd.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ehwqpu.com/Article/details/gtahxiiqnx.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhoulong.xyz/Article/details/gttobthslb.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sweek.top/Article/details/gtxkldsebd.html

Java: enum Color { RED, GREEN }
来源：http://dali.iojbl.cn/Article/details/gtqqvhgjib.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jinqigfzy.top/Article/details/gtcqhwaswt.html

Ruby: Color = %i[red green].freeze
来源：http://dali.guowangkeji.top/Article/details/gtldtenwpo.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xuetiantiany.cn/Article/details/gtgthomfye.html

[G16] 对象转数组 / 字典
来源：http://dali.dianchejie.cn/Article/details/gtzynecimk.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.shanyushiyangtech.top/Article/details/gtoqvhihqo.html

PHP:  get_object_vars($obj);
来源：http://dali.yj202588.top/Article/details/gtgvbbsusg.html

JS:   Object.entries(obj)
来源：http://dali.xinyue.icu/Article/details/gtlhkdwcpq.html

TS:   Object.entries(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtesiuukcu.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhiwuduotai.top/Article/details/gtzqpvwbkt.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.nanxinkj.top/Article/details/gtyupqmncw.html

Ruby: obj.instance_variables
来源：http://dali.vqdsnc.cn/Article/details/gtscxyxmax.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.c1oappe.top/Article/details/gtcudcfqzd.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtlxsjxxbx.html

H. 异常与错误处理
来源：http://dali.yuxming.cn/Article/details/gtobwxkkws.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gttiowmvqs.html

[H01] try / catch 基础
来源：http://dali.yj20258888.top/Article/details/gtzkycufnx.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.gotoacloud.top/Article/details/gtxgklubcv.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gttvpirfbx.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.svipenyu.cn/Article/details/gtnodrxsqd.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.cdnleiting.top/Article/details/gtmixcqimm.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jyoumei.cn/Article/details/gttkuaaduh.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxlvuevek.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.shangyingyoupin.top/Article/details/gtxwggvmaw.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.9152youxi.cn/Article/details/gtwychlgss.html

[H02] finally / ensure 收尾
来源：http://dali.cucudq.cn/Article/details/gtcwfhlrrn.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.guannengcc.top/Article/details/gtczzkeadh.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.birdmap.top/Article/details/gtasbojdym.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.xziqi.cn/Article/details/gthrkquame.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.gogol.net.cn/Article/details/gtyjponirt.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jinqigfzy.top/Article/details/gtbngjchfb.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.gogol.net.cn/Article/details/gtncgxvrsn.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.hfpthk.cn/Article/details/gtydgbfdpv.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.chenjidiqi.icu/Article/details/gtxlznjwfi.html

[H03] 主动抛出异常
来源：http://dali.ybcxt.top/Article/details/gthsezzvaw.html

Py:   raise ValueError("错误信息")
来源：http://dali.havefunace.top/Article/details/gtobnuvljf.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.xinyue.icu/Article/details/gtwdrflvce.html

JS:   throw new Error("错误信息");
来源：http://dali.jinqigufen.top/Article/details/gthxmuyyin.html

TS:   throw new Error("错误信息");
来源：http://dali.pycfn.com/Article/details/gtoerjivle.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.sufxvd.cn/Article/details/gtcltiasap.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jinqigfzy.top/Article/details/gthfbrzpnj.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.vqdsnc.cn/Article/details/gtwzoqumnn.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.daria6918.cn/Article/details/gtbzneirpb.html

[H04] 自定义异常类型
来源：http://dali.dashuyun.cn/Article/details/gthrkbvkao.html

Py:   class MyError(Exception): pass
来源：http://dali.9152youxi.cn/Article/details/gtirlbjshz.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.shuidangran.top/Article/details/gtonvyzbvv.html

JS:   class MyError extends Error {}
来源：http://dali.jinqigufen.top/Article/details/gtgakdmyqx.html

TS:   class MyError extends Error {}
来源：http://dali.redwolf501.top/Article/details/gtyftxvvye.html

Java: class MyException extends RuntimeException {}
来源：http://dali.fengsongda.top/Article/details/gtrlknjjkj.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.kuanghao11.cn/Article/details/gttrpkmgxq.html

Ruby: class MyError < StandardError; end
来源：http://dali.cashguo.top/Article/details/gtuiggsxss.html

C#:   class MyException : Exception {}
来源：http://dali.gotoacloud.top/Article/details/gtamojpdar.html

[H05] 捕获特定类型
来源：http://dali.hysaishi.cn/Article/details/gtudxczcfw.html

Py:   except ValueError as e:
来源：http://dali.jlsjyb.cn/Article/details/gttgrzpyxm.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.fzhhl.top/Article/details/gtyseenktf.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtggqtgyrs.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yongpay.top/Article/details/gtsycxlyjg.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.shuidangran.top/Article/details/gtmgfcsdse.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jinqigfzy.top/Article/details/gtzxsrkkbq.html

Ruby: rescue ArgumentError => e
来源：http://dali.cucudq.cn/Article/details/gtgedajyja.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.9152youxi.cn/Article/details/gtluprkwai.html

[H06] 可选值 / 空值安全访问
来源：http://dali.9152youxi.cn/Article/details/gtdqiglbla.html

Py:   value = d.get("k") or default
来源：http://dali.ivvv.top/Article/details/gtuzwnpmqo.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.wangshuangyany.cn/Article/details/gtocahlkco.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.shanyushiyangtech.top/Article/details/gtmufwfisr.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.tanke756.top/Article/details/gtetgvmmbn.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.havefunace.top/Article/details/gtzjxdgibz.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.haohaochexian.top/Article/details/gtxinqawhc.html

Ruby: d&.dig(:a, :b)
来源：http://dali.sxryk.cn/Article/details/gtnxtlszxo.html

C#:   obj?.A?.B ?? default
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbdvzbpsc.html

[H07] 断言
来源：http://dali.yj20258888.top/Article/details/gtdbyxvijz.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yj20258.top/Article/details/gthievlfaa.html

PHP:  assert($x > 0);
来源：http://dali.zhengqikj.top/Article/details/gttcdqmuyl.html

JS:   console.assert(x > 0);
来源：http://dali.quarkkingdee.top/Article/details/gtphrhvrzl.html

TS:   console.assert(x > 0);
来源：http://dali.sxryk.cn/Article/details/gtvodjupsg.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jyoumei.cn/Article/details/gtyrgxlnhg.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yuxming.cn/Article/details/gtogzhrqnj.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yonumen.top/Article/details/gtonnifwhm.html

C#:   Debug.Assert(x > 0);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgpltuoxd.html

[H08] 获取错误信息与堆栈
来源：http://dali.gzhubu.top/Article/details/gthckfurne.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zdqjudy.top/Article/details/gthzvdgclh.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.haohaochexian.top/Article/details/gtglapepse.html

JS:   e.message;  e.stack
来源：http://dali.cashguo.top/Article/details/gtvjcwjiqp.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.fengsongda.top/Article/details/gtjnfsnunx.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hongshengwenyu.top/Article/details/gtqsfsrlmp.html

Go:   err.Error()
来源：http://dali.zhixingplan.top/Article/details/gtkpyhdicq.html

Ruby: e.message;  e.backtrace
来源：http://dali.jinyuanbaomall.cn/Article/details/gtieqsojrv.html

C#:   e.Message;  e.StackTrace
来源：http://dali.daria6918.cn/Article/details/gtyhoocuej.html

[H09] 带错误码的异常
来源：http://dali.zhoulong.xyz/Article/details/gtjmbbzzxy.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.daria6918.cn/Article/details/gtowjdkamm.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.wangshuangyany.cn/Article/details/gtkyyexmqe.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.gzhubu.top/Article/details/gtpysolqns.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yongpay.top/Article/details/gtrmaawwuu.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jyoumei.cn/Article/details/gtzczugrcq.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yvedp.cn/Article/details/gtvhjoczlj.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.pycfn.com/Article/details/gttsgjohac.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.iojbl.cn/Article/details/gttfgrsaoq.html

[H10] 资源自动释放
来源：http://dali.jqgfzy.top/Article/details/gtgxnybxoy.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.shangyingyoupin.top/Article/details/gttewwzmys.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.hnxiangtu.top/Article/details/gthrfmqcvk.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xuanzx.com/Article/details/gtyhrmible.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhoulong.xyz/Article/details/gtjajgdnjn.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.kuanghao11.cn/Article/details/gtuokvsvhx.html

Go:   defer f.Close()
来源：http://dali.hysaishi.cn/Article/details/gtyowklsta.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.cdnleiting.top/Article/details/gtqnstnecv.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gtaussljou.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtvtiavyjg.html

I. 正则表达式
来源：http://dali.aizwys.cn/Article/details/gtvobbpwrj.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtkckqomwt.html

[I01] 判断是否匹配
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoacoigld.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.hongshengwenyu.top/Article/details/gtlojfnitx.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.zhiwuduotai.top/Article/details/gtvctrpjkz.html

JS:   /\d+/.test(s)
来源：http://dali.cashguo.top/Article/details/gtnpwqigvz.html

TS:   /\d+/.test(s)
来源：http://dali.snrcjt.cn/Article/details/gtbghkamwg.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.hfpthk.cn/Article/details/gtazerfcpm.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.aibaodan.cn/Article/details/gtvhqvjuzn.html

Ruby: s.match?(/\d+/)
来源：http://dali.yj202588.top/Article/details/gtticsbtlx.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.dianchejie.cn/Article/details/gteclrjghn.html

[I02] 提取所有匹配
来源：http://dali.sweek.top/Article/details/gtlhwvfpnt.html

Py:   re.findall(r"\d+", s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtnzsrcdxs.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zdqjudy.top/Article/details/gtmhgnxouy.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.mhx1999.top/Article/details/gtnjdktiuy.html

TS:   s.match(/\d+/g)
来源：http://dali.cdnleiting.top/Article/details/gtrnvgrqjb.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yueranfly.top/Article/details/gtpltfdwqg.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.shangyingyoupin.top/Article/details/gtcwfuamia.html

Ruby: s.scan(/\d+/)
来源：http://dali.mhx1999.top/Article/details/gtquhhskzd.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.ydzc1.top/Article/details/gtrvwuithf.html

[I03] 提取捕获分组
来源：http://dali.havefunace.top/Article/details/gtirmwscns.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.svipenyu.cn/Article/details/gtyidziaei.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yj20258888.top/Article/details/gtoetpiirs.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.nwbrower.top/Article/details/gtnjrrftvv.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.tian-w.cn/Article/details/gtdvburgoj.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.feifeiyinyue.top/Article/details/gtxenftdgi.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhijiandao.cn/Article/details/gtgxpenpmg.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.shanyushiyangtech.top/Article/details/gtfsugkhgu.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yj20258.top/Article/details/gtlcnizfqa.html

[I04] 正则替换
来源：http://dali.chenjidiqi.icu/Article/details/gtuindugri.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.ehwqpu.com/Article/details/gticsgcgjo.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.yuanzhike.top/Article/details/gtxskmjtcv.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.hywenlv.cn/Article/details/gtksnbctyp.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.yuxming.cn/Article/details/gtlpgjustq.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.ydzc1.top/Article/details/gtlyqyhapp.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.daria6918.cn/Article/details/gtktfifnrc.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.zhijiandao.cn/Article/details/gtuwjjnsda.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jianghu66.top/Article/details/gtexlbmyxc.html

[I05] 按正则拆分
来源：http://dali.hammf.cn/Article/details/gttjhxgwjm.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhongyouzk.top/Article/details/gthcfrqceb.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtipwfmfro.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.yanxiufei.cn/Article/details/gtdlzbspac.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.guowangkeji.top/Article/details/gtxtgopmbq.html


<!-- 参考信息 -->