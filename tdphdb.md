代发 wailian999

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.haohaochexian.top/Article/details/gt2wydfencm.html

TS:   path.extname("a.txt")
来源：http://dali.xylfe.cn/Article/details/gt2jecytxwq.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.wangdashe.top/Article/details/gt2mmxpzitz.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.cucudq.cn/Article/details/gt2yywkwbch.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2boquidtx.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.fengsongda.top/Article/details/gt2mblmvqtb.html

[F11] 复制与移动文件
来源：http://dali.fengsongda.top/Article/details/gt2geriqcce.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.bjfxy.top/Article/details/gt2xiooozfc.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.pycfn.com/Article/details/gt2vejttped.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gzhubu.top/Article/details/gt2eeijhizc.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2yjifukkq.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jianghu66.top/Article/details/gt2pucoryed.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.cashguo.top/Article/details/gt2axzvvvap.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yongpay.top/Article/details/gt2iesvnawh.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.hammf.cn/Article/details/gt2urhgrwyh.html

[F12] CSV 读写
来源：http://dali.zhoulong.xyz/Article/details/gt2asmwzjky.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nmyiwdhg.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yongpay.top/Article/details/gt2qvtrojdi.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.iojbl.cn/Article/details/gt2nemzejch.html

TS:   // 同上
来源：http://dali.andypj.xyz/Article/details/gt2ovyposzr.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhoulong.xyz/Article/details/gt2lqqrrjzn.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.aibaodan.cn/Article/details/gt2jesclnay.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.cqqwz.cn/Article/details/gt2dnapkgyh.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.kuanghao11.cn/Article/details/gt2xkjzgmxf.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2tmbrhiih.html

G. 面向对象
来源：http://dali.yj20258.top/Article/details/gt2vsvwbqiw.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hyvdbrex.html

[G01] 定义类
来源：http://dali.chenzaomai.com/Article/details/gt2ntqnpjce.html

Py:   class User: pass
来源：http://dali.zycfv.cn/Article/details/gt2rkebjlex.html

PHP:  class User {}
来源：http://dali.zhengqikj.top/Article/details/gt2zqvnrlzu.html

JS:   class User {}
来源：http://dali.dashuyun.cn/Article/details/gt2lmzbmkgo.html

TS:   class User { name: string = ""; }
来源：http://dali.yuanzhike.top/Article/details/gt2ueasnvfl.html

Java: class User {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2kjkttyrn.html

Go:   type User struct { Name string }
来源：http://dali.shangyingyoupin.top/Article/details/gt2omeulfca.html

Ruby: class User; end
来源：http://dali.zhengqikj.top/Article/details/gt2iawllaue.html

C#:   class User {}
来源：http://dali.redwolf501.top/Article/details/gt2xystmkmc.html

[G02] 构造函数
来源：http://dali.jlsjyb.cn/Article/details/gt2luaffwyr.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.meibo888.top/Article/details/gt2owkhktem.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.0kj1m.cn/Article/details/gt2gsycymwy.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.316326.xyz/Article/details/gt2iupocgqr.html

TS:   constructor(public name: string) {}
来源：http://dali.cheryme.top/Article/details/gt2fiykrrre.html

Java: User(String name) { this.name = name; }
来源：http://dali.yonumen.top/Article/details/gt2yaeyrngr.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.svipenyu.cn/Article/details/gt2pmdutgee.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hammf.cn/Article/details/gt2oggpupwi.html

C#:   public User(string name) { Name = name; }
来源：http://dali.cqqwz.cn/Article/details/gt2pgcankpk.html

[G03] 实例属性
来源：http://dali.xinyue.icu/Article/details/gt2eckhxowh.html

Py:   self.name = "x"
来源：http://dali.aibaodan.cn/Article/details/gt2zybmfyoq.html

PHP:  public string $name = "x";
来源：http://dali.aibaodan.cn/Article/details/gt2zhddqhvn.html

JS:   this.name = "x";
来源：http://dali.sysykeji.top/Article/details/gt2rjfqgcah.html

TS:   name: string = "x";
来源：http://dali.sufxvd.cn/Article/details/gt2ujvtnnkh.html

Java: private String name;
来源：http://dali.chenjidiqi.icu/Article/details/gt2xzoiukgx.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jianghu66.top/Article/details/gt2obszeogu.html

Ruby: @name = "x"
来源：http://dali.shangyingyoupin.top/Article/details/gt2qiniaiib.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jyoumei.cn/Article/details/gt2raqxzjgg.html

[G04] 定义方法
来源：http://dali.shzxlz.cn/Article/details/gt2pvgvwfcr.html

Py:   def greet(self): return self.name
来源：http://dali.gaohongyu789.top/Article/details/gt2xvxcqimy.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2isyisjys.html

JS:   greet() { return this.name; }
来源：http://dali.chenlongwang.top/Article/details/gt2becexreo.html

TS:   greet(): string { return this.name; }
来源：http://dali.vqdsnc.cn/Article/details/gt2epjuokys.html

Java: String greet() { return name; }
来源：http://dali.zycfv.cn/Article/details/gt2rzrabjst.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.ybcxt.top/Article/details/gt2mrbvavqs.html

Ruby: def greet; @name; end
来源：http://dali.yj20258888.top/Article/details/gt2gqyapdmx.html

C#:   public string Greet() => Name;
来源：http://dali.gzhubu.top/Article/details/gt2ldweuyhq.html

[G05] 继承
来源：http://dali.gaohongyu789.top/Article/details/gt2keqqpoky.html

Py:   class Admin(User): pass
来源：http://dali.yangfankeji.com/Article/details/gt2mghdrtoy.html

PHP:  class Admin extends User {}
来源：http://dali.ybcxt.top/Article/details/gt2ilccniaa.html

JS:   class Admin extends User {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2wspmwtpd.html

TS:   class Admin extends User {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2oktjjrzh.html

Java: class Admin extends User {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2zspukniw.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.wangshuangyany.cn/Article/details/gt2wutjabrg.html

Ruby: class Admin < User; end
来源：http://dali.c1oappe.top/Article/details/gt2tlidqpdj.html

C#:   class Admin : User {}
来源：http://dali.meibo888.top/Article/details/gt2xawmuilm.html

[G06] 重写方法
来源：http://dali.hongshengwenyu.top/Article/details/gt2qgjtrihd.html

Py:   def greet(self): return "admin"
来源：http://dali.jiagoushi.top/Article/details/gt2oictmyrj.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.shuidangran.top/Article/details/gt2hftnnltc.html

JS:   greet() { return "admin"; }
来源：http://dali.hywenlv.cn/Article/details/gt2glijhxwj.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hnqzz.top/Article/details/gt2irqqsavu.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yangfankeji.com/Article/details/gt2ijwmauxq.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.cheryme.top/Article/details/gt2iiprlhme.html

Ruby: def greet; "admin"; end
来源：http://dali.haohaochexian.top/Article/details/gt2vfueeefy.html

C#:   public override string Greet() => "admin";
来源：http://dali.yonumen.top/Article/details/gt2shgmkavg.html

[G07] 调用父类方法
来源：http://dali.fengsongda.top/Article/details/gt2koqvmoll.html

Py:   super().greet()
来源：http://dali.cqqwz.cn/Article/details/gt2znwzcgvn.html

PHP:  parent::greet();
来源：http://dali.feifeiyinyue.top/Article/details/gt2ajoxurqp.html

JS:   super.greet();
来源：http://dali.zhengqikj.top/Article/details/gt2gzvcykae.html

TS:   super.greet();
来源：http://dali.vqdsnc.cn/Article/details/gt2jenhwpna.html

Java: super.greet();
来源：http://dali.tianlin.xyz/Article/details/gt2uvjzxgge.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.birdmap.top/Article/details/gt2nswortjs.html

Ruby: super
来源：http://dali.xuetiantiany.cn/Article/details/gt2xwdufynt.html

C#:   base.Greet();
来源：http://dali.gogol.net.cn/Article/details/gt2othcskfh.html

[G08] 静态方法与属性
来源：http://dali.daria6918.cn/Article/details/gt2nubkgize.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.kuanghao11.cn/Article/details/gt2twykepjm.html

PHP:  public static function f() {}
来源：http://dali.yuxming.cn/Article/details/gt2vjtapvui.html

JS:   static f() {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2mhwmmdqv.html

TS:   static f(): void {}
来源：http://dali.vqdsnc.cn/Article/details/gt2xyhfnoer.html

Java: static void f() {}
来源：http://dali.aibaodan.cn/Article/details/gt2vvddkxws.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hvrecoda.html

Ruby: def self.f; end
来源：http://dali.feifeiyinyue.top/Article/details/gt2xwdwvbwp.html

C#:   public static void F() {}
来源：http://dali.jqgfzy.top/Article/details/gt2xqleisqg.html

[G09] 接口 / 抽象类
来源：http://dali.zhongyouzk.top/Article/details/gt2xmjvsdce.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.feifeiyinyue.top/Article/details/gt2baowukgo.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.0kj1m.cn/Article/details/gt2kzeiolot.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.gotoacloud.top/Article/details/gt2zgmentot.html

TS:   interface Shape { area(): number; }
来源：http://dali.ybcxt.top/Article/details/gt2mgaonhld.html

Java: interface Shape { double area(); }
来源：http://dali.hysaishi.cn/Article/details/gt2jboswrgc.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.chenjidiqi.icu/Article/details/gt2dyntefaq.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.chenlongwang.top/Article/details/gt2rqgdxrwt.html

C#:   interface IShape { double Area(); }
来源：http://dali.ivvv.top/Article/details/gt2bnkzqgcm.html

[G10] 访问控制
来源：http://dali.zdqjudy.top/Article/details/gt2awhrakql.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.pycfn.com/Article/details/gt2jciymhrh.html

PHP:  public / protected / private
来源：http://dali.fzhhl.top/Article/details/gt2gdpxceqz.html

JS:   #private 字段；其余公开
来源：http://dali.hnqzz.top/Article/details/gt2cgubldjz.html

TS:   public / protected / private
来源：http://dali.jqgfzy.top/Article/details/gt2wchggxsx.html

Java: public / protected / private / 默认包级
来源：http://dali.nanxuanxn.top/Article/details/gt2cvngqsls.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.guannengcc.top/Article/details/gt2gpjesgvn.html

Ruby: public / protected / private
来源：http://dali.birdmap.top/Article/details/gt2sakmndmq.html

C#:   public / protected / private / internal
来源：http://dali.quarkkingdee.top/Article/details/gt2kyqpgugv.html

[G11] getter / setter
来源：http://dali.zhengqikj.top/Article/details/gt2xayypekx.html

Py:   @property 与 @x.setter
来源：http://dali.yj20258.top/Article/details/gt2uewmjzlc.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yonumen.top/Article/details/gt2rpjrwigp.html

JS:   get name() { return this._name; }
来源：http://dali.zdqjudy.top/Article/details/gt2thcovbaj.html

TS:   get name(): string { return this._name; }
来源：http://dali.hfpthk.cn/Article/details/gt2gisfdcla.html

Java: public String getName() { return name; }
来源：http://dali.zhengqikj.top/Article/details/gt2cfdlfnms.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.smart0.xyz/Article/details/gt2akyifwkt.html

Ruby: attr_accessor :name
来源：http://dali.yvedp.cn/Article/details/gt2vpguerbm.html

C#:   public string Name { get; set; }
来源：http://dali.jqgfzy.top/Article/details/gt2hmdixhaw.html

[G12] 对象转字符串
来源：http://dali.tanke756.top/Article/details/gt2elmmpwwo.html

Py:   def __str__(self): return self.name
来源：http://dali.snrcjt.cn/Article/details/gt2swtlgtnc.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.guowangkeji.top/Article/details/gt2tmqblmsa.html

JS:   toString() { return this.name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kqzeflar.html

TS:   toString(): string { return this.name; }
来源：http://dali.tianlin.xyz/Article/details/gt2mxfuffxo.html

Java: @Override public String toString() { return name; }
来源：http://dali.0kj1m.cn/Article/details/gt2eiuwyymp.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.nwbrower.top/Article/details/gt2kvofaapn.html

Ruby: def to_s; @name; end
来源：http://dali.iojbl.cn/Article/details/gt2zwonidkc.html

C#:   public override string ToString() => Name;
来源：http://dali.hywenlv.cn/Article/details/gt2cgbrzwlu.html

[G13] 判断对象类型
来源：http://dali.xziqi.cn/Article/details/gt2qjrtcbrr.html

Py:   isinstance(u, User)
来源：http://dali.yonumen.top/Article/details/gt2cimimvjb.html

PHP:  $u instanceof User
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dcdlhrbb.html

JS:   u instanceof User
来源：http://dali.zdqjudy.top/Article/details/gt2naruxmbw.html

TS:   u instanceof User
来源：http://dali.xinyue.icu/Article/details/gt2zkugsrye.html

Java: u instanceof User
来源：http://dali.cucudq.cn/Article/details/gt2lsyjgstf.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yj20258888.top/Article/details/gt2mqjhdmro.html

Ruby: u.is_a?(User)
来源：http://dali.jinqigufen.top/Article/details/gt2ubntmzxj.html

C#:   u is User
来源：http://dali.pycfn.com/Article/details/gt2cvbkyuit.html

[G14] 数据类 / record
来源：http://dali.ehwqpu.com/Article/details/gt2dlamuwsh.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.chenjidiqi.icu/Article/details/gt2syqbzncc.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.nwbrower.top/Article/details/gt2nwnrlgyu.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.fzhhl.top/Article/details/gt2fifeqqwn.html

TS:   type User = { name: string; age: number };
来源：http://dali.ydzc1.top/Article/details/gt2vuqterzi.html

Java: record User(String name, int age) {}
来源：http://dali.mhx1999.top/Article/details/gt2qdjsillx.html

Go:   type User struct { Name string; Age int }
来源：http://dali.vqdsnc.cn/Article/details/gt2hisqvjbn.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.andypj.xyz/Article/details/gt2nzoynbcc.html

C#:   record User(string Name, int Age);
来源：http://dali.iojbl.cn/Article/details/gt2gmbbwftj.html

[G15] 枚举
来源：http://dali.snrcjt.cn/Article/details/gt2udhsodea.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.xylfe.cn/Article/details/gt2atzymzgt.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.hammf.cn/Article/details/gt2qatgnliy.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jqgfzy.top/Article/details/gt2uegjjwrx.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ydzc1.top/Article/details/gt2sgpfcdux.html

Java: enum Color { RED, GREEN }
来源：http://dali.snrcjt.cn/Article/details/gt2cbmlbjiu.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2isdtgmdw.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhixingplan.top/Article/details/gt2tieyzofc.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.aizwys.cn/Article/details/gt2nptbhkbh.html

[G16] 对象转数组 / 字典
来源：http://dali.xuetiantiany.cn/Article/details/gt2irpfqgyb.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.daxiang520.top/Article/details/gt2jdjhpoai.html

PHP:  get_object_vars($obj);
来源：http://dali.fzhhl.top/Article/details/gt2omncivxv.html

JS:   Object.entries(obj)
来源：http://dali.haohaochexian.top/Article/details/gt2jujoktmm.html

TS:   Object.entries(obj)
来源：http://dali.daxiang520.top/Article/details/gt2goabrivz.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2maznyifo.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.ppjwa.cn/Article/details/gt2chigqorl.html

Ruby: obj.instance_variables
来源：http://dali.tianlin.xyz/Article/details/gt2aqrrsruo.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.sysykeji.top/Article/details/gt2nziichsm.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2yhkrkcim.html

H. 异常与错误处理
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ncoablec.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2sggaedon.html

[H01] try / catch 基础
来源：http://dali.jiagoushi.top/Article/details/gt2bbvygejw.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.hammf.cn/Article/details/gt2obdsdofs.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.smart0.xyz/Article/details/gt2kjctoezh.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.chenlongwang.top/Article/details/gt2fxjqglem.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.guowangkeji.top/Article/details/gt2oiufweuj.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.iojbl.cn/Article/details/gt2iegyzesx.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.shzxlz.cn/Article/details/gt2wtkohyuc.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fobosafm.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ftdecfxa.html

[H02] finally / ensure 收尾
来源：http://dali.zhengqikj.top/Article/details/gt2kuhhczdi.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.xinyue.icu/Article/details/gt2fnyybehi.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.cheryme.top/Article/details/gt2jvigdkax.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ivvv.top/Article/details/gt2rivfajmw.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.c1oappe.top/Article/details/gt2vkacagbn.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.cashguo.top/Article/details/gt2zfrazals.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yangfankeji.com/Article/details/gt2ivlatyfm.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.cashguo.top/Article/details/gt2fdnkdmnp.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kgbbovtr.html

[H03] 主动抛出异常
来源：http://dali.yuxming.cn/Article/details/gt2wurzpyai.html

Py:   raise ValueError("错误信息")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vywsjjkj.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.cucudq.cn/Article/details/gt2vjeztsyc.html

JS:   throw new Error("错误信息");
来源：http://dali.jyoumei.cn/Article/details/gt2dxtbchqg.html

TS:   throw new Error("错误信息");
来源：http://dali.yj20258.top/Article/details/gt2jibzchjl.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhiwuduotai.top/Article/details/gt2dhhpfzkj.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yongpay.top/Article/details/gt2jpjdvowa.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.mhx1999.top/Article/details/gt2chcnemle.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.quarkkingdee.top/Article/details/gt2gbkvgwju.html

[H04] 自定义异常类型
来源：http://dali.ivvv.top/Article/details/gt2ovwcpcet.html

Py:   class MyError(Exception): pass
来源：http://dali.yangfankeji.com/Article/details/gt2hhfzxgpp.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.iojbl.cn/Article/details/gt2yvlmkhbp.html

JS:   class MyError extends Error {}
来源：http://dali.gaohongyu789.top/Article/details/gt2anhdkfgq.html

TS:   class MyError extends Error {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2yolnvxxw.html

Java: class MyException extends RuntimeException {}
来源：http://dali.daxiang520.top/Article/details/gt2ujsnfvcu.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhongyouzk.top/Article/details/gt2fzssmczg.html

Ruby: class MyError < StandardError; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2osguxqcr.html

C#:   class MyException : Exception {}
来源：http://dali.cashguo.top/Article/details/gt2rceedqvp.html

[H05] 捕获特定类型
来源：http://dali.hammf.cn/Article/details/gt2hbmpjriy.html

Py:   except ValueError as e:
来源：http://dali.mhx1999.top/Article/details/gt2fykebzrj.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.hysaishi.cn/Article/details/gt2umjuvmou.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yj20258888.top/Article/details/gt2zidyahuz.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jlsjyb.cn/Article/details/gt2vtacjyqw.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2ofowxcqj.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.dashuyun.cn/Article/details/gt2ichlxddh.html

Ruby: rescue ArgumentError => e
来源：http://dali.cashguo.top/Article/details/gt2xgjfjtru.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yonumen.top/Article/details/gt2bmwfbeth.html

[H06] 可选值 / 空值安全访问
来源：http://dali.hammf.cn/Article/details/gt2msghuoge.html

Py:   value = d.get("k") or default
来源：http://dali.sxryk.cn/Article/details/gt2povlwhbt.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.316326.xyz/Article/details/gt2dgeayyro.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.ehwqpu.com/Article/details/gt2uzritvhm.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yj20258888.top/Article/details/gt2crwcjhia.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhengqikj.top/Article/details/gt2mvkgxxtn.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.sxryk.cn/Article/details/gt2lqlefxwc.html

Ruby: d&.dig(:a, :b)
来源：http://dali.svipenyu.cn/Article/details/gt2tjunjrau.html

C#:   obj?.A?.B ?? default
来源：http://dali.svipenyu.cn/Article/details/gt2axwuhmoq.html

[H07] 断言
来源：http://dali.yueranfly.top/Article/details/gt2twxsbfzy.html

Py:   assert x > 0, "必须为正"
来源：http://dali.xziqi.cn/Article/details/gt2zfcoqcex.html

PHP:  assert($x > 0);
来源：http://dali.yuxming.cn/Article/details/gt2mndydyxq.html

JS:   console.assert(x > 0);
来源：http://dali.bjfxy.top/Article/details/gt2fhlhtyef.html

TS:   console.assert(x > 0);
来源：http://dali.daria6918.cn/Article/details/gt2nbenopiv.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yanxiufei.cn/Article/details/gt2elfhyisc.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.mhx1999.top/Article/details/gt2ulppisds.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.0kj1m.cn/Article/details/gt2igiddxhv.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yvedp.cn/Article/details/gt2gfdjufmc.html

[H08] 获取错误信息与堆栈
来源：http://dali.feifeiyinyue.top/Article/details/gt2nrtmdtty.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yvedp.cn/Article/details/gt2duyiuhwl.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jinqigfzy.top/Article/details/gt2yhrmizvr.html

JS:   e.message;  e.stack
来源：http://dali.quarkkingdee.top/Article/details/gt2arfdefnd.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.dianchejie.cn/Article/details/gt2qdqonuxe.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zycfv.cn/Article/details/gt2inhabqap.html

Go:   err.Error()
来源：http://dali.sxryk.cn/Article/details/gt2mdsjpend.html

Ruby: e.message;  e.backtrace
来源：http://dali.shangyingyoupin.top/Article/details/gt2txwoplfx.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zycfv.cn/Article/details/gt2bktmzlhx.html

[H09] 带错误码的异常
来源：http://dali.aibaodan.cn/Article/details/gt2idzqirxg.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.xinyue.icu/Article/details/gt2bqangzou.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vyabvthm.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.fengsongda.top/Article/details/gt2eqbzzbys.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.hnqzz.top/Article/details/gt2vulwjlae.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.xylfe.cn/Article/details/gt2vlkdyrev.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yueranfly.top/Article/details/gt2oxnsovke.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.quarkkingdee.top/Article/details/gt2sbhmpfle.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jqgfzy.top/Article/details/gt2ogkanipr.html

[H10] 资源自动释放
来源：http://dali.mhx1999.top/Article/details/gt2hjigskdq.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhongyouzk.top/Article/details/gt2plxwyeem.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.gotoacloud.top/Article/details/gt2njxxkuoq.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ybcxt.top/Article/details/gt2pafpruhv.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cheryme.top/Article/details/gt2xpxpfqiz.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.xuetiantiany.cn/Article/details/gt2xprexhwk.html

Go:   defer f.Close()
来源：http://dali.tianlin.xyz/Article/details/gt2alnwhopl.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.zdqjudy.top/Article/details/gt2xvepvcht.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.9152youxi.cn/Article/details/gt2ligjgkzp.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2yllrxojo.html

I. 正则表达式
来源：http://dali.cucudq.cn/Article/details/gt2ugkkqgfj.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2kgadmnob.html

[I01] 判断是否匹配
来源：http://dali.iojbl.cn/Article/details/gt2teriweue.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.smart0.xyz/Article/details/gt2rdeftbei.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2upfngywl.html

JS:   /\d+/.test(s)
来源：http://dali.dianchejie.cn/Article/details/gt2qpduohuc.html

TS:   /\d+/.test(s)
来源：http://dali.cheryme.top/Article/details/gt2raqhraas.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.hywenlv.cn/Article/details/gt2pwzsjxta.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.smart0.xyz/Article/details/gt2ktivcdwp.html

Ruby: s.match?(/\d+/)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rkijlbjm.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.jianghu66.top/Article/details/gt2slfnyvcl.html

[I02] 提取所有匹配
来源：http://dali.cashguo.top/Article/details/gt2rbahlfsv.html

Py:   re.findall(r"\d+", s)
来源：http://dali.guannengcc.top/Article/details/gt2ueyxgbgz.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.yvedp.cn/Article/details/gt2sxkouhit.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhixingplan.top/Article/details/gt2jguqppjp.html

TS:   s.match(/\d+/g)
来源：http://dali.xziqi.cn/Article/details/gt2wetwwnpq.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.sysykeji.top/Article/details/gt2xxyrdjsy.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.redwolf501.top/Article/details/gt2lmhvnldf.html

Ruby: s.scan(/\d+/)
来源：http://dali.jlsjyb.cn/Article/details/gt2mbarkiqw.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.nanxinkj.top/Article/details/gt2zckwkqvx.html

[I03] 提取捕获分组
来源：http://dali.ydzc1.top/Article/details/gt2sgbxwwvb.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.pycfn.com/Article/details/gt2ntqnbwhr.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fplmvbmj.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.nwbrower.top/Article/details/gt2eguvjixh.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.wangshuangyany.cn/Article/details/gt2vdfhzapa.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.gotoacloud.top/Article/details/gt2cnewqhxa.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.bjfxy.top/Article/details/gt2tsyqnfxa.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.gotoacloud.top/Article/details/gt2xqfrgozg.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.quarkkingdee.top/Article/details/gt2wpdmavze.html

[I04] 正则替换
来源：http://dali.xinyue.icu/Article/details/gt2spelnwpv.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hysaishi.cn/Article/details/gt2eneeoqxm.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.haohaochexian.top/Article/details/gt2tmpqplti.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.dashuyun.cn/Article/details/gt2hyhbptlu.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.daxiang520.top/Article/details/gt2veuibnna.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.hfpthk.cn/Article/details/gt2odhkifzf.html


<!-- 参考信息 -->