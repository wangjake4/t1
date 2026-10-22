代发 wailian999

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.birdmap.top/Article/details/gt2eussuvbj.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yanxiufei.cn/Article/details/gt2sikjoemy.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.tanke756.top/Article/details/gt2xevqszzb.html

[F08] 遍历目录
来源：http://dali.c1oappe.top/Article/details/gt2dqwgqzrk.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.meibo888.top/Article/details/gt2sihqoqqg.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.xinyue.icu/Article/details/gt2dxtkidsz.html

JS:   fs.readdirSync("dir")
来源：http://dali.jyoumei.cn/Article/details/gt2ktwcqcmu.html

TS:   fs.readdirSync("dir")
来源：http://dali.andypj.xyz/Article/details/gt2gpggzgxw.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.cqqwz.cn/Article/details/gt2jajqiioz.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jianghu66.top/Article/details/gt2oncdhuda.html

Ruby: Dir.children("dir")
来源：http://dali.gaohongyu789.top/Article/details/gt2qdrrwpho.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hywenlv.cn/Article/details/gt2iarukouz.html

[F09] 获取文件大小
来源：http://dali.haohaochexian.top/Article/details/gt2julkaxua.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wyuyhotn.html

PHP:  filesize("a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gt2yxwhkfyy.html

JS:   fs.statSync("a.txt").size
来源：http://dali.shuidangran.top/Article/details/gt2fmqccvob.html

TS:   fs.statSync("a.txt").size
来源：http://dali.daria6918.cn/Article/details/gt2nszydpvj.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.cdnleiting.top/Article/details/gt2estupdfp.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.cheryme.top/Article/details/gt2agqnqtse.html

Ruby: File.size("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gt2iksmlnrs.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.smart0.xyz/Article/details/gt2zgygwwzp.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.sweek.top/Article/details/gt2lzureyjb.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gt2fzwlaaex.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.mhx1999.top/Article/details/gt2iirqjrfy.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tawvfpfd.html

TS:   path.extname("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2xnyqhidi.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hongshengwenyu.top/Article/details/gt2slqihvom.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2ukrkcyln.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.guannengcc.top/Article/details/gt2kgaamdmw.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2uvnqobch.html

[F11] 复制与移动文件
来源：http://dali.ehwqpu.com/Article/details/gt2wduyklgs.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2miffcijb.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jiagoushi.top/Article/details/gt2rvooihlf.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xinyue.icu/Article/details/gt2atcfdmif.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hgpwcgpo.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yj20258888.top/Article/details/gt2hujlosuo.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhoulong.xyz/Article/details/gt2kgbvfakt.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yuxming.cn/Article/details/gt2iffitrlt.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jinqigufen.top/Article/details/gt2yenhcftx.html

[F12] CSV 读写
来源：http://dali.xinyue.icu/Article/details/gt2qzgjhyoy.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.dianchejie.cn/Article/details/gt2bvflgvsn.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.fengsongda.top/Article/details/gt2vnsfjhrd.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.cashguo.top/Article/details/gt2avhpnubs.html

TS:   // 同上
来源：http://dali.dianchejie.cn/Article/details/gt2ylzkoifr.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.smart0.xyz/Article/details/gt2uyvilplw.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.ehwqpu.com/Article/details/gt2indvzuva.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.smart0.xyz/Article/details/gt2ewktwlna.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.0kj1m.cn/Article/details/gt2zyllkwyt.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2jdkrmdqh.html

G. 面向对象
来源：http://dali.cheryme.top/Article/details/gt2vvqcnnfb.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2yqmwjiof.html

[G01] 定义类
来源：http://dali.bjfxy.top/Article/details/gt2cxgnfzuz.html

Py:   class User: pass
来源：http://dali.zhoulong.xyz/Article/details/gt2ctpwnpjl.html

PHP:  class User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hpgbfntg.html

JS:   class User {}
来源：http://dali.fengsongda.top/Article/details/gt2crcpsiod.html

TS:   class User { name: string = ""; }
来源：http://dali.kuanghao11.cn/Article/details/gt2bbstxnmd.html

Java: class User {}
来源：http://dali.havefunace.top/Article/details/gt2jobhzjux.html

Go:   type User struct { Name string }
来源：http://dali.zhongyouzk.top/Article/details/gt2aextstgl.html

Ruby: class User; end
来源：http://dali.pengpengdd.cyou/Article/details/gt2afkhnhhq.html

C#:   class User {}
来源：http://dali.ivvv.top/Article/details/gt2aqnfrzxq.html

[G02] 构造函数
来源：http://dali.jinqigfzy.top/Article/details/gt2ivwacpwz.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.kuanghao11.cn/Article/details/gt2tspmzuog.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2bloajwos.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.aibaodan.cn/Article/details/gt2khfquwjs.html

TS:   constructor(public name: string) {}
来源：http://dali.xuanzx.com/Article/details/gt2yhjqofiv.html

Java: User(String name) { this.name = name; }
来源：http://dali.yj202588.top/Article/details/gt2yboiwrzy.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jiagoushi.top/Article/details/gt2dxgmqmdb.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.guannengcc.top/Article/details/gt2jjuuorul.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yuanzhike.top/Article/details/gt2szrnsnvo.html

[G03] 实例属性
来源：http://dali.jinqigufen.top/Article/details/gt2twmawmle.html

Py:   self.name = "x"
来源：http://dali.tian-w.cn/Article/details/gt2mvssnybl.html

PHP:  public string $name = "x";
来源：http://dali.ybcxt.top/Article/details/gt2bkojbqig.html

JS:   this.name = "x";
来源：http://dali.xinyue.icu/Article/details/gt2lrszwfrw.html

TS:   name: string = "x";
来源：http://dali.9152youxi.cn/Article/details/gt2mqvpcipf.html

Java: private String name;
来源：http://dali.cucudq.cn/Article/details/gt2jxkzhtdr.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.tianlin.xyz/Article/details/gt2nbnslhxe.html

Ruby: @name = "x"
来源：http://dali.zdqjudy.top/Article/details/gt2plkcpvqz.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yvedp.cn/Article/details/gt2gcthamuq.html

[G04] 定义方法
来源：http://dali.zdqjudy.top/Article/details/gt2scjjzndc.html

Py:   def greet(self): return self.name
来源：http://dali.zhongyouzk.top/Article/details/gt2kebyoabl.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yj20258888.top/Article/details/gt2ibipcfqb.html

JS:   greet() { return this.name; }
来源：http://dali.hnqzz.top/Article/details/gt2loivcftw.html

TS:   greet(): string { return this.name; }
来源：http://dali.aibaodan.cn/Article/details/gt2yxqsvchf.html

Java: String greet() { return name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vmvypylm.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.316326.xyz/Article/details/gt2auxhczad.html

Ruby: def greet; @name; end
来源：http://dali.jiagoushi.top/Article/details/gt2hypjfsza.html

C#:   public string Greet() => Name;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oqhqbqlc.html

[G05] 继承
来源：http://dali.zycfv.cn/Article/details/gt2afheneux.html

Py:   class Admin(User): pass
来源：http://dali.jinqigufen.top/Article/details/gt2etziirwy.html

PHP:  class Admin extends User {}
来源：http://dali.tian-w.cn/Article/details/gt2sixqfums.html

JS:   class Admin extends User {}
来源：http://dali.yvedp.cn/Article/details/gt2rqsrvwir.html

TS:   class Admin extends User {}
来源：http://dali.xylfe.cn/Article/details/gt2stgbyjqx.html

Java: class Admin extends User {}
来源：http://dali.ppjwa.cn/Article/details/gt2zphdkppx.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xybefrlh.html

Ruby: class Admin < User; end
来源：http://dali.cqqwz.cn/Article/details/gt2zsuiuhbl.html

C#:   class Admin : User {}
来源：http://dali.guowangkeji.top/Article/details/gt2lfmyhwib.html

[G06] 重写方法
来源：http://dali.jinqigfzy.top/Article/details/gt2hvchngnz.html

Py:   def greet(self): return "admin"
来源：http://dali.zhongyouzk.top/Article/details/gt2qftmpqmn.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.tian-w.cn/Article/details/gt2tbhifour.html

JS:   greet() { return "admin"; }
来源：http://dali.fengsongda.top/Article/details/gt2limddkcz.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhongyouzk.top/Article/details/gt2vmutnqkd.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vmgqdgyu.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yuxming.cn/Article/details/gt2yydfuynt.html

Ruby: def greet; "admin"; end
来源：http://dali.pycfn.com/Article/details/gt2yuncsmob.html

C#:   public override string Greet() => "admin";
来源：http://dali.gzhubu.top/Article/details/gt2xywampdt.html

[G07] 调用父类方法
来源：http://dali.cheryme.top/Article/details/gt2amfrtbdo.html

Py:   super().greet()
来源：http://dali.aibaodan.cn/Article/details/gt2hliscqtl.html

PHP:  parent::greet();
来源：http://dali.ydzc1.top/Article/details/gt2ztrnmigk.html

JS:   super.greet();
来源：http://dali.dashuyun.cn/Article/details/gt2roynsxbx.html

TS:   super.greet();
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kzbkdywl.html

Java: super.greet();
来源：http://dali.yj20258888.top/Article/details/gt2kjoheupj.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.gzhubu.top/Article/details/gt2dmvtmkmt.html

Ruby: super
来源：http://dali.cashguo.top/Article/details/gt2zxeucvhd.html

C#:   base.Greet();
来源：http://dali.tian-w.cn/Article/details/gt2xokijjuj.html

[G08] 静态方法与属性
来源：http://dali.cqqwz.cn/Article/details/gt2tpawjuem.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.dianchejie.cn/Article/details/gt2mpzwpbsh.html

PHP:  public static function f() {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2xqbfbomc.html

JS:   static f() {}
来源：http://dali.vqdsnc.cn/Article/details/gt2pngjnkgj.html

TS:   static f(): void {}
来源：http://dali.smart0.xyz/Article/details/gt2ezwpnwsq.html

Java: static void f() {}
来源：http://dali.pycfn.com/Article/details/gt2vvftproe.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2pspjbwpy.html

Ruby: def self.f; end
来源：http://dali.birdmap.top/Article/details/gt2eimbnqcv.html

C#:   public static void F() {}
来源：http://dali.kuanghao11.cn/Article/details/gt2cngsqupw.html

[G09] 接口 / 抽象类
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2aqdhhqbt.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.hysaishi.cn/Article/details/gt2dsmkxklg.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cfrouewo.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.havefunace.top/Article/details/gt2zondbxnu.html

TS:   interface Shape { area(): number; }
来源：http://dali.yj202588.top/Article/details/gt2ogzckezc.html

Java: interface Shape { double area(); }
来源：http://dali.haohaochexian.top/Article/details/gt2nlmkuulb.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.wangshuangyany.cn/Article/details/gt2ntpvydyk.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.svipenyu.cn/Article/details/gt2vuyhspnv.html

C#:   interface IShape { double Area(); }
来源：http://dali.dianchejie.cn/Article/details/gt2mmruiykt.html

[G10] 访问控制
来源：http://dali.mhx1999.top/Article/details/gt2uotcqcrl.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jyoumei.cn/Article/details/gt2xbraefuk.html

PHP:  public / protected / private
来源：http://dali.yj20258888.top/Article/details/gt2kzbuycmb.html

JS:   #private 字段；其余公开
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nipoirdu.html

TS:   public / protected / private
来源：http://dali.cashguo.top/Article/details/gt2kesyxmke.html

Java: public / protected / private / 默认包级
来源：http://dali.iojbl.cn/Article/details/gt2tekgazdz.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jinqigufen.top/Article/details/gt2yniijvii.html

Ruby: public / protected / private
来源：http://dali.dianchejie.cn/Article/details/gt2bgtpryhu.html

C#:   public / protected / private / internal
来源：http://dali.chenjidiqi.icu/Article/details/gt2rggwfpjh.html

[G11] getter / setter
来源：http://dali.hnxiangtu.top/Article/details/gt2tzujuysa.html

Py:   @property 与 @x.setter
来源：http://dali.chenzaomai.com/Article/details/gt2uyhkuyxi.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.sysykeji.top/Article/details/gt2uljtkmmv.html

JS:   get name() { return this._name; }
来源：http://dali.dashuyun.cn/Article/details/gt2uqfwxjnn.html

TS:   get name(): string { return this._name; }
来源：http://dali.vqdsnc.cn/Article/details/gt2edvcwzjv.html

Java: public String getName() { return name; }
来源：http://dali.zhoulong.xyz/Article/details/gt2xeqkkosn.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vrmqpbko.html

Ruby: attr_accessor :name
来源：http://dali.yangfankeji.com/Article/details/gt2ybraofrw.html

C#:   public string Name { get; set; }
来源：http://dali.ehwqpu.com/Article/details/gt2qyxiwfiu.html

[G12] 对象转字符串
来源：http://dali.jiagoushi.top/Article/details/gt2vcmcjdyf.html

Py:   def __str__(self): return self.name
来源：http://dali.ybcxt.top/Article/details/gt2kreehcxx.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2gyldxwel.html

JS:   toString() { return this.name; }
来源：http://dali.yueranfly.top/Article/details/gt2dnaonyzy.html

TS:   toString(): string { return this.name; }
来源：http://dali.yj20258888.top/Article/details/gt2spotjsgk.html

Java: @Override public String toString() { return name; }
来源：http://dali.cashguo.top/Article/details/gt2gyqgkasu.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yj20258888.top/Article/details/gt2lrahrkmz.html

Ruby: def to_s; @name; end
来源：http://dali.dashuyun.cn/Article/details/gt2qzvjzkob.html

C#:   public override string ToString() => Name;
来源：http://dali.zdqjudy.top/Article/details/gt2bybkaiev.html

[G13] 判断对象类型
来源：http://dali.hnqzz.top/Article/details/gt2pgjchygw.html

Py:   isinstance(u, User)
来源：http://dali.cashguo.top/Article/details/gt2ortbdkyo.html

PHP:  $u instanceof User
来源：http://dali.nanxuanxn.top/Article/details/gt2weusaqqx.html

JS:   u instanceof User
来源：http://dali.gaohongyu789.top/Article/details/gt2kasljmmf.html

TS:   u instanceof User
来源：http://dali.bjfxy.top/Article/details/gt2flwazprx.html

Java: u instanceof User
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iofetbby.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ezccusua.html

Ruby: u.is_a?(User)
来源：http://dali.feifeiyinyue.top/Article/details/gt2pzktxxvf.html

C#:   u is User
来源：http://dali.zhengqikj.top/Article/details/gt2jjzgcwpx.html

[G14] 数据类 / record
来源：http://dali.guannengcc.top/Article/details/gt2wokycgzk.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.daxiang520.top/Article/details/gt2kbflojnc.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.andypj.xyz/Article/details/gt2nyspswzk.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yangfankeji.com/Article/details/gt2rysjzxzn.html

TS:   type User = { name: string; age: number };
来源：http://dali.9152youxi.cn/Article/details/gt2vmzonzwj.html

Java: record User(String name, int age) {}
来源：http://dali.zhoulong.xyz/Article/details/gt2oyjvaetl.html

Go:   type User struct { Name string; Age int }
来源：http://dali.pycfn.com/Article/details/gt2cmrkpxpp.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.ivvv.top/Article/details/gt2nomgvtcr.html

C#:   record User(string Name, int Age);
来源：http://dali.cdnleiting.top/Article/details/gt2edvvfioi.html

[G15] 枚举
来源：http://dali.nwbrower.top/Article/details/gt2sijdxmzs.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.pengpengdd.cyou/Article/details/gt2vqembfkk.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhoulong.xyz/Article/details/gt2rjhrcpys.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhoulong.xyz/Article/details/gt2mhwnejdy.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.dashuyun.cn/Article/details/gt2mtqytypz.html

Java: enum Color { RED, GREEN }
来源：http://dali.yuxming.cn/Article/details/gt2tralwngq.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.tianlin.xyz/Article/details/gt2nffqllpn.html

Ruby: Color = %i[red green].freeze
来源：http://dali.birdmap.top/Article/details/gt2xgdwacuw.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hnxiangtu.top/Article/details/gt2zhbbuvoz.html

[G16] 对象转数组 / 字典
来源：http://dali.wangdashe.top/Article/details/gt2vwbzcnsg.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yueranfly.top/Article/details/gt2yovxtrbt.html

PHP:  get_object_vars($obj);
来源：http://dali.smart0.xyz/Article/details/gt2dkcrowwh.html

JS:   Object.entries(obj)
来源：http://dali.fengsongda.top/Article/details/gt2ogntnisa.html

TS:   Object.entries(obj)
来源：http://dali.vqdsnc.cn/Article/details/gt2cafckvhl.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.tian-w.cn/Article/details/gt2nbropekh.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.wangshuangyany.cn/Article/details/gt2ynxcwmvz.html

Ruby: obj.instance_variables
来源：http://dali.aibaodan.cn/Article/details/gt2orxmamzl.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yvedp.cn/Article/details/gt2hidoaqpy.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2njgcazqd.html

H. 异常与错误处理
来源：http://dali.zhixingplan.top/Article/details/gt2elhjfdya.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yxmyldnk.html

[H01] try / catch 基础
来源：http://dali.gotoacloud.top/Article/details/gt2tetbdizy.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.hywenlv.cn/Article/details/gt2bkiwtiov.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.daria6918.cn/Article/details/gt2pgapyrsw.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.0kj1m.cn/Article/details/gt2hnxydyre.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.smart0.xyz/Article/details/gt2yxmbvqqo.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tvjoxogu.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hfpthk.cn/Article/details/gt2atiorzoe.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.iojbl.cn/Article/details/gt2yiuaawct.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2pzaamsen.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2qyaieaqc.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zdqjudy.top/Article/details/gt2mkyyhoaq.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.tianlin.xyz/Article/details/gt2ndnoccba.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.birdmap.top/Article/details/gt2jyxkwfpz.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.xinyue.icu/Article/details/gt2vpetkcog.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yonumen.top/Article/details/gt2hqgehxaz.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.ydzc1.top/Article/details/gt2pabsqbbv.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.9152youxi.cn/Article/details/gt2neeugfeb.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.hywenlv.cn/Article/details/gt2kitypser.html

[H03] 主动抛出异常
来源：http://dali.ppjwa.cn/Article/details/gt2zswxfges.html

Py:   raise ValueError("错误信息")
来源：http://dali.hammf.cn/Article/details/gt2egcvownp.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhengqikj.top/Article/details/gt2ogdroflr.html

JS:   throw new Error("错误信息");
来源：http://dali.dianchejie.cn/Article/details/gt2vlxxqisz.html

TS:   throw new Error("错误信息");
来源：http://dali.9152youxi.cn/Article/details/gt2yonuayox.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.316326.xyz/Article/details/gt2wpxexvdd.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.xuanzx.com/Article/details/gt2pldriabc.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhengqikj.top/Article/details/gt2zopzpajc.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.sweek.top/Article/details/gt2ihkuuftw.html

[H04] 自定义异常类型
来源：http://dali.hysaishi.cn/Article/details/gt2ollggheb.html

Py:   class MyError(Exception): pass
来源：http://dali.kuanghao11.cn/Article/details/gt2ujxkvgjr.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhengqikj.top/Article/details/gt2ltktcozl.html

JS:   class MyError extends Error {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jhgxliqf.html

TS:   class MyError extends Error {}
来源：http://dali.xuanzx.com/Article/details/gt2gwkvlqnr.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhixingplan.top/Article/details/gt2tedtctjt.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.chenjidiqi.icu/Article/details/gt2eslqphtr.html

Ruby: class MyError < StandardError; end
来源：http://dali.gogol.net.cn/Article/details/gt2nwtydjwr.html

C#:   class MyException : Exception {}
来源：http://dali.cucudq.cn/Article/details/gt2hcrbtxfk.html

[H05] 捕获特定类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rphtnpgy.html

Py:   except ValueError as e:
来源：http://dali.yj20258888.top/Article/details/gt2zgedqvjv.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.tianlin.xyz/Article/details/gt2yotcouru.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.andypj.xyz/Article/details/gt2kdckptuj.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2wimqedpr.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.shuidangran.top/Article/details/gt2jcllhoia.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhijiandao.cn/Article/details/gt2ulaxdjah.html

Ruby: rescue ArgumentError => e
来源：http://dali.yangfankeji.com/Article/details/gt2mwgcicid.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yuxming.cn/Article/details/gt2egdcdpnc.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dgkrmckc.html

Py:   value = d.get("k") or default
来源：http://dali.9152youxi.cn/Article/details/gt2ncvflmei.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hammf.cn/Article/details/gt2ngxqamly.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.smart0.xyz/Article/details/gt2jwgyhsoj.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.chenzaomai.com/Article/details/gt2ohmhzwwl.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.fzhhl.top/Article/details/gt2vlvbwrva.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.aizwys.cn/Article/details/gt2uxrvxfdn.html

Ruby: d&.dig(:a, :b)
来源：http://dali.xziqi.cn/Article/details/gt2rfbvrgtr.html

C#:   obj?.A?.B ?? default
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lbpdaoos.html

[H07] 断言
来源：http://dali.jinqigufen.top/Article/details/gt2oukebswb.html

Py:   assert x > 0, "必须为正"
来源：http://dali.pycfn.com/Article/details/gt2sdsckxjm.html

PHP:  assert($x > 0);
来源：http://dali.ybcxt.top/Article/details/gt2cpsxeott.html

JS:   console.assert(x > 0);
来源：http://dali.wangdashe.top/Article/details/gt2kvlfshuc.html

TS:   console.assert(x > 0);
来源：http://dali.chenlongwang.top/Article/details/gt2kvehnnml.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jinqigfzy.top/Article/details/gt2ppidgaaj.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhongyouzk.top/Article/details/gt2pmpvgzyw.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ftuwrewn.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jinqigufen.top/Article/details/gt2formghvu.html

[H08] 获取错误信息与堆栈
来源：http://dali.ivvv.top/Article/details/gt2xabcvbbv.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.gaohongyu789.top/Article/details/gt2iokxvswn.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.shanyushiyangtech.top/Article/details/gt2llgyvgaa.html

JS:   e.message;  e.stack
来源：http://dali.tian-w.cn/Article/details/gt2cpojmipc.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.hongshengwenyu.top/Article/details/gt2kuenwwbu.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.shangyingyoupin.top/Article/details/gt2aovpirgo.html

Go:   err.Error()
来源：http://dali.yonumen.top/Article/details/gt2pbielscm.html

Ruby: e.message;  e.backtrace
来源：http://dali.316326.xyz/Article/details/gt2uejovthv.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yj20258888.top/Article/details/gt2onolblvv.html

[H09] 带错误码的异常
来源：http://dali.bjfxy.top/Article/details/gt2wpsxnjdc.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.chenjidiqi.icu/Article/details/gt2mhvokahj.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.nwbrower.top/Article/details/gt2tkjblssm.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2erozzppb.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.bjfxy.top/Article/details/gt2ohsfycdt.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yongpay.top/Article/details/gt2fmxjzkpj.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.havefunace.top/Article/details/gt2wcifcmrp.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhijiandao.cn/Article/details/gt2mgzquocp.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.tanke756.top/Article/details/gt2wktfcvec.html

[H10] 资源自动释放
来源：http://dali.guowangkeji.top/Article/details/gt2ivgdqhye.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jinqigfzy.top/Article/details/gt2ygesutwj.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ismfoxeo.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gotoacloud.top/Article/details/gt2zfdmhtoo.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.pycfn.com/Article/details/gt2jvggtkds.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.sufxvd.cn/Article/details/gt2vnefiasv.html

Go:   defer f.Close()
来源：http://dali.sufxvd.cn/Article/details/gt2okbtjkii.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.9152youxi.cn/Article/details/gt2uqwquywf.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2duuwvpjt.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2txaadraw.html

I. 正则表达式
来源：http://dali.zycfv.cn/Article/details/gt2wwsxehdt.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2fwpnkxsu.html

[I01] 判断是否匹配
来源：http://dali.jqgfzy.top/Article/details/gt2rkmweybv.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2seltcich.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jinqigufen.top/Article/details/gt2pzlpfxyb.html

JS:   /\d+/.test(s)
来源：http://dali.meibo888.top/Article/details/gt2jcdipmbo.html

TS:   /\d+/.test(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ibqslobk.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.ybcxt.top/Article/details/gt2thrqhmad.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.hywenlv.cn/Article/details/gt2iqprrxtd.html

Ruby: s.match?(/\d+/)
来源：http://dali.havefunace.top/Article/details/gt2rkujhltm.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.redwolf501.top/Article/details/gt2dzmwzhsb.html


<!-- 参考信息 -->