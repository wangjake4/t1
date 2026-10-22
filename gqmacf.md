代发 wailian999

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.snrcjt.cn/Article/details/gt2toioelqb.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.chenlongwang.top/Article/details/gt2pmcywrij.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cqqwz.cn/Article/details/gt2hlquohkz.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.ivvv.top/Article/details/gt2yldjmjwq.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.aibaodan.cn/Article/details/gt2psxwsvob.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yj20258888.top/Article/details/gt2fofhuabs.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.haohaochexian.top/Article/details/gt2xatvfewy.html

[F08] 遍历目录
来源：http://dali.redwolf501.top/Article/details/gt2gpbfujyg.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.pycfn.com/Article/details/gt2hpnokfzw.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.birdmap.top/Article/details/gt2aijfusud.html

JS:   fs.readdirSync("dir")
来源：http://dali.sufxvd.cn/Article/details/gt2hchrosyz.html

TS:   fs.readdirSync("dir")
来源：http://dali.sxryk.cn/Article/details/gt2qxczxggc.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jianghu66.top/Article/details/gt2kciubjmm.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.tianlin.xyz/Article/details/gt2qhjjibmo.html

Ruby: Dir.children("dir")
来源：http://dali.guowangkeji.top/Article/details/gt2qgebszmj.html

C#:   Directory.GetFiles("dir")
来源：http://dali.0kj1m.cn/Article/details/gt2gpdnqopv.html

[F09] 获取文件大小
来源：http://dali.gzhubu.top/Article/details/gt2lhhekyni.html

Py:   os.path.getsize("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gt2eijxfdkv.html

PHP:  filesize("a.txt");
来源：http://dali.yvedp.cn/Article/details/gt2omrzolgo.html

JS:   fs.statSync("a.txt").size
来源：http://dali.feifeiyinyue.top/Article/details/gt2lvfwsmul.html

TS:   fs.statSync("a.txt").size
来源：http://dali.nanxinkj.top/Article/details/gt2acdhmdoz.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.xylfe.cn/Article/details/gt2ulurfvnv.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.cqqwz.cn/Article/details/gt2alpwwoev.html

Ruby: File.size("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2czersnlk.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zdqjudy.top/Article/details/gt2fyxpwuwi.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.shuidangran.top/Article/details/gt2warpabqy.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.snrcjt.cn/Article/details/gt2mcazvyfe.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gt2szynypgp.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhixingplan.top/Article/details/gt2btqppcwz.html

TS:   path.extname("a.txt")
来源：http://dali.guannengcc.top/Article/details/gt2rgixzjle.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.kuanghao11.cn/Article/details/gt2zvtzdlcj.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2leeqimqr.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yonumen.top/Article/details/gt2oylzjljm.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.andypj.xyz/Article/details/gt2soildzhi.html

[F11] 复制与移动文件
来源：http://dali.yanxiufei.cn/Article/details/gt2yksayaft.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2ssmmkjln.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.hywenlv.cn/Article/details/gt2qfbcxbgo.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2zzklycwb.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ewfermra.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.meibo888.top/Article/details/gt2mkwjvwrx.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.cucudq.cn/Article/details/gt2sxlwrkan.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gt2nrbydice.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.sufxvd.cn/Article/details/gt2tujdonzb.html

[F12] CSV 读写
来源：http://dali.ybcxt.top/Article/details/gt2xrgpawzc.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.redwolf501.top/Article/details/gt2zezobifi.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.mhx1999.top/Article/details/gt2nkqoqdqw.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.ybcxt.top/Article/details/gt2jadpbgdq.html

TS:   // 同上
来源：http://dali.yvedp.cn/Article/details/gt2zplrgted.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.iojbl.cn/Article/details/gt2lxzdsmfg.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.tanke756.top/Article/details/gt2dyiykzjr.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.guowangkeji.top/Article/details/gt2ihzzzdcc.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.chenlongwang.top/Article/details/gt2xqysgqcf.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2cvwqbvez.html

G. 面向对象
来源：http://dali.nanxuanxn.top/Article/details/gt2miinejkd.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2wlgwfryr.html

[G01] 定义类
来源：http://dali.kuanghao11.cn/Article/details/gt2vbbvhqoe.html

Py:   class User: pass
来源：http://dali.jiagoushi.top/Article/details/gt2bdenysow.html

PHP:  class User {}
来源：http://dali.ivvv.top/Article/details/gt2fpubjwln.html

JS:   class User {}
来源：http://dali.sxryk.cn/Article/details/gt2dmwcxqtq.html

TS:   class User { name: string = ""; }
来源：http://dali.ppjwa.cn/Article/details/gt2pzsnswnq.html

Java: class User {}
来源：http://dali.hnqzz.top/Article/details/gt2wabvxahd.html

Go:   type User struct { Name string }
来源：http://dali.xziqi.cn/Article/details/gt2vlyvcewl.html

Ruby: class User; end
来源：http://dali.redwolf501.top/Article/details/gt2qzpcffqm.html

C#:   class User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2khtkzoij.html

[G02] 构造函数
来源：http://dali.yuanzhike.top/Article/details/gt2hquqapmo.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.pengpengdd.cyou/Article/details/gt2ihbbzdzb.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.xuanzx.com/Article/details/gt2ykidjvyb.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.quarkkingdee.top/Article/details/gt2dmqhlgwg.html

TS:   constructor(public name: string) {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2dpqthtot.html

Java: User(String name) { this.name = name; }
来源：http://dali.cqqwz.cn/Article/details/gt2nhpmvcay.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.dianchejie.cn/Article/details/gt2xzmiemha.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhixingplan.top/Article/details/gt2ugzbgnjg.html

C#:   public User(string name) { Name = name; }
来源：http://dali.redwolf501.top/Article/details/gt2ixawbyin.html

[G03] 实例属性
来源：http://dali.nanxuanxn.top/Article/details/gt2xaamvski.html

Py:   self.name = "x"
来源：http://dali.hfpthk.cn/Article/details/gt2yfvczzva.html

PHP:  public string $name = "x";
来源：http://dali.cashguo.top/Article/details/gt2ohlhozju.html

JS:   this.name = "x";
来源：http://dali.nanxuanxn.top/Article/details/gt2zqsvqnae.html

TS:   name: string = "x";
来源：http://dali.yuanzhike.top/Article/details/gt2umupebzy.html

Java: private String name;
来源：http://dali.shzxlz.cn/Article/details/gt2fupyugyn.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hnxiangtu.top/Article/details/gt2gdrfxwmx.html

Ruby: @name = "x"
来源：http://dali.yvedp.cn/Article/details/gt2aydoervl.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.daxiang520.top/Article/details/gt2pgueryvq.html

[G04] 定义方法
来源：http://dali.kuanghao11.cn/Article/details/gt2ckrbzzgj.html

Py:   def greet(self): return self.name
来源：http://dali.chenzaomai.com/Article/details/gt2doxxubzl.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.birdmap.top/Article/details/gt2mlxieywx.html

JS:   greet() { return this.name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tdikclaz.html

TS:   greet(): string { return this.name; }
来源：http://dali.yuxming.cn/Article/details/gt2kudauxcv.html

Java: String greet() { return name; }
来源：http://dali.chenlongwang.top/Article/details/gt2zqdtjkek.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.sweek.top/Article/details/gt2nqxaqvzg.html

Ruby: def greet; @name; end
来源：http://dali.sysykeji.top/Article/details/gt2bjqvwfdv.html

C#:   public string Greet() => Name;
来源：http://dali.jinqigufen.top/Article/details/gt2xymxscov.html

[G05] 继承
来源：http://dali.jinqigfzy.top/Article/details/gt2rmnluuns.html

Py:   class Admin(User): pass
来源：http://dali.sweek.top/Article/details/gt2aleeybtm.html

PHP:  class Admin extends User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2isotirpu.html

JS:   class Admin extends User {}
来源：http://dali.jlsjyb.cn/Article/details/gt2spxxugni.html

TS:   class Admin extends User {}
来源：http://dali.ppjwa.cn/Article/details/gt2xjnrktgp.html

Java: class Admin extends User {}
来源：http://dali.zhixingplan.top/Article/details/gt2dslidsfh.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.tianlin.xyz/Article/details/gt2vziwutbm.html

Ruby: class Admin < User; end
来源：http://dali.kuanghao11.cn/Article/details/gt2catpxxhe.html

C#:   class Admin : User {}
来源：http://dali.snrcjt.cn/Article/details/gt2qokhqajm.html

[G06] 重写方法
来源：http://dali.daxiang520.top/Article/details/gt2wagufhka.html

Py:   def greet(self): return "admin"
来源：http://dali.yuanzhike.top/Article/details/gt2dlxuerzb.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yuxming.cn/Article/details/gt2nvmbwatf.html

JS:   greet() { return "admin"; }
来源：http://dali.0kj1m.cn/Article/details/gt2pqgwqhkm.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jqgufenzy.top/Article/details/gt2fdyhqueh.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2bllourwz.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhongyouzk.top/Article/details/gt2abfneikw.html

Ruby: def greet; "admin"; end
来源：http://dali.aizwys.cn/Article/details/gt2nhixfaai.html

C#:   public override string Greet() => "admin";
来源：http://dali.svipenyu.cn/Article/details/gt2gahuceoj.html

[G07] 调用父类方法
来源：http://dali.shzxlz.cn/Article/details/gt2hmpnhscr.html

Py:   super().greet()
来源：http://dali.nanxinkj.top/Article/details/gt2najzjgec.html

PHP:  parent::greet();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hjrpapij.html

JS:   super.greet();
来源：http://dali.yanxiufei.cn/Article/details/gt2aqceaezp.html

TS:   super.greet();
来源：http://dali.dianchejie.cn/Article/details/gt2xqryttpb.html

Java: super.greet();
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2shfbetoz.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jianghu66.top/Article/details/gt2uvqegcgw.html

Ruby: super
来源：http://dali.nanxinkj.top/Article/details/gt2jlqtwkrt.html

C#:   base.Greet();
来源：http://dali.jiagoushi.top/Article/details/gt2wyuhmdki.html

[G08] 静态方法与属性
来源：http://dali.9152youxi.cn/Article/details/gt2zlnwhknf.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xylfe.cn/Article/details/gt2yutsvhwu.html

PHP:  public static function f() {}
来源：http://dali.tanke756.top/Article/details/gt2hgoncfsq.html

JS:   static f() {}
来源：http://dali.hnxiangtu.top/Article/details/gt2aexlvxmz.html

TS:   static f(): void {}
来源：http://dali.gogol.net.cn/Article/details/gt2vlmcqbdt.html

Java: static void f() {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2tpuvkspl.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zdqjudy.top/Article/details/gt2llzsbedo.html

Ruby: def self.f; end
来源：http://dali.wangshuangyany.cn/Article/details/gt2scryjwuu.html

C#:   public static void F() {}
来源：http://dali.andypj.xyz/Article/details/gt2yipqxfsu.html

[G09] 接口 / 抽象类
来源：http://dali.quarkkingdee.top/Article/details/gt2cyhisxtb.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yvedp.cn/Article/details/gt2bxjucnel.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.nwbrower.top/Article/details/gt2nsdmbffv.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.0kj1m.cn/Article/details/gt2eazwbetl.html

TS:   interface Shape { area(): number; }
来源：http://dali.yanxiufei.cn/Article/details/gt2trctclie.html

Java: interface Shape { double area(); }
来源：http://dali.tanke756.top/Article/details/gt2xsrhskik.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mgbrvmap.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.quarkkingdee.top/Article/details/gt2cjrcfpnh.html

C#:   interface IShape { double Area(); }
来源：http://dali.iojbl.cn/Article/details/gt2uqabrpmq.html

[G10] 访问控制
来源：http://dali.ydzc1.top/Article/details/gt2ynohybnq.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yangfankeji.com/Article/details/gt2pirhskrt.html

PHP:  public / protected / private
来源：http://dali.ppjwa.cn/Article/details/gt2ionzofow.html

JS:   #private 字段；其余公开
来源：http://dali.shuidangran.top/Article/details/gt2ohctlcjp.html

TS:   public / protected / private
来源：http://dali.yongpay.top/Article/details/gt2obwdcumn.html

Java: public / protected / private / 默认包级
来源：http://dali.smart0.xyz/Article/details/gt2volztwgj.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qfnaktqo.html

Ruby: public / protected / private
来源：http://dali.sxryk.cn/Article/details/gt2nwhtdiar.html

C#:   public / protected / private / internal
来源：http://dali.hysaishi.cn/Article/details/gt2tfvrhryb.html

[G11] getter / setter
来源：http://dali.meibo888.top/Article/details/gt2hhhrjplj.html

Py:   @property 与 @x.setter
来源：http://dali.smart0.xyz/Article/details/gt2rgcqiwpe.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yj20258.top/Article/details/gt2vwlxmufl.html

JS:   get name() { return this._name; }
来源：http://dali.ivvv.top/Article/details/gt2azucwcro.html

TS:   get name(): string { return this._name; }
来源：http://dali.jlsjyb.cn/Article/details/gt2soogplfr.html

Java: public String getName() { return name; }
来源：http://dali.jyoumei.cn/Article/details/gt2jahfsbgv.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.gogol.net.cn/Article/details/gt2ezycoqtp.html

Ruby: attr_accessor :name
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ytykykmj.html

C#:   public string Name { get; set; }
来源：http://dali.redwolf501.top/Article/details/gt2wapuzxhk.html

[G12] 对象转字符串
来源：http://dali.dianchejie.cn/Article/details/gt2hcuytcqn.html

Py:   def __str__(self): return self.name
来源：http://dali.shuidangran.top/Article/details/gt2kjkkaexn.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jiagoushi.top/Article/details/gt2htrrmrad.html

JS:   toString() { return this.name; }
来源：http://dali.birdmap.top/Article/details/gt2tkkjttow.html

TS:   toString(): string { return this.name; }
来源：http://dali.daria6918.cn/Article/details/gt2anwnqltw.html

Java: @Override public String toString() { return name; }
来源：http://dali.sufxvd.cn/Article/details/gt2rupaxtfu.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.daria6918.cn/Article/details/gt2nvkalaxv.html

Ruby: def to_s; @name; end
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cdrkcovs.html

C#:   public override string ToString() => Name;
来源：http://dali.cheryme.top/Article/details/gt2zztacmsd.html

[G13] 判断对象类型
来源：http://dali.shangyingyoupin.top/Article/details/gt2mrlkgfwx.html

Py:   isinstance(u, User)
来源：http://dali.zycfv.cn/Article/details/gt2djzmrwer.html

PHP:  $u instanceof User
来源：http://dali.yueranfly.top/Article/details/gt2qinxysut.html

JS:   u instanceof User
来源：http://dali.daria6918.cn/Article/details/gt2ndkysrvd.html

TS:   u instanceof User
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tbuhyfby.html

Java: u instanceof User
来源：http://dali.zhiwuduotai.top/Article/details/gt2khjsdusz.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.sufxvd.cn/Article/details/gt2shbxewlp.html

Ruby: u.is_a?(User)
来源：http://dali.zhongyouzk.top/Article/details/gt2twnmjjta.html

C#:   u is User
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pqxpwmvd.html

[G14] 数据类 / record
来源：http://dali.zhiwuduotai.top/Article/details/gt2mjxodsqi.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.wangdashe.top/Article/details/gt2zdspgxnr.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.sxryk.cn/Article/details/gt2svkzopqc.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.kuanghao11.cn/Article/details/gt2nncdpiez.html

TS:   type User = { name: string; age: number };
来源：http://dali.aizwys.cn/Article/details/gt2kgytgcym.html

Java: record User(String name, int age) {}
来源：http://dali.tianlin.xyz/Article/details/gt2dakgeawc.html

Go:   type User struct { Name string; Age int }
来源：http://dali.vqdsnc.cn/Article/details/gt2busukuvd.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.sxryk.cn/Article/details/gt2cbcjfilo.html

C#:   record User(string Name, int Age);
来源：http://dali.cqqwz.cn/Article/details/gt2byujanit.html

[G15] 枚举
来源：http://dali.meibo888.top/Article/details/gt2wqkwnvan.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hnqzz.top/Article/details/gt2hnravtrg.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.tian-w.cn/Article/details/gt2phdhiasw.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.chenlongwang.top/Article/details/gt2ayftqsir.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xinyue.icu/Article/details/gt2gpxzrjtf.html

Java: enum Color { RED, GREEN }
来源：http://dali.yongpay.top/Article/details/gt2tnytoeje.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.tian-w.cn/Article/details/gt2ggsdgbqr.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jyoumei.cn/Article/details/gt2utfrynor.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jlsjyb.cn/Article/details/gt2euwdszbn.html

[G16] 对象转数组 / 字典
来源：http://dali.quarkkingdee.top/Article/details/gt2xkzshpee.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.svipenyu.cn/Article/details/gt2hgptapwv.html

PHP:  get_object_vars($obj);
来源：http://dali.0kj1m.cn/Article/details/gt2mbfvhwaw.html

JS:   Object.entries(obj)
来源：http://dali.yueranfly.top/Article/details/gt2ispqabym.html

TS:   Object.entries(obj)
来源：http://dali.havefunace.top/Article/details/gt2hysmyynd.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yuxming.cn/Article/details/gt2igrlozpy.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.hnqzz.top/Article/details/gt2vcimqndh.html

Ruby: obj.instance_variables
来源：http://dali.hnxiangtu.top/Article/details/gt2ajccwxzg.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.shuidangran.top/Article/details/gt2frqbpjca.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2genseehn.html

H. 异常与错误处理
来源：http://dali.aizwys.cn/Article/details/gt2rqvlakcj.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2xnkoclsf.html

[H01] try / catch 基础
来源：http://dali.yuxming.cn/Article/details/gt2hiafyequ.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.9152youxi.cn/Article/details/gt2brnnvmuu.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.hnqzz.top/Article/details/gt2opfytkxn.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.c1oappe.top/Article/details/gt2hkjodzht.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.andypj.xyz/Article/details/gt2gxobpsvf.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.wangdashe.top/Article/details/gt2mpciygyf.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.xziqi.cn/Article/details/gt2iiieqnau.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.mhx1999.top/Article/details/gt2lkbkhxbm.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jianghu66.top/Article/details/gt2rvjprhnw.html

[H02] finally / ensure 收尾
来源：http://dali.cqqwz.cn/Article/details/gt2lnzhjdlf.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.xylfe.cn/Article/details/gt2ozntnnka.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.316326.xyz/Article/details/gt2isgfbhfv.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.hnxiangtu.top/Article/details/gt2bqzbvvjs.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.aibaodan.cn/Article/details/gt2sayoprcq.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.tanke756.top/Article/details/gt2lllmwype.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.cqqwz.cn/Article/details/gt2hpimcrdg.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yvedp.cn/Article/details/gt2vesmmaou.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yueranfly.top/Article/details/gt2zygyijbq.html

[H03] 主动抛出异常
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jnkddjst.html

Py:   raise ValueError("错误信息")
来源：http://dali.jqgufenzy.top/Article/details/gt2gdmhzjxn.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jlsjyb.cn/Article/details/gt2rrtrvmcj.html

JS:   throw new Error("错误信息");
来源：http://dali.nanxuanxn.top/Article/details/gt2sfyurvrk.html

TS:   throw new Error("错误信息");
来源：http://dali.jiagoushi.top/Article/details/gt2kleaklsi.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2prdqjhvf.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.vqdsnc.cn/Article/details/gt2udcrcizx.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhongyouzk.top/Article/details/gt2kzyyqwii.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.sxryk.cn/Article/details/gt2ktevlkrn.html

[H04] 自定义异常类型
来源：http://dali.tian-w.cn/Article/details/gt2vjhzjkak.html

Py:   class MyError(Exception): pass
来源：http://dali.sweek.top/Article/details/gt2jxrlqgkt.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bumfdwdj.html

JS:   class MyError extends Error {}
来源：http://dali.meibo888.top/Article/details/gt2ziwkrejn.html

TS:   class MyError extends Error {}
来源：http://dali.dianchejie.cn/Article/details/gt2mbrzusqf.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jlsjyb.cn/Article/details/gt2bmylcxoh.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yuanzhike.top/Article/details/gt2ptjqblth.html

Ruby: class MyError < StandardError; end
来源：http://dali.fengsongda.top/Article/details/gt2ynnnwery.html

C#:   class MyException : Exception {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2zugunlqz.html

[H05] 捕获特定类型
来源：http://dali.jyoumei.cn/Article/details/gt2ijpfwpyu.html

Py:   except ValueError as e:
来源：http://dali.xziqi.cn/Article/details/gt2eqkyaypc.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.meibo888.top/Article/details/gt2wvqqfocv.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zhoulong.xyz/Article/details/gt2vmrcmzhp.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.aizwys.cn/Article/details/gt2gfydatzj.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jiagoushi.top/Article/details/gt2tbunlvyb.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zdqjudy.top/Article/details/gt2zvonmzeb.html

Ruby: rescue ArgumentError => e
来源：http://dali.zycfv.cn/Article/details/gt2vdpafimx.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.0kj1m.cn/Article/details/gt2rpxaaoxy.html

[H06] 可选值 / 空值安全访问
来源：http://dali.chenjidiqi.icu/Article/details/gt2zlxnziht.html

Py:   value = d.get("k") or default
来源：http://dali.zhiwuduotai.top/Article/details/gt2zjfkzbra.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.shzxlz.cn/Article/details/gt2zqkudkfe.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.dianchejie.cn/Article/details/gt2paphuxut.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.havefunace.top/Article/details/gt2ogjrrakn.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.pycfn.com/Article/details/gt2jlnhknyr.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.xinyue.icu/Article/details/gt2ixcmkdga.html

Ruby: d&.dig(:a, :b)
来源：http://dali.birdmap.top/Article/details/gt2ddljhmgv.html

C#:   obj?.A?.B ?? default
来源：http://dali.sxryk.cn/Article/details/gt2hkezqizv.html

[H07] 断言
来源：http://dali.pycfn.com/Article/details/gt2zkduyuqq.html

Py:   assert x > 0, "必须为正"
来源：http://dali.xuanzx.com/Article/details/gt2qnewpozf.html

PHP:  assert($x > 0);
来源：http://dali.nwbrower.top/Article/details/gt2gwpxvjhh.html

JS:   console.assert(x > 0);
来源：http://dali.aizwys.cn/Article/details/gt2gjfimgiv.html

TS:   console.assert(x > 0);
来源：http://dali.jianghu66.top/Article/details/gt2suqtkqmk.html

Java: assert x > 0 : "必须为正";
来源：http://dali.vqdsnc.cn/Article/details/gt2rtwhphyy.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.guannengcc.top/Article/details/gt2koyfastz.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yuanzhike.top/Article/details/gt2xmmjelrt.html

C#:   Debug.Assert(x > 0);
来源：http://dali.aibaodan.cn/Article/details/gt2euezfbne.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhijiandao.cn/Article/details/gt2eibbvxsh.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yj20258.top/Article/details/gt2ovzyfruv.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.xziqi.cn/Article/details/gt2eifcvgtg.html

JS:   e.message;  e.stack
来源：http://dali.hongshengwenyu.top/Article/details/gt2txeabssh.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.snrcjt.cn/Article/details/gt2gwzdzxnz.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.kuanghao11.cn/Article/details/gt2jxoculqe.html

Go:   err.Error()
来源：http://dali.nwbrower.top/Article/details/gt2eruwrugg.html

Ruby: e.message;  e.backtrace
来源：http://dali.nwbrower.top/Article/details/gt2taucvqks.html

C#:   e.Message;  e.StackTrace
来源：http://dali.gotoacloud.top/Article/details/gt2rnadyyzr.html

[H09] 带错误码的异常
来源：http://dali.chenzaomai.com/Article/details/gt2lpmajdpw.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.ybcxt.top/Article/details/gt2jvlmwggj.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.sysykeji.top/Article/details/gt2nvmqxsmo.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jianghu66.top/Article/details/gt2ydvogbce.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.zhijiandao.cn/Article/details/gt2htspzpvm.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.havefunace.top/Article/details/gt2gibcrync.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yj20258888.top/Article/details/gt2ueejgymv.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.hywenlv.cn/Article/details/gt2uvjpwcfj.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.cashguo.top/Article/details/gt2bgwijnpm.html

[H10] 资源自动释放
来源：http://dali.guowangkeji.top/Article/details/gt2csynshfb.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yuanzhike.top/Article/details/gt2yucshedr.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.316326.xyz/Article/details/gt2bqaquokf.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhijiandao.cn/Article/details/gt2vvvtmngx.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.nanxuanxn.top/Article/details/gt2hkxwmwkf.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.shuidangran.top/Article/details/gt2wblcuigr.html

Go:   defer f.Close()
来源：http://dali.wangdashe.top/Article/details/gt2dsijxskq.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.wangdashe.top/Article/details/gt2iipinseg.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.ydzc1.top/Article/details/gt2nyydzkoh.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2holluyeg.html

I. 正则表达式
来源：http://dali.andypj.xyz/Article/details/gt2yduxxtby.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2yeqemmmr.html

[I01] 判断是否匹配
来源：http://dali.aizwys.cn/Article/details/gt2ikrexyvu.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.cheryme.top/Article/details/gt2gdqexjsy.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.gzhubu.top/Article/details/gt2dfhubidg.html

JS:   /\d+/.test(s)
来源：http://dali.dashuyun.cn/Article/details/gt2xaltdekr.html

TS:   /\d+/.test(s)
来源：http://dali.gaohongyu789.top/Article/details/gt2dffqohpz.html


<!-- 参考信息 -->