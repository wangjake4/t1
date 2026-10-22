代发 wailian999

C#:   File.Exists("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtxxephsyh.html

[F06] 删除文件
来源：http://dali.xylfe.cn/Article/details/gtsharammu.html

Py:   os.remove("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtuyulbzpq.html

PHP:  unlink("a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gtiqfmebhz.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtllmcedhf.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtxpmvkrpe.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.chenjidiqi.icu/Article/details/gtncctdhiv.html

Go:   os.Remove("a.txt")
来源：http://dali.yj20258.top/Article/details/gtqkzfatxt.html

Ruby: File.delete("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtyhziytac.html

C#:   File.Delete("a.txt");
来源：http://dali.cqqwz.cn/Article/details/gtnzjnpzdn.html

[F07] 创建目录（含多级）
来源：http://dali.chenlongwang.top/Article/details/gtsediwuwh.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.cheryme.top/Article/details/gtdfovxpon.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yongpay.top/Article/details/gtkwuvzuju.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.daxiang520.top/Article/details/gtltwwymsf.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gogol.net.cn/Article/details/gtxkbjalob.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbvtucfxt.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.xylfe.cn/Article/details/gtgqcledxb.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.xuanzx.com/Article/details/gtmmsxzfeg.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.fzhhl.top/Article/details/gtdnqobxtu.html

[F08] 遍历目录
来源：http://dali.hfpthk.cn/Article/details/gtwrfsdmmt.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.0kj1m.cn/Article/details/gtnyavwvvb.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhoulong.xyz/Article/details/gtwadepygp.html

JS:   fs.readdirSync("dir")
来源：http://dali.jlsjyb.cn/Article/details/gtekdbolrl.html

TS:   fs.readdirSync("dir")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlsrjwknw.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.dianchejie.cn/Article/details/gtaqijffcj.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yueranfly.top/Article/details/gtllfmxbgv.html

Ruby: Dir.children("dir")
来源：http://dali.andypj.xyz/Article/details/gtplpgvnxu.html

C#:   Directory.GetFiles("dir")
来源：http://dali.xuanzx.com/Article/details/gtlytsmybw.html

[F09] 获取文件大小
来源：http://dali.ydzc1.top/Article/details/gtbsdbjotp.html

Py:   os.path.getsize("a.txt")
来源：http://dali.hammf.cn/Article/details/gthwoixfib.html

PHP:  filesize("a.txt");
来源：http://dali.daria6918.cn/Article/details/gtrsfysewn.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jinyuanbaomall.cn/Article/details/gtevulnxpp.html

TS:   fs.statSync("a.txt").size
来源：http://dali.feifeiyinyue.top/Article/details/gteyazxoqb.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.sufxvd.cn/Article/details/gtbsgbnvma.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.aibaodan.cn/Article/details/gtndotxgha.html

Ruby: File.size("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtmoxeyuse.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.sxryk.cn/Article/details/gtnqujoaab.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yj20258888.top/Article/details/gtnfqvulpv.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtqtfzfjgo.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gtakfcuvuu.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtwwjqdxfi.html

TS:   path.extname("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtdoujcowj.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.gotoacloud.top/Article/details/gtvgojxgvy.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.daxiang520.top/Article/details/gtmkkvhayd.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gttzjlmbod.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtszqcavda.html

[F11] 复制与移动文件
来源：http://dali.yvedp.cn/Article/details/gtdblqsujn.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtickosgkp.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.ehwqpu.com/Article/details/gtucmswymr.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.aizwys.cn/Article/details/gtyoczotpe.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shzxlz.cn/Article/details/gtmxpovdcv.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jlsjyb.cn/Article/details/gtvgzlfvih.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.cqqwz.cn/Article/details/gtxbeddpqa.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.andypj.xyz/Article/details/gtlisqsutj.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yj202588.top/Article/details/gtbllayzfv.html

[F12] CSV 读写
来源：http://dali.xinyue.icu/Article/details/gturijgjle.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhongyouzk.top/Article/details/gtcwllnjts.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jiagoushi.top/Article/details/gtaqmyfzuy.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hfpthk.cn/Article/details/gtxixhhdjj.html

TS:   // 同上
来源：http://dali.gaohongyu789.top/Article/details/gtnjhhvyqz.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.nwbrower.top/Article/details/gtcnbwrezc.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhongyouzk.top/Article/details/gtpgrfjtiw.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.dashuyun.cn/Article/details/gtiombubpp.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.ppjwa.cn/Article/details/gthnfxjqbq.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtfaqvxabf.html

G. 面向对象
来源：http://dali.jinqigufen.top/Article/details/gtoctqpywe.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtxiaxsdnm.html

[G01] 定义类
来源：http://dali.yangfankeji.com/Article/details/gtcdvyemlf.html

Py:   class User: pass
来源：http://dali.wangshuangyany.cn/Article/details/gtqwccdnak.html

PHP:  class User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgtrglmiu.html

JS:   class User {}
来源：http://dali.sweek.top/Article/details/gttxmepyfx.html

TS:   class User { name: string = ""; }
来源：http://dali.ybcxt.top/Article/details/gtvnfrocos.html

Java: class User {}
来源：http://dali.zhiwuduotai.top/Article/details/gtcuvprheu.html

Go:   type User struct { Name string }
来源：http://dali.yueranfly.top/Article/details/gtwmbwfhhw.html

Ruby: class User; end
来源：http://dali.jinqigufen.top/Article/details/gtrmvxzbbl.html

C#:   class User {}
来源：http://dali.yuxming.cn/Article/details/gtcvpszpsv.html

[G02] 构造函数
来源：http://dali.daxiang520.top/Article/details/gtwwuyiqci.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zdqjudy.top/Article/details/gttijqydxv.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtskhalsyu.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.shzxlz.cn/Article/details/gtfpozvyxl.html

TS:   constructor(public name: string) {}
来源：http://dali.jinqigfzy.top/Article/details/gtynsaqnhk.html

Java: User(String name) { this.name = name; }
来源：http://dali.shuidangran.top/Article/details/gtkteigmtb.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.xziqi.cn/Article/details/gthjdvorxo.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.ppjwa.cn/Article/details/gtdmvzhvyv.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtbwuqotlz.html

[G03] 实例属性
来源：http://dali.birdmap.top/Article/details/gtcbthabqu.html

Py:   self.name = "x"
来源：http://dali.daria6918.cn/Article/details/gtbfjrobfl.html

PHP:  public string $name = "x";
来源：http://dali.wangdashe.top/Article/details/gtxywdgnlm.html

JS:   this.name = "x";
来源：http://dali.316326.xyz/Article/details/gtswxnevti.html

TS:   name: string = "x";
来源：http://dali.fengsongda.top/Article/details/gtcukjxeqx.html

Java: private String name;
来源：http://dali.fzhhl.top/Article/details/gteaxlmwqg.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.xylfe.cn/Article/details/gtxfzvevij.html

Ruby: @name = "x"
来源：http://dali.wangshuangyany.cn/Article/details/gtwcglzaxn.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.cucudq.cn/Article/details/gtjmmuiwln.html

[G04] 定义方法
来源：http://dali.yj202588.top/Article/details/gtoualpole.html

Py:   def greet(self): return self.name
来源：http://dali.chenjidiqi.icu/Article/details/gttdylhvmb.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtidpypwwl.html

JS:   greet() { return this.name; }
来源：http://dali.yangfankeji.com/Article/details/gtygvpazud.html

TS:   greet(): string { return this.name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtamkuyqmx.html

Java: String greet() { return name; }
来源：http://dali.jinqigufen.top/Article/details/gtmmtkvrzd.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yj202588.top/Article/details/gtgkyzpgjf.html

Ruby: def greet; @name; end
来源：http://dali.cashguo.top/Article/details/gtiubjldwv.html

C#:   public string Greet() => Name;
来源：http://dali.shzxlz.cn/Article/details/gtkyjfizvd.html

[G05] 继承
来源：http://dali.quarkkingdee.top/Article/details/gtfyzgaehq.html

Py:   class Admin(User): pass
来源：http://dali.pengpengdd.cyou/Article/details/gtvzysxfbj.html

PHP:  class Admin extends User {}
来源：http://dali.shzxlz.cn/Article/details/gtulnotclg.html

JS:   class Admin extends User {}
来源：http://dali.zhiwuduotai.top/Article/details/gtngnfzvja.html

TS:   class Admin extends User {}
来源：http://dali.sxryk.cn/Article/details/gtkmeflaux.html

Java: class Admin extends User {}
来源：http://dali.hfpthk.cn/Article/details/gtamisvwnn.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.guannengcc.top/Article/details/gtjfwdwnqs.html

Ruby: class Admin < User; end
来源：http://dali.kuanghao11.cn/Article/details/gtbzuvlnwh.html

C#:   class Admin : User {}
来源：http://dali.pengpengdd.cyou/Article/details/gtzhtpwncf.html

[G06] 重写方法
来源：http://dali.cucudq.cn/Article/details/gtmjlksqac.html

Py:   def greet(self): return "admin"
来源：http://dali.haohaochexian.top/Article/details/gtnkntnppv.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.pycfn.com/Article/details/gtglapoljf.html

JS:   greet() { return "admin"; }
来源：http://dali.zhoulong.xyz/Article/details/gtucfazjtw.html

TS:   greet(): string { return "admin"; }
来源：http://dali.daxiang520.top/Article/details/gtnrjxvgco.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.shzxlz.cn/Article/details/gtcrfpeskv.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yueranfly.top/Article/details/gtrcswpdcn.html

Ruby: def greet; "admin"; end
来源：http://dali.sweek.top/Article/details/gtqqfvrlfz.html

C#:   public override string Greet() => "admin";
来源：http://dali.ivvv.top/Article/details/gtnnvtrscj.html

[G07] 调用父类方法
来源：http://dali.jlsjyb.cn/Article/details/gtazhchxab.html

Py:   super().greet()
来源：http://dali.sufxvd.cn/Article/details/gtbarspecx.html

PHP:  parent::greet();
来源：http://dali.snrcjt.cn/Article/details/gtdyrffltt.html

JS:   super.greet();
来源：http://dali.jqgufenzy.top/Article/details/gtwyfoxano.html

TS:   super.greet();
来源：http://dali.hnqzz.top/Article/details/gtafegikzm.html

Java: super.greet();
来源：http://dali.fzhhl.top/Article/details/gtnptdoeby.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jianghu66.top/Article/details/gtvyuzeenk.html

Ruby: super
来源：http://dali.xuetiantiany.cn/Article/details/gtftakhtuv.html

C#:   base.Greet();
来源：http://dali.cheryme.top/Article/details/gtfkfkypem.html

[G08] 静态方法与属性
来源：http://dali.haohaochexian.top/Article/details/gtyltfothh.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jinqigfzy.top/Article/details/gttnnjhppq.html

PHP:  public static function f() {}
来源：http://dali.c1oappe.top/Article/details/gttrotzndu.html

JS:   static f() {}
来源：http://dali.fengsongda.top/Article/details/gtqgtxwbop.html

TS:   static f(): void {}
来源：http://dali.pycfn.com/Article/details/gtcotbrhwp.html

Java: static void f() {}
来源：http://dali.cqqwz.cn/Article/details/gtuensgcxh.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.bjfxy.top/Article/details/gtuanaktmj.html

Ruby: def self.f; end
来源：http://dali.shuidangran.top/Article/details/gtpxyrkbdz.html

C#:   public static void F() {}
来源：http://dali.chenjidiqi.icu/Article/details/gtvllbyads.html

[G09] 接口 / 抽象类
来源：http://dali.yueranfly.top/Article/details/gttiyvgqqa.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.quarkkingdee.top/Article/details/gtaqfnzfym.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.cashguo.top/Article/details/gthbzxlyiv.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.vqdsnc.cn/Article/details/gtpvceeorb.html

TS:   interface Shape { area(): number; }
来源：http://dali.chenzaomai.com/Article/details/gtdbyjcymi.html

Java: interface Shape { double area(); }
来源：http://dali.hnxiangtu.top/Article/details/gtmwaealew.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.cdnleiting.top/Article/details/gtilcqnsqt.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.chenjidiqi.icu/Article/details/gtwlnresej.html

C#:   interface IShape { double Area(); }
来源：http://dali.redwolf501.top/Article/details/gtoajcidjs.html

[G10] 访问控制
来源：http://dali.jinqigfzy.top/Article/details/gtwxgzttmj.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.aibaodan.cn/Article/details/gteqjevfec.html

PHP:  public / protected / private
来源：http://dali.dianchejie.cn/Article/details/gtgexhffbm.html

JS:   #private 字段；其余公开
来源：http://dali.ivvv.top/Article/details/gtchfuubzw.html

TS:   public / protected / private
来源：http://dali.yonumen.top/Article/details/gtkpbbvhwq.html

Java: public / protected / private / 默认包级
来源：http://dali.yvedp.cn/Article/details/gtwraazupo.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.gogol.net.cn/Article/details/gtpzmzbqfr.html

Ruby: public / protected / private
来源：http://dali.shanyushiyangtech.top/Article/details/gthblrzyke.html

C#:   public / protected / private / internal
来源：http://dali.jyoumei.cn/Article/details/gtokzsooie.html

[G11] getter / setter
来源：http://dali.svipenyu.cn/Article/details/gtybiottvi.html

Py:   @property 与 @x.setter
来源：http://dali.zhongyouzk.top/Article/details/gtooneebrb.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvjnztvgo.html

JS:   get name() { return this._name; }
来源：http://dali.cheryme.top/Article/details/gtdwhyikis.html

TS:   get name(): string { return this._name; }
来源：http://dali.ppjwa.cn/Article/details/gtpvtyyrrd.html

Java: public String getName() { return name; }
来源：http://dali.yuanzhike.top/Article/details/gtkmmjpdhj.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.hfpthk.cn/Article/details/gtbpdptccq.html

Ruby: attr_accessor :name
来源：http://dali.jqgufenzy.top/Article/details/gtcpjkjmji.html

C#:   public string Name { get; set; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrvuekpbp.html

[G12] 对象转字符串
来源：http://dali.hammf.cn/Article/details/gtvuyffslw.html

Py:   def __str__(self): return self.name
来源：http://dali.jlsjyb.cn/Article/details/gtifxvnenc.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtbwrrcjfi.html

JS:   toString() { return this.name; }
来源：http://dali.hywenlv.cn/Article/details/gtmwdocnqg.html

TS:   toString(): string { return this.name; }
来源：http://dali.yvedp.cn/Article/details/gthevxyfdj.html

Java: @Override public String toString() { return name; }
来源：http://dali.xuanzx.com/Article/details/gtjzyboxqc.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.daxiang520.top/Article/details/gtuzdosagd.html

Ruby: def to_s; @name; end
来源：http://dali.birdmap.top/Article/details/gtjxkgqmrr.html

C#:   public override string ToString() => Name;
来源：http://dali.yj20258888.top/Article/details/gtseiktxlj.html

[G13] 判断对象类型
来源：http://dali.ydzc1.top/Article/details/gtrrczzdph.html

Py:   isinstance(u, User)
来源：http://dali.yongpay.top/Article/details/gtoquhcdaj.html

PHP:  $u instanceof User
来源：http://dali.shanyushiyangkeji.top/Article/details/gtihhngmrp.html

JS:   u instanceof User
来源：http://dali.hywenlv.cn/Article/details/gtsrydfeqc.html

TS:   u instanceof User
来源：http://dali.0kj1m.cn/Article/details/gtxjlmhgjm.html

Java: u instanceof User
来源：http://dali.yj20258888.top/Article/details/gthudhjfkw.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.iojbl.cn/Article/details/gtvswiycrw.html

Ruby: u.is_a?(User)
来源：http://dali.cashguo.top/Article/details/gtbvhmjcmz.html

C#:   u is User
来源：http://dali.mhx1999.top/Article/details/gtdcksxeav.html

[G14] 数据类 / record
来源：http://dali.mhx1999.top/Article/details/gtujagcrcw.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.sufxvd.cn/Article/details/gtsmubyhzs.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.chenjidiqi.icu/Article/details/gtlmnfqmun.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jqgufenzy.top/Article/details/gterksybou.html

TS:   type User = { name: string; age: number };
来源：http://dali.guowangkeji.top/Article/details/gtklvwczgu.html

Java: record User(String name, int age) {}
来源：http://dali.yj20258888.top/Article/details/gtxiutzimn.html

Go:   type User struct { Name string; Age int }
来源：http://dali.vqdsnc.cn/Article/details/gtzwoqjnlv.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.9152youxi.cn/Article/details/gtslxttfie.html

C#:   record User(string Name, int Age);
来源：http://dali.yj202588.top/Article/details/gtthjrrgmm.html

[G15] 枚举
来源：http://dali.ivvv.top/Article/details/gtxgwekstl.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hfpthk.cn/Article/details/gtlzlvquxp.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtygyeexqh.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.9152youxi.cn/Article/details/gthhuublgj.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jyoumei.cn/Article/details/gtykjkfwsr.html

Java: enum Color { RED, GREEN }
来源：http://dali.chenzaomai.com/Article/details/gtykhvyxqq.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yongpay.top/Article/details/gtlghfdmom.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jinyuanbaomall.cn/Article/details/gthufutqlf.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shanyushiyangtech.top/Article/details/gtqhifgubf.html

[G16] 对象转数组 / 字典
来源：http://dali.cdnleiting.top/Article/details/gtbnahcfwk.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.dashuyun.cn/Article/details/gtiedixhks.html

PHP:  get_object_vars($obj);
来源：http://dali.jinqigfzy.top/Article/details/gtdadjodbm.html

JS:   Object.entries(obj)
来源：http://dali.shuidangran.top/Article/details/gtjewfolcj.html

TS:   Object.entries(obj)
来源：http://dali.guannengcc.top/Article/details/gtxutcwjqr.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yj20258888.top/Article/details/gtwyvllbwl.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jinqigufen.top/Article/details/gtgigimxvi.html

Ruby: obj.instance_variables
来源：http://dali.ybcxt.top/Article/details/gtmtrrzlqp.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.fzhhl.top/Article/details/gtmlbhcwdy.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtsshjujqg.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gtdpgufaoe.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtwikhewtk.html

[H01] try / catch 基础
来源：http://dali.nanxinkj.top/Article/details/gtppuauatc.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yj20258888.top/Article/details/gtmsmcidkv.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.316326.xyz/Article/details/gttzhuleqw.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hnxiangtu.top/Article/details/gtdgmyzcud.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zdqjudy.top/Article/details/gtxfefzgil.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhengqikj.top/Article/details/gtxtzgjwmy.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hammf.cn/Article/details/gtkywrafzt.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.daria6918.cn/Article/details/gtjhvrqetc.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.shuidangran.top/Article/details/gtrxotwcde.html

[H02] finally / ensure 收尾
来源：http://dali.svipenyu.cn/Article/details/gtqletrfhc.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.ybcxt.top/Article/details/gtzagkzxve.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hysaishi.cn/Article/details/gtokypsmwn.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwefqivls.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinqigfzy.top/Article/details/gthhhgcbwv.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.hammf.cn/Article/details/gtvixkgwbm.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yonumen.top/Article/details/gtjdwdzcve.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jqgfzy.top/Article/details/gthqbqmgnh.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jlsjyb.cn/Article/details/gtstntsraj.html

[H03] 主动抛出异常
来源：http://dali.nanxuanxn.top/Article/details/gtrwnezaxm.html

Py:   raise ValueError("错误信息")
来源：http://dali.svipenyu.cn/Article/details/gtkejqzuug.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.nanxinkj.top/Article/details/gtshlvrkrj.html

JS:   throw new Error("错误信息");
来源：http://dali.cashguo.top/Article/details/gtwytuvsjh.html

TS:   throw new Error("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gtwbkujqdq.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.pengpengdd.cyou/Article/details/gtveffxssk.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.wangshuangyany.cn/Article/details/gtfirwrnal.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.shanyushiyangtech.top/Article/details/gtcwhxzemf.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhongyouzk.top/Article/details/gtbuhcsybs.html

[H04] 自定义异常类型
来源：http://dali.guowangkeji.top/Article/details/gtsqujfnfy.html

Py:   class MyError(Exception): pass
来源：http://dali.nanxuanxn.top/Article/details/gtwnodurlm.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jinqigufen.top/Article/details/gtlceqzdda.html

JS:   class MyError extends Error {}
来源：http://dali.aizwys.cn/Article/details/gtczmrdxyf.html

TS:   class MyError extends Error {}
来源：http://dali.mhx1999.top/Article/details/gtkoybitww.html

Java: class MyException extends RuntimeException {}
来源：http://dali.xinyue.icu/Article/details/gtmeyulnfo.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yuxming.cn/Article/details/gtjvushotb.html

Ruby: class MyError < StandardError; end
来源：http://dali.mhx1999.top/Article/details/gtlzoxuted.html

C#:   class MyException : Exception {}
来源：http://dali.haohaochexian.top/Article/details/gtwbzayfen.html

[H05] 捕获特定类型
来源：http://dali.daria6918.cn/Article/details/gtrzbracwj.html

Py:   except ValueError as e:
来源：http://dali.nwbrower.top/Article/details/gtsirjyawp.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.fzhhl.top/Article/details/gttanjofec.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yj20258888.top/Article/details/gtqeadfykb.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtezzsptnx.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.316326.xyz/Article/details/gtvrodndnj.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.shanyushiyangtech.top/Article/details/gtnnkhagom.html

Ruby: rescue ArgumentError => e
来源：http://dali.pycfn.com/Article/details/gtvqdlfsry.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jinqigufen.top/Article/details/gtkofxmsas.html

[H06] 可选值 / 空值安全访问
来源：http://dali.redwolf501.top/Article/details/gtmiqajhwp.html

Py:   value = d.get("k") or default
来源：http://dali.jinqigufen.top/Article/details/gtoembwmdk.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.tanke756.top/Article/details/gttnnzebne.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jiagoushi.top/Article/details/gtcrpzhvqb.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.fengsongda.top/Article/details/gtfgyzfmdh.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqhwedjqz.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.xylfe.cn/Article/details/gtadzxikcx.html

Ruby: d&.dig(:a, :b)
来源：http://dali.xuanzx.com/Article/details/gtkagheuow.html

C#:   obj?.A?.B ?? default
来源：http://dali.hywenlv.cn/Article/details/gtwwhxfrll.html

[H07] 断言
来源：http://dali.feifeiyinyue.top/Article/details/gtexvfnmbf.html

Py:   assert x > 0, "必须为正"
来源：http://dali.fengsongda.top/Article/details/gtutgblxox.html

PHP:  assert($x > 0);
来源：http://dali.sysykeji.top/Article/details/gtgvdpbgcw.html

JS:   console.assert(x > 0);
来源：http://dali.shanyushiyangtech.top/Article/details/gtvcsrymdp.html

TS:   console.assert(x > 0);
来源：http://dali.zhengqikj.top/Article/details/gtbjolbusf.html

Java: assert x > 0 : "必须为正";
来源：http://dali.xziqi.cn/Article/details/gtpukaihep.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.daria6918.cn/Article/details/gthyoqbphf.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.xziqi.cn/Article/details/gtjxfnxblu.html

C#:   Debug.Assert(x > 0);
来源：http://dali.ivvv.top/Article/details/gtjhltibgc.html

[H08] 获取错误信息与堆栈
来源：http://dali.svipenyu.cn/Article/details/gtnqsxlzwt.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.sxryk.cn/Article/details/gttyxinupk.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.tianlin.xyz/Article/details/gtjhgmlekm.html

JS:   e.message;  e.stack
来源：http://dali.ppjwa.cn/Article/details/gtzbkekhow.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.chenlongwang.top/Article/details/gtqovatnyi.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jiagoushi.top/Article/details/gtgscmijmc.html

Go:   err.Error()
来源：http://dali.jinqigufen.top/Article/details/gtzpcrlkor.html

Ruby: e.message;  e.backtrace
来源：http://dali.wangdashe.top/Article/details/gtgaunxpid.html

C#:   e.Message;  e.StackTrace
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbyjmdnrn.html

[H09] 带错误码的异常
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtscpmpmpa.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhoulong.xyz/Article/details/gtibpvaxfa.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtippwebbi.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhixingplan.top/Article/details/gtuydrjxnx.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.nanxuanxn.top/Article/details/gtipnyytyt.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yonumen.top/Article/details/gtvgrssmdu.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.bjfxy.top/Article/details/gtfgqohacq.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.shanyushiyangtech.top/Article/details/gteykxbpgq.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yongpay.top/Article/details/gtqmbcnugm.html

[H10] 资源自动释放
来源：http://dali.shuidangran.top/Article/details/gtvqwobuip.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.0kj1m.cn/Article/details/gtgbgmlhad.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.zycfv.cn/Article/details/gtagqdlray.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.sufxvd.cn/Article/details/gtvkmmjwhm.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jiagoushi.top/Article/details/gtafzwmpfh.html


<!-- 参考信息 -->