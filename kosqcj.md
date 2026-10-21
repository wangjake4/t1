代发 wailian999

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhongyouzk.top/Article/details/gtvyvxqrxs.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.cucudq.cn/Article/details/gtthobbjlp.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yj20258888.top/Article/details/gtltfbwbfo.html

[F08] 遍历目录
来源：http://dali.tianlin.xyz/Article/details/gtqnxpuaki.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.meibo888.top/Article/details/gtxiyzmcls.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zycfv.cn/Article/details/gtygclqhoj.html

JS:   fs.readdirSync("dir")
来源：http://dali.quarkkingdee.top/Article/details/gtodwroypp.html

TS:   fs.readdirSync("dir")
来源：http://dali.jyoumei.cn/Article/details/gterxiserg.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhoulong.xyz/Article/details/gtrnqtpipl.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.shangyingyoupin.top/Article/details/gtqomayksv.html

Ruby: Dir.children("dir")
来源：http://dali.hfpthk.cn/Article/details/gtxrefebgg.html

C#:   Directory.GetFiles("dir")
来源：http://dali.ydzc1.top/Article/details/gtxcbugpis.html

[F09] 获取文件大小
来源：http://dali.yuanzhike.top/Article/details/gtotdpelua.html

Py:   os.path.getsize("a.txt")
来源：http://dali.tian-w.cn/Article/details/gtaeqwyuwy.html

PHP:  filesize("a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gtcqnupjmx.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhongyouzk.top/Article/details/gtkncqodke.html

TS:   fs.statSync("a.txt").size
来源：http://dali.vqdsnc.cn/Article/details/gtyqlkbjhd.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqpihwbzv.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.tanke756.top/Article/details/gtyhsaeqyn.html

Ruby: File.size("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtekbrkgdt.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.feifeiyinyue.top/Article/details/gtlfxonbtb.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yongpay.top/Article/details/gtiqsbznzd.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yangfankeji.com/Article/details/gtauxfzaec.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.tian-w.cn/Article/details/gthinhqmrw.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.fengsongda.top/Article/details/gtvkktgwfi.html

TS:   path.extname("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtvpwbbkxq.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.bjfxy.top/Article/details/gtwhywlxqo.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtttnuvetk.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.fengsongda.top/Article/details/gtpgbjykrf.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtlmygwies.html

[F11] 复制与移动文件
来源：http://dali.0kj1m.cn/Article/details/gttgodbzbe.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.sysykeji.top/Article/details/gtbwjakoab.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.gotoacloud.top/Article/details/gtteoivohy.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.aibaodan.cn/Article/details/gtibcoyewe.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.9152youxi.cn/Article/details/gtlnlvyqgi.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.9152youxi.cn/Article/details/gtqajkjfgj.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jqgfzy.top/Article/details/gtpxtfjznh.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.pycfn.com/Article/details/gtwxjlumuh.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jlsjyb.cn/Article/details/gtrotwoosq.html

[F12] CSV 读写
来源：http://dali.hywenlv.cn/Article/details/gtpfczqcqw.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhongyouzk.top/Article/details/gtytlnudkl.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yvedp.cn/Article/details/gtsiitsgiv.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.birdmap.top/Article/details/gtvpbybsjy.html

TS:   // 同上
来源：http://dali.redwolf501.top/Article/details/gtjamwwrjw.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yonumen.top/Article/details/gtckipacqc.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.fzhhl.top/Article/details/gtjpwlmcov.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.fzhhl.top/Article/details/gtnzczzfky.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jqgfzy.top/Article/details/gtuwjaowbn.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtgkcthgwd.html

G. 面向对象
来源：http://dali.andypj.xyz/Article/details/gtvurogsux.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtlbcvuosi.html

[G01] 定义类
来源：http://dali.xziqi.cn/Article/details/gtpiabketp.html

Py:   class User: pass
来源：http://dali.zhoulong.xyz/Article/details/gtvxxmuatz.html

PHP:  class User {}
来源：http://dali.bjfxy.top/Article/details/gtasldtirf.html

JS:   class User {}
来源：http://dali.bjfxy.top/Article/details/gtaxcquqxq.html

TS:   class User { name: string = ""; }
来源：http://dali.yuanzhike.top/Article/details/gtbbcswkud.html

Java: class User {}
来源：http://dali.tianlin.xyz/Article/details/gtqsgcbngw.html

Go:   type User struct { Name string }
来源：http://dali.tanke756.top/Article/details/gtxmjgfxrh.html

Ruby: class User; end
来源：http://dali.yonumen.top/Article/details/gtxicljhud.html

C#:   class User {}
来源：http://dali.hywenlv.cn/Article/details/gtigwzkeeo.html

[G02] 构造函数
来源：http://dali.smart0.xyz/Article/details/gtpluqyyqh.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.fengsongda.top/Article/details/gteiwhrnsf.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jianghu66.top/Article/details/gtahhaodyo.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtoxhykeeb.html

TS:   constructor(public name: string) {}
来源：http://dali.dianchejie.cn/Article/details/gtuylmhbyt.html

Java: User(String name) { this.name = name; }
来源：http://dali.cdnleiting.top/Article/details/gthhedxdou.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqgegtrrl.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yongpay.top/Article/details/gtzoqktmif.html

C#:   public User(string name) { Name = name; }
来源：http://dali.birdmap.top/Article/details/gtgkdginwt.html

[G03] 实例属性
来源：http://dali.zhoulong.xyz/Article/details/gtpuosnhta.html

Py:   self.name = "x"
来源：http://dali.andypj.xyz/Article/details/gtlemewici.html

PHP:  public string $name = "x";
来源：http://dali.nanxuanxn.top/Article/details/gtpmeachsc.html

JS:   this.name = "x";
来源：http://dali.zhoulong.xyz/Article/details/gtkpobgtvr.html

TS:   name: string = "x";
来源：http://dali.yj20258888.top/Article/details/gtwwiiuvoo.html

Java: private String name;
来源：http://dali.cheryme.top/Article/details/gtyfheiwkq.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yanxiufei.cn/Article/details/gtpkgzxupe.html

Ruby: @name = "x"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtchbjxqgo.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.dashuyun.cn/Article/details/gtrrtazyqa.html

[G04] 定义方法
来源：http://dali.yvedp.cn/Article/details/gtbddjwpyl.html

Py:   def greet(self): return self.name
来源：http://dali.vqdsnc.cn/Article/details/gttdzefrjx.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtbistmhei.html

JS:   greet() { return this.name; }
来源：http://dali.jlsjyb.cn/Article/details/gtzyooupiu.html

TS:   greet(): string { return this.name; }
来源：http://dali.andypj.xyz/Article/details/gttpvhtthn.html

Java: String greet() { return name; }
来源：http://dali.aizwys.cn/Article/details/gtaqicjqoe.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yueranfly.top/Article/details/gtbdtjwgzy.html

Ruby: def greet; @name; end
来源：http://dali.yj202588.top/Article/details/gtjihblxsx.html

C#:   public string Greet() => Name;
来源：http://dali.fengsongda.top/Article/details/gtntnpyodd.html

[G05] 继承
来源：http://dali.chenzaomai.com/Article/details/gtdmfqdutr.html

Py:   class Admin(User): pass
来源：http://dali.chenjidiqi.icu/Article/details/gtsvamwdlo.html

PHP:  class Admin extends User {}
来源：http://dali.yangfankeji.com/Article/details/gtsiwsqbvk.html

JS:   class Admin extends User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfyzrfsiv.html

TS:   class Admin extends User {}
来源：http://dali.redwolf501.top/Article/details/gtrqxacbpm.html

Java: class Admin extends User {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmrytkike.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.cdnleiting.top/Article/details/gtoafepcew.html

Ruby: class Admin < User; end
来源：http://dali.hywenlv.cn/Article/details/gtunarllii.html

C#:   class Admin : User {}
来源：http://dali.xziqi.cn/Article/details/gtebxblpfe.html

[G06] 重写方法
来源：http://dali.mhx1999.top/Article/details/gtuaztlrok.html

Py:   def greet(self): return "admin"
来源：http://dali.wangshuangyany.cn/Article/details/gtoqbbmehn.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.tanke756.top/Article/details/gtfxsidpaz.html

JS:   greet() { return "admin"; }
来源：http://dali.xuanzx.com/Article/details/gtumhenqti.html

TS:   greet(): string { return "admin"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtuwstubae.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.kuanghao11.cn/Article/details/gtlpksdkph.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.pengpengdd.cyou/Article/details/gtewgigflp.html

Ruby: def greet; "admin"; end
来源：http://dali.cashguo.top/Article/details/gtluglnocz.html

C#:   public override string Greet() => "admin";
来源：http://dali.jlsjyb.cn/Article/details/gtumimirkq.html

[G07] 调用父类方法
来源：http://dali.mhx1999.top/Article/details/gtvjikdhse.html

Py:   super().greet()
来源：http://dali.bjfxy.top/Article/details/gtycxadypk.html

PHP:  parent::greet();
来源：http://dali.zhiwuduotai.top/Article/details/gtuttehaxq.html

JS:   super.greet();
来源：http://dali.svipenyu.cn/Article/details/gtfhdcbazj.html

TS:   super.greet();
来源：http://dali.hammf.cn/Article/details/gtvnwwcrkb.html

Java: super.greet();
来源：http://dali.ybcxt.top/Article/details/gtabqxsdug.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.ppjwa.cn/Article/details/gtmntzhddu.html

Ruby: super
来源：http://dali.daria6918.cn/Article/details/gtmvzrvvfl.html

C#:   base.Greet();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzpqyhbyr.html

[G08] 静态方法与属性
来源：http://dali.aizwys.cn/Article/details/gtwbzkmnop.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jinqigufen.top/Article/details/gtyobuqjku.html

PHP:  public static function f() {}
来源：http://dali.gaohongyu789.top/Article/details/gtzpotupit.html

JS:   static f() {}
来源：http://dali.hnxiangtu.top/Article/details/gtqqapviki.html

TS:   static f(): void {}
来源：http://dali.smart0.xyz/Article/details/gtuvcjjjyc.html

Java: static void f() {}
来源：http://dali.fengsongda.top/Article/details/gtvzkihzmv.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhiwuduotai.top/Article/details/gtsztqptzr.html

Ruby: def self.f; end
来源：http://dali.tian-w.cn/Article/details/gttgauqaqb.html

C#:   public static void F() {}
来源：http://dali.daria6918.cn/Article/details/gtcdjbzauh.html

[G09] 接口 / 抽象类
来源：http://dali.hywenlv.cn/Article/details/gtkfmysehu.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yongpay.top/Article/details/gtuujkocld.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhoulong.xyz/Article/details/gtofdonmdz.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.aibaodan.cn/Article/details/gtsyovpadz.html

TS:   interface Shape { area(): number; }
来源：http://dali.sxryk.cn/Article/details/gttookdkmy.html

Java: interface Shape { double area(); }
来源：http://dali.9152youxi.cn/Article/details/gtqpuaeklg.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.guannengcc.top/Article/details/gtsblynhxa.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yueranfly.top/Article/details/gtvrmhwhbd.html

C#:   interface IShape { double Area(); }
来源：http://dali.jlsjyb.cn/Article/details/gtnbammltq.html

[G10] 访问控制
来源：http://dali.guannengcc.top/Article/details/gtsflxjdga.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.xuanzx.com/Article/details/gtwfbummpd.html

PHP:  public / protected / private
来源：http://dali.xinyue.icu/Article/details/gtjpxsfhsf.html

JS:   #private 字段；其余公开
来源：http://dali.yj202588.top/Article/details/gtsqwmdztp.html

TS:   public / protected / private
来源：http://dali.andypj.xyz/Article/details/gtqgzlmqkl.html

Java: public / protected / private / 默认包级
来源：http://dali.xuanzx.com/Article/details/gtykzrmeri.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yj202588.top/Article/details/gtnemqbkdz.html

Ruby: public / protected / private
来源：http://dali.redwolf501.top/Article/details/gtjlitidbx.html

C#:   public / protected / private / internal
来源：http://dali.cashguo.top/Article/details/gtxxuapidl.html

[G11] getter / setter
来源：http://dali.chenlongwang.top/Article/details/gtnsdgmbhp.html

Py:   @property 与 @x.setter
来源：http://dali.zdqjudy.top/Article/details/gtfhxahqta.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.sweek.top/Article/details/gttyedfoex.html

JS:   get name() { return this._name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtcuuupsxu.html

TS:   get name(): string { return this._name; }
来源：http://dali.haohaochexian.top/Article/details/gtysndqkmh.html

Java: public String getName() { return name; }
来源：http://dali.ehwqpu.com/Article/details/gtzvabuook.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.gaohongyu789.top/Article/details/gtntnbnptj.html

Ruby: attr_accessor :name
来源：http://dali.mhx1999.top/Article/details/gtxqxpxhjd.html

C#:   public string Name { get; set; }
来源：http://dali.hammf.cn/Article/details/gtvvpktibx.html

[G12] 对象转字符串
来源：http://dali.xziqi.cn/Article/details/gtcejkozgh.html

Py:   def __str__(self): return self.name
来源：http://dali.daxiang520.top/Article/details/gtprsoddjk.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtzwyjeevi.html

JS:   toString() { return this.name; }
来源：http://dali.daria6918.cn/Article/details/gtvrbavspd.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhongyouzk.top/Article/details/gtudvnxegf.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvyblgyhv.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.dashuyun.cn/Article/details/gtefqxypno.html

Ruby: def to_s; @name; end
来源：http://dali.yueranfly.top/Article/details/gtvfgpsbhn.html

C#:   public override string ToString() => Name;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfffkcryj.html

[G13] 判断对象类型
来源：http://dali.yanxiufei.cn/Article/details/gtklnwknup.html

Py:   isinstance(u, User)
来源：http://dali.nwbrower.top/Article/details/gtbdmfomzm.html

PHP:  $u instanceof User
来源：http://dali.nanxuanxn.top/Article/details/gtfgemrmez.html

JS:   u instanceof User
来源：http://dali.ivvv.top/Article/details/gttfcgnitw.html

TS:   u instanceof User
来源：http://dali.cucudq.cn/Article/details/gtpymlctzj.html

Java: u instanceof User
来源：http://dali.ivvv.top/Article/details/gtjzlbdvwb.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.redwolf501.top/Article/details/gtjdrdmywe.html

Ruby: u.is_a?(User)
来源：http://dali.9152youxi.cn/Article/details/gtlkfmrybn.html

C#:   u is User
来源：http://dali.guannengcc.top/Article/details/gtiymposjd.html

[G14] 数据类 / record
来源：http://dali.xuetiantiany.cn/Article/details/gtkutbjcnj.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yueranfly.top/Article/details/gtjzxniiay.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.cashguo.top/Article/details/gtoflxlpcc.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvzjyrenu.html

TS:   type User = { name: string; age: number };
来源：http://dali.tanke756.top/Article/details/gttvqdtwyt.html

Java: record User(String name, int age) {}
来源：http://dali.mhx1999.top/Article/details/gtobdhtxod.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yuxming.cn/Article/details/gtmzvlioqd.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.nwbrower.top/Article/details/gtzqwquscw.html

C#:   record User(string Name, int Age);
来源：http://dali.fengsongda.top/Article/details/gtqfjanigy.html

[G15] 枚举
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdzydqbjc.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gtapjnefpz.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhengqikj.top/Article/details/gttcpnsxwc.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.meibo888.top/Article/details/gtduqyipxe.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.havefunace.top/Article/details/gtqhrntlgl.html

Java: enum Color { RED, GREEN }
来源：http://dali.gaohongyu789.top/Article/details/gtpzdtsdeu.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.tian-w.cn/Article/details/gtahgvirtq.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jinqigufen.top/Article/details/gtjzfblppk.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shzxlz.cn/Article/details/gtndnzhvtq.html

[G16] 对象转数组 / 字典
来源：http://dali.zdqjudy.top/Article/details/gtyifzbqez.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.redwolf501.top/Article/details/gtsxubuxlp.html

PHP:  get_object_vars($obj);
来源：http://dali.tian-w.cn/Article/details/gtsoiulnfz.html

JS:   Object.entries(obj)
来源：http://dali.tian-w.cn/Article/details/gtbbgeevkc.html

TS:   Object.entries(obj)
来源：http://dali.jqgfzy.top/Article/details/gtrrdmgemk.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhongyouzk.top/Article/details/gtijcjvcdq.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.c1oappe.top/Article/details/gtmcpdbpzs.html

Ruby: obj.instance_variables
来源：http://dali.gogol.net.cn/Article/details/gtbxdxsiju.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.aizwys.cn/Article/details/gtadgpjxqk.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtyyszianj.html

H. 异常与错误处理
来源：http://dali.nwbrower.top/Article/details/gtbqkfmwba.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtupevpfnw.html

[H01] try / catch 基础
来源：http://dali.smart0.xyz/Article/details/gtoiumzozs.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.aibaodan.cn/Article/details/gtkqptvtsn.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yvedp.cn/Article/details/gtdjthiify.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.0kj1m.cn/Article/details/gttcpbtiry.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.iojbl.cn/Article/details/gtnezjckxv.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.snrcjt.cn/Article/details/gtfdsisbpp.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.guannengcc.top/Article/details/gtemwosewl.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.mhx1999.top/Article/details/gtimwneasm.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jqgfzy.top/Article/details/gtndgzrucb.html

[H02] finally / ensure 收尾
来源：http://dali.hammf.cn/Article/details/gtnzuynekb.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.aizwys.cn/Article/details/gtzwbkpcvu.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.chenlongwang.top/Article/details/gtklfjeubh.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ppjwa.cn/Article/details/gthfyvwihw.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgxitdqpo.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.gaohongyu789.top/Article/details/gtlgtqpmfe.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yvedp.cn/Article/details/gtouphwenq.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.nwbrower.top/Article/details/gtdbretpst.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jqgufenzy.top/Article/details/gtjufadjgk.html

[H03] 主动抛出异常
来源：http://dali.c1oappe.top/Article/details/gtuiqukcqi.html

Py:   raise ValueError("错误信息")
来源：http://dali.sufxvd.cn/Article/details/gtcohoyedb.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.feifeiyinyue.top/Article/details/gtngtzehrz.html

JS:   throw new Error("错误信息");
来源：http://dali.jinqigfzy.top/Article/details/gthjtauuem.html

TS:   throw new Error("错误信息");
来源：http://dali.mhx1999.top/Article/details/gtpbuhobur.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.0kj1m.cn/Article/details/gtytwvxibc.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yueranfly.top/Article/details/gtxjbdfgrr.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hywenlv.cn/Article/details/gtfzkgshcs.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.tian-w.cn/Article/details/gttgihitml.html

[H04] 自定义异常类型
来源：http://dali.wangshuangyany.cn/Article/details/gtmqwfrapa.html

Py:   class MyError(Exception): pass
来源：http://dali.fengsongda.top/Article/details/gtmtwlqjhw.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.nanxinkj.top/Article/details/gtafuyewoe.html

JS:   class MyError extends Error {}
来源：http://dali.gaohongyu789.top/Article/details/gtsxzohlnq.html

TS:   class MyError extends Error {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnupdsfva.html

Java: class MyException extends RuntimeException {}
来源：http://dali.cheryme.top/Article/details/gtvcdcishn.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.quarkkingdee.top/Article/details/gtslzikyan.html

Ruby: class MyError < StandardError; end
来源：http://dali.nanxuanxn.top/Article/details/gtikkzgcrq.html

C#:   class MyException : Exception {}
来源：http://dali.andypj.xyz/Article/details/gthghqphdt.html

[H05] 捕获特定类型
来源：http://dali.sxryk.cn/Article/details/gtdpsermwd.html

Py:   except ValueError as e:
来源：http://dali.hnqzz.top/Article/details/gtmimbczwq.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.9152youxi.cn/Article/details/gtzxaaijzi.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.gzhubu.top/Article/details/gtotgcucxo.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtsnuyrvmr.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.tanke756.top/Article/details/gtfpllpbyf.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqgxwjzgn.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhixingplan.top/Article/details/gtqbobjjmc.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jinqigfzy.top/Article/details/gtwpzvgavn.html

[H06] 可选值 / 空值安全访问
来源：http://dali.feifeiyinyue.top/Article/details/gtviaoacew.html

Py:   value = d.get("k") or default
来源：http://dali.jianghu66.top/Article/details/gtfqueqict.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yanxiufei.cn/Article/details/gtbfoqcvmp.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.ybcxt.top/Article/details/gtjiwpqnfi.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.sxryk.cn/Article/details/gtbafadrcs.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yj20258.top/Article/details/gtrxnhjbkq.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnppcchuv.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yj20258888.top/Article/details/gtoztuhrtl.html

C#:   obj?.A?.B ?? default
来源：http://dali.shanyushiyangtech.top/Article/details/gtaueczppg.html

[H07] 断言
来源：http://dali.jinqigufen.top/Article/details/gtaceqhabv.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jlsjyb.cn/Article/details/gtopsbvdfw.html

PHP:  assert($x > 0);
来源：http://dali.c1oappe.top/Article/details/gtonarvaxo.html

JS:   console.assert(x > 0);
来源：http://dali.hywenlv.cn/Article/details/gtjdqpppjj.html

TS:   console.assert(x > 0);
来源：http://dali.fengsongda.top/Article/details/gtgwpsobod.html

Java: assert x > 0 : "必须为正";
来源：http://dali.hnqzz.top/Article/details/gtpargnsfj.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.pengpengdd.cyou/Article/details/gtdftkgwmi.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zhongyouzk.top/Article/details/gtmiqryqpt.html

C#:   Debug.Assert(x > 0);
来源：http://dali.sufxvd.cn/Article/details/gtawxnyrwb.html

[H08] 获取错误信息与堆栈
来源：http://dali.jiagoushi.top/Article/details/gtaqyfwuuo.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.ydzc1.top/Article/details/gtmdhwrfaq.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.cucudq.cn/Article/details/gtydyyuymb.html

JS:   e.message;  e.stack
来源：http://dali.daxiang520.top/Article/details/gtlcfacbuy.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.chenlongwang.top/Article/details/gtdroifilu.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.0kj1m.cn/Article/details/gtxzfaurrw.html

Go:   err.Error()
来源：http://dali.bjfxy.top/Article/details/gtrgvnrhsj.html

Ruby: e.message;  e.backtrace
来源：http://dali.cucudq.cn/Article/details/gtxdmgvxue.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hnqzz.top/Article/details/gtqnvklthx.html

[H09] 带错误码的异常
来源：http://dali.yonumen.top/Article/details/gtcisyzgev.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yangfankeji.com/Article/details/gtnsqkmmnb.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yongpay.top/Article/details/gtkqopfgll.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.cucudq.cn/Article/details/gtcoopbmzf.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.shzxlz.cn/Article/details/gthkerokrj.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.kuanghao11.cn/Article/details/gtxfqfefws.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.cdnleiting.top/Article/details/gtoltftbip.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.gaohongyu789.top/Article/details/gtayrnceoq.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.snrcjt.cn/Article/details/gtgbyjvbab.html

[H10] 资源自动释放
来源：http://dali.hammf.cn/Article/details/gtryleuaxr.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.cqqwz.cn/Article/details/gtptouthnj.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.nwbrower.top/Article/details/gtqvejplld.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.kuanghao11.cn/Article/details/gthcnvqdpc.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shanyushiyangtech.top/Article/details/gtoerrzxub.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.bjfxy.top/Article/details/gtlaxlxcau.html

Go:   defer f.Close()
来源：http://dali.zhoulong.xyz/Article/details/gtlgyaccpf.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jqgufenzy.top/Article/details/gtxmkepenl.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gtrwcufhdg.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gthwavqrdw.html

I. 正则表达式
来源：http://dali.jinqigfzy.top/Article/details/gtgwgnzdlp.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtgvhspjax.html

[I01] 判断是否匹配
来源：http://dali.cdnleiting.top/Article/details/gtphzxasnw.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.hammf.cn/Article/details/gtsttrfhog.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jqgfzy.top/Article/details/gtzwexkcby.html

JS:   /\d+/.test(s)
来源：http://dali.yuanzhike.top/Article/details/gtxoswvour.html

TS:   /\d+/.test(s)
来源：http://dali.gogol.net.cn/Article/details/gtqxxikszr.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jqgufenzy.top/Article/details/gtfblynztt.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.aibaodan.cn/Article/details/gtcrklekrp.html

Ruby: s.match?(/\d+/)
来源：http://dali.jiagoushi.top/Article/details/gtswajfgtw.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmxrbwfjh.html


<!-- 参考信息 -->