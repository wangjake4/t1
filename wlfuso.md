代发 wailian999

JS:   fs.unlinkSync("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtopbfyqat.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.hammf.cn/Article/details/gtvckmrplc.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.0kj1m.cn/Article/details/gtidikzzja.html

Go:   os.Remove("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtcjiskite.html

Ruby: File.delete("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtibzfydjx.html

C#:   File.Delete("a.txt");
来源：http://dali.xylfe.cn/Article/details/gtblumkxvh.html

[F07] 创建目录（含多级）
来源：http://dali.yanxiufei.cn/Article/details/gtujfajqdm.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.shzxlz.cn/Article/details/gtbbwxjipq.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.316326.xyz/Article/details/gtfaoakkcy.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttuxxamwc.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.0kj1m.cn/Article/details/gtyoaajsut.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.daxiang520.top/Article/details/gtpiwqykox.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.havefunace.top/Article/details/gtfdamhgpz.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.aizwys.cn/Article/details/gtzsimlyef.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.cdnleiting.top/Article/details/gtkfjpdpbg.html

[F08] 遍历目录
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjosqppdm.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yueranfly.top/Article/details/gtxopggukj.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jqgfzy.top/Article/details/gtbnoidpss.html

JS:   fs.readdirSync("dir")
来源：http://dali.gogol.net.cn/Article/details/gtycioevgo.html

TS:   fs.readdirSync("dir")
来源：http://dali.hywenlv.cn/Article/details/gtmbtlgtkp.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.cheryme.top/Article/details/gtctiiedhc.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gtarpcgtzr.html

Ruby: Dir.children("dir")
来源：http://dali.jianghu66.top/Article/details/gtcznbnjpm.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yueranfly.top/Article/details/gtamleedvc.html

[F09] 获取文件大小
来源：http://dali.c1oappe.top/Article/details/gtpbkjytdd.html

Py:   os.path.getsize("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtthxpdwha.html

PHP:  filesize("a.txt");
来源：http://dali.jinqigufen.top/Article/details/gtmbxdgktm.html

JS:   fs.statSync("a.txt").size
来源：http://dali.aizwys.cn/Article/details/gtrvwwzhpc.html

TS:   fs.statSync("a.txt").size
来源：http://dali.xuanzx.com/Article/details/gtlnlwwijs.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yuxming.cn/Article/details/gtyfsveccu.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.shuidangran.top/Article/details/gtjvhbpjri.html

Ruby: File.size("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtgchgksai.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.hysaishi.cn/Article/details/gtnzyepnln.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.wangdashe.top/Article/details/gtrobgigwg.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtrkigdnzq.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.wangdashe.top/Article/details/gtcefnuzdv.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtriyolilg.html

TS:   path.extname("a.txt")
来源：http://dali.smart0.xyz/Article/details/gtghkgiscy.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hnqzz.top/Article/details/gtpthfeoqy.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.gotoacloud.top/Article/details/gttovuuuxr.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtlezjrnok.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.cucudq.cn/Article/details/gtmldvyayd.html

[F11] 复制与移动文件
来源：http://dali.nwbrower.top/Article/details/gtspooshtl.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhengqikj.top/Article/details/gtmyqgjpap.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.pycfn.com/Article/details/gtpmjrsfmn.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cheryme.top/Article/details/gtuluxykdq.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ppjwa.cn/Article/details/gtbatfekou.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.ivvv.top/Article/details/gtplgcjhzy.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.tian-w.cn/Article/details/gtfewvasaf.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.sweek.top/Article/details/gtmhsgmtid.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yj202588.top/Article/details/gtjxxxlcps.html

[F12] CSV 读写
来源：http://dali.xinyue.icu/Article/details/gtkmxqfzia.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.guowangkeji.top/Article/details/gtfmdmwlko.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.ybcxt.top/Article/details/gteztsbmha.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.chenlongwang.top/Article/details/gtdvbyovxh.html

TS:   // 同上
来源：http://dali.ywan-chungtsiang.top/Article/details/gtajorxuoz.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhixingplan.top/Article/details/gtwllmgwws.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.iojbl.cn/Article/details/gtwflgzpqs.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdlvtizlj.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.guannengcc.top/Article/details/gtbhskqdor.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtdsudcrsp.html

G. 面向对象
来源：http://dali.gzhubu.top/Article/details/gtweeksmga.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtwuevvtcq.html

[G01] 定义类
来源：http://dali.jqgfzy.top/Article/details/gtsqxwkbtz.html

Py:   class User: pass
来源：http://dali.nwbrower.top/Article/details/gtjmdtlejb.html

PHP:  class User {}
来源：http://dali.gzhubu.top/Article/details/gtvxrdavvl.html

JS:   class User {}
来源：http://dali.jqgfzy.top/Article/details/gtgtpkkmnc.html

TS:   class User { name: string = ""; }
来源：http://dali.nanxinkj.top/Article/details/gtpraqhhoo.html

Java: class User {}
来源：http://dali.zhoulong.xyz/Article/details/gthkppehgu.html

Go:   type User struct { Name string }
来源：http://dali.pycfn.com/Article/details/gtytzfttmh.html

Ruby: class User; end
来源：http://dali.zhiwuduotai.top/Article/details/gtqvoscfbq.html

C#:   class User {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtptlcnvjc.html

[G02] 构造函数
来源：http://dali.jqgufenzy.top/Article/details/gtyqfkqwyf.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.gotoacloud.top/Article/details/gtnykdulml.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.xuanzx.com/Article/details/gtrpwkrwyn.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yj20258.top/Article/details/gtvjhedemw.html

TS:   constructor(public name: string) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkvhnxfrv.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtthcolzjo.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.aibaodan.cn/Article/details/gttardzjxx.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jinqigfzy.top/Article/details/gtoydcslsk.html

C#:   public User(string name) { Name = name; }
来源：http://dali.shzxlz.cn/Article/details/gtzvivtech.html

[G03] 实例属性
来源：http://dali.hongshengwenyu.top/Article/details/gtdljeavjr.html

Py:   self.name = "x"
来源：http://dali.aibaodan.cn/Article/details/gtidzdqbov.html

PHP:  public string $name = "x";
来源：http://dali.iojbl.cn/Article/details/gtlslrjkyd.html

JS:   this.name = "x";
来源：http://dali.chenzaomai.com/Article/details/gtugvfauun.html

TS:   name: string = "x";
来源：http://dali.pengpengdd.cyou/Article/details/gtwsowqkxx.html

Java: private String name;
来源：http://dali.tianlin.xyz/Article/details/gtfboshxio.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.ydzc1.top/Article/details/gtazceozzt.html

Ruby: @name = "x"
来源：http://dali.yj202588.top/Article/details/gtvrcyswxa.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.c1oappe.top/Article/details/gtqsnrhajp.html

[G04] 定义方法
来源：http://dali.cucudq.cn/Article/details/gtperoupeg.html

Py:   def greet(self): return self.name
来源：http://dali.tian-w.cn/Article/details/gtlnwqrbtt.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.ppjwa.cn/Article/details/gtlrkhroiv.html

JS:   greet() { return this.name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzjozkgag.html

TS:   greet(): string { return this.name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtqonzwkgk.html

Java: String greet() { return name; }
来源：http://dali.daria6918.cn/Article/details/gtqwykypiv.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jianghu66.top/Article/details/gtatbfxxnq.html

Ruby: def greet; @name; end
来源：http://dali.birdmap.top/Article/details/gtzevxrkwv.html

C#:   public string Greet() => Name;
来源：http://dali.sweek.top/Article/details/gtlwusrrfo.html

[G05] 继承
来源：http://dali.sweek.top/Article/details/gtuqzodchu.html

Py:   class Admin(User): pass
来源：http://dali.daxiang520.top/Article/details/gtiyfymcsk.html

PHP:  class Admin extends User {}
来源：http://dali.ybcxt.top/Article/details/gtawmyhmdc.html

JS:   class Admin extends User {}
来源：http://dali.vqdsnc.cn/Article/details/gtckqzrotq.html

TS:   class Admin extends User {}
来源：http://dali.jianghu66.top/Article/details/gthxxacwvk.html

Java: class Admin extends User {}
来源：http://dali.zycfv.cn/Article/details/gtrwaratws.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.aibaodan.cn/Article/details/gtwbfwjqxp.html

Ruby: class Admin < User; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlapdvtxl.html

C#:   class Admin : User {}
来源：http://dali.birdmap.top/Article/details/gtlxbvzkao.html

[G06] 重写方法
来源：http://dali.smart0.xyz/Article/details/gtcbjidbbw.html

Py:   def greet(self): return "admin"
来源：http://dali.gaohongyu789.top/Article/details/gtfzlocluw.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.gaohongyu789.top/Article/details/gtlrrufbvk.html

JS:   greet() { return "admin"; }
来源：http://dali.ivvv.top/Article/details/gtkaykoqix.html

TS:   greet(): string { return "admin"; }
来源：http://dali.cqqwz.cn/Article/details/gtrpljlmeo.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.shangyingyoupin.top/Article/details/gtinnhcdoe.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.c1oappe.top/Article/details/gtopnybwlk.html

Ruby: def greet; "admin"; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkvusiibi.html

C#:   public override string Greet() => "admin";
来源：http://dali.tanke756.top/Article/details/gtxwsbaekg.html

[G07] 调用父类方法
来源：http://dali.tianlin.xyz/Article/details/gtvgzdajss.html

Py:   super().greet()
来源：http://dali.mhx1999.top/Article/details/gtmnuwshvu.html

PHP:  parent::greet();
来源：http://dali.redwolf501.top/Article/details/gtlppawpja.html

JS:   super.greet();
来源：http://dali.yueranfly.top/Article/details/gtvzxxkcdw.html

TS:   super.greet();
来源：http://dali.tanke756.top/Article/details/gtjmmioejo.html

Java: super.greet();
来源：http://dali.cashguo.top/Article/details/gtjnocexdk.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jlsjyb.cn/Article/details/gtolvelnqj.html

Ruby: super
来源：http://dali.yj202588.top/Article/details/gtrigkofwc.html

C#:   base.Greet();
来源：http://dali.xinyue.icu/Article/details/gtyfeyozet.html

[G08] 静态方法与属性
来源：http://dali.xinyue.icu/Article/details/gthqzixnhz.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhixingplan.top/Article/details/gtvbvkrpqp.html

PHP:  public static function f() {}
来源：http://dali.jyoumei.cn/Article/details/gtntuozssm.html

JS:   static f() {}
来源：http://dali.yangfankeji.com/Article/details/gtgkldoiqv.html

TS:   static f(): void {}
来源：http://dali.cheryme.top/Article/details/gtxsgaqzfj.html

Java: static void f() {}
来源：http://dali.meibo888.top/Article/details/gtdughxeah.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.guowangkeji.top/Article/details/gtnycpkdxd.html

Ruby: def self.f; end
来源：http://dali.aibaodan.cn/Article/details/gtpdqgzwfa.html

C#:   public static void F() {}
来源：http://dali.smart0.xyz/Article/details/gtwsjtpauj.html

[G09] 接口 / 抽象类
来源：http://dali.yueranfly.top/Article/details/gtfajfsddt.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yvedp.cn/Article/details/gtvrujchja.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yuanzhike.top/Article/details/gtgfqolrhv.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.sweek.top/Article/details/gtwhbohzzd.html

TS:   interface Shape { area(): number; }
来源：http://dali.jyoumei.cn/Article/details/gtboartkle.html

Java: interface Shape { double area(); }
来源：http://dali.feifeiyinyue.top/Article/details/gtoxmifbhl.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.quarkkingdee.top/Article/details/gtcfrjoldr.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhongyouzk.top/Article/details/gtcainptvk.html

C#:   interface IShape { double Area(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnaxvifvo.html

[G10] 访问控制
来源：http://dali.zhiwuduotai.top/Article/details/gtkhlmiyzl.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jinghuilouyu.cn/Article/details/gtlwovmabx.html

PHP:  public / protected / private
来源：http://dali.feifeiyinyue.top/Article/details/gtnjtgaeee.html

JS:   #private 字段；其余公开
来源：http://dali.zhoulong.xyz/Article/details/gtcghpqiji.html

TS:   public / protected / private
来源：http://dali.kuanghao11.cn/Article/details/gtjlpbcyim.html

Java: public / protected / private / 默认包级
来源：http://dali.chenjidiqi.icu/Article/details/gtteorhsop.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.tanke756.top/Article/details/gtzjyifrar.html

Ruby: public / protected / private
来源：http://dali.aibaodan.cn/Article/details/gtyumqxntp.html

C#:   public / protected / private / internal
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrtlvlobp.html

[G11] getter / setter
来源：http://dali.smart0.xyz/Article/details/gtzddbfrwo.html

Py:   @property 与 @x.setter
来源：http://dali.guannengcc.top/Article/details/gtkobzcabg.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.shangyingyoupin.top/Article/details/gthowcjpny.html

JS:   get name() { return this._name; }
来源：http://dali.jianghu66.top/Article/details/gtfbetlsxt.html

TS:   get name(): string { return this._name; }
来源：http://dali.sysykeji.top/Article/details/gtyejgecie.html

Java: public String getName() { return name; }
来源：http://dali.yongpay.top/Article/details/gtmtdjhzpk.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdxxwsour.html

Ruby: attr_accessor :name
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlyolgbvd.html

C#:   public string Name { get; set; }
来源：http://dali.hywenlv.cn/Article/details/gtaxydhlbc.html

[G12] 对象转字符串
来源：http://dali.mhx1999.top/Article/details/gththlqavq.html

Py:   def __str__(self): return self.name
来源：http://dali.feifeiyinyue.top/Article/details/gtiacmlhxv.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.chenzaomai.com/Article/details/gtmlghrqhy.html

JS:   toString() { return this.name; }
来源：http://dali.hysaishi.cn/Article/details/gtwwecuzoc.html

TS:   toString(): string { return this.name; }
来源：http://dali.pycfn.com/Article/details/gtrsggcixw.html

Java: @Override public String toString() { return name; }
来源：http://dali.gotoacloud.top/Article/details/gtqvvgsqdi.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.pycfn.com/Article/details/gtjdvtihil.html

Ruby: def to_s; @name; end
来源：http://dali.andypj.xyz/Article/details/gtdfinmygn.html

C#:   public override string ToString() => Name;
来源：http://dali.ydzc1.top/Article/details/gtxbsewjpx.html

[G13] 判断对象类型
来源：http://dali.cqqwz.cn/Article/details/gttrcetmnk.html

Py:   isinstance(u, User)
来源：http://dali.guannengcc.top/Article/details/gtfuhvckod.html

PHP:  $u instanceof User
来源：http://dali.nanxinkj.top/Article/details/gtecsomqia.html

JS:   u instanceof User
来源：http://dali.cdnleiting.top/Article/details/gtuatxprch.html

TS:   u instanceof User
来源：http://dali.meibo888.top/Article/details/gtkkrebbma.html

Java: u instanceof User
来源：http://dali.9152youxi.cn/Article/details/gtnaomvlyb.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthvrigoic.html

Ruby: u.is_a?(User)
来源：http://dali.cashguo.top/Article/details/gtumgjnkvd.html

C#:   u is User
来源：http://dali.gaohongyu789.top/Article/details/gtibgskfiz.html

[G14] 数据类 / record
来源：http://dali.bjfxy.top/Article/details/gtmupxolfx.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.ywan-chungtsiang.top/Article/details/gtobmfqjqv.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.cheryme.top/Article/details/gtnblbgace.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hywenlv.cn/Article/details/gtxzhcodyd.html

TS:   type User = { name: string; age: number };
来源：http://dali.nanxinkj.top/Article/details/gtsisixrpc.html

Java: record User(String name, int age) {}
来源：http://dali.hysaishi.cn/Article/details/gthewsaupr.html

Go:   type User struct { Name string; Age int }
来源：http://dali.gotoacloud.top/Article/details/gtirgqocmq.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.chenzaomai.com/Article/details/gtffidusxs.html

C#:   record User(string Name, int Age);
来源：http://dali.gzhubu.top/Article/details/gttmvzmfsr.html

[G15] 枚举
来源：http://dali.yvedp.cn/Article/details/gthhbuyium.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.c1oappe.top/Article/details/gtlqhdiauu.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhiwuduotai.top/Article/details/gthamyfzmt.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jiagoushi.top/Article/details/gtkhgbailb.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.vqdsnc.cn/Article/details/gtmbdcncla.html

Java: enum Color { RED, GREEN }
来源：http://dali.xinyue.icu/Article/details/gtibyklxul.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtonmfiwvv.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yanxiufei.cn/Article/details/gtxcikltvl.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhengqikj.top/Article/details/gtgiwyaxew.html

[G16] 对象转数组 / 字典
来源：http://dali.dashuyun.cn/Article/details/gtukgeqyrp.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.chenlongwang.top/Article/details/gtkdibvxmu.html

PHP:  get_object_vars($obj);
来源：http://dali.yangfankeji.com/Article/details/gthzriuiwh.html

JS:   Object.entries(obj)
来源：http://dali.jianghu66.top/Article/details/gtjebqwvua.html

TS:   Object.entries(obj)
来源：http://dali.gzhubu.top/Article/details/gtuhmcyrqu.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.xinyue.icu/Article/details/gtfjmhkxnd.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.9152youxi.cn/Article/details/gtwxlfgiyz.html

Ruby: obj.instance_variables
来源：http://dali.hnxiangtu.top/Article/details/gtmzfaclbi.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhiwuduotai.top/Article/details/gtfwdmulve.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtngcyaoaw.html

H. 异常与错误处理
来源：http://dali.pengpengdd.cyou/Article/details/gtnnwjjxvt.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtnkcmfocu.html

[H01] try / catch 基础
来源：http://dali.wangdashe.top/Article/details/gtczrnnlrv.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.gaohongyu789.top/Article/details/gtgpqdtubs.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.daria6918.cn/Article/details/gtgphgsyjf.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.quarkkingdee.top/Article/details/gtptmghdau.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yj20258.top/Article/details/gtmtajbogc.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.xuanzx.com/Article/details/gtjdbnwrva.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yj20258.top/Article/details/gtvvlsddys.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.daria6918.cn/Article/details/gtrlwyhtlz.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jqgufenzy.top/Article/details/gtiwkzfibx.html

[H02] finally / ensure 收尾
来源：http://dali.hammf.cn/Article/details/gtjicarxbh.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.tanke756.top/Article/details/gtxdxdjzxh.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.dianchejie.cn/Article/details/gtjdnxqvzj.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhixingplan.top/Article/details/gtrijwvays.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.pengpengdd.cyou/Article/details/gtyjlyzfwx.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.tianlin.xyz/Article/details/gtjlognwgs.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.aizwys.cn/Article/details/gtymyercvc.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtilhswnwd.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.gogol.net.cn/Article/details/gtsmujwyag.html

[H03] 主动抛出异常
来源：http://dali.pycfn.com/Article/details/gtrzhxqspm.html

Py:   raise ValueError("错误信息")
来源：http://dali.gotoacloud.top/Article/details/gtcubtwlhn.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.cucudq.cn/Article/details/gtslmbdqov.html

JS:   throw new Error("错误信息");
来源：http://dali.sysykeji.top/Article/details/gtyadstxhy.html

TS:   throw new Error("错误信息");
来源：http://dali.pycfn.com/Article/details/gtnenqxemm.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jinqigfzy.top/Article/details/gtflpyhrvp.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.316326.xyz/Article/details/gtrlzcqtco.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.pengpengdd.cyou/Article/details/gtpsfnykye.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.feifeiyinyue.top/Article/details/gtnrsvzqnw.html

[H04] 自定义异常类型
来源：http://dali.yj20258.top/Article/details/gtpfxvmprm.html

Py:   class MyError(Exception): pass
来源：http://dali.316326.xyz/Article/details/gtuhnqmfbo.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yanxiufei.cn/Article/details/gtdlfswphr.html

JS:   class MyError extends Error {}
来源：http://dali.fzhhl.top/Article/details/gtemwihxlz.html

TS:   class MyError extends Error {}
来源：http://dali.gogol.net.cn/Article/details/gthgeutqlt.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhongyouzk.top/Article/details/gttuvcrnnj.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.sufxvd.cn/Article/details/gtgqzeocxb.html

Ruby: class MyError < StandardError; end
来源：http://dali.yj20258888.top/Article/details/gtgyrfpuln.html

C#:   class MyException : Exception {}
来源：http://dali.dashuyun.cn/Article/details/gtkqabkocw.html

[H05] 捕获特定类型
来源：http://dali.yanxiufei.cn/Article/details/gtdcyopiyi.html

Py:   except ValueError as e:
来源：http://dali.gzhubu.top/Article/details/gtsjsmqbes.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yuanzhike.top/Article/details/gtlwxmelux.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.fzhhl.top/Article/details/gtxlvasyzo.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.tanke756.top/Article/details/gtizuhkecj.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.316326.xyz/Article/details/gtnmzqcpvi.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.shzxlz.cn/Article/details/gtqrmislit.html

Ruby: rescue ArgumentError => e
来源：http://dali.hnqzz.top/Article/details/gtdrfhwhgr.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.tianlin.xyz/Article/details/gtlhezvwnh.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jiagoushi.top/Article/details/gtbapecdrj.html

Py:   value = d.get("k") or default
来源：http://dali.guowangkeji.top/Article/details/gtxemeacso.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.quarkkingdee.top/Article/details/gtbfjdfgmf.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yj20258888.top/Article/details/gtsbpgjkxf.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zycfv.cn/Article/details/gtibcwybzy.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yuxming.cn/Article/details/gtqblvtbgy.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.0kj1m.cn/Article/details/gthtmebtch.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhiwuduotai.top/Article/details/gtbhycqjan.html

C#:   obj?.A?.B ?? default
来源：http://dali.xylfe.cn/Article/details/gtgsbvhixj.html

[H07] 断言
来源：http://dali.chenjidiqi.icu/Article/details/gtoeprrona.html

Py:   assert x > 0, "必须为正"
来源：http://dali.shanyushiyangtech.top/Article/details/gtuheelkyn.html

PHP:  assert($x > 0);
来源：http://dali.jqgufenzy.top/Article/details/gtlciihwmd.html

JS:   console.assert(x > 0);
来源：http://dali.jyoumei.cn/Article/details/gtwdkfhnqj.html

TS:   console.assert(x > 0);
来源：http://dali.haohaochexian.top/Article/details/gtgmcwxonh.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yonumen.top/Article/details/gtmzozwmph.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.shuidangran.top/Article/details/gtvedzjhpj.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jinghuilouyu.cn/Article/details/gtbkwjaeph.html

C#:   Debug.Assert(x > 0);
来源：http://dali.0kj1m.cn/Article/details/gtjnzuouzv.html

[H08] 获取错误信息与堆栈
来源：http://dali.bjfxy.top/Article/details/gthhyihigu.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.gaohongyu789.top/Article/details/gtcqywpwur.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.cucudq.cn/Article/details/gthmnhdyns.html

JS:   e.message;  e.stack
来源：http://dali.ivvv.top/Article/details/gtgyfwhgxt.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.zhoulong.xyz/Article/details/gtfeimqqhb.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.nanxinkj.top/Article/details/gtlviyabuk.html

Go:   err.Error()
来源：http://dali.kuanghao11.cn/Article/details/gthiviwnlq.html

Ruby: e.message;  e.backtrace
来源：http://dali.ehwqpu.com/Article/details/gtudieqlkx.html

C#:   e.Message;  e.StackTrace
来源：http://dali.ybcxt.top/Article/details/gtuwujjgse.html

[H09] 带错误码的异常
来源：http://dali.zhijiandao.cn/Article/details/gttooozsww.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.gogol.net.cn/Article/details/gtowiswrjb.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.fengsongda.top/Article/details/gtbogbbola.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.ydzc1.top/Article/details/gtwedodykl.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.dashuyun.cn/Article/details/gtsgrpocwv.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtypwioino.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.shzxlz.cn/Article/details/gttdygnsde.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.shuidangran.top/Article/details/gtnewviqnu.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.hammf.cn/Article/details/gthbbieaxq.html

[H10] 资源自动释放
来源：http://dali.cucudq.cn/Article/details/gtgvrcnzld.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.dashuyun.cn/Article/details/gttmoxoofg.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.smart0.xyz/Article/details/gtsbaitapj.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.guannengcc.top/Article/details/gtektbvfkm.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.bjfxy.top/Article/details/gtdcxxkcht.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.dianchejie.cn/Article/details/gtrtbrqtfh.html

Go:   defer f.Close()
来源：http://dali.yonumen.top/Article/details/gtjjwmryev.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.pycfn.com/Article/details/gtqwjtazwv.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.jianghu66.top/Article/details/gteuwkpyzg.html


<!-- 参考信息 -->