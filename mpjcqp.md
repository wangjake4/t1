代发 wailian999

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtegfsyejv.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhoulong.xyz/Article/details/gtrdfegyzb.html

Ruby: Dir.children("dir")
来源：http://dali.hfpthk.cn/Article/details/gtpnaietob.html

C#:   Directory.GetFiles("dir")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxoenmwmv.html

[F09] 获取文件大小
来源：http://dali.ybcxt.top/Article/details/gthqzuazhi.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtzwriqxke.html

PHP:  filesize("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gtqlzgixpp.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jyoumei.cn/Article/details/gtrwdiucdr.html

TS:   fs.statSync("a.txt").size
来源：http://dali.birdmap.top/Article/details/gtfktableu.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfgtahfka.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.fengsongda.top/Article/details/gtybwfwibw.html

Ruby: File.size("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtjwnlxcgl.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.svipenyu.cn/Article/details/gtpdinigss.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jinghuilouyu.cn/Article/details/gtacdjvncy.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.tian-w.cn/Article/details/gttmkmwske.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yj202588.top/Article/details/gtuosvfdva.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.gzhubu.top/Article/details/gtsnijenxo.html

TS:   path.extname("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtaffusehk.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.snrcjt.cn/Article/details/gtffgonkpi.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.fzhhl.top/Article/details/gtsbmlorbw.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtvujnnpgw.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.cashguo.top/Article/details/gtndljazxi.html

[F11] 复制与移动文件
来源：http://dali.yvedp.cn/Article/details/gtxkkuthwi.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.gogol.net.cn/Article/details/gtxhwoapnu.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gteqlmveqn.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.mhx1999.top/Article/details/gtsmvdqrjw.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtlsdoipoe.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.dashuyun.cn/Article/details/gtspwqfjzp.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.dashuyun.cn/Article/details/gtqtmrxyty.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jinqigufen.top/Article/details/gtktulsfgn.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.guowangkeji.top/Article/details/gtsjulpfin.html

[F12] CSV 读写
来源：http://dali.jinqigfzy.top/Article/details/gtdmvguvvj.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yonumen.top/Article/details/gtdayobyzu.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.meibo888.top/Article/details/gtawhsgsqd.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.wangdashe.top/Article/details/gtllvbgwrj.html

TS:   // 同上
来源：http://dali.zhijiandao.cn/Article/details/gtexptttrp.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.c1oappe.top/Article/details/gtlotlghpr.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.pycfn.com/Article/details/gtuyuciycr.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqzpgvntd.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yj20258.top/Article/details/gtdhpijsaw.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtuxihojnb.html

G. 面向对象
来源：http://dali.jinghuilouyu.cn/Article/details/gtmciqsewl.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtdhpxbmcy.html

[G01] 定义类
来源：http://dali.quarkkingdee.top/Article/details/gtlmrzhwqv.html

Py:   class User: pass
来源：http://dali.fengsongda.top/Article/details/gtwhkbrtkg.html

PHP:  class User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkgxghpee.html

JS:   class User {}
来源：http://dali.andypj.xyz/Article/details/gtlxpcypxk.html

TS:   class User { name: string = ""; }
来源：http://dali.ehwqpu.com/Article/details/gtwaumtxgm.html

Java: class User {}
来源：http://dali.ybcxt.top/Article/details/gttqqzvbff.html

Go:   type User struct { Name string }
来源：http://dali.nanxinkj.top/Article/details/gtylsemncz.html

Ruby: class User; end
来源：http://dali.yangfankeji.com/Article/details/gticsueywd.html

C#:   class User {}
来源：http://dali.cdnleiting.top/Article/details/gtzhrzzmrr.html

[G02] 构造函数
来源：http://dali.ppjwa.cn/Article/details/gtxetcnhli.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.shangyingyoupin.top/Article/details/gtrxadbbds.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.mhx1999.top/Article/details/gtzjcdadaf.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.xinyue.icu/Article/details/gtkplgpikf.html

TS:   constructor(public name: string) {}
来源：http://dali.9152youxi.cn/Article/details/gtxyiqagjw.html

Java: User(String name) { this.name = name; }
来源：http://dali.ydzc1.top/Article/details/gtsulpqxtl.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zycfv.cn/Article/details/gtypsqtjhv.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.quarkkingdee.top/Article/details/gtkwltdfgf.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yongpay.top/Article/details/gtvrxcuwqj.html

[G03] 实例属性
来源：http://dali.svipenyu.cn/Article/details/gtfzshrqui.html

Py:   self.name = "x"
来源：http://dali.nwbrower.top/Article/details/gtntlhtdps.html

PHP:  public string $name = "x";
来源：http://dali.wangshuangyany.cn/Article/details/gtufsypfvj.html

JS:   this.name = "x";
来源：http://dali.pengpengdd.cyou/Article/details/gtfsxvhrhm.html

TS:   name: string = "x";
来源：http://dali.yvedp.cn/Article/details/gtdetoboyp.html

Java: private String name;
来源：http://dali.pengpengdd.cyou/Article/details/gtnmhiiipf.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.aibaodan.cn/Article/details/gtbxiwsopf.html

Ruby: @name = "x"
来源：http://dali.cucudq.cn/Article/details/gthzcsfqis.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.bjfxy.top/Article/details/gtvuzzqjnv.html

[G04] 定义方法
来源：http://dali.kuanghao11.cn/Article/details/gtdqypnivg.html

Py:   def greet(self): return self.name
来源：http://dali.yonumen.top/Article/details/gtrjvnpqyu.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.gogol.net.cn/Article/details/gtirgyyqpw.html

JS:   greet() { return this.name; }
来源：http://dali.hfpthk.cn/Article/details/gtqcpkuslm.html

TS:   greet(): string { return this.name; }
来源：http://dali.zycfv.cn/Article/details/gtogewimln.html

Java: String greet() { return name; }
来源：http://dali.yuxming.cn/Article/details/gtioivjpva.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.birdmap.top/Article/details/gtazwusatd.html

Ruby: def greet; @name; end
来源：http://dali.guannengcc.top/Article/details/gtfjfthrld.html

C#:   public string Greet() => Name;
来源：http://dali.tian-w.cn/Article/details/gtkpkivyjr.html

[G05] 继承
来源：http://dali.shuidangran.top/Article/details/gtasfzmccx.html

Py:   class Admin(User): pass
来源：http://dali.wangshuangyany.cn/Article/details/gtpuwsittm.html

PHP:  class Admin extends User {}
来源：http://dali.hnqzz.top/Article/details/gtcwmvffec.html

JS:   class Admin extends User {}
来源：http://dali.yvedp.cn/Article/details/gtrkuxmiwj.html

TS:   class Admin extends User {}
来源：http://dali.daxiang520.top/Article/details/gtdoteyyux.html

Java: class Admin extends User {}
来源：http://dali.gotoacloud.top/Article/details/gthgjohqdy.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yuxming.cn/Article/details/gtxssmldzu.html

Ruby: class Admin < User; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfijvuben.html

C#:   class Admin : User {}
来源：http://dali.svipenyu.cn/Article/details/gtwpyhrrxz.html

[G06] 重写方法
来源：http://dali.sxryk.cn/Article/details/gtllzknovg.html

Py:   def greet(self): return "admin"
来源：http://dali.jqgfzy.top/Article/details/gtexkyvpae.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.feifeiyinyue.top/Article/details/gtwtiymjeh.html

JS:   greet() { return "admin"; }
来源：http://dali.c1oappe.top/Article/details/gtcqxapvkq.html

TS:   greet(): string { return "admin"; }
来源：http://dali.shzxlz.cn/Article/details/gthsyizxtd.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.wangshuangyany.cn/Article/details/gtzkcmqyiq.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.tanke756.top/Article/details/gtjfqejksr.html

Ruby: def greet; "admin"; end
来源：http://dali.nwbrower.top/Article/details/gttdpzkbjv.html

C#:   public override string Greet() => "admin";
来源：http://dali.xuetiantiany.cn/Article/details/gtukhaceck.html

[G07] 调用父类方法
来源：http://dali.ivvv.top/Article/details/gtiswkxewv.html

Py:   super().greet()
来源：http://dali.chenzaomai.com/Article/details/gtqsyqrxag.html

PHP:  parent::greet();
来源：http://dali.yueranfly.top/Article/details/gtakqnugip.html

JS:   super.greet();
来源：http://dali.tianlin.xyz/Article/details/gtajclruug.html

TS:   super.greet();
来源：http://dali.aizwys.cn/Article/details/gtbcyrmdnk.html

Java: super.greet();
来源：http://dali.haohaochexian.top/Article/details/gtlrwytbvm.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jianghu66.top/Article/details/gtamjnzcxn.html

Ruby: super
来源：http://dali.hnqzz.top/Article/details/gtvasvkdzf.html

C#:   base.Greet();
来源：http://dali.zhiwuduotai.top/Article/details/gttpzwgthg.html

[G08] 静态方法与属性
来源：http://dali.xylfe.cn/Article/details/gtidajtskw.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.fengsongda.top/Article/details/gtxegowilo.html

PHP:  public static function f() {}
来源：http://dali.andypj.xyz/Article/details/gtfaevbfgp.html

JS:   static f() {}
来源：http://dali.shuidangran.top/Article/details/gtdlrhdjtz.html

TS:   static f(): void {}
来源：http://dali.sysykeji.top/Article/details/gthnxketko.html

Java: static void f() {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtpmknomyo.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.aizwys.cn/Article/details/gtxckhyryb.html

Ruby: def self.f; end
来源：http://dali.xuetiantiany.cn/Article/details/gtzcwbdazl.html

C#:   public static void F() {}
来源：http://dali.zycfv.cn/Article/details/gtousrcfuy.html

[G09] 接口 / 抽象类
来源：http://dali.fengsongda.top/Article/details/gttznxojpg.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jqgfzy.top/Article/details/gtkrumsmdr.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.wangshuangyany.cn/Article/details/gtfcjyzqvl.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.sysykeji.top/Article/details/gtckjynmrw.html

TS:   interface Shape { area(): number; }
来源：http://dali.tian-w.cn/Article/details/gtzgtuggbm.html

Java: interface Shape { double area(); }
来源：http://dali.zdqjudy.top/Article/details/gtkqkvmhjp.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhiwuduotai.top/Article/details/gtnhhsneab.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.cheryme.top/Article/details/gtqlgfwyql.html

C#:   interface IShape { double Area(); }
来源：http://dali.jiagoushi.top/Article/details/gtqcmzbaqg.html

[G10] 访问控制
来源：http://dali.daria6918.cn/Article/details/gtbutpghwg.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.pycfn.com/Article/details/gtzodyaxbc.html

PHP:  public / protected / private
来源：http://dali.snrcjt.cn/Article/details/gtczadizzv.html

JS:   #private 字段；其余公开
来源：http://dali.nanxinkj.top/Article/details/gtfgppdquo.html

TS:   public / protected / private
来源：http://dali.jinqigufen.top/Article/details/gtknovpquy.html

Java: public / protected / private / 默认包级
来源：http://dali.chenjidiqi.icu/Article/details/gtkdadxzfa.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.chenjidiqi.icu/Article/details/gtwyhhwkzw.html

Ruby: public / protected / private
来源：http://dali.chenzaomai.com/Article/details/gtplklcqak.html

C#:   public / protected / private / internal
来源：http://dali.kuanghao11.cn/Article/details/gtcevkdmvj.html

[G11] getter / setter
来源：http://dali.svipenyu.cn/Article/details/gtefjozerw.html

Py:   @property 与 @x.setter
来源：http://dali.yuanzhike.top/Article/details/gtykmtviec.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.guowangkeji.top/Article/details/gtokmpplsj.html

JS:   get name() { return this._name; }
来源：http://dali.xinyue.icu/Article/details/gtajjrpmge.html

TS:   get name(): string { return this._name; }
来源：http://dali.yj202588.top/Article/details/gtubflxtsk.html

Java: public String getName() { return name; }
来源：http://dali.gotoacloud.top/Article/details/gtfccwmrdb.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jinghuilouyu.cn/Article/details/gtrwttdlry.html

Ruby: attr_accessor :name
来源：http://dali.kuanghao11.cn/Article/details/gtfurpsmrr.html

C#:   public string Name { get; set; }
来源：http://dali.yj20258.top/Article/details/gtdpdxqujf.html

[G12] 对象转字符串
来源：http://dali.dashuyun.cn/Article/details/gttoxjgfzm.html

Py:   def __str__(self): return self.name
来源：http://dali.316326.xyz/Article/details/gtyejgsfuw.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.wangdashe.top/Article/details/gtuolhlaok.html

JS:   toString() { return this.name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtskcgcfmf.html

TS:   toString(): string { return this.name; }
来源：http://dali.feifeiyinyue.top/Article/details/gttyxxlyum.html

Java: @Override public String toString() { return name; }
来源：http://dali.xuanzx.com/Article/details/gtqnmkoaxy.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.daxiang520.top/Article/details/gtdhrrawsq.html

Ruby: def to_s; @name; end
来源：http://dali.yj20258.top/Article/details/gtpjzjuxli.html

C#:   public override string ToString() => Name;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtudshgfep.html

[G13] 判断对象类型
来源：http://dali.shangyingyoupin.top/Article/details/gtmmibvbye.html

Py:   isinstance(u, User)
来源：http://dali.jqgufenzy.top/Article/details/gtfgqmmfbi.html

PHP:  $u instanceof User
来源：http://dali.smart0.xyz/Article/details/gtjwmzqxeu.html

JS:   u instanceof User
来源：http://dali.zhiwuduotai.top/Article/details/gtvyqukaai.html

TS:   u instanceof User
来源：http://dali.yuxming.cn/Article/details/gtytbxkgxd.html

Java: u instanceof User
来源：http://dali.xuanzx.com/Article/details/gtfqnifohv.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.ppjwa.cn/Article/details/gtuitiavxy.html

Ruby: u.is_a?(User)
来源：http://dali.wangdashe.top/Article/details/gthsuhzhvh.html

C#:   u is User
来源：http://dali.svipenyu.cn/Article/details/gtpovamsxq.html

[G14] 数据类 / record
来源：http://dali.shuidangran.top/Article/details/gtgwewzfuj.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.guannengcc.top/Article/details/gtbkspgmyy.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.tian-w.cn/Article/details/gtgucjhfkb.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yj20258888.top/Article/details/gtdaqvqicn.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhengqikj.top/Article/details/gtxozdxbpz.html

Java: record User(String name, int age) {}
来源：http://dali.hnqzz.top/Article/details/gtebyeqlhq.html

Go:   type User struct { Name string; Age int }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtykgscsjq.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.guowangkeji.top/Article/details/gtlnugjcez.html

C#:   record User(string Name, int Age);
来源：http://dali.nwbrower.top/Article/details/gtgtwmbrln.html

[G15] 枚举
来源：http://dali.cdnleiting.top/Article/details/gtzqrjhngi.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.9152youxi.cn/Article/details/gtmgbunfyq.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlekdwxzu.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.c1oappe.top/Article/details/gtuglgprow.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cqqwz.cn/Article/details/gtshpmubtc.html

Java: enum Color { RED, GREEN }
来源：http://dali.tian-w.cn/Article/details/gttggfrhom.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zdqjudy.top/Article/details/gttxawiyej.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jinghuilouyu.cn/Article/details/gtybehpvfw.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xuetiantiany.cn/Article/details/gtoqlsievs.html

[G16] 对象转数组 / 字典
来源：http://dali.yvedp.cn/Article/details/gtfjdiszjy.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.xuanzx.com/Article/details/gtqkrhjtjp.html

PHP:  get_object_vars($obj);
来源：http://dali.guannengcc.top/Article/details/gtrkjfrajn.html

JS:   Object.entries(obj)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxmhwvgfi.html

TS:   Object.entries(obj)
来源：http://dali.guowangkeji.top/Article/details/gtcxxrylqa.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jqgfzy.top/Article/details/gtmfvmgcup.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.gogol.net.cn/Article/details/gtefsaqowx.html

Ruby: obj.instance_variables
来源：http://dali.zhiwuduotai.top/Article/details/gtrryxnnem.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhengqikj.top/Article/details/gtushbujbh.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtqvcphisu.html

H. 异常与错误处理
来源：http://dali.dashuyun.cn/Article/details/gtkxzelitv.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtvaabimoa.html

[H01] try / catch 基础
来源：http://dali.jqgufenzy.top/Article/details/gtmemcithp.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.ehwqpu.com/Article/details/gtfkrhkpqz.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.mhx1999.top/Article/details/gttjrhlzxn.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.ydzc1.top/Article/details/gtjebnomfc.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.c1oappe.top/Article/details/gtxrgkxdzd.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.andypj.xyz/Article/details/gtwkyiljmy.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.gaohongyu789.top/Article/details/gtdeniithl.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yj20258.top/Article/details/gtaxazgbta.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.cqqwz.cn/Article/details/gtxaueqpui.html

[H02] finally / ensure 收尾
来源：http://dali.smart0.xyz/Article/details/gtaoftwfmn.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jqgfzy.top/Article/details/gtogghfkow.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yueranfly.top/Article/details/gtpsootpkq.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.chenlongwang.top/Article/details/gttryalxdt.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.shuidangran.top/Article/details/gtymwyahzu.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpaunvocc.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.fengsongda.top/Article/details/gtzgbgddbw.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jinqigfzy.top/Article/details/gtxdaqnkgi.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yangfankeji.com/Article/details/gtawgqbysl.html

[H03] 主动抛出异常
来源：http://dali.meibo888.top/Article/details/gtforvccsi.html

Py:   raise ValueError("错误信息")
来源：http://dali.yj202588.top/Article/details/gtpxoveajo.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yj202588.top/Article/details/gtdmsfkmib.html

JS:   throw new Error("错误信息");
来源：http://dali.hysaishi.cn/Article/details/gtxxupnrkh.html

TS:   throw new Error("错误信息");
来源：http://dali.wangdashe.top/Article/details/gtmjstlhio.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.316326.xyz/Article/details/gtrpevjhpm.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.sufxvd.cn/Article/details/gtjgnutipq.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.316326.xyz/Article/details/gtdcodpztx.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.andypj.xyz/Article/details/gtelndzmjf.html

[H04] 自定义异常类型
来源：http://dali.zhoulong.xyz/Article/details/gtdhvawtyv.html

Py:   class MyError(Exception): pass
来源：http://dali.yj20258.top/Article/details/gtgsowphbx.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.316326.xyz/Article/details/gtbwicwpsy.html

JS:   class MyError extends Error {}
来源：http://dali.hysaishi.cn/Article/details/gtmdbpaktt.html

TS:   class MyError extends Error {}
来源：http://dali.hnqzz.top/Article/details/gtjhyehubc.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jlsjyb.cn/Article/details/gtnhgtjwqv.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jqgfzy.top/Article/details/gtdlppiqmb.html

Ruby: class MyError < StandardError; end
来源：http://dali.sweek.top/Article/details/gtddfhwigs.html

C#:   class MyException : Exception {}
来源：http://dali.jyoumei.cn/Article/details/gtvgqlbbyy.html

[H05] 捕获特定类型
来源：http://dali.yj20258.top/Article/details/gtkmcacfan.html

Py:   except ValueError as e:
来源：http://dali.zhoulong.xyz/Article/details/gtbchntpiq.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.shanyushiyangtech.top/Article/details/gtrxcwlnwu.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yueranfly.top/Article/details/gtbbwtgujn.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.nwbrower.top/Article/details/gthahoodac.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.kuanghao11.cn/Article/details/gtbizexxri.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpxplhgyc.html

Ruby: rescue ArgumentError => e
来源：http://dali.chenlongwang.top/Article/details/gtiimlbybr.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.dianchejie.cn/Article/details/gtzeggkjgb.html

[H06] 可选值 / 空值安全访问
来源：http://dali.cheryme.top/Article/details/gtujeplqrv.html

Py:   value = d.get("k") or default
来源：http://dali.jqgfzy.top/Article/details/gtbrbhtfne.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.daxiang520.top/Article/details/gtjucsljur.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.hammf.cn/Article/details/gtkxfcbcwn.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.snrcjt.cn/Article/details/gtryiefhvb.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yonumen.top/Article/details/gtngolnash.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.sysykeji.top/Article/details/gttdfjjdfp.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhixingplan.top/Article/details/gtbrwjgbqi.html

C#:   obj?.A?.B ?? default
来源：http://dali.xuanzx.com/Article/details/gtkokqfqoz.html

[H07] 断言
来源：http://dali.shanyushiyangtech.top/Article/details/gtpgwklryg.html

Py:   assert x > 0, "必须为正"
来源：http://dali.shangyingyoupin.top/Article/details/gtmdcepnpq.html

PHP:  assert($x > 0);
来源：http://dali.hywenlv.cn/Article/details/gtlqjzqull.html

JS:   console.assert(x > 0);
来源：http://dali.jiagoushi.top/Article/details/gttuwchkgz.html

TS:   console.assert(x > 0);
来源：http://dali.cdnleiting.top/Article/details/gtporbkgea.html

Java: assert x > 0 : "必须为正";
来源：http://dali.ppjwa.cn/Article/details/gtcpecqqko.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.aibaodan.cn/Article/details/gthpjuqgfk.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yuxming.cn/Article/details/gtmwugvwqd.html

C#:   Debug.Assert(x > 0);
来源：http://dali.pengpengdd.cyou/Article/details/gtpzyxfwdg.html

[H08] 获取错误信息与堆栈
来源：http://dali.tian-w.cn/Article/details/gtcdnajgtk.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yueranfly.top/Article/details/gtyxoglldv.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jqgfzy.top/Article/details/gtuughgqiv.html

JS:   e.message;  e.stack
来源：http://dali.tian-w.cn/Article/details/gtrtcrlqwn.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yanxiufei.cn/Article/details/gtaemrpayo.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.chenjidiqi.icu/Article/details/gtcoarqfwn.html

Go:   err.Error()
来源：http://dali.kuanghao11.cn/Article/details/gtgvymgzol.html

Ruby: e.message;  e.backtrace
来源：http://dali.sxryk.cn/Article/details/gtuwowphqx.html

C#:   e.Message;  e.StackTrace
来源：http://dali.gzhubu.top/Article/details/gtrhoqemon.html

[H09] 带错误码的异常
来源：http://dali.dianchejie.cn/Article/details/gtbqnseqoz.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.meibo888.top/Article/details/gttwncpujc.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.redwolf501.top/Article/details/gtccdeihds.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yvedp.cn/Article/details/gtelelmidc.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.hfpthk.cn/Article/details/gtbrzushjm.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.snrcjt.cn/Article/details/gtesfhsgen.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.chenlongwang.top/Article/details/gtwkpglkwx.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yongpay.top/Article/details/gtzdmexdni.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhijiandao.cn/Article/details/gtavbbkekw.html

[H10] 资源自动释放
来源：http://dali.meibo888.top/Article/details/gtfgsminvq.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhongyouzk.top/Article/details/gtntpsbbhg.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.vqdsnc.cn/Article/details/gtbhsiehla.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jiagoushi.top/Article/details/gtrildrcjl.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zdqjudy.top/Article/details/gtcwatfrch.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yj20258.top/Article/details/gtldbsesqn.html

Go:   defer f.Close()
来源：http://dali.shanyushiyangkeji.top/Article/details/gteobyblxh.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.pycfn.com/Article/details/gtmjvgufve.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxyaeduwm.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtcvokabnt.html

I. 正则表达式
来源：http://dali.zdqjudy.top/Article/details/gtzsfligrp.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtrelknogb.html

[I01] 判断是否匹配
来源：http://dali.jinghuilouyu.cn/Article/details/gtxwtmnbbf.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.yonumen.top/Article/details/gtdshxwbce.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.gogol.net.cn/Article/details/gtmmjeeduf.html

JS:   /\d+/.test(s)
来源：http://dali.birdmap.top/Article/details/gtrsewhldy.html

TS:   /\d+/.test(s)
来源：http://dali.nanxuanxn.top/Article/details/gtwkafdhmr.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.andypj.xyz/Article/details/gtizvauejs.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.jiagoushi.top/Article/details/gtbvgsjuyf.html

Ruby: s.match?(/\d+/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoegbsgtp.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.yj20258888.top/Article/details/gtxspxmuzx.html

[I02] 提取所有匹配
来源：http://dali.sufxvd.cn/Article/details/gtvpszecko.html

Py:   re.findall(r"\d+", s)
来源：http://dali.aibaodan.cn/Article/details/gtbfcchtum.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.hnqzz.top/Article/details/gtbaigwwqz.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yj20258.top/Article/details/gtiphlgcra.html

TS:   s.match(/\d+/g)
来源：http://dali.hnqzz.top/Article/details/gttjmmujjm.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.zhongyouzk.top/Article/details/gtosjfdtyf.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.zhongyouzk.top/Article/details/gtkxdbwvfy.html

Ruby: s.scan(/\d+/)
来源：http://dali.dianchejie.cn/Article/details/gtewhdvvzt.html


<!-- 参考信息 -->