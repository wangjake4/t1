代发 wailian999

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jqgfzy.top/Article/details/gt2xvwqqxak.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.ydzc1.top/Article/details/gt2yekwyoxc.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.daxiang520.top/Article/details/gt2vhzsnche.html

[F08] 遍历目录
来源：http://dali.cucudq.cn/Article/details/gt2ocxxrrdr.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.daxiang520.top/Article/details/gt2zcqdqplf.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zycfv.cn/Article/details/gt2dlnrrfmn.html

JS:   fs.readdirSync("dir")
来源：http://dali.sysykeji.top/Article/details/gt2hemqgvgr.html

TS:   fs.readdirSync("dir")
来源：http://dali.aizwys.cn/Article/details/gt2ujyohtrm.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhengqikj.top/Article/details/gt2qnnnstxv.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yuxming.cn/Article/details/gt2bkpjsegc.html

Ruby: Dir.children("dir")
来源：http://dali.jyoumei.cn/Article/details/gt2aqwktbtm.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yuanzhike.top/Article/details/gt2dyigfprd.html

[F09] 获取文件大小
来源：http://dali.shzxlz.cn/Article/details/gt2pmhmmaan.html

Py:   os.path.getsize("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2wmxihzfp.html

PHP:  filesize("a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gt2apihtkws.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhixingplan.top/Article/details/gt2vgrqdnhw.html

TS:   fs.statSync("a.txt").size
来源：http://dali.hnqzz.top/Article/details/gt2yxnbezez.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.cqqwz.cn/Article/details/gt2oheborpl.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.ppjwa.cn/Article/details/gt2fatwtern.html

Ruby: File.size("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2vdsmqhdj.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jqgufenzy.top/Article/details/gt2bugkolus.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.cdnleiting.top/Article/details/gt2ikzcvikj.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2xrsqmadq.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.cucudq.cn/Article/details/gt2xlzhydao.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.ydzc1.top/Article/details/gt2mcfgspio.html

TS:   path.extname("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gt2fkmxqpoe.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hammf.cn/Article/details/gt2joairakl.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.gzhubu.top/Article/details/gt2cubtheix.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.meibo888.top/Article/details/gt2mywtxzqm.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2zbomxvlu.html

[F11] 复制与移动文件
来源：http://dali.wangshuangyany.cn/Article/details/gt2afsyfinr.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2kagirabx.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhoulong.xyz/Article/details/gt2lonrqnju.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ehwqpu.com/Article/details/gt2huzjqkfs.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2ljxgsbym.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.cashguo.top/Article/details/gt2chjsimmp.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ehwqpu.com/Article/details/gt2bwbqfvji.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jinqigufen.top/Article/details/gt2ehfzmiqq.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.hnqzz.top/Article/details/gt2zdnlndca.html

[F12] CSV 读写
来源：http://dali.wangshuangyany.cn/Article/details/gt2qfnvothi.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.nwbrower.top/Article/details/gt2ggdqdpez.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.wangshuangyany.cn/Article/details/gt2vrjqoxvl.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jqgfzy.top/Article/details/gt2ebbmptsk.html

TS:   // 同上
来源：http://dali.aibaodan.cn/Article/details/gt2zzdxumev.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.tianlin.xyz/Article/details/gt2npnrnjyi.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hywenlv.cn/Article/details/gt2nepqmbet.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jqgufenzy.top/Article/details/gt2ntzvshie.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.iojbl.cn/Article/details/gt2hafkgvcl.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dswfolzj.html

G. 面向对象
来源：http://dali.jqgufenzy.top/Article/details/gt2qwoxvtmp.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2ydpxjvqb.html

[G01] 定义类
来源：http://dali.zhengqikj.top/Article/details/gt2khzvgpoz.html

Py:   class User: pass
来源：http://dali.hysaishi.cn/Article/details/gt2mdoqauoq.html

PHP:  class User {}
来源：http://dali.9152youxi.cn/Article/details/gt2usltcqoc.html

JS:   class User {}
来源：http://dali.jqgufenzy.top/Article/details/gt2ozvcgrkn.html

TS:   class User { name: string = ""; }
来源：http://dali.gotoacloud.top/Article/details/gt2xrhyryab.html

Java: class User {}
来源：http://dali.hnqzz.top/Article/details/gt2moywklwj.html

Go:   type User struct { Name string }
来源：http://dali.cdnleiting.top/Article/details/gt2enxyvjpx.html

Ruby: class User; end
来源：http://dali.yanxiufei.cn/Article/details/gt2ddceyfnk.html

C#:   class User {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2rnmzvrvw.html

[G02] 构造函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wdjauvay.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.feifeiyinyue.top/Article/details/gt2bokyyrmt.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.sysykeji.top/Article/details/gt2cediiaqx.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ybcxt.top/Article/details/gt2tzquiaaj.html

TS:   constructor(public name: string) {}
来源：http://dali.yongpay.top/Article/details/gt2zizdrwps.html

Java: User(String name) { this.name = name; }
来源：http://dali.jqgufenzy.top/Article/details/gt2owcnoqzp.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.fzhhl.top/Article/details/gt2yajlnmin.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hfpthk.cn/Article/details/gt2hmjyklia.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhoulong.xyz/Article/details/gt2jfiaupst.html

[G03] 实例属性
来源：http://dali.hfpthk.cn/Article/details/gt2adcuibsk.html

Py:   self.name = "x"
来源：http://dali.hfpthk.cn/Article/details/gt2bhrxfchl.html

PHP:  public string $name = "x";
来源：http://dali.havefunace.top/Article/details/gt2hdsyqozx.html

JS:   this.name = "x";
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hutofvlq.html

TS:   name: string = "x";
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ovcaqcmf.html

Java: private String name;
来源：http://dali.birdmap.top/Article/details/gt2zqzzwcnv.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hnxiangtu.top/Article/details/gt2oyfhkztr.html

Ruby: @name = "x"
来源：http://dali.smart0.xyz/Article/details/gt2kfetvtxj.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.nanxuanxn.top/Article/details/gt2aizlfbmv.html

[G04] 定义方法
来源：http://dali.smart0.xyz/Article/details/gt2kgejgtvd.html

Py:   def greet(self): return self.name
来源：http://dali.ivvv.top/Article/details/gt2bcygqhxq.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.tanke756.top/Article/details/gt2isgrkish.html

JS:   greet() { return this.name; }
来源：http://dali.jianghu66.top/Article/details/gt2jokuukqw.html

TS:   greet(): string { return this.name; }
来源：http://dali.guannengcc.top/Article/details/gt2nofgtumh.html

Java: String greet() { return name; }
来源：http://dali.yongpay.top/Article/details/gt2tsrdqtzz.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qwwyytee.html

Ruby: def greet; @name; end
来源：http://dali.ydzc1.top/Article/details/gt2purqnfkx.html

C#:   public string Greet() => Name;
来源：http://dali.kuanghao11.cn/Article/details/gt2ejxloiui.html

[G05] 继承
来源：http://dali.jqgufenzy.top/Article/details/gt2sylumekk.html

Py:   class Admin(User): pass
来源：http://dali.hnxiangtu.top/Article/details/gt2otvgytgc.html

PHP:  class Admin extends User {}
来源：http://dali.yanxiufei.cn/Article/details/gt2fcragkof.html

JS:   class Admin extends User {}
来源：http://dali.svipenyu.cn/Article/details/gt2juarrjtu.html

TS:   class Admin extends User {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2vffldxad.html

Java: class Admin extends User {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qmzsvegp.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hongshengwenyu.top/Article/details/gt2elfzcddz.html

Ruby: class Admin < User; end
来源：http://dali.havefunace.top/Article/details/gt2mcnknhyh.html

C#:   class Admin : User {}
来源：http://dali.hnxiangtu.top/Article/details/gt2khpgydpq.html

[G06] 重写方法
来源：http://dali.smart0.xyz/Article/details/gt2iaeifhqg.html

Py:   def greet(self): return "admin"
来源：http://dali.yj202588.top/Article/details/gt2eybwizqw.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.mhx1999.top/Article/details/gt2iwqbpmne.html

JS:   greet() { return "admin"; }
来源：http://dali.meibo888.top/Article/details/gt2gjkgzqww.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2oynhokzu.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yuanzhike.top/Article/details/gt2tkiesbds.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.cashguo.top/Article/details/gt2emdjvtka.html

Ruby: def greet; "admin"; end
来源：http://dali.birdmap.top/Article/details/gt2dvmvnyrg.html

C#:   public override string Greet() => "admin";
来源：http://dali.yongpay.top/Article/details/gt2vzubtqsh.html

[G07] 调用父类方法
来源：http://dali.snrcjt.cn/Article/details/gt2bdlwlvzo.html

Py:   super().greet()
来源：http://dali.zhengqikj.top/Article/details/gt2avgdqhtl.html

PHP:  parent::greet();
来源：http://dali.haohaochexian.top/Article/details/gt2huvkecqh.html

JS:   super.greet();
来源：http://dali.gotoacloud.top/Article/details/gt2bwdwiwsv.html

TS:   super.greet();
来源：http://dali.vqdsnc.cn/Article/details/gt2ikfkiazo.html

Java: super.greet();
来源：http://dali.sweek.top/Article/details/gt2zzmuvkjg.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.bjfxy.top/Article/details/gt2hsnnaihl.html

Ruby: super
来源：http://dali.jinqigufen.top/Article/details/gt2fryllqye.html

C#:   base.Greet();
来源：http://dali.gogol.net.cn/Article/details/gt2fuztfdfd.html

[G08] 静态方法与属性
来源：http://dali.shangyingyoupin.top/Article/details/gt2nvbvaphc.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.nanxuanxn.top/Article/details/gt2nfzbjvns.html

PHP:  public static function f() {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pgfykonr.html

JS:   static f() {}
来源：http://dali.chenlongwang.top/Article/details/gt2hjgemakf.html

TS:   static f(): void {}
来源：http://dali.daxiang520.top/Article/details/gt2zrqpwsnn.html

Java: static void f() {}
来源：http://dali.ydzc1.top/Article/details/gt2ccnqvwss.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hammf.cn/Article/details/gt2bswazypb.html

Ruby: def self.f; end
来源：http://dali.316326.xyz/Article/details/gt2ibxskknf.html

C#:   public static void F() {}
来源：http://dali.mhx1999.top/Article/details/gt2uyglxoqu.html

[G09] 接口 / 抽象类
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ckarqljt.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhoulong.xyz/Article/details/gt2pdvajjra.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2dftcqqbv.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hfpthk.cn/Article/details/gt2ymdgnjzh.html

TS:   interface Shape { area(): number; }
来源：http://dali.vqdsnc.cn/Article/details/gt2fbbxnkio.html

Java: interface Shape { double area(); }
来源：http://dali.9152youxi.cn/Article/details/gt2qlsaxwqo.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.ppjwa.cn/Article/details/gt2visfdadg.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.ehwqpu.com/Article/details/gt2adujujvv.html

C#:   interface IShape { double Area(); }
来源：http://dali.hfpthk.cn/Article/details/gt2nbufzgio.html

[G10] 访问控制
来源：http://dali.cucudq.cn/Article/details/gt2faejvqmk.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.iojbl.cn/Article/details/gt2vtuepvbl.html

PHP:  public / protected / private
来源：http://dali.chenzaomai.com/Article/details/gt2dblvfzxe.html

JS:   #private 字段；其余公开
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pcmwknpl.html

TS:   public / protected / private
来源：http://dali.ehwqpu.com/Article/details/gt2vbgbbofx.html

Java: public / protected / private / 默认包级
来源：http://dali.ppjwa.cn/Article/details/gt2dwzujmsz.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jinqigufen.top/Article/details/gt2ntjyxhzj.html

Ruby: public / protected / private
来源：http://dali.c1oappe.top/Article/details/gt2wiobgnwx.html

C#:   public / protected / private / internal
来源：http://dali.gaohongyu789.top/Article/details/gt2qdaaltck.html

[G11] getter / setter
来源：http://dali.c1oappe.top/Article/details/gt2hespfrbh.html

Py:   @property 与 @x.setter
来源：http://dali.jinqigfzy.top/Article/details/gt2brvbltku.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2efpaizcm.html

JS:   get name() { return this._name; }
来源：http://dali.ydzc1.top/Article/details/gt2xrzchznb.html

TS:   get name(): string { return this._name; }
来源：http://dali.xinyue.icu/Article/details/gt2ckmyxpnu.html

Java: public String getName() { return name; }
来源：http://dali.zhengqikj.top/Article/details/gt2gimpiixr.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.hnxiangtu.top/Article/details/gt2vsrqhxce.html

Ruby: attr_accessor :name
来源：http://dali.cqqwz.cn/Article/details/gt2wepedzlc.html

C#:   public string Name { get; set; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2thjklzbe.html

[G12] 对象转字符串
来源：http://dali.fzhhl.top/Article/details/gt2gxnmzvas.html

Py:   def __str__(self): return self.name
来源：http://dali.cdnleiting.top/Article/details/gt2hvvlijbt.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.c1oappe.top/Article/details/gt2hnvztgzh.html

JS:   toString() { return this.name; }
来源：http://dali.yj20258888.top/Article/details/gt2qjlyegim.html

TS:   toString(): string { return this.name; }
来源：http://dali.hfpthk.cn/Article/details/gt2flafwvga.html

Java: @Override public String toString() { return name; }
来源：http://dali.jinqigfzy.top/Article/details/gt2mmkfynqt.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.tian-w.cn/Article/details/gt2wdnppfkh.html

Ruby: def to_s; @name; end
来源：http://dali.mhx1999.top/Article/details/gt2jmxgsgdb.html

C#:   public override string ToString() => Name;
来源：http://dali.guowangkeji.top/Article/details/gt2vrbtzstp.html

[G13] 判断对象类型
来源：http://dali.nwbrower.top/Article/details/gt2vafoagms.html

Py:   isinstance(u, User)
来源：http://dali.guannengcc.top/Article/details/gt2cyfhcvxp.html

PHP:  $u instanceof User
来源：http://dali.bjfxy.top/Article/details/gt2eavapdam.html

JS:   u instanceof User
来源：http://dali.redwolf501.top/Article/details/gt2rfwfzntc.html

TS:   u instanceof User
来源：http://dali.ybcxt.top/Article/details/gt2llqhqiez.html

Java: u instanceof User
来源：http://dali.cheryme.top/Article/details/gt2wnjgcwfz.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.pengpengdd.cyou/Article/details/gt2tcykeeps.html

Ruby: u.is_a?(User)
来源：http://dali.zhongyouzk.top/Article/details/gt2vaovvuqn.html

C#:   u is User
来源：http://dali.gogol.net.cn/Article/details/gt2dtzoqmkv.html

[G14] 数据类 / record
来源：http://dali.shzxlz.cn/Article/details/gt2bswklsuh.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.chenzaomai.com/Article/details/gt2odvqvzbx.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.mhx1999.top/Article/details/gt2wboughld.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhijiandao.cn/Article/details/gt2zasmbnit.html

TS:   type User = { name: string; age: number };
来源：http://dali.chenzaomai.com/Article/details/gt2vrizelwr.html

Java: record User(String name, int age) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kkmjbpcm.html

Go:   type User struct { Name string; Age int }
来源：http://dali.ppjwa.cn/Article/details/gt2ltyteqry.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zdqjudy.top/Article/details/gt2uawtcheo.html

C#:   record User(string Name, int Age);
来源：http://dali.yongpay.top/Article/details/gt2abdxhxpw.html

[G15] 枚举
来源：http://dali.zhiwuduotai.top/Article/details/gt2rbfruxtg.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.chenjidiqi.icu/Article/details/gt2cyvcwtit.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2awjnbwfh.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yuxming.cn/Article/details/gt2uedwjewf.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hongshengwenyu.top/Article/details/gt2zfvsgorf.html

Java: enum Color { RED, GREEN }
来源：http://dali.pengpengdd.cyou/Article/details/gt2ogutzebx.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.0kj1m.cn/Article/details/gt2pbrdwygu.html

Ruby: Color = %i[red green].freeze
来源：http://dali.cashguo.top/Article/details/gt2yjnsvojt.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jlsjyb.cn/Article/details/gt2okwrrolt.html

[G16] 对象转数组 / 字典
来源：http://dali.gaohongyu789.top/Article/details/gt2qqwktfck.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.xuetiantiany.cn/Article/details/gt2ekmnyaig.html

PHP:  get_object_vars($obj);
来源：http://dali.cheryme.top/Article/details/gt2zmogyqmw.html

JS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2tnoadifo.html

TS:   Object.entries(obj)
来源：http://dali.yueranfly.top/Article/details/gt2cqywfdtm.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.nanxinkj.top/Article/details/gt2idwcjjjx.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhijiandao.cn/Article/details/gt2flhixzlc.html

Ruby: obj.instance_variables
来源：http://dali.jqgufenzy.top/Article/details/gt2lwkhnger.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hongshengwenyu.top/Article/details/gt2efnpecpe.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2sxahbtvz.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2urvoddcr.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2oigswzpz.html

[H01] try / catch 基础
来源：http://dali.xinyue.icu/Article/details/gt2sgvtcemo.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.bjfxy.top/Article/details/gt2xxqkjudy.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.cdnleiting.top/Article/details/gt2bevbbrnw.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2afnvqraw.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2zycgnolv.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhengqikj.top/Article/details/gt2wmktmlli.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.redwolf501.top/Article/details/gt2bogrnllf.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.chenjidiqi.icu/Article/details/gt2qwqfuliq.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.aizwys.cn/Article/details/gt2uaghtlze.html

[H02] finally / ensure 收尾
来源：http://dali.hnqzz.top/Article/details/gt2kfpncpjj.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.cdnleiting.top/Article/details/gt2vkmnrkah.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jqgfzy.top/Article/details/gt2bsvgpxfi.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jianghu66.top/Article/details/gt2tvsvgpte.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.0kj1m.cn/Article/details/gt2xgjxrfrv.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yuxming.cn/Article/details/gt2irpfkxnk.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.chenjidiqi.icu/Article/details/gt2auckkcra.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.cheryme.top/Article/details/gt2hjyetxyg.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vzlmqokc.html

[H03] 主动抛出异常
来源：http://dali.jyoumei.cn/Article/details/gt2uzekdxpa.html

Py:   raise ValueError("错误信息")
来源：http://dali.yanxiufei.cn/Article/details/gt2hyifzqpw.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yvedp.cn/Article/details/gt2gipzuwsx.html

JS:   throw new Error("错误信息");
来源：http://dali.hammf.cn/Article/details/gt2vjtnnevw.html

TS:   throw new Error("错误信息");
来源：http://dali.jinqigufen.top/Article/details/gt2wwgsozyp.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hywenlv.cn/Article/details/gt2uxvbwqfh.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.bjfxy.top/Article/details/gt2zqlbcppa.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.quarkkingdee.top/Article/details/gt2omkqaiuv.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jqgfzy.top/Article/details/gt2xgrifntd.html

[H04] 自定义异常类型
来源：http://dali.jqgfzy.top/Article/details/gt2fjhwcbmr.html

Py:   class MyError(Exception): pass
来源：http://dali.svipenyu.cn/Article/details/gt2hxbltnhp.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.tanke756.top/Article/details/gt2vnpkhjjx.html

JS:   class MyError extends Error {}
来源：http://dali.jqgufenzy.top/Article/details/gt2acjbutcl.html

TS:   class MyError extends Error {}
来源：http://dali.shuidangran.top/Article/details/gt2upavrvib.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yanxiufei.cn/Article/details/gt2ahonkigf.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.cqqwz.cn/Article/details/gt2ikdnusrs.html

Ruby: class MyError < StandardError; end
来源：http://dali.fengsongda.top/Article/details/gt2hkhjafuy.html

C#:   class MyException : Exception {}
来源：http://dali.gaohongyu789.top/Article/details/gt2tpbohpnj.html

[H05] 捕获特定类型
来源：http://dali.shuidangran.top/Article/details/gt2dtcwygms.html

Py:   except ValueError as e:
来源：http://dali.daria6918.cn/Article/details/gt2ozrrjwru.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.havefunace.top/Article/details/gt2itapxpyp.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jiagoushi.top/Article/details/gt2vakiitqu.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.xziqi.cn/Article/details/gt2vbnbcagq.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.haohaochexian.top/Article/details/gt2datzyfas.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.aibaodan.cn/Article/details/gt2wewaqqjq.html

Ruby: rescue ArgumentError => e
来源：http://dali.jqgufenzy.top/Article/details/gt2nrcdceog.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.316326.xyz/Article/details/gt2wtyjquqa.html

[H06] 可选值 / 空值安全访问
来源：http://dali.sweek.top/Article/details/gt2guqiveaa.html

Py:   value = d.get("k") or default
来源：http://dali.jlsjyb.cn/Article/details/gt2ftphnzgw.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hnxiangtu.top/Article/details/gt2pzlyjfnu.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hidkgfmy.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.chenzaomai.com/Article/details/gt2gkoncwcv.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhengqikj.top/Article/details/gt2xumpagmz.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhongyouzk.top/Article/details/gt2ybwhzdcg.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jinqigufen.top/Article/details/gt2zfmzbzsi.html

C#:   obj?.A?.B ?? default
来源：http://dali.yj202588.top/Article/details/gt2ecorgmtk.html

[H07] 断言
来源：http://dali.ehwqpu.com/Article/details/gt2idfnovqj.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zdqjudy.top/Article/details/gt2rqlguuqi.html

PHP:  assert($x > 0);
来源：http://dali.snrcjt.cn/Article/details/gt2tlmwsoan.html

JS:   console.assert(x > 0);
来源：http://dali.bjfxy.top/Article/details/gt2dbtnlsly.html

TS:   console.assert(x > 0);
来源：http://dali.jinqigufen.top/Article/details/gt2ecctqbig.html

Java: assert x > 0 : "必须为正";
来源：http://dali.fzhhl.top/Article/details/gt2ivcxxjsw.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.zhiwuduotai.top/Article/details/gt2mjssevdv.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jinqigufen.top/Article/details/gt2ekcqbmes.html

C#:   Debug.Assert(x > 0);
来源：http://dali.316326.xyz/Article/details/gt2hcaoqiqr.html

[H08] 获取错误信息与堆栈
来源：http://dali.dashuyun.cn/Article/details/gt2qfhoztih.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhoulong.xyz/Article/details/gt2lzanepsx.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.guowangkeji.top/Article/details/gt2uigktaus.html

JS:   e.message;  e.stack
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ykljpowd.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.dashuyun.cn/Article/details/gt2vxuvusco.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.xuanzx.com/Article/details/gt2gtnlkigv.html

Go:   err.Error()
来源：http://dali.kuanghao11.cn/Article/details/gt2yakktnco.html

Ruby: e.message;  e.backtrace
来源：http://dali.aibaodan.cn/Article/details/gt2ccetxgyq.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhongyouzk.top/Article/details/gt2vcprrkyt.html

[H09] 带错误码的异常
来源：http://dali.yanxiufei.cn/Article/details/gt2tcuvhnqd.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.jiagoushi.top/Article/details/gt2owotoxau.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.wangdashe.top/Article/details/gt2ldzhvyiq.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.vqdsnc.cn/Article/details/gt2gsuanqyz.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.xinyue.icu/Article/details/gt2ppjfzfsq.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zycfv.cn/Article/details/gt2dfjnqezp.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhongyouzk.top/Article/details/gt2aokqucme.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.vqdsnc.cn/Article/details/gt2imdxmymh.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jinqigufen.top/Article/details/gt2kurqxwcs.html

[H10] 资源自动释放
来源：http://dali.shuidangran.top/Article/details/gt2ythaxlla.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.ppjwa.cn/Article/details/gt2gzemgrfq.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zhoulong.xyz/Article/details/gt2mfmnqjyh.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yonumen.top/Article/details/gt2iwrjzrok.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jiagoushi.top/Article/details/gt2ogtqwzmc.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.sysykeji.top/Article/details/gt2umjepbpk.html

Go:   defer f.Close()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vujzisqw.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.hnxiangtu.top/Article/details/gt2okurkzyp.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gt2hhokgseb.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2bbrgryra.html

I. 正则表达式
来源：http://dali.xylfe.cn/Article/details/gt2mokwemno.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2rjefjmud.html

[I01] 判断是否匹配
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oulnwlvu.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2nfkhvdir.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.yj202588.top/Article/details/gt2kpwmkxbg.html

JS:   /\d+/.test(s)
来源：http://dali.0kj1m.cn/Article/details/gt2dtpgdoph.html

TS:   /\d+/.test(s)
来源：http://dali.jinqigfzy.top/Article/details/gt2jwmpvbqn.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.jyoumei.cn/Article/details/gt2pxwjfynw.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.daxiang520.top/Article/details/gt2gsgwddyf.html

Ruby: s.match?(/\d+/)
来源：http://dali.c1oappe.top/Article/details/gt2alydrxvg.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.wangdashe.top/Article/details/gt2ajdirrbd.html


<!-- 参考信息 -->