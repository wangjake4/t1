代发 wailian999

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.redwolf501.top/Article/details/gt2hztjymwc.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhongyouzk.top/Article/details/gt2nwpjprpf.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.9152youxi.cn/Article/details/gt2rmmcnrir.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.birdmap.top/Article/details/gt2sakdcbro.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.birdmap.top/Article/details/gt2yxlmfxqn.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.snrcjt.cn/Article/details/gt2jutmmydm.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.ppjwa.cn/Article/details/gt2pxhfhzgy.html

[F08] 遍历目录
来源：http://dali.hnxiangtu.top/Article/details/gt2rxgkrgic.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.guowangkeji.top/Article/details/gt2mpebfcfd.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.guowangkeji.top/Article/details/gt2kuzwsulx.html

JS:   fs.readdirSync("dir")
来源：http://dali.jinqigufen.top/Article/details/gt2gqzdsggi.html

TS:   fs.readdirSync("dir")
来源：http://dali.yvedp.cn/Article/details/gt2iqjbezqp.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.fzhhl.top/Article/details/gt2kmccukei.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.sxryk.cn/Article/details/gt2btqhisid.html

Ruby: Dir.children("dir")
来源：http://dali.wangdashe.top/Article/details/gt2zyjgftls.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yangfankeji.com/Article/details/gt2xyvukczb.html

[F09] 获取文件大小
来源：http://dali.cheryme.top/Article/details/gt2bjkzwenx.html

Py:   os.path.getsize("a.txt")
来源：http://dali.wangdashe.top/Article/details/gt2optxsneg.html

PHP:  filesize("a.txt");
来源：http://dali.andypj.xyz/Article/details/gt2xppycsxn.html

JS:   fs.statSync("a.txt").size
来源：http://dali.nanxinkj.top/Article/details/gt2powtwsic.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kagzsfha.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.cheryme.top/Article/details/gt2ralcfisw.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhoulong.xyz/Article/details/gt2ggtszcmz.html

Ruby: File.size("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2inigbcdw.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jlsjyb.cn/Article/details/gt2itlxpltg.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vkvvprae.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.xziqi.cn/Article/details/gt2sdelfniw.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.chenzaomai.com/Article/details/gt2uxpxvbuk.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.wangdashe.top/Article/details/gt2gojqrwxd.html

TS:   path.extname("a.txt")
来源：http://dali.ivvv.top/Article/details/gt2gmmojcnl.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.sxryk.cn/Article/details/gt2edhiargw.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gt2mfzxspks.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2pxgfnoux.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.xuanzx.com/Article/details/gt2envpnqjl.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jfbigidb.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.shuidangran.top/Article/details/gt2kcrmznat.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.svipenyu.cn/Article/details/gt2hggkdxdq.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2wytwtpka.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.aizwys.cn/Article/details/gt2cqefqkxg.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jlsjyb.cn/Article/details/gt2otqdcgdv.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.xinyue.icu/Article/details/gt2tlkxbsnn.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.ybcxt.top/Article/details/gt2cjdlcoll.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.daria6918.cn/Article/details/gt2phuscyez.html

[F12] CSV 读写
来源：http://dali.zhongyouzk.top/Article/details/gt2opvevuub.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.nwbrower.top/Article/details/gt2mswzlkci.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.ydzc1.top/Article/details/gt2yxcvvncg.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.gogol.net.cn/Article/details/gt2bjxzdifh.html

TS:   // 同上
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xzlulwsf.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.iojbl.cn/Article/details/gt2lchptvyp.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.quarkkingdee.top/Article/details/gt2sdfxwfev.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yongpay.top/Article/details/gt2tvjvwoql.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jianghu66.top/Article/details/gt2quygyrue.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2cwlrnazr.html

G. 面向对象
来源：http://dali.yuanzhike.top/Article/details/gt2sesoxpzx.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2fhqzwodo.html

[G01] 定义类
来源：http://dali.quarkkingdee.top/Article/details/gt2wrhldrua.html

Py:   class User: pass
来源：http://dali.c1oappe.top/Article/details/gt2eyysfmjk.html

PHP:  class User {}
来源：http://dali.cdnleiting.top/Article/details/gt2fivchopi.html

JS:   class User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jkuidkug.html

TS:   class User { name: string = ""; }
来源：http://dali.cheryme.top/Article/details/gt2wtzasemi.html

Java: class User {}
来源：http://dali.wangdashe.top/Article/details/gt2sxckaown.html

Go:   type User struct { Name string }
来源：http://dali.daxiang520.top/Article/details/gt2pbghjckb.html

Ruby: class User; end
来源：http://dali.yuanzhike.top/Article/details/gt2gpmejapz.html

C#:   class User {}
来源：http://dali.zhoulong.xyz/Article/details/gt2ethakybb.html

[G02] 构造函数
来源：http://dali.andypj.xyz/Article/details/gt2woovqcfb.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.dashuyun.cn/Article/details/gt2cttfoucd.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.quarkkingdee.top/Article/details/gt2dirqvrua.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.redwolf501.top/Article/details/gt2qtaqhruj.html

TS:   constructor(public name: string) {}
来源：http://dali.yj20258888.top/Article/details/gt2bzktwpyg.html

Java: User(String name) { this.name = name; }
来源：http://dali.meibo888.top/Article/details/gt2doqvzhlu.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.svipenyu.cn/Article/details/gt2tyxhejcn.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.tanke756.top/Article/details/gt2rikunemw.html

C#:   public User(string name) { Name = name; }
来源：http://dali.shzxlz.cn/Article/details/gt2vwntbupg.html

[G03] 实例属性
来源：http://dali.guowangkeji.top/Article/details/gt2pmcqpufv.html

Py:   self.name = "x"
来源：http://dali.tianlin.xyz/Article/details/gt2mniacqdt.html

PHP:  public string $name = "x";
来源：http://dali.zdqjudy.top/Article/details/gt2bxmtrsqm.html

JS:   this.name = "x";
来源：http://dali.ydzc1.top/Article/details/gt2jnenuiwm.html

TS:   name: string = "x";
来源：http://dali.hammf.cn/Article/details/gt2ffscapxo.html

Java: private String name;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yyutrnlk.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yanxiufei.cn/Article/details/gt2ezxgrsfw.html

Ruby: @name = "x"
来源：http://dali.gogol.net.cn/Article/details/gt2ihhrmexi.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.vqdsnc.cn/Article/details/gt2yekislrw.html

[G04] 定义方法
来源：http://dali.yonumen.top/Article/details/gt2mdilgbnm.html

Py:   def greet(self): return self.name
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pyemrycy.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yangfankeji.com/Article/details/gt2uhqhgmnh.html

JS:   greet() { return this.name; }
来源：http://dali.chenlongwang.top/Article/details/gt2fgdijubj.html

TS:   greet(): string { return this.name; }
来源：http://dali.yonumen.top/Article/details/gt2vviglcue.html

Java: String greet() { return name; }
来源：http://dali.ybcxt.top/Article/details/gt2rttxpmft.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.c1oappe.top/Article/details/gt2loubbrmp.html

Ruby: def greet; @name; end
来源：http://dali.jianghu66.top/Article/details/gt2etmibxlz.html

C#:   public string Greet() => Name;
来源：http://dali.dashuyun.cn/Article/details/gt2oqckxpls.html

[G05] 继承
来源：http://dali.aibaodan.cn/Article/details/gt2sixrhdjh.html

Py:   class Admin(User): pass
来源：http://dali.nanxuanxn.top/Article/details/gt2tffxcvbo.html

PHP:  class Admin extends User {}
来源：http://dali.dashuyun.cn/Article/details/gt2bzyxbdah.html

JS:   class Admin extends User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yneajrau.html

TS:   class Admin extends User {}
来源：http://dali.sufxvd.cn/Article/details/gt2liddoima.html

Java: class Admin extends User {}
来源：http://dali.yj202588.top/Article/details/gt2hvhkvtyz.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zycfv.cn/Article/details/gt2aqsxoubh.html

Ruby: class Admin < User; end
来源：http://dali.chenjidiqi.icu/Article/details/gt2iayctnas.html

C#:   class Admin : User {}
来源：http://dali.gzhubu.top/Article/details/gt2ovujksoe.html

[G06] 重写方法
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ltjceycg.html

Py:   def greet(self): return "admin"
来源：http://dali.zhoulong.xyz/Article/details/gt2pdbwzshs.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.ppjwa.cn/Article/details/gt2hmqzmjmi.html

JS:   greet() { return "admin"; }
来源：http://dali.guowangkeji.top/Article/details/gt2cgfmvzpj.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2baykfmzi.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jyoumei.cn/Article/details/gt2vqjpfhjn.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.cheryme.top/Article/details/gt2sazxvfyr.html

Ruby: def greet; "admin"; end
来源：http://dali.zhoulong.xyz/Article/details/gt2lefexkks.html

C#:   public override string Greet() => "admin";
来源：http://dali.iojbl.cn/Article/details/gt2cmrxickc.html

[G07] 调用父类方法
来源：http://dali.yj20258.top/Article/details/gt2dhwfcoow.html

Py:   super().greet()
来源：http://dali.quarkkingdee.top/Article/details/gt2byjxgxat.html

PHP:  parent::greet();
来源：http://dali.chenjidiqi.icu/Article/details/gt2mbayduhv.html

JS:   super.greet();
来源：http://dali.xuetiantiany.cn/Article/details/gt2qeiyeneu.html

TS:   super.greet();
来源：http://dali.ydzc1.top/Article/details/gt2jucpnwvg.html

Java: super.greet();
来源：http://dali.daxiang520.top/Article/details/gt2wfmklssw.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.cheryme.top/Article/details/gt2wtadpahz.html

Ruby: super
来源：http://dali.meibo888.top/Article/details/gt2azptrzjx.html

C#:   base.Greet();
来源：http://dali.vqdsnc.cn/Article/details/gt2wnotcwqh.html

[G08] 静态方法与属性
来源：http://dali.jqgfzy.top/Article/details/gt2xglencdy.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yongpay.top/Article/details/gt2ppxoeamb.html

PHP:  public static function f() {}
来源：http://dali.dashuyun.cn/Article/details/gt2qfiyyizs.html

JS:   static f() {}
来源：http://dali.c1oappe.top/Article/details/gt2cjvaerds.html

TS:   static f(): void {}
来源：http://dali.jlsjyb.cn/Article/details/gt2nvetxgzv.html

Java: static void f() {}
来源：http://dali.dianchejie.cn/Article/details/gt2ipqggaiy.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.gogol.net.cn/Article/details/gt2cvhibeeg.html

Ruby: def self.f; end
来源：http://dali.daria6918.cn/Article/details/gt2fxoiadad.html

C#:   public static void F() {}
来源：http://dali.tian-w.cn/Article/details/gt2ldkqwuaq.html

[G09] 接口 / 抽象类
来源：http://dali.jiagoushi.top/Article/details/gt2rwgmsdqi.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jqgufenzy.top/Article/details/gt2fhjjgyyx.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.hnqzz.top/Article/details/gt2mkaucbxv.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jinqigfzy.top/Article/details/gt2qqnwmsqd.html

TS:   interface Shape { area(): number; }
来源：http://dali.aizwys.cn/Article/details/gt2zybtvjes.html

Java: interface Shape { double area(); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2ipnaeqvb.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhongyouzk.top/Article/details/gt2wckkszfk.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.haohaochexian.top/Article/details/gt2cmedsryk.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhengqikj.top/Article/details/gt2xtutjsps.html

[G10] 访问控制
来源：http://dali.jqgfzy.top/Article/details/gt2bikialci.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.cucudq.cn/Article/details/gt2ivusunym.html

PHP:  public / protected / private
来源：http://dali.snrcjt.cn/Article/details/gt2ibfsysps.html

JS:   #private 字段；其余公开
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dklgqcvv.html

TS:   public / protected / private
来源：http://dali.nanxuanxn.top/Article/details/gt2vjeqjjzq.html

Java: public / protected / private / 默认包级
来源：http://dali.cucudq.cn/Article/details/gt2djhkhqek.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yuxming.cn/Article/details/gt2gquhhzso.html

Ruby: public / protected / private
来源：http://dali.c1oappe.top/Article/details/gt2jepigbkd.html

C#:   public / protected / private / internal
来源：http://dali.aizwys.cn/Article/details/gt2egxjktzo.html

[G11] getter / setter
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lfdwoeah.html

Py:   @property 与 @x.setter
来源：http://dali.pengpengdd.cyou/Article/details/gt2wqghyctm.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.dianchejie.cn/Article/details/gt2qceidgjl.html

JS:   get name() { return this._name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wsiizjaf.html

TS:   get name(): string { return this._name; }
来源：http://dali.ehwqpu.com/Article/details/gt2meavkkpa.html

Java: public String getName() { return name; }
来源：http://dali.aizwys.cn/Article/details/gt2rpghphnd.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jyoumei.cn/Article/details/gt2mupkdqvv.html

Ruby: attr_accessor :name
来源：http://dali.birdmap.top/Article/details/gt2iakrstna.html

C#:   public string Name { get; set; }
来源：http://dali.shzxlz.cn/Article/details/gt2jitehune.html

[G12] 对象转字符串
来源：http://dali.zdqjudy.top/Article/details/gt2wjlzjlaj.html

Py:   def __str__(self): return self.name
来源：http://dali.nanxinkj.top/Article/details/gt2oeuqkmxq.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hywenlv.cn/Article/details/gt2cuqjrkqs.html

JS:   toString() { return this.name; }
来源：http://dali.jiagoushi.top/Article/details/gt2xpichnrt.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhixingplan.top/Article/details/gt2lcetggcx.html

Java: @Override public String toString() { return name; }
来源：http://dali.nwbrower.top/Article/details/gt2zxsevwpj.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jqgufenzy.top/Article/details/gt2tmahdmey.html

Ruby: def to_s; @name; end
来源：http://dali.nanxinkj.top/Article/details/gt2uotnqszx.html

C#:   public override string ToString() => Name;
来源：http://dali.svipenyu.cn/Article/details/gt2lelfekde.html

[G13] 判断对象类型
来源：http://dali.xinyue.icu/Article/details/gt2wjuqerxa.html

Py:   isinstance(u, User)
来源：http://dali.sxryk.cn/Article/details/gt2qxavimxw.html

PHP:  $u instanceof User
来源：http://dali.ybcxt.top/Article/details/gt2gldvoape.html

JS:   u instanceof User
来源：http://dali.hfpthk.cn/Article/details/gt2pwchrhbd.html

TS:   u instanceof User
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2edqmtjwl.html

Java: u instanceof User
来源：http://dali.wangdashe.top/Article/details/gt2pajlonth.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.chenlongwang.top/Article/details/gt2bnsperjn.html

Ruby: u.is_a?(User)
来源：http://dali.gotoacloud.top/Article/details/gt2cdcfycxx.html

C#:   u is User
来源：http://dali.yanxiufei.cn/Article/details/gt2vrmdhwgz.html

[G14] 数据类 / record
来源：http://dali.jqgfzy.top/Article/details/gt2payrhcnn.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.cucudq.cn/Article/details/gt2mfsepysr.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.kuanghao11.cn/Article/details/gt2heuunmkm.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yangfankeji.com/Article/details/gt2hhxblxvw.html

TS:   type User = { name: string; age: number };
来源：http://dali.cashguo.top/Article/details/gt2adgnwehi.html

Java: record User(String name, int age) {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2rdeoksos.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jlsjyb.cn/Article/details/gt2qgwvqnqs.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.xuetiantiany.cn/Article/details/gt2tkqoetbg.html

C#:   record User(string Name, int Age);
来源：http://dali.zhongyouzk.top/Article/details/gt2haeqlbuh.html

[G15] 枚举
来源：http://dali.jqgfzy.top/Article/details/gt2sbvclnek.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.ehwqpu.com/Article/details/gt2wowuczfn.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yongpay.top/Article/details/gt2ljrflaou.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.xziqi.cn/Article/details/gt2ekpxwpnn.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhengqikj.top/Article/details/gt2myjhhhla.html

Java: enum Color { RED, GREEN }
来源：http://dali.yanxiufei.cn/Article/details/gt2yutfpeec.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.aibaodan.cn/Article/details/gt2hqtadoxs.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yangfankeji.com/Article/details/gt2aivolxdc.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xziqi.cn/Article/details/gt2qqytwluj.html

[G16] 对象转数组 / 字典
来源：http://dali.pengpengdd.cyou/Article/details/gt2ksezmxku.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mznearjv.html

PHP:  get_object_vars($obj);
来源：http://dali.jqgfzy.top/Article/details/gt2azgwcvqa.html

JS:   Object.entries(obj)
来源：http://dali.9152youxi.cn/Article/details/gt2lxzpeubs.html

TS:   Object.entries(obj)
来源：http://dali.ivvv.top/Article/details/gt2smxgfaaf.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.havefunace.top/Article/details/gt2czaebtjp.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.hongshengwenyu.top/Article/details/gt2eufyupuc.html

Ruby: obj.instance_variables
来源：http://dali.9152youxi.cn/Article/details/gt2ewkwmysu.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.snrcjt.cn/Article/details/gt2xgytbszy.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2lmpxmpjw.html

H. 异常与错误处理
来源：http://dali.jyoumei.cn/Article/details/gt2mpppbuvf.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2tfacayyi.html

[H01] try / catch 基础
来源：http://dali.hnxiangtu.top/Article/details/gt2evdyyprl.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.mhx1999.top/Article/details/gt2tlomqjbg.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.andypj.xyz/Article/details/gt2ldjjfcpo.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhoulong.xyz/Article/details/gt2zyktcnzs.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.svipenyu.cn/Article/details/gt2jhxvqbxc.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.xziqi.cn/Article/details/gt2lrwjshgh.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.dashuyun.cn/Article/details/gt2lptscmjx.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhengqikj.top/Article/details/gt2xelzmwwn.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fixnvcex.html

[H02] finally / ensure 收尾
来源：http://dali.andypj.xyz/Article/details/gt2nemghelp.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.havefunace.top/Article/details/gt2tbtucouy.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.daxiang520.top/Article/details/gt2zddsxqjp.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.birdmap.top/Article/details/gt2hbdlpiso.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.aizwys.cn/Article/details/gt2fnmarrqf.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.nwbrower.top/Article/details/gt2bcghvmdr.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.vqdsnc.cn/Article/details/gt2yjqzhsdz.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yanxiufei.cn/Article/details/gt2ifmfhnul.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2sehibqtt.html

[H03] 主动抛出异常
来源：http://dali.cucudq.cn/Article/details/gt2xyzvdsgt.html

Py:   raise ValueError("错误信息")
来源：http://dali.nanxinkj.top/Article/details/gt2fhnjfjvk.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yuxming.cn/Article/details/gt2owfpqpfw.html

JS:   throw new Error("错误信息");
来源：http://dali.xinyue.icu/Article/details/gt2udrpgutn.html

TS:   throw new Error("错误信息");
来源：http://dali.jianghu66.top/Article/details/gt2qyhkmmir.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.cqqwz.cn/Article/details/gt2veonkqwg.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.cheryme.top/Article/details/gt2odhkxdqo.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gt2lglsliso.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.iojbl.cn/Article/details/gt2jtllufvr.html

[H04] 自定义异常类型
来源：http://dali.xinyue.icu/Article/details/gt2dqeclscl.html

Py:   class MyError(Exception): pass
来源：http://dali.aizwys.cn/Article/details/gt2lvppfjxl.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.fengsongda.top/Article/details/gt2sttrdwju.html

JS:   class MyError extends Error {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2jsefkxcz.html

TS:   class MyError extends Error {}
来源：http://dali.wangdashe.top/Article/details/gt2ixuazjzc.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yuxming.cn/Article/details/gt2thnsfohf.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.9152youxi.cn/Article/details/gt2pgardkfh.html

Ruby: class MyError < StandardError; end
来源：http://dali.hywenlv.cn/Article/details/gt2eqcnrbvk.html

C#:   class MyException : Exception {}
来源：http://dali.yvedp.cn/Article/details/gt2uoripntm.html

[H05] 捕获特定类型
来源：http://dali.sweek.top/Article/details/gt2pbjgolbc.html

Py:   except ValueError as e:
来源：http://dali.daxiang520.top/Article/details/gt2hpctdbuk.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.chenzaomai.com/Article/details/gt2jmzvooui.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2onwsblul.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2tpvsiubz.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jyoumei.cn/Article/details/gt2absvqblm.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.9152youxi.cn/Article/details/gt2sljjpeoi.html

Ruby: rescue ArgumentError => e
来源：http://dali.cashguo.top/Article/details/gt2eajztadg.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jqgfzy.top/Article/details/gt2xkasherk.html

[H06] 可选值 / 空值安全访问
来源：http://dali.shzxlz.cn/Article/details/gt2ocwzkwfn.html

Py:   value = d.get("k") or default
来源：http://dali.yongpay.top/Article/details/gt2ojkpmuml.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yuanzhike.top/Article/details/gt2wgpvqmib.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.nanxuanxn.top/Article/details/gt2ltitdyli.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.guowangkeji.top/Article/details/gt2dxaaadpp.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.gzhubu.top/Article/details/gt2vknztrcv.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yonumen.top/Article/details/gt2hgmbuwtz.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jqgfzy.top/Article/details/gt2xpdodomv.html

C#:   obj?.A?.B ?? default
来源：http://dali.shzxlz.cn/Article/details/gt2qlnjrilb.html

[H07] 断言
来源：http://dali.daria6918.cn/Article/details/gt2pxhzauyx.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tnqghgxq.html

PHP:  assert($x > 0);
来源：http://dali.0kj1m.cn/Article/details/gt2xzrofqru.html

JS:   console.assert(x > 0);
来源：http://dali.yj20258888.top/Article/details/gt2yvpuqaxg.html

TS:   console.assert(x > 0);
来源：http://dali.0kj1m.cn/Article/details/gt2xeblfspq.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jqgfzy.top/Article/details/gt2ejdjrytu.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yj20258.top/Article/details/gt2jpnrgdyh.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yanxiufei.cn/Article/details/gt2wjfwgfqb.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhiwuduotai.top/Article/details/gt2ozixowmz.html

[H08] 获取错误信息与堆栈
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2reocufrt.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.nwbrower.top/Article/details/gt2vwehlrlu.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jlsjyb.cn/Article/details/gt2vlertmov.html

JS:   e.message;  e.stack
来源：http://dali.yueranfly.top/Article/details/gt2bbvuyijw.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.ehwqpu.com/Article/details/gt2bgtpzaii.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.0kj1m.cn/Article/details/gt2irdlbrsl.html

Go:   err.Error()
来源：http://dali.vqdsnc.cn/Article/details/gt2tihlpgsc.html

Ruby: e.message;  e.backtrace
来源：http://dali.jyoumei.cn/Article/details/gt2qpagqnfh.html

C#:   e.Message;  e.StackTrace
来源：http://dali.cheryme.top/Article/details/gt2decbcfvt.html

[H09] 带错误码的异常
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2axokvbft.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.svipenyu.cn/Article/details/gt2lgpbhxac.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.aibaodan.cn/Article/details/gt2jkmnitme.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.havefunace.top/Article/details/gt2djpievwf.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.xuetiantiany.cn/Article/details/gt2pqycuwvg.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2fhvwibye.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.gaohongyu789.top/Article/details/gt2fwjekfss.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.sxryk.cn/Article/details/gt2unbgones.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.pycfn.com/Article/details/gt2xnxnysaq.html

[H10] 资源自动释放
来源：http://dali.kuanghao11.cn/Article/details/gt2lgnbzpjm.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yuxming.cn/Article/details/gt2zbwcozht.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yangfankeji.com/Article/details/gt2ydeurujt.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zycfv.cn/Article/details/gt2jbkutpbv.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.0kj1m.cn/Article/details/gt2ajbkkbbq.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yuanzhike.top/Article/details/gt2fopowvsy.html

Go:   defer f.Close()
来源：http://dali.cdnleiting.top/Article/details/gt2ngugcfjj.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.meibo888.top/Article/details/gt2kfvoxshc.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hnqzz.top/Article/details/gt2menemqvs.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2awncdnhs.html

I. 正则表达式
来源：http://dali.hammf.cn/Article/details/gt2avseawup.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2jkrptwko.html

[I01] 判断是否匹配
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2stlxbwfr.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zycfv.cn/Article/details/gt2mtovuphi.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.iojbl.cn/Article/details/gt2qfhvhiux.html

JS:   /\d+/.test(s)
来源：http://dali.yongpay.top/Article/details/gt2seffrsuk.html

TS:   /\d+/.test(s)
来源：http://dali.xinyue.icu/Article/details/gt2nnhctqiu.html


<!-- 参考信息 -->