代发 wailian999

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhoulong.xyz/Article/details/gtbwyixbaq.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.meibo888.top/Article/details/gtpqcwtedk.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.ppjwa.cn/Article/details/gtqqbcrlxt.html

[F08] 遍历目录
来源：http://dali.nwbrower.top/Article/details/gthmdtgvqp.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhengqikj.top/Article/details/gttabdokcl.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhijiandao.cn/Article/details/gtfwlfwcuv.html

JS:   fs.readdirSync("dir")
来源：http://dali.feifeiyinyue.top/Article/details/gtdinhfefi.html

TS:   fs.readdirSync("dir")
来源：http://dali.cheryme.top/Article/details/gtwfldptqu.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.tian-w.cn/Article/details/gtbncadynm.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yangfankeji.com/Article/details/gtvakcbvto.html

Ruby: Dir.children("dir")
来源：http://dali.zhongyouzk.top/Article/details/gtcqhykbyl.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yangfankeji.com/Article/details/gtxrqgsfhf.html

[F09] 获取文件大小
来源：http://dali.svipenyu.cn/Article/details/gttvalnszo.html

Py:   os.path.getsize("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtvitccqmy.html

PHP:  filesize("a.txt");
来源：http://dali.jyoumei.cn/Article/details/gtcwjgrndg.html

JS:   fs.statSync("a.txt").size
来源：http://dali.hnxiangtu.top/Article/details/gteossyjiy.html

TS:   fs.statSync("a.txt").size
来源：http://dali.ydzc1.top/Article/details/gtzztrmtpm.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.daxiang520.top/Article/details/gtxhrpzwzd.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.andypj.xyz/Article/details/gtqdsbjflz.html

Ruby: File.size("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtwafxrbph.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zdqjudy.top/Article/details/gtdcjlfqgt.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.tian-w.cn/Article/details/gthpjcuyxv.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yuxming.cn/Article/details/gtzcabrbjx.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.xylfe.cn/Article/details/gttkgfdlsk.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.xinyue.icu/Article/details/gtheekmxbk.html

TS:   path.extname("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtrkoghiqc.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.xuanzx.com/Article/details/gtkacybpjq.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtwgbcutwk.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtuklyjlob.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yj20258.top/Article/details/gtjrxbxxrv.html

[F11] 复制与移动文件
来源：http://dali.ybcxt.top/Article/details/gtqezrvnth.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtqpwwsjad.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.gogol.net.cn/Article/details/gtwmxuqahu.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cdnleiting.top/Article/details/gtyncwxevt.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yj20258.top/Article/details/gtwsmptahx.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.hnqzz.top/Article/details/gtajtigeuk.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.hywenlv.cn/Article/details/gtalvglvol.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.gogol.net.cn/Article/details/gttjsmtdjp.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhoulong.xyz/Article/details/gtpndtcqbq.html

[F12] CSV 读写
来源：http://dali.jinghuilouyu.cn/Article/details/gtzrhmaoof.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jianghu66.top/Article/details/gtyzfvrlja.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.316326.xyz/Article/details/gttxsihirs.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.havefunace.top/Article/details/gteulcykqv.html

TS:   // 同上
来源：http://dali.zhoulong.xyz/Article/details/gtbgfrlscl.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.gogol.net.cn/Article/details/gtqnsxraaz.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.fengsongda.top/Article/details/gtoyglfjjx.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jiagoushi.top/Article/details/gtmldmqppa.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jianghu66.top/Article/details/gtvovqigsv.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtyxgatfrk.html

G. 面向对象
来源：http://dali.yangfankeji.com/Article/details/gtnkzoptmn.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtxevwvrmf.html

[G01] 定义类
来源：http://dali.jinghuilouyu.cn/Article/details/gtkvmafoez.html

Py:   class User: pass
来源：http://dali.chenzaomai.com/Article/details/gteexmauwm.html

PHP:  class User {}
来源：http://dali.yj20258888.top/Article/details/gtfgekdgcw.html

JS:   class User {}
来源：http://dali.yj202588.top/Article/details/gtlydkging.html

TS:   class User { name: string = ""; }
来源：http://dali.yonumen.top/Article/details/gtgnwseqyu.html

Java: class User {}
来源：http://dali.yonumen.top/Article/details/gtpxykxoru.html

Go:   type User struct { Name string }
来源：http://dali.cdnleiting.top/Article/details/gtsssmdgkg.html

Ruby: class User; end
来源：http://dali.gotoacloud.top/Article/details/gtdmkbfxyn.html

C#:   class User {}
来源：http://dali.smart0.xyz/Article/details/gtdjxwgqsc.html

[G02] 构造函数
来源：http://dali.nanxuanxn.top/Article/details/gtxxomuewe.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.shangyingyoupin.top/Article/details/gtxibcioqi.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.xuanzx.com/Article/details/gtmbwrdwrs.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yanxiufei.cn/Article/details/gtivqboseb.html

TS:   constructor(public name: string) {}
来源：http://dali.tianlin.xyz/Article/details/gtuajopfps.html

Java: User(String name) { this.name = name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtiijrvbsy.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hysaishi.cn/Article/details/gtjkqupkbv.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.aizwys.cn/Article/details/gthcclepez.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yangfankeji.com/Article/details/gthyxgsdnr.html

[G03] 实例属性
来源：http://dali.cqqwz.cn/Article/details/gtvjixngrn.html

Py:   self.name = "x"
来源：http://dali.cucudq.cn/Article/details/gtzcxvvymg.html

PHP:  public string $name = "x";
来源：http://dali.cucudq.cn/Article/details/gtbguyeisn.html

JS:   this.name = "x";
来源：http://dali.zdqjudy.top/Article/details/gtzoltaikf.html

TS:   name: string = "x";
来源：http://dali.tianlin.xyz/Article/details/gtmqaxmcmh.html

Java: private String name;
来源：http://dali.yuxming.cn/Article/details/gtvoyyhzbl.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.aizwys.cn/Article/details/gtgqhjezgz.html

Ruby: @name = "x"
来源：http://dali.yj202588.top/Article/details/gtmzcictso.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.dashuyun.cn/Article/details/gtenwdnclb.html

[G04] 定义方法
来源：http://dali.zdqjudy.top/Article/details/gtqxollzta.html

Py:   def greet(self): return self.name
来源：http://dali.wangdashe.top/Article/details/gtkgrmpcqr.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yangfankeji.com/Article/details/gtxwjbusrr.html

JS:   greet() { return this.name; }
来源：http://dali.andypj.xyz/Article/details/gtgmvisufr.html

TS:   greet(): string { return this.name; }
来源：http://dali.dianchejie.cn/Article/details/gtjlupfqzx.html

Java: String greet() { return name; }
来源：http://dali.zhengqikj.top/Article/details/gtolvuujrd.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhixingplan.top/Article/details/gtweiuersi.html

Ruby: def greet; @name; end
来源：http://dali.cqqwz.cn/Article/details/gtzfxbqhrf.html

C#:   public string Greet() => Name;
来源：http://dali.yuxming.cn/Article/details/gtridtjmbp.html

[G05] 继承
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgrdcskuu.html

Py:   class Admin(User): pass
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzbinqool.html

PHP:  class Admin extends User {}
来源：http://dali.jinqigufen.top/Article/details/gtegqiuwkh.html

JS:   class Admin extends User {}
来源：http://dali.haohaochexian.top/Article/details/gtlmikvycj.html

TS:   class Admin extends User {}
来源：http://dali.zhongyouzk.top/Article/details/gtuxmbgrml.html

Java: class Admin extends User {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtueuebjvi.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yangfankeji.com/Article/details/gtqpwrffqf.html

Ruby: class Admin < User; end
来源：http://dali.jinqigufen.top/Article/details/gtriukjilk.html

C#:   class Admin : User {}
来源：http://dali.hysaishi.cn/Article/details/gteeodfmap.html

[G06] 重写方法
来源：http://dali.xinyue.icu/Article/details/gtmzeydfce.html

Py:   def greet(self): return "admin"
来源：http://dali.xuanzx.com/Article/details/gtzwujpisf.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtsvyhjfle.html

JS:   greet() { return "admin"; }
来源：http://dali.xuanzx.com/Article/details/gtiuhepwyb.html

TS:   greet(): string { return "admin"; }
来源：http://dali.feifeiyinyue.top/Article/details/gtoiawktsh.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.andypj.xyz/Article/details/gtsnirmilb.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yangfankeji.com/Article/details/gtaqfymwka.html

Ruby: def greet; "admin"; end
来源：http://dali.yueranfly.top/Article/details/gtzkrbfhgp.html

C#:   public override string Greet() => "admin";
来源：http://dali.yj20258888.top/Article/details/gteyvxuijw.html

[G07] 调用父类方法
来源：http://dali.chenzaomai.com/Article/details/gtdfzhsowa.html

Py:   super().greet()
来源：http://dali.xinyue.icu/Article/details/gtgzigahoc.html

PHP:  parent::greet();
来源：http://dali.zhixingplan.top/Article/details/gtybxlxuxl.html

JS:   super.greet();
来源：http://dali.meibo888.top/Article/details/gtmvgweehg.html

TS:   super.greet();
来源：http://dali.gotoacloud.top/Article/details/gtbybtpvuf.html

Java: super.greet();
来源：http://dali.xuanzx.com/Article/details/gtwjqcaejn.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zdqjudy.top/Article/details/gtlnvzhgie.html

Ruby: super
来源：http://dali.shanyushiyangtech.top/Article/details/gtcbrtcczn.html

C#:   base.Greet();
来源：http://dali.yuanzhike.top/Article/details/gthrjxochi.html

[G08] 静态方法与属性
来源：http://dali.sufxvd.cn/Article/details/gtwcowcnry.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.sxryk.cn/Article/details/gtkceuutee.html

PHP:  public static function f() {}
来源：http://dali.daxiang520.top/Article/details/gttdvqutsz.html

JS:   static f() {}
来源：http://dali.kuanghao11.cn/Article/details/gtaoljumov.html

TS:   static f(): void {}
来源：http://dali.gogol.net.cn/Article/details/gtscfsdsub.html

Java: static void f() {}
来源：http://dali.zhongyouzk.top/Article/details/gtjrjauwjk.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.sufxvd.cn/Article/details/gtxexxagkf.html

Ruby: def self.f; end
来源：http://dali.yanxiufei.cn/Article/details/gtjdviecnn.html

C#:   public static void F() {}
来源：http://dali.0kj1m.cn/Article/details/gtitbpogvt.html

[G09] 接口 / 抽象类
来源：http://dali.sufxvd.cn/Article/details/gtlsivsrsw.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yangfankeji.com/Article/details/gtelwlsala.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.ppjwa.cn/Article/details/gtayjvjtlv.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhaomingkeji.xyz/Article/details/gttwlztxeu.html

TS:   interface Shape { area(): number; }
来源：http://dali.andypj.xyz/Article/details/gtnzaresge.html

Java: interface Shape { double area(); }
来源：http://dali.yongpay.top/Article/details/gtufkgttmg.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.sufxvd.cn/Article/details/gtiymsfggz.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.sxryk.cn/Article/details/gtabrdlezt.html

C#:   interface IShape { double Area(); }
来源：http://dali.redwolf501.top/Article/details/gthewizodw.html

[G10] 访问控制
来源：http://dali.zhixingplan.top/Article/details/gtxhuaodli.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.vqdsnc.cn/Article/details/gtfeltfkev.html

PHP:  public / protected / private
来源：http://dali.xinyue.icu/Article/details/gtqckzxqvv.html

JS:   #private 字段；其余公开
来源：http://dali.c1oappe.top/Article/details/gtxdvhqftj.html

TS:   public / protected / private
来源：http://dali.jianghu66.top/Article/details/gtrvlthllk.html

Java: public / protected / private / 默认包级
来源：http://dali.xinyue.icu/Article/details/gtnblauopk.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jqgfzy.top/Article/details/gtghwifjhj.html

Ruby: public / protected / private
来源：http://dali.daria6918.cn/Article/details/gtartcjgry.html

C#:   public / protected / private / internal
来源：http://dali.ydzc1.top/Article/details/gtahrzqnbk.html

[G11] getter / setter
来源：http://dali.yueranfly.top/Article/details/gtovevajly.html

Py:   @property 与 @x.setter
来源：http://dali.nwbrower.top/Article/details/gtmfozgmoi.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.cashguo.top/Article/details/gtbmezgdzu.html

JS:   get name() { return this._name; }
来源：http://dali.nanxinkj.top/Article/details/gtrxvfondz.html

TS:   get name(): string { return this._name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtvxfhndsu.html

Java: public String getName() { return name; }
来源：http://dali.chenzaomai.com/Article/details/gtuovnyukz.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhiwuduotai.top/Article/details/gtyinehbaq.html

Ruby: attr_accessor :name
来源：http://dali.ehwqpu.com/Article/details/gtcbqzowiz.html

C#:   public string Name { get; set; }
来源：http://dali.bjfxy.top/Article/details/gttqocanji.html

[G12] 对象转字符串
来源：http://dali.tian-w.cn/Article/details/gtiudcywbz.html

Py:   def __str__(self): return self.name
来源：http://dali.tianlin.xyz/Article/details/gtnhnxedzh.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yongpay.top/Article/details/gtueydyfac.html

JS:   toString() { return this.name; }
来源：http://dali.smart0.xyz/Article/details/gtqdysqhtj.html

TS:   toString(): string { return this.name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtmjihgcli.html

Java: @Override public String toString() { return name; }
来源：http://dali.nanxuanxn.top/Article/details/gtnkxrnpki.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.kuanghao11.cn/Article/details/gteoovlvzp.html

Ruby: def to_s; @name; end
来源：http://dali.dashuyun.cn/Article/details/gtsitrwnap.html

C#:   public override string ToString() => Name;
来源：http://dali.xylfe.cn/Article/details/gtpttmzgjp.html

[G13] 判断对象类型
来源：http://dali.xinyue.icu/Article/details/gtohllqicb.html

Py:   isinstance(u, User)
来源：http://dali.aizwys.cn/Article/details/gtooanwrex.html

PHP:  $u instanceof User
来源：http://dali.sxryk.cn/Article/details/gtuibxamie.html

JS:   u instanceof User
来源：http://dali.nwbrower.top/Article/details/gtpsgtghqu.html

TS:   u instanceof User
来源：http://dali.cdnleiting.top/Article/details/gtzqnroftu.html

Java: u instanceof User
来源：http://dali.ppjwa.cn/Article/details/gtooykawau.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.chenzaomai.com/Article/details/gtwqqrygzy.html

Ruby: u.is_a?(User)
来源：http://dali.snrcjt.cn/Article/details/gtmoalvgrb.html

C#:   u is User
来源：http://dali.hongshengwenyu.top/Article/details/gtqifibnrl.html

[G14] 数据类 / record
来源：http://dali.svipenyu.cn/Article/details/gtmghbsapi.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.c1oappe.top/Article/details/gtbktytywl.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.svipenyu.cn/Article/details/gtgzlfpijy.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.tianlin.xyz/Article/details/gtnmxwmkyl.html

TS:   type User = { name: string; age: number };
来源：http://dali.daxiang520.top/Article/details/gtgmbywcea.html

Java: record User(String name, int age) {}
来源：http://dali.xinyue.icu/Article/details/gtzwzhmyjc.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hongshengwenyu.top/Article/details/gtpxukazqo.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.fzhhl.top/Article/details/gtekgleexr.html

C#:   record User(string Name, int Age);
来源：http://dali.aizwys.cn/Article/details/gtelyzhbtw.html

[G15] 枚举
来源：http://dali.hfpthk.cn/Article/details/gtihxuhxed.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yuxming.cn/Article/details/gtesxdepwx.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yj20258888.top/Article/details/gtdcknerku.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.nwbrower.top/Article/details/gthkijbgtv.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.316326.xyz/Article/details/gtfhjafomm.html

Java: enum Color { RED, GREEN }
来源：http://dali.c1oappe.top/Article/details/gtcgnvmqpn.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhiwuduotai.top/Article/details/gtphiqslke.html

Ruby: Color = %i[red green].freeze
来源：http://dali.hnqzz.top/Article/details/gtllninbho.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.tianlin.xyz/Article/details/gthbmklrdt.html

[G16] 对象转数组 / 字典
来源：http://dali.yueranfly.top/Article/details/gtwqxsrgbn.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.ydzc1.top/Article/details/gtsbahepin.html

PHP:  get_object_vars($obj);
来源：http://dali.zhixingplan.top/Article/details/gtzthmqfyd.html

JS:   Object.entries(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gthefftikk.html

TS:   Object.entries(obj)
来源：http://dali.xylfe.cn/Article/details/gtjuzpydda.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhixingplan.top/Article/details/gtyncwtota.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yj202588.top/Article/details/gtyprygqcc.html

Ruby: obj.instance_variables
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdxrhipwy.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.gotoacloud.top/Article/details/gtpoekuhkl.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtbakskypj.html

H. 异常与错误处理
来源：http://dali.xuetiantiany.cn/Article/details/gtvzzilpho.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtevfyenkw.html

[H01] try / catch 基础
来源：http://dali.wangdashe.top/Article/details/gtktuwwumj.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.xinyue.icu/Article/details/gthincnhgp.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yuanzhike.top/Article/details/gtgvwguzlu.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.ybcxt.top/Article/details/gtygpohkkz.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.c1oappe.top/Article/details/gtvlablzze.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yangfankeji.com/Article/details/gtuytdvzmk.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhongyouzk.top/Article/details/gtigpgticu.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.tian-w.cn/Article/details/gtqxdwkgmp.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.haohaochexian.top/Article/details/gtjlkyninh.html

[H02] finally / ensure 收尾
来源：http://dali.xylfe.cn/Article/details/gtqdfvizru.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.ybcxt.top/Article/details/gtvvoiuoam.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.vqdsnc.cn/Article/details/gtxtjsexii.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.kuanghao11.cn/Article/details/gtxbaacycq.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhiwuduotai.top/Article/details/gtpftwvyqa.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.smart0.xyz/Article/details/gtmjidpqip.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.sufxvd.cn/Article/details/gtbzmoczfj.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.hnxiangtu.top/Article/details/gtolhcgwqy.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.cashguo.top/Article/details/gtompkityq.html

[H03] 主动抛出异常
来源：http://dali.yonumen.top/Article/details/gtqwkbwlwv.html

Py:   raise ValueError("错误信息")
来源：http://dali.jyoumei.cn/Article/details/gtyvwvgzzi.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.dianchejie.cn/Article/details/gtvtmbxvcb.html

JS:   throw new Error("错误信息");
来源：http://dali.tanke756.top/Article/details/gthmftedvq.html

TS:   throw new Error("错误信息");
来源：http://dali.0kj1m.cn/Article/details/gtdndmxvma.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hammf.cn/Article/details/gtpubviwkj.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhongyouzk.top/Article/details/gtdzifvarr.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.aibaodan.cn/Article/details/gtoakoiqbn.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yueranfly.top/Article/details/gtihhnfqbd.html

[H04] 自定义异常类型
来源：http://dali.jinghuilouyu.cn/Article/details/gtmswnbsjr.html

Py:   class MyError(Exception): pass
来源：http://dali.daxiang520.top/Article/details/gtxohgttga.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jqgfzy.top/Article/details/gtunzlngdf.html

JS:   class MyError extends Error {}
来源：http://dali.yuxming.cn/Article/details/gtbfyhdulq.html

TS:   class MyError extends Error {}
来源：http://dali.chenjidiqi.icu/Article/details/gtfobnlggx.html

Java: class MyException extends RuntimeException {}
来源：http://dali.gotoacloud.top/Article/details/gtjrriwchk.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.vqdsnc.cn/Article/details/gtoposiwde.html

Ruby: class MyError < StandardError; end
来源：http://dali.cheryme.top/Article/details/gtyhafkbuu.html

C#:   class MyException : Exception {}
来源：http://dali.nanxuanxn.top/Article/details/gtkvrgordx.html

[H05] 捕获特定类型
来源：http://dali.hywenlv.cn/Article/details/gtprasffrq.html

Py:   except ValueError as e:
来源：http://dali.zycfv.cn/Article/details/gtkbejrseg.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.wangshuangyany.cn/Article/details/gtgeafhbfm.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.guannengcc.top/Article/details/gtjopwguhi.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.gaohongyu789.top/Article/details/gtxdrtfikt.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hammf.cn/Article/details/gttvdfophy.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.dianchejie.cn/Article/details/gtmhmwxlcg.html

Ruby: rescue ArgumentError => e
来源：http://dali.yangfankeji.com/Article/details/gtccbsqslc.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgzghstqg.html

[H06] 可选值 / 空值安全访问
来源：http://dali.wangdashe.top/Article/details/gtlolhrrlq.html

Py:   value = d.get("k") or default
来源：http://dali.dashuyun.cn/Article/details/gtgotkbqhb.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.shzxlz.cn/Article/details/gteeflbwvb.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.xuanzx.com/Article/details/gtgyckjuhk.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.cashguo.top/Article/details/gtwxtjftpq.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.sxryk.cn/Article/details/gtobsvcjpz.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jinghuilouyu.cn/Article/details/gtjysuzjrc.html

Ruby: d&.dig(:a, :b)
来源：http://dali.xuetiantiany.cn/Article/details/gtecodqqby.html

C#:   obj?.A?.B ?? default
来源：http://dali.tanke756.top/Article/details/gtpxfgxqca.html

[H07] 断言
来源：http://dali.jqgfzy.top/Article/details/gtbgxvbygi.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yangfankeji.com/Article/details/gtrddfrxqs.html

PHP:  assert($x > 0);
来源：http://dali.aibaodan.cn/Article/details/gtajeqrrmw.html

JS:   console.assert(x > 0);
来源：http://dali.tianlin.xyz/Article/details/gtxidsfvbr.html

TS:   console.assert(x > 0);
来源：http://dali.daria6918.cn/Article/details/gtwsjanhfp.html

Java: assert x > 0 : "必须为正";
来源：http://dali.chenjidiqi.icu/Article/details/gtjbgzryjt.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.pengpengdd.cyou/Article/details/gtqcmjysqh.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.chenzaomai.com/Article/details/gtwiohxcqk.html

C#:   Debug.Assert(x > 0);
来源：http://dali.redwolf501.top/Article/details/gtwfkdovjn.html

[H08] 获取错误信息与堆栈
来源：http://dali.wangdashe.top/Article/details/gtvcdmrshq.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiiamonrp.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.chenzaomai.com/Article/details/gtbhkadekw.html

JS:   e.message;  e.stack
来源：http://dali.hongshengwenyu.top/Article/details/gtrihuepip.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.aibaodan.cn/Article/details/gtvqtolycf.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.wangdashe.top/Article/details/gtqozvuwdm.html

Go:   err.Error()
来源：http://dali.sufxvd.cn/Article/details/gtnspvyyku.html

Ruby: e.message;  e.backtrace
来源：http://dali.yj20258888.top/Article/details/gtwspemetw.html

C#:   e.Message;  e.StackTrace
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxqxnopog.html

[H09] 带错误码的异常
来源：http://dali.andypj.xyz/Article/details/gtcvtwguwd.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jinqigufen.top/Article/details/gtulmytmvm.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.smart0.xyz/Article/details/gtokrswrmh.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.fengsongda.top/Article/details/gtblatrthp.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.tian-w.cn/Article/details/gtprguyhwc.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.pycfn.com/Article/details/gtayszlyax.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yj202588.top/Article/details/gtoixfafnc.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.wangdashe.top/Article/details/gtlrfjqxug.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.ywan-chungtsiang.top/Article/details/gtozybinqz.html

[H10] 资源自动释放
来源：http://dali.jiagoushi.top/Article/details/gtzgvqiodb.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.dashuyun.cn/Article/details/gtjiirdqay.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.tanke756.top/Article/details/gteuidsbuw.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gogol.net.cn/Article/details/gtaemdiztf.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hammf.cn/Article/details/gtcqwiffxw.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.cdnleiting.top/Article/details/gtjqmuuvjy.html

Go:   defer f.Close()
来源：http://dali.gogol.net.cn/Article/details/gtkfvvekhb.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.dashuyun.cn/Article/details/gtkfykgwph.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgbalkqkp.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtmvlhbosq.html

I. 正则表达式
来源：http://dali.hfpthk.cn/Article/details/gtstjjouwk.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtdgzaakpy.html

[I01] 判断是否匹配
来源：http://dali.jqgfzy.top/Article/details/gtyunxcobn.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.dianchejie.cn/Article/details/gtnechwrax.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.snrcjt.cn/Article/details/gtnhqcpwmq.html

JS:   /\d+/.test(s)
来源：http://dali.jyoumei.cn/Article/details/gtazryprii.html

TS:   /\d+/.test(s)
来源：http://dali.chenzaomai.com/Article/details/gtsoptbewd.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.ppjwa.cn/Article/details/gtexgoztjc.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.gaohongyu789.top/Article/details/gtrseplutc.html

Ruby: s.match?(/\d+/)
来源：http://dali.shzxlz.cn/Article/details/gtgvqtqfuy.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.xuetiantiany.cn/Article/details/gtrjohmqjh.html


<!-- 参考信息 -->